---
title: Key Insights From the JavaScript Conference in Budapest, Hungary
date: 2024-08-22T07:24:26.920Z
updated: 2024-08-23T07:24:26.920Z
categories:
  - abbyy
thumbnail: https://thmb.techidaily.com/8dec14c118d7ee81f46eabd3dcf3a5188bbf56bf80fdef23b5e5cacf3addecc5.jpg
---

## Key Insights From the JavaScript Conference in Budapest, Hungary

[Back to ABBYY Blog](https://tools.techidaily.com/abbyy/products/)

# What We Learned at JSConf Budapest 2022

###### Attila Kling

October 27, 2022

![](https://static1.abbyy.com/abbyycommedia/36301/jsconf_cover.jpg) 

This summer, ABBYY was a proud sponsor of [JSConf Budapest—](https://jsconfbp.com/)an international conference bringing together JavaScript enthusiasts from all over the world. Six people from the ABBYY Hungary team, including myself, were representing the company at the event. During the two-day conference, we got to talk to hundreds of developers from as far afield as Singapore, Israel, Serbia, the UK, and many other locations. A steady stream of visitors attended our booth where everyone could take our fun (but not so easy) quiz and win prizes, while learning about ABBYY. We also had the opportunity to listen to dozens of great speakers, and collected some interesting thoughts and insights to share in this post\*.

### **The Power of JS Generators by Anjana Vakil**

In this presentation, Anjana shared her passion about generators with the audience with so much energy that even if you didn’t know anything about generators, you were instantly hyped up!

The presentation started with a brief introduction to generators. In case your generator-related knowledge is a little bit rusty, here's a [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global%5FObjects/Generator) to refresh your memory, but I advise you to watch Anjana's presentation instead, which has it all covered.

_Iterables_

Generator functions are also iterables which means we can loop through them, and we can use, for example, the spread operator:

function\* abcs() {

 yield 'a';

 yield 'b';

 yield 'c';



\[...abcs()\]; _// \['a', 'b', 'c'\]_

In the presentation there was a neat example about a French card deck object with the special property \[Symbol.iterator\] and the presenter used the fact that generators are also iterable so that when we spread the deck object, the internal iterator of the object, which is a generator function, creates all the French deck cards. This presentation helped us to **think out-of-the-box about generators and their practical uses in our applications**.

[Here](https://youtu.be/gu3FfmgkwUc) you can watch the full presentation.

**Typed JavaScript? For Real? The “Type Annotations” Proposal and What It’s All About by Gil Tayar**

Gil presented a TC39 proposal on including types in vanilla JavaScript. The proposal currently is in the first stage, so anything can happen still, but the idea behind types in JavaScript is not uncommon—just think about TypeScript or Flow.

_But we have TypeScript!_ – you might think.

Yes, but the proposal aims to provide a **common alternative to TypeScript in which you don't necessarily have to transpile your code**.

The types would still be ignored by the runtime, similar to how TypeScript works, and the types would be applied by annotations with similar syntax to TypeScript.

Internally, we had an interesting conversation about this topic. In itself, this doesn't provide anything more than just using TypeScript. However, diversity is always welcome, and another option for typed JavaScript is, again, very good. We are very curious about how this proposal will evolve.

[Here](https://youtu.be/SdV9Xy0E4CM) you can watch the full presentation.

### **Communicating Intention with Functional TypeScript by Thiago Temple**

This presentation by Thiago caught our attention for several reasons:

1. a) we use TypeScript extensively here at ABBYY;
2. b) let's face it, when it comes to typing, we developers can be lazy 😊

So hearing some advice, tips and tricks is always helpful. The “gotcha” moment for us in this presentation was to **put more focus on typing, not just for the positive scenario but for (controlled) failures as well**. I'm pretty sure all of you are familiar with code (pseudo) like this:

type Order = {...}

type OrderResult = Result<ProcessedOrder>

function processOrder(order: Order): OrderResult {}

The upper code is quite standard, but what if we throw from the function, or what happens if the order is null ? Maybe the function handles the missing input, in which case it returns a different result. Thiago reminded us to handle those edge-cases as well. Here is an example from the presentation:

type Order = {...}

type OrderResult = Result<ProcessedOrder, OrderProcessingError>

function processOrder(order: Order): OrderResult {}

The speaker also talked about using union types when the input for the function is a well-defined finite set of string values. One way this helps us is to catch typo errors. Here at ABBYY we use union types all the time, so it was nice to learn a little more about them.

[Here](https://youtu.be/fhyHgkH0ZEg) you can watch the full presentation.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
### **7±2 Reasons Psychology Will Help You Write Better Code by Moran Weber**

This was a really exciting talk, and I encourage all of you to watch the video and play along with the little “games”. Moran has a degree in social psychology along with a lot of experience in software development. She shared several cognitive psychology principles that help to better understand how we read and interpret code.

For example, it is common knowledge among developers to use meaningful naming of variables, functions, etc. We all know the requirements. But do we really understand why good naming yields better collaboration? While shamelessly I would reply “yes”, in reality I did not. This presentation explains and demonstrates this extremely well.

One other thing that sticks in my mind and that I have practiced with my team since the conference is that **code reviews should always be cold**. This means no design explanation and intro is needed before handing your code—just send out a pull request. Otherwise, we could fall into a selective attention trap and not stay objective while reviewing the code.

[Here](https://youtu.be/jAUcbFM0nXE) you can watch the full presentation.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
### **Testing Web Accessibility by Adrián Bolonio**

Adrián spoke about web accessibility. At ABBYY Hungary we are working on a web application for ABBYY [Timeline](https://tools.techidaily.com/abbyy/products/)—a cloud-based process intelligence platform that helps companies improve their processes. The target audience does not include every day users rather, per se, superusers such as business analysts. We don't have to think about web accessibility (which is usually referred to as a11y), the target audience just does not require this, right? WRONG. And Adrián explains very well why my statement is so wrong.

According to the presenter, every web application should care about accessibility. It is so easy to consider a11y as something we have to think about only when the target audience includes people with disabilities. Well, what if I tell you this mindset is wrong, and we all should care about a11y regardless of the type of application we are making? Adrián showed us that not only disabled people might use our applications leveraging a11y capabilities, like screen readers or other aids, but people with temporary inconveniences may also need them. For example, a father having his kid on his lap (sounds familiar in the era of home office?) and being able to use the application with only one hand. Or a worker having some temporary eye strain, which can happen to any of us.

This talk was influential—I could even say eye-opening!—to many of us attending the conference. The presentation has given us **ideas and inspiration about the direction in which we want to develop the product we are working on**.

[Here](https://tools.techidaily.com/abbyy/products/) you can watch the full presentation.

\*_All presentations in the program were insightful, and we enjoyed each one of them. The upper excerpts reflect our team's best memories about the conference._

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
### **Conclusion**

For me, personally, this was the first JSConf I was able to attend here in Budapest. I felt the focus was more on the less technical aspects of web development rather than straight technical JavaScript, which was an advantage. This way topics like web accessibility and psychology could gain some love and attention. Huge thanks to the JSConf Budapest team for organizing the conference.

[Tech Talk](https://tools.techidaily.com/abbyy/products/) 

![](https://static4.abbyy.com/abbyycommedia/36306/attila-kling-88x88.png)

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
Attila Kling

Software Development Group Team Lead

Attila leads a software development group of ABBYY Timeline. His day-to-day job includes managing web development projects, and he has a keen interest in web-security, user-management, authentication, and authorization.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-final-cut-pro-x-mastery-crafting-instagrams-desired-format/"><u>[New] 2024 Approved  Final Cut Pro X Mastery  Crafting Instagram's Desired Format</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-from-mono-to-vivid-blades-transformation-into-the-4k-era/"><u>[New] 2024 Approved  From Mono to Vivid  Blade's Transformation Into the 4K Era</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-youtube-earnings-per-watch-average-income-breakdown/"><u>[New] 2024 Approved  YouTube Earnings per Watch  Average Income Breakdown</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-elevate-your-visibility-with-youtube-branding-techniques/"><u>[New] Elevate Your Visibility with YouTube Branding Techniques</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-from-idea-to-impact-top-8-online-courses-for-new-creators/"><u>[New] From Idea to Impact  Top 8 Online Courses for New Creators</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-visionary-insights-selecting-from-5-premier-slow-cameras/"><u>[New] In 2024, Visionary Insights  Selecting From 5 Premier Slow Cameras</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-step-by-step-sharing-photos-on-youtube/"><u>[New] Step-by-Step  Sharing Photos on YouTube</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-acoustic-bridge-to-captivating-trailers-for-2024/"><u>[New] The Acoustic Bridge to Captivating Trailers for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-unveiling-the-typical-podcasters-income/"><u>[New] Unveiling the Typical Podcaster's Income</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-zoom-essentials-a-comprehensible-guide/"><u>[New] Zoom Essentials  A Comprehensible Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-10-steps-to-become-a-successful-smm-for-2024/"><u>[Updated] 10 Steps to Become a Successful SMM for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-elevating-your-shopping-vlogs-advanced-editing-techniques/"><u>[Updated] 2024 Approved  Elevating Your Shopping Vlogs  Advanced Editing Techniques</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-explore-these-14-fascinating-text-based-animations/"><u>[Updated] 2024 Approved  Explore These 14 Fascinating Text-Based Animations</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-industrys-airborenas-titans-10-lifters-reviewed/"><u>[Updated] 2024 Approved  Industry's Airborenas Titans  10 Lifters Reviewed</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-navigating-the-nuances-zoom-and-youtube-live-streaming-explored/"><u>[Updated] 2024 Approved  Navigating the Nuances  Zoom and YouTube Live Streaming Explored</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-restore-lost-details-4-premiere-pro-methods-for-iphone-hdr-footage/"><u>[Updated] 2024 Approved  Restore Lost Details  4 Premiere Pro Methods for iPhone HDR Footage</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-sightgallery-review-system/"><u>[Updated] 2024 Approved  SightGallery Review System</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-the-dynamic-duo-of-yi-and-4k-in-action-video/"><u>[Updated] 2024 Approved  The Dynamic Duo of Yi and 4K in Action Video</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-apeaksoft-2023-screens-recording-insights-for-2024/"><u>[Updated] Apeaksoft 2023 Screens Recording Insights for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-crafting-compelling-visual-narratives-with-illustrators-motion-blur-for-2024/"><u>[Updated] Crafting Compelling Visual Narratives with Illustrator's Motion Blur for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-cutting-edge-android-3d-viewer-tech/"><u>[Updated] Cutting-Edge Android 3D Viewer Tech</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-dive-deep-into-adobe-cloud-then-discover-alternatives/"><u>[Updated] Dive Deep Into Adobe Cloud, Then Discover Alternatives</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-electronic-gamblers-journal/"><u>[Updated] In 2024, ELECTRONIC GAMBLER'S JOURNAL</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-exquisite-online-destinations-for-sparkling-3d-typography/"><u>[Updated] In 2024, Exquisite Online Destinations for Sparkling 3D Typography</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-navigating-microsoft-azure-for-text-conversion/"><u>[Updated] In 2024, Navigating Microsoft Azure for Text Conversion</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-quintessential-preview-reels-set/"><u>[Updated] In 2024, Quintessential Preview Reels Set</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-unlocking-the-realm-of-free-photo-frame-video-downloads/"><u>[Updated] In 2024, Unlocking the Realm of Free Photo Frame Video Downloads</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-securing-sound-speed-increase-in-the-digital-world-of-spotify/"><u>[Updated] Securing Sound Speed Increase in the Digital World of Spotify</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-setting-up-zoom-like-a-pro-for-2024/"><u>[Updated] Setting Up Zoom Like a Pro for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-speedy-switching-spree-from-srt-to-txt-files-done-quickly-for-2024/"><u>[Updated] Speedy Switching Spree  From SRT to TXT Files Done Quickly for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-ultimate-guide-to-affordable-video-players-a-comprehensive-list-pc-and-mobile/"><u>[Updated] Ultimate Guide to Affordable Video Players  A Comprehensive List (PC & Mobile)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-color-grading-mastery-utilizing-cg-centrals-standardized-looks/"><u>2024 Approved  Color Grading Mastery  Utilizing CG Central's Standardized Looks</u></a></li>
<li><a href="https://tech-haven.techidaily.com/androids-voice-controlled-gpt-experience-begins-here/"><u>Android's Voice Controlled GPT Experience Begins Here</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-it-xiaomi-redmi-12-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix It Xiaomi Redmi 12 Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-oneplus-ace-3-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track OnePlus Ace 3 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-itel-a60-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Itel A60 to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-samsung-galaxy-a24-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Samsung Galaxy A24 online without jailbreak</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-filmmaking-simplified-create-an-inviting-youtube-subscription-button-in-filmora/"><u>In 2024, Filmmaking Simplified  Create an Inviting YouTube Subscription Button in Filmora</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-motorola-defy-2-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Motorola Defy 2 Location | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/optimal-cloud-vaults-recommended-solutions-for-2024/"><u>Optimal Cloud Vaults  Recommended Solutions for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/orderly-enjoyment-a-step-by-step-process-for-viewing-full-dragon-ball-series/"><u>Orderly Enjoyment: A Step-by-Step Process for Viewing Full Dragon Ball Series</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-future-of-android-time-lapses-innovations-in-video-capture-for-2024/"><u>The Future of Android Time-Lapses  Innovations in Video Capture for 2024</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-music-from-itel-by-fonelab-android-recover-music/"><u>Undelete lost music from Itel</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unlock-the-full-potential-of-media-player-through-subtitles/"><u>Unlock the Full Potential of Media Player Through Subtitles</u></a></li>
</ul></div>
