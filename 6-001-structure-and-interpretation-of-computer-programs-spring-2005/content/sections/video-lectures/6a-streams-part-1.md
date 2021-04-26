---
about_this_resource_text: <p><b>Topics covered:</b> Streams, Part 1</p> <p><b> Instructors:</b>
  Hal Abelson and Gerald Jay Sussman</p> <p>Subtitles for this course are provided
  through the generous assistance of Henry Baker, Hoofar Pourzand, Heather Wood, Aleksejs
  Truhans, Steven Edwards, George Menhorn, and Mahendra Kumar.</p>
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
embedded_media:
- id: 6A.jpg
  parent_uid: 4deb9a54f9169779089387b55bd5135a
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/6a-streams-part-1/6A.jpg
  title: 6A.jpg
  type: null
  uid: f9f754d132bac988a9e8ca884d0e20a1
- id: Video-YouTube-Stream
  media_location: JkGKLILLy0I
  parent_uid: 4deb9a54f9169779089387b55bd5135a
  title: Video-YouTube-Stream
  type: Video
  uid: ab6aa1008c5dff457cb7851e5777c9c6
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT_Structure_of_Computer_Programs_1986/lec6a.mp4
  parent_uid: 4deb9a54f9169779089387b55bd5135a
  title: Video-Internet Archive-MP4
  type: Video
  uid: 5408073b4d521062e74b8e7ec5f1515b
- id: Thumbnail-OCW-JPG
  parent_uid: 4deb9a54f9169779089387b55bd5135a
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: f5cb0be20ea498cd6e0ab6bc18de5d24
- id: 3Play-3PlayYouTubeid-MP4
  media_location: JkGKLILLy0I
  parent_uid: 4deb9a54f9169779089387b55bd5135a
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 72097f3a1f70dceb0263b80375436eea
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/JkGKLILLy0I/default.jpg
  parent_uid: 4deb9a54f9169779089387b55bd5135a
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 10e3f2f9c57ab586d70b09ce6e594c6b
- id: JkGKLILLy0I.srt
  parent_uid: 4deb9a54f9169779089387b55bd5135a
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/6a-streams-part-1/JkGKLILLy0I.srt
  title: 3play caption file
  type: null
  uid: 6255b3217d34f235e4695fb73bd92c1a
- id: JkGKLILLy0I.pdf
  parent_uid: 4deb9a54f9169779089387b55bd5135a
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/6a-streams-part-1/JkGKLILLy0I.pdf
  title: 3play pdf file
  type: null
  uid: d196a566ea0e1f1ea0d866431de4560c
- id: Caption-3Play YouTube id-SRT
  parent_uid: 4deb9a54f9169779089387b55bd5135a
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 1dea98596c39dcdee534b32b9fd8f9e4
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 4deb9a54f9169779089387b55bd5135a
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: cc97d622a0110f70c6b6b1dc5607b729
inline_embed_id: 711422216a:streams,part142698100
layout: video
order_index: null
parent_uid: 4fcacad2c29981dd668a6b29822403cc
related_resources_text: ''
short_url: 6a-streams-part-1
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/6a-streams-part-1
template_type: Tabbed
title: '6A: Streams, Part 1'
transcript: '<p><span m=''18550''>PROFESSOR: Well,</span> <span m=''18780''>last</span>
  <span m=''19010''>time</span> <span m=''20110''>Gerry</span> <span m=''20400''>really</span>
  <span m=''20660''>let</span> <span m=''20820''>the</span> <span m=''20900''>cat</span>
  <span m=''21140''>out</span> <span m=''21230''>of</span> <span m=''21320''>the</span>
  <span m=''21400''>bag.</span> <span m=''22230''>He</span> <span m=''22770''>introduced</span>
  <span m=''23210''>the</span> <span m=''23330''>idea</span> <span m=''23650''>of</span>
  <span m=''23760''>assignment.</span> <span m=''26350''>Assignment</span> <span m=''32890''>and</span>
  <span m=''33060''>state.</span> <span m=''37620''>And</span> <span m=''37790''>as</span>
  <span m=''38290''>we</span> <span m=''38410''>started</span> <span m=''38750''>to</span>
  <span m=''38830''>see,</span> <span m=''39030''>the</span> <span m=''39130''>implications</span>
  <span m=''40800''>of</span> <span m=''41000''>introducing</span> <span m=''41500''>assignment</span>
  <span m=''42050''>and</span> <span m=''42210''>state</span> <span m=''42580''>into</span>
  <span m=''42730''>the</span> <span m=''42890''>language</span> <span m=''43270''>are</span>
  <span m=''43330''>absolutely</span> <span m=''43860''>frightening.</span> <span
  m=''45350''>First</span> <span m=''45620''>of</span> <span m=''45710''>all,</span>
  <span m=''46090''>the</span> <span m=''46260''>substitution</span> <span m=''46880''>model</span>
  <span m=''47140''>of</span> <span m=''47240''>evaluation</span> <span m=''47860''>breaks</span>
  <span m=''48140''>down.</span> <span m=''48865''>And</span> <span m=''49270''>we</span>
  <span m=''49430''>have</span> <span m=''49560''>to</span> <span m=''49650''>use</span>
  <span m=''49800''>this</span> <span m=''49910''>much</span> <span m=''50150''>more</span>
  <span m=''50290''>complicated</span> <span m=''51650''>environment</span> <span
  m=''52210''>model</span> <span m=''52550''>and</span> <span m=''52650''>this</span>
  <span m=''52750''>very</span> <span m=''52950''>mechanistic</span> <span m=''53510''>thing</span>
  <span m=''53650''>with</span> <span m=''53780''>diagrams,</span> <span m=''54290''>even</span>
  <span m=''54570''>to</span> <span m=''54660''>say</span> <span m=''55250''>what</span>
  <span m=''55470''>statements</span> <span m=''55920''>in</span> <span m=''55970''>the</span>
  <span m=''56050''>programming</span> <span m=''56530''>language</span> <span m=''56900''>mean.</span>
  </p><p><span m=''58130''>And</span> <span m=''58580''>that''s</span> <span m=''58870''>not</span>
  <span m=''58980''>a</span> <span m=''59030''>mere</span> <span m=''59270''>technical</span>
  <span m=''59760''>point.</span> <span m=''60260''>See,</span> <span m=''60480''>it''s
  not</span> <span m=''60700''>that</span> <span m=''60940''>we</span> <span m=''61070''>had</span>
  <span m=''61430''>this</span> <span m=''61620''>particular</span> <span m=''62130''>substitution</span>
  <span m=''62770''>model</span> <span m=''63090''>and,</span> <span m=''63650''>well,</span>
  <span m=''63890''>it</span> <span m=''63970''>doesn''t</span> <span m=''64250''>quite</span>
  <span m=''64480''>work,</span> <span m=''64680''>so</span> <span m=''64769''>we</span>
  <span m=''64870''>have</span> <span m=''64989''>to</span> <span m=''65110''>do</span>
  <span m=''65200''>something</span> <span m=''65540''>else.</span> <span m=''65870''>It''s</span>
  <span m=''66070''>that</span> <span m=''67500''>nothing</span> <span m=''67750''>like</span>
  <span m=''68250''>the</span> <span m=''68540''>substitution</span> <span m=''69170''>model</span>
  <span m=''69440''>can</span> <span m=''69570''>work.</span> <span m=''70730''>Because</span>
  <span m=''71030''>suddenly,</span> <span m=''72790''>a</span> <span m=''72840''>variable</span>
  <span m=''74130''>is</span> <span m=''74320''>not</span> <span m=''74700''>just</span>
  <span m=''75360''>something</span> <span m=''75780''>that</span> <span m=''75950''>stands</span>
  <span m=''76280''>for</span> <span m=''76430''>a</span> <span m=''76460''>value.</span>
  <span m=''78080''>A</span> <span m=''78200''>variable</span> <span m=''79080''>now</span>
  <span m=''79300''>has</span> <span m=''79550''>to</span> <span m=''79640''>somehow</span>
  <span m=''80540''>specify</span> <span m=''81230''>a</span> <span m=''81300''>place</span>
  <span m=''82390''>that</span> <span m=''82540''>holds</span> <span m=''82810''>a</span>
  <span m=''82870''>value.</span> <span m=''83630''>And</span> <span m=''84190''>the</span>
  <span m=''84330''>value</span> <span m=''84700''>that''s</span> <span m=''84910''>in</span>
  <span m=''84970''>that</span> <span m=''85170''>place</span> <span m=''85440''>can</span>
  <span m=''85600''>change.</span> </p><p><span m=''90280''>Or</span> <span m=''92000''>for</span>
  <span m=''92160''>instance,</span> <span m=''92440''>an</span> <span m=''92520''>expression</span>
  <span m=''93120''>like</span> <span m=''93340''>f of</span> <span m=''93725''>x</span>
  <span m=''97440''>might</span> <span m=''98620''>have</span> <span m=''98770''>a</span>
  <span m=''98800''>side</span> <span m=''99110''>effect</span> <span m=''99410''>in
  it.</span> <span m=''100410''>So</span> <span m=''100570''>if</span> <span m=''100660''>we</span>
  <span m=''100740''>say</span> <span m=''100900''>f of</span> <span m=''101120''>x</span>
  <span m=''101230''>and it</span> <span m=''101610''>has</span> <span m=''101820''>some</span>
  <span m=''101990''>value,</span> <span m=''103200''>and</span> <span m=''103360''>then</span>
  <span m=''103760''>later</span> <span m=''104040''>we</span> <span m=''104160''>say</span>
  <span m=''104370''>f</span> <span m=''104530''>of</span> <span m=''104640''>x</span>
  <span m=''104840''>again,</span> <span m=''107320''>we</span> <span m=''107420''>might</span>
  <span m=''107580''>get</span> <span m=''107660''>a</span> <span m=''107740''>different</span>
  <span m=''108070''>value</span> <span m=''108890''>depending</span> <span m=''109270''>on</span>
  <span m=''109370''>the</span> <span m=''109450''>order.</span> <span m=''109730''>So</span>
  <span m=''109860''>suddenly,</span> <span m=''110420''>we</span> <span m=''110560''>have</span>
  <span m=''110680''>to</span> <span m=''110780''>think</span> <span m=''110960''>not</span>
  <span m=''111140''>only</span> <span m=''111380''>about</span> <span m=''111600''>values</span>
  <span m=''112640''>but</span> <span m=''112780''>about</span> <span m=''113080''>time.</span>
  </p><p><span m=''117970''>And</span> <span m=''118180''>then</span> <span m=''118680''>things</span>
  <span m=''118940''>like</span> <span m=''119410''>pairs</span> <span m=''120680''>are</span>
  <span m=''120840''>no</span> <span m=''121010''>longer</span> <span m=''121330''>just</span>
  <span m=''121540''>their</span> <span m=''121680''>CARs</span> <span m=''122010''>and</span>
  <span m=''122070''>their</span> <span m=''122200''>CDRs.</span> <span m=''122520''>A
  pair</span> <span m=''122840''>now</span> <span m=''123760''>is</span> <span m=''124320''>not</span>
  <span m=''124520''>quite</span> <span m=''124710''>its</span> <span m=''124870''>CAR
  and</span> <span m=''125280''>its CDR.</span> <span m=''125830''>It''s</span> <span
  m=''126030''>rather</span> <span m=''126310''>its</span> <span m=''126450''>identity.</span>
  <span m=''128449''>So</span> <span m=''128639''>a pair</span> <span m=''130979''>has</span>
  <span m=''131190''>identity.</span> <span m=''131650''>It''s</span> <span m=''131800''>an</span>
  <span m=''131890''>object.</span> <span m=''141330''>And</span> <span m=''141980''>two</span>
  <span m=''142230''>pairs</span> <span m=''143870''>that</span> <span m=''144080''>have</span>
  <span m=''144230''>the</span> <span m=''144290''>same</span> <span m=''144550''>CAR</span>
  <span m=''144820''>and</span> <span m=''144870''>CDR</span> <span m=''145800''>might</span>
  <span m=''146070''>be</span> <span m=''146200''>the</span> <span m=''146280''>same</span>
  <span m=''146590''>or</span> <span m=''146680''>different,</span> <span m=''147950''>because</span>
  <span m=''148100''>suddenly</span> <span m=''148360''>we</span> <span m=''148460''>have</span>
  <span m=''148630''>to</span> <span m=''148740''>worry</span> <span m=''149650''>about</span>
  <span m=''149960''>sharing.</span> </p><p><span m=''154960''>So</span> <span m=''155200''>all</span>
  <span m=''155370''>of</span> <span m=''155540''>these</span> <span m=''155760''>things</span>
  <span m=''155990''>enter</span> <span m=''156710''>as</span> <span m=''156870''>soon</span>
  <span m=''158180''>as</span> <span m=''158400''>we</span> <span m=''158520''>introduce</span>
  <span m=''158910''>assignment.</span> <span m=''160480''>See,</span> <span m=''160630''>this</span>
  <span m=''160780''>is</span> <span m=''160880''>a</span> <span m=''160980''>really</span>
  <span m=''161670''>far</span> <span m=''162100''>cry</span> <span m=''162430''>from</span>
  <span m=''162630''>where</span> <span m=''162750''>we</span> <span m=''162870''>started</span>
  <span m=''163210''>with</span> <span m=''163340''>substitution.</span> <span m=''165400''>It''s</span>
  <span m=''165600''>a</span> <span m=''165710''>technically</span> <span m=''166240''>harder</span>
  <span m=''167860''>way</span> <span m=''168090''>of</span> <span m=''168190''>looking</span>
  <span m=''168490''>at</span> <span m=''168590''>things</span> <span m=''168950''>because</span>
  <span m=''170420''>we</span> <span m=''170520''>have</span> <span m=''170640''>to</span>
  <span m=''170750''>think</span> <span m=''171470''>more</span> <span m=''171630''>mechanistically</span>
  <span m=''172410''>about</span> <span m=''172620''>our</span> <span m=''172710''>programming</span>
  <span m=''173190''>language.</span> <span m=''173540''>We</span> <span m=''173620''>can''t</span>
  <span m=''173820''>just</span> <span m=''173990''>think</span> <span m=''174140''>about</span>
  <span m=''174340''>it</span> <span m=''174430''>as</span> <span m=''174520''>mathematics.</span>
  <span m=''175960''>It''s</span> <span m=''177670''>philosophically</span> <span
  m=''178350''>harder,</span> <span m=''179130''>because</span> <span m=''179360''>suddenly</span>
  <span m=''179640''>there are</span> <span m=''179780''>all</span> <span m=''179860''>these</span>
  <span m=''180090''>funny</span> <span m=''180350''>issues</span> <span m=''180710''>about</span>
  <span m=''180950''>what</span> <span m=''181070''>does</span> <span m=''181190''>it</span>
  <span m=''181290''>mean</span> <span m=''181530''>that</span> <span m=''181700''>something</span>
  <span m=''182020''>changes</span> <span m=''182460''>or</span> <span m=''182510''>that</span>
  <span m=''182650''>two</span> <span m=''182820''>things</span> <span m=''183060''>are</span>
  <span m=''183110''>the</span> <span m=''183210''>same.</span> <span m=''184050''>And</span>
  <span m=''184300''>also,</span> <span m=''184560''>it''s</span> <span m=''184700''>programming</span>
  <span m=''186030''>harder,</span> <span m=''186370''>because</span> <span m=''187230''>as</span>
  <span m=''187550''>Gerry</span> <span m=''187910''>showed</span> <span m=''188190''>last</span>
  <span m=''188430''>time,</span> <span m=''188580''>there are</span> <span m=''188710''>all</span>
  <span m=''188820''>these</span> <span m=''189020''>bugs</span> <span m=''189470''>having</span>
  <span m=''189760''>to</span> <span m=''189870''>do</span> <span m=''190070''>with</span>
  <span m=''190760''>bad</span> <span m=''191020''>sequencing</span> <span m=''191670''>and</span>
  <span m=''191800''>aliasing</span> <span m=''192340''>that</span> <span m=''192470''>just</span>
  <span m=''193210''>don''t</span> <span m=''193420''>exist</span> <span m=''194420''>in</span>
  <span m=''194520''>a</span> <span m=''194570''>language</span> <span m=''194900''>where
  we</span> <span m=''195080''>don''t</span> <span m=''195250''>worry</span> <span
  m=''195470''>about</span> <span m=''195690''>objects.</span> </p><p><span m=''198210''>Well,</span>
  <span m=''200010''>how''d</span> <span m=''200220''>we</span> <span m=''200310''>get</span>
  <span m=''200410''>into</span> <span m=''200610''>this</span> <span m=''200810''>mess?</span>
  <span m=''203635''>Remember</span> <span m=''204350''>what</span> <span m=''204490''>we</span>
  <span m=''204610''>did,</span> <span m=''205780''>the</span> <span m=''205960''>reason</span>
  <span m=''206260''>we</span> <span m=''206380''>got</span> <span m=''206550''>into</span>
  <span m=''206760''>this</span> <span m=''206980''>is</span> <span m=''207500''>because</span>
  <span m=''207810''>we</span> <span m=''207890''>were</span> <span m=''208000''>looking</span>
  <span m=''209980''>to</span> <span m=''210200''>build</span> <span m=''210420''>modular</span>
  <span m=''210940''>systems.</span> <span m=''215440''>We</span> <span m=''215750''>wanted</span>
  <span m=''216030''>to</span> <span m=''216790''>build</span> <span m=''217080''>systems</span>
  <span m=''217540''>that</span> <span m=''218280''>fall</span> <span m=''218540''>apart</span>
  <span m=''219450''>into</span> <span m=''219690''>chunks</span> <span m=''220090''>that</span>
  <span m=''220250''>seem</span> <span m=''220480''>natural.</span> <span m=''222760''>So</span>
  <span m=''222970''>for</span> <span m=''223130''>instance,</span> <span m=''224055''>we</span>
  <span m=''224540''>want</span> <span m=''224700''>to</span> <span m=''224770''>take</span>
  <span m=''224950''>a</span> <span m=''225010''>random</span> <span m=''225320''>number</span>
  <span m=''225590''>generator</span> <span m=''226260''>and</span> <span m=''226430''>package</span>
  <span m=''226920''>up</span> <span m=''227060''>the</span> <span m=''227150''>state</span>
  <span m=''227440''>of</span> <span m=''227510''>that</span> <span m=''227680''>random</span>
  <span m=''227970''>number</span> <span m=''228200''>generator</span> <span m=''228660''>inside</span>
  <span m=''229140''>of</span> <span m=''229240''>it</span> <span m=''230280''>so</span>
  <span m=''230430''>that</span> <span m=''230570''>we</span> <span m=''230670''>can</span>
  <span m=''230770''>separate</span> <span m=''231480''>the</span> <span m=''231660''>idea</span>
  <span m=''232280''>of</span> <span m=''232520''>picking</span> <span m=''232840''>random</span>
  <span m=''233170''>numbers</span> <span m=''234650''>from</span> <span m=''234820''>the</span>
  <span m=''234900''>general</span> <span m=''235450''>Monte</span> <span m=''235800''>Carlo</span>
  <span m=''236140''>strategy</span> <span m=''236640''>of</span> <span m=''236700''>estimating</span>
  <span m=''237170''>something</span> <span m=''238680''>and</span> <span m=''238830''>separate</span>
  <span m=''239260''>that</span> <span m=''239520''>from</span> <span m=''239660''>the</span>
  <span m=''239740''>particular</span> <span m=''240770''>way</span> <span m=''241030''>that</span>
  <span m=''241190''>you</span> <span m=''241930''>work</span> <span m=''242120''>with</span>
  <span m=''242250''>random</span> <span m=''242550''>numbers</span> <span m=''242850''>in</span>
  <span m=''242900''>that</span> <span m=''243060''>formula</span> <span m=''244090''>developed</span>
  <span m=''244520''>by</span> <span m=''244650''>Cesaro</span> <span m=''245160''>for</span>
  <span m=''245340''>pi.</span> </p><p><span m=''246980''>And</span> <span m=''247130''>similarly,</span>
  <span m=''249220''>when</span> <span m=''249680''>we</span> <span m=''249870''>go</span>
  <span m=''250020''>off</span> <span m=''250190''>and</span> <span m=''250320''>construct</span>
  <span m=''250750''>some</span> <span m=''250900''>models</span> <span m=''251300''>of</span>
  <span m=''251400''>things,</span> <span m=''253650''>if we</span> <span m=''253780''>go</span>
  <span m=''253890''>off</span> <span m=''254040''>and</span> <span m=''254140''>model</span>
  <span m=''254470''>a</span> <span m=''254520''>system</span> <span m=''254880''>that</span>
  <span m=''255000''>we</span> <span m=''255090''>see</span> <span m=''255280''>in</span>
  <span m=''255360''>the</span> <span m=''255440''>real</span> <span m=''255660''>world,</span>
  <span m=''257269''>we''d</span> <span m=''257430''>like</span> <span m=''257640''>our</span>
  <span m=''257740''>program</span> <span m=''258130''>to</span> <span m=''258240''>break</span>
  <span m=''258490''>into</span> <span m=''258680''>natural</span> <span m=''259050''>pieces,</span>
  <span m=''259430''>pieces</span> <span m=''259779''>that</span> <span m=''260010''>mirror</span>
  <span m=''260920''>the</span> <span m=''261269''>parts</span> <span m=''261579''>of</span>
  <span m=''261640''>the</span> <span m=''261709''>system</span> <span m=''262050''>that</span>
  <span m=''262200''>we</span> <span m=''262310''>see</span> <span m=''262510''>in</span>
  <span m=''262590''>the</span> <span m=''262680''>real</span> <span m=''262870''>world.</span>
  <span m=''264900''>So</span> <span m=''265330''>for</span> <span m=''265490''>example,</span>
  <span m=''266320''>if</span> <span m=''266460''>we</span> <span m=''266550''>look</span>
  <span m=''266640''>at</span> <span m=''266740''>a</span> <span m=''266800''>digital</span>
  <span m=''267110''>circuit,</span> <span m=''268450''>we</span> <span m=''268590''>say,</span>
  <span m=''268780''>gee,</span> <span m=''270260''>there''s</span> <span m=''270800''>a</span>
  <span m=''270840''>circuit</span> <span m=''271740''>and</span> <span m=''272050''>it</span>
  <span m=''272370''>has</span> <span m=''272580''>a</span> <span m=''272630''>piece</span>
  <span m=''273780''>and it</span> <span m=''274040''>has</span> <span m=''274240''>another</span>
  <span m=''274550''>piece.</span> <span m=''280100''>And</span> <span m=''280250''>these</span>
  <span m=''280410''>different</span> <span m=''280720''>pieces</span> <span m=''282540''>sort</span>
  <span m=''282880''>of</span> <span m=''282950''>have</span> <span m=''283090''>identity.</span>
  <span m=''283580''>They</span> <span m=''283800''>have</span> <span m=''284020''>state.</span>
  <span m=''285550''>And</span> <span m=''285640''>the</span> <span m=''285740''>state</span>
  <span m=''286050''>sits</span> <span m=''286240''>on</span> <span m=''286380''>these</span>
  <span m=''286560''>wires.</span> <span m=''288580''>And</span> <span m=''288700''>we</span>
  <span m=''288800''>think</span> <span m=''288980''>of</span> <span m=''289090''>this</span>
  <span m=''289280''>piece</span> <span m=''289510''>as</span> <span m=''289620''>an</span>
  <span m=''289710''>object</span> <span m=''290570''>that''s</span> <span m=''290730''>different</span>
  <span m=''291020''>from</span> <span m=''291150''>that</span> <span m=''291340''>as</span>
  <span m=''291430''>an</span> <span m=''291530''>object.</span> <span m=''292610''>And</span>
  <span m=''292740''>when we</span> <span m=''292860''>watch</span> <span m=''293120''>the</span>
  <span m=''293200''>system</span> <span m=''293550''>change,</span> <span m=''293900''>we</span>
  <span m=''294000''>think</span> <span m=''294170''>about</span> <span m=''294360''>a</span>
  <span m=''294400''>signal</span> <span m=''294720''>coming</span> <span m=''295010''>in</span>
  <span m=''295100''>here</span> <span m=''295680''>and</span> <span m=''295840''>changing</span>
  <span m=''296220''>a</span> <span m=''296260''>state</span> <span m=''297020''>that</span>
  <span m=''297220''>might</span> <span m=''297410''>be</span> <span m=''297500''>here
  and</span> <span m=''297850''>going</span> <span m=''298130''>here</span> <span
  m=''298690''>and</span> <span m=''298840''>interacting</span> <span m=''299290''>with</span>
  <span m=''299390''>a</span> <span m=''299440''>state</span> <span m=''299730''>that</span>
  <span m=''299860''>might</span> <span m=''300050''>be</span> <span m=''300130''>stored</span>
  <span m=''300470''>there,</span> <span m=''301300''>and</span> <span m=''301440''>so</span>
  <span m=''301630''>on</span> <span m=''301760''>and</span> <span m=''301900''>so</span>
  <span m=''302050''>on.</span> </p><p><span m=''306860''>So</span> <span m=''307030''>what</span>
  <span m=''307120''>we''d</span> <span m=''307260''>like</span> <span m=''308310''>is</span>
  <span m=''308480''>we''d</span> <span m=''308630''>like</span> <span m=''308880''>to</span>
  <span m=''309500''>build</span> <span m=''310480''>in</span> <span m=''310620''>the</span>
  <span m=''310700''>computer</span> <span m=''312760''>systems</span> <span m=''313250''>that</span>
  <span m=''313420''>fall</span> <span m=''313790''>into</span> <span m=''313900''>pieces</span>
  <span m=''314610''>that</span> <span m=''315090''>mirror</span> <span m=''316890''>our</span>
  <span m=''317020''>view</span> <span m=''317240''>of</span> <span m=''317340''>reality,</span>
  <span m=''317950''>of</span> <span m=''318120''>the</span> <span m=''318210''>way</span>
  <span m=''318350''>that</span> <span m=''318480''>the</span> <span m=''318600''>actual</span>
  <span m=''318980''>systems</span> <span m=''319350''>we''re</span> <span m=''319460''>modeling</span>
  <span m=''319870''>seem</span> <span m=''320060''>to</span> <span m=''320150''>fall
  into</span> <span m=''320510''>pieces.</span> <span m=''323365''>Well,</span> <span
  m=''325750''>maybe</span> <span m=''326040''>the</span> <span m=''326140''>reason</span>
  <span m=''326500''>that</span> <span m=''327810''>building</span> <span m=''328100''>systems</span>
  <span m=''328530''>like</span> <span m=''328780''>this</span> <span m=''328970''>seems</span>
  <span m=''329210''>to</span> <span m=''329300''>introduce</span> <span m=''329730''>such</span>
  <span m=''330360''>technical</span> <span m=''330780''>complications</span> <span
  m=''331460''>has</span> <span m=''331600''>nothing</span> <span m=''331880''>to</span>
  <span m=''331990''>do</span> <span m=''332140''>with</span> <span m=''332270''>computers.</span>
  </p><p><span m=''333610''>See,</span> <span m=''333820''>maybe</span> <span m=''334190''>the</span>
  <span m=''334730''>real</span> <span m=''335090''>reason</span> <span m=''336760''>that</span>
  <span m=''336890''>we</span> <span m=''337010''>pay</span> <span m=''337180''>such</span>
  <span m=''337420''>a</span> <span m=''337470''>price</span> <span m=''337840''>to</span>
  <span m=''337960''>write</span> <span m=''338190''>programs</span> <span m=''338700''>that</span>
  <span m=''338860''>mirror</span> <span m=''339930''>our</span> <span m=''340080''>view</span>
  <span m=''340290''>of</span> <span m=''340420''>reality</span> <span m=''341540''>is</span>
  <span m=''341710''>that</span> <span m=''341820''>we</span> <span m=''341910''>have</span>
  <span m=''342050''>the</span> <span m=''342150''>wrong</span> <span m=''342380''>view</span>
  <span m=''342560''>of</span> <span m=''342670''>reality.</span> <span m=''344550''>See,</span>
  <span m=''344730''>maybe</span> <span m=''345490''>time</span> <span m=''345830''>is</span>
  <span m=''345980''>just</span> <span m=''346230''>an</span> <span m=''346320''>illusion,</span>
  <span m=''347310''>and</span> <span m=''347460''>nothing</span> <span m=''347790''>ever</span>
  <span m=''347980''>changes.</span> <span m=''350150''>See,</span> <span m=''350320''>for</span>
  <span m=''350420''>example,</span> <span m=''350750''>if</span> <span m=''350830''>I</span>
  <span m=''350890''>take</span> <span m=''351100''>this</span> <span m=''351270''>chalk,</span>
  <span m=''352135''>and</span> <span m=''352480''>we</span> <span m=''352580''>say,</span>
  <span m=''352740''>gee,</span> <span m=''352910''>this</span> <span m=''353060''>is</span>
  <span m=''353160''>an</span> <span m=''353260''>object</span> <span m=''354070''>and
  it</span> <span m=''354240''>has</span> <span m=''354430''>a</span> <span m=''354480''>state.</span>
  <span m=''355820''>At</span> <span m=''356070''>each</span> <span m=''356230''>moment</span>
  <span m=''357010''>it</span> <span m=''357150''>has</span> <span m=''357340''>a</span>
  <span m=''357390''>position</span> <span m=''358510''>and a</span> <span m=''358690''>velocity.</span>
  <span m=''359710''>And if</span> <span m=''359870''>we</span> <span m=''359950''>do</span>
  <span m=''360080''>something,</span> <span m=''360370''>that</span> <span m=''360550''>state</span>
  <span m=''360790''>can</span> <span m=''360960''>change.</span> </p><p><span m=''364340''>But</span>
  <span m=''365380''>if</span> <span m=''365510''>you</span> <span m=''365600''>studied
  any</span> <span m=''366020''>relativity,</span> <span m=''366780''>for</span> <span
  m=''366970''>instance,</span> <span m=''367810''>you</span> <span m=''367900''>know</span>
  <span m=''367970''>that</span> <span m=''368110''>you</span> <span m=''368210''>don''t</span>
  <span m=''368460''>think</span> <span m=''368640''>of</span> <span m=''368740''>the</span>
  <span m=''368830''>path</span> <span m=''369160''>of</span> <span m=''369230''>that</span>
  <span m=''369410''>chalk</span> <span m=''369670''>as</span> <span m=''369760''>something</span>
  <span m=''370030''>that</span> <span m=''370160''>goes</span> <span m=''370340''>on</span>
  <span m=''370480''>instant</span> <span m=''370750''>by</span> <span m=''370900''>instant.</span>
  <span m=''371340''>It''s more</span> <span m=''371720''>insightful</span> <span
  m=''372650''>to</span> <span m=''372890''>think</span> <span m=''373090''>of</span>
  <span m=''373170''>that</span> <span m=''373320''>whole</span> <span m=''373520''>chalk''s</span>
  <span m=''373870''>existence</span> <span m=''374390''>as</span> <span m=''374510''>a</span>
  <span m=''374580''>path</span> <span m=''374920''>in</span> <span m=''375000''>space-time.</span>
  <span m=''376020''>that''s</span> <span m=''376460''>all</span> <span m=''376620''>splayed</span>
  <span m=''377100''>out.</span> <span m=''378040''>There</span> <span m=''378150''>aren''t</span>
  <span m=''378270''>individual</span> <span m=''378820''>positions and</span> <span
  m=''379260''>velocities.</span> <span m=''379840''>There''s</span> <span m=''380000''>just</span>
  <span m=''380190''>its</span> <span m=''381120''>unchanging</span> <span m=''382350''>existence</span>
  <span m=''382950''>in</span> <span m=''383030''>space-time.</span> </p><p><span
  m=''384640''>Similarly,</span> <span m=''385130''>if</span> <span m=''385200''>we</span>
  <span m=''385280''>look</span> <span m=''385370''>at</span> <span m=''385470''>this</span>
  <span m=''385600''>electrical</span> <span m=''386060''>system,</span> <span m=''387780''>if</span>
  <span m=''387950''>we</span> <span m=''388080''>imagine</span> <span m=''388700''>this</span>
  <span m=''388900''>electrical</span> <span m=''389370''>system</span> <span m=''389720''>is</span>
  <span m=''389820''>implementing</span> <span m=''390710''>some</span> <span m=''390910''>sort</span>
  <span m=''391100''>of</span> <span m=''392450''>signal</span> <span m=''392800''>processing</span>
  <span m=''393320''>system,</span> <span m=''394360''>the</span> <span m=''394490''>signal</span>
  <span m=''394810''>processing</span> <span m=''395320''>engineer</span> <span m=''395620''>who</span>
  <span m=''395730''>put</span> <span m=''395890''>that</span> <span m=''396080''>thing</span>
  <span m=''396220''>together</span> <span m=''396860''>doesn''t</span> <span m=''397270''>think</span>
  <span m=''397470''>of</span> <span m=''397580''>it</span> <span m=''397940''>as,</span>
  <span m=''398250''>well,</span> <span m=''399010''>at</span> <span m=''399210''>each</span>
  <span m=''399500''>instance</span> <span m=''400020''>there''s</span> <span m=''400290''>a</span>
  <span m=''400350''>voltage</span> <span m=''400810''>coming</span> <span m=''401130''>in.</span>
  <span m=''401490''>And</span> <span m=''401740''>that</span> <span m=''401880''>translates</span>
  <span m=''402390''>into</span> <span m=''402550''>something.</span> <span m=''403340''>And</span>
  <span m=''403640''>that</span> <span m=''404320''>affects</span> <span m=''404720''>the</span>
  <span m=''404790''>state</span> <span m=''405170''>over</span> <span m=''405380''>here,</span>
  <span m=''405680''>which</span> <span m=''405850''>changes</span> <span m=''406320''>the</span>
  <span m=''406400''>state</span> <span m=''406590''>over</span> <span m=''406690''>here.</span>
  <span m=''406810''>Nobody</span> <span m=''407180''>putting</span> <span m=''407610''>together
  a</span> <span m=''408040''>signal</span> <span m=''408320''>processing</span> <span
  m=''408770''>system</span> <span m=''409060''>thinks</span> <span m=''409320''>about</span>
  <span m=''409480''>it</span> <span m=''409650''>like</span> <span m=''409870''>that.</span>
  </p><p><span m=''410420''>Instead,</span> <span m=''410790''>you</span> <span m=''410890''>say</span>
  <span m=''411070''>there''s</span> <span m=''411290''>this</span> <span m=''411380''>signal</span>
  <span m=''413840''>that''s</span> <span m=''416830''>splayed</span> <span m=''417110''>out</span>
  <span m=''417270''>over</span> <span m=''417470''>time.</span> <span m=''418060''>And</span>
  <span m=''418210''>if</span> <span m=''418300''>this</span> <span m=''418460''>is</span>
  <span m=''418560''>acting</span> <span m=''418870''>as</span> <span m=''418940''>a</span>
  <span m=''419020''>filter,</span> <span m=''420020''>this</span> <span m=''420520''>whole</span>
  <span m=''420830''>thing</span> <span m=''421100''>transforms</span> <span m=''422880''>this</span>
  <span m=''423170''>whole</span> <span m=''423490''>thing</span> <span m=''424190''>for</span>
  <span m=''424470''>some</span> <span m=''424650''>sort</span> <span m=''424870''>of</span>
  <span m=''426500''>other</span> <span m=''426690''>output.</span> <span m=''429570''>You</span>
  <span m=''429680''>don''t</span> <span m=''429990''>think</span> <span m=''430170''>of</span>
  <span m=''430280''>it</span> <span m=''430380''>as</span> <span m=''430610''>what''s</span>
  <span m=''430910''>happening</span> <span m=''431270''>instant</span> <span m=''431630''>by</span>
  <span m=''431790''>instant</span> <span m=''432130''>as</span> <span m=''432250''>the</span>
  <span m=''432320''>state</span> <span m=''432630''>of</span> <span m=''432740''>these</span>
  <span m=''432950''>things.</span> <span m=''434160''>And</span> <span m=''434320''>somehow</span>
  <span m=''434580''>you</span> <span m=''434740''>think</span> <span m=''434960''>of</span>
  <span m=''435310''>this</span> <span m=''435640''>box</span> <span m=''435970''>as</span>
  <span m=''436640''>a</span> <span m=''436690''>whole</span> <span m=''437020''>thing,</span>
  <span m=''437320''>not</span> <span m=''437540''>as</span> <span m=''437990''>little</span>
  <span m=''438240''>pieces</span> <span m=''438630''>sending</span> <span m=''439240''>messages</span>
  <span m=''439730''>of</span> <span m=''439820''>state</span> <span m=''440290''>to</span>
  <span m=''440530''>each</span> <span m=''440740''>other</span> <span m=''440940''>at</span>
  <span m=''440980''>particular</span> <span m=''441510''>instants.</span> </p><p><span
  m=''448250''>Well,</span> <span m=''448370''>today</span> <span m=''448620''>we''re</span>
  <span m=''448740''>going</span> <span m=''448820''>to</span> <span m=''448900''>look</span>
  <span m=''449180''>at</span> <span m=''449370''>another</span> <span m=''449720''>way</span>
  <span m=''450000''>to</span> <span m=''450130''>decompose</span> <span m=''450670''>systems</span>
  <span m=''451200''>that''s</span> <span m=''451950''>more</span> <span m=''452320''>like</span>
  <span m=''452860''>the</span> <span m=''453160''>signal</span> <span m=''453530''>processing</span>
  <span m=''454260''>engineer''s</span> <span m=''454750''>view</span> <span m=''454960''>of</span>
  <span m=''455030''>the</span> <span m=''455260''>world</span> <span m=''455610''>than</span>
  <span m=''455840''>it</span> <span m=''455940''>is</span> <span m=''456110''>like</span>
  <span m=''456480''>thinking</span> <span m=''456810''>about</span> <span m=''457050''>objects</span>
  <span m=''457510''>that</span> <span m=''457620''>communicate</span> <span m=''458170''>sending</span>
  <span m=''458430''>messages.</span> <span m=''461130''>That''s</span> <span m=''461460''>called</span>
  <span m=''462430''>stream</span> <span m=''462820''>processing.</span> <span m=''474570''>And</span>
  <span m=''474920''>we''re</span> <span m=''475030''>going</span> <span m=''475110''>to</span>
  <span m=''475200''>start</span> <span m=''478130''>by</span> <span m=''478480''>showing</span>
  <span m=''481070''>how</span> <span m=''481200''>we</span> <span m=''481310''>can</span>
  <span m=''481460''>make</span> <span m=''481660''>our</span> <span m=''481790''>programs</span>
  <span m=''483180''>more</span> <span m=''483420''>uniform</span> <span m=''485150''>and</span>
  <span m=''485320''>see</span> <span m=''485510''>a</span> <span m=''485560''>lot</span>
  <span m=''485740''>more</span> <span m=''485870''>commonality</span> <span m=''486860''>if</span>
  <span m=''487030''>we</span> <span m=''488550''>throw</span> <span m=''488830''>out</span>
  <span m=''489040''>of</span> <span m=''489180''>these</span> <span m=''489320''>programs</span>
  <span m=''490900''>what</span> <span m=''491150''>you</span> <span m=''491220''>might</span>
  <span m=''491430''>say</span> <span m=''491650''>is</span> <span m=''492360''>an</span>
  <span m=''492490''>inordinate</span> <span m=''493050''>concern</span> <span m=''493820''>with</span>
  <span m=''494020''>worrying</span> <span m=''494410''>about</span> <span m=''494700''>time.</span>
  </p><p><span m=''497210''>Let</span> <span m=''497290''>me</span> <span m=''497380''>start</span>
  <span m=''497640''>by</span> <span m=''498170''>comparing</span> <span m=''499360''>two</span>
  <span m=''499550''>procedures.</span> <span m=''503260''>The</span> <span m=''503670''>first</span>
  <span m=''504090''>one</span> <span m=''505220''>does</span> <span m=''505480''>this.</span>
  <span m=''505690''>We</span> <span m=''505810''>imagine</span> <span m=''506540''>that</span>
  <span m=''507020''>there''s</span> <span m=''507240''>a</span> <span m=''507300''>tree.</span>
  <span m=''510400''>Say</span> <span m=''510680''>there''s</span> <span m=''510870''>a</span>
  <span m=''510930''>tree</span> <span m=''511270''>of</span> <span m=''511430''>integers.</span>
  <span m=''513179''>It''s a</span> <span m=''513490''>binary</span> <span m=''513960''>tree.</span>
  <span m=''519100''>So</span> <span m=''519440''>it</span> <span m=''519539''>looks</span>
  <span m=''519750''>like</span> <span m=''519980''>this.</span> <span m=''520230''>And</span>
  <span m=''520299''>there''s</span> <span m=''521450''>integers</span> <span m=''521919''>in</span>
  <span m=''522010''>each</span> <span m=''522179''>of</span> <span m=''522270''>the</span>
  <span m=''522350''>nodes.</span> <span m=''524990''>And</span> <span m=''525400''>what</span>
  <span m=''525520''>we</span> <span m=''525620''>would</span> <span m=''525750''>like</span>
  <span m=''526350''>to</span> <span m=''526500''>compute</span> <span m=''527430''>is</span>
  <span m=''527880''>for</span> <span m=''528320''>each</span> <span m=''530340''>odd</span>
  <span m=''530690''>number</span> <span m=''531000''>sitting</span> <span m=''531260''>here,</span>
  <span m=''532400''>we''d</span> <span m=''532510''>like</span> <span m=''532670''>to</span>
  <span m=''532760''>find</span> <span m=''533020''>the</span> <span m=''533050''>square</span>
  <span m=''533730''>and</span> <span m=''533840''>then</span> <span m=''533960''>sum</span>
  <span m=''534210''>up</span> <span m=''534360''>all</span> <span m=''534490''>those</span>
  <span m=''534670''>squares.</span> </p><p><span m=''537210''>Well,</span> <span
  m=''537370''>that</span> <span m=''538050''>should</span> <span m=''538250''>be</span>
  <span m=''538340''>a</span> <span m=''538390''>familiar</span> <span m=''538820''>kind</span>
  <span m=''539050''>of</span> <span m=''539130''>thing.</span> <span m=''539480''>There''s</span>
  <span m=''539640''>a</span> <span m=''539700''>recursive</span> <span m=''540690''>strategy</span>
  <span m=''541200''>for</span> <span m=''541340''>doing</span> <span m=''541650''>it.</span>
  <span m=''542930''>We</span> <span m=''543170''>look</span> <span m=''543270''>at</span>
  <span m=''543380''>each</span> <span m=''543590''>leaf,</span> <span m=''543890''>and</span>
  <span m=''543990''>either</span> <span m=''544550''>it''s</span> <span m=''544730''>going</span>
  <span m=''544800''>to</span> <span m=''544880''>contribute</span> <span m=''545320''>the</span>
  <span m=''545380''>square</span> <span m=''545750''>of</span> <span m=''545820''>the</span>
  <span m=''545890''>number</span> <span m=''546200''>if</span> <span m=''546270''>it''s</span>
  <span m=''546430''>odd</span> <span m=''546690''>or</span> <span m=''546770''>0</span>
  <span m=''547170''>if</span> <span m=''547280''>it''s</span> <span m=''547410''>even.</span>
  <span m=''548680''>And</span> <span m=''548810''>then</span> <span m=''548940''>recursively,</span>
  <span m=''549590''>we</span> <span m=''549730''>can</span> <span m=''549840''>say</span>
  <span m=''551280''>at</span> <span m=''551440''>each</span> <span m=''551640''>tree,</span>
  <span m=''552740''>the</span> <span m=''552900''>sum</span> <span m=''553170''>of</span>
  <span m=''553280''>all</span> <span m=''553460''>of</span> <span m=''553550''>them</span>
  <span m=''553700''>is</span> <span m=''553810''>the</span> <span m=''553880''>sum</span>
  <span m=''554160''>coming</span> <span m=''554430''>from</span> <span m=''554530''>the</span>
  <span m=''554630''>right</span> <span m=''554880''>branch</span> <span m=''555170''>and</span>
  <span m=''555250''>the</span> <span m=''555330''>left</span> <span m=''555570''>branch,</span>
  <span m=''556310''>and</span> <span m=''556450''>recursively</span> <span m=''556740''>down</span>
  <span m=''557160''>through</span> <span m=''557300''>the</span> <span m=''557400''>nodes.</span>
  <span m=''557640''>And that''s</span> <span m=''557860''>a</span> <span m=''557920''>familiar</span>
  <span m=''558370''>way</span> <span m=''559280''>of</span> <span m=''559420''>thinking</span>
  <span m=''559710''>about</span> <span m=''559920''>programming.</span> </p><p><span
  m=''560360''>Let''s</span> <span m=''560880''>actually</span> <span m=''561350''>look</span>
  <span m=''561480''>at</span> <span m=''561620''>that</span> <span m=''561770''>on
  the</span> <span m=''562075''>slide.</span> <span m=''563960''>We</span> <span m=''564090''>say</span>
  <span m=''564410''>to</span> <span m=''564720''>sum</span> <span m=''565380''>the</span>
  <span m=''565630''>odd</span> <span m=''565820''>squares</span> <span m=''566180''>in</span>
  <span m=''566250''>a</span> <span m=''566310''>tree,</span> <span m=''567520''>well,</span>
  <span m=''567710''>there''s</span> <span m=''567900''>a</span> <span m=''567960''>test.</span>
  <span m=''568330''>Either</span> <span m=''568520''>it''s</span> <span m=''568640''>a</span>
  <span m=''568690''>leaf</span> <span m=''569020''>node,</span> <span m=''569485''>and</span>
  <span m=''569950''>we''re</span> <span m=''570020''>going</span> <span m=''570110''>to</span>
  <span m=''570200''>check</span> <span m=''570430''>to</span> <span m=''570520''>see</span>
  <span m=''570680''>if</span> <span m=''570760''>it''s</span> <span m=''571310''>an</span>
  <span m=''571490''>integer,</span> <span m=''572570''>and</span> <span m=''573060''>then</span>
  <span m=''573200''>either</span> <span m=''573970''>it''s</span> <span m=''574200''>odd,</span>
  <span m=''574490''>in</span> <span m=''574560''>which</span> <span m=''574710''>we</span>
  <span m=''574810''>take</span> <span m=''575010''>the</span> <span m=''575080''>square,</span>
  <span m=''575340''>or</span> <span m=''575600''>else</span> <span m=''575710''>it''s</span>
  <span m=''575910''>0.</span> <span m=''577160''>And</span> <span m=''577360''>then</span>
  <span m=''577690''>the</span> <span m=''577940''>sum</span> <span m=''578210''>of</span>
  <span m=''578270''>the</span> <span m=''578340''>whole</span> <span m=''578570''>thing</span>
  <span m=''579280''>is</span> <span m=''579450''>the</span> <span m=''579540''>sum</span>
  <span m=''579850''>coming</span> <span m=''580120''>from</span> <span m=''580260''>the</span>
  <span m=''580330''>left</span> <span m=''580560''>branch</span> <span m=''581270''>and</span>
  <span m=''581450''>the right</span> <span m=''581720''>branch.</span> </p><p><span
  m=''586340''>OK,</span> <span m=''586520''>well,</span> <span m=''586620''>let</span>
  <span m=''586780''>me</span> <span m=''587480''>contrast</span> <span m=''587950''>that</span>
  <span m=''588130''>with</span> <span m=''588280''>a</span> <span m=''589600''>second</span>
  <span m=''589960''>problem.</span> <span m=''591560''>Suppose</span> <span m=''592450''>I</span>
  <span m=''592550''>give</span> <span m=''592710''>you</span> <span m=''592800''>an</span>
  <span m=''592870''>integer</span> <span m=''593250''>n,</span> <span m=''594770''>and</span>
  <span m=''594930''>then</span> <span m=''595050''>some</span> <span m=''595260''>function</span>
  <span m=''595700''>to</span> <span m=''595810''>compute</span> <span m=''596260''>of
  the</span> <span m=''596530''>first</span> <span m=''597090''>of</span> <span m=''597230''>each</span>
  <span m=''597450''>integer</span> <span m=''597950''>in</span> <span m=''598120''>1</span>
  <span m=''598350''>through</span> <span m=''598600''>n.</span> <span m=''599270''>And</span>
  <span m=''599440''>then</span> <span m=''599630''>I</span> <span m=''599710''>want</span>
  <span m=''599820''>to</span> <span m=''599930''>collect</span> <span m=''600250''>together</span>
  <span m=''600650''>in</span> <span m=''600710''>a</span> <span m=''600770''>list</span>
  <span m=''601290''>all</span> <span m=''601590''>those</span> <span m=''601810''>function</span>
  <span m=''602180''>values</span> <span m=''603000''>that</span> <span m=''603450''>satisfy</span>
  <span m=''603900''>some</span> <span m=''604080''>property.</span> <span m=''605600''>That''s</span>
  <span m=''605830''>a</span> <span m=''605870''>general</span> <span m=''606220''>kind</span>
  <span m=''606370''>of</span> <span m=''606520''>thing.</span> <span m=''606880''>Let''s</span>
  <span m=''607020''>say</span> <span m=''607140''>to</span> <span m=''607200''>be</span>
  <span m=''607330''>specific,</span> <span m=''608710''>let''s</span> <span m=''608930''>imagine</span>
  <span m=''609270''>that</span> <span m=''609410''>for</span> <span m=''609510''>each</span>
  <span m=''609750''>integer,</span> <span m=''610140''>k,</span> <span m=''610720''>we''re</span>
  <span m=''610840''>going</span> <span m=''610910''>to</span> <span m=''610980''>compute</span>
  <span m=''611270''>the</span> <span m=''611360''>k</span> <span m=''611700''>Fibonacci</span>
  <span m=''612160''>number.</span> <span m=''614210''>And</span> <span m=''614420''>then</span>
  <span m=''614870''>we''ll</span> <span m=''614970''>see</span> <span m=''615150''>which</span>
  <span m=''615370''>of</span> <span m=''615470''>those</span> <span m=''615690''>are</span>
  <span m=''615790''>odd</span> <span m=''617020''>and</span> <span m=''617180''>assemble</span>
  <span m=''617550''>those</span> <span m=''617770''>into</span> <span m=''618010''>a</span>
  <span m=''618070''>list.</span> </p><p><span m=''619050''>So</span> <span m=''619220''>here''s</span>
  <span m=''619420''>a</span> <span m=''619480''>procedure</span> <span m=''619900''>that</span>
  <span m=''620070''>does</span> <span m=''620290''>that.</span> <span m=''623730''>Find</span>
  <span m=''624040''>the odd</span> <span m=''624300''>Fibonacci</span> <span m=''624910''>numbers</span>
  <span m=''625210''>among</span> <span m=''625430''>the</span> <span m=''625500''>first</span>
  <span m=''625820''>n.</span> <span m=''626240''>And</span> <span m=''626390''>here</span>
  <span m=''626610''>is</span> <span m=''627190''>a</span> <span m=''627300''>standard</span>
  <span m=''627800''>loop</span> <span m=''628040''>the</span> <span m=''628130''>way
  we''ve</span> <span m=''628320''>been</span> <span m=''628480''>writing</span> <span
  m=''628820''>it.</span> <span m=''628910''>This</span> <span m=''629050''>is</span>
  <span m=''629150''>a</span> <span m=''629210''>recursion.</span> <span m=''630800''>It''s</span>
  <span m=''630940''>a</span> <span m=''630990''>loop</span> <span m=''631240''>on</span>
  <span m=''631430''>k,</span> <span m=''632060''>and</span> <span m=''632300''>says</span>
  <span m=''632620''>if</span> <span m=''632730''>k</span> <span m=''632900''>is</span>
  <span m=''633020''>bigger</span> <span m=''633200''>than</span> <span m=''633380''>n,</span>
  <span m=''633510''>it''s</span> <span m=''633640''>the</span> <span m=''633740''>empty</span>
  <span m=''634010''>list.</span> <span m=''635190''>Otherwise</span> <span m=''635590''>we</span>
  <span m=''635690''>compute</span> <span m=''636060''>the</span> <span m=''636160''>k-th</span>
  <span m=''636620''>Fibonacci</span> <span m=''636990''>number,</span> <span m=''637440''>call</span>
  <span m=''637660''>that</span> <span m=''637860''>f.</span> <span m=''640370''>If</span>
  <span m=''640510''>it''s</span> <span m=''640690''>odd,</span> <span m=''641910''>we</span>
  <span m=''642060''>CONS</span> <span m=''642390''>it</span> <span m=''642520''>on</span>
  <span m=''643810''>to</span> <span m=''643960''>the</span> <span m=''644060''>list</span>
  <span m=''644820''>starting</span> <span m=''645180''>with</span> <span m=''645310''>the</span>
  <span m=''645480''>next</span> <span m=''645660''>one.</span> <span m=''647690''>And</span>
  <span m=''647840''>otherwise,</span> <span m=''648890''>we</span> <span m=''648990''>just</span>
  <span m=''649220''>take</span> <span m=''649420''>the</span> <span m=''649500''>next</span>
  <span m=''649780''>one.</span> <span m=''650390''>And</span> <span m=''650780''>this</span>
  <span m=''651010''>is</span> <span m=''651120''>the</span> <span m=''651160''>standard</span>
  <span m=''651590''>way</span> <span m=''651760''>we''ve</span> <span m=''651910''>been</span>
  <span m=''652000''>writing</span> <span m=''652310''>iterative</span> <span m=''652700''>loops.</span>
  <span m=''653000''>And we</span> <span m=''653090''>start</span> <span m=''653480''>off</span>
  <span m=''654450''>calling</span> <span m=''654740''>that</span> <span m=''654910''>loop</span>
  <span m=''655120''>with</span> <span m=''655250''>1.</span> </p><p><span m=''657600''>OK,</span>
  <span m=''658710''>so</span> <span m=''658900''>there</span> <span m=''659080''>are</span>
  <span m=''659140''>two</span> <span m=''659320''>procedures.</span> <span m=''661600''>Those</span>
  <span m=''661720''>procedures</span> <span m=''662140''>look</span> <span m=''662300''>very</span>
  <span m=''662530''>different.</span> <span m=''662900''>They</span> <span m=''663010''>have</span>
  <span m=''663120''>very</span> <span m=''663350''>different</span> <span m=''663640''>structures.</span>
  <span m=''664390''>Yet</span> <span m=''665700''>from</span> <span m=''665910''>a</span>
  <span m=''665950''>certain</span> <span m=''666270''>point</span> <span m=''666540''>of</span>
  <span m=''666600''>view,</span> <span m=''666960''>those</span> <span m=''667180''>procedures</span>
  <span m=''667630''>are</span> <span m=''667740''>really</span> <span m=''668060''>doing</span>
  <span m=''668370''>very</span> <span m=''668660''>much</span> <span m=''668920''>the</span>
  <span m=''669000''>same</span> <span m=''669320''>thing.</span> <span m=''671330''>So</span>
  <span m=''671610''>if</span> <span m=''671710''>I</span> <span m=''672360''>was</span>
  <span m=''672600''>talking</span> <span m=''673010''>like</span> <span m=''673220''>a</span>
  <span m=''673500''>signal</span> <span m=''673820''>processing</span> <span m=''674310''>engineer,</span>
  <span m=''674930''>what</span> <span m=''675040''>I</span> <span m=''675160''>might</span>
  <span m=''675450''>say</span> <span m=''676300''>is</span> <span m=''676510''>that</span>
  <span m=''678240''>the</span> <span m=''678480''>first</span> <span m=''678720''>procedure</span>
  <span m=''682050''>enumerates</span> <span m=''685600''>the</span> <span m=''685730''>leaves</span>
  <span m=''686070''>of</span> <span m=''686170''>a</span> <span m=''686230''>tree.</span>
  <span m=''691160''>And</span> <span m=''691280''>then</span> <span m=''691380''>we</span>
  <span m=''691490''>can</span> <span m=''691630''>think</span> <span m=''691800''>of</span>
  <span m=''692380''>a</span> <span m=''692430''>signal</span> <span m=''692840''>coming</span>
  <span m=''693160''>out</span> <span m=''693250''>of</span> <span m=''693340''>that,</span>
  <span m=''693510''>which</span> <span m=''693670''>is</span> <span m=''693770''>all</span>
  <span m=''693920''>the</span> <span m=''693990''>leaves.</span> </p><p><span m=''695330''>We''ll</span>
  <span m=''695560''>filter</span> <span m=''695990''>them</span> <span m=''702220''>to</span>
  <span m=''702340''>see</span> <span m=''702500''>which</span> <span m=''702670''>ones</span>
  <span m=''702880''>are</span> <span m=''702980''>odd,</span> <span m=''703550''>put</span>
  <span m=''703740''>them</span> <span m=''703840''>through</span> <span m=''703970''>some</span>
  <span m=''704130''>kind</span> <span m=''704250''>of</span> <span m=''704370''>filter.</span>
  <span m=''705190''>We''ll</span> <span m=''705460''>then</span> <span m=''705620''>put</span>
  <span m=''705810''>them</span> <span m=''705950''>through</span> <span m=''706110''>a</span>
  <span m=''706180''>kind</span> <span m=''706350''>of</span> <span m=''706940''>transducer.</span>
  <span m=''709000''>And for</span> <span m=''709445''>each</span> <span m=''709890''>one</span>
  <span m=''710050''>of</span> <span m=''710110''>those</span> <span m=''710350''>things,</span>
  <span m=''710720''>we''ll</span> <span m=''710850''>take</span> <span m=''711080''>the</span>
  <span m=''711160''>square.</span> <span m=''714200''>And</span> <span m=''714730''>then</span>
  <span m=''716120''>we''ll</span> <span m=''716280''>accumulate</span> <span m=''716820''>all</span>
  <span m=''716980''>of</span> <span m=''717080''>those.</span> <span m=''718290''>We''ll</span>
  <span m=''718400''>accumulate</span> <span m=''718930''>them</span> <span m=''719070''>by</span>
  <span m=''719160''>sticking</span> <span m=''719490''>them</span> <span m=''719600''>together</span>
  <span m=''720350''>with</span> <span m=''720570''>addition</span> <span m=''721830''>starting</span>
  <span m=''722600''>from</span> <span m=''722870''>0.</span> <span m=''727140''>That''s</span>
  <span m=''727420''>the</span> <span m=''727490''>first</span> <span m=''727780''>program.</span>
  </p><p><span m=''728210''>The</span> <span m=''728470''>second</span> <span m=''728740''>program,</span>
  <span m=''729430''>I</span> <span m=''729550''>can</span> <span m=''729670''>describe</span>
  <span m=''730000''>in</span> <span m=''730080''>a</span> <span m=''730130''>very,</span>
  <span m=''730430''>very</span> <span m=''730620''>similar</span> <span m=''730970''>way.</span>
  <span m=''731780''>I''ll</span> <span m=''731900''>say,</span> <span m=''732260''>we''ll</span>
  <span m=''732630''>enumerate</span> <span m=''735940''>the</span> <span m=''736050''>numbers</span>
  <span m=''736420''>on</span> <span m=''736560''>this</span> <span m=''736700''>interval,</span>
  <span m=''737250''>for</span> <span m=''737450''>the</span> <span m=''737940''>interval</span>
  <span m=''738280''>1</span> <span m=''738460''>through</span> <span m=''738640''>n.</span>
  <span m=''742500''>We''ll,</span> <span m=''743420''>for</span> <span m=''743760''>each</span>
  <span m=''743980''>one,</span> <span m=''745380''>compute</span> <span m=''745920''>the</span>
  <span m=''746070''>Fibonacci</span> <span m=''746560''>number,</span> <span m=''747700''>put</span>
  <span m=''747950''>them</span> <span m=''748080''>through</span> <span m=''748220''>a</span>
  <span m=''748280''>transducer.</span> <span m=''749270''>We''ll</span> <span m=''749430''>then</span>
  <span m=''749620''>take</span> <span m=''749860''>the</span> <span m=''749950''>result</span>
  <span m=''750290''>of</span> <span m=''750390''>that,</span> <span m=''751310''>and
  we''ll</span> <span m=''751780''>filter</span> <span m=''752200''>it</span> <span
  m=''753550''>for</span> <span m=''753720''>oddness.</span> <span m=''755976''>And</span>
  <span m=''756390''>then</span> <span m=''756650''>we''ll</span> <span m=''756750''>take</span>
  <span m=''757000''>those</span> <span m=''757520''>and</span> <span m=''757680''>put</span>
  <span m=''757850''>them</span> <span m=''758050''>into</span> <span m=''758320''>an</span>
  <span m=''758600''>accumulator.</span> <span m=''759350''>This</span> <span m=''759540''>time</span>
  <span m=''759710''>we''ll</span> <span m=''759820''>build</span> <span m=''760050''>up</span>
  <span m=''760160''>a</span> <span m=''760220''>list,</span> <span m=''760770''>so</span>
  <span m=''760980''>we''ll</span> <span m=''761130''>accumulate</span> <span m=''761590''>with</span>
  <span m=''761730''>CONS</span> <span m=''762620''>starting</span> <span m=''762990''>from</span>
  <span m=''763120''>the</span> <span m=''763220''>empty</span> <span m=''763480''>list.</span>
  </p><p><span m=''767110''>So</span> <span m=''767740''>this</span> <span m=''768640''>way</span>
  <span m=''768810''>of</span> <span m=''768910''>looking</span> <span m=''769180''>at</span>
  <span m=''769260''>the</span> <span m=''769330''>program</span> <span m=''769930''>makes</span>
  <span m=''770200''>the</span> <span m=''770300''>two</span> <span m=''770660''>seem</span>
  <span m=''770940''>very,</span> <span m=''771190''>very</span> <span m=''771400''>similar.</span>
  <span m=''771900''>The</span> <span m=''772060''>problem</span> <span m=''772530''>is</span>
  <span m=''773220''>that</span> <span m=''773460''>that</span> <span m=''773650''>commonality</span>
  <span m=''775150''>is</span> <span m=''775330''>completely</span> <span m=''775880''>obscured</span>
  <span m=''776640''>when</span> <span m=''776750''>we</span> <span m=''776840''>look</span>
  <span m=''776940''>at</span> <span m=''777050''>the</span> <span m=''777130''>procedures</span>
  <span m=''777620''>we</span> <span m=''777730''>wrote.</span> <span m=''778050''>Let''s</span>
  <span m=''778260''>go</span> <span m=''778330''>back</span> <span m=''779870''>and</span>
  <span m=''780270''>look</span> <span m=''780410''>at</span> <span m=''780500''>some</span>
  <span m=''780700''>odd</span> <span m=''780850''>squares</span> <span m=''781190''>again,</span>
  <span m=''782180''>and</span> <span m=''782470''>say</span> <span m=''782670''>things</span>
  <span m=''782910''>like,</span> <span m=''783410''>where''s</span> <span m=''783800''>the</span>
  <span m=''783970''>enumerator?</span> <span m=''786300''>Where''s</span> <span m=''786610''>the</span>
  <span m=''786790''>enumerator</span> <span m=''787285''>in</span> <span m=''787550''>this</span>
  <span m=''787710''>program?</span> <span m=''788140''>Well,</span> <span m=''789400''>it''s</span>
  <span m=''789580''>not in</span> <span m=''789790''>one</span> <span m=''789990''>place.</span>
  <span m=''791230''>It''s</span> <span m=''791390''>a</span> <span m=''791450''>little</span>
  <span m=''791750''>bit</span> <span m=''792540''>in</span> <span m=''794160''>this</span>
  <span m=''794510''>leaf-node</span> <span m=''794940''>test,</span> <span m=''795990''>which</span>
  <span m=''796490''>is</span> <span m=''796670''>going</span> <span m=''796740''>to</span>
  <span m=''796810''>stop.</span> <span m=''797160''>It''s</span> <span m=''797290''>a</span>
  <span m=''797340''>little</span> <span m=''797600''>bit</span> <span m=''798120''>in</span>
  <span m=''798260''>the</span> <span m=''798320''>recursive</span> <span m=''798780''>structure</span>
  <span m=''799220''>of</span> <span m=''799290''>the</span> <span m=''799380''>thing</span>
  <span m=''799570''>itself.</span> </p><p><span m=''803150''>Where''s</span> <span
  m=''803390''>the</span> <span m=''803510''>accumulator?</span> <span m=''804120''>The</span>
  <span m=''804280''>accumulator</span> <span m=''804730''>isn''t</span> <span m=''804820''>in
  one</span> <span m=''805110''>place</span> <span m=''805410''>either.</span> <span
  m=''805680''>It''s</span> <span m=''807230''>partly</span> <span m=''807650''>in</span>
  <span m=''807840''>this 0</span> <span m=''809420''>and</span> <span m=''809690''>partly</span>
  <span m=''810070''>in</span> <span m=''810190''>this</span> <span m=''810320''>plus.</span>
  <span m=''812180''>It''s</span> <span m=''812310''>not</span> <span m=''812490''>there</span>
  <span m=''812740''>as</span> <span m=''813420''>a</span> <span m=''813480''>thing</span>
  <span m=''813660''>that</span> <span m=''813760''>we</span> <span m=''813880''>can</span>
  <span m=''814060''>look</span> <span m=''814240''>at.</span> <span m=''814510''>Similarly,</span>
  <span m=''816520''>if</span> <span m=''816950''>we</span> <span m=''817060''>look</span>
  <span m=''817350''>at</span> <span m=''818580''>odd</span> <span m=''818810''>Fibs,</span>
  <span m=''819120''>that''s</span> <span m=''819300''>also,</span> <span m=''820230''>in</span>
  <span m=''820360''>some</span> <span m=''820550''>sense,</span> <span m=''820810''>an</span>
  <span m=''820910''>enumerator</span> <span m=''822150''>and an</span> <span m=''822370''>accumulator,</span>
  <span m=''822840''>but</span> <span m=''822940''>it</span> <span m=''823040''>looks</span>
  <span m=''823280''>very</span> <span m=''823520''>different.</span> <span m=''824470''>Because</span>
  <span m=''825100''>partly,</span> <span m=''826540''>the</span> <span m=''827590''>enumerator</span>
  <span m=''827970''>is</span> <span m=''828390''>here</span> <span m=''828560''>in</span>
  <span m=''828670''>this</span> <span m=''828780''>greater</span> <span m=''829080''>than</span>
  <span m=''829260''>sign</span> <span m=''829570''>in</span> <span m=''829660''>the</span>
  <span m=''829760''>test.</span> <span m=''830520''>And</span> <span m=''830680''>partly</span>
  <span m=''831060''>it''s</span> <span m=''831200''>in</span> <span m=''831310''>this</span>
  <span m=''831420''>whole</span> <span m=''831670''>recursive</span> <span m=''832100''>structure</span>
  <span m=''832530''>in</span> <span m=''832600''>the</span> <span m=''832680''>loop,</span>
  <span m=''833240''>and</span> <span m=''833330''>the</span> <span m=''833420''>way</span>
  <span m=''833530''>that</span> <span m=''833650''>we</span> <span m=''833750''>call</span>
  <span m=''834080''>it.</span> <span m=''835680''>And</span> <span m=''835850''>then</span>
  <span m=''836180''>similarly,</span> <span m=''836510''>that''s</span> <span m=''836790''>also</span>
  <span m=''837160''>mixed</span> <span m=''837530''>up</span> <span m=''837720''>in</span>
  <span m=''837840''>there</span> <span m=''837980''>with</span> <span m=''838100''>the</span>
  <span m=''838220''>accumulator,</span> <span m=''838950''>which</span> <span m=''839110''>is</span>
  <span m=''839230''>partly</span> <span m=''839630''>over</span> <span m=''839780''>there</span>
  <span m=''840400''>and</span> <span m=''840650''>partly</span> <span m=''841010''>over</span>
  <span m=''841100''>there.</span> </p><p><span m=''843600''>So</span> <span m=''843910''>these</span>
  <span m=''844090''>very,</span> <span m=''844780''>very</span> <span m=''845070''>natural</span>
  <span m=''845470''>pieces,</span> <span m=''849020''>these</span> <span m=''849160''>very</span>
  <span m=''849450''>natural</span> <span m=''849790''>boxes</span> <span m=''850220''>here</span>
  <span m=''850530''>don''t</span> <span m=''850840''>appear</span> <span m=''851800''>in</span>
  <span m=''851950''>our</span> <span m=''852060''>programs.</span> <span m=''853350''>Because</span>
  <span m=''853580''>they''re</span> <span m=''853670''>kind</span> <span m=''853770''>of</span>
  <span m=''853870''>mixed</span> <span m=''854190''>up.</span> <span m=''854360''>The</span>
  <span m=''854470''>programs</span> <span m=''854870''>don''t</span> <span m=''855080''>chop</span>
  <span m=''855320''>things</span> <span m=''855520''>up</span> <span m=''855650''>in</span>
  <span m=''855730''>the</span> <span m=''855810''>right</span> <span m=''856050''>way.</span>
  <span m=''859450''>Going</span> <span m=''859620''>back</span> <span m=''859800''>to</span>
  <span m=''859890''>this</span> <span m=''860310''>fundamental</span> <span m=''860840''>principle</span>
  <span m=''861300''>of</span> <span m=''861380''>computer</span> <span m=''861770''>science</span>
  <span m=''862240''>that</span> <span m=''862560''>in</span> <span m=''862680''>order</span>
  <span m=''862840''>to</span> <span m=''862920''>control</span> <span m=''863320''>something,</span>
  <span m=''863650''>you</span> <span m=''863750''>need</span> <span m=''863920''>the</span>
  <span m=''863990''>name</span> <span m=''864620''>of</span> <span m=''864810''>it,</span>
  <span m=''865840''>we</span> <span m=''866000''>don''t</span> <span m=''866120''>really</span>
  <span m=''866320''>have</span> <span m=''866480''>control</span> <span m=''867000''>over</span>
  <span m=''867210''>thinking</span> <span m=''867550''>about</span> <span m=''867820''>things</span>
  <span m=''868030''>this</span> <span m=''868190''>way</span> <span m=''868670''>because</span>
  <span m=''869030''>we</span> <span m=''869130''>don''t</span> <span m=''869760''>have</span>
  <span m=''869920''>our</span> <span m=''870010''>hands</span> <span m=''870290''>in</span>
  <span m=''870410''>them</span> <span m=''870500''>explicitly.</span> <span m=''871060''>We</span>
  <span m=''871140''>don''t</span> <span m=''871260''>have</span> <span m=''871390''>a</span>
  <span m=''871450''>good</span> <span m=''871610''>language</span> <span m=''872230''>for</span>
  <span m=''872730''>talking</span> <span m=''873100''>about</span> <span m=''873400''>them.</span>
  </p><p><span m=''875510''>Well,</span> <span m=''877330''>let''s</span> <span m=''877510''>invent</span>
  <span m=''877810''>an</span> <span m=''877880''>appropriate</span> <span m=''878350''>language</span>
  <span m=''882164''>in</span> <span m=''882640''>which</span> <span m=''882850''>we</span>
  <span m=''882950''>can</span> <span m=''883080''>build</span> <span m=''883350''>these</span>
  <span m=''883550''>pieces.</span> <span m=''884515''>The</span> <span m=''885010''>key</span>
  <span m=''885200''>to</span> <span m=''885280''>the</span> <span m=''885390''>language</span>
  <span m=''885950''>is</span> <span m=''886710''>these</span> <span m=''886960''>guys,</span>
  <span m=''887280''>is</span> <span m=''887360''>what</span> <span m=''887630''>is</span>
  <span m=''888360''>these</span> <span m=''888650''>things</span> <span m=''888820''>I</span>
  <span m=''888880''>called</span> <span m=''889130''>signals?</span> <span m=''890480''>What</span>
  <span m=''890610''>are</span> <span m=''890740''>these</span> <span m=''891000''>things</span>
  <span m=''891310''>that</span> <span m=''891430''>are</span> <span m=''891510''>flying</span>
  <span m=''891870''>on</span> <span m=''891970''>the</span> <span m=''892070''>arrows</span>
  <span m=''892450''>between</span> <span m=''892760''>the</span> <span m=''892830''>boxes?</span>
  <span m=''896880''>Well,</span> <span m=''897000''>those</span> <span m=''897280''>things</span>
  <span m=''899960''>are</span> <span m=''900120''>going</span> <span m=''900200''>to</span>
  <span m=''900280''>be</span> <span m=''900370''>data</span> <span m=''900640''>structures</span>
  <span m=''902530''>called</span> <span m=''902840''>streams.</span> <span m=''903850''>That''s</span>
  <span m=''904050''>going</span> <span m=''904130''>to</span> <span m=''904210''>be</span>
  <span m=''904290''>the</span> <span m=''904380''>key</span> <span m=''904650''>to</span>
  <span m=''904770''>inventing</span> <span m=''905210''>this</span> <span m=''905380''>language.</span>
  </p><p><span m=''907980''>What''s</span> <span m=''908210''>a</span> <span m=''908250''>stream?</span>
  <span m=''908600''>Well, a</span> <span m=''908720''>stream</span> <span m=''909070''>is,</span>
  <span m=''909800''>like</span> <span m=''910010''>anything</span> <span m=''910310''>else,</span>
  <span m=''910500''>a data</span> <span m=''910820''>abstraction.</span> <span m=''912220''>So</span>
  <span m=''912410''>I</span> <span m=''912490''>should</span> <span m=''912750''>tell</span>
  <span m=''912910''>you</span> <span m=''913080''>what</span> <span m=''914260''>its</span>
  <span m=''914460''>selectors</span> <span m=''914880''>and</span> <span m=''915000''>constructors</span>
  <span m=''915580''>are.</span> <span m=''916870''>For a</span> <span m=''917090''>stream,</span>
  <span m=''917400''>we''re</span> <span m=''917490''>going</span> <span m=''917550''>to</span>
  <span m=''917610''>have</span> <span m=''918540''>one</span> <span m=''918830''>constructor</span>
  <span m=''919920''>that''s</span> <span m=''920185''>called</span> <span m=''920450''>CONS-stream.</span>
  <span m=''925690''>CONS-stream</span> <span m=''926110''>is</span> <span m=''926230''>going</span>
  <span m=''926370''>to</span> <span m=''926900''>put</span> <span m=''927180''>two</span>
  <span m=''927330''>things</span> <span m=''927590''>together</span> <span m=''928340''>to</span>
  <span m=''928760''>form</span> <span m=''929010''>a</span> <span m=''929060''>thing</span>
  <span m=''929240''>called</span> <span m=''929480''>a</span> <span m=''929510''>stream.</span>
  <span m=''932040''>And</span> <span m=''932200''>then</span> <span m=''932430''>to</span>
  <span m=''932580''>extract</span> <span m=''933030''>things</span> <span m=''933240''>from</span>
  <span m=''933370''>the</span> <span m=''933430''>stream,</span> <span m=''934020''>we''re</span>
  <span m=''934190''>going to</span> <span m=''934310''>have</span> <span m=''934430''>a</span>
  <span m=''934470''>selector</span> <span m=''934950''>called</span> <span m=''935170''>the
  head</span> <span m=''935420''>of</span> <span m=''935540''>the</span> <span m=''935670''>stream.</span>
  </p><p><span m=''938010''>So if I have a</span> <span m=''938450''>stream,</span>
  <span m=''939070''>I</span> <span m=''939365''>can</span> <span m=''939700''>take</span>
  <span m=''939890''>its</span> <span m=''940030''>head</span> <span m=''940815''>or</span>
  <span m=''941170''>I</span> <span m=''941340''>can</span> <span m=''941480''>take</span>
  <span m=''941690''>its</span> <span m=''941890''>tail.</span> <span m=''944720''>And</span>
  <span m=''944980''>remember,</span> <span m=''945310''>I</span> <span m=''945370''>have</span>
  <span m=''945480''>to</span> <span m=''945600''>tell</span> <span m=''945770''>you</span>
  <span m=''946210''>George''s</span> <span m=''946660''>contract</span> <span m=''947260''>here</span>
  <span m=''948250''>to</span> <span m=''948290''>tell</span> <span m=''948410''>you</span>
  <span m=''948560''>what</span> <span m=''948710''>the</span> <span m=''950950''>axioms</span>
  <span m=''951460''>are</span> <span m=''951890''>that</span> <span m=''952050''>relate</span>
  <span m=''952420''>these.</span> <span m=''953160''>And</span> <span m=''953650''>it''s</span>
  <span m=''953790''>going</span> <span m=''953930''>to</span> <span m=''954070''>be</span>
  <span m=''954410''>for</span> <span m=''957000''>any</span> <span m=''958360''>x</span>
  <span m=''959530''>and</span> <span m=''959740''>y,</span> <span m=''963130''>if</span>
  <span m=''963570''>I form</span> <span m=''963990''>the</span> <span m=''964080''>CONS-stream</span>
  <span m=''964530''>and</span> <span m=''964730''>take the</span> <span m=''964980''>head,</span>
  <span m=''965510''>the</span> <span m=''965982''>head</span> <span m=''966926''>of</span>
  <span m=''967790''>CONS-stream</span> <span m=''971070''>of</span> <span m=''971210''>x</span>
  <span m=''971420''>and</span> <span m=''971570''>y</span> <span m=''973640''>is</span>
  <span m=''973750''>going</span> <span m=''973820''>to</span> <span m=''973900''>be</span>
  <span m=''974040''>x</span> <span m=''976200''>and</span> <span m=''976790''>the</span>
  <span m=''976950''>tail</span> <span m=''979795''>of</span> <span m=''980260''>CONS-stream</span>
  <span m=''984120''>of</span> <span m=''984510''>x and</span> <span m=''984800''>y</span>
  <span m=''986590''>is</span> <span m=''986730''>going</span> <span m=''986820''>to</span>
  <span m=''986920''>be</span> <span m=''987020''>y.</span> <span m=''988440''>So</span>
  <span m=''988650''>those</span> <span m=''988850''>are</span> <span m=''988880''>the</span>
  <span m=''989360''>constructor,</span> <span m=''990330''>two</span> <span m=''990560''>selectors</span>
  <span m=''991060''>for</span> <span m=''991180''>streams,</span> <span m=''994190''>and
  an</span> <span m=''994410''>axiom.</span> </p><p><span m=''994750''>There''s</span>
  <span m=''994860''>something</span> <span m=''995120''>fishy</span> <span m=''995490''>here.</span>
  <span m=''996980''>So</span> <span m=''997210''>you</span> <span m=''997310''>might</span>
  <span m=''997490''>notice</span> <span m=''997800''>that</span> <span m=''997900''>these</span>
  <span m=''998060''>are</span> <span m=''998130''>exactly</span> <span m=''1000270''>the</span>
  <span m=''1000450''>axioms</span> <span m=''1000890''>for</span> <span m=''1001060''>CONS,</span>
  <span m=''1001380''>CAR, and</span> <span m=''1001680''>CDR.</span> <span m=''1003710''>If</span>
  <span m=''1004480''>instead</span> <span m=''1004810''>of</span> <span m=''1004900''>writing</span>
  <span m=''1005190''>CONS-stream</span> <span m=''1005470''>I</span> <span m=''1005750''>wrote</span>
  <span m=''1006100''>CONS</span> <span m=''1007210''>and</span> <span m=''1007320''>I</span>
  <span m=''1007430''>said</span> <span m=''1007630''>head</span> <span m=''1007830''>was</span>
  <span m=''1007990''>the</span> <span m=''1008080''>CAR</span> <span m=''1008560''>and</span>
  <span m=''1008800''>tail</span> <span m=''1009200''>was</span> <span m=''1009360''>the</span>
  <span m=''1009440''>CDR,</span> <span m=''1010810''>those</span> <span m=''1010980''>are</span>
  <span m=''1011060''>exactly</span> <span m=''1011610''>the</span> <span m=''1011750''>axioms</span>
  <span m=''1011950''>for</span> <span m=''1012230''>pairs.</span> <span m=''1012810''>And</span>
  <span m=''1012930''>in</span> <span m=''1013030''>fact,</span> <span m=''1013280''>there''s</span>
  <span m=''1013440''>another</span> <span m=''1013720''>thing</span> <span m=''1013930''>here.</span>
  <span m=''1015130''>We''re</span> <span m=''1015240''>going</span> <span m=''1015300''>to</span>
  <span m=''1015370''>have</span> <span m=''1015520''>a</span> <span m=''1015570''>thing</span>
  <span m=''1015710''>called</span> <span m=''1015970''>the-empty-stream,</span> <span
  m=''1022466''>which</span> <span m=''1022930''>is</span> <span m=''1023140''>like</span>
  <span m=''1023320''>the-empty-list.</span> </p><p><span m=''1028319''>So</span>
  <span m=''1028530''>why</span> <span m=''1028730''>am I</span> <span m=''1028900''>introducing</span>
  <span m=''1029329''>this</span> <span m=''1029440''>terminology?</span> <span m=''1030030''>Why
  don''t</span> <span m=''1030200''>I</span> <span m=''1030329''>just</span> <span
  m=''1030540''>keep</span> <span m=''1030690''>talking</span> <span m=''1031060''>about</span>
  <span m=''1031329''>pairs and</span> <span m=''1031730''>lists?</span> <span m=''1032780''>Well,</span>
  <span m=''1033260''>we''ll</span> <span m=''1033380''>see.</span> <span m=''1035510''>For</span>
  <span m=''1035660''>now,</span> <span m=''1035920''>if</span> <span m=''1036010''>you</span>
  <span m=''1036130''>like,</span> <span m=''1037030''>why don''t</span> <span m=''1037390''>you</span>
  <span m=''1037480''>just</span> <span m=''1037690''>pretend</span> <span m=''1038230''>that</span>
  <span m=''1038440''>streams</span> <span m=''1038900''>really</span> <span m=''1039230''>are</span>
  <span m=''1039670''>just</span> <span m=''1039930''>a</span> <span m=''1039980''>terminology</span>
  <span m=''1040619''>for</span> <span m=''1040760''>lists.</span> <span m=''1041560''>And</span>
  <span m=''1041780''>we''ll</span> <span m=''1041869''>see</span> <span m=''1042020''>in
  a</span> <span m=''1042079''>little</span> <span m=''1042329''>while</span> <span
  m=''1042640''>why</span> <span m=''1043839''>we</span> <span m=''1043910''>want</span>
  <span m=''1044020''>to</span> <span m=''1044119''>keep</span> <span m=''1044339''>this</span>
  <span m=''1044890''>extra</span> <span m=''1045240''>abstraction</span> <span m=''1045810''>layer</span>
  <span m=''1046509''>and</span> <span m=''1046900''>not</span> <span m=''1047130''>just</span>
  <span m=''1047329''>call them</span> <span m=''1047670''>lists.</span> </p><p><span
  m=''1052300''>OK,</span> <span m=''1052480''>now that</span> <span m=''1052760''>we</span>
  <span m=''1052880''>have</span> <span m=''1053270''>streams,</span> <span m=''1053730''>we</span>
  <span m=''1053830''>can</span> <span m=''1053930''>start</span> <span m=''1054160''>constructing</span>
  <span m=''1054770''>the</span> <span m=''1054860''>pieces</span> <span m=''1055240''>of
  the</span> <span m=''1055330''>language</span> <span m=''1057060''>to</span> <span
  m=''1057200''>operate</span> <span m=''1057610''>on</span> <span m=''1057770''>streams.</span>
  <span m=''1058760''>And</span> <span m=''1058910''>there</span> <span m=''1058990''>are</span>
  <span m=''1059010''>a</span> <span m=''1059040''>whole</span> <span m=''1059230''>bunch</span>
  <span m=''1059450''>of</span> <span m=''1059530''>very</span> <span m=''1059770''>useful</span>
  <span m=''1060100''>things</span> <span m=''1060350''>that</span> <span m=''1060450''>we</span>
  <span m=''1060560''>could</span> <span m=''1061330''>start</span> <span m=''1061600''>making.</span>
  <span m=''1062120''>For</span> <span m=''1062360''>instance,</span> <span m=''1064880''>we''ll</span>
  <span m=''1065050''>make</span> <span m=''1065220''>our</span> <span m=''1065320''>map</span>
  <span m=''1065650''>box</span> <span m=''1068210''>to</span> <span m=''1068660''>take</span>
  <span m=''1068900''>a</span> <span m=''1068950''>stream,</span> <span m=''1069350''>s,</span>
  <span m=''1074850''>and</span> <span m=''1075640''>a</span> <span m=''1076050''>procedure,</span>
  <span m=''1077490''>and</span> <span m=''1078020''>to</span> <span m=''1078100''>generate</span>
  <span m=''1078520''>a</span> <span m=''1078550''>new</span> <span m=''1078740''>stream</span>
  <span m=''1080100''>which</span> <span m=''1080400''>has</span> <span m=''1081440''>as</span>
  <span m=''1081630''>its</span> <span m=''1081780''>elements</span> <span m=''1082260''>the</span>
  <span m=''1082350''>procedure</span> <span m=''1082840''>applied</span> <span m=''1083220''>to</span>
  <span m=''1083430''>all</span> <span m=''1083550''>the</span> <span m=''1083640''>successive</span>
  <span m=''1084110''>elements</span> <span m=''1084460''>of</span> <span m=''1084520''>s.</span>
  <span m=''1085666''>In</span> <span m=''1086040''>fact,</span> <span m=''1086230''>we''ve</span>
  <span m=''1086360''>seen</span> <span m=''1086680''>this</span> <span m=''1086850''>before.</span>
  <span m=''1087400''>This</span> <span m=''1087590''>is</span> <span m=''1087690''>the</span>
  <span m=''1087770''>procedure</span> <span m=''1088240''>map</span> <span m=''1088740''>that</span>
  <span m=''1089230''>we</span> <span m=''1089340''>did</span> <span m=''1089520''>with</span>
  <span m=''1089680''>lists.</span> <span m=''1090950''>And</span> <span m=''1091100''>you</span>
  <span m=''1091170''>see</span> <span m=''1091510''>it''s</span> <span m=''1091740''>exactly</span>
  <span m=''1092320''>map,</span> <span m=''1092650''>except</span> <span m=''1092910''>we''re</span>
  <span m=''1093490''>testing</span> <span m=''1093870''>for</span> <span m=''1094000''>empty-stream.</span>
  </p><p><span m=''1094650''>Oh, I</span> <span m=''1094730''>forgot</span> <span
  m=''1095010''>to</span> <span m=''1095100''>mention</span> <span m=''1095400''>that.</span>
  <span m=''1095560''>Empty-stream</span> <span m=''1096090''>is</span> <span m=''1096210''>like</span>
  <span m=''1096450''>the</span> <span m=''1096570''>null</span> <span m=''1096750''>test.</span>
  <span m=''1098070''>So</span> <span m=''1098260''>if it''s</span> <span m=''1098410''>empty,</span>
  <span m=''1099300''>we</span> <span m=''1099420''>generate</span> <span m=''1099740''>the</span>
  <span m=''1099850''>empty</span> <span m=''1100120''>stream.</span> <span m=''1100510''>Otherwise,</span>
  <span m=''1101060''>we</span> <span m=''1101360''>form</span> <span m=''1101650''>a</span>
  <span m=''1101700''>new</span> <span m=''1101870''>stream</span> <span m=''1103560''>whose</span>
  <span m=''1103810''>first</span> <span m=''1104110''>element</span> <span m=''1104530''>is</span>
  <span m=''1104700''>the</span> <span m=''1104800''>procedure</span> <span m=''1105360''>applied</span>
  <span m=''1105920''>to</span> <span m=''1106310''>the</span> <span m=''1106400''>head</span>
  <span m=''1106560''>of</span> <span m=''1106640''>the</span> <span m=''1106710''>stream,</span>
  <span m=''1108600''>and</span> <span m=''1108760''>whose</span> <span m=''1108950''>rest</span>
  <span m=''1109610''>is</span> <span m=''1109770''>gotten</span> <span m=''1109980''>by</span>
  <span m=''1110130''>mapping</span> <span m=''1110550''>along</span> <span m=''1110800''>with</span>
  <span m=''1110900''>the</span> <span m=''1110980''>procedure</span> <span m=''1111370''>down</span>
  <span m=''1111570''>the</span> <span m=''1111650''>tail</span> <span m=''1111900''>of</span>
  <span m=''1111970''>the</span> <span m=''1112040''>stream.</span> <span m=''1113140''>So</span>
  <span m=''1113290''>that</span> <span m=''1113410''>looks</span> <span m=''1113580''>exactly</span>
  <span m=''1114070''>like</span> <span m=''1114230''>the</span> <span m=''1114300''>map</span>
  <span m=''1114550''>procedure</span> <span m=''1114920''>we</span> <span m=''1115030''>looked</span>
  <span m=''1115240''>at</span> <span m=''1115400''>before.</span> </p><p><span m=''1117030''>Here''s</span>
  <span m=''1117250''>another</span> <span m=''1117480''>useful</span> <span m=''1117900''>thing.</span>
  <span m=''1118350''>Filter,</span> <span m=''1119180''>this</span> <span m=''1119470''>is
  our</span> <span m=''1119760''>filter</span> <span m=''1120110''>box.</span> <span
  m=''1120460''>We''re</span> <span m=''1120550''>going</span> <span m=''1120630''>to</span>
  <span m=''1120710''>have</span> <span m=''1120940''>a</span> <span m=''1122230''>predicate</span>
  <span m=''1123140''>and</span> <span m=''1123220''>a</span> <span m=''1123310''>stream.</span>
  <span m=''1123890''>We''re</span> <span m=''1124020''>going</span> <span m=''1124090''>to</span>
  <span m=''1124160''>make</span> <span m=''1124340''>a</span> <span m=''1124390''>new</span>
  <span m=''1124600''>stream</span> <span m=''1125360''>that</span> <span m=''1126020''>consists</span>
  <span m=''1126400''>of</span> <span m=''1126510''>all</span> <span m=''1126720''>the</span>
  <span m=''1126830''>elements</span> <span m=''1127190''>of</span> <span m=''1127260''>the</span>
  <span m=''1127390''>original</span> <span m=''1127760''>one</span> <span m=''1128310''>that</span>
  <span m=''1128550''>satisfy</span> <span m=''1128970''>the</span> <span m=''1129070''>predicate.</span>
  <span m=''1130160''>That''s</span> <span m=''1130710''>case</span> <span m=''1131010''>analysis.</span>
  <span m=''1131270''>When</span> <span m=''1131530''>there''s</span> <span m=''1131770''>nothing</span>
  <span m=''1132100''>in</span> <span m=''1132210''>the</span> <span m=''1132270''>stream,</span>
  <span m=''1133030''>we</span> <span m=''1133140''>return</span> <span m=''1133420''>the</span>
  <span m=''1133540''>empty</span> <span m=''1133760''>stream.</span> <span m=''1136280''>We</span>
  <span m=''1136500''>test</span> <span m=''1137540''>the</span> <span m=''1137650''>predicate</span>
  <span m=''1138080''>on</span> <span m=''1138210''>the</span> <span m=''1138260''>head</span>
  <span m=''1138450''>of</span> <span m=''1138530''>the</span> <span m=''1138590''>stream.</span>
  <span m=''1140060''>And</span> <span m=''1140310''>if</span> <span m=''1140400''>it''s</span>
  <span m=''1140570''>true,</span> <span m=''1141530''>we</span> <span m=''1141770''>add</span>
  <span m=''1141920''>the</span> <span m=''1141990''>head</span> <span m=''1142180''>of</span>
  <span m=''1142260''>the</span> <span m=''1142330''>stream</span> <span m=''1143040''>onto</span>
  <span m=''1143420''>the</span> <span m=''1143520''>result</span> <span m=''1144260''>of</span>
  <span m=''1144400''>filtering</span> <span m=''1145230''>the</span> <span m=''1145390''>tail</span>
  <span m=''1145650''>of</span> <span m=''1145720''>the</span> <span m=''1145800''>stream.</span>
  <span m=''1148220''>And</span> <span m=''1148400''>otherwise,</span> <span m=''1148870''>if</span>
  <span m=''1148960''>that</span> <span m=''1149080''>predicate</span> <span m=''1149500''>was</span>
  <span m=''1149630''>false,</span> <span m=''1150480''>we</span> <span m=''1150670''>just</span>
  <span m=''1150870''>filter</span> <span m=''1151030''>the</span> <span m=''1151120''>tail
  of</span> <span m=''1151530''>the</span> <span m=''1151600''>stream.</span> <span
  m=''1153500''>Right,</span> <span m=''1153730''>so</span> <span m=''1153790''>there''s</span>
  <span m=''1153910''>filter.</span> </p><p><span m=''1156595''>Let</span> <span m=''1157020''>me</span>
  <span m=''1157150''>run</span> <span m=''1157310''>through</span> <span m=''1157440''>a</span>
  <span m=''1157500''>couple</span> <span m=''1157790''>more</span> <span m=''1157970''>rather</span>
  <span m=''1158250''>quickly.</span> <span m=''1158560''>They''re</span> <span m=''1158720''>all</span>
  <span m=''1159370''>in</span> <span m=''1159570''>the</span> <span m=''1159640''>book</span>
  <span m=''1159840''>and</span> <span m=''1159920''>you</span> <span m=''1160000''>can</span>
  <span m=''1160150''>look</span> <span m=''1160280''>at</span> <span m=''1160410''>them.</span>
  <span m=''1160880''>Let</span> <span m=''1160990''>me</span> <span m=''1161080''>just</span>
  <span m=''1161270''>flash</span> <span m=''1161610''>through.</span> <span m=''1162110''>Here''s</span>
  <span m=''1162310''>accumulate.</span> <span m=''1163260''>Accumulate</span> <span
  m=''1165090''>takes</span> <span m=''1165480''>a</span> <span m=''1165530''>way</span>
  <span m=''1165810''>of</span> <span m=''1165940''>combining</span> <span m=''1166500''>things</span>
  <span m=''1167390''>and an</span> <span m=''1167690''>initial</span> <span m=''1168040''>value</span>
  <span m=''1168430''>in</span> <span m=''1168490''>a</span> <span m=''1168550''>stream</span>
  <span m=''1170030''>and</span> <span m=''1170220''>sticks</span> <span m=''1170480''>them</span>
  <span m=''1170620''>all</span> <span m=''1170920''>together.</span> <span m=''1171560''>If</span>
  <span m=''1171690''>the</span> <span m=''1171770''>stream''s</span> <span m=''1172080''>empty,</span>
  <span m=''1172390''>it''s</span> <span m=''1172540''>just</span> <span m=''1172710''>the</span>
  <span m=''1172820''>initial</span> <span m=''1173140''>value.</span> <span m=''1173970''>Otherwise,</span>
  <span m=''1174420''>we</span> <span m=''1174520''>combine</span> <span m=''1175250''>the</span>
  <span m=''1175420''>head</span> <span m=''1175600''>of</span> <span m=''1175670''>the</span>
  <span m=''1175740''>stream</span> <span m=''1176290''>with</span> <span m=''1176480''>the</span>
  <span m=''1176550''>result</span> <span m=''1176930''>of</span> <span m=''1177010''>accumulating</span>
  <span m=''1177870''>the</span> <span m=''1178200''>tail</span> <span m=''1178480''>of</span>
  <span m=''1178560''>the</span> <span m=''1178630''>stream</span> <span m=''1178950''>starting</span>
  <span m=''1179290''>from</span> <span m=''1179440''>the</span> <span m=''1179550''>initial</span>
  <span m=''1179840''>value.</span> <span m=''1180900''>So</span> <span m=''1181070''>that''s</span>
  <span m=''1181270''>what</span> <span m=''1181360''>I''d</span> <span m=''1181450''>use</span>
  <span m=''1181610''>to</span> <span m=''1181760''>add</span> <span m=''1181960''>up</span>
  <span m=''1182090''>everything</span> <span m=''1182560''>in the stream.</span>
  <span m=''1182830''>I''d</span> <span m=''1182970''>accumulate</span> <span m=''1183430''>with</span>
  <span m=''1183590''>plus.</span> </p><p><span m=''1185830''>How</span> <span m=''1186040''>would
  I</span> <span m=''1186160''>enumerate</span> <span m=''1186600''>the</span> <span
  m=''1186670''>leaves</span> <span m=''1186930''>of</span> <span m=''1187010''>a</span>
  <span m=''1187080''>tree?</span> <span m=''1188060''>Well,</span> <span m=''1190870''>if</span>
  <span m=''1191210''>the</span> <span m=''1191490''>tree</span> <span m=''1191780''>is</span>
  <span m=''1191880''>just</span> <span m=''1192100''>a</span> <span m=''1192150''>leaf</span>
  <span m=''1192400''>itself,</span> <span m=''1193520''>I</span> <span m=''1193980''>make</span>
  <span m=''1194220''>something</span> <span m=''1194530''>which</span> <span m=''1194670''>only</span>
  <span m=''1194920''>has</span> <span m=''1195150''>that</span> <span m=''1195350''>node</span>
  <span m=''1195580''>in</span> <span m=''1195710''>it.</span> <span m=''1196640''>Otherwise,</span>
  <span m=''1197110''>I</span> <span m=''1197220''>append</span> <span m=''1197540''>together</span>
  <span m=''1198050''>the</span> <span m=''1198310''>stuff</span> <span m=''1198570''>of</span>
  <span m=''1200580''>enumerating</span> <span m=''1200800''>the</span> <span m=''1201100''>left</span>
  <span m=''1201340''>branch</span> <span m=''1201620''>and</span> <span m=''1201730''>the</span>
  <span m=''1201800''>right</span> <span m=''1202020''>branch.</span> <span m=''1204340''>And</span>
  <span m=''1204480''>then</span> <span m=''1204620''>append</span> <span m=''1204980''>here</span>
  <span m=''1205620''>is</span> <span m=''1205810''>like</span> <span m=''1206730''>the</span>
  <span m=''1206870''>ordinary</span> <span m=''1207360''>append</span> <span m=''1207700''>on</span>
  <span m=''1207850''>lists.</span> <span m=''1213190''>You</span> <span m=''1213310''>can</span>
  <span m=''1213450''>look</span> <span m=''1213580''>at</span> <span m=''1213700''>that.</span>
  <span m=''1213850''>That''s</span> <span m=''1214030''>analogous</span> <span m=''1214540''>to</span>
  <span m=''1214650''>the</span> <span m=''1215320''>ordinary</span> <span m=''1215750''>procedure</span>
  <span m=''1216210''>for</span> <span m=''1216410''>appending</span> <span m=''1216950''>two</span>
  <span m=''1217130''>lists.</span> <span m=''1219150''>How</span> <span m=''1219310''>would</span>
  <span m=''1219400''>I</span> <span m=''1219490''>enumerate</span> <span m=''1219760''>an</span>
  <span m=''1220030''>interval?</span> <span m=''1221810''>This</span> <span m=''1222200''>will</span>
  <span m=''1222280''>take</span> <span m=''1222530''>two</span> <span m=''1222710''>integers,</span>
  <span m=''1223110''>low</span> <span m=''1223330''>and</span> <span m=''1223410''>high,</span>
  <span m=''1223950''>and</span> <span m=''1224110''>generate</span> <span m=''1224450''>a</span>
  <span m=''1224500''>stream</span> <span m=''1224990''>of</span> <span m=''1225120''>the</span>
  <span m=''1225320''>integers</span> <span m=''1226020''>going</span> <span m=''1226260''>from</span>
  <span m=''1226440''>low</span> <span m=''1226650''>to high.</span> <span m=''1228106''>And</span>
  <span m=''1228490''>we</span> <span m=''1228640''>can</span> <span m=''1228740''>make</span>
  <span m=''1228870''>a</span> <span m=''1228910''>whole</span> <span m=''1229150''>bunch</span>
  <span m=''1229370''>of</span> <span m=''1229450''>pieces.</span> </p><p><span m=''1231890''>So</span>
  <span m=''1232030''>that''s</span> <span m=''1232220''>a</span> <span m=''1232270''>little</span>
  <span m=''1232510''>language</span> <span m=''1233480''>of</span> <span m=''1233620''>talking</span>
  <span m=''1233980''>about</span> <span m=''1234210''>streams.</span> <span m=''1234530''>Once</span>
  <span m=''1234730''>we</span> <span m=''1234860''>have</span> <span m=''1234980''>streams,</span>
  <span m=''1235380''>we</span> <span m=''1235480''>can</span> <span m=''1235620''>build</span>
  <span m=''1236600''>things</span> <span m=''1236860''>for</span> <span m=''1236950''>manipulating</span>
  <span m=''1237270''>them.</span> <span m=''1237670''>Again,</span> <span m=''1237890''>we''re</span>
  <span m=''1238000''>making</span> <span m=''1238380''>a</span> <span m=''1238520''>language.</span>
  <span m=''1240200''>And</span> <span m=''1240350''>now we</span> <span m=''1240700''>can
  start</span> <span m=''1240800''>expressing</span> <span m=''1241270''>things</span>
  <span m=''1241510''>in</span> <span m=''1241580''>this</span> <span m=''1241750''>language.</span>
  <span m=''1243060''>Here''s</span> <span m=''1244490''>our</span> <span m=''1244670''>original</span>
  <span m=''1245140''>procedure</span> <span m=''1245580''>for</span> <span m=''1245720''>summing</span>
  <span m=''1246020''>the</span> <span m=''1246130''>odd</span> <span m=''1246590''>squares</span>
  <span m=''1246670''>in a</span> <span m=''1246720''>tree.</span> </p><p><span m=''1247310''>And</span>
  <span m=''1247560''>you''ll</span> <span m=''1247670''>notice</span> <span m=''1247930''>it</span>
  <span m=''1248020''>looks</span> <span m=''1249180''>exactly</span> <span m=''1249800''>now</span>
  <span m=''1251010''>like</span> <span m=''1251240''>the</span> <span m=''1251870''>block</span>
  <span m=''1252210''>diagram,</span> <span m=''1252670''>like</span> <span m=''1252800''>the</span>
  <span m=''1252870''>signal</span> <span m=''1253180''>processing</span> <span m=''1253650''>block</span>
  <span m=''1253900''>diagram.</span> <span m=''1254590''>So</span> <span m=''1254760''>to</span>
  <span m=''1254830''>sum</span> <span m=''1255170''>the</span> <span m=''1255310''>odd</span>
  <span m=''1255940''>squares</span> <span m=''1256890''>in</span> <span m=''1257010''>a</span>
  <span m=''1257070''>tree,</span> <span m=''1258000''>we</span> <span m=''1258840''>enumerate</span>
  <span m=''1259700''>the</span> <span m=''1259950''>leaves</span> <span m=''1260230''>of</span>
  <span m=''1260310''>the</span> <span m=''1260390''>tree.</span> <span m=''1261320''>We</span>
  <span m=''1261560''>filter</span> <span m=''1262020''>that</span> <span m=''1262920''>for</span>
  <span m=''1263410''>oddness.</span> <span m=''1264830''>We</span> <span m=''1265090''>map</span>
  <span m=''1265560''>that</span> <span m=''1265780''>for</span> <span m=''1265910''>squareness.</span>
  <span m=''1269320''>And</span> <span m=''1269470''>we</span> <span m=''1269600''>accumulate</span>
  <span m=''1270220''>the</span> <span m=''1270300''>result</span> <span m=''1270670''>of</span>
  <span m=''1270950''>that</span> <span m=''1271630''>using</span> <span m=''1271910''>addition,</span>
  <span m=''1272460''>starting</span> <span m=''1272850''>from</span> <span m=''1272990''>0.</span>
  <span m=''1274760''>So</span> <span m=''1274900''>we</span> <span m=''1275000''>can</span>
  <span m=''1275130''>see</span> <span m=''1275710''>the</span> <span m=''1275980''>pieces</span>
  <span m=''1276470''>that</span> <span m=''1276600''>we</span> <span m=''1276720''>wanted.</span>
  </p><p><span m=''1277290''>Similarly,</span> <span m=''1278040''>the</span> <span
  m=''1278300''>Fibonacci</span> <span m=''1278880''>one,</span> <span m=''1280740''>how</span>
  <span m=''1280860''>do</span> <span m=''1280940''>we</span> <span m=''1281030''>get</span>
  <span m=''1281190''>the</span> <span m=''1281310''>odd</span> <span m=''1281500''>Fibs?</span>
  <span m=''1282050''>Well,</span> <span m=''1282280''>we</span> <span m=''1282730''>enumerate</span>
  <span m=''1283330''>the</span> <span m=''1283430''>interval</span> <span m=''1283750''>from</span>
  <span m=''1283920''>1 to</span> <span m=''1284260''>n,</span> <span m=''1286380''>we</span>
  <span m=''1286560''>map</span> <span m=''1287900''>along</span> <span m=''1288320''>that,</span>
  <span m=''1289000''>computing</span> <span m=''1289460''>the</span> <span m=''1289870''>Fibonacci</span>
  <span m=''1290010''>of</span> <span m=''1290150''>each</span> <span m=''1290290''>one.</span>
  <span m=''1290920''>We</span> <span m=''1291100''>filter</span> <span m=''1292380''>the</span>
  <span m=''1292490''>result</span> <span m=''1292870''>of</span> <span m=''1292960''>those</span>
  <span m=''1293200''>for</span> <span m=''1293310''>oddness.</span> <span m=''1294810''>And</span>
  <span m=''1294960''>we</span> <span m=''1295110''>accumulate</span> <span m=''1295840''>all</span>
  <span m=''1296080''>of</span> <span m=''1296220''>that</span> <span m=''1296370''>stuff</span>
  <span m=''1296920''>using</span> <span m=''1297200''>CONS</span> <span m=''1297940''>starting</span>
  <span m=''1298330''>from</span> <span m=''1298460''>the</span> <span m=''1298570''>empty-list.</span>
  </p><p><span m=''1303650''>OK,</span> <span m=''1306170''>what''s</span> <span m=''1306650''>the</span>
  <span m=''1306750''>advantage</span> <span m=''1307190''>of</span> <span m=''1307290''>this?</span>
  <span m=''1307680''>Well,</span> <span m=''1307830''>for</span> <span m=''1307950''>one</span>
  <span m=''1308220''>thing,</span> <span m=''1308660''>we</span> <span m=''1308850''>now</span>
  <span m=''1309050''>have</span> <span m=''1309240''>pieces</span> <span m=''1309600''>that</span>
  <span m=''1309750''>we</span> <span m=''1309860''>can</span> <span m=''1309980''>start</span>
  <span m=''1310260''>mixing</span> <span m=''1310590''>and</span> <span m=''1310670''>matching.</span>
  <span m=''1311880''>So</span> <span m=''1312060''>for</span> <span m=''1312220''>instance,</span>
  <span m=''1312900''>if</span> <span m=''1312980''>I</span> <span m=''1313040''>wanted</span>
  <span m=''1313270''>to</span> <span m=''1313360''>change</span> <span m=''1313750''>this,</span>
  <span m=''1313940''>if</span> <span m=''1314130''>I</span> <span m=''1314200''>wanted</span>
  <span m=''1314520''>to</span> <span m=''1318230''>compute</span> <span m=''1318550''>the</span>
  <span m=''1318620''>squares</span> <span m=''1319130''>of</span> <span m=''1319220''>the
  integers</span> <span m=''1319700''>and</span> <span m=''1319800''>then</span> <span
  m=''1319940''>filter</span> <span m=''1320200''>them,</span> <span m=''1320400''>all</span>
  <span m=''1320530''>I</span> <span m=''1320600''>need</span> <span m=''1320730''>to</span>
  <span m=''1320860''>do</span> <span m=''1322000''>is</span> <span m=''1322180''>pick</span>
  <span m=''1322360''>up</span> <span m=''1322480''>a</span> <span m=''1322530''>standard</span>
  <span m=''1322990''>piece</span> <span m=''1323240''>like</span> <span m=''1323460''>this</span>
  <span m=''1323750''>in</span> <span m=''1323810''>that</span> <span m=''1324030''>square</span>
  <span m=''1324670''>and</span> <span m=''1324840''>put</span> <span m=''1325010''>it</span>
  <span m=''1325110''>in.</span> <span m=''1326210''>Or</span> <span m=''1326640''>if</span>
  <span m=''1326830''>we</span> <span m=''1326930''>wanted</span> <span m=''1327230''>to</span>
  <span m=''1327330''>do</span> <span m=''1327710''>this</span> <span m=''1327890''>whole</span>
  <span m=''1328130''>Fibonacci</span> <span m=''1328710''>computation</span> <span
  m=''1329810''>on</span> <span m=''1330150''>the</span> <span m=''1330580''>leaves</span>
  <span m=''1330810''>of</span> <span m=''1330880''>a</span> <span m=''1330950''>tree</span>
  <span m=''1331640''>rather</span> <span m=''1331920''>than a</span> <span m=''1332010''>sequence,</span>
  <span m=''1332420''>all</span> <span m=''1332610''>I</span> <span m=''1332680''>need</span>
  <span m=''1332890''>to</span> <span m=''1332980''>do</span> <span m=''1333450''>is</span>
  <span m=''1333600''>replace</span> <span m=''1334220''>this</span> <span m=''1334480''>enumerator</span>
  <span m=''1335340''>with</span> <span m=''1335490''>that</span> <span m=''1335900''>one.</span>
  </p><p><span m=''1338030''>See,</span> <span m=''1338200''>the</span> <span m=''1338330''>advantage</span>
  <span m=''1338770''>of</span> <span m=''1338840''>this</span> <span m=''1338910''>stream</span>
  <span m=''1339230''>processing</span> <span m=''1340290''>is</span> <span m=''1340470''>that</span>
  <span m=''1340650''>we''re</span> <span m=''1340770''>establishing--</span> <span
  m=''1341995''>this</span> <span m=''1342460''>is</span> <span m=''1342660''>one</span>
  <span m=''1342800''>of</span> <span m=''1342850''>the</span> <span m=''1343920''>big</span>
  <span m=''1344180''>themes</span> <span m=''1344450''>of the</span> <span m=''1344560''>course--</span>
  <span m=''1345330''>we''re</span> <span m=''1345490''>establishing</span> <span
  m=''1346090''>conventional</span> <span m=''1346770''>interfaces</span> <span m=''1355440''>that</span>
  <span m=''1355570''>allow</span> <span m=''1355960''>us</span> <span m=''1356140''>to</span>
  <span m=''1356240''>glue</span> <span m=''1356490''>things</span> <span m=''1356760''>together.</span>
  <span m=''1358130''>Things</span> <span m=''1358520''>like</span> <span m=''1358680''>map</span>
  <span m=''1359030''>and</span> <span m=''1359160''>filter</span> <span m=''1359870''>are</span>
  <span m=''1360220''>a</span> <span m=''1360270''>standard</span> <span m=''1360860''>set</span>
  <span m=''1361090''>of</span> <span m=''1361190''>components</span> <span m=''1361730''>that</span>
  <span m=''1361840''>we</span> <span m=''1361950''>can</span> <span m=''1362040''>start</span>
  <span m=''1362290''>using</span> <span m=''1362540''>for</span> <span m=''1362670''>pasting</span>
  <span m=''1363050''>together</span> <span m=''1363350''>programs</span> <span m=''1363820''>in</span>
  <span m=''1363900''>all</span> <span m=''1364020''>sorts</span> <span m=''1364300''>of</span>
  <span m=''1364390''>ways.</span> <span m=''1365750''>It</span> <span m=''1365970''>allows</span>
  <span m=''1366290''>us</span> <span m=''1366400''>to</span> <span m=''1366500''>see</span>
  <span m=''1366940''>the</span> <span m=''1367280''>commonality</span> <span m=''1368100''>of</span>
  <span m=''1368230''>programs.</span> </p><p><span m=''1370090''>I</span> <span m=''1370150''>just</span>
  <span m=''1370260''>ought to</span> <span m=''1370460''>mention,</span> <span m=''1371100''>I''ve</span>
  <span m=''1371280''>only</span> <span m=''1371830''>showed</span> <span m=''1372070''>you</span>
  <span m=''1372220''>two</span> <span m=''1372390''>procedures.</span> <span m=''1373860''>But</span>
  <span m=''1374410''>let</span> <span m=''1374540''>me</span> <span m=''1374670''>emphasize</span>
  <span m=''1375230''>that</span> <span m=''1375380''>this</span> <span m=''1375580''>way</span>
  <span m=''1375990''>of</span> <span m=''1376910''>putting</span> <span m=''1377210''>things</span>
  <span m=''1377420''>together</span> <span m=''1377800''>with</span> <span m=''1377950''>maps,</span>
  <span m=''1378310''>filters,</span> <span m=''1378630''>and</span> <span m=''1379010''>accumulators</span>
  <span m=''1379780''>is</span> <span m=''1380000''>very,</span> <span m=''1380380''>very</span>
  <span m=''1380610''>general.</span> <span m=''1381410''>It''s</span> <span m=''1381840''>the</span>
  <span m=''1384820''>generate</span> <span m=''1385280''>and</span> <span m=''1385460''>test</span>
  <span m=''1386210''>paradigm</span> <span m=''1386630''>for</span> <span m=''1386730''>programs.</span>
  <span m=''1387850''>And as</span> <span m=''1388010''>an</span> <span m=''1388150''>example</span>
  <span m=''1388600''>of</span> <span m=''1388690''>that,</span> <span m=''1389490''>Richard</span>
  <span m=''1389750''>Waters,</span> <span m=''1391110''>who</span> <span m=''1391280''>was
  at</span> <span m=''1391370''>MIT</span> <span m=''1391760''>when</span> <span m=''1391870''>he</span>
  <span m=''1391970''>was</span> <span m=''1392080''>a</span> <span m=''1392130''>graduate</span>
  <span m=''1392560''>student,</span> <span m=''1392860''>as</span> <span m=''1392980''>part</span>
  <span m=''1393170''>of</span> <span m=''1393300''>his</span> <span m=''1393420''>thesis</span>
  <span m=''1393750''>research</span> <span m=''1394060''>went</span> <span m=''1394370''>and</span>
  <span m=''1394660''>analyzed</span> <span m=''1395840''>a</span> <span m=''1395970''>large</span>
  <span m=''1396340''>chunk</span> <span m=''1396650''>of</span> <span m=''1396770''>the</span>
  <span m=''1396880''>IBM</span> <span m=''1397230''>scientific</span> <span m=''1397700''>subroutine</span>
  <span m=''1398590''>library,</span> <span m=''1399850''>and</span> <span m=''1400040''>discovered</span>
  <span m=''1400450''>that</span> <span m=''1400570''>about</span> <span m=''1401380''>60%</span>
  <span m=''1402230''>of</span> <span m=''1402340''>the</span> <span m=''1402410''>programs</span>
  <span m=''1402890''>in</span> <span m=''1403010''>it</span> <span m=''1404090''>could</span>
  <span m=''1404270''>be</span> <span m=''1404390''>expressed</span> <span m=''1405170''>exactly</span>
  <span m=''1405820''>in</span> <span m=''1406490''>terms</span> <span m=''1406830''>using</span>
  <span m=''1407100''>no</span> <span m=''1407240''>more</span> <span m=''1407410''>than</span>
  <span m=''1407540''>what</span> <span m=''1407660''>we''ve</span> <span m=''1407780''>put</span>
  <span m=''1407980''>here--</span> <span m=''1408940''>map,</span> <span m=''1409150''>filter,
  and</span> <span m=''1409610''>accumulate.</span> <span m=''1410710''>All right,</span>
  <span m=''1410860''>let''s</span> <span m=''1411030''>take</span> <span m=''1411180''>a</span>
  <span m=''1411230''>break.</span> <span m=''1416620''>Questions?</span> </p><p><span
  m=''1420470''>AUDIENCE: It seems</span> <span m=''1420950''>like</span> <span m=''1421430''>the</span>
  <span m=''1421910''>essence</span> <span m=''1422390''>of this whole thing</span>
  <span m=''1422870''>is just that</span> <span m=''1423360''>you have</span> <span
  m=''1423600''>a</span> <span m=''1423850''>very</span> <span m=''1424050''>uniform,</span>
  <span m=''1424780''>simple</span> <span m=''1425130''>data</span> <span m=''1425400''>structure</span>
  <span m=''1425980''>to</span> <span m=''1426350''>work</span> <span m=''1426750''>with,
  the</span> <span m=''1427030''>stream.</span> </p><p><span m=''1428380''>PROFESSOR:
  Right.</span> <span m=''1428920''>The</span> <span m=''1429070''>essence</span>
  <span m=''1429400''>is</span> <span m=''1429570''>that</span> <span m=''1429730''>you,</span>
  <span m=''1430150''>again,</span> <span m=''1430420''>it''s</span> <span m=''1430910''>this</span>
  <span m=''1431250''>sense</span> <span m=''1431570''>of</span> <span m=''1431670''>conventional</span>
  <span m=''1432310''>interfaces.</span> <span m=''1433710''>So</span> <span m=''1433850''>you</span>
  <span m=''1433940''>can</span> <span m=''1434040''>start</span> <span m=''1434370''>putting</span>
  <span m=''1434630''>a</span> <span m=''1434680''>lot</span> <span m=''1434830''>of</span>
  <span m=''1434980''>things</span> <span m=''1435190''>together.</span> <span m=''1435610''>And</span>
  <span m=''1436050''>the</span> <span m=''1436230''>stream</span> <span m=''1436550''>is</span>
  <span m=''1438050''>as</span> <span m=''1438430''>you</span> <span m=''1438570''>say,</span>
  <span m=''1438780''>the</span> <span m=''1438850''>uniform</span> <span m=''1439260''>data</span>
  <span m=''1439490''>structure</span> <span m=''1439830''>that</span> <span m=''1440000''>supports</span>
  <span m=''1440420''>that.</span> <span m=''1440890''>This</span> <span m=''1441050''>is</span>
  <span m=''1441180''>very</span> <span m=''1441390''>much</span> <span m=''1441590''>like</span>
  <span m=''1441760''>APL,</span> <span m=''1442270''>by the</span> <span m=''1442510''>way.</span>
  <span m=''1443600''>APL</span> <span m=''1444060''>is</span> <span m=''1444210''>very</span>
  <span m=''1444450''>much</span> <span m=''1444640''>the</span> <span m=''1444720''>same</span>
  <span m=''1444980''>idea,</span> <span m=''1445230''>except</span> <span m=''1445500''>in</span>
  <span m=''1445580''>APL,</span> <span m=''1446060''>instead</span> <span m=''1446330''>of</span>
  <span m=''1446420''>this</span> <span m=''1446510''>stream,</span> <span m=''1447250''>you</span>
  <span m=''1447370''>have</span> <span m=''1447490''>arrays</span> <span m=''1447910''>and</span>
  <span m=''1448030''>vectors.</span> <span m=''1449560''>And</span> <span m=''1449690''>a</span>
  <span m=''1449780''>lot</span> <span m=''1449860''>of</span> <span m=''1449950''>the</span>
  <span m=''1450010''>power</span> <span m=''1450640''>of</span> <span m=''1450780''>APL</span>
  <span m=''1451280''>is</span> <span m=''1452170''>exactly</span> <span m=''1452630''>the</span>
  <span m=''1452700''>same</span> <span m=''1452960''>reason</span> <span m=''1453380''>of
  the</span> <span m=''1453750''>power</span> <span m=''1454080''>of</span> <span
  m=''1454310''>this.</span> <span m=''1459910''>OK,</span> <span m=''1460550''>thank</span>
  <span m=''1460830''>you.</span> <span m=''1460910''>Let''s</span> <span m=''1461050''>take</span>
  <span m=''1461190''>a</span> <span m=''1461230''>break.</span> </p><p><span m=''1497470''>All
  right.</span> <span m=''1497610''>We''ve</span> <span m=''1497810''>been</span>
  <span m=''1497900''>looking</span> <span m=''1498360''>at</span> <span m=''1500850''>ways</span>
  <span m=''1501140''>of</span> <span m=''1501240''>organizing</span> <span m=''1501840''>computations</span>
  <span m=''1502570''>using</span> <span m=''1502830''>streams.</span> <span m=''1503820''>What</span>
  <span m=''1503920''>I</span> <span m=''1504020''>want</span> <span m=''1504120''>to</span>
  <span m=''1504220''>do</span> <span m=''1504330''>now</span> <span m=''1504520''>is</span>
  <span m=''1504630''>just</span> <span m=''1504710''>show</span> <span m=''1504870''>you</span>
  <span m=''1505020''>two</span> <span m=''1507310''>somewhat</span> <span m=''1507560''>more</span>
  <span m=''1507690''>complicated</span> <span m=''1508290''>examples</span> <span
  m=''1508750''>of</span> <span m=''1509300''>that.</span> <span m=''1510810''>Let''s</span>
  <span m=''1511010''>start</span> <span m=''1511340''>by</span> <span m=''1512200''>thinking</span>
  <span m=''1512570''>about</span> <span m=''1513210''>the</span> <span m=''1513410''>following</span>
  <span m=''1514330''>kind</span> <span m=''1514450''>of</span> <span m=''1514570''>utility</span>
  <span m=''1515000''>procedure</span> <span m=''1515400''>that</span> <span m=''1515540''>will</span>
  <span m=''1515640''>come</span> <span m=''1515860''>in</span> <span m=''1516380''>useful.</span>
  <span m=''1516810''>Suppose</span> <span m=''1517150''>I''ve</span> <span m=''1517270''>got</span>
  <span m=''1517460''>a</span> <span m=''1517500''>stream.</span> <span m=''1519960''>And</span>
  <span m=''1520490''>the</span> <span m=''1520660''>elements</span> <span m=''1521300''>of</span>
  <span m=''1521550''>this</span> <span m=''1521640''>stream</span> <span m=''1522090''>are</span>
  <span m=''1522140''>themselves</span> <span m=''1522620''>streams.</span> <span
  m=''1523730''>So</span> <span m=''1524170''>the</span> <span m=''1524380''>first</span>
  <span m=''1524590''>thing</span> <span m=''1524780''>might</span> <span m=''1524960''>be</span>
  <span m=''1525090''>1,</span> <span m=''1525800''>2,</span> <span m=''1526130''>3.</span>
  </p><p><span m=''1532600''>So</span> <span m=''1532950''>I''ve</span> <span m=''1533110''>got
  a</span> <span m=''1533150''>stream.</span> <span m=''1533880''>And</span> <span
  m=''1534070''>each</span> <span m=''1534330''>element</span> <span m=''1538420''>of</span>
  <span m=''1538570''>the</span> <span m=''1538660''>stream</span> <span m=''1539040''>is</span>
  <span m=''1539140''>itself</span> <span m=''1539530''>a</span> <span m=''1539580''>stream.</span>
  <span m=''1540100''>And</span> <span m=''1541140''>what</span> <span m=''1541240''>I''d</span>
  <span m=''1541360''>like</span> <span m=''1541560''>to</span> <span m=''1541690''>do</span>
  <span m=''1542440''>is</span> <span m=''1542670''>build</span> <span m=''1542910''>a</span>
  <span m=''1542950''>stream</span> <span m=''1543620''>that</span> <span m=''1545230''>collects</span>
  <span m=''1545580''>together</span> <span m=''1546010''>all</span> <span m=''1546140''>of</span>
  <span m=''1546280''>the</span> <span m=''1546400''>elements,</span> <span m=''1546760''>pulls</span>
  <span m=''1547010''>all</span> <span m=''1547210''>of the</span> <span m=''1547340''>elements</span>
  <span m=''1547750''>out</span> <span m=''1547870''>of</span> <span m=''1548340''>these</span>
  <span m=''1548480''>sub-streams</span> <span m=''1550110''>and</span> <span m=''1550310''>strings</span>
  <span m=''1550590''>them</span> <span m=''1550740''>all</span> <span m=''1550840''>together</span>
  <span m=''1551210''>in</span> <span m=''1551280''>one</span> <span m=''1551460''>thing.</span>
  <span m=''1552080''>So</span> <span m=''1552400''>just</span> <span m=''1552520''>to</span>
  <span m=''1552610''>show</span> <span m=''1552850''>you</span> <span m=''1553020''>the</span>
  <span m=''1553650''>use</span> <span m=''1553950''>of</span> <span m=''1554040''>this</span>
  <span m=''1554200''>language,</span> <span m=''1554840''>how</span> <span m=''1555060''>easy</span>
  <span m=''1555360''>it</span> <span m=''1555550''>is,</span> <span m=''1556220''>call</span>
  <span m=''1556290''>that</span> <span m=''1556480''>flatten.</span> <span m=''1556960''>And</span>
  <span m=''1557420''>I</span> <span m=''1558200''>can</span> <span m=''1558370''>define</span>
  <span m=''1562670''>to</span> <span m=''1562720''>flatten</span> <span m=''1567920''>this</span>
  <span m=''1568060''>stream</span> <span m=''1569850''>of</span> <span m=''1570020''>streams.</span>
  <span m=''1572564''>Well,</span> <span m=''1573020''>what</span> <span m=''1573310''>is</span>
  <span m=''1573500''>that?</span> <span m=''1573960''>That''s</span> <span m=''1574230''>just</span>
  <span m=''1575200''>an</span> <span m=''1575380''>accumulation.</span> <span m=''1576240''>I</span>
  <span m=''1576500''>want</span> <span m=''1576620''>to</span> <span m=''1576750''>accumulate</span>
  <span m=''1584240''>using</span> <span m=''1584570''>append,</span> <span m=''1585070''>by</span>
  <span m=''1585240''>successively</span> <span m=''1585940''>appending.</span> <span
  m=''1586450''>So I</span> <span m=''1586830''>accumulate</span> <span m=''1588060''>using</span>
  <span m=''1588470''>append</span> <span m=''1588900''>streams,</span> <span m=''1595890''>starting</span>
  <span m=''1596350''>with</span> <span m=''1596590''>the-empty-stream</span> <span
  m=''1606300''>down</span> <span m=''1606790''>that</span> <span m=''1607180''>stream</span>
  <span m=''1607440''>of</span> <span m=''1607520''>streams.</span> </p><p><span m=''1614370''>OK,</span>
  <span m=''1614820''>so</span> <span m=''1614940''>there''s</span> <span m=''1615120''>an</span>
  <span m=''1615200''>example</span> <span m=''1616970''>of</span> <span m=''1617090''>how</span>
  <span m=''1617180''>you</span> <span m=''1617330''>can</span> <span m=''1617430''>start</span>
  <span m=''1617710''>using</span> <span m=''1618110''>these</span> <span m=''1618290''>higher</span>
  <span m=''1618600''>order</span> <span m=''1618870''>things</span> <span m=''1619320''>to
  do</span> <span m=''1619730''>some</span> <span m=''1619880''>interesting</span>
  <span m=''1620240''>operations.</span> <span m=''1620830''>In</span> <span m=''1620890''>fact,</span>
  <span m=''1621050''>there''s</span> <span m=''1621190''>another</span> <span m=''1622660''>useful</span>
  <span m=''1623070''>thing</span> <span m=''1624230''>that I</span> <span m=''1624370''>want</span>
  <span m=''1624480''>to</span> <span m=''1624600''>do.</span> <span m=''1625100''>I
  want</span> <span m=''1625250''>to</span> <span m=''1625440''>define</span> <span
  m=''1625770''>a</span> <span m=''1625810''>procedure</span> <span m=''1626210''>called</span>
  <span m=''1626450''>flat-map,</span> <span m=''1636980''>flat</span> <span m=''1637640''>map</span>
  <span m=''1638500''>of</span> <span m=''1638700''>some</span> <span m=''1638920''>function</span>
  <span m=''1639750''>and a</span> <span m=''1639990''>stream.</span> <span m=''1641840''>And</span>
  <span m=''1642000''>what</span> <span m=''1642270''>this</span> <span m=''1642530''>is</span>
  <span m=''1642620''>going</span> <span m=''1642700''>to</span> <span m=''1642780''>do</span>
  <span m=''1642970''>is</span> <span m=''1643670''>f</span> <span m=''1643860''>will</span>
  <span m=''1643920''>be a</span> <span m=''1644170''>stream</span> <span m=''1644390''>of
  elements.</span> <span m=''1645720''>f</span> <span m=''1645970''>is</span> <span
  m=''1646150''>going</span> <span m=''1646240''>to</span> <span m=''1646330''>be</span>
  <span m=''1647170''>a</span> <span m=''1647370''>function</span> <span m=''1647800''>that</span>
  <span m=''1647950''>for</span> <span m=''1648070''>each</span> <span m=''1648360''>element</span>
  <span m=''1648790''>in</span> <span m=''1648860''>the</span> <span m=''1648930''>stream</span>
  <span m=''1649220''>produces</span> <span m=''1649670''>another</span> <span m=''1650000''>stream.</span>
  </p><p><span m=''1651950''>And</span> <span m=''1652070''>what</span> <span m=''1652140''>I</span>
  <span m=''1652220''>want</span> <span m=''1652330''>to</span> <span m=''1652430''>do</span>
  <span m=''1652550''>is</span> <span m=''1652670''>take</span> <span m=''1652900''>all</span>
  <span m=''1653040''>of</span> <span m=''1653180''>the</span> <span m=''1653290''>elements</span>
  <span m=''1653650''>and</span> <span m=''1653710''>all</span> <span m=''1653830''>of</span>
  <span m=''1653950''>those</span> <span m=''1654050''>streams</span> <span m=''1654990''>and</span>
  <span m=''1655160''>combine</span> <span m=''1655510''>them</span> <span m=''1655610''>together.</span>
  <span m=''1656000''>So</span> <span m=''1656110''>that''s</span> <span m=''1656320''>just</span>
  <span m=''1656500''>going</span> <span m=''1656650''>to</span> <span m=''1656800''>be</span>
  <span m=''1657550''>the</span> <span m=''1658030''>flatten</span> <span m=''1663340''>of</span>
  <span m=''1663870''>map</span> <span m=''1668260''>f</span> <span m=''1668540''>down</span>
  <span m=''1668865''>s.</span> <span m=''1671350''>Each</span> <span m=''1671510''>time</span>
  <span m=''1671710''>I</span> <span m=''1671810''>apply</span> <span m=''1672130''>f</span>
  <span m=''1672290''>to</span> <span m=''1672450''>an</span> <span m=''1672520''>element</span>
  <span m=''1672820''>of</span> <span m=''1672880''>s,</span> <span m=''1673090''>I
  get</span> <span m=''1673210''>a</span> <span m=''1673310''>stream.</span> <span
  m=''1674290''>If I</span> <span m=''1674430''>map it</span> <span m=''1674770''>all</span>
  <span m=''1674850''>the</span> <span m=''1674930''>way</span> <span m=''1675050''>down,</span>
  <span m=''1675340''>I get</span> <span m=''1675440''>a</span> <span m=''1675500''>stream</span>
  <span m=''1675800''>of</span> <span m=''1675880''>streams,</span> <span m=''1676560''>and</span>
  <span m=''1676690''>I''ll</span> <span m=''1676770''>flatten</span> <span m=''1677170''>that.</span>
  </p><p><span m=''1678385''>Well,</span> <span m=''1678740''>I</span> <span m=''1678820''>want</span>
  <span m=''1678980''>to</span> <span m=''1679140''>use</span> <span m=''1679410''>that</span>
  <span m=''1681700''>to</span> <span m=''1682130''>show</span> <span m=''1682260''>you</span>
  <span m=''1683870''>a</span> <span m=''1684000''>new</span> <span m=''1684210''>way</span>
  <span m=''1684390''>to</span> <span m=''1684480''>do</span> <span m=''1684620''>a</span>
  <span m=''1684670''>familiar</span> <span m=''1685120''>kind</span> <span m=''1685330''>of</span>
  <span m=''1685400''>problem.</span> <span m=''1686360''>The</span> <span m=''1686710''>problem''s</span>
  <span m=''1686990''>going</span> <span m=''1687090''>to</span> <span m=''1687180''>be</span>
  <span m=''1690790''>like</span> <span m=''1691130''>a</span> <span m=''1691180''>lot</span>
  <span m=''1691410''>of</span> <span m=''1691490''>problems</span> <span m=''1691880''>you''ve</span>
  <span m=''1691970''>seen,</span> <span m=''1692310''>although</span> <span m=''1692500''>maybe</span>
  <span m=''1692760''>not</span> <span m=''1693010''>this</span> <span m=''1693140''>particular</span>
  <span m=''1693610''>one.</span> <span m=''1694190''>I''m going to</span> <span m=''1694370''>give</span>
  <span m=''1694530''>you</span> <span m=''1694650''>an</span> <span m=''1694730''>integer,</span>
  <span m=''1695090''>n.</span> <span m=''1698480''>And</span> <span m=''1698700''>the</span>
  <span m=''1698920''>problem</span> <span m=''1699310''>is</span> <span m=''1699430''>going</span>
  <span m=''1699600''>to</span> <span m=''1699760''>be</span> <span m=''1701150''>find</span>
  <span m=''1703460''>all</span> <span m=''1703710''>pairs</span> <span m=''1710120''>and</span>
  <span m=''1710390''>integers</span> <span m=''1710900''>i</span> <span m=''1711020''>and</span>
  <span m=''1711170''>j,</span> <span m=''1712160''>between</span> <span m=''1712720''>0</span>
  <span m=''1715000''>and</span> <span m=''1715510''>i,</span> <span m=''1715620''>with</span>
  <span m=''1715860''>j</span> <span m=''1716050''>less</span> <span m=''1716330''>than</span>
  <span m=''1716450''>i,</span> <span m=''1719126''>up to</span> <span m=''1719490''>n,</span>
  <span m=''1722340''>such</span> <span m=''1722740''>that</span> <span m=''1728900''>i</span>
  <span m=''1729100''>plus</span> <span m=''1729450''>j</span> <span m=''1731340''>is</span>
  <span m=''1731530''>prime.</span> </p><p><span m=''1735740''>So</span> <span m=''1735940''>for</span>
  <span m=''1736090''>example,</span> <span m=''1737030''>if</span> <span m=''1737130''>n</span>
  <span m=''1737330''>equals</span> <span m=''1737440''>6,</span> <span m=''1739336''>let''s</span>
  <span m=''1739730''>make a</span> <span m=''1739900''>little</span> <span m=''1740150''>table</span>
  <span m=''1740520''>here,</span> <span m=''1741910''>i</span> <span m=''1743260''>and</span>
  <span m=''1743760''>j</span> <span m=''1745132''>and</span> <span m=''1745520''>i</span>
  <span m=''1745960''>plus</span> <span m=''1746310''>j.</span> <span m=''1749700''>So</span>
  <span m=''1749940''>for,</span> <span m=''1750560''>say,</span> <span m=''1750750''>i</span>
  <span m=''1751060''>equals</span> <span m=''1751180''>2</span> <span m=''1753070''>and</span>
  <span m=''1753240''>j</span> <span m=''1753420''>equals</span> <span m=''1753730''>1,</span>
  <span m=''1754030''>I''d</span> <span m=''1754120''>get</span> <span m=''1754330''>3.</span>
  <span m=''1755520''>And</span> <span m=''1755700''>for</span> <span m=''1755890''>i
  equals</span> <span m=''1756360''>3,</span> <span m=''1757165''>I could</span> <span
  m=''1757430''>have</span> <span m=''1757750''>j</span> <span m=''1757880''>equals</span>
  <span m=''1758240''>2,</span> <span m=''1758600''>and that</span> <span m=''1758940''>would
  be</span> <span m=''1759410''>5.</span> <span m=''1761210''>And</span> <span m=''1761490''>4</span>
  <span m=''1762140''>and</span> <span m=''1762410''>1</span> <span m=''1764226''>would</span>
  <span m=''1764670''>be</span> <span m=''1764910''>5</span> <span m=''1765850''>and</span>
  <span m=''1766030''>so</span> <span m=''1766210''>on,</span> <span m=''1766805''>up</span>
  <span m=''1767150''>until</span> <span m=''1767370''>i goes to</span> <span m=''1767770''>6.</span>
  <span m=''1768400''>And</span> <span m=''1768520''>what</span> <span m=''1768620''>I''d</span>
  <span m=''1768720''>like</span> <span m=''1768870''>to</span> <span m=''1768980''>return</span>
  <span m=''1769810''>is</span> <span m=''1769960''>to</span> <span m=''1770070''>produce</span>
  <span m=''1771850''>a</span> <span m=''1771940''>stream</span> <span m=''1773280''>of</span>
  <span m=''1773460''>all</span> <span m=''1773550''>the</span> <span m=''1773640''>triples</span>
  <span m=''1774030''>like</span> <span m=''1774260''>this,</span> <span m=''1774510''>let''s</span>
  <span m=''1774710''>say</span> <span m=''1775810''>i,</span> <span m=''1776070''>j,</span>
  <span m=''1776300''>and</span> <span m=''1776390''>i plus</span> <span m=''1776490''>j.</span>
  <span m=''1777350''>So</span> <span m=''1777680''>for</span> <span m=''1777830''>each</span>
  <span m=''1778170''>n,</span> <span m=''1778320''>I</span> <span m=''1778410''>want</span>
  <span m=''1778510''>to</span> <span m=''1778560''>generate</span> <span m=''1779010''>this</span>
  <span m=''1779090''>stream.</span> </p><p><span m=''1781530''>OK, well,</span> <span
  m=''1783170''>that''s</span> <span m=''1783450''>easy.</span> <span m=''1783680''>Let''s</span>
  <span m=''1783860''>build</span> <span m=''1784120''>it</span> <span m=''1784310''>up.</span>
  <span m=''1787230''>We</span> <span m=''1787410''>start</span> <span m=''1787640''>like</span>
  <span m=''1787820''>this.</span> <span m=''1790150''>We''re</span> <span m=''1790270''>going</span>
  <span m=''1790330''>to</span> <span m=''1790380''>say</span> <span m=''1790580''>for</span>
  <span m=''1790730''>each</span> <span m=''1792400''>i,</span> <span m=''1795320''>we''re</span>
  <span m=''1795440''>going</span> <span m=''1795510''>to</span> <span m=''1795580''>generate</span>
  <span m=''1795950''>a</span> <span m=''1796000''>stream.</span> <span m=''1796440''>For</span>
  <span m=''1796880''>each</span> <span m=''1797140''>i in the</span> <span m=''1797580''>interval</span>
  <span m=''1797910''>1</span> <span m=''1798260''>through</span> <span m=''1798490''>n,</span>
  <span m=''1798620''>we''re</span> <span m=''1798700''>going</span> <span m=''1798770''>to</span>
  <span m=''1798830''>generate</span> <span m=''1799210''>a</span> <span m=''1799260''>stream.</span>
  <span m=''1800660''>What''s</span> <span m=''1800910''>that</span> <span m=''1801070''>stream</span>
  <span m=''1801370''>going</span> <span m=''1801520''>to</span> <span m=''1801680''>be?</span>
  <span m=''1802230''>We''re</span> <span m=''1802320''>going</span> <span m=''1802380''>to</span>
  <span m=''1802440''>start</span> <span m=''1802750''>by</span> <span m=''1802860''>generating</span>
  <span m=''1803390''>all</span> <span m=''1803530''>the</span> <span m=''1803610''>pairs.</span>
  <span m=''1804180''>So</span> <span m=''1804360''>for</span> <span m=''1804520''>each</span>
  <span m=''1804850''>i,</span> <span m=''1806670''>we''re</span> <span m=''1806780''>going</span>
  <span m=''1806860''>to</span> <span m=''1806930''>generate,</span> <span m=''1808050''>for</span>
  <span m=''1808440''>each</span> <span m=''1808920''>j</span> <span m=''1811590''>in</span>
  <span m=''1811710''>the</span> <span m=''1811840''>interval</span> <span m=''1813250''>1</span>
  <span m=''1813480''>to</span> <span m=''1813850''>i</span> <span m=''1814000''>minus</span>
  <span m=''1814150''>1,</span> <span m=''1816890''>we''ll</span> <span m=''1817030''>generate</span>
  <span m=''1817500''>the</span> <span m=''1817590''>pair,</span> <span m=''1818370''>or</span>
  <span m=''1818490''>the</span> <span m=''1819170''>list</span> <span m=''1819450''>with</span>
  <span m=''1819580''>two</span> <span m=''1819760''>elements</span> <span m=''1820140''>i
  and</span> <span m=''1820400''>j.</span> </p><p><span m=''1823780''>So</span> <span
  m=''1823940''>we</span> <span m=''1824060''>map</span> <span m=''1824400''>along</span>
  <span m=''1826400''>the</span> <span m=''1826560''>interval,</span> <span m=''1828640''>generating</span>
  <span m=''1829110''>the</span> <span m=''1829190''>pairs.</span> <span m=''1830712''>And
  for</span> <span m=''1831180''>each</span> <span m=''1831520''>i,</span> <span m=''1831640''>that</span>
  <span m=''1831880''>generates</span> <span m=''1832270''>a</span> <span m=''1832310''>stream</span>
  <span m=''1832600''>of</span> <span m=''1832690''>pairs.</span> <span m=''1833170''>And</span>
  <span m=''1833550''>we</span> <span m=''1833700''>flatmap</span> <span m=''1834220''>it.</span>
  <span m=''1834590''>Now</span> <span m=''1834750''>we</span> <span m=''1834850''>have</span>
  <span m=''1835020''>all</span> <span m=''1835210''>the</span> <span m=''1835290''>pairs</span>
  <span m=''1835580''>i and</span> <span m=''1835930''>j,</span> <span m=''1836820''>such</span>
  <span m=''1837105''>that i</span> <span m=''1837390''>is less</span> <span m=''1837630''>than</span>
  <span m=''1837750''>j.</span> <span m=''1838730''>So</span> <span m=''1838910''>that</span>
  <span m=''1839080''>builds</span> <span m=''1839360''>that.</span> </p><p><span
  m=''1839850''>Now</span> <span m=''1839970''>we''re</span> <span m=''1840060''>got</span>
  <span m=''1840150''>to</span> <span m=''1840240''>test</span> <span m=''1840580''>them.</span>
  <span m=''1842990''>Well,</span> <span m=''1843280''>we</span> <span m=''1843550''>take</span>
  <span m=''1843850''>that</span> <span m=''1844060''>thing</span> <span m=''1844210''>we</span>
  <span m=''1844330''>just</span> <span m=''1844590''>built,</span> <span m=''1845210''>the</span>
  <span m=''1845230''>flatmap,</span> <span m=''1847040''>and</span> <span m=''1847160''>we</span>
  <span m=''1847270''>filter</span> <span m=''1847690''>it</span> <span m=''1848900''>to</span>
  <span m=''1848990''>see</span> <span m=''1849170''>whether</span> <span m=''1849390''>the</span>
  <span m=''1849490''>i--</span> <span m=''1850090''>see,</span> <span m=''1850270''>we</span>
  <span m=''1850370''>had</span> <span m=''1850520''>an</span> <span m=''1850590''>i</span>
  <span m=''1850830''>and</span> <span m=''1850970''>a</span> <span m=''1851030''>j.</span>
  <span m=''1851660''>i</span> <span m=''1851840''>was</span> <span m=''1852030''>the</span>
  <span m=''1852440''>first</span> <span m=''1852780''>thing</span> <span m=''1853730''>in</span>
  <span m=''1853830''>the</span> <span m=''1853920''>list,</span> <span m=''1854340''>j</span>
  <span m=''1854520''>was</span> <span m=''1854670''>the</span> <span m=''1854730''>second</span>
  <span m=''1855040''>thing</span> <span m=''1855180''>in</span> <span m=''1855260''>the</span>
  <span m=''1855330''>list.</span> <span m=''1857200''>So</span> <span m=''1857390''>we</span>
  <span m=''1857530''>have</span> <span m=''1857670''>a</span> <span m=''1857720''>predicate</span>
  <span m=''1858160''>which</span> <span m=''1858310''>says</span> <span m=''1858530''>in</span>
  <span m=''1858760''>that</span> <span m=''1859030''>list</span> <span m=''1859260''>of</span>
  <span m=''1859340''>two</span> <span m=''1859520''>elements</span> <span m=''1860250''>is</span>
  <span m=''1860410''>the</span> <span m=''1860480''>sum</span> <span m=''1860730''>of</span>
  <span m=''1860790''>the</span> <span m=''1860870''>CAR</span> <span m=''1861090''>and</span>
  <span m=''1861150''>the</span> <span m=''1861210''>CDR</span> <span m=''1861420''>prime.</span>
  <span m=''1862070''>And</span> <span m=''1862190''>we</span> <span m=''1862310''>filter</span>
  <span m=''1863760''>that</span> <span m=''1864180''>collection</span> <span m=''1864560''>of
  pairs</span> <span m=''1864900''>we</span> <span m=''1865000''>just</span> <span
  m=''1865220''>built.</span> <span m=''1866540''>So</span> <span m=''1866690''>those</span>
  <span m=''1866900''>are</span> <span m=''1866930''>the</span> <span m=''1867030''>pairs</span>
  <span m=''1867290''>we</span> <span m=''1867400''>want.</span> </p><p><span m=''1869420''>Now</span>
  <span m=''1869580''>we</span> <span m=''1869670''>go</span> <span m=''1869800''>ahead</span>
  <span m=''1870830''>and</span> <span m=''1871770''>we</span> <span m=''1871990''>take</span>
  <span m=''1872210''>the</span> <span m=''1872290''>result</span> <span m=''1872600''>of</span>
  <span m=''1872700''>that</span> <span m=''1872800''>filter</span> <span m=''1873070''>and</span>
  <span m=''1873340''>we</span> <span m=''1873540''>map</span> <span m=''1873810''>along</span>
  <span m=''1874160''>it,</span> <span m=''1875020''>generating</span> <span m=''1875750''>the</span>
  <span m=''1875980''>list</span> <span m=''1876775''>i</span> <span m=''1877150''>and</span>
  <span m=''1877360''>j</span> <span m=''1878180''>and</span> <span m=''1878340''>i</span>
  <span m=''1878490''>plus</span> <span m=''1878770''>j.</span> <span m=''1879610''>And</span>
  <span m=''1879840''>that''s</span> <span m=''1880040''>our</span> <span m=''1880110''>procedure</span>
  <span m=''1880520''>prime-sum-pairs.</span> <span m=''1882910''>And then</span>
  <span m=''1882990''>just</span> <span m=''1883190''>to</span> <span m=''1883240''>flash</span>
  <span m=''1883570''>it</span> <span m=''1883640''>up, here''s</span> <span m=''1883960''>the</span>
  <span m=''1884030''>whole</span> <span m=''1884190''>procedure.</span> <span m=''1887945''>A</span>
  <span m=''1888210''>map,</span> <span m=''1889380''>a</span> <span m=''1889510''>filter,</span>
  <span m=''1890330''>a</span> <span m=''1890420''>flatmap.</span> <span m=''1894850''>There''s</span>
  <span m=''1895180''>the</span> <span m=''1895250''>whole</span> <span m=''1895430''>thing,</span>
  <span m=''1895680''>even</span> <span m=''1895850''>though</span> <span m=''1895940''>this</span>
  <span m=''1896120''>isn''t</span> <span m=''1896350''>particularly</span> <span
  m=''1896710''>readable.</span> <span m=''1897120''>It''s</span> <span m=''1897430''>just</span>
  <span m=''1897710''>expanding</span> <span m=''1898170''>that</span> <span m=''1898300''>flatmap.</span>
  </p><p><span m=''1900000''>So</span> <span m=''1900110''>there''s</span> <span m=''1900290''>an</span>
  <span m=''1900350''>example</span> <span m=''1903390''>which</span> <span m=''1903600''>illustrates</span>
  <span m=''1904160''>the</span> <span m=''1904240''>general</span> <span m=''1904590''>point</span>
  <span m=''1905090''>that</span> <span m=''1905360''>nested</span> <span m=''1905810''>loops</span>
  <span m=''1907720''>in</span> <span m=''1907850''>this</span> <span m=''1907970''>procedure</span>
  <span m=''1908390''>start</span> <span m=''1908890''>looking</span> <span m=''1909170''>like</span>
  <span m=''1909350''>compositions</span> <span m=''1910030''>of</span> <span m=''1910110''>flatmaps</span>
  <span m=''1910670''>of</span> <span m=''1910760''>flatmaps</span> <span m=''1911300''>of</span>
  <span m=''1911390''>flatmaps</span> <span m=''1911930''>of</span> <span m=''1912030''>maps</span>
  <span m=''1912370''>and</span> <span m=''1912510''>things.</span> <span m=''1914200''>So</span>
  <span m=''1915110''>not</span> <span m=''1915290''>only</span> <span m=''1915480''>can</span>
  <span m=''1915580''>we</span> <span m=''1915880''>enumerate</span> <span m=''1916790''>individual</span>
  <span m=''1917360''>things,</span> <span m=''1917650''>but</span> <span m=''1917780''>by</span>
  <span m=''1917900''>using</span> <span m=''1918200''>flatmaps,</span> <span m=''1919220''>we</span>
  <span m=''1919360''>can</span> <span m=''1919500''>do</span> <span m=''1919650''>what</span>
  <span m=''1919770''>would</span> <span m=''1919910''>correspond</span> <span m=''1920430''>to</span>
  <span m=''1920530''>nested</span> <span m=''1920890''>loops</span> <span m=''1921150''>in</span>
  <span m=''1921240''>most</span> <span m=''1921480''>other</span> <span m=''1921650''>languages.</span>
  </p><p><span m=''1923230''>Of</span> <span m=''1923530''>course,</span> <span m=''1924920''>it''s</span>
  <span m=''1925120''>pretty</span> <span m=''1925320''>awful</span> <span m=''1925680''>to</span>
  <span m=''1925750''>keep</span> <span m=''1925960''>writing</span> <span m=''1926230''>these</span>
  <span m=''1926390''>flatmaps</span> <span m=''1926870''>of</span> <span m=''1926960''>flatmaps</span>
  <span m=''1927460''>of</span> <span m=''1927510''>flatmaps.</span> <span m=''1928410''>Prime-sum-pairs</span>
  <span m=''1929120''>you</span> <span m=''1929210''>saw</span> <span m=''1931860''>looked</span>
  <span m=''1932030''>fairly</span> <span m=''1932350''>complicated,</span> <span
  m=''1933630''>even</span> <span m=''1933830''>though</span> <span m=''1933930''>the</span>
  <span m=''1934070''>individual</span> <span m=''1934500''>pieces</span> <span m=''1934850''>were</span>
  <span m=''1934940''>easy.</span> <span m=''1935480''>So</span> <span m=''1935650''>what</span>
  <span m=''1935810''>you</span> <span m=''1935960''>can</span> <span m=''1936150''>do,</span>
  <span m=''1936640''>if</span> <span m=''1936800''>you</span> <span m=''1936930''>like,</span>
  <span m=''1937150''>is</span> <span m=''1937260''>introduced</span> <span m=''1937650''>some</span>
  <span m=''1937800''>syntactic</span> <span m=''1938440''>sugar</span> <span m=''1939210''>that''s</span>
  <span m=''1939430''>called</span> <span m=''1939670''>collect.</span> <span m=''1941040''>And</span>
  <span m=''1941200''>collect</span> <span m=''1941550''>is</span> <span m=''1941640''>just</span>
  <span m=''1941850''>an</span> <span m=''1941930''>abbreviation</span> <span m=''1942920''>for</span>
  <span m=''1943070''>that</span> <span m=''1943260''>nest</span> <span m=''1943480''>of</span>
  <span m=''1943570''>flatmaps</span> <span m=''1944150''>and</span> <span m=''1944260''>filters</span>
  <span m=''1944670''>arranged</span> <span m=''1945030''>in</span> <span m=''1945080''>that</span>
  <span m=''1945240''>particular</span> <span m=''1945710''>way.</span> <span m=''1946160''>Here''s</span>
  <span m=''1946370''>prime-sum-pairs</span> <span m=''1947100''>again,</span> <span
  m=''1947700''>written</span> <span m=''1947890''>using</span> <span m=''1948150''>collect.</span>
  <span m=''1949620''>It</span> <span m=''1949780''>says</span> <span m=''1950920''>to</span>
  <span m=''1951090''>find</span> <span m=''1951420''>all</span> <span m=''1951560''>those</span>
  <span m=''1951780''>pairs,</span> <span m=''1952100''>I''m</span> <span m=''1952180''>going</span>
  <span m=''1952240''>to</span> <span m=''1952310''>collect</span> <span m=''1952670''>together</span>
  <span m=''1955620''>a</span> <span m=''1955740''>result,</span> <span m=''1956580''>which</span>
  <span m=''1956810''>is</span> <span m=''1956990''>the</span> <span m=''1957080''>list</span>
  <span m=''1957430''>i,</span> <span m=''1957630''>j,</span> <span m=''1958080''>and</span>
  <span m=''1958230''>i plus</span> <span m=''1958430''>j,</span> <span m=''1960910''>that''s</span>
  <span m=''1961110''>going</span> <span m=''1961170''>to</span> <span m=''1961230''>be</span>
  <span m=''1961340''>generated</span> <span m=''1962130''>as</span> <span m=''1962530''>i</span>
  <span m=''1962630''>runs</span> <span m=''1963100''>through</span> <span m=''1963310''>the</span>
  <span m=''1963470''>interval</span> <span m=''1964510''>from</span> <span m=''1964740''>1
  to</span> <span m=''1964970''>n</span> <span m=''1967470''>and</span> <span m=''1967650''>as</span>
  <span m=''1968170''>j</span> <span m=''1968540''>runs</span> <span m=''1968840''>through</span>
  <span m=''1968990''>the</span> <span m=''1969110''>interval</span> <span m=''1970230''>from</span>
  <span m=''1970510''>1</span> <span m=''1971250''>to i</span> <span m=''1971630''>minus</span>
  <span m=''1971760''>1,</span> <span m=''1974220''>such</span> <span m=''1974650''>that</span>
  <span m=''1975260''>i</span> <span m=''1975450''>plus</span> <span m=''1975740''>j
  is</span> <span m=''1976070''>prime.</span> </p><p><span m=''1978040''>So</span>
  <span m=''1978280''>I''m</span> <span m=''1978370''>not</span> <span m=''1978520''>going</span>
  <span m=''1978590''>to</span> <span m=''1978650''>say</span> <span m=''1979080''>what</span>
  <span m=''1979260''>collect does</span> <span m=''1979720''>in</span> <span m=''1979830''>general.</span>
  <span m=''1980690''>You</span> <span m=''1980810''>can</span> <span m=''1981380''>look</span>
  <span m=''1981510''>at</span> <span m=''1981640''>that</span> <span m=''1981800''>by</span>
  <span m=''1981890''>looking</span> <span m=''1982170''>at</span> <span m=''1982220''>it
  in</span> <span m=''1982320''>the</span> <span m=''1982410''>book.</span> <span
  m=''1983420''>But</span> <span m=''1983510''>pretty</span> <span m=''1983760''>much,</span>
  <span m=''1983970''>you</span> <span m=''1984050''>can</span> <span m=''1984170''>see</span>
  <span m=''1984340''>that</span> <span m=''1984450''>the</span> <span m=''1984560''>pieces</span>
  <span m=''1984990''>of</span> <span m=''1985110''>this</span> <span m=''1985810''>are</span>
  <span m=''1986010''>the</span> <span m=''1986130''>pieces</span> <span m=''1986990''>of</span>
  <span m=''1987190''>that</span> <span m=''1987340''>original</span> <span m=''1987720''>procedure</span>
  <span m=''1988040''>I</span> <span m=''1988360''>wrote.</span> <span m=''1988820''>And</span>
  <span m=''1988990''>this</span> <span m=''1989130''>collect</span> <span m=''1989385''>is</span>
  <span m=''1989640''>just</span> <span m=''1989750''>some</span> <span m=''1990600''>syntactic</span>
  <span m=''1991070''>sugar</span> <span m=''1991390''>for</span> <span m=''1991550''>automatically</span>
  <span m=''1992140''>generating</span> <span m=''1992690''>that</span> <span m=''1992890''>nest</span>
  <span m=''1993140''>of</span> <span m=''1993230''>flatmaps</span> <span m=''1994020''>and</span>
  <span m=''1994130''>flatmaps.</span> </p><p><span m=''1996310''>OK,</span> <span
  m=''1998574''>well,</span> <span m=''1999060''>let</span> <span m=''1999210''>me</span>
  <span m=''1999290''>do</span> <span m=''1999410''>one</span> <span m=''1999580''>more</span>
  <span m=''1999800''>example</span> <span m=''2000290''>that</span> <span m=''2000740''>shows</span>
  <span m=''2000970''>you</span> <span m=''2001040''>the</span> <span m=''2001120''>same</span>
  <span m=''2001350''>kind</span> <span m=''2001580''>of</span> <span m=''2001650''>thing.</span>
  <span m=''2002120''>Here''s</span> <span m=''2002290''>a</span> <span m=''2002410''>very</span>
  <span m=''2002700''>famous</span> <span m=''2003060''>problem</span> <span m=''2004590''>that''s</span>
  <span m=''2005080''>used</span> <span m=''2005280''>to</span> <span m=''2005320''>illustrate</span>
  <span m=''2005690''>a</span> <span m=''2005740''>lot</span> <span m=''2005900''>of</span>
  <span m=''2006720''>so-called</span> <span m=''2007130''>backtracking</span> <span
  m=''2007860''>computer</span> <span m=''2008270''>algorithms.</span> <span m=''2008770''>This</span>
  <span m=''2008910''>is</span> <span m=''2008980''>the</span> <span m=''2009260''>eight
  queens</span> <span m=''2009630''>problem.</span> <span m=''2010200''>This</span>
  <span m=''2010360''>is</span> <span m=''2010450''>a</span> <span m=''2010510''>chess</span>
  <span m=''2010820''>board.</span> <span m=''2012370''>And</span> <span m=''2012530''>the</span>
  <span m=''2012720''>eight queens</span> <span m=''2013010''>problem</span> <span
  m=''2013270''>says,</span> <span m=''2013670''>find</span> <span m=''2013970''>a</span>
  <span m=''2014000''>way</span> <span m=''2014110''>to</span> <span m=''2014200''>put</span>
  <span m=''2014400''>down</span> <span m=''2014570''>eight</span> <span m=''2014820''>queens</span>
  <span m=''2015170''>on</span> <span m=''2015290''>a</span> <span m=''2015330''>chess</span>
  <span m=''2015610''>board</span> <span m=''2016430''>so</span> <span m=''2016600''>that</span>
  <span m=''2016760''>no</span> <span m=''2016890''>two</span> <span m=''2017110''>are</span>
  <span m=''2017210''>attacking</span> <span m=''2017660''>each</span> <span m=''2017830''>other.</span>
  </p><p><span m=''2018000''>And</span> <span m=''2018090''>here''s</span> <span m=''2018470''>a</span>
  <span m=''2018540''>particular</span> <span m=''2019050''>solution</span> <span
  m=''2019470''>to</span> <span m=''2019570''>the eight</span> <span m=''2019800''>queens</span>
  <span m=''2020100''>problem.</span> <span m=''2021430''>So</span> <span m=''2021520''>I</span>
  <span m=''2022380''>have</span> <span m=''2022520''>to</span> <span m=''2022640''>make</span>
  <span m=''2022800''>sure</span> <span m=''2022930''>to</span> <span m=''2023000''>put</span>
  <span m=''2023150''>down</span> <span m=''2023340''>queens</span> <span m=''2023610''>so</span>
  <span m=''2023740''>that</span> <span m=''2023900''>no</span> <span m=''2024050''>two</span>
  <span m=''2024260''>are</span> <span m=''2024450''>in</span> <span m=''2024520''>the</span>
  <span m=''2024580''>same</span> <span m=''2024930''>row</span> <span m=''2025650''>or</span>
  <span m=''2025880''>the</span> <span m=''2025980''>same</span> <span m=''2026230''>column</span>
  <span m=''2027730''>or</span> <span m=''2028340''>sit</span> <span m=''2028570''>along</span>
  <span m=''2028810''>the same</span> <span m=''2029100''>diagonal.</span> <span m=''2031410''>Now,</span>
  <span m=''2033260''>there''s</span> <span m=''2033670''>sort</span> <span m=''2033790''>of</span>
  <span m=''2033900''>a</span> <span m=''2035260''>standard</span> <span m=''2035630''>way</span>
  <span m=''2035780''>of</span> <span m=''2035870''>doing</span> <span m=''2036140''>that.</span>
  <span m=''2039740''>Well,</span> <span m=''2039990''>first</span> <span m=''2040340''>we</span>
  <span m=''2040520''>need</span> <span m=''2040660''>to</span> <span m=''2040800''>do</span>
  <span m=''2041040''>is</span> <span m=''2042870''>below</span> <span m=''2043110''>the</span>
  <span m=''2043200''>surface,</span> <span m=''2043700''>at</span> <span m=''2043830''>George''s</span>
  <span m=''2044270''>level.</span> <span m=''2044940''>We</span> <span m=''2045110''>have</span>
  <span m=''2045210''>to</span> <span m=''2045310''>find</span> <span m=''2045530''>some</span>
  <span m=''2045770''>way</span> <span m=''2045920''>to</span> <span m=''2046080''>represent</span>
  <span m=''2046520''>a board,</span> <span m=''2046950''>and</span> <span m=''2047340''>represent</span>
  <span m=''2047840''>positions.</span> <span m=''2048095''>And</span> <span m=''2048350''>we''ll</span>
  <span m=''2048520''>not</span> <span m=''2048710''>worry</span> <span m=''2048960''>about</span>
  <span m=''2049280''>that.</span> </p><p><span m=''2049800''>But</span> <span m=''2050060''>let''s</span>
  <span m=''2050270''>assume</span> <span m=''2051120''>that</span> <span m=''2051330''>there''s</span>
  <span m=''2051510''>a</span> <span m=''2051560''>predicate</span> <span m=''2052020''>called</span>
  <span m=''2052270''>safe.</span> <span m=''2056040''>And</span> <span m=''2056420''>what</span>
  <span m=''2056620''>safe</span> <span m=''2056870''>is</span> <span m=''2056989''>going</span>
  <span m=''2057070''>to</span> <span m=''2057159''>do</span> <span m=''2058050''>is</span>
  <span m=''2058170''>going</span> <span m=''2058239''>to</span> <span m=''2058300''>say</span>
  <span m=''2058469''>given</span> <span m=''2058920''>that</span> <span m=''2059020''>I</span>
  <span m=''2059090''>have</span> <span m=''2059219''>a</span> <span m=''2059260''>bunch</span>
  <span m=''2059460''>of</span> <span m=''2059520''>queens</span> <span m=''2059840''>down</span>
  <span m=''2060000''>on</span> <span m=''2060090''>the</span> <span m=''2060179''>chess</span>
  <span m=''2060460''>board,</span> <span m=''2061440''>is</span> <span m=''2061590''>it</span>
  <span m=''2061699''>OK</span> <span m=''2062360''>to</span> <span m=''2062520''>put</span>
  <span m=''2062650''>a</span> <span m=''2062690''>queen</span> <span m=''2062969''>in</span>
  <span m=''2063179''>this</span> <span m=''2063639''>particular</span> <span m=''2064120''>spot?</span>
  <span m=''2065400''>So</span> <span m=''2065590''>safe</span> <span m=''2065870''>is</span>
  <span m=''2065989''>going</span> <span m=''2066070''>to</span> <span m=''2066159''>take</span>
  <span m=''2066360''>a</span> <span m=''2066460''>row</span> <span m=''2070480''>and</span>
  <span m=''2070590''>a</span> <span m=''2070650''>column.</span> <span m=''2072889''>That''s</span>
  <span m=''2073080''>going</span> <span m=''2073170''>to</span> <span m=''2073270''>be</span>
  <span m=''2073360''>a</span> <span m=''2073400''>place</span> <span m=''2073670''>where</span>
  <span m=''2073800''>I''m going</span> <span m=''2073889''>to</span> <span m=''2073969''>try</span>
  <span m=''2074260''>and</span> <span m=''2074370''>put</span> <span m=''2074510''>down</span>
  <span m=''2074710''>the</span> <span m=''2074780''>next</span> <span m=''2075070''>queen,</span>
  <span m=''2076150''>and</span> <span m=''2079550''>the</span> <span m=''2080110''>rest</span>
  <span m=''2080394''>of</span> <span m=''2082010''>positions.</span> </p><p><span
  m=''2085420''>And</span> <span m=''2085800''>what</span> <span m=''2085969''>safe</span>
  <span m=''2086130''>will</span> <span m=''2086360''>say</span> <span m=''2086690''>is</span>
  <span m=''2087190''>given</span> <span m=''2087630''>that</span> <span m=''2087880''>I</span>
  <span m=''2087980''>already</span> <span m=''2088389''>have</span> <span m=''2088679''>queens</span>
  <span m=''2089040''>down</span> <span m=''2089870''>in</span> <span m=''2090710''>these</span>
  <span m=''2091040''>positions,</span> <span m=''2093080''>is</span> <span m=''2093219''>it</span>
  <span m=''2093350''>safe</span> <span m=''2093670''>to</span> <span m=''2093780''>put</span>
  <span m=''2093920''>another</span> <span m=''2094210''>queen</span> <span m=''2094449''>down</span>
  <span m=''2095150''>in</span> <span m=''2095500''>that</span> <span m=''2095855''>row</span>
  <span m=''2096510''>and</span> <span m=''2096750''>that</span> <span m=''2096889''>column?</span>
  <span m=''2098300''>And</span> <span m=''2098490''>let''s not</span> <span m=''2098670''>worry</span>
  <span m=''2098880''>about</span> <span m=''2099150''>that.</span> <span m=''2099360''>That''s</span>
  <span m=''2099650''>George''s</span> <span m=''2100040''>problem.</span> <span m=''2100450''>and</span>
  <span m=''2100550''>it''s</span> <span m=''2100660''>not</span> <span m=''2100800''>hard</span>
  <span m=''2101000''>to</span> <span m=''2101120''>write.</span> <span m=''2101380''>You</span>
  <span m=''2101450''>just</span> <span m=''2101620''>have</span> <span m=''2101730''>to</span>
  <span m=''2102710''>check</span> <span m=''2102980''>whether</span> <span m=''2104870''>this</span>
  <span m=''2105120''>thing</span> <span m=''2105320''>contains</span> <span m=''2105730''>any</span>
  <span m=''2105950''>things</span> <span m=''2106350''>on</span> <span m=''2106530''>that</span>
  <span m=''2106750''>row</span> <span m=''2106990''>or</span> <span m=''2107080''>that</span>
  <span m=''2107300''>column or</span> <span m=''2107770''>in</span> <span m=''2107840''>that</span>
  <span m=''2108050''>diagonal.</span> </p><p><span m=''2110530''>Now,</span> <span
  m=''2110640''>how</span> <span m=''2110800''>would</span> <span m=''2110910''>you</span>
  <span m=''2111020''>organize</span> <span m=''2111550''>the</span> <span m=''2112180''>program</span>
  <span m=''2112570''>given</span> <span m=''2112840''>that?</span> <span m=''2113590''>And</span>
  <span m=''2113960''>there''s</span> <span m=''2114170''>sort</span> <span m=''2114300''>of</span>
  <span m=''2115670''>a</span> <span m=''2115780''>traditional</span> <span m=''2116340''>way</span>
  <span m=''2116490''>to</span> <span m=''2116570''>organize</span> <span m=''2117080''>it</span>
  <span m=''2118010''>called</span> <span m=''2118230''>backtracking.</span> <span
  m=''2120116''>And</span> <span m=''2120510''>it</span> <span m=''2120870''>says,</span>
  <span m=''2121010''>well,</span> <span m=''2125190''>let''s</span> <span m=''2125410''>think</span>
  <span m=''2125560''>about</span> <span m=''2125980''>all</span> <span m=''2126110''>the</span>
  <span m=''2126230''>ways</span> <span m=''2126510''>of</span> <span m=''2126600''>putting</span>
  <span m=''2127570''>the</span> <span m=''2127800''>first</span> <span m=''2128110''>queen</span>
  <span m=''2128430''>down</span> <span m=''2130130''>in</span> <span m=''2130450''>the</span>
  <span m=''2130680''>first</span> <span m=''2130910''>column.</span> <span m=''2131290''>There</span>
  <span m=''2131510''>are eight</span> <span m=''2131850''>ways.</span> <span m=''2132580''>Well,</span>
  <span m=''2133180''>let''s</span> <span m=''2133450''>say</span> <span m=''2134050''>try</span>
  <span m=''2134290''>the</span> <span m=''2134490''>first</span> <span m=''2134700''>column.</span>
  <span m=''2135880''>Try</span> <span m=''2136360''>column</span> <span m=''2136650''>1,</span>
  <span m=''2136820''>row</span> <span m=''2137040''>1.</span> <span m=''2137300''>These</span>
  <span m=''2137460''>branches</span> <span m=''2137920''>are</span> <span m=''2137990''>going</span>
  <span m=''2138070''>to</span> <span m=''2138150''>represent</span> <span m=''2140180''>the</span>
  <span m=''2140390''>possibilities</span> <span m=''2141220''>at</span> <span m=''2141300''>each</span>
  <span m=''2141510''>level.</span> </p><p><span m=''2143360''>So</span> <span m=''2143600''>I''ll
  try</span> <span m=''2143840''>and</span> <span m=''2143880''>put</span> <span m=''2144010''>a</span>
  <span m=''2144060''>queen</span> <span m=''2144310''>down</span> <span m=''2144520''>in</span>
  <span m=''2144590''>the</span> <span m=''2144650''>first</span> <span m=''2144940''>column.</span>
  <span m=''2145875''>And</span> <span m=''2146300''>now</span> <span m=''2146540''>given</span>
  <span m=''2146770''>that</span> <span m=''2146890''>it''s</span> <span m=''2147050''>in</span>
  <span m=''2147120''>the</span> <span m=''2147190''>first</span> <span m=''2147460''>column,</span>
  <span m=''2147820''>I''ll</span> <span m=''2147920''>try</span> <span m=''2148150''>and</span>
  <span m=''2148240''>put</span> <span m=''2148360''>the</span> <span m=''2148440''>next</span>
  <span m=''2148740''>queen</span> <span m=''2148960''>down in</span> <span m=''2149230''>the</span>
  <span m=''2149410''>first</span> <span m=''2149580''>column.</span> <span m=''2153035''>I''ll
  try</span> <span m=''2153410''>and</span> <span m=''2153550''>put</span> <span m=''2153700''>the</span>
  <span m=''2153770''>first</span> <span m=''2154140''>queen,</span> <span m=''2154890''>the
  one in</span> <span m=''2155130''>the</span> <span m=''2155300''>first</span> <span
  m=''2155470''>column,</span> <span m=''2155780''>down</span> <span m=''2155980''>in</span>
  <span m=''2156050''>the</span> <span m=''2156110''>first</span> <span m=''2156420''>row.</span>
  <span m=''2156920''>I''m sorry.</span> <span m=''2159050''>And then</span> <span
  m=''2159310''>given</span> <span m=''2159490''>that,</span> <span m=''2159670''>we''ll</span>
  <span m=''2159760''>put</span> <span m=''2159910''>the</span> <span m=''2160090''>next</span>
  <span m=''2160270''>queen</span> <span m=''2160510''>down</span> <span m=''2160780''>in</span>
  <span m=''2160860''>the</span> <span m=''2160940''>first</span> <span m=''2161260''>row.</span>
  <span m=''2161390''>And</span> <span m=''2161530''>that''s</span> <span m=''2161660''>no</span>
  <span m=''2161820''>good.</span> </p><p><span m=''2162090''>So I''ll</span> <span
  m=''2162340''>back</span> <span m=''2162670''>up</span> <span m=''2162790''>to</span>
  <span m=''2162900''>here.</span> <span m=''2164200''>And</span> <span m=''2164330''>I''ll</span>
  <span m=''2164410''>say,</span> <span m=''2164850''>oh,</span> <span m=''2165080''>can
  I</span> <span m=''2165250''>put</span> <span m=''2165340''>the</span> <span m=''2165450''>first</span>
  <span m=''2165680''>queen</span> <span m=''2165840''>down</span> <span m=''2166020''>in</span>
  <span m=''2166080''>the</span> <span m=''2166280''>second</span> <span m=''2166480''>row?</span>
  <span m=''2167510''>Well,</span> <span m=''2167620''>that''s</span> <span m=''2167880''>no</span>
  <span m=''2168020''>good.</span> <span m=''2168550''>Oh,</span> <span m=''2168770''>can</span>
  <span m=''2168860''>I put it</span> <span m=''2168970''>down</span> <span m=''2169150''>in
  the</span> <span m=''2169220''>third</span> <span m=''2169520''>row?</span> <span
  m=''2169760''>Well,</span> <span m=''2169840''>that''s</span> <span m=''2170160''>good.</span>
  <span m=''2172790''>Well, now can</span> <span m=''2173130''>I</span> <span m=''2173210''>put</span>
  <span m=''2173390''>the</span> <span m=''2173470''>next</span> <span m=''2173810''>queen</span>
  <span m=''2174010''>down</span> <span m=''2174290''>in the</span> <span m=''2174470''>first</span>
  <span m=''2174640''>column?</span> <span m=''2175380''>Well,</span> <span m=''2175650''>I</span>
  <span m=''2176080''>can''t</span> <span m=''2176400''>visualize</span> <span m=''2176870''>this</span>
  <span m=''2177020''>chess</span> <span m=''2177260''>board</span> <span m=''2177450''>anymore,</span>
  <span m=''2177800''>but</span> <span m=''2177950''>I</span> <span m=''2178030''>think</span>
  <span m=''2178260''>that''s</span> <span m=''2178470''>right.</span> <span m=''2179195''>And</span>
  <span m=''2179490''>I</span> <span m=''2179600''>try</span> <span m=''2179800''>the</span>
  <span m=''2179860''>next</span> <span m=''2180180''>one.</span> </p><p><span m=''2180450''>And</span>
  <span m=''2180670''>at</span> <span m=''2180790''>each</span> <span m=''2181030''>place,</span>
  <span m=''2181940''>I</span> <span m=''2182050''>go</span> <span m=''2182470''>as</span>
  <span m=''2182640''>far</span> <span m=''2183030''>down</span> <span m=''2183220''>this</span>
  <span m=''2183280''>tree</span> <span m=''2183530''>as</span> <span m=''2183640''>I</span>
  <span m=''2183720''>can.</span> <span m=''2184170''>And</span> <span m=''2184410''>I</span>
  <span m=''2185070''>back</span> <span m=''2185430''>up.</span> <span m=''2185640''>If</span>
  <span m=''2185780''>I</span> <span m=''2185850''>get</span> <span m=''2186050''>down</span>
  <span m=''2186270''>to</span> <span m=''2186340''>here</span> <span m=''2186640''>and</span>
  <span m=''2186740''>find</span> <span m=''2186950''>no</span> <span m=''2187110''>possibilities</span>
  <span m=''2188360''>below</span> <span m=''2188740''>there,</span> <span m=''2188970''>I</span>
  <span m=''2189020''>back</span> <span m=''2189270''>all</span> <span m=''2189360''>the</span>
  <span m=''2189440''>way</span> <span m=''2189590''>up</span> <span m=''2189690''>to</span>
  <span m=''2189790''>here,</span> <span m=''2190450''>and</span> <span m=''2190570''>now</span>
  <span m=''2190690''>start</span> <span m=''2190960''>again</span> <span m=''2191280''>generating</span>
  <span m=''2191740''>this</span> <span m=''2191820''>sub-tree.</span> <span m=''2193260''>And
  I sort</span> <span m=''2193650''>of walk</span> <span m=''2193940''>around.</span>
  <span m=''2195050''>And</span> <span m=''2195240''>finally,</span> <span m=''2195560''>if</span>
  <span m=''2195680''>I</span> <span m=''2195750''>ever</span> <span m=''2195940''>manage</span>
  <span m=''2196320''>to</span> <span m=''2196380''>get</span> <span m=''2196490''>all</span>
  <span m=''2196590''>the</span> <span m=''2196690''>way</span> <span m=''2196810''>down,</span>
  <span m=''2197750''>I''ve</span> <span m=''2197870''>found</span> <span m=''2198150''>a</span>
  <span m=''2198180''>solution.</span> </p><p><span m=''2200090''>So</span> <span
  m=''2200130''>that''s</span> <span m=''2200310''>a</span> <span m=''2200380''>typical</span>
  <span m=''2201320''>sort</span> <span m=''2201530''>of</span> <span m=''2203140''>paradigm</span>
  <span m=''2203660''>that''s</span> <span m=''2203830''>used</span> <span m=''2204030''>a</span>
  <span m=''2204070''>lot</span> <span m=''2204755''>in</span> <span m=''2205020''>AI</span>
  <span m=''2205410''>programming.</span> <span m=''2205930''>It''s</span> <span m=''2206060''>called</span>
  <span m=''2206230''>backtracking</span> <span m=''2206870''>search.</span> <span
  m=''2217470''>And</span> <span m=''2221900''>it''s</span> <span m=''2222070''>really</span>
  <span m=''2222310''>unnecessary.</span> <span m=''2223860''>You</span> <span m=''2223970''>saw</span>
  <span m=''2224110''>me</span> <span m=''2224250''>get</span> <span m=''2224410''>confused</span>
  <span m=''2224675''>when I</span> <span m=''2224940''>was</span> <span m=''2225240''>visualizing</span>
  <span m=''2225840''>this</span> <span m=''2226020''>thing.</span> <span m=''2226550''>And</span>
  <span m=''2226860''>you</span> <span m=''2227290''>see</span> <span m=''2227470''>the</span>
  <span m=''2227550''>complication.</span> <span m=''2228550''>This</span> <span m=''2228740''>is</span>
  <span m=''2229420''>a</span> <span m=''2229550''>complicated</span> <span m=''2230160''>thing</span>
  <span m=''2230320''>to</span> <span m=''2230410''>say.</span> </p><p><span m=''2230760''>Why
  is</span> <span m=''2231040''>it</span> <span m=''2231100''>complicated?</span>
  <span m=''2232390''>Its</span> <span m=''2232560''>because</span> <span m=''2232870''>somehow</span>
  <span m=''2233520''>this</span> <span m=''2233780''>program</span> <span m=''2234140''>is</span>
  <span m=''2234270''>too</span> <span m=''2235350''>inordinately</span> <span m=''2236190''>concerned</span>
  <span m=''2236730''>with</span> <span m=''2236890''>time.</span> <span m=''2238580''>It''s</span>
  <span m=''2238790''>too</span> <span m=''2238950''>much--</span> <span m=''2239200''>I</span>
  <span m=''2239260''>try</span> <span m=''2239530''>this</span> <span m=''2239770''>one,</span>
  <span m=''2239930''>and</span> <span m=''2240000''>I</span> <span m=''2240090''>try</span>
  <span m=''2240320''>this</span> <span m=''2240530''>one,</span> <span m=''2240690''>and</span>
  <span m=''2240790''>I</span> <span m=''2240860''>go</span> <span m=''2241010''>back</span>
  <span m=''2241230''>to</span> <span m=''2241330''>the</span> <span m=''2241410''>last</span>
  <span m=''2241670''>possibility.</span> <span m=''2242320''>And</span> <span m=''2242760''>that''s</span>
  <span m=''2243260''>a</span> <span m=''2243310''>complicated</span> <span m=''2243890''>thing.</span>
  <span m=''2244340''>If</span> <span m=''2244520''>I</span> <span m=''2244590''>stop</span>
  <span m=''2244940''>worrying</span> <span m=''2245290''>about</span> <span m=''2245550''>time</span>
  <span m=''2245900''>so</span> <span m=''2246100''>much,</span> <span m=''2248090''>then</span>
  <span m=''2248230''>there''s</span> <span m=''2248370''>a</span> <span m=''2248410''>much</span>
  <span m=''2248590''>simpler</span> <span m=''2248900''>way</span> <span m=''2249040''>to</span>
  <span m=''2249110''>describe</span> <span m=''2249550''>this.</span> <span m=''2251200''>It</span>
  <span m=''2251340''>says,</span> <span m=''2251510''>let''s</span> <span m=''2251710''>imagine</span>
  <span m=''2253360''>that</span> <span m=''2254930''>I</span> <span m=''2255460''>have</span>
  <span m=''2255840''>in</span> <span m=''2255960''>my</span> <span m=''2256080''>hands</span>
  <span m=''2259250''>the</span> <span m=''2259270''>tree</span> <span m=''2260070''>down</span>
  <span m=''2260320''>to</span> <span m=''2261020''>k</span> <span m=''2261220''>minus</span>
  <span m=''2261560''>1</span> <span m=''2261760''>levels.</span> </p><p><span m=''2263400''>See,</span>
  <span m=''2263590''>suppose</span> <span m=''2263990''>I</span> <span m=''2264170''>had</span>
  <span m=''2264350''>in</span> <span m=''2264450''>my</span> <span m=''2264540''>hands</span>
  <span m=''2264990''>all</span> <span m=''2265260''>possible</span> <span m=''2265810''>ways</span>
  <span m=''2269920''>to</span> <span m=''2270060''>put</span> <span m=''2270270''>down</span>
  <span m=''2270670''>queens</span> <span m=''2271030''>in</span> <span m=''2271120''>the</span>
  <span m=''2271210''>first</span> <span m=''2271530''>k</span> <span m=''2271680''>columns.</span>
  <span m=''2273560''>Suppose</span> <span m=''2273790''>I</span> <span m=''2273840''>just</span>
  <span m=''2273980''>had</span> <span m=''2274360''>that.</span> <span m=''2274610''>Let''s</span>
  <span m=''2274820''>not</span> <span m=''2274990''>worry about</span> <span m=''2275110''>how
  we</span> <span m=''2275230''>get</span> <span m=''2275450''>it.</span> <span m=''2277070''>Well,</span>
  <span m=''2277210''>then,</span> <span m=''2277320''>how</span> <span m=''2277440''>do
  I</span> <span m=''2278520''>extend</span> <span m=''2278900''>that?</span> <span
  m=''2279200''>How do I</span> <span m=''2279440''>find</span> <span m=''2279660''>all</span>
  <span m=''2279860''>possible</span> <span m=''2280320''>ways</span> <span m=''2280540''>to</span>
  <span m=''2280630''>put</span> <span m=''2280790''>down</span> <span m=''2280980''>queens</span>
  <span m=''2281270''>in</span> <span m=''2281340''>the</span> <span m=''2281420''>next</span>
  <span m=''2281750''>column?</span> <span m=''2282480''>It''s</span> <span m=''2282590''>really</span>
  <span m=''2282810''>easy.</span> <span m=''2283620''>For</span> <span m=''2283830''>each</span>
  <span m=''2284100''>of</span> <span m=''2284280''>these</span> <span m=''2285500''>positions</span>
  <span m=''2285940''>I</span> <span m=''2286220''>have,</span> <span m=''2291040''>I</span>
  <span m=''2291140''>think</span> <span m=''2291390''>about</span> <span m=''2291860''>putting</span>
  <span m=''2292210''>down</span> <span m=''2292420''>a</span> <span m=''2292480''>queen</span>
  <span m=''2293150''>in</span> <span m=''2293300''>each</span> <span m=''2293550''>row</span>
  <span m=''2295050''>to</span> <span m=''2295190''>make</span> <span m=''2295370''>the</span>
  <span m=''2295550''>next</span> <span m=''2295740''>thing.</span> <span m=''2296160''>And</span>
  <span m=''2296290''>then for</span> <span m=''2296380''>each</span> <span m=''2296670''>one</span>
  <span m=''2296800''>I</span> <span m=''2296860''>put</span> <span m=''2297070''>down,</span>
  <span m=''2297350''>I</span> <span m=''2297580''>filter</span> <span m=''2297980''>those</span>
  <span m=''2298700''>by</span> <span m=''2298820''>the</span> <span m=''2298930''>ones</span>
  <span m=''2299160''>that</span> <span m=''2299260''>are</span> <span m=''2299370''>safe.</span>
  </p><p><span m=''2302080''>So</span> <span m=''2302170''>instead</span> <span m=''2302450''>of</span>
  <span m=''2302520''>thinking</span> <span m=''2302800''>about</span> <span m=''2303000''>this</span>
  <span m=''2303150''>tree as</span> <span m=''2303430''>generated</span> <span m=''2303840''>step</span>
  <span m=''2304060''>by</span> <span m=''2304190''>step,</span> <span m=''2305550''>suppose</span>
  <span m=''2305920''>I</span> <span m=''2305970''>had</span> <span m=''2306180''>it</span>
  <span m=''2306260''>all</span> <span m=''2306540''>there.</span> <span m=''2309680''>And</span>
  <span m=''2309980''>to</span> <span m=''2310120''>extend</span> <span m=''2310490''>it</span>
  <span m=''2310600''>from</span> <span m=''2310690''>level</span> <span m=''2310990''>k</span>
  <span m=''2311170''>minus</span> <span m=''2311520''>1</span> <span m=''2311670''>to</span>
  <span m=''2311770''>level</span> <span m=''2312040''>k,</span> <span m=''2312670''>I</span>
  <span m=''2312780''>just</span> <span m=''2312990''>need</span> <span m=''2313140''>to</span>
  <span m=''2313720''>extend</span> <span m=''2314200''>each</span> <span m=''2314510''>thing</span>
  <span m=''2315250''>in</span> <span m=''2315340''>all</span> <span m=''2315480''>possible</span>
  <span m=''2315910''>ways</span> <span m=''2316510''>and</span> <span m=''2316650''>only</span>
  <span m=''2316840''>keep</span> <span m=''2317030''>the</span> <span m=''2317110''>ones</span>
  <span m=''2317330''>that</span> <span m=''2317440''>are</span> <span m=''2317520''>safe.</span>
  <span m=''2317800''>And</span> <span m=''2317890''>that</span> <span m=''2317980''>will</span>
  <span m=''2318060''>give</span> <span m=''2318160''>me</span> <span m=''2318250''>the</span>
  <span m=''2318350''>tree</span> <span m=''2318660''>to</span> <span m=''2318780''>level</span>
  <span m=''2318970''>k.</span> <span m=''2319300''>And</span> <span m=''2319570''>that''s
  a</span> <span m=''2319750''>recursive</span> <span m=''2320070''>strategy</span>
  <span m=''2320850''>for</span> <span m=''2320990''>solving</span> <span m=''2321300''>the</span>
  <span m=''2321530''>eight queens</span> <span m=''2321820''>problem.</span> </p><p><span
  m=''2324530''>All</span> <span m=''2324620''>right,</span> <span m=''2324720''>well,</span>
  <span m=''2324800''>let''s</span> <span m=''2324980''>look</span> <span m=''2325130''>at</span>
  <span m=''2325250''>it.</span> <span m=''2330280''>To</span> <span m=''2331060''>solve</span>
  <span m=''2331330''>the</span> <span m=''2331600''>eight</span> <span m=''2331710''>queens</span>
  <span m=''2332070''>problem</span> <span m=''2333030''>on</span> <span m=''2333210''>a</span>
  <span m=''2333260''>board</span> <span m=''2333990''>of</span> <span m=''2334170''>some</span>
  <span m=''2334360''>specified</span> <span m=''2335010''>size,</span> <span m=''2338626''>we</span>
  <span m=''2339070''>write</span> <span m=''2339340''>a</span> <span m=''2339470''>sub-procedure</span>
  <span m=''2340190''>called</span> <span m=''2340390''>fill-columns.</span> <span
  m=''2341030''>Fill-columns</span> <span m=''2342270''>is</span> <span m=''2342470''>going</span>
  <span m=''2342580''>to</span> <span m=''2342690''>put</span> <span m=''2342880''>down</span>
  <span m=''2343630''>queens</span> <span m=''2343900''>up</span> <span m=''2344050''>through</span>
  <span m=''2344170''>column</span> <span m=''2344510''>k.</span> <span m=''2346086''>And</span>
  <span m=''2346500''>here''s</span> <span m=''2346730''>the</span> <span m=''2346810''>pattern</span>
  <span m=''2347200''>of</span> <span m=''2347260''>the</span> <span m=''2347310''>recursion.</span>
  <span m=''2347700''>I''m going</span> <span m=''2347900''>to</span> <span m=''2347970''>call</span>
  <span m=''2348220''>fill-columns</span> <span m=''2348830''>with</span> <span m=''2348950''>the</span>
  <span m=''2349020''>size</span> <span m=''2350330''>eventually.</span> </p><p><span
  m=''2352990''>So</span> <span m=''2353180''>fill-columns</span> <span m=''2353810''>says</span>
  <span m=''2353930''>how</span> <span m=''2354030''>to</span> <span m=''2354130''>put</span>
  <span m=''2354290''>down</span> <span m=''2354490''>queens</span> <span m=''2354940''>safely</span>
  <span m=''2355480''>in</span> <span m=''2355550''>the</span> <span m=''2355630''>first</span>
  <span m=''2355910''>k</span> <span m=''2356100''>columns</span> <span m=''2356520''>of</span>
  <span m=''2356640''>this</span> <span m=''2356770''>chess</span> <span m=''2357040''>board</span>
  <span m=''2357260''>with</span> <span m=''2358010''>a</span> <span m=''2358230''>size</span>
  <span m=''2358690''>number</span> <span m=''2359040''>of rows</span> <span m=''2359470''>in
  it.</span> <span m=''2360360''>If k</span> <span m=''2360550''>is</span> <span m=''2360860''>equal</span>
  <span m=''2361110''>to</span> <span m=''2361150''>0,</span> <span m=''2362360''>well,</span>
  <span m=''2362590''>then I</span> <span m=''2362720''>don''t</span> <span m=''2362860''>have
  to put</span> <span m=''2362990''>anything</span> <span m=''2363300''>down.</span>
  <span m=''2363940''>So</span> <span m=''2364100''>my</span> <span m=''2364230''>solution</span>
  <span m=''2364690''>is</span> <span m=''2364790''>just</span> <span m=''2364980''>an</span>
  <span m=''2365060''>empty</span> <span m=''2365260''>chess</span> <span m=''2365540''>board.</span>
  <span m=''2366710''>Otherwise,</span> <span m=''2367130''>I''m</span> <span m=''2367210''>going</span>
  <span m=''2367280''>to</span> <span m=''2367340''>do</span> <span m=''2367450''>some</span>
  <span m=''2367620''>stuff.</span> <span m=''2368070''>And I''m</span> <span m=''2368430''>going
  to use</span> <span m=''2368900''>collect.</span> </p><p><span m=''2370522''>And</span>
  <span m=''2370960''>here''s</span> <span m=''2371190''>the</span> <span m=''2371280''>collect.</span>
  <span m=''2374530''>I</span> <span m=''2376870''>find</span> <span m=''2377200''>all</span>
  <span m=''2377460''>ways</span> <span m=''2377840''>to</span> <span m=''2377960''>put</span>
  <span m=''2378140''>down</span> <span m=''2378360''>queens</span> <span m=''2380380''>in</span>
  <span m=''2380510''>the</span> <span m=''2380590''>first</span> <span m=''2380900''>k</span>
  <span m=''2381160''>minus</span> <span m=''2381390''>1</span> <span m=''2381570''>columns.</span>
  <span m=''2381910''>And</span> <span m=''2382250''>this</span> <span m=''2382510''>was</span>
  <span m=''2382660''>just</span> <span m=''2382820''>what</span> <span m=''2382890''>I</span>
  <span m=''2382970''>set</span> <span m=''2383230''>for.</span> <span m=''2383320''>Imagine</span>
  <span m=''2383820''>I</span> <span m=''2383930''>have</span> <span m=''2384030''>this</span>
  <span m=''2384170''>tree</span> <span m=''2384750''>down</span> <span m=''2385000''>to</span>
  <span m=''2385540''>k</span> <span m=''2385650''>minus</span> <span m=''2385760''>1</span>
  <span m=''2385920''>levels.</span> <span m=''2388880''>And</span> <span m=''2389060''>then</span>
  <span m=''2389810''>I</span> <span m=''2390020''>find</span> <span m=''2390240''>all</span>
  <span m=''2390530''>ways</span> <span m=''2391210''>of</span> <span m=''2391340''>trying</span>
  <span m=''2391660''>a</span> <span m=''2391750''>row,</span> <span m=''2392710''>that''s</span>
  <span m=''2392840''>just</span> <span m=''2393030''>each</span> <span m=''2393230''>of</span>
  <span m=''2393290''>the</span> <span m=''2393370''>possible</span> <span m=''2393820''>rows.</span>
  <span m=''2394130''>They''re</span> <span m=''2394250''>size</span> <span m=''2394640''>rows,</span>
  <span m=''2395070''>so</span> <span m=''2395350''>that''s</span> <span m=''2395630''>enumerate</span>
  <span m=''2396100''>interval.</span> </p><p><span m=''2398040''>And</span> <span
  m=''2398210''>now</span> <span m=''2398330''>what</span> <span m=''2398450''>I</span>
  <span m=''2398510''>do</span> <span m=''2398660''>is</span> <span m=''2398800''>I</span>
  <span m=''2398870''>collect</span> <span m=''2399310''>together</span> <span m=''2402810''>the</span>
  <span m=''2403300''>new</span> <span m=''2403450''>row</span> <span m=''2403730''>I''m</span>
  <span m=''2403870''>going</span> <span m=''2403950''>to</span> <span m=''2404020''>try</span>
  <span m=''2404930''>and</span> <span m=''2405110''>column</span> <span m=''2405370''>k</span>
  <span m=''2408010''>with</span> <span m=''2408140''>the</span> <span m=''2408240''>rest</span>
  <span m=''2408510''>of</span> <span m=''2408570''>the</span> <span m=''2408650''>queens.</span>
  <span m=''2408950''>I</span> <span m=''2409070''>adjoin</span> <span m=''2409410''>a</span>
  <span m=''2409460''>position.</span> <span m=''2410200''>This</span> <span m=''2410390''>is</span>
  <span m=''2410510''>George''s</span> <span m=''2410930''>problem.</span> <span m=''2411290''>An</span>
  <span m=''2411350''>adjoined</span> <span m=''2411640''>position</span> <span m=''2412080''>is</span>
  <span m=''2412200''>like</span> <span m=''2412420''>safe.</span> <span m=''2413640''>It''s</span>
  <span m=''2413790''>a</span> <span m=''2414220''>thing</span> <span m=''2414420''>that</span>
  <span m=''2414540''>takes</span> <span m=''2414790''>a</span> <span m=''2414870''>row</span>
  <span m=''2415460''>and a</span> <span m=''2415730''>column</span> <span m=''2416100''>and</span>
  <span m=''2416160''>the</span> <span m=''2416230''>rest</span> <span m=''2416480''>of</span>
  <span m=''2416530''>the</span> <span m=''2416590''>positions</span> <span m=''2417080''>and</span>
  <span m=''2417160''>makes</span> <span m=''2417380''>a</span> <span m=''2417430''>new</span>
  <span m=''2418120''>position</span> <span m=''2418540''>collection.</span> </p><p><span
  m=''2419660''>So</span> <span m=''2419870''>I</span> <span m=''2419990''>adjoin</span>
  <span m=''2423200''>a</span> <span m=''2423250''>position</span> <span m=''2423830''>of</span>
  <span m=''2424030''>a</span> <span m=''2424100''>new</span> <span m=''2424330''>row</span>
  <span m=''2424930''>and</span> <span m=''2425110''>a</span> <span m=''2425130''>new</span>
  <span m=''2425300''>column</span> <span m=''2426030''>to</span> <span m=''2426230''>the</span>
  <span m=''2426330''>rest</span> <span m=''2426920''>of</span> <span m=''2427040''>the</span>
  <span m=''2427160''>queens,</span> <span m=''2428610''>where</span> <span m=''2428740''>the</span>
  <span m=''2428850''>rest</span> <span m=''2429130''>of</span> <span m=''2429190''>the</span>
  <span m=''2429270''>queens</span> <span m=''2429960''>runs</span> <span m=''2430310''>through</span>
  <span m=''2430490''>all</span> <span m=''2430650''>possible</span> <span m=''2431100''>ways</span>
  <span m=''2431910''>of</span> <span m=''2432050''>solving</span> <span m=''2432420''>the</span>
  <span m=''2432500''>problem</span> <span m=''2432870''>in</span> <span m=''2432990''>k</span>
  <span m=''2433230''>minus</span> <span m=''2433450''>1</span> <span m=''2433640''>columns.</span>
  <span m=''2434620''>And</span> <span m=''2434740''>the</span> <span m=''2434850''>new</span>
  <span m=''2435235''>row</span> <span m=''2435620''>runs</span> <span m=''2435860''>through</span>
  <span m=''2436000''>all</span> <span m=''2436120''>possible</span> <span m=''2436570''>rows</span>
  <span m=''2437890''>such</span> <span m=''2438250''>that</span> <span m=''2439560''>it</span>
  <span m=''2439730''>was</span> <span m=''2439890''>safe</span> <span m=''2440150''>to</span>
  <span m=''2440260''>put</span> <span m=''2440430''>one</span> <span m=''2440600''>there.</span>
  <span m=''2443240''>And</span> <span m=''2443620''>that''s</span> <span m=''2443990''>the</span>
  <span m=''2444050''>whole</span> <span m=''2444170''>program.</span> <span m=''2446500''>There''s</span>
  <span m=''2446690''>the</span> <span m=''2446750''>whole</span> <span m=''2446870''>procedure.</span>
  </p><p><span m=''2449840''>Not</span> <span m=''2450000''>only</span> <span m=''2450170''>that,</span>
  <span m=''2450500''>that</span> <span m=''2450670''>doesn''t</span> <span m=''2450930''>just</span>
  <span m=''2451170''>solve the</span> <span m=''2451600''>eight</span> <span m=''2451690''>queens</span>
  <span m=''2451990''>problem,</span> <span m=''2454550''>it</span> <span m=''2454670''>gives</span>
  <span m=''2454840''>you</span> <span m=''2455000''>all</span> <span m=''2455290''>solutions</span>
  <span m=''2455790''>to</span> <span m=''2455880''>the eight</span> <span m=''2456140''>queens</span>
  <span m=''2456400''>problem.</span> <span m=''2456680''>When</span> <span m=''2456800''>you''re</span>
  <span m=''2456910''>done,</span> <span m=''2457420''>you</span> <span m=''2457550''>have</span>
  <span m=''2457700''>a</span> <span m=''2457740''>stream.</span> <span m=''2458480''>And</span>
  <span m=''2458620''>the</span> <span m=''2458720''>elements</span> <span m=''2459080''>of</span>
  <span m=''2459190''>that stream</span> <span m=''2459550''>are</span> <span m=''2459660''>all</span>
  <span m=''2459970''>possible</span> <span m=''2460410''>ways</span> <span m=''2460650''>of</span>
  <span m=''2460720''>solving</span> <span m=''2461040''>that</span> <span m=''2461190''>problem.</span>
  <span m=''2465310''>Why is</span> <span m=''2465550''>that</span> <span m=''2465700''>simpler?</span>
  <span m=''2466260''>Well,</span> <span m=''2466450''>we</span> <span m=''2466590''>threw</span>
  <span m=''2466900''>away</span> <span m=''2467540''>the</span> <span m=''2467770''>whole</span>
  <span m=''2468020''>idea</span> <span m=''2468360''>that</span> <span m=''2468830''>this</span>
  <span m=''2469250''>is</span> <span m=''2469450''>some</span> <span m=''2469660''>process</span>
  <span m=''2470170''>that</span> <span m=''2470300''>happens</span> <span m=''2470690''>in</span>
  <span m=''2470800''>time</span> <span m=''2471070''>with</span> <span m=''2471200''>state.</span>
  <span m=''2472720''>And we just said</span> <span m=''2473060''>it''s</span> <span
  m=''2473270''>a</span> <span m=''2473320''>whole</span> <span m=''2473580''>collection</span>
  <span m=''2473980''>of</span> <span m=''2474040''>stuff.</span> <span m=''2474420''>And</span>
  <span m=''2474910''>that''s</span> <span m=''2475290''>why</span> <span m=''2475440''>it''s</span>
  <span m=''2475570''>simpler.</span> </p><p><span m=''2478260''>We''ve</span> <span
  m=''2478970''>changed</span> <span m=''2479560''>our</span> <span m=''2479720''>view.</span>
  <span m=''2480110''>Remember,</span> <span m=''2480670''>that''s</span> <span m=''2481520''>where</span>
  <span m=''2481670''>we</span> <span m=''2481780''>started</span> <span m=''2482190''>today.</span>
  <span m=''2482820''>We''ve</span> <span m=''2483030''>changed</span> <span m=''2483600''>our</span>
  <span m=''2483770''>view</span> <span m=''2484680''>of</span> <span m=''2484870''>what</span>
  <span m=''2485110''>it</span> <span m=''2485210''>is</span> <span m=''2485370''>we''re</span>
  <span m=''2485470''>trying</span> <span m=''2485640''>to</span> <span m=''2485820''>model.</span>
  <span m=''2486230''>we</span> <span m=''2486520''>stop</span> <span m=''2487160''>modeling</span>
  <span m=''2487730''>things</span> <span m=''2488010''>that</span> <span m=''2488130''>evolve</span>
  <span m=''2488570''>in</span> <span m=''2488770''>time</span> <span m=''2489410''>and</span>
  <span m=''2489570''>have</span> <span m=''2489750''>steps</span> <span m=''2490570''>and</span>
  <span m=''2490720''>have</span> <span m=''2490900''>state.</span> <span m=''2491750''>And</span>
  <span m=''2491960''>instead,</span> <span m=''2492030''>we''re</span> <span m=''2492150''>trying</span>
  <span m=''2492400''>to</span> <span m=''2492460''>model</span> <span m=''2492740''>this</span>
  <span m=''2493120''>global</span> <span m=''2493550''>thing</span> <span m=''2493790''>like</span>
  <span m=''2493990''>the</span> <span m=''2494770''>whole</span> <span m=''2495050''>flight</span>
  <span m=''2495340''>of</span> <span m=''2495430''>the</span> <span m=''2495510''>chalk,</span>
  <span m=''2496330''>rather</span> <span m=''2496550''>than</span> <span m=''2496720''>its</span>
  <span m=''2497950''>state at</span> <span m=''2498290''>each</span> <span m=''2498470''>instant.</span>
  <span m=''2500750''>Any</span> <span m=''2500930''>questions?</span> </p><p><span
  m=''2503810''>AUDIENCE: It</span> <span m=''2504220''>looks</span> <span m=''2504490''>to</span>
  <span m=''2504570''>me</span> <span m=''2504740''>like</span> <span m=''2505310''>backtracking</span>
  <span m=''2505970''>would</span> <span m=''2506090''>be</span> <span m=''2506190''>searching</span>
  <span m=''2506600''>for</span> <span m=''2507210''>the</span> <span m=''2507330''>first</span>
  <span m=''2507630''>solution</span> <span m=''2508080''>it can</span> <span m=''2508170''>find,</span>
  <span m=''2509340''>whereas</span> <span m=''2509970''>this</span> <span m=''2510210''>recursive</span>
  <span m=''2511140''>search</span> <span m=''2511500''>would</span> <span m=''2511730''>be</span>
  <span m=''2511840''>looking</span> <span m=''2512120''>for</span> <span m=''2512290''>all</span>
  <span m=''2512530''>solutions.</span> <span m=''2514030''>And</span> <span m=''2514450''>it</span>
  <span m=''2514670''>seems</span> <span m=''2515020''>that</span> <span m=''2515350''>if</span>
  <span m=''2515530''>you</span> <span m=''2515640''>have</span> <span m=''2515840''>a</span>
  <span m=''2516040''>large</span> <span m=''2516450''>enough</span> <span m=''2517030''>area</span>
  <span m=''2517470''>to</span> <span m=''2517550''>search,</span> <span m=''2518090''>that</span>
  <span m=''2518610''>the</span> <span m=''2518930''>second</span> <span m=''2519260''>is
  going to</span> <span m=''2519600''>become</span> <span m=''2520260''>impossible.</span>
  </p><p><span m=''2521360''>PROFESSOR: OK,</span> <span m=''2524530''>the</span>
  <span m=''2524810''>answer</span> <span m=''2525070''>to</span> <span m=''2525200''>that</span>
  <span m=''2525390''>question</span> <span m=''2527170''>is</span> <span m=''2527310''>the</span>
  <span m=''2527400''>whole</span> <span m=''2527610''>rest</span> <span m=''2527860''>of</span>
  <span m=''2527930''>this</span> <span m=''2528110''>lecture.</span> <span m=''2528570''>It''s</span>
  <span m=''2529360''>exactly</span> <span m=''2529850''>the</span> <span m=''2529940''>right</span>
  <span m=''2530130''>question.</span> <span m=''2533522''>And</span> <span m=''2533960''>without</span>
  <span m=''2534240''>trying</span> <span m=''2534350''>to</span> <span m=''2534460''>anticipate</span>
  <span m=''2535020''>the</span> <span m=''2535100''>lecture</span> <span m=''2535400''>too</span>
  <span m=''2535540''>much,</span> <span m=''2535960''>you</span> <span m=''2536070''>should</span>
  <span m=''2537240''>start</span> <span m=''2537630''>being</span> <span m=''2537950''>suspicious</span>
  <span m=''2538610''>at</span> <span m=''2538750''>this</span> <span m=''2538940''>point,</span>
  <span m=''2539545''>and</span> <span m=''2539910''>exactly</span> <span m=''2540400''>those</span>
  <span m=''2540600''>kinds</span> <span m=''2540850''>of</span> <span m=''2540920''>suspicions.</span>
  <span m=''2542220''>It''s</span> <span m=''2542400''>wonderful,</span> <span m=''2542840''>but</span>
  <span m=''2543000''>isn''t</span> <span m=''2543210''>it</span> <span m=''2543410''>so</span>
  <span m=''2543550''>terribly</span> <span m=''2543950''>inefficient?</span> <span
  m=''2544830''>That''s</span> <span m=''2545340''>where</span> <span m=''2545460''>we''re</span>
  <span m=''2545590''>going.</span> <span m=''2548100''>So</span> <span m=''2548420''>I</span>
  <span m=''2548530''>won''t</span> <span m=''2548750''>answer</span> <span m=''2549000''>now,</span>
  <span m=''2549290''>but I''ll</span> <span m=''2549590''>answer</span> <span m=''2549740''>later.</span>
  <span m=''2553350''>OK,</span> <span m=''2553630''>let''s</span> <span m=''2553780''>take</span>
  <span m=''2553920''>a</span> <span m=''2553960''>break.</span> </p><p><span m=''2609650''>Well,</span>
  <span m=''2610800''>by</span> <span m=''2610970''>now</span> <span m=''2611210''>you</span>
  <span m=''2611340''>should</span> <span m=''2612470''>be</span> <span m=''2612600''>starting</span>
  <span m=''2612950''>to</span> <span m=''2613010''>get</span> <span m=''2613210''>suspicious.</span>
  <span m=''2615600''>See,</span> <span m=''2615740''>I''ve showed</span> <span m=''2615990''>your</span>
  <span m=''2616110''>this</span> <span m=''2617530''>simple,</span> <span m=''2618400''>elegant</span>
  <span m=''2618840''>way</span> <span m=''2620560''>of</span> <span m=''2621080''>putting</span>
  <span m=''2621450''>programs</span> <span m=''2621890''>together,</span> <span m=''2622980''>very</span>
  <span m=''2623020''>unlike</span> <span m=''2624750''>these</span> <span m=''2624940''>other</span>
  <span m=''2625940''>traditional</span> <span m=''2626440''>programs</span> <span
  m=''2626980''>that</span> <span m=''2627130''>sum</span> <span m=''2627410''>the</span>
  <span m=''2627490''>odd</span> <span m=''2627660''>squares</span> <span m=''2628550''>or</span>
  <span m=''2629810''>compute</span> <span m=''2630150''>the</span> <span m=''2630260''>odd</span>
  <span m=''2630490''>Fibonacci</span> <span m=''2630940''>numbers.</span> <span m=''2633740''>Very</span>
  <span m=''2633900''>unlike</span> <span m=''2634290''>these</span> <span m=''2634470''>programs</span>
  <span m=''2634870''>that</span> <span m=''2635020''>mix</span> <span m=''2635330''>up</span>
  <span m=''2635710''>the</span> <span m=''2636040''>enumerator</span> <span m=''2636960''>and</span>
  <span m=''2637080''>the</span> <span m=''2637200''>filter</span> <span m=''2637880''>and</span>
  <span m=''2637990''>the</span> <span m=''2638100''>accumulator.</span> <span m=''2640440''>And</span>
  <span m=''2641010''>by</span> <span m=''2641150''>mixing</span> <span m=''2641520''>it</span>
  <span m=''2641600''>up,</span> <span m=''2642190''>we</span> <span m=''2643530''>don''t</span>
  <span m=''2643670''>have</span> <span m=''2643820''>all</span> <span m=''2643950''>of</span>
  <span m=''2644070''>these</span> <span m=''2644280''>wonderful</span> <span m=''2644770''>conceptual</span>
  <span m=''2645290''>advantages</span> <span m=''2646110''>of</span> <span m=''2646220''>these</span>
  <span m=''2646320''>streams</span> <span m=''2646780''>pieces,</span> <span m=''2647170''>these</span>
  <span m=''2647990''>wonderful</span> <span m=''2648370''>mix</span> <span m=''2648620''>and</span>
  <span m=''2648720''>match</span> <span m=''2648980''>components</span> <span m=''2649490''>for</span>
  <span m=''2649580''>putting</span> <span m=''2649840''>together</span> <span m=''2650650''>lots</span>
  <span m=''2650970''>and</span> <span m=''2651040''>lots</span> <span m=''2651240''>of</span>
  <span m=''2651310''>programs.</span> </p><p><span m=''2653800''>On the</span> <span
  m=''2653900''>other hand,</span> <span m=''2654310''>most</span> <span m=''2654540''>of</span>
  <span m=''2654590''>the</span> <span m=''2654660''>programs</span> <span m=''2655070''>you''ve</span>
  <span m=''2655170''>seen</span> <span m=''2655410''>look</span> <span m=''2655630''>like</span>
  <span m=''2655810''>these</span> <span m=''2656440''>ugly</span> <span m=''2656660''>ones.</span>
  <span m=''2658340''>Why''s</span> <span m=''2658650''>that?</span> <span m=''2659460''>Can
  it</span> <span m=''2659670''>possibly</span> <span m=''2660220''>be</span> <span
  m=''2660620''>that</span> <span m=''2661750''>computer</span> <span m=''2662180''>scientists</span>
  <span m=''2663260''>are</span> <span m=''2663420''>so</span> <span m=''2663705''>obtuse</span>
  <span m=''2665360''>that</span> <span m=''2665660''>they</span> <span m=''2665770''>don''t</span>
  <span m=''2666070''>notice</span> <span m=''2666940''>that</span> <span m=''2667320''>if</span>
  <span m=''2667400''>you''d</span> <span m=''2667600''>merely</span> <span m=''2667950''>did</span>
  <span m=''2668150''>this</span> <span m=''2668370''>thing,</span> <span m=''2669470''>then</span>
  <span m=''2669780''>you</span> <span m=''2669890''>can</span> <span m=''2670420''>get</span>
  <span m=''2670610''>this</span> <span m=''2670770''>great</span> <span m=''2671010''>programming</span>
  <span m=''2671480''>elegance?</span> <span m=''2673620''>There''s</span> <span m=''2673920''>got</span>
  <span m=''2674060''>to</span> <span m=''2674200''>be</span> <span m=''2674330''>a</span>
  <span m=''2674370''>catch.</span> <span m=''2676760''>And</span> <span m=''2676910''>it''s</span>
  <span m=''2677420''>actually</span> <span m=''2677660''>pretty</span> <span m=''2677850''>easy</span>
  <span m=''2678090''>to</span> <span m=''2678150''>see</span> <span m=''2678320''>what</span>
  <span m=''2678440''>the</span> <span m=''2678520''>catch</span> <span m=''2678850''>is.</span>
  </p><p><span m=''2679510''>Let''s</span> <span m=''2680450''>think</span> <span
  m=''2680600''>about</span> <span m=''2680760''>the</span> <span m=''2680910''>following</span>
  <span m=''2681310''>problem.</span> <span m=''2682030''>Suppose</span> <span m=''2682370''>I</span>
  <span m=''2683850''>tell</span> <span m=''2684030''>you</span> <span m=''2684160''>to</span>
  <span m=''2684240''>find</span> <span m=''2684580''>the</span> <span m=''2684630''>second</span>
  <span m=''2685030''>prime</span> <span m=''2686140''>between</span> <span m=''2686610''>10,000</span>
  <span m=''2687510''>and</span> <span m=''2687620''>1</span> <span m=''2687740''>million,</span>
  <span m=''2689120''>or</span> <span m=''2689310''>if</span> <span m=''2689350''>your</span>
  <span m=''2689490''>computer''s</span> <span m=''2690120''>larger,</span> <span
  m=''2690520''>say</span> <span m=''2690730''>between</span> <span m=''2691020''>10,000</span>
  <span m=''2691760''>and</span> <span m=''2691880''>100</span> <span m=''2692250''>billion,</span>
  <span m=''2692580''>or</span> <span m=''2692650''>something.</span> <span m=''2694105''>And</span>
  <span m=''2694490''>you</span> <span m=''2694590''>say,</span> <span m=''2694740''>oh,</span>
  <span m=''2694940''>that''s</span> <span m=''2695250''>easy.</span> <span m=''2695550''>I</span>
  <span m=''2695630''>can</span> <span m=''2695770''>do</span> <span m=''2695880''>that</span>
  <span m=''2696070''>with</span> <span m=''2696200''>a</span> <span m=''2696240''>stream.</span>
  <span m=''2697080''>All</span> <span m=''2697390''>I</span> <span m=''2697470''>do</span>
  <span m=''2698540''>is</span> <span m=''2698770''>I</span> <span m=''2699190''>enumerate</span>
  <span m=''2700540''>the</span> <span m=''2701180''>interval</span> <span m=''2701530''>from</span>
  <span m=''2701690''>10,000</span> <span m=''2702280''>to</span> <span m=''2702360''>1</span>
  <span m=''2702440''>million.</span> <span m=''2704160''>So</span> <span m=''2704300''>I</span>
  <span m=''2704350''>get</span> <span m=''2704510''>all</span> <span m=''2704680''>those</span>
  <span m=''2704900''>integers</span> <span m=''2705310''>from</span> <span m=''2705410''>10,000</span>
  <span m=''2705910''>to</span> <span m=''2705980''>1</span> <span m=''2706050''>million.</span>
  <span m=''2706800''>I</span> <span m=''2707260''>filter</span> <span m=''2707660''>them</span>
  <span m=''2707890''>for</span> <span m=''2708040''>prime-ness,</span> <span m=''2709290''>so</span>
  <span m=''2709480''>test</span> <span m=''2709810''>all</span> <span m=''2709980''>of</span>
  <span m=''2710020''>them</span> <span m=''2710190''>and</span> <span m=''2710280''>see</span>
  <span m=''2710440''>if</span> <span m=''2710520''>they''re</span> <span m=''2710660''>prime.</span>
  <span m=''2711762''>And I</span> <span m=''2712100''>take</span> <span m=''2712300''>the</span>
  <span m=''2712370''>second</span> <span m=''2712650''>element.</span> <span m=''2713170''>That''s</span>
  <span m=''2713310''>the</span> <span m=''2713380''>head</span> <span m=''2713570''>of</span>
  <span m=''2713670''>the</span> <span m=''2713760''>tail.</span> </p><p><span m=''2716130''>Well,</span>
  <span m=''2716270''>that''s</span> <span m=''2716480''>clearly</span> <span m=''2716780''>pretty</span>
  <span m=''2717010''>ridiculous.</span> <span m=''2721660''>We''d not</span> <span
  m=''2721900''>even</span> <span m=''2722060''>have</span> <span m=''2722300''>room</span>
  <span m=''2722570''>in</span> <span m=''2722630''>the</span> <span m=''2722700''>machine</span>
  <span m=''2723830''>to</span> <span m=''2723920''>store</span> <span m=''2724190''>the</span>
  <span m=''2724320''>integers</span> <span m=''2724620''>in</span> <span m=''2724690''>the</span>
  <span m=''2724760''>first</span> <span m=''2725080''>place,</span> <span m=''2725330''>much</span>
  <span m=''2725540''>less</span> <span m=''2725750''>to</span> <span m=''2725870''>test</span>
  <span m=''2726190''>them.</span> <span m=''2727040''>And</span> <span m=''2727400''>then
  I</span> <span m=''2727470''>only</span> <span m=''2727690''>want</span> <span m=''2727860''>the</span>
  <span m=''2727920''>second</span> <span m=''2728280''>one.</span> <span m=''2729810''>See,</span>
  <span m=''2731990''>the</span> <span m=''2732160''>power</span> <span m=''2733350''>of</span>
  <span m=''2733490''>this</span> <span m=''2733630''>traditional</span> <span m=''2734130''>programming</span>
  <span m=''2734600''>style</span> <span m=''2736500''>is</span> <span m=''2736680''>exactly</span>
  <span m=''2737200''>its</span> <span m=''2737340''>weakness,</span> <span m=''2737830''>that</span>
  <span m=''2738090''>we''re</span> <span m=''2738200''>mixing</span> <span m=''2738670''>up</span>
  <span m=''2739650''>the</span> <span m=''2739860''>enumerating</span> <span m=''2741140''>and</span>
  <span m=''2741460''>the</span> <span m=''2741670''>testing</span> <span m=''2742540''>and</span>
  <span m=''2742680''>the</span> <span m=''2742820''>accumulating.</span> <span m=''2745090''>So</span>
  <span m=''2745280''>we</span> <span m=''2745670''>don''t</span> <span m=''2745950''>do</span>
  <span m=''2746140''>it</span> <span m=''2746210''>all.</span> <span m=''2746670''>So</span>
  <span m=''2748190''>the</span> <span m=''2748460''>very</span> <span m=''2748770''>thing</span>
  <span m=''2749450''>that</span> <span m=''2749680''>makes</span> <span m=''2749930''>it</span>
  <span m=''2750610''>conceptually</span> <span m=''2751250''>ugly</span> <span m=''2752240''>is</span>
  <span m=''2752470''>the</span> <span m=''2752580''>very</span> <span m=''2752880''>thing</span>
  <span m=''2753060''>that</span> <span m=''2753170''>makes</span> <span m=''2753400''>it</span>
  <span m=''2753470''>efficient.</span> <span m=''2755210''>It''s this</span> <span
  m=''2755340''>mixing</span> <span m=''2755700''>up.</span> </p><p><span m=''2757800''>So</span>
  <span m=''2757950''>it</span> <span m=''2758040''>seems</span> <span m=''2758240''>that
  all</span> <span m=''2758330''>I''ve</span> <span m=''2758520''>done</span> <span
  m=''2758690''>this</span> <span m=''2758850''>morning</span> <span m=''2759120''>so</span>
  <span m=''2759310''>far</span> <span m=''2759570''>is</span> <span m=''2759660''>just</span>
  <span m=''2759840''>confuse you.</span> <span m=''2760420''>I</span> <span m=''2760520''>showed</span>
  <span m=''2760760''>you</span> <span m=''2760840''>this</span> <span m=''2760990''>wonderful</span>
  <span m=''2761410''>way</span> <span m=''2761910''>that</span> <span m=''2762190''>programming</span>
  <span m=''2762700''>might</span> <span m=''2762930''>work,</span> <span m=''2763210''>except</span>
  <span m=''2763480''>that</span> <span m=''2763620''>it</span> <span m=''2763730''>doesn''t.</span>
  <span m=''2765840''>Well,</span> <span m=''2766910''>here''s</span> <span m=''2767100''>where</span>
  <span m=''2767200''>the</span> <span m=''2767310''>wonderful</span> <span m=''2767720''>thing</span>
  <span m=''2767880''>happens.</span> <span m=''2769040''>It</span> <span m=''2769160''>turns</span>
  <span m=''2769440''>out</span> <span m=''2769800''>in</span> <span m=''2770070''>this</span>
  <span m=''2770350''>game</span> <span m=''2770950''>that</span> <span m=''2771260''>we</span>
  <span m=''2771570''>really</span> <span m=''2772430''>can</span> <span m=''2772590''>have</span>
  <span m=''2772830''>our</span> <span m=''2772940''>cake</span> <span m=''2773210''>and</span>
  <span m=''2773290''>eat</span> <span m=''2773560''>it</span> <span m=''2773670''>too.</span>
  <span m=''2774870''>And</span> <span m=''2775010''>what</span> <span m=''2775110''>I</span>
  <span m=''2775220''>mean</span> <span m=''2775560''>by</span> <span m=''2775740''>that</span>
  <span m=''2778260''>is</span> <span m=''2778470''>that</span> <span m=''2779100''>we</span>
  <span m=''2779270''>really</span> <span m=''2779700''>can</span> <span m=''2779870''>write</span>
  <span m=''2780280''>stream</span> <span m=''2780640''>programs</span> <span m=''2781110''>exactly</span>
  <span m=''2781580''>like</span> <span m=''2781760''>the</span> <span m=''2781840''>ones</span>
  <span m=''2782050''>I</span> <span m=''2782180''>wrote</span> <span m=''2783540''>and</span>
  <span m=''2783760''>arrange</span> <span m=''2784210''>things</span> <span m=''2785320''>so</span>
  <span m=''2785520''>that</span> <span m=''2786050''>when</span> <span m=''2786270''>the</span>
  <span m=''2786330''>machine</span> <span m=''2786680''>actually</span> <span m=''2787320''>runs,</span>
  <span m=''2788380''>it''s</span> <span m=''2788590''>as</span> <span m=''2788830''>efficient</span>
  <span m=''2789300''>as</span> <span m=''2789410''>running</span> <span m=''2789720''>this</span>
  <span m=''2790120''>traditional</span> <span m=''2790630''>programming</span> <span
  m=''2791120''>style</span> <span m=''2791690''>that</span> <span m=''2791940''>mixes</span>
  <span m=''2792290''>up</span> <span m=''2792440''>the</span> <span m=''2793220''>generation</span>
  <span m=''2793780''>and</span> <span m=''2793860''>the</span> <span m=''2793950''>test.</span>
  </p><p><span m=''2796310''>Well,</span> <span m=''2796440''>that</span> <span m=''2797900''>sounds</span>
  <span m=''2798120''>pretty</span> <span m=''2798320''>magic.</span> <span m=''2800770''>The</span>
  <span m=''2801120''>key</span> <span m=''2801340''>to</span> <span m=''2801440''>this</span>
  <span m=''2802050''>is</span> <span m=''2802210''>that</span> <span m=''2802370''>streams</span>
  <span m=''2802770''>are</span> <span m=''2802980''>not</span> <span m=''2803250''>lists.</span>
  <span m=''2808090''>We''ll</span> <span m=''2808260''>see this</span> <span m=''2808450''>carefully</span>
  <span m=''2808820''>in</span> <span m=''2808880''>a</span> <span m=''2808920''>second,</span>
  <span m=''2809230''>but</span> <span m=''2809380''>for</span> <span m=''2809500''>now,</span>
  <span m=''2809890''>let''s</span> <span m=''2810070''>take</span> <span m=''2810250''>a</span>
  <span m=''2810300''>look</span> <span m=''2810480''>at</span> <span m=''2810540''>that</span>
  <span m=''2811130''>slide</span> <span m=''2811450''>again.</span> <span m=''2812115''>The</span>
  <span m=''2812580''>image</span> <span m=''2812960''>you</span> <span m=''2813050''>should</span>
  <span m=''2813230''>have</span> <span m=''2813500''>here</span> <span m=''2813950''>of</span>
  <span m=''2814070''>this</span> <span m=''2814200''>signal</span> <span m=''2814540''>processing</span>
  <span m=''2815060''>system</span> <span m=''2817400''>is</span> <span m=''2817560''>that</span>
  <span m=''2817710''>what''s</span> <span m=''2817930''>going</span> <span m=''2817990''>to</span>
  <span m=''2818050''>happen</span> <span m=''2819200''>is</span> <span m=''2819790''>there''s</span>
  <span m=''2820190''>this</span> <span m=''2820360''>box</span> <span m=''2820940''>that</span>
  <span m=''2821410''>has</span> <span m=''2821620''>the</span> <span m=''2821770''>integers</span>
  <span m=''2822910''>sitting</span> <span m=''2823300''>in</span> <span m=''2823420''>it.</span>
  <span m=''2825360''>And</span> <span m=''2825530''>there''s</span> <span m=''2825700''>this</span>
  <span m=''2825930''>filter</span> <span m=''2827480''>that''s</span> <span m=''2827720''>connected</span>
  <span m=''2828130''>to</span> <span m=''2828300''>it</span> <span m=''2828380''>and</span>
  <span m=''2828530''>it''s</span> <span m=''2828680''>tugging</span> <span m=''2829030''>on</span>
  <span m=''2829180''>them.</span> <span m=''2830940''>And</span> <span m=''2831110''>then</span>
  <span m=''2831270''>there''s</span> <span m=''2831440''>someone</span> <span m=''2831950''>who''s</span>
  <span m=''2832290''>tugging</span> <span m=''2832650''>on</span> <span m=''2832800''>this</span>
  <span m=''2832930''>stuff</span> <span m=''2833360''>saying</span> <span m=''2833680''>what</span>
  <span m=''2833870''>comes</span> <span m=''2834120''>out</span> <span m=''2834240''>of</span>
  <span m=''2834360''>the</span> <span m=''2834450''>filter.</span> </p><p><span m=''2836790''>And</span>
  <span m=''2836930''>the</span> <span m=''2837030''>image</span> <span m=''2837310''>you</span>
  <span m=''2837380''>should</span> <span m=''2837550''>have</span> <span m=''2838210''>is</span>
  <span m=''2838430''>that</span> <span m=''2838950''>someone</span> <span m=''2839310''>says,</span>
  <span m=''2839520''>well,</span> <span m=''2839630''>what''s</span> <span m=''2839860''>the</span>
  <span m=''2839940''>first</span> <span m=''2840260''>prime,</span> <span m=''2842690''>and</span>
  <span m=''2843070''>tugs</span> <span m=''2843390''>on</span> <span m=''2843520''>this</span>
  <span m=''2843710''>filter.</span> <span m=''2844590''>And</span> <span m=''2844710''>the</span>
  <span m=''2844830''>filter</span> <span m=''2845140''>tugs</span> <span m=''2845460''>on</span>
  <span m=''2845590''>the</span> <span m=''2845720''>integers.</span> <span m=''2848020''>And</span>
  <span m=''2848230''>you</span> <span m=''2848350''>look</span> <span m=''2848490''>only</span>
  <span m=''2848750''>at that</span> <span m=''2849020''>much,</span> <span m=''2849210''>and</span>
  <span m=''2849310''>then</span> <span m=''2849430''>say,</span> <span m=''2849610''>oh,</span>
  <span m=''2849760''>I</span> <span m=''2849830''>really</span> <span m=''2850070''>wanted</span>
  <span m=''2850270''>the</span> <span m=''2850330''>second</span> <span m=''2850640''>one.</span>
  <span m=''2850930''>What''s</span> <span m=''2851160''>the</span> <span m=''2851240''>second</span>
  <span m=''2851600''>prime?</span> <span m=''2853710''>And</span> <span m=''2853870''>that</span>
  <span m=''2855490''>no</span> <span m=''2855620''>computation</span> <span m=''2856200''>gets</span>
  <span m=''2856400''>done</span> <span m=''2856830''>except</span> <span m=''2857140''>when</span>
  <span m=''2857240''>you</span> <span m=''2857340''>tug</span> <span m=''2857580''>on</span>
  <span m=''2857730''>these</span> <span m=''2857930''>things.</span> </p><p><span
  m=''2860500''>Let</span> <span m=''2860580''>me</span> <span m=''2860660''>try</span>
  <span m=''2860830''>that</span> <span m=''2861010''>again.</span> <span m=''2861410''>This</span>
  <span m=''2861630''>is</span> <span m=''2861740''>a</span> <span m=''2861830''>little</span>
  <span m=''2863560''>device.</span> <span m=''2863815''>This is a</span> <span m=''2864070''>little</span>
  <span m=''2864240''>stream</span> <span m=''2864590''>machine</span> <span m=''2865560''>invented</span>
  <span m=''2865990''>by</span> <span m=''2866140''>Eric</span> <span m=''2866400''>Grimson</span>
  <span m=''2867300''>who''s</span> <span m=''2867760''>been</span> <span m=''2867950''>teaching</span>
  <span m=''2868220''>this</span> <span m=''2868370''>course</span> <span m=''2868620''>at</span>
  <span m=''2868690''>MIT.</span> <span m=''2869830''>And</span> <span m=''2870030''>the</span>
  <span m=''2870220''>image is</span> <span m=''2870590''>here''s</span> <span m=''2870820''>a</span>
  <span m=''2871820''>stream</span> <span m=''2872170''>of</span> <span m=''2872250''>stuff,</span>
  <span m=''2872580''>like</span> <span m=''2872740''>a</span> <span m=''2872790''>whole</span>
  <span m=''2872940''>bunch</span> <span m=''2873180''>of</span> <span m=''2873260''>the</span>
  <span m=''2873570''>integers.</span> <span m=''2874780''>And</span> <span m=''2875030''>here''s</span>
  <span m=''2875240''>some</span> <span m=''2875370''>processing</span> <span m=''2875920''>elements.</span>
  <span m=''2878700''>And</span> <span m=''2878870''>if,</span> <span m=''2879180''>say,</span>
  <span m=''2879430''>it''s</span> <span m=''2881300''>filter</span> <span m=''2881690''>of</span>
  <span m=''2881770''>filter</span> <span m=''2882150''>of map, or</span> <span m=''2882240''>something.</span>
  </p><p><span m=''2885570''>And</span> <span m=''2886070''>if</span> <span m=''2886200''>I</span>
  <span m=''2886270''>really</span> <span m=''2886860''>tried</span> <span m=''2887090''>to</span>
  <span m=''2887210''>implement</span> <span m=''2887670''>that</span> <span m=''2888150''>with</span>
  <span m=''2888290''>streams</span> <span m=''2888640''>as</span> <span m=''2888760''>lists,</span>
  <span m=''2889300''>what</span> <span m=''2889390''>I''d</span> <span m=''2889490''>say</span>
  <span m=''2889690''>is,</span> <span m=''2889770''>well,</span> <span m=''2889920''>I''ve</span>
  <span m=''2890030''>got</span> <span m=''2890220''>this</span> <span m=''2890610''>list</span>
  <span m=''2890860''>of</span> <span m=''2890950''>things,</span> <span m=''2891520''>and</span>
  <span m=''2891600''>now</span> <span m=''2891740''>I</span> <span m=''2891810''>do</span>
  <span m=''2891960''>the</span> <span m=''2892160''>first</span> <span m=''2892370''>filter.</span>
  <span m=''2892670''>So</span> <span m=''2893130''>do</span> <span m=''2893300''>all</span>
  <span m=''2893470''>this</span> <span m=''2893650''>processing.</span> <span m=''2894070''>And</span>
  <span m=''2894780''>I</span> <span m=''2895100''>take</span> <span m=''2895340''>this</span>
  <span m=''2895570''>and I</span> <span m=''2896740''>process</span> <span m=''2897000''>and</span>
  <span m=''2897260''>I</span> <span m=''2897390''>process</span> <span m=''2897880''>and</span>
  <span m=''2897980''>I</span> <span m=''2898050''>process</span> <span m=''2898570''>and
  I</span> <span m=''2898710''>process.</span> <span m=''2899610''>And</span> <span
  m=''2899870''>now I''m</span> <span m=''2899960''>got</span> <span m=''2900160''>this</span>
  <span m=''2900330''>new</span> <span m=''2900510''>stream.</span> <span m=''2901910''>Now</span>
  <span m=''2902010''>I</span> <span m=''2902080''>take</span> <span m=''2902330''>that</span>
  <span m=''2902530''>result</span> <span m=''2902910''>in</span> <span m=''2902970''>my</span>
  <span m=''2903100''>hand</span> <span m=''2903620''>someplace.</span> <span m=''2904070''>And
  I</span> <span m=''2904150''>put</span> <span m=''2904330''>that</span> <span m=''2904500''>through</span>
  <span m=''2904610''>the</span> <span m=''2904680''>second</span> <span m=''2905000''>one.</span>
  <span m=''2905260''>And</span> <span m=''2905620''>I</span> <span m=''2905770''>process</span>
  <span m=''2906240''>the</span> <span m=''2906320''>whole</span> <span m=''2906510''>thing.</span>
  <span m=''2908110''>And</span> <span m=''2908590''>there''s</span> <span m=''2908760''>this</span>
  <span m=''2908930''>new</span> <span m=''2909090''>stream.</span> <span m=''2912130''>And
  then</span> <span m=''2912500''>I</span> <span m=''2912560''>take</span> <span m=''2912800''>the</span>
  <span m=''2912880''>result</span> <span m=''2914250''>and</span> <span m=''2914380''>I</span>
  <span m=''2914500''>put</span> <span m=''2914720''>it all</span> <span m=''2914830''>the</span>
  <span m=''2914940''>way</span> <span m=''2915070''>through</span> <span m=''2915230''>this</span>
  <span m=''2915450''>one</span> <span m=''2915600''>the</span> <span m=''2915660''>same</span>
  <span m=''2915940''>way.</span> </p><p><span m=''2916360''>That''s</span> <span
  m=''2918860''>what</span> <span m=''2919090''>would</span> <span m=''2919240''>happen</span>
  <span m=''2919870''>to</span> <span m=''2919990''>these</span> <span m=''2920110''>stream</span>
  <span m=''2920420''>programs</span> <span m=''2921395''>if</span> <span m=''2921760''>streams</span>
  <span m=''2922230''>were</span> <span m=''2922330''>just</span> <span m=''2922610''>lists.</span>
  <span m=''2923860''>But</span> <span m=''2924000''>in</span> <span m=''2924270''>fact,</span>
  <span m=''2924540''>streams</span> <span m=''2924780''>aren''t lists, they''re</span>
  <span m=''2925170''>streams.</span> <span m=''2926010''>And the</span> <span m=''2926120''>image</span>
  <span m=''2926340''>you</span> <span m=''2926400''>should</span> <span m=''2926560''>have</span>
  <span m=''2926660''>is</span> <span m=''2926770''>something</span> <span m=''2927090''>a
  little</span> <span m=''2927240''>bit</span> <span m=''2927390''>more</span> <span
  m=''2927520''>like</span> <span m=''2927740''>this.</span> <span m=''2930230''>I''ve</span>
  <span m=''2930370''>got</span> <span m=''2930610''>these</span> <span m=''2931350''>gadgets</span>
  <span m=''2931810''>connected</span> <span m=''2932250''>up</span> <span m=''2935270''>by</span>
  <span m=''2935400''>this</span> <span m=''2935590''>data</span> <span m=''2935880''>that''s</span>
  <span m=''2936080''>flowing</span> <span m=''2936400''>out</span> <span m=''2936510''>of</span>
  <span m=''2936610''>them.</span> <span m=''2939960''>And</span> <span m=''2940510''>here''s</span>
  <span m=''2940700''>my</span> <span m=''2940820''>original</span> <span m=''2941400''>source</span>
  <span m=''2941780''>of</span> <span m=''2941860''>the</span> <span m=''2941930''>streams.</span>
  <span m=''2942370''>It</span> <span m=''2942450''>might</span> <span m=''2942650''>be</span>
  <span m=''2944190''>starting</span> <span m=''2944600''>to</span> <span m=''2944690''>generate</span>
  <span m=''2945100''>the</span> <span m=''2945250''>integers.</span> </p><p><span
  m=''2945980''>And</span> <span m=''2946140''>now,</span> <span m=''2946240''>what</span>
  <span m=''2946350''>happens</span> <span m=''2946630''>if</span> <span m=''2946750''>I</span>
  <span m=''2946860''>want</span> <span m=''2946970''>a</span> <span m=''2947010''>result?</span>
  <span m=''2947580''>I</span> <span m=''2947950''>tug</span> <span m=''2948180''>on</span>
  <span m=''2948290''>the</span> <span m=''2948440''>end</span> <span m=''2948590''>here.</span>
  <span m=''2950200''>And</span> <span m=''2950380''>this</span> <span m=''2950520''>element</span>
  <span m=''2950890''>says,</span> <span m=''2951090''>gee,</span> <span m=''2951230''>I</span>
  <span m=''2951310''>need</span> <span m=''2951510''>some</span> <span m=''2951650''>more</span>
  <span m=''2951800''>data.</span> <span m=''2953090''>So</span> <span m=''2953630''>this</span>
  <span m=''2954080''>one</span> <span m=''2954220''>comes</span> <span m=''2954470''>here</span>
  <span m=''2954630''>and</span> <span m=''2954720''>tugs</span> <span m=''2954970''>on</span>
  <span m=''2955110''>that</span> <span m=''2955350''>one.</span> <span m=''2955830''>And
  it</span> <span m=''2956120''>says,</span> <span m=''2956280''>gee,</span> <span
  m=''2956410''>I</span> <span m=''2956470''>need</span> <span m=''2956660''>some</span>
  <span m=''2956790''>more</span> <span m=''2956930''>data.</span> <span m=''2957890''>And</span>
  <span m=''2958070''>this</span> <span m=''2958190''>one</span> <span m=''2958320''>tugs</span>
  <span m=''2958570''>on</span> <span m=''2958710''>this</span> <span m=''2959190''>thing,</span>
  <span m=''2959460''>which</span> <span m=''2959630''>might</span> <span m=''2959810''>be
  a</span> <span m=''2959960''>filter, and</span> <span m=''2960330''>says,</span>
  <span m=''2960490''>gee,</span> <span m=''2960610''>I need some</span> <span m=''2960860''>more</span>
  <span m=''2961020''>data.</span> <span m=''2961640''>And</span> <span m=''2961790''>only</span>
  <span m=''2962400''>as</span> <span m=''2962580''>much</span> <span m=''2962840''>of</span>
  <span m=''2962960''>this</span> <span m=''2963480''>thing</span> <span m=''2963720''>at</span>
  <span m=''2963800''>the</span> <span m=''2963950''>end</span> <span m=''2964090''>here</span>
  <span m=''2964260''>gets</span> <span m=''2964470''>generated</span> <span m=''2964755''>as</span>
  <span m=''2965040''>I</span> <span m=''2965120''>tugged.</span> <span m=''2965780''>And</span>
  <span m=''2965950''>only</span> <span m=''2966310''>as</span> <span m=''2966400''>much</span>
  <span m=''2966620''>of</span> <span m=''2966710''>this</span> <span m=''2966840''>stuff</span>
  <span m=''2967060''>goes</span> <span m=''2967320''>through</span> <span m=''2967430''>the</span>
  <span m=''2967520''>processing</span> <span m=''2968030''>units</span> <span m=''2968600''>as</span>
  <span m=''2968760''>I''m</span> <span m=''2968870''>pulling</span> <span m=''2969170''>on</span>
  <span m=''2969280''>the</span> <span m=''2969410''>end</span> <span m=''2969570''>I
  need.</span> <span m=''2970760''>That''s</span> <span m=''2971110''>the</span> <span
  m=''2971220''>image</span> <span m=''2971560''>you</span> <span m=''2971640''>should</span>
  <span m=''2971810''>have</span> <span m=''2972810''>of</span> <span m=''2972970''>the</span>
  <span m=''2973060''>difference</span> <span m=''2973430''>between</span> <span m=''2973720''>implementing</span>
  <span m=''2974770''>what</span> <span m=''2974900''>we''re</span> <span m=''2975010''>actually</span>
  <span m=''2975430''>going</span> <span m=''2975530''>to</span> <span m=''2975630''>do</span>
  <span m=''2976210''>and</span> <span m=''2976410''>if</span> <span m=''2976580''>streams</span>
  <span m=''2976970''>were</span> <span m=''2977070''>lists.</span> </p><p><span m=''2980600''>Well,</span>
  <span m=''2980945''>how do</span> <span m=''2981290''>we</span> <span m=''2981440''>make</span>
  <span m=''2981680''>this</span> <span m=''2981890''>thing?</span> <span m=''2982430''>I</span>
  <span m=''2982460''>hope</span> <span m=''2982610''>you</span> <span m=''2982680''>have</span>
  <span m=''2982810''>the</span> <span m=''2982930''>image.</span> <span m=''2983400''>The</span>
  <span m=''2983620''>trick</span> <span m=''2983810''>is</span> <span m=''2983920''>how</span>
  <span m=''2984030''>to</span> <span m=''2984130''>make</span> <span m=''2984450''>it.</span>
  <span m=''2987930''>We</span> <span m=''2988010''>want</span> <span m=''2988160''>to</span>
  <span m=''2988250''>arrange</span> <span m=''2989530''>for</span> <span m=''2989760''>a</span>
  <span m=''2989800''>stream</span> <span m=''2990420''>to</span> <span m=''2990550''>be</span>
  <span m=''2990690''>a</span> <span m=''2990730''>data</span> <span m=''2991040''>structure</span>
  <span m=''2992080''>that</span> <span m=''2992540''>computes</span> <span m=''2993030''>itself</span>
  <span m=''2993530''>incrementally,</span> <span m=''2994210''>an</span> <span m=''2994500''>on-demand</span>
  <span m=''2995670''>data</span> <span m=''2995900''>structure.</span> <span m=''2999220''>And</span>
  <span m=''2999480''>the</span> <span m=''2999550''>basic</span> <span m=''3000010''>idea</span>
  <span m=''3001030''>is,</span> <span m=''3001170''>again,</span> <span m=''3001370''>one</span>
  <span m=''3001530''>of</span> <span m=''3001580''>the</span> <span m=''3001670''>very</span>
  <span m=''3001940''>basic</span> <span m=''3002320''>ideas</span> <span m=''3002700''>that</span>
  <span m=''3002840''>we''re</span> <span m=''3002940''>seeing</span> <span m=''3003210''>throughout</span>
  <span m=''3003490''>the</span> <span m=''3003560''>whole</span> <span m=''3003760''>course.</span>
  <span m=''3004490''>And</span> <span m=''3004660''>that</span> <span m=''3004830''>is</span>
  <span m=''3005150''>that</span> <span m=''3005730''>there''s</span> <span m=''3005920''>not</span>
  <span m=''3006230''>a</span> <span m=''3006310''>firm</span> <span m=''3006620''>distinction</span>
  <span m=''3007100''>between</span> <span m=''3007440''>programs</span> <span m=''3007960''>and</span>
  <span m=''3008080''>data.</span> </p><p><span m=''3009240''>So</span> <span m=''3009470''>what
  a</span> <span m=''3009560''>stream</span> <span m=''3009940''>is</span> <span m=''3010050''>going</span>
  <span m=''3010210''>to</span> <span m=''3010370''>be</span> <span m=''3010670''>is</span>
  <span m=''3010830''>simultaneously</span> <span m=''3011850''>this</span> <span
  m=''3012020''>data</span> <span m=''3012260''>structure</span> <span m=''3012660''>that</span>
  <span m=''3012800''>you</span> <span m=''3012910''>think</span> <span m=''3013150''>of,</span>
  <span m=''3013280''>like</span> <span m=''3014500''>the</span> <span m=''3014580''>stream</span>
  <span m=''3014880''>of</span> <span m=''3014940''>the</span> <span m=''3015020''>leaves</span>
  <span m=''3015270''>of</span> <span m=''3015390''>this</span> <span m=''3015510''>tree.</span>
  <span m=''3016810''>But</span> <span m=''3017090''>at</span> <span m=''3017160''>the</span>
  <span m=''3017230''>same</span> <span m=''3017560''>time,</span> <span m=''3017910''>it''s</span>
  <span m=''3018040''>going</span> <span m=''3018140''>to</span> <span m=''3018250''>be
  a</span> <span m=''3018350''>very</span> <span m=''3018600''>clever</span> <span
  m=''3018880''>procedure</span> <span m=''3020160''>that</span> <span m=''3020450''>has</span>
  <span m=''3020810''>the method</span> <span m=''3021400''>of</span> <span m=''3021500''>computing</span>
  <span m=''3021980''>in it.</span> <span m=''3023550''>Well,</span> <span m=''3024986''>let</span>
  <span m=''3025360''>me</span> <span m=''3025640''>try</span> <span m=''3025760''>this.</span>
  <span m=''3025930''>It''s</span> <span m=''3026070''>going</span> <span m=''3026140''>to</span>
  <span m=''3026210''>turn</span> <span m=''3026460''>out</span> <span m=''3026780''>that</span>
  <span m=''3026980''>we</span> <span m=''3027070''>don''t</span> <span m=''3027250''>need</span>
  <span m=''3027420''>any</span> <span m=''3027580''>more</span> <span m=''3027750''>mechanism.</span>
  <span m=''3028460''>We</span> <span m=''3028570''>already</span> <span m=''3028810''>have</span>
  <span m=''3028950''>everything</span> <span m=''3029400''>we</span> <span m=''3029520''>need</span>
  <span m=''3030120''>simply</span> <span m=''3030510''>from</span> <span m=''3030620''>the</span>
  <span m=''3030730''>fact</span> <span m=''3031040''>that</span> <span m=''3031150''>we</span>
  <span m=''3031250''>know</span> <span m=''3031410''>how</span> <span m=''3031490''>to</span>
  <span m=''3031570''>handle</span> <span m=''3031890''>procedures</span> <span m=''3032770''>as</span>
  <span m=''3032960''>first-class</span> <span m=''3033440''>objects.</span> </p><p><span
  m=''3035460''>Well,</span> <span m=''3036050''>let''s</span> <span m=''3036160''>go</span>
  <span m=''3036240''>back</span> <span m=''3036510''>to the</span> <span m=''3036590''>key.</span>
  <span m=''3036880''>The</span> <span m=''3037120''>key</span> <span m=''3037340''>is,</span>
  <span m=''3037680''>remember,</span> <span m=''3037950''>we</span> <span m=''3038040''>had</span>
  <span m=''3038180''>these</span> <span m=''3038330''>operations.</span> <span m=''3039030''>CONS-stream</span>
  <span m=''3043970''>and</span> <span m=''3044390''>head</span> <span m=''3046650''>and</span>
  <span m=''3047100''>tail.</span> <span m=''3048080''>When</span> <span m=''3048350''>I</span>
  <span m=''3048410''>started,</span> <span m=''3048810''>I</span> <span m=''3048890''>said</span>
  <span m=''3049940''>you</span> <span m=''3050060''>can</span> <span m=''3050210''>think</span>
  <span m=''3050480''>about</span> <span m=''3050750''>this</span> <span m=''3050930''>as</span>
  <span m=''3051050''>CONS</span> <span m=''3051315''>and</span> <span m=''3051580''>think</span>
  <span m=''3051760''>about</span> <span m=''3052010''>this</span> <span m=''3052200''>as</span>
  <span m=''3052330''>CAR</span> <span m=''3052590''>and</span> <span m=''3052680''>think</span>
  <span m=''3052840''>about</span> <span m=''3053060''>that</span> <span m=''3053210''>as</span>
  <span m=''3053340''>CDR,</span> <span m=''3053550''>but</span> <span m=''3053680''>it''s</span>
  <span m=''3053830''>not.</span> <span m=''3055080''>Now,</span> <span m=''3055280''>let''s</span>
  <span m=''3055400''>look at</span> <span m=''3055520''>what</span> <span m=''3055680''>they</span>
  <span m=''3055780''>really</span> <span m=''3056250''>are.</span> </p><p><span m=''3057550''>Well,</span>
  <span m=''3058050''>CONS-stream</span> <span m=''3064760''>of</span> <span m=''3064960''>x</span>
  <span m=''3065220''>and</span> <span m=''3065350''>y</span> <span m=''3067520''>is</span>
  <span m=''3067690''>going</span> <span m=''3067790''>to</span> <span m=''3067890''>be</span>
  <span m=''3068270''>an</span> <span m=''3068430''>abbreviation</span> <span m=''3069360''>for</span>
  <span m=''3076830''>the</span> <span m=''3076930''>following</span> <span m=''3077430''>thing.</span>
  <span m=''3079540''>CONS</span> <span m=''3080500''>form</span> <span m=''3080790''>a
  pair,</span> <span m=''3081160''>ordinary</span> <span m=''3081510''>CONS,</span>
  <span m=''3082260''>of</span> <span m=''3082530''>x</span> <span m=''3083770''>to</span>
  <span m=''3083900''>a</span> <span m=''3083960''>thing</span> <span m=''3084160''>called</span>
  <span m=''3084470''>delay</span> <span m=''3087630''>of</span> <span m=''3087740''>y.</span>
  <span m=''3091188''>And</span> <span m=''3091680''>before</span> <span m=''3092060''>I</span>
  <span m=''3092100''>explain</span> <span m=''3092500''>that,</span> <span m=''3092630''>let</span>
  <span m=''3092700''>me</span> <span m=''3092780''>go and</span> <span m=''3092980''>write</span>
  <span m=''3093170''>the</span> <span m=''3093250''>rest.</span> <span m=''3094390''>The</span>
  <span m=''3094670''>head</span> <span m=''3094900''>of</span> <span m=''3094950''>a</span>
  <span m=''3095030''>stream</span> <span m=''3098170''>is</span> <span m=''3098330''>going</span>
  <span m=''3098420''>to</span> <span m=''3098510''>be</span> <span m=''3099000''>just</span>
  <span m=''3099230''>the</span> <span m=''3099300''>CAR.</span> <span m=''3102380''>And</span>
  <span m=''3102960''>the</span> <span m=''3103350''>tail</span> <span m=''3103660''>of</span>
  <span m=''3103740''>a</span> <span m=''3103780''>stream</span> <span m=''3106570''>is</span>
  <span m=''3106850''>going</span> <span m=''3106950''>to</span> <span m=''3107060''>be</span>
  <span m=''3107160''>a</span> <span m=''3107210''>thing called</span> <span m=''3107610''>force</span>
  <span m=''3111610''>the</span> <span m=''3112080''>CDR</span> <span m=''3113960''>of</span>
  <span m=''3114120''>the</span> <span m=''3114190''>stream.</span> </p><p><span m=''3116120''>Now
  let me</span> <span m=''3116210''>explain</span> <span m=''3116550''>this.</span>
  <span m=''3118060''>Delay</span> <span m=''3118390''>is</span> <span m=''3118520''>going</span>
  <span m=''3118590''>to</span> <span m=''3118670''>be</span> <span m=''3118780''>a</span>
  <span m=''3118830''>special</span> <span m=''3119210''>magic</span> <span m=''3119600''>thing.</span>
  <span m=''3121420''>What</span> <span m=''3121570''>delay</span> <span m=''3122020''>does</span>
  <span m=''3123860''>is</span> <span m=''3124280''>take an</span> <span m=''3124640''>expression</span>
  <span m=''3125540''>and</span> <span m=''3125710''>produce</span> <span m=''3126130''>a</span>
  <span m=''3126240''>promise</span> <span m=''3127030''>to</span> <span m=''3127300''>compute</span>
  <span m=''3127690''>that</span> <span m=''3127850''>expression</span> <span m=''3128380''>when</span>
  <span m=''3128520''>you</span> <span m=''3128660''>ask</span> <span m=''3128880''>for</span>
  <span m=''3129070''>it.</span> <span m=''3130600''>It</span> <span m=''3130640''>doesn''t</span>
  <span m=''3130890''>do</span> <span m=''3131000''>any</span> <span m=''3131150''>computation</span>
  <span m=''3131790''>here.</span> <span m=''3131980''>It</span> <span m=''3132110''>just</span>
  <span m=''3133420''>gives</span> <span m=''3133620''>you</span> <span m=''3133730''>a</span>
  <span m=''3133790''>rain</span> <span m=''3134030''>check.</span> <span m=''3134820''>It</span>
  <span m=''3135190''>produces</span> <span m=''3135620''>a</span> <span m=''3135670''>promise.</span>
  <span m=''3137110''>And</span> <span m=''3137270''>CONS-stream</span> <span m=''3137820''>says</span>
  <span m=''3138850''>I''m</span> <span m=''3138970''>going</span> <span m=''3139050''>to</span>
  <span m=''3139120''>put</span> <span m=''3139300''>together</span> <span m=''3140700''>in</span>
  <span m=''3140830''>a</span> <span m=''3140870''>pair</span> <span m=''3141560''>x</span>
  <span m=''3143280''>and</span> <span m=''3143470''>a</span> <span m=''3143530''>promise</span>
  <span m=''3144470''>to</span> <span m=''3144650''>compute</span> <span m=''3145030''>y.</span>
  </p><p><span m=''3148230''>Now,</span> <span m=''3148330''>if</span> <span m=''3148430''>I</span>
  <span m=''3148460''>want</span> <span m=''3148640''>the</span> <span m=''3148710''>head,</span>
  <span m=''3149030''>that''s</span> <span m=''3149230''>just</span> <span m=''3149400''>the</span>
  <span m=''3149480''>CAR</span> <span m=''3149870''>that</span> <span m=''3149950''>I</span>
  <span m=''3150020''>put</span> <span m=''3150200''>in</span> <span m=''3150290''>the</span>
  <span m=''3150340''>pair.</span> <span m=''3151840''>And</span> <span m=''3151970''>the</span>
  <span m=''3152050''>key</span> <span m=''3152250''>is</span> <span m=''3152340''>that</span>
  <span m=''3152470''>the</span> <span m=''3152610''>tail</span> <span m=''3153060''>is</span>
  <span m=''3153200''>going</span> <span m=''3153300''>to</span> <span m=''3153390''>be--</span>
  <span m=''3154350''>force</span> <span m=''3155560''>calls</span> <span m=''3155940''>in</span>
  <span m=''3156050''>that</span> <span m=''3156230''>promise.</span> <span m=''3159110''>Tail</span>
  <span m=''3159480''>says,</span> <span m=''3159630''>well,</span> <span m=''3159980''>take</span>
  <span m=''3160330''>that</span> <span m=''3160540''>promise</span> <span m=''3161830''>and</span>
  <span m=''3162020''>now</span> <span m=''3163690''>call in</span> <span m=''3164050''>that</span>
  <span m=''3164110''>promise.</span> <span m=''3164610''>And</span> <span m=''3164770''>then</span>
  <span m=''3164860''>we</span> <span m=''3165090''>compute</span> <span m=''3165480''>that</span>
  <span m=''3165720''>thing.</span> <span m=''3167430''>That''s</span> <span m=''3168080''>how</span>
  <span m=''3168180''>this</span> <span m=''3168360''>is</span> <span m=''3168440''>going</span>
  <span m=''3168510''>to</span> <span m=''3168590''>work.</span> <span m=''3168740''>That''s</span>
  <span m=''3168940''>what</span> <span m=''3169540''>CONS-stream,</span> <span m=''3170420''>head,</span>
  <span m=''3170610''>and</span> <span m=''3170720''>tail</span> <span m=''3170980''>really</span>
  <span m=''3171290''>are.</span> </p><p><span m=''3174196''>Now,</span> <span m=''3174640''>let''s</span>
  <span m=''3174930''>see</span> <span m=''3175040''>how</span> <span m=''3175130''>this</span>
  <span m=''3175310''>works.</span> <span m=''3175570''>And we''ll</span> <span m=''3175830''>go</span>
  <span m=''3175990''>through</span> <span m=''3176130''>this</span> <span m=''3176330''>fairly</span>
  <span m=''3176570''>carefully.</span> <span m=''3178410''>We''re</span> <span m=''3178810''>going
  to</span> <span m=''3178940''>see</span> <span m=''3179090''>how</span> <span m=''3179170''>this</span>
  <span m=''3179330''>works</span> <span m=''3179610''>in</span> <span m=''3180100''>this</span>
  <span m=''3181390''>example</span> <span m=''3181900''>of</span> <span m=''3181990''>computing</span>
  <span m=''3182520''>the</span> <span m=''3182750''>second</span> <span m=''3183220''>prime</span>
  <span m=''3185630''>between</span> <span m=''3186050''>10,000</span> <span m=''3186640''>and</span>
  <span m=''3186700''>a</span> <span m=''3186760''>million.</span> <span m=''3188650''>OK,</span>
  <span m=''3188910''>so</span> <span m=''3189030''>we</span> <span m=''3189360''>start</span>
  <span m=''3189700''>off</span> <span m=''3190600''>and</span> <span m=''3190840''>we</span>
  <span m=''3190940''>have</span> <span m=''3191140''>this</span> <span m=''3191310''>expression.</span>
  <span m=''3195820''>The</span> <span m=''3196070''>second</span> <span m=''3196390''>prime--</span>
  <span m=''3196590''>the</span> <span m=''3196680''>head</span> <span m=''3196900''>of</span>
  <span m=''3196990''>the</span> <span m=''3197070''>tail</span> <span m=''3198380''>of</span>
  <span m=''3199620''>the</span> <span m=''3199920''>result</span> <span m=''3200290''>of</span>
  <span m=''3200380''>filtering</span> <span m=''3200950''>for</span> <span m=''3201120''>primality</span>
  <span m=''3202365''>the</span> <span m=''3202830''>integers</span> <span m=''3203470''>between</span>
  <span m=''3204060''>10,000</span> <span m=''3204350''>and</span> <span m=''3204585''>1</span>
  <span m=''3204820''>million.</span> </p><p><span m=''3206710''>Now,</span> <span
  m=''3206840''>what</span> <span m=''3207030''>is</span> <span m=''3207310''>that?</span>
  <span m=''3208400''>What</span> <span m=''3208580''>that</span> <span m=''3208750''>is,</span>
  <span m=''3212050''>that</span> <span m=''3212230''>interval</span> <span m=''3212690''>between</span>
  <span m=''3213000''>10,000</span> <span m=''3213190''>and</span> <span m=''3213670''>1
  million,</span> <span m=''3215790''>well,</span> <span m=''3215910''>if</span> <span
  m=''3215990''>you</span> <span m=''3216080''>trace</span> <span m=''3216430''>through</span>
  <span m=''3216520''>enumerate</span> <span m=''3216970''>interval,</span> <span
  m=''3217350''>there</span> <span m=''3217480''>builds</span> <span m=''3217810''>a</span>
  <span m=''3217870''>CONS-stream.</span> <span m=''3220250''>And the</span> <span
  m=''3220530''>CONS-stream</span> <span m=''3221190''>is</span> <span m=''3221500''>the</span>
  <span m=''3222060''>CONS</span> <span m=''3222580''>of</span> <span m=''3222720''>10,000</span>
  <span m=''3224530''>to</span> <span m=''3224690''>a</span> <span m=''3224750''>promise</span>
  <span m=''3225590''>to</span> <span m=''3225880''>compute</span> <span m=''3226390''>the</span>
  <span m=''3226650''>integers</span> <span m=''3227190''>between</span> <span m=''3227510''>10,001</span>
  <span m=''3228420''>and</span> <span m=''3228520''>1</span> <span m=''3228560''>million.</span>
  </p><p><span m=''3234480''>So</span> <span m=''3234630''>that''s</span> <span m=''3234850''>what</span>
  <span m=''3234950''>this</span> <span m=''3235110''>expression</span> <span m=''3235630''>is.</span>
  <span m=''3235750''>Here</span> <span m=''3235920''>I''m</span> <span m=''3236210''>using
  the</span> <span m=''3236270''>substitution</span> <span m=''3236950''>model.</span>
  <span m=''3237640''>And</span> <span m=''3237760''>we</span> <span m=''3237890''>can</span>
  <span m=''3238190''>use</span> <span m=''3238370''>the</span> <span m=''3238440''>substitution</span>
  <span m=''3239080''>model</span> <span m=''3239330''>because</span> <span m=''3239600''>we</span>
  <span m=''3239690''>don''t</span> <span m=''3239870''>have</span> <span m=''3240030''>side</span>
  <span m=''3240300''>effects</span> <span m=''3240590''>and</span> <span m=''3240700''>state.</span>
  <span m=''3244270''>So</span> <span m=''3244490''>I</span> <span m=''3244570''>have</span>
  <span m=''3244750''>CONS</span> <span m=''3245490''>of</span> <span m=''3245670''>10,000</span>
  <span m=''3246420''>to</span> <span m=''3246600''>a</span> <span m=''3246650''>promise</span>
  <span m=''3247090''>to</span> <span m=''3247200''>compute</span> <span m=''3247490''>the</span>
  <span m=''3247570''>rest</span> <span m=''3247810''>of</span> <span m=''3247860''>the</span>
  <span m=''3247950''>integers.</span> <span m=''3248380''>So only</span> <span m=''3248640''>one</span>
  <span m=''3248900''>integer,</span> <span m=''3249240''>so</span> <span m=''3249400''>far,</span>
  <span m=''3249570''>got</span> <span m=''3249750''>enumerated.</span> </p><p><span
  m=''3254380''>Well,</span> <span m=''3254720''>I''m</span> <span m=''3254760''>going
  to</span> <span m=''3254920''>filter</span> <span m=''3255270''>that</span> <span
  m=''3255680''>thing</span> <span m=''3256090''>for</span> <span m=''3256230''>primality.</span>
  <span m=''3259900''>Again,</span> <span m=''3260240''>you</span> <span m=''3260340''>go</span>
  <span m=''3260460''>back</span> <span m=''3260670''>and</span> <span m=''3260850''>look</span>
  <span m=''3260970''>at</span> <span m=''3261080''>the</span> <span m=''3261160''>filter</span>
  <span m=''3261500''>code.</span> <span m=''3262360''>What</span> <span m=''3262510''>the</span>
  <span m=''3262590''>filter</span> <span m=''3262920''>will</span> <span m=''3263090''>first</span>
  <span m=''3263420''>do</span> <span m=''3263530''>is</span> <span m=''3263650''>test
  the</span> <span m=''3263970''>head.</span> <span m=''3265460''>So</span> <span
  m=''3265630''>in</span> <span m=''3265720''>this</span> <span m=''3265820''>case,</span>
  <span m=''3266020''>the</span> <span m=''3266090''>filter</span> <span m=''3267100''>will</span>
  <span m=''3267270''>test</span> <span m=''3267560''>10,000</span> <span m=''3270320''>and</span>
  <span m=''3270520''>say,</span> <span m=''3271410''>oh,</span> <span m=''3271580''>10,000''s</span>
  <span m=''3272250''>not</span> <span m=''3272480''>prime.</span> <span m=''3273500''>Therefore,</span>
  <span m=''3274390''>what</span> <span m=''3274570''>I</span> <span m=''3274700''>have</span>
  <span m=''3274820''>to</span> <span m=''3274950''>do</span> <span m=''3275130''>recursively</span>
  <span m=''3276260''>is</span> <span m=''3276490''>filter</span> <span m=''3276760''>the</span>
  <span m=''3276890''>tail.</span> <span m=''3279220''>And</span> <span m=''3279480''>what''s</span>
  <span m=''3279670''>the</span> <span m=''3279740''>tail</span> <span m=''3280050''>of</span>
  <span m=''3280160''>it,</span> <span m=''3280210''>well,</span> <span m=''3280340''>that''s</span>
  <span m=''3280570''>the</span> <span m=''3280660''>tail</span> <span m=''3281910''>of</span>
  <span m=''3282160''>this</span> <span m=''3282550''>pair</span> <span m=''3283030''>with</span>
  <span m=''3283120''>a</span> <span m=''3283220''>promise</span> <span m=''3283600''>in
  it.</span> </p><p><span m=''3286340''>Tail</span> <span m=''3286610''>now</span>
  <span m=''3286760''>comes</span> <span m=''3287060''>in</span> <span m=''3287590''>and</span>
  <span m=''3287780''>says,</span> <span m=''3288380''>well,</span> <span m=''3288620''>I''m
  going</span> <span m=''3288680''>to</span> <span m=''3288730''>force</span> <span
  m=''3289170''>that.</span> <span m=''3289680''>I''m going</span> <span m=''3289860''>to
  force</span> <span m=''3290280''>that</span> <span m=''3290450''>promise,</span>
  <span m=''3292390''>which</span> <span m=''3292570''>means</span> <span m=''3292790''>now</span>
  <span m=''3293660''>I''m</span> <span m=''3293790''>going</span> <span m=''3293860''>to</span>
  <span m=''3293920''>compute</span> <span m=''3295240''>the</span> <span m=''3295640''>integers</span>
  <span m=''3296210''>between</span> <span m=''3296550''>10,001</span> <span m=''3297450''>and</span>
  <span m=''3297510''>1</span> <span m=''3297580''>million.</span> <span m=''3300880''>OK,</span>
  <span m=''3301150''>so</span> <span m=''3301280''>this</span> <span m=''3301470''>filter</span>
  <span m=''3301770''>now</span> <span m=''3301980''>is</span> <span m=''3302100''>looking</span>
  <span m=''3302390''>at</span> <span m=''3302480''>that.</span> <span m=''3307810''>That</span>
  <span m=''3308020''>enumerate</span> <span m=''3308470''>itself,</span> <span m=''3308920''>well,</span>
  <span m=''3309090''>now we''re</span> <span m=''3309290''>back</span> <span m=''3309530''>in</span>
  <span m=''3309600''>the</span> <span m=''3309720''>original</span> <span m=''3310100''>enumerate</span>
  <span m=''3310550''>situation.</span> <span m=''3311960''>The</span> <span m=''3312130''>enumerate</span>
  <span m=''3312660''>is</span> <span m=''3314200''>the</span> <span m=''3314330''>CONS</span>
  <span m=''3314770''>of</span> <span m=''3314840''>the</span> <span m=''3314920''>first</span>
  <span m=''3315220''>thing,</span> <span m=''3315390''>10,001,</span> <span m=''3316590''>onto</span>
  <span m=''3316920''>a</span> <span m=''3316980''>promise</span> <span m=''3317460''>to</span>
  <span m=''3317560''>compute</span> <span m=''3317890''>the</span> <span m=''3317970''>rest.</span>
  </p><p><span m=''3319740''>So</span> <span m=''3319910''>now</span> <span m=''3320090''>the</span>
  <span m=''3320180''>primality</span> <span m=''3320810''>filter</span> <span m=''3321070''>is</span>
  <span m=''3321150''>going</span> <span m=''3321220''>to</span> <span m=''3321280''>go</span>
  <span m=''3321440''>look</span> <span m=''3321610''>at</span> <span m=''3321710''>10,001.</span>
  <span m=''3323060''>It''s going to</span> <span m=''3323450''>decide</span> <span
  m=''3323730''>if</span> <span m=''3323800''>it</span> <span m=''3323880''>likes</span>
  <span m=''3324180''>that</span> <span m=''3324850''>or</span> <span m=''3324940''>not.</span>
  <span m=''3325120''>It</span> <span m=''3325200''>turns</span> <span m=''3325420''>out</span>
  <span m=''3325540''>10,001</span> <span m=''3326280''>isn''t</span> <span m=''3326560''>prime.</span>
  <span m=''3327550''>So</span> <span m=''3327760''>it''ll</span> <span m=''3327930''>force
  it</span> <span m=''3328100''>again</span> <span m=''3328530''>and</span> <span
  m=''3328680''>again</span> <span m=''3329000''>and</span> <span m=''3329150''>again.</span>
  <span m=''3332920''>And</span> <span m=''3333060''>finally,</span> <span m=''3333450''>I</span>
  <span m=''3333550''>think</span> <span m=''3333650''>the</span> <span m=''3333730''>first</span>
  <span m=''3334000''>prime</span> <span m=''3334250''>it</span> <span m=''3334320''>hits</span>
  <span m=''3334520''>is</span> <span m=''3334630''>10,009.</span> <span m=''3337100''>And</span>
  <span m=''3337230''>at</span> <span m=''3337310''>that</span> <span m=''3337520''>point,</span>
  <span m=''3337730''>it''ll</span> <span m=''3337880''>stop.</span> <span m=''3340465''>And</span>
  <span m=''3340890''>that</span> <span m=''3341080''>will</span> <span m=''3341160''>be</span>
  <span m=''3341230''>the</span> <span m=''3341320''>first</span> <span m=''3341630''>prime,</span>
  <span m=''3341910''>and</span> <span m=''3341990''>then</span> <span m=''3342060''>eventually,</span>
  <span m=''3342500''>it''ll</span> <span m=''3342710''>need the</span> <span m=''3342940''>second</span>
  <span m=''3343170''>prime.</span> <span m=''3345240''>So</span> <span m=''3345700''>at</span>
  <span m=''3345820''>that</span> <span m=''3346010''>point,</span> <span m=''3346220''>it
  will</span> <span m=''3346330''>go</span> <span m=''3346460''>again.</span> </p><p><span
  m=''3347030''>So</span> <span m=''3347180''>you</span> <span m=''3347280''>see</span>
  <span m=''3347400''>what</span> <span m=''3347530''>happens</span> <span m=''3347960''>is</span>
  <span m=''3348160''>that</span> <span m=''3348870''>no</span> <span m=''3348990''>more</span>
  <span m=''3349490''>gets</span> <span m=''3349740''>generated</span> <span m=''3351880''>than</span>
  <span m=''3352060''>you</span> <span m=''3352170''>actually</span> <span m=''3352570''>need.</span>
  <span m=''3356690''>That</span> <span m=''3356830''>enumerator</span> <span m=''3357270''>is</span>
  <span m=''3357380''>not</span> <span m=''3357600''>going</span> <span m=''3357680''>to</span>
  <span m=''3357760''>generate</span> <span m=''3358220''>any</span> <span m=''3358440''>more</span>
  <span m=''3359330''>integers</span> <span m=''3360060''>than</span> <span m=''3360310''>the</span>
  <span m=''3360400''>filter</span> <span m=''3360780''>asks</span> <span m=''3361140''>it</span>
  <span m=''3361240''>for</span> <span m=''3361490''>as</span> <span m=''3361580''>it''s</span>
  <span m=''3361730''>pulling</span> <span m=''3362000''>in</span> <span m=''3362100''>things</span>
  <span m=''3362320''>to</span> <span m=''3362410''>check</span> <span m=''3362650''>for</span>
  <span m=''3362780''>primality.</span> <span m=''3364930''>And</span> <span m=''3365000''>the</span>
  <span m=''3365080''>filter</span> <span m=''3365730''>is</span> <span m=''3365890''>not</span>
  <span m=''3366060''>going</span> <span m=''3366130''>to</span> <span m=''3366200''>generate</span>
  <span m=''3366610''>any</span> <span m=''3366770''>more</span> <span m=''3366930''>stuff</span>
  <span m=''3367150''>than</span> <span m=''3367290''>you</span> <span m=''3367520''>ask</span>
  <span m=''3367840''>it for,</span> <span m=''3368080''>which</span> <span m=''3368260''>is</span>
  <span m=''3368360''>the</span> <span m=''3368440''>head</span> <span m=''3368620''>of</span>
  <span m=''3368700''>the</span> <span m=''3368790''>tail.</span> <span m=''3371255''>You</span>
  <span m=''3371680''>see,</span> <span m=''3371860''>what''s</span> <span m=''3372010''>happened</span>
  <span m=''3372970''>is</span> <span m=''3374780''>we''ve</span> <span m=''3375610''>put</span>
  <span m=''3375880''>that</span> <span m=''3376740''>mixing</span> <span m=''3377110''>of</span>
  <span m=''3377180''>generation</span> <span m=''3377750''>and</span> <span m=''3377850''>test</span>
  <span m=''3378770''>into</span> <span m=''3379020''>what</span> <span m=''3379170''>actually</span>
  <span m=''3379620''>happens</span> <span m=''3379960''>in</span> <span m=''3380040''>the</span>
  <span m=''3380130''>computer,</span> <span m=''3381620''>even</span> <span m=''3382390''>though</span>
  <span m=''3383220''>that''s</span> <span m=''3383470''>not</span> <span m=''3383660''>apparently</span>
  <span m=''3384080''>what''s</span> <span m=''3384250''>happening</span> <span m=''3384660''>from</span>
  <span m=''3384800''>looking</span> <span m=''3385050''>at</span> <span m=''3385110''>our</span>
  <span m=''3385220''>programs.</span> </p><p><span m=''3388160''>OK,</span> <span
  m=''3388490''>well,</span> <span m=''3388700''>that</span> <span m=''3388860''>seemed</span>
  <span m=''3389090''>easy.</span> <span m=''3390230''>All</span> <span m=''3390360''>of</span>
  <span m=''3390490''>this</span> <span m=''3390650''>mechanism</span> <span m=''3391120''>got</span>
  <span m=''3391300''>put</span> <span m=''3391440''>into</span> <span m=''3391610''>this</span>
  <span m=''3391770''>magic</span> <span m=''3392180''>delay.</span> <span m=''3393326''>So
  you''re</span> <span m=''3393880''>saying,</span> <span m=''3394070''>gee,</span>
  <span m=''3394250''>that</span> <span m=''3394460''>must</span> <span m=''3394630''>be</span>
  <span m=''3394740''>where</span> <span m=''3394890''>the</span> <span m=''3394980''>magic</span>
  <span m=''3395420''>is.</span> <span m=''3396900''>But</span> <span m=''3397400''>see</span>
  <span m=''3397470''>there''s</span> <span m=''3397620''>no</span> <span m=''3397710''>magic</span>
  <span m=''3398080''>there</span> <span m=''3398270''>either.</span> <span m=''3399070''>You</span>
  <span m=''3399170''>know</span> <span m=''3399280''>what</span> <span m=''3399430''>delay</span>
  <span m=''3399530''>is.</span> <span m=''3400610''>Delay</span> <span m=''3403685''>on</span>
  <span m=''3404180''>some</span> <span m=''3404390''>expression</span> <span m=''3408410''>is</span>
  <span m=''3408590''>just</span> <span m=''3408830''>an</span> <span m=''3408920''>abbreviation</span>
  <span m=''3409680''>for--</span> <span m=''3413400''>well,</span> <span m=''3414090''>what''s</span>
  <span m=''3414250''>a</span> <span m=''3414310''>promise</span> <span m=''3414650''>to</span>
  <span m=''3414750''>compute</span> <span m=''3414960''>an</span> <span m=''3415110''>expression?</span>
  <span m=''3416490''>Lambda</span> <span m=''3417110''>of</span> <span m=''3417470''>nil,</span>
  <span m=''3419120''>procedure</span> <span m=''3419590''>of no</span> <span m=''3419820''>arguments,</span>
  <span m=''3420270''>which</span> <span m=''3420430''>is</span> <span m=''3420570''>that</span>
  <span m=''3420700''>expression.</span> <span m=''3423000''>That''s</span> <span
  m=''3423180''>what</span> <span m=''3423260''>a</span> <span m=''3423320''>procedure</span>
  <span m=''3423625''>is.</span> <span m=''3423930''>It</span> <span m=''3424010''>says</span>
  <span m=''3424230''>I''m</span> <span m=''3424330''>going</span> <span m=''3424400''>to</span>
  <span m=''3424470''>compute an</span> <span m=''3424870''>expression.</span> </p><p><span
  m=''3426050''>What''s</span> <span m=''3426290''>force?</span> <span m=''3427460''>How
  do I</span> <span m=''3427750''>take</span> <span m=''3428010''>up</span> <span
  m=''3428140''>a</span> <span m=''3430320''>promise?</span> <span m=''3430800''>Well,</span>
  <span m=''3431230''>force</span> <span m=''3431670''>of</span> <span m=''3431760''>some</span>
  <span m=''3432810''>procedure,</span> <span m=''3433215''>a</span> <span m=''3433620''>promise,</span>
  <span m=''3434800''>is</span> <span m=''3434920''>just</span> <span m=''3435070''>run</span>
  <span m=''3435420''>it.</span> <span m=''3438710''>Done.</span> <span m=''3440120''>So</span>
  <span m=''3440340''>there''s</span> <span m=''3440510''>no</span> <span m=''3440590''>magic</span>
  <span m=''3440940''>there</span> <span m=''3441100''>at</span> <span m=''3441160''>all.</span>
  </p><p><span m=''3443580''>Well,</span> <span m=''3443810''>what have</span> <span
  m=''3443830''>we</span> <span m=''3443940''>done?</span> <span m=''3446440''>We</span>
  <span m=''3446500''>said</span> <span m=''3446660''>the</span> <span m=''3446770''>old</span>
  <span m=''3447070''>style,</span> <span m=''3448150''>traditional</span> <span m=''3449110''>style</span>
  <span m=''3449430''>of</span> <span m=''3449510''>programming</span> <span m=''3450020''>is</span>
  <span m=''3450110''>more</span> <span m=''3450290''>efficient.</span> <span m=''3450960''>And</span>
  <span m=''3451100''>the stream</span> <span m=''3451530''>thing</span> <span m=''3451720''>is</span>
  <span m=''3451810''>more</span> <span m=''3453150''>perspicuous.</span> <span m=''3455260''>And</span>
  <span m=''3455680''>we</span> <span m=''3455790''>managed</span> <span m=''3456480''>to</span>
  <span m=''3456670''>make</span> <span m=''3457060''>the</span> <span m=''3457500''>stream</span>
  <span m=''3458090''>procedures</span> <span m=''3458900''>run</span> <span m=''3459260''>like</span>
  <span m=''3459760''>the</span> <span m=''3460070''>other</span> <span m=''3460230''>procedures</span>
  <span m=''3462260''>by</span> <span m=''3462400''>using</span> <span m=''3462740''>delay.</span>
  <span m=''3463350''>And</span> <span m=''3463520''>the</span> <span m=''3463590''>thing</span>
  <span m=''3463830''>that</span> <span m=''3464010''>delay</span> <span m=''3464330''>did</span>
  <span m=''3464540''>for</span> <span m=''3464740''>us</span> <span m=''3465210''>was</span>
  <span m=''3465390''>to</span> <span m=''3465510''>de-couple</span> <span m=''3466600''>the</span>
  <span m=''3466880''>apparent</span> <span m=''3467570''>order</span> <span m=''3467950''>of</span>
  <span m=''3468090''>events</span> <span m=''3469540''>in</span> <span m=''3469660''>our</span>
  <span m=''3469760''>programs</span> <span m=''3471100''>from</span> <span m=''3471350''>the</span>
  <span m=''3471520''>actual</span> <span m=''3472150''>order</span> <span m=''3472370''>of</span>
  <span m=''3472460''>events</span> <span m=''3472770''>that</span> <span m=''3472880''>happened</span>
  <span m=''3473170''>in</span> <span m=''3473250''>the</span> <span m=''3473320''>machine.</span>
  <span m=''3474440''>That''s</span> <span m=''3474660''>really</span> <span m=''3474950''>what</span>
  <span m=''3475100''>delay</span> <span m=''3475360''>is</span> <span m=''3475530''>doing.</span>
  </p><p><span m=''3476540''>That''s</span> <span m=''3477390''>exactly</span> <span
  m=''3477890''>the</span> <span m=''3477960''>whole</span> <span m=''3478110''>point.</span>
  <span m=''3478290''>We''ve</span> <span m=''3478470''>given</span> <span m=''3478820''>up</span>
  <span m=''3481150''>the</span> <span m=''3481290''>idea</span> <span m=''3482260''>that</span>
  <span m=''3482460''>our</span> <span m=''3482590''>procedures,</span> <span m=''3483340''>as</span>
  <span m=''3483580''>they</span> <span m=''3483720''>run,</span> <span m=''3484720''>or</span>
  <span m=''3485030''>as</span> <span m=''3485200''>we</span> <span m=''3485330''>look</span>
  <span m=''3485540''>at</span> <span m=''3485660''>them,</span> <span m=''3486420''>mirror</span>
  <span m=''3486860''>some</span> <span m=''3487090''>clear</span> <span m=''3487390''>notion</span>
  <span m=''3487750''>of</span> <span m=''3487850''>time.</span> <span m=''3489182''>And</span>
  <span m=''3489650''>by</span> <span m=''3489850''>giving</span> <span m=''3490190''>that</span>
  <span m=''3490390''>up,</span> <span m=''3491340''>we</span> <span m=''3491460''>give</span>
  <span m=''3491630''>delay</span> <span m=''3491990''>the</span> <span m=''3492110''>freedom</span>
  <span m=''3492420''>to</span> <span m=''3492570''>arrange</span> <span m=''3492960''>the</span>
  <span m=''3493080''>order</span> <span m=''3493320''>of</span> <span m=''3493410''>events</span>
  <span m=''3493700''>in</span> <span m=''3493750''>the</span> <span m=''3493830''>computation</span>
  <span m=''3494400''>the</span> <span m=''3494470''>way</span> <span m=''3494620''>it</span>
  <span m=''3494810''>likes.</span> <span m=''3496690''>That''s</span> <span m=''3497040''>the</span>
  <span m=''3497100''>whole</span> <span m=''3497380''>idea.</span> <span m=''3497610''>We</span>
  <span m=''3497720''>de-couple</span> <span m=''3498400''>the</span> <span m=''3498490''>apparent</span>
  <span m=''3499050''>order</span> <span m=''3499970''>of</span> <span m=''3500150''>events</span>
  <span m=''3500470''>in</span> <span m=''3500550''>our</span> <span m=''3500640''>programs</span>
  <span m=''3501150''>from</span> <span m=''3501270''>the</span> <span m=''3501390''>actual</span>
  <span m=''3501780''>order</span> <span m=''3501990''>of</span> <span m=''3502070''>events</span>
  <span m=''3502360''>in</span> <span m=''3502430''>the</span> <span m=''3502490''>computer.</span>
  </p><p><span m=''3504200''>OK,</span> <span m=''3504480''>well</span> <span m=''3504590''>there''s</span>
  <span m=''3504750''>one</span> <span m=''3505340''>more</span> <span m=''3505490''>detail.</span>
  <span m=''3505770''>It''s</span> <span m=''3506050''>just</span> <span m=''3506320''>a</span>
  <span m=''3506380''>technical</span> <span m=''3506850''>detail,</span> <span m=''3507170''>but</span>
  <span m=''3507290''>it''s</span> <span m=''3507420''>actually</span> <span m=''3507750''>an</span>
  <span m=''3507810''>important</span> <span m=''3508250''>one.</span> <span m=''3509730''>As</span>
  <span m=''3509870''>you</span> <span m=''3510000''>run</span> <span m=''3510200''>through</span>
  <span m=''3510360''>these</span> <span m=''3510500''>recursive</span> <span m=''3511010''>programs</span>
  <span m=''3511490''>unwinding,</span> <span m=''3512190''>you''ll</span> <span m=''3512320''>see</span>
  <span m=''3512490''>a</span> <span m=''3512550''>lot</span> <span m=''3512750''>of</span>
  <span m=''3512830''>things</span> <span m=''3513050''>that</span> <span m=''3513200''>look</span>
  <span m=''3513370''>like</span> <span m=''3513570''>tail</span> <span m=''3515110''>of</span>
  <span m=''3515240''>the</span> <span m=''3515360''>tail</span> <span m=''3516666''>of</span>
  <span m=''3517040''>the</span> <span m=''3517340''>tail.</span> <span m=''3519320''>That''s</span>
  <span m=''3519940''>the</span> <span m=''3520020''>kind</span> <span m=''3520250''>of</span>
  <span m=''3520310''>thing</span> <span m=''3520450''>that</span> <span m=''3520550''>would</span>
  <span m=''3520660''>happen</span> <span m=''3521040''>as</span> <span m=''3521160''>I</span>
  <span m=''3521240''>go</span> <span m=''3521410''>CONSing</span> <span m=''3521840''>down
  a stream</span> <span m=''3522130''>all the</span> <span m=''3522420''>way.</span>
  <span m=''3523860''>And</span> <span m=''3524380''>if</span> <span m=''3524620''>each</span>
  <span m=''3524920''>time</span> <span m=''3525470''>I''m</span> <span m=''3525610''>doing</span>
  <span m=''3525920''>that,</span> <span m=''3526330''>each</span> <span m=''3526500''>time</span>
  <span m=''3526700''>to</span> <span m=''3526770''>compute</span> <span m=''3527100''>a</span>
  <span m=''3527170''>tail,</span> <span m=''3528260''>I</span> <span m=''3529740''>evaluate</span>
  <span m=''3530250''>a</span> <span m=''3530300''>procedure</span> <span m=''3531100''>which</span>
  <span m=''3531290''>then</span> <span m=''3531440''>has</span> <span m=''3531610''>to</span>
  <span m=''3531700''>go</span> <span m=''3531830''>re-compute</span> <span m=''3532420''>its</span>
  <span m=''3532640''>tail,</span> <span m=''3532990''>and</span> <span m=''3533300''>re-compute</span>
  <span m=''3533740''>its</span> <span m=''3534040''>tail</span> <span m=''3534160''>and</span>
  <span m=''3534270''>recompute</span> <span m=''3534630''>its tail</span> <span m=''3534950''>each</span>
  <span m=''3535110''>time,</span> <span m=''3535570''>you</span> <span m=''3535680''>can</span>
  <span m=''3535790''>see</span> <span m=''3535920''>that''s</span> <span m=''3536110''>very</span>
  <span m=''3536380''>inefficient</span> <span m=''3537800''>compared</span> <span
  m=''3538170''>to</span> <span m=''3538250''>just</span> <span m=''3538770''>having</span>
  <span m=''3539010''>a</span> <span m=''3539070''>list</span> <span m=''3539400''>where</span>
  <span m=''3539490''>the</span> <span m=''3539610''>elements</span> <span m=''3539980''>are</span>
  <span m=''3540060''>all</span> <span m=''3540290''>there,</span> <span m=''3541180''>and</span>
  <span m=''3541290''>I</span> <span m=''3541370''>don''t</span> <span m=''3541500''>have</span>
  <span m=''3541620''>to</span> <span m=''3541750''>re-compute</span> <span m=''3542120''>each</span>
  <span m=''3542510''>tail</span> <span m=''3542810''>every</span> <span m=''3542970''>time</span>
  <span m=''3543180''>I</span> <span m=''3543230''>get</span> <span m=''3543400''>the</span>
  <span m=''3543470''>next</span> <span m=''3543780''>tail.</span> </p><p><span m=''3545290''>So</span>
  <span m=''3545550''>there''s</span> <span m=''3545940''>one</span> <span m=''3547650''>little</span>
  <span m=''3547830''>hack</span> <span m=''3549640''>to</span> <span m=''3549820''>slightly</span>
  <span m=''3550410''>change</span> <span m=''3552390''>what</span> <span m=''3552520''>delay</span>
  <span m=''3552860''>is,</span> <span m=''3555030''>and</span> <span m=''3555190''>make</span>
  <span m=''3555380''>it</span> <span m=''3555460''>a</span> <span m=''3555520''>thing</span>
  <span m=''3556250''>which</span> <span m=''3556560''>is--</span> <span m=''3557380''>I''ll</span>
  <span m=''3557540''>write it</span> <span m=''3557740''>this</span> <span m=''3557930''>way.</span>
  <span m=''3560390''>The</span> <span m=''3560780''>actual</span> <span m=''3561180''>implementation,</span>
  <span m=''3564490''>delay</span> <span m=''3565260''>is</span> <span m=''3565410''>an</span>
  <span m=''3565480''>abbreviation</span> <span m=''3566190''>for</span> <span m=''3567360''>this</span>
  <span m=''3567630''>thing,</span> <span m=''3568130''>memo-proc</span> <span m=''3569990''>of</span>
  <span m=''3570150''>a</span> <span m=''3570210''>procedure.</span> <span m=''3571000''>Memo-proc</span>
  <span m=''3571640''>is</span> <span m=''3571770''>a</span> <span m=''3571810''>special</span>
  <span m=''3572560''>thing</span> <span m=''3572700''>that</span> <span m=''3572830''>transforms</span>
  <span m=''3573420''>a</span> <span m=''3573480''>procedure.</span> <span m=''3575150''>What</span>
  <span m=''3575290''>it</span> <span m=''3575410''>does</span> <span m=''3575950''>is</span>
  <span m=''3576090''>it</span> <span m=''3576200''>takes</span> <span m=''3576460''>a</span>
  <span m=''3576520''>procedure</span> <span m=''3577030''>of</span> <span m=''3577100''>no</span>
  <span m=''3577270''>arguments</span> <span m=''3579080''>and</span> <span m=''3579250''>it</span>
  <span m=''3579330''>transforms</span> <span m=''3580060''>it</span> <span m=''3580160''>into</span>
  <span m=''3580400''>a</span> <span m=''3580460''>procedure</span> <span m=''3581240''>that''ll</span>
  <span m=''3581540''>only</span> <span m=''3581900''>have</span> <span m=''3582090''>to</span>
  <span m=''3582190''>do</span> <span m=''3582320''>its</span> <span m=''3582460''>computation</span>
  <span m=''3583220''>once.</span> </p><p><span m=''3584806''>And</span> <span m=''3585200''>what</span>
  <span m=''3585330''>I</span> <span m=''3585460''>mean</span> <span m=''3585690''>by</span>
  <span m=''3585860''>that</span> <span m=''3586100''>is,</span> <span m=''3586390''>you</span>
  <span m=''3586560''>give</span> <span m=''3586730''>it</span> <span m=''3586790''>a</span>
  <span m=''3586840''>procedure.</span> <span m=''3588700''>The</span> <span m=''3588830''>result</span>
  <span m=''3589190''>of</span> <span m=''3589270''>memo-proc</span> <span m=''3589580''>will
  be</span> <span m=''3589990''>a</span> <span m=''3590140''>new</span> <span m=''3590320''>procedure,</span>
  <span m=''3591430''>which</span> <span m=''3591770''>the</span> <span m=''3591950''>first</span>
  <span m=''3592310''>time</span> <span m=''3592500''>you</span> <span m=''3592610''>call</span>
  <span m=''3592940''>it,</span> <span m=''3593690''>will</span> <span m=''3593870''>run</span>
  <span m=''3594070''>the</span> <span m=''3594200''>original</span> <span m=''3594550''>procedure,</span>
  <span m=''3595370''>remember</span> <span m=''3595880''>what</span> <span m=''3596070''>result
  it</span> <span m=''3596550''>got,</span> <span m=''3598530''>and</span> <span m=''3598680''>then</span>
  <span m=''3598840''>from</span> <span m=''3599010''>ever</span> <span m=''3599260''>on</span>
  <span m=''3599680''>after,</span> <span m=''3600040''>when</span> <span m=''3600180''>you</span>
  <span m=''3600280''>call</span> <span m=''3600590''>it,</span> <span m=''3600670''>it</span>
  <span m=''3600840''>just</span> <span m=''3601000''>won''t</span> <span m=''3601190''>have</span>
  <span m=''3601340''>to</span> <span m=''3601430''>do</span> <span m=''3601520''>the</span>
  <span m=''3601610''>computation.</span> <span m=''3602360''>It</span> <span m=''3602520''>will
  have</span> <span m=''3603030''>cached</span> <span m=''3603400''>that</span> <span
  m=''3603600''>result</span> <span m=''3604000''>someplace.</span> </p><p><span m=''3605200''>And</span>
  <span m=''3605360''>here''s</span> <span m=''3605520''>an</span> <span m=''3605580''>implementation</span>
  <span m=''3606200''>of</span> <span m=''3606280''>memo-proc.</span> <span m=''3611210''>Once
  you</span> <span m=''3611340''>have</span> <span m=''3611510''>the</span> <span
  m=''3611620''>idea,</span> <span m=''3611910''>it''s</span> <span m=''3612030''>easy</span>
  <span m=''3612210''>to</span> <span m=''3612270''>implement.</span> <span m=''3612710''>Memo-proc</span>
  <span m=''3612850''>is</span> <span m=''3613290''>this</span> <span m=''3613450''>little</span>
  <span m=''3613640''>thing</span> <span m=''3614280''>that</span> <span m=''3614570''>has</span>
  <span m=''3615650''>two</span> <span m=''3615830''>little</span> <span m=''3616000''>flags</span>
  <span m=''3616390''>in</span> <span m=''3616500''>there.</span> <span m=''3617390''>It</span>
  <span m=''3617530''>says,</span> <span m=''3617710''>have</span> <span m=''3617920''>I</span>
  <span m=''3618110''>already</span> <span m=''3618540''>been</span> <span m=''3618700''>run?</span>
  <span m=''3620320''>And</span> <span m=''3620490''>initially</span> <span m=''3620910''>it</span>
  <span m=''3620990''>says,</span> <span m=''3621160''>no,</span> <span m=''3621330''>I</span>
  <span m=''3621420''>haven''t</span> <span m=''3621720''>already</span> <span m=''3622050''>been</span>
  <span m=''3622240''>run.</span> <span m=''3623620''>And</span> <span m=''3623990''>what</span>
  <span m=''3624180''>was</span> <span m=''3624320''>the</span> <span m=''3624400''>result</span>
  <span m=''3624790''>I</span> <span m=''3624880''>got</span> <span m=''3625500''>the</span>
  <span m=''3625910''>last</span> <span m=''3626190''>time</span> <span m=''3626410''>I</span>
  <span m=''3626530''>was</span> <span m=''3626640''>run?</span> </p><p><span m=''3629070''>So</span>
  <span m=''3629350''>memo-proc</span> <span m=''3629430''>takes</span> <span m=''3629990''>a</span>
  <span m=''3630040''>procedure</span> <span m=''3630480''>called</span> <span m=''3630720''>proc,</span>
  <span m=''3631610''>and</span> <span m=''3631710''>it</span> <span m=''3631810''>returns</span>
  <span m=''3632150''>a</span> <span m=''3632200''>new</span> <span m=''3632360''>procedure</span>
  <span m=''3632950''>of</span> <span m=''3633250''>no</span> <span m=''3633490''>arguments.</span>
  <span m=''3634360''>Proc is</span> <span m=''3634750''>supposed</span> <span m=''3634910''>to</span>
  <span m=''3635070''>be a</span> <span m=''3635190''>procedure</span> <span m=''3635450''>of</span>
  <span m=''3635710''>no</span> <span m=''3635870''>arguments.</span> <span m=''3638610''>And</span>
  <span m=''3638760''>it</span> <span m=''3638900''>says,</span> <span m=''3639180''>oh,</span>
  <span m=''3639520''>if</span> <span m=''3639770''>I''m</span> <span m=''3639950''>not</span>
  <span m=''3640390''>already</span> <span m=''3640940''>run,</span> <span m=''3642630''>then</span>
  <span m=''3642770''>I''m</span> <span m=''3642850''>going</span> <span m=''3642910''>to</span>
  <span m=''3642970''>do</span> <span m=''3643070''>a</span> <span m=''3643120''>sequence</span>
  <span m=''3643550''>of</span> <span m=''3643650''>things.</span> <span m=''3644430''>I''m</span>
  <span m=''3644610''>going</span> <span m=''3644740''>to</span> <span m=''3645000''>compute</span>
  <span m=''3646210''>proc,</span> <span m=''3647080''>I''m</span> <span m=''3647520''>going</span>
  <span m=''3647690''>to</span> <span m=''3647770''>save</span> <span m=''3648240''>that.</span>
  <span m=''3648450''>I''m going to</span> <span m=''3648490''>stash</span> <span
  m=''3648870''>that in</span> <span m=''3649110''>the</span> <span m=''3649190''>variable</span>
  <span m=''3649610''>result.</span> <span m=''3651140''>I''m</span> <span m=''3651350''>going</span>
  <span m=''3651440''>to</span> <span m=''3651700''>make</span> <span m=''3651920''>a</span>
  <span m=''3651980''>note</span> <span m=''3652220''>to</span> <span m=''3652310''>myself</span>
  <span m=''3652710''>that</span> <span m=''3652840''>I''ve</span> <span m=''3653010''>already</span>
  <span m=''3653350''>been</span> <span m=''3653510''>run,</span> <span m=''3654330''>and</span>
  <span m=''3654530''>then I''ll</span> <span m=''3654630''>return the</span> <span
  m=''3655000''>result.</span> </p><p><span m=''3656610''>So</span> <span m=''3656790''>that''s</span>
  <span m=''3657000''>if</span> <span m=''3657090''>you</span> <span m=''3657190''>compute
  it</span> <span m=''3657550''>if</span> <span m=''3657630''>it''s</span> <span m=''3657780''>not</span>
  <span m=''3658020''>already</span> <span m=''3658420''>run.</span> <span m=''3659010''>If</span>
  <span m=''3659160''>you</span> <span m=''3659280''>call</span> <span m=''3659610''>it</span>
  <span m=''3659860''>and</span> <span m=''3659980''>it''s</span> <span m=''3660100''>already</span>
  <span m=''3660440''>been</span> <span m=''3660560''>run,</span> <span m=''3660730''>it</span>
  <span m=''3660810''>just</span> <span m=''3661040''>returns</span> <span m=''3661400''>the</span>
  <span m=''3661470''>result.</span> <span m=''3663420''>So</span> <span m=''3663580''>that''s</span>
  <span m=''3665170''>a</span> <span m=''3665220''>little</span> <span m=''3665630''>clever</span>
  <span m=''3665850''>hack called</span> <span m=''3666260''>memoization.</span> <span
  m=''3668400''>And</span> <span m=''3668560''>in</span> <span m=''3668700''>this</span>
  <span m=''3668830''>case,</span> <span m=''3670400''>it</span> <span m=''3670530''>short</span>
  <span m=''3670830''>circuits</span> <span m=''3671230''>having</span> <span m=''3671470''>to</span>
  <span m=''3671590''>re-compute</span> <span m=''3672100''>the</span> <span m=''3672200''>tail</span>
  <span m=''3672530''>of the</span> <span m=''3672630''>tail</span> <span m=''3672950''>of
  the</span> <span m=''3673030''>tail</span> <span m=''3673330''>of the</span> <span
  m=''3673430''>tail</span> <span m=''3673700''>of the</span> <span m=''3673790''>tail.</span>
  <span m=''3675270''>So</span> <span m=''3675440''>there</span> <span m=''3676200''>isn''t</span>
  <span m=''3676410''>even</span> <span m=''3676660''>that</span> <span m=''3676920''>kind</span>
  <span m=''3677070''>of</span> <span m=''3677220''>inefficiency.</span> <span m=''3677810''>And</span>
  <span m=''3677890''>in</span> <span m=''3677990''>fact,</span> <span m=''3678220''>the</span>
  <span m=''3678290''>streams</span> <span m=''3679200''>will</span> <span m=''3679410''>run</span>
  <span m=''3679610''>with</span> <span m=''3679760''>pretty</span> <span m=''3680020''>much</span>
  <span m=''3680260''>the</span> <span m=''3680340''>same</span> <span m=''3680590''>efficiency</span>
  <span m=''3681080''>as</span> <span m=''3681180''>the</span> <span m=''3681310''>other</span>
  <span m=''3681440''>programs</span> <span m=''3682160''>precisely.</span> </p><p><span
  m=''3684210''>And</span> <span m=''3684420''>remember,</span> <span m=''3684820''>again,</span>
  <span m=''3684980''>the</span> <span m=''3685050''>whole</span> <span m=''3685420''>idea</span>
  <span m=''3685780''>of</span> <span m=''3685970''>this</span> <span m=''3687520''>is</span>
  <span m=''3687730''>that</span> <span m=''3687910''>we''ve</span> <span m=''3688110''>used</span>
  <span m=''3689330''>the</span> <span m=''3690080''>fact</span> <span m=''3690240''>that</span>
  <span m=''3690390''>there''s</span> <span m=''3690550''>no</span> <span m=''3691240''>really</span>
  <span m=''3691500''>good</span> <span m=''3691760''>dividing</span> <span m=''3692190''>line</span>
  <span m=''3692390''>between</span> <span m=''3692640''>procedures</span> <span m=''3693110''>and</span>
  <span m=''3693240''>data.</span> <span m=''3693610''>We''ve</span> <span m=''3693750''>written</span>
  <span m=''3694440''>data</span> <span m=''3694700''>structures</span> <span m=''3695140''>that,</span>
  <span m=''3695250''>in</span> <span m=''3695350''>fact,</span> <span m=''3696030''>are</span>
  <span m=''3696190''>sort</span> <span m=''3696410''>of</span> <span m=''3696510''>like</span>
  <span m=''3696720''>procedures.</span> <span m=''3698760''>And</span> <span m=''3698940''>what</span>
  <span m=''3699080''>that''s</span> <span m=''3699280''>allowed</span> <span m=''3699910''>us</span>
  <span m=''3700140''>to</span> <span m=''3700260''>do</span> <span m=''3701650''>is</span>
  <span m=''3701870''>take</span> <span m=''3704520''>an</span> <span m=''3704630''>example</span>
  <span m=''3705120''>of</span> <span m=''3705210''>a</span> <span m=''3705280''>common</span>
  <span m=''3705750''>control</span> <span m=''3706150''>structure,</span> <span m=''3706770''>in</span>
  <span m=''3706900''>this</span> <span m=''3707030''>place</span> <span m=''3708320''>iteration.</span>
  <span m=''3709620''>And</span> <span m=''3709740''>we''ve</span> <span m=''3709870''>built</span>
  <span m=''3710190''>a</span> <span m=''3710230''>data</span> <span m=''3710530''>structure</span>
  <span m=''3711340''>which,</span> <span m=''3711690''>since</span> <span m=''3712020''>itself</span>
  <span m=''3712460''>is</span> <span m=''3712580''>a</span> <span m=''3712640''>procedure,</span>
  <span m=''3713090''>kind of</span> <span m=''3713310''>has</span> <span m=''3713550''>this</span>
  <span m=''3713660''>iteration</span> <span m=''3714180''>control</span> <span m=''3714530''>structure</span>
  <span m=''3714870''>in</span> <span m=''3715030''>it.</span> <span m=''3715496''>And</span>
  <span m=''3715842''>that''s</span> <span m=''3716190''>really</span> <span m=''3716430''>what</span>
  <span m=''3716570''>streams</span> <span m=''3716910''>are.</span> <span m=''3718650''>OK,</span>
  <span m=''3719250''>questions?</span> </p><p><span m=''3723950''>AUDIENCE: Your</span>
  <span m=''3724120''>description</span> <span m=''3724660''>of</span> <span m=''3724760''>tail-tail-tail,</span>
  <span m=''3725880''>if</span> <span m=''3726030''>I</span> <span m=''3726110''>understand</span>
  <span m=''3726520''>it</span> <span m=''3726610''>correctly,</span> <span m=''3727120''>force
  is</span> <span m=''3728180''>actually</span> <span m=''3728550''>execution</span>
  <span m=''3729180''>of</span> <span m=''3729330''>a</span> <span m=''3730050''>procedure,</span>
  <span m=''3730770''>if</span> <span m=''3730970''>it''s</span> <span m=''3731200''>done</span>
  <span m=''3731370''>without</span> <span m=''3731670''>this</span> <span m=''3731830''>memo-proc</span>
  <span m=''3732240''>thing.</span> <span m=''3733052''>And</span> <span m=''3733460''>you</span>
  <span m=''3733680''>implied</span> <span m=''3734100''>that</span> <span m=''3734440''>memo-proc</span>
  <span m=''3734985''>gets</span> <span m=''3735270''>around</span> <span m=''3735640''>that</span>
  <span m=''3735870''>problem.</span> <span m=''3736380''>Doesn''t</span> <span m=''3736650''>it
  only</span> <span m=''3736890''>get</span> <span m=''3737030''>around</span> <span
  m=''3737340''>it</span> <span m=''3738000''>if</span> <span m=''3739300''>tail-tail-tail</span>
  <span m=''3740110''>is</span> <span m=''3740210''>always</span> <span m=''3740580''>executing</span>
  <span m=''3740980''>exactly</span> <span m=''3741560''>the</span> <span m=''3741670''>same--</span>
  </p><p><span m=''3742550''>PROFESSOR: Oh,</span> <span m=''3742930''>that''s--</span>
  <span m=''3743500''>sure.</span> </p><p><span m=''3743910''>AUDIENCE: I</span> <span
  m=''3744010''>guess</span> <span m=''3744180''>I</span> <span m=''3744970''>missed</span>
  <span m=''3745200''>that</span> <span m=''3745450''>point.</span> </p><p><span m=''3746050''>PROFESSOR:
  Oh,</span> <span m=''3746180''>sure.</span> <span m=''3746540''>I</span> <span m=''3746620''>mean</span>
  <span m=''3746780''>the</span> <span m=''3746850''>point</span> <span m=''3747080''>is--</span>
  <span m=''3751160''>yeah.</span> <span m=''3751290''>I</span> <span m=''3751370''>mean</span>
  <span m=''3751540''>I</span> <span m=''3751760''>have</span> <span m=''3751950''>to</span>
  <span m=''3752040''>do</span> <span m=''3752180''>a</span> <span m=''3752250''>computation</span>
  <span m=''3752870''>to</span> <span m=''3752960''>get</span> <span m=''3753160''>the</span>
  <span m=''3753230''>answer.</span> <span m=''3754160''>But</span> <span m=''3754290''>the</span>
  <span m=''3754360''>point</span> <span m=''3754560''>is,</span> <span m=''3754680''>once</span>
  <span m=''3755380''>I''ve</span> <span m=''3755550''>found</span> <span m=''3755820''>the</span>
  <span m=''3755900''>tail</span> <span m=''3756200''>of</span> <span m=''3756290''>the</span>
  <span m=''3756370''>stream,</span> <span m=''3757590''>to</span> <span m=''3757720''>get</span>
  <span m=''3757850''>the</span> <span m=''3757950''>tail</span> <span m=''3758300''>of</span>
  <span m=''3758390''>the</span> <span m=''3758480''>tail,</span> <span m=''3758760''>I</span>
  <span m=''3758810''>shouldn''t</span> <span m=''3759040''>have</span> <span m=''3759130''>had</span>
  <span m=''3759300''>to</span> <span m=''3759530''>re-compute</span> <span m=''3759850''>the</span>
  <span m=''3760050''>first</span> <span m=''3760260''>tail.</span> <span m=''3762980''>See,</span>
  <span m=''3763250''>and if</span> <span m=''3763360''>I</span> <span m=''3763430''>didn''t</span>
  <span m=''3763680''>use</span> <span m=''3763870''>memo-proc,</span> <span m=''3764360''>that</span>
  <span m=''3764520''>re-computation</span> <span m=''3765370''>would</span> <span
  m=''3765470''>have</span> <span m=''3765580''>been</span> <span m=''3765690''>done.</span>
  </p><p><span m=''3766460''>AUDIENCE: I understand</span> <span m=''3766760''>now.</span>
  </p><p><span m=''3770830''>AUDIENCE: In one of</span> <span m=''3771110''>your examples,</span>
  <span m=''3771760''>you</span> <span m=''3771900''>mentioned</span> <span m=''3772340''>that</span>
  <span m=''3772550''>we</span> <span m=''3772760''>were able</span> <span m=''3773170''>to
  use</span> <span m=''3773310''>the</span> <span m=''3773360''>substitution</span>
  <span m=''3773660''>model</span> <span m=''3774310''>because</span> <span m=''3775010''>there</span>
  <span m=''3775220''>are</span> <span m=''3775260''>no</span> <span m=''3775430''>side</span>
  <span m=''3775730''>effects.</span> <span m=''3776830''>What</span> <span m=''3777040''>if</span>
  <span m=''3777170''>we</span> <span m=''3777300''>had</span> <span m=''3777670''>a</span>
  <span m=''3779530''>single</span> <span m=''3779960''>processing</span> <span m=''3780420''>unit--</span>
  <span m=''3781040''>if we</span> <span m=''3781190''>had</span> <span m=''3781430''>a</span>
  <span m=''3781480''>side</span> <span m=''3781720''>effect,</span> <span m=''3782160''>if
  we had</span> <span m=''3782320''>a</span> <span m=''3782470''>state?</span> <span
  m=''3783620''>Could</span> <span m=''3783820''>we</span> <span m=''3784000''>still</span>
  <span m=''3785210''>practically</span> <span m=''3785840''>build the</span> <span
  m=''3786110''>stream</span> <span m=''3786460''>model?</span> </p><p><span m=''3789120''>PROFESSOR:
  Maybe.</span> <span m=''3789530''>That''s</span> <span m=''3789730''>a</span> <span
  m=''3789790''>hard</span> <span m=''3790030''>question.</span> <span m=''3790540''>I''m</span>
  <span m=''3790990''>going to</span> <span m=''3791440''>talk</span> <span m=''3791680''>a</span>
  <span m=''3791730''>little</span> <span m=''3791940''>bit</span> <span m=''3792100''>later</span>
  <span m=''3792420''>about</span> <span m=''3792680''>the</span> <span m=''3792760''>places</span>
  <span m=''3793190''>where</span> <span m=''3795540''>substitution</span> <span m=''3796290''>and</span>
  <span m=''3796410''>side</span> <span m=''3796640''>effects</span> <span m=''3796940''>don''t</span>
  <span m=''3797080''>really</span> <span m=''3797390''>mix</span> <span m=''3797650''>very</span>
  <span m=''3797880''>well.</span> <span m=''3798960''>But</span> <span m=''3799090''>in</span>
  <span m=''3799230''>general,</span> <span m=''3799680''>I</span> <span m=''3799830''>think</span>
  <span m=''3799980''>the</span> <span m=''3800130''>answer</span> <span m=''3800420''>is</span>
  <span m=''3800500''>unless</span> <span m=''3800780''>you''re</span> <span m=''3800890''>very</span>
  <span m=''3801170''>careful,</span> <span m=''3802000''>any</span> <span m=''3802320''>amount</span>
  <span m=''3802640''>of</span> <span m=''3802710''>side</span> <span m=''3802970''>effect</span>
  <span m=''3803290''>is</span> <span m=''3803380''>going</span> <span m=''3803470''>to</span>
  <span m=''3803550''>mess</span> <span m=''3803780''>up</span> <span m=''3803920''>everything.</span>
  </p><p><span m=''3815490''>AUDIENCE: Sorry, I didn''t quite</span> <span m=''3815670''>understand</span>
  <span m=''3816150''>the</span> <span m=''3816210''>memo-proc</span> <span m=''3817060''>operation.</span>
  <span m=''3819410''>When</span> <span m=''3819730''>do</span> <span m=''3819920''>you</span>
  <span m=''3820150''>execute</span> <span m=''3820570''>the</span> <span m=''3820650''>lambda?</span>
  <span m=''3821990''>In</span> <span m=''3822120''>other</span> <span m=''3822250''>words,</span>
  <span m=''3823730''>when</span> <span m=''3823890''>memo-proc</span> <span m=''3824210''>is</span>
  <span m=''3824610''>executed,</span> <span m=''3825210''>just</span> <span m=''3825520''>this</span>
  <span m=''3825830''>lambda</span> <span m=''3826270''>expression</span> <span m=''3826700''>is</span>
  <span m=''3826800''>being</span> <span m=''3827030''>generated.</span> <span m=''3827600''>But</span>
  <span m=''3828060''>it''s</span> <span m=''3828220''>not</span> <span m=''3828420''>clear</span>
  <span m=''3828810''>to me when</span> <span m=''3829040''>it''s</span> <span m=''3829350''>executed.</span>
  </p><p><span m=''3830390''>PROFESSOR: Right.</span> <span m=''3831350''>What</span>
  <span m=''3831530''>memo-proc</span> <span m=''3831780''>does--</span> <span m=''3832170''>remember,</span>
  <span m=''3833160''>the</span> <span m=''3833440''>thing</span> <span m=''3833700''>that''s</span>
  <span m=''3833890''>going</span> <span m=''3834140''>into</span> <span m=''3834450''>memo-proc,</span>
  <span m=''3834740''>the</span> <span m=''3835170''>thing</span> <span m=''3835410''>proc,</span>
  <span m=''3836440''>is</span> <span m=''3836670''>a</span> <span m=''3836730''>procedure</span>
  <span m=''3837010''>of</span> <span m=''3837290''>no</span> <span m=''3837480''>arguments.</span>
  <span m=''3837930''>And</span> <span m=''3838020''>someday,</span> <span m=''3838380''>you''re</span>
  <span m=''3838480''>going</span> <span m=''3838560''>to</span> <span m=''3838640''>call</span>
  <span m=''3838940''>it.</span> <span m=''3840390''>Memo-proc</span> <span m=''3841690''>translates</span>
  <span m=''3842280''>that</span> <span m=''3842450''>procedure</span> <span m=''3842900''>into</span>
  <span m=''3843010''>another</span> <span m=''3843350''>procedure</span> <span m=''3843890''>of</span>
  <span m=''3843990''>no</span> <span m=''3844130''>arguments,</span> <span m=''3844560''>which</span>
  <span m=''3844710''>someday</span> <span m=''3845110''>you''re</span> <span m=''3845240''>going</span>
  <span m=''3845330''>to</span> <span m=''3845420''>call.</span> <span m=''3846620''>That''s</span>
  <span m=''3846880''>that</span> <span m=''3847165''>lambda.</span> </p><p><span
  m=''3849890''>So</span> <span m=''3850120''>here,</span> <span m=''3850760''>where
  I</span> <span m=''3851040''>initially</span> <span m=''3852720''>built</span> <span
  m=''3853460''>as</span> <span m=''3853730''>my</span> <span m=''3856840''>tail</span>
  <span m=''3857190''>of</span> <span m=''3857280''>the</span> <span m=''3857370''>stream,</span>
  <span m=''3858230''>say,</span> <span m=''3859120''>this</span> <span m=''3859390''>procedure</span>
  <span m=''3859890''>of no</span> <span m=''3860080''>arguments,</span> <span m=''3860530''>which</span>
  <span m=''3860680''>someday</span> <span m=''3861020''>I''ll</span> <span m=''3861160''>call.</span>
  <span m=''3864100''>Instead,</span> <span m=''3864910''>I''m</span> <span m=''3865030''>going</span>
  <span m=''3865350''>to</span> <span m=''3865770''>have</span> <span m=''3866260''>the</span>
  <span m=''3866430''>tail</span> <span m=''3866660''>of the</span> <span m=''3866730''>stream
  be</span> <span m=''3867130''>memo-proc</span> <span m=''3867400''>of</span> <span
  m=''3867790''>it,</span> <span m=''3868180''>which</span> <span m=''3868340''>someday</span>
  <span m=''3868750''>I''ll</span> <span m=''3868900''>call.</span> <span m=''3870650''>So</span>
  <span m=''3870850''>that</span> <span m=''3871070''>lambda</span> <span m=''3871450''>of</span>
  <span m=''3871630''>nil,</span> <span m=''3872030''>that</span> <span m=''3872350''>gets</span>
  <span m=''3872580''>called</span> <span m=''3874010''>when</span> <span m=''3874820''>you</span>
  <span m=''3874970''>call</span> <span m=''3875260''>the</span> <span m=''3875340''>memo-proc,</span>
  <span m=''3879150''>when</span> <span m=''3879300''>you</span> <span m=''3879400''>call</span>
  <span m=''3879670''>the</span> <span m=''3879750''>result</span> <span m=''3880160''>of</span>
  <span m=''3880240''>that</span> <span m=''3880410''>memo-proc,</span> <span m=''3880990''>which</span>
  <span m=''3881480''>would</span> <span m=''3881590''>be</span> <span m=''3881700''>ordinarily</span>
  <span m=''3882380''>when</span> <span m=''3882650''>you</span> <span m=''3882790''>would</span>
  <span m=''3883410''>have</span> <span m=''3883750''>called</span> <span m=''3884230''>the</span>
  <span m=''3884400''>original</span> <span m=''3884820''>thing</span> <span m=''3885060''>that</span>
  <span m=''3885190''>you</span> <span m=''3885300''>set</span> <span m=''3885550''>it.</span>
  </p><p><span m=''3887642''>AUDIENCE: OK,</span> <span m=''3888120''>the reason</span>
  <span m=''3888435''>I ask is</span> <span m=''3888750''>I had a</span> <span m=''3889070''>feeling</span>
  <span m=''3889360''>that</span> <span m=''3889540''>when</span> <span m=''3889690''>you</span>
  <span m=''3889770''>call</span> <span m=''3890110''>memo-proc,</span> <span m=''3890680''>you</span>
  <span m=''3890940''>just</span> <span m=''3891180''>return</span> <span m=''3891600''>this</span>
  <span m=''3891810''>lambda.</span> </p><p><span m=''3892610''>PROFESSOR: That''s</span>
  <span m=''3892830''>right.</span> <span m=''3893770''>When you</span> <span m=''3893910''>call</span>
  <span m=''3894110''>memo-proc,</span> <span m=''3894420''>you</span> <span m=''3894750''>return</span>
  <span m=''3897290''>the</span> <span m=''3897730''>lambda.</span> <span m=''3898100''>You</span>
  <span m=''3898190''>never</span> <span m=''3898410''>evaluate</span> <span m=''3898890''>the</span>
  <span m=''3898970''>expression</span> <span m=''3899420''>at</span> <span m=''3899590''>all,</span>
  <span m=''3899750''>until</span> <span m=''3900000''>the</span> <span m=''3900090''>first</span>
  <span m=''3900430''>time</span> <span m=''3900690''>that</span> <span m=''3900830''>you</span>
  <span m=''3901010''>would</span> <span m=''3901230''>have</span> <span m=''3901490''>evaluated</span>
  <span m=''3901880''>it.</span> </p><p><span m=''3907590''>AUDIENCE: Do I</span>
  <span m=''3907950''>understand</span> <span m=''3908250''>it</span> <span m=''3908550''>right</span>
  <span m=''3908830''>that</span> <span m=''3909190''>you</span> <span m=''3909360''>actually</span>
  <span m=''3909800''>have</span> <span m=''3910000''>to</span> <span m=''3910120''>build</span>
  <span m=''3910490''>the</span> <span m=''3910570''>list</span> <span m=''3911030''>up,</span>
  <span m=''3911480''>but</span> <span m=''3911660''>the</span> <span m=''3912480''>elements</span>
  <span m=''3912850''>of</span> <span m=''3912920''>the</span> <span m=''3912980''>list</span>
  <span m=''3913230''>don''t</span> <span m=''3913430''>get</span> <span m=''3913570''>evaluated?</span>
  <span m=''3914240''>The</span> <span m=''3914310''>expressions</span> <span m=''3914840''>don''t
  get</span> <span m=''3915150''>evaluated?</span> <span m=''3915630''>But</span>
  <span m=''3915870''>at each</span> <span m=''3916370''>stage,</span> <span m=''3916630''>you</span>
  <span m=''3916890''>actually</span> <span m=''3917190''>are</span> <span m=''3917360''>building</span>
  <span m=''3917710''>a</span> <span m=''3917770''>list.</span> </p><p><span m=''3918540''>PROFESSOR:
  That''s--</span> <span m=''3919750''>I</span> <span m=''3919900''>really</span>
  <span m=''3920100''>should</span> <span m=''3920320''>have said</span> <span m=''3920550''>this.</span>
  <span m=''3920700''>That''s</span> <span m=''3921640''>a</span> <span m=''3921700''>really</span>
  <span m=''3921920''>good</span> <span m=''3922050''>point.</span> <span m=''3922270''>No,</span>
  <span m=''3922430''>it''s</span> <span m=''3922550''>not</span> <span m=''3922690''>quite</span>
  <span m=''3922900''>right.</span> <span m=''3923660''>Because</span> <span m=''3924020''>what</span>
  <span m=''3924140''>happens</span> <span m=''3924510''>is</span> <span m=''3924660''>this.</span>
  <span m=''3925080''>Let</span> <span m=''3925240''>me</span> <span m=''3925330''>draw</span>
  <span m=''3925580''>this</span> <span m=''3925770''>as</span> <span m=''3925920''>pairs.</span>
  <span m=''3926890''>Suppose I''m</span> <span m=''3927090''>going</span> <span m=''3927140''>to</span>
  <span m=''3927200''>make</span> <span m=''3927350''>a</span> <span m=''3927410''>big</span>
  <span m=''3927620''>stream,</span> <span m=''3929030''>like</span> <span m=''3929220''>enumerate</span>
  <span m=''3929710''>interval,</span> <span m=''3930390''>1</span> <span m=''3930620''>through</span>
  <span m=''3930850''>1</span> <span m=''3931300''>billion.</span> <span m=''3932740''>What</span>
  <span m=''3932900''>that</span> <span m=''3933110''>is,</span> <span m=''3933320''>is</span>
  <span m=''3935210''>a</span> <span m=''3935310''>pair</span> <span m=''3939370''>with
  a</span> <span m=''3939570''>1</span> <span m=''3941700''>and</span> <span m=''3942700''>a</span>
  <span m=''3942780''>promise.</span> <span m=''3946520''>That''s</span> <span m=''3947030''>exactly</span>
  <span m=''3947540''>what</span> <span m=''3947670''>it</span> <span m=''3947750''>is.</span>
  <span m=''3947890''>Nothing</span> <span m=''3948190''>got</span> <span m=''3948380''>built</span>
  <span m=''3948630''>up.</span> </p><p><span m=''3951600''>When</span> <span m=''3951750''>I</span>
  <span m=''3952200''>go</span> <span m=''3952390''>and</span> <span m=''3952510''>force</span>
  <span m=''3952940''>this,</span> <span m=''3954540''>and</span> <span m=''3954740''>say,</span>
  <span m=''3955820''>what</span> <span m=''3955970''>happens?</span> <span m=''3956370''>Well,</span>
  <span m=''3957320''>this</span> <span m=''3957570''>thing</span> <span m=''3957730''>is</span>
  <span m=''3957850''>now</span> <span m=''3958190''>also</span> <span m=''3958570''>recursively</span>
  <span m=''3958890''>a</span> <span m=''3959240''>CONS.</span> <span m=''3960530''>So</span>
  <span m=''3960690''>that</span> <span m=''3960860''>this</span> <span m=''3961040''>promise</span>
  <span m=''3961460''>now</span> <span m=''3961800''>is</span> <span m=''3964470''>the</span>
  <span m=''3964720''>next</span> <span m=''3964970''>thing,</span> <span m=''3965130''>which</span>
  <span m=''3965310''>is</span> <span m=''3965430''>a</span> <span m=''3965500''>2</span>
  <span m=''3967770''>and</span> <span m=''3967930''>a</span> <span m=''3967980''>promise</span>
  <span m=''3968440''>to</span> <span m=''3968540''>do</span> <span m=''3968710''>more.</span>
  <span m=''3971350''>And</span> <span m=''3971540''>so</span> <span m=''3971730''>on</span>
  <span m=''3971880''>and</span> <span m=''3972010''>so</span> <span m=''3972150''>on</span>
  <span m=''3972240''>and</span> <span m=''3972380''>so</span> <span m=''3972520''>on.</span>
  </p><p><span m=''3974470''>So</span> <span m=''3974720''>nothing</span> <span m=''3975690''>gets</span>
  <span m=''3975940''>built</span> <span m=''3976180''>up</span> <span m=''3976330''>until</span>
  <span m=''3976540''>you</span> <span m=''3976720''>walk</span> <span m=''3976950''>down</span>
  <span m=''3977160''>the</span> <span m=''3977230''>stream.</span> <span m=''3978200''>Because</span>
  <span m=''3978450''>what''s</span> <span m=''3978550''>sitting</span> <span m=''3978840''>here</span>
  <span m=''3978940''>is</span> <span m=''3979010''>not</span> <span m=''3979200''>the</span>
  <span m=''3979280''>list,</span> <span m=''3979950''>but</span> <span m=''3980160''>a</span>
  <span m=''3980210''>promise</span> <span m=''3980660''>to</span> <span m=''3980790''>generate</span>
  <span m=''3981160''>the</span> <span m=''3981610''>list.</span> <span m=''3983360''>And</span>
  <span m=''3983600''>by</span> <span m=''3983720''>promise,</span> <span m=''3984250''>technically</span>
  <span m=''3984650''>I mean</span> <span m=''3984950''>procedure.</span> <span m=''3988050''>So</span>
  <span m=''3988180''>it</span> <span m=''3988250''>doesn''t</span> <span m=''3988510''>get</span>
  <span m=''3988670''>built</span> <span m=''3988900''>up.</span> <span m=''3990485''>Yeah,</span>
  <span m=''3990970''>I</span> <span m=''3991100''>should</span> <span m=''3991250''>have</span>
  <span m=''3991330''>said</span> <span m=''3991570''>that</span> <span m=''3992000''>before</span>
  <span m=''3992490''>this</span> <span m=''3992660''>point.</span> <span m=''3994280''>OK.</span>
  <span m=''3994490''>Thank</span> <span m=''3994690''>you.</span> <span m=''3994790''>Let''s</span>
  <span m=''3994850''>take</span> <span m=''3995050''>a</span> <span m=''3995090''>break.</span>
  </p>'
type: course
uid: 4deb9a54f9169779089387b55bd5135a

---
None