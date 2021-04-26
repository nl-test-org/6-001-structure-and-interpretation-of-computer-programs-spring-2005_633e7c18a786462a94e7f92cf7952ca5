---
about_this_resource_text: <p><b>Topics covered:</b> Explicit-control Evaluator</p>
  <p><b> Instructors:</b> Hal Abelson and Gerald Jay Sussman</p> <p>Subtitles for
  this course are provided through the generous assistance of Henry Baker, Hoofar
  Pourzand, Heather Wood, Aleksejs Truhans, Steven Edwards, George Menhorn, and Mahendra
  Kumar.</p>
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
embedded_media:
- id: 9B.jpg
  parent_uid: a319abbcf6a2fe7c484dfd8f46d49886
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/9b-explicit-control-evaluator/9B.jpg
  title: 9B.jpg
  type: null
  uid: a3cab0107ecde1cad2a379f164070d23
- id: Video-YouTube-Stream
  media_location: Z8-qWEEwTCk
  parent_uid: a319abbcf6a2fe7c484dfd8f46d49886
  title: Video-YouTube-Stream
  type: Video
  uid: 23ca064407d30efbb89fc84081436a3e
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT_Structure_of_Computer_Programs_1986/lec9b.mp4
  parent_uid: a319abbcf6a2fe7c484dfd8f46d49886
  title: Video-Internet Archive-MP4
  type: Video
  uid: 60711eae7973b10e87d389b9b24f227b
- id: Thumbnail-OCW-JPG
  parent_uid: a319abbcf6a2fe7c484dfd8f46d49886
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 3e69fa1cab7df4afe6d100dbaf6eae0e
- id: 3Play-3PlayYouTubeid-MP4
  media_location: Z8-qWEEwTCk
  parent_uid: a319abbcf6a2fe7c484dfd8f46d49886
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 32a3ba7c8eb6e5933afcad49ba81b1ef
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/Z8-qWEEwTCk/default.jpg
  parent_uid: a319abbcf6a2fe7c484dfd8f46d49886
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 15b1d1b6cbc02f0f2eb675ab3aa6ca83
- id: Z8-qWEEwTCk.srt
  parent_uid: a319abbcf6a2fe7c484dfd8f46d49886
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/9b-explicit-control-evaluator/Z8-qWEEwTCk.srt
  title: 3play caption file
  type: null
  uid: 457fc796dfc51f1b5210db9fe832dfb4
- id: Z8-qWEEwTCk.pdf
  parent_uid: a319abbcf6a2fe7c484dfd8f46d49886
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/9b-explicit-control-evaluator/Z8-qWEEwTCk.pdf
  title: 3play pdf file
  type: null
  uid: 72af89dc6655dbce058b68ea42edebf8
- id: Caption-3Play YouTube id-SRT
  parent_uid: a319abbcf6a2fe7c484dfd8f46d49886
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: f8dcb30e23e793907212a9a195e30c36
- id: Transcript-3Play YouTube id-PDF
  parent_uid: a319abbcf6a2fe7c484dfd8f46d49886
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 9b9aff53a7847c3d1ae2d476b2ecba31
inline_embed_id: 525840269b:explicit-controlevaluator27257690
layout: video
order_index: null
parent_uid: 4fcacad2c29981dd668a6b29822403cc
related_resources_text: ''
short_url: 9b-explicit-control-evaluator
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/9b-explicit-control-evaluator
template_type: Tabbed
title: '9B: Explicit-control Evaluator'
transcript: '<p><span m=''15840''>PROFESSOR:</span> <span m=''16340''>Well,</span>
  <span m=''16500''>I</span> <span m=''16570''>hope</span> <span m=''16760''>you</span>
  <span m=''16870''>appreciate</span> <span m=''17430''>that</span> <span m=''19980''>we</span>
  <span m=''20160''>have</span> <span m=''20260''>inducted</span> <span m=''20890''>you</span>
  <span m=''21050''>into</span> <span m=''21260''>some</span> <span m=''22050''>real</span>
  <span m=''22230''>magic,</span> <span m=''24760''>the</span> <span m=''24900''>magic</span>
  <span m=''26270''>of</span> <span m=''26370''>building</span> <span m=''26690''>languages,</span>
  <span m=''27510''>really</span> <span m=''27760''>building</span> <span m=''28070''>new</span>
  <span m=''28160''>languages.</span> <span m=''29730''>What</span> <span m=''29860''>have</span>
  <span m=''29930''>we</span> <span m=''30070''>looked</span> <span m=''30320''>at?</span>
  <span m=''30430''>We''ve</span> <span m=''30600''>looked</span> <span m=''30850''>at</span>
  <span m=''31550''>an</span> <span m=''31690''>Escher</span> <span m=''31990''>picture</span>
  <span m=''32299''>language:</span> <span m=''39200''>this</span> <span m=''39390''>language</span>
  <span m=''39710''>invented</span> <span m=''40030''>by</span> <span m=''40150''>Peter</span>
  <span m=''40430''>Henderson.</span> <span m=''42360''>We</span> <span m=''42500''>looked</span>
  <span m=''42780''>at</span> <span m=''45340''>digital</span> <span m=''45660''>logic</span>
  <span m=''45990''>language.</span> <span m=''53260''>Let''s</span> <span m=''53460''>see.</span>
  <span m=''53570''>We''ve</span> <span m=''53750''>looked</span> <span m=''54010''>at</span>
  <span m=''54340''>the</span> <span m=''54840''>query</span> <span m=''55100''>language.</span>
  </p><p><span m=''59700''>And</span> <span m=''59980''>the</span> <span m=''60040''>thing</span>
  <span m=''60100''>you</span> <span m=''60180''>should</span> <span m=''60340''>realize</span>
  <span m=''60700''>is,</span> <span m=''60810''>even</span> <span m=''61010''>though</span>
  <span m=''61390''>these</span> <span m=''61570''>were</span> <span m=''62130''>toy</span>
  <span m=''62440''>examples,</span> <span m=''64730''>they</span> <span m=''64910''>really</span>
  <span m=''65170''>are</span> <span m=''65530''>the</span> <span m=''65690''>kernels</span>
  <span m=''66140''>of</span> <span m=''66270''>really</span> <span m=''66760''>useful</span>
  <span m=''67130''>things.</span> <span m=''68250''>So,</span> <span m=''68520''>for</span>
  <span m=''68710''>instance,</span> <span m=''70190''>the</span> <span m=''70300''>Escher</span>
  <span m=''70530''>picture</span> <span m=''70840''>language</span> <span m=''71220''>was</span>
  <span m=''71340''>taken</span> <span m=''72380''>by</span> <span m=''72520''>Henry</span>
  <span m=''72830''>Wu,</span> <span m=''73120''>who''s</span> <span m=''73290''>a</span>
  <span m=''73340''>student</span> <span m=''73620''>at</span> <span m=''73690''>MIT,</span>
  <span m=''74900''>and</span> <span m=''75150''>developed</span> <span m=''75580''>into</span>
  <span m=''76720''>a</span> <span m=''77150''>real</span> <span m=''77320''>language</span>
  <span m=''77680''>for</span> <span m=''78460''>laying</span> <span m=''78730''>out</span>
  <span m=''78810''>PC</span> <span m=''79090''>boards</span> <span m=''80650''>based</span>
  <span m=''81050''>just</span> <span m=''81300''>on</span> <span m=''81380''>extending</span>
  <span m=''81840''>those</span> <span m=''81980''>structures.</span> <span m=''83300''>And</span>
  <span m=''83540''>the</span> <span m=''83620''>digital</span> <span m=''83940''>logic</span>
  <span m=''84310''>language,</span> <span m=''84670''>Jerry</span> <span m=''84890''>mentioned</span>
  <span m=''85220''>when</span> <span m=''85320''>he</span> <span m=''85380''>showed</span>
  <span m=''85610''>it</span> <span m=''85700''>to</span> <span m=''85800''>you,</span>
  <span m=''86450''>was</span> <span m=''86590''>really</span> <span m=''86870''>extended</span>
  <span m=''87320''>to</span> <span m=''87410''>be</span> <span m=''87510''>used</span>
  <span m=''87810''>as</span> <span m=''88550''>the</span> <span m=''88650''>basis</span>
  <span m=''89070''>for</span> <span m=''89140''>a</span> <span m=''89210''>simulator</span>
  <span m=''90950''>that</span> <span m=''91580''>was</span> <span m=''91780''>used</span>
  <span m=''91960''>to</span> <span m=''92050''>design</span> <span m=''92340''>a</span>
  <span m=''92370''>real</span> <span m=''92540''>computer.</span> <span m=''93460''>And</span>
  <span m=''93590''>the</span> <span m=''93660''>query</span> <span m=''93930''>language,</span>
  <span m=''94280''>of</span> <span m=''94340''>course,</span> <span m=''94600''>is</span>
  <span m=''94720''>kind</span> <span m=''94900''>of</span> <span m=''94960''>the</span>
  <span m=''95620''>germ</span> <span m=''95790''>of</span> <span m=''95960''>prologue.</span>
  </p><p><span m=''97510''>So</span> <span m=''97670''>we</span> <span m=''97770''>built</span>
  <span m=''98030''>all</span> <span m=''98200''>of</span> <span m=''98290''>these</span>
  <span m=''98450''>languages,</span> <span m=''99640''>they''re</span> <span m=''99830''>all</span>
  <span m=''99900''>based</span> <span m=''100170''>on</span> <span m=''100280''>LISP.</span>
  <span m=''103630''>A</span> <span m=''103760''>lot</span> <span m=''103960''>of</span>
  <span m=''104010''>people</span> <span m=''104340''>ask</span> <span m=''105330''>what</span>
  <span m=''106310''>particular</span> <span m=''107220''>problems</span> <span m=''107700''>is</span>
  <span m=''107830''>LISP</span> <span m=''108010''>good</span> <span m=''108200''>for</span>
  <span m=''108340''>solving</span> <span m=''108690''>for?</span> <span m=''108820''>The</span>
  <span m=''108960''>answer</span> <span m=''109125''>is</span> <span m=''110380''>LISP</span>
  <span m=''110560''>is</span> <span m=''110720''>not</span> <span m=''110930''>good</span>
  <span m=''111060''>for</span> <span m=''111210''>solving</span> <span m=''111540''>any</span>
  <span m=''111690''>particular</span> <span m=''112150''>problems.</span> <span m=''113550''>What</span>
  <span m=''113690''>LISP</span> <span m=''113950''>is</span> <span m=''114070''>good</span>
  <span m=''114250''>for</span> <span m=''114780''>is</span> <span m=''114970''>constructing</span>
  <span m=''115620''>within</span> <span m=''116120''>it</span> <span m=''116340''>the</span>
  <span m=''116430''>right</span> <span m=''116740''>language</span> <span m=''117170''>to</span>
  <span m=''117240''>solve</span> <span m=''117490''>the</span> <span m=''117560''>problems</span>
  <span m=''117890''>you</span> <span m=''117990''>want</span> <span m=''118100''>to</span>
  <span m=''118140''>solve,</span> <span m=''119310''>and</span> <span m=''119400''>that''s</span>
  <span m=''119490''>how</span> <span m=''119580''>you</span> <span m=''119715''>should</span>
  <span m=''119850''>think</span> <span m=''120050''>about</span> <span m=''120150''>it.</span>
  </p><p><span m=''121470''>So</span> <span m=''121670''>all</span> <span m=''121790''>of</span>
  <span m=''121920''>these</span> <span m=''122090''>languages</span> <span m=''122530''>were</span>
  <span m=''122630''>based</span> <span m=''122960''>on</span> <span m=''123090''>LISP.</span>
  <span m=''124326''>Now,</span> <span m=''124740''>what''s</span> <span m=''124910''>LISP</span>
  <span m=''125160''>based</span> <span m=''125460''>on?</span> <span m=''127270''>Where''s</span>
  <span m=''127390''>that</span> <span m=''127510''>come</span> <span m=''127720''>from?</span>
  <span m=''127920''>Well,</span> <span m=''128560''>we</span> <span m=''128639''>looked</span>
  <span m=''128830''>at</span> <span m=''128889''>that</span> <span m=''129150''>too.</span>
  <span m=''132740''>We</span> <span m=''133070''>looked</span> <span m=''133270''>at</span>
  <span m=''133370''>the</span> <span m=''134630''>meta-circular</span> <span m=''135410''>evaluator</span>
  <span m=''142840''>and</span> <span m=''143000''>said</span> <span m=''143390''>well,</span>
  <span m=''143460''>LISP</span> <span m=''143760''>is</span> <span m=''143870''>based</span>
  <span m=''145200''>on</span> <span m=''145360''>LISP.</span> <span m=''145810''>And</span>
  <span m=''146280''>when</span> <span m=''146400''>we</span> <span m=''146480''>start</span>
  <span m=''146760''>looking</span> <span m=''147020''>at</span> <span m=''147100''>that,</span>
  <span m=''148340''>we''ve</span> <span m=''148450''>got</span> <span m=''148560''>to</span>
  <span m=''148635''>do</span> <span m=''148710''>some</span> <span m=''148910''>real</span>
  <span m=''149100''>magic,</span> <span m=''149770''>right?</span> <span m=''149950''>So</span>
  <span m=''150070''>what</span> <span m=''150200''>does</span> <span m=''150400''>that</span>
  <span m=''150600''>mean,</span> <span m=''151265''>right?</span> <span m=''151660''>Why</span>
  <span m=''152020''>operators,</span> <span m=''153910''>and</span> <span m=''154050''>fixed</span>
  <span m=''154380''>points,</span> <span m=''155770''>and</span> <span m=''156080''>the</span>
  <span m=''156210''>idea</span> <span m=''156600''>that</span> <span m=''157500''>what</span>
  <span m=''157730''>this</span> <span m=''157900''>means</span> <span m=''158220''>is</span>
  <span m=''158330''>that</span> <span m=''158480''>LISP</span> <span m=''158780''>is</span>
  <span m=''158860''>somehow</span> <span m=''159820''>the</span> <span m=''159930''>fixed-point</span>
  <span m=''160460''>equation</span> <span m=''162190''>for</span> <span m=''162360''>this</span>
  <span m=''162670''>funny</span> <span m=''163230''>set</span> <span m=''163480''>of</span>
  <span m=''163600''>things</span> <span m=''163880''>which</span> <span m=''164050''>are</span>
  <span m=''164100''>defined</span> <span m=''164500''>in</span> <span m=''164600''>terms</span>
  <span m=''164840''>of</span> <span m=''164900''>themselves.</span> <span m=''167470''>Now,</span>
  <span m=''167580''>it''s</span> <span m=''167920''>real</span> <span m=''168080''>magic.</span>
  </p><p><span m=''169070''>Well,</span> <span m=''170250''>today,</span> <span m=''171170''>for</span>
  <span m=''171350''>a</span> <span m=''171390''>final</span> <span m=''171660''>piece</span>
  <span m=''171860''>of</span> <span m=''171930''>magic,</span> <span m=''172520''>we''re</span>
  <span m=''172603''>going</span> <span m=''172686''>to</span> <span m=''172770''>make</span>
  <span m=''173000''>all</span> <span m=''173090''>the</span> <span m=''173180''>magic</span>
  <span m=''173470''>go</span> <span m=''173650''>away.</span> <span m=''186430''>We</span>
  <span m=''186970''>already</span> <span m=''187170''>know</span> <span m=''187290''>how</span>
  <span m=''187390''>to</span> <span m=''187500''>do</span> <span m=''187640''>that.</span>
  <span m=''189770''>The</span> <span m=''189890''>idea</span> <span m=''190090''>is,</span>
  <span m=''190170''>we''re</span> <span m=''190270''>going</span> <span m=''190360''>to</span>
  <span m=''190420''>take</span> <span m=''191180''>the</span> <span m=''191270''>register</span>
  <span m=''191690''>machine</span> <span m=''191970''>architecture</span> <span m=''193420''>and</span>
  <span m=''193580''>show</span> <span m=''193740''>how</span> <span m=''193840''>to</span>
  <span m=''193920''>implement</span> <span m=''194380''>LISP</span> <span m=''194660''>on</span>
  <span m=''194900''>terms</span> <span m=''195180''>of</span> <span m=''195240''>that.</span>
  <span m=''195500''>And,</span> <span m=''195642''>remember,</span> <span m=''196410''>the</span>
  <span m=''196540''>idea</span> <span m=''196820''>of</span> <span m=''196890''>the</span>
  <span m=''196970''>register</span> <span m=''197360''>machine</span> <span m=''199620''>is</span>
  <span m=''199810''>that</span> <span m=''202640''>there''s</span> <span m=''202850''>a</span>
  <span m=''202900''>fixed</span> <span m=''203155''>and</span> <span m=''203410''>finite</span>
  <span m=''203900''>part</span> <span m=''204120''>of</span> <span m=''204180''>the</span>
  <span m=''204260''>machine.</span> <span m=''204800''>There''s</span> <span m=''204970''>a</span>
  <span m=''205020''>finite-state</span> <span m=''205620''>controller,</span> <span
  m=''206100''>which</span> <span m=''206270''>does</span> <span m=''206410''>some</span>
  <span m=''207050''>particular</span> <span m=''207630''>thing</span> <span m=''207860''>with</span>
  <span m=''207940''>a</span> <span m=''208020''>particular</span> <span m=''208500''>amount</span>
  <span m=''208720''>of</span> <span m=''208790''>hardware.</span> <span m=''210510''>There</span>
  <span m=''210570''>are</span> <span m=''210630''>particular</span> <span m=''211110''>data</span>
  <span m=''211390''>paths:</span> <span m=''211720''>the</span> <span m=''211820''>operation</span>
  <span m=''212400''>the</span> <span m=''212470''>machine</span> <span m=''212830''>does.</span>
  <span m=''213550''>And</span> <span m=''213730''>then,</span> <span m=''213950''>in</span>
  <span m=''214090''>order</span> <span m=''214250''>to</span> <span m=''214290''>implement</span>
  <span m=''214980''>recursion</span> <span m=''215580''>and</span> <span m=''215780''>sustain</span>
  <span m=''216330''>the</span> <span m=''216450''>illusion</span> <span m=''216810''>of</span>
  <span m=''216870''>infinity,</span> <span m=''217850''>there''s</span> <span m=''218030''>some</span>
  <span m=''218190''>large</span> <span m=''218460''>amount</span> <span m=''218680''>of</span>
  <span m=''218730''>memory,</span> <span m=''219050''>which</span> <span m=''219230''>is</span>
  <span m=''219330''>the</span> <span m=''219390''>stack.</span> </p><p><span m=''222060''>So,</span>
  <span m=''222270''>if</span> <span m=''222320''>we</span> <span m=''222450''>implement</span>
  <span m=''223270''>LISP</span> <span m=''223910''>in</span> <span m=''224120''>terms</span>
  <span m=''224390''>of</span> <span m=''224470''>a</span> <span m=''224550''>register</span>
  <span m=''224940''>machine,</span> <span m=''227280''>then</span> <span m=''227500''>everything</span>
  <span m=''227740''>ought</span> <span m=''227870''>to</span> <span m=''227910''>become,</span>
  <span m=''228410''>at</span> <span m=''228560''>this</span> <span m=''228720''>point,</span>
  <span m=''228900''>completely</span> <span m=''229390''>concrete.</span> <span m=''229850''>All</span>
  <span m=''230070''>the</span> <span m=''230150''>magic</span> <span m=''230520''>should</span>
  <span m=''230690''>go</span> <span m=''230880''>away.</span> <span m=''231650''>And,</span>
  <span m=''232110''>by</span> <span m=''232350''>the</span> <span m=''232480''>end</span>
  <span m=''232620''>of</span> <span m=''233090''>this</span> <span m=''233310''>talk,</span>
  <span m=''233610''>I</span> <span m=''233640''>want</span> <span m=''233850''>you</span>
  <span m=''234010''>get</span> <span m=''234160''>the</span> <span m=''234240''>feeling</span>
  <span m=''235140''>that,</span> <span m=''235270''>as</span> <span m=''235370''>opposed</span>
  <span m=''235700''>to</span> <span m=''235770''>this</span> <span m=''237040''>very</span>
  <span m=''237280''>mysterious</span> <span m=''237980''>meta-circular</span> <span
  m=''238400''>evaluator,</span> <span m=''239750''>that</span> <span m=''239880''>a</span>
  <span m=''239940''>LISP</span> <span m=''240190''>evaluator</span> <span m=''240630''>really</span>
  <span m=''240970''>is</span> <span m=''241070''>something</span> <span m=''241630''>that''s</span>
  <span m=''241840''>concrete</span> <span m=''242300''>enough</span> <span m=''242900''>that</span>
  <span m=''243090''>you</span> <span m=''243200''>can</span> <span m=''243310''>hold</span>
  <span m=''243590''>in</span> <span m=''243660''>the</span> <span m=''243740''>palm</span>
  <span m=''244030''>of</span> <span m=''244110''>your</span> <span m=''244210''>hand.</span>
  <span m=''244720''>You</span> <span m=''244780''>should</span> <span m=''244870''>be</span>
  <span m=''244970''>able</span> <span m=''245080''>to</span> <span m=''245280''>imagine</span>
  <span m=''246580''>holding</span> <span m=''246890''>a</span> <span m=''246950''>LISP</span>
  <span m=''247150''>interpreter</span> <span m=''247590''>there.</span> </p><p><span
  m=''249546''>All</span> <span m=''249758''>right,</span> <span m=''249970''>how</span>
  <span m=''250160''>are</span> <span m=''250205''>we</span> <span m=''250250''>going</span>
  <span m=''250340''>to</span> <span m=''250430''>do</span> <span m=''250580''>this?</span>
  <span m=''250950''>We</span> <span m=''251150''>already</span> <span m=''251640''>have</span>
  <span m=''251890''>all</span> <span m=''252090''>the</span> <span m=''252210''>ingredients.</span>
  <span m=''253960''>See,</span> <span m=''255270''>what</span> <span m=''255430''>you</span>
  <span m=''255580''>learned</span> <span m=''255840''>last</span> <span m=''256190''>time</span>
  <span m=''256750''>from</span> <span m=''256930''>Jerry</span> <span m=''257610''>is</span>
  <span m=''257860''>how</span> <span m=''257959''>to</span> <span m=''258060''>take</span>
  <span m=''258300''>any</span> <span m=''258880''>particular</span> <span m=''259820''>couple</span>
  <span m=''260260''>of</span> <span m=''260380''>LISP</span> <span m=''260769''>procedures</span>
  <span m=''262760''>and</span> <span m=''262880''>hand-translate</span> <span m=''263980''>them</span>
  <span m=''264840''>into</span> <span m=''265050''>something</span> <span m=''265350''>that</span>
  <span m=''265480''>runs</span> <span m=''265700''>on</span> <span m=''265820''>a</span>
  <span m=''265850''>register</span> <span m=''266260''>machine.</span> <span m=''268210''>So,</span>
  <span m=''268380''>to</span> <span m=''268460''>implement</span> <span m=''268910''>all</span>
  <span m=''269170''>of</span> <span m=''269280''>LISP</span> <span m=''269600''>on</span>
  <span m=''269670''>a</span> <span m=''269740''>register</span> <span m=''270100''>machine,</span>
  <span m=''270500''>all</span> <span m=''270780''>we</span> <span m=''270900''>have</span>
  <span m=''271060''>to</span> <span m=''271160''>do</span> <span m=''271680''>is</span>
  <span m=''271870''>take</span> <span m=''272090''>the</span> <span m=''272160''>particular</span>
  <span m=''272790''>procedures</span> <span m=''273740''>that</span> <span m=''273870''>are</span>
  <span m=''274010''>the</span> <span m=''274120''>meta-circular</span> <span m=''274790''>evaluator</span>
  <span m=''276220''>and</span> <span m=''276370''>hand-translate</span> <span m=''277030''>them</span>
  <span m=''277160''>for</span> <span m=''277400''>a</span> <span m=''277450''>register</span>
  <span m=''277745''>machine.</span> <span m=''279120''>And</span> <span m=''279240''>that</span>
  <span m=''279370''>does</span> <span m=''279540''>all</span> <span m=''279700''>of</span>
  <span m=''279870''>LISP,</span> <span m=''281916''>right?</span> <span m=''282320''>So,</span>
  <span m=''282480''>in</span> <span m=''282560''>principle,</span> <span m=''282900''>we</span>
  <span m=''283010''>already</span> <span m=''283460''>know</span> <span m=''283610''>how</span>
  <span m=''283720''>to</span> <span m=''283830''>do</span> <span m=''284030''>this.</span>
  <span m=''285380''>And,</span> <span m=''285530''>indeed,</span> <span m=''285760''>it''s</span>
  <span m=''285940''>going</span> <span m=''286040''>to</span> <span m=''286080''>be</span>
  <span m=''286800''>no</span> <span m=''287000''>different,</span> <span m=''288060''>in</span>
  <span m=''288252''>kind,</span> <span m=''291480''>from</span> <span m=''291640''>translating,</span>
  <span m=''292160''>say,</span> <span m=''292300''>recursive</span> <span m=''292800''>factorial</span>
  <span m=''293430''>or</span> <span m=''293490''>recursive</span> <span m=''293930''>Fibonacci.</span>
  <span m=''294670''>It''s</span> <span m=''294810''>just</span> <span m=''294980''>bigger</span>
  <span m=''295340''>and</span> <span m=''295430''>there''s</span> <span m=''295520''>more</span>
  <span m=''295770''>of</span> <span m=''295860''>it.</span> <span m=''296840''>So</span>
  <span m=''297060''>it''d</span> <span m=''297135''>just</span> <span m=''297210''>be</span>
  <span m=''297310''>more</span> <span m=''297550''>details,</span> <span m=''298020''>but</span>
  <span m=''298140''>nothing</span> <span m=''298420''>really</span> <span m=''298760''>conceptually</span>
  <span m=''299370''>new.</span> </p><p><span m=''301730''>All</span> <span m=''301790''>right,</span>
  <span m=''301850''>also,</span> <span m=''302190''>when</span> <span m=''302340''>we''ve</span>
  <span m=''302520''>done</span> <span m=''302760''>that,</span> <span m=''303100''>and</span>
  <span m=''303220''>the</span> <span m=''303290''>thing</span> <span m=''303480''>is</span>
  <span m=''303600''>completely</span> <span m=''304190''>explicit,</span> <span m=''304990''>and</span>
  <span m=''305120''>we</span> <span m=''305220''>see</span> <span m=''305980''>how</span>
  <span m=''306080''>to</span> <span m=''306180''>implement</span> <span m=''306660''>LISP</span>
  <span m=''306900''>in</span> <span m=''306990''>terms</span> <span m=''307260''>of</span>
  <span m=''307320''>the</span> <span m=''307380''>actual</span> <span m=''307960''>sequential</span>
  <span m=''308760''>register</span> <span m=''309260''>operations,</span> <span m=''310230''>that''s</span>
  <span m=''310510''>going</span> <span m=''310570''>to</span> <span m=''310640''>be</span>
  <span m=''310770''>our</span> <span m=''310910''>final</span> <span m=''311980''>most</span>
  <span m=''312390''>explicit</span> <span m=''312780''>model</span> <span m=''313110''>of</span>
  <span m=''313230''>LISP</span> <span m=''313470''>in</span> <span m=''313550''>this</span>
  <span m=''313720''>course.</span> <span m=''314810''>And,</span> <span m=''314920''>remember,</span>
  <span m=''315270''>that''s</span> <span m=''315810''>a</span> <span m=''315900''>progression</span>
  <span m=''316410''>through</span> <span m=''316540''>this</span> <span m=''316720''>course.</span>
  <span m=''316950''>We</span> <span m=''317040''>started</span> <span m=''317370''>out</span>
  <span m=''317480''>with</span> <span m=''317590''>substitution,</span> <span m=''318320''>which</span>
  <span m=''318470''>is</span> <span m=''318550''>sort</span> <span m=''318720''>of</span>
  <span m=''318790''>like</span> <span m=''319000''>algebra.</span> <span m=''320370''>And</span>
  <span m=''320540''>then</span> <span m=''320630''>we</span> <span m=''320730''>went</span>
  <span m=''320870''>to</span> <span m=''320940''>the</span> <span m=''321060''>environment</span>
  <span m=''321590''>model,</span> <span m=''321900''>which</span> <span m=''322070''>talked</span>
  <span m=''322280''>about</span> <span m=''322460''>the</span> <span m=''322570''>actual</span>
  <span m=''323530''>frames</span> <span m=''324020''>and</span> <span m=''324080''>how</span>
  <span m=''324230''>they</span> <span m=''324330''>got</span> <span m=''324490''>linked</span>
  <span m=''324700''>together.</span> <span m=''326390''>And</span> <span m=''326510''>then</span>
  <span m=''326610''>we</span> <span m=''326700''>made</span> <span m=''326910''>that</span>
  <span m=''327090''>more</span> <span m=''327360''>concrete</span> <span m=''327900''>in</span>
  <span m=''328020''>the</span> <span m=''328100''>meta-circular</span> <span m=''328740''>evaluator.</span>
  </p><p><span m=''331080''>There</span> <span m=''331180''>are</span> <span m=''331210''>things</span>
  <span m=''331910''>the</span> <span m=''332180''>meta-circular</span> <span m=''332670''>evaluator</span>
  <span m=''333120''>doesn''t</span> <span m=''333450''>tell</span> <span m=''333670''>us.</span>
  <span m=''334360''>You</span> <span m=''334470''>should</span> <span m=''334640''>realize</span>
  <span m=''335090''>that.</span> <span m=''336090''>For</span> <span m=''336240''>instance,</span>
  <span m=''336710''>it</span> <span m=''336880''>left</span> <span m=''337160''>unanswered</span>
  <span m=''337960''>the</span> <span m=''338080''>question</span> <span m=''338770''>of</span>
  <span m=''338920''>how</span> <span m=''340420''>a</span> <span m=''340530''>procedure,</span>
  <span m=''340980''>like</span> <span m=''341200''>recursive</span> <span m=''341730''>factorial</span>
  <span m=''342420''>here</span> <span m=''342670''>,</span> <span m=''345250''>somehow</span>
  <span m=''345840''>takes</span> <span m=''346100''>space</span> <span m=''346440''>that</span>
  <span m=''346600''>grows.</span> <span m=''347210''>On</span> <span m=''347380''>the</span>
  <span m=''347520''>other</span> <span m=''347670''>hand,</span> <span m=''348170''>a</span>
  <span m=''348270''>procedure</span> <span m=''348770''>which</span> <span m=''349850''>also</span>
  <span m=''350190''>looks</span> <span m=''350450''>syntactically</span> <span m=''351160''>recursive,</span>
  <span m=''352160''>called</span> <span m=''352380''>fact-iter,</span> <span m=''353860''>somehow</span>
  <span m=''354110''>doesn''t</span> <span m=''354520''>take</span> <span m=''354770''>space.</span>
  <span m=''356760''>We</span> <span m=''356940''>justify</span> <span m=''357550''>that</span>
  <span m=''357720''>it</span> <span m=''357800''>doesn''t</span> <span m=''358080''>need</span>
  <span m=''358350''>to</span> <span m=''358440''>take</span> <span m=''358710''>space</span>
  <span m=''360580''>by</span> <span m=''360750''>showing</span> <span m=''361040''>the</span>
  <span m=''361120''>substitution</span> <span m=''361730''>model.</span> <span m=''361960''>But</span>
  <span m=''362080''>we</span> <span m=''362180''>didn''t</span> <span m=''362400''>really</span>
  <span m=''362680''>say</span> <span m=''363570''>how</span> <span m=''363880''>it</span>
  <span m=''364090''>happens</span> <span m=''364540''>that</span> <span m=''364700''>the</span>
  <span m=''364780''>machine</span> <span m=''365550''>manages</span> <span m=''366120''>to</span>
  <span m=''366230''>do</span> <span m=''366390''>that,</span> <span m=''367580''>that</span>
  <span m=''367650''>that</span> <span m=''367720''>has</span> <span m=''367870''>to</span>
  <span m=''367960''>do</span> <span m=''368090''>with</span> <span m=''368220''>the</span>
  <span m=''368280''>details</span> <span m=''369100''>of</span> <span m=''369210''>how</span>
  <span m=''369400''>arguments</span> <span m=''369940''>are</span> <span m=''370040''>passed</span>
  <span m=''370390''>to</span> <span m=''370480''>procedures.</span> <span m=''372520''>And</span>
  <span m=''372650''>that''s</span> <span m=''372790''>the</span> <span m=''372890''>thing</span>
  <span m=''372990''>we</span> <span m=''373090''>didn''t</span> <span m=''373400''>see</span>
  <span m=''373820''>in</span> <span m=''373970''>the</span> <span m=''374040''>meta-circular</span>
  <span m=''374710''>evaluator</span> <span m=''375260''>precisely</span> <span m=''375810''>because</span>
  <span m=''376510''>the</span> <span m=''376650''>way</span> <span m=''376900''>arguments</span>
  <span m=''377410''>got</span> <span m=''377610''>passed</span> <span m=''377930''>to</span>
  <span m=''378010''>procedures</span> <span m=''378550''>in</span> <span m=''378640''>this</span>
  <span m=''378810''>LISP</span> <span m=''379810''>depended</span> <span m=''380230''>on</span>
  <span m=''381080''>the</span> <span m=''381180''>way</span> <span m=''381330''>arguments</span>
  <span m=''381840''>got</span> <span m=''382070''>passed</span> <span m=''382245''>to</span>
  <span m=''382420''>procedures</span> <span m=''382880''>in</span> <span m=''382990''>this</span>
  <span m=''383190''>LISP.</span> <span m=''386070''>But,</span> <span m=''386220''>now,</span>
  <span m=''386380''>that''s</span> <span m=''386580''>going</span> <span m=''386670''>to</span>
  <span m=''387680''>become</span> <span m=''387960''>extremely</span> <span m=''388460''>explicit.</span>
  </p><p><span m=''390740''>OK.</span> <span m=''391230''>Well,</span> <span m=''391430''>before</span>
  <span m=''392330''>going</span> <span m=''392650''>on</span> <span m=''392820''>to</span>
  <span m=''393620''>the</span> <span m=''393800''>evaluator,</span> <span m=''394490''>let</span>
  <span m=''394600''>me</span> <span m=''394690''>just</span> <span m=''394860''>give</span>
  <span m=''395000''>you</span> <span m=''395100''>a</span> <span m=''395130''>sense</span>
  <span m=''395460''>of</span> <span m=''395530''>what</span> <span m=''395640''>a</span>
  <span m=''395670''>whole</span> <span m=''395930''>LISP</span> <span m=''396190''>system</span>
  <span m=''396500''>looks</span> <span m=''396750''>like</span> <span m=''397660''>so</span>
  <span m=''397810''>you</span> <span m=''397940''>can</span> <span m=''398080''>see</span>
  <span m=''398220''>the</span> <span m=''398310''>parts</span> <span m=''398590''>we''re</span>
  <span m=''398680''>going</span> <span m=''398760''>to</span> <span m=''398850''>talk</span>
  <span m=''399090''>about</span> <span m=''399370''>and</span> <span m=''399420''>the</span>
  <span m=''399470''>parts</span> <span m=''399730''>we''re</span> <span m=''399840''>not</span>
  <span m=''400040''>going</span> <span m=''400130''>to</span> <span m=''400200''>talk</span>
  <span m=''400450''>about.</span> <span m=''403250''>Let''s</span> <span m=''403380''>see,</span>
  <span m=''403490''>over</span> <span m=''403660''>here</span> <span m=''406120''>is</span>
  <span m=''406270''>a</span> <span m=''406300''>happy</span> <span m=''406660''>LISP</span>
  <span m=''406920''>user,</span> <span m=''408780''>and</span> <span m=''408950''>the</span>
  <span m=''409020''>LISP</span> <span m=''409240''>user</span> <span m=''410070''>is</span>
  <span m=''410240''>talking</span> <span m=''410620''>to</span> <span m=''410730''>something</span>
  <span m=''411910''>called</span> <span m=''412170''>the</span> <span m=''412240''>reader.</span>
  <span m=''420360''>The</span> <span m=''420580''>reader''s</span> <span m=''420910''>job</span>
  <span m=''421150''>in</span> <span m=''421230''>life</span> <span m=''421950''>is</span>
  <span m=''422140''>to</span> <span m=''422260''>take</span> <span m=''423366''>characters</span>
  <span m=''432470''>from</span> <span m=''432670''>the</span> <span m=''432760''>user</span>
  <span m=''434170''>and</span> <span m=''434500''>turn</span> <span m=''434790''>them</span>
  <span m=''435030''>into</span> <span m=''435720''>data</span> <span m=''436010''>structures</span>
  <span m=''437290''>in</span> <span m=''437410''>something</span> <span m=''437740''>called</span>
  <span m=''437960''>a</span> <span m=''438020''>list</span> <span m=''438440''>structure</span>
  <span m=''438850''>memory.</span> </p><p><span m=''449783''>All</span> <span m=''450036''>right,</span>
  <span m=''450290''>so</span> <span m=''450790''>the</span> <span m=''450890''>reader</span>
  <span m=''451140''>is</span> <span m=''451220''>going</span> <span m=''451340''>to</span>
  <span m=''451410''>take</span> <span m=''452630''>symbols,</span> <span m=''453110''>parentheses,</span>
  <span m=''453770''>and</span> <span m=''454540''>A''s</span> <span m=''454810''>and</span>
  <span m=''454920''>B''s,</span> <span m=''455240''>and</span> <span m=''455350''>ones</span>
  <span m=''455590''>and</span> <span m=''455720''>threes</span> <span m=''456360''>that</span>
  <span m=''456510''>you</span> <span m=''456600''>type</span> <span m=''456880''>in,</span>
  <span m=''457240''>and</span> <span m=''457420''>turn</span> <span m=''457610''>these</span>
  <span m=''457780''>into</span> <span m=''458030''>actual</span> <span m=''458280''>list</span>
  <span m=''458530''>structure:</span> <span m=''459200''>pairs,</span> <span m=''459460''>and</span>
  <span m=''459660''>pointers,</span> <span m=''460060''>and</span> <span m=''460190''>things.</span>
  <span m=''462340''>And</span> <span m=''462410''>so,</span> <span m=''462480''>by</span>
  <span m=''462590''>the</span> <span m=''462710''>time</span> <span m=''462940''>evaluator</span>
  <span m=''463127''>is</span> <span m=''463690''>going,</span> <span m=''463920''>there</span>
  <span m=''464040''>are</span> <span m=''464110''>no</span> <span m=''464180''>characters</span>
  <span m=''464660''>in</span> <span m=''464730''>the</span> <span m=''464810''>world.</span>
  <span m=''465850''>And,</span> <span m=''465990''>of</span> <span m=''466070''>course,</span>
  <span m=''466340''>in</span> <span m=''466720''>more</span> <span m=''466920''>modern</span>
  <span m=''467280''>list</span> <span m=''467500''>systems,</span> <span m=''469090''>there''s</span>
  <span m=''469210''>sort</span> <span m=''469390''>of</span> <span m=''469480''>a</span>
  <span m=''469520''>big</span> <span m=''469730''>morass</span> <span m=''470210''>here</span>
  <span m=''470380''>that</span> <span m=''470540''>might</span> <span m=''470760''>sit</span>
  <span m=''470930''>between</span> <span m=''471220''>the</span> <span m=''471310''>user</span>
  <span m=''471610''>and</span> <span m=''471680''>the</span> <span m=''471770''>reader:</span>
  <span m=''472530''>Windows</span> <span m=''473010''>systems,</span> <span m=''473530''>and</span>
  <span m=''473640''>top</span> <span m=''473920''>levels,</span> <span m=''474320''>and</span>
  <span m=''474870''>mice,</span> <span m=''475210''>and</span> <span m=''475280''>all</span>
  <span m=''475390''>kinds</span> <span m=''475640''>of</span> <span m=''475720''>things.</span>
  <span m=''476280''>But</span> <span m=''476430''>conceptually,</span> <span m=''476980''>characters</span>
  <span m=''477470''>are</span> <span m=''477550''>coming</span> <span m=''477900''>in.</span>
  </p><p><span m=''479590''>All</span> <span m=''479840''>right,</span> <span m=''480190''>the</span>
  <span m=''480280''>reader</span> <span m=''482820''>transforms</span> <span m=''483380''>these</span>
  <span m=''483580''>into</span> <span m=''485820''>pointers</span> <span m=''486240''>to</span>
  <span m=''486340''>stuff</span> <span m=''486580''>in</span> <span m=''486690''>this</span>
  <span m=''486800''>memory,</span> <span m=''488290''>and</span> <span m=''488450''>that''s</span>
  <span m=''488700''>what</span> <span m=''489810''>the</span> <span m=''489940''>evaluator</span>
  <span m=''490640''>sees,</span> <span m=''495624''>OK?</span> <span m=''497090''>The</span>
  <span m=''497200''>evaluator</span> <span m=''497770''>has</span> <span m=''497990''>a</span>
  <span m=''498040''>bunch</span> <span m=''498280''>of</span> <span m=''498360''>helpers.</span>
  <span m=''499780''>It</span> <span m=''499890''>has</span> <span m=''500180''>all</span>
  <span m=''500440''>possible</span> <span m=''501420''>primitive</span> <span m=''502090''>operators</span>
  <span m=''502570''>you</span> <span m=''502700''>might</span> <span m=''502900''>want.</span>
  <span m=''503080''>So</span> <span m=''503270''>there''s</span> <span m=''503440''>a</span>
  <span m=''503510''>completely</span> <span m=''504010''>separate</span> <span m=''504410''>box,</span>
  <span m=''508740''>a</span> <span m=''508920''>floating</span> <span m=''509320''>point</span>
  <span m=''509610''>unit,</span> <span m=''510000''>or</span> <span m=''512330''>all</span>
  <span m=''512460''>sorts</span> <span m=''512700''>of</span> <span m=''512799''>things,</span>
  <span m=''513030''>which</span> <span m=''513220''>do</span> <span m=''513340''>the</span>
  <span m=''513429''>primitive</span> <span m=''513799''>operators.</span> <span m=''515960''>And,</span>
  <span m=''516299''>if</span> <span m=''516400''>you</span> <span m=''516500''>want</span>
  <span m=''516690''>more</span> <span m=''516929''>special</span> <span m=''517280''>primitives,</span>
  <span m=''517669''>you</span> <span m=''517820''>build</span> <span m=''518070''>more</span>
  <span m=''518240''>primitive</span> <span m=''518590''>operators,</span> <span m=''519090''>but</span>
  <span m=''519190''>they''re</span> <span m=''519309''>separate</span> <span m=''519650''>from</span>
  <span m=''519770''>the</span> <span m=''519840''>evaluator.</span> <span m=''522080''>The</span>
  <span m=''522212''>evaluator</span> <span m=''522679''>finally</span> <span m=''523000''>gets</span>
  <span m=''523210''>an</span> <span m=''523280''>answer</span> <span m=''525190''>and</span>
  <span m=''525350''>communicates</span> <span m=''525960''>that</span> <span m=''526150''>to</span>
  <span m=''526240''>the</span> <span m=''526330''>printer.</span> <span m=''530780''>And</span>
  <span m=''530845''>now,</span> <span m=''530910''>the</span> <span m=''531000''>printer''s</span>
  <span m=''531390''>job</span> <span m=''531650''>in</span> <span m=''531730''>life</span>
  <span m=''532020''>is</span> <span m=''532140''>to</span> <span m=''532250''>take</span>
  <span m=''532510''>this</span> <span m=''532670''>list</span> <span m=''532980''>structure</span>
  <span m=''533390''>coming</span> <span m=''533650''>from</span> <span m=''533790''>the</span>
  <span m=''533880''>evaluator,</span> <span m=''535450''>and</span> <span m=''535610''>turn</span>
  <span m=''535800''>it</span> <span m=''535890''>back</span> <span m=''536150''>into</span>
  <span m=''536340''>characters,</span> <span m=''541910''>and</span> <span m=''542110''>communicate</span>
  <span m=''542630''>them</span> <span m=''542750''>to</span> <span m=''542850''>the</span>
  <span m=''542960''>user</span> <span m=''543630''>through</span> <span m=''544280''>whatever</span>
  <span m=''544650''>interface</span> <span m=''545100''>there</span> <span m=''545290''>is.</span>
  </p><p><span m=''548050''>OK.</span> <span m=''548810''>Well,</span> <span m=''548980''>today,</span>
  <span m=''549530''>what</span> <span m=''549680''>we''re</span> <span m=''549760''>going</span>
  <span m=''549820''>to</span> <span m=''549890''>talk</span> <span m=''550100''>about</span>
  <span m=''550290''>is</span> <span m=''550390''>this</span> <span m=''550550''>evaluator.</span>
  <span m=''552670''>The</span> <span m=''552770''>primitive</span> <span m=''553140''>operators</span>
  <span m=''553640''>have</span> <span m=''553780''>nothing</span> <span m=''554060''>particular</span>
  <span m=''554550''>to</span> <span m=''554630''>do</span> <span m=''554770''>with</span>
  <span m=''554900''>LISP,</span> <span m=''555320''>they''re</span> <span m=''555990''>however</span>
  <span m=''556290''>you</span> <span m=''556410''>like</span> <span m=''556580''>to</span>
  <span m=''556720''>implement</span> <span m=''557090''>primitive</span> <span m=''557430''>operations.</span>
  <span m=''559440''>The</span> <span m=''560600''>reader</span> <span m=''560765''>and</span>
  <span m=''560930''>printer</span> <span m=''561360''>are</span> <span m=''561500''>actually</span>
  <span m=''561640''>complicated,</span> <span m=''562250''>but</span> <span m=''562370''>we''re</span>
  <span m=''562460''>not</span> <span m=''562610''>going</span> <span m=''562710''>to</span>
  <span m=''562760''>talk</span> <span m=''563020''>about</span> <span m=''563300''>them.</span>
  <span m=''564420''>They</span> <span m=''564890''>sort</span> <span m=''565060''>of</span>
  <span m=''565120''>have</span> <span m=''565300''>to</span> <span m=''565400''>do</span>
  <span m=''565540''>with</span> <span m=''565680''>details</span> <span m=''566090''>of</span>
  <span m=''566140''>how</span> <span m=''566210''>you</span> <span m=''566310''>might</span>
  <span m=''567170''>build</span> <span m=''567410''>up</span> <span m=''567530''>list</span>
  <span m=''567660''>structure</span> <span m=''568100''>from</span> <span m=''568250''>characters.</span>
  <span m=''569900''>So</span> <span m=''570240''>that</span> <span m=''570420''>is</span>
  <span m=''570530''>a</span> <span m=''570590''>long</span> <span m=''570860''>story,</span>
  <span m=''571220''>but</span> <span m=''571350''>we''re</span> <span m=''571440''>not</span>
  <span m=''571560''>going</span> <span m=''571650''>to</span> <span m=''571720''>talk</span>
  <span m=''571960''>about</span> <span m=''572150''>it.</span> <span m=''572490''>The</span>
  <span m=''572770''>list</span> <span m=''572950''>structure</span> <span m=''573130''>memory,</span>
  <span m=''574630''>we''ll</span> <span m=''574740''>talk</span> <span m=''574970''>about</span>
  <span m=''575120''>next</span> <span m=''575330''>time.</span> <span m=''576930''>So,</span>
  <span m=''577130''>pretty</span> <span m=''577370''>much,</span> <span m=''577600''>except</span>
  <span m=''577910''>for</span> <span m=''578030''>the</span> <span m=''578140''>details</span>
  <span m=''578690''>of</span> <span m=''578800''>reading</span> <span m=''579070''>and</span>
  <span m=''579170''>printing,</span> <span m=''580230''>the</span> <span m=''580460''>only</span>
  <span m=''580690''>mystery</span> <span m=''581030''>that''s</span> <span m=''581230''>going</span>
  <span m=''581300''>to</span> <span m=''581370''>be</span> <span m=''581500''>left</span>
  <span m=''581760''>after</span> <span m=''581860''>you</span> <span m=''582130''>see</span>
  <span m=''582260''>the</span> <span m=''582390''>evaluator</span> <span m=''583400''>is</span>
  <span m=''583590''>how</span> <span m=''583720''>you</span> <span m=''583920''>build</span>
  <span m=''584290''>list</span> <span m=''584340''>structure</span> <span m=''584810''>on</span>
  <span m=''584950''>conventional</span> <span m=''585420''>memories.</span> <span
  m=''586295''>But</span> <span m=''586497''>we''ll</span> <span m=''586700''>worry</span>
  <span m=''587150''>about</span> <span m=''587350''>that</span> <span m=''587530''>next</span>
  <span m=''587720''>time</span> <span m=''587920''>too.</span> </p><p><span m=''590580''>OK.</span>
  <span m=''593350''>Well,</span> <span m=''594280''>let''s</span> <span m=''594430''>start</span>
  <span m=''594670''>talking</span> <span m=''595060''>about</span> <span m=''595310''>the</span>
  <span m=''595380''>evaluator.</span> <span m=''596110''>The</span> <span m=''596270''>one</span>
  <span m=''597360''>that</span> <span m=''597520''>we''re</span> <span m=''597640''>going</span>
  <span m=''597740''>to</span> <span m=''597780''>show</span> <span m=''598010''>you,</span>
  <span m=''598620''>of</span> <span m=''598750''>course,</span> <span m=''598830''>is</span>
  <span m=''599025''>not,</span> <span m=''599880''>I</span> <span m=''599970''>think,</span>
  <span m=''600160''>nothing</span> <span m=''600430''>special</span> <span m=''600820''>about</span>
  <span m=''600900''>it.</span> <span m=''601120''>It''s</span> <span m=''601280''>just</span>
  <span m=''601470''>a</span> <span m=''601520''>particular</span> <span m=''602560''>register</span>
  <span m=''603040''>machine</span> <span m=''603730''>that</span> <span m=''603890''>runs</span>
  <span m=''604180''>LISP.</span> <span m=''604810''>And</span> <span m=''604990''>it</span>
  <span m=''605040''>has</span> <span m=''605220''>seven</span> <span m=''605510''>registers,</span>
  <span m=''607930''>and</span> <span m=''608110''>here</span> <span m=''608280''>are</span>
  <span m=''608330''>the</span> <span m=''608380''>seven</span> <span m=''608660''>registers.</span>
  <span m=''609890''>There''s</span> <span m=''610080''>a</span> <span m=''610140''>register,</span>
  <span m=''611210''>called</span> <span m=''612030''>EXP,</span> <span m=''614140''>and</span>
  <span m=''614310''>its</span> <span m=''614510''>job</span> <span m=''614820''>is</span>
  <span m=''614950''>to</span> <span m=''615050''>hold</span> <span m=''616430''>the</span>
  <span m=''616550''>expression</span> <span m=''617110''>to</span> <span m=''617210''>be</span>
  <span m=''617380''>evaluated.</span> <span m=''618370''>And</span> <span m=''618520''>by</span>
  <span m=''618880''>that,</span> <span m=''619110''>I</span> <span m=''619340''>mean</span>
  <span m=''620470''>it''s</span> <span m=''620650''>going</span> <span m=''620750''>to</span>
  <span m=''620790''>hold</span> <span m=''620980''>a</span> <span m=''621030''>pointer</span>
  <span m=''622110''>to</span> <span m=''622240''>someplace</span> <span m=''622660''>in</span>
  <span m=''622750''>list</span> <span m=''622840''>structure</span> <span m=''623220''>memory</span>
  <span m=''623570''>that</span> <span m=''623690''>holds</span> <span m=''623950''>the</span>
  <span m=''624040''>expression</span> <span m=''624490''>to</span> <span m=''624560''>be</span>
  <span m=''624690''>evaluated.</span> </p><p><span m=''626550''>There''s</span> <span
  m=''626720''>a</span> <span m=''626770''>register,</span> <span m=''627150''>called</span>
  <span m=''627450''>ENV,</span> <span m=''628910''>which</span> <span m=''629090''>holds</span>
  <span m=''629340''>the</span> <span m=''629490''>environment</span> <span m=''631150''>in</span>
  <span m=''631280''>which</span> <span m=''631470''>this</span> <span m=''631640''>expression</span>
  <span m=''632090''>is</span> <span m=''632190''>to</span> <span m=''632270''>be</span>
  <span m=''632420''>evaluated.</span> <span m=''634070''>And,</span> <span m=''634150''>again,</span>
  <span m=''634350''>I</span> <span m=''634370''>made</span> <span m=''634510''>a</span>
  <span m=''634560''>pointer.</span> <span m=''634940''>The</span> <span m=''635060''>environment</span>
  <span m=''635550''>is</span> <span m=''635620''>some</span> <span m=''635810''>data</span>
  <span m=''636040''>structure.</span> <span m=''638240''>There''s</span> <span m=''638420''>a</span>
  <span m=''638460''>register,</span> <span m=''638780''>called</span> <span m=''638970''>FUN,</span>
  <span m=''640730''>which</span> <span m=''640990''>will</span> <span m=''641100''>hold</span>
  <span m=''641330''>the</span> <span m=''641390''>procedure</span> <span m=''641890''>to</span>
  <span m=''642000''>be</span> <span m=''642130''>applied</span> <span m=''642560''>when</span>
  <span m=''642660''>you</span> <span m=''642760''>go</span> <span m=''642860''>to</span>
  <span m=''642960''>apply</span> <span m=''643250''>a</span> <span m=''643310''>procedure.</span>
  <span m=''644630''>A</span> <span m=''644700''>register,</span> <span m=''645130''>called</span>
  <span m=''645690''>ARGL,</span> <span m=''647490''>which</span> <span m=''647650''>wants</span>
  <span m=''647860''>the</span> <span m=''647940''>list</span> <span m=''648210''>of</span>
  <span m=''648290''>evaluated</span> <span m=''648840''>arguments.</span> </p><p><span
  m=''650630''>What</span> <span m=''650750''>you</span> <span m=''650820''>can</span>
  <span m=''650920''>start</span> <span m=''651170''>seeing</span> <span m=''651390''>here</span>
  <span m=''651530''>is</span> <span m=''651600''>the</span> <span m=''651680''>basic</span>
  <span m=''652060''>structure</span> <span m=''652440''>of</span> <span m=''652530''>the</span>
  <span m=''652682''>evaluator.</span> <span m=''653140''>Remember</span> <span m=''653440''>how</span>
  <span m=''653620''>evaluators</span> <span m=''654250''>work.</span> <span m=''654490''>There''s</span>
  <span m=''654650''>a</span> <span m=''654700''>piece</span> <span m=''654930''>that</span>
  <span m=''655040''>takes</span> <span m=''655280''>expressions</span> <span m=''655570''>and</span>
  <span m=''655860''>environments,</span> <span m=''657670''>and</span> <span m=''657780''>there''s</span>
  <span m=''657930''>a</span> <span m=''657970''>piece</span> <span m=''658200''>that</span>
  <span m=''658350''>takes</span> <span m=''659090''>functions,</span> <span m=''659750''>or</span>
  <span m=''659880''>procedures</span> <span m=''661060''>and</span> <span m=''661550''>arguments.</span>
  <span m=''663480''>And</span> <span m=''663660''>going</span> <span m=''664210''>back</span>
  <span m=''664440''>and</span> <span m=''664550''>forth</span> <span m=''664870''>around</span>
  <span m=''665100''>here</span> <span m=''665230''>is</span> <span m=''665360''>the</span>
  <span m=''665470''>eval/apply</span> <span m=''666040''>loop.</span> <span m=''667740''>So</span>
  <span m=''667760''>those</span> <span m=''667780''>are</span> <span m=''667800''>the</span>
  <span m=''667820''>basic</span> <span m=''668250''>pieces</span> <span m=''668610''>of</span>
  <span m=''668690''>the</span> <span m=''668780''>eval</span> <span m=''668935''>and</span>
  <span m=''669090''>apply.</span> </p><p><span m=''670270''>Then</span> <span m=''670410''>there''s</span>
  <span m=''670520''>some</span> <span m=''670670''>other</span> <span m=''670830''>things,</span>
  <span m=''671020''>there''s</span> <span m=''671190''>continue.</span> <span m=''671610''>You</span>
  <span m=''671740''>just</span> <span m=''671980''>saw</span> <span m=''673400''>before</span>
  <span m=''673740''>how</span> <span m=''673870''>the</span> <span m=''673960''>continue</span>
  <span m=''674430''>register</span> <span m=''674890''>is</span> <span m=''674980''>used</span>
  <span m=''675160''>to</span> <span m=''675340''>implement</span> <span m=''675760''>recursion</span>
  <span m=''676872''>and</span> <span m=''677220''>stack</span> <span m=''677530''>discipline.</span>
  <span m=''679000''>There''s</span> <span m=''679160''>a</span> <span m=''679220''>register</span>
  <span m=''679860''>that''s</span> <span m=''680100''>going</span> <span m=''680200''>to</span>
  <span m=''680240''>hold</span> <span m=''680530''>the</span> <span m=''680970''>result</span>
  <span m=''681430''>of</span> <span m=''681510''>some</span> <span m=''681740''>evaluation.</span>
  <span m=''684190''>And</span> <span m=''684360''>then,</span> <span m=''684540''>besides</span>
  <span m=''684810''>that,</span> <span m=''684920''>there''s</span> <span m=''685080''>one</span>
  <span m=''685450''>temporary</span> <span m=''685890''>register,</span> <span m=''686740''>called</span>
  <span m=''686990''>UNEV,</span> <span m=''687330''>which</span> <span m=''687620''>typically,</span>
  <span m=''688190''>in</span> <span m=''688250''>the</span> <span m=''688310''>evaluator,</span>
  <span m=''689280''>is</span> <span m=''689440''>going</span> <span m=''689550''>to</span>
  <span m=''689600''>be</span> <span m=''689730''>used</span> <span m=''689990''>to</span>
  <span m=''690060''>hold</span> <span m=''690670''>temporary</span> <span m=''691920''>pieces</span>
  <span m=''692280''>of</span> <span m=''692390''>the</span> <span m=''692980''>expression</span>
  <span m=''693440''>you''re</span> <span m=''693570''>working</span> <span m=''693890''>on,</span>
  <span m=''694010''>which</span> <span m=''694130''>you</span> <span m=''694200''>haven''t</span>
  <span m=''694470''>gotten</span> <span m=''694690''>around</span> <span m=''694930''>to</span>
  <span m=''695050''>evaluate</span> <span m=''695550''>yet,</span> <span m=''696680''>right?</span>
  <span m=''697150''>So</span> <span m=''697320''>there''s</span> <span m=''697530''>my</span>
  <span m=''697620''>machine:</span> <span m=''698030''>a</span> <span m=''698250''>seven-register</span>
  <span m=''699170''>machine.</span> <span m=''700646''>And,</span> <span m=''701140''>of</span>
  <span m=''701220''>course,</span> <span m=''701400''>you</span> <span m=''701500''>might</span>
  <span m=''702240''>want</span> <span m=''702400''>to</span> <span m=''702440''>make</span>
  <span m=''702610''>a</span> <span m=''702660''>machine</span> <span m=''702930''>with</span>
  <span m=''703020''>a</span> <span m=''703060''>lot</span> <span m=''703300''>more</span>
  <span m=''703530''>registers</span> <span m=''703960''>to</span> <span m=''704040''>get</span>
  <span m=''704200''>better</span> <span m=''704430''>performance,</span> <span m=''704970''>but</span>
  <span m=''705090''>this</span> <span m=''705250''>is</span> <span m=''705350''>just</span>
  <span m=''706040''>a</span> <span m=''706130''>tiny,</span> <span m=''706440''>minimal</span>
  <span m=''706800''>one.</span> </p><p><span m=''708480''>Well,</span> <span m=''708780''>how</span>
  <span m=''708806''>about</span> <span m=''708833''>the</span> <span m=''708860''>data</span>
  <span m=''709130''>paths?</span> <span m=''709780''>This</span> <span m=''709940''>machine</span>
  <span m=''710220''>has</span> <span m=''710330''>a</span> <span m=''710380''>lot</span>
  <span m=''711480''>of</span> <span m=''711600''>special</span> <span m=''712380''>operations</span>
  <span m=''713180''>for</span> <span m=''713330''>LISP.</span> <span m=''715100''>So,</span>
  <span m=''716250''>here</span> <span m=''716295''>are</span> <span m=''716340''>some</span>
  <span m=''716500''>typical</span> <span m=''717340''>data</span> <span m=''717610''>paths.</span>
  <span m=''720120''>A</span> <span m=''720300''>typical</span> <span m=''720480''>one</span>
  <span m=''720640''>might</span> <span m=''720820''>be,</span> <span m=''721410''>oh,</span>
  <span m=''721580''>assign</span> <span m=''722340''>to</span> <span m=''722570''>the</span>
  <span m=''722650''>VAL</span> <span m=''722940''>register</span> <span m=''723320''>the</span>
  <span m=''723410''>contents</span> <span m=''723890''>of</span> <span m=''723960''>the</span>
  <span m=''724110''>EXP</span> <span m=''724380''>register.</span> <span m=''726710''>In</span>
  <span m=''726780''>terms</span> <span m=''726990''>of</span> <span m=''727040''>those</span>
  <span m=''727190''>diagrams</span> <span m=''727700''>you</span> <span m=''727780''>saw,</span>
  <span m=''727980''>that''s</span> <span m=''728170''>a</span> <span m=''728810''>little</span>
  <span m=''729000''>button</span> <span m=''730050''>on</span> <span m=''730190''>some</span>
  <span m=''730350''>arrow.</span> </p><p><span m=''731900''>Here''s</span> <span
  m=''732040''>a</span> <span m=''732100''>more</span> <span m=''732230''>complicated</span>
  <span m=''732820''>one.</span> <span m=''734040''>It</span> <span m=''734130''>says</span>
  <span m=''734220''>branch,</span> <span m=''735220''>if</span> <span m=''736410''>the</span>
  <span m=''737150''>thing</span> <span m=''737640''>in</span> <span m=''737700''>the</span>
  <span m=''737760''>expression</span> <span m=''738230''>register</span> <span m=''738710''>is</span>
  <span m=''738810''>a</span> <span m=''738870''>conditional</span> <span m=''740520''>to</span>
  <span m=''740640''>some</span> <span m=''740870''>label</span> <span m=''741250''>here,</span>
  <span m=''741420''>called</span> <span m=''741650''>the</span> <span m=''741820''>ev-conditional.</span>
  <span m=''743850''>And</span> <span m=''744000''>you</span> <span m=''744090''>can</span>
  <span m=''744200''>imagine</span> <span m=''744660''>this</span> <span m=''744770''>implemented</span>
  <span m=''745350''>in</span> <span m=''745385''>a</span> <span m=''745420''>lot</span>
  <span m=''745610''>of</span> <span m=''745680''>different</span> <span m=''745960''>ways.</span>
  <span m=''746230''>You</span> <span m=''746340''>might</span> <span m=''746520''>imagine</span>
  <span m=''747330''>this</span> <span m=''747510''>conditional</span> <span m=''748030''>test</span>
  <span m=''748370''>as</span> <span m=''748460''>a</span> <span m=''748500''>special</span>
  <span m=''748950''>purpose</span> <span m=''749360''>sub-routine,</span> <span m=''750740''>and</span>
  <span m=''750880''>conditional</span> <span m=''751870''>might</span> <span m=''752060''>be</span>
  <span m=''752180''>represented</span> <span m=''752710''>as</span> <span m=''752790''>some</span>
  <span m=''753110''>data</span> <span m=''753510''>abstraction</span> <span m=''754060''>that</span>
  <span m=''754150''>you</span> <span m=''754240''>don''t</span> <span m=''754400''>care</span>
  <span m=''754650''>about</span> <span m=''754890''>at</span> <span m=''754970''>this</span>
  <span m=''755150''>level</span> <span m=''755400''>of</span> <span m=''755480''>detail.</span>
  <span m=''756610''>So</span> <span m=''756750''>that</span> <span m=''756860''>might</span>
  <span m=''757010''>be</span> <span m=''757100''>done</span> <span m=''757260''>as</span>
  <span m=''757370''>a</span> <span m=''757420''>sub-routine.</span> <span m=''757980''>This</span>
  <span m=''758120''>might</span> <span m=''758330''>be</span> <span m=''758720''>a</span>
  <span m=''759200''>machine</span> <span m=''759670''>with</span> <span m=''759770''>hardware-types,</span>
  <span m=''761050''>and</span> <span m=''761200''>conditional</span> <span m=''761640''>might</span>
  <span m=''761820''>be</span> <span m=''761930''>testing</span> <span m=''762300''>some</span>
  <span m=''762490''>bits</span> <span m=''762840''>for</span> <span m=''762910''>a</span>
  <span m=''762990''>particular</span> <span m=''763490''>code.</span> <span m=''765350''>There</span>
  <span m=''765425''>are</span> <span m=''765500''>all</span> <span m=''765650''>sorts</span>
  <span m=''765900''>of</span> <span m=''765980''>ways</span> <span m=''766140''>that''s</span>
  <span m=''766370''>beneath</span> <span m=''766830''>the</span> <span m=''766910''>level</span>
  <span m=''767190''>of</span> <span m=''767280''>abstraction</span> <span m=''767800''>we''re</span>
  <span m=''767900''>looking</span> <span m=''768220''>at.</span> </p><p><span m=''770190''>Another</span>
  <span m=''770660''>kind</span> <span m=''771010''>of</span> <span m=''771110''>operation,</span>
  <span m=''771690''>and</span> <span m=''771980''>there</span> <span m=''772010''>are</span>
  <span m=''772040''>a</span> <span m=''772070''>lot</span> <span m=''772260''>of</span>
  <span m=''772370''>different</span> <span m=''772610''>operations</span> <span m=''773310''>assigned</span>
  <span m=''773700''>to</span> <span m=''773780''>EXP,</span> <span m=''774130''>the</span>
  <span m=''774240''>first</span> <span m=''774820''>clause</span> <span m=''775880''>of</span>
  <span m=''776040''>what''s</span> <span m=''776160''>in</span> <span m=''776280''>EXP.</span>
  <span m=''776840''>This</span> <span m=''777010''>might</span> <span m=''777180''>be</span>
  <span m=''777280''>part</span> <span m=''777530''>of</span> <span m=''777610''>processing</span>
  <span m=''778230''>a</span> <span m=''778290''>conditional.</span> <span m=''779260''>And,</span>
  <span m=''779370''>again,</span> <span m=''779560''>first</span> <span m=''779900''>clause</span>
  <span m=''780260''>is</span> <span m=''780340''>some</span> <span m=''781070''>selector</span>
  <span m=''783150''>whose</span> <span m=''783350''>details</span> <span m=''783730''>we</span>
  <span m=''783810''>don''t</span> <span m=''783970''>care</span> <span m=''784200''>about.</span>
  <span m=''784470''>And</span> <span m=''784525''>you</span> <span m=''784580''>can,</span>
  <span m=''784770''>again,</span> <span m=''785080''>imagine</span> <span m=''785520''>that</span>
  <span m=''785690''>as</span> <span m=''785810''>a</span> <span m=''785860''>sub-routine</span>
  <span m=''786440''>which''ll</span> <span m=''786670''>do</span> <span m=''786790''>some</span>
  <span m=''786985''>list</span> <span m=''787180''>operations,</span> <span m=''788180''>or</span>
  <span m=''788360''>you</span> <span m=''788470''>can</span> <span m=''788580''>imagine</span>
  <span m=''788940''>that</span> <span m=''789100''>as</span> <span m=''789180''>something</span>
  <span m=''789470''>that''s</span> <span m=''789630''>built</span> <span m=''789790''>directly</span>
  <span m=''790190''>into</span> <span m=''790340''>hardware.</span> <span m=''792170''>The</span>
  <span m=''792260''>reason</span> <span m=''792500''>I</span> <span m=''792560''>keep</span>
  <span m=''792770''>saying</span> <span m=''792980''>you</span> <span m=''793070''>can</span>
  <span m=''793170''>imagine</span> <span m=''793610''>it</span> <span m=''794060''>built</span>
  <span m=''794220''>directly</span> <span m=''794580''>into</span> <span m=''794700''>hardware</span>
  <span m=''795150''>is</span> <span m=''795260''>even</span> <span m=''795450''>though</span>
  <span m=''795570''>there</span> <span m=''795700''>are</span> <span m=''795790''>a</span>
  <span m=''795840''>lot</span> <span m=''796200''>of</span> <span m=''796990''>operations,</span>
  <span m=''798360''>there</span> <span m=''798440''>are</span> <span m=''798520''>still</span>
  <span m=''798720''>a</span> <span m=''798770''>fixed</span> <span m=''799130''>number</span>
  <span m=''799460''>of</span> <span m=''799560''>them.</span> <span m=''799740''>I</span>
  <span m=''800120''>forget</span> <span m=''800420''>how</span> <span m=''800700''>many,</span>
  <span m=''800990''>maybe</span> <span m=''801370''>150.</span> <span m=''802370''>So,</span>
  <span m=''802670''>it''s</span> <span m=''803000''>plausible</span> <span m=''803530''>to</span>
  <span m=''803590''>think</span> <span m=''803800''>of</span> <span m=''803880''>building</span>
  <span m=''804200''>these</span> <span m=''804360''>directly</span> <span m=''804780''>into</span>
  <span m=''804910''>hardware.</span> </p><p><span m=''806400''>Here''s</span> <span
  m=''806490''>a</span> <span m=''806580''>more</span> <span m=''806750''>complicated</span>
  <span m=''807360''>one.</span> <span m=''808500''>You</span> <span m=''808590''>can</span>
  <span m=''808690''>see</span> <span m=''808820''>this</span> <span m=''808960''>has</span>
  <span m=''809130''>to</span> <span m=''809230''>do</span> <span m=''809360''>with</span>
  <span m=''809480''>looking</span> <span m=''809800''>up</span> <span m=''809940''>the</span>
  <span m=''810020''>values</span> <span m=''810440''>of</span> <span m=''810510''>variables.</span>
  <span m=''811710''>It</span> <span m=''811785''>says</span> <span m=''811860''>assign</span>
  <span m=''812200''>to</span> <span m=''812280''>the</span> <span m=''812380''>VAL</span>
  <span m=''812650''>register</span> <span m=''813430''>the</span> <span m=''813520''>result</span>
  <span m=''813860''>of</span> <span m=''813950''>looking</span> <span m=''814370''>up</span>
  <span m=''815670''>the</span> <span m=''815800''>variable</span> <span m=''816260''>value</span>
  <span m=''817010''>of</span> <span m=''817170''>some</span> <span m=''817320''>particular</span>
  <span m=''817810''>expression,</span> <span m=''818855''>which,</span> <span m=''819310''>in</span>
  <span m=''819350''>this</span> <span m=''819500''>case,</span> <span m=''819730''>is</span>
  <span m=''819810''>supposed</span> <span m=''819980''>to</span> <span m=''820150''>be</span>
  <span m=''820215''>a</span> <span m=''820280''>variable</span> <span m=''820940''>in</span>
  <span m=''821130''>some</span> <span m=''821330''>environment.</span> <span m=''822850''>And</span>
  <span m=''822990''>this''ll</span> <span m=''823190''>be</span> <span m=''823310''>some</span>
  <span m=''823790''>operation</span> <span m=''825300''>that</span> <span m=''825500''>searches</span>
  <span m=''825920''>through</span> <span m=''826520''>the</span> <span m=''826650''>environment</span>
  <span m=''827150''>structure,</span> <span m=''827520''>however</span> <span m=''828000''>it</span>
  <span m=''828050''>is</span> <span m=''828160''>represented,</span> <span m=''829500''>and</span>
  <span m=''829640''>goes</span> <span m=''829860''>and</span> <span m=''829930''>looks</span>
  <span m=''830150''>up</span> <span m=''830290''>that</span> <span m=''830460''>variable.</span>
  <span m=''832240''>And,</span> <span m=''832380''>again,</span> <span m=''832600''>that''s</span>
  <span m=''832810''>below</span> <span m=''833120''>the</span> <span m=''833210''>level</span>
  <span m=''833520''>of</span> <span m=''833600''>detail</span> <span m=''834120''>that</span>
  <span m=''834250''>we''re</span> <span m=''834360''>thinking</span> <span m=''834690''>about.</span>
  <span m=''835790''>This</span> <span m=''835930''>has</span> <span m=''836110''>to</span>
  <span m=''836190''>do</span> <span m=''836300''>with</span> <span m=''836430''>the</span>
  <span m=''836490''>details</span> <span m=''837030''>of</span> <span m=''837550''>the</span>
  <span m=''837630''>data</span> <span m=''837930''>structures</span> <span m=''838350''>for</span>
  <span m=''838430''>representing</span> <span m=''838930''>environments.</span> </p><p><span
  m=''840380''>But,</span> <span m=''840500''>anyway,</span> <span m=''841320''>there</span>
  <span m=''841440''>is</span> <span m=''841560''>this</span> <span m=''841640''>fixed</span>
  <span m=''842320''>and</span> <span m=''842530''>finite</span> <span m=''843040''>number</span>
  <span m=''844270''>of</span> <span m=''844410''>operations</span> <span m=''845090''>in</span>
  <span m=''845160''>the</span> <span m=''845230''>register</span> <span m=''845600''>machine.</span>
  <span m=''848500''>Well,</span> <span m=''850330''>what''s</span> <span m=''850580''>its</span>
  <span m=''850720''>overall</span> <span m=''851120''>structure?</span> <span m=''851720''>Those</span>
  <span m=''851900''>are</span> <span m=''852000''>some</span> <span m=''852140''>typical</span>
  <span m=''852530''>operations.</span> <span m=''854930''>Remember</span> <span m=''855500''>what</span>
  <span m=''855690''>we</span> <span m=''855790''>have</span> <span m=''855990''>to</span>
  <span m=''856080''>do,</span> <span m=''856450''>we</span> <span m=''856580''>have</span>
  <span m=''856710''>to</span> <span m=''856800''>take</span> <span m=''856980''>the</span>
  <span m=''857060''>meta-circular</span> <span m=''857750''>evaluator--</span> <span
  m=''860172''>and</span> <span m=''861140''>here''s</span> <span m=''861320''>a</span>
  <span m=''861370''>piece</span> <span m=''861630''>of</span> <span m=''861690''>the</span>
  <span m=''861780''>meta-circular</span> <span m=''862380''>evaluator.</span> <span
  m=''862890''>This</span> <span m=''863040''>is</span> <span m=''864030''>the</span>
  <span m=''864130''>one</span> <span m=''864290''>using</span> <span m=''864560''>abstract</span>
  <span m=''865110''>syntax</span> <span m=''866130''>that''s</span> <span m=''866330''>in</span>
  <span m=''866410''>the</span> <span m=''866490''>book.</span> <span m=''868310''>It''s</span>
  <span m=''868700''>a</span> <span m=''868820''>little</span> <span m=''869110''>bit</span>
  <span m=''869270''>different</span> <span m=''869560''>from</span> <span m=''869670''>the</span>
  <span m=''869750''>one</span> <span m=''870500''>that</span> <span m=''870640''>Jerry</span>
  <span m=''870930''>shows</span> <span m=''871200''>you.</span> <span m=''873500''>And</span>
  <span m=''874490''>the</span> <span m=''874600''>main</span> <span m=''874940''>thing</span>
  <span m=''875120''>to</span> <span m=''875220''>remember</span> <span m=''875650''>about</span>
  <span m=''876660''>the</span> <span m=''876920''>evaluator</span> <span m=''877710''>is</span>
  <span m=''877810''>that</span> <span m=''877950''>it''s</span> <span m=''878120''>doing</span>
  <span m=''878370''>some</span> <span m=''878550''>sort</span> <span m=''878700''>of</span>
  <span m=''878850''>case</span> <span m=''879150''>analysis</span> <span m=''879670''>on</span>
  <span m=''879770''>the</span> <span m=''879880''>kinds</span> <span m=''880230''>of</span>
  <span m=''880310''>expressions:</span> <span m=''883650''>so</span> <span m=''883920''>if</span>
  <span m=''884010''>it''s</span> <span m=''884210''>either</span> <span m=''884420''>self-evaluated,</span>
  <span m=''885290''>or</span> <span m=''885380''>quoted,</span> <span m=''885940''>or</span>
  <span m=''886120''>whatever</span> <span m=''886550''>else.</span> <span m=''888560''>And</span>
  <span m=''888850''>then,</span> <span m=''889000''>in</span> <span m=''889070''>the</span>
  <span m=''889160''>general</span> <span m=''889530''>case</span> <span m=''890150''>where</span>
  <span m=''890900''>the</span> <span m=''891050''>expression</span> <span m=''891470''>it''s</span>
  <span m=''891620''>looking</span> <span m=''891900''>at</span> <span m=''892020''>is</span>
  <span m=''892120''>an</span> <span m=''892190''>application,</span> <span m=''893680''>there''s</span>
  <span m=''893830''>some</span> <span m=''893990''>tricky</span> <span m=''894280''>recursions</span>
  <span m=''894810''>going</span> <span m=''894980''>on.</span> </p><p><span m=''895750''>First</span>
  <span m=''896020''>of</span> <span m=''896070''>all,</span> <span m=''896210''>eval</span>
  <span m=''897390''>has</span> <span m=''897610''>to</span> <span m=''897720''>call</span>
  <span m=''898700''>itself</span> <span m=''899770''>both</span> <span m=''900000''>to</span>
  <span m=''900140''>evaluate</span> <span m=''900640''>the</span> <span m=''900730''>operator</span>
  <span m=''902170''>and</span> <span m=''902380''>to</span> <span m=''902530''>evaluate</span>
  <span m=''903030''>all</span> <span m=''903210''>the</span> <span m=''903320''>operands.</span>
  <span m=''905880''>So</span> <span m=''906040''>there''s</span> <span m=''906250''>this</span>
  <span m=''906300''>sort</span> <span m=''906510''>of</span> <span m=''906590''>red</span>
  <span m=''906820''>recursion</span> <span m=''907870''>of</span> <span m=''907920''>values</span>
  <span m=''908120''>walking</span> <span m=''908470''>down</span> <span m=''908690''>the</span>
  <span m=''908770''>tree</span> <span m=''911050''>that''s</span> <span m=''911200''>really</span>
  <span m=''911500''>the</span> <span m=''911615''>easy</span> <span m=''911730''>recursion.</span>
  <span m=''912270''>That''s</span> <span m=''912410''>just</span> <span m=''912600''>a</span>
  <span m=''912650''>val</span> <span m=''912900''>walking</span> <span m=''913230''>down</span>
  <span m=''913420''>this</span> <span m=''913480''>tree</span> <span m=''913660''>of</span>
  <span m=''913840''>expressions.</span> <span m=''914750''>Then,</span> <span m=''915040''>in</span>
  <span m=''915128''>the</span> <span m=''915216''>evaluator,</span> <span m=''915570''>there''s</span>
  <span m=''915720''>a</span> <span m=''915760''>hard</span> <span m=''916000''>recursion.</span>
  <span m=''916600''>There''s</span> <span m=''916810''>the</span> <span m=''917180''>red</span>
  <span m=''917420''>to</span> <span m=''917510''>green.</span> <span m=''918200''>Eval</span>
  <span m=''918830''>calls</span> <span m=''919050''>apply.</span> <span m=''922470''>That''s</span>
  <span m=''922680''>the</span> <span m=''922760''>case</span> <span m=''924200''>where</span>
  <span m=''924370''>evaluating</span> <span m=''925430''>a</span> <span m=''925520''>procedure</span>
  <span m=''925990''>or</span> <span m=''926132''>argument</span> <span m=''926560''>reduces</span>
  <span m=''927070''>to</span> <span m=''927230''>applying</span> <span m=''927970''>the</span>
  <span m=''928100''>procedure</span> <span m=''928920''>to</span> <span m=''929040''>the</span>
  <span m=''929130''>list</span> <span m=''929350''>of</span> <span m=''929460''>arguments.</span>
  </p><p><span m=''930370''>And</span> <span m=''930530''>then,</span> <span m=''930630''>apply</span>
  <span m=''930940''>comes</span> <span m=''931220''>over</span> <span m=''931430''>here.</span>
  <span m=''934770''>Apply</span> <span m=''935090''>takes</span> <span m=''935350''>a</span>
  <span m=''935410''>procedure</span> <span m=''936040''>and</span> <span m=''936130''>arguments</span>
  <span m=''937820''>and,</span> <span m=''938670''>in</span> <span m=''938820''>the</span>
  <span m=''938900''>general</span> <span m=''939270''>case</span> <span m=''939520''>where</span>
  <span m=''939600''>there''s</span> <span m=''939760''>a</span> <span m=''939810''>compound</span>
  <span m=''940260''>procedure,</span> <span m=''941130''>apply</span> <span m=''941460''>goes</span>
  <span m=''941660''>around</span> <span m=''941950''>and</span> <span m=''942300''>green</span>
  <span m=''942560''>calls</span> <span m=''942830''>red.</span> <span m=''944560''>Apply</span>
  <span m=''944860''>comes</span> <span m=''945110''>around</span> <span m=''945280''>and</span>
  <span m=''945450''>calls</span> <span m=''945710''>eval</span> <span m=''946070''>again.</span>
  <span m=''948170''>Eval''s</span> <span m=''948380''>the</span> <span m=''948640''>body</span>
  <span m=''949020''>of</span> <span m=''949090''>the</span> <span m=''949160''>procedure</span>
  <span m=''950230''>in</span> <span m=''950470''>the</span> <span m=''950820''>result</span>
  <span m=''951240''>of</span> <span m=''951330''>extending</span> <span m=''951800''>the</span>
  <span m=''951930''>environment</span> <span m=''953780''>with</span> <span m=''953920''>the</span>
  <span m=''953980''>parameters</span> <span m=''954520''>of</span> <span m=''954560''>the</span>
  <span m=''954600''>procedure</span> <span m=''955620''>by</span> <span m=''955810''>binding</span>
  <span m=''956210''>the</span> <span m=''956330''>arguments.</span> <span m=''959620''>Except</span>
  <span m=''959910''>in</span> <span m=''959970''>the</span> <span m=''960040''>primitive</span>
  <span m=''960400''>case,</span> <span m=''960670''>where</span> <span m=''960790''>it</span>
  <span m=''960910''>just</span> <span m=''961020''>calls</span> <span m=''961250''>something</span>
  <span m=''961560''>else</span> <span m=''961740''>primitive-apply,</span> <span
  m=''962750''>which</span> <span m=''962930''>is</span> <span m=''963030''>not</span>
  <span m=''963230''>really</span> <span m=''963460''>the</span> <span m=''963550''>business</span>
  <span m=''963890''>of</span> <span m=''963960''>the</span> <span m=''964250''>evaluator.</span>
  <span m=''965980''>So</span> <span m=''966500''>this</span> <span m=''966610''>sort</span>
  <span m=''966840''>of</span> <span m=''966920''>red</span> <span m=''967130''>to</span>
  <span m=''967220''>green,</span> <span m=''967500''>to</span> <span m=''967620''>red</span>
  <span m=''967820''>to</span> <span m=''967900''>green,</span> <span m=''971320''>that''s</span>
  <span m=''971530''>the</span> <span m=''971630''>eval/apply</span> <span m=''972300''>loop,</span>
  <span m=''974230''>and</span> <span m=''974320''>that''s</span> <span m=''974520''>the</span>
  <span m=''974590''>thing</span> <span m=''974750''>that</span> <span m=''974880''>we''re</span>
  <span m=''974990''>going</span> <span m=''975070''>to</span> <span m=''975130''>want</span>
  <span m=''975310''>to</span> <span m=''975350''>see</span> <span m=''976560''>in</span>
  <span m=''976705''>the</span> <span m=''976850''>evaluator.</span> </p><p><span
  m=''979840''>All</span> <span m=''979905''>right.</span> <span m=''979970''>Well,</span>
  <span m=''980100''>it</span> <span m=''980230''>won''t</span> <span m=''980360''>surprise</span>
  <span m=''980660''>you</span> <span m=''980760''>at</span> <span m=''980830''>all</span>
  <span m=''980980''>that</span> <span m=''981470''>the</span> <span m=''981580''>two</span>
  <span m=''981760''>big</span> <span m=''982050''>pieces</span> <span m=''982480''>of</span>
  <span m=''982570''>this</span> <span m=''982750''>evaluator</span> <span m=''985620''>correspond</span>
  <span m=''986130''>to</span> <span m=''986220''>eval</span> <span m=''986310''>and</span>
  <span m=''986610''>apply.</span> <span m=''987470''>There''s</span> <span m=''987640''>a</span>
  <span m=''987690''>piece</span> <span m=''987920''>called</span> <span m=''988180''>eval-dispatch,</span>
  <span m=''989720''>and</span> <span m=''989830''>a</span> <span m=''989910''>piece</span>
  <span m=''990070''>called</span> <span m=''990230''>apply-dispatch.</span> <span
  m=''992110''>And,</span> <span m=''992270''>before</span> <span m=''992550''>we</span>
  <span m=''992680''>get</span> <span m=''992830''>into</span> <span m=''993020''>the</span>
  <span m=''993120''>details</span> <span m=''993560''>of</span> <span m=''993620''>the</span>
  <span m=''993730''>code,</span> <span m=''994280''>the</span> <span m=''994380''>way</span>
  <span m=''994520''>to</span> <span m=''994570''>understand</span> <span m=''995100''>this</span>
  <span m=''995250''>is</span> <span m=''995350''>to</span> <span m=''995450''>think,</span>
  <span m=''996140''>again,</span> <span m=''996410''>in</span> <span m=''996510''>terms</span>
  <span m=''996840''>of</span> <span m=''997760''>these</span> <span m=''997970''>pieces</span>
  <span m=''998320''>of</span> <span m=''998400''>the</span> <span m=''998560''>evaluator</span>
  <span m=''999060''>having</span> <span m=''999320''>contracts</span> <span m=''999990''>with</span>
  <span m=''1000110''>the</span> <span m=''1000180''>rest</span> <span m=''1000430''>of</span>
  <span m=''1000490''>the</span> <span m=''1000580''>world.</span> <span m=''1001870''>What</span>
  <span m=''1002210''>do</span> <span m=''1002240''>they</span> <span m=''1002510''>do</span>
  <span m=''1002610''>from</span> <span m=''1002730''>the</span> <span m=''1002860''>outside</span>
  <span m=''1003240''>before</span> <span m=''1003690''>getting</span> <span m=''1003950''>into</span>
  <span m=''1004320''>the</span> <span m=''1004610''>grungy</span> <span m=''1005000''>details?</span>
  </p><p><span m=''1005780''>Well,</span> <span m=''1005920''>the</span> <span m=''1006020''>contract</span>
  <span m=''1007740''>for</span> <span m=''1008280''>eval-dispatch--</span> <span
  m=''1010080''>remember,</span> <span m=''1010195''>it</span> <span m=''1010310''>corresponds</span>
  <span m=''1010830''>to</span> <span m=''1010920''>eval.</span> <span m=''1011300''>It''s</span>
  <span m=''1011640''>got</span> <span m=''1011760''>to</span> <span m=''1011870''>evaluate</span>
  <span m=''1012360''>an</span> <span m=''1012450''>expression</span> <span m=''1013260''>in</span>
  <span m=''1013400''>an</span> <span m=''1013500''>environment.</span> <span m=''1014100''>So,</span>
  <span m=''1014270''>in</span> <span m=''1014370''>particular,</span> <span m=''1014810''>what</span>
  <span m=''1014940''>this</span> <span m=''1015100''>one</span> <span m=''1015240''>is</span>
  <span m=''1015350''>going</span> <span m=''1015450''>to</span> <span m=''1015500''>do,</span>
  <span m=''1016840''>eval-dispatch</span> <span m=''1017230''>will</span> <span m=''1017540''>assume</span>
  <span m=''1017940''>that,</span> <span m=''1018030''>when</span> <span m=''1018140''>you</span>
  <span m=''1018250''>call</span> <span m=''1018600''>it,</span> <span m=''1019670''>that</span>
  <span m=''1019920''>the</span> <span m=''1020120''>expression</span> <span m=''1020630''>you</span>
  <span m=''1020720''>want</span> <span m=''1020860''>to</span> <span m=''1020960''>evaluate</span>
  <span m=''1021460''>is</span> <span m=''1021570''>in</span> <span m=''1021630''>the</span>
  <span m=''1021760''>EXP</span> <span m=''1021950''>register.</span> <span m=''1023640''>The</span>
  <span m=''1023850''>environment</span> <span m=''1026060''>in</span> <span m=''1026200''>which</span>
  <span m=''1026380''>you</span> <span m=''1026470''>want</span> <span m=''1026670''>the</span>
  <span m=''1026790''>evaluation</span> <span m=''1027390''>to</span> <span m=''1027470''>take</span>
  <span m=''1027680''>place</span> <span m=''1027920''>is</span> <span m=''1028020''>in</span>
  <span m=''1028079''>the</span> <span m=''1028250''>ENV</span> <span m=''1028420''>register.</span>
  <span m=''1029569''>And</span> <span m=''1029710''>continue</span> <span m=''1030170''>tells</span>
  <span m=''1030460''>you</span> <span m=''1030869''>the</span> <span m=''1030960''>place</span>
  <span m=''1031280''>where</span> <span m=''1031390''>the</span> <span m=''1031520''>machine</span>
  <span m=''1031859''>should</span> <span m=''1032040''>go</span> <span m=''1032180''>next</span>
  <span m=''1032550''>when</span> <span m=''1032635''>the</span> <span m=''1032720''>evaluation</span>
  <span m=''1033450''>is</span> <span m=''1033599''>done.</span> <span m=''1037440''>Eval-dispatch''s</span>
  <span m=''1038210''>contract</span> <span m=''1038770''>is</span> <span m=''1038880''>that</span>
  <span m=''1039329''>it''ll</span> <span m=''1039540''>actually</span> <span m=''1039900''>perform</span>
  <span m=''1040210''>that</span> <span m=''1040349''>evaluation,</span> <span m=''1041430''>and,</span>
  <span m=''1041609''>at</span> <span m=''1041680''>the</span> <span m=''1041829''>end</span>
  <span m=''1041980''>of</span> <span m=''1042089''>which,</span> <span m=''1043369''>it''ll</span>
  <span m=''1043490''>end</span> <span m=''1043720''>up</span> <span m=''1043839''>at</span>
  <span m=''1043930''>the</span> <span m=''1044010''>place</span> <span m=''1044260''>specified</span>
  <span m=''1044790''>by</span> <span m=''1044900''>continue.</span> <span m=''1046619''>The</span>
  <span m=''1046720''>result</span> <span m=''1047210''>of</span> <span m=''1047260''>the</span>
  <span m=''1047400''>evaluation</span> <span m=''1048000''>will</span> <span m=''1048089''>be</span>
  <span m=''1048190''>in</span> <span m=''1048280''>the</span> <span m=''1048369''>VAL</span>
  <span m=''1048610''>register.</span> <span m=''1049950''>And</span> <span m=''1050060''>it</span>
  <span m=''1050170''>just</span> <span m=''1050370''>warns</span> <span m=''1050650''>you,</span>
  <span m=''1051310''>it</span> <span m=''1051540''>makes</span> <span m=''1051890''>no</span>
  <span m=''1052010''>promises</span> <span m=''1052570''>about</span> <span m=''1052930''>what</span>
  <span m=''1053100''>happens</span> <span m=''1053440''>to</span> <span m=''1053540''>the</span>
  <span m=''1053910''>registers.</span> <span m=''1055230''>All</span> <span m=''1055400''>other</span>
  <span m=''1055560''>registers</span> <span m=''1055980''>might</span> <span m=''1056170''>be</span>
  <span m=''1056270''>destroyed.</span> <span m=''1057490''>So,</span> <span m=''1057640''>there''s</span>
  <span m=''1057840''>one</span> <span m=''1058070''>piece,</span> <span m=''1059961''>OK?</span>
  </p><p><span m=''1061790''>Together,</span> <span m=''1061930''>the</span> <span
  m=''1062090''>pieces,</span> <span m=''1062560''>apply-dispatch</span> <span m=''1063530''>that</span>
  <span m=''1063640''>corresponds</span> <span m=''1064190''>to</span> <span m=''1064300''>apply,</span>
  <span m=''1066140''>it''s</span> <span m=''1066250''>got</span> <span m=''1066300''>to</span>
  <span m=''1066400''>apply</span> <span m=''1066770''>a</span> <span m=''1066910''>procedure</span>
  <span m=''1067330''>to</span> <span m=''1067440''>some</span> <span m=''1067650''>arguments,</span>
  <span m=''1068770''>so</span> <span m=''1068960''>it</span> <span m=''1069090''>assumes</span>
  <span m=''1069410''>that</span> <span m=''1070330''>this</span> <span m=''1070490''>register,</span>
  <span m=''1070950''>ARGL,</span> <span m=''1071650''>contains</span> <span m=''1072060''>a</span>
  <span m=''1072110''>list</span> <span m=''1072440''>of</span> <span m=''1072510''>the</span>
  <span m=''1072670''>evaluated</span> <span m=''1073210''>arguments.</span> <span
  m=''1074540''>FUN</span> <span m=''1074850''>contains</span> <span m=''1075240''>the</span>
  <span m=''1075320''>procedure.</span> <span m=''1077220''>Those</span> <span m=''1077400''>correspond</span>
  <span m=''1077740''>to</span> <span m=''1077820''>the</span> <span m=''1077940''>arguments</span>
  <span m=''1078510''>to</span> <span m=''1079020''>the</span> <span m=''1079150''>apply</span>
  <span m=''1079500''>procedure</span> <span m=''1080040''>in</span> <span m=''1080110''>the</span>
  <span m=''1080180''>meta-circular</span> <span m=''1080800''>evaluator.</span> </p><p><span
  m=''1083970''>And</span> <span m=''1084130''>apply,</span> <span m=''1084510''>in</span>
  <span m=''1084750''>this</span> <span m=''1084950''>particular</span> <span m=''1085490''>evaluator,</span>
  <span m=''1086080''>we''re</span> <span m=''1086190''>going</span> <span m=''1086280''>to</span>
  <span m=''1086320''>use</span> <span m=''1086520''>a</span> <span m=''1086570''>discipline</span>
  <span m=''1087050''>which</span> <span m=''1087220''>says</span> <span m=''1089520''>the</span>
  <span m=''1089620''>place</span> <span m=''1089870''>the</span> <span m=''1089960''>machine</span>
  <span m=''1090270''>should</span> <span m=''1090440''>go</span> <span m=''1090600''>to</span>
  <span m=''1090790''>next</span> <span m=''1091850''>when</span> <span m=''1091980''>apply</span>
  <span m=''1092310''>is</span> <span m=''1092540''>done</span> <span m=''1092770''>is,</span>
  <span m=''1092825''>at</span> <span m=''1092880''>the</span> <span m=''1092970''>moment</span>
  <span m=''1093590''>apply-dispatch</span> <span m=''1093890''>is</span> <span m=''1094480''>called</span>
  <span m=''1094790''>at</span> <span m=''1094900''>the</span> <span m=''1094990''>top</span>
  <span m=''1095240''>of</span> <span m=''1095340''>the</span> <span m=''1095430''>stack,</span>
  <span m=''1097270''>that''s</span> <span m=''1097480''>just</span> <span m=''1098330''>discipline</span>
  <span m=''1098850''>for</span> <span m=''1098950''>the</span> <span m=''1099040''>way</span>
  <span m=''1099190''>this</span> <span m=''1099410''>particular</span> <span m=''1100310''>machine''s</span>
  <span m=''1100660''>organized.</span> <span m=''1101840''>And</span> <span m=''1101930''>now</span>
  <span m=''1102080''>apply''s</span> <span m=''1102400''>contract</span> <span m=''1102890''>is</span>
  <span m=''1102980''>given</span> <span m=''1103220''>all</span> <span m=''1103380''>that.</span>
  <span m=''1103950''>It''ll</span> <span m=''1104140''>perform</span> <span m=''1104500''>the</span>
  <span m=''1104600''>application.</span> <span m=''1105540''>The</span> <span m=''1105690''>result</span>
  <span m=''1106100''>of</span> <span m=''1106140''>that</span> <span m=''1106300''>application</span>
  <span m=''1106860''>will</span> <span m=''1106980''>end</span> <span m=''1107160''>up</span>
  <span m=''1107270''>in</span> <span m=''1107410''>VAL.</span> <span m=''1108890''>The</span>
  <span m=''1109060''>stack</span> <span m=''1109225''>will</span> <span m=''1109390''>be</span>
  <span m=''1109540''>popped.</span> <span m=''1111120''>And,</span> <span m=''1111250''>again,</span>
  <span m=''1111680''>the</span> <span m=''1111790''>contents</span> <span m=''1112270''>of</span>
  <span m=''1112350''>all</span> <span m=''1112490''>the</span> <span m=''1112610''>other</span>
  <span m=''1112850''>registers</span> <span m=''1113200''>may</span> <span m=''1113330''>be</span>
  <span m=''1113460''>destroyed,</span> <span m=''1114720''>all</span> <span m=''1114915''>right?</span>
  <span m=''1115110''>So</span> <span m=''1115220''>that''s</span> <span m=''1115770''>the</span>
  <span m=''1115870''>basic</span> <span m=''1116350''>organization</span> <span m=''1117060''>of</span>
  <span m=''1117120''>this</span> <span m=''1117280''>machine.</span> <span m=''1119760''>Let''s</span>
  <span m=''1120000''>break</span> <span m=''1120280''>for</span> <span m=''1120315''>a</span>
  <span m=''1120350''>little</span> <span m=''1120500''>bit</span> <span m=''1120590''>and</span>
  <span m=''1120680''>see</span> <span m=''1120790''>if</span> <span m=''1120870''>there</span>
  <span m=''1120925''>are</span> <span m=''1120980''>any</span> <span m=''1121110''>questions,</span>
  <span m=''1121540''>and</span> <span m=''1121610''>then</span> <span m=''1121710''>we''ll</span>
  <span m=''1121820''>do</span> <span m=''1121950''>a</span> <span m=''1121980''>real</span>
  <span m=''1122200''>example.</span> </p><p><span m=''1187850''>Well,</span> <span
  m=''1188340''>let''s</span> <span m=''1188570''>take</span> <span m=''1188790''>the</span>
  <span m=''1188880''>register</span> <span m=''1189280''>machine</span> <span m=''1189620''>now,</span>
  <span m=''1190400''>and</span> <span m=''1190560''>actually</span> <span m=''1190920''>step</span>
  <span m=''1191300''>through,</span> <span m=''1192410''>and</span> <span m=''1192560''>really,</span>
  <span m=''1196060''>in</span> <span m=''1196190''>real</span> <span m=''1196500''>detail,</span>
  <span m=''1197040''>so</span> <span m=''1197190''>you</span> <span m=''1197330''>see</span>
  <span m=''1197520''>completely</span> <span m=''1197950''>concrete</span> <span
  m=''1199660''>how</span> <span m=''1199810''>some</span> <span m=''1200000''>expressions</span>
  <span m=''1200510''>are</span> <span m=''1200600''>evaluated,</span> <span m=''1202970''>all</span>
  <span m=''1203185''>right?</span> <span m=''1203400''>So,</span> <span m=''1204930''>let''s</span>
  <span m=''1205110''>start</span> <span m=''1205330''>with</span> <span m=''1205450''>a</span>
  <span m=''1205490''>very</span> <span m=''1205820''>simple</span> <span m=''1206180''>expression.</span>
  <span m=''1209620''>Let''s</span> <span m=''1209850''>evaluate</span> <span m=''1210410''>the</span>
  <span m=''1210520''>expression</span> <span m=''1212980''>1.</span> <span m=''1218880''>And</span>
  <span m=''1219430''>we</span> <span m=''1219560''>need</span> <span m=''1219700''>an</span>
  <span m=''1219810''>environment,</span> <span m=''1220420''>so</span> <span m=''1220530''>let''s</span>
  <span m=''1220720''>imagine</span> <span m=''1221170''>that</span> <span m=''1221320''>somewhere</span>
  <span m=''1221620''>there''s</span> <span m=''1221840''>an</span> <span m=''1221920''>environment,</span>
  <span m=''1222440''>we''ll</span> <span m=''1222550''>call</span> <span m=''1222760''>it</span>
  <span m=''1222830''>E,0.</span> <span m=''1230260''>And</span> <span m=''1230360''>just,</span>
  <span m=''1233170''>since</span> <span m=''1233640''>we''ll</span> <span m=''1233790''>use</span>
  <span m=''1234000''>these</span> <span m=''1234210''>later,</span> <span m=''1235720''>we</span>
  <span m=''1235850''>obviously</span> <span m=''1236230''>don''t</span> <span m=''1236360''>really</span>
  <span m=''1236550''>need</span> <span m=''1236730''>anything</span> <span m=''1237030''>to</span>
  <span m=''1237160''>evaluate</span> <span m=''1237640''>1.</span> <span m=''1238360''>But,</span>
  <span m=''1238530''>just</span> <span m=''1238710''>for</span> <span m=''1238810''>reference</span>
  <span m=''1239200''>later,</span> <span m=''1239420''>let''s</span> <span m=''1239610''>assume</span>
  <span m=''1239860''>that</span> <span m=''1240000''>E,0</span> <span m=''1240470''>has</span>
  <span m=''1240700''>in</span> <span m=''1240810''>it</span> <span m=''1241680''>an</span>
  <span m=''1241905''>X</span> <span m=''1242130''>that''s</span> <span m=''1242245''>bound</span>
  <span m=''1242360''>to</span> <span m=''1242470''>3</span> <span m=''1243820''>and</span>
  <span m=''1243960''>a</span> <span m=''1244020''>Y</span> <span m=''1244250''>that''s</span>
  <span m=''1244430''>bound</span> <span m=''1244660''>to</span> <span m=''1244760''>4,</span>
  <span m=''1247690''>OK?</span> </p><p><span m=''1249140''>And</span> <span m=''1249280''>now</span>
  <span m=''1249390''>what</span> <span m=''1249530''>we''re</span> <span m=''1249640''>going</span>
  <span m=''1249730''>to</span> <span m=''1249780''>do</span> <span m=''1250620''>is</span>
  <span m=''1250780''>we''re</span> <span m=''1250880''>going</span> <span m=''1250980''>to</span>
  <span m=''1251080''>evaluate</span> <span m=''1252420''>1</span> <span m=''1253700''>in</span>
  <span m=''1253770''>this</span> <span m=''1253940''>environment,</span> <span m=''1255770''>and</span>
  <span m=''1256810''>so</span> <span m=''1257040''>the</span> <span m=''1257180''>ENV</span>
  <span m=''1257400''>register</span> <span m=''1257830''>has</span> <span m=''1257990''>a</span>
  <span m=''1258040''>pointer</span> <span m=''1259650''>to</span> <span m=''1259810''>this</span>
  <span m=''1259960''>environment,</span> <span m=''1260480''>E,0,</span> <span m=''1263120''>all</span>
  <span m=''1263340''>right?</span> <span m=''1263560''>So</span> <span m=''1263730''>let''s</span>
  <span m=''1264700''>watch</span> <span m=''1265050''>that</span> <span m=''1265220''>thing</span>
  <span m=''1265400''>go.</span> <span m=''1265650''>What</span> <span m=''1265880''>I''m</span>
  <span m=''1265940''>going</span> <span m=''1266020''>to</span> <span m=''1266060''>do</span>
  <span m=''1266190''>is</span> <span m=''1266270''>step</span> <span m=''1266500''>through</span>
  <span m=''1266650''>the</span> <span m=''1266760''>code.</span> <span m=''1268260''>And,</span>
  <span m=''1268950''>let''s</span> <span m=''1269100''>see,</span> <span m=''1269190''>I''ll</span>
  <span m=''1269360''>be</span> <span m=''1269480''>the</span> <span m=''1269600''>controller.</span>
  <span m=''1270080''>And</span> <span m=''1270160''>now</span> <span m=''1270270''>what</span>
  <span m=''1270420''>I</span> <span m=''1270480''>need,</span> <span m=''1271000''>since</span>
  <span m=''1271220''>this</span> <span m=''1271370''>gets</span> <span m=''1271540''>rather</span>
  <span m=''1271770''>complicated,</span> <span m=''1272980''>is</span> <span m=''1273410''>a</span>
  <span m=''1275010''>very</span> <span m=''1275220''>little</span> <span m=''1275870''>execution</span>
  <span m=''1276520''>unit.</span> <span m=''1276830''>So</span> <span m=''1277030''>here''s</span>
  <span m=''1277200''>the</span> <span m=''1277320''>execution</span> <span m=''1277860''>unit,</span>
  <span m=''1280144''>OK?</span> <span m=''1282624''>OK.</span> </p><p><span m=''1287088''>OK.</span>
  <span m=''1288590''>All</span> <span m=''1288815''>right,</span> <span m=''1289040''>now</span>
  <span m=''1289320''>we''re</span> <span m=''1289420''>going</span> <span m=''1289510''>to</span>
  <span m=''1289550''>start.</span> <span m=''1290690''>We''re</span> <span m=''1290713''>going</span>
  <span m=''1290736''>to</span> <span m=''1290760''>start</span> <span m=''1291050''>the</span>
  <span m=''1291120''>machine</span> <span m=''1291470''>at</span> <span m=''1291710''>eval-dispatch,</span>
  <span m=''1293296''>right?</span> <span m=''1293660''>That''s</span> <span m=''1293820''>the</span>
  <span m=''1293880''>beginning</span> <span m=''1294200''>of</span> <span m=''1294280''>this.</span>
  <span m=''1296120''>Eval-dispatch</span> <span m=''1297020''>is</span> <span m=''1297170''>going</span>
  <span m=''1297270''>to</span> <span m=''1297320''>look</span> <span m=''1297520''>at</span>
  <span m=''1297580''>the</span> <span m=''1297680''>expression</span> <span m=''1298110''>in</span>
  <span m=''1298220''>dispatch,</span> <span m=''1299320''>just</span> <span m=''1299490''>like</span>
  <span m=''1299620''>eval</span> <span m=''1300940''>where</span> <span m=''1301045''>we</span>
  <span m=''1301150''>look</span> <span m=''1301280''>at</span> <span m=''1301320''>the</span>
  <span m=''1301390''>very</span> <span m=''1301620''>first</span> <span m=''1301860''>thing.</span>
  <span m=''1302010''>We</span> <span m=''1302100''>branch</span> <span m=''1304460''>on</span>
  <span m=''1305760''>whether</span> <span m=''1306090''>or</span> <span m=''1306120''>not</span>
  <span m=''1306340''>this</span> <span m=''1306510''>expression</span> <span m=''1306920''>is</span>
  <span m=''1306990''>self-evaluating.</span> <span m=''1307950''>Self-evaluating</span>
  <span m=''1308740''>is</span> <span m=''1308820''>some</span> <span m=''1309410''>abstraction</span>
  <span m=''1310040''>we</span> <span m=''1310170''>put</span> <span m=''1310360''>into</span>
  <span m=''1310590''>the</span> <span m=''1310680''>machine--</span> <span m=''1312550''>it''s</span>
  <span m=''1312580''>going</span> <span m=''1312610''>to</span> <span m=''1312640''>be</span>
  <span m=''1312750''>true</span> <span m=''1312970''>for</span> <span m=''1313120''>numbers--</span>
  <span m=''1313690''>to</span> <span m=''1313810''>a</span> <span m=''1313860''>place</span>
  <span m=''1314100''>called</span> <span m=''1314280''>ev-self-eval,</span> <span
  m=''1316655''>right?</span> </p><p><span m=''1317040''>So</span> <span m=''1317190''>me,</span>
  <span m=''1317260''>being</span> <span m=''1317650''>the</span> <span m=''1317730''>controller,</span>
  <span m=''1318200''>looks</span> <span m=''1318420''>at</span> <span m=''1318540''>ev-self-eval,</span>
  <span m=''1320130''>so</span> <span m=''1320260''>we''ll</span> <span m=''1320370''>go</span>
  <span m=''1320540''>over</span> <span m=''1320720''>to</span> <span m=''1320900''>there.</span>
  <span m=''1322780''>Ev-self-eval</span> <span m=''1323870''>says</span> <span m=''1324240''>fine,</span>
  <span m=''1326650''>assign</span> <span m=''1327150''>to</span> <span m=''1327250''>val</span>
  <span m=''1328370''>whatever</span> <span m=''1328800''>is</span> <span m=''1328870''>in</span>
  <span m=''1328940''>the</span> <span m=''1329050''>expression</span> <span m=''1329485''>unit,</span>
  <span m=''1333768''>OK?</span> <span m=''1335220''>And</span> <span m=''1335770''>I</span>
  <span m=''1335890''>have</span> <span m=''1336020''>a</span> <span m=''1336140''>bug</span>
  <span m=''1337990''>because</span> <span m=''1338670''>what</span> <span m=''1338810''>I</span>
  <span m=''1338870''>didn''t</span> <span m=''1339120''>do</span> <span m=''1339260''>when</span>
  <span m=''1339380''>I</span> <span m=''1339440''>initialized</span> <span m=''1339930''>this</span>
  <span m=''1340070''>machine</span> <span m=''1341810''>is</span> <span m=''1341980''>also</span>
  <span m=''1342310''>say</span> <span m=''1342580''>what''s</span> <span m=''1342780''>supposed</span>
  <span m=''1342970''>to</span> <span m=''1343160''>happen</span> <span m=''1343450''>when</span>
  <span m=''1343610''>it''s</span> <span m=''1343790''>done,</span> <span m=''1344710''>so</span>
  <span m=''1344910''>I</span> <span m=''1345405''>should</span> <span m=''1345572''>have</span>
  <span m=''1345740''>started</span> <span m=''1346230''>out</span> <span m=''1346265''>the</span>
  <span m=''1346300''>machine</span> <span m=''1347470''>with</span> <span m=''1347640''>done</span>
  <span m=''1348580''>being</span> <span m=''1348830''>in</span> <span m=''1348895''>the</span>
  <span m=''1348960''>continue</span> <span m=''1349390''>register,</span> <span m=''1351162''>OK?</span>
  <span m=''1352050''>So</span> <span m=''1352240''>we</span> <span m=''1352390''>assign</span>
  <span m=''1352780''>to</span> <span m=''1352940''>VAL.</span> <span m=''1353640''>And</span>
  <span m=''1353710''>now</span> <span m=''1353780''>go</span> <span m=''1354070''>to</span>
  <span m=''1354750''>fetch</span> <span m=''1354940''>of</span> <span m=''1355090''>continue,</span>
  <span m=''1355720''>and</span> <span m=''1355790''>[? the value changed. ?]</span>
  <span m=''1358000''>OK.</span> </p><p><span m=''1360000''>OK,</span> <span m=''1360250''>let''s</span>
  <span m=''1360380''>try</span> <span m=''1360500''>something</span> <span m=''1360810''>harder.</span>
  <span m=''1362160''>Let''s</span> <span m=''1362320''>reset</span> <span m=''1362700''>the</span>
  <span m=''1362780''>machine</span> <span m=''1363120''>here,</span> <span m=''1364920''>and</span>
  <span m=''1365180''>we''ll</span> <span m=''1367380''>put</span> <span m=''1367650''>in</span>
  <span m=''1367780''>the</span> <span m=''1367900''>expression</span> <span m=''1368340''>register,</span>
  <span m=''1370450''>X,</span> <span m=''1373770''>OK?</span> <span m=''1376710''>Start</span>
  <span m=''1376990''>again</span> <span m=''1377230''>at</span> <span m=''1377270''>eval-dispatch.</span>
  <span m=''1379610''>Check,</span> <span m=''1379920''>is</span> <span m=''1380070''>it</span>
  <span m=''1380570''>self-evaluating?</span> <span m=''1381690''>No.</span> <span
  m=''1382650''>Is</span> <span m=''1382880''>it</span> <span m=''1382925''>a</span>
  <span m=''1382970''>variable?</span> <span m=''1384630''>Yes.</span> <span m=''1385560''>We</span>
  <span m=''1385680''>go</span> <span m=''1385870''>off</span> <span m=''1386010''>to</span>
  <span m=''1386090''>ev-variable.</span> <span m=''1388380''>It</span> <span m=''1388475''>says</span>
  <span m=''1389730''>assign</span> <span m=''1390400''>to</span> <span m=''1390530''>VAL,</span>
  <span m=''1392310''>look</span> <span m=''1392700''>up</span> <span m=''1393240''>the</span>
  <span m=''1393360''>variable</span> <span m=''1393860''>value</span> <span m=''1394460''>in</span>
  <span m=''1394620''>the</span> <span m=''1394700''>expression</span> <span m=''1395180''>register,</span>
  <span m=''1399644''>OK?</span> <span m=''1401620''>Go</span> <span m=''1401810''>to</span>
  <span m=''1402010''>fetch</span> <span m=''1402280''>of</span> <span m=''1402380''>continue.</span>
  </p><p><span m=''1403625''>PROFESSOR:</span> <span m=''1404040''>Done.</span> </p><p><span
  m=''1407252''>PROFESSOR:</span> <span m=''1407690''>OK.</span> <span m=''1408950''>All</span>
  <span m=''1409190''>right.</span> <span m=''1409430''>Well,</span> <span m=''1409550''>that''s</span>
  <span m=''1409740''>the</span> <span m=''1409810''>basic</span> <span m=''1410180''>idea.</span>
  <span m=''1411330''>That''s</span> <span m=''1411460''>a</span> <span m=''1411510''>simple</span>
  <span m=''1411850''>operation</span> <span m=''1412310''>of</span> <span m=''1412370''>the</span>
  <span m=''1412430''>machine.</span> <span m=''1412920''>Now,</span> <span m=''1413070''>let''s</span>
  <span m=''1413220''>actually</span> <span m=''1413600''>do</span> <span m=''1413750''>something</span>
  <span m=''1414060''>a</span> <span m=''1414170''>little</span> <span m=''1414280''>bit</span>
  <span m=''1414410''>more</span> <span m=''1414600''>interesting.</span> <span m=''1416070''>Let''s</span>
  <span m=''1417640''>look</span> <span m=''1417910''>at</span> <span m=''1417980''>the</span>
  <span m=''1418070''>expression</span> <span m=''1423640''>the</span> <span m=''1423710''>sum</span>
  <span m=''1425310''>of</span> <span m=''1425450''>x</span> <span m=''1427320''>and</span>
  <span m=''1427510''>y.</span> <span m=''1429678''>OK.</span> <span m=''1430130''>And</span>
  <span m=''1430220''>now</span> <span m=''1430310''>we''ll</span> <span m=''1430440''>see</span>
  <span m=''1430620''>how</span> <span m=''1430730''>you</span> <span m=''1430870''>start</span>
  <span m=''1432670''>unrolling</span> <span m=''1433040''>these</span> <span m=''1433240''>expression</span>
  <span m=''1433660''>trees,</span> <span m=''1435600''>OK?</span> </p><p><span m=''1437100''>Well,</span>
  <span m=''1437390''>start</span> <span m=''1437610''>again</span> <span m=''1437810''>at</span>
  <span m=''1438160''>eval-dispatch,</span> <span m=''1439655''>all</span> <span m=''1440150''>right?</span>
  <span m=''1444610''>Self-evaluating?</span> <span m=''1446060''>No.</span> <span
  m=''1446810''>Variable?</span> <span m=''1447280''>No.</span> <span m=''1447850''>All</span>
  <span m=''1448140''>the</span> <span m=''1448260''>other</span> <span m=''1448390''>special</span>
  <span m=''1448740''>forms</span> <span m=''1449010''>which</span> <span m=''1449160''>I</span>
  <span m=''1449210''>didn''t</span> <span m=''1449460''>write</span> <span m=''1449660''>down,</span>
  <span m=''1450270''>like</span> <span m=''1450360''>quote,</span> <span m=''1450810''>and</span>
  <span m=''1451050''>lambda,</span> <span m=''1451560''>and</span> <span m=''1451720''>set,</span>
  <span m=''1452040''>and</span> <span m=''1452260''>whatever,</span> <span m=''1452480''>it''s</span>
  <span m=''1452600''>none</span> <span m=''1452770''>of</span> <span m=''1452840''>those.</span>
  <span m=''1453260''>It</span> <span m=''1453390''>turns</span> <span m=''1453520''>out</span>
  <span m=''1453630''>to</span> <span m=''1453690''>be</span> <span m=''1453790''>an</span>
  <span m=''1453860''>application,</span> <span m=''1455840''>so</span> <span m=''1456010''>we</span>
  <span m=''1456110''>go</span> <span m=''1456270''>off</span> <span m=''1456430''>to</span>
  <span m=''1456520''>ev-application,</span> <span m=''1458695''>OK?</span> <span
  m=''1459970''>Ev-application,</span> <span m=''1462770''>remember</span> <span m=''1463520''>what</span>
  <span m=''1463750''>it''s</span> <span m=''1463970''>going</span> <span m=''1464080''>to</span>
  <span m=''1464150''>do</span> <span m=''1464390''>overall.</span> <span m=''1465580''>It</span>
  <span m=''1465680''>is</span> <span m=''1465780''>going</span> <span m=''1465870''>to</span>
  <span m=''1465940''>evaluate</span> <span m=''1467250''>the</span> <span m=''1467420''>operator.</span>
  <span m=''1468310''>It''s</span> <span m=''1468510''>going</span> <span m=''1468620''>to</span>
  <span m=''1468700''>evaluate</span> <span m=''1469850''>the</span> <span m=''1470770''>arguments,</span>
  <span m=''1472470''>and</span> <span m=''1472590''>then</span> <span m=''1472710''>it''s</span>
  <span m=''1472850''>going</span> <span m=''1472950''>to</span> <span m=''1472990''>go</span>
  <span m=''1473630''>apply</span> <span m=''1474010''>them.</span> <span m=''1475060''>So,</span>
  <span m=''1475210''>before</span> <span m=''1475530''>we</span> <span m=''1475640''>start,</span>
  <span m=''1476940''>since</span> <span m=''1477140''>we''re</span> <span m=''1477230''>being</span>
  <span m=''1477430''>very</span> <span m=''1477640''>literal,</span> <span m=''1478000''>we''d</span>
  <span m=''1478140''>better</span> <span m=''1478320''>remember</span> <span m=''1479110''>that,</span>
  <span m=''1479290''>somewhere</span> <span m=''1479720''>in</span> <span m=''1479800''>this</span>
  <span m=''1479980''>environment,</span> <span m=''1480610''>it''s</span> <span m=''1480760''>linked</span>
  <span m=''1481310''>to</span> <span m=''1481460''>another</span> <span m=''1481780''>environment</span>
  <span m=''1484060''>in</span> <span m=''1484220''>which</span> <span m=''1484440''>plus</span>
  <span m=''1485515''>is</span> <span m=''1486010''>bound</span> <span m=''1486330''>to</span>
  <span m=''1486460''>the</span> <span m=''1486560''>primitive</span> <span m=''1487020''>procedure</span>
  <span m=''1488590''>plus</span> <span m=''1491550''>before</span> <span m=''1491810''>we</span>
  <span m=''1492260''>get</span> <span m=''1492380''>an</span> <span m=''1492480''>unknown</span>
  <span m=''1492890''>variable</span> <span m=''1493360''>in</span> <span m=''1493550''>our</span>
  <span m=''1493620''>machine.</span> </p><p><span m=''1495340''>OK,</span> <span
  m=''1495600''>so</span> <span m=''1495730''>we''re</span> <span m=''1496030''>at</span>
  <span m=''1496105''>ev-application.</span> <span m=''1499850''>OK,</span> <span
  m=''1500130''>assign</span> <span m=''1501310''>to</span> <span m=''1502070''>UNEV</span>
  <span m=''1503290''>the</span> <span m=''1503440''>operands</span> <span m=''1504980''>of</span>
  <span m=''1505420''>what''s</span> <span m=''1505730''>in</span> <span m=''1505800''>the</span>
  <span m=''1505920''>expression</span> <span m=''1506340''>register,</span> <span
  m=''1507542''>OK?</span> <span m=''1507920''>Those</span> <span m=''1508080''>are</span>
  <span m=''1508130''>the</span> <span m=''1508270''>operands.</span> <span m=''1509230''>UNEV''s</span>
  <span m=''1509590''>a</span> <span m=''1509630''>temporary</span> <span m=''1511200''>register</span>
  <span m=''1511650''>where</span> <span m=''1511800''>we''re</span> <span m=''1511920''>going</span>
  <span m=''1512010''>to</span> <span m=''1512060''>save</span> <span m=''1512400''>them.</span>
  </p><p><span m=''1512916''>PROFESSOR:</span> <span m=''1513262''>I''m</span> <span
  m=''1513610''>assigning.</span> </p><p><span m=''1513860''>PROFESSOR:</span> <span
  m=''1514320''>Assign</span> <span m=''1514690''>to</span> <span m=''1514790''>x</span>
  <span m=''1515790''>the</span> <span m=''1515960''>operator.</span> <span m=''1518070''>Now,</span>
  <span m=''1518210''>notice</span> <span m=''1518510''>we''ve</span> <span m=''1518630''>destroyed</span>
  <span m=''1519110''>that</span> <span m=''1519250''>expression</span> <span m=''1519730''>in</span>
  <span m=''1519820''>x,</span> <span m=''1521930''>but</span> <span m=''1522060''>the</span>
  <span m=''1522140''>piece</span> <span m=''1522380''>that</span> <span m=''1522510''>we</span>
  <span m=''1522620''>need</span> <span m=''1522840''>is</span> <span m=''1522940''>now</span>
  <span m=''1523140''>in</span> <span m=''1523260''>UNEV.</span> <span m=''1524790''>OK.</span>
  <span m=''1525820''>Now,</span> <span m=''1525990''>we''re</span> <span m=''1526070''>going</span>
  <span m=''1526150''>to</span> <span m=''1526190''>get</span> <span m=''1526370''>set</span>
  <span m=''1526540''>up</span> <span m=''1526650''>to</span> <span m=''1526760''>recursively</span>
  <span m=''1527490''>evaluate</span> <span m=''1528010''>the</span> <span m=''1528120''>operator.</span>
  <span m=''1528750''>Save</span> <span m=''1529420''>the</span> <span m=''1529540''>continue</span>
  <span m=''1529970''>register</span> <span m=''1531030''>on</span> <span m=''1531190''>the</span>
  <span m=''1531250''>stack.</span> <span m=''1534870''>Save</span> <span m=''1535230''>the</span>
  <span m=''1535370''>environment.</span> <span m=''1540520''>Save</span> <span m=''1541210''>UNEV.</span>
  <span m=''1549272''>OK,</span> <span m=''1549780''>assign</span> <span m=''1551310''>to</span>
  <span m=''1551500''>continue</span> <span m=''1553100''>a</span> <span m=''1553210''>label</span>
  <span m=''1553550''>called</span> <span m=''1553920''>eval-args.</span> </p><p><span
  m=''1561400''>Now,</span> <span m=''1561480''>what</span> <span m=''1561620''>have</span>
  <span m=''1561660''>we</span> <span m=''1561790''>done?</span> <span m=''1561980''>We''ve</span>
  <span m=''1562070''>set</span> <span m=''1562520''>up</span> <span m=''1563360''>for</span>
  <span m=''1563465''>a</span> <span m=''1563570''>recursive</span> <span m=''1564180''>call.</span>
  <span m=''1564380''>We''re</span> <span m=''1564520''>about</span> <span m=''1564790''>to</span>
  <span m=''1564870''>go</span> <span m=''1564990''>to</span> <span m=''1565130''>eval-dispatch.</span>
  <span m=''1566280''>We''ve</span> <span m=''1566450''>set</span> <span m=''1566620''>up</span>
  <span m=''1566730''>for</span> <span m=''1566860''>a</span> <span m=''1566910''>recursive</span>
  <span m=''1567500''>call</span> <span m=''1567810''>to</span> <span m=''1567920''>eval-dispatch.</span>
  <span m=''1570230''>What</span> <span m=''1570280''>did</span> <span m=''1570330''>we</span>
  <span m=''1570450''>do?</span> <span m=''1571020''>We</span> <span m=''1571160''>took</span>
  <span m=''1571350''>the</span> <span m=''1571440''>things</span> <span m=''1572420''>we''re</span>
  <span m=''1572540''>going</span> <span m=''1572620''>to</span> <span m=''1572700''>need</span>
  <span m=''1573230''>later,</span> <span m=''1574570''>those</span> <span m=''1574750''>operands</span>
  <span m=''1575240''>that</span> <span m=''1575390''>were</span> <span m=''1575470''>in</span>
  <span m=''1575550''>UNEV;</span> <span m=''1576470''>the</span> <span m=''1576670''>environment</span>
  <span m=''1577420''>in</span> <span m=''1577550''>which</span> <span m=''1577750''>we''re</span>
  <span m=''1577860''>going</span> <span m=''1577960''>to</span> <span m=''1578080''>eventually</span>
  <span m=''1578510''>have</span> <span m=''1578720''>to,</span> <span m=''1579220''>maybe,</span>
  <span m=''1579490''>evaluate</span> <span m=''1579930''>those</span> <span m=''1580100''>operands;</span>
  <span m=''1582330''>the</span> <span m=''1582420''>place</span> <span m=''1582750''>we</span>
  <span m=''1582900''>eventually</span> <span m=''1583290''>want</span> <span m=''1583430''>to</span>
  <span m=''1583470''>go</span> <span m=''1583680''>to,</span> <span m=''1583910''>which,</span>
  <span m=''1584070''>in</span> <span m=''1584140''>this</span> <span m=''1584280''>case,</span>
  <span m=''1584520''>was</span> <span m=''1584680''>done;</span> <span m=''1585290''>we''ve</span>
  <span m=''1585520''>saved</span> <span m=''1585910''>them</span> <span m=''1586110''>on</span>
  <span m=''1586210''>the</span> <span m=''1586310''>stack.</span> <span m=''1587120''>The</span>
  <span m=''1587210''>reason</span> <span m=''1587430''>we</span> <span m=''1587530''>saved</span>
  <span m=''1587770''>them</span> <span m=''1587880''>on</span> <span m=''1587990''>the</span>
  <span m=''1588070''>stack</span> <span m=''1588450''>is</span> <span m=''1588540''>because</span>
  <span m=''1589120''>eval-dispatch</span> <span m=''1589530''>makes</span> <span
  m=''1589750''>no</span> <span m=''1589930''>promises</span> <span m=''1591000''>about</span>
  <span m=''1591250''>what</span> <span m=''1591400''>registers</span> <span m=''1591860''>it</span>
  <span m=''1591970''>may</span> <span m=''1592080''>destroy.</span> <span m=''1593550''>So</span>
  <span m=''1593710''>all</span> <span m=''1593825''>that</span> <span m=''1593940''>stuff</span>
  <span m=''1594180''>is</span> <span m=''1594280''>saved</span> <span m=''1594580''>on</span>
  <span m=''1594670''>the</span> <span m=''1594740''>stack.</span> </p><p><span m=''1595020''>Now,</span>
  <span m=''1595180''>we''ve</span> <span m=''1595280''>set</span> <span m=''1595540''>up</span>
  <span m=''1595710''>eval-dispatch''s</span> <span m=''1596430''>contract.</span>
  <span m=''1597380''>There''s</span> <span m=''1598040''>a</span> <span m=''1598150''>new</span>
  <span m=''1598350''>expression,</span> <span m=''1598860''>which</span> <span m=''1599030''>is</span>
  <span m=''1599090''>the</span> <span m=''1599220''>operator</span> <span m=''1599620''>plus;</span>
  <span m=''1601120''>a</span> <span m=''1601220''>new</span> <span m=''1601400''>environment,</span>
  <span m=''1601990''>although,</span> <span m=''1602180''>in</span> <span m=''1602250''>this</span>
  <span m=''1602380''>case,</span> <span m=''1602600''>it''s</span> <span m=''1602720''>the</span>
  <span m=''1602790''>same</span> <span m=''1603080''>one;</span> <span m=''1604250''>and</span>
  <span m=''1604440''>a</span> <span m=''1604460''>new</span> <span m=''1604620''>place</span>
  <span m=''1604900''>to</span> <span m=''1605000''>go</span> <span m=''1605200''>to</span>
  <span m=''1605400''>when</span> <span m=''1605530''>you''re</span> <span m=''1605670''>done,</span>
  <span m=''1605850''>which</span> <span m=''1606040''>is</span> <span m=''1606320''>eval-args.</span>
  <span m=''1607600''>So</span> <span m=''1607740''>that''s</span> <span m=''1608000''>set</span>
  <span m=''1608065''>up.</span> <span m=''1608130''>Now,</span> <span m=''1608290''>we''re</span>
  <span m=''1608360''>going</span> <span m=''1608440''>to</span> <span m=''1608480''>go</span>
  <span m=''1608610''>off</span> <span m=''1608710''>to</span> <span m=''1608860''>eval-dispatch.</span>
  <span m=''1610890''>Here</span> <span m=''1610980''>we</span> <span m=''1611070''>are</span>
  <span m=''1611160''>back</span> <span m=''1611430''>at</span> <span m=''1611500''>eval-dispatch.</span>
  <span m=''1613090''>It''s</span> <span m=''1613280''>not</span> <span m=''1613520''>self-evaluating.</span>
  <span m=''1614490''>Oh,</span> <span m=''1614660''>it''s</span> <span m=''1614860''>a</span>
  <span m=''1614910''>variable,</span> <span m=''1616280''>so</span> <span m=''1616440''>we''d</span>
  <span m=''1616550''>better</span> <span m=''1616760''>go</span> <span m=''1616920''>off</span>
  <span m=''1617060''>to</span> <span m=''1617270''>ev-variable,</span> <span m=''1619830''>right?</span>
  <span m=''1620260''>Ev-variable</span> <span m=''1620840''>is</span> <span m=''1620930''>assigned</span>
  <span m=''1621960''>to</span> <span m=''1622080''>VAL.</span> <span m=''1622880''>Look</span>
  <span m=''1623250''>up</span> <span m=''1624140''>the</span> <span m=''1624380''>variable</span>
  <span m=''1624850''>value</span> <span m=''1625560''>of</span> <span m=''1625680''>the</span>
  <span m=''1625780''>expression,</span> <span m=''1628284''>OK?</span> <span m=''1628770''>So</span>
  <span m=''1628950''>VAL</span> <span m=''1629040''>is</span> <span m=''1629270''>the</span>
  <span m=''1629350''>primitive</span> <span m=''1629830''>procedure</span> <span
  m=''1630320''>plus,</span> <span m=''1632558''>OK?</span> <span m=''1633000''>And</span>
  <span m=''1633430''>go</span> <span m=''1633670''>to</span> <span m=''1634180''>fetch</span>
  <span m=''1634480''>of</span> <span m=''1634670''>continue.</span> </p><p><span
  m=''1635020''>PROFESSOR:</span> <span m=''1635370''>Eval-args.</span> </p><p><span
  m=''1635660''>PROFESSOR:</span> <span m=''1635970''>Right,</span> <span m=''1637070''>which</span>
  <span m=''1637460''>is</span> <span m=''1637550''>now</span> <span m=''1637830''>eval-args</span>
  <span m=''1638260''>not</span> <span m=''1638430''>done.</span> <span m=''1639340''>So</span>
  <span m=''1639540''>we</span> <span m=''1639950''>come</span> <span m=''1640100''>back</span>
  <span m=''1640320''>here</span> <span m=''1640560''>at</span> <span m=''1640810''>eval-args,</span>
  <span m=''1641972''>and</span> <span m=''1642310''>what</span> <span m=''1642520''>do</span>
  <span m=''1642580''>we</span> <span m=''1642680''>do?</span> <span m=''1643210''>We''re</span>
  <span m=''1643320''>going</span> <span m=''1643410''>to</span> <span m=''1643450''>restore</span>
  <span m=''1643820''>the</span> <span m=''1643920''>stuff</span> <span m=''1644200''>that</span>
  <span m=''1644320''>we</span> <span m=''1644440''>saved,</span> <span m=''1645190''>so</span>
  <span m=''1645330''>we</span> <span m=''1645620''>restore</span> <span m=''1646090''>UNEV.</span>
  <span m=''1649360''>And</span> <span m=''1649520''>notice,</span> <span m=''1649680''>there,</span>
  <span m=''1650470''>it</span> <span m=''1650790''>wasn''t</span> <span m=''1651000''>necessary,</span>
  <span m=''1651710''>although,</span> <span m=''1651900''>in</span> <span m=''1652090''>general,</span>
  <span m=''1652500''>it</span> <span m=''1652600''>would</span> <span m=''1652700''>be.</span>
  <span m=''1652900''>It</span> <span m=''1653030''>might</span> <span m=''1653160''>be</span>
  <span m=''1653250''>some</span> <span m=''1653480''>arbitrary</span> <span m=''1654040''>evaluation</span>
  <span m=''1654620''>that</span> <span m=''1654740''>happened.</span> <span m=''1655430''>We</span>
  <span m=''1655650''>restore</span> <span m=''1656200''>ENV.</span> <span m=''1667980''>OK,</span>
  <span m=''1668090''>we</span> <span m=''1668330''>assign</span> <span m=''1669050''>to</span>
  <span m=''1669210''>FUN</span> <span m=''1670730''>fetch</span> <span m=''1671080''>of</span>
  <span m=''1671580''>VAL.</span> </p><p><span m=''1678620''>OK,</span> <span m=''1680070''>now,</span>
  <span m=''1680270''>we''re</span> <span m=''1680830''>going</span> <span m=''1680950''>to</span>
  <span m=''1680990''>go</span> <span m=''1681190''>off</span> <span m=''1681330''>and</span>
  <span m=''1681420''>start</span> <span m=''1681650''>evaluating</span> <span m=''1682150''>some</span>
  <span m=''1682330''>arguments.</span> <span m=''1684340''>Well,</span> <span m=''1684500''>first</span>
  <span m=''1684740''>thing</span> <span m=''1684850''>we''d</span> <span m=''1684950''>better</span>
  <span m=''1685170''>do</span> <span m=''1685310''>is</span> <span m=''1685440''>save</span>
  <span m=''1685930''>FUN</span> <span m=''1687550''>because</span> <span m=''1687600''>some</span>
  <span m=''1688330''>arbitrary</span> <span m=''1688830''>stuff</span> <span m=''1689060''>might</span>
  <span m=''1689270''>happen</span> <span m=''1689600''>in</span> <span m=''1689730''>that</span>
  <span m=''1689860''>evaluation.</span> <span m=''1695330''>We</span> <span m=''1695560''>initialize</span>
  <span m=''1696180''>the</span> <span m=''1696290''>argument</span> <span m=''1696650''>list.</span>
  <span m=''1696860''>Assign</span> <span m=''1697230''>to</span> <span m=''1697330''>argl</span>
  <span m=''1698120''>an</span> <span m=''1698240''>empty</span> <span m=''1698590''>argument</span>
  <span m=''1699000''>list,</span> <span m=''1700605''>and</span> <span m=''1700990''>go</span>
  <span m=''1701160''>to</span> <span m=''1701330''>eval-arg-loop,</span> <span m=''1704646''>OK?</span>
  <span m=''1705460''>At</span> <span m=''1705550''>eval-arg-loop,</span> <span m=''1707800''>the</span>
  <span m=''1707950''>idea</span> <span m=''1708280''>of</span> <span m=''1708370''>this</span>
  <span m=''1708560''>is</span> <span m=''1708670''>we''re</span> <span m=''1708770''>going</span>
  <span m=''1708860''>to</span> <span m=''1709580''>evaluate</span> <span m=''1710820''>the</span>
  <span m=''1710910''>pieces</span> <span m=''1711290''>of</span> <span m=''1711380''>the</span>
  <span m=''1711490''>expressions</span> <span m=''1712060''>that</span> <span m=''1712180''>are</span>
  <span m=''1712300''>in</span> <span m=''1712490''>UNEV,</span> <span m=''1712620''>one</span>
  <span m=''1712850''>by</span> <span m=''1713000''>one,</span> <span m=''1713660''>and</span>
  <span m=''1713800''>move</span> <span m=''1714040''>them</span> <span m=''1714180''>from</span>
  <span m=''1714360''>unevaluated</span> <span m=''1714845''>in</span> <span m=''1715180''>UNEV</span>
  <span m=''1715940''>to</span> <span m=''1716110''>evaluated</span> <span m=''1716455''>in</span>
  <span m=''1716800''>the</span> <span m=''1716930''>arg</span> <span m=''1717060''>list,</span>
  <span m=''1717870''>OK?</span> <span m=''1718090''>So</span> <span m=''1718220''>we</span>
  <span m=''1718340''>save</span> <span m=''1718780''>argl.</span> <span m=''1723950''>We</span>
  <span m=''1724100''>assign</span> <span m=''1725220''>to</span> <span m=''1725510''>x</span>
  <span m=''1725940''>the</span> <span m=''1726090''>first</span> <span m=''1726550''>operand</span>
  <span m=''1727440''>of</span> <span m=''1727560''>the</span> <span m=''1727640''>stuff</span>
  <span m=''1728070''>in</span> <span m=''1728200''>UNEV.</span> </p><p><span m=''1733960''>Now,</span>
  <span m=''1734070''>we</span> <span m=''1734170''>check</span> <span m=''1734400''>and</span>
  <span m=''1734510''>see</span> <span m=''1734640''>if</span> <span m=''1734730''>that</span>
  <span m=''1734900''>was</span> <span m=''1735030''>the</span> <span m=''1735110''>last</span>
  <span m=''1735450''>operand.</span> <span m=''1735890''>In</span> <span m=''1735960''>this</span>
  <span m=''1736100''>case,</span> <span m=''1736340''>it</span> <span m=''1736430''>is</span>
  <span m=''1736530''>not,</span> <span m=''1738736''>all</span> <span m=''1738963''>right?</span>
  <span m=''1739190''>So</span> <span m=''1739380''>we</span> <span m=''1739690''>save</span>
  <span m=''1740850''>the</span> <span m=''1740950''>environment.</span> <span m=''1749170''>We</span>
  <span m=''1749280''>save</span> <span m=''1749630''>UNEV</span> <span m=''1751760''>because</span>
  <span m=''1751980''>those</span> <span m=''1752140''>are</span> <span m=''1752210''>all</span>
  <span m=''1752410''>things</span> <span m=''1752620''>we</span> <span m=''1752710''>might</span>
  <span m=''1752910''>need</span> <span m=''1753080''>later.</span> <span m=''1753500''>We''re</span>
  <span m=''1753547''>going</span> <span m=''1753595''>to</span> <span m=''1753642''>need</span>
  <span m=''1753690''>the</span> <span m=''1753890''>environment</span> <span m=''1754200''>to</span>
  <span m=''1754303''>do</span> <span m=''1754406''>some</span> <span m=''1754510''>more</span>
  <span m=''1754860''>evaluations.</span> <span m=''1755800''>We''re</span> <span
  m=''1755896''>going</span> <span m=''1755993''>to</span> <span m=''1756090''>need</span>
  <span m=''1756450''>UNEV</span> <span m=''1756580''>to</span> <span m=''1756710''>look</span>
  <span m=''1756800''>at</span> <span m=''1756890''>what</span> <span m=''1757030''>the</span>
  <span m=''1757100''>rest</span> <span m=''1758130''>of</span> <span m=''1758240''>those</span>
  <span m=''1758420''>arguments</span> <span m=''1758820''>were.</span> <span m=''1760340''>We''re</span>
  <span m=''1760560''>going</span> <span m=''1760670''>to</span> <span m=''1760730''>assign</span>
  <span m=''1761050''>continue</span> <span m=''1761660''>a</span> <span m=''1761720''>place</span>
  <span m=''1762000''>called</span> <span m=''1762170''>accumulate-args,</span> <span
  m=''1763250''>or</span> <span m=''1763900''>accumulate-arg.</span> </p><p><span
  m=''1770898''>OK,</span> <span m=''1771390''>now,</span> <span m=''1771540''>we''ve</span>
  <span m=''1771650''>set</span> <span m=''1771960''>up</span> <span m=''1772230''>for</span>
  <span m=''1772460''>another</span> <span m=''1772770''>call</span> <span m=''1773060''>to</span>
  <span m=''1773300''>eval-dispatch,</span> <span m=''1775630''>OK?</span> <span m=''1776810''>All</span>
  <span m=''1777005''>right,</span> <span m=''1777200''>now,</span> <span m=''1777333''>let</span>
  <span m=''1777466''>me</span> <span m=''1777600''>short-circuit</span> <span m=''1778250''>this</span>
  <span m=''1779170''>so</span> <span m=''1779320''>we</span> <span m=''1779390''>don''t</span>
  <span m=''1779510''>go</span> <span m=''1779590''>through</span> <span m=''1779730''>the</span>
  <span m=''1779830''>details</span> <span m=''1780250''>of</span> <span m=''1780390''>eval-dispatch.</span>
  <span m=''1781090''>Eval-dispatch''s</span> <span m=''1781830''>contract</span>
  <span m=''1782380''>says</span> <span m=''1782990''>I''m</span> <span m=''1783150''>going</span>
  <span m=''1783300''>to</span> <span m=''1784510''>end</span> <span m=''1784840''>up,</span>
  <span m=''1785170''>the</span> <span m=''1785260''>world</span> <span m=''1785550''>will</span>
  <span m=''1785680''>end</span> <span m=''1785890''>up,</span> <span m=''1786060''>with</span>
  <span m=''1786210''>the</span> <span m=''1786270''>value</span> <span m=''1786730''>of</span>
  <span m=''1786850''>evaluating</span> <span m=''1787420''>this</span> <span m=''1787590''>expression</span>
  <span m=''1788330''>in</span> <span m=''1788480''>this</span> <span m=''1788660''>environment</span>
  <span m=''1789490''>in</span> <span m=''1789555''>the</span> <span m=''1789620''>VAL</span>
  <span m=''1789820''>register,</span> <span m=''1790270''>and</span> <span m=''1790380''>I''ll</span>
  <span m=''1790520''>end</span> <span m=''1790660''>up</span> <span m=''1790810''>there.</span>
  <span m=''1791320''>So</span> <span m=''1791445''>we</span> <span m=''1791570''>short-circuit</span>
  <span m=''1792100''>all</span> <span m=''1792193''>of</span> <span m=''1792286''>this,</span>
  <span m=''1794460''>and</span> <span m=''1795100''>a</span> <span m=''1795180''>3</span>
  <span m=''1795540''>ends</span> <span m=''1795700''>up</span> <span m=''1795830''>in</span>
  <span m=''1795980''>VAL.</span> <span m=''1798010''>And,</span> <span m=''1798250''>when</span>
  <span m=''1798370''>we</span> <span m=''1798440''>return</span> <span m=''1798920''>from</span>
  <span m=''1799210''>eval-dispatch,</span> <span m=''1799820''>we''re</span> <span
  m=''1799900''>going</span> <span m=''1800000''>to</span> <span m=''1800050''>return</span>
  <span m=''1800790''>to</span> <span m=''1800940''>accumulate-arg.</span> </p><p><span
  m=''1802110''>PROFESSOR:</span> <span m=''1802460''>Accumulate-arg.</span> </p><p><span
  m=''1803555''>PROFESSOR:</span> <span m=''1806300''>With</span> <span m=''1806390''>3</span>
  <span m=''1806640''>in</span> <span m=''1806710''>the</span> <span m=''1806780''>VAL</span>
  <span m=''1807000''>register,</span> <span m=''1807740''>OK?</span> <span m=''1808720''>So</span>
  <span m=''1808850''>that</span> <span m=''1808990''>short-circuited</span> <span
  m=''1809700''>that</span> <span m=''1809830''>evaluation.</span> <span m=''1810650''>Now,</span>
  <span m=''1810790''>what</span> <span m=''1810900''>do</span> <span m=''1811010''>we</span>
  <span m=''1811130''>do?</span> <span m=''1811320''>We''re</span> <span m=''1811430''>going</span>
  <span m=''1811485''>to</span> <span m=''1811540''>go</span> <span m=''1811680''>back</span>
  <span m=''1811870''>and</span> <span m=''1811950''>look</span> <span m=''1812070''>at</span>
  <span m=''1812190''>the</span> <span m=''1812260''>rest</span> <span m=''1813010''>of</span>
  <span m=''1813120''>the</span> <span m=''1813230''>arguments,</span> <span m=''1813690''>so</span>
  <span m=''1813840''>we</span> <span m=''1813990''>restore</span> <span m=''1814390''>UNEV.</span>
  <span m=''1817820''>We</span> <span m=''1818180''>restore</span> <span m=''1818580''>ENV.</span>
  <span m=''1825530''>We</span> <span m=''1826040''>restore</span> <span m=''1826580''>argl.</span>
  <span m=''1828650''>One</span> <span m=''1828910''>thing.</span> </p><p><span m=''1829170''>PROFESSOR:</span>
  <span m=''1829565''>Oops!</span> <span m=''1830750''>Parity</span> <span m=''1831030''>error.</span>
  </p><p><span m=''1831290''>[LAUGHTER]</span> </p><p><span m=''1833465''>PROFESSOR:</span>
  <span m=''1833900''>Restore</span> <span m=''1834530''>argl.</span> </p><p><span
  m=''1841650''>PROFESSOR:</span> <span m=''1842140''>OK.</span> <span m=''1845570''>OK,</span>
  <span m=''1845720''>we</span> <span m=''1845890''>assign</span> <span m=''1846630''>to</span>
  <span m=''1846880''>argl</span> <span m=''1848850''>consing</span> <span m=''1849320''>on</span>
  <span m=''1850640''>fetch</span> <span m=''1850920''>of</span> <span m=''1851010''>the</span>
  <span m=''1851100''>value</span> <span m=''1851460''>register</span> <span m=''1851880''>to</span>
  <span m=''1851990''>what''s</span> <span m=''1852110''>in</span> <span m=''1852240''>argl.</span>
  <span m=''1858985''>OK,</span> <span m=''1859470''>we</span> <span m=''1860200''>assign</span>
  <span m=''1860600''>to</span> <span m=''1860740''>UNEV</span> <span m=''1861620''>the</span>
  <span m=''1861740''>rest</span> <span m=''1862060''>of</span> <span m=''1862120''>the</span>
  <span m=''1862240''>operands</span> <span m=''1863620''>in</span> <span m=''1863763''>fetch</span>
  <span m=''1863906''>of</span> <span m=''1864050''>UNEV,</span> <span m=''1869040''>and</span>
  <span m=''1869120''>we</span> <span m=''1869200''>go</span> <span m=''1869360''>back</span>
  <span m=''1869880''>to</span> <span m=''1869970''>eval-arg-loop.</span> </p><p><span
  m=''1871516''>PROFESSOR:</span> <span m=''1872010''>Eval-arg-loop.</span> </p><p><span
  m=''1872280''>PROFESSOR:</span> <span m=''1872430''>OK.</span> <span m=''1875880''>Now,</span>
  <span m=''1876010''>we''re</span> <span m=''1876135''>about</span> <span m=''1876260''>to</span>
  <span m=''1876310''>do</span> <span m=''1876360''>the</span> <span m=''1876490''>next</span>
  <span m=''1876630''>argument,</span> <span m=''1877660''>so</span> <span m=''1877780''>the</span>
  <span m=''1877930''>first</span> <span m=''1878090''>thing</span> <span m=''1878200''>we</span>
  <span m=''1878290''>do</span> <span m=''1878390''>is</span> <span m=''1878480''>save</span>
  <span m=''1878820''>argl.</span> <span m=''1885400''>OK,</span> <span m=''1885560''>we</span>
  <span m=''1885710''>assign</span> <span m=''1886340''>to</span> <span m=''1886520''>x</span>
  <span m=''1887130''>the</span> <span m=''1887230''>first</span> <span m=''1887610''>operand</span>
  <span m=''1889220''>of</span> <span m=''1889980''>fetch</span> <span m=''1890230''>of</span>
  <span m=''1890350''>UNEV.</span> <span m=''1894580''>OK,</span> <span m=''1895060''>we</span>
  <span m=''1895220''>test</span> <span m=''1895530''>and</span> <span m=''1895630''>see</span>
  <span m=''1895800''>if</span> <span m=''1895890''>that''s</span> <span m=''1896130''>the</span>
  <span m=''1896210''>last</span> <span m=''1896630''>operand.</span> <span m=''1897140''>In</span>
  <span m=''1897210''>this</span> <span m=''1897360''>case,</span> <span m=''1897610''>it</span>
  <span m=''1897690''>is,</span> <span m=''1898852''>so</span> <span m=''1899051''>we''re</span>
  <span m=''1899250''>going</span> <span m=''1899370''>to</span> <span m=''1899420''>go</span>
  <span m=''1899560''>to</span> <span m=''1899640''>a</span> <span m=''1899690''>special</span>
  <span m=''1900040''>place</span> <span m=''1900320''>that</span> <span m=''1900450''>says</span>
  <span m=''1900650''>evaluate</span> <span m=''1901230''>the</span> <span m=''1901310''>last</span>
  <span m=''1901630''>argument</span> <span m=''1903440''>because,</span> <span m=''1903620''>notice,</span>
  <span m=''1903930''>after</span> <span m=''1904220''>evaluating</span> <span m=''1904720''>the</span>
  <span m=''1904810''>argument,</span> <span m=''1905110''>we</span> <span m=''1905200''>don''t</span>
  <span m=''1905370''>need</span> <span m=''1905500''>the</span> <span m=''1905600''>environment</span>
  <span m=''1906110''>any</span> <span m=''1906315''>more.</span> <span m=''1907446''>That''s</span>
  <span m=''1907678''>going</span> <span m=''1907910''>to</span> <span m=''1907975''>be</span>
  <span m=''1908040''>the</span> <span m=''1908180''>difference.</span> </p><p><span
  m=''1910250''>So</span> <span m=''1910430''>here,</span> <span m=''1910690''>at</span>
  <span m=''1910890''>eval-last-arg,</span> <span m=''1912220''>which</span> <span
  m=''1912470''>is</span> <span m=''1912580''>assigned</span> <span m=''1913000''>to</span>
  <span m=''1913090''>accumulate-last-arg,</span> <span m=''1924410''>now,</span>
  <span m=''1924560''>we''re</span> <span m=''1924650''>set</span> <span m=''1924880''>up</span>
  <span m=''1925090''>again</span> <span m=''1926030''>for</span> <span m=''1926220''>eval-dispatch.</span>
  <span m=''1926900''>We''ve</span> <span m=''1926980''>got</span> <span m=''1927170''>a</span>
  <span m=''1927210''>place</span> <span m=''1927470''>to</span> <span m=''1927560''>go</span>
  <span m=''1927750''>to</span> <span m=''1927910''>when</span> <span m=''1928030''>we''re</span>
  <span m=''1928140''>done.</span> <span m=''1928620''>We''ve</span> <span m=''1928820''>got</span>
  <span m=''1928970''>an</span> <span m=''1929070''>expression.</span> <span m=''1929840''>We''ve</span>
  <span m=''1929930''>got</span> <span m=''1930100''>an</span> <span m=''1930190''>environment.</span>
  <span m=''1931330''>OK,</span> <span m=''1931560''>so</span> <span m=''1931675''>we''ll</span>
  <span m=''1931790''>short-circuit</span> <span m=''1932390''>the</span> <span m=''1932480''>call</span>
  <span m=''1932600''>to</span> <span m=''1933060''>eval-dispatch.</span> <span m=''1934370''>And</span>
  <span m=''1934460''>what''ll</span> <span m=''1934660''>happen</span> <span m=''1934970''>is</span>
  <span m=''1935370''>there''s</span> <span m=''1935580''>a</span> <span m=''1935630''>y</span>
  <span m=''1935970''>there,</span> <span m=''1937290''>it''s</span> <span m=''1937550''>4</span>
  <span m=''1937860''>in</span> <span m=''1937920''>that</span> <span m=''1938090''>environment,</span>
  <span m=''1938580''>so</span> <span m=''1938710''>VAL</span> <span m=''1938840''>will</span>
  <span m=''1939140''>end</span> <span m=''1939280''>up</span> <span m=''1939380''>with</span>
  <span m=''1939530''>4</span> <span m=''1939870''>in</span> <span m=''1939900''>it.</span>
  <span m=''1941060''>And,</span> <span m=''1941125''>then,</span> <span m=''1941190''>we''re</span>
  <span m=''1941266''>going</span> <span m=''1941343''>to</span> <span m=''1941420''>end</span>
  <span m=''1941680''>up</span> <span m=''1941745''>at</span> <span m=''1941810''>accumulate-last-arg,</span>
  <span m=''1944454''>OK?</span> <span m=''1945450''>So,</span> <span m=''1945590''>at</span>
  <span m=''1945670''>accumulate-last-arg,</span> <span m=''1949290''>we</span> <span
  m=''1949440''>restore</span> <span m=''1949960''>argl.</span> <span m=''1961490''>We</span>
  <span m=''1961580''>assign</span> <span m=''1961890''>to</span> <span m=''1962070''>argl</span>
  <span m=''1962250''>cons</span> <span m=''1963810''>of</span> <span m=''1964400''>fetch</span>
  <span m=''1964560''>of</span> <span m=''1964660''>the</span> <span m=''1964760''>new</span>
  <span m=''1964920''>value</span> <span m=''1965280''>onto</span> <span m=''1965460''>it,</span>
  <span m=''1966000''>so</span> <span m=''1966105''>we</span> <span m=''1966210''>cons</span>
  <span m=''1966550''>a</span> <span m=''1966680''>4</span> <span m=''1966810''>onto</span>
  <span m=''1966950''>that.</span> <span m=''1969850''>We</span> <span m=''1970030''>restore</span>
  <span m=''1971020''>what</span> <span m=''1971160''>was</span> <span m=''1971290''>saved</span>
  <span m=''1971570''>in</span> <span m=''1971630''>the</span> <span m=''1971700''>function</span>
  <span m=''1972020''>register.</span> <span m=''1973446''>And</span> <span m=''1973920''>notice,</span>
  <span m=''1974330''>in</span> <span m=''1974490''>this</span> <span m=''1974680''>case,</span>
  <span m=''1974990''>it</span> <span m=''1975075''>had</span> <span m=''1975160''>not</span>
  <span m=''1975450''>been</span> <span m=''1975600''>destroyed,</span> <span m=''1976440''>but,</span>
  <span m=''1976590''>in</span> <span m=''1976700''>general,</span> <span m=''1977080''>it</span>
  <span m=''1977160''>will</span> <span m=''1977400''>be.</span> </p><p><span m=''1979420''>And</span>
  <span m=''1979550''>now,</span> <span m=''1979660''>we''re</span> <span m=''1979770''>ready</span>
  <span m=''1979990''>to</span> <span m=''1980050''>go</span> <span m=''1980220''>off</span>
  <span m=''1980380''>to</span> <span m=''1980510''>apply-dispatch,</span> <span m=''1982420''>all</span>
  <span m=''1982635''>right?</span> <span m=''1982850''>So</span> <span m=''1983010''>we''ve</span>
  <span m=''1983150''>just</span> <span m=''1983400''>gone</span> <span m=''1983590''>through</span>
  <span m=''1983770''>the</span> <span m=''1984010''>eval.</span> <span m=''1984510''>We</span>
  <span m=''1984672''>evaluated</span> <span m=''1985160''>the</span> <span m=''1985260''>argument,</span>
  <span m=''1986570''>the</span> <span m=''1986710''>operator,</span> <span m=''1987190''>and</span>
  <span m=''1987280''>the</span> <span m=''1987370''>arguments,</span> <span m=''1987980''>and</span>
  <span m=''1988100''>now,</span> <span m=''1988230''>we''re</span> <span m=''1988330''>about</span>
  <span m=''1988530''>to</span> <span m=''1988620''>apply</span> <span m=''1988940''>them.</span>
  <span m=''1989580''>So</span> <span m=''1989740''>we</span> <span m=''1989840''>come</span>
  <span m=''1990030''>off</span> <span m=''1990140''>to</span> <span m=''1990240''>apply-dispatch</span>
  <span m=''1991010''>here,</span> <span m=''1995096''>OK?</span> <span m=''1997481''>We</span>
  <span m=''1997960''>come</span> <span m=''1998160''>off</span> <span m=''1998270''>to</span>
  <span m=''1998390''>apply-dispatch,</span> <span m=''2001050''>and</span> <span
  m=''2001210''>we''re</span> <span m=''2001270''>going</span> <span m=''2001350''>to</span>
  <span m=''2001420''>check</span> <span m=''2001670''>whether</span> <span m=''2001890''>it''s</span>
  <span m=''2002000''>a</span> <span m=''2002040''>primitive</span> <span m=''2002460''>or</span>
  <span m=''2002505''>a</span> <span m=''2002550''>compound</span> <span m=''2003030''>procedure.</span>
  </p><p><span m=''2003450''>PROFESSOR:</span> <span m=''2003760''>Yes.</span> </p><p><span
  m=''2004116''>PROFESSOR:</span> <span m=''2004472''>All</span> <span m=''2004651''>right.</span>
  <span m=''2004830''>So,</span> <span m=''2005040''>in</span> <span m=''2005100''>this</span>
  <span m=''2005240''>case,</span> <span m=''2005460''>it''s</span> <span m=''2005570''>a</span>
  <span m=''2005630''>primitive</span> <span m=''2005940''>procedure,</span> <span
  m=''2007530''>and</span> <span m=''2007620''>we</span> <span m=''2007720''>go</span>
  <span m=''2007870''>off</span> <span m=''2008010''>to</span> <span m=''2008110''>primitive-apply.</span>
  <span m=''2009790''>So</span> <span m=''2009950''>we</span> <span m=''2010030''>go</span>
  <span m=''2010180''>off</span> <span m=''2010320''>to</span> <span m=''2010420''>primitive-apply,</span>
  <span m=''2013750''>and</span> <span m=''2013855''>it</span> <span m=''2013960''>says</span>
  <span m=''2014130''>assign</span> <span m=''2014800''>to</span> <span m=''2014930''>VAL</span>
  <span m=''2015750''>the</span> <span m=''2015860''>result</span> <span m=''2016320''>of</span>
  <span m=''2016440''>applying</span> <span m=''2017090''>primitive</span> <span m=''2017580''>procedure</span>
  <span m=''2018360''>of</span> <span m=''2018490''>the</span> <span m=''2018570''>function</span>
  <span m=''2019380''>to</span> <span m=''2019490''>the</span> <span m=''2019610''>argument</span>
  <span m=''2020010''>list.</span> </p><p><span m=''2020940''>PROFESSOR:</span> <span
  m=''2021390''>I</span> <span m=''2021530''>don''t</span> <span m=''2021680''>know</span>
  <span m=''2021750''>how</span> <span m=''2021940''>to</span> <span m=''2022090''>add.</span>
  <span m=''2022540''>I''m</span> <span m=''2022690''>just</span> <span m=''2022910''>an</span>
  <span m=''2022980''>execution</span> <span m=''2023460''>unit.</span> </p><p><span
  m=''2023995''>PROFESSOR:</span> <span m=''2024270''>Well,</span> <span m=''2024670''>I</span>
  <span m=''2024760''>don''t</span> <span m=''2024793''>know</span> <span m=''2024826''>how</span>
  <span m=''2024860''>to</span> <span m=''2025015''>add</span> <span m=''2025170''>either.</span>
  <span m=''2025350''>I''m</span> <span m=''2025440''>just</span> <span m=''2025640''>the</span>
  <span m=''2025870''>evaluator,</span> <span m=''2027030''>so</span> <span m=''2027200''>we</span>
  <span m=''2027290''>need</span> <span m=''2027370''>a</span> <span m=''2027450''>primitive</span>
  <span m=''2027830''>operator.</span> <span m=''2028360''>Let''s</span> <span m=''2028560''>see,</span>
  <span m=''2028932''>so</span> <span m=''2028955''>the</span> <span m=''2029000''>primitive</span>
  <span m=''2029360''>operator,</span> <span m=''2030990''>what''s</span> <span m=''2031210''>the</span>
  <span m=''2031290''>sum</span> <span m=''2031570''>of</span> <span m=''2031680''>3</span>
  <span m=''2031870''>and</span> <span m=''2032000''>4?</span> </p><p><span m=''2032605''>AUDIENCE:</span>
  <span m=''2032900''>7.</span> </p><p><span m=''2033205''>PROFESSOR:</span> <span
  m=''2033510''>OK,</span> <span m=''2034150''>7.</span> </p><p><span m=''2034580''>PROFESSOR:</span>
  <span m=''2035053''>Thank</span> <span m=''2035526''>you.</span> </p><p><span m=''2038837''>PROFESSOR:</span>
  <span m=''2039310''>Now,</span> <span m=''2039470''>we</span> <span m=''2039690''>restore</span>
  <span m=''2040000''>continue,</span> <span m=''2051174''>and</span> <span m=''2051659''>we</span>
  <span m=''2051830''>go</span> <span m=''2051989''>to</span> <span m=''2052070''>fetch</span>
  <span m=''2052330''>of</span> <span m=''2052420''>continue.</span> </p><p><span
  m=''2052900''>PROFESSOR:</span> <span m=''2053100''>Done.</span> </p><p><span m=''2053880''>PROFESSOR:</span>
  <span m=''2054260''>OK.</span> <span m=''2054929''>Well,</span> <span m=''2055110''>that</span>
  <span m=''2055239''>was</span> <span m=''2056750''>in</span> <span m=''2056909''>as</span>
  <span m=''2057030''>much</span> <span m=''2057270''>detail</span> <span m=''2057690''>as</span>
  <span m=''2057770''>you</span> <span m=''2057889''>will</span> <span m=''2058020''>ever</span>
  <span m=''2058239''>see.</span> <span m=''2058659''>We''ll</span> <span m=''2058779''>never</span>
  <span m=''2058900''>do</span> <span m=''2059030''>it</span> <span m=''2059110''>in</span>
  <span m=''2059195''>as</span> <span m=''2059280''>much</span> <span m=''2059469''>detail</span>
  <span m=''2059820''>again.</span> <span m=''2061590''>One</span> <span m=''2062489''>very</span>
  <span m=''2062900''>important</span> <span m=''2063260''>thing</span> <span m=''2063400''>to</span>
  <span m=''2063489''>notice</span> <span m=''2065020''>is</span> <span m=''2065199''>that</span>
  <span m=''2065449''>we</span> <span m=''2065550''>just</span> <span m=''2065780''>executed</span>
  <span m=''2066310''>a</span> <span m=''2066360''>recursive</span> <span m=''2066960''>procedure,</span>
  <span m=''2069340''>right?</span> <span m=''2069780''>This</span> <span m=''2069969''>whole</span>
  <span m=''2070270''>thing,</span> <span m=''2070489''>we</span> <span m=''2070600''>used</span>
  <span m=''2070790''>a</span> <span m=''2070850''>stack</span> <span m=''2071290''>and</span>
  <span m=''2071395''>the</span> <span m=''2071500''>evaluator</span> <span m=''2071669''>was</span>
  <span m=''2072179''>recursive.</span> <span m=''2073070''>A</span> <span m=''2073150''>lot</span>
  <span m=''2073389''>of</span> <span m=''2073460''>people</span> <span m=''2073780''>think</span>
  <span m=''2074270''>the</span> <span m=''2074370''>reason</span> <span m=''2074650''>that</span>
  <span m=''2074810''>you</span> <span m=''2074929''>need</span> <span m=''2075380''>a</span>
  <span m=''2075469''>stack</span> <span m=''2076480''>and</span> <span m=''2076670''>recursion</span>
  <span m=''2077110''>in</span> <span m=''2077310''>an</span> <span m=''2077400''>evaluator</span>
  <span m=''2077900''>is</span> <span m=''2078040''>because</span> <span m=''2078310''>you</span>
  <span m=''2078440''>might</span> <span m=''2078699''>be</span> <span m=''2079090''>evaluating</span>
  <span m=''2079690''>recursive</span> <span m=''2080139''>procedures</span> <span
  m=''2080639''>like</span> <span m=''2080810''>factorial</span> <span m=''2081350''>or</span>
  <span m=''2081429''>Fibonacci.</span> <span m=''2082150''>It''s</span> <span m=''2082300''>not</span>
  <span m=''2082560''>true.</span> <span m=''2083670''>So</span> <span m=''2083740''>you</span>
  <span m=''2083810''>notice</span> <span m=''2084080''>we</span> <span m=''2084179''>did</span>
  <span m=''2084320''>recursion</span> <span m=''2084420''>here,</span> <span m=''2084690''>and</span>
  <span m=''2085050''>all</span> <span m=''2085230''>we</span> <span m=''2085370''>evaluated</span>
  <span m=''2085929''>was</span> <span m=''2086110''>plus</span> <span m=''2086380''>X,</span>
  <span m=''2086570''>Y,</span> <span m=''2087622''>all</span> <span m=''2087816''>right?</span>
  <span m=''2088010''>The</span> <span m=''2088100''>reason</span> <span m=''2088690''>that</span>
  <span m=''2088850''>you</span> <span m=''2088960''>need</span> <span m=''2089120''>recursion</span>
  <span m=''2089210''>in</span> <span m=''2089540''>the</span> <span m=''2089870''>evaluator</span>
  <span m=''2091040''>is</span> <span m=''2091219''>because</span> <span m=''2091530''>the</span>
  <span m=''2091670''>evaluation</span> <span m=''2092540''>process,</span> <span
  m=''2093010''>itself,</span> <span m=''2093429''>is</span> <span m=''2093550''>recursive,</span>
  <span m=''2094394''>all</span> <span m=''2094522''>right?</span> <span m=''2094780''>It''s</span>
  <span m=''2094909''>not</span> <span m=''2095100''>because</span> <span m=''2095389''>the</span>
  <span m=''2095480''>procedure</span> <span m=''2096330''>that</span> <span m=''2096480''>you</span>
  <span m=''2096630''>might</span> <span m=''2096909''>be</span> <span m=''2097070''>evaluating</span>
  <span m=''2097760''>in</span> <span m=''2097920''>LISP</span> <span m=''2098180''>is</span>
  <span m=''2098300''>a</span> <span m=''2098350''>recursive</span> <span m=''2098800''>procedure.</span>
  <span m=''2099270''>So</span> <span m=''2099380''>that''s</span> <span m=''2099580''>an</span>
  <span m=''2099990''>important</span> <span m=''2100410''>thing</span> <span m=''2100550''>that</span>
  <span m=''2100680''>people</span> <span m=''2100950''>get</span> <span m=''2101130''>confused</span>
  <span m=''2101590''>about</span> <span m=''2101620''>a</span> <span m=''2101860''>lot.</span>
  </p><p><span m=''2103010''>The</span> <span m=''2103140''>other</span> <span m=''2103290''>thing</span>
  <span m=''2103450''>to</span> <span m=''2103560''>notice</span> <span m=''2103940''>is</span>
  <span m=''2104070''>that,</span> <span m=''2104260''>when</span> <span m=''2104690''>we''re</span>
  <span m=''2104850''>done</span> <span m=''2105180''>here,</span> <span m=''2106280''>we''re</span>
  <span m=''2106580''>really</span> <span m=''2106840''>done.</span> <span m=''2107120''>Not</span>
  <span m=''2107260''>only</span> <span m=''2107490''>are</span> <span m=''2107540''>we</span>
  <span m=''2107790''>at</span> <span m=''2108100''>done,</span> <span m=''2109470''>but</span>
  <span m=''2111100''>there''s</span> <span m=''2111490''>no</span> <span m=''2111670''>accumulated</span>
  <span m=''2112310''>stuff</span> <span m=''2112600''>on</span> <span m=''2112730''>the</span>
  <span m=''2112810''>stack,</span> <span m=''2113320''>right?</span> <span m=''2113810''>The</span>
  <span m=''2113890''>machine</span> <span m=''2114160''>is</span> <span m=''2114300''>back</span>
  <span m=''2114670''>to</span> <span m=''2114870''>its</span> <span m=''2115000''>initial</span>
  <span m=''2115330''>state,</span> <span m=''2116765''>all</span> <span m=''2116967''>right?</span>
  <span m=''2117170''>So</span> <span m=''2117310''>that''s</span> <span m=''2117490''>part</span>
  <span m=''2117690''>of</span> <span m=''2117770''>what</span> <span m=''2117900''>it</span>
  <span m=''2117990''>means</span> <span m=''2118220''>to</span> <span m=''2118300''>be</span>
  <span m=''2118430''>done.</span> <span m=''2119830''>Another</span> <span m=''2120010''>way</span>
  <span m=''2120120''>to</span> <span m=''2120190''>say</span> <span m=''2120460''>that</span>
  <span m=''2120700''>is</span> <span m=''2122800''>the</span> <span m=''2124000''>evaluation</span>
  <span m=''2124710''>process</span> <span m=''2125150''>has</span> <span m=''2125300''>reduced</span>
  <span m=''2126410''>the</span> <span m=''2126540''>expression,</span> <span m=''2127100''>plus</span>
  <span m=''2127630''>X,</span> <span m=''2127900''>Y,</span> <span m=''2130510''>to</span>
  <span m=''2131430''>the</span> <span m=''2131540''>value</span> <span m=''2131910''>here,</span>
  <span m=''2132260''>7.</span> <span m=''2133460''>And</span> <span m=''2133520''>by</span>
  <span m=''2133580''>reduced,</span> <span m=''2134070''>I</span> <span m=''2134125''>mean</span>
  <span m=''2134260''>a</span> <span m=''2134290''>very</span> <span m=''2134600''>particular</span>
  <span m=''2135100''>thing.</span> <span m=''2136010''>It</span> <span m=''2136230''>means</span>
  <span m=''2136480''>that</span> <span m=''2136690''>there''s</span> <span m=''2136870''>nothing</span>
  <span m=''2137310''>left</span> <span m=''2137600''>on</span> <span m=''2137750''>the</span>
  <span m=''2137820''>stack.</span> <span m=''2138180''>The</span> <span m=''2138260''>machine</span>
  <span m=''2138540''>is</span> <span m=''2139140''>now</span> <span m=''2139460''>in</span>
  <span m=''2139540''>the</span> <span m=''2139620''>same</span> <span m=''2139900''>state,</span>
  <span m=''2141040''>except</span> <span m=''2141330''>there''s</span> <span m=''2141480''>something</span>
  <span m=''2141810''>in</span> <span m=''2141900''>the</span> <span m=''2141970''>value</span>
  <span m=''2142340''>register.</span> <span m=''2142760''>It''s</span> <span m=''2142890''>not</span>
  <span m=''2143100''>part</span> <span m=''2143300''>of</span> <span m=''2143350''>a</span>
  <span m=''2143410''>sub-problem</span> <span m=''2144050''>of</span> <span m=''2144150''>anything.</span>
  <span m=''2144520''>There''s</span> <span m=''2144680''>nothing</span> <span m=''2144960''>to</span>
  <span m=''2145010''>go</span> <span m=''2145140''>back</span> <span m=''2145440''>to.</span>
  <span m=''2146210''>OK.</span> <span m=''2146440''>Let''s</span> <span m=''2146650''>break.</span>
  <span m=''2149712''>Question?</span> </p><p><span m=''2150159''>AUDIENCE:</span>
  <span m=''2151060''>The</span> <span m=''2151370''>question</span> <span m=''2151630''>here,</span>
  <span m=''2153240''>in</span> <span m=''2153390''>the</span> <span m=''2153540''>stack,</span>
  <span m=''2154080''>is</span> <span m=''2154260''>because</span> <span m=''2154710''>the</span>
  <span m=''2154800''>data</span> <span m=''2155170''>may</span> <span m=''2155300''>be</span>
  <span m=''2155430''>recursive.</span> <span m=''2155820''>You</span> <span m=''2156360''>may</span>
  <span m=''2156510''>have</span> <span m=''2156850''>embedded</span> <span m=''2157310''>expressions,</span>
  <span m=''2157753''>for</span> <span m=''2157974''>instance.</span> </p><p><span
  m=''2159312''>PROFESSOR:</span> <span m=''2159650''>Yes,</span> <span m=''2160290''>because</span>
  <span m=''2160640''>you</span> <span m=''2160740''>might</span> <span m=''2160890''>have</span>
  <span m=''2161060''>embedded</span> <span m=''2161490''>expressions.</span> <span
  m=''2162080''>But,</span> <span m=''2162190''>again,</span> <span m=''2162480''>don''t</span>
  <span m=''2162700''>confuse</span> <span m=''2164060''>that</span> <span m=''2164920''>with</span>
  <span m=''2165470''>what</span> <span m=''2165670''>people</span> <span m=''2165940''>sometimes</span>
  <span m=''2166400''>mean</span> <span m=''2166560''>by</span> <span m=''2166680''>the</span>
  <span m=''2166812''>data</span> <span m=''2167210''>may</span> <span m=''2167510''>be</span>
  <span m=''2167630''>recursive,</span> <span m=''2168050''>which</span> <span m=''2168240''>is</span>
  <span m=''2168320''>to</span> <span m=''2168410''>say</span> <span m=''2168550''>you</span>
  <span m=''2168660''>have</span> <span m=''2168780''>these</span> <span m=''2169710''>list-structured,</span>
  <span m=''2171100''>recursive</span> <span m=''2171730''>data</span> <span m=''2172020''>list</span>
  <span m=''2172270''>operations.</span> <span m=''2172930''>That</span> <span m=''2173045''>has</span>
  <span m=''2173160''>nothing</span> <span m=''2173440''>to</span> <span m=''2173490''>do</span>
  <span m=''2173720''>with</span> <span m=''2173850''>it.</span> <span m=''2173980''>It''s</span>
  <span m=''2174120''>simply</span> <span m=''2174260''>that</span> <span m=''2174420''>the</span>
  <span m=''2174500''>expressions</span> <span m=''2175040''>contain</span> <span
  m=''2175360''>sub-expressions.</span> <span m=''2177363''>Yeah?</span> </p><p><span
  m=''2179618''>AUDIENCE:</span> <span m=''2180070''>Why</span> <span m=''2180450''>is</span>
  <span m=''2180520''>it</span> <span m=''2180710''>that</span> <span m=''2180790''>the</span>
  <span m=''2180930''>order</span> <span m=''2181380''>of</span> <span m=''2181480''>the</span>
  <span m=''2181610''>arguments</span> <span m=''2181865''>in</span> <span m=''2182120''>the</span>
  <span m=''2182260''>arg</span> <span m=''2182500''>list</span> <span m=''2182680''>got</span>
  <span m=''2182860''>reversed?</span> </p><p><span m=''2183225''>PROFESSOR:</span>
  <span m=''2183590''>Ah!</span> <span m=''2183860''>Yes,</span> <span m=''2184120''>I</span>
  <span m=''2184160''>should''ve</span> <span m=''2184660''>mentioned</span> <span
  m=''2185020''>that.</span> <span m=''2187260''>Here,</span> <span m=''2187560''>the</span>
  <span m=''2187650''>reason</span> <span m=''2187960''>the</span> <span m=''2188070''>order</span>
  <span m=''2188360''>is</span> <span m=''2188440''>reversed--</span> <span m=''2192507''>it''s</span>
  <span m=''2192753''>a</span> <span m=''2193000''>question</span> <span m=''2193270''>of</span>
  <span m=''2193345''>what</span> <span m=''2193420''>you</span> <span m=''2193520''>mean</span>
  <span m=''2193690''>by</span> <span m=''2193840''>reversed.</span> <span m=''2196050''>I</span>
  <span m=''2196190''>believe</span> <span m=''2196600''>it</span> <span m=''2196730''>was</span>
  <span m=''2199148''>Newton.</span> <span m=''2200624''>In</span> <span m=''2200872''>the</span>
  <span m=''2201120''>very</span> <span m=''2201370''>early</span> <span m=''2201650''>part</span>
  <span m=''2201920''>of</span> <span m=''2202010''>optics,</span> <span m=''2202450''>people</span>
  <span m=''2202750''>realized</span> <span m=''2203650''>that,</span> <span m=''2203800''>when</span>
  <span m=''2203900''>you</span> <span m=''2204030''>look</span> <span m=''2204190''>through</span>
  <span m=''2204330''>the</span> <span m=''2204450''>lens</span> <span m=''2204730''>of</span>
  <span m=''2204830''>your</span> <span m=''2205000''>eye,</span> <span m=''2205560''>the</span>
  <span m=''2205700''>image</span> <span m=''2205940''>was</span> <span m=''2206100''>up-side</span>
  <span m=''2206530''>down.</span> <span m=''2206840''>And</span> <span m=''2206920''>there</span>
  <span m=''2207010''>was</span> <span m=''2207130''>a</span> <span m=''2207170''>lot</span>
  <span m=''2207360''>of</span> <span m=''2207470''>argument</span> <span m=''2207890''>about</span>
  <span m=''2208060''>why</span> <span m=''2208250''>that</span> <span m=''2208450''>didn''t</span>
  <span m=''2208650''>mean</span> <span m=''2208900''>you</span> <span m=''2209150''>saw</span>
  <span m=''2209420''>things</span> <span m=''2209680''>up-side</span> <span m=''2210040''>down.</span>
  <span m=''2211280''>So</span> <span m=''2211490''>it''s</span> <span m=''2211600''>sort</span>
  <span m=''2211770''>of</span> <span m=''2211830''>the</span> <span m=''2211890''>same</span>
  <span m=''2212170''>issue.</span> <span m=''2212860''>Reversed</span> <span m=''2213320''>from</span>
  <span m=''2213520''>what?</span> <span m=''2214810''>So</span> <span m=''2215000''>we</span>
  <span m=''2215110''>just</span> <span m=''2215390''>need</span> <span m=''2215510''>some</span>
  <span m=''2215630''>convention.</span> <span m=''2217940''>The</span> <span m=''2218040''>reason</span>
  <span m=''2218350''>that</span> <span m=''2218480''>they''re</span> <span m=''2218590''>coming</span>
  <span m=''2218870''>at</span> <span m=''2219340''>4,</span> <span m=''2219790''>3</span>
  <span m=''2220840''>is</span> <span m=''2221000''>because</span> <span m=''2221330''>we''re</span>
  <span m=''2221730''>taking</span> <span m=''2222100''>UNEV</span> <span m=''2222260''>and</span>
  <span m=''2222530''>consing</span> <span m=''2222755''>the</span> <span m=''2222980''>result</span>
  <span m=''2223360''>onto</span> <span m=''2223570''>argl.</span> <span m=''2224520''>So</span>
  <span m=''2224660''>you</span> <span m=''2224770''>have</span> <span m=''2224890''>to</span>
  <span m=''2225000''>realize</span> <span m=''2225460''>you''ve</span> <span m=''2225610''>made</span>
  <span m=''2225810''>that</span> <span m=''2225970''>convention.</span> </p><p><span
  m=''2226900''>The</span> <span m=''2227000''>place</span> <span m=''2227300''>that</span>
  <span m=''2228190''>you</span> <span m=''2228310''>have</span> <span m=''2228440''>to</span>
  <span m=''2228580''>realize</span> <span m=''2229020''>that--</span> <span m=''2230100''>well,</span>
  <span m=''2230220''>there''s</span> <span m=''2230310''>actually</span> <span m=''2230610''>two</span>
  <span m=''2230790''>places.</span> <span m=''2231230''>One</span> <span m=''2231440''>is</span>
  <span m=''2231540''>in</span> <span m=''2231640''>apply-primitive-operator,</span>
  <span m=''2232910''>which</span> <span m=''2233050''>has</span> <span m=''2233200''>to</span>
  <span m=''2233320''>realize</span> <span m=''2233800''>that</span> <span m=''2235140''>the</span>
  <span m=''2235460''>arguments</span> <span m=''2235860''>to</span> <span m=''2235950''>primitives</span>
  <span m=''2236340''>go</span> <span m=''2236475''>in,</span> <span m=''2236610''>in</span>
  <span m=''2236690''>the</span> <span m=''2236810''>opposite</span> <span m=''2237190''>order</span>
  <span m=''2237410''>from</span> <span m=''2237540''>the</span> <span m=''2237620''>way</span>
  <span m=''2237760''>you''re</span> <span m=''2237890''>writing</span> <span m=''2238070''>them</span>
  <span m=''2238250''>down.</span> <span m=''2239490''>And</span> <span m=''2239660''>the</span>
  <span m=''2239770''>other</span> <span m=''2240030''>one</span> <span m=''2240220''>is,</span>
  <span m=''2240340''>we''ll</span> <span m=''2240440''>see</span> <span m=''2240630''>later</span>
  <span m=''2241090''>when</span> <span m=''2241260''>you</span> <span m=''2241370''>actually</span>
  <span m=''2241630''>go</span> <span m=''2241760''>to</span> <span m=''2241820''>bind</span>
  <span m=''2242600''>a</span> <span m=''2242680''>function''s</span> <span m=''2243150''>parameters,</span>
  <span m=''2244180''>you</span> <span m=''2244260''>should</span> <span m=''2244410''>realize</span>
  <span m=''2244720''>the</span> <span m=''2244820''>arguments</span> <span m=''2245250''>are</span>
  <span m=''2245320''>going</span> <span m=''2245400''>to</span> <span m=''2245460''>come</span>
  <span m=''2245670''>in</span> <span m=''2245780''>from</span> <span m=''2245890''>the</span>
  <span m=''2246000''>opposite</span> <span m=''2246410''>order</span> <span m=''2246730''>of</span>
  <span m=''2246810''>the</span> <span m=''2246910''>variables</span> <span m=''2247430''>to</span>
  <span m=''2247530''>which</span> <span m=''2247750''>you''re</span> <span m=''2247800''>binding</span>
  <span m=''2248170''>them.</span> <span m=''2248870''>So,</span> <span m=''2249020''>if</span>
  <span m=''2249096''>you</span> <span m=''2249173''>just</span> <span m=''2249250''>keep</span>
  <span m=''2249440''>track</span> <span m=''2249760''>of</span> <span m=''2249870''>that,</span>
  <span m=''2251110''>there''s</span> <span m=''2251270''>no</span> <span m=''2251390''>problem.</span>
  <span m=''2251830''>Also,</span> <span m=''2252390''>this</span> <span m=''2252550''>is</span>
  <span m=''2252670''>completely</span> <span m=''2253100''>arbitrary</span> <span
  m=''2253990''>because,</span> <span m=''2254340''>if</span> <span m=''2254450''>we''d</span>
  <span m=''2254560''>done,</span> <span m=''2255090''>say,</span> <span m=''2255260''>an</span>
  <span m=''2255370''>iteration</span> <span m=''2255880''>through</span> <span m=''2256070''>a</span>
  <span m=''2256120''>vector</span> <span m=''2256490''>assigning</span> <span m=''2256890''>them,</span>
  <span m=''2257480''>they</span> <span m=''2257570''>might</span> <span m=''2257760''>come</span>
  <span m=''2257910''>out</span> <span m=''2258030''>in</span> <span m=''2258070''>the</span>
  <span m=''2258220''>other</span> <span m=''2258370''>order,</span> <span m=''2260314''>OK?</span>
  <span m=''2260730''>So</span> <span m=''2260880''>it''s</span> <span m=''2261030''>just</span>
  <span m=''2261240''>a</span> <span m=''2261280''>convention</span> <span m=''2261750''>of</span>
  <span m=''2261820''>the</span> <span m=''2261890''>way</span> <span m=''2262010''>this</span>
  <span m=''2262220''>particular</span> <span m=''2262700''>evaluator</span> <span
  m=''2263240''>works.</span> <span m=''2265085''>All</span> <span m=''2265322''>right,</span>
  <span m=''2265560''>let''s</span> <span m=''2265750''>take</span> <span m=''2265880''>a</span>
  <span m=''2265920''>break.</span> </p><p><span m=''2321840''>We</span> <span m=''2322080''>just</span>
  <span m=''2322270''>saw</span> <span m=''2323630''>evaluating</span> <span m=''2324520''>an</span>
  <span m=''2324650''>expression</span> <span m=''2325555''>and,</span> <span m=''2325850''>of</span>
  <span m=''2325890''>course,</span> <span m=''2326050''>that</span> <span m=''2326140''>was</span>
  <span m=''2326260''>very</span> <span m=''2326430''>simple</span> <span m=''2326770''>one.</span>
  <span m=''2326950''>But,</span> <span m=''2328910''>in</span> <span m=''2329110''>essence,</span>
  <span m=''2329460''>it</span> <span m=''2329520''>would</span> <span m=''2329640''>be</span>
  <span m=''2329760''>no</span> <span m=''2329920''>different</span> <span m=''2330270''>if</span>
  <span m=''2330550''>it</span> <span m=''2330690''>was</span> <span m=''2330850''>some</span>
  <span m=''2331020''>big</span> <span m=''2331260''>nested</span> <span m=''2331650''>expression,</span>
  <span m=''2332150''>so</span> <span m=''2332270''>there</span> <span m=''2332320''>would</span>
  <span m=''2332370''>just</span> <span m=''2332580''>be</span> <span m=''2333110''>deeper</span>
  <span m=''2333370''>recursion</span> <span m=''2333860''>on</span> <span m=''2333950''>the</span>
  <span m=''2334050''>stack.</span> <span m=''2335130''>But</span> <span m=''2335310''>what</span>
  <span m=''2335450''>I</span> <span m=''2335470''>want</span> <span m=''2335620''>to</span>
  <span m=''2335660''>do</span> <span m=''2335770''>now</span> <span m=''2335980''>is</span>
  <span m=''2336060''>show</span> <span m=''2336140''>you</span> <span m=''2336260''>the</span>
  <span m=''2336350''>last</span> <span m=''2336690''>piece.</span> <span m=''2336920''>I</span>
  <span m=''2336960''>want</span> <span m=''2337100''>to</span> <span m=''2337160''>walk</span>
  <span m=''2337460''>you</span> <span m=''2338210''>around</span> <span m=''2338620''>this</span>
  <span m=''2338690''>eval</span> <span m=''2338900''>and</span> <span m=''2339110''>apply</span>
  <span m=''2339450''>loop,</span> <span m=''2340802''>right?</span> <span m=''2341300''>That''s</span>
  <span m=''2341520''>the</span> <span m=''2341590''>thing</span> <span m=''2341730''>we</span>
  <span m=''2341840''>haven''t</span> <span m=''2342190''>seen,</span> <span m=''2342440''>really.</span>
  <span m=''2343000''>We</span> <span m=''2343120''>haven''t</span> <span m=''2343330''>seen</span>
  <span m=''2343440''>any</span> <span m=''2343620''>compound</span> <span m=''2344110''>procedures</span>
  <span m=''2348490''>where</span> <span m=''2348680''>applying</span> <span m=''2349020''>a</span>
  <span m=''2349070''>procedure</span> <span m=''2349450''>reduces</span> <span m=''2349880''>to</span>
  <span m=''2350050''>evaluating</span> <span m=''2350610''>the</span> <span m=''2350680''>body</span>
  <span m=''2351010''>of</span> <span m=''2351060''>the</span> <span m=''2351110''>procedure,</span>
  <span m=''2352470''>so</span> <span m=''2352620''>let''s</span> <span m=''2352810''>just</span>
  <span m=''2354960''>suppose</span> <span m=''2355330''>we</span> <span m=''2355440''>had</span>
  <span m=''2355660''>this.</span> <span m=''2355810''>Suppose</span> <span m=''2356110''>we</span>
  <span m=''2356210''>were</span> <span m=''2356320''>looking</span> <span m=''2356610''>at</span>
  <span m=''2356700''>the</span> <span m=''2356780''>procedure</span> <span m=''2358200''>define</span>
  <span m=''2365110''>F</span> <span m=''2365670''>of</span> <span m=''2366220''>A</span>
  <span m=''2366880''>and</span> <span m=''2367140''>B</span> <span m=''2369340''>to</span>
  <span m=''2369470''>be</span> <span m=''2369620''>the</span> <span m=''2369720''>sum</span>
  <span m=''2370760''>of</span> <span m=''2370900''>A</span> <span m=''2371130''>and</span>
  <span m=''2371270''>B.</span> <span m=''2374170''>So,</span> <span m=''2374350''>as</span>
  <span m=''2374405''>we</span> <span m=''2374460''>typed</span> <span m=''2374750''>in</span>
  <span m=''2374870''>that</span> <span m=''2375030''>procedure</span> <span m=''2376520''>previously,</span>
  <span m=''2377770''>and</span> <span m=''2377920''>now</span> <span m=''2378120''>we''re</span>
  <span m=''2378230''>going</span> <span m=''2378350''>to</span> <span m=''2378470''>evaluate</span>
  <span m=''2379030''>F</span> <span m=''2380230''>of</span> <span m=''2380420''>X</span>
  <span m=''2380930''>and</span> <span m=''2381120''>Y,</span> <span m=''2382500''>again,</span>
  <span m=''2382810''>in</span> <span m=''2382890''>this</span> <span m=''2383040''>environment,</span>
  <span m=''2383610''>E,0,</span> <span m=''2384380''>where</span> <span m=''2384550''>X</span>
  <span m=''2384710''>is</span> <span m=''2384820''>bound</span> <span m=''2385020''>to</span>
  <span m=''2385110''>3</span> <span m=''2385900''>and</span> <span m=''2386030''>Y</span>
  <span m=''2386230''>is</span> <span m=''2386320''>bound</span> <span m=''2386510''>to</span>
  <span m=''2386610''>4.</span> </p><p><span m=''2390830''>When</span> <span m=''2390980''>the</span>
  <span m=''2391070''>defined</span> <span m=''2391470''>is</span> <span m=''2391600''>executed,</span>
  <span m=''2392110''>remember,</span> <span m=''2392490''>there''s</span> <span m=''2392690''>a</span>
  <span m=''2392750''>lambda</span> <span m=''2393120''>here,</span> <span m=''2393940''>and</span>
  <span m=''2394130''>lambdas</span> <span m=''2394450''>create</span> <span m=''2394740''>procedures.</span>
  <span m=''2395950''>And,</span> <span m=''2396290''>basically,</span> <span m=''2396750''>what</span>
  <span m=''2396900''>will</span> <span m=''2397010''>happen</span> <span m=''2397980''>is,</span>
  <span m=''2399770''>in</span> <span m=''2400070''>E,0,</span> <span m=''2401040''>we''ll</span>
  <span m=''2401240''>end</span> <span m=''2401430''>up</span> <span m=''2401540''>with</span>
  <span m=''2401660''>a</span> <span m=''2401700''>binding</span> <span m=''2402080''>for</span>
  <span m=''2402250''>F,</span> <span m=''2403560''>which</span> <span m=''2403920''>will</span>
  <span m=''2403990''>say</span> <span m=''2404200''>F</span> <span m=''2404480''>is</span>
  <span m=''2404730''>a</span> <span m=''2404830''>procedure,</span> <span m=''2407290''>and</span>
  <span m=''2407440''>its</span> <span m=''2407600''>args</span> <span m=''2410490''>are</span>
  <span m=''2410685''>A</span> <span m=''2410880''>and</span> <span m=''2411330''>B,</span>
  <span m=''2412545''>and</span> <span m=''2412747''>its</span> <span m=''2412950''>body</span>
  <span m=''2414990''>is</span> <span m=''2415210''>plus</span> <span m=''2415590''>a,b.</span>
  <span m=''2418180''>So</span> <span m=''2418270''>that''s</span> <span m=''2418480''>what</span>
  <span m=''2419120''>the</span> <span m=''2419250''>environment</span> <span m=''2420060''>would</span>
  <span m=''2420210''>have</span> <span m=''2420350''>looked</span> <span m=''2420610''>like</span>
  <span m=''2421210''>had</span> <span m=''2421360''>we</span> <span m=''2421460''>made</span>
  <span m=''2421650''>that</span> <span m=''2421780''>definition.</span> </p><p><span
  m=''2424400''>Then,</span> <span m=''2424560''>when</span> <span m=''2424650''>we</span>
  <span m=''2424740''>go</span> <span m=''2424900''>to</span> <span m=''2425040''>evaluate</span>
  <span m=''2426180''>F</span> <span m=''2426400''>of</span> <span m=''2426510''>X</span>
  <span m=''2426750''>and</span> <span m=''2426840''>Y,</span> <span m=''2428830''>we''ll</span>
  <span m=''2428940''>go</span> <span m=''2429070''>through</span> <span m=''2429180''>exactly</span>
  <span m=''2429910''>the</span> <span m=''2430060''>same</span> <span m=''2430360''>process</span>
  <span m=''2431070''>that</span> <span m=''2431190''>we</span> <span m=''2431290''>did</span>
  <span m=''2431450''>before.</span> <span m=''2431810''>It''s</span> <span m=''2431910''>even</span>
  <span m=''2432100''>the</span> <span m=''2432170''>same</span> <span m=''2432430''>expression.</span>
  <span m=''2433360''>The</span> <span m=''2433540''>only</span> <span m=''2433720''>difference</span>
  <span m=''2434100''>is</span> <span m=''2434220''>that</span> <span m=''2434410''>F,</span>
  <span m=''2434650''>instead</span> <span m=''2434940''>of</span> <span m=''2435010''>having</span>
  <span m=''2435270''>primitive</span> <span m=''2436030''>plus</span> <span m=''2436390''>in</span>
  <span m=''2436520''>it,</span> <span m=''2437270''>will</span> <span m=''2438160''>have</span>
  <span m=''2438330''>this</span> <span m=''2438550''>thing.</span> <span m=''2441040''>And</span>
  <span m=''2441270''>so</span> <span m=''2441980''>we''ll</span> <span m=''2442080''>go</span>
  <span m=''2442210''>through</span> <span m=''2442330''>exactly</span> <span m=''2442830''>the</span>
  <span m=''2442920''>same</span> <span m=''2443160''>process,</span> <span m=''2443600''>except</span>
  <span m=''2443890''>this</span> <span m=''2444080''>time,</span> <span m=''2444320''>when</span>
  <span m=''2444420''>we</span> <span m=''2444560''>end</span> <span m=''2444770''>up</span>
  <span m=''2445260''>at</span> <span m=''2446390''>apply-dispatch,</span> <span m=''2448040''>the</span>
  <span m=''2448130''>function</span> <span m=''2448500''>register,</span> <span m=''2448930''>instead</span>
  <span m=''2449150''>of</span> <span m=''2449200''>having</span> <span m=''2449430''>primitive</span>
  <span m=''2449790''>plus,</span> <span m=''2450470''>will</span> <span m=''2450590''>have</span>
  <span m=''2450740''>a</span> <span m=''2451270''>thing</span> <span m=''2451490''>that</span>
  <span m=''2451630''>will</span> <span m=''2451750''>represent</span> <span m=''2452190''>it</span>
  <span m=''2452260''>saying</span> <span m=''2452560''>procedure,</span> <span m=''2454300''>where</span>
  <span m=''2454470''>the</span> <span m=''2454930''>args</span> <span m=''2457300''>are</span>
  <span m=''2458230''>A</span> <span m=''2458395''>and</span> <span m=''2458560''>B,</span>
  <span m=''2460630''>and</span> <span m=''2460780''>the</span> <span m=''2460840''>body</span>
  <span m=''2463790''>is</span> <span m=''2464240''>plus</span> <span m=''2465260''>A,</span>
  <span m=''2465530''>B.</span> <span m=''2468040''>And,</span> <span m=''2468170''>again,</span>
  <span m=''2468380''>what</span> <span m=''2468500''>I</span> <span m=''2468570''>mean,</span>
  <span m=''2469470''>by</span> <span m=''2469720''>its</span> <span m=''2469800''>ENV,</span>
  <span m=''2470030''>I</span> <span m=''2470060''>mean</span> <span m=''2470200''>there''s</span>
  <span m=''2470370''>a</span> <span m=''2470420''>pointer</span> <span m=''2470760''>to</span>
  <span m=''2470940''>it,</span> <span m=''2471190''>so</span> <span m=''2471370''>don''t</span>
  <span m=''2471560''>worry</span> <span m=''2471770''>that</span> <span m=''2471870''>I''m</span>
  <span m=''2471980''>writing</span> <span m=''2472240''>a</span> <span m=''2472290''>lot</span>
  <span m=''2472470''>of</span> <span m=''2472530''>stuff</span> <span m=''2472800''>there.</span>
  <span m=''2473280''>There''s</span> <span m=''2473420''>a</span> <span m=''2473470''>pointer</span>
  <span m=''2473830''>to</span> <span m=''2473930''>this</span> <span m=''2474100''>procedure</span>
  <span m=''2474500''>data</span> <span m=''2474760''>structure.</span> </p><p><span
  m=''2477170''>OK,</span> <span m=''2477730''>so,</span> <span m=''2477910''>we''re</span>
  <span m=''2478050''>in</span> <span m=''2478100''>exactly</span> <span m=''2478640''>the</span>
  <span m=''2478720''>same</span> <span m=''2478960''>situation.</span> <span m=''2480960''>We</span>
  <span m=''2481160''>get</span> <span m=''2481410''>to</span> <span m=''2481520''>apply-dispatch,</span>
  <span m=''2484030''>so,</span> <span m=''2484210''>here,</span> <span m=''2485160''>we</span>
  <span m=''2485430''>come</span> <span m=''2485610''>to</span> <span m=''2485720''>apply-dispatch.</span>
  <span m=''2486480''>Last</span> <span m=''2486770''>time,</span> <span m=''2486960''>we</span>
  <span m=''2487060''>branched</span> <span m=''2487470''>off</span> <span m=''2487610''>to</span>
  <span m=''2487710''>a</span> <span m=''2487760''>primitive</span> <span m=''2488100''>procedure.</span>
  <span m=''2490010''>Here,</span> <span m=''2490210''>it</span> <span m=''2490300''>says</span>
  <span m=''2490490''>oh,</span> <span m=''2490860''>we</span> <span m=''2491200''>now</span>
  <span m=''2491340''>have</span> <span m=''2491450''>a</span> <span m=''2491560''>compound</span>
  <span m=''2492240''>procedure,</span> <span m=''2494600''>so</span> <span m=''2494790''>we''re</span>
  <span m=''2494900''>going</span> <span m=''2495000''>to</span> <span m=''2495040''>go</span>
  <span m=''2495240''>off</span> <span m=''2495410''>to</span> <span m=''2495550''>compound-apply.</span>
  <span m=''2498660''>Now,</span> <span m=''2498790''>what''s</span> <span m=''2498980''>compound-apply?</span>
  <span m=''2502100''>Well,</span> <span m=''2502470''>remember</span> <span m=''2502850''>what</span>
  <span m=''2503020''>the</span> <span m=''2503100''>meta-circular</span> <span m=''2503800''>evaluator</span>
  <span m=''2504400''>did?</span> <span m=''2505090''>Compound-apply</span> <span
  m=''2505850''>said</span> <span m=''2506320''>we''re</span> <span m=''2506470''>going</span>
  <span m=''2506580''>to</span> <span m=''2506680''>evaluate</span> <span m=''2509910''>the</span>
  <span m=''2510350''>body</span> <span m=''2510710''>of</span> <span m=''2510790''>the</span>
  <span m=''2510860''>procedure</span> <span m=''2512920''>in</span> <span m=''2513070''>some</span>
  <span m=''2513310''>new</span> <span m=''2513520''>environment.</span> </p><p><span
  m=''2514120''>Where</span> <span m=''2514320''>does</span> <span m=''2514430''>that</span>
  <span m=''2514610''>new</span> <span m=''2514750''>environment</span> <span m=''2515280''>come</span>
  <span m=''2515460''>from?</span> <span m=''2516730''>We</span> <span m=''2516870''>take</span>
  <span m=''2517710''>the</span> <span m=''2519140''>environment</span> <span m=''2519730''>that</span>
  <span m=''2519840''>was</span> <span m=''2519990''>packaged</span> <span m=''2520460''>with</span>
  <span m=''2520540''>the</span> <span m=''2520620''>procedure,</span> <span m=''2523110''>we</span>
  <span m=''2523630''>bind</span> <span m=''2524440''>the</span> <span m=''2524540''>parameters</span>
  <span m=''2525100''>of</span> <span m=''2525170''>the</span> <span m=''2525240''>procedure</span>
  <span m=''2525960''>to</span> <span m=''2526080''>the</span> <span m=''2526210''>arguments</span>
  <span m=''2526660''>that</span> <span m=''2526760''>we''re</span> <span m=''2526880''>passing</span>
  <span m=''2527320''>in,</span> <span m=''2529930''>and</span> <span m=''2530140''>use</span>
  <span m=''2530360''>that</span> <span m=''2530590''>as</span> <span m=''2530680''>a</span>
  <span m=''2530760''>new</span> <span m=''2530910''>frame</span> <span m=''2531220''>to</span>
  <span m=''2531340''>extend</span> <span m=''2532620''>the</span> <span m=''2532720''>procedure</span>
  <span m=''2533160''>environment.</span> <span m=''2534990''>And</span> <span m=''2535130''>that''s</span>
  <span m=''2535350''>the</span> <span m=''2535470''>environment</span> <span m=''2536420''>in</span>
  <span m=''2536550''>which</span> <span m=''2536770''>we</span> <span m=''2537330''>evaluate</span>
  <span m=''2538010''>the</span> <span m=''2538100''>procedure</span> <span m=''2538520''>body,</span>
  <span m=''2539634''>right?</span> <span m=''2541630''>That''s</span> <span m=''2542070''>going</span>
  <span m=''2542490''>around</span> <span m=''2543010''>the</span> <span m=''2543530''>apply/eval</span>
  <span m=''2544060''>loop.</span> <span m=''2544470''>That''s</span> <span m=''2544600''>apply</span>
  <span m=''2544970''>coming</span> <span m=''2545260''>back</span> <span m=''2545430''>to</span>
  <span m=''2545540''>call</span> <span m=''2545730''>eval,</span> <span m=''2547501''>all</span>
  <span m=''2547744''>right?</span> </p><p><span m=''2550910''>OK.</span> <span m=''2552860''>So,</span>
  <span m=''2553010''>now,</span> <span m=''2553140''>that''s</span> <span m=''2553310''>all</span>
  <span m=''2553470''>we</span> <span m=''2553570''>have</span> <span m=''2553730''>to</span>
  <span m=''2553820''>do</span> <span m=''2553940''>in</span> <span m=''2554040''>compound-apply.</span>
  <span m=''2556950''>What</span> <span m=''2557100''>are</span> <span m=''2557140''>we</span>
  <span m=''2557240''>going</span> <span m=''2557400''>to</span> <span m=''2557560''>do?</span>
  <span m=''2557720''>We''re</span> <span m=''2557970''>going</span> <span m=''2558080''>to</span>
  <span m=''2558160''>manufacture</span> <span m=''2559960''>a</span> <span m=''2560080''>new</span>
  <span m=''2560330''>environment.</span> <span m=''2563720''>And</span> <span m=''2563790''>we''re</span>
  <span m=''2563860''>going</span> <span m=''2563950''>to</span> <span m=''2564000''>manufacture</span>
  <span m=''2564570''>a</span> <span m=''2564590''>new</span> <span m=''2564800''>environment,</span>
  <span m=''2566576''>let''s</span> <span m=''2566818''>see,</span> <span m=''2567060''>that</span>
  <span m=''2567120''>we''ll</span> <span m=''2567180''>call</span> <span m=''2567420''>E,1.</span>
  <span m=''2573100''>E,1</span> <span m=''2573430''>is</span> <span m=''2573530''>going</span>
  <span m=''2573600''>to</span> <span m=''2573660''>be</span> <span m=''2573760''>some</span>
  <span m=''2573950''>environment</span> <span m=''2577610''>where</span> <span m=''2577730''>the</span>
  <span m=''2577830''>parameters</span> <span m=''2578430''>of</span> <span m=''2578500''>the</span>
  <span m=''2578590''>procedure,</span> <span m=''2579170''>where</span> <span m=''2579390''>A</span>
  <span m=''2579640''>is</span> <span m=''2579780''>bound</span> <span m=''2580700''>to</span>
  <span m=''2580850''>3</span> <span m=''2581980''>and</span> <span m=''2582170''>B</span>
  <span m=''2582320''>is</span> <span m=''2582460''>bound</span> <span m=''2582680''>to</span>
  <span m=''2582780''>4,</span> <span m=''2584220''>and</span> <span m=''2584870''>it''s</span>
  <span m=''2585040''>linked</span> <span m=''2585190''>to</span> <span m=''2585330''>E,0</span>
  <span m=''2585890''>because</span> <span m=''2586220''>that''s</span> <span m=''2586410''>where</span>
  <span m=''2586560''>f</span> <span m=''2587320''>is</span> <span m=''2587480''>defined.</span>
  <span m=''2589270''>And,</span> <span m=''2589450''>in</span> <span m=''2589660''>this</span>
  <span m=''2589840''>environment,</span> <span m=''2590330''>we''re</span> <span
  m=''2590430''>going</span> <span m=''2590520''>to</span> <span m=''2590600''>evaluate</span>
  <span m=''2591030''>the</span> <span m=''2591090''>body</span> <span m=''2591420''>of</span>
  <span m=''2591525''>the</span> <span m=''2591630''>procedure.</span> </p><p><span
  m=''2592050''>So</span> <span m=''2592210''>let''s</span> <span m=''2592390''>look</span>
  <span m=''2592540''>at</span> <span m=''2592630''>that,</span> <span m=''2593456''>all</span>
  <span m=''2593663''>right?</span> <span m=''2596730''>All</span> <span m=''2596815''>right,</span>
  <span m=''2596900''>here</span> <span m=''2596960''>we</span> <span m=''2597020''>are</span>
  <span m=''2597170''>at</span> <span m=''2597210''>compound-apply,</span> <span m=''2600200''>which</span>
  <span m=''2600380''>says</span> <span m=''2600690''>assign</span> <span m=''2601540''>to</span>
  <span m=''2602170''>the</span> <span m=''2602340''>expression</span> <span m=''2602900''>register</span>
  <span m=''2604700''>the</span> <span m=''2604840''>body</span> <span m=''2605340''>of</span>
  <span m=''2605460''>the</span> <span m=''2605560''>procedure</span> <span m=''2606050''>that''s</span>
  <span m=''2606290''>in</span> <span m=''2606390''>the</span> <span m=''2606470''>function</span>
  <span m=''2606800''>register.</span> <span m=''2608300''>So</span> <span m=''2608500''>I</span>
  <span m=''2608580''>assign</span> <span m=''2609300''>to</span> <span m=''2609490''>the</span>
  <span m=''2609600''>expression</span> <span m=''2610070''>register</span> <span
  m=''2611370''>the</span> <span m=''2611470''>procedure</span> <span m=''2611970''>body,</span>
  <span m=''2620727''>OK?</span> <span m=''2622710''>That''s</span> <span m=''2623010''>going</span>
  <span m=''2623100''>to</span> <span m=''2623120''>be</span> <span m=''2623140''>evaluated</span>
  <span m=''2623800''>in</span> <span m=''2623990''>an</span> <span m=''2624120''>environment</span>
  <span m=''2625970''>which</span> <span m=''2626170''>is</span> <span m=''2626300''>formed</span>
  <span m=''2626840''>by</span> <span m=''2626960''>making</span> <span m=''2627380''>some</span>
  <span m=''2627650''>bindings</span> <span m=''2631460''>using</span> <span m=''2631810''>information</span>
  <span m=''2632550''>determined</span> <span m=''2633040''>by</span> <span m=''2633200''>the</span>
  <span m=''2633320''>procedure--</span> <span m=''2633860''>that''s</span> <span
  m=''2634060''>what''s</span> <span m=''2634230''>in</span> <span m=''2634360''>FUN--</span>
  <span m=''2635320''>and</span> <span m=''2635510''>the</span> <span m=''2635610''>argument</span>
  <span m=''2636030''>list.</span> </p><p><span m=''2637800''>And</span> <span m=''2637915''>let''s</span>
  <span m=''2638030''>not</span> <span m=''2638160''>worry</span> <span m=''2638340''>about</span>
  <span m=''2638510''>exactly</span> <span m=''2639120''>what</span> <span m=''2639360''>that</span>
  <span m=''2639590''>does,</span> <span m=''2640090''>but</span> <span m=''2640230''>you</span>
  <span m=''2640310''>can</span> <span m=''2640420''>see</span> <span m=''2640570''>the</span>
  <span m=''2640680''>information''s</span> <span m=''2641350''>there.</span> <span
  m=''2641930''>So</span> <span m=''2642040''>make</span> <span m=''2642270''>bindings</span>
  <span m=''2642680''>will</span> <span m=''2642770''>say</span> <span m=''2643010''>oh,</span>
  <span m=''2644080''>the</span> <span m=''2644180''>procedure,</span> <span m=''2644780''>itself,</span>
  <span m=''2646150''>had</span> <span m=''2646320''>an</span> <span m=''2646420''>environment</span>
  <span m=''2647110''>attached</span> <span m=''2647550''>to</span> <span m=''2647630''>it.</span>
  <span m=''2648200''>I</span> <span m=''2648320''>didn''t</span> <span m=''2648440''>write</span>
  <span m=''2648690''>that</span> <span m=''2648890''>quite</span> <span m=''2649090''>here.</span>
  <span m=''2649320''>I</span> <span m=''2649340''>should''ve</span> <span m=''2649580''>said</span>
  <span m=''2649740''>in</span> <span m=''2649880''>environment</span> <span m=''2651460''>because</span>
  <span m=''2651620''>every</span> <span m=''2651810''>procedure</span> <span m=''2652190''>gets</span>
  <span m=''2652400''>built</span> <span m=''2652600''>with</span> <span m=''2652730''>an</span>
  <span m=''2652820''>environment.</span> <span m=''2653660''>So,</span> <span m=''2653840''>from</span>
  <span m=''2654080''>that</span> <span m=''2654240''>environment,</span> <span m=''2655770''>it</span>
  <span m=''2655970''>knows</span> <span m=''2656680''>what</span> <span m=''2656830''>the</span>
  <span m=''2656910''>procedure''s</span> <span m=''2657400''>definition</span> <span
  m=''2657880''>environment</span> <span m=''2658330''>is.</span> <span m=''2659290''>It</span>
  <span m=''2659420''>knows</span> <span m=''2659620''>what</span> <span m=''2659740''>the</span>
  <span m=''2659850''>arguments</span> <span m=''2660360''>are.</span> <span m=''2661830''>It</span>
  <span m=''2661910''>looks</span> <span m=''2662100''>at</span> <span m=''2662160''>argl,</span>
  <span m=''2662560''>and</span> <span m=''2662640''>then</span> <span m=''2662750''>you</span>
  <span m=''2662870''>see</span> <span m=''2663020''>a</span> <span m=''2663060''>reversal</span>
  <span m=''2663540''>convention</span> <span m=''2664040''>here.</span> <span m=''2664280''>It</span>
  <span m=''2664395''>just</span> <span m=''2664510''>has</span> <span m=''2664640''>to</span>
  <span m=''2664740''>know</span> <span m=''2664910''>that</span> <span m=''2665130''>argl</span>
  <span m=''2666010''>is</span> <span m=''2666140''>reversed,</span> <span m=''2667150''>and</span>
  <span m=''2667285''>it</span> <span m=''2667420''>builds</span> <span m=''2667830''>this</span>
  <span m=''2668030''>frame,</span> <span m=''2668320''>E,1.</span> <span m=''2669990''>All</span>
  <span m=''2670185''>right,</span> <span m=''2670380''>so,</span> <span m=''2670490''>let''s</span>
  <span m=''2670650''>assume</span> <span m=''2670960''>that</span> <span m=''2671070''>that''s</span>
  <span m=''2671290''>what</span> <span m=''2671690''>make</span> <span m=''2671960''>bindings</span>
  <span m=''2672400''>returns,</span> <span m=''2673460''>so</span> <span m=''2673660''>it</span>
  <span m=''2673710''>assigns</span> <span m=''2674140''>to</span> <span m=''2674270''>ENV</span>
  <span m=''2675220''>this</span> <span m=''2675410''>thing,</span> <span m=''2675590''>E,1.</span>
  </p><p><span m=''2681490''>All</span> <span m=''2681585''>right,</span> <span m=''2681680''>the</span>
  <span m=''2681775''>next</span> <span m=''2681870''>thing</span> <span m=''2682030''>it</span>
  <span m=''2682140''>says</span> <span m=''2684010''>is</span> <span m=''2684170''>restore</span>
  <span m=''2685130''>continue.</span> <span m=''2686890''>Remember</span> <span m=''2687015''>what</span>
  <span m=''2687140''>continue</span> <span m=''2687322''>was</span> <span m=''2687870''>here?</span>
  <span m=''2688760''>It</span> <span m=''2689060''>got</span> <span m=''2689150''>put</span>
  <span m=''2689370''>up</span> <span m=''2689480''>in</span> <span m=''2689570''>the</span>
  <span m=''2689660''>last</span> <span m=''2689940''>segment.</span> <span m=''2692240''>Continue</span>
  <span m=''2693190''>got</span> <span m=''2693430''>stored.</span> <span m=''2694020''>That</span>
  <span m=''2694180''>was</span> <span m=''2694330''>the</span> <span m=''2694450''>original</span>
  <span m=''2694900''>done,</span> <span m=''2695280''>which</span> <span m=''2695470''>said</span>
  <span m=''2695590''>what</span> <span m=''2695800''>are</span> <span m=''2695820''>you</span>
  <span m=''2696060''>going</span> <span m=''2696180''>to</span> <span m=''2696300''>do</span>
  <span m=''2696840''>after</span> <span m=''2697150''>you''re</span> <span m=''2697320''>done</span>
  <span m=''2697580''>with</span> <span m=''2697750''>this</span> <span m=''2697950''>particular</span>
  <span m=''2698510''>application?</span> <span m=''2699920''>It</span> <span m=''2700090''>was</span>
  <span m=''2700260''>one</span> <span m=''2700390''>of</span> <span m=''2700430''>the</span>
  <span m=''2700520''>very</span> <span m=''2700770''>first</span> <span m=''2701040''>things</span>
  <span m=''2701260''>that</span> <span m=''2701370''>happened</span> <span m=''2701700''>when</span>
  <span m=''2701860''>we</span> <span m=''2701980''>evaluated</span> <span m=''2702420''>the</span>
  <span m=''2702550''>application.</span> </p><p><span m=''2703920''>And</span> <span
  m=''2704070''>now,</span> <span m=''2704200''>finally,</span> <span m=''2704640''>we''re</span>
  <span m=''2704770''>going</span> <span m=''2704860''>to</span> <span m=''2704900''>restore</span>
  <span m=''2705310''>continue.</span> <span m=''2706860''>Remember</span> <span m=''2707950''>apply-dispatch''s</span>
  <span m=''2709000''>contract.</span> <span m=''2709290''>It</span> <span m=''2709580''>assumes</span>
  <span m=''2710000''>that</span> <span m=''2710110''>where</span> <span m=''2710300''>it</span>
  <span m=''2710350''>should</span> <span m=''2710510''>go</span> <span m=''2710660''>to</span>
  <span m=''2710850''>next</span> <span m=''2711160''>was</span> <span m=''2711360''>on</span>
  <span m=''2711510''>the</span> <span m=''2711570''>stack,</span> <span m=''2712000''>and</span>
  <span m=''2712090''>there</span> <span m=''2712270''>it</span> <span m=''2712380''>was</span>
  <span m=''2712490''>on</span> <span m=''2712580''>the</span> <span m=''2712670''>stack.</span>
  <span m=''2713590''>Continue</span> <span m=''2714000''>has</span> <span m=''2714290''>done,</span>
  <span m=''2717920''>and</span> <span m=''2718080''>now</span> <span m=''2718260''>we''re</span>
  <span m=''2718350''>going</span> <span m=''2718450''>to</span> <span m=''2718490''>go</span>
  <span m=''2718630''>back</span> <span m=''2719100''>to</span> <span m=''2719310''>eval-dispatch.</span>
  <span m=''2719940''>We''re</span> <span m=''2720040''>set</span> <span m=''2720250''>up</span>
  <span m=''2720390''>again.</span> <span m=''2720970''>We</span> <span m=''2721110''>have</span>
  <span m=''2721480''>an</span> <span m=''2721680''>expression,</span> <span m=''2722640''>an</span>
  <span m=''2722780''>environment,</span> <span m=''2723350''>and</span> <span m=''2723470''>a</span>
  <span m=''2723520''>place</span> <span m=''2723790''>to</span> <span m=''2723890''>go</span>
  <span m=''2724080''>to.</span> <span m=''2725511''>We''re</span> <span m=''2725900''>not</span>
  <span m=''2726090''>going</span> <span m=''2726180''>to</span> <span m=''2726220''>go</span>
  <span m=''2726310''>through</span> <span m=''2726520''>that</span> <span m=''2728030''>because</span>
  <span m=''2728250''>it''s</span> <span m=''2728380''>sort</span> <span m=''2728560''>of</span>
  <span m=''2728610''>the</span> <span m=''2728690''>same</span> <span m=''2728930''>expression.</span>
  </p><p><span m=''2735167''>OK,</span> <span m=''2735670''>but</span> <span m=''2735980''>the</span>
  <span m=''2736070''>thing,</span> <span m=''2736610''>again,</span> <span m=''2737200''>to</span>
  <span m=''2737340''>notice</span> <span m=''2737840''>is,</span> <span m=''2738000''>at</span>
  <span m=''2738170''>this</span> <span m=''2738340''>point,</span> <span m=''2739390''>we</span>
  <span m=''2739590''>have</span> <span m=''2739780''>reduced</span> <span m=''2740850''>the</span>
  <span m=''2741040''>original</span> <span m=''2741570''>expression,</span> <span
  m=''2743040''>F,X,Y,</span> <span m=''2744480''>right?</span> <span m=''2744830''>We''ve</span>
  <span m=''2745110''>reduced</span> <span m=''2745620''>evaluating</span> <span m=''2746260''>F,X,Y</span>
  <span m=''2746630''>in</span> <span m=''2746930''>environment</span> <span m=''2747020''>E,0</span>
  <span m=''2748950''>to</span> <span m=''2749450''>evaluate</span> <span m=''2750150''>plus</span>
  <span m=''2750400''>A,</span> <span m=''2750580''>B</span> <span m=''2751970''>in</span>
  <span m=''2752145''>E,1.</span> <span m=''2752670''>And</span> <span m=''2752950''>notice,</span>
  <span m=''2753240''>nothing''s</span> <span m=''2753580''>on</span> <span m=''2753670''>the</span>
  <span m=''2753750''>stack,</span> <span m=''2755236''>right?</span> <span m=''2755720''>It''s</span>
  <span m=''2756210''>a</span> <span m=''2756260''>reduction.</span> <span m=''2756830''>At</span>
  <span m=''2756930''>this</span> <span m=''2757150''>point,</span> <span m=''2757500''>the</span>
  <span m=''2757580''>machine</span> <span m=''2758310''>does</span> <span m=''2758510''>not</span>
  <span m=''2759150''>contain,</span> <span m=''2760070''>as</span> <span m=''2760250''>part</span>
  <span m=''2760430''>of</span> <span m=''2760530''>its</span> <span m=''2760690''>state,</span>
  <span m=''2761830''>the</span> <span m=''2761940''>fact</span> <span m=''2762310''>that</span>
  <span m=''2762470''>it''s</span> <span m=''2762620''>in</span> <span m=''2762730''>the</span>
  <span m=''2762820''>middle</span> <span m=''2763100''>of</span> <span m=''2763200''>evaluating</span>
  <span m=''2763790''>some</span> <span m=''2763970''>procedure</span> <span m=''2764360''>called</span>
  <span m=''2764630''>f,</span> <span m=''2765640''>that''s</span> <span m=''2765890''>gone,</span>
  <span m=''2767660''>right?</span> <span m=''2768090''>There''s</span> <span m=''2768290''>no</span>
  <span m=''2768490''>accumulated</span> <span m=''2769150''>state,</span> <span m=''2771500''>OK?</span>
  </p><p><span m=''2773072''>Again,</span> <span m=''2773256''>that''s</span> <span
  m=''2773348''>a</span> <span m=''2773440''>very</span> <span m=''2773680''>important</span>
  <span m=''2774060''>idea.</span> <span m=''2774370''>That''s</span> <span m=''2775350''>the</span>
  <span m=''2775560''>meaning</span> <span m=''2776040''>of,</span> <span m=''2776770''>when</span>
  <span m=''2776890''>we</span> <span m=''2776980''>used</span> <span m=''2777160''>to</span>
  <span m=''2777240''>write</span> <span m=''2777440''>in</span> <span m=''2777510''>the</span>
  <span m=''2777590''>substitution</span> <span m=''2778210''>model,</span> <span
  m=''2778500''>this</span> <span m=''2778690''>expression</span> <span m=''2779400''>reduces</span>
  <span m=''2780060''>to</span> <span m=''2780180''>that</span> <span m=''2780430''>expression.</span>
  <span m=''2781350''>And</span> <span m=''2781460''>you</span> <span m=''2781550''>don''t</span>
  <span m=''2781670''>have</span> <span m=''2781830''>to</span> <span m=''2781920''>remember</span>
  <span m=''2782340''>anything.</span> <span m=''2782660''>And</span> <span m=''2782720''>here,</span>
  <span m=''2782870''>you</span> <span m=''2783010''>see</span> <span m=''2783450''>the</span>
  <span m=''2783610''>meaning</span> <span m=''2783940''>of</span> <span m=''2784030''>reduction.</span>
  <span m=''2784500''>At</span> <span m=''2784630''>this</span> <span m=''2784750''>point,</span>
  <span m=''2784940''>there</span> <span m=''2785070''>is</span> <span m=''2785200''>nothing</span>
  <span m=''2785590''>on</span> <span m=''2785720''>the</span> <span m=''2785780''>stack.</span>
  <span m=''2791590''>See,</span> <span m=''2791890''>that</span> <span m=''2792080''>has</span>
  <span m=''2792250''>very</span> <span m=''2792570''>important</span> <span m=''2792910''>consequences.</span>
  <span m=''2795240''>Let''s</span> <span m=''2795440''>go</span> <span m=''2795510''>back</span>
  <span m=''2795750''>and</span> <span m=''2796510''>look</span> <span m=''2796650''>at</span>
  <span m=''2796780''>iterative</span> <span m=''2797180''>factorial,</span> <span
  m=''2800150''>all</span> <span m=''2800370''>right?</span> </p><p><span m=''2800590''>Remember,</span>
  <span m=''2801150''>this</span> <span m=''2801380''>was</span> <span m=''2801880''>some</span>
  <span m=''2802140''>sort</span> <span m=''2802330''>of</span> <span m=''2802410''>loop</span>
  <span m=''2804080''>and</span> <span m=''2804250''>doing</span> <span m=''2804450''>iter.</span>
  <span m=''2805130''>And</span> <span m=''2805220''>we</span> <span m=''2805330''>kept</span>
  <span m=''2805530''>saying</span> <span m=''2805720''>that''s</span> <span m=''2805920''>an</span>
  <span m=''2806050''>iterative</span> <span m=''2806700''>procedure,</span> <span
  m=''2809002''>right?</span> <span m=''2812570''>And</span> <span m=''2812720''>what</span>
  <span m=''2812870''>we</span> <span m=''2813000''>wrote,</span> <span m=''2813260''>remember,</span>
  <span m=''2818680''>are</span> <span m=''2818750''>things</span> <span m=''2822166''>like,</span>
  <span m=''2822610''>we</span> <span m=''2822740''>said,</span> <span m=''2824660''>fact-iter</span>
  <span m=''2830080''>of</span> <span m=''2830150''>5.</span> <span m=''2832360''>We</span>
  <span m=''2832570''>wrote</span> <span m=''2832620''>things</span> <span m=''2832880''>like</span>
  <span m=''2833090''>reduces</span> <span m=''2833750''>to</span> <span m=''2835460''>iter</span>
  <span m=''2836642''>of</span> <span m=''2837040''>1,</span> <span m=''2837480''>and</span>
  <span m=''2837660''>1,</span> <span m=''2837950''>and</span> <span m=''2838130''>5,</span>
  <span m=''2839030''>which</span> <span m=''2839280''>reduces</span> <span m=''2839880''>to</span>
  <span m=''2841340''>iter</span> <span m=''2843350''>of</span> <span m=''2843530''>1,</span>
  <span m=''2843890''>and</span> <span m=''2844080''>2,</span> <span m=''2844440''>and</span>
  <span m=''2844610''>5,</span> <span m=''2845430''>and</span> <span m=''2845590''>so</span>
  <span m=''2845850''>on,</span> <span m=''2846380''>and</span> <span m=''2846550''>so</span>
  <span m=''2846710''>on,</span> <span m=''2846840''>and</span> <span m=''2846970''>so</span>
  <span m=''2847090''>on.</span> <span m=''2847210''>And</span> <span m=''2847265''>we</span>
  <span m=''2847320''>kept</span> <span m=''2847530''>saying</span> <span m=''2847710''>well,</span>
  <span m=''2847890''>look,</span> <span m=''2848190''>you</span> <span m=''2848390''>don''t</span>
  <span m=''2848550''>have</span> <span m=''2848720''>to</span> <span m=''2848830''>build</span>
  <span m=''2849040''>up</span> <span m=''2849160''>any</span> <span m=''2849360''>storage</span>
  <span m=''2849810''>to</span> <span m=''2849890''>do</span> <span m=''2850060''>that.</span>
  <span m=''2851720''>And</span> <span m=''2851820''>we</span> <span m=''2851920''>waved</span>
  <span m=''2852230''>our</span> <span m=''2852330''>hands,</span> <span m=''2852670''>and</span>
  <span m=''2852750''>said</span> <span m=''2852890''>in</span> <span m=''2852980''>principle,</span>
  <span m=''2853430''>there''s</span> <span m=''2853600''>no</span> <span m=''2853730''>storage</span>
  <span m=''2854170''>needed.</span> <span m=''2855040''>Now,</span> <span m=''2855170''>you</span>
  <span m=''2855300''>see</span> <span m=''2855450''>no</span> <span m=''2855600''>storage</span>
  <span m=''2855990''>needed.</span> <span m=''2856170''>Each</span> <span m=''2856450''>of</span>
  <span m=''2856580''>these</span> <span m=''2856710''>is</span> <span m=''2856840''>a</span>
  <span m=''2856920''>real</span> <span m=''2857450''>reduction,</span> <span m=''2858726''>right?</span>
  </p><p><span m=''2869280''>As</span> <span m=''2869370''>you</span> <span m=''2869460''>walk</span>
  <span m=''2869650''>through</span> <span m=''2869760''>these</span> <span m=''2869950''>expressions,</span>
  <span m=''2870770''>what</span> <span m=''2871010''>you''ll</span> <span m=''2871110''>see</span>
  <span m=''2871370''>are</span> <span m=''2871450''>these</span> <span m=''2871680''>expressions</span>
  <span m=''2872200''>on</span> <span m=''2872320''>the</span> <span m=''2872380''>stack</span>
  <span m=''2873820''>in</span> <span m=''2873960''>some</span> <span m=''2874260''>particular</span>
  <span m=''2874810''>environment,</span> <span m=''2876620''>and</span> <span m=''2876780''>then</span>
  <span m=''2878000''>these</span> <span m=''2878180''>expressions</span> <span m=''2879420''>in</span>
  <span m=''2879620''>the</span> <span m=''2879820''>EXP</span> <span m=''2880045''>register</span>
  <span m=''2880270''>in</span> <span m=''2880310''>some</span> <span m=''2880350''>particular</span>
  <span m=''2880800''>environment.</span> <span m=''2881650''>And,</span> <span m=''2881780''>at</span>
  <span m=''2881895''>each</span> <span m=''2882010''>point,</span> <span m=''2882200''>there''ll</span>
  <span m=''2882300''>be</span> <span m=''2882410''>no</span> <span m=''2882590''>accumulated</span>
  <span m=''2883160''>stuff</span> <span m=''2883400''>on</span> <span m=''2883510''>the</span>
  <span m=''2883570''>stack</span> <span m=''2884520''>because</span> <span m=''2884680''>each</span>
  <span m=''2884790''>one''s</span> <span m=''2884900''>a</span> <span m=''2885010''>real</span>
  <span m=''2885270''>reduction,</span> <span m=''2887235''>OK?</span> </p><p><span
  m=''2889135''>All</span> <span m=''2889372''>right,</span> <span m=''2889610''>so,</span>
  <span m=''2889860''>for</span> <span m=''2890000''>example,</span> <span m=''2890680''>just</span>
  <span m=''2890810''>to</span> <span m=''2890910''>go</span> <span m=''2891020''>through</span>
  <span m=''2891220''>it</span> <span m=''2891350''>in</span> <span m=''2891450''>a</span>
  <span m=''2891520''>little</span> <span m=''2891800''>bit</span> <span m=''2891950''>more</span>
  <span m=''2892140''>care,</span> <span m=''2893580''>if</span> <span m=''2893750''>I</span>
  <span m=''2893820''>start</span> <span m=''2894150''>out</span> <span m=''2894570''>with</span>
  <span m=''2894880''>an</span> <span m=''2894980''>expression</span> <span m=''2895510''>that</span>
  <span m=''2895690''>says</span> <span m=''2895890''>something</span> <span m=''2896270''>like,</span>
  <span m=''2898170''>oh,</span> <span m=''2905050''>say,</span> <span m=''2905210''>fact-iter</span>
  <span m=''2911180''>of</span> <span m=''2911680''>5</span> <span m=''2913200''>in</span>
  <span m=''2913280''>some</span> <span m=''2913520''>environment</span> <span m=''2922150''>that</span>
  <span m=''2922360''>will,</span> <span m=''2924200''>at</span> <span m=''2924380''>some</span>
  <span m=''2924650''>point,</span> <span m=''2924970''>create</span> <span m=''2925420''>an</span>
  <span m=''2925540''>environment</span> <span m=''2926810''>in</span> <span m=''2926920''>which</span>
  <span m=''2927130''>n</span> <span m=''2927285''>is</span> <span m=''2927440''>down</span>
  <span m=''2927670''>to</span> <span m=''2927780''>5.</span> <span m=''2931340''>Let''s</span>
  <span m=''2931530''>call</span> <span m=''2931710''>that--</span> <span m=''2935750''>And,</span>
  <span m=''2935900''>at</span> <span m=''2936020''>some</span> <span m=''2936270''>point,</span>
  <span m=''2936950''>the</span> <span m=''2937060''>machine</span> <span m=''2938280''>will</span>
  <span m=''2941360''>reduce</span> <span m=''2941760''>this</span> <span m=''2941920''>whole</span>
  <span m=''2942120''>thing</span> <span m=''2942900''>to</span> <span m=''2943000''>a</span>
  <span m=''2943100''>thing</span> <span m=''2943300''>that</span> <span m=''2943450''>says</span>
  <span m=''2943650''>that''s</span> <span m=''2943860''>really</span> <span m=''2944810''>iter</span>
  <span m=''2947470''>of</span> <span m=''2947920''>1,</span> <span m=''2948650''>and</span>
  <span m=''2948780''>1,</span> <span m=''2949170''>and</span> <span m=''2949450''>n,</span>
  <span m=''2950780''>evaluated</span> <span m=''2952240''>in</span> <span m=''2952390''>this</span>
  <span m=''2952700''>environment,</span> <span m=''2953210''>E,1</span> <span m=''2956040''>with</span>
  <span m=''2956220''>nothing</span> <span m=''2956550''>on</span> <span m=''2956660''>the</span>
  <span m=''2956720''>stack.</span> <span m=''2957160''>See,</span> <span m=''2957390''>at</span>
  <span m=''2957485''>this</span> <span m=''2957580''>moment,</span> <span m=''2957960''>the</span>
  <span m=''2958020''>machine</span> <span m=''2958400''>is</span> <span m=''2958560''>not</span>
  <span m=''2958850''>remembering</span> <span m=''2960710''>that</span> <span m=''2960880''>evaluating</span>
  <span m=''2961470''>this</span> <span m=''2961640''>expression,</span> <span m=''2962100''>iter--</span>
  <span m=''2965000''>which</span> <span m=''2965170''>is</span> <span m=''2965270''>the</span>
  <span m=''2965350''>loop--</span> <span m=''2965700''>is</span> <span m=''2966200''>part</span>
  <span m=''2966700''>of</span> <span m=''2966910''>this</span> <span m=''2967110''>thing</span>
  <span m=''2967280''>called</span> <span m=''2967520''>iterative</span> <span m=''2967780''>factorial.</span>
  <span m=''2969366''>It''s</span> <span m=''2969860''>not</span> <span m=''2970030''>remembering</span>
  <span m=''2970310''>that.</span> <span m=''2970590''>It''s</span> <span m=''2970780''>just</span>
  <span m=''2970990''>reducing</span> <span m=''2971350''>the</span> <span m=''2971440''>expression</span>
  <span m=''2971890''>to</span> <span m=''2971980''>that,</span> <span m=''2973040''>right?</span>
  <span m=''2973170''>If</span> <span m=''2973260''>we</span> <span m=''2973350''>look</span>
  <span m=''2973530''>again</span> <span m=''2974930''>at</span> <span m=''2975060''>the</span>
  <span m=''2975130''>body</span> <span m=''2975540''>of</span> <span m=''2975735''>iterative</span>
  <span m=''2975930''>factorial,</span> <span m=''2978130''>this</span> <span m=''2978390''>expression</span>
  <span m=''2978880''>has</span> <span m=''2979040''>reduced</span> <span m=''2980230''>to</span>
  <span m=''2980350''>that</span> <span m=''2980570''>expression.</span> <span m=''2982810''>Oh,</span>
  <span m=''2982920''>I</span> <span m=''2983010''>shouldn''t</span> <span m=''2983100''>have</span>
  <span m=''2983230''>the</span> <span m=''2983400''>n</span> <span m=''2983570''>there.</span>
  <span m=''2986590''>It''s</span> <span m=''2986730''>a</span> <span m=''2986870''>slightly</span>
  <span m=''2987010''>different</span> <span m=''2987290''>convention</span> <span
  m=''2987880''>from</span> <span m=''2987970''>the</span> <span m=''2988060''>slide</span>
  <span m=''2988410''>to</span> <span m=''2988495''>the</span> <span m=''2988580''>program,</span>
  <span m=''2990471''>OK?</span> </p><p><span m=''2993340''>And,</span> <span m=''2993590''>then,</span>
  <span m=''2995340''>what''s</span> <span m=''2995600''>the</span> <span m=''2995680''>body</span>
  <span m=''2995980''>of</span> <span m=''2996145''>iter?</span> <span m=''2996310''>Well,</span>
  <span m=''2996450''>iter''s</span> <span m=''2996710''>going</span> <span m=''2996880''>to</span>
  <span m=''2997040''>be</span> <span m=''2997210''>an</span> <span m=''2997360''>it,</span>
  <span m=''2998830''>and</span> <span m=''2998970''>I</span> <span m=''2998990''>won''t</span>
  <span m=''2999150''>go</span> <span m=''2999240''>through</span> <span m=''2999380''>the</span>
  <span m=''2999460''>details</span> <span m=''2999880''>of</span> <span m=''2999930''>if.</span>
  <span m=''3000060''>It''ll</span> <span m=''3000490''>evaluate</span> <span m=''3000960''>the</span>
  <span m=''3001030''>predicate.</span> <span m=''3002540''>In</span> <span m=''3002620''>this</span>
  <span m=''3002750''>case,</span> <span m=''3002970''>it''ll</span> <span m=''3003080''>be</span>
  <span m=''3003220''>false.</span> <span m=''3003810''>And</span> <span m=''3004000''>this</span>
  <span m=''3004140''>iter</span> <span m=''3004670''>will</span> <span m=''3004910''>now</span>
  <span m=''3005300''>reduce</span> <span m=''3005910''>to</span> <span m=''3007680''>the</span>
  <span m=''3007850''>expression</span> <span m=''3010250''>iter</span> <span m=''3010740''>of</span>
  <span m=''3014490''>whatever</span> <span m=''3014650''>it</span> <span m=''3014740''>says,</span>
  <span m=''3015000''>star,</span> <span m=''3015260''>counter</span> <span m=''3017330''>product,</span>
  <span m=''3019790''>and--</span> <span m=''3021620''>what</span> <span m=''3021756''>does</span>
  <span m=''3021893''>it</span> <span m=''3022030''>say--</span> <span m=''3022650''>plus</span>
  <span m=''3023710''>counter</span> <span m=''3024110''>1</span> <span m=''3028710''>in</span>
  <span m=''3029140''>some</span> <span m=''3029430''>other</span> <span m=''3029700''>environment,</span>
  <span m=''3030290''>by</span> <span m=''3030400''>this</span> <span m=''3030590''>time,</span>
  <span m=''3030820''>E,2,</span> <span m=''3033140''>where</span> <span m=''3033310''>E,2</span>
  <span m=''3033750''>will</span> <span m=''3034520''>be</span> <span m=''3034730''>set</span>
  <span m=''3034950''>up</span> <span m=''3035070''>having</span> <span m=''3035390''>bindings</span>
  <span m=''3036305''>for</span> <span m=''3036620''>product</span> <span m=''3038840''>and</span>
  <span m=''3038980''>counter,</span> <span m=''3042725''>right?</span> <span m=''3043200''>And</span>
  <span m=''3043360''>it''ll</span> <span m=''3043450''>reduce</span> <span m=''3043880''>to</span>
  <span m=''3043970''>that,</span> <span m=''3044990''>right?</span> <span m=''3045140''>It</span>
  <span m=''3045180''>won''t</span> <span m=''3045380''>be</span> <span m=''3045500''>remembering</span>
  <span m=''3046160''>that</span> <span m=''3046290''>it''s</span> <span m=''3046460''>part</span>
  <span m=''3046720''>of</span> <span m=''3047220''>something</span> <span m=''3047630''>that</span>
  <span m=''3047820''>it</span> <span m=''3047925''>has</span> <span m=''3048030''>to</span>
  <span m=''3048120''>return</span> <span m=''3048520''>to.</span> <span m=''3049340''>And</span>
  <span m=''3049525''>when</span> <span m=''3049710''>iter</span> <span m=''3049770''>calls</span>
  <span m=''3049970''>iter</span> <span m=''3050190''>again,</span> <span m=''3050470''>it''ll</span>
  <span m=''3050640''>reduce</span> <span m=''3051090''>to</span> <span m=''3051230''>another</span>
  <span m=''3051500''>thing</span> <span m=''3051690''>that</span> <span m=''3051810''>looks</span>
  <span m=''3052040''>like</span> <span m=''3052270''>this</span> <span m=''3053380''>in</span>
  <span m=''3053500''>some</span> <span m=''3053680''>environment,</span> <span m=''3054130''>E,3,</span>
  <span m=''3054860''>which</span> <span m=''3055050''>has</span> <span m=''3055200''>new</span>
  <span m=''3055370''>bindings</span> <span m=''3055810''>for</span> <span m=''3055910''>product</span>
  <span m=''3056290''>and</span> <span m=''3056515''>counter.</span> <span m=''3059160''>So,</span>
  <span m=''3064380''>if</span> <span m=''3064530''>you''re</span> <span m=''3064660''>wondering,</span>
  <span m=''3066120''>see,</span> <span m=''3066185''>if</span> <span m=''3066250''>you''ve</span>
  <span m=''3066390''>always</span> <span m=''3066570''>been</span> <span m=''3066710''>queasy</span>
  <span m=''3068450''>about</span> <span m=''3068850''>how</span> <span m=''3069100''>it</span>
  <span m=''3069190''>is</span> <span m=''3069380''>we''ve</span> <span m=''3069520''>been</span>
  <span m=''3069650''>saying</span> <span m=''3070050''>those</span> <span m=''3070280''>procedures,</span>
  <span m=''3070780''>that</span> <span m=''3070920''>look</span> <span m=''3071180''>syntactically</span>
  <span m=''3071790''>recursive,</span> <span m=''3073810''>are,</span> <span m=''3074000''>in</span>
  <span m=''3074090''>fact,</span> <span m=''3075220''>iterative,</span> <span m=''3075950''>run</span>
  <span m=''3076095''>in</span> <span m=''3076240''>constant</span> <span m=''3076690''>space,</span>
  <span m=''3078410''>well,</span> <span m=''3078560''>I</span> <span m=''3078620''>don''t</span>
  <span m=''3078700''>know</span> <span m=''3078750''>if</span> <span m=''3078800''>this</span>
  <span m=''3078930''>makes</span> <span m=''3079130''>you</span> <span m=''3079230''>less</span>
  <span m=''3079430''>queasy,</span> <span m=''3079830''>but</span> <span m=''3079880''>at</span>
  <span m=''3079930''>least</span> <span m=''3080130''>it</span> <span m=''3080190''>shows</span>
  <span m=''3080490''>you</span> <span m=''3080620''>what''s</span> <span m=''3080840''>happening.</span>
  <span m=''3081230''>There</span> <span m=''3081400''>really</span> <span m=''3081660''>isn''t</span>
  <span m=''3081980''>any</span> <span m=''3082150''>buildup</span> <span m=''3082560''>there.</span>
  </p><p><span m=''3085910''>Now,</span> <span m=''3085990''>you</span> <span m=''3086160''>might</span>
  <span m=''3086390''>ask</span> <span m=''3086700''>well,</span> <span m=''3086940''>is</span>
  <span m=''3087050''>there</span> <span m=''3087180''>buildup</span> <span m=''3088090''>in</span>
  <span m=''3088320''>principle</span> <span m=''3088770''>in</span> <span m=''3088830''>these</span>
  <span m=''3089000''>environment</span> <span m=''3089560''>frames?</span> <span
  m=''3091710''>And</span> <span m=''3091880''>the</span> <span m=''3091950''>answer</span>
  <span m=''3092150''>is</span> <span m=''3092220''>yeah,</span> <span m=''3092400''>you</span>
  <span m=''3092530''>have</span> <span m=''3092670''>to</span> <span m=''3092760''>make</span>
  <span m=''3092940''>these</span> <span m=''3093100''>new</span> <span m=''3093240''>environment</span>
  <span m=''3093740''>frames,</span> <span m=''3094020''>but</span> <span m=''3094140''>you</span>
  <span m=''3094240''>don''t</span> <span m=''3094380''>have</span> <span m=''3094550''>to</span>
  <span m=''3094630''>hang</span> <span m=''3094850''>onto</span> <span m=''3095120''>them</span>
  <span m=''3095560''>when</span> <span m=''3095700''>you''re</span> <span m=''3095830''>done.</span>
  <span m=''3096440''>They</span> <span m=''3096570''>can</span> <span m=''3096690''>be</span>
  <span m=''3096810''>garbage</span> <span m=''3097180''>collected,</span> <span m=''3097900''>or</span>
  <span m=''3098030''>the</span> <span m=''3098110''>space</span> <span m=''3098420''>can</span>
  <span m=''3098510''>be</span> <span m=''3098720''>reused</span> <span m=''3099020''>automatically.</span>
  <span m=''3100720''>But</span> <span m=''3100970''>you</span> <span m=''3101070''>see</span>
  <span m=''3101190''>the</span> <span m=''3101300''>control</span> <span m=''3101770''>structure</span>
  <span m=''3102230''>of</span> <span m=''3102290''>the</span> <span m=''3102350''>evaluator</span>
  <span m=''3103360''>is</span> <span m=''3103520''>really</span> <span m=''3103810''>using</span>
  <span m=''3104120''>this</span> <span m=''3104310''>idea</span> <span m=''3104610''>that</span>
  <span m=''3104760''>you</span> <span m=''3104870''>actually</span> <span m=''3105330''>have</span>
  <span m=''3105440''>a</span> <span m=''3105550''>reduction,</span> <span m=''3107020''>so</span>
  <span m=''3107190''>these</span> <span m=''3107360''>procedures</span> <span m=''3107790''>really</span>
  <span m=''3108100''>are</span> <span m=''3108250''>iterative</span> <span m=''3108780''>procedures.</span>
  <span m=''3110132''>All</span> <span m=''3110321''>right,</span> <span m=''3110510''>let''s</span>
  <span m=''3110680''>stop</span> <span m=''3110900''>for</span> <span m=''3110990''>questions.</span>
  <span m=''3122288''>All</span> <span m=''3122539''>right,</span> <span m=''3122790''>let''s</span>
  <span m=''3122990''>break.</span> </p><p><span m=''3168770''>Let</span> <span m=''3168880''>me</span>
  <span m=''3169010''>contrast</span> <span m=''3169580''>the</span> <span m=''3170550''>iterative</span>
  <span m=''3171000''>procedure</span> <span m=''3172900''>just</span> <span m=''3173080''>so</span>
  <span m=''3173160''>you''ll</span> <span m=''3173290''>see</span> <span m=''3173470''>where</span>
  <span m=''3173600''>space</span> <span m=''3174270''>does</span> <span m=''3174550''>build</span>
  <span m=''3174770''>up</span> <span m=''3175150''>with</span> <span m=''3175300''>a</span>
  <span m=''3175340''>recursive</span> <span m=''3175810''>procedure,</span> <span
  m=''3176250''>so</span> <span m=''3176330''>you</span> <span m=''3176480''>can</span>
  <span m=''3176590''>see</span> <span m=''3176750''>the</span> <span m=''3176840''>difference.</span>
  <span m=''3178030''>Let''s</span> <span m=''3178240''>look</span> <span m=''3178400''>at</span>
  <span m=''3178960''>the</span> <span m=''3179110''>evaluation</span> <span m=''3179790''>of</span>
  <span m=''3179910''>recursive</span> <span m=''3180470''>factorial,</span> <span
  m=''3182455''>all</span> <span m=''3182667''>right?</span> <span m=''3182880''>So,</span>
  <span m=''3184540''>here''s</span> <span m=''3184810''>fact-recursive,</span> <span
  m=''3185550''>or</span> <span m=''3185690''>standard</span> <span m=''3186170''>factorial</span>
  <span m=''3186690''>definition.</span> <span m=''3187220''>We</span> <span m=''3187350''>said</span>
  <span m=''3187540''>this</span> <span m=''3187710''>one</span> <span m=''3188820''>is</span>
  <span m=''3188950''>still</span> <span m=''3189170''>a</span> <span m=''3189210''>recursive</span>
  <span m=''3189680''>procedure,</span> <span m=''3190100''>but</span> <span m=''3190210''>this</span>
  <span m=''3190360''>is</span> <span m=''3190470''>actually</span> <span m=''3190980''>a</span>
  <span m=''3191020''>recursive</span> <span m=''3191770''>process.</span> </p><p><span
  m=''3193750''>And</span> <span m=''3193860''>then,</span> <span m=''3193970''>just</span>
  <span m=''3194150''>to</span> <span m=''3194250''>link</span> <span m=''3194500''>it</span>
  <span m=''3195210''>back</span> <span m=''3195450''>to</span> <span m=''3195690''>the</span>
  <span m=''3195745''>way</span> <span m=''3195800''>we</span> <span m=''3195940''>started,</span>
  <span m=''3196850''>we</span> <span m=''3197010''>said</span> <span m=''3197210''>oh,</span>
  <span m=''3197340''>you</span> <span m=''3197510''>can</span> <span m=''3198390''>see</span>
  <span m=''3198740''>that</span> <span m=''3198910''>it''s</span> <span m=''3199080''>going</span>
  <span m=''3199320''>to</span> <span m=''3199420''>be</span> <span m=''3199590''>recursive</span>
  <span m=''3200070''>process</span> <span m=''3200530''>by</span> <span m=''3200650''>the</span>
  <span m=''3200760''>substitution</span> <span m=''3201420''>model</span> <span m=''3202110''>because,</span>
  <span m=''3202720''>if</span> <span m=''3202870''>I</span> <span m=''3202930''>say</span>
  <span m=''3204010''>recursive</span> <span m=''3204520''>factorial</span> <span
  m=''3207290''>of</span> <span m=''3207400''>5,</span> <span m=''3210660''>that</span>
  <span m=''3212360''>turns</span> <span m=''3212670''>into</span> <span m=''3213390''>5</span>
  <span m=''3214310''>times--</span> <span m=''3216000''>what</span> <span m=''3216050''>is</span>
  <span m=''3216100''>it,</span> <span m=''3216150''>fact-rec,</span> <span m=''3216600''>or</span>
  <span m=''3217063''>record</span> <span m=''3217526''>fact--</span> <span m=''3222620''>5</span>
  <span m=''3222980''>times</span> <span m=''3224160''>recursive</span> <span m=''3224680''>factorial</span>
  <span m=''3227270''>of</span> <span m=''3227430''>4,</span> <span m=''3229460''>which</span>
  <span m=''3229730''>turns</span> <span m=''3230040''>into</span> <span m=''3231340''>5</span>
  <span m=''3232850''>times</span> <span m=''3233220''>4</span> <span m=''3234230''>times</span>
  <span m=''3236350''>fact-rec</span> <span m=''3237105''>of</span> <span m=''3237600''>3,</span>
  <span m=''3239934''>which</span> <span m=''3240360''>returns</span> <span m=''3240680''>into</span>
  <span m=''3240850''>5</span> <span m=''3242460''>times</span> <span m=''3243340''>4</span>
  <span m=''3246120''>times</span> <span m=''3246540''>3</span> <span m=''3248090''>times,</span>
  <span m=''3253590''>and</span> <span m=''3253730''>so</span> <span m=''3253940''>on,</span>
  <span m=''3254850''>right?</span> <span m=''3255240''>The</span> <span m=''3255370''>idea</span>
  <span m=''3255500''>is</span> <span m=''3255630''>there</span> <span m=''3255760''>was</span>
  <span m=''3255940''>this</span> <span m=''3256090''>chain</span> <span m=''3256420''>of</span>
  <span m=''3256510''>stuff</span> <span m=''3256830''>building</span> <span m=''3257200''>up,</span>
  <span m=''3258100''>which</span> <span m=''3258420''>justified,</span> <span m=''3259060''>in</span>
  <span m=''3259130''>the</span> <span m=''3259200''>substitution</span> <span m=''3259860''>model,</span>
  <span m=''3260150''>the</span> <span m=''3260230''>fact</span> <span m=''3260540''>that</span>
  <span m=''3260625''>it''s</span> <span m=''3260710''>recursive.</span> <span m=''3261520''>And</span>
  <span m=''3261650''>now,</span> <span m=''3262250''>let''s</span> <span m=''3262450''>actually</span>
  <span m=''3262720''>see</span> <span m=''3262970''>that</span> <span m=''3263190''>chain</span>
  <span m=''3263470''>of</span> <span m=''3263540''>stuff</span> <span m=''3263800''>build</span>
  <span m=''3264040''>up</span> <span m=''3264180''>and</span> <span m=''3264290''>where</span>
  <span m=''3264470''>it</span> <span m=''3264500''>is</span> <span m=''3264530''>in</span>
  <span m=''3264670''>the</span> <span m=''3264810''>machine,</span> <span m=''3266555''>OK?</span>
  </p><p><span m=''3267465''>All</span> <span m=''3267692''>right,</span> <span m=''3267920''>well,</span>
  <span m=''3268090''>let''s</span> <span m=''3268260''>imagine</span> <span m=''3268760''>we''re</span>
  <span m=''3268880''>going</span> <span m=''3268970''>to</span> <span m=''3269010''>start</span>
  <span m=''3269350''>out</span> <span m=''3269520''>again.</span> <span m=''3270230''>We''ll</span>
  <span m=''3270660''>tell</span> <span m=''3270910''>it</span> <span m=''3270990''>to</span>
  <span m=''3271220''>evaluate</span> <span m=''3276390''>recursive</span> <span m=''3276910''>factorial</span>
  <span m=''3279450''>of</span> <span m=''3279520''>5</span> <span m=''3281560''>in</span>
  <span m=''3281690''>some</span> <span m=''3281920''>environment,</span> <span m=''3282420''>again,</span>
  <span m=''3282660''>E,0</span> <span m=''3285150''>where</span> <span m=''3285270''>recursive</span>
  <span m=''3285720''>factorial</span> <span m=''3285880''>is</span> <span m=''3286360''>defined,</span>
  <span m=''3287866''>OK?</span> <span m=''3289580''>Well,</span> <span m=''3289730''>now</span>
  <span m=''3289870''>we</span> <span m=''3289960''>know</span> <span m=''3290070''>what''s</span>
  <span m=''3290220''>eventually</span> <span m=''3290720''>going</span> <span m=''3290870''>to</span>
  <span m=''3290910''>happen.</span> <span m=''3292490''>This</span> <span m=''3292640''>is</span>
  <span m=''3292730''>going</span> <span m=''3292820''>to</span> <span m=''3292880''>come</span>
  <span m=''3293080''>along,</span> <span m=''3294220''>it''ll</span> <span m=''3294670''>evaluate</span>
  <span m=''3295210''>those</span> <span m=''3295410''>things,</span> <span m=''3295670''>figure</span>
  <span m=''3295960''>out</span> <span m=''3296070''>it''s</span> <span m=''3296220''>a</span>
  <span m=''3296270''>procedure,</span> <span m=''3297240''>build</span> <span m=''3297480''>somewhere</span>
  <span m=''3298270''>over</span> <span m=''3298550''>here</span> <span m=''3298705''>an</span>
  <span m=''3298860''>environment,</span> <span m=''3299410''>E,1,</span> <span m=''3300570''>which</span>
  <span m=''3301110''>has</span> <span m=''3301310''>n</span> <span m=''3302850''>bound</span>
  <span m=''3302990''>to</span> <span m=''3303130''>5,</span> <span m=''3304370''>which</span>
  <span m=''3304620''>hangs</span> <span m=''3305420''>off</span> <span m=''3305680''>of</span>
  <span m=''3305860''>E,0,</span> <span m=''3307740''>which</span> <span m=''3308130''>would</span>
  <span m=''3308240''>be,</span> <span m=''3308360''>presumably,</span> <span m=''3308850''>the</span>
  <span m=''3309042''>definition</span> <span m=''3309620''>environment</span> <span
  m=''3310990''>of</span> <span m=''3311100''>recursive</span> <span m=''3311570''>factorial,</span>
  <span m=''3314152''>OK?</span> </p><p><span m=''3314610''>And,</span> <span m=''3314780''>in</span>
  <span m=''3315030''>this</span> <span m=''3315200''>environment,</span> <span m=''3315710''>it''s</span>
  <span m=''3315870''>going</span> <span m=''3315960''>to</span> <span m=''3316000''>go</span>
  <span m=''3316210''>off</span> <span m=''3316380''>and</span> <span m=''3316490''>evaluate</span>
  <span m=''3317000''>the</span> <span m=''3317070''>body.</span> <span m=''3319670''>So,</span>
  <span m=''3319880''>again,</span> <span m=''3320690''>the</span> <span m=''3323680''>evaluation</span>
  <span m=''3324460''>here</span> <span m=''3324740''>will</span> <span m=''3325010''>reduce</span>
  <span m=''3325540''>to</span> <span m=''3327170''>evaluating</span> <span m=''3327790''>the</span>
  <span m=''3327860''>body</span> <span m=''3328330''>in</span> <span m=''3328410''>E,1.</span>
  <span m=''3330240''>That''s</span> <span m=''3330460''>going</span> <span m=''3330580''>to</span>
  <span m=''3330670''>look</span> <span m=''3330840''>at</span> <span m=''3330900''>an</span>
  <span m=''3331040''>if,</span> <span m=''3331905''>and</span> <span m=''3332350''>I</span>
  <span m=''3332400''>won''t</span> <span m=''3332570''>go</span> <span m=''3332670''>through</span>
  <span m=''3332790''>the</span> <span m=''3332880''>details</span> <span m=''3333260''>of</span>
  <span m=''3333370''>if.</span> <span m=''3333530''>It''ll</span> <span m=''3333690''>look</span>
  <span m=''3333890''>at</span> <span m=''3333950''>the</span> <span m=''3334020''>predicate.</span>
  <span m=''3334880''>It''ll</span> <span m=''3335140''>decide</span> <span m=''3335380''>it</span>
  <span m=''3335620''>eventually</span> <span m=''3336050''>has</span> <span m=''3336250''>to</span>
  <span m=''3336330''>evaluate</span> <span m=''3336800''>the</span> <span m=''3336890''>alternative.</span>
  <span m=''3337840''>So</span> <span m=''3338030''>this</span> <span m=''3338200''>whole</span>
  <span m=''3338440''>thing,</span> <span m=''3339070''>again,</span> <span m=''3339540''>will</span>
  <span m=''3339690''>reduce</span> <span m=''3340040''>to</span> <span m=''3341450''>the</span>
  <span m=''3341640''>alternative</span> <span m=''3343122''>of</span> <span m=''3344510''>recursive</span>
  <span m=''3344950''>factorial,</span> <span m=''3345600''>the</span> <span m=''3346030''>alternative</span>
  <span m=''3346510''>clause,</span> <span m=''3347270''>which</span> <span m=''3347690''>says</span>
  <span m=''3347870''>that</span> <span m=''3347940''>this</span> <span m=''3348010''>whole</span>
  <span m=''3348220''>thing</span> <span m=''3348370''>reduces</span> <span m=''3348850''>to</span>
  <span m=''3349560''>times</span> <span m=''3350680''>n</span> <span m=''3352600''>of</span>
  <span m=''3355480''>recursive</span> <span m=''3356040''>factorial</span> <span
  m=''3358264''>of</span> <span m=''3359130''>n</span> <span m=''3359350''>minus</span>
  <span m=''3359720''>1</span> <span m=''3363550''>in</span> <span m=''3364260''>the</span>
  <span m=''3364400''>environment</span> <span m=''3364940''>E,1,</span> <span m=''3368220''>OK?</span>
  <span m=''3368720''>So</span> <span m=''3369190''>the</span> <span m=''3369310''>original</span>
  <span m=''3369640''>expression,</span> <span m=''3369905''>now,</span> <span m=''3370170''>is</span>
  <span m=''3370240''>going</span> <span m=''3370340''>to</span> <span m=''3370390''>reduce</span>
  <span m=''3370990''>to</span> <span m=''3371200''>evaluating</span> <span m=''3371750''>that</span>
  <span m=''3371930''>expression,</span> <span m=''3373725''>all</span> <span m=''3373927''>right?</span>
  </p><p><span m=''3374130''>Now</span> <span m=''3374370''>we</span> <span m=''3374500''>have</span>
  <span m=''3375420''>an</span> <span m=''3375540''>application.</span> <span m=''3376280''>We</span>
  <span m=''3376360''>did</span> <span m=''3376480''>an</span> <span m=''3376570''>application</span>
  <span m=''3377150''>before.</span> <span m=''3378500''>Remember</span> <span m=''3378810''>what</span>
  <span m=''3379040''>happens</span> <span m=''3379370''>in</span> <span m=''3379440''>an</span>
  <span m=''3379530''>application?</span> <span m=''3380390''>The</span> <span m=''3380480''>first</span>
  <span m=''3380740''>thing</span> <span m=''3380880''>you</span> <span m=''3381020''>do</span>
  <span m=''3381150''>is</span> <span m=''3381250''>you</span> <span m=''3381350''>go</span>
  <span m=''3381540''>off</span> <span m=''3381720''>and</span> <span m=''3381840''>you</span>
  <span m=''3381920''>save</span> <span m=''3382780''>the</span> <span m=''3382880''>value</span>
  <span m=''3383230''>of</span> <span m=''3383300''>the</span> <span m=''3383380''>continue</span>
  <span m=''3383800''>register</span> <span m=''3384220''>on</span> <span m=''3384310''>the</span>
  <span m=''3384370''>stack.</span> <span m=''3385350''>So</span> <span m=''3385520''>the</span>
  <span m=''3385610''>stack</span> <span m=''3385970''>here</span> <span m=''3386180''>is</span>
  <span m=''3386270''>going</span> <span m=''3386370''>to</span> <span m=''3386410''>have</span>
  <span m=''3386650''>done</span> <span m=''3386930''>in</span> <span m=''3387147''>it.</span>
  <span m=''3389980''>And</span> <span m=''3390130''>then</span> <span m=''3390250''>you''re</span>
  <span m=''3390360''>going</span> <span m=''3390470''>to</span> <span m=''3391210''>set</span>
  <span m=''3391470''>up</span> <span m=''3391610''>to</span> <span m=''3391780''>evaluate</span>
  <span m=''3392230''>the</span> <span m=''3392300''>sub-parts,</span> <span m=''3394692''>OK?</span>
  <span m=''3395130''>So</span> <span m=''3395310''>here</span> <span m=''3395460''>we</span>
  <span m=''3395570''>go</span> <span m=''3395730''>off</span> <span m=''3395870''>to</span>
  <span m=''3396010''>evaluate</span> <span m=''3396430''>the</span> <span m=''3396500''>sub-parts.</span>
  </p><p><span m=''3399520''>First</span> <span m=''3399740''>thing</span> <span m=''3399840''>we''re</span>
  <span m=''3399890''>going</span> <span m=''3399940''>to</span> <span m=''3399990''>do</span>
  <span m=''3400090''>is</span> <span m=''3400200''>evaluate</span> <span m=''3400660''>the</span>
  <span m=''3400760''>operator.</span> <span m=''3404490''>What</span> <span m=''3404750''>happens</span>
  <span m=''3405050''>when</span> <span m=''3405160''>we</span> <span m=''3405290''>evaluate</span>
  <span m=''3405740''>an</span> <span m=''3405820''>operator?</span> <span m=''3407250''>Well,</span>
  <span m=''3407580''>we</span> <span m=''3407970''>arrange</span> <span m=''3408510''>things</span>
  <span m=''3408750''>so</span> <span m=''3408860''>that</span> <span m=''3409000''>the</span>
  <span m=''3409120''>operator</span> <span m=''3409590''>ends</span> <span m=''3409760''>up</span>
  <span m=''3409870''>in</span> <span m=''3409940''>the</span> <span m=''3410030''>expression</span>
  <span m=''3410480''>register.</span> <span m=''3411480''>The</span> <span m=''3411610''>environments</span>
  <span m=''3412160''>in</span> <span m=''3412230''>the</span> <span m=''3412400''>ENV</span>
  <span m=''3412560''>register</span> <span m=''3413720''>continue</span> <span m=''3414140''>someplace</span>
  <span m=''3414630''>where</span> <span m=''3414720''>we''re</span> <span m=''3414810''>going</span>
  <span m=''3414890''>to</span> <span m=''3414940''>go</span> <span m=''3415120''>evaluate</span>
  <span m=''3415540''>the</span> <span m=''3415650''>arguments.</span> <span m=''3416590''>And,</span>
  <span m=''3416820''>on</span> <span m=''3416930''>the</span> <span m=''3417000''>stack,</span>
  <span m=''3417410''>we''ve</span> <span m=''3417530''>saved</span> <span m=''3418200''>the</span>
  <span m=''3418360''>original</span> <span m=''3418710''>continue,</span> <span m=''3419270''>which</span>
  <span m=''3419520''>is</span> <span m=''3419610''>where</span> <span m=''3419740''>we</span>
  <span m=''3419820''>wanted</span> <span m=''3420030''>to</span> <span m=''3420090''>be</span>
  <span m=''3420210''>when</span> <span m=''3420360''>we''re</span> <span m=''3420520''>all</span>
  <span m=''3420640''>done.</span> <span m=''3421720''>And</span> <span m=''3421880''>then</span>
  <span m=''3421980''>the</span> <span m=''3422060''>things</span> <span m=''3422290''>we</span>
  <span m=''3422430''>needed</span> <span m=''3423270''>when</span> <span m=''3423650''>we''re</span>
  <span m=''3423900''>going</span> <span m=''3424010''>to</span> <span m=''3424060''>get</span>
  <span m=''3424280''>done</span> <span m=''3424510''>evaluating</span> <span m=''3425040''>the</span>
  <span m=''3425160''>operator,</span> <span m=''3425730''>the</span> <span m=''3426010''>things</span>
  <span m=''3426250''>we''ll</span> <span m=''3426380''>need</span> <span m=''3426640''>to</span>
  <span m=''3426760''>evaluate</span> <span m=''3427190''>the</span> <span m=''3427290''>arguments,</span>
  <span m=''3427760''>namely,</span> <span m=''3428430''>the</span> <span m=''3428580''>environment</span>
  <span m=''3430450''>and</span> <span m=''3431510''>those</span> <span m=''3431710''>arguments,</span>
  <span m=''3432190''>those</span> <span m=''3432320''>unevaluated</span> <span m=''3432920''>arguments,</span>
  <span m=''3434210''>so</span> <span m=''3434370''>there</span> <span m=''3434520''>they</span>
  <span m=''3434670''>are</span> <span m=''3434790''>sitting</span> <span m=''3435080''>on</span>
  <span m=''3435200''>the</span> <span m=''3435250''>stack.</span> <span m=''3435620''>And</span>
  <span m=''3435700''>we''re</span> <span m=''3435840''>about</span> <span m=''3436110''>to</span>
  <span m=''3437090''>go</span> <span m=''3437220''>off</span> <span m=''3437390''>to</span>
  <span m=''3437540''>evaluate</span> <span m=''3438000''>the</span> <span m=''3438100''>operator.</span>
  </p><p><span m=''3443130''>Well,</span> <span m=''3443840''>when</span> <span m=''3444250''>we</span>
  <span m=''3444370''>return</span> <span m=''3445390''>from</span> <span m=''3445530''>this</span>
  <span m=''3445710''>particular</span> <span m=''3446230''>call--</span> <span m=''3446920''>so</span>
  <span m=''3447070''>we''re</span> <span m=''3447200''>about</span> <span m=''3447400''>to</span>
  <span m=''3447480''>call</span> <span m=''3447710''>eval-dispatch</span> <span m=''3448250''>here--</span>
  <span m=''3449380''>when</span> <span m=''3449540''>we</span> <span m=''3449660''>return</span>
  <span m=''3450120''>from</span> <span m=''3450280''>this</span> <span m=''3450460''>call,</span>
  <span m=''3451470''>the</span> <span m=''3451600''>value</span> <span m=''3452000''>of</span>
  <span m=''3452050''>that</span> <span m=''3452230''>operator,</span> <span m=''3452730''>which,</span>
  <span m=''3452940''>in</span> <span m=''3453060''>this</span> <span m=''3453180''>case,</span>
  <span m=''3453400''>is</span> <span m=''3453500''>going</span> <span m=''3453590''>to</span>
  <span m=''3453670''>be</span> <span m=''3453760''>the</span> <span m=''3453850''>primitive</span>
  <span m=''3454380''>multiplier</span> <span m=''3454890''>procedure,</span> <span
  m=''3456510''>will</span> <span m=''3456670''>end</span> <span m=''3456900''>up</span>
  <span m=''3457020''>in</span> <span m=''3457130''>the</span> <span m=''3457200''>FUN</span>
  <span m=''3457440''>register,</span> <span m=''3461215''>all</span> <span m=''3461447''>right?</span>
  <span m=''3463080''>We''re</span> <span m=''3463250''>going</span> <span m=''3463340''>to</span>
  <span m=''3463430''>evaluate</span> <span m=''3463930''>some</span> <span m=''3464070''>arguments.</span>
  <span m=''3464530''>They</span> <span m=''3464590''>will</span> <span m=''3464780''>evaluate</span>
  <span m=''3465280''>in</span> <span m=''3465530''>here.</span> <span m=''3467730''>That''ll</span>
  <span m=''3467980''>give</span> <span m=''3468160''>us</span> <span m=''3468740''>5,</span>
  <span m=''3469210''>in</span> <span m=''3469300''>this</span> <span m=''3469470''>case.</span>
  <span m=''3470250''>We''re</span> <span m=''3470350''>going</span> <span m=''3470430''>to</span>
  <span m=''3470490''>put</span> <span m=''3470650''>that</span> <span m=''3470810''>in</span>
  <span m=''3470930''>the</span> <span m=''3471080''>argl</span> <span m=''3471440''>register,</span>
  <span m=''3473100''>and</span> <span m=''3473230''>then</span> <span m=''3473360''>we''ll</span>
  <span m=''3473480''>go</span> <span m=''3473640''>off</span> <span m=''3474180''>to</span>
  <span m=''3474400''>evaluate</span> <span m=''3475140''>the</span> <span m=''3475340''>second</span>
  <span m=''3475540''>operand.</span> </p><p><span m=''3477460''>So,</span> <span
  m=''3477660''>at</span> <span m=''3477720''>the</span> <span m=''3477790''>point</span>
  <span m=''3478050''>where</span> <span m=''3478150''>we</span> <span m=''3478260''>go</span>
  <span m=''3478450''>off</span> <span m=''3478610''>to</span> <span m=''3478760''>evaluate</span>
  <span m=''3479690''>the</span> <span m=''3479870''>second</span> <span m=''3480050''>operand--</span>
  <span m=''3480490''>and</span> <span m=''3480570''>I''ll</span> <span m=''3480840''>skip</span>
  <span m=''3481160''>details</span> <span m=''3481620''>like</span> <span m=''3481800''>computing,</span>
  <span m=''3482290''>and</span> <span m=''3482390''>minus</span> <span m=''3482740''>1,</span>
  <span m=''3483000''>and</span> <span m=''3483086''>all</span> <span m=''3483173''>of</span>
  <span m=''3483260''>that--</span> <span m=''3483530''>but,</span> <span m=''3483900''>when</span>
  <span m=''3484010''>we</span> <span m=''3484120''>go</span> <span m=''3484290''>off</span>
  <span m=''3484390''>to</span> <span m=''3484510''>evaluate</span> <span m=''3484910''>the</span>
  <span m=''3485080''>second</span> <span m=''3485250''>operand,</span> <span m=''3486670''>that</span>
  <span m=''3486900''>will</span> <span m=''3487060''>eventually</span> <span m=''3487720''>reduce</span>
  <span m=''3488100''>to</span> <span m=''3488210''>another</span> <span m=''3488550''>call</span>
  <span m=''3488850''>to</span> <span m=''3489190''>fact-recursive.</span> <span m=''3492060''>And,</span>
  <span m=''3492200''>what</span> <span m=''3492300''>we''ve</span> <span m=''3492410''>got</span>
  <span m=''3492590''>on</span> <span m=''3492690''>the</span> <span m=''3492750''>stack</span>
  <span m=''3493130''>here</span> <span m=''3493750''>is</span> <span m=''3496720''>the</span>
  <span m=''3496860''>operator</span> <span m=''3497520''>from</span> <span m=''3497670''>that</span>
  <span m=''3497820''>combination</span> <span m=''3499030''>that</span> <span m=''3499140''>we''re</span>
  <span m=''3499240''>going</span> <span m=''3499340''>to</span> <span m=''3499380''>use</span>
  <span m=''3499610''>it</span> <span m=''3499690''>in</span> <span m=''3500120''>and</span>
  <span m=''3500290''>the</span> <span m=''3500400''>other</span> <span m=''3500680''>argument,</span>
  <span m=''3503600''>OK?</span> <span m=''3503790''>So,</span> <span m=''3506110''>now,</span>
  <span m=''3506250''>we''re</span> <span m=''3506350''>set</span> <span m=''3506530''>up</span>
  <span m=''3506630''>for</span> <span m=''3506780''>another</span> <span m=''3507180''>call</span>
  <span m=''3508490''>to</span> <span m=''3508630''>recursive</span> <span m=''3509090''>factorial.</span>
  <span m=''3510200''>And,</span> <span m=''3510360''>when</span> <span m=''3510490''>we''re</span>
  <span m=''3510590''>done</span> <span m=''3510790''>with</span> <span m=''3510930''>this</span>
  <span m=''3511130''>one,</span> <span m=''3511530''>we''re</span> <span m=''3511740''>going</span>
  <span m=''3511830''>to</span> <span m=''3511870''>go</span> <span m=''3512100''>to</span>
  <span m=''3512300''>accumulate</span> <span m=''3512860''>the</span> <span m=''3512940''>last</span>
  <span m=''3513200''>arg.</span> <span m=''3513935''>And</span> <span m=''3514320''>remember</span>
  <span m=''3514670''>what</span> <span m=''3514810''>that''ll</span> <span m=''3515100''>do?</span>
  <span m=''3515200''>That''ll</span> <span m=''3515440''>say</span> <span m=''3515640''>oh,</span>
  <span m=''3516460''>whatever</span> <span m=''3516840''>the</span> <span m=''3516930''>result</span>
  <span m=''3517300''>of</span> <span m=''3517380''>this</span> <span m=''3517840''>has</span>
  <span m=''3518040''>to</span> <span m=''3518140''>get</span> <span m=''3518290''>combined</span>
  <span m=''3518660''>with</span> <span m=''3518820''>that,</span> <span m=''3519310''>and</span>
  <span m=''3519410''>we''re</span> <span m=''3519510''>going</span> <span m=''3519580''>to</span>
  <span m=''3519640''>multiply</span> <span m=''3520090''>them.</span> </p><p><span
  m=''3521690''>But,</span> <span m=''3521830''>notice</span> <span m=''3522180''>now,</span>
  <span m=''3522570''>we''re</span> <span m=''3523370''>at</span> <span m=''3523500''>another</span>
  <span m=''3523780''>recursive</span> <span m=''3524270''>factorial.</span> <span
  m=''3525720''>We''re</span> <span m=''3525890''>about</span> <span m=''3526130''>to</span>
  <span m=''3526230''>call</span> <span m=''3527990''>eval-dispatch</span> <span m=''3528570''>again,</span>
  <span m=''3529380''>except</span> <span m=''3529630''>we</span> <span m=''3529710''>haven''t</span>
  <span m=''3529870''>really</span> <span m=''3530090''>reduced</span> <span m=''3530530''>it</span>
  <span m=''3530610''>because</span> <span m=''3530850''>there''s</span> <span m=''3530990''>stuff</span>
  <span m=''3531250''>on</span> <span m=''3531390''>the</span> <span m=''3531460''>stack</span>
  <span m=''3531870''>now.</span> <span m=''3533700''>The</span> <span m=''3533830''>stuff</span>
  <span m=''3533960''>on</span> <span m=''3534050''>the</span> <span m=''3534130''>stack</span>
  <span m=''3534380''>says</span> <span m=''3534520''>oh,</span> <span m=''3534650''>when</span>
  <span m=''3534800''>you</span> <span m=''3534910''>get</span> <span m=''3535100''>back,</span>
  <span m=''3535380''>you''d</span> <span m=''3535490''>better</span> <span m=''3535690''>multiply</span>
  <span m=''3536150''>it</span> <span m=''3536230''>by</span> <span m=''3536350''>the</span>
  <span m=''3536440''>5</span> <span m=''3536760''>you</span> <span m=''3536805''>had</span>
  <span m=''3536850''>hanging</span> <span m=''3537115''>there.</span> <span m=''3538430''>So,</span>
  <span m=''3538610''>when</span> <span m=''3544540''>we</span> <span m=''3544660''>go</span>
  <span m=''3544860''>off</span> <span m=''3544925''>to</span> <span m=''3544990''>make</span>
  <span m=''3545150''>another</span> <span m=''3545440''>call,</span> <span m=''3547310''>we</span>
  <span m=''3547430''>evaluate</span> <span m=''3547880''>the</span> <span m=''3547990''>n</span>
  <span m=''3548100''>minus</span> <span m=''3548430''>1.</span> <span m=''3549300''>That</span>
  <span m=''3549460''>gives</span> <span m=''3549640''>us</span> <span m=''3549750''>another</span>
  <span m=''3550100''>environment</span> <span m=''3551430''>in</span> <span m=''3551510''>which</span>
  <span m=''3551720''>the</span> <span m=''3551820''>new</span> <span m=''3552050''>n''s</span>
  <span m=''3552320''>going</span> <span m=''3552420''>to</span> <span m=''3552910''>be</span>
  <span m=''3553085''>down</span> <span m=''3553260''>to</span> <span m=''3553360''>4.</span>
  <span m=''3554600''>And</span> <span m=''3554710''>we''re</span> <span m=''3554840''>about</span>
  <span m=''3555060''>to</span> <span m=''3555140''>call</span> <span m=''3555400''>eval-dispatch</span>
  <span m=''3556130''>again,</span> <span m=''3558490''>right?</span> </p><p><span
  m=''3558930''>We</span> <span m=''3559330''>get</span> <span m=''3559450''>another</span>
  <span m=''3559770''>call.</span> <span m=''3561350''>That</span> <span m=''3561530''>4</span>
  <span m=''3561820''>is</span> <span m=''3561910''>going</span> <span m=''3562000''>to</span>
  <span m=''3562050''>end</span> <span m=''3562260''>up</span> <span m=''3562360''>in</span>
  <span m=''3563380''>the</span> <span m=''3563470''>same</span> <span m=''3563740''>situation.</span>
  <span m=''3566040''>We''ll</span> <span m=''3566200''>end</span> <span m=''3566330''>up</span>
  <span m=''3566440''>with</span> <span m=''3566630''>another</span> <span m=''3567040''>call</span>
  <span m=''3567350''>to</span> <span m=''3567440''>fact-recursive</span> <span m=''3568210''>n.</span>
  <span m=''3570020''>And</span> <span m=''3570390''>sitting</span> <span m=''3570670''>on</span>
  <span m=''3570770''>the</span> <span m=''3570840''>stack</span> <span m=''3571150''>will</span>
  <span m=''3571240''>be</span> <span m=''3571350''>the</span> <span m=''3571440''>stuff</span>
  <span m=''3571700''>from</span> <span m=''3571820''>the</span> <span m=''3571960''>original</span>
  <span m=''3572330''>one</span> <span m=''3572870''>and,</span> <span m=''3573030''>now,</span>
  <span m=''3573170''>the</span> <span m=''3573250''>subsidiary</span> <span m=''3573580''>one</span>
  <span m=''3573910''>we''re</span> <span m=''3574120''>doing.</span> <span m=''3575360''>And</span>
  <span m=''3575510''>both</span> <span m=''3575700''>of</span> <span m=''3575780''>them</span>
  <span m=''3575850''>are</span> <span m=''3575910''>waiting</span> <span m=''3576210''>for</span>
  <span m=''3576300''>the</span> <span m=''3576390''>same</span> <span m=''3576640''>thing.</span>
  <span m=''3576910''>They''re</span> <span m=''3577000''>going</span> <span m=''3577110''>to</span>
  <span m=''3577150''>go</span> <span m=''3577330''>to</span> <span m=''3577830''>accumulate</span>
  <span m=''3578380''>a</span> <span m=''3578440''>last</span> <span m=''3578780''>argument.</span>
  <span m=''3580600''>And</span> <span m=''3580730''>then,</span> <span m=''3580830''>of</span>
  <span m=''3580900''>course,</span> <span m=''3581170''>when</span> <span m=''3581310''>we</span>
  <span m=''3581970''>go</span> <span m=''3582070''>to</span> <span m=''3582160''>the</span>
  <span m=''3582270''>fourth</span> <span m=''3582590''>call,</span> <span m=''3583410''>the</span>
  <span m=''3583480''>same</span> <span m=''3583740''>thing</span> <span m=''3583910''>happens,</span>
  <span m=''3585252''>right?</span> <span m=''3585640''>And</span> <span m=''3585860''>this</span>
  <span m=''3586020''>goes</span> <span m=''3586190''>on,</span> <span m=''3586460''>and</span>
  <span m=''3586540''>on,</span> <span m=''3586720''>and</span> <span m=''3586800''>on.</span>
  </p><p><span m=''3587300''>And</span> <span m=''3587400''>what</span> <span m=''3587530''>you</span>
  <span m=''3587620''>see</span> <span m=''3587980''>here</span> <span m=''3588055''>on</span>
  <span m=''3588130''>the</span> <span m=''3588180''>stack,</span> <span m=''3590370''>exactly</span>
  <span m=''3591010''>what''s</span> <span m=''3591180''>sitting</span> <span m=''3591430''>here</span>
  <span m=''3591650''>on</span> <span m=''3591720''>the</span> <span m=''3591790''>stack,</span>
  <span m=''3592130''>the</span> <span m=''3592250''>thing</span> <span m=''3592370''>that</span>
  <span m=''3592520''>says</span> <span m=''3592680''>times</span> <span m=''3593790''>and</span>
  <span m=''3594000''>5.</span> <span m=''3594960''>And</span> <span m=''3595150''>what</span>
  <span m=''3595300''>you''re</span> <span m=''3595470''>going</span> <span m=''3595630''>to</span>
  <span m=''3595710''>do</span> <span m=''3595960''>with</span> <span m=''3596100''>that</span>
  <span m=''3596580''>is</span> <span m=''3596740''>accumulate</span> <span m=''3597300''>that</span>
  <span m=''3597490''>into</span> <span m=''3597790''>a</span> <span m=''3597840''>last</span>
  <span m=''3598150''>argument.</span> <span m=''3600470''>That''s</span> <span m=''3600700''>exactly</span>
  <span m=''3601220''>this,</span> <span m=''3601580''>right?</span> <span m=''3602760''>This</span>
  <span m=''3602960''>is</span> <span m=''3603070''>exactly</span> <span m=''3603640''>where</span>
  <span m=''3603790''>that</span> <span m=''3604010''>stuff</span> <span m=''3604240''>is</span>
  <span m=''3604360''>hanging.</span> <span m=''3605650''>Effectively,</span> <span
  m=''3608832''>the</span> <span m=''3609330''>operator</span> <span m=''3609810''>you''re</span>
  <span m=''3609950''>going</span> <span m=''3610020''>to</span> <span m=''3610090''>apply,</span>
  <span m=''3611840''>the</span> <span m=''3612650''>other</span> <span m=''3612930''>argument</span>
  <span m=''3613790''>that</span> <span m=''3613950''>it''s</span> <span m=''3614090''>got</span>
  <span m=''3614185''>to</span> <span m=''3614280''>be</span> <span m=''3614400''>multiplied</span>
  <span m=''3614870''>by</span> <span m=''3615070''>when</span> <span m=''3615220''>you</span>
  <span m=''3615300''>get</span> <span m=''3615490''>back</span> <span m=''3615840''>and</span>
  <span m=''3616270''>the</span> <span m=''3616350''>parentheses,</span> <span m=''3616950''>which</span>
  <span m=''3617120''>says</span> <span m=''3617200''>yeah,</span> <span m=''3617380''>what</span>
  <span m=''3617510''>you</span> <span m=''3617620''>wanted</span> <span m=''3617780''>to</span>
  <span m=''3617940''>do</span> <span m=''3618090''>was</span> <span m=''3618190''>accumulate</span>
  <span m=''3618670''>them.</span> <span m=''3619620''>So,</span> <span m=''3619750''>you</span>
  <span m=''3619840''>see,</span> <span m=''3619970''>the</span> <span m=''3620050''>substitution</span>
  <span m=''3620690''>model</span> <span m=''3620950''>is</span> <span m=''3621070''>not</span>
  <span m=''3621300''>such</span> <span m=''3621500''>a</span> <span m=''3621570''>lie.</span>
  <span m=''3622560''>That</span> <span m=''3622740''>really</span> <span m=''3623040''>is,</span>
  <span m=''3623160''>in</span> <span m=''3623250''>some</span> <span m=''3623440''>sense,</span>
  <span m=''3623690''>what''s</span> <span m=''3623840''>sitting</span> <span m=''3624460''>right</span>
  <span m=''3624680''>on</span> <span m=''3624810''>the</span> <span m=''3624870''>stack.</span>
  <span m=''3627198''>OK.</span> </p><p><span m=''3629046''>All</span> <span m=''3629278''>right,</span>
  <span m=''3629510''>so</span> <span m=''3630210''>that,</span> <span m=''3630910''>in</span>
  <span m=''3631010''>some</span> <span m=''3631200''>sense,</span> <span m=''3631380''>should</span>
  <span m=''3631540''>explain</span> <span m=''3632000''>for</span> <span m=''3632140''>you,</span>
  <span m=''3633260''>or</span> <span m=''3633350''>at</span> <span m=''3633440''>least</span>
  <span m=''3633840''>convince</span> <span m=''3634310''>you,</span> <span m=''3635930''>that,</span>
  <span m=''3636760''>somehow,</span> <span m=''3637140''>this</span> <span m=''3637300''>evaluator</span>
  <span m=''3637850''>is</span> <span m=''3638080''>managing</span> <span m=''3640130''>to</span>
  <span m=''3640250''>take</span> <span m=''3640470''>these</span> <span m=''3640650''>procedures</span>
  <span m=''3641070''>and</span> <span m=''3641140''>execute</span> <span m=''3641580''>some</span>
  <span m=''3641810''>of</span> <span m=''3641870''>them</span> <span m=''3641960''>iteratively</span>
  <span m=''3643000''>and</span> <span m=''3643170''>some</span> <span m=''3643360''>of</span>
  <span m=''3643400''>them</span> <span m=''3643490''>recursively,</span> <span m=''3645320''>even</span>
  <span m=''3645540''>though,</span> <span m=''3646410''>as</span> <span m=''3646640''>syntactically,</span>
  <span m=''3647470''>they</span> <span m=''3647600''>look</span> <span m=''3647770''>like</span>
  <span m=''3647940''>recursive</span> <span m=''3648370''>procedures.</span> <span
  m=''3649430''>How''s</span> <span m=''3649660''>it</span> <span m=''3649760''>managing</span>
  <span m=''3650150''>to</span> <span m=''3650260''>do</span> <span m=''3650420''>that?</span>
  <span m=''3650660''>Well,</span> <span m=''3651550''>the</span> <span m=''3651640''>basic</span>
  <span m=''3652160''>reason</span> <span m=''3652490''>it''s</span> <span m=''3652650''>managing</span>
  <span m=''3653040''>to</span> <span m=''3653130''>do</span> <span m=''3653320''>that</span>
  <span m=''3653870''>is</span> <span m=''3654010''>the</span> <span m=''3654090''>evaluator</span>
  <span m=''3655040''>is</span> <span m=''3655190''>set</span> <span m=''3655430''>up</span>
  <span m=''3656070''>to</span> <span m=''3656200''>save</span> <span m=''3656560''>only</span>
  <span m=''3657170''>what</span> <span m=''3658520''>it</span> <span m=''3658700''>needs</span>
  <span m=''3658980''>later.</span> </p><p><span m=''3661090''>So,</span> <span m=''3661290''>for</span>
  <span m=''3661480''>example,</span> <span m=''3662030''>at</span> <span m=''3662290''>the</span>
  <span m=''3662350''>point</span> <span m=''3663070''>where</span> <span m=''3663570''>you''ve</span>
  <span m=''3663770''>reduced</span> <span m=''3664670''>evaluating</span> <span m=''3665350''>an</span>
  <span m=''3665430''>expression</span> <span m=''3666400''>and</span> <span m=''3666570''>an</span>
  <span m=''3666660''>environment</span> <span m=''3667860''>to</span> <span m=''3668000''>applying</span>
  <span m=''3668520''>a</span> <span m=''3668580''>procedure</span> <span m=''3669020''>to</span>
  <span m=''3669120''>some</span> <span m=''3669310''>arguments,</span> <span m=''3670720''>it</span>
  <span m=''3670850''>doesn''t</span> <span m=''3671130''>need</span> <span m=''3671280''>that</span>
  <span m=''3671400''>original</span> <span m=''3671700''>environment</span> <span
  m=''3672170''>anymore</span> <span m=''3673560''>because</span> <span m=''3673840''>any</span>
  <span m=''3674070''>environment</span> <span m=''3674640''>stuff</span> <span m=''3674890''>will</span>
  <span m=''3674980''>be</span> <span m=''3675110''>packaged</span> <span m=''3675600''>inside</span>
  <span m=''3675940''>the</span> <span m=''3676020''>procedures</span> <span m=''3677900''>where</span>
  <span m=''3678020''>the</span> <span m=''3678160''>application''s</span> <span m=''3678790''>going</span>
  <span m=''3678880''>to</span> <span m=''3678920''>happen.</span> <span m=''3680160''>All</span>
  <span m=''3680590''>right,</span> <span m=''3681020''>similarly,</span> <span m=''3681590''>when</span>
  <span m=''3681720''>you''re</span> <span m=''3681840''>going</span> <span m=''3682100''>along</span>
  <span m=''3682530''>evaluating</span> <span m=''3683120''>an</span> <span m=''3683300''>argument</span>
  <span m=''3683530''>list,</span> <span m=''3683710''>when</span> <span m=''3683820''>you''ve</span>
  <span m=''3683930''>finished</span> <span m=''3684270''>evaluating</span> <span
  m=''3684870''>the</span> <span m=''3684950''>list,</span> <span m=''3685910''>when</span>
  <span m=''3686090''>you''re</span> <span m=''3686280''>finished</span> <span m=''3686620''>evaluating</span>
  <span m=''3687130''>the</span> <span m=''3687200''>last</span> <span m=''3687450''>argument,</span>
  <span m=''3688200''>you</span> <span m=''3688340''>don''t</span> <span m=''3688550''>need</span>
  <span m=''3689200''>that</span> <span m=''3689350''>argument</span> <span m=''3689680''>list</span>
  <span m=''3689900''>any</span> <span m=''3690040''>more,</span> <span m=''3691060''>right?</span>
  <span m=''3691500''>And</span> <span m=''3691630''>you</span> <span m=''3691750''>don''t</span>
  <span m=''3691900''>need</span> <span m=''3691990''>the</span> <span m=''3692080''>environment</span>
  <span m=''3692660''>where</span> <span m=''3693080''>those</span> <span m=''3693330''>arguments</span>
  <span m=''3693760''>would</span> <span m=''3693910''>be</span> <span m=''3694060''>evaluated,</span>
  <span m=''3696215''>OK?</span> <span m=''3696690''>So</span> <span m=''3696880''>the</span>
  <span m=''3696980''>basic</span> <span m=''3697400''>reason</span> <span m=''3698150''>that</span>
  <span m=''3698940''>this</span> <span m=''3699320''>interpreter</span> <span m=''3699890''>is</span>
  <span m=''3699990''>being</span> <span m=''3700240''>so</span> <span m=''3700430''>smart</span>
  <span m=''3700890''>is</span> <span m=''3701010''>that</span> <span m=''3701120''>it''s</span>
  <span m=''3701250''>not</span> <span m=''3701420''>being</span> <span m=''3701610''>smart</span>
  <span m=''3701950''>at</span> <span m=''3702170''>all,</span> <span m=''3702390''>it''s</span>
  <span m=''3702500''>being</span> <span m=''3702610''>stupid.</span> <span m=''3703050''>It''s</span>
  <span m=''3703210''>just</span> <span m=''3703360''>saying</span> <span m=''3703570''>I''m</span>
  <span m=''3703710''>only</span> <span m=''3703990''>going</span> <span m=''3704160''>to</span>
  <span m=''3704200''>save</span> <span m=''3704760''>what</span> <span m=''3704990''>I</span>
  <span m=''3705050''>really</span> <span m=''3705380''>need.</span> </p><p><span
  m=''3708700''>Well,</span> <span m=''3709120''>let</span> <span m=''3710240''>me</span>
  <span m=''3710360''>show</span> <span m=''3710510''>you</span> <span m=''3710670''>here.</span>
  <span m=''3714880''>Here''s</span> <span m=''3715070''>the</span> <span m=''3715210''>actual</span>
  <span m=''3715660''>thing</span> <span m=''3715860''>that''s</span> <span m=''3716030''>making</span>
  <span m=''3716330''>a</span> <span m=''3716370''>tail</span> <span m=''3716610''>recursive.</span>
  <span m=''3718310''>Remember,</span> <span m=''3718910''>it''s</span> <span m=''3719140''>the</span>
  <span m=''3719220''>restore</span> <span m=''3719730''>of</span> <span m=''3719810''>continue.</span>
  <span m=''3720135''>It''s</span> <span m=''3720460''>saying</span> <span m=''3720940''>when</span>
  <span m=''3721480''>I</span> <span m=''3723530''>go</span> <span m=''3723770''>off</span>
  <span m=''3724050''>to</span> <span m=''3724370''>evaluate</span> <span m=''3725680''>the</span>
  <span m=''3725880''>procedure</span> <span m=''3726380''>body,</span> <span m=''3728990''>I</span>
  <span m=''3729090''>should</span> <span m=''3729260''>tell</span> <span m=''3729630''>eval</span>
  <span m=''3729740''>to</span> <span m=''3729880''>come</span> <span m=''3730250''>back</span>
  <span m=''3730640''>to</span> <span m=''3731410''>the</span> <span m=''3731510''>place</span>
  <span m=''3731830''>where</span> <span m=''3731930''>that</span> <span m=''3732090''>original</span>
  <span m=''3732500''>evaluation</span> <span m=''3733120''>was</span> <span m=''3733250''>supposed</span>
  <span m=''3733510''>to</span> <span m=''3733590''>come</span> <span m=''3733740''>back</span>
  <span m=''3733860''>to.</span> <span m=''3735170''>So,</span> <span m=''3735400''>in</span>
  <span m=''3735470''>some</span> <span m=''3735670''>sense,</span> <span m=''3736220''>you</span>
  <span m=''3736330''>want</span> <span m=''3736430''>to</span> <span m=''3736470''>say</span>
  <span m=''3736580''>what''s</span> <span m=''3736810''>the</span> <span m=''3736960''>actual</span>
  <span m=''3737410''>line</span> <span m=''3737700''>that</span> <span m=''3737820''>makes</span>
  <span m=''3738050''>a</span> <span m=''3738090''>tail</span> <span m=''3738310''>recursive?</span>
  <span m=''3738770''>It''s</span> <span m=''3738920''>that</span> <span m=''3739155''>one.</span>
  </p><p><span m=''3739920''>If</span> <span m=''3740070''>I</span> <span m=''3740120''>wanted</span>
  <span m=''3740390''>to</span> <span m=''3740490''>build</span> <span m=''3740790''>a</span>
  <span m=''3740950''>non-tail</span> <span m=''3742030''>recursive</span> <span m=''3743020''>evaluator,</span>
  <span m=''3743680''>for</span> <span m=''3743820''>some</span> <span m=''3744010''>strange</span>
  <span m=''3744320''>reason,</span> <span m=''3745720''>all</span> <span m=''3746020''>I</span>
  <span m=''3746070''>would</span> <span m=''3746120''>need</span> <span m=''3746360''>to</span>
  <span m=''3746460''>do</span> <span m=''3747060''>is,</span> <span m=''3747370''>instead</span>
  <span m=''3747650''>of</span> <span m=''3747730''>restoring</span> <span m=''3748170''>continue</span>
  <span m=''3748610''>at</span> <span m=''3748690''>this</span> <span m=''3748890''>point,</span>
  <span m=''3750100''>I''d</span> <span m=''3750200''>set</span> <span m=''3750410''>up</span>
  <span m=''3750500''>a</span> <span m=''3750570''>label</span> <span m=''3751090''>down</span>
  <span m=''3751300''>here</span> <span m=''3752900''>called,</span> <span m=''3753790''>"Where</span>
  <span m=''3753990''>to</span> <span m=''3754070''>come</span> <span m=''3754270''>back</span>
  <span m=''3754590''>after</span> <span m=''3754850''>you''ve</span> <span m=''3755010''>finished</span>
  <span m=''3755340''>applying</span> <span m=''3755690''>the</span> <span m=''3755760''>procedure."</span>
  <span m=''3758200''>Instead,</span> <span m=''3758380''>I''d</span> <span m=''3758560''>set</span>
  <span m=''3758790''>continue</span> <span m=''3759220''>to</span> <span m=''3759350''>that.</span>
  <span m=''3759920''>I''d</span> <span m=''3760040''>go</span> <span m=''3760170''>to</span>
  <span m=''3760630''>eval-dispatch,</span> <span m=''3761460''>and</span> <span m=''3761560''>then</span>
  <span m=''3761720''>eval-dispatch</span> <span m=''3762240''>would</span> <span
  m=''3762400''>come</span> <span m=''3762560''>back</span> <span m=''3762790''>here.</span>
  <span m=''3763790''>At</span> <span m=''3763910''>that</span> <span m=''3764120''>point,</span>
  <span m=''3764340''>I</span> <span m=''3764410''>would</span> <span m=''3764560''>restore</span>
  <span m=''3764920''>continue</span> <span m=''3765195''>and</span> <span m=''3765470''>go</span>
  <span m=''3765650''>to</span> <span m=''3765780''>the</span> <span m=''3765920''>original</span>
  <span m=''3766280''>one.</span> <span m=''3767920''>So</span> <span m=''3768090''>here,</span>
  <span m=''3769550''>the</span> <span m=''3769750''>only</span> <span m=''3769940''>consequence</span>
  <span m=''3770540''>of</span> <span m=''3770610''>that</span> <span m=''3771210''>would</span>
  <span m=''3771330''>be</span> <span m=''3771440''>to</span> <span m=''3771510''>make</span>
  <span m=''3771690''>it</span> <span m=''3771790''>non-tail</span> <span m=''3772220''>recursive.</span>
  <span m=''3772840''>It</span> <span m=''3772890''>would</span> <span m=''3772940''>give</span>
  <span m=''3772990''>you</span> <span m=''3773240''>exactly</span> <span m=''3773710''>the</span>
  <span m=''3773790''>same</span> <span m=''3774050''>answers,</span> <span m=''3774800''>except,</span>
  <span m=''3775130''>if</span> <span m=''3775210''>you</span> <span m=''3775340''>did</span>
  <span m=''3775560''>that</span> <span m=''3776030''>iterative</span> <span m=''3776400''>factorial</span>
  <span m=''3777010''>and</span> <span m=''3777090''>all</span> <span m=''3777250''>those</span>
  <span m=''3777420''>iterative</span> <span m=''3777800''>procedures,</span> <span
  m=''3778390''>it</span> <span m=''3778600''>would</span> <span m=''3778800''>execute</span>
  <span m=''3779200''>recursively.</span> </p><p><span m=''3783080''>Well,</span>
  <span m=''3783260''>I</span> <span m=''3783340''>lied</span> <span m=''3783460''>to</span>
  <span m=''3783580''>you</span> <span m=''3783700''>a</span> <span m=''3783750''>little</span>
  <span m=''3784070''>bit,</span> <span m=''3784540''>but</span> <span m=''3784670''>just</span>
  <span m=''3784840''>a</span> <span m=''3784890''>little</span> <span m=''3785110''>bit,</span>
  <span m=''3785760''>because</span> <span m=''3785930''>I</span> <span m=''3785990''>showed</span>
  <span m=''3786240''>you</span> <span m=''3786340''>a</span> <span m=''3786390''>slightly</span>
  <span m=''3786880''>over-simplified</span> <span m=''3787670''>evaluator</span>
  <span m=''3788790''>where</span> <span m=''3789010''>it</span> <span m=''3789050''>assumes</span>
  <span m=''3789430''>that</span> <span m=''3791440''>each</span> <span m=''3791640''>procedure</span>
  <span m=''3792030''>body</span> <span m=''3792330''>has</span> <span m=''3792510''>only</span>
  <span m=''3792710''>one</span> <span m=''3792950''>expression.</span> <span m=''3793890''>Remember,</span>
  <span m=''3794130''>in</span> <span m=''3794200''>general,</span> <span m=''3794550''>a</span>
  <span m=''3794600''>procedure</span> <span m=''3795020''>has</span> <span m=''3795170''>a</span>
  <span m=''3795220''>sequence</span> <span m=''3795680''>of</span> <span m=''3795790''>expressions</span>
  <span m=''3796055''>in</span> <span m=''3796187''>it.</span> <span m=''3797870''>So</span>
  <span m=''3798840''>there''s</span> <span m=''3799030''>nothing</span> <span m=''3799280''>really</span>
  <span m=''3799820''>conceptually</span> <span m=''3800155''>new.</span> <span m=''3800490''>Let</span>
  <span m=''3800580''>me</span> <span m=''3800670''>just</span> <span m=''3800810''>show</span>
  <span m=''3800940''>you</span> <span m=''3801090''>the</span> <span m=''3801250''>actual</span>
  <span m=''3801670''>evaluator</span> <span m=''3802950''>that</span> <span m=''3803100''>handles</span>
  <span m=''3803480''>sequences</span> <span m=''3804050''>of</span> <span m=''3804140''>expressions.</span>
  </p><p><span m=''3808470''>This</span> <span m=''3808610''>is</span> <span m=''3808720''>compound-apply</span>
  <span m=''3809490''>now,</span> <span m=''3809700''>and</span> <span m=''3809780''>the</span>
  <span m=''3809870''>only</span> <span m=''3810170''>difference</span> <span m=''3810520''>from</span>
  <span m=''3810650''>the</span> <span m=''3810750''>old</span> <span m=''3810990''>one</span>
  <span m=''3812200''>is</span> <span m=''3812350''>that,</span> <span m=''3812490''>instead</span>
  <span m=''3812790''>of</span> <span m=''3812870''>going</span> <span m=''3813270''>off</span>
  <span m=''3813325''>to</span> <span m=''3813490''>eval</span> <span m=''3813740''>directly,</span>
  <span m=''3815980''>it</span> <span m=''3816210''>takes</span> <span m=''3816760''>the</span>
  <span m=''3816890''>whole</span> <span m=''3817080''>body</span> <span m=''3817440''>of</span>
  <span m=''3817510''>the</span> <span m=''3817600''>procedure,</span> <span m=''3818090''>which,</span>
  <span m=''3818280''>in</span> <span m=''3818400''>this</span> <span m=''3818510''>case,</span>
  <span m=''3818790''>is</span> <span m=''3818900''>a</span> <span m=''3818940''>sequence</span>
  <span m=''3819390''>of</span> <span m=''3819480''>expressions,</span> <span m=''3820270''>and</span>
  <span m=''3820420''>goes</span> <span m=''3820630''>off</span> <span m=''3820760''>to</span>
  <span m=''3820920''>eval-sequence.</span> <span m=''3822670''>And</span> <span m=''3822865''>eval-sequence</span>
  <span m=''3824560''>is</span> <span m=''3824710''>a</span> <span m=''3824760''>little</span>
  <span m=''3825020''>loop</span> <span m=''3826585''>that,</span> <span m=''3827020''>basically,</span>
  <span m=''3828100''>does</span> <span m=''3828380''>these</span> <span m=''3828590''>evaluations</span>
  <span m=''3829260''>one</span> <span m=''3829440''>at</span> <span m=''3829510''>a</span>
  <span m=''3829580''>time.</span> <span m=''3832630''>So</span> <span m=''3832810''>it</span>
  <span m=''3832870''>does</span> <span m=''3833110''>an</span> <span m=''3833140''>evaluation.</span>
  <span m=''3833900''>Says</span> <span m=''3834150''>oh,</span> <span m=''3834310''>when</span>
  <span m=''3834410''>I</span> <span m=''3834460''>come</span> <span m=''3834710''>back,</span>
  <span m=''3835070''>I''d</span> <span m=''3835130''>better</span> <span m=''3835350''>come</span>
  <span m=''3835520''>back</span> <span m=''3835760''>here</span> <span m=''3835910''>to</span>
  <span m=''3835960''>do</span> <span m=''3836110''>the</span> <span m=''3836310''>next</span>
  <span m=''3836510''>one.</span> <span m=''3838440''>And,</span> <span m=''3838650''>when</span>
  <span m=''3838780''>I''m</span> <span m=''3838930''>all</span> <span m=''3839110''>done,</span>
  <span m=''3839280''>when</span> <span m=''3839410''>I</span> <span m=''3839490''>want</span>
  <span m=''3839650''>to</span> <span m=''3839830''>get</span> <span m=''3840010''>the</span>
  <span m=''3840090''>last</span> <span m=''3840410''>expression,</span> <span m=''3841310''>I</span>
  <span m=''3841460''>just</span> <span m=''3842100''>restore</span> <span m=''3842540''>my</span>
  <span m=''3842680''>continue</span> <span m=''3843940''>and</span> <span m=''3844120''>go</span>
  <span m=''3844300''>off</span> <span m=''3844410''>to</span> <span m=''3844800''>eval-dispatch.</span>
  </p><p><span m=''3846410''>And,</span> <span m=''3846550''>again,</span> <span m=''3847020''>if</span>
  <span m=''3847150''>you</span> <span m=''3847270''>wanted</span> <span m=''3847540''>for</span>
  <span m=''3847670''>some</span> <span m=''3847900''>reason</span> <span m=''3848200''>to</span>
  <span m=''3848290''>break</span> <span m=''3848620''>tail</span> <span m=''3848880''>recursion</span>
  <span m=''3849380''>in</span> <span m=''3849480''>this</span> <span m=''3849630''>evaluator,</span>
  <span m=''3850510''>all</span> <span m=''3850810''>you</span> <span m=''3850910''>need</span>
  <span m=''3851060''>to</span> <span m=''3851140''>do</span> <span m=''3851310''>is</span>
  <span m=''3851440''>not</span> <span m=''3851690''>handle</span> <span m=''3852020''>the</span>
  <span m=''3852100''>last</span> <span m=''3852420''>expression,</span> <span m=''3853160''>especially.</span>
  <span m=''3854900''>Just</span> <span m=''3855090''>say,</span> <span m=''3856160''>after</span>
  <span m=''3856400''>you''ve</span> <span m=''3856520''>done</span> <span m=''3856660''>the</span>
  <span m=''3856750''>last</span> <span m=''3857040''>expression,</span> <span m=''3857430''>come</span>
  <span m=''3857600''>back</span> <span m=''3857820''>to</span> <span m=''3857910''>some</span>
  <span m=''3858110''>other</span> <span m=''3858290''>place</span> <span m=''3859300''>after</span>
  <span m=''3859500''>which</span> <span m=''3859700''>you</span> <span m=''3859780''>restore</span>
  <span m=''3860130''>continue.</span> <span m=''3861900''>And,</span> <span m=''3862580''>for</span>
  <span m=''3862740''>some</span> <span m=''3863000''>reason,</span> <span m=''3863360''>a</span>
  <span m=''3863450''>lot</span> <span m=''3863670''>of</span> <span m=''3863750''>LISP</span>
  <span m=''3863970''>evaluators</span> <span m=''3864610''>tended</span> <span m=''3864920''>to</span>
  <span m=''3865020''>work</span> <span m=''3865250''>that</span> <span m=''3865460''>way.</span>
  <span m=''3866550''>And</span> <span m=''3866700''>the</span> <span m=''3866880''>only</span>
  <span m=''3867050''>consequence</span> <span m=''3867620''>of</span> <span m=''3867710''>that</span>
  <span m=''3867960''>is</span> <span m=''3868100''>that</span> <span m=''3868890''>iterative</span>
  <span m=''3869300''>procedures</span> <span m=''3869920''>built</span> <span m=''3870160''>up</span>
  <span m=''3870280''>stack.</span> <span m=''3871614''>And</span> <span m=''3872046''>it''s</span>
  <span m=''3872480''>not</span> <span m=''3872670''>clear</span> <span m=''3872870''>why</span>
  <span m=''3873000''>that</span> <span m=''3873150''>happened.</span> </p><p><span
  m=''3875670''>All</span> <span m=''3875885''>right.</span> <span m=''3876210''>Well,</span>
  <span m=''3876890''>let</span> <span m=''3876990''>me</span> <span m=''3877080''>just</span>
  <span m=''3877220''>sort</span> <span m=''3877360''>of</span> <span m=''3877420''>summarize,</span>
  <span m=''3878420''>since</span> <span m=''3878515''>this</span> <span m=''3878610''>is</span>
  <span m=''3878720''>a</span> <span m=''3878770''>lot</span> <span m=''3878990''>of</span>
  <span m=''3879070''>details</span> <span m=''3880180''>in</span> <span m=''3880215''>a</span>
  <span m=''3880250''>big</span> <span m=''3880380''>program.</span> <span m=''3881120''>But</span>
  <span m=''3881310''>the</span> <span m=''3881390''>main</span> <span m=''3881610''>point</span>
  <span m=''3881890''>is</span> <span m=''3882000''>that</span> <span m=''3883080''>it''s</span>
  <span m=''3883280''>no</span> <span m=''3883420''>different,</span> <span m=''3884040''>conceptually,</span>
  <span m=''3884680''>from</span> <span m=''3884830''>translating</span> <span m=''3885390''>any</span>
  <span m=''3885570''>other</span> <span m=''3885730''>program.</span> <span m=''3887060''>And</span>
  <span m=''3887090''>the</span> <span m=''3887120''>main</span> <span m=''3887420''>idea</span>
  <span m=''3887740''>is</span> <span m=''3887860''>that</span> <span m=''3887970''>we</span>
  <span m=''3888060''>have</span> <span m=''3888190''>this</span> <span m=''3888280''>universal</span>
  <span m=''3889210''>evaluator</span> <span m=''3889760''>program,</span> <span m=''3890370''>the</span>
  <span m=''3890600''>meta-circular</span> <span m=''3891110''>evaluator.</span> <span
  m=''3891870''>If</span> <span m=''3891980''>we</span> <span m=''3892060''>translate</span>
  <span m=''3892510''>that</span> <span m=''3892680''>into</span> <span m=''3892860''>LISP,</span>
  <span m=''3893190''>then</span> <span m=''3893250''>we</span> <span m=''3893340''>have</span>
  <span m=''3893500''>all</span> <span m=''3893630''>of</span> <span m=''3893760''>LISP.</span>
  <span m=''3894560''>And</span> <span m=''3894655''>that''s</span> <span m=''3894750''>all</span>
  <span m=''3894830''>we</span> <span m=''3894910''>did,</span> <span m=''3896100''>OK?</span>
  </p><p><span m=''3897980''>The</span> <span m=''3898160''>second</span> <span m=''3898340''>point</span>
  <span m=''3898560''>is</span> <span m=''3898680''>that</span> <span m=''3898810''>the</span>
  <span m=''3898890''>magic''s</span> <span m=''3899340''>gone</span> <span m=''3899530''>away.</span>
  <span m=''3899680''>There</span> <span m=''3899770''>should</span> <span m=''3899900''>be</span>
  <span m=''3899990''>no</span> <span m=''3900240''>more</span> <span m=''3900440''>magic</span>
  <span m=''3900880''>in</span> <span m=''3900960''>this</span> <span m=''3901100''>whole</span>
  <span m=''3901260''>system,</span> <span m=''3901670''>right?</span> <span m=''3904820''>In</span>
  <span m=''3904910''>principle,</span> <span m=''3906770''>it</span> <span m=''3906866''>should</span>
  <span m=''3906963''>all</span> <span m=''3907060''>be</span> <span m=''3907190''>very</span>
  <span m=''3907480''>clear</span> <span m=''3907840''>except,</span> <span m=''3908140''>maybe,</span>
  <span m=''3908580''>for</span> <span m=''3908720''>how</span> <span m=''3908910''>list</span>
  <span m=''3909020''>structured</span> <span m=''3909480''>memory</span> <span m=''3909790''>works,</span>
  <span m=''3910810''>and</span> <span m=''3910940''>we''ll</span> <span m=''3911050''>see</span>
  <span m=''3911270''>that</span> <span m=''3911500''>later.</span> <span m=''3912640''>But</span>
  <span m=''3913320''>that''s</span> <span m=''3913540''>not</span> <span m=''3913690''>very</span>
  <span m=''3913880''>hard.</span> </p><p><span m=''3915450''>The</span> <span m=''3915690''>third</span>
  <span m=''3915960''>point</span> <span m=''3916150''>is</span> <span m=''3916240''>that</span>
  <span m=''3916340''>all</span> <span m=''3916480''>this</span> <span m=''3916620''>tail</span>
  <span m=''3916870''>recursion</span> <span m=''3918240''>came</span> <span m=''3918510''>from</span>
  <span m=''3918720''>the</span> <span m=''3918810''>discipline</span> <span m=''3919550''>of</span>
  <span m=''3920500''>eval</span> <span m=''3920840''>being</span> <span m=''3921100''>very</span>
  <span m=''3921380''>careful</span> <span m=''3922550''>to</span> <span m=''3922680''>save</span>
  <span m=''3923100''>only</span> <span m=''3923400''>what</span> <span m=''3923580''>it</span>
  <span m=''3923690''>needs</span> <span m=''3924030''>next</span> <span m=''3924270''>time.</span>
  <span m=''3925870''>It''s</span> <span m=''3926000''>not</span> <span m=''3926160''>some</span>
  <span m=''3926940''>arbitrary</span> <span m=''3927500''>thing</span> <span m=''3927700''>where</span>
  <span m=''3927780''>we''re</span> <span m=''3927860''>saying</span> <span m=''3928060''>well,</span>
  <span m=''3928180''>whenever</span> <span m=''3928530''>we</span> <span m=''3929040''>call</span>
  <span m=''3929310''>a</span> <span m=''3929360''>sub-routine,</span> <span m=''3929920''>we''ll</span>
  <span m=''3930030''>save</span> <span m=''3930310''>all</span> <span m=''3930440''>the</span>
  <span m=''3930510''>registers</span> <span m=''3931020''>in</span> <span m=''3931100''>the</span>
  <span m=''3931180''>world</span> <span m=''3931450''>and</span> <span m=''3931550''>come</span>
  <span m=''3931750''>back,</span> <span m=''3933830''>right?</span> <span m=''3933940''>See,</span>
  <span m=''3934110''>sometimes</span> <span m=''3934620''>it</span> <span m=''3934700''>pays</span>
  <span m=''3935000''>to</span> <span m=''3935110''>really</span> <span m=''3935370''>worry</span>
  <span m=''3935670''>about</span> <span m=''3935920''>efficiency.</span> <span m=''3937150''>And,</span>
  <span m=''3937300''>when</span> <span m=''3937410''>you''re</span> <span m=''3937540''>down</span>
  <span m=''3937930''>in</span> <span m=''3938200''>the</span> <span m=''3938270''>guts</span>
  <span m=''3938600''>of</span> <span m=''3938700''>your</span> <span m=''3938870''>evaluator</span>
  <span m=''3939400''>machine,</span> <span m=''3940610''>it</span> <span m=''3940750''>really</span>
  <span m=''3941020''>pays</span> <span m=''3941290''>to</span> <span m=''3941390''>think</span>
  <span m=''3941590''>about</span> <span m=''3941870''>things</span> <span m=''3942070''>like</span>
  <span m=''3942270''>that</span> <span m=''3942560''>because</span> <span m=''3942750''>it</span>
  <span m=''3942800''>makes</span> <span m=''3943030''>big</span> <span m=''3943160''>consequences.</span>
  </p><p><span m=''3945230''>Well,</span> <span m=''3945800''>I</span> <span m=''3945950''>hope</span>
  <span m=''3946870''>what</span> <span m=''3947020''>this</span> <span m=''3947180''>has</span>
  <span m=''3947310''>done</span> <span m=''3948500''>is</span> <span m=''3948830''>really</span>
  <span m=''3949430''>made</span> <span m=''3949555''>the</span> <span m=''3949680''>evaluator</span>
  <span m=''3951450''>seem</span> <span m=''3951690''>concrete,</span> <span m=''3952125''>right?</span>
  <span m=''3952560''>I</span> <span m=''3952720''>hope</span> <span m=''3952920''>you</span>
  <span m=''3953030''>really</span> <span m=''3953310''>believe</span> <span m=''3954370''>that</span>
  <span m=''3954550''>somebody</span> <span m=''3955640''>could</span> <span m=''3955770''>hold</span>
  <span m=''3955980''>a</span> <span m=''3956740''>LISP</span> <span m=''3957120''>evaluator</span>
  <span m=''3957680''>in</span> <span m=''3957750''>the</span> <span m=''3957820''>palm</span>
  <span m=''3958090''>of</span> <span m=''3958170''>their</span> <span m=''3958240''>hand.</span>
  <span m=''3959390''>Maybe</span> <span m=''3959425''>to</span> <span m=''3959460''>help</span>
  <span m=''3959660''>you</span> <span m=''3959750''>believe</span> <span m=''3960050''>that,</span>
  <span m=''3960800''>here''s</span> <span m=''3961050''>a</span> <span m=''3961185''>LISP</span>
  <span m=''3961320''>evaluator</span> <span m=''3962540''>that</span> <span m=''3962625''>I''m</span>
  <span m=''3962710''>holding</span> <span m=''3963050''>the</span> <span m=''3963140''>palm</span>
  <span m=''3963400''>of</span> <span m=''3963480''>my</span> <span m=''3963630''>hand,</span>
  <span m=''3965304''>right?</span> <span m=''3966160''>And</span> <span m=''3967670''>this</span>
  <span m=''3967840''>is</span> <span m=''3967960''>a</span> <span m=''3968020''>chip</span>
  <span m=''3968860''>which</span> <span m=''3969310''>is</span> <span m=''3969930''>actually</span>
  <span m=''3970900''>quite</span> <span m=''3971180''>a</span> <span m=''3971210''>bit</span>
  <span m=''3971480''>more</span> <span m=''3971750''>complicated</span> <span m=''3972410''>than</span>
  <span m=''3972520''>the</span> <span m=''3972590''>evaluator</span> <span m=''3973210''>I</span>
  <span m=''3973230''>showed</span> <span m=''3973540''>you.</span> <span m=''3977815''>Maybe,</span>
  <span m=''3978210''>here''s</span> <span m=''3978420''>a</span> <span m=''3978460''>better</span>
  <span m=''3978680''>picture</span> <span m=''3978980''>of</span> <span m=''3979110''>it.</span>
  <span m=''3982070''>What</span> <span m=''3982230''>there</span> <span m=''3982430''>is,</span>
  <span m=''3982580''>is</span> <span m=''3982670''>you</span> <span m=''3982770''>can</span>
  <span m=''3982900''>see</span> <span m=''3983050''>the</span> <span m=''3983130''>same</span>
  <span m=''3983540''>overall</span> <span m=''3983920''>structure.</span> <span m=''3984730''>This</span>
  <span m=''3984920''>is</span> <span m=''3985040''>a</span> <span m=''3985110''>register</span>
  <span m=''3985400''>array.</span> <span m=''3986940''>These</span> <span m=''3987030''>are</span>
  <span m=''3987100''>the</span> <span m=''3987170''>data</span> <span m=''3987440''>paths.</span>
  <span m=''3987910''>Here''s</span> <span m=''3987943''>a</span> <span m=''3987960''>finite</span>
  <span m=''3988320''>state</span> <span m=''3988530''>controller.</span> <span m=''3989800''>And</span>
  <span m=''3989910''>again,</span> <span m=''3990110''>finite</span> <span m=''3990700''>state,</span>
  <span m=''3992110''>that''s</span> <span m=''3992320''>all</span> <span m=''3992430''>there</span>
  <span m=''3992620''>is.</span> <span m=''3992810''>And</span> <span m=''3992920''>somewhere</span>
  <span m=''3993190''>there''s</span> <span m=''3993400''>external</span> <span m=''3993800''>memory</span>
  <span m=''3994160''>that''ll</span> <span m=''3994330''>worry</span> <span m=''3994610''>about</span>
  <span m=''3994880''>things.</span> </p><p><span m=''3995750''>And</span> <span m=''3995910''>this</span>
  <span m=''3996040''>particular</span> <span m=''3996510''>one</span> <span m=''3996670''>is</span>
  <span m=''3996790''>very</span> <span m=''3997060''>complicated</span> <span m=''3997670''>because</span>
  <span m=''3997960''>it''s</span> <span m=''3998090''>trying</span> <span m=''3998340''>to</span>
  <span m=''3998410''>run</span> <span m=''3998590''>LISP</span> <span m=''3998800''>fast.</span>
  <span m=''3999800''>And</span> <span m=''3999910''>it</span> <span m=''4000000''>has</span>
  <span m=''4000090''>some</span> <span m=''4000250''>very,</span> <span m=''4000560''>very</span>
  <span m=''4000820''>fast</span> <span m=''4001450''>parallel</span> <span m=''4002080''>operations</span>
  <span m=''4002770''>in</span> <span m=''4002870''>there</span> <span m=''4003130''>like,</span>
  <span m=''4004390''>if</span> <span m=''4004660''>you</span> <span m=''4004780''>want</span>
  <span m=''4004990''>to</span> <span m=''4005180''>index</span> <span m=''4005570''>into</span>
  <span m=''4005780''>an</span> <span m=''4005920''>array,</span> <span m=''4006690''>simultaneously</span>
  <span m=''4009060''>check</span> <span m=''4009300''>that</span> <span m=''4009420''>the</span>
  <span m=''4009540''>index</span> <span m=''4009830''>is</span> <span m=''4009940''>an</span>
  <span m=''4010040''>integer,</span> <span m=''4010380''>check</span> <span m=''4010650''>that</span>
  <span m=''4010790''>it</span> <span m=''4011440''>doesn''t</span> <span m=''4011710''>exceed</span>
  <span m=''4012060''>the</span> <span m=''4012200''>array</span> <span m=''4012430''>bands,</span>
  <span m=''4013020''>and</span> <span m=''4013560''>go</span> <span m=''4013750''>off</span>
  <span m=''4013930''>and</span> <span m=''4014040''>do</span> <span m=''4014130''>the</span>
  <span m=''4014210''>memory</span> <span m=''4014550''>access,</span> <span m=''4015170''>and</span>
  <span m=''4015255''>do</span> <span m=''4015340''>all</span> <span m=''4015460''>those</span>
  <span m=''4015640''>things</span> <span m=''4015810''>simultaneously.</span> <span
  m=''4017120''>And</span> <span m=''4017330''>then,</span> <span m=''4017465''>later,</span>
  <span m=''4017600''>if</span> <span m=''4017680''>they''re</span> <span m=''4017820''>all</span>
  <span m=''4018020''>OK,</span> <span m=''4018280''>actually</span> <span m=''4018970''>get</span>
  <span m=''4019150''>the</span> <span m=''4019220''>value</span> <span m=''4019580''>there.</span>
  <span m=''4020420''>So</span> <span m=''4020560''>there</span> <span m=''4020670''>are</span>
  <span m=''4020690''>a</span> <span m=''4020740''>lot</span> <span m=''4020940''>of</span>
  <span m=''4021010''>complicated</span> <span m=''4021850''>operations</span> <span
  m=''4022450''>in</span> <span m=''4022520''>these</span> <span m=''4022680''>data</span>
  <span m=''4022930''>paths</span> <span m=''4023270''>for</span> <span m=''4023350''>making</span>
  <span m=''4023680''>LISP</span> <span m=''4023830''>run</span> <span m=''4024050''>in</span>
  <span m=''4024140''>parallel.</span> <span m=''4026550''>It''s</span> <span m=''4026710''>a</span>
  <span m=''4026750''>completely</span> <span m=''4027840''>non-risk</span> <span
  m=''4028760''>philosophy</span> <span m=''4029400''>of</span> <span m=''4029480''>evaluating</span>
  <span m=''4030020''>LISP.</span> </p><p><span m=''4030640''>And</span> <span m=''4030800''>then,</span>
  <span m=''4030910''>this</span> <span m=''4031070''>microcode</span> <span m=''4032190''>is</span>
  <span m=''4032400''>pretty</span> <span m=''4032610''>complicated.</span> <span
  m=''4033740''>Let''s</span> <span m=''4033880''>see,</span> <span m=''4036882''>there''s</span>
  <span m=''4037121''>what?</span> <span m=''4037740''>There''s</span> <span m=''4038520''>about</span>
  <span m=''4039070''>389</span> <span m=''4039920''>instructions</span> <span m=''4041740''>of</span>
  <span m=''4041890''>220-bit</span> <span m=''4042780''>microcode</span> <span m=''4043360''>sitting</span>
  <span m=''4043600''>here</span> <span m=''4045970''>because</span> <span m=''4046430''>these</span>
  <span m=''4046580''>are</span> <span m=''4046650''>very</span> <span m=''4046900''>complicated</span>
  <span m=''4047440''>data</span> <span m=''4047670''>paths.</span> <span m=''4047940''>And</span>
  <span m=''4047990''>the</span> <span m=''4048050''>whole</span> <span m=''4048220''>thing</span>
  <span m=''4048370''>has</span> <span m=''4048560''>about</span> <span m=''4048790''>89,000</span>
  <span m=''4049490''>transistors,</span> <span m=''4051595''>OK?</span> <span m=''4053580''>OK.</span>
  <span m=''4053840''>Well,</span> <span m=''4054480''>I</span> <span m=''4054580''>hope</span>
  <span m=''4054760''>that</span> <span m=''4055290''>that</span> <span m=''4055660''>takes</span>
  <span m=''4055980''>away</span> <span m=''4056010''>a</span> <span m=''4056040''>lot</span>
  <span m=''4056230''>of</span> <span m=''4056300''>the</span> <span m=''4056380''>mystery.</span>
  <span m=''4057970''>Maybe</span> <span m=''4058370''>somebody</span> <span m=''4058460''>wants</span>
  <span m=''4058590''>to</span> <span m=''4058690''>look</span> <span m=''4058840''>at</span>
  <span m=''4058900''>this.</span> <span m=''4062048''>Yeah.</span> <span m=''4066260''>OK.</span>
  <span m=''4066480''>Let''s</span> <span m=''4066640''>stop.</span> <span m=''4075890''>Questions?</span>
  </p><p><span m=''4077815''>AUDIENCE:</span> <span m=''4078250''>OK,</span> <span
  m=''4078685''>now,</span> <span m=''4078793''>it</span> <span m=''4078902''>sounds</span>
  <span m=''4079011''>like</span> <span m=''4079120''>what</span> <span m=''4079470''>you''re</span>
  <span m=''4079560''>saying</span> <span m=''4079880''>is</span> <span m=''4080130''>that,</span>
  <span m=''4080630''>with</span> <span m=''4081130''>the</span> <span m=''4081320''>restore</span>
  <span m=''4081585''>continue</span> <span m=''4082280''>put</span> <span m=''4082350''>in</span>
  <span m=''4082420''>the</span> <span m=''4082570''>proper</span> <span m=''4083070''>place,</span>
  <span m=''4083590''>that</span> <span m=''4084550''>procedures</span> <span m=''4085750''>that</span>
  <span m=''4086080''>would</span> <span m=''4086800''>invoke</span> <span m=''4087290''>a</span>
  <span m=''4088200''>recursive</span> <span m=''4088830''>process</span> <span m=''4089490''>now</span>
  <span m=''4089860''>invoke</span> <span m=''4090910''>an</span> <span m=''4091040''>integer</span>
  <span m=''4091380''>process</span> <span m=''4092580''>just</span> <span m=''4092940''>by</span>
  <span m=''4093060''>the</span> <span m=''4093150''>way</span> <span m=''4093310''>that</span>
  <span m=''4093385''>the</span> <span m=''4093460''>eval</span> <span m=''4093930''>signature</span>
  <span m=''4094710''>is?</span> </p><p><span m=''4095165''>PROFESSOR:</span> <span
  m=''4095620''>I</span> <span m=''4095750''>think</span> <span m=''4095960''>the</span>
  <span m=''4096040''>way</span> <span m=''4096220''>I''d</span> <span m=''4096330''>prefer</span>
  <span m=''4096890''>to</span> <span m=''4096970''>put</span> <span m=''4097200''>it</span>
  <span m=''4097330''>is</span> <span m=''4097479''>that,</span> <span m=''4097664''>with</span>
  <span m=''4097850''>restore</span> <span m=''4098189''>continue</span> <span m=''4098600''>put</span>
  <span m=''4098810''>in</span> <span m=''4098870''>the</span> <span m=''4098950''>wrong</span>
  <span m=''4099340''>place,</span> <span m=''4100750''>you</span> <span m=''4100910''>can</span>
  <span m=''4101069''>cause</span> <span m=''4102319''>any</span> <span m=''4102540''>syntactically-looking</span>
  <span m=''4104560''>recursive</span> <span m=''4105020''>procedure,</span> <span
  m=''4105500''>in</span> <span m=''4105609''>fact,</span> <span m=''4105880''>to</span>
  <span m=''4105979''>build</span> <span m=''4106220''>up</span> <span m=''4106319''>stack</span>
  <span m=''4106640''>as</span> <span m=''4106770''>it</span> <span m=''4107100''>runs.</span>
  <span m=''4108029''>But</span> <span m=''4109359''>there''s</span> <span m=''4109600''>no</span>
  <span m=''4109729''>reason</span> <span m=''4110090''>for</span> <span m=''4110200''>that,</span>
  <span m=''4113180''>so</span> <span m=''4113930''>you</span> <span m=''4114040''>might</span>
  <span m=''4114189''>want</span> <span m=''4114310''>to</span> <span m=''4114350''>play</span>
  <span m=''4114529''>around</span> <span m=''4114840''>with</span> <span m=''4114970''>it.</span>
  <span m=''4115660''>You</span> <span m=''4115760''>can</span> <span m=''4115859''>just</span>
  <span m=''4116020''>switch</span> <span m=''4116279''>around</span> <span m=''4116910''>two</span>
  <span m=''4117040''>or</span> <span m=''4117120''>three</span> <span m=''4117310''>instructions</span>
  <span m=''4118430''>in</span> <span m=''4118560''>the</span> <span m=''4118640''>way</span>
  <span m=''4119529''>compound-apply</span> <span m=''4120210''>comes</span> <span
  m=''4120460''>back,</span> <span m=''4121370''>and</span> <span m=''4121490''>you''ll</span>
  <span m=''4121609''>get</span> <span m=''4121779''>something</span> <span m=''4122100''>which</span>
  <span m=''4122260''>isn''t</span> <span m=''4122470''>tail</span> <span m=''4122640''>recursive.</span>
  </p><p><span m=''4125060''>But</span> <span m=''4125210''>the</span> <span m=''4125290''>thing</span>
  <span m=''4125439''>I</span> <span m=''4125470''>wanted</span> <span m=''4125670''>to</span>
  <span m=''4125720''>emphasize</span> <span m=''4126160''>is</span> <span m=''4126279''>there''s</span>
  <span m=''4126450''>no</span> <span m=''4126580''>magic.</span> <span m=''4127670''>It''s</span>
  <span m=''4127880''>not</span> <span m=''4128160''>as</span> <span m=''4128420''>if</span>
  <span m=''4129340''>there''s</span> <span m=''4129529''>some</span> <span m=''4129779''>very</span>
  <span m=''4130160''>clever</span> <span m=''4130899''>pre-processing</span> <span
  m=''4131689''>program</span> <span m=''4132689''>that''s</span> <span m=''4132899''>looking</span>
  <span m=''4133310''>at</span> <span m=''4133439''>this</span> <span m=''4133630''>procedure,</span>
  <span m=''4134580''>factorial</span> <span m=''4135130''>iter,</span> <span m=''4135410''>and</span>
  <span m=''4135540''>say</span> <span m=''4135740''>oh,</span> <span m=''4136050''>gee,</span>
  <span m=''4137600''>I</span> <span m=''4137729''>really</span> <span m=''4138080''>notice</span>
  <span m=''4138550''>that</span> <span m=''4138760''>I</span> <span m=''4138859''>don''t</span>
  <span m=''4139120''>have</span> <span m=''4139319''>to</span> <span m=''4139439''>push</span>
  <span m=''4139920''>stack</span> <span m=''4140410''>in</span> <span m=''4140540''>order</span>
  <span m=''4140729''>to</span> <span m=''4140830''>do</span> <span m=''4140960''>this.</span>
  <span m=''4141060''>Some</span> <span m=''4141229''>people</span> <span m=''4141500''>think</span>
  <span m=''4141729''>that</span> <span m=''4141850''>that''s</span> <span m=''4142069''>what''s</span>
  <span m=''4142260''>going</span> <span m=''4142529''>on.</span> <span m=''4143760''>It''s</span>
  <span m=''4143930''>something</span> <span m=''4144100''>much,</span> <span m=''4144350''>much</span>
  <span m=''4144590''>more</span> <span m=''4144750''>dumb</span> <span m=''4144990''>than</span>
  <span m=''4145140''>that,</span> <span m=''4145439''>it''s</span> <span m=''4145524''>this</span>
  <span m=''4145609''>one</span> <span m=''4145840''>place</span> <span m=''4146130''>you''re</span>
  <span m=''4146229''>putting</span> <span m=''4146470''>the</span> <span m=''4146540''>restore</span>
  <span m=''4146939''>instruction.</span> <span m=''4148880''>It''s</span> <span m=''4149149''>just</span>
  <span m=''4149330''>automatic.</span> </p><p><span m=''4150353''>AUDIENCE:</span>
  <span m=''4150836''>OK.</span> </p><p><span m=''4154217''>AUDIENCE:</span> <span
  m=''4154700''>But</span> <span m=''4154859''>that''s</span> <span m=''4155120''>not</span>
  <span m=''4155300''>affecting</span> <span m=''4155689''>the</span> <span m=''4155770''>time</span>
  <span m=''4156109''>complexity</span> <span m=''4157450''>is</span> <span m=''4157609''>it?</span>
  </p><p><span m=''4157850''>PROFESSOR: No.</span> </p><p><span m=''4158275''>AUDIENCE:</span>
  <span m=''4158700''>It''s</span> <span m=''4158920''>just</span> <span m=''4159630''>that</span>
  <span m=''4159910''>it''s</span> <span m=''4160090''>handling</span> <span m=''4160640''>it</span>
  <span m=''4160990''>recursively</span> <span m=''4161810''>instead</span> <span
  m=''4162140''>of</span> <span m=''4162200''>iteratively.</span> <span m=''4163020''>But,</span>
  <span m=''4163609''>in</span> <span m=''4163689''>terms</span> <span m=''4164060''>of</span>
  <span m=''4164279''>the</span> <span m=''4164960''>order</span> <span m=''4165319''>of</span>
  <span m=''4165399''>time</span> <span m=''4165700''>it</span> <span m=''4165800''>takes</span>
  <span m=''4166109''>to</span> <span m=''4166500''>finish</span> <span m=''4166850''>the</span>
  <span m=''4166960''>operation,</span> <span m=''4167740''>it''s</span> <span m=''4167775''>the</span>
  <span m=''4167810''>same</span> <span m=''4168130''>one</span> <span m=''4168279''>way</span>
  <span m=''4168430''>or</span> <span m=''4168470''>the</span> <span m=''4168710''>other,</span>
  <span m=''4168960''>right?</span> </p><p><span m=''4169220''>PROFESSOR:</span> <span
  m=''4169720''>Yes.</span> <span m=''4169920''>Tail</span> <span m=''4170130''>recursion</span>
  <span m=''4170340''>is</span> <span m=''4170430''>not</span> <span m=''4170620''>going</span>
  <span m=''4170710''>to</span> <span m=''4170779''>change</span> <span m=''4171270''>the</span>
  <span m=''4171450''>time</span> <span m=''4171779''>complexity</span> <span m=''4172319''>of</span>
  <span m=''4172609''>anything</span> <span m=''4172740''>because,</span> <span m=''4172870''>in</span>
  <span m=''4172960''>some</span> <span m=''4173120''>sense,</span> <span m=''4173340''>it''s</span>
  <span m=''4173500''>the</span> <span m=''4173569''>same</span> <span m=''4173880''>algorithm</span>
  <span m=''4174420''>that''s</span> <span m=''4174620''>going</span> <span m=''4174890''>on.</span>
  <span m=''4176029''>What</span> <span m=''4176160''>it''s</span> <span m=''4176340''>doing</span>
  <span m=''4177359''>is</span> <span m=''4177500''>really</span> <span m=''4177790''>making</span>
  <span m=''4178109''>this</span> <span m=''4178279''>thing</span> <span m=''4178410''>run</span>
  <span m=''4178609''>as</span> <span m=''4178720''>an</span> <span m=''4178790''>iteration,</span>
  <span m=''4180615''>right?</span> <span m=''4181210''>Not</span> <span m=''4181590''>going</span>
  <span m=''4181819''>to</span> <span m=''4181870''>run</span> <span m=''4182050''>out</span>
  <span m=''4182149''>of</span> <span m=''4182250''>memory</span> <span m=''4182939''>counting</span>
  <span m=''4183330''>up</span> <span m=''4183430''>to</span> <span m=''4183550''>a</span>
  <span m=''4183609''>giant</span> <span m=''4183939''>number</span> <span m=''4184750''>simply</span>
  <span m=''4185060''>because</span> <span m=''4185380''>the</span> <span m=''4185450''>stack</span>
  <span m=''4185790''>would</span> <span m=''4185910''>get</span> <span m=''4186069''>pushed.</span>
  </p><p><span m=''4187683''>See,</span> <span m=''4188590''>the</span> <span m=''4188680''>thing</span>
  <span m=''4188760''>you</span> <span m=''4188870''>really</span> <span m=''4189080''>have</span>
  <span m=''4189260''>to</span> <span m=''4189350''>believe</span> <span m=''4189830''>is</span>
  <span m=''4189970''>that,</span> <span m=''4190510''>when</span> <span m=''4190710''>we</span>
  <span m=''4190830''>write--</span> <span m=''4191640''>see,</span> <span m=''4191779''>we''ve</span>
  <span m=''4191910''>been</span> <span m=''4192040''>writing</span> <span m=''4192380''>all</span>
  <span m=''4192529''>these</span> <span m=''4192700''>things</span> <span m=''4192890''>called</span>
  <span m=''4193040''>iterations,</span> <span m=''4194040''>infinite</span> <span
  m=''4194540''>loops,</span> <span m=''4196420''>define</span> <span m=''4196720''>loop</span>
  <span m=''4197030''>to</span> <span m=''4197140''>be</span> <span m=''4197320''>called</span>
  <span m=''4197630''>loop.</span> <span m=''4201660''>That''s</span> <span m=''4201840''>is</span>
  <span m=''4202080''>as</span> <span m=''4202420''>much</span> <span m=''4202575''>an</span>
  <span m=''4202730''>iteration</span> <span m=''4203940''>as</span> <span m=''4204070''>if</span>
  <span m=''4204180''>we</span> <span m=''4204290''>wrote</span> <span m=''4204730''>do</span>
  <span m=''4204920''>forever</span> <span m=''4205390''>loop,</span> <span m=''4207156''>right?</span>
  <span m=''4207630''>It''s</span> <span m=''4207740''>just</span> <span m=''4207890''>syntactic</span>
  <span m=''4208430''>sugar</span> <span m=''4208760''>as</span> <span m=''4208860''>the</span>
  <span m=''4208940''>difference.</span> <span m=''4209280''>These</span> <span m=''4209420''>things</span>
  <span m=''4209600''>are</span> <span m=''4209690''>real,</span> <span m=''4210000''>honest</span>
  <span m=''4210205''>to</span> <span m=''4210410''>god,</span> <span m=''4210740''>iterations,</span>
  <span m=''4214242''>right?</span> <span m=''4214730''>They</span> <span m=''4214840''>don''t</span>
  <span m=''4215000''>change</span> <span m=''4215240''>the</span> <span m=''4215300''>time</span>
  <span m=''4215540''>complexity,</span> <span m=''4216060''>but</span> <span m=''4216780''>they</span>
  <span m=''4216900''>turn</span> <span m=''4217160''>them</span> <span m=''4217285''>into</span>
  <span m=''4217410''>real</span> <span m=''4217690''>iterations.</span> <span m=''4221686''>All</span>
  <span m=''4222190''>right,</span> <span m=''4222310''>thank</span> <span m=''4222550''>you.</span>
  </p>'
type: course
uid: a319abbcf6a2fe7c484dfd8f46d49886

---
None