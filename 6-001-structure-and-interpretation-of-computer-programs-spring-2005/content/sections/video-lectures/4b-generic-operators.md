---
about_this_resource_text: '<p><b>Topics covered</b>: Generic Operators</p> <p><b>
  Instructors:</b> Hal Abelson and Gerald Jay Sussman</p> <p>Subtitles for this course
  are provided through the generous assistance of Henry Baker, Hoofar Pourzand, Heather
  Wood, Aleksejs Truhans, Steven Edwards, George Menhorn, and Mahendra Kumar.</p>'
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
embedded_media:
- id: 4B.jpg
  parent_uid: 088abd6ab74fc074cee8818d4f3dcf27
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/4b-generic-operators/4B.jpg
  title: 4B.jpg
  type: null
  uid: 6afe095f9d5a909d30430338efddb391
- id: Video-YouTube-Stream
  media_location: OscT4N2qq7o
  parent_uid: 088abd6ab74fc074cee8818d4f3dcf27
  title: Video-YouTube-Stream
  type: Video
  uid: fb760545ecacaf929b20adfd534e67fb
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT_Structure_of_Computer_Programs_1986/lec4b.mp4
  parent_uid: 088abd6ab74fc074cee8818d4f3dcf27
  title: Video-Internet Archive-MP4
  type: Video
  uid: be935cdbaf6262728b9a87c7f7efa0db
- id: Thumbnail-OCW-JPG
  parent_uid: 088abd6ab74fc074cee8818d4f3dcf27
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 9bb66dc8ea2d5f2f20d7ca843bd11ff3
- id: 3Play-3PlayYouTubeid-MP4
  media_location: OscT4N2qq7o
  parent_uid: 088abd6ab74fc074cee8818d4f3dcf27
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 9d189047f4deba288c3f57bc96d80591
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/OscT4N2qq7o/default.jpg
  parent_uid: 088abd6ab74fc074cee8818d4f3dcf27
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: d7fd6352a0679a70f6725fcfa6fc39f5
- id: OscT4N2qq7o.srt
  parent_uid: 088abd6ab74fc074cee8818d4f3dcf27
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/4b-generic-operators/OscT4N2qq7o.srt
  title: 3play caption file
  type: null
  uid: af067b4fe724af6baca4c8800be50711
- id: OscT4N2qq7o.pdf
  parent_uid: 088abd6ab74fc074cee8818d4f3dcf27
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/4b-generic-operators/OscT4N2qq7o.pdf
  title: 3play pdf file
  type: null
  uid: b31a4b69d5162b24879fa9318c2ef884
- id: Caption-3Play YouTube id-SRT
  parent_uid: 088abd6ab74fc074cee8818d4f3dcf27
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: ab9ca84d7fec79fdcd5871ab68ae8168
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 088abd6ab74fc074cee8818d4f3dcf27
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: e38a7ff1002b6fdba6a47c4e3b35a747
inline_embed_id: 371336644b:genericoperators58823955
layout: video
order_index: null
parent_uid: 4fcacad2c29981dd668a6b29822403cc
related_resources_text: ''
short_url: 4b-generic-operators
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/4b-generic-operators
template_type: Tabbed
title: '4B: Generic Operators'
transcript: '<p><span m=''3936''>[MUSIC-- "JESU, JOY OF MAN''S DESIRING" BY JOHANN
  SEBASTIAN BACH]</span> </p><p><span m=''20180''>PROFESSOR: So</span> <span m=''20440''>far</span>
  <span m=''20700''>in</span> <span m=''20820''>this</span> <span m=''20940''>course</span>
  <span m=''21190''>we''ve</span> <span m=''21310''>been</span> <span m=''21440''>talking</span>
  <span m=''21780''>a</span> <span m=''21840''>lot</span> <span m=''22070''>about</span>
  <span m=''22360''>data</span> <span m=''22600''>abstraction.</span> <span m=''23780''>And</span>
  <span m=''23910''>remember</span> <span m=''24210''>the</span> <span m=''24360''>idea</span>
  <span m=''25190''>is</span> <span m=''25370''>that</span> <span m=''25610''>we</span>
  <span m=''25730''>build</span> <span m=''26610''>systems</span> <span m=''27500''>that</span>
  <span m=''27930''>have</span> <span m=''28230''>these</span> <span m=''28910''>horizontal</span>
  <span m=''29500''>barriers</span> <span m=''29810''>in</span> <span m=''30120''>them,</span>
  <span m=''30946''>these</span> <span m=''31360''>abstraction</span> <span m=''31980''>barriers</span>
  <span m=''35370''>that</span> <span m=''35590''>separate</span> <span m=''35980''>use,</span>
  <span m=''37390''>the</span> <span m=''37640''>way</span> <span m=''37770''>you</span>
  <span m=''37870''>might</span> <span m=''38070''>use</span> <span m=''38320''>some</span>
  <span m=''38490''>data</span> <span m=''38780''>object,</span> <span m=''39980''>from</span>
  <span m=''40100''>the</span> <span m=''40220''>way</span> <span m=''40320''>you</span>
  <span m=''40430''>might</span> <span m=''40630''>represent</span> <span m=''40905''>it.</span>
  <span m=''48985''>Or</span> <span m=''49460''>another</span> <span m=''49770''>way</span>
  <span m=''49880''>to</span> <span m=''49970''>think</span> <span m=''50200''>of</span>
  <span m=''50280''>that</span> <span m=''50770''>is</span> <span m=''50990''>up</span>
  <span m=''51180''>here</span> <span m=''51340''>you</span> <span m=''51510''>have</span>
  <span m=''51690''>the</span> <span m=''51760''>boss</span> <span m=''52160''>who''s</span>
  <span m=''52660''>going</span> <span m=''52740''>to</span> <span m=''52830''>be</span>
  <span m=''52920''>using</span> <span m=''54300''>some</span> <span m=''54500''>sort
  of</span> <span m=''54750''>data</span> <span m=''55050''>object.</span> <span m=''57110''>And</span>
  <span m=''57560''>down here is</span> <span m=''57880''>George</span> <span m=''59130''>who''s</span>
  <span m=''59280''>implemented</span> <span m=''59840''>it.</span> <span m=''62310''>Now</span>
  <span m=''62460''>this</span> <span m=''62630''>notion</span> <span m=''63550''>of</span>
  <span m=''63760''>separating</span> <span m=''64379''>use from</span> <span m=''64680''>representation</span>
  <span m=''65519''>so</span> <span m=''65610''>you</span> <span m=''65760''>can</span>
  <span m=''65910''>think</span> <span m=''66180''>about</span> <span m=''67990''>these</span>
  <span m=''68200''>two</span> <span m=''68330''>problems</span> <span m=''69110''>separately</span>
  <span m=''70410''>is a</span> <span m=''70600''>very,</span> <span m=''70930''>very</span>
  <span m=''71140''>powerful</span> <span m=''71540''>programming</span> <span m=''71970''>methodology,</span>
  <span m=''73760''>data</span> <span m=''73970''>abstraction.</span> </p><p><span
  m=''75930''>On</span> <span m=''76080''>the</span> <span m=''76230''>other</span>
  <span m=''76400''>hand,</span> <span m=''76630''>it''s</span> <span m=''76760''>not</span>
  <span m=''77740''>really</span> <span m=''78110''>sufficient</span> <span m=''80220''>for</span>
  <span m=''80770''>really</span> <span m=''81040''>complex</span> <span m=''81500''>systems.</span>
  <span m=''82900''>And</span> <span m=''83140''>the</span> <span m=''83200''>problem</span>
  <span m=''83680''>with</span> <span m=''83840''>this</span> <span m=''86940''>is</span>
  <span m=''87170''>George.</span> <span m=''88640''>Or</span> <span m=''90710''>actually,</span>
  <span m=''91200''>the</span> <span m=''91370''>problem</span> <span m=''91760''>is</span>
  <span m=''91860''>that</span> <span m=''92000''>there</span> <span m=''92110''>are</span>
  <span m=''92150''>a</span> <span m=''92200''>lot</span> <span m=''92410''>of</span>
  <span m=''92510''>Georges.</span> <span m=''94630''>Let''s</span> <span m=''94820''>be</span>
  <span m=''94950''>concrete.</span> <span m=''95390''>Let''s</span> <span m=''95440''>suppose</span>
  <span m=''95830''>there is</span> <span m=''96060''>George,</span> <span m=''97480''>and</span>
  <span m=''98210''>there''s</span> <span m=''98470''>also</span> <span m=''98730''>Martha.</span>
  <span m=''101192''>OK, now</span> <span m=''101690''>George</span> <span m=''101990''>and</span>
  <span m=''102090''>Martha</span> <span m=''103150''>are</span> <span m=''103360''>both</span>
  <span m=''103640''>working</span> <span m=''104010''>on</span> <span m=''104160''>this</span>
  <span m=''104310''>system,</span> <span m=''106040''>both</span> <span m=''106270''>designing</span>
  <span m=''106650''>representations,</span> <span m=''108440''>and</span> <span m=''109250''>absolutely</span>
  <span m=''110030''>are</span> <span m=''110210''>incompatible.</span> <span m=''111750''>They</span>
  <span m=''112100''>wouldn''t</span> <span m=''112660''>cooperate</span> <span m=''113280''>on</span>
  <span m=''113430''>a</span> <span m=''113470''>representation</span> <span m=''114190''>under</span>
  <span m=''114360''>any</span> <span m=''114620''>circumstances.</span> </p><p><span
  m=''117250''>And</span> <span m=''117340''>the</span> <span m=''117440''>problem</span>
  <span m=''117880''>is</span> <span m=''118390''>you</span> <span m=''118510''>would</span>
  <span m=''118630''>like</span> <span m=''118850''>to</span> <span m=''118970''>have</span>
  <span m=''119090''>some</span> <span m=''119270''>system</span> <span m=''119890''>where</span>
  <span m=''120060''>both</span> <span m=''120340''>George</span> <span m=''120620''>and</span>
  <span m=''120720''>Martha</span> <span m=''121300''>are</span> <span m=''121490''>designing</span>
  <span m=''121880''>representations,</span> <span m=''123388''>and</span> <span m=''125380''>yet,</span>
  <span m=''125940''>if</span> <span m=''126130''>you''re</span> <span m=''126480''>above</span>
  <span m=''126990''>this</span> <span m=''127230''>abstraction</span> <span m=''127820''>barrier</span>
  <span m=''129449''>you</span> <span m=''129699''>don''t want to</span> <span m=''129870''>have</span>
  <span m=''130009''>to</span> <span m=''130150''>worry</span> <span m=''130590''>about</span>
  <span m=''130889''>that,</span> <span m=''131720''>whether</span> <span m=''131960''>something</span>
  <span m=''132270''>is</span> <span m=''132360''>done</span> <span m=''132550''>by</span>
  <span m=''132720''>George</span> <span m=''133460''>or</span> <span m=''133660''>by</span>
  <span m=''133820''>Martha.</span> <span m=''134180''>And</span> <span m=''134310''>you</span>
  <span m=''134430''>don''t</span> <span m=''134550''>want</span> <span m=''134750''>George</span>
  <span m=''134990''>and</span> <span m=''135080''>Martha</span> <span m=''135360''>to</span>
  <span m=''135430''>interfere</span> <span m=''135880''>with</span> <span m=''136010''>each</span>
  <span m=''136180''>other.</span> <span m=''136630''>Somehow</span> <span m=''138010''>in</span>
  <span m=''138160''>designing</span> <span m=''138550''>a</span> <span m=''138590''>system,</span>
  <span m=''138940''>you</span> <span m=''139010''>not</span> <span m=''139220''>only</span>
  <span m=''139400''>want</span> <span m=''139640''>these</span> <span m=''140310''>horizontal</span>
  <span m=''140830''>barriers,</span> <span m=''142150''>but</span> <span m=''142610''>you</span>
  <span m=''142730''>also</span> <span m=''142990''>want</span> <span m=''143200''>some</span>
  <span m=''143360''>kind</span> <span m=''146200''>of</span> <span m=''146300''>vertical</span>
  <span m=''147620''>barrier</span> <span m=''149210''>to</span> <span m=''149340''>keep</span>
  <span m=''149570''>George</span> <span m=''149850''>and</span> <span m=''149960''>Martha</span>
  <span m=''150250''>separate.</span> </p><p><span m=''152980''>Let</span> <span m=''153190''>me
  be</span> <span m=''153420''>a</span> <span m=''153480''>little</span> <span m=''153740''>bit</span>
  <span m=''153890''>more</span> <span m=''154980''>concrete.</span> <span m=''156560''>Imagine</span>
  <span m=''157490''>that</span> <span m=''157680''>you''re</span> <span m=''157790''>thinking</span>
  <span m=''158150''>about</span> <span m=''159870''>personnel</span> <span m=''160390''>records</span>
  <span m=''161150''>for</span> <span m=''161380''>a</span> <span m=''162650''>large</span>
  <span m=''162990''>company</span> <span m=''163340''>with</span> <span m=''164190''>a</span>
  <span m=''164330''>lot</span> <span m=''164470''>of</span> <span m=''164610''>loosely</span>
  <span m=''165060''>linked</span> <span m=''165510''>divisions</span> <span m=''168000''>that</span>
  <span m=''168180''>don''t</span> <span m=''168370''>cooperate</span> <span m=''168910''>very</span>
  <span m=''169120''>well</span> <span m=''169350''>either.</span> <span m=''170430''>And</span>
  <span m=''172160''>imagine</span> <span m=''175060''>even</span> <span m=''175360''>that</span>
  <span m=''175450''>this</span> <span m=''175610''>company</span> <span m=''175970''>is</span>
  <span m=''176150''>formed</span> <span m=''176410''>by</span> <span m=''176530''>merging</span>
  <span m=''176980''>a</span> <span m=''177040''>whole</span> <span m=''177210''>bunch</span>
  <span m=''177450''>of</span> <span m=''177540''>companies</span> <span m=''178130''>that</span>
  <span m=''178300''>already</span> <span m=''178670''>have</span> <span m=''178860''>their</span>
  <span m=''178980''>personnel</span> <span m=''179450''>record</span> <span m=''179760''>system</span>
  <span m=''180080''>set</span> <span m=''180300''>up.</span> <span m=''183250''>And</span>
  <span m=''183450''>imagine</span> <span m=''183890''>that</span> <span m=''184490''>once</span>
  <span m=''185150''>these</span> <span m=''185340''>divisions</span> <span m=''185770''>are</span>
  <span m=''185860''>all</span> <span m=''186140''>linked</span> <span m=''186450''>in</span>
  <span m=''186570''>some</span> <span m=''186760''>kind</span> <span m=''186970''>of</span>
  <span m=''187070''>very</span> <span m=''187380''>sophisticated</span> <span m=''188080''>satellite</span>
  <span m=''188530''>network,</span> <span m=''188880''>and</span> <span m=''188960''>all</span>
  <span m=''189080''>these</span> <span m=''189240''>databases</span> <span m=''189820''>are</span>
  <span m=''189870''>put</span> <span m=''190070''>together.</span> <span m=''192240''>And</span>
  <span m=''192790''>what</span> <span m=''192990''>you''d</span> <span m=''193180''>like</span>
  <span m=''193380''>to</span> <span m=''193480''>do</span> <span m=''194940''>is,</span>
  <span m=''195110''>from</span> <span m=''195250''>any</span> <span m=''195430''>place</span>
  <span m=''195680''>in</span> <span m=''195750''>the</span> <span m=''195820''>company,</span>
  <span m=''197260''>to</span> <span m=''197380''>be</span> <span m=''197550''>able</span>
  <span m=''197760''>to</span> <span m=''198840''>say</span> <span m=''199140''>things</span>
  <span m=''199540''>like,</span> <span m=''200700''>oh,</span> <span m=''202370''>what''s</span>
  <span m=''202610''>the</span> <span m=''202700''>name</span> <span m=''203010''>in</span>
  <span m=''203080''>a</span> <span m=''203130''>personnel</span> <span m=''203600''>record?</span>
  <span m=''206400''>Or,</span> <span m=''207410''>what''s</span> <span m=''207580''>the</span>
  <span m=''207750''>job</span> <span m=''208020''>description</span> <span m=''208430''>in</span>
  <span m=''208520''>a</span> <span m=''208570''>personnel</span> <span m=''208980''>record?</span>
  <span m=''210540''>And</span> <span m=''210690''>not</span> <span m=''210850''>have</span>
  <span m=''210960''>to</span> <span m=''211080''>worry</span> <span m=''211440''>about</span>
  <span m=''211600''>the</span> <span m=''211770''>fact</span> <span m=''212490''>that</span>
  <span m=''213690''>each</span> <span m=''213910''>division</span> <span m=''214840''>obviously</span>
  <span m=''215400''>is</span> <span m=''215490''>going</span> <span m=''215560''>to</span>
  <span m=''215630''>have</span> <span m=''215850''>completely</span> <span m=''216370''>separate</span>
  <span m=''216760''>conventions</span> <span m=''217740''>for</span> <span m=''217940''>how</span>
  <span m=''218080''>you</span> <span m=''218250''>might</span> <span m=''218450''>implement</span>
  <span m=''218840''>these</span> <span m=''219010''>records.</span> <span m=''221580''>From</span>
  <span m=''221850''>this</span> <span m=''222010''>point</span> <span m=''222170''>you</span>
  <span m=''222240''>don''t</span> <span m=''222380''>want</span> <span m=''222460''>to</span>
  <span m=''222550''>know</span> <span m=''222710''>about</span> <span m=''223000''>that.</span>
  </p><p><span m=''224960''>Well</span> <span m=''226600''>how</span> <span m=''226720''>could</span>
  <span m=''226840''>you</span> <span m=''226940''>possibly</span> <span m=''227410''>do</span>
  <span m=''227610''>that?</span> <span m=''228430''>One</span> <span m=''228680''>way,</span>
  <span m=''228850''>of</span> <span m=''228970''>course,</span> <span m=''230490''>is</span>
  <span m=''230630''>to</span> <span m=''230730''>send</span> <span m=''231020''>down</span>
  <span m=''231200''>an</span> <span m=''231310''>edict</span> <span m=''231710''>from</span>
  <span m=''231880''>somewhere</span> <span m=''232640''>that</span> <span m=''233040''>everybody</span>
  <span m=''233540''>has</span> <span m=''233730''>to</span> <span m=''233830''>change</span>
  <span m=''234130''>their</span> <span m=''234270''>format</span> <span m=''235510''>to</span>
  <span m=''235810''>some</span> <span m=''236020''>fixed</span> <span m=''236290''>compatible</span>
  <span m=''236820''>thing.</span> <span m=''238070''>That''s</span> <span m=''238360''>what</span>
  <span m=''238490''>people</span> <span m=''238770''>often</span> <span m=''239050''>try,</span>
  <span m=''239290''>and</span> <span m=''239370''>of</span> <span m=''239450''>course</span>
  <span m=''239680''>it</span> <span m=''239780''>never</span> <span m=''239980''>works.</span>
  <span m=''241820''>Another</span> <span m=''242160''>thing</span> <span m=''243950''>that</span>
  <span m=''244130''>you</span> <span m=''244230''>might</span> <span m=''244420''>want</span>
  <span m=''244520''>to</span> <span m=''244630''>do</span> <span m=''244860''>is</span>
  <span m=''246340''>somehow</span> <span m=''246880''>arrange</span> <span m=''247340''>it</span>
  <span m=''248310''>so</span> <span m=''248450''>you</span> <span m=''248580''>can</span>
  <span m=''248700''>have</span> <span m=''248980''>these</span> <span m=''249190''>vertical</span>
  <span m=''249570''>barriers.</span> <span m=''251250''>So</span> <span m=''251480''>that</span>
  <span m=''251650''>when</span> <span m=''251750''>you</span> <span m=''251860''>ask</span>
  <span m=''252110''>for</span> <span m=''252190''>the</span> <span m=''252300''>name</span>
  <span m=''253300''>of</span> <span m=''253440''>a</span> <span m=''253500''>personnel</span>
  <span m=''253990''>record,</span> <span m=''254430''>somehow,</span> <span m=''255240''>whatever</span>
  <span m=''255700''>format</span> <span m=''256180''>it</span> <span m=''256269''>happens</span>
  <span m=''256709''>to</span> <span m=''256829''>be,</span> <span m=''257620''>name</span>
  <span m=''257860''>will</span> <span m=''257970''>figure</span> <span m=''258310''>out</span>
  <span m=''258440''>how</span> <span m=''258540''>to</span> <span m=''258640''>do</span>
  <span m=''258779''>the</span> <span m=''258899''>right</span> <span m=''259190''>thing.</span>
  <span m=''262730''>We</span> <span m=''262850''>want</span> <span m=''263150''>name</span>
  <span m=''263360''>to</span> <span m=''263440''>be,</span> <span m=''263840''>so-called,</span>
  <span m=''264360''>a</span> <span m=''264440''>generic</span> <span m=''265090''>operator.</span>
  <span m=''266260''>Generic</span> <span m=''266600''>operator</span> <span m=''267090''>means</span>
  <span m=''268160''>what</span> <span m=''268360''>it</span> <span m=''268530''>sort</span>
  <span m=''268670''>of</span> <span m=''268810''>precisely</span> <span m=''269380''>does</span>
  <span m=''269640''>depends</span> <span m=''270060''>on</span> <span m=''270150''>the</span>
  <span m=''270250''>kind</span> <span m=''270510''>of</span> <span m=''270580''>data</span>
  <span m=''270880''>that</span> <span m=''271050''>it''s</span> <span m=''271230''>looking</span>
  <span m=''271550''>at.</span> </p><p><span m=''273650''>More</span> <span m=''273890''>than</span>
  <span m=''274060''>that,</span> <span m=''274620''>you''d</span> <span m=''274810''>like</span>
  <span m=''274980''>to</span> <span m=''275090''>design</span> <span m=''275500''>the</span>
  <span m=''275540''>system</span> <span m=''276070''>so</span> <span m=''276290''>that</span>
  <span m=''276940''>the</span> <span m=''277100''>next</span> <span m=''277420''>time</span>
  <span m=''278160''>a</span> <span m=''278280''>new</span> <span m=''278550''>division</span>
  <span m=''279000''>comes</span> <span m=''279240''>into</span> <span m=''279370''>the</span>
  <span m=''279510''>company</span> <span m=''282550''>they</span> <span m=''282910''>don''t</span>
  <span m=''283250''>have</span> <span m=''283460''>to</span> <span m=''283570''>make</span>
  <span m=''283790''>any</span> <span m=''283970''>big</span> <span m=''284140''>changes</span>
  <span m=''284540''>in</span> <span m=''284640''>what</span> <span m=''284790''>they''re</span>
  <span m=''284910''>already</span> <span m=''285320''>doing</span> <span m=''285640''>to</span>
  <span m=''286180''>link</span> <span m=''286410''>into</span> <span m=''286630''>this</span>
  <span m=''286750''>system,</span> <span m=''287890''>and</span> <span m=''289180''>the</span>
  <span m=''289310''>rest</span> <span m=''289550''>of</span> <span m=''289600''>the</span>
  <span m=''289670''>company</span> <span m=''290110''>doesn''t</span> <span m=''290380''>have</span>
  <span m=''290550''>to</span> <span m=''290670''>make</span> <span m=''290890''>any</span>
  <span m=''291560''>big</span> <span m=''291730''>changes</span> <span m=''292230''>to</span>
  <span m=''292760''>admit</span> <span m=''293090''>their</span> <span m=''293250''>stuff</span>
  <span m=''293500''>to</span> <span m=''293620''>the</span> <span m=''293710''>system.</span>
  <span m=''295520''>So</span> <span m=''296030''>that''s</span> <span m=''296400''>the</span>
  <span m=''296480''>problem</span> <span m=''296930''>you</span> <span m=''297010''>should</span>
  <span m=''297160''>be</span> <span m=''297280''>thinking</span> <span m=''297630''>about.</span>
  <span m=''298700''>Like</span> <span m=''298880''>it''s</span> <span m=''298930''>sort</span>
  <span m=''299140''>of</span> <span m=''299990''>just</span> <span m=''300230''>your</span>
  <span m=''300320''>work.</span> <span m=''300770''>You want to</span> <span m=''300840''>be</span>
  <span m=''300990''>able</span> <span m=''301130''>to</span> <span m=''301410''>include</span>
  <span m=''301850''>new</span> <span m=''301990''>things</span> <span m=''302270''>by</span>
  <span m=''302390''>making</span> <span m=''302750''>minimal</span> <span m=''303130''>changes.</span>
  </p><p><span m=''305980''>OK,</span> <span m=''306080''>well</span> <span m=''306270''>that''s</span>
  <span m=''306470''>the</span> <span m=''306530''>problem</span> <span m=''306920''>that</span>
  <span m=''307060''>we''ll</span> <span m=''307130''>be</span> <span m=''307340''>talking</span>
  <span m=''307700''>about</span> <span m=''307950''>today.</span> <span m=''309440''>And</span>
  <span m=''309620''>you</span> <span m=''309690''>should</span> <span m=''309850''>have</span>
  <span m=''310100''>this</span> <span m=''310730''>sort of</span> <span m=''311110''>distributed</span>
  <span m=''312600''>personnel</span> <span m=''313140''>record</span> <span m=''313450''>system</span>
  <span m=''313790''>in</span> <span m=''313860''>your</span> <span m=''313990''>mind.</span>
  <span m=''314240''>But</span> <span m=''314360''>actually</span> <span m=''314960''>the</span>
  <span m=''315150''>one</span> <span m=''315260''>I''ll</span> <span m=''315340''>be</span>
  <span m=''315440''>talking</span> <span m=''315860''>about</span> <span m=''316080''>is</span>
  <span m=''316190''>a</span> <span m=''316250''>problem</span> <span m=''316620''>that''s</span>
  <span m=''316780''>a</span> <span m=''316830''>little</span> <span m=''317040''>bit</span>
  <span m=''317190''>more</span> <span m=''317370''>self-contained</span> <span m=''318200''>than
  that.</span> <span m=''318900''>that''ll</span> <span m=''319810''>bring</span>
  <span m=''319990''>up</span> <span m=''320080''>the</span> <span m=''320180''>issues,</span>
  <span m=''320780''>I</span> <span m=''320850''>think,</span> <span m=''321050''>more</span>
  <span m=''321250''>clearly.</span> <span m=''321870''>That''s</span> <span m=''322150''>the</span>
  <span m=''322240''>problem</span> <span m=''322690''>of</span> <span m=''323250''>doing</span>
  <span m=''323900''>a</span> <span m=''323990''>system</span> <span m=''324350''>that</span>
  <span m=''324470''>does</span> <span m=''324640''>arithmetic</span> <span m=''325160''>on</span>
  <span m=''325300''>complex</span> <span m=''325820''>numbers.</span> <span m=''327770''>So</span>
  <span m=''328170''>let''s</span> <span m=''328380''>take</span> <span m=''328560''>a</span>
  <span m=''328600''>look</span> <span m=''328760''>here.</span> </p><p><span m=''330690''>Just</span>
  <span m=''330900''>as</span> <span m=''330970''>a</span> <span m=''331040''>little</span>
  <span m=''331280''>review,</span> <span m=''331850''>there</span> <span m=''332160''>are</span>
  <span m=''332190''>things</span> <span m=''332460''>called</span> <span m=''332670''>complex</span>
  <span m=''333170''>numbers.</span> <span m=''335250''>Complex</span> <span m=''335650''>number</span>
  <span m=''335900''>you</span> <span m=''336000''>can</span> <span m=''336140''>think</span>
  <span m=''336320''>of</span> <span m=''336410''>as</span> <span m=''336520''>a</span>
  <span m=''336570''>point</span> <span m=''336860''>in</span> <span m=''336960''>the</span>
  <span m=''337050''>plane,</span> <span m=''337530''>or</span> <span m=''337790''>z.</span>
  <span m=''339370''>And</span> <span m=''341350''>you</span> <span m=''341500''>can</span>
  <span m=''341660''>represent</span> <span m=''343970''>a</span> <span m=''344120''>point</span>
  <span m=''344430''>either</span> <span m=''344780''>by</span> <span m=''345030''>its</span>
  <span m=''345230''>real-part</span> <span m=''346110''>and</span> <span m=''346230''>its</span>
  <span m=''346360''>imaginary-part.</span> <span m=''347190''>So</span> <span m=''347360''>if</span>
  <span m=''347450''>this</span> <span m=''347630''>is</span> <span m=''347820''>z</span>
  <span m=''348660''>and its</span> <span m=''349200''>real-part is</span> <span m=''350280''>this</span>
  <span m=''350480''>much,</span> <span m=''351380''>and</span> <span m=''351690''>its</span>
  <span m=''351820''>imaginary-part</span> <span m=''352490''>is</span> <span m=''352600''>that</span>
  <span m=''352850''>much,</span> <span m=''354230''>and</span> <span m=''354410''>you</span>
  <span m=''354590''>write z</span> <span m=''354880''>equals</span> <span m=''355310''>x</span>
  <span m=''355560''>plus</span> <span m=''355800''>iy.</span> </p><p><span m=''359110''>Or</span>
  <span m=''359580''>another</span> <span m=''359990''>way</span> <span m=''360400''>to</span>
  <span m=''360810''>represent</span> <span m=''361270''>a</span> <span m=''361320''>complex</span>
  <span m=''361780''>number</span> <span m=''362390''>is</span> <span m=''362580''>by</span>
  <span m=''362740''>saying,</span> <span m=''363210''>what''s</span> <span m=''363470''>the</span>
  <span m=''363740''>distance</span> <span m=''364190''>from</span> <span m=''364300''>the</span>
  <span m=''364420''>origin,</span> <span m=''366740''>and</span> <span m=''368220''>what''s</span>
  <span m=''368450''>the</span> <span m=''368550''>angle?</span> <span m=''370900''>So</span>
  <span m=''371370''>that</span> <span m=''371630''>represents</span> <span m=''372060''>a</span>
  <span m=''372120''>complex</span> <span m=''372570''>number</span> <span m=''373170''>as</span>
  <span m=''373410''>its</span> <span m=''373540''>radius</span> <span m=''375720''>times</span>
  <span m=''376170''>an</span> <span m=''376280''>angle.</span> <span m=''379520''>This</span>
  <span m=''379760''>one''s</span> <span m=''379950''>called--</span> <span m=''380140''>the</span>
  <span m=''380250''>original</span> <span m=''380610''>one''s called</span> <span
  m=''380820''>rectangular</span> <span m=''381380''>form,</span> <span m=''382660''>rectangular</span>
  <span m=''383130''>representation,</span> <span m=''384410''>real-</span> <span
  m=''384600''>and</span> <span m=''384690''>imaginary-part,</span> <span m=''386230''>or</span>
  <span m=''386680''>polar</span> <span m=''387070''>representation.</span> <span
  m=''388640''>Magnitude</span> <span m=''389240''>and</span> <span m=''389360''>angle--</span>
  <span m=''390040''>and</span> <span m=''390240''>if</span> <span m=''390330''>you</span>
  <span m=''390440''>know</span> <span m=''390660''>the</span> <span m=''390780''>real-</span>
  <span m=''390960''>and</span> <span m=''391030''>imaginary-part,</span> <span m=''391730''>you</span>
  <span m=''391830''>can</span> <span m=''391960''>figure</span> <span m=''392260''>out</span>
  <span m=''392350''>the</span> <span m=''392430''>magnitude and</span> <span m=''392900''>angle.</span>
  <span m=''393720''>If you know</span> <span m=''394030''>x</span> <span m=''394270''>and</span>
  <span m=''394360''>y,</span> <span m=''395050''>you</span> <span m=''395210''>can</span>
  <span m=''395330''>get</span> <span m=''395500''>r</span> <span m=''396180''>by</span>
  <span m=''396320''>this</span> <span m=''396520''>formula.</span> <span m=''397190''>Square
  root of</span> <span m=''397580''>sum</span> <span m=''397780''>of</span> <span
  m=''397840''>the</span> <span m=''397900''>squares,</span> <span m=''398900''>and</span>
  <span m=''399070''>you can</span> <span m=''399150''>get</span> <span m=''399350''>the</span>
  <span m=''399480''>angle</span> <span m=''399830''>as an</span> <span m=''400170''>arctangent.</span>
  </p><p><span m=''401420''>Or</span> <span m=''401580''>conversely,</span> <span
  m=''402530''>if</span> <span m=''402700''>you</span> <span m=''402810''>knew</span>
  <span m=''403610''>r and A</span> <span m=''404210''>you</span> <span m=''404290''>could</span>
  <span m=''404420''>figure</span> <span m=''404670''>out</span> <span m=''404770''>x</span>
  <span m=''404970''>and</span> <span m=''405080''>y.</span> <span m=''405800''>x
  is</span> <span m=''406140''>r</span> <span m=''406360''>times</span> <span m=''406630''>the</span>
  <span m=''406710''>cosine</span> <span m=''407150''>of</span> <span m=''407210''>A,</span>
  <span m=''408040''>and</span> <span m=''408230''>y</span> <span m=''408430''>is</span>
  <span m=''408550''>r</span> <span m=''408670''>times</span> <span m=''408870''>the</span>
  <span m=''408990''>sine</span> <span m=''409340''>of A.</span> <span m=''410931''>All
  right,</span> <span m=''411400''>so</span> <span m=''411580''>there''s</span> <span
  m=''411800''>these</span> <span m=''411970''>two.</span> <span m=''412490''>They''re</span>
  <span m=''412650''>complex</span> <span m=''413090''>numbers.</span> <span m=''414130''>You</span>
  <span m=''414240''>can</span> <span m=''414370''>think</span> <span m=''414540''>of</span>
  <span m=''414600''>them</span> <span m=''414730''>either</span> <span m=''415040''>in</span>
  <span m=''415110''>polar</span> <span m=''415470''>form</span> <span m=''415810''>or</span>
  <span m=''416140''>rectangular</span> <span m=''416770''>form.</span> <span m=''417150''>What</span>
  <span m=''417320''>we would</span> <span m=''417500''>like</span> <span m=''417660''>to</span>
  <span m=''417770''>do</span> <span m=''418260''>is</span> <span m=''418410''>make</span>
  <span m=''418610''>a</span> <span m=''418670''>system</span> <span m=''419050''>that</span>
  <span m=''419610''>does</span> <span m=''419830''>arithmetic</span> <span m=''420360''>on</span>
  <span m=''420490''>complex</span> <span m=''420970''>numbers.</span> <span m=''423850''>In
  other</span> <span m=''424150''>words,</span> <span m=''424460''>what</span> <span
  m=''424550''>we''d</span> <span m=''424700''>like--</span> <span m=''425580''>just</span>
  <span m=''425770''>like</span> <span m=''425910''>the</span> <span m=''425990''>rational</span>
  <span m=''426340''>number</span> <span m=''426590''>example--</span> <span m=''427380''>is</span>
  <span m=''427620''>to</span> <span m=''428480''>have</span> <span m=''428670''>some</span>
  <span m=''428820''>operations</span> <span m=''429480''>plus c,</span> <span m=''430490''>which</span>
  <span m=''430660''>is</span> <span m=''430750''>going</span> <span m=''430830''>to</span>
  <span m=''430910''>take</span> <span m=''431120''>two</span> <span m=''431240''>complex</span>
  <span m=''431660''>numbers</span> <span m=''431950''>and</span> <span m=''432130''>add</span>
  <span m=''432310''>them,</span> <span m=''432940''>subtract</span> <span m=''433245''>them,</span>
  <span m=''434430''>and</span> <span m=''434640''>multiply</span> <span m=''435140''>them,</span>
  <span m=''436230''>and</span> <span m=''436480''>divide</span> <span m=''436740''>them.</span>
  </p><p><span m=''440730''>OK,</span> <span m=''440960''>well</span> <span m=''442220''>there''s</span>
  <span m=''442520''>little</span> <span m=''442710''>bit</span> <span m=''442850''>of</span>
  <span m=''444020''>mathematics</span> <span m=''444790''>behind</span> <span m=''445140''>it.</span>
  <span m=''445280''>What</span> <span m=''445420''>are</span> <span m=''445470''>the</span>
  <span m=''445570''>actual</span> <span m=''446050''>formulas</span> <span m=''446960''>for</span>
  <span m=''447080''>manipulating</span> <span m=''447760''>such</span> <span m=''448060''>things?</span>
  <span m=''449800''>And</span> <span m=''450480''>it''s sort of</span> <span m=''450610''>not</span>
  <span m=''450780''>important</span> <span m=''451120''>where</span> <span m=''451220''>they</span>
  <span m=''451360''>come</span> <span m=''451620''>from,</span> <span m=''453580''>but</span>
  <span m=''454060''>just</span> <span m=''454270''>as</span> <span m=''454350''>an</span>
  <span m=''454430''>implementer</span> <span m=''455510''>let''s</span> <span m=''455700''>see--</span>
  <span m=''456120''>if</span> <span m=''456370''>you</span> <span m=''456480''>want</span>
  <span m=''456610''>to add</span> <span m=''456940''>two</span> <span m=''457090''>complex</span>
  <span m=''457580''>numbers</span> <span m=''459250''>it''s</span> <span m=''459440''>pretty</span>
  <span m=''459700''>easy</span> <span m=''459970''>to</span> <span m=''460030''>get</span>
  <span m=''460200''>its</span> <span m=''460350''>real-part</span> <span m=''461410''>and</span>
  <span m=''461560''>its</span> <span m=''461720''>imaginary-part.</span> <span m=''462660''>The</span>
  <span m=''462880''>real-part</span> <span m=''464250''>of</span> <span m=''464430''>the</span>
  <span m=''464510''>sum</span> <span m=''464840''>of</span> <span m=''464920''>two</span>
  <span m=''465070''>complex</span> <span m=''465560''>numbers,</span> <span m=''467580''>the</span>
  <span m=''467810''>real-part</span> <span m=''468260''>of</span> <span m=''468350''>the</span>
  <span m=''468590''>z1</span> <span m=''468990''>plus</span> <span m=''469230''>z2</span>
  <span m=''470070''>is</span> <span m=''471040''>the</span> <span m=''471290''>real-part</span>
  <span m=''471710''>of</span> <span m=''471800''>z1</span> <span m=''473380''>plus</span>
  <span m=''473670''>the</span> <span m=''473720''>real-part</span> <span m=''474120''>of</span>
  <span m=''474210''>z2.</span> <span m=''477820''>And</span> <span m=''477980''>the</span>
  <span m=''478080''>imaginary-part</span> <span m=''480470''>of</span> <span m=''480620''>z1</span>
  <span m=''480840''>plus</span> <span m=''481030''>z2</span> <span m=''481770''>is</span>
  <span m=''481980''>the</span> <span m=''482090''>imaginary</span> <span m=''482550''>part</span>
  <span m=''482770''>of</span> <span m=''482890''>z1</span> <span m=''483970''>plus
  the</span> <span m=''484370''>imaginary</span> <span m=''484560''>part</span> <span
  m=''484950''>of</span> <span m=''485060''>z2.</span> <span m=''487410''>So</span>
  <span m=''487930''>it''s</span> <span m=''488030''>pretty</span> <span m=''488220''>easy</span>
  <span m=''488460''>to add</span> <span m=''488710''>complex</span> <span m=''489150''>numbers.</span>
  <span m=''489480''>You just</span> <span m=''489720''>add</span> <span m=''489890''>the</span>
  <span m=''489990''>corresponding</span> <span m=''490630''>parts</span> <span m=''491340''>and</span>
  <span m=''491500''>make</span> <span m=''491680''>a</span> <span m=''491720''>new</span>
  <span m=''491840''>complex</span> <span m=''492320''>number</span> <span m=''492530''>with</span>
  <span m=''492680''>those</span> <span m=''492900''>parts.</span> </p><p><span m=''493400''>If</span>
  <span m=''493510''>you</span> <span m=''493600''>want</span> <span m=''493680''>to</span>
  <span m=''493770''>multiply</span> <span m=''494300''>them,</span> <span m=''495390''>it''s</span>
  <span m=''495670''>kind</span> <span m=''495800''>of</span> <span m=''495930''>nice</span>
  <span m=''496190''>to</span> <span m=''496290''>do</span> <span m=''496480''>it</span>
  <span m=''496980''>in</span> <span m=''497180''>polar</span> <span m=''497400''>form.</span>
  <span m=''497840''>Because</span> <span m=''498950''>if</span> <span m=''499110''>you</span>
  <span m=''499300''>have</span> <span m=''499500''>two</span> <span m=''499640''>complex</span>
  <span m=''500130''>numbers,</span> <span m=''500430''>the</span> <span m=''500520''>magnitude</span>
  <span m=''501810''>of</span> <span m=''502000''>their</span> <span m=''502140''>product</span>
  <span m=''504170''>is</span> <span m=''504320''>here,</span> <span m=''504430''>the</span>
  <span m=''504530''>product</span> <span m=''505670''>of</span> <span m=''505770''>the</span>
  <span m=''505880''>magnitudes.</span> <span m=''508850''>And</span> <span m=''509020''>the</span>
  <span m=''509150''>angle</span> <span m=''510050''>of</span> <span m=''510210''>the</span>
  <span m=''510290''>product</span> <span m=''511270''>is</span> <span m=''511470''>the</span>
  <span m=''511560''>sum</span> <span m=''513360''>of</span> <span m=''513460''>the</span>
  <span m=''513570''>angles.</span> <span m=''515809''>So</span> <span m=''515940''>that''s</span>
  <span m=''516070''>sort</span> <span m=''516220''>of</span> <span m=''516990''>mathematics</span>
  <span m=''517710''>that</span> <span m=''517860''>allows</span> <span m=''518140''>you</span>
  <span m=''518549''>to</span> <span m=''519049''>do</span> <span m=''519179''>arithmetic</span>
  <span m=''519669''>on</span> <span m=''519789''>complex</span> <span m=''520240''>numbers.</span>
  </p><p><span m=''520549''>Let''s</span> <span m=''520710''>actually</span> <span
  m=''521280''>think</span> <span m=''521510''>about</span> <span m=''521760''>the</span>
  <span m=''521830''>implementation.</span> <span m=''523720''>Well</span> <span m=''524540''>we</span>
  <span m=''524750''>do it</span> <span m=''524870''>just</span> <span m=''525210''>like</span>
  <span m=''526540''>rational</span> <span m=''527010''>numbers.</span> <span m=''529330''>We</span>
  <span m=''529800''>come</span> <span m=''529960''>down,</span> <span m=''530190''>we</span>
  <span m=''530300''>assume</span> <span m=''530640''>we</span> <span m=''530740''>have</span>
  <span m=''532000''>some</span> <span m=''532200''>constructors</span> <span m=''532800''>and</span>
  <span m=''532910''>selectors.</span> <span m=''533840''>What</span> <span m=''533990''>would</span>
  <span m=''534130''>we</span> <span m=''534220''>like?</span> <span m=''535330''>Well</span>
  <span m=''535540''>let''s</span> <span m=''535770''>assume</span> <span m=''536100''>that</span>
  <span m=''536230''>we</span> <span m=''536370''>make</span> <span m=''536640''>a</span>
  <span m=''536720''>data</span> <span m=''537040''>object</span> <span m=''537610''>cloud,</span>
  <span m=''538650''>which</span> <span m=''538800''>is</span> <span m=''538890''>a</span>
  <span m=''538940''>complex</span> <span m=''539430''>number</span> <span m=''539740''>that</span>
  <span m=''539890''>has</span> <span m=''540040''>some</span> <span m=''540160''>stuff</span>
  <span m=''540500''>in</span> <span m=''540650''>it,</span> <span m=''541960''>and</span>
  <span m=''542110''>that</span> <span m=''542250''>we</span> <span m=''542350''>can</span>
  <span m=''542510''>get</span> <span m=''542730''>out</span> <span m=''543080''>from</span>
  <span m=''543220''>a</span> <span m=''543280''>complex</span> <span m=''543760''>number</span>
  <span m=''544020''>the</span> <span m=''544150''>real-part,</span> <span m=''545450''>or</span>
  <span m=''545740''>the</span> <span m=''545870''>imaginary-part,</span> <span m=''547290''>or</span>
  <span m=''547510''>the</span> <span m=''547610''>magnitude,</span> <span m=''549000''>or</span>
  <span m=''549240''>the</span> <span m=''549350''>angle.</span> </p><p><span m=''552150''>We</span>
  <span m=''552320''>want</span> <span m=''552500''>some</span> <span m=''552610''>ways</span>
  <span m=''552780''>of</span> <span m=''552840''>making</span> <span m=''553260''>complex</span>
  <span m=''553740''>numbers--</span> <span m=''554010''>not</span> <span m=''554150''>only</span>
  <span m=''554320''>selectors,</span> <span m=''554830''>but</span> <span m=''554980''>constructors.</span>
  <span m=''556800''>So</span> <span m=''556950''>we''ll</span> <span m=''557080''>assume</span>
  <span m=''557370''>we</span> <span m=''557480''>have</span> <span m=''558070''>a
  thing</span> <span m=''558590''>called make-rectangular.</span> <span m=''560160''>What</span>
  <span m=''560380''>make-rectangular</span> <span m=''561170''>is</span> <span m=''561270''>going</span>
  <span m=''561340''>to</span> <span m=''561420''>do</span> <span m=''561580''>is</span>
  <span m=''561780''>take</span> <span m=''563430''>a</span> <span m=''563590''>real-part</span>
  <span m=''564190''>and</span> <span m=''564510''>an</span> <span m=''564720''>imaginary-part</span>
  <span m=''567210''>and</span> <span m=''567400''>construct</span> <span m=''567820''>a</span>
  <span m=''567880''>complex</span> <span m=''568360''>number</span> <span m=''568610''>with</span>
  <span m=''568760''>those</span> <span m=''568980''>parts.</span> <span m=''571920''>Similarly,</span>
  <span m=''572850''>we</span> <span m=''572950''>can</span> <span m=''573070''>have</span>
  <span m=''573520''>make-polar</span> <span m=''574310''>which</span> <span m=''574540''>will</span>
  <span m=''574670''>take</span> <span m=''574950''>a</span> <span m=''575010''>magnitude</span>
  <span m=''577020''>and</span> <span m=''577200''>an</span> <span m=''577320''>angle,</span>
  <span m=''580510''>and</span> <span m=''581050''>construct</span> <span m=''581480''>a</span>
  <span m=''581520''>complex</span> <span m=''582010''>number</span> <span m=''582550''>which</span>
  <span m=''582730''>has</span> <span m=''582910''>that</span> <span m=''583090''>magnitude</span>
  <span m=''583540''>and</span> <span m=''583620''>angle.</span> </p><p><span m=''584680''>So</span>
  <span m=''584850''>here''s</span> <span m=''585010''>a</span> <span m=''585080''>system.</span>
  <span m=''585460''>We''ll have</span> <span m=''585610''>two</span> <span m=''585760''>constructors</span>
  <span m=''586840''>and</span> <span m=''587080''>four</span> <span m=''587250''>selectors.</span>
  <span m=''588910''>And</span> <span m=''589220''>now,</span> <span m=''590060''>just</span>
  <span m=''590280''>like</span> <span m=''590450''>before,</span> <span m=''593510''>in</span>
  <span m=''593650''>terms</span> <span m=''593940''>of that</span> <span m=''594150''>abstract</span>
  <span m=''594880''>data</span> <span m=''595150''>we''ll</span> <span m=''595310''>go</span>
  <span m=''595450''>ahead</span> <span m=''596000''>and</span> <span m=''596170''>implement</span>
  <span m=''597450''>our</span> <span m=''597610''>complex</span> <span m=''598060''>number</span>
  <span m=''598360''>operations.</span> <span m=''599220''>And</span> <span m=''599760''>here</span>
  <span m=''599940''>you</span> <span m=''600080''>can</span> <span m=''600210''>see</span>
  <span m=''600370''>translated</span> <span m=''601470''>into</span> <span m=''601730''>Lisp</span>
  <span m=''602000''>code</span> <span m=''603060''>just</span> <span m=''603280''>the</span>
  <span m=''605490''>arithmetic</span> <span m=''605950''>formulas</span> <span m=''606410''>I</span>
  <span m=''606460''>put</span> <span m=''606680''>down</span> <span m=''606870''>before.</span>
  <span m=''608330''>If</span> <span m=''608640''>I want to add</span> <span m=''608850''>two</span>
  <span m=''609020''>complex</span> <span m=''609500''>numbers</span> <span m=''611690''>I</span>
  <span m=''611820''>will</span> <span m=''612370''>make</span> <span m=''612840''>a</span>
  <span m=''612920''>complex</span> <span m=''613450''>number</span> <span m=''613840''>out</span>
  <span m=''614050''>of</span> <span m=''614190''>its</span> <span m=''614370''>real-</span>
  <span m=''614660''>and</span> <span m=''614790''>imaginary-parts.</span> <span m=''616630''>The</span>
  <span m=''617070''>real</span> <span m=''617330''>part</span> <span m=''617590''>of</span>
  <span m=''617650''>the</span> <span m=''617730''>complex</span> <span m=''618170''>number</span>
  <span m=''618390''>I''m</span> <span m=''618480''>going</span> <span m=''618550''>to</span>
  <span m=''618630''>make</span> <span m=''619500''>is</span> <span m=''619680''>the</span>
  <span m=''619760''>sum</span> <span m=''620730''>of</span> <span m=''620850''>the</span>
  <span m=''620970''>real-parts.</span> <span m=''623310''>The</span> <span m=''623550''>imaginary</span>
  <span m=''624060''>part</span> <span m=''624270''>of</span> <span m=''624320''>the</span>
  <span m=''624370''>complex</span> <span m=''624800''>number</span> <span m=''625020''>I''m</span>
  <span m=''625050''>going</span> <span m=''625190''>to</span> <span m=''625250''>make</span>
  <span m=''625450''>is</span> <span m=''625560''>the</span> <span m=''625640''>sum</span>
  <span m=''626460''>of</span> <span m=''626610''>the</span> <span m=''626750''>imaginary-parts.</span>
  <span m=''630310''>I</span> <span m=''630410''>put</span> <span m=''630610''>those</span>
  <span m=''630780''>together,</span> <span m=''631090''>make</span> <span m=''631310''>a</span>
  <span m=''631370''>complex</span> <span m=''631800''>number.</span> <span m=''631990''>That''s</span>
  <span m=''632230''>how</span> <span m=''632360''>I</span> <span m=''632470''>implement</span>
  <span m=''633430''>complex</span> <span m=''633840''>number</span> <span m=''634080''>addition.</span>
  </p><p><span m=''635780''>Subtraction</span> <span m=''637370''>is</span> <span
  m=''637520''>essentially</span> <span m=''637980''>the</span> <span m=''638060''>same.</span>
  <span m=''639650''>All</span> <span m=''639800''>I</span> <span m=''639870''>do</span>
  <span m=''640010''>is</span> <span m=''640110''>subtract</span> <span m=''640550''>the</span>
  <span m=''640630''>parts</span> <span m=''642100''>rather</span> <span m=''642320''>than</span>
  <span m=''642590''>add</span> <span m=''642760''>them.</span> <span m=''645140''>To</span>
  <span m=''645370''>multiply</span> <span m=''645910''>two</span> <span m=''646100''>complex</span>
  <span m=''646620''>numbers,</span> <span m=''647570''>I</span> <span m=''647980''>use</span>
  <span m=''648140''>the</span> <span m=''648280''>other</span> <span m=''648430''>formula.</span>
  <span m=''649270''>I''ll</span> <span m=''649410''>make</span> <span m=''649650''>a</span>
  <span m=''649720''>complex</span> <span m=''650210''>number</span> <span m=''652480''>out</span>
  <span m=''652700''>of</span> <span m=''652820''>a</span> <span m=''652870''>magnitude</span>
  <span m=''653410''>and</span> <span m=''653500''>angle.</span> <span m=''655350''>The</span>
  <span m=''655450''>magnitude</span> <span m=''656710''>is</span> <span m=''656870''>going</span>
  <span m=''656950''>to</span> <span m=''657030''>be</span> <span m=''657120''>the</span>
  <span m=''657210''>product</span> <span m=''657680''>of</span> <span m=''657750''>the</span>
  <span m=''657830''>magnitudes</span> <span m=''658740''>of</span> <span m=''659030''>the</span>
  <span m=''659120''>two</span> <span m=''659280''>complex</span> <span m=''659750''>numbers</span>
  <span m=''660060''>I''m</span> <span m=''660140''>multiplying.</span> <span m=''663710''>And</span>
  <span m=''664140''>the</span> <span m=''664240''>angle</span> <span m=''664860''>is</span>
  <span m=''665030''>going</span> <span m=''665110''>to</span> <span m=''665190''>be</span>
  <span m=''665270''>the</span> <span m=''665360''>sum</span> <span m=''666210''>of</span>
  <span m=''666330''>the</span> <span m=''666460''>angles</span> <span m=''666830''>of</span>
  <span m=''666900''>the</span> <span m=''666980''>two</span> <span m=''667110''>complex</span>
  <span m=''667550''>numbers</span> <span m=''667810''>I''m</span> <span m=''667860''>multiplying.</span>
  <span m=''669620''>So</span> <span m=''669800''>there''s</span> <span m=''669970''>multiplication.</span>
  </p><p><span m=''671230''>And then</span> <span m=''671530''>division,</span> <span
  m=''674640''>division</span> <span m=''675040''>is</span> <span m=''675140''>almost</span>
  <span m=''675450''>the</span> <span m=''675510''>same.</span> <span m=''677370''>Here</span>
  <span m=''677520''>I</span> <span m=''677580''>divide</span> <span m=''677950''>the</span>
  <span m=''678020''>magnitudes</span> <span m=''678530''>and</span> <span m=''678640''>subtract
  the</span> <span m=''679200''>angles.</span> </p><p><span m=''688640''>Now I''ve</span>
  <span m=''688940''>implemented</span> <span m=''689490''>the</span> <span m=''689600''>operations.</span>
  <span m=''691870''>And</span> <span m=''693070''>what do</span> <span m=''693360''>we</span>
  <span m=''693480''>do?</span> <span m=''693640''>We</span> <span m=''693750''>call</span>
  <span m=''693980''>on</span> <span m=''694150''>George.</span> <span m=''696060''>We''ve</span>
  <span m=''696340''>done</span> <span m=''696810''>the</span> <span m=''696910''>use,</span>
  <span m=''697440''>let''s</span> <span m=''697630''>worry</span> <span m=''697780''>about</span>
  <span m=''697990''>the</span> <span m=''698070''>representation.</span> <span m=''698800''>We''ll</span>
  <span m=''698930''>call</span> <span m=''699170''>on</span> <span m=''699360''>George</span>
  <span m=''700370''>and</span> <span m=''700530''>say</span> <span m=''700680''>to</span>
  <span m=''700760''>George,</span> <span m=''701030''>go</span> <span m=''701160''>ahead</span>
  <span m=''701700''>and</span> <span m=''701910''>build</span> <span m=''702200''>us</span>
  <span m=''702360''>a</span> <span m=''702420''>complex</span> <span m=''702860''>number</span>
  <span m=''703090''>representation.</span> <span m=''705250''>Well</span> <span m=''705460''>that''s</span>
  <span m=''705630''>fine.</span> <span m=''707770''>George</span> <span m=''708060''>can</span>
  <span m=''708180''>say,</span> <span m=''709840''>we''ll</span> <span m=''710020''>implement</span>
  <span m=''711430''>a</span> <span m=''711590''>complex</span> <span m=''712110''>number</span>
  <span m=''712660''>simply</span> <span m=''713070''>as</span> <span m=''713150''>a</span>
  <span m=''713230''>pair</span> <span m=''714760''>that</span> <span m=''715580''>has</span>
  <span m=''715750''>the</span> <span m=''715850''>real-part</span> <span m=''716280''>and</span>
  <span m=''716330''>the</span> <span m=''716400''>imaginary-part.</span> <span m=''717200''>So</span>
  <span m=''718140''>if</span> <span m=''718320''>I</span> <span m=''718370''>want</span>
  <span m=''718460''>to</span> <span m=''718560''>make</span> <span m=''718810''>a</span>
  <span m=''718870''>complex</span> <span m=''719390''>number</span> <span m=''720560''>with</span>
  <span m=''720640''>a</span> <span m=''720720''>certain</span> <span m=''721020''>real-part</span>
  <span m=''721560''>and</span> <span m=''721690''>an</span> <span m=''721800''>imaginary-part,</span>
  <span m=''723420''>I''ll</span> <span m=''723550''>just</span> <span m=''723630''>use</span>
  <span m=''723860''>cons to</span> <span m=''724350''>form</span> <span m=''724580''>a
  pair,</span> <span m=''724910''>and</span> <span m=''725050''>that</span> <span
  m=''725190''>will--</span> <span m=''725420''>that''s</span> <span m=''726340''>George''s</span>
  <span m=''726640''>representation</span> <span m=''727015''>of a</span> <span m=''727390''>complex</span>
  <span m=''727850''>number.</span> </p><p><span m=''729780''>So</span> <span m=''729980''>if</span>
  <span m=''730090''>I</span> <span m=''730110''>want</span> <span m=''730200''>to</span>
  <span m=''730300''>get</span> <span m=''730580''>out</span> <span m=''730950''>the</span>
  <span m=''731170''>real-part</span> <span m=''731600''>of</span> <span m=''731670''>something,</span>
  <span m=''732100''>I</span> <span m=''732170''>just</span> <span m=''732420''>extract</span>
  <span m=''732870''>the</span> <span m=''732950''>car,</span> <span m=''733680''>the
  first</span> <span m=''733900''>part.</span> <span m=''734350''>If</span> <span
  m=''734580''>I</span> <span m=''734670''>want</span> <span m=''734750''>to</span>
  <span m=''734840''>get</span> <span m=''734960''>the</span> <span m=''735070''>imaginary-part,</span>
  <span m=''735800''>I extract</span> <span m=''736230''>the</span> <span m=''736300''>cdr.</span>
  <span m=''739600''>How</span> <span m=''739700''>do</span> <span m=''739800''>I</span>
  <span m=''739870''>deal</span> <span m=''740110''>with</span> <span m=''740310''>the</span>
  <span m=''740780''>magnitude</span> <span m=''741290''>and</span> <span m=''741370''>angle?</span>
  <span m=''742220''>Well</span> <span m=''742400''>if</span> <span m=''742540''>I</span>
  <span m=''742600''>want</span> <span m=''742800''>to</span> <span m=''742920''>extract</span>
  <span m=''743580''>the</span> <span m=''743960''>magnitude</span> <span m=''745000''>of</span>
  <span m=''745130''>one</span> <span m=''745290''>of</span> <span m=''745420''>these</span>
  <span m=''745550''>things,</span> <span m=''745820''>I</span> <span m=''746250''>get</span>
  <span m=''746420''>the</span> <span m=''746490''>square</span> <span m=''746900''>root</span>
  <span m=''747650''>of</span> <span m=''747760''>the</span> <span m=''747870''>sum</span>
  <span m=''748250''>of</span> <span m=''748370''>the</span> <span m=''748490''>square</span>
  <span m=''748830''>of the</span> <span m=''748960''>car</span> <span m=''751130''>plus</span>
  <span m=''751370''>the</span> <span m=''751440''>square</span> <span m=''751740''>of
  the</span> <span m=''751850''>cdr.</span> <span m=''753401''>If</span> <span m=''753810''>I</span>
  <span m=''753890''>want</span> <span m=''753970''>to</span> <span m=''754060''>get</span>
  <span m=''754200''>the</span> <span m=''754310''>angle,</span> <span m=''755350''>I</span>
  <span m=''755700''>compute</span> <span m=''756230''>the arctangent</span> <span
  m=''757480''>of</span> <span m=''757660''>the</span> <span m=''758400''>cdr</span>
  <span m=''758690''>in</span> <span m=''758760''>the</span> <span m=''758860''>car.</span>
  <span m=''759530''>This</span> <span m=''759760''>is</span> <span m=''760770''>a</span>
  <span m=''760890''>list</span> <span m=''761170''>procedure</span> <span m=''761610''>for</span>
  <span m=''761750''>computing</span> <span m=''762100''>arctangent.</span> <span
  m=''764970''>And</span> <span m=''765120''>if</span> <span m=''765180''>somebody</span>
  <span m=''765590''>hands</span> <span m=''765970''>me</span> <span m=''766550''>a</span>
  <span m=''766660''>magnitude</span> <span m=''767900''>and</span> <span m=''768070''>an</span>
  <span m=''768170''>angle</span> <span m=''768970''>and</span> <span m=''769150''>says,</span>
  <span m=''769340''>make</span> <span m=''769580''>me</span> <span m=''769740''>a</span>
  <span m=''769790''>complex</span> <span m=''770270''>number,</span> <span m=''770830''>well</span>
  <span m=''771090''>I</span> <span m=''771160''>compute</span> <span m=''771570''>the</span>
  <span m=''771670''>real-part and the</span> <span m=''772260''>imaginary-part,</span>
  <span m=''773780''>or our cosine</span> <span m=''774280''>of</span> <span m=''774440''>a</span>
  <span m=''775280''>and</span> <span m=''775400''>our</span> <span m=''775560''>sine
  of a,</span> <span m=''777570''>and</span> <span m=''777800''>stick</span> <span
  m=''777990''>them</span> <span m=''778120''>together</span> <span m=''778500''>into</span>
  <span m=''778670''>a</span> <span m=''778730''>pair.</span> </p><p><span m=''781460''>OK</span>
  <span m=''781680''>so</span> <span m=''781830''>we''re</span> <span m=''781940''>done.</span>
  <span m=''782260''>In</span> <span m=''782590''>fact,</span> <span m=''782880''>what</span>
  <span m=''782970''>I</span> <span m=''783070''>just</span> <span m=''783320''>did,</span>
  <span m=''783990''>conceptually,</span> <span m=''786890''>is</span> <span m=''787030''>absolutely</span>
  <span m=''787650''>no</span> <span m=''787830''>different</span> <span m=''788390''>from</span>
  <span m=''788650''>the</span> <span m=''788740''>rational</span> <span m=''789170''>number</span>
  <span m=''790740''>representation</span> <span m=''791490''>that</span> <span m=''791610''>we</span>
  <span m=''791710''>looked</span> <span m=''791930''>at</span> <span m=''792060''>last</span>
  <span m=''792360''>time.</span> <span m=''792510''>It''s</span> <span m=''792840''>the</span>
  <span m=''792980''>same</span> <span m=''793260''>sort</span> <span m=''793420''>of</span>
  <span m=''793590''>idea.</span> <span m=''793910''>You</span> <span m=''794200''>implement</span>
  <span m=''794380''>the</span> <span m=''794500''>operators,</span> <span m=''795040''>you</span>
  <span m=''795130''>pick</span> <span m=''795320''>a</span> <span m=''795380''>representation.</span>
  <span m=''798070''>Nothing</span> <span m=''798410''>different.</span> </p><p><span
  m=''800070''>Now</span> <span m=''800600''>let''s</span> <span m=''800790''>worry</span>
  <span m=''801030''>about</span> <span m=''801250''>Martha.</span> <span m=''803210''>See,</span>
  <span m=''803370''>Martha</span> <span m=''803680''>has</span> <span m=''803890''>a</span>
  <span m=''803910''>different</span> <span m=''804210''>idea.</span> <span m=''806670''>She</span>
  <span m=''806820''>doesn''t</span> <span m=''807060''>want</span> <span m=''807420''>to</span>
  <span m=''807480''>represent</span> <span m=''807890''>a</span> <span m=''807950''>complex</span>
  <span m=''808410''>number as</span> <span m=''808780''>a pair</span> <span m=''809310''>of</span>
  <span m=''809490''>a</span> <span m=''809590''>real-part and an</span> <span m=''810180''>imaginary-part.</span>
  <span m=''810900''>What</span> <span m=''811020''>she</span> <span m=''811210''>would</span>
  <span m=''811340''>like</span> <span m=''811530''>to</span> <span m=''811650''>do</span>
  <span m=''812260''>is</span> <span m=''812390''>represent</span> <span m=''812820''>a</span>
  <span m=''812880''>complex</span> <span m=''813350''>number</span> <span m=''813980''>as</span>
  <span m=''814170''>a</span> <span m=''814220''>pair</span> <span m=''815520''>of</span>
  <span m=''816330''>a</span> <span m=''816440''>magnitude</span> <span m=''817090''>and</span>
  <span m=''817220''>an</span> <span m=''817310''>angle.</span> <span m=''819550''>So
  if</span> <span m=''819900''>instead</span> <span m=''820230''>of</span> <span m=''820300''>calling</span>
  <span m=''820630''>up</span> <span m=''820750''>George</span> <span m=''821050''>we</span>
  <span m=''821210''>ask</span> <span m=''821360''>Martha</span> <span m=''821720''>to</span>
  <span m=''821810''>design</span> <span m=''822130''>our</span> <span m=''822230''>representation,</span>
  <span m=''822910''>we</span> <span m=''822960''>get</span> <span m=''823130''>something</span>
  <span m=''823380''>like</span> <span m=''823620''>this.</span> <span m=''824570''>We</span>
  <span m=''824690''>get</span> <span m=''826230''>make-polar.</span> <span m=''827160''>Sure,</span>
  <span m=''827440''>if</span> <span m=''827550''>I</span> <span m=''827620''>give</span>
  <span m=''827840''>you</span> <span m=''828020''>a</span> <span m=''828460''>magnitude</span>
  <span m=''829090''>and</span> <span m=''829160''>an</span> <span m=''829280''>angle</span>
  <span m=''830110''>we''re</span> <span m=''830220''>just</span> <span m=''830400''>going</span>
  <span m=''830470''>to</span> <span m=''830550''>form</span> <span m=''830810''>a</span>
  <span m=''830850''>pair</span> <span m=''831670''>that</span> <span m=''831860''>has</span>
  <span m=''832040''>magnitude and</span> <span m=''832520''>angle.</span> </p><p><span
  m=''835430''>If</span> <span m=''835550''>you</span> <span m=''835660''>want</span>
  <span m=''835790''>to</span> <span m=''835880''>extract</span> <span m=''836130''>the</span>
  <span m=''836210''>magnitude,</span> <span m=''836700''>that''s</span> <span m=''836920''>easy.</span>
  <span m=''837680''>You</span> <span m=''838040''>just</span> <span m=''838310''>pull</span>
  <span m=''838470''>out</span> <span m=''838580''>the</span> <span m=''838660''>car</span>
  <span m=''838950''>or the</span> <span m=''839070''>pair.</span> <span m=''839780''>If
  you</span> <span m=''839950''>want</span> <span m=''840120''>to extract</span> <span
  m=''840540''>the</span> <span m=''840670''>angle,</span> <span m=''842010''>sure,</span>
  <span m=''842230''>that''s</span> <span m=''842390''>easy.</span> <span m=''842670''>You
  just</span> <span m=''842840''>pull</span> <span m=''842990''>out</span> <span m=''843090''>the</span>
  <span m=''843180''>cdr.</span> <span m=''844770''>If</span> <span m=''844870''>you</span>
  <span m=''844990''>want</span> <span m=''845070''>to</span> <span m=''845160''>look</span>
  <span m=''845310''>for</span> <span m=''845480''>real-parts</span> <span m=''846050''>and</span>
  <span m=''846210''>imaginary-parts,</span> <span m=''847390''>well</span> <span
  m=''847530''>then you</span> <span m=''847660''>have</span> <span m=''847790''>to
  do</span> <span m=''847910''>some</span> <span m=''848090''>work.</span> <span m=''848590''>If</span>
  <span m=''848980''>you</span> <span m=''849100''>want</span> <span m=''849240''>the</span>
  <span m=''849330''>real-part,</span> <span m=''851400''>you</span> <span m=''851510''>have</span>
  <span m=''851670''>to</span> <span m=''851760''>get</span> <span m=''852950''>r</span>
  <span m=''853540''>cosine</span> <span m=''854150''>a.</span> <span m=''854580''>In
  other</span> <span m=''854780''>words,</span> <span m=''856010''>r,</span> <span
  m=''856390''>the</span> <span m=''856470''>car</span> <span m=''857250''>of</span>
  <span m=''857360''>the</span> <span m=''857470''>pair,</span> <span m=''858570''>times</span>
  <span m=''858840''>the</span> <span m=''858920''>cosine</span> <span m=''859880''>of</span>
  <span m=''859990''>the</span> <span m=''860100''>cdr of</span> <span m=''860420''>the</span>
  <span m=''860540''>pair.</span> <span m=''860910''>So</span> <span m=''862740''>this</span>
  <span m=''862940''>is</span> <span m=''863080''>r</span> <span m=''864450''>times</span>
  <span m=''864970''>the</span> <span m=''865130''>cosine</span> <span m=''865600''>of</span>
  <span m=''865640''>a,</span> <span m=''866230''>and</span> <span m=''866500''>that''s</span>
  <span m=''866860''>the</span> <span m=''866950''>real-part.</span> <span m=''868330''>If</span>
  <span m=''868430''>you</span> <span m=''868530''>want</span> <span m=''868590''>to</span>
  <span m=''868660''>get</span> <span m=''868780''>the</span> <span m=''868900''>imaginary-part,
  it''s</span> <span m=''869790''>r</span> <span m=''870350''>times</span> <span m=''870810''>the
  sine</span> <span m=''871020''>of</span> <span m=''871060''>a.</span> </p><p><span
  m=''872660''>And</span> <span m=''873570''>if</span> <span m=''873750''>I</span>
  <span m=''873840''>hand</span> <span m=''874200''>you</span> <span m=''874480''>a</span>
  <span m=''874620''>real-part</span> <span m=''875270''>and</span> <span m=''875760''>an</span>
  <span m=''875990''>imaginary-part</span> <span m=''877330''>and</span> <span m=''877540''>say,</span>
  <span m=''877930''>make</span> <span m=''878300''>me</span> <span m=''878750''>a</span>
  <span m=''878850''>complex</span> <span m=''879360''>number</span> <span m=''881160''>with</span>
  <span m=''881300''>that</span> <span m=''881510''>real-part and</span> <span m=''882030''>imaginary-part,</span>
  <span m=''882720''>well I</span> <span m=''882930''>figure</span> <span m=''883240''>out</span>
  <span m=''883340''>what</span> <span m=''883480''>the</span> <span m=''883560''>magnitude</span>
  <span m=''884070''>and</span> <span m=''884170''>angle</span> <span m=''884460''>should</span>
  <span m=''884650''>be.</span> <span m=''885540''>The</span> <span m=''885720''>magnitude''s</span>
  <span m=''886260''>the</span> <span m=''886340''>square</span> <span m=''886660''>root</span>
  <span m=''886830''>of</span> <span m=''886910''>the</span> <span m=''886980''>sum</span>
  <span m=''887200''>of</span> <span m=''887260''>the</span> <span m=''887320''>squares</span>
  <span m=''888090''>and</span> <span m=''888240''>the angle''s</span> <span m=''888600''>the</span>
  <span m=''888690''>arctangent.</span> <span m=''889230''>I</span> <span m=''889290''>put</span>
  <span m=''889480''>those</span> <span m=''889650''>together</span> <span m=''889950''>to</span>
  <span m=''890040''>make</span> <span m=''890210''>a pair.</span> <span m=''892090''>So</span>
  <span m=''892260''>there''s</span> <span m=''893310''>Martha''s</span> <span m=''893750''>idea.</span>
  </p><p><span m=''896690''>Well</span> <span m=''896800''>which</span> <span m=''897000''>is</span>
  <span m=''897130''>better?</span> <span m=''899680''>Well</span> <span m=''900590''>if</span>
  <span m=''900710''>you''re</span> <span m=''900880''>doing</span> <span m=''901150''>a</span>
  <span m=''901200''>lot</span> <span m=''901400''>of</span> <span m=''901480''>additions,</span>
  <span m=''901990''>probably</span> <span m=''902430''>George''s</span> <span m=''902850''>is</span>
  <span m=''902980''>better,</span> <span m=''903270''>because</span> <span m=''903600''>you''re</span>
  <span m=''903700''>doing</span> <span m=''903910''>a</span> <span m=''903960''>lot</span>
  <span m=''904140''>of</span> <span m=''904260''>real-parts</span> <span m=''904710''>and</span>
  <span m=''904810''>imaginary-parts.</span> <span m=''905850''>If</span> <span m=''906010''>mostly</span>
  <span m=''906520''>you''re</span> <span m=''906840''>going to be</span> <span m=''907070''>doing</span>
  <span m=''907250''>multiplications</span> <span m=''907810''>and</span> <span m=''907920''>divisions,</span>
  <span m=''909570''>then</span> <span m=''909720''>maybe</span> <span m=''909940''>Martha''s</span>
  <span m=''910330''>idea is</span> <span m=''910730''>better.</span> <span m=''911140''>Or</span>
  <span m=''911300''>maybe,</span> <span m=''911790''>and</span> <span m=''911950''>this</span>
  <span m=''912110''>is</span> <span m=''912240''>the</span> <span m=''912350''>real</span>
  <span m=''912570''>point,</span> <span m=''913930''>you</span> <span m=''914040''>can''t</span>
  <span m=''914310''>decide.</span> <span m=''916590''>Or</span> <span m=''916760''>maybe</span>
  <span m=''918540''>you</span> <span m=''918650''>just</span> <span m=''918840''>have</span>
  <span m=''918950''>to</span> <span m=''919070''>let</span> <span m=''919230''>them</span>
  <span m=''919350''>both</span> <span m=''919570''>hang around,</span> <span m=''921040''>for</span>
  <span m=''921170''>personality</span> <span m=''921830''>reasons.</span> <span m=''923480''>Maybe</span>
  <span m=''923740''>you</span> <span m=''923850''>just</span> <span m=''924070''>really</span>
  <span m=''924770''>can''t</span> <span m=''925090''>ever</span> <span m=''925310''>decide</span>
  <span m=''925870''>what</span> <span m=''926040''>you</span> <span m=''926210''>would</span>
  <span m=''926360''>like.</span> </p><p><span m=''928560''>And again,</span> <span
  m=''928890''>what we would</span> <span m=''929120''>really</span> <span m=''929620''>like</span>
  <span m=''930300''>is</span> <span m=''930460''>a</span> <span m=''930510''>system</span>
  <span m=''931050''>that</span> <span m=''931520''>looks</span> <span m=''931740''>like</span>
  <span m=''931980''>this.</span> <span m=''932320''>That</span> <span m=''933340''>somehow</span>
  <span m=''933900''>there''s</span> <span m=''934360''>George</span> <span m=''934720''>over</span>
  <span m=''934910''>here,</span> <span m=''935390''>who</span> <span m=''935840''>has</span>
  <span m=''935980''>built</span> <span m=''937090''>rectangular</span> <span m=''938550''>complex</span>
  <span m=''939100''>numbers.</span> <span m=''941470''>And</span> <span m=''941630''>Martha,</span>
  <span m=''942520''>who</span> <span m=''942700''>has</span> <span m=''942880''>polar</span>
  <span m=''943260''>complex</span> <span m=''943750''>numbers.</span> <span m=''946120''>And</span>
  <span m=''947380''>somehow</span> <span m=''948580''>we</span> <span m=''948700''>have</span>
  <span m=''948900''>operations</span> <span m=''950340''>that</span> <span m=''950600''>can</span>
  <span m=''950860''>add,</span> <span m=''952790''>and</span> <span m=''952990''>subtract,</span>
  <span m=''954200''>and</span> <span m=''954660''>multiply,</span> <span m=''956040''>and</span>
  <span m=''956230''>divide,</span> <span m=''957560''>and</span> <span m=''957730''>it</span>
  <span m=''957830''>shouldn''t</span> <span m=''958320''>matter</span> <span m=''959420''>that</span>
  <span m=''959620''>there</span> <span m=''959710''>are</span> <span m=''959760''>two</span>
  <span m=''960020''>incompatible</span> <span m=''960810''>representations</span>
  <span m=''962090''>of</span> <span m=''962320''>complex</span> <span m=''962790''>numbers</span>
  <span m=''963070''>floating</span> <span m=''963390''>around</span> <span m=''963640''>this</span>
  <span m=''963720''>system.</span> </p><p><span m=''964410''>In</span> <span m=''964480''>other</span>
  <span m=''964620''>words,</span> <span m=''964810''>not</span> <span m=''965040''>only</span>
  <span m=''966680''>like</span> <span m=''966910''>an</span> <span m=''966990''>abstraction</span>
  <span m=''967600''>barrier</span> <span m=''968010''>here</span> <span m=''969640''>that</span>
  <span m=''969720''>has</span> <span m=''970020''>things</span> <span m=''970240''>in</span>
  <span m=''970400''>it</span> <span m=''970800''>like</span> <span m=''971080''>a</span>
  <span m=''971130''>real-part,</span> <span m=''975640''>and an</span> <span m=''975770''>imaginary-part,</span>
  <span m=''978600''>and</span> <span m=''978770''>magnitude,</span> <span m=''980990''>and</span>
  <span m=''981160''>angle.</span> <span m=''983830''>So</span> <span m=''983980''>not</span>
  <span m=''984180''>only</span> <span m=''984350''>is</span> <span m=''984430''>there</span>
  <span m=''984540''>an</span> <span m=''984610''>abstraction</span> <span m=''985150''>barrier</span>
  <span m=''985480''>that</span> <span m=''985630''>hides</span> <span m=''986850''>the</span>
  <span m=''987000''>actual</span> <span m=''987300''>representation</span> <span
  m=''987980''>from</span> <span m=''988230''>us,</span> <span m=''989160''>but</span>
  <span m=''989340''>also</span> <span m=''989770''>there''s</span> <span m=''989960''>some</span>
  <span m=''990100''>kind</span> <span m=''990310''>of</span> <span m=''990380''>vertical</span>
  <span m=''990770''>barrier</span> <span m=''991180''>here</span> <span m=''991970''>that</span>
  <span m=''992380''>allows</span> <span m=''992940''>both</span> <span m=''993340''>of</span>
  <span m=''993430''>these</span> <span m=''993620''>representations</span> <span
  m=''994540''>to</span> <span m=''994730''>exist</span> <span m=''996000''>without</span>
  <span m=''996270''>interfering</span> <span m=''996760''>with</span> <span m=''996890''>each</span>
  <span m=''997050''>other.</span> </p><p><span m=''998570''>The</span> <span m=''998720''>idea</span>
  <span m=''999050''>is</span> <span m=''999240''>that</span> <span m=''999540''>the</span>
  <span m=''1000220''>things</span> <span m=''1000620''>in</span> <span m=''1000730''>here--</span>
  <span m=''1001900''>real-part,</span> <span m=''1002350''>imaginary-part,</span>
  <span m=''1003070''>magnitude, and</span> <span m=''1003490''>angle--</span> <span
  m=''1004120''>will</span> <span m=''1004320''>be</span> <span m=''1004480''>generic</span>
  <span m=''1005760''>operators.</span> <span m=''1007310''>If</span> <span m=''1007450''>you</span>
  <span m=''1007560''>ask</span> <span m=''1007810''>for</span> <span m=''1007890''>the</span>
  <span m=''1008010''>real-part,</span> <span m=''1008500''>it</span> <span m=''1008670''>will</span>
  <span m=''1008800''>worry</span> <span m=''1009150''>about</span> <span m=''1009870''>what</span>
  <span m=''1010190''>representation</span> <span m=''1010920''>it''s</span> <span
  m=''1011060''>looking</span> <span m=''1011370''>at.</span> </p><p><span m=''1013880''>OK,
  well</span> <span m=''1014060''>how</span> <span m=''1014240''>can</span> <span
  m=''1014350''>we</span> <span m=''1014460''>do</span> <span m=''1014640''>that?</span>
  <span m=''1016840''>There''s</span> <span m=''1017780''>actually a</span> <span
  m=''1018140''>really</span> <span m=''1018480''>obvious</span> <span m=''1018910''>idea,</span>
  <span m=''1019850''>if</span> <span m=''1020000''>you''re</span> <span m=''1020100''>used</span>
  <span m=''1020290''>to</span> <span m=''1020380''>thinking</span> <span m=''1020710''>about</span>
  <span m=''1020960''>complex</span> <span m=''1021450''>numbers.</span> <span m=''1022770''>If</span>
  <span m=''1022900''>you''re</span> <span m=''1022980''>used</span> <span m=''1023170''>to</span>
  <span m=''1023250''>thinking</span> <span m=''1023530''>about</span> <span m=''1023740''>compound</span>
  <span m=''1024200''>data.</span> <span m=''1026390''>See,</span> <span m=''1026520''>suppose</span>
  <span m=''1027250''>you</span> <span m=''1027390''>could</span> <span m=''1027530''>just</span>
  <span m=''1027760''>tell</span> <span m=''1029140''>by</span> <span m=''1029280''>looking</span>
  <span m=''1029990''>at</span> <span m=''1030130''>a</span> <span m=''1030180''>complex</span>
  <span m=''1030690''>number</span> <span m=''1032230''>whether</span> <span m=''1032470''>it</span>
  <span m=''1032569''>was</span> <span m=''1032660''>constructed</span> <span m=''1033190''>by</span>
  <span m=''1033339''>George</span> <span m=''1033660''>or</span> <span m=''1033760''>Martha.</span>
  <span m=''1035790''>In</span> <span m=''1035980''>other words,</span> <span m=''1037060''>so</span>
  <span m=''1037210''>it''s</span> <span m=''1037339''>not</span> <span m=''1037859''>that</span>
  <span m=''1038170''>what''s</span> <span m=''1038339''>floating</span> <span m=''1038630''>around</span>
  <span m=''1038900''>here are</span> <span m=''1039150''>ordinary,</span> <span m=''1039650''>just</span>
  <span m=''1039859''>complex</span> <span m=''1040300''>numbers,</span> <span m=''1040550''>right?</span>
  <span m=''1040910''>They''re</span> <span m=''1041250''>fancy,</span> <span m=''1041670''>designer</span>
  <span m=''1042180''>complex</span> <span m=''1042660''>numbers.</span> </p><p><span
  m=''1044390''>So</span> <span m=''1044579''>you</span> <span m=''1044730''>look</span>
  <span m=''1044819''>at</span> <span m=''1044910''>a</span> <span m=''1044960''>complex</span>
  <span m=''1045410''>numbers</span> <span m=''1045740''>as</span> <span m=''1046700''>it''s</span>
  <span m=''1046880''>not</span> <span m=''1047030''>just</span> <span m=''1047210''>a</span>
  <span m=''1047260''>complex</span> <span m=''1047690''>number, it''s</span> <span
  m=''1048030''>got</span> <span m=''1048109''>a</span> <span m=''1048190''>label</span>
  <span m=''1048530''>on</span> <span m=''1048690''>it</span> <span m=''1048910''>that
  says,</span> <span m=''1049020''>this</span> <span m=''1049190''>one</span> <span
  m=''1049330''>is</span> <span m=''1049810''>by</span> <span m=''1050150''>Martha.</span>
  <span m=''1051450''>Or</span> <span m=''1051660''>this</span> <span m=''1051840''>is</span>
  <span m=''1051920''>a</span> <span m=''1051980''>complex</span> <span m=''1052450''>number</span>
  <span m=''1053440''>by</span> <span m=''1053700''>George.</span> <span m=''1054480''>Right?</span>
  <span m=''1054700''>They''re</span> <span m=''1054830''>signed.</span> <span m=''1056860''>See,</span>
  <span m=''1056930''>and</span> <span m=''1057170''>then</span> <span m=''1058730''>whenever</span>
  <span m=''1059000''>we</span> <span m=''1059130''>looked</span> <span m=''1059330''>at</span>
  <span m=''1059390''>a</span> <span m=''1059440''>complex</span> <span m=''1059890''>number</span>
  <span m=''1060090''>we could</span> <span m=''1060220''>just</span> <span m=''1060460''>read</span>
  <span m=''1060650''>the</span> <span m=''1060730''>label,</span> <span m=''1062490''>and</span>
  <span m=''1062720''>then we''d</span> <span m=''1062840''>know</span> <span m=''1064640''>how</span>
  <span m=''1064750''>you</span> <span m=''1064900''>expect</span> <span m=''1065800''>to</span>
  <span m=''1065930''>operate</span> <span m=''1066330''>on</span> <span m=''1066490''>that.</span>
  <span m=''1068030''>In other</span> <span m=''1068270''>words,</span> <span m=''1068340''>what</span>
  <span m=''1068470''>we</span> <span m=''1068570''>want</span> <span m=''1069260''>is</span>
  <span m=''1069420''>not</span> <span m=''1069640''>just</span> <span m=''1069850''>ordinary</span>
  <span m=''1070260''>data</span> <span m=''1070670''>objects.</span> <span m=''1071190''>We
  want to</span> <span m=''1071430''>introduce</span> <span m=''1071890''>the</span>
  <span m=''1071970''>notion</span> <span m=''1072810''>of</span> <span m=''1072940''>what''s</span>
  <span m=''1073120''>called</span> <span m=''1073340''>typed</span> <span m=''1073860''>data.</span>
  <span m=''1079760''>Typed</span> <span m=''1080120''>data</span> <span m=''1080720''>means,</span>
  <span m=''1081320''>again,</span> <span m=''1081680''>there''s</span> <span m=''1081830''>some</span>
  <span m=''1081960''>sort</span> <span m=''1082100''>of</span> <span m=''1082230''>cloud.</span>
  <span m=''1083940''>And</span> <span m=''1084120''>what</span> <span m=''1084250''>it''s</span>
  <span m=''1084410''>got in</span> <span m=''1084790''>it</span> <span m=''1085400''>is</span>
  <span m=''1087340''>an</span> <span m=''1087460''>ordinary</span> <span m=''1087950''>data</span>
  <span m=''1088210''>object</span> <span m=''1088770''>like</span> <span m=''1088930''>we''ve</span>
  <span m=''1089050''>been</span> <span m=''1089200''>thinking</span> <span m=''1089510''>about.</span>
  <span m=''1093180''>Pulled</span> <span m=''1093280''>out</span> <span m=''1093430''>the</span>
  <span m=''1093520''>contents,</span> <span m=''1095020''>sort of</span> <span m=''1095470''>the</span>
  <span m=''1095650''>actual</span> <span m=''1096140''>data.</span> <span m=''1099320''>But</span>
  <span m=''1099540''>also</span> <span m=''1100440''>a</span> <span m=''1100620''>thing</span>
  <span m=''1100790''>called</span> <span m=''1100900''>a</span> <span m=''1101020''>type,</span>
  <span m=''1102570''>but</span> <span m=''1103320''>it''s</span> <span m=''1103540''>signed</span>
  <span m=''1104050''>by</span> <span m=''1104220''>either</span> <span m=''1104480''>George</span>
  <span m=''1104790''>or</span> <span m=''1104840''>Martha.</span> <span m=''1105850''>So</span>
  <span m=''1106080''>we''re going to</span> <span m=''1106280''>go</span> <span m=''1106420''>from</span>
  <span m=''1106590''>regular</span> <span m=''1106940''>data</span> <span m=''1107420''>to</span>
  <span m=''1107600''>type</span> <span m=''1107990''>data.</span> </p><p><span m=''1111950''>How</span>
  <span m=''1112070''>do</span> <span m=''1112120''>we</span> <span m=''1112300''>build</span>
  <span m=''1112460''>that?</span> <span m=''1112710''>Well</span> <span m=''1112830''>that''s</span>
  <span m=''1113030''>easy.</span> <span m=''1113990''>We</span> <span m=''1114090''>know</span>
  <span m=''1114350''>how to build</span> <span m=''1114530''>clouds.</span> <span
  m=''1114980''>We</span> <span m=''1115950''>build them</span> <span m=''1116210''>out
  of</span> <span m=''1116380''>pairs.</span> <span m=''1117920''>So</span> <span
  m=''1118110''>here''s</span> <span m=''1118330''>a</span> <span m=''1118950''>little</span>
  <span m=''1119130''>representation</span> <span m=''1119900''>that</span> <span
  m=''1120060''>supports</span> <span m=''1121050''>typed</span> <span m=''1121370''>data.</span>
  <span m=''1123510''>There''s</span> <span m=''1123960''>a</span> <span m=''1124020''>thing</span>
  <span m=''1124180''>called</span> <span m=''1125810''>take</span> <span m=''1126030''>a</span>
  <span m=''1126110''>type</span> <span m=''1127080''>and</span> <span m=''1127420''>attach</span>
  <span m=''1127920''>it</span> <span m=''1128590''>to</span> <span m=''1128690''>a</span>
  <span m=''1128800''>piece</span> <span m=''1129020''>of</span> <span m=''1129120''>contents,</span>
  <span m=''1129710''>and</span> <span m=''1129790''>we</span> <span m=''1129900''>just</span>
  <span m=''1130120''>use</span> <span m=''1130310''>cons.</span> <span m=''1131530''>And</span>
  <span m=''1131880''>if</span> <span m=''1132040''>we</span> <span m=''1132170''>have</span>
  <span m=''1132310''>a</span> <span m=''1132360''>piece</span> <span m=''1132580''>of</span>
  <span m=''1132670''>typed</span> <span m=''1133000''>data,</span> <span m=''1133190''>we</span>
  <span m=''1133290''>can</span> <span m=''1133440''>look</span> <span m=''1133610''>at</span>
  <span m=''1133670''>the</span> <span m=''1133770''>type,</span> <span m=''1135300''>which</span>
  <span m=''1135470''>is</span> <span m=''1135570''>the</span> <span m=''1135660''>car.</span>
  <span m=''1136290''>We</span> <span m=''1136450''>can</span> <span m=''1136600''>look</span>
  <span m=''1136700''>at</span> <span m=''1136810''>the</span> <span m=''1136890''>contents,</span>
  <span m=''1137420''>which</span> <span m=''1137590''>is</span> <span m=''1137710''>the</span>
  <span m=''1137790''>cdr.</span> <span m=''1140020''>Now</span> <span m=''1140180''>along</span>
  <span m=''1140460''>with</span> <span m=''1140590''>that,</span> <span m=''1140850''>the
  way</span> <span m=''1141010''>we</span> <span m=''1141130''>use</span> <span m=''1141400''>our</span>
  <span m=''1141530''>type</span> <span m=''1141820''>data</span> <span m=''1143730''>will</span>
  <span m=''1143890''>test,</span> <span m=''1145290''>when</span> <span m=''1145420''>we''re</span>
  <span m=''1145530''>given</span> <span m=''1145770''>a</span> <span m=''1145820''>piece</span>
  <span m=''1146060''>of</span> <span m=''1146140''>data,</span> <span m=''1146380''>what</span>
  <span m=''1146550''>type</span> <span m=''1146820''>it</span> <span m=''1147040''>is.</span>
  <span m=''1147520''>So</span> <span m=''1147660''>we</span> <span m=''1147760''>have</span>
  <span m=''1147910''>some</span> <span m=''1148080''>type</span> <span m=''1148400''>predicates</span>
  <span m=''1148900''>with</span> <span m=''1149060''>us.</span> </p><p><span m=''1150510''>For</span>
  <span m=''1150760''>example,</span> <span m=''1151170''>to</span> <span m=''1151240''>see</span>
  <span m=''1152060''>whether</span> <span m=''1152410''>a</span> <span m=''1152460''>complex</span>
  <span m=''1152980''>number</span> <span m=''1153310''>is</span> <span m=''1153470''>one</span>
  <span m=''1153630''>of</span> <span m=''1153730''>George''s,</span> <span m=''1154360''>whether</span>
  <span m=''1154580''>it''s</span> <span m=''1154690''>rectangular,</span> <span m=''1155840''>we</span>
  <span m=''1156020''>just</span> <span m=''1156300''>check</span> <span m=''1156750''>to</span>
  <span m=''1156860''>see</span> <span m=''1158170''>if</span> <span m=''1158340''>the</span>
  <span m=''1158440''>type</span> <span m=''1158750''>of</span> <span m=''1158850''>that</span>
  <span m=''1159970''>is</span> <span m=''1160680''>the</span> <span m=''1160850''>symbol</span>
  <span m=''1161200''>rectangular,</span> <span m=''1163670''>right?</span> <span
  m=''1163850''>The</span> <span m=''1163930''>symbol</span> <span m=''1164320''>rectangular.</span>
  <span m=''1167200''>And</span> <span m=''1167370''>to</span> <span m=''1167470''>check</span>
  <span m=''1168310''>whether</span> <span m=''1168610''>a</span> <span m=''1168660''>complex</span>
  <span m=''1169150''>number</span> <span m=''1169460''>is</span> <span m=''1169830''>one</span>
  <span m=''1169990''>of</span> <span m=''1170060''>Martha''s,</span> <span m=''1170520''>we</span>
  <span m=''1170650''>check</span> <span m=''1170930''>to</span> <span m=''1171020''>see</span>
  <span m=''1171410''>whether</span> <span m=''1171640''>the</span> <span m=''1171780''>type</span>
  <span m=''1172410''>is</span> <span m=''1172600''>the</span> <span m=''1172680''>symbol</span>
  <span m=''1173030''>polar.</span> <span m=''1176460''>So</span> <span m=''1176630''>that''s</span>
  <span m=''1176820''>a</span> <span m=''1176860''>way</span> <span m=''1176970''>to</span>
  <span m=''1177090''>test</span> <span m=''1177740''>what</span> <span m=''1178100''>kind</span>
  <span m=''1178280''>of</span> <span m=''1178460''>number</span> <span m=''1178710''>we''re</span>
  <span m=''1178850''>looking</span> <span m=''1179210''>at.</span> </p><p><span m=''1180350''>Now</span>
  <span m=''1180810''>let''s</span> <span m=''1181050''>think</span> <span m=''1181190''>about</span>
  <span m=''1181350''>how</span> <span m=''1181420''>we</span> <span m=''1181520''>can</span>
  <span m=''1181650''>use</span> <span m=''1181900''>that</span> <span m=''1182070''>to</span>
  <span m=''1182160''>build</span> <span m=''1182370''>the</span> <span m=''1182430''>system.</span>
  <span m=''1183870''>So</span> <span m=''1184030''>let''s</span> <span m=''1184200''>suppose</span>
  <span m=''1184650''>that</span> <span m=''1184790''>George</span> <span m=''1185080''>and</span>
  <span m=''1185170''>Martha</span> <span m=''1185510''>were off</span> <span m=''1185840''>working</span>
  <span m=''1186170''>separately,</span> <span m=''1187450''>and</span> <span m=''1187610''>each</span>
  <span m=''1187840''>of</span> <span m=''1187920''>them</span> <span m=''1188050''>had</span>
  <span m=''1188230''>designed</span> <span m=''1189130''>their</span> <span m=''1190110''>complex</span>
  <span m=''1190710''>number</span> <span m=''1191030''>representation</span> <span
  m=''1191900''>packages.</span> <span m=''1192640''>What</span> <span m=''1192740''>do</span>
  <span m=''1192850''>they</span> <span m=''1193020''>have</span> <span m=''1193180''>to</span>
  <span m=''1193280''>do</span> <span m=''1197300''>to</span> <span m=''1197610''>become</span>
  <span m=''1197910''>part</span> <span m=''1198070''>of</span> <span m=''1198220''>the</span>
  <span m=''1198300''>system,</span> <span m=''1198790''>to</span> <span m=''1198980''>exist</span>
  <span m=''1199280''>compatibly?</span> <span m=''1200140''>Well</span> <span m=''1201230''>it''s</span>
  <span m=''1201320''>really</span> <span m=''1201510''>pretty</span> <span m=''1201760''>easy.</span>
  <span m=''1202860''>Remember,</span> <span m=''1203020''>George</span> <span m=''1203350''>had</span>
  <span m=''1203520''>this</span> <span m=''1203700''>package.</span> <span m=''1205970''>Here''s</span>
  <span m=''1206170''>George''s</span> <span m=''1206520''>original</span> <span m=''1206920''>package,</span>
  <span m=''1207490''>or</span> <span m=''1207850''>half</span> <span m=''1208160''>of</span>
  <span m=''1208270''>it.</span> <span m=''1208980''>And</span> <span m=''1209220''>underlined</span>
  <span m=''1209690''>in</span> <span m=''1209760''>red</span> <span m=''1209980''>are</span>
  <span m=''1210040''>the</span> <span m=''1210160''>changes</span> <span m=''1210570''>he</span>
  <span m=''1210660''>has</span> <span m=''1210850''>to make.</span> <span m=''1212090''>So</span>
  <span m=''1212320''>before,</span> <span m=''1213290''>when</span> <span m=''1213480''>George</span>
  <span m=''1214070''>made</span> <span m=''1214450''>a</span> <span m=''1214510''>complex</span>
  <span m=''1215020''>number</span> <span m=''1215380''>out</span> <span m=''1215500''>of</span>
  <span m=''1215600''>an</span> <span m=''1215700''>x</span> <span m=''1215910''>and</span>
  <span m=''1216010''>y,</span> <span m=''1217470''>he</span> <span m=''1217720''>just</span>
  <span m=''1218380''>put</span> <span m=''1218540''>them</span> <span m=''1218660''>together</span>
  <span m=''1219010''>to</span> <span m=''1219090''>make</span> <span m=''1219280''>a
  pair.</span> <span m=''1220930''>And</span> <span m=''1221040''>the</span> <span
  m=''1221140''>only</span> <span m=''1221330''>difference</span> <span m=''1221760''>is</span>
  <span m=''1221890''>that</span> <span m=''1222370''>now</span> <span m=''1222600''>he</span>
  <span m=''1222710''>signs</span> <span m=''1223130''>them.</span> <span m=''1224090''>He</span>
  <span m=''1224230''>attaches</span> <span m=''1225060''>the</span> <span m=''1225250''>type,</span>
  <span m=''1226200''>which</span> <span m=''1226400''>is</span> <span m=''1226500''>the</span>
  <span m=''1226580''>symbol</span> <span m=''1226920''>rectangular</span> <span m=''1227550''>to</span>
  <span m=''1227650''>that</span> <span m=''1227880''>pair.</span> </p><p><span m=''1230600''>Everything</span>
  <span m=''1231010''>else</span> <span m=''1231220''>George</span> <span m=''1231490''>does</span>
  <span m=''1231680''>is</span> <span m=''1231780''>the</span> <span m=''1231850''>same,</span>
  <span m=''1232420''>except</span> <span m=''1232940''>that--</span> <span m=''1233920''>see,</span>
  <span m=''1234140''>George</span> <span m=''1234460''>and</span> <span m=''1234550''>Martha</span>
  <span m=''1234840''>both</span> <span m=''1235120''>have</span> <span m=''1235230''>procedures</span>
  <span m=''1235750''>named</span> <span m=''1235970''>real-part</span> <span m=''1236940''>and</span>
  <span m=''1237100''>imaginary-part.</span> <span m=''1238700''>So</span> <span m=''1238870''>to</span>
  <span m=''1238980''>allow</span> <span m=''1239270''>them</span> <span m=''1239430''>both</span>
  <span m=''1239730''>to</span> <span m=''1240080''>exist</span> <span m=''1240540''>in</span>
  <span m=''1240650''>the</span> <span m=''1240720''>same</span> <span m=''1241920''>Lisp</span>
  <span m=''1242270''>environment,</span> <span m=''1244220''>George had</span> <span
  m=''1244580''>changed the</span> <span m=''1244940''>names</span> <span m=''1245210''>of</span>
  <span m=''1245310''>his</span> <span m=''1245400''>procedures.</span> <span m=''1245920''>So</span>
  <span m=''1246680''>we''ll</span> <span m=''1246780''>say,</span> <span m=''1247180''>this</span>
  <span m=''1247620''>is</span> <span m=''1247820''>George''s</span> <span m=''1248320''>real-part</span>
  <span m=''1248760''>procedure.</span> <span m=''1249045''>It''s</span> <span m=''1249330''>the</span>
  <span m=''1249480''>real-part</span> <span m=''1249890''>rectangular</span> <span
  m=''1250520''>procedure,</span> <span m=''1251090''>the</span> <span m=''1251760''>imaginary-part</span>
  <span m=''1252710''>rectangular</span> <span m=''1253360''>procedure.</span> <span
  m=''1255170''>And then</span> <span m=''1255580''>here''s</span> <span m=''1255830''>the</span>
  <span m=''1255930''>rest</span> <span m=''1256200''>of</span> <span m=''1256290''>George''s</span>
  <span m=''1256680''>package.</span> <span m=''1259130''>He''d</span> <span m=''1259400''>had</span>
  <span m=''1259630''>magnitude</span> <span m=''1260130''>and</span> <span m=''1260210''>angle,</span>
  <span m=''1260860''>just</span> <span m=''1261010''>renames</span> <span m=''1261470''>them</span>
  <span m=''1261560''>magnitude</span> <span m=''1262060''>rectangular</span> <span
  m=''1262970''>and</span> <span m=''1263130''>angle</span> <span m=''1263520''>rectangular.</span>
  </p><p><span m=''1265702''>And</span> <span m=''1266120''>Martha</span> <span m=''1266530''>has</span>
  <span m=''1266660''>to</span> <span m=''1266750''>do</span> <span m=''1266870''>basically</span>
  <span m=''1267330''>the</span> <span m=''1267410''>same</span> <span m=''1267660''>thing.</span>
  <span m=''1269860''>Martha</span> <span m=''1270230''>previously,</span> <span m=''1271890''>when</span>
  <span m=''1272080''>she</span> <span m=''1272250''>made</span> <span m=''1274200''>a</span>
  <span m=''1274290''>complex</span> <span m=''1274750''>number</span> <span m=''1274960''>out</span>
  <span m=''1275090''>of</span> <span m=''1275150''>a</span> <span m=''1275200''>magnitude</span>
  <span m=''1275720''>and</span> <span m=''1275830''>angle,</span> <span m=''1278220''>she</span>
  <span m=''1278410''>just</span> <span m=''1278630''>cons them.</span> <span m=''1279270''>Now</span>
  <span m=''1279420''>she</span> <span m=''1279590''>attaches</span> <span m=''1280050''>the</span>
  <span m=''1280150''>type</span> <span m=''1280340''>polar,</span> <span m=''1284010''>and</span>
  <span m=''1284280''>she</span> <span m=''1284830''>changes</span> <span m=''1285250''>the</span>
  <span m=''1285330''>name</span> <span m=''1285600''>so</span> <span m=''1285740''>her</span>
  <span m=''1285910''>real-part</span> <span m=''1286410''>procedure</span> <span
  m=''1286810''>won''t</span> <span m=''1287140''>conflict</span> <span m=''1287760''>in</span>
  <span m=''1288100''>name</span> <span m=''1289260''>with</span> <span m=''1289410''>George''s.</span>
  <span m=''1290710''>It''s</span> <span m=''1290910''>a</span> <span m=''1290990''>real-part-polar,</span>
  <span m=''1291760''>imaginary-part-polar,</span> <span m=''1294540''>magnitude</span>
  <span m=''1295150''>polar,</span> <span m=''1296810''>and</span> <span m=''1297350''>angle</span>
  <span m=''1297670''>polar.</span> </p><p><span m=''1305000''>Now</span> <span m=''1305110''>we</span>
  <span m=''1305200''>have</span> <span m=''1305330''>the</span> <span m=''1305410''>system.</span>
  <span m=''1306130''>Right</span> <span m=''1306750''>there''s</span> <span m=''1307010''>George</span>
  <span m=''1307330''>and</span> <span m=''1307430''>Martha.</span> <span m=''1309160''>And</span>
  <span m=''1309310''>now</span> <span m=''1309460''>we''ve</span> <span m=''1309610''>got</span>
  <span m=''1309690''>to</span> <span m=''1309780''>get</span> <span m=''1309950''>some</span>
  <span m=''1310080''>kind</span> <span m=''1310180''>of</span> <span m=''1310290''>manager</span>
  <span m=''1310730''>to</span> <span m=''1310800''>look</span> <span m=''1310920''>at</span>
  <span m=''1311050''>these</span> <span m=''1311260''>types.</span> <span m=''1315050''>How
  are</span> <span m=''1315260''>these things</span> <span m=''1315460''>actually</span>
  <span m=''1315820''>going</span> <span m=''1315910''>to</span> <span m=''1316000''>work</span>
  <span m=''1316310''>now</span> <span m=''1317110''>that</span> <span m=''1317290''>George</span>
  <span m=''1317530''>and</span> <span m=''1317620''>Martha</span> <span m=''1317890''>have</span>
  <span m=''1318040''>supplied us</span> <span m=''1318520''>with</span> <span m=''1318650''>typed</span>
  <span m=''1319030''>data?</span> <span m=''1320530''>Well</span> <span m=''1320680''>what</span>
  <span m=''1320790''>we</span> <span m=''1321020''>have</span> <span m=''1321540''>are</span>
  <span m=''1321710''>a</span> <span m=''1321750''>bunch</span> <span m=''1322020''>of</span>
  <span m=''1322680''>generic</span> <span m=''1323280''>selectors.</span> <span m=''1325260''>Generic</span>
  <span m=''1325670''>selectors</span> <span m=''1326080''>for</span> <span m=''1326180''>complex</span>
  <span m=''1326640''>numbers</span> <span m=''1326930''>real-part,</span> <span m=''1327800''>imaginary-part,</span>
  <span m=''1328980''>magnitude,</span> <span m=''1330010''>and</span> <span m=''1330180''>angle.</span>
  <span m=''1334140''>Let''s</span> <span m=''1334390''>look</span> <span m=''1334500''>at</span>
  <span m=''1334610''>them</span> <span m=''1334690''>more</span> <span m=''1334910''>closely.</span>
  </p><p><span m=''1337930''>What</span> <span m=''1338060''>does a</span> <span m=''1338170''>real-part</span>
  <span m=''1338760''>do?</span> <span m=''1339310''>If</span> <span m=''1339490''>I</span>
  <span m=''1339600''>ask</span> <span m=''1340180''>for</span> <span m=''1340360''>the</span>
  <span m=''1340650''>real</span> <span m=''1340940''>part</span> <span m=''1341580''>of</span>
  <span m=''1341750''>a</span> <span m=''1341810''>complex</span> <span m=''1342340''>number,</span>
  <span m=''1344070''>well</span> <span m=''1344200''>I</span> <span m=''1344270''>look</span>
  <span m=''1344520''>at</span> <span m=''1344770''>it.</span> <span m=''1345800''>I</span>
  <span m=''1345970''>look</span> <span m=''1346080''>at</span> <span m=''1346190''>its</span>
  <span m=''1346370''>type.</span> <span m=''1346690''>I</span> <span m=''1346740''>say,</span>
  <span m=''1346940''>is</span> <span m=''1347150''>it</span> <span m=''1347270''>rectangular?</span>
  <span m=''1351020''>If</span> <span m=''1351200''>so,</span> <span m=''1352640''>I</span>
  <span m=''1352910''>apply</span> <span m=''1353770''>George''s</span> <span m=''1354240''>real</span>
  <span m=''1354470''>part</span> <span m=''1354710''>procedure</span> <span m=''1356080''>to</span>
  <span m=''1356240''>the</span> <span m=''1356350''>contents</span> <span m=''1356970''>of</span>
  <span m=''1357040''>that</span> <span m=''1357210''>complex</span> <span m=''1357680''>number.</span>
  <span m=''1361230''>This</span> <span m=''1361380''>is</span> <span m=''1361500''>a</span>
  <span m=''1361550''>number</span> <span m=''1361880''>that</span> <span m=''1362020''>has</span>
  <span m=''1362180''>a</span> <span m=''1362250''>type</span> <span m=''1362540''>on</span>
  <span m=''1362760''>it.</span> <span m=''1363720''>I</span> <span m=''1363870''>strip</span>
  <span m=''1364360''>off</span> <span m=''1364550''>the</span> <span m=''1364680''>type</span>
  <span m=''1364990''>using</span> <span m=''1365270''>contents</span> <span m=''1366210''>and</span>
  <span m=''1366340''>apply</span> <span m=''1366620''>George''s</span> <span m=''1367000''>procedure.</span>
  </p><p><span m=''1370700''>Or</span> <span m=''1371330''>is</span> <span m=''1371530''>this
  a</span> <span m=''1371580''>polar</span> <span m=''1372050''>complex</span> <span
  m=''1372540''>number?</span> <span m=''1373950''>If</span> <span m=''1374120''>I</span>
  <span m=''1374170''>want</span> <span m=''1374380''>the</span> <span m=''1374480''>real</span>
  <span m=''1374690''>part,</span> <span m=''1375520''>I</span> <span m=''1375680''>apply</span>
  <span m=''1375930''>Martha''s</span> <span m=''1376440''>real</span> <span m=''1376650''>part</span>
  <span m=''1376890''>procedure</span> <span m=''1377550''>to</span> <span m=''1377890''>the</span>
  <span m=''1377980''>contents</span> <span m=''1378450''>of</span> <span m=''1378520''>that</span>
  <span m=''1378710''>number.</span> <span m=''1379850''>So</span> <span m=''1379960''>that''s</span>
  <span m=''1380160''>how</span> <span m=''1380310''>real</span> <span m=''1380500''>part</span>
  <span m=''1380760''>works.</span> <span m=''1382260''>And</span> <span m=''1382470''>then</span>
  <span m=''1382590''>similarly</span> <span m=''1382820''>there''s</span> <span m=''1383540''>imaginary-part,</span>
  <span m=''1384420''>which</span> <span m=''1384580''>is</span> <span m=''1384670''>almost</span>
  <span m=''1385060''>the</span> <span m=''1385140''>same.</span> <span m=''1386770''>It</span>
  <span m=''1387290''>looks</span> <span m=''1387570''>at</span> <span m=''1387910''>the</span>
  <span m=''1388030''>number</span> <span m=''1388360''>and</span> <span m=''1388430''>if</span>
  <span m=''1388500''>it''s</span> <span m=''1388630''>rectangular,</span> <span m=''1389280''>uses</span>
  <span m=''1389600''>George''s</span> <span m=''1389990''>imaginary-part</span> <span
  m=''1390680''>procedure.</span> <span m=''1391130''>If it''s</span> <span m=''1391230''>polar,</span>
  <span m=''1391870''>uses</span> <span m=''1392150''>Martha''s.</span> <span m=''1393380''>And</span>
  <span m=''1393690''>then</span> <span m=''1393780''>there''s</span> <span m=''1393930''>a</span>
  <span m=''1393990''>magnitude</span> <span m=''1396100''>and</span> <span m=''1396570''>an</span>
  <span m=''1396770''>angle.</span> </p><p><span m=''1399880''>So</span> <span m=''1400140''>there''s</span>
  <span m=''1400340''>a</span> <span m=''1400390''>system.</span> <span m=''1403460''>Has</span>
  <span m=''1403720''>three</span> <span m=''1403920''>parts.</span> <span m=''1404260''>There''s</span>
  <span m=''1404370''>sort</span> <span m=''1404550''>of</span> <span m=''1404650''>George,</span>
  <span m=''1405100''>and</span> <span m=''1405230''>Martha,</span> <span m=''1405820''>and</span>
  <span m=''1405990''>the</span> <span m=''1406050''>manager.</span> <span m=''1406760''>And</span>
  <span m=''1406890''>that''s</span> <span m=''1407080''>how</span> <span m=''1407140''>you</span>
  <span m=''1407290''>get</span> <span m=''1407470''>generic</span> <span m=''1407840''>operators</span>
  <span m=''1408370''>implemented.</span> <span m=''1408970''>Let''s</span> <span
  m=''1409220''>look</span> <span m=''1409400''>at</span> <span m=''1409880''>just</span>
  <span m=''1410290''>a</span> <span m=''1410330''>simple</span> <span m=''1410720''>example,</span>
  <span m=''1412130''>just</span> <span m=''1412310''>to</span> <span m=''1412400''>pin</span>
  <span m=''1412580''>it</span> <span m=''1412680''>down.</span> <span m=''1413500''>But</span>
  <span m=''1413640''>exactly</span> <span m=''1414130''>how</span> <span m=''1414280''>this</span>
  <span m=''1414440''>is</span> <span m=''1414570''>going</span> <span m=''1414640''>to</span>
  <span m=''1414710''>work,</span> <span m=''1419720''>suppose</span> <span m=''1420050''>you''re</span>
  <span m=''1420140''>going</span> <span m=''1420240''>to</span> <span m=''1420330''>be</span>
  <span m=''1420430''>looking</span> <span m=''1420820''>at</span> <span m=''1420980''>the</span>
  <span m=''1421160''>complex</span> <span m=''1421700''>number</span> <span m=''1422690''>who''s</span>
  <span m=''1422800''>real-part is</span> <span m=''1423570''>one,</span> <span m=''1424460''>and</span>
  <span m=''1424690''>who''s</span> <span m=''1424920''>imaginary-part</span> <span
  m=''1425700''>is</span> <span m=''1425860''>two.</span> <span m=''1426090''>So</span>
  <span m=''1426240''>that would be</span> <span m=''1426390''>one</span> <span m=''1426830''>plus</span>
  <span m=''1427600''>2i.</span> <span m=''1430310''>What</span> <span m=''1430500''>would</span>
  <span m=''1430680''>happen</span> <span m=''1431140''>is</span> <span m=''1432020''>up</span>
  <span m=''1432200''>here,</span> <span m=''1435390''>up here</span> <span m=''1435720''>above</span>
  <span m=''1436130''>where</span> <span m=''1436220''>the</span> <span m=''1436350''>operations</span>
  <span m=''1436900''>have</span> <span m=''1437050''>to</span> <span m=''1437140''>happen,</span>
  <span m=''1437630''>that</span> <span m=''1437990''>number</span> <span m=''1438260''>would</span>
  <span m=''1438400''>be</span> <span m=''1438530''>represented</span> <span m=''1439720''>as</span>
  <span m=''1440660''>a</span> <span m=''1440770''>pair</span> <span m=''1442320''>of</span>
  <span m=''1442500''>1</span> <span m=''1443980''>and</span> <span m=''1444210''>2</span>
  <span m=''1446260''>together</span> <span m=''1446700''>with</span> <span m=''1447350''>typed</span>
  <span m=''1447780''>data.</span> <span m=''1450320''>That</span> <span m=''1450690''>would
  be</span> <span m=''1450800''>the</span> <span m=''1450890''>contents.</span> <span
  m=''1451870''>And</span> <span m=''1452180''>the whole</span> <span m=''1452460''>data</span>
  <span m=''1452670''>would</span> <span m=''1452800''>be</span> <span m=''1452920''>that</span>
  <span m=''1453200''>thing</span> <span m=''1454180''>with</span> <span m=''1454290''>the</span>
  <span m=''1454390''>symbol</span> <span m=''1456300''>rectangular</span> <span m=''1457210''>added</span>
  <span m=''1457450''>onto</span> <span m=''1457700''>that.</span> <span m=''1457960''>And</span>
  <span m=''1458250''>that''s</span> <span m=''1458560''>the</span> <span m=''1458650''>way</span>
  <span m=''1459480''>that</span> <span m=''1459660''>complex</span> <span m=''1460140''>number</span>
  <span m=''1460330''>would</span> <span m=''1460480''>exist</span> <span m=''1460860''>in</span>
  <span m=''1460980''>the</span> <span m=''1461070''>system.</span> </p><p><span m=''1462330''>When</span>
  <span m=''1462550''>you</span> <span m=''1462650''>went</span> <span m=''1463360''>to</span>
  <span m=''1463870''>take</span> <span m=''1464200''>the</span> <span m=''1464320''>real-part,</span>
  <span m=''1465820''>the</span> <span m=''1466010''>manager</span> <span m=''1466440''>would</span>
  <span m=''1466560''>look</span> <span m=''1466720''>at</span> <span m=''1466990''>this</span>
  <span m=''1467520''>and</span> <span m=''1467670''>say,</span> <span m=''1467850''>oh</span>
  <span m=''1468020''>it''s</span> <span m=''1468140''>one</span> <span m=''1468280''>of</span>
  <span m=''1468400''>George''s.</span> <span m=''1470270''>He''ll</span> <span m=''1470420''>strip</span>
  <span m=''1470780''>off</span> <span m=''1471010''>the</span> <span m=''1471140''>type</span>
  <span m=''1472980''>and</span> <span m=''1473380''>hand</span> <span m=''1473930''>down</span>
  <span m=''1474310''>to</span> <span m=''1474440''>George</span> <span m=''1475490''>the</span>
  <span m=''1475900''>pair</span> <span m=''1476220''>1,</span> <span m=''1476520''>2.</span>
  <span m=''1477532''>And</span> <span m=''1477880''>that''s</span> <span m=''1478320''>the</span>
  <span m=''1478400''>kind</span> <span m=''1478630''>of</span> <span m=''1478700''>data</span>
  <span m=''1478980''>that</span> <span m=''1480600''>George</span> <span m=''1480900''>developed</span>
  <span m=''1481360''>his</span> <span m=''1481420''>system</span> <span m=''1481790''>to</span>
  <span m=''1481900''>use.</span> <span m=''1484950''>So</span> <span m=''1485070''>it</span>
  <span m=''1485150''>gets</span> <span m=''1485280''>stripped</span> <span m=''1485590''>down.</span>
  <span m=''1486680''>Later</span> <span m=''1487050''>on,</span> <span m=''1487580''>if</span>
  <span m=''1487730''>you</span> <span m=''1487870''>ask</span> <span m=''1488090''>George</span>
  <span m=''1488380''>to</span> <span m=''1488470''>construct</span> <span m=''1488880''>a</span>
  <span m=''1488930''>complex</span> <span m=''1489420''>number,</span> <span m=''1491240''>George</span>
  <span m=''1491510''>would</span> <span m=''1491650''>construct</span> <span m=''1492790''>some</span>
  <span m=''1493230''>complex</span> <span m=''1493710''>number as</span> <span m=''1494060''>a</span>
  <span m=''1494140''>pair,</span> <span m=''1495180''>and</span> <span m=''1495370''>before</span>
  <span m=''1496050''>he</span> <span m=''1496270''>passes</span> <span m=''1496800''>it</span>
  <span m=''1496960''>back</span> <span m=''1497260''>up</span> <span m=''1497430''>through</span>
  <span m=''1497610''>the</span> <span m=''1497680''>manager</span> <span m=''1499490''>would</span>
  <span m=''1499630''>attach</span> <span m=''1500070''>the</span> <span m=''1500170''>type</span>
  <span m=''1500430''>rectangular.</span> </p><p><span m=''1503920''>So</span> <span
  m=''1504070''>you</span> <span m=''1504170''>see</span> <span m=''1504290''>what</span>
  <span m=''1504410''>happens.</span> <span m=''1504650''>There''s</span> <span m=''1504730''>no</span>
  <span m=''1504860''>confusion</span> <span m=''1505380''>in</span> <span m=''1505480''>this</span>
  <span m=''1505560''>system.</span> <span m=''1505850''>It</span> <span m=''1505940''>doesn''t</span>
  <span m=''1506320''>matter</span> <span m=''1506670''>in</span> <span m=''1506750''>the</span>
  <span m=''1506830''>least</span> <span m=''1507480''>that</span> <span m=''1507950''>the</span>
  <span m=''1508300''>pair</span> <span m=''1509750''>1,</span> <span m=''1510340''>2</span>
  <span m=''1513490''>means</span> <span m=''1513780''>something</span> <span m=''1514120''>completely</span>
  <span m=''1514630''>different</span> <span m=''1514970''>in</span> <span m=''1515070''>Martha''s</span>
  <span m=''1515510''>world.</span> <span m=''1515750''>In</span> <span m=''1515820''>Martha''s</span>
  <span m=''1516220''>world</span> <span m=''1516780''>this pair</span> <span m=''1517200''>means</span>
  <span m=''1517460''>the</span> <span m=''1517540''>complex</span> <span m=''1518020''>number</span>
  <span m=''1518250''>whose</span> <span m=''1518440''>magnitude</span> <span m=''1519010''>is</span>
  <span m=''1519140''>1</span> <span m=''1519660''>and</span> <span m=''1519820''>whose</span>
  <span m=''1519980''>angle</span> <span m=''1520290''>is</span> <span m=''1520380''>2.</span>
  <span m=''1521190''>And</span> <span m=''1521490''>there''s</span> <span m=''1521630''>no</span>
  <span m=''1521770''>confusion,</span> <span m=''1522370''>because</span> <span m=''1522670''>by</span>
  <span m=''1522800''>the</span> <span m=''1522920''>time</span> <span m=''1523470''>any</span>
  <span m=''1523630''>pair</span> <span m=''1523930''>like</span> <span m=''1524180''>this</span>
  <span m=''1525660''>gets</span> <span m=''1525860''>handed</span> <span m=''1526190''>back</span>
  <span m=''1526430''>through</span> <span m=''1526550''>the</span> <span m=''1526640''>manager</span>
  <span m=''1527050''>to</span> <span m=''1527160''>the</span> <span m=''1527250''>main</span>
  <span m=''1527490''>system</span> <span m=''1528210''>it''s</span> <span m=''1528380''>going</span>
  <span m=''1528440''>to</span> <span m=''1528510''>have</span> <span m=''1528680''>the</span>
  <span m=''1528780''>type</span> <span m=''1528960''>polar</span> <span m=''1529380''>attached.</span>
  <span m=''1531210''>Whereas</span> <span m=''1531520''>this</span> <span m=''1531720''>one</span>
  <span m=''1531990''>would</span> <span m=''1532190''>have</span> <span m=''1532330''>the</span>
  <span m=''1532420''>type</span> <span m=''1532640''>rectangular</span> <span m=''1533190''>attached.</span>
  </p><p><span m=''1536930''>OK,</span> <span m=''1537190''>let''s</span> <span m=''1537430''>take</span>
  <span m=''1537610''>a break.</span> </p><p><span m=''1540770''>[MUSIC-- "JESU, JOY
  OF MAN''S DESIRING" BY JOHANN SEBASTIAN BACH]</span> </p><p><span m=''1580210''>We</span>
  <span m=''1580350''>just</span> <span m=''1580590''>looked</span> <span m=''1580770''>at</span>
  <span m=''1580880''>a</span> <span m=''1580940''>strategy</span> <span m=''1581500''>for</span>
  <span m=''1582080''>implementing</span> <span m=''1583190''>generic</span> <span
  m=''1583560''>operators.</span> <span m=''1584150''>That</span> <span m=''1584350''>strategy</span>
  <span m=''1584770''>has</span> <span m=''1584970''>a</span> <span m=''1585030''>name:</span>
  <span m=''1585710''>it''s</span> <span m=''1585900''>called</span> <span m=''1590230''>dispatch</span>
  <span m=''1590920''>type.</span> <span m=''1594310''>And</span> <span m=''1596010''>the</span>
  <span m=''1596150''>idea</span> <span m=''1596490''>is</span> <span m=''1597450''>that</span>
  <span m=''1597580''>you</span> <span m=''1597690''>break</span> <span m=''1597990''>your</span>
  <span m=''1598080''>system</span> <span m=''1598480''>into</span> <span m=''1598650''>a</span>
  <span m=''1598700''>bunch</span> <span m=''1598940''>of</span> <span m=''1599030''>pieces.</span>
  <span m=''1599360''>There''s</span> <span m=''1599560''>George</span> <span m=''1599890''>and</span>
  <span m=''1599990''>Martha,</span> <span m=''1601160''>who are</span> <span m=''1601330''>making</span>
  <span m=''1601660''>representations,</span> <span m=''1603250''>and</span> <span
  m=''1603620''>then</span> <span m=''1603730''>there''s</span> <span m=''1603920''>the</span>
  <span m=''1603990''>manager.</span> <span m=''1606320''>Looks</span> <span m=''1606620''>at</span>
  <span m=''1606830''>the</span> <span m=''1607060''>types</span> <span m=''1607420''>on</span>
  <span m=''1607610''>the</span> <span m=''1607700''>data</span> <span m=''1608480''>and</span>
  <span m=''1608680''>then</span> <span m=''1608880''>dispatches</span> <span m=''1609600''>them</span>
  <span m=''1609760''>to</span> <span m=''1609880''>the</span> <span m=''1610010''>right</span>
  <span m=''1610260''>person.</span> </p><p><span m=''1611990''>Well</span> <span
  m=''1612370''>what</span> <span m=''1612740''>criticisms</span> <span m=''1613450''>can</span>
  <span m=''1613590''>we</span> <span m=''1613710''>make</span> <span m=''1614270''>of</span>
  <span m=''1614580''>that</span> <span m=''1614780''>as</span> <span m=''1614920''>a</span>
  <span m=''1614960''>system</span> <span m=''1615320''>organization?</span> <span
  m=''1618150''>Well</span> <span m=''1618270''>first</span> <span m=''1618520''>of</span>
  <span m=''1618590''>all</span> <span m=''1618700''>there</span> <span m=''1618820''>was</span>
  <span m=''1618940''>this</span> <span m=''1619360''>little,</span> <span m=''1619650''>annoying</span>
  <span m=''1620010''>problem</span> <span m=''1620400''>that</span> <span m=''1620540''>George</span>
  <span m=''1620790''>and</span> <span m=''1620880''>Martha</span> <span m=''1621140''>had</span>
  <span m=''1621270''>to</span> <span m=''1621350''>change</span> <span m=''1621730''>the</span>
  <span m=''1621810''>names</span> <span m=''1622120''>of</span> <span m=''1622200''>their</span>
  <span m=''1622350''>procedures.</span> <span m=''1624220''>George</span> <span m=''1624490''>originally</span>
  <span m=''1624880''>had</span> <span m=''1625040''>a</span> <span m=''1625130''>real-part</span>
  <span m=''1625620''>procedure,</span> <span m=''1626030''>and</span> <span m=''1626100''>he</span>
  <span m=''1626160''>had</span> <span m=''1626320''>to</span> <span m=''1626340''>go</span>
  <span m=''1626520''>name</span> <span m=''1626700''>it</span> <span m=''1626800''>real-part</span>
  <span m=''1627570''>rectangular</span> <span m=''1628240''>so it</span> <span m=''1628410''>wouldn''t</span>
  <span m=''1629110''>interfere</span> <span m=''1629500''>with</span> <span m=''1629620''>Martha''s</span>
  <span m=''1630060''>real-part</span> <span m=''1630470''>procedure,</span> <span
  m=''1630900''>which</span> <span m=''1631070''>is</span> <span m=''1631170''>now</span>
  <span m=''1631490''>named</span> <span m=''1631780''>real-part-polar,</span> <span
  m=''1633640''>so it</span> <span m=''1633760''>wouldn''t</span> <span m=''1633960''>interfere</span>
  <span m=''1634250''>with</span> <span m=''1634340''>the</span> <span m=''1634410''>manager''s</span>
  <span m=''1634910''>real-part</span> <span m=''1635320''>procedure,</span> <span
  m=''1635700''>who''s</span> <span m=''1635850''>now</span> <span m=''1636000''>named</span>
  <span m=''1636230''>real-part.</span> <span m=''1637310''>That''s</span> <span m=''1637600''>kind</span>
  <span m=''1637700''>of</span> <span m=''1637810''>an</span> <span m=''1637880''>annoying</span>
  <span m=''1638290''>problem.</span> <span m=''1639460''>But</span> <span m=''1639680''>I''m</span>
  <span m=''1639790''>not</span> <span m=''1639950''>going</span> <span m=''1640020''>to</span>
  <span m=''1640080''>talk</span> <span m=''1640320''>about</span> <span m=''1640560''>that</span>
  <span m=''1640750''>one</span> <span m=''1640850''>now.</span> <span m=''1641270''>We''ll</span>
  <span m=''1641410''>see</span> <span m=''1641590''>later</span> <span m=''1641930''>on</span>
  <span m=''1642942''>when</span> <span m=''1643290''>we</span> <span m=''1643490''>think</span>
  <span m=''1643650''>about</span> <span m=''1643790''>the</span> <span m=''1643920''>structure</span>
  <span m=''1644350''>of</span> <span m=''1644450''>Lisp</span> <span m=''1645100''>names</span>
  <span m=''1645540''>and</span> <span m=''1645620''>environments</span> <span m=''1646150''>that</span>
  <span m=''1646270''>there</span> <span m=''1646350''>really</span> <span m=''1646630''>are</span>
  <span m=''1646760''>ways</span> <span m=''1647320''>to</span> <span m=''1647480''>package</span>
  <span m=''1647940''>all</span> <span m=''1648060''>those</span> <span m=''1648600''>so-called</span>
  <span m=''1649020''>name</span> <span m=''1649350''>spaces</span> <span m=''1649730''>separately</span>
  <span m=''1650150''>so</span> <span m=''1650270''>they</span> <span m=''1650390''>don''t</span>
  <span m=''1650600''>interfere</span> <span m=''1650970''>with</span> <span m=''1651100''>each</span>
  <span m=''1651280''>other.</span> <span m=''1652500''>Not</span> <span m=''1652640''>going
  to</span> <span m=''1652760''>think</span> <span m=''1652960''>about</span> <span
  m=''1653170''>that</span> <span m=''1653320''>problem</span> <span m=''1653670''>now.</span>
  </p><p><span m=''1655720''>The</span> <span m=''1655880''>problem</span> <span m=''1656870''>that</span>
  <span m=''1657030''>I</span> <span m=''1657120''>actually</span> <span m=''1657390''>want</span>
  <span m=''1657470''>to</span> <span m=''1657560''>focus</span> <span m=''1657920''>on</span>
  <span m=''1658090''>is</span> <span m=''1658400''>what</span> <span m=''1658740''>happens</span>
  <span m=''1660900''>when</span> <span m=''1661030''>you</span> <span m=''1661120''>bring</span>
  <span m=''1661340''>somebody</span> <span m=''1661840''>new</span> <span m=''1662440''>into</span>
  <span m=''1662620''>the</span> <span m=''1662810''>system.</span> <span m=''1664510''>What</span>
  <span m=''1664720''>has</span> <span m=''1664900''>to</span> <span m=''1664990''>happen?</span>
  <span m=''1665320''>Well</span> <span m=''1665460''>George</span> <span m=''1665780''>and</span>
  <span m=''1665880''>Martha</span> <span m=''1666210''>don''t</span> <span m=''1666470''>care.</span>
  <span m=''1667690''>George is</span> <span m=''1668000''>sitting</span> <span m=''1668350''>there</span>
  <span m=''1668960''>in</span> <span m=''1669400''>his</span> <span m=''1669580''>rectangular</span>
  <span m=''1670370''>world,</span> <span m=''1672480''>has</span> <span m=''1672680''>his</span>
  <span m=''1672830''>procedures</span> <span m=''1673380''>and</span> <span m=''1673490''>his</span>
  <span m=''1673610''>types.</span> <span m=''1674090''>Martha</span> <span m=''1674810''>sits</span>
  <span m=''1675070''>in</span> <span m=''1675130''>her</span> <span m=''1675240''>polar</span>
  <span m=''1676040''>world.</span> <span m=''1676260''>She</span> <span m=''1676390''>doesn''t</span>
  <span m=''1676660''>care.</span> </p><p><span m=''1679380''>But</span> <span m=''1679520''>let''s</span>
  <span m=''1679690''>look</span> <span m=''1679810''>at</span> <span m=''1679920''>the</span>
  <span m=''1680000''>manager.</span> <span m=''1681540''>What''s</span> <span m=''1681720''>the</span>
  <span m=''1681910''>manager</span> <span m=''1682310''>have</span> <span m=''1682460''>to</span>
  <span m=''1682610''>do?</span> <span m=''1683180''>The</span> <span m=''1683310''>manager</span>
  <span m=''1683720''>comes</span> <span m=''1684010''>through</span> <span m=''1684250''>and</span>
  <span m=''1685000''>had</span> <span m=''1685160''>these</span> <span m=''1685350''>operations.</span>
  <span m=''1687360''>There</span> <span m=''1687500''>was</span> <span m=''1687640''>a</span>
  <span m=''1687700''>test</span> <span m=''1688010''>for</span> <span m=''1688120''>rectangular</span>
  <span m=''1689040''>and</span> <span m=''1689170''>a</span> <span m=''1689220''>test</span>
  <span m=''1689490''>for</span> <span m=''1689580''>polar.</span> <span m=''1690140''>If</span>
  <span m=''1690290''>Harry</span> <span m=''1690640''>comes</span> <span m=''1690950''>in</span>
  <span m=''1692080''>with</span> <span m=''1692260''>some</span> <span m=''1692480''>new</span>
  <span m=''1692690''>kind</span> <span m=''1693750''>of</span> <span m=''1693920''>complex</span>
  <span m=''1694420''>number,</span> <span m=''1697210''>and</span> <span m=''1697340''>Harry</span>
  <span m=''1697620''>has</span> <span m=''1697800''>a</span> <span m=''1697850''>new</span>
  <span m=''1697990''>type,</span> <span m=''1698610''>Harry</span> <span m=''1698970''>type</span>
  <span m=''1699240''>complex</span> <span m=''1699710''>number,</span> <span m=''1700250''>the</span>
  <span m=''1700430''>manager</span> <span m=''1700800''>has</span> <span m=''1700980''>to</span>
  <span m=''1701070''>go</span> <span m=''1701270''>in</span> <span m=''1701650''>and</span>
  <span m=''1701830''>change</span> <span m=''1702260''>all</span> <span m=''1702460''>those</span>
  <span m=''1702690''>procedures.</span> <span m=''1705240''>So</span> <span m=''1705420''>the</span>
  <span m=''1705570''>inflexibility</span> <span m=''1706410''>in</span> <span m=''1706480''>the</span>
  <span m=''1706550''>system,</span> <span m=''1706870''>the</span> <span m=''1706950''>place</span>
  <span m=''1708200''>where</span> <span m=''1708630''>work</span> <span m=''1708940''>has</span>
  <span m=''1709190''>to</span> <span m=''1709290''>happen</span> <span m=''1709790''>to</span>
  <span m=''1710040''>accommodate</span> <span m=''1710610''>change,</span> <span
  m=''1711590''>is</span> <span m=''1711760''>in</span> <span m=''1711850''>the</span>
  <span m=''1711940''>manager.</span> <span m=''1714890''>That''s</span> <span m=''1715120''>pretty</span>
  <span m=''1715350''>annoying.</span> </p><p><span m=''1715990''>It''s</span> <span
  m=''1716150''>even</span> <span m=''1716370''>more</span> <span m=''1716680''>annoying</span>
  <span m=''1719070''>when</span> <span m=''1719210''>you</span> <span m=''1719320''>realize</span>
  <span m=''1719610''>the</span> <span m=''1719690''>manager''s</span> <span m=''1720120''>not</span>
  <span m=''1720300''>doing</span> <span m=''1720640''>anything.</span> <span m=''1722590''>The</span>
  <span m=''1722670''>manager</span> <span m=''1723100''>is</span> <span m=''1723240''>just</span>
  <span m=''1723550''>being</span> <span m=''1723840''>a</span> <span m=''1723920''>paper</span>
  <span m=''1724310''>pusher.</span> <span m=''1726690''>Let''s</span> <span m=''1727310''>look</span>
  <span m=''1727540''>again</span> <span m=''1728820''>at</span> <span m=''1729010''>these</span>
  <span m=''1729680''>programs.</span> <span m=''1730260''>What</span> <span m=''1730360''>are</span>
  <span m=''1730460''>they</span> <span m=''1730620''>doing?</span> <span m=''1731760''>What</span>
  <span m=''1731880''>does</span> <span m=''1732010''>real-part do?</span> <span m=''1732880''>Real-part</span>
  <span m=''1733280''>says,</span> <span m=''1733540''>oh,</span> <span m=''1734000''>is</span>
  <span m=''1734240''>it</span> <span m=''1734360''>the</span> <span m=''1734470''>kind</span>
  <span m=''1734780''>of</span> <span m=''1735240''>complex</span> <span m=''1735750''>number</span>
  <span m=''1735990''>that</span> <span m=''1736170''>George</span> <span m=''1736470''>can</span>
  <span m=''1736600''>handle?</span> <span m=''1737000''>If</span> <span m=''1737110''>so,</span>
  <span m=''1737290''>send</span> <span m=''1737540''>it</span> <span m=''1737630''>off</span>
  <span m=''1737790''>to</span> <span m=''1737910''>George.</span> <span m=''1739410''>Is</span>
  <span m=''1739560''>it</span> <span m=''1739660''>the</span> <span m=''1739760''>kind</span>
  <span m=''1739940''>of</span> <span m=''1740120''>complex</span> <span m=''1740570''>number</span>
  <span m=''1740780''>that</span> <span m=''1740950''>Martha</span> <span m=''1741250''>can</span>
  <span m=''1741370''>handle?</span> <span m=''1741910''>If</span> <span m=''1742080''>so,</span>
  <span m=''1742560''>send</span> <span m=''1742950''>it</span> <span m=''1743010''>off</span>
  <span m=''1743300''>to</span> <span m=''1743650''>Martha.</span> <span m=''1745040''>So</span>
  <span m=''1745200''>it''s</span> <span m=''1745710''>really</span> <span m=''1746050''>annoying</span>
  <span m=''1746610''>that</span> <span m=''1746940''>the</span> <span m=''1747270''>bottleneck</span>
  <span m=''1747990''>in</span> <span m=''1748130''>this</span> <span m=''1748280''>system,</span>
  <span m=''1748720''>the</span> <span m=''1748920''>thing</span> <span m=''1749440''>that''s</span>
  <span m=''1750110''>preventing</span> <span m=''1750570''>flexibility</span> <span
  m=''1751190''>and</span> <span m=''1751280''>change,</span> <span m=''1752840''>is</span>
  <span m=''1753040''>completely</span> <span m=''1753510''>in</span> <span m=''1753600''>the</span>
  <span m=''1753690''>bureaucracy.</span> <span m=''1755000''>It''s</span> <span m=''1755190''>not</span>
  <span m=''1755400''>in</span> <span m=''1755510''>anybody</span> <span m=''1756010''>who''s</span>
  <span m=''1756220''>doing</span> <span m=''1756490''>any</span> <span m=''1756680''>of</span>
  <span m=''1756760''>the</span> <span m=''1756850''>work.</span> <span m=''1759700''>Not</span>
  <span m=''1759920''>an</span> <span m=''1760010''>uncommon</span> <span m=''1760500''>situation,</span>
  <span m=''1761150''>unfortunately.</span> </p><p><span m=''1763300''>See,</span>
  <span m=''1763420''>what''s</span> <span m=''1763590''>really</span> <span m=''1763890''>going</span>
  <span m=''1764190''>on--</span> <span m=''1764570''>abstractly</span> <span m=''1765370''>in</span>
  <span m=''1765460''>the</span> <span m=''1765550''>system,</span> <span m=''1766240''>there''s</span>
  <span m=''1766500''>a</span> <span m=''1766600''>table.</span> <span m=''1768100''>So</span>
  <span m=''1768260''>what''s</span> <span m=''1768420''>really</span> <span m=''1768700''>happening</span>
  <span m=''1769070''>is</span> <span m=''1769170''>somewhere</span> <span m=''1769450''>there''s</span>
  <span m=''1769670''>a</span> <span m=''1769730''>table.</span> <span m=''1772780''>There''re</span>
  <span m=''1773190''>types.</span> <span m=''1774400''>There''s</span> <span m=''1774650''>polar</span>
  <span m=''1778010''>and</span> <span m=''1778190''>rectangular.</span> <span m=''1781550''>And</span>
  <span m=''1781700''>Harry''s</span> <span m=''1782150''>may</span> <span m=''1782310''>be</span>
  <span m=''1782460''>over</span> <span m=''1782600''>here.</span> <span m=''1784380''>And</span>
  <span m=''1785720''>there</span> <span m=''1785910''>are</span> <span m=''1786000''>operators.</span>
  <span m=''1788050''>There''s</span> <span m=''1788260''>an</span> <span m=''1788330''>operator</span>
  <span m=''1789420''>like</span> <span m=''1790120''>real-part.</span> <span m=''1795600''>Or</span>
  <span m=''1797200''>imaginary-part.</span> <span m=''1800010''>Or</span> <span m=''1800190''>a</span>
  <span m=''1800240''>magnitude</span> <span m=''1803440''>and</span> <span m=''1803640''>angle.</span>
  <span m=''1805830''>And</span> <span m=''1806690''>sitting</span> <span m=''1808290''>in</span>
  <span m=''1808590''>this</span> <span m=''1808830''>table</span> <span m=''1817430''>are</span>
  <span m=''1817860''>the</span> <span m=''1818150''>right</span> <span m=''1818410''>procedures.</span>
  <span m=''1819280''>So</span> <span m=''1819500''>sitting</span> <span m=''1819790''>here</span>
  <span m=''1820260''>for</span> <span m=''1820510''>the</span> <span m=''1820640''>type</span>
  <span m=''1820930''>polar</span> <span m=''1821300''>and</span> <span m=''1821410''>real-part</span>
  <span m=''1821880''>is</span> <span m=''1821990''>Martha''s</span> <span m=''1822720''>procedure</span>
  <span m=''1824340''>real-part-polar.</span> <span m=''1830570''>And</span> <span
  m=''1830750''>over</span> <span m=''1830940''>here</span> <span m=''1831130''>in</span>
  <span m=''1831190''>the</span> <span m=''1831290''>table</span> <span m=''1831660''>is</span>
  <span m=''1831820''>George''s</span> <span m=''1832230''>procedure</span> <span
  m=''1833740''>real-part-rectangular.</span> <span m=''1837740''>And</span> <span
  m=''1838030''>over</span> <span m=''1838220''>here</span> <span m=''1838410''>would</span>
  <span m=''1838620''>be,</span> <span m=''1839010''>say,</span> <span m=''1839220''>Martha''s</span>
  <span m=''1839710''>procedure</span> <span m=''1840680''>magnitude-polar,</span>
  <span m=''1844440''>and</span> <span m=''1844660''>George''s</span> <span m=''1845040''>procedure</span>
  <span m=''1846780''>magnitude-rectangular,</span> <span m=''1849040''>right,</span>
  <span m=''1849250''>and</span> <span m=''1849370''>so</span> <span m=''1849580''>on.</span>
  <span m=''1849760''>The</span> <span m=''1849840''>rest</span> <span m=''1850080''>of</span>
  <span m=''1850180''>this</span> <span m=''1850280''>table''s</span> <span m=''1850680''>filled</span>
  <span m=''1850940''>in.</span> <span m=''1852390''>And</span> <span m=''1852590''>that''s</span>
  <span m=''1853010''>really</span> <span m=''1853470''>what''s</span> <span m=''1853710''>going</span>
  <span m=''1854010''>on.</span> </p><p><span m=''1857630''>So</span> <span m=''1857840''>in</span>
  <span m=''1857920''>some</span> <span m=''1858110''>sense,</span> <span m=''1860500''>all</span>
  <span m=''1860690''>the</span> <span m=''1860770''>manager is</span> <span m=''1861400''>doing</span>
  <span m=''1862150''>is</span> <span m=''1862370''>acting</span> <span m=''1863140''>as</span>
  <span m=''1863380''>this</span> <span m=''1863720''>table.</span> <span m=''1866860''>Well</span>
  <span m=''1867480''>how</span> <span m=''1867610''>do</span> <span m=''1867700''>we</span>
  <span m=''1867800''>fix</span> <span m=''1868060''>our</span> <span m=''1868150''>system?</span>
  <span m=''1872110''>How</span> <span m=''1872240''>do</span> <span m=''1872330''>you</span>
  <span m=''1872410''>fix</span> <span m=''1872650''>bureaucracies</span> <span m=''1873260''>a
  lot</span> <span m=''1873530''>of the time?</span> <span m=''1873770''>What</span>
  <span m=''1873960''>you</span> <span m=''1874070''>do</span> <span m=''1874260''>is</span>
  <span m=''1874390''>you</span> <span m=''1874470''>get</span> <span m=''1874720''>rid</span>
  <span m=''1874880''>of</span> <span m=''1874950''>the</span> <span m=''1875030''>manager.</span>
  <span m=''1876240''>We</span> <span m=''1876330''>just</span> <span m=''1876500''>take</span>
  <span m=''1876710''>the</span> <span m=''1876790''>manager</span> <span m=''1877650''>and</span>
  <span m=''1878200''>replace</span> <span m=''1878670''>him</span> <span m=''1878790''>by</span>
  <span m=''1878990''>a</span> <span m=''1879050''>computer.</span> <span m=''1880170''>We''re</span>
  <span m=''1880380''>going to</span> <span m=''1880530''>automate</span> <span m=''1880960''>him</span>
  <span m=''1881130''>out</span> <span m=''1881290''>of</span> <span m=''1881390''>existence.</span>
  <span m=''1883320''>Namely,</span> <span m=''1883630''>instead</span> <span m=''1884010''>of</span>
  <span m=''1884100''>having</span> <span m=''1884410''>the</span> <span m=''1884480''>manager</span>
  <span m=''1884960''>who</span> <span m=''1885070''>basically</span> <span m=''1885530''>consults</span>
  <span m=''1885970''>this</span> <span m=''1886150''>table,</span> <span m=''1887480''>we''ll</span>
  <span m=''1887650''>have</span> <span m=''1887830''>our</span> <span m=''1887930''>system</span>
  <span m=''1888280''>use</span> <span m=''1888450''>the</span> <span m=''1888630''>table</span>
  <span m=''1888950''>directly.</span> </p><p><span m=''1891020''>What do</span> <span
  m=''1891260''>I</span> <span m=''1891330''>mean</span> <span m=''1891560''>by</span>
  <span m=''1891720''>that?</span> <span m=''1892110''>Let''s</span> <span m=''1892350''>assume,</span>
  <span m=''1894420''>again</span> <span m=''1894710''>using</span> <span m=''1895020''>data</span>
  <span m=''1895260''>abstraction,</span> <span m=''1897630''>that</span> <span m=''1897870''>we</span>
  <span m=''1897980''>have</span> <span m=''1898460''>some</span> <span m=''1898730''>kind</span>
  <span m=''1898940''>of</span> <span m=''1899030''>data</span> <span m=''1899280''>structure</span>
  <span m=''1899650''>that''s</span> <span m=''1899870''>a</span> <span m=''1899950''>table.</span>
  <span m=''1900880''>And</span> <span m=''1901020''>we</span> <span m=''1901110''>have</span>
  <span m=''1901250''>ways</span> <span m=''1901490''>of</span> <span m=''1901560''>sticking</span>
  <span m=''1901900''>things</span> <span m=''1902160''>in and</span> <span m=''1902470''>ways</span>
  <span m=''1902740''>of</span> <span m=''1902810''>getting</span> <span m=''1903080''>things</span>
  <span m=''1903300''>out.</span> <span m=''1904356''>And</span> <span m=''1904700''>to</span>
  <span m=''1904840''>be</span> <span m=''1905560''>explicit,</span> <span m=''1906090''>let</span>
  <span m=''1906210''>me</span> <span m=''1906330''>assume</span> <span m=''1906630''>that</span>
  <span m=''1906760''>there''s</span> <span m=''1906930''>an</span> <span m=''1907000''>operation</span>
  <span m=''1908400''>called</span> <span m=''1908670''>"put."</span> <span m=''1910390''>And</span>
  <span m=''1910580''>put</span> <span m=''1910820''>is</span> <span m=''1911000''>going</span>
  <span m=''1911090''>to</span> <span m=''1911180''>take,</span> <span m=''1911975''>in</span>
  <span m=''1912270''>this</span> <span m=''1912710''>case</span> <span m=''1912980''>two</span>
  <span m=''1913260''>things</span> <span m=''1913510''>I''ll</span> <span m=''1913620''>call</span>
  <span m=''1913890''>"keys."</span> <span m=''1915280''>Key1</span> <span m=''1917180''>and</span>
  <span m=''1917570''>key2.</span> <span m=''1920130''>And</span> <span m=''1920240''>a</span>
  <span m=''1920350''>value.</span> <span m=''1926200''>And</span> <span m=''1926380''>that</span>
  <span m=''1926720''>stores</span> <span m=''1927240''>the</span> <span m=''1927330''>value</span>
  <span m=''1927810''>in</span> <span m=''1928750''>the</span> <span m=''1929060''>table</span>
  <span m=''1929660''>under</span> <span m=''1929960''>key1</span> <span m=''1930370''>and</span>
  <span m=''1930460''>key2.</span> <span m=''1931490''>And</span> <span m=''1931660''>then</span>
  <span m=''1931800''>we''ll assume</span> <span m=''1932140''>there''s</span> <span
  m=''1932310''>a</span> <span m=''1932360''>thing</span> <span m=''1932510''>called</span>
  <span m=''1932860''>"get,"</span> <span m=''1935220''>such</span> <span m=''1935530''>that</span>
  <span m=''1936080''>if</span> <span m=''1936290''>later</span> <span m=''1936630''>on</span>
  <span m=''1936790''>I</span> <span m=''1936890''>say,</span> <span m=''1937100''>get</span>
  <span m=''1937560''>me</span> <span m=''1937770''>what''s</span> <span m=''1937990''>in</span>
  <span m=''1938090''>the</span> <span m=''1938200''>table</span> <span m=''1939310''>stored</span>
  <span m=''1939680''>under</span> <span m=''1939900''>key1</span> <span m=''1941610''>and</span>
  <span m=''1941970''>key2,</span> <span m=''1943500''>it''ll</span> <span m=''1943670''>retrieve</span>
  <span m=''1944120''>whatever</span> <span m=''1944450''>value</span> <span m=''1944870''>was</span>
  <span m=''1945010''>stored</span> <span m=''1945280''>there.</span> <span m=''1946730''>And</span>
  <span m=''1946890''>let''s</span> <span m=''1947060''>not</span> <span m=''1947230''>worry</span>
  <span m=''1947480''>about</span> <span m=''1947700''>how</span> <span m=''1947820''>tables</span>
  <span m=''1948230''>are</span> <span m=''1948430''>implemented.</span> <span m=''1950000''>That''s</span>
  <span m=''1950310''>yet</span> <span m=''1950460''>another</span> <span m=''1950770''>data</span>
  <span m=''1951050''>abstraction,</span> <span m=''1951670''>George''s</span> <span
  m=''1952070''>problem.</span> <span m=''1953060''>And</span> <span m=''1953440''>maybe</span>
  <span m=''1953720''>we''ll</span> <span m=''1953840''>see</span> <span m=''1954030''>later--</span>
  <span m=''1954700''>talk</span> <span m=''1954910''>about</span> <span m=''1955090''>how</span>
  <span m=''1955160''>you</span> <span m=''1955310''>might</span> <span m=''1955520''>actually</span>
  <span m=''1955880''>build</span> <span m=''1956110''>tables</span> <span m=''1956490''>in</span>
  <span m=''1956600''>Lisp.</span> </p><p><span m=''1960710''>Well</span> <span m=''1961140''>given</span>
  <span m=''1961490''>this</span> <span m=''1961650''>organization,</span> <span m=''1963920''>what</span>
  <span m=''1964050''>did</span> <span m=''1964170''>George</span> <span m=''1964440''>and</span>
  <span m=''1964540''>Martha</span> <span m=''1964850''>have</span> <span m=''1965010''>to</span>
  <span m=''1965170''>do?</span> <span m=''1967380''>Well</span> <span m=''1968270''>when</span>
  <span m=''1968460''>they</span> <span m=''1968590''>build</span> <span m=''1968800''>their</span>
  <span m=''1968920''>system,</span> <span m=''1969410''>they</span> <span m=''1969550''>each</span>
  <span m=''1969760''>have</span> <span m=''1969930''>the</span> <span m=''1970010''>responsibility</span>
  <span m=''1971280''>to</span> <span m=''1971660''>set</span> <span m=''1971920''>up</span>
  <span m=''1972050''>their</span> <span m=''1972240''>appropriate</span> <span m=''1972750''>column</span>
  <span m=''1973190''>in</span> <span m=''1973290''>the</span> <span m=''1973390''>table.</span>
  <span m=''1975210''>So</span> <span m=''1975360''>what</span> <span m=''1975530''>George</span>
  <span m=''1975880''>does,</span> <span m=''1976380''>for</span> <span m=''1976840''>example,</span>
  <span m=''1979840''>when</span> <span m=''1979980''>he</span> <span m=''1980080''>defines</span>
  <span m=''1980510''>his</span> <span m=''1980620''>procedures,</span> <span m=''1981180''>all</span>
  <span m=''1981400''>he</span> <span m=''1981570''>has</span> <span m=''1981730''>to</span>
  <span m=''1981830''>do</span> <span m=''1982310''>is</span> <span m=''1982490''>go</span>
  <span m=''1982650''>off</span> <span m=''1982820''>and</span> <span m=''1983020''>put</span>
  <span m=''1983650''>into</span> <span m=''1983840''>the</span> <span m=''1984020''>table</span>
  <span m=''1985690''>under</span> <span m=''1986350''>the</span> <span m=''1986580''>type-rectangular.</span>
  <span m=''1989820''>And</span> <span m=''1990000''>the</span> <span m=''1990100''>name</span>
  <span m=''1990610''>of</span> <span m=''1990780''>the</span> <span m=''1990900''>operation</span>
  <span m=''1991480''>is</span> <span m=''1991590''>real-part,</span> <span m=''1993240''>his</span>
  <span m=''1993540''>procedure</span> <span m=''1994100''>real-part-rectangular.</span>
  </p><p><span m=''1996250''>So</span> <span m=''1996410''>notice</span> <span m=''1996690''>what''s</span>
  <span m=''1996860''>going</span> <span m=''1997070''>into</span> <span m=''1997240''>this</span>
  <span m=''1997370''>table.</span> <span m=''1997780''>The</span> <span m=''1998080''>two</span>
  <span m=''1998280''>keys</span> <span m=''1998680''>here</span> <span m=''1998860''>are</span>
  <span m=''1998910''>symbols,</span> <span m=''2000600''>rectangular</span> <span
  m=''2001450''>and</span> <span m=''2001620''>real-part.</span> <span m=''2002100''>That''s</span>
  <span m=''2002280''>the</span> <span m=''2002360''>quote.</span> <span m=''2004400''>And</span>
  <span m=''2004560''>what''s</span> <span m=''2004770''>going</span> <span m=''2005100''>into</span>
  <span m=''2005330''>the</span> <span m=''2005460''>table</span> <span m=''2005860''>is</span>
  <span m=''2006050''>the</span> <span m=''2006190''>actual</span> <span m=''2006970''>procedure</span>
  <span m=''2007410''>that</span> <span m=''2007560''>he</span> <span m=''2007680''>wrote,</span>
  <span m=''2008150''>real-part</span> <span m=''2008550''>rectangular.</span> <span
  m=''2012040''>And</span> <span m=''2012160''>then</span> <span m=''2012580''>puts
  an</span> <span m=''2012770''>imaginary</span> <span m=''2013330''>part</span> <span
  m=''2013570''>into</span> <span m=''2013710''>the</span> <span m=''2013850''>table,</span>
  <span m=''2014470''>filed</span> <span m=''2015000''>under</span> <span m=''2015660''>the</span>
  <span m=''2015870''>keys</span> <span m=''2016270''>rectangular-</span> <span m=''2016930''>and</span>
  <span m=''2017020''>imaginary-part,</span> <span m=''2018570''>and</span> <span
  m=''2019370''>magnitude</span> <span m=''2019990''>under</span> <span m=''2020160''>the</span>
  <span m=''2020280''>keys</span> <span m=''2021560''>rectangular</span> <span m=''2022110''>magnitude,</span>
  <span m=''2023630''>angle</span> <span m=''2024020''>under</span> <span m=''2024230''>rectangular-angle.</span>
  <span m=''2027350''>So</span> <span m=''2027450''>that''s</span> <span m=''2027750''>what</span>
  <span m=''2027980''>George</span> <span m=''2028280''>has</span> <span m=''2028530''>to</span>
  <span m=''2028620''>do</span> <span m=''2029150''>to</span> <span m=''2029780''>be</span>
  <span m=''2029920''>part</span> <span m=''2030170''>of</span> <span m=''2030270''>this</span>
  <span m=''2030360''>system.</span> </p><p><span m=''2034420''>Martha</span> <span
  m=''2034920''>similarly</span> <span m=''2036220''>sets</span> <span m=''2036510''>up</span>
  <span m=''2036990''>the</span> <span m=''2037140''>column</span> <span m=''2037640''>and</span>
  <span m=''2037740''>the</span> <span m=''2037840''>table</span> <span m=''2038200''>under</span>
  <span m=''2038400''>polar.</span> <span m=''2039430''>Polar</span> <span m=''2040060''>and</span>
  <span m=''2040210''>real-part.</span> <span m=''2042160''>Is the</span> <span m=''2042260''>procedure</span>
  <span m=''2042720''>real-part-polar?</span> <span m=''2044340''>And</span> <span
  m=''2044780''>imaginary-part,</span> <span m=''2045620''>and</span> <span m=''2045750''>magnitude,</span>
  <span m=''2046720''>and</span> <span m=''2046900''>angle.</span> <span m=''2049030''>So</span>
  <span m=''2049090''>this is</span> <span m=''2049219''>what</span> <span m=''2049360''>Martha</span>
  <span m=''2049679''>has</span> <span m=''2049860''>to</span> <span m=''2049960''>do</span>
  <span m=''2050469''>to</span> <span m=''2050590''>be</span> <span m=''2050699''>part</span>
  <span m=''2050840''>of</span> <span m=''2050969''>the</span> <span m=''2051050''>system.</span>
  <span m=''2051409''>Everyone</span> <span m=''2052159''>who</span> <span m=''2052270''>makes</span>
  <span m=''2052520''>a</span> <span m=''2052580''>representation</span> <span m=''2053300''>has</span>
  <span m=''2053469''>the</span> <span m=''2053550''>responsibility</span> <span m=''2056020''>for</span>
  <span m=''2056320''>setting</span> <span m=''2056560''>up</span> <span m=''2056659''>a</span>
  <span m=''2056730''>column</span> <span m=''2057060''>in</span> <span m=''2057139''>the</span>
  <span m=''2057239''>table.</span> </p><p><span m=''2057840''>And</span> <span m=''2058030''>what</span>
  <span m=''2058159''>does</span> <span m=''2058260''>Harry</span> <span m=''2058710''>do</span>
  <span m=''2058800''>when</span> <span m=''2058929''>Harry</span> <span m=''2059199''>comes</span>
  <span m=''2059440''>in</span> <span m=''2059530''>with</span> <span m=''2059670''>his</span>
  <span m=''2059900''>brilliant</span> <span m=''2060210''>idea</span> <span m=''2060469''>for</span>
  <span m=''2060630''>implementing</span> <span m=''2061030''>complex</span> <span
  m=''2061510''>numbers?</span> <span m=''2061800''>Well</span> <span m=''2061900''>he</span>
  <span m=''2062010''>makes</span> <span m=''2062210''>whatever</span> <span m=''2062489''>procedure</span>
  <span m=''2062909''>he</span> <span m=''2063030''>wants</span> <span m=''2063679''>and</span>
  <span m=''2064100''>builds</span> <span m=''2065170''>a</span> <span m=''2065300''>new</span>
  <span m=''2065440''>column</span> <span m=''2065840''>in</span> <span m=''2065929''>this</span>
  <span m=''2066010''>table.</span> </p><p><span m=''2068550''>OK,</span> <span m=''2068659''>well</span>
  <span m=''2068780''>what</span> <span m=''2069000''>happened</span> <span m=''2069320''>to</span>
  <span m=''2069409''>the</span> <span m=''2069500''>manager?</span> <span m=''2071330''>The</span>
  <span m=''2071580''>manager</span> <span m=''2072440''>has</span> <span m=''2072690''>been</span>
  <span m=''2072830''>automated</span> <span m=''2073370''>out</span> <span m=''2073510''>of</span>
  <span m=''2073590''>existence</span> <span m=''2074340''>and</span> <span m=''2074510''>is</span>
  <span m=''2074610''>replaced</span> <span m=''2075460''>by</span> <span m=''2075670''>a</span>
  <span m=''2075739''>procedure</span> <span m=''2076210''>called</span> <span m=''2076440''>operate.</span>
  <span m=''2077110''>And</span> <span m=''2077290''>this</span> <span m=''2077440''>is</span>
  <span m=''2077590''>the</span> <span m=''2077679''>key</span> <span m=''2077880''>procedure</span>
  <span m=''2078380''>in</span> <span m=''2078580''>the</span> <span m=''2078980''>whole</span>
  <span m=''2079139''>system.</span> <span m=''2080380''>Let''s say</span> <span m=''2080600''>define</span>
  <span m=''2085570''>operate.</span> <span m=''2091060''>Operate</span> <span m=''2091560''>is</span>
  <span m=''2091679''>going</span> <span m=''2091780''>to</span> <span m=''2091889''>take</span>
  <span m=''2094380''>an</span> <span m=''2094489''>operation</span> <span m=''2095210''>that</span>
  <span m=''2095330''>you</span> <span m=''2095469''>want</span> <span m=''2095580''>to</span>
  <span m=''2095690''>do,</span> <span m=''2097750''>the</span> <span m=''2097900''>name</span>
  <span m=''2098190''>of</span> <span m=''2098300''>an</span> <span m=''2098380''>operation,</span>
  <span m=''2099170''>and</span> <span m=''2099360''>an</span> <span m=''2099490''>object</span>
  <span m=''2101190''>that</span> <span m=''2101390''>you</span> <span m=''2101500''>would</span>
  <span m=''2101620''>like</span> <span m=''2101840''>to</span> <span m=''2101970''>apply</span>
  <span m=''2102280''>that</span> <span m=''2102440''>operation</span> <span m=''2103040''>to.</span>
  <span m=''2104210''>So</span> <span m=''2104400''>for</span> <span m=''2104520''>example,</span>
  <span m=''2104880''>the</span> <span m=''2105060''>real-part</span> <span m=''2106130''>of</span>
  <span m=''2106300''>some</span> <span m=''2106490''>particular</span> <span m=''2106950''>complex</span>
  <span m=''2107400''>number,</span> <span m=''2109100''>what</span> <span m=''2109270''>does</span>
  <span m=''2109380''>it</span> <span m=''2109500''>do?</span> </p><p><span m=''2109890''>Well</span>
  <span m=''2110170''>the</span> <span m=''2110340''>first</span> <span m=''2110500''>thing</span>
  <span m=''2110610''>it</span> <span m=''2110650''>does,</span> <span m=''2110860''>it</span>
  <span m=''2110950''>looks</span> <span m=''2111190''>in</span> <span m=''2111270''>the</span>
  <span m=''2111380''>table.</span> <span m=''2112650''>Goes</span> <span m=''2112930''>into</span>
  <span m=''2113090''>the</span> <span m=''2113200''>table</span> <span m=''2114840''>and</span>
  <span m=''2116590''>tries</span> <span m=''2117260''>to</span> <span m=''2117370''>find</span>
  <span m=''2119010''>a</span> <span m=''2119130''>procedure</span> <span m=''2120490''>that''s</span>
  <span m=''2120710''>stored</span> <span m=''2121730''>in</span> <span m=''2121900''>the</span>
  <span m=''2122000''>table.</span> <span m=''2123320''>So</span> <span m=''2123590''>it</span>
  <span m=''2123650''>gets</span> <span m=''2124010''>from</span> <span m=''2124140''>the</span>
  <span m=''2124230''>table,</span> <span m=''2125540''>using</span> <span m=''2125900''>as</span>
  <span m=''2126120''>keys</span> <span m=''2126770''>the</span> <span m=''2127060''>type</span>
  <span m=''2129580''>of</span> <span m=''2129700''>the</span> <span m=''2129830''>object</span>
  <span m=''2132470''>and</span> <span m=''2132940''>the</span> <span m=''2133210''>operator,</span>
  <span m=''2138950''>but</span> <span m=''2139100''>looks</span> <span m=''2139330''>on</span>
  <span m=''2139390''>the</span> <span m=''2139490''>table</span> <span m=''2139840''>and</span>
  <span m=''2139920''>sees</span> <span m=''2140450''>what''s</span> <span m=''2140640''>stored</span>
  <span m=''2141080''>under</span> <span m=''2141270''>the</span> <span m=''2141390''>type</span>
  <span m=''2141670''>of</span> <span m=''2141760''>the</span> <span m=''2141840''>object
  and</span> <span m=''2142120''>the</span> <span m=''2142300''>operator,</span> <span
  m=''2142920''>sees</span> <span m=''2143180''>if</span> <span m=''2143290''>anything''s</span>
  <span m=''2143830''>stored.</span> <span m=''2144440''>Let''s</span> <span m=''2144660''>assume</span>
  <span m=''2144930''>that</span> <span m=''2145030''>get</span> <span m=''2145280''>is</span>
  <span m=''2145410''>implemented.</span> <span m=''2145930''>So if</span> <span m=''2146130''>nothing</span>
  <span m=''2146930''>is</span> <span m=''2147090''>stored</span> <span m=''2147410''>there,</span>
  <span m=''2148190''>it''ll</span> <span m=''2150730''>return</span> <span m=''2151230''>the</span>
  <span m=''2151370''>empty</span> <span m=''2151620''>list.</span> <span m=''2152560''>So</span>
  <span m=''2152860''>it</span> <span m=''2153020''>says,</span> <span m=''2153190''>if</span>
  <span m=''2153650''>there''s</span> <span m=''2154040''>actually</span> <span m=''2154410''>something</span>
  <span m=''2154730''>stored</span> <span m=''2155130''>there,</span> <span m=''2156680''>if</span>
  <span m=''2157000''>the</span> <span m=''2157340''>procedure</span> <span m=''2158890''>here</span>
  <span m=''2159140''>is</span> <span m=''2159280''>not</span> <span m=''2159930''>no,</span>
  <span m=''2162960''>then</span> <span m=''2163770''>it''ll</span> <span m=''2163990''>take</span>
  <span m=''2164760''>the</span> <span m=''2164920''>procedure</span> <span m=''2165900''>that</span>
  <span m=''2166050''>it</span> <span m=''2166210''>found</span> <span m=''2166450''>in</span>
  <span m=''2166510''>the</span> <span m=''2166640''>table</span> <span m=''2169460''>and</span>
  <span m=''2169900''>apply</span> <span m=''2170330''>it</span> <span m=''2170980''>to</span>
  <span m=''2171150''>the</span> <span m=''2171240''>contents</span> <span m=''2174330''>of</span>
  <span m=''2174520''>the</span> <span m=''2174640''>object.</span> <span m=''2178042''>And</span>
  <span m=''2178530''>otherwise</span> <span m=''2179060''>if</span> <span m=''2179160''>there</span>
  <span m=''2179250''>was</span> <span m=''2179400''>nothing</span> <span m=''2179700''>stored</span>
  <span m=''2180110''>there,</span> <span m=''2180760''>it''ll--</span> <span m=''2181445''>well</span>
  <span m=''2181780''>we</span> <span m=''2182010''>can</span> <span m=''2182130''>decide.</span>
  <span m=''2182435''>In</span> <span m=''2182740''>this</span> <span m=''2183020''>case</span>
  <span m=''2183210''>let''s</span> <span m=''2183340''>have it</span> <span m=''2184400''>put</span>
  <span m=''2184570''>out</span> <span m=''2184690''>an</span> <span m=''2184790''>error</span>
  <span m=''2185020''>message</span> <span m=''2185530''>saying,</span> <span m=''2185920''>undefined</span>
  <span m=''2186540''>operator.</span> <span m=''2188650''>No</span> <span m=''2188970''>operator</span>
  <span m=''2189520''>for</span> <span m=''2189650''>this</span> <span m=''2189910''>type.</span>
  <span m=''2192770''>Or</span> <span m=''2193040''>some</span> <span m=''2193260''>appropriate</span>
  <span m=''2193820''>error</span> <span m=''2194030''>message.</span> </p><p><span
  m=''2199150''>OK?</span> <span m=''2199300''>And</span> <span m=''2199500''>that</span>
  <span m=''2200060''>replaces</span> <span m=''2200570''>the</span> <span m=''2200650''>manager.</span>
  <span m=''2201890''>How do</span> <span m=''2202080''>we</span> <span m=''2202240''>really</span>
  <span m=''2202500''>use</span> <span m=''2202790''>it?</span> <span m=''2203960''>Well</span>
  <span m=''2204200''>what</span> <span m=''2204320''>we</span> <span m=''2204430''>say</span>
  <span m=''2204710''>is</span> <span m=''2206360''>we''ll</span> <span m=''2206480''>go</span>
  <span m=''2206640''>off</span> <span m=''2206810''>and</span> <span m=''2206990''>define</span>
  <span m=''2208040''>our</span> <span m=''2208190''>generic</span> <span m=''2208580''>selectors</span>
  <span m=''2209000''>using</span> <span m=''2209250''>operate.</span> <span m=''2210040''>We''ll</span>
  <span m=''2210240''>say</span> <span m=''2210460''>that</span> <span m=''2210820''>the</span>
  <span m=''2215040''>real-part</span> <span m=''2215370''>of</span> <span m=''2215420''>an</span>
  <span m=''2215480''>object</span> <span m=''2216040''>is</span> <span m=''2216190''>found</span>
  <span m=''2216510''>by</span> <span m=''2217140''>operating</span> <span m=''2220370''>on</span>
  <span m=''2220580''>the</span> <span m=''2220670''>object</span> <span m=''2223940''>with</span>
  <span m=''2224070''>the</span> <span m=''2224160''>name</span> <span m=''2224390''>of</span>
  <span m=''2224450''>the</span> <span m=''2224550''>operation</span> <span m=''2225010''>being</span>
  <span m=''2225220''>real-part.</span> <span m=''2228070''>And</span> <span m=''2228410''>then</span>
  <span m=''2228520''>similarly,</span> <span m=''2229070''>imaginary-part is</span>
  <span m=''2229970''>operate</span> <span m=''2230870''>using</span> <span m=''2231140''>the</span>
  <span m=''2231220''>name</span> <span m=''2231420''>imaginary-part</span> <span
  m=''2232250''>and</span> <span m=''2232380''>magnitude</span> <span m=''2233490''>and</span>
  <span m=''2233650''>angle.</span> <span m=''2236080''>That''s</span> <span m=''2236620''>our</span>
  <span m=''2236740''>implementation.</span> <span m=''2237430''>That</span> <span
  m=''2237710''>plus</span> <span m=''2238000''>the</span> <span m=''2238100''>tape</span>
  <span m=''2238700''>plus</span> <span m=''2239000''>the</span> <span m=''2239460''>operate</span>
  <span m=''2239940''>procedure.</span> <span m=''2241330''>And</span> <span m=''2241430''>the</span>
  <span m=''2241520''>table</span> <span m=''2241900''>effectively</span> <span m=''2242340''>replaces</span>
  <span m=''2242870''>what</span> <span m=''2243020''>the</span> <span m=''2243100''>manager</span>
  <span m=''2243500''>used</span> <span m=''2243720''>to</span> <span m=''2243800''>do.</span>
  </p><p><span m=''2244150''>Let''s</span> <span m=''2244340''>just</span> <span m=''2245100''>go</span>
  <span m=''2245240''>through</span> <span m=''2245430''>that</span> <span m=''2246110''>slowly</span>
  <span m=''2246700''>to</span> <span m=''2246760''>show</span> <span m=''2246900''>you</span>
  <span m=''2247040''>what''s</span> <span m=''2247230''>going</span> <span m=''2247490''>on.</span>
  <span m=''2247900''>Suppose</span> <span m=''2249480''>I</span> <span m=''2249650''>have</span>
  <span m=''2251320''>one</span> <span m=''2251610''>of</span> <span m=''2251680''>Martha''s</span>
  <span m=''2252120''>complex</span> <span m=''2252580''>numbers.</span> <span m=''2255520''>It''s</span>
  <span m=''2255670''>got</span> <span m=''2256070''>magnitude</span> <span m=''2257210''>1
  and</span> <span m=''2257690''>angle</span> <span m=''2258310''>2.</span> <span
  m=''2259100''>And</span> <span m=''2259240''>it''s</span> <span m=''2259370''>one</span>
  <span m=''2259520''>of</span> <span m=''2259620''>Martha''s.</span> <span m=''2260220''>So</span>
  <span m=''2260470''>it''s</span> <span m=''2261810''>labeled</span> <span m=''2262470''>here,</span>
  <span m=''2264880''>polar.</span> <span m=''2267120''>Let''s</span> <span m=''2267240''>call</span>
  <span m=''2267430''>that</span> <span m=''2267530''>z.</span> <span m=''2268000''>Suppose</span>
  <span m=''2268580''>that''s z.</span> <span m=''2271770''>And</span> <span m=''2271930''>suppose</span>
  <span m=''2272740''>with</span> <span m=''2272860''>this</span> <span m=''2273020''>implementation</span>
  <span m=''2273720''>someone</span> <span m=''2274050''>comes</span> <span m=''2274320''>up</span>
  <span m=''2274840''>and</span> <span m=''2275110''>asks</span> <span m=''2275600''>for</span>
  <span m=''2276640''>the</span> <span m=''2276780''>real-part of z.</span> <span
  m=''2284870''>Well</span> <span m=''2286000''>real-part</span> <span m=''2286460''>now</span>
  <span m=''2286610''>is</span> <span m=''2286710''>defined</span> <span m=''2287050''>in</span>
  <span m=''2287120''>terms</span> <span m=''2287350''>of</span> <span m=''2287460''>operate.</span>
  <span m=''2288920''>So</span> <span m=''2289300''>that''s</span> <span m=''2289540''>equivalent</span>
  <span m=''2290030''>to</span> <span m=''2290130''>saying</span> <span m=''2292120''>operate</span>
  <span m=''2297580''>with</span> <span m=''2297730''>the</span> <span m=''2297810''>name</span>
  <span m=''2298120''>of</span> <span m=''2298330''>the</span> <span m=''2298470''>operator</span>
  <span m=''2299000''>being</span> <span m=''2299270''>real-part,</span> <span m=''2299870''>the</span>
  <span m=''2299940''>symbol</span> <span m=''2300350''>real-part</span> <span m=''2304120''>on</span>
  <span m=''2304360''>z.</span> <span m=''2307060''>And now</span> <span m=''2307230''>operate</span>
  <span m=''2307780''>comes.</span> <span m=''2308090''>It''s</span> <span m=''2308220''>going</span>
  <span m=''2308300''>to</span> <span m=''2308380''>look</span> <span m=''2308580''>in</span>
  <span m=''2308690''>the</span> <span m=''2308800''>table,</span> <span m=''2311060''>and</span>
  <span m=''2311200''>it''s</span> <span m=''2311340''>going</span> <span m=''2311410''>to</span>
  <span m=''2311480''>try</span> <span m=''2311720''>and</span> <span m=''2311840''>find</span>
  <span m=''2312080''>something</span> <span m=''2312730''>stored</span> <span m=''2313750''>under--</span>
  <span m=''2318830''>the</span> <span m=''2319220''>operation</span> <span m=''2319760''>is</span>
  <span m=''2319870''>going</span> <span m=''2320010''>to</span> <span m=''2320050''>apply</span>
  <span m=''2320810''>by</span> <span m=''2320930''>looking</span> <span m=''2321250''>in</span>
  <span m=''2321310''>the</span> <span m=''2321380''>table</span> <span m=''2322160''>under</span>
  <span m=''2324820''>the</span> <span m=''2325140''>type</span> <span m=''2325500''>of</span>
  <span m=''2325610''>the</span> <span m=''2325730''>object.</span> <span m=''2326225''>And</span>
  <span m=''2326720''>the</span> <span m=''2326940''>type</span> <span m=''2327230''>of</span>
  <span m=''2327340''>z</span> <span m=''2327540''>is</span> <span m=''2327660''>polar.</span>
  <span m=''2328790''>So it''s going to</span> <span m=''2329060''>look</span> <span
  m=''2329270''>and</span> <span m=''2329370''>say,</span> <span m=''2329590''>can</span>
  <span m=''2329710''>I</span> <span m=''2329780''>get</span> <span m=''2330480''>using</span>
  <span m=''2330800''>polar?</span> <span m=''2332990''>And</span> <span m=''2335180''>the</span>
  <span m=''2335310''>operation</span> <span m=''2336030''>name,</span> <span m=''2337670''>which</span>
  <span m=''2337890''>was</span> <span m=''2338030''>real-part.</span> <span m=''2345960''>It''s
  going to</span> <span m=''2346120''>look</span> <span m=''2346350''>in</span> <span
  m=''2346480''>there</span> <span m=''2347680''>and</span> <span m=''2347920''>apply</span>
  <span m=''2348330''>that</span> <span m=''2348730''>to</span> <span m=''2349490''>the</span>
  <span m=''2349610''>contents</span> <span m=''2352730''>of</span> <span m=''2353170''>z.</span>
  <span m=''2354930''>And</span> <span m=''2355350''>that?</span> <span m=''2355650''>If</span>
  <span m=''2355770''>everything</span> <span m=''2356110''>was</span> <span m=''2356240''>set</span>
  <span m=''2356420''>up</span> <span m=''2356550''>correctly,</span> <span m=''2357720''>this</span>
  <span m=''2358090''>thing</span> <span m=''2360090''>is</span> <span m=''2360270''>the</span>
  <span m=''2360350''>procedure</span> <span m=''2360810''>that</span> <span m=''2360980''>Martha</span>
  <span m=''2361300''>put</span> <span m=''2361530''>there.</span> <span m=''2361700''>This</span>
  <span m=''2361880''>is</span> <span m=''2362000''>real-part-polar.</span> <span
  m=''2370790''>And</span> <span m=''2372160''>this</span> <span m=''2372720''>is</span>
  <span m=''2373970''>z</span> <span m=''2374260''>without</span> <span m=''2374620''>its</span>
  <span m=''2374830''>type.</span> <span m=''2375130''>The</span> <span m=''2375580''>thing</span>
  <span m=''2375790''>that</span> <span m=''2375940''>Martha</span> <span m=''2376660''>originally</span>
  <span m=''2377180''>designed</span> <span m=''2377650''>those</span> <span m=''2377860''>procedures</span>
  <span m=''2378310''>to</span> <span m=''2378420''>work</span> <span m=''2378670''>on,</span>
  <span m=''2379420''>which</span> <span m=''2379680''>is</span> <span m=''2379810''>1,</span>
  <span m=''2380070''>2.</span> </p><p><span m=''2383790''>And</span> <span m=''2383930''>so</span>
  <span m=''2384100''>operate</span> <span m=''2384660''>sort</span> <span m=''2384780''>of</span>
  <span m=''2384910''>does</span> <span m=''2385140''>uniformly</span> <span m=''2386560''>what</span>
  <span m=''2386740''>the</span> <span m=''2386810''>manager</span> <span m=''2387210''>used</span>
  <span m=''2387370''>to</span> <span m=''2387460''>do</span> <span m=''2387700''>sort</span>
  <span m=''2387840''>of</span> <span m=''2387990''>all</span> <span m=''2388170''>over</span>
  <span m=''2388320''>the</span> <span m=''2388430''>system.</span> <span m=''2389450''>It</span>
  <span m=''2389590''>finds</span> <span m=''2389950''>the</span> <span m=''2390040''>right</span>
  <span m=''2390300''>thing,</span> <span m=''2390510''>looks</span> <span m=''2390730''>in</span>
  <span m=''2390820''>the</span> <span m=''2390920''>table,</span> <span m=''2391500''>strips</span>
  <span m=''2391990''>off</span> <span m=''2392170''>the</span> <span m=''2392290''>type,</span>
  <span m=''2393630''>and</span> <span m=''2393810''>passes</span> <span m=''2394160''>it</span>
  <span m=''2394250''>down</span> <span m=''2394500''>into</span> <span m=''2396520''>the</span>
  <span m=''2396600''>person</span> <span m=''2396880''>who</span> <span m=''2396960''>handles</span>
  <span m=''2397340''>it.</span> </p><p><span m=''2399160''>This</span> <span m=''2400520''>is</span>
  <span m=''2400660''>another,</span> <span m=''2402430''>and,</span> <span m=''2402550''>you</span>
  <span m=''2402640''>can</span> <span m=''2402760''>see,</span> <span m=''2403310''>more</span>
  <span m=''2403520''>flexible</span> <span m=''2404490''>for</span> <span m=''2404660''>most</span>
  <span m=''2404980''>purposes,</span> <span m=''2406320''>way</span> <span m=''2406570''>of</span>
  <span m=''2406660''>implementing</span> <span m=''2407120''>generic</span> <span
  m=''2407500''>operators.</span> <span m=''2407990''>And</span> <span m=''2408090''>it''s</span>
  <span m=''2408330''>called</span> <span m=''2409270''>data-directed</span> <span
  m=''2415060''>programming.</span> <span m=''2420350''>And</span> <span m=''2420450''>the</span>
  <span m=''2420550''>idea</span> <span m=''2420805''>of</span> <span m=''2421060''>that</span>
  <span m=''2421640''>is</span> <span m=''2423420''>in</span> <span m=''2423570''>some</span>
  <span m=''2423790''>sense</span> <span m=''2424050''>the</span> <span m=''2424190''>data</span>
  <span m=''2424480''>objects</span> <span m=''2424920''>themselves,</span> <span
  m=''2426080''>those</span> <span m=''2426270''>little</span> <span m=''2426420''>complex</span>
  <span m=''2426830''>numbers</span> <span m=''2427090''>that</span> <span m=''2427180''>are</span>
  <span m=''2427260''>floating</span> <span m=''2427590''>around</span> <span m=''2427710''>the</span>
  <span m=''2427830''>system,</span> <span m=''2428690''>are</span> <span m=''2428890''>carrying</span>
  <span m=''2429500''>with</span> <span m=''2429700''>them</span> <span m=''2430030''>the</span>
  <span m=''2430340''>information</span> <span m=''2431280''>about</span> <span m=''2431890''>how</span>
  <span m=''2432080''>you</span> <span m=''2432230''>should</span> <span m=''2432400''>operate</span>
  <span m=''2432790''>on</span> <span m=''2433060''>them.</span> </p><p><span m=''2435390''>Let''s</span>
  <span m=''2435870''>break for</span> <span m=''2436190''>questions.</span> <span
  m=''2441000''>Yes.</span> </p><p><span m=''2441240''>AUDIENCE: What do</span> <span
  m=''2441380''>you</span> <span m=''2441520''>have</span> <span m=''2441790''>stored</span>
  <span m=''2442065''>in</span> <span m=''2442340''>that</span> <span m=''2442710''>data</span>
  <span m=''2442970''>object?</span> <span m=''2443390''>You</span> <span m=''2443510''>have</span>
  <span m=''2444250''>the</span> <span m=''2444390''>data</span> <span m=''2444740''>itself,</span>
  <span m=''2445350''>you</span> <span m=''2445630''>have</span> <span m=''2446390''>its</span>
  <span m=''2446680''>type,</span> <span m=''2447210''>and</span> <span m=''2447330''>you</span>
  <span m=''2447590''>have</span> <span m=''2447850''>the</span> <span m=''2447980''>operations</span>
  <span m=''2448830''>for</span> <span m=''2448970''>that</span> <span m=''2449240''>type?</span>
  <span m=''2449690''>Or</span> <span m=''2450270''>where are</span> <span m=''2450490''>the</span>
  <span m=''2450690''>operations</span> <span m=''2452137''>that you</span> <span
  m=''2452624''>found?</span> </p><p><span m=''2453600''>PROFESSOR: OK,</span> <span
  m=''2453810''>let</span> <span m=''2453910''>me--</span> <span m=''2454980''>yeah,</span>
  <span m=''2455600''>that''s</span> <span m=''2455840''>a</span> <span m=''2455880''>good</span>
  <span m=''2456050''>question.</span> <span m=''2456500''>Because</span> <span m=''2456600''>it</span>
  <span m=''2458210''>raises</span> <span m=''2458480''>other</span> <span m=''2458700''>possibilities</span>
  <span m=''2459510''>of</span> <span m=''2459600''>how</span> <span m=''2459700''>you</span>
  <span m=''2459860''>might</span> <span m=''2460070''>do</span> <span m=''2460250''>it.</span>
  <span m=''2460750''>And</span> <span m=''2460810''>of</span> <span m=''2460950''>course</span>
  <span m=''2461090''>there</span> <span m=''2461180''>are</span> <span m=''2461200''>a</span>
  <span m=''2461310''>lot</span> <span m=''2461420''>of</span> <span m=''2461530''>possibilities.</span>
  <span m=''2464200''>In</span> <span m=''2464420''>this</span> <span m=''2464660''>particular</span>
  <span m=''2465310''>implementation,</span> <span m=''2466300''>what''s</span> <span
  m=''2466540''>sitting</span> <span m=''2466820''>in</span> <span m=''2466930''>this</span>
  <span m=''2467010''>data</span> <span m=''2467310''>object,</span> <span m=''2469050''>for</span>
  <span m=''2469180''>example,</span> <span m=''2470520''>is</span> <span m=''2470770''>the</span>
  <span m=''2470900''>data</span> <span m=''2471080''>itself--</span> <span m=''2471630''>which</span>
  <span m=''2471780''>in</span> <span m=''2471860''>this</span> <span m=''2472020''>case</span>
  <span m=''2472240''>is</span> <span m=''2472320''>a</span> <span m=''2472380''>pair</span>
  <span m=''2472650''>of</span> <span m=''2472730''>1</span> <span m=''2472950''>and</span>
  <span m=''2473090''>2--</span> <span m=''2474980''>and</span> <span m=''2475250''>also</span>
  <span m=''2476030''>a</span> <span m=''2476100''>symbol.</span> <span m=''2476550''>This</span>
  <span m=''2476710''>is</span> <span m=''2476850''>the</span> <span m=''2476940''>symbol,</span>
  <span m=''2477830''>the</span> <span m=''2477890''>word</span> <span m=''2478050''>P-O-L-A-R,</span>
  <span m=''2480630''>and</span> <span m=''2480820''>that''s</span> <span m=''2481000''>what''s</span>
  <span m=''2481140''>sitting</span> <span m=''2481450''>in</span> <span m=''2481540''>this</span>
  <span m=''2481610''>data</span> <span m=''2481890''>object.</span> </p><p><span
  m=''2484870''>Where are</span> <span m=''2485130''>the</span> <span m=''2485260''>operations</span>
  <span m=''2485950''>themselves?</span> <span m=''2486690''>The</span> <span m=''2486970''>operations</span>
  <span m=''2487860''>are</span> <span m=''2487980''>sitting</span> <span m=''2488300''>in</span>
  <span m=''2488420''>the</span> <span m=''2488530''>table.</span> <span m=''2489850''>So</span>
  <span m=''2490120''>in</span> <span m=''2490260''>this</span> <span m=''2490410''>table,</span>
  <span m=''2493700''>the</span> <span m=''2493950''>rows</span> <span m=''2494250''>and</span>
  <span m=''2494380''>columns</span> <span m=''2494820''>of</span> <span m=''2494890''>the</span>
  <span m=''2494990''>table</span> <span m=''2495360''>are</span> <span m=''2495450''>labeled</span>
  <span m=''2495870''>by</span> <span m=''2496020''>symbols.</span> <span m=''2498230''>So</span>
  <span m=''2499040''>when</span> <span m=''2499340''>I store</span> <span m=''2499430''>something
  in</span> <span m=''2499740''>this</span> <span m=''2499870''>table,</span> <span
  m=''2500140''>the</span> <span m=''2500320''>key</span> <span m=''2500500''>might</span>
  <span m=''2500690''>be</span> <span m=''2500810''>the</span> <span m=''2500910''>symbol</span>
  <span m=''2501300''>polar</span> <span m=''2503540''>and</span> <span m=''2503660''>the</span>
  <span m=''2503780''>symbol</span> <span m=''2506270''>magnitude.</span> <span m=''2508240''>And</span>
  <span m=''2508340''>I</span> <span m=''2508440''>think</span> <span m=''2508650''>by</span>
  <span m=''2508750''>writing</span> <span m=''2509120''>it</span> <span m=''2509200''>this</span>
  <span m=''2509370''>way</span> <span m=''2510200''>I''ve</span> <span m=''2510370''>been</span>
  <span m=''2510510''>very</span> <span m=''2510760''>confusing.</span> <span m=''2511310''>Because</span>
  <span m=''2511630''>what''s</span> <span m=''2511800''>really</span> <span m=''2512040''>sitting</span>
  <span m=''2512290''>here</span> <span m=''2512460''>isn''t--</span> <span m=''2513160''>when
  I</span> <span m=''2513290''>wrote</span> <span m=''2513510''>magnitude</span> <span
  m=''2514060''>polar,</span> <span m=''2517110''>what</span> <span m=''2517240''>I</span>
  <span m=''2517310''>mean</span> <span m=''2517520''>is</span> <span m=''2517680''>the</span>
  <span m=''2517810''>procedure</span> <span m=''2518360''>magnitude</span> <span
  m=''2518880''>polar.</span> <span m=''2519850''>And</span> <span m=''2520020''>probably</span>
  <span m=''2520450''>what</span> <span m=''2520590''>I</span> <span m=''2520650''>really</span>
  <span m=''2521020''>should</span> <span m=''2521210''>have</span> <span m=''2521360''>written--</span>
  <span m=''2522580''>except</span> <span m=''2522860''>it''s</span> <span m=''2523030''>too</span>
  <span m=''2523190''>small</span> <span m=''2523570''>for</span> <span m=''2523690''>me</span>
  <span m=''2523820''>to</span> <span m=''2523960''>write</span> <span m=''2524200''>in</span>
  <span m=''2524250''>this</span> <span m=''2524430''>little</span> <span m=''2524610''>space--</span>
  <span m=''2525580''>is</span> <span m=''2525740''>something</span> <span m=''2526060''>like</span>
  <span m=''2526580''>lambda</span> <span m=''2527950''>of</span> <span m=''2528150''>z,</span>
  <span m=''2530550''>the</span> <span m=''2530830''>thing</span> <span m=''2531090''>that</span>
  <span m=''2531250''>Martha</span> <span m=''2531600''>wrote</span> <span m=''2532010''>to</span>
  <span m=''2532170''>implement.</span> <span m=''2534710''>And</span> <span m=''2534850''>then</span>
  <span m=''2534970''>you</span> <span m=''2535070''>can</span> <span m=''2535180''>see</span>
  <span m=''2535400''>from</span> <span m=''2535570''>that,</span> <span m=''2535750''>there''s</span>
  <span m=''2535950''>another</span> <span m=''2536290''>way</span> <span m=''2536490''>that</span>
  <span m=''2536620''>I</span> <span m=''2536710''>alluded</span> <span m=''2537100''>to</span>
  <span m=''2537300''>of</span> <span m=''2537640''>solving</span> <span m=''2538070''>this</span>
  <span m=''2538230''>name</span> <span m=''2538500''>conflict</span> <span m=''2539190''>problem,</span>
  <span m=''2540070''>which</span> <span m=''2540250''>is</span> <span m=''2540380''>that</span>
  <span m=''2540500''>George</span> <span m=''2540770''>and</span> <span m=''2540870''>Martha</span>
  <span m=''2541460''>never</span> <span m=''2541710''>have</span> <span m=''2541910''>to</span>
  <span m=''2542010''>name</span> <span m=''2542250''>their</span> <span m=''2542380''>procedures</span>
  <span m=''2542870''>at</span> <span m=''2542950''>all.</span> <span m=''2543150''>They</span>
  <span m=''2543270''>can</span> <span m=''2543400''>just</span> <span m=''2543620''>stick</span>
  <span m=''2543780''>the</span> <span m=''2545490''>anonymous</span> <span m=''2545950''>things</span>
  <span m=''2546170''>generated</span> <span m=''2546590''>by</span> <span m=''2546710''>lambda</span>
  <span m=''2547060''>directly</span> <span m=''2547460''>into</span> <span m=''2547590''>the</span>
  <span m=''2547710''>table.</span> </p><p><span m=''2548660''>There''s</span> <span
  m=''2548870''>also</span> <span m=''2549820''>another</span> <span m=''2550250''>thing</span>
  <span m=''2550440''>that</span> <span m=''2550770''>your</span> <span m=''2550950''>question</span>
  <span m=''2551330''>raises,</span> <span m=''2552380''>is</span> <span m=''2552540''>the</span>
  <span m=''2552640''>possibility</span> <span m=''2553280''>that</span> <span m=''2553460''>maybe</span>
  <span m=''2554720''>what</span> <span m=''2555070''>I</span> <span m=''2555150''>would</span>
  <span m=''2555310''>like</span> <span m=''2555580''>somehow</span> <span m=''2556010''>is
  to</span> <span m=''2556080''>store</span> <span m=''2556580''>in</span> <span m=''2556720''>this</span>
  <span m=''2556850''>data</span> <span m=''2557570''>object</span> <span m=''2557930''>not</span>
  <span m=''2558150''>the</span> <span m=''2558220''>symbol</span> <span m=''2558580''>P-O-L-A-R</span>
  <span m=''2559740''>but</span> <span m=''2560120''>maybe</span> <span m=''2560460''>actually</span>
  <span m=''2560850''>all</span> <span m=''2561000''>the</span> <span m=''2561120''>operations</span>
  <span m=''2561750''>themselves.</span> <span m=''2563520''>And</span> <span m=''2563900''>that''s</span>
  <span m=''2564210''>another</span> <span m=''2564500''>way</span> <span m=''2564660''>to</span>
  <span m=''2564760''>organize</span> <span m=''2565250''>the</span> <span m=''2565290''>system,</span>
  <span m=''2565640''>called</span> <span m=''2565860''>message</span> <span m=''2566210''>passing.</span>
  <span m=''2568650''>So</span> <span m=''2568770''>there</span> <span m=''2568860''>are</span>
  <span m=''2568880''>a</span> <span m=''2569000''>lot</span> <span m=''2569110''>of</span>
  <span m=''2569230''>ways</span> <span m=''2569470''>you</span> <span m=''2569550''>can</span>
  <span m=''2569670''>do</span> <span m=''2569850''>it.</span> </p><p><span m=''2574640''>AUDIENCE:
  Therefore</span> <span m=''2575250''>if</span> <span m=''2575910''>Martha</span>
  <span m=''2576205''>and</span> <span m=''2576500''>George</span> <span m=''2576910''>had</span>
  <span m=''2577160''>used</span> <span m=''2577480''>the</span> <span m=''2577560''>same</span>
  <span m=''2578040''>procedure</span> <span m=''2578620''>names,</span> <span m=''2579200''>it</span>
  <span m=''2579650''>would</span> <span m=''2579820''>be</span> <span m=''2579960''>OK</span>
  <span m=''2580330''>because</span> <span m=''2580630''>it</span> <span m=''2580700''>wouldn''t</span>
  <span m=''2580980''>look</span> <span m=''2581230''>[UNINTELLIGIBLE].</span> </p><p><span
  m=''2582560''>PROFESSOR: That''s</span> <span m=''2582780''>right.</span> <span
  m=''2583010''>That''s</span> <span m=''2584500''>right.</span> <span m=''2584890''>See,</span>
  <span m=''2585610''>they</span> <span m=''2585750''>wouldn''t</span> <span m=''2586000''>even</span>
  <span m=''2586270''>have</span> <span m=''2586500''>to</span> <span m=''2586680''>name</span>
  <span m=''2586940''>their</span> <span m=''2587060''>procedures</span> <span m=''2587560''>at</span>
  <span m=''2587640''>all.</span> <span m=''2589470''>What</span> <span m=''2589780''>George</span>
  <span m=''2590040''>could</span> <span m=''2590170''>have</span> <span m=''2590290''>written</span>
  <span m=''2590910''>instead</span> <span m=''2591260''>of</span> <span m=''2591350''>saying</span>
  <span m=''2591640''>put</span> <span m=''2592190''>in</span> <span m=''2592350''>the</span>
  <span m=''2592440''>table</span> <span m=''2592880''>under</span> <span m=''2593070''>rectangular-</span>
  <span m=''2594220''>and</span> <span m=''2594600''>real-part,</span> <span m=''2596370''>the</span>
  <span m=''2596580''>procedure</span> <span m=''2596890''>real-part</span> <span
  m=''2597410''>rectangular,</span> <span m=''2597980''>George</span> <span m=''2598330''>could</span>
  <span m=''2598490''>have</span> <span m=''2598640''>written</span> <span m=''2599110''>put</span>
  <span m=''2599380''>under</span> <span m=''2599660''>rectangular</span> <span m=''2600550''>real-part,</span>
  <span m=''2601310''>lambda</span> <span m=''2601740''>of</span> <span m=''2601980''>z,</span>
  <span m=''2602520''>such</span> <span m=''2602780''>and</span> <span m=''2602890''>such,</span>
  <span m=''2603080''>and</span> <span m=''2603180''>such</span> <span m=''2603390''>and</span>
  <span m=''2603500''>such.</span> <span m=''2604540''>And</span> <span m=''2604640''>the</span>
  <span m=''2604750''>system</span> <span m=''2605080''>would work</span> <span m=''2605380''>completely</span>
  <span m=''2605950''>the</span> <span m=''2606300''>same.</span> </p><p><span m=''2607330''>AUDIENCE:
  My</span> <span m=''2607480''>question</span> <span m=''2607960''>is,</span> <span
  m=''2608160''>Martha</span> <span m=''2609970''>could</span> <span m=''2610200''>have</span>
  <span m=''2610430''>put</span> <span m=''2611220''>key1</span> <span m=''2611750''>key2</span>
  <span m=''2612980''>real-part,</span> <span m=''2614110''>and</span> <span m=''2614660''>George</span>
  <span m=''2614970''>could</span> <span m=''2615090''>have</span> <span m=''2615260''>put</span>
  <span m=''2616110''>key1</span> <span m=''2616570''>key2</span> <span m=''2617120''>real-part,</span>
  <span m=''2617790''>and</span> <span m=''2618000''>as</span> <span m=''2618210''>long</span>
  <span m=''2618410''>as</span> <span m=''2618490''>they</span> <span m=''2618580''>defined</span>
  <span m=''2618950''>them</span> <span m=''2619080''>differently</span> <span m=''2619840''>they</span>
  <span m=''2620060''>wouldn''t</span> <span m=''2620280''>have</span> <span m=''2620370''>had</span>
  <span m=''2620580''>any</span> <span m=''2620935''>conflicts, right?</span> </p><p><span
  m=''2621290''>PROFESSOR: Yes,</span> <span m=''2621510''>that</span> <span m=''2622080''>would</span>
  <span m=''2622180''>all</span> <span m=''2622400''>be</span> <span m=''2622590''>OK</span>
  <span m=''2622930''>except</span> <span m=''2623260''>for</span> <span m=''2623360''>the</span>
  <span m=''2623450''>fact</span> <span m=''2624980''>that</span> <span m=''2625130''>if</span>
  <span m=''2625240''>you</span> <span m=''2625340''>imagine</span> <span m=''2625630''>George</span>
  <span m=''2625980''>and</span> <span m=''2626060''>Martha</span> <span m=''2626340''>typing</span>
  <span m=''2626700''>at</span> <span m=''2626780''>the</span> <span m=''2626860''>same</span>
  <span m=''2627130''>console</span> <span m=''2627580''>with</span> <span m=''2627680''>the</span>
  <span m=''2627790''>same</span> <span m=''2628060''>meanings</span> <span m=''2628400''>for</span>
  <span m=''2628550''>all</span> <span m=''2628670''>their</span> <span m=''2628810''>names,</span>
  <span m=''2629870''>and</span> <span m=''2630000''>it</span> <span m=''2630090''>would</span>
  <span m=''2630180''>get</span> <span m=''2630320''>confused</span> <span m=''2630760''>by</span>
  <span m=''2630870''>real-part,</span> <span m=''2631280''>but</span> <span m=''2631390''>there
  are</span> <span m=''2631520''>ways</span> <span m=''2631720''>to</span> <span m=''2631830''>arrange</span>
  <span m=''2632150''>that,</span> <span m=''2632370''>too.</span> <span m=''2632800''>And
  in</span> <span m=''2633040''>principle</span> <span m=''2633850''>you''re</span>
  <span m=''2634020''>absolutely</span> <span m=''2634440''>right.</span> <span m=''2634980''>If</span>
  <span m=''2635130''>their</span> <span m=''2635250''>names</span> <span m=''2635550''>didn''t</span>
  <span m=''2635730''>conflict--</span> <span m=''2636290''>it''s the</span> <span
  m=''2636390''>objects</span> <span m=''2636780''>that</span> <span m=''2636870''>go</span>
  <span m=''2637020''>in</span> <span m=''2637100''>the</span> <span m=''2637200''>table,</span>
  <span m=''2637490''>not the</span> <span m=''2637700''>names.</span> </p><p><span
  m=''2648200''>OK,</span> <span m=''2648300''>let''s</span> <span m=''2648400''>take</span>
  <span m=''2648560''>a</span> <span m=''2648710''>break.</span> </p><p><span m=''2652493''>[MUSIC--
  "JESU, JOY OF MAN''S DESIRING" BY JOHANN SEBASTIAN BACH]</span> </p><p><span m=''2712880''>All
  right,</span> <span m=''2713030''>well we</span> <span m=''2713250''>just</span>
  <span m=''2713500''>looked</span> <span m=''2713760''>at</span> <span m=''2715280''>data-directed</span>
  <span m=''2716000''>programming</span> <span m=''2717680''>as</span> <span m=''2717900''>a</span>
  <span m=''2717960''>way</span> <span m=''2718300''>of</span> <span m=''2718500''>implementing</span>
  <span m=''2719440''>a</span> <span m=''2719640''>system</span> <span m=''2720420''>that</span>
  <span m=''2720770''>does</span> <span m=''2720940''>arithmetic</span> <span m=''2721440''>on</span>
  <span m=''2721590''>complex</span> <span m=''2722090''>numbers.</span> <span m=''2727420''>So</span>
  <span m=''2727710''>I</span> <span m=''2727780''>had</span> <span m=''2728000''>these</span>
  <span m=''2728170''>operations</span> <span m=''2728960''>in</span> <span m=''2729140''>it</span>
  <span m=''2729700''>called</span> <span m=''2730000''>plus</span> <span m=''2730290''>C</span>
  <span m=''2731440''>and</span> <span m=''2731590''>minus</span> <span m=''2731980''>C,</span>
  <span m=''2732880''>and</span> <span m=''2734100''>multiply,</span> <span m=''2735410''>and</span>
  <span m=''2735600''>divide,</span> <span m=''2736190''>and</span> <span m=''2736400''>maybe</span>
  <span m=''2736740''>some</span> <span m=''2736930''>others.</span> <span m=''2738230''>And</span>
  <span m=''2742850''>that</span> <span m=''2743550''>sat</span> <span m=''2743660''>on</span>
  <span m=''2743830''>top</span> <span m=''2744200''>of--</span> <span m=''2744560''>and</span>
  <span m=''2744780''>this</span> <span m=''2745030''>is</span> <span m=''2745140''>the</span>
  <span m=''2745240''>key</span> <span m=''2745410''>point--</span> <span m=''2745790''>sat</span>
  <span m=''2745890''>on</span> <span m=''2746030''>top</span> <span m=''2746330''>of</span>
  <span m=''2746470''>two</span> <span m=''2747230''>different</span> <span m=''2748430''>representations.</span>
  <span m=''2750340''>A</span> <span m=''2750590''>rectangular</span> <span m=''2752860''>package</span>
  <span m=''2753340''>here,</span> <span m=''2754270''>and</span> <span m=''2754360''>a</span>
  <span m=''2754460''>polar</span> <span m=''2754820''>package.</span> <span m=''2758240''>And</span>
  <span m=''2758460''>maybe</span> <span m=''2758730''>some</span> <span m=''2758900''>more.</span>
  <span m=''2759150''>And</span> <span m=''2759230''>we</span> <span m=''2759310''>saw</span>
  <span m=''2759500''>that</span> <span m=''2759640''>the</span> <span m=''2759720''>whole</span>
  <span m=''2759920''>idea</span> <span m=''2760190''>is</span> <span m=''2760280''>that</span>
  <span m=''2760420''>maybe</span> <span m=''2760660''>some</span> <span m=''2760830''>more</span>
  <span m=''2761450''>are</span> <span m=''2761640''>now</span> <span m=''2761830''>very</span>
  <span m=''2762170''>easy</span> <span m=''2762500''>to add.</span> </p><p><span
  m=''2764670''>But</span> <span m=''2765050''>that</span> <span m=''2765230''>doesn''t</span>
  <span m=''2765480''>really</span> <span m=''2766290''>show</span> <span m=''2766450''>the</span>
  <span m=''2766560''>power</span> <span m=''2767040''>of</span> <span m=''2767400''>this</span>
  <span m=''2767580''>methodology.</span> <span m=''2768900''>Shows</span> <span m=''2769110''>you</span>
  <span m=''2769190''>what''s</span> <span m=''2769390''>going</span> <span m=''2769670''>on.</span>
  <span m=''2770150''>The</span> <span m=''2770330''>power of</span> <span m=''2770670''>the</span>
  <span m=''2770760''>methodology</span> <span m=''2771360''>only</span> <span m=''2771570''>becomes</span>
  <span m=''2771920''>apparent</span> <span m=''2772970''>when</span> <span m=''2773160''>you</span>
  <span m=''2773260''>start</span> <span m=''2773580''>embedding</span> <span m=''2774120''>this</span>
  <span m=''2774310''>in</span> <span m=''2774390''>some</span> <span m=''2774610''>more</span>
  <span m=''2774810''>complex</span> <span m=''2775330''>system.</span> <span m=''2777080''>What</span>
  <span m=''2777190''>I''m</span> <span m=''2777210''>going</span> <span m=''2777350''>to</span>
  <span m=''2777400''>do</span> <span m=''2777530''>now</span> <span m=''2777890''>is</span>
  <span m=''2778050''>embed</span> <span m=''2778450''>this</span> <span m=''2778630''>in</span>
  <span m=''2778780''>some</span> <span m=''2778960''>more</span> <span m=''2779180''>complex</span>
  <span m=''2779730''>system.</span> <span m=''2780250''>Let''s</span> <span m=''2780470''>assume</span>
  <span m=''2781500''>that</span> <span m=''2781750''>what</span> <span m=''2781880''>we</span>
  <span m=''2782020''>really</span> <span m=''2782330''>have</span> <span m=''2782540''>is</span>
  <span m=''2782670''>a</span> <span m=''2782730''>general</span> <span m=''2783210''>kind</span>
  <span m=''2783960''>of</span> <span m=''2784310''>arithmetic</span> <span m=''2784870''>system.</span>
  <span m=''2785280''>So</span> <span m=''2785480''>called</span> <span m=''2785650''>generic</span>
  <span m=''2786390''>arithmetic</span> <span m=''2786930''>system.</span> <span m=''2787240''>And</span>
  <span m=''2787310''>at</span> <span m=''2787390''>the</span> <span m=''2787490''>top</span>
  <span m=''2787840''>level</span> <span m=''2788140''>here,</span> <span m=''2790550''>somebody</span>
  <span m=''2791090''>can</span> <span m=''2791220''>say</span> <span m=''2791690''>add</span>
  <span m=''2791870''>two</span> <span m=''2792060''>things,</span> <span m=''2793350''>or</span>
  <span m=''2794800''>subtract two</span> <span m=''2795520''>things,</span> <span
  m=''2796920''>or</span> <span m=''2797750''>multiply</span> <span m=''2798230''>two</span>
  <span m=''2798450''>things,</span> <span m=''2799900''>or</span> <span m=''2800050''>divide</span>
  <span m=''2800510''>two</span> <span m=''2800710''>things.</span> <span m=''2804140''>And</span>
  <span m=''2804390''>underneath</span> <span m=''2804990''>that</span> <span m=''2805280''>there''s</span>
  <span m=''2805480''>an</span> <span m=''2805550''>abstraction</span> <span m=''2806100''>barrier.</span>
  <span m=''2807930''>And</span> <span m=''2808120''>underneath</span> <span m=''2808530''>this</span>
  <span m=''2808730''>barrier,</span> <span m=''2809510''>is,</span> <span m=''2810090''>say,</span>
  <span m=''2810430''>a</span> <span m=''2810510''>complex</span> <span m=''2811030''>arithmetic</span>
  <span m=''2811990''>package.</span> <span m=''2812850''>And</span> <span m=''2813150''>you</span>
  <span m=''2813370''>can</span> <span m=''2813490''>say,</span> <span m=''2813760''>add</span>
  <span m=''2813930''>two</span> <span m=''2814080''>complex</span> <span m=''2814570''>numbers.</span>
  </p><p><span m=''2815110''>Or</span> <span m=''2815300''>you</span> <span m=''2815420''>might</span>
  <span m=''2815860''>also</span> <span m=''2816190''>have--</span> <span m=''2816560''>remember</span>
  <span m=''2816840''>we</span> <span m=''2816940''>did</span> <span m=''2817050''>a</span>
  <span m=''2817110''>rational</span> <span m=''2817540''>number</span> <span m=''2818460''>package--</span>
  <span m=''2818840''>you</span> <span m=''2818910''>might</span> <span m=''2819060''>have</span>
  <span m=''2819200''>that</span> <span m=''2819430''>sitting</span> <span m=''2819720''>there.</span>
  <span m=''2820190''>And</span> <span m=''2820330''>there</span> <span m=''2820430''>might</span>
  <span m=''2820650''>be a</span> <span m=''2820820''>rational</span> <span m=''2821350''>thing.</span>
  <span m=''2823950''>And</span> <span m=''2824400''>the</span> <span m=''2824990''>rational</span>
  <span m=''2825480''>number</span> <span m=''2825760''>package,</span> <span m=''2827190''>well,</span>
  <span m=''2827300''>has the</span> <span m=''2827510''>things</span> <span m=''2827760''>we</span>
  <span m=''2827880''>implemented.</span> <span m=''2828320''>Plus</span> <span m=''2828640''>rat,</span>
  <span m=''2830160''>and</span> <span m=''2831330''>times</span> <span m=''2831660''>rat,</span>
  <span m=''2833910''>and</span> <span m=''2834330''>so</span> <span m=''2834580''>on.</span>
  <span m=''2835490''>Or</span> <span m=''2835680''>you might</span> <span m=''2835850''>have</span>
  <span m=''2836020''>ordinary</span> <span m=''2836420''>Lisp</span> <span m=''2836670''>numbers.</span>
  <span m=''2837010''>You</span> <span m=''2837110''>might</span> <span m=''2837290''>say</span>
  <span m=''2837500''>add</span> <span m=''2838340''>three</span> <span m=''2838590''>and</span>
  <span m=''2838720''>four.</span> <span m=''2839310''>So</span> <span m=''2839530''>we</span>
  <span m=''2839630''>might</span> <span m=''2839800''>have</span> <span m=''2840070''>ordinary</span>
  <span m=''2840540''>numbers,</span> <span m=''2848310''>in</span> <span m=''2848420''>which</span>
  <span m=''2848600''>case</span> <span m=''2848800''>we</span> <span m=''2848910''>have</span>
  <span m=''2849030''>the</span> <span m=''2849160''>Lisp</span> <span m=''2849670''>supplied</span>
  <span m=''2850240''>plus,</span> <span m=''2851330''>and</span> <span m=''2851600''>minus,</span>
  <span m=''2852760''>and</span> <span m=''2853040''>times,</span> <span m=''2853910''>and</span>
  <span m=''2854110''>slash.</span> </p><p><span m=''2856670''>OK,</span> <span m=''2856900''>so</span>
  <span m=''2857040''>we</span> <span m=''2857140''>might</span> <span m=''2857490''>imagine</span>
  <span m=''2857960''>this</span> <span m=''2858100''>complex</span> <span m=''2858570''>number</span>
  <span m=''2858800''>system</span> <span m=''2859360''>sitting</span> <span m=''2859840''>in</span>
  <span m=''2861180''>a</span> <span m=''2861290''>more</span> <span m=''2861480''>complicated</span>
  <span m=''2862090''>generic</span> <span m=''2862670''>operator</span> <span m=''2863180''>structure</span>
  <span m=''2863580''>at</span> <span m=''2863660''>the</span> <span m=''2863820''>next</span>
  <span m=''2863970''>level</span> <span m=''2864250''>up.</span> <span m=''2867730''>Well</span>
  <span m=''2867850''>how</span> <span m=''2867940''>can</span> <span m=''2868060''>we</span>
  <span m=''2868190''>make</span> <span m=''2868470''>that?</span> <span m=''2869050''>We</span>
  <span m=''2869190''>already</span> <span m=''2869390''>have</span> <span m=''2869590''>the</span>
  <span m=''2869710''>idea,</span> <span m=''2869990''>we''re</span> <span m=''2870080''>just</span>
  <span m=''2870240''>going</span> <span m=''2870320''>to</span> <span m=''2870390''>do</span>
  <span m=''2870560''>it</span> <span m=''2870620''>again.</span> <span m=''2872780''>We''ve</span>
  <span m=''2873000''>implemented</span> <span m=''2873530''>a</span> <span m=''2873600''>rational</span>
  <span m=''2874020''>number</span> <span m=''2874270''>package.</span> <span m=''2874720''>Let''s</span>
  <span m=''2874920''>look</span> <span m=''2875520''>at</span> <span m=''2875690''>how</span>
  <span m=''2875840''>it</span> <span m=''2875910''>has</span> <span m=''2876110''>to</span>
  <span m=''2876190''>be</span> <span m=''2876310''>changed.</span> </p><p><span m=''2881590''>In</span>
  <span m=''2881670''>fact,</span> <span m=''2881940''>at</span> <span m=''2881990''>this</span>
  <span m=''2882160''>level</span> <span m=''2882380''>it doesn''t</span> <span m=''2882530''>have
  to</span> <span m=''2882660''>be</span> <span m=''2882750''>changed</span> <span
  m=''2883080''>at</span> <span m=''2883140''>all.</span> <span m=''2883730''>This</span>
  <span m=''2883900''>is</span> <span m=''2884020''>exactly</span> <span m=''2884560''>the</span>
  <span m=''2884670''>code</span> <span m=''2884950''>that</span> <span m=''2885060''>we</span>
  <span m=''2885170''>wrote</span> <span m=''2885360''>last</span> <span m=''2885640''>time.</span>
  <span m=''2887180''>To</span> <span m=''2887650''>add</span> <span m=''2887930''>two</span>
  <span m=''2888100''>rational</span> <span m=''2888520''>numbers,</span> <span m=''2889890''>remember</span>
  <span m=''2890140''>there</span> <span m=''2890280''>was</span> <span m=''2890360''>this</span>
  <span m=''2890520''>formula.</span> <span m=''2891140''>You</span> <span m=''2891250''>make</span>
  <span m=''2891440''>a</span> <span m=''2891500''>rational</span> <span m=''2891950''>number</span>
  <span m=''2892500''>whose</span> <span m=''2892720''>numerator--</span> <span m=''2894980''>the</span>
  <span m=''2895100''>numerator</span> <span m=''2895480''>of</span> <span m=''2895560''>the</span>
  <span m=''2895690''>first</span> <span m=''2896040''>times</span> <span m=''2896300''>the</span>
  <span m=''2896380''>denominator</span> <span m=''2896960''>of</span> <span m=''2897020''>the</span>
  <span m=''2897330''>second,</span> <span m=''2897990''>plus</span> <span m=''2898660''>the</span>
  <span m=''2899000''>denominator</span> <span m=''2899680''>of</span> <span m=''2899740''>the</span>
  <span m=''2899920''>first</span> <span m=''2900100''>times</span> <span m=''2900320''>the
  numerator of</span> <span m=''2900820''>the</span> <span m=''2900880''>second.</span>
  <span m=''2901520''>And</span> <span m=''2901670''>who''s</span> <span m=''2901820''>denominator</span>
  <span m=''2902410''>is</span> <span m=''2902490''>the</span> <span m=''2902570''>product</span>
  <span m=''2902950''>of</span> <span m=''2903020''>the</span> <span m=''2903100''>denominators.</span>
  <span m=''2905760''>And</span> <span m=''2906250''>minus</span> <span m=''2906660''>rat,</span>
  <span m=''2907190''>and</span> <span m=''2907350''>star</span> <span m=''2907780''>rat,</span>
  <span m=''2908160''>and</span> <span m=''2908330''>slash</span> <span m=''2908730''>rat.</span>
  <span m=''2910580''>And</span> <span m=''2912300''>this</span> <span m=''2912510''>is</span>
  <span m=''2912620''>exactly</span> <span m=''2913210''>the</span> <span m=''2913310''>rational</span>
  <span m=''2913680''>number</span> <span m=''2913900''>package</span> <span m=''2914310''>that</span>
  <span m=''2914420''>we</span> <span m=''2914530''>made</span> <span m=''2914740''>before.</span>
  <span m=''2916310''>We''re</span> <span m=''2916440''>ignoring</span> <span m=''2916730''>the</span>
  <span m=''2916800''>GCD</span> <span m=''2917300''>problem,</span> <span m=''2917760''>but
  let''s</span> <span m=''2918000''>not</span> <span m=''2918140''>worry</span> <span
  m=''2918390''>about</span> <span m=''2918660''>that.</span> </p><p><span m=''2920240''>As</span>
  <span m=''2920530''>implementers</span> <span m=''2921160''>of</span> <span m=''2921290''>this</span>
  <span m=''2921420''>rational</span> <span m=''2921880''>number</span> <span m=''2922150''>package,</span>
  <span m=''2922810''>how</span> <span m=''2922980''>do</span> <span m=''2923090''>we</span>
  <span m=''2923190''>install</span> <span m=''2923620''>it in</span> <span m=''2923760''>the</span>
  <span m=''2923890''>generic</span> <span m=''2924240''>arithmetic</span> <span m=''2924700''>system?</span>
  <span m=''2925570''>Well</span> <span m=''2925680''>that''s</span> <span m=''2925900''>easy.</span>
  <span m=''2928980''>There''s</span> <span m=''2929250''>only</span> <span m=''2929410''>one</span>
  <span m=''2929730''>thing</span> <span m=''2929920''>we</span> <span m=''2930070''>have</span>
  <span m=''2930210''>to</span> <span m=''2930320''>do</span> <span m=''2930440''>differently.</span>
  <span m=''2931840''>Whereas</span> <span m=''2932110''>previously</span> <span m=''2933440''>we</span>
  <span m=''2933560''>said</span> <span m=''2933770''>that</span> <span m=''2934030''>to</span>
  <span m=''2934370''>make</span> <span m=''2934700''>a</span> <span m=''2934780''>rational</span>
  <span m=''2935230''>number</span> <span m=''2936270''>you</span> <span m=''2936400''>built</span>
  <span m=''2936670''>a pair</span> <span m=''2938100''>of</span> <span m=''2938260''>the</span>
  <span m=''2938780''>numerator and</span> <span m=''2939290''>denominator,</span>
  <span m=''2940960''>here</span> <span m=''2941270''>we''ll</span> <span m=''2941400''>not</span>
  <span m=''2941580''>only</span> <span m=''2941750''>build</span> <span m=''2941950''>the</span>
  <span m=''2942040''>pair,</span> <span m=''2942390''>but</span> <span m=''2942570''>we''ll</span>
  <span m=''2942680''>sign</span> <span m=''2943030''>it.</span> <span m=''2943300''>We''ll</span>
  <span m=''2943430''>attach</span> <span m=''2943770''>the</span> <span m=''2943860''>type</span>
  <span m=''2944120''>rational.</span> <span m=''2946120''>That''s</span> <span m=''2946570''>the</span>
  <span m=''2946680''>only</span> <span m=''2947040''>thing</span> <span m=''2947220''>we</span>
  <span m=''2947340''>have</span> <span m=''2947470''>to</span> <span m=''2947590''>do</span>
  <span m=''2947710''>different,</span> <span m=''2948600''>make</span> <span m=''2948800''>it</span>
  <span m=''2948850''>a</span> <span m=''2948940''>typed</span> <span m=''2949320''>data</span>
  <span m=''2949540''>object.</span> </p><p><span m=''2952380''>And</span> <span m=''2952540''>now</span>
  <span m=''2952670''>we''ll</span> <span m=''2952750''>stick</span> <span m=''2952960''>our</span>
  <span m=''2953110''>operations</span> <span m=''2953590''>in</span> <span m=''2953650''>the</span>
  <span m=''2953720''>table.</span> <span m=''2954500''>We''ll</span> <span m=''2954650''>put</span>
  <span m=''2954940''>under</span> <span m=''2955170''>the</span> <span m=''2955270''>symbol</span>
  <span m=''2955600''>rational</span> <span m=''2956960''>and</span> <span m=''2957090''>the</span>
  <span m=''2957220''>operation</span> <span m=''2957820''>add</span> <span m=''2958920''>our</span>
  <span m=''2959070''>procedure,</span> <span m=''2959690''>plus</span> <span m=''2959990''>rat.</span>
  <span m=''2961820''>And,</span> <span m=''2961960''>again,</span> <span m=''2962170''>note</span>
  <span m=''2962410''>this</span> <span m=''2962560''>is</span> <span m=''2962680''>a</span>
  <span m=''2962720''>symbol.</span> <span m=''2963580''>Right?</span> <span m=''2963930''>Quote,</span>
  <span m=''2964870''>unquote,</span> <span m=''2965360''>but</span> <span m=''2965470''>the</span>
  <span m=''2965610''>actual</span> <span m=''2966020''>thing</span> <span m=''2966210''>we''re</span>
  <span m=''2966310''>putting</span> <span m=''2966640''>in</span> <span m=''2966740''>the</span>
  <span m=''2966830''>table</span> <span m=''2967220''>is</span> <span m=''2967330''>the</span>
  <span m=''2967430''>procedure.</span> <span m=''2970060''>And</span> <span m=''2970260''>for</span>
  <span m=''2970960''>how</span> <span m=''2971160''>to</span> <span m=''2971220''>subtract,</span>
  <span m=''2971850''>well</span> <span m=''2972360''>you</span> <span m=''2972470''>subtract</span>
  <span m=''2973700''>rationals</span> <span m=''2975490''>with</span> <span m=''2976060''>minus</span>
  <span m=''2976490''>rat.</span> <span m=''2978270''>And</span> <span m=''2978860''>multiply,</span>
  <span m=''2979620''>and</span> <span m=''2979840''>divide.</span> <span m=''2981090''>And</span>
  <span m=''2981220''>that</span> <span m=''2981350''>is</span> <span m=''2981480''>exactly</span>
  <span m=''2982090''>and</span> <span m=''2982220''>precisely</span> <span m=''2982740''>what</span>
  <span m=''2982870''>we</span> <span m=''2982980''>have</span> <span m=''2983130''>to</span>
  <span m=''2983280''>do</span> <span m=''2983640''>to</span> <span m=''2984270''>fit</span>
  <span m=''2984440''>inside</span> <span m=''2984790''>this</span> <span m=''2984930''>generic</span>
  <span m=''2985280''>arithmetic</span> <span m=''2985770''>system.</span> </p><p><span
  m=''2988510''>Well</span> <span m=''2988730''>how</span> <span m=''2988920''>does</span>
  <span m=''2989050''>the</span> <span m=''2989150''>whole</span> <span m=''2989380''>thing</span>
  <span m=''2989650''>work?</span> <span m=''2991560''>See,</span> <span m=''2991740''>what</span>
  <span m=''2991850''>we</span> <span m=''2991950''>want</span> <span m=''2992200''>to</span>
  <span m=''2992290''>do</span> <span m=''2996380''>is</span> <span m=''2996560''>have</span>
  <span m=''2996730''>some</span> <span m=''2996910''>generic</span> <span m=''2997680''>operators.</span>
  <span m=''3000170''>Have</span> <span m=''3000390''>add and</span> <span m=''3000780''>sub
  and</span> <span m=''3001160''>[UNINTELLIGIBLE]</span> <span m=''3001720''>be</span>
  <span m=''3001830''>generic</span> <span m=''3002220''>operators.</span> <span m=''3003990''>So</span>
  <span m=''3004150''>we''re</span> <span m=''3004300''>going</span> <span m=''3004400''>to</span>
  <span m=''3004910''>define</span> <span m=''3006540''>add</span> <span m=''3012110''>and</span>
  <span m=''3012170''>say,</span> <span m=''3013920''>to</span> <span m=''3014430''>add</span>
  <span m=''3016470''>x</span> <span m=''3016760''>and</span> <span m=''3016880''>y,</span>
  <span m=''3017960''>that</span> <span m=''3018930''>will</span> <span m=''3019060''>be</span>
  <span m=''3021510''>operate--</span> <span m=''3026080''>we were</span> <span m=''3026230''>going</span>
  <span m=''3026360''>to</span> <span m=''3026420''>call it</span> <span m=''3026780''>operate-2.</span>
  <span m=''3027490''>This</span> <span m=''3027630''>is</span> <span m=''3028450''>our</span>
  <span m=''3028620''>operator</span> <span m=''3029130''>procedure,</span> <span
  m=''3029540''>but</span> <span m=''3029720''>set</span> <span m=''3029870''>up</span>
  <span m=''3030000''>for</span> <span m=''3030120''>two</span> <span m=''3030350''>arguments</span>
  <span m=''3031690''>using</span> <span m=''3032070''>add</span> <span m=''3034020''>on</span>
  <span m=''3034240''>x</span> <span m=''3035290''>and</span> <span m=''3035530''>y.</span>
  <span m=''3037261''>And</span> <span m=''3037720''>so</span> <span m=''3037900''>this</span>
  <span m=''3038070''>is</span> <span m=''3038200''>the</span> <span m=''3038720''>analog</span>
  <span m=''3039150''>to</span> <span m=''3039260''>operate.</span> </p><p><span m=''3040420''>Let''s</span>
  <span m=''3040620''>look</span> <span m=''3040720''>at</span> <span m=''3040830''>the</span>
  <span m=''3040910''>code</span> <span m=''3041200''>for</span> <span m=''3041350''>second.</span>
  <span m=''3041680''>It''s</span> <span m=''3041800''>almost</span> <span m=''3042180''>like</span>
  <span m=''3042340''>operate.</span> <span m=''3046040''>To</span> <span m=''3046190''>operate</span>
  <span m=''3048320''>with</span> <span m=''3048470''>some</span> <span m=''3048680''>operator</span>
  <span m=''3049920''>on</span> <span m=''3050120''>an</span> <span m=''3050220''>argument</span>
  <span m=''3050650''>1</span> <span m=''3051050''>and</span> <span m=''3051350''>an</span>
  <span m=''3051550''>argument</span> <span m=''3051980''>2,</span> <span m=''3055080''>well</span>
  <span m=''3055310''>the</span> <span m=''3055480''>first</span> <span m=''3055650''>thing</span>
  <span m=''3055770''>we''re</span> <span m=''3055880''>going</span> <span m=''3055950''>to</span>
  <span m=''3056030''>do</span> <span m=''3056190''>is</span> <span m=''3056370''>check</span>
  <span m=''3056870''>and</span> <span m=''3057040''>see</span> <span m=''3057180''>if</span>
  <span m=''3058730''>the</span> <span m=''3058800''>two</span> <span m=''3059430''>arguments</span>
  <span m=''3059890''>have</span> <span m=''3060020''>the</span> <span m=''3060080''>same</span>
  <span m=''3060350''>type.</span> <span m=''3061900''>So</span> <span m=''3062120''>we''ll</span>
  <span m=''3062790''>say,</span> <span m=''3062990''>is</span> <span m=''3063110''>the</span>
  <span m=''3063210''>type</span> <span m=''3064590''>of</span> <span m=''3064720''>the</span>
  <span m=''3064920''>first</span> <span m=''3065120''>argument</span> <span m=''3065670''>the</span>
  <span m=''3066220''>same</span> <span m=''3066510''>as</span> <span m=''3066610''>the</span>
  <span m=''3066700''>type</span> <span m=''3066940''>of</span> <span m=''3067010''>the</span>
  <span m=''3067200''>second</span> <span m=''3067380''>argument?</span> <span m=''3070350''>And</span>
  <span m=''3070510''>if</span> <span m=''3070620''>they''re</span> <span m=''3070790''>not,</span>
  <span m=''3073600''>we''ll</span> <span m=''3073720''>go</span> <span m=''3073890''>off
  and</span> <span m=''3074140''>complain,</span> <span m=''3074860''>and</span> <span
  m=''3074930''>say,</span> <span m=''3075070''>that''s</span> <span m=''3075280''>an</span>
  <span m=''3075370''>error.</span> <span m=''3075670''>We</span> <span m=''3075790''>don''t</span>
  <span m=''3075930''>know</span> <span m=''3076050''>how</span> <span m=''3076140''>to</span>
  <span m=''3076220''>do</span> <span m=''3076410''>that.</span> </p><p><span m=''3079140''>If</span>
  <span m=''3079300''>they</span> <span m=''3079430''>do</span> <span m=''3079690''>have</span>
  <span m=''3079880''>the</span> <span m=''3079960''>same</span> <span m=''3080230''>type,</span>
  <span m=''3080530''>we''ll</span> <span m=''3080630''>do</span> <span m=''3080920''>exactly</span>
  <span m=''3081420''>what</span> <span m=''3081520''>we</span> <span m=''3081620''>did</span>
  <span m=''3081740''>before.</span> <span m=''3082080''>We''ll</span> <span m=''3082530''>go</span>
  <span m=''3082680''>look</span> <span m=''3083790''>and</span> <span m=''3084020''>filed</span>
  <span m=''3084390''>under</span> <span m=''3084560''>the</span> <span m=''3084690''>type</span>
  <span m=''3085540''>of</span> <span m=''3085680''>the</span> <span m=''3085810''>argument--</span>
  <span m=''3086460''>arg 1</span> <span m=''3087220''>and</span> <span m=''3087290''>arg
  2</span> <span m=''3087640''>have</span> <span m=''3087770''>the</span> <span m=''3087830''>same</span>
  <span m=''3088090''>type,</span> <span m=''3088630''>so</span> <span m=''3088820''>it</span>
  <span m=''3088900''>doesn''t</span> <span m=''3089160''>matter.</span> <span m=''3090420''>So</span>
  <span m=''3090630''>we''ll</span> <span m=''3090680''>look</span> <span m=''3090970''>in</span>
  <span m=''3091070''>the</span> <span m=''3091150''>table,</span> <span m=''3091650''>find</span>
  <span m=''3091990''>the</span> <span m=''3092030''>procedure.</span> <span m=''3093640''>If</span>
  <span m=''3094620''>there</span> <span m=''3094830''>is</span> <span m=''3094950''>a</span>
  <span m=''3095010''>procedure</span> <span m=''3095480''>there,</span> <span m=''3097570''>then</span>
  <span m=''3097720''>we''ll</span> <span m=''3097860''>apply</span> <span m=''3098270''>it</span>
  <span m=''3098610''>to</span> <span m=''3098770''>the</span> <span m=''3098870''>contents</span>
  <span m=''3099470''>of</span> <span m=''3099590''>the</span> <span m=''3099930''>argument</span>
  <span m=''3100180''>1</span> <span m=''3100510''>and</span> <span m=''3100590''>the</span>
  <span m=''3100670''>contents</span> <span m=''3101120''>of arg</span> <span m=''3101470''>2.</span>
  <span m=''3103030''>And</span> <span m=''3103190''>otherwise</span> <span m=''3103570''>we''ll</span>
  <span m=''3103660''>say,</span> <span m=''3104380''>error.</span> <span m=''3104760''>Undefined</span>
  <span m=''3105330''>operator.</span> <span m=''3106890''>And</span> <span m=''3107010''>so</span>
  <span m=''3107140''>there''s</span> <span m=''3107360''>operate-2.</span> <span
  m=''3111326''>And</span> <span m=''3111790''>that''s</span> <span m=''3112040''>all</span>
  <span m=''3112170''>we</span> <span m=''3112310''>have</span> <span m=''3112450''>to</span>
  <span m=''3112550''>do.</span> </p><p><span m=''3115160''>We</span> <span m=''3115280''>just</span>
  <span m=''3115500''>built</span> <span m=''3115760''>the</span> <span m=''3115850''>complex</span>
  <span m=''3116310''>number</span> <span m=''3116520''>package</span> <span m=''3116930''>before.</span>
  <span m=''3117640''>How</span> <span m=''3117820''>do</span> <span m=''3117860''>we</span>
  <span m=''3118220''>embed</span> <span m=''3118730''>that</span> <span m=''3118920''>complex</span>
  <span m=''3119360''>number</span> <span m=''3119600''>package</span> <span m=''3120030''>in</span>
  <span m=''3120140''>this</span> <span m=''3120260''>generic</span> <span m=''3120630''>system?</span>
  <span m=''3122140''>Almost</span> <span m=''3122470''>the</span> <span m=''3122530''>same.</span>
  <span m=''3126410''>We</span> <span m=''3126650''>make</span> <span m=''3126870''>a</span>
  <span m=''3126930''>procedure</span> <span m=''3127430''>called</span> <span m=''3127690''>make-complex</span>
  <span m=''3129550''>that</span> <span m=''3130230''>takes</span> <span m=''3131060''>whatever</span>
  <span m=''3131400''>George</span> <span m=''3131730''>and</span> <span m=''3131830''>Martha</span>
  <span m=''3132150''>hand</span> <span m=''3132440''>to</span> <span m=''3132600''>us</span>
  <span m=''3133680''>and</span> <span m=''3133940''>add the</span> <span m=''3134100''>type-complex.</span>
  <span m=''3138170''>And</span> <span m=''3138360''>then</span> <span m=''3138500''>we</span>
  <span m=''3138620''>say,</span> <span m=''3139530''>to</span> <span m=''3139990''>add</span>
  <span m=''3140290''>complex</span> <span m=''3140800''>numbers,</span> <span m=''3142930''>plus</span>
  <span m=''3143240''>complex,</span> <span m=''3145840''>we</span> <span m=''3146510''>use</span>
  <span m=''3146870''>our</span> <span m=''3147160''>internal</span> <span m=''3147640''>procedure,</span>
  <span m=''3148110''>plus c,</span> <span m=''3150880''>and</span> <span m=''3151480''>attach</span>
  <span m=''3151870''>a</span> <span m=''3151920''>type,</span> <span m=''3152240''>make</span>
  <span m=''3152440''>that</span> <span m=''3152580''>a</span> <span m=''3152620''>complex</span>
  <span m=''3153120''>number.</span> </p><p><span m=''3157560''>So</span> <span m=''3159140''>our</span>
  <span m=''3159310''>original</span> <span m=''3159690''>package</span> <span m=''3160160''>had</span>
  <span m=''3160980''>names</span> <span m=''3161330''>plus</span> <span m=''3161690''>c</span>
  <span m=''3161850''>and</span> <span m=''3161990''>minus</span> <span m=''3162220''>c</span>
  <span m=''3162600''>that</span> <span m=''3162840''>we''re</span> <span m=''3162940''>using</span>
  <span m=''3163230''>to</span> <span m=''3163330''>communicate</span> <span m=''3163840''>with</span>
  <span m=''3163960''>George</span> <span m=''3164210''>and</span> <span m=''3164300''>Martha.</span>
  <span m=''3165250''>And</span> <span m=''3165410''>then</span> <span m=''3165920''>to</span>
  <span m=''3166040''>communicate</span> <span m=''3166510''>with</span> <span m=''3166640''>the</span>
  <span m=''3166760''>outside</span> <span m=''3167160''>world,</span> <span m=''3167420''>we</span>
  <span m=''3167520''>have</span> <span m=''3167680''>a</span> <span m=''3167730''>thing</span>
  <span m=''3167930''>called</span> <span m=''3168890''>plus-complex</span> <span
  m=''3171520''>and</span> <span m=''3172110''>minus-complex.</span> <span m=''3175920''>And</span>
  <span m=''3176090''>so</span> <span m=''3176360''>on.</span> <span m=''3176530''>And</span>
  <span m=''3176620''>the</span> <span m=''3176720''>only</span> <span m=''3176920''>difference</span>
  <span m=''3177360''>is</span> <span m=''3177480''>that</span> <span m=''3178350''>these</span>
  <span m=''3178640''>return</span> <span m=''3179000''>values</span> <span m=''3179410''>that</span>
  <span m=''3179540''>are</span> <span m=''3179630''>tight.</span> <span m=''3181120''>So</span>
  <span m=''3181230''>they</span> <span m=''3181380''>can</span> <span m=''3181520''>be</span>
  <span m=''3181620''>looked</span> <span m=''3181880''>at</span> <span m=''3182010''>up</span>
  <span m=''3182160''>here.</span> <span m=''3182850''>And</span> <span m=''3183000''>these</span>
  <span m=''3183180''>are</span> <span m=''3183850''>internal</span> <span m=''3184350''>operations.</span>
  </p><p><span m=''3189250''>Let''s</span> <span m=''3189390''>go</span> <span m=''3189680''>look</span>
  <span m=''3189800''>at</span> <span m=''3189910''>that</span> <span m=''3190080''>slide</span>
  <span m=''3190370''>again.</span> <span m=''3190680''>There''s</span> <span m=''3190980''>one</span>
  <span m=''3191160''>more</span> <span m=''3192380''>thing</span> <span m=''3192590''>we</span>
  <span m=''3192700''>do.</span> <span m=''3193740''>After</span> <span m=''3193980''>defining</span>
  <span m=''3194900''>plus-complex,</span> <span m=''3195710''>we</span> <span m=''3195850''>put</span>
  <span m=''3197350''>under</span> <span m=''3197530''>the</span> <span m=''3197700''>type</span>
  <span m=''3198010''>complex</span> <span m=''3199280''>and</span> <span m=''3199510''>the</span>
  <span m=''3199750''>symbol</span> <span m=''3200160''>add,</span> <span m=''3200580''>that</span>
  <span m=''3201530''>procedure</span> <span m=''3201950''>plus</span> <span m=''3202220''>complex.</span>
  <span m=''3203200''>And</span> <span m=''3203390''>then</span> <span m=''3203630''>similarly</span>
  <span m=''3204980''>for</span> <span m=''3205330''>subtracting</span> <span m=''3205940''>complex</span>
  <span m=''3206370''>numbers,</span> <span m=''3207130''>and</span> <span m=''3207370''>multiplying</span>
  <span m=''3207980''>them,</span> <span m=''3208360''>and</span> <span m=''3208580''>dividing</span>
  <span m=''3208855''>them.</span> </p><p><span m=''3211700''>OK, how</span> <span
  m=''3211880''>do</span> <span m=''3212010''>we</span> <span m=''3212130''>install</span>
  <span m=''3212490''>ordinary</span> <span m=''3213050''>numbers?</span> <span m=''3215250''>Exactly</span>
  <span m=''3215620''>the</span> <span m=''3215700''>same</span> <span m=''3215970''>way.</span>
  <span m=''3218160''>Come</span> <span m=''3218370''>off</span> <span m=''3218540''>and</span>
  <span m=''3219170''>say,</span> <span m=''3219390''>well</span> <span m=''3219920''>we''ll</span>
  <span m=''3220020''>make</span> <span m=''3220190''>a</span> <span m=''3220230''>thing</span>
  <span m=''3220380''>called</span> <span m=''3220500''>make-number.</span> <span
  m=''3224340''>Make-number</span> <span m=''3225320''>takes</span> <span m=''3225670''>a</span>
  <span m=''3225720''>number</span> <span m=''3226280''>and</span> <span m=''3226440''>attaches</span>
  <span m=''3227660''>a</span> <span m=''3227800''>type,</span> <span m=''3228160''>which</span>
  <span m=''3228320''>is</span> <span m=''3228420''>the</span> <span m=''3228500''>symbol</span>
  <span m=''3228860''>number.</span> <span m=''3230260''>We</span> <span m=''3230390''>build</span>
  <span m=''3230620''>a</span> <span m=''3230660''>procedure</span> <span m=''3231130''>called</span>
  <span m=''3231370''>plus-number,</span> <span m=''3232980''>which</span> <span m=''3233260''>is</span>
  <span m=''3234080''>simply,</span> <span m=''3235300''>add</span> <span m=''3235500''>the</span>
  <span m=''3235590''>two</span> <span m=''3235760''>things</span> <span m=''3236170''>using</span>
  <span m=''3237360''>the</span> <span m=''3237640''>ordinary</span> <span m=''3238190''>addition,</span>
  <span m=''3238970''>because</span> <span m=''3239120''>in</span> <span m=''3239220''>this</span>
  <span m=''3239310''>case</span> <span m=''3239490''>we''re</span> <span m=''3239580''>talking</span>
  <span m=''3239830''>about</span> <span m=''3239970''>ordinary</span> <span m=''3240410''>numbers,</span>
  <span m=''3241300''>and</span> <span m=''3241470''>attach</span> <span m=''3241800''>a</span>
  <span m=''3241850''>type</span> <span m=''3242090''>to</span> <span m=''3242320''>it
  and make</span> <span m=''3242520''>that</span> <span m=''3242660''>a</span> <span
  m=''3242720''>number.</span> <span m=''3244510''>And</span> <span m=''3244710''>then</span>
  <span m=''3245770''>we</span> <span m=''3245930''>put</span> <span m=''3246250''>into</span>
  <span m=''3246490''>the</span> <span m=''3246590''>table</span> <span m=''3247030''>under</span>
  <span m=''3247160''>the</span> <span m=''3247290''>symbol</span> <span m=''3247630''>number</span>
  <span m=''3248550''>and</span> <span m=''3248700''>the</span> <span m=''3248860''>operation</span>
  <span m=''3249340''>add,</span> <span m=''3249770''>this</span> <span m=''3249980''>procedure</span>
  <span m=''3250370''>plus-number,</span> <span m=''3252390''>and</span> <span m=''3252550''>then</span>
  <span m=''3252720''>the</span> <span m=''3252810''>same</span> <span m=''3253100''>thing</span>
  <span m=''3253320''>for</span> <span m=''3253470''>subtracting,</span> <span m=''3254400''>and</span>
  <span m=''3254580''>multiplying,</span> <span m=''3255360''>and</span> <span m=''3255550''>dividing.</span>
  </p><p><span m=''3262750''>Let''s</span> <span m=''3262930''>look</span> <span m=''3263030''>at</span>
  <span m=''3263130''>an</span> <span m=''3263210''>example,</span> <span m=''3264060''>just</span>
  <span m=''3264880''>to</span> <span m=''3265440''>make</span> <span m=''3265620''>it</span>
  <span m=''3265730''>clear.</span> <span m=''3266060''>Suppose,</span> <span m=''3268140''>for</span>
  <span m=''3268310''>instance,</span> <span m=''3272360''>I''m</span> <span m=''3272510''>going</span>
  <span m=''3272600''>to</span> <span m=''3272690''>perform</span> <span m=''3273310''>the</span>
  <span m=''3273430''>operation.</span> <span m=''3274150''>So</span> <span m=''3274350''>I</span>
  <span m=''3274430''>sit</span> <span m=''3274690''>up</span> <span m=''3274860''>here</span>
  <span m=''3276160''>and</span> <span m=''3276350''>I''m</span> <span m=''3277050''>going
  to</span> <span m=''3277250''>perform</span> <span m=''3277610''>the</span> <span
  m=''3277730''>operation,</span> <span m=''3278220''>which</span> <span m=''3278390''>looks</span>
  <span m=''3278640''>like</span> <span m=''3278840''>multiplying</span> <span m=''3279450''>two</span>
  <span m=''3279610''>complex</span> <span m=''3280100''>numbers.</span> <span m=''3280930''>So
  I would</span> <span m=''3281140''>multiply,</span> <span m=''3282380''>say,</span>
  <span m=''3282990''>3</span> <span m=''3283290''>plus</span> <span m=''3283640''>4i</span>
  <span m=''3285680''>and</span> <span m=''3287420''>2</span> <span m=''3287790''>plus</span>
  <span m=''3288080''>6i.</span> <span m=''3289786''>And</span> <span m=''3290190''>that''s</span>
  <span m=''3290450''>something</span> <span m=''3290730''>that</span> <span m=''3290830''>I</span>
  <span m=''3290890''>might</span> <span m=''3291110''>want</span> <span m=''3291220''>to</span>
  <span m=''3291350''>take</span> <span m=''3291740''>hand</span> <span m=''3291950''>that</span>
  <span m=''3292090''>to</span> <span m=''3292160''>mul.</span> <span m=''3292840''>I''ll
  write</span> <span m=''3293870''>mul</span> <span m=''3294340''>as</span> <span
  m=''3294460''>my</span> <span m=''3294590''>generic</span> <span m=''3295020''>operator</span>
  <span m=''3295480''>here.</span> </p><p><span m=''3297170''>How''s</span> <span
  m=''3297370''>that</span> <span m=''3297510''>going</span> <span m=''3297600''>to</span>
  <span m=''3297690''>work?</span> <span m=''3298280''>Well</span> <span m=''3299140''>3</span>
  <span m=''3299500''>plus</span> <span m=''3299890''>4i,</span> <span m=''3300990''>say,</span>
  <span m=''3302250''>sits</span> <span m=''3302580''>in</span> <span m=''3302670''>the</span>
  <span m=''3302760''>system</span> <span m=''3303740''>at</span> <span m=''3303970''>this</span>
  <span m=''3304200''>level</span> <span m=''3304840''>as</span> <span m=''3305020''>something</span>
  <span m=''3305290''>that</span> <span m=''3305430''>looks</span> <span m=''3305630''>like</span>
  <span m=''3305860''>this.</span> <span m=''3306250''>Let''s</span> <span m=''3306450''>say</span>
  <span m=''3306550''>it</span> <span m=''3306640''>was</span> <span m=''3306770''>one</span>
  <span m=''3306930''>of</span> <span m=''3307020''>George''s.</span> <span m=''3308280''>So</span>
  <span m=''3309260''>it</span> <span m=''3309370''>would</span> <span m=''3309470''>have</span>
  <span m=''3309660''>a</span> <span m=''3311840''>3</span> <span m=''3314030''>and</span>
  <span m=''3314430''>a 4.</span> <span m=''3318490''>And</span> <span m=''3318960''>attached</span>
  <span m=''3319470''>to</span> <span m=''3319560''>that</span> <span m=''3319810''>would</span>
  <span m=''3319950''>be</span> <span m=''3320090''>George''s</span> <span m=''3320570''>type,</span>
  <span m=''3324440''>which</span> <span m=''3325010''>would</span> <span m=''3325150''>say</span>
  <span m=''3325330''>rectangular,</span> <span m=''3327040''>it</span> <span m=''3327460''>came</span>
  <span m=''3327690''>from</span> <span m=''3327870''>George.</span> <span m=''3329510''>And</span>
  <span m=''3329640''>attached</span> <span m=''3330080''>to</span> <span m=''3330190''>that--</span>
  <span m=''3331230''>and</span> <span m=''3331740''>this</span> <span m=''3332080''>itself</span>
  <span m=''3333330''>would</span> <span m=''3333470''>be</span> <span m=''3333610''>the</span>
  <span m=''3333710''>data</span> <span m=''3334660''>view</span> <span m=''3334830''>from</span>
  <span m=''3335000''>the</span> <span m=''3335070''>next</span> <span m=''3335340''>level</span>
  <span m=''3335630''>up,</span> <span m=''3336340''>which</span> <span m=''3336610''>it</span>
  <span m=''3336700''>is--</span> <span m=''3337700''>so</span> <span m=''3338080''>that</span>
  <span m=''3338260''>itself</span> <span m=''3338690''>would</span> <span m=''3338790''>be</span>
  <span m=''3338890''>a</span> <span m=''3338950''>type-data</span> <span m=''3339420''>object</span>
  <span m=''3340690''>which</span> <span m=''3340900''>would</span> <span m=''3341030''>say</span>
  <span m=''3341240''>complex.</span> <span m=''3344820''>So</span> <span m=''3344990''>that''s</span>
  <span m=''3345270''>what</span> <span m=''3345730''>this</span> <span m=''3346210''>object</span>
  <span m=''3346740''>would</span> <span m=''3346860''>look</span> <span m=''3347070''>like</span>
  <span m=''3348670''>up</span> <span m=''3348870''>here</span> <span m=''3349060''>at</span>
  <span m=''3349140''>the</span> <span m=''3349240''>very</span> <span m=''3349470''>highest</span>
  <span m=''3349910''>level,</span> <span m=''3350720''>where</span> <span m=''3350860''>the</span>
  <span m=''3351310''>really</span> <span m=''3351610''>super-generic</span> <span
  m=''3352300''>operations</span> <span m=''3352890''>are</span> <span m=''3352940''>looking</span>
  <span m=''3353270''>at</span> <span m=''3353420''>it.</span> </p><p><span m=''3355560''>Now</span>
  <span m=''3355720''>what</span> <span m=''3355870''>happens,</span> <span m=''3357030''>mul</span>
  <span m=''3357400''>eventually''s</span> <span m=''3357860''>going</span> <span
  m=''3357930''>to</span> <span m=''3358010''>come</span> <span m=''3358220''>along</span>
  <span m=''3358810''>and</span> <span m=''3359070''>say,</span> <span m=''3359400''>oh,</span>
  <span m=''3359660''>what''s</span> <span m=''3359950''>it''s</span> <span m=''3360120''>type?</span>
  <span m=''3360400''>It''s</span> <span m=''3360470''>type</span> <span m=''3360790''>is</span>
  <span m=''3360930''>complex.</span> <span m=''3364270''>Go</span> <span m=''3364420''>through</span>
  <span m=''3364600''>to</span> <span m=''3364690''>operate-2</span> <span m=''3366140''>and</span>
  <span m=''3366290''>say,</span> <span m=''3366470''>oh,</span> <span m=''3367400''>what</span>
  <span m=''3367580''>I</span> <span m=''3367760''>want</span> <span m=''3367890''>to</span>
  <span m=''3368010''>do</span> <span m=''3368290''>is</span> <span m=''3368460''>apply</span>
  <span m=''3369080''>what''s</span> <span m=''3369300''>in</span> <span m=''3369380''>the</span>
  <span m=''3369480''>table,</span> <span m=''3369830''>which</span> <span m=''3369990''>is</span>
  <span m=''3370090''>going</span> <span m=''3370180''>to</span> <span m=''3370260''>be</span>
  <span m=''3370350''>the</span> <span m=''3370440''>procedure</span> <span m=''3372070''>star</span>
  <span m=''3372470''>complex,</span> <span m=''3375110''>on</span> <span m=''3375630''>this</span>
  <span m=''3376280''>thing</span> <span m=''3376600''>with</span> <span m=''3376780''>the</span>
  <span m=''3376890''>type</span> <span m=''3377150''>stripped</span> <span m=''3377550''>off.</span>
  <span m=''3377950''>So</span> <span m=''3378110''>it''s</span> <span m=''3378250''>going</span>
  <span m=''3378320''>to</span> <span m=''3378380''>strip</span> <span m=''3378670''>off</span>
  <span m=''3378820''>the</span> <span m=''3378920''>type,</span> <span m=''3379970''>take</span>
  <span m=''3380220''>that</span> <span m=''3380480''>much,</span> <span m=''3382010''>and</span>
  <span m=''3382180''>send</span> <span m=''3382400''>that</span> <span m=''3382580''>down</span>
  <span m=''3383100''>into</span> <span m=''3383320''>the</span> <span m=''3383420''>complex</span>
  <span m=''3384010''>world.</span> </p><p><span m=''3386288''>The</span> <span m=''3386760''>complex</span>
  <span m=''3387210''>world</span> <span m=''3387430''>looks</span> <span m=''3387660''>at</span>
  <span m=''3387720''>its</span> <span m=''3387890''>operations</span> <span m=''3388500''>and</span>
  <span m=''3388600''>says,</span> <span m=''3388760''>oh,</span> <span m=''3388880''>I</span>
  <span m=''3388950''>have</span> <span m=''3389100''>to</span> <span m=''3389210''>apply</span>
  <span m=''3389700''>star</span> <span m=''3390110''>c.</span> <span m=''3391280''>Star</span>
  <span m=''3391640''>c</span> <span m=''3391920''>might</span> <span m=''3392190''>say,</span>
  <span m=''3392410''>oh,</span> <span m=''3392640''>at</span> <span m=''3392740''>some</span>
  <span m=''3392890''>point</span> <span m=''3393090''>I</span> <span m=''3393150''>want</span>
  <span m=''3393250''>to</span> <span m=''3393350''>look</span> <span m=''3393570''>at</span>
  <span m=''3394210''>the</span> <span m=''3394490''>magnitude</span> <span m=''3395160''>of</span>
  <span m=''3395300''>this</span> <span m=''3395430''>object</span> <span m=''3395820''>that</span>
  <span m=''3395960''>it''s</span> <span m=''3396130''>in,</span> <span m=''3396450''>that</span>
  <span m=''3396760''>it''s</span> <span m=''3396930''>got.</span> <span m=''3399420''>And</span>
  <span m=''3399610''>they''ll</span> <span m=''3399690''>say,</span> <span m=''3399910''>oh,</span>
  <span m=''3400030''>it''s</span> <span m=''3400160''>rectangular,</span> <span m=''3400850''>it''s</span>
  <span m=''3400950''>one</span> <span m=''3401110''>of</span> <span m=''3401200''>George''s.</span>
  <span m=''3401870''>So</span> <span m=''3402080''>it''ll</span> <span m=''3402340''>then</span>
  <span m=''3402630''>strip</span> <span m=''3403070''>off</span> <span m=''3403310''>the</span>
  <span m=''3403430''>next</span> <span m=''3403740''>version</span> <span m=''3404070''>of</span>
  <span m=''3404170''>type,</span> <span m=''3406890''>and</span> <span m=''3407110''>hand</span>
  <span m=''3407340''>that</span> <span m=''3407950''>down</span> <span m=''3408190''>to</span>
  <span m=''3408300''>George</span> <span m=''3408690''>to</span> <span m=''3408790''>take</span>
  <span m=''3409010''>the</span> <span m=''3409080''>magnitude</span> <span m=''3409620''>of.</span>
  </p><p><span m=''3412160''>So</span> <span m=''3412300''>you</span> <span m=''3412400''>see</span>
  <span m=''3412540''>what''s</span> <span m=''3412750''>going</span> <span m=''3412980''>on</span>
  <span m=''3413470''>is</span> <span m=''3413650''>that</span> <span m=''3415140''>there
  are</span> <span m=''3415290''>these</span> <span m=''3415930''>chains</span> <span
  m=''3416460''>of</span> <span m=''3416600''>types.</span> <span m=''3419320''>And</span>
  <span m=''3419430''>the</span> <span m=''3419550''>length</span> <span m=''3419790''>of</span>
  <span m=''3419880''>the</span> <span m=''3420010''>chain</span> <span m=''3420290''>is</span>
  <span m=''3420370''>sort</span> <span m=''3420470''>of</span> <span m=''3420570''>the</span>
  <span m=''3420650''>number</span> <span m=''3420970''>of</span> <span m=''3421070''>levels</span>
  <span m=''3421530''>that</span> <span m=''3421710''>you''re</span> <span m=''3421730''>going</span>
  <span m=''3421800''>to</span> <span m=''3421880''>be</span> <span m=''3421950''>going</span>
  <span m=''3422230''>up</span> <span m=''3422370''>in</span> <span m=''3422480''>this</span>
  <span m=''3422640''>table.</span> <span m=''3425090''>And</span> <span m=''3425270''>what</span>
  <span m=''3425470''>a</span> <span m=''3425670''>type tells</span> <span m=''3425930''>you,</span>
  <span m=''3426030''>every</span> <span m=''3426280''>time</span> <span m=''3426790''>you</span>
  <span m=''3426900''>have</span> <span m=''3429010''>a</span> <span m=''3429130''>vertical</span>
  <span m=''3429590''>barrier</span> <span m=''3430100''>in</span> <span m=''3430200''>this</span>
  <span m=''3430370''>table,</span> <span m=''3431150''>where</span> <span m=''3431270''>there''s</span>
  <span m=''3431480''>some</span> <span m=''3431680''>ambiguity</span> <span m=''3432230''>about</span>
  <span m=''3432350''>where</span> <span m=''3432580''>you</span> <span m=''3432660''>should</span>
  <span m=''3432850''>go</span> <span m=''3432990''>down</span> <span m=''3433310''>to</span>
  <span m=''3433390''>the</span> <span m=''3433560''>next</span> <span m=''3433730''>level,</span>
  <span m=''3434320''>the</span> <span m=''3434570''>type</span> <span m=''3434840''>is</span>
  <span m=''3435010''>telling</span> <span m=''3435280''>you</span> <span m=''3435400''>where</span>
  <span m=''3435540''>to</span> <span m=''3435590''>go.</span> <span m=''3437440''>And</span>
  <span m=''3437590''>then</span> <span m=''3437730''>everybody</span> <span m=''3438200''>at</span>
  <span m=''3438270''>the</span> <span m=''3438350''>bottom,</span> <span m=''3438980''>as</span>
  <span m=''3439160''>they</span> <span m=''3439270''>construct</span> <span m=''3439690''>data</span>
  <span m=''3439950''>and</span> <span m=''3440090''>filter</span> <span m=''3440440''>it</span>
  <span m=''3440490''>up,</span> <span m=''3441520''>they</span> <span m=''3441670''>stick</span>
  <span m=''3441950''>their</span> <span m=''3442090''>type</span> <span m=''3442380''>back</span>
  <span m=''3442620''>on.</span> <span m=''3445350''>So</span> <span m=''3445580''>that''s</span>
  <span m=''3448130''>the</span> <span m=''3448210''>general</span> <span m=''3448660''>structure</span>
  <span m=''3449980''>of</span> <span m=''3450180''>the</span> <span m=''3450270''>system.</span>
  </p><p><span m=''3453410''>OK.</span> <span m=''3454820''>Now that</span> <span
  m=''3454960''>we''ve</span> <span m=''3455170''>got</span> <span m=''3455400''>this,</span>
  <span m=''3457670''>let''s</span> <span m=''3457850''>go</span> <span m=''3457940''>and</span>
  <span m=''3458040''>make</span> <span m=''3458190''>this</span> <span m=''3458330''>thing</span>
  <span m=''3458440''>even</span> <span m=''3458660''>more</span> <span m=''3458880''>complex.</span>
  <span m=''3461890''>Let''s</span> <span m=''3462120''>talk</span> <span m=''3462370''>about</span>
  <span m=''3462750''>adding</span> <span m=''3463130''>to</span> <span m=''3463250''>the</span>
  <span m=''3463360''>system</span> <span m=''3465330''>not</span> <span m=''3465520''>only</span>
  <span m=''3465700''>these</span> <span m=''3465840''>kinds</span> <span m=''3466090''>of</span>
  <span m=''3466150''>numbers,</span> <span m=''3466600''>but</span> <span m=''3468200''>it''s</span>
  <span m=''3468350''>also</span> <span m=''3468570''>meaningful</span> <span m=''3469050''>to</span>
  <span m=''3469110''>start</span> <span m=''3469360''>talking</span> <span m=''3469680''>about</span>
  <span m=''3469870''>adding</span> <span m=''3470230''>polynomials.</span> <span
  m=''3471510''>Might</span> <span m=''3471650''>do</span> <span m=''3471750''>arithmetic</span>
  <span m=''3472220''>on</span> <span m=''3472350''>polynomials.</span> <span m=''3473360''>Like
  we</span> <span m=''3473690''>could</span> <span m=''3473910''>have</span> <span
  m=''3474260''>x to the</span> <span m=''3474670''>fifteenth</span> <span m=''3476060''>plus</span>
  <span m=''3476970''>2x</span> <span m=''3477430''>to</span> <span m=''3477500''>the</span>
  <span m=''3477570''>seventh</span> <span m=''3482250''>plus</span> <span m=''3482900''>5.</span>
  <span m=''3484480''>That</span> <span m=''3484670''>might</span> <span m=''3484860''>be</span>
  <span m=''3484970''>some</span> <span m=''3485160''>polynomial.</span> <span m=''3486380''>And</span>
  <span m=''3486650''>if</span> <span m=''3486740''>we</span> <span m=''3486830''>have</span>
  <span m=''3486990''>two</span> <span m=''3487190''>such</span> <span m=''3487520''>gadgets</span>
  <span m=''3487940''>we</span> <span m=''3488050''>can</span> <span m=''3488180''>add</span>
  <span m=''3488450''>them</span> <span m=''3488630''>or</span> <span m=''3488720''>multiply</span>
  <span m=''3489290''>them.</span> <span m=''3490530''>Let''s</span> <span m=''3490660''>not</span>
  <span m=''3490760''>worry</span> <span m=''3490900''>about</span> <span m=''3491110''>dividing</span>
  <span m=''3491560''>them.</span> <span m=''3492140''>Just</span> <span m=''3492390''>add</span>
  <span m=''3492470''>them, multiply</span> <span m=''3492790''>them,</span> <span
  m=''3493670''>then we''ll</span> <span m=''3493950''>subtract</span> <span m=''3494380''>them.</span>
  </p><p><span m=''3495870''>What do</span> <span m=''3496020''>we</span> <span m=''3496120''>have</span>
  <span m=''3496280''>to</span> <span m=''3496390''>do?</span> <span m=''3496660''>Well</span>
  <span m=''3498610''>let''s</span> <span m=''3498800''>think</span> <span m=''3498960''>about</span>
  <span m=''3499190''>how</span> <span m=''3499310''>we</span> <span m=''3499410''>might</span>
  <span m=''3499590''>represent</span> <span m=''3500100''>a</span> <span m=''3500480''>polynomial.</span>
  <span m=''3501830''>It''s</span> <span m=''3501920''>going</span> <span m=''3501970''>to</span>
  <span m=''3502030''>be</span> <span m=''3502120''>some</span> <span m=''3502300''>typed</span>
  <span m=''3502740''>data</span> <span m=''3502960''>object.</span> <span m=''3504950''>So
  let''s say</span> <span m=''3505680''>a</span> <span m=''3506100''>polynomial</span>
  <span m=''3506580''>to</span> <span m=''3506850''>this</span> <span m=''3506950''>system</span>
  <span m=''3508640''>might</span> <span m=''3508880''>look</span> <span m=''3509060''>like</span>
  <span m=''3509430''>a</span> <span m=''3509690''>thing</span> <span m=''3509870''>that</span>
  <span m=''3510020''>starts</span> <span m=''3510320''>with</span> <span m=''3510430''>the</span>
  <span m=''3510530''>type</span> <span m=''3510970''>polynomial.</span> <span m=''3512000''>And</span>
  <span m=''3512140''>then</span> <span m=''3512260''>maybe</span> <span m=''3512540''>it</span>
  <span m=''3512660''>says</span> <span m=''3512880''>the</span> <span m=''3512960''>next</span>
  <span m=''3513230''>thing</span> <span m=''3513410''>is</span> <span m=''3513520''>what</span>
  <span m=''3513710''>variable</span> <span m=''3514220''>its</span> <span m=''3514370''>in.</span>
  <span m=''3514550''>So</span> <span m=''3514730''>I might</span> <span m=''3514940''>say
  I''m a</span> <span m=''3516110''>polynomial</span> <span m=''3516700''>in</span>
  <span m=''3516860''>the</span> <span m=''3516950''>variable</span> <span m=''3517430''>x.</span>
  <span m=''3518960''>And</span> <span m=''3519140''>then</span> <span m=''3519240''>it''ll</span>
  <span m=''3519340''>have</span> <span m=''3519510''>some</span> <span m=''3519680''>information</span>
  <span m=''3520280''>about</span> <span m=''3520500''>what</span> <span m=''3520640''>the</span>
  <span m=''3520730''>terms</span> <span m=''3521140''>are.</span> </p><p><span m=''3522250''>And</span>
  <span m=''3522860''>there''re</span> <span m=''3523040''>just</span> <span m=''3523210''>tons</span>
  <span m=''3523450''>of</span> <span m=''3523500''>ways</span> <span m=''3523700''>to</span>
  <span m=''3523820''>do</span> <span m=''3524000''>this,</span> <span m=''3524250''>but</span>
  <span m=''3524380''>one</span> <span m=''3524550''>way</span> <span m=''3524730''>is</span>
  <span m=''3524900''>to</span> <span m=''3525620''>say</span> <span m=''3525960''>we''re</span>
  <span m=''3526100''>going</span> <span m=''3526180''>to</span> <span m=''3526250''>have</span>
  <span m=''3526410''>a</span> <span m=''3526470''>thing</span> <span m=''3526640''>called</span>
  <span m=''3526850''>a</span> <span m=''3526900''>term-list.</span> <span m=''3531047''>And</span>
  <span m=''3531520''>a</span> <span m=''3531670''>term-list--</span> <span m=''3533700''>well,
  in</span> <span m=''3533930''>our</span> <span m=''3534060''>case</span> <span m=''3534350''>we''ll</span>
  <span m=''3534480''>use</span> <span m=''3534580''>something</span> <span m=''3534830''>that</span>
  <span m=''3534940''>looks</span> <span m=''3535130''>like</span> <span m=''3535360''>this.</span>
  <span m=''3536360''>We''ll</span> <span m=''3536440''>make</span> <span m=''3536630''>it</span>
  <span m=''3536690''>a</span> <span m=''3536730''>bunch</span> <span m=''3536980''>of</span>
  <span m=''3537140''>pairs</span> <span m=''3538030''>which</span> <span m=''3538190''>have</span>
  <span m=''3538340''>an</span> <span m=''3538410''>order</span> <span m=''3538870''>in</span>
  <span m=''3538960''>a</span> <span m=''3539010''>coefficient.</span> <span m=''3539690''>So</span>
  <span m=''3539960''>this</span> <span m=''3540130''>polynomial</span> <span m=''3541520''>would</span>
  <span m=''3541640''>be</span> <span m=''3541750''>represented</span> <span m=''3544840''>by</span>
  <span m=''3545000''>this</span> <span m=''3545260''>term-list.</span> <span m=''3549070''>And</span>
  <span m=''3549570''>what</span> <span m=''3549710''>that</span> <span m=''3549920''>means</span>
  <span m=''3550240''>is</span> <span m=''3550840''>that</span> <span m=''3551540''>this</span>
  <span m=''3551730''>polynomial</span> <span m=''3552310''>starts</span> <span m=''3552720''>off</span>
  <span m=''3552910''>with</span> <span m=''3553000''>a</span> <span m=''3553090''>term</span>
  <span m=''3554000''>of</span> <span m=''3554150''>order</span> <span m=''3554530''>15</span>
  <span m=''3557850''>and</span> <span m=''3558570''>coefficient</span> <span m=''3559290''>1.</span>
  <span m=''3563820''>And</span> <span m=''3564270''>the</span> <span m=''3564470''>next</span>
  <span m=''3564660''>thing</span> <span m=''3564820''>in it</span> <span m=''3564910''>is</span>
  <span m=''3565120''>a</span> <span m=''3565180''>term</span> <span m=''3565560''>of</span>
  <span m=''3565660''>order</span> <span m=''3565920''>7</span> <span m=''3566630''>and</span>
  <span m=''3566780''>coefficient</span> <span m=''3567310''>2,</span> <span m=''3567490''>a
  term of</span> <span m=''3567870''>order</span> <span m=''3568070''>0,</span> <span
  m=''3568950''>which is</span> <span m=''3569170''>constant</span> <span m=''3569425''>in</span>
  <span m=''3569680''>coefficient</span> <span m=''3570230''>5.</span> </p><p><span
  m=''3571450''>And</span> <span m=''3572780''>there</span> <span m=''3572940''>are</span>
  <span m=''3572970''>lots</span> <span m=''3573340''>and</span> <span m=''3573440''>lots</span>
  <span m=''3573750''>of</span> <span m=''3573850''>ways,</span> <span m=''3574240''>and</span>
  <span m=''3574410''>lots</span> <span m=''3574700''>and</span> <span m=''3574770''>lots</span>
  <span m=''3575020''>of</span> <span m=''3575600''>trade-offs</span> <span m=''3576060''>when</span>
  <span m=''3576170''>you</span> <span m=''3576310''>really</span> <span m=''3576620''>think</span>
  <span m=''3576830''>about</span> <span m=''3577080''>making</span> <span m=''3577440''>algebraic</span>
  <span m=''3577890''>manipulation</span> <span m=''3578550''>packages</span> <span
  m=''3579420''>about</span> <span m=''3579710''>exactly</span> <span m=''3580230''>how</span>
  <span m=''3580330''>you should</span> <span m=''3580570''>represent</span> <span
  m=''3581050''>these</span> <span m=''3581260''>things.</span> <span m=''3581730''>But</span>
  <span m=''3582210''>this</span> <span m=''3582390''>is</span> <span m=''3582500''>a</span>
  <span m=''3582590''>fairly</span> <span m=''3582950''>standard</span> <span m=''3583390''>one.</span>
  <span m=''3584180''>It''s</span> <span m=''3584350''>useful</span> <span m=''3584680''>in
  a</span> <span m=''3584800''>lot</span> <span m=''3584930''>of</span> <span m=''3585050''>contexts.</span>
  </p><p><span m=''3587770''>OK,</span> <span m=''3588030''>well</span> <span m=''3588560''>how</span>
  <span m=''3588710''>do</span> <span m=''3588800''>we</span> <span m=''3589390''>implement</span>
  <span m=''3589810''>our</span> <span m=''3589920''>polynomial</span> <span m=''3590510''>arithmetic?</span>
  <span m=''3594270''>Let''s</span> <span m=''3594450''>start</span> <span m=''3594700''>out.</span>
  <span m=''3597950''>What</span> <span m=''3598090''>we''ll</span> <span m=''3598210''>do</span>
  <span m=''3599470''>to</span> <span m=''3599760''>make</span> <span m=''3599950''>a
  polynomial--</span> <span m=''3600760''>we''ll</span> <span m=''3600880''>first</span>
  <span m=''3601380''>have</span> <span m=''3601650''>a</span> <span m=''3602990''>way</span>
  <span m=''3603110''>to</span> <span m=''3603230''>make</span> <span m=''3603470''>polynomials.</span>
  <span m=''3605690''>We''re</span> <span m=''3605840''>going</span> <span m=''3605910''>to</span>
  <span m=''3605980''>make</span> <span m=''3606230''>a polynomial</span> <span m=''3607540''>out</span>
  <span m=''3607720''>of</span> <span m=''3607870''>variable</span> <span m=''3608560''>like</span>
  <span m=''3608830''>x</span> <span m=''3609560''>and</span> <span m=''3609830''>term-list.</span>
  <span m=''3611300''>And</span> <span m=''3611430''>all</span> <span m=''3611540''>that</span>
  <span m=''3611710''>does</span> <span m=''3612000''>is</span> <span m=''3612660''>we''ll</span>
  <span m=''3612810''>package</span> <span m=''3613180''>them</span> <span m=''3613290''>together</span>
  <span m=''3613630''>someway.</span> <span m=''3614290''>We''ll</span> <span m=''3617050''>put</span>
  <span m=''3617220''>the</span> <span m=''3617300''>variable</span> <span m=''3617720''>together</span>
  <span m=''3618040''>with</span> <span m=''3618160''>the</span> <span m=''3618240''>term</span>
  <span m=''3618530''>list</span> <span m=''3618740''>using</span> <span m=''3618980''>cons,</span>
  <span m=''3619820''>and</span> <span m=''3619950''>then</span> <span m=''3620080''>attached</span>
  <span m=''3620500''>to</span> <span m=''3620580''>that</span> <span m=''3620770''>the</span>
  <span m=''3620860''>type</span> <span m=''3621170''>polynomial.</span> </p><p><span
  m=''3626270''>OK,</span> <span m=''3626600''>how</span> <span m=''3626810''>do we
  add</span> <span m=''3626970''>two</span> <span m=''3627110''>polynomials?</span>
  <span m=''3629280''>To</span> <span m=''3629390''>add</span> <span m=''3629610''>a</span>
  <span m=''3629980''>polynomial,</span> <span m=''3630260''>p1</span> <span m=''3631020''>and</span>
  <span m=''3631210''>p2,</span> <span m=''3632740''>and</span> <span m=''3632900''>then</span>
  <span m=''3633030''>just</span> <span m=''3633230''>for</span> <span m=''3633330''>simplicity</span>
  <span m=''3634530''>let''s</span> <span m=''3634790''>say</span> <span m=''3634940''>we</span>
  <span m=''3635400''>will</span> <span m=''3635560''>only</span> <span m=''3635920''>add</span>
  <span m=''3636060''>things</span> <span m=''3636290''>in</span> <span m=''3636370''>the</span>
  <span m=''3636440''>same</span> <span m=''3636730''>variable.</span> <span m=''3637380''>So</span>
  <span m=''3637950''>if</span> <span m=''3638110''>they</span> <span m=''3638230''>have</span>
  <span m=''3638350''>the</span> <span m=''3638420''>same</span> <span m=''3638690''>variable,</span>
  <span m=''3639770''>and</span> <span m=''3639930''>same</span> <span m=''3640190''>variable</span>
  <span m=''3640740''>here</span> <span m=''3640960''>is</span> <span m=''3641080''>going</span>
  <span m=''3641180''>to</span> <span m=''3641270''>be</span> <span m=''3641370''>some</span>
  <span m=''3641670''>selector</span> <span m=''3642120''>we</span> <span m=''3642240''>write,</span>
  <span m=''3642980''>whose</span> <span m=''3643160''>details</span> <span m=''3643530''>we</span>
  <span m=''3643630''>don''t</span> <span m=''3643810''>care</span> <span m=''3644030''>about.</span>
  <span m=''3645150''>If</span> <span m=''3645320''>the</span> <span m=''3645360''>two</span>
  <span m=''3645510''>polynomials</span> <span m=''3646080''>have</span> <span m=''3646180''>the</span>
  <span m=''3646230''>same</span> <span m=''3646490''>variable,</span> <span m=''3648030''>then</span>
  <span m=''3648160''>we''ll</span> <span m=''3648280''>do</span> <span m=''3648440''>something.</span>
  <span m=''3648810''>If</span> <span m=''3648890''>they</span> <span m=''3649000''>don''t</span>
  <span m=''3649220''>have</span> <span m=''3649370''>the</span> <span m=''3649430''>same</span>
  <span m=''3649690''>variable,</span> <span m=''3650580''>we''ll</span> <span m=''3650700''>give</span>
  <span m=''3650820''>an</span> <span m=''3650920''>error,</span> <span m=''3652350''>polynomials</span>
  <span m=''3652920''>not</span> <span m=''3653100''>in</span> <span m=''3653160''>the</span>
  <span m=''3653210''>same</span> <span m=''3653460''>variable.</span> </p><p><span
  m=''3655480''>And</span> <span m=''3656050''>if</span> <span m=''3656180''>they</span>
  <span m=''3656290''>do</span> <span m=''3656460''>have</span> <span m=''3656620''>the</span>
  <span m=''3656680''>same</span> <span m=''3656940''>variable,</span> <span m=''3657630''>what</span>
  <span m=''3657790''>we''ll</span> <span m=''3657890''>do</span> <span m=''3658030''>is</span>
  <span m=''3658120''>we''ll</span> <span m=''3658220''>make</span> <span m=''3658470''>a
  polynomial</span> <span m=''3659850''>whose</span> <span m=''3660060''>variable</span>
  <span m=''3660580''>is</span> <span m=''3660700''>whatever</span> <span m=''3660950''>that</span>
  <span m=''3661130''>variable</span> <span m=''3661600''>is,</span> <span m=''3663110''>and</span>
  <span m=''3663330''>whose</span> <span m=''3664270''>term-list</span> <span m=''3664920''>is</span>
  <span m=''3665150''>something</span> <span m=''3665450''>we''ll</span> <span m=''3665570''>call</span>
  <span m=''3665770''>sum-terms.</span> <span m=''3667570''>Plus</span> <span m=''3667830''>terms</span>
  <span m=''3668180''>will</span> <span m=''3668840''>add</span> <span m=''3669080''>the</span>
  <span m=''3669170''>two</span> <span m=''3669320''>term</span> <span m=''3669620''>lists.</span>
  <span m=''3670170''>So</span> <span m=''3670250''>we''ll add</span> <span m=''3670520''>the</span>
  <span m=''3670650''>two</span> <span m=''3670810''>term</span> <span m=''3671050''>lists</span>
  <span m=''3671330''>to the</span> <span m=''3671400''>polynomial.</span> <span m=''3673500''>That''ll</span>
  <span m=''3673760''>give us a</span> <span m=''3674000''>term-list.</span> <span
  m=''3675110''>We''ll</span> <span m=''3675310''>add</span> <span m=''3675450''>on,</span>
  <span m=''3676170''>we''ll</span> <span m=''3676260''>say</span> <span m=''3676430''>it''s</span>
  <span m=''3676580''>a polynomial</span> <span m=''3677300''>in</span> <span m=''3677890''>the</span>
  <span m=''3678150''>variable</span> <span m=''3679150''>with</span> <span m=''3679310''>that</span>
  <span m=''3679500''>term-list.</span> <span m=''3680750''>That''s</span> <span m=''3681010''>plus</span>
  <span m=''3681280''>poly.</span> <span m=''3682550''>And</span> <span m=''3682750''>then</span>
  <span m=''3682860''>we''re</span> <span m=''3682990''>going</span> <span m=''3683130''>to</span>
  <span m=''3684020''>put</span> <span m=''3684380''>in</span> <span m=''3684510''>our</span>
  <span m=''3684650''>table</span> <span m=''3685700''>under</span> <span m=''3685860''>the</span>
  <span m=''3686020''>type</span> <span m=''3686360''>polynomial,</span> <span m=''3688280''>add</span>
  <span m=''3688510''>them</span> <span m=''3688970''>using</span> <span m=''3689260''>plus</span>
  <span m=''3689540''>poly.</span> <span m=''3690520''>And</span> <span m=''3690610''>of</span>
  <span m=''3690720''>course</span> <span m=''3690840''>we</span> <span m=''3690940''>really</span>
  <span m=''3691120''>haven''t</span> <span m=''3691350''>done</span> <span m=''3691540''>much.</span>
  <span m=''3691750''>What</span> <span m=''3691870''>we''ve</span> <span m=''3692020''>really</span>
  <span m=''3692270''>done</span> <span m=''3692480''>is</span> <span m=''3693350''>pushed</span>
  <span m=''3693630''>all</span> <span m=''3693750''>the</span> <span m=''3693830''>work</span>
  <span m=''3694090''>onto</span> <span m=''3694310''>this thing,</span> <span m=''3694410''>plus-terms,</span>
  <span m=''3695830''>which</span> <span m=''3695990''>is</span> <span m=''3696080''>supposed</span>
  <span m=''3696240''>to</span> <span m=''3696400''>add term-lists.</span> </p><p><span
  m=''3698480''>Let''s</span> <span m=''3698670''>look</span> <span m=''3698850''>at</span>
  <span m=''3698950''>that.</span> <span m=''3700920''>Here''s</span> <span m=''3701380''>an</span>
  <span m=''3701480''>overview</span> <span m=''3702860''>of</span> <span m=''3703030''>how</span>
  <span m=''3703170''>we</span> <span m=''3703300''>might</span> <span m=''3707180''>add</span>
  <span m=''3707360''>two</span> <span m=''3707510''>term-lists.</span> <span m=''3708900''>So</span>
  <span m=''3709050''>L1</span> <span m=''3709810''>and</span> <span m=''3709990''>L2</span>
  <span m=''3710330''>were</span> <span m=''3710460''>going</span> <span m=''3710550''>to</span>
  <span m=''3710640''>be</span> <span m=''3710730''>two</span> <span m=''3711270''>term-lists.</span>
  <span m=''3711860''>And</span> <span m=''3711930''>a</span> <span m=''3711990''>term-list</span>
  <span m=''3712510''>is</span> <span m=''3712620''>a</span> <span m=''3713020''>bunch</span>
  <span m=''3713260''>of</span> <span m=''3713360''>pairs,</span> <span m=''3713700''>coefficient</span>
  <span m=''3714290''>in</span> <span m=''3714380''>order.</span> <span m=''3715700''>And</span>
  <span m=''3715900''>it''s</span> <span m=''3716040''>a big</span> <span m=''3716160''>case</span>
  <span m=''3716460''>analysis.</span> <span m=''3719860''>And</span> <span m=''3719990''>the</span>
  <span m=''3720130''>first</span> <span m=''3721800''>thing</span> <span m=''3721930''>we''ll</span>
  <span m=''3722030''>check</span> <span m=''3722320''>for</span> <span m=''3722960''>and</span>
  <span m=''3723100''>see</span> <span m=''3723250''>if</span> <span m=''3723320''>there
  are</span> <span m=''3723470''>any</span> <span m=''3723690''>terms.</span> <span
  m=''3725440''>We''re</span> <span m=''3725570''>going</span> <span m=''3725640''>to</span>
  <span m=''3725710''>recursively</span> <span m=''3726380''>work</span> <span m=''3726630''>down</span>
  <span m=''3726850''>these</span> <span m=''3727020''>term-lists,</span> <span m=''3728090''>so</span>
  <span m=''3728310''>eventually</span> <span m=''3728690''>we''ll</span> <span m=''3728820''>get</span>
  <span m=''3728970''>to</span> <span m=''3729050''>a</span> <span m=''3729140''>place</span>
  <span m=''3729450''>where</span> <span m=''3729980''>either</span> <span m=''3730200''>L1</span>
  <span m=''3730530''>or</span> <span m=''3730760''>L2</span> <span m=''3730940''>might</span>
  <span m=''3731130''>be</span> <span m=''3731260''>empty.</span> <span m=''3732270''>And</span>
  <span m=''3732480''>if</span> <span m=''3732620''>either</span> <span m=''3733620''>one</span>
  <span m=''3733840''>is</span> <span m=''3733980''>empty,</span> <span m=''3734520''>our</span>
  <span m=''3734690''>answer</span> <span m=''3735020''>will</span> <span m=''3735160''>be</span>
  <span m=''3735320''>the</span> <span m=''3735450''>other</span> <span m=''3735650''>one.</span>
  <span m=''3735850''>So</span> <span m=''3736950''>if</span> <span m=''3737120''>L1</span>
  <span m=''3737500''>is</span> <span m=''3737610''>empty</span> <span m=''3738950''>we''ll</span>
  <span m=''3739070''>return</span> <span m=''3739420''>L2,</span> <span m=''3739870''>and</span>
  <span m=''3739970''>if</span> <span m=''3740080''>L2</span> <span m=''3740460''>is
  empty</span> <span m=''3740720''>we''ll</span> <span m=''3740870''>return</span>
  <span m=''3741230''>L1.</span> </p><p><span m=''3743470''>Otherwise</span> <span
  m=''3743960''>there</span> <span m=''3744260''>are</span> <span m=''3744370''>sort
  of</span> <span m=''3744580''>three</span> <span m=''3744860''>interesting</span>
  <span m=''3745260''>cases.</span> <span m=''3747220''>What</span> <span m=''3747370''>we''re</span>
  <span m=''3747470''>going</span> <span m=''3747550''>to</span> <span m=''3747630''>do</span>
  <span m=''3747840''>is</span> <span m=''3749220''>grab</span> <span m=''3749510''>the</span>
  <span m=''3749600''>first</span> <span m=''3749970''>term</span> <span m=''3750250''>in</span>
  <span m=''3750330''>each</span> <span m=''3750490''>of</span> <span m=''3750560''>those</span>
  <span m=''3750770''>lists,</span> <span m=''3754580''>called</span> <span m=''3754810''>t1</span>
  <span m=''3755400''>and</span> <span m=''3755590''>t2.</span> <span m=''3757660''>And</span>
  <span m=''3757780''>we''re</span> <span m=''3757880''>going</span> <span m=''3757930''>to</span>
  <span m=''3757990''>look</span> <span m=''3758130''>at</span> <span m=''3758270''>three</span>
  <span m=''3758490''>cases,</span> <span m=''3760270''>depending</span> <span m=''3760800''>on</span>
  <span m=''3763090''>whether</span> <span m=''3763240''>the</span> <span m=''3763450''>order</span>
  <span m=''3763710''>of</span> <span m=''3763790''>t1</span> <span m=''3764220''>is</span>
  <span m=''3764340''>greater</span> <span m=''3764660''>than</span> <span m=''3764810''>the</span>
  <span m=''3764910''>order</span> <span m=''3765240''>of</span> <span m=''3765430''>t2,</span>
  <span m=''3767230''>or</span> <span m=''3767410''>less</span> <span m=''3767770''>than</span>
  <span m=''3768160''>t2,</span> <span m=''3769800''>or</span> <span m=''3769960''>the</span>
  <span m=''3770070''>same.</span> <span m=''3773290''>Those</span> <span m=''3773490''>are</span>
  <span m=''3773520''>the</span> <span m=''3773620''>three</span> <span m=''3773820''>cases</span>
  <span m=''3774180''>we''re</span> <span m=''3774280''>going</span> <span m=''3774360''>to</span>
  <span m=''3774430''>look</span> <span m=''3774590''>at.</span> </p><p><span m=''3774910''>Let''s</span>
  <span m=''3775100''>look</span> <span m=''3775230''>at</span> <span m=''3775360''>this</span>
  <span m=''3775490''>case.</span> <span m=''3778640''>If</span> <span m=''3778750''>the</span>
  <span m=''3778860''>order</span> <span m=''3779190''>of</span> <span m=''3779270''>t1</span>
  <span m=''3779650''>is</span> <span m=''3779780''>greater</span> <span m=''3780110''>than</span>
  <span m=''3780260''>the</span> <span m=''3780360''>order</span> <span m=''3780600''>of</span>
  <span m=''3780680''>t2,</span> <span m=''3783420''>then</span> <span m=''3783550''>what</span>
  <span m=''3783690''>that</span> <span m=''3783890''>means</span> <span m=''3784240''>is</span>
  <span m=''3784470''>that</span> <span m=''3786060''>our</span> <span m=''3786280''>answer</span>
  <span m=''3786750''>is</span> <span m=''3786880''>going</span> <span m=''3786950''>to</span>
  <span m=''3787030''>start</span> <span m=''3787560''>with</span> <span m=''3788280''>this</span>
  <span m=''3788540''>term</span> <span m=''3788910''>of</span> <span m=''3789010''>the</span>
  <span m=''3789100''>order of</span> <span m=''3789360''>t1.</span> <span m=''3791480''>Because</span>
  <span m=''3791820''>it</span> <span m=''3791900''>won''t</span> <span m=''3792100''>combine</span>
  <span m=''3792570''>with</span> <span m=''3792710''>any</span> <span m=''3792890''>lower</span>
  <span m=''3793350''>order</span> <span m=''3793420''>terms.</span> <span m=''3794170''>So</span>
  <span m=''3794350''>what we</span> <span m=''3794560''>do</span> <span m=''3794670''>is</span>
  <span m=''3794860''>add</span> <span m=''3795080''>the</span> <span m=''3795160''>lower</span>
  <span m=''3795470''>order</span> <span m=''3795740''>terms.</span> <span m=''3796910''>We</span>
  <span m=''3797180''>recursively</span> <span m=''3797810''>add</span> <span m=''3799720''>together</span>
  <span m=''3800110''>all</span> <span m=''3800300''>the</span> <span m=''3800390''>terms</span>
  <span m=''3801120''>in</span> <span m=''3801290''>the</span> <span m=''3801390''>rest</span>
  <span m=''3801730''>of</span> <span m=''3801820''>the</span> <span m=''3801900''>term-list</span>
  <span m=''3802540''>in</span> <span m=''3802700''>L1</span> <span m=''3804410''>and</span>
  <span m=''3804550''>L2.</span> <span m=''3806880''>That''s</span> <span m=''3807430''>going</span>
  <span m=''3807500''>to</span> <span m=''3807570''>be</span> <span m=''3807640''>the</span>
  <span m=''3807730''>lower</span> <span m=''3808070''>order</span> <span m=''3808350''>terms</span>
  <span m=''3808680''>of</span> <span m=''3808750''>the</span> <span m=''3808910''>answer.</span>
  <span m=''3810120''>And</span> <span m=''3810290''>then</span> <span m=''3810390''>we''re</span>
  <span m=''3810510''>going</span> <span m=''3810640''>to</span> <span m=''3810760''>adjoin</span>
  <span m=''3811100''>to that</span> <span m=''3811410''>the</span> <span m=''3811490''>highest</span>
  <span m=''3811870''>order</span> <span m=''3812070''>term.</span> </p><p><span m=''3813180''>And</span>
  <span m=''3813330''>I''m using</span> <span m=''3813690''>here</span> <span m=''3813860''>a</span>
  <span m=''3813900''>whole</span> <span m=''3814040''>bunch of</span> <span m=''3814300''>procedures</span>
  <span m=''3814780''>I</span> <span m=''3814910''>haven''t</span> <span m=''3815120''>defined,</span>
  <span m=''3815510''>like a</span> <span m=''3815730''>adjoin-term,</span> <span
  m=''3816630''>and</span> <span m=''3816800''>rest-terms,</span> <span m=''3818600''>and</span>
  <span m=''3818800''>selectors</span> <span m=''3819360''>that</span> <span m=''3819500''>get</span>
  <span m=''3819670''>order.</span> <span m=''3821410''>But</span> <span m=''3821530''>you</span>
  <span m=''3821630''>can</span> <span m=''3821750''>imagine</span> <span m=''3822160''>what</span>
  <span m=''3822290''>those</span> <span m=''3822470''>are.</span> <span m=''3824730''>So</span>
  <span m=''3826070''>if</span> <span m=''3826210''>the</span> <span m=''3826390''>first</span>
  <span m=''3826560''>term-list</span> <span m=''3827060''>has</span> <span m=''3827530''>a</span>
  <span m=''3827630''>higher</span> <span m=''3827980''>order</span> <span m=''3828340''>than</span>
  <span m=''3828480''>the</span> <span m=''3828550''>second,</span> <span m=''3828900''>we</span>
  <span m=''3829400''>recursively</span> <span m=''3829800''>add all the</span> <span
  m=''3830440''>lower</span> <span m=''3830680''>terms</span> <span m=''3831310''>and</span>
  <span m=''3831430''>then</span> <span m=''3831560''>stick</span> <span m=''3831830''>on</span>
  <span m=''3832210''>that</span> <span m=''3832740''>last</span> <span m=''3833030''>term.</span>
  <span m=''3835540''>The</span> <span m=''3835680''>other</span> <span m=''3835810''>case,</span>
  <span m=''3836120''>the</span> <span m=''3836200''>same</span> <span m=''3836480''>way.</span>
  <span m=''3836890''>If</span> <span m=''3837770''>the</span> <span m=''3837890''>first</span>
  <span m=''3838190''>term</span> <span m=''3838410''>has</span> <span m=''3839330''>a</span>
  <span m=''3839420''>smaller</span> <span m=''3839860''>order,</span> <span m=''3840530''>well</span>
  <span m=''3840750''>then</span> <span m=''3845100''>we</span> <span m=''3845400''>add</span>
  <span m=''3845530''>the</span> <span m=''3845720''>first</span> <span m=''3845900''>term-list</span>
  <span m=''3846330''>and</span> <span m=''3846410''>the</span> <span m=''3846500''>rest</span>
  <span m=''3846740''>of</span> <span m=''3846790''>the</span> <span m=''3846880''>terms</span>
  <span m=''3847210''>in</span> <span m=''3847300''>the</span> <span m=''3847740''>second</span>
  <span m=''3848110''>one,</span> <span m=''3848600''>and</span> <span m=''3848750''>adjoin</span>
  <span m=''3849110''>on</span> <span m=''3850240''>this</span> <span m=''3850460''>highest</span>
  <span m=''3850830''>order</span> <span m=''3851040''>term.</span> </p><p><span m=''3854570''>So</span>
  <span m=''3854740''>so</span> <span m=''3854890''>far</span> <span m=''3855050''>nothing''s</span>
  <span m=''3855400''>much</span> <span m=''3855630''>happened,</span> <span m=''3855925''>we''ve</span>
  <span m=''3856220''>just</span> <span m=''3856430''>sort</span> <span m=''3856580''>of</span>
  <span m=''3856660''>pushed</span> <span m=''3856880''>this</span> <span m=''3857090''>thing</span>
  <span m=''3857240''>off</span> <span m=''3857450''>into</span> <span m=''3858220''>adding</span>
  <span m=''3858490''>lower</span> <span m=''3858750''>order</span> <span m=''3858980''>terms.</span>
  <span m=''3859420''>The</span> <span m=''3859700''>last</span> <span m=''3859990''>case</span>
  <span m=''3860230''>where</span> <span m=''3860340''>you</span> <span m=''3860460''>actually</span>
  <span m=''3860870''>get</span> <span m=''3861080''>to</span> <span m=''3861180''>a</span>
  <span m=''3861290''>coefficients</span> <span m=''3862110''>that</span> <span m=''3862760''>you</span>
  <span m=''3862870''>have</span> <span m=''3863060''>to</span> <span m=''3863190''>add,</span>
  <span m=''3863500''>this</span> <span m=''3863640''>will</span> <span m=''3863710''>be</span>
  <span m=''3863800''>the</span> <span m=''3863890''>case</span> <span m=''3864150''>where</span>
  <span m=''3864240''>the</span> <span m=''3864350''>orders are</span> <span m=''3864670''>equal.</span>
  <span m=''3867240''>What</span> <span m=''3867410''>we</span> <span m=''3867530''>do</span>
  <span m=''3867880''>is,</span> <span m=''3868860''>well</span> <span m=''3868990''>again</span>
  <span m=''3869200''>recursively</span> <span m=''3869850''>add</span> <span m=''3869980''>the</span>
  <span m=''3870060''>lower</span> <span m=''3870340''>order</span> <span m=''3870590''>terms.</span>
  <span m=''3871020''>But</span> <span m=''3871150''>now</span> <span m=''3871310''>we</span>
  <span m=''3871410''>have</span> <span m=''3871560''>to</span> <span m=''3871660''>really</span>
  <span m=''3871890''>combine</span> <span m=''3872340''>something.</span> <span m=''3873460''>What</span>
  <span m=''3873600''>we</span> <span m=''3873740''>do</span> <span m=''3874080''>is</span>
  <span m=''3874310''>we</span> <span m=''3875550''>make</span> <span m=''3875800''>a</span>
  <span m=''3875860''>term</span> <span m=''3877090''>whose</span> <span m=''3877490''>order</span>
  <span m=''3878330''>is</span> <span m=''3878490''>the</span> <span m=''3878610''>order</span>
  <span m=''3878910''>of</span> <span m=''3878960''>the</span> <span m=''3879050''>term</span>
  <span m=''3879310''>we''re</span> <span m=''3879400''>looking</span> <span m=''3879760''>at.</span>
  <span m=''3880820''>By</span> <span m=''3880990''>now</span> <span m=''3881160''>t1</span>
  <span m=''3881560''>and</span> <span m=''3881660''>t2</span> <span m=''3881970''>have</span>
  <span m=''3882060''>the</span> <span m=''3882130''>same</span> <span m=''3882380''>order.</span>
  <span m=''3884320''>That''s</span> <span m=''3884520''>its</span> <span m=''3884640''>order.</span>
  <span m=''3885090''>And</span> <span m=''3885240''>its</span> <span m=''3885380''>coefficient</span>
  <span m=''3886230''>is</span> <span m=''3886500''>gotten</span> <span m=''3886790''>by</span>
  <span m=''3886990''>adding</span> <span m=''3889650''>the</span> <span m=''3889780''>coefficient</span>
  <span m=''3890310''>of</span> <span m=''3890400''>t1</span> <span m=''3890960''>and</span>
  <span m=''3891060''>the</span> <span m=''3891160''>coefficient</span> <span m=''3891660''>of</span>
  <span m=''3891760''>t2.</span> </p><p><span m=''3896360''>This</span> <span m=''3896530''>is</span>
  <span m=''3896620''>a</span> <span m=''3896670''>big</span> <span m=''3896880''>recursive</span>
  <span m=''3898650''>working</span> <span m=''3899000''>down</span> <span m=''3899210''>of</span>
  <span m=''3899290''>terms,</span> <span m=''3899650''>but</span> <span m=''3899800''>really</span>
  <span m=''3900320''>there''s</span> <span m=''3900620''>only</span> <span m=''3900880''>one</span>
  <span m=''3901120''>interesting</span> <span m=''3902320''>symbol</span> <span m=''3902830''>in</span>
  <span m=''3902950''>this</span> <span m=''3903070''>procedure,</span> <span m=''3904260''>only</span>
  <span m=''3904530''>one</span> <span m=''3904740''>interesting</span> <span m=''3905270''>idea.</span>
  <span m=''3905900''>The</span> <span m=''3906010''>interesting</span> <span m=''3906450''>idea</span>
  <span m=''3907750''>is</span> <span m=''3907950''>this</span> <span m=''3908170''>add.</span>
  <span m=''3912390''>And</span> <span m=''3912470''>the</span> <span m=''3912540''>reason</span>
  <span m=''3912790''>that''s</span> <span m=''3913010''>interesting</span> <span
  m=''3914220''>is</span> <span m=''3914400''>because</span> <span m=''3915330''>something</span>
  <span m=''3915780''>completely</span> <span m=''3916280''>wonderful</span> <span
  m=''3916760''>just</span> <span m=''3917000''>happened.</span> <span m=''3918220''>We</span>
  <span m=''3918920''>reduced</span> <span m=''3919880''>adding</span> <span m=''3920750''>polynomials,</span>
  <span m=''3922570''>not</span> <span m=''3923040''>to</span> <span m=''3924070''>sort</span>
  <span m=''3924350''>of</span> <span m=''3924470''>plus,</span> <span m=''3925130''>but</span>
  <span m=''3925340''>to</span> <span m=''3925440''>the</span> <span m=''3925550''>generic</span>
  <span m=''3926070''>add.</span> <span m=''3928820''>In</span> <span m=''3928960''>other</span>
  <span m=''3929140''>words,</span> <span m=''3930990''>by</span> <span m=''3931140''>implementing</span>
  <span m=''3931600''>it</span> <span m=''3931720''>that</span> <span m=''3931980''>way,</span>
  <span m=''3933040''>not</span> <span m=''3933270''>only</span> <span m=''3933510''>do</span>
  <span m=''3933610''>we</span> <span m=''3933720''>have</span> <span m=''3933960''>our</span>
  <span m=''3934080''>system</span> <span m=''3935910''>where</span> <span m=''3936090''>we</span>
  <span m=''3936220''>can</span> <span m=''3936370''>have</span> <span m=''3937050''>rational</span>
  <span m=''3937530''>numbers,</span> <span m=''3939030''>or</span> <span m=''3939220''>complex</span>
  <span m=''3939790''>numbers,</span> <span m=''3940520''>or</span> <span m=''3940730''>ordinary</span>
  <span m=''3941220''>numbers,</span> <span m=''3941880''>we''ve</span> <span m=''3942090''>just</span>
  <span m=''3942520''>added</span> <span m=''3942810''>on</span> <span m=''3942980''>polynomials.</span>
  <span m=''3948520''>But</span> <span m=''3949300''>the</span> <span m=''3949810''>coefficients</span>
  <span m=''3950480''>of</span> <span m=''3950540''>the</span> <span m=''3950610''>polynomials</span>
  <span m=''3951250''>can</span> <span m=''3951340''>be</span> <span m=''3951470''>anything</span>
  <span m=''3951820''>that</span> <span m=''3951960''>the</span> <span m=''3952040''>system</span>
  <span m=''3952420''>can</span> <span m=''3952600''>add.</span> <span m=''3953590''>So</span>
  <span m=''3953770''>these</span> <span m=''3953970''>could</span> <span m=''3954120''>be</span>
  <span m=''3954350''>polynomials</span> <span m=''3955690''>whose</span> <span m=''3956070''>coefficients</span>
  <span m=''3957190''>are</span> <span m=''3957450''>rational</span> <span m=''3957940''>numbers</span>
  <span m=''3959570''>or</span> <span m=''3960100''>complex</span> <span m=''3960760''>numbers,</span>
  <span m=''3962890''>which</span> <span m=''3963200''>in</span> <span m=''3963400''>turn</span>
  <span m=''3963880''>could</span> <span m=''3964110''>be</span> <span m=''3964260''>either</span>
  <span m=''3964540''>rectangular,</span> <span m=''3966270''>or</span> <span m=''3966420''>polar,</span>
  <span m=''3969140''>or</span> <span m=''3970430''>ordinary</span> <span m=''3970930''>numbers.</span>
  </p><p><span m=''3979860''>So</span> <span m=''3980080''>what</span> <span m=''3980210''>I</span>
  <span m=''3980250''>mean</span> <span m=''3980440''>precisely</span> <span m=''3981040''>is</span>
  <span m=''3982080''>our</span> <span m=''3982230''>system</span> <span m=''3982630''>right</span>
  <span m=''3982960''>now</span> <span m=''3983460''>automatically</span> <span m=''3986570''>can</span>
  <span m=''3986770''>handle</span> <span m=''3987160''>things</span> <span m=''3987510''>like</span>
  <span m=''3989620''>adding</span> <span m=''3989870''>together</span> <span m=''3990200''>polynomials</span>
  <span m=''3990760''>that</span> <span m=''3990880''>have</span> <span m=''3991040''>this</span>
  <span m=''3991270''>one:</span> <span m=''3991470''>2/3</span> <span m=''3992720''>of</span>
  <span m=''3992860''>x</span> <span m=''3993200''>squared</span> <span m=''3994370''>plus</span>
  <span m=''3995830''>5/17 x</span> <span m=''3998700''>plus</span> <span m=''3998950''>11/4.</span>
  <span m=''4000940''>Or</span> <span m=''4001250''>automatically</span> <span m=''4001980''>handle</span>
  <span m=''4002280''>polynomials</span> <span m=''4002910''>that</span> <span m=''4003070''>look</span>
  <span m=''4003250''>like</span> <span m=''4004000''>3</span> <span m=''4004210''>plus</span>
  <span m=''4004510''>2i</span> <span m=''4005520''>times x</span> <span m=''4006070''>to</span>
  <span m=''4006150''>the</span> <span m=''4006260''>fifth</span> <span m=''4007340''>plus</span>
  <span m=''4009560''>4</span> <span m=''4009950''>plus</span> <span m=''4011270''>7i,</span>
  <span m=''4011840''>or</span> <span m=''4012110''>something.</span> <span m=''4014160''>You</span>
  <span m=''4014280''>can</span> <span m=''4014630''>automatically</span> <span m=''4015580''>handle</span>
  <span m=''4015680''>those</span> <span m=''4015920''>things.</span> <span m=''4016210''>Why</span>
  <span m=''4016480''>is</span> <span m=''4016740''>that?</span> <span m=''4017820''>That''s</span>
  <span m=''4019460''>merely</span> <span m=''4019810''>because,</span> <span m=''4020250''>or</span>
  <span m=''4020480''>profoundly</span> <span m=''4021020''>because</span> <span m=''4022200''>we</span>
  <span m=''4022360''>reduced</span> <span m=''4023280''>adding</span> <span m=''4023710''>polynomials</span>
  <span m=''4024500''>to</span> <span m=''4024640''>adding</span> <span m=''4025000''>their</span>
  <span m=''4025210''>coefficients.</span> <span m=''4026790''>And</span> <span m=''4026990''>adding</span>
  <span m=''4027270''>coefficients</span> <span m=''4028230''>was</span> <span m=''4028490''>done</span>
  <span m=''4028710''>by</span> <span m=''4028870''>the</span> <span m=''4028980''>generic</span>
  <span m=''4029450''>add</span> <span m=''4029670''>operator,</span> <span m=''4031180''>which</span>
  <span m=''4031350''>said,</span> <span m=''4031720''>I</span> <span m=''4031860''>don''t</span>
  <span m=''4032010''>care</span> <span m=''4032210''>what</span> <span m=''4032340''>your</span>
  <span m=''4032460''>types</span> <span m=''4032780''>are</span> <span m=''4032890''>as</span>
  <span m=''4032970''>long</span> <span m=''4033130''>as</span> <span m=''4033220''>I</span>
  <span m=''4033290''>know</span> <span m=''4033390''>how</span> <span m=''4033490''>to</span>
  <span m=''4033580''>add</span> <span m=''4033860''>you.</span> <span m=''4035170''>So</span>
  <span m=''4035390''>automatically</span> <span m=''4036040''>for</span> <span m=''4036210''>free</span>
  <span m=''4037380''>we</span> <span m=''4037500''>get</span> <span m=''4037680''>the</span>
  <span m=''4037800''>ability</span> <span m=''4038210''>to</span> <span m=''4038310''>handle</span>
  <span m=''4038630''>that.</span> </p><p><span m=''4040880''>What''s</span> <span
  m=''4041090''>even</span> <span m=''4041290''>better</span> <span m=''4041580''>than</span>
  <span m=''4041740''>that,</span> <span m=''4042240''>because</span> <span m=''4042550''>remember</span>
  <span m=''4044570''>one</span> <span m=''4044760''>of</span> <span m=''4044840''>the</span>
  <span m=''4044920''>things</span> <span m=''4045180''>we</span> <span m=''4045300''>did</span>
  <span m=''4045870''>is</span> <span m=''4047310''>we</span> <span m=''4047450''>put</span>
  <span m=''4047670''>into</span> <span m=''4047900''>the</span> <span m=''4048010''>table</span>
  <span m=''4048820''>that</span> <span m=''4049110''>the</span> <span m=''4049190''>way</span>
  <span m=''4049360''>you</span> <span m=''4049550''>add</span> <span m=''4049870''>polynomials</span>
  <span m=''4051340''>is</span> <span m=''4051520''>using</span> <span m=''4051810''>plus</span>
  <span m=''4052110''>poly.</span> <span m=''4054660''>That</span> <span m=''4054880''>means</span>
  <span m=''4055110''>that</span> <span m=''4056090''>polynomials</span> <span m=''4056880''>themselves</span>
  <span m=''4057420''>are</span> <span m=''4057480''>things</span> <span m=''4057750''>that</span>
  <span m=''4057880''>can</span> <span m=''4058030''>be</span> <span m=''4058190''>added.</span>
  <span m=''4059370''>So</span> <span m=''4059590''>for</span> <span m=''4059790''>instance</span>
  <span m=''4061230''>let</span> <span m=''4061320''>me</span> <span m=''4061440''>write</span>
  <span m=''4061650''>one</span> <span m=''4061810''>here.</span> <span m=''4065260''>Here''s</span>
  <span m=''4065460''>a</span> <span m=''4065830''>polynomial.</span> <span m=''4070560''>So</span>
  <span m=''4070750''>this</span> <span m=''4071030''>gadget</span> <span m=''4071440''>here</span>
  <span m=''4071900''>I''m writing up,</span> <span m=''4074240''>this</span> <span
  m=''4074510''>is</span> <span m=''4074670''>a</span> <span m=''4075080''>polynomial</span>
  <span m=''4077660''>in</span> <span m=''4077890''>y</span> <span m=''4080940''>whose</span>
  <span m=''4081350''>coefficients</span> <span m=''4082090''>are</span> <span m=''4082710''>polynomials</span>
  <span m=''4084030''>in</span> <span m=''4084290''>x.</span> <span m=''4088610''>So</span>
  <span m=''4088850''>you</span> <span m=''4089050''>see,</span> <span m=''4089210''>simply</span>
  <span m=''4089600''>by</span> <span m=''4090470''>saying,</span> <span m=''4091730''>polynomials</span>
  <span m=''4092470''>are</span> <span m=''4092630''>themselves</span> <span m=''4093110''>things</span>
  <span m=''4093300''>that</span> <span m=''4093440''>can</span> <span m=''4093580''>be</span>
  <span m=''4093720''>added,</span> <span m=''4094460''>we</span> <span m=''4094580''>can</span>
  <span m=''4094700''>go</span> <span m=''4094810''>off</span> <span m=''4094970''>and</span>
  <span m=''4095060''>say,</span> <span m=''4095210''>well</span> <span m=''4095360''>not</span>
  <span m=''4095590''>only</span> <span m=''4096310''>can</span> <span m=''4096500''>we</span>
  <span m=''4096630''>deal</span> <span m=''4096870''>with</span> <span m=''4097370''>rationals,</span>
  <span m=''4098290''>or</span> <span m=''4098439''>complex,</span> <span m=''4099350''>or</span>
  <span m=''4099560''>ordinary</span> <span m=''4100000''>numbers,</span> <span m=''4100350''>but</span>
  <span m=''4100470''>we</span> <span m=''4100580''>can</span> <span m=''4100720''>deal</span>
  <span m=''4100899''>with</span> <span m=''4101069''>polynomials</span> <span m=''4101890''>whose</span>
  <span m=''4102330''>coefficients</span> <span m=''4102890''>are</span> <span m=''4102979''>rationals,</span>
  <span m=''4103410''>or</span> <span m=''4103569''>complex,</span> <span m=''4104350''>or</span>
  <span m=''4104490''>ordinary</span> <span m=''4104960''>numbers,</span> <span m=''4105420''>or</span>
  <span m=''4106620''>polynomials</span> <span m=''4108920''>whose</span> <span m=''4109630''>coefficients</span>
  <span m=''4110189''>are</span> <span m=''4110350''>rationals,</span> <span m=''4111729''>or</span>
  <span m=''4111979''>complex,</span> <span m=''4114140''>rectangular,</span> <span
  m=''4114740''>polar,</span> <span m=''4115529''>or</span> <span m=''4115760''>ordinary</span>
  <span m=''4116250''>numbers,</span> <span m=''4117060''>or</span> <span m=''4117569''>polynomials</span>
  <span m=''4119040''>whose</span> <span m=''4119439''>coefficients</span> <span m=''4119970''>are</span>
  <span m=''4120540''>rationals,</span> <span m=''4121700''>complex,</span> <span
  m=''4122154''>or</span> <span m=''4122609''>ordinary</span> <span m=''4123010''>numbers.</span>
  <span m=''4123670''>And</span> <span m=''4123850''>so</span> <span m=''4124029''>on,</span>
  <span m=''4124189''>and</span> <span m=''4124319''>so</span> <span m=''4124460''>on,</span>
  <span m=''4124600''>and so</span> <span m=''4124790''>on.</span> </p><p><span m=''4125950''>So</span>
  <span m=''4126140''>this</span> <span m=''4126319''>is</span> <span m=''4126410''>sort</span>
  <span m=''4126600''>of</span> <span m=''4126700''>an</span> <span m=''4126960''>infinite</span>
  <span m=''4128470''>or</span> <span m=''4128600''>maybe</span> <span m=''4128870''>a</span>
  <span m=''4128950''>recursive</span> <span m=''4130270''>tower</span> <span m=''4130729''>of</span>
  <span m=''4130830''>types</span> <span m=''4132130''>that</span> <span m=''4132290''>we''ve</span>
  <span m=''4132439''>built</span> <span m=''4132729''>up.</span> <span m=''4133880''>And</span>
  <span m=''4134050''>it''s</span> <span m=''4134229''>all</span> <span m=''4134770''>exactly</span>
  <span m=''4135330''>from</span> <span m=''4135460''>that</span> <span m=''4135620''>one</span>
  <span m=''4135770''>little</span> <span m=''4135950''>symbol.</span> <span m=''4136420''>A-D-D.</span>
  <span m=''4137649''>Writing</span> <span m=''4137950''>"add"</span> <span m=''4138229''>instead</span>
  <span m=''4138550''>of</span> <span m=''4138649''>"plus"</span> <span m=''4139430''>in
  the</span> <span m=''4139800''>polynomial</span> <span m=''4140240''>thing.</span>
  </p><p><span m=''4142270''>Slightly</span> <span m=''4142649''>different</span>
  <span m=''4142890''>way</span> <span m=''4142990''>to</span> <span m=''4143069''>think</span>
  <span m=''4143300''>about</span> <span m=''4143600''>it</span> <span m=''4143990''>is</span>
  <span m=''4144220''>that</span> <span m=''4144620''>polynomials</span> <span m=''4145979''>are</span>
  <span m=''4146319''>a</span> <span m=''4146380''>constructor</span> <span m=''4147090''>for</span>
  <span m=''4147319''>types.</span> <span m=''4148740''>Namely</span> <span m=''4149000''>you</span>
  <span m=''4149100''>give</span> <span m=''4149279''>it</span> <span m=''4149340''>a</span>
  <span m=''4149430''>type,</span> <span m=''4150050''>like</span> <span m=''4150729''>integer,</span>
  <span m=''4151540''>and it</span> <span m=''4151710''>returns</span> <span m=''4152149''>for</span>
  <span m=''4152270''>you</span> <span m=''4152689''>polynomials</span> <span m=''4153800''>in
  x</span> <span m=''4154175''>whose</span> <span m=''4154550''>coefficients</span>
  <span m=''4155130''>are</span> <span m=''4155450''>integers.</span> <span m=''4156279''>And</span>
  <span m=''4156390''>the</span> <span m=''4156500''>important</span> <span m=''4156899''>thing</span>
  <span m=''4157040''>about</span> <span m=''4157399''>that</span> <span m=''4158680''>is</span>
  <span m=''4158930''>that</span> <span m=''4159069''>the</span> <span m=''4159210''>operations</span>
  <span m=''4159880''>on</span> <span m=''4160010''>polynomials</span> <span m=''4161359''>reduce</span>
  <span m=''4161740''>to</span> <span m=''4161830''>the</span> <span m=''4161950''>operations</span>
  <span m=''4162540''>on</span> <span m=''4162640''>the</span> <span m=''4162729''>coefficients.</span>
  <span m=''4163500''>And</span> <span m=''4163609''>there</span> <span m=''4163710''>are</span>
  <span m=''4163850''>a</span> <span m=''4163930''>lot</span> <span m=''4164000''>of</span>
  <span m=''4164080''>things</span> <span m=''4164270''>like</span> <span m=''4164609''>that.</span>
  </p><p><span m=''4165840''>So</span> <span m=''4166020''>for</span> <span m=''4166170''>example,</span>
  <span m=''4166649''>let''s</span> <span m=''4166800''>go</span> <span m=''4166870''>back</span>
  <span m=''4167060''>and</span> <span m=''4167140''>rational</span> <span m=''4167580''>numbers.</span>
  <span m=''4168870''>We</span> <span m=''4168990''>thought</span> <span m=''4169160''>about</span>
  <span m=''4169430''>rational</span> <span m=''4169899''>numbers</span> <span m=''4170330''>as</span>
  <span m=''4171550''>an</span> <span m=''4171640''>integer</span> <span m=''4172069''>over</span>
  <span m=''4172330''>an</span> <span m=''4172410''>integer,</span> <span m=''4172779''>but</span>
  <span m=''4172910''>there''s</span> <span m=''4173109''>the</span> <span m=''4173170''>general</span>
  <span m=''4173569''>notion</span> <span m=''4174229''>of</span> <span m=''4174490''>a</span>
  <span m=''4174590''>rational</span> <span m=''4175060''>object.</span> <span m=''4176240''>Like</span>
  <span m=''4176420''>we</span> <span m=''4176510''>might</span> <span m=''4176830''>think</span>
  <span m=''4177229''>about</span> <span m=''4177560''>3x</span> <span m=''4178029''>plus</span>
  <span m=''4178319''>7</span> <span m=''4179640''>over</span> <span m=''4180859''>x</span>
  <span m=''4181080''>squared</span> <span m=''4181319''>plus</span> <span m=''4181560''>1.</span>
  <span m=''4183010''>That''s</span> <span m=''4183930''>general</span> <span m=''4184290''>rational</span>
  <span m=''4184819''>object</span> <span m=''4186740''>whose</span> <span m=''4186960''>numerator</span>
  <span m=''4187140''>and</span> <span m=''4187430''>denominator</span> <span m=''4188080''>are</span>
  <span m=''4188420''>polynomials.</span> <span m=''4190310''>And</span> <span m=''4190510''>to</span>
  <span m=''4190649''>add</span> <span m=''4190850''>two</span> <span m=''4191029''>of</span>
  <span m=''4191149''>them</span> <span m=''4191260''>we</span> <span m=''4191359''>use</span>
  <span m=''4191529''>the</span> <span m=''4191609''>same</span> <span m=''4191880''>formula,</span>
  <span m=''4192460''>numerator</span> <span m=''4192990''>times</span> <span m=''4193310''>denominator</span>
  <span m=''4193870''>plus</span> <span m=''4194120''>denominator</span> <span m=''4194630''>times</span>
  <span m=''4194900''>numerator</span> <span m=''4195720''>over</span> <span m=''4195910''>product</span>
  <span m=''4196290''>of</span> <span m=''4196350''>denominators.</span> </p><p><span
  m=''4197290''>How</span> <span m=''4197450''>could</span> <span m=''4197600''>we</span>
  <span m=''4198160''>install</span> <span m=''4198600''>that</span> <span m=''4198760''>in</span>
  <span m=''4198920''>our</span> <span m=''4199020''>system?</span> <span m=''4199430''>Well</span>
  <span m=''4199540''>here''s</span> <span m=''4199790''>our</span> <span m=''4199920''>original</span>
  <span m=''4201400''>rational</span> <span m=''4201820''>number</span> <span m=''4202110''>arithmetic</span>
  <span m=''4202570''>package.</span> <span m=''4204250''>And</span> <span m=''4204460''>all</span>
  <span m=''4204790''>we</span> <span m=''4204940''>have</span> <span m=''4205230''>to</span>
  <span m=''4205350''>do</span> <span m=''4206530''>in</span> <span m=''4206680''>order</span>
  <span m=''4206910''>to</span> <span m=''4207030''>make</span> <span m=''4207260''>the</span>
  <span m=''4207370''>entire</span> <span m=''4207800''>system</span> <span m=''4208660''>continue</span>
  <span m=''4209130''>working</span> <span m=''4209770''>with</span> <span m=''4209990''>general</span>
  <span m=''4210730''>rational</span> <span m=''4211240''>objects,</span> <span m=''4211960''>is</span>
  <span m=''4212140''>replace</span> <span m=''4212530''>these</span> <span m=''4212690''>particular</span>
  <span m=''4213410''>pluses</span> <span m=''4213950''>and</span> <span m=''4214110''>stars</span>
  <span m=''4215210''>by</span> <span m=''4215540''>the</span> <span m=''4215650''>generic</span>
  <span m=''4216050''>operator.</span> <span m=''4216480''>So if</span> <span m=''4216670''>we</span>
  <span m=''4216760''>simply</span> <span m=''4217050''>change</span> <span m=''4217340''>that</span>
  <span m=''4217540''>procedure</span> <span m=''4218180''>to</span> <span m=''4218720''>this</span>
  <span m=''4218950''>one,</span> <span m=''4219710''>here</span> <span m=''4219870''>we''ve</span>
  <span m=''4220050''>changed</span> <span m=''4220360''>plus</span> <span m=''4220730''>and</span>
  <span m=''4220870''>star</span> <span m=''4221300''>to add</span> <span m=''4221560''>a</span>
  <span m=''4221620''>mul,</span> <span m=''4222930''>those are</span> <span m=''4223100''>absolutely</span>
  <span m=''4223700''>the</span> <span m=''4223850''>only</span> <span m=''4224000''>change,</span>
  <span m=''4224950''>then</span> <span m=''4225410''>suddenly</span> <span m=''4227510''>our</span>
  <span m=''4227720''>entire</span> <span m=''4228170''>system</span> <span m=''4228780''>can</span>
  <span m=''4228920''>start</span> <span m=''4229210''>talking</span> <span m=''4229580''>about</span>
  <span m=''4229830''>objects</span> <span m=''4230480''>that</span> <span m=''4230730''>look</span>
  <span m=''4230900''>like</span> <span m=''4231150''>this.</span> </p><p><span m=''4234000''>So</span>
  <span m=''4234140''>for</span> <span m=''4234680''>example,</span> <span m=''4235200''>here</span>
  <span m=''4235670''>is</span> <span m=''4236060''>a</span> <span m=''4237400''>rational</span>
  <span m=''4237840''>object</span> <span m=''4239230''>whose</span> <span m=''4240350''>numerator</span>
  <span m=''4241950''>is</span> <span m=''4242140''>a</span> <span m=''4242530''>polynomial</span>
  <span m=''4242750''>in</span> <span m=''4242920''>x</span> <span m=''4243200''>whose</span>
  <span m=''4243360''>coefficients</span> <span m=''4243950''>are</span> <span m=''4244030''>rational</span>
  <span m=''4244440''>numbers.</span> <span m=''4247350''>Or here</span> <span m=''4247620''>is</span>
  <span m=''4248300''>a</span> <span m=''4248500''>rational</span> <span m=''4249010''>object</span>
  <span m=''4251110''>whose</span> <span m=''4251330''>numerator</span> <span m=''4252350''>is</span>
  <span m=''4253320''>polynomials</span> <span m=''4253740''>in</span> <span m=''4254040''>x</span>
  <span m=''4255180''>whose</span> <span m=''4255420''>coefficients</span> <span m=''4256110''>are</span>
  <span m=''4257180''>rational</span> <span m=''4257700''>objects</span> <span m=''4259930''>constructed</span>
  <span m=''4260480''>out</span> <span m=''4260620''>of</span> <span m=''4260720''>complex</span>
  <span m=''4261200''>numbers.</span> <span m=''4263390''>And</span> <span m=''4263520''>then</span>
  <span m=''4263650''>there</span> <span m=''4263730''>are</span> <span m=''4263750''>a</span>
  <span m=''4263840''>lot</span> <span m=''4263930''>of</span> <span m=''4264020''>other</span>
  <span m=''4264240''>things</span> <span m=''4264500''>like</span> <span m=''4264680''>that.</span>
  </p><p><span m=''4264850''>See,</span> <span m=''4264950''>whenever</span> <span
  m=''4265270''>you</span> <span m=''4265680''>have</span> <span m=''4265900''>a</span>
  <span m=''4265950''>thing</span> <span m=''4266210''>where</span> <span m=''4266350''>the</span>
  <span m=''4266490''>operations</span> <span m=''4267160''>reduce to</span> <span
  m=''4267500''>operations</span> <span m=''4268090''>on</span> <span m=''4268190''>the</span>
  <span m=''4268270''>pieces,</span> <span m=''4268890''>another</span> <span m=''4269290''>example</span>
  <span m=''4269690''>would</span> <span m=''4269840''>be</span> <span m=''4270180''>two</span>
  <span m=''4270450''>by</span> <span m=''4270600''>two</span> <span m=''4270810''>matrices.</span>
  <span m=''4272310''>I</span> <span m=''4272400''>have</span> <span m=''4273710''>the</span>
  <span m=''4273830''>idea,</span> <span m=''4274120''>there</span> <span m=''4274210''>might</span>
  <span m=''4274430''>be a</span> <span m=''4274560''>matrix</span> <span m=''4275060''>here</span>
  <span m=''4276430''>of</span> <span m=''4276640''>general</span> <span m=''4277030''>things</span>
  <span m=''4277290''>that</span> <span m=''4277380''>I</span> <span m=''4277470''>don''t</span>
  <span m=''4277670''>care</span> <span m=''4277940''>about.</span> <span m=''4278650''>But</span>
  <span m=''4278970''>if</span> <span m=''4279090''>I</span> <span m=''4279260''>add</span>
  <span m=''4279490''>two</span> <span m=''4279710''>of</span> <span m=''4279830''>them,</span>
  <span m=''4282280''>the</span> <span m=''4282530''>answer</span> <span m=''4284130''>over</span>
  <span m=''4284340''>here</span> <span m=''4284620''>is</span> <span m=''4284730''>gotten</span>
  <span m=''4285010''>by</span> <span m=''4285180''>adding</span> <span m=''4285610''>this</span>
  <span m=''4285840''>one</span> <span m=''4286320''>and</span> <span m=''4286540''>that</span>
  <span m=''4286760''>one,</span> <span m=''4286890''>however</span> <span m=''4287260''>they</span>
  <span m=''4287440''>like</span> <span m=''4287720''>to</span> <span m=''4287830''>add.</span>
  <span m=''4289030''>So</span> <span m=''4289270''>I</span> <span m=''4289570''>can</span>
  <span m=''4290030''>implement</span> <span m=''4290500''>that</span> <span m=''4290630''>the</span>
  <span m=''4290710''>same</span> <span m=''4290970''>way.</span> <span m=''4291110''>And</span>
  <span m=''4291180''>if</span> <span m=''4291260''>I</span> <span m=''4291340''>do</span>
  <span m=''4291530''>that,</span> <span m=''4291950''>then</span> <span m=''4292120''>again</span>
  <span m=''4292360''>suddenly</span> <span m=''4292660''>my</span> <span m=''4292790''>system</span>
  <span m=''4293140''>can</span> <span m=''4293260''>start</span> <span m=''4293520''>handling</span>
  <span m=''4293880''>things</span> <span m=''4294130''>like</span> <span m=''4294330''>this.</span>
  <span m=''4295480''>So</span> <span m=''4295580''>here''s</span> <span m=''4295770''>a</span>
  <span m=''4295840''>matrix</span> <span m=''4297790''>whose</span> <span m=''4298010''>elements</span>
  <span m=''4298440''>happen</span> <span m=''4298780''>to</span> <span m=''4298890''>be--</span>
  <span m=''4299460''>we''ll</span> <span m=''4299570''>say</span> <span m=''4299740''>this</span>
  <span m=''4299960''>element</span> <span m=''4300330''>here</span> <span m=''4300520''>is</span>
  <span m=''4300660''>a</span> <span m=''4301180''>rational</span> <span m=''4301730''>object</span>
  <span m=''4303120''>whose</span> <span m=''4303330''>numerator</span> <span m=''4303460''>and</span>
  <span m=''4303800''>denominators</span> <span m=''4304380''>are</span> <span m=''4304490''>polynomials.</span>
  <span m=''4307230''>And</span> <span m=''4307570''>all</span> <span m=''4307830''>that</span>
  <span m=''4308780''>comes</span> <span m=''4309090''>for</span> <span m=''4309180''>free.</span>
  </p><p><span m=''4312580''>What''s</span> <span m=''4312790''>really</span> <span
  m=''4313030''>going</span> <span m=''4313310''>on</span> <span m=''4313540''>here?</span>
  <span m=''4313920''>What''s</span> <span m=''4314140''>really</span> <span m=''4314390''>going</span>
  <span m=''4314700''>on</span> <span m=''4315830''>is</span> <span m=''4317710''>getting</span>
  <span m=''4318010''>rid</span> <span m=''4318180''>of</span> <span m=''4318310''>this</span>
  <span m=''4318450''>manager</span> <span m=''4318910''>who''s</span> <span m=''4319040''>sitting</span>
  <span m=''4319350''>there</span> <span m=''4319500''>poking</span> <span m=''4319840''>his</span>
  <span m=''4320040''>nose</span> <span m=''4320340''>into</span> <span m=''4321350''>who</span>
  <span m=''4321540''>everybody''s</span> <span m=''4322060''>business is.</span>
  <span m=''4323120''>We</span> <span m=''4323230''>built</span> <span m=''4323490''>a</span>
  <span m=''4323530''>system</span> <span m=''4324260''>that</span> <span m=''4324440''>has</span>
  <span m=''4324670''>decentralized</span> <span m=''4325640''>control.</span> <span
  m=''4334350''>So</span> <span m=''4334880''>when</span> <span m=''4335000''>you</span>
  <span m=''4335080''>come</span> <span m=''4335300''>into</span> <span m=''4335570''>and</span>
  <span m=''4337090''>no</span> <span m=''4337220''>one''s</span> <span m=''4337500''>poking</span>
  <span m=''4337860''>around</span> <span m=''4338120''>saying,</span> <span m=''4338340''>gee,</span>
  <span m=''4338550''>are</span> <span m=''4338660''>you</span> <span m=''4338870''>in</span>
  <span m=''4338970''>the</span> <span m=''4339090''>official</span> <span m=''4339490''>list</span>
  <span m=''4339740''>of</span> <span m=''4341080''>people</span> <span m=''4341400''>who</span>
  <span m=''4341540''>can</span> <span m=''4341720''>be</span> <span m=''4341920''>added?</span>
  <span m=''4342440''>Rather</span> <span m=''4342690''>you</span> <span m=''4342820''>say,</span>
  <span m=''4342960''>well</span> <span m=''4343160''>go</span> <span m=''4343340''>off</span>
  <span m=''4343580''>and</span> <span m=''4343990''>add yourself</span> <span m=''4344560''>how</span>
  <span m=''4344670''>your</span> <span m=''4344850''>parts</span> <span m=''4345460''>like</span>
  <span m=''4345680''>to</span> <span m=''4345780''>be</span> <span m=''4345950''>added.</span>
  <span m=''4347810''>And</span> <span m=''4348220''>the</span> <span m=''4348280''>result</span>
  <span m=''4348630''>of</span> <span m=''4348720''>that</span> <span m=''4348900''>is</span>
  <span m=''4349000''>you</span> <span m=''4349090''>can</span> <span m=''4349230''>get</span>
  <span m=''4349860''>this</span> <span m=''4350090''>very,</span> <span m=''4350540''>very,</span>
  <span m=''4350800''>very</span> <span m=''4351030''>complex</span> <span m=''4351490''>hierarchy</span>
  <span m=''4352430''>where</span> <span m=''4352610''>a</span> <span m=''4352650''>lot</span>
  <span m=''4352870''>of</span> <span m=''4352960''>things</span> <span m=''4353220''>just</span>
  <span m=''4353400''>get</span> <span m=''4353570''>done</span> <span m=''4353760''>and</span>
  <span m=''4353870''>rooted</span> <span m=''4354140''>to</span> <span m=''4354240''>the</span>
  <span m=''4354340''>right</span> <span m=''4354540''>place</span> <span m=''4354810''>automatically.</span>
  </p><p><span m=''4356482''>Let''s</span> <span m=''4356970''>stop</span> <span m=''4357250''>for</span>
  <span m=''4357340''>questions.</span> </p><p><span m=''4360380''>AUDIENCE: You</span>
  <span m=''4360510''>say</span> <span m=''4361160''>you</span> <span m=''4361290''>get</span>
  <span m=''4361480''>this</span> <span m=''4361680''>for</span> <span m=''4361810''>free.</span>
  <span m=''4363020''>One</span> <span m=''4363320''>thing</span> <span m=''4363520''>that</span>
  <span m=''4363680''>strikes</span> <span m=''4364040''>me</span> <span m=''4364190''>is</span>
  <span m=''4364360''>that</span> <span m=''4364530''>now</span> <span m=''4364700''>you''ve</span>
  <span m=''4364940''>lost</span> <span m=''4366460''>kind</span> <span m=''4366690''>of</span>
  <span m=''4366920''>the</span> <span m=''4367260''>cleanness</span> <span m=''4367930''>of</span>
  <span m=''4368100''>the</span> <span m=''4368400''>break</span> <span m=''4368680''>between</span>
  <span m=''4369200''>what''s</span> <span m=''4369460''>on</span> <span m=''4369640''>top</span>
  <span m=''4370020''>and</span> <span m=''4370150''>what''s</span> <span m=''4370390''>underneath.</span>
  <span m=''4370910''>In</span> <span m=''4371030''>other</span> <span m=''4371160''>words,</span>
  <span m=''4371380''>now</span> <span m=''4371570''>you''re</span> <span m=''4371710''>defining</span>
  <span m=''4372290''>some</span> <span m=''4372490''>of</span> <span m=''4372620''>the</span>
  <span m=''4372770''>lower-level</span> <span m=''4373360''>procedures</span> <span
  m=''4373960''>in</span> <span m=''4374070''>terms</span> <span m=''4374470''>of</span>
  <span m=''4374560''>things</span> <span m=''4374850''>above</span> <span m=''4375190''>their</span>
  <span m=''4375340''>own line.</span> <span m=''4376610''>Isn''t</span> <span m=''4376910''>that</span>
  <span m=''4378920''>dangerous?</span> <span m=''4380350''>Or, if</span> <span m=''4380780''>nothing</span>
  <span m=''4381070''>more,</span> <span m=''4382400''>a</span> <span m=''4382610''>little</span>
  <span m=''4382900''>less</span> <span m=''4383850''>structured?</span> </p><p><span
  m=''4385440''>PROFESSOR: No,</span> <span m=''4385710''>I--</span> <span m=''4386125''>the</span>
  <span m=''4386420''>question is</span> <span m=''4386690''>whether</span> <span
  m=''4386890''>that''s</span> <span m=''4387110''>less</span> <span m=''4387290''>structured.</span>
  <span m=''4387770''>Depends on</span> <span m=''4387890''>what</span> <span m=''4388030''>you</span>
  <span m=''4388130''>mean</span> <span m=''4388280''>by</span> <span m=''4388410''>structure.</span>
  <span m=''4388690''>All</span> <span m=''4388970''>this</span> <span m=''4389130''>is</span>
  <span m=''4389260''>doing</span> <span m=''4389500''>is</span> <span m=''4389590''>recursion.</span>
  <span m=''4391050''>See, it''s</span> <span m=''4391320''>saying</span> <span m=''4391640''>that</span>
  <span m=''4394610''>the</span> <span m=''4394700''>way</span> <span m=''4394840''>you</span>
  <span m=''4394970''>add</span> <span m=''4395470''>these</span> <span m=''4395780''>guys</span>
  <span m=''4397240''>is</span> <span m=''4397410''>to</span> <span m=''4397530''>use</span>
  <span m=''4398350''>that.</span> <span m=''4398640''>And</span> <span m=''4398930''>that''s</span>
  <span m=''4399440''>not</span> <span m=''4399590''>less</span> <span m=''4399740''>structured,</span>
  <span m=''4400190''>it''s</span> <span m=''4400280''>just</span> <span m=''4400490''>a</span>
  <span m=''4400520''>recursive</span> <span m=''4400970''>structure.</span> <span
  m=''4402610''>So</span> <span m=''4402850''>I</span> <span m=''4402910''>don''t</span>
  <span m=''4403090''>think</span> <span m=''4403260''>it''s</span> <span m=''4403970''>particularly</span>
  <span m=''4404470''>any less clean.</span> </p><p><span m=''4404730''>AUDIENCE:
  Now</span> <span m=''4405050''>when</span> <span m=''4405280''>you</span> <span
  m=''4405400''>want</span> <span m=''4405650''>to</span> <span m=''4405750''>change</span>
  <span m=''4406200''>the</span> <span m=''4406300''>multiplier</span> <span m=''4407070''>or
  the</span> <span m=''4407250''>add</span> <span m=''4407520''>operator,</span> <span
  m=''4409320''>suddenly</span> <span m=''4409580''>you''ve</span> <span m=''4409840''>got</span>
  <span m=''4410040''>tremendous</span> <span m=''4410520''>consequences</span> <span
  m=''4411380''>underneath</span> <span m=''4411900''>that</span> <span m=''4412090''>you''re</span>
  <span m=''4412180''>not</span> <span m=''4412400''>even</span> <span m=''4412650''>sure</span>
  <span m=''4413540''>the</span> <span m=''4413670''>extent</span> <span m=''4414060''>of.</span>
  </p><p><span m=''4414480''>PROFESSOR: That''s</span> <span m=''4414730''>right,</span>
  <span m=''4415000''>but</span> <span m=''4415110''>it</span> <span m=''4415200''>depends</span>
  <span m=''4415620''>what</span> <span m=''4415780''>you</span> <span m=''4415960''>mean.</span>
  <span m=''4417080''>See,</span> <span m=''4417280''>this</span> <span m=''4417590''>goes</span>
  <span m=''4417800''>both</span> <span m=''4418020''>ways.</span> <span m=''4421790''>What</span>
  <span m=''4422140''>would</span> <span m=''4422270''>be</span> <span m=''4422410''>a</span>
  <span m=''4422440''>good</span> <span m=''4422640''>example?</span> <span m=''4424690''>I</span>
  <span m=''4424790''>ignored</span> <span m=''4425120''>greatest</span> <span m=''4425490''>common</span>
  <span m=''4425800''>divisor,</span> <span m=''4426830''>for</span> <span m=''4427030''>instance.</span>
  <span m=''4427500''>I</span> <span m=''4427830''>ignored</span> <span m=''4428160''>that</span>
  <span m=''4428380''>problem</span> <span m=''4428710''>just</span> <span m=''4428860''>to</span>
  <span m=''4428950''>keep</span> <span m=''4429130''>the</span> <span m=''4429250''>example</span>
  <span m=''4429660''>simple.</span> <span m=''4430280''>But</span> <span m=''4430520''>if</span>
  <span m=''4430630''>I</span> <span m=''4430700''>suddenly</span> <span m=''4431060''>decided</span>
  <span m=''4431850''>that</span> <span m=''4436020''>plus</span> <span m=''4436320''>rat</span>
  <span m=''4436600''>here</span> <span m=''4437760''>should</span> <span m=''4438010''>do</span>
  <span m=''4439140''>a</span> <span m=''4439280''>GCD</span> <span m=''4439820''>computation</span>
  <span m=''4440640''>and</span> <span m=''4440900''>install</span> <span m=''4441340''>that,</span>
  <span m=''4443270''>then</span> <span m=''4443450''>that</span> <span m=''4443660''>immediately</span>
  <span m=''4444330''>becomes</span> <span m=''4444750''>available</span> <span m=''4445760''>to</span>
  <span m=''4446010''>all</span> <span m=''4446180''>of</span> <span m=''4446280''>these,</span>
  <span m=''4446560''>to</span> <span m=''4446670''>that</span> <span m=''4446920''>guy,</span>
  <span m=''4447200''>and</span> <span m=''4447390''>that</span> <span m=''4447570''>guy,</span>
  <span m=''4448110''>and</span> <span m=''4448280''>that</span> <span m=''4448460''>guy,</span>
  <span m=''4449220''>and</span> <span m=''4449370''>all</span> <span m=''4449450''>the</span>
  <span m=''4449540''>way</span> <span m=''4449690''>down.</span> </p><p><span m=''4451560''>So</span>
  <span m=''4451740''>it</span> <span m=''4451810''>depends</span> <span m=''4452150''>what</span>
  <span m=''4452280''>you</span> <span m=''4452410''>mean</span> <span m=''4452610''>by</span>
  <span m=''4452720''>the</span> <span m=''4452830''>coherence</span> <span m=''4453290''>of</span>
  <span m=''4453360''>your</span> <span m=''4453500''>system.</span> <span m=''4453890''>It''s
  certainly</span> <span m=''4454540''>true</span> <span m=''4454800''>that</span>
  <span m=''4454950''>you</span> <span m=''4455060''>might</span> <span m=''4455250''>want</span>
  <span m=''4455400''>to</span> <span m=''4456380''>have</span> <span m=''4456560''>a</span>
  <span m=''4456620''>special</span> <span m=''4457030''>different</span> <span m=''4457360''>one</span>
  <span m=''4457510''>that</span> <span m=''4457890''>didn''t</span> <span m=''4458220''>filter</span>
  <span m=''4458490''>down</span> <span m=''4458710''>through</span> <span m=''4458850''>the</span>
  <span m=''4458950''>coefficients,</span> <span m=''4459610''>but</span> <span m=''4459890''>the</span>
  <span m=''4460040''>nice</span> <span m=''4460280''>thing</span> <span m=''4460430''>about</span>
  <span m=''4460720''>this</span> <span m=''4460900''>particular</span> <span m=''4461400''>example</span>
  <span m=''4461790''>is</span> <span m=''4461890''>that</span> <span m=''4462240''>mostly
  you</span> <span m=''4462730''>do.</span> </p><p><span m=''4465440''>AUDIENCE: Isn''t</span>
  <span m=''4465660''>that</span> <span m=''4466620''>the</span> <span m=''4466730''>problem,</span>
  <span m=''4467130''>I</span> <span m=''4467190''>think,</span> <span m=''4467370''>that</span>
  <span m=''4467490''>you''re</span> <span m=''4467630''>getting</span> <span m=''4467880''>to</span>
  <span m=''4468550''>tied</span> <span m=''4468830''>in with</span> <span m=''4468980''>the</span>
  <span m=''4469070''>fact</span> <span m=''4469420''>that</span> <span m=''4470760''>the</span>
  <span m=''4470880''>structuring,</span> <span m=''4472760''>the</span> <span m=''4472950''>recursiveness</span>
  <span m=''4473590''>of</span> <span m=''4473790''>that</span> <span m=''4473990''>structuring</span>
  <span m=''4474560''>there</span> <span m=''4474790''>is</span> <span m=''4474920''>actually</span>
  <span m=''4476330''>in</span> <span m=''4476490''>execution</span> <span m=''4477170''>as</span>
  <span m=''4477290''>opposed</span> <span m=''4477610''>to</span> <span m=''4477680''>just</span>
  <span m=''4478570''>definition</span> <span m=''4479260''>of</span> <span m=''4479360''>the</span>
  <span m=''4479460''>actual</span> <span m=''4480340''>types</span> <span m=''4480670''>themselves?</span>
  </p><p><span m=''4484680''>PROFESSOR: I</span> <span m=''4484890''>think</span>
  <span m=''4485100''>I</span> <span m=''4485200''>understand</span> <span m=''4485650''>the</span>
  <span m=''4485720''>question.</span> <span m=''4486120''>The</span> <span m=''4486360''>point</span>
  <span m=''4486530''>is</span> <span m=''4486620''>that</span> <span m=''4486760''>these</span>
  <span m=''4486950''>types</span> <span m=''4487330''>evolve</span> <span m=''4487880''>and</span>
  <span m=''4487990''>get</span> <span m=''4488160''>more</span> <span m=''4488380''>and</span>
  <span m=''4488450''>more</span> <span m=''4488650''>complex</span> <span m=''4489210''>as</span>
  <span m=''4489310''>the</span> <span m=''4489430''>thing''s</span> <span m=''4489690''>actually</span>
  <span m=''4490060''>running.</span> <span m=''4490400''>Is</span> <span m=''4490500''>that</span>
  <span m=''4490620''>what--</span> </p><p><span m=''4490730''>AUDIENCE: Yes.</span>
  <span m=''4490990''>As</span> <span m=''4491200''>it''s</span> <span m=''4491350''>running.</span>
  </p><p><span m=''4491790''>PROFESSOR: --what</span> <span m=''4491890''>you''re
  saying? Yes, the point is--</span> </p><p><span m=''4492090''>AUDIENCE:</span> <span
  m=''4492320''>As</span> <span m=''4492400''>opposed</span> <span m=''4492690''>to</span>
  <span m=''4492890''>the</span> <span m=''4493080''>basic</span> <span m=''4493420''>definitions.</span>
  </p><p><span m=''4494180''>PROFESSOR: Right.</span> <span m=''4494830''>The</span>
  <span m=''4495080''>type</span> <span m=''4495350''>structure</span> <span m=''4495780''>is</span>
  <span m=''4495870''>sort</span> <span m=''4496070''>of</span> <span m=''4496200''>recursive.</span>
  <span m=''4497210''>It''s</span> <span m=''4497390''>not</span> <span m=''4497580''>that</span>
  <span m=''4497700''>you</span> <span m=''4498760''>can</span> <span m=''4498910''>make</span>
  <span m=''4499120''>this</span> <span m=''4499300''>finite</span> <span m=''4499710''>list</span>
  <span m=''4499990''>of</span> <span m=''4501580''>the</span> <span m=''4501820''>actual</span>
  <span m=''4502770''>things</span> <span m=''4503040''>they</span> <span m=''4503150''>might</span>
  <span m=''4503380''>look</span> <span m=''4503570''>like</span> <span m=''4503770''>before</span>
  <span m=''4504040''>the</span> <span m=''4504130''>system</span> <span m=''4504520''>runs.</span>
  <span m=''4504850''>It''s something</span> <span m=''4505200''>that</span> <span
  m=''4505340''>evolves.</span> <span m=''4506780''>So</span> <span m=''4507000''>if</span>
  <span m=''4507090''>you</span> <span m=''4507170''>want</span> <span m=''4507280''>to</span>
  <span m=''4507660''>specify</span> <span m=''4508240''>that</span> <span m=''4508450''>system,</span>
  <span m=''4508790''>you</span> <span m=''4508910''>have</span> <span m=''4509040''>to</span>
  <span m=''4509130''>do</span> <span m=''4509260''>in</span> <span m=''4509380''>some</span>
  <span m=''4509610''>other</span> <span m=''4509770''>way</span> <span m=''4509910''>than</span>
  <span m=''4510050''>by</span> <span m=''4510200''>this</span> <span m=''4510410''>finite</span>
  <span m=''4510770''>list.</span> <span m=''4511080''>You</span> <span m=''4511150''>have</span>
  <span m=''4511290''>to</span> <span m=''4511830''>do</span> <span m=''4511970''>it</span>
  <span m=''4512060''>by</span> <span m=''4512190''>a recursive</span> <span m=''4512690''>structure.</span>
  </p><p><span m=''4513670''>AUDIENCE: Because</span> <span m=''4513770''>the</span>
  <span m=''4513880''>basic</span> <span m=''4515450''>structure</span> <span m=''4516010''>of</span>
  <span m=''4516100''>the</span> <span m=''4516200''>types</span> <span m=''4516800''>is</span>
  <span m=''4516960''>pretty</span> <span m=''4517170''>clean and</span> <span m=''4517520''>simple.</span>
  </p><p><span m=''4517900''>PROFESSOR: Right.</span> <span m=''4520125''>Yes?</span>
  </p><p><span m=''4521460''>AUDIENCE: I have</span> <span m=''4522180''>a</span>
  <span m=''4522320''>question.</span> <span m=''4522870''>I</span> <span m=''4523030''>understand</span>
  <span m=''4523580''>once</span> <span m=''4523770''>you</span> <span m=''4523880''>have</span>
  <span m=''4524040''>your</span> <span m=''4524640''>data</span> <span m=''4524920''>structure</span>
  <span m=''4525290''>set</span> <span m=''4525510''>up,</span> <span m=''4525980''>how
  it</span> <span m=''4526930''>pulls</span> <span m=''4527260''>off</span> <span
  m=''4527420''>complex</span> <span m=''4527990''>and</span> <span m=''4528120''>passes</span>
  <span m=''4528390''>that</span> <span m=''4528600''>down,</span> <span m=''4529100''>and
  then pulls off</span> <span m=''4529360''>rect,</span> <span m=''4529990''>passes</span>
  <span m=''4530315''>that down.</span> <span m=''4530640''>But</span> <span m=''4530850''>if</span>
  <span m=''4530950''>you''re</span> <span m=''4531030''>just</span> <span m=''4531240''>a
  user</span> <span m=''4531510''>and you</span> <span m=''4531710''>don''t</span>
  <span m=''4531900''>know</span> <span m=''4532080''>anything</span> <span m=''4532380''>about</span>
  <span m=''4532790''>rect or</span> <span m=''4533200''>polar</span> <span m=''4533520''>or</span>
  <span m=''4533650''>whatever,</span> <span m=''4534170''>how</span> <span m=''4534360''>do</span>
  <span m=''4534440''>you</span> <span m=''4534680''>initially</span> <span m=''4535110''>set</span>
  <span m=''4535310''>up</span> <span m=''4535400''>that</span> <span m=''4535610''>data
  structure</span> <span m=''4536460''>so that</span> <span m=''4536800''>everything</span>
  <span m=''4537140''>goes</span> <span m=''4537330''>to</span> <span m=''4537430''>the</span>
  <span m=''4537530''>right</span> <span m=''4537760''>spot?</span> <span m=''4538390''>If
  I</span> <span m=''4538610''>just</span> <span m=''4538880''>have</span> <span m=''4539060''>the</span>
  <span m=''4539870''>equation</span> <span m=''4540420''>over</span> <span m=''4540550''>there</span>
  <span m=''4540680''>on</span> <span m=''4540740''>the</span> <span m=''4540800''>left</span>
  <span m=''4541050''>and</span> <span m=''4541120''>I</span> <span m=''4541210''>just</span>
  <span m=''4541380''>want</span> <span m=''4541470''>to</span> <span m=''4541550''>add,</span>
  <span m=''4541870''>multiply complex numbers--</span> </p><p><span m=''4542500''>PROFESSOR:
  Well that''s</span> <span m=''4542750''>the</span> <span m=''4542830''>wonderful</span>
  <span m=''4543260''>thing.</span> <span m=''4543640''>If</span> <span m=''4543780''>you''re</span>
  <span m=''4543890''>just</span> <span m=''4544160''>a</span> <span m=''4544200''>user</span>
  <span m=''4544490''>you</span> <span m=''4544650''>say</span> <span m=''4544840''>"mul."</span>
  </p><p><span m=''4547730''>AUDIENCE: And</span> <span m=''4547920''>it</span> <span
  m=''4548060''>figures</span> <span m=''4548400''>out</span> <span m=''4548560''>that</span>
  <span m=''4548730''>I</span> <span m=''4548890''>mean</span> <span m=''4549190''>complex</span>
  <span m=''4549660''>numbers?</span> <span m=''4550280''>Or</span> <span m=''4550580''>how
  do I</span> <span m=''4550680''>tell it</span> <span m=''4551010''>that</span> <span
  m=''4551120''>I</span> <span m=''4551230''>want--</span> </p><p><span m=''4551420''>PROFESSOR:
  Well you''re going</span> <span m=''4551490''>to</span> <span m=''4551560''>have
  in</span> <span m=''4551840''>your</span> <span m=''4551950''>hands</span> <span
  m=''4552280''>complex</span> <span m=''4552750''>numbers.</span> <span m=''4553050''>See</span>
  <span m=''4553160''>what</span> <span m=''4553330''>you</span> <span m=''4553430''>would</span>
  <span m=''4553550''>have</span> <span m=''4554310''>at</span> <span m=''4554500''>some</span>
  <span m=''4554770''>level,</span> <span m=''4555140''>as</span> <span m=''4555280''>a</span>
  <span m=''4555360''>real</span> <span m=''4555700''>user,</span> <span m=''4556330''>is</span>
  <span m=''4556490''>a</span> <span m=''4556560''>constructor</span> <span m=''4557140''>for</span>
  <span m=''4557300''>complex</span> <span m=''4557780''>numbers.</span> </p><p><span
  m=''4558370''>AUDIENCE: So then I have to</span> <span m=''4558700''>make</span>
  <span m=''4559000''>complex numbers?</span> </p><p><span m=''4559470''>PROFESSOR:
  So</span> <span m=''4559540''>you</span> <span m=''4559700''>have</span> <span m=''4559860''>to</span>
  <span m=''4559970''>make</span> <span m=''4560230''>them.</span> <span m=''4560350''>What</span>
  <span m=''4560490''>you</span> <span m=''4560590''>would</span> <span m=''4560710''>probably</span>
  <span m=''4561200''>have</span> <span m=''4561390''>as</span> <span m=''4561460''>a</span>
  <span m=''4561620''>user</span> <span m=''4562270''>is</span> <span m=''4562410''>some</span>
  <span m=''4562600''>little</span> <span m=''4562810''>thing</span> <span m=''4563180''>in</span>
  <span m=''4563330''>the</span> <span m=''4563440''>reader</span> <span m=''4563740''>loop,</span>
  <span m=''4564730''>which</span> <span m=''4564910''>would</span> <span m=''4565050''>give</span>
  <span m=''4565190''>you</span> <span m=''4565300''>some</span> <span m=''4566860''>plausible</span>
  <span m=''4567390''>way</span> <span m=''4567530''>to</span> <span m=''4567680''>type</span>
  <span m=''4567940''>in</span> <span m=''4568050''>a</span> <span m=''4568110''>complex</span>
  <span m=''4568580''>number,</span> <span m=''4569195''>in</span> <span m=''4569850''>whatever</span>
  <span m=''4570160''>format</span> <span m=''4570590''>you</span> <span m=''4570710''>like.</span>
  <span m=''4571590''>Or</span> <span m=''4572050''>it</span> <span m=''4572200''>might</span>
  <span m=''4572430''>be</span> <span m=''4572570''>that</span> <span m=''4573170''>you''re</span>
  <span m=''4573300''>never</span> <span m=''4573550''>typing</span> <span m=''4573910''>them</span>
  <span m=''4574060''>in.</span> <span m=''4574360''>Someone''s</span> <span m=''4574750''>just</span>
  <span m=''4574900''>handing</span> <span m=''4575210''>you</span> <span m=''4575330''>a</span>
  <span m=''4575390''>complex</span> <span m=''4575860''>number.</span> </p><p><span
  m=''4576170''>AUDIENCE: OK,</span> <span m=''4576635''>so</span> <span m=''4577100''>if</span>
  <span m=''4577280''>I</span> <span m=''4577470''>had</span> <span m=''4578100''>a</span>
  <span m=''4578210''>complex</span> <span m=''4578660''>number</span> <span m=''4578840''>that</span>
  <span m=''4579160''>had</span> <span m=''4579380''>a</span> <span m=''4579500''>polynomial</span>
  <span m=''4579740''>in it,</span> <span m=''4579880''>I''d</span> <span m=''4580020''>have</span>
  <span m=''4580170''>to</span> <span m=''4580270''>make</span> <span m=''4580450''>my</span>
  <span m=''4580640''>polynomial</span> <span m=''4581100''>and</span> <span m=''4581370''>then
  make</span> <span m=''4581640''>my</span> <span m=''4581800''>complex number.</span>
  </p><p><span m=''4581960''>PROFESSOR: Right</span> <span m=''4582490''>if</span>
  <span m=''4582630''>you</span> <span m=''4582740''>wanted</span> <span m=''4582890''>it</span>
  <span m=''4583030''>constructed</span> <span m=''4583520''>from</span> <span m=''4583660''>scratch.</span>
  <span m=''4584220''>At</span> <span m=''4584350''>some</span> <span m=''4584490''>point</span>
  <span m=''4584680''>you</span> <span m=''4584770''>construct</span> <span m=''4585120''>them</span>
  <span m=''4585230''>from</span> <span m=''4585350''>scratch.</span> <span m=''4585710''>But</span>
  <span m=''4585810''>what</span> <span m=''4585950''>you</span> <span m=''4586040''>don''t</span>
  <span m=''4586290''>have</span> <span m=''4586450''>to</span> <span m=''4586550''>know
  of</span> <span m=''4586760''>that</span> <span m=''4587330''>is</span> <span m=''4587470''>when</span>
  <span m=''4587580''>you</span> <span m=''4587730''>have</span> <span m=''4587880''>the</span>
  <span m=''4588010''>object</span> <span m=''4588390''>you</span> <span m=''4588460''>can</span>
  <span m=''4588590''>just</span> <span m=''4588750''>say</span> <span m=''4588860''>"mul."</span>
  <span m=''4589560''>And it''ll</span> <span m=''4589710''>multiply.</span> <span
  m=''4592345''>Yeah?</span> </p><p><span m=''4593279''>AUDIENCE: I think the</span>
  <span m=''4593750''>question</span> <span m=''4594190''>that</span> <span m=''4594360''>was</span>
  <span m=''4594550''>being</span> <span m=''4594760''>posed</span> <span m=''4595150''>here</span>
  <span m=''4595440''>is,</span> <span m=''4596450''>say</span> <span m=''4596740''>if
  I</span> <span m=''4596840''>want</span> <span m=''4597010''>to</span> <span m=''4597160''>change</span>
  <span m=''4598100''>my</span> <span m=''4598460''>presentation</span> <span m=''4599180''>of</span>
  <span m=''4599340''>complexes,</span> <span m=''4600070''>or</span> <span m=''4600220''>some</span>
  <span m=''4600450''>operation of</span> <span m=''4601020''>complex,</span> <span
  m=''4601570''>how</span> <span m=''4601730''>much</span> <span m=''4602170''>real</span>
  <span m=''4602540''>code</span> <span m=''4603940''>I will</span> <span m=''4604180''>have</span>
  <span m=''4604470''>to</span> <span m=''4606330''>gets</span> <span m=''4606550''>around</span>
  <span m=''4607000''>with,</span> <span m=''4607210''>or</span> <span m=''4607660''>change</span>
  <span m=''4608920''>to</span> <span m=''4609090''>change</span> <span m=''4609400''>it</span>
  <span m=''4609650''>in one</span> <span m=''4610070''>specific</span> <span m=''4610260''>operation?</span>
  </p><p><span m=''4612270''>PROFESSOR: [UNINTELLIGIBLE]</span> <span m=''4612650''>what</span>
  <span m=''4612800''>you</span> <span m=''4612910''>have</span> <span m=''4613020''>to</span>
  <span m=''4613140''>change.</span> <span m=''4613490''>And</span> <span m=''4613560''>the</span>
  <span m=''4613630''>point</span> <span m=''4613880''>is</span> <span m=''4613980''>that</span>
  <span m=''4614120''>you</span> <span m=''4614220''>only</span> <span m=''4614430''>have</span>
  <span m=''4614590''>to</span> <span m=''4614690''>change</span> <span m=''4615330''>what</span>
  <span m=''4615590''>you''re</span> <span m=''4615700''>changing.</span> <span m=''4616070''>See</span>
  <span m=''4616220''>if</span> <span m=''4616290''>Martha</span> <span m=''4616640''>decides</span>
  <span m=''4617280''>that</span> <span m=''4619010''>she</span> <span m=''4619200''>would</span>
  <span m=''4619320''>rather--</span> <span m=''4620320''>let''s</span> <span m=''4620500''>see</span>
  <span m=''4620580''>something</span> <span m=''4620830''>silly--</span> <span m=''4621440''>like</span>
  <span m=''4621650''>change</span> <span m=''4621950''>the</span> <span m=''4622050''>order</span>
  <span m=''4622380''>in</span> <span m=''4622460''>the</span> <span m=''4622540''>pair.</span>
  <span m=''4624040''>Like</span> <span m=''4626120''>angle</span> <span m=''4626550''>and</span>
  <span m=''4627450''>magnitude</span> <span m=''4627770''>in</span> <span m=''4628090''>the</span>
  <span m=''4628230''>other</span> <span m=''4628380''>order,</span> <span m=''4629360''>she</span>
  <span m=''4629530''>just</span> <span m=''4629700''>makes</span> <span m=''4629970''>that</span>
  <span m=''4630050''>change</span> <span m=''4630350''>locally.</span> <span m=''4630970''>And</span>
  <span m=''4631120''>the</span> <span m=''4631180''>whole</span> <span m=''4631430''>thing</span>
  <span m=''4631630''>will</span> <span m=''4631740''>propagate</span> <span m=''4632210''>through</span>
  <span m=''4632320''>the</span> <span m=''4632410''>system</span> <span m=''4632750''>in</span>
  <span m=''4632810''>the</span> <span m=''4632880''>right</span> <span m=''4633080''>way.</span>
  <span m=''4634790''>Or</span> <span m=''4635030''>if</span> <span m=''4635120''>suddenly</span>
  <span m=''4636010''>you</span> <span m=''4636200''>said,</span> <span m=''4636510''>gee,</span>
  <span m=''4636690''>I</span> <span m=''4636760''>have</span> <span m=''4636900''>another</span>
  <span m=''4637290''>representation</span> <span m=''4638040''>for</span> <span m=''4638180''>rationals.</span>
  <span m=''4639700''>And</span> <span m=''4639830''>I''m</span> <span m=''4639920''>going</span>
  <span m=''4639980''>to</span> <span m=''4640050''>stick</span> <span m=''4640300''>it</span>
  <span m=''4640370''>here,</span> <span m=''4641900''>by</span> <span m=''4642030''>filing</span>
  <span m=''4642570''>those</span> <span m=''4642740''>operations</span> <span m=''4643270''>in</span>
  <span m=''4643350''>the</span> <span m=''4643430''>table.</span> <span m=''4644820''>Then</span>
  <span m=''4645010''>suddenly</span> <span m=''4645360''>all</span> <span m=''4645500''>of</span>
  <span m=''4645640''>these</span> <span m=''4645820''>polynomials</span> <span m=''4646520''>whose</span>
  <span m=''4646660''>coefficients</span> <span m=''4647220''>are</span> <span m=''4647330''>coefficients</span>
  <span m=''4647900''>of</span> <span m=''4647990''>coefficients,</span> <span m=''4648560''>or</span>
  <span m=''4648600''>whatever,</span> <span m=''4649240''>also</span> <span m=''4649630''>can</span>
  <span m=''4650280''>automatically</span> <span m=''4650840''>have</span> <span m=''4651010''>available</span>
  <span m=''4651420''>that</span> <span m=''4651570''>representation.</span> <span
  m=''4652970''>That''s</span> <span m=''4653230''>the</span> <span m=''4653310''>power</span>
  <span m=''4653670''>of</span> <span m=''4653750''>this</span> <span m=''4653930''>particular</span>
  <span m=''4654280''>one.</span> </p><p><span m=''4655952''>AUDIENCE: I''m not sure</span>
  <span m=''4656436''>if I can even</span> <span m=''4656920''>pose an</span> <span
  m=''4657280''>intelligent</span> <span m=''4657625''>sounding</span> <span m=''4658220''>question.</span>
  <span m=''4658700''>But</span> <span m=''4660060''>somehow</span> <span m=''4660570''>this</span>
  <span m=''4660770''>whole</span> <span m=''4660960''>thing</span> <span m=''4661220''>went</span>
  <span m=''4661490''>really</span> <span m=''4661730''>nicely</span> <span m=''4662530''>to</span>
  <span m=''4662660''>this</span> <span m=''4662920''>beautiful</span> <span m=''4663350''>finish</span>
  <span m=''4663770''>where</span> <span m=''4664100''>all</span> <span m=''4664290''>the</span>
  <span m=''4664390''>things</span> <span m=''4664680''>seemed</span> <span m=''4664910''>to</span>
  <span m=''4664990''>fall</span> <span m=''4665270''>into</span> <span m=''4665370''>place.</span>
  <span m=''4667280''>Sort of</span> <span m=''4667680''>seemed a little</span> <span
  m=''4668010''>contrived.</span> <span m=''4670930''>That''s</span> <span m=''4671200''>all</span>
  <span m=''4671340''>for</span> <span m=''4671430''>the</span> <span m=''4671490''>sake,</span>
  <span m=''4671750''>I''m</span> <span m=''4671850''>sure,</span> <span m=''4672150''>of</span>
  <span m=''4672290''>teaching.</span> <span m=''4672670''>I</span> <span m=''4672880''>doubt</span>
  <span m=''4673220''>that</span> <span m=''4673460''>the</span> <span m=''4673550''>guys</span>
  <span m=''4673860''>who</span> <span m=''4673950''>first</span> <span m=''4674320''>did</span>
  <span m=''4674560''>this--</span> <span m=''4675100''>and I</span> <span m=''4675370''>could
  be wrong--</span> <span m=''4676510''>figured</span> <span m=''4676850''>it</span>
  <span m=''4676910''>all</span> <span m=''4677190''>out</span> <span m=''4677420''>so</span>
  <span m=''4677550''>that</span> <span m=''4677680''>when</span> <span m=''4677820''>they</span>
  <span m=''4678280''>just</span> <span m=''4678580''>all</span> <span m=''4678820''>put</span>
  <span m=''4678970''>it</span> <span m=''4679050''>all</span> <span m=''4679200''>together,</span>
  <span m=''4679850''>you</span> <span m=''4679960''>could</span> <span m=''4680090''>all
  of</span> <span m=''4680440''>the sudden,</span> <span m=''4680765''>blam,</span>
  <span m=''4681090''>do</span> <span m=''4681380''>any</span> <span m=''4681560''>kind</span>
  <span m=''4681740''>of</span> <span m=''4682410''>arithmetic</span> <span m=''4682940''>on</span>
  <span m=''4683100''>any</span> <span m=''4683270''>kind</span> <span m=''4683380''>of</span>
  <span m=''4683510''>object.</span> <span m=''4684860''>It</span> <span m=''4684980''>seems</span>
  <span m=''4685210''>like</span> <span m=''4685460''>maybe</span> <span m=''4685810''>they</span>
  <span m=''4685900''>had</span> <span m=''4686040''>to</span> <span m=''4686100''>play</span>
  <span m=''4686380''>with</span> <span m=''4686540''>it</span> <span m=''4686670''>for</span>
  <span m=''4686730''>a</span> <span m=''4686800''>while</span> <span m=''4687930''>and</span>
  <span m=''4688090''>had</span> <span m=''4688290''>to</span> <span m=''4689260''>bash
  it and</span> <span m=''4689890''>rework</span> <span m=''4690430''>it.</span> </p><p><span
  m=''4691800''>And</span> <span m=''4692510''>it</span> <span m=''4692580''>seems</span>
  <span m=''4692760''>like</span> <span m=''4692890''>that''s</span> <span m=''4693110''>the</span>
  <span m=''4693190''>kind</span> <span m=''4693320''>of</span> <span m=''4693450''>problem</span>
  <span m=''4693750''>we''re</span> <span m=''4693910''>really</span> <span m=''4694120''>faced</span>
  <span m=''4694480''>with</span> <span m=''4694630''>we</span> <span m=''4694830''>start</span>
  <span m=''4695150''>trying</span> <span m=''4695380''>to</span> <span m=''4695440''>design</span>
  <span m=''4695790''>a</span> <span m=''4695820''>really</span> <span m=''4696010''>complex</span>
  <span m=''4696540''>system,</span> <span m=''4697350''>is</span> <span m=''4697520''>having</span>
  <span m=''4697860''>lots</span> <span m=''4698230''>of</span> <span m=''4698330''>different</span>
  <span m=''4698640''>kinds</span> <span m=''4698840''>of</span> <span m=''4698920''>parts</span>
  <span m=''4699300''>and</span> <span m=''4699390''>not</span> <span m=''4699570''>even</span>
  <span m=''4699780''>knowing</span> <span m=''4701160''>what</span> <span m=''4701350''>kinds</span>
  <span m=''4701590''>of</span> <span m=''4701700''>operations</span> <span m=''4702340''>we''re</span>
  <span m=''4702450''>going</span> <span m=''4702520''>to</span> <span m=''4702580''>want</span>
  <span m=''4702730''>to</span> <span m=''4703700''>do</span> <span m=''4703960''>on</span>
  <span m=''4704090''>those</span> <span m=''4704280''>parts.</span> <span m=''4704620''>How</span>
  <span m=''4704730''>to</span> <span m=''4704850''>organize</span> <span m=''4705300''>the</span>
  <span m=''4705420''>operations</span> <span m=''4706080''>in</span> <span m=''4706190''>this</span>
  <span m=''4706250''>nice</span> <span m=''4706430''>way</span> <span m=''4706650''>so</span>
  <span m=''4706840''>that</span> <span m=''4707510''>no</span> <span m=''4707580''>matter</span>
  <span m=''4707810''>what</span> <span m=''4708030''>you</span> <span m=''4708190''>do,</span>
  <span m=''4708360''>when</span> <span m=''4708470''>you</span> <span m=''4708550''>start</span>
  <span m=''4708880''>putting them</span> <span m=''4709170''>together</span> <span
  m=''4709630''>everything</span> <span m=''4709930''>starts</span> <span m=''4710210''>falling</span>
  <span m=''4710540''>out</span> <span m=''4710810''>for free.</span> </p><p><span
  m=''4711700''>PROFESSOR: OK,</span> <span m=''4711800''>well</span> <span m=''4712000''>that''s</span>
  <span m=''4712700''>certainly</span> <span m=''4713050''>a</span> <span m=''4713090''>very</span>
  <span m=''4713400''>intelligent</span> <span m=''4713820''>question.</span> <span
  m=''4717020''>One</span> <span m=''4717300''>part</span> <span m=''4717550''>is</span>
  <span m=''4717780''>this</span> <span m=''4718060''>is</span> <span m=''4718170''>a</span>
  <span m=''4718240''>very</span> <span m=''4718510''>good</span> <span m=''4718670''>methodology</span>
  <span m=''4719930''>that</span> <span m=''4720120''>people</span> <span m=''4720560''>have</span>
  <span m=''4720690''>discovered</span> <span m=''4721470''>a</span> <span m=''4721570''>lot</span>
  <span m=''4722580''>coming</span> <span m=''4722850''>from</span> <span m=''4723010''>symbolic</span>
  <span m=''4723520''>algebra.</span> <span m=''4724590''>Because there</span> <span
  m=''4724670''>are a</span> <span m=''4724770''>lot</span> <span m=''4724870''>of</span>
  <span m=''4724970''>complications.</span> <span m=''4727590''>To</span> <span m=''4727780''>allow</span>
  <span m=''4728080''>you</span> <span m=''4729070''>to</span> <span m=''4729140''>implement</span>
  <span m=''4729560''>these</span> <span m=''4729740''>things</span> <span m=''4729950''>before</span>
  <span m=''4730210''>you</span> <span m=''4730320''>decide</span> <span m=''4730710''>what</span>
  <span m=''4730840''>you</span> <span m=''4730980''>want</span> <span m=''4731150''>all</span>
  <span m=''4731280''>the</span> <span m=''4731400''>operations</span> <span m=''4732040''>to</span>
  <span m=''4732130''>be,</span> <span m=''4732270''>and</span> <span m=''4732360''>all</span>
  <span m=''4732510''>of</span> <span m=''4732600''>that.</span> <span m=''4733310''>So</span>
  <span m=''4733490''>in</span> <span m=''4733570''>some</span> <span m=''4733770''>sense</span>
  <span m=''4734420''>it''s</span> <span m=''4734610''>an</span> <span m=''4734700''>answer</span>
  <span m=''4735060''>that</span> <span m=''4735240''>people</span> <span m=''4735500''>have</span>
  <span m=''4735580''>discovered</span> <span m=''4736560''>by</span> <span m=''4736690''>wading</span>
  <span m=''4737050''>through</span> <span m=''4737230''>this</span> <span m=''4737410''>stuff.</span>
  <span m=''4738560''>In</span> <span m=''4738690''>another</span> <span m=''4738990''>sense,</span>
  <span m=''4739220''>it</span> <span m=''4739290''>is</span> <span m=''4739420''>a</span>
  <span m=''4739530''>very</span> <span m=''4739980''>contrived</span> <span m=''4740440''>example.</span>
  </p><p><span m=''4742160''>AUDIENCE: It</span> <span m=''4742360''>seems</span>
  <span m=''4742620''>like</span> <span m=''4744670''>to</span> <span m=''4744840''>be</span>
  <span m=''4745000''>able</span> <span m=''4745130''>to</span> <span m=''4745210''>do</span>
  <span m=''4745400''>this</span> <span m=''4745620''>you</span> <span m=''4745710''>do</span>
  <span m=''4745930''>have</span> <span m=''4746090''>to</span> <span m=''4746240''>wade</span>
  <span m=''4746610''>through</span> <span m=''4746850''>it</span> <span m=''4747010''>for
  a</span> <span m=''4747150''>certain</span> <span m=''4747390''>amount</span> <span
  m=''4747610''>of</span> <span m=''4747680''>time</span> <span m=''4747960''>before</span>
  <span m=''4748170''>you</span> <span m=''4748240''>can</span> <span m=''4748320''>become</span>
  <span m=''4748610''>good at it.</span> </p><p><span m=''4749010''>PROFESSOR: Let</span>
  <span m=''4749190''>me</span> <span m=''4750250''>show</span> <span m=''4750390''>you</span>
  <span m=''4750490''>how</span> <span m=''4750600''>terribly</span> <span m=''4751140''>contrived</span>
  <span m=''4751395''>this</span> <span m=''4751650''>is.</span> <span m=''4752220''>So</span>
  <span m=''4752370''>you</span> <span m=''4752500''>can</span> <span m=''4752640''>write</span>
  <span m=''4752870''>all</span> <span m=''4753020''>these</span> <span m=''4753390''>wonderful</span>
  <span m=''4753840''>things.</span> <span m=''4754130''>But</span> <span m=''4754640''>the</span>
  <span m=''4754910''>system</span> <span m=''4755400''>that</span> <span m=''4755530''>I</span>
  <span m=''4755620''>wrote</span> <span m=''4755880''>here,</span> <span m=''4756980''>and</span>
  <span m=''4757140''>if</span> <span m=''4757240''>we</span> <span m=''4757310''>had</span>
  <span m=''4757420''>another</span> <span m=''4757600''>half</span> <span m=''4757840''>an</span>
  <span m=''4757940''>hour</span> <span m=''4758180''>to</span> <span m=''4758230''>give</span>
  <span m=''4758380''>this</span> <span m=''4758570''>lecture</span> <span m=''4759330''>I
  would have</span> <span m=''4759570''>given</span> <span m=''4759820''>this</span>
  <span m=''4759960''>part</span> <span m=''4760200''>of</span> <span m=''4760320''>it,</span>
  <span m=''4760860''>which</span> <span m=''4761120''>says,</span> <span m=''4761270''>notice</span>
  <span m=''4761790''>that</span> <span m=''4762090''>it</span> <span m=''4762220''>breaks</span>
  <span m=''4762570''>down</span> <span m=''4763260''>if</span> <span m=''4763470''>I</span>
  <span m=''4763560''>tell</span> <span m=''4763810''>it</span> <span m=''4763900''>to</span>
  <span m=''4764000''>do</span> <span m=''4764120''>something</span> <span m=''4764570''>as</span>
  <span m=''4764750''>foolish</span> <span m=''4765160''>as</span> <span m=''4766580''>add</span>
  <span m=''4766780''>3</span> <span m=''4767370''>plus</span> <span m=''4768480''>7/2.</span>
  <span m=''4770880''>Because</span> <span m=''4771300''>what</span> <span m=''4771440''>will</span>
  <span m=''4771570''>happen</span> <span m=''4772050''>is</span> <span m=''4772160''>you''ll</span>
  <span m=''4772270''>get</span> <span m=''4772460''>to</span> <span m=''4772560''>operate-2,</span>
  <span m=''4773710''>and</span> <span m=''4773980''>operate-2</span> <span m=''4774580''>will</span>
  <span m=''4774680''>say,</span> <span m=''4774840''>oh</span> <span m=''4774940''>this</span>
  <span m=''4775140''>is</span> <span m=''4775260''>type</span> <span m=''4775540''>number,</span>
  <span m=''4776180''>and</span> <span m=''4776380''>that''s</span> <span m=''4776570''>type</span>
  <span m=''4776820''>rational.</span> <span m=''4777560''>I</span> <span m=''4777690''>don''t</span>
  <span m=''4777810''>know</span> <span m=''4777940''>how</span> <span m=''4778060''>to</span>
  <span m=''4778180''>add</span> <span m=''4778450''>them.</span> </p><p><span m=''4781530''>So</span>
  <span m=''4781690''>you''d</span> <span m=''4781880''>like</span> <span m=''4782080''>the</span>
  <span m=''4782160''>system</span> <span m=''4782480''>at</span> <span m=''4782550''>least</span>
  <span m=''4782880''>to</span> <span m=''4782970''>be</span> <span m=''4783150''>able</span>
  <span m=''4783300''>to</span> <span m=''4783370''>say</span> <span m=''4783600''>something</span>
  <span m=''4784000''>like,</span> <span m=''4785980''>gee,</span> <span m=''4786320''>before</span>
  <span m=''4786610''>you</span> <span m=''4786730''>do</span> <span m=''4786920''>that</span>
  <span m=''4788660''>change</span> <span m=''4788910''>that</span> <span m=''4789080''>to</span>
  <span m=''4789180''>3/1.</span> <span m=''4790480''>Turn</span> <span m=''4790700''>it
  into</span> <span m=''4790960''>a rational</span> <span m=''4791420''>number,</span>
  <span m=''4791670''>hand</span> <span m=''4791900''>that</span> <span m=''4792060''>to</span>
  <span m=''4792150''>the</span> <span m=''4792250''>rational</span> <span m=''4792680''>package.</span>
  <span m=''4795510''>That''s</span> <span m=''4795750''>the</span> <span m=''4795830''>thing</span>
  <span m=''4795990''>I</span> <span m=''4796060''>didn''t</span> <span m=''4796320''>talk</span>
  <span m=''4796600''>about</span> <span m=''4796870''>in</span> <span m=''4797070''>this</span>
  <span m=''4798570''>lecture.</span> <span m=''4798860''>It''s</span> <span m=''4798960''>a</span>
  <span m=''4799010''>little</span> <span m=''4799210''>bit</span> <span m=''4799350''>in</span>
  <span m=''4799450''>the</span> <span m=''4799560''>book,</span> <span m=''4799820''>which</span>
  <span m=''4799970''>talks</span> <span m=''4800190''>about</span> <span m=''4800310''>the</span>
  <span m=''4800430''>problem</span> <span m=''4800880''>of</span> <span m=''4800950''>what''s</span>
  <span m=''4801130''>called</span> <span m=''4801320''>coercion.</span> <span m=''4803390''>Where</span>
  <span m=''4803570''>you</span> <span m=''4804680''>wanted--</span> <span m=''4805310''>see,</span>
  <span m=''4805490''>having</span> <span m=''4806140''>so</span> <span m=''4806470''>carefully</span>
  <span m=''4806970''>set</span> <span m=''4807170''>up</span> <span m=''4807310''>all</span>
  <span m=''4807480''>of</span> <span m=''4807560''>these</span> <span m=''4807760''>types</span>
  <span m=''4808120''>as</span> <span m=''4808280''>distinct</span> <span m=''4808700''>objects,</span>
  <span m=''4809220''>a</span> <span m=''4809280''>lot</span> <span m=''4809560''>of</span>
  <span m=''4809650''>times</span> <span m=''4810650''>you</span> <span m=''4810800''>want</span>
  <span m=''4810950''>to</span> <span m=''4811030''>also</span> <span m=''4811390''>put</span>
  <span m=''4811580''>in</span> <span m=''4811720''>knowledge</span> <span m=''4812360''>about</span>
  <span m=''4812730''>how</span> <span m=''4812830''>to</span> <span m=''4812930''>view</span>
  <span m=''4815400''>an</span> <span m=''4815480''>ordinary</span> <span m=''4815930''>number</span>
  <span m=''4816650''>as</span> <span m=''4816950''>a</span> <span m=''4817070''>kind</span>
  <span m=''4817380''>of</span> <span m=''4817480''>rational.</span> <span m=''4819110''>Or
  view</span> <span m=''4819510''>an</span> <span m=''4819580''>ordinary</span> <span
  m=''4819990''>number</span> <span m=''4820240''>as</span> <span m=''4820320''>a</span>
  <span m=''4820400''>kind</span> <span m=''4820560''>of</span> <span m=''4820730''>complex.</span>
  <span m=''4821620''>That''s</span> <span m=''4822080''>where</span> <span m=''4822820''>the</span>
  <span m=''4822960''>complexity</span> <span m=''4823480''>in</span> <span m=''4823580''>the</span>
  <span m=''4823650''>system</span> <span m=''4824020''>really</span> <span m=''4824270''>starts</span>
  <span m=''4824580''>happening,</span> <span m=''4825790''>where you</span> <span
  m=''4825990''>talk</span> <span m=''4826230''>about,</span> <span m=''4826750''>see</span>
  <span m=''4826910''>where</span> <span m=''4827110''>do I</span> <span m=''4827180''>put</span>
  <span m=''4827380''>that</span> <span m=''4827620''>knowledge?</span> <span m=''4828420''>Is</span>
  <span m=''4828590''>it</span> <span m=''4828690''>rational</span> <span m=''4829200''>to</span>
  <span m=''4829370''>know</span> <span m=''4829550''>that</span> <span m=''4829690''>ordinary</span>
  <span m=''4830140''>numbers</span> <span m=''4830460''>might</span> <span m=''4830680''>be</span>
  <span m=''4830810''>pieces</span> <span m=''4831170''>of</span> <span m=''4831350''>[UNINTELLIGIBLE]</span>
  <span m=''4831730''>of</span> <span m=''4831840''>them?</span> </p><p><span m=''4833130''>Or</span>
  <span m=''4833550''>they''re</span> <span m=''4833830''>terrible,</span> <span m=''4834270''>terrible</span>
  <span m=''4834710''>examples,</span> <span m=''4835780''>like</span> <span m=''4838170''>if</span>
  <span m=''4838390''>I</span> <span m=''4838440''>might</span> <span m=''4838660''>want</span>
  <span m=''4838790''>to</span> <span m=''4838920''>add</span> <span m=''4840560''>a</span>
  <span m=''4842850''>complex</span> <span m=''4843430''>number</span> <span m=''4845750''>to</span>
  <span m=''4846510''>a</span> <span m=''4846650''>rational</span> <span m=''4847130''>number.</span>
  <span m=''4850080''>Bad</span> <span m=''4850370''>example.</span> <span m=''4850760''>5/7.</span>
  <span m=''4853860''>Then</span> <span m=''4854440''>somebody''s</span> <span m=''4854860''>got</span>
  <span m=''4854970''>to</span> <span m=''4855070''>know</span> <span m=''4855320''>that</span>
  <span m=''4856040''>I</span> <span m=''4856200''>have</span> <span m=''4856390''>to</span>
  <span m=''4856510''>convert</span> <span m=''4856990''>these</span> <span m=''4857300''>to</span>
  <span m=''4857500''>another</span> <span m=''4857830''>type,</span> <span m=''4858200''>which</span>
  <span m=''4858390''>is</span> <span m=''4858540''>complex</span> <span m=''4859020''>numbers</span>
  <span m=''4859360''>whose</span> <span m=''4859520''>parts</span> <span m=''4859790''>might</span>
  <span m=''4859980''>be</span> <span m=''4860100''>rationals.</span> <span m=''4861540''>And</span>
  <span m=''4861680''>who</span> <span m=''4861800''>worries</span> <span m=''4862140''>about</span>
  <span m=''4862450''>that?</span> <span m=''4862680''>Does</span> <span m=''4862800''>complex</span>
  <span m=''4863250''>worry</span> <span m=''4863460''>about</span> <span m=''4863730''>that?</span>
  <span m=''4863950''>Does</span> <span m=''4864040''>rational</span> <span m=''4864460''>worry</span>
  <span m=''4864640''>about</span> <span m=''4864870''>that?</span> <span m=''4865030''>Does</span>
  <span m=''4865200''>plus</span> <span m=''4865430''>worry</span> <span m=''4865670''>about
  that?</span> </p><p><span m=''4866900''>That''s</span> <span m=''4867200''>where</span>
  <span m=''4867300''>the</span> <span m=''4867420''>real</span> <span m=''4867590''>complexity</span>
  <span m=''4868120''>comes</span> <span m=''4868380''>in.</span> <span m=''4868520''>And</span>
  <span m=''4868620''>that''s</span> <span m=''4868880''>where</span> <span m=''4870200''>it''s</span>
  <span m=''4870370''>pretty</span> <span m=''4870570''>well</span> <span m=''4870720''>sorted</span>
  <span m=''4871110''>out.</span> <span m=''4871380''>And</span> <span m=''4871510''>a</span>
  <span m=''4871560''>lot of,</span> <span m=''4872270''>in</span> <span m=''4872390''>fact,</span>
  <span m=''4872750''>all</span> <span m=''4872880''>of</span> <span m=''4872960''>this</span>
  <span m=''4873130''>message</span> <span m=''4873460''>passing</span> <span m=''4873790''>stuff</span>
  <span m=''4874660''>was</span> <span m=''4874810''>motivated</span> <span m=''4875380''>by</span>
  <span m=''4875520''>problems</span> <span m=''4876030''>like</span> <span m=''4876250''>this.</span>
  <span m=''4878460''>And</span> <span m=''4878680''>when</span> <span m=''4878800''>you</span>
  <span m=''4878940''>really</span> <span m=''4879210''>push</span> <span m=''4879510''>it,</span>
  <span m=''4880340''>people</span> <span m=''4880650''>are--</span> <span m=''4880790''>somehow</span>
  <span m=''4881410''>the</span> <span m=''4881630''>algebraic</span> <span m=''4882150''>manipulation</span>
  <span m=''4882740''>problem</span> <span m=''4883130''>seems</span> <span m=''4883420''>to</span>
  <span m=''4883520''>be</span> <span m=''4883990''>so</span> <span m=''4884240''>complex</span>
  <span m=''4885120''>that</span> <span m=''4885330''>the</span> <span m=''4885430''>people</span>
  <span m=''4885710''>who</span> <span m=''4885800''>are</span> <span m=''4885880''>always</span>
  <span m=''4886210''>at</span> <span m=''4886280''>the</span> <span m=''4886410''>edge</span>
  <span m=''4886590''>of</span> <span m=''4886690''>it</span> <span m=''4886760''>are</span>
  <span m=''4886850''>exactly</span> <span m=''4887320''>in</span> <span m=''4887410''>the</span>
  <span m=''4887450''>state</span> <span m=''4887700''>you</span> <span m=''4887810''>said.</span>
  <span m=''4888050''>They''re</span> <span m=''4888170''>wading</span> <span m=''4888520''>through</span>
  <span m=''4888630''>this</span> <span m=''4888860''>thing,</span> <span m=''4889050''>mucking</span>
  <span m=''4889380''>around,</span> <span m=''4889690''>seeing</span> <span m=''4889940''>what</span>
  <span m=''4890100''>they use,</span> <span m=''4890410''>trying</span> <span m=''4890590''>to</span>
  <span m=''4890770''>distill</span> <span m=''4891100''>stuff.</span> </p><p><span
  m=''4893470''>AUDIENCE: I just</span> <span m=''4893970''>want to</span> <span m=''4894470''>come</span>
  <span m=''4894780''>back</span> <span m=''4894990''>to</span> <span m=''4895100''>this</span>
  <span m=''4895540''>issue</span> <span m=''4895910''>of</span> <span m=''4896030''>complexity</span>
  <span m=''4896980''>once</span> <span m=''4897400''>more.</span> <span m=''4899250''>It</span>
  <span m=''4899450''>certainly</span> <span m=''4899810''>seems</span> <span m=''4900130''>to</span>
  <span m=''4900230''>be</span> <span m=''4900340''>true</span> <span m=''4901670''>that</span>
  <span m=''4903040''>you</span> <span m=''4903720''>have</span> <span m=''4904020''>a</span>
  <span m=''4904080''>great</span> <span m=''4904300''>deal</span> <span m=''4904470''>of</span>
  <span m=''4904550''>flexibility</span> <span m=''4905980''>in</span> <span m=''4906100''>altering</span>
  <span m=''4906800''>the</span> <span m=''4906930''>lower</span> <span m=''4907240''>level</span>
  <span m=''4907510''>kinds</span> <span m=''4907830''>of</span> <span m=''4907920''>things.</span>
  <span m=''4909580''>But</span> <span m=''4911280''>it</span> <span m=''4911480''>is</span>
  <span m=''4911710''>true</span> <span m=''4912020''>that</span> <span m=''4912640''>you</span>
  <span m=''4912820''>are,</span> <span m=''4912970''>in</span> <span m=''4913030''>a</span>
  <span m=''4913070''>sense,</span> <span m=''4913410''>freezing</span> <span m=''4913970''>higher</span>
  <span m=''4914320''>level</span> <span m=''4914620''>operations.</span> <span m=''4915450''>Or</span>
  <span m=''4915640''>at</span> <span m=''4915810''>least</span> <span m=''4915980''>if</span>
  <span m=''4916080''>you</span> <span m=''4916180''>change</span> <span m=''4916570''>them</span>
  <span m=''4917140''>you</span> <span m=''4917250''>don''t</span> <span m=''4917430''>know</span>
  <span m=''4917600''>where</span> <span m=''4918140''>all</span> <span m=''4918320''>of</span>
  <span m=''4918510''>the</span> <span m=''4918590''>changes</span> <span m=''4919820''>are</span>
  <span m=''4919980''>going</span> <span m=''4920260''>to</span> <span m=''4920410''>show</span>
  <span m=''4920710''>up,</span> <span m=''4921300''>or</span> <span m=''4921420''>how</span>
  <span m=''4921690''>they</span> <span m=''4921840''>are.</span> </p><p><span m=''4922060''>PROFESSOR:
  OK,</span> <span m=''4922330''>that''s</span> <span m=''4922670''>an</span> <span
  m=''4922780''>extremely</span> <span m=''4923520''>good</span> <span m=''4923710''>question.</span>
  <span m=''4924840''>What</span> <span m=''4924960''>I</span> <span m=''4925090''>have</span>
  <span m=''4925220''>to</span> <span m=''4925350''>do</span> <span m=''4925590''>is,</span>
  <span m=''4928720''>if</span> <span m=''4928900''>I</span> <span m=''4928990''>decide</span>
  <span m=''4929370''>there''s</span> <span m=''4929530''>a</span> <span m=''4929600''>new</span>
  <span m=''4929760''>general</span> <span m=''4930130''>operation</span> <span m=''4931500''>called</span>
  <span m=''4932200''>equality</span> <span m=''4932790''>test,</span> <span m=''4934980''>then</span>
  <span m=''4935200''>all</span> <span m=''4935410''>of</span> <span m=''4935500''>these</span>
  <span m=''4935700''>people</span> <span m=''4936300''>have</span> <span m=''4936550''>to</span>
  <span m=''4936670''>decide</span> <span m=''4938270''>whether</span> <span m=''4938640''>or</span>
  <span m=''4938700''>not</span> <span m=''4938990''>they</span> <span m=''4939110''>would</span>
  <span m=''4939260''>like</span> <span m=''4939480''>to</span> <span m=''4939620''>have</span>
  <span m=''4939780''>an equality</span> <span m=''4940290''>test</span> <span m=''4941540''>by</span>
  <span m=''4941660''>looking</span> <span m=''4941950''>in</span> <span m=''4942030''>the</span>
  <span m=''4942120''>table.</span> <span m=''4944650''>There''re</span> <span m=''4944880''>ways
  to</span> <span m=''4945280''>decentralize</span> <span m=''4946020''>it</span>
  <span m=''4946100''>even</span> <span m=''4946470''>more.</span> <span m=''4947870''>That''s</span>
  <span m=''4948160''>what</span> <span m=''4948290''>I</span> <span m=''4948380''>sort</span>
  <span m=''4948510''>of</span> <span m=''4948660''>hinted</span> <span m=''4949000''>at</span>
  <span m=''4949820''>last</span> <span m=''4950060''>time, where I</span> <span m=''4950390''>said</span>
  <span m=''4951160''>you</span> <span m=''4951430''>could</span> <span m=''4951600''>not</span>
  <span m=''4951800''>only</span> <span m=''4951970''>have</span> <span m=''4952160''>this</span>
  <span m=''4952310''>type</span> <span m=''4952570''>as</span> <span m=''4952670''>a</span>
  <span m=''4952720''>symbol,</span> <span m=''4953420''>but</span> <span m=''4953610''>you</span>
  <span m=''4953730''>actually</span> <span m=''4954240''>might</span> <span m=''4954490''>store</span>
  <span m=''4954900''>in</span> <span m=''4955120''>each</span> <span m=''4955790''>object</span>
  <span m=''4957060''>the</span> <span m=''4957180''>operations</span> <span m=''4957850''>that</span>
  <span m=''4957970''>it</span> <span m=''4958090''>knows</span> <span m=''4958350''>of</span>
  <span m=''4958410''>that.</span> </p><p><span m=''4960450''>So</span> <span m=''4960600''>you</span>
  <span m=''4960760''>might</span> <span m=''4961040''>have</span> <span m=''4961340''>things</span>
  <span m=''4961690''>like</span> <span m=''4962640''>greatest</span> <span m=''4963010''>common</span>
  <span m=''4963350''>divisor,</span> <span m=''4964460''>which</span> <span m=''4964670''>is</span>
  <span m=''4964790''>a</span> <span m=''4964840''>thing</span> <span m=''4965060''>here</span>
  <span m=''4965210''>which</span> <span m=''4965380''>is</span> <span m=''4965500''>defined</span>
  <span m=''4965900''>only</span> <span m=''4966180''>for</span> <span m=''4966310''>integers,</span>
  <span m=''4967390''>and</span> <span m=''4967540''>not</span> <span m=''4967820''>in</span>
  <span m=''4967910''>general</span> <span m=''4968210''>for</span> <span m=''4968340''>rational</span>
  <span m=''4968740''>numbers.</span> <span m=''4971030''>So</span> <span m=''4971210''>it
  might</span> <span m=''4971340''>be a</span> <span m=''4971540''>very,</span> <span
  m=''4971930''>very</span> <span m=''4972200''>fragmented</span> <span m=''4972760''>system.</span>
  <span m=''4973110''>And</span> <span m=''4973190''>then</span> <span m=''4973270''>depending</span>
  <span m=''4973700''>on</span> <span m=''4974090''>where</span> <span m=''4974320''>you</span>
  <span m=''4974480''>want</span> <span m=''4974730''>your</span> <span m=''4974890''>flexibility,</span>
  <span m=''4976570''>there''s</span> <span m=''4976770''>a</span> <span m=''4976820''>whole</span>
  <span m=''4977000''>spectrum</span> <span m=''4977430''>of</span> <span m=''4977530''>places</span>
  <span m=''4977940''>that</span> <span m=''4978060''>you</span> <span m=''4978190''>can</span>
  <span m=''4978330''>build</span> <span m=''4978620''>that</span> <span m=''4978740''>in.</span>
  <span m=''4979960''>But</span> <span m=''4980100''>you''re</span> <span m=''4980220''>pointing</span>
  <span m=''4980610''>at</span> <span m=''4980700''>the</span> <span m=''4980780''>place</span>
  <span m=''4981020''>where</span> <span m=''4981130''>this</span> <span m=''4981270''>starts</span>
  <span m=''4982080''>being</span> <span m=''4982320''>weak,</span> <span m=''4982670''>that</span>
  <span m=''4982790''>there</span> <span m=''4982900''>has</span> <span m=''4983140''>to</span>
  <span m=''4983220''>be</span> <span m=''4983320''>some</span> <span m=''4983490''>agreement</span>
  <span m=''4983850''>on</span> <span m=''4983980''>top</span> <span m=''4984260''>here</span>
  <span m=''4984540''>about</span> <span m=''4985330''>these</span> <span m=''4985500''>general</span>
  <span m=''4985820''>operations.</span> <span m=''4986370''>Or</span> <span m=''4986430''>at
  least</span> <span m=''4986630''>people</span> <span m=''4986840''>have</span> <span
  m=''4986940''>to</span> <span m=''4987040''>think</span> <span m=''4987280''>about</span>
  <span m=''4987740''>them.</span> <span m=''4988390''>Or</span> <span m=''4988550''>you</span>
  <span m=''4988670''>might</span> <span m=''4988860''>decide,</span> <span m=''4989180''>you</span>
  <span m=''4989280''>might</span> <span m=''4989440''>have</span> <span m=''4989530''>a</span>
  <span m=''4989630''>table</span> <span m=''4989960''>that''s</span> <span m=''4990140''>very</span>
  <span m=''4990340''>sparse,</span> <span m=''4990770''>that only</span> <span m=''4990980''>has</span>
  <span m=''4991190''>a</span> <span m=''4991240''>few</span> <span m=''4991410''>things</span>
  <span m=''4991680''>in</span> <span m=''4991790''>it.</span> <span m=''4994010''>But</span>
  <span m=''4994180''>there</span> <span m=''4994260''>are</span> <span m=''4994290''>lot</span>
  <span m=''4994520''>of</span> <span m=''4994590''>ways</span> <span m=''4994800''>to</span>
  <span m=''4994880''>play</span> <span m=''4995060''>that</span> <span m=''4995280''>game.</span>
  <span m=''4999780''>OK,</span> <span m=''5000040''>thank</span> <span m=''5000250''>you.</span>
  </p><p><span m=''5003534''>[MUSIC: "JESU, JOY OF MAN''S DESIRING" BY JOHANN SEBASTIAN
  BACH]</span> </p>'
type: course
uid: 088abd6ab74fc074cee8818d4f3dcf27

---
None