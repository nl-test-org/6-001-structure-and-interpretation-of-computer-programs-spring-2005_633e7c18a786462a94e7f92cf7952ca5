---
about_this_resource_text: <p><b>Topics covered:</b> Pattern Matching and Rule-based
  Substitution</p> <p><b> Instructors:</b> Hal Abelson and Gerald Jay Sussman</p>
  <p>Subtitles for this course are provided through the generous assistance of Henry
  Baker, Hoofar Pourzand, Heather Wood, Aleksejs Truhans, Steven Edwards, George Menhorn,
  and Mahendra Kumar.</p>
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
embedded_media:
- id: 4A.jpg
  parent_uid: e621477bd0a9ffda4f1bc6c1525285ab
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/4a-pattern-matching-and-rule-based-substitution/4A.jpg
  title: 4A.jpg
  type: null
  uid: 6a12c1495ef0810e6deabf42ac68e89d
- id: Video-YouTube-Stream
  media_location: _fXQ1SwKjDg
  parent_uid: e621477bd0a9ffda4f1bc6c1525285ab
  title: Video-YouTube-Stream
  type: Video
  uid: ebabeb174b053dc9c16ee4ce759848f8
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT_Structure_of_Computer_Programs_1986/lec4a.mp4
  parent_uid: e621477bd0a9ffda4f1bc6c1525285ab
  title: Video-Internet Archive-MP4
  type: Video
  uid: 6a5dbe523a1ea768ef2701e4fd961288
- id: Thumbnail-OCW-JPG
  parent_uid: e621477bd0a9ffda4f1bc6c1525285ab
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 19d8cf79465325fe3fb4e37d8ab4b277
- id: 3Play-3PlayYouTubeid-MP4
  media_location: _fXQ1SwKjDg
  parent_uid: e621477bd0a9ffda4f1bc6c1525285ab
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: f8d2407fe1d4c206e4925b5617603705
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/_fXQ1SwKjDg/default.jpg
  parent_uid: e621477bd0a9ffda4f1bc6c1525285ab
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 760a83daf1c1eab2eb90a2c3bbdf1d05
- id: fXQ1SwKjDg.srt
  parent_uid: e621477bd0a9ffda4f1bc6c1525285ab
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/4a-pattern-matching-and-rule-based-substitution/fXQ1SwKjDg.srt
  title: 3play caption file
  type: null
  uid: dfb529469bceb38c13864429ded139d4
- id: fXQ1SwKjDg.pdf
  parent_uid: e621477bd0a9ffda4f1bc6c1525285ab
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/4a-pattern-matching-and-rule-based-substitution/fXQ1SwKjDg.pdf
  title: 3play pdf file
  type: null
  uid: 6ac1de7c1a6862dab0992e7d2e45a766
