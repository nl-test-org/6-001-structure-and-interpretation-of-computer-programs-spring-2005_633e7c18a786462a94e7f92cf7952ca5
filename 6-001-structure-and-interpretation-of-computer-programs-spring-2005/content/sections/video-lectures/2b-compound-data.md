---
about_this_resource_text: <p><b>Topics covered:</b> Compound Data</p> <p><b> Instructors:</b>
  Hal Abelson and Gerald Jay Sussman</p> <p>Subtitles for this course are provided
  through the generous assistance of Henry Baker, Hoofar Pourzand, Heather Wood, Aleksejs
  Truhans, Steven Edwards, George Menhorn, and Mahendra Kumar.</p>
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
embedded_media:
- id: 2B.jpg
  parent_uid: de38c275d043c9a135daa1024edec34b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/2b-compound-data/2B.jpg
  title: 2B.jpg
  type: null
  uid: b1ffb01180c304b21b1ebcde46d7d7a7
- id: Video-YouTube-Stream
  media_location: DrFkf-T-6Co
  parent_uid: de38c275d043c9a135daa1024edec34b
  title: Video-YouTube-Stream
  type: Video
  uid: 2d3938190388fc109893e69e3dd79dfd
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT_Structure_of_Computer_Programs_1986/lec2b.mp4
  parent_uid: de38c275d043c9a135daa1024edec34b
  title: Video-Internet Archive-MP4
  type: Video
  uid: 111c37bf6999220eb63cf716354e6ce2
- id: Thumbnail-OCW-JPG
  parent_uid: de38c275d043c9a135daa1024edec34b
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 3af65a64800e8a1693b8cbb072c6f9f6
- id: 3Play-3PlayYouTubeid-SRT
  media_location: DrFkf-T-6Co
  parent_uid: de38c275d043c9a135daa1024edec34b
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 0ce6f6b5d0bcf650dac3af2932c55da8
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/DrFkf-T-6Co/default.jpg
  parent_uid: de38c275d043c9a135daa1024edec34b
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 757f68557689f3128437e2453b332ea3
- id: DrFkf-T-6Co.srt
  parent_uid: de38c275d043c9a135daa1024edec34b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/2b-compound-data/DrFkf-T-6Co.srt
  title: 3play caption file
  type: null
  uid: 486a2b9c05cb6d3ee7d6d06da2fac3d5
- id: DrFkf-T-6Co.pdf
  parent_uid: de38c275d043c9a135daa1024edec34b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/2b-compound-data/DrFkf-T-6Co.pdf
  title: 3play pdf file
  type: null
  uid: 2fb7874c262b32016f3635d8143326ff
- id: Caption-3Play YouTube id-SRT
  parent_uid: de38c275d043c9a135daa1024edec34b
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: fc28dde30e7cccca3aea2757ae253950
- id: Transcript-3Play YouTube id-PDF
  parent_uid: de38c275d043c9a135daa1024edec34b
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: ce324913f92d852198448ba436efece0
inline_embed_id: 545604502b:compounddata55517922
layout: video
order_index: null
parent_uid: 4fcacad2c29981dd668a6b29822403cc
related_resources_text: ''
short_url: 2b-compound-data
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/2b-compound-data
template_type: Tabbed
title: '2B: Compound Data'
transcript: '<p><span m=''5892''>[MUSIC PLAYING]</span> </p><p><span m=''22120''>PROFESSOR:
  Well,</span> <span m=''22560''>so</span> <span m=''22820''>far</span> <span m=''23060''>in</span>
  <span m=''23170''>this</span> <span m=''23280''>course</span> <span m=''23530''>we''ve</span>
  <span m=''23650''>been</span> <span m=''23800''>talking</span> <span m=''24170''>about</span>
  <span m=''24510''>procedures,</span> <span m=''26370''>and</span> <span m=''26570''>then</span>
  <span m=''26680''>just to</span> <span m=''26900''>remind</span> <span m=''27300''>you</span>
  <span m=''27430''>of</span> <span m=''27500''>this</span> <span m=''27680''>framework</span>
  <span m=''29370''>that</span> <span m=''29520''>we</span> <span m=''29640''>introduced</span>
  <span m=''29980''>for</span> <span m=''30080''>talking</span> <span m=''30390''>about</span>
  <span m=''30620''>languages,</span> <span m=''31090''>we</span> <span m=''31180''>talked</span>
  <span m=''31420''>about</span> <span m=''31540''>the</span> <span m=''31670''>primitive</span>
  <span m=''32110''>things</span> <span m=''33740''>that</span> <span m=''33860''>are</span>
  <span m=''33980''>built</span> <span m=''34260''>into</span> <span m=''34390''>the</span>
  <span m=''34530''>system.</span> <span m=''36040''>We</span> <span m=''36190''>mentioned</span>
  <span m=''36520''>some</span> <span m=''36680''>means</span> <span m=''36940''>of</span>
  <span m=''37040''>combination</span> <span m=''39040''>by</span> <span m=''39160''>which</span>
  <span m=''39370''>you</span> <span m=''39440''>take</span> <span m=''39710''>the</span>
  <span m=''39790''>primitive</span> <span m=''40150''>things</span> <span m=''40530''>and
  you make</span> <span m=''40700''>more</span> <span m=''40850''>complicated</span>
  <span m=''41460''>things.</span> <span m=''42530''>And</span> <span m=''42880''>then
  we</span> <span m=''42980''>talked</span> <span m=''43220''>about</span> <span m=''43460''>the</span>
  <span m=''43540''>means</span> <span m=''43750''>of</span> <span m=''43820''>abstraction,</span>
  <span m=''44410''>how</span> <span m=''44490''>you</span> <span m=''44610''>can</span>
  <span m=''44750''>take</span> <span m=''44980''>those</span> <span m=''45150''>complicated</span>
  <span m=''45690''>things</span> <span m=''45860''>and</span> <span m=''45920''>name</span>
  <span m=''46250''>them</span> <span m=''46880''>so</span> <span m=''47040''>you</span>
  <span m=''47190''>can</span> <span m=''47340''>use</span> <span m=''47540''>them</span>
  <span m=''47660''>as</span> <span m=''47710''>simple</span> <span m=''48050''>building</span>
  <span m=''48370''>blocks.</span> </p><p><span m=''49770''>And</span> <span m=''49890''>then</span>
  <span m=''50020''>last</span> <span m=''50310''>time</span> <span m=''50500''>you</span>
  <span m=''50590''>saw</span> <span m=''50770''>we</span> <span m=''50860''>went</span>
  <span m=''51000''>even</span> <span m=''51170''>beyond</span> <span m=''51530''>that.</span>
  <span m=''51750''>We</span> <span m=''51850''>saw</span> <span m=''52040''>that</span>
  <span m=''52230''>by</span> <span m=''52350''>using</span> <span m=''53110''>higher</span>
  <span m=''53510''>order</span> <span m=''53820''>procedures,</span> <span m=''55570''>you</span>
  <span m=''55690''>can</span> <span m=''55830''>actually</span> <span m=''56210''>express</span>
  <span m=''56580''>general</span> <span m=''56860''>methods</span> <span m=''57460''>for</span>
  <span m=''57590''>computing</span> <span m=''58050''>things.</span> <span m=''58400''>Like</span>
  <span m=''58660''>the</span> <span m=''59090''>method</span> <span m=''59500''>of</span>
  <span m=''59600''>doing</span> <span m=''59840''>something</span> <span m=''60150''>by</span>
  <span m=''60290''>fixed</span> <span m=''60580''>points,</span> <span m=''61340''>or</span>
  <span m=''61540''>Newton''s</span> <span m=''61940''>method,</span> <span m=''63340''>and</span>
  <span m=''63520''>so</span> <span m=''63700''>the</span> <span m=''63980''>incredible</span>
  <span m=''64459''>expressive</span> <span m=''64959''>power</span> <span m=''65280''>you</span>
  <span m=''65420''>can</span> <span m=''65570''>get</span> <span m=''66140''>just</span>
  <span m=''66340''>by</span> <span m=''66460''>combining</span> <span m=''67020''>these</span>
  <span m=''67660''>means</span> <span m=''67880''>of</span> <span m=''67950''>abstraction.</span>
  </p><p><span m=''68730''>And</span> <span m=''68860''>the</span> <span m=''68940''>crucial</span>
  <span m=''69360''>idea</span> <span m=''69600''>in</span> <span m=''69750''>all</span>
  <span m=''69960''>of</span> <span m=''70190''>this</span> <span m=''71400''>is</span>
  <span m=''72000''>the</span> <span m=''72310''>one</span> <span m=''72490''>that</span>
  <span m=''72620''>we</span> <span m=''72750''>build</span> <span m=''73260''>a</span>
  <span m=''73340''>layered</span> <span m=''74010''>system.</span> <span m=''75210''>So</span>
  <span m=''75430''>for</span> <span m=''75600''>instance,</span> <span m=''76630''>if
  we''re</span> <span m=''76810''>writing the</span> <span m=''77100''>square</span>
  <span m=''77530''>root</span> <span m=''77570''>procedure,</span> <span m=''81150''>somewhere</span>
  <span m=''81920''>the</span> <span m=''82140''>square</span> <span m=''82540''>root</span>
  <span m=''82580''>procedure</span> <span m=''83080''>uses</span> <span m=''84850''>a</span>
  <span m=''84950''>procedure</span> <span m=''85360''>called</span> <span m=''85600''>good-enough,</span>
  <span m=''91490''>and</span> <span m=''92240''>between</span> <span m=''92750''>those</span>
  <span m=''93010''>there is</span> <span m=''93130''>some</span> <span m=''93360''>sort</span>
  <span m=''93590''>of</span> <span m=''94100''>abstraction</span> <span m=''94850''>boundary.</span>
  <span m=''98060''>It''s</span> <span m=''98260''>almost</span> <span m=''98620''>as</span>
  <span m=''98740''>if</span> <span m=''99160''>we</span> <span m=''99310''>go</span>
  <span m=''99510''>out</span> <span m=''100100''>and</span> <span m=''100360''>in
  writing</span> <span m=''100690''>square</span> <span m=''101080''>root,</span>
  <span m=''101450''>we</span> <span m=''101620''>go</span> <span m=''101760''>and</span>
  <span m=''101860''>make</span> <span m=''102040''>a</span> <span m=''102090''>contract</span>
  <span m=''102680''>with</span> <span m=''103540''>George,</span> <span m=''105120''>and</span>
  <span m=''105310''>tell</span> <span m=''105540''>George</span> <span m=''105830''>that</span>
  <span m=''105940''>his</span> <span m=''106120''>job</span> <span m=''106390''>is</span>
  <span m=''106490''>to</span> <span m=''106600''>write</span> <span m=''106800''>good-enough,</span>
  <span m=''109060''>and</span> <span m=''109200''>so</span> <span m=''109320''>long</span>
  <span m=''109480''>as</span> <span m=''109600''>good-enough</span> <span m=''110270''>works,</span>
  <span m=''110660''>we</span> <span m=''110760''>don''t</span> <span m=''110920''>care</span>
  <span m=''111130''>what</span> <span m=''111310''>it</span> <span m=''111410''>does.</span>
  <span m=''112630''>We</span> <span m=''112710''>don''t</span> <span m=''112890''>care</span>
  <span m=''113050''>exactly</span> <span m=''113520''>how</span> <span m=''113760''>it''s</span>
  <span m=''113890''>implemented.</span> <span m=''114380''>There are</span> <span
  m=''115010''>levels</span> <span m=''115450''>of</span> <span m=''115550''>detail</span>
  <span m=''115960''>here</span> <span m=''116290''>that</span> <span m=''116530''>are</span>
  <span m=''116770''>George''s</span> <span m=''117230''>concern</span> <span m=''118360''>and</span>
  <span m=''118550''>not</span> <span m=''118750''>ours.</span> <span m=''120450''>So</span>
  <span m=''120650''>for</span> <span m=''120830''>instance,</span> <span m=''121240''>George</span>
  <span m=''121560''>might</span> <span m=''121840''>use</span> <span m=''122730''>an</span>
  <span m=''122880''>absolute</span> <span m=''123300''>value</span> <span m=''123680''>procedure</span>
  <span m=''124350''>that''s</span> <span m=''124950''>written</span> <span m=''125150''>by</span>
  <span m=''125310''>Harry,</span> <span m=''126620''>and</span> <span m=''126780''>we</span>
  <span m=''126860''>don''t</span> <span m=''126970''>much</span> <span m=''127150''>care</span>
  <span m=''127370''>about</span> <span m=''127630''>that</span> <span m=''127820''>or</span>
  <span m=''127930''>even</span> <span m=''128190''>know</span> <span m=''128570''>that,</span>
  <span m=''129210''>maybe,</span> <span m=''129449''>Harry</span> <span m=''129780''>exists.</span>
  </p><p><span m=''133830''>So</span> <span m=''133990''>the</span> <span m=''134100''>crucial</span>
  <span m=''134500''>idea</span> <span m=''135470''>is</span> <span m=''135610''>that</span>
  <span m=''135850''>when we''re</span> <span m=''135970''>building</span> <span m=''136320''>things,</span>
  <span m=''136760''>we</span> <span m=''136910''>divorce</span> <span m=''137640''>the</span>
  <span m=''137960''>task</span> <span m=''138530''>of</span> <span m=''138690''>building</span>
  <span m=''139130''>things</span> <span m=''141530''>from</span> <span m=''141710''>the</span>
  <span m=''141810''>task</span> <span m=''142320''>of</span> <span m=''142600''>implementing</span>
  <span m=''143260''>the</span> <span m=''143360''>parts.</span> <span m=''147690''>And</span>
  <span m=''147910''>in</span> <span m=''148050''>a</span> <span m=''148110''>large</span>
  <span m=''148420''>system,</span> <span m=''148760''>of</span> <span m=''148840''>course,</span>
  <span m=''149090''>we</span> <span m=''149290''>have</span> <span m=''149520''>abstraction</span>
  <span m=''150110''>barriers</span> <span m=''150510''>like</span> <span m=''150710''>this</span>
  <span m=''151310''>at</span> <span m=''151490''>lots,</span> <span m=''151850''>and</span>
  <span m=''151950''>lots,</span> <span m=''152210''>and</span> <span m=''152300''>lots</span>
  <span m=''152520''>of</span> <span m=''152620''>levels.</span> <span m=''154180''>And</span>
  <span m=''154350''>that''s</span> <span m=''154550''>the</span> <span m=''154670''>idea</span>
  <span m=''154920''>that</span> <span m=''155040''>we''ve</span> <span m=''155170''>been</span>
  <span m=''155280''>using</span> <span m=''155920''>so</span> <span m=''156130''>far</span>
  <span m=''156340''>over</span> <span m=''156630''>and</span> <span m=''156700''>over</span>
  <span m=''156960''>in</span> <span m=''157020''>implementing</span> <span m=''157480''>procedures.</span>
  </p><p><span m=''158290''>Well,</span> <span m=''159730''>now</span> <span m=''160000''>what</span>
  <span m=''160130''>we''re</span> <span m=''160220''>going</span> <span m=''160310''>to</span>
  <span m=''160410''>do</span> <span m=''160740''>is</span> <span m=''160910''>look</span>
  <span m=''161080''>at</span> <span m=''161150''>the</span> <span m=''161220''>same</span>
  <span m=''161640''>issues</span> <span m=''162090''>for</span> <span m=''162270''>data.</span>
  <span m=''164170''>We''re</span> <span m=''164300''>going</span> <span m=''164390''>to</span>
  <span m=''164480''>see</span> <span m=''164940''>that</span> <span m=''165110''>the</span>
  <span m=''165190''>system</span> <span m=''165510''>has</span> <span m=''165730''>primitive</span>
  <span m=''166110''>data.</span> <span m=''166350''>In</span> <span m=''166490''>fact,</span>
  <span m=''166710''>we''ve already</span> <span m=''166980''>seen</span> <span m=''167280''>that.</span>
  <span m=''167470''>We''ve</span> <span m=''167590''>talked</span> <span m=''167820''>about</span>
  <span m=''168030''>numbers</span> <span m=''168400''>as</span> <span m=''168510''>primitive</span>
  <span m=''168840''>data.</span> <span m=''170270''>And</span> <span m=''170380''>then</span>
  <span m=''170500''>we''re</span> <span m=''170590''>going</span> <span m=''170650''>to</span>
  <span m=''170710''>see</span> <span m=''170840''>their</span> <span m=''170970''>means</span>
  <span m=''171210''>of</span> <span m=''171300''>combination</span> <span m=''172000''>for</span>
  <span m=''172140''>data.</span> <span m=''172390''>There''s</span> <span m=''172610''>glue</span>
  <span m=''173390''>that</span> <span m=''173700''>allows</span> <span m=''174010''>you</span>
  <span m=''174100''>to</span> <span m=''174190''>put</span> <span m=''174490''>primitive</span>
  <span m=''175030''>data</span> <span m=''175410''>together</span> <span m=''175940''>to</span>
  <span m=''176480''>make</span> <span m=''176670''>more</span> <span m=''177180''>complicated,</span>
  <span m=''177820''>kind</span> <span m=''177930''>of</span> <span m=''178050''>compound</span>
  <span m=''178600''>data.</span> <span m=''179500''>And</span> <span m=''179660''>then</span>
  <span m=''179820''>we''re</span> <span m=''179940''>going</span> <span m=''180010''>to</span>
  <span m=''180090''>see</span> <span m=''180870''>a</span> <span m=''181730''>methodology</span>
  <span m=''183030''>for</span> <span m=''183210''>abstraction</span> <span m=''184840''>that''s</span>
  <span m=''185120''>a</span> <span m=''185170''>very</span> <span m=''185400''>good</span>
  <span m=''185590''>thing</span> <span m=''185760''>to</span> <span m=''185900''>use</span>
  <span m=''186330''>when</span> <span m=''186490''>you</span> <span m=''186590''>start</span>
  <span m=''186840''>building</span> <span m=''187200''>up</span> <span m=''187330''>data</span>
  <span m=''187600''>in</span> <span m=''187750''>terms</span> <span m=''188020''>of</span>
  <span m=''188080''>simpler</span> <span m=''188440''>data.</span> </p><p><span m=''189090''>And</span>
  <span m=''189230''>again,</span> <span m=''189530''>the</span> <span m=''189620''>key</span>
  <span m=''189920''>idea</span> <span m=''190890''>is</span> <span m=''191030''>that</span>
  <span m=''191170''>you''re</span> <span m=''191260''>going</span> <span m=''191350''>to</span>
  <span m=''191440''>build</span> <span m=''191740''>the</span> <span m=''191790''>system</span>
  <span m=''192240''>in</span> <span m=''192450''>layers</span> <span m=''193770''>and</span>
  <span m=''193930''>set</span> <span m=''194100''>up</span> <span m=''194220''>abstraction</span>
  <span m=''194810''>barriers</span> <span m=''195500''>that</span> <span m=''195700''>isolate</span>
  <span m=''196280''>the</span> <span m=''196360''>details</span> <span m=''197210''>at</span>
  <span m=''197420''>the</span> <span m=''197500''>lower</span> <span m=''197780''>layers</span>
  <span m=''199840''>from</span> <span m=''200020''>the</span> <span m=''200090''>thing</span>
  <span m=''200250''>that''s</span> <span m=''200470''>going</span> <span m=''200700''>on</span>
  <span m=''200880''>at the</span> <span m=''200990''>upper</span> <span m=''201210''>layers.</span>
  <span m=''201630''>The</span> <span m=''201830''>details</span> <span m=''202230''>at</span>
  <span m=''202310''>the</span> <span m=''202390''>lower</span> <span m=''202660''>layers,</span>
  <span m=''203140''>the</span> <span m=''203270''>ideas,</span> <span m=''203670''>they</span>
  <span m=''203790''>won''t</span> <span m=''204020''>matter.</span> <span m=''205260''>They''re</span>
  <span m=''205410''>going</span> <span m=''205480''>to</span> <span m=''205550''>be</span>
  <span m=''205630''>George''s</span> <span m=''206070''>concern</span> <span m=''206850''>because</span>
  <span m=''207160''>he</span> <span m=''207240''>signed</span> <span m=''207540''>this</span>
  <span m=''207680''>contract</span> <span m=''208200''>with</span> <span m=''208320''>us</span>
  <span m=''208730''>for</span> <span m=''208930''>how</span> <span m=''209170''>the</span>
  <span m=''209280''>stuff</span> <span m=''209590''>that</span> <span m=''209760''>he</span>
  <span m=''209930''>implements</span> <span m=''210430''>behaves,</span> <span m=''212030''>and</span>
  <span m=''212160''>how</span> <span m=''212410''>he</span> <span m=''212500''>implements</span>
  <span m=''212910''>the</span> <span m=''212990''>thing</span> <span m=''213560''>is</span>
  <span m=''213740''>his</span> <span m=''213930''>problem.</span> </p><p><span m=''216250''>All
  right, well</span> <span m=''216510''>let''s</span> <span m=''216770''>look</span>
  <span m=''216870''>at</span> <span m=''216980''>an</span> <span m=''217090''>example.</span>
  <span m=''217890''>And</span> <span m=''218020''>the</span> <span m=''218150''>example</span>
  <span m=''218550''>I''m</span> <span m=''218640''>going</span> <span m=''218720''>to</span>
  <span m=''218800''>talk</span> <span m=''219050''>about</span> <span m=''219890''>is</span>
  <span m=''220110''>a</span> <span m=''220160''>system</span> <span m=''220780''>that</span>
  <span m=''220990''>does</span> <span m=''221210''>arithmetic</span> <span m=''221820''>on</span>
  <span m=''222000''>rational</span> <span m=''222460''>numbers.</span> <span m=''223010''>And</span>
  <span m=''223130''>what</span> <span m=''223240''>I</span> <span m=''223410''>have</span>
  <span m=''223580''>in</span> <span m=''223660''>mind</span> <span m=''224020''>is</span>
  <span m=''224260''>that</span> <span m=''225000''>we</span> <span m=''225170''>should</span>
  <span m=''225330''>have</span> <span m=''225750''>something</span> <span m=''226160''>in</span>
  <span m=''226240''>the</span> <span m=''226320''>computer</span> <span m=''227090''>that</span>
  <span m=''227420''>allows</span> <span m=''227830''>us</span> <span m=''228010''>to</span>
  <span m=''230230''>ask</span> <span m=''230550''>it,</span> <span m=''230750''>like,</span>
  <span m=''231870''>what''s</span> <span m=''232040''>the</span> <span m=''232220''>sum</span>
  <span m=''233350''>of</span> <span m=''233450''>1/2</span> <span m=''234960''>and</span>
  <span m=''235160''>1/4,</span> <span m=''235910''>and</span> <span m=''236080''>somehow</span>
  <span m=''236410''>the</span> <span m=''236500''>system</span> <span m=''236880''>should</span>
  <span m=''237080''>say,</span> <span m=''240590''>yeah,</span> <span m=''240830''>that''s</span>
  <span m=''241090''>3/4.</span> <span m=''242890''>Or</span> <span m=''244630''>we</span>
  <span m=''244900''>should</span> <span m=''245050''>be</span> <span m=''245140''>able</span>
  <span m=''245260''>to</span> <span m=''245310''>say</span> <span m=''245450''>what''s</span>
  <span m=''245730''>3/4</span> <span m=''247090''>times</span> <span m=''248800''>2/3,</span>
  <span m=''251070''>and</span> <span m=''251300''>the</span> <span m=''251370''>system</span>
  <span m=''251700''>should</span> <span m=''251910''>be</span> <span m=''252070''>able</span>
  <span m=''252220''>to</span> <span m=''252290''>say,</span> <span m=''252910''>yeah,</span>
  <span m=''253080''>that''s</span> <span m=''253320''>1/2.</span> <span m=''256500''>Right?</span>
  <span m=''256730''>And you</span> <span m=''256839''>know</span> <span m=''256959''>what</span>
  <span m=''257029''>I</span> <span m=''257110''>have</span> <span m=''257290''>in</span>
  <span m=''257350''>mind.</span> <span m=''257990''>And</span> <span m=''258180''>you</span>
  <span m=''258350''>also</span> <span m=''258570''>know</span> <span m=''258670''>how</span>
  <span m=''258760''>to</span> <span m=''258850''>do</span> <span m=''259070''>this</span>
  <span m=''259360''>from,</span> <span m=''259880''>I don''t know,</span> <span m=''260459''>fifth</span>
  <span m=''260700''>grade or</span> <span m=''260990''>sixth</span> <span m=''261290''>grade.</span>
  </p><p><span m=''262410''>There</span> <span m=''262790''>are these</span> <span
  m=''263100''>formulas</span> <span m=''263560''>that</span> <span m=''263660''>say</span>
  <span m=''263910''>if</span> <span m=''264060''>I</span> <span m=''264130''>have</span>
  <span m=''264350''>some</span> <span m=''264540''>fraction</span> <span m=''266510''>which</span>
  <span m=''266660''>is</span> <span m=''266760''>a numerator</span> <span m=''267380''>over
  a</span> <span m=''267620''>denominator,</span> <span m=''268530''>and</span> <span
  m=''268660''>I</span> <span m=''268790''>want</span> <span m=''268920''>to</span>
  <span m=''269050''>add</span> <span m=''269350''>that</span> <span m=''269970''>to</span>
  <span m=''270220''>some</span> <span m=''270430''>other</span> <span m=''270590''>fraction</span>
  <span m=''271740''>which</span> <span m=''271940''>is</span> <span m=''272020''>another</span>
  <span m=''272320''>numerator</span> <span m=''273600''>over</span> <span m=''273820''>another</span>
  <span m=''274090''>denominator,</span> <span m=''275470''>then</span> <span m=''275770''>the</span>
  <span m=''275940''>answer</span> <span m=''276280''>is</span> <span m=''277470''>the</span>
  <span m=''277580''>numerator</span> <span m=''278130''>of</span> <span m=''278200''>the</span>
  <span m=''278280''>first</span> <span m=''279490''>times</span> <span m=''279810''>the</span>
  <span m=''279890''>denominator</span> <span m=''280530''>of</span> <span m=''280590''>the</span>
  <span m=''280660''>second,</span> <span m=''281920''>plus</span> <span m=''282610''>the</span>
  <span m=''283420''>numerator</span> <span m=''283710''>of</span> <span m=''284020''>the</span>
  <span m=''284380''>second</span> <span m=''285140''>times</span> <span m=''285480''>the</span>
  <span m=''285560''>denominator</span> <span m=''285885''>of</span> <span m=''286210''>the</span>
  <span m=''286570''>first.</span> <span m=''288130''>That''s</span> <span m=''288740''>the</span>
  <span m=''288820''>numerator</span> <span m=''289320''>of</span> <span m=''289380''>the</span>
  <span m=''289500''>answer,</span> <span m=''289840''>and</span> <span m=''289930''>the</span>
  <span m=''290010''>denominator</span> <span m=''291430''>is</span> <span m=''291590''>the</span>
  <span m=''291670''>product</span> <span m=''292090''>of</span> <span m=''292150''>the</span>
  <span m=''292230''>two</span> <span m=''292360''>denominators.</span> </p><p><span
  m=''293260''>Right?</span> <span m=''293400''>So</span> <span m=''293520''>there''s</span>
  <span m=''293710''>something</span> <span m=''295160''>from</span> <span m=''295370''>fifth</span>
  <span m=''295610''>or</span> <span m=''295690''>sixth</span> <span m=''295980''>grade</span>
  <span m=''296350''>fraction</span> <span m=''296850''>arithmetic.</span> <span m=''297570''>And</span>
  <span m=''297740''>then</span> <span m=''297840''>similarly,</span> <span m=''298400''>if</span>
  <span m=''298530''>I</span> <span m=''298570''>want</span> <span m=''298670''>to</span>
  <span m=''298770''>multiply</span> <span m=''299400''>two</span> <span m=''299620''>things,</span>
  <span m=''299950''>n1</span> <span m=''300320''>over</span> <span m=''300520''>d1</span>
  <span m=''301850''>multiplied</span> <span m=''303410''>by</span> <span m=''303660''>n2</span>
  <span m=''304090''>over</span> <span m=''304270''>d2</span> <span m=''305890''>is</span>
  <span m=''306090''>the</span> <span m=''306170''>product</span> <span m=''306580''>of</span>
  <span m=''306660''>the</span> <span m=''306710''>numerators</span> <span m=''309250''>over</span>
  <span m=''309450''>the</span> <span m=''309550''>product</span> <span m=''309970''>of</span>
  <span m=''310030''>the</span> <span m=''310120''>denominators.</span> </p><p><span
  m=''314330''>So</span> <span m=''314490''>it''s</span> <span m=''314600''>no</span>
  <span m=''314680''>problem</span> <span m=''315080''>at</span> <span m=''315290''>all,</span>
  <span m=''316710''>but</span> <span m=''316840''>it''s</span> <span m=''316960''>absolutely</span>
  <span m=''317360''>no</span> <span m=''317510''>problem</span> <span m=''317960''>to</span>
  <span m=''318880''>think</span> <span m=''319190''>about</span> <span m=''319520''>what</span>
  <span m=''319660''>computation</span> <span m=''320400''>you</span> <span m=''320520''>want</span>
  <span m=''320620''>to</span> <span m=''320730''>make</span> <span m=''320980''>in</span>
  <span m=''321180''>adding</span> <span m=''321380''>and</span> <span m=''321460''>multiplying</span>
  <span m=''321990''>these</span> <span m=''322150''>fractions.</span> <span m=''323760''>But</span>
  <span m=''323900''>as soon as</span> <span m=''324010''>we go</span> <span m=''324380''>to</span>
  <span m=''324440''>implement</span> <span m=''324950''>it,</span> <span m=''325880''>we</span>
  <span m=''326010''>run</span> <span m=''326160''>up</span> <span m=''326290''>across</span>
  <span m=''326600''>something.</span> <span m=''327920''>We</span> <span m=''328040''>don''t</span>
  <span m=''328900''>have</span> <span m=''330340''>what a</span> <span m=''330570''>rational</span>
  <span m=''331010''>number</span> <span m=''331430''>is.</span> <span m=''333320''>So</span>
  <span m=''333530''>we</span> <span m=''333630''>said</span> <span m=''333850''>that</span>
  <span m=''334320''>the</span> <span m=''335030''>system</span> <span m=''335390''>gives</span>
  <span m=''335610''>us</span> <span m=''335770''>individual</span> <span m=''336470''>numbers,</span>
  <span m=''336840''>so</span> <span m=''336980''>we</span> <span m=''337090''>can</span>
  <span m=''337200''>have</span> <span m=''337370''>5</span> <span m=''337810''>and</span>
  <span m=''338010''>3,</span> <span m=''338930''>but</span> <span m=''340430''>somehow</span>
  <span m=''341950''>we</span> <span m=''342110''>don''t</span> <span m=''342260''>have</span>
  <span m=''342370''>a</span> <span m=''342480''>way</span> <span m=''342820''>of</span>
  <span m=''343700''>saying</span> <span m=''343960''>there''s</span> <span m=''344140''>a</span>
  <span m=''344190''>thing</span> <span m=''344610''>that</span> <span m=''344760''>has</span>
  <span m=''345510''>both</span> <span m=''345630''>a</span> <span m=''345960''>3</span>
  <span m=''346200''>and</span> <span m=''346310''>a</span> <span m=''346370''>4 in</span>
  <span m=''346670''>it,</span> <span m=''347880''>or</span> <span m=''347970''>both</span>
  <span m=''348910''>a</span> <span m=''349000''>2</span> <span m=''349200''>and</span>
  <span m=''349430''>a 3.</span> <span m=''349850''>It''s</span> <span m=''350040''>almost</span>
  <span m=''350480''>as</span> <span m=''350640''>if</span> <span m=''352470''>we''d</span>
  <span m=''352600''>like</span> <span m=''352800''>to</span> <span m=''352950''>imagine</span>
  <span m=''353550''>that</span> <span m=''354420''>somehow</span> <span m=''354780''>there</span>
  <span m=''354980''>are these</span> <span m=''355240''>clouds,</span> <span m=''357750''>and</span>
  <span m=''357850''>a</span> <span m=''357950''>cloud</span> <span m=''358460''>somehow</span>
  <span m=''359010''>has</span> <span m=''359320''>both</span> <span m=''359560''>a</span>
  <span m=''359640''>numerator</span> <span m=''360820''>and</span> <span m=''360930''>a</span>
  <span m=''361050''>denominator</span> <span m=''361720''>in</span> <span m=''361810''>it,</span>
  <span m=''362580''>and</span> <span m=''362730''>that''s</span> <span m=''362890''>what
  we''d</span> <span m=''363080''>like</span> <span m=''363250''>to</span> <span m=''363350''>work</span>
  <span m=''363590''>in</span> <span m=''363700''>terms</span> <span m=''364000''>of.</span>
  </p><p><span m=''366820''>Well,</span> <span m=''366960''>how</span> <span m=''367100''>are
  we</span> <span m=''367200''>going</span> <span m=''367270''>to</span> <span m=''367340''>solve</span>
  <span m=''367620''>that</span> <span m=''367800''>problem?</span> <span m=''368320''>We''re</span>
  <span m=''368450''>going</span> <span m=''368510''>to</span> <span m=''368570''>solve</span>
  <span m=''368890''>that</span> <span m=''369060''>problem</span> <span m=''369720''>by</span>
  <span m=''370020''>using</span> <span m=''371130''>this</span> <span m=''371360''>incredibly</span>
  <span m=''371910''>powerful</span> <span m=''372410''>design</span> <span m=''372770''>strategy</span>
  <span m=''373400''>that</span> <span m=''373990''>you''ve</span> <span m=''374160''>already</span>
  <span m=''374450''>seen</span> <span m=''374700''>us</span> <span m=''374830''>use</span>
  <span m=''375120''>over</span> <span m=''375410''>and</span> <span m=''375490''>over.</span>
  <span m=''376580''>And</span> <span m=''376730''>that''s</span> <span m=''376930''>the</span>
  <span m=''376980''>strategy</span> <span m=''377470''>of</span> <span m=''377560''>wishful</span>
  <span m=''377900''>thinking.</span> <span m=''385700''>Just</span> <span m=''385920''>like</span>
  <span m=''386110''>before</span> <span m=''386540''>when</span> <span m=''386710''>we</span>
  <span m=''386860''>didn''t</span> <span m=''387110''>have</span> <span m=''387260''>a</span>
  <span m=''387330''>procedure,</span> <span m=''387760''>we</span> <span m=''387870''>said,</span>
  <span m=''388040''>well, let''s</span> <span m=''388300''>imagine</span> <span m=''389110''>that</span>
  <span m=''389290''>that</span> <span m=''389460''>procedure</span> <span m=''389910''>already</span>
  <span m=''390240''>exists.</span> <span m=''391420''>We''ll</span> <span m=''391550''>say,</span>
  <span m=''391670''>well,</span> <span m=''391820''>let''s</span> <span m=''392030''>imagine</span>
  <span m=''392810''>that</span> <span m=''393410''>we</span> <span m=''393520''>have</span>
  <span m=''393730''>these</span> <span m=''393900''>clouds.</span> </p><p><span m=''396100''>Now</span>
  <span m=''396200''>more</span> <span m=''396360''>precisely</span> <span m=''397020''>what</span>
  <span m=''397170''>I</span> <span m=''397260''>mean</span> <span m=''397670''>is</span>
  <span m=''399250''>let''s</span> <span m=''399780''>imagine</span> <span m=''400780''>that</span>
  <span m=''401480''>we</span> <span m=''401590''>have</span> <span m=''402400''>three</span>
  <span m=''402600''>procedures,</span> <span m=''404360''>one</span> <span m=''404530''>called</span>
  <span m=''404860''>make-RAT.</span> <span m=''407740''>make-RAT</span> <span m=''409140''>is</span>
  <span m=''409300''>going</span> <span m=''409390''>to</span> <span m=''409490''>take</span>
  <span m=''411050''>as</span> <span m=''411210''>arguments</span> <span m=''412350''>two</span>
  <span m=''412510''>numbers,</span> <span m=''414530''>so I''ll call</span> <span
  m=''414780''>them</span> <span m=''414930''>numerator</span> <span m=''415390''>and</span>
  <span m=''415480''>denominator,</span> <span m=''417990''>and it''ll</span> <span
  m=''418360''>return</span> <span m=''418800''>for</span> <span m=''419020''>us</span>
  <span m=''420660''>a</span> <span m=''420810''>cloud--</span> <span m=''422860''>one</span>
  <span m=''422990''>of</span> <span m=''423050''>these</span> <span m=''423260''>clouds.</span>
  <span m=''425300''>I</span> <span m=''425380''>don''t</span> <span m=''425490''>really</span>
  <span m=''425690''>know</span> <span m=''425810''>what</span> <span m=''425920''>a</span>
  <span m=''425960''>cloud</span> <span m=''426350''>is.</span> <span m=''427030''>It''s</span>
  <span m=''427270''>whatever</span> <span m=''427610''>make-RAT</span> <span m=''428030''>returns,</span>
  <span m=''428470''>that''s</span> <span m=''428670''>its</span> <span m=''428920''>business.</span>
  </p><p><span m=''431500''>And</span> <span m=''431630''>then</span> <span m=''431760''>we''re</span>
  <span m=''431880''>going</span> <span m=''431960''>to</span> <span m=''432040''>say,</span>
  <span m=''432390''>suppose</span> <span m=''432660''>we''ve</span> <span m=''432820''>got</span>
  <span m=''433050''>one</span> <span m=''433180''>of</span> <span m=''433290''>these</span>
  <span m=''433400''>clouds,</span> <span m=''434170''>we</span> <span m=''434370''>have</span>
  <span m=''434570''>a</span> <span m=''434640''>procedure</span> <span m=''435070''>called</span>
  <span m=''435310''>numer,</span> <span m=''437100''>which</span> <span m=''437300''>takes</span>
  <span m=''437580''>in</span> <span m=''437750''>a</span> <span m=''437800''>cloud</span>
  <span m=''438790''>that has</span> <span m=''439220''>an</span> <span m=''439410''>n</span>
  <span m=''439480''>and</span> <span m=''439670''>a</span> <span m=''439770''>d</span>
  <span m=''440140''>in it,</span> <span m=''440260''>whatever</span> <span m=''440710''>a</span>
  <span m=''440760''>cloud</span> <span m=''441100''>is,</span> <span m=''441290''>and
  I don''t</span> <span m=''441550''>know what it</span> <span m=''441870''>is,</span>
  <span m=''443160''>and</span> <span m=''443390''>returns</span> <span m=''443690''>for</span>
  <span m=''443860''>us</span> <span m=''443990''>the</span> <span m=''444090''>numerator</span>
  <span m=''444530''>part.</span> <span m=''446980''>And</span> <span m=''447320''>then</span>
  <span m=''447350''>we''ll</span> <span m=''447510''>assume</span> <span m=''447770''>we</span>
  <span m=''447890''>have</span> <span m=''448010''>a</span> <span m=''448070''>procedure</span>
  <span m=''448520''>denom,</span> <span m=''451250''>which</span> <span m=''451460''>again</span>
  <span m=''451750''>takes</span> <span m=''452010''>in</span> <span m=''452110''>a</span>
  <span m=''452160''>cloud,</span> <span m=''452810''>whatever a</span> <span m=''453240''>cloud</span>
  <span m=''453590''>is,</span> <span m=''455310''>and</span> <span m=''455570''>returns</span>
  <span m=''455970''>for</span> <span m=''456110''>us</span> <span m=''456610''>the</span>
  <span m=''456870''>denominator</span> <span m=''457420''>[? required. ?]</span>
  </p><p><span m=''457850''>This</span> <span m=''458100''>is</span> <span m=''458210''>just</span>
  <span m=''458590''>like</span> <span m=''458830''>before,</span> <span m=''460190''>when</span>
  <span m=''460410''>if</span> <span m=''460580''>we''re</span> <span m=''460710''>building</span>
  <span m=''461660''>a</span> <span m=''462160''>square</span> <span m=''462530''>root,</span>
  <span m=''462700''>we</span> <span m=''462820''>assume</span> <span m=''463230''>that</span>
  <span m=''463370''>we</span> <span m=''463470''>have</span> <span m=''463680''>good</span>
  <span m=''463850''>enough.</span> <span m=''465440''>Right?</span> <span m=''465600''>And</span>
  <span m=''465760''>what</span> <span m=''465930''>we''ll</span> <span m=''466040''>say</span>
  <span m=''466290''>is,</span> <span m=''466650''>we''ll</span> <span m=''466790''>go</span>
  <span m=''466970''>find</span> <span m=''467280''>George,</span> <span m=''468010''>and
  we''ll</span> <span m=''468230''>say to</span> <span m=''468390''>George,</span>
  <span m=''468640''>well,</span> <span m=''469030''>it''s</span> <span m=''469130''>your</span>
  <span m=''469300''>business</span> <span m=''469690''>to</span> <span m=''469800''>make</span>
  <span m=''470020''>us</span> <span m=''470260''>these</span> <span m=''470480''>procedures.</span>
  <span m=''472280''>And</span> <span m=''472430''>how</span> <span m=''472650''>you</span>
  <span m=''472830''>choose</span> <span m=''473130''>to</span> <span m=''473220''>implement</span>
  <span m=''473630''>these</span> <span m=''473790''>clouds,</span> <span m=''474010''>that''s</span>
  <span m=''474170''>your</span> <span m=''474330''>problem.</span> <span m=''475060''>We</span>
  <span m=''475170''>don''t</span> <span m=''475290''>want</span> <span m=''475440''>to</span>
  <span m=''475520''>know.</span> </p><p><span m=''478670''>Well,</span> <span m=''480170''>having</span>
  <span m=''480540''>pushed</span> <span m=''480940''>this</span> <span m=''481140''>task</span>
  <span m=''481520''>off</span> <span m=''481730''>onto</span> <span m=''481960''>George,</span>
  <span m=''483340''>then</span> <span m=''483590''>it''s</span> <span m=''483740''>pretty</span>
  <span m=''484040''>easy</span> <span m=''484490''>to</span> <span m=''484720''>do</span>
  <span m=''484850''>the</span> <span m=''485000''>other</span> <span m=''485160''>part.</span>
  <span m=''485520''>Once</span> <span m=''485740''>we''ve</span> <span m=''485890''>got</span>
  <span m=''486130''>the</span> <span m=''486220''>clouds,</span> <span m=''487280''>it''s</span>
  <span m=''487450''>pretty</span> <span m=''487720''>easy</span> <span m=''487950''>to</span>
  <span m=''488040''>write</span> <span m=''488280''>the</span> <span m=''488360''>thing</span>
  <span m=''488590''>that</span> <span m=''488790''>does</span> <span m=''489000''>say</span>
  <span m=''489510''>addition</span> <span m=''489930''>of</span> <span m=''490030''>rational</span>
  <span m=''490420''>numbers.</span> <span m=''491820''>You can just</span> <span
  m=''492030''>say</span> <span m=''492320''>define,</span> <span m=''496550''>well,</span>
  <span m=''497120''>let''s</span> <span m=''497300''>say</span> <span m=''497640''>+RAT.</span>
  <span m=''501980''>Define</span> <span m=''502690''>+RAT,</span> <span m=''503180''>which</span>
  <span m=''503310''>will</span> <span m=''503410''>take</span> <span m=''503680''>in</span>
  <span m=''504150''>two</span> <span m=''504920''>rational</span> <span m=''505450''>numbers,</span>
  <span m=''507170''>x</span> <span m=''507410''>and</span> <span m=''507540''>y.</span>
  <span m=''508110''>x</span> <span m=''508310''>and</span> <span m=''508400''>y</span>
  <span m=''508620''>are</span> <span m=''509530''>each</span> <span m=''509940''>these</span>
  <span m=''510170''>clouds.</span> </p><p><span m=''511880''>And</span> <span m=''512010''>what</span>
  <span m=''512150''>does</span> <span m=''512270''>it</span> <span m=''512370''>do?</span>
  <span m=''512539''>Well,</span> <span m=''513179''>it''s</span> <span m=''513390''>going</span>
  <span m=''513510''>to</span> <span m=''514169''>return</span> <span m=''514610''>for</span>
  <span m=''514820''>us</span> <span m=''514950''>a</span> <span m=''515020''>rational</span>
  <span m=''515480''>number.</span> <span m=''520299''>What</span> <span m=''520480''>rational</span>
  <span m=''520890''>number</span> <span m=''521150''>is</span> <span m=''521360''>it?</span>
  <span m=''521460''>Well,</span> <span m=''522350''>we''ve</span> <span m=''522450''>got</span>
  <span m=''522640''>the</span> <span m=''522710''>formulas</span> <span m=''523220''>there.</span>
  <span m=''523659''>The</span> <span m=''523820''>numerator</span> <span m=''524380''>of</span>
  <span m=''524560''>it</span> <span m=''524920''>is</span> <span m=''525110''>the</span>
  <span m=''525200''>sum</span> <span m=''525690''>of</span> <span m=''527300''>the</span>
  <span m=''527510''>product</span> <span m=''529380''>of</span> <span m=''529500''>the</span>
  <span m=''529620''>numerator</span> <span m=''532180''>of</span> <span m=''532640''>x</span>
  <span m=''534150''>and</span> <span m=''535140''>the</span> <span m=''535310''>denominator</span>
  <span m=''536030''>of</span> <span m=''536120''>y.</span> <span m=''542580''>It''s</span>
  <span m=''542660''>one</span> <span m=''542870''>thing</span> <span m=''543010''>in</span>
  <span m=''543090''>the</span> <span m=''543170''>sum.</span> <span m=''543950''>And</span>
  <span m=''545000''>the</span> <span m=''545290''>other</span> <span m=''545460''>thing</span>
  <span m=''545710''>in the</span> <span m=''545770''>numerator</span> <span m=''546240''>is</span>
  <span m=''546720''>the</span> <span m=''546820''>product</span> <span m=''547240''>of</span>
  <span m=''547310''>the</span> <span m=''547380''>numerator</span> <span m=''550670''>of</span>
  <span m=''551050''>y</span> <span m=''552820''>and</span> <span m=''553340''>the</span>
  <span m=''553420''>denominator</span> <span m=''556550''>of</span> <span m=''556830''>x.</span>
  <span m=''559060''>The star, close the plus.</span> </p><p><span m=''560910''>Right,</span>
  <span m=''561050''>that''s</span> <span m=''561300''>the</span> <span m=''562130''>first</span>
  <span m=''562620''>argument</span> <span m=''563040''>to</span> <span m=''563130''>make-RAT,</span>
  <span m=''563580''>which</span> <span m=''563740''>is</span> <span m=''563830''>the</span>
  <span m=''563910''>numerator</span> <span m=''564490''>of</span> <span m=''564550''>the</span>
  <span m=''564640''>thing</span> <span m=''564810''>I''m</span> <span m=''564950''>constructing.</span>
  <span m=''566080''>And</span> <span m=''566510''>then</span> <span m=''567070''>the</span>
  <span m=''567230''>rest</span> <span m=''567510''>of</span> <span m=''567580''>the</span>
  <span m=''567670''>thing</span> <span m=''567870''>goes</span> <span m=''568050''>into</span>
  <span m=''568230''>make-RAT</span> <span m=''568650''>is</span> <span m=''568760''>the</span>
  <span m=''568860''>denominator</span> <span m=''569570''>of</span> <span m=''569660''>the</span>
  <span m=''570120''>answer,</span> <span m=''570610''>which</span> <span m=''570940''>is</span>
  <span m=''571040''>the</span> <span m=''571130''>product</span> <span m=''572670''>of</span>
  <span m=''572810''>the</span> <span m=''572950''>denominator</span> <span m=''575091''>of</span>
  <span m=''575530''>x</span> <span m=''577210''>and</span> <span m=''577320''>the</span>
  <span m=''577430''>denominator</span> <span m=''580610''>of</span> <span m=''580720''>y.</span>
  <span m=''582230''>Like that.</span> <span m=''586050''>OK?</span> <span m=''586500''>So</span>
  <span m=''586770''>there</span> <span m=''587010''>is</span> <span m=''588440''>the</span>
  <span m=''588550''>analog</span> <span m=''589080''>of</span> <span m=''590160''>doing</span>
  <span m=''590480''>rational</span> <span m=''590850''>number</span> <span m=''591090''>addition.</span>
  <span m=''591710''>And</span> <span m=''591870''>it''s</span> <span m=''592000''>no</span>
  <span m=''592120''>problem</span> <span m=''592550''>at</span> <span m=''592740''>all,</span>
  <span m=''593470''>assuming</span> <span m=''593880''>that</span> <span m=''594030''>we</span>
  <span m=''594170''>have</span> <span m=''594320''>these</span> <span m=''594520''>clouds.</span>
  </p><p><span m=''599020''>And</span> <span m=''599460''>of</span> <span m=''599520''>course,</span>
  <span m=''599720''>we</span> <span m=''599830''>can</span> <span m=''599970''>do</span>
  <span m=''600810''>multiplication</span> <span m=''601470''>in</span> <span m=''601540''>the</span>
  <span m=''601610''>same</span> <span m=''601900''>way.</span> <span m=''605570''>Define</span>
  <span m=''608200''>how</span> <span m=''608320''>to</span> <span m=''608390''>get</span>
  <span m=''608560''>the</span> <span m=''608640''>product</span> <span m=''609180''>of</span>
  <span m=''609340''>two</span> <span m=''609540''>rational</span> <span m=''610030''>numbers,</span>
  <span m=''611160''>call</span> <span m=''611380''>it</span> <span m=''611500''>*RAT.</span>
  <span m=''613080''>Takes</span> <span m=''613450''>in</span> <span m=''613760''>two</span>
  <span m=''614970''>of</span> <span m=''615140''>these</span> <span m=''615320''>clouds,</span>
  <span m=''615770''>x</span> <span m=''615980''>and</span> <span m=''616090''>y,</span>
  <span m=''619890''>it</span> <span m=''620040''>returns</span> <span m=''620420''>a</span>
  <span m=''620480''>rational</span> <span m=''620950''>number,</span> <span m=''621270''>make-RAT,</span>
  <span m=''624570''>whose</span> <span m=''624850''>numerator</span> <span m=''625450''>is</span>
  <span m=''626300''>the</span> <span m=''626570''>product</span> <span m=''627040''>of</span>
  <span m=''627100''>the</span> <span m=''627180''>numerators--</span> <span m=''630270''>numerator</span>
  <span m=''630510''>of</span> <span m=''630880''>x</span> <span m=''632020''>times</span>
  <span m=''633640''>the</span> <span m=''633850''>numerator</span> <span m=''635770''>of</span>
  <span m=''635940''>y.</span> <span m=''638170''>And</span> <span m=''638400''>the</span>
  <span m=''638490''>denominator</span> <span m=''639240''>of</span> <span m=''639460''>the</span>
  <span m=''640040''>thing</span> <span m=''640230''>it''s</span> <span m=''640370''>going</span>
  <span m=''640450''>to</span> <span m=''640530''>return</span> <span m=''641630''>is</span>
  <span m=''641780''>the</span> <span m=''641860''>product</span> <span m=''642280''>of</span>
  <span m=''642330''>the</span> <span m=''642420''>denominators.</span> </p><p><span
  m=''657930''>Well,</span> <span m=''659700''>except</span> <span m=''660040''>that</span>
  <span m=''660150''>I</span> <span m=''660240''>haven''t</span> <span m=''660500''>told</span>
  <span m=''660720''>you</span> <span m=''660840''>what</span> <span m=''660990''>these</span>
  <span m=''661170''>clouds</span> <span m=''661550''>are,</span> <span m=''662630''>that''s</span>
  <span m=''663130''>all</span> <span m=''663230''>there</span> <span m=''663390''>is</span>
  <span m=''663490''>to</span> <span m=''663690''>it.</span> <span m=''664510''>See,</span>
  <span m=''664660''>what</span> <span m=''664870''>did I</span> <span m=''664960''>do?</span>
  <span m=''665280''>I</span> <span m=''665500''>assumed</span> <span m=''666150''>by</span>
  <span m=''666340''>wishful</span> <span m=''666730''>thinking</span> <span m=''667730''>that</span>
  <span m=''668140''>I</span> <span m=''668210''>had</span> <span m=''668340''>a</span>
  <span m=''668380''>new</span> <span m=''668510''>kind</span> <span m=''668750''>of</span>
  <span m=''668820''>data</span> <span m=''669090''>object.</span> <span m=''670490''>And
  in</span> <span m=''670630''>particular,</span> <span m=''671190''>I</span> <span
  m=''671300''>assumed</span> <span m=''672080''>I</span> <span m=''672320''>had</span>
  <span m=''673630''>ways</span> <span m=''673950''>of</span> <span m=''674060''>creating</span>
  <span m=''674590''>these</span> <span m=''674780''>data</span> <span m=''675030''>objects.</span>
  <span m=''676360''>Make-RAT</span> <span m=''676980''>creates</span> <span m=''677450''>one</span>
  <span m=''677590''>of</span> <span m=''677670''>these</span> <span m=''677870''>things.</span>
  <span m=''678140''>This is</span> <span m=''678340''>called</span> <span m=''678550''>a</span>
  <span m=''678680''>constructor.</span> <span m=''685720''>All right,</span> <span
  m=''686090''>I have a thing</span> <span m=''686230''>that</span> <span m=''686940''>constructs</span>
  <span m=''688200''>such</span> <span m=''688630''>data</span> <span m=''688900''>objects.</span>
  <span m=''689750''>And</span> <span m=''689930''>then</span> <span m=''690030''>I</span>
  <span m=''690140''>assume</span> <span m=''691140''>I</span> <span m=''691300''>have</span>
  <span m=''691460''>things</span> <span m=''691840''>that,</span> <span m=''693020''>having</span>
  <span m=''693420''>made</span> <span m=''694090''>these</span> <span m=''694370''>things,</span>
  <span m=''694600''>I</span> <span m=''694670''>have</span> <span m=''694780''>ways</span>
  <span m=''694980''>of</span> <span m=''695050''>getting</span> <span m=''695270''>the</span>
  <span m=''695360''>parts</span> <span m=''695760''>out.</span> <span m=''695940''>Those</span>
  <span m=''696110''>are</span> <span m=''696190''>called</span> <span m=''697070''>selectors.</span>
  </p><p><span m=''702850''>And</span> <span m=''703000''>so</span> <span m=''703160''>formally,</span>
  <span m=''703530''>what</span> <span m=''703620''>I</span> <span m=''703720''>said</span>
  <span m=''703910''>is</span> <span m=''704000''>I</span> <span m=''704100''>assumed</span>
  <span m=''704900''>I</span> <span m=''705050''>had</span> <span m=''705210''>procedures</span>
  <span m=''705750''>that</span> <span m=''705960''>are</span> <span m=''706390''>constructors</span>
  <span m=''707270''>and</span> <span m=''707430''>selectors</span> <span m=''707990''>for</span>
  <span m=''708060''>these</span> <span m=''708250''>data</span> <span m=''708450''>objects,</span>
  <span m=''709160''>and</span> <span m=''709270''>then</span> <span m=''709390''>I</span>
  <span m=''709460''>went</span> <span m=''709580''>off</span> <span m=''709710''>and</span>
  <span m=''709800''>used</span> <span m=''710050''>them.</span> <span m=''712090''>That''s</span>
  <span m=''712470''>no</span> <span m=''712600''>different</span> <span m=''713010''>in</span>
  <span m=''713160''>kind</span> <span m=''713660''>from</span> <span m=''713890''>saying</span>
  <span m=''714180''>I</span> <span m=''714300''>assume</span> <span m=''714720''>I</span>
  <span m=''714800''>have</span> <span m=''714900''>a</span> <span m=''715010''>procedure</span>
  <span m=''715440''>good-enough,</span> <span m=''716380''>and</span> <span m=''716460''>I</span>
  <span m=''716550''>go</span> <span m=''716680''>use it</span> <span m=''717110''>to</span>
  <span m=''717240''>implement</span> <span m=''717630''>square</span> <span m=''718000''>root.</span>
  </p><p><span m=''720850''>OK,</span> <span m=''721050''>well</span> <span m=''721180''>before</span>
  <span m=''721470''>we</span> <span m=''721580''>go</span> <span m=''721760''>on,</span>
  <span m=''724930''>let''s</span> <span m=''725100''>ask</span> <span m=''725250''>the</span>
  <span m=''725330''>question</span> <span m=''725620''>of</span> <span m=''725700''>why</span>
  <span m=''726940''>do</span> <span m=''727190''>we</span> <span m=''727270''>want</span>
  <span m=''727360''>to</span> <span m=''727410''>do</span> <span m=''727550''>this</span>
  <span m=''727720''>in</span> <span m=''727800''>the</span> <span m=''727970''>first</span>
  <span m=''728150''>place?</span> <span m=''728660''>See,</span> <span m=''728840''>why</span>
  <span m=''729080''>do we</span> <span m=''729220''>want</span> <span m=''729580''>a</span>
  <span m=''729700''>procedure</span> <span m=''730220''>like</span> <span m=''731840''>+RAT</span>
  <span m=''733600''>that</span> <span m=''733860''>takes</span> <span m=''734170''>in</span>
  <span m=''734940''>two</span> <span m=''736340''>rational</span> <span m=''736920''>numbers</span>
  <span m=''738040''>and</span> <span m=''738170''>returns</span> <span m=''738610''>a</span>
  <span m=''738690''>rational</span> <span m=''739190''>number?</span> <span m=''740340''>See,</span>
  <span m=''740520''>another</span> <span m=''740760''>way</span> <span m=''740870''>to</span>
  <span m=''740980''>think</span> <span m=''741200''>about</span> <span m=''741470''>this</span>
  <span m=''741680''>is,</span> <span m=''741770''>well,</span> <span m=''741960''>here''s</span>
  <span m=''742140''>this</span> <span m=''742310''>formula.</span> <span m=''745160''>And</span>
  <span m=''745580''>I''ve</span> <span m=''745950''>also</span> <span m=''745970''>got</span>
  <span m=''746050''>to</span> <span m=''746140''>implement</span> <span m=''747420''>something</span>
  <span m=''747740''>that</span> <span m=''748060''>adds</span> <span m=''748260''>rational</span>
  <span m=''748720''>numbers.</span> </p><p><span m=''749890''>One</span> <span m=''750060''>other</span>
  <span m=''750250''>way</span> <span m=''750370''>to</span> <span m=''750470''>think</span>
  <span m=''750670''>about</span> <span m=''750930''>is,</span> <span m=''751110''>well,</span>
  <span m=''751310''>there''s</span> <span m=''751490''>this</span> <span m=''751680''>thing,</span>
  <span m=''752240''>and</span> <span m=''752340''>I</span> <span m=''752450''>type
  in</span> <span m=''752870''>four</span> <span m=''753140''>numbers,</span> <span
  m=''753540''>an</span> <span m=''753680''>n1,</span> <span m=''754150''>and a d1,</span>
  <span m=''754750''>and</span> <span m=''754850''>an</span> <span m=''754940''>n2,</span>
  <span m=''755210''>and a</span> <span m=''755460''>d2.</span> <span m=''756600''>And</span>
  <span m=''756820''>it</span> <span m=''756930''>sets</span> <span m=''757090''>some</span>
  <span m=''757270''>registers</span> <span m=''757720''>in</span> <span m=''757790''>the</span>
  <span m=''757860''>machine</span> <span m=''758510''>to</span> <span m=''760640''>this</span>
  <span m=''761120''>numerator</span> <span m=''761610''>and</span> <span m=''761730''>this</span>
  <span m=''761880''>denominator.</span> <span m=''762440''>So</span> <span m=''762570''>I</span>
  <span m=''762620''>might</span> <span m=''762830''>say,</span> <span m=''762920''>well,</span>
  <span m=''763380''>why don''t</span> <span m=''763520''>I</span> <span m=''763630''>just</span>
  <span m=''763840''>add</span> <span m=''764010''>rational</span> <span m=''764380''>numbers</span>
  <span m=''764690''>by</span> <span m=''764910''>I type in</span> <span m=''765250''>four</span>
  <span m=''765470''>numbers,</span> <span m=''766100''>numerators</span> <span m=''766600''>and</span>
  <span m=''766640''>denominators,</span> <span m=''767220''>and</span> <span m=''767320''>get</span>
  <span m=''767470''>out</span> <span m=''767620''>two</span> <span m=''767760''>numbers,</span>
  <span m=''768120''>which</span> <span m=''768270''>is</span> <span m=''768380''>a</span>
  <span m=''768600''>numerator</span> <span m=''768950''>and a</span> <span m=''769040''>denominator.</span>
  </p><p><span m=''771000''>Why</span> <span m=''771730''>are</span> <span m=''771790''>we</span>
  <span m=''771930''>worrying</span> <span m=''773380''>about</span> <span m=''773730''>building</span>
  <span m=''774020''>things</span> <span m=''774250''>like</span> <span m=''774450''>this</span>
  <span m=''774660''>anyway?</span> <span m=''778620''>Well,</span> <span m=''779250''>the</span>
  <span m=''779440''>answer</span> <span m=''779690''>is,</span> <span m=''780110''>suppose</span>
  <span m=''780570''>you</span> <span m=''780690''>want</span> <span m=''780820''>to</span>
  <span m=''780880''>think</span> <span m=''781150''>about</span> <span m=''782390''>expressing</span>
  <span m=''783030''>something</span> <span m=''783420''>like</span> <span m=''785890''>this,</span>
  <span m=''786090''>suppose</span> <span m=''786250''>I''d</span> <span m=''786360''>like</span>
  <span m=''786510''>to</span> <span m=''786620''>express</span> <span m=''788430''>the</span>
  <span m=''788580''>idea</span> <span m=''789030''>of</span> <span m=''790320''>taking</span>
  <span m=''790900''>two</span> <span m=''791100''>rational</span> <span m=''791540''>numbers,</span>
  <span m=''793330''>x</span> <span m=''793590''>plus</span> <span m=''793870''>y,</span>
  <span m=''794840''>say,</span> <span m=''795300''>and</span> <span m=''795770''>multiplying</span>
  <span m=''796320''>that</span> <span m=''797030''>by</span> <span m=''797190''>the</span>
  <span m=''797290''>sum</span> <span m=''800330''>of</span> <span m=''800520''>two</span>
  <span m=''800720''>other</span> <span m=''800920''>rational</span> <span m=''801310''>numbers.</span>
  <span m=''803670''>Well,</span> <span m=''803840''>the</span> <span m=''803900''>way</span>
  <span m=''804060''>I</span> <span m=''804190''>do</span> <span m=''804500''>it,</span>
  <span m=''805370''>having</span> <span m=''805660''>things</span> <span m=''805910''>like</span>
  <span m=''806160''>+RAT</span> <span m=''806930''>and</span> <span m=''807090''>*RAT,</span>
  <span m=''808266''>is</span> <span m=''808650''>I''d</span> <span m=''808890''>say,</span>
  <span m=''809040''>oh</span> <span m=''809150''>yeah,</span> <span m=''809540''>what</span>
  <span m=''809700''>that</span> <span m=''809920''>is</span> <span m=''811580''>is</span>
  <span m=''811770''>just</span> <span m=''812050''>the</span> <span m=''813320''>product.</span>
  <span m=''813930''>That''s</span> <span m=''814170''>*RAT</span> <span m=''816100''>of</span>
  <span m=''819880''>the</span> <span m=''820340''>sum</span> <span m=''821570''>of</span>
  <span m=''821810''>x</span> <span m=''822090''>and</span> <span m=''822230''>y</span>
  <span m=''824360''>and</span> <span m=''824860''>the sum</span> <span m=''827340''>of
  s</span> <span m=''828800''>and</span> <span m=''828980''>t.</span> </p><p><span
  m=''831570''>So</span> <span m=''831740''>except</span> <span m=''832040''>for</span>
  <span m=''832160''>syntax,</span> <span m=''834520''>I</span> <span m=''834640''>get</span>
  <span m=''834790''>an</span> <span m=''834880''>expression</span> <span m=''835940''>that</span>
  <span m=''836220''>looks</span> <span m=''836540''>like</span> <span m=''837020''>the</span>
  <span m=''837710''>way</span> <span m=''837870''>I</span> <span m=''837940''>want</span>
  <span m=''838100''>to</span> <span m=''838170''>think</span> <span m=''838380''>about</span>
  <span m=''838640''>it</span> <span m=''838730''>mathematically.</span> <span m=''839490''>I</span>
  <span m=''839930''>want</span> <span m=''840060''>to</span> <span m=''840190''>say</span>
  <span m=''840480''>there</span> <span m=''840840''>are</span> <span m=''841580''>two</span>
  <span m=''841750''>numbers.</span> <span m=''842080''>There''s</span> <span m=''842250''>a</span>
  <span m=''842310''>thing</span> <span m=''842690''>which</span> <span m=''842860''>is</span>
  <span m=''842980''>the</span> <span m=''843050''>sum</span> <span m=''843330''>of</span>
  <span m=''843430''>them,</span> <span m=''845750''>and</span> <span m=''845860''>there''s</span>
  <span m=''846010''>a</span> <span m=''846060''>thing</span> <span m=''846420''>which</span>
  <span m=''846590''>is</span> <span m=''846680''>the</span> <span m=''846760''>sum</span>
  <span m=''846960''>of</span> <span m=''847130''>these</span> <span m=''847300''>two.</span>
  <span m=''847490''>That''s</span> <span m=''848580''>this</span> <span m=''850260''>and</span>
  <span m=''850480''>this.</span> <span m=''850780''>And</span> <span m=''850880''>then</span>
  <span m=''850990''>I</span> <span m=''851070''>multiply</span> <span m=''851680''>them.</span>
  <span m=''852530''>So I get</span> <span m=''852650''>an</span> <span m=''852830''>expression</span>
  <span m=''853330''>that</span> <span m=''853460''>matches</span> <span m=''853790''>this</span>
  <span m=''853970''>expression.</span> </p><p><span m=''854640''>If</span> <span
  m=''854790''>I</span> <span m=''854850''>did</span> <span m=''855020''>the</span>
  <span m=''855130''>other</span> <span m=''855400''>thing,</span> <span m=''856170''>if</span>
  <span m=''856330''>I</span> <span m=''856390''>said,</span> <span m=''856600''>well,</span>
  <span m=''857090''>the</span> <span m=''857210''>way</span> <span m=''857450''>I</span>
  <span m=''857520''>want</span> <span m=''857660''>to</span> <span m=''857720''>think</span>
  <span m=''857920''>about</span> <span m=''858210''>this</span> <span m=''858450''>is</span>
  <span m=''858560''>I</span> <span m=''858640''>type</span> <span m=''858920''>into</span>
  <span m=''859150''>my</span> <span m=''859300''>machine</span> <span m=''859680''>four</span>
  <span m=''859960''>numbers,</span> <span m=''860770''>which</span> <span m=''860950''>are</span>
  <span m=''860990''>the</span> <span m=''861100''>numerators</span> <span m=''861670''>and
  the</span> <span m=''861760''>denominators</span> <span m=''862270''>of</span> <span
  m=''862460''>x</span> <span m=''862650''>and</span> <span m=''862750''>y,</span>
  <span m=''864140''>and</span> <span m=''864300''>then</span> <span m=''864540''>four</span>
  <span m=''864880''>more</span> <span m=''865130''>numbers,</span> <span m=''865620''>which</span>
  <span m=''865830''>are</span> <span m=''865860''>the</span> <span m=''865960''>numerators</span>
  <span m=''866440''>and</span> <span m=''866540''>denominators</span> <span m=''867030''>of</span>
  <span m=''867250''>s and</span> <span m=''867530''>t.</span> <span m=''869140''>And</span>
  <span m=''869230''>then</span> <span m=''869320''>what I''d</span> <span m=''869540''>be</span>
  <span m=''869640''>sitting</span> <span m=''869990''>with</span> <span m=''870170''>is,</span>
  <span m=''870320''>well,</span> <span m=''870460''>what</span> <span m=''870680''>would
  I</span> <span m=''870780''>do?</span> <span m=''871340''>I''d</span> <span m=''871550''>add</span>
  <span m=''871950''>these,</span> <span m=''872550''>and</span> <span m=''872650''>somehow</span>
  <span m=''873000''>I''d</span> <span m=''873130''>have</span> <span m=''873280''>to</span>
  <span m=''873380''>have</span> <span m=''873560''>two</span> <span m=''873750''>temporary</span>
  <span m=''874380''>variables,</span> <span m=''875640''>which</span> <span m=''875830''>are</span>
  <span m=''875860''>the</span> <span m=''875970''>numerators</span> <span m=''876440''>and</span>
  <span m=''876540''>denominators</span> <span m=''877010''>of</span> <span m=''877090''>this</span>
  <span m=''877180''>sum,</span> <span m=''878300''>and</span> <span m=''878410''>I''d</span>
  <span m=''878480''>go</span> <span m=''878700''>off</span> <span m=''878840''>and</span>
  <span m=''878940''>store</span> <span m=''879200''>them</span> <span m=''879370''>someplace.</span>
  </p><p><span m=''882500''>And then</span> <span m=''882710''>I''d</span> <span m=''882800''>go</span>
  <span m=''882980''>over</span> <span m=''883160''>here,</span> <span m=''883420''>I''d</span>
  <span m=''883500''>type</span> <span m=''883720''>in</span> <span m=''883830''>four</span>
  <span m=''884080''>more</span> <span m=''884280''>numbers,</span> <span m=''884610''>I''d</span>
  <span m=''884670''>get</span> <span m=''884840''>two</span> <span m=''885030''>more</span>
  <span m=''885270''>temporary</span> <span m=''885810''>variables,</span> <span m=''886720''>which</span>
  <span m=''887010''>are</span> <span m=''887050''>the</span> <span m=''887140''>numerators</span>
  <span m=''887620''>and</span> <span m=''887690''>denominators</span> <span m=''888260''>of</span>
  <span m=''888350''>s</span> <span m=''888520''>and</span> <span m=''888640''>t.</span>
  <span m=''890180''>And</span> <span m=''890290''>then</span> <span m=''890400''>finally,</span>
  <span m=''890870''>I</span> <span m=''890940''>put</span> <span m=''891160''>those</span>
  <span m=''891430''>together</span> <span m=''892200''>by</span> <span m=''892330''>multiplying</span>
  <span m=''892980''>them.</span> <span m=''895000''>You</span> <span m=''895080''>see,</span>
  <span m=''895180''>what''s</span> <span m=''895590''>starting</span> <span m=''895890''>to</span>
  <span m=''895940''>happen,</span> <span m=''896420''>there are</span> <span m=''896620''>all</span>
  <span m=''896710''>these</span> <span m=''896890''>temporary</span> <span m=''897370''>variables,</span>
  <span m=''898550''>which</span> <span m=''898830''>are</span> <span m=''900080''>sort</span>
  <span m=''900220''>of</span> <span m=''900370''>the</span> <span m=''900460''>guts</span>
  <span m=''901160''>of</span> <span m=''901340''>the</span> <span m=''901450''>internals</span>
  <span m=''902060''>of</span> <span m=''902190''>these</span> <span m=''902320''>rational</span>
  <span m=''902740''>numbers</span> <span m=''903140''>that</span> <span m=''903300''>start</span>
  <span m=''903780''>hanging</span> <span m=''904180''>out</span> <span m=''904320''>all</span>
  <span m=''904530''>over</span> <span m=''904710''>the</span> <span m=''904800''>system.</span>
  </p><p><span m=''906190''>And</span> <span m=''906320''>of</span> <span m=''906510''>course,</span>
  <span m=''906720''>if</span> <span m=''906860''>I</span> <span m=''906970''>had</span>
  <span m=''907080''>more and</span> <span m=''907310''>more</span> <span m=''907500''>complicated</span>
  <span m=''908050''>expressions,</span> <span m=''908580''>there''d</span> <span
  m=''908640''>be</span> <span m=''908780''>more</span> <span m=''909000''>and</span>
  <span m=''909060''>more</span> <span m=''909230''>guts</span> <span m=''909500''>hanging</span>
  <span m=''909830''>out</span> <span m=''910170''>that</span> <span m=''910380''>confuse</span>
  <span m=''910800''>my</span> <span m=''910940''>programming.</span> <span m=''913010''>And</span>
  <span m=''913150''>those</span> <span m=''913330''>of</span> <span m=''913410''>you
  who</span> <span m=''913600''>sort</span> <span m=''913790''>of</span> <span m=''913880''>programmed</span>
  <span m=''915050''>things</span> <span m=''915340''>like</span> <span m=''915620''>that,</span>
  <span m=''915920''>where</span> <span m=''916040''>you''re</span> <span m=''916180''>just</span>
  <span m=''916850''>adding</span> <span m=''917150''>numbers</span> <span m=''917480''>in</span>
  <span m=''917630''>assembly</span> <span m=''918040''>language,</span> <span m=''918440''>you</span>
  <span m=''918520''>sort</span> <span m=''918640''>of</span> <span m=''918760''>see</span>
  <span m=''918920''>you</span> <span m=''919060''>have</span> <span m=''919210''>to</span>
  <span m=''919300''>suddenly</span> <span m=''919630''>be</span> <span m=''919750''>concerned</span>
  <span m=''920170''>with</span> <span m=''920280''>these</span> <span m=''920450''>temporary</span>
  <span m=''920880''>variables.</span> </p><p><span m=''923040''>But</span> <span
  m=''923210''>more</span> <span m=''923830''>importantly</span> <span m=''926640''>than</span>
  <span m=''926770''>confusing</span> <span m=''927620''>my</span> <span m=''927770''>programming,</span>
  <span m=''928350''>they''re</span> <span m=''928470''>going</span> <span m=''928540''>to</span>
  <span m=''928620''>confuse</span> <span m=''929020''>my</span> <span m=''929150''>mind.</span>
  <span m=''929760''>Because</span> <span m=''930170''>the</span> <span m=''930250''>whole</span>
  <span m=''930500''>name</span> <span m=''930870''>of</span> <span m=''931090''>this</span>
  <span m=''931310''>game</span> <span m=''933440''>is</span> <span m=''933620''>that</span>
  <span m=''933820''>we''d</span> <span m=''933980''>like</span> <span m=''934410''>the</span>
  <span m=''934700''>programming</span> <span m=''935320''>language</span> <span m=''937130''>to</span>
  <span m=''937300''>express</span> <span m=''937740''>the</span> <span m=''937820''>concepts</span>
  <span m=''938440''>that</span> <span m=''938580''>we</span> <span m=''938750''>have</span>
  <span m=''938920''>in</span> <span m=''938990''>our</span> <span m=''939120''>heads,</span>
  <span m=''939670''>like</span> <span m=''940160''>rational</span> <span m=''940600''>numbers</span>
  <span m=''940920''>are</span> <span m=''941050''>things</span> <span m=''941350''>that</span>
  <span m=''941490''>you</span> <span m=''941640''>can</span> <span m=''941790''>add</span>
  <span m=''943050''>and</span> <span m=''943170''>then</span> <span m=''943300''>take</span>
  <span m=''943510''>that</span> <span m=''943660''>result</span> <span m=''944000''>and</span>
  <span m=''944090''>multiply</span> <span m=''944550''>them.</span> </p><p><span
  m=''948760''>Let''s</span> <span m=''948910''>break</span> <span m=''949090''>for</span>
  <span m=''949170''>questions.</span> <span m=''959570''>Yeah?</span> </p><p><span
  m=''960080''>AUDIENCE: I</span> <span m=''960630''>don''t</span> <span m=''960830''>quite</span>
  <span m=''961120''>see</span> <span m=''961320''>the need-</span> <span m=''962240''>when
  we</span> <span m=''962550''>had</span> <span m=''962710''>make-RAT</span> <span
  m=''963240''>with</span> <span m=''963510''>the numerator</span> <span m=''964060''>and</span>
  <span m=''964160''>denominator,</span> <span m=''964460''>we</span> <span m=''964600''>had</span>
  <span m=''964800''>to</span> <span m=''964870''>have</span> <span m=''965150''>the</span>
  <span m=''965200''>numerator</span> <span m=''965340''>and</span> <span m=''965670''>denominator</span>
  <span m=''966050''>to</span> <span m=''966130''>pass as</span> <span m=''966550''>parameters</span>
  <span m=''967440''>to</span> <span m=''967590''>create</span> <span m=''967970''>the</span>
  <span m=''968050''>cloud,</span> <span m=''968770''>and</span> <span m=''969020''>then
  we</span> <span m=''969290''>extracted</span> <span m=''969640''>to get</span> <span
  m=''969990''>back</span> <span m=''970240''>what we</span> <span m=''970420''>had</span>
  <span m=''970620''>to have</span> <span m=''970885''>originally.</span> </p><p><span
  m=''971720''>PROFESSOR: That''s</span> <span m=''971980''>right.</span> <span m=''973740''>So</span>
  <span m=''973960''>the</span> <span m=''974050''>question</span> <span m=''974420''>is,</span>
  <span m=''975100''>I</span> <span m=''975230''>sort</span> <span m=''975350''>of</span>
  <span m=''975480''>have</span> <span m=''975770''>the</span> <span m=''975840''>numerator
  and the</span> <span m=''976310''>denominator,</span> <span m=''977370''>why</span>
  <span m=''977690''>am</span> <span m=''977830''>I</span> <span m=''978860''>worrying</span>
  <span m=''979270''>about</span> <span m=''979490''>having</span> <span m=''979770''>the</span>
  <span m=''979840''>cloud</span> <span m=''980480''>given</span> <span m=''980690''>that</span>
  <span m=''980800''>I</span> <span m=''980890''>have</span> <span m=''981060''>to</span>
  <span m=''981150''>get</span> <span m=''981320''>the</span> <span m=''981410''>pieces</span>
  <span m=''981750''>out?</span> <span m=''983500''>That''s</span> <span m=''984000''>sort</span>
  <span m=''984150''>of</span> <span m=''984300''>what</span> <span m=''984410''>I</span>
  <span m=''984470''>tried</span> <span m=''984710''>to</span> <span m=''984750''>say</span>
  <span m=''984940''>at</span> <span m=''985050''>the</span> <span m=''985260''>end,</span>
  <span m=''985490''>but</span> <span m=''985630''>let</span> <span m=''985740''>me</span>
  <span m=''986100''>try</span> <span m=''986310''>and</span> <span m=''986390''>say</span>
  <span m=''986550''>it</span> <span m=''986630''>again,</span> <span m=''986920''>because</span>
  <span m=''987070''>that''s</span> <span m=''987250''>really</span> <span m=''987540''>the</span>
  <span m=''987640''>crucial</span> <span m=''988010''>question.</span> </p><p><span
  m=''989390''>The</span> <span m=''989740''>point</span> <span m=''990000''>is,</span>
  <span m=''990170''>I</span> <span m=''990270''>want</span> <span m=''990370''>to</span>
  <span m=''990470''>carry</span> <span m=''990860''>this</span> <span m=''991050''>numerator</span>
  <span m=''991305''>and</span> <span m=''991560''>denominator</span> <span m=''992540''>around</span>
  <span m=''994400''>together</span> <span m=''994910''>all</span> <span m=''995030''>the</span>
  <span m=''995150''>time.</span> <span m=''996816''>And</span> <span m=''997260''>it''s</span>
  <span m=''997500''>almost</span> <span m=''997830''>as</span> <span m=''997930''>if</span>
  <span m=''998100''>I</span> <span m=''998670''>want</span> <span m=''998780''>to</span>
  <span m=''998900''>know,</span> <span m=''999030''>yeah,</span> <span m=''999300''>there''s</span>
  <span m=''999510''>a</span> <span m=''999570''>numerator</span> <span m=''999720''>and</span>
  <span m=''1000020''>denominator</span> <span m=''1000590''>in</span> <span m=''1000710''>there,</span>
  <span m=''1000840''>but</span> <span m=''1000990''>also,</span> <span m=''1001880''>I</span>
  <span m=''1002000''>would</span> <span m=''1002130''>like</span> <span m=''1002350''>to</span>
  <span m=''1003710''>say,</span> <span m=''1004720''>fine,</span> <span m=''1005730''>but</span>
  <span m=''1006610''>from</span> <span m=''1006800''>another</span> <span m=''1007140''>point</span>
  <span m=''1007420''>of</span> <span m=''1007490''>view,</span> <span m=''1008000''>that''s</span>
  <span m=''1008750''>x.</span> <span m=''1010180''>And</span> <span m=''1010380''>I</span>
  <span m=''1010450''>carry</span> <span m=''1010800''>x</span> <span m=''1011040''>around,</span>
  <span m=''1011410''>and I</span> <span m=''1011530''>name</span> <span m=''1011790''>it
  as</span> <span m=''1012020''>x,</span> <span m=''1012250''>and I</span> <span m=''1012360''>hold</span>
  <span m=''1012720''>it.</span> <span m=''1013040''>And</span> <span m=''1013170''>I</span>
  <span m=''1013230''>can</span> <span m=''1013360''>say</span> <span m=''1013560''>things</span>
  <span m=''1013800''>like,</span> <span m=''1014300''>the</span> <span m=''1014480''>sum</span>
  <span m=''1014750''>of</span> <span m=''1014880''>x</span> <span m=''1015060''>and</span>
  <span m=''1015160''>y,</span> <span m=''1016140''>rather</span> <span m=''1016370''>than</span>
  <span m=''1016520''>just</span> <span m=''1016740''>have--</span> <span m=''1017050''>see,</span>
  <span m=''1017180''>it''s</span> <span m=''1017290''>not</span> <span m=''1017460''>so</span>
  <span m=''1017570''>bad</span> <span m=''1017860''>when</span> <span m=''1017990''>I</span>
  <span m=''1018060''>only</span> <span m=''1018230''>think</span> <span m=''1018390''>about</span>
  <span m=''1018430''>x,</span> <span m=''1019180''>but</span> <span m=''1019750''>if
  I</span> <span m=''1019820''>have</span> <span m=''1020040''>a</span> <span m=''1020120''>system</span>
  <span m=''1020470''>with</span> <span m=''1020600''>10</span> <span m=''1020840''>rational</span>
  <span m=''1021250''>numbers,</span> <span m=''1021870''>suddenly</span> <span m=''1022240''>I</span>
  <span m=''1022360''>have</span> <span m=''1022480''>20</span> <span m=''1022760''>numerators</span>
  <span m=''1023220''>and</span> <span m=''1023310''>denominators,</span> <span m=''1024260''>which</span>
  <span m=''1024440''>are</span> <span m=''1024500''>not</span> <span m=''1024770''>necessarily--</span>
  <span m=''1025930''>if I</span> <span m=''1026030''>don''t</span> <span m=''1026220''>link</span>
  <span m=''1026410''>them,</span> <span m=''1026609''>then</span> <span m=''1026710''>it''s</span>
  <span m=''1026819''>just</span> <span m=''1026980''>20</span> <span m=''1027210''>arbitrary</span>
  <span m=''1027630''>numbers</span> <span m=''1028609''>that are</span> <span m=''1028810''>not</span>
  <span m=''1029000''>linked</span> <span m=''1029250''>in</span> <span m=''1029339''>any</span>
  <span m=''1029490''>particular</span> <span m=''1029970''>way.</span> </p><p><span
  m=''1030560''>It''s</span> <span m=''1031400''>a</span> <span m=''1031460''>lot</span>
  <span m=''1031800''>like</span> <span m=''1032700''>saying,</span> <span m=''1033280''>well,
  I</span> <span m=''1033480''>have</span> <span m=''1033630''>these</span> <span
  m=''1033790''>instructions</span> <span m=''1034319''>that</span> <span m=''1034400''>are</span>
  <span m=''1034480''>the</span> <span m=''1034599''>body</span> <span m=''1034910''>of</span>
  <span m=''1034970''>the</span> <span m=''1035060''>procedures,</span> <span m=''1035589''>why</span>
  <span m=''1035750''>do</span> <span m=''1035849''>I</span> <span m=''1035900''>want</span>
  <span m=''1036040''>to</span> <span m=''1036099''>package</span> <span m=''1036500''>them</span>
  <span m=''1036640''>and</span> <span m=''1036730''>say</span> <span m=''1036880''>it''s</span>
  <span m=''1037040''>the</span> <span m=''1037119''>procedure?</span> <span m=''1037970''>It''s</span>
  <span m=''1038020''>exactly</span> <span m=''1038460''>the</span> <span m=''1038550''>same</span>
  <span m=''1038780''>idea.</span> </p><p><span m=''1051875''>No?</span> <span m=''1053840''>OK.</span>
  <span m=''1055120''>Let''s</span> <span m=''1055380''>break, let''s</span> <span
  m=''1055640''>just</span> <span m=''1055840''>stretch</span> <span m=''1056250''>and
  get</span> <span m=''1056460''>somebody--</span> <span m=''1056870''>[INAUDIBLE]</span>
  </p><p><span m=''1058349''>[MUSIC PLAYING]</span> </p><p><span m=''1107080''>OK,</span>
  <span m=''1107300''>well,</span> <span m=''1107450''>we''ve</span> <span m=''1107580''>been</span>
  <span m=''1107710''>working</span> <span m=''1108050''>on</span> <span m=''1108210''>this</span>
  <span m=''1108370''>rational</span> <span m=''1109360''>number</span> <span m=''1109790''>arithmetic</span>
  <span m=''1110310''>system,</span> <span m=''1111810''>and</span> <span m=''1112065''>then</span>
  <span m=''1112320''>what</span> <span m=''1112440''>we</span> <span m=''1112550''>did,</span>
  <span m=''1114160''>the</span> <span m=''1114230''>important</span> <span m=''1114590''>thing</span>
  <span m=''1114730''>about</span> <span m=''1114930''>what</span> <span m=''1115070''>we</span>
  <span m=''1115190''>did,</span> <span m=''1115720''>is</span> <span m=''1115850''>we</span>
  <span m=''1115970''>thought</span> <span m=''1116220''>about</span> <span m=''1116380''>the</span>
  <span m=''1116540''>problem</span> <span m=''1117310''>by</span> <span m=''1117430''>breaking</span>
  <span m=''1117820''>it</span> <span m=''1117900''>into</span> <span m=''1118120''>two</span>
  <span m=''1118300''>pieces.</span> <span m=''1120160''>We</span> <span m=''1120390''>said,</span>
  <span m=''1120820''>assume</span> <span m=''1121320''>there</span> <span m=''1121470''>is
  this</span> <span m=''1121680''>contract</span> <span m=''1122210''>with</span>
  <span m=''1122350''>George,</span> <span m=''1123410''>and</span> <span m=''1123580''>George</span>
  <span m=''1123890''>has</span> <span m=''1124070''>figured</span> <span m=''1124390''>out</span>
  <span m=''1124580''>the</span> <span m=''1124660''>way</span> <span m=''1125230''>to</span>
  <span m=''1125400''>how</span> <span m=''1125500''>to</span> <span m=''1125600''>construct</span>
  <span m=''1126010''>these</span> <span m=''1126200''>clouds,</span> <span m=''1127920''>provided</span>
  <span m=''1128480''>us</span> <span m=''1128620''>procedures</span> <span m=''1129560''>make-RAT,</span>
  <span m=''1130510''>which</span> <span m=''1130690''>was</span> <span m=''1130800''>a</span>
  <span m=''1130900''>constructor,</span> <span m=''1132110''>and</span> <span m=''1132360''>selectors,</span>
  <span m=''1133730''>which</span> <span m=''1133910''>are</span> <span m=''1133970''>numerator
  and</span> <span m=''1134340''>denominator.</span> <span m=''1135040''>And</span>
  <span m=''1135160''>then</span> <span m=''1135290''>in</span> <span m=''1135350''>terms</span>
  <span m=''1135620''>of</span> <span m=''1135720''>that,</span> <span m=''1135830''>we</span>
  <span m=''1135930''>went</span> <span m=''1136100''>off</span> <span m=''1136320''>and</span>
  <span m=''1137050''>implemented</span> <span m=''1137580''>addition</span> <span
  m=''1137900''>and</span> <span m=''1137990''>multiplication</span> <span m=''1138580''>of</span>
  <span m=''1138670''>rational</span> <span m=''1139030''>numbers.</span> </p><p><span
  m=''1140630''>Well,</span> <span m=''1141390''>now</span> <span m=''1141500''>let''s</span>
  <span m=''1141680''>go</span> <span m=''1141770''>look</span> <span m=''1141920''>at</span>
  <span m=''1142000''>George''s</span> <span m=''1142360''>problem.</span> <span m=''1143640''>How</span>
  <span m=''1143790''>can</span> <span m=''1143930''>we</span> <span m=''1144040''>go</span>
  <span m=''1144550''>and</span> <span m=''1144730''>package</span> <span m=''1145210''>together</span>
  <span m=''1145660''>a</span> <span m=''1145770''>numerator</span> <span m=''1146260''>and</span>
  <span m=''1146340''>a</span> <span m=''1146910''>denominator</span> <span m=''1147210''>and</span>
  <span m=''1147510''>actually</span> <span m=''1147890''>make</span> <span m=''1148150''>one</span>
  <span m=''1148300''>of</span> <span m=''1148370''>these</span> <span m=''1148570''>clouds?</span>
  <span m=''1149360''>See,</span> <span m=''1149440''>what</span> <span m=''1149550''>we</span>
  <span m=''1149650''>need</span> <span m=''1150050''>is</span> <span m=''1150760''>a</span>
  <span m=''1150880''>kind</span> <span m=''1151030''>of</span> <span m=''1151180''>glue,</span>
  <span m=''1154430''>a</span> <span m=''1154560''>glue</span> <span m=''1154860''>for</span>
  <span m=''1155010''>data</span> <span m=''1155300''>objects</span> <span m=''1155760''>that</span>
  <span m=''1155860''>allows</span> <span m=''1156240''>us</span> <span m=''1156330''>to</span>
  <span m=''1156440''>put</span> <span m=''1156630''>things</span> <span m=''1156830''>together.</span>
  <span m=''1158040''>And</span> <span m=''1159410''>Lisp</span> <span m=''1159710''>provides</span>
  <span m=''1160160''>such</span> <span m=''1160400''>a</span> <span m=''1160450''>glue,</span>
  <span m=''1161310''>and</span> <span m=''1161790''>that</span> <span m=''1162280''>glue</span>
  <span m=''1163170''>is</span> <span m=''1163340''>called</span> <span m=''1163630''>list</span>
  <span m=''1163850''>structure.</span> <span m=''1170410''>List</span> <span m=''1170720''>structure</span>
  <span m=''1171170''>is</span> <span m=''1171280''>a</span> <span m=''1171330''>way</span>
  <span m=''1171850''>of</span> <span m=''1172170''>gluing</span> <span m=''1172620''>things</span>
  <span m=''1172940''>together,</span> <span m=''1175490''>and</span> <span m=''1175700''>more</span>
  <span m=''1175820''>precisely,</span> <span m=''1176600''>Lisp</span> <span m=''1177690''>provides</span>
  <span m=''1178520''>a</span> <span m=''1178610''>way</span> <span m=''1178890''>of</span>
  <span m=''1179010''>constructing</span> <span m=''1179620''>things</span> <span
  m=''1180750''>called</span> <span m=''1181280''>pairs.</span> </p><p><span m=''1184750''>There''s</span>
  <span m=''1186650''>a</span> <span m=''1186710''>primitive</span> <span m=''1187690''>operator</span>
  <span m=''1189060''>in</span> <span m=''1189230''>Lisp</span> <span m=''1190460''>called</span>
  <span m=''1190730''>cons.</span> <span m=''1192222''>We can</span> <span m=''1192680''>take</span>
  <span m=''1192910''>a</span> <span m=''1193050''>look</span> <span m=''1193200''>at</span>
  <span m=''1193340''>it.</span> <span m=''1194920''>There''s</span> <span m=''1195490''>a</span>
  <span m=''1195560''>thing</span> <span m=''1195730''>called</span> <span m=''1196890''>cons.</span>
  <span m=''1200620''>Cons</span> <span m=''1201210''>is</span> <span m=''1201380''>an</span>
  <span m=''1201450''>operator</span> <span m=''1202340''>which</span> <span m=''1202530''>takes</span>
  <span m=''1202810''>in two</span> <span m=''1203160''>arguments</span> <span m=''1203650''>called</span>
  <span m=''1203880''>x</span> <span m=''1204060''>and</span> <span m=''1204160''>y,</span>
  <span m=''1206540''>and</span> <span m=''1206700''>it</span> <span m=''1206750''>returns</span>
  <span m=''1207200''>for</span> <span m=''1207370''>us</span> <span m=''1207580''>a</span>
  <span m=''1207860''>thing</span> <span m=''1208110''>called</span> <span m=''1208460''>a
  pair.</span> <span m=''1211510''>All right,</span> <span m=''1212540''>so a thing</span>
  <span m=''1212830''>called</span> <span m=''1213060''>a</span> <span m=''1213100''>pair</span>
  <span m=''1215070''>that</span> <span m=''1215200''>has</span> <span m=''1215370''>a</span>
  <span m=''1215430''>first</span> <span m=''1215730''>part</span> <span m=''1217300''>a</span>
  <span m=''1217520''>second</span> <span m=''1217850''>part.</span> </p><p><span
  m=''1222250''>So</span> <span m=''1222390''>cons</span> <span m=''1222920''>takes
  two</span> <span m=''1223060''>objects.</span> <span m=''1225450''>There''s</span>
  <span m=''1225610''>a</span> <span m=''1225660''>thing</span> <span m=''1225820''>called</span>
  <span m=''1226060''>a pair.</span> <span m=''1226780''>The</span> <span m=''1227010''>first</span>
  <span m=''1227230''>part</span> <span m=''1227360''>of</span> <span m=''1227480''>the</span>
  <span m=''1227540''>cons</span> <span m=''1227800''>is</span> <span m=''1228300''>x,</span>
  <span m=''1229990''>and</span> <span m=''1230270''>the</span> <span m=''1230330''>second</span>
  <span m=''1230610''>part</span> <span m=''1230700''>of</span> <span m=''1230800''>the</span>
  <span m=''1230870''>cons</span> <span m=''1231170''>is</span> <span m=''1231270''>y.</span>
  <span m=''1231600''>And that''s</span> <span m=''1231870''>what</span> <span m=''1231980''>it</span>
  <span m=''1232090''>builds.</span> <span m=''1234090''>And</span> <span m=''1234300''>then</span>
  <span m=''1234580''>we</span> <span m=''1234770''>also</span> <span m=''1235030''>assume</span>
  <span m=''1235200''>we</span> <span m=''1235320''>have</span> <span m=''1235450''>ways</span>
  <span m=''1235660''>of</span> <span m=''1235740''>getting</span> <span m=''1236030''>things</span>
  <span m=''1236290''>out.</span> <span m=''1236880''>If</span> <span m=''1237040''>you''re</span>
  <span m=''1237200''>given</span> <span m=''1237740''>a pair,</span> <span m=''1238150''>there''s</span>
  <span m=''1238360''>a</span> <span m=''1238410''>thing</span> <span m=''1238570''>called</span>
  <span m=''1238840''>car,</span> <span m=''1241820''>and</span> <span m=''1242130''>car
  of</span> <span m=''1242510''>a pair,</span> <span m=''1242820''>p,</span> <span
  m=''1243630''>gives you</span> <span m=''1244000''>out</span> <span m=''1244250''>the</span>
  <span m=''1244350''>first</span> <span m=''1244640''>part</span> <span m=''1244760''>of</span>
  <span m=''1244870''>the</span> <span m=''1244960''>pair,</span> <span m=''1245245''>p.</span>
  <span m=''1246640''>And</span> <span m=''1246800''>there''s</span> <span m=''1246940''>a</span>
  <span m=''1247000''>thing</span> <span m=''1247130''>called</span> <span m=''1247330''>cdr,</span>
  <span m=''1247970''>and</span> <span m=''1248270''>cdr</span> <span m=''1248540''>of</span>
  <span m=''1248610''>the</span> <span m=''1248700''>pair,</span> <span m=''1248985''>p,</span>
  <span m=''1249650''>gives</span> <span m=''1249860''>you</span> <span m=''1249990''>the</span>
  <span m=''1250790''>second</span> <span m=''1251110''>part</span> <span m=''1251230''>of</span>
  <span m=''1251360''>the</span> <span m=''1251430''>pair,</span> <span m=''1251670''>p.</span>
  <span m=''1254310''>OK, so</span> <span m=''1254750''>that''s</span> <span m=''1255180''>how</span>
  <span m=''1255270''>we</span> <span m=''1255400''>construct</span> <span m=''1255910''>things.</span>
  </p><p><span m=''1256710''>There''s</span> <span m=''1257010''>also</span> <span
  m=''1258270''>a</span> <span m=''1259320''>conventional</span> <span m=''1259910''>way</span>
  <span m=''1260550''>of</span> <span m=''1260820''>drawing</span> <span m=''1261180''>pictures</span>
  <span m=''1261620''>of</span> <span m=''1261720''>these</span> <span m=''1261960''>things.</span>
  <span m=''1262800''>Just</span> <span m=''1262990''>like</span> <span m=''1263160''>we</span>
  <span m=''1263290''>write</span> <span m=''1263510''>down</span> <span m=''1267040''>that</span>
  <span m=''1267890''>as</span> <span m=''1268070''>the</span> <span m=''1268150''>conventional</span>
  <span m=''1268720''>way</span> <span m=''1268930''>of</span> <span m=''1269070''>writing</span>
  <span m=''1270140''>Plato''s</span> <span m=''1270650''>idea</span> <span m=''1271180''>of</span>
  <span m=''1271540''>two,</span> <span m=''1273740''>the</span> <span m=''1273870''>way</span>
  <span m=''1274010''>we</span> <span m=''1274910''>could</span> <span m=''1276890''>draw</span>
  <span m=''1277400''>a</span> <span m=''1277480''>diagram</span> <span m=''1278420''>to</span>
  <span m=''1278590''>represent</span> <span m=''1279100''>cons</span> <span m=''1279465''>of</span>
  <span m=''1279830''>two and three</span> <span m=''1280620''>is</span> <span m=''1280730''>like</span>
  <span m=''1280950''>this.</span> <span m=''1281510''>We</span> <span m=''1281980''>draw</span>
  <span m=''1282110''>a</span> <span m=''1282230''>little</span> <span m=''1282420''>box.</span>
  <span m=''1283912''>And</span> <span m=''1284310''>so</span> <span m=''1284480''>here''s</span>
  <span m=''1284700''>the</span> <span m=''1284770''>box</span> <span m=''1285070''>we''re</span>
  <span m=''1285170''>talking</span> <span m=''1285550''>about,</span> <span m=''1286510''>and</span>
  <span m=''1286740''>this</span> <span m=''1286880''>box</span> <span m=''1287140''>has</span>
  <span m=''1287290''>two</span> <span m=''1287480''>arrows</span> <span m=''1287890''>coming</span>
  <span m=''1288240''>out</span> <span m=''1288330''>of</span> <span m=''1288410''>it.</span>
  <span m=''1290070''>And say</span> <span m=''1290260''>the</span> <span m=''1290670''>first</span>
  <span m=''1292630''>part</span> <span m=''1292980''>of</span> <span m=''1293090''>this</span>
  <span m=''1293850''>pair</span> <span m=''1294205''>is</span> <span m=''1294560''>2,</span>
  <span m=''1295180''>and</span> <span m=''1295350''>the</span> <span m=''1295530''>second</span>
  <span m=''1295700''>part</span> <span m=''1295890''>of</span> <span m=''1295960''>this</span>
  <span m=''1296080''>pair is</span> <span m=''1296450''>3.</span> <span m=''1298250''>And</span>
  <span m=''1298710''>this</span> <span m=''1299800''>notation</span> <span m=''1300330''>has</span>
  <span m=''1300520''>a</span> <span m=''1300570''>name,</span> <span m=''1300830''>it''s</span>
  <span m=''1300950''>called</span> <span m=''1301180''>box</span> <span m=''1304080''>and</span>
  <span m=''1304220''>pointer</span> <span m=''1304580''>notation.</span> </p><p><span
  m=''1316050''>By the way,</span> <span m=''1316370''>let</span> <span m=''1316450''>me</span>
  <span m=''1316540''>say</span> <span m=''1316700''>right</span> <span m=''1316980''>now</span>
  <span m=''1317320''>that</span> <span m=''1317610''>a</span> <span m=''1317700''>lot</span>
  <span m=''1317800''>of</span> <span m=''1317890''>people</span> <span m=''1318150''>get</span>
  <span m=''1318340''>confused</span> <span m=''1318720''>that</span> <span m=''1318840''>there''s</span>
  <span m=''1319010''>some</span> <span m=''1319870''>significance</span> <span m=''1320590''>to
  the</span> <span m=''1320740''>geometric</span> <span m=''1321650''>way</span> <span
  m=''1321840''>I</span> <span m=''1321930''>drew</span> <span m=''1322110''>these</span>
  <span m=''1322320''>pointers,</span> <span m=''1322970''>the</span> <span m=''1323100''>directions.</span>
  <span m=''1323640''>Like</span> <span m=''1324080''>some</span> <span m=''1324240''>people</span>
  <span m=''1324470''>think</span> <span m=''1324600''>it''d</span> <span m=''1324660''>be</span>
  <span m=''1324820''>different</span> <span m=''1325200''>if</span> <span m=''1325300''>I</span>
  <span m=''1325630''>took</span> <span m=''1325910''>this</span> <span m=''1326090''>pointer</span>
  <span m=''1326410''>and</span> <span m=''1326500''>turned</span> <span m=''1326720''>it</span>
  <span m=''1326800''>up</span> <span m=''1326940''>here,</span> <span m=''1327650''>and</span>
  <span m=''1327790''>put</span> <span m=''1327920''>the</span> <span m=''1328010''>3</span>
  <span m=''1328250''>out</span> <span m=''1328420''>here.</span> <span m=''1328660''>That</span>
  <span m=''1328810''>has</span> <span m=''1328940''>no</span> <span m=''1329100''>significance.</span>
  <span m=''1330760''>All right?</span> <span m=''1330940''>It''s</span> <span m=''1331580''>merely</span>
  <span m=''1331960''>you</span> <span m=''1332110''>have</span> <span m=''1332260''>a</span>
  <span m=''1332310''>bunch</span> <span m=''1332540''>of</span> <span m=''1332640''>arrows,</span>
  <span m=''1333040''>these</span> <span m=''1333240''>pointers,</span> <span m=''1334470''>and</span>
  <span m=''1334560''>the</span> <span m=''1334640''>boxes.</span> <span m=''1335090''>The</span>
  <span m=''1335200''>only</span> <span m=''1335500''>issue</span> <span m=''1335840''>is</span>
  <span m=''1336540''>how</span> <span m=''1336700''>they''re</span> <span m=''1336840''>connected,</span>
  <span m=''1337390''>not</span> <span m=''1338050''>the</span> <span m=''1338270''>geometric</span>
  <span m=''1338860''>arrangement</span> <span m=''1339330''>of</span> <span m=''1339420''>whether</span>
  <span m=''1339670''>I</span> <span m=''1339720''>write</span> <span m=''1339950''>the</span>
  <span m=''1340030''>pointer</span> <span m=''1340400''>across,</span> <span m=''1340790''>or</span>
  <span m=''1340900''>up, or</span> <span m=''1341160''>down.</span> </p><p><span
  m=''1343160''>Now it''s</span> <span m=''1344010''>completely</span> <span m=''1344430''>un-obvious,</span>
  <span m=''1346020''>probably,</span> <span m=''1346490''>why</span> <span m=''1346700''>that''s</span>
  <span m=''1346920''>called</span> <span m=''1347180''>list</span> <span m=''1347290''>structure.</span>
  <span m=''1348870''>We''re</span> <span m=''1348990''>not</span> <span m=''1349150''>actually</span>
  <span m=''1349400''>going</span> <span m=''1349470''>to</span> <span m=''1349540''>talk</span>
  <span m=''1349790''>about</span> <span m=''1350040''>that</span> <span m=''1350220''>today.</span>
  <span m=''1350420''>We''ll</span> <span m=''1351020''>see</span> <span m=''1351160''>that</span>
  <span m=''1351330''>next</span> <span m=''1351570''>time.</span> </p><p><span m=''1357870''>So</span>
  <span m=''1358060''>those</span> <span m=''1358290''>are</span> <span m=''1358400''>pairs,</span>
  <span m=''1359740''>there''s</span> <span m=''1359970''>cons</span> <span m=''1360320''>that</span>
  <span m=''1360470''>constructs</span> <span m=''1360980''>them.</span> <span m=''1361740''>And</span>
  <span m=''1362510''>what</span> <span m=''1362720''>I''m</span> <span m=''1362830''>going</span>
  <span m=''1362900''>to</span> <span m=''1362970''>know</span> <span m=''1363190''>about</span>
  <span m=''1363480''>cons,</span> <span m=''1364390''>and</span> <span m=''1364570''>car,</span>
  <span m=''1364910''>and cdr,</span> <span m=''1365640''>is</span> <span m=''1366570''>precisely</span>
  <span m=''1367180''>that</span> <span m=''1367340''>if</span> <span m=''1367450''>I</span>
  <span m=''1368080''>have</span> <span m=''1368200''>any</span> <span m=''1368850''>x</span>
  <span m=''1369090''>and</span> <span m=''1369200''>y,</span> <span m=''1370070''>all
  right,</span> <span m=''1371170''>if</span> <span m=''1371340''>I</span> <span m=''1371420''>have</span>
  <span m=''1371510''>any</span> <span m=''1371920''>things</span> <span m=''1371990''>x</span>
  <span m=''1372190''>and</span> <span m=''1372300''>y,</span> <span m=''1373990''>and</span>
  <span m=''1374220''>I</span> <span m=''1374290''>use</span> <span m=''1374510''>cons</span>
  <span m=''1375090''>to</span> <span m=''1375380''>construct</span> <span m=''1375800''>a</span>
  <span m=''1375860''>pair,</span> <span m=''1379420''>then</span> <span m=''1380040''>the</span>
  <span m=''1380200''>car</span> <span m=''1380610''>of that</span> <span m=''1380930''>pair</span>
  <span m=''1381200''>is</span> <span m=''1381300''>going</span> <span m=''1381410''>to</span>
  <span m=''1381530''>be</span> <span m=''1381640''>x,</span> <span m=''1382770''>the</span>
  <span m=''1382910''>thing I</span> <span m=''1382990''>put in,</span> <span m=''1383920''>and</span>
  <span m=''1384030''>the</span> <span m=''1384140''>cdr of</span> <span m=''1384460''>that</span>
  <span m=''1384710''>pair</span> <span m=''1385220''>is</span> <span m=''1385370''>going</span>
  <span m=''1385460''>to</span> <span m=''1385560''>be</span> <span m=''1385650''>y.</span>
  <span m=''1387790''>That''s</span> <span m=''1388010''>the</span> <span m=''1388600''>behavior</span>
  <span m=''1389210''>of</span> <span m=''1389380''>these</span> <span m=''1389550''>operators,</span>
  <span m=''1390050''>cons,</span> <span m=''1390340''>car,</span> <span m=''1390620''>and
  cdr.</span> </p><p><span m=''1392360''>Given</span> <span m=''1392620''>them,</span>
  <span m=''1393090''>it''s</span> <span m=''1393310''>pretty</span> <span m=''1393560''>clear</span>
  <span m=''1393840''>how</span> <span m=''1393960''>George</span> <span m=''1394280''>can</span>
  <span m=''1394430''>go</span> <span m=''1394590''>off</span> <span m=''1394770''>and</span>
  <span m=''1394870''>construct his</span> <span m=''1395350''>rational</span> <span
  m=''1395740''>numbers.</span> <span m=''1397520''>After all, all</span> <span m=''1397640''>he</span>
  <span m=''1397960''>has</span> <span m=''1398210''>to</span> <span m=''1398320''>do--</span>
  <span m=''1399390''>remember</span> <span m=''1399580''>George''s</span> <span m=''1399980''>problem</span>
  <span m=''1400340''>was</span> <span m=''1400460''>to</span> <span m=''1400560''>implement</span>
  <span m=''1401040''>make-RAT,</span> <span m=''1401710''>numerator,</span> <span
  m=''1402520''>and</span> <span m=''1402720''>denom.</span> <span m=''1403320''>So
  all</span> <span m=''1403580''>George</span> <span m=''1403840''>has</span> <span
  m=''1404060''>to</span> <span m=''1404160''>do</span> <span m=''1404670''>is</span>
  <span m=''1405030''>say</span> <span m=''1405160''>define</span> <span m=''1409410''>make-RAT</span>
  <span m=''1414570''>of</span> <span m=''1414980''>some</span> <span m=''1415510''>n</span>
  <span m=''1415930''>and a</span> <span m=''1416060''>d--</span> <span m=''1417110''>so</span>
  <span m=''1417970''>all</span> <span m=''1418110''>I</span> <span m=''1418220''>have</span>
  <span m=''1418320''>to</span> <span m=''1418430''>do</span> <span m=''1418580''>is</span>
  <span m=''1418700''>cons them.</span> <span m=''1420710''>That''s</span> <span m=''1421170''>cons</span>
  <span m=''1422000''>of</span> <span m=''1422180''>n</span> <span m=''1422480''>and</span>
  <span m=''1422660''>d.</span> </p><p><span m=''1425570''>And</span> <span m=''1425710''>then</span>
  <span m=''1425860''>if</span> <span m=''1425980''>I</span> <span m=''1426090''>want</span>
  <span m=''1426190''>to</span> <span m=''1426230''>get</span> <span m=''1426390''>the</span>
  <span m=''1426460''>numerator</span> <span m=''1426990''>out,</span> <span m=''1427810''>I</span>
  <span m=''1428020''>would</span> <span m=''1428160''>say</span> <span m=''1428300''>define</span>
  <span m=''1433090''>the</span> <span m=''1433210''>numerator,</span> <span m=''1433970''>numer,</span>
  <span m=''1437340''>of</span> <span m=''1437510''>some</span> <span m=''1438420''>rational</span>
  <span m=''1438890''>number,</span> <span m=''1439160''>x.</span> <span m=''1440260''>If</span>
  <span m=''1440450''>the</span> <span m=''1440550''>rational</span> <span m=''1440950''>number''s</span>
  <span m=''1441260''>implemented</span> <span m=''1441780''>as</span> <span m=''1441860''>a</span>
  <span m=''1441920''>pair,</span> <span m=''1442510''>then</span> <span m=''1443010''>all</span>
  <span m=''1443130''>I</span> <span m=''1443210''>have</span> <span m=''1443280''>to</span>
  <span m=''1443360''>do</span> <span m=''1443500''>is</span> <span m=''1443620''>get</span>
  <span m=''1443750''>out</span> <span m=''1443920''>the</span> <span m=''1444000''>car</span>
  <span m=''1444350''>of x.</span> <span m=''1446190''>And</span> <span m=''1446530''>then</span>
  <span m=''1446870''>similarly,</span> <span m=''1449080''>define</span> <span m=''1453410''>the</span>
  <span m=''1453550''>denom</span> <span m=''1458380''>is</span> <span m=''1458520''>going</span>
  <span m=''1458610''>to</span> <span m=''1458700''>be</span> <span m=''1458790''>the</span>
  <span m=''1458880''>cdr,</span> <span m=''1459350''>the</span> <span m=''1459520''>other</span>
  <span m=''1460340''>thing</span> <span m=''1460520''>I</span> <span m=''1460610''>put</span>
  <span m=''1460790''>into</span> <span m=''1460930''>the</span> <span m=''1461080''>pair.</span>
  </p><p><span m=''1467080''>Well,</span> <span m=''1467310''>now we''re</span> <span
  m=''1467520''>in</span> <span m=''1467590''>business.</span> <span m=''1468960''>That''s</span>
  <span m=''1471100''>a</span> <span m=''1471160''>complete</span> <span m=''1471530''>implementation</span>
  <span m=''1472180''>of</span> <span m=''1472250''>rational</span> <span m=''1472640''>numbers.</span>
  <span m=''1473810''>Let''s</span> <span m=''1474000''>use</span> <span m=''1474190''>it.</span>
  <span m=''1474410''>Suppose</span> <span m=''1474580''>I</span> <span m=''1474650''>want</span>
  <span m=''1474760''>to</span> <span m=''1474860''>say,</span> <span m=''1476130''>so
  I want to</span> <span m=''1476410''>think</span> <span m=''1476540''>about</span>
  <span m=''1476780''>how to</span> <span m=''1477090''>add</span> <span m=''1477270''>1/2</span>
  <span m=''1478720''>plus</span> <span m=''1478960''>1/4</span> <span m=''1481580''>and</span>
  <span m=''1482520''>watch</span> <span m=''1482790''>the</span> <span m=''1482870''>system</span>
  <span m=''1483250''>work.</span> <span m=''1483470''>Well,</span> <span m=''1483540''>the</span>
  <span m=''1483610''>way</span> <span m=''1483740''>I''d</span> <span m=''1483800''>use</span>
  <span m=''1484110''>that</span> <span m=''1484770''>is</span> <span m=''1484940''>I''d</span>
  <span m=''1485080''>say,</span> <span m=''1485320''>well,</span> <span m=''1485480''>maybe</span>
  <span m=''1485730''>define</span> <span m=''1490460''>a.</span> <span m=''1490780''>I</span>
  <span m=''1490890''>have</span> <span m=''1490990''>to</span> <span m=''1491100''>make</span>
  <span m=''1491420''>a</span> <span m=''1491530''>1/2.</span> <span m=''1493080''>Well,</span>
  <span m=''1493540''>that''s</span> <span m=''1493770''>a</span> <span m=''1493840''>rational</span>
  <span m=''1494260''>number</span> <span m=''1494500''>with</span> <span m=''1494660''>numerator</span>
  <span m=''1495670''>1</span> <span m=''1495830''>and</span> <span m=''1495980''>denominator</span>
  <span m=''1496670''>2,</span> <span m=''1499600''>so</span> <span m=''1499780''>a</span>
  <span m=''1500010''>will</span> <span m=''1500120''>be</span> <span m=''1500260''>make-RAT</span>
  <span m=''1500480''>of</span> <span m=''1500785''>1 and 2.</span> </p><p><span m=''1505490''>And</span>
  <span m=''1505720''>then</span> <span m=''1505960''>I''ll</span> <span m=''1506400''>construct</span>
  <span m=''1506830''>the</span> <span m=''1506900''>1/4.</span> <span m=''1507770''>I''ll</span>
  <span m=''1507860''>say</span> <span m=''1508010''>define</span> <span m=''1511020''>d</span>
  <span m=''1512940''>to</span> <span m=''1513170''>be</span> <span m=''1515120''>make-RAT</span>
  <span m=''1517350''>of</span> <span m=''1519530''>1</span> <span m=''1519920''>and</span>
  <span m=''1520070''>4.</span> <span m=''1523362''>And if</span> <span m=''1523830''>I''d</span>
  <span m=''1524100''>like</span> <span m=''1524260''>to</span> <span m=''1524350''>look</span>
  <span m=''1524470''>at</span> <span m=''1524600''>the</span> <span m=''1524770''>answer--</span>
  <span m=''1525440''>well,</span> <span m=''1525630''>assuming</span> <span m=''1525990''>I</span>
  <span m=''1526050''>don''t</span> <span m=''1526210''>have</span> <span m=''1526400''>a</span>
  <span m=''1526720''>special</span> <span m=''1527120''>thing</span> <span m=''1527280''>that</span>
  <span m=''1527420''>prints</span> <span m=''1527710''>rational</span> <span m=''1528110''>numbers,</span>
  <span m=''1528440''>or</span> <span m=''1528530''>I</span> <span m=''1528600''>could</span>
  <span m=''1528800''>make</span> <span m=''1529060''>one--</span> <span m=''1530100''>I</span>
  <span m=''1530230''>could</span> <span m=''1530390''>say,</span> <span m=''1530960''>for</span>
  <span m=''1531100''>instance,</span> <span m=''1531530''>define</span> <span m=''1535260''>the</span>
  <span m=''1535630''>answer</span> <span m=''1538530''>to</span> <span m=''1538860''>be</span>
  <span m=''1539000''>+RAT</span> <span m=''1541622''>of</span> <span m=''1542080''>a</span>
  <span m=''1542460''>and</span> <span m=''1543450''>b,</span> <span m=''1546380''>and</span>
  <span m=''1546550''>now I</span> <span m=''1546660''>can</span> <span m=''1546790''>say,</span>
  <span m=''1546930''>what''s</span> <span m=''1547160''>the</span> <span m=''1547290''>answer?</span>
  <span m=''1547790''>What</span> <span m=''1547880''>are</span> <span m=''1547960''>the</span>
  <span m=''1548080''>numerators</span> <span m=''1548320''>and</span> <span m=''1548700''>denominators</span>
  <span m=''1549690''>of</span> <span m=''1549810''>the</span> <span m=''1549930''>answer?</span>
  </p><p><span m=''1550900''>So</span> <span m=''1551090''>if</span> <span m=''1551280''>I''m
  adding</span> <span m=''1551470''>1/2</span> <span m=''1552040''>and</span> <span
  m=''1552330''>1/4,</span> <span m=''1554310''>I''ll</span> <span m=''1554470''>say,</span>
  <span m=''1554640''>what</span> <span m=''1554890''>is</span> <span m=''1555280''>the</span>
  <span m=''1555520''>numerator</span> <span m=''1559890''>of</span> <span m=''1560010''>the</span>
  <span m=''1560130''>answer?</span> <span m=''1564230''>And</span> <span m=''1564340''>the</span>
  <span m=''1564450''>system</span> <span m=''1564820''>is</span> <span m=''1564920''>going</span>
  <span m=''1565010''>to</span> <span m=''1565100''>type</span> <span m=''1565460''>out,</span>
  <span m=''1568850''>well,</span> <span m=''1570260''>6.</span> <span m=''1570880''>Bad</span>
  <span m=''1571160''>news.</span> <span m=''1573250''>And</span> <span m=''1573460''>if
  I</span> <span m=''1573570''>say</span> <span m=''1573720''>what''s</span> <span
  m=''1573940''>the</span> <span m=''1574020''>denominator</span> <span m=''1574630''>of</span>
  <span m=''1574730''>the</span> <span m=''1574830''>answer,</span> <span m=''1582340''>the</span>
  <span m=''1582790''>system''s</span> <span m=''1583130''>going</span> <span m=''1583250''>to</span>
  <span m=''1583350''>type</span> <span m=''1583600''>out</span> <span m=''1584440''>8.</span>
  <span m=''1586430''>So</span> <span m=''1586630''>instead</span> <span m=''1586960''>of</span>
  <span m=''1587930''>what</span> <span m=''1588080''>I</span> <span m=''1588210''>would</span>
  <span m=''1588340''>really</span> <span m=''1588630''>like,</span> <span m=''1589930''>which</span>
  <span m=''1590120''>is</span> <span m=''1590240''>for it</span> <span m=''1590400''>to</span>
  <span m=''1590510''>say</span> <span m=''1590720''>that</span> <span m=''1590900''>1/2</span>
  <span m=''1591420''>and</span> <span m=''1591580''>1/4</span> <span m=''1591950''>is</span>
  <span m=''1592250''>3/4,</span> <span m=''1595630''>this</span> <span m=''1595740''>foolish</span>
  <span m=''1596110''>machine</span> <span m=''1596450''>is</span> <span m=''1596550''>going</span>
  <span m=''1596620''>to</span> <span m=''1596680''>say,</span> <span m=''1596830''>no,</span>
  <span m=''1597190''>it''s</span> <span m=''1598050''>6/8.</span> </p><p><span m=''1600450''>Well,</span>
  <span m=''1600620''>that''s</span> <span m=''1600790''>sort of</span> <span m=''1601280''>bad</span>
  <span m=''1601550''>news.</span> <span m=''1603400''>Where''s</span> <span m=''1603750''>the
  bug?</span> <span m=''1607280''>Why</span> <span m=''1607480''>does</span> <span
  m=''1607570''>it</span> <span m=''1607650''>do</span> <span m=''1607880''>that,</span>
  <span m=''1608110''>after</span> <span m=''1608440''>all?</span> <span m=''1608780''>Well,</span>
  <span m=''1609050''>it''s the</span> <span m=''1609160''>way</span> <span m=''1610290''>that</span>
  <span m=''1610430''>we</span> <span m=''1610530''>just</span> <span m=''1610730''>had</span>
  <span m=''1610900''>+RAT.</span> <span m=''1611400''>+RAT</span> <span m=''1611850''>just</span>
  <span m=''1612020''>took</span> <span m=''1612200''>the--</span> <span m=''1613220''>it</span>
  <span m=''1613510''>said</span> <span m=''1613730''>you</span> <span m=''1613850''>add</span>
  <span m=''1614100''>the</span> <span m=''1615340''>numerator</span> <span m=''1615950''>times</span>
  <span m=''1616210''>the</span> <span m=''1616290''>denominator,</span> <span m=''1618220''>you</span>
  <span m=''1618360''>add</span> <span m=''1618510''>that</span> <span m=''1618680''>to</span>
  <span m=''1618770''>the</span> <span m=''1618870''>numerator</span> <span m=''1619220''>times
  the</span> <span m=''1619680''>denominator,</span> <span m=''1620780''>and</span>
  <span m=''1620930''>put</span> <span m=''1621070''>that</span> <span m=''1621230''>over</span>
  <span m=''1621390''>the</span> <span m=''1621490''>product</span> <span m=''1621870''>of</span>
  <span m=''1621940''>the</span> <span m=''1622060''>two</span> <span m=''1622210''>denominators,</span>
  <span m=''1622780''>and</span> <span m=''1622900''>that''s</span> <span m=''1623020''>why</span>
  <span m=''1623140''>you</span> <span m=''1623260''>get</span> <span m=''1623440''>6/8.</span>
  </p><p><span m=''1625890''>So</span> <span m=''1626010''>what</span> <span m=''1626140''>was</span>
  <span m=''1626290''>wrong</span> <span m=''1628050''>with</span> <span m=''1628180''>our</span>
  <span m=''1628320''>implementation</span> <span m=''1629030''>of</span> <span m=''1629390''>+RAT?</span>
  <span m=''1630640''>What''s</span> <span m=''1630810''>wrong</span> <span m=''1631010''>with</span>
  <span m=''1631110''>that</span> <span m=''1631260''>rational</span> <span m=''1631590''>number</span>
  <span m=''1631940''>arithmetic</span> <span m=''1632110''>stuff</span> <span m=''1632780''>that</span>
  <span m=''1633080''>we</span> <span m=''1633180''>did</span> <span m=''1633350''>before</span>
  <span m=''1633620''>the</span> <span m=''1633710''>break?</span> <span m=''1635880''>Well,</span>
  <span m=''1635990''>the</span> <span m=''1636110''>answer</span> <span m=''1636390''>is</span>
  <span m=''1636490''>one</span> <span m=''1636630''>way</span> <span m=''1636730''>to</span>
  <span m=''1636830''>look</span> <span m=''1637010''>at</span> <span m=''1637190''>it</span>
  <span m=''1637290''>is</span> <span m=''1637380''>absolutely</span> <span m=''1637730''>nothing''s</span>
  <span m=''1638090''>wrong.</span> <span m=''1639730''>That''s</span> <span m=''1639940''>perfectly</span>
  <span m=''1640510''>good</span> <span m=''1640700''>implementation.</span> <span
  m=''1641070''>It</span> <span m=''1641440''>follows</span> <span m=''1641860''>the</span>
  <span m=''1644680''>sixth</span> <span m=''1645000''>grade,</span> <span m=''1645270''>fifth</span>
  <span m=''1645450''>grade</span> <span m=''1645660''>mathematic</span> <span m=''1646230''>for
  adding</span> <span m=''1646340''>fractions.</span> </p><p><span m=''1650000''>One</span>
  <span m=''1650160''>thing</span> <span m=''1650280''>we</span> <span m=''1650400''>can</span>
  <span m=''1650540''>say</span> <span m=''1650780''>is,</span> <span m=''1650920''>well,</span>
  <span m=''1651060''>that''s</span> <span m=''1651240''>George''s</span> <span m=''1651660''>problem.</span>
  <span m=''1653310''>Like,</span> <span m=''1653580''>boy,</span> <span m=''1653630''>wasn''t</span>
  <span m=''1653960''>George</span> <span m=''1654670''>dumb</span> <span m=''1655770''>to</span>
  <span m=''1655900''>say</span> <span m=''1656250''>that</span> <span m=''1656510''>he</span>
  <span m=''1656620''>can</span> <span m=''1656750''>make</span> <span m=''1656950''>a</span>
  <span m=''1657030''>rational</span> <span m=''1657490''>number</span> <span m=''1658080''>simply</span>
  <span m=''1658440''>by</span> <span m=''1659120''>sticking</span> <span m=''1659500''>together</span>
  <span m=''1659850''>the</span> <span m=''1659960''>numerator</span> <span m=''1660100''>and
  the</span> <span m=''1660450''>denominator?</span> <span m=''1662900''>Wouldn''t</span>
  <span m=''1663140''>it</span> <span m=''1663270''>be</span> <span m=''1663360''>better</span>
  <span m=''1664100''>for</span> <span m=''1664250''>George,</span> <span m=''1665360''>when
  he</span> <span m=''1665460''>made</span> <span m=''1665850''>a</span> <span m=''1665910''>rational</span>
  <span m=''1666360''>number,</span> <span m=''1667900''>to</span> <span m=''1668070''>reduce</span>
  <span m=''1668420''>the</span> <span m=''1668510''>stuff</span> <span m=''1668760''>to</span>
  <span m=''1668890''>lowest</span> <span m=''1669230''>terms?</span> <span m=''1670970''>And</span>
  <span m=''1671400''>what</span> <span m=''1671580''>I</span> <span m=''1671750''>mean</span>
  <span m=''1672020''>is,</span> <span m=''1672360''>wouldn''t</span> <span m=''1672540''>it</span>
  <span m=''1672680''>be</span> <span m=''1672810''>better</span> <span m=''1675110''>for</span>
  <span m=''1675360''>George,</span> <span m=''1675750''>instead</span> <span m=''1676080''>of</span>
  <span m=''1676950''>using</span> <span m=''1677430''>this</span> <span m=''1677820''>version</span>
  <span m=''1678180''>of</span> <span m=''1678280''>make-RAT,</span> <span m=''1680430''>to</span>
  <span m=''1680770''>use</span> <span m=''1680970''>this</span> <span m=''1681150''>one</span>
  <span m=''1681300''>on</span> <span m=''1681380''>the</span> <span m=''1681460''>slide?</span>
  <span m=''1683580''>Or</span> <span m=''1683720''>instead</span> <span m=''1683990''>of</span>
  <span m=''1684090''>just</span> <span m=''1684500''>saying</span> <span m=''1685340''>cons</span>
  <span m=''1685710''>together</span> <span m=''1686370''>n</span> <span m=''1686560''>and
  d,</span> <span m=''1687550''>what</span> <span m=''1687780''>you</span> <span m=''1687900''>do</span>
  <span m=''1689190''>is</span> <span m=''1689390''>compute</span> <span m=''1689980''>the</span>
  <span m=''1690320''>greatest</span> <span m=''1690710''>common</span> <span m=''1691020''>divisor</span>
  <span m=''1691110''>of</span> <span m=''1691450''>n</span> <span m=''1691660''>and</span>
  <span m=''1691760''>d,</span> <span m=''1692800''>and</span> <span m=''1692980''>gcd</span>
  <span m=''1693530''>is</span> <span m=''1693650''>the</span> <span m=''1693700''>procedure</span>
  <span m=''1694190''>which,</span> <span m=''1695460''>well,</span> <span m=''1695560''>for
  all we</span> <span m=''1695680''>care</span> <span m=''1695940''>is</span> <span
  m=''1696020''>a</span> <span m=''1696080''>primitive,</span> <span m=''1696540''>which</span>
  <span m=''1696690''>computes</span> <span m=''1697020''>the</span> <span m=''1697100''>greatest</span>
  <span m=''1697470''>common</span> <span m=''1697750''>divisor</span> <span m=''1698220''>of</span>
  <span m=''1698320''>two</span> <span m=''1698460''>numbers.</span> </p><p><span
  m=''1700628''>So</span> <span m=''1701050''>the</span> <span m=''1701220''>way</span>
  <span m=''1701350''>I</span> <span m=''1701420''>can</span> <span m=''1701590''>construct</span>
  <span m=''1702000''>a</span> <span m=''1702040''>rational</span> <span m=''1702450''>number</span>
  <span m=''1702970''>is</span> <span m=''1704520''>get</span> <span m=''1704810''>the</span>
  <span m=''1704890''>greatest</span> <span m=''1705270''>common</span> <span m=''1705520''>divisor</span>
  <span m=''1706210''>of</span> <span m=''1706320''>the</span> <span m=''1706400''>two</span>
  <span m=''1706550''>numbers,</span> <span m=''1706890''>and I''m going to</span>
  <span m=''1707140''>call that</span> <span m=''1707390''>g,</span> <span m=''1710210''>and</span>
  <span m=''1710370''>then</span> <span m=''1710530''>instead</span> <span m=''1710860''>of</span>
  <span m=''1710980''>consing</span> <span m=''1711590''>together</span> <span m=''1712150''>n</span>
  <span m=''1712320''>and</span> <span m=''1712800''>d,</span> <span m=''1713000''>I''ll</span>
  <span m=''1713250''>divide</span> <span m=''1713620''>them</span> <span m=''1713700''>through.</span>
  <span m=''1714000''>I''ll cons</span> <span m=''1714540''>together the</span> <span
  m=''1714610''>quotient</span> <span m=''1715050''>of</span> <span m=''1715140''>n</span>
  <span m=''1715415''>by the</span> <span m=''1716110''>the</span> <span m=''1716250''>gcd</span>
  <span m=''1717630''>and</span> <span m=''1717740''>the</span> <span m=''1717860''>quotient</span>
  <span m=''1718220''>of</span> <span m=''1718290''>d</span> <span m=''1718500''>by</span>
  <span m=''1718660''>the</span> <span m=''1718760''>gcd.</span> <span m=''1720510''>And
  that</span> <span m=''1720980''>will</span> <span m=''1721060''>reduce</span> <span
  m=''1721420''>the</span> <span m=''1721490''>rational</span> <span m=''1721880''>number</span>
  <span m=''1722120''>to lowest</span> <span m=''1722540''>terms.</span> <span m=''1727780''>So</span>
  <span m=''1728220''>when</span> <span m=''1728360''>I</span> <span m=''1728440''>do</span>
  <span m=''1728700''>this</span> <span m=''1728870''>addition,</span> <span m=''1729200''>when</span>
  <span m=''1729730''>+RAT</span> <span m=''1731160''>calls</span> <span m=''1733320''>make-RAT--</span>
  <span m=''1734330''>and for</span> <span m=''1734500''>the</span> <span m=''1734580''>definition</span>
  <span m=''1735020''>of</span> <span m=''1735090''>+RAT</span> <span m=''1735560''>it
  had</span> <span m=''1735740''>a</span> <span m=''1735840''>make-RAT</span> <span
  m=''1735970''>in</span> <span m=''1736310''>there--</span> <span m=''1737810''>just</span>
  <span m=''1738000''>by</span> <span m=''1738120''>the</span> <span m=''1738230''>fact</span>
  <span m=''1738470''>that it''s</span> <span m=''1738710''>constructing</span> <span
  m=''1739250''>that,</span> <span m=''1739560''>the thing</span> <span m=''1739880''>will</span>
  <span m=''1740000''>get</span> <span m=''1740160''>reduced</span> <span m=''1740480''>to</span>
  <span m=''1740570''>lowest</span> <span m=''1740860''>terms</span> <span m=''1741110''>automatically.</span>
  </p><p><span m=''1749612''>OK,</span> <span m=''1752080''>that</span> <span m=''1752670''>is</span>
  <span m=''1752840''>a</span> <span m=''1752920''>complete</span> <span m=''1753310''>system.</span>
  <span m=''1755180''>For</span> <span m=''1755300''>rational</span> <span m=''1755640''>number</span>
  <span m=''1755920''>arithmetic,</span> <span m=''1756110''>let''s</span> <span m=''1756380''>look</span>
  <span m=''1756550''>at</span> <span m=''1756630''>what</span> <span m=''1756780''>we''ve</span>
  <span m=''1756940''>done.</span> <span m=''1759590''>All right,</span> <span m=''1759720''>we</span>
  <span m=''1759860''>said</span> <span m=''1760940''>we</span> <span m=''1761060''>want</span>
  <span m=''1761160''>to</span> <span m=''1761270''>build</span> <span m=''1761650''>rational</span>
  <span m=''1762080''>number</span> <span m=''1762440''>arithmetic,</span> <span m=''1764900''>and</span>
  <span m=''1765390''>we</span> <span m=''1765760''>had</span> <span m=''1765960''>a</span>
  <span m=''1766000''>thing</span> <span m=''1766190''>called</span> <span m=''1766440''>+RAT.</span>
  <span m=''1767230''>We</span> <span m=''1767380''>implemented</span> <span m=''1767930''>that.</span>
  <span m=''1769940''>And</span> <span m=''1770770''>I</span> <span m=''1771230''>showed</span>
  <span m=''1771620''>you</span> <span m=''1771970''>multiplying</span> <span m=''1772550''>rational</span>
  <span m=''1772940''>numbers,</span> <span m=''1773330''>and</span> <span m=''1774500''>although</span>
  <span m=''1774660''>I</span> <span m=''1774730''>didn''t</span> <span m=''1774930''>put</span>
  <span m=''1775050''>them</span> <span m=''1775170''>up</span> <span m=''1775300''>there,</span>
  <span m=''1775440''>presumably</span> <span m=''1775980''>we''d</span> <span m=''1776130''>like</span>
  <span m=''1776310''>to</span> <span m=''1776440''>have</span> <span m=''1776570''>something</span>
  <span m=''1776900''>that</span> <span m=''1777090''>subtracts</span> <span m=''1777580''>rational</span>
  <span m=''1777980''>numbers,</span> <span m=''1779320''>and</span> <span m=''1779600''>I</span>
  <span m=''1779750''>don''t</span> <span m=''1779860''>know,</span> <span m=''1779960''>all</span>
  <span m=''1780070''>sorts</span> <span m=''1780320''>of</span> <span m=''1780430''>things.</span>
  <span m=''1780770''>Things</span> <span m=''1780980''>that</span> <span m=''1781350''>test
  equality</span> <span m=''1781900''>in</span> <span m=''1782050''>division,</span>
  <span m=''1782550''>and</span> <span m=''1782650''>maybe</span> <span m=''1782910''>things</span>
  <span m=''1783120''>that</span> <span m=''1783270''>print</span> <span m=''1783490''>rational</span>
  <span m=''1783910''>numbers</span> <span m=''1784250''>in</span> <span m=''1784350''>some</span>
  <span m=''1784480''>particular</span> <span m=''1784920''>way.</span> </p><p><span
  m=''1786190''>And</span> <span m=''1786320''>we</span> <span m=''1786440''>implemented</span>
  <span m=''1787040''>those</span> <span m=''1789360''>in</span> <span m=''1789530''>terms</span>
  <span m=''1789810''>of</span> <span m=''1789910''>pairs.</span> <span m=''1792330''>These</span>
  <span m=''1792730''>pairs,</span> <span m=''1793040''>cons,</span> <span m=''1793140''>car,</span>
  <span m=''1793410''>and</span> <span m=''1793680''>cdr</span> <span m=''1793920''>that</span>
  <span m=''1794030''>are</span> <span m=''1794130''>built</span> <span m=''1794390''>into</span>
  <span m=''1794600''>Lisp.</span> <span m=''1795800''>But</span> <span m=''1795940''>the</span>
  <span m=''1796090''>important</span> <span m=''1796760''>thing</span> <span m=''1797580''>is</span>
  <span m=''1797770''>that</span> <span m=''1797960''>between</span> <span m=''1800260''>these</span>
  <span m=''1803560''>and</span> <span m=''1803790''>these,</span> <span m=''1805100''>we</span>
  <span m=''1805230''>set</span> <span m=''1805450''>up</span> <span m=''1805690''>an</span>
  <span m=''1805830''>abstraction</span> <span m=''1806470''>barrier.</span> <span
  m=''1807622''>We</span> <span m=''1807970''>set</span> <span m=''1808080''>up</span>
  <span m=''1808220''>a</span> <span m=''1808270''>layer</span> <span m=''1808640''>of</span>
  <span m=''1808800''>abstraction.</span> </p><p><span m=''1817310''>And</span> <span
  m=''1817450''>what</span> <span m=''1817640''>was</span> <span m=''1817950''>that</span>
  <span m=''1818170''>layer</span> <span m=''1818430''>of</span> <span m=''1818520''>abstraction?</span>
  <span m=''1819190''>That layer</span> <span m=''1819410''>of</span> <span m=''1819730''>abstraction</span>
  <span m=''1820130''>was</span> <span m=''1820300''>precisely</span> <span m=''1821310''>the</span>
  <span m=''1821470''>constructor</span> <span m=''1822070''>and</span> <span m=''1822140''>the</span>
  <span m=''1822220''>selectors.</span> <span m=''1825630''>This</span> <span m=''1825790''>layer</span>
  <span m=''1826010''>was</span> <span m=''1826330''>make-RAT,</span> <span m=''1828080''>and</span>
  <span m=''1828670''>numer,</span> <span m=''1834100''>and</span> <span m=''1834370''>denom.</span>
  <span m=''1838970''>This</span> <span m=''1839330''>methodology,</span> <span m=''1841970''>another</span>
  <span m=''1842150''>way</span> <span m=''1842270''>to</span> <span m=''1842330''>say</span>
  <span m=''1842510''>what</span> <span m=''1842650''>it''s</span> <span m=''1842830''>doing,</span>
  <span m=''1843480''>is</span> <span m=''1843670''>that</span> <span m=''1843850''>we</span>
  <span m=''1843960''>are</span> <span m=''1844040''>separating</span> <span m=''1849910''>the</span>
  <span m=''1850010''>way</span> <span m=''1850240''>something</span> <span m=''1850610''>is</span>
  <span m=''1850740''>used,</span> <span m=''1853520''>separating</span> <span m=''1853960''>the</span>
  <span m=''1854040''>use</span> <span m=''1854410''>of</span> <span m=''1854570''>data</span>
  <span m=''1854850''>objects,</span> <span m=''1856380''>from</span> <span m=''1857620''>the</span>
  <span m=''1857760''>representation</span> <span m=''1858700''>of data</span> <span
  m=''1858920''>objects.</span> <span m=''1867650''>So</span> <span m=''1867730''>up</span>
  <span m=''1867920''>here,</span> <span m=''1868080''>we</span> <span m=''1868240''>have</span>
  <span m=''1868400''>the</span> <span m=''1868470''>way</span> <span m=''1868830''>that</span>
  <span m=''1869210''>rational</span> <span m=''1869620''>numbers</span> <span m=''1869930''>are</span>
  <span m=''1870010''>used,</span> <span m=''1871440''>do</span> <span m=''1871590''>arithmetic</span>
  <span m=''1872050''>on</span> <span m=''1872210''>them.</span> <span m=''1872620''>Down</span>
  <span m=''1872850''>here,</span> <span m=''1873080''>we</span> <span m=''1873210''>have</span>
  <span m=''1873900''>the</span> <span m=''1873940''>way</span> <span m=''1874100''>that</span>
  <span m=''1874250''>they''re</span> <span m=''1874370''>represented,</span> <span
  m=''1875140''>and</span> <span m=''1875280''>they''re</span> <span m=''1875390''>separated</span>
  <span m=''1875950''>by</span> <span m=''1876080''>this</span> <span m=''1876270''>boundary.</span>
  <span m=''1877950''>The boundary</span> <span m=''1878280''>is</span> <span m=''1878560''>the</span>
  <span m=''1878660''>constructors</span> <span m=''1879190''>and</span> <span m=''1879300''>selectors.</span>
  </p><p><span m=''1883760''>And</span> <span m=''1883960''>this</span> <span m=''1884520''>methodology</span>
  <span m=''1885170''>has</span> <span m=''1885360''>a</span> <span m=''1885400''>name.</span>
  <span m=''1885920''>This is</span> <span m=''1886030''>called</span> <span m=''1886270''>data</span>
  <span m=''1886580''>abstraction.</span> <span m=''1895820''>Data</span> <span m=''1896370''>abstraction</span>
  <span m=''1896625''>is</span> <span m=''1896880''>sort</span> <span m=''1897080''>of</span>
  <span m=''1897140''>the</span> <span m=''1897200''>programming</span> <span m=''1897820''>methodology</span>
  <span m=''1898920''>of</span> <span m=''1899030''>setting</span> <span m=''1899320''>up</span>
  <span m=''1899430''>data</span> <span m=''1899680''>objects</span> <span m=''1900140''>by</span>
  <span m=''1900780''>postulating</span> <span m=''1901440''>constructors</span> <span
  m=''1901960''>and</span> <span m=''1902060''>selectors</span> <span m=''1902640''>to</span>
  <span m=''1902810''>isolate</span> <span m=''1903290''>use</span> <span m=''1903450''>from</span>
  <span m=''1903670''>representation.</span> <span m=''1907550''>Well, so</span> <span
  m=''1907860''>why?</span> <span m=''1909060''>I</span> <span m=''1909120''>mean,</span>
  <span m=''1909250''>after</span> <span m=''1909440''>all, we</span> <span m=''1909550''>didn''t</span>
  <span m=''1909730''>have</span> <span m=''1909910''>to</span> <span m=''1910090''>do</span>
  <span m=''1910260''>it</span> <span m=''1910370''>this</span> <span m=''1910560''>way.</span>
  <span m=''1911750''>It''s</span> <span m=''1911930''>perfectly</span> <span m=''1912420''>possible</span>
  <span m=''1913080''>to</span> <span m=''1913370''>do</span> <span m=''1913520''>rational</span>
  <span m=''1913970''>number</span> <span m=''1914990''>addition</span> <span m=''1915450''>without</span>
  <span m=''1915750''>having</span> <span m=''1916000''>any</span> <span m=''1916120''>compound</span>
  <span m=''1916540''>data</span> <span m=''1916740''>objects,</span> <span m=''1917200''>and
  here</span> <span m=''1917410''>on</span> <span m=''1917480''>the</span> <span m=''1917550''>slide</span>
  <span m=''1918930''>is</span> <span m=''1919050''>one</span> <span m=''1919270''>example.</span>
  </p><p><span m=''1920060''>We</span> <span m=''1920240''>certainly</span> <span
  m=''1920630''>could</span> <span m=''1920850''>have</span> <span m=''1921070''>defined</span>
  <span m=''1922280''>+RAT,</span> <span m=''1923220''>which</span> <span m=''1923370''>takes</span>
  <span m=''1923660''>in</span> <span m=''1924640''>things</span> <span m=''1925510''>x</span>
  <span m=''1925780''>and</span> <span m=''1925910''>y,</span> <span m=''1926190''>and</span>
  <span m=''1926290''>we''ll say, well</span> <span m=''1926540''>what</span> <span
  m=''1926670''>are</span> <span m=''1926810''>these</span> <span m=''1927390''>rational</span>
  <span m=''1927830''>numbers</span> <span m=''1928570''>really?</span> <span m=''1930030''>So</span>
  <span m=''1930240''>really,</span> <span m=''1930600''>they''re</span> <span m=''1930750''>just</span>
  <span m=''1931030''>pairs,</span> <span m=''1932000''>and the</span> <span m=''1932150''>numerator''s</span>
  <span m=''1932730''>the</span> <span m=''1932800''>car</span> <span m=''1933060''>and</span>
  <span m=''1933130''>the</span> <span m=''1933200''>denominator''s</span> <span m=''1933750''>the</span>
  <span m=''1933870''>cdr.</span> <span m=''1934440''>So</span> <span m=''1934640''>what</span>
  <span m=''1934780''>we''ll</span> <span m=''1934910''>do</span> <span m=''1935120''>is</span>
  <span m=''1935370''>we''ll</span> <span m=''1935880''>take</span> <span m=''1936180''>the</span>
  <span m=''1936270''>car</span> <span m=''1936640''>of</span> <span m=''1936750''>x</span>
  <span m=''1937870''>times</span> <span m=''1938200''>the</span> <span m=''1938280''>cdr</span>
  <span m=''1938580''>of</span> <span m=''1938680''>y,</span> <span m=''1942310''>multiply</span>
  <span m=''1942850''>them.</span> <span m=''1943310''>Take</span> <span m=''1943520''>the</span>
  <span m=''1943600''>car</span> <span m=''1943890''>of</span> <span m=''1943980''>y</span>
  <span m=''1944550''>times</span> <span m=''1944750''>the</span> <span m=''1944830''>cdr</span>
  <span m=''1945180''>of x,</span> <span m=''1945650''>multiply</span> <span m=''1946150''>them.</span>
  <span m=''1946470''>Add</span> <span m=''1946620''>them.</span> <span m=''1948650''>Take</span>
  <span m=''1948910''>the</span> <span m=''1949010''>cdr</span> <span m=''1949340''>of</span>
  <span m=''1949460''>x</span> <span m=''1949840''>and the cdr</span> <span m=''1950120''>of
  y,</span> <span m=''1950550''>multiply</span> <span m=''1951040''>them,</span> <span
  m=''1951720''>and</span> <span m=''1951840''>then</span> <span m=''1951960''>constitute</span>
  <span m=''1952520''>together.</span> <span m=''1955450''>Well,</span> <span m=''1955820''>that
  sort of</span> <span m=''1955990''>does</span> <span m=''1956170''>the</span> <span
  m=''1956250''>same</span> <span m=''1956520''>thing.</span> </p><p><span m=''1961560''>But</span>
  <span m=''1961700''>this</span> <span m=''1961840''>ignores</span> <span m=''1962250''>the</span>
  <span m=''1962330''>problem</span> <span m=''1962780''>of</span> <span m=''1962990''>reducing</span>
  <span m=''1963410''>things</span> <span m=''1963550''>to</span> <span m=''1963840''>lowest</span>
  <span m=''1963930''>terms,</span> <span m=''1964350''>but</span> <span m=''1965110''>let''s</span>
  <span m=''1965930''>not</span> <span m=''1966060''>worry</span> <span m=''1966220''>about</span>
  <span m=''1966410''>that</span> <span m=''1966560''>for</span> <span m=''1966620''>a</span>
  <span m=''1966690''>minute.</span> <span m=''1967680''>But</span> <span m=''1967850''>so</span>
  <span m=''1968010''>what?</span> <span m=''1968200''>Why</span> <span m=''1968400''>don''t</span>
  <span m=''1968490''>we</span> <span m=''1968610''>do</span> <span m=''1968750''>it</span>
  <span m=''1968860''>that</span> <span m=''1969090''>way?</span> <span m=''1970790''>Right?</span>
  <span m=''1970960''>After</span> <span m=''1971160''>all,</span> <span m=''1971230''>there</span>
  <span m=''1971530''>are</span> <span m=''1971590''>sort</span> <span m=''1971750''>of</span>
  <span m=''1971810''>fewer</span> <span m=''1972090''>procedures</span> <span m=''1972650''>to</span>
  <span m=''1972770''>define,</span> <span m=''1973220''>and</span> <span m=''1973340''>it''s</span>
  <span m=''1973470''>a</span> <span m=''1973520''>lot</span> <span m=''1973720''>more</span>
  <span m=''1973870''>straightforward.</span> <span m=''1977210''>It</span> <span
  m=''1977510''>saves</span> <span m=''1977820''>all</span> <span m=''1977970''>this</span>
  <span m=''1978050''>self-righteous</span> <span m=''1978820''>BS</span> <span m=''1979240''>about</span>
  <span m=''1979610''>talking</span> <span m=''1980010''>about</span> <span m=''1980220''>data</span>
  <span m=''1980430''>abstraction.</span> <span m=''1980850''>We just sort of</span>
  <span m=''1981400''>do</span> <span m=''1981670''>it.</span> <span m=''1982270''>I</span>
  <span m=''1982340''>mean,</span> <span m=''1982440''>who</span> <span m=''1982520''>knows,</span>
  <span m=''1982700''>maybe</span> <span m=''1982980''>it''s</span> <span m=''1983120''>even</span>
  <span m=''1983360''>marginally</span> <span m=''1984190''>more</span> <span m=''1984440''>efficient</span>
  <span m=''1984870''>depending</span> <span m=''1985290''>on</span> <span m=''1985580''>whatever</span>
  <span m=''1986040''>compiler</span> <span m=''1986540''>were</span> <span m=''1986650''>using</span>
  <span m=''1986980''>for</span> <span m=''1987090''>this.</span> </p><p><span m=''1987930''>What''s</span>
  <span m=''1988100''>the</span> <span m=''1988760''>point</span> <span m=''1989930''>of</span>
  <span m=''1990100''>isolating</span> <span m=''1990960''>the use</span> <span m=''1991230''>from</span>
  <span m=''1991370''>the</span> <span m=''1991500''>representation?</span> <span
  m=''1993910''>Well,</span> <span m=''1994770''>it</span> <span m=''1995190''>goes</span>
  <span m=''1995440''>back</span> <span m=''1995750''>to</span> <span m=''1995860''>this</span>
  <span m=''1996060''>notion</span> <span m=''1996420''>of</span> <span m=''1996590''>naming.</span>
  <span m=''1997130''>Remember,</span> <span m=''1998320''>one</span> <span m=''1998480''>of</span>
  <span m=''1998550''>the</span> <span m=''1998620''>most</span> <span m=''1998930''>important</span>
  <span m=''1999310''>principles</span> <span m=''2000870''>in</span> <span m=''2001020''>programming</span>
  <span m=''2001670''>is</span> <span m=''2001860''>the</span> <span m=''2001940''>same</span>
  <span m=''2002330''>as</span> <span m=''2002740''>one</span> <span m=''2003030''>of</span>
  <span m=''2003090''>the</span> <span m=''2003240''>most</span> <span m=''2003400''>important</span>
  <span m=''2003770''>principles</span> <span m=''2004210''>in</span> <span m=''2004340''>sorcery,</span>
  <span m=''2005400''>all right?</span> <span m=''2005660''>That''s if</span> <span
  m=''2005760''>you</span> <span m=''2005860''>have</span> <span m=''2006180''>the</span>
  <span m=''2006260''>name</span> <span m=''2006670''>of</span> <span m=''2006830''>the</span>
  <span m=''2006920''>spirit,</span> <span m=''2007930''>you</span> <span m=''2008050''>get</span>
  <span m=''2008210''>control</span> <span m=''2008640''>over</span> <span m=''2008890''>it.</span>
  </p><p><span m=''2010330''>And</span> <span m=''2010480''>if</span> <span m=''2010560''>you</span>
  <span m=''2010890''>go</span> <span m=''2011020''>back</span> <span m=''2011250''>and</span>
  <span m=''2011350''>look</span> <span m=''2011500''>at</span> <span m=''2011620''>the</span>
  <span m=''2011730''>slide,</span> <span m=''2013790''>you</span> <span m=''2013900''>see</span>
  <span m=''2014030''>what''s</span> <span m=''2014210''>in</span> <span m=''2014420''>there</span>
  <span m=''2014600''>is</span> <span m=''2014730''>we</span> <span m=''2014830''>have</span>
  <span m=''2015060''>this thing</span> <span m=''2015140''>+RAT,</span> <span m=''2016940''>but</span>
  <span m=''2017140''>nowhere</span> <span m=''2018340''>in</span> <span m=''2018480''>the</span>
  <span m=''2018580''>system,</span> <span m=''2019020''>if</span> <span m=''2019140''>I</span>
  <span m=''2019230''>have</span> <span m=''2019330''>a</span> <span m=''2019380''>+RAT</span>
  <span m=''2019980''>and a -RAT</span> <span m=''2020600''>and a</span> <span m=''2020650''>*RAT,</span>
  <span m=''2021420''>and</span> <span m=''2021550''>things</span> <span m=''2021710''>that</span>
  <span m=''2021850''>look</span> <span m=''2022020''>like</span> <span m=''2022190''>that,</span>
  <span m=''2022580''>nowhere</span> <span m=''2022910''>in</span> <span m=''2022990''>the</span>
  <span m=''2023080''>system</span> <span m=''2023620''>do</span> <span m=''2024480''>I</span>
  <span m=''2024630''>have</span> <span m=''2024790''>a</span> <span m=''2024870''>thing</span>
  <span m=''2025060''>that</span> <span m=''2025160''>I</span> <span m=''2025250''>can</span>
  <span m=''2025510''>point</span> <span m=''2026030''>at</span> <span m=''2029660''>which</span>
  <span m=''2029860''>is</span> <span m=''2029970''>a</span> <span m=''2030040''>rational</span>
  <span m=''2030440''>number.</span> <span m=''2033550''>I</span> <span m=''2033810''>don''t</span>
  <span m=''2034250''>have,</span> <span m=''2034790''>in</span> <span m=''2035350''>a</span>
  <span m=''2035450''>system</span> <span m=''2035790''>like</span> <span m=''2036000''>that,</span>
  <span m=''2037170''>the</span> <span m=''2037460''>idea</span> <span m=''2037890''>of</span>
  <span m=''2038040''>rational</span> <span m=''2038480''>number</span> <span m=''2038750''>as</span>
  <span m=''2038840''>a</span> <span m=''2038930''>conceptual</span> <span m=''2039560''>entity.</span>
  </p><p><span m=''2041340''>Well,</span> <span m=''2041820''>what''s</span> <span
  m=''2042160''>the</span> <span m=''2042300''>advantage</span> <span m=''2042820''>of</span>
  <span m=''2042910''>that?</span> <span m=''2044270''>What''s</span> <span m=''2044430''>the</span>
  <span m=''2044570''>advantage</span> <span m=''2045020''>of</span> <span m=''2045210''>isolating</span>
  <span m=''2045920''>the</span> <span m=''2046180''>idea</span> <span m=''2046720''>of</span>
  <span m=''2046820''>rational</span> <span m=''2047200''>numbers</span> <span m=''2047590''>as
  a</span> <span m=''2047650''>conceptual</span> <span m=''2048179''>entity,</span>
  <span m=''2048360''>and</span> <span m=''2048530''>really</span> <span m=''2048810''>naming</span>
  <span m=''2049250''>it</span> <span m=''2049400''>with</span> <span m=''2049679''>make-RAT,</span>
  <span m=''2050560''>numerator,</span> <span m=''2050929''>and</span> <span m=''2051100''>denominator.</span>
  <span m=''2052900''>Well,</span> <span m=''2053290''>one</span> <span m=''2053670''>advantage</span>
  <span m=''2054610''>is</span> <span m=''2055449''>you</span> <span m=''2055610''>might</span>
  <span m=''2055810''>want</span> <span m=''2055949''>to</span> <span m=''2058000''>have</span>
  <span m=''2058230''>alternative</span> <span m=''2058659''>representations.</span>
  <span m=''2060679''>See,</span> <span m=''2061500''>before</span> <span m=''2061889''>I</span>
  <span m=''2061949''>showed</span> <span m=''2062210''>you</span> <span m=''2062290''>that</span>
  <span m=''2062440''>one</span> <span m=''2062620''>way</span> <span m=''2062800''>George</span>
  <span m=''2063110''>can</span> <span m=''2063219''>solve</span> <span m=''2063520''>this</span>
  <span m=''2064889''>things</span> <span m=''2065179''>not</span> <span m=''2065380''>reduced</span>
  <span m=''2065719''>to</span> <span m=''2065810''>lowest</span> <span m=''2066080''>terms</span>
  <span m=''2066530''>problem,</span> <span m=''2066920''>is</span> <span m=''2067040''>when</span>
  <span m=''2067190''>you</span> <span m=''2067280''>build</span> <span m=''2067610''>a</span>
  <span m=''2067650''>rational</span> <span m=''2068090''>number,</span> <span m=''2069179''>you</span>
  <span m=''2069280''>divide</span> <span m=''2069610''>up</span> <span m=''2069739''>by</span>
  <span m=''2069840''>the</span> <span m=''2069940''>greatest</span> <span m=''2070260''>common</span>
  <span m=''2070580''>denominator.</span> </p><p><span m=''2071190''>Another</span>
  <span m=''2071590''>way</span> <span m=''2071699''>to</span> <span m=''2071820''>do</span>
  <span m=''2072000''>that</span> <span m=''2073670''>is</span> <span m=''2075540''>shown</span>
  <span m=''2075719''>over</span> <span m=''2075909''>here.</span> <span m=''2076650''>I</span>
  <span m=''2076750''>can</span> <span m=''2076840''>have</span> <span m=''2076949''>an</span>
  <span m=''2077000''>alternative</span> <span m=''2077600''>representation</span>
  <span m=''2078300''>for</span> <span m=''2078420''>rational</span> <span m=''2078810''>numbers</span>
  <span m=''2079330''>where</span> <span m=''2079760''>when</span> <span m=''2079960''>you</span>
  <span m=''2080060''>make</span> <span m=''2080290''>a</span> <span m=''2080360''>rational</span>
  <span m=''2080760''>number,</span> <span m=''2080980''>you</span> <span m=''2081100''>just</span>
  <span m=''2081290''>cons</span> <span m=''2081639''>them.</span> <span m=''2083409''>However,</span>
  <span m=''2083929''>when</span> <span m=''2084120''>you</span> <span m=''2084199''>go</span>
  <span m=''2084300''>to</span> <span m=''2084409''>select</span> <span m=''2084870''>out</span>
  <span m=''2085040''>the</span> <span m=''2085120''>numerator,</span> <span m=''2086170''>at</span>
  <span m=''2086370''>that</span> <span m=''2086610''>point</span> <span m=''2087980''>you</span>
  <span m=''2088110''>compute</span> <span m=''2088500''>the</span> <span m=''2088820''>gcd</span>
  <span m=''2089440''>of</span> <span m=''2089989''>the</span> <span m=''2090139''>stuff</span>
  <span m=''2090409''>that''s</span> <span m=''2090600''>sitting</span> <span m=''2090850''>in</span>
  <span m=''2090929''>that</span> <span m=''2091070''>pair,</span> <span m=''2092429''>and</span>
  <span m=''2092590''>divide</span> <span m=''2092940''>out</span> <span m=''2093070''>by</span>
  <span m=''2093190''>the</span> <span m=''2093320''>gcd.</span> <span m=''2097970''>And</span>
  <span m=''2098200''>similarly,</span> <span m=''2098660''>when</span> <span m=''2098790''>I</span>
  <span m=''2098830''>get</span> <span m=''2098960''>the</span> <span m=''2099040''>denominator,</span>
  <span m=''2101090''>at</span> <span m=''2101270''>that</span> <span m=''2101560''>point</span>
  <span m=''2102300''>when</span> <span m=''2102430''>I</span> <span m=''2102490''>go</span>
  <span m=''2102570''>to</span> <span m=''2102660''>get</span> <span m=''2102920''>the</span>
  <span m=''2103000''>denominator,</span> <span m=''2103600''>I''ll</span> <span m=''2103760''>divide</span>
  <span m=''2103820''>out</span> <span m=''2103990''>by</span> <span m=''2104280''>the</span>
  <span m=''2104340''>gcd.</span> </p><p><span m=''2105420''>So</span> <span m=''2105650''>the</span>
  <span m=''2105740''>difference</span> <span m=''2106110''>would</span> <span m=''2106240''>be</span>
  <span m=''2106380''>in</span> <span m=''2106470''>the</span> <span m=''2106550''>old</span>
  <span m=''2106770''>representation,</span> <span m=''2108840''>when</span> <span
  m=''2109090''>ans</span> <span m=''2109450''>was</span> <span m=''2109600''>constructed</span>
  <span m=''2110150''>here,</span> <span m=''2111360''>say</span> <span m=''2111560''>what''s</span>
  <span m=''2111720''>6 and</span> <span m=''2112150''>8,</span> <span m=''2113170''>in</span>
  <span m=''2113270''>the</span> <span m=''2113350''>first</span> <span m=''2113680''>way,</span>
  <span m=''2114020''>the</span> <span m=''2114640''>6</span> <span m=''2114900''>and</span>
  <span m=''2114990''>8</span> <span m=''2115070''>would</span> <span m=''2115180''>have</span>
  <span m=''2115300''>got</span> <span m=''2115500''>reduced</span> <span m=''2115880''>when</span>
  <span m=''2115990''>they</span> <span m=''2116080''>got</span> <span m=''2116260''>stuck</span>
  <span m=''2116510''>into</span> <span m=''2116720''>that</span> <span m=''2116920''>pair,</span>
  <span m=''2117220''>numerator</span> <span m=''2117720''>would</span> <span m=''2117840''>select</span>
  <span m=''2118230''>out</span> <span m=''2118440''>3.</span> <span m=''2120380''>And</span>
  <span m=''2120520''>in</span> <span m=''2120570''>the</span> <span m=''2120650''>way</span>
  <span m=''2120790''>I</span> <span m=''2120890''>just</span> <span m=''2121150''>showed</span>
  <span m=''2121420''>you,</span> <span m=''2121540''>well,</span> <span m=''2122110''>ans</span>
  <span m=''2122890''>would</span> <span m=''2123020''>get</span> <span m=''2123480''>6</span>
  <span m=''2123730''>and</span> <span m=''2123850''>8</span> <span m=''2124070''>put</span>
  <span m=''2124240''>in,</span> <span m=''2125110''>and</span> <span m=''2125400''>then</span>
  <span m=''2125630''>at</span> <span m=''2125760''>the</span> <span m=''2125860''>point</span>
  <span m=''2126220''>where</span> <span m=''2126370''>I</span> <span m=''2126460''>said</span>
  <span m=''2126690''>numerator,</span> <span m=''2127650''>some</span> <span m=''2127850''>computation</span>
  <span m=''2128510''>would</span> <span m=''2128660''>get</span> <span m=''2128820''>done</span>
  <span m=''2129190''>to</span> <span m=''2129420''>put</span> <span m=''2129590''>out</span>
  <span m=''2129770''>3</span> <span m=''2130090''>instead</span> <span m=''2130390''>of</span>
  <span m=''2130460''>6.</span> <span m=''2132590''>So</span> <span m=''2132710''>those</span>
  <span m=''2132880''>are</span> <span m=''2132950''>two</span> <span m=''2133400''>different</span>
  <span m=''2133760''>ways</span> <span m=''2134010''>I</span> <span m=''2134090''>might</span>
  <span m=''2134300''>do</span> <span m=''2134440''>it.</span> </p><p><span m=''2134520''>Which</span>
  <span m=''2134690''>one''s</span> <span m=''2134860''>better?</span> <span m=''2137530''>Well,</span>
  <span m=''2137740''>it</span> <span m=''2137820''>depends,</span> <span m=''2138140''>right?</span>
  <span m=''2138460''>If</span> <span m=''2138710''>I''m</span> <span m=''2138790''>making</span>
  <span m=''2139090''>a</span> <span m=''2139140''>system</span> <span m=''2139530''>where</span>
  <span m=''2139940''>I</span> <span m=''2140080''>am</span> <span m=''2140240''>mostly</span>
  <span m=''2140690''>constructing</span> <span m=''2141230''>rational</span> <span
  m=''2141620''>numbers</span> <span m=''2142010''>and hardly</span> <span m=''2142350''>ever</span>
  <span m=''2142510''>looking</span> <span m=''2142850''>at</span> <span m=''2142950''>them,</span>
  <span m=''2143140''>then</span> <span m=''2143240''>it''s</span> <span m=''2143360''>probably</span>
  <span m=''2143740''>better</span> <span m=''2143990''>not</span> <span m=''2144140''>to</span>
  <span m=''2144280''>do</span> <span m=''2144440''>that</span> <span m=''2145270''>gcd</span>
  <span m=''2145670''>computation</span> <span m=''2146300''>when</span> <span m=''2146450''>I</span>
  <span m=''2146520''>construct</span> <span m=''2147383''>them.</span> <span m=''2147776''>If</span>
  <span m=''2148170''>I''m</span> <span m=''2148310''>doing</span> <span m=''2148560''>a</span>
  <span m=''2148610''>system</span> <span m=''2148940''>where</span> <span m=''2149040''>I</span>
  <span m=''2149130''>look</span> <span m=''2149270''>at</span> <span m=''2150220''>things</span>
  <span m=''2150450''>a</span> <span m=''2150500''>lot</span> <span m=''2150760''>more</span>
  <span m=''2150910''>than</span> <span m=''2151070''>I</span> <span m=''2151160''>construct</span>
  <span m=''2151630''>them,</span> <span m=''2152060''>then</span> <span m=''2152220''>it''s</span>
  <span m=''2152350''>probably</span> <span m=''2152750''>better</span> <span m=''2153030''>to</span>
  <span m=''2154040''>do</span> <span m=''2154170''>the</span> <span m=''2154260''>work</span>
  <span m=''2154470''>when I</span> <span m=''2154660''>construct</span> <span m=''2155100''>them.</span>
  <span m=''2157240''>So</span> <span m=''2157390''>there''s</span> <span m=''2157730''>a</span>
  <span m=''2157790''>choice</span> <span m=''2158050''>there.</span> </p><p><span
  m=''2158170''>But</span> <span m=''2158330''>the</span> <span m=''2158440''>real</span>
  <span m=''2158810''>issue</span> <span m=''2159770''>is</span> <span m=''2161020''>that</span>
  <span m=''2161200''>you</span> <span m=''2161320''>might</span> <span m=''2161580''>not</span>
  <span m=''2161780''>be</span> <span m=''2161910''>able</span> <span m=''2162120''>to</span>
  <span m=''2162240''>decide</span> <span m=''2164680''>at</span> <span m=''2164840''>the</span>
  <span m=''2164920''>moment</span> <span m=''2165210''>you''re</span> <span m=''2165320''>worrying</span>
  <span m=''2165640''>about</span> <span m=''2165890''>these</span> <span m=''2166050''>rational</span>
  <span m=''2166420''>numbers.</span> <span m=''2167640''>See, in</span> <span m=''2167850''>general,</span>
  <span m=''2168705''>as</span> <span m=''2169080''>systems</span> <span m=''2169890''>designers,</span>
  <span m=''2173430''>you''re</span> <span m=''2173660''>forced</span> <span m=''2174330''>with</span>
  <span m=''2174470''>the</span> <span m=''2174620''>necessity</span> <span m=''2175140''>to</span>
  <span m=''2175220''>make</span> <span m=''2175440''>decisions</span> <span m=''2175900''>about</span>
  <span m=''2176090''>how</span> <span m=''2176200''>you''re</span> <span m=''2176350''>going</span>
  <span m=''2176570''>to</span> <span m=''2176640''>do</span> <span m=''2176830''>things,</span>
  <span m=''2178010''>and</span> <span m=''2178160''>in</span> <span m=''2178250''>general,</span>
  <span m=''2178970''>the</span> <span m=''2179050''>way</span> <span m=''2179230''>you''d</span>
  <span m=''2179370''>like</span> <span m=''2179550''>to</span> <span m=''2179640''>retain</span>
  <span m=''2179970''>flexibility</span> <span m=''2180880''>is</span> <span m=''2181020''>to</span>
  <span m=''2181110''>never</span> <span m=''2181360''>make</span> <span m=''2181580''>up</span>
  <span m=''2181710''>your</span> <span m=''2181820''>mind</span> <span m=''2182310''>about</span>
  <span m=''2182720''>anything</span> <span m=''2183990''>until</span> <span m=''2184220''>you''re</span>
  <span m=''2184370''>forced</span> <span m=''2184700''>to</span> <span m=''2184770''>do</span>
  <span m=''2184970''>it.</span> </p><p><span m=''2186890''>The</span> <span m=''2187090''>problem</span>
  <span m=''2187520''>is,</span> <span m=''2188280''>there''s</span> <span m=''2188710''>a</span>
  <span m=''2189200''>very,</span> <span m=''2189690''>very</span> <span m=''2190000''>narrow</span>
  <span m=''2190350''>line</span> <span m=''2191350''>between</span> <span m=''2191730''>deferring</span>
  <span m=''2192200''>decisions</span> <span m=''2193520''>and</span> <span m=''2194060''>outright</span>
  <span m=''2194430''>procrastination.</span> <span m=''2198760''>So</span> <span
  m=''2198820''>you''d</span> <span m=''2199020''>like</span> <span m=''2199250''>to</span>
  <span m=''2199340''>make</span> <span m=''2199550''>progress,</span> <span m=''2202920''>but</span>
  <span m=''2203060''>also</span> <span m=''2203470''>at</span> <span m=''2203530''>the</span>
  <span m=''2203610''>same</span> <span m=''2203860''>time,</span> <span m=''2204080''>never</span>
  <span m=''2204330''>be</span> <span m=''2204470''>bound</span> <span m=''2204780''>by</span>
  <span m=''2204920''>the</span> <span m=''2205020''>consequences</span> <span m=''2205700''>of</span>
  <span m=''2205790''>your</span> <span m=''2205880''>decisions.</span> <span m=''2208620''>Data</span>
  <span m=''2208840''>abstraction''s</span> <span m=''2209460''>one</span> <span m=''2209610''>way</span>
  <span m=''2209780''>of</span> <span m=''2209870''>doing</span> <span m=''2210160''>this.</span>
  <span m=''2210550''>What</span> <span m=''2210740''>we</span> <span m=''2210850''>did</span>
  <span m=''2211170''>is we</span> <span m=''2211290''>used</span> <span m=''2211540''>wishful</span>
  <span m=''2211930''>thinking.</span> <span m=''2214540''>See, we</span> <span m=''2214770''>gave</span>
  <span m=''2214970''>a</span> <span m=''2215030''>name</span> <span m=''2215500''>to</span>
  <span m=''2215610''>the</span> <span m=''2215720''>decision.</span> <span m=''2217190''>We</span>
  <span m=''2217300''>said,</span> <span m=''2217770''>make-RAT,</span> <span m=''2218420''>numerator,
  and</span> <span m=''2218910''>denominator</span> <span m=''2220690''>will</span>
  <span m=''2220820''>stand</span> <span m=''2221220''>for</span> <span m=''2221340''>however</span>
  <span m=''2221700''>it''s</span> <span m=''2221830''>going</span> <span m=''2221910''>to</span>
  <span m=''2221980''>be</span> <span m=''2222090''>done,</span> <span m=''2222380''>and
  however</span> <span m=''2222710''>it''s</span> <span m=''2222830''>going</span>
  <span m=''2222900''>to</span> <span m=''2222970''>be</span> <span m=''2223040''>done</span>
  <span m=''2223250''>is</span> <span m=''2223420''>George''s</span> <span m=''2223780''>problem.</span>
  </p><p><span m=''2224080''>But</span> <span m=''2224230''>really,</span> <span m=''2224490''>what</span>
  <span m=''2224640''>that</span> <span m=''2224790''>was</span> <span m=''2224940''>doing</span>
  <span m=''2225610''>is</span> <span m=''2226270''>giving</span> <span m=''2226520''>a</span>
  <span m=''2226550''>name</span> <span m=''2226890''>to</span> <span m=''2226990''>the</span>
  <span m=''2227100''>decision</span> <span m=''2227460''>of</span> <span m=''2227530''>how</span>
  <span m=''2227660''>we''re</span> <span m=''2227770''>going</span> <span m=''2227860''>to</span>
  <span m=''2227950''>do</span> <span m=''2228160''>it,</span> <span m=''2230380''>and</span>
  <span m=''2230520''>then</span> <span m=''2231130''>continuing</span> <span m=''2231800''>as</span>
  <span m=''2232030''>if</span> <span m=''2232180''>we</span> <span m=''2232310''>made</span>
  <span m=''2232540''>the</span> <span m=''2232620''>decision.</span> <span m=''2234400''>And</span>
  <span m=''2234560''>then</span> <span m=''2235480''>eventually,</span> <span m=''2236040''>when</span>
  <span m=''2236150''>we</span> <span m=''2236260''>really</span> <span m=''2236510''>wanted</span>
  <span m=''2236730''>it to</span> <span m=''2236950''>work,</span> <span m=''2237110''>coming</span>
  <span m=''2237410''>back</span> <span m=''2237690''>and</span> <span m=''2237820''>facing</span>
  <span m=''2238160''>what</span> <span m=''2238280''>we</span> <span m=''2238390''>really</span>
  <span m=''2238620''>had</span> <span m=''2238800''>to</span> <span m=''2238880''>do.</span>
  <span m=''2240330''>And</span> <span m=''2240730''>in</span> <span m=''2240900''>fact,</span>
  <span m=''2241170''>we''ll</span> <span m=''2241260''>see</span> <span m=''2241430''>a</span>
  <span m=''2241480''>couple</span> <span m=''2241800''>times</span> <span m=''2242100''>from</span>
  <span m=''2242220''>now</span> <span m=''2242690''>that</span> <span m=''2242970''>you</span>
  <span m=''2243080''>may</span> <span m=''2243230''>never</span> <span m=''2243580''>have</span>
  <span m=''2243760''>to</span> <span m=''2243880''>choose</span> <span m=''2244120''>any</span>
  <span m=''2244280''>particular</span> <span m=''2244810''>representation,</span>
  <span m=''2245440''>ever,</span> <span m=''2245680''>ever.</span> <span m=''2247800''>Anyway,</span>
  <span m=''2248150''>that''s</span> <span m=''2248390''>a</span> <span m=''2248450''>very</span>
  <span m=''2248740''>powerful</span> <span m=''2249170''>design</span> <span m=''2249510''>technique.</span>
  <span m=''2250230''>It''s the</span> <span m=''2250680''>key</span> <span m=''2250890''>to</span>
  <span m=''2250980''>the</span> <span m=''2251070''>reason</span> <span m=''2251340''>people</span>
  <span m=''2251580''>use</span> <span m=''2251760''>data</span> <span m=''2251960''>abstraction.</span>
  <span m=''2254830''>And</span> <span m=''2255010''>we''re</span> <span m=''2255110''>going</span>
  <span m=''2255170''>to</span> <span m=''2255230''>see</span> <span m=''2255420''>that</span>
  <span m=''2255650''>idea</span> <span m=''2256160''>again</span> <span m=''2256540''>and</span>
  <span m=''2256620''>again.</span> <span m=''2257854''>Let''s</span> <span m=''2258296''>stop
  for</span> <span m=''2258738''>questions.</span> </p><p><span m=''2260510''>AUDIENCE:
  What</span> <span m=''2260760''>does</span> <span m=''2260980''>this</span> <span
  m=''2263150''>decision</span> <span m=''2263220''>making</span> <span m=''2263600''>through</span>
  <span m=''2263810''>abstraction</span> <span m=''2264290''>layers</span> <span m=''2265230''>do</span>
  <span m=''2265370''>to</span> <span m=''2265500''>the</span> <span m=''2265720''>axiom</span>
  <span m=''2266190''>of</span> <span m=''2266490''>do</span> <span m=''2266690''>all</span>
  <span m=''2266810''>your</span> <span m=''2266930''>design</span> <span m=''2267500''>before</span>
  <span m=''2267690''>any</span> <span m=''2267870''>of</span> <span m=''2267970''>your</span>
  <span m=''2268110''>code?</span> </p><p><span m=''2269800''>PROFESSOR: Well,</span>
  <span m=''2270070''>that''s</span> <span m=''2271180''>someone''s</span> <span m=''2271610''>axiom,</span>
  <span m=''2272290''>and</span> <span m=''2272390''>I</span> <span m=''2272500''>bet</span>
  <span m=''2272700''>that''s</span> <span m=''2272900''>the</span> <span m=''2273030''>axiom</span>
  <span m=''2273460''>of</span> <span m=''2273540''>someone</span> <span m=''2273860''>who</span>
  <span m=''2273990''>hasn''t</span> <span m=''2274260''>implemented</span> <span
  m=''2274750''>very</span> <span m=''2274990''>large</span> <span m=''2275270''>computer</span>
  <span m=''2275640''>systems</span> <span m=''2276030''>very</span> <span m=''2276230''>much.</span>
  <span m=''2281220''>I said</span> <span m=''2281360''>that</span> <span m=''2281480''>computer</span>
  <span m=''2281860''>science</span> <span m=''2282250''>is a</span> <span m=''2282320''>lot</span>
  <span m=''2282540''>like</span> <span m=''2282720''>magic,</span> <span m=''2283460''>and</span>
  <span m=''2284080''>it''s sort of</span> <span m=''2284190''>good</span> <span m=''2284490''>that</span>
  <span m=''2284620''>it''s</span> <span m=''2284790''>like</span> <span m=''2284960''>magic.</span>
  <span m=''2285270''>There''s</span> <span m=''2285390''>a</span> <span m=''2285430''>bad</span>
  <span m=''2285710''>part</span> <span m=''2285900''>of</span> <span m=''2285990''>computer</span>
  <span m=''2286360''>science</span> <span m=''2286690''>that''s</span> <span m=''2286850''>a</span>
  <span m=''2286900''>lot</span> <span m=''2287100''>like</span> <span m=''2287310''>religion.</span>
  <span m=''2288746''>And</span> <span m=''2291650''>in</span> <span m=''2291790''>general,</span>
  <span m=''2292130''>I</span> <span m=''2292240''>think</span> <span m=''2292350''>people</span>
  <span m=''2292530''>who</span> <span m=''2292720''>really</span> <span m=''2293020''>believe</span>
  <span m=''2293300''>that</span> <span m=''2293450''>you</span> <span m=''2293570''>design</span>
  <span m=''2293960''>everything</span> <span m=''2294380''>before</span> <span m=''2294650''>you</span>
  <span m=''2294750''>implement</span> <span m=''2295220''>it</span> <span m=''2296300''>basically</span>
  <span m=''2296730''>are</span> <span m=''2296800''>people</span> <span m=''2297010''>who</span>
  <span m=''2297220''>haven''t</span> <span m=''2297410''>designed</span> <span m=''2297840''>very
  many</span> <span m=''2298220''>things.</span> </p><p><span m=''2301230''>The</span>
  <span m=''2301430''>real</span> <span m=''2302360''>power is</span> <span m=''2302800''>that</span>
  <span m=''2302950''>you</span> <span m=''2303070''>can</span> <span m=''2303230''>pretend</span>
  <span m=''2303870''>that</span> <span m=''2304190''>you''ve</span> <span m=''2304360''>made</span>
  <span m=''2304590''>the</span> <span m=''2304660''>decision</span> <span m=''2306000''>and</span>
  <span m=''2306150''>then</span> <span m=''2306700''>later</span> <span m=''2307000''>on</span>
  <span m=''2307190''>figure</span> <span m=''2307510''>out</span> <span m=''2307630''>which</span>
  <span m=''2307800''>one</span> <span m=''2307980''>is</span> <span m=''2308120''>right,</span>
  <span m=''2308640''>which</span> <span m=''2308820''>decision</span> <span m=''2309230''>you</span>
  <span m=''2309370''>ought</span> <span m=''2309530''>to</span> <span m=''2309660''>have</span>
  <span m=''2309810''>made.</span> <span m=''2310550''>And</span> <span m=''2310890''>when</span>
  <span m=''2311100''>you</span> <span m=''2311200''>can</span> <span m=''2311320''>do</span>
  <span m=''2311460''>that,</span> <span m=''2311690''>you</span> <span m=''2311790''>have</span>
  <span m=''2311930''>the</span> <span m=''2312000''>best</span> <span m=''2312270''>of</span>
  <span m=''2312330''>both</span> <span m=''2312540''>worlds.</span> </p><p><span
  m=''2315834''>AUDIENCE: Can you</span> <span m=''2316330''>explain</span> <span
  m=''2316780''>the</span> <span m=''2316880''>difference</span> <span m=''2317330''>between</span>
  <span m=''2317800''>let</span> <span m=''2318660''>and</span> <span m=''2319150''>define?</span>
  </p><p><span m=''2320180''>PROFESSOR: Oh,</span> <span m=''2320990''>OK.</span>
  <span m=''2323520''>Let</span> <span m=''2323900''>is</span> <span m=''2326900''>a</span>
  <span m=''2326960''>way</span> <span m=''2327160''>to</span> <span m=''2327580''>establish</span>
  <span m=''2328060''>local</span> <span m=''2328780''>names.</span> <span m=''2335150''>Let</span>
  <span m=''2335250''>me</span> <span m=''2335330''>give</span> <span m=''2335510''>you</span>
  <span m=''2335950''>sort</span> <span m=''2336100''>of</span> <span m=''2336250''>the
  half</span> <span m=''2336580''>answer.</span> <span m=''2337430''>And</span> <span
  m=''2337720''>I''ll say,</span> <span m=''2338880''>later</span> <span m=''2339210''>on</span>
  <span m=''2339350''>we</span> <span m=''2339440''>can</span> <span m=''2339550''>talk</span>
  <span m=''2339750''>about</span> <span m=''2339950''>the</span> <span m=''2340030''>whole</span>
  <span m=''2340720''>very</span> <span m=''2340970''>complicated</span> <span m=''2341630''>thing.</span>
  <span m=''2342960''>But</span> <span m=''2343560''>the</span> <span m=''2343740''>big</span>
  <span m=''2343980''>difference</span> <span m=''2344400''>for</span> <span m=''2344520''>now</span>
  <span m=''2345150''>is</span> <span m=''2345340''>that,</span> <span m=''2345630''>see,</span>
  <span m=''2345750''>when</span> <span m=''2345890''>you''re</span> <span m=''2346000''>typing</span>
  <span m=''2346410''>at</span> <span m=''2346570''>Lisp,</span> <span m=''2347990''>you''re</span>
  <span m=''2348130''>typing</span> <span m=''2348530''>in</span> <span m=''2348680''>this</span>
  <span m=''2349380''>environment</span> <span m=''2349910''>where</span> <span m=''2350020''>you''re</span>
  <span m=''2350170''>making</span> <span m=''2350540''>definitions.</span> <span
  m=''2352020''>And</span> <span m=''2352210''>when</span> <span m=''2352350''>you</span>
  <span m=''2352470''>say</span> <span m=''2352660''>define</span> <span m=''2353270''>a</span>
  <span m=''2353340''>to be</span> <span m=''2353500''>5,</span> <span m=''2356220''>if
  I</span> <span m=''2356490''>say</span> <span m=''2356560''>define</span> <span
  m=''2358590''>a to be</span> <span m=''2358990''>5,</span> <span m=''2360446''>then</span>
  <span m=''2360940''>from</span> <span m=''2361090''>then</span> <span m=''2361300''>on</span>
  <span m=''2361520''>the</span> <span m=''2361600''>thing</span> <span m=''2361790''>will</span>
  <span m=''2361900''>remember</span> <span m=''2362280''>that</span> <span m=''2362750''>a
  is</span> <span m=''2363100''>5.</span> </p><p><span m=''2365640''>Let</span> <span
  m=''2365920''>is</span> <span m=''2366060''>a</span> <span m=''2366110''>way</span>
  <span m=''2367090''>to</span> <span m=''2367210''>set</span> <span m=''2367390''>up</span>
  <span m=''2367500''>a</span> <span m=''2367560''>local</span> <span m=''2367980''>context</span>
  <span m=''2369090''>where</span> <span m=''2369210''>there''s</span> <span m=''2369410''>a</span>
  <span m=''2369460''>definition.</span> <span m=''2371090''>So</span> <span m=''2371280''>if</span>
  <span m=''2371380''>I</span> <span m=''2371470''>type</span> <span m=''2371740''>something</span>
  <span m=''2372140''>like,</span> <span m=''2372340''>saying</span> <span m=''2372720''>let</span>
  <span m=''2376650''>a--</span> <span m=''2377030''>no,</span> <span m=''2377490''>I
  shouldn''t</span> <span m=''2377900''>say</span> <span m=''2378357''>a--</span>
  <span m=''2380642''>if</span> <span m=''2381100''>I</span> <span m=''2381200''>said</span>
  <span m=''2381410''>let</span> <span m=''2382950''>z</span> <span m=''2383360''>be
  10,</span> <span m=''2388400''>and</span> <span m=''2389080''>within</span> <span
  m=''2389410''>that</span> <span m=''2389600''>context,</span> <span m=''2390180''>tell</span>
  <span m=''2390330''>me</span> <span m=''2390480''>what</span> <span m=''2390780''>the</span>
  <span m=''2390880''>sum</span> <span m=''2392020''>of</span> <span m=''2392200''>z</span>
  <span m=''2393210''>and</span> <span m=''2393440''>z</span> <span m=''2393730''>is.</span>
  <span m=''2394280''>So</span> <span m=''2394490''>if I</span> <span m=''2394590''>typed</span>
  <span m=''2394910''>in</span> <span m=''2395080''>this</span> <span m=''2395560''>expression</span>
  <span m=''2396150''>to</span> <span m=''2396260''>Lisp,</span> <span m=''2398530''>and</span>
  <span m=''2398710''>then</span> <span m=''2399780''>this</span> <span m=''2400240''>would</span>
  <span m=''2400360''>put</span> <span m=''2400500''>out</span> <span m=''2400670''>20.</span>
  <span m=''2402210''>However,</span> <span m=''2404180''>then</span> <span m=''2404470''>if</span>
  <span m=''2404610''>I</span> <span m=''2404710''>said</span> <span m=''2404940''>what''s</span>
  <span m=''2405230''>z,</span> <span m=''2405975''>the</span> <span m=''2406380''>computer</span>
  <span m=''2406950''>would</span> <span m=''2407090''>say</span> <span m=''2407340''>that''s</span>
  <span m=''2407540''>an</span> <span m=''2408570''>unbound</span> <span m=''2409230''>variable.</span>
  </p><p><span m=''2410910''>So</span> <span m=''2411080''>let</span> <span m=''2411290''>is</span>
  <span m=''2411410''>a</span> <span m=''2411470''>way</span> <span m=''2411640''>of</span>
  <span m=''2411740''>setting</span> <span m=''2412090''>up</span> <span m=''2412440''>a</span>
  <span m=''2412580''>context</span> <span m=''2413170''>where</span> <span m=''2413260''>you</span>
  <span m=''2413390''>can</span> <span m=''2413510''>make</span> <span m=''2413710''>definitions.</span>
  <span m=''2416320''>But</span> <span m=''2416500''>those</span> <span m=''2416890''>definitions</span>
  <span m=''2417430''>are</span> <span m=''2417490''>local</span> <span m=''2417920''>to</span>
  <span m=''2418030''>this</span> <span m=''2418130''>context.</span> <span m=''2419320''>And</span>
  <span m=''2419600''>of</span> <span m=''2419670''>course,</span> <span m=''2419890''>if</span>
  <span m=''2420000''>I''d</span> <span m=''2420100''>said</span> <span m=''2420920''>a
  in</span> <span m=''2421260''>here,</span> <span m=''2427000''>I''d</span> <span
  m=''2427130''>still</span> <span m=''2427370''>get</span> <span m=''2427560''>20.</span>
  <span m=''2427990''>But</span> <span m=''2428260''>this</span> <span m=''2428510''>a</span>
  <span m=''2430290''>would</span> <span m=''2430490''>not</span> <span m=''2430710''>interfere</span>
  <span m=''2431140''>at</span> <span m=''2431240''>all</span> <span m=''2431340''>with</span>
  <span m=''2431480''>this</span> <span m=''2431670''>one.</span> <span m=''2433960''>So</span>
  <span m=''2434070''>if</span> <span m=''2434160''>I</span> <span m=''2434230''>type</span>
  <span m=''2434500''>this,</span> <span m=''2434810''>and then</span> <span m=''2435060''>type</span>
  <span m=''2435300''>this,</span> <span m=''2435710''>and then</span> <span m=''2435830''>say</span>
  <span m=''2435940''>what''s</span> <span m=''2436210''>a? a</span> <span m=''2436590''>will</span>
  <span m=''2436670''>still</span> <span m=''2436860''>be</span> <span m=''2437010''>5.</span>
  <span m=''2439160''>So</span> <span m=''2439610''>there''s</span> <span m=''2440310''>some</span>
  <span m=''2440480''>other</span> <span m=''2440770''>subtle</span> <span m=''2441080''>differences</span>
  <span m=''2441510''>between</span> <span m=''2441830''>let and</span> <span m=''2442220''>define,</span>
  <span m=''2442470''>but</span> <span m=''2442590''>that''s</span> <span m=''2442840''>the</span>
  <span m=''2443370''>most</span> <span m=''2443710''>important</span> <span m=''2444050''>one.</span>
  </p><p><span m=''2480090''>All right,</span> <span m=''2480270''>well, we''ve</span>
  <span m=''2480610''>looked</span> <span m=''2480930''>at</span> <span m=''2481680''>implementing</span>
  <span m=''2482210''>this</span> <span m=''2482780''>little</span> <span m=''2482980''>system</span>
  <span m=''2483800''>for</span> <span m=''2483970''>doing</span> <span m=''2484290''>arithmetic</span>
  <span m=''2484760''>on</span> <span m=''2484870''>rational</span> <span m=''2485270''>numbers</span>
  <span m=''2486210''>as</span> <span m=''2486410''>an</span> <span m=''2486490''>example</span>
  <span m=''2487470''>of</span> <span m=''2487620''>this</span> <span m=''2487770''>methodology</span>
  <span m=''2488430''>of</span> <span m=''2488500''>data</span> <span m=''2488740''>abstraction.</span>
  <span m=''2491096''>And</span> <span m=''2491530''>that''s</span> <span m=''2492240''>a</span>
  <span m=''2492340''>way</span> <span m=''2492820''>of</span> <span m=''2493080''>controlling</span>
  <span m=''2493560''>complexity</span> <span m=''2493995''>in</span> <span m=''2494430''>large</span>
  <span m=''2494840''>systems.</span> <span m=''2496870''>But,</span> <span m=''2497450''>see,</span>
  <span m=''2497630''>like</span> <span m=''2497850''>procedure</span> <span m=''2498270''>definition,</span>
  <span m=''2499150''>and</span> <span m=''2499330''>like</span> <span m=''2499530''>all</span>
  <span m=''2499810''>the</span> <span m=''2499890''>ways</span> <span m=''2500130''>we''re</span>
  <span m=''2500230''>going</span> <span m=''2500310''>to</span> <span m=''2500390''>talk</span>
  <span m=''2500650''>about</span> <span m=''2500910''>for</span> <span m=''2501020''>controlling</span>
  <span m=''2501420''>complexity,</span> <span m=''2502370''>the</span> <span m=''2502500''>real</span>
  <span m=''2502760''>power</span> <span m=''2503180''>of</span> <span m=''2503250''>these</span>
  <span m=''2503450''>things</span> <span m=''2504800''>show</span> <span m=''2505080''>up</span>
  <span m=''2505250''>not</span> <span m=''2505520''>when</span> <span m=''2505660''>you</span>
  <span m=''2505990''>sort</span> <span m=''2506110''>of</span> <span m=''2506230''>do</span>
  <span m=''2506370''>these</span> <span m=''2506590''>things</span> <span m=''2506820''>in</span>
  <span m=''2506910''>themselves,</span> <span m=''2508150''>like</span> <span m=''2508860''>it''s</span>
  <span m=''2508980''>not</span> <span m=''2509180''>such</span> <span m=''2509370''>a</span>
  <span m=''2509420''>great</span> <span m=''2509700''>thing</span> <span m=''2509880''>that</span>
  <span m=''2510000''>we''ve</span> <span m=''2510120''>done</span> <span m=''2510260''>rational</span>
  <span m=''2510670''>number</span> <span m=''2511120''>arithmetic,</span> <span m=''2512430''>it''s</span>
  <span m=''2512840''>that</span> <span m=''2513720''>you</span> <span m=''2513840''>can</span>
  <span m=''2513990''>use</span> <span m=''2514400''>these</span> <span m=''2515110''>as</span>
  <span m=''2515360''>building</span> <span m=''2515720''>blocks</span> <span m=''2516670''>for</span>
  <span m=''2516800''>making</span> <span m=''2517150''>more</span> <span m=''2517310''>complicated</span>
  <span m=''2517920''>things.</span> </p><p><span m=''2520620''>So</span> <span m=''2520780''>it''s</span>
  <span m=''2521020''>no</span> <span m=''2521100''>wonderful</span> <span m=''2521830''>idea</span>
  <span m=''2522190''>that</span> <span m=''2522350''>you</span> <span m=''2522460''>can</span>
  <span m=''2522570''>just</span> <span m=''2522790''>put</span> <span m=''2522980''>two</span>
  <span m=''2523120''>numbers</span> <span m=''2523460''>together</span> <span m=''2523770''>to</span>
  <span m=''2523840''>form</span> <span m=''2524080''>a</span> <span m=''2524140''>pair.
  If</span> <span m=''2524390''>that''s</span> <span m=''2524640''>all</span> <span
  m=''2524880''>you</span> <span m=''2525040''>ever</span> <span m=''2525240''>wanted</span>
  <span m=''2525440''>to</span> <span m=''2525640''>do,</span> <span m=''2526020''>there</span>
  <span m=''2526220''>are</span> <span m=''2526270''>tons</span> <span m=''2526560''>of</span>
  <span m=''2526670''>ways</span> <span m=''2526890''>that</span> <span m=''2527030''>you</span>
  <span m=''2527160''>can</span> <span m=''2527300''>do</span> <span m=''2527410''>that.</span>
  <span m=''2528450''>The</span> <span m=''2528620''>real</span> <span m=''2528860''>issue</span>
  <span m=''2529040''>is</span> <span m=''2529140''>can</span> <span m=''2529230''>you</span>
  <span m=''2529330''>do that</span> <span m=''2529610''>in</span> <span m=''2529720''>such</span>
  <span m=''2530040''>a</span> <span m=''2530100''>way</span> <span m=''2531490''>so</span>
  <span m=''2531660''>that</span> <span m=''2531820''>the</span> <span m=''2531910''>things</span>
  <span m=''2532170''>that</span> <span m=''2532320''>you</span> <span m=''2532460''>build</span>
  <span m=''2533080''>become</span> <span m=''2533400''>building</span> <span m=''2533790''>blocks</span>
  <span m=''2534100''>for</span> <span m=''2534200''>doing</span> <span m=''2534420''>something</span>
  <span m=''2534750''>even</span> <span m=''2535800''>more</span> <span m=''2536010''>complex?</span>
  <span m=''2536945''>So</span> <span m=''2537330''>whenever</span> <span m=''2537650''>someone</span>
  <span m=''2537920''>shows</span> <span m=''2538160''>you</span> <span m=''2538280''>a</span>
  <span m=''2538330''>method</span> <span m=''2538640''>for</span> <span m=''2538740''>controlling</span>
  <span m=''2539120''>complexity,</span> <span m=''2539385''>you</span> <span m=''2539650''>should</span>
  <span m=''2539810''>say,</span> <span m=''2539930''>yeah,</span> <span m=''2540140''>that''s</span>
  <span m=''2540370''>great,</span> <span m=''2540690''>but</span> <span m=''2540940''>what</span>
  <span m=''2541080''>can</span> <span m=''2541220''>I</span> <span m=''2541330''>build</span>
  <span m=''2541610''>with</span> <span m=''2541730''>it?</span> </p><p><span m=''2545290''>So</span>
  <span m=''2545480''>for</span> <span m=''2545620''>example,</span> <span m=''2548920''>let
  me</span> <span m=''2549080''>just</span> <span m=''2549300''>run</span> <span m=''2549610''>through</span>
  <span m=''2549770''>another</span> <span m=''2550270''>thing</span> <span m=''2550490''>that''s</span>
  <span m=''2550660''>a</span> <span m=''2550700''>lot</span> <span m=''2550980''>like</span>
  <span m=''2551170''>the</span> <span m=''2551250''>rational</span> <span m=''2551620''>number</span>
  <span m=''2551840''>one.</span> <span m=''2552090''>Suppose</span> <span m=''2552270''>we</span>
  <span m=''2552380''>would</span> <span m=''2552480''>like</span> <span m=''2552670''>to</span>
  <span m=''2552780''>represent</span> <span m=''2554160''>points</span> <span m=''2554530''>in</span>
  <span m=''2554630''>the</span> <span m=''2554720''>plane.</span> <span m=''2555760''>You</span>
  <span m=''2555860''>sort</span> <span m=''2555970''>of</span> <span m=''2556090''>say,</span>
  <span m=''2556210''>well,</span> <span m=''2556340''>there''s</span> <span m=''2556530''>a</span>
  <span m=''2556590''>point,</span> <span m=''2557550''>and</span> <span m=''2557870''>we''re</span>
  <span m=''2557970''>going</span> <span m=''2558050''>to</span> <span m=''2558130''>call</span>
  <span m=''2558360''>that</span> <span m=''2558550''>point</span> <span m=''2558890''>p.</span>
  <span m=''2560810''>And</span> <span m=''2564100''>that</span> <span m=''2564330''>point</span>
  <span m=''2564550''>might</span> <span m=''2564720''>have</span> <span m=''2564880''>coordinates,</span>
  <span m=''2567360''>like</span> <span m=''2568470''>this</span> <span m=''2568650''>might</span>
  <span m=''2568810''>be</span> <span m=''2568910''>the</span> <span m=''2569010''>point</span>
  <span m=''2569300''>1</span> <span m=''2569610''>comma</span> <span m=''2569940''>2.</span>
  <span m=''2570330''>The</span> <span m=''2570595''>x-coordinate</span> <span m=''2570950''>might</span>
  <span m=''2571120''>be</span> <span m=''2571240''>1,</span> <span m=''2572120''>and
  it''s</span> <span m=''2572500''>y-coordinate</span> <span m=''2573100''>might</span>
  <span m=''2573310''>be</span> <span m=''2573410''>2.</span> <span m=''2574370''>And</span>
  <span m=''2574820''>we''ll</span> <span m=''2574920''>make</span> <span m=''2575090''>a</span>
  <span m=''2575140''>little</span> <span m=''2575320''>system</span> <span m=''2575700''>for</span>
  <span m=''2576770''>manipulating</span> <span m=''2577310''>points</span> <span
  m=''2577620''>in</span> <span m=''2577700''>the</span> <span m=''2577780''>plane.</span>
  </p><p><span m=''2580450''>And</span> <span m=''2580600''>again,</span> <span m=''2580730''>we</span>
  <span m=''2580860''>can</span> <span m=''2581000''>do</span> <span m=''2581180''>that--</span>
  <span m=''2581470''>here''s</span> <span m=''2583000''>a</span> <span m=''2583040''>little</span>
  <span m=''2583290''>example</span> <span m=''2583730''>of</span> <span m=''2583800''>that.</span>
  <span m=''2587070''>It can</span> <span m=''2587180''>represent</span> <span m=''2587680''>vectors,</span>
  <span m=''2588370''>the</span> <span m=''2588510''>same</span> <span m=''2588810''>as</span>
  <span m=''2588910''>points</span> <span m=''2589180''>in</span> <span m=''2589260''>the</span>
  <span m=''2589330''>plane,</span> <span m=''2590080''>and</span> <span m=''2590240''>we''ll</span>
  <span m=''2590360''>say,</span> <span m=''2591350''>yep,</span> <span m=''2591870''>there''s</span>
  <span m=''2595220''>a</span> <span m=''2595280''>constructor</span> <span m=''2597210''>called</span>
  <span m=''2597550''>make-vector,</span> <span m=''2598160''>make-vector''s</span>
  <span m=''2598730''>going</span> <span m=''2598810''>to</span> <span m=''2598890''>take</span>
  <span m=''2599090''>two</span> <span m=''2599240''>coordinates,</span> <span m=''2601100''>and</span>
  <span m=''2601270''>here</span> <span m=''2601470''>we</span> <span m=''2601610''>can</span>
  <span m=''2601990''>implement</span> <span m=''2602480''>them</span> <span m=''2602630''>if</span>
  <span m=''2602730''>we</span> <span m=''2602830''>like</span> <span m=''2603100''>as
  pairs,</span> <span m=''2604050''>but</span> <span m=''2604180''>the</span> <span
  m=''2604280''>important</span> <span m=''2604650''>thing</span> <span m=''2604760''>is</span>
  <span m=''2604840''>that</span> <span m=''2604950''>there''s</span> <span m=''2605110''>a</span>
  <span m=''2605170''>constructor.</span> <span m=''2607120''>And</span> <span m=''2607260''>then</span>
  <span m=''2607410''>given</span> <span m=''2607710''>some</span> <span m=''2607880''>vector,</span>
  <span m=''2608230''>p,</span> <span m=''2609590''>we</span> <span m=''2609690''>can</span>
  <span m=''2609820''>find its</span> <span m=''2610180''>x-coordinate,</span> <span
  m=''2611890''>or</span> <span m=''2612340''>we</span> <span m=''2612540''>can</span>
  <span m=''2612630''>get</span> <span m=''2612740''>its</span> <span m=''2612870''>y-coordinate.</span>
  <span m=''2613540''>So</span> <span m=''2613630''>there''s</span> <span m=''2613810''>a</span>
  <span m=''2613870''>constructor</span> <span m=''2615080''>and</span> <span m=''2615510''>selectors</span>
  <span m=''2616170''>for</span> <span m=''2616270''>points</span> <span m=''2616580''>in</span>
  <span m=''2616650''>the</span> <span m=''2616720''>plane.</span> </p><p><span m=''2619010''>Well,</span>
  <span m=''2619200''>given</span> <span m=''2619410''>points</span> <span m=''2619700''>in</span>
  <span m=''2619780''>the</span> <span m=''2619850''>plane,</span> <span m=''2620540''>we</span>
  <span m=''2620680''>might</span> <span m=''2620850''>want</span> <span m=''2620930''>to</span>
  <span m=''2621000''>use</span> <span m=''2621310''>them</span> <span m=''2621440''>to</span>
  <span m=''2621570''>build</span> <span m=''2621830''>something.</span> <span m=''2622420''>So</span>
  <span m=''2622650''>for</span> <span m=''2622830''>instance,</span> <span m=''2623150''>we</span>
  <span m=''2623260''>might</span> <span m=''2623450''>want</span> <span m=''2623550''>to</span>
  <span m=''2623660''>talk</span> <span m=''2624020''>about,</span> <span m=''2625100''>we</span>
  <span m=''2625220''>might</span> <span m=''2625380''>have</span> <span m=''2625540''>a
  point,</span> <span m=''2625920''>p,</span> <span m=''2626740''>and a</span> <span
  m=''2626850''>point,</span> <span m=''2627150''>q,</span> <span m=''2628460''>and</span>
  <span m=''2628630''>p</span> <span m=''2628820''>might</span> <span m=''2629040''>be</span>
  <span m=''2629720''>the</span> <span m=''2629840''>point</span> <span m=''2630100''>1,
  2,</span> <span m=''2631000''>and</span> <span m=''2631220''>q</span> <span m=''2631360''>might</span>
  <span m=''2631570''>be</span> <span m=''2631680''>the</span> <span m=''2631800''>point</span>
  <span m=''2632280''>2, 3.</span> <span m=''2634790''>And</span> <span m=''2635010''>we</span>
  <span m=''2635090''>might</span> <span m=''2635290''>want</span> <span m=''2635400''>to</span>
  <span m=''2635510''>talk</span> <span m=''2635880''>about</span> <span m=''2637280''>the</span>
  <span m=''2637410''>line</span> <span m=''2637710''>segment</span> <span m=''2638770''>that</span>
  <span m=''2638970''>starts</span> <span m=''2639320''>at</span> <span m=''2639430''>p</span>
  <span m=''2639650''>and</span> <span m=''2639750''>ends</span> <span m=''2640040''>at</span>
  <span m=''2640400''>q.</span> <span m=''2641570''>And</span> <span m=''2641970''>that</span>
  <span m=''2642360''>might</span> <span m=''2642530''>be</span> <span m=''2642650''>the</span>
  <span m=''2642740''>segment</span> <span m=''2643250''>s.</span> <span m=''2645180''>So</span>
  <span m=''2645340''>we</span> <span m=''2645420''>might</span> <span m=''2645580''>want</span>
  <span m=''2645680''>to</span> <span m=''2645770''>build</span> <span m=''2646910''>points</span>
  <span m=''2650820''>for</span> <span m=''2651410''>vectors</span> <span m=''2651920''>in</span>
  <span m=''2652000''>terms</span> <span m=''2652220''>of</span> <span m=''2652300''>numbers,</span>
  <span m=''2652870''>and</span> <span m=''2653030''>segments</span> <span m=''2653470''>in</span>
  <span m=''2653550''>terms</span> <span m=''2653810''>of</span> <span m=''2653970''>vectors.</span>
  <span m=''2656410''>So</span> <span m=''2656640''>we</span> <span m=''2656740''>can</span>
  <span m=''2657040''>represent</span> <span m=''2657520''>line</span> <span m=''2657770''>segments</span>
  <span m=''2658180''>in</span> <span m=''2658240''>exactly</span> <span m=''2658690''>the</span>
  <span m=''2658770''>same</span> <span m=''2659050''>way.</span> </p><p><span m=''2659920''>All
  right,</span> <span m=''2660160''>so</span> <span m=''2660290''>the</span> <span
  m=''2660340''>line</span> <span m=''2660740''>segment</span> <span m=''2661050''>from</span>
  <span m=''2661170''>p to</span> <span m=''2661430''>q,</span> <span m=''2661820''>we''ll</span>
  <span m=''2661950''>say</span> <span m=''2662100''>there''s</span> <span m=''2662300''>a</span>
  <span m=''2662360''>constructor,</span> <span m=''2663340''>make-segment.</span>
  <span m=''2667010''>And</span> <span m=''2668210''>make</span> <span m=''2668480''>up</span>
  <span m=''2668610''>names</span> <span m=''2668890''>for</span> <span m=''2668960''>the</span>
  <span m=''2669050''>selectors,</span> <span m=''2669530''>the</span> <span m=''2669600''>starting</span>
  <span m=''2670020''>point</span> <span m=''2670270''>of</span> <span m=''2670340''>the</span>
  <span m=''2670430''>segment</span> <span m=''2671320''>and</span> <span m=''2671450''>the</span>
  <span m=''2671570''>ending</span> <span m=''2671820''>point</span> <span m=''2672020''>of</span>
  <span m=''2672070''>the</span> <span m=''2672130''>segment.</span> <span m=''2672560''>And
  again,</span> <span m=''2672840''>we</span> <span m=''2672950''>can</span> <span
  m=''2673080''>implement</span> <span m=''2673440''>a</span> <span m=''2673490''>segment</span>
  <span m=''2674220''>using</span> <span m=''2674500''>cons</span> <span m=''2674755''>as</span>
  <span m=''2675010''>a</span> <span m=''2675060''>pair</span> <span m=''2675290''>of</span>
  <span m=''2675370''>points,</span> <span m=''2677200''>and</span> <span m=''2677730''>car</span>
  <span m=''2678060''>and cdr</span> <span m=''2678290''>get</span> <span m=''2678470''>out</span>
  <span m=''2678630''>the</span> <span m=''2678710''>two</span> <span m=''2678860''>points</span>
  <span m=''2679210''>that</span> <span m=''2679320''>we</span> <span m=''2679430''>put</span>
  <span m=''2679610''>together</span> <span m=''2679980''>to</span> <span m=''2680040''>get</span>
  <span m=''2680200''>the</span> <span m=''2680270''>segment.</span> </p><p><span
  m=''2684820''>Well,</span> <span m=''2684960''>now</span> <span m=''2685080''>having</span>
  <span m=''2685340''>done</span> <span m=''2685570''>that,</span> <span m=''2688000''>we</span>
  <span m=''2688110''>can</span> <span m=''2688210''>have</span> <span m=''2688370''>some</span>
  <span m=''2688520''>operations</span> <span m=''2689210''>on</span> <span m=''2689450''>them.</span>
  <span m=''2691920''>Like</span> <span m=''2692140''>we</span> <span m=''2692230''>could</span>
  <span m=''2692390''>say,</span> <span m=''2692770''>what''s</span> <span m=''2694950''>the</span>
  <span m=''2695040''>midpoint</span> <span m=''2695620''>of</span> <span m=''2695720''>a</span>
  <span m=''2695770''>line</span> <span m=''2696030''>segment?</span> <span m=''2697610''>So</span>
  <span m=''2697750''>here''s</span> <span m=''2697940''>the</span> <span m=''2698040''>midpoint</span>
  <span m=''2698890''>of</span> <span m=''2699030''>a</span> <span m=''2699060''>line</span>
  <span m=''2699360''>segment,</span> <span m=''2700140''>that''s</span> <span m=''2700420''>going</span>
  <span m=''2700480''>to</span> <span m=''2700540''>be</span> <span m=''2700640''>the</span>
  <span m=''2702580''>points</span> <span m=''2703240''>whose</span> <span m=''2703630''>coordinates</span>
  <span m=''2704870''>are</span> <span m=''2705000''>the</span> <span m=''2705180''>averages</span>
  <span m=''2705880''>of</span> <span m=''2705980''>the</span> <span m=''2706070''>coordinates</span>
  <span m=''2706510''>of</span> <span m=''2706570''>the</span> <span m=''2706700''>endpoints.</span>
  <span m=''2707310''>OK,</span> <span m=''2708280''>there''s</span> <span m=''2708470''>the</span>
  <span m=''2708550''>midpoint.</span> </p><p><span m=''2710170''>So</span> <span
  m=''2710360''>to</span> <span m=''2710450''>get</span> <span m=''2710630''>the</span>
  <span m=''2710710''>midpoint</span> <span m=''2711300''>of</span> <span m=''2711390''>a</span>
  <span m=''2711440''>line</span> <span m=''2711690''>segment,</span> <span m=''2712060''>s,</span>
  <span m=''2713960''>we''ll</span> <span m=''2714070''>just</span> <span m=''2714290''>say</span>
  <span m=''2715420''>grab</span> <span m=''2715760''>the</span> <span m=''2716140''>starting</span>
  <span m=''2716550''>point</span> <span m=''2716780''>to</span> <span m=''2716850''>the</span>
  <span m=''2716930''>segment,</span> <span m=''2717630''>grab</span> <span m=''2717860''>the</span>
  <span m=''2717980''>ending</span> <span m=''2718240''>point</span> <span m=''2718450''>of</span>
  <span m=''2718510''>the</span> <span m=''2718560''>segment,</span> <span m=''2720320''>and</span>
  <span m=''2720530''>now</span> <span m=''2720560''>make</span> <span m=''2720810''>a</span>
  <span m=''2720870''>vector--</span> <span m=''2721640''>make</span> <span m=''2721860''>a</span>
  <span m=''2721910''>point</span> <span m=''2723060''>whose</span> <span m=''2723300''>coordinates</span>
  <span m=''2723900''>are</span> <span m=''2724500''>the</span> <span m=''2724670''>average</span>
  <span m=''2726130''>of</span> <span m=''2726300''>the</span> <span m=''2726480''>x-coordinate</span>
  <span m=''2727160''>of</span> <span m=''2727240''>the</span> <span m=''2727340''>first</span>
  <span m=''2727630''>point</span> <span m=''2727880''>and</span> <span m=''2727970''>the</span>
  <span m=''2728050''>x-coordinate</span> <span m=''2728420''>of</span> <span m=''2728510''>the</span>
  <span m=''2728680''>second</span> <span m=''2728860''>point,</span> <span m=''2730220''>and</span>
  <span m=''2730360''>whose</span> <span m=''2730510''>y-coordinate</span> <span m=''2731200''>is</span>
  <span m=''2731340''>the</span> <span m=''2731460''>average</span> <span m=''2731860''>of</span>
  <span m=''2731930''>the</span> <span m=''2732010''>y-coordinates.</span> <span m=''2733530''>So</span>
  <span m=''2733890''>there''s</span> <span m=''2734140''>an</span> <span m=''2734200''>implementation</span>
  <span m=''2735280''>of</span> <span m=''2735510''>midpoint.</span> </p><p><span
  m=''2737810''>And</span> <span m=''2738000''>then</span> <span m=''2739500''>similarly,</span>
  <span m=''2741350''>we</span> <span m=''2741490''>can</span> <span m=''2741630''>build</span>
  <span m=''2741840''>something</span> <span m=''2742130''>like</span> <span m=''2742320''>the</span>
  <span m=''2742400''>length</span> <span m=''2742730''>of</span> <span m=''2742800''>the</span>
  <span m=''2742870''>segment.</span> <span m=''2744450''>The</span> <span m=''2744530''>length</span>
  <span m=''2744840''>of</span> <span m=''2744910''>the</span> <span m=''2744970''>segment</span>
  <span m=''2746230''>is</span> <span m=''2746410''>a</span> <span m=''2746460''>thing</span>
  <span m=''2746710''>whose--</span> <span m=''2750410''>use</span> <span m=''2750630''>Pythagoras''s</span>
  <span m=''2751720''>rule,</span> <span m=''2752040''>the</span> <span m=''2752160''>length</span>
  <span m=''2752350''>of</span> <span m=''2752430''>the</span> <span m=''2752520''>segment</span>
  <span m=''2752850''>is</span> <span m=''2752940''>the</span> <span m=''2753000''>square</span>
  <span m=''2753350''>root</span> <span m=''2753570''>of</span> <span m=''2753990''>the</span>
  <span m=''2754210''>d x</span> <span m=''2754390''>squared</span> <span m=''2755470''>plus</span>
  <span m=''2755680''>d</span> <span m=''2755790''>y</span> <span m=''2756010''>squared.</span>
  <span m=''2757100''>We''ll</span> <span m=''2757210''>say</span> <span m=''2757510''>to</span>
  <span m=''2757770''>get</span> <span m=''2757930''>the</span> <span m=''2758010''>length</span>
  <span m=''2758420''>of</span> <span m=''2758550''>a</span> <span m=''2758600''>line</span>
  <span m=''2758900''>segment,</span> <span m=''2760600''>we''ll</span> <span m=''2760770''>let</span>
  <span m=''2760880''>dx</span> <span m=''2762200''>be</span> <span m=''2762420''>the</span>
  <span m=''2763160''>difference</span> <span m=''2764560''>of</span> <span m=''2764700''>the</span>
  <span m=''2764850''>x-coordinate</span> <span m=''2766190''>of</span> <span m=''2766380''>one</span>
  <span m=''2766570''>endpoint</span> <span m=''2769030''>and</span> <span m=''2769160''>the</span>
  <span m=''2769250''>x-coordinate</span> <span m=''2769660''>of</span> <span m=''2769730''>the</span>
  <span m=''2769860''>other</span> <span m=''2770030''>endpoint,</span> <span m=''2771560''>and</span>
  <span m=''2771720''>we''ll</span> <span m=''2771980''>let</span> <span m=''2772180''>dy</span>
  <span m=''2773300''>be</span> <span m=''2773460''>the</span> <span m=''2773560''>difference</span>
  <span m=''2773910''>of</span> <span m=''2773970''>the</span> <span m=''2774030''>y-coordinates.</span>
  <span m=''2776260''>And</span> <span m=''2776530''>then we''ll</span> <span m=''2776650''>take</span>
  <span m=''2776880''>the</span> <span m=''2776960''>square</span> <span m=''2777310''>root</span>
  <span m=''2777860''>of</span> <span m=''2777970''>the</span> <span m=''2778080''>sum</span>
  <span m=''2778320''>of</span> <span m=''2778390''>the</span> <span m=''2778450''>squares</span>
  <span m=''2779290''>of</span> <span m=''2779440''>dx</span> <span m=''2779830''>and</span>
  <span m=''2779940''>dy,</span> <span m=''2780310''>that''s</span> <span m=''2780460''>what</span>
  <span m=''2780570''>this</span> <span m=''2780740''>says.</span> <span m=''2782251''>All
  right, so</span> <span m=''2782640''>there''s</span> <span m=''2782870''>an</span>
  <span m=''2782950''>implementation</span> <span m=''2784210''>of</span> <span m=''2784390''>length.</span>
  </p><p><span m=''2786190''>And</span> <span m=''2786310''>again,</span> <span m=''2791510''>what</span>
  <span m=''2791650''>we</span> <span m=''2791780''>built</span> <span m=''2792840''>is</span>
  <span m=''2792980''>a</span> <span m=''2793050''>layered</span> <span m=''2793760''>system.</span>
  <span m=''2795760''>We</span> <span m=''2796020''>built</span> <span m=''2796250''>a</span>
  <span m=''2796290''>system</span> <span m=''2797280''>which</span> <span m=''2797580''>has,</span>
  <span m=''2798980''>well,</span> <span m=''2799360''>say</span> <span m=''2799590''>up</span>
  <span m=''2799730''>here</span> <span m=''2799880''>there''s</span> <span m=''2800040''>segments.</span>
  <span m=''2807430''>And</span> <span m=''2807570''>then</span> <span m=''2807710''>there''s</span>
  <span m=''2807870''>an</span> <span m=''2807960''>abstraction</span> <span m=''2808530''>barrier.</span>
  <span m=''2810530''>The</span> <span m=''2811190''>abstraction</span> <span m=''2811760''>barrier</span>
  <span m=''2812140''>separates</span> <span m=''2814170''>the</span> <span m=''2814290''>implementation</span>
  <span m=''2816880''>of</span> <span m=''2817010''>segments</span> <span m=''2817480''>from</span>
  <span m=''2817580''>the</span> <span m=''2817680''>implementation</span> <span m=''2818430''>of</span>
  <span m=''2818500''>vectors</span> <span m=''2818870''>and</span> <span m=''2819000''>points,</span>
  <span m=''2819500''>and</span> <span m=''2819600''>what</span> <span m=''2819740''>that</span>
  <span m=''2819870''>abstraction</span> <span m=''2820360''>barrier</span> <span
  m=''2820720''>is</span> <span m=''2822460''>are</span> <span m=''2822860''>the</span>
  <span m=''2822950''>constructors</span> <span m=''2823510''>and</span> <span m=''2823620''>selectors.</span>
  <span m=''2824260''>It''s</span> <span m=''2824320''>make-segment,</span> <span
  m=''2827370''>and</span> <span m=''2827620''>segment-start,</span> <span m=''2833970''>and</span>
  <span m=''2834340''>segment-end.</span> </p><p><span m=''2838030''>And</span> <span
  m=''2838160''>then</span> <span m=''2838350''>there are</span> <span m=''2838500''>vectors.</span>
  <span m=''2840120''>And</span> <span m=''2840300''>vectors</span> <span m=''2840820''>in</span>
  <span m=''2840920''>turn</span> <span m=''2842120''>are</span> <span m=''2842270''>built</span>
  <span m=''2842600''>on</span> <span m=''2842800''>top</span> <span m=''2843110''>of</span>
  <span m=''2843520''>pairs</span> <span m=''2843880''>and</span> <span m=''2843990''>numbers.</span>
  <span m=''2845600''>So I''ll say</span> <span m=''2845800''>pairs</span> <span m=''2848810''>and</span>
  <span m=''2849000''>numbers.</span> <span m=''2849670''>And</span> <span m=''2850240''>that</span>
  <span m=''2850680''>has</span> <span m=''2850830''>its</span> <span m=''2850970''>own</span>
  <span m=''2851230''>abstraction</span> <span m=''2851740''>barrier,</span> <span
  m=''2852930''>which</span> <span m=''2853150''>is</span> <span m=''2853250''>make-vector,</span>
  <span m=''2859580''>and</span> <span m=''2859760''>x-coordinate,</span> <span m=''2861800''>and</span>
  <span m=''2862140''>y-coordinate.</span> <span m=''2866920''>So</span> <span m=''2867150''>we</span>
  <span m=''2867260''>have,</span> <span m=''2867480''>again,</span> <span m=''2867890''>a</span>
  <span m=''2868040''>layered</span> <span m=''2868530''>system.</span> <span m=''2868930''>You''re</span>
  <span m=''2869040''>starting</span> <span m=''2869500''>to</span> <span m=''2869610''>see</span>
  <span m=''2870600''>that</span> <span m=''2870940''>there</span> <span m=''2871050''>are</span>
  <span m=''2871080''>layers</span> <span m=''2871490''>here.</span> </p><p><span
  m=''2872080''>I</span> <span m=''2872200''>ought</span> <span m=''2872320''>to</span>
  <span m=''2872360''>mention,</span> <span m=''2873630''>there</span> <span m=''2873800''>is
  a</span> <span m=''2873860''>very</span> <span m=''2874170''>important</span> <span
  m=''2874630''>thing</span> <span m=''2877470''>that</span> <span m=''2877900''>I</span>
  <span m=''2878080''>kind</span> <span m=''2878240''>of</span> <span m=''2878410''>took</span>
  <span m=''2878640''>for</span> <span m=''2878750''>granted.</span> <span m=''2882016''>And</span>
  <span m=''2882950''>it''s</span> <span m=''2883130''>sort</span> <span m=''2883240''>of</span>
  <span m=''2883350''>so</span> <span m=''2883560''>natural,</span> <span m=''2883820''>but</span>
  <span m=''2884080''>on</span> <span m=''2884180''>the</span> <span m=''2884280''>other</span>
  <span m=''2884420''>hand</span> <span m=''2884670''>it''s</span> <span m=''2886430''>a</span>
  <span m=''2886700''>very</span> <span m=''2887080''>important</span> <span m=''2887420''>thing.</span>
  <span m=''2887580''>Notice</span> <span m=''2888130''>that</span> <span m=''2888320''>in</span>
  <span m=''2888400''>order</span> <span m=''2888720''>to</span> <span m=''2889190''>represent</span>
  <span m=''2889780''>this</span> <span m=''2889840''>segment</span> <span m=''2890230''>s,</span>
  <span m=''2891890''>I</span> <span m=''2892070''>said</span> <span m=''2892390''>this</span>
  <span m=''2892660''>segment</span> <span m=''2893020''>is</span> <span m=''2893170''>a</span>
  <span m=''2893230''>pair</span> <span m=''2893700''>of</span> <span m=''2893910''>points.</span>
  </p><p><span m=''2896600''>And</span> <span m=''2896690''>a</span> <span m=''2896780''>point</span>
  <span m=''2897110''>is</span> <span m=''2897250''>a</span> <span m=''2897310''>pair</span>
  <span m=''2897780''>of</span> <span m=''2897940''>numbers.</span> <span m=''2899120''>And</span>
  <span m=''2899270''>if</span> <span m=''2899340''>I were</span> <span m=''2899520''>going</span>
  <span m=''2899590''>to</span> <span m=''2899670''>draw</span> <span m=''2899980''>the</span>
  <span m=''2900080''>box</span> <span m=''2900390''>and</span> <span m=''2900500''>pointers</span>
  <span m=''2901750''>structure</span> <span m=''2902180''>for</span> <span m=''2902300''>that,</span>
  <span m=''2903940''>I</span> <span m=''2904020''>would</span> <span m=''2904150''>say,</span>
  <span m=''2904310''>oh,</span> <span m=''2904450''>the</span> <span m=''2904560''>segment</span>
  <span m=''2905080''>is,</span> <span m=''2906390''>given</span> <span m=''2906650''>those</span>
  <span m=''2907180''>particular</span> <span m=''2908280''>representations</span>
  <span m=''2909130''>that</span> <span m=''2909200''>I</span> <span m=''2909280''>showed</span>
  <span m=''2909560''>you,</span> <span m=''2909780''>I''d say</span> <span m=''2909900''>this</span>
  <span m=''2910100''>segment</span> <span m=''2910470''>s</span> <span m=''2911010''>is</span>
  <span m=''2911980''>a</span> <span m=''2912300''>pair,</span> <span m=''2914050''>and</span>
  <span m=''2914160''>the</span> <span m=''2914270''>first</span> <span m=''2914600''>thing</span>
  <span m=''2914750''>in</span> <span m=''2914830''>the</span> <span m=''2914910''>pair</span>
  <span m=''2916090''>is</span> <span m=''2918070''>a</span> <span m=''2918180''>vector,</span>
  <span m=''2920600''>and</span> <span m=''2920760''>the</span> <span m=''2920830''>vector</span>
  <span m=''2921240''>is</span> <span m=''2923220''>a</span> <span m=''2923340''>pair</span>
  <span m=''2923630''>of</span> <span m=''2923710''>numbers.</span> <span m=''2925430''>And
  that''s</span> <span m=''2926130''>this,</span> <span m=''2926400''>that''s</span>
  <span m=''2926620''>p.</span> <span m=''2930190''>And</span> <span m=''2930550''>the</span>
  <span m=''2931010''>other</span> <span m=''2931250''>thing</span> <span m=''2931460''>in</span>
  <span m=''2931540''>the</span> <span m=''2931660''>segment</span> <span m=''2932060''>is</span>
  <span m=''2932270''>q,</span> <span m=''2933380''>which</span> <span m=''2933580''>is</span>
  <span m=''2933710''>itself</span> <span m=''2935330''>a</span> <span m=''2935450''>pair</span>
  <span m=''2937674''>of</span> <span m=''2938110''>numbers.</span> </p><p><span m=''2940100''>So</span>
  <span m=''2940240''>I</span> <span m=''2940300''>almost</span> <span m=''2940680''>took</span>
  <span m=''2940840''>it</span> <span m=''2940980''>for</span> <span m=''2941090''>granted</span>
  <span m=''2941520''>when</span> <span m=''2941660''>I</span> <span m=''2941750''>said</span>
  <span m=''2942600''>that</span> <span m=''2943570''>cons</span> <span m=''2944070''>allows</span>
  <span m=''2944480''>you</span> <span m=''2945220''>to</span> <span m=''2945380''>put</span>
  <span m=''2945600''>things</span> <span m=''2946160''>together.</span> <span m=''2948960''>But</span>
  <span m=''2949930''>it''s</span> <span m=''2950150''>very</span> <span m=''2950370''>easy</span>
  <span m=''2951330''>to</span> <span m=''2951690''>not</span> <span m=''2951860''>appreciate</span>
  <span m=''2952420''>that,</span> <span m=''2952890''>because</span> <span m=''2953110''>notice,</span>
  <span m=''2954660''>some</span> <span m=''2954950''>of</span> <span m=''2955030''>the</span>
  <span m=''2955110''>things</span> <span m=''2955610''>I</span> <span m=''2955690''>can</span>
  <span m=''2955850''>put</span> <span m=''2956040''>together</span> <span m=''2957490''>can</span>
  <span m=''2957650''>themselves</span> <span m=''2958120''>be</span> <span m=''2958250''>pairs.</span>
  <span m=''2960720''>And</span> <span m=''2960840''>let</span> <span m=''2960950''>me</span>
  <span m=''2961050''>introduce</span> <span m=''2961460''>a</span> <span m=''2961510''>word</span>
  <span m=''2961830''>that</span> <span m=''2961960''>I''ll</span> <span m=''2962440''>talk</span>
  <span m=''2962840''>about</span> <span m=''2963040''>more</span> <span m=''2963210''>next</span>
  <span m=''2963510''>time,</span> <span m=''2964400''>it''s</span> <span m=''2964510''>one</span>
  <span m=''2964630''>of</span> <span m=''2964680''>my</span> <span m=''2965810''>favorite</span>
  <span m=''2966190''>words,</span> <span m=''2966450''>called</span> <span m=''2966660''>closure.</span>
  <span m=''2970640''>And</span> <span m=''2970750''>by</span> <span m=''2970850''>closure</span>
  <span m=''2971380''>I</span> <span m=''2971510''>mean</span> <span m=''2972550''>that</span>
  <span m=''2973170''>the</span> <span m=''2973520''>means</span> <span m=''2973880''>of</span>
  <span m=''2973990''>combination</span> <span m=''2974780''>in</span> <span m=''2974950''>your</span>
  <span m=''2975180''>system</span> <span m=''2976540''>are</span> <span m=''2976710''>such</span>
  <span m=''2977080''>that</span> <span m=''2977940''>when</span> <span m=''2978150''>you</span>
  <span m=''2978250''>put</span> <span m=''2978450''>things</span> <span m=''2978680''>together</span>
  <span m=''2979040''>using</span> <span m=''2979390''>them,</span> <span m=''2979650''>like</span>
  <span m=''2979850''>we</span> <span m=''2979940''>make</span> <span m=''2980140''>a
  pair,</span> <span m=''2982070''>you</span> <span m=''2982200''>can</span> <span
  m=''2982380''>then</span> <span m=''2982570''>put</span> <span m=''2982770''>those</span>
  <span m=''2983040''>together</span> <span m=''2983430''>with</span> <span m=''2983530''>the</span>
  <span m=''2983620''>same</span> <span m=''2983870''>means</span> <span m=''2984080''>of</span>
  <span m=''2984160''>combination.</span> <span m=''2985080''>So</span> <span m=''2985390''>I</span>
  <span m=''2985470''>can</span> <span m=''2985600''>have</span> <span m=''2985820''>not</span>
  <span m=''2986010''>only</span> <span m=''2986250''>a</span> <span m=''2986300''>pair</span>
  <span m=''2986620''>of</span> <span m=''2986700''>numbers,</span> <span m=''2987370''>but</span>
  <span m=''2987710''>I</span> <span m=''2987780''>can</span> <span m=''2987900''>have</span>
  <span m=''2988060''>a</span> <span m=''2988120''>pair</span> <span m=''2988380''>of
  pairs.</span> </p><p><span m=''2991710''>So</span> <span m=''2991920''>for</span>
  <span m=''2992100''>instance,</span> <span m=''2995560''>making</span> <span m=''2995910''>arrays</span>
  <span m=''2996390''>in</span> <span m=''2996450''>a</span> <span m=''2996500''>language</span>
  <span m=''2996860''>like</span> <span m=''2997080''>Fortran</span> <span m=''2997920''>is</span>
  <span m=''2998070''>not</span> <span m=''2998170''>a</span> <span m=''2998270''>closed</span>
  <span m=''2998770''>means</span> <span m=''2999000''>of</span> <span m=''2999080''>combination,</span>
  <span m=''2999690''>because</span> <span m=''2999920''>I</span> <span m=''2999980''>can</span>
  <span m=''3000120''>make</span> <span m=''3000290''>an</span> <span m=''3000380''>array</span>
  <span m=''3000620''>of</span> <span m=''3000720''>numbers,</span> <span m=''3001575''>but</span>
  <span m=''3001860''>I</span> <span m=''3002010''>can''t</span> <span m=''3002200''>make</span>
  <span m=''3002350''>an</span> <span m=''3002430''>array</span> <span m=''3002680''>of</span>
  <span m=''3002810''>arrays.</span> <span m=''3005790''>And</span> <span m=''3006020''>one</span>
  <span m=''3006250''>of</span> <span m=''3006320''>the</span> <span m=''3006380''>things</span>
  <span m=''3006640''>that</span> <span m=''3006780''>you</span> <span m=''3006880''>should</span>
  <span m=''3007060''>ask,</span> <span m=''3007710''>one</span> <span m=''3007930''>of</span>
  <span m=''3008010''>your</span> <span m=''3008700''>tests</span> <span m=''3009060''>of</span>
  <span m=''3009190''>quality</span> <span m=''3010570''>for</span> <span m=''3010740''>a</span>
  <span m=''3010780''>means</span> <span m=''3011050''>of</span> <span m=''3011130''>combination</span>
  <span m=''3011770''>that</span> <span m=''3011840''>someone</span> <span m=''3012150''>shows</span>
  <span m=''3012430''>you,</span> <span m=''3012920''>is</span> <span m=''3013500''>gee,</span>
  <span m=''3014780''>are</span> <span m=''3014940''>the</span> <span m=''3015060''>things</span>
  <span m=''3015330''>you</span> <span m=''3015460''>make</span> <span m=''3015620''>closed</span>
  <span m=''3016140''>under</span> <span m=''3016300''>that</span> <span m=''3016500''>means</span>
  <span m=''3016720''>of</span> <span m=''3016780''>combination?</span> <span m=''3018340''>So</span>
  <span m=''3019100''>pairs</span> <span m=''3019400''>would</span> <span m=''3019520''>not</span>
  <span m=''3019750''>be</span> <span m=''3019850''>nearly</span> <span m=''3020160''>so</span>
  <span m=''3020340''>interesting</span> <span m=''3020700''>if</span> <span m=''3020800''>all</span>
  <span m=''3021030''>I</span> <span m=''3021120''>could</span> <span m=''3021290''>do</span>
  <span m=''3021460''>was</span> <span m=''3021610''>make</span> <span m=''3021810''>a</span>
  <span m=''3021870''>pair</span> <span m=''3022100''>of</span> <span m=''3022180''>numbers.</span>
  <span m=''3023160''>I</span> <span m=''3023280''>couldn''t</span> <span m=''3023510''>build</span>
  <span m=''3023630''>very</span> <span m=''3023860''>much</span> <span m=''3024020''>structure
  at</span> <span m=''3024380''>all.</span> </p><p><span m=''3026820''>OK, well,</span>
  <span m=''3027110''>we''ll</span> <span m=''3027380''>come</span> <span m=''3027540''>back</span>
  <span m=''3027780''>to</span> <span m=''3027890''>that.</span> <span m=''3028170''>I
  just</span> <span m=''3028490''>wanted</span> <span m=''3028680''>to</span> <span
  m=''3028740''>mention</span> <span m=''3029040''>it</span> <span m=''3029140''>now.</span>
  <span m=''3029300''>You''ll</span> <span m=''3029430''>hear</span> <span m=''3029620''>a</span>
  <span m=''3029720''>lot</span> <span m=''3029820''>about</span> <span m=''3030110''>closure</span>
  <span m=''3030460''>later</span> <span m=''3030720''>on.</span> </p><p><span m=''3032170''>You</span>
  <span m=''3032290''>can</span> <span m=''3032400''>also</span> <span m=''3032670''>see</span>
  <span m=''3035560''>the</span> <span m=''3035790''>potential</span> <span m=''3037340''>for</span>
  <span m=''3037580''>losing</span> <span m=''3038000''>control</span> <span m=''3038420''>of</span>
  <span m=''3038520''>complexity</span> <span m=''3039330''>as</span> <span m=''3039420''>you</span>
  <span m=''3039500''>have</span> <span m=''3039670''>a</span> <span m=''3039730''>layered</span>
  <span m=''3040140''>system</span> <span m=''3040710''>if</span> <span m=''3040860''>you</span>
  <span m=''3040970''>don''t</span> <span m=''3041310''>use</span> <span m=''3041510''>data</span>
  <span m=''3041760''>abstraction.</span> <span m=''3044030''>Let''s</span> <span
  m=''3044310''>go</span> <span m=''3044390''>back</span> <span m=''3045570''>and</span>
  <span m=''3045670''>look</span> <span m=''3045790''>at</span> <span m=''3045910''>this</span>
  <span m=''3045990''>slide</span> <span m=''3046360''>for</span> <span m=''3046500''>length.</span>
  <span m=''3048130''>Length</span> <span m=''3049120''>works</span> <span m=''3049470''>and</span>
  <span m=''3049570''>is</span> <span m=''3049650''>a</span> <span m=''3049710''>simple</span>
  <span m=''3050050''>thing</span> <span m=''3050960''>because</span> <span m=''3051500''>I</span>
  <span m=''3051590''>can</span> <span m=''3051750''>say,</span> <span m=''3052826''>when</span>
  <span m=''3053190''>I</span> <span m=''3053330''>want</span> <span m=''3053430''>to</span>
  <span m=''3053520''>get</span> <span m=''3053880''>this</span> <span m=''3054110''>value,</span>
  <span m=''3054710''>I</span> <span m=''3054850''>can</span> <span m=''3055030''>say,</span>
  <span m=''3055190''>oh,</span> <span m=''3055510''>that</span> <span m=''3055850''>is</span>
  <span m=''3056220''>the</span> <span m=''3056450''>x-coordinate</span> <span m=''3058250''>of</span>
  <span m=''3058770''>the</span> <span m=''3059100''>first</span> <span m=''3059450''>endpoint</span>
  <span m=''3059960''>of</span> <span m=''3060100''>the</span> <span m=''3060170''>segment.</span>
  <span m=''3062990''>And</span> <span m=''3063190''>each</span> <span m=''3063430''>of</span>
  <span m=''3063500''>these</span> <span m=''3063760''>things,</span> <span m=''3064030''>each</span>
  <span m=''3064170''>of these</span> <span m=''3064330''>selectors,</span> <span
  m=''3064850''>x-coordinate</span> <span m=''3066150''>and</span> <span m=''3066360''>endpoint,</span>
  <span m=''3067260''>stand</span> <span m=''3068030''>for</span> <span m=''3068180''>a</span>
  <span m=''3068320''>decision</span> <span m=''3068750''>choice</span> <span m=''3069190''>whose</span>
  <span m=''3069420''>details</span> <span m=''3070020''>I</span> <span m=''3070240''>don''t</span>
  <span m=''3070450''>have</span> <span m=''3070610''>to</span> <span m=''3070780''>look</span>
  <span m=''3071010''>at.</span> </p><p><span m=''3072260''>So</span> <span m=''3072430''>I</span>
  <span m=''3072500''>could</span> <span m=''3072670''>perfectly</span> <span m=''3073170''>well,</span>
  <span m=''3073980''>again,</span> <span m=''3074310''>just</span> <span m=''3074500''>like</span>
  <span m=''3074670''>rational</span> <span m=''3075070''>numbers</span> <span m=''3075660''>I</span>
  <span m=''3075800''>did</span> <span m=''3075930''>before,</span> <span m=''3076230''>I</span>
  <span m=''3076270''>could</span> <span m=''3076420''>say,</span> <span m=''3076550''>oh</span>
  <span m=''3076730''>well,</span> <span m=''3077160''>gee,</span> <span m=''3077320''>a</span>
  <span m=''3077450''>segment</span> <span m=''3077910''>really</span> <span m=''3078400''>is</span>
  <span m=''3079210''>a</span> <span m=''3079330''>pair</span> <span m=''3079640''>of</span>
  <span m=''3079720''>pairs.</span> <span m=''3081180''>And</span> <span m=''3081530''>the</span>
  <span m=''3082600''>x-coordinate</span> <span m=''3083230''>of the</span> <span
  m=''3083450''>first</span> <span m=''3083660''>endpoint</span> <span m=''3084040''>or</span>
  <span m=''3084090''>the</span> <span m=''3084160''>segment</span> <span m=''3084810''>really</span>
  <span m=''3085330''>is</span> <span m=''3085770''>the--</span> <span m=''3086770''>well,</span>
  <span m=''3086970''>what</span> <span m=''3087090''>is</span> <span m=''3087230''>it?</span>
  <span m=''3087330''>It''s</span> <span m=''3087500''>the</span> <span m=''3087590''>car</span>
  <span m=''3089540''>of</span> <span m=''3090970''>the</span> <span m=''3091140''>car</span>
  <span m=''3092690''>of</span> <span m=''3092810''>the</span> <span m=''3092880''>segment.</span>
  <span m=''3093890''>So</span> <span m=''3094080''>I</span> <span m=''3094140''>could</span>
  <span m=''3094320''>perfectly</span> <span m=''3094850''>well</span> <span m=''3095740''>go
  and</span> <span m=''3096020''>redefine</span> <span m=''3096560''>length.</span>
  <span m=''3097500''>I</span> <span m=''3097620''>could</span> <span m=''3097760''>say,</span>
  <span m=''3098030''>define</span> <span m=''3101730''>the</span> <span m=''3102070''>length</span>
  <span m=''3105660''>of</span> <span m=''3105810''>some</span> <span m=''3106340''>segment</span>
  <span m=''3106480''>s.</span> </p><p><span m=''3108614''>And</span> <span m=''3109050''>I</span>
  <span m=''3109140''>could</span> <span m=''3109290''>start</span> <span m=''3109600''>off</span>
  <span m=''3109780''>writing</span> <span m=''3110050''>something</span> <span m=''3110420''>like,</span>
  <span m=''3110640''>well,</span> <span m=''3110860''>we''ll</span> <span m=''3111050''>let</span>
  <span m=''3112720''>dx</span> <span m=''3115570''>be--</span> <span m=''3115950''>well,
  what''s it have to</span> <span m=''3116130''>be?</span> <span m=''3116260''>It''s</span>
  <span m=''3116400''>got</span> <span m=''3116520''>to</span> <span m=''3116580''>be</span>
  <span m=''3116720''>the</span> <span m=''3117010''>difference</span> <span m=''3117410''>of</span>
  <span m=''3117470''>the</span> <span m=''3117530''>two</span> <span m=''3117700''>coordinates,</span>
  <span m=''3118270''>so</span> <span m=''3118380''>that''s</span> <span m=''3118620''>the</span>
  <span m=''3118700''>difference</span> <span m=''3119690''>of,</span> <span m=''3120150''>the
  first</span> <span m=''3120480''>one</span> <span m=''3120640''>is</span> <span
  m=''3120740''>the</span> <span m=''3120870''>car</span> <span m=''3122560''>of</span>
  <span m=''3123890''>the</span> <span m=''3124310''>car</span> <span m=''3125460''>of</span>
  <span m=''3125900''>s,</span> <span m=''3127890''>subtracted</span> <span m=''3128910''>from</span>
  <span m=''3129715''>the</span> <span m=''3131510''>first</span> <span m=''3131720''>one,</span>
  <span m=''3131850''>the</span> <span m=''3131940''>car</span> <span m=''3132370''>of</span>
  <span m=''3132750''>the</span> <span m=''3133070''>other</span> <span m=''3133320''>half
  of</span> <span m=''3133610''>it,</span> <span m=''3134040''>the cdr</span> <span
  m=''3135160''>of</span> <span m=''3135650''>s.</span> <span m=''3141530''>All right,
  and then</span> <span m=''3141970''>dy</span> <span m=''3142490''>would</span> <span
  m=''3142680''>be--</span> <span m=''3144430''>well,</span> <span m=''3144820''>let''s</span>
  <span m=''3144980''>see,</span> <span m=''3146250''>I''d</span> <span m=''3146370''>get</span>
  <span m=''3146560''>the</span> <span m=''3146640''>y-coordinate,</span> <span m=''3147260''>so</span>
  <span m=''3147410''>it''d</span> <span m=''3147560''>be</span> <span m=''3147700''>the</span>
  <span m=''3147780''>difference</span> <span m=''3148675''>of</span> <span m=''3149100''>the</span>
  <span m=''3149240''>cdr</span> <span m=''3150865''>of</span> <span m=''3151250''>the</span>
  <span m=''3151790''>car</span> <span m=''3152950''>of</span> <span m=''3153110''>s,</span>
  <span m=''3153850''>and</span> <span m=''3154220''>the</span> <span m=''3154590''>cdr</span>
  <span m=''3156610''>of the</span> <span m=''3156890''>cdr</span> <span m=''3157120''>of</span>
  <span m=''3157490''>s,</span> <span m=''3160760''>sort</span> <span m=''3160930''>of</span>
  <span m=''3161100''>go on.</span> </p><p><span m=''3164210''>You</span> <span m=''3164340''>can</span>
  <span m=''3164450''>see</span> <span m=''3164550''>that''s</span> <span m=''3165220''>much</span>
  <span m=''3165380''>harder</span> <span m=''3165660''>to</span> <span m=''3165750''>read</span>
  <span m=''3166800''>than</span> <span m=''3166890''>the</span> <span m=''3166980''>program</span>
  <span m=''3167310''>I</span> <span m=''3167380''>had</span> <span m=''3167590''>before.</span>
  <span m=''3168270''>But</span> <span m=''3170380''>worse</span> <span m=''3170600''>than</span>
  <span m=''3170720''>that,</span> <span m=''3171560''>suppose</span> <span m=''3171940''>you''d</span>
  <span m=''3172020''>gone and</span> <span m=''3172350''>implemented</span> <span
  m=''3172900''>length?</span> <span m=''3176930''>And</span> <span m=''3177070''>then</span>
  <span m=''3177430''>the</span> <span m=''3177610''>next</span> <span m=''3177800''>day,</span>
  <span m=''3177980''>George</span> <span m=''3178330''>comes</span> <span m=''3178580''>to</span>
  <span m=''3178670''>you</span> <span m=''3178780''>and</span> <span m=''3178890''>says,
  I''m</span> <span m=''3179150''>sorry,</span> <span m=''3179610''>I</span> <span
  m=''3179720''>changed</span> <span m=''3180110''>my</span> <span m=''3180230''>mind.</span>
  <span m=''3181030''>I</span> <span m=''3181150''>want</span> <span m=''3181280''>to</span>
  <span m=''3181410''>write</span> <span m=''3181730''>points</span> <span m=''3182080''>with</span>
  <span m=''3182280''>the</span> <span m=''3183290''>x-coordinate</span> <span m=''3183890''>first.</span>
  <span m=''3185130''>So</span> <span m=''3185270''>you</span> <span m=''3185390''>come</span>
  <span m=''3185550''>back</span> <span m=''3185750''>you stare</span> <span m=''3185930''>at</span>
  <span m=''3186210''>this</span> <span m=''3186360''>code</span> <span m=''3186570''>and</span>
  <span m=''3186670''>say,</span> <span m=''3186800''>oh</span> <span m=''3186940''>gee,</span>
  <span m=''3187130''>what</span> <span m=''3187300''>was</span> <span m=''3187480''>that?</span>
  <span m=''3187750''>That</span> <span m=''3187950''>was</span> <span m=''3188140''>the</span>
  <span m=''3190040''>car,</span> <span m=''3190420''>so</span> <span m=''3190670''>I</span>
  <span m=''3190790''>have</span> <span m=''3190930''>to</span> <span m=''3191030''>change</span>
  <span m=''3191370''>this to</span> <span m=''3191640''>cdr,</span> <span m=''3193980''>and</span>
  <span m=''3195340''>this</span> <span m=''3195510''>is</span> <span m=''3195660''>cdr,</span>
  <span m=''3197430''>and</span> <span m=''3197560''>this</span> <span m=''3197630''>now</span>
  <span m=''3197850''>has</span> <span m=''3198070''>to</span> <span m=''3198160''>be</span>
  <span m=''3198310''>car.</span> <span m=''3200770''>And</span> <span m=''3201410''>this
  has</span> <span m=''3201740''>to</span> <span m=''3201780''>be</span> <span m=''3201860''>car.</span>
  </p><p><span m=''3203900''>And you</span> <span m=''3204210''>sort of</span> <span
  m=''3204290''>do</span> <span m=''3204520''>that,</span> <span m=''3204840''>and</span>
  <span m=''3204940''>then</span> <span m=''3205060''>the</span> <span m=''3205220''>next</span>
  <span m=''3205370''>day</span> <span m=''3205550''>George</span> <span m=''3205830''>comes</span>
  <span m=''3206050''>back</span> <span m=''3206310''>and</span> <span m=''3206420''>says,</span>
  <span m=''3206610''>sorry,</span> <span m=''3209290''>the</span> <span m=''3209820''>guys</span>
  <span m=''3210090''>designing</span> <span m=''3210530''>the</span> <span m=''3210620''>display</span>
  <span m=''3211410''>would</span> <span m=''3211600''>like</span> <span m=''3213260''>lines</span>
  <span m=''3213850''>to</span> <span m=''3213930''>be</span> <span m=''3214030''>painted</span>
  <span m=''3214390''>in</span> <span m=''3214490''>the</span> <span m=''3214580''>opposite</span>
  <span m=''3215020''>direction,</span> <span m=''3215490''>so</span> <span m=''3215620''>I</span>
  <span m=''3215740''>have</span> <span m=''3215850''>to</span> <span m=''3215970''>write</span>
  <span m=''3216160''>the</span> <span m=''3216330''>endpoint</span> <span m=''3216850''>first</span>
  <span m=''3217140''>in</span> <span m=''3217220''>the</span> <span m=''3217310''>order.</span>
  <span m=''3217630''>And</span> <span m=''3217720''>then</span> <span m=''3217800''>you</span>
  <span m=''3217910''>come</span> <span m=''3218080''>back</span> <span m=''3218320''>and</span>
  <span m=''3218390''>you stare</span> <span m=''3218720''>at this</span> <span m=''3218920''>code,</span>
  <span m=''3219280''>and say, gee,</span> <span m=''3219440''>what</span> <span m=''3219610''>was</span>
  <span m=''3219750''>it</span> <span m=''3221710''>talking</span> <span m=''3222090''>about?</span>
  <span m=''3222400''>Oh</span> <span m=''3222570''>yeah,</span> <span m=''3222830''>well</span>
  <span m=''3223020''>I''ve</span> <span m=''3223090''>got</span> <span m=''3223180''>to</span>
  <span m=''3223280''>change</span> <span m=''3223540''>this</span> <span m=''3223740''>one</span>
  <span m=''3223870''>to</span> <span m=''3223970''>cdr,</span> <span m=''3224930''>and</span>
  <span m=''3225520''>this</span> <span m=''3225660''>one</span> <span m=''3225800''>becomes</span>
  <span m=''3226200''>car,</span> <span m=''3227410''>this</span> <span m=''3227910''>one</span>
  <span m=''3228140''>comes</span> <span m=''3228420''>car,</span> <span m=''3229830''>and</span>
  <span m=''3230030''>this</span> <span m=''3230150''>becomes</span> <span m=''3230500''>cdr.</span>
  </p><p><span m=''3230620''>And</span> <span m=''3230750''>you</span> <span m=''3230880''>go</span>
  <span m=''3231050''>up</span> <span m=''3231200''>and</span> <span m=''3231320''>do</span>
  <span m=''3231460''>that,</span> <span m=''3232360''>and</span> <span m=''3232530''>then</span>
  <span m=''3232640''>the</span> <span m=''3232780''>next</span> <span m=''3232930''>day,</span>
  <span m=''3233090''>George</span> <span m=''3233340''>comes back and says,</span>
  <span m=''3233790''>I''m</span> <span m=''3233880''>sorry,</span> <span m=''3234140''>what</span>
  <span m=''3234290''>I</span> <span m=''3234340''>really</span> <span m=''3234670''>meant</span>
  <span m=''3235110''>is</span> <span m=''3235270''>that</span> <span m=''3235410''>the</span>
  <span m=''3235480''>segments</span> <span m=''3235880''>always</span> <span m=''3236130''>have</span>
  <span m=''3236310''>to</span> <span m=''3237170''>be</span> <span m=''3237300''>painted</span>
  <span m=''3237710''>from</span> <span m=''3237870''>left</span> <span m=''3238060''>to</span>
  <span m=''3238150''>right</span> <span m=''3238380''>on</span> <span m=''3238520''>the</span>
  <span m=''3238580''>screen.</span> <span m=''3239660''>And</span> <span m=''3239780''>then</span>
  <span m=''3239900''>you</span> <span m=''3239990''>sort</span> <span m=''3240160''>of,</span>
  <span m=''3240590''>it''s</span> <span m=''3240770''>clear,</span> <span m=''3240990''>you</span>
  <span m=''3241120''>just</span> <span m=''3241300''>go</span> <span m=''3241440''>and</span>
  <span m=''3241560''>punch</span> <span m=''3241800''>George</span> <span m=''3242040''>in</span>
  <span m=''3242110''>the</span> <span m=''3242180''>mouth</span> <span m=''3242930''>at</span>
  <span m=''3243040''>that</span> <span m=''3243250''>point.</span> <span m=''3243610''>But</span>
  <span m=''3246710''>you</span> <span m=''3246830''>see,</span> <span m=''3247180''>as</span>
  <span m=''3247300''>soon</span> <span m=''3247460''>as</span> <span m=''3247560''>we</span>
  <span m=''3247660''>have</span> <span m=''3248110''>a</span> <span m=''3248200''>10</span>
  <span m=''3248480''>layer</span> <span m=''3248760''>system,</span> <span m=''3249310''>you</span>
  <span m=''3249410''>see</span> <span m=''3249560''>how</span> <span m=''3249690''>that</span>
  <span m=''3249860''>complexity</span> <span m=''3250390''>immediately</span> <span
  m=''3250920''>builds</span> <span m=''3251240''>up</span> <span m=''3251820''>to</span>
  <span m=''3251950''>the</span> <span m=''3252050''>point</span> <span m=''3252290''>where</span>
  <span m=''3252670''>even</span> <span m=''3253060''>something</span> <span m=''3253350''>like</span>
  <span m=''3253550''>this</span> <span m=''3253750''>gets</span> <span m=''3253960''>out</span>
  <span m=''3254080''>of</span> <span m=''3254200''>control.</span> </p><p><span m=''3256250''>So</span>
  <span m=''3256420''>again,</span> <span m=''3257390''>the</span> <span m=''3257580''>way</span>
  <span m=''3257800''>we''ve</span> <span m=''3257980''>gotten</span> <span m=''3258290''>out</span>
  <span m=''3258420''>of</span> <span m=''3258550''>that</span> <span m=''3259560''>is</span>
  <span m=''3259710''>we''ve</span> <span m=''3259910''>named</span> <span m=''3260470''>that</span>
  <span m=''3260710''>spirit.</span> <span m=''3261150''>We</span> <span m=''3261360''>built</span>
  <span m=''3262940''>a</span> <span m=''3262980''>system</span> <span m=''3263370''>where</span>
  <span m=''3263480''>there</span> <span m=''3263680''>is</span> <span m=''3264080''>a</span>
  <span m=''3264320''>thing,</span> <span m=''3265530''>which</span> <span m=''3265770''>is</span>
  <span m=''3266140''>the</span> <span m=''3266560''>representation</span> <span m=''3267480''>choice</span>
  <span m=''3268980''>for</span> <span m=''3269140''>how</span> <span m=''3269270''>you''re</span>
  <span m=''3269420''>going</span> <span m=''3269510''>to</span> <span m=''3269590''>talk</span>
  <span m=''3269810''>about</span> <span m=''3270060''>vectors.</span> <span m=''3271570''>And</span>
  <span m=''3271720''>choices</span> <span m=''3272200''>about</span> <span m=''3272460''>that</span>
  <span m=''3272620''>representation</span> <span m=''3273450''>are</span> <span m=''3273670''>localized</span>
  <span m=''3274430''>right</span> <span m=''3274710''>there.</span> <span m=''3275670''>They</span>
  <span m=''3275810''>don''t</span> <span m=''3275960''>have</span> <span m=''3276110''>their</span>
  <span m=''3276250''>guts</span> <span m=''3276580''>spilling</span> <span m=''3276930''>over</span>
  <span m=''3277180''>into</span> <span m=''3277330''>things</span> <span m=''3277620''>like</span>
  <span m=''3277840''>how</span> <span m=''3277940''>you</span> <span m=''3278110''>compute</span>
  <span m=''3278430''>the</span> <span m=''3278510''>length</span> <span m=''3278870''>and
  how</span> <span m=''3278990''>you</span> <span m=''3279130''>compute</span> <span
  m=''3279270''>the</span> <span m=''3279470''>midpoint.</span> <span m=''3280926''>And</span>
  <span m=''3281390''>that''s</span> <span m=''3281820''>the</span> <span m=''3281930''>real</span>
  <span m=''3283190''>power</span> <span m=''3283445''>of</span> <span m=''3283700''>this</span>
  <span m=''3283810''>system.</span> <span m=''3285660''>OK,</span> <span m=''3285870''>we''re</span>
  <span m=''3286040''>explicit</span> <span m=''3286640''>about</span> <span m=''3286970''>them,</span>
  <span m=''3288330''>so</span> <span m=''3288500''>that</span> <span m=''3288640''>we</span>
  <span m=''3288740''>have</span> <span m=''3288890''>control</span> <span m=''3289300''>over</span>
  <span m=''3289490''>them.</span> <span m=''3290916''>All right,</span> <span m=''3291400''>questions?</span>
  </p><p><span m=''3292190''>AUDIENCE: What</span> <span m=''3292520''>happens</span>
  <span m=''3292850''>in the case</span> <span m=''3293140''>where</span> <span m=''3293550''>you</span>
  <span m=''3293900''>don''t</span> <span m=''3294210''>want</span> <span m=''3294520''>to
  be</span> <span m=''3294850''>treating</span> <span m=''3295223''>objects in terms</span>
  <span m=''3295596''>of</span> <span m=''3295970''>pairs?</span> <span m=''3296660''>For
  instance,</span> <span m=''3298280''>in</span> <span m=''3298470''>three-dimensional</span>
  <span m=''3299270''>space,</span> <span m=''3300420''>you''d have</span> <span m=''3300760''>three</span>
  <span m=''3301000''>coordinates.</span> <span m=''3301680''>Or even</span> <span
  m=''3302030''>in the</span> <span m=''3302120''>case</span> <span m=''3302400''>where
  you</span> <span m=''3302570''>have</span> <span m=''3302740''>n-dimensional</span>
  <span m=''3303280''>space,</span> <span m=''3303520''>what happens?</span> </p><p><span
  m=''3304180''>PROFESSOR: Right,</span> <span m=''3304790''>OK.</span> <span m=''3305140''>Well,</span>
  <span m=''3305610''>this</span> <span m=''3305960''>is</span> <span m=''3306020''>a</span>
  <span m=''3306100''>preview</span> <span m=''3306490''>of</span> <span m=''3306570''>what</span>
  <span m=''3306690''>I''ll</span> <span m=''3306760''>say</span> <span m=''3306990''>tomorrow.</span>
  <span m=''3308374''>But</span> <span m=''3311580''>the</span> <span m=''3311720''>point</span>
  <span m=''3311940''>is,</span> <span m=''3312070''>once</span> <span m=''3312330''>you</span>
  <span m=''3312530''>have</span> <span m=''3314120''>two</span> <span m=''3314320''>things,</span>
  <span m=''3314640''>you</span> <span m=''3314730''>have</span> <span m=''3314920''>as</span>
  <span m=''3315020''>many</span> <span m=''3315270''>things</span> <span m=''3315520''>as</span>
  <span m=''3315620''>you</span> <span m=''3315770''>want.</span> <span m=''3316972''>All
  right?</span> <span m=''3317370''>Because</span> <span m=''3317770''>if</span> <span
  m=''3317920''>I</span> <span m=''3317960''>want</span> <span m=''3318060''>to</span>
  <span m=''3318160''>make</span> <span m=''3318370''>three</span> <span m=''3318590''>things,</span>
  <span m=''3319310''>I</span> <span m=''3319540''>could</span> <span m=''3319680''>start</span>
  <span m=''3319970''>making</span> <span m=''3320310''>things</span> <span m=''3320560''>like</span>
  <span m=''3320790''>a pair</span> <span m=''3325050''>whose</span> <span m=''3325280''>first</span>
  <span m=''3325580''>thing</span> <span m=''3325750''>is</span> <span m=''3325880''>1,</span>
  <span m=''3326750''>and</span> <span m=''3326970''>whose</span> <span m=''3327190''>second</span>
  <span m=''3327620''>thing</span> <span m=''3327820''>is</span> <span m=''3327910''>another</span>
  <span m=''3328230''>pair</span> <span m=''3331120''>that, say,</span> <span m=''3331780''>has</span>
  <span m=''3331940''>2</span> <span m=''3332140''>and</span> <span m=''3332330''>3</span>
  <span m=''3332520''>in</span> <span m=''3332640''>it.</span> <span m=''3334582''>And
  so on,</span> <span m=''3335140''>a</span> <span m=''3335280''>hundred</span> <span
  m=''3335600''>things.</span> <span m=''3335760''>I</span> <span m=''3335890''>can</span>
  <span m=''3336160''>nest</span> <span m=''3336250''>them out</span> <span m=''3336430''>of
  pairs.</span> </p><p><span m=''3337550''>I</span> <span m=''3337740''>made</span>
  <span m=''3337890''>a</span> <span m=''3337940''>pretty</span> <span m=''3338190''>arbitrary</span>
  <span m=''3339180''>decision</span> <span m=''3339620''>about</span> <span m=''3339830''>how</span>
  <span m=''3339930''>to</span> <span m=''3340040''>do</span> <span m=''3340250''>it,</span>
  <span m=''3340370''>and</span> <span m=''3340450''>you</span> <span m=''3340540''>can</span>
  <span m=''3340770''>immediately</span> <span m=''3341220''>see</span> <span m=''3341360''>there</span>
  <span m=''3341450''>are</span> <span m=''3341480''>lots</span> <span m=''3341770''>of</span>
  <span m=''3341860''>ways</span> <span m=''3342080''>to</span> <span m=''3342170''>do</span>
  <span m=''3342330''>that.</span> <span m=''3342730''>What</span> <span m=''3343050''>we''ll</span>
  <span m=''3343260''>start</span> <span m=''3343530''>talking</span> <span m=''3343860''>about</span>
  <span m=''3344070''>next</span> <span m=''3344250''>time are</span> <span m=''3344530''>conventions</span>
  <span m=''3345120''>for</span> <span m=''3345210''>how</span> <span m=''3345320''>to</span>
  <span m=''3345420''>do</span> <span m=''3345550''>things</span> <span m=''3345790''>like</span>
  <span m=''3345980''>that.</span> <span m=''3347660''>But</span> <span m=''3347820''>notice</span>
  <span m=''3348220''>that</span> <span m=''3348360''>what</span> <span m=''3348500''>this</span>
  <span m=''3348650''>really</span> <span m=''3348890''>depends</span> <span m=''3349270''>on</span>
  <span m=''3349430''>is</span> <span m=''3349530''>I</span> <span m=''3349600''>can</span>
  <span m=''3349730''>make</span> <span m=''3349910''>pairs of</span> <span m=''3350200''>pairs.</span>
  <span m=''3351950''>If</span> <span m=''3352060''>all</span> <span m=''3352300''>I</span>
  <span m=''3352380''>could</span> <span m=''3352540''>do</span> <span m=''3352650''>was</span>
  <span m=''3352780''>make</span> <span m=''3353040''>pairs</span> <span m=''3353290''>of</span>
  <span m=''3353380''>numbers,</span> <span m=''3353740''>I''d</span> <span m=''3353860''>be</span>
  <span m=''3353950''>stuck.</span> </p><p><span m=''3367140''>OK.</span> <span m=''3369236''>Let''s</span>
  <span m=''3369610''>break.</span> </p><p><span m=''3371960''>[MUSIC PLAYING]</span>
  </p><p><span m=''3415580''>All right,</span> <span m=''3415740''>well,</span> <span
  m=''3415860''>we''ve</span> <span m=''3416000''>just</span> <span m=''3416650''>gone</span>
  <span m=''3416900''>off</span> <span m=''3417080''>and</span> <span m=''3417260''>done</span>
  <span m=''3419530''>a</span> <span m=''3419650''>couple</span> <span m=''3419960''>of</span>
  <span m=''3420210''>simple</span> <span m=''3420710''>examples</span> <span m=''3421230''>of</span>
  <span m=''3421320''>data</span> <span m=''3421600''>abstraction.</span> <span m=''3423575''>Now</span>
  <span m=''3424020''>I</span> <span m=''3424130''>want to do</span> <span m=''3424340''>something</span>
  <span m=''3424590''>more</span> <span m=''3424710''>complicated.</span> <span m=''3425695''>We''re</span>
  <span m=''3426010''>going</span> <span m=''3426130''>to</span> <span m=''3426190''>talk</span>
  <span m=''3426410''>about</span> <span m=''3426630''>what</span> <span m=''3426770''>it</span>
  <span m=''3426900''>means.</span> <span m=''3428310''>And</span> <span m=''3428440''>this</span>
  <span m=''3428550''>will</span> <span m=''3428620''>be</span> <span m=''3428730''>harder,</span>
  <span m=''3429180''>because it''s</span> <span m=''3429590''>always</span> <span
  m=''3431390''>much</span> <span m=''3431590''>harder</span> <span m=''3432240''>in</span>
  <span m=''3432370''>computer</span> <span m=''3432790''>programming</span> <span
  m=''3433340''>to</span> <span m=''3433460''>talk</span> <span m=''3433700''>about</span>
  <span m=''3433940''>what</span> <span m=''3434110''>something</span> <span m=''3434450''>means</span>
  <span m=''3434790''>than</span> <span m=''3434920''>to</span> <span m=''3435010''>go</span>
  <span m=''3435170''>off</span> <span m=''3435370''>and</span> <span m=''3435530''>do</span>
  <span m=''3435690''>it.</span> </p><p><span m=''3436450''>But</span> <span m=''3438450''>let''s</span>
  <span m=''3438700''>go</span> <span m=''3438800''>back</span> <span m=''3440600''>to</span>
  <span m=''3440740''>almost</span> <span m=''3441100''>the</span> <span m=''3441190''>very</span>
  <span m=''3441460''>beginning.</span> <span m=''3442070''>Let''s</span> <span m=''3442230''>go</span>
  <span m=''3442300''>back</span> <span m=''3442480''>to</span> <span m=''3442580''>the</span>
  <span m=''3442680''>point</span> <span m=''3443800''>where</span> <span m=''3444380''>I</span>
  <span m=''3444460''>said,</span> <span m=''3445800''>we</span> <span m=''3445940''>just</span>
  <span m=''3446200''>assumed</span> <span m=''3447050''>that</span> <span m=''3447260''>there</span>
  <span m=''3447410''>were</span> <span m=''3447480''>procedures,</span> <span m=''3450210''>make-RAT,</span>
  <span m=''3452370''>and</span> <span m=''3452600''>numer,</span> <span m=''3455900''>and</span>
  <span m=''3456420''>denom.</span> <span m=''3458480''>Let''s go</span> <span m=''3458590''>back</span>
  <span m=''3458960''>to</span> <span m=''3459180''>where</span> <span m=''3459340''>we</span>
  <span m=''3459460''>had</span> <span m=''3459800''>this,</span> <span m=''3460110''>at</span>
  <span m=''3460170''>the</span> <span m=''3460240''>very</span> <span m=''3460480''>beginning,</span>
  <span m=''3461570''>constructors</span> <span m=''3462570''>and</span> <span m=''3462670''>selectors,</span>
  <span m=''3463860''>and</span> <span m=''3464660''>went off</span> <span m=''3464920''>and</span>
  <span m=''3465240''>defined</span> <span m=''3466080''>the</span> <span m=''3466210''>rational</span>
  <span m=''3466590''>number</span> <span m=''3466940''>arithmetic.</span> <span m=''3467210''>And</span>
  <span m=''3468110''>remember,</span> <span m=''3468440''>I said at</span> <span
  m=''3468580''>that</span> <span m=''3468780''>point</span> <span m=''3468940''>we</span>
  <span m=''3469030''>were</span> <span m=''3469150''>sort</span> <span m=''3469310''>of</span>
  <span m=''3469470''>done,</span> <span m=''3469700''>except</span> <span m=''3469980''>for</span>
  <span m=''3470120''>George.</span> <span m=''3471990''>Well,</span> <span m=''3472210''>what</span>
  <span m=''3472400''>is</span> <span m=''3472600''>it</span> <span m=''3472910''>that</span>
  <span m=''3473150''>we''d</span> <span m=''3473290''>actually</span> <span m=''3473670''>done</span>
  <span m=''3474080''>at</span> <span m=''3474230''>that</span> <span m=''3474430''>point?</span>
  <span m=''3475920''>What</span> <span m=''3476120''>was</span> <span m=''3476330''>it</span>
  <span m=''3476450''>that</span> <span m=''3476610''>was</span> <span m=''3476790''>done?</span>
  </p><p><span m=''3479420''>Well, what</span> <span m=''3479640''>I</span> <span
  m=''3479680''>want</span> <span m=''3479770''>to</span> <span m=''3479860''>say</span>
  <span m=''3480150''>is,</span> <span m=''3481310''>what</span> <span m=''3481470''>was</span>
  <span m=''3481680''>done</span> <span m=''3483190''>after</span> <span m=''3483430''>we''d</span>
  <span m=''3483540''>implemented</span> <span m=''3483990''>the</span> <span m=''3484090''>operations</span>
  <span m=''3484680''>and</span> <span m=''3484790''>terms</span> <span m=''3485120''>of</span>
  <span m=''3485350''>these,</span> <span m=''3486060''>was</span> <span m=''3486290''>that</span>
  <span m=''3486440''>we</span> <span m=''3486540''>had</span> <span m=''3486730''>defined</span>
  <span m=''3487970''>a</span> <span m=''3488110''>rational</span> <span m=''3488540''>number</span>
  <span m=''3488780''>representation</span> <span m=''3490290''>in</span> <span m=''3490500''>terms</span>
  <span m=''3490910''>of</span> <span m=''3491100''>abstract</span> <span m=''3492030''>data.</span>
  </p><p><span m=''3497946''>What</span> <span m=''3498410''>do I</span> <span m=''3498690''>mean
  by</span> <span m=''3498870''>abstract</span> <span m=''3499560''>data?</span> <span
  m=''3501090''>Well,</span> <span m=''3501280''>the</span> <span m=''3501400''>idea</span>
  <span m=''3501790''>is</span> <span m=''3502060''>that</span> <span m=''3504830''>at</span>
  <span m=''3505000''>that</span> <span m=''3505240''>point,</span> <span m=''3505610''>when</span>
  <span m=''3505720''>we</span> <span m=''3505820''>had</span> <span m=''3505970''>our</span>
  <span m=''3506080''>+RAT</span> <span m=''3506630''>and</span> <span m=''3506720''>our</span>
  <span m=''3506850''>*RAT,</span> <span m=''3508870''>that</span> <span m=''3509180''>any</span>
  <span m=''3510000''>implementation</span> <span m=''3511330''>of</span> <span m=''3511550''>make-RAT,</span>
  <span m=''3512115''>and</span> <span m=''3512400''>numerator,</span> <span m=''3513060''>and</span>
  <span m=''3513230''>denominator</span> <span m=''3515210''>that</span> <span m=''3515480''>George</span>
  <span m=''3515760''>supplied</span> <span m=''3516210''>us</span> <span m=''3516370''>with,</span>
  <span m=''3518000''>could</span> <span m=''3518140''>be</span> <span m=''3518280''>the</span>
  <span m=''3518360''>basis</span> <span m=''3518770''>for a</span> <span m=''3518920''>rational</span>
  <span m=''3519280''>number</span> <span m=''3519520''>representation.</span> <span
  m=''3520990''>Like,</span> <span m=''3521190''>it</span> <span m=''3521260''>wasn''t</span>
  <span m=''3521490''>our</span> <span m=''3521610''>concern</span> <span m=''3522090''>where</span>
  <span m=''3522290''>you</span> <span m=''3523850''>divided</span> <span m=''3524320''>through</span>
  <span m=''3524500''>to</span> <span m=''3524550''>get</span> <span m=''3524740''>the</span>
  <span m=''3524820''>greatest</span> <span m=''3525160''>common</span> <span m=''3525430''>denominator,</span>
  <span m=''3526150''>or</span> <span m=''3526310''>any</span> <span m=''3526500''>of</span>
  <span m=''3526680''>that.</span> </p><p><span m=''3528980''>So</span> <span m=''3529190''>the</span>
  <span m=''3529340''>idea</span> <span m=''3529650''>is</span> <span m=''3529770''>that</span>
  <span m=''3531200''>what</span> <span m=''3531330''>we</span> <span m=''3531460''>built</span>
  <span m=''3532260''>is</span> <span m=''3532420''>a</span> <span m=''3532480''>rational</span>
  <span m=''3533320''>arithmetic</span> <span m=''3533830''>system</span> <span m=''3534130''>that</span>
  <span m=''3534250''>would</span> <span m=''3534370''>sit</span> <span m=''3534560''>on</span>
  <span m=''3534700''>top</span> <span m=''3534930''>of</span> <span m=''3535050''>any</span>
  <span m=''3535600''>representation.</span> <span m=''3537140''>What do I mean</span>
  <span m=''3537530''>by</span> <span m=''3537660''>any</span> <span m=''3537940''>representation?</span>
  <span m=''3539930''>I</span> <span m=''3540040''>mean,</span> <span m=''3540170''>certainly</span>
  <span m=''3540560''>it can''t</span> <span m=''3540900''>be</span> <span m=''3541020''>the</span>
  <span m=''3541120''>case</span> <span m=''3542160''>that</span> <span m=''3542300''>all</span>
  <span m=''3542510''>I</span> <span m=''3542590''>mean</span> <span m=''3542850''>is</span>
  <span m=''3542950''>George</span> <span m=''3543260''>can</span> <span m=''3543380''>reach</span>
  <span m=''3543600''>in</span> <span m=''3543690''>a</span> <span m=''3543740''>bag</span>
  <span m=''3544030''>and</span> <span m=''3544140''>pull</span> <span m=''3544330''>out</span>
  <span m=''3544440''>three</span> <span m=''3544630''>arbitrary</span> <span m=''3545130''>procedures</span>
  <span m=''3547450''>and</span> <span m=''3547640''>say,</span> <span m=''3548830''>well,</span>
  <span m=''3549230''>fine,</span> <span m=''3549830''>now</span> <span m=''3550030''>that''s</span>
  <span m=''3550280''>the</span> <span m=''3550380''>implementation.</span> <span
  m=''3551960''>That</span> <span m=''3552160''>can''t</span> <span m=''3552400''>be</span>
  <span m=''3552520''>what</span> <span m=''3552660''>I mean.</span> </p><p><span
  m=''3554080''>What</span> <span m=''3554310''>I''ve</span> <span m=''3554420''>got</span>
  <span m=''3554600''>to</span> <span m=''3554650''>mean</span> <span m=''3556210''>is</span>
  <span m=''3556380''>that</span> <span m=''3556570''>there''s</span> <span m=''3558070''>some</span>
  <span m=''3558350''>way</span> <span m=''3558560''>of</span> <span m=''3558650''>saying</span>
  <span m=''3558990''>whether</span> <span m=''3561060''>three</span> <span m=''3561330''>procedures</span>
  <span m=''3561870''>are</span> <span m=''3561940''>going</span> <span m=''3562040''>to</span>
  <span m=''3562150''>be</span> <span m=''3562250''>suitable</span> <span m=''3563690''>as</span>
  <span m=''3563900''>a</span> <span m=''3563950''>basis</span> <span m=''3564590''>for</span>
  <span m=''3564880''>rational</span> <span m=''3565270''>number</span> <span m=''3565510''>representation.</span>
  <span m=''3566690''>If</span> <span m=''3566840''>we</span> <span m=''3566950''>think</span>
  <span m=''3567210''>about</span> <span m=''3567540''>it,</span> <span m=''3568610''>what</span>
  <span m=''3568890''>suitable</span> <span m=''3569250''>might</span> <span m=''3569590''>mean</span>
  <span m=''3569920''>is</span> <span m=''3570410''>if</span> <span m=''3570620''>I</span>
  <span m=''3570750''>have</span> <span m=''3570880''>to</span> <span m=''3571000''>assume</span>
  <span m=''3571300''>something</span> <span m=''3571650''>like</span> <span m=''3571930''>this,</span>
  <span m=''3572210''>I</span> <span m=''3572270''>have</span> <span m=''3572390''>to</span>
  <span m=''3572510''>say</span> <span m=''3572680''>that</span> <span m=''3572900''>if</span>
  <span m=''3575210''>x</span> <span m=''3576220''>is</span> <span m=''3576790''>the</span>
  <span m=''3577090''>result</span> <span m=''3577680''>of</span> <span m=''3579030''>say,
  doing</span> <span m=''3579830''>make-RAT</span> <span m=''3584630''>of</span> <span
  m=''3584930''>n</span> <span m=''3585160''>and</span> <span m=''3585320''>d,</span>
  <span m=''3588640''>then</span> <span m=''3593970''>the</span> <span m=''3594130''>numerator</span>
  <span m=''3596920''>of</span> <span m=''3597030''>x</span> <span m=''3599210''>divided</span>
  <span m=''3599730''>by</span> <span m=''3600700''>the</span> <span m=''3600900''>denominator</span>
  <span m=''3601590''>of x</span> <span m=''3606210''>is</span> <span m=''3606400''>equal</span>
  <span m=''3606720''>to n</span> <span m=''3606920''>over d.</span> </p><p><span
  m=''3609680''>See,</span> <span m=''3609840''>what</span> <span m=''3610010''>that</span>
  <span m=''3610250''>is</span> <span m=''3610450''>is</span> <span m=''3610740''>that''s</span>
  <span m=''3611210''>George''s</span> <span m=''3611710''>contract.</span> <span
  m=''3613770''>What</span> <span m=''3613940''>we</span> <span m=''3614090''>mean</span>
  <span m=''3614710''>by</span> <span m=''3614830''>writing</span> <span m=''3615190''>a</span>
  <span m=''3615250''>contract</span> <span m=''3615555''>for</span> <span m=''3615860''>rational</span>
  <span m=''3616230''>numbers,</span> <span m=''3616520''>if</span> <span m=''3616590''>you</span>
  <span m=''3616650''>think</span> <span m=''3616830''>about</span> <span m=''3616990''>it,</span>
  <span m=''3617140''>this</span> <span m=''3617300''>is</span> <span m=''3617390''>the</span>
  <span m=''3617480''>right</span> <span m=''3617770''>thing.</span> <span m=''3618790''>And</span>
  <span m=''3618920''>the</span> <span m=''3619020''>two</span> <span m=''3619850''>ones</span>
  <span m=''3620050''>we</span> <span m=''3620140''>showed</span> <span m=''3620770''>do</span>
  <span m=''3620920''>the</span> <span m=''3621020''>right</span> <span m=''3621280''>thing.</span>
  <span m=''3621510''>See,</span> <span m=''3621670''>if</span> <span m=''3621750''>I''m</span>
  <span m=''3621860''>taking</span> <span m=''3622170''>out</span> <span m=''3622260''>greatest</span>
  <span m=''3622620''>common</span> <span m=''3622930''>divisors,</span> <span m=''3625550''>it</span>
  <span m=''3625720''>doesn''t</span> <span m=''3625960''>matter</span> <span m=''3626220''>whether</span>
  <span m=''3626440''>I</span> <span m=''3626500''>take</span> <span m=''3626760''>them</span>
  <span m=''3626900''>out</span> <span m=''3627040''>or</span> <span m=''3627130''>not,</span>
  <span m=''3627410''>or</span> <span m=''3627610''>the</span> <span m=''3628060''>place</span>
  <span m=''3628350''>where</span> <span m=''3628510''>I</span> <span m=''3628570''>take</span>
  <span m=''3628800''>them,</span> <span m=''3629110''>because</span> <span m=''3629350''>the</span>
  <span m=''3629450''>idea is</span> <span m=''3629740''>I''m</span> <span m=''3629830''>going</span>
  <span m=''3629910''>to</span> <span m=''3629980''>divide</span> <span m=''3630380''>through.</span>
  </p><p><span m=''3632380''>But</span> <span m=''3632550''>see,</span> <span m=''3632670''>this</span>
  <span m=''3632900''>is</span> <span m=''3633060''>George''s</span> <span m=''3633410''>contract.</span>
  <span m=''3633930''>So what we</span> <span m=''3634150''>really</span> <span m=''3634390''>say</span>
  <span m=''3634560''>to</span> <span m=''3634660''>George</span> <span m=''3634950''>is</span>
  <span m=''3635720''>your</span> <span m=''3635890''>business</span> <span m=''3636900''>is</span>
  <span m=''3637060''>to</span> <span m=''3637160''>go</span> <span m=''3637410''>off</span>
  <span m=''3638440''>and</span> <span m=''3638660''>find</span> <span m=''3639030''>us</span>
  <span m=''3639410''>three</span> <span m=''3639670''>procedures,</span> <span m=''3640970''>make-RAT,</span>
  <span m=''3641600''>and numerator, and</span> <span m=''3641910''>denominator,</span>
  <span m=''3642820''>that</span> <span m=''3643070''>fulfill</span> <span m=''3643590''>this</span>
  <span m=''3643800''>contract</span> <span m=''3645660''>for</span> <span m=''3645810''>any</span>
  <span m=''3645960''>choice</span> <span m=''3646280''>of</span> <span m=''3646500''>n
  and d.</span> <span m=''3646870''>And</span> <span m=''3647200''>that''s</span>
  <span m=''3647960''>what</span> <span m=''3648100''>we</span> <span m=''3648240''>mean</span>
  <span m=''3648640''>by</span> <span m=''3649770''>we</span> <span m=''3649930''>can</span>
  <span m=''3650050''>use</span> <span m=''3650240''>that</span> <span m=''3650390''>as</span>
  <span m=''3650500''>the</span> <span m=''3650570''>basis</span> <span m=''3651000''>for
  a</span> <span m=''3651160''>rational</span> <span m=''3651550''>number</span> <span
  m=''3651790''>representation.</span> <span m=''3654540''>And</span> <span m=''3655240''>other</span>
  <span m=''3655530''>than</span> <span m=''3655680''>that,</span> <span m=''3655830''>it</span>
  <span m=''3655940''>fulfills</span> <span m=''3656330''>this</span> <span m=''3656470''>contract.</span>
  <span m=''3657130''>We</span> <span m=''3657310''>don''t</span> <span m=''3657550''>care</span>
  <span m=''3657850''>how</span> <span m=''3658000''>he</span> <span m=''3658110''>does</span>
  <span m=''3658360''>it.</span> <span m=''3659292''>It''s</span> <span m=''3659760''>not</span>
  <span m=''3659910''>our</span> <span m=''3660030''>business.</span> <span m=''3660410''>It''s</span>
  <span m=''3660570''>below</span> <span m=''3661400''>the</span> <span m=''3661590''>layer</span>
  <span m=''3661910''>of</span> <span m=''3662010''>abstraction.</span> </p><p><span
  m=''3667010''>In</span> <span m=''3667160''>fact,</span> <span m=''3668320''>if</span>
  <span m=''3668500''>we</span> <span m=''3668590''>want</span> <span m=''3668780''>to</span>
  <span m=''3668820''>say,</span> <span m=''3669340''>what</span> <span m=''3669700''>is</span>
  <span m=''3669920''>a</span> <span m=''3669980''>rational</span> <span m=''3670500''>number</span>
  <span m=''3671950''>really?</span> <span m=''3673860''>See,</span> <span m=''3674010''>what''s</span>
  <span m=''3674170''>it</span> <span m=''3674320''>really,</span> <span m=''3674600''>without</span>
  <span m=''3674860''>having</span> <span m=''3675080''>to</span> <span m=''3675160''>talk</span>
  <span m=''3675430''>about</span> <span m=''3676020''>going</span> <span m=''3676240''>below</span>
  <span m=''3676490''>the</span> <span m=''3676580''>layer</span> <span m=''3676810''>of</span>
  <span m=''3676890''>abstraction,</span> <span m=''3677370''>what</span> <span m=''3677480''>we''re</span>
  <span m=''3677580''>forced</span> <span m=''3678240''>into</span> <span m=''3678470''>saying</span>
  <span m=''3679160''>is</span> <span m=''3680100''>a</span> <span m=''3680200''>rational</span>
  <span m=''3680620''>number</span> <span m=''3681150''>really</span> <span m=''3684130''>is</span>
  <span m=''3684350''>sort</span> <span m=''3684500''>of</span> <span m=''3684650''>this</span>
  <span m=''3684820''>axiom,</span> <span m=''3686150''>is</span> <span m=''3686970''>three</span>
  <span m=''3687260''>procedures,</span> <span m=''3687870''>make-RAT,</span> <span
  m=''3688480''>numerator, and</span> <span m=''3688830''>denominator,</span> <span
  m=''3689630''>that</span> <span m=''3689870''>satisfy</span> <span m=''3690420''>this</span>
  <span m=''3690640''>axiom.</span> <span m=''3692370''>In</span> <span m=''3692620''>some</span>
  <span m=''3693250''>sense,</span> <span m=''3693780''>abstractly,</span> <span m=''3694420''>that''s</span>
  <span m=''3694640''>what</span> <span m=''3694740''>a</span> <span m=''3694790''>rational</span>
  <span m=''3695180''>number</span> <span m=''3695770''>is</span> <span m=''3696670''>really.</span>
  </p><p><span m=''3701490''>That''s</span> <span m=''3701780''>sort of</span> <span
  m=''3701920''>easy</span> <span m=''3703010''>words</span> <span m=''3703170''>to</span>
  <span m=''3703320''>listen</span> <span m=''3703650''>to,</span> <span m=''3703880''>because</span>
  <span m=''3704530''>what</span> <span m=''3704680''>you</span> <span m=''3704860''>have</span>
  <span m=''3705040''>in</span> <span m=''3705110''>your</span> <span m=''3705200''>head,</span>
  <span m=''3705400''>of</span> <span m=''3705520''>course,</span> <span m=''3705780''>is</span>
  <span m=''3705900''>well,</span> <span m=''3706330''>for</span> <span m=''3706670''>all</span>
  <span m=''3706770''>this</span> <span m=''3706980''>thing</span> <span m=''3707190''>about</span>
  <span m=''3707460''>saying</span> <span m=''3707880''>that''s</span> <span m=''3708290''>what</span>
  <span m=''3708390''>a</span> <span m=''3708450''>rational</span> <span m=''3708850''>number</span>
  <span m=''3709090''>is</span> <span m=''3709270''>really,</span> <span m=''3710750''>you</span>
  <span m=''3710850''>actually</span> <span m=''3711160''>just</span> <span m=''3711430''>saw</span>
  <span m=''3711700''>that</span> <span m=''3711840''>we</span> <span m=''3711960''>built</span>
  <span m=''3712190''>rational</span> <span m=''3712670''>numbers.</span> <span m=''3718830''>See,
  what we</span> <span m=''3718990''>really</span> <span m=''3719340''>did</span>
  <span m=''3719420''>is</span> <span m=''3719510''>we</span> <span m=''3719620''>built</span>
  <span m=''3719800''>rational</span> <span m=''3720230''>numbers</span> <span m=''3723350''>on</span>
  <span m=''3723540''>top</span> <span m=''3723790''>of</span> <span m=''3723910''>pairs.</span>
  <span m=''3728680''>So</span> <span m=''3728970''>for</span> <span m=''3729160''>all
  I''m</span> <span m=''3729360''>saying</span> <span m=''3730000''>abstractly,</span>
  <span m=''3730680''>we</span> <span m=''3730790''>can</span> <span m=''3730900''>say</span>
  <span m=''3731090''>a</span> <span m=''3731170''>rational</span> <span m=''3731560''>number</span>
  <span m=''3731830''>really</span> <span m=''3732750''>is</span> <span m=''3732950''>just</span>
  <span m=''3733160''>this</span> <span m=''3733330''>axiom.</span> <span m=''3735450''>You</span>
  <span m=''3735490''>can</span> <span m=''3735980''>listen</span> <span m=''3736300''>to</span>
  <span m=''3736390''>that</span> <span m=''3736580''>comfortably,</span> <span m=''3737030''>because</span>
  <span m=''3737300''>you''re</span> <span m=''3737370''>saying,</span> <span m=''3737580''>well,</span>
  <span m=''3737960''>yeah,</span> <span m=''3738110''>but</span> <span m=''3738270''>really</span>
  <span m=''3738640''>it''s</span> <span m=''3738810''>actually</span> <span m=''3739200''>pairs,</span>
  <span m=''3740300''>and</span> <span m=''3740410''>I''m</span> <span m=''3740510''>just</span>
  <span m=''3741350''>annoying</span> <span m=''3741810''>you</span> <span m=''3741950''>by</span>
  <span m=''3742090''>trying</span> <span m=''3742260''>to</span> <span m=''3742440''>be</span>
  <span m=''3742570''>abstract.</span> </p><p><span m=''3744820''>Well,</span> <span
  m=''3745400''>let</span> <span m=''3745510''>me,</span> <span m=''3746840''>as</span>
  <span m=''3747010''>an</span> <span m=''3747110''>antidote</span> <span m=''3747670''>for</span>
  <span m=''3747770''>that,</span> <span m=''3748970''>let</span> <span m=''3749100''>me</span>
  <span m=''3749200''>do</span> <span m=''3749330''>something</span> <span m=''3749960''>that</span>
  <span m=''3750140''>I</span> <span m=''3750320''>think</span> <span m=''3750520''>is</span>
  <span m=''3750630''>really</span> <span m=''3750900''>going</span> <span m=''3751010''>to</span>
  <span m=''3751130''>terrify</span> <span m=''3751660''>you.</span> <span m=''3752636''>I
  mean,</span> <span m=''3753040''>it''s</span> <span m=''3753240''>really</span>
  <span m=''3753480''>going</span> <span m=''3753570''>to</span> <span m=''3753670''>bring</span>
  <span m=''3753890''>you</span> <span m=''3754980''>face</span> <span m=''3755430''>to</span>
  <span m=''3755540''>face</span> <span m=''3756660''>with</span> <span m=''3756920''>the</span>
  <span m=''3757150''>sort</span> <span m=''3757460''>of</span> <span m=''3758090''>existential</span>
  <span m=''3758790''>reality</span> <span m=''3759320''>of</span> <span m=''3759390''>this</span>
  <span m=''3759550''>abstraction</span> <span m=''3760090''>that</span> <span m=''3760210''>we''re</span>
  <span m=''3760310''>talking</span> <span m=''3760630''>about.</span> <span m=''3761490''>And</span>
  <span m=''3761820''>what</span> <span m=''3761960''>I''m</span> <span m=''3762090''>going</span>
  <span m=''3762180''>to</span> <span m=''3762270''>talk</span> <span m=''3762520''>about</span>
  <span m=''3763070''>is,</span> <span m=''3763250''>what</span> <span m=''3763420''>are</span>
  <span m=''3763510''>pairs</span> <span m=''3763920''>really?</span> <span m=''3765960''>See,</span>
  <span m=''3766110''>what</span> <span m=''3766270''>did I</span> <span m=''3766350''>tell</span>
  <span m=''3766540''>you</span> <span m=''3766720''>about</span> <span m=''3766980''>pairs?</span>
  <span m=''3768710''>I</span> <span m=''3768830''>tricked you,</span> <span m=''3769230''>right?</span>
  </p><p><span m=''3769420''>I</span> <span m=''3769490''>said</span> <span m=''3769710''>that</span>
  <span m=''3769870''>Lisp</span> <span m=''3770570''>has</span> <span m=''3770820''>this</span>
  <span m=''3770940''>primitive</span> <span m=''3771290''>called</span> <span m=''3771520''>cons</span>
  <span m=''3771980''>that builds</span> <span m=''3772250''>pairs.</span> <span m=''3773520''>But</span>
  <span m=''3773790''>what</span> <span m=''3773980''>did I</span> <span m=''3774060''>really</span>
  <span m=''3774510''>tell you</span> <span m=''3774670''>about?</span> <span m=''3776470''>If</span>
  <span m=''3776550''>you</span> <span m=''3776640''>go</span> <span m=''3776760''>back</span>
  <span m=''3777110''>and</span> <span m=''3777220''>said,</span> <span m=''3778080''>let''s</span>
  <span m=''3778130''>look</span> <span m=''3778320''>on</span> <span m=''3778430''>this</span>
  <span m=''3778510''>slide,</span> <span m=''3779510''>all</span> <span m=''3779860''>I</span>
  <span m=''3780060''>really</span> <span m=''3780470''>told</span> <span m=''3780710''>you</span>
  <span m=''3780870''>about</span> <span m=''3781130''>pairs</span> <span m=''3782570''>is</span>
  <span m=''3782720''>that</span> <span m=''3782860''>there</span> <span m=''3782970''>happens</span>
  <span m=''3783380''>to</span> <span m=''3783480''>be</span> <span m=''3783650''>this</span>
  <span m=''3784090''>property,</span> <span m=''3784980''>these</span> <span m=''3785250''>properties</span>
  <span m=''3785680''>of</span> <span m=''3785770''>cons,</span> <span m=''3786000''>car,</span>
  <span m=''3786340''>and cdr.</span> <span m=''3786860''>And</span> <span m=''3786980''>all</span>
  <span m=''3787140''>I</span> <span m=''3787220''>really</span> <span m=''3787510''>said</span>
  <span m=''3787770''>about</span> <span m=''3787990''>pairs</span> <span m=''3788880''>is</span>
  <span m=''3789030''>that</span> <span m=''3789160''>there''s</span> <span m=''3789330''>a</span>
  <span m=''3789390''>thing</span> <span m=''3789580''>called</span> <span m=''3789840''>cons,</span>
  <span m=''3790350''>and</span> <span m=''3790760''>a</span> <span m=''3791020''>thing</span>
  <span m=''3791150''>called</span> <span m=''3791400''>car,</span> <span m=''3792100''>and</span>
  <span m=''3792190''>a</span> <span m=''3792280''>thing</span> <span m=''3792460''>called</span>
  <span m=''3792680''>cdr.</span> </p><p><span m=''3794870''>And</span> <span m=''3795100''>it</span>
  <span m=''3795250''>is</span> <span m=''3795430''>the</span> <span m=''3795540''>case</span>
  <span m=''3796150''>that</span> <span m=''3796420''>if</span> <span m=''3796560''>I</span>
  <span m=''3796640''>build</span> <span m=''3796920''>cons of</span> <span m=''3797310''>x,</span>
  <span m=''3797510''>y</span> <span m=''3797750''>and</span> <span m=''3797860''>take</span>
  <span m=''3798080''>car</span> <span m=''3798340''>of</span> <span m=''3798470''>it,
  I</span> <span m=''3798590''>get</span> <span m=''3798780''>x.</span> <span m=''3800710''>And</span>
  <span m=''3800890''>if</span> <span m=''3800990''>I</span> <span m=''3802110''>build</span>
  <span m=''3802400''>cons</span> <span m=''3802670''>of</span> <span m=''3802730''>x,</span>
  <span m=''3802890''>y</span> <span m=''3803090''>and</span> <span m=''3803220''>get</span>
  <span m=''3803330''>cdr</span> <span m=''3803530''>of it,</span> <span m=''3803810''>I</span>
  <span m=''3803890''>get</span> <span m=''3804110''>y.</span> <span m=''3805810''>And</span>
  <span m=''3808040''>even</span> <span m=''3808260''>though</span> <span m=''3808430''>I</span>
  <span m=''3810230''>lulled</span> <span m=''3810610''>you</span> <span m=''3810810''>into</span>
  <span m=''3811020''>thinking</span> <span m=''3811360''>that</span> <span m=''3811510''>there''s</span>
  <span m=''3811670''>something</span> <span m=''3812000''>in</span> <span m=''3812160''>Lisp</span>
  <span m=''3812330''>that</span> <span m=''3812530''>does</span> <span m=''3812770''>that,</span>
  <span m=''3813050''>so</span> <span m=''3813200''>you</span> <span m=''3813360''>pretended</span>
  <span m=''3813800''>you</span> <span m=''3813890''>knew</span> <span m=''3814060''>what
  it</span> <span m=''3814180''>was,</span> <span m=''3814790''>in</span> <span m=''3814940''>fact,</span>
  <span m=''3815220''>I</span> <span m=''3815390''>didn''t</span> <span m=''3815630''>tell</span>
  <span m=''3815800''>you</span> <span m=''3815950''>any more</span> <span m=''3816330''>about</span>
  <span m=''3816590''>pairs</span> <span m=''3816880''>than</span> <span m=''3817020''>this</span>
  <span m=''3817180''>tells</span> <span m=''3817400''>you</span> <span m=''3817530''>about</span>
  <span m=''3817750''>rational</span> <span m=''3818150''>numbers.</span> <span m=''3819750''>It''s</span>
  <span m=''3819890''>just</span> <span m=''3820110''>some</span> <span m=''3820240''>axiom</span>
  <span m=''3820680''>for pairs.</span> </p><p><span m=''3824720''>Well,</span> <span
  m=''3826630''>to</span> <span m=''3827080''>drive</span> <span m=''3827380''>that</span>
  <span m=''3827560''>home,</span> <span m=''3828470''>let</span> <span m=''3828610''>me</span>
  <span m=''3828750''>really</span> <span m=''3829060''>scare you,</span> <span m=''3831190''>and</span>
  <span m=''3831730''>show</span> <span m=''3831880''>you</span> <span m=''3832040''>what</span>
  <span m=''3832180''>we</span> <span m=''3832280''>might</span> <span m=''3832510''>build</span>
  <span m=''3833070''>pairs</span> <span m=''3833400''>in</span> <span m=''3833510''>terms</span>
  <span m=''3833870''>of.</span> <span m=''3836120''>And</span> <span m=''3836250''>what</span>
  <span m=''3836370''>you''re</span> <span m=''3836490''>going</span> <span m=''3836550''>to</span>
  <span m=''3836620''>see</span> <span m=''3837860''>is</span> <span m=''3838020''>that</span>
  <span m=''3838160''>we</span> <span m=''3838280''>can</span> <span m=''3838430''>build</span>
  <span m=''3839860''>rational</span> <span m=''3840470''>numbers,</span> <span m=''3840900''>and</span>
  <span m=''3841120''>line</span> <span m=''3841410''>segments,</span> <span m=''3841890''>and</span>
  <span m=''3842060''>vectors,</span> <span m=''3842500''>and</span> <span m=''3842600''>all</span>
  <span m=''3842870''>of this</span> <span m=''3842960''>stuff</span> <span m=''3843230''>in</span>
  <span m=''3843330''>terms</span> <span m=''3843570''>of</span> <span m=''3843660''>pairs,</span>
  <span m=''3844780''>and</span> <span m=''3845160''>we''re</span> <span m=''3845270''>going</span>
  <span m=''3845320''>to</span> <span m=''3845380''>see</span> <span m=''3845570''>below</span>
  <span m=''3845850''>here</span> <span m=''3846160''>that</span> <span m=''3846460''>pairs</span>
  <span m=''3846800''>can</span> <span m=''3846930''>be</span> <span m=''3847070''>built</span>
  <span m=''3847320''>out</span> <span m=''3847430''>of</span> <span m=''3847540''>nothing</span>
  <span m=''3847900''>at</span> <span m=''3848070''>all.</span> <span m=''3850680''>Pure</span>
  <span m=''3851250''>abstraction.</span> </p><p><span m=''3852680''>So</span> <span
  m=''3852920''>let</span> <span m=''3853110''>me</span> <span m=''3853260''>show</span>
  <span m=''3853440''>you</span> <span m=''3853650''>on</span> <span m=''3853770''>this</span>
  <span m=''3853860''>slide</span> <span m=''3856400''>an</span> <span m=''3856560''>implementation</span>
  <span m=''3857620''>of</span> <span m=''3857800''>cons,</span> <span m=''3858140''>car,</span>
  <span m=''3858470''>and cdr.</span> <span m=''3861125''>And we''ll</span> <span
  m=''3861590''>look</span> <span m=''3861940''>at</span> <span m=''3862060''>it</span>
  <span m=''3862130''>again</span> <span m=''3862380''>in</span> <span m=''3862440''>a</span>
  <span m=''3862700''>second,</span> <span m=''3863080''>but</span> <span m=''3864070''>notice</span>
  <span m=''3864360''>that</span> <span m=''3864470''>their</span> <span m=''3864620''>procedure</span>
  <span m=''3865080''>definitions</span> <span m=''3865720''>of</span> <span m=''3865910''>cons,</span>
  <span m=''3866480''>car,</span> <span m=''3866880''>and cdr,</span> <span m=''3867440''>you</span>
  <span m=''3867540''>don''t</span> <span m=''3867700''>see</span> <span m=''3867840''>any</span>
  <span m=''3867990''>data in</span> <span m=''3868490''>there,</span> <span m=''3869390''>what</span>
  <span m=''3869790''>you</span> <span m=''3869850''>see</span> <span m=''3870170''>is</span>
  <span m=''3872020''>a</span> <span m=''3872070''>lambda.</span> <span m=''3874720''>So</span>
  <span m=''3875190''>cons</span> <span m=''3876680''>here</span> <span m=''3877770''>is</span>
  <span m=''3877980''>going</span> <span m=''3878220''>to</span> <span m=''3878360''>return--</span>
  <span m=''3878840''>is</span> <span m=''3878950''>a</span> <span m=''3879000''>procedure</span>
  <span m=''3879470''>that</span> <span m=''3879630''>returns</span> <span m=''3880120''>a</span>
  <span m=''3880180''>procedure,</span> <span m=''3881470''>just</span> <span m=''3881660''>like</span>
  <span m=''3882150''>AVERAGE</span> <span m=''3882550''>DAMP.</span> </p><p><span
  m=''3884630''>Cons</span> <span m=''3885050''>of</span> <span m=''3885340''>a and
  b</span> <span m=''3885740''>returns</span> <span m=''3886220''>a</span> <span m=''3886330''>procedure</span>
  <span m=''3888430''>of</span> <span m=''3888580''>an</span> <span m=''3888650''>argument</span>
  <span m=''3889050''>called</span> <span m=''3889350''>pick,</span> <span m=''3892010''>and</span>
  <span m=''3892170''>it</span> <span m=''3892280''>says,</span> <span m=''3893110''>if</span>
  <span m=''3893360''>pick is</span> <span m=''3893740''>equal</span> <span m=''3893990''>to</span>
  <span m=''3894050''>1,</span> <span m=''3894825''>I''m</span> <span m=''3895130''>going
  to</span> <span m=''3895400''>return a,</span> <span m=''3897450''>and if</span>
  <span m=''3897620''>pick</span> <span m=''3897880''>is</span> <span m=''3897990''>equal</span>
  <span m=''3898210''>to</span> <span m=''3898300''>2,</span> <span m=''3898940''>I''m</span>
  <span m=''3899070''>going</span> <span m=''3899140''>to</span> <span m=''3899220''>return</span>
  <span m=''3899610''>b,</span> <span m=''3900550''>and</span> <span m=''3900710''>that''s</span>
  <span m=''3900870''>what</span> <span m=''3901020''>cons</span> <span m=''3901500''>is
  going</span> <span m=''3901670''>to</span> <span m=''3901830''>be.</span> <span
  m=''3904810''>Car</span> <span m=''3905850''>of</span> <span m=''3908630''>a</span>
  <span m=''3908850''>thing</span> <span m=''3909070''>x,</span> <span m=''3909410''>car</span>
  <span m=''3909710''>of a</span> <span m=''3909760''>pair</span> <span m=''3910120''>x,</span>
  <span m=''3910850''>is</span> <span m=''3911030''>going</span> <span m=''3911110''>to</span>
  <span m=''3911180''>be</span> <span m=''3911370''>x</span> <span m=''3911600''>applied</span>
  <span m=''3911920''>to</span> <span m=''3912090''>1.</span> <span m=''3912320''>And</span>
  <span m=''3912390''>notice</span> <span m=''3912680''>that</span> <span m=''3912840''>makes</span>
  <span m=''3913080''>sense.</span> <span m=''3913470''>You</span> <span m=''3913550''>might</span>
  <span m=''3913650''>not</span> <span m=''3914720''>understand</span> <span m=''3915130''>why</span>
  <span m=''3915450''>or</span> <span m=''3915620''>how</span> <span m=''3915940''>I''m</span>
  <span m=''3916080''>doing</span> <span m=''3916340''>such</span> <span m=''3916580''>a
  thing,</span> <span m=''3916690''>but</span> <span m=''3916810''>at</span> <span
  m=''3916970''>least</span> <span m=''3917120''>it</span> <span m=''3917190''>makes</span>
  <span m=''3917410''>sense,</span> <span m=''3918060''>because</span> <span m=''3918740''>the</span>
  <span m=''3919020''>thing</span> <span m=''3919330''>constructed</span> <span m=''3919820''>by</span>
  <span m=''3919950''>cons</span> <span m=''3920300''>is</span> <span m=''3920400''>a</span>
  <span m=''3920460''>procedure,</span> <span m=''3921550''>and</span> <span m=''3921720''>car</span>
  <span m=''3922020''>applies</span> <span m=''3922400''>that</span> <span m=''3922550''>to</span>
  <span m=''3922680''>1.</span> </p><p><span m=''3924630''>And</span> <span m=''3924820''>similarly,</span>
  <span m=''3925570''>cdr</span> <span m=''3925910''>applies</span> <span m=''3926280''>that</span>
  <span m=''3926420''>thing to</span> <span m=''3926650''>2.</span> <span m=''3929370''>OK,
  now</span> <span m=''3929690''>I</span> <span m=''3929820''>claimed</span> <span
  m=''3930130''>that</span> <span m=''3930390''>this</span> <span m=''3930870''>is</span>
  <span m=''3931040''>a</span> <span m=''3931110''>representation</span> <span m=''3932280''>of</span>
  <span m=''3932450''>cons,</span> <span m=''3933140''>car,</span> <span m=''3933290''>and
  cdr, and notice</span> <span m=''3933590''>there''s</span> <span m=''3933760''>no</span>
  <span m=''3933880''>data in it.</span> <span m=''3935780''>All right, it''s</span>
  <span m=''3936130''>built</span> <span m=''3936420''>out</span> <span m=''3936530''>of</span>
  <span m=''3936750''>air.</span> <span m=''3937190''>It''s</span> <span m=''3937400''>just</span>
  <span m=''3937640''>procedures.</span> <span m=''3939600''>There''s</span> <span
  m=''3939960''>no</span> <span m=''3940090''>data</span> <span m=''3940400''>objects</span>
  <span m=''3940770''>at</span> <span m=''3940970''>all</span> <span m=''3941390''>in</span>
  <span m=''3941510''>that</span> <span m=''3941680''>representation.</span> <span
  m=''3943660''>Well,</span> <span m=''3944010''>what</span> <span m=''3944120''>could</span>
  <span m=''3944220''>that</span> <span m=''3944370''>possibly</span> <span m=''3944880''>mean?</span>
  <span m=''3949690''>Well,</span> <span m=''3949990''>if</span> <span m=''3950120''>you</span>
  <span m=''3950260''>really</span> <span m=''3950620''>believe</span> <span m=''3951010''>this</span>
  <span m=''3951200''>stuff,</span> <span m=''3954320''>then</span> <span m=''3954490''>you</span>
  <span m=''3954580''>have</span> <span m=''3954780''>to</span> <span m=''3954990''>believe</span>
  <span m=''3955750''>that</span> <span m=''3956630''>in</span> <span m=''3956780''>order</span>
  <span m=''3957060''>to</span> <span m=''3957130''>show</span> <span m=''3957430''>that</span>
  <span m=''3957590''>that''s</span> <span m=''3957810''>a</span> <span m=''3957870''>representation</span>
  <span m=''3958650''>for</span> <span m=''3958780''>cons,</span> <span m=''3959090''>car,</span>
  <span m=''3959390''>and cdr,</span> <span m=''3959750''>all</span> <span m=''3960210''>I</span>
  <span m=''3960330''>have</span> <span m=''3960440''>to</span> <span m=''3960560''>do</span>
  <span m=''3960810''>is</span> <span m=''3960940''>show</span> <span m=''3961140''>that</span>
  <span m=''3961270''>it</span> <span m=''3961390''>satisfies</span> <span m=''3961930''>the</span>
  <span m=''3962070''>axiom.</span> </p><p><span m=''3963550''>See,</span> <span m=''3963710''>all</span>
  <span m=''3964000''>I</span> <span m=''3964070''>should</span> <span m=''3964240''>have</span>
  <span m=''3964420''>to</span> <span m=''3964520''>convince</span> <span m=''3964870''>you</span>
  <span m=''3965010''>of</span> <span m=''3965410''>is,</span> <span m=''3965740''>for</span>
  <span m=''3966070''>example,</span> <span m=''3966990''>that</span> <span m=''3969490''>gee,</span>
  <span m=''3969700''>that</span> <span m=''3969900''>car</span> <span m=''3972440''>of</span>
  <span m=''3973930''>cons</span> <span m=''3975340''>of</span> <span m=''3975800''>37</span>
  <span m=''3976780''>and</span> <span m=''3976960''>49</span> <span m=''3982310''>is</span>
  <span m=''3982650''>37</span> <span m=''3983600''>for</span> <span m=''3983760''>arbitrary</span>
  <span m=''3984220''>values</span> <span m=''3984640''>of</span> <span m=''3984740''>37</span>
  <span m=''3985270''>and</span> <span m=''3985360''>49.</span> <span m=''3988060''>And</span>
  <span m=''3988220''>cdr</span> <span m=''3988480''>the</span> <span m=''3988590''>same</span>
  <span m=''3988850''>way.</span> <span m=''3992070''>See,</span> <span m=''3992240''>if</span>
  <span m=''3992340''>I</span> <span m=''3992410''>really</span> <span m=''3992710''>can</span>
  <span m=''3993350''>demonstrate</span> <span m=''3994030''>to</span> <span m=''3994130''>you</span>
  <span m=''3994430''>that</span> <span m=''3994860''>that</span> <span m=''3995050''>weird</span>
  <span m=''3995400''>procedure</span> <span m=''3995830''>definition,</span> <span
  m=''3996990''>in</span> <span m=''3997120''>terms</span> <span m=''3997430''>of</span>
  <span m=''3997540''>[? air ?],</span> <span m=''3998530''>has</span> <span m=''3998810''>the</span>
  <span m=''3998900''>property</span> <span m=''3999350''>that</span> <span m=''3999480''>it</span>
  <span m=''3999610''>satisfies</span> <span m=''4000230''>this,</span> <span m=''4001810''>then</span>
  <span m=''4002180''>you</span> <span m=''4002330''>just</span> <span m=''4002550''>have</span>
  <span m=''4002700''>to</span> <span m=''4002860''>grant</span> <span m=''4003160''>me</span>
  <span m=''4003360''>that</span> <span m=''4003680''>that</span> <span m=''4003880''>is</span>
  <span m=''4004660''>a</span> <span m=''4004730''>possible</span> <span m=''4005290''>implementation</span>
  <span m=''4006270''>of</span> <span m=''4006520''>cons,</span> <span m=''4006760''>car,</span>
  <span m=''4007100''>and cdr,</span> <span m=''4007590''>on</span> <span m=''4007730''>which</span>
  <span m=''4007910''>I</span> <span m=''4007970''>can</span> <span m=''4008110''>build</span>
  <span m=''4008320''>everything</span> <span m=''4008720''>else.</span> </p><p><span
  m=''4010030''>Well,</span> <span m=''4010190''>let''s</span> <span m=''4010370''>look</span>
  <span m=''4010510''>at</span> <span m=''4010650''>that.</span> <span m=''4010980''>And
  this will</span> <span m=''4011250''>be</span> <span m=''4011370''>practice in</span>
  <span m=''4012550''>the</span> <span m=''4012660''>substitution</span> <span m=''4013340''>model.</span>
  <span m=''4019320''>How</span> <span m=''4019800''>could</span> <span m=''4020130''>we</span>
  <span m=''4020290''>check</span> <span m=''4020550''>this?</span> <span m=''4020690''>We</span>
  <span m=''4020780''>sort of</span> <span m=''4021010''>know</span> <span m=''4021200''>how</span>
  <span m=''4021300''>to</span> <span m=''4021410''>do</span> <span m=''4021590''>that.</span>
  <span m=''4021840''>It''s</span> <span m=''4021960''>just</span> <span m=''4022130''>the</span>
  <span m=''4022200''>same</span> <span m=''4022520''>substitution</span> <span m=''4023220''>model.</span>
  <span m=''4025920''>Let''s</span> <span m=''4026140''>look.</span> <span m=''4026310''>We</span>
  <span m=''4026390''>start</span> <span m=''4026780''>out,</span> <span m=''4026990''>and
  we</span> <span m=''4027110''>say,</span> <span m=''4027280''>what''s</span> <span
  m=''4027530''>car</span> <span m=''4027830''>of</span> <span m=''4027910''>cons
  of</span> <span m=''4028340''>37</span> <span m=''4028800''>and</span> <span m=''4028890''>49?</span>
  <span m=''4031120''>What</span> <span m=''4031310''>do we</span> <span m=''4031430''>do?</span>
  <span m=''4031720''>Cons is</span> <span m=''4032180''>some</span> <span m=''4032720''>procedure.</span>
  <span m=''4035950''>Its</span> <span m=''4036170''>value</span> <span m=''4036670''>is</span>
  <span m=''4037430''>cons</span> <span m=''4037840''>was a</span> <span m=''4037900''>procedure</span>
  <span m=''4038310''>of a</span> <span m=''4038670''>and b.</span> <span m=''4039530''>The</span>
  <span m=''4040070''>thing</span> <span m=''4040300''>returned</span> <span m=''4040720''>by</span>
  <span m=''4040920''>cons</span> <span m=''4041730''>is</span> <span m=''4042090''>its</span>
  <span m=''4042300''>procedure</span> <span m=''4042750''>body</span> <span m=''4043440''>with</span>
  <span m=''4044190''>37</span> <span m=''4045290''>and</span> <span m=''4045450''>49</span>
  <span m=''4045900''>substituted</span> <span m=''4046470''>for</span> <span m=''4046560''>the</span>
  <span m=''4046640''>parameters.</span> <span m=''4047370''>It''ll</span> <span m=''4047530''>be</span>
  <span m=''4047630''>37</span> <span m=''4048200''>substituted</span> <span m=''4048810''>for
  a</span> <span m=''4049650''>and</span> <span m=''4049800''>49</span> <span m=''4050280''>substituted</span>
  <span m=''4050890''>for</span> <span m=''4051010''>b.</span> </p><p><span m=''4052770''>So</span>
  <span m=''4053160''>this</span> <span m=''4053580''>expression</span> <span m=''4054590''>has</span>
  <span m=''4054830''>the</span> <span m=''4054900''>same</span> <span m=''4055200''>meaning</span>
  <span m=''4055790''>as</span> <span m=''4056480''>this</span> <span m=''4056710''>expression.</span>
  <span m=''4057170''>Its</span> <span m=''4057330''>car</span> <span m=''4057730''>of,</span>
  <span m=''4058500''>and</span> <span m=''4058870''>the</span> <span m=''4059090''>body</span>
  <span m=''4059400''>of</span> <span m=''4059480''>cons</span> <span m=''4059830''>was</span>
  <span m=''4059980''>this</span> <span m=''4060140''>thing</span> <span m=''4060270''>that</span>
  <span m=''4060410''>started</span> <span m=''4060700''>with</span> <span m=''4060840''>lambda.</span>
  <span m=''4063190''>And</span> <span m=''4063360''>it says,</span> <span m=''4063890''>so</span>
  <span m=''4064180''>if</span> <span m=''4064950''>pick</span> <span m=''4065250''>is</span>
  <span m=''4065440''>equal</span> <span m=''4065680''>to</span> <span m=''4065740''>1,</span>
  <span m=''4066090''>where</span> <span m=''4066250''>pick</span> <span m=''4066470''>is</span>
  <span m=''4066570''>this</span> <span m=''4066730''>other</span> <span m=''4066970''>argument,</span>
  <span m=''4067630''>if</span> <span m=''4067740''>pick</span> <span m=''4067950''>is</span>
  <span m=''4068050''>equal</span> <span m=''4068260''>to</span> <span m=''4068320''>1,</span>
  <span m=''4068930''>it''s</span> <span m=''4069120''>37,</span> <span m=''4069790''>that''s</span>
  <span m=''4070070''>where</span> <span m=''4070210''>a</span> <span m=''4070400''>was,</span>
  <span m=''4071450''>and if</span> <span m=''4071550''>pick</span> <span m=''4071850''>is</span>
  <span m=''4071950''>equal</span> <span m=''4072160''>to</span> <span m=''4072250''>2,</span>
  <span m=''4073000''>it''s</span> <span m=''4073210''>49.</span> <span m=''4075240''>So</span>
  <span m=''4075410''>that''s</span> <span m=''4075600''>the</span> <span m=''4075780''>first</span>
  <span m=''4075960''>step.</span> <span m=''4076410''>I''m</span> <span m=''4076610''>just</span>
  <span m=''4076870''>going</span> <span m=''4077130''>through</span> <span m=''4077530''>mechanical</span>
  <span m=''4078200''>substitution.</span> <span m=''4079460''>And</span> <span m=''4079610''>remember,</span>
  <span m=''4080060''>at</span> <span m=''4080140''>this</span> <span m=''4080320''>point</span>
  <span m=''4080530''>in</span> <span m=''4080580''>the</span> <span m=''4080660''>course,</span>
  <span m=''4080940''>if</span> <span m=''4081040''>you''re</span> <span m=''4081150''>confused</span>
  <span m=''4081630''>about</span> <span m=''4081850''>what</span> <span m=''4082030''>things</span>
  <span m=''4082250''>mean,</span> <span m=''4082610''>go</span> <span m=''4083290''>mechanically</span>
  <span m=''4083970''>through</span> <span m=''4084110''>the</span> <span m=''4084190''>substitution</span>
  <span m=''4084830''>model.</span> </p><p><span m=''4085480''>Well,</span> <span
  m=''4085570''>what</span> <span m=''4085740''>is</span> <span m=''4085860''>this</span>
  <span m=''4086060''>reduced</span> <span m=''4086510''>to?</span> <span m=''4087920''>Car</span>
  <span m=''4088270''>said,</span> <span m=''4089710''>take</span> <span m=''4092740''>your</span>
  <span m=''4093000''>argument,</span> <span m=''4093610''>which</span> <span m=''4093800''>in</span>
  <span m=''4093910''>this</span> <span m=''4094020''>case</span> <span m=''4094270''>is</span>
  <span m=''4094400''>this,</span> <span m=''4095050''>and</span> <span m=''4095210''>apply</span>
  <span m=''4095530''>it</span> <span m=''4095620''>to</span> <span m=''4095720''>1.</span>
  <span m=''4096060''>That</span> <span m=''4096300''>was</span> <span m=''4096439''>the</span>
  <span m=''4096520''>definition</span> <span m=''4096990''>of</span> <span m=''4097100''>car.</span>
  <span m=''4097979''>So</span> <span m=''4098210''>if I</span> <span m=''4098310''>look</span>
  <span m=''4098510''>at</span> <span m=''4098609''>car,</span> <span m=''4100200''>if</span>
  <span m=''4100580''>I</span> <span m=''4100700''>do</span> <span m=''4100930''>that,</span>
  <span m=''4101609''>the</span> <span m=''4101800''>answer</span> <span m=''4102109''>is,</span>
  <span m=''4102370''>well,</span> <span m=''4102600''>it''s</span> <span m=''4102930''>that</span>
  <span m=''4103060''>argument,</span> <span m=''4103640''>this</span> <span m=''4103800''>was</span>
  <span m=''4103930''>the</span> <span m=''4104020''>argument</span> <span m=''4104380''>to</span>
  <span m=''4104470''>car,</span> <span m=''4105165''>applied</span> <span m=''4105630''>to</span>
  <span m=''4106040''>1.</span> <span m=''4109580''>Well,</span> <span m=''4109939''>what</span>
  <span m=''4110060''>does</span> <span m=''4110180''>that</span> <span m=''4110430''>mean?</span>
  <span m=''4111140''>I</span> <span m=''4111260''>take</span> <span m=''4111800''>1,</span>
  <span m=''4112490''>and</span> <span m=''4112609''>I</span> <span m=''4112740''>substitute
  it</span> <span m=''4113450''>in</span> <span m=''4113560''>the</span> <span m=''4113630''>body</span>
  <span m=''4113970''>here</span> <span m=''4114479''>for</span> <span m=''4114700''>this</span>
  <span m=''4114800''>value</span> <span m=''4115090''>of</span> <span m=''4115270''>pick,</span>
  <span m=''4115950''>which</span> <span m=''4116120''>is</span> <span m=''4116210''>the</span>
  <span m=''4116290''>name</span> <span m=''4116490''>of</span> <span m=''4116529''>the</span>
  <span m=''4116630''>argument,</span> <span m=''4117939''>what do</span> <span m=''4118229''>I
  get?</span> <span m=''4119779''>Well,</span> <span m=''4120050''>I</span> <span
  m=''4120120''>get</span> <span m=''4120279''>the</span> <span m=''4120370''>thing</span>
  <span m=''4120550''>that</span> <span m=''4120710''>says</span> <span m=''4120890''>if</span>
  <span m=''4121029''>1</span> <span m=''4121220''>equals</span> <span m=''4122069''>1</span>
  <span m=''4122300''>it''s</span> <span m=''4122450''>37,</span> <span m=''4123390''>and</span>
  <span m=''4123660''>if 1</span> <span m=''4123819''>equals</span> <span m=''4124100''>2</span>
  <span m=''4124260''>it''s</span> <span m=''4124430''>49,</span> <span m=''4124880''>so</span>
  <span m=''4124990''>the</span> <span m=''4125109''>answer''s</span> <span m=''4125399''>37.</span>
  <span m=''4126700''>And</span> <span m=''4126840''>similarly,</span> <span m=''4127340''>if</span>
  <span m=''4127460''>I''d</span> <span m=''4128240''>taken</span> <span m=''4128550''>cdr,</span>
  <span m=''4128850''>that</span> <span m=''4129010''>would</span> <span m=''4129200''>apply
  it</span> <span m=''4129520''>to</span> <span m=''4129660''>2,</span> <span m=''4129880''>and
  I''d</span> <span m=''4130060''>get</span> <span m=''4130260''>49.</span> </p><p><span
  m=''4131729''>So</span> <span m=''4131910''>you see,</span> <span m=''4132010''>what
  I''ve</span> <span m=''4132260''>demonstrated</span> <span m=''4133810''>is</span>
  <span m=''4133970''>that</span> <span m=''4134600''>that</span> <span m=''4135020''>completely</span>
  <span m=''4135510''>weird</span> <span m=''4135870''>implementation</span> <span
  m=''4136590''>of</span> <span m=''4136689''>cons,</span> <span m=''4136969''>car,</span>
  <span m=''4137560''>and cdr,</span> <span m=''4137870''>satisfies</span> <span m=''4138540''>the</span>
  <span m=''4138670''>axioms.</span> <span m=''4140120''>So</span> <span m=''4140310''>it''s</span>
  <span m=''4140390''>a</span> <span m=''4140450''>perfectly</span> <span m=''4140950''>valid</span>
  <span m=''4141390''>way</span> <span m=''4142000''>of</span> <span m=''4142180''>building,</span>
  <span m=''4142640''>in</span> <span m=''4142740''>fact,</span> <span m=''4143000''>all</span>
  <span m=''4143140''>of the</span> <span m=''4143279''>data</span> <span m=''4143600''>objects</span>
  <span m=''4143939''>we''re</span> <span m=''4144029''>going</span> <span m=''4144100''>to</span>
  <span m=''4144170''>see</span> <span m=''4144370''>in</span> <span m=''4144439''>Lisp.</span>
  <span m=''4145620''>So</span> <span m=''4145760''>they</span> <span m=''4146010''>all,</span>
  <span m=''4146149''>if</span> <span m=''4146229''>you</span> <span m=''4146340''>like,</span>
  <span m=''4146510''>can</span> <span m=''4146590''>be</span> <span m=''4146740''>built</span>
  <span m=''4147000''>on</span> <span m=''4147500''>sort of</span> <span m=''4147930''>existential</span>
  <span m=''4148540''>nothing.</span> <span m=''4149670''>And</span> <span m=''4150010''>as</span>
  <span m=''4150270''>far</span> <span m=''4150609''>as</span> <span m=''4150700''>you</span>
  <span m=''4150830''>know,</span> <span m=''4151100''>that''s</span> <span m=''4151359''>how</span>
  <span m=''4151550''>it</span> <span m=''4151630''>works.</span> <span m=''4154229''>You</span>
  <span m=''4154350''>couldn''t</span> <span m=''4154740''>tell.</span> <span m=''4155149''>If</span>
  <span m=''4155290''>all</span> <span m=''4155540''>you''re</span> <span m=''4155689''>ever</span>
  <span m=''4155950''>going</span> <span m=''4156050''>to</span> <span m=''4156149''>do</span>
  <span m=''4157260''>with</span> <span m=''4157500''>pairs</span> <span m=''4157920''>is</span>
  <span m=''4158050''>construct them</span> <span m=''4158580''>with</span> <span
  m=''4158729''>cons</span> <span m=''4159060''>and</span> <span m=''4159160''>look</span>
  <span m=''4159270''>at</span> <span m=''4159390''>them</span> <span m=''4159520''>with</span>
  <span m=''4159660''>car</span> <span m=''4159970''>and cdr,</span> <span m=''4160439''>you</span>
  <span m=''4160580''>couldn''t</span> <span m=''4160890''>possibly</span> <span m=''4161410''>tell</span>
  <span m=''4161609''>how</span> <span m=''4161810''>this</span> <span m=''4162020''>thing</span>
  <span m=''4162170''>works.</span> </p><p><span m=''4164270''>Now,</span> <span m=''4164430''>it
  might</span> <span m=''4164689''>give</span> <span m=''4164790''>you a</span> <span
  m=''4164930''>sort</span> <span m=''4165120''>of</span> <span m=''4165210''>warm</span>
  <span m=''4165500''>feeling</span> <span m=''4165830''>inside</span> <span m=''4166200''>if</span>
  <span m=''4166310''>I</span> <span m=''4166370''>say,</span> <span m=''4166529''>well,</span>
  <span m=''4166680''>yeah,</span> <span m=''4166890''>in</span> <span m=''4166979''>fact,</span>
  <span m=''4167790''>for</span> <span m=''4168210''>various</span> <span m=''4168640''>reasons</span>
  <span m=''4169000''>there</span> <span m=''4169120''>happens</span> <span m=''4169470''>to</span>
  <span m=''4169550''>be a</span> <span m=''4169710''>primitive</span> <span m=''4170640''>called</span>
  <span m=''4170859''>cons,</span> <span m=''4171149''>car, and</span> <span m=''4171439''>cdr,</span>
  <span m=''4171770''>and</span> <span m=''4172560''>if</span> <span m=''4172660''>it''s</span>
  <span m=''4172800''>too</span> <span m=''4172930''>scary,</span> <span m=''4173275''>if</span>
  <span m=''4173620''>this</span> <span m=''4173920''>kind</span> <span m=''4174020''>of</span>
  <span m=''4174109''>stuff</span> <span m=''4174319''>is</span> <span m=''4174430''>too</span>
  <span m=''4174550''>scary,</span> <span m=''4174950''>you</span> <span m=''4175029''>don''t</span>
  <span m=''4175180''>have</span> <span m=''4175330''>to</span> <span m=''4175430''>look</span>
  <span m=''4175600''>inside</span> <span m=''4175960''>of</span> <span m=''4176050''>it.</span>
  <span m=''4176770''>So that</span> <span m=''4177080''>might</span> <span m=''4177160''>make</span>
  <span m=''4177310''>you</span> <span m=''4177370''>feel</span> <span m=''4177640''>better,</span>
  <span m=''4179069''>but</span> <span m=''4179180''>the</span> <span m=''4179290''>point</span>
  <span m=''4179520''>is,</span> <span m=''4179870''>it</span> <span m=''4180060''>really</span>
  <span m=''4180319''>could</span> <span m=''4180580''>work</span> <span m=''4180810''>this</span>
  <span m=''4181020''>way,</span> <span m=''4182100''>and</span> <span m=''4182189''>it</span>
  <span m=''4182279''>wouldn''t</span> <span m=''4182460''>make</span> <span m=''4182660''>any</span>
  <span m=''4182910''>difference</span> <span m=''4183250''>to</span> <span m=''4183319''>the</span>
  <span m=''4183410''>system</span> <span m=''4183779''>at</span> <span m=''4183990''>all.</span>
  <span m=''4186590''>So</span> <span m=''4186800''>in</span> <span m=''4186880''>some</span>
  <span m=''4187080''>sense,</span> <span m=''4187390''>we</span> <span m=''4187540''>don''t</span>
  <span m=''4187660''>need</span> <span m=''4187790''>data</span> <span m=''4188050''>at</span>
  <span m=''4188240''>all</span> <span m=''4188640''>to</span> <span m=''4188800''>build</span>
  <span m=''4188979''>these</span> <span m=''4189140''>data</span> <span m=''4189359''>abstractions.</span>
  <span m=''4191760''>We</span> <span m=''4191939''>can</span> <span m=''4192029''>do</span>
  <span m=''4192149''>everything</span> <span m=''4192550''>in</span> <span m=''4192640''>terms</span>
  <span m=''4192899''>of</span> <span m=''4192979''>procedures.</span> </p><p><span
  m=''4194860''>OK,</span> <span m=''4195090''>well,</span> <span m=''4195210''>why</span>
  <span m=''4195380''>did</span> <span m=''4195480''>I</span> <span m=''4195550''>terrify</span>
  <span m=''4196040''>you in</span> <span m=''4196280''>this</span> <span m=''4196440''>way?</span>
  <span m=''4197500''>First,</span> <span m=''4197740''>I</span> <span m=''4197790''>really</span>
  <span m=''4198120''>want</span> <span m=''4198270''>to</span> <span m=''4198560''>reinforce</span>
  <span m=''4199130''>this</span> <span m=''4199280''>idea</span> <span m=''4199580''>of</span>
  <span m=''4199660''>abstraction,</span> <span m=''4202140''>that</span> <span m=''4202360''>you</span>
  <span m=''4202500''>really</span> <span m=''4202800''>can</span> <span m=''4203120''>do</span>
  <span m=''4203260''>these</span> <span m=''4203470''>things</span> <span m=''4203670''>abstractly.</span>
  <span m=''4206220''>Secondly,</span> <span m=''4206760''>I</span> <span m=''4206850''>want</span>
  <span m=''4206980''>to</span> <span m=''4207560''>introduce</span> <span m=''4209740''>an</span>
  <span m=''4209890''>idea</span> <span m=''4210200''>we''re</span> <span m=''4210320''>going</span>
  <span m=''4210390''>to</span> <span m=''4210450''>see</span> <span m=''4210640''>more</span>
  <span m=''4211070''>and</span> <span m=''4211170''>more</span> <span m=''4211450''>of</span>
  <span m=''4211590''>in</span> <span m=''4211760''>this</span> <span m=''4211920''>course,</span>
  <span m=''4214160''>which</span> <span m=''4214430''>is</span> <span m=''4214950''>we''re</span>
  <span m=''4215100''>going</span> <span m=''4215190''>to</span> <span m=''4215280''>blur</span>
  <span m=''4215720''>the</span> <span m=''4215830''>line</span> <span m=''4216360''>between</span>
  <span m=''4216890''>what''s</span> <span m=''4217150''>data</span> <span m=''4217440''>and</span>
  <span m=''4217590''>what''s</span> <span m=''4217730''>a</span> <span m=''4217880''>procedure.</span>
  </p><p><span m=''4219715''>See,</span> <span m=''4220150''>in</span> <span m=''4220450''>this</span>
  <span m=''4220760''>funny</span> <span m=''4221080''>implementation</span> <span
  m=''4221840''>it</span> <span m=''4221940''>turned</span> <span m=''4222220''>out</span>
  <span m=''4222350''>that</span> <span m=''4222800''>cons</span> <span m=''4224280''>of</span>
  <span m=''4224430''>something</span> <span m=''4225060''>happened</span> <span m=''4225450''>to</span>
  <span m=''4225540''>be</span> <span m=''4225660''>represented</span> <span m=''4226260''>in</span>
  <span m=''4226340''>terms</span> <span m=''4226660''>of</span> <span m=''4226770''>a</span>
  <span m=''4226830''>procedure,</span> <span m=''4227320''>even</span> <span m=''4227610''>though</span>
  <span m=''4227860''>we</span> <span m=''4228070''>think</span> <span m=''4228330''>of</span>
  <span m=''4228440''>it</span> <span m=''4228540''>as</span> <span m=''4228710''>data.</span>
  <span m=''4231940''>While</span> <span m=''4232080''>here</span> <span m=''4232280''>that''s</span>
  <span m=''4232460''>sort of</span> <span m=''4232580''>a</span> <span m=''4232700''>mathematical</span>
  <span m=''4233360''>trick,</span> <span m=''4234630''>but</span> <span m=''4234980''>one</span>
  <span m=''4235300''>of</span> <span m=''4235360''>the</span> <span m=''4235420''>things</span>
  <span m=''4235650''>we''ll</span> <span m=''4235750''>see</span> <span m=''4236200''>is</span>
  <span m=''4236350''>that</span> <span m=''4236470''>a</span> <span m=''4236510''>lot</span>
  <span m=''4236960''>of</span> <span m=''4237150''>the</span> <span m=''4237250''>very</span>
  <span m=''4237600''>important</span> <span m=''4238050''>programming</span> <span
  m=''4238540''>techniques</span> <span m=''4238990''>that</span> <span m=''4239090''>we''re</span>
  <span m=''4239200''>going</span> <span m=''4239260''>to</span> <span m=''4239320''>get</span>
  <span m=''4239530''>to</span> <span m=''4241920''>sort</span> <span m=''4242030''>of</span>
  <span m=''4242150''>depend</span> <span m=''4242520''>very</span> <span m=''4242780''>crucially</span>
  <span m=''4243560''>on</span> <span m=''4243810''>blurring</span> <span m=''4244400''>this</span>
  <span m=''4245010''>traditional</span> <span m=''4245570''>line</span> <span m=''4245840''>between</span>
  <span m=''4246340''>what</span> <span m=''4246600''>you</span> <span m=''4246700''>consider
  a</span> <span m=''4247120''>procedure</span> <span m=''4247580''>and</span> <span
  m=''4247640''>what</span> <span m=''4247850''>you</span> <span m=''4247940''>consider</span>
  <span m=''4248340''>data.</span> <span m=''4248950''>We''re going to</span> <span
  m=''4249130''>see</span> <span m=''4249300''>more</span> <span m=''4249540''>and</span>
  <span m=''4249600''>more</span> <span m=''4249840''>of that,</span> <span m=''4250060''>especially</span>
  <span m=''4250500''>next</span> <span m=''4250750''>time.</span> </p><p><span m=''4252495''>OK,</span>
  <span m=''4253290''>questions?</span> </p><p><span m=''4255190''>AUDIENCE: If you</span>
  <span m=''4255410''>asked</span> <span m=''4256240''>the</span> <span m=''4256560''>system</span>
  <span m=''4256770''>to</span> <span m=''4256790''>print</span> <span m=''4257290''>a,</span>
  <span m=''4258790''>what</span> <span m=''4259040''>would</span> <span m=''4259470''>happen?</span>
  </p><p><span m=''4260720''>PROFESSOR: The</span> <span m=''4260860''>question</span>
  <span m=''4261210''>is,</span> <span m=''4261310''>what</span> <span m=''4263790''>would</span>
  <span m=''4263900''>happen</span> <span m=''4264190''>if</span> <span m=''4264300''>I</span>
  <span m=''4264390''>asked</span> <span m=''4264570''>the</span> <span m=''4264620''>system</span>
  <span m=''4264900''>to</span> <span m=''4264980''>print a.</span> <span m=''4265600''>Given</span>
  <span m=''4265930''>this</span> <span m=''4266090''>representation,</span> <span
  m=''4267260''>you</span> <span m=''4267410''>already</span> <span m=''4267620''>know</span>
  <span m=''4267740''>the</span> <span m=''4267890''>answer.</span> <span m=''4270200''>The</span>
  <span m=''4270380''>answer</span> <span m=''4270680''>is</span> <span m=''4274080''>compound</span>
  <span m=''4274950''>procedure</span> <span m=''4275460''>a,</span> <span m=''4276360''>just</span>
  <span m=''4276670''>like</span> <span m=''4277700''>last</span> <span m=''4278030''>time.</span>
  <span m=''4281170''>It''d</span> <span m=''4281480''>say</span> <span m=''4281800''>compound</span>
  <span m=''4282320''>procedure.</span> <span m=''4285150''>It</span> <span m=''4285610''>might</span>
  <span m=''4285750''>say a</span> <span m=''4285930''>little</span> <span m=''4286120''>bit</span>
  <span m=''4286240''>more.</span> <span m=''4286420''>It might</span> <span m=''4286610''>say</span>
  <span m=''4286720''>compound</span> <span m=''4287150''>procedure</span> <span m=''4287500''>lambda</span>
  <span m=''4287830''>or</span> <span m=''4287880''>something</span> <span m=''4288250''>or</span>
  <span m=''4288360''>other,</span> <span m=''4289620''>depending</span> <span m=''4289990''>on</span>
  <span m=''4290570''>details</span> <span m=''4290960''>of</span> <span m=''4291060''>how</span>
  <span m=''4291210''>I</span> <span m=''4291280''>named</span> <span m=''4291610''>it.</span>
  <span m=''4291730''>But</span> <span m=''4291860''>it''s</span> <span m=''4292020''>a</span>
  <span m=''4292090''>procedure.</span> </p><p><span m=''4293070''>And</span> <span
  m=''4293220''>the</span> <span m=''4293370''>only</span> <span m=''4293530''>reason</span>
  <span m=''4293780''>for</span> <span m=''4293880''>that</span> <span m=''4294080''>is</span>
  <span m=''4294770''>I</span> <span m=''4294890''>haven''t</span> <span m=''4295140''>told</span>
  <span m=''4295340''>the</span> <span m=''4295400''>system</span> <span m=''4295790''>anything</span>
  <span m=''4296140''>special</span> <span m=''4297620''>about</span> <span m=''4297930''>how</span>
  <span m=''4298040''>to</span> <span m=''4298140''>print</span> <span m=''4298390''>such</span>
  <span m=''4298640''>things.</span> <span m=''4300220''>Now,</span> <span m=''4300350''>it''s</span>
  <span m=''4300490''>in</span> <span m=''4300560''>fact</span> <span m=''4300920''>true</span>
  <span m=''4301250''>that</span> <span m=''4301950''>with</span> <span m=''4302170''>the</span>
  <span m=''4302350''>actual</span> <span m=''4302840''>implementation</span> <span
  m=''4303500''>of</span> <span m=''4303590''>cons</span> <span m=''4303950''>that</span>
  <span m=''4304320''>to</span> <span m=''4304410''>be</span> <span m=''4304510''>built</span>
  <span m=''4304750''>in</span> <span m=''4304830''>the</span> <span m=''4304890''>system,</span>
  <span m=''4305270''>it would</span> <span m=''4305420''>print</span> <span m=''4305630''>something</span>
  <span m=''4305960''>else.</span> <span m=''4306840''>It</span> <span m=''4307340''>would</span>
  <span m=''4307560''>print,</span> <span m=''4307840''>say,</span> <span m=''4308030''>this</span>
  <span m=''4308250''>is</span> <span m=''4308390''>a</span> <span m=''4308450''>pair.</span>
  </p><p><span m=''4313500''>AUDIENCE: When</span> <span m=''4314170''>you</span>
  <span m=''4314270''>define</span> <span m=''4314730''>cons,</span> <span m=''4318000''>and</span>
  <span m=''4318200''>then you</span> <span m=''4318410''>pass it</span> <span m=''4318870''>into</span>
  <span m=''4319330''>values,</span> <span m=''4321050''>how</span> <span m=''4321340''>does
  it</span> <span m=''4321640''>know</span> <span m=''4321840''>where</span> <span
  m=''4322120''>to</span> <span m=''4322260''>look</span> <span m=''4322730''>for</span>
  <span m=''4323140''>the</span> <span m=''4323310''>cons,</span> <span m=''4323840''>because</span>
  <span m=''4324140''>you</span> <span m=''4325080''>can</span> <span m=''4325460''>use</span>
  <span m=''4325630''>cons</span> <span m=''4325700''>over and over</span> <span m=''4325920''>again?</span>
  <span m=''4327220''>How does it know</span> <span m=''4327520''>where</span> <span
  m=''4327740''>to</span> <span m=''4327880''>look</span> <span m=''4328370''>to</span>
  <span m=''4328900''>know</span> <span m=''4329080''>which</span> <span m=''4330560''>a
  and</span> <span m=''4330970''>b</span> <span m=''4331285''>it''s supposed</span>
  <span m=''4331600''>to</span> <span m=''4331690''>pull</span> <span m=''4331910''>back</span>
  <span m=''4332210''>out?</span> <span m=''4333500''>I don''t know if</span> <span
  m=''4333990''>I''m</span> <span m=''4334480''>expressing that</span> <span m=''4334970''>quite
  right.</span> <span m=''4337140''>Where is</span> <span m=''4337635''>it stored?</span>
  </p><p><span m=''4339120''>PROFESSOR: OK,</span> <span m=''4339420''>the</span>
  <span m=''4339600''>question</span> <span m=''4340040''>is,</span> <span m=''4343140''>I</span>
  <span m=''4343250''>sort</span> <span m=''4343380''>of</span> <span m=''4343510''>have</span>
  <span m=''4343660''>a</span> <span m=''4343720''>cons</span> <span m=''4344160''>with</span>
  <span m=''4344760''>a</span> <span m=''4344820''>37</span> <span m=''4345430''>and
  a</span> <span m=''4345490''>49,</span> <span m=''4345770''>and</span> <span m=''4346050''>I</span>
  <span m=''4346090''>might</span> <span m=''4346290''>make</span> <span m=''4346430''>another</span>
  <span m=''4346750''>cons</span> <span m=''4347370''>with</span> <span m=''4347550''>a
  1 and</span> <span m=''4347880''>a</span> <span m=''4347990''>2,</span> <span m=''4348610''>and</span>
  <span m=''4348740''>I</span> <span m=''4348880''>might</span> <span m=''4349080''>have</span>
  <span m=''4349250''>one</span> <span m=''4349430''>called</span> <span m=''4349680''>a,
  and I</span> <span m=''4349940''>might</span> <span m=''4350200''>have</span> <span
  m=''4350350''>one</span> <span m=''4350520''>called</span> <span m=''4350880''>b.</span>
  <span m=''4351920''>And</span> <span m=''4352020''>the</span> <span m=''4352120''>question</span>
  <span m=''4352360''>is,</span> <span m=''4352430''>how</span> <span m=''4352530''>does</span>
  <span m=''4352690''>it</span> <span m=''4352810''>know?</span> <span m=''4353400''>And</span>
  <span m=''4353640''>why</span> <span m=''4353790''>don''t</span> <span m=''4353960''>they</span>
  <span m=''4354060''>get</span> <span m=''4354240''>confused?</span> <span m=''4355275''>And</span>
  <span m=''4355610''>that''s</span> <span m=''4355900''>a</span> <span m=''4355960''>very</span>
  <span m=''4356910''>good</span> <span m=''4357070''>question.</span> <span m=''4360820''>See,
  you</span> <span m=''4360990''>have</span> <span m=''4361190''>to</span> <span m=''4361310''>really</span>
  <span m=''4361590''>believe</span> <span m=''4362260''>that</span> <span m=''4362630''>the</span>
  <span m=''4362730''>procedures</span> <span m=''4363280''>are</span> <span m=''4363410''>objects.</span>
  </p><p><span m=''4365550''>It''s</span> <span m=''4365670''>sort</span> <span m=''4365930''>of</span>
  <span m=''4366030''>like</span> <span m=''4366250''>saying--</span> <span m=''4366490''>let''s</span>
  <span m=''4366630''>try another</span> <span m=''4367240''>simpler</span> <span
  m=''4367710''>example.</span> <span m=''4369340''>Suppose</span> <span m=''4369630''>I</span>
  <span m=''4369740''>ask</span> <span m=''4370010''>for</span> <span m=''4370090''>the</span>
  <span m=''4370190''>square</span> <span m=''4370560''>root</span> <span m=''4370750''>of</span>
  <span m=''4370880''>3.</span> <span m=''4375760''>So I</span> <span m=''4376160''>asked
  for</span> <span m=''4376240''>the</span> <span m=''4376440''>square root</span>
  <span m=''4376760''>of</span> <span m=''4376840''>5,</span> <span m=''4378260''>and</span>
  <span m=''4378440''>then</span> <span m=''4378560''>I</span> <span m=''4378680''>ask</span>
  <span m=''4378990''>for</span> <span m=''4379110''>the</span> <span m=''4379220''>square</span>
  <span m=''4379880''>of</span> <span m=''4380353''>20.</span> <span m=''4386470''>You''re</span>
  <span m=''4386590''>probably</span> <span m=''4386870''>not</span> <span m=''4387030''>the</span>
  <span m=''4387110''>least</span> <span m=''4387390''>bit</span> <span m=''4387590''>bothered</span>
  <span m=''4388310''>that</span> <span m=''4388540''>I</span> <span m=''4388640''>can</span>
  <span m=''4388800''>take</span> <span m=''4389050''>square</span> <span m=''4389510''>root</span>
  <span m=''4389590''>and</span> <span m=''4389660''>apply</span> <span m=''4389980''>it</span>
  <span m=''4390070''>to</span> <span m=''4390150''>5,</span> <span m=''4390480''>and</span>
  <span m=''4390590''>then</span> <span m=''4390700''>I</span> <span m=''4390800''>can</span>
  <span m=''4390940''>take</span> <span m=''4391150''>square</span> <span m=''4391470''>root</span>
  <span m=''4391790''>and</span> <span m=''4392400''>apply</span> <span m=''4392740''>it</span>
  <span m=''4392840''>to</span> <span m=''4392930''>20.</span> <span m=''4394880''>And</span>
  <span m=''4395110''>there''s</span> <span m=''4395240''>sort</span> <span m=''4395400''>of</span>
  <span m=''4395480''>no</span> <span m=''4395630''>issue,</span> <span m=''4395940''>gee,</span>
  <span m=''4396040''>doesn''t</span> <span m=''4396280''>it</span> <span m=''4396380''>get</span>
  <span m=''4396530''>confused</span> <span m=''4396980''>about</span> <span m=''4397160''>whether</span>
  <span m=''4397390''>it''s</span> <span m=''4397500''>working</span> <span m=''4397830''>on</span>
  <span m=''4397990''>5</span> <span m=''4398300''>or</span> <span m=''4398370''>20?</span>
  <span m=''4399630''>There''s</span> <span m=''4399860''>no</span> <span m=''4400020''>issue</span>
  <span m=''4400400''>about</span> <span m=''4400710''>that</span> <span m=''4400940''>because</span>
  <span m=''4402510''>you''re</span> <span m=''4402630''>thinking</span> <span m=''4402940''>of</span>
  <span m=''4403040''>a</span> <span m=''4403120''>procedure</span> <span m=''4403560''>which</span>
  <span m=''4403740''>goes</span> <span m=''4403940''>off</span> <span m=''4404110''>and</span>
  <span m=''4404780''>does</span> <span m=''4404980''>something.</span> </p><p><span
  m=''4406600''>Now,</span> <span m=''4406940''>in</span> <span m=''4407090''>some</span>
  <span m=''4407280''>sense</span> <span m=''4407480''>you''re</span> <span m=''4407640''>asking</span>
  <span m=''4407930''>me</span> <span m=''4408030''>the</span> <span m=''4408110''>same</span>
  <span m=''4408360''>question.</span> <span m=''4410410''>But</span> <span m=''4410660''>it''s</span>
  <span m=''4410820''>really</span> <span m=''4411180''>bothering</span> <span m=''4411680''>you,</span>
  <span m=''4412000''>and</span> <span m=''4412150''>it''s</span> <span m=''4412280''>bothering</span>
  <span m=''4412650''>you</span> <span m=''4412750''>for a</span> <span m=''4412940''>really</span>
  <span m=''4413190''>good</span> <span m=''4413370''>reason.</span> <span m=''4414140''>Because</span>
  <span m=''4414970''>when</span> <span m=''4415100''>I</span> <span m=''4415140''>write</span>
  <span m=''4415430''>that,</span> <span m=''4415740''>you''re</span> <span m=''4415830''>saying</span>
  <span m=''4416130''>gee,</span> <span m=''4416300''>this</span> <span m=''4416490''>is,</span>
  <span m=''4416990''>I</span> <span m=''4417150''>know,</span> <span m=''4417380''>sort</span>
  <span m=''4417590''>of</span> <span m=''4417700''>a</span> <span m=''4417760''>procedure.</span>
  <span m=''4418300''>But</span> <span m=''4418580''>it''s</span> <span m=''4418720''>not</span>
  <span m=''4418930''>a</span> <span m=''4418990''>procedure</span> <span m=''4419420''>that''s</span>
  <span m=''4419690''>just</span> <span m=''4419900''>running.</span> <span m=''4420250''>It''s</span>
  <span m=''4420380''>just</span> <span m=''4420530''>sort</span> <span m=''4420690''>of</span>
  <span m=''4420780''>a</span> <span m=''4420840''>procedure</span> <span m=''4421280''>sitting</span>
  <span m=''4421600''>there.</span> <span m=''4422600''>And</span> <span m=''4422750''>how</span>
  <span m=''4422930''>can</span> <span m=''4423090''>it</span> <span m=''4423210''>be</span>
  <span m=''4423740''>that</span> <span m=''4424010''>sometimes</span> <span m=''4424560''>this</span>
  <span m=''4424720''>procedure</span> <span m=''4425130''>has</span> <span m=''4425570''>37</span>
  <span m=''4425820''>and</span> <span m=''4425950''>49,</span> <span m=''4426960''>and</span>
  <span m=''4427120''>there</span> <span m=''4427190''>might</span> <span m=''4427360''>be</span>
  <span m=''4427470''>another</span> <span m=''4427810''>one</span> <span m=''4427990''>which</span>
  <span m=''4428180''>has</span> <span m=''4428910''>5</span> <span m=''4429190''>and</span>
  <span m=''4429280''>6</span> <span m=''4429540''>in</span> <span m=''4429610''>there,</span>
  <span m=''4429740''>and</span> <span m=''4429800''>why</span> <span m=''4429960''>don''t</span>
  <span m=''4430130''>they</span> <span m=''4430230''>get</span> <span m=''4430420''>confused?</span>
  </p><p><span m=''4432630''>So</span> <span m=''4433880''>there''s</span> <span m=''4434060''>something</span>
  <span m=''4434340''>very,</span> <span m=''4434650''>very</span> <span m=''4434960''>important</span>
  <span m=''4435470''>that''s</span> <span m=''4435910''>bothering</span> <span m=''4436350''>you.</span>
  <span m=''4438990''>And</span> <span m=''4439140''>it''s</span> <span m=''4439280''>really</span>
  <span m=''4439550''>crucial</span> <span m=''4439910''>to</span> <span m=''4439970''>what''s</span>
  <span m=''4440200''>going</span> <span m=''4440470''>on.</span> <span m=''4441380''>We''re</span>
  <span m=''4441510''>suddenly</span> <span m=''4442200''>saying</span> <span m=''4442540''>that</span>
  <span m=''4442690''>procedures</span> <span m=''4443320''>are</span> <span m=''4443460''>not</span>
  <span m=''4443810''>just</span> <span m=''4445680''>the</span> <span m=''4445870''>act</span>
  <span m=''4446280''>of</span> <span m=''4446390''>doing</span> <span m=''4446660''>something.</span>
  <span m=''4448290''>Procedures</span> <span m=''4448840''>are</span> <span m=''4449000''>conceptual</span>
  <span m=''4449680''>entities,</span> <span m=''4450640''>objects,</span> <span m=''4451940''>and</span>
  <span m=''4452120''>if</span> <span m=''4452230''>I</span> <span m=''4452310''>built</span>
  <span m=''4453450''>cons</span> <span m=''4453780''>of</span> <span m=''4453860''>37</span>
  <span m=''4454350''>and</span> <span m=''4454480''>49,</span> <span m=''4454910''>that''s</span>
  <span m=''4455160''>a</span> <span m=''4455220''>particular</span> <span m=''4455670''>procedure</span>
  <span m=''4456080''>that</span> <span m=''4456260''>sits</span> <span m=''4456490''>there.</span>
  <span m=''4458070''>And</span> <span m=''4458250''>it''s</span> <span m=''4458450''>different</span>
  <span m=''4459090''>from</span> <span m=''4459970''>cons</span> <span m=''4460350''>of</span>
  <span m=''4460450''>3</span> <span m=''4460710''>and</span> <span m=''4460850''>4.</span>
  <span m=''4461490''>That''s</span> <span m=''4461700''>another</span> <span m=''4462020''>procedure</span>
  <span m=''4462390''>that</span> <span m=''4462570''>sits</span> <span m=''4462800''>there.</span>
  </p><p><span m=''4463020''>AUDIENCE: Both of them exist</span> <span m=''4463270''>independently.</span>
  </p><p><span m=''4464060''>PROFESSOR: And</span> <span m=''4464330''>exists</span>
  <span m=''4464730''>independently.</span> </p><p><span m=''4465610''>AUDIENCE: And
  they</span> <span m=''4465850''>both</span> <span m=''4466160''>can be</span> <span
  m=''4466410''>referenced</span> <span m=''4466810''>by</span> <span m=''4467340''>car</span>
  <span m=''4467670''>and cdr.</span> </p><p><span m=''4468370''>PROFESSOR: And</span>
  <span m=''4468530''>they</span> <span m=''4468650''>both</span> <span m=''4468940''>would</span>
  <span m=''4469090''>be</span> <span m=''4469220''>referenced</span> <span m=''4469600''>by</span>
  <span m=''4469720''>car</span> <span m=''4470080''>and cdr.</span> <span m=''4470350''>Just</span>
  <span m=''4470600''>like</span> <span m=''4470820''>I</span> <span m=''4470940''>could</span>
  <span m=''4474170''>increment</span> <span m=''4474740''>this,</span> <span m=''4475290''>and</span>
  <span m=''4475400''>I</span> <span m=''4475500''>could</span> <span m=''4475640''>increment</span>
  <span m=''4477320''>that.</span> <span m=''4478270''>They''re</span> <span m=''4478550''>objects.</span>
  <span m=''4479960''>And</span> <span m=''4480180''>that''s</span> <span m=''4480770''>sort</span>
  <span m=''4480910''>of</span> <span m=''4481050''>where</span> <span m=''4481200''>we''re</span>
  <span m=''4481370''>going.</span> <span m=''4481730''>See,</span> <span m=''4481900''>the</span>
  <span m=''4482000''>fact</span> <span m=''4482190''>that</span> <span m=''4482380''>you''re</span>
  <span m=''4482550''>asking</span> <span m=''4482830''>the</span> <span m=''4482910''>question</span>
  <span m=''4483280''>shows</span> <span m=''4483520''>that</span> <span m=''4483660''>you''re</span>
  <span m=''4483800''>really</span> <span m=''4484030''>starting</span> <span m=''4484550''>to</span>
  <span m=''4485140''>think</span> <span m=''4485330''>about</span> <span m=''4485490''>the</span>
  <span m=''4485660''>implications</span> <span m=''4486330''>of</span> <span m=''4486990''>what''s</span>
  <span m=''4487220''>going</span> <span m=''4487460''>on.</span> <span m=''4487790''>It''s</span>
  <span m=''4487980''>the</span> <span m=''4488060''>difference</span> <span m=''4488530''>between</span>
  <span m=''4488950''>saying</span> <span m=''4489790''>a</span> <span m=''4489920''>procedure</span>
  <span m=''4490410''>is</span> <span m=''4490500''>just</span> <span m=''4490700''>the</span>
  <span m=''4490820''>act</span> <span m=''4491160''>of</span> <span m=''4491240''>doing</span>
  <span m=''4491500''>something.</span> <span m=''4493070''>And a</span> <span m=''4493150''>procedure</span>
  <span m=''4493610''>is</span> <span m=''4493700''>a</span> <span m=''4493800''>real</span>
  <span m=''4494220''>object</span> <span m=''4494720''>that</span> <span m=''4494850''>has</span>
  <span m=''4495090''>existence.</span> </p><p><span m=''4496270''>AUDIENCE: So</span>
  <span m=''4496400''>when</span> <span m=''4496660''>the</span> <span m=''4497520''>procedure</span>
  <span m=''4497860''>gets</span> <span m=''4498205''>built, the</span> <span m=''4498550''>actual</span>
  <span m=''4498990''>values</span> <span m=''4499410''>are</span> <span m=''4499815''>now</span>
  <span m=''4500220''>substituted</span> <span m=''4500640''>for a</span> <span m=''4500870''>and
  b--</span> </p><p><span m=''4501930''>PROFESSOR: That''s right.</span> </p><p><span
  m=''4502050''>AUDIENCE: And then that</span> <span m=''4502430''>procedure</span>
  <span m=''4502520''>exists</span> <span m=''4502750''>as</span> <span m=''4504080''>lambda,</span>
  <span m=''4504870''>and</span> <span m=''4505110''>pick is</span> <span m=''4505350''>what''s
  actually</span> <span m=''4505824''>passed in.</span> </p><p><span m=''4507720''>PROFESSOR:
  Yes,</span> <span m=''4507980''>when</span> <span m=''4508920''>cons</span> <span
  m=''4509290''>gets</span> <span m=''4509530''>called,</span> <span m=''4509950''>and</span>
  <span m=''4510080''>the</span> <span m=''4510160''>result</span> <span m=''4510640''>of</span>
  <span m=''4510780''>cons</span> <span m=''4511850''>is</span> <span m=''4512000''>a</span>
  <span m=''4512060''>new</span> <span m=''4512240''>procedure</span> <span m=''4512720''>that''s</span>
  <span m=''4512940''>constructed,</span> <span m=''4513530''>that</span> <span m=''4514110''>new</span>
  <span m=''4514260''>procedure</span> <span m=''4514680''>has</span> <span m=''4514830''>an</span>
  <span m=''4514900''>argument</span> <span m=''4515330''>that''s</span> <span m=''4515500''>called</span>
  <span m=''4515750''>pick.</span> </p><p><span m=''4517440''>AUDIENCE: But</span>
  <span m=''4517640''>it no</span> <span m=''4517780''>longer</span> <span m=''4518030''>has</span>
  <span m=''4518300''>an a and</span> <span m=''4518565''>b.</span> <span m=''4518830''>The</span>
  <span m=''4519220''>a and b</span> <span m=''4519610''>are the actual</span> <span
  m=''4520013''>values</span> <span m=''4520416''>that are passed through.</span>
  </p><p><span m=''4520820''>PROFESSOR: And</span> <span m=''4521080''>it</span> <span
  m=''4521240''>has--</span> <span m=''4521640''>right,</span> <span m=''4522180''>according</span>
  <span m=''4522500''>to</span> <span m=''4522590''>the</span> <span m=''4522650''>substitution</span>
  <span m=''4523280''>model,</span> <span m=''4523530''>what</span> <span m=''4523670''>it</span>
  <span m=''4523780''>now</span> <span m=''4523970''>has</span> <span m=''4524260''>is</span>
  <span m=''4524390''>not</span> <span m=''4524560''>those</span> <span m=''4524740''>arbitrary</span>
  <span m=''4524880''>names</span> <span m=''4525370''>a</span> <span m=''4525470''>and
  b,</span> <span m=''4526340''>it</span> <span m=''4526500''>somehow</span> <span
  m=''4526890''>has</span> <span m=''4527110''>that</span> <span m=''4527250''>37</span>
  <span m=''4527820''>and</span> <span m=''4527940''>49</span> <span m=''4528740''>in
  there.</span> <span m=''4531560''>But</span> <span m=''4531730''>you''re</span>
  <span m=''4531890''>right,</span> <span m=''4532090''>that''s</span> <span m=''4532260''>a</span>
  <span m=''4532310''>hard</span> <span m=''4532690''>thing</span> <span m=''4532860''>to</span>
  <span m=''4532930''>think</span> <span m=''4533140''>about</span> <span m=''4533390''>it,</span>
  <span m=''4533520''>and it''s</span> <span m=''4533610''>different</span> <span
  m=''4534020''>from</span> <span m=''4534120''>the</span> <span m=''4534230''>way</span>
  <span m=''4534370''>you''ve been</span> <span m=''4534620''>thinking</span> <span
  m=''4534930''>about</span> <span m=''4535150''>procedures.</span> </p><p><span m=''4536500''>AUDIENCE:
  And if I</span> <span m=''4537310''>have</span> <span m=''4537660''>again</span>
  <span m=''4538010''>cons of</span> <span m=''4538360''>37 and</span> <span m=''4538510''>49,</span>
  <span m=''4538975''>it''s a different</span> <span m=''4540370''>object?</span>
  </p><p><span m=''4541300''>PROFESSOR: And</span> <span m=''4541420''>if</span> <span
  m=''4541520''>you</span> <span m=''4541670''>make</span> <span m=''4545510''>another</span>
  <span m=''4546290''>cons</span> <span m=''4546720''>of</span> <span m=''4546840''>37</span>
  <span m=''4547380''>and</span> <span m=''4547500''>49,</span> <span m=''4551790''>you''re</span>
  <span m=''4551910''>into</span> <span m=''4552200''>a</span> <span m=''4552600''>wonderful</span>
  <span m=''4553100''>philosophical</span> <span m=''4553790''>problem,</span> <span
  m=''4554220''>which</span> <span m=''4554390''>is</span> <span m=''4554520''>going</span>
  <span m=''4554630''>to</span> <span m=''4554730''>be</span> <span m=''4554840''>what</span>
  <span m=''4555570''>the</span> <span m=''4555710''>lecture</span> <span m=''4557190''>about</span>
  <span m=''4557430''>halfway</span> <span m=''4557730''>through</span> <span m=''4557870''>this</span>
  <span m=''4558030''>course</span> <span m=''4558310''>is</span> <span m=''4558410''>about.</span>
  <span m=''4560080''>Which</span> <span m=''4560320''>is,</span> <span m=''4560490''>if</span>
  <span m=''4560620''>I cons</span> <span m=''4561060''>37</span> <span m=''4561570''>and</span>
  <span m=''4561680''>49,</span> <span m=''4562230''>and</span> <span m=''4562350''>I</span>
  <span m=''4562440''>do</span> <span m=''4562600''>it</span> <span m=''4562680''>again,</span>
  <span m=''4563340''>is</span> <span m=''4563510''>that</span> <span m=''4563720''>the</span>
  <span m=''4563810''>same</span> <span m=''4564170''>thing,</span> <span m=''4564730''>or</span>
  <span m=''4564850''>is</span> <span m=''4564940''>it</span> <span m=''4565030''>a</span>
  <span m=''4565090''>different</span> <span m=''4565460''>thing?</span> <span m=''4566490''>And</span>
  <span m=''4566650''>how</span> <span m=''4566830''>could</span> <span m=''4567020''>you</span>
  <span m=''4567120''>tell?</span> <span m=''4567680''>And</span> <span m=''4567860''>when</span>
  <span m=''4568020''>could</span> <span m=''4568170''>it</span> <span m=''4568260''>possibly</span>
  <span m=''4568730''>matter?</span> </p><p><span m=''4570240''>And</span> <span m=''4570400''>that''s</span>
  <span m=''4574680''>sort</span> <span m=''4574840''>of</span> <span m=''4574930''>like</span>
  <span m=''4575130''>saying,</span> <span m=''4575480''>is</span> <span m=''4577710''>that</span>
  <span m=''4578030''>the</span> <span m=''4578110''>same</span> <span m=''4578420''>thing</span>
  <span m=''4578720''>as</span> <span m=''4579420''>this?</span> <span m=''4581140''>Or</span>
  <span m=''4581320''>is</span> <span m=''4581490''>this</span> <span m=''4581710''>the</span>
  <span m=''4581790''>same</span> <span m=''4582070''>thing</span> <span m=''4582280''>as</span>
  <span m=''4582430''>that?</span> <span m=''4583850''>It''s</span> <span m=''4584010''>the</span>
  <span m=''4584080''>same</span> <span m=''4584340''>kind</span> <span m=''4584550''>of</span>
  <span m=''4584750''>question.</span> <span m=''4585150''>And</span> <span m=''4585280''>that''s</span>
  <span m=''4585410''>a</span> <span m=''4585470''>very,</span> <span m=''4586610''>very</span>
  <span m=''4587230''>deep</span> <span m=''4587460''>question.</span> <span m=''4587930''>And</span>
  <span m=''4588130''>I</span> <span m=''4588180''>can''t</span> <span m=''4588450''>answer</span>
  <span m=''4588780''>in</span> <span m=''4588890''>less</span> <span m=''4589080''>than</span>
  <span m=''4589210''>an</span> <span m=''4589330''>hour.</span> <span m=''4590180''>But</span>
  <span m=''4590320''>we</span> <span m=''4590520''>will.</span> </p>'
type: course
uid: de38c275d043c9a135daa1024edec34b

---
None