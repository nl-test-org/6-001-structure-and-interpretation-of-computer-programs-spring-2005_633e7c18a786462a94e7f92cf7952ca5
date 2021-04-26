---
about_this_resource_text: <p><b>Topics covered:</b> Symbolic Differentiation; Quotation</p>
  <p><b> Instructors:</b> Hal Abelson and Gerald Jay Sussman</p> <p>Subtitles for
  this course are provided through the generous assistance of Henry Baker, Hoofar
  Pourzand, Heather Wood, Aleksejs Truhans, Steven Edwards, George Menhorn, and Mahendra
  Kumar.</p>
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
embedded_media:
- id: 3B.jpg
  parent_uid: fdf62f2cf463a056b918ba7f340743f3
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/3b-symbolic-differentiation-quotation/3B.jpg
  title: 3B.jpg
  type: null
  uid: 5715c8dfec19f1365ecee6f815fb68dd
- id: Video-YouTube-Stream
  media_location: bV87UzKMRtE
  parent_uid: fdf62f2cf463a056b918ba7f340743f3
  title: Video-YouTube-Stream
  type: Video
  uid: 7d65a0dd0966a733c5eab0d359759b8d
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT_Structure_of_Computer_Programs_1986/lec3b.mp4
  parent_uid: fdf62f2cf463a056b918ba7f340743f3
  title: Video-Internet Archive-MP4
  type: Video
  uid: 4db14e655117063dd68c069960e9b537
- id: Thumbnail-OCW-JPG
  parent_uid: fdf62f2cf463a056b918ba7f340743f3
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 954b528bc271bfad36b476c5e6a76bf3
- id: 3Play-3PlayYouTubeid-MP4
  media_location: bV87UzKMRtE
  parent_uid: fdf62f2cf463a056b918ba7f340743f3
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: a5b3bc310f65af7f13c95b179d09198b
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/bV87UzKMRtE/default.jpg
  parent_uid: fdf62f2cf463a056b918ba7f340743f3
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 9227036d01afa35af8f4a61ea5ca7ce3
- id: bV87UzKMRtE.srt
  parent_uid: fdf62f2cf463a056b918ba7f340743f3
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/3b-symbolic-differentiation-quotation/bV87UzKMRtE.srt
  title: 3play caption file
  type: null
  uid: bc116b5efe43380bff590f213c63bd6e
- id: bV87UzKMRtE.pdf
  parent_uid: fdf62f2cf463a056b918ba7f340743f3
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/3b-symbolic-differentiation-quotation/bV87UzKMRtE.pdf
  title: 3play pdf file
  type: null
  uid: 20ace20264e0b891145a184405f6ef10
