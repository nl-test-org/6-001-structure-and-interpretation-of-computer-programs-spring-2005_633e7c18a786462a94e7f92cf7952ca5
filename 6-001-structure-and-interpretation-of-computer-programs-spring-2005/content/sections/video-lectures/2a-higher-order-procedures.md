---
about_this_resource_text: <p><b>Topics covered:</b> Higher-order Procedures</p> <p><b>
  Instructors:</b> Hal Abelson and Gerald Jay Sussman</p> <p>Subtitles for this course
  are provided through the generous assistance of Henry Baker, Hoofar Pourzand, Heather
  Wood, Aleksejs Truhans, Steven Edwards, George Menhorn, and Mahendra Kumar.</p>
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
embedded_media:
- id: 2A.jpg
  parent_uid: 11baf0a782fb1ef4a384c3213648f09b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/2a-higher-order-procedures/2A.jpg
  title: 2A.jpg
  type: null
  uid: 17eff22656a9c4dee849084e694d3e08
- id: Video-YouTube-Stream
  media_location: eJeMOEiHv8c
  parent_uid: 11baf0a782fb1ef4a384c3213648f09b
  title: Video-YouTube-Stream
  type: Video
  uid: 1f9d5d48a7995acf77c4342f0b79cd8e
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT_Structure_of_Computer_Programs_1986/lec2a.mp4
  parent_uid: 11baf0a782fb1ef4a384c3213648f09b
  title: Video-Internet Archive-MP4
  type: Video
  uid: bf3b3dadf813c39e33e65b91b495065d
- id: Thumbnail-OCW-JPG
  parent_uid: 11baf0a782fb1ef4a384c3213648f09b
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 144a53e48b6c25f5b944b6948b26130c
- id: 3Play-3PlayYouTubeid-MP4
  media_location: eJeMOEiHv8c
  parent_uid: 11baf0a782fb1ef4a384c3213648f09b
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: adb51c09d4fbafa8f489a49990e7774a
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/eJeMOEiHv8c/default.jpg
  parent_uid: 11baf0a782fb1ef4a384c3213648f09b
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 45dcdc4f9d86c289abb2a03fbc717c2a
- id: eJeMOEiHv8c.srt
  parent_uid: 11baf0a782fb1ef4a384c3213648f09b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/2a-higher-order-procedures/eJeMOEiHv8c.srt
  title: 3play caption file
  type: null
  uid: 2357c38e12703534461596528a1e0000
- id: eJeMOEiHv8c.pdf
  parent_uid: 11baf0a782fb1ef4a384c3213648f09b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/2a-higher-order-procedures/eJeMOEiHv8c.pdf
  title: 3play pdf file
  type: null
  uid: 32465b886efeca0f6edafaed2f0586c3
