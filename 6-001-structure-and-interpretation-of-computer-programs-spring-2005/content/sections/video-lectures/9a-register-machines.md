---
about_this_resource_text: <p><b>Topics covered:</b> Register Machines</p> <p><b> Instructors:</b>
  Hal Abelson and Gerald Jay Sussman</p> <p>Subtitles for this course are provided
  through the generous assistance of Henry Baker, Hoofar Pourzand, Heather Wood, Aleksejs
  Truhans, Steven Edwards, George Menhorn, and Mahendra Kumar.</p>
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
embedded_media:
- id: 9A.jpg
  parent_uid: 0abf802ec53fd91aa9766c2311428220
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/9a-register-machines/9A.jpg
  title: 9A.jpg
  type: null
  uid: cdc50880ca68b6a554a248057f1f5fb7
- id: Video-YouTube-Stream
  media_location: cIc8ZBMcqAc
  parent_uid: 0abf802ec53fd91aa9766c2311428220
  title: Video-YouTube-Stream
  type: Video
  uid: 9d4cf615f2b7eefc47a75dc62a145b21
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT_Structure_of_Computer_Programs_1986/lec9a.mp4
  parent_uid: 0abf802ec53fd91aa9766c2311428220
  title: Video-Internet Archive-MP4
  type: Video
  uid: 17c15e7267a12a569f0a44d583e5ef8a
- id: Thumbnail-OCW-JPG
  parent_uid: 0abf802ec53fd91aa9766c2311428220
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: a7863b6fe2d78d2ee5e94bbd8e236df1
- id: 3Play-3PlayYouTubeid-MP4
  media_location: cIc8ZBMcqAc
  parent_uid: 0abf802ec53fd91aa9766c2311428220
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 7129e2108e581e5258a569682914098c
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/cIc8ZBMcqAc/default.jpg
  parent_uid: 0abf802ec53fd91aa9766c2311428220
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: ae776effeb60804b272b67a7d2bf2920
- id: cIc8ZBMcqAc.srt
  parent_uid: 0abf802ec53fd91aa9766c2311428220
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/9a-register-machines/cIc8ZBMcqAc.srt
  title: 3play caption file
  type: null
  uid: eb5c655135ce6747691c1c41156f8230
- id: cIc8ZBMcqAc.pdf
  parent_uid: 0abf802ec53fd91aa9766c2311428220
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/9a-register-machines/cIc8ZBMcqAc.pdf
  title: 3play pdf file
  type: null
  uid: 8b955a3bffbbe00a8aa32576b43695dc
- id: Caption-3Play YouTube id-SRT
  parent_uid: 0abf802ec53fd91aa9766c2311428220
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: add3b17852e7719db26243fec3f3ae20
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 0abf802ec53fd91aa9766c2311428220
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 7163f8dbfebd4fa408262e5584aecc3c
inline_embed_id: 914710129a:registermachines2547036
layout: video
order_index: null
parent_uid: 4fcacad2c29981dd668a6b29822403cc
related_resources_text: ''
short_url: 9a-register-machines
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/9a-register-machines
template_type: Tabbed
title: '9A: Register Machines'
transcript: '<p><span m=''2190''>[MUSIC PLAYING - "JESU, JOY OF MAN''S DESIRING" BY
  JOHANN SEBASTIAN BACH]</span> </p><p><span m=''17260''>PROFESSOR: Well,</span> <span
  m=''17560''>up</span> <span m=''17710''>''til</span> <span m=''17900''>now,</span>
  <span m=''18210''>I</span> <span m=''18340''>suppose,</span> <span m=''19350''>we''ve</span>
  <span m=''19590''>been</span> <span m=''20110''>learning</span> <span m=''20520''>about</span>
  <span m=''22070''>a</span> <span m=''22190''>lot</span> <span m=''22460''>of</span>
  <span m=''22730''>techniques</span> <span m=''23240''>for</span> <span m=''24130''>organizing</span>
  <span m=''24680''>big</span> <span m=''24920''>programs,</span> <span m=''26690''>symbolic</span>
  <span m=''27700''>manipulation</span> <span m=''28420''>a</span> <span m=''28540''>bit,</span>
  <span m=''30870''>some</span> <span m=''31070''>of</span> <span m=''31120''>the</span>
  <span m=''31210''>technology</span> <span m=''32689''>that</span> <span m=''33180''>you</span>
  <span m=''33290''>use</span> <span m=''33820''>for</span> <span m=''34200''>establishing</span>
  <span m=''35100''>languages,</span> <span m=''35650''>one</span> <span m=''35820''>in</span>
  <span m=''35900''>terms</span> <span m=''36160''>of</span> <span m=''36250''>another,</span>
  <span m=''37110''>which</span> <span m=''37620''>is</span> <span m=''37710''>used</span>
  <span m=''38030''>for</span> <span m=''38360''>organizing</span> <span m=''38870''>very</span>
  <span m=''39080''>large</span> <span m=''39340''>programs.</span> <span m=''39890''>In</span>
  <span m=''39980''>fact,</span> <span m=''40760''>the</span> <span m=''40860''>nicest</span>
  <span m=''41230''>programs</span> <span m=''41660''>I</span> <span m=''41750''>know</span>
  <span m=''42590''>look</span> <span m=''42770''>more</span> <span m=''42960''>like</span>
  <span m=''43160''>a</span> <span m=''43230''>pile</span> <span m=''43580''>of</span>
  <span m=''43680''>languages</span> <span m=''44880''>than</span> <span m=''45700''>like</span>
  <span m=''46010''>a</span> <span m=''46170''>decomposition</span> <span m=''46840''>of</span>
  <span m=''46920''>a</span> <span m=''46980''>problem</span> <span m=''47310''>into</span>
  <span m=''47470''>parts.</span> <span m=''49900''>Well,</span> <span m=''50310''>I</span>
  <span m=''50400''>suppose</span> <span m=''50780''>at this</span> <span m=''50990''>point,</span>
  <span m=''52160''>there are</span> <span m=''52340''>still,</span> <span m=''52540''>however,</span>
  <span m=''52840''>a</span> <span m=''52880''>few</span> <span m=''53070''>mysteries</span>
  <span m=''53620''>about</span> <span m=''53820''>how</span> <span m=''54040''>this</span>
  <span m=''54160''>sort</span> <span m=''54390''>of</span> <span m=''54440''>stuff</span>
  <span m=''54700''>works.</span> </p><p><span m=''56260''>And</span> <span m=''56490''>so</span>
  <span m=''57230''>what</span> <span m=''57440''>we''d</span> <span m=''57610''>like</span>
  <span m=''57800''>to</span> <span m=''57890''>do</span> <span m=''58060''>now</span>
  <span m=''59290''>is</span> <span m=''60170''>diverge</span> <span m=''60720''>from</span>
  <span m=''61420''>the</span> <span m=''61630''>plan</span> <span m=''62410''>of</span>
  <span m=''62950''>telling</span> <span m=''63330''>you</span> <span m=''63870''>how</span>
  <span m=''64150''>to</span> <span m=''64230''>organize</span> <span m=''64720''>big</span>
  <span m=''64930''>programs,</span> <span m=''65500''>and</span> <span m=''65590''>rather</span>
  <span m=''65890''>tell</span> <span m=''66060''>you</span> <span m=''66220''>something</span>
  <span m=''66630''>about</span> <span m=''67230''>the</span> <span m=''67350''>mechanisms</span>
  <span m=''68540''>by</span> <span m=''68710''>which</span> <span m=''69580''>these</span>
  <span m=''69870''>things</span> <span m=''70140''>can</span> <span m=''70560''>be</span>
  <span m=''70820''>made</span> <span m=''71060''>to</span> <span m=''71160''>work.</span>
  <span m=''72196''>The</span> <span m=''72550''>main</span> <span m=''72890''>reason</span>
  <span m=''73240''>for</span> <span m=''73380''>this</span> <span m=''74290''>is</span>
  <span m=''75940''>demystification,</span> <span m=''77240''>if</span> <span m=''77400''>you</span>
  <span m=''77540''>will,</span> <span m=''78652''>that</span> <span m=''79050''>we</span>
  <span m=''79240''>have</span> <span m=''79440''>a</span> <span m=''79490''>lot</span>
  <span m=''79680''>of</span> <span m=''79740''>mysteries</span> <span m=''80270''>left,</span>
  <span m=''81160''>like</span> <span m=''81360''>exactly</span> <span m=''81930''>how</span>
  <span m=''82170''>it</span> <span m=''82260''>is</span> <span m=''82420''>the</span>
  <span m=''82500''>case</span> <span m=''83210''>that</span> <span m=''83480''>a</span>
  <span m=''83800''>program</span> <span m=''84700''>is</span> <span m=''84850''>controlled,</span>
  <span m=''86140''>how</span> <span m=''86920''>a</span> <span m=''87260''>computer</span>
  <span m=''88190''>knows</span> <span m=''88960''>what</span> <span m=''89180''>the</span>
  <span m=''89260''>next</span> <span m=''89520''>thing</span> <span m=''89710''>to</span>
  <span m=''89800''>do</span> <span m=''90090''>is,</span> <span m=''90590''>or</span>
  <span m=''90760''>something</span> <span m=''91100''>like</span> <span m=''91360''>that.</span>
  <span m=''92430''>And</span> <span m=''92610''>what</span> <span m=''92750''>I''d</span>
  <span m=''92860''>like</span> <span m=''93060''>to</span> <span m=''93140''>do</span>
  <span m=''93280''>now</span> <span m=''94020''>is</span> <span m=''94280''>make</span>
  <span m=''94490''>that</span> <span m=''94750''>clear</span> <span m=''95070''>to</span>
  <span m=''95130''>you,</span> <span m=''95890''>that</span> <span m=''96410''>even</span>
  <span m=''96630''>if</span> <span m=''96960''>you''ve</span> <span m=''97140''>never</span>
  <span m=''97440''>played</span> <span m=''97690''>with</span> <span m=''97810''>a</span>
  <span m=''97850''>physical</span> <span m=''98230''>computer</span> <span m=''98580''>before,</span>
  <span m=''101480''>the</span> <span m=''101820''>mechanism</span> <span m=''102410''>is</span>
  <span m=''102510''>really</span> <span m=''102750''>very</span> <span m=''103000''>simple,</span>
  <span m=''104065''>and</span> <span m=''104560''>that</span> <span m=''104660''>you</span>
  <span m=''104740''>can</span> <span m=''104840''>understand it</span> <span m=''105250''>completely</span>
  <span m=''105690''>with</span> <span m=''105820''>no</span> <span m=''105980''>trouble.</span>
  </p><p><span m=''107650''>So</span> <span m=''108170''>I''d</span> <span m=''108530''>like</span>
  <span m=''108740''>to</span> <span m=''108820''>start</span> <span m=''109740''>by</span>
  <span m=''109950''>imagining</span> <span m=''110790''>that</span> <span m=''110910''>we--</span>
  <span m=''111390''>well,</span> <span m=''111510''>the</span> <span m=''111680''>way</span>
  <span m=''111840''>we''re going to</span> <span m=''112020''>do</span> <span m=''112180''>this,</span>
  <span m=''112380''>by</span> <span m=''112520''>the</span> <span m=''112650''>way,</span>
  <span m=''112900''>is</span> <span m=''113080''>we''re</span> <span m=''113190''>going</span>
  <span m=''113320''>to</span> <span m=''113530''>take</span> <span m=''114090''>some</span>
  <span m=''114360''>very</span> <span m=''114590''>simple</span> <span m=''114900''>Lisp</span>
  <span m=''115140''>programs,</span> <span m=''116650''>very</span> <span m=''116960''>simple</span>
  <span m=''117320''>Lisp</span> <span m=''117440''>programs,</span> <span m=''119060''>and</span>
  <span m=''119250''>transform</span> <span m=''119810''>them</span> <span m=''119930''>into</span>
  <span m=''120110''>hardware.</span> <span m=''122160''>I''m</span> <span m=''122200''>not</span>
  <span m=''122360''>going</span> <span m=''122430''>to</span> <span m=''122500''>worry</span>
  <span m=''122840''>about</span> <span m=''123130''>some</span> <span m=''123260''>intermediate</span>
  <span m=''123780''>step</span> <span m=''124880''>of</span> <span m=''125260''>going</span>
  <span m=''125520''>through</span> <span m=''125700''>some</span> <span m=''125930''>existing</span>
  <span m=''126430''>computer</span> <span m=''126820''>machine</span> <span m=''127130''>language</span>
  <span m=''127470''>and</span> <span m=''127560''>then</span> <span m=''127680''>showing</span>
  <span m=''127810''>you</span> <span m=''127940''>how</span> <span m=''128050''>that</span>
  <span m=''128220''>computer</span> <span m=''128530''>works,</span> <span m=''129850''>because</span>
  <span m=''130669''>that''s</span> <span m=''130960''>not</span> <span m=''131150''>as</span>
  <span m=''131240''>illuminating.</span> <span m=''132750''>So</span> <span m=''132940''>what</span>
  <span m=''133030''>I''m</span> <span m=''133140''>really</span> <span m=''133360''>going</span>
  <span m=''133470''>to</span> <span m=''133580''>show</span> <span m=''133790''>you</span>
  <span m=''134560''>is</span> <span m=''134790''>how</span> <span m=''135740''>a</span>
  <span m=''135940''>piece</span> <span m=''136250''>of</span> <span m=''136310''>machinery</span>
  <span m=''136890''>can</span> <span m=''137030''>be</span> <span m=''137160''>built</span>
  <span m=''138000''>to</span> <span m=''138130''>do</span> <span m=''138320''>a</span>
  <span m=''138380''>job</span> <span m=''140210''>that</span> <span m=''140540''>you
  have</span> <span m=''140710''>written</span> <span m=''140930''>down</span> <span
  m=''141130''>as</span> <span m=''141260''>a</span> <span m=''141310''>program.</span>
  <span m=''142040''>That</span> <span m=''142150''>program is,</span> <span m=''142530''>in</span>
  <span m=''142630''>fact,</span> <span m=''142850''>a</span> <span m=''142900''>description</span>
  <span m=''143350''>of a</span> <span m=''143400''>machine.</span> </p><p><span m=''145760''>We''re</span>
  <span m=''145880''>going</span> <span m=''146000''>to</span> <span m=''146040''>start</span>
  <span m=''146300''>with</span> <span m=''146400''>a</span> <span m=''146450''>very</span>
  <span m=''146750''>simple</span> <span m=''147060''>program,</span> <span m=''148030''>proceed</span>
  <span m=''148600''>to</span> <span m=''148690''>show</span> <span m=''148840''>you</span>
  <span m=''148970''>some</span> <span m=''149760''>simple</span> <span m=''150120''>mechanisms,</span>
  <span m=''151390''>proceed</span> <span m=''151740''>to</span> <span m=''151830''>a</span>
  <span m=''151890''>few</span> <span m=''152250''>more</span> <span m=''152440''>complicated</span>
  <span m=''153040''>programs,</span> <span m=''154290''>and</span> <span m=''154470''>then</span>
  <span m=''154630''>later</span> <span m=''154900''>show</span> <span m=''155040''>you</span>
  <span m=''155560''>a</span> <span m=''156130''>not</span> <span m=''156450''>very</span>
  <span m=''156660''>complicated</span> <span m=''157120''>program,</span> <span m=''157430''>how</span>
  <span m=''157550''>the</span> <span m=''157670''>evaluator</span> <span m=''159680''>transforms</span>
  <span m=''160230''>into</span> <span m=''160340''>a</span> <span m=''160360''>piece</span>
  <span m=''160530''>of</span> <span m=''160620''>hardware.</span> <span m=''161230''>And</span>
  <span m=''161330''>of</span> <span m=''161400''>course</span> <span m=''161590''>at</span>
  <span m=''161650''>that</span> <span m=''161850''>point,</span> <span m=''162050''>you
  have</span> <span m=''162220''>made</span> <span m=''162520''>the</span> <span m=''162890''>universal</span>
  <span m=''163390''>transition</span> <span m=''164280''>and</span> <span m=''164520''>can</span>
  <span m=''165270''>execute</span> <span m=''165610''>any</span> <span m=''165780''>program</span>
  <span m=''166130''>imaginable</span> <span m=''167300''>with</span> <span m=''167400''>a</span>
  <span m=''167510''>piece</span> <span m=''167710''>of</span> <span m=''167880''>well-defined</span>
  <span m=''168350''>hardware.</span> </p><p><span m=''171392''>Well,</span> <span
  m=''171830''>let''s</span> <span m=''172110''>start</span> <span m=''172350''>up</span>
  <span m=''172490''>now,</span> <span m=''173060''>give</span> <span m=''173200''>you</span>
  <span m=''173320''>a</span> <span m=''173350''>real</span> <span m=''173570''>concrete</span>
  <span m=''174010''>feeling</span> <span m=''174320''>for</span> <span m=''174430''>this</span>
  <span m=''174630''>sort</span> <span m=''174800''>of</span> <span m=''174880''>thing.</span>
  <span m=''175440''>Let''s</span> <span m=''175610''>start</span> <span m=''175860''>with</span>
  <span m=''176320''>a</span> <span m=''176380''>very</span> <span m=''176780''>simple</span>
  <span m=''177150''>program.</span> <span m=''179600''>Here''s</span> <span m=''179880''>Euclid''s</span>
  <span m=''180260''>algorithm.</span> <span m=''183880''>It''s</span> <span m=''183970''>actually</span>
  <span m=''184200''>a</span> <span m=''184260''>little</span> <span m=''184440''>bit</span>
  <span m=''185590''>more</span> <span m=''185760''>modern</span> <span m=''186140''>than</span>
  <span m=''186290''>Euclid''s</span> <span m=''186440''>algorithm.</span> <span m=''186770''>Euclid''s</span>
  <span m=''187120''>algorithm</span> <span m=''187740''>for</span> <span m=''188120''>computing</span>
  <span m=''188460''>the</span> <span m=''188520''>greatest</span> <span m=''188810''>common</span>
  <span m=''189010''>divisor of</span> <span m=''189460''>two</span> <span m=''189630''>numbers</span>
  <span m=''190470''>was</span> <span m=''191210''>invented</span> <span m=''191880''>350</span>
  <span m=''192720''>BC,</span> <span m=''193170''>I</span> <span m=''193380''>think.</span>
  <span m=''194300''>It''s</span> <span m=''194400''>the</span> <span m=''194500''>oldest</span>
  <span m=''194870''>known</span> <span m=''195080''>algorithm.</span> </p><p><span
  m=''199320''>But</span> <span m=''199810''>here</span> <span m=''199990''>we''re</span>
  <span m=''200080''>going</span> <span m=''200160''>to</span> <span m=''200240''>talk</span>
  <span m=''200420''>about</span> <span m=''200950''>GCD</span> <span m=''201410''>of</span>
  <span m=''202133''>A and</span> <span m=''202616''>B,</span> <span m=''203380''>the</span>
  <span m=''203440''>Greatest</span> <span m=''203710''>Common</span> <span m=''203930''>Divisor</span>
  <span m=''204185''>or</span> <span m=''204440''>two</span> <span m=''204590''>numbers,</span>
  <span m=''204950''>A</span> <span m=''205220''>and</span> <span m=''205610''>B.</span>
  <span m=''206370''>And</span> <span m=''207260''>the</span> <span m=''207380''>algorithm</span>
  <span m=''207660''>is</span> <span m=''207820''>extremely</span> <span m=''208350''>simple.</span>
  <span m=''209500''>If</span> <span m=''210220''>B</span> <span m=''210390''>is</span>
  <span m=''210560''>0,</span> <span m=''214060''>then</span> <span m=''214410''>the</span>
  <span m=''214500''>result</span> <span m=''215320''>is</span> <span m=''215500''>going</span>
  <span m=''215660''>to</span> <span m=''215820''>be</span> <span m=''216200''>A.</span>
  <span m=''217580''>Otherwise,</span> <span m=''218100''>the</span> <span m=''218170''>result</span>
  <span m=''218970''>is</span> <span m=''219270''>the</span> <span m=''219320''>GCD</span>
  <span m=''222280''>of</span> <span m=''222720''>B</span> <span m=''224520''>and</span>
  <span m=''224730''>the</span> <span m=''224810''>remainder</span> <span m=''231290''>when</span>
  <span m=''231980''>A</span> <span m=''232250''>is</span> <span m=''232410''>divided</span>
  <span m=''232830''>by</span> <span m=''232990''>B.</span> </p><p><span m=''238530''>So</span>
  <span m=''238740''>this</span> <span m=''238990''>we</span> <span m=''239180''>have</span>
  <span m=''239390''>here</span> <span m=''239610''>is</span> <span m=''239690''>a</span>
  <span m=''239730''>very</span> <span m=''240020''>simple</span> <span m=''240400''>iterative</span>
  <span m=''241200''>process.</span> <span m=''242030''>This</span> <span m=''242350''>a</span>
  <span m=''242670''>simple</span> <span m=''243020''>recursive</span> <span m=''243530''>procedure,</span>
  <span m=''244400''>recursively</span> <span m=''245060''>defined</span> <span m=''245550''>procedure,</span>
  <span m=''246350''>recursive</span> <span m=''246780''>definition,</span> <span
  m=''247690''>which</span> <span m=''247940''>yields</span> <span m=''248240''>an</span>
  <span m=''248340''>iterative</span> <span m=''248690''>process.</span> <span m=''249990''>And</span>
  <span m=''250140''>the</span> <span m=''250220''>way</span> <span m=''250380''>it</span>
  <span m=''250490''>works</span> <span m=''251330''>is</span> <span m=''251520''>that</span>
  <span m=''251730''>every</span> <span m=''252000''>step,</span> <span m=''252870''>it</span>
  <span m=''253020''>determines</span> <span m=''253840''>whether</span> <span m=''254190''>B</span>
  <span m=''254460''>was</span> <span m=''254640''>zero.</span> <span m=''255996''>And</span>
  <span m=''256420''>if</span> <span m=''256660''>B</span> <span m=''256839''>is</span>
  <span m=''256970''>0,</span> <span m=''257250''>we</span> <span m=''257390''>got</span>
  <span m=''257550''>the</span> <span m=''257690''>answer</span> <span m=''258209''>in</span>
  <span m=''258380''>A.</span> <span m=''259680''>Otherwise,</span> <span m=''261040''>we</span>
  <span m=''261660''>make</span> <span m=''261880''>another</span> <span m=''262170''>step</span>
  <span m=''262480''>where</span> <span m=''262810''>A</span> <span m=''263030''>is</span>
  <span m=''263180''>the</span> <span m=''263300''>old</span> <span m=''263530''>B,</span>
  <span m=''263950''>and</span> <span m=''264210''>B</span> <span m=''264500''>is</span>
  <span m=''264930''>the</span> <span m=''265060''>remainder</span> <span m=''265490''>of</span>
  <span m=''265560''>the</span> <span m=''265660''>old</span> <span m=''265870''>A</span>
  <span m=''266020''>divided</span> <span m=''266380''>by</span> <span m=''266490''>the</span>
  <span m=''266620''>old</span> <span m=''266830''>B.</span> <span m=''268830''>Very</span>
  <span m=''269090''>simple.</span> </p><p><span m=''271110''>Now</span> <span m=''271300''>this,</span>
  <span m=''271540''>I''ve</span> <span m=''271740''>already</span> <span m=''272050''>told</span>
  <span m=''272360''>you</span> <span m=''272940''>some</span> <span m=''273180''>of</span>
  <span m=''273220''>the</span> <span m=''273280''>mechanism</span> <span m=''273760''>by</span>
  <span m=''273900''>just</span> <span m=''274080''>saying</span> <span m=''274370''>it</span>
  <span m=''274470''>that</span> <span m=''274670''>way.</span> <span m=''274860''>I</span>
  <span m=''274940''>set</span> <span m=''275170''>it in</span> <span m=''275410''>time.</span>
  <span m=''276360''>I</span> <span m=''276460''>said</span> <span m=''276770''>there</span>
  <span m=''276890''>are</span> <span m=''276960''>certain</span> <span m=''277200''>steps,</span>
  <span m=''278130''>and</span> <span m=''278390''>that,</span> <span m=''278770''>in</span>
  <span m=''278950''>fact,</span> <span m=''279450''>one</span> <span m=''279710''>of</span>
  <span m=''279770''>the</span> <span m=''279840''>things</span> <span m=''280020''>you</span>
  <span m=''280130''>can</span> <span m=''280260''>see</span> <span m=''280470''>here</span>
  <span m=''281100''>is</span> <span m=''281450''>that</span> <span m=''281650''>one</span>
  <span m=''281850''>of</span> <span m=''281890''>the</span> <span m=''281940''>reasons</span>
  <span m=''282280''>why</span> <span m=''282510''>this</span> <span m=''282750''>is</span>
  <span m=''283120''>iterative</span> <span m=''283980''>is</span> <span m=''284180''>nothing</span>
  <span m=''284520''>is</span> <span m=''284630''>needed</span> <span m=''284950''>of</span>
  <span m=''285040''>the</span> <span m=''285230''>last</span> <span m=''285430''>step</span>
  <span m=''286840''>to</span> <span m=''286960''>get</span> <span m=''287120''>the</span>
  <span m=''287230''>answer.</span> <span m=''289490''>All</span> <span m=''289800''>of
  the</span> <span m=''289920''>information</span> <span m=''291000''>that''s</span>
  <span m=''291760''>needed</span> <span m=''292060''>to</span> <span m=''292170''>run</span>
  <span m=''292370''>this</span> <span m=''292540''>algorithm</span> <span m=''294230''>is</span>
  <span m=''294460''>in</span> <span m=''294650''>A</span> <span m=''294820''>and</span>
  <span m=''294970''>B.</span> <span m=''295620''>It</span> <span m=''295910''>has</span>
  <span m=''296140''>two</span> <span m=''296390''>well-defined</span> <span m=''296940''>state</span>
  <span m=''297220''>variables.</span> </p><p><span m=''300470''>So</span> <span m=''300630''>I''m</span>
  <span m=''300760''>going</span> <span m=''300840''>to</span> <span m=''300930''>define</span>
  <span m=''301320''>a</span> <span m=''301370''>machine</span> <span m=''301790''>for</span>
  <span m=''301970''>you</span> <span m=''304090''>that</span> <span m=''304200''>can</span>
  <span m=''304370''>compute</span> <span m=''304690''>you</span> <span m=''304840''>GCDs.</span>
  <span m=''306560''>Now</span> <span m=''306760''>let''s</span> <span m=''306940''>see.</span>
  <span m=''307120''>Every</span> <span m=''307380''>computer</span> <span m=''307810''>that''s</span>
  <span m=''307980''>ever</span> <span m=''308180''>been</span> <span m=''308340''>made</span>
  <span m=''309780''>that''s</span> <span m=''309890''>a</span> <span m=''310010''>single-process</span>
  <span m=''310710''>computer,</span> <span m=''311480''>as</span> <span m=''311860''>opposed</span>
  <span m=''312120''>to</span> <span m=''312210''>a</span> <span m=''312260''>multiprocessor</span>
  <span m=''313370''>of</span> <span m=''313490''>some</span> <span m=''313690''>sort,</span>
  <span m=''315050''>is</span> <span m=''315220''>made</span> <span m=''315410''>according</span>
  <span m=''315680''>to</span> <span m=''315720''>the</span> <span m=''315790''>same</span>
  <span m=''316070''>plan.</span> <span m=''317840''>The</span> <span m=''317940''>plan</span>
  <span m=''318220''>is</span> <span m=''318360''>the</span> <span m=''318410''>computer</span>
  <span m=''318670''>has</span> <span m=''318930''>two</span> <span m=''319060''>parts,</span>
  <span m=''320296''>a</span> <span m=''320640''>part</span> <span m=''321030''>called</span>
  <span m=''321470''>the</span> <span m=''321630''>datapaths,</span> <span m=''323140''>and</span>
  <span m=''323280''>a part</span> <span m=''323570''>called</span> <span m=''323810''>the</span>
  <span m=''324090''>controller.</span> </p><p><span m=''325910''>The</span> <span
  m=''326050''>datapaths</span> <span m=''326940''>correspond</span> <span m=''327590''>to</span>
  <span m=''327740''>a</span> <span m=''327810''>calculator</span> <span m=''328190''>that</span>
  <span m=''328570''>you</span> <span m=''328750''>might</span> <span m=''328960''>have.</span>
  <span m=''330010''>It</span> <span m=''330070''>contains</span> <span m=''330300''>certain</span>
  <span m=''330530''>registers</span> <span m=''331070''>that</span> <span m=''331160''>remember</span>
  <span m=''331580''>things,</span> <span m=''331900''>and you''ve all</span> <span
  m=''332240''>used</span> <span m=''332410''>calculators.</span> <span m=''333560''>It</span>
  <span m=''333690''>has</span> <span m=''333840''>some</span> <span m=''333950''>buttons</span>
  <span m=''334320''>on</span> <span m=''334470''>it</span> <span m=''334610''>and</span>
  <span m=''334740''>some</span> <span m=''334890''>lights.</span> <span m=''337030''>And</span>
  <span m=''337190''>so</span> <span m=''337380''>by</span> <span m=''337550''>pushing</span>
  <span m=''337870''>the</span> <span m=''337950''>various</span> <span m=''338280''>buttons,</span>
  <span m=''338560''>you</span> <span m=''338680''>can</span> <span m=''338840''>cause</span>
  <span m=''339010''>operations</span> <span m=''339550''>to</span> <span m=''339620''>happen</span>
  <span m=''339920''>inside</span> <span m=''340240''>there</span> <span m=''340380''>among</span>
  <span m=''340610''>the</span> <span m=''340690''>registers,</span> <span m=''341900''>and</span>
  <span m=''342080''>some</span> <span m=''342220''>of</span> <span m=''342270''>the</span>
  <span m=''342330''>results</span> <span m=''342670''>to</span> <span m=''342740''>be</span>
  <span m=''342840''>displayed.</span> </p><p><span m=''345160''>That''s</span> <span
  m=''345310''>completely</span> <span m=''345650''>mechanical.</span> <span m=''346250''>You</span>
  <span m=''346380''>could</span> <span m=''346500''>imagine</span> <span m=''347340''>that</span>
  <span m=''347620''>box</span> <span m=''348470''>has</span> <span m=''348660''>no</span>
  <span m=''348820''>intelligence</span> <span m=''349320''>in</span> <span m=''349560''>it.</span>
  <span m=''350900''>Now</span> <span m=''351040''>it might</span> <span m=''351190''>be
  very</span> <span m=''351510''>impressive</span> <span m=''351790''>that it</span>
  <span m=''352070''>can produce</span> <span m=''352400''>the</span> <span m=''352460''>sine</span>
  <span m=''352720''>of</span> <span m=''352790''>a</span> <span m=''352830''>number,</span>
  <span m=''354720''>but</span> <span m=''354880''>that</span> <span m=''355500''>at</span>
  <span m=''355550''>least</span> <span m=''355830''>is</span> <span m=''356540''>apparently</span>
  <span m=''357670''>possibly</span> <span m=''358440''>mechanical.</span> <span m=''358970''>At</span>
  <span m=''359030''>least,</span> <span m=''359260''>I</span> <span m=''359320''>could</span>
  <span m=''359470''>open</span> <span m=''359730''>that</span> <span m=''359910''>up</span>
  <span m=''360050''>in</span> <span m=''360140''>the</span> <span m=''360210''>same</span>
  <span m=''360410''>way</span> <span m=''360500''>I''m about</span> <span m=''360870''>to
  open</span> <span m=''361080''>GCD.</span> </p><p><span m=''362690''>So</span> <span
  m=''362840''>this</span> <span m=''362980''>may</span> <span m=''363130''>have</span>
  <span m=''363280''>a</span> <span m=''363320''>whole</span> <span m=''363470''>computer</span>
  <span m=''363800''>inside</span> <span m=''364120''>of</span> <span m=''364190''>it,</span>
  <span m=''364690''>but</span> <span m=''364830''>that''s</span> <span m=''365030''>not</span>
  <span m=''365150''>interesting.</span> <span m=''365940''>Addition</span> <span
  m=''366320''>is</span> <span m=''366400''>certainly</span> <span m=''366700''>simple.</span>
  <span m=''368200''>That</span> <span m=''368280''>can</span> <span m=''368360''>be</span>
  <span m=''368460''>done</span> <span m=''368620''>without</span> <span m=''368890''>any</span>
  <span m=''369060''>further</span> <span m=''369320''>mechanism.</span> </p><p><span
  m=''370890''>Now</span> <span m=''371170''>also,</span> <span m=''373640''>if</span>
  <span m=''373710''>we</span> <span m=''373830''>were</span> <span m=''373960''>to</span>
  <span m=''374290''>look</span> <span m=''374450''>at</span> <span m=''374490''>the</span>
  <span m=''374590''>other</span> <span m=''374780''>half,</span> <span m=''374990''>the</span>
  <span m=''375080''>controller,</span> <span m=''375980''>that''s</span> <span m=''376200''>a</span>
  <span m=''376260''>part</span> <span m=''376500''>that''s</span> <span m=''376680''>dumb,</span>
  <span m=''376930''>too.</span> <span m=''378190''>It</span> <span m=''378370''>pushes</span>
  <span m=''378680''>the</span> <span m=''378750''>buttons.</span> <span m=''380350''>It</span>
  <span m=''380500''>pushes</span> <span m=''380830''>them</span> <span m=''380990''>according
  to the</span> <span m=''381150''>sequence,</span> <span m=''381520''>which</span>
  <span m=''381660''>is</span> <span m=''381730''>written</span> <span m=''381920''>down</span>
  <span m=''382120''>on</span> <span m=''382190''>a</span> <span m=''382240''>piece</span>
  <span m=''382410''>of</span> <span m=''382450''>paper,</span> <span m=''384260''>and</span>
  <span m=''384660''>observes</span> <span m=''385090''>the</span> <span m=''385180''>lights.</span>
  </p><p><span m=''386290''>And</span> <span m=''386410''>every</span> <span m=''386560''>so</span>
  <span m=''386730''>often,</span> <span m=''386970''>it</span> <span m=''387040''>comes</span>
  <span m=''387270''>to</span> <span m=''388130''>a</span> <span m=''388180''>place</span>
  <span m=''388500''>in a</span> <span m=''388650''>sequence</span> <span m=''389050''>that</span>
  <span m=''389210''>says,</span> <span m=''389430''>if</span> <span m=''389990''>light
  A</span> <span m=''390350''>is</span> <span m=''390550''>on,</span> <span m=''391265''>do</span>
  <span m=''391580''>this</span> <span m=''391920''>sequence.</span> <span m=''392370''>Otherwise,</span>
  <span m=''392980''>do</span> <span m=''393170''>that</span> <span m=''393420''>sequence.</span>
  <span m=''394620''>And</span> <span m=''394760''>thereby,</span> <span m=''395080''>there''s</span>
  <span m=''395340''>no</span> <span m=''396400''>complexity</span> <span m=''396900''>there</span>
  <span m=''397110''>either.</span> <span m=''397950''>Well,</span> <span m=''398380''>let''s</span>
  <span m=''398710''>just draw</span> <span m=''398990''>that</span> <span m=''399330''>and
  see</span> <span m=''399470''>what</span> <span m=''399570''>we</span> <span m=''399700''>feel</span>
  <span m=''399930''>about</span> <span m=''400250''>that.</span> </p><p><span m=''402510''>So</span>
  <span m=''402790''>for</span> <span m=''403640''>computing</span> <span m=''404050''>GCDs,</span>
  <span m=''405596''>what</span> <span m=''405950''>I</span> <span m=''406060''>want</span>
  <span m=''406240''>you</span> <span m=''406300''>to</span> <span m=''406360''>think</span>
  <span m=''406570''>about</span> <span m=''408090''>is</span> <span m=''408270''>that</span>
  <span m=''408440''>there</span> <span m=''408600''>are</span> <span m=''408640''>these</span>
  <span m=''408830''>registers.</span> <span m=''410310''>A</span> <span m=''410650''>register</span>
  <span m=''411150''>is</span> <span m=''411230''>a</span> <span m=''411290''>place</span>
  <span m=''411590''>where</span> <span m=''411720''>I</span> <span m=''411770''>store
  a</span> <span m=''412120''>number,</span> <span m=''412460''>in</span> <span m=''412530''>this</span>
  <span m=''412710''>case.</span> <span m=''413240''>And</span> <span m=''413520''>this</span>
  <span m=''413710''>one''s</span> <span m=''413890''>called</span> <span m=''414170''>a.</span>
  <span m=''416810''>And</span> <span m=''417030''>then</span> <span m=''417120''>there''s</span>
  <span m=''417300''>another</span> <span m=''417540''>one</span> <span m=''417770''>for</span>
  <span m=''417880''>storing</span> <span m=''418220''>b.</span> </p><p><span m=''423170''>Now</span>
  <span m=''423270''>we</span> <span m=''423360''>have</span> <span m=''423430''>to</span>
  <span m=''423500''>see</span> <span m=''423660''>what</span> <span m=''423850''>things</span>
  <span m=''424060''>we</span> <span m=''424170''>can</span> <span m=''424360''>do</span>
  <span m=''424510''>with</span> <span m=''424640''>these</span> <span m=''424820''>registers,</span>
  <span m=''425780''>and</span> <span m=''426050''>they''re</span> <span m=''426260''>not</span>
  <span m=''426520''>entirely</span> <span m=''427000''>obvious</span> <span m=''427700''>what</span>
  <span m=''427880''>you</span> <span m=''428010''>can</span> <span m=''428150''>do</span>
  <span m=''428340''>with</span> <span m=''428430''>them.</span> <span m=''429840''>Well,</span>
  <span m=''430020''>we</span> <span m=''430110''>have</span> <span m=''430260''>to</span>
  <span m=''430300''>see</span> <span m=''430440''>what</span> <span m=''430770''>things
  we</span> <span m=''430940''>need</span> <span m=''431190''>to</span> <span m=''431260''>do</span>
  <span m=''431410''>with</span> <span m=''431550''>them.</span> <span m=''431890''>We''re</span>
  <span m=''432010''>looking</span> <span m=''432300''>at</span> <span m=''432380''>the</span>
  <span m=''432450''>problem</span> <span m=''432910''>we''re</span> <span m=''433040''>trying</span>
  <span m=''433210''>to</span> <span m=''433390''>solve.</span> </p><p><span m=''434030''>One</span>
  <span m=''434170''>of</span> <span m=''434210''>the</span> <span m=''434330''>important</span>
  <span m=''434750''>things</span> <span m=''434990''>for</span> <span m=''435100''>designing</span>
  <span m=''435530''>a</span> <span m=''435570''>computer,</span> <span m=''437100''>which</span>
  <span m=''437290''>I</span> <span m=''437370''>think</span> <span m=''437590''>most</span>
  <span m=''437840''>designers</span> <span m=''438360''>don''t</span> <span m=''439230''>do,</span>
  <span m=''439920''>is</span> <span m=''440230''>you</span> <span m=''440440''>study</span>
  <span m=''440720''>the</span> <span m=''440810''>problem</span> <span m=''441090''>you</span>
  <span m=''441180''>want</span> <span m=''441320''>to</span> <span m=''441370''>solve</span>
  <span m=''442315''>and</span> <span m=''442750''>then</span> <span m=''442880''>use</span>
  <span m=''443290''>what</span> <span m=''443420''>you</span> <span m=''443540''>learn</span>
  <span m=''443780''>from</span> <span m=''443910''>studying</span> <span m=''444160''>the</span>
  <span m=''444240''>problem</span> <span m=''444460''>you</span> <span m=''444530''>want</span>
  <span m=''444660''>to</span> <span m=''444710''>solve</span> <span m=''445490''>to</span>
  <span m=''445610''>put</span> <span m=''445780''>in</span> <span m=''445900''>the</span>
  <span m=''445970''>mechanisms</span> <span m=''446440''>needed</span> <span m=''446570''>to</span>
  <span m=''446935''>solve it</span> <span m=''447580''>in</span> <span m=''447740''>the</span>
  <span m=''447830''>computer</span> <span m=''448140''>you''re</span> <span m=''448260''>building,</span>
  <span m=''448900''>no</span> <span m=''449110''>more</span> <span m=''449420''>no</span>
  <span m=''449620''>less.</span> <span m=''452140''>Now</span> <span m=''452380''>it</span>
  <span m=''452480''>may</span> <span m=''452650''>be</span> <span m=''452860''>that</span>
  <span m=''452930''>the</span> <span m=''453010''>problem</span> <span m=''453270''>you''re</span>
  <span m=''453350''>trying</span> <span m=''453480''>to</span> <span m=''453610''>solve</span>
  <span m=''454240''>is</span> <span m=''454440''>everybody''s</span> <span m=''454920''>problem,</span>
  <span m=''456120''>in</span> <span m=''456180''>which</span> <span m=''456320''>case</span>
  <span m=''456500''>you</span> <span m=''456600''>have</span> <span m=''456740''>to</span>
  <span m=''456820''>build</span> <span m=''457080''>in</span> <span m=''457180''>a</span>
  <span m=''457200''>universal</span> <span m=''457720''>interpreter</span> <span
  m=''458350''>of</span> <span m=''458520''>some</span> <span m=''458720''>language.</span>
  <span m=''460190''>But</span> <span m=''460310''>you</span> <span m=''460370''>shouldn''t</span>
  <span m=''460610''>put</span> <span m=''460760''>any more</span> <span m=''461200''>in</span>
  <span m=''461690''>than</span> <span m=''461800''>required</span> <span m=''462280''>to</span>
  <span m=''462360''>build the</span> <span m=''462580''>universal</span> <span m=''463080''>interpreter</span>
  <span m=''463440''>of</span> <span m=''463530''>some</span> <span m=''463750''>language.</span>
  <span m=''464540''>We''ll</span> <span m=''464650''>worry</span> <span m=''464860''>about</span>
  <span m=''465080''>that</span> <span m=''465250''>in a</span> <span m=''465320''>second.</span>
  </p><p><span m=''467025''>OK,</span> <span m=''467470''>going</span> <span m=''467690''>back</span>
  <span m=''467950''>to</span> <span m=''468040''>here,</span> <span m=''469490''>let''s</span>
  <span m=''469710''>see.</span> <span m=''469930''>What</span> <span m=''470040''>do</span>
  <span m=''470080''>we</span> <span m=''470210''>have</span> <span m=''470430''>to</span>
  <span m=''470520''>be</span> <span m=''470630''>able</span> <span m=''470810''>to</span>
  <span m=''470900''>do?</span> <span m=''471640''>Well,</span> <span m=''472000''>somehow,</span>
  <span m=''472560''>we have</span> <span m=''472680''>to be able</span> <span m=''472800''>to</span>
  <span m=''473050''>get</span> <span m=''473260''>B</span> <span m=''473440''>into</span>
  <span m=''473700''>A.</span> <span m=''476240''>We</span> <span m=''476410''>have</span>
  <span m=''476580''>to</span> <span m=''476650''>be able</span> <span m=''476890''>to
  get</span> <span m=''477060''>the</span> <span m=''477540''>old</span> <span m=''477900''>value</span>
  <span m=''478220''>of</span> <span m=''478300''>B</span> <span m=''478510''>into</span>
  <span m=''478730''>the</span> <span m=''478830''>value</span> <span m=''479170''>of</span>
  <span m=''479260''>A.</span> <span m=''480030''>So</span> <span m=''480500''>we</span>
  <span m=''480580''>have</span> <span m=''480690''>to</span> <span m=''480780''>have</span>
  <span m=''480880''>some</span> <span m=''481050''>path</span> <span m=''481800''>by</span>
  <span m=''481970''>which</span> <span m=''482430''>stuff</span> <span m=''482840''>can</span>
  <span m=''483040''>flow,</span> <span m=''483340''>whatever</span> <span m=''483660''>this</span>
  <span m=''483840''>information</span> <span m=''484470''>is,</span> <span m=''485700''>from</span>
  <span m=''485860''>b</span> <span m=''486040''>to</span> <span m=''486540''>a.</span>
  <span m=''487390''>I''m</span> <span m=''487510''>going</span> <span m=''487610''>to</span>
  <span m=''487650''>draw</span> <span m=''487900''>that</span> <span m=''488120''>with</span>
  <span m=''488490''>by</span> <span m=''488630''>an</span> <span m=''488720''>arrow</span>
  <span m=''489470''>saying</span> <span m=''490110''>that</span> <span m=''490260''>it
  is</span> <span m=''490520''>possible</span> <span m=''490990''>to</span> <span
  m=''491080''>move</span> <span m=''491270''>the</span> <span m=''491360''>contents</span>
  <span m=''491760''>of</span> <span m=''491850''>b</span> <span m=''492050''>into</span>
  <span m=''492290''>a,</span> <span m=''493020''>replacing</span> <span m=''493570''>the</span>
  <span m=''493640''>value</span> <span m=''494010''>of</span> <span m=''494100''>a.</span>
  <span m=''495120''>And</span> <span m=''495350''>there''s</span> <span m=''495480''>a</span>
  <span m=''495530''>little</span> <span m=''495700''>button</span> <span m=''495990''>here</span>
  <span m=''496170''>which</span> <span m=''496330''>you</span> <span m=''496430''>push</span>
  <span m=''497460''>which</span> <span m=''497660''>allows</span> <span m=''497950''>that</span>
  <span m=''498120''>to</span> <span m=''498180''>happen.</span> <span m=''499710''>That''s
  what</span> <span m=''499840''>the little</span> <span m=''500100''>x is</span>
  <span m=''500520''>here.</span> </p><p><span m=''503070''>Now</span> <span m=''503200''>it''s</span>
  <span m=''503300''>also</span> <span m=''503550''>the</span> <span m=''503650''>case</span>
  <span m=''503980''>that I</span> <span m=''504080''>have</span> <span m=''504260''>to</span>
  <span m=''504350''>be</span> <span m=''504450''>able</span> <span m=''504590''>to</span>
  <span m=''504650''>compute</span> <span m=''505030''>the</span> <span m=''505110''>remainder</span>
  <span m=''505640''>of</span> <span m=''505740''>a</span> <span m=''505880''>and</span>
  <span m=''506160''>b.</span> <span m=''507000''>Now</span> <span m=''507120''>that</span>
  <span m=''507310''>may</span> <span m=''507440''>be</span> <span m=''507570''>a</span>
  <span m=''507610''>complicated</span> <span m=''508120''>mess.</span> <span m=''508860''>On</span>
  <span m=''509020''>the</span> <span m=''509130''>other</span> <span m=''509250''>hand,</span>
  <span m=''509430''>I''m</span> <span m=''509510''>going</span> <span m=''509630''>to</span>
  <span m=''509670''>make</span> <span m=''509870''>it</span> <span m=''509950''>a</span>
  <span m=''510020''>small</span> <span m=''510380''>box.</span> <span m=''511960''>If</span>
  <span m=''512110''>we</span> <span m=''512210''>have</span> <span m=''512460''>to,</span>
  <span m=''512580''>we</span> <span m=''512690''>may</span> <span m=''512830''>open</span>
  <span m=''513110''>up</span> <span m=''513250''>that</span> <span m=''513490''>box</span>
  <span m=''514210''>and</span> <span m=''514320''>look</span> <span m=''514460''>inside</span>
  <span m=''514809''>and</span> <span m=''514890''>see</span> <span m=''514990''>what</span>
  <span m=''515159''>it</span> <span m=''515360''>is.</span> </p><p><span m=''517740''>So</span>
  <span m=''518000''>here,</span> <span m=''518179''>I''m</span> <span m=''518250''>going</span>
  <span m=''518350''>to</span> <span m=''518470''>have</span> <span m=''518600''>a</span>
  <span m=''518640''>little</span> <span m=''518850''>box,</span> <span m=''519220''>which</span>
  <span m=''519360''>I''m</span> <span m=''519450''>going</span> <span m=''519510''>to</span>
  <span m=''519580''>draw</span> <span m=''519799''>this</span> <span m=''519970''>way,</span>
  <span m=''522459''>which</span> <span m=''522893''>we''ll</span> <span m=''523330''>call
  the</span> <span m=''523600''>remainder.</span> <span m=''526440''>And</span> <span
  m=''526670''>it''s</span> <span m=''526790''>going</span> <span m=''526910''>to</span>
  <span m=''527040''>take</span> <span m=''527330''>in</span> <span m=''528010''>a.</span>
  <span m=''530910''>That''s</span> <span m=''531090''>going to</span> <span m=''531220''>take
  in</span> <span m=''531590''>b.</span> <span m=''534370''>And</span> <span m=''534740''>it''s</span>
  <span m=''534840''>going</span> <span m=''535010''>to</span> <span m=''535070''>put</span>
  <span m=''535270''>out</span> <span m=''535830''>something,</span> <span m=''539000''>the</span>
  <span m=''539110''>remainder</span> <span m=''539480''>of</span> <span m=''539570''>a</span>
  <span m=''539660''>divided</span> <span m=''539960''>by</span> <span m=''540090''>b.</span>
  </p><p><span m=''542290''>Another</span> <span m=''542600''>thing</span> <span m=''542750''>we</span>
  <span m=''542830''>have</span> <span m=''542960''>to</span> <span m=''543020''>see
  here</span> <span m=''543510''>is</span> <span m=''543640''>that we</span> <span
  m=''543750''>have</span> <span m=''543900''>to</span> <span m=''543970''>be able
  to</span> <span m=''544210''>test</span> <span m=''544580''>whether</span> <span
  m=''545010''>b</span> <span m=''545200''>is</span> <span m=''545330''>equal</span>
  <span m=''545560''>to</span> <span m=''545620''>0.</span> <span m=''548000''>Well,</span>
  <span m=''548180''>that</span> <span m=''548300''>means</span> <span m=''548430''>somebody''s</span>
  <span m=''548760''>got</span> <span m=''548850''>to</span> <span m=''548940''>be</span>
  <span m=''549030''>looking</span> <span m=''549410''>at--</span> <span m=''550020''>a</span>
  <span m=''550210''>thing</span> <span m=''550410''>that''s</span> <span m=''550610''>looking</span>
  <span m=''550960''>at</span> <span m=''551090''>the</span> <span m=''551180''>value</span>
  <span m=''551680''>of</span> <span m=''551780''>b.</span> <span m=''553390''>I</span>
  <span m=''553470''>have</span> <span m=''553560''>a</span> <span m=''553620''>light</span>
  <span m=''553890''>bulb</span> <span m=''554155''>here</span> <span m=''555920''>which</span>
  <span m=''556140''>lights</span> <span m=''556420''>up</span> <span m=''556560''>if
  b</span> <span m=''556740''>equals</span> <span m=''557080''>0.</span> <span m=''561110''>That''s</span>
  <span m=''561360''>its</span> <span m=''561540''>job.</span> </p><p><span m=''564030''>And</span>
  <span m=''564290''>finally,</span> <span m=''564980''>I</span> <span m=''565120''>suppose,</span>
  <span m=''565830''>because</span> <span m=''566260''>of</span> <span m=''566330''>the</span>
  <span m=''566400''>fact</span> <span m=''566990''>that</span> <span m=''567130''>we</span>
  <span m=''567250''>want</span> <span m=''567900''>the</span> <span m=''568230''>new</span>
  <span m=''568380''>value</span> <span m=''568890''>of</span> <span m=''569020''>a</span>
  <span m=''569310''>to</span> <span m=''569430''>be the</span> <span m=''569630''>old</span>
  <span m=''569870''>value</span> <span m=''570160''>of</span> <span m=''570210''>b,</span>
  <span m=''570500''>and</span> <span m=''570640''>simultaneously</span> <span m=''572030''>the</span>
  <span m=''572210''>new</span> <span m=''572360''>value</span> <span m=''572690''>of</span>
  <span m=''572750''>b</span> <span m=''572970''>to</span> <span m=''573040''>be</span>
  <span m=''573170''>something</span> <span m=''573520''>I''ve</span> <span m=''573630''>done</span>
  <span m=''573820''>with</span> <span m=''574080''>a,</span> <span m=''575270''>and</span>
  <span m=''575430''>if</span> <span m=''575550''>I</span> <span m=''576320''>plan</span>
  <span m=''576550''>to</span> <span m=''576640''>make</span> <span m=''576820''>my</span>
  <span m=''576990''>machine</span> <span m=''577780''>such</span> <span m=''578020''>that</span>
  <span m=''578160''>everything</span> <span m=''578510''>happens</span> <span m=''578870''>one</span>
  <span m=''579080''>at</span> <span m=''579150''>a</span> <span m=''579230''>time,</span>
  <span m=''580230''>one</span> <span m=''580420''>motion</span> <span m=''580810''>at</span>
  <span m=''580900''>a</span> <span m=''580990''>time,</span> <span m=''581620''>and</span>
  <span m=''581750''>I</span> <span m=''581810''>can''t</span> <span m=''582080''>put</span>
  <span m=''582250''>two</span> <span m=''582370''>numbers</span> <span m=''582730''>in</span>
  <span m=''582790''>a</span> <span m=''582850''>register,</span> <span m=''584100''>then
  I</span> <span m=''584460''>have to have</span> <span m=''584560''>another</span>
  <span m=''584780''>place</span> <span m=''585000''>to</span> <span m=''585080''>put</span>
  <span m=''585250''>one</span> <span m=''585430''>while</span> <span m=''585780''>I''m</span>
  <span m=''585870''>interchanging.</span> <span m=''589534''>OK?</span> <span m=''590000''>I</span>
  <span m=''590110''>can''t</span> <span m=''590470''>interchange</span> <span m=''590710''>the</span>
  <span m=''590790''>two</span> <span m=''590930''>things</span> <span m=''591150''>in</span>
  <span m=''591210''>my</span> <span m=''591350''>hands,</span> <span m=''592110''>unless</span>
  <span m=''592400''>I</span> <span m=''592490''>either</span> <span m=''592670''>put</span>
  <span m=''593030''>two</span> <span m=''593240''>in</span> <span m=''593320''>one</span>
  <span m=''593500''>hand</span> <span m=''593730''>and</span> <span m=''593830''>then</span>
  <span m=''594070''>pull it</span> <span m=''594260''>back</span> <span m=''594480''>the</span>
  <span m=''594600''>other</span> <span m=''594730''>way,</span> <span m=''595420''>or</span>
  <span m=''595780''>unless</span> <span m=''595950''>I</span> <span m=''596000''>put</span>
  <span m=''596190''>one</span> <span m=''596450''>down,</span> <span m=''597040''>pick</span>
  <span m=''597210''>it</span> <span m=''597290''>up,</span> <span m=''597420''>and</span>
  <span m=''597560''>put</span> <span m=''597710''>the</span> <span m=''597840''>other</span>
  <span m=''597960''>one,</span> <span m=''598110''>like</span> <span m=''598330''>that,</span>
  <span m=''599660''>unless</span> <span m=''600130''>I''m</span> <span m=''600260''>a</span>
  <span m=''600390''>juggler,</span> <span m=''601580''>which</span> <span m=''601920''>I''m</span>
  <span m=''602060''>not,</span> <span m=''602430''>as</span> <span m=''602800''>you</span>
  <span m=''602930''>can</span> <span m=''603090''>see,</span> <span m=''604780''>in</span>
  <span m=''604920''>which</span> <span m=''605150''>case</span> <span m=''605910''>I</span>
  <span m=''605980''>have</span> <span m=''606090''>a</span> <span m=''606200''>possibility
  of</span> <span m=''606680''>timing</span> <span m=''606950''>errors.</span> <span
  m=''608850''>In</span> <span m=''609110''>fact,</span> <span m=''609390''>much</span>
  <span m=''609580''>of</span> <span m=''609690''>the</span> <span m=''610140''>type</span>
  <span m=''610370''>of</span> <span m=''610440''>computer</span> <span m=''610760''>design</span>
  <span m=''611060''>people</span> <span m=''611330''>do</span> <span m=''611500''>involves</span>
  <span m=''611840''>timing</span> <span m=''612180''>errors,</span> <span m=''612710''>of</span>
  <span m=''613190''>some</span> <span m=''613460''>potential</span> <span m=''614290''>timing</span>
  <span m=''614610''>errors,</span> <span m=''615260''>which</span> <span m=''615450''>I</span>
  <span m=''615510''>don''t</span> <span m=''615700''>much</span> <span m=''615930''>like.</span>
  </p><p><span m=''617840''>So</span> <span m=''618040''>for</span> <span m=''618170''>that</span>
  <span m=''618410''>reason,</span> <span m=''618830''>I</span> <span m=''618890''>have</span>
  <span m=''619100''>to have a</span> <span m=''619240''>place</span> <span m=''619480''>to</span>
  <span m=''619560''>put</span> <span m=''619760''>the</span> <span m=''622230''>second</span>
  <span m=''622500''>one</span> <span m=''622630''>of</span> <span m=''622730''>them</span>
  <span m=''622830''>down.</span> <span m=''623410''>So</span> <span m=''623560''>I</span>
  <span m=''623610''>have</span> <span m=''623710''>a</span> <span m=''623790''>place</span>
  <span m=''624140''>called</span> <span m=''624430''>t,</span> <span m=''624730''>which</span>
  <span m=''624880''>is</span> <span m=''624960''>a</span> <span m=''625010''>register</span>
  <span m=''625370''>just for</span> <span m=''625820''>temporary,</span> <span m=''626300''>t,</span>
  <span m=''628336''>with</span> <span m=''628800''>a</span> <span m=''628870''>button</span>
  <span m=''629180''>on</span> <span m=''629360''>it.</span> <span m=''630470''>And</span>
  <span m=''630610''>then</span> <span m=''630740''>I''ll</span> <span m=''630850''>take</span>
  <span m=''631070''>the</span> <span m=''631150''>result</span> <span m=''631580''>of</span>
  <span m=''631620''>that,</span> <span m=''631870''>since</span> <span m=''632030''>I</span>
  <span m=''632170''>have to take</span> <span m=''632450''>that</span> <span m=''632660''>and</span>
  <span m=''632770''>put</span> <span m=''632910''>into</span> <span m=''633200''>b,</span>
  <span m=''633560''>over</span> <span m=''633740''>here,</span> <span m=''634760''>we''ll</span>
  <span m=''634950''>take</span> <span m=''635140''>the</span> <span m=''635210''>result</span>
  <span m=''635570''>of</span> <span m=''635640''>that</span> <span m=''635870''>and
  go</span> <span m=''636110''>like</span> <span m=''636350''>this,</span> <span m=''638392''>and</span>
  <span m=''638800''>a button</span> <span m=''638880''>here.</span> <span m=''642430''>So</span>
  <span m=''642610''>that''s</span> <span m=''642910''>the</span> <span m=''643030''>datapaths</span>
  <span m=''644840''>of</span> <span m=''644970''>a</span> <span m=''645130''>GCD</span>
  <span m=''645420''>machine.</span> </p><p><span m=''647600''>Now</span> <span m=''647740''>what''s
  the</span> <span m=''647950''>controller?</span> <span m=''649740''>Controller''s</span>
  <span m=''650090''>a</span> <span m=''650130''>very</span> <span m=''650370''>simple</span>
  <span m=''650690''>thing,</span> <span m=''650930''>too.</span> <span m=''652280''>The</span>
  <span m=''652380''>machine</span> <span m=''652510''>has</span> <span m=''652740''>a</span>
  <span m=''652790''>state.</span> </p><p><span m=''653710''>The</span> <span m=''654140''>way</span>
  <span m=''654440''>I</span> <span m=''654740''>like</span> <span m=''654910''>to</span>
  <span m=''655000''>visualize</span> <span m=''655630''>that</span> <span m=''656640''>is
  that</span> <span m=''656840''>I''ve</span> <span m=''657030''>got</span> <span
  m=''657170''>a</span> <span m=''657220''>maze.</span> <span m=''659010''>And</span>
  <span m=''659150''>the</span> <span m=''659220''>maze</span> <span m=''659720''>has</span>
  <span m=''660730''>a</span> <span m=''660810''>bunch</span> <span m=''661050''>of</span>
  <span m=''661130''>places</span> <span m=''661680''>connected</span> <span m=''662030''>by</span>
  <span m=''662170''>directed</span> <span m=''662590''>arrows.</span> <span m=''664430''>And</span>
  <span m=''664620''>what</span> <span m=''664740''>I</span> <span m=''664790''>have</span>
  <span m=''665000''>is a</span> <span m=''665090''>marble,</span> <span m=''666560''>which</span>
  <span m=''666740''>represents</span> <span m=''667800''>the</span> <span m=''668080''>state</span>
  <span m=''668350''>of</span> <span m=''668430''>the</span> <span m=''668500''>controller.</span>
  <span m=''670740''>The</span> <span m=''670840''>marble</span> <span m=''671200''>rolls</span>
  <span m=''671440''>around</span> <span m=''671770''>in the</span> <span m=''671840''>maze.</span>
  <span m=''673256''>Of</span> <span m=''673740''>course,</span> <span m=''675100''>this</span>
  <span m=''675470''>analogy</span> <span m=''675940''>breaks</span> <span m=''676180''>down</span>
  <span m=''676360''>for</span> <span m=''676470''>energy</span> <span m=''676830''>reasons.</span>
  <span m=''677150''>I</span> <span m=''677240''>sometimes</span> <span m=''677590''>have</span>
  <span m=''677690''>to</span> <span m=''677760''>pump</span> <span m=''678020''>the</span>
  <span m=''678130''>marble</span> <span m=''678490''>up to</span> <span m=''678580''>the</span>
  <span m=''678780''>top,</span> <span m=''679190''>because</span> <span m=''679310''>it''s
  going</span> <span m=''679440''>to</span> <span m=''679780''>otherwise</span> <span
  m=''680150''>be</span> <span m=''680370''>a</span> <span m=''680680''>perpetual</span>
  <span m=''681070''>motion</span> <span m=''681370''>machine.</span> <span m=''682000''>But</span>
  <span m=''682190''>not</span> <span m=''682370''>worrying</span> <span m=''682690''>about</span>
  <span m=''683000''>that,</span> <span m=''684070''>this</span> <span m=''684210''>is</span>
  <span m=''684270''>not</span> <span m=''684860''>a</span> <span m=''684910''>physical</span>
  <span m=''685320''>analogy.</span> </p><p><span m=''686080''>This</span> <span m=''686270''>marble</span>
  <span m=''686660''>rolls</span> <span m=''686930''>around.</span> <span m=''687680''>And</span>
  <span m=''687830''>every</span> <span m=''688020''>time</span> <span m=''688210''>it</span>
  <span m=''688270''>rolls</span> <span m=''688530''>around</span> <span m=''688770''>certain</span>
  <span m=''689020''>bumpers,</span> <span m=''689730''>like</span> <span m=''689960''>in</span>
  <span m=''690060''>a</span> <span m=''690180''>pinball</span> <span m=''690540''>machine,</span>
  <span m=''691480''>it</span> <span m=''691640''>pushes</span> <span m=''691740''>one</span>
  <span m=''691890''>of</span> <span m=''691930''>these</span> <span m=''692120''>buttons.</span>
  <span m=''694830''>And</span> <span m=''694980''>every</span> <span m=''695180''>so</span>
  <span m=''695350''>often,</span> <span m=''695660''>it</span> <span m=''695740''>comes</span>
  <span m=''695980''>to</span> <span m=''696080''>a</span> <span m=''696150''>place,</span>
  <span m=''696490''>which</span> <span m=''696640''>is</span> <span m=''696750''>a</span>
  <span m=''696810''>division,</span> <span m=''698302''>where</span> <span m=''698700''>it
  has to</span> <span m=''699040''>make</span> <span m=''699180''>a</span> <span m=''699230''>choice.</span>
  <span m=''700250''>And</span> <span m=''700400''>there''s</span> <span m=''700540''>a</span>
  <span m=''700590''>flap,</span> <span m=''701170''>which</span> <span m=''701320''>is</span>
  <span m=''701420''>controlled</span> <span m=''701810''>by</span> <span m=''701940''>this.</span>
  <span m=''706000''>So</span> <span m=''706220''>that''s</span> <span m=''706600''>a</span>
  <span m=''706740''>really</span> <span m=''707210''>mechanical</span> <span m=''707940''>way</span>
  <span m=''708090''>of</span> <span m=''708180''>thinking</span> <span m=''708460''>about</span>
  <span m=''708660''>it.</span> </p><p><span m=''708820''>Of</span> <span m=''708910''>course,</span>
  <span m=''709120''>controllers</span> <span m=''709830''>these</span> <span m=''710000''>days,</span>
  <span m=''710230''>are</span> <span m=''710310''>not</span> <span m=''710510''>built</span>
  <span m=''710720''>that</span> <span m=''710900''>way in</span> <span m=''711060''>real</span>
  <span m=''711330''>computers.</span> <span m=''711840''>They''re</span> <span m=''712095''>built</span>
  <span m=''712350''>with</span> <span m=''713300''>a</span> <span m=''713660''>little</span>
  <span m=''713850''>bit</span> <span m=''713980''>of</span> <span m=''714090''>ROM</span>
  <span m=''714900''>and</span> <span m=''715160''>a</span> <span m=''715240''>state</span>
  <span m=''715490''>register.</span> <span m=''716610''>But</span> <span m=''716800''>there</span>
  <span m=''716910''>was</span> <span m=''717040''>a</span> <span m=''717100''>time,</span>
  <span m=''717410''>like</span> <span m=''717600''>the</span> <span m=''717690''>DEC</span>
  <span m=''718015''>PDP-6,</span> <span m=''719040''>where</span> <span m=''719390''>that''s</span>
  <span m=''719630''>how you built</span> <span m=''719920''>the</span> <span m=''719970''>controller</span>
  <span m=''720300''>of a</span> <span m=''720380''>machine.</span> <span m=''721400''>There</span>
  <span m=''721980''>was</span> <span m=''722090''>a</span> <span m=''722130''>bit</span>
  <span m=''722310''>that</span> <span m=''722610''>ran</span> <span m=''722820''>around
  the</span> <span m=''722940''>delay</span> <span m=''723220''>line,</span> <span
  m=''725870''>and</span> <span m=''725990''>it</span> <span m=''726800''>triggered</span>
  <span m=''727110''>things</span> <span m=''727340''>as</span> <span m=''727420''>it</span>
  <span m=''727500''>went</span> <span m=''727690''>by.</span> <span m=''728580''>And</span>
  <span m=''728700''>it</span> <span m=''728740''>would</span> <span m=''728840''>come</span>
  <span m=''728980''>back</span> <span m=''729170''>to</span> <span m=''729320''>the</span>
  <span m=''729440''>beginning</span> <span m=''729810''>and</span> <span m=''729860''>get</span>
  <span m=''730090''>fed round</span> <span m=''730330''>again.</span> </p><p><span
  m=''731990''>And</span> <span m=''732100''>of</span> <span m=''732160''>course,</span>
  <span m=''732420''>there</span> <span m=''732550''>were all</span> <span m=''732770''>sorts
  of</span> <span m=''732870''>great</span> <span m=''733090''>bugs</span> <span m=''733350''>you</span>
  <span m=''733510''>could have</span> <span m=''733750''>like</span> <span m=''734260''>two</span>
  <span m=''734390''>bits</span> <span m=''734650''>going</span> <span m=''734820''>around,</span>
  <span m=''737060''>two</span> <span m=''737250''>marbles.</span> <span m=''737670''>And
  then</span> <span m=''737760''>the</span> <span m=''737850''>machine</span> <span
  m=''738090''>has</span> <span m=''738220''>lost</span> <span m=''738470''>its</span>
  <span m=''738580''>marbles.</span> <span m=''739260''>That</span> <span m=''739750''>happens,</span>
  <span m=''739860''>too.</span> <span m=''740980''>Oh,</span> <span m=''741160''>well.</span>
  </p><p><span m=''741935''>So</span> <span m=''742430''>anyway,</span> <span m=''743400''>for</span>
  <span m=''743540''>this</span> <span m=''743730''>machine,</span> <span m=''744260''>what</span>
  <span m=''744400''>I</span> <span m=''744480''>have</span> <span m=''744570''>to</span>
  <span m=''744660''>do</span> <span m=''744830''>is</span> <span m=''744920''>the</span>
  <span m=''744990''>following.</span> <span m=''745940''>I''m</span> <span m=''746020''>going</span>
  <span m=''746380''>to</span> <span m=''746720''>start</span> <span m=''746980''>my</span>
  <span m=''747090''>maze</span> <span m=''747250''>here.</span> <span m=''750520''>And</span>
  <span m=''751470''>the</span> <span m=''751650''>first</span> <span m=''751830''>thing</span>
  <span m=''751990''>I''ve</span> <span m=''752070''>got</span> <span m=''752210''>to</span>
  <span m=''752290''>do,</span> <span m=''754430''>in</span> <span m=''754710''>a</span>
  <span m=''754750''>notation</span> <span m=''755280''>which</span> <span m=''755460''>many</span>
  <span m=''755680''>of</span> <span m=''755760''>you</span> <span m=''755890''>are</span>
  <span m=''755940''>familiar</span> <span m=''756390''>with,</span> <span m=''757110''>is</span>
  <span m=''757360''>b</span> <span m=''757560''>equal</span> <span m=''757880''>to</span>
  <span m=''757960''>zero,</span> <span m=''759340''>a</span> <span m=''759440''>test.</span>
  <span m=''761540''>And</span> <span m=''761690''>there''s</span> <span m=''761790''>a</span>
  <span m=''761840''>possibility,</span> <span m=''762860''>either</span> <span m=''763270''>yes,</span>
  <span m=''764410''>in</span> <span m=''764540''>which</span> <span m=''764710''>case</span>
  <span m=''764940''>I''m</span> <span m=''765080''>done.</span> <span m=''769790''>Otherwise,</span>
  <span m=''770480''>if</span> <span m=''770700''>no,</span> <span m=''772380''>then</span>
  <span m=''772790''>I''m</span> <span m=''772940''>going</span> <span m=''773030''>have
  to</span> <span m=''773220''>roll</span> <span m=''773510''>over</span> <span m=''773670''>some</span>
  <span m=''773830''>bumpers.</span> </p><p><span m=''774725''>I''m</span> <span m=''775080''>going</span>
  <span m=''775250''>to</span> <span m=''775290''>do</span> <span m=''775470''>it
  in</span> <span m=''775570''>the</span> <span m=''775650''>following</span> <span
  m=''776050''>order.</span> <span m=''777420''>I</span> <span m=''777560''>want</span>
  <span m=''777880''>to</span> <span m=''781630''>do</span> <span m=''781760''>this</span>
  <span m=''781960''>interchange</span> <span m=''783030''>game.</span> <span m=''784050''>Now</span>
  <span m=''784190''>first,</span> <span m=''784450''>since</span> <span m=''784580''>I</span>
  <span m=''784660''>need</span> <span m=''784880''>both</span> <span m=''785140''>a</span>
  <span m=''785250''>and</span> <span m=''785380''>b,</span> <span m=''786380''>but</span>
  <span m=''786690''>then</span> <span m=''787040''>the</span> <span m=''787110''>first--</span>
  <span m=''787360''>and</span> <span m=''787620''>this</span> <span m=''787750''>is</span>
  <span m=''787830''>not</span> <span m=''788020''>necessary--</span> <span m=''788670''>I</span>
  <span m=''788800''>want</span> <span m=''788970''>to</span> <span m=''789030''>collect</span>
  <span m=''789390''>this.</span> <span m=''791070''>This</span> <span m=''791200''>is</span>
  <span m=''791300''>the</span> <span m=''791410''>thing</span> <span m=''791560''>that''s</span>
  <span m=''791710''>going</span> <span m=''791830''>to</span> <span m=''791870''>go</span>
  <span m=''792020''>into</span> <span m=''792170''>b.</span> <span m=''793240''>So</span>
  <span m=''793400''>I''m</span> <span m=''793500''>going</span> <span m=''793590''>to</span>
  <span m=''793680''>say,</span> <span m=''794280''>take</span> <span m=''794540''>this,</span>
  <span m=''794870''>which</span> <span m=''795030''>depends</span> <span m=''795380''>upon</span>
  <span m=''795580''>both</span> <span m=''795680''>a</span> <span m=''795810''>and</span>
  <span m=''795920''>b,</span> <span m=''796430''>and</span> <span m=''796630''>put</span>
  <span m=''797640''>the</span> <span m=''797740''>remainder</span> <span m=''798160''>into</span>
  <span m=''798330''>here.</span> <span m=''799150''>So</span> <span m=''799280''>I''m
  going to</span> <span m=''799380''>push</span> <span m=''799550''>this</span> <span
  m=''799750''>button</span> <span m=''799990''>first.</span> <span m=''801540''>Then,</span>
  <span m=''802500''>I''m</span> <span m=''802710''>going</span> <span m=''802940''>to</span>
  <span m=''803320''>transfer</span> <span m=''803830''>b</span> <span m=''804010''>to
  a,</span> <span m=''804490''>push</span> <span m=''804680''>that</span> <span m=''804960''>button,</span>
  <span m=''805820''>and</span> <span m=''805940''>then I</span> <span m=''806060''>transfer</span>
  <span m=''806460''>the</span> <span m=''806550''>temporary</span> <span m=''807020''>into</span>
  <span m=''807270''>b,</span> <span m=''808810''>push</span> <span m=''809020''>that</span>
  <span m=''809240''>button.</span> <span m=''812030''>So</span> <span m=''813332''>a</span>
  <span m=''813710''>very</span> <span m=''813960''>sequential</span> <span m=''814440''>machine,</span>
  <span m=''815190''>it''s</span> <span m=''815530''>very</span> <span m=''815830''>inefficient.</span>
  <span m=''817750''>But</span> <span m=''817880''>that''s</span> <span m=''818100''>fine</span>
  <span m=''818370''>right</span> <span m=''818590''>now.</span> </p><p><span m=''819810''>We''re</span>
  <span m=''819990''>going</span> <span m=''820100''>to</span> <span m=''820190''>name</span>
  <span m=''820420''>the</span> <span m=''820500''>buttons,</span> <span m=''821460''>t</span>
  <span m=''821630''>gets</span> <span m=''821950''>remainder.</span> <span m=''826750''>a</span>
  <span m=''827070''>gets</span> <span m=''828230''>b.</span> <span m=''830036''>And</span>
  <span m=''833350''>b</span> <span m=''833700''>gets</span> <span m=''834210''>t.</span>
  <span m=''835470''>And</span> <span m=''835590''>then</span> <span m=''835740''>I''m</span>
  <span m=''835850''>going</span> <span m=''836010''>to</span> <span m=''836120''>go</span>
  <span m=''836330''>around</span> <span m=''837270''>here</span> <span m=''838800''>and</span>
  <span m=''838920''>it''s to go</span> <span m=''839150''>back</span> <span m=''839330''>to</span>
  <span m=''839410''>start.</span> </p><p><span m=''841620''>And</span> <span m=''841830''>if</span>
  <span m=''841920''>you</span> <span m=''842080''>look,</span> <span m=''842740''>what</span>
  <span m=''842990''>are</span> <span m=''843030''>we</span> <span m=''843170''>seeing</span>
  <span m=''843530''>here?</span> <span m=''843870''>We''re</span> <span m=''844010''>seeing</span>
  <span m=''844330''>the</span> <span m=''844420''>various--</span> <span m=''845080''>what</span>
  <span m=''845270''>I</span> <span m=''845320''>really</span> <span m=''845520''>have
  is</span> <span m=''845730''>some sort of</span> <span m=''846050''>mechanical</span>
  <span m=''846610''>connection,</span> <span m=''847400''>where</span> <span m=''847640''>t</span>
  <span m=''847800''>gets</span> <span m=''848070''>r</span> <span m=''849280''>controls</span>
  <span m=''853050''>this</span> <span m=''853320''>thing.</span> <span m=''856830''>And</span>
  <span m=''857060''>I</span> <span m=''857150''>have</span> <span m=''857380''>here</span>
  <span m=''857870''>that</span> <span m=''858000''>a</span> <span m=''858190''>gets</span>
  <span m=''858520''>b</span> <span m=''859190''>controls</span> <span m=''860150''>this</span>
  <span m=''860390''>fellow</span> <span m=''860740''>over</span> <span m=''860910''>here,</span>
  <span m=''866910''>and</span> <span m=''867250''>this</span> <span m=''867400''>fellow</span>
  <span m=''867640''>over</span> <span m=''867860''>here.</span> </p><p><span m=''868120''>Boy,</span>
  <span m=''868320''>that''s</span> <span m=''868610''>absolutely</span> <span m=''870820''>pessimal,</span>
  <span m=''871090''>the</span> <span m=''871530''>inverse of</span> <span m=''871890''>optimal.</span>
  <span m=''872630''>Every</span> <span m=''872860''>line heads</span> <span m=''873190''>across</span>
  <span m=''873460''>every other</span> <span m=''873690''>line</span> <span m=''874020''>the
  way</span> <span m=''874160''>I</span> <span m=''874220''>drew</span> <span m=''874460''>it.</span>
  <span m=''878540''>I</span> <span m=''878670''>suppose</span> <span m=''879040''>this</span>
  <span m=''879210''>goes</span> <span m=''879440''>here,</span> <span m=''880195''>b</span>
  <span m=''880570''>gets</span> <span m=''880860''>t.</span> </p><p><span m=''885690''>Now</span>
  <span m=''886190''>I''d</span> <span m=''886300''>like</span> <span m=''886460''>to</span>
  <span m=''886890''>run</span> <span m=''887180''>this</span> <span m=''887380''>machine.</span>
  <span m=''888040''>But</span> <span m=''888240''>before</span> <span m=''888560''>I</span>
  <span m=''888680''>run</span> <span m=''888870''>the</span> <span m=''888950''>machine,</span>
  <span m=''889320''>I</span> <span m=''889430''>want</span> <span m=''889650''>to</span>
  <span m=''889690''>write</span> <span m=''889970''>down</span> <span m=''890200''>a</span>
  <span m=''890260''>description</span> <span m=''890750''>of</span> <span m=''890830''>this</span>
  <span m=''890950''>controller,</span> <span m=''891640''>just</span> <span m=''891870''>so
  you</span> <span m=''892210''>can see that</span> <span m=''892310''>these</span>
  <span m=''892530''>things,</span> <span m=''892730''>of</span> <span m=''892820''>course,</span>
  <span m=''893090''>as</span> <span m=''893300''>usual,</span> <span m=''893920''>can</span>
  <span m=''894060''>be</span> <span m=''894160''>written</span> <span m=''894340''>down
  in</span> <span m=''894600''>some</span> <span m=''894790''>nice</span> <span m=''895050''>language,</span>
  <span m=''896060''>so that</span> <span m=''896300''>we</span> <span m=''896400''>don''t</span>
  <span m=''896560''>have</span> <span m=''896700''>to</span> <span m=''896850''>always</span>
  <span m=''897130''>draw</span> <span m=''897300''>these</span> <span m=''897450''>diagrams.</span>
  <span m=''898380''>One</span> <span m=''898580''>of</span> <span m=''898630''>the</span>
  <span m=''898690''>problems</span> <span m=''899010''>with</span> <span m=''899110''>diagrams</span>
  <span m=''899560''>is that</span> <span m=''899670''>they</span> <span m=''899780''>take
  up</span> <span m=''899860''>a</span> <span m=''899910''>lot</span> <span m=''900140''>of</span>
  <span m=''900210''>space.</span> <span m=''900710''>And</span> <span m=''901060''>for
  a</span> <span m=''901180''>machine</span> <span m=''901500''>this</span> <span
  m=''901740''>small,</span> <span m=''901980''>it</span> <span m=''902030''>takes</span>
  <span m=''902250''>two</span> <span m=''902380''>blackboards.</span> <span m=''903220''>For
  a</span> <span m=''903360''>machine</span> <span m=''904010''>that''s</span> <span
  m=''904200''>the</span> <span m=''904490''>evaluator</span> <span m=''904780''>machine,</span>
  <span m=''905410''>I</span> <span m=''905520''>have</span> <span m=''905690''>trouble</span>
  <span m=''905990''>putting</span> <span m=''906240''>it</span> <span m=''906310''>into</span>
  <span m=''906440''>this</span> <span m=''906600''>room,</span> <span m=''907990''>even</span>
  <span m=''908180''>though</span> <span m=''908320''>it</span> <span m=''908390''>isn''t</span>
  <span m=''908510''>very</span> <span m=''908760''>big.</span> <span m=''909900''>So</span>
  <span m=''910070''>I''m</span> <span m=''910140''>going</span> <span m=''910220''>to</span>
  <span m=''910260''>make</span> <span m=''910400''>a little</span> <span m=''910450''>language</span>
  <span m=''911010''>for</span> <span m=''911100''>this</span> <span m=''911290''>that''s</span>
  <span m=''911360''>just</span> <span m=''911550''>a</span> <span m=''911600''>description</span>
  <span m=''912110''>of</span> <span m=''912190''>that,</span> <span m=''912945''>saying</span>
  <span m=''913340''>define</span> <span m=''917440''>a</span> <span m=''917530''>machine</span>
  <span m=''922130''>we''ll</span> <span m=''922150''>call</span> <span m=''922370''>GCD.</span>
  </p><p><span m=''924420''>Of</span> <span m=''924480''>course,</span> <span m=''924680''>once</span>
  <span m=''924890''>we</span> <span m=''925000''>have</span> <span m=''925220''>something</span>
  <span m=''925440''>like</span> <span m=''925590''>this,</span> <span m=''925730''>we</span>
  <span m=''925810''>have</span> <span m=''925930''>a</span> <span m=''925970''>simulator</span>
  <span m=''926450''>for</span> <span m=''926725''>it.</span> <span m=''927220''>And</span>
  <span m=''927320''>the</span> <span m=''927390''>reason</span> <span m=''927610''>why</span>
  <span m=''927730''>we</span> <span m=''927830''>want</span> <span m=''928130''>to
  build a</span> <span m=''928240''>language</span> <span m=''928740''>in</span> <span
  m=''928810''>this</span> <span m=''928980''>form,</span> <span m=''929630''>is</span>
  <span m=''929790''>because</span> <span m=''930290''>all</span> <span m=''930380''>of</span>
  <span m=''930480''>a</span> <span m=''930510''>sudden</span> <span m=''930700''>we</span>
  <span m=''930790''>can</span> <span m=''930900''>manipulate</span> <span m=''931300''>these</span>
  <span m=''931500''>expressions</span> <span m=''931795''>that</span> <span m=''932090''>I''m</span>
  <span m=''932200''>writing</span> <span m=''932450''>down.</span> <span m=''933210''>And</span>
  <span m=''933570''>then</span> <span m=''933690''>of</span> <span m=''933760''>course</span>
  <span m=''933960''>I</span> <span m=''934020''>can</span> <span m=''934140''>write</span>
  <span m=''934320''>things</span> <span m=''934510''>that</span> <span m=''934590''>can</span>
  <span m=''935320''>algebraically</span> <span m=''935970''>manipulate</span> <span
  m=''936440''>these</span> <span m=''936660''>things,</span> <span m=''937120''>simulate</span>
  <span m=''937720''>them,</span> <span m=''938200''>all</span> <span m=''938360''>that</span>
  <span m=''938580''>sort</span> <span m=''938730''>of</span> <span m=''939080''>things</span>
  <span m=''939320''>that I</span> <span m=''939380''>might</span> <span m=''939580''>want</span>
  <span m=''939670''>to</span> <span m=''939720''>do,</span> <span m=''940120''>perhaps</span>
  <span m=''940430''>transform</span> <span m=''940910''>them</span> <span m=''941140''>as
  a</span> <span m=''941370''>layout,</span> <span m=''942140''>who</span> <span m=''942250''>knows.</span>
  <span m=''943630''>Once</span> <span m=''943920''>I</span> <span m=''944030''>have</span>
  <span m=''944300''>a</span> <span m=''945440''>nice</span> <span m=''945970''>representation</span>
  <span m=''947650''>of</span> <span m=''947780''>registers,</span> <span m=''948185''>it</span>
  <span m=''948590''>has</span> <span m=''948770''>certain</span> <span m=''948990''>registers,</span>
  <span m=''952640''>which</span> <span m=''953140''>we can</span> <span m=''953270''>call</span>
  <span m=''953550''>A,</span> <span m=''954280''>B,</span> <span m=''954690''>and</span>
  <span m=''954970''>T.</span> <span m=''956326''>And</span> <span m=''956810''>there''s</span>
  <span m=''957030''>a</span> <span m=''957110''>controller.</span> </p><p><span m=''962190''>Actually,
  a</span> <span m=''962500''>better</span> <span m=''962810''>language,</span> <span
  m=''963230''>which</span> <span m=''963360''>would</span> <span m=''963460''>be</span>
  <span m=''963560''>more</span> <span m=''963780''>explicit,</span> <span m=''964910''>would</span>
  <span m=''965040''>be</span> <span m=''965180''>one</span> <span m=''965420''>which</span>
  <span m=''965650''>named</span> <span m=''966150''>every</span> <span m=''966480''>button</span>
  <span m=''968180''>also</span> <span m=''969270''>and</span> <span m=''969440''>said</span>
  <span m=''969610''>what</span> <span m=''969750''>it</span> <span m=''969770''>did.</span>
  <span m=''970420''>Like,</span> <span m=''970630''>this</span> <span m=''970910''>button</span>
  <span m=''971610''>causes</span> <span m=''972110''>the</span> <span m=''972220''>contents</span>
  <span m=''972680''>of</span> <span m=''972780''>T</span> <span m=''972970''>to</span>
  <span m=''973040''>go</span> <span m=''973170''>to</span> <span m=''973310''>the</span>
  <span m=''973390''>contents</span> <span m=''973780''>of</span> <span m=''973850''>B.</span>
  <span m=''975240''>Well</span> <span m=''975410''>I</span> <span m=''975500''>don''t</span>
  <span m=''975680''>want</span> <span m=''975840''>to</span> <span m=''975880''>do</span>
  <span m=''975960''>that,</span> <span m=''976130''>because it''s</span> <span m=''976310''>actually</span>
  <span m=''976530''>harder</span> <span m=''976770''>to</span> <span m=''976840''>read</span>
  <span m=''977430''>to</span> <span m=''977530''>do</span> <span m=''977660''>that,</span>
  <span m=''978060''>and</span> <span m=''978310''>it</span> <span m=''978410''>takes</span>
  <span m=''978600''>up</span> <span m=''978680''>more</span> <span m=''978880''>space.</span>
  <span m=''979510''>So</span> <span m=''979640''>I''m</span> <span m=''979740''>going</span>
  <span m=''979830''>to</span> <span m=''979880''>have</span> <span m=''980160''>that</span>
  <span m=''980360''>in</span> <span m=''980580''>the</span> <span m=''980860''>instructions</span>
  <span m=''981450''>written</span> <span m=''981650''>in</span> <span m=''981710''>the</span>
  <span m=''981800''>controller.</span> </p><p><span m=''983290''>It''s</span> <span
  m=''983470''>going to</span> <span m=''983580''>be</span> <span m=''983700''>implicit</span>
  <span m=''984100''>what</span> <span m=''984290''>the</span> <span m=''984390''>operations</span>
  <span m=''985010''>are.</span> <span m=''986460''>They</span> <span m=''986590''>can</span>
  <span m=''986740''>be</span> <span m=''986860''>deduced</span> <span m=''987710''>by</span>
  <span m=''987850''>reading</span> <span m=''988260''>these</span> <span m=''989200''>and</span>
  <span m=''989290''>collecting</span> <span m=''989630''>together</span> <span m=''989990''>all</span>
  <span m=''990160''>the</span> <span m=''990230''>different</span> <span m=''990490''>things</span>
  <span m=''990680''>that</span> <span m=''990740''>can</span> <span m=''990870''>be</span>
  <span m=''990980''>done.</span> <span m=''993500''>Well, let''s just</span> <span
  m=''993960''>look at what</span> <span m=''994070''>these</span> <span m=''994220''>things</span>
  <span m=''994430''>are.</span> <span m=''995482''>There''s</span> <span m=''995860''>a</span>
  <span m=''995930''>little</span> <span m=''996200''>loop</span> <span m=''996350''>that</span>
  <span m=''996500''>we</span> <span m=''996600''>go</span> <span m=''996770''>around</span>
  <span m=''998260''>which</span> <span m=''998460''>says</span> <span m=''999510''>branch,</span>
  <span m=''1002550''>this</span> <span m=''1002840''>is</span> <span m=''1002980''>the</span>
  <span m=''1003550''>representation</span> <span m=''1004610''>of</span> <span m=''1005090''>the</span>
  <span m=''1005750''>little</span> <span m=''1006010''>flap</span> <span m=''1006970''>that</span>
  <span m=''1007080''>decides</span> <span m=''1007430''>which</span> <span m=''1007590''>way</span>
  <span m=''1007720''>you</span> <span m=''1007890''>go</span> <span m=''1008110''>here,</span>
  <span m=''1009080''>if</span> <span m=''1009410''>0</span> <span m=''1014180''>fetch</span>
  <span m=''1014610''>of</span> <span m=''1014850''>B,</span> <span m=''1016700''>the</span>
  <span m=''1016850''>contents</span> <span m=''1017360''>of</span> <span m=''1017440''>B,</span>
  <span m=''1018010''>and</span> <span m=''1018425''>if the</span> <span m=''1018840''>contents
  of B</span> <span m=''1019340''>is</span> <span m=''1019570''>0,</span> <span m=''1020330''>then</span>
  <span m=''1020520''>go</span> <span m=''1020640''>to</span> <span m=''1020690''>a</span>
  <span m=''1020790''>place</span> <span m=''1021040''>called</span> <span m=''1021280''>done.</span>
  </p><p><span m=''1023640''>Now,</span> <span m=''1024329''>one</span> <span m=''1024560''>thing</span>
  <span m=''1024680''>you''re</span> <span m=''1024829''>seeing</span> <span m=''1025109''>here,</span>
  <span m=''1025319''>this</span> <span m=''1025420''>looks</span> <span m=''1025599''>very</span>
  <span m=''1025810''>much</span> <span m=''1026030''>like a</span> <span m=''1026319''>traditional</span>
  <span m=''1026560''>computer</span> <span m=''1026869''>language.</span> <span m=''1028170''>And</span>
  <span m=''1028310''>what</span> <span m=''1028460''>you''re</span> <span m=''1028630''>seeing</span>
  <span m=''1029040''>here</span> <span m=''1030040''>is</span> <span m=''1030470''>things</span>
  <span m=''1030810''>like</span> <span m=''1031420''>labels</span> <span m=''1033010''>that</span>
  <span m=''1033099''>represent</span> <span m=''1033730''>places</span> <span m=''1034710''>in</span>
  <span m=''1034920''>a</span> <span m=''1035050''>sequence</span> <span m=''1035589''>written</span>
  <span m=''1035839''>down</span> <span m=''1036140''>as</span> <span m=''1036270''>a</span>
  <span m=''1036329''>sequence.</span> <span m=''1037609''>The</span> <span m=''1037730''>reason</span>
  <span m=''1038040''>why</span> <span m=''1038250''>they''re</span> <span m=''1038450''>needed</span>
  <span m=''1039530''>is</span> <span m=''1039720''>because</span> <span m=''1040490''>over</span>
  <span m=''1040760''>here,</span> <span m=''1041450''>I''ve</span> <span m=''1041700''>written</span>
  <span m=''1041869''>something</span> <span m=''1042180''>with</span> <span m=''1042310''>loops.</span>
  </p><p><span m=''1043329''>But</span> <span m=''1043490''>if</span> <span m=''1043569''>I''m</span>
  <span m=''1043690''>writing</span> <span m=''1044030''>English</span> <span m=''1044460''>text,</span>
  <span m=''1045099''>or</span> <span m=''1045260''>something</span> <span m=''1045579''>like</span>
  <span m=''1045800''>that,</span> <span m=''1046569''>it''s</span> <span m=''1046720''>hard</span>
  <span m=''1046990''>to</span> <span m=''1047069''>refer</span> <span m=''1047410''>to</span>
  <span m=''1047480''>a</span> <span m=''1047589''>place.</span> <span m=''1048580''>I</span>
  <span m=''1048680''>don''t</span> <span m=''1048790''>have</span> <span m=''1048910''>arrows.</span>
  <span m=''1051440''>Arrows</span> <span m=''1051820''>are</span> <span m=''1051880''>represented</span>
  <span m=''1052410''>by</span> <span m=''1052530''>giving</span> <span m=''1052750''>names</span>
  <span m=''1053070''>to the</span> <span m=''1053180''>places</span> <span m=''1053450''>where</span>
  <span m=''1053590''>the</span> <span m=''1053710''>arrows</span> <span m=''1053970''>terminate,</span>
  <span m=''1054305''>and</span> <span m=''1054640''>then</span> <span m=''1054890''>referring</span>
  <span m=''1055330''>to them</span> <span m=''1055500''>by</span> <span m=''1055680''>those</span>
  <span m=''1055900''>names.</span> <span m=''1057620''>Now this is</span> <span m=''1057740''>just</span>
  <span m=''1057920''>an</span> <span m=''1057990''>encoding.</span> <span m=''1059860''>There''s</span>
  <span m=''1060000''>nothing</span> <span m=''1060350''>magical</span> <span m=''1060810''>about</span>
  <span m=''1061080''>things</span> <span m=''1061310''>like</span> <span m=''1061520''>that.</span>
  </p><p><span m=''1063150''>Next</span> <span m=''1063370''>thing</span> <span m=''1063490''>we''re</span>
  <span m=''1063590''>going</span> <span m=''1063680''>to</span> <span m=''1063720''>do</span>
  <span m=''1064090''>is</span> <span m=''1064360''>we''re</span> <span m=''1064420''>going</span>
  <span m=''1064510''>to</span> <span m=''1064550''>say,</span> <span m=''1065000''>how</span>
  <span m=''1065190''>do</span> <span m=''1065310''>we</span> <span m=''1065770''>do</span>
  <span m=''1066050''>T</span> <span m=''1066260''>gets</span> <span m=''1066530''>R?</span>
  <span m=''1066840''>Oh,</span> <span m=''1067270''>that''s</span> <span m=''1067700''>easy</span>
  <span m=''1068000''>enough,</span> <span m=''1068720''>assign.</span> <span m=''1071930''>We</span>
  <span m=''1072440''>assign</span> <span m=''1073110''>to</span> <span m=''1073290''>T</span>
  <span m=''1074670''>the</span> <span m=''1074780''>remainder.</span> <span m=''1076400''>Assign</span>
  <span m=''1077410''>is</span> <span m=''1077600''>the</span> <span m=''1077700''>name</span>
  <span m=''1078320''>of</span> <span m=''1078720''>the</span> <span m=''1078820''>button.</span>
  <span m=''1081470''>That''s</span> <span m=''1081810''>the</span> <span m=''1081910''>button-pusher.</span>
  <span m=''1083140''>Assign</span> <span m=''1083600''>to</span> <span m=''1083680''>T</span>
  <span m=''1084150''>the</span> <span m=''1084290''>remainder,</span> <span m=''1084970''>and</span>
  <span m=''1085050''>here''s</span> <span m=''1085280''>the</span> <span m=''1085350''>representation</span>
  <span m=''1085630''>of</span> <span m=''1085910''>the</span> <span m=''1086040''>operation,</span>
  <span m=''1091850''>when</span> <span m=''1092030''>we</span> <span m=''1092150''>divide</span>
  <span m=''1092660''>the</span> <span m=''1092750''>fetch</span> <span m=''1092970''>of</span>
  <span m=''1093460''>A</span> <span m=''1096380''>by</span> <span m=''1096740''>the</span>
  <span m=''1097040''>fetch</span> <span m=''1097300''>of</span> <span m=''1097550''>B.</span>
  </p><p><span m=''1103478''>And</span> <span m=''1103980''>we''re</span> <span m=''1104210''>also</span>
  <span m=''1104460''>going</span> <span m=''1104700''>to</span> <span m=''1105160''>assign</span>
  <span m=''1108512''>to</span> <span m=''1108970''>A</span> <span m=''1109740''>the</span>
  <span m=''1110150''>fetch</span> <span m=''1110350''>of</span> <span m=''1110460''>B,</span>
  <span m=''1115070''>assign</span> <span m=''1115490''>to</span> <span m=''1115560''>B</span>
  <span m=''1121360''>the</span> <span m=''1121480''>result</span> <span m=''1121880''>of</span>
  <span m=''1122390''>getting</span> <span m=''1122610''>the</span> <span m=''1122710''>contents</span>
  <span m=''1123150''>of</span> <span m=''1123800''>T.</span> <span m=''1129316''>And</span>
  <span m=''1129800''>now</span> <span m=''1129950''>I</span> <span m=''1130040''>have</span>
  <span m=''1130140''>to</span> <span m=''1130230''>refer</span> <span m=''1130690''>to</span>
  <span m=''1130830''>the</span> <span m=''1130950''>beginning</span> <span m=''1131410''>here.</span>
  <span m=''1133280''>I</span> <span m=''1133440''>see,</span> <span m=''1133610''>why
  don''t</span> <span m=''1133820''>I</span> <span m=''1133890''>call</span> <span
  m=''1134130''>that</span> <span m=''1134320''>loop</span> <span m=''1135030''>like</span>
  <span m=''1135230''>I</span> <span m=''1135360''>have</span> <span m=''1135480''>here?</span>
  <span m=''1145390''>So</span> <span m=''1145620''>that''s that</span> <span m=''1145800''>reference</span>
  <span m=''1146240''>to that</span> <span m=''1146430''>arrow.</span> <span m=''1147610''>And</span>
  <span m=''1147860''>when we''re</span> <span m=''1148140''>done,</span> <span m=''1148420''>we''re</span>
  <span m=''1148590''>done.</span> <span m=''1148950''>We go to</span> <span m=''1149230''>here,</span>
  <span m=''1151690''>which</span> <span m=''1152080''>is</span> <span m=''1152180''>the</span>
  <span m=''1152330''>end</span> <span m=''1152480''>of</span> <span m=''1152610''>the</span>
  <span m=''1152730''>thing.</span> </p><p><span m=''1154340''>So</span> <span m=''1154815''>here''s</span>
  <span m=''1155290''>just a</span> <span m=''1155570''>written</span> <span m=''1155990''>representation</span>
  <span m=''1157740''>of</span> <span m=''1157900''>this</span> <span m=''1158090''>fragment</span>
  <span m=''1158550''>of</span> <span m=''1158610''>machinery</span> <span m=''1160010''>that</span>
  <span m=''1160100''>we''ve</span> <span m=''1160260''>drawn</span> <span m=''1160540''>here.</span>
  <span m=''1161660''>Now</span> <span m=''1161810''>the</span> <span m=''1161970''>next</span>
  <span m=''1162130''>thing</span> <span m=''1162280''>I''d</span> <span m=''1162440''>like</span>
  <span m=''1162630''>to</span> <span m=''1162730''>do</span> <span m=''1164040''>is</span>
  <span m=''1164190''>run</span> <span m=''1164510''>this.</span> <span m=''1165490''>I</span>
  <span m=''1165570''>want us</span> <span m=''1165810''>to</span> <span m=''1165900''>feel</span>
  <span m=''1166190''>it</span> <span m=''1166270''>running.</span> <span m=''1167620''>Never</span>
  <span m=''1167960''>done</span> <span m=''1168190''>this</span> <span m=''1168370''>before,</span>
  <span m=''1168770''>you</span> <span m=''1168870''>got</span> <span m=''1169020''>to</span>
  <span m=''1169080''>do it</span> <span m=''1169260''>once.</span> </p><p><span m=''1171010''>So</span>
  <span m=''1171180''>let''s</span> <span m=''1171510''>take</span> <span m=''1171640''>a</span>
  <span m=''1171710''>particular</span> <span m=''1172120''>problem.</span> <span
  m=''1173100''>Suppose</span> <span m=''1173270''>we</span> <span m=''1173420''>want</span>
  <span m=''1173650''>to compute</span> <span m=''1173790''>the</span> <span m=''1173930''>GCD</span>
  <span m=''1175100''>of</span> <span m=''1175490''>a</span> <span m=''1175710''>equals</span>
  <span m=''1175950''>30</span> <span m=''1178580''>and</span> <span m=''1179340''>b</span>
  <span m=''1179580''>equals</span> <span m=''1179880''>42.</span> <span m=''1182210''>I</span>
  <span m=''1182360''>have</span> <span m=''1182470''>no</span> <span m=''1182710''>idea</span>
  <span m=''1183710''>what</span> <span m=''1183910''>that</span> <span m=''1184150''>is</span>
  <span m=''1184290''>right</span> <span m=''1184540''>now.</span> <span m=''1185860''>But</span>
  <span m=''1186230''>a</span> <span m=''1186390''>30</span> <span m=''1186680''>and</span>
  <span m=''1186770''>b</span> <span m=''1186880''>is</span> <span m=''1187010''>42.</span>
  <span m=''1190530''>So</span> <span m=''1191000''>that''s how</span> <span m=''1191190''>I</span>
  <span m=''1191290''>start</span> <span m=''1191610''>this</span> <span m=''1191740''>thing</span>
  <span m=''1191940''>up.</span> </p><p><span m=''1192410''>Well,</span> <span m=''1192700''>what''s</span>
  <span m=''1192880''>the</span> <span m=''1193050''>first</span> <span m=''1193270''>thing</span>
  <span m=''1193410''>I</span> <span m=''1193510''>do?</span> <span m=''1194240''>I</span>
  <span m=''1194390''>say</span> <span m=''1194730''>is</span> <span m=''1195140''>B</span>
  <span m=''1195310''>equal</span> <span m=''1195560''>to</span> <span m=''1195610''>0,</span>
  <span m=''1196400''>no.</span> <span m=''1197590''>Then</span> <span m=''1198300''>assign</span>
  <span m=''1198640''>to</span> <span m=''1198910''>T</span> <span m=''1199080''>the</span>
  <span m=''1199160''>remainder</span> <span m=''1200560''>of</span> <span m=''1200760''>the</span>
  <span m=''1200820''>fetch of A</span> <span m=''1201170''>and</span> <span m=''1201390''>the
  fetch of</span> <span m=''1201720''>B.</span> <span m=''1202720''>Well</span> <span
  m=''1202950''>the</span> <span m=''1203010''>remainder</span> <span m=''1203610''>of</span>
  <span m=''1204110''>30</span> <span m=''1204780''>when</span> <span m=''1205090''>divided</span>
  <span m=''1205490''>by</span> <span m=''1205640''>42</span> <span m=''1206260''>is</span>
  <span m=''1206360''>itself</span> <span m=''1206970''>30.</span> <span m=''1211130''>Push</span>
  <span m=''1211330''>that</span> <span m=''1211620''>button.</span> </p><p><span
  m=''1212920''>Now</span> <span m=''1213810''>the</span> <span m=''1213930''>marble</span>
  <span m=''1214310''>has</span> <span m=''1214380''>rolled to</span> <span m=''1214720''>here.</span>
  <span m=''1217100''>A</span> <span m=''1217300''>gets</span> <span m=''1217610''>B.</span>
  <span m=''1219050''>That</span> <span m=''1219300''>pushes</span> <span m=''1220250''>this</span>
  <span m=''1220410''>button.</span> <span m=''1221220''>So</span> <span m=''1221310''>42</span>
  <span m=''1221750''>moves</span> <span m=''1221990''>into</span> <span m=''1222170''>here.</span>
  </p><p><span m=''1226360''>B</span> <span m=''1226850''>gets</span> <span m=''1227130''>C.</span>
  <span m=''1228180''>Push</span> <span m=''1228650''>that</span> <span m=''1228900''>button.</span>
  <span m=''1229870''>The</span> <span m=''1229980''>30</span> <span m=''1230280''>goes</span>
  <span m=''1230590''>here.</span> <span m=''1232225''>Let</span> <span m=''1232660''>met</span>
  <span m=''1232740''>just</span> <span m=''1232940''>interchange</span> <span m=''1233440''>them.</span>
  </p><p><span m=''1234660''>Now</span> <span m=''1234840''>let''s</span> <span m=''1235080''>see,</span>
  <span m=''1237000''>go</span> <span m=''1237130''>back</span> <span m=''1237430''>to</span>
  <span m=''1237500''>the</span> <span m=''1237710''>beginning.</span> <span m=''1238280''>B</span>
  <span m=''1238650''>0,</span> <span m=''1239230''>no.</span> <span m=''1240200''>T</span>
  <span m=''1240390''>gets</span> <span m=''1240800''>the</span> <span m=''1240890''>remainder.</span>
  <span m=''1243230''>I</span> <span m=''1243360''>suppose</span> <span m=''1243670''>the</span>
  <span m=''1243700''>remainder</span> <span m=''1244080''>when</span> <span m=''1244300''>dividing</span>
  <span m=''1244720''>42</span> <span m=''1245230''>by</span> <span m=''1245350''>30</span>
  <span m=''1245610''>is</span> <span m=''1245700''>12.</span> <span m=''1247240''>I</span>
  <span m=''1247340''>push</span> <span m=''1247630''>that</span> <span m=''1247870''>one.</span>
  </p><p><span m=''1248530''>Next</span> <span m=''1248830''>thing</span> <span m=''1249020''>I</span>
  <span m=''1249120''>do</span> <span m=''1249930''>is</span> <span m=''1250100''>allow</span>
  <span m=''1250300''>the</span> <span m=''1250380''>30</span> <span m=''1250630''>to</span>
  <span m=''1250700''>go</span> <span m=''1250870''>to</span> <span m=''1250950''>here,</span>
  <span m=''1253860''>push</span> <span m=''1254150''>this</span> <span m=''1254360''>one,</span>
  <span m=''1254590''>allow</span> <span m=''1254820''>the</span> <span m=''1254920''>12</span>
  <span m=''1255220''>to</span> <span m=''1255290''>go</span> <span m=''1255470''>to</span>
  <span m=''1255530''>here.</span> <span m=''1259550''>Go</span> <span m=''1259710''>around</span>
  <span m=''1260040''>this</span> <span m=''1260170''>thing.</span> <span m=''1260380''>Is</span>
  <span m=''1260510''>that</span> <span m=''1260800''>done?</span> <span m=''1261530''>No.</span>
  <span m=''1262360''>How</span> <span m=''1262550''>about--</span> <span m=''1265080''>so
  now</span> <span m=''1265310''>I have</span> <span m=''1265470''>to</span> <span
  m=''1265530''>find</span> <span m=''1265830''>out</span> <span m=''1265970''>the</span>
  <span m=''1266040''>remainder</span> <span m=''1266620''>of</span> <span m=''1266870''>30</span>
  <span m=''1267090''>divided</span> <span m=''1267440''>by</span> <span m=''1267580''>12.</span>
  <span m=''1268850''>And</span> <span m=''1269470''>I</span> <span m=''1269610''>believe</span>
  <span m=''1269870''>that''s</span> <span m=''1270100''>6.</span> <span m=''1272420''>So</span>
  <span m=''1272630''>6</span> <span m=''1272950''>goes</span> <span m=''1273220''>here</span>
  <span m=''1274120''>on</span> <span m=''1274330''>this</span> <span m=''1274510''>button</span>
  <span m=''1274770''>push.</span> <span m=''1275916''>Then</span> <span m=''1276280''>the</span>
  <span m=''1276550''>next</span> <span m=''1276820''>thing</span> <span m=''1276990''>I</span>
  <span m=''1277070''>push</span> <span m=''1277400''>is</span> <span m=''1277590''>this</span>
  <span m=''1277800''>one,</span> <span m=''1278280''>which</span> <span m=''1278490''>the</span>
  <span m=''1278550''>12</span> <span m=''1278830''>goes</span> <span m=''1279030''>into</span>
  <span m=''1279190''>here.</span> </p><p><span m=''1283730''>Then</span> <span m=''1283950''>I</span>
  <span m=''1284040''>push</span> <span m=''1284510''>this</span> <span m=''1284770''>button.</span>
  <span m=''1285090''>The 6</span> <span m=''1285350''>gets into</span> <span m=''1285650''>here.</span>
  <span m=''1289850''>Is</span> <span m=''1290450''>6</span> <span m=''1290930''>equal</span>
  <span m=''1291190''>to</span> <span m=''1291675''>0?</span> <span m=''1292100''>No.</span>
  <span m=''1293420''>OK.</span> </p><p><span m=''1294380''>So</span> <span m=''1294640''>then</span>
  <span m=''1296020''>at</span> <span m=''1296150''>that</span> <span m=''1296370''>point,</span>
  <span m=''1296890''>the</span> <span m=''1296970''>next</span> <span m=''1297160''>thing</span>
  <span m=''1297290''>to</span> <span m=''1297370''>do</span> <span m=''1297590''>is</span>
  <span m=''1297750''>divide</span> <span m=''1298120''>it.</span> <span m=''1298380''>Ooh,
  this has</span> <span m=''1298590''>got</span> <span m=''1298760''>a</span> <span
  m=''1298780''>remainder</span> <span m=''1299180''>of</span> <span m=''1299230''>0.</span>
  <span m=''1300660''>Looks</span> <span m=''1300770''>like</span> <span m=''1300920''>we''re</span>
  <span m=''1301040''>almost</span> <span m=''1301360''>done.</span> </p><p><span
  m=''1302360''>Move</span> <span m=''1302700''>the</span> <span m=''1302750''>6</span>
  <span m=''1303040''>over</span> <span m=''1303280''>here</span> <span m=''1303970''>next.</span>
  <span m=''1307230''>0</span> <span m=''1307420''>over</span> <span m=''1307760''>here.</span>
  <span m=''1309090''>Is</span> <span m=''1309220''>the</span> <span m=''1309340''>answer</span>
  <span m=''1309770''>0?</span> <span m=''1310200''>Yes.</span> <span m=''1311340''>B</span>
  <span m=''1311510''>is</span> <span m=''1311640''>0,</span> <span m=''1311940''>therefore</span>
  <span m=''1312270''>the</span> <span m=''1312420''>answer</span> <span m=''1312710''>is
  in</span> <span m=''1312910''>A.</span> </p><p><span m=''1314470''>The</span> <span
  m=''1314840''>answer</span> <span m=''1315190''>is</span> <span m=''1315270''>6.</span>
  <span m=''1316610''>And</span> <span m=''1316770''>indeed</span> <span m=''1317000''>that''s</span>
  <span m=''1317270''>right,</span> <span m=''1317600''>because</span> <span m=''1317890''>if
  we</span> <span m=''1318060''>look</span> <span m=''1318230''>at</span> <span m=''1318310''>the</span>
  <span m=''1318400''>original</span> <span m=''1318820''>problem,</span> <span m=''1320160''>what</span>
  <span m=''1320320''>we</span> <span m=''1320590''>have</span> <span m=''1321130''>is</span>
  <span m=''1321990''>30</span> <span m=''1323030''>is</span> <span m=''1324440''>2</span>
  <span m=''1324730''>times</span> <span m=''1325220''>3</span> <span m=''1325640''>times</span>
  <span m=''1326130''>5,</span> <span m=''1327060''>and</span> <span m=''1327300''>42</span>
  <span m=''1328740''>is</span> <span m=''1329000''>2</span> <span m=''1329250''>times</span>
  <span m=''1329710''>3</span> <span m=''1330070''>times</span> <span m=''1330440''>7.</span>
  <span m=''1331670''>So</span> <span m=''1331880''>the</span> <span m=''1332010''>greatest</span>
  <span m=''1332320''>common</span> <span m=''1332580''>divisor</span> <span m=''1333100''>is</span>
  <span m=''1333180''>2</span> <span m=''1333320''>times</span> <span m=''1333650''>3,</span>
  <span m=''1334270''>which</span> <span m=''1334510''>is</span> <span m=''1334640''>6.</span>
  </p><p><span m=''1338380''>Now</span> <span m=''1338500''>normally,</span> <span
  m=''1338980''>we</span> <span m=''1339090''>write</span> <span m=''1339310''>one</span>
  <span m=''1339510''>other</span> <span m=''1339810''>little</span> <span m=''1340040''>line</span>
  <span m=''1340310''>here,</span> <span m=''1340550''>just</span> <span m=''1340780''>to</span>
  <span m=''1341400''>make</span> <span m=''1341620''>it</span> <span m=''1341680''>a</span>
  <span m=''1341710''>little</span> <span m=''1341910''>bit</span> <span m=''1342080''>clearer,</span>
  <span m=''1342930''>which</span> <span m=''1343160''>is</span> <span m=''1343290''>that</span>
  <span m=''1343420''>we</span> <span m=''1343770''>leave</span> <span m=''1344170''>in</span>
  <span m=''1345620''>a</span> <span m=''1346740''>connection</span> <span m=''1347250''>saying</span>
  <span m=''1347970''>that</span> <span m=''1348210''>this</span> <span m=''1348410''>light</span>
  <span m=''1348675''>is</span> <span m=''1348940''>the</span> <span m=''1349010''>guy</span>
  <span m=''1349760''>that</span> <span m=''1349900''>that</span> <span m=''1350150''>flap</span>
  <span m=''1350490''>looks</span> <span m=''1350710''>at.</span> <span m=''1354050''>Of</span>
  <span m=''1354240''>course,</span> <span m=''1355710''>any</span> <span m=''1355970''>real</span>
  <span m=''1356180''>machine</span> <span m=''1356480''>has</span> <span m=''1356630''>a</span>
  <span m=''1356670''>lot</span> <span m=''1356920''>more</span> <span m=''1357870''>complicated</span>
  <span m=''1358440''>things</span> <span m=''1358700''>in</span> <span m=''1358780''>it</span>
  <span m=''1358900''>than</span> <span m=''1359010''>what</span> <span m=''1359160''>I''ve</span>
  <span m=''1359210''>just</span> <span m=''1359420''>shown</span> <span m=''1359680''>you.</span>
  <span m=''1361350''>Let''s</span> <span m=''1361610''>look</span> <span m=''1361800''>for</span>
  <span m=''1361930''>a</span> <span m=''1362000''>second</span> <span m=''1362360''>at</span>
  <span m=''1364261''>the</span> <span m=''1364680''>first</span> <span m=''1366350''>still</span>
  <span m=''1366670''>store.</span> </p><p><span m=''1367980''>Wow.</span> <span m=''1370190''>Well</span>
  <span m=''1370370''>you</span> <span m=''1370480''>see,</span> <span m=''1370650''>for</span>
  <span m=''1370790''>example,</span> <span m=''1371120''>one</span> <span m=''1371310''>thing</span>
  <span m=''1371480''>we</span> <span m=''1371580''>might</span> <span m=''1371790''>want</span>
  <span m=''1371980''>to</span> <span m=''1372040''>do</span> <span m=''1372700''>is</span>
  <span m=''1372850''>worry</span> <span m=''1373070''>about</span> <span m=''1373750''>the</span>
  <span m=''1373970''>operations</span> <span m=''1374225''>that</span> <span m=''1374480''>are</span>
  <span m=''1374610''>of</span> <span m=''1375030''>IO</span> <span m=''1375450''>form.</span>
  <span m=''1376840''>And</span> <span m=''1376950''>we</span> <span m=''1377060''>may</span>
  <span m=''1377250''>have</span> <span m=''1377510''>to</span> <span m=''1378510''>collect</span>
  <span m=''1380270''>something</span> <span m=''1380520''>from</span> <span m=''1380630''>the</span>
  <span m=''1380730''>outside.</span> <span m=''1381980''>So</span> <span m=''1382430''>a</span>
  <span m=''1382500''>state</span> <span m=''1382790''>machine</span> <span m=''1383060''>that</span>
  <span m=''1383180''>we</span> <span m=''1383280''>might</span> <span m=''1383500''>have,</span>
  <span m=''1384320''>the</span> <span m=''1384850''>controller</span> <span m=''1386040''>may</span>
  <span m=''1386310''>have</span> <span m=''1386570''>to,</span> <span m=''1387840''>for</span>
  <span m=''1388030''>example,</span> <span m=''1388510''>get</span> <span m=''1389070''>a</span>
  <span m=''1389390''>value</span> <span m=''1389810''>from</span> <span m=''1390040''>something</span>
  <span m=''1390900''>and</span> <span m=''1391050''>put</span> <span m=''1391190''>register</span>
  <span m=''1391380''>a</span> <span m=''1391830''>to load it</span> <span m=''1392220''>up.</span>
  <span m=''1393490''>I</span> <span m=''1393580''>have</span> <span m=''1393720''>to</span>
  <span m=''1393820''>master</span> <span m=''1394050''>load up</span> <span m=''1394130''>register</span>
  <span m=''1394780''>b</span> <span m=''1394940''>with</span> <span m=''1395080''>another</span>
  <span m=''1395380''>value.</span> </p><p><span m=''1397070''>And</span> <span m=''1397250''>then</span>
  <span m=''1397420''>later,</span> <span m=''1397820''>when</span> <span m=''1397990''>I''m</span>
  <span m=''1398130''>done,</span> <span m=''1399010''>I</span> <span m=''1399140''>might</span>
  <span m=''1399330''>want</span> <span m=''1399470''>to</span> <span m=''1399510''>print</span>
  <span m=''1399760''>the</span> <span m=''1399900''>answer</span> <span m=''1400240''>out.</span>
  <span m=''1400970''>And</span> <span m=''1401400''>of</span> <span m=''1401530''>course,</span>
  <span m=''1401760''>that</span> <span m=''1401980''>might</span> <span m=''1402220''>be</span>
  <span m=''1403920''>either</span> <span m=''1404170''>simple</span> <span m=''1404430''>or</span>
  <span m=''1404530''>complicated.</span> <span m=''1406250''>I''m</span> <span m=''1406410''>writing,</span>
  <span m=''1406700''>assuming</span> <span m=''1407070''>print</span> <span m=''1407280''>is</span>
  <span m=''1407370''>very</span> <span m=''1407590''>simple,</span> <span m=''1408030''>and</span>
  <span m=''1408320''>read</span> <span m=''1408560''>is</span> <span m=''1408660''>very</span>
  <span m=''1408880''>simple.</span> <span m=''1409880''>But</span> <span m=''1410020''>in</span>
  <span m=''1410120''>fact,</span> <span m=''1410440''>in</span> <span m=''1410520''>the</span>
  <span m=''1410600''>real</span> <span m=''1410870''>world,</span> <span m=''1411140''>those</span>
  <span m=''1411350''>are</span> <span m=''1411410''>very</span> <span m=''1411700''>complicated</span>
  <span m=''1412260''>operations,</span> <span m=''1413650''>usually</span> <span
  m=''1414020''>much,</span> <span m=''1414350''>much</span> <span m=''1414550''>larger</span>
  <span m=''1414860''>and</span> <span m=''1414930''>more</span> <span m=''1415080''>complicated</span>
  <span m=''1415590''>than</span> <span m=''1415700''>the</span> <span m=''1415790''>thing</span>
  <span m=''1415970''>you''re</span> <span m=''1416090''>doing</span> <span m=''1416770''>as</span>
  <span m=''1416940''>your</span> <span m=''1417080''>problem</span> <span m=''1417500''>you''re</span>
  <span m=''1417600''>trying</span> <span m=''1417720''>to</span> <span m=''1417850''>solve.</span>
  </p><p><span m=''1421670''>On</span> <span m=''1421820''>the</span> <span m=''1421940''>other</span>
  <span m=''1422070''>hand,</span> <span m=''1422290''>I</span> <span m=''1422350''>can</span>
  <span m=''1422490''>remember</span> <span m=''1422790''>a</span> <span m=''1422840''>time</span>
  <span m=''1423190''>when,</span> <span m=''1424920''>I</span> <span m=''1425060''>remember</span>
  <span m=''1425200''>using</span> <span m=''1425630''>IBM</span> <span m=''1427350''>7090</span>
  <span m=''1427960''>computer</span> <span m=''1428230''>of</span> <span m=''1428500''>sorts,</span>
  <span m=''1429080''>where</span> <span m=''1429320''>things</span> <span m=''1429570''>like</span>
  <span m=''1429770''>read</span> <span m=''1429980''>and</span> <span m=''1430030''>write</span>
  <span m=''1430910''>of</span> <span m=''1431060''>a</span> <span m=''1431190''>single</span>
  <span m=''1432610''>object,</span> <span m=''1432875''>a</span> <span m=''1433140''>single</span>
  <span m=''1433600''>number,</span> <span m=''1434090''>a</span> <span m=''1434170''>number,</span>
  <span m=''1435940''>is</span> <span m=''1436100''>a</span> <span m=''1436150''>primitive</span>
  <span m=''1436490''>operation</span> <span m=''1436980''>of</span> <span m=''1437080''>the</span>
  <span m=''1437810''>IO</span> <span m=''1438040''>controller.</span> <span m=''1439065''>OK?</span>
  </p><p><span m=''1440400''>And</span> <span m=''1440550''>so</span> <span m=''1440660''>we</span>
  <span m=''1440750''>have</span> <span m=''1440920''>that</span> <span m=''1441130''>kind</span>
  <span m=''1441290''>of</span> <span m=''1441450''>thing in</span> <span m=''1441720''>there.</span>
  <span m=''1442330''>And in</span> <span m=''1443520''>such</span> <span m=''1443830''>a</span>
  <span m=''1443970''>machine,</span> <span m=''1445450''>well,</span> <span m=''1445820''>what</span>
  <span m=''1445950''>are</span> <span m=''1445990''>we</span> <span m=''1446140''>really</span>
  <span m=''1446410''>doing?</span> <span m=''1448360''>We''re</span> <span m=''1448440''>just</span>
  <span m=''1448610''>saying</span> <span m=''1448840''>that</span> <span m=''1448950''>there''s</span>
  <span m=''1449150''>a</span> <span m=''1449210''>source</span> <span m=''1450470''>over</span>
  <span m=''1450580''>here</span> <span m=''1450845''>called</span> <span m=''1451110''>"read,"</span>
  <span m=''1452240''>which</span> <span m=''1452450''>is</span> <span m=''1452530''>an</span>
  <span m=''1452610''>operation</span> <span m=''1453180''>which</span> <span m=''1453360''>always</span>
  <span m=''1453640''>has</span> <span m=''1453820''>a</span> <span m=''1453880''>value.</span>
  <span m=''1454660''>We</span> <span m=''1454760''>have</span> <span m=''1454860''>to</span>
  <span m=''1454930''>think</span> <span m=''1455140''>about</span> <span m=''1455450''>this</span>
  <span m=''1455930''>as</span> <span m=''1456110''>always</span> <span m=''1456390''>having</span>
  <span m=''1456630''>a</span> <span m=''1456680''>value</span> <span m=''1457250''>which</span>
  <span m=''1457480''>can</span> <span m=''1457640''>be</span> <span m=''1457760''>gated</span>
  <span m=''1458160''>into</span> <span m=''1458380''>either</span> <span m=''1458590''>register</span>
  <span m=''1459030''>a</span> <span m=''1459160''>or</span> <span m=''1459310''>b.</span>
  <span m=''1461660''>And</span> <span m=''1461950''>print</span> <span m=''1462240''>is</span>
  <span m=''1462360''>some</span> <span m=''1462590''>sort</span> <span m=''1462800''>of</span>
  <span m=''1462910''>thing</span> <span m=''1463410''>which</span> <span m=''1463590''>when</span>
  <span m=''1463780''>you</span> <span m=''1463930''>gate</span> <span m=''1464190''>it</span>
  <span m=''1464290''>appropriately,</span> <span m=''1465310''>when</span> <span
  m=''1465450''>you</span> <span m=''1465570''>push</span> <span m=''1465770''>the</span>
  <span m=''1465870''>button</span> <span m=''1466150''>on</span> <span m=''1466310''>it,</span>
  <span m=''1466700''>will</span> <span m=''1466900''>cause</span> <span m=''1467320''>a</span>
  <span m=''1467410''>print</span> <span m=''1467700''>of</span> <span m=''1467820''>the</span>
  <span m=''1467910''>value</span> <span m=''1468240''>that''s</span> <span m=''1468420''>currently</span>
  <span m=''1468810''>in</span> <span m=''1468900''>register</span> <span m=''1469155''>a.</span>
  <span m=''1471660''>Nothing</span> <span m=''1471950''>very</span> <span m=''1472170''>exciting.</span>
  </p><p><span m=''1473050''>So</span> <span m=''1473410''>that''s</span> <span m=''1473650''>one</span>
  <span m=''1473900''>sort</span> <span m=''1474090''>of</span> <span m=''1474160''>thing</span>
  <span m=''1474320''>you</span> <span m=''1474420''>might</span> <span m=''1474620''>want</span>
  <span m=''1474790''>to</span> <span m=''1474830''>have.</span> <span m=''1475900''>But</span>
  <span m=''1476110''>these</span> <span m=''1476310''>are</span> <span m=''1476360''>also</span>
  <span m=''1476650''>other</span> <span m=''1476850''>things</span> <span m=''1477110''>that
  are</span> <span m=''1477260''>a</span> <span m=''1477300''>little</span> <span
  m=''1477460''>bit</span> <span m=''1477590''>worrisome.</span> <span m=''1478320''>Like</span>
  <span m=''1478560''>I''ve</span> <span m=''1478720''>used</span> <span m=''1478960''>here</span>
  <span m=''1479160''>some</span> <span m=''1479360''>complicated</span> <span m=''1480000''>mechanisms.</span>
  </p><p><span m=''1481050''>What</span> <span m=''1481220''>you</span> <span m=''1481350''>see</span>
  <span m=''1481510''>here</span> <span m=''1481760''>is</span> <span m=''1481810''>remainder.</span>
  <span m=''1483850''>What</span> <span m=''1483980''>is</span> <span m=''1484190''>that?</span>
  <span m=''1484690''>That</span> <span m=''1484860''>may not</span> <span m=''1485000''>be</span>
  <span m=''1485100''>so</span> <span m=''1485350''>obvious</span> <span m=''1485780''>how</span>
  <span m=''1485880''>to</span> <span m=''1485960''>compute.</span> <span m=''1486920''>It</span>
  <span m=''1487080''>may</span> <span m=''1487310''>be</span> <span m=''1487480''>something</span>
  <span m=''1487840''>which</span> <span m=''1487990''>when</span> <span m=''1488130''>you</span>
  <span m=''1488290''>open</span> <span m=''1488600''>it</span> <span m=''1488700''>up,</span>
  <span m=''1489550''>you</span> <span m=''1489670''>get</span> <span m=''1489820''>a</span>
  <span m=''1489860''>whole</span> <span m=''1490060''>machine.</span> <span m=''1491880''>OK?</span>
  <span m=''1492720''>In</span> <span m=''1492840''>fact,</span> <span m=''1493070''>that''s</span>
  <span m=''1493310''>true.</span> </p><p><span m=''1494540''>For</span> <span m=''1494750''>example,</span>
  <span m=''1497160''>if</span> <span m=''1497470''>I</span> <span m=''1497530''>write</span>
  <span m=''1497780''>down</span> <span m=''1497970''>the</span> <span m=''1498040''>program</span>
  <span m=''1498470''>for</span> <span m=''1498570''>remainder,</span> <span m=''1499470''>the</span>
  <span m=''1499570''>simplest</span> <span m=''1500020''>program</span> <span m=''1500450''>for</span>
  <span m=''1500680''>it</span> <span m=''1500820''>is</span> <span m=''1501150''>by</span>
  <span m=''1501270''>repeated</span> <span m=''1501680''>subtraction.</span> <span
  m=''1504480''>Because</span> <span m=''1504980''>of</span> <span m=''1505070''>course,</span>
  <span m=''1505270''>division</span> <span m=''1505610''>can</span> <span m=''1505700''>be</span>
  <span m=''1505800''>done</span> <span m=''1505950''>by</span> <span m=''1506040''>repeated</span>
  <span m=''1506380''>subtraction</span> <span m=''1507480''>of</span> <span m=''1507900''>numbers,</span>
  <span m=''1508180''>of</span> <span m=''1508460''>integers.</span> <span m=''1509800''>So</span>
  <span m=''1513810''>the</span> <span m=''1513920''>remainder</span> <span m=''1521810''>of</span>
  <span m=''1522060''>N</span> <span m=''1522380''>divided</span> <span m=''1522760''>by</span>
  <span m=''1522950''>D</span> <span m=''1525040''>is</span> <span m=''1525210''>nothing</span>
  <span m=''1525540''>more</span> <span m=''1525930''>than</span> <span m=''1526330''>if</span>
  <span m=''1529900''>N</span> <span m=''1530270''>is</span> <span m=''1530420''>less</span>
  <span m=''1530690''>than</span> <span m=''1530930''>D,</span> <span m=''1532310''>then</span>
  <span m=''1532450''>the</span> <span m=''1532520''>result</span> <span m=''1532980''>is</span>
  <span m=''1533150''>N.</span> <span m=''1534290''>Otherwise,</span> <span m=''1534605''>it''s</span>
  <span m=''1534920''>the</span> <span m=''1535000''>remainder</span> <span m=''1541080''>when</span>
  <span m=''1541380''>we</span> <span m=''1541520''>subtract</span> <span m=''1542870''>D</span>
  <span m=''1543070''>from</span> <span m=''1543270''>N</span> <span m=''1546680''>with</span>
  <span m=''1546770''>respect</span> <span m=''1547140''>to</span> <span m=''1547200''>D,</span>
  <span m=''1548350''>when</span> <span m=''1548490''>divided</span> <span m=''1548830''>by</span>
  <span m=''1548980''>D.</span> <span m=''1550924''>Gee,</span> <span m=''1551330''>this</span>
  <span m=''1551610''>looks</span> <span m=''1551840''>just</span> <span m=''1552160''>like</span>
  <span m=''1553590''>the</span> <span m=''1553760''>GCD</span> <span m=''1554320''>program.</span>
  </p><p><span m=''1556890''>Of</span> <span m=''1556980''>course,</span> <span m=''1557170''>it''s</span>
  <span m=''1557270''>not</span> <span m=''1557430''>a</span> <span m=''1557450''>very</span>
  <span m=''1557650''>nice</span> <span m=''1557920''>way</span> <span m=''1558060''>to</span>
  <span m=''1558680''>do</span> <span m=''1558870''>remainders.</span> <span m=''1559750''>You''d</span>
  <span m=''1559910''>really</span> <span m=''1560150''>want</span> <span m=''1560320''>to</span>
  <span m=''1560360''>use</span> <span m=''1560530''>something</span> <span m=''1560730''>like</span>
  <span m=''1560880''>binary</span> <span m=''1561270''>notation</span> <span m=''1561525''>and</span>
  <span m=''1561780''>shift</span> <span m=''1562110''>and</span> <span m=''1562230''>things</span>
  <span m=''1562460''>like</span> <span m=''1562680''>that</span> <span m=''1563380''>in</span>
  <span m=''1563530''>a</span> <span m=''1564050''>practical</span> <span m=''1564900''>computer.</span>
  <span m=''1565550''>But</span> <span m=''1565870''>the</span> <span m=''1565960''>point</span>
  <span m=''1566310''>of</span> <span m=''1566360''>that</span> <span m=''1566630''>is</span>
  <span m=''1567120''>that</span> <span m=''1567360''>if</span> <span m=''1567500''>I</span>
  <span m=''1567580''>open</span> <span m=''1567910''>this</span> <span m=''1568120''>thing</span>
  <span m=''1568320''>up,</span> <span m=''1568950''>I</span> <span m=''1569060''>might</span>
  <span m=''1569310''>find</span> <span m=''1569510''>inside of it</span> <span m=''1569930''>a</span>
  <span m=''1570070''>computer.</span> </p><p><span m=''1571880''>Oh,</span> <span
  m=''1572070''>we</span> <span m=''1572180''>know</span> <span m=''1572270''>how</span>
  <span m=''1572340''>to</span> <span m=''1572420''>do</span> <span m=''1572590''>that.</span>
  <span m=''1573510''>We</span> <span m=''1573680''>just</span> <span m=''1573860''>made</span>
  <span m=''1574070''>one.</span> <span m=''1575640''>And it</span> <span m=''1575840''>could</span>
  <span m=''1575970''>be</span> <span m=''1576090''>another</span> <span m=''1576420''>thing
  just</span> <span m=''1576650''>like</span> <span m=''1576870''>this.</span> </p><p><span
  m=''1577400''>On</span> <span m=''1577570''>the</span> <span m=''1577690''>other</span>
  <span m=''1577810''>hand,</span> <span m=''1578040''>we</span> <span m=''1578160''>might</span>
  <span m=''1578370''>want</span> <span m=''1578540''>to</span> <span m=''1578580''>make</span>
  <span m=''1578770''>a</span> <span m=''1579180''>more</span> <span m=''1579520''>efficient</span>
  <span m=''1580030''>or</span> <span m=''1580150''>better-structured</span> <span
  m=''1580930''>machine,</span> <span m=''1581490''>or</span> <span m=''1581910''>maybe</span>
  <span m=''1582130''>make</span> <span m=''1582340''>use</span> <span m=''1582540''>of</span>
  <span m=''1582620''>some</span> <span m=''1582770''>of</span> <span m=''1582810''>the</span>
  <span m=''1582890''>registers</span> <span m=''1583340''>more</span> <span m=''1583500''>than</span>
  <span m=''1583670''>once,</span> <span m=''1584030''>or</span> <span m=''1584150''>some</span>
  <span m=''1584540''>horrible</span> <span m=''1584940''>mess</span> <span m=''1585180''>like</span>
  <span m=''1585340''>that</span> <span m=''1585540''>that</span> <span m=''1585640''>hardware</span>
  <span m=''1585940''>designers</span> <span m=''1586350''>like</span> <span m=''1586520''>to</span>
  <span m=''1586620''>do,</span> <span m=''1587470''>and for</span> <span m=''1587630''>very</span>
  <span m=''1587850''>good</span> <span m=''1588010''>reasons.</span> <span m=''1589250''>So</span>
  <span m=''1589770''>for</span> <span m=''1589930''>example,</span> <span m=''1590300''>here''s</span>
  <span m=''1590560''>a</span> <span m=''1590640''>machine</span> <span m=''1591020''>that</span>
  <span m=''1591080''>you</span> <span m=''1591220''>see,</span> <span m=''1592170''>which</span>
  <span m=''1592990''>you''re</span> <span m=''1593140''>not</span> <span m=''1593380''>supposed</span>
  <span m=''1593720''>to</span> <span m=''1593860''>be</span> <span m=''1594040''>able</span>
  <span m=''1594240''>to</span> <span m=''1594380''>read.</span> <span m=''1595050''>It''s</span>
  <span m=''1595450''>a</span> <span m=''1595500''>little</span> <span m=''1595700''>bit</span>
  <span m=''1595850''>complicated.</span> <span m=''1597520''>But</span> <span m=''1597940''>what</span>
  <span m=''1598210''>it</span> <span m=''1598280''>is</span> <span m=''1598630''>is</span>
  <span m=''1598780''>the</span> <span m=''1598900''>integration</span> <span m=''1599700''>of</span>
  <span m=''1600150''>the</span> <span m=''1600270''>remainder</span> <span m=''1601830''>into</span>
  <span m=''1602800''>the</span> <span m=''1602920''>GCD</span> <span m=''1603370''>machine.</span>
  <span m=''1604210''>And</span> <span m=''1604660''>it</span> <span m=''1604740''>takes,</span>
  <span m=''1604950''>in</span> <span m=''1605020''>fact,</span> <span m=''1605230''>no</span>
  <span m=''1605380''>more</span> <span m=''1605560''>registers.</span> <span m=''1606020''>There</span>
  <span m=''1606190''>are</span> <span m=''1606230''>three</span> <span m=''1606440''>registers</span>
  <span m=''1606950''>in</span> <span m=''1607060''>the</span> <span m=''1607130''>datapaths.</span>
  <span m=''1608360''>OK?</span> </p><p><span m=''1609050''>But</span> <span m=''1609280''>now</span>
  <span m=''1609500''>there''s</span> <span m=''1609750''>a</span> <span m=''1609810''>subtractor.</span>
  <span m=''1611550''>There</span> <span m=''1611750''>are</span> <span m=''1611810''>two</span>
  <span m=''1612030''>things</span> <span m=''1612310''>that are</span> <span m=''1612400''>tested.</span>
  <span m=''1613020''>Is</span> <span m=''1613230''>b</span> <span m=''1614170''>equal</span>
  <span m=''1614500''>to</span> <span m=''1614550''>0,</span> <span m=''1614830''>or</span>
  <span m=''1615120''>is</span> <span m=''1615390''>t</span> <span m=''1615660''>less</span>
  <span m=''1615890''>than</span> <span m=''1616070''>b?</span> </p><p><span m=''1617250''>And</span>
  <span m=''1617470''>then</span> <span m=''1617620''>the</span> <span m=''1617700''>controller,</span>
  <span m=''1618500''>which</span> <span m=''1618660''>you</span> <span m=''1618760''>see</span>
  <span m=''1618950''>over</span> <span m=''1619130''>here,</span> <span m=''1620240''>is</span>
  <span m=''1620420''>not</span> <span m=''1620620''>much</span> <span m=''1620800''>more</span>
  <span m=''1620970''>complicated.</span> <span m=''1621850''>But</span> <span m=''1621980''>it</span>
  <span m=''1622020''>has</span> <span m=''1622970''>two</span> <span m=''1623170''>loops</span>
  <span m=''1623490''>in</span> <span m=''1623600''>it,</span> <span m=''1624570''>one</span>
  <span m=''1624770''>of</span> <span m=''1624850''>which</span> <span m=''1625100''>is</span>
  <span m=''1625260''>the</span> <span m=''1625890''>main</span> <span m=''1626190''>one</span>
  <span m=''1627040''>for</span> <span m=''1627210''>doing</span> <span m=''1627470''>the</span>
  <span m=''1627570''>GCD,</span> <span m=''1628420''>and</span> <span m=''1628580''>one</span>
  <span m=''1628730''>of</span> <span m=''1628800''>which</span> <span m=''1629010''>is</span>
  <span m=''1629110''>the</span> <span m=''1629200''>subtraction</span> <span m=''1629840''>loop</span>
  <span m=''1630370''>for</span> <span m=''1630570''>doing</span> <span m=''1630850''>the</span>
  <span m=''1631130''>remainder</span> <span m=''1632070''>sub-operation.</span> <span
  m=''1634030''>And</span> <span m=''1634270''>there</span> <span m=''1634460''>are</span>
  <span m=''1634520''>ways,</span> <span m=''1634850''>of</span> <span m=''1634950''>course,</span>
  <span m=''1635570''>of,</span> <span m=''1635990''>if</span> <span m=''1636110''>you</span>
  <span m=''1636220''>think</span> <span m=''1636460''>about</span> <span m=''1636770''>it,</span>
  <span m=''1637190''>taking</span> <span m=''1637500''>the</span> <span m=''1637600''>remainder</span>
  <span m=''1638000''>program.</span> <span m=''1639920''>If</span> <span m=''1640060''>I</span>
  <span m=''1640140''>take</span> <span m=''1640380''>remainder,</span> <span m=''1641030''>as</span>
  <span m=''1641140''>you</span> <span m=''1641230''>see</span> <span m=''1641400''>over</span>
  <span m=''1641550''>there,</span> <span m=''1641770''>as</span> <span m=''1641840''>a</span>
  <span m=''1641890''>lambda</span> <span m=''1642270''>expression,</span> <span m=''1643560''>substitute</span>
  <span m=''1643945''>it</span> <span m=''1644330''>in</span> <span m=''1644560''>for</span>
  <span m=''1644850''>remainder</span> <span m=''1645360''>over</span> <span m=''1645530''>here</span>
  <span m=''1645750''>in</span> <span m=''1645830''>the</span> <span m=''1645920''>GCD</span>
  <span m=''1646420''>program,</span> <span m=''1648630''>then</span> <span m=''1648900''>do</span>
  <span m=''1649050''>some</span> <span m=''1649200''>simplification</span> <span
  m=''1650330''>by</span> <span m=''1650460''>substituting</span> <span m=''1650910''>a
  and</span> <span m=''1651210''>b</span> <span m=''1651800''>for</span> <span m=''1652450''>remainder</span>
  <span m=''1653070''>in</span> <span m=''1653220''>there,</span> <span m=''1654490''>then</span>
  <span m=''1654600''>I</span> <span m=''1654670''>can</span> <span m=''1654990''>unwind</span>
  <span m=''1655490''>this</span> <span m=''1655690''>loop.</span> <span m=''1656630''>And</span>
  <span m=''1656750''>I</span> <span m=''1656880''>can</span> <span m=''1657700''>get</span>
  <span m=''1657930''>this</span> <span m=''1658710''>piece</span> <span m=''1658880''>of</span>
  <span m=''1658940''>machinery</span> <span m=''1661010''>by</span> <span m=''1661270''>basically,</span>
  <span m=''1661610''>a</span> <span m=''1661660''>little</span> <span m=''1661860''>bit</span>
  <span m=''1661980''>of</span> <span m=''1663400''>algebraic</span> <span m=''1663790''>simplification</span>
  <span m=''1664280''>on the</span> <span m=''1664370''>lambda</span> <span m=''1664700''>expressions.</span>
  </p><p><span m=''1668550''>So</span> <span m=''1668740''>I</span> <span m=''1668850''>suppose</span>
  <span m=''1669210''>you''ve</span> <span m=''1669360''>seen</span> <span m=''1669530''>your</span>
  <span m=''1669660''>first</span> <span m=''1669910''>very</span> <span m=''1670140''>simple</span>
  <span m=''1670440''>machines</span> <span m=''1670850''>now.</span> <span m=''1672280''>Are</span>
  <span m=''1672400''>there</span> <span m=''1672570''>any</span> <span m=''1672690''>questions?</span>
  <span m=''1682700''>Good.</span> <span m=''1685360''>This</span> <span m=''1685530''>looks</span>
  <span m=''1685630''>easy,</span> <span m=''1685970''>doesn''t</span> <span m=''1686280''>it?</span>
  <span m=''1690200''>Thank</span> <span m=''1690460''>you.</span> <span m=''1690550''>I</span>
  <span m=''1690590''>suppose,</span> <span m=''1690830''>take a</span> <span m=''1690990''>break.</span>
  </p><p><span m=''1691350''>[MUSIC PLAYING - "JESU, JOY OF MAN''S DESIRING" BY JOHANN
  SEBASTIAN BACH]</span> </p><p><span m=''1727310''>PROFESSOR:</span> <span m=''1727700''>Well,</span>
  <span m=''1728090''>let''s</span> <span m=''1728340''>see.</span> <span m=''1729480''>Now</span>
  <span m=''1729640''>you</span> <span m=''1729740''>know</span> <span m=''1729850''>how</span>
  <span m=''1729960''>to</span> <span m=''1730040''>make</span> <span m=''1730320''>an</span>
  <span m=''1731520''>iterative</span> <span m=''1731830''>procedure,</span> <span
  m=''1732610''>or a</span> <span m=''1732750''>procedure</span> <span m=''1733230''>that
  yields</span> <span m=''1733520''>an</span> <span m=''1733600''>iterative</span>
  <span m=''1733930''>process,</span> <span m=''1735340''>turn</span> <span m=''1735530''>into</span>
  <span m=''1735710''>a</span> <span m=''1735760''>machine.</span> <span m=''1737770''>I</span>
  <span m=''1737910''>suppose</span> <span m=''1738270''>the</span> <span m=''1738310''>next</span>
  <span m=''1738540''>thing</span> <span m=''1738670''>we</span> <span m=''1738710''>want</span>
  <span m=''1738890''>to</span> <span m=''1738930''>do</span> <span m=''1739140''>is</span>
  <span m=''1739210''>worry</span> <span m=''1739460''>about</span> <span m=''1739750''>things</span>
  <span m=''1740600''>that</span> <span m=''1741060''>reveal</span> <span m=''1741270''>recursive</span>
  <span m=''1741730''>processes.</span> <span m=''1742690''>So</span> <span m=''1742910''>let''s</span>
  <span m=''1743230''>play</span> <span m=''1743400''>with</span> <span m=''1743530''>a</span>
  <span m=''1743590''>simple</span> <span m=''1743890''>factorial</span> <span m=''1744400''>procedure.</span>
  </p><p><span m=''1750894''>We</span> <span m=''1751390''>define</span> <span m=''1751920''>factorial</span>
  <span m=''1755066''>of</span> <span m=''1755530''>N</span> <span m=''1756120''>to</span>
  <span m=''1756410''>be</span> <span m=''1760042''>if</span> <span m=''1760950''>n</span>
  <span m=''1761550''>is</span> <span m=''1761820''>1,</span> <span m=''1763130''>the</span>
  <span m=''1763220''>result</span> <span m=''1763640''>is</span> <span m=''1763750''>1,</span>
  <span m=''1764690''>using</span> <span m=''1765030''>1</span> <span m=''1765170''>right</span>
  <span m=''1765330''>now</span> <span m=''1765490''>to</span> <span m=''1765600''>decrease</span>
  <span m=''1766010''>the</span> <span m=''1766090''>amount</span> <span m=''1766250''>of</span>
  <span m=''1766320''>work</span> <span m=''1766550''>I</span> <span m=''1766640''>have</span>
  <span m=''1766730''>to</span> <span m=''1766830''>do</span> <span m=''1766950''>to</span>
  <span m=''1767050''>simulate</span> <span m=''1767540''>it,</span> <span m=''1768220''>else</span>
  <span m=''1768540''>it''s</span> <span m=''1769070''>times</span> <span m=''1769740''>N</span>
  <span m=''1770760''>factorial</span> <span m=''1773170''>N</span> <span m=''1773310''>minus</span>
  <span m=''1773630''>1.</span> <span m=''1782520''>And</span> <span m=''1782890''>what''s</span>
  <span m=''1783180''>different</span> <span m=''1784530''>with</span> <span m=''1784680''>this</span>
  <span m=''1784900''>program,</span> <span m=''1785450''>as</span> <span m=''1785540''>you</span>
  <span m=''1785670''>know,</span> <span m=''1786720''>is</span> <span m=''1786970''>that</span>
  <span m=''1787440''>after</span> <span m=''1787820''>I''ve</span> <span m=''1787980''>computed</span>
  <span m=''1788570''>factorial</span> <span m=''1789250''>of</span> <span m=''1789470''>N</span>
  <span m=''1789640''>minus</span> <span m=''1789900''>1</span> <span m=''1790100''>here,</span>
  <span m=''1790670''>I</span> <span m=''1790820''>have</span> <span m=''1790960''>to</span>
  <span m=''1791050''>do</span> <span m=''1791220''>something</span> <span m=''1791630''>to</span>
  <span m=''1791720''>the</span> <span m=''1791820''>result.</span> <span m=''1792260''>I</span>
  <span m=''1792340''>have</span> <span m=''1792440''>to</span> <span m=''1792540''>multiply</span>
  <span m=''1792990''>it</span> <span m=''1793090''>by</span> <span m=''1793230''>N.</span>
  </p><p><span m=''1796000''>So</span> <span m=''1796850''>the</span> <span m=''1797180''>only</span>
  <span m=''1797420''>way</span> <span m=''1797560''>I</span> <span m=''1797680''>can</span>
  <span m=''1798130''>visualize</span> <span m=''1799250''>what</span> <span m=''1799430''>this</span>
  <span m=''1799690''>machine</span> <span m=''1800020''>is</span> <span m=''1800160''>doing,</span>
  <span m=''1801100''>because</span> <span m=''1801560''>of</span> <span m=''1801620''>the</span>
  <span m=''1801690''>fact--</span> <span m=''1802360''>think</span> <span m=''1802570''>of</span>
  <span m=''1802640''>it</span> <span m=''1802710''>this</span> <span m=''1802900''>way,</span>
  <span m=''1803410''>that</span> <span m=''1803530''>I</span> <span m=''1803650''>have</span>
  <span m=''1803760''>a</span> <span m=''1803880''>machine</span> <span m=''1804300''>out</span>
  <span m=''1804520''>here</span> <span m=''1805120''>which</span> <span m=''1805320''>somehow</span>
  <span m=''1805690''>needs</span> <span m=''1805940''>a</span> <span m=''1806190''>factorial</span>
  <span m=''1806640''>machine</span> <span m=''1806890''>in</span> <span m=''1806970''>order</span>
  <span m=''1807110''>to</span> <span m=''1807170''>compute</span> <span m=''1807530''>its</span>
  <span m=''1807670''>answer.</span> <span m=''1809320''>But</span> <span m=''1809550''>this</span>
  <span m=''1809750''>machine,</span> <span m=''1810270''>the</span> <span m=''1810370''>outer</span>
  <span m=''1810660''>machine,</span> <span m=''1811170''>has</span> <span m=''1811390''>to</span>
  <span m=''1811520''>exist</span> <span m=''1812070''>before</span> <span m=''1812550''>and</span>
  <span m=''1812730''>after</span> <span m=''1813950''>the</span> <span m=''1814080''>factorial</span>
  <span m=''1814550''>machine,</span> <span m=''1814870''>which</span> <span m=''1815050''>is</span>
  <span m=''1815140''>inside.</span> <span m=''1816800''>Whereas</span> <span m=''1816980''>in</span>
  <span m=''1817060''>the</span> <span m=''1817230''>iterative</span> <span m=''1817490''>case,</span>
  <span m=''1818400''>the</span> <span m=''1818770''>outer</span> <span m=''1819140''>machine</span>
  <span m=''1819660''>doesn''t</span> <span m=''1819840''>need</span> <span m=''1820080''>to</span>
  <span m=''1820190''>exist</span> <span m=''1820970''>after</span> <span m=''1821280''>the</span>
  <span m=''1821460''>inner</span> <span m=''1821640''>machine</span> <span m=''1822840''>is</span>
  <span m=''1823680''>running,</span> <span m=''1824850''>because</span> <span m=''1825170''>you</span>
  <span m=''1825280''>never</span> <span m=''1825490''>need</span> <span m=''1825650''>to</span>
  <span m=''1825700''>go</span> <span m=''1825830''>back</span> <span m=''1826180''>to</span>
  <span m=''1826290''>the outer</span> <span m=''1826580''>machine</span> <span m=''1826850''>to</span>
  <span m=''1826930''>do</span> <span m=''1827110''>anything.</span> </p><p><span
  m=''1828640''>So</span> <span m=''1829140''>here</span> <span m=''1829350''>we</span>
  <span m=''1829430''>have</span> <span m=''1829550''>a</span> <span m=''1829610''>problem</span>
  <span m=''1830250''>where</span> <span m=''1830390''>we</span> <span m=''1830490''>have</span>
  <span m=''1830650''>a</span> <span m=''1830670''>machine</span> <span m=''1831030''>which</span>
  <span m=''1831200''>has</span> <span m=''1831370''>the</span> <span m=''1831460''>same</span>
  <span m=''1831730''>machine</span> <span m=''1832040''>inside</span> <span m=''1832470''>of</span>
  <span m=''1832570''>it,</span> <span m=''1833642''>an</span> <span m=''1834090''>infinitely</span>
  <span m=''1834610''>large</span> <span m=''1834920''>machine.</span> <span m=''1840390''>And</span>
  <span m=''1840580''>it''s</span> <span m=''1840670''>got</span> <span m=''1840830''>other</span>
  <span m=''1841010''>things</span> <span m=''1841270''>inside of</span> <span m=''1841650''>it,</span>
  <span m=''1841730''>like</span> <span m=''1842180''>a</span> <span m=''1842310''>multiplier,</span>
  <span m=''1844540''>which</span> <span m=''1844780''>takes</span> <span m=''1845110''>some</span>
  <span m=''1845260''>inputs,</span> <span m=''1845790''>and</span> <span m=''1846320''>there''s</span>
  <span m=''1846520''>a</span> <span m=''1846580''>minus</span> <span m=''1846970''>1</span>
  <span m=''1847240''>box,</span> <span m=''1848150''>and</span> <span m=''1848310''>things</span>
  <span m=''1848550''>like</span> <span m=''1848800''>that.</span> <span m=''1850690''>You</span>
  <span m=''1851020''>can</span> <span m=''1851140''>imagine</span> <span m=''1852890''>that''s</span>
  <span m=''1853090''>what</span> <span m=''1853190''>it</span> <span m=''1853260''>looks</span>
  <span m=''1853470''>like.</span> </p><p><span m=''1854370''>But</span> <span m=''1854590''>the</span>
  <span m=''1854690''>important</span> <span m=''1855130''>thing</span> <span m=''1855630''>is</span>
  <span m=''1855970''>that</span> <span m=''1856080''>here</span> <span m=''1856360''>I</span>
  <span m=''1856450''>have</span> <span m=''1856980''>something</span> <span m=''1857340''>that</span>
  <span m=''1857430''>happens</span> <span m=''1857740''>before</span> <span m=''1858300''>and</span>
  <span m=''1858490''>after,</span> <span m=''1858990''>in</span> <span m=''1859110''>the</span>
  <span m=''1859230''>outer</span> <span m=''1859460''>machine,</span> <span m=''1860170''>the</span>
  <span m=''1860360''>execution</span> <span m=''1860820''>of</span> <span m=''1860900''>the
  inner</span> <span m=''1861220''>machine.</span> <span m=''1862540''>So</span> <span
  m=''1862760''>this</span> <span m=''1862970''>machine</span> <span m=''1863290''>has</span>
  <span m=''1863450''>to</span> <span m=''1863510''>have</span> <span m=''1863590''>a</span>
  <span m=''1863680''>life.</span> <span m=''1865570''>It</span> <span m=''1865760''>has</span>
  <span m=''1867030''>to</span> <span m=''1867100''>exist</span> <span m=''1868720''>on</span>
  <span m=''1868870''>both</span> <span m=''1869680''>times</span> <span m=''1870030''>sides</span>
  <span m=''1870600''>of</span> <span m=''1870740''>this</span> <span m=''1870920''>machine.</span>
  </p><p><span m=''1873490''>So</span> <span m=''1873750''>somehow,</span> <span m=''1874130''>I</span>
  <span m=''1874220''>have</span> <span m=''1874380''>to</span> <span m=''1874450''>have</span>
  <span m=''1874600''>a</span> <span m=''1874660''>place</span> <span m=''1875160''>to</span>
  <span m=''1875270''>store</span> <span m=''1876250''>the</span> <span m=''1876370''>things</span>
  <span m=''1876660''>that</span> <span m=''1876770''>this</span> <span m=''1876970''>thing</span>
  <span m=''1877160''>needs</span> <span m=''1877530''>to</span> <span m=''1877700''>run.</span>
  <span m=''1880030''>Infinite</span> <span m=''1880440''>objects</span> <span m=''1880890''>don''t</span>
  <span m=''1881060''>exist</span> <span m=''1881400''>in</span> <span m=''1881470''>the</span>
  <span m=''1881540''>real</span> <span m=''1881790''>world.</span> <span m=''1884140''>What</span>
  <span m=''1884260''>we</span> <span m=''1884350''>have</span> <span m=''1884470''>to</span>
  <span m=''1884560''>do</span> <span m=''1884710''>is</span> <span m=''1884780''>arrange</span>
  <span m=''1885060''>an</span> <span m=''1885110''>illusion</span> <span m=''1885970''>that</span>
  <span m=''1886280''>we</span> <span m=''1886780''>have</span> <span m=''1886930''>an
  infinite</span> <span m=''1887110''>object,</span> <span m=''1888140''>we have</span>
  <span m=''1888210''>an</span> <span m=''1888280''>infinite</span> <span m=''1888540''>amount</span>
  <span m=''1888720''>of</span> <span m=''1888780''>hardware</span> <span m=''1889210''>somewhere.</span>
  </p><p><span m=''1891830''>Now</span> <span m=''1892000''>of</span> <span m=''1892110''>course,</span>
  <span m=''1894060''>illusion''s</span> <span m=''1894470''>all</span> <span m=''1894630''>that</span>
  <span m=''1894720''>really</span> <span m=''1894920''>matters.</span> <span m=''1896280''>If</span>
  <span m=''1896460''>we</span> <span m=''1896550''>can</span> <span m=''1896690''>arrange</span>
  <span m=''1897700''>that</span> <span m=''1898060''>every</span> <span m=''1898280''>time</span>
  <span m=''1898540''>you</span> <span m=''1898630''>look</span> <span m=''1898830''>at</span>
  <span m=''1898910''>some</span> <span m=''1899090''>infinite</span> <span m=''1899370''>object,</span>
  <span m=''1899730''>the</span> <span m=''1899810''>part</span> <span m=''1900040''>of</span>
  <span m=''1900110''>it</span> <span m=''1901030''>that</span> <span m=''1901160''>you</span>
  <span m=''1901280''>look</span> <span m=''1901490''>at</span> <span m=''1902390''>is</span>
  <span m=''1902570''>there,</span> <span m=''1904520''>then</span> <span m=''1904800''>it''s
  as</span> <span m=''1904920''>infinite</span> <span m=''1905220''>as</span> <span
  m=''1905330''>you</span> <span m=''1905430''>need</span> <span m=''1905680''>it
  to</span> <span m=''1905760''>be.</span> <span m=''1907390''>And</span> <span m=''1907560''>of</span>
  <span m=''1907640''>course,</span> <span m=''1908040''>one of the</span> <span m=''1908290''>things</span>
  <span m=''1908470''>we</span> <span m=''1908570''>might</span> <span m=''1908830''>want</span>
  <span m=''1908990''>to</span> <span m=''1909050''>do,</span> <span m=''1909830''>just</span>
  <span m=''1910060''>look</span> <span m=''1910220''>at</span> <span m=''1910310''>this</span>
  <span m=''1911720''>thing</span> <span m=''1911880''>over</span> <span m=''1912080''>here,</span>
  <span m=''1912920''>is</span> <span m=''1913250''>the</span> <span m=''1913320''>organization</span>
  <span m=''1913605''>that</span> <span m=''1913890''>we''ve</span> <span m=''1914040''>had</span>
  <span m=''1914290''>so</span> <span m=''1914520''>far</span> <span m=''1917950''>involves</span>
  <span m=''1918830''>having</span> <span m=''1920160''>a</span> <span m=''1920290''>part</span>
  <span m=''1920790''>of</span> <span m=''1920850''>the</span> <span m=''1920940''>machine,</span>
  <span m=''1921390''>which</span> <span m=''1921590''>is</span> <span m=''1921640''>the</span>
  <span m=''1921720''>controller,</span> <span m=''1923160''>which</span> <span m=''1923400''>sits</span>
  <span m=''1923610''>right</span> <span m=''1923850''>over</span> <span m=''1924030''>here,</span>
  <span m=''1924770''>which</span> <span m=''1925030''>is</span> <span m=''1925140''>perfectly</span>
  <span m=''1925570''>finite</span> <span m=''1926505''>and</span> <span m=''1926850''>very</span>
  <span m=''1927130''>simple.</span> <span m=''1929170''>We</span> <span m=''1929380''>have</span>
  <span m=''1929680''>some</span> <span m=''1929930''>datapaths,</span> <span m=''1930220''>which</span>
  <span m=''1930620''>consist of</span> <span m=''1931070''>registers</span> <span
  m=''1931720''>and</span> <span m=''1931970''>operators.</span> <span m=''1933080''>And</span>
  <span m=''1933190''>what</span> <span m=''1933320''>I</span> <span m=''1933390''>propose</span>
  <span m=''1933800''>to</span> <span m=''1933900''>do</span> <span m=''1934100''>here
  is</span> <span m=''1934340''>decompose</span> <span m=''1935500''>the</span> <span
  m=''1935710''>machine</span> <span m=''1936100''>into</span> <span m=''1936190''>two</span>
  <span m=''1936460''>parts,</span> <span m=''1937350''>such that</span> <span m=''1937610''>there</span>
  <span m=''1937740''>is</span> <span m=''1937850''>a</span> <span m=''1937910''>part</span>
  <span m=''1938330''>which</span> <span m=''1938530''>is</span> <span m=''1938650''>fundamentally</span>
  <span m=''1939260''>finite,</span> <span m=''1940780''>and</span> <span m=''1941020''>some</span>
  <span m=''1941190''>part</span> <span m=''1941570''>where</span> <span m=''1941850''>a
  certain</span> <span m=''1942160''>amount</span> <span m=''1942400''>of</span> <span
  m=''1942560''>infinite</span> <span m=''1942770''>stuff</span> <span m=''1942990''>can</span>
  <span m=''1943120''>be</span> <span m=''1943250''>kept.</span> </p><p><span m=''1944230''>On</span>
  <span m=''1944390''>the</span> <span m=''1944500''>other</span> <span m=''1944610''>hand</span>
  <span m=''1944820''>this is</span> <span m=''1945010''>very</span> <span m=''1945330''>simple</span>
  <span m=''1946400''>and</span> <span m=''1946570''>really</span> <span m=''1946850''>isn''t</span>
  <span m=''1947050''>infinite,</span> <span m=''1947330''>but</span> <span m=''1947610''>it''s</span>
  <span m=''1947810''>just</span> <span m=''1947930''>very</span> <span m=''1948210''>large.</span>
  <span m=''1949430''>But</span> <span m=''1949600''>it''s</span> <span m=''1949730''>so</span>
  <span m=''1949910''>simple</span> <span m=''1950520''>that</span> <span m=''1950610''>it</span>
  <span m=''1950700''>could</span> <span m=''1950820''>be</span> <span m=''1950950''>cheaply</span>
  <span m=''1951300''>reproduced</span> <span m=''1951770''>in</span> <span m=''1951840''>such</span>
  <span m=''1952040''>large</span> <span m=''1952320''>amounts,</span> <span m=''1953503''>we</span>
  <span m=''1953916''>call</span> <span m=''1954330''>it</span> <span m=''1954420''>memory,</span>
  <span m=''1956560''>that</span> <span m=''1956700''>we</span> <span m=''1956800''>can</span>
  <span m=''1956940''>make</span> <span m=''1957400''>a</span> <span m=''1957550''>structure</span>
  <span m=''1957970''>called</span> <span m=''1958170''>a</span> <span m=''1958220''>stack</span>
  <span m=''1958610''>out</span> <span m=''1958750''>of</span> <span m=''1958840''>it</span>
  <span m=''1959370''>which</span> <span m=''1959600''>will</span> <span m=''1959740''>allow</span>
  <span m=''1960060''>us</span> <span m=''1960480''>to,</span> <span m=''1960710''>in</span>
  <span m=''1960820''>fact,</span> <span m=''1961730''>simulate</span> <span m=''1962270''>the</span>
  <span m=''1962340''>existence</span> <span m=''1962800''>of</span> <span m=''1962900''>an</span>
  <span m=''1962990''>infinite</span> <span m=''1963280''>machine</span> <span m=''1963620''>which</span>
  <span m=''1963810''>is made</span> <span m=''1963960''>out of</span> <span m=''1964100''>a</span>
  <span m=''1964150''>recursive</span> <span m=''1964650''>nest</span> <span m=''1965170''>of</span>
  <span m=''1965340''>many</span> <span m=''1966360''>machines.</span> <span m=''1968340''>And</span>
  <span m=''1968490''>the</span> <span m=''1968560''>way</span> <span m=''1968730''>it''s</span>
  <span m=''1968840''>going</span> <span m=''1968980''>to</span> <span m=''1969130''>work</span>
  <span m=''1969940''>is</span> <span m=''1970170''>that</span> <span m=''1970560''>we''re</span>
  <span m=''1970750''>going</span> <span m=''1970960''>to</span> <span m=''1971060''>store</span>
  <span m=''1971760''>in</span> <span m=''1971920''>this</span> <span m=''1972080''>place</span>
  <span m=''1972330''>called</span> <span m=''1972490''>the</span> <span m=''1972550''>stack</span>
  <span m=''1974240''>the</span> <span m=''1974470''>information</span> <span m=''1975000''>required</span>
  <span m=''1975930''>after</span> <span m=''1976290''>the</span> <span m=''1976480''>inner</span>
  <span m=''1976680''>machine</span> <span m=''1977080''>runs</span> <span m=''1979180''>to</span>
  <span m=''1979310''>resume</span> <span m=''1979680''>the</span> <span m=''1979800''>operation</span>
  <span m=''1980270''>of the</span> <span m=''1980400''>outer</span> <span m=''1980590''>machine.</span>
  </p><p><span m=''1983840''>So</span> <span m=''1984390''>it</span> <span m=''1984620''>will</span>
  <span m=''1984870''>remember</span> <span m=''1985670''>the</span> <span m=''1985820''>important</span>
  <span m=''1986210''>things</span> <span m=''1986450''>about</span> <span m=''1986690''>the</span>
  <span m=''1986760''>life</span> <span m=''1987030''>of</span> <span m=''1987130''>the</span>
  <span m=''1987240''>outer</span> <span m=''1987460''>machine</span> <span m=''1988090''>that</span>
  <span m=''1988230''>will</span> <span m=''1988310''>be</span> <span m=''1988450''>needed</span>
  <span m=''1988900''>for</span> <span m=''1989030''>this</span> <span m=''1989510''>computation.</span>
  <span m=''1991390''>Since,</span> <span m=''1991820''>of</span> <span m=''1991950''>course,</span>
  <span m=''1992850''>these</span> <span m=''1993080''>machines</span> <span m=''1993490''>are</span>
  <span m=''1993630''>nested</span> <span m=''1994832''>in</span> <span m=''1995190''>a</span>
  <span m=''1995380''>recursive</span> <span m=''1995880''>manner,</span> <span m=''1998320''>then</span>
  <span m=''1998680''>in</span> <span m=''1998770''>fact</span> <span m=''1999340''>the</span>
  <span m=''1999460''>stack</span> <span m=''1999860''>will</span> <span m=''1999970''>only</span>
  <span m=''2000150''>be</span> <span m=''2000320''>accessed</span> <span m=''2001750''>in</span>
  <span m=''2002870''>a</span> <span m=''2002920''>manner</span> <span m=''2003460''>which</span>
  <span m=''2003750''>is</span> <span m=''2004280''>the</span> <span m=''2004420''>last</span>
  <span m=''2004720''>thing</span> <span m=''2004850''>that</span> <span m=''2004950''>goes</span>
  <span m=''2005170''>in is</span> <span m=''2005330''>the</span> <span m=''2005450''>first</span>
  <span m=''2005690''>thing</span> <span m=''2005790''>that</span> <span m=''2005870''>comes</span>
  <span m=''2006110''>out.</span> <span m=''2009330''>So</span> <span m=''2009560''>we''ll</span>
  <span m=''2009680''>only</span> <span m=''2009800''>need</span> <span m=''2010010''>to</span>
  <span m=''2010090''>access</span> <span m=''2010740''>some</span> <span m=''2011000''>little</span>
  <span m=''2011210''>part</span> <span m=''2011510''>of</span> <span m=''2011600''>this</span>
  <span m=''2011720''>stack</span> <span m=''2012170''>memory.</span> </p><p><span
  m=''2014930''>OK,</span> <span m=''2015240''>well,</span> <span m=''2015340''>let''s</span>
  <span m=''2015590''>do</span> <span m=''2015770''>it.</span> <span m=''2016810''>I''m
  going</span> <span m=''2016970''>to</span> <span m=''2017030''>build</span> <span
  m=''2017330''>you</span> <span m=''2017480''>a</span> <span m=''2017530''>datapath</span>
  <span m=''2018100''>now,</span> <span m=''2018480''>and I''m</span> <span m=''2018630''>going</span>
  <span m=''2018690''>to</span> <span m=''2018750''>write</span> <span m=''2019010''>the</span>
  <span m=''2019090''>controller.</span> <span m=''2020370''>And</span> <span m=''2020600''>then</span>
  <span m=''2020730''>we''re</span> <span m=''2020850''>going</span> <span m=''2021040''>to</span>
  <span m=''2021360''>execute</span> <span m=''2021810''>this</span> <span m=''2021990''>to</span>
  <span m=''2022090''>see</span> <span m=''2022230''>how</span> <span m=''2022410''>you</span>
  <span m=''2022550''>do</span> <span m=''2022750''>it.</span> <span m=''2023510''>So</span>
  <span m=''2024010''>the</span> <span m=''2024130''>factorial</span> <span m=''2024630''>machine</span>
  <span m=''2025930''>isn''t</span> <span m=''2026210''>so</span> <span m=''2026360''>bad.</span>
  <span m=''2027900''>It''s</span> <span m=''2028070''>going</span> <span m=''2028190''>to</span>
  <span m=''2028380''>have</span> <span m=''2028730''>a</span> <span m=''2028870''>register</span>
  <span m=''2029280''>called</span> <span m=''2029460''>the</span> <span m=''2029530''>value,</span>
  <span m=''2032280''>where</span> <span m=''2032490''>the</span> <span m=''2032660''>answer</span>
  <span m=''2033000''>is</span> <span m=''2033070''>going</span> <span m=''2033180''>to</span>
  <span m=''2033300''>be</span> <span m=''2033410''>stored,</span> <span m=''2034930''>and</span>
  <span m=''2035210''>a</span> <span m=''2035290''>registered</span> <span m=''2035790''>called</span>
  <span m=''2036150''>N,</span> <span m=''2039890''>which</span> <span m=''2040030''>is</span>
  <span m=''2040130''>where</span> <span m=''2040640''>the</span> <span m=''2040730''>number</span>
  <span m=''2041050''>I''m</span> <span m=''2041180''>taking</span> <span m=''2041500''>factorial</span>
  <span m=''2042100''>will</span> <span m=''2042210''>be</span> <span m=''2042330''>stored,</span>
  <span m=''2043300''>factorial</span> <span m=''2043670''>of.</span> <span m=''2044165''>And</span>
  <span m=''2044660''>it</span> <span m=''2044700''>will</span> <span m=''2044800''>be</span>
  <span m=''2044920''>necessary</span> <span m=''2045570''>in</span> <span m=''2045660''>some</span>
  <span m=''2045910''>instances</span> <span m=''2047480''>to</span> <span m=''2048500''>connect</span>
  <span m=''2049630''>VAL</span> <span m=''2049780''>to</span> <span m=''2050130''>N.</span>
  </p><p><span m=''2051760''>In</span> <span m=''2051920''>fact,</span> <span m=''2052310''>one</span>
  <span m=''2052639''>nice</span> <span m=''2052940''>case</span> <span m=''2053210''>of</span>
  <span m=''2053310''>this</span> <span m=''2053820''>is</span> <span m=''2054000''>if
  I</span> <span m=''2054159''>just</span> <span m=''2054440''>said</span> <span m=''2054949''>over</span>
  <span m=''2055150''>here,</span> <span m=''2056389''>N,</span> <span m=''2057000''>because</span>
  <span m=''2057139''>that</span> <span m=''2057270''>would</span> <span m=''2057350''>be</span>
  <span m=''2057489''>right</span> <span m=''2058260''>for</span> <span m=''2058409''>N</span>
  <span m=''2058540''>equal</span> <span m=''2058800''>1N.</span> <span m=''2059139''>And</span>
  <span m=''2059820''>I</span> <span m=''2060130''>could</span> <span m=''2060270''>just</span>
  <span m=''2060540''>move</span> <span m=''2060719''>the</span> <span m=''2060850''>answer</span>
  <span m=''2061170''>over</span> <span m=''2061389''>there</span> <span m=''2062380''>if</span>
  <span m=''2062510''>that''s</span> <span m=''2062730''>important.</span> <span m=''2063909''>I''m</span>
  <span m=''2064030''>not</span> <span m=''2064210''>worried</span> <span m=''2064460''>about</span>
  <span m=''2064710''>that</span> <span m=''2064920''>right</span> <span m=''2065150''>now.</span>
  </p><p><span m=''2066980''>And</span> <span m=''2067139''>there</span> <span m=''2067360''>are</span>
  <span m=''2067420''>things</span> <span m=''2067639''>I</span> <span m=''2067699''>have</span>
  <span m=''2067830''>to</span> <span m=''2067900''>be</span> <span m=''2067989''>able</span>
  <span m=''2068120''>to</span> <span m=''2068219''>do.</span> <span m=''2069060''>Like</span>
  <span m=''2069330''>I</span> <span m=''2069400''>have</span> <span m=''2069600''>to</span>
  <span m=''2069699''>be</span> <span m=''2069880''>able</span> <span m=''2070090''>to,</span>
  <span m=''2070239''>as</span> <span m=''2070409''>we</span> <span m=''2070530''>see</span>
  <span m=''2070760''>here,</span> <span m=''2071210''>multiply</span> <span m=''2071790''>N</span>
  <span m=''2072440''>by</span> <span m=''2072650''>something</span> <span m=''2074199''>in</span>
  <span m=''2074290''>VAL,</span> <span m=''2075000''>because</span> <span m=''2075250''>VAL</span>
  <span m=''2075650''>is</span> <span m=''2075810''>the</span> <span m=''2075900''>result</span>
  <span m=''2076350''>of</span> <span m=''2076440''>computing</span> <span m=''2076780''>factorial.</span>
  <span m=''2078290''>And</span> <span m=''2078750''>I</span> <span m=''2078980''>have
  to put</span> <span m=''2079219''>the</span> <span m=''2079280''>result</span> <span
  m=''2079639''>back</span> <span m=''2079870''>into</span> <span m=''2080070''>VAL.</span>
  </p><p><span m=''2081429''>So</span> <span m=''2081739''>here</span> <span m=''2081929''>we</span>
  <span m=''2082100''>can</span> <span m=''2082219''>see</span> <span m=''2082820''>that</span>
  <span m=''2083030''>the</span> <span m=''2083110''>result</span> <span m=''2085030''>of</span>
  <span m=''2085159''>computing</span> <span m=''2085590''>a</span> <span m=''2085639''>factorial</span>
  <span m=''2086600''>is</span> <span m=''2086949''>N</span> <span m=''2087260''>times</span>
  <span m=''2087610''>the</span> <span m=''2087690''>result</span> <span m=''2088070''>of</span>
  <span m=''2088210''>computing a</span> <span m=''2088590''>factorial.</span> <span
  m=''2090690''>VAL</span> <span m=''2090985''>will</span> <span m=''2091280''>be
  the</span> <span m=''2091330''>representation</span> <span m=''2092080''>of</span>
  <span m=''2092250''>the</span> <span m=''2092380''>answer</span> <span m=''2092770''>of</span>
  <span m=''2092860''>the</span> <span m=''2092989''>inner</span> <span m=''2093159''>factorial.</span>
  <span m=''2095199''>And</span> <span m=''2095389''>so</span> <span m=''2096199''>I''m</span>
  <span m=''2096360''>going</span> <span m=''2096540''>to</span> <span m=''2096610''>have</span>
  <span m=''2096800''>to</span> <span m=''2097000''>have</span> <span m=''2097490''>a</span>
  <span m=''2099220''>multiplier</span> <span m=''2099940''>here,</span> <span m=''2102370''>which
  is</span> <span m=''2102680''>going</span> <span m=''2102890''>to</span> <span m=''2102980''>sample</span>
  <span m=''2103400''>the</span> <span m=''2103480''>value</span> <span m=''2103880''>of</span>
  <span m=''2104000''>N</span> <span m=''2105780''>and</span> <span m=''2105940''>the</span>
  <span m=''2106100''>value</span> <span m=''2106540''>of</span> <span m=''2106720''>VAL</span>
  <span m=''2109220''>and</span> <span m=''2109350''>put</span> <span m=''2109560''>the</span>
  <span m=''2109650''>result</span> <span m=''2110100''>back</span> <span m=''2110380''>into</span>
  <span m=''2110600''>VAL</span> <span m=''2115070''>like</span> <span m=''2115240''>that.</span>
  </p><p><span m=''2117170''>I''m</span> <span m=''2117310''>also</span> <span m=''2117540''>going</span>
  <span m=''2117710''>to</span> <span m=''2117820''>have to</span> <span m=''2117960''>be
  able</span> <span m=''2118160''>to see</span> <span m=''2118380''>if</span> <span
  m=''2118460''>N is</span> <span m=''2118770''>1.</span> <span m=''2120618''>So</span>
  <span m=''2121064''>I</span> <span m=''2121510''>need a</span> <span m=''2121670''>light</span>
  <span m=''2121940''>bulb.</span> <span m=''2128200''>And</span> <span m=''2128430''>I</span>
  <span m=''2128500''>suppose</span> <span m=''2128870''>the</span> <span m=''2128980''>other</span>
  <span m=''2129160''>thing</span> <span m=''2129340''>I''m</span> <span m=''2129440''>going</span>
  <span m=''2129610''>to</span> <span m=''2129710''>need</span> <span m=''2129920''>to</span>
  <span m=''2130000''>have</span> <span m=''2131010''>is</span> <span m=''2131210''>a</span>
  <span m=''2131270''>way</span> <span m=''2131540''>of</span> <span m=''2131760''>decrementing</span>
  <span m=''2132430''>N.</span> <span m=''2134850''>So</span> <span m=''2134980''>I''m</span>
  <span m=''2135100''>going</span> <span m=''2135190''>to</span> <span m=''2135230''>have</span>
  <span m=''2135340''>a</span> <span m=''2135400''>decrementer,</span> <span m=''2138260''>which</span>
  <span m=''2138460''>takes</span> <span m=''2138750''>N</span> <span m=''2139110''>and</span>
  <span m=''2139600''>is</span> <span m=''2139750''>going</span> <span m=''2139940''>to</span>
  <span m=''2139990''>put</span> <span m=''2140200''>back</span> <span m=''2140430''>the</span>
  <span m=''2140520''>result</span> <span m=''2140930''>into</span> <span m=''2141130''>N.</span>
  <span m=''2146620''>That''s</span> <span m=''2146830''>pretty</span> <span m=''2147020''>much</span>
  <span m=''2147250''>what</span> <span m=''2147370''>I</span> <span m=''2147460''>need
  in</span> <span m=''2147750''>my</span> <span m=''2147890''>machine.</span> </p><p><span
  m=''2149550''>Now,</span> <span m=''2150400''>there''s</span> <span m=''2150560''>a</span>
  <span m=''2150600''>little</span> <span m=''2150840''>bit</span> <span m=''2150980''>else</span>
  <span m=''2151250''>I</span> <span m=''2151330''>need.</span> <span m=''2151985''>It''s</span>
  <span m=''2152320''>a</span> <span m=''2152410''>little</span> <span m=''2152660''>bit</span>
  <span m=''2152800''>more</span> <span m=''2152970''>complicated,</span> <span m=''2155110''>because</span>
  <span m=''2155270''>I''m</span> <span m=''2155410''>also</span> <span m=''2155620''>going</span>
  <span m=''2155740''>to</span> <span m=''2155800''>need</span> <span m=''2156030''>a</span>
  <span m=''2156070''>way</span> <span m=''2156210''>to</span> <span m=''2156360''>store,</span>
  <span m=''2157240''>to</span> <span m=''2157360''>save</span> <span m=''2157610''>away,</span>
  <span m=''2158410''>the</span> <span m=''2158510''>things</span> <span m=''2158870''>that
  are</span> <span m=''2158980''>going</span> <span m=''2159090''>to</span> <span
  m=''2159130''>be</span> <span m=''2159280''>needed</span> <span m=''2161060''>for</span>
  <span m=''2161340''>resuming</span> <span m=''2161810''>the</span> <span m=''2161900''>computation</span>
  <span m=''2162460''>of a</span> <span m=''2162600''>factorial</span> <span m=''2163120''>after</span>
  <span m=''2163420''>I''ve</span> <span m=''2163810''>done</span> <span m=''2164040''>a</span>
  <span m=''2164100''>sub-factorial.</span> <span m=''2166250''>What''s</span> <span
  m=''2166590''>that?</span> <span m=''2167230''>One</span> <span m=''2167430''>thing</span>
  <span m=''2167590''>I</span> <span m=''2167680''>need</span> <span m=''2168190''>is</span>
  <span m=''2168350''>N.</span> </p><p><span m=''2169850''>So</span> <span m=''2170080''>I''m
  going</span> <span m=''2170160''>to</span> <span m=''2170230''>build</span> <span
  m=''2170520''>here</span> <span m=''2170980''>a</span> <span m=''2171090''>thing</span>
  <span m=''2171290''>called</span> <span m=''2171500''>a</span> <span m=''2171590''>stack.</span>
  <span m=''2174700''>The</span> <span m=''2174840''>stack</span> <span m=''2175300''>is</span>
  <span m=''2177980''>a</span> <span m=''2178080''>bunch</span> <span m=''2178390''>of</span>
  <span m=''2178500''>stuff</span> <span m=''2182716''>that</span> <span m=''2183200''>I''m</span>
  <span m=''2183310''>going</span> <span m=''2183470''>to</span> <span m=''2183630''>write</span>
  <span m=''2183920''>in</span> <span m=''2184130''>sequentially.</span> <span m=''2187410''>I</span>
  <span m=''2187500''>don''t</span> <span m=''2187630''>how</span> <span m=''2187780''>long</span>
  <span m=''2188110''>it</span> <span m=''2188560''>is.</span> <span m=''2188916''>The</span>
  <span m=''2189272''>longer</span> <span m=''2189630''>it</span> <span m=''2189700''>is,</span>
  <span m=''2189880''>the</span> <span m=''2189970''>better</span> <span m=''2190200''>my</span>
  <span m=''2190350''>illusion of</span> <span m=''2190800''>infinity.</span> <span
  m=''2192890''>And</span> <span m=''2193300''>I''m</span> <span m=''2193530''>going</span>
  <span m=''2193710''>to</span> <span m=''2193870''>have</span> <span m=''2194030''>to</span>
  <span m=''2194130''>have</span> <span m=''2194560''>a</span> <span m=''2194710''>way</span>
  <span m=''2194910''>of</span> <span m=''2195020''>getting</span> <span m=''2195310''>stuff</span>
  <span m=''2195650''>out</span> <span m=''2195930''>of N and</span> <span m=''2196250''>into</span>
  <span m=''2196570''>the</span> <span m=''2196660''>stack</span> <span m=''2198130''>and</span>
  <span m=''2198390''>vice</span> <span m=''2198650''>versa.</span> <span m=''2199515''>So</span>
  <span m=''2200000''>I''m going to</span> <span m=''2200240''>need a</span> <span
  m=''2200560''>connection</span> <span m=''2200990''>like</span> <span m=''2201260''>this,</span>
  <span m=''2204460''>which</span> <span m=''2204610''>is</span> <span m=''2204740''>two-way,</span>
  <span m=''2210460''>whereby</span> <span m=''2210880''>I</span> <span m=''2210970''>can</span>
  <span m=''2211130''>save</span> <span m=''2211410''>the</span> <span m=''2211520''>value</span>
  <span m=''2211850''>of</span> <span m=''2211960''>N</span> <span m=''2212250''>and</span>
  <span m=''2212380''>then</span> <span m=''2212500''>restore</span> <span m=''2212755''>it</span>
  <span m=''2213010''>some</span> <span m=''2213160''>other</span> <span m=''2213330''>time</span>
  <span m=''2214580''>through</span> <span m=''2214750''>that</span> <span m=''2214970''>connection.</span>
  <span m=''2215820''>This</span> <span m=''2216150''>is</span> <span m=''2216330''>the</span>
  <span m=''2216410''>stack.</span> </p><p><span m=''2218100''>I</span> <span m=''2218260''>also</span>
  <span m=''2218560''>need</span> <span m=''2218800''>a</span> <span m=''2218850''>way</span>
  <span m=''2220520''>of</span> <span m=''2220930''>remembering</span> <span m=''2221870''>where</span>
  <span m=''2222260''>I</span> <span m=''2222340''>was</span> <span m=''2222600''>in</span>
  <span m=''2222690''>the</span> <span m=''2222790''>computation</span> <span m=''2224460''>of</span>
  <span m=''2224640''>factorial</span> <span m=''2225770''>in</span> <span m=''2225960''>the</span>
  <span m=''2226950''>outer</span> <span m=''2227150''>program.</span> <span m=''2228530''>Now</span>
  <span m=''2228720''>in</span> <span m=''2228790''>the</span> <span m=''2228890''>case</span>
  <span m=''2229200''>of</span> <span m=''2229290''>this</span> <span m=''2229520''>machine,</span>
  <span m=''2230760''>it</span> <span m=''2231090''>isn''t</span> <span m=''2232400''>very</span>
  <span m=''2232550''>much a</span> <span m=''2232750''>problem.</span> <span m=''2234090''>Factorial</span>
  <span m=''2235330''>always</span> <span m=''2235540''>returns,</span> <span m=''2236850''>has</span>
  <span m=''2236990''>to</span> <span m=''2237150''>go</span> <span m=''2237280''>back</span>
  <span m=''2237570''>to</span> <span m=''2237650''>the</span> <span m=''2237720''>place</span>
  <span m=''2237920''>where</span> <span m=''2238020''>we</span> <span m=''2238110''>multiply</span>
  <span m=''2238500''>by</span> <span m=''2238670''>N,</span> <span m=''2239430''>except</span>
  <span m=''2239750''>for</span> <span m=''2239810''>the</span> <span m=''2239890''>last</span>
  <span m=''2240260''>time,</span> <span m=''2241180''>when</span> <span m=''2241390''>it
  has to</span> <span m=''2241650''>return</span> <span m=''2242000''>to</span> <span
  m=''2242110''>whatever</span> <span m=''2242260''>needs</span> <span m=''2242410''>the</span>
  <span m=''2242560''>factorial</span> <span m=''2243060''>or go</span> <span m=''2243160''>to</span>
  <span m=''2243270''>done or</span> <span m=''2243640''>stop.</span> <span m=''2245660''>However,</span>
  <span m=''2246090''>in</span> <span m=''2246220''>general,</span> <span m=''2247180''>I''m</span>
  <span m=''2247330''>going</span> <span m=''2247430''>to have to</span> <span m=''2247590''>remember</span>
  <span m=''2247960''>where</span> <span m=''2248160''>I have</span> <span m=''2248330''>been,</span>
  <span m=''2248940''>because</span> <span m=''2249220''>I</span> <span m=''2249330''>might</span>
  <span m=''2249520''>have</span> <span m=''2249600''>computed</span> <span m=''2249990''>factorial</span>
  <span m=''2250440''>from</span> <span m=''2250570''>somewhere</span> <span m=''2250900''>else.</span>
  <span m=''2251770''>I</span> <span m=''2252140''>have</span> <span m=''2252290''>to</span>
  <span m=''2252330''>go</span> <span m=''2252440''>back</span> <span m=''2252720''>to</span>
  <span m=''2252800''>that</span> <span m=''2253010''>place</span> <span m=''2253960''>and</span>
  <span m=''2254110''>continue</span> <span m=''2254530''>there.</span> </p><p><span
  m=''2256070''>So</span> <span m=''2256210''>I''m</span> <span m=''2256290''>going</span>
  <span m=''2256380''>to</span> <span m=''2256470''>have</span> <span m=''2256560''>to</span>
  <span m=''2256660''>have</span> <span m=''2256760''>some</span> <span m=''2257020''>way</span>
  <span m=''2257180''>of</span> <span m=''2257290''>taking</span> <span m=''2257620''>the</span>
  <span m=''2257710''>place</span> <span m=''2257990''>where</span> <span m=''2258090''>the</span>
  <span m=''2258200''>marble</span> <span m=''2258630''>is</span> <span m=''2258820''>in</span>
  <span m=''2258910''>the</span> <span m=''2259860''>finite</span> <span m=''2260180''>state</span>
  <span m=''2260300''>controller,</span> <span m=''2261420''>the</span> <span m=''2261500''>state</span>
  <span m=''2261810''>of</span> <span m=''2261900''>the</span> <span m=''2262060''>controller,</span>
  <span m=''2264190''>and</span> <span m=''2264440''>storing</span> <span m=''2264860''>that</span>
  <span m=''2265240''>in</span> <span m=''2265390''>the</span> <span m=''2265460''>stack</span>
  <span m=''2265820''>as</span> <span m=''2265930''>well.</span> <span m=''2267400''>And</span>
  <span m=''2267610''>I''m going to</span> <span m=''2267640''>have</span> <span m=''2267740''>to</span>
  <span m=''2267870''>have</span> <span m=''2267980''>ways</span> <span m=''2268170''>of</span>
  <span m=''2268270''>restoring</span> <span m=''2268820''>that</span> <span m=''2269490''>back</span>
  <span m=''2269740''>to</span> <span m=''2269840''>the</span> <span m=''2270040''>state</span>
  <span m=''2270340''>of the--</span> <span m=''2270620''>the</span> <span m=''2270720''>marble.</span>
  <span m=''2271870''>So</span> <span m=''2272230''>I have</span> <span m=''2272420''>to
  have</span> <span m=''2272620''>something that</span> <span m=''2272670''>moves
  the</span> <span m=''2272990''>marble</span> <span m=''2273420''>to</span> <span
  m=''2273510''>the</span> <span m=''2273570''>right</span> <span m=''2273800''>place.</span>
  </p><p><span m=''2274310''>Well,</span> <span m=''2274690''>we''re</span> <span
  m=''2274960''>going</span> <span m=''2275220''>to have a</span> <span m=''2275260''>place</span>
  <span m=''2275560''>which</span> <span m=''2275700''>is</span> <span m=''2275780''>the</span>
  <span m=''2275870''>marble</span> <span m=''2276250''>now.</span> <span m=''2277462''>And</span>
  <span m=''2277930''>it''s</span> <span m=''2278020''>called</span> <span m=''2278120''>the</span>
  <span m=''2278310''>continue</span> <span m=''2278720''>register,</span> <span m=''2283650''>called</span>
  <span m=''2283790''>continue,</span> <span m=''2289220''>which</span> <span m=''2289380''>is</span>
  <span m=''2289480''>the</span> <span m=''2289570''>place</span> <span m=''2289860''>to</span>
  <span m=''2289960''>put</span> <span m=''2290140''>the</span> <span m=''2290210''>marble</span>
  <span m=''2291110''>next</span> <span m=''2291480''>time</span> <span m=''2292060''>I</span>
  <span m=''2292180''>go</span> <span m=''2292350''>to</span> <span m=''2292430''>continue.</span>
  <span m=''2294260''>That''s</span> <span m=''2294700''>what</span> <span m=''2295140''>that''s</span>
  <span m=''2295460''>for.</span> <span m=''2296140''>And</span> <span m=''2296320''>so</span>
  <span m=''2296430''>there''s</span> <span m=''2296600''>got</span> <span m=''2296690''>to</span>
  <span m=''2296790''>be</span> <span m=''2296890''>some</span> <span m=''2297080''>path</span>
  <span m=''2297360''>from</span> <span m=''2297460''>that</span> <span m=''2297890''>into
  the</span> <span m=''2297990''>controller.</span> </p><p><span m=''2302910''>I</span>
  <span m=''2303030''>also</span> <span m=''2303300''>have to have</span> <span m=''2303590''>some</span>
  <span m=''2303890''>way</span> <span m=''2304150''>of</span> <span m=''2304250''>saving</span>
  <span m=''2304700''>that</span> <span m=''2306270''>on</span> <span m=''2306500''>the</span>
  <span m=''2306560''>stack.</span> <span m=''2309074''>And</span> <span m=''2309490''>I</span>
  <span m=''2309700''>have</span> <span m=''2309880''>to have</span> <span m=''2309950''>some
  way of</span> <span m=''2310430''>setting</span> <span m=''2310760''>that</span>
  <span m=''2310960''>up</span> <span m=''2311870''>to</span> <span m=''2311960''>have</span>
  <span m=''2312120''>various</span> <span m=''2312450''>constants,</span> <span m=''2314040''>a</span>
  <span m=''2314120''>certain</span> <span m=''2314540''>fixed</span> <span m=''2314780''>number</span>
  <span m=''2314990''>of</span> <span m=''2315060''>constants.</span> <span m=''2316860''>And</span>
  <span m=''2316960''>that''s</span> <span m=''2317170''>very</span> <span m=''2317400''>easy</span>
  <span m=''2317550''>to</span> <span m=''2317650''>arrange.</span> <span m=''2318840''>So</span>
  <span m=''2318980''>let''s</span> <span m=''2319090''>have</span> <span m=''2319230''>some</span>
  <span m=''2319380''>constants</span> <span m=''2319820''>here.</span> <span m=''2320180''>We''ll</span>
  <span m=''2320330''>call</span> <span m=''2320550''>this</span> <span m=''2320670''>one</span>
  <span m=''2320830''>after-fact.</span> <span m=''2327430''>And</span> <span m=''2327680''>that''s</span>
  <span m=''2327920''>a</span> <span m=''2328070''>constant</span> <span m=''2328890''>which</span>
  <span m=''2329150''>we''ll</span> <span m=''2329930''>get</span> <span m=''2330110''>into</span>
  <span m=''2330340''>the</span> <span m=''2330440''>continue</span> <span m=''2330890''>register,</span>
  <span m=''2332660''>and</span> <span m=''2332810''>also</span> <span m=''2333080''>another</span>
  <span m=''2333270''>one</span> <span m=''2333460''>called</span> <span m=''2333670''>fact-done.</span>
  </p><p><span m=''2345210''>So</span> <span m=''2345370''>this</span> <span m=''2345560''>is</span>
  <span m=''2345700''>the</span> <span m=''2346480''>machine</span> <span m=''2346890''>I</span>
  <span m=''2346970''>want</span> <span m=''2347220''>to</span> <span m=''2347310''>build.</span>
  <span m=''2348130''>That''s</span> <span m=''2348270''>its</span> <span m=''2348660''>datapaths,</span>
  <span m=''2349040''>at</span> <span m=''2349100''>least.</span> <span m=''2349930''>And</span>
  <span m=''2350220''>it mixes</span> <span m=''2350550''>a</span> <span m=''2350600''>little</span>
  <span m=''2350810''>with</span> <span m=''2350900''>the</span> <span m=''2351000''>controller</span>
  <span m=''2351440''>here,</span> <span m=''2351950''>because</span> <span m=''2352250''>of
  the</span> <span m=''2352350''>fact</span> <span m=''2352540''>that</span> <span
  m=''2352730''>I</span> <span m=''2352790''>have</span> <span m=''2352990''>to</span>
  <span m=''2353380''>remember</span> <span m=''2353790''>where</span> <span m=''2354050''>I</span>
  <span m=''2354090''>was</span> <span m=''2354690''>and</span> <span m=''2354850''>restore</span>
  <span m=''2355220''>myself</span> <span m=''2355620''>to that</span> <span m=''2355870''>place.</span>
  </p><p><span m=''2357300''>But</span> <span m=''2357420''>let''s</span> <span m=''2357590''>write</span>
  <span m=''2357820''>the</span> <span m=''2357890''>program</span> <span m=''2358440''>now</span>
  <span m=''2358630''>which</span> <span m=''2358780''>represents</span> <span m=''2359240''>the</span>
  <span m=''2359310''>controller.</span> <span m=''2360390''>I''m</span> <span m=''2360700''>not</span>
  <span m=''2360920''>going</span> <span m=''2361030''>to</span> <span m=''2361080''>write</span>
  <span m=''2361360''>the</span> <span m=''2361450''>define</span> <span m=''2361860''>machine</span>
  <span m=''2362310''>thing</span> <span m=''2362610''>and the</span> <span m=''2362760''>register</span>
  <span m=''2363160''>list,</span> <span m=''2363540''>because</span> <span m=''2363850''>that''s</span>
  <span m=''2364060''>not</span> <span m=''2364180''>very</span> <span m=''2364350''>interesting.</span>
  <span m=''2364890''>I''m</span> <span m=''2365180''>just</span> <span m=''2365280''>going</span>
  <span m=''2365370''>to</span> <span m=''2365420''>write</span> <span m=''2365660''>down</span>
  <span m=''2366290''>the</span> <span m=''2366410''>sequence</span> <span m=''2366930''>of</span>
  <span m=''2367420''>instructions</span> <span m=''2368020''>that</span> <span m=''2368150''>constitute</span>
  <span m=''2368530''>the</span> <span m=''2368600''>controller.</span> </p><p><span
  m=''2370920''>So</span> <span m=''2371370''>we</span> <span m=''2371670''>have</span>
  <span m=''2372400''>assign,</span> <span m=''2374300''>to</span> <span m=''2374420''>set</span>
  <span m=''2374680''>up,</span> <span m=''2376320''>continue</span> <span m=''2381130''>to</span>
  <span m=''2381250''>done.</span> <span m=''2384476''>We</span> <span m=''2384927''>have</span>
  <span m=''2385380''>a</span> <span m=''2385460''>loop</span> <span m=''2386950''>which</span>
  <span m=''2387360''>says</span> <span m=''2387780''>branch</span> <span m=''2392090''>if</span>
  <span m=''2394030''>equal</span> <span m=''2394400''>1</span> <span m=''2395180''>fetch</span>
  <span m=''2395450''>N,</span> <span m=''2401010''>if</span> <span m=''2401150''>N</span>
  <span m=''2401350''>is</span> <span m=''2401450''>1,</span> <span m=''2402260''>then</span>
  <span m=''2402440''>go</span> <span m=''2402590''>to</span> <span m=''2402650''>the</span>
  <span m=''2402750''>base</span> <span m=''2403040''>step of the</span> <span m=''2403410''>induction,</span>
  <span m=''2406220''>the</span> <span m=''2406300''>simple</span> <span m=''2406640''>case.</span>
  </p><p><span m=''2408050''>Otherwise,</span> <span m=''2408930''>I</span> <span
  m=''2409030''>have</span> <span m=''2409230''>to</span> <span m=''2409350''>remember</span>
  <span m=''2409890''>the</span> <span m=''2410010''>things</span> <span m=''2410240''>that</span>
  <span m=''2410320''>are</span> <span m=''2410380''>necessary</span> <span m=''2410740''>to</span>
  <span m=''2410840''>perform</span> <span m=''2411380''>a</span> <span m=''2412850''>sub-factorial.</span>
  <span m=''2414265''>I''m</span> <span m=''2414690''>going to</span> <span m=''2414890''>go</span>
  <span m=''2415140''>over here,</span> <span m=''2415390''>and</span> <span m=''2415540''>I
  have to</span> <span m=''2415620''>perform</span> <span m=''2416120''>a</span> <span
  m=''2416280''>sub-factorial.</span> <span m=''2417570''>So I</span> <span m=''2417700''>have</span>
  <span m=''2417780''>to</span> <span m=''2420440''>remember</span> <span m=''2420740''>what''s</span>
  <span m=''2420970''>needed</span> <span m=''2421220''>after</span> <span m=''2421560''>I
  will</span> <span m=''2421750''>be</span> <span m=''2421870''>done</span> <span
  m=''2422110''>with</span> <span m=''2422290''>that.</span> </p><p><span m=''2424000''>See,</span>
  <span m=''2424160''>I''m</span> <span m=''2424250''>about</span> <span m=''2424550''>to</span>
  <span m=''2424610''>do</span> <span m=''2424760''>something</span> <span m=''2425020''>terrible.</span>
  <span m=''2425510''>I''m</span> <span m=''2425780''>about</span> <span m=''2426180''>to</span>
  <span m=''2426270''>change</span> <span m=''2426570''>the</span> <span m=''2426650''>value</span>
  <span m=''2426940''>of</span> <span m=''2427010''>N.</span> <span m=''2428580''>But</span>
  <span m=''2428750''>this</span> <span m=''2428940''>guy</span> <span m=''2429040''>has</span>
  <span m=''2429240''>to</span> <span m=''2429310''>know</span> <span m=''2429430''>the</span>
  <span m=''2429540''>old</span> <span m=''2429740''>value</span> <span m=''2430050''>of</span>
  <span m=''2430150''>N.</span> <span m=''2432070''>But</span> <span m=''2432310''>in</span>
  <span m=''2432360''>order</span> <span m=''2432500''>to</span> <span m=''2432560''>make</span>
  <span m=''2432730''>the</span> <span m=''2432780''>sub-factorial</span> <span m=''2433520''>work,</span>
  <span m=''2433730''>I</span> <span m=''2433820''>have to change</span> <span m=''2434170''>the</span>
  <span m=''2434230''>value</span> <span m=''2434490''>of</span> <span m=''2434570''>N.</span>
  <span m=''2435570''>So</span> <span m=''2435710''>I</span> <span m=''2435790''>have
  to</span> <span m=''2436070''>remember</span> <span m=''2436370''>the</span> <span
  m=''2436480''>old</span> <span m=''2436650''>value.</span> <span m=''2438000''>And</span>
  <span m=''2438120''>I</span> <span m=''2438190''>also</span> <span m=''2438390''>have</span>
  <span m=''2438490''>to</span> <span m=''2438550''>remember</span> <span m=''2438880''>where</span>
  <span m=''2439110''>I''ve</span> <span m=''2439230''>been.</span> <span m=''2440850''>So</span>
  <span m=''2441180''>I</span> <span m=''2441280''>save</span> <span m=''2441560''>up</span>
  <span m=''2441670''>continue.</span> </p><p><span m=''2447705''>And</span> <span
  m=''2448210''>this</span> <span m=''2448390''>is</span> <span m=''2448480''>an</span>
  <span m=''2448550''>instruction</span> <span m=''2449150''>that</span> <span m=''2449260''>says,</span>
  <span m=''2450060''>put</span> <span m=''2450260''>something</span> <span m=''2450610''>in</span>
  <span m=''2450770''>the</span> <span m=''2450850''>stack.</span> <span m=''2453580''>Save</span>
  <span m=''2453780''>the</span> <span m=''2453930''>contents</span> <span m=''2454320''>of</span>
  <span m=''2454390''>the</span> <span m=''2454470''>continuation</span> <span m=''2455040''>register,</span>
  <span m=''2456570''>which</span> <span m=''2456760''>in</span> <span m=''2456900''>this</span>
  <span m=''2457040''>case</span> <span m=''2457340''>is</span> <span m=''2457500''>done,</span>
  <span m=''2458550''>because</span> <span m=''2459080''>later</span> <span m=''2459330''>I''m</span>
  <span m=''2459410''>going</span> <span m=''2459500''>to</span> <span m=''2459560''>change</span>
  <span m=''2459830''>that, too,</span> <span m=''2460160''>because</span> <span m=''2460300''>I</span>
  <span m=''2460360''>need</span> <span m=''2460520''>to</span> <span m=''2460570''>go</span>
  <span m=''2460690''>back to</span> <span m=''2460970''>after-fact,</span> <span
  m=''2462320''>as</span> <span m=''2462450''>well.</span> <span m=''2463550''>We''ll</span>
  <span m=''2463690''>see</span> <span m=''2463880''>that.</span> </p><p><span m=''2465040''>We</span>
  <span m=''2465150''>save</span> <span m=''2465470''>N,</span> <span m=''2468500''>because</span>
  <span m=''2468690''>I''m going to</span> <span m=''2468790''>need</span> <span m=''2468990''>that</span>
  <span m=''2469170''>for</span> <span m=''2469270''>later.</span> <span m=''2470380''>Assign</span>
  <span m=''2473540''>to</span> <span m=''2473800''>N</span> <span m=''2475000''>the</span>
  <span m=''2475110''>decrement</span> <span m=''2476502''>of</span> <span m=''2476850''>fetch</span>
  <span m=''2480000''>N.</span> <span m=''2483300''>Assign</span> <span m=''2488180''>continue,</span>
  <span m=''2491422''>we''re</span> <span m=''2491864''>going to</span> <span m=''2492310''>look</span>
  <span m=''2492510''>at</span> <span m=''2492720''>this</span> <span m=''2492990''>now,</span>
  <span m=''2494140''>to</span> <span m=''2494420''>after,</span> <span m=''2494820''>we''ll</span>
  <span m=''2494940''>call</span> <span m=''2495398''>it.</span> <span m=''2497690''>That''s</span>
  <span m=''2497860''>a</span> <span m=''2497900''>good</span> <span m=''2498070''>name</span>
  <span m=''2498300''>for</span> <span m=''2498420''>this,</span> <span m=''2498780''>a
  little</span> <span m=''2499000''>bit</span> <span m=''2499120''>easier</span> <span
  m=''2499470''>and</span> <span m=''2499560''>shorter,</span> <span m=''2499890''>and</span>
  <span m=''2500020''>fits</span> <span m=''2500200''>in</span> <span m=''2500290''>here.</span>
  </p><p><span m=''2512772''>Now</span> <span m=''2513244''>look</span> <span m=''2513720''>what</span>
  <span m=''2513880''>I''m</span> <span m=''2514000''>doing</span> <span m=''2514280''>here.</span>
  <span m=''2515330''>I''m</span> <span m=''2515470''>saying,</span> <span m=''2515790''>if</span>
  <span m=''2515960''>the</span> <span m=''2516110''>answer</span> <span m=''2516380''>is</span>
  <span m=''2516490''>1,</span> <span m=''2518970''>I''m</span> <span m=''2519150''>done.</span>
  <span m=''2520065''>I''m</span> <span m=''2520490''>going to</span> <span m=''2520610''>have</span>
  <span m=''2520760''>to</span> <span m=''2520860''>just</span> <span m=''2521040''>get</span>
  <span m=''2521160''>the</span> <span m=''2521260''>answer.</span> <span m=''2522150''>Otherwise,</span>
  <span m=''2522750''>I''m</span> <span m=''2522930''>going</span> <span m=''2523040''>to</span>
  <span m=''2523080''>save</span> <span m=''2523310''>the</span> <span m=''2523440''>continuation,</span>
  <span m=''2524110''>save</span> <span m=''2524390''>N,</span> <span m=''2525880''>make</span>
  <span m=''2526160''>N</span> <span m=''2526400''>one</span> <span m=''2526600''>less</span>
  <span m=''2526840''>than</span> <span m=''2527140''>N,</span> <span m=''2527690''>remember</span>
  <span m=''2528170''>I''m</span> <span m=''2528280''>going</span> <span m=''2528390''>to</span>
  <span m=''2528440''>come</span> <span m=''2528630''>back</span> <span m=''2528850''>to</span>
  <span m=''2528940''>someplace</span> <span m=''2529420''>else,</span> <span m=''2529630''>and</span>
  <span m=''2529780''>go</span> <span m=''2529910''>back</span> <span m=''2530190''>and</span>
  <span m=''2530300''>start</span> <span m=''2530530''>doing</span> <span m=''2530770''>another</span>
  <span m=''2530930''>factorial.</span> </p><p><span m=''2533980''>However,</span>
  <span m=''2534190''>I''ve</span> <span m=''2534250''>got a</span> <span m=''2534430''>different</span>
  <span m=''2534770''>machine</span> <span m=''2535240''>[? in me ?]</span> <span
  m=''2535370''>now.</span> <span m=''2536050''>N</span> <span m=''2536220''>is</span>
  <span m=''2536360''>1,</span> <span m=''2536840''>and</span> <span m=''2537000''>continue</span>
  <span m=''2537480''>is</span> <span m=''2537580''>something</span> <span m=''2537980''>else.</span>
  <span m=''2542160''>N</span> <span m=''2542340''>is</span> <span m=''2542440''>N</span>
  <span m=''2542550''>minus</span> <span m=''2542830''>1.</span> </p><p><span m=''2543590''>Now</span>
  <span m=''2544010''>after</span> <span m=''2544400''>I''m</span> <span m=''2544560''>done</span>
  <span m=''2544800''>with</span> <span m=''2544920''>that,</span> <span m=''2546635''>I</span>
  <span m=''2547070''>can</span> <span m=''2547260''>go</span> <span m=''2547440''>there.</span>
  <span m=''2548660''>I</span> <span m=''2548760''>will</span> <span m=''2548910''>restore</span>
  <span m=''2549430''>the</span> <span m=''2549550''>old</span> <span m=''2549720''>value</span>
  <span m=''2550060''>of</span> <span m=''2550501''>N,</span> <span m=''2552710''>which</span>
  <span m=''2552910''>is</span> <span m=''2553040''>the</span> <span m=''2553490''>opposite</span>
  <span m=''2554010''>of</span> <span m=''2554130''>this</span> <span m=''2554400''>save</span>
  <span m=''2555810''>over</span> <span m=''2556040''>here.</span> <span m=''2558360''>I</span>
  <span m=''2558450''>will</span> <span m=''2558570''>restore</span> <span m=''2558900''>the</span>
  <span m=''2558970''>continuation.</span> </p><p><span m=''2569660''>I</span> <span
  m=''2569780''>will</span> <span m=''2569980''>then</span> <span m=''2571670''>go</span>
  <span m=''2571780''>to</span> <span m=''2571890''>here.</span> <span m=''2574320''>I
  will</span> <span m=''2574760''>assign</span> <span m=''2578610''>to</span> <span
  m=''2579100''>the</span> <span m=''2579490''>VAL</span> <span m=''2580250''>register</span>
  <span m=''2581190''>the</span> <span m=''2581340''>product</span> <span m=''2583310''>of</span>
  <span m=''2583920''>N</span> <span m=''2587010''>and</span> <span m=''2587420''>fetch</span>
  <span m=''2587770''>VAL.</span> <span m=''2593520''>VAL</span> <span m=''2595370''>fetch</span>
  <span m=''2596370''>product</span> <span m=''2597590''>assign.</span> </p><p><span
  m=''2599790''>And</span> <span m=''2599940''>then</span> <span m=''2600150''>I</span>
  <span m=''2600230''>will</span> <span m=''2600830''>be</span> <span m=''2600980''>done.</span>
  <span m=''2601440''>I will</span> <span m=''2601630''>have</span> <span m=''2601770''>my</span>
  <span m=''2601910''>answer</span> <span m=''2602460''>to</span> <span m=''2602580''>the</span>
  <span m=''2602660''>sub-factorial</span> <span m=''2604950''>in</span> <span m=''2605390''>VAL.</span>
  <span m=''2606570''>At</span> <span m=''2606740''>that</span> <span m=''2606980''>point,</span>
  <span m=''2607710''>I''m</span> <span m=''2607860''>going</span> <span m=''2607990''>to</span>
  <span m=''2608030''>return</span> <span m=''2609320''>by</span> <span m=''2609450''>going</span>
  <span m=''2609620''>to</span> <span m=''2609790''>the</span> <span m=''2609860''>place</span>
  <span m=''2610140''>where</span> <span m=''2610260''>the</span> <span m=''2610330''>continuation</span>
  <span m=''2611040''>is</span> <span m=''2611130''>pointing.</span> <span m=''2613640''>That</span>
  <span m=''2613970''>says,</span> <span m=''2614410''>go</span> <span m=''2614570''>to</span>
  <span m=''2614720''>fetch</span> <span m=''2614970''>continue.</span> </p><p><span
  m=''2625870''>And</span> <span m=''2626140''>then I</span> <span m=''2626270''>have</span>
  <span m=''2626400''>finally</span> <span m=''2626700''>a base</span> <span m=''2627150''>step,</span>
  <span m=''2628646''>which</span> <span m=''2629058''>is</span> <span m=''2629470''>the</span>
  <span m=''2629610''>immediate</span> <span m=''2629950''>answer.</span> <span m=''2630730''>Assign</span>
  <span m=''2633686''>to</span> <span m=''2634050''>VAL</span> <span m=''2635730''>fetch</span>
  <span m=''2636170''>N,</span> <span m=''2641380''>and</span> <span m=''2641610''>go</span>
  <span m=''2641770''>to</span> <span m=''2641940''>fetch</span> <span m=''2642160''>continue.</span>
  <span m=''2652670''>And</span> <span m=''2652820''>then</span> <span m=''2653010''>I''m</span>
  <span m=''2653100''>done.</span> </p><p><span m=''2658640''>Now</span> <span m=''2658820''>let''s</span>
  <span m=''2658980''>see</span> <span m=''2659080''>how</span> <span m=''2659250''>this</span>
  <span m=''2659450''>executes</span> <span m=''2660070''>on</span> <span m=''2660230''>a</span>
  <span m=''2660270''>very</span> <span m=''2660480''>simple</span> <span m=''2660820''>case,</span>
  <span m=''2662470''>because</span> <span m=''2662830''>then</span> <span m=''2662910''>we''ll</span>
  <span m=''2663100''>see</span> <span m=''2663700''>the</span> <span m=''2663870''>use</span>
  <span m=''2664090''>of</span> <span m=''2664190''>this</span> <span m=''2664420''>stack</span>
  <span m=''2665350''>to</span> <span m=''2665450''>do</span> <span m=''2665570''>the</span>
  <span m=''2665700''>job</span> <span m=''2666030''>we</span> <span m=''2666140''>need.</span>
  <span m=''2666890''>This</span> <span m=''2667060''>is</span> <span m=''2667130''>statically</span>
  <span m=''2667550''>what</span> <span m=''2667680''>it''s</span> <span m=''2667980''>doing,</span>
  <span m=''2668320''>but</span> <span m=''2668410''>we</span> <span m=''2668500''>have</span>
  <span m=''2668620''>look</span> <span m=''2668820''>dynamically</span> <span m=''2669390''>at</span>
  <span m=''2669500''>this.</span> <span m=''2671340''>So</span> <span m=''2671540''>let''s</span>
  <span m=''2671770''>see.</span> </p><p><span m=''2672300''>First</span> <span m=''2672560''>thing</span>
  <span m=''2672750''>we</span> <span m=''2672830''>do</span> <span m=''2673310''>is</span>
  <span m=''2673470''>continue</span> <span m=''2673880''>gets</span> <span m=''2674110''>done.</span>
  <span m=''2676730''>The way</span> <span m=''2676920''>that</span> <span m=''2677070''>happened</span>
  <span m=''2677400''>is I</span> <span m=''2677450''>pushed</span> <span m=''2677730''>this.</span>
  <span m=''2678300''>Let''s</span> <span m=''2678490''>call</span> <span m=''2678670''>that</span>
  <span m=''2679060''>done the way I</span> <span m=''2679350''>have</span> <span
  m=''2679640''>it.</span> <span m=''2686390''>I push</span> <span m=''2686550''>that</span>
  <span m=''2686750''>button.</span> <span m=''2687030''>Done</span> <span m=''2687250''>goes</span>
  <span m=''2687480''>into</span> <span m=''2687700''>there.</span> </p><p><span m=''2688950''>Now</span>
  <span m=''2691070''>I</span> <span m=''2691310''>also</span> <span m=''2691610''>have</span>
  <span m=''2691740''>to</span> <span m=''2691820''>set</span> <span m=''2692030''>this</span>
  <span m=''2692170''>thing</span> <span m=''2692340''>up</span> <span m=''2692470''>to</span>
  <span m=''2692550''>have an</span> <span m=''2692780''>initial</span> <span m=''2693160''>value.</span>
  <span m=''2693850''>Let''s</span> <span m=''2695660''>consider</span> <span m=''2696690''>a</span>
  <span m=''2697080''>factorial</span> <span m=''2697355''>of</span> <span m=''2697630''>three,</span>
  <span m=''2698430''>a</span> <span m=''2698520''>simple</span> <span m=''2698820''>case.</span>
  <span m=''2700192''>And</span> <span m=''2700590''>we''re</span> <span m=''2700750''>going</span>
  <span m=''2700880''>to</span> <span m=''2700930''>start</span> <span m=''2701230''>out</span>
  <span m=''2701980''>with</span> <span m=''2702250''>our</span> <span m=''2702430''>stack</span>
  <span m=''2703010''>growing</span> <span m=''2703430''>over</span> <span m=''2703650''>here.</span>
  <span m=''2705900''>Stacks</span> <span m=''2706370''>have</span> <span m=''2706540''>their</span>
  <span m=''2706700''>own</span> <span m=''2706840''>little</span> <span m=''2707040''>internal</span>
  <span m=''2707430''>state</span> <span m=''2707800''>saying</span> <span m=''2708200''>where</span>
  <span m=''2708520''>they</span> <span m=''2708670''>are,</span> <span m=''2709890''>where</span>
  <span m=''2710030''>the</span> <span m=''2710070''>next</span> <span m=''2710400''>place</span>
  <span m=''2710660''>I''m</span> <span m=''2710790''>going</span> <span m=''2710970''>to</span>
  <span m=''2711070''>write</span> <span m=''2711310''>is.</span> </p><p><span m=''2712770''>So</span>
  <span m=''2712990''>now</span> <span m=''2713200''>we</span> <span m=''2713310''>say,</span>
  <span m=''2713830''>is</span> <span m=''2714040''>N</span> <span m=''2714310''>1?</span>
  <span m=''2714590''>The</span> <span m=''2714870''>answer</span> <span m=''2715220''>is</span>
  <span m=''2715320''>no.</span> <span m=''2716110''>So</span> <span m=''2716260''>now</span>
  <span m=''2716420''>I''m</span> <span m=''2716500''>going</span> <span m=''2716560''>to</span>
  <span m=''2716620''>save</span> <span m=''2716870''>continue,</span> <span m=''2717940''>bang.</span>
  <span m=''2719066''>Now</span> <span m=''2719420''>that</span> <span m=''2719640''>done</span>
  <span m=''2719840''>goes</span> <span m=''2720050''>in</span> <span m=''2720160''>here.</span>
  <span m=''2722080''>And</span> <span m=''2722570''>this</span> <span m=''2722800''>moves</span>
  <span m=''2723110''>to</span> <span m=''2723210''>here,</span> <span m=''2724526''>the</span>
  <span m=''2724970''>next</span> <span m=''2725220''>place</span> <span m=''2725420''>I''m</span>
  <span m=''2725530''>going</span> <span m=''2725690''>to</span> <span m=''2725790''>write.</span>
  </p><p><span m=''2726660''>Save</span> <span m=''2727150''>N</span> <span m=''2728090''>3.</span>
  <span m=''2729950''>OK?</span> <span m=''2730750''>Assign</span> <span m=''2730910''>to</span>
  <span m=''2731070''>N</span> <span m=''2732140''>the</span> <span m=''2732300''>decrement</span>
  <span m=''2732820''>of</span> <span m=''2733040''>N.</span> <span m=''2733840''>That</span>
  <span m=''2734150''>means</span> <span m=''2734240''>I''ve</span> <span m=''2734300''>pushed</span>
  <span m=''2734530''>this</span> <span m=''2734800''>button.</span> <span m=''2735940''>This</span>
  <span m=''2736100''>becomes</span> <span m=''2736860''>2.</span> </p><p><span m=''2740400''>Assign</span>
  <span m=''2740840''>to</span> <span m=''2740900''>continue</span> <span m=''2741880''>aft.</span>
  <span m=''2742580''>So</span> <span m=''2742740''>I''ve</span> <span m=''2742800''>pushed</span>
  <span m=''2743050''>that</span> <span m=''2743340''>button.</span> <span m=''2743610''>Aft</span>
  <span m=''2743910''>goes</span> <span m=''2744120''>in</span> <span m=''2744220''>here.</span>
  </p><p><span m=''2749140''>OK,</span> <span m=''2749510''>now</span> <span m=''2751620''>go</span>
  <span m=''2751800''>to</span> <span m=''2752130''>loop,</span> <span m=''2752880''>bang,</span>
  <span m=''2753210''>so up to</span> <span m=''2753510''>here.</span> <span m=''2754830''>Is</span>
  <span m=''2755640''>N</span> <span m=''2755780''>1?</span> <span m=''2756570''>No.</span>
  </p><p><span m=''2757780''>So I have</span> <span m=''2758120''>to</span> <span
  m=''2758180''>save</span> <span m=''2758540''>continue.</span> <span m=''2759490''>What''s</span>
  <span m=''2759710''>continue?</span> <span m=''2760600''>Continue</span> <span m=''2760890''>is</span>
  <span m=''2761180''>aft.</span> <span m=''2761530''>Push</span> <span m=''2761760''>this</span>
  <span m=''2762020''>button.</span> <span m=''2762780''>So</span> <span m=''2763030''>this</span>
  <span m=''2763210''>moves to</span> <span m=''2763490''>here.</span> </p><p><span
  m=''2768490''>I</span> <span m=''2768600''>have</span> <span m=''2768770''>to</span>
  <span m=''2768870''>save</span> <span m=''2769170''>N.</span> <span m=''2770530''>N</span>
  <span m=''2770750''>is</span> <span m=''2770900''>over</span> <span m=''2771160''>here.</span>
  <span m=''2771460''>I got</span> <span m=''2771580''>to</span> <span m=''2771710''>2.</span>
  <span m=''2772280''>Push</span> <span m=''2772480''>that</span> <span m=''2772820''>button.</span>
  <span m=''2773655''>So a</span> <span m=''2774100''>2</span> <span m=''2774280''>gets</span>
  <span m=''2774490''>written</span> <span m=''2774750''>there.</span> <span m=''2776050''>And</span>
  <span m=''2776340''>then</span> <span m=''2776520''>this</span> <span m=''2776720''>thing</span>
  <span m=''2776900''>moves</span> <span m=''2777100''>down</span> <span m=''2777350''>here.</span>
  </p><p><span m=''2780060''>OK,</span> <span m=''2780240''>save</span> <span m=''2780540''>N.</span>
  <span m=''2780860''>Assign</span> <span m=''2781240''>N to</span> <span m=''2781560''>the</span>
  <span m=''2781640''>decrement</span> <span m=''2782130''>of</span> <span m=''2782550''>N.</span>
  <span m=''2784214''>This</span> <span m=''2784630''>becomes</span> <span m=''2785010''>a</span>
  <span m=''2785070''>1.</span> <span m=''2789240''>Assign</span> <span m=''2789700''>continue</span>
  <span m=''2789960''>to</span> <span m=''2790230''>aft.</span> <span m=''2791370''>A-F-T</span>
  <span m=''2793410''>gets</span> <span m=''2793560''>written</span> <span m=''2793760''>there</span>
  <span m=''2793990''>again.</span> </p><p><span m=''2794960''>Go</span> <span m=''2795150''>to</span>
  <span m=''2795350''>loop.</span> <span m=''2796520''>Is N</span> <span m=''2796770''>equal</span>
  <span m=''2797180''>to</span> <span m=''2797300''>1?</span> <span m=''2797930''>Oh,</span>
  <span m=''2798090''>yes,</span> <span m=''2798440''>the</span> <span m=''2798550''>answer</span>
  <span m=''2798880''>is</span> <span m=''2799020''>1.</span> </p><p><span m=''2801160''>OK,</span>
  <span m=''2801210''>go</span> <span m=''2801430''>to</span> <span m=''2802610''>base</span>
  <span m=''2802980''>step.</span> <span m=''2804160''>Assign</span> <span m=''2804640''>to</span>
  <span m=''2805020''>VAL</span> <span m=''2805180''>fetch of</span> <span m=''2805290''>N.</span>
  <span m=''2806600''>Bang,</span> <span m=''2808190''>1</span> <span m=''2808420''>gets</span>
  <span m=''2808630''>put</span> <span m=''2808760''>in</span> <span m=''2808840''>there.</span>
  </p><p><span m=''2811100''>Go</span> <span m=''2811290''>to</span> <span m=''2811710''>fetch
  continue.</span> <span m=''2812200''>So</span> <span m=''2812330''>we</span> <span
  m=''2812440''>look</span> <span m=''2812590''>in</span> <span m=''2812740''>continue.</span>
  <span m=''2813680''>Basically,</span> <span m=''2813980''>I''m</span> <span m=''2814380''>pushing</span>
  <span m=''2814540''>a button</span> <span m=''2814810''>over here</span> <span m=''2815080''>that
  goes to</span> <span m=''2815350''>the</span> <span m=''2815420''>controller.</span>
  <span m=''2817130''>The</span> <span m=''2817230''>continue</span> <span m=''2817640''>becomes</span>
  <span m=''2818030''>aft,</span> <span m=''2818290''>and</span> <span m=''2818460''>all</span>
  <span m=''2818560''>of</span> <span m=''2818670''>a</span> <span m=''2818700''>sudden,</span>
  <span m=''2818960''>the</span> <span m=''2819220''>program''s</span> <span m=''2819580''>running</span>
  <span m=''2819840''>here.</span> </p><p><span m=''2822640''>I</span> <span m=''2822800''>now</span>
  <span m=''2823000''>have to</span> <span m=''2823130''>restore</span> <span m=''2823610''>the</span>
  <span m=''2823790''>outer</span> <span m=''2824500''>version</span> <span m=''2824870''>of</span>
  <span m=''2824950''>factorial.</span> <span m=''2826650''>So</span> <span m=''2826970''>we</span>
  <span m=''2827090''>go</span> <span m=''2827250''>here.</span> <span m=''2827550''>We</span>
  <span m=''2827690''>say,</span> <span m=''2828430''>restore</span> <span m=''2829020''>N.</span>
  <span m=''2830240''>So</span> <span m=''2830440''>restore</span> <span m=''2830870''>N</span>
  <span m=''2831150''>means</span> <span m=''2831480''>take</span> <span m=''2831730''>the</span>
  <span m=''2831840''>contents</span> <span m=''2832410''>that''s</span> <span m=''2832550''>here.</span>
  <span m=''2833940''>Push</span> <span m=''2834260''>this</span> <span m=''2834480''>button,</span>
  <span m=''2835120''>and</span> <span m=''2835260''>it</span> <span m=''2835320''>goes</span>
  <span m=''2835560''>into</span> <span m=''2835740''>here,</span> <span m=''2837620''>2,</span>
  <span m=''2838790''>and</span> <span m=''2839040''>the</span> <span m=''2839190''>pointer</span>
  <span m=''2839520''>moves</span> <span m=''2839780''>up.</span> </p><p><span m=''2842230''>Restore</span>
  <span m=''2842530''>continue,</span> <span m=''2843610''>pretty</span> <span m=''2843900''>easy.</span>
  <span m=''2844810''>Go</span> <span m=''2844990''>push</span> <span m=''2845660''>this</span>
  <span m=''2845950''>button.</span> <span m=''2847020''>And</span> <span m=''2847450''>then</span>
  <span m=''2847630''>aft gets</span> <span m=''2847820''>written</span> <span m=''2848040''>in</span>
  <span m=''2848150''>here</span> <span m=''2848370''>again.</span> <span m=''2851280''>That</span>
  <span m=''2851550''>means</span> <span m=''2851800''>this</span> <span m=''2851990''>thing</span>
  <span m=''2852180''>moves</span> <span m=''2852420''>up.</span> <span m=''2852640''>I''ve</span>
  <span m=''2853370''>gotten</span> <span m=''2853550''>rid</span> <span m=''2853750''>of</span>
  <span m=''2853840''>something</span> <span m=''2854210''>else</span> <span m=''2854450''>on</span>
  <span m=''2854640''>my</span> <span m=''2854790''>stack.</span> </p><p><span m=''2862240''>Right,</span>
  <span m=''2862540''>then</span> <span m=''2862690''>I</span> <span m=''2862760''>go</span>
  <span m=''2862950''>to</span> <span m=''2863010''>here,</span> <span m=''2864000''>which</span>
  <span m=''2864160''>says,</span> <span m=''2864690''>assign</span> <span m=''2865160''>to</span>
  <span m=''2865240''>VAL</span> <span m=''2865820''>the</span> <span m=''2865930''>product</span>
  <span m=''2866290''>of N an</span> <span m=''2866660''>VAL.</span> <span m=''2867850''>So</span>
  <span m=''2868020''>I</span> <span m=''2868100''>push</span> <span m=''2868340''>this</span>
  <span m=''2868560''>button</span> <span m=''2868840''>over</span> <span m=''2869060''>here,</span>
  <span m=''2869990''>bang.</span> <span m=''2870970''>2</span> <span m=''2871180''>times</span>
  <span m=''2871570''>1</span> <span m=''2871980''>gives</span> <span m=''2872200''>me</span>
  <span m=''2872380''>a</span> <span m=''2872490''>2,</span> <span m=''2873336''>get</span>
  <span m=''2873792''>written</span> <span m=''2874250''>there.</span> </p><p><span
  m=''2875920''>Go</span> <span m=''2876130''>to</span> <span m=''2876300''>fetch</span>
  <span m=''2876530''>continue.</span> <span m=''2877540''>Continue</span> <span m=''2878360''>is</span>
  <span m=''2878760''>aft.</span> <span m=''2879190''>I</span> <span m=''2879290''>go
  to</span> <span m=''2879490''>aft.</span> <span m=''2881290''>Aft</span> <span m=''2882070''>says</span>
  <span m=''2882940''>restore</span> <span m=''2883460''>N.</span> <span m=''2884340''>Do</span>
  <span m=''2884490''>your</span> <span m=''2884630''>restore</span> <span m=''2885130''>N,</span>
  <span m=''2885940''>means</span> <span m=''2886190''>I</span> <span m=''2886270''>take</span>
  <span m=''2886550''>the</span> <span m=''2886640''>value</span> <span m=''2887080''>over</span>
  <span m=''2887260''>here,</span> <span m=''2887510''>which</span> <span m=''2887710''>is</span>
  <span m=''2887860''>3,</span> <span m=''2888870''>push</span> <span m=''2889370''>this</span>
  <span m=''2889570''>up</span> <span m=''2889750''>to</span> <span m=''2889830''>here,</span>
  <span m=''2890660''>and</span> <span m=''2890850''>move</span> <span m=''2891030''>it
  into</span> <span m=''2891270''>here,</span> <span m=''2895326''>N.</span> <span
  m=''2895798''>Now</span> <span m=''2896270''>it''s</span> <span m=''2896460''>pushing</span>
  <span m=''2896780''>that</span> <span m=''2897000''>button.</span> </p><p><span
  m=''2897715''>The</span> <span m=''2898200''>next</span> <span m=''2898410''>thing</span>
  <span m=''2898530''>I</span> <span m=''2898580''>do</span> <span m=''2898740''>is</span>
  <span m=''2898790''>restore</span> <span m=''2899200''>continue.</span> <span m=''2900200''>Continue</span>
  <span m=''2900760''>is</span> <span m=''2900900''>now</span> <span m=''2901140''>going</span>
  <span m=''2901250''>to</span> <span m=''2901350''>become</span> <span m=''2901650''>done.</span>
  <span m=''2902830''>So</span> <span m=''2903560''>this</span> <span m=''2904100''>moves</span>
  <span m=''2904320''>up</span> <span m=''2904520''>here</span> <span m=''2904920''>when</span>
  <span m=''2905090''>I</span> <span m=''2905180''>push</span> <span m=''2905860''>this</span>
  <span m=''2906170''>button.</span> <span m=''2907260''>Done</span> <span m=''2908300''>may</span>
  <span m=''2908540''>or</span> <span m=''2908620''>may</span> <span m=''2908760''>be</span>
  <span m=''2909000''>there</span> <span m=''2909360''>anymore,</span> <span m=''2909690''>I''m</span>
  <span m=''2909770''>not</span> <span m=''2909920''>interested,</span> <span m=''2910470''>but</span>
  <span m=''2910590''>it</span> <span m=''2910660''>certainly</span> <span m=''2911040''>is</span>
  <span m=''2911130''>here.</span> </p><p><span m=''2915800''>Next</span> <span m=''2916020''>thing</span>
  <span m=''2916190''>I</span> <span m=''2916330''>do</span> <span m=''2916760''>is</span>
  <span m=''2917140''>assign</span> <span m=''2917540''>to</span> <span m=''2917870''>VAL</span>
  <span m=''2918520''>the</span> <span m=''2918620''>product</span> <span m=''2919040''>of</span>
  <span m=''2919130''>the</span> <span m=''2919290''>fetch</span> <span m=''2919590''>of
  N</span> <span m=''2919810''>and</span> <span m=''2919970''>the fetch</span> <span
  m=''2920220''>of</span> <span m=''2920260''>VAL.</span> <span m=''2921440''>That''s</span>
  <span m=''2921620''>pushing</span> <span m=''2921920''>this</span> <span m=''2922140''>button</span>
  <span m=''2922950''>over</span> <span m=''2923180''>here,</span> <span m=''2923570''>bang.</span>
  <span m=''2924300''>2</span> <span m=''2924500''>times</span> <span m=''2924870''>3</span>
  <span m=''2925120''>is</span> <span m=''2925260''>6.</span> <span m=''2926520''>So</span>
  <span m=''2926650''>I</span> <span m=''2926740''>get</span> <span m=''2926870''>a</span>
  <span m=''2926920''>6</span> <span m=''2927210''>over</span> <span m=''2927510''>here.</span>
  </p><p><span m=''2932020''>And</span> <span m=''2932240''>go</span> <span m=''2932390''>to</span>
  <span m=''2932500''>fetch</span> <span m=''2932770''>continue,</span> <span m=''2933510''>whoops,</span>
  <span m=''2933750''>I</span> <span m=''2933800''>go</span> <span m=''2934010''>to
  done,</span> <span m=''2934270''>and</span> <span m=''2934340''>I''m</span> <span
  m=''2934590''>done.</span> <span m=''2935020''>And</span> <span m=''2935160''>my</span>
  <span m=''2935280''>answer</span> <span m=''2935610''>is</span> <span m=''2935690''>6,</span>
  <span m=''2936200''>as</span> <span m=''2936590''>you can see</span> <span m=''2936875''>in
  the</span> <span m=''2937160''>VAL</span> <span m=''2937380''>register.</span> <span
  m=''2938950''>And</span> <span m=''2939320''>in</span> <span m=''2939400''>fact,</span>
  <span m=''2940970''>the</span> <span m=''2941080''>stack</span> <span m=''2941490''>is</span>
  <span m=''2941790''>in</span> <span m=''2942000''>the</span> <span m=''2942060''>state</span>
  <span m=''2942320''>it</span> <span m=''2942380''>originally</span> <span m=''2942830''>was</span>
  <span m=''2942990''>in.</span> </p><p><span m=''2947735''>Now</span> <span m=''2948230''>there''s</span>
  <span m=''2948430''>a</span> <span m=''2948480''>bit</span> <span m=''2948610''>of</span>
  <span m=''2948710''>discipline</span> <span m=''2949210''>in</span> <span m=''2949360''>using</span>
  <span m=''2949670''>these</span> <span m=''2949850''>things</span> <span m=''2950100''>like</span>
  <span m=''2950320''>stacks</span> <span m=''2950900''>that</span> <span m=''2951280''>we</span>
  <span m=''2951430''>have</span> <span m=''2951520''>to</span> <span m=''2951600''>be</span>
  <span m=''2951700''>careful</span> <span m=''2952190''>of.</span> <span m=''2953620''>And</span>
  <span m=''2953740''>we''ll</span> <span m=''2953860''>see</span> <span m=''2954030''>that</span>
  <span m=''2954350''>in the</span> <span m=''2954620''>next</span> <span m=''2954890''>segment.</span>
  <span m=''2956260''>But</span> <span m=''2956410''>first</span> <span m=''2956640''>I</span>
  <span m=''2956670''>want</span> <span m=''2956800''>to</span> <span m=''2956840''>ask</span>
  <span m=''2957030''>if</span> <span m=''2957080''>there are</span> <span m=''2957230''>any</span>
  <span m=''2957340''>questions</span> <span m=''2958030''>for</span> <span m=''2958160''>this.</span>
  <span m=''2968560''>Are</span> <span m=''2968710''>there</span> <span m=''2968880''>any</span>
  <span m=''2969000''>questions?</span> <span m=''2970170''>Yes,</span> <span m=''2970350''>Ron.</span>
  </p><p><span m=''2970630''>AUDIENCE: What</span> <span m=''2971010''>happens</span>
  <span m=''2971390''>when</span> <span m=''2971670''>you</span> <span m=''2971950''>roll
  off</span> <span m=''2972140''>the end</span> <span m=''2972460''>of the</span>
  <span m=''2972780''>stack</span> <span m=''2973390''>with--</span> </p><p><span
  m=''2973640''>PROFESSOR: What</span> <span m=''2973800''>do you mean,</span> <span
  m=''2974130''>roll off</span> <span m=''2974580''>of?</span> </p><p><span m=''2975030''>AUDIENCE:
  Well, the</span> <span m=''2975140''>largest</span> <span m=''2975500''>number--</span>
  <span m=''2976090''>a</span> <span m=''2976180''>larger</span> <span m=''2976390''>starting</span>
  <span m=''2976680''>point</span> <span m=''2977020''>of</span> <span m=''2977160''>N</span>
  <span m=''2977440''>requires</span> <span m=''2977920''>more memory,</span> <span
  m=''2978320''>correct?</span> </p><p><span m=''2978860''>PROFESSOR: Oh,</span> <span
  m=''2979140''>yes.</span> <span m=''2979440''>Well,</span> <span m=''2979560''>I</span>
  <span m=''2979620''>need</span> <span m=''2979780''>to</span> <span m=''2979850''>have</span>
  <span m=''2979930''>a</span> <span m=''2980000''>long</span> <span m=''2980270''>enough</span>
  <span m=''2980660''>stack.</span> <span m=''2981530''>You</span> <span m=''2981630''>say,</span>
  <span m=''2981770''>what</span> <span m=''2981920''>if</span> <span m=''2982040''>I</span>
  <span m=''2982120''>violate</span> <span m=''2982610''>my</span> <span m=''2982730''>illusion?</span>
  </p><p><span m=''2983843''>AUDIENCE: Yes.</span> </p><p><span m=''2984550''>PROFESSOR:
  Well,</span> <span m=''2984920''>then the</span> <span m=''2985090''>magic doesn''t</span>
  <span m=''2985480''>work.</span> <span m=''2988210''>The</span> <span m=''2988290''>truth</span>
  <span m=''2988510''>of the</span> <span m=''2988770''>matter</span> <span m=''2989030''>is</span>
  <span m=''2989410''>that</span> <span m=''2989580''>every</span> <span m=''2989780''>machine</span>
  <span m=''2990100''>is</span> <span m=''2990280''>finite.</span> <span m=''2991640''>And</span>
  <span m=''2991910''>for</span> <span m=''2992450''>a</span> <span m=''2992580''>procedure</span>
  <span m=''2993100''>like</span> <span m=''2993380''>this,</span> <span m=''2994170''>there''s</span>
  <span m=''2994420''>a</span> <span m=''2994470''>limit</span> <span m=''2994760''>to</span>
  <span m=''2994850''>the</span> <span m=''2996190''>number</span> <span m=''2996480''>of</span>
  <span m=''2997420''>sub-factorials</span> <span m=''2998270''>I</span> <span m=''2998340''>could</span>
  <span m=''2998570''>have.</span> </p><p><span m=''2999950''>Remember</span> <span
  m=''3000380''>when we</span> <span m=''3000550''>were</span> <span m=''3000680''>doing</span>
  <span m=''3001010''>the</span> <span m=''3001060''>y-operator</span> <span m=''3001720''>a</span>
  <span m=''3001780''>while</span> <span m=''3002070''>ago,</span> <span m=''3002770''>we</span>
  <span m=''3002970''>pointed</span> <span m=''3003350''>out</span> <span m=''3003720''>that</span>
  <span m=''3003880''>there</span> <span m=''3003960''>was</span> <span m=''3004060''>a</span>
  <span m=''3004110''>sequence</span> <span m=''3004630''>of</span> <span m=''3004800''>exponentiation</span>
  <span m=''3005750''>procedures,</span> <span m=''3006290''>each</span> <span m=''3006460''>of</span>
  <span m=''3006510''>which</span> <span m=''3006660''>was</span> <span m=''3006760''>a</span>
  <span m=''3006810''>little</span> <span m=''3006980''>better</span> <span m=''3007150''>than</span>
  <span m=''3007300''>the</span> <span m=''3007390''>previous</span> <span m=''3007740''>one.</span>
  <span m=''3008350''>Well,</span> <span m=''3008710''>we''re</span> <span m=''3009000''>now</span>
  <span m=''3009220''>seeing</span> <span m=''3009450''>how</span> <span m=''3009600''>we</span>
  <span m=''3009700''>implement</span> <span m=''3010350''>that</span> <span m=''3010530''>mathematical</span>
  <span m=''3011160''>idea.</span> <span m=''3013090''>The</span> <span m=''3013200''>limiting</span>
  <span m=''3013590''>process</span> <span m=''3014360''>is</span> <span m=''3014510''>only</span>
  <span m=''3014730''>so</span> <span m=''3014940''>good</span> <span m=''3015130''>as
  as</span> <span m=''3015300''>far</span> <span m=''3015460''>as</span> <span m=''3015620''>you</span>
  <span m=''3015700''>take</span> <span m=''3015890''>the</span> <span m=''3015960''>limit.</span>
  </p><p><span m=''3017990''>If</span> <span m=''3018150''>you</span> <span m=''3018240''>think</span>
  <span m=''3018440''>about</span> <span m=''3018690''>it,</span> <span m=''3018820''>what
  am I</span> <span m=''3018950''>using</span> <span m=''3019240''>here?</span> <span
  m=''3019420''>I''m</span> <span m=''3019520''>using</span> <span m=''3019760''>about</span>
  <span m=''3020190''>two</span> <span m=''3021370''>pieces</span> <span m=''3022080''>of</span>
  <span m=''3022150''>memory</span> <span m=''3023020''>for</span> <span m=''3023240''>every</span>
  <span m=''3025910''>recursion</span> <span m=''3026260''>of</span> <span m=''3026340''>this</span>
  <span m=''3026530''>process.</span> <span m=''3029100''>If</span> <span m=''3029480''>we</span>
  <span m=''3029630''>try</span> <span m=''3029790''>to</span> <span m=''3029860''>compute</span>
  <span m=''3030220''>factorial</span> <span m=''3030760''>of</span> <span m=''3031070''>10,000,</span>
  <span m=''3031720''>that''s</span> <span m=''3031920''>not a</span> <span m=''3032070''>lot</span>
  <span m=''3032260''>of</span> <span m=''3032320''>memory.</span> <span m=''3033180''>On</span>
  <span m=''3033320''>the</span> <span m=''3033400''>other</span> <span m=''3033480''>hand,</span>
  <span m=''3033670''>it''s</span> <span m=''3033800''>an</span> <span m=''3033930''>awful</span>
  <span m=''3034050''>big</span> <span m=''3034250''>number.</span> </p><p><span m=''3036080''>So</span>
  <span m=''3036510''>the</span> <span m=''3036570''>question</span> <span m=''3036840''>is,</span>
  <span m=''3036920''>is</span> <span m=''3037030''>that</span> <span m=''3037200''>a</span>
  <span m=''3037230''>valuable</span> <span m=''3037630''>thing</span> <span m=''3037810''>in</span>
  <span m=''3037890''>this</span> <span m=''3038060''>case.</span> <span m=''3039180''>But</span>
  <span m=''3039300''>it</span> <span m=''3039350''>really</span> <span m=''3040850''>turns</span>
  <span m=''3041130''>out</span> <span m=''3041270''>not</span> <span m=''3041460''>to</span>
  <span m=''3041520''>be</span> <span m=''3041620''>a</span> <span m=''3041670''>terrible</span>
  <span m=''3042000''>limit,</span> <span m=''3042240''>because</span> <span m=''3042480''>memory
  is</span> <span m=''3042880''>el</span> <span m=''3043010''>cheapo,</span> <span
  m=''3044170''>and</span> <span m=''3044330''>people</span> <span m=''3044580''>are</span>
  <span m=''3044610''>pretty</span> <span m=''3044800''>expensive.</span> <span m=''3048130''>OK,</span>
  <span m=''3049230''>thank</span> <span m=''3049430''>you,</span> <span m=''3049510''>let''s</span>
  <span m=''3049660''>take</span> <span m=''3049790''>a</span> <span m=''3049830''>break.</span>
  </p><p><span m=''3051050''>[MUSIC PLAYING - "JESU, JOY OF MAN''S DESIRING" BY JOHANN
  SEBASTIAN BACH]</span> </p><p><span m=''3115176''>PROFESSOR:</span> <span m=''3115670''>Well,</span>
  <span m=''3116190''>let''s</span> <span m=''3116470''>see.</span> <span m=''3118351''>What</span>
  <span m=''3118850''>I''ve</span> <span m=''3118940''>shown</span> <span m=''3119140''>you</span>
  <span m=''3119320''>now</span> <span m=''3119620''>is</span> <span m=''3119720''>how</span>
  <span m=''3119870''>to</span> <span m=''3119950''>do</span> <span m=''3120110''>a</span>
  <span m=''3120170''>simple</span> <span m=''3122450''>iterative</span> <span m=''3122770''>process</span>
  <span m=''3123710''>and a</span> <span m=''3123910''>simple</span> <span m=''3124170''>recursive</span>
  <span m=''3124660''>process.</span> <span m=''3125640''>I</span> <span m=''3125790''>just</span>
  <span m=''3126010''>want</span> <span m=''3126150''>to</span> <span m=''3126200''>summarize</span>
  <span m=''3127040''>the</span> <span m=''3127180''>design</span> <span m=''3127590''>of</span>
  <span m=''3127710''>simple</span> <span m=''3128050''>machines</span> <span m=''3129630''>for</span>
  <span m=''3129760''>specific</span> <span m=''3130240''>applications</span> <span
  m=''3131270''>by</span> <span m=''3131390''>showing</span> <span m=''3131590''>you</span>
  <span m=''3131730''>a</span> <span m=''3131810''>little</span> <span m=''3132100''>bit</span>
  <span m=''3132250''>more</span> <span m=''3132470''>complicated</span> <span m=''3133020''>design,</span>
  <span m=''3133980''>that</span> <span m=''3134210''>of</span> <span m=''3134320''>a</span>
  <span m=''3135100''>thing</span> <span m=''3135290''>that</span> <span m=''3135370''>does</span>
  <span m=''3135570''>doubly</span> <span m=''3135870''>recursive</span> <span m=''3136290''>Fibonacci,</span>
  <span m=''3137290''>because</span> <span m=''3137640''>it</span> <span m=''3137700''>will</span>
  <span m=''3138150''>indicate</span> <span m=''3138670''>to</span> <span m=''3138760''>us,</span>
  <span m=''3138930''>and we''ll</span> <span m=''3139100''>understand,</span> <span
  m=''3140070''>a</span> <span m=''3140170''>bit</span> <span m=''3140380''>about</span>
  <span m=''3141340''>the</span> <span m=''3141410''>conventions</span> <span m=''3141990''>required</span>
  <span m=''3142650''>for</span> <span m=''3142870''>making</span> <span m=''3143150''>stacks</span>
  <span m=''3143610''>operate</span> <span m=''3144400''>correctly.</span> </p><p><span
  m=''3146400''>So</span> <span m=''3146650''>let''s</span> <span m=''3146940''>see.</span>
  <span m=''3147110''>I''m just</span> <span m=''3147150''>going to</span> <span m=''3147300''>write</span>
  <span m=''3147570''>down,</span> <span m=''3147810''>first</span> <span m=''3148030''>of
  all, the</span> <span m=''3148290''>program</span> <span m=''3148730''>I''m</span>
  <span m=''3148830''>going</span> <span m=''3148960''>to</span> <span m=''3149010''>translate.</span>
  <span m=''3154150''>I</span> <span m=''3154290''>need</span> <span m=''3154490''>a</span>
  <span m=''3155200''>Fibonacci</span> <span m=''3155720''>procedure,</span> <span
  m=''3159320''>it''s</span> <span m=''3159610''>very</span> <span m=''3159820''>simple,</span>
  <span m=''3160480''>which</span> <span m=''3160800''>says,</span> <span m=''3161190''>if</span>
  <span m=''3164670''>N</span> <span m=''3164840''>is</span> <span m=''3164990''>less</span>
  <span m=''3165300''>than</span> <span m=''3165750''>2,</span> <span m=''3166986''>the</span>
  <span m=''3167350''>result</span> <span m=''3167830''>is</span> <span m=''3168030''>N,</span>
  <span m=''3169290''>otherwise</span> <span m=''3170170''>it''s</span> <span m=''3170390''>the</span>
  <span m=''3170750''>sum</span> <span m=''3171640''>of</span> <span m=''3171890''>Fib</span>
  <span m=''3174080''>of</span> <span m=''3174270''>N</span> <span m=''3174450''>minus</span>
  <span m=''3174760''>1</span> <span m=''3178510''>and</span> <span m=''3178740''>Fib
  of</span> <span m=''3178990''>N</span> <span m=''3179150''>minus</span> <span m=''3179480''>2.</span>
  <span m=''3187240''>That''s</span> <span m=''3187480''>the</span> <span m=''3188230''>plan</span>
  <span m=''3188580''>I</span> <span m=''3188760''>have</span> <span m=''3188930''>here.</span>
  </p><p><span m=''3189290''>And</span> <span m=''3189410''>we''re</span> <span m=''3189520''>just</span>
  <span m=''3189640''>going</span> <span m=''3189730''>to</span> <span m=''3189810''>write</span>
  <span m=''3190110''>down</span> <span m=''3191070''>the</span> <span m=''3191180''>controller</span>
  <span m=''3191640''>for</span> <span m=''3191750''>such</span> <span m=''3191980''>a</span>
  <span m=''3192020''>machine.</span> <span m=''3193070''>We''re</span> <span m=''3193190''>going</span>
  <span m=''3193290''>to</span> <span m=''3193400''>assume</span> <span m=''3194080''>that</span>
  <span m=''3194250''>there</span> <span m=''3194460''>are</span> <span m=''3194560''>registers,</span>
  <span m=''3195290''>N,</span> <span m=''3195620''>which</span> <span m=''3196240''>holds</span>
  <span m=''3196620''>the</span> <span m=''3197580''>number we''re</span> <span m=''3197950''>taking</span>
  <span m=''3198210''>Fibonacci</span> <span m=''3198790''>of,</span> <span m=''3200020''>VAL,</span>
  <span m=''3200280''>which</span> <span m=''3200450''>is</span> <span m=''3200510''>where</span>
  <span m=''3200620''>the</span> <span m=''3200750''>answer</span> <span m=''3201060''>is</span>
  <span m=''3201150''>going</span> <span m=''3201260''>to</span> <span m=''3201300''>get</span>
  <span m=''3201480''>put,</span> <span m=''3202200''>and</span> <span m=''3202310''>continue,</span>
  <span m=''3203420''>which</span> <span m=''3203630''>is</span> <span m=''3203720''>the</span>
  <span m=''3203810''>thing</span> <span m=''3203990''>that''s</span> <span m=''3204180''>linked</span>
  <span m=''3204380''>to</span> <span m=''3204460''>the</span> <span m=''3204540''>controller,</span>
  <span m=''3205870''>like</span> <span m=''3206280''>before.</span> <span m=''3206810''>But</span>
  <span m=''3207030''>I''m</span> <span m=''3207210''>not</span> <span m=''3207370''>going</span>
  <span m=''3207470''>to</span> <span m=''3207510''>draw</span> <span m=''3207730''>another</span>
  <span m=''3208250''>physical</span> <span m=''3208650''>datapath,</span> <span m=''3211740''>because</span>
  <span m=''3211990''>it''s</span> <span m=''3212100''>pretty</span> <span m=''3212270''>much</span>
  <span m=''3212460''>the</span> <span m=''3212500''>same</span> <span m=''3212760''>as</span>
  <span m=''3212850''>the last</span> <span m=''3213140''>one</span> <span m=''3213230''>you''ve</span>
  <span m=''3213330''>seen.</span> </p><p><span m=''3214360''>And</span> <span m=''3214490''>of</span>
  <span m=''3214590''>course,</span> <span m=''3215330''>one</span> <span m=''3215500''>of</span>
  <span m=''3215560''>the</span> <span m=''3215660''>most</span> <span m=''3215950''>amazing</span>
  <span m=''3216490''>things</span> <span m=''3216810''>about</span> <span m=''3217070''>computation</span>
  <span m=''3218840''>is</span> <span m=''3219040''>that</span> <span m=''3219160''>after</span>
  <span m=''3219400''>a</span> <span m=''3219430''>while,</span> <span m=''3220070''>you</span>
  <span m=''3220170''>build</span> <span m=''3220380''>up a</span> <span m=''3220420''>little</span>
  <span m=''3220700''>more</span> <span m=''3220860''>features</span> <span m=''3221230''>and
  a few</span> <span m=''3221460''>more</span> <span m=''3221580''>features,</span>
  <span m=''3221950''>and all of the sudden,</span> <span m=''3222170''>you''ve</span>
  <span m=''3222320''>got</span> <span m=''3222450''>everything</span> <span m=''3222770''>you</span>
  <span m=''3222860''>need.</span> <span m=''3224860''>So</span> <span m=''3225130''>it''s</span>
  <span m=''3225910''>remarkable</span> <span m=''3226210''>that</span> <span m=''3226510''>it</span>
  <span m=''3226640''>just</span> <span m=''3226800''>gets</span> <span m=''3226990''>there</span>
  <span m=''3227130''>so</span> <span m=''3227280''>fast.</span> <span m=''3228170''>I</span>
  <span m=''3228290''>don''t</span> <span m=''3228390''>need</span> <span m=''3228600''>much</span>
  <span m=''3228810''>more</span> <span m=''3229000''>to</span> <span m=''3229080''>make</span>
  <span m=''3229790''>a</span> <span m=''3229840''>universal</span> <span m=''3230360''>computer.</span>
  </p><p><span m=''3231810''>But</span> <span m=''3232020''>in</span> <span m=''3232100''>any</span>
  <span m=''3232290''>case,</span> <span m=''3232620''>let''s</span> <span m=''3232730''>look</span>
  <span m=''3232880''>at</span> <span m=''3232930''>the</span> <span m=''3232980''>controller</span>
  <span m=''3233410''>for</span> <span m=''3233540''>the</span> <span m=''3233630''>Fibonacci</span>
  <span m=''3234200''>thing.</span> <span m=''3235060''>First</span> <span m=''3235320''>thing</span>
  <span m=''3235470''>I</span> <span m=''3235520''>want</span> <span m=''3235710''>to</span>
  <span m=''3235760''>do</span> <span m=''3236660''>is</span> <span m=''3237300''>start</span>
  <span m=''3237620''>the thing</span> <span m=''3237900''>up</span> <span m=''3238320''>by</span>
  <span m=''3238500''>assign</span> <span m=''3241680''>to</span> <span m=''3241770''>continue</span>
  <span m=''3247200''>a</span> <span m=''3247340''>place</span> <span m=''3247620''>called</span>
  <span m=''3247930''>done,</span> <span m=''3249340''>called</span> <span m=''3249480''>Fib-done</span>
  <span m=''3249880''>here.</span> <span m=''3253709''>So</span> <span m=''3254210''>that</span>
  <span m=''3254440''>means</span> <span m=''3254690''>that</span> <span m=''3254800''>somewhere</span>
  <span m=''3255210''>over</span> <span m=''3255390''>here,</span> <span m=''3255610''>I''m</span>
  <span m=''3255690''>going</span> <span m=''3255890''>to</span> <span m=''3256100''>have</span>
  <span m=''3256490''>a</span> <span m=''3256630''>label,</span> <span m=''3257520''>Fib-done,</span>
  <span m=''3259820''>which</span> <span m=''3260020''>is</span> <span m=''3260080''>the</span>
  <span m=''3260180''>place</span> <span m=''3260450''>where</span> <span m=''3260600''>I</span>
  <span m=''3260670''>go</span> <span m=''3261160''>when</span> <span m=''3261370''>I</span>
  <span m=''3261420''>want</span> <span m=''3261610''>the</span> <span m=''3261650''>machine</span>
  <span m=''3261920''>to</span> <span m=''3262420''>stop.</span> <span m=''3264120''>That''s
  what</span> <span m=''3264290''>that</span> <span m=''3264560''>is.</span> </p><p><span
  m=''3265395''>And</span> <span m=''3265880''>I''m going</span> <span m=''3266070''>to</span>
  <span m=''3266320''>make up</span> <span m=''3266410''>a</span> <span m=''3266470''>loop.</span>
  <span m=''3271110''>It''s</span> <span m=''3271360''>a</span> <span m=''3271410''>place</span>
  <span m=''3271690''>I''m</span> <span m=''3271780''>going</span> <span m=''3271940''>to</span>
  <span m=''3271990''>go</span> <span m=''3272230''>to</span> <span m=''3272660''>in</span>
  <span m=''3272810''>order</span> <span m=''3272960''>to</span> <span m=''3273000''>start</span>
  <span m=''3273330''>up</span> <span m=''3273490''>computing</span> <span m=''3273850''>a</span>
  <span m=''3273900''>Fib.</span> <span m=''3275470''>Whatever</span> <span m=''3275780''>is</span>
  <span m=''3275880''>in N</span> <span m=''3276170''>at</span> <span m=''3276270''>this</span>
  <span m=''3276470''>point,</span> <span m=''3277450''>Fibonacci</span> <span m=''3277950''>will</span>
  <span m=''3278090''>be</span> <span m=''3278210''>computed</span> <span m=''3278620''>of,</span>
  <span m=''3278850''>and</span> <span m=''3279240''>we will</span> <span m=''3279610''>return</span>
  <span m=''3280350''>to</span> <span m=''3280450''>the</span> <span m=''3280550''>place</span>
  <span m=''3280820''>specified</span> <span m=''3281320''>by</span> <span m=''3281430''>continue.</span>
  </p><p><span m=''3286070''>So</span> <span m=''3286280''>what</span> <span m=''3286450''>you''re</span>
  <span m=''3286560''>going</span> <span m=''3286640''>to</span> <span m=''3286720''>see</span>
  <span m=''3286960''>here</span> <span m=''3287570''>at</span> <span m=''3287800''>this</span>
  <span m=''3288030''>place,</span> <span m=''3288420''>what</span> <span m=''3288580''>I</span>
  <span m=''3288640''>want</span> <span m=''3288960''>here</span> <span m=''3289530''>is</span>
  <span m=''3289690''>the</span> <span m=''3289790''>contract</span> <span m=''3291070''>that</span>
  <span m=''3291390''>says,</span> <span m=''3292070''>I''m</span> <span m=''3292130''>going</span>
  <span m=''3292240''>to</span> <span m=''3292280''>write</span> <span m=''3292490''>this</span>
  <span m=''3292650''>with</span> <span m=''3292780''>a</span> <span m=''3292850''>comment</span>
  <span m=''3293620''>syntax,</span> <span m=''3294590''>the</span> <span m=''3294710''>contract</span>
  <span m=''3295320''>is</span> <span m=''3295980''>N</span> <span m=''3297010''>contains</span>
  <span m=''3299480''>arg,</span> <span m=''3300230''>the</span> <span m=''3300340''>argument.</span>
  <span m=''3302100''>Continue</span> <span m=''3307500''>is</span> <span m=''3308495''>the</span>
  <span m=''3308960''>recipient.</span> <span m=''3312812''>And</span> <span m=''3313260''>that''s</span>
  <span m=''3313660''>where</span> <span m=''3313860''>it</span> <span m=''3313920''>is.</span>
  <span m=''3317370''>At</span> <span m=''3317520''>this</span> <span m=''3317710''>point,</span>
  <span m=''3317930''>if I ever</span> <span m=''3318330''>go to this</span> <span
  m=''3318570''>place,</span> <span m=''3319280''>I''m</span> <span m=''3319520''>expecting</span>
  <span m=''3320140''>this</span> <span m=''3320430''>to</span> <span m=''3320500''>be</span>
  <span m=''3320640''>true,</span> <span m=''3321870''>the</span> <span m=''3322070''>argument
  for</span> <span m=''3322210''>computing</span> <span m=''3322570''>the</span> <span
  m=''3322640''>Fibonacci.</span> </p><p><span m=''3324820''>Now</span> <span m=''3324960''>the</span>
  <span m=''3325100''>next</span> <span m=''3325240''>thing</span> <span m=''3325320''>I</span>
  <span m=''3325390''>want</span> <span m=''3325600''>to</span> <span m=''3325660''>do</span>
  <span m=''3325930''>is</span> <span m=''3326090''>to</span> <span m=''3326180''>branch.</span>
  <span m=''3330220''>And</span> <span m=''3330680''>if</span> <span m=''3331070''>N</span>
  <span m=''3331270''>is</span> <span m=''3331370''>less</span> <span m=''3331600''>than</span>
  <span m=''3331800''>2--</span> <span m=''3334930''>by</span> <span m=''3335230''>the</span>
  <span m=''3335320''>way,</span> <span m=''3335420''>I''m</span> <span m=''3335590''>using</span>
  <span m=''3335890''>what</span> <span m=''3336020''>looks</span> <span m=''3336220''>like</span>
  <span m=''3336440''>Lisp</span> <span m=''3336670''>syntax.</span> <span m=''3338730''>This</span>
  <span m=''3338890''>is</span> <span m=''3339000''>not</span> <span m=''3339250''>Lisp.</span>
  <span m=''3341310''>This</span> <span m=''3341510''>does</span> <span m=''3341620''>not</span>
  <span m=''3341880''>run.</span> <span m=''3342750''>What</span> <span m=''3342880''>I''m</span>
  <span m=''3342990''>writing</span> <span m=''3343260''>here</span> <span m=''3343690''>does</span>
  <span m=''3343780''>not</span> <span m=''3344010''>run</span> <span m=''3344220''>as</span>
  <span m=''3344300''>a</span> <span m=''3344380''>simple</span> <span m=''3344640''>Lisp</span>
  <span m=''3344900''>program.</span> <span m=''3346120''>This</span> <span m=''3346310''>is</span>
  <span m=''3346450''>a</span> <span m=''3346560''>representation</span> <span m=''3348110''>of</span>
  <span m=''3348250''>another</span> <span m=''3348680''>language.</span> </p><p><span
  m=''3349710''>The</span> <span m=''3349860''>reason</span> <span m=''3350120''>I''m</span>
  <span m=''3350220''>using</span> <span m=''3350510''>the</span> <span m=''3350610''>syntax</span>
  <span m=''3351100''>of parentheses</span> <span m=''3351530''>and</span> <span m=''3351780''>so</span>
  <span m=''3352030''>on</span> <span m=''3352420''>is</span> <span m=''3352560''>because</span>
  <span m=''3352700''>I</span> <span m=''3352830''>tend</span> <span m=''3353150''>to</span>
  <span m=''3353490''>use</span> <span m=''3353790''>a</span> <span m=''3353880''>Lisp</span>
  <span m=''3354180''>system</span> <span m=''3355390''>to</span> <span m=''3355520''>write</span>
  <span m=''3355960''>an</span> <span m=''3356100''>interpreter</span> <span m=''3356720''>for</span>
  <span m=''3356910''>this</span> <span m=''3357820''>which</span> <span m=''3358000''>allows</span>
  <span m=''3358360''>me</span> <span m=''3358500''>to</span> <span m=''3358560''>simulate</span>
  <span m=''3359290''>the</span> <span m=''3359380''>machine</span> <span m=''3359710''>I''m</span>
  <span m=''3359820''>trying</span> <span m=''3360070''>to</span> <span m=''3360470''>build.</span>
  <span m=''3363380''>I</span> <span m=''3363530''>don''t</span> <span m=''3363700''>want</span>
  <span m=''3363840''>to</span> <span m=''3364060''>confuse</span> <span m=''3364520''>this</span>
  <span m=''3364720''>to</span> <span m=''3364810''>think</span> <span m=''3365050''>that</span>
  <span m=''3365170''>this</span> <span m=''3365370''>is</span> <span m=''3365540''>Lisp</span>
  <span m=''3365770''>code.</span> <span m=''3366940''>It''s</span> <span m=''3367100''>just
  I''m</span> <span m=''3367340''>using</span> <span m=''3367600''>a</span> <span
  m=''3367650''>lot</span> <span m=''3367870''>of the</span> <span m=''3367920''>pieces</span>
  <span m=''3368200''>of</span> <span m=''3368300''>Lisp.</span> <span m=''3369510''>I''m</span>
  <span m=''3369730''>embedding</span> <span m=''3370040''>a</span> <span m=''3370100''>language</span>
  <span m=''3370440''>in</span> <span m=''3370540''>Lisp,</span> <span m=''3371010''>using</span>
  <span m=''3371340''>Lisp</span> <span m=''3371620''>as</span> <span m=''3371850''>pieces</span>
  <span m=''3372770''>to</span> <span m=''3372880''>make</span> <span m=''3373090''>my</span>
  <span m=''3373230''>process</span> <span m=''3373600''>of</span> <span m=''3373670''>making</span>
  <span m=''3373950''>my</span> <span m=''3374090''>simulator</span> <span m=''3374560''>easy.</span>
  <span m=''3376620''>So</span> <span m=''3376720''>I''m</span> <span m=''3376810''>inheriting</span>
  <span m=''3377250''>from</span> <span m=''3377400''>Lisp</span> <span m=''3377590''>all</span>
  <span m=''3377790''>of its</span> <span m=''3377940''>properties.</span> </p><p><span
  m=''3378900''>Fetch</span> <span m=''3379360''>of</span> <span m=''3379470''>N</span>
  <span m=''3380960''>2,</span> <span m=''3381810''>I</span> <span m=''3381920''>want</span>
  <span m=''3382150''>to</span> <span m=''3382190''>go</span> <span m=''3382300''>to</span>
  <span m=''3382370''>a</span> <span m=''3382440''>place</span> <span m=''3382700''>called</span>
  <span m=''3382890''>immediate</span> <span m=''3383250''>answer.</span> <span m=''3385985''>It''s
  the</span> <span m=''3386440''>base</span> <span m=''3386790''>step.</span> <span
  m=''3393150''>Now,</span> <span m=''3393320''>that''s</span> <span m=''3393530''>somewhere</span>
  <span m=''3393910''>over</span> <span m=''3394110''>here,</span> <span m=''3395900''>just</span>
  <span m=''3396150''>above</span> <span m=''3396550''>done.</span> <span m=''3397750''>And</span>
  <span m=''3397840''>we''ll</span> <span m=''3397970''>see</span> <span m=''3398130''>it</span>
  <span m=''3398250''>later.</span> </p><p><span m=''3399330''>Now,</span> <span m=''3399820''>in</span>
  <span m=''3399960''>the</span> <span m=''3400050''>general</span> <span m=''3400440''>case,</span>
  <span m=''3400730''>which</span> <span m=''3400900''>is</span> <span m=''3400950''>the</span>
  <span m=''3401030''>part</span> <span m=''3401250''>I''m</span> <span m=''3401350''>going</span>
  <span m=''3401420''>to</span> <span m=''3401480''>write</span> <span m=''3401720''>down</span>
  <span m=''3401950''>now,</span> <span m=''3403230''>let''s</span> <span m=''3403460''>just</span>
  <span m=''3403640''>do</span> <span m=''3403810''>it.</span> <span m=''3404860''>Well,</span>
  <span m=''3405200''>first</span> <span m=''3405510''>of</span> <span m=''3405600''>all,</span>
  <span m=''3405800''>I''m</span> <span m=''3405930''>going</span> <span m=''3406030''>to</span>
  <span m=''3406080''>have</span> <span m=''3406230''>to</span> <span m=''3406370''>call</span>
  <span m=''3407050''>Fibonacci</span> <span m=''3407680''>twice.</span> <span m=''3409420''>In</span>
  <span m=''3409610''>each</span> <span m=''3409870''>case--</span> <span m=''3411300''>well,</span>
  <span m=''3411550''>in</span> <span m=''3411670''>one</span> <span m=''3411890''>case</span>
  <span m=''3412150''>at</span> <span m=''3412360''>least,</span> <span m=''3412760''>I''m</span>
  <span m=''3412950''>going</span> <span m=''3413100''>to</span> <span m=''3413140''>have</span>
  <span m=''3413270''>to</span> <span m=''3413370''>know</span> <span m=''3413510''>what</span>
  <span m=''3413640''>to</span> <span m=''3413710''>do</span> <span m=''3413900''>to</span>
  <span m=''3414000''>come</span> <span m=''3414160''>back</span> <span m=''3414420''>and</span>
  <span m=''3414550''>do</span> <span m=''3414660''>the</span> <span m=''3414770''>next</span>
  <span m=''3415040''>one.</span> <span m=''3416310''>I</span> <span m=''3417550''>have</span>
  <span m=''3417640''>to</span> <span m=''3417720''>remember,</span> <span m=''3419685''>have</span>
  <span m=''3419970''>I</span> <span m=''3420380''>done</span> <span m=''3420500''>the</span>
  <span m=''3420610''>first</span> <span m=''3420700''>Fib,</span> <span m=''3421130''>or
  have</span> <span m=''3421210''>I</span> <span m=''3421600''>done</span> <span m=''3421690''>the</span>
  <span m=''3421770''>second</span> <span m=''3422130''>one?</span> <span m=''3424500''>Do</span>
  <span m=''3424590''>I</span> <span m=''3424740''>have</span> <span m=''3424890''>to</span>
  <span m=''3424980''>come</span> <span m=''3425170''>back</span> <span m=''3425460''>to</span>
  <span m=''3425550''>the</span> <span m=''3425620''>place</span> <span m=''3425890''>where
  I</span> <span m=''3426090''>do</span> <span m=''3426230''>the</span> <span m=''3426290''>second</span>
  <span m=''3426630''>Fib,</span> <span m=''3427060''>or</span> <span m=''3427270''>do</span>
  <span m=''3427340''>I</span> <span m=''3427410''>have</span> <span m=''3427530''>to</span>
  <span m=''3427590''>come</span> <span m=''3427730''>back</span> <span m=''3427920''>to</span>
  <span m=''3427980''>the</span> <span m=''3428040''>place</span> <span m=''3428240''>where</span>
  <span m=''3428370''>I do</span> <span m=''3428500''>the</span> <span m=''3428680''>add?</span>
  </p><p><span m=''3432140''>In</span> <span m=''3432240''>the</span> <span m=''3432440''>first</span>
  <span m=''3432630''>case,</span> <span m=''3433330''>over</span> <span m=''3433660''>the</span>
  <span m=''3433890''>first</span> <span m=''3434120''>Fibonacci,</span> <span m=''3434620''>I''m
  going</span> <span m=''3434700''>to</span> <span m=''3434810''>need</span> <span
  m=''3435000''>the</span> <span m=''3435060''>value</span> <span m=''3435400''>of
  N</span> <span m=''3435740''>for</span> <span m=''3435870''>computing</span> <span
  m=''3436220''>for</span> <span m=''3436290''>the</span> <span m=''3436380''>second</span>
  <span m=''3436690''>one.</span> <span m=''3440010''>So I have</span> <span m=''3440480''>to
  store</span> <span m=''3440660''>some</span> <span m=''3440830''>of</span> <span
  m=''3440900''>these</span> <span m=''3441100''>things</span> <span m=''3441380''>up.</span>
  <span m=''3442996''>So</span> <span m=''3443420''>first</span> <span m=''3443670''>I''m</span>
  <span m=''3443750''>going</span> <span m=''3443840''>to</span> <span m=''3443960''>save</span>
  <span m=''3444290''>continue.</span> <span m=''3445820''>That''s</span> <span m=''3446290''>who</span>
  <span m=''3446520''>needs</span> <span m=''3446790''>the</span> <span m=''3446940''>answer.</span>
  <span m=''3451320''>And</span> <span m=''3451440''>the</span> <span m=''3451520''>reason</span>
  <span m=''3451820''>I''m</span> <span m=''3451940''>doing</span> <span m=''3452200''>that</span>
  <span m=''3452460''>is</span> <span m=''3452570''>because</span> <span m=''3452670''>I''m</span>
  <span m=''3452810''>about</span> <span m=''3453090''>to</span> <span m=''3453240''>assign</span>
  <span m=''3453560''>continue</span> <span m=''3461050''>to</span> <span m=''3461220''>the</span>
  <span m=''3461360''>place</span> <span m=''3461690''>which</span> <span m=''3461900''>is</span>
  <span m=''3462540''>the</span> <span m=''3462630''>place</span> <span m=''3462830''>I</span>
  <span m=''3462870''>want</span> <span m=''3463040''>to</span> <span m=''3463080''>go</span>
  <span m=''3463250''>to</span> <span m=''3463760''>after.</span> </p><p><span m=''3466870''>Let''s</span>
  <span m=''3467020''>call</span> <span m=''3467120''>it</span> <span m=''3467250''>Fib-N-minus-1,</span>
  <span m=''3470780''>big</span> <span m=''3471140''>long</span> <span m=''3471500''>name,</span>
  <span m=''3472510''>classic</span> <span m=''3472960''>Lisp</span> <span m=''3473240''>name.</span>
  <span m=''3477700''>Because</span> <span m=''3477910''>I''m</span> <span m=''3478000''>going</span>
  <span m=''3478090''>to</span> <span m=''3478140''>compute</span> <span m=''3478460''>the</span>
  <span m=''3478550''>first</span> <span m=''3478860''>Fib</span> <span m=''3479220''>of</span>
  <span m=''3479350''>N</span> <span m=''3479500''>minus</span> <span m=''3479810''>1,</span>
  <span m=''3480900''>and</span> <span m=''3480990''>then</span> <span m=''3481120''>after</span>
  <span m=''3481490''>that,</span> <span m=''3481670''>I</span> <span m=''3481730''>want</span>
  <span m=''3481950''>to</span> <span m=''3482000''>come</span> <span m=''3482140''>back</span>
  <span m=''3482360''>and</span> <span m=''3482440''>do</span> <span m=''3482540''>something</span>
  <span m=''3482890''>else.</span> <span m=''3483960''>That''s</span> <span m=''3484180''>the</span>
  <span m=''3484270''>place</span> <span m=''3484560''>I</span> <span m=''3484590''>want</span>
  <span m=''3484770''>to</span> <span m=''3484810''>go</span> <span m=''3484990''>to</span>
  <span m=''3485460''>after</span> <span m=''3485870''>I''ve</span> <span m=''3486070''>done</span>
  <span m=''3487690''>the</span> <span m=''3487870''>first</span> <span m=''3488050''>Fibonacci</span>
  <span m=''3488650''>calculation.</span> <span m=''3491106''>And</span> <span m=''3491560''>I</span>
  <span m=''3491720''>want</span> <span m=''3491920''>to</span> <span m=''3491960''>do</span>
  <span m=''3492100''>a</span> <span m=''3492300''>save of</span> <span m=''3492530''>N,</span>
  <span m=''3494430''>because</span> <span m=''3494590''>I''m</span> <span m=''3494690''>going
  to need it</span> <span m=''3495030''>later,</span> <span m=''3496560''>after</span>
  <span m=''3496840''>that.</span> </p><p><span m=''3499130''>Now</span> <span m=''3499380''>I''m</span>
  <span m=''3499450''>going</span> <span m=''3499660''>to,</span> <span m=''3499860''>at</span>
  <span m=''3499940''>this</span> <span m=''3500140''>point,</span> <span m=''3500630''>get</span>
  <span m=''3500990''>ready to</span> <span m=''3501180''>do</span> <span m=''3501340''>the</span>
  <span m=''3501480''>Fibonacci</span> <span m=''3501930''>of</span> <span m=''3502000''>N</span>
  <span m=''3502110''>minus</span> <span m=''3502370''>1.</span> <span m=''3503230''>So</span>
  <span m=''3503380''>assign</span> <span m=''3505966''>to</span> <span m=''3506450''>N</span>
  <span m=''3507930''>the</span> <span m=''3508060''>difference</span> <span m=''3508620''>of</span>
  <span m=''3508870''>the</span> <span m=''3508960''>fetch</span> <span m=''3509230''>of</span>
  <span m=''3509605''>N</span> <span m=''3513310''>and</span> <span m=''3513600''>1.</span>
  <span m=''3518110''>Now</span> <span m=''3518340''>I''m</span> <span m=''3518530''>ready</span>
  <span m=''3518780''>to</span> <span m=''3518850''>go</span> <span m=''3519030''>back</span>
  <span m=''3519320''>to</span> <span m=''3519440''>doing</span> <span m=''3519670''>the
  Fib</span> <span m=''3519940''>loop.</span> </p><p><span m=''3527630''>Have</span>
  <span m=''3528160''>I</span> <span m=''3528470''>satisfied</span> <span m=''3529070''>my</span>
  <span m=''3529200''>contract?</span> <span m=''3530195''>And</span> <span m=''3530460''>the</span>
  <span m=''3530570''>answer</span> <span m=''3530900''>is</span> <span m=''3531000''>yes.</span>
  <span m=''3531770''>N</span> <span m=''3532080''>contains</span> <span m=''3533510''>N</span>
  <span m=''3533650''>minus</span> <span m=''3533930''>1,</span> <span m=''3534200''>which</span>
  <span m=''3534340''>is</span> <span m=''3534410''>what</span> <span m=''3534530''>I</span>
  <span m=''3534590''>need.</span> <span m=''3537210''>Continue</span> <span m=''3537810''>contains</span>
  <span m=''3538250''>a</span> <span m=''3538310''>place</span> <span m=''3538640''>I</span>
  <span m=''3538690''>want</span> <span m=''3538850''>to</span> <span m=''3538890''>go</span>
  <span m=''3539090''>to</span> <span m=''3539260''>when</span> <span m=''3539390''>I''m</span>
  <span m=''3539510''>done</span> <span m=''3541370''>with</span> <span m=''3541540''>calculating</span>
  <span m=''3542140''>N</span> <span m=''3542410''>minus</span> <span m=''3542690''>1.</span>
  <span m=''3544100''>So</span> <span m=''3544250''>I''ve</span> <span m=''3544350''>satisfied</span>
  <span m=''3544840''>the</span> <span m=''3544950''>contract.</span> <span m=''3545440''>And</span>
  <span m=''3545520''>therefore,</span> <span m=''3545810''>I</span> <span m=''3545830''>can</span>
  <span m=''3545990''>write</span> <span m=''3546200''>down</span> <span m=''3546390''>here
  a</span> <span m=''3548270''>label,</span> <span m=''3551580''>after-Fib-N-minus-1.</span>
  </p><p><span m=''3560490''>Now</span> <span m=''3560620''>what</span> <span m=''3560800''>am
  I</span> <span m=''3560890''>going</span> <span m=''3561010''>to</span> <span m=''3561120''>do</span>
  <span m=''3561300''>here?</span> <span m=''3562690''>Here''s</span> <span m=''3562980''>a</span>
  <span m=''3563050''>place</span> <span m=''3563950''>where</span> <span m=''3564380''>I</span>
  <span m=''3564580''>now</span> <span m=''3564810''>have</span> <span m=''3564990''>to</span>
  <span m=''3565080''>get</span> <span m=''3565240''>ready to</span> <span m=''3565490''>do</span>
  <span m=''3565660''>Fib of</span> <span m=''3565960''>N</span> <span m=''3566080''>minus</span>
  <span m=''3566370''>2.</span> <span m=''3569270''>But</span> <span m=''3569460''>in</span>
  <span m=''3569540''>order</span> <span m=''3569760''>to</span> <span m=''3569820''>do</span>
  <span m=''3569990''>a Fib</span> <span m=''3570080''>of N</span> <span m=''3570250''>minus</span>
  <span m=''3570350''>2,</span> <span m=''3570660''>look,</span> <span m=''3570890''>I</span>
  <span m=''3571060''>don''t</span> <span m=''3571220''>know.</span> <span m=''3571780''>I''ve</span>
  <span m=''3571990''>clobbered</span> <span m=''3572430''>my</span> <span m=''3572600''>N</span>
  <span m=''3572800''>over</span> <span m=''3573010''>here.</span> <span m=''3573810''>And</span>
  <span m=''3574020''>presumably</span> <span m=''3574355''>my N</span> <span m=''3574690''>is</span>
  <span m=''3574940''>counted</span> <span m=''3575270''>down</span> <span m=''3575500''>all</span>
  <span m=''3575750''>the way to</span> <span m=''3575860''>1</span> <span m=''3576090''>or</span>
  <span m=''3576160''>0</span> <span m=''3576470''>or</span> <span m=''3576610''>something</span>
  <span m=''3577910''>at</span> <span m=''3578110''>this</span> <span m=''3578290''>point.</span>
  <span m=''3579780''>So</span> <span m=''3580420''>I</span> <span m=''3580500''>don''t</span>
  <span m=''3580580''>know</span> <span m=''3580650''>what</span> <span m=''3580790''>the</span>
  <span m=''3580890''>value</span> <span m=''3581160''>of</span> <span m=''3581240''>N</span>
  <span m=''3581410''>in</span> <span m=''3581490''>the</span> <span m=''3581630''>N</span>
  <span m=''3581760''>register</span> <span m=''3582270''>is.</span> </p><p><span
  m=''3583030''>I</span> <span m=''3583230''>want</span> <span m=''3583470''>the</span>
  <span m=''3583540''>value</span> <span m=''3583830''>of N</span> <span m=''3584040''>that</span>
  <span m=''3584110''>was</span> <span m=''3584230''>on</span> <span m=''3584360''>the</span>
  <span m=''3584430''>stack</span> <span m=''3584790''>that</span> <span m=''3584930''>I</span>
  <span m=''3585020''>saved</span> <span m=''3585450''>over</span> <span m=''3585640''>here</span>
  <span m=''3586070''>so</span> <span m=''3586520''>that</span> <span m=''3586610''>could</span>
  <span m=''3586770''>restore</span> <span m=''3587250''>it</span> <span m=''3587310''>over</span>
  <span m=''3587530''>here.</span> <span m=''3589520''>I</span> <span m=''3589650''>saved</span>
  <span m=''3589910''>up</span> <span m=''3590070''>the</span> <span m=''3590150''>value</span>
  <span m=''3590500''>of</span> <span m=''3590610''>N,</span> <span m=''3591110''>which</span>
  <span m=''3591390''>is</span> <span m=''3591510''>this</span> <span m=''3591740''>value</span>
  <span m=''3592140''>of</span> <span m=''3592510''>N</span> <span m=''3593690''>at</span>
  <span m=''3593880''>this</span> <span m=''3594090''>point,</span> <span m=''3594800''>so</span>
  <span m=''3595040''>that I</span> <span m=''3595150''>could</span> <span m=''3595290''>restore</span>
  <span m=''3595690''>it</span> <span m=''3595840''>after</span> <span m=''3595980''>computing</span>
  <span m=''3596220''>Fib of</span> <span m=''3596460''>N</span> <span m=''3596670''>minus</span>
  <span m=''3596930''>1,</span> <span m=''3597550''>so</span> <span m=''3597720''>that
  I</span> <span m=''3597810''>could</span> <span m=''3598040''>count</span> <span
  m=''3598270''>that</span> <span m=''3598450''>down</span> <span m=''3598680''>to</span>
  <span m=''3598760''>N</span> <span m=''3598870''>minus</span> <span m=''3599150''>2</span>
  <span m=''3599360''>and</span> <span m=''3599600''>then</span> <span m=''3599870''>compute</span>
  <span m=''3600140''>Fib of N</span> <span m=''3600250''>minus</span> <span m=''3600520''>2.</span>
  <span m=''3601810''>So</span> <span m=''3601970''>let''s</span> <span m=''3602080''>restore</span>
  <span m=''3602450''>that.</span> <span m=''3608830''>Restore</span> <span m=''3609260''>of</span>
  <span m=''3609340''>N.</span> </p><p><span m=''3611130''>Now</span> <span m=''3612040''>I''m</span>
  <span m=''3612190''>about</span> <span m=''3612510''>to</span> <span m=''3612570''>do</span>
  <span m=''3612720''>something</span> <span m=''3613340''>which</span> <span m=''3613870''>is</span>
  <span m=''3615310''>superstitious,</span> <span m=''3615980''>and</span> <span m=''3616120''>we</span>
  <span m=''3616200''>will</span> <span m=''3616410''>remove</span> <span m=''3616750''>it</span>
  <span m=''3616850''>shortly.</span> <span m=''3618520''>I am</span> <span m=''3618760''>about</span>
  <span m=''3619100''>to</span> <span m=''3619380''>finish</span> <span m=''3619820''>the</span>
  <span m=''3619950''>sequence</span> <span m=''3620560''>of</span> <span m=''3621230''>doing</span>
  <span m=''3621540''>the</span> <span m=''3622390''>subroutine</span> <span m=''3622650''>call,</span>
  <span m=''3623080''>if</span> <span m=''3623180''>you</span> <span m=''3623280''>will.</span>
  <span m=''3624800''>I''m</span> <span m=''3624960''>going</span> <span m=''3625140''>to</span>
  <span m=''3625190''>say,</span> <span m=''3625600''>well,</span> <span m=''3626020''>I</span>
  <span m=''3626160''>also</span> <span m=''3626570''>saved</span> <span m=''3626820''>up</span>
  <span m=''3627020''>the</span> <span m=''3627100''>continuation,</span> <span m=''3628510''>since</span>
  <span m=''3629400''>I''m</span> <span m=''3629520''>going</span> <span m=''3629650''>to</span>
  <span m=''3629690''>restore</span> <span m=''3630090''>it</span> <span m=''3630160''>now.</span>
  </p><p><span m=''3631600''>But</span> <span m=''3631710''>actually,</span> <span
  m=''3632040''>I</span> <span m=''3632100''>don''t</span> <span m=''3632270''>have</span>
  <span m=''3632490''>to,</span> <span m=''3632590''>because</span> <span m=''3632750''>I''m</span>
  <span m=''3632810''>not</span> <span m=''3632970''>going</span> <span m=''3633080''>to</span>
  <span m=''3633120''>need</span> <span m=''3633390''>it.</span> <span m=''3634610''>We''ll</span>
  <span m=''3634730''>fix</span> <span m=''3634950''>that</span> <span m=''3635090''>in
  a</span> <span m=''3635220''>second.</span> <span m=''3636260''>So</span> <span
  m=''3636390''>we''ll</span> <span m=''3636470''>do</span> <span m=''3636560''>a</span>
  <span m=''3636700''>restore</span> <span m=''3636955''>of</span> <span m=''3637210''>continue,</span>
  <span m=''3646110''>which</span> <span m=''3646280''>is</span> <span m=''3646350''>what</span>
  <span m=''3646500''>I</span> <span m=''3646590''>would</span> <span m=''3646740''>in</span>
  <span m=''3646870''>general</span> <span m=''3647230''>need</span> <span m=''3647430''>to</span>
  <span m=''3647510''>do.</span> <span m=''3648020''>And</span> <span m=''3648100''>we''re
  just</span> <span m=''3648320''>going</span> <span m=''3648430''>to</span> <span
  m=''3648480''>see</span> <span m=''3648660''>what</span> <span m=''3649500''>you</span>
  <span m=''3649620''>would</span> <span m=''3649710''>call</span> <span m=''3649970''>in
  the</span> <span m=''3650240''>compiler</span> <span m=''3650670''>world</span>
  <span m=''3650910''>a</span> <span m=''3651120''>peephole</span> <span m=''3651330''>optimization,</span>
  <span m=''3652220''>which</span> <span m=''3652400''>says,</span> <span m=''3652540''>whoops,</span>
  <span m=''3652740''>you</span> <span m=''3652870''>didn''t</span> <span m=''3652990''>have</span>
  <span m=''3653140''>to</span> <span m=''3653220''>do</span> <span m=''3653360''>that.</span>
  </p><p><span m=''3655420''>OK,</span> <span m=''3655710''>so</span> <span m=''3655850''>the</span>
  <span m=''3655970''>next</span> <span m=''3656190''>thing</span> <span m=''3656360''>I</span>
  <span m=''3656480''>see</span> <span m=''3656720''>here</span> <span m=''3658440''>is</span>
  <span m=''3659090''>that I</span> <span m=''3659250''>have</span> <span m=''3659450''>to</span>
  <span m=''3659530''>get</span> <span m=''3659720''>ready</span> <span m=''3660010''>now</span>
  <span m=''3660240''>to</span> <span m=''3660380''>do</span> <span m=''3660820''>Fibonacci</span>
  <span m=''3661370''>of</span> <span m=''3661440''>N</span> <span m=''3661580''>minus</span>
  <span m=''3661900''>2.</span> <span m=''3662770''>But</span> <span m=''3662980''>I</span>
  <span m=''3663050''>don''t</span> <span m=''3663220''>have</span> <span m=''3663310''>to</span>
  <span m=''3663400''>save</span> <span m=''3663880''>N</span> <span m=''3664150''>anymore.</span>
  <span m=''3665050''>The</span> <span m=''3665130''>reason</span> <span m=''3665410''>why</span>
  <span m=''3665540''>I</span> <span m=''3665590''>don''t</span> <span m=''3665690''>have</span>
  <span m=''3665780''>to</span> <span m=''3665860''>save</span> <span m=''3666060''>N</span>
  <span m=''3666220''>anymore</span> <span m=''3666580''>is</span> <span m=''3666940''>because</span>
  <span m=''3667070''>I</span> <span m=''3667140''>don''t</span> <span m=''3667310''>need</span>
  <span m=''3667560''>N</span> <span m=''3667850''>after</span> <span m=''3668200''>I''ve</span>
  <span m=''3668250''>done</span> <span m=''3668530''>Fib of</span> <span m=''3668730''>N</span>
  <span m=''3668840''>minus</span> <span m=''3669110''>2,</span> <span m=''3669340''>because</span>
  <span m=''3669500''>the</span> <span m=''3669690''>next</span> <span m=''3669860''>thing</span>
  <span m=''3670000''>I</span> <span m=''3670060''>do</span> <span m=''3670230''>is</span>
  <span m=''3670630''>add.</span> <span m=''3673540''>So</span> <span m=''3674160''>I''m</span>
  <span m=''3674230''>just</span> <span m=''3674370''>going</span> <span m=''3674460''>to</span>
  <span m=''3674500''>set</span> <span m=''3674680''>up</span> <span m=''3674770''>my</span>
  <span m=''3674930''>N</span> <span m=''3675190''>that</span> <span m=''3675390''>way.</span>
  <span m=''3676500''>Assign</span> <span m=''3679720''>N</span> <span m=''3680980''>minus</span>
  <span m=''3682490''>difference</span> <span m=''3683020''>of</span> <span m=''3683390''>fetch</span>
  <span m=''3686880''>N</span> <span m=''3688200''>and</span> <span m=''3688620''>2.</span>
  </p><p><span m=''3691850''>Now</span> <span m=''3692030''>I</span> <span m=''3692160''>have</span>
  <span m=''3692280''>to</span> <span m=''3692860''>finish</span> <span m=''3693185''>the</span>
  <span m=''3693510''>setup</span> <span m=''3694190''>for</span> <span m=''3695070''>calling</span>
  <span m=''3695440''>Fibonacci</span> <span m=''3695960''>of</span> <span m=''3696060''>N</span>
  <span m=''3696160''>minus</span> <span m=''3696450''>2.</span> <span m=''3696950''>Well,</span>
  <span m=''3697170''>I</span> <span m=''3697340''>have to save up</span> <span m=''3697730''>continue</span>
  <span m=''3704090''>and</span> <span m=''3704390''>assign</span> <span m=''3704810''>continue,</span>
  <span m=''3708330''>continue,</span> <span m=''3711962''>to</span> <span m=''3712460''>the</span>
  <span m=''3712580''>place</span> <span m=''3712940''>which</span> <span m=''3713140''>is</span>
  <span m=''3713450''>after</span> <span m=''3716814''>Fib</span> <span m=''3718690''>N</span>
  <span m=''3719350''>2,</span> <span m=''3722580''>that</span> <span m=''3722710''>place</span>
  <span m=''3723050''>over</span> <span m=''3723240''>here</span> <span m=''3723400''>somewhere.</span>
  <span m=''3725320''>However,</span> <span m=''3726070''>I''ve</span> <span m=''3726190''>got</span>
  <span m=''3726320''>to</span> <span m=''3726360''>be</span> <span m=''3726460''>very</span>
  <span m=''3726690''>careful.</span> <span m=''3728650''>The</span> <span m=''3728890''>old</span>
  <span m=''3729170''>value,</span> <span m=''3729570''>the</span> <span m=''3729680''>value</span>
  <span m=''3730160''>of</span> <span m=''3730300''>Fib of</span> <span m=''3730490''>N</span>
  <span m=''3730680''>minus</span> <span m=''3731020''>1,</span> <span m=''3732100''>I''m</span>
  <span m=''3732250''>going</span> <span m=''3732430''>to</span> <span m=''3732470''>need</span>
  <span m=''3732740''>later.</span> </p><p><span m=''3735300''>The</span> <span m=''3735410''>value</span>
  <span m=''3735810''>of</span> <span m=''3735890''>Fibonacci</span> <span m=''3736400''>of</span>
  <span m=''3736460''>N</span> <span m=''3736610''>minus</span> <span m=''3736920''>1,</span>
  <span m=''3737580''>I''m</span> <span m=''3737770''>going</span> <span m=''3737920''>to</span>
  <span m=''3737970''>need.</span> <span m=''3738480''>And</span> <span m=''3738880''>I</span>
  <span m=''3738990''>can''t</span> <span m=''3739280''>clobber</span> <span m=''3739575''>it,</span>
  <span m=''3741020''>because</span> <span m=''3741490''>I''m</span> <span m=''3741570''>going</span>
  <span m=''3741620''>to</span> <span m=''3741660''>have</span> <span m=''3741790''>to</span>
  <span m=''3741880''>add</span> <span m=''3742100''>it to</span> <span m=''3742180''>the</span>
  <span m=''3742260''>value</span> <span m=''3742640''>of</span> <span m=''3742830''>Fib
  of N</span> <span m=''3742980''>minus</span> <span m=''3743250''>2.</span> <span
  m=''3744150''>That''s</span> <span m=''3744360''>in</span> <span m=''3744440''>the</span>
  <span m=''3744510''>value</span> <span m=''3744870''>register,</span> <span m=''3745220''>so</span>
  <span m=''3745310''>I''m</span> <span m=''3745380''>going</span> <span m=''3745460''>to</span>
  <span m=''3745500''>save</span> <span m=''3745780''>it.</span> <span m=''3747720''>So</span>
  <span m=''3747870''>I</span> <span m=''3747940''>have</span> <span m=''3748010''>to</span>
  <span m=''3748090''>save</span> <span m=''3748310''>this</span> <span m=''3748500''>right</span>
  <span m=''3748740''>now,</span> <span m=''3751630''>save</span> <span m=''3751890''>up</span>
  <span m=''3751990''>VAL.</span> <span m=''3753780''>And</span> <span m=''3753950''>now</span>
  <span m=''3754150''>I can</span> <span m=''3754380''>go</span> <span m=''3754550''>off</span>
  <span m=''3754710''>to</span> <span m=''3754840''>my</span> <span m=''3755120''>subroutine,</span>
  <span m=''3756700''>go</span> <span m=''3756880''>to</span> <span m=''3758620''>Fib</span>
  <span m=''3759080''>loop.</span> </p><p><span m=''3764220''>Now</span> <span m=''3764400''>before</span>
  <span m=''3765610''>I</span> <span m=''3765720''>go</span> <span m=''3765940''>any</span>
  <span m=''3766080''>further</span> <span m=''3766820''>and</span> <span m=''3768490''>finish</span>
  <span m=''3768780''>this</span> <span m=''3769000''>program,</span> <span m=''3769400''>I</span>
  <span m=''3769460''>just</span> <span m=''3769590''>want</span> <span m=''3769700''>to</span>
  <span m=''3769740''>look</span> <span m=''3769920''>at</span> <span m=''3769990''>this</span>
  <span m=''3770150''>segment</span> <span m=''3770550''>so</span> <span m=''3770690''>far</span>
  <span m=''3771270''>and</span> <span m=''3771490''>see,</span> <span m=''3772180''>oh</span>
  <span m=''3772340''>yes,</span> <span m=''3773250''>there''s</span> <span m=''3773490''>a</span>
  <span m=''3773540''>sequence</span> <span m=''3774020''>of</span> <span m=''3774110''>instructions</span>
  <span m=''3774770''>here,</span> <span m=''3775090''>if</span> <span m=''3775370''>you</span>
  <span m=''3775520''>will,</span> <span m=''3777508''>that</span> <span m=''3777920''>I</span>
  <span m=''3778030''>can</span> <span m=''3778190''>do</span> <span m=''3778320''>something</span>
  <span m=''3778680''>about.</span> <span m=''3781580''>Here</span> <span m=''3781830''>I</span>
  <span m=''3781870''>have</span> <span m=''3782010''>a</span> <span m=''3782140''>restore
  of</span> <span m=''3782640''>continue,</span> <span m=''3784280''>a</span> <span
  m=''3784340''>save of</span> <span m=''3784770''>continue,</span> <span m=''3786010''>and</span>
  <span m=''3786360''>then an</span> <span m=''3786450''>assign</span> <span m=''3786750''>of</span>
  <span m=''3786860''>continue,</span> <span m=''3788700''>with</span> <span m=''3788840''>no</span>
  <span m=''3789040''>other</span> <span m=''3789200''>references</span> <span m=''3789620''>to</span>
  <span m=''3789710''>continue</span> <span m=''3790090''>in</span> <span m=''3790170''>between.</span>
  <span m=''3793840''>The</span> <span m=''3793960''>restore</span> <span m=''3794440''>followed</span>
  <span m=''3794850''>by</span> <span m=''3794960''>the</span> <span m=''3795060''>save</span>
  <span m=''3795520''>leaves</span> <span m=''3795760''>the</span> <span m=''3795800''>stack</span>
  <span m=''3796110''>unchanged.</span> </p><p><span m=''3799090''>The</span> <span
  m=''3799230''>only</span> <span m=''3799370''>difference</span> <span m=''3799740''>is</span>
  <span m=''3799940''>that I</span> <span m=''3800100''>set</span> <span m=''3800320''>the</span>
  <span m=''3800380''>continue</span> <span m=''3800700''>register</span> <span m=''3801080''>to</span>
  <span m=''3801200''>a</span> <span m=''3801250''>value,</span> <span m=''3801880''>which</span>
  <span m=''3802140''>is</span> <span m=''3802210''>the</span> <span m=''3802260''>value</span>
  <span m=''3802620''>that was</span> <span m=''3802710''>on</span> <span m=''3802830''>the</span>
  <span m=''3802880''>stack.</span> <span m=''3804330''>Since</span> <span m=''3804480''>I</span>
  <span m=''3804560''>now</span> <span m=''3804790''>clobber</span> <span m=''3805150''>that</span>
  <span m=''3805350''>value,</span> <span m=''3806430''>as</span> <span m=''3806670''>in</span>
  <span m=''3806880''>it</span> <span m=''3807030''>was</span> <span m=''3807170''>never</span>
  <span m=''3807360''>referenced,</span> <span m=''3808640''>these</span> <span m=''3808870''>instructions</span>
  <span m=''3809370''>are</span> <span m=''3809480''>unnecessary.</span> <span m=''3811710''>So</span>
  <span m=''3813734''>we</span> <span m=''3814162''>will</span> <span m=''3814590''>remove</span>
  <span m=''3814990''>these.</span> </p><p><span m=''3818550''>But</span> <span m=''3819010''>I</span>
  <span m=''3819250''>couldn''t</span> <span m=''3819400''>have</span> <span m=''3819550''>seen
  that</span> <span m=''3819810''>unless</span> <span m=''3820100''>I had</span> <span
  m=''3820210''>written them</span> <span m=''3820530''>down.</span> <span m=''3823780''>Was</span>
  <span m=''3823920''>that</span> <span m=''3824110''>really</span> <span m=''3824350''>true?</span>
  <span m=''3825590''>Well,</span> <span m=''3825950''>I</span> <span m=''3826070''>don''t</span>
  <span m=''3826230''>know.</span> </p><p><span m=''3828610''>OK,</span> <span m=''3828970''>so</span>
  <span m=''3830260''>we''ve</span> <span m=''3830560''>now</span> <span m=''3830740''>gone</span>
  <span m=''3830950''>off</span> <span m=''3831130''>to</span> <span m=''3831230''>compute</span>
  <span m=''3831560''>Fibonacci</span> <span m=''3832010''>of</span> <span m=''3832080''>N</span>
  <span m=''3832200''>minus</span> <span m=''3832520''>2.</span> <span m=''3833660''>So</span>
  <span m=''3833820''>after</span> <span m=''3834230''>that,</span> <span m=''3842440''>what</span>
  <span m=''3842920''>are we</span> <span m=''3843220''>going</span> <span m=''3843440''>to</span>
  <span m=''3843520''>do?</span> <span m=''3845070''>Well,</span> <span m=''3845210''>I</span>
  <span m=''3845280''>suppose</span> <span m=''3845620''>the</span> <span m=''3845700''>first</span>
  <span m=''3845960''>thing</span> <span m=''3846100''>we</span> <span m=''3846190''>have</span>
  <span m=''3846350''>to</span> <span m=''3846440''>do--</span> <span m=''3847010''>we''ve</span>
  <span m=''3847180''>got</span> <span m=''3847420''>two</span> <span m=''3847580''>things.</span>
  <span m=''3847960''>We''ve</span> <span m=''3848140''>got</span> <span m=''3848270''>a</span>
  <span m=''3848310''>thing</span> <span m=''3848540''>in</span> <span m=''3848630''>the</span>
  <span m=''3848720''>value</span> <span m=''3849080''>register</span> <span m=''3849460''>which</span>
  <span m=''3849620''>is</span> <span m=''3849720''>now</span> <span m=''3849930''>valuable.</span>
  <span m=''3850920''>We</span> <span m=''3851040''>also</span> <span m=''3851150''>have
  a thing</span> <span m=''3851520''>on</span> <span m=''3851630''>the</span> <span
  m=''3851690''>stack</span> <span m=''3852050''>that</span> <span m=''3852100''>can</span>
  <span m=''3852190''>be</span> <span m=''3852290''>restored</span> <span m=''3852610''>into</span>
  <span m=''3852730''>the</span> <span m=''3852840''>value</span> <span m=''3853160''>register.</span>
  <span m=''3854815''>And what</span> <span m=''3855210''>I</span> <span m=''3855320''>have</span>
  <span m=''3855480''>to</span> <span m=''3855570''>be</span> <span m=''3855700''>careful</span>
  <span m=''3856050''>with</span> <span m=''3856230''>now</span> <span m=''3856900''>is</span>
  <span m=''3857010''>I</span> <span m=''3857070''>want</span> <span m=''3857260''>to</span>
  <span m=''3857300''>shuffle</span> <span m=''3857630''>this</span> <span m=''3857800''>right</span>
  <span m=''3858060''>so</span> <span m=''3858120''>I</span> <span m=''3858190''>can</span>
  <span m=''3858290''>do the</span> <span m=''3858430''>multiply.</span> </p><p><span
  m=''3859470''>Now</span> <span m=''3859620''>there</span> <span m=''3859730''>are</span>
  <span m=''3859750''>various</span> <span m=''3860060''>conventions</span> <span
  m=''3860590''>I</span> <span m=''3860690''>might</span> <span m=''3860910''>use,</span>
  <span m=''3861430''>but</span> <span m=''3861600''>I''m</span> <span m=''3861700''>going</span>
  <span m=''3861790''>to</span> <span m=''3861830''>be</span> <span m=''3861970''>very</span>
  <span m=''3863050''>picky</span> <span m=''3863400''>and</span> <span m=''3863560''>say,</span>
  <span m=''3863710''>I''m only</span> <span m=''3863910''>going</span> <span m=''3864000''>to</span>
  <span m=''3864080''>restore</span> <span m=''3864510''>into a</span> <span m=''3864590''>register</span>
  <span m=''3865000''>I''ve</span> <span m=''3865330''>saved</span> <span m=''3865510''>from.</span>
  <span m=''3866740''>If</span> <span m=''3866940''>that''s</span> <span m=''3867150''>the</span>
  <span m=''3867210''>case,</span> <span m=''3867400''>I</span> <span m=''3867540''>have
  to do</span> <span m=''3867670''>a</span> <span m=''3867710''>shuffle</span> <span
  m=''3868060''>here.</span> <span m=''3870020''>It''s</span> <span m=''3870280''>the</span>
  <span m=''3870430''>same</span> <span m=''3870620''>problem</span> <span m=''3870890''>with</span>
  <span m=''3870990''>how</span> <span m=''3871120''>many</span> <span m=''3871260''>hands</span>
  <span m=''3871580''>I</span> <span m=''3871810''>have.</span> <span m=''3872620''>So</span>
  <span m=''3872860''>I''m</span> <span m=''3872950''>going to</span> <span m=''3873040''>assign</span>
  <span m=''3876085''>to</span> <span m=''3876580''>N,</span> <span m=''3877090''>because</span>
  <span m=''3877270''>I''m</span> <span m=''3877360''>not</span> <span m=''3877480''>going
  to</span> <span m=''3877600''>need N</span> <span m=''3877800''>anymore,</span>
  <span m=''3878600''>N</span> <span m=''3878760''>is</span> <span m=''3878840''>useless,</span>
  <span m=''3879810''>the</span> <span m=''3880110''>current</span> <span m=''3880370''>value</span>
  <span m=''3880690''>of</span> <span m=''3880830''>VAL,</span> <span m=''3885220''>which</span>
  <span m=''3885440''>was</span> <span m=''3885640''>the</span> <span m=''3885680''>value</span>
  <span m=''3886140''>of</span> <span m=''3886420''>Fib of</span> <span m=''3886650''>N
  minus</span> <span m=''3886940''>2.</span> </p><p><span m=''3892950''>And</span>
  <span m=''3893510''>I''m</span> <span m=''3893720''>going</span> <span m=''3893990''>to</span>
  <span m=''3894690''>restore</span> <span m=''3895100''>the</span> <span m=''3895180''>value</span>
  <span m=''3895510''>register</span> <span m=''3895890''>now.</span> <span m=''3901850''>This</span>
  <span m=''3902060''>restore</span> <span m=''3902860''>matches</span> <span m=''3903330''>this</span>
  <span m=''3903450''>save.</span> <span m=''3905690''>And</span> <span m=''3905800''>if</span>
  <span m=''3905880''>you''re</span> <span m=''3906010''>very</span> <span m=''3906290''>careful</span>
  <span m=''3906590''>and</span> <span m=''3906890''>examine</span> <span m=''3907320''>very</span>
  <span m=''3907510''>carefully</span> <span m=''3907850''>what</span> <span m=''3907990''>goes</span>
  <span m=''3908230''>on,</span> <span m=''3909820''>restores</span> <span m=''3910190''>and</span>
  <span m=''3910310''>saves</span> <span m=''3910930''>are</span> <span m=''3911070''>always</span>
  <span m=''3911410''>matched.</span> <span m=''3913840''>Now</span> <span m=''3913980''>there''s</span>
  <span m=''3914140''>an</span> <span m=''3914230''>outstanding</span> <span m=''3914720''>save,</span>
  <span m=''3915060''>of</span> <span m=''3915160''>course,</span> <span m=''3915460''>that
  we</span> <span m=''3915520''>have</span> <span m=''3915660''>to</span> <span m=''3915840''>get
  rid</span> <span m=''3915980''>of</span> <span m=''3916080''>soon.</span> </p><p><span
  m=''3919000''>And</span> <span m=''3919150''>so</span> <span m=''3919300''>I</span>
  <span m=''3919370''>restored</span> <span m=''3919680''>the</span> <span m=''3919800''>value</span>
  <span m=''3920120''>register.</span> <span m=''3920590''>Now</span> <span m=''3921070''>I</span>
  <span m=''3921200''>restore</span> <span m=''3921560''>the</span> <span m=''3921650''>continue</span>
  <span m=''3922060''>one,</span> <span m=''3930850''>which</span> <span m=''3931410''>matches</span>
  <span m=''3931800''>this</span> <span m=''3932000''>one,</span> <span m=''3934850''>dot,</span>
  <span m=''3935070''>dot, dot,</span> <span m=''3935560''>dot,</span> <span m=''3935830''>dot,</span>
  <span m=''3936226''>dot, dot,</span> <span m=''3937020''>down</span> <span m=''3937280''>to</span>
  <span m=''3937370''>here,</span> <span m=''3940830''>restoring</span> <span m=''3941300''>that</span>
  <span m=''3941500''>continuation.</span> <span m=''3942860''>That</span> <span m=''3943080''>continuation</span>
  <span m=''3943960''>is</span> <span m=''3944160''>a</span> <span m=''3944200''>continuation</span>
  <span m=''3944940''>of</span> <span m=''3945190''>Fib of</span> <span m=''3945270''>N,</span>
  <span m=''3946600''>which</span> <span m=''3946790''>is the</span> <span m=''3946870''>problem</span>
  <span m=''3947220''>I</span> <span m=''3947290''>was</span> <span m=''3947380''>trying</span>
  <span m=''3947490''>to</span> <span m=''3947600''>solve,</span> <span m=''3947940''>a</span>
  <span m=''3948020''>major</span> <span m=''3948330''>problem</span> <span m=''3948620''>I''m</span>
  <span m=''3948730''>trying</span> <span m=''3948860''>to</span> <span m=''3948990''>solve.</span>
  <span m=''3949665''>So</span> <span m=''3950080''>that''s</span> <span m=''3950220''>the</span>
  <span m=''3950360''>guy</span> <span m=''3950570''>I have</span> <span m=''3950700''>to</span>
  <span m=''3950770''>go</span> <span m=''3950870''>back</span> <span m=''3951170''>to</span>
  <span m=''3951330''>who</span> <span m=''3951820''>wants Fib of</span> <span m=''3952250''>N.</span>
  <span m=''3952530''>I</span> <span m=''3952670''>saved</span> <span m=''3952960''>them</span>
  <span m=''3953150''>all</span> <span m=''3953270''>the</span> <span m=''3953390''>way</span>
  <span m=''3953530''>up</span> <span m=''3953690''>here</span> <span m=''3954120''>when</span>
  <span m=''3954310''>I</span> <span m=''3954370''>realized</span> <span m=''3955060''>N</span>
  <span m=''3955300''>was</span> <span m=''3955470''>not</span> <span m=''3955750''>less</span>
  <span m=''3956000''>than</span> <span m=''3956190''>2.</span> <span m=''3957360''>And
  so</span> <span m=''3957550''>I</span> <span m=''3957700''>had to do</span> <span
  m=''3957900''>a</span> <span m=''3957960''>complicated</span> <span m=''3958420''>operation.</span>
  </p><p><span m=''3960840''>Now</span> <span m=''3961050''>I''ve</span> <span m=''3961220''>got</span>
  <span m=''3961380''>everything</span> <span m=''3961740''>I</span> <span m=''3961820''>need</span>
  <span m=''3962060''>to</span> <span m=''3962130''>do</span> <span m=''3962360''>it.</span>
  <span m=''3963240''>So</span> <span m=''3963470''>I''m</span> <span m=''3963550''>going</span>
  <span m=''3963630''>to</span> <span m=''3963670''>restore</span> <span m=''3964020''>that,</span>
  <span m=''3965630''>assign</span> <span m=''3969360''>to</span> <span m=''3969460''>VAL</span>
  <span m=''3972600''>the</span> <span m=''3972920''>sum</span> <span m=''3974110''>of</span>
  <span m=''3974470''>fetch</span> <span m=''3977470''>VAL</span> <span m=''3979490''>and</span>
  <span m=''3979840''>fetch</span> <span m=''3980510''>of</span> <span m=''3980630''>N,</span>
  <span m=''3987520''>and</span> <span m=''3987800''>go</span> <span m=''3987940''>to</span>
  <span m=''3988040''>continue.</span> <span m=''3998260''>So</span> <span m=''3998430''>now</span>
  <span m=''3998610''>I''ve</span> <span m=''3998780''>returned</span> <span m=''4002810''>from</span>
  <span m=''4002980''>computing</span> <span m=''4003330''>Fibonacci</span> <span
  m=''4004230''>of</span> <span m=''4004380''>N,</span> <span m=''4005660''>the</span>
  <span m=''4005750''>general</span> <span m=''4006110''>case.</span> <span m=''4007110''>Now</span>
  <span m=''4007290''>what''s</span> <span m=''4007460''>left</span> <span m=''4007680''>is</span>
  <span m=''4007760''>we have</span> <span m=''4008150''>to</span> <span m=''4008350''>fix</span>
  <span m=''4008620''>up</span> <span m=''4008770''>a</span> <span m=''4008840''>few</span>
  <span m=''4010070''>details,</span> <span m=''4011030''>like</span> <span m=''4011230''>there''s</span>
  <span m=''4011480''>the</span> <span m=''4011560''>base</span> <span m=''4011860''>case</span>
  <span m=''4013290''>of</span> <span m=''4013770''>this</span> <span m=''4013920''>induction,</span>
  <span m=''4014660''>immediate</span> <span m=''4015040''>answer,</span> <span m=''4023750''>which</span>
  <span m=''4024050''>is</span> <span m=''4025890''>nothing</span> <span m=''4026150''>more</span>
  <span m=''4026440''>than</span> <span m=''4026750''>assign</span> <span m=''4028230''>to</span>
  <span m=''4028670''>VAL</span> <span m=''4030740''>fetch</span> <span m=''4031220''>of</span>
  <span m=''4031650''>N,</span> <span m=''4033710''>because</span> <span m=''4034140''>N</span>
  <span m=''4034360''>was</span> <span m=''4034750''>less</span> <span m=''4035010''>than</span>
  <span m=''4035250''>2,</span> <span m=''4035500''>and</span> <span m=''4035610''>therefore,</span>
  <span m=''4035930''>the</span> <span m=''4036060''>answer</span> <span m=''4036420''>is</span>
  <span m=''4036520''>N</span> <span m=''4036860''>in</span> <span m=''4037120''>our</span>
  <span m=''4037310''>original</span> <span m=''4037620''>program,</span> <span m=''4039270''>and</span>
  <span m=''4039830''>return</span> <span m=''4045800''>continue--</span> <span m=''4051460''>bobble,</span>
  <span m=''4051910''>bobble</span> <span m=''4053510''>almost--</span> <span m=''4054800''>and</span>
  <span m=''4055250''>finally</span> <span m=''4055525''>Fib</span> <span m=''4055800''>done.</span>
  </p><p><span m=''4063460''>So</span> <span m=''4063630''>that''s</span> <span m=''4064030''>a</span>
  <span m=''4064200''>fairly</span> <span m=''4064590''>complicated</span> <span m=''4065170''>program.</span>
  <span m=''4065640''>And</span> <span m=''4065830''>the</span> <span m=''4065990''>reason</span>
  <span m=''4066280''>I</span> <span m=''4066330''>wanted</span> <span m=''4066560''>you</span>
  <span m=''4066760''>see</span> <span m=''4067010''>to that is</span> <span m=''4067500''>because</span>
  <span m=''4067670''>I</span> <span m=''4067720''>want</span> <span m=''4067950''>you</span>
  <span m=''4068060''>to see</span> <span m=''4068520''>the</span> <span m=''4068640''>particular</span>
  <span m=''4069490''>flavors</span> <span m=''4069950''>of</span> <span m=''4070120''>stack</span>
  <span m=''4070500''>discipline</span> <span m=''4071740''>that</span> <span m=''4071930''>I</span>
  <span m=''4072030''>was</span> <span m=''4072140''>obeying.</span> <span m=''4072965''>It</span>
  <span m=''4073290''>was</span> <span m=''4073530''>first</span> <span m=''4073780''>of</span>
  <span m=''4073840''>all,</span> <span m=''4073980''>I</span> <span m=''4074030''>don''t</span>
  <span m=''4074140''>want</span> <span m=''4074250''>to</span> <span m=''4074300''>take</span>
  <span m=''4074540''>anything</span> <span m=''4076565''>that</span> <span m=''4077050''>I''m</span>
  <span m=''4077240''>not</span> <span m=''4077410''>going</span> <span m=''4077510''>to</span>
  <span m=''4077550''>need</span> <span m=''4077740''>later.</span> <span m=''4080395''>I
  was</span> <span m=''4080830''>being</span> <span m=''4081120''>very</span> <span
  m=''4081420''>careful.</span> <span m=''4081850''>And</span> <span m=''4081960''>it''s</span>
  <span m=''4082110''>very</span> <span m=''4082420''>important.</span> <span m=''4083940''>And</span>
  <span m=''4084080''>there are</span> <span m=''4084250''>all</span> <span m=''4084460''>sorts</span>
  <span m=''4084750''>of</span> <span m=''4085270''>other</span> <span m=''4085540''>disciplines</span>
  <span m=''4085990''>people</span> <span m=''4086250''>make</span> <span m=''4087095''>with</span>
  <span m=''4087570''>frames</span> <span m=''4088090''>and</span> <span m=''4088210''>things</span>
  <span m=''4088470''>like</span> <span m=''4088730''>that</span> <span m=''4088940''>of</span>
  <span m=''4089030''>some</span> <span m=''4089220''>sort,</span> <span m=''4090270''>where
  you</span> <span m=''4090520''>save</span> <span m=''4090760''>all</span> <span
  m=''4090910''>sorts of</span> <span m=''4091150''>junk</span> <span m=''4091430''>you''re
  not</span> <span m=''4091710''>going to need</span> <span m=''4091960''>later</span>
  <span m=''4092220''>and</span> <span m=''4092280''>restore it</span> <span m=''4092650''>because,</span>
  <span m=''4092920''>in</span> <span m=''4093040''>some</span> <span m=''4093410''>sense,</span>
  <span m=''4093780''>it''s</span> <span m=''4094040''>easier</span> <span m=''4094570''>to</span>
  <span m=''4094680''>do</span> <span m=''4094860''>that.</span> <span m=''4095830''>That''s</span>
  <span m=''4096010''>going</span> <span m=''4096090''>to</span> <span m=''4096170''>lead
  to</span> <span m=''4096370''>various</span> <span m=''4096670''>disasters,</span>
  <span m=''4098840''>which</span> <span m=''4098990''>we''ll</span> <span m=''4099109''>see</span>
  <span m=''4099640''>a</span> <span m=''4099710''>little</span> <span m=''4099899''>later.</span>
  </p><p><span m=''4101740''>It''s</span> <span m=''4101899''>crucial</span> <span
  m=''4102439''>to</span> <span m=''4102540''>say</span> <span m=''4102859''>exactly</span>
  <span m=''4103359''>what</span> <span m=''4103450''>you''re</span> <span m=''4103560''>going</span>
  <span m=''4103630''>to</span> <span m=''4103700''>need</span> <span m=''4103899''>later.</span>
  <span m=''4106899''>It''s</span> <span m=''4107020''>an</span> <span m=''4107120''>important</span>
  <span m=''4107560''>idea.</span> <span m=''4109859''>And</span> <span m=''4110050''>the</span>
  <span m=''4110140''>responsibility</span> <span m=''4110990''>of</span> <span m=''4111060''>that</span>
  <span m=''4111890''>is</span> <span m=''4112090''>whoever</span> <span m=''4112410''>saves</span>
  <span m=''4112689''>something</span> <span m=''4113819''>is</span> <span m=''4114020''>the
  guy</span> <span m=''4114120''>who</span> <span m=''4114229''>restores it,</span>
  <span m=''4114689''>because</span> <span m=''4114760''>he</span> <span m=''4115025''>needs</span>
  <span m=''4115290''>it.</span> <span m=''4116930''>And</span> <span m=''4117240''>in</span>
  <span m=''4117660''>such</span> <span m=''4117880''>discipline,</span> <span m=''4118970''>you</span>
  <span m=''4119140''>can</span> <span m=''4119300''>see</span> <span m=''4119540''>what</span>
  <span m=''4119770''>things</span> <span m=''4120020''>are</span> <span m=''4120130''>unnecessary,</span>
  <span m=''4123540''>operations</span> <span m=''4124060''>that</span> <span m=''4124270''>are</span>
  <span m=''4124330''>unimportant.</span> </p><p><span m=''4126940''>Now,</span> <span
  m=''4127359''>one</span> <span m=''4127529''>other</span> <span m=''4127700''>thing</span>
  <span m=''4127859''>I</span> <span m=''4127899''>want</span> <span m=''4128100''>to</span>
  <span m=''4128160''>tell</span> <span m=''4128300''>you</span> <span m=''4128450''>about</span>
  <span m=''4129630''>that''s</span> <span m=''4129750''>very</span> <span m=''4129950''>simple</span>
  <span m=''4131689''>is</span> <span m=''4131910''>that,</span> <span m=''4132240''>of</span>
  <span m=''4132350''>course,</span> <span m=''4132800''>the</span> <span m=''4132899''>picture</span>
  <span m=''4133200''>you</span> <span m=''4133439''>see</span> <span m=''4133779''>is</span>
  <span m=''4133880''>not</span> <span m=''4134060''>the</span> <span m=''4134120''>whole</span>
  <span m=''4134310''>picture.</span> <span m=''4135350''>Supposing</span> <span m=''4135810''>I</span>
  <span m=''4135990''>had</span> <span m=''4136180''>systems</span> <span m=''4136830''>that</span>
  <span m=''4136960''>had</span> <span m=''4137220''>things</span> <span m=''4137810''>like</span>
  <span m=''4138140''>other</span> <span m=''4138430''>operations,</span> <span m=''4138960''>CAR,</span>
  <span m=''4140029''>CDR,</span> <span m=''4140930''>cons,</span> <span m=''4143710''>building</span>
  <span m=''4144950''>a</span> <span m=''4145060''>vector</span> <span m=''4145930''>and</span>
  <span m=''4146080''>referencing</span> <span m=''4146355''>the</span> <span m=''4146630''>nth</span>
  <span m=''4146800''>element</span> <span m=''4147130''>of</span> <span m=''4147506''>it,</span>
  <span m=''4148260''>or</span> <span m=''4148370''>things</span> <span m=''4148630''>like</span>
  <span m=''4148850''>that.</span> <span m=''4150000''>Well,</span> <span m=''4150970''>at</span>
  <span m=''4151149''>this</span> <span m=''4151319''>level</span> <span m=''4151580''>of</span>
  <span m=''4151670''>detail,</span> <span m=''4152890''>whatever</span> <span m=''4153229''>it</span>
  <span m=''4153279''>is,</span> <span m=''4153939''>we</span> <span m=''4154120''>can</span>
  <span m=''4154229''>conceptualize</span> <span m=''4154579''>those</span> <span
  m=''4154930''>as</span> <span m=''4155229''>primitive</span> <span m=''4155520''>operations</span>
  <span m=''4157069''>in</span> <span m=''4157260''>the</span> <span m=''4157350''>datapath.</span>
  <span m=''4158299''>In</span> <span m=''4158659''>other words,</span> <span m=''4159020''>we</span>
  <span m=''4159160''>could</span> <span m=''4159319''>say</span> <span m=''4159950''>that</span>
  <span m=''4160100''>some</span> <span m=''4160290''>machine</span> <span m=''4160740''>that,</span>
  <span m=''4160830''>for</span> <span m=''4161020''>example,</span> <span m=''4161520''>has</span>
  <span m=''4163060''>the</span> <span m=''4163200''>append</span> <span m=''4163600''>machine,</span>
  <span m=''4164229''>which</span> <span m=''4164399''>has</span> <span m=''4164569''>to
  do</span> <span m=''4164740''>cons</span> <span m=''4165460''>of</span> <span m=''4165609''>the</span>
  <span m=''4165689''>CAR</span> <span m=''4165979''>of</span> <span m=''4166069''>x</span>
  <span m=''4166700''>with</span> <span m=''4166899''>the</span> <span m=''4167210''>append</span>
  <span m=''4167560''>of</span> <span m=''4167689''>the</span> <span m=''4167800''>CDR</span>
  <span m=''4168200''>of</span> <span m=''4168880''>x</span> <span m=''4169140''>and</span>
  <span m=''4169370''>y,</span> <span m=''4169870''>well,</span> <span m=''4170060''>gee,</span>
  <span m=''4170189''>that''s</span> <span m=''4170399''>exactly</span> <span m=''4170790''>the</span>
  <span m=''4170830''>same</span> <span m=''4171050''>as</span> <span m=''4171149''>the</span>
  <span m=''4171830''>factorial</span> <span m=''4172569''>structure.</span> <span
  m=''4173630''>Well, it''s</span> <span m=''4174100''>got about</span> <span m=''4174430''>the</span>
  <span m=''4174510''>same</span> <span m=''4174800''>structure.</span> </p><p><span
  m=''4176133''>And</span> <span m=''4176540''>what do</span> <span m=''4176819''>we</span>
  <span m=''4176950''>have?</span> <span m=''4177270''>We</span> <span m=''4177359''>have</span>
  <span m=''4177580''>some</span> <span m=''4177740''>sort</span> <span m=''4177920''>of</span>
  <span m=''4178010''>things</span> <span m=''4178950''>in</span> <span m=''4179130''>it</span>
  <span m=''4179779''>which</span> <span m=''4179950''>may</span> <span m=''4180130''>be</span>
  <span m=''4180680''>registers,</span> <span m=''4181189''>x</span> <span m=''4181590''>and</span>
  <span m=''4181880''>y,</span> <span m=''4182510''>and</span> <span m=''4182640''>then</span>
  <span m=''4182819''>x</span> <span m=''4183060''>has to</span> <span m=''4183300''>somehow</span>
  <span m=''4183740''>move</span> <span m=''4184010''>to</span> <span m=''4184130''>y</span>
  <span m=''4184479''>sometimes,</span> <span m=''4185370''>x</span> <span m=''4185490''>has</span>
  <span m=''4185600''>to</span> <span m=''4185670''>get</span> <span m=''4185779''>the</span>
  <span m=''4185850''>value of</span> <span m=''4186220''>y.</span> <span m=''4186939''>And</span>
  <span m=''4187010''>then</span> <span m=''4187109''>we</span> <span m=''4187210''>may</span>
  <span m=''4187359''>have</span> <span m=''4187510''>to be</span> <span m=''4187600''>able
  to do</span> <span m=''4188000''>something</span> <span m=''4188550''>which</span>
  <span m=''4188810''>is</span> <span m=''4188950''>a</span> <span m=''4189390''>cons.</span>
  <span m=''4191700''>I</span> <span m=''4191830''>don''t</span> <span m=''4191939''>remember</span>
  <span m=''4192319''>if</span> <span m=''4192430''>I</span> <span m=''4192490''>need</span>
  <span m=''4192720''>to</span> <span m=''4192850''>like</span> <span m=''4193080''>this</span>
  <span m=''4193279''>is</span> <span m=''4196140''>in</span> <span m=''4196310''>this</span>
  <span m=''4197370''>system,</span> <span m=''4197760''>but</span> <span m=''4197970''>cons</span>
  <span m=''4198340''>is</span> <span m=''4198690''>sort</span> <span m=''4198880''>of</span>
  <span m=''4198980''>like</span> <span m=''4199390''>subtract</span> <span m=''4200080''>or</span>
  <span m=''4200210''>add</span> <span m=''4200490''>or</span> <span m=''4200590''>something.</span>
  <span m=''4201420''>It</span> <span m=''4201540''>combines</span> <span m=''4202120''>two</span>
  <span m=''4202290''>things,</span> <span m=''4202710''>producing</span> <span m=''4203180''>a</span>
  <span m=''4203230''>thing</span> <span m=''4203410''>which</span> <span m=''4203570''>is</span>
  <span m=''4203680''>the</span> <span m=''4203800''>cons,</span> <span m=''4204520''>which</span>
  <span m=''4204730''>we</span> <span m=''4204870''>may</span> <span m=''4205100''>then</span>
  <span m=''4205370''>think</span> <span m=''4205590''>goes</span> <span m=''4205840''>into</span>
  <span m=''4206070''>there.</span> <span m=''4207600''>And</span> <span m=''4207800''>then</span>
  <span m=''4207930''>maybe</span> <span m=''4208240''>a</span> <span m=''4208300''>thing</span>
  <span m=''4208580''>called</span> <span m=''4209140''>the</span> <span m=''4209260''>CAR,</span>
  <span m=''4213010''>which</span> <span m=''4213320''>will</span> <span m=''4213570''>produce--</span>
  <span m=''4214920''>I</span> <span m=''4215010''>can</span> <span m=''4215170''>get</span>
  <span m=''4215320''>the</span> <span m=''4215390''>CAR</span> <span m=''4215720''>or</span>
  <span m=''4215780''>something.</span> <span m=''4216920''>And</span> <span m=''4217070''>maybe</span>
  <span m=''4217170''>I can</span> <span m=''4217440''>get</span> <span m=''4217590''>the</span>
  <span m=''4217660''>CDR</span> <span m=''4218040''>of</span> <span m=''4218120''>something,</span>
  <span m=''4218860''>and</span> <span m=''4219020''>so</span> <span m=''4219270''>on.</span>
  </p><p><span m=''4220150''>But</span> <span m=''4220310''>we</span> <span m=''4220410''>shouldn''t</span>
  <span m=''4220610''>be</span> <span m=''4220720''>too</span> <span m=''4220850''>afraid</span>
  <span m=''4221180''>of</span> <span m=''4221280''>saying</span> <span m=''4221590''>things</span>
  <span m=''4221810''>this</span> <span m=''4222000''>way,</span> <span m=''4222730''>because</span>
  <span m=''4223110''>the</span> <span m=''4223190''>worst</span> <span m=''4223540''>that</span>
  <span m=''4223650''>could</span> <span m=''4223770''>happen</span> <span m=''4224270''>is</span>
  <span m=''4224765''>if</span> <span m=''4225260''>we</span> <span m=''4225440''>open</span>
  <span m=''4225740''>up</span> <span m=''4225890''>cons,</span> <span m=''4227330''>what</span>
  <span m=''4227480''>we''re</span> <span m=''4227590''>going</span> <span m=''4227710''>to</span>
  <span m=''4227770''>find</span> <span m=''4228645''>is</span> <span m=''4229030''>some</span>
  <span m=''4229300''>machine.</span> <span m=''4231770''>And</span> <span m=''4232030''>cons</span>
  <span m=''4232280''>may</span> <span m=''4232410''>in</span> <span m=''4232500''>fact</span>
  <span m=''4232740''>overlap</span> <span m=''4232800''>with</span> <span m=''4232990''>CAR</span>
  <span m=''4233180''>and</span> <span m=''4233540''>CDR,</span> <span m=''4233660''>and
  it</span> <span m=''4233750''>always</span> <span m=''4234040''>does,</span> <span
  m=''4235336''>in</span> <span m=''4235750''>the</span> <span m=''4235810''>same</span>
  <span m=''4236070''>way</span> <span m=''4236200''>that</span> <span m=''4236650''>plus
  and</span> <span m=''4237040''>minus</span> <span m=''4237540''>overlap,</span>
  <span m=''4238660''>and</span> <span m=''4238810''>really</span> <span m=''4239050''>the</span>
  <span m=''4239140''>same</span> <span m=''4239390''>business.</span> <span m=''4241210''>Cons,</span>
  <span m=''4241540''>CAR,</span> <span m=''4241800''>and CDR</span> <span m=''4242060''>are
  going</span> <span m=''4242140''>to</span> <span m=''4242240''>overlap,</span> <span
  m=''4242640''>and</span> <span m=''4242700''>we''re</span> <span m=''4242830''>going</span>
  <span m=''4242910''>to</span> <span m=''4242950''>find</span> <span m=''4243490''>a</span>
  <span m=''4243590''>little</span> <span m=''4243810''>controller,</span> <span m=''4245570''>a</span>
  <span m=''4245640''>little</span> <span m=''4245870''>datapath,</span> <span m=''4248120''>which</span>
  <span m=''4248430''>may</span> <span m=''4248630''>have</span> <span m=''4248720''>some</span>
  <span m=''4248810''>registers</span> <span m=''4249320''>in</span> <span m=''4249440''>it,</span>
  <span m=''4249730''>some</span> <span m=''4251820''>stuff</span> <span m=''4252120''>like</span>
  <span m=''4252370''>that.</span> <span m=''4253300''>And</span> <span m=''4253510''>maybe</span>
  <span m=''4253820''>inside</span> <span m=''4254320''>it,</span> <span m=''4254450''>there</span>
  <span m=''4254700''>may</span> <span m=''4254870''>also</span> <span m=''4255180''>be</span>
  <span m=''4255340''>an</span> <span m=''4255640''>infinite</span> <span m=''4255820''>part,</span>
  <span m=''4256570''>a</span> <span m=''4256650''>part</span> <span m=''4256920''>that''s</span>
  <span m=''4257340''>semi-infinite</span> <span m=''4257900''>or</span> <span m=''4258250''>something,</span>
  <span m=''4258810''>which</span> <span m=''4259020''>is</span> <span m=''4259080''>a</span>
  <span m=''4259150''>lot</span> <span m=''4259360''>of</span> <span m=''4259440''>very</span>
  <span m=''4259610''>uniform</span> <span m=''4259935''>stuff,</span> <span m=''4260870''>which
  we''ll</span> <span m=''4261260''>call</span> <span m=''4261570''>memory.</span>
  </p><p><span m=''4266570''>And</span> <span m=''4266850''>I</span> <span m=''4266890''>wouldn''t</span>
  <span m=''4267110''>be</span> <span m=''4267210''>so</span> <span m=''4267380''>horrified</span>
  <span m=''4267670''>if</span> <span m=''4267960''>that were the</span> <span m=''4268100''>way</span>
  <span m=''4268390''>it</span> <span m=''4268470''>works.</span> <span m=''4269330''>In</span>
  <span m=''4269460''>fact,</span> <span m=''4269750''>it</span> <span m=''4269810''>does,</span>
  <span m=''4270100''>and</span> <span m=''4270260''>we''ll talk</span> <span m=''4270480''>about</span>
  <span m=''4270680''>that</span> <span m=''4270850''>later.</span> <span m=''4273320''>So</span>
  <span m=''4273520''>are</span> <span m=''4273640''>there</span> <span m=''4273780''>any</span>
  <span m=''4273880''>questions?</span> </p><p><span m=''4284340''>Gee,</span> <span
  m=''4284510''>what</span> <span m=''4284710''>an</span> <span m=''4284900''>unquestioning</span>
  <span m=''4285390''>audience.</span> <span m=''4288670''>Suppose</span> <span m=''4288790''>I</span>
  <span m=''4288920''>tell</span> <span m=''4289070''>you</span> <span m=''4289140''>a</span>
  <span m=''4289170''>horrible</span> <span m=''4289510''>pile</span> <span m=''4289760''>of</span>
  <span m=''4289850''>lies.</span> <span m=''4299690''>OK.</span> <span m=''4301990''>Well,</span>
  <span m=''4302160''>thank</span> <span m=''4302400''>you.</span> <span m=''4302520''>Let''s</span>
  <span m=''4302710''>take</span> <span m=''4302890''>our</span> <span m=''4302970''>break.</span>
  </p><p><span m=''4304230''>[MUSIC PLAYING - "JESU, JOY OF MAN''S DESIRING" BY JOHANN
  SEBASTIAN BACH]</span> </p>'
type: course
uid: 0abf802ec53fd91aa9766c2311428220

---
None