- id: Caption-3Play YouTube id-SRT
  parent_uid: fdf62f2cf463a056b918ba7f340743f3
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: c2743d32182edf389fc50825cf682f85
- id: Transcript-3Play YouTube id-PDF
  parent_uid: fdf62f2cf463a056b918ba7f340743f3
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 6aaa88fb4c688c962e76577ed9414d22
inline_embed_id: 796145143b:symbolicdifferentiation;quotation72825749
layout: video
order_index: null
parent_uid: 4fcacad2c29981dd668a6b29822403cc
related_resources_text: ''
short_url: 3b-symbolic-differentiation-quotation
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/3b-symbolic-differentiation-quotation
template_type: Tabbed
title: '3B: Symbolic Differentiation; Quotation'
transcript: '<p><span m=''2928''>[MUSIC PLAYING]</span> </p><p><span m=''19520''>PROFESSOR:
  Well,</span> <span m=''19910''>Hal</span> <span m=''20240''>just</span> <span m=''21250''>told</span>
  <span m=''21530''>us</span> <span m=''21670''>how</span> <span m=''21810''>you</span>
  <span m=''21950''>build</span> <span m=''22250''>robust</span> <span m=''22720''>systems.</span>
  <span m=''24140''>The</span> <span m=''24260''>key</span> <span m=''24500''>idea</span>
  <span m=''25510''>was--</span> <span m=''26960''>I''m</span> <span m=''27210''>sure</span>
  <span m=''27460''>that</span> <span m=''27610''>many</span> <span m=''27830''>of</span>
  <span m=''27880''>you</span> <span m=''28200''>don''t</span> <span m=''29010''>really</span>
  <span m=''29310''>assimilate</span> <span m=''29780''>that</span> <span m=''30000''>yet--</span>
  <span m=''30250''>but</span> <span m=''30410''>the</span> <span m=''30490''>key</span>
  <span m=''30680''>idea</span> <span m=''31060''>is</span> <span m=''31600''>that</span>
  <span m=''31790''>in</span> <span m=''31850''>order</span> <span m=''32000''>to</span>
  <span m=''32049''>make</span> <span m=''32250''>a</span> <span m=''32299''>system</span>
  <span m=''32980''>that''s</span> <span m=''33240''>robust,</span> <span m=''33770''>it</span>
  <span m=''34240''>has</span> <span m=''34450''>to</span> <span m=''34540''>be</span>
  <span m=''34780''>insensitive</span> <span m=''35370''>to</span> <span m=''35490''>small</span>
  <span m=''35800''>changes,</span> <span m=''36850''>that</span> <span m=''37050''>is,</span>
  <span m=''37500''>a</span> <span m=''37610''>small</span> <span m=''37940''>change</span>
  <span m=''38240''>in</span> <span m=''38310''>the</span> <span m=''38390''>problem</span>
  <span m=''39060''>should</span> <span m=''39240''>lead</span> <span m=''39390''>to</span>
  <span m=''39460''>only</span> <span m=''39630''>a</span> <span m=''39680''>small</span>
  <span m=''39940''>change</span> <span m=''40170''>in</span> <span m=''40240''>the</span>
  <span m=''40310''>solution.</span> <span m=''41340''>There</span> <span m=''41610''>ought   to</span>
  <span m=''41740''>be a</span> <span m=''41870''>continuity.</span> <span m=''42670''>The</span>
  <span m=''43010''>space</span> <span m=''43350''>of</span> <span m=''43420''>solutions</span>
  <span m=''43880''>ought to</span> <span m=''44050''>be</span> <span m=''44140''>continuous</span>
  <span m=''44710''>in</span> <span m=''44770''>this</span> <span m=''45140''>space
  of</span> <span m=''45410''>problems.</span> </p><p><span m=''46120''>The</span>
  <span m=''46510''>way</span> <span m=''46680''>he</span> <span m=''46800''>was</span>
  <span m=''46940''>explaining</span> <span m=''47380''>how</span> <span m=''47550''>to</span>
  <span m=''48110''>do</span> <span m=''48370''>that</span> <span m=''49660''>was</span>
  <span m=''49860''>instead</span> <span m=''50190''>of</span> <span m=''50270''>solving</span>
  <span m=''50620''>a</span> <span m=''50690''>particular</span> <span m=''51160''>problem</span>
  <span m=''51540''>at</span> <span m=''51620''>every</span> <span m=''51880''>level</span>
  <span m=''52150''>of</span> <span m=''52240''>decomposition</span> <span m=''53190''>of</span>
  <span m=''53360''>the</span> <span m=''53440''>problem</span> <span m=''53740''>at</span>
  <span m=''53820''>the</span> <span m=''53880''>subproblems,</span> <span m=''55230''>where
  you</span> <span m=''55520''>solve</span> <span m=''55860''>the</span> <span m=''55960''>class</span>
  <span m=''56320''>of</span> <span m=''56420''>problems,</span> <span m=''57030''>which</span>
  <span m=''57230''>are a</span> <span m=''57350''>neighborhood</span> <span m=''58350''>of</span>
  <span m=''58570''>the</span> <span m=''58710''>particular</span> <span m=''59250''>problem</span>
  <span m=''59550''>that you''re</span> <span m=''59770''>trying</span> <span m=''59920''>to</span>
  <span m=''60080''>solve.</span> <span m=''61440''>The</span> <span m=''61580''>way</span>
  <span m=''61720''>you</span> <span m=''61850''>do</span> <span m=''61990''>that</span>
  <span m=''62190''>is</span> <span m=''62400''>by</span> <span m=''62600''>producing</span>
  <span m=''63150''>a</span> <span m=''63220''>language</span> <span m=''63680''>at</span>
  <span m=''63790''>that</span> <span m=''63980''>level</span> <span m=''64200''>of</span>
  <span m=''64280''>detail</span> <span m=''65120''>in</span> <span m=''65269''>which</span>
  <span m=''65480''>the</span> <span m=''65570''>solutions</span> <span m=''66070''>to</span>
  <span m=''66690''>that</span> <span m=''67130''>class</span> <span m=''67400''>of</span>
  <span m=''67500''>problems</span> <span m=''68600''>is</span> <span m=''68760''>representable</span>
  <span m=''69550''>in</span> <span m=''69670''>that</span> <span m=''69870''>language.</span>
  <span m=''71170''>Therefore</span> <span m=''72140''>when</span> <span m=''72310''>you</span>
  <span m=''72770''>makes</span> <span m=''73000''>more</span> <span m=''73230''>changes</span>
  <span m=''73630''>to</span> <span m=''73730''>the</span> <span m=''73830''>problem</span>
  <span m=''74250''>you''re</span> <span m=''74370''>trying</span> <span m=''74500''>to</span>
  <span m=''74630''>solve,</span> <span m=''75440''>you</span> <span m=''75570''>generally</span>
  <span m=''75920''>have</span> <span m=''76070''>to</span> <span m=''76140''>make</span>
  <span m=''76310''>only</span> <span m=''76520''>small</span> <span m=''76840''>local</span>
  <span m=''77140''>changes</span> <span m=''77680''>to</span> <span m=''77850''>the</span>
  <span m=''77930''>solution</span> <span m=''78300''>you''ve</span> <span m=''78420''>constructed,</span>
  <span m=''79480''>because</span> <span m=''80290''>at</span> <span m=''80550''>the</span>
  <span m=''80640''>level</span> <span m=''80950''>of</span> <span m=''81040''>detail</span>
  <span m=''81480''>you''re</span> <span m=''81610''>working,</span> <span m=''82290''>there''s</span>
  <span m=''82730''>a</span> <span m=''82800''>language</span> <span m=''83190''>where</span>
  <span m=''83310''>you</span> <span m=''83410''>can</span> <span m=''83520''>express</span>
  <span m=''85030''>the</span> <span m=''85260''>various</span> <span m=''85670''>solutions</span>
  <span m=''86140''>to</span> <span m=''86330''>alternate</span> <span m=''86940''>problems</span>
  <span m=''87390''>of</span> <span m=''87500''>the</span> <span m=''87560''>same</span>
  <span m=''87820''>type.</span> </p><p><span m=''90170''>Well</span> <span m=''90540''>that''s</span>
  <span m=''90990''>the</span> <span m=''91100''>beginning</span> <span m=''91690''>of</span>
  <span m=''92220''>a</span> <span m=''92380''>very</span> <span m=''92720''>important</span>
  <span m=''93210''>idea,</span> <span m=''94520''>the</span> <span m=''94780''>most</span>
  <span m=''95090''>important</span> <span m=''95500''>perhaps</span> <span m=''95850''>idea</span>
  <span m=''96200''>that</span> <span m=''96320''>makes</span> <span m=''96500''>computer</span>
  <span m=''96830''>science</span> <span m=''97700''>more</span> <span m=''97950''>powerful</span>
  <span m=''98590''>than</span> <span m=''98990''>most</span> <span m=''99150''>of</span>
  <span m=''99320''>the</span> <span m=''99470''>other</span> <span m=''99630''>kinds</span>
  <span m=''99870''>of</span> <span m=''99940''>engineering</span> <span m=''100320''>disciplines</span>
  <span m=''101610''>we</span> <span m=''101770''>know</span> <span m=''101960''>about.</span>
  <span m=''103500''>What</span> <span m=''103690''>we''ve</span> <span m=''103850''>seen</span>
  <span m=''104080''>so</span> <span m=''104300''>far</span> <span m=''105070''>is</span>
  <span m=''105640''>sort</span> <span m=''105960''>of</span> <span m=''106390''>how</span>
  <span m=''106650''>to</span> <span m=''106710''>use</span> <span m=''107350''>embedding</span>
  <span m=''107930''>of</span> <span m=''108040''>languages.</span> <span m=''109500''>And,</span>
  <span m=''110040''>of</span> <span m=''110200''>course,</span> <span m=''110370''>the</span>
  <span m=''110450''>power</span> <span m=''110720''>of</span> <span m=''110810''>embedding</span>
  <span m=''111120''>languages</span> <span m=''112190''>partly</span> <span m=''112570''>comes</span>
  <span m=''112860''>from</span> <span m=''114260''>procedures</span> <span m=''114750''>like</span>
  <span m=''114970''>this</span> <span m=''115170''>one</span> <span m=''115370''>that</span>
  <span m=''115480''>I</span> <span m=''115890''>showed</span> <span m=''116140''>you</span>
  <span m=''116240''>yesterday.</span> </p><p><span m=''117500''>What</span> <span
  m=''117630''>you</span> <span m=''117760''>see</span> <span m=''117990''>here</span>
  <span m=''119060''>is</span> <span m=''119500''>the</span> <span m=''119710''>derivative</span>
  <span m=''120160''>program</span> <span m=''120920''>that</span> <span m=''121060''>we</span>
  <span m=''121210''>described</span> <span m=''121610''>yesterday.</span> <span m=''122280''>It''s</span>
  <span m=''122450''>a</span> <span m=''122520''>procedure</span> <span m=''123100''>that</span>
  <span m=''123440''>takes</span> <span m=''124130''>a</span> <span m=''124890''>procedure</span>
  <span m=''125340''>as</span> <span m=''125440''>an</span> <span m=''125530''>argument</span>
  <span m=''126160''>and</span> <span m=''126270''>returns</span> <span m=''126740''>a</span>
  <span m=''126850''>procedure</span> <span m=''127250''>as</span> <span m=''127340''>a</span>
  <span m=''127400''>value.</span> <span m=''129880''>And</span> <span m=''130280''>using</span>
  <span m=''130680''>such</span> <span m=''130970''>things</span> <span m=''131770''>is</span>
  <span m=''131930''>very</span> <span m=''132140''>nice.</span> <span m=''132680''>You</span>
  <span m=''132840''>can</span> <span m=''132970''>make</span> <span m=''133170''>things</span>
  <span m=''133390''>like</span> <span m=''133590''>push</span> <span m=''133820''>combinators</span>
  <span m=''134790''>and</span> <span m=''135020''>all</span> <span m=''135170''>that</span>
  <span m=''135350''>sort</span> <span m=''135480''>of</span> <span m=''135540''>wonderful</span>
  <span m=''135760''>thing</span> <span m=''135990''>that</span> <span m=''136070''>you</span>
  <span m=''136160''>saw</span> <span m=''136330''>last</span> <span m=''136640''>time.</span>
  </p><p><span m=''138020''>However,</span> <span m=''138430''>now</span> <span m=''138710''>I''m</span>
  <span m=''138850''>going</span> <span m=''139010''>to</span> <span m=''139170''>really</span>
  <span m=''139550''>muddy</span> <span m=''139860''>the</span> <span m=''139940''>waters.</span>
  <span m=''141730''>See</span> <span m=''141860''>this</span> <span m=''143520''>confuses</span>
  <span m=''144080''>the</span> <span m=''144190''>issue</span> <span m=''144480''>of</span>
  <span m=''144580''>what''s</span> <span m=''144740''>the</span> <span m=''144830''>procedure</span>
  <span m=''145230''>and</span> <span m=''145310''>what</span> <span m=''145430''>is</span>
  <span m=''145540''>data,</span> <span m=''146440''>but</span> <span m=''146830''>not</span>
  <span m=''147020''>very</span> <span m=''147210''>badly.</span> <span m=''148310''>What</span>
  <span m=''148750''>we</span> <span m=''148920''>really</span> <span m=''149220''>want</span>
  <span m=''149330''>to</span> <span m=''149450''>do</span> <span m=''149570''>is</span>
  <span m=''149650''>confuse</span> <span m=''149970''>it</span> <span m=''150110''>very</span>
  <span m=''150400''>badly.</span> <span m=''151260''>And</span> <span m=''151360''>the</span>
  <span m=''151460''>best</span> <span m=''151730''>way</span> <span m=''151830''>to</span>
  <span m=''151940''>do</span> <span m=''152100''>that</span> <span m=''152520''>is</span>
  <span m=''152660''>to</span> <span m=''152720''>get</span> <span m=''152860''>involved</span>
  <span m=''153230''>with</span> <span m=''153310''>the</span> <span m=''153400''>manipulation</span>
  <span m=''154220''>of</span> <span m=''154430''>the</span> <span m=''154570''>algebraic</span>
  <span m=''155160''>expressions</span> <span m=''155820''>that</span> <span m=''155900''>the</span>
  <span m=''155980''>procedures</span> <span m=''156520''>themselves are</span> <span
  m=''156990''>expressed</span> <span m=''157440''>in.</span> </p><p><span m=''159750''>So</span>
  <span m=''159930''>at</span> <span m=''160070''>this</span> <span m=''160210''>point,</span>
  <span m=''160750''>I</span> <span m=''160920''>want</span> <span m=''161240''>to</span>
  <span m=''161610''>talk</span> <span m=''161980''>about</span> <span m=''162320''>instead</span>
  <span m=''162760''>of</span> <span m=''163240''>things</span> <span m=''163660''>like</span>
  <span m=''164370''>on</span> <span m=''164670''>this</span> <span m=''164970''>slide,</span>
  <span m=''165730''>the</span> <span m=''167010''>derivative</span> <span m=''167500''>procedure</span>
  <span m=''167980''>being</span> <span m=''168240''>a</span> <span m=''168300''>thing</span>
  <span m=''168540''>that</span> <span m=''168650''>manipulates</span> <span m=''169120''>a</span>
  <span m=''169210''>procedure--</span> <span m=''169880''>this</span> <span m=''170100''>is
  a</span> <span m=''170210''>numerical</span> <span m=''170840''>method</span> <span
  m=''171200''>you</span> <span m=''171310''>see</span> <span m=''171520''>here.</span>
  <span m=''171870''>And</span> <span m=''172230''>what</span> <span m=''172350''>you''re</span>
  <span m=''172480''>seeing</span> <span m=''172870''>is</span> <span m=''174120''>a</span>
  <span m=''174280''>representation</span> <span m=''175600''>of</span> <span m=''176180''>the</span>
  <span m=''176440''>numerical</span> <span m=''177020''>approximation</span> <span
  m=''178130''>to</span> <span m=''178320''>the</span> <span m=''178420''>derivative.</span>
  <span m=''179275''>That''s</span> <span m=''179610''>what''s</span> <span m=''179870''>here.</span>
  <span m=''180980''>In</span> <span m=''181150''>fact</span> <span m=''181550''>what
  I''d</span> <span m=''181620''>like</span> <span m=''181810''>to</span> <span m=''181910''>talk</span>
  <span m=''182160''>about</span> <span m=''182640''>is</span> <span m=''182800''>instead</span>
  <span m=''183790''>things</span> <span m=''184040''>that</span> <span m=''184180''>look</span>
  <span m=''184360''>like</span> <span m=''184610''>this.</span> <span m=''186170''>And</span>
  <span m=''186390''>what</span> <span m=''186510''>we</span> <span m=''186680''>have</span>
  <span m=''186860''>here</span> <span m=''188050''>are</span> <span m=''188400''>rules</span>
  <span m=''189410''>from</span> <span m=''189700''>a</span> <span m=''189950''>calculus</span>
  <span m=''191010''>book.</span> </p><p><span m=''192080''>These</span> <span m=''192580''>are</span>
  <span m=''192650''>rules</span> <span m=''193180''>for</span> <span m=''193330''>finding</span>
  <span m=''193820''>the</span> <span m=''193920''>derivatives</span> <span m=''194650''>of</span>
  <span m=''194830''>the</span> <span m=''195010''>expressions</span> <span m=''196830''>that</span>
  <span m=''197100''>one</span> <span m=''197290''>might</span> <span m=''197560''>write</span>
  <span m=''198020''>in</span> <span m=''198190''>some</span> <span m=''199500''>algebraic</span>
  <span m=''200050''>language.</span> <span m=''201520''>It</span> <span m=''201930''>says</span>
  <span m=''202230''>things</span> <span m=''202470''>like</span> <span m=''202680''>a</span>
  <span m=''202740''>derivative</span> <span m=''203120''>of</span> <span m=''203220''>a</span>
  <span m=''203290''>constant</span> <span m=''203800''>is</span> <span m=''203920''>0.</span>
  <span m=''204990''>The</span> <span m=''205330''>derivative</span> <span m=''205910''>of</span>
  <span m=''206050''>the</span> <span m=''206190''>valuable</span> <span m=''206505''>with</span>
  <span m=''206820''>respect</span> <span m=''207280''>to which</span> <span m=''207490''>you</span>
  <span m=''207580''>are</span> <span m=''207700''>taking the</span> <span m=''207990''>derivative</span>
  <span m=''208420''>is</span> <span m=''208570''>1.</span> <span m=''209250''>The</span>
  <span m=''209510''>derivative</span> <span m=''209870''>of</span> <span m=''210150''>a</span>
  <span m=''210220''>constant</span> <span m=''210990''>times the</span> <span m=''211340''>function</span>
  <span m=''212160''>is</span> <span m=''212390''>the</span> <span m=''212490''>constant</span>
  <span m=''212900''>times</span> <span m=''213140''>the</span> <span m=''213230''>derivative</span>
  <span m=''213320''>of</span> <span m=''213690''>the</span> <span m=''213780''>function,</span>
  <span m=''214980''>and</span> <span m=''215150''>things</span> <span m=''215380''>like</span>
  <span m=''215640''>that.</span> <span m=''218300''>These</span> <span m=''218560''>are</span>
  <span m=''218680''>exact</span> <span m=''219180''>expressions.</span> <span m=''219690''>These</span>
  <span m=''219840''>are</span> <span m=''219910''>not</span> <span m=''220130''>numerical</span>
  <span m=''220550''>approximations.</span> <span m=''223090''>Can</span> <span m=''223310''>we</span>
  <span m=''223440''>make</span> <span m=''223880''>programs?</span> <span m=''224560''>And,</span>
  <span m=''224660''>in</span> <span m=''224810''>fact,</span> <span m=''225000''>it''s
  very</span> <span m=''225400''>easy</span> <span m=''225860''>to</span> <span m=''226210''>make</span>
  <span m=''226440''>programs</span> <span m=''228000''>that</span> <span m=''231000''>manipulate</span>
  <span m=''231480''>these</span> <span m=''231650''>expressions.</span> </p><p><span
  m=''236130''>Well</span> <span m=''236580''>let''s</span> <span m=''236940''>see.</span>
  <span m=''237480''>Let''s</span> <span m=''237670''>look</span> <span m=''237810''>at</span>
  <span m=''237890''>these</span> <span m=''238100''>rules</span> <span m=''238440''>in</span>
  <span m=''238560''>some</span> <span m=''238760''>detail.</span> <span m=''241350''>You</span>
  <span m=''241520''>all have</span> <span m=''241770''>seen</span> <span m=''242040''>these</span>
  <span m=''242260''>rules</span> <span m=''242550''>in</span> <span m=''242760''>your</span>
  <span m=''242990''>elementary</span> <span m=''243400''>calculus</span> <span m=''243850''>class</span>
  <span m=''244150''>at</span> <span m=''244230''>one</span> <span m=''244430''>time</span>
  <span m=''244660''>or</span> <span m=''244720''>another.</span> <span m=''246140''>And</span>
  <span m=''246310''>you</span> <span m=''246430''>know</span> <span m=''246850''>from</span>
  <span m=''247040''>calculus</span> <span m=''247820''>that</span> <span m=''248700''>it''s</span>
  <span m=''248880''>easy</span> <span m=''250130''>to</span> <span m=''250270''>produce</span>
  <span m=''250570''>derivatives</span> <span m=''251020''>of</span> <span m=''251140''>arbitrary</span>
  <span m=''251520''>expressions.</span> <span m=''252840''>You</span> <span m=''252970''>also</span>
  <span m=''253190''>know</span> <span m=''253350''>from your</span> <span m=''253490''>elementary</span>
  <span m=''253900''>calculus</span> <span m=''254620''>that it''s</span> <span m=''254900''>hard</span>
  <span m=''255130''>to</span> <span m=''255400''>produce</span> <span m=''255640''>integrals.</span>
  <span m=''257140''>Yet</span> <span m=''257410''>integrals</span> <span m=''257690''>and</span>
  <span m=''257810''>derivatives</span> <span m=''258160''>are</span> <span m=''258399''>opposites</span>
  <span m=''258829''>of</span> <span m=''258920''>each</span> <span m=''259100''>other.</span>
  <span m=''259690''>They''re</span> <span m=''259829''>inverse</span> <span m=''260440''>operations.</span>
  <span m=''261800''>And</span> <span m=''261990''>they</span> <span m=''262130''>have</span>
  <span m=''262270''>the</span> <span m=''262370''>same</span> <span m=''262740''>rules.</span>
  <span m=''264360''>What</span> <span m=''264600''>is</span> <span m=''264740''>special</span>
  <span m=''266350''>about</span> <span m=''266780''>these</span> <span m=''267070''>rules</span>
  <span m=''267720''>that</span> <span m=''268330''>makes</span> <span m=''268560''>it</span>
  <span m=''268650''>possible</span> <span m=''269110''>for</span> <span m=''269210''>one</span>
  <span m=''269590''>to</span> <span m=''269920''>produce</span> <span m=''270390''>derivatives</span>
  <span m=''270860''>easily</span> <span m=''272140''>and</span> <span m=''272310''>integrals</span>
  <span m=''272900''>why</span> <span m=''273130''>it''s</span> <span m=''273220''>so</span>
  <span m=''273360''>hard?</span> <span m=''275100''>Let''s</span> <span m=''275320''>think</span>
  <span m=''275470''>about</span> <span m=''275730''>that</span> <span m=''275910''>very</span>
  <span m=''276460''>simply.</span> </p><p><span m=''277510''>Look</span> <span m=''277680''>at</span>
  <span m=''277780''>these</span> <span m=''277990''>rules.</span> <span m=''279390''>Every</span>
  <span m=''279680''>one</span> <span m=''279860''>of</span> <span m=''280000''>these</span>
  <span m=''280150''>rules,</span> <span m=''280910''>when</span> <span m=''281100''>used</span>
  <span m=''281370''>in</span> <span m=''281460''>the</span> <span m=''281550''>direction</span>
  <span m=''282050''>for</span> <span m=''282190''>taking</span> <span m=''282480''>derivatives,</span>
  <span m=''283130''>which</span> <span m=''283340''>is</span> <span m=''283420''>in</span>
  <span m=''283510''>the</span> <span m=''283590''>direction</span> <span m=''284000''>of</span>
  <span m=''284130''>this</span> <span m=''284260''>arrow,</span> <span m=''286850''>the</span>
  <span m=''286960''>left</span> <span m=''287240''>side</span> <span m=''287730''>is</span>
  <span m=''287940''>matched</span> <span m=''288350''>against</span> <span m=''288660''>your</span>
  <span m=''288830''>expression,</span> <span m=''289320''>and</span> <span m=''289420''>the</span>
  <span m=''289530''>right</span> <span m=''289800''>side</span> <span m=''290050''>is</span>
  <span m=''290270''>the</span> <span m=''290380''>thing</span> <span m=''290820''>which</span>
  <span m=''291130''>is</span> <span m=''291310''>the</span> <span m=''291710''>derivative</span>
  <span m=''292180''>of</span> <span m=''292280''>that</span> <span m=''292440''>expression.</span>
  <span m=''293810''>The</span> <span m=''294240''>arrow</span> <span m=''294590''>is</span>
  <span m=''294700''>going</span> <span m=''294990''>that</span> <span m=''295280''>way.</span>
  <span m=''298630''>In</span> <span m=''299050''>each</span> <span m=''299410''>of</span>
  <span m=''299770''>these</span> <span m=''300020''>rules,</span> <span m=''301190''>the</span>
  <span m=''301500''>expressions</span> <span m=''302090''>on</span> <span m=''302270''>the</span>
  <span m=''302370''>right-hand</span> <span m=''302830''>side</span> <span m=''303050''>of</span>
  <span m=''303160''>the</span> <span m=''303240''>rule</span> <span m=''303620''>that</span>
  <span m=''303910''>are</span> <span m=''303970''>contained</span> <span m=''304330''>within</span>
  <span m=''304750''>derivatives</span> <span m=''305600''>are</span> <span m=''305970''>subexpressions,</span>
  <span m=''306780''>are</span> <span m=''306930''>proper</span> <span m=''307330''>subexpressions,</span>
  <span m=''308390''>of</span> <span m=''308560''>the</span> <span m=''308630''>expression</span>
  <span m=''309090''>on</span> <span m=''309320''>the</span> <span m=''309410''>left-hand</span>
  <span m=''309930''>side.</span> </p><p><span m=''310670''>So</span> <span m=''310880''>here</span>
  <span m=''311050''>we</span> <span m=''311190''>see</span> <span m=''311630''>the</span>
  <span m=''311860''>derivative</span> <span m=''312310''>of</span> <span m=''312400''>the</span>
  <span m=''312490''>sum,</span> <span m=''314100''>with</span> <span m=''314260''>is</span>
  <span m=''314343''>the</span> <span m=''314510''>expression</span> <span m=''314980''>on</span>
  <span m=''315060''>the</span> <span m=''315140''>left-hand</span> <span m=''315610''>side</span>
  <span m=''316370''>is</span> <span m=''316570''>the</span> <span m=''316690''>sum</span>
  <span m=''317050''>of</span> <span m=''317180''>the</span> <span m=''317260''>derivatives</span>
  <span m=''317670''>of</span> <span m=''317830''>the</span> <span m=''317920''>pieces.</span>
  <span m=''320030''>So</span> <span m=''320190''>the</span> <span m=''320300''>rule
  of</span> <span m=''320680''>moving</span> <span m=''321050''>to</span> <span m=''321220''>the</span>
  <span m=''321360''>right</span> <span m=''323430''>are</span> <span m=''323610''>reduction</span>
  <span m=''324170''>rules.</span> <span m=''325070''>The</span> <span m=''325290''>problem</span>
  <span m=''325700''>becomes</span> <span m=''326070''>easier.</span> <span m=''328110''>I</span>
  <span m=''328210''>turn</span> <span m=''328410''>a</span> <span m=''328460''>big</span>
  <span m=''328680''>complicated</span> <span m=''329220''>problem</span> <span m=''329750''>it''s</span>
  <span m=''329980''>lots</span> <span m=''330250''>of</span> <span m=''330340''>smaller</span>
  <span m=''330810''>problems</span> <span m=''332550''>and</span> <span m=''332690''>then</span>
  <span m=''332840''>combine the</span> <span m=''333250''>results,</span> <span m=''334160''>a</span>
  <span m=''334280''>perfect</span> <span m=''334610''>place</span> <span m=''334850''>for</span>
  <span m=''335000''>recursion</span> <span m=''335460''>to</span> <span m=''335550''>work.</span>
  </p><p><span m=''336730''>If</span> <span m=''336910''>I''m</span> <span m=''337060''>going</span>
  <span m=''337360''>in</span> <span m=''337470''>the</span> <span m=''337660''>other</span>
  <span m=''337860''>direction</span> <span m=''340140''>like</span> <span m=''340400''>this,</span>
  <span m=''342040''>if</span> <span m=''342190''>I''m</span> <span m=''342310''>trying</span>
  <span m=''342440''>to</span> <span m=''342570''>produce</span> <span m=''342820''>integrals,</span>
  <span m=''343550''>well</span> <span m=''343690''>there</span> <span m=''343810''>are</span>
  <span m=''343870''>several</span> <span m=''344160''>problems</span> <span m=''344510''>you</span>
  <span m=''344620''>see</span> <span m=''344800''>here.</span> <span m=''345340''>First</span>
  <span m=''345610''>of</span> <span m=''345680''>all,</span> <span m=''345840''>if
  I</span> <span m=''346210''>try</span> <span m=''346440''>to</span> <span m=''346490''>integrate</span>
  <span m=''347220''>an</span> <span m=''347350''>expression</span> <span m=''348160''>like</span>
  <span m=''348390''>a</span> <span m=''348460''>sum,</span> <span m=''349280''>more</span>
  <span m=''349520''>than</span> <span m=''349770''>one</span> <span m=''350010''>rule</span>
  <span m=''350310''>matches.</span> <span m=''350930''>Here''s</span> <span m=''351210''>one</span>
  <span m=''351370''>that</span> <span m=''351490''>matches.</span> <span m=''352610''>Here''s</span>
  <span m=''352840''>one</span> <span m=''353000''>that</span> <span m=''353140''>matches.</span>
  <span m=''354850''>I</span> <span m=''354940''>don''t</span> <span m=''355030''>know</span>
  <span m=''355130''>which</span> <span m=''355280''>one</span> <span m=''355450''>to</span>
  <span m=''355540''>take.</span> <span m=''356210''>And</span> <span m=''356400''>they
  may</span> <span m=''356610''>be</span> <span m=''356710''>different.</span> <span
  m=''357870''>I</span> <span m=''357970''>may</span> <span m=''358150''>get to</span>
  <span m=''359020''>explore</span> <span m=''359450''>different</span> <span m=''359740''>things.</span>
  <span m=''360250''>Also,</span> <span m=''361120''>the</span> <span m=''361420''>expressions</span>
  <span m=''362030''>become</span> <span m=''362410''>larger</span> <span m=''362850''>in</span>
  <span m=''362920''>that</span> <span m=''363110''>direction.</span> <span m=''364660''>And</span>
  <span m=''364810''>when</span> <span m=''364930''>the</span> <span m=''365020''>expressions</span>
  <span m=''365520''>become</span> <span m=''365780''>larger,</span> <span m=''366340''>then</span>
  <span m=''366550''>there''s</span> <span m=''366730''>no</span> <span m=''366910''>guarantee</span>
  <span m=''367690''>that</span> <span m=''367840''>any</span> <span m=''368040''>particular</span>
  <span m=''369030''>path</span> <span m=''369310''>I</span> <span m=''369440''>choose</span>
  <span m=''369810''>will</span> <span m=''370030''>terminate,</span> <span m=''370940''>because</span>
  <span m=''371140''>we</span> <span m=''371230''>will</span> <span m=''371380''>only</span>
  <span m=''371570''>terminate</span> <span m=''371980''>by</span> <span m=''372220''>accidental</span>
  <span m=''372700''>cancellation.</span> <span m=''374380''>So</span> <span m=''374520''>that''s</span>
  <span m=''374750''>why</span> <span m=''375650''>integrals</span> <span m=''376180''>are</span>
  <span m=''376350''>complicated</span> <span m=''376840''>searches</span> <span m=''377290''>and</span>
  <span m=''377350''>hard</span> <span m=''377550''>to</span> <span m=''377610''>do.</span>
  </p><p><span m=''379170''>Right</span> <span m=''379450''>now</span> <span m=''379600''>I</span>
  <span m=''379720''>don''t</span> <span m=''379840''>want</span> <span m=''379910''>to</span>
  <span m=''379980''>do</span> <span m=''380070''>anything</span> <span m=''380200''>as</span>
  <span m=''380330''>hard</span> <span m=''380580''>as</span> <span m=''380660''>that.</span>
  <span m=''381640''>Let''s</span> <span m=''381850''>work</span> <span m=''382040''>on</span>
  <span m=''382180''>derivatives</span> <span m=''382590''>for</span> <span m=''382690''>a</span>
  <span m=''382730''>while.</span> <span m=''384260''>Well,</span> <span m=''384490''>these</span>
  <span m=''384680''>roles</span> <span m=''385240''>are</span> <span m=''385400''>ones</span>
  <span m=''385610''>you</span> <span m=''385740''>know</span> <span m=''386770''>for</span>
  <span m=''386860''>the</span> <span m=''386960''>most</span> <span m=''387230''>part</span>
  <span m=''387550''>hopefully.</span> <span m=''388860''>So</span> <span m=''389040''>let''s</span>
  <span m=''389220''>see</span> <span m=''389440''>if</span> <span m=''389540''>we</span>
  <span m=''389640''>can</span> <span m=''389780''>write</span> <span m=''390120''>a</span>
  <span m=''390240''>program</span> <span m=''390930''>which</span> <span m=''391130''>is</span>
  <span m=''391260''>these</span> <span m=''391460''>rules.</span> <span m=''392410''>And</span>
  <span m=''392510''>that</span> <span m=''392610''>should</span> <span m=''392770''>be</span>
  <span m=''392880''>very</span> <span m=''393260''>easy.</span> <span m=''394790''>Just</span>
  <span m=''395270''>write</span> <span m=''395520''>the</span> <span m=''395600''>program.</span>
  <span m=''396830''>See,</span> <span m=''397040''>because</span> <span m=''397380''>while</span>
  <span m=''397510''>I</span> <span m=''397610''>showed</span> <span m=''397810''>you</span>
  <span m=''398010''>is</span> <span m=''398210''>that</span> <span m=''398340''>it''s</span>
  <span m=''398420''>a</span> <span m=''398510''>reduction</span> <span m=''399010''>rule,</span>
  <span m=''399470''>it''s</span> <span m=''399680''>something</span> <span m=''399880''>appropriate</span>
  <span m=''400390''>for</span> <span m=''400600''>a</span> <span m=''400760''>recursion.</span>
  <span m=''403180''>And,</span> <span m=''403350''>of</span> <span m=''403430''>course,</span>
  <span m=''403840''>what</span> <span m=''404110''>we have</span> <span m=''404310''>for</span>
  <span m=''404440''>each</span> <span m=''404600''>of</span> <span m=''404670''>these</span>
  <span m=''404860''>rules</span> <span m=''405120''>is we</span> <span m=''405230''>have</span>
  <span m=''405350''>a</span> <span m=''405390''>case</span> <span m=''406830''>in</span>
  <span m=''406960''>some</span> <span m=''407130''>case</span> <span m=''407400''>analysis.</span>
  </p><p><span m=''408375''>So</span> <span m=''408670''>I''m</span> <span m=''408760''>just</span>
  <span m=''408890''>going</span> <span m=''408990''>to</span> <span m=''409100''>write</span>
  <span m=''409360''>this</span> <span m=''409510''>program</span> <span m=''409980''>down.</span>
  <span m=''413130''>Now,</span> <span m=''413350''>of</span> <span m=''413520''>course,</span>
  <span m=''413690''>I''m</span> <span m=''413980''>going</span> <span m=''414270''>to</span>
  <span m=''415240''>be</span> <span m=''415790''>saying</span> <span m=''416140''>something</span>
  <span m=''416540''>you</span> <span m=''416660''>have</span> <span m=''416780''>to</span>
  <span m=''416910''>believe.</span> <span m=''417450''>Right?</span> <span m=''417890''>What</span>
  <span m=''417990''>you</span> <span m=''418080''>have</span> <span m=''418180''>to</span>
  <span m=''418260''>believe</span> <span m=''418530''>is I</span> <span m=''418610''>can</span>
  <span m=''418750''>represent</span> <span m=''419170''>these</span> <span m=''419340''>algebraic</span>
  <span m=''419870''>expressions,</span> <span m=''420690''>that</span> <span m=''420940''>I</span>
  <span m=''421020''>can</span> <span m=''421170''>grab</span> <span m=''421440''>their</span>
  <span m=''421580''>parts,</span> <span m=''422720''>that</span> <span m=''422820''>I</span>
  <span m=''422930''>can</span> <span m=''423070''>put</span> <span m=''423210''>them</span>
  <span m=''423340''>together.</span> <span m=''424330''>We''ve</span> <span m=''424510''>invented</span>
  <span m=''424880''>list</span> <span m=''425090''>structures</span> <span m=''425510''>so</span>
  <span m=''425670''>that</span> <span m=''425830''>you</span> <span m=''425920''>can</span>
  <span m=''426050''>do</span> <span m=''426220''>that.</span> <span m=''427620''>But</span>
  <span m=''427800''>you</span> <span m=''427890''>don''t</span> <span m=''428040''>want</span>
  <span m=''428120''>to</span> <span m=''428200''>worry</span> <span m=''428440''>about</span>
  <span m=''428670''>that</span> <span m=''428890''>now.</span> <span m=''429810''>Right</span>
  <span m=''430040''>now</span> <span m=''430200''>I''m</span> <span m=''430310''>going</span>
  <span m=''430380''>to</span> <span m=''430450''>write</span> <span m=''430640''>the</span>
  <span m=''430690''>program</span> <span m=''431050''>that</span> <span m=''431240''>encapsulates</span>
  <span m=''431680''>these</span> <span m=''431860''>rules</span> <span m=''432840''>independent</span>
  <span m=''433470''>of</span> <span m=''433590''>the</span> <span m=''433680''>representation</span>
  <span m=''434650''>of</span> <span m=''434800''>the</span> <span m=''434920''>algebraic</span>
  <span m=''435330''>expressions.</span> </p><p><span m=''440580''>You</span> <span
  m=''440720''>have</span> <span m=''440860''>a</span> <span m=''440920''>derivative</span>
  <span m=''444790''>of</span> <span m=''445040''>an</span> <span m=''445110''>expression</span>
  <span m=''447540''>with</span> <span m=''447610''>respect</span> <span m=''448010''>to</span>
  <span m=''448150''>a</span> <span m=''448210''>variable.</span> <span m=''450280''>This</span>
  <span m=''450780''>is</span> <span m=''450860''>a</span> <span m=''450940''>different</span>
  <span m=''451390''>thing</span> <span m=''451760''>than</span> <span m=''451980''>the</span>
  <span m=''452020''>derivative</span> <span m=''452400''>of</span> <span m=''452480''>the</span>
  <span m=''452560''>function.</span> <span m=''455040''>That''s what</span> <span
  m=''455230''>we</span> <span m=''455400''>saw</span> <span m=''455560''>last</span>
  <span m=''455940''>time,</span> <span m=''456980''>that</span> <span m=''457180''>numerical</span>
  <span m=''457570''>approximation.</span> <span m=''459130''>It''s</span> <span m=''459280''>something</span>
  <span m=''459450''>you</span> <span m=''459560''>can''t</span> <span m=''459840''>open</span>
  <span m=''460080''>up</span> <span m=''460180''>a</span> <span m=''460240''>function.</span>
  <span m=''460860''>It''s</span> <span m=''461070''>just</span> <span m=''461340''>the</span>
  <span m=''461460''>answers.</span> <span m=''462990''>The</span> <span m=''463330''>derivative
  of an</span> <span m=''463830''>expression</span> <span m=''464330''>is</span> <span
  m=''464450''>the</span> <span m=''464510''>way</span> <span m=''464660''>it''s</span>
  <span m=''464790''>written.</span> <span m=''465990''>And</span> <span m=''466220''>therefore</span>
  <span m=''466640''>it''s a</span> <span m=''466790''>syntactic</span> <span m=''467180''>phenomenon.</span>
  <span m=''468410''>And</span> <span m=''468560''>so a</span> <span m=''468670''>lot</span>
  <span m=''468780''>of</span> <span m=''468900''>what</span> <span m=''469030''>we''re
  going</span> <span m=''469130''>to</span> <span m=''469260''>be</span> <span m=''469370''>doing</span>
  <span m=''469610''>today</span> <span m=''470390''>is</span> <span m=''470540''>worrying</span>
  <span m=''470830''>about</span> <span m=''471100''>syntax,</span> <span m=''472370''>syntax</span>
  <span m=''472770''>of</span> <span m=''472840''>expressions</span> <span m=''473400''>and</span>
  <span m=''473520''>things</span> <span m=''473730''>like</span> <span m=''473930''>that.</span>
  </p><p><span m=''474830''>Well, there''s</span> <span m=''475170''>a</span> <span
  m=''475210''>case</span> <span m=''475470''>analysis.</span> <span m=''477700''>Anytime</span>
  <span m=''478220''>we</span> <span m=''478340''>do</span> <span m=''478490''>anything</span>
  <span m=''478790''>complicated</span> <span m=''479790''>thereby</span> <span m=''480105''>a</span>
  <span m=''480420''>recursion,</span> <span m=''480920''>we</span> <span m=''481050''>presumably</span>
  <span m=''481570''>need</span> <span m=''481670''>a</span> <span m=''481770''>case</span>
  <span m=''482020''>analysis.</span> <span m=''483690''>It''s</span> <span m=''483830''>the</span>
  <span m=''483950''>essential</span> <span m=''484350''>way</span> <span m=''484470''>to</span>
  <span m=''484590''>begin.</span> <span m=''485340''>And</span> <span m=''485490''>that''s</span>
  <span m=''485650''>usually a</span> <span m=''485970''>conditional</span> <span
  m=''486590''>of some</span> <span m=''486730''>large</span> <span m=''487020''>kind.</span>
  <span m=''488170''>Well,</span> <span m=''488770''>what</span> <span m=''488970''>are</span>
  <span m=''489130''>their</span> <span m=''489270''>possibilities?</span> <span m=''490000''>the</span>
  <span m=''490200''>first</span> <span m=''490400''>rule</span> <span m=''490640''>that</span>
  <span m=''490750''>you</span> <span m=''490870''>saw</span> <span m=''491400''>is</span>
  <span m=''491590''>this</span> <span m=''491720''>something</span> <span m=''491970''>a</span>
  <span m=''492030''>constant?</span> <span m=''496610''>And</span> <span m=''496870''>what</span>
  <span m=''496990''>I''m</span> <span m=''497110''>asking</span> <span m=''497470''>is,</span>
  <span m=''497600''>is</span> <span m=''497730''>the</span> <span m=''497830''>expression</span>
  <span m=''499520''>a</span> <span m=''499710''>constant</span> <span m=''500330''>with</span>
  <span m=''500510''>respect</span> <span m=''500990''>to</span> <span m=''501070''>the</span>
  <span m=''501170''>variable</span> <span m=''501650''>given?</span> <span m=''504990''>If</span>
  <span m=''505250''>so,</span> <span m=''505800''>the</span> <span m=''506150''>result</span>
  <span m=''506600''>is</span> <span m=''506680''>0,</span> <span m=''507600''>because</span>
  <span m=''507850''>the</span> <span m=''507940''>derivative</span> <span m=''508460''>represents</span>
  <span m=''508930''>the</span> <span m=''509020''>rate</span> <span m=''509200''>of</span>
  <span m=''509290''>change</span> <span m=''509620''>of</span> <span m=''509720''>something.</span>
  </p><p><span m=''511880''>If,</span> <span m=''512090''>however,</span> <span m=''514530''>the</span>
  <span m=''514990''>expression</span> <span m=''515700''>that</span> <span m=''516000''>I''m</span>
  <span m=''517549''>taking the</span> <span m=''517820''>derivative</span> <span
  m=''518169''>of</span> <span m=''518820''>is</span> <span m=''519039''>the</span>
  <span m=''519130''>variable</span> <span m=''519880''>I''m</span> <span m=''520070''>varying,</span>
  <span m=''521919''>then</span> <span m=''522159''>this</span> <span m=''522289''>is</span>
  <span m=''522380''>the</span> <span m=''522450''>same</span> <span m=''522770''>variable,</span>
  <span m=''527220''>the</span> <span m=''527650''>expression</span> <span m=''529630''>var,</span>
  <span m=''531320''>then</span> <span m=''531500''>the</span> <span m=''531580''>rate</span>
  <span m=''531760''>of</span> <span m=''531850''>change</span> <span m=''532250''>of</span>
  <span m=''532400''>the</span> <span m=''532560''>expression</span> <span m=''533050''>with</span>
  <span m=''533190''>respect</span> <span m=''533530''>to</span> <span m=''533600''>the</span>
  <span m=''533660''>variable</span> <span m=''534070''>is</span> <span m=''534190''>1.</span>
  <span m=''535560''>It''s</span> <span m=''535720''>the</span> <span m=''535790''>same</span>
  <span m=''536080''>1.</span> </p><p><span m=''538970''>Well</span> <span m=''539130''>now</span>
  <span m=''539310''>there</span> <span m=''539460''>are</span> <span m=''539530''>a</span>
  <span m=''539570''>couple</span> <span m=''539780''>of</span> <span m=''539860''>other</span>
  <span m=''539990''>possibilities.</span> <span m=''541490''>It</span> <span m=''541710''>could,</span>
  <span m=''541980''>for</span> <span m=''542110''>example,</span> <span m=''542450''>be</span>
  <span m=''542620''>a</span> <span m=''542670''>sum.</span> <span m=''544010''>Well,</span>
  <span m=''544170''>I</span> <span m=''544270''>don''t</span> <span m=''544400''>know</span>
  <span m=''544470''>how</span> <span m=''544680''>I''m</span> <span m=''544746''>going</span>
  <span m=''544813''>to</span> <span m=''544880''>express</span> <span m=''545260''>sums</span>
  <span m=''545490''>yet.</span> <span m=''546140''>Actually</span> <span m=''546490''>I</span>
  <span m=''546580''>do.</span> <span m=''547180''>But</span> <span m=''547290''>I</span>
  <span m=''547510''>haven''t told</span> <span m=''547770''>you</span> <span m=''547870''>yet.</span>
  <span m=''550370''>But</span> <span m=''550920''>is</span> <span m=''551070''>it</span>
  <span m=''551360''>a</span> <span m=''551783''>sum?</span> <span m=''552630''>I''m</span>
  <span m=''552790''>imagining</span> <span m=''553350''>that</span> <span m=''553480''>there''s</span>
  <span m=''553630''>some</span> <span m=''553800''>way</span> <span m=''553930''>of</span>
  <span m=''554010''>telling.</span> <span m=''555520''>I''m</span> <span m=''555730''>doing</span>
  <span m=''556220''>a</span> <span m=''556360''>dispatch</span> <span m=''557370''>on</span>
  <span m=''557550''>the</span> <span m=''557660''>type</span> <span m=''558370''>of</span>
  <span m=''558480''>the</span> <span m=''558600''>expression</span> <span m=''559110''>here,</span>
  <span m=''560860''>absolutely</span> <span m=''561380''>essential</span> <span m=''562560''>in</span>
  <span m=''562700''>building</span> <span m=''563060''>languages.</span> <span m=''564960''>Languages</span>
  <span m=''565180''>are made</span> <span m=''565430''>out of</span> <span m=''565670''>different</span>
  <span m=''565880''>expressions.</span> <span m=''566520''>And</span> <span m=''566720''>soon
  we''re</span> <span m=''566910''>going</span> <span m=''566980''>to</span> <span
  m=''567060''>see</span> <span m=''567260''>that</span> <span m=''567970''>in</span>
  <span m=''568090''>our</span> <span m=''568200''>more</span> <span m=''568410''>powerful</span>
  <span m=''568930''>methods</span> <span m=''569510''>of</span> <span m=''569700''>building</span>
  <span m=''570000''>languages</span> <span m=''570370''>on</span> <span m=''570530''>languages.</span>
  </p><p><span m=''572760''>Is</span> <span m=''572920''>an</span> <span m=''573000''>expression</span>
  <span m=''573500''>a</span> <span m=''573560''>sum?</span> <span m=''575530''>If</span>
  <span m=''575750''>it''s a</span> <span m=''575860''>sum,</span> <span m=''576370''>well,</span>
  <span m=''576500''>we</span> <span m=''576610''>know</span> <span m=''576760''>the</span>
  <span m=''576910''>rule</span> <span m=''577210''>for</span> <span m=''577890''>derivative</span>
  <span m=''578280''>of the</span> <span m=''578360''>sum</span> <span m=''578990''>is</span>
  <span m=''579430''>the</span> <span m=''579730''>sum</span> <span m=''580040''>of</span>
  <span m=''580190''>the</span> <span m=''580270''>derivatives</span> <span m=''580750''>of</span>
  <span m=''580930''>the</span> <span m=''581020''>parts.</span> <span m=''582160''>One</span>
  <span m=''582320''>of them is</span> <span m=''582510''>called</span> <span m=''582720''>the</span>
  <span m=''582830''>addend</span> <span m=''583180''>and</span> <span m=''583270''>the</span>
  <span m=''583370''>other</span> <span m=''583500''>is</span> <span m=''583590''>the</span>
  <span m=''583700''>augend.</span> <span m=''584050''>But</span> <span m=''584380''>I</span>
  <span m=''584560''>don''t</span> <span m=''584660''>have</span> <span m=''584800''>enough</span>
  <span m=''584860''>space</span> <span m=''585150''>on</span> <span m=''585220''>the</span>
  <span m=''585290''>blackboard</span> <span m=''585710''>to</span> <span m=''585870''>such</span>
  <span m=''586090''>long</span> <span m=''586330''>names.</span> <span m=''586810''>So</span>
  <span m=''587010''>I''ll</span> <span m=''587150''>call</span> <span m=''587330''>them</span>
  <span m=''587410''>A1</span> <span m=''587560''>and</span> <span m=''587780''>A2.</span>
  </p><p><span m=''588660''>I</span> <span m=''588990''>want</span> <span m=''589250''>to</span>
  <span m=''589510''>make</span> <span m=''589700''>a</span> <span m=''589760''>sum.</span>
  <span m=''593100''>Do</span> <span m=''593580''>you</span> <span m=''593720''>remember</span>
  <span m=''594060''>which</span> <span m=''594270''>is</span> <span m=''594370''>the</span>
  <span m=''594460''>sum for end</span> <span m=''594920''>or</span> <span m=''595000''>the</span>
  <span m=''595080''>menu end?</span> <span m=''597300''>Or</span> <span m=''597710''>was</span>
  <span m=''597860''>it</span> <span m=''597970''>the</span> <span m=''598120''>dividend</span>
  <span m=''598980''>and the</span> <span m=''599280''>divisor</span> <span m=''600210''>or</span>
  <span m=''600310''>something</span> <span m=''600590''>like</span> <span m=''600800''>that?</span>
  <span m=''601700''>Make</span> <span m=''602070''>sum</span> <span m=''602740''>of</span>
  <span m=''602980''>the</span> <span m=''603070''>derivative</span> <span m=''606320''>of</span>
  <span m=''606610''>the</span> <span m=''607610''>A1,</span> <span m=''607780''>I''ll</span>
  <span m=''608060''>call</span> <span m=''608220''>it.</span> <span m=''608720''>It''s
  the</span> <span m=''608970''>addend</span> <span m=''609610''>of</span> <span m=''609960''>the</span>
  <span m=''610140''>expression</span> <span m=''611920''>with</span> <span m=''612200''>respect</span>
  <span m=''612500''>to</span> <span m=''612560''>the</span> <span m=''612640''>variable,</span>
  <span m=''614970''>and</span> <span m=''615720''>the</span> <span m=''616350''>derivative</span>
  <span m=''620070''>of</span> <span m=''620170''>the</span> <span m=''620350''>A2</span>
  <span m=''621890''>of</span> <span m=''621990''>the</span> <span m=''622100''>expression,</span>
  <span m=''623506''>because</span> <span m=''623890''>the</span> <span m=''624400''>two</span>
  <span m=''624540''>arguments,</span> <span m=''625410''>the</span> <span m=''626080''>addition</span>
  <span m=''626850''>with</span> <span m=''627020''>respect</span> <span m=''627370''>to
  the</span> <span m=''627450''>variable.</span> </p><p><span m=''632450''>And</span>
  <span m=''632700''>another</span> <span m=''633100''>rule</span> <span m=''633350''>that</span>
  <span m=''633490''>we</span> <span m=''633630''>know</span> <span m=''634080''>is</span>
  <span m=''634240''>product</span> <span m=''634640''>rule,</span> <span m=''635360''>which</span>
  <span m=''635600''>is,</span> <span m=''636160''>if</span> <span m=''636350''>the</span>
  <span m=''636440''>expression</span> <span m=''636880''>is</span> <span m=''636960''>a</span>
  <span m=''637020''>product.</span> <span m=''643090''>By</span> <span m=''643385''>the</span>
  <span m=''643680''>way,</span> <span m=''643870''>it''s a</span> <span m=''643910''>good</span>
  <span m=''644120''>idea</span> <span m=''644490''>when</span> <span m=''644630''>you''re</span>
  <span m=''644760''>defining</span> <span m=''645500''>things,</span> <span m=''647070''>when</span>
  <span m=''647230''>you''re</span> <span m=''647260''>defining</span> <span m=''647880''>predicates,</span>
  <span m=''648990''>to</span> <span m=''649090''>give</span> <span m=''649270''>them</span>
  <span m=''649390''>a</span> <span m=''649440''>name</span> <span m=''649750''>that</span>
  <span m=''649860''>ends</span> <span m=''650080''>in</span> <span m=''650160''>a</span>
  <span m=''650220''>question</span> <span m=''650580''>mark.</span> <span m=''651290''>This</span>
  <span m=''651460''>question</span> <span m=''651720''>mark</span> <span m=''651880''>doesn''t</span>
  <span m=''652140''>mean</span> <span m=''652370''>anything.</span> <span m=''653140''>It''s</span>
  <span m=''653330''>for</span> <span m=''653490''>us</span> <span m=''653750''>as</span>
  <span m=''653880''>an</span> <span m=''653950''>agreement.</span> <span m=''654730''>It''s</span>
  <span m=''654880''>a</span> <span m=''654920''>conventional</span> <span m=''655500''>interface</span>
  <span m=''655870''>between</span> <span m=''656170''>humans</span> <span m=''657070''>so</span>
  <span m=''657240''>you</span> <span m=''657390''>can</span> <span m=''657540''>read</span>
  <span m=''657710''>my</span> <span m=''657850''>programs</span> <span m=''658240''>more</span>
  <span m=''658430''>easily.</span> <span m=''659980''>So</span> <span m=''660250''>I</span>
  <span m=''660330''>want</span> <span m=''660600''>you</span> <span m=''660730''>to,</span>
  <span m=''661110''>when</span> <span m=''661260''>you</span> <span m=''661370''>write</span>
  <span m=''661610''>programs,</span> <span m=''662010''>if</span> <span m=''662090''>you</span>
  <span m=''662180''>define</span> <span m=''662510''>a</span> <span m=''662560''>predicate</span>
  <span m=''663140''>procedure,</span> <span m=''663740''>that''s</span> <span m=''664180''>something</span>
  <span m=''664395''>that</span> <span m=''664610''>rings</span> <span m=''665070''>true</span>
  <span m=''665200''>of</span> <span m=''665330''>false,</span> <span m=''666090''>it</span>
  <span m=''666160''>should</span> <span m=''666280''>have</span> <span m=''666380''>a</span>
  <span m=''666480''>name</span> <span m=''666760''>which</span> <span m=''667070''>ends
  in</span> <span m=''667120''>question</span> <span m=''667440''>mark.</span> <span
  m=''667720''>The</span> <span m=''668160''>list</span> <span m=''668360''>doesn''t</span>
  <span m=''668630''>care.</span> <span m=''669740''>I</span> <span m=''669960''>care.</span>
  </p><p><span m=''671740''>I</span> <span m=''671870''>want</span> <span m=''672060''>to</span>
  <span m=''672480''>make</span> <span m=''672780''>a</span> <span m=''672830''>sum.</span>
  <span m=''673400''>Because</span> <span m=''675020''>the</span> <span m=''675580''>derivative</span>
  <span m=''675920''>of</span> <span m=''676010''>a</span> <span m=''676070''>product</span>
  <span m=''676840''>is</span> <span m=''677030''>the</span> <span m=''677110''>sum</span>
  <span m=''677990''>of</span> <span m=''678180''>the</span> <span m=''678280''>first</span>
  <span m=''678570''>times</span> <span m=''678810''>the derivative</span> <span m=''679060''>of
  the</span> <span m=''679130''>second</span> <span m=''679480''>plus</span> <span
  m=''679610''>the</span> <span m=''679760''>second</span> <span m=''679920''>times</span>
  <span m=''680060''>the derivative</span> <span m=''680290''>of the</span> <span
  m=''680440''>first.</span> <span m=''683500''>Make</span> <span m=''683765''>a</span>
  <span m=''684030''>sum</span> <span m=''685750''>of</span> <span m=''686230''>two</span>
  <span m=''686620''>things,</span> <span m=''689710''>a</span> <span m=''689890''>product</span>
  <span m=''693809''>of,</span> <span m=''694300''>well,</span> <span m=''694560''>I''m</span>
  <span m=''694640''>going</span> <span m=''694700''>to</span> <span m=''694770''>say</span>
  <span m=''695290''>the</span> <span m=''695580''>M1</span> <span m=''697470''>of</span>
  <span m=''697620''>the</span> <span m=''697710''>expression,</span> <span m=''699970''>and</span>
  <span m=''700090''>the</span> <span m=''700220''>derivative</span> <span m=''703320''>of</span>
  <span m=''703820''>the</span> <span m=''704030''>M2</span> <span m=''705790''>of</span>
  <span m=''705950''>the</span> <span m=''706030''>expression</span> <span m=''707560''>with</span>
  <span m=''708030''>respect</span> <span m=''708410''>to the</span> <span m=''708490''>variable,</span>
  <span m=''712060''>and</span> <span m=''712270''>the</span> <span m=''712350''>product</span>
  <span m=''720540''>of</span> <span m=''720850''>the</span> <span m=''721680''>derivative</span>
  <span m=''725350''>of</span> <span m=''725570''>M1,</span> <span m=''726960''>the</span>
  <span m=''727230''>multiplier</span> <span m=''728410''>of</span> <span m=''728500''>the</span>
  <span m=''728600''>expression,</span> <span m=''730720''>with</span> <span m=''731010''>respect</span>
  <span m=''731200''>to</span> <span m=''731270''>the</span> <span m=''731600''>variable.</span>
  <span m=''733450''>It''s</span> <span m=''733730''>the product</span> <span m=''734040''>of</span>
  <span m=''734140''>that</span> <span m=''734470''>and</span> <span m=''734630''>the</span>
  <span m=''734690''>multiplicand,</span> <span m=''735790''>M2,</span> <span m=''736500''>of</span>
  <span m=''736920''>the</span> <span m=''737340''>expression.</span> <span m=''741660''>Make</span>
  <span m=''741840''>that</span> <span m=''742050''>product.</span> <span m=''742630''>Make
  the</span> <span m=''742940''>sum.</span> <span m=''743850''>Close</span> <span
  m=''744170''>that</span> <span m=''744360''>case.</span> </p><p><span m=''745080''>And,</span>
  <span m=''745250''>of</span> <span m=''745350''>course,</span> <span m=''745740''>I</span>
  <span m=''745930''>could</span> <span m=''746050''>add</span> <span m=''746230''>as</span>
  <span m=''746320''>many</span> <span m=''746590''>cases</span> <span m=''747090''>as
  I</span> <span m=''747220''>like</span> <span m=''747520''>here</span> <span m=''748190''>for</span>
  <span m=''748590''>a</span> <span m=''748630''>complete</span> <span m=''749000''>set</span>
  <span m=''749130''>of</span> <span m=''749230''>rules</span> <span m=''749500''>you</span>
  <span m=''749580''>might</span> <span m=''749800''>find</span> <span m=''750000''>in
  a</span> <span m=''750090''>calculus</span> <span m=''750570''>book.</span> <span
  m=''754880''>So</span> <span m=''755110''>this</span> <span m=''755360''>is</span>
  <span m=''756730''>what</span> <span m=''756920''>it</span> <span m=''757040''>takes</span>
  <span m=''758230''>to</span> <span m=''758360''>encapsulate</span> <span m=''758870''>those</span>
  <span m=''759080''>rules.</span> <span m=''761184''>And</span> <span m=''761590''>you</span>
  <span m=''761780''>see,</span> <span m=''761930''>you</span> <span m=''762040''>have</span>
  <span m=''762160''>to</span> <span m=''762280''>realize</span> <span m=''762690''>there''s</span>
  <span m=''762790''>a</span> <span m=''762830''>lot</span> <span m=''763010''>of</span>
  <span m=''763080''>wishful</span> <span m=''763370''>thinking</span> <span m=''763660''>here.</span>
  <span m=''764690''>I</span> <span m=''764870''>haven''t</span> <span m=''765040''>told</span>
  <span m=''765220''>you</span> <span m=''765300''>anything</span> <span m=''765920''>about</span>
  <span m=''766130''>how</span> <span m=''766250''>I''m going to</span> <span m=''766400''>make</span>
  <span m=''766620''>these</span> <span m=''766770''>representations.</span> <span
  m=''768570''>Now,</span> <span m=''769170''>once</span> <span m=''769500''>I''ve</span>
  <span m=''769600''>decided</span> <span m=''770620''>that</span> <span m=''770780''>this</span>
  <span m=''770930''>is</span> <span m=''771000''>my</span> <span m=''771210''>set</span>
  <span m=''771390''>of</span> <span m=''771500''>rules,</span> <span m=''772660''>I</span>
  <span m=''772830''>think</span> <span m=''773000''>it''s</span> <span m=''773170''>time</span>
  <span m=''773830''>to</span> <span m=''773950''>play</span> <span m=''774130''>with</span>
  <span m=''774230''>the</span> <span m=''774340''>representation.</span> <span m=''775820''>Let''s</span>
  <span m=''775980''>attack</span> <span m=''776340''>that/</span> </p><p><span m=''778030''>Well,</span>
  <span m=''778230''>first</span> <span m=''778530''>of</span> <span m=''778630''>all,</span>
  <span m=''779100''>I''m</span> <span m=''779260''>going</span> <span m=''779330''>to</span>
  <span m=''779400''>play</span> <span m=''779600''>a</span> <span m=''780060''>pun.</span>
  <span m=''781120''>It''s</span> <span m=''781300''>an</span> <span m=''781380''>important</span>
  <span m=''781820''>pun.</span> <span m=''782870''>It''s</span> <span m=''784190''>a</span>
  <span m=''784370''>key</span> <span m=''784580''>to a</span> <span m=''784690''>sort</span>
  <span m=''785540''>of</span> <span m=''785650''>powerful</span> <span m=''786210''>idea.</span>
  <span m=''789750''>If</span> <span m=''789920''>I</span> <span m=''790020''>want</span>
  <span m=''790140''>to</span> <span m=''790270''>represent</span> <span m=''791240''>sums,</span>
  <span m=''791690''>and</span> <span m=''791830''>products,</span> <span m=''792220''>and</span>
  <span m=''792350''>differences,</span> <span m=''792790''>and</span> <span m=''792900''>quotients,</span>
  <span m=''793380''>and</span> <span m=''793500''>things</span> <span m=''793770''>like</span>
  <span m=''794000''>that,</span> <span m=''795340''>why</span> <span m=''795530''>not</span>
  <span m=''795720''>use</span> <span m=''795970''>the</span> <span m=''796080''>same</span>
  <span m=''796450''>language</span> <span m=''797440''>as</span> <span m=''797590''>I''m</span>
  <span m=''797710''>writing</span> <span m=''797940''>my</span> <span m=''798050''>program</span>
  <span m=''798540''>in?</span> <span m=''800660''>I</span> <span m=''800720''>write</span>
  <span m=''800930''>my</span> <span m=''801030''>program</span> <span m=''801730''>in</span>
  <span m=''801910''>algebraic</span> <span m=''802400''>expressions</span> <span
  m=''802990''>that</span> <span m=''803130''>look</span> <span m=''803340''>like</span>
  <span m=''804432''>the</span> <span m=''804800''>sum</span> <span m=''805440''>of</span>
  <span m=''805740''>the</span> <span m=''805980''>product</span> <span m=''806990''>on</span>
  <span m=''807310''>a</span> <span m=''807920''>and</span> <span m=''808200''>the</span>
  <span m=''808320''>product</span> <span m=''809280''>of</span> <span m=''809500''>x</span>
  <span m=''809850''>and</span> <span m=''810160''>x,</span> <span m=''812600''>and</span>
  <span m=''812890''>things</span> <span m=''813110''>like</span> <span m=''813360''>that.</span>
  <span m=''814330''>And</span> <span m=''814680''>the</span> <span m=''814930''>product</span>
  <span m=''815780''>of</span> <span m=''816050''>b</span> <span m=''816340''>and</span>
  <span m=''816550''>x</span> <span m=''817140''>and</span> <span m=''817400''>c,</span>
  <span m=''817990''>whatever,</span> <span m=''818630''>make</span> <span m=''818880''>that
  a</span> <span m=''819090''>sum</span> <span m=''819390''>of</span> <span m=''819480''>the</span>
  <span m=''819550''>product.</span> <span m=''820960''>Right</span> <span m=''821160''>now</span>
  <span m=''821300''>I</span> <span m=''821400''>don''t</span> <span m=''821620''>want</span>
  <span m=''821720''>to</span> <span m=''821830''>have</span> <span m=''822230''>procedures</span>
  <span m=''822730''>with</span> <span m=''822910''>unknown</span> <span m=''823230''>numbers</span>
  <span m=''823550''>of</span> <span m=''823660''>arguments,</span> <span m=''825070''>a</span>
  <span m=''825160''>product</span> <span m=''825610''>of</span> <span m=''825930''>b</span>
  <span m=''826250''>and</span> <span m=''826500''>x</span> <span m=''827190''>and</span>
  <span m=''828020''>c.</span> </p><p><span m=''831050''>This</span> <span m=''831730''>is</span>
  <span m=''831850''>list</span> <span m=''832090''>structure.</span> <span m=''834280''>And</span>
  <span m=''834420''>the</span> <span m=''834560''>reason</span> <span m=''834830''>why</span>
  <span m=''835040''>this</span> <span m=''835220''>is</span> <span m=''835320''>nice,</span>
  <span m=''835930''>is</span> <span m=''836080''>because</span> <span m=''836410''>any</span>
  <span m=''836610''>one</span> <span m=''836810''>of</span> <span m=''836950''>these</span>
  <span m=''837090''>objects</span> <span m=''837590''>has</span> <span m=''837760''>a</span>
  <span m=''837810''>property.</span> <span m=''840380''>I</span> <span m=''840480''>know</span>
  <span m=''840680''>where</span> <span m=''840860''>the</span> <span m=''840980''>car</span>
  <span m=''841350''>is.</span> <span m=''841970''>The</span> <span m=''842080''>car</span>
  <span m=''842420''>is</span> <span m=''842510''>the</span> <span m=''842630''>operator.</span>
  <span m=''844100''>And</span> <span m=''844220''>the</span> <span m=''844350''>operands</span>
  <span m=''845070''>are</span> <span m=''845230''>the</span> <span m=''845330''>successive</span>
  <span m=''845820''>cdrs</span> <span m=''847590''>the</span> <span m=''847810''>successive</span>
  <span m=''848190''>cars</span> <span m=''848780''>of</span> <span m=''848890''>the</span>
  <span m=''849000''>cdrs</span> <span m=''849360''>of</span> <span m=''849480''>the</span>
  <span m=''849550''>list</span> <span m=''849860''>that this</span> <span m=''849930''>is.</span>
  <span m=''852276''>It</span> <span m=''852720''>makes</span> <span m=''852940''>it</span>
  <span m=''853030''>very</span> <span m=''853250''>convenient.</span> <span m=''854470''>I</span>
  <span m=''854600''>have</span> <span m=''854730''>to</span> <span m=''854860''>parse</span>
  <span m=''855220''>it.</span> <span m=''855560''>It''s</span> <span m=''855690''>been</span>
  <span m=''855840''>done</span> <span m=''856060''>for</span> <span m=''856180''>me.</span>
  <span m=''857590''>I''m</span> <span m=''857710''>using</span> <span m=''858030''>the</span>
  <span m=''858190''>embedding</span> <span m=''858600''>and Lisp</span> <span m=''859160''>to</span>
  <span m=''859390''>advantage.</span> </p><p><span m=''862860''>So,</span> <span
  m=''863080''>for</span> <span m=''863290''>example,</span> <span m=''866440''>let''s</span>
  <span m=''866610''>start</span> <span m=''866870''>using</span> <span m=''867390''>list</span>
  <span m=''867500''>structure</span> <span m=''868750''>to</span> <span m=''869070''>write</span>
  <span m=''869340''>down</span> <span m=''871510''>the</span> <span m=''871620''>representation</span>
  <span m=''872620''>that I''m</span> <span m=''872960''>implicitly</span> <span m=''873370''>assuming</span>
  <span m=''873650''>here.</span> <span m=''875390''>Well</span> <span m=''875600''>I
  have to</span> <span m=''875680''>define</span> <span m=''876100''>various</span>
  <span m=''876500''>things</span> <span m=''876790''>that</span> <span m=''876880''>are</span>
  <span m=''876980''>implied</span> <span m=''877350''>in this</span> <span m=''877830''>representation.</span>
  <span m=''878640''>Like</span> <span m=''878830''>I</span> <span m=''878920''>have</span>
  <span m=''879010''>to</span> <span m=''879080''>find</span> <span m=''879380''>out</span>
  <span m=''879890''>how</span> <span m=''880010''>to</span> <span m=''880070''>do</span>
  <span m=''880180''>a</span> <span m=''880260''>constant,</span> <span m=''881210''>how</span>
  <span m=''881450''>you do</span> <span m=''881570''>same</span> <span m=''881890''>variable.</span>
  <span m=''882520''>Let''s</span> <span m=''882670''>do</span> <span m=''882790''>those</span>
  <span m=''883040''>first.</span> <span m=''883945''>That''s</span> <span m=''884270''>pretty</span>
  <span m=''884530''>easy</span> <span m=''884770''>enough.</span> <span m=''885890''>Now</span>
  <span m=''886320''>I''m going</span> <span m=''886430''>to be</span> <span m=''886770''>introducing</span>
  <span m=''886990''>lots of</span> <span m=''887060''>primitives</span> <span m=''887410''>here,</span>
  <span m=''888650''>because</span> <span m=''888920''>these</span> <span m=''889130''>are
  the</span> <span m=''889200''>primitives</span> <span m=''889550''>that</span> <span
  m=''889680''>come</span> <span m=''889850''>with</span> <span m=''890040''>list</span>
  <span m=''890100''>structure.</span> </p><p><span m=''891745''>OK,</span> <span
  m=''892130''>you</span> <span m=''892280''>define</span> <span m=''892640''>a</span>
  <span m=''892700''>constant.</span> <span m=''902800''>And</span> <span m=''902950''>what</span>
  <span m=''903060''>I</span> <span m=''903170''>mean</span> <span m=''903380''>by</span>
  <span m=''903510''>a</span> <span m=''903640''>constant,</span> <span m=''904250''>an</span>
  <span m=''904370''>expression</span> <span m=''904830''>that''s</span> <span m=''904940''>constant</span>
  <span m=''906350''>with</span> <span m=''906520''>respect</span> <span m=''906860''>to</span>
  <span m=''906940''>a</span> <span m=''907050''>veritable,</span> <span m=''909120''>is</span>
  <span m=''909710''>that</span> <span m=''910180''>the</span> <span m=''910300''>expression</span>
  <span m=''910770''>is</span> <span m=''910860''>something</span> <span m=''911170''>simple.</span>
  <span m=''911530''>I</span> <span m=''911610''>can''t</span> <span m=''911870''>take</span>
  <span m=''912040''>it</span> <span m=''912170''>into</span> <span m=''912400''>pieces,</span>
  <span m=''913220''>and</span> <span m=''913390''>yet</span> <span m=''913550''>it</span>
  <span m=''913640''>isn''t</span> <span m=''913880''>that</span> <span m=''914070''>variable.</span>
  <span m=''916550''>I</span> <span m=''916630''>can''t</span> <span m=''916900''>break</span>
  <span m=''917120''>it</span> <span m=''917220''>up,</span> <span m=''917570''>and</span>
  <span m=''917700''>yet</span> <span m=''917840''>it</span> <span m=''917910''>isn''t</span>
  <span m=''918130''>that</span> <span m=''918300''>variable.</span> <span m=''918940''>That</span>
  <span m=''919290''>does</span> <span m=''919420''>not</span> <span m=''919650''>mean</span>
  <span m=''919890''>that</span> <span m=''920100''>there</span> <span m=''920570''>may</span>
  <span m=''920730''>be</span> <span m=''921190''>other</span> <span m=''921510''>expressions</span>
  <span m=''922220''>that</span> <span m=''922840''>are</span> <span m=''922890''>more</span>
  <span m=''923070''>complicated</span> <span m=''924060''>that</span> <span m=''924460''>are</span>
  <span m=''924520''>constants.</span> <span m=''925230''>It''s</span> <span m=''925390''>just</span>
  <span m=''925610''>that</span> <span m=''925710''>I''m</span> <span m=''925850''>going</span>
  <span m=''925920''>to</span> <span m=''925990''>look</span> <span m=''926160''>at</span>
  <span m=''926220''>the</span> <span m=''926290''>primitive</span> <span m=''926700''>constants</span>
  <span m=''928310''>in</span> <span m=''928450''>this</span> <span m=''928600''>way.</span>
  </p><p><span m=''930510''>So</span> <span m=''930610''>what</span> <span m=''930780''>this</span>
  <span m=''930970''>is,</span> <span m=''931270''>is</span> <span m=''931490''>it</span>
  <span m=''931690''>says</span> <span m=''932180''>that''s</span> <span m=''932540''>it''s
  the</span> <span m=''932720''>and.</span> <span m=''934080''>I</span> <span m=''934230''>can</span>
  <span m=''934390''>combine</span> <span m=''934900''>predicate</span> <span m=''935340''>expressions</span>
  <span m=''936160''>which</span> <span m=''936370''>return</span> <span m=''936730''>true</span>
  <span m=''937030''>or false with</span> <span m=''937330''>and.</span> <span m=''938610''>Something</span>
  <span m=''938990''>atomic,</span> <span m=''943890''>The</span> <span m=''944250''>expression</span>
  <span m=''944700''>is</span> <span m=''944810''>atomic,</span> <span m=''945290''>meaning</span>
  <span m=''945600''>it</span> <span m=''945700''>cannot</span> <span m=''945940''>be</span>
  <span m=''946040''>broken</span> <span m=''946370''>into</span> <span m=''946520''>parts.</span>
  <span m=''947050''>It</span> <span m=''947170''>doesn''t</span> <span m=''947420''>have</span>
  <span m=''947650''>a</span> <span m=''947710''>car</span> <span m=''947980''>and</span>
  <span m=''948040''>a</span> <span m=''948090''>cdr.</span> <span m=''949520''>It''s</span>
  <span m=''949730''>not</span> <span m=''949930''>a</span> <span m=''949990''>list.</span>
  <span m=''950910''>It</span> <span m=''951130''>adds a</span> <span m=''951170''>special</span>
  <span m=''951520''>test</span> <span m=''951990''>built</span> <span m=''952230''>into</span>
  <span m=''952370''>the</span> <span m=''952520''>system.</span> <span m=''954250''>And</span>
  <span m=''954470''>it''s</span> <span m=''954660''>not</span> <span m=''957840''>identically</span>
  <span m=''958400''>equal</span> <span m=''958800''>to</span> <span m=''963860''>that</span>
  <span m=''964110''>variable.</span> <span m=''966950''>I''m</span> <span m=''967090''>representing</span>
  <span m=''967580''>my</span> <span m=''967740''>variable</span> <span m=''970500''>by</span>
  <span m=''970720''>things</span> <span m=''971020''>that</span> <span m=''971140''>are</span>
  <span m=''971290''>symbols</span> <span m=''971810''>which</span> <span m=''971960''>cannot</span>
  <span m=''972200''>be</span> <span m=''972310''>broken</span> <span m=''972770''>into</span>
  <span m=''972870''>pieces,</span> <span m=''974090''>things</span> <span m=''974290''>like</span>
  <span m=''974540''>x,</span> <span m=''975280''>and</span> <span m=''975470''>y,</span>
  <span m=''976550''>things</span> <span m=''976810''>like</span> <span m=''977030''>this.</span>
  <span m=''979850''>Whereas,</span> <span m=''980100''>of</span> <span m=''980220''>course,</span>
  <span m=''980350''>something</span> <span m=''980600''>like</span> <span m=''980800''>this</span>
  <span m=''981030''>can</span> <span m=''981250''>be</span> <span m=''981370''>broken</span>
  <span m=''981730''>up</span> <span m=''981890''>into</span> <span m=''982050''>pieces.</span>
  </p><p><span m=''984860''>And</span> <span m=''984980''>the</span> <span m=''985110''>same</span>
  <span m=''985390''>variable</span> <span m=''997594''>of</span> <span m=''998090''>an</span>
  <span m=''998220''>expression</span> <span m=''1000010''>with</span> <span m=''1000080''>respect</span>
  <span m=''1000400''>to</span> <span m=''1000490''>a</span> <span m=''1000560''>variable</span>
  <span m=''1006030''>is,</span> <span m=''1006510''>in</span> <span m=''1006710''>fact,</span>
  <span m=''1007060''>an</span> <span m=''1007190''>atomic</span> <span m=''1007650''>expression.</span>
  <span m=''1008840''>I</span> <span m=''1008970''>want</span> <span m=''1009090''>to</span>
  <span m=''1009210''>have</span> <span m=''1009380''>an</span> <span m=''1009610''>atomic</span>
  <span m=''1010040''>expression,</span> <span m=''1018440''>which</span> <span m=''1018860''>is</span>
  <span m=''1019040''>identical.</span> <span m=''1028030''>I</span> <span m=''1028160''>don''t</span>
  <span m=''1028319''>want</span> <span m=''1028410''>to</span> <span m=''1028500''>look</span>
  <span m=''1028700''>inside</span> <span m=''1029260''>this</span> <span m=''1030650''>stuff</span>
  <span m=''1031030''>anymore.</span> <span m=''1033329''>These</span> <span m=''1033589''>are</span>
  <span m=''1033829''>primitive</span> <span m=''1034890''>maybe.</span> <span m=''1036040''>But</span>
  <span m=''1036160''>it</span> <span m=''1036210''>doesn''t</span> <span m=''1036520''>matter.</span>
  <span m=''1038180''>I''m</span> <span m=''1039310''>using</span> <span m=''1039700''>things
  that</span> <span m=''1039950''>are</span> <span m=''1040020''>given</span> <span
  m=''1040839''>to</span> <span m=''1040920''>me</span> <span m=''1041040''>with</span>
  <span m=''1041130''>a</span> <span m=''1041230''>language.</span> <span m=''1042569''>I''m</span>
  <span m=''1042920''>not terribly</span> <span m=''1043180''>interest</span> <span
  m=''1043470''>in</span> <span m=''1043740''>them</span> </p><p><span m=''1044300''>Now</span>
  <span m=''1044650''>how do</span> <span m=''1045000''>we</span> <span m=''1045140''>deal</span>
  <span m=''1045319''>with</span> <span m=''1045490''>sums?</span> <span m=''1046900''>Ah,</span>
  <span m=''1047210''>something</span> <span m=''1047540''>very</span> <span m=''1047810''>interesting</span>
  <span m=''1048180''>will</span> <span m=''1048260''>happen.</span> <span m=''1049100''>A</span>
  <span m=''1049290''>sum is</span> <span m=''1049660''>something</span> <span m=''1050230''>which</span>
  <span m=''1050420''>is</span> <span m=''1050510''>not</span> <span m=''1050720''>atomic</span>
  <span m=''1051530''>and</span> <span m=''1051750''>begins</span> <span m=''1052130''>with</span>
  <span m=''1052260''>the</span> <span m=''1052380''>plus</span> <span m=''1052680''>symbol.</span>
  <span m=''1055230''>That''s</span> <span m=''1055460''>what</span> <span m=''1055570''>it</span>
  <span m=''1055650''>means.</span> <span m=''1056680''>So</span> <span m=''1057030''>here,</span>
  <span m=''1058640''>I</span> <span m=''1058740''>will</span> <span m=''1058860''>define.</span>
  <span m=''1065630''>An</span> <span m=''1065970''>question</span> <span m=''1066390''>is</span>
  <span m=''1066550''>a</span> <span m=''1066620''>sum</span> <span m=''1073145''>if</span>
  <span m=''1073430''>and</span> <span m=''1076550''>it''s</span> <span m=''1076790''>not</span>
  <span m=''1076990''>atomic</span> <span m=''1083929''>and</span> <span m=''1084422''>it''s</span>
  <span m=''1087890''>head,</span> <span m=''1088380''>it''s beginning,</span> <span
  m=''1089290''>its</span> <span m=''1089450''>car</span> <span m=''1090720''>of</span>
  <span m=''1091100''>the</span> <span m=''1091200''>expression</span> <span m=''1093170''>is</span>
  <span m=''1093600''>the</span> <span m=''1093910''>symbol</span> <span m=''1094740''>plus.</span>
  </p><p><span m=''1099950''>Now</span> <span m=''1100130''>you''re</span> <span m=''1100270''>about</span>
  <span m=''1100550''>to</span> <span m=''1100630''>see</span> <span m=''1100810''>something</span>
  <span m=''1101160''>you</span> <span m=''1101260''>haven''t</span> <span m=''1101550''>seen</span>
  <span m=''1101730''>before,</span> <span m=''1103160''>this</span> <span m=''1103340''>quotation.</span>
  <span m=''1106240''>Why</span> <span m=''1106640''>do</span> <span m=''1106770''>I</span>
  <span m=''1106920''>have</span> <span m=''1107070''>that</span> <span m=''1107240''>quotation</span>
  <span m=''1107760''>there?</span> <span m=''1109440''>Say</span> <span m=''1109740''>your</span>
  <span m=''1109990''>name,</span> </p><p><span m=''1110970''>AUDIENCE: Susanna.</span>
  </p><p><span m=''1111410''>PROFESSOR: Louder.</span> </p><p><span m=''1112270''>AUDIENCE:
  Susanna</span> </p><p><span m=''1113190''>PROFESSOR: Say</span> <span m=''1113480''>your</span>
  <span m=''1113740''>name.</span> </p><p><span m=''1114250''>AUDIENCE: Your</span>
  <span m=''1114530''>name.</span> </p><p><span m=''1115160''>PROFESSOR: Louder.</span>
  </p><p><span m=''1115910''>AUDIENCE: Your</span> <span m=''1116140''>name.</span>
  </p><p><span m=''1116960''>PROFESSOR: OK.</span> <span m=''1119100''>What I''m</span>
  <span m=''1119480''>showing</span> <span m=''1119770''>you</span> <span m=''1119900''>here</span>
  <span m=''1120700''>is</span> <span m=''1121110''>that</span> <span m=''1121560''>the</span>
  <span m=''1121650''>words</span> <span m=''1122040''>of</span> <span m=''1122150''>English</span>
  <span m=''1123780''>are</span> <span m=''1123950''>ambiguous.</span> <span m=''1125520''>I</span>
  <span m=''1125730''>was</span> <span m=''1125940''>saying,</span> <span m=''1126510''>say</span>
  <span m=''1128230''>your</span> <span m=''1129870''>name.</span> <span m=''1132220''>I</span>
  <span m=''1132330''>was</span> <span m=''1132440''>also</span> <span m=''1132780''>possibly</span>
  <span m=''1133270''>saying</span> <span m=''1134410''>say,</span> <span m=''1136300''>your</span>
  <span m=''1136580''>name.</span> <span m=''1140710''>But</span> <span m=''1141090''>that</span>
  <span m=''1141260''>cannot</span> <span m=''1141500''>be</span> <span m=''1141590''>distinguished</span>
  <span m=''1142310''>in</span> <span m=''1142460''>speech.</span> <span m=''1144100''>However,</span>
  <span m=''1144350''>we</span> <span m=''1144480''>do</span> <span m=''1144650''>have</span>
  <span m=''1144730''>a</span> <span m=''1144820''>notation</span> <span m=''1146860''>in</span>
  <span m=''1147420''>writing,</span> <span m=''1148230''>which</span> <span m=''1148430''>is</span>
  <span m=''1148540''>quotation</span> <span m=''1149600''>for</span> <span m=''1149790''>distinguishing</span>
  <span m=''1151200''>these</span> <span m=''1151480''>two</span> <span m=''1151620''>possible</span>
  <span m=''1152020''>meanings.</span> </p><p><span m=''1154180''>In</span> <span
  m=''1154370''>particular,</span> <span m=''1154920''>over</span> <span m=''1155110''>here,</span>
  <span m=''1156720''>in</span> <span m=''1156880''>Lisp</span> <span m=''1157300''>we</span>
  <span m=''1157440''>have</span> <span m=''1157590''>a</span> <span m=''1157630''>notation</span>
  <span m=''1159350''>for</span> <span m=''1159490''>distinguishing</span> <span m=''1159990''>these</span>
  <span m=''1160180''>meetings.</span> <span m=''1161510''>If</span> <span m=''1161670''>I</span>
  <span m=''1161780''>were to</span> <span m=''1161940''>just</span> <span m=''1162090''>write</span>
  <span m=''1162240''>a</span> <span m=''1162300''>plus</span> <span m=''1162680''>here,</span>
  <span m=''1163610''>a</span> <span m=''1163700''>plus</span> <span m=''1163980''>symbol,</span>
  <span m=''1164760''>I would be</span> <span m=''1165110''>asking,</span> <span m=''1165690''>is</span>
  <span m=''1166030''>the</span> <span m=''1166720''>first</span> <span m=''1167060''>element</span>
  <span m=''1167460''>of</span> <span m=''1167590''>the</span> <span m=''1167710''>expression,</span>
  <span m=''1169270''>is</span> <span m=''1169400''>the</span> <span m=''1169510''>operator</span>
  <span m=''1169950''>position</span> <span m=''1170370''>of</span> <span m=''1170490''>the</span>
  <span m=''1170590''>expression,</span> <span m=''1172220''>the</span> <span m=''1172480''>addition</span>
  <span m=''1172860''>operator?</span> <span m=''1174760''>I</span> <span m=''1174950''>don''t</span>
  <span m=''1175180''>know.</span> <span m=''1176330''>I</span> <span m=''1176420''>would</span>
  <span m=''1176560''>have</span> <span m=''1176690''>to have</span> <span m=''1176810''>written
  the</span> <span m=''1177130''>addition</span> <span m=''1177450''>operator</span>
  <span m=''1177860''>there,</span> <span m=''1179550''>which</span> <span m=''1179710''>I</span>
  <span m=''1179780''>can''t</span> <span m=''1180040''>write.</span> <span m=''1181330''>However,</span>
  <span m=''1181820''>this</span> <span m=''1182040''>way</span> <span m=''1182180''>I''m</span>
  <span m=''1182310''>asking,</span> <span m=''1182890''>is</span> <span m=''1183130''>this</span>
  <span m=''1183320''>the</span> <span m=''1183430''>symbolic</span> <span m=''1184620''>object</span>
  <span m=''1185470''>plus,</span> <span m=''1186080''>which</span> <span m=''1186390''>normally</span>
  <span m=''1186750''>stands</span> <span m=''1187130''>for</span> <span m=''1187220''>the</span>
  <span m=''1187360''>addition</span> <span m=''1187670''>operator?</span> <span m=''1189790''>That''s</span>
  <span m=''1190030''>what</span> <span m=''1190120''>I</span> <span m=''1190270''>want.</span>
  <span m=''1190420''>That''s</span> <span m=''1190590''>the</span> <span m=''1190670''>question</span>
  <span m=''1190950''>I</span> <span m=''1191090''>want</span> <span m=''1191230''>to</span>
  <span m=''1191340''>ask.</span> <span m=''1193110''>Now</span> <span m=''1193320''>before</span>
  <span m=''1193630''>I</span> <span m=''1193700''>go</span> <span m=''1193840''>any</span>
  <span m=''1193990''>further,</span> <span m=''1194520''>I</span> <span m=''1194650''>want</span>
  <span m=''1194770''>to</span> <span m=''1194880''>point</span> <span m=''1195150''>out</span>
  <span m=''1195330''>the</span> <span m=''1195430''>quotation</span> <span m=''1196240''>is</span>
  <span m=''1196420''>a</span> <span m=''1196490''>very</span> <span m=''1196890''>complex</span>
  <span m=''1197360''>concept,</span> <span m=''1199050''>and</span> <span m=''1199260''>adding</span>
  <span m=''1199550''>it</span> <span m=''1199630''>to</span> <span m=''1199710''>a</span>
  <span m=''1199780''>language</span> <span m=''1200055''>causes</span> <span m=''1200740''>a</span>
  <span m=''1200820''>great</span> <span m=''1201100''>deal</span> <span m=''1201290''>of</span>
  <span m=''1201370''>troubles.</span> </p><p><span m=''1203510''>Consider</span>
  <span m=''1204170''>the</span> <span m=''1204300''>next</span> <span m=''1204600''>slide.</span>
  <span m=''1206370''>Here''s</span> <span m=''1207710''>a</span> <span m=''1207780''>deduction</span>
  <span m=''1208350''>which</span> <span m=''1208510''>we</span> <span m=''1208610''>should</span>
  <span m=''1208730''>all</span> <span m=''1208890''>agree</span> <span m=''1209120''>with.</span>
  <span m=''1211830''>We</span> <span m=''1211930''>have,</span> <span m=''1212600''>Alyssa</span>
  <span m=''1213050''>is</span> <span m=''1213210''>smart</span> <span m=''1214910''>and</span>
  <span m=''1215360''>Alyssa</span> <span m=''1215900''>is</span> <span m=''1216080''>George''s</span>
  <span m=''1216460''>mother.</span> <span m=''1217530''>This</span> <span m=''1217760''>is</span>
  <span m=''1217830''>an</span> <span m=''1217950''>equality,</span> <span m=''1220010''>is.</span>
  <span m=''1222350''>From</span> <span m=''1222700''>those</span> <span m=''1222960''>two,</span>
  <span m=''1223130''>we</span> <span m=''1223530''>can</span> <span m=''1223610''>deduce</span>
  <span m=''1224590''>that</span> <span m=''1224890''>George''s</span> <span m=''1225310''>mother</span>
  <span m=''1225670''>is</span> <span m=''1225810''>smart.</span> <span m=''1227470''>Because</span>
  <span m=''1227850''>we</span> <span m=''1227950''>can</span> <span m=''1228040''>always</span>
  <span m=''1228340''>substitute</span> <span m=''1229130''>equals</span> <span m=''1229480''>for</span>
  <span m=''1229710''>equals</span> <span m=''1232320''>in</span> <span m=''1232460''>expressions.</span>
  <span m=''1234250''>Or</span> <span m=''1234470''>can</span> <span m=''1234780''>we?</span>
  </p><p><span m=''1236420''>Here''s</span> <span m=''1236860''>a</span> <span m=''1236900''>case</span>
  <span m=''1237490''>where</span> <span m=''1237630''>we</span> <span m=''1237830''>have</span>
  <span m=''1238160''>"Chicago"</span> <span m=''1239330''>has</span> <span m=''1239550''>seven</span>
  <span m=''1239840''>letters.</span> <span m=''1241400''>The</span> <span m=''1241580''>quotation</span>
  <span m=''1242220''>means that</span> <span m=''1242710''>I''m</span> <span m=''1243010''>discussing</span>
  <span m=''1243580''>the</span> <span m=''1243660''>word</span> <span m=''1244010''>Chicago,</span>
  <span m=''1245100''>not</span> <span m=''1245400''>what</span> <span m=''1245550''>the</span>
  <span m=''1245630''>word</span> <span m=''1245960''>represents.</span> <span m=''1249940''>Here</span>
  <span m=''1250220''>I</span> <span m=''1250280''>have</span> <span m=''1250650''>that</span>
  <span m=''1250860''>Chicago</span> <span m=''1251290''>is</span> <span m=''1251380''>the</span>
  <span m=''1251470''>biggest</span> <span m=''1251760''>city</span> <span m=''1252010''>in</span>
  <span m=''1252110''>Illinois.</span> <span m=''1254830''>As</span> <span m=''1254990''>a</span>
  <span m=''1255040''>consequence</span> <span m=''1255570''>of</span> <span m=''1255660''>this,</span>
  <span m=''1255840''>I</span> <span m=''1255950''>would</span> <span m=''1256090''>like</span>
  <span m=''1256270''>to</span> <span m=''1256360''>deduce</span> <span m=''1256900''>that</span>
  <span m=''1257080''>the</span> <span m=''1257160''>biggest</span> <span m=''1257500''>city</span>
  <span m=''1257700''>in</span> <span m=''1257790''>Illinois</span> <span m=''1258220''>has</span>
  <span m=''1258370''>seven</span> <span m=''1258650''>letters.</span> <span m=''1259250''>But</span>
  <span m=''1259550''>that''s</span> <span m=''1259780''>manifestly</span> <span m=''1260460''>false.</span>
  <span m=''1265480''>Wow,</span> <span m=''1266680''>it</span> <span m=''1266850''>works.</span>
  </p><p><span m=''1269420''>OK,</span> <span m=''1270250''>so</span> <span m=''1270650''>once</span>
  <span m=''1270950''>we</span> <span m=''1271110''>have</span> <span m=''1271350''>things</span>
  <span m=''1271580''>like</span> <span m=''1271840''>that,</span> <span m=''1272510''>our</span>
  <span m=''1272810''>language</span> <span m=''1273210''>gets</span> <span m=''1273420''>much</span>
  <span m=''1273640''>more</span> <span m=''1273800''>complicated.</span> <span m=''1274540''>Because</span>
  <span m=''1274990''>it''s no</span> <span m=''1275140''>longer</span> <span m=''1275450''>true</span>
  <span m=''1276100''>that</span> <span m=''1276410''>things</span> <span m=''1276640''>we</span>
  <span m=''1276780''>tend</span> <span m=''1277030''>to</span> <span m=''1277110''>like</span>
  <span m=''1277350''>to</span> <span m=''1277440''>do</span> <span m=''1277660''>with</span>
  <span m=''1277800''>languages,</span> <span m=''1278520''>like</span> <span m=''1278680''>substituting</span>
  <span m=''1279090''>equals</span> <span m=''1279390''>for equals</span> <span m=''1279750''>and</span>
  <span m=''1279850''>getting</span> <span m=''1280070''>right</span> <span m=''1280250''>answers,</span>
  <span m=''1281480''>are</span> <span m=''1281580''>going</span> <span m=''1281670''>to</span>
  <span m=''1281770''>work</span> <span m=''1282380''>without</span> <span m=''1282670''>being</span>
  <span m=''1282840''>very</span> <span m=''1283050''>careful.</span> <span m=''1284550''>We</span>
  <span m=''1284680''>can''t</span> <span m=''1285000''>substitute</span> <span m=''1285340''>into</span>
  <span m=''1285590''>what''s</span> <span m=''1285800''>called</span> <span m=''1285990''>referentially</span>
  <span m=''1286470''>opaque</span> <span m=''1286780''>contexts,</span> <span m=''1287805''>of</span>
  <span m=''1288080''>which</span> <span m=''1288760''>a</span> <span m=''1288890''>quotation</span>
  <span m=''1289650''>is</span> <span m=''1289780''>the</span> <span m=''1289860''>prototypical</span>
  <span m=''1290410''>type</span> <span m=''1291270''>of</span> <span m=''1291450''>referentially</span>
  <span m=''1291930''>opaque</span> <span m=''1292240''>context.</span> <span m=''1293380''>If</span>
  <span m=''1293480''>you</span> <span m=''1293580''>know</span> <span m=''1293730''>what
  that</span> <span m=''1293960''>means,</span> <span m=''1294340''>you can</span>
  <span m=''1294410''>consult</span> <span m=''1294720''>a</span> <span m=''1294760''>philosopher.</span>
  <span m=''1295560''>Presumably</span> <span m=''1296020''>there</span> <span m=''1296190''>is</span>
  <span m=''1296290''>one in the</span> <span m=''1296540''>room.</span> </p><p><span
  m=''1298790''>In</span> <span m=''1298920''>any</span> <span m=''1299120''>case,</span>
  <span m=''1300440''>let''s</span> <span m=''1300650''>continue</span> <span m=''1301090''>now,</span>
  <span m=''1301300''>now</span> <span m=''1301530''>that</span> <span m=''1301680''>we</span>
  <span m=''1301930''>at</span> <span m=''1302080''>least</span> <span m=''1302220''>have
  an</span> <span m=''1302340''>operational</span> <span m=''1302920''>understanding</span>
  <span m=''1303560''>of</span> <span m=''1303680''>a</span> <span m=''1303750''>2000-year-old</span>
  <span m=''1304550''>issue</span> <span m=''1305360''>that</span> <span m=''1305660''>has</span>
  <span m=''1305770''>to do with</span> <span m=''1306180''>name,</span> <span m=''1306500''>and</span>
  <span m=''1306600''>mention,</span> <span m=''1307000''>and all</span> <span m=''1307250''>sorts
  of</span> <span m=''1307350''>things</span> <span m=''1307560''>like</span> <span
  m=''1307760''>that.</span> <span m=''1312440''>I</span> <span m=''1312550''>have</span>
  <span m=''1312630''>to</span> <span m=''1312720''>define</span> <span m=''1313100''>what</span>
  <span m=''1313250''>I</span> <span m=''1313310''>mean,</span> <span m=''1313690''>how</span>
  <span m=''1313850''>to</span> <span m=''1313930''>make</span> <span m=''1314140''>a</span>
  <span m=''1314310''>sum</span> <span m=''1319160''>of</span> <span m=''1319480''>two</span>
  <span m=''1319790''>things,</span> <span m=''1320170''>an</span> <span m=''1320250''>a1</span>
  <span m=''1320680''>and</span> <span m=''1320830''>a2.</span> <span m=''1322250''>And
  I''m</span> <span m=''1322650''>going</span> <span m=''1322790''>to do this</span>
  <span m=''1323010''>very</span> <span m=''1323230''>simply.</span> <span m=''1323590''>It''s</span>
  <span m=''1323780''>a</span> <span m=''1323840''>list</span> <span m=''1327764''>of</span>
  <span m=''1328260''>the</span> <span m=''1328590''>symbol</span> <span m=''1329030''>plus,</span>
  <span m=''1329830''>and</span> <span m=''1330130''>a1,</span> <span m=''1331050''>and</span>
  <span m=''1331290''>a2.</span> <span m=''1333600''>And</span> <span m=''1334020''>I</span>
  <span m=''1334280''>can</span> <span m=''1334670''>determine</span> <span m=''1335910''>the</span>
  <span m=''1336460''>first</span> <span m=''1336740''>element.</span> <span m=''1341600''>Define</span>
  <span m=''1342370''>a1</span> <span m=''1343960''>to</span> <span m=''1344110''>be</span>
  <span m=''1344650''>cadr.</span> <span m=''1354150''>I''ve</span> <span m=''1354270''>just</span>
  <span m=''1354510''>introduced</span> <span m=''1354930''>another</span> <span m=''1355310''>primitive.</span>
  <span m=''1356370''>This</span> <span m=''1356590''>is</span> <span m=''1356810''>the</span>
  <span m=''1356960''>car</span> <span m=''1357610''>of</span> <span m=''1357810''>the</span>
  <span m=''1357920''>cdr</span> <span m=''1358390''>of</span> <span m=''1358560''>something.</span>
  </p><p><span m=''1359990''>You</span> <span m=''1360110''>might</span> <span m=''1360310''>want</span>
  <span m=''1360400''>to</span> <span m=''1360500''>know</span> <span m=''1360710''>why</span>
  <span m=''1361040''>car</span> <span m=''1361500''>and</span> <span m=''1361570''>cdr</span>
  <span m=''1361750''>are</span> <span m=''1362220''>names</span> <span m=''1363580''>of</span>
  <span m=''1363770''>these</span> <span m=''1363950''>primitives,</span> <span m=''1364680''>and</span>
  <span m=''1364940''>why</span> <span m=''1365470''>they''ve</span> <span m=''1365780''>survived,</span>
  <span m=''1366320''>even</span> <span m=''1366470''>though</span> <span m=''1366580''>they''re</span>
  <span m=''1366720''>much</span> <span m=''1366920''>better</span> <span m=''1367170''>ideas</span>
  <span m=''1367500''>like</span> <span m=''1367700''>left</span> <span m=''1367920''>and</span>
  <span m=''1368000''>right.</span> <span m=''1368970''>We</span> <span m=''1369040''>could
  have</span> <span m=''1369240''>called</span> <span m=''1369420''>them</span> <span
  m=''1369530''>things</span> <span m=''1369750''>like</span> <span m=''1369940''>that.</span>
  <span m=''1371380''>Well,</span> <span m=''1371490''>first</span> <span m=''1371760''>of</span>
  <span m=''1371860''>all,</span> <span m=''1372570''>the</span> <span m=''1372810''>names</span>
  <span m=''1373120''>come</span> <span m=''1373290''>from</span> <span m=''1373420''>the</span>
  <span m=''1373510''>fact</span> <span m=''1373970''>that</span> <span m=''1374093''>in</span>
  <span m=''1374216''>the</span> <span m=''1374340''>great</span> <span m=''1374620''>past,</span>
  <span m=''1375060''>when</span> <span m=''1375230''>Lisp</span> <span m=''1375410''>was</span>
  <span m=''1375510''>invented,</span> <span m=''1376440''>I</span> <span m=''1376580''>suppose</span>
  <span m=''1376810''>in</span> <span m=''1376920''>''58</span> <span m=''1377370''>or</span>
  <span m=''1377470''>something,</span> <span m=''1377785''>it</span> <span m=''1378100''>was</span>
  <span m=''1378290''>on</span> <span m=''1378430''>a</span> <span m=''1378480''>704</span>
  <span m=''1380210''>or</span> <span m=''1380320''>something</span> <span m=''1380525''>like</span>
  <span m=''1380730''>that,</span> <span m=''1380880''>which</span> <span m=''1381030''>had</span>
  <span m=''1381220''>a</span> <span m=''1381260''>machine.</span> <span m=''1381870''>It
  was</span> <span m=''1382030''>a</span> <span m=''1382070''>machine</span> <span
  m=''1382410''>that</span> <span m=''1383230''>had</span> <span m=''1383480''>an</span>
  <span m=''1383600''>address</span> <span m=''1383920''>register</span> <span m=''1384360''>and
  a</span> <span m=''1384440''>decrement</span> <span m=''1384890''>register.</span>
  <span m=''1385340''>And</span> <span m=''1385630''>these</span> <span m=''1385860''>were</span>
  <span m=''1385900''>the</span> <span m=''1386000''>contents</span> <span m=''1386400''>of</span>
  <span m=''1386470''>the</span> <span m=''1386580''>address</span> <span m=''1386910''>register</span>
  <span m=''1387370''>and</span> <span m=''1387420''>the decrement</span> <span m=''1387800''>register.</span>
  <span m=''1388270''>So it''s an</span> <span m=''1388500''>historical</span> <span
  m=''1389050''>accident.</span> </p><p><span m=''1389880''>Now</span> <span m=''1390100''>why</span>
  <span m=''1390310''>have</span> <span m=''1390370''>these</span> <span m=''1390570''>names</span>
  <span m=''1390770''>survived?</span> <span m=''1391880''>It''s</span> <span m=''1392050''>because</span>
  <span m=''1392540''>Lisp</span> <span m=''1392790''>programmers</span> <span m=''1393320''>like</span>
  <span m=''1393480''>to</span> <span m=''1393550''>talk</span> <span m=''1393750''>to</span>
  <span m=''1393810''>each</span> <span m=''1393900''>other</span> <span m=''1394110''>over</span>
  <span m=''1394240''>the</span> <span m=''1394380''>phone.</span> <span m=''1395900''>And</span>
  <span m=''1396020''>if</span> <span m=''1396120''>you</span> <span m=''1396230''>want</span>
  <span m=''1396320''>to</span> <span m=''1396400''>have</span> <span m=''1396490''>a</span>
  <span m=''1396590''>long</span> <span m=''1396910''>sequence</span> <span m=''1397340''>of</span>
  <span m=''1397420''>cars</span> <span m=''1397670''>and</span> <span m=''1397770''>cdrs</span>
  <span m=''1398380''>you</span> <span m=''1398460''>might</span> <span m=''1398660''>say,</span>
  <span m=''1398970''>cdaddedr,</span> <span m=''1401380''>which</span> <span m=''1401580''>can</span>
  <span m=''1401700''>be</span> <span m=''1401810''>understood.</span> <span m=''1402530''>But</span>
  <span m=''1402710''>left</span> <span m=''1402900''>of</span> <span m=''1403010''>right</span>
  <span m=''1403200''>or</span> <span m=''1403270''>right</span> <span m=''1403460''>of</span>
  <span m=''1403490''>left</span> <span m=''1403800''>is</span> <span m=''1403890''>not</span>
  <span m=''1404070''>so</span> <span m=''1404200''>clear</span> <span m=''1406160''>if</span>
  <span m=''1406240''>you</span> <span m=''1406330''>get</span> <span m=''1406490''>good</span>
  <span m=''1406650''>at</span> <span m=''1406800''>it.</span> <span m=''1406970''>So</span>
  <span m=''1407470''>that''s</span> <span m=''1408970''>why</span> <span m=''1409130''>we</span>
  <span m=''1409270''>have</span> <span m=''1409400''>these</span> <span m=''1409570''>words.</span>
  <span m=''1410570''>All</span> <span m=''1410900''>of them</span> <span m=''1411070''>up</span>
  <span m=''1411230''>to four</span> <span m=''1411470''>deep</span> <span m=''1411880''>are</span>
  <span m=''1412135''>defined</span> <span m=''1412910''>typically</span> <span m=''1413340''>in
  a Lisp</span> <span m=''1413680''>system.</span> <span m=''1418270''>A2</span> <span
  m=''1419540''>to</span> <span m=''1420230''>be--</span> <span m=''1423540''>and,</span>
  <span m=''1423690''>of</span> <span m=''1423850''>course,</span> <span m=''1424010''>you</span>
  <span m=''1424130''>can</span> <span m=''1424290''>see</span> <span m=''1424720''>that</span>
  <span m=''1425230''>if</span> <span m=''1425410''>I</span> <span m=''1425500''>looked</span>
  <span m=''1425790''>at</span> <span m=''1425950''>one</span> <span m=''1426100''>of</span>
  <span m=''1426170''>these</span> <span m=''1426350''>expressions</span> <span m=''1427490''>like</span>
  <span m=''1428060''>the</span> <span m=''1429140''>sum</span> <span m=''1430280''>of</span>
  <span m=''1430780''>3</span> <span m=''1431200''>and</span> <span m=''1431440''>5,</span>
  <span m=''1432810''>what</span> <span m=''1433000''>that</span> <span m=''1433230''>is</span>
  <span m=''1434100''>is</span> <span m=''1434480''>a</span> <span m=''1434630''>list</span>
  <span m=''1434950''>containing</span> <span m=''1436220''>the</span> <span m=''1436570''>symbol</span>
  <span m=''1437760''>plus,</span> <span m=''1439220''>and</span> <span m=''1441860''>a</span>
  <span m=''1442080''>number</span> <span m=''1443590''>3,</span> <span m=''1446100''>and</span>
  <span m=''1446840''>a</span> <span m=''1447180''>number</span> <span m=''1449820''>5.</span>
  <span m=''1451470''>Then</span> <span m=''1452950''>the</span> <span m=''1453230''>car</span>
  <span m=''1454090''>is</span> <span m=''1454300''>the</span> <span m=''1454400''>symbol</span>
  <span m=''1454660''>plus.</span> <span m=''1456100''>The</span> <span m=''1456740''>car</span>
  <span m=''1457400''>of</span> <span m=''1457540''>the</span> <span m=''1457630''>cdr.</span>
  <span m=''1458320''>Well</span> <span m=''1458560''>I</span> <span m=''1458670''>take
  the</span> <span m=''1458740''>cdr</span> <span m=''1459060''>and</span> <span m=''1459210''>then
  I</span> <span m=''1459370''>take</span> <span m=''1459580''>the</span> <span m=''1459670''>car.</span>
  <span m=''1460070''>And</span> <span m=''1460170''>that''s</span> <span m=''1460250''>how</span>
  <span m=''1460440''>I</span> <span m=''1460530''>get</span> <span m=''1460600''>to
  the</span> <span m=''1460720''>3.</span> <span m=''1461200''>That''s</span> <span
  m=''1461310''>the</span> <span m=''1461410''>first</span> <span m=''1461670''>argument.</span>
  <span m=''1462630''>And</span> <span m=''1462850''>the</span> <span m=''1462920''>car</span>
  <span m=''1463170''>of</span> <span m=''1463240''>the</span> <span m=''1463320''>cdr</span>
  <span m=''1463590''>of</span> <span m=''1463660''>the</span> <span m=''1463730''>cdr</span>
  <span m=''1463930''>gets</span> <span m=''1464150''>me</span> <span m=''1464270''>to</span>
  <span m=''1464370''>this</span> <span m=''1464570''>one,</span> <span m=''1465160''>the</span>
  <span m=''1465270''>5.</span> </p><p><span m=''1468860''>And</span> <span m=''1469080''>similarly,</span>
  <span m=''1470480''>of</span> <span m=''1470800''>course,</span> <span m=''1471380''>I</span>
  <span m=''1471510''>can</span> <span m=''1471660''>define</span> <span m=''1472460''>what''s</span>
  <span m=''1472660''>going</span> <span m=''1472860''>on</span> <span m=''1472970''>with</span>
  <span m=''1473090''>products.</span> <span m=''1475300''>Let''s do</span> <span
  m=''1475520''>that</span> <span m=''1475720''>very</span> <span m=''1475960''>quickly.</span>
  <span m=''1488760''>Is</span> <span m=''1489145''>the</span> <span m=''1489530''>expression</span>
  <span m=''1490010''>a</span> <span m=''1490070''>product?</span> <span m=''1491130''>Yes</span>
  <span m=''1491630''>if</span> <span m=''1491910''>and</span> <span m=''1492970''>if</span>
  <span m=''1493120''>it''s</span> <span m=''1493240''>true,</span> <span m=''1493650''>that''s</span>
  <span m=''1494010''>it''s not</span> <span m=''1494200''>atomic</span> <span m=''1501430''>and</span>
  <span m=''1501910''>it''s</span> <span m=''1502160''>EQ</span> <span m=''1508920''>quote,</span>
  <span m=''1509750''>the</span> <span m=''1509970''>asterisk</span> <span m=''1510910''>symbol,</span>
  <span m=''1511830''>which</span> <span m=''1512010''>is</span> <span m=''1512130''>the</span>
  <span m=''1512710''>operator</span> <span m=''1513260''>for</span> <span m=''1513430''>multiplication.</span>
  </p><p><span m=''1515800''>Make</span> <span m=''1516670''>product</span> <span
  m=''1528500''>of</span> <span m=''1528680''>an</span> <span m=''1528780''>M1</span>
  <span m=''1529430''>and</span> <span m=''1529590''>an</span> <span m=''1529700''>M2</span>
  <span m=''1531145''>to</span> <span m=''1531450''>be</span> <span m=''1531650''>list,</span>
  <span m=''1534032''>quote,</span> <span m=''1534860''>the</span> <span m=''1535090''>asterisk</span>
  <span m=''1535650''>operation</span> <span m=''1536660''>and</span> <span m=''1537310''>M1</span>
  <span m=''1538380''>and</span> <span m=''1538720''>M2.</span> <span m=''1540930''>and
  I</span> <span m=''1541240''>define</span> <span m=''1545440''>M1</span> <span m=''1546250''>to</span>
  <span m=''1546350''>be</span> <span m=''1546540''>cadr</span> <span m=''1549140''>and</span>
  <span m=''1549500''>M2</span> <span m=''1555450''>to</span> <span m=''1555930''>be</span>
  <span m=''1556280''>caddr.</span> <span m=''1560280''>You</span> <span m=''1560450''>get
  to</span> <span m=''1560540''>be a good</span> <span m=''1560710''>Lisp</span> <span
  m=''1560890''>programmer</span> <span m=''1561190''>because</span> <span m=''1561260''>you</span>
  <span m=''1561330''>start</span> <span m=''1561550''>talking</span> <span m=''1561830''>that</span>
  <span m=''1562000''>way.</span> <span m=''1562690''>I</span> <span m=''1562860''>cdr</span>
  <span m=''1563200''>down lists</span> <span m=''1563380''>and</span> <span m=''1563650''>console</span>
  <span m=''1563920''>them up</span> <span m=''1565020''>and</span> <span m=''1565200''>so</span>
  <span m=''1565390''>on.</span> </p><p><span m=''1566430''>Now,</span> <span m=''1567075''>now</span>
  <span m=''1567350''>that</span> <span m=''1567800''>we</span> <span m=''1567970''>have</span>
  <span m=''1568150''>essentially a</span> <span m=''1568600''>complete</span> <span
  m=''1569030''>program</span> <span m=''1569480''>for</span> <span m=''1569570''>finding</span>
  <span m=''1569850''>derivatives,</span> <span m=''1570330''>you</span> <span m=''1570440''>can</span>
  <span m=''1570540''>add</span> <span m=''1570710''>more</span> <span m=''1570880''>rules</span>
  <span m=''1571100''>if</span> <span m=''1571210''>you</span> <span m=''1571320''>like.</span>
  <span m=''1572360''>What</span> <span m=''1572520''>kind</span> <span m=''1572670''>of</span>
  <span m=''1572720''>behavior</span> <span m=''1573140''>do</span> <span m=''1573220''>we</span>
  <span m=''1573310''>get</span> <span m=''1573480''>out</span> <span m=''1573600''>of</span>
  <span m=''1573720''>it?</span> <span m=''1574800''>I''ll</span> <span m=''1575040''>have</span>
  <span m=''1575190''>to</span> <span m=''1575310''>clear</span> <span m=''1575600''>that</span>
  <span m=''1576250''>x.</span> <span m=''1577930''>Well,</span> <span m=''1578110''>supposing</span>
  <span m=''1578460''>I</span> <span m=''1578560''>define</span> <span m=''1580030''>foo</span>
  <span m=''1580370''>here</span> <span m=''1584280''>to</span> <span m=''1584870''>be</span>
  <span m=''1585380''>the</span> <span m=''1586390''>sum</span> <span m=''1587030''>of</span>
  <span m=''1587830''>the</span> <span m=''1588060''>product</span> <span m=''1588470''>of</span>
  <span m=''1588540''>ax</span> <span m=''1588880''>square</span> <span m=''1589240''>and</span>
  <span m=''1589350''>bx</span> <span m=''1589470''>plus</span> <span m=''1589880''>c.</span>
  <span m=''1590450''>That''s</span> <span m=''1590970''>the</span> <span m=''1591090''>same</span>
  <span m=''1591350''>thing</span> <span m=''1591500''>we</span> <span m=''1591620''>see</span>
  <span m=''1591820''>here</span> <span m=''1592080''>as</span> <span m=''1593090''>the</span>
  <span m=''1593580''>algebraic</span> <span m=''1594020''>expression</span> <span
  m=''1594330''>written</span> <span m=''1594520''>in</span> <span m=''1594600''>the</span>
  <span m=''1594630''>more</span> <span m=''1594770''>conventional</span> <span m=''1595260''>notation</span>
  <span m=''1595820''>over</span> <span m=''1595990''>there.</span> </p><p><span m=''1597860''>Well,</span>
  <span m=''1598160''>the derivative</span> <span m=''1598600''>of</span> <span m=''1598760''>foo</span>
  <span m=''1599180''>with</span> <span m=''1599320''>respect</span> <span m=''1599760''>to
  x,</span> <span m=''1600360''>which</span> <span m=''1600510''>we</span> <span m=''1600620''>can</span>
  <span m=''1600750''>see</span> <span m=''1600920''>over</span> <span m=''1601130''>here,</span>
  <span m=''1603560''>is</span> <span m=''1603710''>this</span> <span m=''1603900''>horrible,</span>
  <span m=''1604420''>horrendous</span> <span m=''1604870''>mess.</span> <span m=''1606250''>I</span>
  <span m=''1606370''>would</span> <span m=''1606520''>like</span> <span m=''1606780''>it</span>
  <span m=''1606880''>to</span> <span m=''1606970''>be</span> <span m=''1607880''>2ax</span>
  <span m=''1608490''>plus</span> <span m=''1608810''>b.</span> <span m=''1610760''>But</span>
  <span m=''1610910''>it''s</span> <span m=''1611130''>not.</span> <span m=''1612240''>It''s</span>
  <span m=''1612650''>equivalent</span> <span m=''1613090''>to</span> <span m=''1613250''>it.</span>
  <span m=''1614620''>What</span> <span m=''1614820''>is</span> <span m=''1614970''>it?</span>
  <span m=''1616090''>I</span> <span m=''1616300''>have</span> <span m=''1616500''>here,</span>
  <span m=''1619330''>what do</span> <span m=''1619540''>I</span> <span m=''1619770''>have?</span>
  <span m=''1620510''>I</span> <span m=''1620730''>have</span> <span m=''1621540''>the</span>
  <span m=''1621800''>derivative</span> <span m=''1622510''>of</span> <span m=''1622650''>the</span>
  <span m=''1622790''>product</span> <span m=''1623290''>of</span> <span m=''1623550''>x</span>
  <span m=''1623840''>and</span> <span m=''1624195''>x.</span> <span m=''1624550''>Over</span>
  <span m=''1624950''>here</span> <span m=''1626530''>is,</span> <span m=''1627310''>of</span>
  <span m=''1627460''>course,</span> <span m=''1627950''>the</span> <span m=''1628090''>sum</span>
  <span m=''1628760''>of</span> <span m=''1628900''>x</span> <span m=''1629130''>times</span>
  <span m=''1629410''>1</span> <span m=''1629630''>and</span> <span m=''1629720''>1</span>
  <span m=''1629950''>times</span> <span m=''1630200''>x.</span> </p><p><span m=''1632830''>Now,</span>
  <span m=''1633130''>well,</span> <span m=''1633330''>it''s the</span> <span m=''1633390''>first</span>
  <span m=''1633570''>times</span> <span m=''1633740''>the derivative</span> <span
  m=''1633920''>of the</span> <span m=''1634100''>second</span> <span m=''1634280''>plus
  the</span> <span m=''1634500''>second</span> <span m=''1634720''>times</span> <span
  m=''1634980''>the</span> <span m=''1635170''>derivative of the first. It''s</span>
  <span m=''1635370''>right.</span> <span m=''1637780''>That''s</span> <span m=''1638400''>2x</span>
  <span m=''1638810''>of</span> <span m=''1638890''>course.</span> <span m=''1640220''>a</span>
  <span m=''1640460''>times</span> <span m=''1640770''>2x</span> <span m=''1641220''>is</span>
  <span m=''1641400''>2ax</span> <span m=''1642260''>plus</span> <span m=''1642570''>0X</span>
  <span m=''1643090''>square</span> <span m=''1643270''>doesn''t</span> <span m=''1643530''>count</span>
  <span m=''1644280''>plus</span> <span m=''1645590''>B</span> <span m=''1646600''>over</span>
  <span m=''1646820''>here</span> <span m=''1647360''>plus</span> <span m=''1647580''>a</span>
  <span m=''1647630''>bunch</span> <span m=''1647830''>of</span> <span m=''1647910''>0''s.</span>
  <span m=''1649100''>Well</span> <span m=''1649330''>the</span> <span m=''1649640''>answer
  is</span> <span m=''1649850''>right.</span> <span m=''1650130''>But</span> <span
  m=''1650210''>I</span> <span m=''1650290''>give</span> <span m=''1650510''>people</span>
  <span m=''1650780''>take</span> <span m=''1650970''>off</span> <span m=''1651290''>points</span>
  <span m=''1651610''>on an</span> <span m=''1651840''>exam</span> <span m=''1652180''>for</span>
  <span m=''1652300''>that,</span> <span m=''1654390''>sadly</span> <span m=''1654860''>enough.</span>
  <span m=''1655690''>Let''s</span> <span m=''1655890''>worry</span> <span m=''1656090''>about</span>
  <span m=''1656370''>that</span> <span m=''1656580''>in</span> <span m=''1656620''>the</span>
  <span m=''1656770''>next</span> <span m=''1656910''>segment.</span> <span m=''1657830''>Are</span>
  <span m=''1657940''>there</span> <span m=''1658080''>any</span> <span m=''1658210''>questions?</span>
  <span m=''1662970''>Yes?</span> </p><p><span m=''1664070''>AUDIENCE: If</span> <span
  m=''1664310''>you</span> <span m=''1664460''>had</span> <span m=''1664680''>left</span>
  <span m=''1664950''>the</span> <span m=''1665050''>quote</span> <span m=''1665690''>when</span>
  <span m=''1665880''>you</span> <span m=''1665970''>put</span> <span m=''1666210''>the</span>
  <span m=''1666300''>plus,</span> <span m=''1666790''>then</span> <span m=''1667300''>would</span>
  <span m=''1667490''>that</span> <span m=''1667740''>be</span> <span m=''1667920''>referring</span>
  <span m=''1668600''>to</span> <span m=''1669160''>the</span> <span m=''1669780''>procedure</span>
  <span m=''1670480''>plus</span> <span m=''1670950''>and</span> <span m=''1671120''>could</span>
  <span m=''1671310''>you</span> <span m=''1671410''>do</span> <span m=''1671720''>a</span>
  <span m=''1671800''>comparison</span> <span m=''1672350''>between</span> <span m=''1672720''>that</span>
  <span m=''1672920''>procedure</span> <span m=''1673380''>and</span> <span m=''1673560''>some</span>
  <span m=''1673750''>other</span> <span m=''1673890''>procedure</span> <span m=''1674380''>if
  you</span> <span m=''1674650''>wanted</span> <span m=''1674840''>to?</span> </p><p><span
  m=''1675460''>PROFESSOR: Yes.</span> <span m=''1676320''>Good</span> <span m=''1676520''>question.</span>
  <span m=''1678960''>If</span> <span m=''1679150''>I</span> <span m=''1679280''>had</span>
  <span m=''1679400''>left</span> <span m=''1679800''>this</span> <span m=''1680180''>quotation</span>
  <span m=''1680810''>off</span> <span m=''1681410''>at</span> <span m=''1681610''>this</span>
  <span m=''1681800''>point,</span> <span m=''1684740''>if</span> <span m=''1684900''>I</span>
  <span m=''1685400''>had</span> <span m=''1685650''>left that</span> <span m=''1685810''>quotation</span>
  <span m=''1686230''>off</span> <span m=''1686400''>at that</span> <span m=''1686650''>point,</span>
  <span m=''1687380''>then</span> <span m=''1688170''>I</span> <span m=''1688370''>would</span>
  <span m=''1688560''>be</span> <span m=''1688720''>referring</span> <span m=''1689170''>here</span>
  <span m=''1689840''>to</span> <span m=''1690050''>the</span> <span m=''1690210''>procedure</span>
  <span m=''1691060''>which</span> <span m=''1691390''>is</span> <span m=''1691610''>the</span>
  <span m=''1692590''>thing</span> <span m=''1692790''>that</span> <span m=''1692970''>plus</span>
  <span m=''1693210''>is</span> <span m=''1693270''>defined</span> <span m=''1693720''>to</span>
  <span m=''1693800''>be.</span> </p><p><span m=''1695510''>And</span> <span m=''1695850''>indeed,</span>
  <span m=''1697110''>I</span> <span m=''1697270''>could</span> <span m=''1697650''>compare</span>
  <span m=''1701580''>some</span> <span m=''1701940''>procedures</span> <span m=''1702520''>with</span>
  <span m=''1702640''>each</span> <span m=''1702810''>other</span> <span m=''1703790''>for</span>
  <span m=''1704030''>identity.</span> <span m=''1705070''>Now</span> <span m=''1705220''>what</span>
  <span m=''1705430''>that</span> <span m=''1705700''>means</span> <span m=''1706330''>is</span>
  <span m=''1706480''>not</span> <span m=''1706710''>clear</span> <span m=''1706970''>right</span>
  <span m=''1707190''>now.</span> <span m=''1708080''>I</span> <span m=''1708190''>don''t</span>
  <span m=''1708370''>like</span> <span m=''1708540''>to</span> <span m=''1708640''>think</span>
  <span m=''1708850''>about</span> <span m=''1709140''>it.</span> <span m=''1710100''>Because</span>
  <span m=''1710370''>I</span> <span m=''1710440''>don''t</span> <span m=''1710560''>know</span>
  <span m=''1710690''>exactly</span> <span m=''1711080''>what</span> <span m=''1711180''>it
  would</span> <span m=''1711330''>need</span> <span m=''1711480''>to</span> <span
  m=''1711550''>compare</span> <span m=''1711840''>procedures.</span> <span m=''1712450''>There
  are</span> <span m=''1712710''>reasons</span> <span m=''1712990''>why</span> <span
  m=''1713120''>that</span> <span m=''1713290''>may</span> <span m=''1713430''>make</span>
  <span m=''1713620''>no</span> <span m=''1713750''>sense</span> <span m=''1714000''>at</span>
  <span m=''1714150''>all.</span> <span m=''1715610''>However,</span> <span m=''1715990''>the</span>
  <span m=''1716090''>symbols,</span> <span m=''1716490''>we</span> <span m=''1716630''>understand.</span>
  <span m=''1718890''>And</span> <span m=''1719060''>so</span> <span m=''1719220''>that''s</span>
  <span m=''1719450''>why</span> <span m=''1719600''>I</span> <span m=''1719670''>put</span>
  <span m=''1719830''>that</span> <span m=''1719950''>quote</span> <span m=''1720190''>in.</span>
  <span m=''1721240''>I</span> <span m=''1721360''>want</span> <span m=''1721480''>to</span>
  <span m=''1721610''>talk</span> <span m=''1721810''>about</span> <span m=''1721930''>the</span>
  <span m=''1722060''>symbol</span> <span m=''1722360''>that''s</span> <span m=''1722510''>apparent</span>
  <span m=''1722980''>on</span> <span m=''1723080''>the</span> <span m=''1723180''>page.</span>
  <span m=''1726250''>Any</span> <span m=''1726450''>other</span> <span m=''1726580''>questions?</span>
  <span m=''1728700''>OK.</span> <span m=''1730720''>Thank</span> <span m=''1730960''>you.</span>
  <span m=''1731060''>Let''s</span> <span m=''1731190''>take</span> <span m=''1731330''>a</span>
  <span m=''1731370''>break.</span> </p><p><span m=''1734210''>[MUSIC PLAYING]</span>
  </p><p><span m=''1770010''>PROFESSOR: Well,</span> <span m=''1770180''>let''s</span>
  <span m=''1770370''>see.</span> <span m=''1771580''>We''ve</span> <span m=''1771740''>just</span>
  <span m=''1772040''>developed</span> <span m=''1772510''>a</span> <span m=''1772620''>fairly</span>
  <span m=''1773020''>plausible</span> <span m=''1773510''>program</span> <span m=''1775160''>for</span>
  <span m=''1775560''>computing</span> <span m=''1776000''>the</span> <span m=''1776090''>derivatives</span>
  <span m=''1776600''>of</span> <span m=''1776720''>algebraic</span> <span m=''1777160''>expressions.</span>
  <span m=''1778390''>It''s</span> <span m=''1778590''>an</span> <span m=''1778660''>incomplete</span>
  <span m=''1779170''>program,</span> <span m=''1779670''>if</span> <span m=''1780160''>you</span>
  <span m=''1780290''>would</span> <span m=''1780400''>like</span> <span m=''1780590''>to</span>
  <span m=''1780670''>add</span> <span m=''1780910''>more</span> <span m=''1781120''>rules.</span>
  <span m=''1782330''>And</span> <span m=''1782730''>perhaps</span> <span m=''1783100''>you
  might</span> <span m=''1783250''>extend</span> <span m=''1783525''>it</span> <span
  m=''1783800''>to</span> <span m=''1783910''>deal</span> <span m=''1784140''>with</span>
  <span m=''1785130''>uses</span> <span m=''1785580''>of</span> <span m=''1786020''>addition</span>
  <span m=''1786550''>with</span> <span m=''1786690''>any</span> <span m=''1786860''>number</span>
  <span m=''1787170''>of</span> <span m=''1787260''>arguments</span> <span m=''1787820''>and</span>
  <span m=''1787890''>multiplication</span> <span m=''1788390''>with</span> <span
  m=''1788550''>any</span> <span m=''1788730''>of</span> <span m=''1788810''>the</span>
  <span m=''1788920''>number</span> <span m=''1789160''>of</span> <span m=''1789250''>arguments.</span>
  <span m=''1789950''>And</span> <span m=''1790100''>that''s</span> <span m=''1790300''>all</span>
  <span m=''1790520''>rather</span> <span m=''1790830''>easy.</span> </p><p><span
  m=''1792470''>However,</span> <span m=''1794620''>there</span> <span m=''1794970''>was</span>
  <span m=''1795110''>a</span> <span m=''1795160''>little</span> <span m=''1795630''>fly</span>
  <span m=''1796080''>in</span> <span m=''1796200''>that</span> <span m=''1796380''>ointment.</span>
  <span m=''1797620''>We</span> <span m=''1797800''>go</span> <span m=''1797960''>back</span>
  <span m=''1798250''>to</span> <span m=''1798370''>this</span> <span m=''1801670''>slide.</span>
  <span m=''1802980''>We</span> <span m=''1803180''>see</span> <span m=''1803430''>that</span>
  <span m=''1804030''>the</span> <span m=''1804280''>expressions</span> <span m=''1804910''>that</span>
  <span m=''1805010''>we</span> <span m=''1805130''>get</span> <span m=''1806860''>are</span>
  <span m=''1807640''>rather</span> <span m=''1807990''>bad.</span> <span m=''1809000''>This</span>
  <span m=''1809280''>is</span> <span m=''1809490''>a</span> <span m=''1809660''>rather</span>
  <span m=''1810050''>bad</span> <span m=''1810350''>expression.</span> <span m=''1811620''>How</span>
  <span m=''1811800''>do</span> <span m=''1811890''>we</span> <span m=''1811980''>get</span>
  <span m=''1812180''>such</span> <span m=''1812370''>an</span> <span m=''1812440''>expression?</span>
  <span m=''1814000''>Why</span> <span m=''1814310''>do</span> <span m=''1814410''>we</span>
  <span m=''1814510''>have</span> <span m=''1814730''>that</span> <span m=''1814880''>expression?</span>
  <span m=''1816940''>Let''s</span> <span m=''1817220''>look</span> <span m=''1817310''>at</span>
  <span m=''1817400''>this</span> <span m=''1817520''>expression</span> <span m=''1817950''>in</span>
  <span m=''1818030''>some</span> <span m=''1818230''>detail.</span> <span m=''1819060''>Let''s</span>
  <span m=''1819180''>find</span> <span m=''1819350''>out</span> <span m=''1819510''>where</span>
  <span m=''1819650''>all</span> <span m=''1819740''>the</span> <span m=''1819830''>pieces</span>
  <span m=''1820190''>come</span> <span m=''1820390''>from.</span> <span m=''1821850''>As</span>
  <span m=''1822080''>we</span> <span m=''1822220''>see</span> <span m=''1822440''>here,</span>
  <span m=''1823670''>we</span> <span m=''1823800''>have</span> <span m=''1823930''>a</span>
  <span m=''1823980''>sum--</span> <span m=''1824590''>just</span> <span m=''1824800''>what
  I</span> <span m=''1824950''>showed</span> <span m=''1825160''>you at</span> <span
  m=''1825250''>the</span> <span m=''1825360''>end</span> <span m=''1825500''>of</span>
  <span m=''1825580''>the</span> <span m=''1825650''>last</span> <span m=''1825970''>time--</span>
  <span m=''1827012''>of</span> <span m=''1827380''>X</span> <span m=''1827630''>times</span>
  <span m=''1827890''>1</span> <span m=''1828120''>plus</span> <span m=''1828330''>1</span>
  <span m=''1828550''>time</span> <span m=''1828790''>X.</span> <span m=''1829540''>That</span>
  <span m=''1829910''>is</span> <span m=''1830060''>a</span> <span m=''1830110''>derivative</span>
  <span m=''1830530''>of</span> <span m=''1830660''>this</span> <span m=''1830840''>product.</span>
  <span m=''1832590''>The</span> <span m=''1832800''>produce</span> <span m=''1833270''>of</span>
  <span m=''1833540''>a times</span> <span m=''1833900''>that,</span> <span m=''1834920''>where</span>
  <span m=''1835080''>a</span> <span m=''1835240''>does</span> <span m=''1835410''>not</span>
  <span m=''1835670''>depend</span> <span m=''1836000''>upon</span> <span m=''1836270''>x,</span>
  <span m=''1836530''>and</span> <span m=''1836790''>therefore is</span> <span m=''1837010''>constant</span>
  <span m=''1837410''>with</span> <span m=''1837500''>respect</span> <span m=''1837880''>to</span>
  <span m=''1838080''>x,</span> <span m=''1839210''>is</span> <span m=''1839670''>this</span>
  <span m=''1840430''>sum,</span> <span m=''1840890''>which</span> <span m=''1841060''>goes</span>
  <span m=''1841300''>from</span> <span m=''1841470''>here</span> <span m=''1842250''>all</span>
  <span m=''1842400''>the</span> <span m=''1842560''>way</span> <span m=''1842720''>through</span>
  <span m=''1842940''>here</span> <span m=''1843660''>and</span> <span m=''1843910''>through</span>
  <span m=''1844120''>here.</span> <span m=''1844840''>Because</span> <span m=''1845510''>it</span>
  <span m=''1845730''>is</span> <span m=''1845930''>the</span> <span m=''1846050''>first</span>
  <span m=''1846470''>thing</span> <span m=''1847140''>times the</span> <span m=''1847560''>derivative</span>
  <span m=''1848020''>of</span> <span m=''1848140''>the</span> <span m=''1848470''>second</span>
  <span m=''1849550''>plus</span> <span m=''1850100''>the</span> <span m=''1851700''>derivative</span>
  <span m=''1852170''>of</span> <span m=''1852280''>the</span> <span m=''1852380''>first</span>
  <span m=''1853540''>times</span> <span m=''1853850''>the</span> <span m=''1854150''>second</span>
  <span m=''1854760''>as</span> <span m=''1854900''>the</span> <span m=''1855040''>program</span>
  <span m=''1855420''>we</span> <span m=''1855800''>wrote</span> <span m=''1856080''>on</span>
  <span m=''1856150''>the</span> <span m=''1856220''>blackboard</span> <span m=''1857970''>indicated</span>
  <span m=''1858410''>we</span> <span m=''1858500''>should</span> <span m=''1858680''>do.</span>
  </p><p><span m=''1860740''>And,</span> <span m=''1860960''>of</span> <span m=''1861260''>course,</span>
  <span m=''1863580''>the</span> <span m=''1863720''>product</span> <span m=''1864100''>of</span>
  <span m=''1864260''>bx</span> <span m=''1864450''>over</span> <span m=''1864850''>here</span>
  <span m=''1865590''>manifests</span> <span m=''1866190''>itself</span> <span m=''1866690''>as</span>
  <span m=''1867720''>B</span> <span m=''1867900''>times</span> <span m=''1868270''>1</span>
  <span m=''1868570''>plus</span> <span m=''1868770''>0</span> <span m=''1869060''>times</span>
  <span m=''1869410''>X</span> <span m=''1870950''>because</span> <span m=''1871310''>we</span>
  <span m=''1871450''>see</span> <span m=''1871920''>that</span> <span m=''1874710''>B</span>
  <span m=''1874860''>does</span> <span m=''1874990''>not</span> <span m=''1875220''>depend</span>
  <span m=''1875510''>upon</span> <span m=''1875770''>X.</span> <span m=''1876640''>And</span>
  <span m=''1876820''>so</span> <span m=''1876900''>the</span> <span m=''1876980''>derivative</span>
  <span m=''1877390''>of</span> <span m=''1877560''>B</span> <span m=''1877720''>is</span>
  <span m=''1877830''>this</span> <span m=''1877930''>0,</span> <span m=''1878950''>and
  the</span> <span m=''1879220''>derivative</span> <span m=''1879670''>of X with</span>
  <span m=''1879940''>respect</span> <span m=''1880300''>itself</span> <span m=''1880650''>is</span>
  <span m=''1880730''>the</span> <span m=''1880810''>1.</span> <span m=''1883100''>And,</span>
  <span m=''1883270''>of</span> <span m=''1883450''>course,</span> <span m=''1884095''>the</span>
  <span m=''1884450''>derivative</span> <span m=''1884750''>of the</span> <span m=''1884930''>sums</span>
  <span m=''1885660''>over</span> <span m=''1885800''>here</span> <span m=''1886260''>turn</span>
  <span m=''1886510''>into</span> <span m=''1886690''>these</span> <span m=''1886960''>two</span>
  <span m=''1887140''>sums</span> <span m=''1887510''>of</span> <span m=''1887650''>the</span>
  <span m=''1887740''>derivatives</span> <span m=''1888150''>of</span> <span m=''1888220''>the</span>
  <span m=''1888300''>parts.</span> </p><p><span m=''1889360''>So</span> <span m=''1889650''>what</span>
  <span m=''1889860''>we''re</span> <span m=''1890000''>seeing</span> <span m=''1890400''>here</span>
  <span m=''1891000''>is</span> <span m=''1891180''>exactly</span> <span m=''1891840''>the</span>
  <span m=''1891950''>thing</span> <span m=''1892150''>I</span> <span m=''1892240''>was</span>
  <span m=''1892380''>trying</span> <span m=''1892620''>to</span> <span m=''1892690''>tell</span>
  <span m=''1892880''>you</span> <span m=''1893060''>about</span> <span m=''1893780''>with</span>
  <span m=''1894030''>Fibonacci</span> <span m=''1894550''>numbers</span> <span m=''1894960''>a</span>
  <span m=''1895040''>while</span> <span m=''1895370''>ago,</span> <span m=''1897760''>that</span>
  <span m=''1898080''>the</span> <span m=''1898190''>form</span> <span m=''1898710''>of</span>
  <span m=''1898820''>the</span> <span m=''1898900''>process</span> <span m=''1901450''>is</span>
  <span m=''1902110''>expanded</span> <span m=''1903690''>from</span> <span m=''1903920''>the</span>
  <span m=''1904000''>local</span> <span m=''1904430''>rules</span> <span m=''1905050''>that</span>
  <span m=''1905220''>you</span> <span m=''1905390''>see</span> <span m=''1905640''>in</span>
  <span m=''1905720''>the</span> <span m=''1905800''>procedure,</span> <span m=''1908220''>that</span>
  <span m=''1908360''>the</span> <span m=''1908450''>procedure</span> <span m=''1908850''>represents</span>
  <span m=''1909290''>a</span> <span m=''1909340''>set</span> <span m=''1909560''>of</span>
  <span m=''1909660''>local</span> <span m=''1910000''>rules</span> <span m=''1910650''>for</span>
  <span m=''1910830''>the</span> <span m=''1911030''>expansion</span> <span m=''1911640''>of</span>
  <span m=''1911720''>this</span> <span m=''1911870''>process.</span> <span m=''1913520''>And</span>
  <span m=''1913710''>here,</span> <span m=''1913900''>the</span> <span m=''1914010''>process</span>
  <span m=''1914420''>left</span> <span m=''1914650''>behind</span> <span m=''1916550''>some</span>
  <span m=''1916770''>stuff,</span> <span m=''1919170''>which</span> <span m=''1919330''>is</span>
  <span m=''1919440''>the</span> <span m=''1919590''>answer.</span> <span m=''1920370''>And</span>
  <span m=''1920440''>it</span> <span m=''1920520''>was</span> <span m=''1920620''>constructed</span>
  <span m=''1921930''>by</span> <span m=''1922170''>the</span> <span m=''1922280''>walk</span>
  <span m=''1922670''>it</span> <span m=''1922820''>takes</span> <span m=''1923370''>of</span>
  <span m=''1923520''>the</span> <span m=''1923610''>tree</span> <span m=''1923850''>structure,</span>
  <span m=''1925130''>which</span> <span m=''1925330''>is</span> <span m=''1925390''>the</span>
  <span m=''1925480''>expression.</span> <span m=''1928390''>So</span> <span m=''1928580''>every</span>
  <span m=''1928830''>part</span> <span m=''1928990''>in</span> <span m=''1929160''>the</span>
  <span m=''1929300''>answer</span> <span m=''1929600''>we</span> <span m=''1929750''>see</span>
  <span m=''1929930''>here</span> <span m=''1930510''>derives</span> <span m=''1931140''>from</span>
  <span m=''1931310''>some</span> <span m=''1931540''>part</span> <span m=''1931830''>of</span>
  <span m=''1931930''>the</span> <span m=''1932030''>problem.</span> </p><p><span
  m=''1934670''>Now,</span> <span m=''1935300''>we</span> <span m=''1935500''>can</span>
  <span m=''1935660''>look</span> <span m=''1935860''>at,</span> <span m=''1936050''>for</span>
  <span m=''1936180''>example,</span> <span m=''1936570''>the derivative</span> <span
  m=''1937040''>of</span> <span m=''1937360''>foo,</span> <span m=''1937860''>which</span>
  <span m=''1938020''>is</span> <span m=''1938130''>ax</span> <span m=''1938260''>square</span>
  <span m=''1938660''>plus</span> <span m=''1938820''>bx plus</span> <span m=''1938930''>c,</span>
  <span m=''1939930''>with</span> <span m=''1940090''>respect</span> <span m=''1940430''>to</span>
  <span m=''1940500''>other</span> <span m=''1940760''>things,</span> <span m=''1941900''>like</span>
  <span m=''1942050''>here,</span> <span m=''1942320''>for</span> <span m=''1942510''>example,</span>
  <span m=''1944310''>we</span> <span m=''1944430''>can</span> <span m=''1944560''>see</span>
  <span m=''1945050''>that</span> <span m=''1945250''>the</span> <span m=''1945320''>derivative</span>
  <span m=''1945830''>of</span> <span m=''1946020''>foo</span> <span m=''1946360''>with</span>
  <span m=''1946530''>respect</span> <span m=''1946920''>to</span> <span m=''1947010''>a.</span>
  <span m=''1947860''>And</span> <span m=''1948340''>it''s</span> <span m=''1948580''>very</span>
  <span m=''1948860''>similar.</span> <span m=''1949390''>It''s,</span> <span m=''1949530''>in</span>
  <span m=''1949640''>fact,</span> <span m=''1949880''>the</span> <span m=''1950040''>identical</span>
  <span m=''1950580''>algebraic</span> <span m=''1951230''>expression,</span> <span
  m=''1952490''>except</span> <span m=''1952840''>for</span> <span m=''1952910''>the</span>
  <span m=''1952990''>fact</span> <span m=''1953150''>that</span> <span m=''1953320''>theses</span>
  <span m=''1953410''>0''s</span> <span m=''1953810''>and</span> <span m=''1953920''>1''s</span>
  <span m=''1954220''>are</span> <span m=''1954320''>in</span> <span m=''1954390''>different</span>
  <span m=''1954670''>places.</span> <span m=''1955900''>Because</span> <span m=''1956470''>the</span>
  <span m=''1956650''>only</span> <span m=''1956830''>degree</span> <span m=''1957160''>of</span>
  <span m=''1957250''>freedom</span> <span m=''1957540''>we</span> <span m=''1957690''>have</span>
  <span m=''1957840''>in</span> <span m=''1957940''>this</span> <span m=''1958050''>tree</span>
  <span m=''1958260''>walk</span> <span m=''1959070''>is</span> <span m=''1959230''>what''s</span>
  <span m=''1959500''>constant</span> <span m=''1961080''>with</span> <span m=''1961190''>respect</span>
  <span m=''1961590''>to</span> <span m=''1961670''>the</span> <span m=''1961770''>variable</span>
  <span m=''1961990''>we''re</span> <span m=''1962285''>taking</span> <span m=''1962580''>the</span>
  <span m=''1962730''>derivative with</span> <span m=''1963170''>respect</span> <span
  m=''1963465''>to</span> <span m=''1964390''>and</span> <span m=''1964550''>was</span>
  <span m=''1964780''>the</span> <span m=''1964870''>same</span> <span m=''1965140''>variable.</span>
  </p><p><span m=''1968310''>In</span> <span m=''1968420''>other</span> <span m=''1968510''>words,</span>
  <span m=''1968710''>if</span> <span m=''1968820''>we</span> <span m=''1968910''>go</span>
  <span m=''1969070''>back</span> <span m=''1969450''>to</span> <span m=''1969870''>this</span>
  <span m=''1970830''>blackboard</span> <span m=''1971430''>and</span> <span m=''1971530''>we</span>
  <span m=''1971660''>look,</span> <span m=''1973130''>we</span> <span m=''1973310''>have</span>
  <span m=''1973490''>no</span> <span m=''1973670''>choice</span> <span m=''1974020''>what</span>
  <span m=''1974170''>to</span> <span m=''1974250''>do</span> <span m=''1974490''>when</span>
  <span m=''1974690''>we</span> <span m=''1974820''>take</span> <span m=''1975210''>the
  derivative of the</span> <span m=''1975580''>sum</span> <span m=''1976840''>or a</span>
  <span m=''1977110''>product.</span> <span m=''1978150''>The</span> <span m=''1978370''>only</span>
  <span m=''1978580''>interesting</span> <span m=''1979070''>place</span> <span m=''1979370''>here</span>
  <span m=''1979820''>is,</span> <span m=''1982580''>is</span> <span m=''1982990''>the</span>
  <span m=''1983280''>expression</span> <span m=''1983770''>the</span> <span m=''1983840''>variable,</span>
  <span m=''1984890''>or is</span> <span m=''1985300''>the</span> <span m=''1985430''>expression</span>
  <span m=''1986530''>a</span> <span m=''1986630''>constant</span> <span m=''1986950''>with</span>
  <span m=''1987130''>respect</span> <span m=''1987490''>to that</span> <span m=''1987690''>variable</span>
  <span m=''1988330''>for</span> <span m=''1988470''>very,</span> <span m=''1988760''>very</span>
  <span m=''1988990''>small</span> <span m=''1989390''>expressions?</span> <span m=''1990130''>In</span>
  <span m=''1990500''>which</span> <span m=''1990690''>case</span> <span m=''1990830''>we</span>
  <span m=''1990890''>get</span> <span m=''1991090''>various</span> <span m=''1991520''>1''s</span>
  <span m=''1991910''>and</span> <span m=''1992030''>0''s,</span> <span m=''1992750''>which</span>
  <span m=''1992910''>if we</span> <span m=''1993080''>go</span> <span m=''1993220''>back</span>
  <span m=''1993520''>to</span> <span m=''1993620''>this</span> <span m=''1993960''>slide,</span>
  <span m=''1995200''>we</span> <span m=''1995340''>can</span> <span m=''1995460''>see</span>
  <span m=''1995820''>that</span> <span m=''1996000''>the</span> <span m=''1996140''>0''s</span>
  <span m=''1996480''>that</span> <span m=''1996640''>appear</span> <span m=''1996970''>here,</span>
  <span m=''1997290''>for</span> <span m=''1997480''>example,</span> <span m=''1998670''>this</span>
  <span m=''1998890''>1</span> <span m=''1999780''>over</span> <span m=''1999960''>here</span>
  <span m=''2000540''>in</span> <span m=''2000650''>derivative</span> <span m=''2000970''>of</span>
  <span m=''2001250''>foo</span> <span m=''2001590''>with</span> <span m=''2001740''>respect</span>
  <span m=''2002090''>to</span> <span m=''2002170''>A,</span> <span m=''2003180''>which</span>
  <span m=''2003340''>gets</span> <span m=''2003530''>us</span> <span m=''2003640''>an</span>
  <span m=''2003750''>X</span> <span m=''2004270''>square,</span> <span m=''2004770''>because</span>
  <span m=''2005100''>that</span> <span m=''2005420''>1</span> <span m=''2005710''>gets</span>
  <span m=''2005980''>the</span> <span m=''2006060''>multiply</span> <span m=''2006315''>of</span>
  <span m=''2006570''>X and</span> <span m=''2006780''>X</span> <span m=''2007870''>into</span>
  <span m=''2008100''>the</span> <span m=''2008230''>answer,</span> <span m=''2009130''>that</span>
  <span m=''2009660''>1</span> <span m=''2011780''>is</span> <span m=''2011990''>0.</span>
  <span m=''2012770''>Over</span> <span m=''2012920''>here,</span> <span m=''2013110''>we''re
  not</span> <span m=''2013510''>taking the</span> <span m=''2013840''>derivative
  of foo</span> <span m=''2014050''>with respect to</span> <span m=''2014420''>c.</span>
  <span m=''2016690''>But</span> <span m=''2017060''>the</span> <span m=''2017150''>shapes</span>
  <span m=''2017590''>of</span> <span m=''2017690''>these</span> <span m=''2017890''>expressions</span>
  <span m=''2018420''>are</span> <span m=''2018570''>the</span> <span m=''2018690''>same.</span>
  <span m=''2020301''>See</span> <span m=''2020700''>all those</span> <span m=''2021100''>shapes.</span>
  <span m=''2022561''>They''re</span> <span m=''2023050''>the</span> <span m=''2023220''>same.</span>
  </p><p><span m=''2030480''>Well</span> <span m=''2030840''>is</span> <span m=''2030930''>there</span>
  <span m=''2031080''>anything</span> <span m=''2031400''>wrong</span> <span m=''2031600''>with</span>
  <span m=''2031720''>our</span> <span m=''2031890''>rules?</span> <span m=''2033750''>No.</span>
  <span m=''2034030''>They''re</span> <span m=''2034190''>the</span> <span m=''2034300''>right</span>
  <span m=''2034530''>rules.</span> <span m=''2036250''>We''ve</span> <span m=''2036440''>been</span>
  <span m=''2036610''>through</span> <span m=''2036790''>this</span> <span m=''2036950''>one</span>
  <span m=''2037140''>before.</span> <span m=''2038160''>One</span> <span m=''2038350''>of</span>
  <span m=''2038420''>the</span> <span m=''2038490''>things</span> <span m=''2038730''>you''re</span>
  <span m=''2038840''>going</span> <span m=''2038930''>to</span> <span m=''2039030''>begin</span>
  <span m=''2039320''>to</span> <span m=''2039390''>discover</span> <span m=''2041630''>is</span>
  <span m=''2041820''>that</span> <span m=''2042020''>there</span> <span m=''2042150''>aren''t</span>
  <span m=''2042420''>too</span> <span m=''2042570''>many</span> <span m=''2042780''>good</span>
  <span m=''2042960''>ideas.</span> <span m=''2046510''>When</span> <span m=''2046680''>we</span>
  <span m=''2046780''>were</span> <span m=''2046880''>looking</span> <span m=''2047120''>at</span>
  <span m=''2047220''>rational</span> <span m=''2047590''>numbers</span> <span m=''2049060''>yesterday,</span>
  <span m=''2052139''>the</span> <span m=''2052320''>problem</span> <span m=''2052610''>was</span>
  <span m=''2052780''>that</span> <span m=''2052850''>we</span> <span m=''2052929''>got</span>
  <span m=''2053130''>6/8</span> <span m=''2053480''>rather</span> <span m=''2053850''>then</span>
  <span m=''2053989''>3/4.</span> <span m=''2054909''>The</span> <span m=''2055179''>answer</span>
  <span m=''2055449''>was</span> <span m=''2055590''>unsimplified.</span> <span m=''2057949''>The</span>
  <span m=''2058400''>problem,</span> <span m=''2058719''>of</span> <span m=''2059000''>course,</span>
  <span m=''2060070''>is</span> <span m=''2060219''>very</span> <span m=''2060449''>similar.</span>
  <span m=''2061150''>There</span> <span m=''2061469''>are</span> <span m=''2061510''>things</span>
  <span m=''2061820''>I''d</span> <span m=''2062030''>like</span> <span m=''2062270''>to</span>
  <span m=''2062370''>be</span> <span m=''2062540''>identical</span> <span m=''2063560''>by</span>
  <span m=''2063690''>simplification</span> <span m=''2064350''>that</span> <span
  m=''2064489''>don''t</span> <span m=''2064690''>become</span> <span m=''2064929''>identical.</span>
  <span m=''2067350''>And</span> <span m=''2067730''>yet</span> <span m=''2067929''>the</span>
  <span m=''2068020''>rules</span> <span m=''2068320''>for</span> <span m=''2068460''>doing</span>
  <span m=''2069020''>addition</span> <span m=''2069429''>a</span> <span m=''2069469''>multiplication</span>
  <span m=''2070510''>of</span> <span m=''2070690''>rational</span> <span m=''2071060''>numbers</span>
  <span m=''2071409''>were</span> <span m=''2071510''>correct.</span> </p><p><span
  m=''2074000''>So</span> <span m=''2074190''>the</span> <span m=''2074280''>way</span>
  <span m=''2074440''>we</span> <span m=''2074570''>might</span> <span m=''2074870''>solve</span>
  <span m=''2075110''>this</span> <span m=''2075250''>problem</span> <span m=''2075620''>is</span>
  <span m=''2075719''>do</span> <span m=''2075860''>the</span> <span m=''2075949''>thing</span>
  <span m=''2076110''>we</span> <span m=''2076199''>did</span> <span m=''2076350''>last</span>
  <span m=''2076630''>time,</span> <span m=''2076860''>which</span> <span m=''2076960''>always</span>
  <span m=''2077190''>works.</span> <span m=''2077940''>If</span> <span m=''2078050''>something</span>
  <span m=''2078340''>worked</span> <span m=''2078550''>last</span> <span m=''2078770''>time</span>
  <span m=''2078909''>it</span> <span m=''2078929''>ought</span> <span m=''2079020''>to</span>
  <span m=''2079110''>work</span> <span m=''2079300''>again.</span> <span m=''2080690''>It''s</span>
  <span m=''2080810''>changed</span> <span m=''2081080''>representation.</span> <span
  m=''2083120''>Perhaps</span> <span m=''2083590''>in</span> <span m=''2083650''>the</span>
  <span m=''2083719''>representation</span> <span m=''2084810''>we</span> <span m=''2084949''>could</span>
  <span m=''2085070''>put</span> <span m=''2085190''>in</span> <span m=''2085310''>a</span>
  <span m=''2085350''>simplification</span> <span m=''2086090''>step</span> <span
  m=''2087969''>that</span> <span m=''2088199''>produces</span> <span m=''2088409''>a</span>
  <span m=''2088460''>simplified</span> <span m=''2088940''>representation.</span>
  <span m=''2090199''>This</span> <span m=''2090400''>may</span> <span m=''2090590''>not</span>
  <span m=''2090790''>always</span> <span m=''2091090''>work,</span> <span m=''2091320''>of</span>
  <span m=''2091590''>course.</span> <span m=''2092580''>I''m</span> <span m=''2092699''>not</span>
  <span m=''2092870''>trying</span> <span m=''2093030''>to</span> <span m=''2093199''>say</span>
  <span m=''2093360''>that it</span> <span m=''2093489''>always</span> <span m=''2093860''>works.</span>
  <span m=''2095210''>But</span> <span m=''2095420''>it''s one</span> <span m=''2096380''>of</span>
  <span m=''2096639''>the</span> <span m=''2096810''>pieces</span> <span m=''2097010''>of</span>
  <span m=''2097120''>artillery</span> <span m=''2097640''>we</span> <span m=''2097900''>have</span>
  <span m=''2098950''>in</span> <span m=''2099080''>our</span> <span m=''2099250''>war</span>
  <span m=''2099540''>against</span> <span m=''2099810''>complexity.</span> </p><p><span
  m=''2101560''>You</span> <span m=''2101670''>see,</span> <span m=''2101830''>because</span>
  <span m=''2102090''>we</span> <span m=''2102250''>solved</span> <span m=''2102600''>our</span>
  <span m=''2102730''>problem</span> <span m=''2103100''>very</span> <span m=''2103380''>carefully.</span>
  <span m=''2104360''>What</span> <span m=''2104560''>we''ve</span> <span m=''2104730''>done,</span>
  <span m=''2105360''>is</span> <span m=''2105530''>we''ve</span> <span m=''2105690''>divided</span>
  <span m=''2106090''>the</span> <span m=''2106170''>world</span> <span m=''2106440''>in</span>
  <span m=''2106510''>several</span> <span m=''2106820''>parts.</span> <span m=''2107630''>There</span>
  <span m=''2107800''>are</span> <span m=''2107850''>derivatives</span> <span m=''2108300''>rules</span>
  <span m=''2111370''>and</span> <span m=''2111580''>general</span> <span m=''2111910''>rules</span>
  <span m=''2112220''>for</span> <span m=''2112350''>algebra</span> <span m=''2112980''>of</span>
  <span m=''2113100''>some</span> <span m=''2113320''>sort</span> <span m=''2114560''>at</span>
  <span m=''2114810''>this</span> <span m=''2114990''>level</span> <span m=''2115250''>of</span>
  <span m=''2115310''>detail.</span> <span m=''2116420''>and</span> <span m=''2116590''>i</span>
  <span m=''2116770''>have</span> <span m=''2116950''>an</span> <span m=''2117050''>abstraction</span>
  <span m=''2117670''>barrier.</span> <span m=''2121874''>And</span> <span m=''2122251''>i</span>
  <span m=''2122630''>have</span> <span m=''2122950''>the</span> <span m=''2123050''>representation</span>
  <span m=''2123920''>of</span> <span m=''2124010''>the</span> <span m=''2124160''>algebraic</span>
  <span m=''2124530''>expressions,</span> <span m=''2132710''>list</span> <span m=''2132910''>structure.</span>
  </p><p><span m=''2137420''>And</span> <span m=''2137820''>in</span> <span m=''2138100''>this</span>
  <span m=''2138290''>barrier,</span> <span m=''2140750''>I</span> <span m=''2141050''>have</span>
  <span m=''2141380''>the</span> <span m=''2141560''>interface</span> <span m=''2142060''>procedures.</span>
  <span m=''2143050''>I</span> <span m=''2143380''>have</span> <span m=''2144180''>constant,</span>
  <span m=''2148210''>and</span> <span m=''2148700''>things</span> <span m=''2148900''>like</span>
  <span m=''2149080''>same-var.</span> <span m=''2154680''>I</span> <span m=''2154760''>have</span>
  <span m=''2154960''>things</span> <span m=''2155230''>like</span> <span m=''2155720''>sum,</span>
  <span m=''2157840''>make-sum.</span> <span m=''2162310''>I</span> <span m=''2162470''>have</span>
  <span m=''2163200''>A1,</span> <span m=''2164900''>A2.</span> <span m=''2166770''>I</span>
  <span m=''2166850''>have</span> <span m=''2167000''>products</span> <span m=''2167540''>and</span>
  <span m=''2167670''>things</span> <span m=''2167900''>like</span> <span m=''2168160''>that,</span>
  <span m=''2168880''>all</span> <span m=''2169110''>the</span> <span m=''2169240''>other</span>
  <span m=''2169370''>things</span> <span m=''2169610''>I</span> <span m=''2169720''>might</span>
  <span m=''2169980''>need</span> <span m=''2170230''>for</span> <span m=''2170330''>various</span>
  <span m=''2170690''>kinds</span> <span m=''2170950''>of</span> <span m=''2171010''>algebraic</span>
  <span m=''2171490''>expressions.</span> </p><p><span m=''2173000''>Making</span>
  <span m=''2173400''>this</span> <span m=''2173580''>barrier</span> <span m=''2174350''>allows</span>
  <span m=''2174940''>me</span> <span m=''2176400''>to</span> <span m=''2176850''>arbitrarily</span>
  <span m=''2177490''>change</span> <span m=''2177870''>the</span> <span m=''2178080''>representation</span>
  <span m=''2180240''>without</span> <span m=''2180600''>changing</span> <span m=''2181010''>the</span>
  <span m=''2181110''>rules</span> <span m=''2181520''>that  are</span> <span m=''2181710''>written</span>
  <span m=''2181960''>in</span> <span m=''2182040''>terms</span> <span m=''2182350''>of
  that</span> <span m=''2182520''>representation.</span> <span m=''2185060''>So</span>
  <span m=''2185310''>if</span> <span m=''2185500''>I</span> <span m=''2185620''>can</span>
  <span m=''2185930''>make</span> <span m=''2186180''>the</span> <span m=''2186300''>problem</span>
  <span m=''2186640''>go</span> <span m=''2186810''>away</span> <span m=''2187610''>by</span>
  <span m=''2187890''>changing</span> <span m=''2188220''>representation,</span> <span
  m=''2191210''>the</span> <span m=''2191330''>composition</span> <span m=''2191890''>of</span>
  <span m=''2191960''>the</span> <span m=''2192000''>problem</span> <span m=''2192320''>into</span>
  <span m=''2192410''>these</span> <span m=''2192640''>two</span> <span m=''2192760''>parts</span>
  <span m=''2193440''>has</span> <span m=''2193660''>helped</span> <span m=''2193860''>me</span>
  <span m=''2193980''>a</span> <span m=''2194000''>great</span> <span m=''2194220''>deal.</span>
  </p><p><span m=''2195660''>So</span> <span m=''2195820''>let''s</span> <span m=''2195980''>take</span>
  <span m=''2196230''>a</span> <span m=''2196350''>very</span> <span m=''2196570''>simple</span>
  <span m=''2196880''>case</span> <span m=''2197130''>of</span> <span m=''2197230''>this.</span>
  <span m=''2198860''>What</span> <span m=''2199050''>was</span> <span m=''2199190''>one</span>
  <span m=''2199380''>of</span> <span m=''2199470''>the</span> <span m=''2199550''>problems?</span>
  <span m=''2200330''>Let''s</span> <span m=''2200550''>go</span> <span m=''2200660''>back</span>
  <span m=''2200980''>to</span> <span m=''2201100''>this</span> <span m=''2202410''>transparency</span>
  <span m=''2203210''>again.</span> <span m=''2204115''>And</span> <span m=''2204590''>we</span>
  <span m=''2204800''>see</span> <span m=''2205050''>here,</span> <span m=''2205690''>oh</span>
  <span m=''2205850''>yes,</span> <span m=''2206230''>there''s</span> <span m=''2206410''>horrible</span>
  <span m=''2206850''>things</span> <span m=''2207790''>like</span> <span m=''2208280''>here</span>
  <span m=''2208640''>is</span> <span m=''2208830''>the</span> <span m=''2208950''>sum</span>
  <span m=''2209910''>of</span> <span m=''2210510''>an</span> <span m=''2210640''>expression</span>
  <span m=''2211220''>and</span> <span m=''2211430''>0.</span> <span m=''2213190''>Well</span>
  <span m=''2213620''>that''s</span> <span m=''2213980''>no</span> <span m=''2214170''>reason</span>
  <span m=''2214480''>to</span> <span m=''2214540''>think</span> <span m=''2214730''>of
  it</span> <span m=''2214800''>as</span> <span m=''2215040''>anything</span> <span
  m=''2215360''>other than</span> <span m=''2215590''>the</span> <span m=''2215690''>expression</span>
  <span m=''2216190''>itself.</span> <span m=''2217300''>Why</span> <span m=''2217660''>should</span>
  <span m=''2217960''>the</span> <span m=''2218180''>summation</span> <span m=''2218760''>operation</span>
  <span m=''2219600''>have</span> <span m=''2219970''>made</span> <span m=''2220340''>up</span>
  <span m=''2221030''>this</span> <span m=''2221310''>edition?</span> <span m=''2223450''>It</span>
  <span m=''2223550''>can</span> <span m=''2223630''>be</span> <span m=''2223720''>smarter</span>
  <span m=''2224010''>than</span> <span m=''2224160''>that.</span> <span m=''2225550''>Or</span>
  <span m=''2225790''>here,</span> <span m=''2225960''>for</span> <span m=''2226150''>example,</span>
  <span m=''2227120''>is</span> <span m=''2227270''>a</span> <span m=''2227320''>multiplication</span>
  <span m=''2228880''>of</span> <span m=''2229080''>something</span> <span m=''2229520''>by</span>
  <span m=''2229690''>1.</span> <span m=''2230816''>It''s</span> <span m=''2231160''>another</span>
  <span m=''2231425''>thing</span> <span m=''2231690''>like</span> <span m=''2231940''>that.</span>
  <span m=''2232990''>Or</span> <span m=''2233150''>here is</span> <span m=''2233320''>a</span>
  <span m=''2233430''>product</span> <span m=''2233810''>of</span> <span m=''2233890''>something</span>
  <span m=''2234220''>with</span> <span m=''2234350''>0,</span> <span m=''2234700''>which</span>
  <span m=''2234890''>is</span> <span m=''2234960''>certainly</span> <span m=''2235250''>0.</span>
  <span m=''2237800''>So</span> <span m=''2237980''>we won''t</span> <span m=''2238250''>have</span>
  <span m=''2238420''>to</span> <span m=''2238590''>make</span> <span m=''2238770''>this</span>
  <span m=''2238920''>construction.</span> </p><p><span m=''2241430''>So</span> <span
  m=''2241600''>why</span> <span m=''2241750''>don''t</span> <span m=''2241840''>we</span>
  <span m=''2241950''>just</span> <span m=''2242140''>do</span> <span m=''2242300''>that?</span>
  <span m=''2243800''>We</span> <span m=''2244060''>need to change</span> <span m=''2244430''>the</span>
  <span m=''2244500''>way</span> <span m=''2244640''>the</span> <span m=''2244720''>representation</span>
  <span m=''2245340''>works,</span> <span m=''2247270''>almost</span> <span m=''2247750''>here.</span>
  <span m=''2257500''>Make-sum</span> <span m=''2261290''>to</span> <span m=''2261410''>be.</span>
  <span m=''2262060''>Well,</span> <span m=''2262490''>now</span> <span m=''2262700''>it''s</span>
  <span m=''2262840''>not</span> <span m=''2262980''>something</span> <span m=''2263210''>so</span>
  <span m=''2263360''>simple.</span> <span m=''2264020''>I''m</span> <span m=''2264250''>not</span>
  <span m=''2264490''>going</span> <span m=''2264640''>to</span> <span m=''2264720''>make</span>
  <span m=''2264900''>a</span> <span m=''2264970''>list</span> <span m=''2265470''>containing</span>
  <span m=''2266130''>the</span> <span m=''2266560''>symbol</span> <span m=''2267000''>plus</span>
  <span m=''2268150''>and</span> <span m=''2268500''>things</span> <span m=''2269470''>unless</span>
  <span m=''2269740''>I</span> <span m=''2269850''>need</span> <span m=''2270010''>to.</span>
  </p><p><span m=''2271322''>Well,</span> <span m=''2271820''>what</span> <span m=''2271950''>are</span>
  <span m=''2272090''>the</span> <span m=''2272180''>possibilities?</span> <span m=''2277220''>I</span>
  <span m=''2277370''>have</span> <span m=''2277540''>some sort</span> <span m=''2277670''>of</span>
  <span m=''2277730''>cases</span> <span m=''2278190''>here.</span> <span m=''2279420''>If</span>
  <span m=''2279610''>I</span> <span m=''2279700''>have</span> <span m=''2279860''>numbers,</span>
  <span m=''2286940''>if</span> <span m=''2287120''>anyone</span> <span m=''2287530''>is</span>
  <span m=''2287630''>a</span> <span m=''2287700''>number--</span> <span m=''2289160''>and</span>
  <span m=''2289270''>here''s</span> <span m=''2289480''>another</span> <span m=''2289770''>primitive</span>
  <span m=''2290130''>I''ve</span> <span m=''2290270''>just</span> <span m=''2290500''>introduced,</span>
  <span m=''2290820''>it''s</span> <span m=''2290930''>possible</span> <span m=''2291310''>to</span>
  <span m=''2291660''>tell</span> <span m=''2291920''>whether</span> <span m=''2292200''>something''s</span>
  <span m=''2292640''>number--</span> <span m=''2295230''>and</span> <span m=''2295870''>if</span>
  <span m=''2296450''>number</span> <span m=''2300610''>A2,</span> <span m=''2301590''>meaning</span>
  <span m=''2301840''>they''re</span> <span m=''2301970''>not</span> <span m=''2302530''>symbolic</span>
  <span m=''2303090''>expressions,</span> <span m=''2304350''>then</span> <span m=''2304750''>why</span>
  <span m=''2304940''>not</span> <span m=''2305120''>do</span> <span m=''2305250''>the</span>
  <span m=''2305380''>addition</span> <span m=''2305760''>now?</span> <span m=''2306280''>The</span>
  <span m=''2306620''>result</span> <span m=''2307110''>is</span> <span m=''2307210''>just</span>
  <span m=''2307450''>a</span> <span m=''2307500''>plus</span> <span m=''2308160''>of</span>
  <span m=''2308290''>A1</span> <span m=''2309220''>and</span> <span m=''2309420''>A2.</span>
  </p><p><span m=''2312270''>I''m</span> <span m=''2312700''>not asking</span> <span
  m=''2312880''>if</span> <span m=''2312990''>these</span> <span m=''2313170''>represent</span>
  <span m=''2313670''>numbers.</span> <span m=''2314000''>Of</span> <span m=''2314180''>course</span>
  <span m=''2314360''>all</span> <span m=''2314490''>of</span> <span m=''2314610''>these</span>
  <span m=''2314740''>symbols</span> <span m=''2315080''>represent</span> <span m=''2315540''>numbers.</span>
  <span m=''2317100''>I''m</span> <span m=''2317420''>talking</span> <span m=''2317580''>about</span>
  <span m=''2317690''>whether</span> <span m=''2318040''>the</span> <span m=''2318110''>one</span>
  <span m=''2318300''>I''ve</span> <span m=''2318460''>got</span> <span m=''2318750''>is</span>
  <span m=''2319000''>the</span> <span m=''2319100''>number</span> <span m=''2319350''>3</span>
  <span m=''2320700''>right</span> <span m=''2320900''>now.</span> <span m=''2323420''>And,</span>
  <span m=''2323690''>for</span> <span m=''2323810''>example,</span> <span m=''2328780''>supposing</span>
  <span m=''2329750''>A1</span> <span m=''2330150''>is</span> <span m=''2330250''>a</span>
  <span m=''2330290''>number,</span> <span m=''2338220''>and</span> <span m=''2338440''>it''s</span>
  <span m=''2338790''>equal to</span> <span m=''2339070''>0,</span> <span m=''2344350''>well</span>
  <span m=''2344560''>then</span> <span m=''2344820''>the</span> <span m=''2345130''>answer</span>
  <span m=''2345440''>is</span> <span m=''2345560''>just</span> <span m=''2345880''>A2.</span>
  <span m=''2346900''>There is</span> <span m=''2347320''>no</span> <span m=''2347460''>reason</span>
  <span m=''2347730''>to</span> <span m=''2347860''>make</span> <span m=''2348070''>anything</span>
  <span m=''2348390''>up.</span> <span m=''2350698''>And</span> <span m=''2351140''>if</span>
  <span m=''2359920''>A2</span> <span m=''2360490''>is</span> <span m=''2360600''>a</span>
  <span m=''2360660''>number,</span> <span m=''2361940''>and</span> <span m=''2362270''>equal</span>
  <span m=''2362730''>A20,</span> <span m=''2367290''>then</span> <span m=''2367630''>the</span>
  <span m=''2367710''>result</span> <span m=''2368110''>is</span> <span m=''2368210''>A1.</span>
  </p><p><span m=''2370210''>And</span> <span m=''2370370''>only</span> <span m=''2370740''>if</span>
  <span m=''2370890''>I</span> <span m=''2371000''>can''t</span> <span m=''2371310''>figure</span>
  <span m=''2371580''>out</span> <span m=''2371800''>something</span> <span m=''2372100''>better</span>
  <span m=''2372310''>to</span> <span m=''2372420''>do</span> <span m=''2372640''>with</span>
  <span m=''2372770''>this</span> <span m=''2372840''>situation,</span> <span m=''2374140''>well,</span>
  <span m=''2374320''>I</span> <span m=''2374410''>can</span> <span m=''2374560''>start</span>
  <span m=''2375120''>a</span> <span m=''2375230''>list.</span> <span m=''2378070''>Otherwise</span>
  <span m=''2380870''>I</span> <span m=''2381010''>want the</span> <span m=''2381310''>representation</span>
  <span m=''2382070''>to</span> <span m=''2382140''>be</span> <span m=''2382290''>the</span>
  <span m=''2382410''>list</span> <span m=''2384080''>containing</span> <span m=''2384940''>the</span>
  <span m=''2385160''>quoted</span> <span m=''2385790''>symbol</span> <span m=''2386400''>plus,</span>
  <span m=''2389130''>and</span> <span m=''2389930''>A1,</span> <span m=''2391520''>and</span>
  <span m=''2391670''>A2.</span> </p><p><span m=''2398720''>And,</span> <span m=''2398940''>of</span>
  <span m=''2399200''>course,</span> <span m=''2399710''>a</span> <span m=''2399830''>very</span>
  <span m=''2400080''>similar</span> <span m=''2400430''>thing</span> <span m=''2400660''>can</span>
  <span m=''2400740''>be</span> <span m=''2400850''>done</span> <span m=''2401050''>for</span>
  <span m=''2401130''>products.</span> <span m=''2403020''>And</span> <span m=''2403180''>I</span>
  <span m=''2403230''>think</span> <span m=''2403500''>I''ll</span> <span m=''2403730''>avoid</span>
  <span m=''2404160''>boring</span> <span m=''2404530''>you</span> <span m=''2404650''>with</span>
  <span m=''2404840''>them.</span> <span m=''2405650''>I</span> <span m=''2405720''>was</span>
  <span m=''2405850''>going</span> <span m=''2406040''>to</span> <span m=''2406140''>write</span>
  <span m=''2406370''>it on</span> <span m=''2406460''>the</span> <span m=''2406550''>blackboard.</span>
  <span m=''2407740''>I</span> <span m=''2407850''>don''t</span> <span m=''2408000''>think</span>
  <span m=''2408150''>it''s</span> <span m=''2408310''>necessary.</span> <span m=''2409080''>You</span>
  <span m=''2409200''>know</span> <span m=''2409320''>what</span> <span m=''2409450''>to</span>
  <span m=''2409540''>do.</span> <span m=''2410830''>It''s</span> <span m=''2410990''>very</span>
  <span m=''2411190''>simple.</span> </p><p><span m=''2412880''>But</span> <span m=''2413090''>now,</span>
  <span m=''2415130''>let''s</span> <span m=''2415340''>just</span> <span m=''2415510''>see</span>
  <span m=''2415630''>the</span> <span m=''2415730''>kind</span> <span m=''2415880''>of</span>
  <span m=''2416030''>results</span> <span m=''2416430''>we</span> <span m=''2416550''>get</span>
  <span m=''2417660''>out</span> <span m=''2417800''>of</span> <span m=''2417890''>changing</span>
  <span m=''2418340''>our</span> <span m=''2418470''>program</span> <span m=''2419190''>in</span>
  <span m=''2419360''>this</span> <span m=''2419550''>way.</span> <span m=''2421870''>Well,</span>
  <span m=''2422000''>here''s</span> <span m=''2422250''>the</span> <span m=''2422290''>derivatives</span>
  <span m=''2424110''>after</span> <span m=''2424400''>having</span> <span m=''2424670''>just</span>
  <span m=''2424940''>changed</span> <span m=''2425760''>the</span> <span m=''2425920''>constructors</span>
  <span m=''2427090''>for</span> <span m=''2427300''>expressions.</span> <span m=''2428810''>The</span>
  <span m=''2429230''>same</span> <span m=''2429790''>foo,</span> <span m=''2430450''>aX</span>
  <span m=''2430790''>square</span> <span m=''2431110''>plus</span> <span m=''2431330''>bX</span>
  <span m=''2431500''>plus</span> <span m=''2431830''>c,</span> <span m=''2433410''>and</span>
  <span m=''2433570''>what</span> <span m=''2433690''>I</span> <span m=''2433800''>get</span>
  <span m=''2435790''>is</span> <span m=''2435810''>nothing</span> <span m=''2436220''>more</span>
  <span m=''2436560''>than</span> <span m=''2438110''>the</span> <span m=''2438130''>derivative</span>
  <span m=''2438540''>of</span> <span m=''2438670''>that</span> <span m=''2439600''>is</span>
  <span m=''2439820''>2aX</span> <span m=''2440000''>plus</span> <span m=''2440265''>B.</span>
  </p><p><span m=''2440660''>Well,</span> <span m=''2440910''>it''s not</span> <span
  m=''2441110''>completely</span> <span m=''2441520''>simplified.</span> <span m=''2442670''>I</span>
  <span m=''2442790''>would</span> <span m=''2442910''>like</span> <span m=''2443070''>to</span>
  <span m=''2443150''>collect</span> <span m=''2443420''>common</span> <span m=''2443710''>terms</span>
  <span m=''2444000''>and</span> <span m=''2444100''>sums.</span> <span m=''2445170''>Well,</span>
  <span m=''2445300''>that''s</span> <span m=''2445500''>more</span> <span m=''2445670''>work.</span>
  <span m=''2447180''>And,</span> <span m=''2447440''>of</span> <span m=''2447680''>course,</span>
  <span m=''2448600''>programs</span> <span m=''2449060''>to</span> <span m=''2449120''>do</span>
  <span m=''2449270''>this</span> <span m=''2449430''>sort</span> <span m=''2449550''>of</span>
  <span m=''2449660''>thing</span> <span m=''2450550''>are</span> <span m=''2450780''>huge</span>
  <span m=''2451130''>and</span> <span m=''2451230''>complicated.</span> <span m=''2452440''>Algebraic</span>
  <span m=''2452980''>simplification,</span> <span m=''2453990''>it''s a</span> <span
  m=''2454160''>very</span> <span m=''2454450''>complicated</span> <span m=''2454980''>mess.</span>
  <span m=''2456510''>There''s a</span> <span m=''2456680''>very</span> <span m=''2456900''>famous</span>
  <span m=''2457190''>program</span> <span m=''2457490''>you</span> <span m=''2457570''>may</span>
  <span m=''2457670''>have</span> <span m=''2457770''>heard</span> <span m=''2457900''>of</span>
  <span m=''2458010''>called</span> <span m=''2458240''>Maxima</span> <span m=''2458690''>developed
  at</span> <span m=''2459070''>MIT</span> <span m=''2459460''>in</span> <span m=''2459570''>the</span>
  <span m=''2459840''>past,</span> <span m=''2460460''>which</span> <span m=''2460660''>is</span>
  <span m=''2461440''>5,000</span> <span m=''2462120''>pages</span> <span m=''2462470''>of</span>
  <span m=''2462750''>Lisp</span> <span m=''2463120''>code,</span> <span m=''2464010''>mostly</span>
  <span m=''2464490''>the</span> <span m=''2464670''>algebraic</span> <span m=''2465480''>simplification</span>
  <span m=''2465830''>operations.</span> </p><p><span m=''2470080''>There</span> <span
  m=''2470410''>we</span> <span m=''2470560''>see</span> <span m=''2471370''>the</span>
  <span m=''2471610''>derivative of</span> <span m=''2471940''>foo.</span> <span m=''2472210''>In
  fact,</span> <span m=''2472610''>X</span> <span m=''2472740''>is at</span> <span
  m=''2472870''>something</span> <span m=''2473130''>I</span> <span m=''2473190''>wouldn''t</span>
  <span m=''2473570''>take</span> <span m=''2473750''>off</span> <span m=''2473880''>more</span>
  <span m=''2474030''>than</span> <span m=''2474150''>1</span> <span m=''2474390''>point</span>
  <span m=''2474620''>for</span> <span m=''2475180''>on</span> <span m=''2475320''>an</span>
  <span m=''2475570''>elementary</span> <span m=''2475980''>calculus</span> <span
  m=''2476520''>class.</span> <span m=''2478390''>And</span> <span m=''2478650''>the</span>
  <span m=''2478910''>derivative</span> <span m=''2479290''>of foo with</span> <span
  m=''2479580''>respect</span> <span m=''2480050''>to a,</span> <span m=''2480340''>well</span>
  <span m=''2480630''>it''s</span> <span m=''2480740''>gone</span> <span m=''2480960''>down</span>
  <span m=''2481190''>to</span> <span m=''2481640''>X</span> <span m=''2481880''>times</span>
  <span m=''2482170''>X,</span> <span m=''2482870''>which</span> <span m=''2483030''>isn''t</span>
  <span m=''2483240''>so</span> <span m=''2483380''>bad.</span> <span m=''2484730''>And</span>
  <span m=''2485040''>the derivative</span> <span m=''2485420''>of foo with</span>
  <span m=''2485720''>respect</span> <span m=''2486050''>to b</span> <span m=''2486380''>is</span>
  <span m=''2486560''>just</span> <span m=''2486820''>X</span> <span m=''2487060''>itself.</span>
  <span m=''2488200''>And</span> <span m=''2488430''>the derivative</span> <span m=''2488700''>of
  foo</span> <span m=''2488960''>with</span> <span m=''2489060''>respect</span> <span
  m=''2489190''>to c</span> <span m=''2489460''>comes</span> <span m=''2489690''>out</span>
  <span m=''2489860''>1.</span> <span m=''2490730''>So</span> <span m=''2490940''>I''m</span>
  <span m=''2491100''>pretty</span> <span m=''2491310''>pleased</span> <span m=''2491640''>with</span>
  <span m=''2491790''>this.</span> </p><p><span m=''2494260''>What</span> <span m=''2494390''>you''ve</span>
  <span m=''2494610''>seen</span> <span m=''2495980''>is,</span> <span m=''2496140''>of</span>
  <span m=''2496360''>course,</span> <span m=''2496440''>a little</span> <span m=''2496660''>bit</span>
  <span m=''2496830''>contrived,</span> <span m=''2497440''>carefully</span> <span
  m=''2497890''>organized</span> <span m=''2498430''>example</span> <span m=''2499580''>to</span>
  <span m=''2499820''>show</span> <span m=''2500100''>you</span> <span m=''2500490''>how</span>
  <span m=''2500750''>we</span> <span m=''2500870''>can</span> <span m=''2501020''>manipulate</span>
  <span m=''2501420''>algebraic</span> <span m=''2501940''>expressions,</span> <span
  m=''2503040''>how</span> <span m=''2503180''>we</span> <span m=''2503300''>do</span>
  <span m=''2503420''>that</span> <span m=''2503610''>abstractly</span> <span m=''2504280''>in</span>
  <span m=''2504400''>terms</span> <span m=''2504620''>of</span> <span m=''2504690''>abstract</span>
  <span m=''2505280''>syntax</span> <span m=''2506510''>rather</span> <span m=''2506760''>than</span>
  <span m=''2506890''>concrete</span> <span m=''2507330''>syntax</span> <span m=''2509280''>and</span>
  <span m=''2510290''>how</span> <span m=''2510470''>we</span> <span m=''2510600''>can</span>
  <span m=''2510790''>use</span> <span m=''2511080''>the</span> <span m=''2511510''>abstraction</span>
  <span m=''2512900''>to</span> <span m=''2513410''>control</span> <span m=''2513910''>what</span>
  <span m=''2514100''>goes</span> <span m=''2514350''>on</span> <span m=''2514930''>in</span>
  <span m=''2515080''>building</span> <span m=''2515440''>these</span> <span m=''2515620''>expressions.</span>
  </p><p><span m=''2517850''>But</span> <span m=''2518010''>the</span> <span m=''2518130''>real</span>
  <span m=''2518430''>story</span> <span m=''2518820''>isn''t</span> <span m=''2519060''>just</span>
  <span m=''2519270''>such</span> <span m=''2519430''>a</span> <span m=''2519480''>simple</span>
  <span m=''2519770''>thing</span> <span m=''2519970''>as</span> <span m=''2520110''>that.</span>
  <span m=''2520910''>The</span> <span m=''2521150''>real</span> <span m=''2521410''>story</span>
  <span m=''2521970''>is,</span> <span m=''2522130''>in</span> <span m=''2522270''>fact,</span>
  <span m=''2522770''>that</span> <span m=''2522920''>I''m</span> <span m=''2523110''>manipulating</span>
  <span m=''2523700''>these</span> <span m=''2523890''>expressions.</span> <span m=''2524450''>And</span>
  <span m=''2524530''>the</span> <span m=''2524600''>expressions</span> <span m=''2525280''>are</span>
  <span m=''2525570''>the</span> <span m=''2525710''>same</span> <span m=''2526040''>expressions--</span>
  <span m=''2526860''>going</span> <span m=''2527080''>back</span> <span m=''2527320''>to
  the</span> <span m=''2527500''>slide--</span> <span m=''2528150''>as</span> <span
  m=''2528370''>the</span> <span m=''2528440''>ones</span> <span m=''2528710''>that</span>
  <span m=''2528930''>are</span> <span m=''2529060''>Lisp</span> <span m=''2529840''>expressions.</span>
  <span m=''2532110''>There''s</span> <span m=''2532350''>a</span> <span m=''2532420''>pun</span>
  <span m=''2532700''>here.</span> <span m=''2533890''>I''ve</span> <span m=''2534170''>chosen</span>
  <span m=''2534660''>my</span> <span m=''2534790''>representation</span> <span m=''2535870''>to</span>
  <span m=''2536030''>be</span> <span m=''2536190''>the</span> <span m=''2536300''>same</span>
  <span m=''2536820''>as</span> <span m=''2536920''>the</span> <span m=''2537020''>representation</span>
  <span m=''2537710''>in</span> <span m=''2537800''>my</span> <span m=''2537960''>language</span>
  <span m=''2540680''>of</span> <span m=''2540810''>similar</span> <span m=''2541180''>things.</span>
  <span m=''2542830''>By</span> <span m=''2543180''>doing</span> <span m=''2543550''>so,</span>
  <span m=''2544380''>I''ve</span> <span m=''2545070''>invoked</span> <span m=''2545660''>a</span>
  <span m=''2545700''>necessity.</span> <span m=''2546990''>I</span> <span m=''2547120''>created</span>
  <span m=''2547660''>the</span> <span m=''2547740''>necessity</span> <span m=''2548590''>to</span>
  <span m=''2549080''>have</span> <span m=''2549260''>things</span> <span m=''2549480''>like</span>
  <span m=''2549710''>quotation</span> <span m=''2550890''>because</span> <span m=''2551550''>of</span>
  <span m=''2551630''>the</span> <span m=''2551710''>fact</span> <span m=''2552370''>that</span>
  <span m=''2552770''>my</span> <span m=''2552940''>language</span> <span m=''2554640''>is</span>
  <span m=''2554820''>capable</span> <span m=''2555310''>of</span> <span m=''2555430''>writing</span>
  <span m=''2555690''>expressions</span> <span m=''2556250''>that</span> <span m=''2556380''>talk</span>
  <span m=''2556620''>about</span> <span m=''2556810''>expressions</span> <span m=''2557370''>of</span>
  <span m=''2557560''>the</span> <span m=''2557650''>language.</span> <span m=''2559820''>I</span>
  <span m=''2559940''>need</span> <span m=''2560210''>to</span> <span m=''2560290''>have</span>
  <span m=''2560590''>something</span> <span m=''2560950''>that</span> <span m=''2561080''>says,</span>
  <span m=''2561460''>this</span> <span m=''2561760''>is</span> <span m=''2561880''>an</span>
  <span m=''2561980''>expression</span> <span m=''2562420''>I''m</span> <span m=''2562560''>talking</span>
  <span m=''2562910''>about</span> <span m=''2563820''>rather</span> <span m=''2564110''>than</span>
  <span m=''2564290''>this</span> <span m=''2564430''>expression</span> <span m=''2564890''>is</span>
  <span m=''2565000''>talking</span> <span m=''2565320''>about</span> <span m=''2565590''>something,</span>
  <span m=''2566882''>and</span> <span m=''2567280''>I</span> <span m=''2567430''>want</span>
  <span m=''2567530''>to</span> <span m=''2567630''>talk</span> <span m=''2567810''>about</span>
  <span m=''2568080''>that.</span> </p><p><span m=''2571290''>So</span> <span m=''2571550''>quotation</span>
  <span m=''2572390''>stops</span> <span m=''2572910''>and</span> <span m=''2573040''>says,</span>
  <span m=''2573630''>I''m</span> <span m=''2573800''>talking</span> <span m=''2574080''>about</span>
  <span m=''2574260''>this</span> <span m=''2574420''>expression</span> <span m=''2574930''>itself.</span>
  <span m=''2578140''>Now,</span> <span m=''2579900''>given</span> <span m=''2580220''>that</span>
  <span m=''2580480''>power,</span> <span m=''2581235''>if</span> <span m=''2581570''>I</span>
  <span m=''2581770''>can</span> <span m=''2581930''>manipulate</span> <span m=''2582390''>expressions</span>
  <span m=''2582930''>of</span> <span m=''2583030''>the</span> <span m=''2583140''>language,</span>
  <span m=''2584890''>I</span> <span m=''2585040''>can</span> <span m=''2585200''>begin</span>
  <span m=''2585540''>to</span> <span m=''2585630''>build</span> <span m=''2586240''>even</span>
  <span m=''2586510''>much</span> <span m=''2586740''>more</span> <span m=''2586940''>powerful</span>
  <span m=''2587370''>layers</span> <span m=''2587710''>upon</span> <span m=''2588020''>layers</span>
  <span m=''2588330''>of</span> <span m=''2588440''>languages.</span> <span m=''2589860''>Because</span>
  <span m=''2589970''>I</span> <span m=''2590040''>can</span> <span m=''2590190''>write</span>
  <span m=''2590400''>languages</span> <span m=''2591080''>that</span> <span m=''2591340''>not</span>
  <span m=''2591510''>only</span> <span m=''2591740''>are</span> <span m=''2591800''>embedded</span>
  <span m=''2592260''>in</span> <span m=''2592370''>Lisp</span> <span m=''2593410''>or</span>
  <span m=''2593510''>whatever</span> <span m=''2593770''>language</span> <span m=''2594110''>you</span>
  <span m=''2594200''>start</span> <span m=''2594520''>with,</span> <span m=''2594990''>but</span>
  <span m=''2596170''>languages</span> <span m=''2596600''>that</span> <span m=''2596730''>are</span>
  <span m=''2596770''>completely</span> <span m=''2597230''>different,</span> <span
  m=''2598710''>that are</span> <span m=''2598950''>just,</span> <span m=''2600040''>if</span>
  <span m=''2600190''>we</span> <span m=''2600280''>say,</span> <span m=''2600400''>interpreted</span>
  <span m=''2601070''>in</span> <span m=''2601260''>Lisp</span> <span m=''2601450''>or</span>
  <span m=''2601610''>something</span> <span m=''2601860''>like</span> <span m=''2602060''>that.</span>
  </p><p><span m=''2603280''>We''ll</span> <span m=''2603390''>get</span> <span m=''2603600''>to</span>
  <span m=''2603700''>understand</span> <span m=''2604140''>those</span> <span m=''2604310''>words</span>
  <span m=''2604570''>more</span> <span m=''2604870''>in</span> <span m=''2604950''>the</span>
  <span m=''2605020''>future.</span> <span m=''2606232''>But</span> <span m=''2606660''>right</span>
  <span m=''2606950''>now</span> <span m=''2607090''>I</span> <span m=''2607270''>just</span>
  <span m=''2607420''>want to</span> <span m=''2607490''>leave</span> <span m=''2607640''>you</span>
  <span m=''2608190''>with</span> <span m=''2608360''>the</span> <span m=''2608460''>fact</span>
  <span m=''2608910''>that</span> <span m=''2610150''>we''ve</span> <span m=''2611060''>hit</span>
  <span m=''2611460''>a</span> <span m=''2611550''>line</span> <span m=''2612520''>which</span>
  <span m=''2613570''>gives</span> <span m=''2613780''>us</span> <span m=''2614010''>tremendous</span>
  <span m=''2614610''>power.</span> <span m=''2616160''>And</span> <span m=''2616270''>this</span>
  <span m=''2616400''>point</span> <span m=''2616550''>we''ve</span> <span m=''2616990''>bought</span>
  <span m=''2617170''>a</span> <span m=''2617260''>sledgehammer.</span> <span m=''2617900''>We</span>
  <span m=''2618340''>have</span> <span m=''2618470''>to</span> <span m=''2618590''>be</span>
  <span m=''2618720''>careful</span> <span m=''2619780''>to</span> <span m=''2619860''>what</span>
  <span m=''2620020''>flies</span> <span m=''2620300''>when we</span> <span m=''2620390''>apply</span>
  <span m=''2620770''>it.</span> <span m=''2622250''>Thank you.</span> </p><p><span
  m=''2622570''>[MUSIC PLAYING]</span> </p>'
type: course
uid: fdf62f2cf463a056b918ba7f340743f3

---
None