- id: Caption-3Play YouTube id-SRT
  parent_uid: e621477bd0a9ffda4f1bc6c1525285ab
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 7cd415393ef39ffeaf84444b19c0cee9
- id: Transcript-3Play YouTube id-PDF
  parent_uid: e621477bd0a9ffda4f1bc6c1525285ab
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 233310e623e7fbde99f8477c4875630d
inline_embed_id: 145818354a:patternmatchingandrule-basedsubstitution46392229
layout: video
order_index: null
parent_uid: 4fcacad2c29981dd668a6b29822403cc
related_resources_text: ''
short_url: 4a-pattern-matching-and-rule-based-substitution
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/4a-pattern-matching-and-rule-based-substitution
template_type: Tabbed
title: '4A: Pattern Matching and Rule-based Substitution'
transcript: '<p><span m=''24460''>PROFESSOR: Well,</span> <span m=''25860''>yesterday</span>
  <span m=''26720''>we</span> <span m=''27190''>learned</span> <span m=''27410''>a</span>
  <span m=''27440''>bit</span> <span m=''27560''>about</span> <span m=''27830''>symbolic</span>
  <span m=''28270''>manipulation,</span> <span m=''29492''>and</span> <span m=''32210''>we</span>
  <span m=''32340''>wrote</span> <span m=''32590''>a</span> <span m=''33520''>rather</span>
  <span m=''33820''>stylized</span> <span m=''34540''>program</span> <span m=''35040''>to</span>
  <span m=''35140''>implement</span> <span m=''36260''>a</span> <span m=''36380''>pile</span>
  <span m=''36760''>of</span> <span m=''37220''>calculus</span> <span m=''37720''>rule</span>
  <span m=''37920''>from the</span> <span m=''38120''>calculus</span> <span m=''38660''>book.</span>
  <span m=''40620''>Here</span> <span m=''40910''>on</span> <span m=''41050''>the</span>
  <span m=''43650''>transparencies,</span> <span m=''45090''>we</span> <span m=''45270''>see</span>
  <span m=''45870''>a</span> <span m=''46010''>bunch</span> <span m=''46230''>of</span>
  <span m=''46320''>calculus</span> <span m=''46850''>rules</span> <span m=''47790''>from</span>
  <span m=''48040''>such</span> <span m=''48240''>a</span> <span m=''48280''>book.</span>
  <span m=''49470''>And,</span> <span m=''49580''>of</span> <span m=''49780''>course,</span>
  <span m=''50240''>what</span> <span m=''50360''>we</span> <span m=''50470''>did
  is sort of</span> <span m=''50890''>translate</span> <span m=''51520''>these</span>
  <span m=''51760''>rules</span> <span m=''53030''>into</span> <span m=''53270''>the</span>
  <span m=''53350''>language</span> <span m=''53810''>of</span> <span m=''53880''>the</span>
  <span m=''53970''>computer.</span> <span m=''56040''>But,</span> <span m=''56290''>of</span>
  <span m=''56440''>course,</span> <span m=''56590''>that''s</span> <span m=''56700''>a
  sort</span> <span m=''56810''>of</span> <span m=''57090''>funny</span> <span m=''57370''>strategy.</span>
  <span m=''59340''>Why</span> <span m=''59730''>should</span> <span m=''59940''>we</span>
  <span m=''60100''>have</span> <span m=''60430''>to</span> <span m=''62300''>translate</span>
  <span m=''62860''>these</span> <span m=''63040''>rules</span> <span m=''63370''>into</span>
  <span m=''63480''>the</span> <span m=''63570''>language</span> <span m=''63920''>of</span>
  <span m=''63980''>the</span> <span m=''64050''>computer?</span> <span m=''64989''>And</span>
  <span m=''65110''>what</span> <span m=''65209''>do I</span> <span m=''65310''>really</span>
  <span m=''65610''>mean</span> <span m=''65850''>by</span> <span m=''66010''>that?</span>
  </p><p><span m=''67320''>These are--the</span> <span m=''67480''>program</span>
  <span m=''67840''>we</span> <span m=''67980''>wrote</span> <span m=''68170''>yesterday</span>
  <span m=''69470''>was</span> <span m=''69710''>very</span> <span m=''69960''>stylized.</span>
  <span m=''71240''>It</span> <span m=''71330''>was</span> <span m=''71420''>a</span>
  <span m=''71520''>conditional,</span> <span m=''72920''>a</span> <span m=''73050''>dispatch</span>
  <span m=''74520''>on</span> <span m=''74660''>the</span> <span m=''74750''>type</span>
  <span m=''75020''>of</span> <span m=''75110''>the</span> <span m=''75210''>expression</span>
  <span m=''76450''>as</span> <span m=''76690''>observed</span> <span m=''77510''>by</span>
  <span m=''77830''>the</span> <span m=''77970''>rules.</span> <span m=''79660''>What
  we</span> <span m=''79920''>see</span> <span m=''80100''>here</span> <span m=''80590''>are</span>
  <span m=''80870''>rules</span> <span m=''81100''>that</span> <span m=''81240''>say</span>
  <span m=''81750''>if</span> <span m=''81940''>the</span> <span m=''82560''>object</span>
  <span m=''83010''>being</span> <span m=''83450''>the</span> <span m=''83660''>derivative</span>
  <span m=''84600''>is</span> <span m=''84740''>being</span> <span m=''84920''>taken</span>
  <span m=''85260''>of,</span> <span m=''85580''>if</span> <span m=''85700''>that</span>
  <span m=''85830''>expression</span> <span m=''86630''>is</span> <span m=''86770''>a</span>
  <span m=''86850''>constant,</span> <span m=''88450''>then</span> <span m=''88610''>do</span>
  <span m=''88790''>one</span> <span m=''89060''>thing.</span> <span m=''89350''>If</span>
  <span m=''89550''>it''s</span> <span m=''89680''>a</span> <span m=''89730''>variable,</span>
  <span m=''90300''>do</span> <span m=''90460''>another</span> <span m=''90720''>thing.</span>
  <span m=''91590''>If</span> <span m=''91820''>it''s</span> <span m=''92020''>a</span>
  <span m=''92140''>product</span> <span m=''92570''>of</span> <span m=''92640''>a</span>
  <span m=''92690''>constant</span> <span m=''93100''>times</span> <span m=''93300''>a</span>
  <span m=''93400''>variable,</span> <span m=''93890''>do</span> <span m=''94040''>something</span>
  <span m=''94750''>and</span> <span m=''94940''>so</span> <span m=''95210''>on.</span>
  <span m=''96220''>There''s sort</span> <span m=''96520''>of a</span> <span m=''96630''>dispatch</span>
  <span m=''97290''>there</span> <span m=''98180''>on a</span> <span m=''98360''>type.</span>
  </p><p><span m=''101750''>Well,</span> <span m=''102330''>since</span> <span m=''102680''>it</span>
  <span m=''102780''>has such</span> <span m=''102950''>a</span> <span m=''103010''>stylized</span>
  <span m=''103720''>behavior</span> <span m=''103990''>and</span> <span m=''104260''>structure,</span>
  <span m=''105900''>is</span> <span m=''106050''>there</span> <span m=''106160''>some</span>
  <span m=''106390''>other</span> <span m=''106570''>way</span> <span m=''106780''>of</span>
  <span m=''106890''>writing</span> <span m=''107170''>this</span> <span m=''107340''>program</span>
  <span m=''108110''>that''s</span> <span m=''108410''>more</span> <span m=''108650''>clear?</span>
  <span m=''110401''>Well,</span> <span m=''110800''>what''s</span> <span m=''111010''>a</span>
  <span m=''111220''>rule,</span> <span m=''111770''>first</span> <span m=''112060''>of</span>
  <span m=''112170''>all?</span> <span m=''112280''>What</span> <span m=''112490''>are</span>
  <span m=''112680''>these</span> <span m=''112950''>rules?</span> </p><p><span m=''115960''>Let''s</span>
  <span m=''116180''>think</span> <span m=''116350''>about</span> <span m=''116660''>that.</span>
  <span m=''117130''>Rules</span> <span m=''117410''>have</span> <span m=''117690''>parts.</span>
  <span m=''118910''>If</span> <span m=''119040''>you</span> <span m=''119200''>look</span>
  <span m=''119330''>at</span> <span m=''119470''>these</span> <span m=''119680''>rules</span>
  <span m=''121600''>in</span> <span m=''121750''>detail,</span> <span m=''123650''>what</span>
  <span m=''123800''>you</span> <span m=''123970''>see,</span> <span m=''124210''>for</span>
  <span m=''124400''>example,</span> <span m=''125090''>is</span> <span m=''125290''>the</span>
  <span m=''125390''>rule</span> <span m=''125770''>has</span> <span m=''126710''>a</span>
  <span m=''126870''>left-hand</span> <span m=''127450''>side</span> <span m=''128479''>and</span>
  <span m=''128680''>a</span> <span m=''128750''>right-hand</span> <span m=''129250''>side.</span>
  <span m=''130940''>Each</span> <span m=''131160''>of</span> <span m=''131290''>these</span>
  <span m=''131420''>rules</span> <span m=''131910''>has a</span> <span m=''132090''>left-hand</span>
  <span m=''132550''>side</span> <span m=''132960''>and</span> <span m=''133130''>the</span>
  <span m=''133220''>right-hand</span> <span m=''133670''>side.</span> <span m=''134960''>The</span>
  <span m=''135290''>left-hand</span> <span m=''135740''>side</span> <span m=''135970''>is</span>
  <span m=''136100''>somehow</span> <span m=''136480''>compared</span> <span m=''137030''>with</span>
  <span m=''137140''>the</span> <span m=''137270''>expression</span> <span m=''138640''>you''re</span>
  <span m=''138790''>trying</span> <span m=''139100''>to</span> <span m=''139170''>take</span>
  <span m=''139380''>the</span> <span m=''139440''>derivative</span> <span m=''139890''>of.</span>
  <span m=''141250''>The</span> <span m=''141670''>right-hand</span> <span m=''142140''>side</span>
  <span m=''143020''>is</span> <span m=''143240''>the</span> <span m=''143340''>replacement</span>
  <span m=''144060''>for</span> <span m=''144180''>that</span> <span m=''144440''>expression.</span>
  <span m=''148410''>So</span> <span m=''148730''>all</span> <span m=''149030''>rules</span>
  <span m=''149410''>on</span> <span m=''149610''>this</span> <span m=''149820''>page</span>
  <span m=''151700''>are</span> <span m=''151880''>something</span> <span m=''152320''>like</span>
  <span m=''152570''>this.</span> </p><p><span m=''155900''>I</span> <span m=''156380''>have</span>
  <span m=''156860''>patterns,</span> <span m=''161440''>and</span> <span m=''161850''>somehow,</span>
  <span m=''163040''>I</span> <span m=''163180''>have</span> <span m=''163420''>to</span>
  <span m=''164900''>produce,</span> <span m=''165650''>given</span> <span m=''165910''>a</span>
  <span m=''165990''>pattern,</span> <span m=''167300''>a</span> <span m=''167420''>skeleton.</span>
  <span m=''171700''>This</span> <span m=''172100''>is</span> <span m=''172190''>a</span>
  <span m=''172280''>rule.</span> <span m=''175420''>A</span> <span m=''175560''>pattern</span>
  <span m=''175930''>is</span> <span m=''176030''>something</span> <span m=''176390''>that</span>
  <span m=''176560''>matches,</span> <span m=''177900''>and</span> <span m=''178070''>a</span>
  <span m=''178110''>skeleton</span> <span m=''178500''>is</span> <span m=''178650''>something</span>
  <span m=''178930''>you</span> <span m=''179040''>substitute</span> <span m=''179530''>into</span>
  <span m=''180750''>in order to</span> <span m=''181150''>get</span> <span m=''182230''>a</span>
  <span m=''182320''>new</span> <span m=''182470''>expression.</span> <span m=''186410''>So</span>
  <span m=''186950''>what</span> <span m=''187110''>that</span> <span m=''187350''>means</span>
  <span m=''188060''>is</span> <span m=''188240''>that</span> <span m=''188410''>the</span>
  <span m=''188660''>pattern</span> <span m=''189280''>is</span> <span m=''189480''>matched</span>
  <span m=''192060''>against</span> <span m=''192830''>the</span> <span m=''192960''>expression,</span>
  <span m=''194560''>which is the</span> <span m=''195260''>source</span> <span m=''195570''>expression.</span>
  <span m=''203730''>And</span> <span m=''203960''>the</span> <span m=''204060''>result</span>
  <span m=''204740''>of</span> <span m=''204970''>the</span> <span m=''205140''>application</span>
  <span m=''205760''>of</span> <span m=''205840''>the</span> <span m=''205920''>rule</span>
  <span m=''206290''>is</span> <span m=''206470''>to</span> <span m=''206620''>produce</span>
  <span m=''207380''>a</span> <span m=''207550''>new</span> <span m=''207750''>expression,</span>
  <span m=''213470''>which</span> <span m=''213840''>I''ll</span> <span m=''214050''>call
  a</span> <span m=''214320''>target,</span> <span m=''217380''>by</span> <span m=''218070''>instantiation</span>
  <span m=''219220''>of</span> <span m=''219280''>a</span> <span m=''219350''>skeleton.</span>
  <span m=''221620''>That''s called</span> <span m=''222015''>instantiation.</span>
  <span m=''230580''>So</span> <span m=''230900''>that</span> <span m=''231110''>is</span>
  <span m=''231220''>the</span> <span m=''231540''>process</span> <span m=''232200''>by</span>
  <span m=''232330''>which</span> <span m=''232530''>these</span> <span m=''232760''>rules</span>
  <span m=''233680''>are</span> <span m=''233910''>described.</span> </p><p><span
  m=''235780''>What</span> <span m=''235950''>I''d</span> <span m=''236110''>like</span>
  <span m=''236350''>to</span> <span m=''236440''>do</span> <span m=''236610''>today</span>
  <span m=''238750''>is</span> <span m=''239790''>build</span> <span m=''240310''>a</span>
  <span m=''240410''>language</span> <span m=''242210''>and</span> <span m=''242300''>a</span>
  <span m=''242400''>means</span> <span m=''242680''>of</span> <span m=''242760''>interpreting</span>
  <span m=''243300''>that</span> <span m=''243500''>language,</span> <span m=''243870''>a</span>
  <span m=''243900''>means of</span> <span m=''244220''>executing</span> <span m=''244760''>that</span>
  <span m=''244950''>language,</span> <span m=''245670''>where that</span> <span m=''246010''>language</span>
  <span m=''246330''>allows</span> <span m=''246650''>us</span> <span m=''246750''>to</span>
  <span m=''246870''>directly</span> <span m=''247380''>express</span> <span m=''247770''>these</span>
  <span m=''247980''>rules.</span> <span m=''250550''>And</span> <span m=''250820''>what</span>
  <span m=''250940''>we''re</span> <span m=''251040''>going</span> <span m=''251120''>to</span>
  <span m=''251210''>do</span> <span m=''251420''>is</span> <span m=''251560''>instead</span>
  <span m=''252000''>of</span> <span m=''252670''>bringing</span> <span m=''253420''>the</span>
  <span m=''253700''>rules</span> <span m=''254150''>to</span> <span m=''254250''>the</span>
  <span m=''254310''>level</span> <span m=''254660''>of</span> <span m=''254740''>the</span>
  <span m=''254810''>computer</span> <span m=''255390''>by</span> <span m=''255540''>writing</span>
  <span m=''255810''>a</span> <span m=''255870''>program</span> <span m=''256500''>that</span>
  <span m=''256730''>is</span> <span m=''256920''>those</span> <span m=''257149''>rules</span>
  <span m=''258390''>in</span> <span m=''258500''>the</span> <span m=''258570''>computer''s</span>
  <span m=''258980''>language--</span> <span m=''260279''>at</span> <span m=''260500''>the</span>
  <span m=''260570''>moment,</span> <span m=''260910''>in</span> <span m=''261140''>a</span>
  <span m=''261220''>Lisp--</span> <span m=''262170''>we''re</span> <span m=''262370''>going</span>
  <span m=''262590''>to</span> <span m=''262700''>bring</span> <span m=''262930''>the</span>
  <span m=''263040''>computer</span> <span m=''263450''>to</span> <span m=''263570''>the</span>
  <span m=''263640''>level</span> <span m=''264010''>of</span> <span m=''264130''>us</span>
  <span m=''265560''>by</span> <span m=''265740''>writing</span> <span m=''265940''>a
  way</span> <span m=''266800''>by</span> <span m=''266960''>which</span> <span m=''267190''>the</span>
  <span m=''267270''>computer</span> <span m=''267560''>can</span> <span m=''267670''>understand</span>
  <span m=''268120''>rules</span> <span m=''268400''>of</span> <span m=''268510''>this</span>
  <span m=''268610''>sort.</span> </p><p><span m=''270670''>This</span> <span m=''271010''>is</span>
  <span m=''271130''>slightly</span> <span m=''271490''>emphasizing</span> <span m=''272330''>the</span>
  <span m=''272550''>idea</span> <span m=''273250''>that</span> <span m=''273640''>we</span>
  <span m=''273740''>had</span> <span m=''273930''>last</span> <span m=''274280''>time</span>
  <span m=''275210''>that</span> <span m=''275510''>we''re</span> <span m=''275650''>trying</span>
  <span m=''275890''>to</span> <span m=''275960''>make</span> <span m=''276100''>a</span>
  <span m=''276160''>solution</span> <span m=''276840''>to</span> <span m=''276950''>a</span>
  <span m=''277070''>class</span> <span m=''277440''>of</span> <span m=''277560''>problems</span>
  <span m=''278010''>rather</span> <span m=''278280''>than</span> <span m=''278410''>a</span>
  <span m=''278470''>particular</span> <span m=''278910''>one.</span> <span m=''279630''>The</span>
  <span m=''279940''>problem</span> <span m=''280390''>is</span> <span m=''280520''>if</span>
  <span m=''280640''>I</span> <span m=''280730''>want</span> <span m=''281040''>to</span>
  <span m=''281770''>write</span> <span m=''282330''>rules</span> <span m=''282640''>for
  a</span> <span m=''282860''>different</span> <span m=''285740''>piece</span> <span
  m=''285950''>of</span> <span m=''286010''>mathematics,</span> <span m=''288210''>say,</span>
  <span m=''288680''>to</span> <span m=''289160''>simple</span> <span m=''289490''>algebraic</span>
  <span m=''289990''>simplification</span> <span m=''290480''>or</span> <span m=''290570''>something</span>
  <span m=''290850''>like</span> <span m=''291090''>that,</span> <span m=''291920''>or</span>
  <span m=''292050''>manipulation</span> <span m=''292790''>of</span> <span m=''294050''>trigonometric</span>
  <span m=''294920''>functions,</span> <span m=''296120''>I would</span> <span m=''296270''>have</span>
  <span m=''296460''>to</span> <span m=''296640''>write</span> <span m=''297030''>a</span>
  <span m=''297160''>different</span> <span m=''297530''>program</span> <span m=''299850''>in</span>
  <span m=''300050''>using</span> <span m=''300310''>yesterday''s</span> <span m=''300800''>method.</span>
  <span m=''301130''>Whereas</span> <span m=''301440''>I</span> <span m=''301540''>would</span>
  <span m=''301650''>like</span> <span m=''301860''>to</span> <span m=''302180''>encapsulate</span>
  <span m=''302890''>all of</span> <span m=''303210''>the</span> <span m=''303310''>things</span>
  <span m=''303550''>that</span> <span m=''303660''>are</span> <span m=''303720''>common</span>
  <span m=''304100''>to</span> <span m=''304200''>both</span> <span m=''304490''>of</span>
  <span m=''304560''>those</span> <span m=''304790''>programs,</span> <span m=''306080''>meaning</span>
  <span m=''306520''>the</span> <span m=''306770''>idea</span> <span m=''307100''>of</span>
  <span m=''307230''>matching,</span> <span m=''307900''>instantiation,</span> <span
  m=''309020''>the</span> <span m=''309390''>control</span> <span m=''309870''>structure,</span>
  <span m=''310210''>which</span> <span m=''310460''>turns out</span> <span m=''310620''>to</span>
  <span m=''310740''>be</span> <span m=''310870''>very</span> <span m=''311110''>complicated</span>
  <span m=''311690''>for</span> <span m=''311800''>such</span> <span m=''312030''>a</span>
  <span m=''312090''>thing,</span> <span m=''313800''>I''d like to</span> <span m=''314060''>encapsulate</span>
  <span m=''314820''>that</span> <span m=''316100''>separately</span> <span m=''316760''>from</span>
  <span m=''317040''>the</span> <span m=''317130''>rules</span> <span m=''317420''>themselves.</span>
  </p><p><span m=''320010''>So</span> <span m=''320180''>let''s</span> <span m=''320410''>look</span>
  <span m=''320660''>at,</span> <span m=''320920''>first</span> <span m=''321180''>of</span>
  <span m=''321260''>all,</span> <span m=''321690''>a</span> <span m=''321800''>representation.</span>
  <span m=''322730''>I''d</span> <span m=''322850''>like</span> <span m=''323050''>to
  use</span> <span m=''323160''>the</span> <span m=''323290''>overhead</span> <span
  m=''323670''>here.</span> <span m=''324670''>I''d</span> <span m=''324870''>like--</span>
  <span m=''325070''>there</span> <span m=''325300''>it is.</span> <span m=''325975''>I''d</span>
  <span m=''326280''>like</span> <span m=''326460''>to</span> <span m=''326590''>look
  at</span> <span m=''326810''>a</span> <span m=''326880''>representation</span> <span
  m=''328510''>of</span> <span m=''328900''>the</span> <span m=''329070''>rules</span>
  <span m=''329360''>of</span> <span m=''329440''>calculus</span> <span m=''331140''>for</span>
  <span m=''331690''>derivatives</span> <span m=''333660''>in</span> <span m=''333870''>a</span>
  <span m=''333930''>sort</span> <span m=''334130''>of</span> <span m=''334570''>simple</span>
  <span m=''334970''>language</span> <span m=''335640''>that</span> <span m=''336010''>I''m</span>
  <span m=''336360''>writing</span> <span m=''336670''>right</span> <span m=''336880''>here.</span>
  <span m=''338140''>Now,</span> <span m=''338380''>I''m</span> <span m=''338490''>going</span>
  <span m=''338690''>to avoid--I''m going to</span> <span m=''338820''>avoid</span>
  <span m=''341420''>worrying</span> <span m=''341840''>about</span> <span m=''342670''>syntax.</span>
  <span m=''344250''>We</span> <span m=''344390''>can</span> <span m=''344690''>easily</span>
  <span m=''344860''>pretty</span> <span m=''345190''>this,</span> <span m=''346602''>and</span>
  <span m=''347100''>I''m</span> <span m=''347330''>not</span> <span m=''347530''>interested</span>
  <span m=''347910''>in</span> <span m=''348010''>making--</span> <span m=''348340''>this
  is</span> <span m=''348640''>indeed</span> <span m=''348860''>ugly.</span> <span
  m=''349230''>This</span> <span m=''349380''>doesn''t</span> <span m=''349630''>look</span>
  <span m=''349910''>like</span> <span m=''350290''>the</span> <span m=''350460''>beautiful</span>
  <span m=''351320''>text</span> <span m=''351660''>set</span> <span m=''352790''>dx</span>
  <span m=''353840''>by</span> <span m=''354350''>dt</span> <span m=''354720''>or</span>
  <span m=''354810''>something</span> <span m=''355160''>that</span> <span m=''355510''>I''d</span>
  <span m=''355740''>like</span> <span m=''355960''>to</span> <span m=''356080''>write,</span>
  <span m=''356730''>but</span> <span m=''356990''>that''s</span> <span m=''357290''>not</span>
  <span m=''357540''>essential.</span> <span m=''358710''>That''s sort of</span> <span
  m=''359090''>an</span> <span m=''359260''>accidental</span> <span m=''359890''>phenomenon.</span>
  </p><p><span m=''360480''>Here,</span> <span m=''360920''>we''re just</span> <span
  m=''361390''>worrying</span> <span m=''361640''>about</span> <span m=''361810''>the</span>
  <span m=''361980''>fact</span> <span m=''362620''>that</span> <span m=''363140''>the</span>
  <span m=''363220''>structure</span> <span m=''363790''>of</span> <span m=''363870''>the</span>
  <span m=''363970''>rules</span> <span m=''364790''>is</span> <span m=''365000''>that</span>
  <span m=''365150''>there</span> <span m=''365390''>is</span> <span m=''365530''>a</span>
  <span m=''366140''>left-hand</span> <span m=''366720''>side</span> <span m=''367060''>here,</span>
  <span m=''367740''>represents</span> <span m=''368620''>the</span> <span m=''368940''>thing</span>
  <span m=''369160''>I</span> <span m=''369240''>want</span> <span m=''369370''>to</span>
  <span m=''369500''>match</span> <span m=''369960''>against</span> <span m=''370230''>the</span>
  <span m=''370510''>derivative</span> <span m=''370910''>expression.</span> <span
  m=''371720''>This</span> <span m=''372090''>is</span> <span m=''372230''>the</span>
  <span m=''372300''>representation</span> <span m=''373040''>I''m going to</span>
  <span m=''373190''>say</span> <span m=''373490''>for</span> <span m=''373900''>the</span>
  <span m=''374140''>derivative</span> <span m=''374800''>of</span> <span m=''375970''>a</span>
  <span m=''376290''>constant,</span> <span m=''376980''>which</span> <span m=''377130''>we</span>
  <span m=''377270''>will</span> <span m=''377430''>call</span> <span m=''377740''>c</span>
  <span m=''378830''>with</span> <span m=''378980''>respect</span> <span m=''379400''>to</span>
  <span m=''379490''>the</span> <span m=''379620''>variable</span> <span m=''380210''>we
  will</span> <span m=''380480''>call</span> <span m=''380810''>v.</span> <span m=''383100''>And</span>
  <span m=''383360''>what</span> <span m=''383530''>we will</span> <span m=''383730''>get</span>
  <span m=''383920''>on</span> <span m=''384040''>the</span> <span m=''384160''>right-hand</span>
  <span m=''384650''>side</span> <span m=''384930''>is</span> <span m=''385040''>0.</span>
  <span m=''386010''>So</span> <span m=''386270''>this</span> <span m=''386560''>represents</span>
  <span m=''387340''>a</span> <span m=''387490''>rule.</span> </p><p><span m=''389620''>The</span>
  <span m=''389800''>next</span> <span m=''389990''>rule</span> <span m=''390270''>will</span>
  <span m=''390400''>be</span> <span m=''390810''>the</span> <span m=''390940''>derivative</span>
  <span m=''391530''>of</span> <span m=''391740''>a</span> <span m=''391820''>variable,</span>
  <span m=''392980''>which</span> <span m=''393140''>we</span> <span m=''393270''>will</span>
  <span m=''393400''>call</span> <span m=''393670''>v</span> <span m=''394170''>with</span>
  <span m=''394350''>respect</span> <span m=''394880''>to</span> <span m=''395020''>the</span>
  <span m=''395140''>same</span> <span m=''395490''>variable</span> <span m=''396010''>v,</span>
  <span m=''396860''>and</span> <span m=''396970''>we</span> <span m=''397090''>get</span>
  <span m=''397230''>a</span> <span m=''397290''>1.</span> <span m=''398560''>However,</span>
  <span m=''399280''>if</span> <span m=''399450''>we</span> <span m=''399550''>have</span>
  <span m=''399730''>the</span> <span m=''399820''>derivative</span> <span m=''400220''>of</span>
  <span m=''400350''>a</span> <span m=''400390''>variable</span> <span m=''401360''>called</span>
  <span m=''401640''>u</span> <span m=''402390''>with</span> <span m=''402540''>respect</span>
  <span m=''403050''>to</span> <span m=''403490''>a</span> <span m=''403620''>different</span>
  <span m=''403990''>variables</span> <span m=''404490''>v,</span> <span m=''405380''>we</span>
  <span m=''405640''>will</span> <span m=''406370''>get</span> <span m=''406610''>0.</span>
  <span m=''407790''>I just</span> <span m=''407990''>want</span> <span m=''408170''>you</span>
  <span m=''408300''>look</span> <span m=''408440''>at</span> <span m=''408590''>these</span>
  <span m=''408800''>rules</span> <span m=''409110''>a</span> <span m=''409160''>little</span>
  <span m=''409420''>bit</span> <span m=''410270''>and</span> <span m=''410610''>see</span>
  <span m=''410770''>how</span> <span m=''410880''>they</span> <span m=''411280''>fit</span>
  <span m=''411640''>together.</span> <span m=''412750''>For</span> <span m=''413040''>example,</span>
  <span m=''413540''>over</span> <span m=''413800''>here,</span> <span m=''414670''>we''re</span>
  <span m=''414830''>going</span> <span m=''414920''>to</span> <span m=''415010''>have</span>
  <span m=''415290''>the</span> <span m=''415400''>derivative</span> <span m=''416310''>of</span>
  <span m=''416600''>the</span> <span m=''416710''>sum</span> <span m=''417690''>of</span>
  <span m=''418060''>an</span> <span m=''418160''>expression</span> <span m=''418610''>called</span>
  <span m=''418890''>x1</span> <span m=''419980''>and</span> <span m=''420240''>an</span>
  <span m=''420360''>expression</span> <span m=''420880''>called</span> <span m=''421160''>x2.</span>
  <span m=''421790''>These</span> <span m=''422360''>things</span> <span m=''422610''>that</span>
  <span m=''422750''>begin</span> <span m=''423100''>with</span> <span m=''423300''>question</span>
  <span m=''423730''>marks</span> <span m=''424300''>are</span> <span m=''424590''>called</span>
  <span m=''424960''>pattern</span> <span m=''425340''>variables</span> <span m=''426860''>in</span>
  <span m=''427110''>the</span> <span m=''427210''>language</span> <span m=''427740''>that</span>
  <span m=''427910''>we''re</span> <span m=''428010''>inventing,</span> <span m=''428910''>and</span>
  <span m=''429040''>you</span> <span m=''429250''>see we''re just</span> <span m=''429500''>making</span>
  <span m=''429980''>it</span> <span m=''430070''>up,</span> <span m=''430990''>so</span>
  <span m=''431450''>pattern</span> <span m=''431830''>variables</span> <span m=''432820''>for</span>
  <span m=''434090''>matching.</span> </p><p><span m=''434960''>And</span> <span m=''435170''>so
  in this--</span> <span m=''436050''>here we</span> <span m=''436240''>have</span>
  <span m=''436440''>the</span> <span m=''436540''>derivative</span> <span m=''437010''>of</span>
  <span m=''437180''>the</span> <span m=''437280''>sum</span> <span m=''437920''>of</span>
  <span m=''438380''>the</span> <span m=''438670''>expression</span> <span m=''439140''>which</span>
  <span m=''439280''>we</span> <span m=''439390''>will</span> <span m=''439520''>call</span>
  <span m=''439830''>x1.</span> <span m=''440380''>And</span> <span m=''440510''>the</span>
  <span m=''440640''>expression</span> <span m=''441100''>we</span> <span m=''441200''>will</span>
  <span m=''441330''>call</span> <span m=''441580''>x2</span> <span m=''442370''>with</span>
  <span m=''442520''>respect</span> <span m=''442960''>to</span> <span m=''443040''>the</span>
  <span m=''443150''>variable</span> <span m=''443510''>we</span> <span m=''443660''>call</span>
  <span m=''444000''>v</span> <span m=''444590''>will</span> <span m=''444870''>be--</span>
  <span m=''445170''>here</span> <span m=''445370''>is</span> <span m=''445450''>the</span>
  <span m=''445560''>right-hand</span> <span m=''446070''>side:</span> <span m=''446500''>the</span>
  <span m=''446780''>sum</span> <span m=''447160''>of</span> <span m=''447390''>the</span>
  <span m=''447500''>derivative</span> <span m=''448290''>of</span> <span m=''448510''>that</span>
  <span m=''448690''>expression</span> <span m=''449150''>x1</span> <span m=''449560''>with</span>
  <span m=''449700''>respect</span> <span m=''450080''>to</span> <span m=''450170''>v--</span>
  <span m=''450520''>the</span> <span m=''451020''>right-hand</span> <span m=''451500''>side</span>
  <span m=''451830''>is</span> <span m=''451930''>the</span> <span m=''452020''>skeleton--</span>
  <span m=''453910''>and</span> <span m=''454150''>the</span> <span m=''454230''>derivative</span>
  <span m=''455175''>of</span> <span m=''455470''>x2</span> <span m=''456000''>with</span>
  <span m=''456160''>respect</span> <span m=''456560''>to</span> <span m=''456700''>v.</span>
  <span m=''457590''>Colons</span> <span m=''458180''>here</span> <span m=''458710''>will</span>
  <span m=''458950''>stand</span> <span m=''459330''>for</span> <span m=''460960''>substitution</span>
  <span m=''461800''>objects.</span> <span m=''464690''>They''re--we''ll call them</span>
  <span m=''465820''>skeleton</span> <span m=''466280''>evaluations.</span> </p><p><span
  m=''468480''>So</span> <span m=''468730''>let</span> <span m=''468850''>me</span>
  <span m=''468950''>put</span> <span m=''469120''>up</span> <span m=''469280''>here</span>
  <span m=''469540''>on</span> <span m=''469710''>the</span> <span m=''469780''>blackboard</span>
  <span m=''470350''>for a</span> <span m=''470530''>second</span> <span m=''471940''>some</span>
  <span m=''472420''>syntax</span> <span m=''473200''>so</span> <span m=''473330''>we''ll</span>
  <span m=''473470''>know</span> <span m=''473600''>what''s</span> <span m=''473790''>going</span>
  <span m=''474060''>on</span> <span m=''474380''>for</span> <span m=''474670''>this</span>
  <span m=''474840''>rule</span> <span m=''475090''>language.</span> <span m=''476620''>First</span>
  <span m=''476950''>of</span> <span m=''477050''>all,</span> <span m=''477550''>we''re</span>
  <span m=''477700''>going</span> <span m=''477770''>to</span> <span m=''477850''>have</span>
  <span m=''478010''>to</span> <span m=''478180''>worry</span> <span m=''478360''>about</span>
  <span m=''478540''>the</span> <span m=''478730''>pattern</span> <span m=''479090''>matching.</span>
  <span m=''485790''>We''re</span> <span m=''486180''>going</span> <span m=''486410''>to</span>
  <span m=''486470''>have</span> <span m=''486690''>things</span> <span m=''487010''>like</span>
  <span m=''489420''>a</span> <span m=''489590''>symbol</span> <span m=''490000''>like</span>
  <span m=''490310''>foo</span> <span m=''491520''>matches</span> <span m=''491950''>exactly</span>
  <span m=''492560''>itself.</span> <span m=''503170''>The</span> <span m=''504840''>expression</span>
  <span m=''506000''>f</span> <span m=''506970''>of</span> <span m=''507310''>a</span>
  <span m=''507710''>and</span> <span m=''508120''>b</span> <span m=''509500''>will</span>
  <span m=''509720''>be</span> <span m=''509860''>used</span> <span m=''510200''>to</span>
  <span m=''510300''>match</span> <span m=''510630''>any</span> <span m=''510880''>list</span>
  <span m=''515919''>whose</span> <span m=''517919''>first</span> <span m=''520200''>element</span>
  <span m=''522860''>is</span> <span m=''523659''>f,</span> <span m=''525340''>whose</span>
  <span m=''525760''>second</span> <span m=''526300''>element</span> <span m=''529110''>is</span>
  <span m=''529870''>a,</span> <span m=''530740''>and</span> <span m=''531130''>whose</span>
  <span m=''531540''>third</span> <span m=''533600''>element</span> <span m=''534620''>is</span>
  <span m=''536520''>b.</span> </p><p><span m=''538550''>Also,</span> <span m=''539650''>another</span>
  <span m=''539990''>thing</span> <span m=''540310''>we might</span> <span m=''540430''>have</span>
  <span m=''540700''>in</span> <span m=''540810''>a</span> <span m=''540870''>pattern</span>
  <span m=''542070''>is</span> <span m=''542360''>that--</span> <span m=''543200''>a</span>
  <span m=''543340''>question</span> <span m=''543870''>mark</span> <span m=''545590''>with</span>
  <span m=''545810''>some</span> <span m=''546000''>variable</span> <span m=''546430''>like</span>
  <span m=''546780''>x.</span> <span m=''548150''>And</span> <span m=''548730''>what</span>
  <span m=''548850''>that</span> <span m=''549090''>means,</span> <span m=''550150''>it</span>
  <span m=''550310''>says</span> <span m=''550880''>matches</span> <span m=''551360''>anything,</span>
  <span m=''557690''>which</span> <span m=''557840''>we will</span> <span m=''558090''>call</span>
  <span m=''558420''>x.</span> <span m=''565610''>Question</span> <span m=''566060''>mark</span>
  <span m=''566770''>c</span> <span m=''567660''>x</span> <span m=''568480''>will</span>
  <span m=''568670''>match</span> <span m=''568990''>only</span> <span m=''569270''>constants.</span>
  <span m=''570922''>So</span> <span m=''571370''>this</span> <span m=''571690''>is</span>
  <span m=''571830''>something</span> <span m=''572170''>which</span> <span m=''572340''>matches</span>
  <span m=''572640''>a</span> <span m=''572750''>constant</span> <span m=''580160''>colon</span>
  <span m=''580650''>x.</span> <span m=''584620''>And</span> <span m=''584940''>question</span>
  <span m=''585360''>mark</span> <span m=''586490''>v</span> <span m=''587310''>x</span>
  <span m=''588070''>will</span> <span m=''588510''>match</span> <span m=''588830''>a</span>
  <span m=''588900''>variable,</span> <span m=''595920''>which</span> <span m=''596280''>we
  call</span> <span m=''596760''>x.</span> </p><p><span m=''601690''>This</span> <span
  m=''602040''>is sort of</span> <span m=''602150''>the</span> <span m=''602260''>language</span>
  <span m=''602740''>we''re</span> <span m=''602900''>making</span> <span m=''603230''>up</span>
  <span m=''603440''>now.</span> <span m=''604140''>If</span> <span m=''604320''>I</span>
  <span m=''604440''>match</span> <span m=''604820''>two</span> <span m=''605070''>things</span>
  <span m=''605730''>against</span> <span m=''606150''>each</span> <span m=''606350''>other,</span>
  <span m=''606720''>then</span> <span m=''606960''>they</span> <span m=''607090''>are</span>
  <span m=''607240''>compared</span> <span m=''608310''>element</span> <span m=''608730''>by</span>
  <span m=''608900''>element.</span> <span m=''610200''>But</span> <span m=''610470''>elements</span>
  <span m=''610890''>in</span> <span m=''611000''>the</span> <span m=''611090''>pattern</span>
  <span m=''611670''>may</span> <span m=''611930''>contain</span> <span m=''612610''>these</span>
  <span m=''612950''>syntactic</span> <span m=''613630''>variables,</span> <span m=''614780''>pattern</span>
  <span m=''615150''>variables,</span> <span m=''617110''>which</span> <span m=''617310''>will</span>
  <span m=''617430''>be</span> <span m=''617550''>used</span> <span m=''618080''>to</span>
  <span m=''618870''>match</span> <span m=''619310''>arbitrary</span> <span m=''619880''>objects.</span>
  <span m=''622160''>And</span> <span m=''622330''>we''ll</span> <span m=''622450''>get</span>
  <span m=''622680''>that</span> <span m=''623300''>object</span> <span m=''624010''>as</span>
  <span m=''624240''>the</span> <span m=''624350''>value</span> <span m=''626810''>in</span>
  <span m=''626980''>the</span> <span m=''627080''>name</span> <span m=''627670''>x</span>
  <span m=''628320''>here,</span> <span m=''628480''>for</span> <span m=''628670''>example.</span>
  </p><p><span m=''631030''>Now,</span> <span m=''631280''>when we</span> <span m=''631400''>make</span>
  <span m=''631590''>skeletons</span> <span m=''636130''>for</span> <span m=''636680''>instantiation.</span>
  <span m=''639290''>Well,</span> <span m=''639630''>then</span> <span m=''639800''>we</span>
  <span m=''639960''>have</span> <span m=''640440''>things</span> <span m=''640850''>like</span>
  <span m=''641110''>this.</span> <span m=''642320''>foo,</span> <span m=''643890''>a</span>
  <span m=''644090''>symbol,</span> <span m=''645010''>instantiates</span> <span m=''645720''>to</span>
  <span m=''645840''>itself.</span> <span m=''655020''>Something</span> <span m=''655580''>which</span>
  <span m=''655790''>is</span> <span m=''655910''>a</span> <span m=''656060''>list</span>
  <span m=''656470''>like</span> <span m=''656890''>f</span> <span m=''657530''>of</span>
  <span m=''657830''>a</span> <span m=''658080''>and</span> <span m=''658300''>b,</span>
  <span m=''659630''>instantiates</span> <span m=''665160''>to--</span> <span m=''666350''>well,</span>
  <span m=''666620''>f</span> <span m=''666960''>instantiates</span> <span m=''667530''>to</span>
  <span m=''671050''>a</span> <span m=''671250''>3-list,</span> <span m=''673650''>a</span>
  <span m=''673920''>list of</span> <span m=''674050''>three</span> <span m=''674270''>elements,
  okay,</span> <span m=''676240''>which</span> <span m=''676560''>are</span> <span
  m=''676680''>the</span> <span m=''676810''>results</span> <span m=''680035''>of</span>
  <span m=''680510''>instantiating</span> <span m=''687160''>each</span> <span m=''687420''>of</span>
  <span m=''691490''>f,</span> <span m=''692440''>a,</span> <span m=''692710''>and</span>
  <span m=''692970''>b.</span> <span m=''696310''>And</span> <span m=''699040''>x</span>
  <span m=''700080''>well--we</span> <span m=''700490''>instantiate</span> <span m=''705790''>to</span>
  <span m=''706090''>the</span> <span m=''706210''>value</span> <span m=''711326''>of</span>
  <span m=''711820''>x</span> <span m=''713060''>as</span> <span m=''713310''>in</span>
  <span m=''713390''>the</span> <span m=''713470''>matched</span> <span m=''713780''>pattern.</span>
  </p><p><span m=''722960''>So</span> <span m=''723240''>going</span> <span m=''723540''>back</span>
  <span m=''723800''>to</span> <span m=''723900''>the</span> <span m=''724030''>overhead</span>
  <span m=''724560''>here,</span> <span m=''725820''>we</span> <span m=''726130''>see--we
  see</span> <span m=''727690''>that</span> <span m=''728480''>all</span> <span m=''728630''>of</span>
  <span m=''728790''>those</span> <span m=''729080''>kinds</span> <span m=''729440''>of</span>
  <span m=''729540''>objects,</span> <span m=''730740''>we</span> <span m=''731000''>see</span>
  <span m=''731240''>here</span> <span m=''731960''>a</span> <span m=''732290''>pattern</span>
  <span m=''732840''>variable</span> <span m=''734040''>which</span> <span m=''734220''>matches</span>
  <span m=''735060''>a</span> <span m=''735190''>constant,</span> <span m=''736530''>a</span>
  <span m=''736640''>pattern</span> <span m=''737110''>variable</span> <span m=''737440''>which</span>
  <span m=''737680''>matches</span> <span m=''738180''>a</span> <span m=''738260''>variable,</span>
  <span m=''739410''>a</span> <span m=''739570''>pattern</span> <span m=''739930''>variable</span>
  <span m=''740300''>which</span> <span m=''740500''>will</span> <span m=''740660''>match</span>
  <span m=''741010''>anything.</span> <span m=''742660''>And</span> <span m=''742870''>if</span>
  <span m=''742960''>we</span> <span m=''743080''>have</span> <span m=''743280''>two</span>
  <span m=''743490''>instances</span> <span m=''743950''>of</span> <span m=''744050''>the</span>
  <span m=''744170''>same</span> <span m=''744460''>name,</span> <span m=''745080''>like</span>
  <span m=''745320''>this</span> <span m=''745510''>is</span> <span m=''745810''>the</span>
  <span m=''746050''>derivative</span> <span m=''746610''>of</span> <span m=''746870''>the</span>
  <span m=''748530''>expression</span> <span m=''749090''>which</span> <span m=''749280''>is</span>
  <span m=''749390''>a</span> <span m=''749450''>variable</span> <span m=''749840''>only</span>
  <span m=''750510''>whose</span> <span m=''750720''>name</span> <span m=''750950''>will</span>
  <span m=''751070''>be</span> <span m=''751200''>v</span> <span m=''752880''>with</span>
  <span m=''753020''>respect</span> <span m=''753480''>to</span> <span m=''753580''>some</span>
  <span m=''753860''>arbitrary</span> <span m=''754510''>expression</span> <span m=''755300''>which
  we</span> <span m=''755490''>will</span> <span m=''755710''>call</span> <span m=''756000''>v,</span>
  <span m=''756390''>since</span> <span m=''756660''>this</span> <span m=''756870''>v</span>
  <span m=''757110''>appears</span> <span m=''757510''>twice,</span> <span m=''758560''>we''re</span>
  <span m=''758810''>going</span> <span m=''758910''>to</span> <span m=''759020''>want</span>
  <span m=''759330''>that</span> <span m=''759570''>to mean</span> <span m=''759820''>they</span>
  <span m=''759940''>have</span> <span m=''760100''>to</span> <span m=''760270''>be</span>
  <span m=''760400''>the</span> <span m=''760510''>same.</span> </p><p><span m=''762770''>The</span>
  <span m=''762910''>only</span> <span m=''763150''>consistent</span> <span m=''763600''>match
  is</span> <span m=''764000''>that</span> <span m=''764120''>those</span> <span m=''764370''>are</span>
  <span m=''764410''>the</span> <span m=''764530''>same.</span> <span m=''765630''>So
  here,</span> <span m=''765710''>we''re</span> <span m=''765870''>making</span> <span
  m=''766070''>up</span> <span m=''766160''>a</span> <span m=''766210''>language.</span>
  <span m=''768170''>And</span> <span m=''768520''>in fact,</span> <span m=''769000''>that''s</span>
  <span m=''769210''>a</span> <span m=''769290''>very</span> <span m=''769530''>nice</span>
  <span m=''769830''>thing</span> <span m=''770000''>to</span> <span m=''770090''>be</span>
  <span m=''770230''>doing.</span> <span m=''770440''>It''s</span> <span m=''770570''>so</span>
  <span m=''770690''>much</span> <span m=''770910''>fun</span> <span m=''771240''>to</span>
  <span m=''771320''>make</span> <span m=''771490''>up</span> <span m=''771570''>a</span>
  <span m=''771640''>language.</span> <span m=''772555''>And</span> <span m=''772840''>you</span>
  <span m=''773090''>do</span> <span m=''773240''>this</span> <span m=''773400''>all</span>
  <span m=''773570''>the</span> <span m=''773750''>time.</span> <span m=''774320''>And</span>
  <span m=''774490''>the</span> <span m=''774580''>really</span> <span m=''774900''>most</span>
  <span m=''775130''>powerful</span> <span m=''775570''>design</span> <span m=''775970''>things</span>
  <span m=''776040''>you</span> <span m=''776300''>ever</span> <span m=''776500''>do</span>
  <span m=''777160''>are</span> <span m=''777390''>sort</span> <span m=''777520''>of</span>
  <span m=''777830''>making</span> <span m=''778230''>up</span> <span m=''778340''>a</span>
  <span m=''778400''>language</span> <span m=''778900''>to</span> <span m=''779040''>solve</span>
  <span m=''779330''>problems</span> <span m=''779730''>like</span> <span m=''779960''>this.</span>
  </p><p><span m=''782050''>Now,</span> <span m=''783430''>here we</span> <span m=''783510''>go</span>
  <span m=''783620''>back</span> <span m=''783970''>here</span> <span m=''784160''>and</span>
  <span m=''784230''>look</span> <span m=''784350''>at</span> <span m=''784480''>some</span>
  <span m=''784660''>of</span> <span m=''784810''>these</span> <span m=''784970''>rules.</span>
  <span m=''785780''>Well,</span> <span m=''785990''>there''s a</span> <span m=''786080''>whole</span>
  <span m=''786300''>set</span> <span m=''786530''>of</span> <span m=''786650''>them.</span>
  <span m=''787070''>I</span> <span m=''787140''>mean,</span> <span m=''787310''>there''s</span>
  <span m=''787870''>one for</span> <span m=''788210''>addition</span> <span m=''789300''>and</span>
  <span m=''789550''>one</span> <span m=''789780''>for</span> <span m=''790540''>multiplication,</span>
  <span m=''791310''>just</span> <span m=''791530''>like</span> <span m=''791690''>we</span>
  <span m=''791790''>had</span> <span m=''791990''>before.</span> <span m=''792390''>The</span>
  <span m=''792510''>derivative</span> <span m=''792760''>of</span> <span m=''792870''>the</span>
  <span m=''792980''>product</span> <span m=''793650''>of</span> <span m=''794250''>x1</span>
  <span m=''794530''>and</span> <span m=''794840''>x2</span> <span m=''795390''>with</span>
  <span m=''795520''>respect</span> <span m=''795950''>to</span> <span m=''796070''>v</span>
  <span m=''796900''>is</span> <span m=''797420''>the</span> <span m=''797790''>sum</span>
  <span m=''798180''>of</span> <span m=''799610''>the</span> <span m=''800030''>product</span>
  <span m=''800400''>of</span> <span m=''800510''>x1</span> <span m=''801590''>and</span>
  <span m=''801710''>the</span> <span m=''801840''>derivative</span> <span m=''802340''>x2</span>
  <span m=''802510''>with</span> <span m=''802660''>respect to</span> <span m=''803145''>v</span>
  <span m=''803930''>and</span> <span m=''804070''>the</span> <span m=''804150''>product</span>
  <span m=''804510''>of</span> <span m=''804690''>the</span> <span m=''804750''>derivative
  of</span> <span m=''805170''>x1</span> <span m=''805660''>and</span> <span m=''805840''>x2.</span>
  <span m=''807200''>And</span> <span m=''807340''>here</span> <span m=''807480''>we</span>
  <span m=''807630''>have</span> <span m=''807980''>exponentiation.</span> <span m=''809180''>And,</span>
  <span m=''809310''>of</span> <span m=''809400''>course,</span> <span m=''809590''>we</span>
  <span m=''809700''>run</span> <span m=''809840''>off</span> <span m=''810040''>the</span>
  <span m=''810220''>end</span> <span m=''810400''>down</span> <span m=''810660''>here.</span>
  <span m=''810880''>We</span> <span m=''810980''>get</span> <span m=''811100''>as</span>
  <span m=''811330''>many</span> <span m=''811530''>as</span> <span m=''811620''>we</span>
  <span m=''811760''>like.</span> <span m=''812540''>But</span> <span m=''812830''>the</span>
  <span m=''812920''>whole</span> <span m=''813210''>thing</span> <span m=''813390''>over</span>
  <span m=''813580''>here,</span> <span m=''814000''>I''m</span> <span m=''814200''>giving</span>
  <span m=''814510''>this--this</span> <span m=''815820''>list</span> <span m=''816140''>of</span>
  <span m=''816270''>rules</span> <span m=''817570''>the</span> <span m=''817770''>name</span>
  <span m=''818260''>"derivative</span> <span m=''818710''>rules."</span> </p><p><span
  m=''820910''>What</span> <span m=''821160''>would</span> <span m=''821290''>we</span>
  <span m=''821430''>do</span> <span m=''821620''>with</span> <span m=''821790''>such</span>
  <span m=''822000''>a</span> <span m=''822070''>thing</span> <span m=''823140''>once</span>
  <span m=''823350''>we</span> <span m=''823460''>have</span> <span m=''823720''>it?</span>
  <span m=''825240''>Well,</span> <span m=''825890''>one</span> <span m=''826090''>of</span>
  <span m=''826160''>the</span> <span m=''826240''>nicest</span> <span m=''826750''>ideas,</span>
  <span m=''827140''>first</span> <span m=''827470''>of</span> <span m=''827560''>all,</span>
  <span m=''828400''>is</span> <span m=''828620''>I''m</span> <span m=''828780''>going</span>
  <span m=''828980''>to</span> <span m=''829080''>write</span> <span m=''829390''>for</span>
  <span m=''829520''>you, and</span> <span m=''829860''>we''re</span> <span m=''830000''>going</span>
  <span m=''830090''>to</span> <span m=''830180''>play</span> <span m=''830490''>with</span>
  <span m=''830690''>it</span> <span m=''830930''>all</span> <span m=''831250''>day.</span>
  <span m=''832230''>What I''m</span> <span m=''832520''>going to</span> <span m=''832580''>write</span>
  <span m=''832850''>for</span> <span m=''832970''>you</span> <span m=''833520''>is
  a</span> <span m=''835590''>program</span> <span m=''836330''>called</span> <span
  m=''836680''>simplifier,</span> <span m=''837760''>the</span> <span m=''837960''>general-purpose</span>
  <span m=''838760''>simplifier.</span> <span m=''840150''>And we''re going to</span>
  <span m=''840420''>say</span> <span m=''840630''>something</span> <span m=''841000''>like</span>
  <span m=''841250''>define</span> <span m=''845360''>dsimp</span> <span m=''848860''>to</span>
  <span m=''849150''>be</span> <span m=''849640''>a</span> <span m=''849860''>simplifier</span>
  <span m=''856080''>of</span> <span m=''856270''>the</span> <span m=''856360''>derivative</span>
  <span m=''856760''>rules.</span> <span m=''863740''>And</span> <span m=''863890''>what</span>
  <span m=''864200''>simplifier</span> <span m=''864500''>is</span> <span m=''864830''>going</span>
  <span m=''865080''>to</span> <span m=''865150''>do</span> <span m=''865490''>is,</span>
  <span m=''865730''>given</span> <span m=''865980''>a</span> <span m=''866050''>set</span>
  <span m=''866250''>of</span> <span m=''866390''>rules,</span> <span m=''867120''>it</span>
  <span m=''867220''>will</span> <span m=''867380''>produce</span> <span m=''867750''>for
  me a</span> <span m=''868050''>procedure</span> <span m=''869280''>which</span>
  <span m=''869540''>will</span> <span m=''869670''>simplify</span> <span m=''870140''>expressions</span>
  <span m=''870700''>containing</span> <span m=''871850''>the</span> <span m=''872620''>things</span>
  <span m=''873000''>that</span> <span m=''873130''>are</span> <span m=''873200''>referred</span>
  <span m=''873620''>to</span> <span m=''873780''>by</span> <span m=''873960''>these</span>
  <span m=''874190''>rules.</span> </p><p><span m=''877360''>So</span> <span m=''877510''>here
  will</span> <span m=''877780''>be</span> <span m=''877930''>a</span> <span m=''878010''>procedure</span>
  <span m=''878520''>constructed</span> <span m=''879720''>for</span> <span m=''880170''>your</span>
  <span m=''880450''>purposes</span> <span m=''882110''>to</span> <span m=''882270''>simplify</span>
  <span m=''882750''>things</span> <span m=''882990''>with</span> <span m=''883110''>derivatives</span>
  <span m=''883540''>in them</span> <span m=''884490''>such</span> <span m=''884870''>that,</span>
  <span m=''885150''>after</span> <span m=''885480''>that,</span> <span m=''886000''>if</span>
  <span m=''886100''>we''re</span> <span m=''886310''>typing</span> <span m=''886700''>at</span>
  <span m=''886820''>some</span> <span m=''887360''>list</span> <span m=''887710''>system,</span>
  <span m=''888700''>and</span> <span m=''888790''>we</span> <span m=''888890''>get</span>
  <span m=''889000''>a</span> <span m=''889050''>prompt,</span> <span m=''889880''>and</span>
  <span m=''890020''>we</span> <span m=''890150''>say</span> <span m=''890990''>dsimp,</span>
  <span m=''894220''>for</span> <span m=''894370''>example,</span> <span m=''895310''>of</span>
  <span m=''895650''>the</span> <span m=''895930''>derivative</span> <span m=''897640''>of</span>
  <span m=''898030''>the</span> <span m=''898540''>sum</span> <span m=''899466''>of</span>
  <span m=''899822''>x</span> <span m=''900490''>and</span> <span m=''900800''>y</span>
  <span m=''902680''>with</span> <span m=''902950''>respect</span> <span m=''903400''>to</span>
  <span m=''903570''>x--</span> <span m=''906990''>note</span> <span m=''907270''>the</span>
  <span m=''907360''>quote</span> <span m=''907670''>here</span> <span m=''907880''>because</span>
  <span m=''908130''>I''m</span> <span m=''908230''>talking</span> <span m=''908460''>about</span>
  <span m=''908600''>the</span> <span m=''908740''>expression</span> <span m=''909870''>which</span>
  <span m=''910090''>is</span> <span m=''910230''>the</span> <span m=''910310''>derivative--</span>
  <span m=''913310''>then</span> <span m=''913570''>I</span> <span m=''913670''>will</span>
  <span m=''913820''>get</span> <span m=''914080''>back</span> <span m=''914420''>as</span>
  <span m=''914530''>a</span> <span m=''914580''>result</span> <span m=''915500''>plus</span>
  <span m=''916610''>1</span> <span m=''917120''>0.</span> <span m=''919970''>Because</span>
  <span m=''920265''>the</span> <span m=''920560''>derivative</span> <span m=''921060''>of</span>
  <span m=''921410''>x</span> <span m=''921650''>plus</span> <span m=''921860''>y</span>
  <span m=''922480''>is</span> <span m=''922930''>the derivative</span> <span m=''923200''>of</span>
  <span m=''923630''>x plus  derivative</span> <span m=''924020''>y.</span> <span
  m=''924490''>The</span> <span m=''924800''>derivative of</span> <span m=''924890''>x
  with respect</span> <span m=''925170''>to</span> <span m=''925450''>x</span> <span
  m=''925720''>is</span> <span m=''925810''>1.</span> <span m=''926300''>The derivative
  of</span> <span m=''926600''>y</span> <span m=''926960''>with respect to x</span>
  <span m=''927360''>is</span> <span m=''927460''>0.</span> <span m=''929260''>It''s</span>
  <span m=''929460''>not</span> <span m=''929630''>what</span> <span m=''929750''>we''re</span>
  <span m=''929870''>going</span> <span m=''930000''>to</span> <span m=''930140''>get.</span>
  <span m=''931170''>I haven''t</span> <span m=''931400''>put</span> <span m=''931620''>any</span>
  <span m=''931730''>simplification</span> <span m=''932290''>at</span> <span m=''932370''>that</span>
  <span m=''932590''>level--</span> <span m=''933280''>algebraic</span> <span m=''933540''>simplification--</span>
  <span m=''934440''>yet.</span> </p><p><span m=''936010''>Of</span> <span m=''936210''>course,</span>
  <span m=''936660''>once</span> <span m=''936910''>we</span> <span m=''937070''>have</span>
  <span m=''937370''>such</span> <span m=''937590''>a</span> <span m=''937830''>thing,</span>
  <span m=''938870''>then</span> <span m=''939250''>we</span> <span m=''939410''>can--then
  we can</span> <span m=''940610''>look</span> <span m=''940730''>at</span> <span
  m=''940880''>other</span> <span m=''941120''>rules.</span> <span m=''942340''>So,</span>
  <span m=''942710''>for</span> <span m=''942900''>example,</span> <span m=''944630''>we</span>
  <span m=''944790''>can,</span> <span m=''945700''>if</span> <span m=''945890''>we</span>
  <span m=''945980''>go</span> <span m=''946160''>to</span> <span m=''946340''>the</span>
  <span m=''947440''>slide,</span> <span m=''948510''>OK?</span> <span m=''949310''>Here,</span>
  <span m=''949610''>for</span> <span m=''949810''>example,</span> <span m=''950740''>are</span>
  <span m=''950970''>other</span> <span m=''951250''>rules</span> <span m=''951590''>that</span>
  <span m=''951700''>we</span> <span m=''951820''>might</span> <span m=''952030''>have,</span>
  <span m=''952480''>algebraic</span> <span m=''953030''>manipulation</span> <span
  m=''953740''>rules,</span> <span m=''955980''>ones</span> <span m=''956200''>that</span>
  <span m=''956310''>would</span> <span m=''956410''>be</span> <span m=''956500''>used</span>
  <span m=''956670''>for</span> <span m=''956780''>simplifying</span> <span m=''957340''>algebraic</span>
  <span m=''957850''>expressions.</span> <span m=''958960''>For</span> <span m=''959240''>example,</span>
  <span m=''960750''>just</span> <span m=''960990''>looking</span> <span m=''961270''>at</span>
  <span m=''961380''>some</span> <span m=''961570''>of</span> <span m=''961680''>these,</span>
  <span m=''963270''>the</span> <span m=''963920''>left-hand</span> <span m=''964470''>side</span>
  <span m=''964670''>says</span> <span m=''964990''>any</span> <span m=''965240''>operator</span>
  <span m=''966250''>applied</span> <span m=''966710''>to</span> <span m=''966830''>a</span>
  <span m=''966950''>constant</span> <span m=''967500''>e1</span> <span m=''967970''>and</span>
  <span m=''968090''>a</span> <span m=''968220''>constant</span> <span m=''968610''>e2</span>
  <span m=''969340''>is</span> <span m=''969540''>the</span> <span m=''969650''>result</span>
  <span m=''970210''>of</span> <span m=''970900''>evaluating</span> <span m=''971540''>that</span>
  <span m=''971720''>operator</span> <span m=''972180''>on</span> <span m=''972310''>the</span>
  <span m=''972400''>constants</span> <span m=''973560''>e1</span> <span m=''973710''>and</span>
  <span m=''973900''>e2.</span> <span m=''975850''>Or</span> <span m=''976510''>an</span>
  <span m=''976730''>operator,</span> <span m=''978160''>applied</span> <span m=''978640''>to</span>
  <span m=''978990''>e1,</span> <span m=''979410''>any</span> <span m=''979680''>expression</span>
  <span m=''980130''>e1</span> <span m=''980430''>and</span> <span m=''980610''>a</span>
  <span m=''980660''>constant</span> <span m=''981030''>e2,</span> <span m=''981700''>is</span>
  <span m=''981880''>going</span> <span m=''982120''>to</span> <span m=''982240''>move</span>
  <span m=''982740''>the</span> <span m=''982940''>constant</span> <span m=''983400''>forward.</span>
  <span m=''984520''>So</span> <span m=''984710''>that''ll</span> <span m=''984890''>turn</span>
  <span m=''985090''>into</span> <span m=''985300''>the</span> <span m=''985420''>operator</span>
  <span m=''985820''>with</span> <span m=''985980''>e2</span> <span m=''986590''>followed</span>
  <span m=''986880''>by</span> <span m=''987030''>e1.</span> <span m=''988770''>Why
  I</span> <span m=''989110''>did</span> <span m=''989350''>that,</span> <span m=''989560''>I</span>
  <span m=''989740''>don''t</span> <span m=''989920''>know.</span> <span m=''990200''>It</span>
  <span m=''990350''>wouldn''t</span> <span m=''990510''>work</span> <span m=''990830''>if
  I</span> <span m=''990980''>had</span> <span m=''991060''>division,</span> <span
  m=''992500''>for</span> <span m=''992680''>example.</span> <span m=''993560''>So
  there''s a</span> <span m=''993870''>bug</span> <span m=''994190''>in</span> <span
  m=''994280''>the</span> <span m=''994370''>rules,</span> <span m=''994700''>if</span>
  <span m=''994820''>you</span> <span m=''994950''>like.</span> </p><p><span m=''996610''>So
  the</span> <span m=''996780''>sum</span> <span m=''997210''>of</span> <span m=''997820''>0</span>
  <span m=''998830''>and</span> <span m=''999160''>e</span> <span m=''1000220''>is
  e.</span> <span m=''1002120''>The</span> <span m=''1002280''>product</span> <span
  m=''1002870''>of</span> <span m=''1003130''>1</span> <span m=''1003550''>and</span>
  <span m=''1003830''>any</span> <span m=''1004130''>expression</span> <span m=''1004430''>e</span>
  <span m=''1004680''>is</span> <span m=''1004850''>e.</span> <span m=''1006110''>The</span>
  <span m=''1006280''>product</span> <span m=''1006610''>of</span> <span m=''1006710''>0</span>
  <span m=''1007220''>and</span> <span m=''1007390''>any</span> <span m=''1007580''>expression</span>
  <span m=''1008005''>e</span> <span m=''1008430''>is</span> <span m=''1008640''>0.</span>
  <span m=''1009520''>Just</span> <span m=''1009680''>looking at</span> <span m=''1009830''>some</span>
  <span m=''1009970''>more</span> <span m=''1010210''>of</span> <span m=''1010360''>these</span>
  <span m=''1010500''>rules,</span> <span m=''1010750''>we could</span> <span m=''1010940''>have</span>
  <span m=''1011130''>arbitrarily</span> <span m=''1011680''>complicated</span> <span
  m=''1012260''>ones.</span> <span m=''1013670''>We could</span> <span m=''1013820''>have</span>
  <span m=''1014170''>things</span> <span m=''1014430''>like</span> <span m=''1015275''>the</span>
  <span m=''1015740''>product</span> <span m=''1016766''>of</span> <span m=''1017460''>the</span>
  <span m=''1017810''>constant</span> <span m=''1018270''>e1</span> <span m=''1018820''>and</span>
  <span m=''1019050''>any</span> <span m=''1019240''>constant</span> <span m=''1019560''>e2</span>
  <span m=''1020880''>with</span> <span m=''1021000''>e3</span> <span m=''1022330''>is</span>
  <span m=''1022660''>the</span> <span m=''1022930''>result</span> <span m=''1023440''>of</span>
  <span m=''1024060''>multiplying the result of--multiplying</span> <span m=''1027119''>now</span>
  <span m=''1027650''>the</span> <span m=''1027800''>constants</span> <span m=''1028150''>e1</span>
  <span m=''1028440''>and</span> <span m=''1028579''>e2</span> <span m=''1028750''>together</span>
  <span m=''1030310''>and</span> <span m=''1030839''>putting</span> <span m=''1031089''>e3</span>
  <span m=''1031619''>there.</span> <span m=''1033319''>So it</span> <span m=''1033530''>says</span>
  <span m=''1033790''>combine</span> <span m=''1034220''>the</span> <span m=''1034310''>constants</span>
  <span m=''1035782''>that</span> <span m=''1036170''>I</span> <span m=''1036349''>had,</span>
  <span m=''1036609''>which</span> <span m=''1036760''>was if I had</span> <span m=''1036869''>a</span>
  <span m=''1036940''>product</span> <span m=''1037510''>of</span> <span m=''1037560''>e1</span>
  <span m=''1037720''>and</span> <span m=''1038020''>e2</span> <span m=''1039160''>and</span>
  <span m=''1039540''>e3</span> <span m=''1040260''>just multiply--I mean and</span>
  <span m=''1040700''>e1</span> <span m=''1040829''>and</span> <span m=''1041119''>e2</span>
  <span m=''1041260''>are both</span> <span m=''1041510''>constants,</span> <span
  m=''1041920''>multiply</span> <span m=''1042359''>them.</span> </p><p><span m=''1043800''>And</span>
  <span m=''1043910''>you</span> <span m=''1044069''>can</span> <span m=''1044160''>make</span>
  <span m=''1044349''>up</span> <span m=''1044450''>the</span> <span m=''1044550''>rules</span>
  <span m=''1044810''>as</span> <span m=''1045020''>you</span> <span m=''1045150''>like.</span>
  <span m=''1045690''>There</span> <span m=''1045970''>are</span> <span m=''1045990''>lots</span>
  <span m=''1046329''>of</span> <span m=''1046460''>them</span> <span m=''1046599''>here.</span>
  <span m=''1047619''>There</span> <span m=''1047770''>are</span> <span m=''1047810''>things</span>
  <span m=''1048200''>as</span> <span m=''1048440''>complicated,</span> <span m=''1049070''>for</span>
  <span m=''1049240''>example,</span> <span m=''1050180''>as--</span> <span m=''1051300''>oh,</span>
  <span m=''1051450''>I</span> <span m=''1051560''>suppose</span> <span m=''1051900''>down</span>
  <span m=''1052020''>here</span> <span m=''1052210''>some</span> <span m=''1052360''>distributive</span>
  <span m=''1052880''>law,</span> <span m=''1053410''>you</span> <span m=''1053550''>see.</span>
  <span m=''1053910''>The</span> <span m=''1054120''>product</span> <span m=''1054510''>of</span>
  <span m=''1055060''>any</span> <span m=''1055370''>object</span> <span m=''1055840''>c</span>
  <span m=''1056790''>and</span> <span m=''1057000''>the</span> <span m=''1057060''>sum</span>
  <span m=''1057340''>of</span> <span m=''1057450''>d</span> <span m=''1057880''>and</span>
  <span m=''1058120''>e</span> <span m=''1059000''>gives</span> <span m=''1059150''>the</span>
  <span m=''1059260''>result</span> <span m=''1059690''>as</span> <span m=''1059750''>the</span>
  <span m=''1059820''>same</span> <span m=''1060130''>as</span> <span m=''1060230''>the</span>
  <span m=''1060340''>sum</span> <span m=''1060650''>of</span> <span m=''1060770''>the</span>
  <span m=''1060870''>product</span> <span m=''1061240''>of</span> <span m=''1061330''>c</span>
  <span m=''1061600''>and</span> <span m=''1061770''>d</span> <span m=''1062340''>and</span>
  <span m=''1062470''>the</span> <span m=''1062600''>product</span> <span m=''1063220''>of
  c and</span> <span m=''1063370''>e.</span> </p><p><span m=''1065320''>Now,</span>
  <span m=''1065500''>what</span> <span m=''1065680''>exactly</span> <span m=''1066160''>these</span>
  <span m=''1066390''>rules</span> <span m=''1066710''>are</span> <span m=''1067210''>doesn''t</span>
  <span m=''1067550''>very</span> <span m=''1067770''>much</span> <span m=''1068000''>interest</span>
  <span m=''1068330''>me.</span> <span m=''1069220''>We''re</span> <span m=''1069370''>going</span>
  <span m=''1069460''>to be</span> <span m=''1069550''>writing the</span> <span m=''1070030''>language</span>
  <span m=''1071150''>that</span> <span m=''1071330''>will</span> <span m=''1071450''>allow</span>
  <span m=''1071750''>us</span> <span m=''1071850''>to</span> <span m=''1071970''>interpret</span>
  <span m=''1072440''>these</span> <span m=''1072660''>rules</span> <span m=''1075440''>so</span>
  <span m=''1075600''>that</span> <span m=''1075710''>we</span> <span m=''1075810''>can,</span>
  <span m=''1075940''>in</span> <span m=''1076010''>fact,</span> <span m=''1076260''>make</span>
  <span m=''1076390''>up</span> <span m=''1076480''>whatever</span> <span m=''1076690''>rules</span>
  <span m=''1076940''>we</span> <span m=''1077110''>like,</span> <span m=''1078320''>another</span>
  <span m=''1078750''>whole</span> <span m=''1078980''>language of</span> <span m=''1079430''>programming.</span>
  <span m=''1083350''>Well,</span> <span m=''1083730''>let''s</span> <span m=''1084090''>see.</span>
  <span m=''1085130''>I haven''t</span> <span m=''1085430''>told</span> <span m=''1085710''>you</span>
  <span m=''1086000''>how</span> <span m=''1086260''>we''re</span> <span m=''1086370''>going</span>
  <span m=''1086460''>to</span> <span m=''1086550''>do</span> <span m=''1086720''>this.</span>
  <span m=''1087520''>And,</span> <span m=''1087640''>of</span> <span m=''1087730''>course,</span>
  <span m=''1088630''>for</span> <span m=''1088750''>a</span> <span m=''1088780''>while,</span>
  <span m=''1089110''>we''re</span> <span m=''1089210''>going</span> <span m=''1089280''>to</span>
  <span m=''1089350''>work</span> <span m=''1089570''>on</span> <span m=''1089730''>that.</span>
  <span m=''1090760''>But</span> <span m=''1091070''>there''s</span> <span m=''1091280''>a</span>
  <span m=''1091700''>real</span> <span m=''1092070''>question</span> <span m=''1092600''>of</span>
  <span m=''1092820''>what is--what</span> <span m=''1093240''>am</span> <span m=''1093340''>I</span>
  <span m=''1093430''>going</span> <span m=''1093560''>to</span> <span m=''1093680''>do</span>
  <span m=''1093980''>at</span> <span m=''1094040''>all</span> <span m=''1094380''>at</span>
  <span m=''1094460''>a</span> <span m=''1094510''>large</span> <span m=''1094900''>scale?</span>
  <span m=''1096940''>How</span> <span m=''1097230''>do</span> <span m=''1097300''>these</span>
  <span m=''1097550''>rules</span> <span m=''1097890''>work?</span> <span m=''1098930''>How</span>
  <span m=''1099170''>is</span> <span m=''1099330''>the</span> <span m=''1099430''>simplifier</span>
  <span m=''1100070''>program</span> <span m=''1100700''>going</span> <span m=''1100960''>to</span>
  <span m=''1101080''>manipulate</span> <span m=''1101620''>these</span> <span m=''1101830''>rules</span>
  <span m=''1102470''>with</span> <span m=''1102720''>your</span> <span m=''1102980''>expression</span>
  <span m=''1104240''>to</span> <span m=''1104450''>produce</span> <span m=''1104760''>a</span>
  <span m=''1104840''>reasonable</span> <span m=''1105230''>answer?</span> </p><p><span
  m=''1106190''>Well,</span> <span m=''1106340''>first,</span> <span m=''1106620''>I''d</span>
  <span m=''1106700''>like</span> <span m=''1106840''>to</span> <span m=''1106900''>think</span>
  <span m=''1107070''>about</span> <span m=''1107300''>these</span> <span m=''1107500''>rules</span>
  <span m=''1107980''>as</span> <span m=''1108180''>being</span> <span m=''1108410''>some</span>
  <span m=''1108550''>sort</span> <span m=''1108680''>of</span> <span m=''1108990''>deck</span>
  <span m=''1109360''>of</span> <span m=''1109510''>them.</span> <span m=''1112100''>So</span>
  <span m=''1112370''>here I have</span> <span m=''1112850''>a</span> <span m=''1113050''>whole</span>
  <span m=''1113440''>bunch</span> <span m=''1113660''>of</span> <span m=''1113800''>rules,</span>
  <span m=''1121030''>right?</span> <span m=''1122030''>Each</span> <span m=''1122330''>rule--</span>
  <span m=''1123660''>here''s</span> <span m=''1123880''>a</span> <span m=''1123970''>rule--</span>
  <span m=''1126930''>has</span> <span m=''1127420''>a</span> <span m=''1127560''>pattern</span>
  <span m=''1128430''>and</span> <span m=''1128590''>a</span> <span m=''1128640''>skeleton.</span>
  <span m=''1129720''>I''m</span> <span m=''1129810''>trying</span> <span m=''1129960''>to
  make up a</span> <span m=''1130120''>control</span> <span m=''1130640''>structure</span>
  <span m=''1131050''>for</span> <span m=''1131180''>this.</span> </p><p><span m=''1133410''>Now,</span>
  <span m=''1134050''>what</span> <span m=''1134230''>I</span> <span m=''1134350''>have</span>
  <span m=''1135320''>is</span> <span m=''1135840''>a</span> <span m=''1135980''>matcher,</span>
  <span m=''1140506''>and</span> <span m=''1141010''>I</span> <span m=''1141220''>have</span>
  <span m=''1141430''>something</span> <span m=''1142130''>which</span> <span m=''1142510''>is</span>
  <span m=''1142720''>an</span> <span m=''1143020''>instantiater.</span> <span m=''1149120''>And</span>
  <span m=''1149610''>I''m</span> <span m=''1149930''>going</span> <span m=''1150180''>to</span>
  <span m=''1150280''>pass</span> <span m=''1151090''>from</span> <span m=''1151300''>the</span>
  <span m=''1151440''>matcher</span> <span m=''1151820''>to</span> <span m=''1151920''>the</span>
  <span m=''1152040''>instantiater</span> <span m=''1153950''>some</span> <span m=''1154910''>set</span>
  <span m=''1155180''>of</span> <span m=''1155430''>meaning</span> <span m=''1156010''>for</span>
  <span m=''1156310''>the</span> <span m=''1156470''>pattern</span> <span m=''1156860''>variables,</span>
  <span m=''1158060''>a</span> <span m=''1158200''>dictionary,</span> <span m=''1158770''>I''ll</span>
  <span m=''1158930''>call</span> <span m=''1159210''>it.</span> <span m=''1160560''>A</span>
  <span m=''1160690''>dictionary,</span> <span m=''1164790''>which</span> <span m=''1165080''>will</span>
  <span m=''1165250''>say</span> <span m=''1165570''>x</span> <span m=''1165890''>was</span>
  <span m=''1166080''>matched</span> <span m=''1166410''>against</span> <span m=''1166640''>the</span>
  <span m=''1166740''>following</span> <span m=''1167060''>subexpression</span> <span
  m=''1169050''>and</span> <span m=''1169290''>y</span> <span m=''1169530''>was</span>
  <span m=''1169670''>matched</span> <span m=''1169970''>against</span> <span m=''1170150''>another</span>
  <span m=''1170410''>following</span> <span m=''1170720''>subexpression.</span> <span
  m=''1172170''>And</span> <span m=''1172450''>from</span> <span m=''1172650''>the</span>
  <span m=''1172890''>instantiater,</span> <span m=''1173480''>I</span> <span m=''1173550''>will</span>
  <span m=''1173670''>be</span> <span m=''1173810''>making</span> <span m=''1174090''>expressions,</span>
  <span m=''1175040''>and</span> <span m=''1175210''>they will</span> <span m=''1175430''>go</span>
  <span m=''1175570''>into</span> <span m=''1175690''>the</span> <span m=''1175810''>matcher.</span>
  <span m=''1177130''>They will</span> <span m=''1177330''>be</span> <span m=''1177460''>expressions.</span>
  <span m=''1184960''>And</span> <span m=''1185200''>the</span> <span m=''1185270''>patterns</span>
  <span m=''1185880''>of</span> <span m=''1186100''>the</span> <span m=''1186210''>rules</span>
  <span m=''1187040''>will</span> <span m=''1187250''>be</span> <span m=''1187370''>fed</span>
  <span m=''1187560''>into</span> <span m=''1187720''>the</span> <span m=''1187820''>matcher,</span>
  <span m=''1189190''>and</span> <span m=''1189480''>the</span> <span m=''1189570''>skeletons</span>
  <span m=''1190500''>from</span> <span m=''1190770''>the</span> <span m=''1191060''>same</span>
  <span m=''1191340''>rule</span> <span m=''1191560''>will</span> <span m=''1191850''>be
  fed</span> <span m=''1192000''>into</span> <span m=''1192130''>the</span> <span
  m=''1193600''>instantiater.</span> </p><p><span m=''1195190''>Now,</span> <span
  m=''1195370''>this is</span> <span m=''1195530''>a</span> <span m=''1195610''>little</span>
  <span m=''1195850''>complicated</span> <span m=''1196940''>because</span> <span
  m=''1197680''>when</span> <span m=''1197810''>you</span> <span m=''1197920''>have</span>
  <span m=''1198120''>something</span> <span m=''1198320''>like</span> <span m=''1198490''>an</span>
  <span m=''1198560''>algebraic</span> <span m=''1199050''>expression,</span> <span
  m=''1200910''>where someth--the</span> <span m=''1201020''>rules</span> <span m=''1201320''>are</span>
  <span m=''1201400''>intended</span> <span m=''1201740''>to</span> <span m=''1201810''>be</span>
  <span m=''1202000''>able</span> <span m=''1202220''>to allow you to</span> <span
  m=''1202290''>substitute</span> <span m=''1202720''>equal</span> <span m=''1203020''>for</span>
  <span m=''1203330''>equal.</span> <span m=''1204290''>These are</span> <span m=''1204570''>equal</span>
  <span m=''1204820''>transformation</span> <span m=''1205490''>rules.</span> <span
  m=''1206860''>So</span> <span m=''1207110''>all</span> <span m=''1207380''>subexpressions</span>
  <span m=''1208110''>of the</span> <span m=''1208230''>expression</span> <span m=''1208710''>should</span>
  <span m=''1208860''>be</span> <span m=''1208980''>looked</span> <span m=''1209200''>at.</span>
  <span m=''1211090''>You</span> <span m=''1211220''>give</span> <span m=''1211380''>it</span>
  <span m=''1211450''>an</span> <span m=''1211560''>expression,</span> <span m=''1212340''>this</span>
  <span m=''1212610''>thing,</span> <span m=''1213150''>and</span> <span m=''1213400''>the</span>
  <span m=''1213510''>rules</span> <span m=''1214440''>should</span> <span m=''1214620''>be</span>
  <span m=''1214800''>cycled</span> <span m=''1215230''>around.</span> </p><p><span
  m=''1216010''>First</span> <span m=''1216270''>of all,</span> <span m=''1216600''>for</span>
  <span m=''1216830''>every</span> <span m=''1217120''>subexpression</span> <span
  m=''1217760''>of</span> <span m=''1217840''>the</span> <span m=''1218540''>expression</span>
  <span m=''1218960''>you</span> <span m=''1219090''>feed</span> <span m=''1219320''>in,</span>
  <span m=''1220210''>all</span> <span m=''1220400''>of</span> <span m=''1220590''>the</span>
  <span m=''1220690''>rules</span> <span m=''1221020''>must</span> <span m=''1221240''>be</span>
  <span m=''1221340''>tried</span> <span m=''1222110''>and</span> <span m=''1222290''>looked</span>
  <span m=''1222540''>at.</span> <span m=''1224390''>And if</span> <span m=''1224510''>any</span>
  <span m=''1224740''>rule</span> <span m=''1224980''>matches,</span> <span m=''1225670''>then</span>
  <span m=''1225980''>this</span> <span m=''1226130''>process</span> <span m=''1226550''>occurs.</span>
  <span m=''1227200''>The</span> <span m=''1227470''>dictionary--the dictionary</span>
  <span m=''1229640''>is to have</span> <span m=''1229800''>some</span> <span m=''1229950''>values</span>
  <span m=''1230310''>in it.</span> <span m=''1230620''>The</span> <span m=''1230770''>instantiater</span>
  <span m=''1231030''>makes</span> <span m=''1231460''>a</span> <span m=''1231510''>new</span>
  <span m=''1232670''>expression,</span> <span m=''1233840''>which is</span> <span
  m=''1234250''>basically</span> <span m=''1234800''>replaces</span> <span m=''1235370''>that</span>
  <span m=''1235610''>part</span> <span m=''1235780''>of</span> <span m=''1235950''>the</span>
  <span m=''1236100''>expression</span> <span m=''1236720''>that</span> <span m=''1236950''>was</span>
  <span m=''1237050''>matched</span> <span m=''1237860''>in</span> <span m=''1238000''>your</span>
  <span m=''1238150''>original</span> <span m=''1238520''>expression.</span> <span
  m=''1240800''>And</span> <span m=''1241050''>then, then,</span> <span m=''1242090''>of</span>
  <span m=''1242240''>course,</span> <span m=''1242880''>we''re</span> <span m=''1243070''>going</span>
  <span m=''1243310''>to</span> <span m=''1243550''>recheck</span> <span m=''1244100''>that,</span>
  <span m=''1244700''>going to go</span> <span m=''1245090''>around</span> <span m=''1245380''>these</span>
  <span m=''1245560''>rules</span> <span m=''1245790''>again,</span> <span m=''1246440''>seeing
  if</span> <span m=''1246780''>that</span> <span m=''1246990''>could</span> <span
  m=''1247060''>be</span> <span m=''1247170''>simplified</span> <span m=''1247690''>further.</span>
  <span m=''1249520''>And</span> <span m=''1249680''>then, then</span> <span m=''1250270''>we''re
  going</span> <span m=''1250350''>to do</span> <span m=''1250470''>that</span> <span
  m=''1250670''>for</span> <span m=''1250760''>every</span> <span m=''1250960''>subexpression</span>
  <span m=''1252160''>until</span> <span m=''1252540''>the thing</span> <span m=''1252670''>no</span>
  <span m=''1252840''>longer</span> <span m=''1253170''>changes.</span> </p><p><span
  m=''1254940''>You</span> <span m=''1255060''>can</span> <span m=''1255200''>think</span>
  <span m=''1255420''>of</span> <span m=''1255500''>this</span> <span m=''1256020''>as</span>
  <span m=''1256260''>sort</span> <span m=''1256360''>of</span> <span m=''1256450''>an</span>
  <span m=''1256520''>organic</span> <span m=''1257020''>process.</span> <span m=''1257890''>You''ve</span>
  <span m=''1258040''>got</span> <span m=''1258270''>some</span> <span m=''1258420''>sort</span>
  <span m=''1258550''>of</span> <span m=''1258680''>stew,</span> <span m=''1259496''>right?</span>
  <span m=''1260190''>You''ve</span> <span m=''1260370''>got</span> <span m=''1260600''>bacteria</span>
  <span m=''1261160''>or</span> <span m=''1261290''>something,</span> <span m=''1261530''>or</span>
  <span m=''1261620''>enzymes</span> <span m=''1262820''>in</span> <span m=''1262970''>some,
  in some</span> <span m=''1263830''>gooey</span> <span m=''1264090''>mess.</span>
  <span m=''1265590''>And there''s these--and</span> <span m=''1268790''>these</span>
  <span m=''1269040''>enzymes</span> <span m=''1269720''>change</span> <span m=''1270150''>things.</span>
  <span m=''1270470''>They</span> <span m=''1270600''>attach</span> <span m=''1271030''>to</span>
  <span m=''1271170''>your</span> <span m=''1271380''>expression,</span> <span m=''1272170''>change</span>
  <span m=''1272570''>it,</span> <span m=''1273110''>and</span> <span m=''1273320''>then</span>
  <span m=''1273480''>they</span> <span m=''1273600''>go</span> <span m=''1273860''>away.</span>
  <span m=''1275300''>And</span> <span m=''1275480''>they</span> <span m=''1275500''>have</span>
  <span m=''1275660''>to</span> <span m=''1275770''>match.</span> <span m=''1276080''>The</span>
  <span m=''1276570''>key-in-lock</span> <span m=''1277140''>phenomenon.</span> <span
  m=''1277740''>They</span> <span m=''1278080''>match,</span> <span m=''1278470''>they</span>
  <span m=''1278650''>change</span> <span m=''1278980''>it,</span> <span m=''1279070''>they</span>
  <span m=''1279170''>go</span> <span m=''1279380''>away.</span> <span m=''1279660''>You</span>
  <span m=''1279740''>can</span> <span m=''1279840''>imagine it</span> <span m=''1280070''>as
  a</span> <span m=''1280200''>parallel</span> <span m=''1280690''>process</span>
  <span m=''1281100''>of some</span> <span m=''1281390''>sort.</span> <span m=''1282310''>So</span>
  <span m=''1282670''>you</span> <span m=''1282840''>stick an</span> <span m=''1283110''>expression</span>
  <span m=''1283600''>into</span> <span m=''1283730''>this</span> <span m=''1284570''>mess,</span>
  <span m=''1285460''>and</span> <span m=''1285820''>after</span> <span m=''1286200''>a</span>
  <span m=''1286250''>while,</span> <span m=''1286430''>you</span> <span m=''1286560''>take</span>
  <span m=''1286770''>it</span> <span m=''1286840''>out, and</span> <span m=''1287090''>it''s</span>
  <span m=''1287240''>been</span> <span m=''1287390''>simplified.</span> <span m=''1289440''>And</span>
  <span m=''1290050''>it just</span> <span m=''1290180''>keeps</span> <span m=''1290390''>changing</span>
  <span m=''1291120''>until</span> <span m=''1291480''>it</span> <span m=''1291550''>no</span>
  <span m=''1291660''>longer</span> <span m=''1292020''>can</span> <span m=''1292120''>be</span>
  <span m=''1292230''>changed.</span> <span m=''1293170''>But</span> <span m=''1293480''>these</span>
  <span m=''1293660''>enzymes</span> <span m=''1294100''>can</span> <span m=''1294220''>attach</span>
  <span m=''1294480''>to any</span> <span m=''1294680''>part</span> <span m=''1297070''>of
  the, of</span> <span m=''1297400''>the</span> <span m=''1297840''>expression.</span>
  </p><p><span m=''1299230''>OK,</span> <span m=''1301390''>at</span> <span m=''1301550''>this</span>
  <span m=''1301740''>point,</span> <span m=''1302360''>I''d</span> <span m=''1302450''>like
  to</span> <span m=''1302670''>stop</span> <span m=''1302970''>and ask  for</span>
  <span m=''1303300''>questions.</span> <span m=''1304990''>Yes.</span> </p><p><span
  m=''1305950''>AUDIENCE: This</span> <span m=''1306300''>implies</span> <span m=''1306790''>that
  the</span> <span m=''1307170''>matching</span> <span m=''1307630''>program</span>
  <span m=''1308100''>and</span> <span m=''1308240''>the</span> <span m=''1308550''>instantiation</span>
  <span m=''1309180''>program</span> <span m=''1309690''>are</span> <span m=''1309940''>separate</span>
  <span m=''1310460''>programs;</span> <span m=''1310880''>is that</span> <span m=''1311180''>right?</span>
  <span m=''1311650''>Or is that--</span> <span m=''1312090''>they</span> <span m=''1312360''>are.</span>
  </p><p><span m=''1312690''>PROFESSOR: They''re</span> <span m=''1312870''>separate</span>
  <span m=''1313130''>little</span> <span m=''1313300''>pieces.</span> <span m=''1314090''>They</span>
  <span m=''1314310''>fit</span> <span m=''1314520''>together</span> <span m=''1314920''>in</span>
  <span m=''1315150''>a</span> <span m=''1315260''>larger</span> <span m=''1315920''>structure.</span>
  </p><p><span m=''1317170''>AUDIENCE: So</span> <span m=''1317420''>I''m</span> <span
  m=''1317670''>going</span> <span m=''1317990''>through</span> <span m=''1318310''>and</span>
  <span m=''1318420''>matching</span> <span m=''1319680''>and</span> <span m=''1319970''>passing</span>
  <span m=''1320225''>the</span> <span m=''1320480''>information</span> <span m=''1321030''>about</span>
  <span m=''1321260''>what</span> <span m=''1321380''>I</span> <span m=''1321500''>matched</span>
  <span m=''1322320''>to</span> <span m=''1322660''>an</span> <span m=''1322790''>instantiater,</span>
  <span m=''1323520''>which</span> <span m=''1323730''>makes</span> <span m=''1324000''>the</span>
  <span m=''1324100''>changes.</span> <span m=''1324620''>And</span> <span m=''1324730''>then</span>
  <span m=''1324840''>I</span> <span m=''1325430''>pass</span> <span m=''1325700''>that</span>
  <span m=''1325890''>back</span> <span m=''1326150''>to the</span> <span m=''1326290''>matcher?</span>
  </p><p><span m=''1326480''>PROFESSOR: It won''t make</span> <span m=''1326680''>a</span>
  <span m=''1326730''>change.</span> <span m=''1327060''>It</span> <span m=''1327160''>will</span>
  <span m=''1327280''>make</span> <span m=''1327460''>a</span> <span m=''1327520''>new</span>
  <span m=''1327770''>expression,</span> <span m=''1329600''>which</span> <span m=''1329860''>has,
  which has</span> <span m=''1331540''>substituted</span> <span m=''1332390''>the</span>
  <span m=''1332650''>values</span> <span m=''1333080''>of</span> <span m=''1333170''>the</span>
  <span m=''1333260''>pattern</span> <span m=''1334030''>variable</span> <span m=''1334580''>that</span>
  <span m=''1334880''>were</span> <span m=''1334980''>matched</span> <span m=''1335410''>on</span>
  <span m=''1335570''>the</span> <span m=''1335640''>left-hand</span> <span m=''1336100''>side</span>
  <span m=''1336790''>for</span> <span m=''1337100''>the</span> <span m=''1337230''>variables</span>
  <span m=''1337680''>that</span> <span m=''1337770''>are</span> <span m=''1337860''>mentioned,</span>
  <span m=''1338840''>the</span> <span m=''1338950''>skeleton</span> <span m=''1339350''>variables</span>
  <span m=''1339750''>or evaluation</span> <span m=''1340570''>variables</span> <span
  m=''1340930''>or whatever</span> <span m=''1341860''>I</span> <span m=''1341970''>called</span>
  <span m=''1342180''>them,</span> <span m=''1342800''>on</span> <span m=''1342920''>the</span>
  <span m=''1343050''>right-hand</span> <span m=''1343480''>side.</span> </p><p><span
  m=''1345170''>AUDIENCE: And</span> <span m=''1345520''>then</span> <span m=''1345760''>that''s</span>
  <span m=''1346030''>passed</span> <span m=''1346315''>back</span> <span m=''1346600''>into</span>
  <span m=''1346760''>the</span> <span m=''1346810''>matcher?</span> </p><p><span
  m=''1347660''>PROFESSOR: Then</span> <span m=''1347870''>this is</span> <span m=''1348030''>going</span>
  <span m=''1348150''>to</span> <span m=''1348280''>go</span> <span m=''1348690''>around</span>
  <span m=''1349180''>again.</span> <span m=''1349490''>This is going</span> <span
  m=''1349610''>to</span> <span m=''1349720''>go</span> <span m=''1349870''>through</span>
  <span m=''1350120''>this</span> <span m=''1350310''>mess</span> <span m=''1350860''>until</span>
  <span m=''1351330''>it</span> <span m=''1351390''>no</span> <span m=''1351500''>longer</span>
  <span m=''1351800''>changes.</span> </p><p><span m=''1353240''>AUDIENCE: And</span>
  <span m=''1353800''>it</span> <span m=''1353990''>seems</span> <span m=''1354270''>that</span>
  <span m=''1354370''>there</span> <span m=''1354510''>would</span> <span m=''1354650''>be</span>
  <span m=''1354800''>a</span> <span m=''1354870''>danger</span> <span m=''1355360''>of</span>
  <span m=''1355440''>getting</span> <span m=''1355680''>into</span> <span m=''1355870''>a</span>
  <span m=''1356200''>recursive</span> <span m=''1356760''>loop.</span> </p><p><span
  m=''1357170''>PROFESSOR: Yes.</span> <span m=''1358160''>Yes,</span> <span m=''1358410''>if
  you</span> <span m=''1358590''>do not</span> <span m=''1358890''>write</span> <span
  m=''1359030''>your</span> <span m=''1359200''>rules</span> <span m=''1359490''>nicely,</span>
  <span m=''1360930''>you</span> <span m=''1361190''>are--</span> <span m=''1361240''>indeed,</span>
  <span m=''1362040''>in</span> <span m=''1362180''>any</span> <span m=''1362370''>programming</span>
  <span m=''1362790''>language</span> <span m=''1363130''>you</span> <span m=''1363280''>invent,</span>
  <span m=''1363540''>if</span> <span m=''1363800''>it''s</span> <span m=''1363870''>sufficiently</span>
  <span m=''1364280''>powerful</span> <span m=''1364730''>to</span> <span m=''1364800''>do</span>
  <span m=''1364950''>anything,</span> <span m=''1365700''>you</span> <span m=''1365840''>can</span>
  <span m=''1365980''>write</span> <span m=''1366190''>programs</span> <span m=''1366680''>that</span>
  <span m=''1367560''>will</span> <span m=''1367640''>go</span> <span m=''1367780''>into</span>
  <span m=''1368010''>infinite</span> <span m=''1368280''>loops.</span> <span m=''1369280''>And</span>
  <span m=''1369480''>indeed,</span> <span m=''1370760''>writing</span> <span m=''1371030''>a</span>
  <span m=''1371090''>program</span> <span m=''1371510''>for</span> <span m=''1371850''>doing</span>
  <span m=''1372200''>algebraic</span> <span m=''1372600''>manipulation</span> <span
  m=''1373090''>for</span> <span m=''1373380''>long</span> <span m=''1373800''>will</span>
  <span m=''1373970''>produce</span> <span m=''1374540''>infinite</span> <span m=''1374680''>loops.</span>
  <span m=''1380722''>Go</span> <span m=''1381198''>ahead.</span> </p><p><span m=''1381680''>AUDIENCE:
  Some</span> <span m=''1382380''>language</span> <span m=''1382830''>designers</span>
  <span m=''1383480''>feel</span> <span m=''1383780''>that</span> <span m=''1384410''>this</span>
  <span m=''1384580''>feature</span> <span m=''1384890''>is</span> <span m=''1385200''>so</span>
  <span m=''1385440''>important</span> <span m=''1386060''>that</span> <span m=''1386180''>it</span>
  <span m=''1386310''>should</span> <span m=''1386550''>become</span> <span m=''1387340''>part</span>
  <span m=''1387660''>of</span> <span m=''1387760''>the</span> <span m=''1387850''>basic</span>
  <span m=''1388280''>language,</span> <span m=''1388770''>for</span> <span m=''1388910''>example,</span>
  <span m=''1389440''>scheme</span> <span m=''1390473''>in</span> <span m=''1390966''>this</span>
  <span m=''1391460''>case.</span> <span m=''1392670''>What</span> <span m=''1392870''>are</span>
  <span m=''1392920''>your</span> <span m=''1393060''>thoughts</span> <span m=''1393530''>on--</span>
  </p><p><span m=''1393960''>PROFESSOR: Which</span> <span m=''1394310''>language</span>
  <span m=''1394670''>feature?</span> </p><p><span m=''1395722''>AUDIENCE: The</span>
  <span m=''1396080''>pairs</span> <span m=''1396380''>matching.</span> <span m=''1397290''>It''s
  all</span> <span m=''1397700''>application</span> <span m=''1398460''>of</span>
  <span m=''1398520''>such</span> <span m=''1398770''>rules</span> <span m=''1400090''>should</span>
  <span m=''1400640''>be--</span> </p><p><span m=''1401840''>PROFESSOR: Oh,</span>
  <span m=''1402000''>you mean</span> <span m=''1402190''>like</span> <span m=''1402390''>Prolog?</span>
  </p><p><span m=''1403650''>AUDIENCE: Like</span> <span m=''1403800''>Prolog,</span>
  <span m=''1404480''>but</span> <span m=''1405190''>it</span> <span m=''1405470''>becomes</span>
  <span m=''1405900''>a</span> <span m=''1405970''>more</span> <span m=''1406190''>general--</span>
  </p><p><span m=''1406595''>PROFESSOR: It''s</span> <span m=''1407000''>possible.</span>
  <span m=''1408470''>OK,</span> <span m=''1408710''>I</span> <span m=''1408880''>think</span>
  <span m=''1409200''>my</span> <span m=''1409420''>feeling</span> <span m=''1409720''>about</span>
  <span m=''1410010''>that</span> <span m=''1411500''>is</span> <span m=''1411940''>that</span>
  <span m=''1413150''>I</span> <span m=''1413260''>would</span> <span m=''1413380''>like</span>
  <span m=''1413680''>to teach</span> <span m=''1413800''>you</span> <span m=''1413890''>how</span>
  <span m=''1413990''>to</span> <span m=''1414100''>do</span> <span m=''1414270''>it</span>
  <span m=''1414370''>so you</span> <span m=''1414540''>don''t</span> <span m=''1414690''>depend</span>
  <span m=''1414950''>upon</span> <span m=''1415240''>some</span> <span m=''1415840''>language</span>
  <span m=''1416130''>designer.</span> </p><p><span m=''1418490''>AUDIENCE: OK.</span>
  </p><p><span m=''1420870''>PROFESSOR: You</span> <span m=''1421010''>make</span>
  <span m=''1421210''>it</span> <span m=''1421290''>yourself.</span> <span m=''1421850''>You</span>
  <span m=''1421970''>can</span> <span m=''1422100''>roll</span> <span m=''1422280''>your</span>
  <span m=''1422470''>own.</span> <span m=''1424640''>Thank</span> <span m=''1425500''>you.</span>
  </p><p><span m=''1454120''>Well,</span> <span m=''1455410''>let''s</span> <span
  m=''1455600''>see.</span> <span m=''1455800''>Now</span> <span m=''1456030''>we</span>
  <span m=''1456120''>have</span> <span m=''1456240''>to</span> <span m=''1456280''>tell</span>
  <span m=''1456440''>you</span> <span m=''1456560''>how</span> <span m=''1456750''>it</span>
  <span m=''1456830''>works.</span> <span m=''1461586''>It</span> <span m=''1461980''>conveniently</span>
  <span m=''1462490''>breaks</span> <span m=''1462830''>up</span> <span m=''1463030''>into</span>
  <span m=''1463130''>various</span> <span m=''1463520''>pieces.</span> <span m=''1464445''>I''d</span>
  <span m=''1464840''>like</span> <span m=''1465100''>to</span> <span m=''1465150''>look</span>
  <span m=''1465410''>now</span> <span m=''1465720''>at</span> <span m=''1465840''>the</span>
  <span m=''1465920''>matcher.</span> <span m=''1468680''>The</span> <span m=''1468790''>matcher</span>
  <span m=''1469160''>has</span> <span m=''1469360''>the</span> <span m=''1469440''>following</span>
  <span m=''1470340''>basic</span> <span m=''1470750''>structure.</span> <span m=''1472730''>It''s</span>
  <span m=''1472970''>a</span> <span m=''1473730''>box</span> <span m=''1474700''>that</span>
  <span m=''1474970''>takes</span> <span m=''1475190''>as</span> <span m=''1475340''>its</span>
  <span m=''1475740''>input</span> <span m=''1477810''>an</span> <span m=''1478360''>expression</span>
  <span m=''1483960''>and</span> <span m=''1484400''>a</span> <span m=''1484500''>pattern,</span>
  <span m=''1492080''>and</span> <span m=''1492380''>it</span> <span m=''1492500''>turns</span>
  <span m=''1492790''>out</span> <span m=''1493050''>a</span> <span m=''1493160''>dictionary.</span>
  </p><p><span m=''1501530''>A</span> <span m=''1501790''>dictionary,</span> <span
  m=''1502390''>remember,</span> <span m=''1502780''>is</span> <span m=''1502880''>a</span>
  <span m=''1502980''>mapping</span> <span m=''1503700''>of</span> <span m=''1504520''>pattern</span>
  <span m=''1504930''>variables</span> <span m=''1506440''>to</span> <span m=''1506610''>the</span>
  <span m=''1506710''>values</span> <span m=''1507230''>that</span> <span m=''1507340''>were</span>
  <span m=''1507510''>found</span> <span m=''1507860''>by</span> <span m=''1508020''>matching,</span>
  <span m=''1509030''>and it</span> <span m=''1509340''>puts</span> <span m=''1509680''>out</span>
  <span m=''1509990''>another</span> <span m=''1510340''>dictionary,</span> <span
  m=''1518230''>which</span> <span m=''1518500''>is</span> <span m=''1518720''>the</span>
  <span m=''1518830''>result</span> <span m=''1519300''>of</span> <span m=''1519470''>augmenting</span>
  <span m=''1520150''>this</span> <span m=''1520370''>dictionary</span> <span m=''1521220''>by</span>
  <span m=''1521470''>what</span> <span m=''1521690''>was</span> <span m=''1521910''>found</span>
  <span m=''1522620''>in</span> <span m=''1522890''>matching</span> <span m=''1523490''>this</span>
  <span m=''1523810''>expression</span> <span m=''1524350''>against</span> <span m=''1524600''>this</span>
  <span m=''1524880''>pattern.</span> <span m=''1527930''>So</span> <span m=''1528100''>that''s</span>
  <span m=''1528360''>the</span> <span m=''1528460''>matcher.</span> </p><p><span
  m=''1533900''>Now,</span> <span m=''1534010''>this</span> <span m=''1534200''>is</span>
  <span m=''1534260''>a</span> <span m=''1534610''>rather</span> <span m=''1535050''>complicated</span>
  <span m=''1535770''>program,</span> <span m=''1537170''>and</span> <span m=''1537380''>we</span>
  <span m=''1537600''>can</span> <span m=''1538110''>look</span> <span m=''1538330''>at</span>
  <span m=''1538550''>it</span> <span m=''1538660''>on</span> <span m=''1538860''>the</span>
  <span m=''1539000''>overhead</span> <span m=''1539520''>over</span> <span m=''1539750''>here</span>
  <span m=''1540880''>and</span> <span m=''1541110''>see,</span> <span m=''1541880''>ha,</span>
  <span m=''1542080''>ha,</span> <span m=''1542530''>it''s</span> <span m=''1542780''>very</span>
  <span m=''1543070''>complicated.</span> <span m=''1544430''>I just</span> <span
  m=''1544650''>want you to</span> <span m=''1544890''>look</span> <span m=''1545030''>at</span>
  <span m=''1545160''>the</span> <span m=''1545240''>shape</span> <span m=''1545660''>of</span>
  <span m=''1545780''>it.</span> <span m=''1546740''>It''s</span> <span m=''1547410''>too</span>
  <span m=''1547820''>complicated</span> <span m=''1548460''>to</span> <span m=''1548560''>look</span>
  <span m=''1548740''>at</span> <span m=''1548920''>except</span> <span m=''1549240''>in</span>
  <span m=''1549360''>pieces.</span> <span m=''1551670''>However,</span> <span m=''1552080''>it''s</span>
  <span m=''1552190''>a</span> <span m=''1552660''>fairly</span> <span m=''1553070''>large,</span>
  <span m=''1553400''>complicated</span> <span m=''1554050''>program</span> <span
  m=''1554990''>with</span> <span m=''1555340''>a</span> <span m=''1555480''>lot</span>
  <span m=''1556720''>of</span> <span m=''1557010''>sort</span> <span m=''1557270''>of</span>
  <span m=''1558020''>indented</span> <span m=''1558580''>structure.</span> <span
  m=''1560140''>At</span> <span m=''1560310''>the</span> <span m=''1560400''>largest</span>
  <span m=''1561010''>scale--</span> <span m=''1562090''>you don''t</span> <span m=''1562470''>try</span>
  <span m=''1562660''>to</span> <span m=''1562750''>read</span> <span m=''1562930''>those</span>
  <span m=''1563150''>characters,</span> <span m=''1564010''>but</span> <span m=''1564120''>at</span>
  <span m=''1564230''>the</span> <span m=''1564310''>largest</span> <span m=''1564740''>scale,</span>
  <span m=''1565410''>you</span> <span m=''1565580''>see</span> <span m=''1566120''>that</span>
  <span m=''1566300''>there</span> <span m=''1566590''>is</span> <span m=''1566970''>a</span>
  <span m=''1567110''>case</span> <span m=''1567450''>analysis,</span> <span m=''1568570''>which</span>
  <span m=''1568780''>is</span> <span m=''1568910''>all</span> <span m=''1569130''>these</span>
  <span m=''1569390''>cases</span> <span m=''1569770''>lined</span> <span m=''1570180''>up.</span>
  <span m=''1572100''>What</span> <span m=''1572270''>we''re</span> <span m=''1572430''>now</span>
  <span m=''1572680''>going</span> <span m=''1572920''>to</span> <span m=''1573010''>do</span>
  <span m=''1573830''>is</span> <span m=''1574030''>look</span> <span m=''1574160''>at</span>
  <span m=''1574290''>this</span> <span m=''1574470''>in</span> <span m=''1574650''>a</span>
  <span m=''1574700''>bit</span> <span m=''1574900''>more</span> <span m=''1575400''>detail,</span>
  <span m=''1576600''>attempting</span> <span m=''1577070''>to</span> <span m=''1577140''>understand</span>
  <span m=''1577940''>how</span> <span m=''1578200''>it</span> <span m=''1578270''>works.</span>
  </p><p><span m=''1579970''>Let''s</span> <span m=''1580280''>go</span> <span m=''1580430''>now</span>
  <span m=''1580680''>to</span> <span m=''1580900''>the</span> <span m=''1581400''>first</span>
  <span m=''1581790''>slide,</span> <span m=''1583460''>showing</span> <span m=''1584230''>some</span>
  <span m=''1584530''>of</span> <span m=''1584660''>the</span> <span m=''1584810''>structure</span>
  <span m=''1586300''>of</span> <span m=''1586430''>the</span> <span m=''1586560''>matcher</span>
  <span m=''1586980''>at</span> <span m=''1587100''>a</span> <span m=''1587140''>large</span>
  <span m=''1587480''>scale.</span> <span m=''1588710''>And</span> <span m=''1588890''>we</span>
  <span m=''1589080''>see</span> <span m=''1589600''>that</span> <span m=''1589770''>the</span>
  <span m=''1589860''>matcher, the matcher</span> <span m=''1591860''>takes</span>
  <span m=''1592230''>as</span> <span m=''1592380''>its</span> <span m=''1592500''>input</span>
  <span m=''1593440''>a</span> <span m=''1593610''>pattern,</span> <span m=''1594500''>an</span>
  <span m=''1594630''>expression,</span> <span m=''1595410''>and</span> <span m=''1595570''>a</span>
  <span m=''1595720''>dictionary.</span> <span m=''1598580''>And</span> <span m=''1598750''>there</span>
  <span m=''1598970''>is</span> <span m=''1599080''>a</span> <span m=''1599190''>case</span>
  <span m=''1599490''>analysis</span> <span m=''1600060''>here,</span> <span m=''1601310''>which</span>
  <span m=''1601640''>is</span> <span m=''1601840''>made</span> <span m=''1602090''>out
  of</span> <span m=''1602370''>several</span> <span m=''1602680''>cases,</span> <span
  m=''1603620''>some</span> <span m=''1603880''>of</span> <span m=''1603970''>which</span>
  <span m=''1604130''>have</span> <span m=''1604260''>been</span> <span m=''1604430''>left</span>
  <span m=''1604740''>out</span> <span m=''1604980''>over</span> <span m=''1605120''>here,</span>
  <span m=''1606630''>and</span> <span m=''1606840''>the</span> <span m=''1606920''>general</span>
  <span m=''1607320''>case,</span> <span m=''1607600''>which</span> <span m=''1607770''>I''d</span>
  <span m=''1607880''>like</span> <span m=''1608090''>you</span> <span m=''1608170''>to</span>
  <span m=''1608250''>see.</span> </p><p><span m=''1610560''>Let''s</span> <span m=''1610790''>consider</span>
  <span m=''1611170''>this</span> <span m=''1611380''>general</span> <span m=''1611670''>case.</span>
  <span m=''1611920''>It''s</span> <span m=''1612040''>a</span> <span m=''1612100''>very</span>
  <span m=''1612370''>important</span> <span m=''1612790''>pattern.</span> <span m=''1615920''>The</span>
  <span m=''1616470''>problem</span> <span m=''1616920''>is</span> <span m=''1617240''>that</span>
  <span m=''1617490''>we</span> <span m=''1617620''>have</span> <span m=''1617850''>to</span>
  <span m=''1618680''>examine</span> <span m=''1619600''>two</span> <span m=''1619840''>trees</span>
  <span m=''1620650''>simultaneously.</span> <span m=''1623000''>One</span> <span
  m=''1623250''>of</span> <span m=''1623320''>the</span> <span m=''1623410''>trees</span>
  <span m=''1624110''>is</span> <span m=''1624280''>the</span> <span m=''1624360''>tree</span>
  <span m=''1624610''>of</span> <span m=''1624710''>the</span> <span m=''1624810''>expression,</span>
  <span m=''1625990''>and</span> <span m=''1626110''>the</span> <span m=''1626230''>other</span>
  <span m=''1626430''>is</span> <span m=''1626510''>the</span> <span m=''1626620''>tree</span>
  <span m=''1626950''>of</span> <span m=''1627070''>the</span> <span m=''1627150''>pattern.</span>
  <span m=''1628660''>We</span> <span m=''1628770''>have</span> <span m=''1628870''>to</span>
  <span m=''1628950''>compare</span> <span m=''1629340''>them</span> <span m=''1629480''>with</span>
  <span m=''1629620''>each</span> <span m=''1629800''>other</span> <span m=''1631360''>so</span>
  <span m=''1631510''>that</span> <span m=''1631850''>the</span> <span m=''1632540''>subexpressions</span>
  <span m=''1633460''>of</span> <span m=''1633660''>the</span> <span m=''1633740''>expression</span>
  <span m=''1634440''>are</span> <span m=''1634690''>matched</span> <span m=''1635020''>against</span>
  <span m=''1635230''>subexpressions</span> <span m=''1635880''>of</span> <span m=''1635980''>the</span>
  <span m=''1636030''>pattern.</span> </p><p><span m=''1638380''>Looking</span> <span
  m=''1638640''>at</span> <span m=''1638750''>that</span> <span m=''1638860''>in</span>
  <span m=''1639060''>a</span> <span m=''1639180''>bit</span> <span m=''1639390''>more</span>
  <span m=''1639590''>detail,</span> <span m=''1640270''>suppose</span> <span m=''1640750''>I</span>
  <span m=''1640930''>had</span> <span m=''1641110''>a</span> <span m=''1641170''>pattern,
  a pattern,</span> <span m=''1643910''>which</span> <span m=''1644110''>was</span>
  <span m=''1644650''>the</span> <span m=''1644830''>sum</span> <span m=''1645760''>of</span>
  <span m=''1646060''>the</span> <span m=''1646160''>product</span> <span m=''1649225''>of</span>
  <span m=''1649650''>a</span> <span m=''1649820''>thing</span> <span m=''1650270''>which</span>
  <span m=''1650450''>we</span> <span m=''1650560''>will</span> <span m=''1650690''>call</span>
  <span m=''1651080''>x</span> <span m=''1652420''>and</span> <span m=''1653090''>a</span>
  <span m=''1653300''>thing</span> <span m=''1654140''>which</span> <span m=''1654270''>we</span>
  <span m=''1654390''>will</span> <span m=''1654550''>call</span> <span m=''1654870''>y,</span>
  <span m=''1658130''>and</span> <span m=''1659110''>the</span> <span m=''1659310''>sum</span>
  <span m=''1659550''>of</span> <span m=''1659710''>that,</span> <span m=''1660330''>and</span>
  <span m=''1660630''>the</span> <span m=''1660700''>same</span> <span m=''1661040''>thing</span>
  <span m=''1661220''>we</span> <span m=''1661350''>call</span> <span m=''1661640''>y.</span>
  <span m=''1665070''>So</span> <span m=''1665230''>we''re</span> <span m=''1665410''>looking</span>
  <span m=''1665810''>for</span> <span m=''1666460''>a</span> <span m=''1666640''>sum</span>
  <span m=''1666930''>of a</span> <span m=''1667090''>product</span> <span m=''1669030''>whose</span>
  <span m=''1669730''>second--whose second</span> <span m=''1671640''>argument</span>
  <span m=''1672610''>is</span> <span m=''1672770''>the</span> <span m=''1672870''>same</span>
  <span m=''1673250''>as</span> <span m=''1673410''>the</span> <span m=''1673460''>second</span>
  <span m=''1673790''>argument</span> <span m=''1674140''>of the</span> <span m=''1674310''>sum.</span>
  <span m=''1676960''>That''s</span> <span m=''1677180''>a</span> <span m=''1677470''>thing</span>
  <span m=''1677740''>you</span> <span m=''1677840''>might</span> <span m=''1678040''>be</span>
  <span m=''1678170''>looking</span> <span m=''1678490''>for.</span> <span m=''1679650''>Well,</span>
  <span m=''1679760''>that,</span> <span m=''1680180''>as a</span> <span m=''1680300''>pattern,</span>
  <span m=''1681160''>looks</span> <span m=''1681520''>like</span> <span m=''1681690''>this.</span>
  <span m=''1682770''>There</span> <span m=''1683270''>is</span> <span m=''1683370''>a</span>
  <span m=''1683490''>tree,</span> <span m=''1684950''>which</span> <span m=''1685110''>consists</span>
  <span m=''1685490''>of</span> <span m=''1685590''>a</span> <span m=''1685800''>sum,</span>
  <span m=''1688040''>and</span> <span m=''1689330''>a</span> <span m=''1689660''>product</span>
  <span m=''1691860''>with</span> <span m=''1692210''>a</span> <span m=''1693200''>pattern</span>
  <span m=''1693750''>variable</span> <span m=''1694060''>question</span> <span m=''1694370''>mark</span>
  <span m=''1694750''>x</span> <span m=''1696192''>and</span> <span m=''1696640''>question</span>
  <span m=''1697050''>mark</span> <span m=''1698510''>y,</span> <span m=''1699110''>the</span>
  <span m=''1699230''>other</span> <span m=''1699360''>pattern</span> <span m=''1699720''>variable,</span>
  <span m=''1701390''>and</span> <span m=''1701650''>question</span> <span m=''1701960''>mark</span>
  <span m=''1702180''>y,</span> <span m=''1703210''>just</span> <span m=''1703360''>looking</span>
  <span m=''1703480''>at</span> <span m=''1703590''>the</span> <span m=''1703680''>same,</span>
  <span m=''1704920''>just</span> <span m=''1705120''>writing</span> <span m=''1705440''>down</span>
  <span m=''1705690''>the list</span> <span m=''1705880''>structure</span> <span m=''1706290''>in
  a</span> <span m=''1706330''>different</span> <span m=''1706640''>way.</span> </p><p><span
  m=''1708760''>Now,</span> <span m=''1709025''>suppose we</span> <span m=''1709290''>were</span>
  <span m=''1709450''>matching</span> <span m=''1709840''>that</span> <span m=''1710040''>against</span>
  <span m=''1710330''>an</span> <span m=''1710420''>expression</span> <span m=''1711040''>which</span>
  <span m=''1711210''>matches</span> <span m=''1711600''>it,</span> <span m=''1712440''>the</span>
  <span m=''1712740''>sum</span> <span m=''1713540''>of,</span> <span m=''1713690''>say,</span>
  <span m=''1714520''>the</span> <span m=''1714620''>product</span> <span m=''1715440''>of</span>
  <span m=''1715770''>3</span> <span m=''1716320''>and</span> <span m=''1716650''>x</span>
  <span m=''1718990''>and,</span> <span m=''1719270''>say,</span> <span m=''1719650''>x.</span>
  <span m=''1722420''>That''s</span> <span m=''1722620''>another</span> <span m=''1722910''>tree.</span>
  <span m=''1724380''>It''s</span> <span m=''1724660''>the</span> <span m=''1725200''>sum</span>
  <span m=''1726520''>of</span> <span m=''1727520''>the</span> <span m=''1727780''>product</span>
  <span m=''1729350''>of</span> <span m=''1730140''>3</span> <span m=''1730780''>and</span>
  <span m=''1731530''>x</span> <span m=''1733240''>and</span> <span m=''1734312''>of</span>
  <span m=''1735790''>x.</span> <span m=''1739320''>So what</span> <span m=''1739540''>I</span>
  <span m=''1739670''>want</span> <span m=''1739830''>to</span> <span m=''1739990''>do</span>
  <span m=''1740190''>is</span> <span m=''1740420''>traverse</span> <span m=''1740770''>these</span>
  <span m=''1740950''>two</span> <span m=''1741150''>trees</span> <span m=''1742030''>simultaneously.</span>
  <span m=''1744410''>And</span> <span m=''1744560''>what</span> <span m=''1744660''>I''d</span>
  <span m=''1744820''>like</span> <span m=''1745030''>to</span> <span m=''1745130''>do</span>
  <span m=''1745640''>is</span> <span m=''1745870''>walk</span> <span m=''1746240''>them</span>
  <span m=''1747210''>like</span> <span m=''1747450''>this.</span> <span m=''1748670''>I''m</span>
  <span m=''1748840''>going</span> <span m=''1748990''>to</span> <span m=''1749140''>say</span>
  <span m=''1751820''>are</span> <span m=''1752020''>these</span> <span m=''1752300''>the</span>
  <span m=''1752400''>same?</span> <span m=''1752880''>This</span> <span m=''1753190''>is</span>
  <span m=''1753290''>a</span> <span m=''1753380''>complicated</span> <span m=''1753960''>object.</span>
  <span m=''1755200''>Let''s</span> <span m=''1755430''>look</span> <span m=''1755600''>at</span>
  <span m=''1755730''>the</span> <span m=''1756440''>left</span> <span m=''1756740''>branches.</span>
  <span m=''1757240''>Well, that</span> <span m=''1757510''>could</span> <span m=''1757600''>be</span>
  <span m=''1757680''>the</span> <span m=''1757770''>car.</span> <span m=''1758460''>How</span>
  <span m=''1758720''>does that</span> <span m=''1759020''>look?</span> <span m=''1759250''>Oh</span>
  <span m=''1759410''>yes,</span> <span m=''1759730''>the</span> <span m=''1759850''>plus</span>
  <span m=''1760160''>looks</span> <span m=''1760410''>just</span> <span m=''1760680''>fine.</span>
  <span m=''1761880''>But</span> <span m=''1762010''>the</span> <span m=''1762210''>next</span>
  <span m=''1762410''>thing</span> <span m=''1762610''>here</span> <span m=''1763070''>is</span>
  <span m=''1763220''>a</span> <span m=''1763260''>complicated</span> <span m=''1763810''>thing.</span>
  <span m=''1764080''>Let''s</span> <span m=''1764250''>look</span> <span m=''1764370''>at</span>
  <span m=''1764490''>that.</span> <span m=''1765170''>Oh</span> <span m=''1765420''>yes,</span>
  <span m=''1765740''>that''s</span> <span m=''1765990''>pretty</span> <span m=''1766210''>fine,</span>
  <span m=''1766570''>too.</span> <span m=''1766780''>They''re</span> <span m=''1766920''>both</span>
  <span m=''1767110''>asterisks.</span> </p><p><span m=''1768560''>Now,</span> <span
  m=''1769920''>whoops!</span> <span m=''1770410''>My</span> <span m=''1770620''>pattern</span>
  <span m=''1771060''>variable,</span> <span m=''1771930''>it</span> <span m=''1772120''>matches</span>
  <span m=''1772550''>against</span> <span m=''1772770''>the</span> <span m=''1772990''>3.</span>
  <span m=''1774300''>Remember,</span> <span m=''1774830''>x</span> <span m=''1774930''>equals</span>
  <span m=''1775320''>3</span> <span m=''1775550''>now.</span> <span m=''1776400''>That''s</span>
  <span m=''1776580''>in</span> <span m=''1776660''>my</span> <span m=''1776800''>dictionary,</span>
  <span m=''1777580''>and</span> <span m=''1777800''>the</span> <span m=''1777920''>dictionary''s</span>
  <span m=''1778100''>going</span> <span m=''1778190''>to</span> <span m=''1778290''>follow</span>
  <span m=''1778720''>along</span> <span m=''1779150''>with</span> <span m=''1779320''>me:</span>
  <span m=''1779760''>x</span> <span m=''1780020''>equals</span> <span m=''1780340''>three.</span>
  <span m=''1781490''>Ah</span> <span m=''1781700''>yes,</span> <span m=''1782480''>x</span>
  <span m=''1782740''>equals</span> <span m=''1783010''>3</span> <span m=''1783260''>and</span>
  <span m=''1783400''>y</span> <span m=''1783720''>equals</span> <span m=''1783840''>x,</span>
  <span m=''1785370''>different</span> <span m=''1785650''>x.</span> <span m=''1786800''>The</span>
  <span m=''1786920''>pattern</span> <span m=''1787270''>x</span> <span m=''1787850''>is</span>
  <span m=''1788800''>the</span> <span m=''1789250''>expression</span> <span m=''1789780''>x,</span>
  <span m=''1790140''>the</span> <span m=''1790370''>pattern</span> <span m=''1790730''>y.</span>
  <span m=''1793630''>Oh</span> <span m=''1793760''>yes,</span> <span m=''1794040''>the</span>
  <span m=''1794150''>pattern</span> <span m=''1794540''>variable</span> <span m=''1794920''>y,</span>
  <span m=''1796160''>I''ve</span> <span m=''1796360''>already</span> <span m=''1796570''>got</span>
  <span m=''1796690''>a</span> <span m=''1796730''>value</span> <span m=''1797070''>for
  it.</span> <span m=''1797270''>It''s</span> <span m=''1797420''>x.</span> <span
  m=''1798410''>Is</span> <span m=''1798570''>this</span> <span m=''1798720''>an</span>
  <span m=''1798880''>x?</span> <span m=''1799050''>Oh</span> <span m=''1799160''>yeah,</span>
  <span m=''1799510''>sure</span> <span m=''1799750''>it</span> <span m=''1799790''>is.</span>
  <span m=''1800070''>That''s</span> <span m=''1800200''>fine.</span> <span m=''1802040''>Yep,</span>
  <span m=''1802370''>done.</span> <span m=''1803380''>I</span> <span m=''1803540''>now</span>
  <span m=''1803780''>have</span> <span m=''1804800''>a</span> <span m=''1804890''>dictionary,</span>
  <span m=''1806070''>which</span> <span m=''1806300''>I''ve</span> <span m=''1806430''>accumulated</span>
  <span m=''1807070''>by</span> <span m=''1807200''>making</span> <span m=''1807520''>this</span>
  <span m=''1807670''>walk.</span> </p><p><span m=''1811370''>Well,</span> <span m=''1811560''>now</span>
  <span m=''1811730''>let''s</span> <span m=''1811920''>look</span> <span m=''1812010''>at</span>
  <span m=''1812100''>this</span> <span m=''1812860''>general</span> <span m=''1813240''>case</span>
  <span m=''1813550''>here</span> <span m=''1813740''>and</span> <span m=''1813830''>see</span>
  <span m=''1813950''>how</span> <span m=''1814080''>that</span> <span m=''1814260''>works.</span>
  <span m=''1815830''>Here we</span> <span m=''1816070''>have</span> <span m=''1816330''>it.</span>
  <span m=''1817150''>I</span> <span m=''1817340''>take</span> <span m=''1817800''>in</span>
  <span m=''1818070''>a</span> <span m=''1818290''>pattern variable--a pattern,</span>
  <span m=''1820180''>an</span> <span m=''1820520''>expression,</span> <span m=''1820830''>and</span>
  <span m=''1821000''>a</span> <span m=''1821060''>dictionary.</span> <span m=''1822310''>And</span>
  <span m=''1822560''>now</span> <span m=''1822970''>I''m</span> <span m=''1823250''>going</span>
  <span m=''1823460''>to</span> <span m=''1823540''>do</span> <span m=''1825390''>a</span>
  <span m=''1825500''>complicated</span> <span m=''1826110''>thing</span> <span m=''1826320''>here,</span>
  <span m=''1826490''>which</span> <span m=''1826650''>is</span> <span m=''1826720''>the</span>
  <span m=''1826830''>general</span> <span m=''1827170''>case.</span> <span m=''1829610''>The</span>
  <span m=''1830140''>expression</span> <span m=''1831110''>is</span> <span m=''1831280''>made</span>
  <span m=''1831420''>out of</span> <span m=''1831630''>two</span> <span m=''1831770''>parts:</span>
  <span m=''1832790''>a</span> <span m=''1832890''>left</span> <span m=''1833130''>and
  a</span> <span m=''1833240''>right</span> <span m=''1833480''>half,</span> <span
  m=''1834180''>in</span> <span m=''1834370''>general.</span> <span m=''1835470''>Anything</span>
  <span m=''1835700''>that''s</span> <span m=''1835970''>complicated</span> <span
  m=''1836520''>is</span> <span m=''1836610''>made</span> <span m=''1836810''>out</span>
  <span m=''1836900''>of</span> <span m=''1837000''>two</span> <span m=''1837140''>pieces</span>
  <span m=''1837950''>in a</span> <span m=''1838080''>Lisp</span> <span m=''1838340''>system.</span>
  </p><p><span m=''1839950''>Well,</span> <span m=''1840170''>now</span> <span m=''1840340''>what
  do</span> <span m=''1840480''>we</span> <span m=''1840690''>have</span> <span m=''1840900''>here?</span>
  <span m=''1841870''>I''m</span> <span m=''1842100''>going</span> <span m=''1842330''>to</span>
  <span m=''1842450''>match</span> <span m=''1842830''>the</span> <span m=''1842990''>car''s</span>
  <span m=''1843630''>of</span> <span m=''1843760''>the</span> <span m=''1843850''>two</span>
  <span m=''1843980''>expressions</span> <span m=''1845410''>against</span> <span
  m=''1845840''>each</span> <span m=''1846020''>other</span> <span m=''1846790''>with</span>
  <span m=''1846920''>respect</span> <span m=''1847330''>to</span> <span m=''1847400''>the</span>
  <span m=''1847500''>dictionary</span> <span m=''1847990''>I</span> <span m=''1848280''>already</span>
  <span m=''1848510''>have,</span> <span m=''1850190''>producing</span> <span m=''1850890''>a</span>
  <span m=''1850990''>dictionary</span> <span m=''1852210''>as</span> <span m=''1852380''>its</span>
  <span m=''1852550''>value,</span> <span m=''1854240''>which</span> <span m=''1854480''>I</span>
  <span m=''1854580''>will</span> <span m=''1854710''>then</span> <span m=''1854960''>use</span>
  <span m=''1855620''>for</span> <span m=''1855740''>matching</span> <span m=''1856060''>the</span>
  <span m=''1856140''>cdr''s</span> <span m=''1856510''>against</span> <span m=''1856820''>each</span>
  <span m=''1857000''>other.</span> <span m=''1858130''>So</span> <span m=''1858550''>that''s</span>
  <span m=''1858830''>how</span> <span m=''1858980''>the</span> <span m=''1859120''>dictionary</span>
  <span m=''1859740''>travels,</span> <span m=''1860580''>threads</span> <span m=''1861070''>the</span>
  <span m=''1861200''>entire</span> <span m=''1861580''>structure.</span> <span m=''1863580''>And</span>
  <span m=''1863850''>then</span> <span m=''1863970''>the</span> <span m=''1864050''>result</span>
  <span m=''1864440''>of</span> <span m=''1864520''>that</span> <span m=''1865100''>is</span>
  <span m=''1865270''>the</span> <span m=''1865350''>dictionary</span> <span m=''1865810''>for</span>
  <span m=''1865920''>the</span> <span m=''1866010''>match</span> <span m=''1866310''>of</span>
  <span m=''1866450''>the</span> <span m=''1866550''>car</span> <span m=''1866840''>and</span>
  <span m=''1866990''>the</span> <span m=''1867140''>cdr,</span> <span m=''1870080''>and</span>
  <span m=''1870310''>that''s</span> <span m=''1870500''>what''s</span> <span m=''1870660''>going</span>
  <span m=''1870890''>to</span> <span m=''1870950''>be</span> <span m=''1871230''>returned</span>
  <span m=''1871730''>as</span> <span m=''1871810''>a</span> <span m=''1871890''>value.</span>
  </p><p><span m=''1873640''>Now,</span> <span m=''1873860''>at</span> <span m=''1873920''>any</span>
  <span m=''1874150''>point,</span> <span m=''1874590''>a</span> <span m=''1874750''>match</span>
  <span m=''1875100''>might</span> <span m=''1875430''>fail.</span> <span m=''1876670''>It</span>
  <span m=''1876850''>may</span> <span m=''1877050''>be</span> <span m=''1877180''>the</span>
  <span m=''1877290''>case,</span> <span m=''1877590''>for</span> <span m=''1877730''>example,</span>
  <span m=''1878340''>if</span> <span m=''1878470''>we</span> <span m=''1878580''>go</span>
  <span m=''1878760''>back</span> <span m=''1879320''>and</span> <span m=''1879670''>look</span>
  <span m=''1879960''>at</span> <span m=''1880920''>an</span> <span m=''1881020''>expression</span>
  <span m=''1881530''>that</span> <span m=''1882070''>doesn''t</span> <span m=''1882420''>quite</span>
  <span m=''1882720''>match,</span> <span m=''1883750''>like</span> <span m=''1884010''>supposing</span>
  <span m=''1884520''>this</span> <span m=''1884710''>was</span> <span m=''1886540''>a</span>
  <span m=''1886650''>4.</span> <span m=''1889040''>Well,</span> <span m=''1889220''>now</span>
  <span m=''1889420''>these</span> <span m=''1889630''>two</span> <span m=''1889750''>don''t</span>
  <span m=''1889950''>match</span> <span m=''1890250''>any</span> <span m=''1890410''>more,</span>
  <span m=''1891890''>because</span> <span m=''1892540''>the</span> <span m=''1893010''>x</span>
  <span m=''1893520''>that</span> <span m=''1894070''>had</span> <span m=''1894320''>to</span>
  <span m=''1894430''>be--</span> <span m=''1894860''>sorry,</span> <span m=''1895120''>the</span>
  <span m=''1895530''>y</span> <span m=''1895990''>that</span> <span m=''1896190''>had</span>
  <span m=''1896420''>to</span> <span m=''1896510''>be</span> <span m=''1896690''>x</span>
  <span m=''1896940''>here</span> <span m=''1897830''>and</span> <span m=''1898010''>this</span>
  <span m=''1898190''>y</span> <span m=''1898420''>has</span> <span m=''1898640''>to</span>
  <span m=''1898820''>be</span> <span m=''1899620''>4.</span> <span m=''1900410''>But</span>
  <span m=''1900700''>x</span> <span m=''1900920''>and</span> <span m=''1901050''>4</span>
  <span m=''1901250''>were</span> <span m=''1901380''>not</span> <span m=''1901600''>the</span>
  <span m=''1901680''>same</span> <span m=''1902060''>object</span> <span m=''1902790''>syntactically.</span>
  <span m=''1904510''>So</span> <span m=''1904640''>this</span> <span m=''1904820''>wouldn''t</span>
  <span m=''1905130''>match,</span> <span m=''1905930''>and</span> <span m=''1906230''>that</span>
  <span m=''1906400''>would</span> <span m=''1906510''>be</span> <span m=''1906610''>rejected</span>
  <span m=''1907130''>sometimes,</span> <span m=''1907620''>so</span> <span m=''1907860''>matches</span>
  <span m=''1908230''>may</span> <span m=''1908410''>fail.</span> </p><p><span m=''1910220''>Now,</span>
  <span m=''1910610''>of</span> <span m=''1910780''>course,</span> <span m=''1911400''>because</span>
  <span m=''1912260''>this</span> <span m=''1912510''>matcher</span> <span m=''1913130''>takes</span>
  <span m=''1913540''>the</span> <span m=''1913640''>dictionary</span> <span m=''1914140''>from</span>
  <span m=''1914310''>the</span> <span m=''1914400''>previous</span> <span m=''1914860''>match</span>
  <span m=''1915430''>as</span> <span m=''1915630''>input,</span> <span m=''1916490''>it</span>
  <span m=''1916640''>must</span> <span m=''1916850''>be</span> <span m=''1916950''>able</span>
  <span m=''1917040''>to</span> <span m=''1917110''>propagate</span> <span m=''1917630''>the</span>
  <span m=''1917720''>failures.</span> <span m=''1918520''>And</span> <span m=''1918710''>so
  that''s what</span> <span m=''1918900''>the</span> <span m=''1919100''>first</span>
  <span m=''1919600''>clause</span> <span m=''1919970''>of</span> <span m=''1920090''>this</span>
  <span m=''1920200''>conditional</span> <span m=''1920680''>does.</span> </p><p><span
  m=''1923420''>It''s</span> <span m=''1923650''>also</span> <span m=''1924010''>true</span>
  <span m=''1924740''>that</span> <span m=''1925520''>if</span> <span m=''1925800''>it</span>
  <span m=''1925930''>turned</span> <span m=''1926230''>out</span> <span m=''1926500''>that</span>
  <span m=''1926740''>the</span> <span m=''1926850''>pattern</span> <span m=''1927330''>was</span>
  <span m=''1927490''>not</span> <span m=''1927700''>atomic--</span> <span m=''1928540''>see,</span>
  <span m=''1928850''>if the</span> <span m=''1928960''>pattern</span> <span m=''1929220''>was</span>
  <span m=''1929350''>atomic,</span> <span m=''1929700''>I''d</span> <span m=''1929770''>go</span>
  <span m=''1929940''>into</span> <span m=''1930100''>this</span> <span m=''1930280''>stuff,</span>
  <span m=''1930500''>which</span> <span m=''1930600''>we</span> <span m=''1930680''>haven''t</span>
  <span m=''1930800''>looked</span> <span m=''1931060''>at</span> <span m=''1931230''>yet.</span>
  <span m=''1932060''>But if</span> <span m=''1932350''>the</span> <span m=''1932440''>pattern</span>
  <span m=''1932770''>is</span> <span m=''1932890''>not</span> <span m=''1933130''>atomic</span>
  <span m=''1935870''>and</span> <span m=''1936150''>the</span> <span m=''1936250''>expression</span>
  <span m=''1936700''>is</span> <span m=''1936830''>atomic--</span> <span m=''1937825''>it''s</span>
  <span m=''1938290''>not</span> <span m=''1938480''>made out</span> <span m=''1938640''>of</span>
  <span m=''1938790''>pieces--</span> <span m=''1940010''>then</span> <span m=''1940330''>that</span>
  <span m=''1940500''>must</span> <span m=''1940660''>be</span> <span m=''1940760''>a</span>
  <span m=''1940810''>failure,</span> <span m=''1941760''>and so</span> <span m=''1941940''>we</span>
  <span m=''1942030''>go</span> <span m=''1942180''>over</span> <span m=''1942360''>here.</span>
  <span m=''1943560''>If</span> <span m=''1943770''>the</span> <span m=''1943870''>pattern</span>
  <span m=''1944170''>is</span> <span m=''1944280''>not</span> <span m=''1944490''>atomic</span>
  <span m=''1945080''>and</span> <span m=''1945260''>the</span> <span m=''1945330''>pattern</span>
  <span m=''1945610''>is</span> <span m=''1945700''>not</span> <span m=''1946030''>a</span>
  <span m=''1946660''>pattern</span> <span m=''1946970''>variable--</span> <span m=''1947420''>I</span>
  <span m=''1947520''>have</span> <span m=''1947620''>to</span> <span m=''1947720''>remind</span>
  <span m=''1948060''>myself of</span> <span m=''1948400''>that--</span> <span m=''1949716''>then</span>
  <span m=''1950160''>we</span> <span m=''1950350''>go over</span> <span m=''1950550''>here.</span>
  <span m=''1950850''>So that way,</span> <span m=''1951450''>failures</span> <span
  m=''1951980''>may</span> <span m=''1952190''>occur.</span> </p><p><span m=''1955280''>OK,</span>
  <span m=''1956720''>so</span> <span m=''1956910''>now</span> <span m=''1957070''>let''s</span>
  <span m=''1957280''>look</span> <span m=''1957510''>at</span> <span m=''1957730''>the</span>
  <span m=''1957830''>insides</span> <span m=''1958350''>of</span> <span m=''1958440''>this</span>
  <span m=''1958660''>thing.</span> <span m=''1959612''>Well,</span> <span m=''1959950''>the</span>
  <span m=''1960130''>first</span> <span m=''1960340''>place to</span> <span m=''1960620''>look</span>
  <span m=''1961050''>is</span> <span m=''1961210''>what</span> <span m=''1961370''>happens</span>
  <span m=''1961690''>if</span> <span m=''1961790''>I</span> <span m=''1961900''>have</span>
  <span m=''1962020''>an</span> <span m=''1962080''>atomic</span> <span m=''1962440''>pattern?</span>
  <span m=''1962870''>That''s</span> <span m=''1963150''>very</span> <span m=''1963370''>simple.</span>
  <span m=''1963870''>A</span> <span m=''1964020''>pattern</span> <span m=''1964340''>that''s</span>
  <span m=''1964460''>not</span> <span m=''1964650''>made</span> <span m=''1964800''>out
  of</span> <span m=''1964950''>any</span> <span m=''1965200''>pieces:</span> <span
  m=''1966130''>foo.</span> <span m=''1966945''>That''s a</span> <span m=''1967390''>nice</span>
  <span m=''1967690''>atomic</span> <span m=''1968050''>pattern.</span> <span m=''1969200''>Well,</span>
  <span m=''1970420''>here''s</span> <span m=''1970640''>what</span> <span m=''1970750''>we</span>
  <span m=''1970890''>see.</span> <span m=''1972060''>If</span> <span m=''1972230''>the</span>
  <span m=''1972350''>pattern</span> <span m=''1972730''>is</span> <span m=''1972830''>atomic,</span>
  <span m=''1974220''>then</span> <span m=''1974450''>if</span> <span m=''1974560''>the</span>
  <span m=''1974680''>expression</span> <span m=''1975250''>is</span> <span m=''1975360''>atomic,</span>
  <span m=''1976750''>then</span> <span m=''1977010''>if</span> <span m=''1977120''>they</span>
  <span m=''1977230''>are</span> <span m=''1977320''>the</span> <span m=''1977450''>same</span>
  <span m=''1977840''>thing,</span> <span m=''1978970''>then</span> <span m=''1979360''>the</span>
  <span m=''1979440''>dictionary</span> <span m=''1980070''>I</span> <span m=''1980200''>get</span>
  <span m=''1980400''>is</span> <span m=''1980490''>the</span> <span m=''1980570''>same</span>
  <span m=''1980830''>one</span> <span m=''1981010''>as</span> <span m=''1981110''>I</span>
  <span m=''1981260''>had</span> <span m=''1981400''>before.</span> <span m=''1983120''>Nothing''s</span>
  <span m=''1983510''>changed.</span> <span m=''1984730''>It''s</span> <span m=''1984900''>just</span>
  <span m=''1985300''>that I</span> <span m=''1985510''>matched</span> <span m=''1986100''>plus</span>
  <span m=''1986440''>against</span> <span m=''1986760''>plus,</span> <span m=''1988390''>asterisk</span>
  <span m=''1988800''>against</span> <span m=''1989160''>asterisk,</span> <span m=''1989530''>x</span>
  <span m=''1989760''>against</span> <span m=''1990090''>x.</span> <span m=''1991440''>That''s</span>
  <span m=''1991670''>all</span> <span m=''1991820''>fine.</span> </p><p><span m=''1992920''>However,</span>
  <span m=''1994070''>if</span> <span m=''1994240''>the</span> <span m=''1994350''>pattern</span>
  <span m=''1994670''>is</span> <span m=''1994780''>not</span> <span m=''1995020''>the</span>
  <span m=''1995100''>one</span> <span m=''1995730''>which</span> <span m=''1995930''>is</span>
  <span m=''1995990''>the</span> <span m=''1996110''>expression,</span> <span m=''1997280''>if</span>
  <span m=''1997400''>I have</span> <span m=''1997590''>two</span> <span m=''1997750''>separate</span>
  <span m=''1998090''>atomic</span> <span m=''1998480''>objects,</span> <span m=''1999100''>then</span>
  <span m=''1999405''>it</span> <span m=''1999710''>was</span> <span m=''1999830''>matching</span>
  <span m=''2000200''>plus</span> <span m=''2000430''>against</span> <span m=''2000870''>asterisk,</span>
  <span m=''2002440''>which</span> <span m=''2002680''>case</span> <span m=''2002930''>I</span>
  <span m=''2003030''>fail.</span> <span m=''2005810''>Or</span> <span m=''2006390''>if</span>
  <span m=''2006580''>it</span> <span m=''2006680''>turns</span> <span m=''2006960''>out</span>
  <span m=''2007260''>that</span> <span m=''2007480''>the</span> <span m=''2007920''>pattern</span>
  <span m=''2008260''>is</span> <span m=''2008350''>atomic</span> <span m=''2008890''>but</span>
  <span m=''2009100''>the</span> <span m=''2009300''>expression</span> <span m=''2009760''>is</span>
  <span m=''2009920''>complicated,</span> <span m=''2011470''>it''s</span> <span m=''2011650''>not</span>
  <span m=''2011840''>atomic,</span> <span m=''2013310''>then</span> <span m=''2013420''>I</span>
  <span m=''2013530''>get</span> <span m=''2013620''>a</span> <span m=''2013700''>failure.</span>
  <span m=''2017100''>That''s</span> <span m=''2017600''>very</span> <span m=''2017850''>simple.</span>
  </p><p><span m=''2018800''>Now,</span> <span m=''2018960''>what</span> <span m=''2019110''>about</span>
  <span m=''2019290''>the</span> <span m=''2019470''>various</span> <span m=''2019800''>kinds</span>
  <span m=''2020100''>of</span> <span m=''2022740''>pattern</span> <span m=''2023080''>variables?</span>
  <span m=''2024040''>We</span> <span m=''2024160''>had</span> <span m=''2024340''>three</span>
  <span m=''2024550''>kinds.</span> <span m=''2025610''>I</span> <span m=''2025780''>give</span>
  <span m=''2025940''>them</span> <span m=''2026040''>the</span> <span m=''2026120''>names.</span>
  <span m=''2027340''>They''re</span> <span m=''2027530''>arbitrary</span> <span m=''2028020''>constants,</span>
  <span m=''2029620''>arbitrary</span> <span m=''2030110''>variables,</span> <span
  m=''2030840''>and</span> <span m=''2030990''>arbitrary</span> <span m=''2031370''>expressions.</span>
  <span m=''2033770''>A</span> <span m=''2033920''>question</span> <span m=''2034310''>mark</span>
  <span m=''2037110''>x</span> <span m=''2038570''>is</span> <span m=''2038770''>an</span>
  <span m=''2038880''>arbitrary</span> <span m=''2039500''>expression.</span> <span
  m=''2041210''>A</span> <span m=''2041300''>question</span> <span m=''2041750''>mark</span>
  <span m=''2042040''>cx</span> <span m=''2043440''>is an</span> <span m=''2043740''>arbitrary</span>
  <span m=''2043950''>constant,</span> <span m=''2044520''>and</span> <span m=''2044720''>a</span>
  <span m=''2044830''>question</span> <span m=''2045130''>mark</span> <span m=''2045300''>vx</span>
  <span m=''2045980''>is</span> <span m=''2046240''>an</span> <span m=''2046440''>arbitrary</span>
  <span m=''2046810''>variable.</span> </p><p><span m=''2048537''>Well,</span> <span
  m=''2048949''>what do</span> <span m=''2049170''>we</span> <span m=''2049270''>do</span>
  <span m=''2049460''>here?</span> <span m=''2050540''>Looking</span> <span m=''2050870''>at</span>
  <span m=''2051110''>this,</span> <span m=''2051340''>we</span> <span m=''2051540''>see</span>
  <span m=''2052449''>that</span> <span m=''2053239''>if</span> <span m=''2053409''>I</span>
  <span m=''2053510''>have</span> <span m=''2053600''>an</span> <span m=''2053639''>arbitrary</span>
  <span m=''2054139''>constant,</span> <span m=''2054750''>if</span> <span m=''2055210''>the</span>
  <span m=''2055440''>pattern</span> <span m=''2055780''>is</span> <span m=''2055870''>an</span>
  <span m=''2055940''>arbitrary</span> <span m=''2056370''>constant,</span> <span
  m=''2057530''>then</span> <span m=''2058010''>it</span> <span m=''2058080''>had</span>
  <span m=''2058230''>better</span> <span m=''2058409''>be</span> <span m=''2058530''>the</span>
  <span m=''2058650''>case</span> <span m=''2058920''>that</span> <span m=''2059010''>the</span>
  <span m=''2059090''>expression</span> <span m=''2059560''>had</span> <span m=''2059670''>better</span>
  <span m=''2059830''>be</span> <span m=''2059940''>a</span> <span m=''2059989''>constant.</span>
  <span m=''2061480''>If</span> <span m=''2061639''>the</span> <span m=''2061820''>expression
  is</span> <span m=''2061920''>not</span> <span m=''2062219''>a constant,</span>
  <span m=''2062620''>then</span> <span m=''2062690''>that</span> <span m=''2062889''>match</span>
  <span m=''2063130''>fails.</span> <span m=''2063920''>If</span> <span m=''2064469''>it</span>
  <span m=''2064560''>is</span> <span m=''2064690''>a</span> <span m=''2064750''>constant,</span>
  <span m=''2065110''>however,</span> <span m=''2065690''>then</span> <span m=''2065800''>I</span>
  <span m=''2065920''>wish</span> <span m=''2066100''>to</span> <span m=''2066230''>extend</span>
  <span m=''2066699''>the</span> <span m=''2066780''>dictionary.</span> <span m=''2067620''>I</span>
  <span m=''2067679''>wish</span> <span m=''2067870''>to</span> <span m=''2068360''>extend</span>
  <span m=''2068909''>the</span> <span m=''2068980''>dictionary</span> <span m=''2070699''>with</span>
  <span m=''2070989''>that</span> <span m=''2071650''>pattern</span> <span m=''2072380''>being</span>
  <span m=''2073699''>remembered</span> <span m=''2074250''>to</span> <span m=''2074340''>be</span>
  <span m=''2074480''>that</span> <span m=''2074670''>expression</span> <span m=''2076050''>using</span>
  <span m=''2076340''>the</span> <span m=''2076449''>old</span> <span m=''2076650''>dictionary</span>
  <span m=''2077090''>as a</span> <span m=''2077190''>starting</span> <span m=''2077540''>point.</span>
  </p><p><span m=''2081050''>So really,</span> <span m=''2081315''>for</span> <span
  m=''2081580''>arbitrary</span> <span m=''2082130''>variables,</span> <span m=''2083699''>I
  have to</span> <span m=''2083940''>check</span> <span m=''2084179''>first</span>
  <span m=''2084500''>if the</span> <span m=''2084699''>expression is a</span> <span
  m=''2085199''>variable</span> <span m=''2086570''>by</span> <span m=''2086699''>matching</span>
  <span m=''2087139''>against.</span> <span m=''2087440''>If</span> <span m=''2087690''>so,</span>
  <span m=''2088630''>it''s</span> <span m=''2088790''>worth</span> <span m=''2088989''>extending</span>
  <span m=''2089400''>the</span> <span m=''2089500''>dictionary</span> <span m=''2090330''>so
  that</span> <span m=''2090580''>the</span> <span m=''2090750''>pattern</span> <span
  m=''2091150''>is</span> <span m=''2091260''>remembered</span> <span m=''2091679''>to</span>
  <span m=''2091790''>be</span> <span m=''2091900''>matched</span> <span m=''2092210''>against</span>
  <span m=''2092480''>that</span> <span m=''2092639''>expression,</span> <span m=''2093380''>given</span>
  <span m=''2093630''>the</span> <span m=''2093719''>original</span> <span m=''2094080''>dictionary,</span>
  <span m=''2095230''>and</span> <span m=''2095350''>this</span> <span m=''2095500''>makes</span>
  <span m=''2095820''>a</span> <span m=''2095900''>new</span> <span m=''2096100''>dictionary.</span>
  </p><p><span m=''2098880''>Now,</span> <span m=''2099080''>it</span> <span m=''2099180''>has</span>
  <span m=''2099400''>to</span> <span m=''2099520''>check.</span> <span m=''2100310''>There''s</span>
  <span m=''2100670''>a</span> <span m=''2100790''>sorts</span> <span m=''2101060''>of</span>
  <span m=''2101150''>failure</span> <span m=''2101920''>inside</span> <span m=''2102440''>extend</span>
  <span m=''2103070''>dictionary,</span> <span m=''2103860''>which</span> <span m=''2104080''>is
  that--</span> <span m=''2104990''>if</span> <span m=''2105170''>one</span> <span
  m=''2105340''>of</span> <span m=''2105470''>these</span> <span m=''2105600''>pattern</span>
  <span m=''2105910''>variables</span> <span m=''2106330''>already</span> <span m=''2106700''>has</span>
  <span m=''2106990''>a</span> <span m=''2107050''>value</span> <span m=''2109200''>and</span>
  <span m=''2109390''>I''m</span> <span m=''2109520''>trying</span> <span m=''2109770''>to</span>
  <span m=''2109870''>match</span> <span m=''2110180''>the</span> <span m=''2110290''>thing</span>
  <span m=''2110690''>against</span> <span m=''2111040''>something</span> <span m=''2111550''>else</span>
  <span m=''2112810''>which</span> <span m=''2112990''>is</span> <span m=''2113110''>not</span>
  <span m=''2113370''>equivalent</span> <span m=''2113880''>to</span> <span m=''2113960''>the</span>
  <span m=''2114050''>one</span> <span m=''2114480''>that</span> <span m=''2114730''>I''ve</span>
  <span m=''2114970''>already</span> <span m=''2115140''>matched</span> <span m=''2115310''>it</span>
  <span m=''2115560''>against</span> <span m=''2115910''>once,</span> <span m=''2116420''>then</span>
  <span m=''2116580''>a</span> <span m=''2116630''>failure</span> <span m=''2117030''>will</span>
  <span m=''2117140''>come</span> <span m=''2117310''>flying</span> <span m=''2117670''>out</span>
  <span m=''2117760''>of</span> <span m=''2117840''>here,</span> <span m=''2118040''>too.</span>
  <span m=''2120220''>And</span> <span m=''2120380''>I</span> <span m=''2120420''>will</span>
  <span m=''2120570''>see</span> <span m=''2120780''>that</span> <span m=''2120970''>some</span>
  <span m=''2121170''>time.</span> </p><p><span m=''2122890''>And</span> <span m=''2123110''>finally,</span>
  <span m=''2123680''>an</span> <span m=''2123800''>arbitrary</span> <span m=''2124210''>expression</span>
  <span m=''2125240''>does</span> <span m=''2125400''>not</span> <span m=''2125610''>have</span>
  <span m=''2125740''>to</span> <span m=''2125850''>check</span> <span m=''2126140''>anything</span>
  <span m=''2126500''>syntactic</span> <span m=''2127080''>about</span> <span m=''2127280''>the</span>
  <span m=''2127470''>expression</span> <span m=''2128210''>that''s</span> <span m=''2128790''>being</span>
  <span m=''2129010''>matched,</span> <span m=''2130050''>so</span> <span m=''2130230''>all
  it</span> <span m=''2130500''>does</span> <span m=''2130890''>is it''s</span> <span
  m=''2131060''>an</span> <span m=''2131100''>extension</span> <span m=''2131510''>of</span>
  <span m=''2131590''>the</span> <span m=''2131670''>dictionary.</span> </p><p><span
  m=''2134355''>So</span> <span m=''2134780''>you''ve</span> <span m=''2135030''>just</span>
  <span m=''2135290''>seen</span> <span m=''2136360''>a</span> <span m=''2136470''>complete,</span>
  <span m=''2137160''>very</span> <span m=''2137520''>simple</span> <span m=''2137850''>matcher.</span>
  <span m=''2139300''>Now,</span> <span m=''2139470''>one</span> <span m=''2139640''>of</span>
  <span m=''2139700''>the</span> <span m=''2139750''>things</span> <span m=''2139990''>that''s</span>
  <span m=''2140140''>rather</span> <span m=''2140360''>remarkable</span> <span m=''2140890''>about</span>
  <span m=''2141170''>this</span> <span m=''2141640''>is</span> <span m=''2141810''>people</span>
  <span m=''2142060''>pay</span> <span m=''2142250''>an</span> <span m=''2142330''>awful</span>
  <span m=''2142610''>lot</span> <span m=''2142820''>of</span> <span m=''2142880''>money</span>
  <span m=''2143170''>these</span> <span m=''2143390''>days</span> <span m=''2144130''>for</span>
  <span m=''2144310''>someone</span> <span m=''2144670''>to</span> <span m=''2144790''>make</span>
  <span m=''2145400''>a,</span> <span m=''2145560''>quote,</span> <span m=''2145980''>AI</span>
  <span m=''2146440''>expert</span> <span m=''2146960''>system</span> <span m=''2148420''>that</span>
  <span m=''2148630''>has</span> <span m=''2148860''>nothing</span> <span m=''2149140''>more
  in</span> <span m=''2149440''>it</span> <span m=''2149680''>than</span> <span m=''2150010''>a</span>
  <span m=''2150050''>matcher</span> <span m=''2150490''>and</span> <span m=''2150560''>maybe</span>
  <span m=''2150800''>an</span> <span m=''2150860''>instantiater</span> <span m=''2151560''>like</span>
  <span m=''2151830''>this.</span> <span m=''2153470''>But</span> <span m=''2153630''>it''s</span>
  <span m=''2153760''>very</span> <span m=''2154080''>easy</span> <span m=''2154280''>to</span>
  <span m=''2154380''>do,</span> <span m=''2154800''>and</span> <span m=''2154970''>now,</span>
  <span m=''2155150''>of</span> <span m=''2155230''>course,</span> <span m=''2155450''>you</span>
  <span m=''2155540''>can</span> <span m=''2155630''>start up</span> <span m=''2155930''>a
  little</span> <span m=''2156130''>start-up</span> <span m=''2156390''>company</span>
  <span m=''2157410''>and</span> <span m=''2158170''>make</span> <span m=''2158530''>a</span>
  <span m=''2158640''>couple</span> <span m=''2158740''>of</span> <span m=''2158850''>megabucks</span>
  <span m=''2159070''>in</span> <span m=''2159500''>the</span> <span m=''2159740''>next</span>
  <span m=''2160110''>week</span> <span m=''2160310''>taking</span> <span m=''2160660''>some</span>
  <span m=''2160900''>people</span> <span m=''2161130''>for a</span> <span m=''2161360''>ride.</span>
  <span m=''2164690''>20</span> <span m=''2164970''>years</span> <span m=''2165220''>ago,</span>
  <span m=''2165430''>this</span> <span m=''2165570''>was</span> <span m=''2165680''>remarkable,</span>
  <span m=''2167510''>this</span> <span m=''2167730''>kind</span> <span m=''2167960''>of</span>
  <span m=''2168040''>program.</span> <span m=''2169610''>But</span> <span m=''2169920''>now,</span>
  <span m=''2170160''>this is</span> <span m=''2170380''>sort</span> <span m=''2170510''>of</span>
  <span m=''2170640''>easy.</span> <span m=''2171870''>You can teach  it to freshmen.</span>
  </p><p><span m=''2173660''>Well,</span> <span m=''2173820''>now</span> <span m=''2174000''>there''s</span>
  <span m=''2174150''>an</span> <span m=''2174260''>instantiater</span> <span m=''2175120''>as
  well.</span> <span m=''2179980''>The</span> <span m=''2180250''>problem</span> <span
  m=''2180630''>is</span> <span m=''2180700''>they''re</span> <span m=''2180850''>all</span>
  <span m=''2180970''>going</span> <span m=''2181130''>off and</span> <span m=''2181290''>making</span>
  <span m=''2181570''>more</span> <span m=''2181710''>money</span> <span m=''2181930''>than</span>
  <span m=''2182100''>I</span> <span m=''2182210''>do.</span> <span m=''2184190''>But</span>
  <span m=''2184640''>that''s</span> <span m=''2185200''>always</span> <span m=''2185430''>been</span>
  <span m=''2185600''>true</span> <span m=''2185760''>of</span> <span m=''2185920''>universities.</span>
  <span m=''2186660''>As</span> <span m=''2187320''>expression,</span> <span m=''2191410''>the</span>
  <span m=''2191660''>purpose</span> <span m=''2191900''>of</span> <span m=''2192140''>the</span>
  <span m=''2192350''>instantiater is</span> <span m=''2192740''>to</span> <span m=''2192830''>make</span>
  <span m=''2193140''>expressions</span> <span m=''2193870''>given</span> <span m=''2194090''>a</span>
  <span m=''2194160''>dictionary</span> <span m=''2198460''>and</span> <span m=''2198780''>a</span>
  <span m=''2198830''>skeleton.</span> <span m=''2204290''>And</span> <span m=''2204480''>that''s</span>
  <span m=''2204710''>not</span> <span m=''2204880''>very</span> <span m=''2205100''>hard</span>
  <span m=''2205350''>at</span> <span m=''2205550''>all.</span> <span m=''2206770''>We''ll</span>
  <span m=''2206910''>see</span> <span m=''2207090''>that</span> <span m=''2207730''>very</span>
  <span m=''2208020''>simply</span> <span m=''2208730''>in</span> <span m=''2208950''>the</span>
  <span m=''2209050''>next, the next</span> <span m=''2211140''>slide</span> <span
  m=''2212960''>here.</span> </p><p><span m=''2213590''>To</span> <span m=''2214040''>instantiate</span>
  <span m=''2214820''>a</span> <span m=''2214890''>skeleton,</span> <span m=''2216850''>given</span>
  <span m=''2217070''>a</span> <span m=''2217150''>particular</span> <span m=''2217570''>dictionary--</span>
  <span m=''2218230''>oh,</span> <span m=''2218510''>this</span> <span m=''2218690''>is</span>
  <span m=''2218830''>easy.</span> <span m=''2219650''>We''re</span> <span m=''2219790''>going</span>
  <span m=''2219890''>to</span> <span m=''2219990''>do</span> <span m=''2220140''>a</span>
  <span m=''2220230''>recursive</span> <span m=''2220790''>tree</span> <span m=''2221050''>walk</span>
  <span m=''2222250''>over</span> <span m=''2222420''>the</span> <span m=''2222590''>skeleton.</span>
  <span m=''2224050''>And</span> <span m=''2224260''>for</span> <span m=''2224360''>everything</span>
  <span m=''2224790''>which</span> <span m=''2224970''>is</span> <span m=''2225120''>a</span>
  <span m=''2225180''>skeleton</span> <span m=''2225970''>variable--</span> <span
  m=''2226540''>I don''t</span> <span m=''2226610''>know,</span> <span m=''2226800''>call
  it a</span> <span m=''2227130''>skeleton</span> <span m=''2227490''>evaluation.</span>
  <span m=''2228390''>That''s</span> <span m=''2228640''>the</span> <span m=''2228740''>name</span>
  <span m=''2229000''>and the</span> <span m=''2229140''>abstract</span> <span m=''2229690''>syntax</span>
  <span m=''2230025''>that I</span> <span m=''2230360''>give it in</span> <span m=''2230740''>this</span>
  <span m=''2230890''>program:</span> <span m=''2231640''>a</span> <span m=''2231750''>skeleton</span>
  <span m=''2232130''>evaluation,</span> <span m=''2232850''>a</span> <span m=''2232970''>thing</span>
  <span m=''2233250''>beginning</span> <span m=''2233610''>with</span> <span m=''2233700''>a</span>
  <span m=''2233780''>colon</span> <span m=''2235690''>in</span> <span m=''2235880''>the</span>
  <span m=''2236040''>rules.</span> <span m=''2238180''>For</span> <span m=''2238640''>anything</span>
  <span m=''2238790''>of</span> <span m=''2239090''>that</span> <span m=''2239420''>case,</span>
  <span m=''2239800''>I''m</span> <span m=''2239970''>going to</span> <span m=''2240190''>look</span>
  <span m=''2240400''>up</span> <span m=''2240550''>the</span> <span m=''2240750''>answer</span>
  <span m=''2241640''>in</span> <span m=''2241850''>the</span> <span m=''2241950''>dictionary,</span>
  <span m=''2242880''>and we''ll</span> <span m=''2242980''>worry</span> <span m=''2243300''>about</span>
  <span m=''2243530''>that</span> <span m=''2243640''>in</span> <span m=''2243740''>a</span>
  <span m=''2243780''>second.</span> <span m=''2244470''>Let''s</span> <span m=''2244690''>look</span>
  <span m=''2244800''>at</span> <span m=''2244900''>this</span> <span m=''2245100''>as</span>
  <span m=''2245230''>a</span> <span m=''2245290''>whole.</span> </p><p><span m=''2247700''>Here,</span>
  <span m=''2247930''>I</span> <span m=''2248150''>have--</span> <span m=''2248530''>I''m</span>
  <span m=''2248690''>going</span> <span m=''2248840''>to</span> <span m=''2248920''>instantiate</span>
  <span m=''2249900''>a</span> <span m=''2250010''>skeleton,</span> <span m=''2250860''>given</span>
  <span m=''2251120''>a</span> <span m=''2251190''>dictionary.</span> <span m=''2252740''>Well,</span>
  <span m=''2252950''>I''m</span> <span m=''2253040''>going</span> <span m=''2253120''>to</span>
  <span m=''2253200''>define</span> <span m=''2253600''>some</span> <span m=''2254790''>internal</span>
  <span m=''2255290''>loop</span> <span m=''2256550''>right</span> <span m=''2256790''>there,</span>
  <span m=''2258130''>and</span> <span m=''2258300''>it''s</span> <span m=''2258460''>going</span>
  <span m=''2258660''>to</span> <span m=''2258720''>do</span> <span m=''2258860''>something</span>
  <span m=''2259170''>very</span> <span m=''2259420''>simple.</span> <span m=''2260190''>Even
  if a skeleton--even</span> <span m=''2261720''>if a</span> <span m=''2261840''>skeleton</span>
  <span m=''2262300''>is</span> <span m=''2262470''>simple</span> <span m=''2262840''>and</span>
  <span m=''2262910''>atomic,</span> <span m=''2264600''>in</span> <span m=''2264760''>which</span>
  <span m=''2264960''>case</span> <span m=''2265200''>it''s</span> <span m=''2265330''>nothing</span>
  <span m=''2265630''>more</span> <span m=''2265780''>than</span> <span m=''2265920''>giving</span>
  <span m=''2266070''>the</span> <span m=''2266140''>skeleton</span> <span m=''2266450''>back</span>
  <span m=''2266810''>as</span> <span m=''2266940''>an answer,</span> <span m=''2268770''>or</span>
  <span m=''2269740''>in</span> <span m=''2270040''>the</span> <span m=''2270300''>general</span>
  <span m=''2270650''>case,</span> <span m=''2270960''>it''s</span> <span m=''2271140''>complicated,</span>
  <span m=''2272610''>in</span> <span m=''2272770''>which</span> <span m=''2272980''>case</span>
  <span m=''2273630''>I''m</span> <span m=''2273850''>going</span> <span m=''2274170''>to</span>
  <span m=''2274650''>make</span> <span m=''2275040''>up</span> <span m=''2276010''>the</span>
  <span m=''2276150''>expression</span> <span m=''2276900''>which</span> <span m=''2277190''>is</span>
  <span m=''2277300''>the</span> <span m=''2277400''>result</span> <span m=''2277655''>of</span>
  <span m=''2278440''>instantiating--</span> <span m=''2279360''>calling</span> <span
  m=''2279680''>this</span> <span m=''2279820''>loop</span> <span m=''2280060''>recursively--</span>
  <span m=''2281000''>instantiating</span> <span m=''2281730''>the</span> <span m=''2282130''>car</span>
  <span m=''2282460''>of</span> <span m=''2282540''>the</span> <span m=''2282610''>skeleton</span>
  <span m=''2283440''>and</span> <span m=''2283700''>the</span> <span m=''2283820''>cdr.</span>
  </p><p><span m=''2284870''>So</span> <span m=''2284970''>here</span> <span m=''2285140''>is
  a</span> <span m=''2285360''>recursive</span> <span m=''2285690''>tree</span> <span
  m=''2285900''>walk.</span> <span m=''2288090''>However,</span> <span m=''2288870''>if</span>
  <span m=''2289030''>it</span> <span m=''2289150''>turns</span> <span m=''2289460''>out</span>
  <span m=''2289890''>to</span> <span m=''2290050''>be</span> <span m=''2290640''>a</span>
  <span m=''2291000''>skeleton</span> <span m=''2291380''>evaluation,</span> <span
  m=''2291940''>a</span> <span m=''2292030''>colon</span> <span m=''2292410''>expression</span>
  <span m=''2293500''>in</span> <span m=''2293610''>the</span> <span m=''2293730''>skeleton,</span>
  <span m=''2294970''>then</span> <span m=''2295140''>what</span> <span m=''2295260''>I''m</span>
  <span m=''2295360''>going</span> <span m=''2295580''>to</span> <span m=''2295660''>do</span>
  <span m=''2296480''>is</span> <span m=''2298020''>find</span> <span m=''2298560''>the</span>
  <span m=''2298770''>expression</span> <span m=''2299380''>that''s</span> <span m=''2299790''>in</span>
  <span m=''2299970''>the</span> <span m=''2300050''>colon--</span> <span m=''2301520''>the</span>
  <span m=''2301630''>CADR</span> <span m=''2302050''>in</span> <span m=''2302130''>this</span>
  <span m=''2302290''>case.</span> <span m=''2302820''>It''s</span> <span m=''2303000''>a
  piece of</span> <span m=''2303240''>abstract</span> <span m=''2303730''>syntax</span>
  <span m=''2304140''>here,</span> <span m=''2304470''>so</span> <span m=''2304650''>I</span>
  <span m=''2304710''>can</span> <span m=''2304850''>change</span> <span m=''2305110''>my</span>
  <span m=''2305210''>representation</span> <span m=''2305780''>of</span> <span m=''2305880''>rules.</span>
  <span m=''2307480''>I''m</span> <span m=''2307610''>going</span> <span m=''2307770''>to</span>
  <span m=''2307920''>evaluate</span> <span m=''2308540''>that</span> <span m=''2309000''>relative</span>
  <span m=''2309275''>to</span> <span m=''2309550''>this</span> <span m=''2309970''>dictionary,</span>
  <span m=''2311330''>whatever</span> <span m=''2311710''>evaluation</span> <span
  m=''2312330''>means.</span> <span m=''2312940''>We''ll</span> <span m=''2313050''>find</span>
  <span m=''2313210''>out</span> <span m=''2313370''>a</span> <span m=''2313400''>lot</span>
  <span m=''2313580''>about</span> <span m=''2313780''>that</span> <span m=''2314010''>sometime.</span>
  <span m=''2316100''>And</span> <span m=''2316220''>the</span> <span m=''2316350''>result</span>
  <span m=''2316820''>of</span> <span m=''2317070''>that</span> <span m=''2317620''>is</span>
  <span m=''2317790''>my</span> <span m=''2317950''>answer.</span> <span m=''2319650''>so.</span>
  <span m=''2319830''>I</span> <span m=''2319940''>start</span> <span m=''2320200''>up</span>
  <span m=''2320360''>this</span> <span m=''2320520''>loop--</span> <span m=''2321010''>here''s</span>
  <span m=''2321160''>my</span> <span m=''2321360''>initialization--</span> <span
  m=''2322240''>by</span> <span m=''2322490''>calling</span> <span m=''2322850''>it
  with</span> <span m=''2322950''>the</span> <span m=''2323130''>whole</span> <span
  m=''2323310''>skeleton,</span> <span m=''2324400''>and</span> <span m=''2324520''>this
  will</span> <span m=''2324710''>just</span> <span m=''2324900''>do a</span> <span
  m=''2325030''>recursive</span> <span m=''2325450''>decomposition</span> <span m=''2326360''>into</span>
  <span m=''2326610''>pieces.</span> </p><p><span m=''2329690''>Now,</span> <span
  m=''2330930''>one</span> <span m=''2331170''>more</span> <span m=''2331400''>little</span>
  <span m=''2331680''>bit</span> <span m=''2331870''>of</span> <span m=''2332200''>detail</span>
  <span m=''2334130''>is</span> <span m=''2334800''>what</span> <span m=''2335090''>happens</span>
  <span m=''2335470''>inside</span> <span m=''2335830''>evaluate?</span> <span m=''2337130''>I</span>
  <span m=''2337300''>can''t</span> <span m=''2337630''>tell</span> <span m=''2337780''>you</span>
  <span m=''2337930''>that</span> <span m=''2338200''>in</span> <span m=''2338330''>great</span>
  <span m=''2338600''>detail.</span> <span m=''2340030''>I''ll</span> <span m=''2340200''>tell</span>
  <span m=''2340360''>you</span> <span m=''2340510''>a</span> <span m=''2340560''>little</span>
  <span m=''2340820''>bit</span> <span m=''2341000''>of</span> <span m=''2341160''>it.</span>
  <span m=''2341650''>Later,</span> <span m=''2341940''>we''re</span> <span m=''2342050''>going</span>
  <span m=''2342120''>to</span> <span m=''2342380''>see--look</span> <span m=''2342530''>into</span>
  <span m=''2342700''>this</span> <span m=''2342840''>in</span> <span m=''2342940''>much</span>
  <span m=''2343130''>more</span> <span m=''2343320''>detail.</span> <span m=''2344970''>To</span>
  <span m=''2345440''>evaluate</span> <span m=''2346710''>some</span> <span m=''2347500''>form,</span>
  <span m=''2348120''>some</span> <span m=''2348870''>expression</span> <span m=''2349490''>with</span>
  <span m=''2349610''>respect</span> <span m=''2349970''>to</span> <span m=''2350050''>a</span>
  <span m=''2350120''>dictionary,</span> <span m=''2351930''>if</span> <span m=''2352150''>the</span>
  <span m=''2352280''>expression</span> <span m=''2352860''>is</span> <span m=''2353130''>an</span>
  <span m=''2353230''>atomic</span> <span m=''2353660''>object,</span> <span m=''2355050''>well,</span>
  <span m=''2355300''>I''m going</span> <span m=''2355410''>to</span> <span m=''2355510''>go</span>
  <span m=''2355670''>look</span> <span m=''2355880''>it</span> <span m=''2355970''>up.</span>
  <span m=''2358620''>Nothing</span> <span m=''2358840''>very</span> <span m=''2359050''>exciting</span>
  <span m=''2359450''>there.</span> <span m=''2360610''>Otherwise,</span> <span m=''2361790''>I''m</span>
  <span m=''2361990''>going</span> <span m=''2362070''>to</span> <span m=''2362150''>do</span>
  <span m=''2362330''>something</span> <span m=''2362700''>complicated</span> <span
  m=''2363250''>here,</span> <span m=''2363900''>which</span> <span m=''2364140''>is</span>
  <span m=''2364280''>I''m</span> <span m=''2364430''>going</span> <span m=''2364650''>to</span>
  <span m=''2364780''>apply</span> <span m=''2365150''>a</span> <span m=''2365230''>procedure</span>
  <span m=''2366030''>which is</span> <span m=''2366280''>the</span> <span m=''2366380''>result</span>
  <span m=''2366790''>of</span> <span m=''2366890''>looking</span> <span m=''2367200''>up</span>
  <span m=''2367320''>the</span> <span m=''2367450''>operator</span> <span m=''2367920''>part</span>
  <span m=''2369460''>in</span> <span m=''2369670''>something</span> <span m=''2370040''>that</span>
  <span m=''2370140''>we''re</span> <span m=''2370220''>going</span> <span m=''2370290''>to</span>
  <span m=''2370360''>find</span> <span m=''2370590''>out</span> <span m=''2370820''>about</span>
  <span m=''2371090''>someday.</span> </p><p><span m=''2372150''>I</span> <span m=''2372310''>want</span>
  <span m=''2372470''>you</span> <span m=''2372600''>realize</span> <span m=''2372980''>you''re</span>
  <span m=''2373110''>seeing</span> <span m=''2373360''>magic</span> <span m=''2373780''>now.</span>
  <span m=''2374630''>This</span> <span m=''2374850''>magic will</span> <span m=''2375270''>become</span>
  <span m=''2375590''>clear</span> <span m=''2376370''>very</span> <span m=''2376610''>soon,</span>
  <span m=''2377770''>but</span> <span m=''2377910''>not</span> <span m=''2378110''>today.</span>
  <span m=''2380000''>Then I''m</span> <span m=''2380290''>looking at--looking</span>
  <span m=''2382320''>up</span> <span m=''2382440''>all</span> <span m=''2382620''>the</span>
  <span m=''2382710''>pieces,</span> <span m=''2383250''>all</span> <span m=''2383440''>the</span>
  <span m=''2383540''>arguments</span> <span m=''2383835''>to</span> <span m=''2384130''>that</span>
  <span m=''2385190''>in</span> <span m=''2385410''>the</span> <span m=''2385890''>dictionary.</span>
  <span m=''2388460''>So</span> <span m=''2388620''>I</span> <span m=''2388740''>don''t</span>
  <span m=''2388940''>want</span> <span m=''2389190''>you</span> <span m=''2389360''>to</span>
  <span m=''2389720''>look</span> <span m=''2389880''>at</span> <span m=''2390030''>this</span>
  <span m=''2390220''>in</span> <span m=''2390330''>detail.</span> <span m=''2391390''>I</span>
  <span m=''2391500''>want</span> <span m=''2391720''>you</span> <span m=''2392020''>to
  say that there''s</span> <span m=''2392360''>more</span> <span m=''2392630''>going</span>
  <span m=''2392910''>on</span> <span m=''2393150''>here,</span> <span m=''2393815''>and</span>
  <span m=''2394150''>we''re</span> <span m=''2394330''>going</span> <span m=''2394430''>to</span>
  <span m=''2394540''>see</span> <span m=''2394740''>more</span> <span m=''2396020''>about</span>
  <span m=''2396360''>this.</span> <span m=''2399000''>But it''s--</span> <span m=''2399490''>the</span>
  <span m=''2399620''>magic</span> <span m=''2400040''>is</span> <span m=''2400180''>going</span>
  <span m=''2400340''>to</span> <span m=''2400500''>stop.</span> <span m=''2402490''>This</span>
  <span m=''2402840''>part</span> <span m=''2403050''>has</span> <span m=''2403230''>to</span>
  <span m=''2403300''>do</span> <span m=''2403530''>with Lisp,</span> <span m=''2405296''>and</span>
  <span m=''2405760''>it''s</span> <span m=''2406120''>the</span> <span m=''2406230''>end</span>
  <span m=''2406460''>of</span> <span m=''2406800''>that.</span> </p><p><span m=''2410260''>OK,</span>
  <span m=''2410510''>so</span> <span m=''2410600''>now</span> <span m=''2410790''>we</span>
  <span m=''2410920''>know</span> <span m=''2411120''>about</span> <span m=''2412130''>matching</span>
  <span m=''2412600''>and</span> <span m=''2412720''>instantiation.</span> <span m=''2415040''>Are</span>
  <span m=''2415200''>there</span> <span m=''2415340''>any</span> <span m=''2415460''>questions</span>
  <span m=''2415940''>for</span> <span m=''2416040''>this</span> <span m=''2416160''>segment?</span>
  </p><p><span m=''2427936''>AUDIENCE: I have</span> <span m=''2428418''>a question.</span>
  </p><p><span m=''2429870''>PROFESSOR: Yes.</span> </p><p><span m=''2430880''>AUDIENCE:
  Is it possible</span> <span m=''2431100''>to bring up a</span> <span m=''2431310''>previous</span>
  <span m=''2431940''>slide?</span> <span m=''2433600''>It''s</span> <span m=''2433760''>about</span>
  <span m=''2434030''>this</span> <span m=''2434200''>define</span> <span m=''2434700''>match</span>
  <span m=''2435010''>pattern.</span> </p><p><span m=''2436160''>PROFESSOR: Yes.</span>
  <span m=''2437300''>You''d</span> <span m=''2437500''>like</span> <span m=''2437760''>to</span>
  <span m=''2437850''>see</span> <span m=''2438370''>the</span> <span m=''2438720''>overall</span>
  <span m=''2439320''>slide</span> <span m=''2439720''>define</span> <span m=''2440110''>match
  pattern.</span> <span m=''2440590''>Can</span> <span m=''2440690''>somebody</span>
  <span m=''2441010''>put</span> <span m=''2441160''>up</span> <span m=''2441360''>the--</span>
  <span m=''2441890''>no,</span> <span m=''2442170''>the</span> <span m=''2442410''>overhead.</span>
  <span m=''2442940''>That''s</span> <span m=''2443420''>the</span> <span m=''2443510''>biggest</span>
  <span m=''2444430''>scale</span> <span m=''2444790''>one.</span> <span m=''2445300''>What</span>
  <span m=''2445450''>part would you</span> <span m=''2445750''>like</span> <span
  m=''2445970''>to see?</span> </p><p><span m=''2447640''>AUDIENCE: Well,</span> <span
  m=''2448800''>the</span> <span m=''2449070''>top</span> <span m=''2449400''>would</span>
  <span m=''2449510''>be</span> <span m=''2449600''>fine.</span> <span m=''2449930''>Any</span>
  <span m=''2450110''>of</span> <span m=''2450200''>the</span> <span m=''2450280''>parts</span>
  <span m=''2450640''>where</span> <span m=''2450830''>you''re</span> <span m=''2452380''>passing</span>
  <span m=''2453270''>failed.</span> </p><p><span m=''2454540''>PROFESSOR: Yes.</span>
  </p><p><span m=''2456300''>AUDIENCE: The</span> <span m=''2456440''>idea</span>
  <span m=''2456750''>is</span> <span m=''2456850''>to</span> <span m=''2456940''>pass</span>
  <span m=''2457390''>failed</span> <span m=''2457790''>back</span> <span m=''2458070''>to</span>
  <span m=''2458170''>the</span> <span m=''2458250''>dictionary;</span> <span m=''2458625''>is
  that right?</span> </p><p><span m=''2459000''>PROFESSOR: The</span> <span m=''2459370''>dictionary</span>
  <span m=''2460010''>is</span> <span m=''2462150''>the</span> <span m=''2462290''>answer</span>
  <span m=''2462620''>to</span> <span m=''2462770''>a</span> <span m=''2462820''>match,</span>
  <span m=''2463910''>right?</span> <span m=''2465180''>And</span> <span m=''2465480''>it</span>
  <span m=''2465650''>is</span> <span m=''2465800''>either</span> <span m=''2468820''>some</span>
  <span m=''2469150''>mapping</span> <span m=''2471080''>or</span> <span m=''2472170''>there''s</span>
  <span m=''2472300''>no</span> <span m=''2472400''>match.</span> <span m=''2473150''>It</span>
  <span m=''2473450''>doesn''t</span> <span m=''2473700''>match.</span> </p><p><span
  m=''2474560''>AUDIENCE: Right.</span> </p><p><span m=''2475150''>PROFESSOR: So what</span>
  <span m=''2475400''>you''re</span> <span m=''2475580''>seeing</span> <span m=''2476020''>over</span>
  <span m=''2476140''>here</span> <span m=''2476760''>is,</span> <span m=''2477290''>in</span>
  <span m=''2477460''>fact,</span> <span m=''2478110''>because</span> <span m=''2478440''>the</span>
  <span m=''2478560''>fact</span> <span m=''2478830''>that</span> <span m=''2478950''>a</span>
  <span m=''2478990''>match</span> <span m=''2479300''>may</span> <span m=''2480050''>have</span>
  <span m=''2480550''>another</span> <span m=''2480890''>match</span> <span m=''2481230''>pass</span>
  <span m=''2481520''>in</span> <span m=''2481620''>the</span> <span m=''2481690''>dictionary,</span>
  <span m=''2482760''>as</span> <span m=''2482960''>you</span> <span m=''2483080''>see</span>
  <span m=''2483250''>in</span> <span m=''2483320''>the</span> <span m=''2483380''>general</span>
  <span m=''2483720''>case</span> <span m=''2484000''>down</span> <span m=''2484220''>here.</span>
  <span m=''2484950''>Here''s</span> <span m=''2485280''>the</span> <span m=''2485340''>general</span>
  <span m=''2485640''>case</span> <span m=''2486110''>where</span> <span m=''2486320''>a</span>
  <span m=''2486360''>match</span> <span m=''2486640''>passes</span> <span m=''2486930''>another</span>
  <span m=''2487180''>match to</span> <span m=''2487470''>the dictionary.</span> <span
  m=''2488090''>When</span> <span m=''2488200''>I</span> <span m=''2488320''>match</span>
  <span m=''2488670''>the</span> <span m=''2488800''>cdr''s,</span> <span m=''2489390''>I</span>
  <span m=''2489540''>match</span> <span m=''2489850''>them</span> <span m=''2489980''>in</span>
  <span m=''2490610''>the</span> <span m=''2491210''>dictionary</span> <span m=''2491860''>that</span>
  <span m=''2492560''>is</span> <span m=''2492720''>resulting</span> <span m=''2493170''>from</span>
  <span m=''2493280''>matching</span> <span m=''2493600''>the</span> <span m=''2493680''>car''s.</span>
  <span m=''2496070''>OK, that''s what I</span> <span m=''2496210''>have</span> <span
  m=''2496500''>here.</span> <span m=''2497180''>So</span> <span m=''2497400''>because</span>
  <span m=''2497760''>of</span> <span m=''2497840''>that,</span> <span m=''2498090''>if</span>
  <span m=''2498270''>the</span> <span m=''2499130''>match</span> <span m=''2499350''>of</span>
  <span m=''2499430''>the</span> <span m=''2499520''>car''s</span> <span m=''2499860''>fails,</span>
  <span m=''2501230''>then</span> <span m=''2501430''>it</span> <span m=''2501480''>may</span>
  <span m=''2501610''>be</span> <span m=''2501700''>necessary</span> <span m=''2502370''>that</span>
  <span m=''2502610''>the</span> <span m=''2503010''>match</span> <span m=''2503270''>of</span>
  <span m=''2503360''>the</span> <span m=''2503450''>cdr''s</span> <span m=''2504200''>propagates</span>
  <span m=''2504770''>that</span> <span m=''2505000''>failure,</span> <span m=''2505410''>and</span>
  <span m=''2505900''>that''s what</span> <span m=''2506080''>the</span> <span m=''2506260''>first</span>
  <span m=''2506540''>line is.</span> </p><p><span m=''2508570''>AUDIENCE: OK,</span>
  <span m=''2508990''>well,</span> <span m=''2509540''>I''m</span> <span m=''2509760''>still</span>
  <span m=''2510050''>unclear</span> <span m=''2510390''>what</span> <span m=''2510800''>matches--</span>
  <span m=''2511400''>what</span> <span m=''2511570''>comes</span> <span m=''2511840''>out</span>
  <span m=''2512010''>of</span> <span m=''2512880''>one</span> <span m=''2513390''>instance</span>
  <span m=''2513840''>of the</span> <span m=''2513920''>match?</span> </p><p><span
  m=''2514800''>PROFESSOR: One</span> <span m=''2515000''>of</span> <span m=''2515090''>two</span>
  <span m=''2515240''>possibilities.</span> <span m=''2516320''>Either</span> <span
  m=''2516630''>the</span> <span m=''2516750''>symbol</span> <span m=''2517390''>failed,</span>
  <span m=''2517990''>which</span> <span m=''2518210''>means</span> <span m=''2518400''>there</span>
  <span m=''2518580''>is</span> <span m=''2518670''>no</span> <span m=''2518840''>match.</span>
  </p><p><span m=''2519350''>AUDIENCE: Right.</span> </p><p><span m=''2519840''>PROFESSOR:
  Or</span> <span m=''2520580''>some</span> <span m=''2521230''>mapping,</span> <span
  m=''2522430''>which</span> <span m=''2522610''>is</span> <span m=''2522690''>an</span>
  <span m=''2522760''>abstract</span> <span m=''2523200''>thing</span> <span m=''2523360''>right</span>
  <span m=''2523600''>now,</span> <span m=''2523870''>and</span> <span m=''2524260''>you</span>
  <span m=''2524420''>should</span> <span m=''2524590''>know</span> <span m=''2524730''>about</span>
  <span m=''2524920''>the</span> <span m=''2524990''>structure</span> <span m=''2525420''>of</span>
  <span m=''2525520''>it,</span> <span m=''2526480''>which</span> <span m=''2526960''>relates</span>
  <span m=''2527590''>the</span> <span m=''2529460''>pattern</span> <span m=''2529950''>variables</span>
  <span m=''2531660''>to</span> <span m=''2531850''>their</span> <span m=''2532090''>values</span>
  <span m=''2532950''>as</span> <span m=''2533170''>picked</span> <span m=''2533370''>up</span>
  <span m=''2533510''>in</span> <span m=''2533590''>the</span> <span m=''2533660''>match.</span>
  </p><p><span m=''2534490''>AUDIENCE: OK,</span> <span m=''2535690''>so</span> <span
  m=''2536750''>it is--</span> </p><p><span m=''2536930''>PROFESSOR: That''s</span>
  <span m=''2537100''>constructed</span> <span m=''2537440''>by</span> <span m=''2537550''>extend</span>
  <span m=''2537825''>dictionary.</span> </p><p><span m=''2538810''>AUDIENCE: So</span>
  <span m=''2539350''>the</span> <span m=''2539800''>recursive</span> <span m=''2540860''>nature</span>
  <span m=''2541590''>brings</span> <span m=''2541880''>about</span> <span m=''2542060''>the</span>
  <span m=''2542240''>fact</span> <span m=''2542450''>that</span> <span m=''2542650''>if</span>
  <span m=''2543550''>ever</span> <span m=''2545000''>a</span> <span m=''2545050''>failed</span>
  <span m=''2545530''>gets</span> <span m=''2545730''>passed</span> <span m=''2546110''>out</span>
  <span m=''2546220''>of</span> <span m=''2546360''>any</span> <span m=''2547650''>calling</span>
  <span m=''2548160''>of</span> <span m=''2548290''>match,</span> <span m=''2548710''>then</span>
  <span m=''2548810''>the</span> <span m=''2548890''>first</span> <span m=''2549240''>condition</span>
  <span m=''2549680''>will</span> <span m=''2549810''>pick</span> <span m=''2550030''>it</span>
  <span m=''2550130''>up--</span> </p><p><span m=''2550430''>PROFESSOR: And</span>
  <span m=''2550650''>just</span> <span m=''2551120''>propagate it</span> <span m=''2551600''>along</span>
  <span m=''2551880''>without</span> <span m=''2552090''>any</span> <span m=''2552240''>further</span>
  <span m=''2552820''>ado,</span> <span m=''2553300''>right.</span> </p><p><span m=''2553530''>AUDIENCE:
  Oh,</span> <span m=''2553870''>right.</span> <span m=''2554370''>OK.</span> </p><p><span
  m=''2555460''>PROFESSOR: That''s just</span> <span m=''2555740''>the</span> <span
  m=''2555810''>fastest</span> <span m=''2556100''>way</span> <span m=''2556240''>to</span>
  <span m=''2556300''>get</span> <span m=''2556470''>that</span> <span m=''2556650''>failure</span>
  <span m=''2556960''>out</span> <span m=''2557060''>of</span> <span m=''2557160''>there.</span>
  <span m=''2563260''>Yes.</span> </p><p><span m=''2563850''>AUDIENCE: If</span> <span
  m=''2564410''>I</span> <span m=''2564570''>don''t</span> <span m=''2564980''>fail,</span>
  <span m=''2565380''>that</span> <span m=''2565550''>means</span> <span m=''2565850''>that</span>
  <span m=''2565930''>I''ve</span> <span m=''2566140''>matched</span> <span m=''2566460''>a</span>
  <span m=''2566530''>pattern,</span> <span m=''2567800''>and</span> <span m=''2568020''>I</span>
  <span m=''2568210''>run</span> <span m=''2568440''>the</span> <span m=''2568520''>procedure</span>
  <span m=''2568970''>extend</span> <span m=''2569650''>dict</span> <span m=''2570930''>and</span>
  <span m=''2571030''>then</span> <span m=''2571230''>pass in</span> <span m=''2571620''>the</span>
  <span m=''2571700''>pattern</span> <span m=''2572120''>in</span> <span m=''2572220''>the</span>
  <span m=''2572310''>expression.</span> <span m=''2575270''>But</span> <span m=''2575430''>the</span>
  <span m=''2575630''>substitution</span> <span m=''2576300''>will</span> <span m=''2576410''>not</span>
  <span m=''2576590''>be</span> <span m=''2576710''>made</span> <span m=''2576990''>at</span>
  <span m=''2577070''>that</span> <span m=''2577290''>point;</span> <span m=''2577920''>is</span>
  <span m=''2577990''>that</span> <span m=''2578140''>right?</span> <span m=''2578400''>I''m</span>
  <span m=''2578570''>just--</span> </p><p><span m=''2579110''>PROFESSOR: No, no.</span>
  <span m=''2579420''>There''s</span> <span m=''2579580''>no</span> <span m=''2579730''>substitution</span>
  <span m=''2580220''>being</span> <span m=''2580380''>there</span> <span m=''2580630''>because
  there''s</span> <span m=''2580770''>no</span> <span m=''2580960''>skeleton</span>
  <span m=''2581470''>to</span> <span m=''2581540''>be</span> <span m=''2581650''>substituted</span>
  <span m=''2581965''>in.</span> </p><p><span m=''2582520''>AUDIENCE: Right.</span>
  <span m=''2582950''>So what--</span> </p><p><span m=''2583070''>PROFESSOR: All</span>
  <span m=''2583380''>you''ve</span> <span m=''2583500''>got</span> <span m=''2583780''>there</span>
  <span m=''2584010''>is</span> <span m=''2584110''>we''re</span> <span m=''2584250''>making</span>
  <span m=''2584550''>up</span> <span m=''2584660''>the</span> <span m=''2584760''>dictionary</span>
  <span m=''2585400''>for</span> <span m=''2585690''>later</span> <span m=''2586270''>substitution.</span>
  </p><p><span m=''2588270''>AUDIENCE: And</span> <span m=''2588770''>what</span>
  <span m=''2589330''>would</span> <span m=''2589550''>the</span> <span m=''2589630''>dictionary</span>
  <span m=''2590250''>look</span> <span m=''2590470''>like?</span> <span m=''2590680''>Is</span>
  <span m=''2590800''>it</span> <span m=''2591200''>ordered</span> <span m=''2591560''>pairs?</span>
  </p><p><span m=''2593540''>PROFESSOR: That''s--that''s</span> <span m=''2595160''>not</span>
  <span m=''2595360''>told</span> <span m=''2595590''>to</span> <span m=''2595680''>you.</span>
  <span m=''2595940''>We''re</span> <span m=''2596070''>being</span> <span m=''2596300''>abstract.</span>
  </p><p><span m=''2596700''>AUDIENCE: OK.</span> </p><p><span m=''2597650''>PROFESSOR:
  Why</span> <span m=''2597860''>do</span> <span m=''2597950''>you</span> <span m=''2598030''>want</span>
  <span m=''2598160''>to</span> <span m=''2598290''>know?</span> <span m=''2598850''>What</span>
  <span m=''2599135''>it is,</span> <span m=''2599710''>it''s a</span> <span m=''2599810''>function.</span>
  <span m=''2600075''>It''s a</span> <span m=''2600340''>function.</span> </p><p><span
  m=''2601330''>AUDIENCE: Well,</span> <span m=''2601500''>the</span> <span m=''2601580''>reason
  I want to know is--</span> </p><p><span m=''2602090''>PROFESSOR: A</span> <span
  m=''2602280''>function</span> <span m=''2602820''>abstractly</span> <span m=''2603130''>is</span>
  <span m=''2603250''>a</span> <span m=''2603300''>set</span> <span m=''2603480''>of</span>
  <span m=''2603570''>ordered</span> <span m=''2603820''>pairs.</span> <span m=''2605130''>It</span>
  <span m=''2605320''>could</span> <span m=''2605510''>be</span> <span m=''2605820''>implemented</span>
  <span m=''2606430''>as</span> <span m=''2606730''>a</span> <span m=''2606810''>set</span>
  <span m=''2607090''>of</span> <span m=''2607470''>list</span> <span m=''2607940''>pairs.</span>
  <span m=''2609040''>It</span> <span m=''2609380''>could</span> <span m=''2609570''>be</span>
  <span m=''2609670''>implemented</span> <span m=''2610360''>as</span> <span m=''2610620''>some</span>
  <span m=''2610870''>fancy</span> <span m=''2611340''>table</span> <span m=''2611680''>mechanism.</span>
  <span m=''2612590''>It</span> <span m=''2612740''>could</span> <span m=''2612880''>be</span>
  <span m=''2612990''>implemented</span> <span m=''2613490''>as</span> <span m=''2613610''>a</span>
  <span m=''2613650''>function.</span> <span m=''2615780''>And</span> <span m=''2615900''>somehow,</span>
  <span m=''2616180''>I''m</span> <span m=''2616300''>building</span> <span m=''2616650''>up</span>
  <span m=''2616770''>a</span> <span m=''2616840''>function.</span> <span m=''2618500''>But</span>
  <span m=''2618910''>I''m</span> <span m=''2619270''>not</span> <span m=''2619420''>telling</span>
  <span m=''2619720''>you.</span> <span m=''2620560''>That''s</span> <span m=''2621120''>up</span>
  <span m=''2621250''>to</span> <span m=''2621350''>George,</span> <span m=''2622090''>who''s</span>
  <span m=''2622240''>going</span> <span m=''2622330''>to</span> <span m=''2622420''>build</span>
  <span m=''2622630''>that</span> <span m=''2622810''>later.</span> </p><p><span m=''2629430''>I</span>
  <span m=''2629690''>know</span> <span m=''2629870''>you</span> <span m=''2630040''>really</span>
  <span m=''2630320''>badly</span> <span m=''2630630''>want</span> <span m=''2630740''>to</span>
  <span m=''2630860''>write</span> <span m=''2631070''>concrete</span> <span m=''2631560''>things.</span>
  <span m=''2632470''>I''m</span> <span m=''2632620''>not</span> <span m=''2633250''>going</span>
  <span m=''2633310''>to</span> <span m=''2633370''>let</span> <span m=''2633560''>you</span>
  <span m=''2633720''>do</span> <span m=''2633870''>that.</span> </p><p><span m=''2634280''>AUDIENCE:
  Well,</span> <span m=''2634690''>let</span> <span m=''2634800''>me</span> <span
  m=''2634920''>at</span> <span m=''2635070''>least</span> <span m=''2635230''>ask,</span>
  <span m=''2635500''>what</span> <span m=''2635730''>is</span> <span m=''2635880''>the</span>
  <span m=''2636020''>important</span> <span m=''2636410''>information</span> <span
  m=''2636725''>there</span> <span m=''2637040''>that''s</span> <span m=''2637320''>being</span>
  <span m=''2637530''>passed</span> <span m=''2638310''>to</span> <span m=''2638590''>extend</span>
  <span m=''2639050''>dict?</span> <span m=''2639750''>I</span> <span m=''2639820''>want</span>
  <span m=''2640030''>to</span> <span m=''2640090''>pass</span> <span m=''2640630''>the</span>
  <span m=''2640810''>pattern</span> <span m=''2641200''>I</span> <span m=''2641330''>found--</span>
  </p><p><span m=''2641720''>PROFESSOR: Yes.</span> <span m=''2642630''>The</span>
  <span m=''2642790''>pattern that''s</span> <span m=''2643280''>matched</span> <span
  m=''2643670''>against</span> <span m=''2644080''>the</span> <span m=''2644170''>expression.</span>
  <span m=''2644870''>You</span> <span m=''2645660''>want</span> <span m=''2645760''>to</span>
  <span m=''2645870''>have</span> <span m=''2646320''>the</span> <span m=''2646560''>pattern,</span>
  <span m=''2646880''>which</span> <span m=''2647010''>happens</span> <span m=''2647290''>to</span>
  <span m=''2647330''>be</span> <span m=''2647450''>in</span> <span m=''2647490''>those</span>
  <span m=''2647680''>cases</span> <span m=''2648180''>pattern</span> <span m=''2648520''>variables,</span>
  <span m=''2649810''>right?</span> <span m=''2649970''>All</span> <span m=''2650180''>of</span>
  <span m=''2650240''>those</span> <span m=''2650450''>three</span> <span m=''2650620''>cases</span>
  <span m=''2650880''>for</span> <span m=''2651030''>extend</span> <span m=''2651420''>dict</span>
  <span m=''2651900''>are</span> <span m=''2652070''>pattern</span> <span m=''2652400''>variables.</span>
  </p><p><span m=''2653220''>AUDIENCE: Right.</span> </p><p><span m=''2654090''>PROFESSOR:
  So you</span> <span m=''2654390''>have</span> <span m=''2654580''>a</span> <span
  m=''2654750''>pattern</span> <span m=''2655050''>variable</span> <span m=''2655510''>that</span>
  <span m=''2655680''>is</span> <span m=''2655810''>to</span> <span m=''2655910''>be</span>
  <span m=''2656370''>given</span> <span m=''2656720''>a</span> <span m=''2656840''>value</span>
  <span m=''2657930''>in</span> <span m=''2658070''>a</span> <span m=''2658120''>dictionary.</span>
  </p><p><span m=''2658965''>AUDIENCE: Mm-hmm.</span> </p><p><span m=''2659250''>PROFESSOR:
  The</span> <span m=''2659620''>value</span> <span m=''2660050''>is</span> <span
  m=''2660170''>the</span> <span m=''2660250''>expression</span> <span m=''2661040''>that
  it</span> <span m=''2661460''>matched</span> <span m=''2661760''>against.</span>
  <span m=''2662870''>The</span> <span m=''2663480''>dictionary</span> <span m=''2664650''>is</span>
  <span m=''2664920''>the</span> <span m=''2666180''>set</span> <span m=''2666440''>of</span>
  <span m=''2666510''>things</span> <span m=''2666730''>I''ve</span> <span m=''2666860''>already</span>
  <span m=''2667260''>figured</span> <span m=''2667610''>out</span> <span m=''2667840''>that</span>
  <span m=''2667930''>I</span> <span m=''2668020''>have</span> <span m=''2668370''>memorized</span>
  <span m=''2669160''>or</span> <span m=''2669240''>learned.</span> <span m=''2670195''>And</span>
  <span m=''2670600''>I</span> <span m=''2670670''>am</span> <span m=''2670870''>going</span>
  <span m=''2670930''>to</span> <span m=''2670990''>make</span> <span m=''2671140''>a</span>
  <span m=''2671200''>new</span> <span m=''2671360''>dictionary,</span> <span m=''2671860''>which</span>
  <span m=''2672040''>is</span> <span m=''2672140''>extended</span> <span m=''2673250''>from</span>
  <span m=''2673470''>the</span> <span m=''2673570''>original</span> <span m=''2673980''>one</span>
  <span m=''2674980''>by</span> <span m=''2675230''>having</span> <span m=''2675650''>that</span>
  <span m=''2675910''>pattern</span> <span m=''2676210''>variable</span> <span m=''2676870''>have</span>
  <span m=''2676980''>a</span> <span m=''2677090''>value</span> <span m=''2677510''>with
  the</span> <span m=''2677740''>new</span> <span m=''2677870''>dictionary.</span>
  </p><p><span m=''2679880''>AUDIENCE: I</span> <span m=''2679920''>guess</span> <span
  m=''2680170''>what</span> <span m=''2680280''>I</span> <span m=''2680340''>don''t</span>
  <span m=''2680410''>understand</span> <span m=''2680725''>is</span> <span m=''2681040''>why</span>
  <span m=''2681220''>can''t</span> <span m=''2681500''>the</span> <span m=''2681580''>substitution</span>
  <span m=''2681965''>be</span> <span m=''2682350''>made</span> <span m=''2682500''>right</span>
  <span m=''2682840''>as</span> <span m=''2683070''>soon</span> <span m=''2683220''>as
  you find--</span> </p><p><span m=''2683450''>PROFESSOR: How do</span> <span m=''2683810''>I
  know what</span> <span m=''2684020''>I''m</span> <span m=''2684180''>going to</span>
  <span m=''2684300''>substitute?</span> <span m=''2684760''>I</span> <span m=''2684900''>don''t</span>
  <span m=''2685380''>know anything</span> <span m=''2685540''>about</span> <span
  m=''2685690''>this</span> <span m=''2686020''>skeleton.</span> <span m=''2687590''>This</span>
  <span m=''2687810''>pattern,</span> <span m=''2688130''>this</span> <span m=''2688240''>matcher</span>
  <span m=''2688590''>is</span> <span m=''2688680''>an</span> <span m=''2688790''>independent</span>
  <span m=''2689190''>unit.</span> </p><p><span m=''2689550''>AUDIENCE: Oh,</span>
  <span m=''2689935''>I see.</span> <span m=''2690320''>OK.</span> </p><p><span m=''2691090''>PROFESSOR:
  Right?</span> </p><p><span m=''2691350''>AUDIENCE: Yeah.</span> </p><p><span m=''2692330''>PROFESSOR:
  I</span> <span m=''2692450''>take</span> <span m=''2692710''>the</span> <span m=''2692790''>matcher.</span>
  <span m=''2693200''>I</span> <span m=''2693310''>apply</span> <span m=''2693670''>the</span>
  <span m=''2693710''>matcher.</span> <span m=''2694170''>If</span> <span m=''2694420''>it</span>
  <span m=''2694510''>matches,</span> <span m=''2694860''>then</span> <span m=''2695120''>it</span>
  <span m=''2695360''>was</span> <span m=''2695490''>worth</span> <span m=''2695680''>doing</span>
  <span m=''2696470''>instantiation.</span> </p><p><span m=''2697532''>AUDIENCE: OK,</span>
  <span m=''2698024''>good.</span> <span m=''2698516''>Yeah.</span> </p><p><span m=''2699008''>PROFESSOR:
  OK?</span> </p><p><span m=''2700484''>AUDIENCE: Can you</span> <span m=''2700980''>just
  do</span> <span m=''2701260''>that</span> <span m=''2701780''>answer</span> <span
  m=''2702190''>again</span> <span m=''2702450''>using</span> <span m=''2702740''>that</span>
  <span m=''2702880''>example</span> <span m=''2703330''>on</span> <span m=''2703440''>the</span>
  <span m=''2703520''>board?</span> <span m=''2704940''>You</span> <span m=''2705030''>know,</span>
  <span m=''2705130''>what</span> <span m=''2705550''>you</span> <span m=''2705650''>just</span>
  <span m=''2705850''>passed</span> <span m=''2706120''>back to the matcher.</span>
  </p><p><span m=''2706390''>PROFESSOR: Oh</span> <span m=''2706530''>yes.</span>
  <span m=''2706900''>OK,</span> <span m=''2707660''>yes.</span> <span m=''2708480''>You''re</span>
  <span m=''2708600''>looking</span> <span m=''2708850''>at</span> <span m=''2708940''>this</span>
  <span m=''2709110''>example.</span> <span m=''2710660''>At</span> <span m=''2710880''>this</span>
  <span m=''2711100''>point</span> <span m=''2711390''>when</span> <span m=''2711520''>I''m</span>
  <span m=''2711650''>traversing</span> <span m=''2712250''>this</span> <span m=''2712840''>structure,</span>
  <span m=''2714270''>I</span> <span m=''2714470''>get to</span> <span m=''2714690''>here:</span>
  <span m=''2715220''>x.</span> <span m=''2716630''>I</span> <span m=''2716820''>have</span>
  <span m=''2717000''>some</span> <span m=''2717200''>dictionary,</span> <span m=''2717650''>presumably</span>
  <span m=''2718190''>an</span> <span m=''2718260''>empty</span> <span m=''2718530''>dictionary
  at</span> <span m=''2718990''>this</span> <span m=''2719170''>point</span> <span
  m=''2719370''>if this is</span> <span m=''2719420''>the whole</span> <span m=''2719890''>expression.</span>
  <span m=''2722020''>So I</span> <span m=''2722340''>have an</span> <span m=''2722490''>empty</span>
  <span m=''2722610''>dictionary,</span> <span m=''2723530''>and I''ve matched</span>
  <span m=''2724140''>x</span> <span m=''2724500''>against</span> <span m=''2724940''>3.</span>
  <span m=''2726550''>So</span> <span m=''2726700''>now,</span> <span m=''2727080''>after</span>
  <span m=''2727410''>this</span> <span m=''2727660''>point,</span> <span m=''2728110''>the</span>
  <span m=''2728340''>dictionary</span> <span m=''2728850''>contains</span> <span
  m=''2730630''>x is</span> <span m=''2731000''>3,</span> <span m=''2733340''>OK?</span>
  </p><p><span m=''2733550''>Now,</span> <span m=''2733820''>I</span> <span m=''2733920''>continue</span>
  <span m=''2734350''>walking</span> <span m=''2734650''>along</span> <span m=''2734910''>here.</span>
  <span m=''2735290''>I</span> <span m=''2735400''>see</span> <span m=''2735590''>y.</span>
  <span m=''2737040''>Now,</span> <span m=''2737180''>this</span> <span m=''2737320''>is</span>
  <span m=''2737720''>a</span> <span m=''2737910''>particular</span> <span m=''2738390''>x,</span>
  <span m=''2738580''>a</span> <span m=''2738630''>pattern</span> <span m=''2739000''>x.</span>
  <span m=''2739780''>I</span> <span m=''2739930''>see</span> <span m=''2740140''>y,</span>
  <span m=''2740470''>a</span> <span m=''2740540''>pattern</span> <span m=''2740940''>y.</span>
  <span m=''2741690''>The</span> <span m=''2742260''>dictionary</span> <span m=''2742760''>says,</span>
  <span m=''2743470''>oh</span> <span m=''2743620''>yes,</span> <span m=''2744550''>the</span>
  <span m=''2745060''>pattern</span> <span m=''2745400''>y</span> <span m=''2746190''>is</span>
  <span m=''2746500''>the</span> <span m=''2747180''>symbol</span> <span m=''2747590''>x</span>
  <span m=''2748940''>because</span> <span m=''2749130''>I''ve</span> <span m=''2750020''>got</span>
  <span m=''2750220''>a</span> <span m=''2750580''>match</span> <span m=''2750960''>there.</span>
  <span m=''2752360''>So</span> <span m=''2752530''>the</span> <span m=''2752710''>dictionary
  now</span> <span m=''2753190''>contains</span> <span m=''2753280''>at</span> <span
  m=''2753420''>this</span> <span m=''2753590''>point</span> <span m=''2753860''>two</span>
  <span m=''2754040''>entries.</span> <span m=''2755380''>The</span> <span m=''2755540''>pattern</span>
  <span m=''2755880''>x</span> <span m=''2756140''>is</span> <span m=''2757010''>3,</span>
  <span m=''2757790''>and</span> <span m=''2757900''>the</span> <span m=''2758010''>pattern</span>
  <span m=''2758330''>y</span> <span m=''2758940''>is</span> <span m=''2759100''>the</span>
  <span m=''2759180''>expression</span> <span m=''2759650''>x.</span> <span m=''2762180''>Now,</span>
  <span m=''2762410''>I</span> <span m=''2762510''>get</span> <span m=''2762740''>that,</span>
  <span m=''2763140''>I can</span> <span m=''2763160''>walk</span> <span m=''2763400''>along</span>
  <span m=''2763660''>further.</span> <span m=''2764230''>I</span> <span m=''2764380''>say,</span>
  <span m=''2764830''>oh,</span> <span m=''2765860''>pattern</span> <span m=''2766180''>y</span>
  <span m=''2766360''>also</span> <span m=''2766610''>wants</span> <span m=''2766630''>to</span>
  <span m=''2766810''>be</span> <span m=''2767010''>4.</span> <span m=''2768100''>But
  that isn''t</span> <span m=''2768540''>possible,</span> <span m=''2769920''>producing
  a</span> <span m=''2770250''>failure.</span> <span m=''2774340''>Thank</span> <span
  m=''2774590''>you.</span> <span m=''2774830''>Let''s</span> <span m=''2775070''>take
  a</span> <span m=''2775290''>break.</span> </p><p><span m=''2822380''>OK,</span>
  <span m=''2823280''>you''re</span> <span m=''2823530''>seeing</span> <span m=''2823900''>your
  first</span> <span m=''2824240''>very</span> <span m=''2824500''>big</span> <span
  m=''2824720''>and</span> <span m=''2824800''>hairy</span> <span m=''2825140''>program.</span>
  <span m=''2827020''>Now,</span> <span m=''2827240''>of</span> <span m=''2827450''>course,</span>
  <span m=''2827780''>one</span> <span m=''2828050''>of</span> <span m=''2828180''>the</span>
  <span m=''2828300''>goals</span> <span m=''2828690''>of</span> <span m=''2828860''>this</span>
  <span m=''2829040''>subsegment</span> <span m=''2830080''>is</span> <span m=''2830290''>to</span>
  <span m=''2830380''>get</span> <span m=''2830590''>you</span> <span m=''2830750''>to
  be</span> <span m=''2830890''>able to</span> <span m=''2831080''>read</span> <span
  m=''2831350''>something</span> <span m=''2831710''>like</span> <span m=''2831910''>this</span>
  <span m=''2832050''>and</span> <span m=''2832140''>not</span> <span m=''2832330''>be</span>
  <span m=''2832440''>afraid</span> <span m=''2832770''>of</span> <span m=''2832870''>it.</span>
  <span m=''2833760''>This</span> <span m=''2833980''>one''s</span> <span m=''2834190''>only</span>
  <span m=''2834420''>about</span> <span m=''2834690''>four</span> <span m=''2834900''>pages</span>
  <span m=''2835860''>of</span> <span m=''2835980''>code.</span> <span m=''2836715''>By</span>
  <span m=''2837050''>the end of the</span> <span m=''2837300''>subject,</span> <span
  m=''2837730''>I</span> <span m=''2837810''>hope a</span> <span m=''2838040''>50-page</span>
  <span m=''2838640''>program</span> <span m=''2840300''>will</span> <span m=''2840460''>not</span>
  <span m=''2840690''>look</span> <span m=''2840850''>particularly</span> <span m=''2841270''>frightening.</span>
  <span m=''2842510''>But</span> <span m=''2842880''>I</span> <span m=''2843100''>don''t</span>
  <span m=''2843380''>expect-- and</span> <span m=''2843860''>I</span> <span m=''2843990''>don''t</span>
  <span m=''2844170''>want you</span> <span m=''2844480''>to</span> <span m=''2844530''>think</span>
  <span m=''2844950''>that</span> <span m=''2845200''>I</span> <span m=''2845310''>expect</span>
  <span m=''2845720''>you</span> <span m=''2845830''>to</span> <span m=''2845940''>be</span>
  <span m=''2846690''>getting</span> <span m=''2847080''>it</span> <span m=''2847300''>as</span>
  <span m=''2847510''>it''s</span> <span m=''2847670''>coming</span> <span m=''2848020''>out.</span>
  <span m=''2849200''>You''re</span> <span m=''2849380''>supposed</span> <span m=''2849520''>to</span>
  <span m=''2849660''>feel the</span> <span m=''2850000''>flavor</span> <span m=''2850325''>of</span>
  <span m=''2850650''>this,</span> <span m=''2851370''>OK?</span> <span m=''2851760''>And</span>
  <span m=''2851940''>then you''re</span> <span m=''2852090''>supposed</span> <span
  m=''2852350''>to</span> <span m=''2852610''>think</span> <span m=''2852860''>about</span>
  <span m=''2853160''>it</span> <span m=''2853210''>because</span> <span m=''2853430''>it</span>
  <span m=''2853560''>is</span> <span m=''2853740''>a</span> <span m=''2853800''>big</span>
  <span m=''2854000''>program.</span> <span m=''2855220''>There''s</span> <span m=''2855590''>a</span>
  <span m=''2855640''>lot</span> <span m=''2856030''>of</span> <span m=''2856100''>stuff</span>
  <span m=''2857080''>inside</span> <span m=''2857560''>this</span> <span m=''2858390''>program.</span>
  </p><p><span m=''2860812''>Now,</span> <span m=''2861300''>I''ve</span> <span m=''2861500''>told</span>
  <span m=''2861810''>you</span> <span m=''2861970''>about</span> <span m=''2862490''>the</span>
  <span m=''2863020''>language</span> <span m=''2863500''>we''re</span> <span m=''2863730''>implementing,</span>
  <span m=''2864400''>the</span> <span m=''2864560''>pattern</span> <span m=''2865070''>match</span>
  <span m=''2865280''>substitution</span> <span m=''2865550''>language.</span> <span
  m=''2866770''>I showed you</span> <span m=''2867140''>some</span> <span m=''2867280''>rules.</span>
  <span m=''2868320''>And</span> <span m=''2868460''>I''ve</span> <span m=''2868540''>told</span>
  <span m=''2868830''>you</span> <span m=''2868940''>about</span> <span m=''2869440''>matching</span>
  <span m=''2870010''>and</span> <span m=''2870270''>instantiation,</span> <span m=''2871490''>which
  are</span> <span m=''2871680''>the</span> <span m=''2871820''>two</span> <span m=''2871990''>halves</span>
  <span m=''2872340''>of</span> <span m=''2872470''>how</span> <span m=''2872640''>a</span>
  <span m=''2872750''>rule</span> <span m=''2872980''>works.</span> <span m=''2874240''>Now</span>
  <span m=''2874420''>we</span> <span m=''2874490''>have</span> <span m=''2874600''>to</span>
  <span m=''2874670''>understand</span> <span m=''2875140''>the</span> <span m=''2875390''>control</span>
  <span m=''2875810''>structure</span> <span m=''2876700''>by</span> <span m=''2876980''>which</span>
  <span m=''2877230''>the</span> <span m=''2877350''>rules</span> <span m=''2877690''>are</span>
  <span m=''2877940''>applied</span> <span m=''2879025''>to</span> <span m=''2879400''>the</span>
  <span m=''2879610''>expressions</span> <span m=''2880920''>so</span> <span m=''2881290''>as</span>
  <span m=''2881500''>to</span> <span m=''2882350''>do</span> <span m=''2883220''>algebraic</span>
  <span m=''2883680''>simplification.</span> </p><p><span m=''2886960''>Now,</span>
  <span m=''2887400''>that''s</span> <span m=''2887980''>also</span> <span m=''2888440''>a</span>
  <span m=''2888510''>big</span> <span m=''2888720''>complicated</span> <span m=''2889310''>mess.</span>
  <span m=''2892060''>The</span> <span m=''2892220''>problem</span> <span m=''2892670''>is</span>
  <span m=''2893430''>that</span> <span m=''2893820''>there</span> <span m=''2894220''>is</span>
  <span m=''2894560''>a</span> <span m=''2894730''>variety</span> <span m=''2895330''>of</span>
  <span m=''2895430''>interlocking,</span> <span m=''2896450''>interwoven</span> <span
  m=''2897450''>loops,</span> <span m=''2897820''>if</span> <span m=''2897950''>you</span>
  <span m=''2898090''>will,</span> <span m=''2898620''>involved</span> <span m=''2899160''>in</span>
  <span m=''2899230''>this.</span> <span m=''2900140''>For</span> <span m=''2900290''>one</span>
  <span m=''2900570''>thing,</span> <span m=''2901270''>I have to</span> <span m=''2901640''>apply--</span>
  <span m=''2902540''>I have to</span> <span m=''2903010''>examine</span> <span m=''2903610''>every</span>
  <span m=''2903880''>subexpression</span> <span m=''2905270''>of</span> <span m=''2905470''>my</span>
  <span m=''2905640''>expression</span> <span m=''2905910''>that</span> <span m=''2906180''>I''m</span>
  <span m=''2906260''>trying</span> <span m=''2906380''>to</span> <span m=''2906490''>simplify.</span>
  <span m=''2909070''>That</span> <span m=''2909290''>we</span> <span m=''2909420''>know
  how</span> <span m=''2909530''>to</span> <span m=''2909640''>do.</span> <span m=''2909960''>It''s
  a</span> <span m=''2910080''>car</span> <span m=''2910310''>cdr</span> <span m=''2910540''>recursion</span>
  <span m=''2910980''>of</span> <span m=''2911070''>some</span> <span m=''2911290''>sort,</span>
  <span m=''2912990''>or</span> <span m=''2913350''>something</span> <span m=''2913800''>like</span>
  <span m=''2914090''>that,</span> <span m=''2915190''>and some</span> <span m=''2915350''>sort</span>
  <span m=''2915490''>of</span> <span m=''2915620''>tree</span> <span m=''2915880''>walk.</span>
  <span m=''2917480''>And</span> <span m=''2917630''>that''s</span> <span m=''2917830''>going</span>
  <span m=''2917910''>to</span> <span m=''2918000''>be</span> <span m=''2918080''>happening.</span>
  </p><p><span m=''2918850''>Now,</span> <span m=''2919010''>for</span> <span m=''2919160''>every</span>
  <span m=''2919490''>such</span> <span m=''2919940''>place,</span> <span m=''2920500''>every</span>
  <span m=''2920760''>node</span> <span m=''2921350''>that</span> <span m=''2921605''>I</span>
  <span m=''2921860''>get</span> <span m=''2922140''>to</span> <span m=''2923450''>in</span>
  <span m=''2923660''>doing</span> <span m=''2923990''>my</span> <span m=''2925980''>traversal</span>
  <span m=''2926500''>of</span> <span m=''2926930''>the</span> <span m=''2927140''>expression</span>
  <span m=''2927660''>I''m</span> <span m=''2927770''>trying</span> <span m=''2928060''>to</span>
  <span m=''2928270''>simplify,</span> <span m=''2929150''>I</span> <span m=''2929300''>want</span>
  <span m=''2929560''>to</span> <span m=''2929870''>apply</span> <span m=''2930190''>all
  of</span> <span m=''2930390''>the</span> <span m=''2930590''>rules.</span> <span
  m=''2933390''>Every</span> <span m=''2933680''>rule</span> <span m=''2933960''>is</span>
  <span m=''2934040''>going</span> <span m=''2934120''>to</span> <span m=''2934200''>look</span>
  <span m=''2934320''>at</span> <span m=''2934440''>every</span> <span m=''2934680''>node.</span>
  <span m=''2936380''>I''m</span> <span m=''2936630''>going to</span> <span m=''2936720''>rotate</span>
  <span m=''2937060''>the</span> <span m=''2937160''>rules</span> <span m=''2937460''>around.</span>
  </p><p><span m=''2941660''>Now,</span> <span m=''2943210''>either a</span> <span
  m=''2943530''>rule</span> <span m=''2943890''>will</span> <span m=''2944200''>or</span>
  <span m=''2944350''>will</span> <span m=''2944560''>not</span> <span m=''2945110''>match.</span>
  <span m=''2947530''>If</span> <span m=''2947730''>the</span> <span m=''2947870''>rule</span>
  <span m=''2948150''>does</span> <span m=''2948320''>not</span> <span m=''2948590''>match,</span>
  <span m=''2949100''>then</span> <span m=''2949550''>it''s</span> <span m=''2949750''>not</span>
  <span m=''2949940''>very</span> <span m=''2950140''>interesting.</span> <span m=''2952270''>If</span>
  <span m=''2952500''>the</span> <span m=''2952610''>rule</span> <span m=''2952900''>does</span>
  <span m=''2953230''>match,</span> <span m=''2954460''>then</span> <span m=''2954760''>I''m</span>
  <span m=''2954870''>going</span> <span m=''2954950''>to</span> <span m=''2955040''>replace</span>
  <span m=''2955500''>that</span> <span m=''2955760''>node</span> <span m=''2956090''>in</span>
  <span m=''2956190''>the</span> <span m=''2956290''>expression</span> <span m=''2958360''>by</span>
  <span m=''2958710''>an</span> <span m=''2958850''>alternate</span> <span m=''2959350''>expression.</span>
  <span m=''2960110''>I''m</span> <span m=''2960580''>actually</span> <span m=''2960910''>going
  to</span> <span m=''2960990''>make a</span> <span m=''2961210''>new</span> <span
  m=''2961360''>expression,</span> <span m=''2962110''>which</span> <span m=''2962270''>contains--</span>
  <span m=''2963530''>everything</span> <span m=''2964260''>contains</span> <span
  m=''2964620''>that</span> <span m=''2964820''>new</span> <span m=''2965010''>value,</span>
  <span m=''2966040''>the</span> <span m=''2966150''>result</span> <span m=''2966450''>of</span>
  <span m=''2966560''>substituting</span> <span m=''2966940''>into</span> <span m=''2967320''>the</span>
  <span m=''2968030''>skeleton,</span> <span m=''2969250''>instantiating</span> <span
  m=''2969880''>the</span> <span m=''2969950''>skeleton</span> <span m=''2970370''>for</span>
  <span m=''2970460''>that</span> <span m=''2970660''>rule</span> <span m=''2971140''>at</span>
  <span m=''2971330''>this</span> <span m=''2971510''>level.</span> <span m=''2972480''>But</span>
  <span m=''2972970''>no</span> <span m=''2973090''>one</span> <span m=''2973280''>knows</span>
  <span m=''2973790''>whether</span> <span m=''2974080''>that</span> <span m=''2974410''>thing</span>
  <span m=''2974490''>that</span> <span m=''2974850''>I</span> <span m=''2975110''>instantiated</span>
  <span m=''2975670''>there</span> <span m=''2976200''>is</span> <span m=''2976340''>in</span>
  <span m=''2976410''>simplified</span> <span m=''2976920''>form.</span> <span m=''2978180''>So</span>
  <span m=''2978650''>we''re going</span> <span m=''2978980''>to have to</span> <span
  m=''2979040''>simplify</span> <span m=''2979440''>that,</span> <span m=''2980960''>somehow</span>
  <span m=''2981420''>to</span> <span m=''2981550''>call the</span> <span m=''2981830''>simplifier</span>
  <span m=''2982380''>on</span> <span m=''2982510''>the</span> <span m=''2982580''>thing
  that</span> <span m=''2982800''>I</span> <span m=''2982900''>just</span> <span m=''2983060''>constructed.</span>
  <span m=''2985990''>And then</span> <span m=''2986300''>when</span> <span m=''2986410''>that''s</span>
  <span m=''2986690''>done,</span> <span m=''2987660''>then</span> <span m=''2987810''>I</span>
  <span m=''2988110''>sort</span> <span m=''2988230''>of can</span> <span m=''2988350''>build</span>
  <span m=''2988550''>that</span> <span m=''2988710''>into</span> <span m=''2988840''>the</span>
  <span m=''2988970''>expression</span> <span m=''2989420''>I</span> <span m=''2989590''>want
  as</span> <span m=''2989770''>my</span> <span m=''2989920''>answer.</span> </p><p><span
  m=''2991820''>Now,</span> <span m=''2991970''>there is</span> <span m=''2992190''>a</span>
  <span m=''2992540''>basic</span> <span m=''2993000''>idea</span> <span m=''2993330''>here,</span>
  <span m=''2993850''>which</span> <span m=''2994110''>I</span> <span m=''2994210''>will</span>
  <span m=''2994350''>call</span> <span m=''2995080''>a</span> <span m=''2995490''>garbage-</span>
  <span m=''2995960''>in,</span> <span m=''2996230''>garbage-out</span> <span m=''2996860''>simplifier.</span>
  <span m=''3001280''>It''s a</span> <span m=''3001460''>kind</span> <span m=''3001640''>of</span>
  <span m=''3001720''>recursive</span> <span m=''3002140''>simplifier.</span> <span
  m=''3003570''>And</span> <span m=''3003700''>what</span> <span m=''3003820''>happens
  is</span> <span m=''3004220''>the</span> <span m=''3004290''>way</span> <span m=''3004440''>you</span>
  <span m=''3004540''>simplify</span> <span m=''3005020''>something</span> <span m=''3006010''>is</span>
  <span m=''3006150''>that</span> <span m=''3006750''>simple</span> <span m=''3007150''>objects</span>
  <span m=''3007670''>like</span> <span m=''3007990''>variables</span> <span m=''3008490''>are</span>
  <span m=''3008540''>simple.</span> <span m=''3010660''>Compound</span> <span m=''3011260''>objects,</span>
  <span m=''3012650''>well,</span> <span m=''3012800''>I</span> <span m=''3012910''>don''t</span>
  <span m=''3013020''>know.</span> <span m=''3014110''>What</span> <span m=''3014240''>I''m</span>
  <span m=''3014340''>going</span> <span m=''3014410''>to</span> <span m=''3014490''>do</span>
  <span m=''3015040''>is</span> <span m=''3015190''>I''m</span> <span m=''3015260''>going</span>
  <span m=''3015320''>to</span> <span m=''3015380''>build</span> <span m=''3015680''>up</span>
  <span m=''3015830''>from</span> <span m=''3015970''>simple</span> <span m=''3016260''>objects,</span>
  <span m=''3016780''>trying</span> <span m=''3017050''>to</span> <span m=''3017180''>make</span>
  <span m=''3017480''>simple</span> <span m=''3017810''>things</span> <span m=''3019130''>by</span>
  <span m=''3019280''>assuming</span> <span m=''3019700''>that</span> <span m=''3019820''>the</span>
  <span m=''3019940''>pieces</span> <span m=''3020210''>they''re</span> <span m=''3020350''>made
  out of</span> <span m=''3020510''>are</span> <span m=''3020840''>simple.</span>
  <span m=''3024540''>That''s</span> <span m=''3024830''>what''s</span> <span m=''3024980''>happening</span>
  <span m=''3025370''>here.</span> </p><p><span m=''3027830''>Well,</span> <span m=''3028010''>now,</span>
  <span m=''3028500''>if we</span> <span m=''3028750''>look</span> <span m=''3028940''>at</span>
  <span m=''3029050''>the</span> <span m=''3029260''>first</span> <span m=''3029610''>slide--</span>
  <span m=''3030400''>no,</span> <span m=''3030540''>overhead,</span> <span m=''3031100''>overhead.</span>
  <span m=''3031965''>If we</span> <span m=''3032260''>look</span> <span m=''3032390''>at</span>
  <span m=''3032520''>the</span> <span m=''3032610''>overhead,</span> <span m=''3033840''>we</span>
  <span m=''3034060''>see</span> <span m=''3034440''>a</span> <span m=''3034520''>very</span>
  <span m=''3034780''>complicated</span> <span m=''3035320''>program</span> <span
  m=''3035780''>like</span> <span m=''3035960''>we</span> <span m=''3036040''>saw</span>
  <span m=''3036210''>before</span> <span m=''3036530''>for</span> <span m=''3036630''>the</span>
  <span m=''3036730''>matcher,</span> <span m=''3037420''>so</span> <span m=''3037720''>complicated</span>
  <span m=''3038510''>that</span> <span m=''3038810''>you</span> <span m=''3038920''>can''t</span>
  <span m=''3039180''>read</span> <span m=''3039360''>it</span> <span m=''3039460''>like</span>
  <span m=''3039710''>that.</span> <span m=''3041260''>I just</span> <span m=''3041480''>want</span>
  <span m=''3041810''>you</span> <span m=''3041950''>to</span> <span m=''3042150''>get</span>
  <span m=''3042370''>the</span> <span m=''3042450''>feel</span> <span m=''3042790''>of</span>
  <span m=''3042900''>the</span> <span m=''3042970''>shape</span> <span m=''3043330''>of</span>
  <span m=''3043480''>it,</span> <span m=''3044430''>and</span> <span m=''3044590''>the</span>
  <span m=''3044660''>shape</span> <span m=''3045000''>of</span> <span m=''3045130''>it</span>
  <span m=''3045270''>is</span> <span m=''3045770''>that</span> <span m=''3046380''>this</span>
  <span m=''3046580''>program</span> <span m=''3047250''>has</span> <span m=''3048150''>various</span>
  <span m=''3048880''>subprograms</span> <span m=''3049560''>in</span> <span m=''3049850''>it.</span>
  <span m=''3053550''>One of them--this</span> <span m=''3054030''>part</span> <span
  m=''3054510''>is</span> <span m=''3054770''>the</span> <span m=''3055280''>part</span>
  <span m=''3055920''>for</span> <span m=''3056350''>traversing</span> <span m=''3056715''>the</span>
  <span m=''3057080''>expression,</span> <span m=''3058970''>and</span> <span m=''3059230''>this</span>
  <span m=''3059440''>part</span> <span m=''3059740''>is</span> <span m=''3059890''>the</span>
  <span m=''3059950''>part</span> <span m=''3060380''>for</span> <span m=''3060570''>trying</span>
  <span m=''3060960''>rules.</span> </p><p><span m=''3062560''>Now,</span> <span m=''3062740''>of</span>
  <span m=''3062910''>course,</span> <span m=''3063070''>we</span> <span m=''3063210''>can</span>
  <span m=''3063340''>look</span> <span m=''3063480''>at</span> <span m=''3063620''>that</span>
  <span m=''3064530''>in</span> <span m=''3064680''>some</span> <span m=''3064910''>more</span>
  <span m=''3065090''>detail.</span> <span m=''3066490''>Let''s look at--let''s</span>
  <span m=''3066910''>look</span> <span m=''3067110''>at</span> <span m=''3068710''>the</span>
  <span m=''3069090''>first</span> <span m=''3070420''>transparency,</span> <span
  m=''3071590''>right?</span> <span m=''3073370''>The</span> <span m=''3073550''>simplifier</span>
  <span m=''3075540''>is</span> <span m=''3075730''>made</span> <span m=''3076030''>out</span>
  <span m=''3076300''>of</span> <span m=''3076510''>several</span> <span m=''3077030''>parts.</span>
  <span m=''3077990''>Now,</span> <span m=''3078130''>remember at</span> <span m=''3078610''>the</span>
  <span m=''3078770''>very</span> <span m=''3079020''>beginning,</span> <span m=''3079560''>the</span>
  <span m=''3079820''>simplifier</span> <span m=''3080120''>is</span> <span m=''3080500''>the</span>
  <span m=''3080570''>thing</span> <span m=''3081020''>which</span> <span m=''3081300''>takes</span>
  <span m=''3081650''>a rules--a</span> <span m=''3082410''>set</span> <span m=''3082540''>of</span>
  <span m=''3082650''>rules</span> <span m=''3083850''>and</span> <span m=''3084100''>produces</span>
  <span m=''3085120''>a</span> <span m=''3085250''>program</span> <span m=''3085680''>which</span>
  <span m=''3085810''>will</span> <span m=''3085920''>simplify it</span> <span m=''3086370''>relative</span>
  <span m=''3086830''>to</span> <span m=''3086930''>them.</span> </p><p><span m=''3089850''>So</span>
  <span m=''3090660''>here</span> <span m=''3090950''>we</span> <span m=''3091090''>have</span>
  <span m=''3091660''>our</span> <span m=''3091860''>simplifier.</span> <span m=''3092390''>It</span>
  <span m=''3093440''>takes</span> <span m=''3093840''>a</span> <span m=''3094240''>rule</span>
  <span m=''3094500''>set.</span> <span m=''3096150''>And</span> <span m=''3096330''>in</span>
  <span m=''3096470''>the</span> <span m=''3096890''>context</span> <span m=''3097350''>where
  that</span> <span m=''3097630''>rule set</span> <span m=''3097880''>is</span> <span
  m=''3098090''>defined,</span> <span m=''3099080''>there</span> <span m=''3099410''>are</span>
  <span m=''3099440''>various</span> <span m=''3099730''>other</span> <span m=''3099950''>definitions</span>
  <span m=''3100500''>that</span> <span m=''3100750''>are</span> <span m=''3100940''>done</span>
  <span m=''3101150''>here.</span> <span m=''3102260''>And</span> <span m=''3102530''>then</span>
  <span m=''3102830''>the</span> <span m=''3103130''>result</span> <span m=''3103700''>of</span>
  <span m=''3103960''>this</span> <span m=''3104160''>simplifier</span> <span m=''3104900''>procedure</span>
  <span m=''3106380''>is,</span> <span m=''3106540''>in</span> <span m=''3106660''>fact,</span>
  <span m=''3107090''>one</span> <span m=''3107360''>of</span> <span m=''3107450''>the</span>
  <span m=''3107540''>procedures</span> <span m=''3108030''>that</span> <span m=''3108170''>was</span>
  <span m=''3108300''>defined.</span> <span m=''3110110''>Simplify</span> <span m=''3110610''>x.</span>
  <span m=''3112400''>What</span> <span m=''3112620''>I''m</span> <span m=''3112790''>returning</span>
  <span m=''3113670''>as</span> <span m=''3113860''>the</span> <span m=''3113970''>value</span>
  <span m=''3115250''>of</span> <span m=''3115800''>calling</span> <span m=''3116400''>the</span>
  <span m=''3116480''>simplifier</span> <span m=''3116850''>on</span> <span m=''3116980''>a</span>
  <span m=''3117030''>set</span> <span m=''3117200''>of</span> <span m=''3117340''>rules</span>
  <span m=''3118130''>is</span> <span m=''3118340''>a</span> <span m=''3118470''>procedure,</span>
  <span m=''3120570''>the</span> <span m=''3120660''>simplify</span> <span m=''3121120''>x</span>
  <span m=''3121340''>procedure,</span> <span m=''3121740''>which</span> <span m=''3121910''>is</span>
  <span m=''3121990''>defined</span> <span m=''3122410''>in</span> <span m=''3122530''>that</span>
  <span m=''3122730''>context,</span> <span m=''3125210''>which</span> <span m=''3125370''>is</span>
  <span m=''3125480''>a</span> <span m=''3125680''>simplification</span> <span m=''3126540''>procedure</span>
  <span m=''3127050''>appropriate</span> <span m=''3127660''>for</span> <span m=''3127780''>using</span>
  <span m=''3128110''>those</span> <span m=''3128200''>set</span> <span m=''3128350''>of</span>
  <span m=''3128450''>rules.</span> <span m=''3134930''>That''s</span> <span m=''3135220''>what</span>
  <span m=''3135320''>I</span> <span m=''3135490''>have</span> <span m=''3135660''>there.</span>
  </p><p><span m=''3137460''>Now,</span> <span m=''3138560''>the</span> <span m=''3138870''>first</span>
  <span m=''3139220''>two</span> <span m=''3139390''>of</span> <span m=''3139540''>these</span>
  <span m=''3139690''>procedures,</span> <span m=''3140200''>this</span> <span m=''3140420''>one</span>
  <span m=''3140930''>and</span> <span m=''3141230''>this</span> <span m=''3141440''>one,</span>
  <span m=''3142020''>are</span> <span m=''3142350''>together</span> <span m=''3142830''>going</span>
  <span m=''3143190''>to</span> <span m=''3143300''>be</span> <span m=''3143720''>the</span>
  <span m=''3143970''>recursive</span> <span m=''3144430''>traversal</span> <span
  m=''3144920''>of an</span> <span m=''3145070''>expression.</span> <span m=''3146950''>This</span>
  <span m=''3147170''>one</span> <span m=''3147730''>is</span> <span m=''3147890''>the</span>
  <span m=''3148010''>general</span> <span m=''3148640''>simplification</span> <span
  m=''3149360''>for</span> <span m=''3149510''>any</span> <span m=''3149680''>expression,</span>
  <span m=''3150870''>and</span> <span m=''3151120''>this</span> <span m=''3151260''>is</span>
  <span m=''3151340''>the</span> <span m=''3151420''>thing</span> <span m=''3151650''>which</span>
  <span m=''3151830''>simplifies</span> <span m=''3152330''>a</span> <span m=''3152410''>list</span>
  <span m=''3152620''>of</span> <span m=''3152700''>parts</span> <span m=''3153010''>of</span>
  <span m=''3153070''>an</span> <span m=''3153150''>expression.</span> <span m=''3155540''>Nothing</span>
  <span m=''3155790''>more.</span> <span m=''3156940''>For</span> <span m=''3157140''>each</span>
  <span m=''3157300''>of</span> <span m=''3157400''>those,</span> <span m=''3157640''>we''re</span>
  <span m=''3157740''>going</span> <span m=''3157820''>to</span> <span m=''3157900''>do</span>
  <span m=''3158030''>something</span> <span m=''3158320''>complicated,</span> <span
  m=''3158770''>which</span> <span m=''3158900''>involves</span> <span m=''3159250''>trying</span>
  <span m=''3159560''>the</span> <span m=''3159650''>rules.</span> </p><p><span m=''3160340''>Now,</span>
  <span m=''3160610''>we should</span> <span m=''3160700''>look</span> <span m=''3160820''>at</span>
  <span m=''3160940''>the</span> <span m=''3161030''>various</span> <span m=''3161430''>parts.</span>
  <span m=''3165290''>Well</span> <span m=''3165720''>let''s</span> <span m=''3166000''>look</span>
  <span m=''3166140''>first</span> <span m=''3166440''>at</span> <span m=''3166610''>the</span>
  <span m=''3166690''>recursive</span> <span m=''3167150''>traversal</span> <span
  m=''3167650''>of an</span> <span m=''3167710''>expression.</span> <span m=''3168530''>And</span>
  <span m=''3168690''>this</span> <span m=''3168820''>is</span> <span m=''3168980''>done</span>
  <span m=''3169960''>in</span> <span m=''3170435''>a</span> <span m=''3170740''>sort</span>
  <span m=''3171000''>of</span> <span m=''3171110''>simple</span> <span m=''3171460''>way.</span>
  <span m=''3174210''>This</span> <span m=''3174400''>is</span> <span m=''3176030''>a</span>
  <span m=''3176260''>little</span> <span m=''3176510''>nest</span> <span m=''3176840''>of</span>
  <span m=''3176930''>recursive</span> <span m=''3177320''>procedures.</span> <span
  m=''3179310''>And</span> <span m=''3179490''>what</span> <span m=''3179610''>we</span>
  <span m=''3179820''>have</span> <span m=''3180020''>here</span> <span m=''3180850''>are</span>
  <span m=''3181050''>two</span> <span m=''3181270''>procedures--</span> <span m=''3182580''>one</span>
  <span m=''3182850''>for</span> <span m=''3183680''>simplifying</span> <span m=''3184400''>an</span>
  <span m=''3184460''>expression,</span> <span m=''3186020''>and</span> <span m=''3186240''>one</span>
  <span m=''3186450''>for</span> <span m=''3186600''>simplifying</span> <span m=''3187130''>parts</span>
  <span m=''3187420''>of an</span> <span m=''3187550''>expression.</span> <span m=''3188982''>And</span>
  <span m=''3189410''>the</span> <span m=''3189550''>way</span> <span m=''3189730''>this</span>
  <span m=''3189930''>works</span> <span m=''3190290''>is</span> <span m=''3190410''>very</span>
  <span m=''3190610''>simple.</span> <span m=''3192130''>If</span> <span m=''3192320''>the</span>
  <span m=''3192400''>expression</span> <span m=''3192860''>I''m</span> <span m=''3192990''>trying</span>
  <span m=''3193330''>to</span> <span m=''3194150''>simplify</span> <span m=''3195530''>is</span>
  <span m=''3195690''>a</span> <span m=''3195750''>compound</span> <span m=''3196270''>expression,</span>
  <span m=''3196920''>I''m</span> <span m=''3197050''>going to</span> <span m=''3197290''>simplify</span>
  <span m=''3197620''>all</span> <span m=''3197720''>the</span> <span m=''3197810''>parts</span>
  <span m=''3198090''>of</span> <span m=''3198190''>it.</span> <span m=''3199920''>And</span>
  <span m=''3200490''>that''s calling--that</span> <span m=''3200940''>procedure,</span>
  <span m=''3201500''>simplify</span> <span m=''3202000''>parts,</span> <span m=''3202350''>is</span>
  <span m=''3202480''>going</span> <span m=''3202680''>to</span> <span m=''3202780''>make</span>
  <span m=''3203050''>up</span> <span m=''3203650''>a</span> <span m=''3203770''>new</span>
  <span m=''3203960''>expression</span> <span m=''3204450''>with</span> <span m=''3204570''>all</span>
  <span m=''3204660''>the</span> <span m=''3204760''>parts</span> <span m=''3205020''>simplified,</span>
  <span m=''3205970''>which</span> <span m=''3206190''>I''m then</span> <span m=''3206300''>going</span>
  <span m=''3206460''>to</span> <span m=''3206620''>try</span> <span m=''3206820''>the</span>
  <span m=''3206920''>rules</span> <span m=''3207250''>on</span> <span m=''3208220''>over</span>
  <span m=''3208410''>here.</span> </p><p><span m=''3210840''>If</span> <span m=''3211010''>it</span>
  <span m=''3211110''>turns</span> <span m=''3211420''>out</span> <span m=''3211740''>that</span>
  <span m=''3211990''>the</span> <span m=''3212060''>expression</span> <span m=''3212550''>is</span>
  <span m=''3212700''>not</span> <span m=''3213030''>compound,</span> <span m=''3213295''>if</span>
  <span m=''3213560''>it''s</span> <span m=''3213800''>simple,</span> <span m=''3214840''>like</span>
  <span m=''3215040''>just</span> <span m=''3215270''>a</span> <span m=''3215550''>symbol</span>
  <span m=''3215980''>or</span> <span m=''3216070''>something</span> <span m=''3216390''>like</span>
  <span m=''3216640''>pi,</span> <span m=''3217990''>then</span> <span m=''3218360''>in</span>
  <span m=''3218480''>any</span> <span m=''3218680''>case,</span> <span m=''3218880''>I''m
  going</span> <span m=''3218990''>to</span> <span m=''3219100''>try the</span> <span
  m=''3219390''>rules</span> <span m=''3219690''>on it</span> <span m=''3219930''>because</span>
  <span m=''3220220''>it</span> <span m=''3220300''>might</span> <span m=''3220510''>be</span>
  <span m=''3220630''>that</span> <span m=''3220700''>I</span> <span m=''3220780''>want</span>
  <span m=''3221080''>in</span> <span m=''3221220''>my</span> <span m=''3221370''>set</span>
  <span m=''3221530''>of</span> <span m=''3221620''>rules</span> <span m=''3222080''>to</span>
  <span m=''3222230''>expand</span> <span m=''3222620''>pi to</span> <span m=''3222900''>3.14159265358979,</span>
  <span m=''3226930''>dot, dot,</span> <span m=''3227290''>dot.</span> <span m=''3228290''>But
  I</span> <span m=''3228660''>may</span> <span m=''3228830''>not.</span> <span m=''3229570''>But</span>
  <span m=''3230310''>there is</span> <span m=''3230490''>no</span> <span m=''3230640''>reason</span>
  <span m=''3230930''>not</span> <span m=''3231160''>to</span> <span m=''3231250''>do</span>
  <span m=''3231480''>it.</span> </p><p><span m=''3232750''>Now,</span> <span m=''3234560''>if</span>
  <span m=''3234740''>I</span> <span m=''3234820''>want</span> <span m=''3235030''>to</span>
  <span m=''3235070''>simplify</span> <span m=''3235560''>the</span> <span m=''3235670''>parts,</span>
  <span m=''3236440''>well,</span> <span m=''3236630''>that''s</span> <span m=''3236870''>easy</span>
  <span m=''3237120''>too.</span> <span m=''3239010''>Either</span> <span m=''3239310''>the</span>
  <span m=''3239410''>expression</span> <span m=''3240480''>is</span> <span m=''3241300''>an</span>
  <span m=''3241420''>empty</span> <span m=''3241700''>one,</span> <span m=''3241990''>there''s</span>
  <span m=''3242170''>no</span> <span m=''3242300''>more</span> <span m=''3242480''>parts,</span>
  <span m=''3243700''>in</span> <span m=''3243800''>which</span> <span m=''3244000''>case</span>
  <span m=''3244220''>I</span> <span m=''3244290''>have</span> <span m=''3244440''>the
  empty</span> <span m=''3244750''>expression.</span> <span m=''3245730''>Otherwise,</span>
  <span m=''3247530''>I''m</span> <span m=''3247710''>going</span> <span m=''3247950''>to</span>
  <span m=''3248650''>make</span> <span m=''3248880''>a</span> <span m=''3248950''>new</span>
  <span m=''3249160''>expression</span> <span m=''3249820''>by</span> <span m=''3249980''>cons,</span>
  <span m=''3251140''>which</span> <span m=''3251460''>is</span> <span m=''3251560''>the</span>
  <span m=''3251650''>result</span> <span m=''3251960''>of</span> <span m=''3252010''>simplifying</span>
  <span m=''3252550''>the</span> <span m=''3252650''>first</span> <span m=''3253020''>part</span>
  <span m=''3253140''>of</span> <span m=''3253270''>the</span> <span m=''3253360''>expression,</span>
  <span m=''3253790''>the</span> <span m=''3253890''>car,</span> <span m=''3255390''>and</span>
  <span m=''3255600''>simplifying</span> <span m=''3255990''>the</span> <span m=''3256060''>rest</span>
  <span m=''3256280''>of</span> <span m=''3256320''>the</span> <span m=''3256370''>expression,</span>
  <span m=''3256780''>which is</span> <span m=''3256980''>the</span> <span m=''3257090''>cdr.</span>
  </p><p><span m=''3261060''>Now,</span> <span m=''3261310''>the</span> <span m=''3261420''>reason</span>
  <span m=''3261660''>why</span> <span m=''3261810''>I''m</span> <span m=''3261950''>showing</span>
  <span m=''3262320''>you</span> <span m=''3262430''>this</span> <span m=''3262570''>sort</span>
  <span m=''3262720''>of</span> <span m=''3262860''>stuff</span> <span m=''3263250''>this</span>
  <span m=''3263470''>way</span> <span m=''3264532''>is</span> <span m=''3264880''>because</span>
  <span m=''3265390''>I</span> <span m=''3265570''>want</span> <span m=''3265780''>you</span>
  <span m=''3265870''>get</span> <span m=''3266010''>the</span> <span m=''3266080''>feeling</span>
  <span m=''3266420''>for</span> <span m=''3266500''>the various</span> <span m=''3266980''>patterns</span>
  <span m=''3267510''>that</span> <span m=''3267630''>are</span> <span m=''3267680''>very</span>
  <span m=''3267900''>important</span> <span m=''3269410''>when</span> <span m=''3269570''>writing</span>
  <span m=''3269800''>programs.</span> <span m=''3272210''>And</span> <span m=''3272760''>this</span>
  <span m=''3272900''>could</span> <span m=''3273020''>be written</span> <span m=''3273150''>a</span>
  <span m=''3273310''>different</span> <span m=''3273600''>way.</span> <span m=''3273970''>There''s</span>
  <span m=''3274300''>another</span> <span m=''3274500''>way</span> <span m=''3274590''>to</span>
  <span m=''3274690''>write</span> <span m=''3274920''>simplified</span> <span m=''3275320''>expressions</span>
  <span m=''3275810''>so</span> <span m=''3275850''>there</span> <span m=''3275980''>would</span>
  <span m=''3276070''>be</span> <span m=''3276170''>only</span> <span m=''3276410''>one</span>
  <span m=''3276640''>of</span> <span m=''3276820''>them.</span> <span m=''3277355''>There</span>
  <span m=''3277720''>would</span> <span m=''3277900''>only</span> <span m=''3278120''>be</span>
  <span m=''3278280''>one</span> <span m=''3278720''>little</span> <span m=''3278940''>procedure</span>
  <span m=''3279350''>here.</span> <span m=''3279530''>Let</span> <span m=''3279650''>me</span>
  <span m=''3279730''>just</span> <span m=''3279910''>write</span> <span m=''3280070''>that</span>
  <span m=''3280200''>on</span> <span m=''3280280''>the</span> <span m=''3280330''>blackboard</span>
  <span m=''3280910''>to</span> <span m=''3281110''>give you</span> <span m=''3281470''>a</span>
  <span m=''3281540''>feeling</span> <span m=''3281860''>for</span> <span m=''3281990''>that.</span>
  </p><p><span m=''3289520''>This</span> <span m=''3290070''>in</span> <span m=''3290360''>another</span>
  <span m=''3290800''>idiom,</span> <span m=''3291590''>if</span> <span m=''3291720''>you</span>
  <span m=''3291850''>will.</span> <span m=''3298449''>To</span> <span m=''3298940''>simplify</span>
  <span m=''3299405''>an</span> <span m=''3299870''>expression</span> <span m=''3300240''>called</span>
  <span m=''3300460''>x,</span> <span m=''3302640''>what am I</span> <span m=''3302810''>going</span>
  <span m=''3302970''>to</span> <span m=''3303090''>do?</span> <span m=''3303400''>I''m
  going to</span> <span m=''3303530''>try</span> <span m=''3303710''>the</span> <span
  m=''3303890''>rules</span> <span m=''3309110''>on</span> <span m=''3309280''>the</span>
  <span m=''3309350''>following</span> <span m=''3309730''>situation.</span> <span
  m=''3311100''>If--</span> <span m=''3312170''>on</span> <span m=''3312330''>the</span>
  <span m=''3312400''>following</span> <span m=''3312630''>expression--</span> <span
  m=''3314090''>compound,</span> <span m=''3314730''>just</span> <span m=''3314900''>like</span>
  <span m=''3315030''>we</span> <span m=''3315110''>had</span> <span m=''3315270''>before.</span>
  <span m=''3321060''>If</span> <span m=''3321490''>the</span> <span m=''3321720''>expression</span>
  <span m=''3322120''>is</span> <span m=''3322240''>compound,</span> <span m=''3323010''>well,</span>
  <span m=''3323270''>what</span> <span m=''3323530''>am</span> <span m=''3323570''>I</span>
  <span m=''3323700''>going</span> <span m=''3323990''>to do?</span> <span m=''3324270''>I''m</span>
  <span m=''3324550''>going  to</span> <span m=''3324780''>simplify</span> <span m=''3324950''>all</span>
  <span m=''3325040''>the</span> <span m=''3325130''>parts.</span> <span m=''3325970''>But</span>
  <span m=''3326060''>I</span> <span m=''3326150''>already</span> <span m=''3326380''>have</span>
  <span m=''3326600''>a</span> <span m=''3326980''>cdr</span> <span m=''3327180''>recursion,</span>
  <span m=''3330150''>a common</span> <span m=''3330570''>pattern of</span> <span
  m=''3330950''>usage,</span> <span m=''3331310''>which has been</span> <span m=''3331690''>captured</span>
  <span m=''3332100''>as</span> <span m=''3332230''>a</span> <span m=''3332320''>high-order</span>
  <span m=''3332690''>procedure.</span> <span m=''3333590''>It''s</span> <span m=''3333990''>called</span>
  <span m=''3334310''>map.</span> <span m=''3336040''>So I''ll</span> <span m=''3336140''>just</span>
  <span m=''3336240''>write</span> <span m=''3336490''>that</span> <span m=''3336590''>here.</span>
  </p><p><span m=''3337180''>Map</span> <span m=''3339350''>simplify</span> <span
  m=''3344300''>the</span> <span m=''3344670''>expression,</span> <span m=''3346720''>all</span>
  <span m=''3346840''>the</span> <span m=''3346920''>parts</span> <span m=''3347210''>of</span>
  <span m=''3347250''>the</span> <span m=''3347290''>expression.</span> <span m=''3349060''>This</span>
  <span m=''3349190''>says</span> <span m=''3349580''>apply</span> <span m=''3351280''>the</span>
  <span m=''3351420''>simplification</span> <span m=''3352080''>operation,</span>
  <span m=''3352580''>which is</span> <span m=''3352770''>this</span> <span m=''3352960''>one,</span>
  <span m=''3353290''>every</span> <span m=''3353530''>part</span> <span m=''3353700''>of</span>
  <span m=''3353860''>the</span> <span m=''3353950''>expression,</span> <span m=''3355290''>and</span>
  <span m=''3355470''>then</span> <span m=''3355780''>that</span> <span m=''3356120''>cuts</span>
  <span m=''3356460''>those</span> <span m=''3356640''>up</span> <span m=''3356750''>into</span>
  <span m=''3356890''>a</span> <span m=''3357030''>list.</span> <span m=''3359570''>It''s</span>
  <span m=''3359990''>every</span> <span m=''3362020''>element</span> <span m=''3362390''>of</span>
  <span m=''3362440''>the</span> <span m=''3362520''>list</span> <span m=''3362840''>which
  the</span> <span m=''3363020''>expression</span> <span m=''3363335''>is</span> <span
  m=''3363650''>assumed</span> <span m=''3363780''>to be</span> <span m=''3363960''>made</span>
  <span m=''3364270''>out of,</span> <span m=''3366254''>and</span> <span m=''3366750''>otherwise,</span>
  <span m=''3367210''>I have the</span> <span m=''3367410''>expression.</span> <span
  m=''3368910''>So</span> <span m=''3369170''>I</span> <span m=''3369250''>don''t</span>
  <span m=''3369420''>need</span> <span m=''3369650''>the</span> <span m=''3370180''>helper</span>
  <span m=''3370480''>procedure,</span> <span m=''3371630''>simplify</span> <span
  m=''3372080''>parts,</span> <span m=''3372650''>because</span> <span m=''3372840''>that''s</span>
  <span m=''3373050''>really</span> <span m=''3373320''>this.</span> <span m=''3375370''>So</span>
  <span m=''3375570''>sometimes,</span> <span m=''3375950''>you</span> <span m=''3376000''>just</span>
  <span m=''3376240''>write</span> <span m=''3376570''>it</span> <span m=''3376670''>this</span>
  <span m=''3376840''>way.</span> <span m=''3377690''>It</span> <span m=''3377820''>doesn''t</span>
  <span m=''3378060''>matter</span> <span m=''3378300''>very</span> <span m=''3378540''>much.</span>
  </p><p><span m=''3380830''>Well,</span> <span m=''3381310''>now</span> <span m=''3381480''>let''s</span>
  <span m=''3381670''>take</span> <span m=''3381850''>a</span> <span m=''3382020''>look</span>
  <span m=''3382190''>at--</span> <span m=''3384410''>let''s</span> <span m=''3384600''>just</span>
  <span m=''3384800''>look</span> <span m=''3385030''>at</span> <span m=''3385360''>how</span>
  <span m=''3385540''>you</span> <span m=''3385670''>try</span> <span m=''3385940''>rules.</span>
  <span m=''3387660''>If</span> <span m=''3387820''>you</span> <span m=''3387970''>look</span>
  <span m=''3388110''>at</span> <span m=''3388300''>this</span> <span m=''3388790''>slide,</span>
  <span m=''3390030''>we see this</span> <span m=''3390220''>is</span> <span m=''3390470''>a</span>
  <span m=''3390540''>complicated</span> <span m=''3391100''>mess</span> <span m=''3391340''>also.</span>
  <span m=''3393680''>I''m</span> <span m=''3393840''>trying</span> <span m=''3394280''>rules</span>
  <span m=''3394600''>on</span> <span m=''3394840''>an</span> <span m=''3394950''>expression.</span>
  <span m=''3396140''>It</span> <span m=''3396270''>turns</span> <span m=''3396530''>out
  the</span> <span m=''3396710''>expression I''m</span> <span m=''3397170''>trying</span>
  <span m=''3397600''>it on is</span> <span m=''3397790''>some</span> <span m=''3398030''>subexpression</span>
  <span m=''3398710''>now</span> <span m=''3399150''>of the</span> <span m=''3399310''>expression</span>
  <span m=''3399680''>I</span> <span m=''3399750''>started</span> <span m=''3400040''>with.</span>
  <span m=''3400490''>Because</span> <span m=''3400800''>the</span> <span m=''3400880''>thing</span>
  <span m=''3401060''>I</span> <span m=''3401160''>just</span> <span m=''3401390''>arranged</span>
  <span m=''3402230''>allowed</span> <span m=''3402620''>us</span> <span m=''3402730''>to</span>
  <span m=''3402820''>try</span> <span m=''3403040''>every</span> <span m=''3403320''>subexpression.</span>
  </p><p><span m=''3406050''>So</span> <span m=''3406210''>now</span> <span m=''3406640''>here</span>
  <span m=''3406920''>we''re taking</span> <span m=''3407200''>in</span> <span m=''3407810''>a</span>
  <span m=''3407960''>subexpression</span> <span m=''3409920''>of</span> <span m=''3410070''>the</span>
  <span m=''3410140''>expression</span> <span m=''3410540''>we</span> <span m=''3410650''>started</span>
  <span m=''3410910''>with.</span> <span m=''3411080''>That''s</span> <span m=''3411260''>what</span>
  <span m=''3411370''>this</span> <span m=''3411570''>is.</span> <span m=''3412225''>And</span>
  <span m=''3412530''>what</span> <span m=''3412770''>we''re</span> <span m=''3412890''>going</span>
  <span m=''3412960''>to</span> <span m=''3413030''>define</span> <span m=''3413460''>here</span>
  <span m=''3414020''>is</span> <span m=''3414190''>a</span> <span m=''3414250''>procedure</span>
  <span m=''3415380''>called</span> <span m=''3415670''>scan,</span> <span m=''3416580''>which
  is</span> <span m=''3416750''>going</span> <span m=''3416840''>to</span> <span m=''3416940''>try</span>
  <span m=''3417180''>every</span> <span m=''3417440''>rule.</span> <span m=''3418640''>And</span>
  <span m=''3418770''>we''re</span> <span m=''3418850''>going</span> <span m=''3418910''>to</span>
  <span m=''3418970''>start it</span> <span m=''3419270''>up</span> <span m=''3419440''>on
  the</span> <span m=''3419580''>whole set</span> <span m=''3419810''>of</span> <span
  m=''3420105''>rules.</span> <span m=''3421920''>This</span> <span m=''3422030''>is</span>
  <span m=''3422190''>going</span> <span m=''3422350''>to</span> <span m=''3422580''>go</span>
  <span m=''3423480''>cdr-ing</span> <span m=''3423920''>down</span> <span m=''3424220''>the</span>
  <span m=''3424300''>rules,</span> <span m=''3424660''>if</span> <span m=''3424780''>you</span>
  <span m=''3424900''>will,</span> <span m=''3426670''>looking</span> <span m=''3427000''>for</span>
  <span m=''3427160''>a</span> <span m=''3427320''>rule</span> <span m=''3427600''>to</span>
  <span m=''3427810''>apply.</span> <span m=''3429370''>And</span> <span m=''3429510''>when</span>
  <span m=''3429590''>it</span> <span m=''3429680''>finds</span> <span m=''3430050''>one,</span>
  <span m=''3431130''>it''ll</span> <span m=''3431570''>do</span> <span m=''3431720''>the</span>
  <span m=''3431840''>job.</span> </p><p><span m=''3434140''>Well,</span> <span m=''3434410''>let''s</span>
  <span m=''3434580''>take</span> <span m=''3434780''>a</span> <span m=''3434910''>look</span>
  <span m=''3435050''>at</span> <span m=''3435280''>how</span> <span m=''3435450''>try</span>
  <span m=''3435770''>rules</span> <span m=''3436120''>works.</span> <span m=''3437630''>It''s</span>
  <span m=''3437750''>very</span> <span m=''3437940''>simple:</span> <span m=''3438660''>the</span>
  <span m=''3438890''>scan</span> <span m=''3439305''>rules.</span> <span m=''3439720''>Scan
  rules, the</span> <span m=''3440180''>way</span> <span m=''3440390''>of</span> <span
  m=''3440460''>scanning.</span> <span m=''3442066''>Well,</span> <span m=''3442450''>is</span>
  <span m=''3442610''>it</span> <span m=''3442720''>so</span> <span m=''3442890''>simple?</span>
  <span m=''3443270''>It''s</span> <span m=''3443380''>a</span> <span m=''3443430''>big</span>
  <span m=''3443610''>program,</span> <span m=''3444150''>of</span> <span m=''3444220''>course.</span>
  <span m=''3445510''>We</span> <span m=''3445640''>take</span> <span m=''3445810''>a</span>
  <span m=''3445870''>bunch</span> <span m=''3446090''>of</span> <span m=''3446220''>rules,</span>
  <span m=''3446910''>which</span> <span m=''3447190''>is</span> <span m=''3447440''>a</span>
  <span m=''3447540''>sublist</span> <span m=''3448060''>of</span> <span m=''3448160''>the</span>
  <span m=''3448230''>list</span> <span m=''3448480''>of</span> <span m=''3448600''>rules.</span>
  <span m=''3450700''>We''ve</span> <span m=''3450890''>tried</span> <span m=''3451190''>some</span>
  <span m=''3451360''>of</span> <span m=''3451410''>them</span> <span m=''3451540''>already,</span>
  <span m=''3452260''>and</span> <span m=''3452470''>they''ve</span> <span m=''3452670''>not</span>
  <span m=''3452850''>been</span> <span m=''3453080''>appropriate,</span> <span m=''3453830''>so</span>
  <span m=''3453990''>we</span> <span m=''3454080''>get</span> <span m=''3454270''>to</span>
  <span m=''3454460''>some</span> <span m=''3454740''>here.</span> <span m=''3455360''>We
  get</span> <span m=''3455530''>to move to</span> <span m=''3455870''>the next one.</span>
  <span m=''3456490''>If</span> <span m=''3456680''>there</span> <span m=''3456820''>are</span>
  <span m=''3456860''>no</span> <span m=''3457030''>more</span> <span m=''3457280''>rules,</span>
  <span m=''3457810''>well</span> <span m=''3458000''>then,</span> <span m=''3458120''>there''s</span>
  <span m=''3458290''>nothing</span> <span m=''3458540''>I</span> <span m=''3458600''>can</span>
  <span m=''3458730''>do</span> <span m=''3458840''>with</span> <span m=''3458920''>this</span>
  <span m=''3459040''>expression,</span> <span m=''3459530''>and</span> <span m=''3459880''>it''s</span>
  <span m=''3460110''>simplified.</span> </p><p><span m=''3462200''>However,</span>
  <span m=''3464020''>if</span> <span m=''3464230''>it</span> <span m=''3464340''>turns</span>
  <span m=''3464660''>out</span> <span m=''3465060''>that</span> <span m=''3465870''>there</span>
  <span m=''3465980''>are</span> <span m=''3466130''>still</span> <span m=''3466360''>rules</span>
  <span m=''3466610''>to</span> <span m=''3466680''>be</span> <span m=''3466790''>done,</span>
  <span m=''3467830''>then</span> <span m=''3468500''>let''s</span> <span m=''3468800''>match</span>
  <span m=''3469390''>the</span> <span m=''3469610''>pattern</span> <span m=''3470130''>of</span>
  <span m=''3470560''>the</span> <span m=''3470800''>first</span> <span m=''3471130''>rule</span>
  <span m=''3472180''>against</span> <span m=''3472430''>the</span> <span m=''3472670''>expression</span>
  <span m=''3473850''>using</span> <span m=''3474120''>the</span> <span m=''3474250''>empty</span>
  <span m=''3474490''>dictionary</span> <span m=''3474940''>to</span> <span m=''3475000''>start</span>
  <span m=''3475280''>with</span> <span m=''3477470''>and</span> <span m=''3477660''>use</span>
  <span m=''3477910''>that</span> <span m=''3478140''>as</span> <span m=''3478300''>the</span>
  <span m=''3478370''>dictionary.</span> <span m=''3480270''>If</span> <span m=''3480520''>that</span>
  <span m=''3480840''>happens</span> <span m=''3481220''>to</span> <span m=''3481310''>be</span>
  <span m=''3481430''>a</span> <span m=''3481490''>failure,</span> <span m=''3482520''>try</span>
  <span m=''3482830''>the</span> <span m=''3482940''>rest</span> <span m=''3483200''>of</span>
  <span m=''3483280''>the</span> <span m=''3483370''>rules.</span> <span m=''3486540''>That''s</span>
  <span m=''3486780''>all</span> <span m=''3486920''>it</span> <span m=''3487010''>says</span>
  <span m=''3487230''>here.</span> <span m=''3488790''>It</span> <span m=''3488950''>says</span>
  <span m=''3489400''>discard</span> <span m=''3489840''>that</span> <span m=''3490060''>rule.</span>
  <span m=''3491080''>Otherwise,</span> <span m=''3492540''>well,</span> <span m=''3492940''>I''m</span>
  <span m=''3493130''>going</span> <span m=''3493330''>to</span> <span m=''3493370''>get</span>
  <span m=''3493530''>the</span> <span m=''3493610''>skeleton</span> <span m=''3494150''>of</span>
  <span m=''3494280''>the</span> <span m=''3494370''>first</span> <span m=''3494640''>rule,</span>
  <span m=''3495320''>instantiate</span> <span m=''3496070''>that</span> <span m=''3496310''>relative</span>
  <span m=''3496720''>to</span> <span m=''3496810''>the</span> <span m=''3496890''>dictionary,</span>
  <span m=''3497890''>and</span> <span m=''3498080''>simplify</span> <span m=''3498600''>the</span>
  <span m=''3498710''>result,</span> <span m=''3499165''>and</span> <span m=''3499620''>that''s</span>
  <span m=''3499890''>the</span> <span m=''3499960''>expression</span> <span m=''3500390''>I</span>
  <span m=''3500660''>want.</span> </p><p><span m=''3504070''>So</span> <span m=''3504350''>although</span>
  <span m=''3504600''>that</span> <span m=''3504760''>was</span> <span m=''3504870''>a</span>
  <span m=''3504910''>complicated</span> <span m=''3505440''>program,</span> <span
  m=''3506200''>every</span> <span m=''3506380''>complicated</span> <span m=''3506980''>program</span>
  <span m=''3507340''>is</span> <span m=''3507420''>made</span> <span m=''3507570''>out
  of a</span> <span m=''3507720''>lot</span> <span m=''3507880''>of</span> <span m=''3508030''>simple</span>
  <span m=''3508330''>pieces.</span> <span m=''3509940''>Now,</span> <span m=''3510080''>the</span>
  <span m=''3510140''>pattern</span> <span m=''3511540''>of</span> <span m=''3511630''>recursions</span>
  <span m=''3512130''>here</span> <span m=''3512330''>is</span> <span m=''3512460''>very</span>
  <span m=''3512720''>complicated.</span> <span m=''3514760''>And</span> <span m=''3514920''>one
  of</span> <span m=''3515090''>the most</span> <span m=''3515260''>important things
  is</span> <span m=''3515750''>not</span> <span m=''3515950''>to</span> <span m=''3516010''>think</span>
  <span m=''3516230''>about</span> <span m=''3516520''>that.</span> <span m=''3518126''>If</span>
  <span m=''3518620''>you</span> <span m=''3518800''>try</span> <span m=''3519060''>to</span>
  <span m=''3519160''>think</span> <span m=''3519400''>about</span> <span m=''3519980''>the
  actual</span> <span m=''3520250''>pattern</span> <span m=''3520590''>by</span> <span
  m=''3520720''>which</span> <span m=''3520930''>this</span> <span m=''3521130''>does</span>
  <span m=''3521380''>something,</span> <span m=''3522020''>you''re</span> <span m=''3522200''>going</span>
  <span m=''3522260''>to</span> <span m=''3522330''>get</span> <span m=''3522510''>very</span>
  <span m=''3522900''>confused.</span> <span m=''3525250''>I</span> <span m=''3525440''>would.</span>
  <span m=''3527420''>This is</span> <span m=''3527630''>not</span> <span m=''3527840''>a</span>
  <span m=''3527880''>matter</span> <span m=''3528230''>of</span> <span m=''3529020''>you</span>
  <span m=''3529140''>can</span> <span m=''3529480''>do</span> <span m=''3529580''>this
  with</span> <span m=''3529820''>practice.</span> <span m=''3531470''>These</span>
  <span m=''3531700''>patterns</span> <span m=''3532020''>are</span> <span m=''3532080''>hard.</span>
  <span m=''3533761''>But</span> <span m=''3534160''>you don''t</span> <span m=''3534440''>have</span>
  <span m=''3534680''>to</span> <span m=''3534800''>think</span> <span m=''3535000''>about</span>
  <span m=''3535290''>it.</span> <span m=''3535840''>The</span> <span m=''3536110''>key</span>
  <span m=''3536360''>to</span> <span m=''3536430''>this--</span> <span m=''3537010''>it''s</span>
  <span m=''3537820''>very</span> <span m=''3538050''>good</span> <span m=''3538250''>programming</span>
  <span m=''3538870''>and</span> <span m=''3538990''>very</span> <span m=''3539150''>good</span>
  <span m=''3539290''>design--</span> <span m=''3539730''>is</span> <span m=''3539900''>to</span>
  <span m=''3539990''>know</span> <span m=''3540120''>what</span> <span m=''3540320''>not</span>
  <span m=''3540520''>to</span> <span m=''3540610''>think</span> <span m=''3540820''>about.</span>
  </p><p><span m=''3542990''>The</span> <span m=''3543230''>fact</span> <span m=''3543620''>is,</span>
  <span m=''3544100''>going back</span> <span m=''3544380''>to</span> <span m=''3544500''>this</span>
  <span m=''3545580''>slide,</span> <span m=''3546890''>I</span> <span m=''3547050''>don''t</span>
  <span m=''3547220''>have</span> <span m=''3547380''>to</span> <span m=''3547540''>think</span>
  <span m=''3547770''>about</span> <span m=''3548060''>it</span> <span m=''3548530''>because</span>
  <span m=''3548920''>I</span> <span m=''3549010''>have</span> <span m=''3549220''>specifications</span>
  <span m=''3550530''>in</span> <span m=''3550720''>my</span> <span m=''3550930''>mind</span>
  <span m=''3551285''>for</span> <span m=''3551640''>what</span> <span m=''3552100''>simplify</span>
  <span m=''3552660''>x</span> <span m=''3553040''>does.</span> <span m=''3554000''>I</span>
  <span m=''3554170''>don''t have to</span> <span m=''3554390''>know</span> <span
  m=''3554570''>how</span> <span m=''3554820''>it</span> <span m=''3554940''>does</span>
  <span m=''3555180''>it.</span> <span m=''3556735''>And</span> <span m=''3557170''>it</span>
  <span m=''3557340''>may,</span> <span m=''3557550''>in fact,</span> <span m=''3557950''>call</span>
  <span m=''3558470''>scan</span> <span m=''3558710''>somehow</span> <span m=''3559650''>through</span>
  <span m=''3559900''>try</span> <span m=''3560240''>rules,</span> <span m=''3560720''>which</span>
  <span m=''3560870''>it</span> <span m=''3560980''>does.</span> <span m=''3562190''>And</span>
  <span m=''3562320''>somehow,</span> <span m=''3562660''>I''ve got</span> <span m=''3562840''>another</span>
  <span m=''3563060''>recursion</span> <span m=''3563470''>going</span> <span m=''3563690''>on</span>
  <span m=''3563840''>here.</span> <span m=''3564230''>But</span> <span m=''3564450''>since</span>
  <span m=''3564630''>I</span> <span m=''3564730''>know</span> <span m=''3564910''>that</span>
  <span m=''3565020''>simplify</span> <span m=''3565500''>x</span> <span m=''3566880''>is</span>
  <span m=''3567010''>assumed</span> <span m=''3568000''>by</span> <span m=''3568140''>wishful</span>
  <span m=''3568470''>thinking</span> <span m=''3568880''>to</span> <span m=''3568960''>produce</span>
  <span m=''3569380''>the</span> <span m=''3569430''>simplified</span> <span m=''3569930''>result,</span>
  <span m=''3571200''>then I don''t</span> <span m=''3571570''>have to</span> <span
  m=''3571900''>think</span> <span m=''3572330''>about</span> <span m=''3572550''>it</span>
  <span m=''3572630''>anymore.</span> <span m=''3573900''>I''ve</span> <span m=''3574040''>used
  it.</span> <span m=''3575030''>I''ve</span> <span m=''3575220''>used</span> <span
  m=''3575440''>it in</span> <span m=''3575590''>a</span> <span m=''3575670''>reasonable</span>
  <span m=''3576030''>way.</span> <span m=''3576480''>I will</span> <span m=''3576650''>get</span>
  <span m=''3576740''>a</span> <span m=''3576840''>reasonable</span> <span m=''3577290''>answer.</span>
  <span m=''3579468''>And</span> <span m=''3579910''>you</span> <span m=''3580070''>have</span>
  <span m=''3580160''>to</span> <span m=''3580260''>learn</span> <span m=''3580450''>how</span>
  <span m=''3580530''>to</span> <span m=''3580610''>program</span> <span m=''3581030''>that</span>
  <span m=''3581240''>way--</span> <span m=''3581760''>with</span> <span m=''3581860''>abandon.</span>
  </p><p><span m=''3587480''>Well,</span> <span m=''3587800''>there''s</span> <span
  m=''3588000''>very</span> <span m=''3588310''>little</span> <span m=''3588660''>left
  of this</span> <span m=''3589160''>thing.</span> <span m=''3590390''>All</span>
  <span m=''3590620''>there</span> <span m=''3590800''>is</span> <span m=''3590900''>left</span>
  <span m=''3591160''>is</span> <span m=''3591250''>a</span> <span m=''3591300''>few</span>
  <span m=''3591520''>details</span> <span m=''3592160''>associated</span> <span m=''3593200''>with</span>
  <span m=''3593420''>what</span> <span m=''3593570''>a</span> <span m=''3593610''>dictionary</span>
  <span m=''3594200''>is.</span> <span m=''3595060''>And</span> <span m=''3595530''>those</span>
  <span m=''3595880''>of</span> <span m=''3595970''>you who''ve</span> <span m=''3596340''>been</span>
  <span m=''3596700''>itching</span> <span m=''3597040''>to</span> <span m=''3597160''>know</span>
  <span m=''3597310''>what</span> <span m=''3597460''>a</span> <span m=''3597520''>dictionary</span>
  <span m=''3598110''>is,</span> <span m=''3598620''>well,</span> <span m=''3599400''>I</span>
  <span m=''3599550''>will</span> <span m=''3599780''>flip it</span> <span m=''3600030''>up</span>
  <span m=''3600480''>and</span> <span m=''3600650''>not</span> <span m=''3600850''>tell</span>
  <span m=''3601000''>you</span> <span m=''3601130''>anything</span> <span m=''3601450''>about</span>
  <span m=''3601770''>it.</span> <span m=''3604110''>Dictionaries</span> <span m=''3604610''>are</span>
  <span m=''3604710''>easy.</span> <span m=''3606020''>It''s</span> <span m=''3606210''>represented</span>
  <span m=''3606770''>in</span> <span m=''3606880''>terms</span> <span m=''3607130''>of</span>
  <span m=''3607210''>something</span> <span m=''3607540''>else</span> <span m=''3607800''>called</span>
  <span m=''3608900''>an</span> <span m=''3609370''>A</span> <span m=''3609570''>list,</span>
  <span m=''3610660''>which</span> <span m=''3610850''>is</span> <span m=''3610930''>a</span>
  <span m=''3610990''>particular</span> <span m=''3611390''>pattern</span> <span m=''3612030''>of</span>
  <span m=''3612330''>usage</span> <span m=''3612800''>for</span> <span m=''3612940''>making</span>
  <span m=''3614730''>tables</span> <span m=''3615630''>in</span> <span m=''3615810''>lists.</span>
  <span m=''3616730''>They''re</span> <span m=''3616820''>easy.</span> <span m=''3617220''>They''re</span>
  <span m=''3617350''>made out of</span> <span m=''3617690''>pairs,</span> <span m=''3618160''>as</span>
  <span m=''3618300''>was</span> <span m=''3618470''>asked</span> <span m=''3618800''>a</span>
  <span m=''3618840''>bit</span> <span m=''3619670''>ago.</span> <span m=''3621670''>And</span>
  <span m=''3621830''>there are</span> <span m=''3621960''>special</span> <span m=''3622300''>procedures</span>
  <span m=''3622770''>for</span> <span m=''3622870''>dealing</span> <span m=''3623170''>with</span>
  <span m=''3623270''>such</span> <span m=''3623450''>things</span> <span m=''3623730''>called</span>
  <span m=''3623920''>assq,</span> <span m=''3624910''>and</span> <span m=''3625030''>you</span>
  <span m=''3625110''>can</span> <span m=''3625230''>find</span> <span m=''3625530''>them</span>
  <span m=''3625660''>in</span> <span m=''3625770''>manuals.</span> </p><p><span m=''3627020''>I''m</span>
  <span m=''3627230''>not</span> <span m=''3627410''>terribly</span> <span m=''3627740''>excited</span>
  <span m=''3628170''>about</span> <span m=''3628460''>it.</span> <span m=''3628730''>The</span>
  <span m=''3628980''>only</span> <span m=''3629240''>interesting</span> <span m=''3629660''>thing</span>
  <span m=''3629860''>here</span> <span m=''3630080''>in</span> <span m=''3630160''>extend</span>
  <span m=''3630590''>dictionary</span> <span m=''3631180''>is</span> <span m=''3631510''>I
  have</span> <span m=''3631910''>to</span> <span m=''3632040''>extend</span> <span
  m=''3632350''>the</span> <span m=''3632400''>dictionary</span> <span m=''3633440''>with</span>
  <span m=''3633630''>a</span> <span m=''3634030''>pattern,</span> <span m=''3635520''>a</span>
  <span m=''3635860''>datum,</span> <span m=''3636115''>and</span> <span m=''3636370''>a</span>
  <span m=''3636480''>dictionary.</span> <span m=''3637910''>This</span> <span m=''3638130''>pattern</span>
  <span m=''3638480''>is,</span> <span m=''3638910''>in</span> <span m=''3639020''>fact,</span>
  <span m=''3639320''>at</span> <span m=''3639390''>this</span> <span m=''3639590''>point</span>
  <span m=''3641050''>a</span> <span m=''3641670''>pattern</span> <span m=''3641980''>variable.</span>
  <span m=''3642896''>And</span> <span m=''3643332''>what do</span> <span m=''3643770''>I</span>
  <span m=''3644150''>want</span> <span m=''3644270''>to</span> <span m=''3644390''>do?</span>
  <span m=''3644880''>I</span> <span m=''3645020''>want</span> <span m=''3645140''>to</span>
  <span m=''3645250''>pull</span> <span m=''3645460''>out</span> <span m=''3645640''>the</span>
  <span m=''3645740''>name</span> <span m=''3646040''>of</span> <span m=''3646340''>that</span>
  <span m=''3646830''>pattern</span> <span m=''3647170''>variable,</span> <span m=''3647930''>the</span>
  <span m=''3648220''>pattern</span> <span m=''3648650''>variable</span> <span m=''3649010''>name,</span>
  <span m=''3650460''>and</span> <span m=''3650720''>I''m</span> <span m=''3650870''>going</span>
  <span m=''3651130''>to</span> <span m=''3651700''>look</span> <span m=''3651870''>up</span>
  <span m=''3651980''>in</span> <span m=''3652040''>the</span> <span m=''3652100''>dictionary</span>
  <span m=''3652470''>and see if it</span> <span m=''3652730''>already</span> <span
  m=''3653060''>has</span> <span m=''3653250''>a</span> <span m=''3653300''>value.</span>
  <span m=''3653750''>If</span> <span m=''3654000''>not,</span> <span m=''3654260''>I''m</span>
  <span m=''3654520''>going</span> <span m=''3654965''>to add</span> <span m=''3655410''>a</span>
  <span m=''3655660''>new</span> <span m=''3655860''>one</span> <span m=''3656070''>in.</span>
  <span m=''3657030''>If</span> <span m=''3657190''>it</span> <span m=''3657370''>does</span>
  <span m=''3657750''>have</span> <span m=''3658000''>one,</span> <span m=''3658255''>if
  it</span> <span m=''3658510''>has</span> <span m=''3658760''>a</span> <span m=''3658820''>value,</span>
  <span m=''3659390''>then</span> <span m=''3659980''>it</span> <span m=''3660120''>had</span>
  <span m=''3660280''>better</span> <span m=''3660490''>be</span> <span m=''3660730''>equal</span>
  <span m=''3661050''>to</span> <span m=''3661160''>the</span> <span m=''3661260''>one</span>
  <span m=''3661680''>that</span> <span m=''3661860''>was</span> <span m=''3662050''>already</span>
  <span m=''3662350''>stored</span> <span m=''3662780''>away.</span> <span m=''3663920''>And</span>
  <span m=''3664430''>if</span> <span m=''3664560''>that''s</span> <span m=''3664760''>the</span>
  <span m=''3664820''>case,</span> <span m=''3665050''>the</span> <span m=''3665130''>dictionary</span>
  <span m=''3665560''>is what I</span> <span m=''3665690''>expected it</span> <span
  m=''3666190''>to</span> <span m=''3666250''>be.</span> <span m=''3666940''>Otherwise,</span>
  <span m=''3668300''>I</span> <span m=''3668800''>fail.</span> <span m=''3671605''>So</span>
  <span m=''3672100''>that''s</span> <span m=''3672390''>easy,</span> <span m=''3672660''>too.</span>
  <span m=''3673430''>If you</span> <span m=''3673930''>open</span> <span m=''3674220''>up</span>
  <span m=''3674350''>any</span> <span m=''3674520''>program,</span> <span m=''3674795''>you''re</span>
  <span m=''3675070''>going to</span> <span m=''3675150''>find</span> <span m=''3675470''>inside</span>
  <span m=''3675800''>of  it</span> <span m=''3676080''>lots of</span> <span m=''3676200''>little</span>
  <span m=''3676400''>pieces,</span> <span m=''3677320''>all</span> <span m=''3677470''>of</span>
  <span m=''3677610''>which</span> <span m=''3677790''>are</span> <span m=''3677880''>easy.</span>
  </p><p><span m=''3680000''>So</span> <span m=''3680210''>at</span> <span m=''3680350''>this</span>
  <span m=''3680490''>point,</span> <span m=''3680780''>I</span> <span m=''3680880''>suppose,</span>
  <span m=''3681500''>I''ve</span> <span m=''3681680''>just</span> <span m=''3681920''>told</span>
  <span m=''3682140''>you</span> <span m=''3682620''>some</span> <span m=''3683340''>million-dollar</span>
  <span m=''3684240''>valuable</span> <span m=''3685260''>information.</span> <span
  m=''3687995''>And</span> <span m=''3688430''>I</span> <span m=''3688670''>suppose</span>
  <span m=''3689070''>at</span> <span m=''3689140''>this</span> <span m=''3689200''>point</span>
  <span m=''3689450''>we''re</span> <span m=''3689590''>pretty</span> <span m=''3689790''>much</span>
  <span m=''3690010''>done</span> <span m=''3690200''>with</span> <span m=''3690320''>this</span>
  <span m=''3690490''>program.</span> <span m=''3691930''>I''d like to</span> <span
  m=''3692140''>ask</span> <span m=''3692360''>about</span> <span m=''3692550''>questions.</span>
  </p><p><span m=''3694330''>AUDIENCE: Yes,</span> <span m=''3694550''>can</span>
  <span m=''3694660''>you</span> <span m=''3694730''>give</span> <span m=''3694850''>me</span>
  <span m=''3694960''>the</span> <span m=''3695050''>words</span> <span m=''3695320''>that</span>
  <span m=''3695410''>describe</span> <span m=''3695880''>the</span> <span m=''3695940''>specification</span>
  <span m=''3696600''>for a</span> <span m=''3696740''>simplified</span> <span m=''3697630''>expression?</span>
  </p><p><span m=''3698650''>PROFESSOR: Sure.</span> <span m=''3699475''>A</span>
  <span m=''3699790''>simplified</span> <span m=''3700370''>expression</span> <span
  m=''3700680''>takes</span> <span m=''3700940''>an</span> <span m=''3701000''>expression</span>
  <span m=''3702830''>and</span> <span m=''3702910''>produces a</span> <span m=''3703330''>simplified</span>
  <span m=''3703840''>expression.</span> <span m=''3704838''>That''s it,</span> <span
  m=''3706710''>OK?</span> <span m=''3708120''>How it</span> <span m=''3708560''>does</span>
  <span m=''3708830''>it</span> <span m=''3709550''>is</span> <span m=''3709710''>very</span>
  <span m=''3709980''>easy.</span> <span m=''3711212''>In</span> <span m=''3711660''>compound</span>
  <span m=''3712100''>expressions,</span> <span m=''3712600''>all the pieces are</span>
  <span m=''3713100''>simplified,</span> <span m=''3713405''>and</span> <span m=''3713710''>then</span>
  <span m=''3713880''>the</span> <span m=''3713970''>rules</span> <span m=''3714210''>are</span>
  <span m=''3714260''>tried</span> <span m=''3714780''>on</span> <span m=''3715090''>the</span>
  <span m=''3715760''>result.</span> <span m=''3716910''>And</span> <span m=''3717215''>for
  simple</span> <span m=''3717520''>expressions,</span> <span m=''3717750''>you just</span>
  <span m=''3717950''>try all the</span> <span m=''3718260''>rules.</span> </p><p><span
  m=''3719216''>AUDIENCE: So an</span> <span m=''3719712''>expression is</span> <span
  m=''3720210''>simplified</span> <span m=''3721080''>by</span> <span m=''3721280''>virtue</span>
  <span m=''3721705''>of the rules?</span> </p><p><span m=''3722535''>PROFESSOR: That''s,</span>
  <span m=''3722940''>of</span> <span m=''3723140''>course,</span> <span m=''3723360''>true.</span>
  </p><p><span m=''3723660''>AUDIENCE: Right.</span> </p><p><span m=''3724140''>PROFESSOR:
  And</span> <span m=''3724250''>the</span> <span m=''3724360''>way</span> <span m=''3724570''>this</span>
  <span m=''3724760''>works</span> <span m=''3725380''>is</span> <span m=''3725540''>that</span>
  <span m=''3725600''>simplifi</span> <span m=''3726060''>expression,</span> <span
  m=''3726540''>as</span> <span m=''3726710''>you</span> <span m=''3726810''>see</span>
  <span m=''3727040''>here,</span> <span m=''3728700''>what</span> <span m=''3728850''>it</span>
  <span m=''3728940''>does</span> <span m=''3729400''>is it</span> <span m=''3729580''>breaks</span>
  <span m=''3729860''>the</span> <span m=''3730000''>expression</span> <span m=''3730290''>down</span>
  <span m=''3730560''>into</span> <span m=''3730770''>the</span> <span m=''3730920''>smallest</span>
  <span m=''3731270''>pieces,</span> <span m=''3732540''>simplifies</span> <span m=''3733190''>building</span>
  <span m=''3733550''>up</span> <span m=''3733720''>from</span> <span m=''3733820''>the</span>
  <span m=''3733920''>bottom</span> <span m=''3735730''>using</span> <span m=''3735980''>the</span>
  <span m=''3736080''>rules</span> <span m=''3736400''>to</span> <span m=''3736490''>be</span>
  <span m=''3736610''>the</span> <span m=''3736690''>simplifier,</span> <span m=''3738210''>to
  do</span> <span m=''3738530''>the</span> <span m=''3738650''>manipulations,</span>
  <span m=''3740412''>and</span> <span m=''3740830''>constructs</span> <span m=''3741100''>a</span>
  <span m=''3741370''>new</span> <span m=''3741490''>expression</span> <span m=''3741940''>as</span>
  <span m=''3742060''>the</span> <span m=''3742110''>result.</span> <span m=''3744400''>Eventually,</span>
  <span m=''3746710''>one</span> <span m=''3746870''>of</span> <span m=''3746980''>things</span>
  <span m=''3747170''>you</span> <span m=''3747280''>see</span> <span m=''3747760''>is</span>
  <span m=''3747960''>that</span> <span m=''3748100''>the rules themselves,</span>
  <span m=''3748670''>the</span> <span m=''3748900''>try</span> <span m=''3749150''>rules,</span>
  <span m=''3749730''>call</span> <span m=''3750060''>a</span> <span m=''3750210''>simplified</span>
  <span m=''3750570''>expression</span> <span m=''3750880''>on the</span> <span m=''3751090''>results</span>
  <span m=''3751750''>when</span> <span m=''3751910''>it</span> <span m=''3752010''>changes</span>
  <span m=''3752360''>something,</span> <span m=''3754230''>the</span> <span m=''3754280''>results</span>
  <span m=''3754650''>of</span> <span m=''3755210''>a</span> <span m=''3755260''>match.</span>
  <span m=''3755830''>I''m</span> <span m=''3756130''>sorry,</span> <span m=''3756510''>the
  results of</span> <span m=''3756850''>instantiation</span> <span m=''3757520''>of
  a</span> <span m=''3757740''>skeleton</span> <span m=''3759420''>for</span> <span
  m=''3759610''>a rule</span> <span m=''3759950''>that</span> <span m=''3760290''>has</span>
  <span m=''3760480''>matched.</span> <span m=''3761900''>So</span> <span m=''3762380''>the</span>
  <span m=''3762910''>spec</span> <span m=''3763390''>of a</span> <span m=''3763550''>simplified</span>
  <span m=''3764040''>expression</span> <span m=''3764460''>is that any</span> <span
  m=''3764570''>expression</span> <span m=''3765100''>you</span> <span m=''3765170''>put</span>
  <span m=''3765330''>into</span> <span m=''3765580''>it</span> <span m=''3765840''>comes</span>
  <span m=''3766060''>out</span> <span m=''3766250''>simplified</span> <span m=''3766460''>according</span>
  <span m=''3766860''>to</span> <span m=''3766940''>those</span> <span m=''3767130''>rules.</span>
  <span m=''3769590''>Thank</span> <span m=''3770070''>you.</span> <span m=''3770190''>Let''s</span>
  <span m=''3770380''>take</span> <span m=''3770550''>a</span> <span m=''3770610''>break.</span>
  </p>'
type: course
uid: e621477bd0a9ffda4f1bc6c1525285ab

---
None