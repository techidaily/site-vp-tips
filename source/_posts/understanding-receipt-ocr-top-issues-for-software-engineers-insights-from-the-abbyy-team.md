---
title: "Understanding Receipt OCR: Top Issues for Software Engineers - Insights From the ABBYY Team"
date: 2024-08-20 11:33:51
updated: 2024-08-22 12:32:38
categories:
  - abbyy
thumbnail: https://thmb.techidaily.com/581e555a79746fa6146e452431e04adcc0fe595ec9a8fe5547dd855a218b2d27.jpg
---

## Understanding Receipt OCR: Top Issues for Software Engineers - Insights From the ABBYY Team

[Back to ABBYY Blog](https://tools.techidaily.com/abbyy/products/)

## Top 5 Pains for Developers in Receipt OCR

December 22, 2015

![abbyy cloud ocr sdk | ABBYY Blog Post](https://static4.abbyy.com/abbyycommedia/28766/ocrsdk-visual-default.jpg) 

Receipt processing holds much promise today. Resource savings in handling business expenses reports, effective loyalty programs, and control over personal finances are just some of the opportunities that receipt data capture can offer. However developing receipts processing is anything but simple.

Here are some of the most common pains for developers in receipt capture:

* Poor quality of paper, print, and photo.
* No well-defined receipt structure or common receipt template.
* Local country specifics of receipts.
* Failure in keyword search due to OCR errors.
* Difficulty in gathering enough receipt samples.

We’d like to share ABBYY’s long-term experience in receipt capture development and take a closer look at these pains.

## 1\. Poor quality of paper, print, and photo

Big challenge #1 is pale, illegible text. Along with easy crumpling and fading paper and blurred angled photos (when taken with a mobile phone) it makes it hard to recognize the characters.

[![pale text](https://static1.abbyy.com/abbyycommedia/25812/1-11-216x300.png)](http://blog.ocrsdk.com/wp-content/uploads/2015/12/1-11.png)

This problem can be solved (and it is solved this way in ABBYY Receipt Capture SDK) with enhanced image pre-processing. This allows for a strong increase in recognition accuracy – thanks to the contrast adjustment, image adaptive binarization (image conversion from color/grayscale to black & white), skew correction and line straightening – and thus makes a half of the job done.

## 2\. Failure in keyword search due to OCR errors

Letters in a receipt can be too thin or jammed together so at the OCR stage some characters could be mistranscribed, for instance, “O” could be recognized as “C”. A misspelled word fails to match the correct keyword (which helps identify data with a relevant field), so its search and capture becomes impossible in automatic mode. The way out is to use a fuzzy search which involves looking for the keywords in the recognized text, taking into account possible mistakes in their spelling that appeared during the OCR stage. Thanks to this feature, the mistranscribed word “TCTAL” will be identified with the keyword “TOTAL” and the corresponding sum will be matched with the proper field. 

At the same time it’s important not to do this search too fuzzy, as otherwise keywords will be found everywhere. Thus the balanced fuzzy search is a significant part of the technology, the real know-how for increasing the accuracy of receipt capture.

Text loss at the OCR stage is another challenge. It may impact the whole receipt processing while a keyword loss definitely decreases the accuracy of receipt capture. This problem may be solved by consideration and analysis of all the possible text blocks using a tool called aggressive search. In that case everything that resembles text – small print, caption under a picture or logo etc. – is recognized. Implementation of this tool has a side effect, possibly bringing excess text and “garbage” into the results which, however, may be classified and rejected during the following steps. Nevertheless, an aggressive search secures against any text loss and extends the accuracy of receipt processing.

## 3\. No well-defined receipt structure or common receipt template

The application should not only recognize a document and extract information from it, but also use this information properly, i.e. “understand” which figure in the receipt is, say, the total sum of your purchase and which word relates to the vendor name. Each time you get a recognized text, you need to identify the proper field for a sum, a vendor, line items, a card number, and so on. The big challenge is that receipt layout dramatically varies from vendor to vendor.

[![No common receipt template](https://static1.abbyy.com/abbyycommedia/25813/2-300x176.png)](http://blog.ocrsdk.com/wp-content/uploads/2015/12/2.png)

In response to this problem ABBYY Receipt Capture SDK implements a so-called common approach: it considers what the typical receipt of that country looks like and then generates several hypotheses about the relevant data locations. For each hypothesis the technology finds and takes into account different factors like position of data in a receipt, what surrounds the data, and so on. During this analysis the technology gives more weight to a particular hypothesis, and penalizes it if finds discrepancy.

On the basis of this analysis the technology “concludes” that a certain hypothesis has won i.e. the exact piece of data much more likely belongs to a given field. When a particular hypothesis wins, the corresponding data is excluded from a further search. This increases search quality: now there are fewer fields and “candidates” and therefore a lower error probability.

Another way out is pre-trained etalons with marked fields. We created these etalons for known vendors. To use them we should “just” identify the vendor who issued the receipt i.e. find the vendor name in the receipt. The challenge is that even a vendor name search is a headache because it can be depicted in numerous ways, from abbreviation to logo.

To address this we use two vendor classifiers:

1. First, a keyword classifier is applied for a receipt. For accurate capture of vendor names a special dictionary containing known vendor names was compiled and continues to be expanded. The technology searches for vendors listed in the dictionary across the text being recognized. If the receipt contains a vendor name that is familiar for the technology it means that we already have that receipt type in our database and have the ready etalon available, where the proper fields are indicated. This classifier applies for long, complicated, and unique vendor names but doesn’t work on short names. The reason is that a fuzzy search could mistake some other words with the vendor name (e.g. a vendor name is “Border”; in the search for that name the fuzzy search will also propose “Order” as a vendor name).
2. If the first approach fails to yield a result, a text classifier is launched. It works with recognized text and searches for keywords typical for receipts of the given vendor. This helps identify the relevant field for data extraction. These keywords are chosen during the training process and may contain no vendor name at all.

Training can be provided in these classifiers through the corresponding API on the customer’s own vendor base. This option provides high accuracy when capturing vendor names that are important for the customer but which are not widespread. The training is optional. 

If these two approaches fail ABBYY Receipt Capture SDK implements the common approach: trying to “understand” which recognized word could be a vendor name by estimating its position on an image, text font properties and repeatability in certain word models like URL and e-mail.

[![Identifying the proper field](https://static1.abbyy.com/abbyycommedia/25814/3-1-234x300.png)](http://blog.ocrsdk.com/wp-content/uploads/2015/12/3-1.png)

## 4\. Local country specifics of receipts

Each country has its own tax law and peculiarities of receipt data visualization, so when speaking about receipt capture it would be correct to talk about supported countries, not recognition languages. ABBYY Receipt Capture SDK supports 12 countries, including the USA, UK, Germany, Italy, France, Spain, Brazil, Japan, China, Korea, and Taiwan.

Talking about the specifics of local receipts, it is noteworthy that for such countries as Korea, Japan, and China it is quite common for a receipt to contain a mixture of hieroglyphs and Latin characters. Simultaneous recognition of these two types of characters can present a nightmare and leads to an increased number of mistakes.

To start with, hieroglyphs and Latin characters are usually in different print, which leads to recognition failure. Also, as receipt quality leaves much to be desired it can be difficult, even with our high-accuracy multi-recognition technology to provide the recognition accuracy suitable for data capture at an adequate level.

[![country specifics](https://static1.abbyy.com/abbyycommedia/25815/4-1.png)](http://blog.ocrsdk.com/wp-content/uploads/2015/12/4-1.png)

The workaround is “double recognition”. The recognition of hieroglyphs comes first and returns recognized text with some unrecognized blocks (as usual these blocks contain numerals and Latin characters). The Latin character OCR then follows. Transcribed numerals and Latin characters are substituted for poorly recognized characters (if they are) from the first step. As a result we have a receipt with correctly recognized text blocks. This approach significantly improves the accuracy of date and sum OCR in receipts with mixed languages.

## 5\. Difficulty in gathering enough receipt samples

A declaration of accurate receipt processing is senseless without testing on masses of receipts. A variety and volume are important – just remember that no common template for receipts exists.

Why does a receipt capture technology developer need so many receipt samples?

1. For creating templates of known vendors’ receipts and tuning the classifier to be implemented for receipt data capture.
2. For making the technology smarter in general. This means that the more receipts of different types are processed, the greater the probability that the next new vendor and its layout will not present a surprise for the technology.
3. For more precise quality assessment: the more receipts we have, the higher the accuracy in measurements we get and vice versa.

In summary, the more receipts from different vendors and countries you collect, the more accurate the recognition and capture will be. However, the gathering of such a volume of receipts, especially of various types, is a serious challenge. ABBYY Receipt Capture collection covers dozens of receipt types from tens of countries, with thousands of receipts in total.

As you can see, developing a receipt capture technology is a very promising but resource-intensive and complex process. If you are considering implementation of a receipt processing feature into your solution you do not need to embark on this volume of work yourself. Ask for a trial of ABBYY Receipt Capture SDK and get ready-to-use technology instead of wasting your resources.

And if you are still thinking about developing your own technology, set up a proper base with the 99.8% recognition accuracy of FineReader Engine, because [high OCR accuracy is an essential requirement](https://tools.techidaily.com/abbyy/products/) for building up a worthwhile receipt capture technology.

[OCR](https://tools.techidaily.com/abbyy/products/) 

### Like, share or repost

Share 

#### Subscribe for blog updates

First name\*

E-mail\*

Сountry\*

СountryAfghanistanAland IslandsAlbaniaAlgeriaAmerican SamoaAndorraAngolaAnguillaAntarcticaAntigua and BarbudaArgentinaArmeniaArubaAustraliaAustriaAzerbaijanBahamasBahrainBangladeshBarbadosBelgiumBelizeBeninBermudaBhutanBoliviaBonaire, Sint Eustatius and SabaBosnia and HerzegovinaBotswanaBouvet IslandBrazilBritish Indian Ocean TerritoryBritish Virgin IslandsBrunei DarussalamBulgariaBurkina FasoBurundiCambodiaCameroonCanadaCape VerdeCayman IslandsCentral African RepublicChadChileChinaChristmas IslandCocos (Keeling) IslandsColombiaComorosCongo (Brazzaville)Congo, (Kinshasa)Cook IslandsCosta RicaCroatiaCuraçaoCyprusCzech RepublicCôte d'IvoireDenmarkDjiboutiDominicaDominican RepublicEcuadorEgyptEl SalvadorEquatorial GuineaEritreaEstoniaEthiopiaFalkland Islands (Malvinas)Faroe IslandsFijiFinlandFranceFrench GuianaFrench PolynesiaFrench Southern TerritoriesGabonGambiaGeorgiaGermanyGhanaGibraltarGreeceGreenlandGrenadaGuadeloupeGuamGuatemalaGuernseyGuineaGuinea-BissauGuyanaHaitiHeard and Mcdonald IslandsHoly See (Vatican City State)HondurasHong Kong, SAR ChinaHungaryIcelandIndiaIndonesiaIraqIrelandIsle of ManIsraelITJamaicaJapanJerseyJordanKazakhstanKenyaKiribatiKorea (South)KuwaitKyrgyzstanLao PDRLatviaLebanonLesothoLiberiaLibyaLiechtensteinLithuaniaLuxembourgMacao, SAR ChinaMacedonia, Republic ofMadagascarMalawiMalaysiaMaldivesMaliMaltaMarshall IslandsMartiniqueMauritaniaMauritiusMayotteMexicoMicronesia, Federated States ofMoldovaMonacoMongoliaMontenegroMontserratMoroccoMozambiqueMyanmarNamibiaNauruNepalNetherlandsNetherlands AntillesNew CaledoniaNew ZealandNicaraguaNigerNigeriaNiueNorfolk IslandNorthern Mariana IslandsNorwayOmanPakistanPalauPalestinian TerritoryPanamaPapua New GuineaParaguayPeruPhilippinesPitcairnPolandPortugalPuerto RicoQatarRomaniaRwandaRéunionSaint HelenaSaint Kitts and NevisSaint LuciaSaint Pierre and MiquelonSaint Vincent and GrenadinesSaint-BarthélemySaint-Martin (French part)SamoaSan MarinoSao Tome and PrincipeSaudi ArabiaSenegalSerbiaSeychellesSierra LeoneSingaporeSint Maarten (Dutch part)SlovakiaSloveniaSolomon IslandsSouth AfricaSouth Georgia and the South Sandwich IslandsSouth SudanSpainSri LankaSurinameSvalbard and Jan Mayen IslandsSwazilandSwedenSwitzerlandTaiwan, Republic of ChinaTajikistanTanzania, United Republic ofThailandTimor-LesteTogoTokelauTongaTrinidad and TobagoTunisiaTurkeyTurks and Caicos IslandsTuvaluUgandaUkraineUnited Arab EmiratesUnited KingdomUnited States of AmericaUruguayUS Minor Outlying IslandsUzbekistanVanuatuVenezuela (Bolivarian Republic)Viet NamVirgin Islands, USWallis and Futuna IslandsWestern SaharaZambiaZimbabwe

* I have read and agree with the [Privacy policy](https://tools.techidaily.com/abbyy/products/) and the [Cookie policy](https://tools.techidaily.com/abbyy/products/).

* I agree to receive email updates from ABBYY Solutions Ltd. such as news related to ABBYY Solutions Ltd. products and technologies, invitations to events and webinars, and information about whitepapers and content related to ABBYY Solutions Ltd. products and services.  
    
I am aware that my consent could be revoked at any time by clicking the unsubscribe link inside any email received from ABBYY Solutions Ltd. or via [ABBYY Data Subject Access Rights Form](https://tools.techidaily.com/abbyy/products/).

Referrer

Last name

Query string

Product Interest Temp

UTM Campaign Name

UTM Medium

UTM Source

ITM Source

GA Client ID

UTM Content

GDPR Consent Note

Captcha Score

Page URL

Connect with us

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
