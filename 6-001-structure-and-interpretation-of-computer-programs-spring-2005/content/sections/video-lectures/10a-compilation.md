---
about_this_resource_text: <p><b>Topics covered:&nbsp;</b>Compilation</p> <p><b> Instructors:</b>
  Hal Abelson and Gerald Jay Sussman</p> <p>Subtitles for this course are provided
  through the generous assistance of Henry Baker, Hoofar Pourzand, Heather Wood, Aleksejs
  Truhans, Steven Edwards, George Menhorn, and Mahendra Kumar.</p>
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
embedded_media:
- id: 10A.jpg
  parent_uid: d2102ce55255210d335802fb34d064dd
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/10a-compilation/10A.jpg
  title: 10A.jpg
  type: null
  uid: 8f35b47496ec1a93e158ed1fbc8170f1
- id: Video-YouTube-Stream
  media_location: TqO6V3qR9Ws
  parent_uid: d2102ce55255210d335802fb34d064dd
  title: Video-YouTube-Stream
  type: Video
  uid: 6d2bc1e33bc3d11eff7b09e593020f99
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT_Structure_of_Computer_Programs_1986/lec10a.mp4
  parent_uid: d2102ce55255210d335802fb34d064dd
  title: Video-Internet Archive-MP4
  type: Video
  uid: 767e93bc089029c9f73069c976aa0112
- id: Thumbnail-OCW-JPG
  parent_uid: d2102ce55255210d335802fb34d064dd
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 9e5d5aa388439718398573b1a8aae4af
- id: 3Play-3PlayYouTubeid-MP4
  media_location: TqO6V3qR9Ws
  parent_uid: d2102ce55255210d335802fb34d064dd
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 37f31f990c8c569dd2f339a466090052
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/TqO6V3qR9Ws/default.jpg
  parent_uid: d2102ce55255210d335802fb34d064dd
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 8ebfbf22c85b8087e6de8569cd6a93ea
- id: TqO6V3qR9Ws.srt
  parent_uid: d2102ce55255210d335802fb34d064dd
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/10a-compilation/TqO6V3qR9Ws.srt
  title: 3play caption file
  type: null
  uid: 337fce99a0197528bf25137480ca4c5b
- id: TqO6V3qR9Ws.pdf
  parent_uid: d2102ce55255210d335802fb34d064dd
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/10a-compilation/TqO6V3qR9Ws.pdf
  title: 3play pdf file
  type: null
  uid: 9dfa296596372438318a4315c5a53a0e