- id: Caption-3Play YouTube id-SRT
  parent_uid: 11baf0a782fb1ef4a384c3213648f09b
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 50dbae0f2c0dd2ca7d1be7abab71e583
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 11baf0a782fb1ef4a384c3213648f09b
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: f29ca5d5ff1cf53558e8e14a9bc88b5f
inline_embed_id: 552011942a:higher-orderprocedures45463525
layout: video
order_index: null
parent_uid: 4fcacad2c29981dd668a6b29822403cc
related_resources_text: ''
short_url: 2a-higher-order-procedures
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/2a-higher-order-procedures
template_type: Tabbed
title: '2A: Higher-order Procedures'
transcript: '<p><span m=''25680''>PROFESSOR: Well,</span> <span m=''25920''>yesterday</span>
  <span m=''26390''>was</span> <span m=''26570''>easy.</span> <span m=''27960''>You</span>
  <span m=''28440''>learned</span> <span m=''28600''>all</span> <span m=''28790''>of</span>
  <span m=''28900''>the</span> <span m=''29010''>rules of</span> <span m=''29380''>programming</span>
  <span m=''30776''>and</span> <span m=''31180''>lived.</span> <span m=''33020''>Almost</span>
  <span m=''33450''>all</span> <span m=''33570''>of</span> <span m=''33690''>them.</span>
  <span m=''34980''>And</span> <span m=''35260''>so</span> <span m=''35510''>at</span>
  <span m=''35580''>this</span> <span m=''35770''>point,</span> <span m=''36140''>you''re
  now</span> <span m=''36330''>certified</span> <span m=''36850''>programmers--</span>
  <span m=''38372''>it</span> <span m=''38828''>says.</span> <span m=''40200''>However,</span>
  <span m=''41400''>I</span> <span m=''41630''>suppose</span> <span m=''42080''>what
  we</span> <span m=''42270''>did is</span> <span m=''47090''>we, aah,</span> <span
  m=''47210''>sort</span> <span m=''47390''>of</span> <span m=''48530''>got</span>
  <span m=''48750''>you</span> <span m=''48870''>a</span> <span m=''48890''>little</span>
  <span m=''49110''>bit</span> <span m=''49280''>of</span> <span m=''50140''>into</span>
  <span m=''50310''>an easy</span> <span m=''50780''>state.</span> <span m=''51700''>Here,</span>
  <span m=''51800''>you</span> <span m=''52560''>still</span> <span m=''52760''>believe</span>
  <span m=''53090''>it''s</span> <span m=''53240''>possible</span> <span m=''54100''>that
  this</span> <span m=''54440''>might</span> <span m=''54670''>be</span> <span m=''54770''>programming
  in</span> <span m=''55250''>BASIC</span> <span m=''55690''>or Pascal</span> <span
  m=''56340''>with</span> <span m=''56725''>just</span> <span m=''57110''>a funny</span>
  <span m=''57465''>syntax.</span> <span m=''59250''>Today,</span> <span m=''60650''>that</span>
  <span m=''61050''>illusion--</span> <span m=''61770''>or</span> <span m=''62160''>you</span>
  <span m=''62300''>can</span> <span m=''62500''>no</span> <span m=''62620''>longer</span>
  <span m=''63000''>support</span> <span m=''63600''>that</span> <span m=''64250''>belief.</span>
  <span m=''64919''>What we''re</span> <span m=''65239''>going to</span> <span m=''65440''>do
  today</span> <span m=''65670''>is</span> <span m=''66170''>going</span> <span m=''66310''>to</span>
  <span m=''66450''>completely</span> <span m=''66910''>smash</span> <span m=''67410''>that.</span>
  </p><p><span m=''68340''>So</span> <span m=''69310''>let''s</span> <span m=''69520''>start</span>
  <span m=''69810''>out</span> <span m=''72370''>by</span> <span m=''72500''>writing</span>
  <span m=''72770''>a</span> <span m=''72810''>few</span> <span m=''73010''>programs</span>
  <span m=''73460''>on</span> <span m=''73520''>the</span> <span m=''73590''>blackboard</span>
  <span m=''74020''>that</span> <span m=''74090''>have</span> <span m=''74180''>a</span>
  <span m=''74270''>lot</span> <span m=''74490''>in</span> <span m=''74550''>common</span>
  <span m=''74860''>with</span> <span m=''75010''>each</span> <span m=''75180''>other.</span>
  <span m=''75895''>What</span> <span m=''76350''>we''re</span> <span m=''76730''>going</span>
  <span m=''76810''>to</span> <span m=''76900''>do</span> <span m=''77180''>is</span>
  <span m=''77340''>try</span> <span m=''77470''>to</span> <span m=''77600''>make</span>
  <span m=''77790''>them</span> <span m=''78020''>abstractions</span> <span m=''78680''>that</span>
  <span m=''79540''>are</span> <span m=''79610''>not</span> <span m=''79860''>ones</span>
  <span m=''80490''>that</span> <span m=''81680''>are easy</span> <span m=''81890''>to
  make</span> <span m=''82255''>in</span> <span m=''82620''>most</span> <span m=''82860''>languages.</span>
  <span m=''83880''>Let''s</span> <span m=''84320''>start</span> <span m=''84590''>with</span>
  <span m=''84730''>some</span> <span m=''84790''>very simple</span> <span m=''85240''>ones</span>
  <span m=''85480''>that you can</span> <span m=''85760''>make</span> <span m=''86040''>in</span>
  <span m=''86130''>most</span> <span m=''86380''>languages.</span> </p><p><span m=''88070''>Supposing</span>
  <span m=''88410''>I</span> <span m=''88500''>want</span> <span m=''88760''>to</span>
  <span m=''88880''>write</span> <span m=''89480''>the</span> <span m=''90230''>mathematical</span>
  <span m=''90960''>expression</span> <span m=''91880''>which</span> <span m=''92130''>adds</span>
  <span m=''92420''>up</span> <span m=''93150''>a</span> <span m=''93400''>bunch</span>
  <span m=''93550''>of</span> <span m=''93930''>integers.</span> <span m=''94100''>So</span>
  <span m=''94560''>if I</span> <span m=''94930''>wanted</span> <span m=''95080''>to</span>
  <span m=''95210''>write</span> <span m=''95440''>down</span> <span m=''96550''>and</span>
  <span m=''96780''>say</span> <span m=''97030''>the</span> <span m=''97290''>sum</span>
  <span m=''98120''>from</span> <span m=''98510''>i</span> <span m=''98850''>equal</span>
  <span m=''99090''>a</span> <span m=''99675''>to</span> <span m=''100080''>b</span>
  <span m=''100895''>on</span> <span m=''101150''>i.</span> <span m=''101410''>Now,</span>
  <span m=''101830''>you</span> <span m=''101970''>know that</span> <span m=''102330''>that''s</span>
  <span m=''102800''>an</span> <span m=''102860''>easy</span> <span m=''103140''>thing</span>
  <span m=''103340''>to</span> <span m=''103430''>compute</span> <span m=''103750''>in</span>
  <span m=''103930''>a</span> <span m=''104190''>closed</span> <span m=''104510''>form</span>
  <span m=''104780''>for it, and</span> <span m=''105120''>I''m</span> <span m=''105230''>not</span>
  <span m=''105450''>interested</span> <span m=''105830''>in</span> <span m=''105980''>that.</span>
  <span m=''106180''>But I''m going to write a</span> <span m=''106600''>program</span>
  <span m=''106960''>that adds</span> <span m=''107320''>up</span> <span m=''107660''>those</span>
  <span m=''107780''>integers.</span> </p><p><span m=''109045''>Well,</span> <span
  m=''109490''>that''s</span> <span m=''110480''>rather</span> <span m=''110820''>easy</span>
  <span m=''111080''>to</span> <span m=''111190''>do</span> <span m=''112220''>to</span>
  <span m=''112970''>say</span> <span m=''113250''>I want</span> <span m=''113570''>to</span>
  <span m=''113890''>define</span> <span m=''117402''>the</span> <span m=''117890''>sum</span>
  <span m=''118550''>of</span> <span m=''118650''>the</span> <span m=''118760''>integers</span>
  <span m=''124030''>from</span> <span m=''124460''>a</span> <span m=''124710''>to</span>
  <span m=''124850''>b</span> <span m=''126840''>to</span> <span m=''127095''>be--</span>
  <span m=''128710''>well,</span> <span m=''129100''>it''s</span> <span m=''129490''>the</span>
  <span m=''129620''>following</span> <span m=''130060''>two</span> <span m=''130150''>possibilities.</span>
  <span m=''131380''>If</span> <span m=''132130''>a</span> <span m=''132610''>is</span>
  <span m=''132800''>greater</span> <span m=''133090''>than</span> <span m=''133330''>b,</span>
  <span m=''135500''>well,</span> <span m=''135850''>then</span> <span m=''136560''>there''s</span>
  <span m=''136860''>nothing</span> <span m=''137180''>to</span> <span m=''137270''>be</span>
  <span m=''137430''>done</span> <span m=''137680''>and</span> <span m=''137770''>the</span>
  <span m=''137870''>answer</span> <span m=''138250''>is</span> <span m=''138330''>zero.</span>
  <span m=''139582''>This is</span> <span m=''140020''>how</span> <span m=''140340''>you''re
  going to</span> <span m=''140470''>have to</span> <span m=''140640''>think</span>
  <span m=''140820''>recursively.</span> <span m=''142530''>You''re going to</span>
  <span m=''142850''>say</span> <span m=''143105''>if</span> <span m=''143360''>I</span>
  <span m=''143490''>have</span> <span m=''143700''>an</span> <span m=''143790''>easy</span>
  <span m=''144120''>case</span> <span m=''144400''>that</span> <span m=''144490''>I</span>
  <span m=''144580''>know</span> <span m=''144710''>the</span> <span m=''144880''>answer</span>
  <span m=''145080''>to,</span> <span m=''145590''>just</span> <span m=''145790''>write
  it</span> <span m=''146040''>down.</span> <span m=''146610''>Otherwise,</span> <span
  m=''147410''>I''m</span> <span m=''147530''>going to</span> <span m=''147850''>try</span>
  <span m=''148040''>to</span> <span m=''148140''>reduce</span> <span m=''148580''>this</span>
  <span m=''148790''>problem</span> <span m=''149590''>to</span> <span m=''149830''>a</span>
  <span m=''149890''>simpler</span> <span m=''150240''>problem.</span> <span m=''151060''>And</span>
  <span m=''151220''>maybe</span> <span m=''151450''>in</span> <span m=''151540''>this</span>
  <span m=''151720''>case,</span> <span m=''151930''>I''m going to</span> <span m=''152010''>make</span>
  <span m=''152400''>a  subproblem</span> <span m=''152630''>of</span> <span m=''153000''>the</span>
  <span m=''153140''>simpler</span> <span m=''153440''>problem</span> <span m=''153730''>and</span>
  <span m=''154120''>then do</span> <span m=''154440''>something to</span> <span m=''154510''>the</span>
  <span m=''154580''>result.</span> <span m=''155340''>So</span> <span m=''156940''>the</span>
  <span m=''157100''>easiest</span> <span m=''157400''>way</span> <span m=''157490''>to</span>
  <span m=''157580''>do</span> <span m=''157770''>this</span> <span m=''158540''>is</span>
  <span m=''158690''>say</span> <span m=''158970''>that</span> <span m=''159090''>I''m</span>
  <span m=''159200''>going</span> <span m=''159410''>to</span> <span m=''159990''>add</span>
  <span m=''161290''>the</span> <span m=''161760''>index,</span> <span m=''162180''>which</span>
  <span m=''162611''>in this</span> <span m=''163042''>case</span> <span m=''163473''>is
  a,</span> <span m=''164766''>to the</span> <span m=''165200''>result</span> <span
  m=''166050''>of</span> <span m=''166270''>adding</span> <span m=''166530''>up</span>
  <span m=''166630''>the</span> <span m=''166720''>integers</span> <span m=''171800''>from</span>
  <span m=''173040''>a</span> <span m=''173180''>plus</span> <span m=''173450''>1</span>
  <span m=''177040''>to</span> <span m=''177490''>b.</span> </p><p><span m=''182343''>Now,</span>
  <span m=''182830''>at</span> <span m=''183010''>this</span> <span m=''183190''>point,</span>
  <span m=''183490''>you should</span> <span m=''183570''>have</span> <span m=''183670''>no</span>
  <span m=''183850''>trouble</span> <span m=''184140''>looking</span> <span m=''184380''>at</span>
  <span m=''184460''>such</span> <span m=''184650''>a</span> <span m=''184710''>definition.</span>
  <span m=''186190''>Indeed,</span> <span m=''187550''>coming</span> <span m=''187860''>up</span>
  <span m=''188010''>with</span> <span m=''188140''>such</span> <span m=''188330''>a</span>
  <span m=''188390''>thing</span> <span m=''188610''>might</span> <span m=''188850''>be</span>
  <span m=''189030''>a little</span> <span m=''189360''>hard</span> <span m=''189740''>in
  synthesis,</span> <span m=''190205''>but</span> <span m=''190770''>being</span>
  <span m=''190900''>able</span> <span m=''191010''>to</span> <span m=''191100''>read</span>
  <span m=''191310''>it at</span> <span m=''191460''>this</span> <span m=''191670''>point</span>
  <span m=''192230''>should</span> <span m=''192360''>be</span> <span m=''192690''>easy.</span>
  <span m=''193840''>And</span> <span m=''193910''>what it</span> <span m=''194220''>says</span>
  <span m=''194490''>to</span> <span m=''194590''>you</span> <span m=''195220''>is,</span>
  <span m=''195740''>well,</span> <span m=''196900''>here</span> <span m=''197210''>is</span>
  <span m=''197300''>the</span> <span m=''197460''>subproblem</span> <span m=''198220''>I''m</span>
  <span m=''198640''>going</span> <span m=''198840''>to</span> <span m=''198900''>solve.</span>
  <span m=''199520''>I''m</span> <span m=''199780''>going</span> <span m=''200040''>to</span>
  <span m=''200720''>try</span> <span m=''200990''>to</span> <span m=''201130''>add</span>
  <span m=''201290''>up</span> <span m=''201400''>the</span> <span m=''201520''>integers,</span>
  <span m=''202340''>one</span> <span m=''202610''>fewer</span> <span m=''202920''>integer</span>
  <span m=''204240''>than</span> <span m=''204560''>I added</span> <span m=''204870''>up
  for the</span> <span m=''205180''>the</span> <span m=''205320''>whole</span> <span
  m=''205550''>problem.</span> <span m=''206970''>I''m</span> <span m=''207200''>adding</span>
  <span m=''207390''>up</span> <span m=''207500''>the</span> <span m=''207620''>one</span>
  <span m=''207850''>fewer</span> <span m=''208100''>one,</span> <span m=''209250''>and</span>
  <span m=''210060''>that</span> <span m=''210385''>subproblem,</span> <span m=''211100''>once</span>
  <span m=''211270''>I''ve</span> <span m=''211480''>solved</span> <span m=''211800''>it,</span>
  <span m=''212080''>I''m going to</span> <span m=''212570''>add a</span> <span m=''212720''>to</span>
  <span m=''212830''>that,</span> <span m=''214610''>and</span> <span m=''214960''>that
  will</span> <span m=''215150''>be</span> <span m=''215410''>the answer to</span>
  <span m=''215700''>this</span> <span m=''216040''>problem.</span> <span m=''218550''>And</span>
  <span m=''218780''>the</span> <span m=''218840''>simplest</span> <span m=''219260''>case,</span>
  <span m=''219890''>I don''t have to</span> <span m=''220010''>do</span> <span m=''220380''>any</span>
  <span m=''220500''>work.</span> </p><p><span m=''221626''>Now, I''m</span> <span
  m=''222010''>also</span> <span m=''222190''>going</span> <span m=''222300''>to</span>
  <span m=''222490''>write</span> <span m=''222690''>down</span> <span m=''223250''>another</span>
  <span m=''223670''>simple</span> <span m=''224480''>one</span> <span m=''224720''>just</span>
  <span m=''224990''>like</span> <span m=''225240''>this,</span> <span m=''226740''>which</span>
  <span m=''227020''>is</span> <span m=''227190''>the</span> <span m=''228620''>mathematical</span>
  <span m=''229160''>expression,</span> <span m=''229465''>the sum</span> <span m=''229770''>of</span>
  <span m=''230070''>the</span> <span m=''230140''>square</span> <span m=''231358''>from</span>
  <span m=''231782''>i</span> <span m=''232206''>equal</span> <span m=''232630''>a</span>
  <span m=''232890''>to</span> <span m=''233150''>b.</span> <span m=''235840''>And</span>
  <span m=''235990''>again,</span> <span m=''237160''>it''s a</span> <span m=''237320''>very</span>
  <span m=''237510''>simple</span> <span m=''237780''>program.</span> <span m=''251220''>And</span>
  <span m=''252000''>indeed,</span> <span m=''252160''>it</span> <span m=''252330''>starts</span>
  <span m=''252670''>the</span> <span m=''252770''>same</span> <span m=''253060''>way.</span>
  <span m=''256029''>If</span> <span m=''256459''>a</span> <span m=''256760''>is</span>
  <span m=''257019''>greater</span> <span m=''257260''>than</span> <span m=''257450''>b,</span>
  <span m=''259040''>then</span> <span m=''259269''>the</span> <span m=''259420''>answer</span>
  <span m=''259720''>is</span> <span m=''259790''>zero.</span> <span m=''261240''>And,</span>
  <span m=''261390''>of</span> <span m=''261570''>course,</span> <span m=''261750''>we''re</span>
  <span m=''261870''>beginning</span> <span m=''262230''>to</span> <span m=''262370''>see</span>
  <span m=''263500''>that</span> <span m=''263630''>there''s</span> <span m=''264160''>something</span>
  <span m=''264450''>wrong</span> <span m=''264760''>with</span> <span m=''265010''>me</span>
  <span m=''265150''>writing</span> <span m=''265490''>this</span> <span m=''265660''>down</span>
  <span m=''265920''>again.</span> <span m=''267980''>It''s</span> <span m=''268140''>the</span>
  <span m=''268210''>same</span> <span m=''268540''>program.</span> <span m=''269820''>It''s</span>
  <span m=''270070''>the</span> <span m=''270280''>sum</span> <span m=''271290''>of</span>
  <span m=''271430''>the</span> <span m=''271580''>square</span> <span m=''274948''>of</span>
  <span m=''275420''>a</span> <span m=''277140''>and</span> <span m=''277970''>the</span>
  <span m=''278160''>sum</span> <span m=''278360''>of</span> <span m=''278400''>the</span>
  <span m=''278450''>square</span> <span m=''281716''>of</span> <span m=''282180''>the</span>
  <span m=''282380''>increment</span> <span m=''285186''>and</span> <span m=''285660''>b.</span>
  </p><p><span m=''290880''>Now,</span> <span m=''291030''>if you</span> <span m=''291220''>look</span>
  <span m=''291350''>at</span> <span m=''291480''>these</span> <span m=''291740''>things,</span>
  <span m=''293250''>these programs</span> <span m=''293690''>are</span> <span m=''294070''>almost</span>
  <span m=''294370''>identical.</span> <span m=''296380''>There''s</span> <span m=''296650''>not</span>
  <span m=''298240''>much</span> <span m=''298410''>to</span> <span m=''298500''>distinguish</span>
  <span m=''298980''>them.</span> <span m=''299860''>They</span> <span m=''300160''>have</span>
  <span m=''300470''>the</span> <span m=''300540''>same</span> <span m=''300860''>first</span>
  <span m=''301180''>clause</span> <span m=''301550''>of</span> <span m=''301640''>the</span>
  <span m=''301720''>conditional</span> <span m=''303000''>and</span> <span m=''303140''>the</span>
  <span m=''303320''>same</span> <span m=''303430''>predicate</span> <span m=''303700''>and</span>
  <span m=''303750''>the</span> <span m=''303820''>same</span> <span m=''304040''>consequence,</span>
  <span m=''305980''>and</span> <span m=''306150''>the</span> <span m=''306250''>alternatives</span>
  <span m=''307170''>are</span> <span m=''307340''>very</span> <span m=''307620''>similar,</span>
  <span m=''308000''>too.</span> <span m=''308910''>They</span> <span m=''309230''>only</span>
  <span m=''309520''>differ</span> <span m=''310430''>by</span> <span m=''310590''>the</span>
  <span m=''310730''>fact</span> <span m=''311250''>that</span> <span m=''311590''>where</span>
  <span m=''311890''>here</span> <span m=''312540''>I</span> <span m=''312800''>have</span>
  <span m=''313580''>a,</span> <span m=''315510''>here, I</span> <span m=''315700''>have</span>
  <span m=''315890''>the</span> <span m=''315970''>square</span> <span m=''316410''>of</span>
  <span m=''316873''>a.</span> <span m=''317336''>The</span> <span m=''317800''>only</span>
  <span m=''318100''>other</span> <span m=''318360''>difference,</span> <span m=''319320''>but</span>
  <span m=''319460''>this</span> <span m=''319590''>one''s</span> <span m=''319850''>sort</span>
  <span m=''320010''>of</span> <span m=''321290''>unessential</span> <span m=''322020''>is</span>
  <span m=''322220''>in</span> <span m=''322420''>the</span> <span m=''322550''>name</span>
  <span m=''322790''>of</span> <span m=''322900''>this</span> <span m=''323010''>procedure</span>
  <span m=''323550''>is</span> <span m=''323670''>sum</span> <span m=''323940''>int,</span>
  <span m=''325020''>whereas</span> <span m=''325240''>the</span> <span m=''325320''>name</span>
  <span m=''325530''>of</span> <span m=''325600''>the</span> <span m=''325720''>procedure</span>
  <span m=''326010''>is</span> <span m=''326300''>sum</span> <span m=''326540''>square.</span>
  <span m=''327560''>So</span> <span m=''328040''>the</span> <span m=''328180''>things</span>
  <span m=''328320''>that</span> <span m=''328430''>vary</span> <span m=''329250''>between</span>
  <span m=''329610''>these</span> <span m=''329820''>two</span> <span m=''330800''>are</span>
  <span m=''330950''>very</span> <span m=''331250''>small.</span> </p><p><span m=''333250''>Now,</span>
  <span m=''333620''>wherever</span> <span m=''333970''>you</span> <span m=''334060''>see</span>
  <span m=''334210''>yourself</span> <span m=''334570''>writing</span> <span m=''334850''>the</span>
  <span m=''334940''>same</span> <span m=''335170''>thing</span> <span m=''335360''>down</span>
  <span m=''336080''>more</span> <span m=''336290''>than</span> <span m=''336450''>once,</span>
  <span m=''337120''>there''s</span> <span m=''337540''>something</span> <span m=''337870''>wrong,
  and</span> <span m=''338230''>you</span> <span m=''338340''>shouldn''t</span> <span
  m=''338630''>be</span> <span m=''338740''>doing</span> <span m=''339030''>it.</span>
  <span m=''340280''>And</span> <span m=''340400''>the</span> <span m=''340530''>reason</span>
  <span m=''340840''>is</span> <span m=''340970''>not</span> <span m=''341270''>because</span>
  <span m=''342460''>it''s</span> <span m=''342610''>a</span> <span m=''342650''>waste</span>
  <span m=''342900''>of</span> <span m=''342960''>time</span> <span m=''343170''>to</span>
  <span m=''343240''>write</span> <span m=''343420''>something</span> <span m=''343610''>down</span>
  <span m=''343840''>more than</span> <span m=''344040''>once.</span> <span m=''345540''>It''s</span>
  <span m=''345730''>because</span> <span m=''345800''>there''s</span> <span m=''346090''>some</span>
  <span m=''346300''>idea</span> <span m=''346730''>here,</span> <span m=''347970''>a</span>
  <span m=''348090''>very</span> <span m=''348460''>simple</span> <span m=''348810''>idea,</span>
  <span m=''350720''>which</span> <span m=''351520''>has</span> <span m=''351730''>to</span>
  <span m=''351820''>do</span> <span m=''352010''>with</span> <span m=''352150''>the</span>
  <span m=''352300''>sigma</span> <span m=''352680''>notation--</span> <span m=''354620''>this</span>
  <span m=''355240''>much--</span> <span m=''357330''>not</span> <span m=''357600''>depending</span>
  <span m=''358010''>upon</span> <span m=''358580''>what</span> <span m=''358800''>it</span>
  <span m=''358930''>is</span> <span m=''359070''>I''m</span> <span m=''359240''>adding</span>
  <span m=''359530''>up.</span> <span m=''361255''>And</span> <span m=''361740''>I</span>
  <span m=''361900''>would</span> <span m=''362030''>like</span> <span m=''362210''>to</span>
  <span m=''362290''>be</span> <span m=''362370''>able</span> <span m=''362520''>to--</span>
  <span m=''363070''>always,</span> <span m=''363530''>whenever</span> <span m=''363910''>trying</span>
  <span m=''364260''>to</span> <span m=''364360''>make</span> <span m=''364580''>complicated</span>
  <span m=''365120''>systems</span> <span m=''365490''>and</span> <span m=''365610''>understand</span>
  <span m=''365880''>them,</span> <span m=''366680''>it''s</span> <span m=''367040''>crucial</span>
  <span m=''367520''>to</span> <span m=''367620''>divide</span> <span m=''368010''>the</span>
  <span m=''368090''>things</span> <span m=''368340''>up</span> <span m=''368470''>into
  as</span> <span m=''368680''>many</span> <span m=''368900''>pieces</span> <span
  m=''369240''>as</span> <span m=''369350''>I</span> <span m=''369470''>can,</span>
  <span m=''370020''>each</span> <span m=''370170''>of</span> <span m=''370320''>which</span>
  <span m=''370490''>I</span> <span m=''370600''>understand</span> <span m=''371030''>separately.</span>
  <span m=''373050''>I</span> <span m=''373160''>would</span> <span m=''373270''>like</span>
  <span m=''373440''>to</span> <span m=''373510''>understand</span> <span m=''373990''>the</span>
  <span m=''374050''>way</span> <span m=''374220''>of</span> <span m=''374320''>adding</span>
  <span m=''374570''>things</span> <span m=''374810''>up</span> <span m=''375030''>independently</span>
  <span m=''375590''>of</span> <span m=''375670''>what</span> <span m=''375830''>it
  is</span> <span m=''376000''>I''m</span> <span m=''376190''>adding up</span> <span
  m=''377350''>so</span> <span m=''377650''>I</span> <span m=''377740''>can</span>
  <span m=''377940''>do</span> <span m=''378140''>that</span> <span m=''379540''>having</span>
  <span m=''379870''>debugged it</span> <span m=''380300''>once</span> <span m=''381760''>and</span>
  <span m=''382190''>understood it</span> <span m=''382420''>once</span> <span m=''383820''>and</span>
  <span m=''384010''>having</span> <span m=''384260''>been</span> <span m=''384430''>able</span>
  <span m=''384550''>to</span> <span m=''384610''>share</span> <span m=''384940''>that</span>
  <span m=''385360''>among</span> <span m=''385820''>many</span> <span m=''386040''>different</span>
  <span m=''387350''>uses of</span> <span m=''387570''>it.</span> </p><p><span m=''389400''>Here,</span>
  <span m=''389590''>we</span> <span m=''389690''>have</span> <span m=''389820''>another</span>
  <span m=''390120''>example.</span> <span m=''392360''>This</span> <span m=''392790''>is</span>
  <span m=''395110''>Leibnitz''s</span> <span m=''395430''>formula</span> <span m=''396870''>for</span>
  <span m=''397980''>finding</span> <span m=''398420''>pi</span> <span m=''398800''>over</span>
  <span m=''399055''>8.</span> <span m=''400400''>It''s</span> <span m=''400640''>a</span>
  <span m=''401420''>funny,</span> <span m=''401740''>ugly</span> <span m=''402060''>mess.</span>
  <span m=''403460''>What</span> <span m=''403630''>is</span> <span m=''403760''>it?</span>
  <span m=''403930''>It''s something</span> <span m=''404270''>like</span> <span m=''406250''>1</span>
  <span m=''406480''>over</span> <span m=''406810''>1</span> <span m=''407140''>times</span>
  <span m=''407620''>3</span> <span m=''408140''>plus</span> <span m=''408840''>1</span>
  <span m=''409120''>over</span> <span m=''409550''>5</span> <span m=''409990''>times</span>
  <span m=''410390''>7</span> <span m=''410670''>plus</span> <span m=''411390''>1</span>
  <span m=''411720''>over</span> <span m=''412300''>9</span> <span m=''412700''>times</span>
  <span m=''412990''>11</span> <span m=''413870''>plus--</span> <span m=''414340''>and
  for</span> <span m=''414560''>some</span> <span m=''414820''>reason,</span> <span
  m=''416160''>things</span> <span m=''416430''>like</span> <span m=''416640''>this
  tend</span> <span m=''417010''>to</span> <span m=''419450''>have</span> <span m=''419750''>interesting</span>
  <span m=''420060''>values</span> <span m=''420520''>like</span> <span m=''420740''>pi</span>
  <span m=''420920''>over</span> <span m=''421020''>8.</span> <span m=''422160''>But</span>
  <span m=''423650''>what do</span> <span m=''423840''>we</span> <span m=''423990''>see</span>
  <span m=''424210''>here?</span> <span m=''424460''>It''s</span> <span m=''424590''>the</span>
  <span m=''424710''>same</span> <span m=''425000''>program</span> <span m=''425750''>or</span>
  <span m=''426120''>almost</span> <span m=''426480''>the</span> <span m=''426570''>same</span>
  <span m=''426840''>program.</span> <span m=''427850''>It''s</span> <span m=''428020''>a</span>
  <span m=''428080''>sum.</span> <span m=''429290''>So</span> <span m=''429740''>we''re</span>
  <span m=''429910''>seeing</span> <span m=''430470''>the</span> <span m=''430710''>figure</span>
  <span m=''430910''>notation,</span> <span m=''431500''>although</span> <span m=''431860''>over</span>
  <span m=''432040''>here,</span> <span m=''432660''>we''re</span> <span m=''432970''>dealing</span>
  <span m=''433380''>with</span> <span m=''435430''>incrementing</span> <span m=''436010''>by</span>
  <span m=''436190''>4,</span> <span m=''437090''>so it''s</span> <span m=''437250''>a</span>
  <span m=''437320''>slightly</span> <span m=''437700''>different</span> <span m=''437980''>problem,</span>
  <span m=''438630''>which</span> <span m=''438920''>means</span> <span m=''439240''>that</span>
  <span m=''439380''>over</span> <span m=''439690''>here,</span> <span m=''440430''>I</span>
  <span m=''440550''>have</span> <span m=''440720''>to</span> <span m=''440860''>change
  a</span> <span m=''442190''>by</span> <span m=''442390''>4,</span> <span m=''442760''>as</span>
  <span m=''442870''>you</span> <span m=''443010''>see</span> <span m=''443210''>right</span>
  <span m=''443470''>over</span> <span m=''443650''>here.</span> <span m=''445560''>It''s</span>
  <span m=''445760''>not</span> <span m=''446030''>by</span> <span m=''446170''>1.</span>
  </p><p><span m=''448390''>The</span> <span m=''448540''>other</span> <span m=''448770''>thing,</span>
  <span m=''448970''>of</span> <span m=''449240''>course,</span> <span m=''449740''>is</span>
  <span m=''449920''>that</span> <span m=''450130''>the</span> <span m=''450670''>thing</span>
  <span m=''450910''>that''s</span> <span m=''451150''>represented</span> <span m=''451730''>by</span>
  <span m=''451890''>square</span> <span m=''452830''>in</span> <span m=''453070''>the</span>
  <span m=''453310''>previous</span> <span m=''453660''>sum of</span> <span m=''453930''>squares,</span>
  <span m=''454380''>or</span> <span m=''454580''>a when</span> <span m=''455030''>adding</span>
  <span m=''455330''>up</span> <span m=''455440''>the</span> <span m=''455540''>integers.</span>
  <span m=''456400''>Well,</span> <span m=''456580''>here, I</span> <span m=''456810''>have</span>
  <span m=''456980''>a</span> <span m=''457020''>different</span> <span m=''457440''>thing</span>
  <span m=''457630''>I''m</span> <span m=''457770''>adding up,</span> <span m=''457960''>a</span>
  <span m=''458060''>different</span> <span m=''458370''>term,</span> <span m=''459070''>which</span>
  <span m=''459260''>is</span> <span m=''459630''>1</span> <span m=''459860''>over</span>
  <span m=''460170''>a</span> <span m=''462400''>times</span> <span m=''462640''>a</span>
  <span m=''462860''>plus</span> <span m=''463100''>2.</span> <span m=''464290''>But</span>
  <span m=''464530''>the</span> <span m=''464630''>rest</span> <span m=''464890''>of</span>
  <span m=''464950''>this</span> <span m=''465020''>program</span> <span m=''465490''>is</span>
  <span m=''465600''>identical.</span> <span m=''468530''>Well,</span> <span m=''468680''>any
  time</span> <span m=''469150''>we</span> <span m=''469300''>have</span> <span m=''469450''>a</span>
  <span m=''469500''>bunch</span> <span m=''469740''>of</span> <span m=''469840''>things</span>
  <span m=''470080''>like</span> <span m=''470270''>this</span> <span m=''470430''>that</span>
  <span m=''470530''>are</span> <span m=''470640''>identical,</span> <span m=''471700''>we''re</span>
  <span m=''471860''>going</span> <span m=''471950''>to</span> <span m=''472040''>have</span>
  <span m=''472170''>to</span> <span m=''472300''>come</span> <span m=''472480''>up</span>
  <span m=''472620''>with</span> <span m=''472770''>some</span> <span m=''472960''>sort</span>
  <span m=''473130''>of</span> <span m=''473200''>abstraction</span> <span m=''474160''>to</span>
  <span m=''474250''>cover</span> <span m=''474520''>them.</span> </p><p><span m=''475582''>If</span>
  <span m=''476000''>you</span> <span m=''476160''>think</span> <span m=''476340''>about</span>
  <span m=''476670''>this,</span> <span m=''477210''>what</span> <span m=''477370''>you''ve</span>
  <span m=''477540''>learned</span> <span m=''477830''>so</span> <span m=''478050''>far</span>
  <span m=''479310''>is</span> <span m=''479500''>the</span> <span m=''479920''>rules</span>
  <span m=''480200''>of</span> <span m=''480300''>some</span> <span m=''480400''>language,</span>
  <span m=''480880''>some</span> <span m=''481070''>primitive,</span> <span m=''482760''>some</span>
  <span m=''483070''>means of</span> <span m=''483370''>combination,</span> <span
  m=''484500''>almost</span> <span m=''484830''>all</span> <span m=''485000''>of</span>
  <span m=''485200''>them,</span> <span m=''485860''>the</span> <span m=''485960''>means</span>
  <span m=''486220''>of</span> <span m=''486310''>abstraction,</span> <span m=''486930''>almost</span>
  <span m=''487310''>all</span> <span m=''487450''>of</span> <span m=''487590''>them.</span>
  <span m=''489730''>But</span> <span m=''489990''>what</span> <span m=''490100''>you</span>
  <span m=''490180''>haven''t</span> <span m=''490420''>learned</span> <span m=''490800''>is</span>
  <span m=''491050''>common</span> <span m=''491330''>patterns</span> <span m=''491650''>of</span>
  <span m=''491720''>usage.</span> </p><p><span m=''493290''>Now,</span> <span m=''493460''>most</span>
  <span m=''493750''>of</span> <span m=''493810''>the</span> <span m=''493870''>time,</span>
  <span m=''494090''>you</span> <span m=''494190''>learn</span> <span m=''494370''>idioms</span>
  <span m=''494740''>when</span> <span m=''494860''>learning</span> <span m=''495070''>a</span>
  <span m=''495150''>language,</span> <span m=''495520''>which is</span> <span m=''495640''>a</span>
  <span m=''495710''>common</span> <span m=''495990''>pattern</span> <span m=''496500''>that</span>
  <span m=''497020''>mean</span> <span m=''497250''>things</span> <span m=''497990''>that</span>
  <span m=''498380''>are</span> <span m=''498400''>useful</span> <span m=''498750''>to</span>
  <span m=''498850''>know</span> <span m=''499630''>in a</span> <span m=''499810''>flash.</span>
  <span m=''500760''>And if</span> <span m=''501230''>you</span> <span m=''501500''>build</span>
  <span m=''501760''>a</span> <span m=''501800''>great</span> <span m=''502050''>number</span>
  <span m=''502320''>of</span> <span m=''502420''>them,</span> <span m=''502530''>if</span>
  <span m=''502620''>you''re a</span> <span m=''502760''>FORTRAN</span> <span m=''503190''>programmer,</span>
  <span m=''503510''>of</span> <span m=''503610''>course,</span> <span m=''503840''>everybody</span>
  <span m=''504200''>knows</span> <span m=''504420''>how</span> <span m=''504580''>to--</span>
  <span m=''506180''>what do</span> <span m=''506460''>you</span> <span m=''506530''>do,</span>
  <span m=''507640''>for</span> <span m=''507760''>example,</span> <span m=''508650''>to</span>
  <span m=''508730''>get</span> <span m=''508890''>an</span> <span m=''509010''>integer</span>
  <span m=''509420''>which is</span> <span m=''509560''>the</span> <span m=''509640''>biggest</span>
  <span m=''509880''>integer</span> <span m=''510340''>in something.</span> <span
  m=''511250''>It''s</span> <span m=''511550''>a</span> <span m=''511890''>classic</span>
  <span m=''512245''>thing.</span> <span m=''512600''>Every</span> <span m=''512799''>FORTRAN</span>
  <span m=''513049''>programmer</span> <span m=''513429''>knows how</span> <span m=''513600''>to
  do that.</span> <span m=''514350''>And if</span> <span m=''514630''>you</span> <span
  m=''514720''>don''t</span> <span m=''514870''>know</span> <span m=''515020''>that,</span>
  <span m=''515270''>you''re</span> <span m=''515409''>in real</span> <span m=''515610''>hot</span>
  <span m=''515820''>water</span> <span m=''516059''>because it</span> <span m=''516190''>takes</span>
  <span m=''516350''>a long</span> <span m=''516559''>time</span> <span m=''516700''>to
  think</span> <span m=''516960''>it out.</span> <span m=''518150''>However,</span>
  <span m=''519850''>one</span> <span m=''520049''>of</span> <span m=''520100''>the</span>
  <span m=''520159''>things</span> <span m=''520350''>you</span> <span m=''520450''>can</span>
  <span m=''520610''>do</span> <span m=''520789''>in</span> <span m=''520909''>this</span>
  <span m=''521110''>language</span> <span m=''521539''>that</span> <span m=''521620''>we''re</span>
  <span m=''521710''>showing</span> <span m=''521919''>you</span> <span m=''522380''>is</span>
  <span m=''522539''>not</span> <span m=''522720''>only do</span> <span m=''523000''>you</span>
  <span m=''523210''>know</span> <span m=''523400''>something</span> <span m=''523710''>like</span>
  <span m=''523900''>that,</span> <span m=''524090''>but</span> <span m=''524250''>you</span>
  <span m=''524520''>give</span> <span m=''524720''>the</span> <span m=''524810''>knowledge</span>
  <span m=''525280''>of</span> <span m=''525380''>that a</span> <span m=''525620''>name.</span>
  <span m=''528380''>And</span> <span m=''528660''>so</span> <span m=''528780''>that''s</span>
  <span m=''528990''>what</span> <span m=''529070''>we''re</span> <span m=''529170''>going</span>
  <span m=''529260''>to</span> <span m=''529350''>be</span> <span m=''529450''>going</span>
  <span m=''529720''>after</span> <span m=''529960''>right</span> <span m=''530230''>now.</span>
  </p><p><span m=''533530''>OK,</span> <span m=''533830''>well,</span> <span m=''534270''>let''s</span>
  <span m=''534550''>see</span> <span m=''534650''>what</span> <span m=''534810''>these</span>
  <span m=''534980''>things</span> <span m=''535190''>have</span> <span m=''535370''>in</span>
  <span m=''535470''>common.</span> <span m=''538680''>Right</span> <span m=''538860''>over</span>
  <span m=''539020''>here</span> <span m=''540190''>we</span> <span m=''540370''>have</span>
  <span m=''541060''>what</span> <span m=''541260''>appears</span> <span m=''541670''>to</span>
  <span m=''541760''>be</span> <span m=''542010''>a</span> <span m=''542160''>general</span>
  <span m=''542560''>pattern,</span> <span m=''544470''>a</span> <span m=''544600''>general</span>
  <span m=''544930''>pattern</span> <span m=''545260''>which</span> <span m=''545420''>covers</span>
  <span m=''545720''>all</span> <span m=''545870''>of</span> <span m=''546030''>the</span>
  <span m=''546100''>cases</span> <span m=''546470''>we''ve</span> <span m=''546680''>seen</span>
  <span m=''546910''>so</span> <span m=''547180''>far.</span> <span m=''549700''>There</span>
  <span m=''550110''>is</span> <span m=''550230''>a</span> <span m=''550860''>sum</span>
  <span m=''551830''>procedure,</span> <span m=''552380''>which</span> <span m=''552570''>is</span>
  <span m=''552670''>being</span> <span m=''552920''>defined.</span> <span m=''555200''>It</span>
  <span m=''555430''>has</span> <span m=''556240''>two</span> <span m=''556490''>arguments,</span>
  <span m=''556890''>which</span> <span m=''557040''>are</span> <span m=''557130''>a</span>
  <span m=''557380''>lower bound</span> <span m=''557680''>and an</span> <span m=''557860''>upper</span>
  <span m=''558060''>bound.</span> <span m=''559630''>The</span> <span m=''560130''>lower</span>
  <span m=''560400''>bound</span> <span m=''561710''>is</span> <span m=''562000''>tested</span>
  <span m=''562380''>to</span> <span m=''562460''>be</span> <span m=''562560''>greater</span>
  <span m=''562780''>than</span> <span m=''562880''>the</span> <span m=''562980''>upper</span>
  <span m=''563150''>bound,</span> <span m=''563710''>and</span> <span m=''564450''>if</span>
  <span m=''565120''>it</span> <span m=''565280''>is</span> <span m=''565460''>greater,</span>
  <span m=''565940''>then</span> <span m=''566120''>the</span> <span m=''566190''>result</span>
  <span m=''566570''>is</span> <span m=''566680''>zero.</span> <span m=''567590''>Otherwise,</span>
  <span m=''568240''>we''re</span> <span m=''568390''>going</span> <span m=''568660''>to</span>
  <span m=''569820''>do</span> <span m=''570110''>something</span> <span m=''570600''>to</span>
  <span m=''570730''>the</span> <span m=''570860''>lower</span> <span m=''571140''>bound,</span>
  <span m=''571640''>which</span> <span m=''571800''>is</span> <span m=''571890''>the</span>
  <span m=''572000''>index</span> <span m=''572890''>of</span> <span m=''573010''>the</span>
  <span m=''573090''>conversation,</span> <span m=''574590''>and</span> <span m=''575110''>add</span>
  <span m=''575340''>that</span> <span m=''575540''>result</span> <span m=''576670''>to</span>
  <span m=''578056''>the</span> <span m=''578520''>result</span> <span m=''579060''>of</span>
  <span m=''579240''>following</span> <span m=''579620''>the</span> <span m=''579730''>procedure</span>
  <span m=''580150''>recursively</span> <span m=''581700''>on</span> <span m=''582610''>our</span>
  <span m=''582900''>lower</span> <span m=''583390''>bound</span> <span m=''583730''>incremented</span>
  <span m=''584170''>by</span> <span m=''584580''>some</span> <span m=''584760''>next</span>
  <span m=''585050''>operation</span> <span m=''588050''>with</span> <span m=''588160''>the</span>
  <span m=''588280''>same</span> <span m=''588560''>upper</span> <span m=''588740''>bound
  as</span> <span m=''589050''>I had</span> <span m=''589350''>before.</span> </p><p><span
  m=''593710''>So</span> <span m=''593930''>this</span> <span m=''594150''>is</span>
  <span m=''594260''>a</span> <span m=''596070''>general</span> <span m=''596540''>pattern,</span>
  <span m=''597460''>and</span> <span m=''597880''>what</span> <span m=''598170''>I''d</span>
  <span m=''598300''>like</span> <span m=''598500''>to</span> <span m=''598590''>do</span>
  <span m=''598910''>is</span> <span m=''599070''>be</span> <span m=''599230''>able</span>
  <span m=''599360''>to</span> <span m=''599880''>name</span> <span m=''600240''>this</span>
  <span m=''600360''>general</span> <span m=''600700''>pattern</span> <span m=''601050''>a
  bit.</span> <span m=''603610''>Well, that''s</span> <span m=''603890''>sort</span>
  <span m=''604060''>of</span> <span m=''604130''>easy,</span> <span m=''605090''>because</span>
  <span m=''605690''>one</span> <span m=''605880''>of</span> <span m=''605960''>the</span>
  <span m=''606050''>things</span> <span m=''606320''>I''m</span> <span m=''606550''>going</span>
  <span m=''606790''>to</span> <span m=''607110''>do</span> <span m=''607350''>right</span>
  <span m=''607590''>now</span> <span m=''608070''>is--</span> <span m=''608390''>there''s</span>
  <span m=''608620''>nothing</span> <span m=''608940''>very</span> <span m=''609200''>special</span>
  <span m=''609610''>about</span> <span m=''609930''>numbers.</span> <span m=''611790''>Numbers</span>
  <span m=''612150''>are</span> <span m=''612220''>just</span> <span m=''612460''>one</span>
  <span m=''612700''>kind</span> <span m=''612870''>of</span> <span m=''613040''>data.</span>
  <span m=''614790''>It</span> <span m=''615020''>seems</span> <span m=''615290''>to</span>
  <span m=''615390''>me</span> <span m=''615580''>perfectly</span> <span m=''615990''>reasonable</span>
  <span m=''616580''>to</span> <span m=''616740''>give</span> <span m=''616970''>all</span>
  <span m=''617350''>sorts</span> <span m=''617570''>of</span> <span m=''617690''>names</span>
  <span m=''618550''>to</span> <span m=''619990''>all</span> <span m=''620140''>kinds</span>
  <span m=''620370''>of</span> <span m=''620420''>data,</span> <span m=''621350''>for</span>
  <span m=''621580''>example,</span> <span m=''621940''>procedures.</span> <span m=''623260''>And</span>
  <span m=''623460''>now</span> <span m=''623590''>many</span> <span m=''624090''>languages</span>
  <span m=''624560''>allow</span> <span m=''624820''>you</span> <span m=''624980''>have</span>
  <span m=''625150''>procedural</span> <span m=''625650''>arguments,</span> <span
  m=''626370''>and</span> <span m=''626530''>right</span> <span m=''626820''>now,</span>
  <span m=''627380''>we''re</span> <span m=''627510''>going</span> <span m=''627580''>to</span>
  <span m=''627650''>talk</span> <span m=''627830''>about</span> <span m=''628000''>procedural</span>
  <span m=''628430''>arguments.</span> <span m=''629120''>They''re</span> <span m=''629500''>very</span>
  <span m=''629730''>easy</span> <span m=''629910''>to</span> <span m=''629980''>deal</span>
  <span m=''630200''>with.</span> <span m=''631280''>And</span> <span m=''631380''>shortly,</span>
  <span m=''631690''>we''ll</span> <span m=''631850''>do</span> <span m=''631980''>some</span>
  <span m=''632160''>remarkable</span> <span m=''632670''>things</span> <span m=''632920''>that</span>
  <span m=''633000''>are</span> <span m=''633090''>not</span> <span m=''633300''>like</span>
  <span m=''633470''>procedural</span> <span m=''633890''>arguments.</span> </p><p><span
  m=''635730''>So</span> <span m=''635990''>here,</span> <span m=''636180''>we''ll</span>
  <span m=''636340''>define</span> <span m=''640820''>our</span> <span m=''641020''>sigma</span>
  <span m=''641393''>notation.</span> <span m=''643190''>This is</span> <span m=''643520''>called</span>
  <span m=''643850''>sum</span> <span m=''646030''>and it</span> <span m=''646420''>takes</span>
  <span m=''647140''>a</span> <span m=''648660''>term,</span> <span m=''652100''>an</span>
  <span m=''653170''>A,</span> <span m=''653850''>a</span> <span m=''654860''>next</span>
  <span m=''655450''>term,</span> <span m=''658548''>and</span> <span m=''659026''>B</span>
  <span m=''659510''>as</span> <span m=''659750''>arguments.</span> <span m=''660190''>So
  it</span> <span m=''660310''>takes</span> <span m=''660440''>four</span> <span m=''660710''>arguments,</span>
  <span m=''661910''>and</span> <span m=''662850''>there</span> <span m=''663040''>was</span>
  <span m=''663110''>nothing</span> <span m=''663420''>particularly</span> <span m=''663860''>special</span>
  <span m=''664280''>about</span> <span m=''664570''>me</span> <span m=''664690''>writing</span>
  <span m=''665000''>this</span> <span m=''665110''>in</span> <span m=''665220''>lowercase.</span>
  <span m=''666580''>I</span> <span m=''666680''>hope</span> <span m=''666910''>that</span>
  <span m=''667360''>it</span> <span m=''667480''>doesn''t</span> <span m=''667760''>confuse</span>
  <span m=''668170''>you, so</span> <span m=''668350''>I''ll</span> <span m=''668510''>write
  it in</span> <span m=''668700''>uppercase</span> <span m=''669180''>right</span>
  <span m=''669440''>now.</span> <span m=''669930''>The</span> <span m=''670200''>machine</span>
  <span m=''670400''>doesn''t</span> <span m=''670750''>care.</span> </p><p><span
  m=''674350''>But</span> <span m=''674830''>these</span> <span m=''675090''>two</span>
  <span m=''675320''>arguments</span> <span m=''676550''>are</span> <span m=''676720''>different.</span>
  <span m=''677180''>These</span> <span m=''677380''>are</span> <span m=''677450''>not</span>
  <span m=''677710''>numbers.</span> <span m=''679360''>These are</span> <span m=''679500''>going
  to</span> <span m=''679810''>be</span> <span m=''679930''>procedures</span> <span
  m=''681020''>for</span> <span m=''681150''>computing</span> <span m=''681600''>something</span>
  <span m=''681940''>given a</span> <span m=''682200''>number.</span> <span m=''683690''>Term</span>
  <span m=''683960''>will</span> <span m=''684100''>be</span> <span m=''684220''>a</span>
  <span m=''684270''>procedure</span> <span m=''684740''>which,</span> <span m=''684900''>when</span>
  <span m=''685350''>given an</span> <span m=''685720''>index,</span> <span m=''686590''>will</span>
  <span m=''686730''>produce</span> <span m=''687570''>the</span> <span m=''687680''>value</span>
  <span m=''688070''>of</span> <span m=''688150''>the</span> <span m=''688260''>term</span>
  <span m=''688500''>for</span> <span m=''688590''>that</span> <span m=''688760''>index.</span>
  <span m=''689920''>Next</span> <span m=''690470''>will</span> <span m=''690660''>be</span>
  <span m=''690850''>given an</span> <span m=''691150''>index, which</span> <span
  m=''691540''>will</span> <span m=''691660''>produce</span> <span m=''692070''>the</span>
  <span m=''692290''>next</span> <span m=''692510''>index.</span> <span m=''694050''>This</span>
  <span m=''694220''>will be</span> <span m=''694520''>for</span> <span m=''694610''>counting.</span>
  <span m=''696000''>And</span> <span m=''696300''>it''s</span> <span m=''696380''>very</span>
  <span m=''696680''>simple.</span> <span m=''700590''>It''s</span> <span m=''700790''>exactly</span>
  <span m=''701560''>what</span> <span m=''701720''>you</span> <span m=''701830''>see.</span>
  <span m=''703400''>If</span> <span m=''706670''>A</span> <span m=''707310''>is</span>
  <span m=''707550''>greater</span> <span m=''707900''>than</span> <span m=''708160''>B,</span>
  <span m=''709570''>then</span> <span m=''709860''>the</span> <span m=''709960''>result</span>
  <span m=''710530''>is</span> <span m=''710710''>0.</span> <span m=''712220''>Otherwise,</span>
  <span m=''713760''>it''s the</span> <span m=''714220''>sum</span> <span m=''715340''>of</span>
  <span m=''715790''>term</span> <span m=''718540''>applied</span> <span m=''718950''>to</span>
  <span m=''719050''>A</span> <span m=''721180''>and</span> <span m=''721650''>the</span>
  <span m=''722120''>sum</span> <span m=''724970''>of</span> <span m=''725210''>term,</span>
  <span m=''729550''>next</span> <span m=''730040''>index.</span> </p><p><span m=''734990''>Let</span>
  <span m=''735305''>me</span> <span m=''735620''>write</span> <span m=''735860''>it</span>
  <span m=''736070''>this</span> <span m=''736250''>way.</span> <span m=''749370''>Now,</span>
  <span m=''750070''>I''d</span> <span m=''750300''>like you</span> <span m=''750460''>to</span>
  <span m=''750620''>see</span> <span m=''750800''>something,</span> <span m=''751560''>first</span>
  <span m=''751760''>of</span> <span m=''751900''>all.</span> <span m=''752160''>I</span>
  <span m=''752390''>was</span> <span m=''752530''>writing</span> <span m=''752970''>here,
  and</span> <span m=''753260''>I</span> <span m=''753340''>ran</span> <span m=''753510''>out</span>
  <span m=''753610''>of</span> <span m=''753710''>space.</span> <span m=''755210''>What
  I</span> <span m=''755500''>did is</span> <span m=''755840''>I</span> <span m=''755900''>start</span>
  <span m=''756150''>indenting</span> <span m=''757510''>according</span> <span m=''757890''>to</span>
  <span m=''758000''>the</span> <span m=''758110''>Pretty-printing</span> <span m=''758630''>rule,</span>
  <span m=''759220''>which</span> <span m=''759400''>says</span> <span m=''759590''>that
  I</span> <span m=''759760''>align</span> <span m=''760620''>all</span> <span m=''760790''>of</span>
  <span m=''760970''>the</span> <span m=''761080''>arguments</span> <span m=''761500''>of</span>
  <span m=''761560''>the</span> <span m=''761660''>procedure</span> <span m=''763800''>so</span>
  <span m=''763950''>I</span> <span m=''764040''>can</span> <span m=''764210''>see</span>
  <span m=''764340''>which</span> <span m=''764960''>ones</span> <span m=''765140''>go</span>
  <span m=''765280''>together.</span> <span m=''767060''>And this</span> <span m=''767170''>is</span>
  <span m=''767320''>just</span> <span m=''767480''>something</span> <span m=''767790''>I</span>
  <span m=''767870''>do</span> <span m=''768010''>automatically,</span> <span m=''769175''>and
  I</span> <span m=''769670''>want</span> <span m=''769840''>you to</span> <span m=''769960''>learn</span>
  <span m=''770130''>how</span> <span m=''770200''>to</span> <span m=''770280''>do</span>
  <span m=''770390''>that,</span> <span m=''770590''>too,</span> <span m=''770720''>so</span>
  <span m=''770830''>your</span> <span m=''770970''>programs</span> <span m=''771300''>can</span>
  <span m=''771390''>be</span> <span m=''771530''>read and</span> <span m=''771850''>understood.</span>
  </p><p><span m=''774750''>However,</span> <span m=''776500''>what do</span> <span
  m=''776700''>we</span> <span m=''776880''>have</span> <span m=''777070''>here?</span>
  <span m=''777610''>We</span> <span m=''777800''>have</span> <span m=''778240''>four</span>
  <span m=''778470''>arguments:</span> <span m=''779690''>the</span> <span m=''779830''>procedure,</span>
  <span m=''780740''>the</span> <span m=''781010''>lower</span> <span m=''781310''>index--</span>
  <span m=''781730''>lower</span> <span m=''781920''>bound</span> <span m=''782200''>index--</span>
  <span m=''783670''>the</span> <span m=''783890''>way</span> <span m=''784050''>to</span>
  <span m=''784110''>get</span> <span m=''784270''>the</span> <span m=''784350''>next</span>
  <span m=''784620''>index,</span> <span m=''785680''>and the</span> <span m=''785910''>upper</span>
  <span m=''786110''>bound.</span> <span m=''789010''>What''s</span> <span m=''789220''>passed</span>
  <span m=''789520''>along</span> <span m=''790750''>on</span> <span m=''790940''>the</span>
  <span m=''790980''>recursive</span> <span m=''791450''>call</span> <span m=''792920''>is</span>
  <span m=''793090''>indeed</span> <span m=''793640''>the</span> <span m=''793890''>same</span>
  <span m=''794160''>procedure</span> <span m=''795420''>because I''m</span> <span
  m=''795695''>going to need it</span> <span m=''795970''>again,</span> <span m=''797830''>the</span>
  <span m=''798110''>next</span> <span m=''798400''>index,</span> <span m=''798830''>which</span>
  <span m=''798970''>is</span> <span m=''799040''>using</span> <span m=''799360''>the</span>
  <span m=''799440''>next</span> <span m=''799690''>procedure</span> <span m=''800030''>to</span>
  <span m=''800100''>compute</span> <span m=''800430''>it,</span> <span m=''801260''>the</span>
  <span m=''801550''>procedure</span> <span m=''801960''>for</span> <span m=''802050''>computing</span>
  <span m=''802460''>next,</span> <span m=''802700''>which</span> <span m=''802850''>I</span>
  <span m=''802900''>also</span> <span m=''803140''>have to have</span> <span m=''803430''>separately,</span>
  <span m=''803860''>and</span> <span m=''804010''>that''s</span> <span m=''804160''>different.</span>
  <span m=''805250''>The</span> <span m=''805380''>procedure</span> <span m=''805800''>for</span>
  <span m=''805900''>computing</span> <span m=''806340''>next</span> <span m=''807110''>is</span>
  <span m=''807320''>different</span> <span m=''807690''>from</span> <span m=''807810''>the</span>
  <span m=''807940''>next</span> <span m=''808210''>index,</span> <span m=''809200''>which</span>
  <span m=''809370''>is</span> <span m=''809460''>the</span> <span m=''809540''>result</span>
  <span m=''809890''>of</span> <span m=''809980''>using</span> <span m=''810240''>next</span>
  <span m=''810520''>on</span> <span m=''810620''>the</span> <span m=''810680''>last</span>
  <span m=''810970''>index.</span> <span m=''812510''>And</span> <span m=''812840''>I
  also have to</span> <span m=''812950''>pass</span> <span m=''813270''>along</span>
  <span m=''813470''>the</span> <span m=''813720''>upper</span> <span m=''813850''>bound.</span>
  <span m=''817090''>So</span> <span m=''817220''>this</span> <span m=''817480''>captures</span>
  <span m=''819710''>both</span> <span m=''820040''>of</span> <span m=''820160''>these</span>
  <span m=''820690''>and</span> <span m=''820900''>the</span> <span m=''821060''>other</span>
  <span m=''822100''>nice</span> <span m=''824450''>program</span> <span m=''824850''>that</span>
  <span m=''824940''>we</span> <span m=''825050''>are</span> <span m=''825110''>playing</span>
  <span m=''825410''>with.</span> </p><p><span m=''827810''>So</span> <span m=''828280''>using</span>
  <span m=''828810''>this,</span> <span m=''829190''>we</span> <span m=''829470''>can</span>
  <span m=''829620''>write</span> <span m=''829900''>down</span> <span m=''830390''>the</span>
  <span m=''830720''>original</span> <span m=''831140''>program</span> <span m=''832520''>as</span>
  <span m=''832740''>instances</span> <span m=''833910''>of</span> <span m=''834120''>sum</span>
  <span m=''835590''>very</span> <span m=''835830''>simply.</span> <span m=''848880''>A</span>
  <span m=''849330''>and</span> <span m=''849780''>B.</span> <span m=''855760''>Well,
  I''m</span> <span m=''856080''>going to need an</span> <span m=''856400''>identity</span>
  <span m=''857200''>procedure</span> <span m=''857620''>here</span> <span m=''859170''>because</span>
  <span m=''865710''>,ahh, the</span> <span m=''866130''>sum</span> <span m=''866440''>of</span>
  <span m=''866530''>the</span> <span m=''866650''>integers</span> <span m=''867690''>requires</span>
  <span m=''868320''>me</span> <span m=''868580''>to</span> <span m=''869270''>in</span>
  <span m=''869440''>this</span> <span m=''869650''>case</span> <span m=''870710''>compute
  a</span> <span m=''871070''>term</span> <span m=''871380''>for</span> <span m=''871500''>every</span>
  <span m=''871720''>integer,</span> <span m=''872520''>but</span> <span m=''872630''>the</span>
  <span m=''872750''>term</span> <span m=''873020''>procedure</span> <span m=''873350''>doesn''t</span>
  <span m=''873520''>want</span> <span m=''873770''>to do anything</span> <span m=''874080''>to</span>
  <span m=''874150''>that</span> <span m=''874330''>integer.</span> <span m=''875560''>So</span>
  <span m=''875860''>the</span> <span m=''876060''>identity</span> <span m=''876520''>procedure</span>
  <span m=''877000''>on</span> <span m=''877210''>A</span> <span m=''877690''>is A</span>
  <span m=''879420''>or</span> <span m=''879910''>X</span> <span m=''880220''>or</span>
  <span m=''880280''>whatever,</span> <span m=''881240''>and</span> <span m=''881350''>I</span>
  <span m=''881460''>want</span> <span m=''881570''>to</span> <span m=''881680''>say</span>
  <span m=''882360''>the</span> <span m=''882530''>sum</span> <span m=''884690''>of</span>
  <span m=''884900''>using</span> <span m=''885220''>identity</span> <span m=''885770''>of</span>
  <span m=''885890''>the</span> <span m=''885980''>term</span> <span m=''886230''>procedure</span>
  <span m=''892420''>and</span> <span m=''892600''>using</span> <span m=''892990''>A</span>
  <span m=''893260''>as</span> <span m=''893370''>the</span> <span m=''893500''>initial</span>
  <span m=''893830''>index</span> <span m=''895770''>and</span> <span m=''895930''>the</span>
  <span m=''896100''>incrementer</span> <span m=''898400''>being</span> <span m=''899760''>the</span>
  <span m=''899860''>way</span> <span m=''899980''>to</span> <span m=''900030''>get</span>
  <span m=''900210''>the</span> <span m=''900450''>next</span> <span m=''900780''>index</span>
  <span m=''902060''>and</span> <span m=''902390''>B</span> <span m=''902770''>being</span>
  <span m=''903830''>the</span> <span m=''905330''>high bound,</span> <span m=''906220''>the</span>
  <span m=''906280''>upper bound.</span> <span m=''907870''>This</span> <span m=''908160''>procedure</span>
  <span m=''908860''>does</span> <span m=''909040''>exactly</span> <span m=''909560''>the</span>
  <span m=''909690''>same</span> <span m=''910630''>as</span> <span m=''911420''>the</span>
  <span m=''911520''>sum</span> <span m=''911730''>of</span> <span m=''911860''>the</span>
  <span m=''912010''>integers</span> <span m=''912290''>over</span> <span m=''912520''>here,</span>
  <span m=''913090''>computes</span> <span m=''913390''>the</span> <span m=''913560''>same</span>
  <span m=''913800''>answer.</span> </p><p><span m=''917690''>Now,</span> <span m=''917880''>one</span>
  <span m=''918080''>thing</span> <span m=''919660''>you</span> <span m=''919790''>should</span>
  <span m=''920010''>see,</span> <span m=''920230''>of</span> <span m=''920500''>course,</span>
  <span m=''921070''>is</span> <span m=''921210''>that</span> <span m=''921300''>there''s</span>
  <span m=''921520''>nothing</span> <span m=''921840''>very</span> <span m=''922090''>special</span>
  <span m=''922700''>over</span> <span m=''922890''>here</span> <span m=''923580''>about</span>
  <span m=''924410''>what</span> <span m=''924670''>I</span> <span m=''924750''>used</span>
  <span m=''924930''>as</span> <span m=''925070''>the</span> <span m=''925220''>formal</span>
  <span m=''925540''>parameter.</span> <span m=''925990''>I</span> <span m=''926090''>could
  have,</span> <span m=''926340''>for</span> <span m=''926460''>example,</span> <span
  m=''926830''>written this</span> <span m=''927230''>X.</span> <span m=''927660''>It</span>
  <span m=''928066''>doesn''t matter.</span> <span m=''929690''>I</span> <span m=''929930''>just</span>
  <span m=''930090''>wanted</span> <span m=''930470''>you to</span> <span m=''930560''>see</span>
  <span m=''931110''>that</span> <span m=''931720''>this</span> <span m=''932450''>name</span>
  <span m=''932930''>does</span> <span m=''933130''>not</span> <span m=''933330''>conflict</span>
  <span m=''933760''>with</span> <span m=''933980''>this</span> <span m=''934260''>one</span>
  <span m=''934470''>at all.</span> <span m=''935140''>It''s an</span> <span m=''935370''>internal</span>
  <span m=''935760''>name.</span> </p><p><span m=''937850''>For</span> <span m=''937990''>the</span>
  <span m=''938200''>second</span> <span m=''938420''>procedure</span> <span m=''938810''>here,</span>
  <span m=''938960''>the</span> <span m=''939070''>sum</span> <span m=''939350''>of
  the</span> <span m=''939440''>squares,</span> <span m=''940370''>it''s</span> <span
  m=''940500''>even</span> <span m=''940650''>a</span> <span m=''940740''>little</span>
  <span m=''940940''>bit</span> <span m=''941080''>easier.</span> <span m=''953760''>And</span>
  <span m=''953870''>what do</span> <span m=''954030''>we</span> <span m=''954130''>have</span>
  <span m=''954290''>to</span> <span m=''954370''>do?</span> <span m=''954850''>Nothing</span>
  <span m=''955190''>more</span> <span m=''955440''>than</span> <span m=''955740''>add</span>
  <span m=''955950''>up</span> <span m=''957020''>the</span> <span m=''957700''>squares,</span>
  <span m=''961370''>this</span> <span m=''961740''>is</span> <span m=''961840''>the</span>
  <span m=''961950''>procedure</span> <span m=''962560''>that</span> <span m=''962830''>each</span>
  <span m=''963020''>index</span> <span m=''963380''>will</span> <span m=''963520''>be</span>
  <span m=''963640''>given,</span> <span m=''964390''>will</span> <span m=''964500''>be</span>
  <span m=''964710''>given</span> <span m=''964820''>each--</span> <span m=''965620''>yes.</span>
  <span m=''966780''>Each</span> <span m=''966990''>index</span> <span m=''967350''>will</span>
  <span m=''967590''>have</span> <span m=''967840''>this</span> <span m=''968030''>done
  to</span> <span m=''968370''>it</span> <span m=''968790''>to</span> <span m=''968910''>get</span>
  <span m=''969130''>the</span> <span m=''969240''>term.</span> <span m=''970410''>That''s</span>
  <span m=''970720''>the</span> <span m=''970790''>thing</span> <span m=''970970''>that</span>
  <span m=''971150''>maps</span> <span m=''971470''>against</span> <span m=''972060''>term
  over</span> <span m=''972470''>here.</span> <span m=''973570''>Then</span> <span
  m=''973770''>I</span> <span m=''973900''>have</span> <span m=''974070''>A as the</span>
  <span m=''974490''>lower</span> <span m=''974760''>bound,</span> <span m=''976520''>the</span>
  <span m=''976910''>incrementer</span> <span m=''978120''>as</span> <span m=''978620''>the</span>
  <span m=''978810''>next</span> <span m=''979010''>term</span> <span m=''979250''>method,</span>
  <span m=''980250''>and</span> <span m=''980490''>B</span> <span m=''980740''>as</span>
  <span m=''980860''>the</span> <span m=''980950''>upper</span> <span m=''981140''>bound.</span>
  </p><p><span m=''986780''>And</span> <span m=''987160''>finally,</span> <span m=''987620''>just</span>
  <span m=''987820''>for</span> <span m=''987900''>the</span> <span m=''988030''>thing</span>
  <span m=''988180''>that</span> <span m=''988270''>we</span> <span m=''988360''>did</span>
  <span m=''988490''>about</span> <span m=''988800''>pi</span> <span m=''989030''>sums,</span>
  <span m=''991220''>pi</span> <span m=''991410''>sums</span> <span m=''992360''>are</span>
  <span m=''992560''>sort</span> <span m=''992720''>of--</span> <span m=''993270''>well,</span>
  <span m=''993820''>it''s</span> <span m=''994070''>even</span> <span m=''994290''>easier</span>
  <span m=''994730''>to</span> <span m=''994790''>think</span> <span m=''994980''>about</span>
  <span m=''995230''>them</span> <span m=''995350''>this</span> <span m=''995540''>way</span>
  <span m=''995840''>because</span> <span m=''995950''>I</span> <span m=''996020''>don''t
  have to</span> <span m=''996320''>think.</span> <span m=''996610''>What I''m</span>
  <span m=''996770''>doing</span> <span m=''997060''>is</span> <span m=''997170''>separating</span>
  <span m=''999200''>the</span> <span m=''999330''>thing</span> <span m=''999540''>I''m</span>
  <span m=''999650''>adding</span> <span m=''999970''>up</span> <span m=''1000720''>from</span>
  <span m=''1001110''>the</span> <span m=''1001190''>method</span> <span m=''1001490''>of</span>
  <span m=''1001570''>doing the</span> <span m=''1001890''>addition.</span> <span
  m=''1003340''>And</span> <span m=''1003480''>so</span> <span m=''1003590''>we</span>
  <span m=''1003730''>have</span> <span m=''1003990''>here,</span> <span m=''1004160''>for</span>
  <span m=''1004360''>example,</span> <span m=''1013460''>pi</span> <span m=''1013720''>sum</span>
  <span m=''1014920''>A</span> <span m=''1015520''>B</span> <span m=''1017200''>of
  the</span> <span m=''1017450''>sum</span> <span m=''1017890''>of</span> <span m=''1018330''>things.</span>
  <span m=''1019890''>I''m</span> <span m=''1020020''>going to</span> <span m=''1020300''>write</span>
  <span m=''1020550''>the</span> <span m=''1020870''>terms</span> <span m=''1021410''>procedure</span>
  <span m=''1021910''>here</span> <span m=''1022700''>explicitly</span> <span m=''1023350''>without</span>
  <span m=''1023610''>giving</span> <span m=''1023840''>it</span> <span m=''1023920''>a</span>
  <span m=''1023980''>name.</span> <span m=''1025670''>This</span> <span m=''1025810''>is</span>
  <span m=''1025950''>done</span> <span m=''1026150''>anonymously.</span> <span m=''1027119''>I</span>
  <span m=''1027250''>don''t</span> <span m=''1027839''>necessarily</span> <span m=''1028270''>have</span>
  <span m=''1028430''>to</span> <span m=''1028630''>give a</span> <span m=''1028940''>name
  to</span> <span m=''1029220''>something</span> <span m=''1030630''>if</span> <span
  m=''1030770''>I</span> <span m=''1030960''>just want</span> <span m=''1031300''>to
  use it</span> <span m=''1031440''>once.</span> </p><p><span m=''1032310''>And,</span>
  <span m=''1033030''>of</span> <span m=''1033290''>course,</span> <span m=''1033619''>I</span>
  <span m=''1033760''>can</span> <span m=''1033940''>write</span> <span m=''1034210''>sort</span>
  <span m=''1034400''>of</span> <span m=''1034579''>a</span> <span m=''1035250''>expression</span>
  <span m=''1036609''>that</span> <span m=''1038050''>produces</span> <span m=''1038450''>a</span>
  <span m=''1038520''>procedure.</span> <span m=''1039579''>I''m</span> <span m=''1039710''>going</span>
  <span m=''1039890''>to</span> <span m=''1039990''>write</span> <span m=''1041170''>the</span>
  <span m=''1041420''>Greek</span> <span m=''1041730''>lambda</span> <span m=''1041810''>letter</span>
  <span m=''1042030''>here</span> <span m=''1042220''>instead</span> <span m=''1042420''>of</span>
  <span m=''1042740''>L-A-M-B-D-A</span> <span m=''1043710''>in</span> <span m=''1043819''>general</span>
  <span m=''1044390''>to</span> <span m=''1044560''>avoid</span> <span m=''1045220''>taking</span>
  <span m=''1045589''>up</span> <span m=''1045740''>a</span> <span m=''1045770''>lot</span>
  <span m=''1045869''>of</span> <span m=''1045960''>space</span> <span m=''1046220''>on</span>
  <span m=''1046349''>blackboards.</span> <span m=''1047240''>But</span> <span m=''1047400''>unfortunately,</span>
  <span m=''1047869''>we</span> <span m=''1047940''>don''t</span> <span m=''1048109''>have</span>
  <span m=''1048270''>lambda</span> <span m=''1048590''>keys</span> <span m=''1048840''>on</span>
  <span m=''1048950''>our</span> <span m=''1049060''>keyboards.</span> <span m=''1049960''>Maybe</span>
  <span m=''1050220''>we</span> <span m=''1050370''>can</span> <span m=''1050690''>convince</span>
  <span m=''1051300''>our</span> <span m=''1051450''>friends</span> <span m=''1051710''>in</span>
  <span m=''1051780''>the</span> <span m=''1051850''>computer</span> <span m=''1052170''>industry
  that</span> <span m=''1052520''>this</span> <span m=''1052800''>is</span> <span
  m=''1052860''>an</span> <span m=''1052920''>important.</span> <span m=''1054040''>Lambda</span>
  <span m=''1054380''>of</span> <span m=''1054570''>i</span> <span m=''1055960''>is</span>
  <span m=''1056160''>the</span> <span m=''1056320''>quotient</span> <span m=''1057295''>of</span>
  <span m=''1057710''>1</span> <span m=''1058310''>and</span> <span m=''1059560''>the</span>
  <span m=''1059720''>product</span> <span m=''1061394''>of</span> <span m=''1062340''>i</span>
  <span m=''1062730''>and</span> <span m=''1063230''>the</span> <span m=''1063480''>sum</span>
  <span m=''1063880''>of</span> <span m=''1064280''>i</span> <span m=''1064850''>2,</span>
  <span m=''1072550''>starting</span> <span m=''1072940''>at</span> <span m=''1073090''>a</span>
  <span m=''1073405''>with</span> <span m=''1073720''>the</span> <span m=''1075930''>way</span>
  <span m=''1076220''>of</span> <span m=''1076530''>incrementing</span> <span m=''1077370''>being</span>
  <span m=''1078020''>that</span> <span m=''1078330''>procedure</span> <span m=''1078780''>of</span>
  <span m=''1078980''>an</span> <span m=''1079060''>index</span> <span m=''1079490''>i,</span>
  <span m=''1080470''>which</span> <span m=''1080800''>adds</span> <span m=''1081560''>i</span>
  <span m=''1082250''>to 4,</span> <span m=''1086070''>and</span> <span m=''1086790''>b</span>
  <span m=''1087040''>being</span> <span m=''1088666''>the</span> <span m=''1089130''>upper</span>
  <span m=''1089370''>bound.</span> <span m=''1092270''>So</span> <span m=''1092810''>you</span>
  <span m=''1093030''>can</span> <span m=''1093170''>see</span> <span m=''1093860''>that</span>
  <span m=''1094230''>this</span> <span m=''1094410''>notation,</span> <span m=''1095730''>the</span>
  <span m=''1096200''>invention</span> <span m=''1096840''>of</span> <span m=''1097160''>the</span>
  <span m=''1097490''>procedure</span> <span m=''1098110''>that</span> <span m=''1098350''>takes</span>
  <span m=''1099200''>a</span> <span m=''1099420''>procedural</span> <span m=''1099960''>argument,</span>
  <span m=''1100860''>allows</span> <span m=''1101260''>us</span> <span m=''1101370''>to</span>
  <span m=''1101460''>compress</span> <span m=''1102800''>a</span> <span m=''1102940''>lot</span>
  <span m=''1103150''>of</span> <span m=''1103230''>these</span> <span m=''1103430''>procedures</span>
  <span m=''1103920''>into</span> <span m=''1104080''>one</span> <span m=''1104390''>thing.</span>
  <span m=''1106066''>This</span> <span m=''1107600''>procedure,</span> <span m=''1108320''>sums,</span>
  <span m=''1109120''>covers</span> <span m=''1109860''>a</span> <span m=''1109920''>whole</span>
  <span m=''1110090''>bunch</span> <span m=''1110390''>of</span> <span m=''1110510''>ideas.</span>
  </p><p><span m=''1112780''>Now,</span> <span m=''1112930''>just</span> <span m=''1113170''>why</span>
  <span m=''1113510''>is this</span> <span m=''1113710''>important?</span> <span m=''1114740''>I</span>
  <span m=''1114860''>tried</span> <span m=''1115130''>to</span> <span m=''1115200''>say</span>
  <span m=''1115350''>before</span> <span m=''1115700''>that it</span> <span m=''1115850''>helps</span>
  <span m=''1116070''>us</span> <span m=''1116150''>divide</span> <span m=''1116760''>a</span>
  <span m=''1116910''>problem</span> <span m=''1117220''>into</span> <span m=''1117370''>two</span>
  <span m=''1117540''>pieces,</span> <span m=''1118350''>and</span> <span m=''1118620''>indeed,</span>
  <span m=''1118820''>it</span> <span m=''1118910''>does,</span> <span m=''1120870''>for</span>
  <span m=''1121390''>example,</span> <span m=''1122200''>if</span> <span m=''1122390''>someone</span>
  <span m=''1122760''>came</span> <span m=''1122980''>up</span> <span m=''1123130''>with</span>
  <span m=''1123260''>a</span> <span m=''1123330''>different</span> <span m=''1123680''>way</span>
  <span m=''1124020''>of</span> <span m=''1124170''>implementing</span> <span m=''1124720''>this,</span>
  <span m=''1126400''>which,</span> <span m=''1126570''>of</span> <span m=''1126690''>course,</span>
  <span m=''1127630''>one</span> <span m=''1127960''>might.</span> <span m=''1130010''>Here,</span>
  <span m=''1130270''>for</span> <span m=''1130400''>example,</span> <span m=''1130900''>an</span>
  <span m=''1130990''>iterative</span> <span m=''1131230''>implementation</span> <span
  m=''1131850''>of</span> <span m=''1131910''>sum.</span> <span m=''1135900''>Iterative</span>
  <span m=''1136300''>implementation</span> <span m=''1137370''>for</span> <span m=''1137890''>some</span>
  <span m=''1138160''>reason</span> <span m=''1138590''>might</span> <span m=''1138890''>be</span>
  <span m=''1139020''>better</span> <span m=''1139470''>than</span> <span m=''1139870''>the</span>
  <span m=''1139960''>recursive</span> <span m=''1140530''>implementation.</span>
  <span m=''1143670''>But</span> <span m=''1143840''>the</span> <span m=''1143940''>important</span>
  <span m=''1144300''>thing</span> <span m=''1144490''>is</span> <span m=''1144620''>that
  it''s</span> <span m=''1144800''>different.</span> </p><p><span m=''1146460''>Now,</span>
  <span m=''1146660''>supposing</span> <span m=''1147200''>I</span> <span m=''1147320''>had</span>
  <span m=''1147430''>written</span> <span m=''1147670''>my</span> <span m=''1147820''>program</span>
  <span m=''1148370''>this</span> <span m=''1148560''>way</span> <span m=''1148950''>that</span>
  <span m=''1149200''>you</span> <span m=''1149460''>see</span> <span m=''1149640''>on</span>
  <span m=''1149750''>the</span> <span m=''1149860''>blackboard</span> <span m=''1151560''>on</span>
  <span m=''1151750''>the</span> <span m=''1151820''>left.</span> <span m=''1154310''>That''s</span>
  <span m=''1154530''>correct,</span> <span m=''1155025''>the</span> <span m=''1155520''>left.</span>
  <span m=''1157810''>Well,</span> <span m=''1157990''>then</span> <span m=''1158370''>if</span>
  <span m=''1158560''>I</span> <span m=''1158660''>want</span> <span m=''1158900''>to</span>
  <span m=''1159010''>change</span> <span m=''1159260''>the</span> <span m=''1159360''>method</span>
  <span m=''1159660''>of</span> <span m=''1159760''>addition,</span> <span m=''1161950''>then</span>
  <span m=''1162280''>I''d</span> <span m=''1162480''>have</span> <span m=''1162580''>to</span>
  <span m=''1162670''>change</span> <span m=''1162960''>each</span> <span m=''1163160''>of</span>
  <span m=''1163410''>these.</span> <span m=''1165200''>Whereas</span> <span m=''1165760''>if</span>
  <span m=''1165930''>I</span> <span m=''1166030''>write</span> <span m=''1166320''>them</span>
  <span m=''1166820''>like</span> <span m=''1167120''>this</span> <span m=''1167990''>that</span>
  <span m=''1168300''>you</span> <span m=''1168490''>see</span> <span m=''1168710''>here,</span>
  <span m=''1169480''>then</span> <span m=''1170210''>the</span> <span m=''1170300''>method</span>
  <span m=''1170660''>by</span> <span m=''1170800''>which</span> <span m=''1171000''>I</span>
  <span m=''1171070''>did</span> <span m=''1171220''>the</span> <span m=''1171300''>addition</span>
  <span m=''1171600''>is</span> <span m=''1171710''>encapsulated</span> <span m=''1172340''>in</span>
  <span m=''1172430''>the</span> <span m=''1172530''>procedure</span> <span m=''1172920''>sum.</span>
  <span m=''1174850''>That</span> <span m=''1175090''>decomposition</span> <span m=''1175870''>allows</span>
  <span m=''1176340''>me</span> <span m=''1176520''>to</span> <span m=''1176620''>independently</span>
  <span m=''1177250''>change</span> <span m=''1177590''>one</span> <span m=''1177780''>part</span>
  <span m=''1177900''>of</span> <span m=''1178030''>the</span> <span m=''1178110''>program</span>
  <span m=''1179880''>and</span> <span m=''1180110''>prove</span> <span m=''1180340''>it</span>
  <span m=''1180440''>perhaps</span> <span m=''1181540''>without</span> <span m=''1182850''>changing</span>
  <span m=''1183210''>the</span> <span m=''1183280''>other</span> <span m=''1183420''>part</span>
  <span m=''1184320''>that</span> <span m=''1184470''>was</span> <span m=''1184590''>written</span>
  <span m=''1184920''>for some of</span> <span m=''1185120''>the</span> <span m=''1185230''>other</span>
  <span m=''1186140''>cases.</span> <span m=''1190366''>Thank</span> <span m=''1190840''>you.</span>
  <span m=''1191010''>Are</span> <span m=''1191050''>there</span> <span m=''1191170''>any</span>
  <span m=''1191280''>questions?</span> <span m=''1192420''>Yes,</span> <span m=''1192700''>sir.</span>
  </p><p><span m=''1193190''>AUDIENCE: Would you go over next</span> <span m=''1193680''>A
  and next</span> <span m=''1194170''>again</span> <span m=''1194660''>on--</span>
  </p><p><span m=''1195150''>PROFESSOR: Yes.</span> <span m=''1195640''>It''s</span>
  <span m=''1195770''>the</span> <span m=''1195850''>same</span> <span m=''1196120''>problem.</span>
  <span m=''1196680''>I''m</span> <span m=''1196800''>sure</span> <span m=''1197070''>you''re
  going to--</span> <span m=''1197900''>you''re going to</span> <span m=''1198120''>have</span>
  <span m=''1198440''>to</span> <span m=''1198520''>work</span> <span m=''1198780''>on</span>
  <span m=''1198970''>this.</span> <span m=''1199160''>This</span> <span m=''1199290''>is</span>
  <span m=''1199380''>hard</span> <span m=''1200350''>the</span> <span m=''1200410''>first</span>
  <span m=''1200650''>time you''ve</span> <span m=''1200920''>ever</span> <span m=''1201080''>seen</span>
  <span m=''1201280''>something</span> <span m=''1201500''>like</span> <span m=''1201710''>this.</span>
  </p><p><span m=''1202460''>What</span> <span m=''1202610''>I</span> <span m=''1202690''>have</span>
  <span m=''1202950''>here</span> <span m=''1204160''>is</span> <span m=''1205000''>a--</span>
  <span m=''1205250''>procedures</span> <span m=''1206300''>can</span> <span m=''1206450''>be</span>
  <span m=''1206570''>named</span> <span m=''1206900''>by</span> <span m=''1207050''>variables.</span>
  <span m=''1210020''>Procedures</span> <span m=''1210830''>are</span> <span m=''1210880''>not</span>
  <span m=''1211150''>special.</span> <span m=''1212710''>Actually,</span> <span m=''1213170''>sum</span>
  <span m=''1213460''>square</span> <span m=''1213980''>is</span> <span m=''1214160''>a</span>
  <span m=''1214220''>variable,</span> <span m=''1214680''>which</span> <span m=''1214820''>has</span>
  <span m=''1214960''>gotten a</span> <span m=''1215230''>value,</span> <span m=''1217110''>which
  is</span> <span m=''1217300''>a</span> <span m=''1217490''>procedure.</span> <span
  m=''1218640''>This is</span> <span m=''1219100''>define</span> <span m=''1219440''>sum</span>
  <span m=''1219580''>square</span> <span m=''1219820''>to</span> <span m=''1219920''>be</span>
  <span m=''1220030''>lambda</span> <span m=''1220470''>of A</span> <span m=''1220640''>and</span>
  <span m=''1220770''>B</span> <span m=''1221000''>something.</span> <span m=''1223310''>So</span>
  <span m=''1223450''>the</span> <span m=''1223540''>procedure</span> <span m=''1223820''>can</span>
  <span m=''1223920''>be</span> <span m=''1224040''>named.</span> <span m=''1224700''>Therefore,</span>
  <span m=''1225170''>they</span> <span m=''1225300''>can</span> <span m=''1225410''>be</span>
  <span m=''1225500''>passed</span> <span m=''1225800''>from</span> <span m=''1225900''>one</span>
  <span m=''1227020''>to</span> <span m=''1227130''>another,</span> <span m=''1227660''>one</span>
  <span m=''1227900''>procedure</span> <span m=''1228240''>to</span> <span m=''1228370''>another,</span>
  <span m=''1229460''>as</span> <span m=''1230000''>arguments.</span> <span m=''1231430''>Well,
  what we''re</span> <span m=''1231710''>doing</span> <span m=''1231980''>here</span>
  <span m=''1232430''>is</span> <span m=''1232560''>we''re passing</span> <span m=''1233090''>the</span>
  <span m=''1233190''>procedure</span> <span m=''1233630''>term</span> <span m=''1234670''>as
  an</span> <span m=''1234920''>argument</span> <span m=''1235230''>to</span> <span
  m=''1235540''>sum</span> <span m=''1237180''>just</span> <span m=''1237420''>when</span>
  <span m=''1237490''>we</span> <span m=''1237680''>get it</span> <span m=''1237860''>around
  in</span> <span m=''1238190''>the</span> <span m=''1238250''>next</span> <span m=''1239200''>recursive.</span>
  </p><p><span m=''1241060''>Here,</span> <span m=''1241190''>we''re</span> <span
  m=''1241490''>passing</span> <span m=''1243540''>the</span> <span m=''1243700''>procedure</span>
  <span m=''1244080''>next</span> <span m=''1245350''>as</span> <span m=''1245910''>an</span>
  <span m=''1246140''>argument</span> <span m=''1246500''>also.</span> <span m=''1247630''>However,</span>
  <span m=''1247920''>here</span> <span m=''1248070''>we''re</span> <span m=''1248300''>using</span>
  <span m=''1248780''>the</span> <span m=''1248870''>procedure</span> <span m=''1249320''>next.</span>
  <span m=''1250120''>That''s what</span> <span m=''1250250''>the</span> <span m=''1250500''>parentheses</span>
  <span m=''1250750''>mean.</span> <span m=''1251690''>We''re</span> <span m=''1251940''>applying</span>
  <span m=''1252590''>next</span> <span m=''1252950''>to</span> <span m=''1253380''>A</span>
  <span m=''1254490''>to</span> <span m=''1254600''>get</span> <span m=''1254760''>the</span>
  <span m=''1254910''>next</span> <span m=''1255070''>value</span> <span m=''1255380''>of</span>
  <span m=''1255650''>A.</span> <span m=''1256590''>If</span> <span m=''1256750''>you</span>
  <span m=''1256860''>look</span> <span m=''1256950''>at</span> <span m=''1257040''>what</span>
  <span m=''1257200''>next</span> <span m=''1257500''>is</span> <span m=''1257600''>mapped</span>
  <span m=''1257900''>against,</span> <span m=''1258550''>remember</span> <span m=''1259090''>that</span>
  <span m=''1259390''>the way</span> <span m=''1259540''>you</span> <span m=''1259640''>think</span>
  <span m=''1259830''>about</span> <span m=''1260140''>this</span> <span m=''1260690''>is</span>
  <span m=''1260860''>that</span> <span m=''1261020''>you</span> <span m=''1261140''>substitute</span>
  <span m=''1261980''>the</span> <span m=''1262390''>arguments</span> <span m=''1263160''>for</span>
  <span m=''1263260''>the</span> <span m=''1263360''>formal</span> <span m=''1263770''>parameters</span>
  <span m=''1264360''>in</span> <span m=''1264450''>the</span> <span m=''1264530''>body.</span>
  <span m=''1266800''>If you''re</span> <span m=''1267220''>ever confused,</span>
  <span m=''1268930''>think of</span> <span m=''1269210''>the</span> <span m=''1269420''>thing</span>
  <span m=''1269610''>that</span> <span m=''1269850''>way.</span> </p><p><span m=''1270590''>Well,</span>
  <span m=''1271510''>over</span> <span m=''1271740''>here,</span> <span m=''1272690''>with</span>
  <span m=''1272880''>sum</span> <span m=''1273060''>of</span> <span m=''1273160''>the</span>
  <span m=''1273270''>integers.</span> <span m=''1274730''>I</span> <span m=''1275160''>substitute</span>
  <span m=''1275720''>identity</span> <span m=''1276610''>for a</span> <span m=''1276870''>term</span>
  <span m=''1279870''>and</span> <span m=''1280250''>1</span> <span m=''1280490''>plus</span>
  <span m=''1280950''>the</span> <span m=''1281150''>incrementer</span> <span m=''1281960''>for</span>
  <span m=''1282450''>next</span> <span m=''1284160''>in</span> <span m=''1284340''>the</span>
  <span m=''1284420''>body.</span> <span m=''1286070''>Well,</span> <span m=''1286210''>the</span>
  <span m=''1286330''>identity</span> <span m=''1286980''>procedure</span> <span m=''1288190''>on</span>
  <span m=''1288550''>A</span> <span m=''1288960''>is what</span> <span m=''1289220''>I</span>
  <span m=''1289280''>get</span> <span m=''1289480''>here.</span> <span m=''1290600''>Identity</span>
  <span m=''1290900''>is</span> <span m=''1291130''>being</span> <span m=''1291320''>passed</span>
  <span m=''1291620''>along,</span> <span m=''1294190''>and</span> <span m=''1294560''>here,</span>
  <span m=''1294840''>I</span> <span m=''1294910''>have</span> <span m=''1295170''>increment</span>
  <span m=''1295900''>1</span> <span m=''1296350''>plus</span> <span m=''1297550''>being</span>
  <span m=''1297750''>applied</span> <span m=''1298180''>to A</span> <span m=''1300210''>and</span>
  <span m=''1300410''>1</span> <span m=''1300630''>plus is</span> <span m=''1300800''>being</span>
  <span m=''1301040''>passed</span> <span m=''1301330''>along.</span> <span m=''1302980''>Does</span>
  <span m=''1303090''>that</span> <span m=''1303280''>clarify</span> <span m=''1304600''>the</span>
  <span m=''1305020''>situation?</span> </p><p><span m=''1306340''>AUDIENCE: We</span>
  <span m=''1306660''>could</span> <span m=''1306840''>also</span> <span m=''1307300''>define</span>
  <span m=''1308385''>explicitly</span> <span m=''1308870''>those two</span> <span
  m=''1309355''>functions,</span> <span m=''1309840''>then</span> <span m=''1310325''>pass  them.</span>
  </p><p><span m=''1311300''>PROFESSOR: Sure.</span> <span m=''1312360''>What</span>
  <span m=''1312530''>we</span> <span m=''1312640''>can</span> <span m=''1312750''>do</span>
  <span m=''1312870''>is</span> <span m=''1312930''>we</span> <span m=''1313040''>could</span>
  <span m=''1313140''>have</span> <span m=''1313250''>given</span> <span m=''1313510''>names</span>
  <span m=''1313870''>to</span> <span m=''1313980''>them,</span> <span m=''1314760''>just</span>
  <span m=''1314950''>like</span> <span m=''1315120''>I</span> <span m=''1315160''>did</span>
  <span m=''1315350''>here.</span> <span m=''1315770''>In fact,</span> <span m=''1315910''>I
  gave</span> <span m=''1316080''>you</span> <span m=''1316250''>various</span> <span
  m=''1316810''>ways</span> <span m=''1317310''>so</span> <span m=''1317410''>you</span>
  <span m=''1317530''>could</span> <span m=''1317620''>see</span> <span m=''1317850''>it,</span>
  <span m=''1318160''>a</span> <span m=''1318250''>variety.</span> <span m=''1319390''>Here,</span>
  <span m=''1319690''>I</span> <span m=''1319820''>define</span> <span m=''1320300''>the</span>
  <span m=''1320460''>thing</span> <span m=''1322010''>which</span> <span m=''1322200''>I</span>
  <span m=''1322310''>passed</span> <span m=''1322840''>the</span> <span m=''1323000''>name</span>
  <span m=''1323310''>of.</span> <span m=''1325130''>I</span> <span m=''1325450''>referenced</span>
  <span m=''1325740''>it</span> <span m=''1326030''>by</span> <span m=''1326170''>its</span>
  <span m=''1326360''>name.</span> <span m=''1327850''>But</span> <span m=''1328140''>the</span>
  <span m=''1328270''>thing</span> <span m=''1328520''>is,</span> <span m=''1328710''>in</span>
  <span m=''1328820''>fact,</span> <span m=''1329230''>that</span> <span m=''1329500''>procedure,</span>
  <span m=''1329890''>one</span> <span m=''1330070''>argument</span> <span m=''1330400''>X,</span>
  <span m=''1330760''>which</span> <span m=''1331110''>is</span> <span m=''1331220''>X.</span>
  <span m=''1332550''>And</span> <span m=''1332730''>the</span> <span m=''1332840''>identity</span>
  <span m=''1333200''>procedure</span> <span m=''1333480''>is</span> <span m=''1334030''>just</span>
  <span m=''1334300''>lambda</span> <span m=''1334710''>of</span> <span m=''1334940''>X</span>
  <span m=''1335420''>X.</span> <span m=''1338100''>And</span> <span m=''1338450''>that''s</span>
  <span m=''1338950''>what</span> <span m=''1339070''>you''re</span> <span m=''1339190''>seeing</span>
  <span m=''1339430''>here.</span> <span m=''1340870''>Here,</span> <span m=''1341020''>I</span>
  <span m=''1341230''>happened</span> <span m=''1341610''>to just</span> <span m=''1342040''>write</span>
  <span m=''1343560''>its</span> <span m=''1344020''>canonical</span> <span m=''1344620''>name</span>
  <span m=''1345630''>there</span> <span m=''1346060''>for</span> <span m=''1346190''>you</span>
  <span m=''1346300''>to</span> <span m=''1346410''>see.</span> <span m=''1351730''>Is
  it OK if</span> <span m=''1352160''>we</span> <span m=''1352590''>take our</span>
  <span m=''1352730''>five-minute</span> <span m=''1352870''>break?</span> </p><p><span
  m=''1395850''>As I</span> <span m=''1396070''>said,</span> <span m=''1397390''>computers</span>
  <span m=''1397900''>to</span> <span m=''1397990''>make</span> <span m=''1398210''>people</span>
  <span m=''1398490''>happy,</span> <span m=''1399330''>not</span> <span m=''1399560''>people</span>
  <span m=''1399740''>to</span> <span m=''1399780''>make</span> <span m=''1399960''>computers</span>
  <span m=''1400370''>happy.</span> <span m=''1401070''>And</span> <span m=''1401490''>for</span>
  <span m=''1401580''>the</span> <span m=''1401660''>most</span> <span m=''1401920''>part,</span>
  <span m=''1402180''>the</span> <span m=''1402250''>reason</span> <span m=''1402490''>why</span>
  <span m=''1402650''>we</span> <span m=''1402810''>introduce</span> <span m=''1402940''>all</span>
  <span m=''1403080''>this</span> <span m=''1403370''>abstraction</span> <span m=''1403960''>stuff</span>
  <span m=''1404640''>is</span> <span m=''1404850''>to</span> <span m=''1404930''>make</span>
  <span m=''1405110''>it</span> <span m=''1405230''>so</span> <span m=''1405410''>that</span>
  <span m=''1405740''>programs</span> <span m=''1406290''>can</span> <span m=''1406440''>be</span>
  <span m=''1406600''>more</span> <span m=''1406770''>easily</span> <span m=''1407030''>written</span>
  <span m=''1407350''>and</span> <span m=''1407500''>more</span> <span m=''1407670''>easily</span>
  <span m=''1407970''>read.</span> <span m=''1409940''>Let''s</span> <span m=''1410540''>try</span>
  <span m=''1410740''>to</span> <span m=''1410780''>understand</span> <span m=''1411370''>what''s</span>
  <span m=''1411700''>the</span> <span m=''1411860''>most</span> <span m=''1412010''>complicated</span>
  <span m=''1412560''>program</span> <span m=''1412930''>we''ve</span> <span m=''1413090''>seen</span>
  <span m=''1413330''>so</span> <span m=''1413510''>far</span> <span m=''1414420''>using</span>
  <span m=''1415000''>a</span> <span m=''1415210''>little</span> <span m=''1415420''>bit</span>
  <span m=''1415590''>of</span> <span m=''1416280''>this</span> <span m=''1416480''>abstraction</span>
  <span m=''1417070''>stuff.</span> </p><p><span m=''1418120''>If you</span> <span
  m=''1418430''>look</span> <span m=''1418580''>at</span> <span m=''1418730''>the</span>
  <span m=''1419510''>slide,</span> <span m=''1420300''>this</span> <span m=''1420500''>is</span>
  <span m=''1420650''>the</span> <span m=''1421960''>Heron</span> <span m=''1422680''>of</span>
  <span m=''1422800''>Alexandria''s</span> <span m=''1424560''>method</span> <span
  m=''1424850''>of</span> <span m=''1424910''>computing</span> <span m=''1425270''>square</span>
  <span m=''1425600''>roots that we</span> <span m=''1426010''>saw</span> <span m=''1428830''>yesterday.</span>
  <span m=''1431590''>And</span> <span m=''1433670''>let''s</span> <span m=''1433900''>see.</span>
  <span m=''1436460''>Well,</span> <span m=''1439010''>in</span> <span m=''1439150''>any</span>
  <span m=''1439340''>case,</span> <span m=''1439860''>this</span> <span m=''1440100''>program
  is</span> <span m=''1440440''>a</span> <span m=''1440510''>little</span> <span m=''1440780''>complicated.</span>
  <span m=''1441805''>And</span> <span m=''1442090''>at</span> <span m=''1442340''>the</span>
  <span m=''1442420''>current</span> <span m=''1442730''>state</span> <span m=''1443030''>of</span>
  <span m=''1443520''>your</span> <span m=''1443650''>thinking,</span> <span m=''1444270''>you
  just</span> <span m=''1444530''>can''t</span> <span m=''1444800''>look</span> <span
  m=''1444930''>at</span> <span m=''1445060''>that</span> <span m=''1445270''>and</span>
  <span m=''1445370''>say,</span> <span m=''1445700''>oh,</span> <span m=''1446130''>this</span>
  <span m=''1446340''>obviously</span> <span m=''1447000''>means</span> <span m=''1447320''>something</span>
  <span m=''1447690''>very</span> <span m=''1448700''>clear.</span> <span m=''1450380''>It''s</span>
  <span m=''1450640''>not</span> <span m=''1451090''>obvious</span> <span m=''1451570''>from</span>
  <span m=''1452140''>looking</span> <span m=''1452410''>at</span> <span m=''1452850''>the</span>
  <span m=''1452930''>program</span> <span m=''1454130''>what</span> <span m=''1454290''>it''s</span>
  <span m=''1454410''>computing.</span> <span m=''1457060''>There''s</span> <span
  m=''1457410''>some</span> <span m=''1457720''>loop</span> <span m=''1457890''>here</span>
  <span m=''1458640''>inside</span> <span m=''1459150''>try,</span> <span m=''1460680''>and</span>
  <span m=''1460990''>a</span> <span m=''1461130''>loop</span> <span m=''1461440''>does</span>
  <span m=''1461660''>something</span> <span m=''1461890''>about</span> <span m=''1462170''>trying</span>
  <span m=''1462620''>the</span> <span m=''1462740''>improvement</span> <span m=''1463830''>of</span>
  <span m=''1464090''>y.</span> <span m=''1466030''>There''s</span> <span m=''1467880''>something</span>
  <span m=''1468190''>called</span> <span m=''1468500''>improve,</span> <span m=''1469540''>which</span>
  <span m=''1469790''>does some</span> <span m=''1470170''>averaging</span> <span
  m=''1470840''>and</span> <span m=''1471280''>quotienting</span> <span m=''1471840''>and</span>
  <span m=''1472080''>things</span> <span m=''1472340''>like</span> <span m=''1472570''>that.</span>
  <span m=''1473270''>But</span> <span m=''1473550''>what''s</span> <span m=''1473810''>the</span>
  <span m=''1473970''>real</span> <span m=''1474290''>idea?</span> <span m=''1474840''>Can</span>
  <span m=''1475110''>we</span> <span m=''1475240''>make</span> <span m=''1475480''>it</span>
  <span m=''1475570''>clear</span> <span m=''1476050''>what</span> <span m=''1476220''>the</span>
  <span m=''1476340''>idea</span> <span m=''1476780''>is?</span> <span m=''1478930''>Well,</span>
  <span m=''1479090''>I</span> <span m=''1479190''>think</span> <span m=''1479410''>we</span>
  <span m=''1479550''>can.</span> <span m=''1481610''>I</span> <span m=''1481770''>think</span>
  <span m=''1481970''>we</span> <span m=''1482080''>can</span> <span m=''1482420''>use</span>
  <span m=''1482800''>abstraction</span> <span m=''1483730''>that</span> <span m=''1483910''>we</span>
  <span m=''1484010''>have</span> <span m=''1484180''>learned</span> <span m=''1484450''>about</span>
  <span m=''1484780''>so</span> <span m=''1485070''>far</span> <span m=''1485610''>to</span>
  <span m=''1486530''>clarify</span> <span m=''1487230''>what''s</span> <span m=''1487490''>going</span>
  <span m=''1487760''>on.</span> </p><p><span m=''1488990''>Now, what</span> <span
  m=''1489140''>we</span> <span m=''1489380''>have</span> <span m=''1490120''>mathematically</span>
  <span m=''1492610''>is</span> <span m=''1494090''>a</span> <span m=''1494250''>procedure</span>
  <span m=''1494720''>for</span> <span m=''1494930''>improving</span> <span m=''1495740''>a</span>
  <span m=''1495880''>guess</span> <span m=''1496190''>for</span> <span m=''1496310''>square</span>
  <span m=''1496650''>roots.</span> <span m=''1498411''>And</span> <span m=''1498860''>if</span>
  <span m=''1499440''>y</span> <span m=''1499870''>is a</span> <span m=''1500070''>guess</span>
  <span m=''1500330''>for a</span> <span m=''1500510''>square</span> <span m=''1500880''>root,</span>
  <span m=''1501870''>then</span> <span m=''1502060''>what</span> <span m=''1502220''>we</span>
  <span m=''1502350''>want</span> <span m=''1502610''>to</span> <span m=''1502700''>get</span>
  <span m=''1502990''>we''ll</span> <span m=''1503130''>call</span> <span m=''1503670''>a</span>
  <span m=''1503770''>function</span> <span m=''1504210''>f.</span> <span m=''1504570''>This</span>
  <span m=''1504870''>is</span> <span m=''1504970''>the</span> <span m=''1505040''>means</span>
  <span m=''1505300''>of</span> <span m=''1505380''>improvement.</span> <span m=''1507660''>I</span>
  <span m=''1507800''>want</span> <span m=''1507950''>to</span> <span m=''1508110''>get</span>
  <span m=''1508690''>y</span> <span m=''1509850''>plus</span> <span m=''1511190''>x/y</span>
  <span m=''1512970''>over</span> <span m=''1513240''>2,</span> <span m=''1514110''>so</span>
  <span m=''1514500''>the</span> <span m=''1514790''>average</span> <span m=''1516240''>of</span>
  <span m=''1516430''>y</span> <span m=''1516910''>and</span> <span m=''1517130''>x</span>
  <span m=''1517510''>divided</span> <span m=''1517920''>by</span> <span m=''1518070''>y</span>
  <span m=''1519880''>as</span> <span m=''1520230''>the</span> <span m=''1520470''>improved</span>
  <span m=''1520870''>value</span> <span m=''1521340''>for</span> <span m=''1521470''>the</span>
  <span m=''1521550''>square</span> <span m=''1521850''>root</span> <span m=''1522100''>of</span>
  <span m=''1522230''>x</span> <span m=''1524080''>such</span> <span m=''1524490''>that--</span>
  <span m=''1524970''>one</span> <span m=''1525210''>thing</span> <span m=''1525330''>you</span>
  <span m=''1525450''>can</span> <span m=''1525630''>notice</span> <span m=''1525940''>about</span>
  <span m=''1526210''>this</span> <span m=''1526410''>function</span> <span m=''1526780''>f</span>
  <span m=''1527920''>is</span> <span m=''1528160''>that</span> <span m=''1528840''>f</span>
  <span m=''1529030''>of</span> <span m=''1529140''>the</span> <span m=''1529220''>square
  root of</span> <span m=''1529600''>f</span> <span m=''1534820''>is</span> <span
  m=''1535290''>in</span> <span m=''1535520''>fact</span> <span m=''1536220''>the</span>
  <span m=''1536310''>square root of</span> <span m=''1536760''>x.</span> <span m=''1538460''>In
  other words,</span> <span m=''1538900''>if</span> <span m=''1539360''>I</span> <span
  m=''1539490''>take</span> <span m=''1539990''>the</span> <span m=''1540090''>square
  root</span> <span m=''1540390''>of</span> <span m=''1540510''>x</span> <span m=''1541420''>and</span>
  <span m=''1541670''>substitute it</span> <span m=''1542120''>for</span> <span m=''1542200''>y</span>
  <span m=''1542520''>here,</span> <span m=''1543440''>I</span> <span m=''1543590''>see</span>
  <span m=''1543720''>the</span> <span m=''1543800''>square root of</span> <span m=''1544210''>x</span>
  <span m=''1544600''>plus</span> <span m=''1544930''>x</span> <span m=''1545140''>divided</span>
  <span m=''1545520''>by</span> <span m=''1545610''>the</span> <span m=''1545700''>square</span>
  <span m=''1545960''>of</span> <span m=''1546030''>x,</span> <span m=''1546320''>which</span>
  <span m=''1546490''>is</span> <span m=''1546570''>the square</span> <span m=''1546700''>root
  of</span> <span m=''1546940''>x.</span> <span m=''1547560''>That''s</span> <span
  m=''1547880''>2</span> <span m=''1548040''>times the</span> <span m=''1548410''>square
  root of</span> <span m=''1548720''>x</span> <span m=''1549040''>divided</span> <span
  m=''1549110''>by</span> <span m=''1549320''>2,</span> <span m=''1549470''>is</span>
  <span m=''1549690''>the</span> <span m=''1549890''>square root of</span> <span m=''1550235''>x.</span>
  </p><p><span m=''1551640''>So,</span> <span m=''1551870''>in</span> <span m=''1552010''>fact,</span>
  <span m=''1553440''>what</span> <span m=''1553630''>we''re</span> <span m=''1553800''>really</span>
  <span m=''1554050''>looking</span> <span m=''1554370''>for</span> <span m=''1554960''>is</span>
  <span m=''1555140''>we''re</span> <span m=''1555310''>looking</span> <span m=''1555630''>for</span>
  <span m=''1555810''>a</span> <span m=''1555870''>fixed</span> <span m=''1556230''>point,</span>
  <span m=''1561330''>a</span> <span m=''1561880''>fixed</span> <span m=''1562260''>point</span>
  <span m=''1571450''>of</span> <span m=''1571880''>the</span> <span m=''1571970''>function</span>
  <span m=''1572400''>f.</span> <span m=''1577570''>A</span> <span m=''1577700''>fixed</span>
  <span m=''1577990''>point</span> <span m=''1578970''>is</span> <span m=''1579150''>a</span>
  <span m=''1579210''>place</span> <span m=''1580420''>which</span> <span m=''1580630''>has</span>
  <span m=''1580840''>the</span> <span m=''1580940''>property</span> <span m=''1582250''>that</span>
  <span m=''1582460''>if</span> <span m=''1582540''>you</span> <span m=''1582650''>put
  it</span> <span m=''1582900''>into</span> <span m=''1583190''>the</span> <span m=''1583280''>function,</span>
  <span m=''1583790''>you get</span> <span m=''1583880''>the</span> <span m=''1583940''>same</span>
  <span m=''1584170''>value</span> <span m=''1584480''>out.</span> <span m=''1587620''>Now,</span>
  <span m=''1587760''>I</span> <span m=''1587840''>suppose</span> <span m=''1588125''>if</span>
  <span m=''1588410''>I</span> <span m=''1588480''>were giving</span> <span m=''1588980''>some
  nice,</span> <span m=''1589360''>boring</span> <span m=''1589700''>lecture,</span>
  <span m=''1590180''>and</span> <span m=''1590280''>you</span> <span m=''1590370''>happened</span>
  <span m=''1590670''>to have</span> <span m=''1590790''>in</span> <span m=''1590880''>front</span>
  <span m=''1591080''>of</span> <span m=''1591180''>you</span> <span m=''1591750''>an</span>
  <span m=''1592930''>HP-35</span> <span m=''1594480''>desk</span> <span m=''1594710''>calculator</span>
  <span m=''1595450''>like</span> <span m=''1595650''>I</span> <span m=''1595710''>used</span>
  <span m=''1595820''>to</span> <span m=''1595930''>have</span> <span m=''1596200''>when</span>
  <span m=''1596320''>I</span> <span m=''1596380''>went to</span> <span m=''1596550''>boring</span>
  <span m=''1596850''>lectures.</span> <span m=''1598170''>And</span> <span m=''1598540''>if</span>
  <span m=''1598790''>you</span> <span m=''1599070''>think</span> <span m=''1599260''>it
  was</span> <span m=''1599360''>really</span> <span m=''1599570''>boring,</span>
  <span m=''1599840''>you</span> <span m=''1600650''>put it</span> <span m=''1600800''>into</span>
  <span m=''1601120''>radians</span> <span m=''1601550''>mode,</span> <span m=''1601960''>and</span>
  <span m=''1602255''>you</span> <span m=''1602550''>hit</span> <span m=''1602790''>cosine,</span>
  <span m=''1603330''>and</span> <span m=''1603590''>you</span> <span m=''1603850''>hit</span>
  <span m=''1604180''>cosine,</span> <span m=''1604720''>and</span> <span m=''1605060''>you
  hit</span> <span m=''1605240''>cosine.</span> <span m=''1605780''>And</span> <span
  m=''1606100''>eventually,</span> <span m=''1606620''>you</span> <span m=''1606740''>end</span>
  <span m=''1606950''>up</span> <span m=''1607110''>with</span> <span m=''1607400''>0.734</span>
  <span m=''1608710''>or</span> <span m=''1608770''>something</span> <span m=''1609110''>like</span>
  <span m=''1609370''>that.</span> <span m=''1610090''>0.743,</span> <span m=''1610980''>I
  don''t</span> <span m=''1611060''>remember</span> <span m=''1611380''>what</span>
  <span m=''1611620''>exactly,</span> <span m=''1612250''>and</span> <span m=''1612460''>it</span>
  <span m=''1612690''>gets</span> <span m=''1612870''>closer</span> <span m=''1613250''>and</span>
  <span m=''1613310''>closer</span> <span m=''1613640''>to</span> <span m=''1613710''>that.</span>
  <span m=''1614810''>Some</span> <span m=''1615140''>functions</span> <span m=''1615660''>have</span>
  <span m=''1615830''>the</span> <span m=''1615910''>property</span> <span m=''1616920''>that</span>
  <span m=''1617270''>you</span> <span m=''1617370''>can</span> <span m=''1617550''>find</span>
  <span m=''1617980''>their fixed</span> <span m=''1618400''>point</span> <span m=''1619250''>by</span>
  <span m=''1619560''>iterating</span> <span m=''1620260''>the</span> <span m=''1620450''>function,</span>
  <span m=''1622990''>and</span> <span m=''1623230''>that''s</span> <span m=''1623420''>essentially</span>
  <span m=''1623920''>what''s</span> <span m=''1624120''>happening</span> <span m=''1625850''>in</span>
  <span m=''1626030''>the</span> <span m=''1626120''>square</span> <span m=''1626510''>root</span>
  <span m=''1626550''>program</span> <span m=''1627020''>by</span> <span m=''1627170''>Heron''s</span>
  <span m=''1627550''>method.</span> </p><p><span m=''1631550''>So</span> <span m=''1631750''>let''s</span>
  <span m=''1631950''>see</span> <span m=''1632060''>if</span> <span m=''1632140''>we</span>
  <span m=''1632240''>can</span> <span m=''1632390''>write</span> <span m=''1632660''>that</span>
  <span m=''1632920''>down,</span> <span m=''1633200''>that</span> <span m=''1633420''>idea.</span>
  <span m=''1634732''>Now,</span> <span m=''1635140''>I''m</span> <span m=''1635350''>not</span>
  <span m=''1635500''>going</span> <span m=''1635570''>to</span> <span m=''1635640''>say</span>
  <span m=''1635940''>how</span> <span m=''1636140''>I</span> <span m=''1636220''>compute</span>
  <span m=''1636610''>fixed</span> <span m=''1636800''>points</span> <span m=''1637090''>yet.</span>
  <span m=''1637670''>There</span> <span m=''1637760''>might</span> <span m=''1637940''>be</span>
  <span m=''1638020''>more</span> <span m=''1638200''>than</span> <span m=''1638330''>one</span>
  <span m=''1638550''>way.</span> <span m=''1639240''>But</span> <span m=''1639710''>the</span>
  <span m=''1639890''>first</span> <span m=''1640080''>thing</span> <span m=''1640240''>to</span>
  <span m=''1640320''>do</span> <span m=''1641470''>is</span> <span m=''1641650''>I''m</span>
  <span m=''1641790''>going</span> <span m=''1641950''>to</span> <span m=''1642750''>say</span>
  <span m=''1643120''>what</span> <span m=''1643230''>I</span> <span m=''1643340''>just</span>
  <span m=''1643670''>said.</span> <span m=''1644310''>I''m going to</span> <span
  m=''1644490''>say</span> <span m=''1644630''>it</span> <span m=''1645900''>specifically,</span>
  <span m=''1646790''>the</span> <span m=''1646880''>square</span> <span m=''1647150''>root.</span>
  <span m=''1652440''>The</span> <span m=''1652520''>square root of</span> <span m=''1653010''>x</span>
  <span m=''1656480''>is</span> <span m=''1656630''>the</span> <span m=''1656730''>fixed</span>
  <span m=''1657020''>point</span> <span m=''1663990''>of</span> <span m=''1664500''>that</span>
  <span m=''1664970''>procedure</span> <span m=''1668210''>which</span> <span m=''1668460''>takes</span>
  <span m=''1669150''>an</span> <span m=''1669340''>argument</span> <span m=''1669790''>y</span>
  <span m=''1671016''>and</span> <span m=''1671400''>averages</span> <span m=''1678290''>of</span>
  <span m=''1678780''>x</span> <span m=''1679180''>divided</span> <span m=''1679570''>by</span>
  <span m=''1679720''>y</span> <span m=''1681840''>with</span> <span m=''1682020''>y.</span>
  <span m=''1685620''>And</span> <span m=''1685810''>we''re</span> <span m=''1685930''>going
  to</span> <span m=''1686140''>start</span> <span m=''1686450''>up</span> <span m=''1686730''>with</span>
  <span m=''1686890''>the</span> <span m=''1687050''>initial</span> <span m=''1687390''>guess</span>
  <span m=''1687650''>for</span> <span m=''1687910''>the</span> <span m=''1688120''>fixed</span>
  <span m=''1688350''>point</span> <span m=''1689040''>of</span> <span m=''1689340''>1.</span>
  <span m=''1689630''>It</span> <span m=''1689920''>doesn''t</span> <span m=''1690200''>matter</span>
  <span m=''1690450''>where</span> <span m=''1690630''>it</span> <span m=''1690750''>starts.</span>
  <span m=''1691860''>A</span> <span m=''1691980''>theorem</span> <span m=''1692660''>having</span>
  <span m=''1692930''>to</span> <span m=''1693020''>do</span> <span m=''1693130''>with</span>
  <span m=''1693250''>square</span> <span m=''1693520''>roots.</span> </p><p><span
  m=''1698610''>So</span> <span m=''1698780''>what you''re</span> <span m=''1699010''>seeing</span>
  <span m=''1699340''>here is</span> <span m=''1699600''>I''m</span> <span m=''1699710''>just</span>
  <span m=''1699820''>trying</span> <span m=''1700050''>to</span> <span m=''1700150''>write</span>
  <span m=''1700430''>out</span> <span m=''1701410''>by</span> <span m=''1701750''>wishful</span>
  <span m=''1702190''>thinking.</span> <span m=''1702560''>I</span> <span m=''1702700''>don''t</span>
  <span m=''1702830''>know</span> <span m=''1702900''>how</span> <span m=''1703180''>I''m</span>
  <span m=''1703250''>going to</span> <span m=''1703430''>make</span> <span m=''1703560''>fixed</span>
  <span m=''1703850''>point</span> <span m=''1704050''>happen.</span> <span m=''1704380''>We''ll</span>
  <span m=''1704750''>worry</span> <span m=''1705010''>about</span> <span m=''1705230''>that</span>
  <span m=''1705420''>later.</span> <span m=''1706290''>But</span> <span m=''1706510''>if</span>
  <span m=''1706610''>somehow</span> <span m=''1707310''>I</span> <span m=''1707420''>had</span>
  <span m=''1707620''>a</span> <span m=''1707660''>way</span> <span m=''1708110''>of</span>
  <span m=''1708260''>finding</span> <span m=''1708500''>the</span> <span m=''1708600''>fixed</span>
  <span m=''1708880''>point</span> <span m=''1709290''>of</span> <span m=''1709430''>the</span>
  <span m=''1709570''>function</span> <span m=''1709950''>computed</span> <span m=''1710360''>by</span>
  <span m=''1710510''>this</span> <span m=''1710740''>procedure,</span> <span m=''1712580''>then</span>
  <span m=''1712970''>I</span> <span m=''1713100''>would</span> <span m=''1713350''>have--</span>
  <span m=''1713590''>that</span> <span m=''1713830''>would</span> <span m=''1713960''>be</span>
  <span m=''1714090''>the</span> <span m=''1714220''>square</span> <span m=''1714550''>root</span>
  <span m=''1715310''>that I''m</span> <span m=''1715560''>looking</span> <span m=''1715820''>for.</span>
  </p><p><span m=''1719770''>OK,</span> <span m=''1720020''>well,</span> <span m=''1720370''>now
  let''s</span> <span m=''1720510''>see</span> <span m=''1720640''>how</span> <span
  m=''1720760''>we''re</span> <span m=''1720820''>going</span> <span m=''1720890''>to</span>
  <span m=''1720970''>write--</span> <span m=''1721500''>how</span> <span m=''1721670''>we''re</span>
  <span m=''1721760''>going</span> <span m=''1721840''>to</span> <span m=''1721910''>come</span>
  <span m=''1722030''>up</span> <span m=''1722130''>with</span> <span m=''1722250''>fixed</span>
  <span m=''1722490''>points.</span> <span m=''1723470''>Well, it''s</span> <span
  m=''1723680''>very</span> <span m=''1724040''>simple,</span> <span m=''1724410''>actually.</span>
  <span m=''1724890''>I''m</span> <span m=''1725030''>going</span> <span m=''1725110''>to</span>
  <span m=''1725190''>write</span> <span m=''1725730''>an</span> <span m=''1725850''>abbreviated</span>
  <span m=''1726430''>version</span> <span m=''1726750''>here</span> <span m=''1726960''>just</span>
  <span m=''1727180''>so</span> <span m=''1727270''>we</span> <span m=''1727420''>understand</span>
  <span m=''1727870''>it.</span> <span m=''1740450''>I''m</span> <span m=''1740500''>going
  to</span> <span m=''1740700''>find</span> <span m=''1740900''>the</span> <span m=''1740950''>fixed</span>
  <span m=''1741200''>point</span> <span m=''1741470''>of</span> <span m=''1741570''>a</span>
  <span m=''1741620''>function</span> <span m=''1742350''>f--</span> <span m=''1743310''>actually,</span>
  <span m=''1743740''>the</span> <span m=''1744460''>fixed</span> <span m=''1744680''>point</span>
  <span m=''1744890''>of</span> <span m=''1744950''>the</span> <span m=''1745020''>function</span>
  <span m=''1745410''>computed</span> <span m=''1745870''>by</span> <span m=''1746010''>the</span>
  <span m=''1746140''>procedure</span> <span m=''1746660''>whose</span> <span m=''1746900''>name</span>
  <span m=''1747140''>will</span> <span m=''1747250''>be</span> <span m=''1747420''>f</span>
  <span m=''1747690''>in</span> <span m=''1747870''>this</span> <span m=''1748050''>procedure.</span>
  <span m=''1749990''>How''s</span> <span m=''1750240''>that?</span> <span m=''1751025''>A</span>
  <span m=''1751390''>long</span> <span m=''1751650''>sentence--</span> <span m=''1753230''>starting</span>
  <span m=''1753570''>with</span> <span m=''1753640''>a</span> <span m=''1753770''>particular</span>
  <span m=''1754030''>starting</span> <span m=''1754360''>value.</span> </p><p><span
  m=''1759920''>Well,</span> <span m=''1760100''>I''m</span> <span m=''1760140''>going
  to</span> <span m=''1760410''>have</span> <span m=''1760530''>a</span> <span m=''1760640''>little</span>
  <span m=''1760910''>loop</span> <span m=''1761200''>inside</span> <span m=''1761610''>here,</span>
  <span m=''1762470''>which</span> <span m=''1762660''>is</span> <span m=''1762760''>going</span>
  <span m=''1762980''>to</span> <span m=''1763060''>push</span> <span m=''1763260''>the</span>
  <span m=''1763380''>button</span> <span m=''1763730''>on</span> <span m=''1763840''>the</span>
  <span m=''1763910''>calculator</span> <span m=''1765020''>repeatedly,</span> <span
  m=''1765800''>hoping</span> <span m=''1766370''>that it</span> <span m=''1766520''>will</span>
  <span m=''1766650''>eventually</span> <span m=''1767070''>converge.</span> <span
  m=''1768940''>And we will</span> <span m=''1769430''>say</span> <span m=''1769620''>here</span>
  <span m=''1773700''>internal</span> <span m=''1774110''>loops</span> <span m=''1774450''>are</span>
  <span m=''1774530''>written</span> <span m=''1774790''>by</span> <span m=''1774930''>defining</span>
  <span m=''1775290''>internal</span> <span m=''1775570''>procedures.</span> <span
  m=''1779340''>Well,</span> <span m=''1779600''>one</span> <span m=''1779800''>thing</span>
  <span m=''1779960''>I''m</span> <span m=''1780050''>going</span> <span m=''1780100''>to</span>
  <span m=''1780150''>have</span> <span m=''1780270''>to</span> <span m=''1780390''>do</span>
  <span m=''1780940''>is</span> <span m=''1781550''>I''m</span> <span m=''1781730''>going</span>
  <span m=''1781800''>to</span> <span m=''1781860''>have</span> <span m=''1781950''>to</span>
  <span m=''1782020''>say</span> <span m=''1782230''>whether</span> <span m=''1782430''>I''m</span>
  <span m=''1782530''>done.</span> <span m=''1783690''>And the way I''m going to</span>
  <span m=''1784070''>decide</span> <span m=''1784390''>when</span> <span m=''1784520''>I''m</span>
  <span m=''1784630''>done</span> <span m=''1784870''>is</span> <span m=''1785000''>when</span>
  <span m=''1785410''>the</span> <span m=''1785670''>old</span> <span m=''1785930''>value</span>
  <span m=''1786420''>and</span> <span m=''1786510''>the</span> <span m=''1786600''>new</span>
  <span m=''1786730''>value</span> <span m=''1787050''>are</span> <span m=''1787140''>close</span>
  <span m=''1787390''>enough</span> <span m=''1787580''>so</span> <span m=''1787690''>I</span>
  <span m=''1787760''>can''t</span> <span m=''1787990''>distinguish</span> <span m=''1788390''>them</span>
  <span m=''1788540''>anymore.</span> <span m=''1790820''>That''s</span> <span m=''1791150''>the</span>
  <span m=''1791200''>standard</span> <span m=''1791490''>thing</span> <span m=''1791640''>you</span>
  <span m=''1791720''>do</span> <span m=''1791870''>on</span> <span m=''1791970''>the</span>
  <span m=''1792040''>calculator</span> <span m=''1793300''>unless</span> <span m=''1793510''>you</span>
  <span m=''1793610''>look</span> <span m=''1793750''>at</span> <span m=''1793830''>more</span>
  <span m=''1794010''>precision,</span> <span m=''1794430''>and</span> <span m=''1794550''>eventually,</span>
  <span m=''1794970''>you</span> <span m=''1795070''>run</span> <span m=''1795210''>out</span>
  <span m=''1795290''>of</span> <span m=''1795370''>precision.</span> </p><p><span
  m=''1797820''>So</span> <span m=''1801250''>the</span> <span m=''1801740''>old</span>
  <span m=''1802010''>value</span> <span m=''1802470''>and</span> <span m=''1802680''>new</span>
  <span m=''1802830''>value,</span> <span m=''1805376''>and</span> <span m=''1805870''>I''m</span>
  <span m=''1806100''>going</span> <span m=''1806200''>to</span> <span m=''1806310''>stay</span>
  <span m=''1806530''>here</span> <span m=''1807040''>if</span> <span m=''1808650''>I</span>
  <span m=''1808810''>can''t</span> <span m=''1809050''>distinguish</span> <span m=''1809440''>them</span>
  <span m=''1809610''>if</span> <span m=''1809700''>they''re</span> <span m=''1809860''>close</span>
  <span m=''1810160''>enough,</span> <span m=''1814758''>and</span> <span m=''1815240''>we''ll</span>
  <span m=''1815530''>have</span> <span m=''1815660''>to</span> <span m=''1815740''>worry</span>
  <span m=''1815910''>about</span> <span m=''1816070''>what</span> <span m=''1816170''>that</span>
  <span m=''1816360''>is</span> <span m=''1816500''>soon.</span> <span m=''1820780''>The</span>
  <span m=''1820840''>old</span> <span m=''1821100''>value</span> <span m=''1821250''>and</span>
  <span m=''1821380''>the</span> <span m=''1821450''>new</span> <span m=''1821620''>value
  are</span> <span m=''1821930''>close</span> <span m=''1822210''>enough</span> <span
  m=''1822380''>to</span> <span m=''1822480''>each  other</span> <span m=''1822680''>and</span>
  <span m=''1822790''>let''s</span> <span m=''1822970''>pick</span> <span m=''1823130''>the</span>
  <span m=''1823190''>new</span> <span m=''1823350''>value</span> <span m=''1823740''>as
  the</span> <span m=''1823870''>answer.</span> <span m=''1825880''>Otherwise,</span>
  <span m=''1827310''>I''m</span> <span m=''1827460''>going</span> <span m=''1827630''>to</span>
  <span m=''1827900''>iterate</span> <span m=''1827970''>around</span> <span m=''1828280''>again</span>
  <span m=''1831420''>with</span> <span m=''1832000''>the</span> <span m=''1833520''>next</span>
  <span m=''1833910''>value of</span> <span m=''1834310''>old</span> <span m=''1834890''>being</span>
  <span m=''1835300''>the</span> <span m=''1835400''>current</span> <span m=''1835660''>value</span>
  <span m=''1835980''>of</span> <span m=''1836070''>new</span> <span m=''1838740''>and</span>
  <span m=''1838960''>the</span> <span m=''1839020''>next</span> <span m=''1839260''>value</span>
  <span m=''1839610''>of</span> <span m=''1839700''>new</span> <span m=''1840320''>being</span>
  <span m=''1840870''>the</span> <span m=''1841090''>result</span> <span m=''1841690''>of</span>
  <span m=''1841890''>calling</span> <span m=''1842210''>f</span> <span m=''1842460''>on</span>
  <span m=''1842830''>new.</span> <span m=''1854810''>And</span> <span m=''1854960''>so</span>
  <span m=''1855070''>this</span> <span m=''1855230''>is</span> <span m=''1856050''>my</span>
  <span m=''1856210''>iteration</span> <span m=''1856700''>loop</span> <span m=''1856900''>that</span>
  <span m=''1857050''>pushes</span> <span m=''1857240''>the</span> <span m=''1857330''>button</span>
  <span m=''1857560''>on</span> <span m=''1857680''>the</span> <span m=''1857740''>calculator.</span>
  <span m=''1858600''>I</span> <span m=''1858770''>basically</span> <span m=''1859230''>think</span>
  <span m=''1859370''>of it as</span> <span m=''1859560''>having</span> <span m=''1859810''>two</span>
  <span m=''1859980''>registers</span> <span m=''1860430''>on the</span> <span m=''1860760''>calculator:</span>
  <span m=''1861200''>old</span> <span m=''1861440''>and</span> <span m=''1861680''>new.</span>
  <span m=''1862495''>And in</span> <span m=''1862970''>each</span> <span m=''1863100''>step,</span>
  <span m=''1864010''>new</span> <span m=''1864250''>becomes</span> <span m=''1864640''>old,</span>
  <span m=''1865490''>and</span> <span m=''1865870''>new</span> <span m=''1866770''>gets</span>
  <span m=''1866970''>F</span> <span m=''1867150''>of</span> <span m=''1867270''>new.</span>
  <span m=''1869070''>So</span> <span m=''1869230''>this is</span> <span m=''1869430''>the</span>
  <span m=''1869570''>thing</span> <span m=''1869790''>where</span> <span m=''1870130''>I''m</span>
  <span m=''1870270''>getting</span> <span m=''1870520''>the</span> <span m=''1870700''>next</span>
  <span m=''1870880''>value.</span> </p><p><span m=''1873080''>And</span> <span m=''1873290''>now,</span>
  <span m=''1873575''>I''m</span> <span m=''1873860''>going</span> <span m=''1873930''>to</span>
  <span m=''1874010''>start</span> <span m=''1874310''>this</span> <span m=''1874470''>thing</span>
  <span m=''1874650''>up</span> <span m=''1880970''>by</span> <span m=''1881180''>giving</span>
  <span m=''1881450''>two</span> <span m=''1881600''>values.</span> <span m=''1888470''>I</span>
  <span m=''1888640''>wrote</span> <span m=''1888830''>down on</span> <span m=''1889110''>the</span>
  <span m=''1889150''>blackboard</span> <span m=''1889690''>to</span> <span m=''1889790''>be</span>
  <span m=''1889900''>slow</span> <span m=''1890570''>so</span> <span m=''1890730''>you</span>
  <span m=''1890870''>can</span> <span m=''1890970''>see</span> <span m=''1891240''>this.</span>
  <span m=''1891640''>This</span> <span m=''1892110''>is</span> <span m=''1892280''>the</span>
  <span m=''1892460''>first</span> <span m=''1892650''>time</span> <span m=''1892880''>you''ve</span>
  <span m=''1892990''>seen</span> <span m=''1893210''>something</span> <span m=''1894110''>quite</span>
  <span m=''1894470''>this</span> <span m=''1894650''>complicated,</span> <span m=''1895210''>I</span>
  <span m=''1895450''>think.</span> <span m=''1897700''>However,</span> <span m=''1900200''>we</span>
  <span m=''1900330''>might</span> <span m=''1900530''>want</span> <span m=''1900670''>to</span>
  <span m=''1900710''>see</span> <span m=''1900860''>the</span> <span m=''1901150''>whole</span>
  <span m=''1901530''>thing</span> <span m=''1901760''>over</span> <span m=''1901970''>here</span>
  <span m=''1904540''>in</span> <span m=''1904710''>this</span> <span m=''1907460''>transparency</span>
  <span m=''1908230''>or</span> <span m=''1908380''>slide or</span> <span m=''1908800''>whatever.</span>
  <span m=''1910720''>What</span> <span m=''1910890''>we</span> <span m=''1911180''>have</span>
  <span m=''1912690''>is</span> <span m=''1913830''>all</span> <span m=''1914040''>of</span>
  <span m=''1914240''>the</span> <span m=''1914320''>details</span> <span m=''1915010''>that
  are</span> <span m=''1915340''>required</span> <span m=''1916390''>to</span> <span
  m=''1917200''>make</span> <span m=''1917510''>this</span> <span m=''1917670''>thing</span>
  <span m=''1917870''>work.</span> <span m=''1918500''>I</span> <span m=''1918660''>have</span>
  <span m=''1918780''>a</span> <span m=''1918810''>way</span> <span m=''1919000''>of</span>
  <span m=''1919260''>getting</span> <span m=''1919490''>a</span> <span m=''1919560''>tolerance</span>
  <span m=''1920700''>for</span> <span m=''1920910''>a</span> <span m=''1921130''>close</span>
  <span m=''1921440''>enough</span> <span m=''1921660''>procedure,</span> <span m=''1922190''>which</span>
  <span m=''1922330''>we</span> <span m=''1922460''>see</span> <span m=''1922670''>here.</span>
  <span m=''1923080''>The</span> <span m=''1923480''>close</span> <span m=''1923790''>enough</span>
  <span m=''1923990''>procedure,</span> <span m=''1924750''>it</span> <span m=''1925080''>tests</span>
  <span m=''1925390''>whether</span> <span m=''1925570''>u</span> <span m=''1925770''>and</span>
  <span m=''1925880''>v are</span> <span m=''1926030''>close</span> <span m=''1926300''>enough</span>
  <span m=''1926880''>by</span> <span m=''1927280''>seeing</span> <span m=''1928020''>if</span>
  <span m=''1928220''>the</span> <span m=''1928390''>absolute</span> <span m=''1928780''>value</span>
  <span m=''1929040''>of</span> <span m=''1929110''>the</span> <span m=''1929170''>difference</span>
  <span m=''1929480''>in</span> <span m=''1929600''>u and</span> <span m=''1929770''>v</span>
  <span m=''1929870''>is</span> <span m=''1930130''>less</span> <span m=''1930340''>than</span>
  <span m=''1930430''>the</span> <span m=''1930530''>given</span> <span m=''1930780''>tolerance,</span>
  <span m=''1932170''>OK?</span> <span m=''1932460''>And</span> <span m=''1932690''>here
  is</span> <span m=''1932950''>the</span> <span m=''1933110''>iteration</span> <span
  m=''1933550''>loop that</span> <span m=''1933840''>I</span> <span m=''1933930''>just</span>
  <span m=''1934120''>wrote</span> <span m=''1934270''>on</span> <span m=''1934360''>the</span>
  <span m=''1934440''>blackboard</span> <span m=''1935840''>and</span> <span m=''1935970''>the</span>
  <span m=''1936110''>initialization</span> <span m=''1936900''>for it,</span> <span
  m=''1937770''>which</span> <span m=''1937930''>is</span> <span m=''1938000''>right</span>
  <span m=''1938220''>there.</span> <span m=''1941680''>It''s</span> <span m=''1941890''>very</span>
  <span m=''1942110''>simple.</span> </p><p><span m=''1954210''>But</span> <span m=''1954450''>let''s</span>
  <span m=''1954660''>see.</span> <span m=''1954880''>I</span> <span m=''1954990''>haven''t</span>
  <span m=''1955250''>told</span> <span m=''1955490''>you</span> <span m=''1955640''>enough.</span>
  <span m=''1956630''>It''s</span> <span m=''1956840''>actually</span> <span m=''1957280''>easier</span>
  <span m=''1957680''>than</span> <span m=''1957840''>this.</span> <span m=''1959500''>There
  is</span> <span m=''1959950''>more</span> <span m=''1960220''>structure</span> <span
  m=''1960850''>to</span> <span m=''1961000''>this</span> <span m=''1961200''>problem</span>
  <span m=''1961700''>than</span> <span m=''1961950''>I''ve</span> <span m=''1962120''>already</span>
  <span m=''1962380''>told</span> <span m=''1962660''>you.</span> <span m=''1963310''>Like</span>
  <span m=''1963590''>why</span> <span m=''1963980''>should</span> <span m=''1964160''>this</span>
  <span m=''1964350''>work?</span> <span m=''1965700''>Why</span> <span m=''1965950''>should
  it</span> <span m=''1966190''>converge?</span> <span m=''1968070''>There''s</span>
  <span m=''1968300''>a</span> <span m=''1968370''>hairy</span> <span m=''1968640''>theorem</span>
  <span m=''1968940''>in</span> <span m=''1968990''>mathematics</span> <span m=''1970190''>tied</span>
  <span m=''1970410''>up in</span> <span m=''1970710''>what</span> <span m=''1970930''>I''ve</span>
  <span m=''1971090''>written</span> <span m=''1971310''>here.</span> <span m=''1972760''>Why</span>
  <span m=''1973090''>is</span> <span m=''1973230''>it</span> <span m=''1973350''>that</span>
  <span m=''1973450''>I</span> <span m=''1973560''>should</span> <span m=''1973740''>assume</span>
  <span m=''1974150''>that</span> <span m=''1974400''>by</span> <span m=''1974540''>iterating</span>
  <span m=''1975320''>averaging</span> <span m=''1975890''>the</span> <span m=''1975970''>quotient</span>
  <span m=''1976250''>of</span> <span m=''1976370''>x</span> <span m=''1976540''>and</span>
  <span m=''1976620''>y</span> <span m=''1976840''>and</span> <span m=''1976940''>y</span>
  <span m=''1977500''>that</span> <span m=''1977710''>I should</span> <span m=''1977780''>get</span>
  <span m=''1977940''>the</span> <span m=''1978020''>right</span> <span m=''1978190''>answer?</span>
  <span m=''1980110''>It</span> <span m=''1980340''>isn''t</span> <span m=''1980440''>so</span>
  <span m=''1980500''>obvious.</span> </p><p><span m=''1983710''>Surely</span> <span
  m=''1984140''>there</span> <span m=''1984350''>are</span> <span m=''1984410''>other</span>
  <span m=''1984570''>things,</span> <span m=''1985650''>other</span> <span m=''1985840''>procedures,</span>
  <span m=''1987070''>which</span> <span m=''1987280''>compute</span> <span m=''1987590''>functions</span>
  <span m=''1988430''>whose</span> <span m=''1988880''>fixed points</span> <span m=''1989380''>would</span>
  <span m=''1989480''>also</span> <span m=''1989700''>be</span> <span m=''1989800''>the</span>
  <span m=''1989870''>square</span> <span m=''1990150''>root.</span> <span m=''1992040''>For</span>
  <span m=''1992330''>example,</span> <span m=''1993310''>the</span> <span m=''1993560''>obvious</span>
  <span m=''1994040''>one</span> <span m=''1997690''>will</span> <span m=''1997840''>be
  a</span> <span m=''1997990''>new</span> <span m=''1998180''>function</span> <span
  m=''1998570''>g,</span> <span m=''2000480''>which</span> <span m=''2000700''>maps</span>
  <span m=''2001030''>y</span> <span m=''2003210''>to</span> <span m=''2005130''>x/y.</span>
  <span m=''2007950''>That''s</span> <span m=''2008130''>even</span> <span m=''2008360''>simpler.</span>
  <span m=''2010870''>The</span> <span m=''2011060''>fixed</span> <span m=''2011340''>point</span>
  <span m=''2011580''>of</span> <span m=''2011670''>g</span> <span m=''2011920''>is</span>
  <span m=''2012070''>surely</span> <span m=''2012450''>the</span> <span m=''2012530''>square</span>
  <span m=''2012830''>root</span> <span m=''2012950''>also,</span> <span m=''2014150''>and</span>
  <span m=''2014320''>it''s</span> <span m=''2014540''>a</span> <span m=''2014560''>simpler</span>
  <span m=''2014950''>procedure.</span> </p><p><span m=''2017400''>Why</span> <span
  m=''2017580''>am</span> <span m=''2017690''>I</span> <span m=''2017760''>not</span>
  <span m=''2017970''>using</span> <span m=''2018280''>it?</span> <span m=''2019020''>Well,</span>
  <span m=''2019310''>I</span> <span m=''2019430''>suppose you know.</span> <span
  m=''2020470''>Supposing</span> <span m=''2020920''>x is</span> <span m=''2021220''>2</span>
  <span m=''2021710''>and</span> <span m=''2021840''>I</span> <span m=''2021880''>start</span>
  <span m=''2022100''>out</span> <span m=''2022210''>with</span> <span m=''2022300''>1,</span>
  <span m=''2023005''>and</span> <span m=''2023300''>if I</span> <span m=''2023670''>divide</span>
  <span m=''2024730''>1</span> <span m=''2024970''>into</span> <span m=''2025210''>2,</span>
  <span m=''2026380''>I</span> <span m=''2026510''>get</span> <span m=''2026750''>2.</span>
  <span m=''2027700''>And then if I</span> <span m=''2028050''>divide</span> <span
  m=''2028400''>2</span> <span m=''2028520''>into</span> <span m=''2028750''>2,</span>
  <span m=''2028930''>I</span> <span m=''2029010''>get</span> <span m=''2029210''>1.</span>
  <span m=''2029610''>If</span> <span m=''2029810''>I</span> <span m=''2030050''>divide</span>
  <span m=''2030120''>1 into</span> <span m=''2030440''>2,</span> <span m=''2030590''>I</span>
  <span m=''2030650''>get</span> <span m=''2030860''>2,</span> <span m=''2031350''>and</span>
  <span m=''2031500''>2 into</span> <span m=''2031640''>2,</span> <span m=''2031850''>I</span>
  <span m=''2031910''>get</span> <span m=''2032100''>1,</span> <span m=''2032580''>and</span>
  <span m=''2032700''>I</span> <span m=''2032740''>never</span> <span m=''2032920''>get</span>
  <span m=''2033080''>any</span> <span m=''2033190''>closer</span> <span m=''2033540''>to
  the</span> <span m=''2033610''>square</span> <span m=''2033990''>root.</span> <span
  m=''2035480''>It</span> <span m=''2035550''>just</span> <span m=''2035690''>oscillates.</span>
  <span m=''2039080''>So</span> <span m=''2039650''>what</span> <span m=''2039780''>we</span>
  <span m=''2039910''>have</span> <span m=''2040040''>is</span> <span m=''2040580''>a</span>
  <span m=''2040760''>signal</span> <span m=''2041070''>processing</span> <span m=''2041460''>system,</span>
  <span m=''2043010''>an</span> <span m=''2043110''>electrical</span> <span m=''2043600''>circuit</span>
  <span m=''2045100''>which</span> <span m=''2045240''>is</span> <span m=''2045340''>oscillating,</span>
  <span m=''2045625''>and</span> <span m=''2045910''>I</span> <span m=''2046000''>want</span>
  <span m=''2046120''>to</span> <span m=''2046230''>damp</span> <span m=''2046530''>out</span>
  <span m=''2046720''>these</span> <span m=''2046890''>oscillations.</span> <span
  m=''2050530''>Well,</span> <span m=''2050690''>I</span> <span m=''2050760''>can</span>
  <span m=''2050909''>do</span> <span m=''2051020''>that.</span> </p><p><span m=''2051840''>See,</span>
  <span m=''2052020''>what I''m</span> <span m=''2052199''>really</span> <span m=''2052480''>doing</span>
  <span m=''2052780''>here</span> <span m=''2053070''>when</span> <span m=''2053210''>I''m</span>
  <span m=''2053360''>taking</span> <span m=''2053940''>my</span> <span m=''2054190''>average,</span>
  <span m=''2055020''>the</span> <span m=''2055260''>average</span> <span m=''2055659''>is</span>
  <span m=''2055780''>averaging</span> <span m=''2056250''>the</span> <span m=''2056300''>last</span>
  <span m=''2056679''>two</span> <span m=''2056800''>values</span> <span m=''2057290''>of</span>
  <span m=''2057370''>something</span> <span m=''2057639''>which</span> <span m=''2057800''>oscillates,</span>
  <span m=''2059110''>getting</span> <span m=''2059320''>something</span> <span m=''2059699''>in</span>
  <span m=''2059790''>between.</span> <span m=''2061350''>The</span> <span m=''2061560''>classic</span>
  <span m=''2061960''>way</span> <span m=''2062219''>is</span> <span m=''2062320''>damping</span>
  <span m=''2062719''>out</span> <span m=''2063070''>oscillations</span> <span m=''2063710''>in</span>
  <span m=''2063840''>a</span> <span m=''2064159''>signal</span> <span m=''2064480''>processing</span>
  <span m=''2064880''>system.</span> <span m=''2068460''>So</span> <span m=''2068650''>why
  don''t</span> <span m=''2068850''>we</span> <span m=''2068989''>write</span> <span
  m=''2069250''>down</span> <span m=''2069590''>the</span> <span m=''2070060''>strategy</span>
  <span m=''2070590''>that</span> <span m=''2070710''>I</span> <span m=''2070800''>just</span>
  <span m=''2071030''>said</span> <span m=''2071500''>in</span> <span m=''2071679''>a</span>
  <span m=''2071719''>more</span> <span m=''2072380''>clear</span> <span m=''2072650''>way?</span>
  <span m=''2073872''>Well,</span> <span m=''2074340''>that''s</span> <span m=''2074830''>easy</span>
  <span m=''2075080''>enough.</span> </p><p><span m=''2078639''>I''m</span> <span
  m=''2079070''>going</span> <span m=''2079199''>to</span> <span m=''2079330''>define</span>
  <span m=''2081960''>the</span> <span m=''2082090''>square</span> <span m=''2082409''>root</span>
  <span m=''2085120''>of</span> <span m=''2085310''>x</span> <span m=''2086070''>to</span>
  <span m=''2086270''>be</span> <span m=''2087570''>a</span> <span m=''2087679''>fixed</span>
  <span m=''2088020''>point</span> <span m=''2093790''>of</span> <span m=''2093989''>the</span>
  <span m=''2094090''>procedure</span> <span m=''2094679''>resulting</span> <span
  m=''2095330''>from</span> <span m=''2095570''>average</span> <span m=''2096050''>damping.</span>
  <span m=''2098510''>So</span> <span m=''2098740''>I have</span> <span m=''2098860''>a</span>
  <span m=''2098970''>procedure</span> <span m=''2099740''>resulting</span> <span
  m=''2100410''>from</span> <span m=''2101020''>average</span> <span m=''2101430''>damp</span>
  <span m=''2110620''>of</span> <span m=''2110780''>the</span> <span m=''2111120''>procedure,</span>
  <span m=''2111890''>that</span> <span m=''2112210''>procedure</span> <span m=''2112700''>of</span>
  <span m=''2112930''>y,</span> <span m=''2114740''>which</span> <span m=''2116950''>divides</span>
  <span m=''2119520''>x</span> <span m=''2119880''>by</span> <span m=''2120100''>y</span>
  <span m=''2124820''>starting</span> <span m=''2125260''>out</span> <span m=''2125390''>at</span>
  <span m=''2125460''>1.</span> <span m=''2129840''>Ah,</span> <span m=''2130375''>but</span>
  <span m=''2130650''>average</span> <span m=''2131050''>damp</span> <span m=''2131900''>is</span>
  <span m=''2132030''>a</span> <span m=''2132070''>special</span> <span m=''2132430''>procedure</span>
  <span m=''2132970''>that''s</span> <span m=''2133460''>going</span> <span m=''2133520''>to</span>
  <span m=''2133580''>take</span> <span m=''2133750''>a</span> <span m=''2133810''>procedure</span>
  <span m=''2134110''>as its</span> <span m=''2134410''>argument</span> <span m=''2135210''>and</span>
  <span m=''2135360''>return</span> <span m=''2135650''>a</span> <span m=''2135720''>procedure</span>
  <span m=''2136025''>as its</span> <span m=''2136330''>value.</span> <span m=''2138080''>It''s</span>
  <span m=''2138200''>a</span> <span m=''2138250''>generalization</span> <span m=''2139320''>that</span>
  <span m=''2139560''>says</span> <span m=''2140300''>given</span> <span m=''2140510''>a</span>
  <span m=''2140580''>procedure,</span> <span m=''2141860''>it''s</span> <span m=''2142090''>the</span>
  <span m=''2142150''>thing</span> <span m=''2142360''>which</span> <span m=''2142500''>produces</span>
  <span m=''2142870''>a</span> <span m=''2142930''>procedure</span> <span m=''2143280''>which</span>
  <span m=''2143460''>averages</span> <span m=''2144850''>the</span> <span m=''2145090''>last</span>
  <span m=''2145870''>value</span> <span m=''2146790''>and</span> <span m=''2147000''>the</span>
  <span m=''2147260''>value</span> <span m=''2147600''>before</span> <span m=''2147910''>and</span>
  <span m=''2147980''>after</span> <span m=''2148240''>running</span> <span m=''2148430''>the</span>
  <span m=''2148480''>procedure.</span> <span m=''2151320''>You can</span> <span m=''2151500''>use</span>
  <span m=''2151660''>it</span> <span m=''2151750''>for</span> <span m=''2151890''>anything</span>
  <span m=''2152210''>if</span> <span m=''2152300''>you</span> <span m=''2152400''>want</span>
  <span m=''2152560''>to</span> <span m=''2152840''>damp</span> <span m=''2153130''>out</span>
  <span m=''2153260''>oscillations.</span> <span m=''2154880''>So</span> <span m=''2155130''>let''s</span>
  <span m=''2155310''>write</span> <span m=''2155520''>that</span> <span m=''2155710''>down.</span>
  <span m=''2156495''>It''s very</span> <span m=''2156950''>easy.</span> </p><p><span
  m=''2160624''>And</span> <span m=''2161070''>stylistically</span> <span m=''2161900''>here,</span>
  <span m=''2162450''>I''m</span> <span m=''2162640''>going</span> <span m=''2162730''>to</span>
  <span m=''2162820''>use</span> <span m=''2163120''>lambda</span> <span m=''2163420''>notation</span>
  <span m=''2164590''>because it''s</span> <span m=''2164830''>much</span> <span m=''2165120''>easier</span>
  <span m=''2165720''>to</span> <span m=''2166020''>think</span> <span m=''2166330''>when</span>
  <span m=''2166450''>you''re</span> <span m=''2166560''>dealing</span> <span m=''2166820''>with</span>
  <span m=''2166950''>procedure,</span> <span m=''2167370''>the</span> <span m=''2167530''>mid-line</span>
  <span m=''2167970''>procedures,</span> <span m=''2168230''>to</span> <span m=''2168320''>understand</span>
  <span m=''2168810''>that the</span> <span m=''2168880''>procedures</span> <span
  m=''2169410''>are</span> <span m=''2169590''>the</span> <span m=''2169750''>objects</span>
  <span m=''2170240''>I''m</span> <span m=''2170330''>dealing</span> <span m=''2170630''>with,</span>
  <span m=''2170930''>so</span> <span m=''2171170''>I''m</span> <span m=''2171425''>going
  to</span> <span m=''2171680''>use</span> <span m=''2172390''>lambda</span> <span
  m=''2172680''>notation</span> <span m=''2173150''>here.</span> <span m=''2173830''>Not</span>
  <span m=''2174050''>always.</span> <span m=''2174490''>I don''t always</span> <span
  m=''2174830''>use</span> <span m=''2175020''>it,</span> <span m=''2176030''>but</span>
  <span m=''2176170''>very</span> <span m=''2176360''>specifically</span> <span m=''2176910''>here</span>
  <span m=''2177480''>to</span> <span m=''2178110''>expand</span> <span m=''2178760''>on</span>
  <span m=''2178910''>that</span> <span m=''2179090''>idea,</span> <span m=''2180350''>to</span>
  <span m=''2181290''>elucidate</span> <span m=''2181640''>it.</span> </p><p><span
  m=''2188590''>Well,</span> <span m=''2189100''>average</span> <span m=''2189460''>damp</span>
  <span m=''2189700''>is</span> <span m=''2189840''>a</span> <span m=''2189900''>procedure,</span>
  <span m=''2192220''>which</span> <span m=''2192440''>takes</span> <span m=''2193670''>a</span>
  <span m=''2193810''>procedure</span> <span m=''2194250''>as</span> <span m=''2194350''>its</span>
  <span m=''2194420''>argument,</span> <span m=''2194820''>which</span> <span m=''2194940''>we
  will</span> <span m=''2195170''>call</span> <span m=''2195490''>f.</span> <span
  m=''2197560''>And</span> <span m=''2197670''>what does</span> <span m=''2197930''>it</span>
  <span m=''2198010''>produce?</span> <span m=''2198710''>It</span> <span m=''2198930''>produces</span>
  <span m=''2199400''>as</span> <span m=''2199500''>its</span> <span m=''2199710''>value--</span>
  <span m=''2200340''>the</span> <span m=''2200530''>body</span> <span m=''2201020''>of</span>
  <span m=''2201170''>this</span> <span m=''2201380''>procedure</span> <span m=''2202200''>is</span>
  <span m=''2202770''>a</span> <span m=''2202920''>thing</span> <span m=''2203120''>which</span>
  <span m=''2203340''>produces</span> <span m=''2203830''>a</span> <span m=''2203890''>procedure,</span>
  <span m=''2204690''>the</span> <span m=''2204760''>construct</span> <span m=''2205020''>of</span>
  <span m=''2205280''>the</span> <span m=''2205450''>procedures</span> <span m=''2205910''>right</span>
  <span m=''2206110''>here,</span> <span m=''2207100''>of</span> <span m=''2207260''>one</span>
  <span m=''2207440''>argument</span> <span m=''2207730''>x,</span> <span m=''2210130''>which</span>
  <span m=''2210690''>averages</span> <span m=''2217150''>f</span> <span m=''2217310''>of</span>
  <span m=''2217470''>x</span> <span m=''2219780''>with</span> <span m=''2219970''>x.</span>
  </p><p><span m=''2230420''>This</span> <span m=''2230770''>is</span> <span m=''2230880''>a</span>
  <span m=''2231020''>very</span> <span m=''2231400''>special</span> <span m=''2231890''>thing.</span>
  <span m=''2234070''>I</span> <span m=''2234170''>think</span> <span m=''2234320''>for</span>
  <span m=''2234410''>the</span> <span m=''2234490''>first</span> <span m=''2234810''>time</span>
  <span m=''2235050''>you''re</span> <span m=''2235190''>seeing</span> <span m=''2237200''>a</span>
  <span m=''2237330''>procedure</span> <span m=''2237730''>which</span> <span m=''2237890''>produces</span>
  <span m=''2238250''>a</span> <span m=''2238350''>procedure</span> <span m=''2238780''>as</span>
  <span m=''2238870''>its</span> <span m=''2239020''>value.</span> <span m=''2241730''>This</span>
  <span m=''2242650''>procedure</span> <span m=''2243710''>takes</span> <span m=''2244010''>the</span>
  <span m=''2244070''>procedure</span> <span m=''2244600''>f</span> <span m=''2244920''>and</span>
  <span m=''2245140''>does</span> <span m=''2245350''>something</span> <span m=''2245690''>to</span>
  <span m=''2245900''>it</span> <span m=''2246140''>to</span> <span m=''2246440''>produce</span>
  <span m=''2246700''>a</span> <span m=''2246770''>new</span> <span m=''2246990''>procedure</span>
  <span m=''2247740''>of</span> <span m=''2247880''>one</span> <span m=''2248010''>argument</span>
  <span m=''2248350''>x,</span> <span m=''2249360''>which</span> <span m=''2249640''>averages</span>
  <span m=''2250015''>f--</span> <span m=''2251050''>this</span> <span m=''2251330''>f--</span>
  <span m=''2251950''>applied</span> <span m=''2252460''>to</span> <span m=''2252680''>x</span>
  <span m=''2253330''>and</span> <span m=''2253560''>x</span> <span m=''2253760''>itself.</span>
  <span m=''2256040''>Using</span> <span m=''2256490''>the</span> <span m=''2256590''>context</span>
  <span m=''2257250''>here,</span> <span m=''2258110''>I</span> <span m=''2258620''>apply</span>
  <span m=''2258930''>average</span> <span m=''2259280''>damping</span> <span m=''2259900''>to</span>
  <span m=''2260180''>the</span> <span m=''2260280''>procedure,</span> <span m=''2260750''>which</span>
  <span m=''2261020''>just</span> <span m=''2261250''>divides</span> <span m=''2262210''>x</span>
  <span m=''2262480''>by</span> <span m=''2262650''>y.</span> <span m=''2264670''>It''s</span>
  <span m=''2264760''>a</span> <span m=''2264800''>division.</span> <span m=''2268122''>And</span>
  <span m=''2268590''>I''m</span> <span m=''2268820''>finding</span> <span m=''2269070''>to</span>
  <span m=''2269150''>fixed</span> <span m=''2269400''>point</span> <span m=''2269650''>of</span>
  <span m=''2269860''>that,</span> <span m=''2270600''>and</span> <span m=''2270780''>that''s</span>
  <span m=''2271470''>a</span> <span m=''2271600''>clearer</span> <span m=''2271980''>way</span>
  <span m=''2272200''>of</span> <span m=''2272320''>writing</span> <span m=''2272630''>down</span>
  <span m=''2273300''>what</span> <span m=''2273430''>I</span> <span m=''2273850''>wrote</span>
  <span m=''2274060''>down</span> <span m=''2274280''>over</span> <span m=''2274460''>here,</span>
  <span m=''2276160''>wherever</span> <span m=''2276440''>it</span> <span m=''2276540''>was.</span>
  <span m=''2277796''>Here,</span> <span m=''2279125''>because</span> <span m=''2279570''>it</span>
  <span m=''2279750''>tells</span> <span m=''2280020''>why</span> <span m=''2280300''>I</span>
  <span m=''2280320''>am</span> <span m=''2280470''>writing</span> <span m=''2280700''>this</span>
  <span m=''2280880''>down.</span> </p><p><span m=''2287910''>I</span> <span m=''2288080''>suppose</span>
  <span m=''2288440''>this</span> <span m=''2289320''>to</span> <span m=''2289450''>some</span>
  <span m=''2289640''>extent</span> <span m=''2289910''>really</span> <span m=''2290130''>clarifies</span>
  <span m=''2290670''>what</span> <span m=''2290790''>Heron</span> <span m=''2291020''>of</span>
  <span m=''2291110''>Alexandria</span> <span m=''2291630''>was</span> <span m=''2291780''>up</span>
  <span m=''2291910''>to.</span> <span m=''2294260''>I</span> <span m=''2294390''>suppose</span>
  <span m=''2294550''>I''ll</span> <span m=''2294620''>stop</span> <span m=''2294960''>now.</span>
  <span m=''2295130''>Are</span> <span m=''2295180''>there</span> <span m=''2295290''>any</span>
  <span m=''2295410''>questions?</span> </p><p><span m=''2298190''>AUDIENCE: So</span>
  <span m=''2298440''>when</span> <span m=''2298540''>you</span> <span m=''2298610''>define</span>
  <span m=''2299080''>average</span> <span m=''2299480''>damp,</span> <span m=''2299890''>don''t</span>
  <span m=''2300300''>you</span> <span m=''2300791''>need</span> <span m=''2301282''>to
  have</span> <span m=''2301773''>a</span> <span m=''2302264''>variable</span> <span
  m=''2302755''>on</span> <span m=''2303246''>f?</span> </p><p><span m=''2305210''>PROFESSOR:
  Ah,</span> <span m=''2305750''>the</span> <span m=''2306170''>question</span> <span
  m=''2307030''>was,</span> <span m=''2307390''>and</span> <span m=''2307530''>here
  we''re</span> <span m=''2307810''>having--</span> <span m=''2308150''>again,</span>
  <span m=''2308570''>you''ve</span> <span m=''2308690''>got</span> <span m=''2308780''>to</span>
  <span m=''2308860''>learn</span> <span m=''2309090''>about</span> <span m=''2309240''>the</span>
  <span m=''2309380''>syntax.</span> <span m=''2309900''>The</span> <span m=''2310010''>question</span>
  <span m=''2310400''>was</span> <span m=''2311320''>when</span> <span m=''2311580''>defining</span>
  <span m=''2312120''>average</span> <span m=''2312460''>damp,</span> <span m=''2313290''>don''t</span>
  <span m=''2313560''>you</span> <span m=''2313700''>have</span> <span m=''2313840''>to</span>
  <span m=''2313990''>have</span> <span m=''2315080''>a</span> <span m=''2315190''>variable</span>
  <span m=''2316380''>defined</span> <span m=''2316820''>with</span> <span m=''2317000''>f?</span>
  <span m=''2318070''>What</span> <span m=''2318290''>you</span> <span m=''2318450''>are</span>
  <span m=''2318560''>asking</span> <span m=''2318840''>about</span> <span m=''2319020''>is</span>
  <span m=''2319110''>the</span> <span m=''2319200''>formal</span> <span m=''2319500''>parameter</span>
  <span m=''2319950''>of f?</span> </p><p><span m=''2320310''>AUDIENCE: Yeah.</span>
  </p><p><span m=''2321290''>PROFESSOR: OK.</span> <span m=''2322810''>The</span>
  <span m=''2323150''>formal</span> <span m=''2323390''>parameter</span> <span m=''2323840''>of</span>
  <span m=''2323890''>f</span> <span m=''2324120''>is</span> <span m=''2324260''>here.</span>
  <span m=''2325580''>The</span> <span m=''2325760''>formal</span> <span m=''2326015''>parameter</span>
  <span m=''2326270''>of</span> <span m=''2326440''>f--</span> </p><p><span m=''2327318''>AUDIENCE:
  The formal</span> <span m=''2327796''>parameter of</span> <span m=''2328274''>average</span>
  <span m=''2328752''>damp.</span> </p><p><span m=''2330190''>PROFESSOR: F</span>
  <span m=''2330430''>is</span> <span m=''2330550''>being</span> <span m=''2330820''>used</span>
  <span m=''2331170''>to</span> <span m=''2331650''>apply it</span> <span m=''2331860''>to</span>
  <span m=''2331890''>an</span> <span m=''2332040''>argument,</span> <span m=''2333890''>right?</span>
  <span m=''2334400''>It''s</span> <span m=''2334740''>indeed</span> <span m=''2335060''>true</span>
  <span m=''2335260''>that</span> <span m=''2335380''>f</span> <span m=''2335560''>must</span>
  <span m=''2335830''>have</span> <span m=''2335920''>a</span> <span m=''2336010''>formal</span>
  <span m=''2336290''>parameter.</span> <span m=''2337780''>Let''s</span> <span m=''2338040''>find</span>
  <span m=''2338320''>out</span> <span m=''2338500''>what</span> <span m=''2338660''>f''s</span>
  <span m=''2338740''>formal</span> <span m=''2339070''>parameter</span> <span m=''2339460''>is.</span>
  </p><p><span m=''2340380''>AUDIENCE: The formal</span> <span m=''2340630''>parameter</span>
  <span m=''2341130''>of</span> <span m=''2341320''>average</span> <span m=''2341730''>damp.</span>
  </p><p><span m=''2342440''>PROFESSOR: Oh,</span> <span m=''2342860''>f</span> <span
  m=''2343140''>is</span> <span m=''2343380''>the</span> <span m=''2343470''>formal</span>
  <span m=''2343700''>parameter of</span> <span m=''2343950''>average</span> <span
  m=''2344280''>damp.</span> <span m=''2344700''>I''m</span> <span m=''2344910''>sorry.</span>
  <span m=''2345500''>You''re</span> <span m=''2345660''>just</span> <span m=''2345930''>confusing</span>
  <span m=''2346410''>a</span> <span m=''2346470''>syntactic</span> <span m=''2347010''>thing.</span>
  <span m=''2347910''>I</span> <span m=''2348090''>could</span> <span m=''2348260''>have</span>
  <span m=''2348380''>written</span> <span m=''2348570''>this</span> <span m=''2348790''>the</span>
  <span m=''2348900''>other</span> <span m=''2349110''>way.</span> <span m=''2350470''>Actually,</span>
  <span m=''2350610''>I didn''t</span> <span m=''2350840''>understand</span> <span
  m=''2351150''>your</span> <span m=''2351240''>question.</span> <span m=''2352520''>Of</span>
  <span m=''2352660''>course,</span> <span m=''2352790''>I</span> <span m=''2352850''>could</span>
  <span m=''2352950''>have</span> <span m=''2353060''>written</span> <span m=''2353220''>it</span>
  <span m=''2353310''>this</span> <span m=''2353440''>other</span> <span m=''2353640''>way.</span>
  <span m=''2359340''>Those</span> <span m=''2359690''>are</span> <span m=''2359770''>identical</span>
  <span m=''2360190''>notations.</span> <span m=''2361540''>This</span> <span m=''2361800''>is</span>
  <span m=''2361960''>a</span> <span m=''2363110''>different</span> <span m=''2363410''>way</span>
  <span m=''2363570''>of</span> <span m=''2363680''>writing</span> <span m=''2365138''>this.</span>
  <span m=''2371710''>You''re</span> <span m=''2371850''>going</span> <span m=''2371910''>to</span>
  <span m=''2371970''>have</span> <span m=''2372090''>to</span> <span m=''2372200''>get</span>
  <span m=''2372300''>used</span> <span m=''2372430''>to</span> <span m=''2372550''>lambda</span>
  <span m=''2372830''>notation</span> <span m=''2373280''>because</span> <span m=''2373530''>I''m
  going to</span> <span m=''2373670''>use</span> <span m=''2373850''>it.</span> </p><p><span
  m=''2375520''>What</span> <span m=''2375730''>it</span> <span m=''2375840''>says</span>
  <span m=''2376100''>here,</span> <span m=''2377030''>I''m</span> <span m=''2377300''>defining</span>
  <span m=''2379020''>the</span> <span m=''2379160''>name</span> <span m=''2379520''>average</span>
  <span m=''2379980''>damp</span> <span m=''2380460''>to</span> <span m=''2380660''>name</span>
  <span m=''2381120''>the</span> <span m=''2381320''>procedure</span> <span m=''2382030''>whose</span>
  <span m=''2382590''>of</span> <span m=''2382750''>one</span> <span m=''2382910''>argument</span>
  <span m=''2383320''>f.</span> <span m=''2384600''>That''s</span> <span m=''2384740''>the</span>
  <span m=''2384890''>formal</span> <span m=''2385160''>parameter</span> <span m=''2385800''>of</span>
  <span m=''2385930''>the</span> <span m=''2386070''>procedure</span> <span m=''2386450''>average</span>
  <span m=''2386810''>damp.</span> <span m=''2389250''>What</span> <span m=''2389760''>define</span>
  <span m=''2390180''>does</span> <span m=''2391280''>is</span> <span m=''2391620''>it</span>
  <span m=''2391860''>says</span> <span m=''2392160''>give</span> <span m=''2392460''>this</span>
  <span m=''2393960''>name</span> <span m=''2394940''>a</span> <span m=''2395070''>value.</span>
  <span m=''2396550''>Here</span> <span m=''2397030''>is</span> <span m=''2397120''>the</span>
  <span m=''2397210''>value</span> <span m=''2397560''>of</span> <span m=''2397630''>for
  it.</span> <span m=''2401310''>That</span> <span m=''2401790''>there</span> <span
  m=''2401990''>happens</span> <span m=''2402270''>to</span> <span m=''2402350''>be</span>
  <span m=''2402530''>a</span> <span m=''2402590''>funny</span> <span m=''2402850''>syntax</span>
  <span m=''2404380''>to</span> <span m=''2404760''>make</span> <span m=''2404980''>that</span>
  <span m=''2405100''>easier</span> <span m=''2405670''>in</span> <span m=''2405780''>some</span>
  <span m=''2406000''>cases</span> <span m=''2407280''>is</span> <span m=''2407430''>purely</span>
  <span m=''2407760''>convenience.</span> <span m=''2410900''>But</span> <span m=''2411100''>the
  reason why</span> <span m=''2411540''>I</span> <span m=''2411680''>wrote</span>
  <span m=''2411860''>it</span> <span m=''2411930''>this</span> <span m=''2412100''>way</span>
  <span m=''2412280''>here</span> <span m=''2412830''>is</span> <span m=''2412990''>to</span>
  <span m=''2413080''>emphasize</span> <span m=''2414540''>that</span> <span m=''2415040''>I''m</span>
  <span m=''2415180''>dealing with</span> <span m=''2415500''>a</span> <span m=''2415620''>procedure</span>
  <span m=''2416150''>that</span> <span m=''2416290''>takes</span> <span m=''2416470''>a</span>
  <span m=''2416530''>procedure</span> <span m=''2416940''>as</span> <span m=''2417040''>its</span>
  <span m=''2417100''>argument</span> <span m=''2417490''>and</span> <span m=''2417600''>produces</span>
  <span m=''2418030''>a</span> <span m=''2418100''>procedure</span> <span m=''2418410''>as
  its</span> <span m=''2418720''>value.</span> </p><p><span m=''2423640''>AUDIENCE:
  I don''t</span> <span m=''2423770''>understand</span> <span m=''2424250''>why</span>
  <span m=''2424420''>you</span> <span m=''2424740''>use</span> <span m=''2424920''>lambda</span>
  <span m=''2425370''>twice.</span> <span m=''2425800''>Can</span> <span m=''2425980''>you</span>
  <span m=''2426100''>just</span> <span m=''2426370''>use</span> <span m=''2426560''>one</span>
  <span m=''2426990''>lambda</span> <span m=''2427180''>and</span> <span m=''2427350''>take</span>
  <span m=''2427590''>two</span> <span m=''2427760''>arguments</span> <span m=''2428060''>f</span>
  <span m=''2428360''>and</span> <span m=''2428590''>x?</span> </p><p><span m=''2429230''>PROFESSOR:
  No.</span> </p><p><span m=''2429520''>AUDIENCE: You</span> <span m=''2429740''>can''t?</span>
  </p><p><span m=''2430330''>PROFESSOR: No,</span> <span m=''2430530''>that</span>
  <span m=''2430730''>would</span> <span m=''2430850''>be</span> <span m=''2430970''>a</span>
  <span m=''2431010''>different</span> <span m=''2431360''>thing.</span> <span m=''2432500''>If</span>
  <span m=''2432680''>I</span> <span m=''2432780''>were to</span> <span m=''2432980''>write</span>
  <span m=''2433390''>the</span> <span m=''2433540''>procedure</span> <span m=''2434790''>lambda</span>
  <span m=''2435130''>of</span> <span m=''2435350''>f</span> <span m=''2435520''>and
  x,</span> <span m=''2436190''>the</span> <span m=''2436400''>average</span> <span
  m=''2436830''>of</span> <span m=''2436980''>f of x</span> <span m=''2437500''>and</span>
  <span m=''2437710''>x,</span> <span m=''2438710''>that</span> <span m=''2438990''>would</span>
  <span m=''2439110''>not</span> <span m=''2439320''>be</span> <span m=''2439450''>something</span>
  <span m=''2440090''>which</span> <span m=''2440320''>would</span> <span m=''2440450''>be</span>
  <span m=''2440560''>allowed</span> <span m=''2440870''>to</span> <span m=''2440930''>take</span>
  <span m=''2441180''>a</span> <span m=''2441280''>procedure</span> <span m=''2441810''>as</span>
  <span m=''2441910''>an</span> <span m=''2441990''>argument</span> <span m=''2442570''>and</span>
  <span m=''2442810''>produce</span> <span m=''2443060''>a</span> <span m=''2443130''>procedure</span>
  <span m=''2443590''>as</span> <span m=''2443680''>its</span> <span m=''2443810''>value.</span>
  <span m=''2444580''>That</span> <span m=''2444810''>would</span> <span m=''2444970''>be</span>
  <span m=''2445080''>a</span> <span m=''2445130''>thing</span> <span m=''2445330''>that</span>
  <span m=''2445430''>takes</span> <span m=''2445570''>a</span> <span m=''2445630''>procedure</span>
  <span m=''2446090''>as</span> <span m=''2446180''>its</span> <span m=''2446330''>argument</span>
  <span m=''2446760''>and</span> <span m=''2446960''>numbers</span> <span m=''2447460''>its</span>
  <span m=''2447600''>argument</span> <span m=''2448480''>and</span> <span m=''2448700''>produces
  a new</span> <span m=''2449190''>number.</span> <span m=''2450620''>But</span> <span
  m=''2451040''>what I''m</span> <span m=''2451250''>producing</span> <span m=''2451660''>here</span>
  <span m=''2451880''>is</span> <span m=''2451960''>a</span> <span m=''2452020''>procedure</span>
  <span m=''2452520''>to</span> <span m=''2452610''>fit</span> <span m=''2452870''>in</span>
  <span m=''2453430''>the</span> <span m=''2453650''>procedure</span> <span m=''2454280''>slot</span>
  <span m=''2454670''>over</span> <span m=''2454930''>here,</span> <span m=''2455410''>which</span>
  <span m=''2455650''>is</span> <span m=''2455730''>going</span> <span m=''2456000''>to</span>
  <span m=''2456090''>be</span> <span m=''2456240''>used</span> <span m=''2456650''>over</span>
  <span m=''2456860''>here.</span> <span m=''2458860''>So</span> <span m=''2458990''>the</span>
  <span m=''2459120''>number</span> <span m=''2459470''>has</span> <span m=''2459650''>to</span>
  <span m=''2459720''>come</span> <span m=''2459880''>from</span> <span m=''2460050''>here.</span>
  <span m=''2461450''>This</span> <span m=''2461810''>is</span> <span m=''2461920''>the</span>
  <span m=''2462030''>thing</span> <span m=''2462230''>that''s</span> <span m=''2462390''>going</span>
  <span m=''2462470''>to</span> <span m=''2462540''>eventually</span> <span m=''2463010''>end</span>
  <span m=''2463170''>up</span> <span m=''2463290''>in the</span> <span m=''2463470''>x.</span>
  <span m=''2464440''>And</span> <span m=''2464620''>if</span> <span m=''2464700''>you''re</span>
  <span m=''2464860''>confused,</span> <span m=''2465320''>you</span> <span m=''2465450''>should</span>
  <span m=''2465660''>do</span> <span m=''2465810''>some</span> <span m=''2466010''>substitution</span>
  <span m=''2467810''>and</span> <span m=''2467980''>see</span> <span m=''2468230''>for</span>
  <span m=''2468320''>yourself.</span> <span m=''2472010''>Yes?</span> </p><p><span
  m=''2472746''>AUDIENCE: Will you</span> <span m=''2473152''>please</span> <span
  m=''2473560''>show</span> <span m=''2474300''>the</span> <span m=''2474630''>definition</span>
  <span m=''2475240''>for</span> <span m=''2475410''>average</span> <span m=''2475870''>damp</span>
  <span m=''2476170''>without using</span> <span m=''2476605''>lambda</span> <span
  m=''2477040''>notation</span> <span m=''2477475''>in</span> <span m=''2477910''>both</span>
  <span m=''2478260''>cases.</span> </p><p><span m=''2479320''>PROFESSOR: I</span>
  <span m=''2479440''>can''t</span> <span m=''2479900''>make</span> <span m=''2480170''>a</span>
  <span m=''2480250''>very</span> <span m=''2480540''>simple</span> <span m=''2480830''>one</span>
  <span m=''2481010''>like</span> <span m=''2481240''>that.</span> <span m=''2481490''>Let</span>
  <span m=''2481630''>me</span> <span m=''2481720''>do it</span> <span m=''2481920''>for</span>
  <span m=''2482110''>you,</span> <span m=''2482290''>though.</span> <span m=''2482990''>I</span>
  <span m=''2483120''>can</span> <span m=''2483310''>get</span> <span m=''2483480''>rid</span>
  <span m=''2483580''>of</span> <span m=''2483660''>this</span> <span m=''2483860''>lambda</span>
  <span m=''2484130''>easily.</span> <span m=''2486530''>I</span> <span m=''2486710''>don''t</span>
  <span m=''2486890''>want</span> <span m=''2487010''>to</span> <span m=''2487130''>be--</span>
  <span m=''2492760''>actually,</span> <span m=''2493090''>I''m</span> <span m=''2493240''>lying</span>
  <span m=''2493570''>to</span> <span m=''2493680''>you.</span> <span m=''2493810''>I</span>
  <span m=''2493890''>don''t</span> <span m=''2494080''>want</span> <span m=''2494210''>to</span>
  <span m=''2494340''>do</span> <span m=''2495310''>what you</span> <span m=''2495460''>want</span>
  <span m=''2496510''>because</span> <span m=''2496700''>I</span> <span m=''2496760''>think</span>
  <span m=''2496880''>it''s</span> <span m=''2496990''>more</span> <span m=''2497170''>confusing</span>
  <span m=''2497640''>than</span> <span m=''2497770''>you</span> <span m=''2497900''>think.</span>
  <span m=''2499310''>I''m</span> <span m=''2499440''>not</span> <span m=''2499610''>going</span>
  <span m=''2499680''>to</span> <span m=''2499760''>write</span> <span m=''2499940''>what</span>
  <span m=''2500050''>you</span> <span m=''2500170''>want.</span> </p><p><span m=''2515450''>So</span>
  <span m=''2515660''>we''ll</span> <span m=''2515920''>have to get</span> <span m=''2516090''>a</span>
  <span m=''2516140''>name.</span> <span m=''2516500''>FOO</span> <span m=''2517726''>of</span>
  <span m=''2518110''>x</span> <span m=''2519870''>to</span> <span m=''2520040''>be</span>
  <span m=''2525370''>of</span> <span m=''2526813''>F</span> <span m=''2527780''>of</span>
  <span m=''2528020''>x</span> <span m=''2528785''>and</span> <span m=''2529090''>x</span>
  <span m=''2531930''>and</span> <span m=''2532100''>return</span> <span m=''2532490''>as</span>
  <span m=''2532640''>a</span> <span m=''2532690''>value</span> <span m=''2533110''>FOO.</span>
  <span m=''2537140''>This</span> <span m=''2537660''>is</span> <span m=''2537780''>equivalent,</span>
  <span m=''2539470''>but</span> <span m=''2539740''>I''ve had</span> <span m=''2540010''>to</span>
  <span m=''2540260''>make an arbitrary</span> <span m=''2540480''>name</span> <span
  m=''2540710''>up.</span> <span m=''2541700''>This is</span> <span m=''2541900''>equivalent</span>
  <span m=''2542580''>to</span> <span m=''2542950''>this</span> <span m=''2543160''>without</span>
  <span m=''2543450''>any</span> <span m=''2543630''>lambdas.</span> <span m=''2546290''>Lambda</span>
  <span m=''2546930''>is</span> <span m=''2547110''>very</span> <span m=''2547400''>convenient</span>
  <span m=''2547910''>for</span> <span m=''2548400''>naming</span> <span m=''2550190''>anonymous</span>
  <span m=''2550640''>procedures.</span> <span m=''2551240''>It''s</span> <span m=''2551370''>the</span>
  <span m=''2551560''>anonymous</span> <span m=''2551800''>name of</span> <span m=''2552130''>something.</span>
  <span m=''2554080''>Now,</span> <span m=''2557630''>if</span> <span m=''2557740''>you</span>
  <span m=''2557860''>really</span> <span m=''2558090''>want</span> <span m=''2558330''>to
  know</span> <span m=''2558510''>a cute</span> <span m=''2558770''>way</span> <span
  m=''2558990''>of</span> <span m=''2559060''>doing</span> <span m=''2559350''>this,</span>
  <span m=''2559780''>we''ll</span> <span m=''2559890''>talk</span> <span m=''2560030''>about
  it</span> <span m=''2560200''>later.</span> <span m=''2561820''>We''re</span> <span
  m=''2562000''>going to</span> <span m=''2562130''>have</span> <span m=''2562330''>to</span>
  <span m=''2563270''>define</span> <span m=''2563710''>the</span> <span m=''2564040''>anonymous</span>
  <span m=''2564190''>procedure.</span> <span m=''2564680''>Any</span> <span m=''2565065''>other</span>
  <span m=''2565450''>questions?</span> <span m=''2569116''>And</span> <span m=''2569580''>so</span>
  <span m=''2569770''>we</span> <span m=''2569890''>go</span> <span m=''2570030''>for</span>
  <span m=''2570180''>our</span> <span m=''2570250''>break</span> <span m=''2570450''>again.</span>
  </p><p><span m=''2611740''>So</span> <span m=''2611970''>now</span> <span m=''2612160''>we''ve</span>
  <span m=''2612350''>seen</span> <span m=''2614070''>how to</span> <span m=''2614260''>use</span>
  <span m=''2614900''>high-order</span> <span m=''2615380''>procedures,</span> <span
  m=''2615940''>they''re</span> <span m=''2616090''>called.</span> <span m=''2616490''>That''s</span>
  <span m=''2616710''>procedures</span> <span m=''2617170''>that</span> <span m=''2617300''>take</span>
  <span m=''2617430''>procedural</span> <span m=''2617970''>arguments</span> <span
  m=''2618410''>and</span> <span m=''2618570''>produce</span> <span m=''2618880''>procedural</span>
  <span m=''2619330''>values</span> <span m=''2620260''>to</span> <span m=''2620620''>help</span>
  <span m=''2620840''>us</span> <span m=''2620960''>clarify</span> <span m=''2621650''>and</span>
  <span m=''2622080''>abstract</span> <span m=''2623310''>some</span> <span m=''2623570''>otherwise</span>
  <span m=''2624020''>complicated</span> <span m=''2624540''>processes.</span> <span
  m=''2626470''>I</span> <span m=''2626590''>suppose what I''d</span> <span m=''2626860''>like</span>
  <span m=''2627010''>to</span> <span m=''2627210''>do</span> <span m=''2627340''>now</span>
  <span m=''2627590''>is</span> <span m=''2627680''>have</span> <span m=''2627820''>a</span>
  <span m=''2627860''>bit</span> <span m=''2628020''>of</span> <span m=''2628080''>fun</span>
  <span m=''2628320''>with</span> <span m=''2628500''>that</span> <span m=''2629770''>and</span>
  <span m=''2631670''>sort</span> <span m=''2631820''>of</span> <span m=''2631970''>a</span>
  <span m=''2632000''>little</span> <span m=''2632200''>practice</span> <span m=''2632640''>as</span>
  <span m=''2632760''>well.</span> <span m=''2634080''>So</span> <span m=''2634250''>let''s</span>
  <span m=''2634420''>play</span> <span m=''2634650''>with</span> <span m=''2634800''>this</span>
  <span m=''2634890''>square</span> <span m=''2635270''>root</span> <span m=''2635470''>thing</span>
  <span m=''2635600''>even</span> <span m=''2635910''>more.</span> <span m=''2636290''>Let''s</span>
  <span m=''2636490''>elaborate</span> <span m=''2636895''>it</span> <span m=''2637500''>and</span>
  <span m=''2637690''>understand</span> <span m=''2638160''>what''s</span> <span m=''2638360''>going</span>
  <span m=''2638630''>on</span> <span m=''2639550''>and</span> <span m=''2639800''>make</span>
  <span m=''2639990''>use</span> <span m=''2640170''>of</span> <span m=''2640280''>this</span>
  <span m=''2640400''>kind</span> <span m=''2640590''>of</span> <span m=''2641170''>programming</span>
  <span m=''2641640''>style.</span> </p><p><span m=''2644270''>One</span> <span m=''2644600''>thing</span>
  <span m=''2644790''>that</span> <span m=''2646730''>you</span> <span m=''2646880''>might</span>
  <span m=''2647140''>know</span> <span m=''2647660''>is</span> <span m=''2647810''>that</span>
  <span m=''2647940''>there</span> <span m=''2648070''>is</span> <span m=''2648170''>a</span>
  <span m=''2648370''>general</span> <span m=''2648680''>method</span> <span m=''2649000''>called</span>
  <span m=''2649280''>Newton''s</span> <span m=''2649600''>method</span> <span m=''2651150''>the</span>
  <span m=''2651470''>purpose</span> <span m=''2651800''>of</span> <span m=''2651910''>which</span>
  <span m=''2652640''>is</span> <span m=''2652840''>to</span> <span m=''2652990''>find</span>
  <span m=''2653430''>the</span> <span m=''2653960''>roots--</span> <span m=''2655180''>that''s</span>
  <span m=''2655420''>the</span> <span m=''2655680''>zeroes--</span> <span m=''2657280''>of</span>
  <span m=''2657570''>functions.</span> <span m=''2659130''>So,</span> <span m=''2659400''>for</span>
  <span m=''2659590''>example,</span> <span m=''2661070''>to</span> <span m=''2661260''>find</span>
  <span m=''2661570''>a</span> <span m=''2661620''>y</span> <span m=''2667920''>such</span>
  <span m=''2668350''>that</span> <span m=''2674380''>f of</span> <span m=''2674740''>y</span>
  <span m=''2676410''>equals</span> <span m=''2676890''>0,</span> <span m=''2678180''>we</span>
  <span m=''2678420''>start</span> <span m=''2678800''>with</span> <span m=''2678940''>some</span>
  <span m=''2679170''>guess.</span> <span m=''2680280''>This is</span> <span m=''2680500''>Newton''s</span>
  <span m=''2680810''>method.</span> <span m=''2691260''>And</span> <span m=''2691520''>the</span>
  <span m=''2691600''>guess</span> <span m=''2692050''>we</span> <span m=''2692210''>start</span>
  <span m=''2692520''>with</span> <span m=''2692740''>we''ll</span> <span m=''2692960''>call</span>
  <span m=''2693190''>y0,</span> <span m=''2695380''>and</span> <span m=''2695580''>then</span>
  <span m=''2695740''>we</span> <span m=''2695860''>will</span> <span m=''2696100''>iterate</span>
  <span m=''2696780''>the</span> <span m=''2696940''>following</span> <span m=''2698870''>expression.</span>
  </p><p><span m=''2701100''>y</span> <span m=''2701500''>n</span> <span m=''2701890''>plus</span>
  <span m=''2702200''>1--</span> <span m=''2702700''>this</span> <span m=''2702950''>is</span>
  <span m=''2703040''>a</span> <span m=''2703200''>difference</span> <span m=''2703580''>equation--</span>
  <span m=''2704880''>is</span> <span m=''2705660''>yn</span> <span m=''2707800''>minus</span>
  <span m=''2709430''>f of</span> <span m=''2709740''>yn</span> <span m=''2712340''>over</span>
  <span m=''2713220''>the</span> <span m=''2713490''>derivative</span> <span m=''2714150''>with</span>
  <span m=''2714380''>respect</span> <span m=''2715310''>to</span> <span m=''2715600''>y</span>
  <span m=''2717366''>of</span> <span m=''2717770''>f</span> <span m=''2718730''>evaluated</span>
  <span m=''2719760''>at</span> <span m=''2720210''>y</span> <span m=''2720760''>equal</span>
  <span m=''2721210''>yn.</span> <span m=''2723270''>Very</span> <span m=''2723530''>strange</span>
  <span m=''2723890''>notation.</span> <span m=''2726430''>I</span> <span m=''2727160''>must</span>
  <span m=''2727440''>say</span> <span m=''2728856''>ugh.</span> <span m=''2731700''>The</span>
  <span m=''2731760''>derivative</span> <span m=''2732220''>of</span> <span m=''2732360''>f</span>
  <span m=''2733110''>with</span> <span m=''2733230''>respect</span> <span m=''2733690''>to</span>
  <span m=''2733780''>y</span> <span m=''2734100''>is</span> <span m=''2734350''>a</span>
  <span m=''2734450''>function.</span> <span m=''2735990''>I''m</span> <span m=''2736030''>having</span>
  <span m=''2736330''>a</span> <span m=''2736390''>little</span> <span m=''2736590''>bit</span>
  <span m=''2736720''>of</span> <span m=''2736820''>unhappiness</span> <span m=''2737420''>with</span>
  <span m=''2737570''>that,</span> <span m=''2738180''>but</span> <span m=''2738420''>that''s</span>
  <span m=''2738680''>all</span> <span m=''2738900''>right.</span> <span m=''2739120''>It</span>
  <span m=''2739490''>turns</span> <span m=''2739750''>out in</span> <span m=''2739960''>the</span>
  <span m=''2740050''>programming</span> <span m=''2740440''>language</span> <span
  m=''2740750''>world,</span> <span m=''2741050''>the</span> <span m=''2741350''>notation</span>
  <span m=''2741610''>is</span> <span m=''2741870''>much</span> <span m=''2742070''>clearer.</span>
  </p><p><span m=''2743930''>Now,</span> <span m=''2744100''>what</span> <span m=''2744280''>is</span>
  <span m=''2744430''>this?</span> <span m=''2745950''>People</span> <span m=''2746170''>call
  it</span> <span m=''2746530''>Newton''s</span> <span m=''2746830''>method.</span>
  <span m=''2747330''>It''s a</span> <span m=''2747400''>method</span> <span m=''2748480''>for</span>
  <span m=''2748600''>finding</span> <span m=''2749240''>the</span> <span m=''2749660''>roots</span>
  <span m=''2750190''>of</span> <span m=''2750530''>the</span> <span m=''2751870''>function</span>
  <span m=''2752280''>f.</span> <span m=''2754250''>And it,</span> <span m=''2754520''>of</span>
  <span m=''2754630''>course,</span> <span m=''2755070''>sometimes</span> <span m=''2755580''>converges,</span>
  <span m=''2755970''>and when</span> <span m=''2756100''>it</span> <span m=''2756330''>does,
  it</span> <span m=''2756490''>does</span> <span m=''2756720''>so</span> <span m=''2756820''>very</span>
  <span m=''2757190''>fast.</span> <span m=''2758420''>And</span> <span m=''2758690''>sometimes,
  it</span> <span m=''2759030''>doesn''t</span> <span m=''2759310''>converge,</span>
  <span m=''2760270''>and,</span> <span m=''2760930''>oh</span> <span m=''2761140''>well,</span>
  <span m=''2761450''>we</span> <span m=''2761540''>have</span> <span m=''2761700''>to</span>
  <span m=''2761760''>do</span> <span m=''2761860''>something</span> <span m=''2762250''>else.</span>
  <span m=''2763230''>But</span> <span m=''2763390''>let''s</span> <span m=''2763810''>talk</span>
  <span m=''2764040''>about</span> <span m=''2764500''>square root</span> <span m=''2764960''>by</span>
  <span m=''2765100''>Newton''s</span> <span m=''2765450''>method.</span> </p><p><span
  m=''2767190''>Well,</span> <span m=''2767310''>that''s</span> <span m=''2767960''>rather</span>
  <span m=''2768260''>interesting.</span> <span m=''2768680''>Let''s</span> <span
  m=''2768850''>do</span> <span m=''2768990''>exactly</span> <span m=''2769450''>the</span>
  <span m=''2769550''>same</span> <span m=''2769760''>thing</span> <span m=''2769900''>we</span>
  <span m=''2769990''>did</span> <span m=''2770150''>last</span> <span m=''2770430''>time:</span>
  <span m=''2771030''>a</span> <span m=''2771150''>bit</span> <span m=''2771340''>of</span>
  <span m=''2771470''>wishful</span> <span m=''2771800''>thinking.</span> <span m=''2773490''>We</span>
  <span m=''2773710''>will</span> <span m=''2773870''>apply</span> <span m=''2774230''>Newton''s</span>
  <span m=''2774520''>method,</span> <span m=''2775410''>assuming</span> <span m=''2775790''>we</span>
  <span m=''2775930''>knew</span> <span m=''2776080''>how</span> <span m=''2776180''>to</span>
  <span m=''2776290''>do</span> <span m=''2776510''>it.</span> <span m=''2778210''>You</span>
  <span m=''2778400''>don''t</span> <span m=''2778540''>know</span> <span m=''2778600''>how</span>
  <span m=''2778700''>to</span> <span m=''2778800''>do</span> <span m=''2778990''>it</span>
  <span m=''2779110''>yet.</span> <span m=''2780620''>Well,</span> <span m=''2780960''>let''s</span>
  <span m=''2781130''>go.</span> <span m=''2785090''>What do</span> <span m=''2785530''>I</span>
  <span m=''2785620''>have</span> <span m=''2785860''>here?</span> <span m=''2786070''>The</span>
  <span m=''2786150''>square root of</span> <span m=''2786620''>x.</span> <span m=''2791410''>It''s</span>
  <span m=''2791670''>Newton''s</span> <span m=''2792040''>method</span> <span m=''2795740''>applied</span>
  <span m=''2796190''>to</span> <span m=''2796380''>a</span> <span m=''2796430''>procedure</span>
  <span m=''2797050''>which</span> <span m=''2797290''>will</span> <span m=''2797480''>represent</span>
  <span m=''2798330''>that</span> <span m=''2798610''>function</span> <span m=''2798940''>of</span>
  <span m=''2799050''>y,</span> <span m=''2799450''>which</span> <span m=''2799610''>computes</span>
  <span m=''2799990''>that</span> <span m=''2800210''>function of</span> <span m=''2800520''>y.</span>
  <span m=''2802480''>Well,</span> <span m=''2802670''>that</span> <span m=''2802850''>procedure</span>
  <span m=''2804210''>is</span> <span m=''2804430''>that</span> <span m=''2804640''>procedure</span>
  <span m=''2805300''>of</span> <span m=''2805510''>y,</span> <span m=''2807300''>which</span>
  <span m=''2808080''>is</span> <span m=''2808640''>the</span> <span m=''2808820''>difference</span>
  <span m=''2809410''>between</span> <span m=''2809970''>x</span> <span m=''2810750''>and</span>
  <span m=''2810930''>the</span> <span m=''2810980''>square</span> <span m=''2811400''>of
  y.</span> <span m=''2820080''>Indeed,</span> <span m=''2821340''>if</span> <span
  m=''2821560''>I</span> <span m=''2821840''>had</span> <span m=''2822250''>a</span>
  <span m=''2822410''>value</span> <span m=''2822860''>of</span> <span m=''2822980''>y</span>
  <span m=''2824500''>for</span> <span m=''2824710''>which</span> <span m=''2825040''>this</span>
  <span m=''2825540''>was</span> <span m=''2825740''>zero,</span> <span m=''2827330''>then</span>
  <span m=''2827570''>y</span> <span m=''2827800''>would</span> <span m=''2827960''>be</span>
  <span m=''2828050''>the</span> <span m=''2828130''>square</span> <span m=''2828440''>root</span>
  <span m=''2829460''>of</span> <span m=''2829640''>x.</span> <span m=''2833730''>See</span>
  <span m=''2833910''>that?</span> <span m=''2835550''>OK,</span> <span m=''2836890''>I''m</span>
  <span m=''2837290''>going</span> <span m=''2837370''>to</span> <span m=''2837450''>start</span>
  <span m=''2837730''>this</span> <span m=''2837900''>out</span> <span m=''2838250''>searching</span>
  <span m=''2838590''>at</span> <span m=''2838720''>1.</span> <span m=''2839250''>Again,</span>
  <span m=''2840460''>completely</span> <span m=''2840990''>arbitrary</span> <span
  m=''2841440''>property</span> <span m=''2841940''>of</span> <span m=''2842910''>square</span>
  <span m=''2843200''>roots</span> <span m=''2843430''>that</span> <span m=''2843570''>I</span>
  <span m=''2843700''>can</span> <span m=''2843870''>do</span> <span m=''2844030''>that.</span>
  </p><p><span m=''2847950''>Now,</span> <span m=''2848170''>how am I</span> <span
  m=''2848470''>going to</span> <span m=''2848510''>compute</span> <span m=''2849510''>Newton''s</span>
  <span m=''2849860''>method?</span> <span m=''2851480''>Well,</span> <span m=''2851660''>this</span>
  <span m=''2851910''>is the method.</span> <span m=''2852170''>I</span> <span m=''2852240''>have</span>
  <span m=''2852410''>it</span> <span m=''2852480''>right</span> <span m=''2852680''>here.</span>
  <span m=''2854310''>In</span> <span m=''2854500''>fact,</span> <span m=''2854790''>what</span>
  <span m=''2854890''>I''m</span> <span m=''2854990''>doing</span> <span m=''2855410''>is</span>
  <span m=''2855560''>looking</span> <span m=''2855810''>for</span> <span m=''2855940''>a</span>
  <span m=''2855980''>fixed</span> <span m=''2856290''>point</span> <span m=''2857630''>of</span>
  <span m=''2857740''>some</span> <span m=''2859340''>procedure.</span> <span m=''2861240''>This</span>
  <span m=''2861410''>procedure</span> <span m=''2861870''>involves</span> <span m=''2863030''>some</span>
  <span m=''2863430''>complicated</span> <span m=''2863980''>expressions</span> <span
  m=''2865030''>in</span> <span m=''2865190''>terms</span> <span m=''2865430''>of</span>
  <span m=''2865530''>other</span> <span m=''2866120''>complicated</span> <span m=''2866700''>things.</span>
  <span m=''2867150''>Well,</span> <span m=''2867570''>I''m</span> <span m=''2867730''>trying</span>
  <span m=''2867950''>to</span> <span m=''2868010''>find</span> <span m=''2868190''>the</span>
  <span m=''2868230''>fixed</span> <span m=''2868420''>point of</span> <span m=''2868540''>this.</span>
  <span m=''2868800''>I</span> <span m=''2868880''>want</span> <span m=''2869010''>to</span>
  <span m=''2869140''>find</span> <span m=''2870640''>the</span> <span m=''2871430''>values</span>
  <span m=''2871930''>of</span> <span m=''2872030''>y,</span> <span m=''2872740''>which</span>
  <span m=''2872960''>if I put</span> <span m=''2873130''>y</span> <span m=''2873700''>in</span>
  <span m=''2873770''>here,</span> <span m=''2874540''>I</span> <span m=''2874620''>get</span>
  <span m=''2874750''>the</span> <span m=''2874820''>same</span> <span m=''2875050''>value
  out</span> <span m=''2875340''>here</span> <span m=''2876940''>up</span> <span m=''2877080''>to</span>
  <span m=''2877180''>some</span> <span m=''2877720''>degree</span> <span m=''2877990''>of</span>
  <span m=''2878060''>accuracy.</span> <span m=''2880130''>Well,</span> <span m=''2880300''>I</span>
  <span m=''2880380''>already</span> <span m=''2880670''>have</span> <span m=''2880870''>a</span>
  <span m=''2880910''>fixed</span> <span m=''2881170''>point</span> <span m=''2881410''>process</span>
  <span m=''2882710''>around</span> <span m=''2883050''>to</span> <span m=''2883120''>do</span>
  <span m=''2883310''>that.</span> <span m=''2885040''>And</span> <span m=''2885370''>so,</span>
  <span m=''2885890''>let''s</span> <span m=''2886050''>just define</span> <span m=''2886490''>Newton''s</span>
  <span m=''2886820''>method</span> <span m=''2886990''>over</span> <span m=''2887170''>here.</span>
  </p><p><span m=''2899430''>A</span> <span m=''2900060''>procedure</span> <span m=''2900420''>which</span>
  <span m=''2900540''>computes</span> <span m=''2900850''>a</span> <span m=''2900950''>function</span>
  <span m=''2901490''>and a</span> <span m=''2901680''>guess,</span> <span m=''2904960''>initial</span>
  <span m=''2905290''>guess.</span> <span m=''2906640''>Now,</span> <span m=''2907070''>I''m</span>
  <span m=''2907290''>going</span> <span m=''2907470''>to have to</span> <span m=''2907700''>do</span>
  <span m=''2907850''>something</span> <span m=''2908210''>here.</span> <span m=''2908920''>I''m</span>
  <span m=''2909140''>going</span> <span m=''2909330''>to</span> <span m=''2909400''>need</span>
  <span m=''2909590''>the</span> <span m=''2909640''>derivative</span> <span m=''2910950''>of</span>
  <span m=''2911210''>the</span> <span m=''2912140''>function.</span> <span m=''2913280''>I''m
  going</span> <span m=''2913410''>to</span> <span m=''2913490''>need a</span> <span
  m=''2913680''>procedure</span> <span m=''2914080''>which</span> <span m=''2914220''>computes</span>
  <span m=''2914490''>the</span> <span m=''2914660''>derivative</span> <span m=''2916550''>of</span>
  <span m=''2916740''>the</span> <span m=''2916820''>function</span> <span m=''2917240''>computed</span>
  <span m=''2917730''>by</span> <span m=''2917910''>the</span> <span m=''2918100''>given</span>
  <span m=''2918600''>a</span> <span m=''2918680''>procedure</span> <span m=''2919110''>f.</span>
  <span m=''2922140''>I''m</span> <span m=''2922310''>trying</span> <span m=''2922450''>to</span>
  <span m=''2922590''>be</span> <span m=''2922710''>very</span> <span m=''2922970''>careful</span>
  <span m=''2923310''>about</span> <span m=''2923490''>what</span> <span m=''2923570''>I''m</span>
  <span m=''2923650''>saying.</span> <span m=''2924440''>I</span> <span m=''2924590''>don''t</span>
  <span m=''2924730''>want</span> <span m=''2924810''>to</span> <span m=''2924890''>mix</span>
  <span m=''2925110''>up</span> <span m=''2925240''>the</span> <span m=''2925320''>word</span>
  <span m=''2925580''>procedure</span> <span m=''2925890''>and</span> <span m=''2926000''>function.</span>
  <span m=''2926270''>Function</span> <span m=''2926480''>is a</span> <span m=''2926630''>mathematical</span>
  <span m=''2927240''>word.</span> <span m=''2927875''>It</span> <span m=''2928190''>says</span>
  <span m=''2928620''>I''m</span> <span m=''2928770''>mapping</span> <span m=''2929230''>from</span>
  <span m=''2931300''>values</span> <span m=''2931770''>to</span> <span m=''2931900''>other</span>
  <span m=''2932080''>values,</span> <span m=''2932415''>a</span> <span m=''2932750''>set</span>
  <span m=''2932950''>of</span> <span m=''2933030''>ordered</span> <span m=''2933290''>pairs.</span>
  <span m=''2935430''>But</span> <span m=''2936470''>sometimes,</span> <span m=''2936850''>I''ll</span>
  <span m=''2936990''>accidentally</span> <span m=''2937500''>mix those</span> <span
  m=''2937990''>up.</span> <span m=''2940380''>Procedures</span> <span m=''2940920''>compute</span>
  <span m=''2941370''>functions.</span> </p><p><span m=''2947400''>So</span> <span
  m=''2947940''>I''m</span> <span m=''2948050''>going</span> <span m=''2948190''>to</span>
  <span m=''2948470''>define</span> <span m=''2949080''>the</span> <span m=''2949210''>derivative</span>
  <span m=''2949820''>of</span> <span m=''2949960''>f</span> <span m=''2951100''>to</span>
  <span m=''2951340''>be</span> <span m=''2951780''>by</span> <span m=''2952100''>wishful</span>
  <span m=''2952450''>thinking</span> <span m=''2952700''>again.</span> <span m=''2952930''>I</span>
  <span m=''2953070''>don''t know</span> <span m=''2953200''>how</span> <span m=''2953360''>I''m
  going</span> <span m=''2953490''>to</span> <span m=''2953560''>do</span> <span m=''2953790''>it.</span>
  <span m=''2954720''>Let''s</span> <span m=''2954890''>worry</span> <span m=''2955060''>about</span>
  <span m=''2955260''>that</span> <span m=''2955450''>later--</span> <span m=''2958612''>of</span>
  <span m=''2959089''>F.</span> <span m=''2960520''>So</span> <span m=''2960930''>if  F</span>
  <span m=''2961070''>is</span> <span m=''2961190''>a</span> <span m=''2961250''>procedure,</span>
  <span m=''2963710''>which</span> <span m=''2963900''>happens</span> <span m=''2964320''>to</span>
  <span m=''2964430''>be</span> <span m=''2964800''>this</span> <span m=''2965130''>one</span>
  <span m=''2965340''>over</span> <span m=''2965550''>here</span> <span m=''2965810''>for
  a</span> <span m=''2966020''>square</span> <span m=''2966300''>root,</span> <span
  m=''2969130''>then</span> <span m=''2970520''>DF</span> <span m=''2971000''>will</span>
  <span m=''2971110''>be</span> <span m=''2971260''>the</span> <span m=''2971350''>derivative</span>
  <span m=''2971800''>of</span> <span m=''2971950''>it,</span> <span m=''2972290''>which</span>
  <span m=''2972460''>is</span> <span m=''2972680''>also</span> <span m=''2973850''>the</span>
  <span m=''2973910''>derivative</span> <span m=''2974290''>of</span> <span m=''2974410''>the</span>
  <span m=''2974530''>function</span> <span m=''2974890''>computed</span> <span m=''2975200''>by</span>
  <span m=''2975320''>that</span> <span m=''2975480''>procedure.</span> <span m=''2976080''>DF</span>
  <span m=''2976340''>will</span> <span m=''2976440''>be</span> <span m=''2976530''>a</span>
  <span m=''2976590''>procedure</span> <span m=''2976980''>that</span> <span m=''2977380''>computes</span>
  <span m=''2977970''>the</span> <span m=''2978130''>derivative</span> <span m=''2978395''>of</span>
  <span m=''2978660''>the</span> <span m=''2978760''>function</span> <span m=''2979490''>computed</span>
  <span m=''2979950''>by</span> <span m=''2980060''>the</span> <span m=''2980170''>procedure</span>
  <span m=''2980570''>F.</span> <span m=''2982240''>And</span> <span m=''2982460''>then</span>
  <span m=''2982650''>given</span> <span m=''2982920''>that,</span> <span m=''2983240''>I</span>
  <span m=''2983360''>will</span> <span m=''2983490''>just</span> <span m=''2983630''>go</span>
  <span m=''2983800''>looking</span> <span m=''2984060''>for a</span> <span m=''2984240''>fixed</span>
  <span m=''2984480''>point.</span> </p><p><span m=''2991910''>What</span> <span m=''2992100''>is</span>
  <span m=''2992220''>the</span> <span m=''2992310''>fixed</span> <span m=''2992640''>point</span>
  <span m=''2992880''>I''m</span> <span m=''2992980''>looking</span> <span m=''2993220''>for?</span>
  <span m=''2993710''>It''s</span> <span m=''2993900''>the</span> <span m=''2993990''>one</span>
  <span m=''2994240''>for</span> <span m=''2994350''>that</span> <span m=''2994640''>procedure</span>
  <span m=''2995460''>of</span> <span m=''2995610''>one</span> <span m=''2995760''>argument</span>
  <span m=''2996250''>x,</span> <span m=''2997580''>which</span> <span m=''2998530''>I</span>
  <span m=''2998750''>compute</span> <span m=''2999150''>by</span> <span m=''2999350''>subtracting</span>
  <span m=''3000050''>x.</span> <span m=''3000500''>That''s the</span> <span m=''3000640''>old--</span>
  <span m=''3000970''>that''s</span> <span m=''3001910''>the</span> <span m=''3002080''>yn</span>
  <span m=''3002670''>here.</span> <span m=''3004870''>The</span> <span m=''3005400''>quotient</span>
  <span m=''3007120''>of</span> <span m=''3007860''>f</span> <span m=''3009270''>of</span>
  <span m=''3009500''>x</span> <span m=''3010400''>and</span> <span m=''3010950''>df
  of</span> <span m=''3011350''>x,</span> <span m=''3020470''>starting</span> <span
  m=''3020860''>out with</span> <span m=''3021030''>the</span> <span m=''3021110''>original</span>
  <span m=''3021450''>guess.</span> <span m=''3029450''>That''s</span> <span m=''3030050''>all</span>
  <span m=''3030170''>very</span> <span m=''3030400''>simple.</span> </p><p><span
  m=''3032640''>Now,</span> <span m=''3032780''>I</span> <span m=''3032880''>have</span>
  <span m=''3032980''>one</span> <span m=''3033180''>part</span> <span m=''3033420''>left
  that</span> <span m=''3033700''>I</span> <span m=''3033820''>haven''t</span> <span
  m=''3034040''>written,</span> <span m=''3034780''>and</span> <span m=''3034860''>I</span>
  <span m=''3034950''>want you</span> <span m=''3035310''>to</span> <span m=''3035380''>see</span>
  <span m=''3035690''>the</span> <span m=''3035830''>process</span> <span m=''3036310''>by</span>
  <span m=''3036460''>which</span> <span m=''3036690''>I</span> <span m=''3036740''>write</span>
  <span m=''3037000''>these</span> <span m=''3037180''>things,</span> <span m=''3037720''>because</span>
  <span m=''3037840''>this</span> <span m=''3038020''>is</span> <span m=''3038130''>really</span>
  <span m=''3038460''>true.</span> <span m=''3040150''>I</span> <span m=''3040300''>start</span>
  <span m=''3040530''>out</span> <span m=''3040630''>with</span> <span m=''3040790''>some</span>
  <span m=''3040840''>mathematical</span> <span m=''3041610''>idea,</span> <span m=''3041920''>perhaps.</span>
  <span m=''3043810''>By</span> <span m=''3044020''>wishful</span> <span m=''3044400''>thinking,</span>
  <span m=''3044710''>I</span> <span m=''3045460''>assume</span> <span m=''3046560''>that</span>
  <span m=''3046960''>by</span> <span m=''3047240''>some</span> <span m=''3047520''>magic</span>
  <span m=''3048010''>I</span> <span m=''3048100''>can</span> <span m=''3048280''>do</span>
  <span m=''3048440''>something that</span> <span m=''3048790''>I</span> <span m=''3048870''>have</span>
  <span m=''3048960''>a</span> <span m=''3049020''>name</span> <span m=''3049270''>for.</span>
  <span m=''3050980''>I''m not going to</span> <span m=''3051290''>worry</span> <span
  m=''3051530''>about</span> <span m=''3051730''>how</span> <span m=''3051900''>I</span>
  <span m=''3052010''>do it</span> <span m=''3052190''>yet.</span> <span m=''3054850''>Then</span>
  <span m=''3055000''>I</span> <span m=''3055070''>go</span> <span m=''3055190''>walking</span>
  <span m=''3055540''>down</span> <span m=''3055730''>here</span> <span m=''3055870''>and</span>
  <span m=''3055990''>say,</span> <span m=''3056050''>well,</span> <span m=''3056480''>by</span>
  <span m=''3056720''>some</span> <span m=''3056990''>magic,</span> <span m=''3057970''>I''m</span>
  <span m=''3058120''>somehow</span> <span m=''3058280''>going to</span> <span m=''3058460''>figure</span>
  <span m=''3058620''>how</span> <span m=''3058810''>to</span> <span m=''3058920''>do</span>
  <span m=''3059030''>that,</span> <span m=''3060930''>but</span> <span m=''3061090''>I''m
  going to</span> <span m=''3061170''>write</span> <span m=''3061380''>my</span> <span
  m=''3061480''>program</span> <span m=''3061890''>anyway.</span> <span m=''3064330''>Wishful</span>
  <span m=''3064700''>thinking,</span> <span m=''3065300''>essential</span> <span
  m=''3065820''>to</span> <span m=''3065900''>good</span> <span m=''3066040''>engineering,</span>
  <span m=''3067780''>and</span> <span m=''3067990''>certainly</span> <span m=''3068310''>essential</span>
  <span m=''3068700''>to</span> <span m=''3068790''>a</span> <span m=''3069300''>good</span>
  <span m=''3069340''>computer</span> <span m=''3069680''>science.</span> </p><p><span
  m=''3072770''>So</span> <span m=''3072950''>anyway,</span> <span m=''3074910''>how</span>
  <span m=''3075120''>many of</span> <span m=''3075210''>you</span> <span m=''3075420''>wished</span>
  <span m=''3075650''>that</span> <span m=''3075790''>your</span> <span m=''3075900''>computer</span>
  <span m=''3076220''>ran</span> <span m=''3076470''>faster?</span> <span m=''3081120''>Well,</span>
  <span m=''3081510''>the</span> <span m=''3081600''>derivative</span> <span m=''3082070''>isn''t</span>
  <span m=''3082260''>so</span> <span m=''3082380''>bad</span> <span m=''3082610''>either.</span>
  <span m=''3083390''>Sort of</span> <span m=''3083650''>like</span> <span m=''3083850''>average</span>
  <span m=''3084210''>damping.</span> <span m=''3088922''>The</span> <span m=''3089400''>derivative</span>
  <span m=''3089890''>is</span> <span m=''3090030''>a</span> <span m=''3090100''>procedure</span>
  <span m=''3091680''>that</span> <span m=''3092160''>takes</span> <span m=''3093000''>a</span>
  <span m=''3093450''>procedure</span> <span m=''3093890''>that</span> <span m=''3094010''>computes</span>
  <span m=''3094320''>a</span> <span m=''3094440''>function</span> <span m=''3094820''>as</span>
  <span m=''3094940''>its</span> <span m=''3095070''>argument,</span> <span m=''3097320''>and</span>
  <span m=''3097450''>it</span> <span m=''3097590''>produces</span> <span m=''3098410''>a</span>
  <span m=''3098560''>procedure</span> <span m=''3100190''>that</span> <span m=''3100570''>computes</span>
  <span m=''3100810''>a</span> <span m=''3100940''>function,</span> <span m=''3101580''>which</span>
  <span m=''3101820''>needs</span> <span m=''3102050''>one</span> <span m=''3102230''>argument</span>
  <span m=''3102730''>x.</span> <span m=''3103930''>Well,</span> <span m=''3104230''>you</span>
  <span m=''3104360''>all</span> <span m=''3104510''>know</span> <span m=''3104620''>this</span>
  <span m=''3104810''>definition.</span> <span m=''3106270''>It''s</span> <span m=''3106470''>f
  of</span> <span m=''3106640''>x</span> <span m=''3106860''>plus</span> <span m=''3106950''>delta</span>
  <span m=''3107140''>x</span> <span m=''3107370''>minus</span> <span m=''3107610''>f
  of x</span> <span m=''3107930''>over</span> <span m=''3108080''>delta</span> <span
  m=''3108360''>x,</span> <span m=''3108570''>right?</span> <span m=''3109040''>For</span>
  <span m=''3109170''>some</span> <span m=''3109310''>small</span> <span m=''3109590''>delta</span>
  <span m=''3109890''>x.</span> <span m=''3110800''>So</span> <span m=''3111050''>that''s</span>
  <span m=''3111370''>the</span> <span m=''3112440''>quotient</span> <span m=''3113730''>of</span>
  <span m=''3114120''>the</span> <span m=''3114270''>difference</span> <span m=''3115856''>of</span>
  <span m=''3116260''>f</span> <span m=''3117200''>of</span> <span m=''3117680''>the</span>
  <span m=''3118160''>sum</span> <span m=''3119472''>of</span> <span m=''3119850''>x</span>
  <span m=''3120610''>and</span> <span m=''3121090''>dx</span> <span m=''3124610''>minus</span>
  <span m=''3125710''>f</span> <span m=''3126720''>point</span> <span m=''3127010''>x</span>
  <span m=''3129470''>divided</span> <span m=''3129880''>by</span> <span m=''3130030''>dx.</span>
  <span m=''3138530''>I think</span> <span m=''3138940''>the thing was</span> <span
  m=''3139060''>lining</span> <span m=''3139340''>up</span> <span m=''3139460''>correctly</span>
  <span m=''3139870''>when</span> <span m=''3140000''>I</span> <span m=''3141110''>balanced</span>
  <span m=''3141360''>the</span> <span m=''3141440''>parentheses.</span> </p><p><span
  m=''3145120''>Now, I</span> <span m=''3145320''>want you to</span> <span m=''3145510''>look</span>
  <span m=''3145790''>at</span> <span m=''3146040''>this.</span> <span m=''3147070''>Just</span>
  <span m=''3147410''>look.</span> <span m=''3151330''>I</span> <span m=''3151500''>suppose
  I</span> <span m=''3151710''>haven''t</span> <span m=''3152010''>told</span> <span
  m=''3152190''>you</span> <span m=''3152270''>what</span> <span m=''3152410''>dx</span>
  <span m=''3152850''>is.</span> <span m=''3153220''>Somewhere</span> <span m=''3154000''>in</span>
  <span m=''3154310''>the</span> <span m=''3154490''>world</span> <span m=''3154770''>I''m
  going to</span> <span m=''3154900''>have</span> <span m=''3155020''>to</span> <span
  m=''3155150''>write</span> <span m=''3155370''>down</span> <span m=''3164880''>something</span>
  <span m=''3165170''>like</span> <span m=''3165390''>that.</span> <span m=''3165770''>I''m</span>
  <span m=''3166270''>not</span> <span m=''3166510''>interested.</span> <span m=''3168150''>This</span>
  <span m=''3168450''>is</span> <span m=''3168520''>a</span> <span m=''3168600''>procedure</span>
  <span m=''3169810''>which</span> <span m=''3170030''>takes</span> <span m=''3170270''>a</span>
  <span m=''3170340''>procedure</span> <span m=''3172310''>and</span> <span m=''3172520''>produces</span>
  <span m=''3172970''>an</span> <span m=''3173040''>approximation,</span> <span m=''3174050''>a</span>
  <span m=''3174400''>procedure</span> <span m=''3174740''>that</span> <span m=''3174840''>computes</span>
  <span m=''3175250''>an</span> <span m=''3175330''>approximation</span> <span m=''3175950''>of</span>
  <span m=''3176040''>the</span> <span m=''3176090''>derivative</span> <span m=''3176890''>of</span>
  <span m=''3177000''>the</span> <span m=''3177110''>function</span> <span m=''3177490''>computed</span>
  <span m=''3177770''>by</span> <span m=''3177910''>the</span> <span m=''3178010''>procedure</span>
  <span m=''3178440''>given</span> <span m=''3181150''>by</span> <span m=''3181360''>the</span>
  <span m=''3181560''>standard</span> <span m=''3181950''>methods</span> <span m=''3182300''>that</span>
  <span m=''3182430''>you</span> <span m=''3182580''>all</span> <span m=''3182740''>know</span>
  <span m=''3182920''>and</span> <span m=''3183000''>love.</span> </p><p><span m=''3184800''>Now,</span>
  <span m=''3185130''>it</span> <span m=''3185300''>may</span> <span m=''3185440''>not</span>
  <span m=''3185620''>be</span> <span m=''3185730''>the</span> <span m=''3185830''>case</span>
  <span m=''3186500''>that</span> <span m=''3187410''>doing</span> <span m=''3187840''>this</span>
  <span m=''3188000''>operation</span> <span m=''3188830''>is such</span> <span m=''3189010''>a</span>
  <span m=''3189180''>good</span> <span m=''3189350''>way</span> <span m=''3189600''>of</span>
  <span m=''3189710''>approximating</span> <span m=''3190300''>a</span> <span m=''3190350''>derivative.</span>
  <span m=''3191390''>Numerical</span> <span m=''3192860''>analysts</span> <span m=''3193280''>here</span>
  <span m=''3194020''>should</span> <span m=''3194220''>jump</span> <span m=''3194460''>on</span>
  <span m=''3194590''>me</span> <span m=''3194660''>and</span> <span m=''3194800''>say</span>
  <span m=''3195140''>don''t</span> <span m=''3195310''>do</span> <span m=''3195410''>that.</span>
  <span m=''3196690''>Computing</span> <span m=''3197040''>derivatives</span> <span
  m=''3197410''>produces</span> <span m=''3197720''>noisy</span> <span m=''3198070''>answers,</span>
  <span m=''3198450''>which</span> <span m=''3198580''>is</span> <span m=''3198680''>true.</span>
  <span m=''3200150''>However,</span> <span m=''3200640''>this</span> <span m=''3200800''>again</span>
  <span m=''3202180''>is</span> <span m=''3202400''>for</span> <span m=''3202500''>the</span>
  <span m=''3202600''>sake</span> <span m=''3202930''>of</span> <span m=''3203040''>understanding.</span>
  <span m=''3204850''>Look</span> <span m=''3205000''>what</span> <span m=''3205100''>we''ve</span>
  <span m=''3205280''>got.</span> <span m=''3206620''>We</span> <span m=''3206770''>started</span>
  <span m=''3207180''>out</span> <span m=''3207400''>with</span> <span m=''3207500''>what</span>
  <span m=''3207800''>is</span> <span m=''3207970''>apparently a</span> <span m=''3208470''>mathematically</span>
  <span m=''3209040''>complex</span> <span m=''3209530''>thing.</span> <span m=''3211210''>and.</span>
  <span m=''3211610''>In</span> <span m=''3211760''>a</span> <span m=''3211810''>few</span>
  <span m=''3212020''>blackboards</span> <span m=''3212640''>full,</span> <span m=''3214140''>we</span>
  <span m=''3214280''>managed</span> <span m=''3214680''>to</span> <span m=''3214750''>decompose</span>
  <span m=''3215290''>the</span> <span m=''3215370''>problem</span> <span m=''3216200''>of</span>
  <span m=''3216340''>computing</span> <span m=''3216680''>square</span> <span m=''3216950''>roots</span>
  <span m=''3217230''>by</span> <span m=''3217390''>the</span> <span m=''3217490''>way</span>
  <span m=''3217700''>you</span> <span m=''3217800''>were</span> <span m=''3217900''>taught</span>
  <span m=''3218190''>in</span> <span m=''3218970''>your</span> <span m=''3219110''>college</span>
  <span m=''3219460''>calculus</span> <span m=''3219960''>class--</span> <span m=''3221770''>Newton''s</span>
  <span m=''3222120''>method--</span> <span m=''3223720''>so</span> <span m=''3223910''>that
  it</span> <span m=''3224060''>can</span> <span m=''3224220''>be</span> <span m=''3224330''>understood.</span>
  <span m=''3225830''>It''s</span> <span m=''3226030''>clear.</span> </p><p><span
  m=''3227840''>Let''s</span> <span m=''3228040''>look</span> <span m=''3228160''>at</span>
  <span m=''3228280''>the</span> <span m=''3228340''>structure of</span> <span m=''3228830''>what</span>
  <span m=''3229070''>it</span> <span m=''3229200''>is</span> <span m=''3229330''>we''ve</span>
  <span m=''3229520''>got.</span> <span m=''3231231''>Let''s</span> <span m=''3231650''>look</span>
  <span m=''3231840''>at</span> <span m=''3232010''>this</span> <span m=''3232180''>slide.</span>
  <span m=''3234660''>This</span> <span m=''3236000''>is</span> <span m=''3236150''>a</span>
  <span m=''3237340''>diagram</span> <span m=''3238750''>of</span> <span m=''3238940''>the</span>
  <span m=''3239050''>machine</span> <span m=''3239640''>described</span> <span m=''3241960''>by</span>
  <span m=''3242210''>the</span> <span m=''3243110''>program</span> <span m=''3243610''>on</span>
  <span m=''3243720''>the</span> <span m=''3243790''>blackboard.</span> <span m=''3245520''>There''s</span>
  <span m=''3245795''>a</span> <span m=''3246070''>machine</span> <span m=''3246460''>described</span>
  <span m=''3247010''>here.</span> <span m=''3248940''>And what have</span> <span
  m=''3249200''>I</span> <span m=''3249300''>got?</span> <span m=''3250700''>Over</span>
  <span m=''3250930''>here</span> <span m=''3252140''>is</span> <span m=''3252350''>the</span>
  <span m=''3252710''>Newton''s</span> <span m=''3253280''>method</span> <span m=''3256090''>function</span>
  <span m=''3256510''>f</span> <span m=''3257230''>that</span> <span m=''3257390''>we</span>
  <span m=''3257470''>have</span> <span m=''3257690''>on</span> <span m=''3257850''>the</span>
  <span m=''3258220''>left-most</span> <span m=''3258790''>blackboard.</span> <span
  m=''3261040''>It''s</span> <span m=''3261190''>the</span> <span m=''3261280''>thing</span>
  <span m=''3261470''>that</span> <span m=''3261590''>takes</span> <span m=''3261840''>an</span>
  <span m=''3261910''>argument</span> <span m=''3262250''>called</span> <span m=''3262480''>y</span>
  <span m=''3263120''>and</span> <span m=''3263340''>puts</span> <span m=''3263590''>out</span>
  <span m=''3264990''>the</span> <span m=''3265070''>difference</span> <span m=''3265450''>between</span>
  <span m=''3266190''>x</span> <span m=''3266450''>and the</span> <span m=''3266670''>square
  of</span> <span m=''3267000''>y,</span> <span m=''3270040''>where</span> <span m=''3270270''>x</span>
  <span m=''3270640''>is</span> <span m=''3272500''>some</span> <span m=''3272730''>sort</span>
  <span m=''3272840''>of</span> <span m=''3272960''>free</span> <span m=''3273220''>variable</span>
  <span m=''3273740''>that</span> <span m=''3273880''>comes</span> <span m=''3274130''>in</span>
  <span m=''3274250''>from</span> <span m=''3274360''>the</span> <span m=''3274480''>outside</span>
  <span m=''3275400''>by</span> <span m=''3275550''>some</span> <span m=''3275770''>magic.</span>
  <span m=''3278050''>So</span> <span m=''3278210''>the</span> <span m=''3278310''>square</span>
  <span m=''3278760''>root</span> <span m=''3278810''>routine</span> <span m=''3279730''>picks</span>
  <span m=''3279980''>up</span> <span m=''3280120''>an</span> <span m=''3280240''>x,</span>
  <span m=''3282470''>and</span> <span m=''3282770''>builds</span> <span m=''3283220''>this</span>
  <span m=''3283430''>procedure,</span> <span m=''3285670''>which I</span> <span m=''3285840''>have</span>
  <span m=''3286030''>the</span> <span m=''3286150''>x</span> <span m=''3286370''>rolled</span>
  <span m=''3286640''>up</span> <span m=''3286770''>in</span> <span m=''3286860''>it</span>
  <span m=''3287580''>by</span> <span m=''3287750''>substitution.</span> </p><p><span
  m=''3290170''>Now,</span> <span m=''3290490''>this</span> <span m=''3290870''>procedure</span>
  <span m=''3291880''>in</span> <span m=''3292060''>the</span> <span m=''3292140''>cloud</span>
  <span m=''3293740''>is</span> <span m=''3293960''>fed</span> <span m=''3294160''>in</span>
  <span m=''3294400''>as</span> <span m=''3294610''>the</span> <span m=''3294760''>f</span>
  <span m=''3298490''>into</span> <span m=''3298930''>the</span> <span m=''3299040''>Newton''s</span>
  <span m=''3299310''>method</span> <span m=''3300140''>which</span> <span m=''3300290''>is</span>
  <span m=''3300380''>here,</span> <span m=''3300880''>this</span> <span m=''3301140''>box.</span>
  <span m=''3304650''>The</span> <span m=''3305810''>f</span> <span m=''3306780''>is</span>
  <span m=''3307510''>fanned out.</span> <span m=''3308790''>Part</span> <span m=''3308920''>of</span>
  <span m=''3309050''>it</span> <span m=''3309160''>goes</span> <span m=''3309400''>into</span>
  <span m=''3309930''>something</span> <span m=''3310390''>else,</span> <span m=''3311200''>and</span>
  <span m=''3311370''>the</span> <span m=''3311540''>other</span> <span m=''3311720''>part</span>
  <span m=''3311860''>of</span> <span m=''3312010''>it</span> <span m=''3312130''>goes</span>
  <span m=''3312260''>through</span> <span m=''3312450''>a</span> <span m=''3312500''>derivative</span>
  <span m=''3312920''>process</span> <span m=''3313490''>into</span> <span m=''3313720''>something</span>
  <span m=''3314150''>else</span> <span m=''3315470''>to</span> <span m=''3315670''>produce</span>
  <span m=''3316590''>a</span> <span m=''3316750''>procedure,</span> <span m=''3318180''>which</span>
  <span m=''3318410''>computes</span> <span m=''3318790''>the</span> <span m=''3318890''>function</span>
  <span m=''3320280''>which</span> <span m=''3320470''>is</span> <span m=''3320570''>the</span>
  <span m=''3320800''>iteration</span> <span m=''3321280''>function</span> <span m=''3322810''>of</span>
  <span m=''3322990''>Newton''s</span> <span m=''3323340''>method when</span> <span
  m=''3323660''>we</span> <span m=''3323900''>use</span> <span m=''3324090''>the</span>
  <span m=''3324140''>fixed</span> <span m=''3324390''>point</span> <span m=''3324650''>method.</span>
  <span m=''3327450''>So</span> <span m=''3327710''>this</span> <span m=''3328730''>procedure,</span>
  <span m=''3330260''>which</span> <span m=''3330830''>contains</span> <span m=''3331270''>it</span>
  <span m=''3331720''>by</span> <span m=''3331960''>substitution--</span> <span m=''3333030''>remember,</span>
  <span m=''3333800''>Newton''s</span> <span m=''3334210''>method</span> <span m=''3334500''>over</span>
  <span m=''3334700''>here,</span> <span m=''3335410''>Newton''s</span> <span m=''3335780''>method</span>
  <span m=''3336700''>builds</span> <span m=''3337730''>this</span> <span m=''3338090''>procedure,</span>
  <span m=''3339700''>and</span> <span m=''3339870''>Newton''s</span> <span m=''3340270''>method</span>
  <span m=''3340750''>has</span> <span m=''3341160''>in</span> <span m=''3341500''>it</span>
  <span m=''3341870''>defined</span> <span m=''3342430''>f</span> <span m=''3342760''>and</span>
  <span m=''3343010''>df,</span> <span m=''3344970''>so</span> <span m=''3345150''>those</span>
  <span m=''3345370''>are</span> <span m=''3345430''>captured</span> <span m=''3345930''>over</span>
  <span m=''3346140''>here:</span> <span m=''3346490''>f</span> <span m=''3347000''>and</span>
  <span m=''3347260''>df.</span> <span m=''3348900''>Starting</span> <span m=''3349310''>with</span>
  <span m=''3349460''>this</span> <span m=''3349660''>procedure,</span> <span m=''3350840''>I</span>
  <span m=''3350970''>can</span> <span m=''3351130''>now</span> <span m=''3351300''>feed</span>
  <span m=''3351570''>this</span> <span m=''3351740''>to</span> <span m=''3351850''>the</span>
  <span m=''3351930''>fixed</span> <span m=''3352200''>point</span> <span m=''3352460''>process</span>
  <span m=''3353690''>within</span> <span m=''3354040''>an</span> <span m=''3354110''>initial</span>
  <span m=''3354340''>guess</span> <span m=''3354680''>coming</span> <span m=''3354980''>out</span>
  <span m=''3355160''>from</span> <span m=''3355260''>the</span> <span m=''3355350''>outside</span>
  <span m=''3356050''>from</span> <span m=''3356550''>square</span> <span m=''3356890''>root</span>
  <span m=''3358550''>to</span> <span m=''3358680''>produce</span> <span m=''3359070''>the
  square</span> <span m=''3359200''>root of x.</span> <span m=''3363680''>So what</span>
  <span m=''3363870''>we''ve</span> <span m=''3364100''>built</span> <span m=''3364650''>is</span>
  <span m=''3364800''>a</span> <span m=''3364850''>very</span> <span m=''3365100''>powerful</span>
  <span m=''3365570''>engine,</span> <span m=''3367000''>which</span> <span m=''3367270''>allows</span>
  <span m=''3367680''>us</span> <span m=''3367990''>to</span> <span m=''3368180''>make</span>
  <span m=''3368470''>nice</span> <span m=''3368700''>things</span> <span m=''3368950''>like</span>
  <span m=''3369190''>this.</span> </p><p><span m=''3371256''>Now,</span> <span m=''3371680''>I</span>
  <span m=''3371920''>want</span> <span m=''3372830''>to</span> <span m=''3374150''>end</span>
  <span m=''3374320''>this</span> <span m=''3376320''>with</span> <span m=''3376720''>basically</span>
  <span m=''3377310''>an</span> <span m=''3377410''>idea</span> <span m=''3377800''>of</span>
  <span m=''3378730''>Chris</span> <span m=''3379000''>Strachey,</span> <span m=''3379970''>one</span>
  <span m=''3380120''>of</span> <span m=''3380200''>the</span> <span m=''3381520''>grandfathers</span>
  <span m=''3382110''>of</span> <span m=''3382190''>computer</span> <span m=''3382530''>science.</span>
  <span m=''3383230''>He''s</span> <span m=''3383320''>a</span> <span m=''3383370''>logician</span>
  <span m=''3384040''>who</span> <span m=''3384540''>lived</span> <span m=''3384840''>in</span>
  <span m=''3385050''>the--</span> <span m=''3387440''>I</span> <span m=''3387540''>suppose</span>
  <span m=''3387900''>about</span> <span m=''3388360''>10</span> <span m=''3388550''>years</span>
  <span m=''3388750''>ago</span> <span m=''3388870''>or</span> <span m=''3388960''>15</span>
  <span m=''3389260''>years</span> <span m=''3389430''>ago,</span> <span m=''3389560''>he</span>
  <span m=''3389660''>died.</span> <span m=''3390320''>I don''t</span> <span m=''3390460''>remember</span>
  <span m=''3390830''>exactly</span> <span m=''3391250''>when.</span> <span m=''3391840''>He''s
  one of</span> <span m=''3392070''>the</span> <span m=''3392190''>inventors of</span>
  <span m=''3392520''>something</span> <span m=''3392870''>called</span> <span m=''3393250''>denotational</span>
  <span m=''3394060''>semantics.</span> <span m=''3394820''>He</span> <span m=''3395120''>was</span>
  <span m=''3395210''>a</span> <span m=''3395250''>great</span> <span m=''3395510''>advocate</span>
  <span m=''3396450''>of</span> <span m=''3397070''>making</span> <span m=''3398600''>procedures</span>
  <span m=''3399200''>or</span> <span m=''3399310''>functions</span> <span m=''3400560''>first-class</span>
  <span m=''3401150''>citizens</span> <span m=''3401640''>in</span> <span m=''3401720''>a</span>
  <span m=''3401780''>programming</span> <span m=''3402210''>language.</span> </p><p><span
  m=''3403950''>So</span> <span m=''3404150''>here''s</span> <span m=''3404440''>the</span>
  <span m=''3404940''>rights</span> <span m=''3405240''>and</span> <span m=''3405360''>privileges</span>
  <span m=''3406110''>of</span> <span m=''3406320''>first-class</span> <span m=''3406910''>citizens</span>
  <span m=''3407910''>in</span> <span m=''3408010''>a</span> <span m=''3408070''>programming</span>
  <span m=''3408470''>language.</span> <span m=''3410690''>It allows</span> <span
  m=''3410870''>you to</span> <span m=''3410980''>make</span> <span m=''3411280''>any</span>
  <span m=''3411430''>abstraction</span> <span m=''3411780''>you</span> <span m=''3412130''>like</span>
  <span m=''3412820''>if</span> <span m=''3412950''>you</span> <span m=''3413070''>have</span>
  <span m=''3414630''>functions</span> <span m=''3415100''>as</span> <span m=''3415180''>first-class</span>
  <span m=''3415260''>citizens.</span> <span m=''3417710''>The</span> <span m=''3417840''>first-class</span>
  <span m=''3418040''>citizens</span> <span m=''3418260''>must</span> <span m=''3418530''>be</span>
  <span m=''3418890''>able</span> <span m=''3419030''>to</span> <span m=''3419090''>be</span>
  <span m=''3419180''>named</span> <span m=''3419580''>by</span> <span m=''3419720''>variables.</span>
  <span m=''3422270''>And</span> <span m=''3422400''>you''re</span> <span m=''3422510''>seeing</span>
  <span m=''3422740''>me</span> <span m=''3422860''>doing</span> <span m=''3423070''>that</span>
  <span m=''3423230''>all</span> <span m=''3423400''>the</span> <span m=''3423500''>time.</span>
  <span m=''3424600''>Here''s</span> <span m=''3424790''>a nice</span> <span m=''3425240''>variable</span>
  <span m=''3425890''>which</span> <span m=''3426160''>names</span> <span m=''3426950''>a</span>
  <span m=''3427070''>procedure</span> <span m=''3427530''>which</span> <span m=''3427700''>computes</span>
  <span m=''3428070''>something.</span> <span m=''3433270''>They</span> <span m=''3433420''>have</span>
  <span m=''3433600''>to</span> <span m=''3433680''>be</span> <span m=''3433790''>passed</span>
  <span m=''3434110''>as</span> <span m=''3434190''>arguments</span> <span m=''3434600''>to</span>
  <span m=''3434700''>procedures.</span> <span m=''3435370''>We''ve</span> <span m=''3435580''>certainly</span>
  <span m=''3435830''>seen</span> <span m=''3436050''>that.</span> <span m=''3438540''>We</span>
  <span m=''3438700''>have</span> <span m=''3438840''>to</span> <span m=''3438930''>be</span>
  <span m=''3439010''>able</span> <span m=''3439150''>to</span> <span m=''3439230''>return</span>
  <span m=''3439670''>them</span> <span m=''3439840''>as</span> <span m=''3440020''>values</span>
  <span m=''3440470''>from</span> <span m=''3440640''>procedures.</span> <span m=''3443340''>And</span>
  <span m=''3443470''>I</span> <span m=''3443610''>suppose</span> <span m=''3443890''>we''ve</span>
  <span m=''3444000''>seen</span> <span m=''3444230''>that.</span> <span m=''3445300''>We</span>
  <span m=''3445400''>haven''t</span> <span m=''3445690''>yet</span> <span m=''3445900''>seen</span>
  <span m=''3446200''>anything</span> <span m=''3446450''>about</span> <span m=''3446690''>data</span>
  <span m=''3446880''>structures.</span> <span m=''3447970''>We</span> <span m=''3448080''>will</span>
  <span m=''3448270''>soon,</span> <span m=''3449620''>but</span> <span m=''3449920''>it''s</span>
  <span m=''3450100''>also</span> <span m=''3450370''>the</span> <span m=''3450470''>case</span>
  <span m=''3450940''>that</span> <span m=''3451290''>in order</span> <span m=''3451380''>to
  have</span> <span m=''3451490''>a</span> <span m=''3451590''>first-class</span>
  <span m=''3452080''>citizen</span> <span m=''3452340''>in</span> <span m=''3452600''>a</span>
  <span m=''3452660''>programming</span> <span m=''3453060''>language,</span> <span
  m=''3453820''>the</span> <span m=''3453940''>object</span> <span m=''3454420''>has</span>
  <span m=''3454640''>to</span> <span m=''3454740''>be</span> <span m=''3454880''>allowed</span>
  <span m=''3455220''>to</span> <span m=''3455270''>be</span> <span m=''3455370''>part</span>
  <span m=''3455570''>of a</span> <span m=''3455680''>data</span> <span m=''3455890''>structure.</span>
  <span m=''3457200''>We''re</span> <span m=''3457290''>going</span> <span m=''3457360''>to</span>
  <span m=''3457430''>see</span> <span m=''3457610''>that</span> <span m=''3457870''>soon.</span>
  </p><p><span m=''3459110''>So</span> <span m=''3459130''>I</span> <span m=''3459420''>just</span>
  <span m=''3459650''>want</span> <span m=''3459730''>to</span> <span m=''3459810''>close</span>
  <span m=''3460170''>with</span> <span m=''3460310''>this</span> <span m=''3461120''>and</span>
  <span m=''3461260''>say</span> <span m=''3462160''>having</span> <span m=''3463150''>things</span>
  <span m=''3463530''>like</span> <span m=''3463800''>procedures</span> <span m=''3464300''>as</span>
  <span m=''3464480''>first-class</span> <span m=''3465030''>data</span> <span m=''3465350''>structures,</span>
  <span m=''3465980''>first-class</span> <span m=''3466180''>data,</span> <span m=''3467320''>allows</span>
  <span m=''3467790''>one</span> <span m=''3468500''>to</span> <span m=''3468730''>make</span>
  <span m=''3469130''>powerful</span> <span m=''3469550''>abstractions,</span> <span
  m=''3470550''>which</span> <span m=''3470780''>encode</span> <span m=''3471140''>general</span>
  <span m=''3471470''>methods</span> <span m=''3472080''>like</span> <span m=''3472300''>Newton''s</span>
  <span m=''3472570''>method</span> <span m=''3473110''>in</span> <span m=''3473250''>very</span>
  <span m=''3473490''>clear</span> <span m=''3473740''>way.</span> <span m=''3474780''>Are</span>
  <span m=''3474950''>there</span> <span m=''3475100''>any</span> <span m=''3475200''>questions?</span>
  <span m=''3477430''>Yes.</span> </p><p><span m=''3477780''>AUDIENCE: Could</span>
  <span m=''3478085''>you</span> <span m=''3478390''>put</span> <span m=''3478720''>derivative</span>
  <span m=''3479030''>instead</span> <span m=''3479345''>of</span> <span m=''3479660''>df</span>
  <span m=''3480040''>directly</span> <span m=''3480882''>in the</span> <span m=''3481303''>fixed</span>
  <span m=''3481724''>point?</span> </p><p><span m=''3482570''>PROFESSOR: Oh,</span>
  <span m=''3482710''>sure.</span> <span m=''3483810''>Yes,</span> <span m=''3484330''>I</span>
  <span m=''3484470''>could</span> <span m=''3484770''>have</span> <span m=''3485090''>put</span>
  <span m=''3486510''>deriv</span> <span m=''3486775''>of</span> <span m=''3487040''>f</span>
  <span m=''3487300''>right</span> <span m=''3487530''>here,</span> <span m=''3488720''>no</span>
  <span m=''3488870''>question.</span> <span m=''3491810''>Any time</span> <span m=''3492290''>you</span>
  <span m=''3492390''>see</span> <span m=''3492720''>something</span> <span m=''3493100''>defined,</span>
  <span m=''3494560''>you can</span> <span m=''3494780''>put</span> <span m=''3495110''>the</span>
  <span m=''3495340''>thing</span> <span m=''3496190''>that</span> <span m=''3496350''>the</span>
  <span m=''3496470''>definition</span> <span m=''3496970''>is</span> <span m=''3497190''>there</span>
  <span m=''3498710''>because</span> <span m=''3498870''>you</span> <span m=''3498950''>get</span>
  <span m=''3499090''>the</span> <span m=''3499150''>same</span> <span m=''3499380''>result.</span>
  <span m=''3501060''>In</span> <span m=''3501200''>fact,</span> <span m=''3501610''>what
  that would</span> <span m=''3501950''>look</span> <span m=''3502160''>like,</span>
  <span m=''3502490''>it''s</span> <span m=''3502690''>interesting.</span> </p><p><span
  m=''3502800''>AUDIENCE: Lambda.</span> </p><p><span m=''3503750''>PROFESSOR: Huh?</span>
  </p><p><span m=''3504085''>AUDIENCE: You could</span> <span m=''3504420''>put</span>
  <span m=''3504500''>the</span> <span m=''3504570''>lambda expression</span> <span
  m=''3505000''>in there.</span> </p><p><span m=''3505970''>PROFESSOR: I</span> <span
  m=''3506220''>could</span> <span m=''3506350''>also</span> <span m=''3506590''>put</span>
  <span m=''3507380''>derivative</span> <span m=''3507710''>of</span> <span m=''3508100''>f</span>
  <span m=''3508340''>here.</span> <span m=''3509990''>It would</span> <span m=''3510370''>look</span>
  <span m=''3510720''>interesting</span> <span m=''3511400''>because</span> <span
  m=''3511800''>of</span> <span m=''3511910''>the</span> <span m=''3512060''>open</span>
  <span m=''3512330''>paren,</span> <span m=''3512640''>open</span> <span m=''3513000''>paren,</span>
  <span m=''3514130''>deriv of</span> <span m=''3514480''>f,</span> <span m=''3515570''>closed</span>
  <span m=''3515950''>paren</span> <span m=''3516140''>on an</span> <span m=''3516470''>x.</span>
  <span m=''3518610''>Now,</span> <span m=''3518870''>that</span> <span m=''3519040''>would</span>
  <span m=''3519280''>have</span> <span m=''3519510''>the</span> <span m=''3519600''>bad</span>
  <span m=''3519940''>property</span> <span m=''3520400''>of</span> <span m=''3520490''>computing
  the</span> <span m=''3520900''>derivative</span> <span m=''3521340''>many</span>
  <span m=''3521570''>times,</span> <span m=''3522860''>because</span> <span m=''3522990''>every</span>
  <span m=''3523210''>time</span> <span m=''3523420''>I</span> <span m=''3523470''>would</span>
  <span m=''3523610''>run</span> <span m=''3523800''>this</span> <span m=''3523980''>procedure,</span>
  <span m=''3524370''>I would</span> <span m=''3524500''>compute the</span> <span
  m=''3524810''>derivative</span> <span m=''3525170''>again.</span> <span m=''3528030''>However,</span>
  <span m=''3529700''>the</span> <span m=''3529920''>two</span> <span m=''3530110''>open</span>
  <span m=''3530390''>parens</span> <span m=''3530830''>here</span> <span m=''3531270''>both</span>
  <span m=''3531490''>would</span> <span m=''3531580''>be</span> <span m=''3531720''>meaningful.</span>
  <span m=''3532510''>I</span> <span m=''3532590''>want you</span> <span m=''3532680''>to</span>
  <span m=''3532780''>understand</span> <span m=''3533280''>syntactically</span> <span
  m=''3533685''>that</span> <span m=''3534090''>that''s</span> <span m=''3534560''>a</span>
  <span m=''3534600''>sensible</span> <span m=''3535050''>thing.</span> <span m=''3535350''>Because</span>
  <span m=''3535770''>if</span> <span m=''3536190''>was</span> <span m=''3536620''>to</span>
  <span m=''3536710''>rewrite</span> <span m=''3537080''>this</span> <span m=''3537260''>program--</span>
  <span m=''3537730''>and I</span> <span m=''3537790''>should</span> <span m=''3537960''>do</span>
  <span m=''3538110''>it</span> <span m=''3538190''>right</span> <span m=''3538370''>here</span>
  <span m=''3538520''>just</span> <span m=''3538720''>so</span> <span m=''3538810''>you</span>
  <span m=''3538980''>see</span> <span m=''3539760''>because</span> <span m=''3540210''>that''s</span>
  <span m=''3540500''>a</span> <span m=''3540550''>good</span> <span m=''3540750''>question--</span>
  <span m=''3551490''>of</span> <span m=''3551730''>F</span> <span m=''3551950''>and</span>
  <span m=''3552190''>guess</span> <span m=''3555830''>to</span> <span m=''3556340''>be</span>
  <span m=''3556490''>fixed</span> <span m=''3556800''>point</span> <span m=''3563550''>of</span>
  <span m=''3563740''>that</span> <span m=''3564300''>procedure</span> <span m=''3565010''>of</span>
  <span m=''3565220''>one</span> <span m=''3565430''>argument</span> <span m=''3565990''>x,</span>
  <span m=''3566890''>which</span> <span m=''3567810''>subtracts</span> <span m=''3568700''>from</span>
  <span m=''3569080''>x</span> <span m=''3570990''>the</span> <span m=''3571120''>quotient</span>
  <span m=''3572540''>of</span> <span m=''3573880''>F</span> <span m=''3574920''>applied</span>
  <span m=''3575320''>to</span> <span m=''3575390''>x</span> <span m=''3577140''>and</span>
  <span m=''3577710''>the</span> <span m=''3577930''>deriv</span> <span m=''3582080''>of</span>
  <span m=''3582500''>F</span> <span m=''3584020''>applied</span> <span m=''3584530''>to</span>
  <span m=''3584740''>x.</span> <span m=''3593459''>This is</span> <span m=''3593950''>guess.</span>
  </p><p><span m=''3599960''>This</span> <span m=''3600160''>is</span> <span m=''3600280''>a</span>
  <span m=''3600340''>perfectly</span> <span m=''3600770''>legitimate</span> <span
  m=''3601200''>program,</span> <span m=''3602680''>because</span> <span m=''3603020''>what</span>
  <span m=''3603150''>I</span> <span m=''3603320''>have</span> <span m=''3603500''>here--</span>
  <span m=''3604250''>remember</span> <span m=''3604560''>the</span> <span m=''3604670''>evaluation</span>
  <span m=''3605270''>rule.</span> <span m=''3605910''>The</span> <span m=''3606260''>evaluation</span>
  <span m=''3606870''>rule is</span> <span m=''3607310''>evaluate</span> <span m=''3607980''>all
  of</span> <span m=''3608330''>the</span> <span m=''3608410''>parts</span> <span
  m=''3608700''>of</span> <span m=''3608760''>the</span> <span m=''3608810''>combination:</span>
  <span m=''3609120''>the</span> <span m=''3609430''>operator</span> <span m=''3610730''>and</span>
  <span m=''3610890''>the</span> <span m=''3610980''>operands.</span> <span m=''3612070''>This</span>
  <span m=''3612430''>is</span> <span m=''3612630''>the</span> <span m=''3612760''>operator</span>
  <span m=''3613840''>of</span> <span m=''3614050''>this</span> <span m=''3614250''>combination.</span>
  <span m=''3617080''>Evaluating</span> <span m=''3617720''>this</span> <span m=''3617860''>operator</span>
  <span m=''3620270''>will,</span> <span m=''3620420''>of</span> <span m=''3620590''>course,</span>
  <span m=''3620760''>produce the</span> <span m=''3621080''>derivative</span> <span
  m=''3621840''>of</span> <span m=''3622050''>F.</span> </p><p><span m=''3628250''>AUDIENCE:
  To get</span> <span m=''3628525''>it</span> <span m=''3628800''>one</span> <span
  m=''3629210''>step</span> <span m=''3629470''>further,</span> <span m=''3629790''>you  could</span>
  <span m=''3630000''>put the</span> <span m=''3630300''>lambda</span> <span m=''3630630''>expression</span>
  <span m=''3630915''>there, too.</span> </p><p><span m=''3631200''>PROFESSOR: Oh,</span>
  <span m=''3631600''>of</span> <span m=''3631850''>course.</span> <span m=''3633180''>Any</span>
  <span m=''3633410''>time</span> <span m=''3633710''>I</span> <span m=''3633800''>take</span>
  <span m=''3634080''>something</span> <span m=''3634580''>which</span> <span m=''3634800''>is</span>
  <span m=''3635220''>define,</span> <span m=''3636120''>I</span> <span m=''3636280''>can</span>
  <span m=''3636440''>put</span> <span m=''3636690''>the</span> <span m=''3637620''>thing</span>
  <span m=''3637930''>it''s</span> <span m=''3638120''>defined</span> <span m=''3638560''>to</span>
  <span m=''3638640''>be</span> <span m=''3639560''>in</span> <span m=''3639710''>the</span>
  <span m=''3639770''>place</span> <span m=''3640020''>where</span> <span m=''3640160''>the</span>
  <span m=''3640220''>thing</span> <span m=''3640420''>defined</span> <span m=''3640490''>is.</span>
  <span m=''3642420''>I</span> <span m=''3642510''>can''t</span> <span m=''3642770''>remember</span>
  <span m=''3643040''>which</span> <span m=''3643180''>is</span> <span m=''3643250''>definiens</span>
  <span m=''3644100''>and</span> <span m=''3644190''>which</span> <span m=''3644330''>is</span>
  <span m=''3644430''>definiendum.</span> <span m=''3647490''>When</span> <span m=''3647640''>I''m</span>
  <span m=''3648570''>trying</span> <span m=''3648720''>to</span> <span m=''3648870''>figure</span>
  <span m=''3649110''>out</span> <span m=''3649210''>how</span> <span m=''3649340''>to
  do</span> <span m=''3649540''>a lecture</span> <span m=''3649790''>about</span>
  <span m=''3650050''>this</span> <span m=''3650230''>in</span> <span m=''3651210''>a</span>
  <span m=''3651300''>freshman</span> <span m=''3651640''>class,</span> <span m=''3651950''>I</span>
  <span m=''3652020''>use</span> <span m=''3652230''>such</span> <span m=''3652370''>words</span>
  <span m=''3653190''>and</span> <span m=''3653360''>tell</span> <span m=''3653610''>everybody</span>
  <span m=''3654160''>it''s</span> <span m=''3654290''>fun</span> <span m=''3654540''>to</span>
  <span m=''3654640''>tell</span> <span m=''3654840''>their</span> <span m=''3655000''>friends.</span>
  <span m=''3659470''>OK,</span> <span m=''3659800''>I</span> <span m=''3659820''>think</span>
  <span m=''3660000''>that''s</span> <span m=''3660210''>it.</span> </p>'
type: course
uid: 11baf0a782fb1ef4a384c3213648f09b

---
None