- id: Caption-3Play YouTube id-SRT
  parent_uid: d2102ce55255210d335802fb34d064dd
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 36a19205c9ef06fbc57725dba77d7234
- id: Transcript-3Play YouTube id-PDF
  parent_uid: d2102ce55255210d335802fb34d064dd
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 7f90ae5e4b7c962e3c346b5ca637841e
inline_embed_id: 2109382610a:compilation97461763
layout: video
order_index: null
parent_uid: 4fcacad2c29981dd668a6b29822403cc
related_resources_text: ''
short_url: 10a-compilation
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/10a-compilation
template_type: Tabbed
title: '10A: Compilation'
transcript: '<p><span m=''5580''>[MUSIC PLAYING]</span> </p><p><span m=''20180''>PROFESSOR:
  Last</span> <span m=''20510''>time,</span> <span m=''20690''>we</span> <span m=''20790''>took</span>
  <span m=''20980''>a</span> <span m=''21040''>look</span> <span m=''21310''>at</span>
  <span m=''22710''>an</span> <span m=''22860''>explicit</span> <span m=''23470''>control</span>
  <span m=''23920''>evaluator</span> <span m=''24910''>for</span> <span m=''25090''>Lisp,</span>
  <span m=''25680''>and</span> <span m=''25840''>that</span> <span m=''26010''>bridged</span>
  <span m=''26310''>the</span> <span m=''26420''>gap</span> <span m=''26810''>between</span>
  <span m=''27120''>all</span> <span m=''27280''>these</span> <span m=''27430''>high-level</span>
  <span m=''28520''>languages</span> <span m=''29050''>like</span> <span m=''29740''>Lisp</span>
  <span m=''30100''>and</span> <span m=''30145''>the</span> <span m=''30190''>query</span>
  <span m=''30460''>language</span> <span m=''31070''>and</span> <span m=''31400''>all</span>
  <span m=''31510''>of</span> <span m=''31630''>that</span> <span m=''31820''>stuff,</span>
  <span m=''32460''>bridged</span> <span m=''32700''>the</span> <span m=''32800''>gap</span>
  <span m=''33020''>between</span> <span m=''33330''>that</span> <span m=''34080''>and</span>
  <span m=''34610''>a</span> <span m=''34750''>conventional</span> <span m=''35280''>register</span>
  <span m=''35650''>machine.</span> <span m=''36640''>And</span> <span m=''36810''>in</span>
  <span m=''36950''>fact,</span> <span m=''37090''>you</span> <span m=''37160''>can</span>
  <span m=''37310''>think</span> <span m=''37620''>of</span> <span m=''37730''>the</span>
  <span m=''37860''>explicit</span> <span m=''39110''>control</span> <span m=''39540''>evaluator</span>
  <span m=''40140''>either</span> <span m=''40650''>as,</span> <span m=''41110''>say,</span>
  <span m=''41470''>the</span> <span m=''42960''>code</span> <span m=''43350''>for</span>
  <span m=''43460''>a</span> <span m=''43570''>Lisp</span> <span m=''43810''>interpreter</span>
  <span m=''44340''>if</span> <span m=''44420''>you</span> <span m=''44520''>wanted</span>
  <span m=''44650''>to</span> <span m=''44790''>implement</span> <span m=''45085''>it</span>
  <span m=''45380''>in</span> <span m=''45580''>the</span> <span m=''46630''>assembly</span>
  <span m=''47020''>language</span> <span m=''47420''>of</span> <span m=''47500''>some</span>
  <span m=''47680''>conventional</span> <span m=''48170''>register</span> <span m=''48520''>transfer</span>
  <span m=''48920''>machine,</span> <span m=''49490''>or,</span> <span m=''49640''>if</span>
  <span m=''49730''>you</span> <span m=''49830''>like,</span> <span m=''50020''>you</span>
  <span m=''50120''>can</span> <span m=''50220''>think</span> <span m=''50410''>of</span>
  <span m=''50470''>it</span> <span m=''50540''>as</span> <span m=''50660''>the</span>
  <span m=''50730''>microcode</span> <span m=''52060''>of</span> <span m=''52260''>some</span>
  <span m=''52460''>machine</span> <span m=''52770''>that''s</span> <span m=''52940''>going</span>
  <span m=''53020''>to</span> <span m=''53110''>be</span> <span m=''53200''>specially</span>
  <span m=''53620''>designed</span> <span m=''53960''>to</span> <span m=''54060''>run</span>
  <span m=''54240''>Lisp.</span> </p><p><span m=''55340''>In</span> <span m=''55470''>either</span>
  <span m=''55720''>case,</span> <span m=''56110''>what</span> <span m=''56230''>we''re</span>
  <span m=''56350''>doing</span> <span m=''56610''>is</span> <span m=''56700''>we''re</span>
  <span m=''56800''>taking</span> <span m=''58050''>a</span> <span m=''58160''>machine</span>
  <span m=''58720''>that</span> <span m=''59150''>speaks</span> <span m=''59390''>some</span>
  <span m=''59590''>low-level</span> <span m=''60000''>language,</span> <span m=''61390''>and</span>
  <span m=''61650''>we''re</span> <span m=''61790''>raising</span> <span m=''62600''>the</span>
  <span m=''62900''>machine</span> <span m=''63340''>to</span> <span m=''63510''>a</span>
  <span m=''63540''>high-level</span> <span m=''64000''>language</span> <span m=''64400''>like</span>
  <span m=''64610''>Lisp</span> <span m=''65250''>by</span> <span m=''65470''>writing</span>
  <span m=''65780''>an</span> <span m=''65850''>interpreter.</span> <span m=''68230''>So</span>
  <span m=''68440''>for</span> <span m=''68690''>instance,</span> <span m=''71800''>here,</span>
  <span m=''72790''>conceptually,</span> <span m=''78960''>is</span> <span m=''79120''>a</span>
  <span m=''80740''>special</span> <span m=''81160''>purpose</span> <span m=''81550''>machine</span>
  <span m=''81950''>for</span> <span m=''82120''>computing</span> <span m=''82530''>factorials.</span>
  <span m=''83910''>It</span> <span m=''84400''>takes</span> <span m=''84680''>in</span>
  <span m=''84780''>five</span> <span m=''86080''>and</span> <span m=''86350''>puts</span>
  <span m=''86550''>out</span> <span m=''86710''>120.</span> <span m=''89000''>And</span>
  <span m=''89130''>what</span> <span m=''89280''>this</span> <span m=''89360''>special</span>
  <span m=''89710''>purpose</span> <span m=''90030''>machine</span> <span m=''90370''>is</span>
  <span m=''90990''>is</span> <span m=''91170''>actually</span> <span m=''91690''>a</span>
  <span m=''91790''>Lisp</span> <span m=''92060''>interpreter</span> <span m=''93630''>that''s</span>
  <span m=''93880''>configured</span> <span m=''94430''>itself</span> <span m=''95010''>to</span>
  <span m=''95160''>run</span> <span m=''95320''>factorials,</span> <span m=''98410''>because</span>
  <span m=''98620''>you</span> <span m=''98730''>fit</span> <span m=''98940''>into</span>
  <span m=''99200''>it</span> <span m=''99260''>a</span> <span m=''99320''>description</span>
  <span m=''99820''>of</span> <span m=''99880''>the</span> <span m=''99950''>factorial</span>
  <span m=''100570''>machine.</span> </p><p><span m=''102410''>So</span> <span m=''102510''>that''s</span>
  <span m=''102700''>what</span> <span m=''102800''>an</span> <span m=''102900''>interpreter</span>
  <span m=''103410''>is.</span> <span m=''103610''>It</span> <span m=''103730''>configures</span>
  <span m=''104280''>itself</span> <span m=''105180''>to</span> <span m=''106390''>emulate</span>
  <span m=''106840''>a</span> <span m=''106880''>machine</span> <span m=''107190''>whose</span>
  <span m=''107320''>description</span> <span m=''107740''>you</span> <span m=''108730''>read</span>
  <span m=''108930''>in.</span> <span m=''110120''>Now,</span> <span m=''110270''>inside</span>
  <span m=''110550''>the</span> <span m=''110620''>Lisp</span> <span m=''110860''>interpreter,</span>
  <span m=''111300''>what''s</span> <span m=''111550''>that?</span> <span m=''112110''>Well,</span>
  <span m=''112310''>that</span> <span m=''112470''>might</span> <span m=''112650''>be</span>
  <span m=''112740''>your</span> <span m=''113090''>general</span> <span m=''113840''>register</span>
  <span m=''114480''>language</span> <span m=''114860''>interpreter</span> <span m=''117090''>that</span>
  <span m=''117300''>configures</span> <span m=''117860''>itself</span> <span m=''118320''>to</span>
  <span m=''118750''>behave</span> <span m=''119050''>like</span> <span m=''119220''>a</span>
  <span m=''119280''>Lisp</span> <span m=''119500''>interpreter,</span> <span m=''120240''>because</span>
  <span m=''120560''>you</span> <span m=''120660''>put</span> <span m=''120800''>in</span>
  <span m=''120890''>a</span> <span m=''120930''>whole</span> <span m=''121080''>bunch</span>
  <span m=''121300''>of</span> <span m=''121360''>instructions</span> <span m=''122140''>in</span>
  <span m=''122280''>register</span> <span m=''122660''>language.</span> <span m=''123410''>This</span>
  <span m=''123590''>is</span> <span m=''123690''>the</span> <span m=''123770''>explicit</span>
  <span m=''124170''>control</span> <span m=''124540''>evaluator.</span> <span m=''127070''>And</span>
  <span m=''127230''>then</span> <span m=''127350''>it</span> <span m=''127400''>also</span>
  <span m=''127700''>has</span> <span m=''127880''>some</span> <span m=''127990''>sort</span>
  <span m=''128120''>of</span> <span m=''128259''>library,</span> <span m=''128729''>a</span>
  <span m=''128860''>library</span> <span m=''129229''>of</span> <span m=''129300''>primitive</span>
  <span m=''129660''>operators</span> <span m=''130250''>and</span> <span m=''130340''>Lisp</span>
  <span m=''130610''>operations</span> <span m=''131170''>and</span> <span m=''131230''>all</span>
  <span m=''131320''>sorts</span> <span m=''131540''>of</span> <span m=''131620''>things</span>
  <span m=''131820''>like</span> <span m=''132010''>that.</span> <span m=''132780''>That''s</span>
  <span m=''133020''>the</span> <span m=''133090''>general</span> <span m=''133960''>strategy</span>
  <span m=''135720''>of</span> <span m=''135860''>interpretation.</span> </p><p><span
  m=''137350''>And</span> <span m=''137450''>the</span> <span m=''137560''>point</span>
  <span m=''137820''>is,</span> <span m=''137930''>what</span> <span m=''138060''>we''re</span>
  <span m=''138170''>doing</span> <span m=''138660''>is</span> <span m=''138790''>we''re</span>
  <span m=''138910''>writing</span> <span m=''139280''>an</span> <span m=''139420''>interpreter</span>
  <span m=''141670''>to</span> <span m=''141870''>raise</span> <span m=''142880''>the</span>
  <span m=''143010''>machine</span> <span m=''143410''>to</span> <span m=''143510''>the</span>
  <span m=''143600''>level</span> <span m=''143910''>of</span> <span m=''143980''>the</span>
  <span m=''144060''>programs</span> <span m=''144500''>that</span> <span m=''144600''>we</span>
  <span m=''144710''>want</span> <span m=''144870''>to</span> <span m=''144920''>write.</span>
  <span m=''145430''>Well,</span> <span m=''145590''>there''s</span> <span m=''145740''>another</span>
  <span m=''146010''>strategy,</span> <span m=''146980''>a</span> <span m=''147370''>different</span>
  <span m=''147730''>one,</span> <span m=''147850''>which</span> <span m=''148020''>is</span>
  <span m=''148110''>compilation.</span> <span m=''149030''>Compilation''s</span>
  <span m=''149590''>a</span> <span m=''149640''>little</span> <span m=''149840''>bit</span>
  <span m=''149990''>different.</span> <span m=''151090''>Here--here</span> <span
  m=''153550''>we</span> <span m=''153660''>might</span> <span m=''153890''>have</span>
  <span m=''154100''>produced</span> <span m=''155670''>a</span> <span m=''156900''>special</span>
  <span m=''157360''>purpose</span> <span m=''157720''>machine</span> <span m=''158120''>for,
  for</span> <span m=''158780''>computing</span> <span m=''159140''>factorials,</span>
  <span m=''163690''>starting</span> <span m=''164150''>with</span> <span m=''164280''>some</span>
  <span m=''164430''>sort</span> <span m=''164650''>of</span> <span m=''164720''>machine</span>
  <span m=''165030''>that</span> <span m=''165170''>speaks</span> <span m=''165430''>register</span>
  <span m=''165830''>language,</span> <span m=''166210''>except</span> <span m=''166450''>we''re</span>
  <span m=''166530''>going</span> <span m=''166590''>to</span> <span m=''166650''>do</span>
  <span m=''166750''>a</span> <span m=''166820''>different</span> <span m=''167090''>strategy.</span>
  </p><p><span m=''167870''>We</span> <span m=''168020''>take</span> <span m=''168310''>our</span>
  <span m=''169090''>factorial</span> <span m=''169720''>program.</span> <span m=''171680''>We</span>
  <span m=''171840''>use</span> <span m=''172020''>that</span> <span m=''172190''>as</span>
  <span m=''172320''>the</span> <span m=''172380''>source</span> <span m=''172770''>code</span>
  <span m=''172980''>into</span> <span m=''173180''>a</span> <span m=''173230''>compiler.</span>
  <span m=''173780''>What</span> <span m=''173890''>the</span> <span m=''174010''>compiler</span>
  <span m=''174540''>will</span> <span m=''174690''>do</span> <span m=''175240''>is</span>
  <span m=''175410''>translate</span> <span m=''176250''>that</span> <span m=''176600''>factorial</span>
  <span m=''177090''>program</span> <span m=''177500''>into</span> <span m=''177700''>some</span>
  <span m=''177890''>register</span> <span m=''178270''>machine</span> <span m=''178570''>language.</span>
  <span m=''179926''>And</span> <span m=''180350''>this</span> <span m=''180630''>will</span>
  <span m=''180700''>now</span> <span m=''180890''>be</span> <span m=''181010''>not</span>
  <span m=''181230''>the</span> <span m=''181610''>explicit</span> <span m=''182120''>control</span>
  <span m=''182510''>evaluator</span> <span m=''182990''>for</span> <span m=''183110''>Lisp,</span>
  <span m=''183410''>this</span> <span m=''183560''>will</span> <span m=''183640''>be</span>
  <span m=''183740''>some</span> <span m=''183970''>register</span> <span m=''184420''>language</span>
  <span m=''184860''>for</span> <span m=''184990''>computing</span> <span m=''185380''>factorials.</span>
  <span m=''186760''>So</span> <span m=''186860''>this</span> <span m=''187080''>is</span>
  <span m=''187190''>the</span> <span m=''187270''>translation</span> <span m=''187910''>of</span>
  <span m=''188160''>that.</span> </p><p><span m=''190460''>That</span> <span m=''190870''>will</span>
  <span m=''190970''>go</span> <span m=''191150''>into</span> <span m=''191340''>some</span>
  <span m=''191510''>sort</span> <span m=''191670''>of</span> <span m=''191830''>loader</span>
  <span m=''193420''>which</span> <span m=''193590''>will</span> <span m=''193690''>combine</span>
  <span m=''194410''>this</span> <span m=''194690''>code</span> <span m=''195280''>with</span>
  <span m=''195500''>code</span> <span m=''195780''>selected</span> <span m=''196170''>from</span>
  <span m=''196265''>the</span> <span m=''196360''>library</span> <span m=''196910''>to</span>
  <span m=''197010''>do</span> <span m=''197140''>things</span> <span m=''197350''>like</span>
  <span m=''197520''>primitive</span> <span m=''197830''>multiplication.</span> <span
  m=''199970''>And</span> <span m=''200110''>then</span> <span m=''200220''>we''ll</span>
  <span m=''200360''>produce</span> <span m=''200720''>a</span> <span m=''200780''>load</span>
  <span m=''201090''>module</span> <span m=''202250''>which</span> <span m=''202440''>configures</span>
  <span m=''203080''>the</span> <span m=''203190''>register</span> <span m=''204070''>language</span>
  <span m=''204430''>machine</span> <span m=''204940''>to</span> <span m=''205280''>be</span>
  <span m=''205380''>a</span> <span m=''205420''>special</span> <span m=''205760''>purpose</span>
  <span m=''206100''>factorial</span> <span m=''206640''>machine.</span> <span m=''208320''>So</span>
  <span m=''208440''>that''s</span> <span m=''209280''>a, that''s a</span> <span m=''209330''>different</span>
  <span m=''209650''>strategy.</span> <span m=''209905''>In</span> <span m=''210160''>interpretation,</span>
  <span m=''211250''>we''re</span> <span m=''211410''>raising</span> <span m=''212940''>the</span>
  <span m=''213080''>machine</span> <span m=''213550''>to</span> <span m=''213660''>the</span>
  <span m=''213740''>level</span> <span m=''214090''>of</span> <span m=''214190''>our</span>
  <span m=''214300''>language,</span> <span m=''214700''>like</span> <span m=''214910''>Lisp.</span>
  <span m=''215360''>In</span> <span m=''215500''>compilation,</span> <span m=''216420''>we''re</span>
  <span m=''217080''>taking</span> <span m=''217420''>our</span> <span m=''217510''>program</span>
  <span m=''217690''>and</span> <span m=''217870''>lowering</span> <span m=''218370''>it</span>
  <span m=''218480''>to</span> <span m=''218580''>the</span> <span m=''218840''>language</span>
  <span m=''219220''>that''s</span> <span m=''219370''>spoken</span> <span m=''219710''>by</span>
  <span m=''219840''>the</span> <span m=''219940''>machine.</span> </p><p><span m=''222040''>Well,</span>
  <span m=''222320''>how</span> <span m=''222450''>do</span> <span m=''222520''>these</span>
  <span m=''222680''>two</span> <span m=''222790''>strategies</span> <span m=''223280''>compare?</span>
  <span m=''224280''>The</span> <span m=''224430''>compiler</span> <span m=''227020''>can</span>
  <span m=''227310''>produce</span> <span m=''227710''>code</span> <span m=''228000''>that</span>
  <span m=''228130''>will</span> <span m=''228280''>execute</span> <span m=''228710''>more</span>
  <span m=''228890''>efficiently.</span> <span m=''232490''>The</span> <span m=''232650''>essential</span>
  <span m=''233130''>reason</span> <span m=''233440''>for</span> <span m=''233560''>that</span>
  <span m=''234170''>is</span> <span m=''234360''>that</span> <span m=''234560''>if</span>
  <span m=''234670''>you</span> <span m=''235470''>think</span> <span m=''235680''>about</span>
  <span m=''236380''>the</span> <span m=''236820''>register</span> <span m=''237390''>operations</span>
  <span m=''238150''>that</span> <span m=''238300''>are</span> <span m=''238450''>running,</span>
  <span m=''241560''>the</span> <span m=''242120''>interpreter</span> <span m=''242650''>has</span>
  <span m=''242870''>to</span> <span m=''242960''>produce</span> <span m=''243260''>register</span>
  <span m=''243760''>operations</span> <span m=''244940''>which,</span> <span m=''245190''>in</span>
  <span m=''245280''>principle,</span> <span m=''245740''>are</span> <span m=''245800''>going</span>
  <span m=''245880''>to</span> <span m=''245960''>be</span> <span m=''246070''>general</span>
  <span m=''246510''>enough</span> <span m=''247280''>to</span> <span m=''247430''>execute</span>
  <span m=''247900''>any</span> <span m=''248150''>Lisp</span> <span m=''248420''>procedure.</span>
  <span m=''250260''>Whereas</span> <span m=''250550''>the</span> <span m=''250630''>compiler</span>
  <span m=''251310''>only</span> <span m=''251550''>has</span> <span m=''251730''>to</span>
  <span m=''251820''>worry</span> <span m=''252080''>about</span> <span m=''252260''>producing</span>
  <span m=''252640''>a</span> <span m=''252680''>special</span> <span m=''253320''>bunch</span>
  <span m=''253590''>of</span> <span m=''253700''>register</span> <span m=''254110''>operations</span>
  <span m=''254670''>for, for</span> <span m=''255660''>doing</span> <span m=''255940''>the</span>
  <span m=''256029''>particular</span> <span m=''256630''>Lisp</span> <span m=''256870''>procedure</span>
  <span m=''257290''>that</span> <span m=''257459''>you''ve</span> <span m=''257620''>compiled.</span>
  </p><p><span m=''260209''>Or</span> <span m=''260399''>another</span> <span m=''260519''>way</span>
  <span m=''260579''>to</span> <span m=''260640''>say</span> <span m=''260870''>that</span>
  <span m=''261240''>is</span> <span m=''261380''>that</span> <span m=''261519''>the</span>
  <span m=''261630''>interpreter</span> <span m=''263060''>is</span> <span m=''263280''>a</span>
  <span m=''263340''>general</span> <span m=''263740''>purpose</span> <span m=''264620''>simulator,</span>
  <span m=''265950''>that</span> <span m=''266130''>when</span> <span m=''266240''>you</span>
  <span m=''266390''>read</span> <span m=''266446''>in</span> <span m=''266503''>a</span>
  <span m=''266560''>Lisp</span> <span m=''266940''>procedure,</span> <span m=''267670''>then</span>
  <span m=''267840''>those</span> <span m=''268070''>can</span> <span m=''268420''>simulate</span>
  <span m=''268940''>the</span> <span m=''269010''>program</span> <span m=''269380''>described</span>
  <span m=''269820''>by</span> <span m=''269940''>that, by that</span> <span m=''270730''>procedure.</span>
  <span m=''271160''>So</span> <span m=''271250''>the</span> <span m=''271370''>interpreter</span>
  <span m=''271830''>is</span> <span m=''271900''>worrying</span> <span m=''272180''>about</span>
  <span m=''272350''>making</span> <span m=''272610''>a</span> <span m=''272640''>general</span>
  <span m=''272960''>purpose</span> <span m=''273290''>simulator,</span> <span m=''274670''>whereas</span>
  <span m=''274890''>the</span> <span m=''274970''>compiler,</span> <span m=''275510''>in</span>
  <span m=''275630''>effect,</span> <span m=''276020''>is</span> <span m=''276170''>configuring</span>
  <span m=''276750''>the</span> <span m=''276820''>thing</span> <span m=''277040''>to</span>
  <span m=''277140''>be</span> <span m=''277250''>the</span> <span m=''277350''>machine</span>
  <span m=''277690''>that</span> <span m=''277820''>the</span> <span m=''277930''>interpreter</span>
  <span m=''278370''>would</span> <span m=''278460''>have</span> <span m=''278560''>been</span>
  <span m=''278690''>simulating.</span> <span m=''280000''>So</span> <span m=''280120''>the</span>
  <span m=''280220''>compiler</span> <span m=''280710''>can</span> <span m=''280820''>be</span>
  <span m=''280920''>faster.</span> </p><p><span m=''292830''>On</span> <span m=''292950''>the</span>
  <span m=''293080''>other</span> <span m=''293220''>hand,</span> <span m=''296050''>the</span>
  <span m=''296200''>interpreter</span> <span m=''296620''>is</span> <span m=''296700''>a</span>
  <span m=''296750''>nicer</span> <span m=''297100''>environment</span> <span m=''297550''>for</span>
  <span m=''297650''>debugging.</span> <span m=''299340''>And</span> <span m=''299520''>the</span>
  <span m=''299590''>reason</span> <span m=''299850''>for</span> <span m=''299960''>that</span>
  <span m=''300140''>is</span> <span m=''300320''>that</span> <span m=''300500''>we''ve</span>
  <span m=''300670''>got</span> <span m=''300970''>the</span> <span m=''301680''>source</span>
  <span m=''301990''>code</span> <span m=''302200''>actually</span> <span m=''302710''>there.</span>
  <span m=''302960''>We''re</span> <span m=''303120''>interpreting</span> <span m=''303640''>it.</span>
  <span m=''303740''>That''s</span> <span m=''303930''>what</span> <span m=''304060''>we''re</span>
  <span m=''304160''>working</span> <span m=''304510''>with.</span> <span m=''306010''>And</span>
  <span m=''306130''>we</span> <span m=''306250''>also</span> <span m=''306520''>have</span>
  <span m=''306630''>the</span> <span m=''306750''>library</span> <span m=''307270''>around.</span>
  <span m=''307880''>See,</span> <span m=''308750''>the interpreter--the</span> <span
  m=''308980''>library</span> <span m=''309410''>sitting</span> <span m=''309720''>there</span>
  <span m=''309860''>is</span> <span m=''309970''>part</span> <span m=''310150''>of</span>
  <span m=''310200''>the</span> <span m=''310310''>interpreter.</span> <span m=''311140''>The</span>
  <span m=''311320''>compiler</span> <span m=''311870''>only</span> <span m=''312060''>pulls</span>
  <span m=''312360''>out</span> <span m=''312530''>from</span> <span m=''312620''>the</span>
  <span m=''312720''>library</span> <span m=''313160''>what</span> <span m=''313320''>it</span>
  <span m=''313410''>needs</span> <span m=''313660''>to</span> <span m=''313760''>run</span>
  <span m=''313930''>the</span> <span m=''314000''>program.</span> </p><p><span m=''314830''>So</span>
  <span m=''315090''>if</span> <span m=''315740''>you''re</span> <span m=''315920''>in</span>
  <span m=''316000''>the</span> <span m=''316080''>middle</span> <span m=''316360''>of</span>
  <span m=''316440''>debugging,</span> <span m=''318000''>and</span> <span m=''318140''>you</span>
  <span m=''318250''>might</span> <span m=''318480''>like</span> <span m=''318710''>to</span>
  <span m=''318850''>write</span> <span m=''319580''>a</span> <span m=''319690''>little</span>
  <span m=''319900''>extra</span> <span m=''320260''>program</span> <span m=''320740''>to</span>
  <span m=''320910''>examine</span> <span m=''321340''>some</span> <span m=''321550''>run</span>
  <span m=''321730''>time</span> <span m=''321930''>data</span> <span m=''322170''>structure</span>
  <span m=''322920''>or</span> <span m=''323110''>to</span> <span m=''323200''>produce</span>
  <span m=''323480''>some</span> <span m=''323620''>computation</span> <span m=''324330''>that</span>
  <span m=''324450''>you</span> <span m=''324540''>didn''t</span> <span m=''324770''>think</span>
  <span m=''324950''>of</span> <span m=''325070''>when</span> <span m=''325180''>you</span>
  <span m=''325290''>wrote</span> <span m=''325450''>the</span> <span m=''325530''>program,</span>
  <span m=''325890''>the</span> <span m=''325990''>interpreter</span> <span m=''326420''>can</span>
  <span m=''326540''>do</span> <span m=''326640''>that</span> <span m=''326820''>perfectly</span>
  <span m=''327230''>well,</span> <span m=''328080''>whereas</span> <span m=''328310''>the</span>
  <span m=''328390''>compiler</span> <span m=''328830''>can''t.</span> <span m=''329670''>So</span>
  <span m=''329810''>there</span> <span m=''329870''>are</span> <span m=''329930''>sort</span>
  <span m=''330040''>of</span> <span m=''330160''>dual, dual</span> <span m=''331370''>advantages.</span>
  <span m=''331850''>The</span> <span m=''331930''>compiler</span> <span m=''332390''>will</span>
  <span m=''332750''>produce</span> <span m=''333140''>code</span> <span m=''333340''>that</span>
  <span m=''333460''>executes</span> <span m=''333920''>faster.</span> <span m=''334720''>The</span>
  <span m=''334920''>interpreter</span> <span m=''335330''>is</span> <span m=''335420''>a</span>
  <span m=''335470''>better</span> <span m=''335770''>environment</span> <span m=''336290''>for</span>
  <span m=''336390''>debugging.</span> </p><p><span m=''339030''>And</span> <span
  m=''339300''>most</span> <span m=''339900''>Lisp</span> <span m=''340170''>systems</span>
  <span m=''340560''>end</span> <span m=''340710''>up</span> <span m=''340810''>having</span>
  <span m=''341090''>both,</span> <span m=''342970''>end</span> <span m=''343180''>up</span>
  <span m=''343290''>being</span> <span m=''343520''>configured</span> <span m=''344010''>so</span>
  <span m=''344110''>you</span> <span m=''344340''>have</span> <span m=''344600''>an</span>
  <span m=''344720''>interpreter</span> <span m=''345220''>that</span> <span m=''345350''>you</span>
  <span m=''345480''>use</span> <span m=''345750''>when</span> <span m=''345860''>you''re</span>
  <span m=''345970''>developing</span> <span m=''346460''>your</span> <span m=''346610''>code.</span>
  <span m=''346930''>Then</span> <span m=''347050''>you</span> <span m=''347150''>can</span>
  <span m=''347260''>speed</span> <span m=''347570''>it</span> <span m=''347660''>up</span>
  <span m=''347780''>by</span> <span m=''347920''>compiling.</span> <span m=''349060''>And</span>
  <span m=''349420''>very</span> <span m=''349690''>often,</span> <span m=''350030''>you</span>
  <span m=''350140''>can</span> <span m=''350270''>arrange</span> <span m=''350610''>that</span>
  <span m=''350800''>compiled</span> <span m=''351340''>code</span> <span m=''351610''>and</span>
  <span m=''351720''>interpreted</span> <span m=''352520''>code</span> <span m=''352790''>can</span>
  <span m=''352930''>call</span> <span m=''353170''>each</span> <span m=''353310''>other.</span>
  <span m=''354810''>We''ll</span> <span m=''354970''>see</span> <span m=''355130''>how</span>
  <span m=''355330''>to</span> <span m=''355390''>do</span> <span m=''355510''>that.</span>
  <span m=''355700''>That''s</span> <span m=''355880''>not</span> <span m=''355960''>hard.</span>
  </p><p><span m=''361040''>In</span> <span m=''361160''>fact, the way we''ll--</span>
  <span m=''364390''>in</span> <span m=''364520''>the</span> <span m=''364600''>compiler</span>
  <span m=''365040''>we''re</span> <span m=''365150''>going</span> <span m=''365230''>to</span>
  <span m=''365310''>make,</span> <span m=''365750''>the</span> <span m=''365890''>way</span>
  <span m=''366030''>we''ll</span> <span m=''366260''>arrange</span> <span m=''366580''>for</span>
  <span m=''366690''>compiled</span> <span m=''367150''>coding</span> <span m=''367320''>and</span>
  <span m=''367490''>interpreted</span> <span m=''367980''>code</span> <span m=''368220''>to</span>
  <span m=''368780''>call, to call</span> <span m=''369040''>each</span> <span m=''369200''>other,</span>
  <span m=''369930''>is</span> <span m=''370130''>that</span> <span m=''370350''>we''ll</span>
  <span m=''370440''>have</span> <span m=''370630''>the</span> <span m=''370710''>compiler</span>
  <span m=''371470''>use</span> <span m=''371700''>exactly</span> <span m=''372220''>the</span>
  <span m=''372300''>same</span> <span m=''372590''>register</span> <span m=''372980''>conventions</span>
  <span m=''373580''>as</span> <span m=''373700''>the</span> <span m=''373820''>interpreter.</span>
  <span m=''378680''>Well,</span> <span m=''379040''>the</span> <span m=''379230''>idea</span>
  <span m=''379660''>of</span> <span m=''379860''>a</span> <span m=''381550''>compiler</span>
  <span m=''381880''>is</span> <span m=''382210''>very</span> <span m=''382500''>much</span>
  <span m=''383080''>like</span> <span m=''383320''>the</span> <span m=''383470''>idea</span>
  <span m=''383800''>of</span> <span m=''383900''>an</span> <span m=''383970''>interpreter</span>
  <span m=''384640''>or</span> <span m=''385170''>evaluator.</span> <span m=''385490''>It''s</span>
  <span m=''385650''>the</span> <span m=''385810''>same</span> <span m=''386105''>thing.</span>
  <span m=''387070''>See,</span> <span m=''387350''>the</span> <span m=''387610''>evaluator</span>
  <span m=''388240''>walks</span> <span m=''388630''>over</span> <span m=''388750''>the</span>
  <span m=''388880''>code</span> <span m=''389700''>and</span> <span m=''390990''>performs</span>
  <span m=''391390''>some</span> <span m=''391460''>register</span> <span m=''391850''>operations.</span>
  <span m=''393840''>That''s</span> <span m=''394010''>what</span> <span m=''394100''>we</span>
  <span m=''394240''>did</span> <span m=''394450''>yesterday.</span> </p><p><span
  m=''397040''>Well,</span> <span m=''397290''>the</span> <span m=''397380''>compiler</span>
  <span m=''398200''>essentially</span> <span m=''398730''>would</span> <span m=''398840''>like</span>
  <span m=''399010''>to</span> <span m=''399110''>walk</span> <span m=''399390''>over</span>
  <span m=''399590''>the</span> <span m=''399700''>code</span> <span m=''400540''>and</span>
  <span m=''400730''>produce</span> <span m=''401520''>the</span> <span m=''401910''>register</span>
  <span m=''402390''>operations</span> <span m=''403050''>that</span> <span m=''403240''>the</span>
  <span m=''403380''>evaluator</span> <span m=''404000''>would</span> <span m=''404200''>have</span>
  <span m=''404400''>done</span> <span m=''405000''>were</span> <span m=''405320''>it</span>
  <span m=''405550''>evaluating</span> <span m=''406210''>the</span> <span m=''406280''>thing.</span>
  <span m=''408890''>And</span> <span m=''408970''>that</span> <span m=''409050''>gives</span>
  <span m=''409230''>us</span> <span m=''409360''>a</span> <span m=''409410''>model</span>
  <span m=''410450''>for</span> <span m=''410680''>how</span> <span m=''410790''>to</span>
  <span m=''410900''>implement</span> <span m=''411800''>a</span> <span m=''412000''>zeroth-order</span>
  <span m=''413150''>compiler,</span> <span m=''414990''>a</span> <span m=''415410''>very</span>
  <span m=''415770''>bad</span> <span m=''416060''>compiler</span> <span m=''416360''>but</span>
  <span m=''417150''>essentially a</span> <span m=''417720''>compiler.</span> <span
  m=''418330''>A</span> <span m=''418380''>model</span> <span m=''418730''>for</span>
  <span m=''418850''>doing</span> <span m=''419110''>that</span> <span m=''419280''>is</span>
  <span m=''419380''>you</span> <span m=''419480''>just</span> <span m=''419670''>take</span>
  <span m=''419870''>the</span> <span m=''419980''>evaluator,</span> <span m=''420730''>you</span>
  <span m=''420900''>run</span> <span m=''420995''>it</span> <span m=''421090''>over</span>
  <span m=''421330''>the</span> <span m=''421440''>code,</span> <span m=''422660''>but</span>
  <span m=''423020''>instead</span> <span m=''423300''>of</span> <span m=''423400''>executing</span>
  <span m=''424710''>the</span> <span m=''424970''>actual</span> <span m=''425320''>operations,</span>
  <span m=''426040''>you</span> <span m=''426240''>just</span> <span m=''426410''>save</span>
  <span m=''426660''>them</span> <span m=''426790''>away.</span> <span m=''427550''>And</span>
  <span m=''427670''>that''s</span> <span m=''427820''>your</span> <span m=''427940''>compiled</span>
  <span m=''428390''>code.</span> </p><p><span m=''428820''>So</span> <span m=''428950''>let</span>
  <span m=''429010''>me</span> <span m=''429070''>give</span> <span m=''429130''>you</span>
  <span m=''429250''>an</span> <span m=''429320''>example</span> <span m=''429780''>of</span>
  <span m=''429960''>that.</span> <span m=''435130''>Suppose we''re going to compile--suppose</span>
  <span m=''435340''>we</span> <span m=''435470''>want</span> <span m=''435620''>to</span>
  <span m=''435770''>compile</span> <span m=''436210''>the</span> <span m=''436290''>expression</span>
  <span m=''436880''>f</span> <span m=''437220''>of</span> <span m=''437510''>x.</span>
  <span m=''445100''>So</span> <span m=''445290''>let''s</span> <span m=''445500''>assume</span>
  <span m=''445840''>that</span> <span m=''445970''>we''ve</span> <span m=''446120''>got</span>
  <span m=''446410''>f</span> <span m=''446610''>of</span> <span m=''446730''>x</span>
  <span m=''446970''>in</span> <span m=''447070''>the</span> <span m=''447170''>x</span>
  <span m=''447630''>register</span> <span m=''448010''>and</span> <span m=''448175''>something</span>
  <span m=''448340''>in</span> <span m=''448430''>the</span> <span m=''448520''>environment</span>
  <span m=''448960''>register.</span> <span m=''450170''>And</span> <span m=''450300''>now</span>
  <span m=''450440''>imagine</span> <span m=''450860''>starting</span> <span m=''451270''>up</span>
  <span m=''451360''>the</span> <span m=''451440''>evaluator.</span> <span m=''454560''>Well,</span>
  <span m=''454890''>it</span> <span m=''454960''>looks</span> <span m=''455180''>at</span>
  <span m=''455240''>the</span> <span m=''455340''>expression</span> <span m=''455820''>and</span>
  <span m=''456030''>it</span> <span m=''456240''>sees</span> <span m=''456305''>that</span>
  <span m=''456370''>it''s</span> <span m=''456510''>an</span> <span m=''456600''>application.</span>
  <span m=''458000''>And</span> <span m=''459820''>it</span> <span m=''459950''>branches</span>
  <span m=''460560''>to</span> <span m=''461080''>a</span> <span m=''461170''>place</span>
  <span m=''461480''>in</span> <span m=''461650''>the</span> <span m=''462580''>evaluator</span>
  <span m=''463200''>code</span> <span m=''463350''>we</span> <span m=''463510''>saw</span>
  <span m=''463730''>called</span> <span m=''463930''>ev-application.</span> <span
  m=''467230''>And</span> <span m=''467450''>then</span> <span m=''467580''>it</span>
  <span m=''467700''>begins.</span> <span m=''468190''>It</span> <span m=''468330''>stores</span>
  <span m=''468660''>away</span> <span m=''468880''>the</span> <span m=''469010''>operands</span>
  <span m=''469570''>and</span> <span m=''469680''>unev,</span> <span m=''470100''>and</span>
  <span m=''470220''>then</span> <span m=''470340''>it''s</span> <span m=''470480''>going</span>
  <span m=''470560''>to</span> <span m=''470650''>put</span> <span m=''470850''>the</span>
  <span m=''471460''>operator</span> <span m=''472050''>in</span> <span m=''472150''>exp,</span>
  <span m=''472455''>and</span> <span m=''472607''>it''s</span> <span m=''472760''>going</span>
  <span m=''472820''>to</span> <span m=''472890''>go</span> <span m=''473030''>recursively</span>
  <span m=''473590''>evaluate</span> <span m=''473895''>it.</span> </p><p><span m=''474410''>That''s</span>
  <span m=''474750''>the</span> <span m=''474830''>process</span> <span m=''475220''>that</span>
  <span m=''475330''>we</span> <span m=''475440''>walk</span> <span m=''475670''>through.</span>
  <span m=''476385''>And</span> <span m=''476770''>if</span> <span m=''476930''>you</span>
  <span m=''477020''>start</span> <span m=''477240''>looking</span> <span m=''477500''>at</span>
  <span m=''477560''>the</span> <span m=''477640''>code,</span> <span m=''477880''>you</span>
  <span m=''477950''>start</span> <span m=''478180''>seeing</span> <span m=''478360''>some</span>
  <span m=''478620''>register</span> <span m=''479040''>operations.</span> <span m=''480200''>You</span>
  <span m=''480320''>see</span> <span m=''480420''>assign</span> <span m=''480970''>to</span>
  <span m=''481100''>unev</span> <span m=''481470''>the</span> <span m=''481600''>operands,</span>
  <span m=''481950''>assign</span> <span m=''482490''>to</span> <span m=''482560''>exp</span>
  <span m=''483200''>the</span> <span m=''483370''>operator,</span> <span m=''484100''>save</span>
  <span m=''484430''>the</span> <span m=''484560''>environment,</span> <span m=''485100''>generate</span>
  <span m=''485520''>that,</span> <span m=''485750''>and</span> <span m=''485920''>so</span>
  <span m=''486200''>on.</span> <span m=''490310''>Well,</span> <span m=''490470''>if</span>
  <span m=''490505''>we</span> <span m=''490540''>look</span> <span m=''490690''>on</span>
  <span m=''491080''>the</span> <span m=''491210''>overhead</span> <span m=''491570''>here,</span>
  <span m=''495770''>we</span> <span m=''495880''>can</span> <span m=''496000''>see,
  we can see</span> <span m=''497850''>those</span> <span m=''498040''>operations</span>
  <span m=''498660''>starting</span> <span m=''498910''>to</span> <span m=''498970''>be</span>
  <span m=''499090''>produced.</span> <span m=''500860''>Here''s</span> <span m=''500915''>sort</span>
  <span m=''500970''>of</span> <span m=''501170''>the</span> <span m=''501380''>first</span>
  <span m=''501590''>real</span> <span m=''501840''>operation</span> <span m=''502600''>that</span>
  <span m=''502800''>the</span> <span m=''503440''>evaluator</span> <span m=''504130''>would</span>
  <span m=''504260''>have</span> <span m=''504400''>done.</span> <span m=''504910''>It</span>
  <span m=''505100''>pulls</span> <span m=''505310''>the</span> <span m=''505410''>operands</span>
  <span m=''506050''>out</span> <span m=''506220''>of</span> <span m=''506290''>the</span>
  <span m=''506410''>exp</span> <span m=''506850''>register</span> <span m=''507460''>and</span>
  <span m=''507610''>assigns</span> <span m=''507980''>it</span> <span m=''508070''>to</span>
  <span m=''508170''>unev.</span> <span m=''510070''>And</span> <span m=''510220''>then</span>
  <span m=''510420''>it</span> <span m=''510580''>assigns</span> <span m=''510740''>something</span>
  <span m=''511110''>to</span> <span m=''511240''>the</span> <span m=''511340''>expression</span>
  <span m=''511780''>register,</span> <span m=''512250''>and</span> <span m=''512340''>it</span>
  <span m=''512440''>saves</span> <span m=''512730''>continue,</span> <span m=''513620''>and</span>
  <span m=''513740''>it</span> <span m=''513860''>saves</span> <span m=''514240''>env.</span>
  </p><p><span m=''514740''>And</span> <span m=''514860''>all</span> <span m=''514980''>I''m</span>
  <span m=''515100''>doing</span> <span m=''515360''>here</span> <span m=''515559''>is</span>
  <span m=''515659''>writing</span> <span m=''516070''>down</span> <span m=''517220''>the</span>
  <span m=''517610''>register</span> <span m=''518049''>assignments</span> <span m=''519620''>that</span>
  <span m=''519760''>the</span> <span m=''519900''>evaluator</span> <span m=''520500''>would</span>
  <span m=''520630''>have</span> <span m=''520760''>done</span> <span m=''521049''>in</span>
  <span m=''521130''>executing</span> <span m=''521650''>that</span> <span m=''521730''>code.</span>
  <span m=''522010''>And</span> <span m=''522770''>can</span> <span m=''522964''>zoom</span>
  <span m=''523159''>out</span> <span m=''523250''>a</span> <span m=''523340''>little</span>
  <span m=''523510''>bit.</span> <span m=''524280''>Altogether,</span> <span m=''524700''>there</span>
  <span m=''524860''>are</span> <span m=''525240''>about</span> <span m=''525720''>19</span>
  <span m=''526200''>operations</span> <span m=''526860''>there.</span> <span m=''529430''>And</span>
  <span m=''529720''>this is the--this</span> <span m=''530410''>will</span> <span
  m=''530480''>be</span> <span m=''530610''>the</span> <span m=''530700''>piece</span>
  <span m=''530980''>of</span> <span m=''531090''>code</span> <span m=''532010''>up</span>
  <span m=''532260''>until</span> <span m=''532570''>the</span> <span m=''532650''>point</span>
  <span m=''533420''>where</span> <span m=''534870''>the</span> <span m=''534970''>evaluator</span>
  <span m=''535530''>branches</span> <span m=''535960''>off</span> <span m=''536100''>to</span>
  <span m=''536230''>apply-dispatch.</span> <span m=''537940''>And</span> <span m=''538040''>in</span>
  <span m=''538140''>fact,</span> <span m=''538400''>in</span> <span m=''538520''>this</span>
  <span m=''538640''>compiler,</span> <span m=''539120''>we''re</span> <span m=''539250''>not</span>
  <span m=''539440''>going</span> <span m=''539510''>to</span> <span m=''539590''>worry</span>
  <span m=''539880''>about</span> <span m=''540110''>apply-dispatch</span> <span m=''540870''>at</span>
  <span m=''540930''>all.</span> <span m=''541450''>We''re</span> <span m=''542340''>going</span>
  <span m=''542450''>to</span> <span m=''542560''>have everything--we''re going to
  have</span> <span m=''542700''>both</span> <span m=''543060''>interpreted</span>
  <span m=''543620''>code</span> <span m=''543880''>and</span> <span m=''544050''>compiled</span>
  <span m=''544530''>code.</span> <span m=''546160''>Always</span> <span m=''546500''>evaluate</span>
  <span m=''547000''>procedures,</span> <span m=''547540''>always</span> <span m=''547780''>apply</span>
  <span m=''548060''>procedures</span> <span m=''548540''>by</span> <span m=''548670''>going</span>
  <span m=''548920''>to</span> <span m=''549040''>apply-dispatch.</span> <span m=''550240''>That</span>
  <span m=''550540''>will</span> <span m=''550710''>easily</span> <span m=''551130''>allow</span>
  <span m=''551450''>interpreted</span> <span m=''551930''>code</span> <span m=''552160''>and</span>
  <span m=''552270''>compiled</span> <span m=''552720''>code</span> <span m=''552940''>to</span>
  <span m=''553020''>call</span> <span m=''553270''>each</span> <span m=''553410''>other.</span>
  </p><p><span m=''558330''>Well,</span> <span m=''558430''>in</span> <span m=''558530''>principle,</span>
  <span m=''558900''>that''s</span> <span m=''559090''>all</span> <span m=''559190''>we</span>
  <span m=''559300''>need</span> <span m=''559410''>to</span> <span m=''559550''>do.</span>
  <span m=''561220''>You</span> <span m=''561420''>just</span> <span m=''561610''>run</span>
  <span m=''561820''>the</span> <span m=''561950''>evaluator.</span> <span m=''562620''>So</span>
  <span m=''562670''>the</span> <span m=''562730''>compiler''s</span> <span m=''563200''>a</span>
  <span m=''563260''>lot</span> <span m=''563470''>like</span> <span m=''563640''>the</span>
  <span m=''563770''>evaluator.</span> <span m=''564320''>You</span> <span m=''564460''>run</span>
  <span m=''564650''>it,</span> <span m=''564750''>except</span> <span m=''564930''>it</span>
  <span m=''565110''>stashes</span> <span m=''565580''>away</span> <span m=''565780''>these</span>
  <span m=''565980''>operations</span> <span m=''566620''>instead</span> <span m=''566890''>of</span>
  <span m=''566960''>actually</span> <span m=''567670''>executing</span> <span m=''567955''>them.</span>
  <span m=''569480''>Well,</span> <span m=''569670''>that''s</span> <span m=''569830''>not,
  that''s not</span> <span m=''570310''>quite</span> <span m=''570600''>true.</span>
  <span m=''572680''>There''s</span> <span m=''573170''>only</span> <span m=''573360''>one</span>
  <span m=''574100''>little</span> <span m=''574330''>lie</span> <span m=''574515''>in</span>
  <span m=''574700''>that.</span> </p><p><span m=''576370''>What</span> <span m=''576450''>you</span>
  <span m=''576530''>have</span> <span m=''576650''>to</span> <span m=''576740''>worry</span>
  <span m=''577030''>about</span> <span m=''577320''>is</span> <span m=''577460''>if</span>
  <span m=''577550''>you</span> <span m=''577750''>have</span> <span m=''578530''>a,
  a</span> <span m=''578650''>predicate.</span> <span m=''580480''>If</span> <span
  m=''580570''>you</span> <span m=''580640''>have</span> <span m=''580720''>some</span>
  <span m=''580900''>kind</span> <span m=''581030''>of</span> <span m=''581160''>test</span>
  <span m=''581500''>you</span> <span m=''581610''>want</span> <span m=''581710''>to</span>
  <span m=''581810''>do,</span> <span m=''583560''>obviously,</span> <span m=''584110''>at</span>
  <span m=''584200''>the</span> <span m=''584290''>point</span> <span m=''584590''>when</span>
  <span m=''584720''>you''re</span> <span m=''585000''>compiling</span> <span m=''585770''>it,</span>
  <span m=''586580''>you</span> <span m=''586690''>don''t</span> <span m=''586880''>know</span>
  <span m=''587000''>which</span> <span m=''587250''>branch</span> <span m=''587610''>of
  these--of</span> <span m=''588460''>a</span> <span m=''588570''>conditional</span>
  <span m=''589050''>like</span> <span m=''589220''>this</span> <span m=''589400''>you''re</span>
  <span m=''589490''>going</span> <span m=''589790''>to</span> <span m=''589830''>do.</span>
  <span m=''591400''>So</span> <span m=''591470''>you</span> <span m=''591580''>can''t</span>
  <span m=''591830''>say</span> <span m=''591990''>which</span> <span m=''592240''>one</span>
  <span m=''592420''>the</span> <span m=''592560''>evaluator</span> <span m=''593150''>would</span>
  <span m=''593340''>have</span> <span m=''593530''>done.</span> <span m=''595010''>So</span>
  <span m=''595300''>all</span> <span m=''595370''>you</span> <span m=''595440''>do</span>
  <span m=''595570''>there</span> <span m=''595870''>is</span> <span m=''596660''>very</span>
  <span m=''596860''>simple.</span> <span m=''597190''>You</span> <span m=''597360''>compile</span>
  <span m=''597810''>both</span> <span m=''598070''>branches.</span> </p><p><span
  m=''598985''>So</span> <span m=''599360''>you</span> <span m=''599540''>compile</span>
  <span m=''599950''>a</span> <span m=''599990''>structure</span> <span m=''600360''>that</span>
  <span m=''600520''>looks</span> <span m=''600710''>like</span> <span m=''600930''>this.</span>
  <span m=''602050''>That''ll</span> <span m=''602320''>compile</span> <span m=''602850''>into</span>
  <span m=''603030''>something</span> <span m=''603370''>that</span> <span m=''603540''>says,</span>
  <span m=''605010''>the code, the</span> <span m=''605330''>code</span> <span m=''608430''>for</span>
  <span m=''608560''>P.</span> <span m=''610680''>And</span> <span m=''610850''>it</span>
  <span m=''610930''>puts</span> <span m=''611150''>its</span> <span m=''611310''>results</span>
  <span m=''614840''>in,</span> <span m=''615350''>say,</span> <span m=''615540''>the</span>
  <span m=''615660''>val</span> <span m=''615930''>register.</span> <span m=''618140''>So</span>
  <span m=''618310''>you</span> <span m=''619090''>walk</span> <span m=''619360''>the</span>
  <span m=''619470''>interpreter</span> <span m=''619970''>over</span> <span m=''620120''>the</span>
  <span m=''620210''>predicate</span> <span m=''621400''>and</span> <span m=''621470''>make</span>
  <span m=''621680''>sure</span> <span m=''621880''>that</span> <span m=''622410''>the</span>
  <span m=''622520''>result</span> <span m=''622870''>would</span> <span m=''622940''>go</span>
  <span m=''623090''>into</span> <span m=''623210''>the</span> <span m=''623340''>val</span>
  <span m=''623590''>register.</span> <span m=''624770''>And</span> <span m=''624900''>then</span>
  <span m=''625040''>you</span> <span m=''625140''>compile</span> <span m=''626170''>an</span>
  <span m=''626320''>instruction</span> <span m=''626840''>that</span> <span m=''627020''>says,</span>
  <span m=''627240''>branch</span> <span m=''630790''>if, if</span> <span m=''632810''>val</span>
  <span m=''633060''>is</span> <span m=''633310''>true,</span> <span m=''636970''>to</span>
  <span m=''637150''>a</span> <span m=''637330''>place</span> <span m=''637610''>we''ll</span>
  <span m=''637700''>call</span> <span m=''637920''>label</span> <span m=''638280''>one.</span>
  </p><p><span m=''644950''>Then</span> <span m=''645190''>we, we</span> <span m=''646190''>will</span>
  <span m=''646290''>put</span> <span m=''646470''>the</span> <span m=''646550''>code</span>
  <span m=''646850''>for</span> <span m=''646980''>B</span> <span m=''649080''>to</span>
  <span m=''649600''>walk the interpreter--walk</span> <span m=''649890''>the</span>
  <span m=''651120''>interpreter</span> <span m=''651670''>over</span> <span m=''651800''>B.</span>
  <span m=''653660''>And</span> <span m=''653840''>then</span> <span m=''654040''>go</span>
  <span m=''654270''>to</span> <span m=''655990''>put</span> <span m=''656190''>in</span>
  <span m=''656260''>an</span> <span m=''656330''>instruction</span> <span m=''656900''>that</span>
  <span m=''657030''>says,</span> <span m=''657230''>go</span> <span m=''657390''>to</span>
  <span m=''657600''>the</span> <span m=''657830''>next</span> <span m=''658070''>thing,</span>
  <span m=''658320''>whatever, whatever</span> <span m=''662640''>was</span> <span
  m=''662770''>supposed</span> <span m=''662920''>to</span> <span m=''663080''>happen</span>
  <span m=''663430''>after</span> <span m=''663640''>this</span> <span m=''663820''>thing</span>
  <span m=''663960''>was</span> <span m=''664100''>done.</span> <span m=''664920''>You</span>
  <span m=''665040''>put</span> <span m=''665170''>in</span> <span m=''665260''>that</span>
  <span m=''665430''>instruction.</span> <span m=''666900''>And</span> <span m=''667040''>here</span>
  <span m=''667190''>you</span> <span m=''667320''>put</span> <span m=''667490''>label</span>
  <span m=''667820''>one.</span> <span m=''671521''>And</span> <span m=''671990''>here</span>
  <span m=''672290''>you</span> <span m=''672590''>put</span> <span m=''672750''>the</span>
  <span m=''672830''>code</span> <span m=''673140''>for</span> <span m=''673280''>A.</span>
  <span m=''679400''>And</span> <span m=''679750''>you</span> <span m=''679860''>put</span>
  <span m=''680090''>go</span> <span m=''680280''>to</span> <span m=''685140''>next</span>
  <span m=''685500''>thing.</span> </p><p><span m=''691420''>So</span> <span m=''691600''>that''s</span>
  <span m=''691850''>how</span> <span m=''691935''>you</span> <span m=''692020''>treat</span>
  <span m=''692220''>a</span> <span m=''692290''>conditional.</span> <span m=''693090''>You</span>
  <span m=''693170''>generate</span> <span m=''693530''>a</span> <span m=''693570''>little</span>
  <span m=''693760''>block</span> <span m=''694080''>like</span> <span m=''694280''>that.</span>
  <span m=''695890''>And</span> <span m=''697290''>other</span> <span m=''697530''>than</span>
  <span m=''697690''>that,</span> <span m=''699000''>this</span> <span m=''699110''>zeroth-order</span>
  <span m=''699810''>compiler</span> <span m=''700145''>is</span> <span m=''700480''>the</span>
  <span m=''700550''>same</span> <span m=''700810''>as</span> <span m=''700900''>the</span>
  <span m=''701000''>evaluator.</span> <span m=''702310''>It''s</span> <span m=''702510''>just</span>
  <span m=''702660''>stashing</span> <span m=''703130''>away</span> <span m=''703350''>the</span>
  <span m=''703480''>instructions</span> <span m=''704040''>instead</span> <span m=''704310''>of</span>
  <span m=''704380''>executing</span> <span m=''704890''>them.</span> <span m=''706380''>That</span>
  <span m=''706800''>seems</span> <span m=''706990''>pretty</span> <span m=''707190''>simple,</span>
  <span m=''707550''>but</span> <span m=''707690''>we''ve</span> <span m=''707810''>gained</span>
  <span m=''708140''>something</span> <span m=''708520''>by</span> <span m=''708680''>that.</span>
  <span m=''710120''>See,</span> <span m=''710270''>already</span> <span m=''710660''>that''s</span>
  <span m=''710880''>going</span> <span m=''710950''>to</span> <span m=''711030''>be</span>
  <span m=''711150''>more</span> <span m=''711360''>efficient</span> <span m=''711750''>than</span>
  <span m=''711890''>the</span> <span m=''712060''>evaluator.</span> <span m=''713630''>Because,</span>
  <span m=''713930''>if</span> <span m=''714030''>you</span> <span m=''714140''>watch</span>
  <span m=''714750''>the</span> <span m=''715000''>evaluator</span> <span m=''715590''>run,</span>
  <span m=''716320''>it''s</span> <span m=''716530''>not</span> <span m=''716790''>only</span>
  <span m=''718030''>generating</span> <span m=''719200''>the</span> <span m=''719430''>register</span>
  <span m=''719890''>operations</span> <span m=''720410''>we</span> <span m=''720510''>wrote</span>
  <span m=''720710''>down,</span> <span m=''721220''>it''s</span> <span m=''721410''>also</span>
  <span m=''721630''>doing</span> <span m=''721910''>things</span> <span m=''722130''>to</span>
  <span m=''722230''>decide</span> <span m=''722610''>which</span> <span m=''722780''>ones</span>
  <span m=''722960''>to</span> <span m=''723060''>generate.</span> </p><p><span m=''724740''>So</span>
  <span m=''725270''>the</span> <span m=''725410''>very</span> <span m=''725730''>first</span>
  <span m=''726110''>thing</span> <span m=''726280''>it</span> <span m=''726390''>does,</span>
  <span m=''726650''>say,</span> <span m=''726890''>here</span> <span m=''727700''>for</span>
  <span m=''728090''>instance,</span> <span m=''728480''>is</span> <span m=''728810''>go</span>
  <span m=''728950''>do</span> <span m=''729120''>some</span> <span m=''729340''>tests</span>
  <span m=''729770''>and</span> <span m=''729910''>decide</span> <span m=''730380''>that</span>
  <span m=''730510''>this</span> <span m=''730670''>is</span> <span m=''730760''>an</span>
  <span m=''730860''>application,</span> <span m=''733470''>and</span> <span m=''733770''>then</span>
  <span m=''733890''>branch</span> <span m=''734340''>off</span> <span m=''734510''>to</span>
  <span m=''734600''>the</span> <span m=''734700''>place</span> <span m=''734980''>that,
  that</span> <span m=''735590''>handles</span> <span m=''735930''>applications.</span>
  <span m=''736780''>In</span> <span m=''736840''>other</span> <span m=''736970''>words,</span>
  <span m=''737150''>what</span> <span m=''737310''>the</span> <span m=''737420''>evaluator''s</span>
  <span m=''738030''>doing</span> <span m=''738710''>is</span> <span m=''738870''>simultaneously</span>
  <span m=''740840''>analyzing</span> <span m=''741450''>the</span> <span m=''741530''>code</span>
  <span m=''741780''>to</span> <span m=''741890''>see</span> <span m=''742000''>what</span>
  <span m=''742135''>to</span> <span m=''742270''>do,</span> <span m=''743550''>and</span>
  <span m=''743720''>running</span> <span m=''744030''>these</span> <span m=''744220''>operations.</span>
  <span m=''745580''>And when you--</span> <span m=''745960''>if</span> <span m=''746060''>you</span>
  <span m=''746170''>run</span> <span m=''746710''>the</span> <span m=''747010''>evaluator</span>
  <span m=''747570''>a</span> <span m=''747610''>million</span> <span m=''747910''>times,</span>
  <span m=''748270''>that</span> <span m=''748390''>analysis</span> <span m=''748960''>phase</span>
  <span m=''749190''>happens</span> <span m=''749520''>a</span> <span m=''749560''>million</span>
  <span m=''749860''>times,</span> <span m=''750920''>whereas</span> <span m=''751150''>in</span>
  <span m=''751195''>the</span> <span m=''751240''>compiler,</span> <span m=''751555''>it''s</span>
  <span m=''751870''>happened</span> <span m=''752190''>once,</span> <span m=''752530''>and</span>
  <span m=''752620''>then</span> <span m=''752710''>you</span> <span m=''752800''>just</span>
  <span m=''753030''>have</span> <span m=''753150''>the</span> <span m=''753240''>register</span>
  <span m=''753650''>operations</span> <span m=''754180''>themselves.</span> </p><p><span
  m=''759730''>Ok, that''s</span> <span m=''760200''>a, a</span> <span m=''760320''>zeroth-order</span>
  <span m=''761030''>compiler,</span> <span m=''761830''>but</span> <span m=''761970''>it</span>
  <span m=''762090''>is</span> <span m=''762210''>a</span> <span m=''762310''>wretched,</span>
  <span m=''762970''>wretched</span> <span m=''763370''>compiler.</span> <span m=''764550''>It''s</span>
  <span m=''764640''>really</span> <span m=''764930''>dumb.</span> <span m=''767200''>Let''s--let''s</span>
  <span m=''767900''>go</span> <span m=''768000''>back</span> <span m=''768240''>and,
  and</span> <span m=''770020''>look</span> <span m=''770180''>at</span> <span m=''770280''>this</span>
  <span m=''770390''>overhead.</span> <span m=''772040''>So</span> <span m=''772310''>look</span>
  <span m=''772460''>at</span> <span m=''772660''>look</span> <span m=''772790''>at</span>
  <span m=''772930''>some</span> <span m=''773100''>of</span> <span m=''773160''>the</span>
  <span m=''773580''>operations</span> <span m=''774170''>this</span> <span m=''774330''>thing</span>
  <span m=''774480''>is</span> <span m=''774600''>doing.</span> <span m=''776020''>We''re</span>
  <span m=''776110''>supposedly</span> <span m=''779790''>looking</span> <span m=''780130''>at</span>
  <span m=''780220''>the</span> <span m=''780340''>operations</span> <span m=''780950''>and</span>
  <span m=''781030''>interpreting</span> <span m=''781560''>f</span> <span m=''781720''>of</span>
  <span m=''781890''>x.</span> <span m=''783710''>Now,</span> <span m=''784000''>look</span>
  <span m=''784080''>here</span> <span m=''784150''>what</span> <span m=''784220''>it''s</span>
  <span m=''784410''>doing.</span> <span m=''785220''>For</span> <span m=''785350''>example,</span>
  <span m=''785730''>here</span> <span m=''787220''>it</span> <span m=''787350''>assigns</span>
  <span m=''787870''>to</span> <span m=''788000''>exp</span> <span m=''790220''>the</span>
  <span m=''790360''>operator</span> <span m=''791110''>in</span> <span m=''791365''>fetch</span>
  <span m=''791492''>of</span> <span m=''791620''>exp.</span> <span m=''793850''>But</span>
  <span m=''794000''>see,</span> <span m=''794090''>there''s</span> <span m=''794230''>no</span>
  <span m=''794330''>reason</span> <span m=''794600''>to</span> <span m=''794700''>do</span>
  <span m=''794880''>that,</span> <span m=''795180''>because this is--</span> <span
  m=''796290''>the</span> <span m=''796420''>compiler</span> <span m=''796980''>knows</span>
  <span m=''797600''>that</span> <span m=''797840''>the</span> <span m=''799060''>operator,</span>
  <span m=''799650''>fetch</span> <span m=''799910''>of</span> <span m=''800020''>exp,</span>
  <span m=''800850''>is</span> <span m=''801090''>f</span> <span m=''801290''>right</span>
  <span m=''801480''>here.</span> </p><p><span m=''803310''>So</span> <span m=''803460''>there''s</span>
  <span m=''803630''>no</span> <span m=''803770''>reason</span> <span m=''804020''>why</span>
  <span m=''804160''>this</span> <span m=''804330''>instruction</span> <span m=''804800''>should</span>
  <span m=''804960''>say</span> <span m=''805170''>that.</span> <span m=''805850''>It</span>
  <span m=''805970''>should</span> <span m=''806120''>say,</span> <span m=''807190''>we''ll</span>
  <span m=''807290''>assign</span> <span m=''807660''>to</span> <span m=''807790''>exp,</span>
  <span m=''808560''>f.</span> <span m=''809580''>Or</span> <span m=''809710''>in</span>
  <span m=''809780''>fact,</span> <span m=''810050''>you</span> <span m=''810120''>don''t</span>
  <span m=''810240''>need</span> <span m=''810420''>exp</span> <span m=''810580''>at</span>
  <span m=''810740''>all.</span> <span m=''812000''>There''s</span> <span m=''812140''>no</span>
  <span m=''812230''>reason</span> <span m=''812500''>it</span> <span m=''812560''>should</span>
  <span m=''812690''>have</span> <span m=''812860''>exp</span> <span m=''813020''>at</span>
  <span m=''813180''>all.</span> <span m=''813670''>What, what</span> <span m=''813970''>did</span>
  <span m=''814180''>exp</span> <span m=''814520''>get</span> <span m=''814670''>used</span>
  <span m=''814970''>for?</span> <span m=''815170''>Well,</span> <span m=''815420''>if</span>
  <span m=''815465''>we</span> <span m=''815510''>come</span> <span m=''815700''>down</span>
  <span m=''815900''>here,</span> <span m=''820910''>we''re</span> <span m=''821010''>going</span>
  <span m=''821080''>to</span> <span m=''821160''>assign</span> <span m=''821530''>to</span>
  <span m=''821650''>val,</span> <span m=''823190''>look</span> <span m=''823470''>up</span>
  <span m=''823620''>the</span> <span m=''823730''>stuff</span> <span m=''824050''>in</span>
  <span m=''824370''>exp</span> <span m=''826390''>in</span> <span m=''826500''>the</span>
  <span m=''826620''>environment.</span> <span m=''828620''>So</span> <span m=''828880''>what</span>
  <span m=''828950''>we</span> <span m=''829020''>really</span> <span m=''829280''>should</span>
  <span m=''829440''>do</span> <span m=''829530''>is</span> <span m=''829640''>get</span>
  <span m=''829800''>rid</span> <span m=''829930''>of</span> <span m=''830030''>the</span>
  <span m=''830140''>exp</span> <span m=''830380''>register</span> <span m=''830800''>altogether,</span>
  <span m=''831630''>and</span> <span m=''831780''>just</span> <span m=''831950''>change</span>
  <span m=''832240''>this</span> <span m=''832440''>instruction</span> <span m=''832695''>to</span>
  <span m=''832950''>say,</span> <span m=''833290''>assign</span> <span m=''833660''>to</span>
  <span m=''833940''>val,</span> <span m=''834570''>look</span> <span m=''834820''>up</span>
  <span m=''834970''>the</span> <span m=''835090''>variable</span> <span m=''835590''>value</span>
  <span m=''836320''>of</span> <span m=''836560''>the</span> <span m=''836630''>symbol</span>
  <span m=''837060''>f</span> <span m=''837600''>in</span> <span m=''837700''>the</span>
  <span m=''837810''>environment.</span> </p><p><span m=''841100''>Similarly,</span>
  <span m=''842660''>back</span> <span m=''842890''>up</span> <span m=''843010''>here,</span>
  <span m=''843120''>we</span> <span m=''843210''>don''t</span> <span m=''843340''>need</span>
  <span m=''843490''>unev</span> <span m=''843830''>at</span> <span m=''843910''>all,</span>
  <span m=''844800''>because</span> <span m=''845110''>we</span> <span m=''845240''>know</span>
  <span m=''846320''>what</span> <span m=''846520''>the</span> <span m=''846650''>operands</span>
  <span m=''847050''>of</span> <span m=''847270''>fetch</span> <span m=''847480''>of</span>
  <span m=''847660''>exp</span> <span m=''847960''>are</span> <span m=''848260''>for</span>
  <span m=''848360''>this</span> <span m=''848540''>piece</span> <span m=''848770''>of</span>
  <span m=''848860''>code.</span> <span m=''849150''>It''s</span> <span m=''849870''>the,
  it''s the</span> <span m=''849950''>list</span> <span m=''850210''>x.</span> <span
  m=''853270''>So</span> <span m=''853490''>in</span> <span m=''853560''>some</span>
  <span m=''853720''>sense,</span> <span m=''856330''>you</span> <span m=''856460''>don''t</span>
  <span m=''856620''>want</span> <span m=''856820''>unev</span> <span m=''858420''>and</span>
  <span m=''858570''>exp</span> <span m=''858940''>at</span> <span m=''859290''>all.</span>
  <span m=''859660''>See,</span> <span m=''859820''>what</span> <span m=''859990''>they</span>
  <span m=''860120''>really are</span> <span m=''860450''>in</span> <span m=''860700''>some</span>
  <span m=''860830''>sense,</span> <span m=''861060''>those</span> <span m=''861270''>aren''t</span>
  <span m=''862690''>registers</span> <span m=''863380''>of</span> <span m=''863500''>the</span>
  <span m=''863630''>actual</span> <span m=''863990''>machine</span> <span m=''864330''>that''s</span>
  <span m=''864490''>supposed</span> <span m=''864810''>to</span> <span m=''864920''>run.</span>
  <span m=''865230''>Those</span> <span m=''865610''>are</span> <span m=''865720''>registers</span>
  <span m=''866530''>that</span> <span m=''866760''>have</span> <span m=''866960''>to</span>
  <span m=''867070''>do</span> <span m=''867240''>with</span> <span m=''867380''>arranging</span>
  <span m=''867890''>the</span> <span m=''867990''>thing</span> <span m=''868180''>that</span>
  <span m=''868320''>can</span> <span m=''868440''>simulate</span> <span m=''868920''>that</span>
  <span m=''869100''>machine.</span> </p><p><span m=''870760''>So</span> <span m=''870940''>they''re</span>
  <span m=''871120''>always</span> <span m=''871560''>going</span> <span m=''871640''>to</span>
  <span m=''871720''>hold</span> <span m=''872880''>expressions</span> <span m=''874060''>which,</span>
  <span m=''874780''>from</span> <span m=''874890''>the</span> <span m=''875010''>compiler''s</span>
  <span m=''875560''>point</span> <span m=''875770''>of</span> <span m=''875870''>view,</span>
  <span m=''875980''>are</span> <span m=''876050''>just</span> <span m=''876260''>constants,</span>
  <span m=''876930''>so</span> <span m=''877100''>can</span> <span m=''877210''>be</span>
  <span m=''877330''>put</span> <span m=''877500''>right</span> <span m=''877700''>into</span>
  <span m=''877840''>the</span> <span m=''877980''>code.</span> <span m=''879510''>So</span>
  <span m=''879650''>you</span> <span m=''879790''>can</span> <span m=''879930''>forget</span>
  <span m=''880230''>about</span> <span m=''880460''>all</span> <span m=''880610''>the</span>
  <span m=''880730''>operations</span> <span m=''881340''>worrying</span> <span m=''881630''>about</span>
  <span m=''881850''>exp</span> <span m=''882200''>and</span> <span m=''882350''>unev</span>
  <span m=''882560''>and</span> <span m=''882665''>just</span> <span m=''882770''>use</span>
  <span m=''882960''>those</span> <span m=''883160''>constants.</span> <span m=''884000''>Similarly,</span>
  <span m=''885800''>again,</span> <span m=''885990''>if</span> <span m=''886080''>we</span>
  <span m=''886160''>go, go</span> <span m=''887050''>back</span> <span m=''887260''>and</span>
  <span m=''887370''>look</span> <span m=''887540''>here,</span> <span m=''888050''>there</span>
  <span m=''888170''>are</span> <span m=''888200''>things</span> <span m=''888510''>like</span>
  <span m=''889160''>assign</span> <span m=''889680''>to</span> <span m=''889780''>continue</span>
  <span m=''890370''>eval-args.</span> <span m=''893890''>Now,</span> <span m=''894000''>that</span>
  <span m=''894150''>has</span> <span m=''894310''>nothing</span> <span m=''894590''>to</span>
  <span m=''894670''>do</span> <span m=''894800''>with</span> <span m=''894940''>anything.</span>
  <span m=''895440''>That</span> <span m=''895730''>was</span> <span m=''896020''>just</span>
  <span m=''896300''>the</span> <span m=''896810''>evaluator</span> <span m=''897980''>keeping</span>
  <span m=''898440''>track</span> <span m=''898780''>of</span> <span m=''898890''>where</span>
  <span m=''899090''>it</span> <span m=''899280''>should</span> <span m=''899550''>go</span>
  <span m=''899750''>next,</span> <span m=''902950''>to</span> <span m=''903060''>evaluate</span>
  <span m=''903530''>the</span> <span m=''903630''>arguments</span> <span m=''904810''>in</span>
  <span m=''904950''>some, in some</span> <span m=''905150''>application.</span> </p><p><span
  m=''906920''>But</span> <span m=''907050''>of</span> <span m=''907110''>course,</span>
  <span m=''907280''>that''s</span> <span m=''907460''>irrelevant</span> <span m=''907960''>to</span>
  <span m=''908030''>the</span> <span m=''908130''>compiler,</span> <span m=''908690''>because
  you--</span> <span m=''911470''>the</span> <span m=''911920''>analysis</span> <span
  m=''912520''>phase</span> <span m=''912800''>will</span> <span m=''912890''>have</span>
  <span m=''912980''>already</span> <span m=''913380''>done</span> <span m=''913600''>that.</span>
  <span m=''915220''>So</span> <span m=''915420''>this</span> <span m=''915620''>is</span>
  <span m=''915730''>completely</span> <span m=''916210''>irrelevant.</span> <span
  m=''917680''>So</span> <span m=''917940''>a</span> <span m=''918020''>lot</span>
  <span m=''918320''>of</span> <span m=''918470''>these, these</span> <span m=''918930''>assignments</span>
  <span m=''919400''>to</span> <span m=''919500''>continue</span> <span m=''919970''>have</span>
  <span m=''920170''>not</span> <span m=''920860''>to</span> <span m=''921080''>do</span>
  <span m=''921270''>where</span> <span m=''921460''>the</span> <span m=''922920''>running</span>
  <span m=''923230''>machine</span> <span m=''923610''>is</span> <span m=''923690''>supposed</span>
  <span m=''923880''>to</span> <span m=''924070''>continue</span> <span m=''924510''>in</span>
  <span m=''924610''>keeping</span> <span m=''924880''>track</span> <span m=''925180''>of</span>
  <span m=''925280''>its</span> <span m=''925470''>state.</span> <span m=''926120''>It</span>
  <span m=''926250''>has</span> <span m=''926440''>to, to</span> <span m=''926530''>do</span>
  <span m=''926680''>with</span> <span m=''926810''>where</span> <span m=''926950''>the</span>
  <span m=''927120''>evaluator</span> <span m=''927465''>analysis</span> <span m=''928220''>should</span>
  <span m=''928380''>continue,</span> <span m=''928780''>and</span> <span m=''928850''>those</span>
  <span m=''929050''>are</span> <span m=''929120''>completely</span> <span m=''929600''>irrelevant.</span>
  <span m=''930080''>So</span> <span m=''930170''>we</span> <span m=''930280''>can</span>
  <span m=''930410''>get</span> <span m=''930590''>rid</span> <span m=''930730''>of</span>
  <span m=''930800''>them.</span> </p><p><span m=''944330''>Ok, well,</span> <span
  m=''944500''>if</span> <span m=''944600''>we, if we</span> <span m=''945120''>simply</span>
  <span m=''945500''>do</span> <span m=''945660''>that,</span> <span m=''946240''>make</span>
  <span m=''946420''>those</span> <span m=''946620''>kinds</span> <span m=''946880''>of</span>
  <span m=''946990''>optimizations,</span> <span m=''947740''>get</span> <span m=''947920''>rid,
  get rid</span> <span m=''948100''>of</span> <span m=''950170''>worrying</span> <span
  m=''950510''>about</span> <span m=''950810''>exp</span> <span m=''951200''>and</span>
  <span m=''951380''>unev,</span> <span m=''951760''>and</span> <span m=''951950''>get</span>
  <span m=''952130''>rid</span> <span m=''952290''>of</span> <span m=''953850''>these</span>
  <span m=''954050''>irrelevant</span> <span m=''954620''>register</span> <span m=''955030''>assignments</span>
  <span m=''955490''>to</span> <span m=''955590''>continue,</span> <span m=''957210''>then</span>
  <span m=''957470''>we</span> <span m=''957580''>can</span> <span m=''957720''>take</span>
  <span m=''958740''>this</span> <span m=''959040''>literal</span> <span m=''959410''>code,</span>
  <span m=''961400''>these</span> <span m=''961630''>sort</span> <span m=''961785''>of</span>
  <span m=''961940''>19</span> <span m=''962350''>instructions</span> <span m=''962900''>that</span>
  <span m=''963060''>the, that the</span> <span m=''964640''>evaluator</span> <span
  m=''965370''>would</span> <span m=''965500''>have</span> <span m=''965690''>done,</span>
  <span m=''967040''>and</span> <span m=''967190''>then</span> <span m=''967300''>replace</span>
  <span m=''967720''>them.</span> <span m=''968540''>Let''s</span> <span m=''968740''>look</span>
  <span m=''968860''>at</span> <span m=''968920''>the, at the</span> <span m=''969580''>slide.</span>
  <span m=''973490''>Replace them by--we</span> <span m=''973860''>get</span> <span
  m=''974010''>rid</span> <span m=''974130''>of</span> <span m=''974230''>about</span>
  <span m=''974500''>half</span> <span m=''974820''>of</span> <span m=''974960''>them.</span>
  <span m=''978370''>And</span> <span m=''978640''>again,</span> <span m=''978880''>this</span>
  <span m=''979030''>is</span> <span m=''979120''>just</span> <span m=''979290''>sort</span>
  <span m=''979440''>of</span> <span m=''979860''>filtering</span> <span m=''981140''>what</span>
  <span m=''981310''>the</span> <span m=''981470''>evaluator</span> <span m=''982010''>would</span>
  <span m=''982110''>have</span> <span m=''982210''>done</span> <span m=''982750''>by</span>
  <span m=''982910''>getting</span> <span m=''983200''>rid</span> <span m=''983330''>of</span>
  <span m=''983410''>the</span> <span m=''983510''>irrelevant</span> <span m=''984060''>stuff.</span>
  </p><p><span m=''985200''>And</span> <span m=''985360''>you</span> <span m=''985440''>see,</span>
  <span m=''985600''>for</span> <span m=''985790''>instance,</span> <span m=''988090''>here
  the--where</span> <span m=''988260''>the</span> <span m=''988760''>evaluator</span>
  <span m=''989450''>said,</span> <span m=''989700''>assign</span> <span m=''990100''>val,</span>
  <span m=''990370''>look</span> <span m=''990540''>up</span> <span m=''990690''>variable</span>
  <span m=''991180''>value,</span> <span m=''991600''>fetch</span> <span m=''992100''>of</span>
  <span m=''992460''>exp,</span> <span m=''992570''>here</span> <span m=''992760''>we</span>
  <span m=''992950''>have</span> <span m=''993140''>put</span> <span m=''993310''>in</span>
  <span m=''993400''>the</span> <span m=''993490''>constant</span> <span m=''993920''>f.</span>
  <span m=''995470''>Here</span> <span m=''995610''>we''ve</span> <span m=''995760''>put</span>
  <span m=''995950''>in</span> <span m=''996060''>the</span> <span m=''996140''>constant</span>
  <span m=''996580''>x.</span> <span m=''999770''>So</span> <span m=''1000220''>there''s
  a, there''s</span> <span m=''1001170''>a</span> <span m=''1001230''>little</span>
  <span m=''1001450''>better</span> <span m=''1001720''>compiler.</span> <span m=''1003860''>It''s</span>
  <span m=''1005970''>still</span> <span m=''1006140''>pretty</span> <span m=''1006450''>dumb.</span>
  <span m=''1007930''>It''s</span> <span m=''1008100''>still</span> <span m=''1008280''>doing</span>
  <span m=''1008520''>a</span> <span m=''1008580''>lot</span> <span m=''1008700''>of</span>
  <span m=''1008820''>dumb</span> <span m=''1009070''>things.</span> <span m=''1010560''>Again,</span>
  <span m=''1010760''>if</span> <span m=''1010850''>we</span> <span m=''1010930''>go</span>
  <span m=''1011370''>look</span> <span m=''1011500''>at</span> <span m=''1011620''>the</span>
  <span m=''1011680''>slide</span> <span m=''1012040''>again,</span> <span m=''1012390''>look</span>
  <span m=''1012625''>at</span> <span m=''1012860''>the</span> <span m=''1013140''>very</span>
  <span m=''1013290''>beginning</span> <span m=''1013650''>here,</span> <span m=''1016360''>we</span>
  <span m=''1016470''>see</span> <span m=''1016600''>a</span> <span m=''1016860''>save</span>
  <span m=''1017190''>the</span> <span m=''1017420''>environment,</span> <span m=''1019430''>assign</span>
  <span m=''1020150''>something</span> <span m=''1020540''>to</span> <span m=''1020640''>the</span>
  <span m=''1020750''>val</span> <span m=''1021010''>register,</span> <span m=''1021920''>and</span>
  <span m=''1022080''>restore</span> <span m=''1022430''>the</span> <span m=''1022580''>environment.</span>
  </p><p><span m=''1023430''>Where''d</span> <span m=''1023590''>that</span> <span
  m=''1023820''>come</span> <span m=''1024060''>from?</span> <span m=''1025030''>That</span>
  <span m=''1025180''>came</span> <span m=''1025369''>from</span> <span m=''1025490''>the</span>
  <span m=''1025619''>evaluator</span> <span m=''1026390''>back</span> <span m=''1026650''>here</span>
  <span m=''1026829''>saying,</span> <span m=''1027150''>oh,</span> <span m=''1027349''>I''m</span>
  <span m=''1028050''>in</span> <span m=''1028200''>the</span> <span m=''1028290''>middle</span>
  <span m=''1028630''>of</span> <span m=''1028810''>evaluating</span> <span m=''1029140''>an</span>
  <span m=''1029470''>application.</span> <span m=''1031160''>So</span> <span m=''1031349''>I''m</span>
  <span m=''1031470''>going</span> <span m=''1031560''>to</span> <span m=''1031650''>recursively</span>
  <span m=''1032410''>call</span> <span m=''1033680''>eval</span> <span m=''1034089''>dispatch.</span>
  <span m=''1035940''>So</span> <span m=''1036170''>I''d</span> <span m=''1036260''>better</span>
  <span m=''1036619''>save</span> <span m=''1036950''>the</span> <span m=''1037040''>thing</span>
  <span m=''1037260''>I''m</span> <span m=''1037359''>going</span> <span m=''1037430''>to</span>
  <span m=''1037500''>need</span> <span m=''1037690''>later,</span> <span m=''1038000''>which</span>
  <span m=''1038170''>is</span> <span m=''1038270''>the</span> <span m=''1038400''>environment.</span>
  <span m=''1039849''>This</span> <span m=''1040119''>was</span> <span m=''1040280''>the</span>
  <span m=''1040390''>result</span> <span m=''1040890''>of</span> <span m=''1040940''>recursively</span>
  <span m=''1041609''>calling</span> <span m=''1041960''>eval</span> <span m=''1042240''>dispatch.</span>
  <span m=''1043520''>It</span> <span m=''1043609''>was</span> <span m=''1043710''>evaluating</span>
  <span m=''1044319''>the</span> <span m=''1044400''>symbol</span> <span m=''1044800''>f</span>
  <span m=''1045030''>in</span> <span m=''1045119''>that</span> <span m=''1045300''>case.</span>
  </p><p><span m=''1046540''>Then</span> <span m=''1046680''>it</span> <span m=''1046790''>came</span>
  <span m=''1047170''>back</span> <span m=''1047490''>from</span> <span m=''1047589''>eval</span>
  <span m=''1047900''>dispatch,</span> <span m=''1048349''>restored</span> <span m=''1048770''>the</span>
  <span m=''1048900''>environment.</span> <span m=''1051380''>But</span> <span m=''1051620''>in</span>
  <span m=''1051760''>fact,</span> <span m=''1052600''>the</span> <span m=''1052720''>actual</span>
  <span m=''1053170''>thing</span> <span m=''1053380''>it</span> <span m=''1053450''>ended</span>
  <span m=''1053740''>up</span> <span m=''1053870''>doing</span> <span m=''1055050''>in</span>
  <span m=''1055180''>the</span> <span m=''1055290''>evaluation</span> <span m=''1055970''>is</span>
  <span m=''1056080''>not</span> <span m=''1056500''>going</span> <span m=''1056560''>to</span>
  <span m=''1056620''>hurt</span> <span m=''1056810''>the</span> <span m=''1056920''>environment</span>
  <span m=''1057350''>at</span> <span m=''1057520''>all.</span> <span m=''1058740''>So</span>
  <span m=''1058880''>there''s</span> <span m=''1059090''>no</span> <span m=''1059260''>reason</span>
  <span m=''1059610''>to</span> <span m=''1059700''>be</span> <span m=''1059800''>saving</span>
  <span m=''1060220''>the</span> <span m=''1060350''>environment</span> <span m=''1060840''>and</span>
  <span m=''1060890''>restoring</span> <span m=''1061370''>the</span> <span m=''1061470''>environment</span>
  <span m=''1061940''>here.</span> <span m=''1066020''>Similarly,</span> <span m=''1069770''>here</span>
  <span m=''1069935''>I''m</span> <span m=''1070100''>saving</span> <span m=''1070450''>the</span>
  <span m=''1070570''>argument</span> <span m=''1071030''>list.</span> <span m=''1073180''>That''s</span>
  <span m=''1073380''>a</span> <span m=''1073430''>piece</span> <span m=''1073690''>of</span>
  <span m=''1073850''>the</span> <span m=''1074560''>argument</span> <span m=''1074960''>evaluation</span>
  <span m=''1075320''>loop,</span> <span m=''1075770''>saving</span> <span m=''1076090''>the</span>
  <span m=''1076190''>argument</span> <span m=''1076560''>list,</span> <span m=''1077140''>and</span>
  <span m=''1077270''>here</span> <span m=''1077430''>you</span> <span m=''1077540''>restore</span>
  <span m=''1077970''>it.</span> </p><p><span m=''1078090''>But</span> <span m=''1078220''>the</span>
  <span m=''1078340''>actual</span> <span m=''1079060''>thing</span> <span m=''1079400''>that</span>
  <span m=''1079540''>you</span> <span m=''1079660''>ended</span> <span m=''1079920''>up</span>
  <span m=''1080030''>doing</span> <span m=''1080890''>didn''t</span> <span m=''1081150''>trash</span>
  <span m=''1081510''>the</span> <span m=''1081650''>argument</span> <span m=''1082020''>list.</span>
  <span m=''1082810''>So</span> <span m=''1082970''>there</span> <span m=''1083090''>was</span>
  <span m=''1083200''>no</span> <span m=''1083290''>reason</span> <span m=''1083610''>to</span>
  <span m=''1083700''>save</span> <span m=''1083880''>it.</span> <span m=''1088690''>So</span>
  <span m=''1088860''>another</span> <span m=''1089130''>way</span> <span m=''1089290''>to</span>
  <span m=''1092140''>say, another way to say</span> <span m=''1092390''>that</span>
  <span m=''1093800''>is</span> <span m=''1094050''>that</span> <span m=''1094290''>the,
  the</span> <span m=''1096600''>evaluator</span> <span m=''1097160''>has</span> <span
  m=''1097390''>to</span> <span m=''1097480''>be</span> <span m=''1097790''>maximally</span>
  <span m=''1098430''>pessimistic,</span> <span m=''1099860''>because as far</span>
  <span m=''1100340''>from</span> <span m=''1100500''>its</span> <span m=''1100700''>point</span>
  <span m=''1100920''>of</span> <span m=''1100980''>view</span> <span m=''1101130''>it''s</span>
  <span m=''1101250''>just</span> <span m=''1101430''>going</span> <span m=''1101710''>off</span>
  <span m=''1101880''>to</span> <span m=''1102050''>evaluate</span> <span m=''1102680''>something.</span>
  <span m=''1103180''>So</span> <span m=''1103340''>it</span> <span m=''1103420''>better</span>
  <span m=''1103700''>save</span> <span m=''1103970''>what</span> <span m=''1104090''>it''s</span>
  <span m=''1104250''>going</span> <span m=''1104320''>to</span> <span m=''1104390''>need</span>
  <span m=''1104570''>later.</span> </p><p><span m=''1106200''>But</span> <span m=''1106340''>once</span>
  <span m=''1106520''>you''ve</span> <span m=''1106650''>done</span> <span m=''1106860''>the</span>
  <span m=''1107190''>analysis,</span> <span m=''1107830''>the</span> <span m=''1107930''>compiler</span>
  <span m=''1108240''>is</span> <span m=''1108550''>in</span> <span m=''1108640''>a</span>
  <span m=''1108700''>position</span> <span m=''1109320''>to</span> <span m=''1109460''>say,</span>
  <span m=''1109620''>well,</span> <span m=''1109810''>what</span> <span m=''1110020''>actually</span>
  <span m=''1110510''>did</span> <span m=''1110650''>I</span> <span m=''1110730''>need</span>
  <span m=''1110880''>to</span> <span m=''1111020''>save?</span> <span m=''1112140''>And
  doesn''t need to do any--</span> <span m=''1112225''>it</span> <span m=''1112310''>doesn''t</span>
  <span m=''1112530''>need</span> <span m=''1112700''>to</span> <span m=''1113900''>be</span>
  <span m=''1114110''>as</span> <span m=''1115410''>careful</span> <span m=''1115820''>as</span>
  <span m=''1115940''>the</span> <span m=''1116750''>evaluator,</span> <span m=''1117320''>because</span>
  <span m=''1117445''>it</span> <span m=''1117570''>knows</span> <span m=''1117840''>what</span>
  <span m=''1117970''>it</span> <span m=''1118060''>actually</span> <span m=''1118440''>needs.</span>
  <span m=''1119950''>Well,</span> <span m=''1120040''>in</span> <span m=''1120130''>any</span>
  <span m=''1120230''>case,</span> <span m=''1120440''>if</span> <span m=''1120530''>we</span>
  <span m=''1120620''>do</span> <span m=''1120760''>that</span> <span m=''1122610''>and</span>
  <span m=''1122990''>eliminate</span> <span m=''1123490''>all</span> <span m=''1123720''>those</span>
  <span m=''1124240''>redundant</span> <span m=''1124595''>saves</span> <span m=''1124950''>and</span>
  <span m=''1125030''>restores,</span> <span m=''1126130''>then</span> <span m=''1126450''>we</span>
  <span m=''1127950''>can</span> <span m=''1128110''>get</span> <span m=''1128225''>it</span>
  <span m=''1128340''>down</span> <span m=''1128550''>to</span> <span m=''1128640''>this.</span>
  <span m=''1129400''>And</span> <span m=''1129720''>you</span> <span m=''1129920''>see</span>
  <span m=''1130120''>there</span> <span m=''1130195''>are</span> <span m=''1130270''>actually</span>
  <span m=''1130780''>only</span> <span m=''1131070''>three</span> <span m=''1132130''>instructions</span>
  <span m=''1132690''>that</span> <span m=''1132810''>we</span> <span m=''1132950''>actually</span>
  <span m=''1133320''>need,</span> <span m=''1134090''>down</span> <span m=''1134310''>from</span>
  <span m=''1134440''>the</span> <span m=''1134580''>initial</span> <span m=''1134950''>11</span>
  <span m=''1135280''>or</span> <span m=''1135380''>so,</span> <span m=''1135990''>or</span>
  <span m=''1136130''>the</span> <span m=''1136230''>initial</span> <span m=''1137430''>20</span>
  <span m=''1137760''>or</span> <span m=''1137830''>so</span> <span m=''1138060''>in</span>
  <span m=''1138140''>the</span> <span m=''1138220''>original</span> <span m=''1138550''>one.</span>
  </p><p><span m=''1140070''>And</span> <span m=''1140240''>that''s</span> <span m=''1140420''>just</span>
  <span m=''1140580''>saying,</span> <span m=''1141160''>of</span> <span m=''1141380''>those</span>
  <span m=''1141920''>register</span> <span m=''1142410''>operations,</span> <span
  m=''1143260''>which</span> <span m=''1143540''>ones</span> <span m=''1143780''>did</span>
  <span m=''1143910''>we</span> <span m=''1144080''>actually</span> <span m=''1144520''>need?</span>
  <span m=''1149490''>Let</span> <span m=''1149745''>me</span> <span m=''1150000''>just</span>
  <span m=''1150280''>sort</span> <span m=''1150326''>of</span> <span m=''1150420''>summarize</span>
  <span m=''1150685''>that</span> <span m=''1150950''>in</span> <span m=''1151120''>another</span>
  <span m=''1151450''>way,</span> <span m=''1151710''>just</span> <span m=''1151870''>to</span>
  <span m=''1151950''>show</span> <span m=''1152110''>you in</span> <span m=''1152440''>a</span>
  <span m=''1152480''>little</span> <span m=''1152760''>better</span> <span m=''1152980''>picture.</span>
  <span m=''1156010''>Here''s</span> <span m=''1156190''>a</span> <span m=''1156250''>picture</span>
  <span m=''1156650''>of</span> <span m=''1156740''>starting--</span> <span m=''1158690''>This</span>
  <span m=''1159020''>is</span> <span m=''1159130''>looking</span> <span m=''1159450''>at</span>
  <span m=''1159560''>all</span> <span m=''1159670''>the</span> <span m=''1159740''>saves</span>
  <span m=''1160110''>and</span> <span m=''1160210''>restores.</span> <span m=''1163770''>So</span>
  <span m=''1163860''>here''s</span> <span m=''1164040''>the</span> <span m=''1164110''>expression,</span>
  <span m=''1164560''>f</span> <span m=''1164730''>of</span> <span m=''1164910''>x,</span>
  <span m=''1165380''>and</span> <span m=''1165530''>then</span> <span m=''1165670''>this</span>
  <span m=''1165820''>traces</span> <span m=''1166300''>through,</span> <span m=''1166920''>on</span>
  <span m=''1167020''>the</span> <span m=''1167120''>bottom</span> <span m=''1167430''>here,</span>
  <span m=''1168330''>the</span> <span m=''1168900''>various</span> <span m=''1169590''>places</span>
  <span m=''1170630''>in</span> <span m=''1170790''>the</span> <span m=''1170940''>evaluator</span>
  <span m=''1174930''>that</span> <span m=''1175260''>were</span> <span m=''1175390''>passed</span>
  <span m=''1176490''>when</span> <span m=''1176630''>the</span> <span m=''1176680''>evaluation</span>
  <span m=''1177310''>happened.</span> </p><p><span m=''1178160''>And</span> <span
  m=''1178280''>then</span> <span m=''1178400''>here, here</span> <span m=''1178580''>you</span>
  <span m=''1179040''>see</span> <span m=''1179260''>arrows.</span> <span m=''1180250''>Arrow</span>
  <span m=''1180520''>down</span> <span m=''1180880''>means</span> <span m=''1181100''>register</span>
  <span m=''1181580''>saved.</span> <span m=''1182320''>So</span> <span m=''1182490''>the</span>
  <span m=''1182660''>first</span> <span m=''1182840''>thing</span> <span m=''1182970''>that</span>
  <span m=''1183100''>happened</span> <span m=''1183460''>is</span> <span m=''1183560''>the</span>
  <span m=''1183690''>environment</span> <span m=''1184190''>got</span> <span m=''1184390''>saved.</span>
  <span m=''1186860''>And</span> <span m=''1187030''>over</span> <span m=''1187210''>here,</span>
  <span m=''1187370''>the</span> <span m=''1187480''>environment</span> <span m=''1187910''>got</span>
  <span m=''1188030''>restored.</span> <span m=''1192380''>And these--</span> <span
  m=''1192520''>so</span> <span m=''1192630''>there</span> <span m=''1192710''>are</span>
  <span m=''1192790''>all</span> <span m=''1192865''>the</span> <span m=''1192940''>pairs</span>
  <span m=''1193270''>of</span> <span m=''1193320''>stack</span> <span m=''1193670''>operations.</span>
  <span m=''1196220''>Now,</span> <span m=''1196460''>if</span> <span m=''1196540''>you</span>
  <span m=''1196630''>go</span> <span m=''1196750''>ahead</span> <span m=''1197070''>and</span>
  <span m=''1197210''>say,</span> <span m=''1198130''>well,</span> <span m=''1198290''>let''s</span>
  <span m=''1198910''>remember</span> <span m=''1199370''>that we don''t--that</span>
  <span m=''1200280''>unev,</span> <span m=''1200900''>for</span> <span m=''1201090''>instance,</span>
  <span m=''1201460''>is</span> <span m=''1201570''>a</span> <span m=''1201640''>completely</span>
  <span m=''1202070''>useless</span> <span m=''1202500''>register.</span> <span m=''1207550''>And</span>
  <span m=''1207950''>if</span> <span m=''1208040''>we</span> <span m=''1208120''>use</span>
  <span m=''1208300''>the</span> <span m=''1208390''>constant</span> <span m=''1208810''>structure</span>
  <span m=''1209140''>of</span> <span m=''1209210''>the</span> <span m=''1209290''>code,</span>
  <span m=''1209550''>well,</span> <span m=''1209820''>we</span> <span m=''1209980''>don''t</span>
  <span m=''1210170''>need, we don''t need</span> <span m=''1210840''>to</span> <span
  m=''1210910''>save</span> <span m=''1211230''>unev.</span> <span m=''1211470''>We</span>
  <span m=''1211530''>don''t</span> <span m=''1211650''>need</span> <span m=''1211770''>unev</span>
  <span m=''1212020''>at</span> <span m=''1212120''>all.</span> </p><p><span m=''1216220''>And</span>
  <span m=''1216460''>then,</span> <span m=''1216600''>depending</span> <span m=''1217020''>on</span>
  <span m=''1217100''>how</span> <span m=''1217220''>we</span> <span m=''1217330''>set</span>
  <span m=''1217500''>up</span> <span m=''1217620''>the</span> <span m=''1217710''>discipline</span>
  <span m=''1218670''>of the--of</span> <span m=''1219290''>calling</span> <span m=''1221010''>other</span>
  <span m=''1221210''>things</span> <span m=''1221430''>that</span> <span m=''1221480''>apply,</span>
  <span m=''1221800''>we</span> <span m=''1221970''>may</span> <span m=''1222130''>or</span>
  <span m=''1222210''>may</span> <span m=''1222360''>not</span> <span m=''1222610''>need</span>
  <span m=''1222740''>to</span> <span m=''1222870''>save</span> <span m=''1223130''>continue.</span>
  <span m=''1227360''>That''s</span> <span m=''1227700''>the</span> <span m=''1227860''>first</span>
  <span m=''1228020''>step</span> <span m=''1228280''>I</span> <span m=''1228360''>did.</span>
  <span m=''1228800''>And</span> <span m=''1228960''>then</span> <span m=''1229070''>we</span>
  <span m=''1229180''>can</span> <span m=''1229310''>look</span> <span m=''1229480''>and</span>
  <span m=''1229570''>see</span> <span m=''1229720''>what''s</span> <span m=''1229930''>actually,
  what''s actually</span> <span m=''1232320''>needed.</span> <span m=''1232960''>See,</span>
  <span m=''1233470''>we don''t--</span> <span m=''1233590''>didn''t</span> <span
  m=''1234080''>really</span> <span m=''1234360''>need</span> <span m=''1234540''>to</span>
  <span m=''1234710''>save</span> <span m=''1234900''>env</span> <span m=''1236080''>or</span>
  <span m=''1236300''>cross-evaluating</span> <span m=''1237570''>f,</span> <span
  m=''1238110''>because</span> <span m=''1238260''>it</span> <span m=''1238330''>wouldn''t,
  it wouldn''t</span> <span m=''1239360''>trash</span> <span m=''1239710''>it.</span>
  <span m=''1240040''>So</span> <span m=''1240190''>if</span> <span m=''1240250''>we</span>
  <span m=''1240340''>take</span> <span m=''1240520''>advantage</span> <span m=''1240870''>of</span>
  <span m=''1240940''>that,</span> <span m=''1244190''>and</span> <span m=''1244390''>see</span>
  <span m=''1245990''>the</span> <span m=''1246130''>evaluation</span> <span m=''1246720''>of</span>
  <span m=''1246810''>f</span> <span m=''1247030''>here,</span> <span m=''1248610''>doesn''t</span>
  <span m=''1248910''>really</span> <span m=''1249220''>need</span> <span m=''1249540''>to</span>
  <span m=''1249740''>worry</span> <span m=''1250050''>about, about</span> <span m=''1251940''>hurting</span>
  <span m=''1252280''>env.</span> <span m=''1252485''>And</span> <span m=''1252690''>similarly,</span>
  <span m=''1253440''>the</span> <span m=''1253620''>evaluation</span> <span m=''1254110''>of</span>
  <span m=''1254210''>x</span> <span m=''1254500''>here,</span> <span m=''1257190''>when</span>
  <span m=''1257370''>the</span> <span m=''1257560''>evaluator</span> <span m=''1257925''>did</span>
  <span m=''1258290''>that</span> <span m=''1258650''>it</span> <span m=''1258740''>said,</span>
  <span m=''1258830''>oh,</span> <span m=''1258960''>I''d</span> <span m=''1259050''>better</span>
  <span m=''1259610''>preserve</span> <span m=''1260060''>the</span> <span m=''1260140''>function</span>
  <span m=''1260510''>register</span> <span m=''1261070''>around</span> <span m=''1261310''>that,</span>
  <span m=''1262120''>because</span> <span m=''1262240''>I</span> <span m=''1262280''>might</span>
  <span m=''1262500''>need</span> <span m=''1262650''>it</span> <span m=''1262740''>later.</span>
  <span m=''1263320''>And</span> <span m=''1263420''>I</span> <span m=''1263520''>better</span>
  <span m=''1263740''>preserve</span> <span m=''1264060''>the</span> <span m=''1264180''>argument</span>
  <span m=''1264590''>list.</span> </p><p><span m=''1267140''>Whereas</span> <span
  m=''1267350''>the</span> <span m=''1267430''>compiler</span> <span m=''1267760''>is</span>
  <span m=''1268090''>now</span> <span m=''1268280''>in</span> <span m=''1268360''>a</span>
  <span m=''1268400''>position</span> <span m=''1268810''>to</span> <span m=''1268900''>know,</span>
  <span m=''1269040''>well,</span> <span m=''1269180''>we</span> <span m=''1269280''>didn''t</span>
  <span m=''1269500''>really</span> <span m=''1269730''>need to save--</span> <span
  m=''1269930''>to</span> <span m=''1270540''>do</span> <span m=''1270690''>those</span>
  <span m=''1270880''>saves</span> <span m=''1271140''>and</span> <span m=''1271220''>restores.</span>
  <span m=''1272730''>So</span> <span m=''1272880''>in</span> <span m=''1272960''>fact,</span>
  <span m=''1273190''>all</span> <span m=''1273370''>of</span> <span m=''1273540''>the</span>
  <span m=''1273610''>stack</span> <span m=''1273950''>operations</span> <span m=''1275070''>done</span>
  <span m=''1275240''>by</span> <span m=''1275380''>the</span> <span m=''1275520''>evaluator</span>
  <span m=''1276360''>turned</span> <span m=''1276740''>out</span> <span m=''1277110''>to</span>
  <span m=''1277210''>be</span> <span m=''1277380''>unnecessary</span> <span m=''1278410''>or</span>
  <span m=''1278540''>overly</span> <span m=''1278900''>pessimistic.</span> <span
  m=''1279670''>And</span> <span m=''1279790''>the</span> <span m=''1279860''>compiler</span>
  <span m=''1280135''>is</span> <span m=''1280410''>in</span> <span m=''1280470''>a</span>
  <span m=''1280520''>position</span> <span m=''1280900''>to</span> <span m=''1280990''>know</span>
  <span m=''1281130''>that.</span> <span m=''1287470''>Well that''s</span> <span m=''1287710''>the</span>
  <span m=''1287800''>basic</span> <span m=''1288160''>idea.</span> <span m=''1289980''>We</span>
  <span m=''1290090''>take</span> <span m=''1290310''>the</span> <span m=''1290440''>evaluator,</span>
  <span m=''1290930''>we</span> <span m=''1291090''>eliminate</span> <span m=''1291770''>the</span>
  <span m=''1292140''>things</span> <span m=''1292360''>that</span> <span m=''1292500''>you</span>
  <span m=''1292600''>don''t</span> <span m=''1292800''>need,</span> <span m=''1293030''>that</span>
  <span m=''1293160''>in</span> <span m=''1293250''>some</span> <span m=''1293410''>sense</span>
  <span m=''1293600''>have</span> <span m=''1293720''>nothing</span> <span m=''1294020''>to</span>
  <span m=''1294110''>do</span> <span m=''1294250''>with</span> <span m=''1294370''>the</span>
  <span m=''1294450''>compiler</span> <span m=''1294730''>at</span> <span m=''1295010''>all,</span>
  <span m=''1295180''>just</span> <span m=''1295300''>the</span> <span m=''1295420''>evaluator,</span>
  <span m=''1297390''>and</span> <span m=''1297690''>then</span> <span m=''1298170''>you</span>
  <span m=''1298300''>see</span> <span m=''1298480''>which</span> <span m=''1298660''>stack</span>
  <span m=''1298990''>operations</span> <span m=''1299560''>are</span> <span m=''1299680''>unnecessary.</span>
  </p><p><span m=''1300460''>That''s</span> <span m=''1301120''>the</span> <span m=''1301200''>basic</span>
  <span m=''1301600''>structure</span> <span m=''1302030''>of</span> <span m=''1302110''>the</span>
  <span m=''1302890''>compiler</span> <span m=''1303410''>that''s</span> <span m=''1304080''>described</span>
  <span m=''1304490''>in</span> <span m=''1304570''>the</span> <span m=''1304650''>book.</span>
  <span m=''1305130''>Let</span> <span m=''1305250''>me</span> <span m=''1305350''>just</span>
  <span m=''1305500''>show</span> <span m=''1305690''>you</span> <span m=''1306340''>how</span>
  <span m=''1307940''>that</span> <span m=''1308120''>examples</span> <span m=''1308570''>a</span>
  <span m=''1308620''>little</span> <span m=''1308870''>bit</span> <span m=''1309060''>too</span>
  <span m=''1309180''>simple.</span> <span m=''1311280''>To</span> <span m=''1311410''>see</span>
  <span m=''1311580''>how</span> <span m=''1312240''>you, how you</span> <span m=''1312410''>actually</span>
  <span m=''1312740''>save</span> <span m=''1313030''>a</span> <span m=''1313080''>lot,</span>
  <span m=''1313320''>let''s</span> <span m=''1313500''>look</span> <span m=''1313610''>at</span>
  <span m=''1313710''>a</span> <span m=''1314280''>little</span> <span m=''1314600''>bit</span>
  <span m=''1314770''>more</span> <span m=''1314920''>complicated</span> <span m=''1315510''>expression.</span>
  <span m=''1318330''>F</span> <span m=''1319550''>of</span> <span m=''1319690''>G</span>
  <span m=''1319910''>of</span> <span m=''1320052''>X</span> <span m=''1321320''>and</span>
  <span m=''1321560''>1.</span> <span m=''1323542''>And</span> <span m=''1323960''>I''m</span>
  <span m=''1324120''>not</span> <span m=''1324280''>going</span> <span m=''1324350''>to</span>
  <span m=''1324410''>go</span> <span m=''1324560''>through</span> <span m=''1324780''>all</span>
  <span m=''1324880''>the</span> <span m=''1324960''>code.</span> <span m=''1326410''>There''s</span>
  <span m=''1326640''>a, there''s a</span> <span m=''1327620''>fair</span> <span m=''1327830''>pile</span>
  <span m=''1327975''>of</span> <span m=''1328120''>it.</span> <span m=''1329830''>I</span>
  <span m=''1329930''>think</span> <span m=''1330090''>there</span> <span m=''1330310''>are,
  there are</span> <span m=''1331050''>something</span> <span m=''1331300''>like</span>
  <span m=''1331500''>16</span> <span m=''1332400''>pairs</span> <span m=''1332870''>of</span>
  <span m=''1333410''>register</span> <span m=''1333830''>saves</span> <span m=''1334130''>and</span>
  <span m=''1334210''>restores</span> <span m=''1334700''>as</span> <span m=''1334755''>the</span>
  <span m=''1334810''>evaluator</span> <span m=''1335440''>walks</span> <span m=''1335730''>through</span>
  <span m=''1335900''>that.</span> <span m=''1337270''>Here''s</span> <span m=''1337490''>a</span>
  <span m=''1337540''>diagram</span> <span m=''1338060''>of</span> <span m=''1338230''>them.</span>
  </p><p><span m=''1340680''>Let''s</span> <span m=''1340900''>see.</span> <span m=''1341060''>You</span>
  <span m=''1341135''>see</span> <span m=''1341210''>what''s</span> <span m=''1341400''>going</span>
  <span m=''1341660''>on.</span> <span m=''1344210''>You start out by--the</span>
  <span m=''1344350''>evaluator</span> <span m=''1344800''>says,</span> <span m=''1344990''>oh,</span>
  <span m=''1345150''>I''m</span> <span m=''1345290''>about</span> <span m=''1345530''>to</span>
  <span m=''1345620''>do</span> <span m=''1345770''>an</span> <span m=''1345850''>application.</span>
  <span m=''1346480''>I''ll</span> <span m=''1346880''>preserve</span> <span m=''1347290''>the</span>
  <span m=''1347410''>environment.</span> <span m=''1348010''>I''ll</span> <span m=''1348160''>restore</span>
  <span m=''1348415''>it</span> <span m=''1348670''>here.</span> <span m=''1350261''>Then</span>
  <span m=''1350650''>I''m</span> <span m=''1351030''>about</span> <span m=''1351310''>to</span>
  <span m=''1351410''>do</span> <span m=''1352580''>the</span> <span m=''1352730''>first</span>
  <span m=''1353510''>operand.</span> <span m=''1356790''>Here</span> <span m=''1357020''>it</span>
  <span m=''1357050''>recursively</span> <span m=''1357660''>goes</span> <span m=''1357950''>to</span>
  <span m=''1358070''>the</span> <span m=''1358650''>evaluator.</span> <span m=''1358970''>The</span>
  <span m=''1359290''>evaluator</span> <span m=''1359470''>says,</span> <span m=''1359930''>oh,</span>
  <span m=''1360010''>this</span> <span m=''1360180''>is</span> <span m=''1360290''>an</span>
  <span m=''1360510''>application,</span> <span m=''1361000''>I''ll</span> <span m=''1361310''>save</span>
  <span m=''1361370''>the</span> <span m=''1361430''>environment,</span> <span m=''1362200''>do</span>
  <span m=''1362360''>the</span> <span m=''1362740''>operator</span> <span m=''1363025''>of</span>
  <span m=''1363310''>that</span> <span m=''1363520''>combination,</span> <span m=''1364090''>restore</span>
  <span m=''1364325''>it</span> <span m=''1364560''>here.</span> </p><p><span m=''1366740''>This
  save--this</span> <span m=''1366950''>restore</span> <span m=''1367750''>matches</span>
  <span m=''1368180''>that</span> <span m=''1368430''>save.</span> <span m=''1369980''>And</span>
  <span m=''1370180''>so</span> <span m=''1370410''>on.</span> <span m=''1371720''>There''s</span>
  <span m=''1371920''>unev</span> <span m=''1372310''>here,</span> <span m=''1372500''>which</span>
  <span m=''1372700''>turns</span> <span m=''1372960''>out</span> <span m=''1373090''>to</span>
  <span m=''1373170''>be</span> <span m=''1373290''>completely</span> <span m=''1373740''>unnecessary,</span>
  <span m=''1374840''>continues</span> <span m=''1375480''>getting</span> <span m=''1375730''>bumped</span>
  <span m=''1376000''>around</span> <span m=''1376280''>here.</span> <span m=''1377240''>The</span>
  <span m=''1377510''>function</span> <span m=''1377880''>register</span> <span m=''1378810''>is</span>
  <span m=''1378990''>getting, getting</span> <span m=''1379920''>saved</span> <span
  m=''1380790''>across</span> <span m=''1381040''>the</span> <span m=''1381280''>first</span>
  <span m=''1382520''>operands,</span> <span m=''1383350''>across</span> <span m=''1383640''>the</span>
  <span m=''1383760''>operands.</span> <span m=''1385330''>All</span> <span m=''1385440''>sorts</span>
  <span m=''1385650''>of</span> <span m=''1385720''>things</span> <span m=''1385930''>are</span>
  <span m=''1385990''>going</span> <span m=''1386270''>on.</span> <span m=''1386680''>But</span>
  <span m=''1386920''>if</span> <span m=''1387030''>you</span> <span m=''1387120''>say,</span>
  <span m=''1387330''>well,</span> <span m=''1387450''>what</span> <span m=''1387940''>of</span>
  <span m=''1387970''>those</span> <span m=''1388190''>really</span> <span m=''1388470''>were</span>
  <span m=''1388570''>the</span> <span m=''1388680''>business</span> <span m=''1389090''>of</span>
  <span m=''1389250''>the</span> <span m=''1389710''>compiler</span> <span m=''1389897''>as</span>
  <span m=''1390460''>opposed</span> <span m=''1390750''>to</span> <span m=''1390805''>the</span>
  <span m=''1390860''>evaluator,</span> <span m=''1392300''>you</span> <span m=''1392410''>get</span>
  <span m=''1392570''>rid</span> <span m=''1392680''>of</span> <span m=''1392770''>a</span>
  <span m=''1392810''>whole</span> <span m=''1393010''>bunch.</span> </p><p><span
  m=''1394320''>And</span> <span m=''1394450''>then</span> <span m=''1394580''>on</span>
  <span m=''1394690''>top</span> <span m=''1394950''>of</span> <span m=''1395130''>that,</span>
  <span m=''1395310''>if</span> <span m=''1395470''>you</span> <span m=''1395580''>say</span>
  <span m=''1395780''>things</span> <span m=''1396070''>like,</span> <span m=''1399015''>the</span>
  <span m=''1399500''>evaluation</span> <span m=''1400310''>of</span> <span m=''1400470''>F</span>
  <span m=''1400950''>doesn''t</span> <span m=''1401230''>hurt</span> <span m=''1401450''>the</span>
  <span m=''1401570''>environment</span> <span m=''1402040''>register,</span> <span
  m=''1403880''>or</span> <span m=''1404520''>simply</span> <span m=''1405050''>looking</span>
  <span m=''1405400''>up</span> <span m=''1405520''>the</span> <span m=''1405610''>symbol</span>
  <span m=''1405980''>X,</span> <span m=''1409370''>you</span> <span m=''1409490''>don''t</span>
  <span m=''1409650''>have</span> <span m=''1409820''>to</span> <span m=''1409930''>protect</span>
  <span m=''1410500''>the</span> <span m=''1410630''>function</span> <span m=''1411000''>register</span>
  <span m=''1411450''>against</span> <span m=''1411760''>that.</span> <span m=''1414570''>So</span>
  <span m=''1414780''>you</span> <span m=''1414840''>come</span> <span m=''1415030''>down</span>
  <span m=''1415260''>to</span> <span m=''1415360''>just</span> <span m=''1415560''>a</span>
  <span m=''1415600''>couple</span> <span m=''1415960''>of, a couple of</span> <span
  m=''1416870''>pairs</span> <span m=''1417220''>here.</span> <span m=''1420280''>And</span>
  <span m=''1420840''>still,</span> <span m=''1421090''>you</span> <span m=''1421210''>can</span>
  <span m=''1421300''>do</span> <span m=''1421475''>a</span> <span m=''1421650''>little</span>
  <span m=''1421900''>better.</span> </p><p><span m=''1422160''>Look</span> <span
  m=''1422300''>what''s</span> <span m=''1422460''>going</span> <span m=''1422670''>on</span>
  <span m=''1422810''>here</span> <span m=''1422970''>with</span> <span m=''1423090''>the</span>
  <span m=''1423190''>environment</span> <span m=''1423690''>register.</span> <span
  m=''1424962''>The</span> <span m=''1425330''>environment</span> <span m=''1425910''>register</span>
  <span m=''1426090''>comes</span> <span m=''1426340''>along</span> <span m=''1426700''>and</span>
  <span m=''1426830''>says,</span> <span m=''1427060''>oh,</span> <span m=''1431050''>here''s</span>
  <span m=''1431290''>a</span> <span m=''1431350''>combination.</span> <span m=''1434280''>This</span>
  <span m=''1434560''>evaluator,</span> <span m=''1435170''>by</span> <span m=''1435310''>the</span>
  <span m=''1435420''>way,</span> <span m=''1435840''>doesn''t</span> <span m=''1436100''>know</span>
  <span m=''1436230''>anything</span> <span m=''1436540''>about</span> <span m=''1436790''>G.</span>
  <span m=''1438580''>So</span> <span m=''1438780''>here</span> <span m=''1439010''>it</span>
  <span m=''1439140''>says, so it says,</span> <span m=''1441310''>I''d</span> <span
  m=''1441650''>better</span> <span m=''1441930''>save</span> <span m=''1442200''>the</span>
  <span m=''1442330''>environment</span> <span m=''1442870''>register,</span> <span
  m=''1444010''>because</span> <span m=''1444340''>evaluating</span> <span m=''1444870''>G</span>
  <span m=''1445120''>might</span> <span m=''1445320''>be</span> <span m=''1445420''>some</span>
  <span m=''1445610''>arbitrary</span> <span m=''1446060''>piece</span> <span m=''1446300''>of</span>
  <span m=''1446390''>code</span> <span m=''1446610''>that</span> <span m=''1446730''>would</span>
  <span m=''1446850''>trash</span> <span m=''1447220''>it,</span> <span m=''1447630''>and</span>
  <span m=''1447770''>I''m</span> <span m=''1447880''>going</span> <span m=''1447960''>to</span>
  <span m=''1448050''>need</span> <span m=''1448390''>it</span> <span m=''1448840''>later,</span>
  <span m=''1450280''>after</span> <span m=''1450560''>this</span> <span m=''1450830''>argument,</span>
  <span m=''1452220''>for</span> <span m=''1452360''>doing</span> <span m=''1452610''>the</span>
  <span m=''1452800''>second</span> <span m=''1452990''>argument.</span> <span m=''1455540''>So</span>
  <span m=''1455690''>that''s</span> <span m=''1455910''>why</span> <span m=''1456040''>this</span>
  <span m=''1456210''>one</span> <span m=''1456360''>didn''t</span> <span m=''1456650''>go</span>
  <span m=''1456830''>away,</span> <span m=''1459110''>because</span> <span m=''1459360''>the</span>
  <span m=''1460030''>compiler</span> <span m=''1460580''>made</span> <span m=''1460750''>no</span>
  <span m=''1460920''>assumptions</span> <span m=''1461410''>about</span> <span m=''1461650''>what</span>
  <span m=''1461810''>G</span> <span m=''1461970''>would</span> <span m=''1462140''>do.</span>
  </p><p><span m=''1462550''>On</span> <span m=''1462740''>the</span> <span m=''1462920''>other</span>
  <span m=''1463100''>hand,</span> <span m=''1464630''>if</span> <span m=''1464760''>you</span>
  <span m=''1464870''>look</span> <span m=''1464990''>at</span> <span m=''1465210''>what</span>
  <span m=''1465350''>the</span> <span m=''1465540''>second</span> <span m=''1465730''>argument</span>
  <span m=''1466170''>is,</span> <span m=''1466670''>that''s</span> <span m=''1466930''>just</span>
  <span m=''1467120''>looking</span> <span m=''1467380''>up</span> <span m=''1467500''>one.</span>
  <span m=''1467710''>That</span> <span m=''1467850''>doesn''t</span> <span m=''1468160''>need</span>
  <span m=''1468390''>this</span> <span m=''1468580''>environment</span> <span m=''1469000''>register.</span>
  <span m=''1470810''>So</span> <span m=''1470940''>there''s</span> <span m=''1471130''>no</span>
  <span m=''1471260''>reason</span> <span m=''1471550''>to</span> <span m=''1471630''>save</span>
  <span m=''1471900''>it.</span> <span m=''1472070''>So</span> <span m=''1472180''>in</span>
  <span m=''1472270''>fact,</span> <span m=''1472480''>you</span> <span m=''1472560''>can</span>
  <span m=''1472640''>get</span> <span m=''1472750''>rid</span> <span m=''1472850''>of</span>
  <span m=''1472900''>that</span> <span m=''1473130''>one,</span> <span m=''1473280''>too.</span>
  <span m=''1475020''>And</span> <span m=''1475210''>from</span> <span m=''1475340''>this</span>
  <span m=''1475470''>whole</span> <span m=''1475650''>pile</span> <span m=''1476090''>of,
  of</span> <span m=''1476580''>register</span> <span m=''1477040''>operations,</span>
  <span m=''1478060''>if</span> <span m=''1478200''>you</span> <span m=''1478290''>simply</span>
  <span m=''1478610''>do</span> <span m=''1478760''>a</span> <span m=''1478780''>little</span>
  <span m=''1478940''>bit</span> <span m=''1479060''>of</span> <span m=''1479130''>reasoning</span>
  <span m=''1479470''>like</span> <span m=''1479670''>that,</span> <span m=''1480550''>you</span>
  <span m=''1480670''>get</span> <span m=''1480840''>down</span> <span m=''1481060''>to,</span>
  <span m=''1481180''>I</span> <span m=''1481270''>think,</span> <span m=''1481370''>just</span>
  <span m=''1481560''>two</span> <span m=''1481680''>pairs</span> <span m=''1481990''>of</span>
  <span m=''1482050''>saves</span> <span m=''1482360''>and</span> <span m=''1482440''>restores.</span>
  <span m=''1485170''>And</span> <span m=''1485340''>those,</span> <span m=''1485570''>in</span>
  <span m=''1485760''>fact,</span> <span m=''1485950''>could</span> <span m=''1486030''>go</span>
  <span m=''1486110''>away</span> <span m=''1486260''>further</span> <span m=''1486660''>if</span>
  <span m=''1486770''>you, if you</span> <span m=''1487870''>knew</span> <span m=''1488030''>something</span>
  <span m=''1488420''>about</span> <span m=''1488530''>G.</span> </p><p><span m=''1496650''>So</span>
  <span m=''1496750''>again,</span> <span m=''1496960''>the</span> <span m=''1497030''>general</span>
  <span m=''1497410''>idea</span> <span m=''1498020''>is</span> <span m=''1498180''>that</span>
  <span m=''1498340''>the</span> <span m=''1498440''>reason</span> <span m=''1498710''>the</span>
  <span m=''1498790''>compiler</span> <span m=''1499250''>can</span> <span m=''1499380''>be</span>
  <span m=''1499470''>better</span> <span m=''1500020''>is</span> <span m=''1500180''>that</span>
  <span m=''1500320''>the</span> <span m=''1500440''>interpreter</span> <span m=''1500890''>doesn''t</span>
  <span m=''1501200''>know</span> <span m=''1501310''>what</span> <span m=''1501430''>it''s</span>
  <span m=''1501550''>about</span> <span m=''1501810''>to</span> <span m=''1501910''>encounter.</span>
  <span m=''1503310''>It</span> <span m=''1503420''>has</span> <span m=''1503580''>to</span>
  <span m=''1503670''>be</span> <span m=''1503770''>maximally</span> <span m=''1504390''>pessimistic</span>
  <span m=''1505050''>in</span> <span m=''1505170''>saving</span> <span m=''1505540''>things</span>
  <span m=''1505740''>to</span> <span m=''1505830''>protect</span> <span m=''1506220''>itself.</span>
  <span m=''1507750''>The</span> <span m=''1508050''>compiler</span> <span m=''1509510''>only</span>
  <span m=''1509810''>has</span> <span m=''1510000''>to</span> <span m=''1510100''>deal</span>
  <span m=''1510300''>with</span> <span m=''1510670''>what</span> <span m=''1510820''>actually</span>
  <span m=''1511380''>had</span> <span m=''1511640''>to</span> <span m=''1511740''>be</span>
  <span m=''1511870''>saved.</span> <span m=''1513410''>And</span> <span m=''1513490''>there</span>
  <span m=''1513580''>are</span> <span m=''1513660''>two</span> <span m=''1513890''>reasons</span>
  <span m=''1514530''>that</span> <span m=''1514800''>something</span> <span m=''1515150''>might</span>
  <span m=''1515620''>not</span> <span m=''1516370''>have</span> <span m=''1516630''>to</span>
  <span m=''1516740''>be</span> <span m=''1516880''>saved.</span> <span m=''1517920''>One</span>
  <span m=''1518160''>is</span> <span m=''1518310''>that</span> <span m=''1518530''>what</span>
  <span m=''1518660''>you''re</span> <span m=''1518800''>protecting</span> <span m=''1519360''>it</span>
  <span m=''1519420''>against,</span> <span m=''1519950''>in</span> <span m=''1520100''>fact,</span>
  <span m=''1520420''>didn''t</span> <span m=''1520660''>trash</span> <span m=''1520960''>the</span>
  <span m=''1521070''>register,</span> <span m=''1522300''>like it was</span> <span
  m=''1522460''>just</span> <span m=''1522660''>a</span> <span m=''1522700''>variable</span>
  <span m=''1523100''>look-up.</span> <span m=''1524210''>And</span> <span m=''1524340''>the</span>
  <span m=''1524460''>other</span> <span m=''1524690''>one</span> <span m=''1524960''>is,</span>
  <span m=''1525380''>that</span> <span m=''1525570''>the</span> <span m=''1525660''>thing</span>
  <span m=''1525880''>that</span> <span m=''1526010''>you</span> <span m=''1526140''>were</span>
  <span m=''1526260''>saving</span> <span m=''1526610''>it</span> <span m=''1526730''>for</span>
  <span m=''1528390''>might</span> <span m=''1528570''>turn</span> <span m=''1528830''>out</span>
  <span m=''1528960''>not</span> <span m=''1529090''>to</span> <span m=''1529210''>actually</span>
  <span m=''1529570''>need</span> <span m=''1529800''>it.</span> </p><p><span m=''1530800''>So</span>
  <span m=''1530980''>those</span> <span m=''1531170''>are</span> <span m=''1531210''>the</span>
  <span m=''1531350''>two</span> <span m=''1532830''>basic</span> <span m=''1533360''>pieces</span>
  <span m=''1533700''>of</span> <span m=''1533800''>knowledge</span> <span m=''1534210''>that</span>
  <span m=''1534280''>the</span> <span m=''1534370''>compiler</span> <span m=''1534800''>can</span>
  <span m=''1534950''>take</span> <span m=''1535170''>advantage</span> <span m=''1535630''>of</span>
  <span m=''1536840''>in</span> <span m=''1536970''>making</span> <span m=''1537010''>the</span>
  <span m=''1537050''>code</span> <span m=''1537270''>more</span> <span m=''1537420''>efficient.</span>
  <span m=''1544570''>Let''s</span> <span m=''1544760''>break</span> <span m=''1544940''>for</span>
  <span m=''1545040''>questions.</span> </p><p><span m=''1551280''>AUDIENCE: You</span>
  <span m=''1551430''>kept</span> <span m=''1551650''>saying</span> <span m=''1552020''>that</span>
  <span m=''1552130''>the</span> <span m=''1552280''>uneval</span> <span m=''1552790''>register,</span>
  <span m=''1553670''>unev</span> <span m=''1554410''>register</span> <span m=''1554860''>didn''t</span>
  <span m=''1554970''>need</span> <span m=''1555260''>to</span> <span m=''1555320''>be</span>
  <span m=''1555730''>used</span> <span m=''1556040''>at</span> <span m=''1556190''>all.</span>
  <span m=''1556350''>Does</span> <span m=''1556470''>that</span> <span m=''1556600''>mean</span>
  <span m=''1556770''>that</span> <span m=''1556890''>you</span> <span m=''1557010''>could</span>
  <span m=''1557160''>just</span> <span m=''1557390''>map</span> <span m=''1557560''>a</span>
  <span m=''1557660''>six-register</span> <span m=''1558250''>machine?</span> <span
  m=''1558590''>Or</span> <span m=''1558650''>is</span> <span m=''1558790''>that,</span>
  <span m=''1558930''>in</span> <span m=''1559070''>this</span> <span m=''1559210''>particular</span>
  <span m=''1559630''>example,</span> <span m=''1560130''>it</span> <span m=''1560220''>didn''t</span>
  <span m=''1560460''>need</span> <span m=''1560580''>to</span> <span m=''1560690''>be</span>
  <span m=''1560810''>used?</span> </p><p><span m=''1561860''>PROFESSOR: For</span>
  <span m=''1562000''>the</span> <span m=''1562100''>compiler,</span> <span m=''1564410''>you</span>
  <span m=''1564550''>could</span> <span m=''1564660''>generate</span> <span m=''1565070''>code</span>
  <span m=''1565390''>for</span> <span m=''1565480''>the</span> <span m=''1565570''>six-register,</span>
  <span m=''1566780''>five,</span> <span m=''1567150''>right?</span> <span m=''1567580''>Because</span>
  <span m=''1567730''>that</span> <span m=''1567850''>exp</span> <span m=''1568140''>goes</span>
  <span m=''1568330''>away</span> <span m=''1568540''>also.</span> <span m=''1571750''>Assuming--yeah,</span>
  <span m=''1572880''>you</span> <span m=''1573190''>can</span> <span m=''1573310''>get</span>
  <span m=''1573470''>rid</span> <span m=''1573600''>of</span> <span m=''1573680''>both</span>
  <span m=''1573930''>exp</span> <span m=''1574150''>and</span> <span m=''1574370''>unev,</span>
  <span m=''1574700''>because,</span> <span m=''1575140''>see,</span> <span m=''1575157''>those</span>
  <span m=''1575175''>are</span> <span m=''1575210''>data</span> <span m=''1575470''>structures</span>
  <span m=''1575890''>of</span> <span m=''1575980''>the</span> <span m=''1576080''>evaluator.</span>
  <span m=''1577380''>Those</span> <span m=''1577640''>are</span> <span m=''1577710''>all</span>
  <span m=''1577940''>things</span> <span m=''1578240''>that</span> <span m=''1578430''>would</span>
  <span m=''1578640''>be</span> <span m=''1578860''>constants</span> <span m=''1579380''>from</span>
  <span m=''1579490''>the</span> <span m=''1579600''>point</span> <span m=''1579830''>of</span>
  <span m=''1579880''>view</span> <span m=''1580030''>of</span> <span m=''1580080''>the</span>
  <span m=''1580130''>compiler.</span> <span m=''1581410''>The</span> <span m=''1581870''>only</span>
  <span m=''1582090''>thing</span> <span m=''1582280''>is</span> <span m=''1582450''>this</span>
  <span m=''1582760''>particular</span> <span m=''1583510''>compiler</span> <span
  m=''1583860''>is</span> <span m=''1584210''>set</span> <span m=''1584390''>up</span>
  <span m=''1584730''>so</span> <span m=''1584970''>that</span> <span m=''1585130''>interpreted</span>
  <span m=''1586070''>code</span> <span m=''1586320''>and</span> <span m=''1586420''>compiled</span>
  <span m=''1586890''>code</span> <span m=''1587130''>can</span> <span m=''1587260''>coexist.</span>
  </p><p><span m=''1589330''>So</span> <span m=''1589490''>the</span> <span m=''1589580''>way</span>
  <span m=''1589720''>to</span> <span m=''1589810''>think</span> <span m=''1590020''>about</span>
  <span m=''1590340''>it</span> <span m=''1590430''>is, is</span> <span m=''1591090''>maybe</span>
  <span m=''1591350''>you</span> <span m=''1591480''>build</span> <span m=''1591770''>a</span>
  <span m=''1591820''>chip</span> <span m=''1594330''>which</span> <span m=''1594520''>is</span>
  <span m=''1594630''>the</span> <span m=''1594690''>evaluator,</span> <span m=''1595940''>and</span>
  <span m=''1596180''>what</span> <span m=''1596380''>the</span> <span m=''1596480''>compiler</span>
  <span m=''1596930''>might</span> <span m=''1597140''>do</span> <span m=''1597290''>is</span>
  <span m=''1597420''>generate</span> <span m=''1597890''>code</span> <span m=''1598190''>for</span>
  <span m=''1598440''>that</span> <span m=''1598680''>chip.</span> <span m=''1599920''>It</span>
  <span m=''1600410''>just</span> <span m=''1600600''>wouldn''t</span> <span m=''1600780''>use</span>
  <span m=''1601050''>two</span> <span m=''1601160''>of</span> <span m=''1601225''>the</span>
  <span m=''1601290''>registers.</span> <span m=''1611158''>All</span> <span m=''1611409''>right,</span>
  <span m=''1611660''>let''s</span> <span m=''1611920''>take</span> <span m=''1612060''>a</span>
  <span m=''1612100''>break.</span> </p><p><span m=''1613326''>[MUSIC PLAYING]</span>
  </p><p><span m=''1648576''>We</span> <span m=''1649070''>just</span> <span m=''1649310''>looked</span>
  <span m=''1649650''>at</span> <span m=''1650780''>what</span> <span m=''1650990''>the</span>
  <span m=''1651090''>compiler</span> <span m=''1651405''>is</span> <span m=''1651720''>supposed</span>
  <span m=''1651910''>to</span> <span m=''1652110''>do.</span> <span m=''1652900''>Now</span>
  <span m=''1653220''>let''s</span> <span m=''1653750''>very</span> <span m=''1654210''>briefly</span>
  <span m=''1655470''>look</span> <span m=''1655820''>at</span> <span m=''1656140''>how,
  how</span> <span m=''1656320''>this</span> <span m=''1656500''>gets</span> <span
  m=''1656700''>accomplished.</span> <span m=''1658120''>And</span> <span m=''1658500''>I''m</span>
  <span m=''1658530''>going</span> <span m=''1658610''>to</span> <span m=''1658730''>give</span>
  <span m=''1658880''>no</span> <span m=''1659050''>details.</span> <span m=''1659600''>There''s,
  there''s</span> <span m=''1660640''>a</span> <span m=''1660690''>giant</span> <span
  m=''1661110''>pile</span> <span m=''1661430''>of</span> <span m=''1661520''>code</span>
  <span m=''1661770''>in</span> <span m=''1661860''>the</span> <span m=''1661940''>book</span>
  <span m=''1662240''>that</span> <span m=''1662390''>gives</span> <span m=''1662580''>all</span>
  <span m=''1662740''>the</span> <span m=''1662810''>details.</span> <span m=''1663440''>But</span>
  <span m=''1663620''>what</span> <span m=''1663750''>I</span> <span m=''1663810''>want</span>
  <span m=''1663900''>to</span> <span m=''1664000''>do</span> <span m=''1664140''>is</span>
  <span m=''1664290''>just</span> <span m=''1664540''>show</span> <span m=''1664750''>you</span>
  <span m=''1665700''>the, the</span> <span m=''1666150''>essential</span> <span m=''1666640''>idea</span>
  <span m=''1666950''>here.</span> <span m=''1669590''>Worry</span> <span m=''1669840''>about</span>
  <span m=''1670050''>the</span> <span m=''1670120''>details</span> <span m=''1670570''>some</span>
  <span m=''1670760''>other</span> <span m=''1670950''>time.</span> </p><p><span m=''1671450''>Let''s</span>
  <span m=''1671670''>imagine</span> <span m=''1672090''>that</span> <span m=''1672270''>we''re</span>
  <span m=''1673480''>compiling</span> <span m=''1674650''>an</span> <span m=''1674750''>expression</span>
  <span m=''1675270''>that</span> <span m=''1675420''>looks</span> <span m=''1675640''>like</span>
  <span m=''1675800''>there''s</span> <span m=''1675970''>some</span> <span m=''1676160''>operator,</span>
  <span m=''1677570''>and</span> <span m=''1677650''>there</span> <span m=''1677740''>are</span>
  <span m=''1677820''>two</span> <span m=''1678050''>arguments.</span> <span m=''1683660''>Now,
  the--</span> <span m=''1686310''>what''s</span> <span m=''1686490''>the</span> <span
  m=''1686580''>code</span> <span m=''1686900''>that</span> <span m=''1687000''>the</span>
  <span m=''1687100''>compiler</span> <span m=''1687560''>should</span> <span m=''1687680''>generate?</span>
  <span m=''1688940''>Well,</span> <span m=''1689040''>first</span> <span m=''1689330''>of</span>
  <span m=''1689440''>all,</span> <span m=''1689800''>it</span> <span m=''1689960''>should</span>
  <span m=''1690100''>recursively</span> <span m=''1690730''>go</span> <span m=''1690960''>off</span>
  <span m=''1691980''>and</span> <span m=''1692170''>compile</span> <span m=''1692630''>the</span>
  <span m=''1692740''>operator.</span> <span m=''1694192''>So</span> <span m=''1694426''>it</span>
  <span m=''1694660''>says,</span> <span m=''1695240''>I''ll</span> <span m=''1695370''>compile</span>
  <span m=''1698100''>the</span> <span m=''1698330''>operator.</span> <span m=''1701250''>And</span>
  <span m=''1703026''>where</span> <span m=''1703233''>I''m</span> <span m=''1703440''>going</span>
  <span m=''1703655''>to</span> <span m=''1703870''>need</span> <span m=''1704260''>that</span>
  <span m=''1704900''>is</span> <span m=''1705610''>to</span> <span m=''1705770''>be</span>
  <span m=''1706030''>in</span> <span m=''1706160''>the</span> <span m=''1706230''>function</span>
  <span m=''1706600''>register,</span> <span m=''1707180''>eventually.</span> <span
  m=''1708400''>So</span> <span m=''1708525''>I''ll</span> <span m=''1708650''>compile</span>
  <span m=''1709100''>some</span> <span m=''1709260''>instructions</span> <span m=''1709770''>that</span>
  <span m=''1709880''>will</span> <span m=''1710180''>compile</span> <span m=''1710830''>the</span>
  <span m=''1710940''>operator</span> <span m=''1711710''>and</span> <span m=''1711970''>end</span>
  <span m=''1712250''>up</span> <span m=''1712850''>with</span> <span m=''1713010''>the</span>
  <span m=''1713100''>result</span> <span m=''1717220''>in</span> <span m=''1717640''>the</span>
  <span m=''1717820''>function</span> <span m=''1718230''>register.</span> </p><p><span
  m=''1725420''>The</span> <span m=''1725690''>next</span> <span m=''1725970''>thing</span>
  <span m=''1726110''>it''s</span> <span m=''1726250''>going</span> <span m=''1726330''>to</span>
  <span m=''1726400''>do,</span> <span m=''1727820''>another</span> <span m=''1728110''>piece</span>
  <span m=''1728820''>is</span> <span m=''1729000''>to</span> <span m=''1729110''>say,</span>
  <span m=''1729770''>well,</span> <span m=''1729900''>I</span> <span m=''1729960''>have</span>
  <span m=''1730100''>to</span> <span m=''1730230''>compile</span> <span m=''1733960''>the</span>
  <span m=''1734310''>first</span> <span m=''1734620''>argument.</span> <span m=''1735140''>So</span>
  <span m=''1735330''>it</span> <span m=''1735440''>calls</span> <span m=''1735670''>itself</span>
  <span m=''1736000''>recursively.</span> <span m=''1738100''>And</span> <span m=''1738480''>let''s</span>
  <span m=''1738810''>say</span> <span m=''1738910''>the</span> <span m=''1739030''>result</span>
  <span m=''1742110''>will</span> <span m=''1742320''>go</span> <span m=''1742620''>into</span>
  <span m=''1742730''>val.</span> <span m=''1749150''>And</span> <span m=''1749330''>then</span>
  <span m=''1749480''>what</span> <span m=''1749610''>it''s</span> <span m=''1749960''>going</span>
  <span m=''1750050''>to</span> <span m=''1750140''>need</span> <span m=''1750290''>to</span>
  <span m=''1750430''>do</span> <span m=''1750630''>is</span> <span m=''1750780''>start</span>
  <span m=''1751110''>setting</span> <span m=''1751360''>up</span> <span m=''1751460''>the</span>
  <span m=''1751570''>argument</span> <span m=''1751970''>list.</span> <span m=''1752725''>So</span>
  <span m=''1753050''>it''ll</span> <span m=''1753350''>say,</span> <span m=''1753550''>assign</span>
  <span m=''1757440''>to</span> <span m=''1758010''>argl</span> <span m=''1762340''>cons</span>
  <span m=''1764590''>of</span> <span m=''1765060''>fetch--</span> <span m=''1765370''>so</span>
  <span m=''1765510''>it</span> <span m=''1765650''>generates</span> <span m=''1766030''>this</span>
  <span m=''1766160''>literal</span> <span m=''1766510''>instruction--</span> <span
  m=''1767160''>fetch</span> <span m=''1767730''>of</span> <span m=''1767940''>val</span>
  <span m=''1769920''>onto</span> <span m=''1771690''>empty</span> <span m=''1771990''>list.</span>
  </p><p><span m=''1775430''>However, it might have to work--</span> <span m=''1779590''>when</span>
  <span m=''1779680''>it</span> <span m=''1779770''>gets</span> <span m=''1780000''>here,</span>
  <span m=''1781390''>it''s</span> <span m=''1781580''>going</span> <span m=''1781660''>to</span>
  <span m=''1781750''>need</span> <span m=''1782070''>the</span> <span m=''1782190''>environment.</span>
  <span m=''1783950''>It''s</span> <span m=''1784190''>going</span> <span m=''1784265''>to</span>
  <span m=''1784340''>need</span> <span m=''1784440''>whatever</span> <span m=''1784650''>environment</span>
  <span m=''1785050''>was</span> <span m=''1785180''>here</span> <span m=''1785370''>in</span>
  <span m=''1785420''>order</span> <span m=''1785650''>to</span> <span m=''1785770''>do</span>
  <span m=''1785930''>this</span> <span m=''1786540''>evaluation</span> <span m=''1787320''>of</span>
  <span m=''1787390''>the</span> <span m=''1787470''>first</span> <span m=''1787750''>argument.</span>
  <span m=''1789030''>So</span> <span m=''1789250''>it</span> <span m=''1789390''>has</span>
  <span m=''1789540''>to</span> <span m=''1789890''>ensure</span> <span m=''1790770''>that</span>
  <span m=''1791820''>the</span> <span m=''1792070''>compilation</span> <span m=''1792750''>of</span>
  <span m=''1792840''>this</span> <span m=''1793010''>operand,</span> <span m=''1794990''>or</span>
  <span m=''1795420''>it</span> <span m=''1795550''>has</span> <span m=''1795710''>to</span>
  <span m=''1795820''>protect</span> <span m=''1796590''>the</span> <span m=''1796680''>function</span>
  <span m=''1797050''>register</span> <span m=''1798120''>against</span> <span m=''1798610''>whatever</span>
  <span m=''1798900''>might</span> <span m=''1799110''>happen</span> <span m=''1799440''>in</span>
  <span m=''1799490''>the</span> <span m=''1799580''>compilation</span> <span m=''1800150''>of</span>
  <span m=''1800210''>this</span> <span m=''1800360''>operand.</span> </p><p><span
  m=''1801220''>So</span> <span m=''1801420''>it</span> <span m=''1801510''>puts</span>
  <span m=''1801690''>a</span> <span m=''1801740''>note</span> <span m=''1802010''>here</span>
  <span m=''1802210''>and</span> <span m=''1802370''>says,</span> <span m=''1802690''>oh,</span>
  <span m=''1803350''>this</span> <span m=''1803810''>piece</span> <span m=''1804490''>should</span>
  <span m=''1804710''>be</span> <span m=''1804820''>done</span> <span m=''1806300''>preserving</span>
  <span m=''1811930''>the</span> <span m=''1812050''>environment</span> <span m=''1812350''>register.</span>
  <span m=''1817350''>Similarly,</span> <span m=''1817950''>here,</span> <span m=''1821100''>after</span>
  <span m=''1821350''>it</span> <span m=''1821440''>gets</span> <span m=''1821640''>done</span>
  <span m=''1821800''>compiling</span> <span m=''1822230''>the</span> <span m=''1822430''>first</span>
  <span m=''1822630''>operand,</span> <span m=''1823690''>it''s</span> <span m=''1823870''>going</span>
  <span m=''1823920''>to</span> <span m=''1823980''>say, I better compile--</span>
  <span m=''1825110''>I''m</span> <span m=''1825190''>going</span> <span m=''1825285''>to</span>
  <span m=''1825380''>need</span> <span m=''1825650''>to</span> <span m=''1825750''>know</span>
  <span m=''1825920''>the</span> <span m=''1826070''>environment</span> <span m=''1826740''>for</span>
  <span m=''1827060''>the</span> <span m=''1827270''>second</span> <span m=''1827470''>operand.</span>
  <span m=''1827930''>So</span> <span m=''1828040''>it</span> <span m=''1828120''>puts</span>
  <span m=''1828300''>a</span> <span m=''1828350''>little</span> <span m=''1828560''>note</span>
  <span m=''1828780''>here,</span> <span m=''1828950''>saying,</span> <span m=''1829810''>yeah,</span>
  <span m=''1829980''>this</span> <span m=''1830300''>is</span> <span m=''1830480''>also</span>
  <span m=''1830870''>done</span> <span m=''1832190''>preserving</span> <span m=''1835450''>env.</span>
  <span m=''1839680''>Now</span> <span m=''1839755''>it</span> <span m=''1839830''>goes</span>
  <span m=''1840080''>on</span> <span m=''1840230''>and</span> <span m=''1840330''>says,</span>
  <span m=''1840580''>well,</span> <span m=''1841240''>the</span> <span m=''1841510''>next</span>
  <span m=''1841870''>chunk</span> <span m=''1842180''>of</span> <span m=''1842320''>code</span>
  <span m=''1843370''>is</span> <span m=''1843570''>the</span> <span m=''1843660''>one</span>
  <span m=''1843850''>that''s</span> <span m=''1844050''>going</span> <span m=''1844130''>to</span>
  <span m=''1844210''>compile</span> <span m=''1848550''>the</span> <span m=''1848880''>second</span>
  <span m=''1849220''>argument.</span> </p><p><span m=''1850760''>And</span> <span
  m=''1851990''>let''s</span> <span m=''1852230''>say</span> <span m=''1852760''>it''ll</span>
  <span m=''1853200''>compile</span> <span m=''1853750''>it</span> <span m=''1853870''>with</span>
  <span m=''1854040''>a</span> <span m=''1857270''>targeted</span> <span m=''1857555''>to</span>
  <span m=''1857840''>val,</span> <span m=''1858430''>as</span> <span m=''1858680''>they</span>
  <span m=''1858880''>say.</span> <span m=''1863940''>And</span> <span m=''1864190''>then</span>
  <span m=''1864880''>it''ll</span> <span m=''1865080''>generate</span> <span m=''1865460''>the</span>
  <span m=''1865540''>literal</span> <span m=''1865970''>instruction,</span> <span
  m=''1867970''>building</span> <span m=''1868360''>up</span> <span m=''1868480''>the</span>
  <span m=''1868610''>argument</span> <span m=''1868990''>list.</span> <span m=''1869250''>So</span>
  <span m=''1869660''>it''ll</span> <span m=''1869940''>say,</span> <span m=''1870150''>assign</span>
  <span m=''1874480''>to</span> <span m=''1874770''>argl</span> <span m=''1880210''>cons</span>
  <span m=''1880700''>of</span> <span m=''1880860''>the</span> <span m=''1881020''>new</span>
  <span m=''1881730''>value</span> <span m=''1882050''>it</span> <span m=''1882250''>just</span>
  <span m=''1882440''>got</span> <span m=''1887480''>onto</span> <span m=''1887840''>the</span>
  <span m=''1887970''>old</span> <span m=''1888200''>argument</span> <span m=''1888590''>list.</span>
  <span m=''1894060''>However,</span> <span m=''1894910''>in</span> <span m=''1895030''>order</span>
  <span m=''1895190''>to</span> <span m=''1895370''>have</span> <span m=''1895550''>the</span>
  <span m=''1895660''>old</span> <span m=''1895850''>argument</span> <span m=''1896200''>list,</span>
  <span m=''1897160''>it</span> <span m=''1897360''>better</span> <span m=''1897610''>have</span>
  <span m=''1897780''>arranged</span> <span m=''1898530''>that</span> <span m=''1898700''>the</span>
  <span m=''1899420''>argument</span> <span m=''1899840''>list</span> <span m=''1900030''>didn''t</span>
  <span m=''1900270''>get</span> <span m=''1900440''>trashed</span> <span m=''1901270''>by</span>
  <span m=''1901410''>whatever</span> <span m=''1901740''>happened</span> <span m=''1902130''>in</span>
  <span m=''1902220''>here.</span> </p><p><span m=''1903510''>So</span> <span m=''1903680''>it</span>
  <span m=''1903800''>puts</span> <span m=''1903920''>a</span> <span m=''1903970''>little</span>
  <span m=''1904190''>note</span> <span m=''1904390''>here</span> <span m=''1904590''>and</span>
  <span m=''1904720''>says,</span> <span m=''1905410''>oh,</span> <span m=''1905800''>this</span>
  <span m=''1905990''>has</span> <span m=''1906030''>to</span> <span m=''1906070''>be</span>
  <span m=''1906200''>done</span> <span m=''1907400''>preserving</span> <span m=''1911080''>argl.</span>
  <span m=''1914380''>Now</span> <span m=''1914540''>it''s</span> <span m=''1914750''>got</span>
  <span m=''1914805''>the</span> <span m=''1914860''>argument</span> <span m=''1915250''>list</span>
  <span m=''1915410''>set</span> <span m=''1915700''>up.</span> <span m=''1918090''>And</span>
  <span m=''1919280''>it''s</span> <span m=''1919460''>all</span> <span m=''1919645''>ready</span>
  <span m=''1919830''>to</span> <span m=''1919900''>go</span> <span m=''1920200''>to</span>
  <span m=''1921640''>apply</span> <span m=''1922050''>dispatch.</span> <span m=''1926450''>It</span>
  <span m=''1927010''>generates</span> <span m=''1927580''>this</span> <span m=''1929670''>literal</span>
  <span m=''1930110''>instruction.</span> <span m=''1934990''>Because</span> <span
  m=''1935450''>now</span> <span m=''1935640''>it''s</span> <span m=''1935790''>got</span>
  <span m=''1936100''>the</span> <span m=''1936210''>arguments</span> <span m=''1936690''>in</span>
  <span m=''1936750''>argl</span> <span m=''1938250''>and</span> <span m=''1938510''>the</span>
  <span m=''1939310''>operator</span> <span m=''1939890''>in</span> <span m=''1939990''>fun,</span>
  <span m=''1940600''>but</span> <span m=''1940890''>wait,</span> <span m=''1941020''>it''s</span>
  <span m=''1941320''>only</span> <span m=''1941490''>got</span> <span m=''1941680''>the</span>
  <span m=''1941800''>operator</span> <span m=''1942250''>in</span> <span m=''1942360''>fun</span>
  <span m=''1943240''>if</span> <span m=''1943420''>it</span> <span m=''1943520''>had</span>
  <span m=''1944710''>ensured</span> <span m=''1945180''>that</span> <span m=''1945440''>this</span>
  <span m=''1945650''>block</span> <span m=''1945970''>of</span> <span m=''1946070''>code</span>
  <span m=''1947230''>didn''t</span> <span m=''1947520''>trash</span> <span m=''1947930''>what</span>
  <span m=''1948040''>was</span> <span m=''1948190''>in</span> <span m=''1948270''>the</span>
  <span m=''1948360''>function</span> <span m=''1948640''>register.</span> </p><p><span
  m=''1949600''>So</span> <span m=''1949760''>it</span> <span m=''1949880''>puts</span>
  <span m=''1949990''>a</span> <span m=''1950040''>little</span> <span m=''1950220''>note</span>
  <span m=''1950400''>here</span> <span m=''1950580''>and</span> <span m=''1950660''>says,</span>
  <span m=''1950830''>oh,</span> <span m=''1950930''>yes,</span> <span m=''1951550''>all</span>
  <span m=''1951930''>this</span> <span m=''1952090''>stuff</span> <span m=''1952350''>here</span>
  <span m=''1954860''>had</span> <span m=''1955070''>better</span> <span m=''1955280''>be</span>
  <span m=''1955410''>done</span> <span m=''1956320''>preserving</span> <span m=''1959460''>the</span>
  <span m=''1959810''>function</span> <span m=''1960160''>register.</span> <span m=''1966110''>So
  that''s the little--so when it starts ticking--so</span> <span m=''1966210''>basically,</span>
  <span m=''1966650''>what</span> <span m=''1966800''>the</span> <span m=''1968680''>compiler</span>
  <span m=''1968990''>does</span> <span m=''1969870''>is</span> <span m=''1970830''>append</span>
  <span m=''1971040''>a</span> <span m=''1971080''>whole</span> <span m=''1971270''>bunch</span>
  <span m=''1971510''>of</span> <span m=''1971600''>code</span> <span m=''1971850''>sequences.</span>
  <span m=''1973432''>See,</span> <span m=''1973860''>what</span> <span m=''1974060''>it''s</span>
  <span m=''1974140''>got</span> <span m=''1974220''>in</span> <span m=''1974560''>it</span>
  <span m=''1975610''>is</span> <span m=''1976790''>little</span> <span m=''1977040''>primitive</span>
  <span m=''1978010''>pieces</span> <span m=''1978480''>of</span> <span m=''1978580''>things,</span>
  <span m=''1978900''>like</span> <span m=''1979070''>how</span> <span m=''1979170''>to</span>
  <span m=''1979270''>look</span> <span m=''1979440''>up</span> <span m=''1979570''>a</span>
  <span m=''1979890''>symbol,</span> <span m=''1981500''>how</span> <span m=''1981620''>to</span>
  <span m=''1981740''>do</span> <span m=''1981890''>a</span> <span m=''1981940''>conditional.</span>
  <span m=''1982560''>Those</span> <span m=''1982810''>are</span> <span m=''1982920''>all</span>
  <span m=''1982990''>little</span> <span m=''1984690''>pieces</span> <span m=''1985030''>of</span>
  <span m=''1985140''>things.</span> </p><p><span m=''1985530''>And</span> <span m=''1985680''>then</span>
  <span m=''1985755''>it</span> <span m=''1985830''>appends</span> <span m=''1986250''>them</span>
  <span m=''1986390''>together</span> <span m=''1986820''>in</span> <span m=''1986920''>this</span>
  <span m=''1987060''>sort</span> <span m=''1987260''>of</span> <span m=''1987340''>discipline.</span>
  <span m=''1988810''>So</span> <span m=''1988950''>the</span> <span m=''1989070''>basic</span>
  <span m=''1989510''>means</span> <span m=''1989810''>of</span> <span m=''1989910''>combining</span>
  <span m=''1990390''>things</span> <span m=''1990940''>is</span> <span m=''1991100''>to</span>
  <span m=''1991270''>append</span> <span m=''1991890''>two</span> <span m=''1992170''>code</span>
  <span m=''1992450''>sequences.</span> <span m=''2001610''>That''s</span> <span m=''2001830''>what''s</span>
  <span m=''2002020''>going</span> <span m=''2002260''>on</span> <span m=''2002430''>here.</span>
  <span m=''2005690''>And</span> <span m=''2006070''>it''s</span> <span m=''2006370''>a</span>
  <span m=''2006580''>little</span> <span m=''2006645''>bit</span> <span m=''2006710''>tricky.</span>
  <span m=''2007590''>The</span> <span m=''2007760''>idea</span> <span m=''2007980''>is</span>
  <span m=''2008090''>that</span> <span m=''2008280''>it</span> <span m=''2008470''>appends</span>
  <span m=''2008920''>two</span> <span m=''2009230''>code</span> <span m=''2009530''>sequences,</span>
  <span m=''2011650''>taking</span> <span m=''2012020''>care</span> <span m=''2012270''>to</span>
  <span m=''2012420''>preserve</span> <span m=''2012650''>a</span> <span m=''2013060''>register.</span>
  <span m=''2015670''>So</span> <span m=''2015810''>the</span> <span m=''2015930''>actual</span>
  <span m=''2016280''>append</span> <span m=''2016600''>operation</span> <span m=''2017090''>looks</span>
  <span m=''2017290''>like</span> <span m=''2017510''>this.</span> <span m=''2019250''>What</span>
  <span m=''2019370''>it</span> <span m=''2019420''>wants</span> <span m=''2019670''>to</span>
  <span m=''2019750''>do</span> <span m=''2019960''>is</span> <span m=''2020120''>say,</span>
  <span m=''2020390''>if--</span> <span m=''2021230''>here''s</span> <span m=''2021430''>what</span>
  <span m=''2021530''>it</span> <span m=''2021600''>means</span> <span m=''2021810''>to</span>
  <span m=''2021930''>append</span> <span m=''2022960''>two</span> <span m=''2023150''>code</span>
  <span m=''2023400''>sequences.</span> <span m=''2024450''>So</span> <span m=''2024740''>if</span>
  <span m=''2024890''>sequence</span> <span m=''2025410''>one</span> <span m=''2028490''>needs</span>
  <span m=''2033310''>register--</span> <span m=''2033685''>I</span> <span m=''2034060''>should</span>
  <span m=''2034400''>change</span> <span m=''2034560''>this.</span> <span m=''2034720''>Append</span>
  <span m=''2035120''>sequence</span> <span m=''2035560''>one</span> <span m=''2035740''>to</span>
  <span m=''2035830''>sequence</span> <span m=''2036340''>two,</span> <span m=''2037200''>preserving</span>
  <span m=''2042910''>some</span> <span m=''2043390''>register.</span> <span m=''2048370''>Let</span>
  <span m=''2048540''>me</span> <span m=''2048710''>say,</span> <span m=''2048949''>and.</span>
  <span m=''2051080''>So</span> <span m=''2051270''>it''s</span> <span m=''2051460''>clear</span>
  <span m=''2051650''>that</span> <span m=''2051830''>sequence</span> <span m=''2052190''>one</span>
  <span m=''2052370''>comes</span> <span m=''2052639''>first.</span> </p><p><span
  m=''2053719''>So</span> <span m=''2055530''>if</span> <span m=''2055679''>sequence</span>
  <span m=''2056909''>two</span> <span m=''2058620''>needs</span> <span m=''2058840''>the</span>
  <span m=''2059060''>register</span> <span m=''2061190''>and</span> <span m=''2064350''>sequence</span>
  <span m=''2064830''>one</span> <span m=''2066449''>modifies</span> <span m=''2067139''>the</span>
  <span m=''2067230''>register,</span> <span m=''2073840''>then</span> <span m=''2074219''>the</span>
  <span m=''2074480''>instructions</span> <span m=''2075020''>that</span> <span m=''2075150''>the</span>
  <span m=''2075230''>compiler</span> <span m=''2075719''>spits</span> <span m=''2076010''>out</span>
  <span m=''2076909''>are,</span> <span m=''2077900''>save</span> <span m=''2080389''>the</span>
  <span m=''2080690''>register.</span> <span m=''2083380''>Here''s</span> <span m=''2083580''>the</span>
  <span m=''2083659''>code.</span> <span m=''2084440''>You</span> <span m=''2084540''>generate</span>
  <span m=''2084900''>this</span> <span m=''2085080''>code.</span> <span m=''2085280''>Save</span>
  <span m=''2085580''>the</span> <span m=''2085670''>register,</span> <span m=''2086500''>and</span>
  <span m=''2086960''>then</span> <span m=''2087070''>you</span> <span m=''2088929''>put</span>
  <span m=''2089110''>out</span> <span m=''2089310''>the</span> <span m=''2089639''>recursively</span>
  <span m=''2090860''>compiled</span> <span m=''2091570''>stuff</span> <span m=''2091830''>for</span>
  <span m=''2091949''>sequence</span> <span m=''2092380''>one.</span> <span m=''2093389''>And</span>
  <span m=''2093510''>then</span> <span m=''2093639''>you</span> <span m=''2093760''>restore</span>
  <span m=''2094150''>the</span> <span m=''2094260''>register.</span> </p><p><span
  m=''2100440''>And</span> <span m=''2100770''>then</span> <span m=''2100920''>you</span>
  <span m=''2101980''>put</span> <span m=''2102170''>out</span> <span m=''2102330''>the</span>
  <span m=''2102470''>recursively</span> <span m=''2103000''>compiled</span> <span
  m=''2103540''>stuff</span> <span m=''2104300''>for</span> <span m=''2104610''>sequence</span>
  <span m=''2105070''>two.</span> <span m=''2107330''>That''s</span> <span m=''2107520''>in</span>
  <span m=''2107590''>the</span> <span m=''2107670''>case</span> <span m=''2108020''>where</span>
  <span m=''2108770''>you</span> <span m=''2108990''>need</span> <span m=''2109200''>to</span>
  <span m=''2109290''>do</span> <span m=''2109460''>it.</span> <span m=''2109610''>Sequence</span>
  <span m=''2110070''>two</span> <span m=''2110250''>actually</span> <span m=''2110590''>needs</span>
  <span m=''2110980''>the</span> <span m=''2111130''>register,</span> <span m=''2111940''>and</span>
  <span m=''2112120''>sequence</span> <span m=''2112500''>one</span> <span m=''2112700''>actually</span>
  <span m=''2113140''>clobbers</span> <span m=''2113560''>it.</span> <span m=''2115430''>So</span>
  <span m=''2115570''>that''s</span> <span m=''2115620''>sort</span> <span m=''2115670''>of</span>
  <span m=''2115720''>if.</span> <span m=''2116320''>Otherwise,</span> <span m=''2120600''>all</span>
  <span m=''2120760''>you</span> <span m=''2120880''>spit</span> <span m=''2121170''>out</span>
  <span m=''2121420''>is</span> <span m=''2121560''>sequence</span> <span m=''2122060''>one</span>
  <span m=''2125380''>followed</span> <span m=''2125690''>by</span> <span m=''2125820''>sequence</span>
  <span m=''2126300''>two.</span> <span m=''2128240''>So</span> <span m=''2128550''>that''s</span>
  <span m=''2128770''>the</span> <span m=''2128850''>basic</span> <span m=''2129530''>operation</span>
  <span m=''2130410''>for</span> <span m=''2130750''>sticking</span> <span m=''2131100''>together</span>
  <span m=''2131460''>these</span> <span m=''2131720''>bits</span> <span m=''2132060''>of</span>
  <span m=''2132630''>code</span> <span m=''2132910''>fragments,</span> <span m=''2134040''>these</span>
  <span m=''2134230''>bits</span> <span m=''2134430''>of</span> <span m=''2134490''>instructions</span>
  <span m=''2135240''>into</span> <span m=''2135385''>a</span> <span m=''2135530''>sequence.</span>
  </p><p><span m=''2136960''>And</span> <span m=''2137120''>you</span> <span m=''2137200''>see,</span>
  <span m=''2137710''>from</span> <span m=''2137870''>this</span> <span m=''2138060''>point</span>
  <span m=''2138250''>of</span> <span m=''2138310''>view,</span> <span m=''2138490''>the</span>
  <span m=''2141140''>difference</span> <span m=''2142840''>between</span> <span m=''2143340''>the</span>
  <span m=''2143890''>interpreter</span> <span m=''2144480''>and</span> <span m=''2144590''>the</span>
  <span m=''2144710''>compiler,</span> <span m=''2145260''>in</span> <span m=''2145350''>some</span>
  <span m=''2145550''>sense,</span> <span m=''2146840''>is</span> <span m=''2147080''>that</span>
  <span m=''2147330''>where</span> <span m=''2147450''>the</span> <span m=''2147550''>compiler</span>
  <span m=''2148060''>has</span> <span m=''2148290''>these</span> <span m=''2148470''>preserving</span>
  <span m=''2148760''>notes,</span> <span m=''2150010''>and</span> <span m=''2150220''>says,</span>
  <span m=''2150410''>maybe</span> <span m=''2150760''>I''ll</span> <span m=''2151120''>actually</span>
  <span m=''2151530''>generate</span> <span m=''2151940''>the</span> <span m=''2152500''>saves</span>
  <span m=''2152705''>and</span> <span m=''2152910''>restores</span> <span m=''2153300''>and</span>
  <span m=''2153370''>maybe</span> <span m=''2153620''>I</span> <span m=''2153700''>won''t,</span>
  <span m=''2155260''>the</span> <span m=''2155410''>interpreter</span> <span m=''2155900''>being</span>
  <span m=''2156220''>maximally</span> <span m=''2156670''>pessimistic</span> <span
  m=''2157280''>always</span> <span m=''2157580''>has</span> <span m=''2157750''>a</span>
  <span m=''2157800''>save</span> <span m=''2158050''>and</span> <span m=''2158130''>restore</span>
  <span m=''2158500''>here.</span> <span m=''2159550''>That''s</span> <span m=''2161060''>the</span>
  <span m=''2161170''>essential</span> <span m=''2161510''>difference.</span> </p><p><span
  m=''2164140''>Well,</span> <span m=''2164450''>in</span> <span m=''2164520''>order</span>
  <span m=''2164690''>to</span> <span m=''2164790''>do</span> <span m=''2164980''>this,</span>
  <span m=''2165410''>of</span> <span m=''2165670''>course,</span> <span m=''2166250''>the</span>
  <span m=''2166860''>compiler</span> <span m=''2167390''>needs</span> <span m=''2167620''>some</span>
  <span m=''2167790''>theory</span> <span m=''2168800''>of</span> <span m=''2169670''>what</span>
  <span m=''2169850''>code</span> <span m=''2170100''>sequences</span> <span m=''2170610''>need</span>
  <span m=''2170775''>and</span> <span m=''2170940''>modifier</span> <span m=''2171400''>registers.</span>
  <span m=''2174330''>So</span> <span m=''2174580''>the</span> <span m=''2175220''>tiny</span>
  <span m=''2175580''>little</span> <span m=''2175790''>fragments</span> <span m=''2176330''>that</span>
  <span m=''2176460''>you</span> <span m=''2176580''>put</span> <span m=''2176770''>in,</span>
  <span m=''2176930''>like</span> <span m=''2177430''>the</span> <span m=''2177670''>basic</span>
  <span m=''2179130''>primitive</span> <span m=''2180100''>code</span> <span m=''2180430''>fragments,</span>
  <span m=''2182760''>say,</span> <span m=''2182940''>what</span> <span m=''2183150''>are</span>
  <span m=''2183200''>the</span> <span m=''2183340''>operations</span> <span m=''2184000''>that</span>
  <span m=''2184140''>you</span> <span m=''2184280''>do</span> <span m=''2184910''>when</span>
  <span m=''2185040''>you</span> <span m=''2185170''>look</span> <span m=''2185350''>up</span>
  <span m=''2185470''>a</span> <span m=''2185530''>variable?</span> <span m=''2187120''>What</span>
  <span m=''2187270''>are</span> <span m=''2187630''>the</span> <span m=''2187750''>sequence</span>
  <span m=''2188170''>of</span> <span m=''2188270''>things</span> <span m=''2188520''>that</span>
  <span m=''2188660''>you</span> <span m=''2188790''>do</span> <span m=''2189040''>when</span>
  <span m=''2189210''>you</span> <span m=''2189630''>compile</span> <span m=''2190060''>a</span>
  <span m=''2190130''>constant</span> <span m=''2190700''>or</span> <span m=''2191020''>apply</span>
  <span m=''2191225''>a</span> <span m=''2191430''>function?</span> <span m=''2192900''>Those</span>
  <span m=''2193180''>have</span> <span m=''2193330''>little</span> <span m=''2193510''>notations</span>
  <span m=''2194140''>in</span> <span m=''2194240''>there</span> <span m=''2194620''>about</span>
  <span m=''2194960''>what</span> <span m=''2195140''>they</span> <span m=''2195270''>need</span>
  <span m=''2195500''>and</span> <span m=''2195600''>what</span> <span m=''2195750''>they</span>
  <span m=''2195860''>modify.</span> </p><p><span m=''2198760''>So</span> <span m=''2199850''>the</span>
  <span m=''2200010''>bottom-level</span> <span m=''2200630''>data</span> <span m=''2200870''>structures--</span>
  <span m=''2202750''>Well,</span> <span m=''2203070''>I''ll</span> <span m=''2203840''>say</span>
  <span m=''2204010''>this.</span> <span m=''2204330''>A</span> <span m=''2204490''>code</span>
  <span m=''2204990''>sequence</span> <span m=''2206450''>to</span> <span m=''2206570''>the</span>
  <span m=''2206650''>compiler</span> <span m=''2207140''>looks</span> <span m=''2207330''>like</span>
  <span m=''2207540''>this.</span> <span m=''2208070''>It</span> <span m=''2208210''>has</span>
  <span m=''2208470''>the</span> <span m=''2209290''>actual</span> <span m=''2209720''>sequence</span>
  <span m=''2210040''>of</span> <span m=''2210500''>instructions.</span> <span m=''2215780''>And</span>
  <span m=''2215910''>then,</span> <span m=''2216040''>along</span> <span m=''2216390''>with</span>
  <span m=''2216590''>it,</span> <span m=''2217060''>there''s</span> <span m=''2217470''>the</span>
  <span m=''2220020''>set</span> <span m=''2220370''>of</span> <span m=''2221240''>registers</span>
  <span m=''2221790''>modified.</span> <span m=''2230630''>And</span> <span m=''2230780''>then</span>
  <span m=''2230930''>there''s</span> <span m=''2231110''>the</span> <span m=''2231180''>set</span>
  <span m=''2231430''>of</span> <span m=''2231540''>registers</span> <span m=''2232030''>needed.</span>
  <span m=''2239910''>So</span> <span m=''2240180''>that''s</span> <span m=''2240560''>the</span>
  <span m=''2240930''>information</span> <span m=''2241560''>the</span> <span m=''2241620''>compiler</span>
  <span m=''2242070''>has</span> <span m=''2242940''>that</span> <span m=''2243180''>it</span>
  <span m=''2243270''>draws</span> <span m=''2243640''>on</span> <span m=''2244310''>in</span>
  <span m=''2244450''>order</span> <span m=''2244730''>to</span> <span m=''2244860''>be</span>
  <span m=''2245070''>able</span> <span m=''2245220''>to</span> <span m=''2245310''>do</span>
  <span m=''2245440''>this</span> <span m=''2245650''>operation.</span> </p><p><span
  m=''2249420''>And</span> <span m=''2249690''>where</span> <span m=''2249900''>do</span>
  <span m=''2250035''>those</span> <span m=''2250170''>come</span> <span m=''2250380''>from?</span>
  <span m=''2250650''>Well,</span> <span m=''2252890''>those</span> <span m=''2253230''>come</span>
  <span m=''2253420''>from,</span> <span m=''2253800''>you</span> <span m=''2253930''>might</span>
  <span m=''2254110''>expect,</span> <span m=''2254530''>for</span> <span m=''2254610''>the</span>
  <span m=''2254710''>very</span> <span m=''2254920''>primitive</span> <span m=''2255310''>ones,</span>
  <span m=''2255540''>we''re</span> <span m=''2255630''>going</span> <span m=''2255700''>to</span>
  <span m=''2255760''>put</span> <span m=''2255920''>them</span> <span m=''2256030''>in</span>
  <span m=''2256110''>by</span> <span m=''2256270''>hand.</span> <span m=''2257230''>And</span>
  <span m=''2257440''>then,</span> <span m=''2257650''>when</span> <span m=''2257705''>we</span>
  <span m=''2257760''>combine</span> <span m=''2258200''>two</span> <span m=''2258340''>sequences,</span>
  <span m=''2258870''>we''ll</span> <span m=''2258980''>figure</span> <span m=''2259320''>out</span>
  <span m=''2259890''>what</span> <span m=''2260040''>these</span> <span m=''2260250''>things</span>
  <span m=''2260430''>should</span> <span m=''2260550''>be.</span> <span m=''2262080''>So</span>
  <span m=''2262480''>for</span> <span m=''2262640''>example,</span> <span m=''2263020''>a</span>
  <span m=''2263060''>very</span> <span m=''2263290''>primitive</span> <span m=''2263700''>one,</span>
  <span m=''2267510''>let''s</span> <span m=''2267720''>see.</span> <span m=''2268460''>How</span>
  <span m=''2268620''>about</span> <span m=''2269980''>doing</span> <span m=''2270260''>a</span>
  <span m=''2270350''>register</span> <span m=''2270820''>assignment.</span> </p><p><span
  m=''2271790''>So</span> <span m=''2271905''>a</span> <span m=''2272020''>primitive</span>
  <span m=''2272410''>sequence</span> <span m=''2273300''>might</span> <span m=''2273510''>say,</span>
  <span m=''2273670''>oh,</span> <span m=''2273800''>it''s</span> <span m=''2273960''>code</span>
  <span m=''2275160''>fragment.</span> <span m=''2276040''>Its</span> <span m=''2276230''>code</span>
  <span m=''2276450''>instruction</span> <span m=''2277170''>is</span> <span m=''2277340''>assigned</span>
  <span m=''2277870''>to</span> <span m=''2278750''>R1,</span> <span m=''2281640''>fetch</span>
  <span m=''2282080''>of</span> <span m=''2282410''>R2.</span> <span m=''2283050''>So</span>
  <span m=''2283230''>this</span> <span m=''2283420''>is</span> <span m=''2283520''>an</span>
  <span m=''2283610''>example.</span> <span m=''2285000''>That</span> <span m=''2285570''>might</span>
  <span m=''2285750''>be</span> <span m=''2286230''>an</span> <span m=''2286340''>example</span>
  <span m=''2286830''>of</span> <span m=''2286950''>a</span> <span m=''2287170''>sequence</span>
  <span m=''2287650''>of</span> <span m=''2287730''>instructions.</span> <span m=''2288510''>And</span>
  <span m=''2288990''>along</span> <span m=''2289300''>with</span> <span m=''2289460''>that,</span>
  <span m=''2289710''>it''ll</span> <span m=''2289860''>say,</span> <span m=''2290110''>oh,</span>
  <span m=''2290450''>what</span> <span m=''2290810''>I</span> <span m=''2290870''>need</span>
  <span m=''2291150''>to</span> <span m=''2293110''>remember</span> <span m=''2293610''>is</span>
  <span m=''2293810''>that</span> <span m=''2294020''>that</span> <span m=''2294220''>modifies</span>
  <span m=''2294970''>R1,</span> <span m=''2298700''>and</span> <span m=''2298860''>then</span>
  <span m=''2298990''>it</span> <span m=''2299060''>needs</span> <span m=''2300460''>R2.</span>
  <span m=''2304630''>So</span> <span m=''2305380''>when</span> <span m=''2305490''>you''re</span>
  <span m=''2305600''>first</span> <span m=''2305890''>building</span> <span m=''2306240''>this</span>
  <span m=''2306390''>compiler,</span> <span m=''2307270''>you</span> <span m=''2307370''>put</span>
  <span m=''2307540''>in</span> <span m=''2307640''>little</span> <span m=''2307830''>fragments</span>
  <span m=''2308290''>of</span> <span m=''2308370''>stuff</span> <span m=''2308650''>like</span>
  <span m=''2308840''>that.</span> </p><p><span m=''2311030''>And</span> <span m=''2311200''>now,</span>
  <span m=''2311440''>when</span> <span m=''2311690''>it</span> <span m=''2311790''>combines</span>
  <span m=''2312310''>two</span> <span m=''2312460''>sequences,</span> <span m=''2316930''>if</span>
  <span m=''2317040''>I''m</span> <span m=''2317150''>going</span> <span m=''2317240''>to</span>
  <span m=''2317320''>combine,</span> <span m=''2318960''>let''s</span> <span m=''2319170''>say,</span>
  <span m=''2320430''>sequence</span> <span m=''2321030''>one,</span> <span m=''2322920''>that</span>
  <span m=''2324460''>modifies</span> <span m=''2325550''>a</span> <span m=''2325640''>bunch</span>
  <span m=''2325900''>of</span> <span m=''2325990''>registers</span> <span m=''2326470''>M1,</span>
  <span m=''2328490''>and</span> <span m=''2329010''>needs</span> <span m=''2329480''>a</span>
  <span m=''2329530''>bunch</span> <span m=''2329790''>of</span> <span m=''2329900''>registers</span>
  <span m=''2330700''>N1.</span> <span m=''2334940''>And</span> <span m=''2335100''>I''m</span>
  <span m=''2335220''>going</span> <span m=''2335360''>to</span> <span m=''2336230''>combine</span>
  <span m=''2336900''>that</span> <span m=''2337190''>with</span> <span m=''2338380''>sequence</span>
  <span m=''2338880''>two.</span> <span m=''2340800''>That</span> <span m=''2342260''>modifies</span>
  <span m=''2343410''>a</span> <span m=''2343510''>bunch</span> <span m=''2343770''>of</span>
  <span m=''2343880''>registers</span> <span m=''2344915''>M2,</span> <span m=''2347200''>and</span>
  <span m=''2347410''>needs</span> <span m=''2347720''>a</span> <span m=''2347780''>bunch</span>
  <span m=''2348030''>of</span> <span m=''2348150''>registers</span> <span m=''2349260''>N2.</span>
  </p><p><span m=''2352590''>Then,</span> <span m=''2353660''>well,</span> <span m=''2353780''>we</span>
  <span m=''2353890''>can</span> <span m=''2354030''>reason</span> <span m=''2354280''>it</span>
  <span m=''2354370''>out.</span> <span m=''2355035''>The</span> <span m=''2355310''>new</span>
  <span m=''2355490''>code</span> <span m=''2355800''>fragment,</span> <span m=''2357170''>sequence</span>
  <span m=''2357640''>one, and--</span> <span m=''2360230''>followed</span> <span
  m=''2360720''>by</span> <span m=''2360860''>sequence</span> <span m=''2361320''>two,</span>
  <span m=''2364110''>well,</span> <span m=''2365270''>what''s</span> <span m=''2365470''>it</span>
  <span m=''2365540''>going</span> <span m=''2365610''>to</span> <span m=''2365690''>modify?</span>
  <span m=''2367760''>The</span> <span m=''2367880''>things</span> <span m=''2368090''>that</span>
  <span m=''2368200''>it</span> <span m=''2368255''>will</span> <span m=''2368310''>modify</span>
  <span m=''2368800''>are</span> <span m=''2368860''>the</span> <span m=''2368980''>things</span>
  <span m=''2369200''>that</span> <span m=''2369310''>are</span> <span m=''2369380''>modified</span>
  <span m=''2370020''>either</span> <span m=''2370320''>by</span> <span m=''2371220''>sequence</span>
  <span m=''2371650''>one</span> <span m=''2371775''>or</span> <span m=''2371900''>sequence</span>
  <span m=''2372330''>two.</span> <span m=''2373990''>So</span> <span m=''2374950''>the</span>
  <span m=''2375230''>union</span> <span m=''2375650''>of</span> <span m=''2375820''>these</span>
  <span m=''2375980''>two</span> <span m=''2377620''>sets</span> <span m=''2378150''>are</span>
  <span m=''2378220''>what</span> <span m=''2378380''>the</span> <span m=''2378460''>new</span>
  <span m=''2378600''>thing</span> <span m=''2378780''>modifies.</span> <span m=''2380530''>And</span>
  <span m=''2380660''>then</span> <span m=''2380800''>you</span> <span m=''2380870''>say,</span>
  <span m=''2381010''>well,</span> <span m=''2381150''>what is this--what</span> <span
  m=''2384940''>registers</span> <span m=''2385410''>is</span> <span m=''2385530''>it</span>
  <span m=''2385620''>going</span> <span m=''2385710''>to</span> <span m=''2385800''>need?</span>
  </p><p><span m=''2387870''>It''s</span> <span m=''2388070''>going</span> <span m=''2388150''>to</span>
  <span m=''2388230''>need</span> <span m=''2388580''>the</span> <span m=''2388670''>things</span>
  <span m=''2389140''>that</span> <span m=''2389590''>are,</span> <span m=''2390010''>first</span>
  <span m=''2390270''>of</span> <span m=''2390350''>all,</span> <span m=''2390440''>needed</span>
  <span m=''2390770''>by</span> <span m=''2390920''>sequence</span> <span m=''2391370''>one.</span>
  <span m=''2392790''>So</span> <span m=''2393050''>what</span> <span m=''2393140''>it</span>
  <span m=''2393190''>needs</span> <span m=''2393430''>is</span> <span m=''2393510''>sequence</span>
  <span m=''2393990''>one.</span> <span m=''2395250''>And</span> <span m=''2395520''>then,</span>
  <span m=''2396960''>well,</span> <span m=''2397200''>not</span> <span m=''2397390''>quite</span>
  <span m=''2397640''>all</span> <span m=''2397800''>of</span> <span m=''2397950''>the</span>
  <span m=''2398030''>ones</span> <span m=''2398310''>that</span> <span m=''2398400''>are</span>
  <span m=''2398460''>needed</span> <span m=''2398700''>by</span> <span m=''2398820''>sequence</span>
  <span m=''2399095''>one.</span> <span m=''2399760''>What</span> <span m=''2399980''>it</span>
  <span m=''2400090''>needs</span> <span m=''2400400''>are</span> <span m=''2400460''>the</span>
  <span m=''2401110''>ones</span> <span m=''2401580''>that</span> <span m=''2401900''>are</span>
  <span m=''2401960''>needed</span> <span m=''2402290''>by</span> <span m=''2402430''>sequence</span>
  <span m=''2402910''>two</span> <span m=''2403810''>that</span> <span m=''2404140''>have</span>
  <span m=''2404320''>not</span> <span m=''2404590''>been</span> <span m=''2404730''>set</span>
  <span m=''2404940''>up</span> <span m=''2405150''>by</span> <span m=''2406130''>sequence</span>
  <span m=''2406590''>one.</span> <span m=''2408070''>So</span> <span m=''2408390''>it''s</span>
  <span m=''2408530''>sort</span> <span m=''2408730''>of</span> <span m=''2408810''>the</span>
  <span m=''2408910''>union</span> <span m=''2409370''>of</span> <span m=''2411690''>the</span>
  <span m=''2411820''>things</span> <span m=''2412110''>that</span> <span m=''2412280''>sequence</span>
  <span m=''2412710''>two</span> <span m=''2412880''>needs</span> <span m=''2414500''>minus</span>
  <span m=''2415770''>the</span> <span m=''2416410''>ones</span> <span m=''2416760''>that</span>
  <span m=''2417200''>sequence</span> <span m=''2417680''>one</span> <span m=''2417850''>modifies.</span>
  <span m=''2419370''>Because</span> <span m=''2419580''>it</span> <span m=''2419700''>worries</span>
  <span m=''2419990''>about</span> <span m=''2420260''>setting</span> <span m=''2420510''>them</span>
  <span m=''2420650''>up.</span> </p><p><span m=''2424230''>So</span> <span m=''2424330''>there''s</span>
  <span m=''2424540''>the</span> <span m=''2424630''>basic</span> <span m=''2425110''>structure</span>
  <span m=''2425500''>of</span> <span m=''2425580''>the</span> <span m=''2425660''>compiler.</span>
  <span m=''2426740''>The</span> <span m=''2426850''>way</span> <span m=''2426990''>you</span>
  <span m=''2427110''>do</span> <span m=''2427270''>register</span> <span m=''2427720''>optimizations</span>
  <span m=''2429000''>is</span> <span m=''2429190''>you</span> <span m=''2430250''>have</span>
  <span m=''2430410''>some</span> <span m=''2430520''>strategies</span> <span m=''2431380''>for</span>
  <span m=''2431530''>what</span> <span m=''2431700''>needs</span> <span m=''2431900''>to</span>
  <span m=''2431990''>be</span> <span m=''2432110''>preserved.</span> <span m=''2434010''>That</span>
  <span m=''2434270''>depends</span> <span m=''2434630''>on</span> <span m=''2434760''>a</span>
  <span m=''2434800''>data</span> <span m=''2435125''>structure.</span> <span m=''2435450''>Well,</span>
  <span m=''2435760''>it</span> <span m=''2435900''>depends</span> <span m=''2436140''>on</span>
  <span m=''2436220''>the</span> <span m=''2436310''>operation</span> <span m=''2436930''>of</span>
  <span m=''2437010''>what</span> <span m=''2437140''>it</span> <span m=''2437240''>means</span>
  <span m=''2437500''>to</span> <span m=''2437600''>put</span> <span m=''2437780''>things</span>
  <span m=''2437990''>together.</span> <span m=''2439080''>Preserving</span> <span
  m=''2439560''>something,</span> <span m=''2439930''>that</span> <span m=''2440100''>depends</span>
  <span m=''2440710''>on</span> <span m=''2440980''>knowing</span> <span m=''2441990''>what</span>
  <span m=''2444710''>registers</span> <span m=''2445180''>are</span> <span m=''2445250''>needed</span>
  <span m=''2445580''>and</span> <span m=''2445670''>modified</span> <span m=''2446200''>by</span>
  <span m=''2446300''>these</span> <span m=''2446500''>code</span> <span m=''2446740''>fragments.</span>
  </p><p><span m=''2448900''>That</span> <span m=''2449070''>depends</span> <span
  m=''2449410''>on</span> <span m=''2449520''>having</span> <span m=''2450110''>little</span>
  <span m=''2450350''>data</span> <span m=''2450600''>structures,</span> <span m=''2451480''>which</span>
  <span m=''2451640''>say,</span> <span m=''2452630''>a</span> <span m=''2452820''>code</span>
  <span m=''2453140''>sequence</span> <span m=''2453640''>is</span> <span m=''2454160''>the</span>
  <span m=''2454300''>actual</span> <span m=''2454660''>instructions,</span> <span
  m=''2455680''>what</span> <span m=''2455850''>they</span> <span m=''2455960''>modify</span>
  <span m=''2456450''>and</span> <span m=''2456660''>what</span> <span m=''2456715''>they</span>
  <span m=''2456770''>need.</span> <span m=''2457350''>That</span> <span m=''2457650''>comes</span>
  <span m=''2458010''>from,</span> <span m=''2458230''>at</span> <span m=''2458300''>the</span>
  <span m=''2458390''>primitive</span> <span m=''2458750''>level,</span> <span m=''2459030''>building</span>
  <span m=''2459370''>it</span> <span m=''2459460''>in.</span> <span m=''2460240''>At</span>
  <span m=''2460480''>the</span> <span m=''2460720''>primitive</span> <span m=''2461050''>level,</span>
  <span m=''2461300''>it''s</span> <span m=''2461420''>going</span> <span m=''2461490''>to</span>
  <span m=''2461570''>be</span> <span m=''2461640''>completely</span> <span m=''2462070''>obvious</span>
  <span m=''2462800''>what</span> <span m=''2463220''>something</span> <span m=''2463490''>needs</span>
  <span m=''2463690''>and</span> <span m=''2463770''>modifies.</span> <span m=''2464850''>Plus,</span>
  <span m=''2465440''>this</span> <span m=''2465760''>particular</span> <span m=''2466780''>way</span>
  <span m=''2467010''>that</span> <span m=''2467180''>says,</span> <span m=''2467340''>when</span>
  <span m=''2467470''>I</span> <span m=''2467540''>build</span> <span m=''2467810''>up</span>
  <span m=''2467860''>bigger</span> <span m=''2468160''>ones,</span> <span m=''2469360''>here''s</span>
  <span m=''2469560''>how</span> <span m=''2469660''>I</span> <span m=''2469760''>generate</span>
  <span m=''2470230''>the</span> <span m=''2470270''>new</span> <span m=''2470390''>set</span>
  <span m=''2470590''>of</span> <span m=''2470710''>registers</span> <span m=''2471130''>modified</span>
  <span m=''2472020''>and</span> <span m=''2472075''>the</span> <span m=''2472130''>new</span>
  <span m=''2472320''>set</span> <span m=''2472500''>of</span> <span m=''2472590''>registers</span>
  <span m=''2473020''>needed.</span> </p><p><span m=''2475010''>And</span> <span m=''2475300''>that''s
  the</span> <span m=''2475590''>whole--</span> <span m=''2476120''>well,</span> <span
  m=''2476450''>I</span> <span m=''2476530''>shouldn''t</span> <span m=''2476730''>say</span>
  <span m=''2476850''>that''s</span> <span m=''2477050''>the</span> <span m=''2477120''>whole</span>
  <span m=''2477310''>thing.</span> <span m=''2477810''>That''s</span> <span m=''2478070''>the</span>
  <span m=''2478140''>whole</span> <span m=''2478310''>thing</span> <span m=''2478500''>except</span>
  <span m=''2478800''>for</span> <span m=''2478960''>about</span> <span m=''2480120''>30</span>
  <span m=''2480380''>pages</span> <span m=''2480770''>of</span> <span m=''2480850''>details</span>
  <span m=''2481320''>in</span> <span m=''2481415''>the</span> <span m=''2481510''>book.</span>
  <span m=''2481860''>But</span> <span m=''2482540''>it</span> <span m=''2482640''>is</span>
  <span m=''2483680''>a</span> <span m=''2483740''>perfectly</span> <span m=''2486150''>usable</span>
  <span m=''2486530''>rudimentary</span> <span m=''2487010''>compiler.</span> <span
  m=''2488880''>Let</span> <span m=''2488930''>me</span> <span m=''2489430''>kind</span>
  <span m=''2489600''>of</span> <span m=''2489660''>show</span> <span m=''2489870''>you</span>
  <span m=''2490070''>what</span> <span m=''2491030''>it</span> <span m=''2491130''>does.</span>
  </p><p><span m=''2491390''>Suppose</span> <span m=''2491560''>we</span> <span m=''2491660''>start</span>
  <span m=''2491930''>out</span> <span m=''2492110''>with</span> <span m=''2494070''>recursive</span>
  <span m=''2494520''>factorial.</span> <span m=''2496330''>And</span> <span m=''2496440''>these</span>
  <span m=''2496510''>slides</span> <span m=''2496840''>are</span> <span m=''2496890''>going</span>
  <span m=''2496970''>to</span> <span m=''2497060''>be</span> <span m=''2497140''>much</span>
  <span m=''2497400''>too</span> <span m=''2497940''>small</span> <span m=''2498240''>to</span>
  <span m=''2498290''>read.</span> <span m=''2498590''>I</span> <span m=''2498760''>just</span>
  <span m=''2498830''>want</span> <span m=''2498900''>to</span> <span m=''2499040''>flash</span>
  <span m=''2499340''>through</span> <span m=''2499470''>the</span> <span m=''2499560''>code</span>
  <span m=''2499800''>and</span> <span m=''2499880''>show</span> <span m=''2499990''>you</span>
  <span m=''2500110''>about</span> <span m=''2500370''>how</span> <span m=''2500490''>much</span>
  <span m=''2500750''>it</span> <span m=''2500800''>is.</span> <span m=''2504460''>That
  starts out with--here''s</span> <span m=''2504620''>a</span> <span m=''2504680''>first</span>
  <span m=''2504980''>block</span> <span m=''2505290''>of</span> <span m=''2505400''>it,</span>
  <span m=''2506010''>where</span> <span m=''2506150''>it</span> <span m=''2506220''>compiles</span>
  <span m=''2506700''>a</span> <span m=''2506760''>procedure</span> <span m=''2507250''>entry</span>
  <span m=''2507380''>and</span> <span m=''2507720''>does</span> <span m=''2507830''>a</span>
  <span m=''2507880''>bunch</span> <span m=''2508120''>of</span> <span m=''2508190''>assignments.</span>
  <span m=''2508740''>And</span> <span m=''2508810''>this</span> <span m=''2508980''>thing</span>
  <span m=''2509140''>is</span> <span m=''2509550''>basically</span> <span m=''2510470''>up</span>
  <span m=''2510620''>through</span> <span m=''2510790''>the</span> <span m=''2510900''>part</span>
  <span m=''2511190''>where</span> <span m=''2511390''>it</span> <span m=''2512750''>sets</span>
  <span m=''2513000''>up</span> <span m=''2513100''>to</span> <span m=''2513200''>do</span>
  <span m=''2513300''>the</span> <span m=''2513400''>predicate</span> <span m=''2514380''>and</span>
  <span m=''2515040''>test</span> <span m=''2515340''>whether</span> <span m=''2515500''>the</span>
  <span m=''2515610''>predicate''s</span> <span m=''2516050''>true.</span> </p><p><span
  m=''2516830''>The</span> <span m=''2517170''>second</span> <span m=''2517520''>part</span>
  <span m=''2518560''>is</span> <span m=''2518770''>what</span> <span m=''2518950''>results
  from--</span> <span m=''2519530''>in</span> <span m=''2519690''>the</span> <span
  m=''2520010''>recursive</span> <span m=''2520460''>call</span> <span m=''2520770''>to</span>
  <span m=''2522280''>fact</span> <span m=''2522680''>of</span> <span m=''2522745''>n</span>
  <span m=''2522810''>minus</span> <span m=''2523160''>one.</span> <span m=''2524210''>And</span>
  <span m=''2524400''>this</span> <span m=''2524560''>last</span> <span m=''2524850''>part</span>
  <span m=''2526150''>is</span> <span m=''2526380''>coming</span> <span m=''2526670''>back</span>
  <span m=''2526970''>from</span> <span m=''2527130''>that</span> <span m=''2527900''>and</span>
  <span m=''2528200''>then</span> <span m=''2528460''>taking</span> <span m=''2528750''>care</span>
  <span m=''2528910''>of</span> <span m=''2528960''>the</span> <span m=''2529040''>constant</span>
  <span m=''2529480''>case.</span> <span m=''2529890''>So</span> <span m=''2530060''>that''s</span>
  <span m=''2530240''>about</span> <span m=''2530600''>how</span> <span m=''2530740''>much</span>
  <span m=''2531000''>code</span> <span m=''2531900''>it</span> <span m=''2532010''>would</span>
  <span m=''2532110''>produce</span> <span m=''2532400''>for</span> <span m=''2532510''>factorial.</span>
  </p><p><span m=''2533760''>We</span> <span m=''2533870''>could</span> <span m=''2534000''>make</span>
  <span m=''2534200''>this</span> <span m=''2534340''>compiler</span> <span m=''2534760''>much,</span>
  <span m=''2535100''>much</span> <span m=''2535380''>better,</span> <span m=''2537170''>of</span>
  <span m=''2537300''>course.</span> <span m=''2538380''>The</span> <span m=''2539430''>main</span>
  <span m=''2539740''>way</span> <span m=''2539870''>we</span> <span m=''2540030''>could</span>
  <span m=''2540170''>make</span> <span m=''2540370''>it</span> <span m=''2540460''>better</span>
  <span m=''2541060''>is</span> <span m=''2541320''>to</span> <span m=''2541480''>allow</span>
  <span m=''2541770''>the</span> <span m=''2541870''>compiler</span> <span m=''2542380''>to</span>
  <span m=''2542630''>make</span> <span m=''2542890''>any</span> <span m=''2543110''>assumptions</span>
  <span m=''2543650''>at</span> <span m=''2543890''>all</span> <span m=''2544290''>about</span>
  <span m=''2544600''>what</span> <span m=''2544720''>happens</span> <span m=''2545070''>when</span>
  <span m=''2545180''>you</span> <span m=''2545290''>call</span> <span m=''2545680''>a</span>
  <span m=''2545730''>procedure.</span> <span m=''2546990''>So</span> <span m=''2547170''>this</span>
  <span m=''2547370''>compiler,</span> <span m=''2547850''>for</span> <span m=''2547990''>instance,</span>
  <span m=''2548330''>doesn''t</span> <span m=''2548640''>even</span> <span m=''2549630''>know,</span>
  <span m=''2550810''>say,</span> <span m=''2551020''>that</span> <span m=''2551470''>multiplication</span>
  <span m=''2553240''>is</span> <span m=''2554580''>something</span> <span m=''2554890''>that</span>
  <span m=''2555030''>could</span> <span m=''2555150''>be</span> <span m=''2555260''>coded</span>
  <span m=''2555590''>in</span> <span m=''2555720''>line.</span> <span m=''2556030''>Instead,</span>
  <span m=''2556320''>it</span> <span m=''2556450''>sets</span> <span m=''2556680''>up</span>
  <span m=''2556770''>this</span> <span m=''2556930''>whole</span> <span m=''2557070''>mechanism.</span>
  <span m=''2557670''>It</span> <span m=''2558060''>goes</span> <span m=''2558250''>to</span>
  <span m=''2558360''>apply-dispatch.</span> </p><p><span m=''2561430''>That''s</span>
  <span m=''2561700''>a</span> <span m=''2561760''>tremendous</span> <span m=''2562210''>waste,</span>
  <span m=''2562580''>because</span> <span m=''2562900''>what</span> <span m=''2563060''>you</span>
  <span m=''2563180''>do</span> <span m=''2563510''>every</span> <span m=''2563740''>time</span>
  <span m=''2563900''>you</span> <span m=''2564010''>go</span> <span m=''2564120''>to</span>
  <span m=''2564220''>apply-dispatch</span> <span m=''2564800''>is</span> <span m=''2565120''>you</span>
  <span m=''2565240''>have</span> <span m=''2565350''>to</span> <span m=''2565470''>concept</span>
  <span m=''2565900''>this</span> <span m=''2566060''>argument</span> <span m=''2566470''>list,</span>
  <span m=''2567480''>because</span> <span m=''2567810''>it''s</span> <span m=''2567920''>a</span>
  <span m=''2567950''>very</span> <span m=''2568140''>general</span> <span m=''2568490''>thing</span>
  <span m=''2568640''>you''re</span> <span m=''2568770''>going</span> <span m=''2569040''>to.</span>
  <span m=''2569170''>In</span> <span m=''2569300''>any</span> <span m=''2569870''>real</span>
  <span m=''2570100''>compiler,</span> <span m=''2570650''>of</span> <span m=''2570740''>course,</span>
  <span m=''2571010''>you''re</span> <span m=''2571110''>going</span> <span m=''2571200''>to</span>
  <span m=''2571280''>have</span> <span m=''2571510''>registers</span> <span m=''2572370''>for</span>
  <span m=''2572500''>holding</span> <span m=''2572790''>arguments.</span> <span m=''2573830''>And</span>
  <span m=''2573970''>you''re</span> <span m=''2574060''>going</span> <span m=''2574140''>to</span>
  <span m=''2574230''>start</span> <span m=''2574490''>preserving</span> <span m=''2575010''>and</span>
  <span m=''2576350''>saving</span> <span m=''2576830''>the</span> <span m=''2576910''>way</span>
  <span m=''2577060''>you</span> <span m=''2577200''>use</span> <span m=''2577340''>those</span>
  <span m=''2577480''>registers</span> <span m=''2577960''>similar</span> <span m=''2580350''>to</span>
  <span m=''2580450''>the</span> <span m=''2580510''>same</span> <span m=''2580740''>strategy</span>
  <span m=''2581200''>here.</span> </p><p><span m=''2582442''>So</span> <span m=''2582900''>that''s</span>
  <span m=''2584170''>probably</span> <span m=''2584520''>the</span> <span m=''2584630''>very</span>
  <span m=''2585490''>main</span> <span m=''2585790''>way</span> <span m=''2585920''>that</span>
  <span m=''2586070''>this</span> <span m=''2586230''>particular</span> <span m=''2586700''>compiler</span>
  <span m=''2587180''>in</span> <span m=''2587250''>the</span> <span m=''2587320''>book</span>
  <span m=''2587530''>could</span> <span m=''2587660''>be</span> <span m=''2587800''>fixed.</span>
  <span m=''2588940''>There</span> <span m=''2589070''>are</span> <span m=''2589100''>other</span>
  <span m=''2589280''>things</span> <span m=''2589560''>like</span> <span m=''2589740''>looking</span>
  <span m=''2590030''>up</span> <span m=''2590120''>variable</span> <span m=''2590570''>values</span>
  <span m=''2591170''>and</span> <span m=''2592010''>making</span> <span m=''2592340''>more</span>
  <span m=''2592520''>efficient</span> <span m=''2592870''>primitive</span> <span
  m=''2593210''>operations</span> <span m=''2593830''>and</span> <span m=''2593890''>all</span>
  <span m=''2594010''>sorts</span> <span m=''2594230''>of</span> <span m=''2594320''>things.</span>
  <span m=''2594490''>Essentially,</span> <span m=''2595550''>a</span> <span m=''2595740''>good</span>
  <span m=''2595950''>Lisp</span> <span m=''2596170''>compiler</span> <span m=''2596650''>can</span>
  <span m=''2596800''>absorb</span> <span m=''2597150''>an</span> <span m=''2597260''>arbitrary</span>
  <span m=''2597820''>amount</span> <span m=''2597930''>of</span> <span m=''2598180''>effort.</span>
  <span m=''2599780''>And</span> <span m=''2600100''>probably</span> <span m=''2600670''>one</span>
  <span m=''2600910''>of</span> <span m=''2601000''>the</span> <span m=''2601090''>reasons</span>
  <span m=''2601940''>that</span> <span m=''2602180''>Lisp</span> <span m=''2602450''>is</span>
  <span m=''2602560''>slow</span> <span m=''2603670''>with</span> <span m=''2603820''>compared</span>
  <span m=''2604200''>to</span> <span m=''2604300''>languages</span> <span m=''2604770''>like</span>
  <span m=''2604970''>FORTRAN</span> <span m=''2606070''>is</span> <span m=''2606250''>that,</span>
  <span m=''2606430''>if</span> <span m=''2606610''>you</span> <span m=''2607290''>look</span>
  <span m=''2607470''>over</span> <span m=''2607720''>history</span> <span m=''2608100''>at</span>
  <span m=''2608210''>the</span> <span m=''2608350''>amount</span> <span m=''2608760''>of</span>
  <span m=''2608920''>effort</span> <span m=''2609240''>that''s</span> <span m=''2609450''>gone</span>
  <span m=''2609650''>into</span> <span m=''2609860''>building</span> <span m=''2610220''>Lisp</span>
  <span m=''2610410''>compilers,</span> <span m=''2610970''>it''s</span> <span m=''2611130''>nowhere</span>
  <span m=''2611440''>near</span> <span m=''2611630''>the</span> <span m=''2611780''>amount</span>
  <span m=''2612020''>of</span> <span m=''2612110''>effort</span> <span m=''2612350''>that''s</span>
  <span m=''2612540''>gone</span> <span m=''2612710''>into</span> <span m=''2612880''>FORTRAN</span>
  <span m=''2613260''>compilers.</span> <span m=''2614520''>And</span> <span m=''2614730''>maybe</span>
  <span m=''2614940''>that''s</span> <span m=''2615130''>something</span> <span m=''2615400''>that</span>
  <span m=''2616090''>will</span> <span m=''2616180''>change</span> <span m=''2616500''>over</span>
  <span m=''2616610''>the</span> <span m=''2616760''>next</span> <span m=''2616910''>couple</span>
  <span m=''2617120''>of</span> <span m=''2617190''>years.</span> </p><p><span m=''2618250''>OK,</span>
  <span m=''2618360''>let''s</span> <span m=''2618540''>break.</span> <span m=''2623950''>Questions?</span>
  </p><p><span m=''2628370''>AUDIENCE: One</span> <span m=''2628465''>of</span> <span
  m=''2628560''>the</span> <span m=''2628640''>very</span> <span m=''2628860''>first</span>
  <span m=''2629160''>classes--</span> <span m=''2629590''>I</span> <span m=''2630020''>don''t</span>
  <span m=''2630110''>know</span> <span m=''2630200''>if</span> <span m=''2630256''>it</span>
  <span m=''2630313''>was</span> <span m=''2630370''>during</span> <span m=''2630570''>class</span>
  <span m=''2631010''>or</span> <span m=''2631080''>after</span> <span m=''2631150''>class-</span>
  <span m=''2631560''>you</span> <span m=''2632180''>showed</span> <span m=''2632480''>me</span>
  <span m=''2632650''>the,</span> <span m=''2633990''>say,</span> <span m=''2634530''>addition</span>
  <span m=''2634900''>has</span> <span m=''2635480''>a</span> <span m=''2636150''>primitive</span>
  <span m=''2636590''>that</span> <span m=''2636700''>we</span> <span m=''2636800''>don''t</span>
  <span m=''2637040''>see,</span> <span m=''2637740''>and-percent</span> <span m=''2638010''>add</span>
  <span m=''2638170''>or</span> <span m=''2638430''>something</span> <span m=''2638710''>like</span>
  <span m=''2638910''>that.</span> <span m=''2640720''>Is</span> <span m=''2640850''>that</span>
  <span m=''2641060''>because,</span> <span m=''2641620''>if</span> <span m=''2641750''>you''re</span>
  <span m=''2641840''>doing</span> <span m=''2642050''>inline</span> <span m=''2642390''>code</span>
  <span m=''2642640''>you''d</span> <span m=''2642780''>want</span> <span m=''2643070''>to</span>
  <span m=''2644380''>just</span> <span m=''2644610''>do</span> <span m=''2644760''>it</span>
  <span m=''2644870''>for</span> <span m=''2644990''>two</span> <span m=''2646490''>operators,</span>
  <span m=''2647480''>operands?</span> <span m=''2648540''>But</span> <span m=''2648990''>if</span>
  <span m=''2649100''>you</span> <span m=''2649500''>had</span> <span m=''2649680''>more</span>
  <span m=''2649890''>operands,</span> <span m=''2650380''>you''d</span> <span m=''2650437''>want</span>
  <span m=''2650495''>to</span> <span m=''2650552''>do</span> <span m=''2650610''>something</span>
  <span m=''2650930''>special?</span> </p><p><span m=''2652800''>PROFESSOR: Yeah,</span>
  <span m=''2653350''>you''re</span> <span m=''2653500''>looking</span> <span m=''2654440''>in</span>
  <span m=''2654550''>the</span> <span m=''2654650''>actual</span> <span m=''2654960''>scheme</span>
  <span m=''2655290''>implementation.</span> <span m=''2655980''>There''s</span> <span
  m=''2656170''>a</span> <span m=''2656230''>plus,</span> <span m=''2656690''>and</span>
  <span m=''2656775''>a</span> <span m=''2656860''>plus</span> <span m=''2657130''>is</span>
  <span m=''2657190''>some</span> <span m=''2657430''>operator.</span> <span m=''2657880''>And</span>
  <span m=''2658030''>then</span> <span m=''2658080''>if</span> <span m=''2658130''>you</span>
  <span m=''2658530''>go</span> <span m=''2658690''>look</span> <span m=''2658880''>inside</span>
  <span m=''2659210''>the</span> <span m=''2659290''>code</span> <span m=''2659520''>for</span>
  <span m=''2659620''>plus,</span> <span m=''2660390''>you</span> <span m=''2660470''>see</span>
  <span m=''2660630''>something</span> <span m=''2660970''>called--</span> <span m=''2661440''>I</span>
  <span m=''2661610''>forget--</span> <span m=''2661880''>and-percent</span> <span
  m=''2662840''>plus</span> <span m=''2663160''>or</span> <span m=''2663240''>something</span>
  <span m=''2663560''>like</span> <span m=''2663760''>that.</span> <span m=''2664640''>And</span>
  <span m=''2664780''>what''s</span> <span m=''2664990''>going</span> <span m=''2665260''>on</span>
  <span m=''2665480''>there</span> <span m=''2665670''>is</span> <span m=''2665770''>that</span>
  <span m=''2665990''>particular</span> <span m=''2666680''>kind</span> <span m=''2666930''>of</span>
  <span m=''2667190''>optimization.</span> <span m=''2668540''>Because,</span> <span
  m=''2668860''>see,</span> <span m=''2668940''>general</span> <span m=''2669330''>plus</span>
  <span m=''2670130''>takes</span> <span m=''2670460''>an</span> <span m=''2670520''>arbitrary</span>
  <span m=''2671020''>number</span> <span m=''2671270''>of</span> <span m=''2671360''>arguments.</span>
  </p><p><span m=''2674750''>So</span> <span m=''2675220''>the</span> <span m=''2675310''>most</span>
  <span m=''2675610''>general</span> <span m=''2675900''>plus</span> <span m=''2676770''>says,</span>
  <span m=''2677080''>oh,</span> <span m=''2677310''>if</span> <span m=''2677380''>I</span>
  <span m=''2677450''>have</span> <span m=''2677520''>an</span> <span m=''2677600''>argument</span>
  <span m=''2678020''>list,</span> <span m=''2678310''>I''d</span> <span m=''2678440''>better</span>
  <span m=''2679320''>cons</span> <span m=''2679740''>it</span> <span m=''2679815''>up</span>
  <span m=''2679890''>in</span> <span m=''2680000''>some</span> <span m=''2680240''>list</span>
  <span m=''2681700''>and</span> <span m=''2681880''>then</span> <span m=''2682000''>figure</span>
  <span m=''2682330''>out</span> <span m=''2682400''>how</span> <span m=''2682490''>many</span>
  <span m=''2682750''>there</span> <span m=''2682900''>were</span> <span m=''2683080''>or</span>
  <span m=''2683260''>something</span> <span m=''2683600''>like</span> <span m=''2683790''>that.</span>
  <span m=''2684880''>That''s</span> <span m=''2685100''>terribly</span> <span m=''2685550''>inefficient,</span>
  <span m=''2686740''>especially</span> <span m=''2687250''>since</span> <span m=''2687450''>most</span>
  <span m=''2687590''>of</span> <span m=''2687740''>the</span> <span m=''2687820''>time</span>
  <span m=''2688020''>you''re</span> <span m=''2688100''>probably</span> <span m=''2688480''>adding</span>
  <span m=''2688690''>two</span> <span m=''2688840''>numbers.</span> <span m=''2689200''>You</span>
  <span m=''2689310''>don''t</span> <span m=''2689470''>want</span> <span m=''2689570''>to</span>
  <span m=''2689670''>really</span> <span m=''2689890''>have</span> <span m=''2690010''>to</span>
  <span m=''2690130''>cons</span> <span m=''2690600''>this</span> <span m=''2690790''>argument</span>
  <span m=''2690980''>list.</span> <span m=''2692030''>So</span> <span m=''2692200''>what</span>
  <span m=''2692340''>you''d</span> <span m=''2692480''>like</span> <span m=''2692700''>to</span>
  <span m=''2692810''>do</span> <span m=''2693340''>is</span> <span m=''2693540''>build</span>
  <span m=''2695660''>the</span> <span m=''2695860''>code</span> <span m=''2696160''>for</span>
  <span m=''2696300''>plus</span> <span m=''2696650''>with</span> <span m=''2696740''>a</span>
  <span m=''2696820''>bunch</span> <span m=''2697050''>of</span> <span m=''2697150''>entries.</span>
  </p><p><span m=''2698170''>So</span> <span m=''2698390''>most</span> <span m=''2698710''>of</span>
  <span m=''2698810''>what</span> <span m=''2698960''>it''s</span> <span m=''2699120''>doing</span>
  <span m=''2699410''>is</span> <span m=''2699550''>the</span> <span m=''2699630''>same.</span>
  <span m=''2700170''>However,</span> <span m=''2700860''>there</span> <span m=''2700990''>might</span>
  <span m=''2701190''>be</span> <span m=''2701280''>a</span> <span m=''2701330''>special</span>
  <span m=''2701760''>entry</span> <span m=''2702010''>that</span> <span m=''2702140''>you''d</span>
  <span m=''2702270''>go</span> <span m=''2702450''>to</span> <span m=''2702630''>if</span>
  <span m=''2702720''>you</span> <span m=''2702810''>knew</span> <span m=''2702910''>there</span>
  <span m=''2702995''>were</span> <span m=''2703080''>only</span> <span m=''2703240''>two</span>
  <span m=''2703420''>arguments.</span> <span m=''2704640''>And</span> <span m=''2704790''>those</span>
  <span m=''2705020''>you''ll</span> <span m=''2705100''>put</span> <span m=''2705270''>in</span>
  <span m=''2705390''>registers.</span> <span m=''2705910''>They</span> <span m=''2705990''>won''t</span>
  <span m=''2706190''>be</span> <span m=''2706290''>in</span> <span m=''2706370''>an</span>
  <span m=''2706450''>argument</span> <span m=''2706820''>list</span> <span m=''2707060''>and</span>
  <span m=''2707140''>you</span> <span m=''2707220''>won''t</span> <span m=''2707350''>have</span>
  <span m=''2707470''>to</span> <span m=''2707590''>[UNINTELLIGIBLE].</span> <span
  m=''2709080''>That''s</span> <span m=''2709270''>how</span> <span m=''2709400''>a</span>
  <span m=''2709510''>lot</span> <span m=''2709620''>of</span> <span m=''2709730''>these</span>
  <span m=''2709900''>things</span> <span m=''2710100''>work.</span> <span m=''2712570''>OK,</span>
  <span m=''2712800''>let''s</span> <span m=''2712980''>take</span> <span m=''2713120''>a</span>
  <span m=''2713160''>break.</span> </p><p><span m=''2713948''>[MUSIC PLAYING]</span>
  </p>'
type: course
uid: d2102ce55255210d335802fb34d064dd

---
None