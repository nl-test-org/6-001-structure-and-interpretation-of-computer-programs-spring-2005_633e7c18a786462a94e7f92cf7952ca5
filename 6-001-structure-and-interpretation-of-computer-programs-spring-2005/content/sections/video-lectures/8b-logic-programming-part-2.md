---
about_this_resource_text: <p><b>Topics covered:</b> Logic Programming, Part 2</p>
  <p><b> Instructors:</b> Hal Abelson and Gerald Jay Sussman</p> <p>Subtitles for
  this course are provided through the generous assistance of Henry Baker, Hoofar
  Pourzand, Heather Wood, Aleksejs Truhans, Steven Edwards, George Menhorn, and Mahendra
  Kumar.</p>
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
embedded_media:
- id: 8B.jpg
  parent_uid: 1d264c40a64a3604495574e9399e9070
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/8b-logic-programming-part-2/8B.jpg
  title: 8B.jpg
  type: null
  uid: c21ca024c0edc41031795456d149b93c
- id: Video-YouTube-Stream
  media_location: GReBwkGFZcs
  parent_uid: 1d264c40a64a3604495574e9399e9070
  title: Video-YouTube-Stream
  type: Video
  uid: e294c1761919f4fdea5ce01f9f9a94a4
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT_Structure_of_Computer_Programs_1986/lec8b.mp4
  parent_uid: 1d264c40a64a3604495574e9399e9070
  title: Video-Internet Archive-MP4
  type: Video
  uid: d3faa659935960f7bd57a55cbcf7238c
- id: Thumbnail-OCW-JPG
  parent_uid: 1d264c40a64a3604495574e9399e9070
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 7aead954d55741130222acbd454149f9
- id: 3Play-3PlayYouTubeid-MP4
  media_location: GReBwkGFZcs
  parent_uid: 1d264c40a64a3604495574e9399e9070
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 03855a4316f40f1e13ac6b15ab14fdb8
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/GReBwkGFZcs/default.jpg
  parent_uid: 1d264c40a64a3604495574e9399e9070
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: fbdc4d90c72035edd7404bb2b57ee87c
- id: GReBwkGFZcs.srt
  parent_uid: 1d264c40a64a3604495574e9399e9070
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/8b-logic-programming-part-2/GReBwkGFZcs.srt
  title: 3play caption file
  type: null
  uid: 2e696658eac7e370193b21dc108f1ffd
- id: GReBwkGFZcs.pdf
  parent_uid: 1d264c40a64a3604495574e9399e9070
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/8b-logic-programming-part-2/GReBwkGFZcs.pdf
  title: 3play pdf file
  type: null
  uid: f4784e2d396f83a7d2a0af9cb8925d3c
- id: Caption-3Play YouTube id-SRT
  parent_uid: 1d264c40a64a3604495574e9399e9070
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: f29358453b10c8201418bec33d25c2d7
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 1d264c40a64a3604495574e9399e9070
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 878d6391cd7072b7c91f1c9a0a3705e0
inline_embed_id: 820128018b:logicprogramming,part282732216
layout: video
order_index: null
parent_uid: 4fcacad2c29981dd668a6b29822403cc
related_resources_text: ''
short_url: 8b-logic-programming-part-2
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/8b-logic-programming-part-2
template_type: Tabbed
title: '8B: Logic Programming, Part 2'
transcript: '<p><span m=''18910''>PROFESSOR: All</span> <span m=''19100''>right, well,</span>
  <span m=''19250''>we''ve</span> <span m=''19380''>seen</span> <span m=''19700''>how</span>
  <span m=''19880''>the</span> <span m=''20690''>query</span> <span m=''20900''>language</span>
  <span m=''21250''>works.</span> <span m=''22502''>Now,</span> <span m=''22880''>let''s</span>
  <span m=''23130''>talk</span> <span m=''23350''>about</span> <span m=''23890''>how</span>
  <span m=''24070''>it''s</span> <span m=''24230''>implemented.</span> <span m=''26280''>You</span>
  <span m=''26510''>already</span> <span m=''26740''>pretty</span> <span m=''27120''>much</span>
  <span m=''27410''>can</span> <span m=''27570''>guess</span> <span m=''28660''>what''s</span>
  <span m=''28870''>going</span> <span m=''29120''>on</span> <span m=''29310''>there.</span>
  <span m=''29470''>At</span> <span m=''29540''>the</span> <span m=''29620''>bottom</span>
  <span m=''30010''>of</span> <span m=''30130''>it,</span> <span m=''30340''>there''s</span>
  <span m=''30720''>a</span> <span m=''30770''>pattern</span> <span m=''31120''>matcher.</span>
  <span m=''32810''>And</span> <span m=''32950''>we</span> <span m=''33050''>looked</span>
  <span m=''33250''>at</span> <span m=''33310''>a</span> <span m=''33370''>pattern</span>
  <span m=''33720''>matcher</span> <span m=''34700''>when</span> <span m=''34810''>we</span>
  <span m=''34910''>did</span> <span m=''35080''>the</span> <span m=''35180''>rule-based</span>
  <span m=''36060''>control</span> <span m=''36630''>language.</span> </p><p><span
  m=''38110''>Just</span> <span m=''38360''>to</span> <span m=''38430''>remind</span>
  <span m=''38870''>you,</span> <span m=''39190''>here are</span> <span m=''39360''>some</span>
  <span m=''39520''>sample</span> <span m=''39920''>patterns.</span> <span m=''41520''>This</span>
  <span m=''41840''>is</span> <span m=''41910''>a</span> <span m=''41970''>pattern</span>
  <span m=''42650''>that</span> <span m=''43140''>will</span> <span m=''43270''>match</span>
  <span m=''43860''>any</span> <span m=''44100''>list</span> <span m=''44340''>of</span>
  <span m=''44430''>three</span> <span m=''44670''>things</span> <span m=''45010''>of</span>
  <span m=''45090''>which</span> <span m=''45280''>the</span> <span m=''45360''>first</span>
  <span m=''46400''>is</span> <span m=''46660''>a</span> <span m=''47240''>and</span>
  <span m=''47340''>the</span> <span m=''47450''>second</span> <span m=''47770''>is</span>
  <span m=''47840''>c</span> <span m=''48500''>and</span> <span m=''48750''>the middle</span>
  <span m=''48930''>one</span> <span m=''49100''>can</span> <span m=''49250''>be</span>
  <span m=''49380''>anything.</span> <span m=''50650''>So</span> <span m=''50840''>in</span>
  <span m=''50940''>this</span> <span m=''51050''>little</span> <span m=''51210''>pattern-matching</span>
  <span m=''51860''>syntax,</span> <span m=''52310''>there''s</span> <span m=''52460''>only</span>
  <span m=''52910''>one</span> <span m=''53140''>distinction</span> <span m=''53630''>you</span>
  <span m=''53770''>make.</span> <span m=''54050''>There''s</span> <span m=''54240''>either</span>
  <span m=''54980''>literal</span> <span m=''55370''>things</span> <span m=''56480''>or</span>
  <span m=''56680''>variables,</span> <span m=''56975''>and</span> <span m=''57270''>variables</span>
  <span m=''57830''>begin</span> <span m=''58080''>with</span> <span m=''58220''>question</span>
  <span m=''58560''>mark.</span> </p><p><span m=''61370''>So</span> <span m=''61490''>this</span>
  <span m=''61670''>matches</span> <span m=''62440''>any</span> <span m=''62670''>list</span>
  <span m=''62880''>of</span> <span m=''62980''>three</span> <span m=''63210''>things</span>
  <span m=''64519''>of</span> <span m=''64650''>which</span> <span m=''64819''>the</span>
  <span m=''64900''>first is</span> <span m=''65269''>a</span> <span m=''65550''>and</span>
  <span m=''65610''>the</span> <span m=''65780''>second</span> <span m=''65950''>is</span>
  <span m=''66030''>c.</span> <span m=''66500''>This</span> <span m=''66810''>one</span>
  <span m=''66960''>matches</span> <span m=''67290''>any</span> <span m=''67550''>list</span>
  <span m=''67810''>of</span> <span m=''68200''>three</span> <span m=''68510''>things</span>
  <span m=''70500''>of</span> <span m=''70700''>which</span> <span m=''70920''>the</span>
  <span m=''71010''>first</span> <span m=''71370''>is</span> <span m=''71660''>the</span>
  <span m=''71790''>symbol</span> <span m=''72160''>job.</span> <span m=''72530''>The</span>
  <span m=''72740''>second</span> <span m=''72950''>can</span> <span m=''73050''>be</span>
  <span m=''73180''>anything.</span> <span m=''74210''>And</span> <span m=''74320''>the</span>
  <span m=''74440''>third</span> <span m=''74710''>is</span> <span m=''74820''>a</span>
  <span m=''74890''>list</span> <span m=''75190''>of</span> <span m=''75300''>two</span>
  <span m=''75500''>things</span> <span m=''75910''>of</span> <span m=''76020''>which</span>
  <span m=''76210''>the</span> <span m=''76300''>first</span> <span m=''76650''>is</span>
  <span m=''76750''>the</span> <span m=''76830''>symbol</span> <span m=''77170''>computer</span>
  <span m=''77970''>and</span> <span m=''78070''>the</span> <span m=''78180''>second</span>
  <span m=''78530''>can</span> <span m=''78660''>be</span> <span m=''78800''>anything.</span>
  <span m=''80480''>And</span> <span m=''81310''>this</span> <span m=''81900''>one,</span>
  <span m=''82470''>this</span> <span m=''82770''>next</span> <span m=''83060''>one</span>
  <span m=''83910''>matches</span> <span m=''84310''>any</span> <span m=''84540''>list</span>
  <span m=''84750''>of</span> <span m=''84860''>three</span> <span m=''85100''>things,</span>
  <span m=''85890''>and</span> <span m=''86000''>the</span> <span m=''86120''>only</span>
  <span m=''86320''>difference</span> <span m=''86740''>is,</span> <span m=''88310''>here,</span>
  <span m=''88670''>the</span> <span m=''88800''>third</span> <span m=''89120''>list,</span>
  <span m=''89750''>the</span> <span m=''89870''>first</span> <span m=''90210''>is</span>
  <span m=''90320''>the</span> <span m=''90390''>symbol</span> <span m=''90700''>computer,</span>
  <span m=''91860''>and</span> <span m=''92030''>then</span> <span m=''92130''>there''s</span>
  <span m=''92280''>some</span> <span m=''92440''>rest</span> <span m=''92740''>of</span>
  <span m=''92810''>the</span> <span m=''92870''>list.</span> <span m=''95010''>So</span>
  <span m=''95200''>this</span> <span m=''95340''>means</span> <span m=''95550''>two</span>
  <span m=''95700''>elements</span> <span m=''96130''>and</span> <span m=''96250''>this</span>
  <span m=''96430''>means</span> <span m=''96550''>arbitrary</span> <span m=''97060''>number.</span>
  <span m=''97860''>And</span> <span m=''98240''>our</span> <span m=''98440''>language</span>
  <span m=''98830''>implementation</span> <span m=''99450''>isn''t</span> <span m=''99890''>even
  going to</span> <span m=''100210''>have</span> <span m=''100340''>to</span> <span
  m=''100470''>worry</span> <span m=''100780''>about</span> <span m=''101140''>implementing</span>
  <span m=''101670''>this</span> <span m=''101750''>dot</span> <span m=''102030''>because</span>
  <span m=''102310''>that''s</span> <span m=''102570''>automatically</span> <span
  m=''103170''>done</span> <span m=''103370''>by</span> <span m=''103500''>Lisp''s</span>
  <span m=''103630''>reader.</span> </p><p><span m=''108340''>Remember</span> <span
  m=''108570''>matchers</span> <span m=''108970''>also have</span> <span m=''109250''>some</span>
  <span m=''109440''>consistency</span> <span m=''110080''>in them.</span> <span m=''110310''>This</span>
  <span m=''110500''>match</span> <span m=''110790''>is</span> <span m=''110910''>a</span>
  <span m=''110960''>list</span> <span m=''111440''>of</span> <span m=''111610''>three</span>
  <span m=''111860''>things</span> <span m=''112720''>of</span> <span m=''112850''>which</span>
  <span m=''113010''>the</span> <span m=''113100''>first</span> <span m=''113410''>is</span>
  <span m=''113560''>a.</span> <span m=''114430''>And</span> <span m=''114660''>the</span>
  <span m=''114830''>second</span> <span m=''115010''>and</span> <span m=''115120''>third</span>
  <span m=''115320''>can</span> <span m=''115430''>be</span> <span m=''115580''>anything,</span>
  <span m=''115900''>but</span> <span m=''116010''>they</span> <span m=''116110''>have</span>
  <span m=''116220''>to be</span> <span m=''116340''>the</span> <span m=''116420''>same</span>
  <span m=''116710''>thing.</span> <span m=''117940''>They''re</span> <span m=''118070''>both</span>
  <span m=''118300''>called</span> <span m=''118580''>x.</span> <span m=''119600''>And</span>
  <span m=''119980''>this</span> <span m=''120130''>matches</span> <span m=''120470''>a</span>
  <span m=''120520''>list</span> <span m=''120770''>of</span> <span m=''120850''>four</span>
  <span m=''121070''>things</span> <span m=''121990''>of</span> <span m=''122150''>which</span>
  <span m=''122330''>the</span> <span m=''122420''>first</span> <span m=''122730''>is</span>
  <span m=''122830''>the</span> <span m=''122920''>fourth</span> <span m=''123650''>and</span>
  <span m=''123790''>the</span> <span m=''123970''>second</span> <span m=''124150''>is
  the same as</span> <span m=''124560''>the</span> <span m=''124650''>third.</span>
  <span m=''125590''>And</span> <span m=''125740''>this</span> <span m=''125900''>last</span>
  <span m=''126230''>one</span> <span m=''126520''>matches</span> <span m=''127140''>any</span>
  <span m=''127400''>list</span> <span m=''127650''>that</span> <span m=''127780''>begins</span>
  <span m=''128100''>with</span> <span m=''128250''>a.</span> <span m=''129685''>The</span>
  <span m=''130080''>first</span> <span m=''130360''>thing is</span> <span m=''130650''>a,</span>
  <span m=''131310''>and</span> <span m=''131420''>the</span> <span m=''131530''>rest</span>
  <span m=''131770''>can</span> <span m=''131900''>be</span> <span m=''132020''>anything.</span>
  <span m=''134040''>So</span> <span m=''134210''>that''s</span> <span m=''134380''>just</span>
  <span m=''134810''>a</span> <span m=''134930''>review</span> <span m=''135330''>of</span>
  <span m=''135420''>pattern</span> <span m=''135810''>matcher</span> <span m=''136130''>syntax</span>
  <span m=''136640''>that</span> <span m=''136750''>you''ve</span> <span m=''136920''>already</span>
  <span m=''137260''>seen.</span> </p><p><span m=''138780''>And</span> <span m=''139030''>remember,</span>
  <span m=''139800''>that''s</span> <span m=''140090''>implemented</span> <span m=''140680''>by</span>
  <span m=''140810''>some</span> <span m=''141020''>procedure</span> <span m=''141490''>called</span>
  <span m=''141760''>match.</span> <span m=''144870''>And</span> <span m=''145060''>match</span>
  <span m=''148340''>takes</span> <span m=''148670''>a</span> <span m=''148720''>pattern</span>
  <span m=''151410''>and</span> <span m=''151600''>some</span> <span m=''151770''>data</span>
  <span m=''155030''>and</span> <span m=''155280''>a</span> <span m=''155330''>dictionary.</span>
  <span m=''163200''>And</span> <span m=''165590''>match</span> <span m=''165950''>asks</span>
  <span m=''166440''>the</span> <span m=''166580''>question</span> <span m=''167830''>is</span>
  <span m=''167980''>there</span> <span m=''168110''>any</span> <span m=''168340''>way</span>
  <span m=''168790''>to</span> <span m=''168940''>match</span> <span m=''170110''>this</span>
  <span m=''170470''>pattern</span> <span m=''171080''>against</span> <span m=''171370''>this</span>
  <span m=''171660''>data</span> <span m=''171970''>object</span> <span m=''173460''>subject</span>
  <span m=''174310''>to</span> <span m=''174610''>the</span> <span m=''174710''>bindings</span>
  <span m=''175170''>that are</span> <span m=''175430''>already</span> <span m=''175830''>in</span>
  <span m=''175960''>this</span> <span m=''176130''>dictionary?</span> </p><p><span
  m=''178160''>So,</span> <span m=''178390''>for</span> <span m=''178630''>instance,</span>
  <span m=''179620''>if</span> <span m=''179810''>we''re</span> <span m=''179910''>going</span>
  <span m=''179990''>to</span> <span m=''180080''>match</span> <span m=''180390''>the</span>
  <span m=''180500''>pattern</span> <span m=''181630''>x,</span> <span m=''183200''>y,</span>
  <span m=''184410''>y,</span> <span m=''185920''>x</span> <span m=''187760''>against</span>
  <span m=''188880''>the</span> <span m=''189040''>data</span> <span m=''190700''>a,</span>
  <span m=''191530''>b,</span> <span m=''192360''>b,</span> <span m=''193390''>a</span>
  <span m=''195050''>subject</span> <span m=''195840''>to</span> <span m=''196040''>a</span>
  <span m=''196240''>dictionary,</span> <span m=''198080''>that</span> <span m=''198380''>says</span>
  <span m=''198700''>x</span> <span m=''199400''>equals</span> <span m=''200010''>a.</span>
  <span m=''202010''>Then</span> <span m=''202170''>the</span> <span m=''202240''>matcher</span>
  <span m=''203390''>would</span> <span m=''203550''>say,</span> <span m=''204000''>yes,</span>
  <span m=''204360''>that''s</span> <span m=''204680''>consistent.</span> <span m=''205260''>These</span>
  <span m=''205550''>match,</span> <span m=''206090''>and</span> <span m=''206240''>it''s</span>
  <span m=''206400''>consistent</span> <span m=''207890''>with</span> <span m=''208050''>what''s</span>
  <span m=''208270''>in</span> <span m=''208320''>the</span> <span m=''208410''>dictionary</span>
  <span m=''208900''>to</span> <span m=''209000''>say</span> <span m=''209200''>that</span>
  <span m=''209350''>x</span> <span m=''209540''>equals</span> <span m=''209870''>a.</span>
  <span m=''210320''>And</span> <span m=''210490''>the</span> <span m=''210560''>result</span>
  <span m=''210990''>of</span> <span m=''211080''>the</span> <span m=''211170''>match</span>
  <span m=''212310''>is</span> <span m=''212560''>the</span> <span m=''212960''>extended</span>
  <span m=''213610''>dictionary</span> <span m=''214650''>that</span> <span m=''214810''>says</span>
  <span m=''215010''>x</span> <span m=''215270''>equals</span> <span m=''215690''>a</span>
  <span m=''216340''>and</span> <span m=''216700''>y</span> <span m=''216940''>equals</span>
  <span m=''217270''>b.</span> <span m=''219490''>So a</span> <span m=''219700''>matcher</span>
  <span m=''220050''>takes</span> <span m=''220340''>in</span> <span m=''221200''>pattern</span>
  <span m=''221530''>data</span> <span m=''221790''>dictionary,</span> <span m=''222290''>puts</span>
  <span m=''222640''>out</span> <span m=''222770''>an</span> <span m=''222860''>extended</span>
  <span m=''223300''>dictionary</span> <span m=''223780''>if</span> <span m=''223890''>it</span>
  <span m=''223990''>matches,</span> <span m=''225060''>or</span> <span m=''225150''>if</span>
  <span m=''225230''>it</span> <span m=''225310''>doesn''t</span> <span m=''225590''>match,</span>
  <span m=''225840''>says</span> <span m=''226040''>that</span> <span m=''226170''>it</span>
  <span m=''226310''>fails.</span> <span m=''226840''>So,</span> <span m=''227030''>for</span>
  <span m=''227210''>example,</span> <span m=''227950''>if</span> <span m=''228170''>I</span>
  <span m=''228240''>use</span> <span m=''228490''>the</span> <span m=''228560''>same</span>
  <span m=''229620''>pattern</span> <span m=''230000''>here,</span> <span m=''230770''>if</span>
  <span m=''230970''>I</span> <span m=''231470''>say</span> <span m=''231620''>this</span>
  <span m=''231790''>x,</span> <span m=''232660''>y,</span> <span m=''233470''>y,</span>
  <span m=''234680''>x</span> <span m=''235650''>match</span> <span m=''236160''>a,</span>
  <span m=''236800''>b,</span> <span m=''237330''>b,</span> <span m=''238060''>a</span>
  <span m=''239510''>with</span> <span m=''239790''>the</span> <span m=''239870''>dictionary</span>
  <span m=''241860''>y</span> <span m=''242170''>equals</span> <span m=''242450''>a,</span>
  <span m=''245030''>then</span> <span m=''245360''>the</span> <span m=''245440''>matcher</span>
  <span m=''245820''>would</span> <span m=''245980''>put</span> <span m=''246130''>out</span>
  <span m=''246350''>fail.</span> </p><p><span m=''252150''>Well,</span> <span m=''252630''>you''ve</span>
  <span m=''252890''>already</span> <span m=''253190''>seen</span> <span m=''253480''>the</span>
  <span m=''253570''>code</span> <span m=''253830''>for a</span> <span m=''253960''>pattern</span>
  <span m=''254330''>matcher</span> <span m=''254970''>so</span> <span m=''255100''>I''m</span>
  <span m=''255190''>not</span> <span m=''255360''>going</span> <span m=''255430''>to</span>
  <span m=''255500''>go</span> <span m=''255650''>over</span> <span m=''255910''>it,</span>
  <span m=''256740''>but</span> <span m=''256890''>it''s</span> <span m=''257060''>the</span>
  <span m=''258490''>same</span> <span m=''258760''>thing</span> <span m=''258920''>we''ve</span>
  <span m=''259040''>been</span> <span m=''259160''>doing</span> <span m=''259370''>before.</span>
  <span m=''261190''>You</span> <span m=''261390''>saw</span> <span m=''261640''>that</span>
  <span m=''261810''>in</span> <span m=''261899''>the</span> <span m=''261970''>system</span>
  <span m=''262300''>on</span> <span m=''262410''>rule-based</span> <span m=''262830''>control.</span>
  <span m=''263220''>It''s</span> <span m=''263340''>essentially</span> <span m=''263780''>the</span>
  <span m=''263860''>same</span> <span m=''264120''>matcher.</span> <span m=''264950''>In</span>
  <span m=''265020''>fact,</span> <span m=''265210''>I</span> <span m=''265260''>think</span>
  <span m=''265440''>the</span> <span m=''266320''>syntax</span> <span m=''266430''>is</span>
  <span m=''266770''>a</span> <span m=''266830''>little</span> <span m=''267080''>bit</span>
  <span m=''267270''>simpler</span> <span m=''268360''>because we''re</span> <span
  m=''268470''>not</span> <span m=''268650''>worrying</span> <span m=''268980''>about</span>
  <span m=''269460''>arbitrary</span> <span m=''269960''>constants</span> <span m=''270225''>and</span>
  <span m=''270490''>expressions</span> <span m=''271000''>and</span> <span m=''271130''>things.</span>
  <span m=''271400''>There''s just</span> <span m=''271740''>variables</span> <span
  m=''272290''>and</span> <span m=''272410''>constants.</span> </p><p><span m=''275790''>OK,</span>
  <span m=''276490''>well,</span> <span m=''276620''>given</span> <span m=''276930''>that,</span>
  <span m=''278560''>what''s</span> <span m=''278790''>a</span> <span m=''278840''>primitive</span>
  <span m=''279220''>query?</span> <span m=''282970''>Primitive</span> <span m=''283320''>query</span>
  <span m=''283530''>is</span> <span m=''283630''>going</span> <span m=''283690''>to</span>
  <span m=''283760''>be</span> <span m=''283900''>a</span> <span m=''283960''>rather</span>
  <span m=''284350''>complicated</span> <span m=''285000''>thing.</span> <span m=''286720''>It''s</span>
  <span m=''286900''>going</span> <span m=''286980''>to</span> <span m=''287070''>be--</span>
  <span m=''288100''>let''s</span> <span m=''288430''>think</span> <span m=''288580''>about</span>
  <span m=''288860''>the</span> <span m=''288940''>query</span> <span m=''291050''>job</span>
  <span m=''293150''>of</span> <span m=''293570''>x</span> <span m=''295600''>is</span>
  <span m=''300390''>d</span> <span m=''302110''>dot</span> <span m=''303090''>y.</span>
  <span m=''306850''>That''s</span> <span m=''307320''>a</span> <span m=''307370''>query</span>
  <span m=''307720''>we</span> <span m=''307850''>might</span> <span m=''308090''>type</span>
  <span m=''308360''>in.</span> <span m=''309400''>That''s</span> <span m=''309680''>going</span>
  <span m=''309750''>to</span> <span m=''309820''>be</span> <span m=''309960''>implemented</span>
  <span m=''310630''>in</span> <span m=''310770''>the</span> <span m=''310840''>system.</span>
  <span m=''314270''>We''ll</span> <span m=''314290''>think of</span> <span m=''314530''>it</span>
  <span m=''314690''>as</span> <span m=''314800''>this</span> <span m=''314960''>little</span>
  <span m=''315170''>box.</span> <span m=''315700''>Here''s</span> <span m=''315890''>the</span>
  <span m=''315960''>primitive</span> <span m=''316310''>query.</span> </p><p><span
  m=''318880''>What</span> <span m=''319060''>this</span> <span m=''319240''>little</span>
  <span m=''319380''>box</span> <span m=''319700''>is</span> <span m=''319800''>going</span>
  <span m=''319880''>to</span> <span m=''319970''>do</span> <span m=''322350''>is</span>
  <span m=''325060''>take</span> <span m=''325450''>in</span> <span m=''325800''>two</span>
  <span m=''326570''>streams</span> <span m=''332070''>and</span> <span m=''332260''>put</span>
  <span m=''332480''>out</span> <span m=''332720''>a</span> <span m=''332760''>stream.</span>
  <span m=''334030''>So</span> <span m=''334180''>the</span> <span m=''334280''>shape</span>
  <span m=''335100''>of</span> <span m=''335310''>a</span> <span m=''335370''>primitive</span>
  <span m=''335740''>query</span> <span m=''336510''>is</span> <span m=''336680''>that</span>
  <span m=''336810''>it''s</span> <span m=''336970''>a</span> <span m=''337020''>thing</span>
  <span m=''337310''>where</span> <span m=''337450''>two</span> <span m=''337650''>streams</span>
  <span m=''338000''>come</span> <span m=''338180''>in</span> <span m=''338740''>and</span>
  <span m=''338920''>one</span> <span m=''339110''>stream</span> <span m=''339410''>goes</span>
  <span m=''339660''>out.</span> <span m=''341120''>What</span> <span m=''341310''>these</span>
  <span m=''341470''>streams</span> <span m=''341730''>are</span> <span m=''341810''>going</span>
  <span m=''341890''>to</span> <span m=''341970''>be</span> <span m=''343020''>is</span>
  <span m=''343240''>down</span> <span m=''343520''>here</span> <span m=''345230''>is</span>
  <span m=''345450''>the</span> <span m=''345530''>database.</span> <span m=''351600''>So</span>
  <span m=''352120''>we</span> <span m=''352240''>imagine</span> <span m=''352590''>all</span>
  <span m=''352970''>the</span> <span m=''353060''>things</span> <span m=''353280''>in</span>
  <span m=''353350''>the</span> <span m=''353420''>database</span> <span m=''355940''>sort</span>
  <span m=''356120''>of</span> <span m=''356180''>sitting</span> <span m=''356490''>there</span>
  <span m=''356660''>in a stream</span> <span m=''357050''>and</span> <span m=''357260''>this</span>
  <span m=''357600''>thing</span> <span m=''357750''>sucks</span> <span m=''358060''>on</span>
  <span m=''358210''>them.</span> <span m=''360330''>So</span> <span m=''360640''>what</span>
  <span m=''360810''>are</span> <span m=''360890''>some</span> <span m=''361050''>things</span>
  <span m=''361270''>that</span> <span m=''361390''>might</span> <span m=''361570''>be</span>
  <span m=''361680''>in</span> <span m=''361750''>the</span> <span m=''361820''>database?</span>
  <span m=''362800''>Oh,</span> <span m=''368580''>job</span> <span m=''370160''>of
  Alyssa</span> <span m=''379470''>is</span> <span m=''379660''>something</span> <span
  m=''381680''>and</span> <span m=''382260''>some</span> <span m=''382440''>other</span>
  <span m=''382630''>job</span> <span m=''383020''>is</span> <span m=''383130''>something.</span>
  <span m=''385770''>So</span> <span m=''385970''>imagine</span> <span m=''386240''>all</span>
  <span m=''386450''>of</span> <span m=''386670''>the</span> <span m=''387970''>facts</span>
  <span m=''388330''>in</span> <span m=''388390''>the</span> <span m=''388480''>database</span>
  <span m=''389250''>sitting</span> <span m=''389560''>there</span> <span m=''389710''>in</span>
  <span m=''389800''>the</span> <span m=''389860''>stream.</span> <span m=''392040''>That''s</span>
  <span m=''392280''>what</span> <span m=''392390''>comes</span> <span m=''392650''>in</span>
  <span m=''392760''>here.</span> </p><p><span m=''393400''>What</span> <span m=''393570''>comes</span>
  <span m=''393820''>in</span> <span m=''393930''>here</span> <span m=''394940''>is</span>
  <span m=''395120''>a</span> <span m=''395170''>stream</span> <span m=''395670''>of</span>
  <span m=''395820''>dictionaries.</span> <span m=''398510''>So</span> <span m=''398910''>one</span>
  <span m=''399110''>particular</span> <span m=''399630''>dictionary</span> <span
  m=''400610''>might</span> <span m=''400960''>say</span> <span m=''407400''>y</span>
  <span m=''408050''>equals</span> <span m=''408580''>programmer.</span> <span m=''415470''>Now,</span>
  <span m=''415590''>what</span> <span m=''415720''>the</span> <span m=''415800''>query</span>
  <span m=''416170''>does</span> <span m=''417100''>when</span> <span m=''417200''>it</span>
  <span m=''417300''>gets</span> <span m=''417600''>in</span> <span m=''418380''>a</span>
  <span m=''418500''>dictionary</span> <span m=''419010''>from</span> <span m=''419170''>this</span>
  <span m=''419270''>stream,</span> <span m=''422070''>it</span> <span m=''422240''>finds</span>
  <span m=''422600''>all</span> <span m=''422910''>possible</span> <span m=''423470''>ways</span>
  <span m=''424300''>of</span> <span m=''424500''>matching</span> <span m=''425970''>the</span>
  <span m=''426090''>query</span> <span m=''427530''>against</span> <span m=''428700''>whatever</span>
  <span m=''429000''>is</span> <span m=''429100''>coming</span> <span m=''429380''>in</span>
  <span m=''429470''>from</span> <span m=''429600''>the</span> <span m=''429690''>database.</span>
  <span m=''431390''>It</span> <span m=''431510''>looks</span> <span m=''431690''>at</span>
  <span m=''431770''>the</span> <span m=''431850''>query</span> <span m=''432150''>as</span>
  <span m=''432280''>a</span> <span m=''432340''>pattern,</span> <span m=''433180''>matches
  it</span> <span m=''433660''>against</span> <span m=''435420''>any</span> <span
  m=''435670''>fact</span> <span m=''436010''>from</span> <span m=''436100''>the</span>
  <span m=''436200''>database</span> <span m=''436950''>or</span> <span m=''437140''>all</span>
  <span m=''437820''>possible</span> <span m=''438310''>ways</span> <span m=''438660''>of</span>
  <span m=''440530''>finding</span> <span m=''440870''>and</span> <span m=''440990''>matching</span>
  <span m=''441340''>the</span> <span m=''441580''>database</span> <span m=''443000''>with</span>
  <span m=''443190''>respect</span> <span m=''443970''>to</span> <span m=''444100''>this</span>
  <span m=''444330''>dictionary</span> <span m=''444830''>that''s</span> <span m=''445040''>coming</span>
  <span m=''445340''>in.</span> <span m=''447550''>So</span> <span m=''447810''>for</span>
  <span m=''448670''>each</span> <span m=''448850''>fact</span> <span m=''449130''>in</span>
  <span m=''449200''>the</span> <span m=''449290''>database,</span> <span m=''449760''>it</span>
  <span m=''449840''>calls</span> <span m=''450110''>the</span> <span m=''450180''>matcher</span>
  <span m=''450940''>using</span> <span m=''451190''>the</span> <span m=''451260''>pattern,</span>
  <span m=''453140''>fact,</span> <span m=''453620''>and</span> <span m=''453800''>dictionary.</span>
  <span m=''455110''>And</span> <span m=''455320''>every</span> <span m=''455580''>time</span>
  <span m=''455880''>it</span> <span m=''455970''>gets</span> <span m=''456850''>a</span>
  <span m=''456970''>good</span> <span m=''457180''>match,</span> <span m=''458270''>it</span>
  <span m=''458440''>puts</span> <span m=''458680''>out</span> <span m=''458840''>the</span>
  <span m=''458950''>extended</span> <span m=''459470''>dictionary.</span> </p><p><span
  m=''460420''>So,</span> <span m=''460880''>for</span> <span m=''461000''>example,</span>
  <span m=''461370''>if</span> <span m=''461450''>this</span> <span m=''461610''>one</span>
  <span m=''461760''>comes</span> <span m=''462000''>in</span> <span m=''463090''>and
  it</span> <span m=''463330''>finds</span> <span m=''463620''>a</span> <span m=''463670''>match,</span>
  <span m=''464610''>out</span> <span m=''464830''>will</span> <span m=''464940''>come</span>
  <span m=''465110''>a</span> <span m=''465170''>dictionary</span> <span m=''466532''>that</span>
  <span m=''466880''>in</span> <span m=''467090''>this</span> <span m=''467240''>case</span>
  <span m=''467500''>will</span> <span m=''467590''>have</span> <span m=''468440''>y</span>
  <span m=''468710''>equals</span> <span m=''469060''>programmer</span> <span m=''471590''>and</span>
  <span m=''471910''>x</span> <span m=''472170''>equals</span> <span m=''472510''>something.</span>
  <span m=''476740''>y</span> <span m=''476990''>is</span> <span m=''477240''>programmer,</span>
  <span m=''477750''>x is</span> <span m=''478140''>something,</span> <span m=''479020''>and</span>
  <span m=''479200''>d</span> <span m=''479410''>is</span> <span m=''479530''>whatever</span>
  <span m=''479870''>it found.</span> <span m=''481430''>And</span> <span m=''481780''>that''s</span>
  <span m=''482070''>all.</span> <span m=''483520''>And,</span> <span m=''484400''>of</span>
  <span m=''484550''>course,</span> <span m=''484750''>it''s</span> <span m=''484880''>going</span>
  <span m=''484950''>to</span> <span m=''485020''>try</span> <span m=''485290''>this</span>
  <span m=''485520''>for</span> <span m=''485710''>every</span> <span m=''486650''>fact</span>
  <span m=''487090''>in</span> <span m=''487160''>the</span> <span m=''487240''>dictionary.</span>
  <span m=''487980''>So</span> <span m=''488170''>it</span> <span m=''488250''>might</span>
  <span m=''488430''>find</span> <span m=''488660''>lots</span> <span m=''488990''>of</span>
  <span m=''489130''>them.</span> <span m=''489250''>It</span> <span m=''489660''>might</span>
  <span m=''489860''>find</span> <span m=''490070''>another</span> <span m=''490390''>one</span>
  <span m=''491320''>that says</span> <span m=''491550''>y</span> <span m=''491740''>equals</span>
  <span m=''492300''>programmer</span> <span m=''493496''>and</span> <span m=''493860''>x</span>
  <span m=''494110''>equals,</span> <span m=''495110''>and</span> <span m=''495570''>d</span>
  <span m=''496030''>equals.</span> </p><p><span m=''500040''>So</span> <span m=''500260''>for</span>
  <span m=''500380''>one</span> <span m=''500650''>frame</span> <span m=''500920''>coming</span>
  <span m=''501220''>in,</span> <span m=''501830''>it</span> <span m=''501990''>might</span>
  <span m=''502170''>put</span> <span m=''502330''>out--</span> <span m=''502750''>for</span>
  <span m=''502870''>one</span> <span m=''503010''>dictionary</span> <span m=''503410''>coming</span>
  <span m=''503670''>in,</span> <span m=''503770''>it</span> <span m=''503860''>might</span>
  <span m=''503980''>put</span> <span m=''504160''>out</span> <span m=''504270''>a</span>
  <span m=''504310''>lot</span> <span m=''504530''>of</span> <span m=''504600''>dictionaries,</span>
  <span m=''506460''>or</span> <span m=''507275''>it</span> <span m=''507640''>might</span>
  <span m=''507890''>put</span> <span m=''508020''>out</span> <span m=''508220''>none.</span>
  <span m=''510470''>It</span> <span m=''510630''>might</span> <span m=''510840''>have</span>
  <span m=''512080''>something</span> <span m=''512440''>that</span> <span m=''512600''>wouldn''t</span>
  <span m=''512760''>match</span> <span m=''514620''>like</span> <span m=''516890''>x</span>
  <span m=''517169''>equals</span> <span m=''517983''>FOO.</span> <span m=''519320''>This</span>
  <span m=''519480''>one</span> <span m=''519620''>might</span> <span m=''519880''>not</span>
  <span m=''520039''>match</span> <span m=''520299''>anything</span> <span m=''521610''>in</span>
  <span m=''521750''>which</span> <span m=''521919''>case</span> <span m=''522130''>nothing</span>
  <span m=''522730''>will</span> <span m=''522900''>go</span> <span m=''523049''>into</span>
  <span m=''523270''>this</span> <span m=''523380''>stream</span> <span m=''523720''>corresponding</span>
  <span m=''524380''>to</span> <span m=''524510''>this</span> <span m=''524750''>frame.</span>
  <span m=''527510''>Or</span> <span m=''528600''>what</span> <span m=''528740''>you</span>
  <span m=''528850''>might</span> <span m=''529060''>do</span> <span m=''529260''>is</span>
  <span m=''529730''>put</span> <span m=''530150''>in</span> <span m=''530280''>an</span>
  <span m=''530400''>empty</span> <span m=''530730''>frame,</span> <span m=''533020''>and</span>
  <span m=''533140''>an</span> <span m=''533240''>empty</span> <span m=''533560''>frame</span>
  <span m=''533880''>says</span> <span m=''534330''>try</span> <span m=''534950''>matching</span>
  <span m=''535510''>all ways--</span> <span m=''539930''>find</span> <span m=''540120''>all</span>
  <span m=''540340''>possible</span> <span m=''540760''>ways</span> <span m=''541020''>of</span>
  <span m=''541100''>matching</span> <span m=''541740''>the</span> <span m=''541860''>query</span>
  <span m=''542610''>against</span> <span m=''542880''>something</span> <span m=''543230''>in</span>
  <span m=''543300''>the</span> <span m=''543380''>database</span> <span m=''544240''>subject</span>
  <span m=''544730''>to</span> <span m=''544830''>no</span> <span m=''545030''>previous</span>
  <span m=''545470''>restrictions.</span> <span m=''547570''>And</span> <span m=''547730''>if</span>
  <span m=''547800''>you</span> <span m=''547880''>think</span> <span m=''548030''>about</span>
  <span m=''548230''>what</span> <span m=''548360''>that</span> <span m=''548590''>means,</span>
  <span m=''548800''>that''s</span> <span m=''549000''>just</span> <span m=''550400''>the</span>
  <span m=''550620''>computation</span> <span m=''551400''>that''s</span> <span m=''551600''>done</span>
  <span m=''551750''>when</span> <span m=''551880''>you</span> <span m=''552000''>type</span>
  <span m=''552290''>in a</span> <span m=''552470''>query</span> <span m=''553350''>right</span>
  <span m=''553610''>off.</span> <span m=''553980''>It</span> <span m=''554330''>tries</span>
  <span m=''554610''>to</span> <span m=''554700''>find</span> <span m=''554900''>all</span>
  <span m=''555080''>matches.</span> </p><p><span m=''556650''>So a</span> <span m=''556860''>primitive</span>
  <span m=''557340''>query</span> <span m=''557620''>sets</span> <span m=''557930''>up</span>
  <span m=''558050''>this</span> <span m=''558210''>mechanism.</span> <span m=''559370''>And</span>
  <span m=''559550''>what</span> <span m=''559690''>the</span> <span m=''559760''>language</span>
  <span m=''560210''>does,</span> <span m=''562820''>when</span> <span m=''562940''>you</span>
  <span m=''563040''>type</span> <span m=''563380''>in the</span> <span m=''563540''>query</span>
  <span m=''563840''>at</span> <span m=''563920''>the</span> <span m=''564000''>top</span>
  <span m=''564300''>level,</span> <span m=''564840''>it</span> <span m=''564960''>takes</span>
  <span m=''565240''>this</span> <span m=''565390''>mechanism,</span> <span m=''566110''>feeds</span>
  <span m=''566400''>in</span> <span m=''566560''>one</span> <span m=''566980''>single</span>
  <span m=''567440''>empty</span> <span m=''567750''>dictionary,</span> <span m=''570920''>and</span>
  <span m=''571090''>then</span> <span m=''571230''>for</span> <span m=''571360''>each</span>
  <span m=''571630''>thing</span> <span m=''571820''>that</span> <span m=''571950''>comes</span>
  <span m=''572240''>out</span> <span m=''573130''>takes</span> <span m=''574880''>the</span>
  <span m=''575080''>original</span> <span m=''575430''>query</span> <span m=''576650''>and</span>
  <span m=''576800''>instantiates</span> <span m=''578730''>the</span> <span m=''578860''>result</span>
  <span m=''579220''>with</span> <span m=''579330''>all</span> <span m=''579450''>the</span>
  <span m=''579530''>different</span> <span m=''579790''>dictionaries,</span> <span
  m=''580830''>producing</span> <span m=''581250''>a</span> <span m=''581530''>new</span>
  <span m=''581810''>stream</span> <span m=''582620''>of</span> <span m=''582730''>instantiated</span>
  <span m=''583600''>patterns</span> <span m=''584060''>here.</span> <span m=''584990''>And</span>
  <span m=''585150''>that''s</span> <span m=''585310''>what</span> <span m=''585440''>gets</span>
  <span m=''585640''>printed</span> <span m=''585900''>on</span> <span m=''585990''>the</span>
  <span m=''586090''>terminal.</span> <span m=''588170''>That''s</span> <span m=''588460''>the</span>
  <span m=''588550''>basic</span> <span m=''590150''>mechanism</span> <span m=''590650''>going</span>
  <span m=''590890''>on</span> <span m=''591080''>there.</span> </p><p><span m=''593510''>Well,</span>
  <span m=''594000''>why</span> <span m=''594260''>is</span> <span m=''594410''>that</span>
  <span m=''594570''>so</span> <span m=''594700''>complicated?</span> <span m=''596870''>You</span>
  <span m=''597350''>probably</span> <span m=''598010''>can</span> <span m=''598140''>think
  of</span> <span m=''598280''>a</span> <span m=''598320''>lot</span> <span m=''599100''>simpler</span>
  <span m=''599520''>ways</span> <span m=''599860''>to</span> <span m=''600000''>arrange</span>
  <span m=''600310''>this</span> <span m=''600480''>match</span> <span m=''600790''>for</span>
  <span m=''601100''>a</span> <span m=''601560''>primitive</span> <span m=''601940''>query</span>
  <span m=''602260''>rather</span> <span m=''602500''>than</span> <span m=''602630''>having</span>
  <span m=''602910''>all of</span> <span m=''603110''>these</span> <span m=''603260''>streams</span>
  <span m=''603620''>floating</span> <span m=''603920''>around.</span> <span m=''604725''>And</span>
  <span m=''605210''>the</span> <span m=''605500''>answer</span> <span m=''605790''>is--</span>
  <span m=''607290''>you</span> <span m=''607350''>probably</span> <span m=''607720''>guess</span>
  <span m=''608060''>already.</span> <span m=''610860''>The</span> <span m=''611090''>answer</span>
  <span m=''611320''>is</span> <span m=''611760''>this</span> <span m=''611980''>thing</span>
  <span m=''612850''>extends</span> <span m=''613390''>elegantly</span> <span m=''614530''>to</span>
  <span m=''615250''>implement</span> <span m=''615660''>the</span> <span m=''615740''>means</span>
  <span m=''616000''>of</span> <span m=''616090''>combination.</span> <span m=''617790''>So,</span>
  <span m=''618000''>for</span> <span m=''618200''>instance,</span> <span m=''620670''>suppose</span>
  <span m=''621070''>I</span> <span m=''621170''>don''t</span> <span m=''621410''>only</span>
  <span m=''621680''>want</span> <span m=''621790''>to</span> <span m=''621910''>do</span>
  <span m=''622090''>this.</span> <span m=''622470''>I</span> <span m=''622540''>don''t</span>
  <span m=''623450''>want</span> <span m=''623540''>to</span> <span m=''623640''>say</span>
  <span m=''623850''>who</span> <span m=''625400''>to</span> <span m=''625510''>be</span>
  <span m=''625660''>everybody''s</span> <span m=''626110''>job</span> <span m=''626350''>description.</span>
  </p><p><span m=''627230''>Suppose</span> <span m=''627520''>I</span> <span m=''627580''>want</span>
  <span m=''627690''>to</span> <span m=''627810''>say</span> <span m=''630010''>AND</span>
  <span m=''633640''>the</span> <span m=''634130''>job</span> <span m=''634570''>of</span>
  <span m=''634640''>x is</span> <span m=''635020''>d dot</span> <span m=''635420''>y</span>
  <span m=''636870''>and</span> <span m=''638990''>the</span> <span m=''639140''>supervisor</span>
  <span m=''644410''>of</span> <span m=''644770''>x</span> <span m=''646082''>is</span>
  <span m=''646520''>z.</span> <span m=''648800''>Now,</span> <span m=''649060''>supervisor</span>
  <span m=''649850''>of</span> <span m=''649930''>x is z</span> <span m=''651440''>is</span>
  <span m=''651590''>going</span> <span m=''651680''>to</span> <span m=''651770''>be</span>
  <span m=''651860''>another</span> <span m=''652190''>primitive</span> <span m=''652550''>query</span>
  <span m=''653730''>that</span> <span m=''653900''>has</span> <span m=''654130''>the</span>
  <span m=''654200''>same</span> <span m=''654500''>shape</span> <span m=''655750''>to</span>
  <span m=''656180''>take</span> <span m=''656440''>in</span> <span m=''656830''>a</span>
  <span m=''656920''>stream</span> <span m=''657420''>of</span> <span m=''657540''>data</span>
  <span m=''657830''>objects,</span> <span m=''659260''>a</span> <span m=''659370''>stream</span>
  <span m=''660180''>of</span> <span m=''660690''>initial</span> <span m=''661100''>dictionaries,</span>
  <span m=''661720''>which</span> <span m=''661920''>are</span> <span m=''661990''>the</span>
  <span m=''662570''>restrictions</span> <span m=''663190''>to</span> <span m=''663280''>try</span>
  <span m=''663520''>and</span> <span m=''664580''>use</span> <span m=''664810''>when</span>
  <span m=''664940''>you</span> <span m=''665050''>match,</span> <span m=''665560''>and</span>
  <span m=''665720''>it''s</span> <span m=''665860''>going</span> <span m=''665930''>to</span>
  <span m=''666010''>put</span> <span m=''666200''>out</span> <span m=''666360''>a</span>
  <span m=''666400''>stream</span> <span m=''666720''>of</span> <span m=''666800''>dictionaries.</span>
  <span m=''668700''>So</span> <span m=''668850''>that''s</span> <span m=''669050''>what</span>
  <span m=''669130''>this</span> <span m=''669470''>primitive</span> <span m=''669950''>query</span>
  <span m=''670260''>looks</span> <span m=''670500''>like.</span> <span m=''671680''>And</span>
  <span m=''671840''>how</span> <span m=''671980''>do I</span> <span m=''672110''>implement
  the</span> <span m=''672560''>AND?</span> <span m=''672910''>Well, it''s</span>
  <span m=''673170''>simple.</span> <span m=''673450''>I</span> <span m=''673520''>just</span>
  <span m=''673700''>hook</span> <span m=''673850''>them</span> <span m=''673980''>together.</span>
  <span m=''674880''>I</span> <span m=''675020''>take</span> <span m=''675210''>the</span>
  <span m=''675350''>output</span> <span m=''675650''>of</span> <span m=''675730''>this</span>
  <span m=''675960''>one,</span> <span m=''676615''>and</span> <span m=''677040''>I</span>
  <span m=''677260''>put</span> <span m=''677400''>that</span> <span m=''677570''>to</span>
  <span m=''677670''>the</span> <span m=''677790''>input</span> <span m=''678070''>of</span>
  <span m=''678150''>that</span> <span m=''678380''>one.</span> <span m=''679830''>And</span>
  <span m=''679940''>I</span> <span m=''680050''>take</span> <span m=''680260''>the</span>
  <span m=''680340''>dictionary</span> <span m=''680840''>here</span> <span m=''681030''>and</span>
  <span m=''681110''>I fan</span> <span m=''681200''>it out.</span> </p><p><span m=''686570''>And</span>
  <span m=''686750''>then</span> <span m=''686860''>you</span> <span m=''686940''>see</span>
  <span m=''687100''>how</span> <span m=''687210''>that''s</span> <span m=''687440''>going</span>
  <span m=''687520''>to</span> <span m=''687600''>work,</span> <span m=''688870''>because</span>
  <span m=''689440''>what''s</span> <span m=''689610''>going</span> <span m=''689670''>to</span>
  <span m=''689730''>happen</span> <span m=''690100''>is</span> <span m=''690220''>a</span>
  <span m=''690260''>frame</span> <span m=''691320''>will</span> <span m=''691440''>now</span>
  <span m=''691630''>come</span> <span m=''691890''>in</span> <span m=''691990''>here,</span>
  <span m=''692480''>which</span> <span m=''692820''>has</span> <span m=''694420''>a</span>
  <span m=''694530''>binding</span> <span m=''695080''>for</span> <span m=''695360''>x,</span>
  <span m=''695870''>y,</span> <span m=''696180''>and d.</span> <span m=''697920''>And</span>
  <span m=''698120''>then</span> <span m=''698350''>when</span> <span m=''698500''>this</span>
  <span m=''698670''>one</span> <span m=''698820''>gets</span> <span m=''699090''>it,</span>
  <span m=''699160''>it''ll</span> <span m=''699260''>say,</span> <span m=''699430''>oh,</span>
  <span m=''699870''>gee,</span> <span m=''700030''>subject</span> <span m=''700600''>to</span>
  <span m=''700730''>these</span> <span m=''700860''>restrictions,</span> <span m=''702210''>which</span>
  <span m=''702430''>now</span> <span m=''702900''>already</span> <span m=''703420''>have</span>
  <span m=''705160''>values</span> <span m=''705530''>in</span> <span m=''705600''>the</span>
  <span m=''705670''>dictionary</span> <span m=''706140''>for</span> <span m=''706300''>y</span>
  <span m=''707210''>and</span> <span m=''707390''>x</span> <span m=''708630''>and</span>
  <span m=''708800''>d,</span> <span m=''711880''>it</span> <span m=''712010''>looks</span>
  <span m=''712190''>in</span> <span m=''712250''>the</span> <span m=''712340''>database</span>
  <span m=''712850''>and</span> <span m=''712930''>says,</span> <span m=''713130''>gee,</span>
  <span m=''713220''>can I</span> <span m=''713420''>find</span> <span m=''713620''>any</span>
  <span m=''713760''>supervisor</span> <span m=''714380''>facts?</span> <span m=''716080''>And</span>
  <span m=''716220''>if</span> <span m=''716300''>it</span> <span m=''716410''>finds</span>
  <span m=''716740''>any,</span> <span m=''717220''>out will</span> <span m=''717475''>come</span>
  <span m=''717730''>dictionaries</span> <span m=''719690''>which</span> <span m=''719900''>have</span>
  <span m=''720120''>bindings</span> <span m=''720620''>for</span> <span m=''720750''>y</span>
  <span m=''722610''>and</span> <span m=''722830''>x</span> <span m=''725900''>and</span>
  <span m=''726170''>d</span> <span m=''728140''>and</span> <span m=''728670''>z</span>
  <span m=''729030''>now.</span> </p><p><span m=''732070''>And</span> <span m=''732240''>then</span>
  <span m=''732270''>notice</span> <span m=''732850''>that</span> <span m=''734370''>because</span>
  <span m=''735020''>the</span> <span m=''735130''>frames</span> <span m=''735570''>coming</span>
  <span m=''735830''>in</span> <span m=''735930''>here</span> <span m=''736220''>have</span>
  <span m=''736430''>these</span> <span m=''736610''>restrictions,</span> <span m=''737500''>that''s</span>
  <span m=''737920''>the</span> <span m=''738010''>thing</span> <span m=''738210''>that</span>
  <span m=''738340''>assures</span> <span m=''738880''>that</span> <span m=''739330''>when</span>
  <span m=''739440''>you</span> <span m=''739550''>do</span> <span m=''739720''>the</span>
  <span m=''739840''>AND,</span> <span m=''740540''>this</span> <span m=''740860''>x</span>
  <span m=''742320''>will</span> <span m=''742450''>mean</span> <span m=''742640''>the</span>
  <span m=''742710''>same</span> <span m=''743010''>thing</span> <span m=''743850''>as</span>
  <span m=''744070''>that</span> <span m=''744290''>x.</span> <span m=''746470''>Because</span>
  <span m=''746810''>by the</span> <span m=''746900''>time</span> <span m=''747810''>something</span>
  <span m=''748100''>comes</span> <span m=''748280''>floating</span> <span m=''748590''>in</span>
  <span m=''748690''>here,</span> <span m=''750030''>x has</span> <span m=''750520''>a
  value</span> <span m=''750990''>that</span> <span m=''751260''>you</span> <span
  m=''751370''>have</span> <span m=''751490''>to</span> <span m=''751610''>match</span>
  <span m=''751870''>against</span> <span m=''752150''>consistently.</span> <span
  m=''754460''>And</span> <span m=''754690''>then you</span> <span m=''754770''>remember</span>
  <span m=''755080''>from</span> <span m=''755180''>the</span> <span m=''755270''>code</span>
  <span m=''755520''>from</span> <span m=''755610''>the</span> <span m=''755710''>matcher,</span>
  <span m=''756140''>there</span> <span m=''756250''>was</span> <span m=''756370''>something</span>
  <span m=''756670''>in</span> <span m=''756770''>the</span> <span m=''757200''>way</span>
  <span m=''757390''>the</span> <span m=''757490''>matcher</span> <span m=''757750''>did</span>
  <span m=''757920''>dictionaries</span> <span m=''758410''>that</span> <span m=''758570''>arrange</span>
  <span m=''758910''>consistent</span> <span m=''759370''>matches.</span> <span m=''760710''>So</span>
  <span m=''761120''>there''s</span> <span m=''761360''>AND.</span> </p><p><span m=''764260''>The</span>
  <span m=''764400''>important</span> <span m=''764860''>point</span> <span m=''765100''>to</span>
  <span m=''765220''>notice</span> <span m=''766050''>is</span> <span m=''766230''>the</span>
  <span m=''766300''>general</span> <span m=''766620''>shape.</span> <span m=''768570''>Look</span>
  <span m=''768700''>at</span> <span m=''768840''>what</span> <span m=''768980''>happened:</span>
  <span m=''769290''>the</span> <span m=''769670''>AND</span> <span m=''770000''>of</span>
  <span m=''770090''>two</span> <span m=''770260''>queries,</span> <span m=''770680''>say,</span>
  <span m=''770820''>P</span> <span m=''771040''>and</span> <span m=''771190''>Q.</span>
  <span m=''772600''>Here''s</span> <span m=''772900''>P</span> <span m=''774680''>and</span>
  <span m=''775090''>Q.</span> <span m=''776870''>The</span> <span m=''777530''>AND</span>
  <span m=''777770''>of</span> <span m=''777850''>two</span> <span m=''778010''>queries,</span>
  <span m=''780400''>well, it</span> <span m=''780530''>looks</span> <span m=''780720''>like</span>
  <span m=''780960''>this.</span> <span m=''781190''>Each</span> <span m=''781430''>query</span>
  <span m=''781760''>takes</span> <span m=''782040''>in</span> <span m=''782140''>a</span>
  <span m=''782190''>stream</span> <span m=''783500''>from</span> <span m=''783640''>the</span>
  <span m=''783780''>database,</span> <span m=''784600''>a</span> <span m=''784710''>stream</span>
  <span m=''785010''>of</span> <span m=''785120''>inputs,</span> <span m=''786420''>and</span>
  <span m=''786620''>puts</span> <span m=''786830''>out</span> <span m=''786960''>a</span>
  <span m=''787000''>stream</span> <span m=''787420''>of</span> <span m=''787510''>outputs.</span>
  <span m=''790230''>And</span> <span m=''790410''>the</span> <span m=''790470''>important</span>
  <span m=''790950''>point</span> <span m=''791190''>to</span> <span m=''791290''>notice</span>
  <span m=''792290''>is</span> <span m=''792480''>that</span> <span m=''793440''>if</span>
  <span m=''793610''>I</span> <span m=''793690''>draw</span> <span m=''793930''>a</span>
  <span m=''793970''>box</span> <span m=''794320''>around</span> <span m=''794580''>this</span>
  <span m=''794780''>thing</span> <span m=''798980''>and</span> <span m=''799420''>say</span>
  <span m=''799620''>this</span> <span m=''799810''>is</span> <span m=''799960''>AND</span>
  <span m=''801766''>of</span> <span m=''802180''>P</span> <span m=''803000''>and</span>
  <span m=''803180''>Q,</span> <span m=''805750''>then</span> <span m=''806090''>that</span>
  <span m=''806500''>box</span> <span m=''808550''>has</span> <span m=''808760''>exactly</span>
  <span m=''809320''>the</span> <span m=''809390''>same</span> <span m=''809720''>overall</span>
  <span m=''810070''>shape.</span> <span m=''812360''>It''s</span> <span m=''812470''>something</span>
  <span m=''812700''>that</span> <span m=''812860''>takes</span> <span m=''813110''>in</span>
  <span m=''813190''>a</span> <span m=''813240''>stream</span> <span m=''813520''>from</span>
  <span m=''813620''>the</span> <span m=''813730''>database.</span> <span m=''814200''>Here</span>
  <span m=''814330''>it''s</span> <span m=''814440''>going</span> <span m=''814500''>to</span>
  <span m=''814560''>get</span> <span m=''814760''>fanned</span> <span m=''815060''>out</span>
  <span m=''815210''>inside,</span> <span m=''816660''>but</span> <span m=''816760''>from</span>
  <span m=''816900''>the</span> <span m=''817020''>outside</span> <span m=''817340''>you</span>
  <span m=''817420''>don''t</span> <span m=''817600''>see</span> <span m=''817750''>that.</span>
  <span m=''818160''>It</span> <span m=''818300''>takes</span> <span m=''818510''>an</span>
  <span m=''818600''>input</span> <span m=''818890''>stream</span> <span m=''819340''>and</span>
  <span m=''819580''>puts</span> <span m=''819780''>out</span> <span m=''819890''>an</span>
  <span m=''819930''>output</span> <span m=''820230''>stream.</span> </p><p><span
  m=''822230''>So</span> <span m=''822410''>this</span> <span m=''822590''>is</span>
  <span m=''822730''>AND.</span> <span m=''823570''>And</span> <span m=''823730''>then</span>
  <span m=''823820''>similarly,</span> <span m=''824570''>OR</span> <span m=''824900''>would</span>
  <span m=''825060''>look</span> <span m=''825220''>like</span> <span m=''825440''>this.</span>
  <span m=''826020''>OR</span> <span m=''826250''>would--</span> <span m=''828030''>although</span>
  <span m=''828310''>I</span> <span m=''828400''>didn''t</span> <span m=''828580''>show</span>
  <span m=''828700''>you</span> <span m=''828800''>examples</span> <span m=''829260''>of</span>
  <span m=''829360''>OR.</span> <span m=''829840''>OR</span> <span m=''830130''>would</span>
  <span m=''830270''>say</span> <span m=''830510''>can</span> <span m=''830670''>I</span>
  <span m=''830750''>find</span> <span m=''831570''>all</span> <span m=''831810''>ways</span>
  <span m=''832180''>of</span> <span m=''833360''>matching</span> <span m=''833770''>P</span>
  <span m=''833990''>or</span> <span m=''834250''>Q.</span> <span m=''835750''>So
  I</span> <span m=''835970''>have</span> <span m=''836200''>P and</span> <span m=''836520''>Q.</span>
  <span m=''836760''>Each</span> <span m=''837000''>will</span> <span m=''837290''>have</span>
  <span m=''837500''>their</span> <span m=''837640''>shape.</span> <span m=''844460''>And</span>
  <span m=''844560''>the</span> <span m=''844660''>way</span> <span m=''844810''>OR</span>
  <span m=''845080''>is</span> <span m=''845170''>implemented</span> <span m=''846300''>is</span>
  <span m=''848590''>I''ll</span> <span m=''848720''>take</span> <span m=''848960''>my</span>
  <span m=''849850''>database</span> <span m=''850360''>stream.</span> <span m=''852500''>I''ll</span>
  <span m=''852730''>fan</span> <span m=''853020''>it</span> <span m=''853110''>out.</span>
  <span m=''853490''>I''ll</span> <span m=''853670''>put</span> <span m=''853870''>one</span>
  <span m=''854090''>into</span> <span m=''854320''>P</span> <span m=''854700''>and</span>
  <span m=''855190''>one</span> <span m=''855380''>into</span> <span m=''855570''>Q.</span>
  <span m=''857530''>I''ll</span> <span m=''857630''>take</span> <span m=''857900''>my</span>
  <span m=''858900''>initial</span> <span m=''859870''>query</span> <span m=''860220''>stream</span>
  <span m=''860490''>coming</span> <span m=''860800''>in</span> <span m=''861000''>and</span>
  <span m=''861200''>fan it</span> <span m=''861610''>out.</span> <span m=''866750''>So</span>
  <span m=''866960''>I''ll</span> <span m=''867280''>look</span> <span m=''867390''>at</span>
  <span m=''867500''>all</span> <span m=''867680''>the</span> <span m=''867800''>answers</span>
  <span m=''868130''>I</span> <span m=''868190''>might</span> <span m=''868400''>get</span>
  <span m=''868570''>from</span> <span m=''868710''>P</span> <span m=''869270''>and</span>
  <span m=''869460''>all</span> <span m=''869580''>the</span> <span m=''869700''>answers</span>
  <span m=''869980''>I</span> <span m=''870050''>might</span> <span m=''870260''>get</span>
  <span m=''870420''>from</span> <span m=''870580''>Q,</span> <span m=''871660''>and</span>
  <span m=''871810''>I''ll</span> <span m=''871900''>put</span> <span m=''872120''>them</span>
  <span m=''872950''>through</span> <span m=''873170''>some</span> <span m=''873360''>sort</span>
  <span m=''873540''>of</span> <span m=''873620''>thing</span> <span m=''873750''>that</span>
  <span m=''873870''>appends</span> <span m=''874310''>them</span> <span m=''874730''>or
  merges</span> <span m=''875280''>the</span> <span m=''875370''>result</span> <span
  m=''876550''>into</span> <span m=''876780''>one</span> <span m=''877000''>stream,</span>
  <span m=''879720''>and</span> <span m=''879860''>that''s</span> <span m=''880120''>what</span>
  <span m=''880240''>will</span> <span m=''880330''>come</span> <span m=''880550''>out.</span>
  <span m=''881080''>And</span> <span m=''881830''>this</span> <span m=''882100''>whole</span>
  <span m=''882390''>thing</span> <span m=''882650''>from</span> <span m=''882810''>the</span>
  <span m=''882950''>outside</span> <span m=''887590''>is</span> <span m=''887850''>OR.</span>
  <span m=''892350''>And</span> <span m=''892480''>again,</span> <span m=''892720''>you</span>
  <span m=''892800''>see it</span> <span m=''892950''>has</span> <span m=''893140''>the</span>
  <span m=''893220''>same</span> <span m=''893940''>overall</span> <span m=''894410''>shape</span>
  <span m=''895150''>when</span> <span m=''895330''>looked</span> <span m=''895540''>at</span>
  <span m=''895700''>from</span> <span m=''895820''>the</span> <span m=''895940''>outside.</span>
  </p><p><span m=''901000''>What''s</span> <span m=''901270''>NOT?</span> <span m=''902020''>NOT</span>
  <span m=''902210''>works</span> <span m=''902400''>kind</span> <span m=''902530''>of</span>
  <span m=''902670''>the</span> <span m=''902730''>same</span> <span m=''903010''>way.</span>
  <span m=''904310''>If</span> <span m=''904570''>I</span> <span m=''904640''>have</span>
  <span m=''904820''>some</span> <span m=''905050''>query</span> <span m=''905480''>P,</span>
  <span m=''908860''>I</span> <span m=''908980''>take</span> <span m=''909270''>the</span>
  <span m=''912220''>primitive</span> <span m=''912610''>query</span> <span m=''912920''>for</span>
  <span m=''913070''>P.</span> <span m=''914690''>Here, I''m going to</span> <span
  m=''915040''>implement</span> <span m=''915570''>NOT</span> <span m=''915940''>P.</span>
  <span m=''918770''>And</span> <span m=''918940''>NOT''s</span> <span m=''919230''>just</span>
  <span m=''919490''>going to</span> <span m=''919600''>act</span> <span m=''919870''>as</span>
  <span m=''919950''>a</span> <span m=''920030''>filter.</span> <span m=''920720''>I''ll</span>
  <span m=''920850''>take in</span> <span m=''921200''>the</span> <span m=''921270''>database</span>
  <span m=''923380''>and</span> <span m=''924030''>my</span> <span m=''925330''>original</span>
  <span m=''926500''>stream</span> <span m=''926880''>of</span> <span m=''927050''>dictionaries</span>
  <span m=''927660''>coming</span> <span m=''927970''>in,</span> <span m=''928810''>and</span>
  <span m=''928970''>what</span> <span m=''929160''>NOT</span> <span m=''929480''>P</span>
  <span m=''929870''>will</span> <span m=''930313''>do</span> <span m=''931200''>is</span>
  <span m=''931950''>it</span> <span m=''932080''>will</span> <span m=''932210''>filter</span>
  <span m=''936700''>these</span> <span m=''936970''>guys.</span> <span m=''939020''>And</span>
  <span m=''939130''>the</span> <span m=''939250''>way</span> <span m=''939400''>it
  will</span> <span m=''939550''>filter</span> <span m=''939940''>it,</span> <span
  m=''940270''>it</span> <span m=''940380''>will say</span> <span m=''940520''>when</span>
  <span m=''940680''>I</span> <span m=''940760''>get</span> <span m=''941020''>in</span>
  <span m=''941750''>a</span> <span m=''941850''>dictionary</span> <span m=''942380''>here,</span>
  <span m=''943420''>I''ll</span> <span m=''943600''>find</span> <span m=''943910''>all</span>
  <span m=''944020''>the</span> <span m=''944090''>matches,</span> <span m=''944830''>and</span>
  <span m=''944990''>if</span> <span m=''945110''>I</span> <span m=''945190''>find</span>
  <span m=''945540''>any,</span> <span m=''945690''>I''ll</span> <span m=''945860''>throw</span>
  <span m=''946070''>it</span> <span m=''946140''>away.</span> <span m=''947460''>And</span>
  <span m=''947600''>if</span> <span m=''947700''>I</span> <span m=''947890''>don''t</span>
  <span m=''948090''>find</span> <span m=''948340''>any</span> <span m=''948500''>matches</span>
  <span m=''948900''>to</span> <span m=''948980''>something</span> <span m=''949310''>coming</span>
  <span m=''949580''>in</span> <span m=''949670''>here,</span> <span m=''950170''>I''ll</span>
  <span m=''950370''>just</span> <span m=''950590''>pass</span> <span m=''950880''>that</span>
  <span m=''951070''>through,</span> <span m=''952300''>so</span> <span m=''952500''>NOT</span>
  <span m=''952720''>is</span> <span m=''952830''>a</span> <span m=''952890''>pure</span>
  <span m=''953110''>filter.</span> </p><p><span m=''955560''>So</span> <span m=''955720''>AND</span>
  <span m=''956070''>is--</span> <span m=''956890''>think</span> <span m=''957100''>of</span>
  <span m=''957190''>these</span> <span m=''958020''>sort</span> <span m=''958210''>of</span>
  <span m=''958720''>electoral</span> <span m=''959090''>resistors</span> <span m=''959580''>or</span>
  <span m=''959660''>something.</span> <span m=''959980''>AND</span> <span m=''960240''>is</span>
  <span m=''960780''>series</span> <span m=''961160''>combination</span> <span m=''962580''>and</span>
  <span m=''962750''>OR</span> <span m=''962980''>is</span> <span m=''963090''>parallel</span>
  <span m=''963450''>combination.</span> <span m=''964960''>And</span> <span m=''965120''>then</span>
  <span m=''965280''>NOT</span> <span m=''965530''>is</span> <span m=''965890''>not</span>
  <span m=''966080''>going</span> <span m=''966150''>to</span> <span m=''966230''>extend</span>
  <span m=''966600''>any</span> <span m=''966780''>dictionaries</span> <span m=''967240''>at</span>
  <span m=''967320''>all.</span> <span m=''967460''>It''s</span> <span m=''967600''>just</span>
  <span m=''967700''>going</span> <span m=''967770''>to</span> <span m=''967850''>filter</span>
  <span m=''968300''>it.</span> <span m=''968750''>It''s going to</span> <span m=''968960''>throw</span>
  <span m=''969260''>away</span> <span m=''969430''>the</span> <span m=''969550''>ones</span>
  <span m=''969830''>for</span> <span m=''969930''>which</span> <span m=''970110''>it</span>
  <span m=''970220''>finds</span> <span m=''971160''>a</span> <span m=''971210''>way</span>
  <span m=''971330''>to</span> <span m=''971420''>match.</span> <span m=''972640''>And</span>
  <span m=''972800''>list</span> <span m=''972990''>value</span> <span m=''973190''>is</span>
  <span m=''973280''>sort</span> <span m=''973400''>of</span> <span m=''973520''>the</span>
  <span m=''973580''>same</span> <span m=''973860''>way.</span> <span m=''974540''>The</span>
  <span m=''974880''>filter''s a</span> <span m=''975240''>little</span> <span m=''975600''>more</span>
  <span m=''975790''>complicated.</span> <span m=''976600''>It</span> <span m=''976880''>applies
  to</span> <span m=''976960''>predicate.</span> </p><p><span m=''979640''>The</span>
  <span m=''980100''>major</span> <span m=''980520''>point</span> <span m=''980910''>to</span>
  <span m=''981060''>notice</span> <span m=''981410''>here,</span> <span m=''981620''>and</span>
  <span m=''981940''>it''s</span> <span m=''982110''>a</span> <span m=''982150''>major</span>
  <span m=''982430''>point</span> <span m=''982610''>we''ve</span> <span m=''982750''>looked</span>
  <span m=''982950''>at</span> <span m=''983080''>before,</span> <span m=''983670''>is</span>
  <span m=''983830''>this</span> <span m=''984060''>idea</span> <span m=''984480''>of</span>
  <span m=''984680''>closure.</span> <span m=''988490''>The</span> <span m=''988650''>things</span>
  <span m=''989240''>that</span> <span m=''989570''>we</span> <span m=''989730''>build</span>
  <span m=''990580''>as</span> <span m=''990750''>a</span> <span m=''990790''>means</span>
  <span m=''991030''>of</span> <span m=''991130''>combination</span> <span m=''991990''>have</span>
  <span m=''992200''>the</span> <span m=''992280''>same</span> <span m=''992910''>overall</span>
  <span m=''993880''>structure</span> <span m=''995750''>as</span> <span m=''995980''>the</span>
  <span m=''996070''>primitive</span> <span m=''996470''>things</span> <span m=''996710''>that</span>
  <span m=''996830''>we''re</span> <span m=''996960''>combining.</span> <span m=''999750''>So</span>
  <span m=''1000810''>the</span> <span m=''1000920''>AND</span> <span m=''1001220''>of</span>
  <span m=''1001310''>two</span> <span m=''1001480''>things</span> <span m=''1001710''>when</span>
  <span m=''1001820''>looked</span> <span m=''1002000''>at</span> <span m=''1002100''>from</span>
  <span m=''1002200''>the</span> <span m=''1002320''>outside</span> <span m=''1002780''>has</span>
  <span m=''1002950''>the</span> <span m=''1003030''>same</span> <span m=''1003310''>shape.</span>
  <span m=''1004630''>And</span> <span m=''1004750''>what</span> <span m=''1004870''>that</span>
  <span m=''1005080''>means</span> <span m=''1005540''>is</span> <span m=''1005740''>that</span>
  <span m=''1006970''>this</span> <span m=''1007190''>box</span> <span m=''1007500''>here</span>
  <span m=''1007720''>could</span> <span m=''1007890''>be</span> <span m=''1008320''>an</span>
  <span m=''1008470''>AND</span> <span m=''1008790''>or</span> <span m=''1008950''>an</span>
  <span m=''1009000''>OR</span> <span m=''1009380''>or a</span> <span m=''1009640''>NOT</span>
  <span m=''1009910''>or</span> <span m=''1010000''>something</span> <span m=''1010280''>because</span>
  <span m=''1010440''>it</span> <span m=''1010580''>has</span> <span m=''1010710''>the</span>
  <span m=''1010790''>same</span> <span m=''1011110''>shape</span> <span m=''1011560''>to</span>
  <span m=''1011780''>interface</span> <span m=''1012310''>to</span> <span m=''1012410''>the</span>
  <span m=''1013630''>larger</span> <span m=''1013960''>things.</span> </p><p><span
  m=''1014950''>It''s</span> <span m=''1015140''>the</span> <span m=''1015210''>same</span>
  <span m=''1015530''>thing</span> <span m=''1015740''>that</span> <span m=''1015840''>allowed</span>
  <span m=''1016160''>us</span> <span m=''1016290''>to</span> <span m=''1016380''>get</span>
  <span m=''1016980''>complexity</span> <span m=''1017370''>in the</span> <span m=''1017760''>Escher</span>
  <span m=''1018040''>picture</span> <span m=''1018430''>language</span> <span m=''1019680''>or</span>
  <span m=''1019820''>allows</span> <span m=''1020120''>you</span> <span m=''1020210''>to</span>
  <span m=''1020480''>immediately</span> <span m=''1020980''>build</span> <span m=''1021200''>up</span>
  <span m=''1021290''>these</span> <span m=''1021440''>complicated</span> <span m=''1021970''>structures</span>
  <span m=''1022370''>just</span> <span m=''1022580''>out</span> <span m=''1022700''>of</span>
  <span m=''1022790''>pairs.</span> <span m=''1024170''>It''s</span> <span m=''1024339''>closure.</span>
  <span m=''1026280''>And</span> <span m=''1026490''>that''s</span> <span m=''1026770''>the</span>
  <span m=''1026869''>thing</span> <span m=''1027589''>that</span> <span m=''1029730''>allowed</span>
  <span m=''1030010''>me</span> <span m=''1030150''>to</span> <span m=''1030220''>do</span>
  <span m=''1030420''>what</span> <span m=''1030550''>by</span> <span m=''1030760''>now</span>
  <span m=''1030920''>you</span> <span m=''1031040''>took</span> <span m=''1031250''>for</span>
  <span m=''1031359''>granted</span> <span m=''1031740''>when</span> <span m=''1031869''>I</span>
  <span m=''1031930''>said,</span> <span m=''1032089''>gee,</span> <span m=''1032260''>there''s</span>
  <span m=''1032450''>a</span> <span m=''1032510''>query</span> <span m=''1032829''>which</span>
  <span m=''1033020''>is</span> <span m=''1033130''>AND</span> <span m=''1033470''>of</span>
  <span m=''1034020''>job</span> <span m=''1034339''>and</span> <span m=''1034450''>salary,</span>
  <span m=''1034950''>and</span> <span m=''1035050''>I</span> <span m=''1035140''>said,</span>
  <span m=''1035290''>oh,</span> <span m=''1035369''>there''s</span> <span m=''1035540''>another</span>
  <span m=''1035829''>one,</span> <span m=''1035970''>which</span> <span m=''1036150''>is</span>
  <span m=''1036319''>AND</span> <span m=''1036569''>of</span> <span m=''1037190''>job,</span>
  <span m=''1037819''>a</span> <span m=''1037930''>NOT</span> <span m=''1038250''>of</span>
  <span m=''1038329''>something.</span> <span m=''1039260''>The</span> <span m=''1039390''>fact</span>
  <span m=''1039829''>that</span> <span m=''1040270''>I</span> <span m=''1040339''>can</span>
  <span m=''1040490''>do</span> <span m=''1040630''>that</span> <span m=''1040819''>is</span>
  <span m=''1040940''>a</span> <span m=''1040990''>direct</span> <span m=''1041339''>consequence</span>
  <span m=''1041869''>of</span> <span m=''1041950''>this closure</span> <span m=''1042420''>principle.</span>
  <span m=''1045230''>OK,</span> <span m=''1046030''>let''s</span> <span m=''1046230''>break</span>
  <span m=''1046490''>and then</span> <span m=''1046579''>we''ll</span> <span m=''1046750''>go
  on.</span> </p><p><span m=''1049520''>AUDIENCE: Where</span> <span m=''1049730''>does</span>
  <span m=''1049910''>the</span> <span m=''1049980''>dictionary</span> <span m=''1050470''>come
  from?</span> </p><p><span m=''1050710''>PROFESSOR: The</span> <span m=''1051090''>dictionary</span>
  <span m=''1051870''>comes</span> <span m=''1052220''>initially</span> <span m=''1054830''>from</span>
  <span m=''1055140''>what</span> <span m=''1055290''>you</span> <span m=''1055430''>type</span>
  <span m=''1055740''>in.</span> <span m=''1056030''>So</span> <span m=''1056220''>when</span>
  <span m=''1056350''>you</span> <span m=''1056440''>start</span> <span m=''1056850''>this</span>
  <span m=''1057070''>up,</span> <span m=''1059100''>the</span> <span m=''1059340''>first</span>
  <span m=''1059570''>thing</span> <span m=''1059710''>it</span> <span m=''1059800''>does</span>
  <span m=''1060020''>is</span> <span m=''1060130''>set</span> <span m=''1060280''>up</span>
  <span m=''1060390''>this</span> <span m=''1060530''>whole</span> <span m=''1060700''>structure.</span>
  <span m=''1061090''>It</span> <span m=''1061170''>puts</span> <span m=''1061370''>in</span>
  <span m=''1061510''>one</span> <span m=''1061750''>empty</span> <span m=''1062050''>dictionary.</span>
  <span m=''1065000''>And</span> <span m=''1065260''>if</span> <span m=''1065410''>all</span>
  <span m=''1065620''>you</span> <span m=''1065830''>have</span> <span m=''1066030''>is</span>
  <span m=''1066160''>one</span> <span m=''1066470''>primitive</span> <span m=''1066850''>query,</span>
  <span m=''1068300''>then</span> <span m=''1068450''>what will</span> <span m=''1068670''>come</span>
  <span m=''1068880''>out</span> <span m=''1069090''>is</span> <span m=''1069200''>a</span>
  <span m=''1069240''>bunch</span> <span m=''1069520''>of</span> <span m=''1069610''>dictionaries</span>
  <span m=''1070190''>with</span> <span m=''1070330''>things</span> <span m=''1070610''>filled
  in.</span> <span m=''1072310''>The</span> <span m=''1072480''>general</span> <span
  m=''1072880''>situation</span> <span m=''1073460''>that</span> <span m=''1073560''>I</span>
  <span m=''1073650''>have</span> <span m=''1073880''>here</span> <span m=''1074520''>is</span>
  <span m=''1074680''>when</span> <span m=''1074900''>this</span> <span m=''1075140''>is</span>
  <span m=''1075240''>in</span> <span m=''1075330''>the</span> <span m=''1075410''>middle</span>
  <span m=''1076440''>of</span> <span m=''1076590''>some</span> <span m=''1076870''>nest</span>
  <span m=''1077240''>of</span> <span m=''1078790''>combined</span> <span m=''1079300''>things.</span>
  </p><p><span m=''1082380''>Let''s</span> <span m=''1082570''>look</span> <span m=''1082660''>at</span>
  <span m=''1082760''>the</span> <span m=''1082830''>picture</span> <span m=''1083170''>over</span>
  <span m=''1083330''>here.</span> <span m=''1083790''>This</span> <span m=''1084540''>supervisor</span>
  <span m=''1085290''>query</span> <span m=''1085840''>gets</span> <span m=''1086050''>in</span>
  <span m=''1086130''>some</span> <span m=''1086300''>dictionary.</span> <span m=''1086730''>Where</span>
  <span m=''1086960''>did</span> <span m=''1087100''>this</span> <span m=''1087270''>one</span>
  <span m=''1087440''>come</span> <span m=''1087650''>from?</span> <span m=''1088730''>This</span>
  <span m=''1088940''>dictionary</span> <span m=''1089410''>came</span> <span m=''1089700''>from</span>
  <span m=''1089830''>the</span> <span m=''1089950''>fact</span> <span m=''1090440''>that</span>
  <span m=''1092870''>I''m</span> <span m=''1093020''>looking</span> <span m=''1093290''>at</span>
  <span m=''1093360''>the</span> <span m=''1093480''>output</span> <span m=''1093870''>of</span>
  <span m=''1093980''>this</span> <span m=''1094190''>primitive</span> <span m=''1094560''>query.</span>
  <span m=''1096260''>So</span> <span m=''1096630''>maybe</span> <span m=''1096890''>to</span>
  <span m=''1096970''>be</span> <span m=''1097090''>very</span> <span m=''1097380''>specific,</span>
  <span m=''1098390''>if</span> <span m=''1098880''>I</span> <span m=''1099070''>literally</span>
  <span m=''1099600''>typed</span> <span m=''1099930''>in</span> <span m=''1100070''>just</span>
  <span m=''1100370''>this</span> <span m=''1100580''>query</span> <span m=''1100930''>at</span>
  <span m=''1101010''>the</span> <span m=''1101100''>top</span> <span m=''1101380''>level,</span>
  <span m=''1102270''>this</span> <span m=''1102530''>AND,</span> <span m=''1103120''>what
  would</span> <span m=''1103400''>actually</span> <span m=''1103820''>happen is it</span>
  <span m=''1104220''>would</span> <span m=''1104380''>build</span> <span m=''1104620''>this</span>
  <span m=''1104710''>structure</span> <span m=''1105590''>and</span> <span m=''1105770''>start</span>
  <span m=''1106100''>up</span> <span m=''1106230''>this</span> <span m=''1106400''>whole</span>
  <span m=''1106590''>thing</span> <span m=''1108890''>with</span> <span m=''1109060''>one</span>
  <span m=''1109350''>empty</span> <span m=''1109600''>dictionary.</span> <span m=''1111770''>And</span>
  <span m=''1111940''>now</span> <span m=''1112330''>this</span> <span m=''1112580''>one</span>
  <span m=''1112720''>would</span> <span m=''1112860''>process,</span> <span m=''1113270''>and
  a</span> <span m=''1113370''>whole</span> <span m=''1113550''>bunch</span> <span
  m=''1113770''>of</span> <span m=''1113850''>dictionaries</span> <span m=''1114350''>would</span>
  <span m=''1114460''>come</span> <span m=''1114680''>out</span> <span m=''1115200''>with</span>
  <span m=''1115350''>x,</span> <span m=''1115600''>y''s</span> <span m=''1116490''>and</span>
  <span m=''1116720''>d''s</span> <span m=''1116990''>in</span> <span m=''1117100''>them.</span>
  <span m=''1118640''>Run it</span> <span m=''1118910''>through</span> <span m=''1119100''>this</span>
  <span m=''1119340''>one.</span> </p><p><span m=''1120190''>So</span> <span m=''1120330''>now</span>
  <span m=''1121050''>that''s</span> <span m=''1121270''>the</span> <span m=''1121380''>input</span>
  <span m=''1121670''>to</span> <span m=''1121760''>this</span> <span m=''1121970''>one.</span>
  <span m=''1122160''>This</span> <span m=''1122330''>one</span> <span m=''1122460''>would</span>
  <span m=''1122580''>now</span> <span m=''1122740''>put</span> <span m=''1122920''>out</span>
  <span m=''1123070''>some</span> <span m=''1123230''>other</span> <span m=''1123400''>stuff.</span>
  <span m=''1125040''>And if</span> <span m=''1125280''>this</span> <span m=''1125540''>itself</span>
  <span m=''1125990''>were</span> <span m=''1126090''>buried</span> <span m=''1126430''>in</span>
  <span m=''1126520''>some</span> <span m=''1127610''>larger</span> <span m=''1127950''>thing,</span>
  <span m=''1129370''>like</span> <span m=''1130030''>an</span> <span m=''1130110''>OR</span>
  <span m=''1130410''>of</span> <span m=''1130480''>something,</span> <span m=''1133510''>then</span>
  <span m=''1133660''>that</span> <span m=''1133830''>would</span> <span m=''1133990''>go</span>
  <span m=''1134620''>feed</span> <span m=''1134860''>into</span> <span m=''1135050''>the</span>
  <span m=''1135140''>next</span> <span m=''1135420''>one.</span> <span m=''1138560''>So</span>
  <span m=''1138790''>you</span> <span m=''1138960''>initially</span> <span m=''1139360''>get</span>
  <span m=''1139500''>only</span> <span m=''1139750''>one</span> <span m=''1139940''>empty</span>
  <span m=''1140180''>dictionary</span> <span m=''1140590''>when</span> <span m=''1140730''>you</span>
  <span m=''1140780''>start</span> <span m=''1141130''>it,</span> <span m=''1141480''>but</span>
  <span m=''1141860''>as</span> <span m=''1142120''>you''re</span> <span m=''1142260''>in</span>
  <span m=''1142320''>the</span> <span m=''1142400''>middle</span> <span m=''1142640''>of</span>
  <span m=''1142720''>processing</span> <span m=''1143230''>these</span> <span m=''1143380''>compounds</span>
  <span m=''1143900''>things,</span> <span m=''1144120''>that''s</span> <span m=''1144300''>where</span>
  <span m=''1144400''>these</span> <span m=''1144600''>cascades</span> <span m=''1145110''>of</span>
  <span m=''1145190''>dictionaries</span> <span m=''1145640''>start getting</span>
  <span m=''1145920''>generated.</span> </p><p><span m=''1147660''>AUDIENCE: Dictionaries</span>
  <span m=''1148150''>only</span> <span m=''1149920''>come</span> <span m=''1150110''>about</span>
  <span m=''1150380''>as</span> <span m=''1150450''>a</span> <span m=''1150530''>result</span>
  <span m=''1150910''>of</span> <span m=''1151030''>using</span> <span m=''1151410''>the</span>
  <span m=''1151700''>queries?</span> <span m=''1155120''>Or</span> <span m=''1155710''>do</span>
  <span m=''1155810''>they</span> <span m=''1157120''>become--</span> <span m=''1158280''>do</span>
  <span m=''1158620''>they</span> <span m=''1159330''>stay</span> <span m=''1159640''>someplace</span>
  <span m=''1161040''>in</span> <span m=''1161210''>space</span> <span m=''1161580''>like</span>
  <span m=''1161800''>the</span> <span m=''1161890''>database</span> <span m=''1162400''>does?</span>
  <span m=''1163220''>Are</span> <span m=''1163690''>these</span> <span m=''1164050''>temporary</span>
  <span m=''1164520''>items?</span> </p><p><span m=''1164980''>PROFESSOR: They''re</span>
  <span m=''1165130''>created</span> <span m=''1165640''>temporarily</span> <span
  m=''1166320''>in</span> <span m=''1166390''>the</span> <span m=''1166470''>matcher.</span>
  <span m=''1168030''>Really,</span> <span m=''1168410''>they''re</span> <span m=''1168900''>someplace</span>
  <span m=''1169330''>in</span> <span m=''1169430''>storage.</span> <span m=''1169880''>Initially,</span>
  <span m=''1170580''>someone</span> <span m=''1171030''>creates</span> <span m=''1171400''>a</span>
  <span m=''1171460''>thing</span> <span m=''1171650''>called</span> <span m=''1171940''>the</span>
  <span m=''1172120''>empty</span> <span m=''1172430''>dictionary</span> <span m=''1174220''>that</span>
  <span m=''1174470''>gets</span> <span m=''1174880''>initially</span> <span m=''1175440''>fed</span>
  <span m=''1175680''>to this</span> <span m=''1175950''>match</span> <span m=''1176240''>procedure,</span>
  <span m=''1176740''>and then</span> <span m=''1176870''>the</span> <span m=''1177000''>match</span>
  <span m=''1177290''>procedure</span> <span m=''1177820''>builds</span> <span m=''1178340''>some</span>
  <span m=''1178510''>dictionaries,</span> <span m=''1179080''>and</span> <span m=''1179150''>they</span>
  <span m=''1179240''>get</span> <span m=''1179410''>passed</span> <span m=''1179710''>on
  and</span> <span m=''1179970''>on.</span> </p><p><span m=''1180950''>AUDIENCE: OK,
  so</span> <span m=''1181180''>they''ll</span> <span m=''1181320''>go</span> <span
  m=''1181510''>way</span> <span m=''1181780''>after</span> <span m=''1181930''>the</span>
  <span m=''1182160''>match?</span> </p><p><span m=''1183526''>PROFESSOR: They''ll</span>
  <span m=''1183910''>go</span> <span m=''1184110''>away</span> <span m=''1184270''>when</span>
  <span m=''1184420''>no</span> <span m=''1184530''>one</span> <span m=''1184680''>needs</span>
  <span m=''1184900''>them</span> <span m=''1185000''>again,</span> <span m=''1185240''>yeah.</span>
  </p><p><span m=''1191900''>AUDIENCE: It</span> <span m=''1192010''>appears</span>
  <span m=''1192390''>that</span> <span m=''1192590''>the</span> <span m=''1192790''>AND</span>
  <span m=''1193140''>performs</span> <span m=''1193700''>some</span> <span m=''1193780''>redundant</span>
  <span m=''1194230''>searches</span> <span m=''1194640''>of</span> <span m=''1194720''>the</span>
  <span m=''1194800''>database.</span> <span m=''1196050''>If</span> <span m=''1196300''>the</span>
  <span m=''1196540''>first</span> <span m=''1196770''>clause</span> <span m=''1197210''>matched,</span>
  <span m=''1197770''>let''s say,</span> <span m=''1197880''>the</span> <span m=''1197940''>third</span>
  <span m=''1198190''>element</span> <span m=''1198660''>and not</span> <span m=''1198920''>on
  the</span> <span m=''1198990''>first</span> <span m=''1199310''>two elements,</span>
  <span m=''1200016''>the</span> <span m=''1200370''>second</span> <span m=''1201400''>clause</span>
  <span m=''1201680''>is</span> <span m=''1201820''>going</span> <span m=''1201890''>to</span>
  <span m=''1201970''>look</span> <span m=''1202150''>at</span> <span m=''1202220''>those</span>
  <span m=''1202410''>first two</span> <span m=''1202730''>elements</span> <span m=''1203180''>again,</span>
  <span m=''1204340''>discarding</span> <span m=''1204890''>them</span> <span m=''1205610''>because</span>
  <span m=''1205950''>they</span> <span m=''1206020''>don''t</span> <span m=''1206260''>match.</span>
  <span m=''1206700''>The</span> <span m=''1207220''>match</span> <span m=''1207580''>is</span>
  <span m=''1207700''>already</span> <span m=''1208040''>in the</span> <span m=''1208080''>dictionary.</span>
  <span m=''1210000''>Would</span> <span m=''1210180''>it</span> <span m=''1210610''>makes</span>
  <span m=''1210990''>sense</span> <span m=''1211230''>to</span> <span m=''1211350''>carry</span>
  <span m=''1211700''>the</span> <span m=''1211830''>data</span> <span m=''1212300''>element</span>
  <span m=''1212730''>from the</span> <span m=''1212920''>database</span> <span m=''1213380''>along</span>
  <span m=''1213690''>with the</span> <span m=''1214000''>dictionary?</span> </p><p><span
  m=''1217120''>PROFESSOR: Well,</span> <span m=''1217300''>in</span> <span m=''1217440''>general,</span>
  <span m=''1217780''>there</span> <span m=''1217900''>are</span> <span m=''1217920''>other</span>
  <span m=''1218150''>ways</span> <span m=''1218410''>to</span> <span m=''1218550''>arrange</span>
  <span m=''1218890''>this</span> <span m=''1219010''>search,</span> <span m=''1220200''>and</span>
  <span m=''1220280''>there''s</span> <span m=''1220440''>some</span> <span m=''1220610''>analysis</span>
  <span m=''1221220''>that</span> <span m=''1221360''>you</span> <span m=''1221470''>can</span>
  <span m=''1221610''>do.</span> <span m=''1221740''>I</span> <span m=''1221810''>think</span>
  <span m=''1222000''>there''s</span> <span m=''1222180''>a</span> <span m=''1222230''>problem</span>
  <span m=''1222670''>in</span> <span m=''1222740''>the</span> <span m=''1222810''>book,</span>
  <span m=''1223970''>which</span> <span m=''1224130''>talks</span> <span m=''1224370''>about</span>
  <span m=''1224540''>a</span> <span m=''1224600''>different</span> <span m=''1225020''>way</span>
  <span m=''1225240''>that</span> <span m=''1225390''>you</span> <span m=''1225550''>can</span>
  <span m=''1225720''>cascade</span> <span m=''1226320''>AND</span> <span m=''1226960''>to</span>
  <span m=''1227210''>eliminate</span> <span m=''1227680''>various</span> <span m=''1228040''>kinds</span>
  <span m=''1228340''>of</span> <span m=''1228440''>redundancies.</span> <span m=''1229850''>This</span>
  <span m=''1230030''>one</span> <span m=''1230160''>is</span> <span m=''1230250''>meant</span>
  <span m=''1230430''>to</span> <span m=''1230510''>be--</span> <span m=''1231380''>was</span>
  <span m=''1231560''>mainly</span> <span m=''1232250''>meant</span> <span m=''1232440''>to</span>
  <span m=''1232500''>be</span> <span m=''1232590''>very</span> <span m=''1232820''>simple</span>
  <span m=''1233170''>so</span> <span m=''1233290''>you</span> <span m=''1233430''>can</span>
  <span m=''1233550''>see</span> <span m=''1233690''>how</span> <span m=''1233790''>they</span>
  <span m=''1233910''>fit</span> <span m=''1234090''>together.</span> <span m=''1234650''>But</span>
  <span m=''1234910''>you''re</span> <span m=''1235010''>quite</span> <span m=''1235230''>right.</span>
  <span m=''1235380''>There are</span> <span m=''1235500''>redundancies</span> <span
  m=''1236160''>here</span> <span m=''1236290''>that</span> <span m=''1236450''>you</span>
  <span m=''1236570''>can</span> <span m=''1236710''>get</span> <span m=''1236910''>rid</span>
  <span m=''1237080''>of.</span> <span m=''1238370''>That''s</span> <span m=''1238830''>another</span>
  <span m=''1239120''>reason</span> <span m=''1239350''>why</span> <span m=''1239490''>this</span>
  <span m=''1239660''>language</span> <span m=''1240020''>is</span> <span m=''1240110''>somewhat</span>
  <span m=''1240420''>slow.</span> <span m=''1241190''>There</span> <span m=''1241330''>are
  a</span> <span m=''1241350''>lot</span> <span m=''1241670''>smarter</span> <span
  m=''1241950''>things</span> <span m=''1242190''>you</span> <span m=''1242300''>can</span>
  <span m=''1242440''>do.</span> <span m=''1242930''>We''re</span> <span m=''1243070''>just</span>
  <span m=''1243140''>trying</span> <span m=''1243360''>to</span> <span m=''1243610''>show</span>
  <span m=''1243780''>you</span> <span m=''1243910''>a</span> <span m=''1243950''>very</span>
  <span m=''1244610''>simple,</span> <span m=''1245010''>in</span> <span m=''1245130''>principle,</span>
  <span m=''1245590''>implementation.</span> </p><p><span m=''1251220''>AUDIENCE:
  Did you</span> <span m=''1251500''>model</span> <span m=''1251880''>this</span>
  <span m=''1252080''>language</span> <span m=''1252590''>on</span> <span m=''1252860''>Prolog,</span>
  <span m=''1253215''>or</span> <span m=''1253570''>did it just</span> <span m=''1253790''>come</span>
  <span m=''1254060''>out</span> <span m=''1254220''>looking</span> <span m=''1254530''>like</span>
  <span m=''1254770''>Prolog?</span> </p><p><span m=''1264960''>PROFESSOR: Well,</span>
  <span m=''1265110''>Jerry</span> <span m=''1265340''>insulted</span> <span m=''1265840''>a</span>
  <span m=''1265860''>whole</span> <span m=''1266010''>bunch</span> <span m=''1266230''>of</span>
  <span m=''1266380''>people</span> <span m=''1266540''>yesterday,</span> <span m=''1267190''>so</span>
  <span m=''1267390''>I might</span> <span m=''1267550''>as</span> <span m=''1267730''>well</span>
  <span m=''1267870''>say</span> <span m=''1268040''>that</span> <span m=''1268190''>the</span>
  <span m=''1268310''>MIT</span> <span m=''1268750''>attitude</span> <span m=''1269150''>towards</span>
  <span m=''1269410''>Prolog</span> <span m=''1270310''>is</span> <span m=''1270450''>something</span>
  <span m=''1270750''>that</span> <span m=''1270910''>people</span> <span m=''1271180''>did</span>
  <span m=''1271370''>in</span> <span m=''1271460''>about</span> <span m=''1271720''>1971</span>
  <span m=''1272640''>and</span> <span m=''1272750''>decided</span> <span m=''1273170''>that</span>
  <span m=''1273290''>it</span> <span m=''1273400''>wasn''t</span> <span m=''1273690''>really</span>
  <span m=''1273920''>the</span> <span m=''1274030''>right</span> <span m=''1274310''>thing</span>
  <span m=''1275030''>and</span> <span m=''1275210''>stopped.</span> <span m=''1276120''>So</span>
  <span m=''1276370''>we</span> <span m=''1277580''>modeled</span> <span m=''1277950''>this</span>
  <span m=''1278160''>on</span> <span m=''1281230''>the</span> <span m=''1281330''>sort</span>
  <span m=''1281470''>of</span> <span m=''1281620''>natural</span> <span m=''1282020''>way</span>
  <span m=''1282180''>that</span> <span m=''1282330''>this</span> <span m=''1282480''>thing</span>
  <span m=''1282640''>was</span> <span m=''1282820''>done</span> <span m=''1283270''>in</span>
  <span m=''1283410''>about</span> <span m=''1283660''>1971,</span> <span m=''1285200''>except</span>
  <span m=''1285540''>at</span> <span m=''1285600''>that</span> <span m=''1285810''>point,</span>
  <span m=''1286020''>we</span> <span m=''1286140''>didn''t</span> <span m=''1286370''>do</span>
  <span m=''1286590''>it with</span> <span m=''1286720''>streams.</span> <span m=''1291350''>After</span>
  <span m=''1291540''>we were</span> <span m=''1291770''>using</span> <span m=''1292050''>it</span>
  <span m=''1292150''>for</span> <span m=''1292260''>about</span> <span m=''1292540''>six</span>
  <span m=''1292770''>months,</span> <span m=''1293020''>we</span> <span m=''1293140''>discovered</span>
  <span m=''1293750''>that</span> <span m=''1293910''>it</span> <span m=''1294000''>had</span>
  <span m=''1294190''>all</span> <span m=''1294330''>these</span> <span m=''1294520''>problems,</span>
  <span m=''1294960''>some</span> <span m=''1295100''>of</span> <span m=''1295190''>which</span>
  <span m=''1295360''>I''ll</span> <span m=''1295460''>talk</span> <span m=''1295700''>about</span>
  <span m=''1295970''>later.</span> <span m=''1297330''>And</span> <span m=''1297640''>we</span>
  <span m=''1297760''>said,</span> <span m=''1298200''>gee,</span> <span m=''1298690''>Prolog</span>
  <span m=''1299080''>must</span> <span m=''1299280''>have</span> <span m=''1299370''>fixed</span>
  <span m=''1299660''>those,</span> <span m=''1299950''>and</span> <span m=''1300050''>then</span>
  <span m=''1300170''>we</span> <span m=''1300310''>found</span> <span m=''1300570''>out</span>
  <span m=''1300680''>that</span> <span m=''1300810''>it</span> <span m=''1300910''>didn''t.</span>
  <span m=''1301250''>So</span> <span m=''1301360''>this</span> <span m=''1301530''>does</span>
  <span m=''1301710''>about</span> <span m=''1301960''>the</span> <span m=''1302040''>same</span>
  <span m=''1302280''>thing</span> <span m=''1302470''>as</span> <span m=''1302580''>Prolog.</span>
  </p><p><span m=''1303460''>AUDIENCE: Does Prolog</span> <span m=''1303870''>use</span>
  <span m=''1304280''>streams?</span> </p><p><span m=''1304950''>PROFESSOR: No.</span>
  <span m=''1308540''>In</span> <span m=''1309130''>how</span> <span m=''1309290''>it</span>
  <span m=''1309400''>behaves,</span> <span m=''1309860''>it</span> <span m=''1309970''>behaves</span>
  <span m=''1310270''>a</span> <span m=''1310310''>lot</span> <span m=''1310500''>like</span>
  <span m=''1310660''>Prolog.</span> <span m=''1311040''>Prolog</span> <span m=''1311470''>uses</span>
  <span m=''1311770''>a</span> <span m=''1311830''>backtracking</span> <span m=''1312420''>strategy.</span>
  <span m=''1313800''>But</span> <span m=''1313930''>the</span> <span m=''1314060''>other</span>
  <span m=''1314220''>thing</span> <span m=''1314380''>that''s</span> <span m=''1314540''>really</span>
  <span m=''1314750''>good</span> <span m=''1314960''>about</span> <span m=''1315220''>Prolog</span>
  <span m=''1315740''>that</span> <span m=''1315910''>makes</span> <span m=''1316160''>it</span>
  <span m=''1316980''>a</span> <span m=''1317110''>usable</span> <span m=''1317590''>thing</span>
  <span m=''1318400''>is</span> <span m=''1318570''>that</span> <span m=''1318750''>there''s</span>
  <span m=''1318940''>a</span> <span m=''1319010''>really</span> <span m=''1319650''>very,</span>
  <span m=''1319950''>very</span> <span m=''1322440''>well-engineered</span> <span
  m=''1323080''>compiler</span> <span m=''1323570''>technology</span> <span m=''1324160''>that</span>
  <span m=''1324330''>makes</span> <span m=''1324540''>it</span> <span m=''1324620''>run</span>
  <span m=''1324830''>fast.</span> <span m=''1326660''>So</span> <span m=''1327100''>although</span>
  <span m=''1327340''>you</span> <span m=''1327480''>saw</span> <span m=''1327720''>the</span>
  <span m=''1327770''>merge</span> <span m=''1328630''>spitting</span> <span m=''1329000''>out</span>
  <span m=''1329120''>these</span> <span m=''1329260''>answers</span> <span m=''1329590''>very,</span>
  <span m=''1329970''>very</span> <span m=''1330250''>slowly,</span> <span m=''1331710''>a</span>
  <span m=''1331830''>real</span> <span m=''1332020''>Prolog</span> <span m=''1332440''>will</span>
  <span m=''1332560''>run</span> <span m=''1332790''>very,</span> <span m=''1333080''>very</span>
  <span m=''1333280''>fast.</span> <span m=''1334760''>Because</span> <span m=''1335100''>even</span>
  <span m=''1335270''>though</span> <span m=''1335390''>it''s</span> <span m=''1335450''>sort</span>
  <span m=''1335700''>of</span> <span m=''1335800''>doing</span> <span m=''1336080''>this,</span>
  <span m=''1336520''>the</span> <span m=''1336800''>real</span> <span m=''1336970''>work</span>
  <span m=''1337240''>that</span> <span m=''1337350''>went</span> <span m=''1337480''>into</span>
  <span m=''1337650''>Prolog</span> <span m=''1338120''>is</span> <span m=''1338680''>a</span>
  <span m=''1338800''>very,</span> <span m=''1339200''>very</span> <span m=''1339600''>excellent</span>
  <span m=''1340010''>compiler</span> <span m=''1340430''>effort.</span> <span m=''1344460''>Let''s</span>
  <span m=''1344730''>take</span> <span m=''1344880''>a</span> <span m=''1344930''>break.</span>
  </p><p><span m=''1396650''>We''ve</span> <span m=''1396850''>looked</span> <span
  m=''1397090''>at</span> <span m=''1397810''>the</span> <span m=''1397980''>primitive</span>
  <span m=''1398330''>queries</span> <span m=''1399260''>and</span> <span m=''1399410''>the</span>
  <span m=''1399560''>ways</span> <span m=''1399880''>that</span> <span m=''1400410''>streams</span>
  <span m=''1400920''>are</span> <span m=''1400980''>used</span> <span m=''1401250''>to</span>
  <span m=''1401330''>implement</span> <span m=''1401800''>the</span> <span m=''1402490''>means</span>
  <span m=''1402730''>of</span> <span m=''1402810''>combination:</span> <span m=''1403950''>AND</span>
  <span m=''1404300''>and</span> <span m=''1404450''>OR</span> <span m=''1405100''>and</span>
  <span m=''1405320''>NOT.</span> <span m=''1406950''>Now,</span> <span m=''1407100''>let</span>
  <span m=''1407210''>go on</span> <span m=''1407370''>to the</span> <span m=''1407520''>means</span>
  <span m=''1407680''>of</span> <span m=''1407850''>abstraction.</span> <span m=''1409580''>Remember,</span>
  <span m=''1410200''>the</span> <span m=''1410320''>means</span> <span m=''1410530''>of</span>
  <span m=''1410650''>abstraction</span> <span m=''1411050''>in</span> <span m=''1411160''>this</span>
  <span m=''1411280''>language</span> <span m=''1412010''>are</span> <span m=''1412280''>rules.</span>
  <span m=''1415150''>So</span> <span m=''1415980''>z</span> <span m=''1416120''>is</span>
  <span m=''1416260''>a</span> <span m=''1416320''>boss in</span> <span m=''1416760''>division</span>
  <span m=''1417350''>d</span> <span m=''1419240''>if</span> <span m=''1419570''>there''s</span>
  <span m=''1419870''>some</span> <span m=''1420140''>x</span> <span m=''1422180''>who</span>
  <span m=''1422360''>has</span> <span m=''1422530''>a</span> <span m=''1422580''>job</span>
  <span m=''1422890''>in</span> <span m=''1423000''>division</span> <span m=''1423380''>d</span>
  <span m=''1425710''>and</span> <span m=''1425940''>z</span> <span m=''1426130''>is</span>
  <span m=''1426260''>the</span> <span m=''1426330''>supervisor</span> <span m=''1427030''>of</span>
  <span m=''1427120''>x.</span> <span m=''1428900''>That''s</span> <span m=''1429270''>what</span>
  <span m=''1429380''>it</span> <span m=''1429450''>means</span> <span m=''1429600''>for</span>
  <span m=''1429690''>someone</span> <span m=''1429940''>to</span> <span m=''1430040''>be
  a</span> <span m=''1430200''>boss.</span> </p><p><span m=''1432260''>And</span>
  <span m=''1432740''>in</span> <span m=''1432840''>effect,</span> <span m=''1433095''>if</span>
  <span m=''1433350''>you</span> <span m=''1433440''>think</span> <span m=''1433590''>about</span>
  <span m=''1433790''>what</span> <span m=''1433910''>we''re</span> <span m=''1434020''>doing</span>
  <span m=''1434630''>with</span> <span m=''1434780''>relation</span> <span m=''1435250''>to</span>
  <span m=''1435370''>this,</span> <span m=''1436760''>there''s</span> <span m=''1437160''>the</span>
  <span m=''1437230''>query</span> <span m=''1437550''>we</span> <span m=''1437760''>wrote--</span>
  <span m=''1437940''>the</span> <span m=''1438020''>job</span> <span m=''1438300''>of</span>
  <span m=''1438450''>x</span> <span m=''1438660''>is</span> <span m=''1438760''>in
  d</span> <span m=''1439580''>and</span> <span m=''1439670''>the</span> <span m=''1439770''>supervisor</span>
  <span m=''1440090''>of</span> <span m=''1440410''>x</span> <span m=''1440660''>is</span>
  <span m=''1441360''>z--</span> <span m=''1442150''>what</span> <span m=''1442300''>we</span>
  <span m=''1442410''>in</span> <span m=''1442470''>effect</span> <span m=''1442810''>want</span>
  <span m=''1442910''>to</span> <span m=''1443020''>do</span> <span m=''1443210''>is</span>
  <span m=''1443320''>take</span> <span m=''1443530''>this</span> <span m=''1443670''>whole</span>
  <span m=''1443890''>mess</span> <span m=''1445130''>and</span> <span m=''1445330''>draw</span>
  <span m=''1445600''>a</span> <span m=''1445710''>box</span> <span m=''1446090''>around</span>
  <span m=''1446400''>it</span> <span m=''1459170''>and</span> <span m=''1459360''>say</span>
  <span m=''1460980''>this</span> <span m=''1461290''>whole</span> <span m=''1461620''>thing</span>
  <span m=''1463620''>inside</span> <span m=''1464000''>the</span> <span m=''1464070''>box</span>
  <span m=''1465170''>is</span> <span m=''1466560''>boss</span> <span m=''1470270''>of</span>
  <span m=''1470470''>z</span> <span m=''1471500''>in</span> <span m=''1471640''>division</span>
  <span m=''1472090''>d.</span> <span m=''1473900''>That''s</span> <span m=''1474080''>in</span>
  <span m=''1474170''>effect</span> <span m=''1474540''>what</span> <span m=''1474650''>we</span>
  <span m=''1474750''>want</span> <span m=''1474880''>to</span> <span m=''1475040''>do.</span>
  </p><p><span m=''1478720''>So,</span> <span m=''1479100''>for</span> <span m=''1479230''>instance,</span>
  <span m=''1483240''>if</span> <span m=''1483410''>we''ve</span> <span m=''1483580''>done</span>
  <span m=''1483820''>that,</span> <span m=''1484610''>and</span> <span m=''1484980''>we</span>
  <span m=''1485350''>want</span> <span m=''1485580''>to</span> <span m=''1485690''>check</span>
  <span m=''1486340''>whether</span> <span m=''1486730''>or</span> <span m=''1486810''>not</span>
  <span m=''1487150''>it''s</span> <span m=''1487360''>true</span> <span m=''1487940''>that</span>
  <span m=''1488200''>Ben</span> <span m=''1488450''>Bitdiddle</span> <span m=''1488840''>is</span>
  <span m=''1488950''>a</span> <span m=''1489020''>boss</span> <span m=''1489410''>in</span>
  <span m=''1489490''>the</span> <span m=''1489570''>computer</span> <span m=''1489980''>division,</span>
  <span m=''1490900''>so if</span> <span m=''1491350''>I</span> <span m=''1491420''>want</span>
  <span m=''1491510''>to</span> <span m=''1491590''>say</span> <span m=''1491730''>boss</span>
  <span m=''1500420''>of</span> <span m=''1500520''>Ben</span> <span m=''1500730''>Bitdiddle</span>
  <span m=''1501710''>in</span> <span m=''1501820''>the</span> <span m=''1501920''>computer</span>
  <span m=''1502320''>division,</span> <span m=''1504930''>imagine</span> <span m=''1505250''>typing</span>
  <span m=''1505600''>that</span> <span m=''1505850''>in</span> <span m=''1505950''>as</span>
  <span m=''1506070''>query</span> <span m=''1506440''>to</span> <span m=''1506530''>the</span>
  <span m=''1506630''>system,</span> <span m=''1507170''>in</span> <span m=''1507390''>effect</span>
  <span m=''1508170''>what</span> <span m=''1508360''>we</span> <span m=''1508470''>want</span>
  <span m=''1508710''>to</span> <span m=''1508820''>do</span> <span m=''1510730''>is</span>
  <span m=''1510860''>set</span> <span m=''1511140''>up</span> <span m=''1511860''>a</span>
  <span m=''1512040''>dictionary</span> <span m=''1512600''>here,</span> <span m=''1515610''>which</span>
  <span m=''1516010''>has</span> <span m=''1516620''>z</span> <span m=''1522700''>to
  Ben</span> <span m=''1522940''>Bitdiddle</span> <span m=''1528920''>and</span> <span
  m=''1530070''>d</span> <span m=''1532380''>to</span> <span m=''1532720''>computer.</span>
  <span m=''1537340''>Where  did</span> <span m=''1537510''>that</span> <span m=''1537730''>dictionary</span>
  <span m=''1538140''>come</span> <span m=''1538340''>from?</span> <span m=''1538720''>Let''s</span>
  <span m=''1538910''>look</span> <span m=''1539030''>at</span> <span m=''1539140''>the</span>
  <span m=''1539210''>slide</span> <span m=''1539960''>for</span> <span m=''1540060''>one</span>
  <span m=''1540210''>second.</span> </p><p><span m=''1540710''>That</span> <span
  m=''1540960''>dictionary</span> <span m=''1541380''>came</span> <span m=''1541710''>from</span>
  <span m=''1542520''>matching</span> <span m=''1543070''>the</span> <span m=''1543160''>query</span>
  <span m=''1544320''>that</span> <span m=''1544510''>said</span> <span m=''1544750''>boss</span>
  <span m=''1545030''>of</span> <span m=''1545190''>Ben</span> <span m=''1545360''>Bitdiddle</span>
  <span m=''1545740''>and</span> <span m=''1545830''>computer</span> <span m=''1546510''>onto</span>
  <span m=''1546880''>the</span> <span m=''1546990''>conclusion</span> <span m=''1547720''>of</span>
  <span m=''1547830''>the</span> <span m=''1547940''>rule:</span> <span m=''1548390''>boss</span>
  <span m=''1548660''>of</span> <span m=''1549160''>z and d.</span> <span m=''1551650''>So</span>
  <span m=''1551960''>we</span> <span m=''1552100''>match</span> <span m=''1552400''>the</span>
  <span m=''1552480''>query</span> <span m=''1552810''>to</span> <span m=''1552910''>the</span>
  <span m=''1553010''>conclusion</span> <span m=''1553520''>of</span> <span m=''1553610''>the</span>
  <span m=''1553700''>rule.</span> <span m=''1554190''>That</span> <span m=''1554510''>gives</span>
  <span m=''1554710''>us</span> <span m=''1554860''>a</span> <span m=''1554910''>dictionary,</span>
  <span m=''1559040''>and</span> <span m=''1559230''>that''s</span> <span m=''1559500''>the</span>
  <span m=''1559610''>thing</span> <span m=''1559940''>that</span> <span m=''1560240''>we</span>
  <span m=''1560330''>would</span> <span m=''1560460''>now</span> <span m=''1560650''>like</span>
  <span m=''1560830''>to</span> <span m=''1560940''>put</span> <span m=''1561120''>into</span>
  <span m=''1561340''>this</span> <span m=''1561500''>whole</span> <span m=''1561970''>big</span>
  <span m=''1562200''>thing</span> <span m=''1562940''>and</span> <span m=''1563180''>process</span>
  <span m=''1563740''>and</span> <span m=''1563860''>see</span> <span m=''1563990''>if</span>
  <span m=''1564120''>anything</span> <span m=''1564480''>comes</span> <span m=''1564720''>out</span>
  <span m=''1564910''>the</span> <span m=''1565040''>other</span> <span m=''1565170''>side.</span>
  <span m=''1566670''>If</span> <span m=''1566820''>anything</span> <span m=''1567160''>comes</span>
  <span m=''1567420''>out,</span> <span m=''1569070''>it''ll</span> <span m=''1569380''>be</span>
  <span m=''1569490''>true.</span> <span m=''1571330''>That''s</span> <span m=''1571550''>the</span>
  <span m=''1571630''>basic</span> <span m=''1572050''>idea.</span> </p><p><span m=''1572370''>So</span>
  <span m=''1572550''>in</span> <span m=''1572660''>general,</span> <span m=''1573990''>the</span>
  <span m=''1574200''>way</span> <span m=''1574360''>we</span> <span m=''1574510''>implement</span>
  <span m=''1574930''>a</span> <span m=''1575000''>rule</span> <span m=''1575920''>is</span>
  <span m=''1576080''>we</span> <span m=''1576260''>match</span> <span m=''1577020''>the</span>
  <span m=''1577400''>conclusion</span> <span m=''1578150''>of</span> <span m=''1578300''>the</span>
  <span m=''1578450''>rule</span> <span m=''1580870''>against</span> <span m=''1581160''>something</span>
  <span m=''1581550''>we</span> <span m=''1581670''>might</span> <span m=''1581860''>want</span>
  <span m=''1581950''>to</span> <span m=''1582170''>check</span> <span m=''1582430''>it''s</span>
  <span m=''1582580''>true.</span> <span m=''1583580''>That</span> <span m=''1583880''>match</span>
  <span m=''1584220''>gives</span> <span m=''1584410''>us</span> <span m=''1584530''>a</span>
  <span m=''1584590''>dictionary,</span> <span m=''1585330''>and</span> <span m=''1585670''>with</span>
  <span m=''1585950''>respect</span> <span m=''1586790''>to</span> <span m=''1586990''>that</span>
  <span m=''1587620''>dictionary,</span> <span m=''1592700''>we</span> <span m=''1592830''>process</span>
  <span m=''1593640''>the</span> <span m=''1593790''>body</span> <span m=''1594170''>of</span>
  <span m=''1594230''>the</span> <span m=''1594330''>rule.</span> </p><p><span m=''1596470''>Well,</span>
  <span m=''1596620''>that''s</span> <span m=''1596800''>really</span> <span m=''1597020''>all</span>
  <span m=''1597170''>there</span> <span m=''1597370''>is,</span> <span m=''1598690''>except</span>
  <span m=''1599070''>for</span> <span m=''1600110''>two</span> <span m=''1600550''>technical</span>
  <span m=''1600990''>points.</span> <span m=''1603070''>The</span> <span m=''1603230''>first</span>
  <span m=''1603400''>technical</span> <span m=''1603770''>point</span> <span m=''1604060''>is</span>
  <span m=''1604140''>that</span> <span m=''1605820''>I</span> <span m=''1605930''>might</span>
  <span m=''1606250''>have</span> <span m=''1606370''>said</span> <span m=''1606580''>something</span>
  <span m=''1606990''>else.</span> <span m=''1607510''>I</span> <span m=''1607640''>might</span>
  <span m=''1607860''>have</span> <span m=''1607940''>said</span> <span m=''1610640''>who''s</span>
  <span m=''1610820''>the</span> <span m=''1610900''>boss</span> <span m=''1611270''>in</span>
  <span m=''1611330''>the</span> <span m=''1611410''>computer</span> <span m=''1611780''>division?</span>
  <span m=''1612490''>So</span> <span m=''1612750''>I</span> <span m=''1612840''>might</span>
  <span m=''1613080''>say</span> <span m=''1613190''>boss</span> <span m=''1613600''>of</span>
  <span m=''1613850''>who</span> <span m=''1615260''>in</span> <span m=''1615420''>computer</span>
  <span m=''1615820''>division.</span> <span m=''1620329''>And</span> <span m=''1620780''>if</span>
  <span m=''1621030''>I</span> <span m=''1621120''>did</span> <span m=''1621350''>that,</span>
  <span m=''1622630''>what</span> <span m=''1622790''>I</span> <span m=''1622900''>would</span>
  <span m=''1623020''>really</span> <span m=''1623290''>like</span> <span m=''1623500''>to</span>
  <span m=''1623620''>do</span> <span m=''1623840''>in</span> <span m=''1623920''>effect</span>
  <span m=''1624280''>is</span> <span m=''1625210''>start</span> <span m=''1625570''>up</span>
  <span m=''1625700''>this</span> <span m=''1625910''>dictionary</span> <span m=''1628380''>with</span>
  <span m=''1628610''>a</span> <span m=''1628670''>match</span> <span m=''1629090''>that</span>
  <span m=''1629280''>sort</span> <span m=''1629470''>of</span> <span m=''1629540''>says,</span>
  <span m=''1629980''>well,</span> <span m=''1630210''>d</span> <span m=''1630450''>is</span>
  <span m=''1630590''>computer</span> <span m=''1634390''>and</span> <span m=''1634640''>z</span>
  <span m=''1635020''>is</span> <span m=''1637370''>whatever</span> <span m=''1637870''>who</span>
  <span m=''1638170''>is.</span> <span m=''1641700''>And</span> <span m=''1641860''>our</span>
  <span m=''1641950''>matcher</span> <span m=''1642320''>won''t</span> <span m=''1642530''>quite</span>
  <span m=''1642880''>do</span> <span m=''1643040''>that.</span> <span m=''1643220''>That''s</span>
  <span m=''1643430''>not</span> <span m=''1643740''>quite</span> <span m=''1644700''>matching</span>
  <span m=''1645630''>a</span> <span m=''1645760''>pattern</span> <span m=''1646150''>against</span>
  <span m=''1646550''>data.</span> <span m=''1648580''>It''s</span> <span m=''1648760''>matching</span>
  <span m=''1649150''>two</span> <span m=''1649310''>patterns</span> <span m=''1649940''>and</span>
  <span m=''1650090''>saying</span> <span m=''1650350''>are</span> <span m=''1650500''>they</span>
  <span m=''1650660''>consistent</span> <span m=''1651210''>or</span> <span m=''1651310''>not</span>
  <span m=''1651640''>or</span> <span m=''1651920''>what</span> <span m=''1652210''>ways</span>
  <span m=''1652430''>make</span> <span m=''1652620''>them</span> <span m=''1652760''>consistent.</span>
  </p><p><span m=''1653480''>In</span> <span m=''1653600''>other</span> <span m=''1653750''>words,</span>
  <span m=''1653910''>what</span> <span m=''1654030''>we</span> <span m=''1654120''>need</span>
  <span m=''1655000''>is</span> <span m=''1655170''>not</span> <span m=''1655340''>quite</span>
  <span m=''1655540''>a</span> <span m=''1655580''>pattern</span> <span m=''1655940''>matcher,</span>
  <span m=''1656420''>but</span> <span m=''1657510''>something</span> <span m=''1657850''>a</span>
  <span m=''1657900''>little</span> <span m=''1658120''>bit</span> <span m=''1658290''>more</span>
  <span m=''1658450''>general</span> <span m=''1659220''>called</span> <span m=''1659420''>a</span>
  <span m=''1659470''>unifier.</span> <span m=''1664420''>And</span> <span m=''1664670''>a</span>
  <span m=''1664780''>unifier</span> <span m=''1665460''>is</span> <span m=''1665640''>a</span>
  <span m=''1665690''>slight</span> <span m=''1666360''>generalization</span> <span
  m=''1667190''>of a</span> <span m=''1667330''>pattern</span> <span m=''1667670''>matcher.</span>
  <span m=''1669530''>What</span> <span m=''1669660''>a</span> <span m=''1669780''>unifier</span>
  <span m=''1670260''>does</span> <span m=''1670650''>is</span> <span m=''1670820''>take</span>
  <span m=''1671160''>two</span> <span m=''1671600''>patterns</span> <span m=''1673240''>and</span>
  <span m=''1673490''>say</span> <span m=''1675050''>what''s</span> <span m=''1675390''>the</span>
  <span m=''1675480''>most</span> <span m=''1675860''>general</span> <span m=''1676230''>thing</span>
  <span m=''1676500''>you</span> <span m=''1676630''>can</span> <span m=''1676770''>substitute</span>
  <span m=''1678210''>for</span> <span m=''1678360''>the</span> <span m=''1678470''>variables</span>
  <span m=''1679020''>in</span> <span m=''1679100''>those</span> <span m=''1679280''>two</span>
  <span m=''1679440''>patterns</span> <span m=''1682690''>to</span> <span m=''1682840''>make</span>
  <span m=''1683040''>them</span> <span m=''1683160''>satisfy</span> <span m=''1683660''>the</span>
  <span m=''1683760''>pattern</span> <span m=''1684060''>simultaneously?</span> <span
  m=''1685680''>Let me give you an</span> <span m=''1686010''>example.</span> </p><p><span
  m=''1688900''>If</span> <span m=''1689050''>I</span> <span m=''1689150''>have</span>
  <span m=''1689250''>the</span> <span m=''1689330''>pattern</span> <span m=''1692120''>two-element</span>
  <span m=''1692750''>list,</span> <span m=''1693330''>which</span> <span m=''1693510''>is</span>
  <span m=''1693650''>x</span> <span m=''1693940''>and</span> <span m=''1694150''>x,</span>
  <span m=''1695710''>so</span> <span m=''1696200''>I</span> <span m=''1696240''>have</span>
  <span m=''1696320''>a</span> <span m=''1696400''>two-element</span> <span m=''1696910''>list</span>
  <span m=''1697360''>where</span> <span m=''1697520''>both</span> <span m=''1697780''>elements</span>
  <span m=''1698160''>are</span> <span m=''1698220''>the</span> <span m=''1698320''>same</span>
  <span m=''1698680''>and</span> <span m=''1698760''>otherwise</span> <span m=''1699120''>I</span>
  <span m=''1699220''>don''t</span> <span m=''1699330''>care</span> <span m=''1699530''>what</span>
  <span m=''1699680''>they</span> <span m=''1699820''>are,</span> <span m=''1700440''>and</span>
  <span m=''1700560''>I</span> <span m=''1700670''>unify</span> <span m=''1701250''>that</span>
  <span m=''1701860''>against</span> <span m=''1702260''>the</span> <span m=''1702300''>pattern</span>
  <span m=''1702950''>that</span> <span m=''1703180''>says</span> <span m=''1703380''>there''s</span>
  <span m=''1703470''>a</span> <span m=''1703790''>two-element</span> <span m=''1704330''>list,</span>
  <span m=''1704670''>and</span> <span m=''1704730''>the</span> <span m=''1704800''>first</span>
  <span m=''1705130''>one</span> <span m=''1705730''>is</span> <span m=''1705950''>a</span>
  <span m=''1706460''>and</span> <span m=''1706630''>something</span> <span m=''1707010''>in</span>
  <span m=''1707120''>c</span> <span m=''1708050''>and</span> <span m=''1708220''>the</span>
  <span m=''1708410''>second</span> <span m=''1708610''>one</span> <span m=''1708810''>is</span>
  <span m=''1708950''>a</span> <span m=''1709160''>and</span> <span m=''1709340''>b</span>
  <span m=''1709550''>and</span> <span m=''1709760''>z,</span> <span m=''1712940''>then</span>
  <span m=''1713350''>what</span> <span m=''1713600''>the</span> <span m=''1713830''>unifier</span>
  <span m=''1714300''>should</span> <span m=''1714440''>tell</span> <span m=''1714670''>me</span>
  <span m=''1714840''>is,</span> <span m=''1714940''>oh</span> <span m=''1715060''>yeah,</span>
  <span m=''1715270''>in</span> <span m=''1715440''>that</span> <span m=''1715640''>dictionary,</span>
  <span m=''1716480''>x</span> <span m=''1716960''>has to</span> <span m=''1717050''>be</span>
  <span m=''1717230''>a,</span> <span m=''1717360''>b,</span> <span m=''1717540''>c,</span>
  <span m=''1719420''>and</span> <span m=''1719640''>y</span> <span m=''1719870''>has
  to be</span> <span m=''1720340''>d</span> <span m=''1720500''>and</span> <span m=''1720870''>z</span>
  <span m=''1721080''>has</span> <span m=''1721310''>to</span> <span m=''1721400''>be</span>
  <span m=''1721520''>c.</span> <span m=''1723440''>Those</span> <span m=''1723660''>are</span>
  <span m=''1723700''>the</span> <span m=''1723790''>restrictions</span> <span m=''1724390''>I''d</span>
  <span m=''1724480''>have</span> <span m=''1724650''>to</span> <span m=''1724760''>put</span>
  <span m=''1724930''>on</span> <span m=''1725100''>the</span> <span m=''1725180''>values</span>
  <span m=''1725560''>of</span> <span m=''1725660''>x,</span> <span m=''1725860''>y,</span>
  <span m=''1726070''>and</span> <span m=''1726160''>z</span> <span m=''1726340''>to</span>
  <span m=''1726460''>make</span> <span m=''1726690''>these</span> <span m=''1726890''>two</span>
  <span m=''1727000''>unify,</span> <span m=''1728220''>or</span> <span m=''1728340''>in</span>
  <span m=''1728410''>other</span> <span m=''1728540''>words,</span> <span m=''1728770''>to</span>
  <span m=''1728880''>make</span> <span m=''1729880''>this</span> <span m=''1730190''>match</span>
  <span m=''1730460''>x</span> <span m=''1731210''>and</span> <span m=''1731390''>make</span>
  <span m=''1731620''>this</span> <span m=''1732750''>match</span> <span m=''1732950''>x.</span>
  <span m=''1735420''>The</span> <span m=''1735520''>unifier</span> <span m=''1735960''>should</span>
  <span m=''1736100''>be</span> <span m=''1736250''>able</span> <span m=''1736400''>to</span>
  <span m=''1736730''>deduce</span> <span m=''1737290''>that.</span> </p><p><span
  m=''1738540''>But the</span> <span m=''1738700''>unifier</span> <span m=''1739090''>may--</span>
  <span m=''1739730''>there</span> <span m=''1739930''>are</span> <span m=''1740040''>more</span>
  <span m=''1740200''>complicated</span> <span m=''1740860''>things.</span> <span
  m=''1741080''>I</span> <span m=''1741150''>might</span> <span m=''1741330''>have</span>
  <span m=''1741410''>said</span> <span m=''1741590''>something</span> <span m=''1741870''>a</span>
  <span m=''1741920''>little</span> <span m=''1742140''>bit</span> <span m=''1742280''>more</span>
  <span m=''1742430''>complicated.</span> <span m=''1743810''>I might have</span>
  <span m=''1743940''>said</span> <span m=''1744350''>there''s</span> <span m=''1744570''>a</span>
  <span m=''1744630''>list</span> <span m=''1744890''>with</span> <span m=''1745020''>two</span>
  <span m=''1745210''>elements,</span> <span m=''1747030''>and</span> <span m=''1747170''>they''re</span>
  <span m=''1747270''>both</span> <span m=''1747550''>the</span> <span m=''1747710''>same,</span>
  <span m=''1748910''>and</span> <span m=''1749040''>they</span> <span m=''1749170''>should</span>
  <span m=''1749350''>unify</span> <span m=''1749830''>against</span> <span m=''1750080''>something</span>
  <span m=''1750380''>of</span> <span m=''1750550''>this</span> <span m=''1750720''>form.</span>
  <span m=''1752650''>And the</span> <span m=''1752890''>unifier</span> <span m=''1753670''>should</span>
  <span m=''1753880''>be</span> <span m=''1754050''>able</span> <span m=''1754220''>to</span>
  <span m=''1754360''>deduce</span> <span m=''1754830''>from</span> <span m=''1755020''>that.</span>
  <span m=''1756890''>Like</span> <span m=''1757230''>that</span> <span m=''1757510''>y</span>
  <span m=''1757990''>would</span> <span m=''1758130''>have</span> <span m=''1758320''>to</span>
  <span m=''1758420''>be</span> <span m=''1758560''>b.</span> <span m=''1758810''>y</span>
  <span m=''1759000''>would</span> <span m=''1759110''>have</span> <span m=''1759290''>to</span>
  <span m=''1759410''>be b.</span> <span m=''1759570''>Because</span> <span m=''1759910''>these</span>
  <span m=''1761330''>two</span> <span m=''1761490''>are</span> <span m=''1761550''>the</span>
  <span m=''1761660''>same,</span> <span m=''1762220''>so</span> <span m=''1762430''>y''s</span>
  <span m=''1762730''>got</span> <span m=''1762840''>to</span> <span m=''1762940''>be</span>
  <span m=''1763090''>b.</span> <span m=''1764340''>And</span> <span m=''1765220''>v</span>
  <span m=''1765470''>here</span> <span m=''1766660''>would</span> <span m=''1766810''>have</span>
  <span m=''1766980''>to</span> <span m=''1767060''>be</span> <span m=''1767260''>a.</span>
  <span m=''1768940''>And</span> <span m=''1769820''>z</span> <span m=''1770090''>and</span>
  <span m=''1770190''>w</span> <span m=''1770490''>can</span> <span m=''1770620''>be</span>
  <span m=''1770760''>anything,</span> <span m=''1771090''>but</span> <span m=''1771200''>they</span>
  <span m=''1771310''>have</span> <span m=''1771450''>to</span> <span m=''1771520''>be</span>
  <span m=''1771630''>the</span> <span m=''1771700''>same</span> <span m=''1771990''>thing.</span>
  <span m=''1775710''>And</span> <span m=''1777660''>x</span> <span m=''1778260''>would</span>
  <span m=''1778380''>have</span> <span m=''1778540''>to</span> <span m=''1778690''>be</span>
  <span m=''1778890''>b,</span> <span m=''1779210''>followed</span> <span m=''1779540''>by</span>
  <span m=''1779730''>a,</span> <span m=''1780170''>followed</span> <span m=''1780560''>by</span>
  <span m=''1780680''>whatever</span> <span m=''1781020''>w</span> <span m=''1781450''>is</span>
  <span m=''1782930''>or</span> <span m=''1783030''>whatever</span> <span m=''1783160''>z</span>
  <span m=''1783650''>is,</span> <span m=''1783860''>which</span> <span m=''1784020''>is</span>
  <span m=''1784120''>the</span> <span m=''1784190''>same.</span> <span m=''1784680''>So</span>
  <span m=''1784830''>you</span> <span m=''1784910''>see,</span> <span m=''1785350''>the</span>
  <span m=''1785430''>unifier</span> <span m=''1786850''>somehow</span> <span m=''1787200''>has</span>
  <span m=''1787420''>to</span> <span m=''1787550''>deduce</span> <span m=''1788040''>things</span>
  <span m=''1788260''>to</span> <span m=''1788350''>unify</span> <span m=''1788720''>these</span>
  <span m=''1788930''>patterns.</span> <span m=''1790880''>So</span> <span m=''1791030''>you</span>
  <span m=''1791160''>might</span> <span m=''1791350''>think</span> <span m=''1791490''>there''s</span>
  <span m=''1791640''>some</span> <span m=''1791770''>kind</span> <span m=''1791910''>of</span>
  <span m=''1792050''>magic</span> <span m=''1792420''>deduction</span> <span m=''1792880''>going</span>
  <span m=''1793170''>on,</span> <span m=''1794390''>but</span> <span m=''1794650''>there''s</span>
  <span m=''1794860''>not.</span> </p><p><span m=''1795850''>A</span> <span m=''1795980''>unifier</span>
  <span m=''1796820''>is</span> <span m=''1797020''>basically</span> <span m=''1797520''>a</span>
  <span m=''1797580''>very</span> <span m=''1797920''>simple</span> <span m=''1798240''>modification</span>
  <span m=''1798960''>of</span> <span m=''1799050''>a</span> <span m=''1799100''>pattern</span>
  <span m=''1799440''>matcher.</span> <span m=''1800150''>And</span> <span m=''1800240''>if</span>
  <span m=''1800330''>you</span> <span m=''1800450''>look</span> <span m=''1800610''>in</span>
  <span m=''1800700''>the</span> <span m=''1800780''>book,</span> <span m=''1801000''>you''ll</span>
  <span m=''1801110''>see</span> <span m=''1801280''>something</span> <span m=''1801600''>like</span>
  <span m=''1802530''>three</span> <span m=''1802800''>or</span> <span m=''1802860''>four</span>
  <span m=''1803120''>lines</span> <span m=''1803480''>of</span> <span m=''1803590''>code</span>
  <span m=''1804180''>added</span> <span m=''1804530''>to</span> <span m=''1804610''>the</span>
  <span m=''1804690''>pattern</span> <span m=''1805020''>matcher</span> <span m=''1805350''>you</span>
  <span m=''1805460''>just</span> <span m=''1805740''>saw</span> <span m=''1806170''>to</span>
  <span m=''1806690''>handle</span> <span m=''1807050''>the</span> <span m=''1807270''>symmetric</span>
  <span m=''1807730''>case.</span> <span m=''1808280''>Remember,</span> <span m=''1808570''>the</span>
  <span m=''1808670''>pattern</span> <span m=''1809000''>matcher</span> <span m=''1809630''>has</span>
  <span m=''1809840''>a</span> <span m=''1809900''>place</span> <span m=''1810220''>where</span>
  <span m=''1810390''>it</span> <span m=''1810500''>says</span> <span m=''1811710''>is</span>
  <span m=''1811920''>this</span> <span m=''1812130''>variable</span> <span m=''1812610''>matching</span>
  <span m=''1813650''>a</span> <span m=''1813790''>constant.</span> <span m=''1814980''>And</span>
  <span m=''1815170''>if</span> <span m=''1815230''>so,</span> <span m=''1815450''>it</span>
  <span m=''1815530''>checks</span> <span m=''1815790''>in</span> <span m=''1815840''>the</span>
  <span m=''1815920''>dictionary.</span> <span m=''1816420''>There''s</span> <span
  m=''1816590''>only</span> <span m=''1816850''>one</span> <span m=''1817080''>other</span>
  <span m=''1817260''>clause</span> <span m=''1817550''>in</span> <span m=''1817620''>the</span>
  <span m=''1817690''>unifier,</span> <span m=''1818590''>which</span> <span m=''1818770''>says
  is</span> <span m=''1818970''>this</span> <span m=''1819270''>variable</span> <span
  m=''1819700''>matching</span> <span m=''1820100''>a</span> <span m=''1820150''>variable,</span>
  <span m=''1822060''>in</span> <span m=''1822190''>which</span> <span m=''1822350''>case</span>
  <span m=''1822540''>you</span> <span m=''1822620''>go</span> <span m=''1822760''>look</span>
  <span m=''1822920''>in</span> <span m=''1822990''>the</span> <span m=''1823070''>dictionary</span>
  <span m=''1823570''>and</span> <span m=''1823660''>see</span> <span m=''1823830''>if</span>
  <span m=''1823900''>that''s</span> <span m=''1824130''>consistent</span> <span m=''1824630''>with</span>
  <span m=''1824740''>what''s</span> <span m=''1824970''>in</span> <span m=''1825050''>the</span>
  <span m=''1825120''>dictionary.</span> </p><p><span m=''1827030''>So</span> <span
  m=''1827310''>all</span> <span m=''1827540''>the,</span> <span m=''1828130''>quote,</span>
  <span m=''1828650''>deduction</span> <span m=''1829800''>that''s</span> <span m=''1830330''>in</span>
  <span m=''1830420''>this</span> <span m=''1830590''>language,</span> <span m=''1831320''>if</span>
  <span m=''1831450''>you</span> <span m=''1831580''>sort</span> <span m=''1831720''>of</span>
  <span m=''1831860''>look</span> <span m=''1832070''>at</span> <span m=''1832270''>it,</span>
  <span m=''1832820''>sort</span> <span m=''1832960''>of</span> <span m=''1833100''>sits</span>
  <span m=''1833350''>in</span> <span m=''1833440''>the</span> <span m=''1833530''>rule</span>
  <span m=''1833780''>applications,</span> <span m=''1835090''>which,</span> <span
  m=''1835800''>if</span> <span m=''1835940''>you</span> <span m=''1836080''>look</span>
  <span m=''1836210''>at</span> <span m=''1836340''>that,</span> <span m=''1836770''>sits</span>
  <span m=''1837060''>in</span> <span m=''1837140''>the</span> <span m=''1837220''>unifier,</span>
  <span m=''1838480''>which,</span> <span m=''1838700''>if</span> <span m=''1838800''>you</span>
  <span m=''1838940''>look</span> <span m=''1839080''>at</span> <span m=''1839210''>that</span>
  <span m=''1839420''>under</span> <span m=''1839630''>a</span> <span m=''1839670''>microscope,</span>
  <span m=''1840550''>sits</span> <span m=''1842500''>essentially</span> <span m=''1843090''>in</span>
  <span m=''1843220''>the</span> <span m=''1843320''>pattern</span> <span m=''1843670''>matcher.</span>
  <span m=''1845260''>There''s</span> <span m=''1845470''>no</span> <span m=''1845660''>magic</span>
  <span m=''1846000''>at</span> <span m=''1846130''>all</span> <span m=''1846260''>going</span>
  <span m=''1846540''>on</span> <span m=''1846720''>in</span> <span m=''1846810''>there.</span>
  <span m=''1847410''>And</span> <span m=''1847650''>the,</span> <span m=''1848460''>quote,</span>
  <span m=''1848840''>deduction</span> <span m=''1849510''>that</span> <span m=''1849670''>you</span>
  <span m=''1849840''>see</span> <span m=''1850990''>is</span> <span m=''1851200''>just</span>
  <span m=''1851430''>the</span> <span m=''1851510''>fact</span> <span m=''1851720''>that</span>
  <span m=''1851930''>there''s</span> <span m=''1852130''>this</span> <span m=''1852350''>recursion,</span>
  <span m=''1852950''>which</span> <span m=''1853120''>is</span> <span m=''1853220''>unwinding</span>
  <span m=''1853850''>the</span> <span m=''1854610''>matches</span> <span m=''1855090''>bit</span>
  <span m=''1855280''>by</span> <span m=''1855440''>bit.</span> <span m=''1856030''>So</span>
  <span m=''1856210''>it</span> <span m=''1856290''>looks</span> <span m=''1856520''>like</span>
  <span m=''1856700''>this</span> <span m=''1856860''>thing</span> <span m=''1857020''>is</span>
  <span m=''1857130''>being</span> <span m=''1857360''>very</span> <span m=''1857600''>clever,</span>
  <span m=''1858440''>but</span> <span m=''1858570''>in</span> <span m=''1858670''>fact,</span>
  <span m=''1858890''>it''s</span> <span m=''1859030''>not</span> <span m=''1859260''>being</span>
  <span m=''1859470''>very</span> <span m=''1859700''>clever</span> <span m=''1860050''>at</span>
  <span m=''1860110''>all.</span> </p><p><span m=''1862140''>There</span> <span m=''1862310''>are</span>
  <span m=''1862350''>cases</span> <span m=''1862770''>where a</span> <span m=''1862960''>unifier</span>
  <span m=''1863420''>might</span> <span m=''1863680''>have</span> <span m=''1863820''>to</span>
  <span m=''1863960''>be</span> <span m=''1864070''>clever.</span> <span m=''1864880''>Let</span>
  <span m=''1864970''>me</span> <span m=''1865060''>show</span> <span m=''1865200''>you</span>
  <span m=''1865370''>one</span> <span m=''1865550''>more.</span> <span m=''1871070''>Suppose
  I want to</span> <span m=''1871520''>unify</span> <span m=''1872160''>a</span> <span
  m=''1872310''>list</span> <span m=''1872580''>of</span> <span m=''1872680''>two</span>
  <span m=''1872860''>elements,</span> <span m=''1873550''>x</span> <span m=''1874150''>and</span>
  <span m=''1874340''>x,</span> <span m=''1877330''>with</span> <span m=''1877530''>a</span>
  <span m=''1877620''>thing</span> <span m=''1877890''>that</span> <span m=''1878060''>says</span>
  <span m=''1879450''>it''s</span> <span m=''1879680''>y</span> <span m=''1880610''>followed</span>
  <span m=''1881100''>by</span> <span m=''1881310''>a</span> <span m=''1881510''>dot</span>
  <span m=''1881810''>y.</span> <span m=''1884370''>Now,</span> <span m=''1884500''>if</span>
  <span m=''1884580''>you</span> <span m=''1884660''>think</span> <span m=''1884820''>of</span>
  <span m=''1884920''>what</span> <span m=''1885070''>that</span> <span m=''1885200''>would</span>
  <span m=''1885300''>have</span> <span m=''1885570''>to</span> <span m=''1885690''>mean,</span>
  <span m=''1886930''>it</span> <span m=''1887030''>would</span> <span m=''1887120''>have</span>
  <span m=''1887280''>to</span> <span m=''1887440''>mean</span> <span m=''1887840''>that</span>
  <span m=''1888060''>x</span> <span m=''1888430''>had better</span> <span m=''1888670''>be</span>
  <span m=''1888810''>the</span> <span m=''1888890''>same</span> <span m=''1889210''>as</span>
  <span m=''1889330''>y,</span> <span m=''1890950''>but</span> <span m=''1891110''>also</span>
  <span m=''1891870''>x</span> <span m=''1892230''>had</span> <span m=''1892430''>better</span>
  <span m=''1892590''>be the</span> <span m=''1892650''>same</span> <span m=''1893300''>as</span>
  <span m=''1893550''>a</span> <span m=''1893610''>list</span> <span m=''1893920''>whose</span>
  <span m=''1894100''>first</span> <span m=''1894350''>element</span> <span m=''1894660''>is</span>
  <span m=''1894890''>a</span> <span m=''1895160''>and whose</span> <span m=''1895330''>rest</span>
  <span m=''1895620''>is</span> <span m=''1895740''>y.</span> <span m=''1897330''>And</span>
  <span m=''1897490''>if</span> <span m=''1897580''>you</span> <span m=''1897660''>think</span>
  <span m=''1897850''>about</span> <span m=''1898090''>what</span> <span m=''1898230''>that</span>
  <span m=''1898430''>would</span> <span m=''1898550''>have</span> <span m=''1898750''>to</span>
  <span m=''1898950''>mean,</span> <span m=''1902380''>it would</span> <span m=''1902540''>have
  to</span> <span m=''1902720''>mean</span> <span m=''1902850''>that</span> <span
  m=''1903000''>y</span> <span m=''1903280''>is</span> <span m=''1903410''>the</span>
  <span m=''1903550''>infinite</span> <span m=''1903910''>list</span> <span m=''1904260''>of
  a''s.</span> <span m=''1907500''>In</span> <span m=''1907660''>some</span> <span
  m=''1907940''>sense,</span> <span m=''1909280''>in</span> <span m=''1909430''>order</span>
  <span m=''1909620''>to</span> <span m=''1911370''>do</span> <span m=''1911510''>that</span>
  <span m=''1911690''>unification,</span> <span m=''1912630''>I</span> <span m=''1912810''>have</span>
  <span m=''1913010''>to</span> <span m=''1913100''>solve</span> <span m=''1913640''>the</span>
  <span m=''1913710''>fixed-point</span> <span m=''1914210''>equation</span> <span
  m=''1915330''>cons</span> <span m=''1917666''>of</span> <span m=''1918865''>a</span>
  <span m=''1919140''>to</span> <span m=''1919300''>y</span> <span m=''1921030''>is</span>
  <span m=''1921160''>equal</span> <span m=''1921460''>to y.</span> </p><p><span m=''1924570''>And</span>
  <span m=''1924760''>in</span> <span m=''1924890''>general,</span> <span m=''1925730''>I</span>
  <span m=''1925830''>wrote</span> <span m=''1925990''>a</span> <span m=''1926020''>very</span>
  <span m=''1926230''>simple</span> <span m=''1926560''>one.</span> <span m=''1927290''>Really</span>
  <span m=''1927700''>doing</span> <span m=''1927960''>unification</span> <span m=''1928980''>might</span>
  <span m=''1929210''>have</span> <span m=''1929360''>to</span> <span m=''1929460''>solve</span>
  <span m=''1930020''>an</span> <span m=''1930200''>arbitrary</span> <span m=''1931260''>fixed-point</span>
  <span m=''1931680''>equation:</span> <span m=''1932150''>f</span> <span m=''1932350''>of</span>
  <span m=''1932420''>y</span> <span m=''1932710''>equals</span> <span m=''1933030''>y.</span>
  <span m=''1935530''>And</span> <span m=''1935830''>basically,</span> <span m=''1936220''>you</span>
  <span m=''1936330''>can''t</span> <span m=''1936680''>do</span> <span m=''1936830''>that
  and</span> <span m=''1937120''>make</span> <span m=''1937390''>the</span> <span
  m=''1937440''>thing</span> <span m=''1938260''>finite</span> <span m=''1938750''>all</span>
  <span m=''1938880''>the</span> <span m=''1939010''>time.</span> <span m=''1940570''>So</span>
  <span m=''1940790''>how</span> <span m=''1940930''>does</span> <span m=''1942090''>the</span>
  <span m=''1942180''>logic</span> <span m=''1942570''>language</span> <span m=''1942950''>handle</span>
  <span m=''1943260''>that?</span> <span m=''1945140''>The</span> <span m=''1945290''>answer</span>
  <span m=''1945550''>is</span> <span m=''1945800''>it</span> <span m=''1946100''>doesn''t.</span>
  <span m=''1946850''>It</span> <span m=''1947280''>just</span> <span m=''1947680''>punts.</span>
  <span m=''1948730''>And</span> <span m=''1948870''>there''s</span> <span m=''1949010''>a</span>
  <span m=''1949060''>little</span> <span m=''1949260''>check</span> <span m=''1949620''>in</span>
  <span m=''1949730''>the</span> <span m=''1949840''>unifier,</span> <span m=''1951310''>which</span>
  <span m=''1951590''>says,</span> <span m=''1952060''>oh,</span> <span m=''1952280''>is</span>
  <span m=''1952470''>this</span> <span m=''1952650''>one</span> <span m=''1952870''>of</span>
  <span m=''1952970''>the</span> <span m=''1953050''>hard</span> <span m=''1953320''>cases</span>
  <span m=''1954550''>which</span> <span m=''1954730''>when</span> <span m=''1954870''>I</span>
  <span m=''1954940''>go</span> <span m=''1955080''>to</span> <span m=''1955170''>match</span>
  <span m=''1955520''>things</span> <span m=''1956030''>would</span> <span m=''1956230''>involve</span>
  <span m=''1956610''>solving</span> <span m=''1956960''>a</span> <span m=''1957010''>fixed-point</span>
  <span m=''1957450''>equation?</span> </p><p><span m=''1958650''>And</span> <span
  m=''1958920''>in</span> <span m=''1959050''>this</span> <span m=''1959180''>case,</span>
  <span m=''1959450''>I</span> <span m=''1959560''>will</span> <span m=''1959840''>throw</span>
  <span m=''1960220''>up</span> <span m=''1960330''>my</span> <span m=''1960480''>hands.</span>
  <span m=''1962840''>And</span> <span m=''1963010''>if</span> <span m=''1963410''>that</span>
  <span m=''1963620''>check</span> <span m=''1963860''>were</span> <span m=''1963990''>not</span>
  <span m=''1964240''>in</span> <span m=''1964350''>there,</span> <span m=''1964990''>what</span>
  <span m=''1965260''>would</span> <span m=''1965370''>happen?</span> <span m=''1967990''>In</span>
  <span m=''1968180''>most</span> <span m=''1968520''>cases</span> <span m=''1968830''>is</span>
  <span m=''1969140''>that</span> <span m=''1969310''>the</span> <span m=''1969390''>unifier</span>
  <span m=''1969860''>would</span> <span m=''1969970''>just</span> <span m=''1970170''>go</span>
  <span m=''1970290''>into</span> <span m=''1970510''>an</span> <span m=''1970590''>infinite</span>
  <span m=''1970960''>loop.</span> <span m=''1973740''>And</span> <span m=''1974450''>other</span>
  <span m=''1974680''>logic</span> <span m=''1975040''>programming</span> <span m=''1975460''>languages</span>
  <span m=''1975870''>work</span> <span m=''1976070''>like</span> <span m=''1976260''>that.</span>
  <span m=''1976800''>So</span> <span m=''1977010''>there''s</span> <span m=''1977180''>really</span>
  <span m=''1977500''>no</span> <span m=''1977670''>magic.</span> <span m=''1978220''>The</span>
  <span m=''1978390''>easy</span> <span m=''1978640''>case is</span> <span m=''1979050''>done</span>
  <span m=''1979240''>in</span> <span m=''1979320''>a</span> <span m=''1979400''>matcher.</span>
  <span m=''1980100''>The</span> <span m=''1980210''>hard</span> <span m=''1980440''>case</span>
  <span m=''1980680''>is</span> <span m=''1980790''>not</span> <span m=''1980990''>done</span>
  <span m=''1981200''>at</span> <span m=''1981400''>all.</span> <span m=''1982960''>And</span>
  <span m=''1983210''>that''s</span> <span m=''1983970''>about</span> <span m=''1984140''>the</span>
  <span m=''1984310''>state</span> <span m=''1984570''>of</span> <span m=''1984650''>this</span>
  <span m=''1984790''>technology.</span> </p><p><span m=''1992840''>Let</span> <span
  m=''1992950''>me</span> <span m=''1993060''>just</span> <span m=''1993350''>say</span>
  <span m=''1993540''>again</span> <span m=''1993780''>formally</span> <span m=''1994240''>how</span>
  <span m=''1994390''>rules</span> <span m=''1994710''>work</span> <span m=''1994960''>now</span>
  <span m=''1995090''>that</span> <span m=''1995170''>I</span> <span m=''1995250''>talked</span>
  <span m=''1995520''>about</span> <span m=''1995710''>unifiers.</span> <span m=''1997390''>So</span>
  <span m=''1997550''>the</span> <span m=''1997680''>official</span> <span m=''1998040''>definition</span>
  <span m=''1999320''>is</span> <span m=''1999530''>that</span> <span m=''1999730''>to</span>
  <span m=''1999860''>apply</span> <span m=''2000320''>a</span> <span m=''2000420''>rule,</span>
  <span m=''2004110''>we--</span> <span m=''2005260''>well, let''s</span> <span m=''2005470''>start</span>
  <span m=''2005730''>using</span> <span m=''2005980''>some</span> <span m=''2006150''>words</span>
  <span m=''2006430''>we''ve used</span> <span m=''2006760''>before.</span> <span
  m=''2008270''>Let''s</span> <span m=''2008500''>talk</span> <span m=''2008740''>about</span>
  <span m=''2009350''>sticking</span> <span m=''2010190''>dictionaries</span> <span
  m=''2011340''>into</span> <span m=''2012850''>these</span> <span m=''2013120''>big</span>
  <span m=''2013280''>boxes</span> <span m=''2013790''>of</span> <span m=''2014290''>query</span>
  <span m=''2014610''>things</span> <span m=''2014890''>as</span> <span m=''2015060''>evaluating</span>
  <span m=''2017480''>these</span> <span m=''2017710''>large</span> <span m=''2018020''>queries</span>
  <span m=''2020090''>relative</span> <span m=''2021410''>to</span> <span m=''2022370''>an</span>
  <span m=''2022530''>environment</span> <span m=''2023190''>or a</span> <span m=''2023380''>frame.</span>
  <span m=''2023850''>So when you</span> <span m=''2024200''>think</span> <span m=''2024340''>of</span>
  <span m=''2024440''>that</span> <span m=''2024510''>dictionary,</span> <span m=''2025090''>what''s</span>
  <span m=''2025220''>the</span> <span m=''2025350''>dictionary</span> <span m=''2025870''>after</span>
  <span m=''2026170''>all?</span> <span m=''2026720''>It''s</span> <span m=''2026940''>a</span>
  <span m=''2027000''>bunch</span> <span m=''2027260''>of</span> <span m=''2027350''>meanings</span>
  <span m=''2027700''>for</span> <span m=''2027810''>symbols.</span> <span m=''2028180''>That''s</span>
  <span m=''2028350''>what</span> <span m=''2028450''>we''ve</span> <span m=''2028570''>been</span>
  <span m=''2028700''>calling</span> <span m=''2028960''>frames</span> <span m=''2029440''>or</span>
  <span m=''2029590''>environments.</span> </p><p><span m=''2031800''>What</span>
  <span m=''2031920''>does</span> <span m=''2032050''>it</span> <span m=''2032130''>mean</span>
  <span m=''2032300''>to</span> <span m=''2032770''>do</span> <span m=''2032900''>some</span>
  <span m=''2033070''>processing</span> <span m=''2033610''>relevant</span> <span
  m=''2033960''>to</span> <span m=''2035370''>an</span> <span m=''2035430''>environment?</span>
  <span m=''2035970''>That''s</span> <span m=''2036130''>what we''ve</span> <span
  m=''2036260''>been</span> <span m=''2036380''>calling</span> <span m=''2036640''>evaluation.</span>
  <span m=''2038310''>So</span> <span m=''2038470''>we</span> <span m=''2038590''>can</span>
  <span m=''2038690''>say</span> <span m=''2038970''>the</span> <span m=''2039210''>way</span>
  <span m=''2039870''>that</span> <span m=''2040240''>you</span> <span m=''2040730''>apply</span>
  <span m=''2041130''>a</span> <span m=''2041220''>rule</span> <span m=''2041940''>is</span>
  <span m=''2042090''>to</span> <span m=''2042240''>evaluate</span> <span m=''2043030''>the</span>
  <span m=''2043130''>rule</span> <span m=''2043350''>body</span> <span m=''2044490''>relative</span>
  <span m=''2045080''>to</span> <span m=''2045280''>an</span> <span m=''2045360''>environment</span>
  <span m=''2046560''>that''s</span> <span m=''2046980''>formed</span> <span m=''2047520''>by</span>
  <span m=''2047730''>unifying</span> <span m=''2049100''>the</span> <span m=''2049260''>rule</span>
  <span m=''2049530''>conclusion</span> <span m=''2050710''>with</span> <span m=''2050820''>the</span>
  <span m=''2050929''>given</span> <span m=''2051219''>query.</span> <span m=''2053230''>And</span>
  <span m=''2053360''>the</span> <span m=''2053489''>thing</span> <span m=''2053679''>I</span>
  <span m=''2053719''>want</span> <span m=''2053929''>you</span> <span m=''2054010''>to</span>
  <span m=''2054100''>notice</span> <span m=''2054830''>is</span> <span m=''2055060''>the</span>
  <span m=''2055170''>complete</span> <span m=''2055949''>formal</span> <span m=''2056340''>similarity</span>
  <span m=''2058110''>to</span> <span m=''2058250''>the</span> <span m=''2058310''>net</span>
  <span m=''2058469''>of</span> <span m=''2058510''>circular</span> <span m=''2058980''>evaluator</span>
  <span m=''2060540''>or</span> <span m=''2060670''>the</span> <span m=''2060760''>substitution</span>
  <span m=''2061400''>model.</span> </p><p><span m=''2061630''>To</span> <span m=''2061750''>apply</span>
  <span m=''2062100''>a</span> <span m=''2062159''>procedure,</span> <span m=''2062880''>we</span>
  <span m=''2063070''>evaluate</span> <span m=''2064530''>the</span> <span m=''2064909''>procedure</span>
  <span m=''2065420''>body</span> <span m=''2067100''>relative</span> <span m=''2067530''>to</span>
  <span m=''2067699''>an</span> <span m=''2067790''>environment</span> <span m=''2068520''>that''s</span>
  <span m=''2068870''>formed</span> <span m=''2069139''>by</span> <span m=''2069300''>blinding</span>
  <span m=''2070860''>the</span> <span m=''2071040''>procedure</span> <span m=''2071500''>parameters</span>
  <span m=''2072409''>to</span> <span m=''2072530''>the</span> <span m=''2072659''>arguments.</span>
  <span m=''2074560''>There''s</span> <span m=''2074719''>a</span> <span m=''2074780''>complete</span>
  <span m=''2075260''>formal</span> <span m=''2075600''>similarity</span> <span m=''2076190''>here</span>
  <span m=''2076380''>between the</span> <span m=''2076760''>rules,</span> <span m=''2077860''>rule</span>
  <span m=''2078130''>application,</span> <span m=''2079270''>and</span> <span m=''2079460''>procedure</span>
  <span m=''2079900''>application</span> <span m=''2080610''>even</span> <span m=''2080870''>though</span>
  <span m=''2081000''>these</span> <span m=''2081159''>things</span> <span m=''2081370''>are</span>
  <span m=''2081460''>very,</span> <span m=''2081730''>very</span> <span m=''2081960''>different.</span>
  <span m=''2083650''>And</span> <span m=''2083800''>again,</span> <span m=''2084340''>you</span>
  <span m=''2084489''>have</span> <span m=''2084639''>the</span> <span m=''2084810''>EVAL</span>
  <span m=''2085100''>APPLY</span> <span m=''2085409''>loop.</span> <span m=''2087290''>EVAL</span>
  <span m=''2088870''>and</span> <span m=''2089030''>APPLY.</span> </p><p><span m=''2093360''>So</span>
  <span m=''2093540''>in</span> <span m=''2093659''>general,</span> <span m=''2094270''>I</span>
  <span m=''2094380''>might</span> <span m=''2095690''>be</span> <span m=''2095820''>processing</span>
  <span m=''2096389''>some</span> <span m=''2096570''>combined</span> <span m=''2097050''>expression</span>
  <span m=''2097530''>that</span> <span m=''2097650''>will</span> <span m=''2097740''>turn</span>
  <span m=''2097970''>into</span> <span m=''2098060''>a</span> <span m=''2098150''>rule</span>
  <span m=''2098370''>application,</span> <span m=''2100790''>which</span> <span m=''2100960''>will</span>
  <span m=''2101050''>generate</span> <span m=''2101510''>some</span> <span m=''2101660''>dictionaries</span>
  <span m=''2102290''>or</span> <span m=''2102360''>frames</span> <span m=''2102770''>or</span>
  <span m=''2102830''>environments--</span> <span m=''2103090''>whatever</span> <span
  m=''2103350''>you</span> <span m=''2103590''>want</span> <span m=''2103680''>to</span>
  <span m=''2103780''>call</span> <span m=''2103980''>them--</span> <span m=''2104090''>from</span>
  <span m=''2104280''>match,</span> <span m=''2105060''>which</span> <span m=''2105260''>will</span>
  <span m=''2105360''>then</span> <span m=''2106010''>be the</span> <span m=''2106360''>input</span>
  <span m=''2106710''>to</span> <span m=''2106790''>some</span> <span m=''2106990''>big</span>
  <span m=''2107220''>compound</span> <span m=''2107690''>thing</span> <span m=''2107820''>like</span>
  <span m=''2108060''>this.</span> <span m=''2108660''>This</span> <span m=''2108850''>has</span>
  <span m=''2109590''>pieces</span> <span m=''2109980''>of</span> <span m=''2110210''>it
  and</span> <span m=''2110330''>may</span> <span m=''2110460''>have</span> <span
  m=''2110640''>other</span> <span m=''2110850''>rule</span> <span m=''2111110''>applications.</span>
  <span m=''2113580''>And</span> <span m=''2113940''>you</span> <span m=''2114040''>have</span>
  <span m=''2114470''>essentially</span> <span m=''2115020''>the</span> <span m=''2115110''>same</span>
  <span m=''2115360''>cycle</span> <span m=''2115760''>even</span> <span m=''2115950''>though</span>
  <span m=''2116040''>there''s</span> <span m=''2116220''>nothing</span> <span m=''2116590''>here</span>
  <span m=''2116780''>at</span> <span m=''2117010''>all</span> <span m=''2117430''>that</span>
  <span m=''2117700''>looks</span> <span m=''2117900''>like</span> <span m=''2118100''>procedures.</span>
  <span m=''2119680''>It</span> <span m=''2119810''>really</span> <span m=''2120060''>has</span>
  <span m=''2120240''>to</span> <span m=''2120350''>do</span> <span m=''2120480''>with</span>
  <span m=''2120570''>the</span> <span m=''2120670''>fact</span> <span m=''2120910''>you''ve</span>
  <span m=''2120980''>built</span> <span m=''2121290''>a</span> <span m=''2121330''>language</span>
  <span m=''2122120''>whose</span> <span m=''2122370''>means</span> <span m=''2122750''>of</span>
  <span m=''2122860''>combination</span> <span m=''2123480''>and</span> <span m=''2123590''>abstraction</span>
  <span m=''2124150''>unwind</span> <span m=''2124650''>in</span> <span m=''2124740''>certain</span>
  <span m=''2125090''>ways.</span> </p><p><span m=''2128770''>And</span> <span m=''2128900''>then</span>
  <span m=''2129030''>in</span> <span m=''2129120''>general,</span> <span m=''2129740''>what</span>
  <span m=''2130000''>happens at</span> <span m=''2130390''>the</span> <span m=''2130470''>very</span>
  <span m=''2130720''>top</span> <span m=''2131050''>level,</span> <span m=''2133840''>you</span>
  <span m=''2133950''>might</span> <span m=''2134120''>have</span> <span m=''2134290''>rules</span>
  <span m=''2134620''>in</span> <span m=''2134770''>your</span> <span m=''2134910''>database</span>
  <span m=''2135470''>also,</span> <span m=''2136660''>so</span> <span m=''2136960''>things</span>
  <span m=''2137220''>in</span> <span m=''2137280''>this</span> <span m=''2137400''>database</span>
  <span m=''2137890''>might</span> <span m=''2138120''>be</span> <span m=''2138250''>rules.</span>
  <span m=''2140460''>There</span> <span m=''2140580''>are</span> <span m=''2140620''>ways</span>
  <span m=''2140880''>to</span> <span m=''2140980''>check</span> <span m=''2141210''>that</span>
  <span m=''2141340''>things</span> <span m=''2141570''>are</span> <span m=''2141640''>true.</span>
  <span m=''2142920''>So it</span> <span m=''2143130''>might</span> <span m=''2143290''>come
  in</span> <span m=''2143610''>here</span> <span m=''2143770''>and</span> <span m=''2143840''>have</span>
  <span m=''2143990''>to</span> <span m=''2144080''>do</span> <span m=''2144210''>a</span>
  <span m=''2144260''>rule</span> <span m=''2144520''>check.</span> <span m=''2146750''>And</span>
  <span m=''2146930''>then</span> <span m=''2147120''>there''s</span> <span m=''2147310''>some</span>
  <span m=''2147460''>control</span> <span m=''2147830''>structure</span> <span m=''2148180''>which</span>
  <span m=''2148370''>says,</span> <span m=''2148480''>well,</span> <span m=''2148580''>you</span>
  <span m=''2148710''>look</span> <span m=''2148830''>at</span> <span m=''2148950''>some</span>
  <span m=''2149120''>rules,</span> <span m=''2149420''>and</span> <span m=''2149490''>you</span>
  <span m=''2149620''>look</span> <span m=''2149760''>at</span> <span m=''2149830''>some</span>
  <span m=''2149950''>data</span> <span m=''2150130''>elements,</span> <span m=''2150520''>and</span>
  <span m=''2150600''>you</span> <span m=''2150750''>look at</span> <span m=''2150880''>some</span>
  <span m=''2151030''>rules</span> <span m=''2151270''>and</span> <span m=''2151350''>data</span>
  <span m=''2151530''>elements,</span> <span m=''2151900''>and these</span> <span
  m=''2152030''>fan</span> <span m=''2152350''>out and</span> <span m=''2152500''>out
  and</span> <span m=''2152730''>out.</span> </p><p><span m=''2153350''>So</span>
  <span m=''2153540''>it</span> <span m=''2153600''>becomes</span> <span m=''2154430''>essentially</span>
  <span m=''2154840''>impossible</span> <span m=''2155610''>to</span> <span m=''2155810''>say</span>
  <span m=''2155990''>what</span> <span m=''2156180''>order</span> <span m=''2156520''>it''s</span>
  <span m=''2156660''>looking</span> <span m=''2156930''>at</span> <span m=''2157000''>these</span>
  <span m=''2157200''>things</span> <span m=''2157490''>in,</span> <span m=''2158310''>whether</span>
  <span m=''2158570''>it''s</span> <span m=''2158720''>breadth</span> <span m=''2158980''>first</span>
  <span m=''2159300''>or</span> <span m=''2159370''>depth</span> <span m=''2159650''>first</span>
  <span m=''2159930''>or</span> <span m=''2159990''>anything.</span> <span m=''2160245''>And</span>
  <span m=''2160500''>it''s</span> <span m=''2160670''>even</span> <span m=''2160880''>more</span>
  <span m=''2161110''>impossible</span> <span m=''2161670''>because</span> <span m=''2161960''>the</span>
  <span m=''2162090''>actual</span> <span m=''2162520''>order</span> <span m=''2163490''>is</span>
  <span m=''2163650''>somehow</span> <span m=''2163900''>buried</span> <span m=''2164250''>in</span>
  <span m=''2164360''>the</span> <span m=''2164430''>delays</span> <span m=''2164820''>of</span>
  <span m=''2164910''>the</span> <span m=''2164990''>streams.</span> <span m=''2167680''>So</span>
  <span m=''2168380''>what''s</span> <span m=''2168640''>very</span> <span m=''2168900''>hard</span>
  <span m=''2169130''>to</span> <span m=''2169220''>tell</span> <span m=''2169430''>from</span>
  <span m=''2169600''>this</span> <span m=''2169760''>is</span> <span m=''2169870''>the</span>
  <span m=''2169960''>order</span> <span m=''2170300''>in</span> <span m=''2170370''>which</span>
  <span m=''2170540''>it''s</span> <span m=''2170650''>scanned.</span> <span m=''2171270''>But</span>
  <span m=''2171490''>what''s</span> <span m=''2171710''>true,</span> <span m=''2172140''>because</span>
  <span m=''2172480''>you''re</span> <span m=''2172620''>looking</span> <span m=''2172850''>at</span>
  <span m=''2172930''>the</span> <span m=''2173000''>stream</span> <span m=''2173330''>view,</span>
  <span m=''2173960''>is</span> <span m=''2174100''>that</span> <span m=''2174240''>all</span>
  <span m=''2174440''>of</span> <span m=''2174520''>them</span> <span m=''2174700''>eventually</span>
  <span m=''2175170''>get</span> <span m=''2175370''>looked</span> <span m=''2175590''>at.</span>
  </p><p><span m=''2184980''>Let</span> <span m=''2185090''>me</span> <span m=''2185210''>just</span>
  <span m=''2185420''>mention</span> <span m=''2185780''>one</span> <span m=''2186300''>tiny</span>
  <span m=''2187260''>technical</span> <span m=''2187700''>problem.</span> <span m=''2197530''>Suppose</span>
  <span m=''2197790''>I</span> <span m=''2197880''>tried</span> <span m=''2198180''>saying</span>
  <span m=''2198540''>boss</span> <span m=''2198830''>of</span> <span m=''2199990''>y</span>
  <span m=''2200370''>is</span> <span m=''2200550''>computer,</span> <span m=''2204260''>then</span>
  <span m=''2204570''>a</span> <span m=''2204650''>funny</span> <span m=''2204960''>thing</span>
  <span m=''2205130''>would</span> <span m=''2205250''>happen.</span> <span m=''2205780''>As</span>
  <span m=''2205960''>I</span> <span m=''2206060''>stuck</span> <span m=''2206760''>a</span>
  <span m=''2206890''>dictionary</span> <span m=''2207450''>with</span> <span m=''2209470''>y
  in</span> <span m=''2209970''>here,</span> <span m=''2212780''>I</span> <span m=''2212900''>might</span>
  <span m=''2213130''>get--</span> <span m=''2213680''>this</span> <span m=''2213900''>y</span>
  <span m=''2214280''>is</span> <span m=''2214480''>not</span> <span m=''2214710''>the</span>
  <span m=''2214790''>same</span> <span m=''2215170''>as</span> <span m=''2216820''>that</span>
  <span m=''2217090''>y,</span> <span m=''2217440''>which</span> <span m=''2217650''>was</span>
  <span m=''2217800''>the</span> <span m=''2218870''>other</span> <span m=''2219100''>piece</span>
  <span m=''2219350''>of</span> <span m=''2219420''>somebody''s</span> <span m=''2219840''>job</span>
  <span m=''2220080''>description.</span> <span m=''2221580''>So</span> <span m=''2221750''>if</span>
  <span m=''2221860''>I</span> <span m=''2221920''>really</span> <span m=''2222270''>only</span>
  <span m=''2222560''>did</span> <span m=''2222730''>literally</span> <span m=''2223180''>what</span>
  <span m=''2223310''>I</span> <span m=''2223400''>said,</span> <span m=''2224270''>we''d</span>
  <span m=''2224380''>get</span> <span m=''2224550''>some</span> <span m=''2225020''>variable</span>
  <span m=''2225470''>conflict</span> <span m=''2225970''>problems.</span> <span m=''2228890''>So</span>
  <span m=''2229360''>I</span> <span m=''2229500''>lied to</span> <span m=''2229840''>you</span>
  <span m=''2229950''>a</span> <span m=''2229990''>little</span> <span m=''2230220''>bit.</span>
  </p><p><span m=''2230930''>Notice</span> <span m=''2231250''>that</span> <span m=''2231450''>problem</span>
  <span m=''2231870''>is</span> <span m=''2232070''>exactly</span> <span m=''2232550''>a</span>
  <span m=''2232600''>problem</span> <span m=''2232900''>we''ve</span> <span m=''2233060''>run</span>
  <span m=''2233180''>into</span> <span m=''2233410''>before.</span> <span m=''2234360''>It</span>
  <span m=''2234490''>is</span> <span m=''2234710''>precisely</span> <span m=''2235820''>the</span>
  <span m=''2236150''>need</span> <span m=''2236430''>for</span> <span m=''2236550''>local</span>
  <span m=''2236890''>variables</span> <span m=''2237720''>in a</span> <span m=''2237880''>language.</span>
  <span m=''2240505''>When</span> <span m=''2240780''>I</span> <span m=''2240940''>have</span>
  <span m=''2241090''>the</span> <span m=''2241150''>sum</span> <span m=''2241370''>of</span>
  <span m=''2241440''>squares,</span> <span m=''2241800''>that</span> <span m=''2242020''>x</span>
  <span m=''2242460''>had better</span> <span m=''2242520''>not</span> <span m=''2242710''>be
  that</span> <span m=''2242850''>x.</span> <span m=''2244960''>That''s</span> <span
  m=''2245170''>exactly</span> <span m=''2245650''>the</span> <span m=''2245720''>same</span>
  <span m=''2246070''>as</span> <span m=''2247620''>this</span> <span m=''2247830''>y</span>
  <span m=''2248440''>had</span> <span m=''2248620''>better</span> <span m=''2248840''>not</span>
  <span m=''2249070''>be</span> <span m=''2249200''>that</span> <span m=''2249470''>y.</span>
  <span m=''2251800''>And</span> <span m=''2251910''>we</span> <span m=''2252020''>know
  how</span> <span m=''2252200''>to solve</span> <span m=''2252590''>that.</span>
  <span m=''2253100''>That</span> <span m=''2253220''>was</span> <span m=''2253350''>this</span>
  <span m=''2253480''>whole</span> <span m=''2253690''>environment</span> <span m=''2254180''>model,</span>
  <span m=''2254550''>and</span> <span m=''2254640''>we</span> <span m=''2254730''>built</span>
  <span m=''2254940''>chains</span> <span m=''2255300''>of</span> <span m=''2255380''>frames</span>
  <span m=''2255770''>and</span> <span m=''2255840''>all</span> <span m=''2255970''>sorts</span>
  <span m=''2256210''>of</span> <span m=''2256290''>things</span> <span m=''2256510''>like</span>
  <span m=''2256710''>that.</span> </p><p><span m=''2257710''>There''s</span> <span
  m=''2257930''>a</span> <span m=''2257970''>much</span> <span m=''2258130''>more</span>
  <span m=''2258250''>brutal</span> <span m=''2258610''>way</span> <span m=''2258720''>to</span>
  <span m=''2258830''>solve it.</span> <span m=''2259270''>In the</span> <span m=''2259350''>query</span>
  <span m=''2259640''>language,</span> <span m=''2260010''>we</span> <span m=''2260110''>didn''t</span>
  <span m=''2261120''>even</span> <span m=''2261380''>do</span> <span m=''2261520''>that.</span>
  <span m=''2261730''>We</span> <span m=''2261810''>did</span> <span m=''2261940''>something</span>
  <span m=''2262220''>completely</span> <span m=''2262720''>brutal.</span> <span m=''2263540''>We</span>
  <span m=''2263790''>said</span> <span m=''2264410''>every</span> <span m=''2264750''>time</span>
  <span m=''2265020''>you</span> <span m=''2265140''>apply</span> <span m=''2265480''>a</span>
  <span m=''2265570''>rule,</span> <span m=''2267310''>rename</span> <span m=''2267800''>consistently</span>
  <span m=''2268380''>all</span> <span m=''2268520''>the</span> <span m=''2268600''>variables</span>
  <span m=''2269110''>in</span> <span m=''2269190''>the</span> <span m=''2269270''>rule</span>
  <span m=''2269710''>to</span> <span m=''2269900''>some</span> <span m=''2270120''>new</span>
  <span m=''2270200''>unique</span> <span m=''2270610''>names</span> <span m=''2270950''>that</span>
  <span m=''2271100''>won''t</span> <span m=''2272560''>conflict</span> <span m=''2272920''>with</span>
  <span m=''2273020''>anything.</span> <span m=''2275720''>That''s</span> <span m=''2276060''>conceptually</span>
  <span m=''2276690''>simpler,</span> <span m=''2277080''>but</span> <span m=''2277280''>really</span>
  <span m=''2277540''>brutal and</span> <span m=''2277960''>not</span> <span m=''2278150''>particularly</span>
  <span m=''2278660''>efficient.</span> </p><p><span m=''2279970''>But</span> <span
  m=''2280660''>notice,</span> <span m=''2281340''>we</span> <span m=''2281520''>could</span>
  <span m=''2281640''>have</span> <span m=''2281770''>gotten</span> <span m=''2283170''>rid</span>
  <span m=''2283330''>of all of</span> <span m=''2283440''>our</span> <span m=''2283700''>environment</span>
  <span m=''2284180''>structures</span> <span m=''2285610''>if</span> <span m=''2285770''>we</span>
  <span m=''2285880''>defined</span> <span m=''2286720''>for</span> <span m=''2286900''>procedures</span>
  <span m=''2287530''>in Lisp</span> <span m=''2288030''>the</span> <span m=''2288280''>same</span>
  <span m=''2288550''>thing.</span> <span m=''2289180''>If every time</span> <span
  m=''2289390''>we</span> <span m=''2289480''>applied</span> <span m=''2289760''>a</span>
  <span m=''2289850''>procedure</span> <span m=''2290300''>and</span> <span m=''2290440''>did</span>
  <span m=''2290510''>the</span> <span m=''2290580''>substitution</span> <span m=''2291220''>model</span>
  <span m=''2291880''>we</span> <span m=''2292080''>renamed</span> <span m=''2292560''>all</span>
  <span m=''2292700''>the</span> <span m=''2292790''>variables</span> <span m=''2293270''>in</span>
  <span m=''2293340''>the</span> <span m=''2293410''>procedure,</span> <span m=''2294180''>then</span>
  <span m=''2294320''>we</span> <span m=''2294410''>never</span> <span m=''2294600''>would</span>
  <span m=''2294700''>have</span> <span m=''2294810''>had</span> <span m=''2294960''>to</span>
  <span m=''2295040''>worry</span> <span m=''2295320''>about</span> <span m=''2295570''>local</span>
  <span m=''2295830''>variables</span> <span m=''2296185''>because they</span> <span
  m=''2296540''>would</span> <span m=''2296710''>never</span> <span m=''2297100''>arise.</span>
  <span m=''2299040''>OK,</span> <span m=''2299350''>well,</span> <span m=''2299480''>that</span>
  <span m=''2299610''>would</span> <span m=''2299750''>be</span> <span m=''2299870''>inefficient,</span>
  <span m=''2300860''>and</span> <span m=''2301110''>it''s</span> <span m=''2301240''>inefficient</span>
  <span m=''2301690''>here</span> <span m=''2301860''>in</span> <span m=''2301920''>the</span>
  <span m=''2301990''>query</span> <span m=''2302280''>language,</span> <span m=''2302670''>too,</span>
  <span m=''2303070''>but</span> <span m=''2303510''>we</span> <span m=''2303620''>did</span>
  <span m=''2303780''>it</span> <span m=''2303870''>to</span> <span m=''2303920''>keep</span>
  <span m=''2304110''>it</span> <span m=''2304220''>simple.</span> <span m=''2305610''>Let''s</span>
  <span m=''2305880''>break</span> <span m=''2306110''>for</span> <span m=''2306190''>questions.</span>
  </p><p><span m=''2310880''>AUDIENCE: When</span> <span m=''2311040''>you</span>
  <span m=''2311180''>started</span> <span m=''2311920''>this</span> <span m=''2313130''>section,</span>
  <span m=''2313570''>you</span> <span m=''2314130''>emphasized</span> <span m=''2314870''>how</span>
  <span m=''2315310''>powerful</span> <span m=''2317410''>our</span> <span m=''2318530''>APPLY</span>
  <span m=''2318700''>EVAL</span> <span m=''2319050''>model</span> <span m=''2319370''>was</span>
  <span m=''2319640''>that</span> <span m=''2319740''>we</span> <span m=''2319880''>could</span>
  <span m=''2320020''>use</span> <span m=''2320240''>it</span> <span m=''2320390''>for</span>
  <span m=''2320540''>any</span> <span m=''2320750''>language.</span> <span m=''2321170''>And</span>
  <span m=''2321330''>then</span> <span m=''2321480''>you</span> <span m=''2321570''>say</span>
  <span m=''2321680''>we''re going</span> <span m=''2321850''>to have</span> <span
  m=''2322010''>this</span> <span m=''2322240''>language</span> <span m=''2322660''>which
  is</span> <span m=''2322790''>so</span> <span m=''2322960''>different.</span> <span
  m=''2323950''>It</span> <span m=''2324060''>turns</span> <span m=''2324350''>out</span>
  <span m=''2324510''>that</span> <span m=''2324630''>this</span> <span m=''2324800''>language,</span>
  <span m=''2325690''>as</span> <span m=''2325840''>you</span> <span m=''2325930''>just</span>
  <span m=''2326160''>pointed</span> <span m=''2326440''>out,</span> <span m=''2326650''>is</span>
  <span m=''2327070''>very</span> <span m=''2327270''>much</span> <span m=''2327490''>the</span>
  <span m=''2327610''>same.</span> <span m=''2327880''>I''m</span> <span m=''2327990''>wondering</span>
  <span m=''2328310''>if</span> <span m=''2328420''>you''re</span> <span m=''2328590''>arguing</span>
  <span m=''2328770''>that</span> <span m=''2328850''>all</span> <span m=''2329040''>languages</span>
  <span m=''2329470''>end</span> <span m=''2329710''>up</span> <span m=''2330470''>coming</span>
  <span m=''2330780''>down</span> <span m=''2331040''>to</span> <span m=''2331130''>this</span>
  <span m=''2332210''>you</span> <span m=''2332340''>can</span> <span m=''2332460''>apply
  a</span> <span m=''2332870''>rule</span> <span m=''2333170''>or</span> <span m=''2333470''>apply
  a</span> <span m=''2333810''>procedure</span> <span m=''2334195''>or</span> <span
  m=''2335120''>some</span> <span m=''2335330''>kind</span> <span m=''2335470''>of</span>
  <span m=''2335560''>apply?</span> </p><p><span m=''2337030''>PROFESSOR: I</span>
  <span m=''2337220''>would</span> <span m=''2337420''>say</span> <span m=''2337550''>that</span>
  <span m=''2337720''>pretty</span> <span m=''2337950''>much</span> <span m=''2338160''>any</span>
  <span m=''2338370''>language</span> <span m=''2338970''>where</span> <span m=''2339150''>you</span>
  <span m=''2339320''>really</span> <span m=''2339640''>are</span> <span m=''2339800''>building</span>
  <span m=''2340200''>up</span> <span m=''2340980''>these</span> <span m=''2341750''>means
  of</span> <span m=''2342040''>combination</span> <span m=''2343020''>and</span>
  <span m=''2343210''>giving</span> <span m=''2343520''>them</span> <span m=''2343810''>simpler</span>
  <span m=''2343930''>names</span> <span m=''2344750''>and</span> <span m=''2344920''>you''re</span>
  <span m=''2345030''>saying</span> <span m=''2345420''>anything</span> <span m=''2345900''>of</span>
  <span m=''2346010''>the</span> <span m=''2346120''>sort,</span> <span m=''2346540''>like</span>
  <span m=''2347580''>here''s</span> <span m=''2348020''>a</span> <span m=''2348130''>general</span>
  <span m=''2348840''>kind</span> <span m=''2349070''>of</span> <span m=''2349300''>expression,</span>
  <span m=''2350100''>like</span> <span m=''2350290''>how</span> <span m=''2350430''>to</span>
  <span m=''2350580''>square</span> <span m=''2350900''>something,</span> <span m=''2352360''>almost</span>
  <span m=''2352560''>anything</span> <span m=''2352960''>that</span> <span m=''2353070''>you</span>
  <span m=''2353180''>would</span> <span m=''2353290''>call</span> <span m=''2353520''>a</span>
  <span m=''2353580''>procedure.</span> <span m=''2354880''>If</span> <span m=''2355020''>that''s</span>
  <span m=''2355280''>got</span> <span m=''2355360''>to</span> <span m=''2355440''>have</span>
  <span m=''2355650''>parts,</span> <span m=''2355940''>you</span> <span m=''2356080''>have</span>
  <span m=''2356220''>to</span> <span m=''2356360''>unwind</span> <span m=''2356760''>those</span>
  <span m=''2356960''>parts.</span> <span m=''2358020''>You</span> <span m=''2358140''>have</span>
  <span m=''2358260''>to</span> <span m=''2358340''>have</span> <span m=''2358410''>some</span>
  <span m=''2358680''>kind</span> <span m=''2358820''>of</span> <span m=''2358970''>organization</span>
  <span m=''2359670''>which</span> <span m=''2359820''>says</span> <span m=''2360620''>when</span>
  <span m=''2360750''>I</span> <span m=''2360830''>look</span> <span m=''2360960''>at</span>
  <span m=''2361090''>the</span> <span m=''2361250''>abstract</span> <span m=''2363050''>variables</span>
  <span m=''2363600''>or</span> <span m=''2363680''>tags</span> <span m=''2364100''>or</span>
  <span m=''2364190''>whatever</span> <span m=''2364600''>you  want to</span> <span
  m=''2365040''>call them that</span> <span m=''2365280''>might</span> <span m=''2365500''>stand</span>
  <span m=''2365840''>for</span> <span m=''2366020''>particular</span> <span m=''2366650''>things,</span>
  <span m=''2368370''>you</span> <span m=''2368490''>have</span> <span m=''2368600''>to</span>
  <span m=''2368670''>keep</span> <span m=''2368840''>track</span> <span m=''2369160''>of</span>
  <span m=''2369240''>that,</span> <span m=''2369420''>and that''s going</span> <span
  m=''2369550''>to</span> <span m=''2369630''>be</span> <span m=''2369720''>something</span>
  <span m=''2370080''>like</span> <span m=''2370280''>an</span> <span m=''2370370''>environment.</span>
  <span m=''2371720''>And</span> <span m=''2371880''>then</span> <span m=''2372020''>if</span>
  <span m=''2372120''>you</span> <span m=''2372210''>say</span> <span m=''2372700''>this</span>
  <span m=''2373050''>part</span> <span m=''2373390''>can</span> <span m=''2373560''>have</span>
  <span m=''2373800''>parts</span> <span m=''2374170''>which</span> <span m=''2374330''>I</span>
  <span m=''2374440''>have</span> <span m=''2374560''>to</span> <span m=''2374670''>unwind,</span>
  <span m=''2375880''>you''ve</span> <span m=''2376020''>got</span> <span m=''2376130''>to</span>
  <span m=''2376240''>have</span> <span m=''2376390''>something</span> <span m=''2376690''>like</span>
  <span m=''2376890''>this</span> <span m=''2377050''>cycle.</span> </p><p><span m=''2379970''>And</span>
  <span m=''2381150''>lots</span> <span m=''2381480''>and</span> <span m=''2381550''>lots</span>
  <span m=''2381810''>of</span> <span m=''2381870''>languages</span> <span m=''2382350''>have</span>
  <span m=''2382540''>that</span> <span m=''2382720''>character</span> <span m=''2383730''>when</span>
  <span m=''2383900''>they</span> <span m=''2384000''>sort</span> <span m=''2384170''>of</span>
  <span m=''2384230''>get</span> <span m=''2384390''>put</span> <span m=''2384550''>together</span>
  <span m=''2384910''>in</span> <span m=''2385050''>this</span> <span m=''2385180''>way.</span>
  <span m=''2385590''>This</span> <span m=''2385830''>language</span> <span m=''2386160''>again</span>
  <span m=''2386440''>really</span> <span m=''2386740''>is</span> <span m=''2386890''>different</span>
  <span m=''2387200''>because</span> <span m=''2387440''>there''s</span> <span m=''2387610''>nothing</span>
  <span m=''2388010''>like</span> <span m=''2388260''>procedures</span> <span m=''2388730''>on</span>
  <span m=''2388860''>the</span> <span m=''2388980''>outside.</span> <span m=''2390690''>When</span>
  <span m=''2390800''>you</span> <span m=''2390870''>go</span> <span m=''2391010''>below</span>
  <span m=''2391200''>the</span> <span m=''2391290''>surface</span> <span m=''2391680''>and</span>
  <span m=''2391760''>you</span> <span m=''2391830''>see</span> <span m=''2391980''>the</span>
  <span m=''2392080''>implementation,</span> <span m=''2392800''>of</span> <span m=''2392890''>course,</span>
  <span m=''2393110''>it</span> <span m=''2393190''>starts</span> <span m=''2393470''>looking</span>
  <span m=''2393720''>the</span> <span m=''2393790''>same.</span> <span m=''2394870''>But</span>
  <span m=''2395030''>from</span> <span m=''2395130''>the</span> <span m=''2395250''>outside,</span>
  <span m=''2395590''>it''s</span> <span m=''2395710''>a</span> <span m=''2395760''>very</span>
  <span m=''2396020''>different</span> <span m=''2396290''>world</span> <span m=''2396620''>view.</span>
  <span m=''2396950''>You''re</span> <span m=''2397080''>not</span> <span m=''2397270''>computing</span>
  <span m=''2397690''>functions</span> <span m=''2398100''>of</span> <span m=''2398200''>inputs.</span>
  </p><p><span m=''2403970''>AUDIENCE: You</span> <span m=''2404110''>mentioned</span>
  <span m=''2404500''>earlier</span> <span m=''2404930''>that</span> <span m=''2406370''>when</span>
  <span m=''2406680''>you</span> <span m=''2407370''>build</span> <span m=''2407920''>all
  of</span> <span m=''2408050''>these</span> <span m=''2408320''>rules</span> <span
  m=''2408700''>in</span> <span m=''2409143''>pattern</span> <span m=''2409586''>matcher</span>
  <span m=''2410030''>and</span> <span m=''2410260''>with</span> <span m=''2410460''>the
  delayed</span> <span m=''2410660''>action</span> <span m=''2410975''>of streams,</span>
  <span m=''2411290''>you</span> <span m=''2411550''>really have</span> <span m=''2411810''>no
  way</span> <span m=''2412010''>to</span> <span m=''2412390''>know</span> <span m=''2413140''>in</span>
  <span m=''2413550''>what</span> <span m=''2413900''>order things</span> <span m=''2414230''>are
  evaluated.</span> </p><p><span m=''2415495''>PROFESSOR: Right.</span> </p><p><span
  m=''2415940''>AUDIENCE: And that</span> <span m=''2416385''>would</span> <span m=''2416830''>indicate</span>
  <span m=''2417275''>then</span> <span m=''2417720''>that</span> <span m=''2419060''>you</span>
  <span m=''2419280''>should</span> <span m=''2419470''>only</span> <span m=''2419700''>express</span>
  <span m=''2420260''>declarative</span> <span m=''2420825''>knowledge</span> <span
  m=''2421240''>that''s</span> <span m=''2421360''>true</span> <span m=''2421690''>for</span>
  <span m=''2421850''>all-time,</span> <span m=''2422020''>no-time</span> <span m=''2422400''>sequence</span>
  <span m=''2422690''>built</span> <span m=''2423110''>into it.</span> <span m=''2423950''>Otherwise,</span>
  <span m=''2424440''>these</span> <span m=''2424940''>things get</span> <span m=''2425440''>all--</span>
  </p><p><span m=''2427440''>PROFESSOR: Yes.</span> <span m=''2428490''>Yes.</span>
  <span m=''2428820''>The</span> <span m=''2428930''>question</span> <span m=''2429290''>is</span>
  <span m=''2430110''>this</span> <span m=''2430360''>really</span> <span m=''2430680''>is</span>
  <span m=''2430820''>set</span> <span m=''2431010''>up</span> <span m=''2431220''>for</span>
  <span m=''2431330''>doing</span> <span m=''2431590''>declarative</span> <span m=''2432100''>knowledge,</span>
  <span m=''2433250''>and</span> <span m=''2433440''>as</span> <span m=''2433700''>I</span>
  <span m=''2433800''>presented</span> <span m=''2434320''>it--</span> <span m=''2434490''>and</span>
  <span m=''2434780''>I''ll</span> <span m=''2436660''>show</span> <span m=''2436800''>you</span>
  <span m=''2436920''>some</span> <span m=''2437140''>of</span> <span m=''2437190''>the</span>
  <span m=''2437690''>ugly</span> <span m=''2437840''>warts</span> <span m=''2438430''>under</span>
  <span m=''2438610''>this</span> <span m=''2438880''>after</span> <span m=''2439110''>the</span>
  <span m=''2439190''>break.</span> <span m=''2440830''>As</span> <span m=''2441040''>I</span>
  <span m=''2441120''>presented</span> <span m=''2441395''>it,</span> <span m=''2441670''>it''s</span>
  <span m=''2441820''>just</span> <span m=''2442000''>doing</span> <span m=''2442250''>logic.</span>
  <span m=''2443070''>And</span> <span m=''2443240''>in</span> <span m=''2443320''>principle,</span>
  <span m=''2443590''>if it</span> <span m=''2443860''>were</span> <span m=''2444090''>logic,</span>
  <span m=''2444530''>it</span> <span m=''2444630''>wouldn''t</span> <span m=''2444870''>matter</span>
  <span m=''2445570''>what</span> <span m=''2445720''>order</span> <span m=''2445990''>it''s</span>
  <span m=''2446130''>getting</span> <span m=''2446370''>done.</span> <span m=''2448840''>And</span>
  <span m=''2450740''>it''s</span> <span m=''2451020''>quite</span> <span m=''2451230''>true</span>
  <span m=''2451540''>when</span> <span m=''2451720''>you</span> <span m=''2451810''>start</span>
  <span m=''2452080''>doing</span> <span m=''2452310''>things</span> <span m=''2452620''>where</span>
  <span m=''2452730''>you</span> <span m=''2452840''>have</span> <span m=''2453020''>side</span>
  <span m=''2453290''>effects</span> <span m=''2453770''>like</span> <span m=''2453980''>adding
  things</span> <span m=''2454480''>to</span> <span m=''2454560''>the</span> <span
  m=''2454660''>database</span> <span m=''2455260''>and</span> <span m=''2455380''>taking</span>
  <span m=''2455680''>things</span> <span m=''2455900''>out,</span> <span m=''2456860''>and</span>
  <span m=''2457350''>we''ll</span> <span m=''2457460''>see</span> <span m=''2457620''>some</span>
  <span m=''2457820''>others,</span> <span m=''2458880''>you</span> <span m=''2459420''>use</span>
  <span m=''2459830''>that</span> <span m=''2459990''>kind</span> <span m=''2460120''>of</span>
  <span m=''2460260''>control.</span> </p><p><span m=''2461290''>So,</span> <span
  m=''2461470''>for</span> <span m=''2461590''>example,</span> <span m=''2461890''>contrasting</span>
  <span m=''2462370''>with</span> <span m=''2462500''>Prolog.</span> <span m=''2462940''>Say</span>
  <span m=''2463120''>Prolog</span> <span m=''2463540''>has</span> <span m=''2464370''>various</span>
  <span m=''2464780''>features</span> <span m=''2465160''>where</span> <span m=''2465300''>you</span>
  <span m=''2465440''>really</span> <span m=''2465720''>exploit</span> <span m=''2466570''>the</span>
  <span m=''2466700''>order</span> <span m=''2466920''>of</span> <span m=''2467010''>evaluation.</span>
  <span m=''2469640''>And</span> <span m=''2470190''>people</span> <span m=''2470410''>write</span>
  <span m=''2470580''>Prolog</span> <span m=''2470890''>programs</span> <span m=''2471310''>that</span>
  <span m=''2471490''>way.</span> <span m=''2471770''>That</span> <span m=''2472070''>turns</span>
  <span m=''2472310''>out</span> <span m=''2472420''>to</span> <span m=''2472490''>be</span>
  <span m=''2472560''>very</span> <span m=''2472810''>complicated</span> <span m=''2473170''>in</span>
  <span m=''2473530''>Prolog,</span> <span m=''2474420''>although</span> <span m=''2474710''>if</span>
  <span m=''2474800''>you''re</span> <span m=''2474910''>an</span> <span m=''2474990''>expert</span>
  <span m=''2475510''>Prolog</span> <span m=''2475940''>programmer,</span> <span m=''2476780''>you</span>
  <span m=''2476920''>can</span> <span m=''2477180''>do</span> <span m=''2477370''>it.</span>
  <span m=''2478590''>However,</span> <span m=''2478890''>here</span> <span m=''2479100''>I</span>
  <span m=''2479150''>don''t</span> <span m=''2479320''>think</span> <span m=''2479490''>you</span>
  <span m=''2479580''>can</span> <span m=''2479680''>do</span> <span m=''2479810''>it
  at</span> <span m=''2479950''>all.</span> <span m=''2480210''>It''s</span> <span
  m=''2480350''>very</span> <span m=''2480600''>complicated</span> <span m=''2481800''>because</span>
  <span m=''2481920''>you</span> <span m=''2482060''>really</span> <span m=''2482340''>are</span>
  <span m=''2482490''>giving</span> <span m=''2482790''>up</span> <span m=''2482890''>control</span>
  <span m=''2483370''>over</span> <span m=''2483720''>any</span> <span m=''2484160''>prearranged</span>
  <span m=''2484730''>order of</span> <span m=''2485040''>trying</span> <span m=''2485380''>things.</span>
  </p><p><span m=''2487150''>AUDIENCE: Now,</span> <span m=''2487350''>that would</span>
  <span m=''2487790''>indicate</span> <span m=''2488070''>then</span> <span m=''2488360''>that</span>
  <span m=''2488510''>you</span> <span m=''2488650''>have</span> <span m=''2489100''>a</span>
  <span m=''2489210''>functional</span> <span m=''2489750''>mapping.</span> <span
  m=''2490670''>And</span> <span m=''2491160''>when</span> <span m=''2491300''>you</span>
  <span m=''2491350''>started</span> <span m=''2491730''>out this</span> <span m=''2491970''>lecture,</span>
  <span m=''2492972''>you</span> <span m=''2493394''>said</span> <span m=''2493816''>that</span>
  <span m=''2494660''>we</span> <span m=''2494870''>express</span> <span m=''2495430''>the</span>
  <span m=''2495530''>declarative</span> <span m=''2495810''>knowledge</span> <span
  m=''2496050''>which</span> <span m=''2496230''>is</span> <span m=''2496320''>a</span>
  <span m=''2496370''>relation,</span> <span m=''2496635''>and</span> <span m=''2497200''>we</span>
  <span m=''2497380''>don''t</span> <span m=''2497880''>talk about</span> <span m=''2498210''>the
  inputs</span> <span m=''2498540''>and the outputs.</span> </p><p><span m=''2501390''>PROFESSOR:
  Well,</span> <span m=''2502020''>there''s</span> <span m=''2502160''>a</span> <span
  m=''2502220''>pun</span> <span m=''2502460''>on</span> <span m=''2502590''>functional,</span>
  <span m=''2503190''>right?</span> <span m=''2503370''>There''s function</span> <span
  m=''2503930''>in</span> <span m=''2503970''>the</span> <span m=''2504050''>sense</span>
  <span m=''2504310''>of</span> <span m=''2504930''>no</span> <span m=''2505110''>side</span>
  <span m=''2505390''>effects</span> <span m=''2506240''>and</span> <span m=''2506410''>not</span>
  <span m=''2506560''>depending</span> <span m=''2506920''>on</span> <span m=''2507040''>what</span>
  <span m=''2507190''>order is</span> <span m=''2507570''>going</span> <span m=''2507840''>on.</span>
  <span m=''2508700''>And</span> <span m=''2508800''>then there''s</span> <span m=''2508900''>functional</span>
  <span m=''2509210''>in the</span> <span m=''2509520''>sense</span> <span m=''2509710''>of</span>
  <span m=''2509770''>mathematical</span> <span m=''2510720''>function,</span> <span
  m=''2511130''>which</span> <span m=''2511290''>means</span> <span m=''2511470''>input</span>
  <span m=''2511740''>and</span> <span m=''2511860''>output.</span> <span m=''2512220''>And</span>
  <span m=''2512430''>it''s</span> <span m=''2512780''>just</span> <span m=''2513070''>that</span>
  <span m=''2513200''>pun  that</span> <span m=''2513350''>you''re</span> <span m=''2513700''>making,</span>
  <span m=''2514000''>I</span> <span m=''2514300''>think.</span> </p><p><span m=''2516510''>AUDIENCE:
  I''m</span> <span m=''2516810''>a</span> <span m=''2516840''>little</span> <span
  m=''2517060''>unclear</span> <span m=''2517425''>on</span> <span m=''2517790''>what</span>
  <span m=''2517980''>you''re</span> <span m=''2518150''>doing</span> <span m=''2518380''>with
  these</span> <span m=''2518660''>two</span> <span m=''2519170''>statements,</span>
  <span m=''2519630''>the</span> <span m=''2519920''>two</span> <span m=''2520330''>boss
  statements.</span> <span m=''2521270''>Is</span> <span m=''2521490''>the</span>
  <span m=''2521720''>first</span> <span m=''2521940''>one</span> <span m=''2524000''>building</span>
  <span m=''2524480''>up</span> <span m=''2525560''>the</span> <span m=''2525740''>database
  and</span> <span m=''2526230''>the second one</span> <span m=''2526510''>a query</span>
  <span m=''2527350''>or--</span> </p><p><span m=''2529150''>PROFESSOR: OK,</span>
  <span m=''2529570''>I''m</span> <span m=''2529740''>sorry.</span> <span m=''2532440''>What</span>
  <span m=''2532540''>I</span> <span m=''2532640''>meant</span> <span m=''2532910''>here,</span>
  <span m=''2533050''>if</span> <span m=''2533180''>I</span> <span m=''2533270''>type</span>
  <span m=''2533590''>something</span> <span m=''2533910''>like</span> <span m=''2534130''>this</span>
  <span m=''2534360''>in</span> <span m=''2534490''>as</span> <span m=''2534590''>a</span>
  <span m=''2534680''>query--</span> <span m=''2536200''>I</span> <span m=''2536310''>should</span>
  <span m=''2536500''>have</span> <span m=''2536600''>given</span> <span m=''2536820''>an</span>
  <span m=''2536900''>example</span> <span m=''2537290''>way</span> <span m=''2537570''>at</span>
  <span m=''2537660''>the</span> <span m=''2537740''>very</span> <span m=''2537980''>beginning.</span>
  <span m=''2539470''>If</span> <span m=''2539670''>I</span> <span m=''2539760''>type</span>
  <span m=''2540080''>in</span> <span m=''2541690''>job,</span> <span m=''2542120''>Ben</span>
  <span m=''2542310''>Bitdiddle,</span> <span m=''2542720''>computer</span> <span
  m=''2543120''>wizard,</span> <span m=''2545100''>what</span> <span m=''2545240''>the</span>
  <span m=''2545320''>processing</span> <span m=''2545860''>will</span> <span m=''2545990''>do</span>
  <span m=''2546550''>is</span> <span m=''2546740''>if</span> <span m=''2546820''>it</span>
  <span m=''2546920''>finds</span> <span m=''2547190''>a</span> <span m=''2547250''>match,</span>
  <span m=''2548400''>it''ll</span> <span m=''2548570''>find</span> <span m=''2548830''>a</span>
  <span m=''2548870''>match</span> <span m=''2549150''>to</span> <span m=''2549240''>that</span>
  <span m=''2549450''>exact</span> <span m=''2549920''>thing,</span> <span m=''2550860''>and</span>
  <span m=''2551040''>it''ll</span> <span m=''2551190''>type</span> <span m=''2551420''>out</span>
  <span m=''2551580''>a</span> <span m=''2551600''>job,</span> <span m=''2551980''>Ben</span>
  <span m=''2552140''>Bitdiddle,</span> <span m=''2552510''>computer</span> <span
  m=''2552900''>wizard.</span> <span m=''2554220''>If</span> <span m=''2554380''>it</span>
  <span m=''2554480''>doesn''t</span> <span m=''2554870''>find</span> <span m=''2555130''>a</span>
  <span m=''2555170''>match,</span> <span m=''2555750''>it</span> <span m=''2555850''>won''t</span>
  <span m=''2556060''>find</span> <span m=''2556280''>anything.</span> </p><p><span
  m=''2557400''>So</span> <span m=''2558330''>what</span> <span m=''2558490''>I</span>
  <span m=''2558550''>should</span> <span m=''2558720''>have</span> <span m=''2558810''>said</span>
  <span m=''2559030''>is</span> <span m=''2559140''>the</span> <span m=''2559220''>way</span>
  <span m=''2559380''>you</span> <span m=''2559490''>use</span> <span m=''2559710''>the</span>
  <span m=''2559800''>query</span> <span m=''2560100''>language</span> <span m=''2560450''>to</span>
  <span m=''2560590''>check</span> <span m=''2561140''>whether</span> <span m=''2561380''>something</span>
  <span m=''2561770''>is</span> <span m=''2561890''>true,</span> <span m=''2563132''>remember,</span>
  <span m=''2563610''>that''s</span> <span m=''2563830''>one</span> <span m=''2563980''>of</span>
  <span m=''2564050''>the</span> <span m=''2564130''>things</span> <span m=''2564310''>you</span>
  <span m=''2564410''>want</span> <span m=''2564490''>to</span> <span m=''2564580''>do</span>
  <span m=''2564730''>in</span> <span m=''2564820''>logic</span> <span m=''2565130''>programming,</span>
  <span m=''2566450''>is</span> <span m=''2566600''>you</span> <span m=''2566690''>type</span>
  <span m=''2566930''>in</span> <span m=''2567030''>your</span> <span m=''2567140''>query</span>
  <span m=''2567510''>and either</span> <span m=''2567730''>that</span> <span m=''2567990''>comes</span>
  <span m=''2568240''>out</span> <span m=''2568410''>or</span> <span m=''2568630''>it</span>
  <span m=''2568960''>doesn''t.</span> <span m=''2570680''>So</span> <span m=''2570930''>what</span>
  <span m=''2571160''>I</span> <span m=''2571240''>was</span> <span m=''2571500''>trying</span>
  <span m=''2571640''>to</span> <span m=''2571780''>illustrate</span> <span m=''2572210''>here,</span>
  <span m=''2572430''>I</span> <span m=''2572470''>wanted</span> <span m=''2572690''>to</span>
  <span m=''2572940''>start</span> <span m=''2573250''>with</span> <span m=''2573330''>a</span>
  <span m=''2573410''>very</span> <span m=''2573620''>simple</span> <span m=''2574420''>example</span>
  <span m=''2574900''>before</span> <span m=''2575220''>talking</span> <span m=''2575610''>about</span>
  <span m=''2575920''>unifiers.</span> <span m=''2577480''>So</span> <span m=''2577660''>what</span>
  <span m=''2577770''>I</span> <span m=''2577840''>should</span> <span m=''2578010''>have</span>
  <span m=''2578080''>said,</span> <span m=''2578240''>if</span> <span m=''2578350''>I</span>
  <span m=''2578420''>just</span> <span m=''2578710''>wanted</span> <span m=''2579050''>to</span>
  <span m=''2579180''>check</span> <span m=''2579910''>whether</span> <span m=''2580260''>this</span>
  <span m=''2580480''>is</span> <span m=''2580620''>true,</span> <span m=''2581230''>I</span>
  <span m=''2581350''>could</span> <span m=''2581510''>type</span> <span m=''2581780''>that</span>
  <span m=''2581930''>in</span> <span m=''2582100''>and</span> <span m=''2582210''>see</span>
  <span m=''2582370''>if</span> <span m=''2582470''>anything</span> <span m=''2582820''>came</span>
  <span m=''2583030''>out</span> </p><p><span m=''2584854''>AUDIENCE: And then the</span>
  <span m=''2585352''>second one--</span> </p><p><span m=''2586290''>PROFESSOR: The</span>
  <span m=''2586490''>second</span> <span m=''2586690''>one</span> <span m=''2586840''>would</span>
  <span m=''2586950''>be</span> <span m=''2587070''>a</span> <span m=''2587140''>real</span>
  <span m=''2587330''>query.</span> </p><p><span m=''2587830''>AUDIENCE: A real</span>
  <span m=''2588320''>query, yeah.</span> </p><p><span m=''2590770''>PROFESSOR: What</span>
  <span m=''2590880''>would</span> <span m=''2591020''>come</span> <span m=''2591210''>out,</span>
  <span m=''2591660''>see, it</span> <span m=''2591810''>would</span> <span m=''2591960''>go</span>
  <span m=''2592120''>in</span> <span m=''2592210''>here</span> <span m=''2592380''>say</span>
  <span m=''2592530''>with</span> <span m=''2592700''>FOO,</span> <span m=''2593950''>and</span>
  <span m=''2594110''>in</span> <span m=''2594370''>would</span> <span m=''2594530''>go</span>
  <span m=''2594590''>frame</span> <span m=''2594970''>that</span> <span m=''2595110''>says</span>
  <span m=''2596710''>z</span> <span m=''2596990''>is</span> <span m=''2597140''>bound</span>
  <span m=''2597390''>to</span> <span m=''2597480''>who</span> <span m=''2597700''>and</span>
  <span m=''2597820''>d</span> <span m=''2598000''>is bound</span> <span m=''2598220''>to</span>
  <span m=''2598310''>computer.</span> <span m=''2599560''>And</span> <span m=''2599670''>this</span>
  <span m=''2599790''>will</span> <span m=''2599890''>pass</span> <span m=''2600220''>through,</span>
  <span m=''2600460''>and</span> <span m=''2600560''>then</span> <span m=''2600670''>by</span>
  <span m=''2600770''>the</span> <span m=''2600870''>time</span> <span m=''2601130''>it</span>
  <span m=''2601220''>got</span> <span m=''2601400''>out</span> <span m=''2601550''>of</span>
  <span m=''2601640''>here,</span> <span m=''2601960''>who</span> <span m=''2602290''>would</span>
  <span m=''2602460''>pick</span> <span m=''2602640''>up</span> <span m=''2602760''>a</span>
  <span m=''2602810''>binding.</span> </p><p><span m=''2606950''>AUDIENCE: On</span>
  <span m=''2607110''>the</span> <span m=''2607470''>unifying</span> <span m=''2608230''>thing</span>
  <span m=''2608430''>there,</span> <span m=''2610880''>I</span> <span m=''2611150''>still</span>
  <span m=''2611410''>am</span> <span m=''2611670''>not</span> <span m=''2611950''>sure</span>
  <span m=''2612220''>what</span> <span m=''2612470''>happens</span> <span m=''2613340''>with</span>
  <span m=''2613960''>who</span> <span m=''2615040''>and</span> <span m=''2615350''>z.</span>
  <span m=''2616460''>If</span> <span m=''2616790''>the</span> <span m=''2617170''>unifying--</span>
  <span m=''2617850''>the</span> <span m=''2618430''>rule</span> <span m=''2618780''>here</span>
  <span m=''2619020''>says--</span> <span m=''2622070''>OK, so</span> <span m=''2622300''>you</span>
  <span m=''2622570''>say</span> <span m=''2622800''>that you can''t</span> <span
  m=''2623300''>make</span> <span m=''2623400''>question</span> <span m=''2623880''>mark</span>
  <span m=''2624320''>equal</span> <span m=''2624690''>to</span> <span m=''2624920''>question</span>
  <span m=''2625320''>mark</span> <span m=''2625720''>who.</span> </p><p><span m=''2626260''>PROFESSOR:
  Right.</span> <span m=''2626410''>That''s</span> <span m=''2626580''>what</span>
  <span m=''2626720''>the</span> <span m=''2627010''>matcher</span> <span m=''2627480''>can''t</span>
  <span m=''2627780''>do.</span> <span m=''2628360''>But</span> <span m=''2629200''>what</span>
  <span m=''2629480''>this</span> <span m=''2629640''>will</span> <span m=''2629730''>mean</span>
  <span m=''2630020''>to</span> <span m=''2630180''>a unifier</span> <span m=''2631990''>is</span>
  <span m=''2632140''>that</span> <span m=''2632290''>there''s</span> <span m=''2632470''>an</span>
  <span m=''2632550''>environment</span> <span m=''2633080''>with</span> <span m=''2633220''>three</span>
  <span m=''2633460''>variables.</span> <span m=''2636690''>d</span> <span m=''2637020''>here
  is</span> <span m=''2637310''>computer.</span> <span m=''2638520''>z</span> <span
  m=''2638860''>is</span> <span m=''2639050''>whatever</span> <span m=''2639460''>who</span>
  <span m=''2639890''>is.</span> <span m=''2641830''>So</span> <span m=''2642040''>if</span>
  <span m=''2642160''>later</span> <span m=''2642500''>on</span> <span m=''2643850''>in</span>
  <span m=''2644090''>the</span> <span m=''2644160''>matcher</span> <span m=''2644760''>routine</span>
  <span m=''2647260''>it</span> <span m=''2647470''>said,</span> <span m=''2648670''>for</span>
  <span m=''2648780''>example,</span> <span m=''2649180''>who</span> <span m=''2649400''>has</span>
  <span m=''2649630''>to</span> <span m=''2649720''>be</span> <span m=''2649860''>3,</span>
  <span m=''2652060''>then</span> <span m=''2652260''>when</span> <span m=''2652380''>I</span>
  <span m=''2652450''>looked</span> <span m=''2652710''>up</span> <span m=''2652830''>in</span>
  <span m=''2652910''>the</span> <span m=''2652990''>dictionary,</span> <span m=''2654110''>it</span>
  <span m=''2654200''>will</span> <span m=''2654300''>say,</span> <span m=''2654500''>oh,
  z</span> <span m=''2654890''>is</span> <span m=''2655040''>3</span> <span m=''2655270''>because</span>
  <span m=''2655470''>it''s</span> <span m=''2655630''>the</span> <span m=''2655680''>same</span>
  <span m=''2655970''>as</span> <span m=''2656100''>who.</span> <span m=''2658360''>And</span>
  <span m=''2658610''>that''s in</span> <span m=''2658880''>some</span> <span m=''2659180''>sense</span>
  <span m=''2659380''>the</span> <span m=''2659490''>only</span> <span m=''2659700''>thing</span>
  <span m=''2659870''>you</span> <span m=''2659930''>need</span> <span m=''2660080''>to</span>
  <span m=''2660230''>do</span> <span m=''2660390''>to</span> <span m=''2660500''>extend</span>
  <span m=''2660820''>the</span> <span m=''2660970''>unifier</span> <span m=''2661460''>to
  a</span> <span m=''2661510''>matcher.</span> </p><p><span m=''2662640''>AUDIENCE:
  OK, because it</span> <span m=''2662990''>looked</span> <span m=''2663340''>like</span>
  <span m=''2663480''>when</span> <span m=''2663590''>you were</span> <span m=''2663830''>telling
  how to</span> <span m=''2664270''>unify</span> <span m=''2664410''>it,</span> <span
  m=''2664550''>it looked</span> <span m=''2664970''>like</span> <span m=''2665180''>you
  would</span> <span m=''2665550''>put</span> <span m=''2665920''>the</span> <span
  m=''2666000''>things</span> <span m=''2666210''>together</span> <span m=''2666290''>in</span>
  <span m=''2666520''>such</span> <span m=''2666760''>a way</span> <span m=''2666990''>that
  you''d</span> <span m=''2667200''>actually</span> <span m=''2667520''>solve</span>
  <span m=''2667810''>and have</span> <span m=''2668100''>a</span> <span m=''2668465''>value
  for</span> <span m=''2668830''>both of them.</span> <span m=''2669770''>And</span>
  <span m=''2670020''>what it</span> <span m=''2670310''>looks</span> <span m=''2670400''>like</span>
  <span m=''2670830''>now</span> <span m=''2671230''>is that you''re</span> <span
  m=''2671500''>actually</span> <span m=''2671720''>pass</span> <span m=''2672180''>a</span>
  <span m=''2672230''>dictionary</span> <span m=''2672970''>with</span> <span m=''2673260''>two</span>
  <span m=''2673550''>variables and the</span> <span m=''2674020''>variables</span>
  <span m=''2674325''>are</span> <span m=''2674630''>linked.</span> </p><p><span m=''2674860''>PROFESSOR:
  Right.</span> <span m=''2675130''>It only</span> <span m=''2675370''>looks</span>
  <span m=''2675820''>like</span> <span m=''2676020''>you''re</span> <span m=''2676370''>solving</span>
  <span m=''2676490''>for</span> <span m=''2676590''>both</span> <span m=''2676880''>of</span>
  <span m=''2676980''>them</span> <span m=''2677580''>because</span> <span m=''2677880''>you''re</span>
  <span m=''2677970''>sort</span> <span m=''2678090''>of</span> <span m=''2678220''>looking</span>
  <span m=''2678510''>at</span> <span m=''2678590''>the</span> <span m=''2678670''>whole</span>
  <span m=''2678840''>solution</span> <span m=''2679270''>at</span> <span m=''2679360''>once.</span>
  <span m=''2680540''>If</span> <span m=''2680690''>you</span> <span m=''2680810''>sort</span>
  <span m=''2681010''>of</span> <span m=''2681110''>watch</span> <span m=''2681420''>the</span>
  <span m=''2681550''>thing</span> <span m=''2681700''>getting</span> <span m=''2681930''>built</span>
  <span m=''2682080''>up</span> <span m=''2682230''>recursively,</span> <span m=''2682790''>it''s</span>
  <span m=''2683020''>merely</span> <span m=''2683330''>this.</span> </p><p><span
  m=''2684980''>AUDIENCE: OK, so</span> <span m=''2685270''>you</span> <span m=''2685520''>do</span>
  <span m=''2685880''>pass</span> <span m=''2686160''>off</span> <span m=''2686390''>that</span>
  <span m=''2686620''>dictionary</span> <span m=''2686970''>with</span> <span m=''2687410''>two</span>
  <span m=''2687860''>variables?</span> </p><p><span m=''2688400''>PROFESSOR: That''s</span>
  <span m=''2688770''>right.</span> </p><p><span m=''2689110''>AUDIENCE: And</span>
  <span m=''2689450''>link?</span> </p><p><span m=''2690190''>PROFESSOR: Right.</span>
  <span m=''2690560''>It</span> <span m=''2690940''>just</span> <span m=''2691180''>looks</span>
  <span m=''2691340''>like</span> <span m=''2691520''>an</span> <span m=''2691900''>ordinary</span>
  <span m=''2692160''>dictionary.</span> </p><p><span m=''2694055''>AUDIENCE: When
  you''re</span> <span m=''2694540''>talking</span> <span m=''2695025''>about the</span>
  <span m=''2695510''>unifier,</span> <span m=''2695995''>is</span> <span m=''2696480''>it</span>
  <span m=''2696965''>that</span> <span m=''2697450''>there</span> <span m=''2697935''>are
  some</span> <span m=''2698420''>cases</span> <span m=''2698905''>or</span> <span
  m=''2699390''>some points</span> <span m=''2699875''>that</span> <span m=''2700845''>you</span>
  <span m=''2701330''>are</span> <span m=''2701815''>not</span> <span m=''2702300''>able</span>
  <span m=''2702785''>to</span> <span m=''2703270''>use</span> <span m=''2703755''>by</span>
  <span m=''2704240''>them?</span> </p><p><span m=''2704725''>PROFESSOR: Right.</span>
  </p><p><span m=''2705220''>AUDIENCE: Can you</span> <span m=''2705630''>just</span>
  <span m=''2706475''>by</span> <span m=''2706930''>building</span> <span m=''2707170''>the</span>
  <span m=''2707655''>rules</span> <span m=''2708140''>or</span> <span m=''2709850''>writing</span>
  <span m=''2710100''>the</span> <span m=''2710570''>forms</span> <span m=''2711820''>know</span>
  <span m=''2712270''>in</span> <span m=''2712720''>advance</span> <span m=''2712995''>if
  you</span> <span m=''2713270''>are going</span> <span m=''2713760''>to</span> <span
  m=''2714694''>be able</span> <span m=''2715138''>to</span> <span m=''2715582''>solve</span>
  <span m=''2716470''>to</span> <span m=''2716610''>get</span> <span m=''2716860''>the</span>
  <span m=''2717080''>unification</span> <span m=''2717355''>or</span> <span m=''2717630''>not?</span>
  <span m=''2718540''>Can</span> <span m=''2718760''>you</span> <span m=''2719130''>add</span>
  <span m=''2719480''>some</span> <span m=''2720135''>properties</span> <span m=''2720540''>either</span>
  <span m=''2721150''>to</span> <span m=''2721840''>the</span> <span m=''2721930''>rules</span>
  <span m=''2722360''>itself</span> <span m=''2723240''>or</span> <span m=''2723560''>to</span>
  <span m=''2723720''>the</span> <span m=''2723890''>formula</span> <span m=''2724330''>that</span>
  <span m=''2724740''>you''re</span> <span m=''2724940''>writing</span> <span m=''2725800''>so</span>
  <span m=''2725980''>that</span> <span m=''2726110''>you avoid</span> <span m=''2726420''>the</span>
  <span m=''2726730''>problem</span> <span m=''2727210''>of</span> <span m=''2727690''>not</span>
  <span m=''2728170''>finding</span> <span m=''2728650''>unification?</span> </p><p><span
  m=''2730090''>PROFESSOR: I</span> <span m=''2730140''>mean,</span> <span m=''2730270''>you</span>
  <span m=''2730380''>can</span> <span m=''2730520''>agree,</span> <span m=''2731460''>I</span>
  <span m=''2731640''>think,</span> <span m=''2732310''>to</span> <span m=''2732510''>write
  in</span> <span m=''2732820''>a</span> <span m=''2732870''>fairly</span> <span m=''2733210''>restricted</span>
  <span m=''2733710''>way</span> <span m=''2733940''>where</span> <span m=''2734090''>you
  won''t</span> <span m=''2734350''>run</span> <span m=''2734610''>into</span> <span
  m=''2734880''>it.</span> <span m=''2735390''>See,</span> <span m=''2735700''>because</span>
  <span m=''2736000''>what</span> <span m=''2736140''>you''re</span> <span m=''2736260''>getting--</span>
  <span m=''2736870''>see,</span> <span m=''2737090''>the</span> <span m=''2737180''>place</span>
  <span m=''2737450''>where</span> <span m=''2737540''>you</span> <span m=''2737680''>get</span>
  <span m=''2737830''>into</span> <span m=''2738060''>problems</span> <span m=''2738570''>is</span>
  <span m=''2738680''>when</span> <span m=''2738820''>you--</span> <span m=''2739760''>well,
  again,</span> <span m=''2740030''>you''re</span> <span m=''2740340''>trying</span>
  <span m=''2740570''>to</span> <span m=''2740670''>match</span> <span m=''2742650''>things</span>
  <span m=''2742910''>like</span> <span m=''2743820''>that</span> <span m=''2744580''>against</span>
  <span m=''2745020''>things</span> <span m=''2745270''>where</span> <span m=''2746280''>these</span>
  <span m=''2746540''>have</span> <span m=''2746700''>structure,</span> <span m=''2747600''>where</span>
  <span m=''2748560''>a,</span> <span m=''2750040''>y,</span> <span m=''2750730''>b,</span>
  <span m=''2754420''>y</span> <span m=''2754840''>something.</span> <span m=''2758980''>So</span>
  <span m=''2759110''>this</span> <span m=''2759280''>is</span> <span m=''2759350''>the</span>
  <span m=''2759430''>kind</span> <span m=''2759570''>of</span> <span m=''2759710''>place</span>
  <span m=''2759940''>where</span> <span m=''2760460''>you''re</span> <span m=''2760570''>going</span>
  <span m=''2760640''>to</span> <span m=''2760710''>get</span> <span m=''2760890''>into</span>
  <span m=''2761080''>trouble.</span> </p><p><span m=''2763070''>AUDIENCE: So</span>
  <span m=''2763320''>you</span> <span m=''2763560''>can do</span> <span m=''2763870''>that</span>
  <span m=''2764960''>syntactically?</span> </p><p><span m=''2766370''>PROFESSOR:
  So</span> <span m=''2766550''>you</span> <span m=''2766720''>can</span> <span m=''2767490''>kind</span>
  <span m=''2767700''>of</span> <span m=''2767910''>watch</span> <span m=''2768250''>your</span>
  <span m=''2768410''>rules</span> <span m=''2768800''>in</span> <span m=''2768850''>the</span>
  <span m=''2768940''>kinds</span> <span m=''2769320''>of</span> <span m=''2769430''>things</span>
  <span m=''2769670''>that</span> <span m=''2769840''>your</span> <span m=''2770000''>writing.</span>
  </p><p><span m=''2771561''>AUDIENCE: So</span> <span m=''2771940''>that''s</span>
  <span m=''2772160''>the</span> <span m=''2772240''>problem</span> <span m=''2772890''>that</span>
  <span m=''2773130''>the builder</span> <span m=''2774100''>of</span> <span m=''2774460''>the</span>
  <span m=''2774850''>database</span> <span m=''2775170''>has to be</span> <span m=''2775550''>concerned?</span>
  </p><p><span m=''2776310''>PROFESSOR: That''s</span> <span m=''2776820''>a</span>
  <span m=''2776870''>problem.</span> <span m=''2779930''>It''s</span> <span m=''2780190''>a</span>
  <span m=''2780420''>problem</span> <span m=''2780460''>either--</span> <span m=''2780710''>not</span>
  <span m=''2780900''>quite</span> <span m=''2781080''>the</span> <span m=''2781170''>builder</span>
  <span m=''2781440''>of</span> <span m=''2781500''>the</span> <span m=''2781580''>database,</span>
  <span m=''2782040''>the</span> <span m=''2782120''>person</span> <span m=''2782430''>who</span>
  <span m=''2782490''>is</span> <span m=''2782580''>expressing</span> <span m=''2783080''>the</span>
  <span m=''2783160''>rules,</span> <span m=''2784050''>or</span> <span m=''2784170''>the</span>
  <span m=''2784270''>builder</span> <span m=''2784550''>of</span> <span m=''2784620''>the</span>
  <span m=''2784690''>database.</span> <span m=''2785800''>What</span> <span m=''2786650''>the</span>
  <span m=''2787110''>unifier</span> <span m=''2787660''>actually</span> <span m=''2787990''>does</span>
  <span m=''2788250''>is</span> <span m=''2788330''>you</span> <span m=''2788440''>can</span>
  <span m=''2788560''>check</span> <span m=''2788800''>at</span> <span m=''2788870''>the</span>
  <span m=''2788950''>next</span> <span m=''2789230''>level</span> <span m=''2789480''>down</span>
  <span m=''2790000''>when</span> <span m=''2790140''>you</span> <span m=''2790260''>actually</span>
  <span m=''2790720''>get</span> <span m=''2790950''>to</span> <span m=''2791050''>the</span>
  <span m=''2791140''>unifier</span> <span m=''2792440''>and</span> <span m=''2792600''>you''ll</span>
  <span m=''2792710''>see</span> <span m=''2792880''>in</span> <span m=''2792990''>the</span>
  <span m=''2793070''>code</span> <span m=''2793310''>where it</span> <span m=''2793470''>looks</span>
  <span m=''2793750''>up</span> <span m=''2793890''>in</span> <span m=''2793970''>the</span>
  <span m=''2794050''>dictionary.</span> <span m=''2794940''>If</span> <span m=''2795090''>it</span>
  <span m=''2795190''>sort of says</span> <span m=''2795610''>what</span> <span m=''2795750''>does</span>
  <span m=''2795890''>y</span> <span m=''2796160''>have</span> <span m=''2796390''>to</span>
  <span m=''2796510''>be?</span> <span m=''2797260''>Oh,</span> <span m=''2797350''>does</span>
  <span m=''2797520''>y</span> <span m=''2797820''>have</span> <span m=''2797970''>to</span>
  <span m=''2798110''>be</span> <span m=''2798240''>something</span> <span m=''2798670''>that</span>
  <span m=''2799510''>contains</span> <span m=''2800100''>a y</span> <span m=''2800570''>as</span>
  <span m=''2800690''>its</span> <span m=''2800840''>expression?</span> <span m=''2801960''>At</span>
  <span m=''2802120''>that</span> <span m=''2802350''>point,</span> <span m=''2802640''>the</span>
  <span m=''2802780''>unifier</span> <span m=''2803090''>and</span> <span m=''2803190''>say,</span>
  <span m=''2803290''>oh</span> <span m=''2803430''>my</span> <span m=''2803590''>God,</span>
  <span m=''2803850''>I''m</span> <span m=''2803960''>trying</span> <span m=''2804250''>to</span>
  <span m=''2805120''>solve</span> <span m=''2805420''>a</span> <span m=''2805480''>fixed-point</span>
  <span m=''2805870''>equation.</span> <span m=''2806240''>I''ll</span> <span m=''2806340''>give
  it</span> <span m=''2806540''>up</span> <span m=''2806720''>here.</span> </p><p><span
  m=''2809220''>AUDIENCE: You</span> <span m=''2809380''>make</span> <span m=''2809600''>the</span>
  <span m=''2809660''>distinction</span> <span m=''2810190''>between</span> <span
  m=''2810560''>the rules</span> <span m=''2810940''>in the</span> <span m=''2811080''>database.</span>
  <span m=''2811910''>Are</span> <span m=''2812746''>the</span> <span m=''2813212''>rules</span>
  <span m=''2815080''>added</span> <span m=''2815355''>to</span> <span m=''2815630''>the</span>
  <span m=''2816110''>database?</span> </p><p><span m=''2816950''>PROFESSOR: Yes.</span>
  <span m=''2817870''>Yes,</span> <span m=''2818100''>I</span> <span m=''2818340''>should
  have</span> <span m=''2818600''>said</span> <span m=''2818720''>that.</span> <span
  m=''2818870''>One</span> <span m=''2819020''>way</span> <span m=''2819140''>to</span>
  <span m=''2819250''>think</span> <span m=''2819550''>about</span> <span m=''2819850''>rules</span>
  <span m=''2820670''>is</span> <span m=''2820850''>that</span> <span m=''2821000''>they''re</span>
  <span m=''2821110''>just</span> <span m=''2821330''>other</span> <span m=''2821540''>things</span>
  <span m=''2821820''>in</span> <span m=''2821920''>the</span> <span m=''2822020''>database.</span>
  <span m=''2823890''>So</span> <span m=''2824140''>if</span> <span m=''2824240''>you</span>
  <span m=''2824340''>want</span> <span m=''2824450''>to</span> <span m=''2824550''>check</span>
  <span m=''2824900''>the</span> <span m=''2825150''>things</span> <span m=''2825350''>that</span>
  <span m=''2825460''>have</span> <span m=''2825550''>to</span> <span m=''2825640''>be</span>
  <span m=''2825750''>checked</span> <span m=''2826050''>in</span> <span m=''2826240''>the</span>
  <span m=''2826320''>database,</span> <span m=''2826800''>they''re</span> <span m=''2826920''>kind</span>
  <span m=''2827080''>of</span> <span m=''2827200''>virtual</span> <span m=''2828020''>facts</span>
  <span m=''2828530''>that</span> <span m=''2828650''>are</span> <span m=''2828740''>in
  the</span> <span m=''2829190''>database.</span> </p><p><span m=''2829445''>AUDIENCE:
  But</span> <span m=''2829700''>in</span> <span m=''2830230''>that</span> <span m=''2830980''>explanation,</span>
  <span m=''2831450''>you</span> <span m=''2831540''>made</span> <span m=''2831990''>the</span>
  <span m=''2832510''>differentiation</span> <span m=''2833880''>between</span> <span
  m=''2834640''>database</span> <span m=''2835775''>and the</span> <span m=''2836250''>rules</span>
  <span m=''2836910''>itself.</span> </p><p><span m=''2838230''>PROFESSOR: Yeah,</span>
  <span m=''2838400''>I</span> <span m=''2838480''>probably</span> <span m=''2838850''>should</span>
  <span m=''2839050''>not</span> <span m=''2839240''>have</span> <span m=''2839350''>done</span>
  <span m=''2839560''>that.</span> <span m=''2840490''>The</span> <span m=''2840650''>only</span>
  <span m=''2840810''>reason</span> <span m=''2841200''>to</span> <span m=''2841490''>do</span>
  <span m=''2841630''>that</span> <span m=''2841820''>is</span> <span m=''2841980''>in</span>
  <span m=''2842060''>terms</span> <span m=''2842290''>of</span> <span m=''2842360''>the</span>
  <span m=''2842440''>implementation.</span> <span m=''2843540''>When</span> <span
  m=''2843680''>you</span> <span m=''2843780''>look</span> <span m=''2843890''>at</span>
  <span m=''2843990''>the</span> <span m=''2844050''>implementation,</span> <span
  m=''2844740''>there''s</span> <span m=''2844900''>a</span> <span m=''2844960''>part</span>
  <span m=''2845220''>which</span> <span m=''2845410''>says</span> <span m=''2845550''>check</span>
  <span m=''2846650''>either</span> <span m=''2846920''>primitive</span> <span m=''2847460''>assertions</span>
  <span m=''2847960''>in</span> <span m=''2848040''>the</span> <span m=''2848120''>database</span>
  <span m=''2848950''>or</span> <span m=''2849130''>check</span> <span m=''2849410''>rules.</span>
  <span m=''2850470''>And then</span> <span m=''2851660''>the</span> <span m=''2851980''>real</span>
  <span m=''2852200''>reason</span> <span m=''2852470''>why</span> <span m=''2852610''>you</span>
  <span m=''2852720''>can''t</span> <span m=''2853000''>tell</span> <span m=''2853170''>what</span>
  <span m=''2853300''>order</span> <span m=''2853510''>things</span> <span m=''2853740''>are</span>
  <span m=''2853790''>going</span> <span m=''2853860''>to</span> <span m=''2853930''>come</span>
  <span m=''2854120''>out in</span> <span m=''2854330''>and</span> <span m=''2855010''>is</span>
  <span m=''2855260''>that</span> <span m=''2856520''>the</span> <span m=''2856700''>rules</span>
  <span m=''2858010''>database</span> <span m=''2858660''>and</span> <span m=''2858830''>the</span>
  <span m=''2859830''>data</span> <span m=''2860090''>database</span> <span m=''2860490''>sort</span>
  <span m=''2860620''>of</span> <span m=''2860750''>get</span> <span m=''2860910''>merged</span>
  <span m=''2861340''>in</span> <span m=''2861900''>a</span> <span m=''2862100''>kind</span>
  <span m=''2862240''>of</span> <span m=''2862370''>delayed</span> <span m=''2862710''>evaluation</span>
  <span m=''2863410''>way.</span> <span m=''2864600''>And</span> <span m=''2864810''>so</span>
  <span m=''2865040''>that''s</span> <span m=''2865270''>what</span> <span m=''2865360''>makes</span>
  <span m=''2865580''>the</span> <span m=''2865670''>order</span> <span m=''2865890''>very</span>
  <span m=''2866110''>complicated.</span> <span m=''2875440''>OK,</span> <span m=''2875580''>let''s</span>
  <span m=''2875770''>break.</span> </p><p><span m=''2913160''>We''ve</span> <span
  m=''2913320''>just</span> <span m=''2913520''>seen</span> <span m=''2913800''>how</span>
  <span m=''2914210''>the</span> <span m=''2914490''>logic</span> <span m=''2914840''>language</span>
  <span m=''2915170''>works</span> <span m=''2915520''>and</span> <span m=''2915600''>how</span>
  <span m=''2915760''>rules</span> <span m=''2916110''>work.</span> <span m=''2917230''>Now,</span>
  <span m=''2917340''>let''s</span> <span m=''2917500''>turn</span> <span m=''2917690''>to</span>
  <span m=''2918160''>a</span> <span m=''2918280''>more</span> <span m=''2918460''>profound</span>
  <span m=''2918870''>question.</span> </p><p><span m=''2920120''>What</span> <span
  m=''2920340''>do</span> <span m=''2920370''>these</span> <span m=''2920610''>things</span>
  <span m=''2920840''>mean?</span> <span m=''2923180''>That</span> <span m=''2923870''>brings</span>
  <span m=''2924260''>us</span> <span m=''2924430''>to</span> <span m=''2924550''>the</span>
  <span m=''2925140''>subtlest,</span> <span m=''2925820''>most</span> <span m=''2926200''>devious</span>
  <span m=''2926630''>part</span> <span m=''2927100''>of</span> <span m=''2927240''>this</span>
  <span m=''2927390''>whole</span> <span m=''2927570''>query</span> <span m=''2927880''>language</span>
  <span m=''2928230''>business,</span> <span m=''2929270''>and</span> <span m=''2929450''>that</span>
  <span m=''2929640''>is</span> <span m=''2929870''>that</span> <span m=''2931420''>it''s</span>
  <span m=''2931550''>not</span> <span m=''2931810''>quite</span> <span m=''2932140''>what</span>
  <span m=''2932260''>it</span> <span m=''2932380''>seems</span> <span m=''2932650''>to</span>
  <span m=''2932750''>be.</span> <span m=''2933570''>AND</span> <span m=''2934240''>and</span>
  <span m=''2934450''>OR</span> <span m=''2935570''>and</span> <span m=''2935810''>NOT</span>
  <span m=''2937100''>and the</span> <span m=''2937400''>logical</span> <span m=''2937810''>implication</span>
  <span m=''2938380''>of</span> <span m=''2938500''>rules</span> <span m=''2939750''>are</span>
  <span m=''2939910''>not</span> <span m=''2940610''>really</span> <span m=''2941680''>the</span>
  <span m=''2942080''>AND and</span> <span m=''2942480''>OR</span> <span m=''2943740''>and</span>
  <span m=''2943940''>NOT</span> <span m=''2944770''>and</span> <span m=''2944940''>logical</span>
  <span m=''2945400''>implication</span> <span m=''2946100''>of</span> <span m=''2946260''>logic.</span>
  <span m=''2947690''>Let</span> <span m=''2947860''>me</span> <span m=''2948460''>give</span>
  <span m=''2948640''>you</span> <span m=''2948750''>an</span> <span m=''2948850''>example</span>
  <span m=''2949340''>of</span> <span m=''2949440''>that.</span> </p><p><span m=''2949910''>Certainly,</span>
  <span m=''2950820''>if</span> <span m=''2950950''>we</span> <span m=''2951040''>have</span>
  <span m=''2951210''>two</span> <span m=''2951380''>things</span> <span m=''2951650''>in</span>
  <span m=''2951730''>logic,</span> <span m=''2952480''>it</span> <span m=''2952640''>ought</span>
  <span m=''2952840''>to</span> <span m=''2952960''>be</span> <span m=''2953120''>the</span>
  <span m=''2953230''>case</span> <span m=''2953780''>that</span> <span m=''2956790''>AND</span>
  <span m=''2957240''>of</span> <span m=''2958440''>P</span> <span m=''2958930''>and</span>
  <span m=''2959080''>Q</span> <span m=''2960060''>is</span> <span m=''2960230''>the</span>
  <span m=''2960310''>same</span> <span m=''2960670''>as</span> <span m=''2961340''>AND</span>
  <span m=''2961690''>of</span> <span m=''2961850''>Q</span> <span m=''2962000''>and
  P</span> <span m=''2962450''>and</span> <span m=''2962830''>that</span> <span m=''2963430''>OR</span>
  <span m=''2963740''>of</span> <span m=''2963790''>P and</span> <span m=''2964160''>Q</span>
  <span m=''2964850''>is</span> <span m=''2965000''>the</span> <span m=''2965080''>same</span>
  <span m=''2965410''>as</span> <span m=''2965510''>OR</span> <span m=''2965800''>of</span>
  <span m=''2965900''>Q</span> <span m=''2966080''>and P.</span> <span m=''2968710''>But</span>
  <span m=''2968920''>let''s</span> <span m=''2969740''>look</span> <span m=''2969950''>here.</span>
  <span m=''2970100''>Here''s</span> <span m=''2971310''>an</span> <span m=''2971380''>example.</span>
  <span m=''2972180''>Let''s</span> <span m=''2972420''>talk</span> <span m=''2972630''>about</span>
  <span m=''2974380''>somebody</span> <span m=''2974850''>outranking</span> <span
  m=''2975450''>somebody</span> <span m=''2975880''>else</span> <span m=''2976350''>in</span>
  <span m=''2978200''>our</span> <span m=''2978330''>little</span> <span m=''2978660''>database</span>
  <span m=''2979150''>organization.</span> </p><p><span m=''2980140''>We''ll</span>
  <span m=''2980330''>say</span> <span m=''2980540''>s</span> <span m=''2981620''>is</span>
  <span m=''2981790''>outranked</span> <span m=''2982370''>by</span> <span m=''2982730''>b</span>
  <span m=''2984960''>or</span> <span m=''2985310''>if</span> <span m=''2985450''>either</span>
  <span m=''2986800''>the</span> <span m=''2987110''>supervisor</span> <span m=''2987830''>of</span>
  <span m=''2987890''>this</span> <span m=''2988120''>is</span> <span m=''2988270''>b</span>
  <span m=''2989700''>or there''s</span> <span m=''2989950''>some</span> <span m=''2990140''>middle</span>
  <span m=''2990360''>manager</span> <span m=''2990730''>here,</span> <span m=''2990900''>that</span>
  <span m=''2991100''>supervisor</span> <span m=''2991430''>of</span> <span m=''2991760''>s</span>
  <span m=''2992120''>is</span> <span m=''2992280''>m,</span> <span m=''2993750''>and</span>
  <span m=''2994400''>m</span> <span m=''2994610''>is</span> <span m=''2994760''>outranked</span>
  <span m=''2995200''>by</span> <span m=''2995420''>b.</span> <span m=''2999830''>So</span>
  <span m=''2999950''>there''s</span> <span m=''3000360''>one</span> <span m=''3000640''>way</span>
  <span m=''3000760''>to</span> <span m=''3000880''>define</span> <span m=''3001250''>rule</span>
  <span m=''3001510''>outranked</span> <span m=''3001990''>by.</span> <span m=''3002310''>Or</span>
  <span m=''3002590''>we</span> <span m=''3002700''>can write</span> <span m=''3002960''>exactly</span>
  <span m=''3003380''>the</span> <span m=''3003460''>same</span> <span m=''3003740''>thing,</span>
  <span m=''3005200''>except</span> <span m=''3005580''>at</span> <span m=''3005670''>the</span>
  <span m=''3006300''>bottom</span> <span m=''3006620''>here,</span> <span m=''3007310''>we</span>
  <span m=''3007450''>reversed</span> <span m=''3008480''>the</span> <span m=''3008620''>order</span>
  <span m=''3008940''>of</span> <span m=''3009010''>these</span> <span m=''3009200''>two</span>
  <span m=''3009340''>clauses.</span> <span m=''3011630''>And</span> <span m=''3011810''>certainly</span>
  <span m=''3012180''>if</span> <span m=''3012280''>this</span> <span m=''3012450''>were</span>
  <span m=''3012560''>logic,</span> <span m=''3013010''>those</span> <span m=''3013240''>ought</span>
  <span m=''3013550''>to</span> <span m=''3013710''>mean</span> <span m=''3014070''>the</span>
  <span m=''3014180''>same</span> <span m=''3014530''>thing.</span> </p><p><span m=''3016690''>However,</span>
  <span m=''3017810''>in</span> <span m=''3018300''>our</span> <span m=''3018450''>particular</span>
  <span m=''3019000''>implementation,</span> <span m=''3019690''>if</span> <span m=''3019770''>you</span>
  <span m=''3019870''>say</span> <span m=''3020060''>something</span> <span m=''3020420''>like</span>
  <span m=''3021110''>who''s</span> <span m=''3021540''>outranked</span> <span m=''3021980''>by</span>
  <span m=''3022120''>Ben</span> <span m=''3022390''>Bitdiddle,</span> <span m=''3023490''>what</span>
  <span m=''3023640''>you''ll</span> <span m=''3023800''>find</span> <span m=''3024350''>is</span>
  <span m=''3024540''>that</span> <span m=''3024740''>this</span> <span m=''3024950''>rule</span>
  <span m=''3026810''>will</span> <span m=''3026920''>work</span> <span m=''3027150''>perfectly</span>
  <span m=''3027590''>well</span> <span m=''3027800''>and</span> <span m=''3027870''>generate</span>
  <span m=''3028260''>answers,</span> <span m=''3030110''>whereas</span> <span m=''3030390''>this</span>
  <span m=''3030570''>rule</span> <span m=''3030740''>will</span> <span m=''3030870''>go</span>
  <span m=''3031030''>into</span> <span m=''3031250''>an</span> <span m=''3031330''>infinite</span>
  <span m=''3031670''>loop.</span> <span m=''3034110''>And</span> <span m=''3034220''>the</span>
  <span m=''3034340''>reason</span> <span m=''3034630''>for</span> <span m=''3034750''>that
  is</span> <span m=''3035910''>that</span> <span m=''3036380''>this</span> <span
  m=''3036610''>will</span> <span m=''3036800''>come</span> <span m=''3037030''>in</span>
  <span m=''3037110''>and</span> <span m=''3037230''>say,</span> <span m=''3037410''>oh,</span>
  <span m=''3037580''>who''s</span> <span m=''3037990''>outranked</span> <span m=''3038540''>by</span>
  <span m=''3038770''>Ben</span> <span m=''3039085''>Bitdiddle?</span> <span m=''3041920''>Find</span>
  <span m=''3042240''>an</span> <span m=''3042360''>s</span> <span m=''3043990''>which</span>
  <span m=''3044170''>is</span> <span m=''3044310''>outranked</span> <span m=''3044690''>by</span>
  <span m=''3044850''>b,</span> <span m=''3045060''>where</span> <span m=''3045240''>b</span>
  <span m=''3045420''>is</span> <span m=''3045530''>Ben</span> <span m=''3045790''>Bitdiddle,</span>
  <span m=''3047600''>which</span> <span m=''3047760''>is</span> <span m=''3047860''>going</span>
  <span m=''3047930''>to</span> <span m=''3047990''>happen</span> <span m=''3048390''>in
  it</span> <span m=''3048630''>a</span> <span m=''3048740''>subproblem.</span> <span
  m=''3050330''>Oh</span> <span m=''3050490''>gee,</span> <span m=''3051090''>find
  an</span> <span m=''3051570''>m</span> <span m=''3052210''>such</span> <span m=''3052520''>as</span>
  <span m=''3052620''>m is</span> <span m=''3052840''>outranked</span> <span m=''3053260''>by</span>
  <span m=''3053370''>Ben</span> <span m=''3053750''>Bitdiddle</span> <span m=''3055710''>with</span>
  <span m=''3055880''>no</span> <span m=''3056390''>restrictions</span> <span m=''3056940''>on</span>
  <span m=''3057070''>m.</span> </p><p><span m=''3058560''>So</span> <span m=''3058760''>this</span>
  <span m=''3058920''>will</span> <span m=''3058990''>say</span> <span m=''3059130''>in</span>
  <span m=''3059200''>order</span> <span m=''3059380''>to</span> <span m=''3059440''>solve</span>
  <span m=''3059710''>this</span> <span m=''3059900''>problem,</span> <span m=''3061490''>I</span>
  <span m=''3061640''>solve</span> <span m=''3061910''>exactly</span> <span m=''3062400''>the</span>
  <span m=''3062500''>same</span> <span m=''3062790''>problem.</span> <span m=''3064570''>And</span>
  <span m=''3064650''>then</span> <span m=''3064750''>after</span> <span m=''3065000''>I''ve</span>
  <span m=''3065040''>solved</span> <span m=''3065370''>that,</span> <span m=''3065510''>I''ll</span>
  <span m=''3065620''>check</span> <span m=''3065860''>for a</span> <span m=''3066010''>supervisory</span>
  <span m=''3066660''>relationship.</span> <span m=''3068000''>Whereas</span> <span
  m=''3068230''>this</span> <span m=''3068390''>one</span> <span m=''3068510''>won''t</span>
  <span m=''3068680''>get</span> <span m=''3068800''>into</span> <span m=''3068990''>that,</span>
  <span m=''3069170''>because</span> <span m=''3069460''>before</span> <span m=''3070170''>it</span>
  <span m=''3070290''>tries</span> <span m=''3070620''>to</span> <span m=''3070720''>find</span>
  <span m=''3071230''>this</span> <span m=''3071570''>outranked</span> <span m=''3072070''>by,</span>
  <span m=''3072990''>it''ll</span> <span m=''3073330''>already</span> <span m=''3073680''>have</span>
  <span m=''3073820''>had</span> <span m=''3073980''>a</span> <span m=''3074010''>restriction</span>
  <span m=''3074540''>on</span> <span m=''3074730''>m</span> <span m=''3074950''>here.</span>
  <span m=''3078560''>So</span> <span m=''3079420''>these</span> <span m=''3079630''>two</span>
  <span m=''3079760''>things</span> <span m=''3079940''>which</span> <span m=''3080080''>ought</span>
  <span m=''3080270''>to</span> <span m=''3080380''>mean</span> <span m=''3080550''>the</span>
  <span m=''3080610''>same,</span> <span m=''3081050''>in</span> <span m=''3081190''>fact,</span>
  <span m=''3081440''>one</span> <span m=''3081620''>goes</span> <span m=''3081830''>into</span>
  <span m=''3082040''>an</span> <span m=''3082120''>infinite</span> <span m=''3082470''>loop.</span>
  <span m=''3082860''>One</span> <span m=''3084460''>does</span> <span m=''3084620''>not.</span>
  </p><p><span m=''3086720''>That''s</span> <span m=''3087060''>a</span> <span m=''3088660''>very</span>
  <span m=''3088950''>extreme</span> <span m=''3089450''>case</span> <span m=''3089760''>of</span>
  <span m=''3089840''>a</span> <span m=''3089900''>general</span> <span m=''3090240''>thing</span>
  <span m=''3090380''>that</span> <span m=''3090510''>you''ll</span> <span m=''3090630''>find</span>
  <span m=''3090910''>in</span> <span m=''3091000''>logic</span> <span m=''3091310''>programming</span>
  <span m=''3092150''>that</span> <span m=''3094420''>if</span> <span m=''3094560''>you</span>
  <span m=''3095020''>start</span> <span m=''3095380''>changing</span> <span m=''3095870''>the</span>
  <span m=''3095970''>order</span> <span m=''3097150''>of</span> <span m=''3097370''>the</span>
  <span m=''3097440''>things</span> <span m=''3097720''>in the</span> <span m=''3097830''>ANDs</span>
  <span m=''3098210''>or ORs,</span> <span m=''3099520''>you''ll</span> <span m=''3099650''>find</span>
  <span m=''3099910''>tremendous</span> <span m=''3100380''>differences</span> <span
  m=''3100850''>in</span> <span m=''3100940''>efficiency.</span> <span m=''3102240''>And</span>
  <span m=''3102600''>we</span> <span m=''3102730''>just</span> <span m=''3102910''>saw</span>
  <span m=''3103780''>an</span> <span m=''3103910''>infinitely</span> <span m=''3104750''>big</span>
  <span m=''3104910''>difference</span> <span m=''3105260''>in</span> <span m=''3105360''>efficiency</span>
  <span m=''3105860''>and an</span> <span m=''3105950''>infinite</span> <span m=''3106300''>loop.</span>
  </p><p><span m=''3109190''>And</span> <span m=''3109430''>there are</span> <span
  m=''3109560''>similar</span> <span m=''3109960''>things</span> <span m=''3110570''>having</span>
  <span m=''3110850''>to</span> <span m=''3110950''>do</span> <span m=''3111050''>with</span>
  <span m=''3111180''>the</span> <span m=''3111320''>order</span> <span m=''3112070''>in</span>
  <span m=''3112220''>which</span> <span m=''3112410''>you</span> <span m=''3112500''>enter</span>
  <span m=''3112860''>rules.</span> <span m=''3114070''>The</span> <span m=''3114200''>order</span>
  <span m=''3114520''>in</span> <span m=''3114600''>which</span> <span m=''3114780''>it</span>
  <span m=''3114840''>happens</span> <span m=''3115200''>to</span> <span m=''3115310''>look</span>
  <span m=''3115480''>at</span> <span m=''3115580''>rules</span> <span m=''3115830''>in</span>
  <span m=''3115890''>the</span> <span m=''3115980''>database</span> <span m=''3116810''>may</span>
  <span m=''3117060''>vastly</span> <span m=''3117560''>change</span> <span m=''3117870''>the</span>
  <span m=''3117990''>efficiency</span> <span m=''3118520''>with</span> <span m=''3118660''>which</span>
  <span m=''3118830''>it</span> <span m=''3118910''>gets</span> <span m=''3119140''>out</span>
  <span m=''3119280''>answers</span> <span m=''3119610''>or,</span> <span m=''3119840''>in</span>
  <span m=''3119940''>fact,</span> <span m=''3120490''>send</span> <span m=''3120780''>it</span>
  <span m=''3120850''>into</span> <span m=''3121080''>an</span> <span m=''3121160''>infinite</span>
  <span m=''3121500''>loop</span> <span m=''3121710''>for</span> <span m=''3121860''>some</span>
  <span m=''3122070''>orderings.</span> <span m=''3123840''>And</span> <span m=''3124980''>this</span>
  <span m=''3125190''>whole</span> <span m=''3125390''>thing</span> <span m=''3125580''>has</span>
  <span m=''3125820''>to</span> <span m=''3125920''>do</span> <span m=''3127030''>with</span>
  <span m=''3127570''>the</span> <span m=''3127750''>fact</span> <span m=''3128090''>that</span>
  <span m=''3128220''>you''re</span> <span m=''3128370''>checking</span> <span m=''3128800''>these</span>
  <span m=''3128990''>rules</span> <span m=''3129320''>in</span> <span m=''3129430''>some</span>
  <span m=''3129710''>order.</span> <span m=''3130950''>And</span> <span m=''3131140''>some</span>
  <span m=''3131390''>rules</span> <span m=''3131740''>may</span> <span m=''3131880''>lead</span>
  <span m=''3132120''>to</span> <span m=''3132240''>really</span> <span m=''3132510''>long</span>
  <span m=''3133230''>paths</span> <span m=''3133590''>of</span> <span m=''3133690''>implication.</span>
  <span m=''3135180''>Others</span> <span m=''3135470''>might</span> <span m=''3135690''>not.</span>
  <span m=''3136440''>And</span> <span m=''3136550''>you</span> <span m=''3136670''>don''t</span>
  <span m=''3136820''>know</span> <span m=''3136980''>a</span> <span m=''3137150''>priori</span>
  <span m=''3137560''>which</span> <span m=''3137750''>ones</span> <span m=''3137980''>are</span>
  <span m=''3138070''>good</span> <span m=''3138250''>and</span> <span m=''3138320''>which</span>
  <span m=''3138480''>ones</span> <span m=''3138680''>are</span> <span m=''3138760''>bad.</span>
  </p><p><span m=''3139300''>And</span> <span m=''3139420''>there''s</span> <span
  m=''3139530''>a</span> <span m=''3139590''>whole</span> <span m=''3139850''>bunch</span>
  <span m=''3140100''>of</span> <span m=''3140220''>research</span> <span m=''3140630''>having</span>
  <span m=''3140890''>to</span> <span m=''3140980''>do</span> <span m=''3141140''>with</span>
  <span m=''3141270''>that,</span> <span m=''3142240''>mostly</span> <span m=''3142580''>having</span>
  <span m=''3142830''>to</span> <span m=''3142930''>do</span> <span m=''3143050''>with</span>
  <span m=''3143200''>thinking</span> <span m=''3143510''>about</span> <span m=''3143980''>making</span>
  <span m=''3144310''>parallel</span> <span m=''3144840''>implementations</span> <span
  m=''3145590''>of</span> <span m=''3145690''>logic</span> <span m=''3146030''>programming</span>
  <span m=''3146490''>languages.</span> <span m=''3146970''>And</span> <span m=''3147410''>in</span>
  <span m=''3147520''>some</span> <span m=''3147700''>sense,</span> <span m=''3147940''>what</span>
  <span m=''3148090''>you''d</span> <span m=''3148200''>like</span> <span m=''3148380''>to</span>
  <span m=''3148470''>do</span> <span m=''3148580''>is</span> <span m=''3148680''>check</span>
  <span m=''3148920''>all</span> <span m=''3149100''>rules</span> <span m=''3149330''>in</span>
  <span m=''3149450''>parallel</span> <span m=''3150370''>and</span> <span m=''3150490''>whichever</span>
  <span m=''3150830''>ones</span> <span m=''3151320''>get</span> <span m=''3151570''>answers,</span>
  <span m=''3151870''>you</span> <span m=''3151970''>bubble</span> <span m=''3152250''>them</span>
  <span m=''3152420''>up.</span> <span m=''3152620''>And</span> <span m=''3153080''>if</span>
  <span m=''3153210''>some</span> <span m=''3153430''>go</span> <span m=''3153550''>down</span>
  <span m=''3153790''>infinite</span> <span m=''3154270''>deductive</span> <span m=''3154600''>changed,</span>
  <span m=''3155090''>well,</span> <span m=''3155210''>you</span> <span m=''3155340''>just--</span>
  <span m=''3156290''>you know,</span> <span m=''3156410''>memory</span> <span m=''3156840''>is</span>
  <span m=''3156960''>cheap</span> <span m=''3157260''>and</span> <span m=''3157380''>processors</span>
  <span m=''3157910''>are</span> <span m=''3157980''>cheap,</span> <span m=''3158260''>and
  you</span> <span m=''3158440''>just</span> <span m=''3158960''>let</span> <span
  m=''3159140''>them</span> <span m=''3159300''>buzz for</span> <span m=''3159490''>as</span>
  <span m=''3159610''>for</span> <span m=''3159710''>as</span> <span m=''3159820''>long</span>
  <span m=''3160010''>as</span> <span m=''3160100''>you</span> <span m=''3160220''>want.</span>
  </p><p><span m=''3163510''>There''s</span> <span m=''3163710''>a</span> <span m=''3163760''>deeper</span>
  <span m=''3164080''>problem,</span> <span m=''3164500''>though,</span> <span m=''3165190''>in</span>
  <span m=''3165410''>comparing</span> <span m=''3167500''>this</span> <span m=''3167660''>logic</span>
  <span m=''3168010''>language</span> <span m=''3168360''>to</span> <span m=''3169840''>real</span>
  <span m=''3170050''>logic.</span> <span m=''3170870''>The</span> <span m=''3171090''>example</span>
  <span m=''3171450''>I</span> <span m=''3171520''>just</span> <span m=''3171710''>showed</span>
  <span m=''3171980''>you,</span> <span m=''3172140''>it</span> <span m=''3173010''>went</span>
  <span m=''3173280''>into</span> <span m=''3173500''>an</span> <span m=''3173590''>infinite</span>
  <span m=''3173930''>loop</span> <span m=''3174260''>maybe,</span> <span m=''3175400''>but</span>
  <span m=''3175540''>at</span> <span m=''3175700''>least</span> <span m=''3175850''>it</span>
  <span m=''3175900''>didn''t</span> <span m=''3176090''>give</span> <span m=''3176210''>the</span>
  <span m=''3176290''>wrong</span> <span m=''3176560''>answer.</span> <span m=''3178370''>There''s</span>
  <span m=''3178580''>an</span> <span m=''3178650''>actual</span> <span m=''3180710''>deeper</span>
  <span m=''3181030''>problem</span> <span m=''3182260''>when</span> <span m=''3182400''>we</span>
  <span m=''3182500''>start</span> <span m=''3182980''>comparing,</span> <span m=''3183820''>seriously</span>
  <span m=''3184550''>comparing</span> <span m=''3185640''>this</span> <span m=''3185970''>logic</span>
  <span m=''3186350''>language</span> <span m=''3186720''>with</span> <span m=''3186860''>real</span>
  <span m=''3187460''>classical</span> <span m=''3188150''>logic.</span> <span m=''3189490''>So</span>
  <span m=''3189660''>let''s</span> <span m=''3190000''>sort</span> <span m=''3190180''>of</span>
  <span m=''3190700''>review</span> <span m=''3191180''>real</span> <span m=''3191560''>classical</span>
  <span m=''3192120''>logic.</span> </p><p><span m=''3194030''>All</span> <span m=''3195790''>humans</span>
  <span m=''3198300''>are</span> <span m=''3200680''>mortal.</span> <span m=''3202140''>That''s</span>
  <span m=''3202380''>pretty</span> <span m=''3202590''>classical</span> <span m=''3203050''>logic.</span>
  <span m=''3204390''>Then</span> <span m=''3204570''>maybe</span> <span m=''3204870''>we''ll</span>
  <span m=''3204990''>continue</span> <span m=''3205410''>in</span> <span m=''3205510''>the</span>
  <span m=''3206100''>very</span> <span m=''3206410''>best</span> <span m=''3207550''>classical</span>
  <span m=''3208050''>tradition.</span> <span m=''3209120''>We''ll</span> <span m=''3209240''>say</span>
  <span m=''3209770''>all--</span> <span m=''3211010''>let''s</span> <span m=''3211310''>make</span>
  <span m=''3211490''>it</span> <span m=''3211590''>really</span> <span m=''3211870''>classical.</span>
  <span m=''3212740''>All</span> <span m=''3212990''>Greeks</span> <span m=''3214810''>are</span>
  <span m=''3216650''>human,</span> <span m=''3220590''>which</span> <span m=''3220700''>has</span>
  <span m=''3220980''>the</span> <span m=''3221235''>syllogism</span> <span m=''3221490''>that</span>
  <span m=''3221690''>Socrates</span> <span m=''3224690''>is</span> <span m=''3225360''>a</span>
  <span m=''3225540''>Greek.</span> <span m=''3228060''>And</span> <span m=''3228310''>then</span>
  <span m=''3228560''>what do</span> <span m=''3228700''>you</span> <span m=''3228850''>write</span>
  <span m=''3229060''>here?</span> <span m=''3229210''>I</span> <span m=''3229240''>think</span>
  <span m=''3229430''>three</span> <span m=''3229660''>dots,</span> <span m=''3230960''>classical</span>
  <span m=''3231460''>logic.</span> <span m=''3231890''>Therefore,</span> <span m=''3233370''>then</span>
  <span m=''3233580''>the</span> <span m=''3233650''>syllogism,</span> <span m=''3234660''>Socrates</span>
  <span m=''3238620''>is</span> <span m=''3239010''>mortal.</span> <span m=''3241360''>So
  there''s</span> <span m=''3241770''>some</span> <span m=''3243580''>real</span>
  <span m=''3243800''>honest</span> <span m=''3244180''>classical</span> <span m=''3244610''>logic.</span>
  </p><p><span m=''3245880''>Let''s</span> <span m=''3248040''>compare</span> <span
  m=''3248420''>that</span> <span m=''3249240''>with</span> <span m=''3249480''>our</span>
  <span m=''3249720''>classical</span> <span m=''3250190''>logic</span> <span m=''3250530''>database.</span>
  <span m=''3252570''>So</span> <span m=''3252790''>here''s</span> <span m=''3253000''>a</span>
  <span m=''3253060''>classical</span> <span m=''3253510''>logic</span> <span m=''3253840''>database.</span>
  <span m=''3256270''>Socrates</span> <span m=''3256850''>is</span> <span m=''3256980''>a</span>
  <span m=''3257040''>Greek.</span> <span m=''3258030''>Plato</span> <span m=''3258320''>is</span>
  <span m=''3258410''>a</span> <span m=''3258510''>Greek.</span> <span m=''3259600''>Zeus</span>
  <span m=''3259880''>is</span> <span m=''3260010''>a</span> <span m=''3260070''>Greek,</span>
  <span m=''3260870''>and</span> <span m=''3261120''>Zeus</span> <span m=''3261330''>is</span>
  <span m=''3261440''>a</span> <span m=''3261490''>god.</span> <span m=''3264120''>And</span>
  <span m=''3268700''>all</span> <span m=''3268930''>humans</span> <span m=''3269400''>are</span>
  <span m=''3269560''>mortal.</span> <span m=''3270780''>To</span> <span m=''3270870''>show</span>
  <span m=''3271110''>that</span> <span m=''3271310''>something</span> <span m=''3271740''>is</span>
  <span m=''3271860''>mortal,</span> <span m=''3272230''>it''s</span> <span m=''3272370''>enough</span>
  <span m=''3272570''>to</span> <span m=''3272680''>show</span> <span m=''3272880''>that</span>
  <span m=''3273060''>it''s</span> <span m=''3273230''>human.</span> <span m=''3274650''>All</span>
  <span m=''3274870''>humans</span> <span m=''3275250''>are</span> <span m=''3275350''>fallible.</span>
  <span m=''3278900''>And</span> <span m=''3279500''>all</span> <span m=''3279700''>Greeks</span>
  <span m=''3279960''>are</span> <span m=''3280010''>humans is</span> <span m=''3280360''>not</span>
  <span m=''3280500''>quite</span> <span m=''3280730''>right.</span> <span m=''3280980''>This</span>
  <span m=''3281210''>says</span> <span m=''3281520''>that</span> <span m=''3282520''>all</span>
  <span m=''3282870''>Greeks</span> <span m=''3283190''>who</span> <span m=''3283290''>are</span>
  <span m=''3283370''>not</span> <span m=''3283600''>gods</span> <span m=''3283930''>are</span>
  <span m=''3284000''>human.</span> <span m=''3285920''>So</span> <span m=''3286100''>to</span>
  <span m=''3286150''>show</span> <span m=''3286350''>something''s</span> <span m=''3286750''>human,</span>
  <span m=''3287030''>it''s</span> <span m=''3287160''>enough</span> <span m=''3287350''>to</span>
  <span m=''3287460''>show</span> <span m=''3287620''>it''s</span> <span m=''3287760''>a</span>
  <span m=''3287820''>Greek</span> <span m=''3288070''>and</span> <span m=''3288160''>not</span>
  <span m=''3288330''>a</span> <span m=''3288380''>god.</span> <span m=''3289320''>And</span>
  <span m=''3289660''>the</span> <span m=''3289820''>address</span> <span m=''3291020''>of</span>
  <span m=''3291170''>any</span> <span m=''3291380''>Greek</span> <span m=''3291630''>god</span>
  <span m=''3292020''>is</span> <span m=''3292200''>Mount</span> <span m=''3292410''>Olympus.</span>
  <span m=''3294470''>So</span> <span m=''3294660''>there''s</span> <span m=''3294830''>a</span>
  <span m=''3294870''>little</span> <span m=''3295640''>classical</span> <span m=''3296210''>logic</span>
  <span m=''3296600''>database.</span> <span m=''3297390''>And</span> <span m=''3297540''>indeed,</span>
  <span m=''3297770''>that would</span> <span m=''3297920''>work</span> <span m=''3298700''>fairly</span>
  <span m=''3299000''>well.</span> <span m=''3299490''>If</span> <span m=''3299610''>we</span>
  <span m=''3300310''>type</span> <span m=''3300590''>that</span> <span m=''3300760''>in</span>
  <span m=''3301330''>and</span> <span m=''3301530''>say</span> <span m=''3303550''>is</span>
  <span m=''3303780''>Socrates</span> <span m=''3304430''>mortal</span> <span m=''3304870''>or</span>
  <span m=''3305000''>Socrates</span> <span m=''3305420''>fallible</span> <span m=''3306070''>or</span>
  <span m=''3306190''>mortal?</span> <span m=''3306910''>It''ll</span> <span m=''3307050''>say</span>
  <span m=''3307260''>yes.</span> <span m=''3307690''>Is</span> <span m=''3307800''>Plato</span>
  <span m=''3308740''>mortal</span> <span m=''3309130''>and</span> <span m=''3309240''>fallible.</span>
  <span m=''3309710''>It''ll  say</span> <span m=''3309930''>yes.</span> <span m=''3310680''>If
  we</span> <span m=''3310960''>say</span> <span m=''3311380''>is</span> <span m=''3311600''>Zeus</span>
  <span m=''3311870''>mortal?</span> <span m=''3312210''>It</span> <span m=''3312300''>won''t</span>
  <span m=''3312500''>find</span> <span m=''3312770''>anything.</span> <span m=''3314900''>And</span>
  <span m=''3315000''>it''ll</span> <span m=''3315130''>work</span> <span m=''3315330''>perfectly</span>
  <span m=''3315760''>well.</span> </p><p><span m=''3316640''>However,</span> <span
  m=''3318920''>suppose</span> <span m=''3319230''>we</span> <span m=''3319300''>want</span>
  <span m=''3319420''>to</span> <span m=''3319460''>extend</span> <span m=''3319850''>this.</span>
  <span m=''3320120''>Let''s</span> <span m=''3320300''>define</span> <span m=''3321180''>what</span>
  <span m=''3321340''>it</span> <span m=''3321440''>means</span> <span m=''3321660''>for</span>
  <span m=''3321770''>someone</span> <span m=''3322080''>to</span> <span m=''3322170''>be</span>
  <span m=''3322280''>a</span> <span m=''3322330''>perfect</span> <span m=''3322780''>being.</span>
  <span m=''3325070''>Let''s</span> <span m=''3325230''>say</span> <span m=''3325320''>rule:</span>
  <span m=''3326200''>a</span> <span m=''3326300''>perfect</span> <span m=''3326740''>being.</span>
  <span m=''3334050''>And</span> <span m=''3334170''>I</span> <span m=''3334660''>think</span>
  <span m=''3334920''>this</span> <span m=''3335100''>is</span> <span m=''3335230''>right.</span>
  <span m=''3335480''>If</span> <span m=''3335580''>you''re</span> <span m=''3335730''>up</span>
  <span m=''3335790''>on your</span> <span m=''3336060''>medieval</span> <span m=''3336810''>scholastic</span>
  <span m=''3337540''>philosophy,</span> <span m=''3338450''>I</span> <span m=''3338570''>believe</span>
  <span m=''3338870''>that</span> <span m=''3339030''>perfect</span> <span m=''3339390''>beings</span>
  <span m=''3339750''>are</span> <span m=''3339840''>ones</span> <span m=''3340740''>who</span>
  <span m=''3340880''>were</span> <span m=''3341010''>neither</span> <span m=''3341350''>mortal</span>
  <span m=''3341710''>nor</span> <span m=''3341860''>fallible.</span> <span m=''3344100''>AND</span>
  <span m=''3344720''>NOT</span> <span m=''3347450''>mortal</span> <span m=''3348680''>x,</span>
  <span m=''3351430''>NOT</span> <span m=''3354010''>fallible</span> <span m=''3356550''>x.</span>
  </p><p><span m=''3359300''>So</span> <span m=''3359790''>we''ll</span> <span m=''3359920''>define</span>
  <span m=''3360300''>this</span> <span m=''3360380''>system</span> <span m=''3362230''>to</span>
  <span m=''3362840''>teach</span> <span m=''3363070''>it</span> <span m=''3363150''>what</span>
  <span m=''3363280''>a</span> <span m=''3363340''>perfect</span> <span m=''3363760''>being</span>
  <span m=''3364070''>is.</span> <span m=''3365790''>And</span> <span m=''3365940''>now
  what</span> <span m=''3366090''>we''re</span> <span m=''3366330''>going</span> <span
  m=''3366410''>to</span> <span m=''3366490''>do</span> <span m=''3367130''>is</span>
  <span m=''3367870''>he</span> <span m=''3368180''>ask</span> <span m=''3368380''>for</span>
  <span m=''3368500''>the</span> <span m=''3368620''>address</span> <span m=''3369010''>of</span>
  <span m=''3369110''>all</span> <span m=''3369210''>the</span> <span m=''3369310''>perfect</span>
  <span m=''3369720''>beings.</span> <span m=''3371750''>AND</span> <span m=''3373350''>the</span>
  <span m=''3373750''>address</span> <span m=''3378980''>of</span> <span m=''3379440''>x</span>
  <span m=''3379710''>is</span> <span m=''3379860''>y</span> <span m=''3381270''>and</span>
  <span m=''3381470''>x</span> <span m=''3381710''>is</span> <span m=''3381850''>perfect.</span>
  <span m=''3383680''>And</span> <span m=''3383850''>so what</span> <span m=''3383980''>we''re</span>
  <span m=''3384190''>generating</span> <span m=''3384690''>here is</span> <span m=''3385000''>the</span>
  <span m=''3385080''>world''s</span> <span m=''3386220''>most</span> <span m=''3386590''>exclusive</span>
  <span m=''3387130''>mailing</span> <span m=''3387550''>list.</span> <span m=''3390140''>For</span>
  <span m=''3390630''>the</span> <span m=''3390970''>address</span> <span m=''3391360''>of</span>
  <span m=''3391450''>all</span> <span m=''3391550''>the</span> <span m=''3391660''>perfect</span>
  <span m=''3392050''>things,</span> <span m=''3392280''>we</span> <span m=''3392370''>might</span>
  <span m=''3392530''>have</span> <span m=''3392630''>typed</span> <span m=''3392920''>this</span>
  <span m=''3393160''>in.</span> <span m=''3393830''>Or</span> <span m=''3394410''>we</span>
  <span m=''3394560''>might</span> <span m=''3394760''>type</span> <span m=''3395000''>in</span>
  <span m=''3395160''>this.</span> <span m=''3396240''>We''ll say</span> <span m=''3396430''>AND</span>
  <span m=''3398400''>perfect</span> <span m=''3403760''>of</span> <span m=''3404070''>x</span>
  <span m=''3404980''>and</span> <span m=''3405200''>the</span> <span m=''3405420''>address</span>
  <span m=''3409140''>of x</span> <span m=''3410070''>is</span> <span m=''3410260''>y.</span>
  </p><p><span m=''3412140''>Well,</span> <span m=''3412260''>suppose</span> <span
  m=''3412460''>we</span> <span m=''3412540''>type</span> <span m=''3412820''>all</span>
  <span m=''3412960''>that</span> <span m=''3413130''>in</span> <span m=''3413560''>and</span>
  <span m=''3413830''>we</span> <span m=''3414020''>try</span> <span m=''3414290''>this</span>
  <span m=''3414360''>query.</span> <span m=''3415190''>This</span> <span m=''3415480''>query</span>
  <span m=''3415770''>is</span> <span m=''3415880''>going</span> <span m=''3415950''>to</span>
  <span m=''3416010''>give</span> <span m=''3416180''>us</span> <span m=''3416300''>an</span>
  <span m=''3416380''>answer.</span> <span m=''3417650''>This</span> <span m=''3417860''>query</span>
  <span m=''3418170''>will</span> <span m=''3418310''>say,</span> <span m=''3418900''>yeah,</span>
  <span m=''3419050''>Mount</span> <span m=''3419440''>Olympus.</span> <span m=''3424230''>This</span>
  <span m=''3424730''>query,</span> <span m=''3425120''>in</span> <span m=''3425250''>fact,</span>
  <span m=''3425580''>is</span> <span m=''3425670''>going</span> <span m=''3425740''>to</span>
  <span m=''3425810''>give</span> <span m=''3426010''>us</span> <span m=''3426160''>nothing.</span>
  <span m=''3426740''>It</span> <span m=''3427010''>will</span> <span m=''3427180''>say</span>
  <span m=''3427920''>no</span> <span m=''3428190''>addresses</span> <span m=''3428680''>of</span>
  <span m=''3428750''>perfect</span> <span m=''3429020''>beings.</span> </p><p><span
  m=''3431640''>Now,</span> <span m=''3431790''>why</span> <span m=''3432010''>is</span>
  <span m=''3432210''>that?</span> <span m=''3432510''>Why</span> <span m=''3432770''>is</span>
  <span m=''3432840''>there</span> <span m=''3432950''>a</span> <span m=''3433000''>difference?</span>
  <span m=''3434230''>This</span> <span m=''3434410''>is</span> <span m=''3434530''>not</span>
  <span m=''3434680''>an</span> <span m=''3434770''>infinite</span> <span m=''3435130''>loop</span>
  <span m=''3435300''>question.</span> <span m=''3435690''>This</span> <span m=''3435820''>is</span>
  <span m=''3435940''>a</span> <span m=''3436010''>different</span> <span m=''3436300''>answer</span>
  <span m=''3436610''>question.</span> <span m=''3439145''>The</span> <span m=''3439580''>reason</span>
  <span m=''3439910''>is</span> <span m=''3440220''>that</span> <span m=''3440600''>if</span>
  <span m=''3440690''>you</span> <span m=''3440730''>remember</span> <span m=''3440940''>the</span>
  <span m=''3441030''>implementation</span> <span m=''3441690''>of</span> <span m=''3441790''>NOT,</span>
  <span m=''3443580''>NOT</span> <span m=''3443860''>acted</span> <span m=''3444210''>as</span>
  <span m=''3444330''>a</span> <span m=''3444390''>filter.</span> <span m=''3445880''>NOT</span>
  <span m=''3446170''>said</span> <span m=''3446620''>I''m</span> <span m=''3446800''>going</span>
  <span m=''3446880''>to</span> <span m=''3446950''>take</span> <span m=''3447450''>some</span>
  <span m=''3447740''>possible</span> <span m=''3448360''>dictionaries,</span> <span
  m=''3449040''>some</span> <span m=''3449250''>possible</span> <span m=''3449660''>frames,</span>
  <span m=''3450470''>some</span> <span m=''3450630''>possible</span> <span m=''3451080''>answers,</span>
  <span m=''3451900''>and</span> <span m=''3452090''>filter</span> <span m=''3452480''>out</span>
  <span m=''3452650''>the</span> <span m=''3452730''>ones</span> <span m=''3453280''>that</span>
  <span m=''3453500''>happened</span> <span m=''3453800''>to</span> <span m=''3453870''>satisfy</span>
  <span m=''3454340''>some</span> <span m=''3454540''>condition,</span> <span m=''3454940''>and</span>
  <span m=''3455070''>that''s</span> <span m=''3455190''>how</span> <span m=''3455300''>I</span>
  <span m=''3455380''>implement</span> <span m=''3455790''>NOT.</span> <span m=''3456520''>If</span>
  <span m=''3456920''>you</span> <span m=''3457150''>think</span> <span m=''3457320''>about</span>
  <span m=''3457520''>what''s</span> <span m=''3457710''>going</span> <span m=''3457960''>on</span>
  <span m=''3458190''>here,</span> <span m=''3460170''>I''ll</span> <span m=''3460340''>build</span>
  <span m=''3460560''>this</span> <span m=''3460730''>query</span> <span m=''3461040''>box</span>
  <span m=''3461400''>where</span> <span m=''3463370''>the</span> <span m=''3463530''>output</span>
  <span m=''3463830''>of</span> <span m=''3463890''>an</span> <span m=''3463980''>address</span>
  <span m=''3464430''>piece</span> <span m=''3464680''>gets</span> <span m=''3464920''>fed</span>
  <span m=''3465090''>into</span> <span m=''3466470''>a</span> <span m=''3466530''>perfect</span>
  <span m=''3466960''>piece.</span> <span m=''3470290''>What</span> <span m=''3470420''>will</span>
  <span m=''3470510''>happen</span> <span m=''3470880''>is</span> <span m=''3471390''>the</span>
  <span m=''3471560''>address</span> <span m=''3471950''>piece</span> <span m=''3472180''>will</span>
  <span m=''3472260''>set</span> <span m=''3472500''>up</span> <span m=''3472630''>some</span>
  <span m=''3472880''>things</span> <span m=''3473170''>of</span> <span m=''3473360''>everyone</span>
  <span m=''3473740''>whose</span> <span m=''3473920''>address</span> <span m=''3474350''>I</span>
  <span m=''3474440''>know.</span> <span m=''3475290''>Those</span> <span m=''3475490''>will</span>
  <span m=''3475550''>get</span> <span m=''3475760''>filtered</span> <span m=''3476140''>by</span>
  <span m=''3476270''>the</span> <span m=''3476390''>NOTs</span> <span m=''3476770''>inside</span>
  <span m=''3477210''>perfect</span> <span m=''3477620''>here.</span> <span m=''3479880''>So</span>
  <span m=''3480100''>it will throw out</span> <span m=''3480480''>the</span> <span
  m=''3480560''>ones</span> <span m=''3480820''>which</span> <span m=''3482460''>happened</span>
  <span m=''3482780''>to</span> <span m=''3482850''>be</span> <span m=''3482980''>either</span>
  <span m=''3483230''>mortal</span> <span m=''3483440''>or</span> <span m=''3483620''>fallible.</span>
  </p><p><span m=''3484910''>In</span> <span m=''3485010''>the</span> <span m=''3485160''>other</span>
  <span m=''3485470''>order</span> <span m=''3485750''>what</span> <span m=''3485900''>happens</span>
  <span m=''3486850''>is</span> <span m=''3487050''>I</span> <span m=''3487140''>set</span>
  <span m=''3487390''>this</span> <span m=''3487590''>up,</span> <span m=''3487700''>started</span>
  <span m=''3488040''>up</span> <span m=''3488150''>with</span> <span m=''3488260''>an</span>
  <span m=''3488360''>empty</span> <span m=''3488630''>frame.</span> <span m=''3489520''>The</span>
  <span m=''3489790''>perfect</span> <span m=''3490200''>in</span> <span m=''3490280''>here</span>
  <span m=''3490470''>doesn''t</span> <span m=''3490770''>find</span> <span m=''3491020''>anything</span>
  <span m=''3491370''>for</span> <span m=''3491510''>the</span> <span m=''3491610''>NOTs</span>
  <span m=''3491900''>to</span> <span m=''3492000''>filter,</span> <span m=''3492350''>so</span>
  <span m=''3492470''>nothing</span> <span m=''3492890''>comes</span> <span m=''3493170''>out</span>
  <span m=''3493390''>here</span> <span m=''3493570''>at</span> <span m=''3493740''>all.</span>
  <span m=''3498830''>And</span> <span m=''3499280''>there''s</span> <span m=''3499460''>sort</span>
  <span m=''3499560''>of</span> <span m=''3499660''>nothing</span> <span m=''3500000''>there</span>
  <span m=''3500160''>that</span> <span m=''3500310''>gets</span> <span m=''3500490''>fed</span>
  <span m=''3500640''>into</span> <span m=''3500810''>the</span> <span m=''3500940''>address</span>
  <span m=''3501370''>thing.</span> <span m=''3501940''>So</span> <span m=''3502130''>here,</span>
  <span m=''3502260''>I</span> <span m=''3502320''>don''t</span> <span m=''3502620''>get</span>
  <span m=''3502770''>an</span> <span m=''3502870''>answer.</span> <span m=''3504260''>And</span>
  <span m=''3504430''>again,</span> <span m=''3504640''>the</span> <span m=''3504730''>reason</span>
  <span m=''3505010''>for</span> <span m=''3505110''>that</span> <span m=''3505240''>is</span>
  <span m=''3505360''>NOT</span> <span m=''3505620''>isn''t</span> <span m=''3506120''>generating</span>
  <span m=''3506660''>anything.</span> <span m=''3507440''>NOT''s</span> <span m=''3507680''>only</span>
  <span m=''3507870''>throwing</span> <span m=''3508250''>out</span> <span m=''3508440''>things.</span>
  <span m=''3508800''>And</span> <span m=''3509290''>if</span> <span m=''3509430''>I</span>
  <span m=''3509480''>never</span> <span m=''3509710''>started</span> <span m=''3510010''>up</span>
  <span m=''3510130''>with</span> <span m=''3510260''>anything,</span> <span m=''3510520''>there''s</span>
  <span m=''3510680''>nothing</span> <span m=''3510990''>for</span> <span m=''3511160''>it
  to</span> <span m=''3511270''>throw</span> <span m=''3511510''>out.</span> <span
  m=''3512020''>So</span> <span m=''3512190''>out</span> <span m=''3512350''>of</span>
  <span m=''3512470''>this</span> <span m=''3512620''>thing,</span> <span m=''3512750''>I</span>
  <span m=''3512830''>get</span> <span m=''3513020''>the</span> <span m=''3513110''>wrong</span>
  <span m=''3513390''>answer.</span> </p><p><span m=''3517200''>How</span> <span m=''3517350''>can</span>
  <span m=''3517480''>you</span> <span m=''3517580''>fix</span> <span m=''3517830''>that?</span>
  <span m=''3517970''>Well, there</span> <span m=''3518030''>are</span> <span m=''3518160''>ways</span>
  <span m=''3518400''>to</span> <span m=''3518500''>fix</span> <span m=''3518770''>that.</span>
  <span m=''3519070''>So</span> <span m=''3519420''>you</span> <span m=''3519610''>might</span>
  <span m=''3519800''>say,</span> <span m=''3519890''>well,</span> <span m=''3520140''>that''s</span>
  <span m=''3520180''>sort</span> <span m=''3520360''>of</span> <span m=''3520400''>stupid.</span>
  <span m=''3521410''>Why</span> <span m=''3522410''>are</span> <span m=''3522600''>you</span>
  <span m=''3522730''>just</span> <span m=''3522940''>doing</span> <span m=''3523130''>all</span>
  <span m=''3523280''>your</span> <span m=''3523390''>NOT</span> <span m=''3523700''>stuff</span>
  <span m=''3523980''>at</span> <span m=''3524400''>the</span> <span m=''3524510''>beginning?</span>
  <span m=''3524900''>The</span> <span m=''3525000''>right</span> <span m=''3525260''>way</span>
  <span m=''3525350''>to</span> <span m=''3525440''>implement</span> <span m=''3525860''>NOT</span>
  <span m=''3526490''>is</span> <span m=''3526640''>to</span> <span m=''3526800''>realize</span>
  <span m=''3527560''>that</span> <span m=''3528000''>when</span> <span m=''3528100''>you</span>
  <span m=''3528220''>have</span> <span m=''3528340''>conditions</span> <span m=''3528860''>like</span>
  <span m=''3529680''>NOT,</span> <span m=''3530210''>you</span> <span m=''3530460''>should</span>
  <span m=''3530640''>generate</span> <span m=''3531050''>all</span> <span m=''3531190''>your</span>
  <span m=''3531360''>answers</span> <span m=''3531720''>first,</span> <span m=''3532830''>and</span>
  <span m=''3533010''>then</span> <span m=''3533100''>with</span> <span m=''3533240''>each</span>
  <span m=''3533410''>of</span> <span m=''3533510''>these</span> <span m=''3533620''>dictionaries</span>
  <span m=''3534140''>pass</span> <span m=''3534480''>along</span> <span m=''3535500''>until</span>
  <span m=''3535770''>at</span> <span m=''3535860''>the</span> <span m=''3535950''>very</span>
  <span m=''3536270''>end</span> <span m=''3536980''>I''ll</span> <span m=''3537150''>do</span>
  <span m=''3537280''>filtering.</span> <span m=''3538560''>And</span> <span m=''3538710''>there</span>
  <span m=''3538830''>are</span> <span m=''3539550''>implementations</span> <span
  m=''3540260''>of</span> <span m=''3540370''>logic</span> <span m=''3540710''>languages</span>
  <span m=''3541190''>that</span> <span m=''3541330''>work</span> <span m=''3541560''>like</span>
  <span m=''3541770''>that</span> <span m=''3542120''>that</span> <span m=''3542710''>solve</span>
  <span m=''3542890''>this</span> <span m=''3543110''>particular</span> <span m=''3543590''>problem.</span>
  </p><p><span m=''3546660''>However,</span> <span m=''3547100''>there''s</span> <span
  m=''3547270''>a</span> <span m=''3547310''>more</span> <span m=''3547490''>profound</span>
  <span m=''3548350''>problem,</span> <span m=''3549550''>which</span> <span m=''3549850''>is</span>
  <span m=''3550030''>which</span> <span m=''3550300''>one</span> <span m=''3550430''>of</span>
  <span m=''3550540''>these</span> <span m=''3550650''>is</span> <span m=''3550750''>the</span>
  <span m=''3550840''>right</span> <span m=''3551050''>answer?</span> <span m=''3552530''>Is</span>
  <span m=''3552700''>it</span> <span m=''3552870''>Mount Olympus</span> <span m=''3553250''>or
  is</span> <span m=''3553505''>it</span> <span m=''3553760''>nothing?</span> <span
  m=''3555320''>So</span> <span m=''3555490''>you</span> <span m=''3555600''>might</span>
  <span m=''3555840''>say</span> <span m=''3557990''>it''s</span> <span m=''3558120''>Mount</span>
  <span m=''3558340''>Olympus,</span> <span m=''3558790''>because</span> <span m=''3559100''>after
  all,</span> <span m=''3559420''>Zeus</span> <span m=''3559740''>is</span> <span
  m=''3559860''>in</span> <span m=''3559990''>that</span> <span m=''3560180''>database,</span>
  <span m=''3562610''>and</span> <span m=''3562860''>Zeus</span> <span m=''3563060''>was</span>
  <span m=''3563220''>neither</span> <span m=''3563480''>mortal</span> <span m=''3564370''>nor</span>
  <span m=''3564520''>fallible.</span> <span m=''3569550''>So</span> <span m=''3569790''>you</span>
  <span m=''3569930''>might say</span> <span m=''3570370''>Zeus</span> <span m=''3571190''>wants</span>
  <span m=''3571590''>to</span> <span m=''3571690''>satisfy</span> <span m=''3574390''>NOT</span>
  <span m=''3578080''>mortal</span> <span m=''3580070''>Zeus</span> <span m=''3582520''>or</span>
  <span m=''3582960''>NOT</span> <span m=''3583310''>fallible</span> <span m=''3583840''>Zeus.</span>
  <span m=''3584120''>But</span> <span m=''3584290''>let''s</span> <span m=''3584470''>actually</span>
  <span m=''3584830''>look</span> <span m=''3585020''>at</span> <span m=''3585120''>that</span>
  <span m=''3585300''>database.</span> <span m=''3587638''>Let''s</span> <span m=''3588080''>look</span>
  <span m=''3588230''>at</span> <span m=''3588340''>it.</span> </p><p><span m=''3589320''>There''s</span>
  <span m=''3589600''>no</span> <span m=''3589800''>way--</span> <span m=''3591275''>how</span>
  <span m=''3591660''>does</span> <span m=''3591780''>it</span> <span m=''3591900''>know</span>
  <span m=''3592030''>that</span> <span m=''3592200''>Zeus</span> <span m=''3592450''>is</span>
  <span m=''3592570''>not</span> <span m=''3592770''>fallible?</span> <span m=''3594810''>There''s</span>
  <span m=''3594970''>nothing</span> <span m=''3595240''>in</span> <span m=''3595440''>there</span>
  <span m=''3595600''>about</span> <span m=''3595860''>that.</span> <span m=''3597930''>What''s</span>
  <span m=''3598140''>in</span> <span m=''3598240''>there</span> <span m=''3598440''>is</span>
  <span m=''3598570''>that</span> <span m=''3598690''>humans</span> <span m=''3599070''>are</span>
  <span m=''3599150''>fallible.</span> <span m=''3602390''>How</span> <span m=''3602510''>does</span>
  <span m=''3602660''>it</span> <span m=''3602770''>know</span> <span m=''3602920''>that</span>
  <span m=''3603110''>Zeus</span> <span m=''3603350''>is</span> <span m=''3603470''>not</span>
  <span m=''3603700''>mortal?</span> <span m=''3604430''>There''s</span> <span m=''3604770''>nothing</span>
  <span m=''3605060''>in</span> <span m=''3605170''>there</span> <span m=''3605320''>about</span>
  <span m=''3605560''>that.</span> <span m=''3607980''>It</span> <span m=''3608120''>just</span>
  <span m=''3609240''>said</span> <span m=''3609460''>I</span> <span m=''3609540''>don''t</span>
  <span m=''3609710''>have</span> <span m=''3609850''>any</span> <span m=''3610040''>rule,</span>
  <span m=''3610650''>which--</span> <span m=''3612000''>the</span> <span m=''3612080''>only</span>
  <span m=''3612220''>way I</span> <span m=''3612510''>can</span> <span m=''3612610''>deduce</span>
  <span m=''3612730''>something''s</span> <span m=''3613120''>mortal</span> <span
  m=''3613460''>is</span> <span m=''3613560''>if</span> <span m=''3613680''>it''s</span>
  <span m=''3613820''>human,</span> <span m=''3614170''>and</span> <span m=''3614300''>that''s</span>
  <span m=''3614430''>all it</span> <span m=''3614650''>really</span> <span m=''3614870''>knows</span>
  <span m=''3615080''>about</span> <span m=''3615340''>mortal.</span> <span m=''3616690''>And</span>
  <span m=''3616820''>in</span> <span m=''3616880''>fact,</span> <span m=''3617070''>if</span>
  <span m=''3617150''>you</span> <span m=''3617210''>remember</span> <span m=''3617500''>your</span>
  <span m=''3618990''>classical</span> <span m=''3619450''>mythology,</span> <span
  m=''3619755''>you</span> <span m=''3620060''>know</span> <span m=''3620190''>that</span>
  <span m=''3620360''>the</span> <span m=''3620440''>Greek</span> <span m=''3620690''>gods</span>
  <span m=''3620980''>were</span> <span m=''3621990''>not</span> <span m=''3622310''>mortal</span>
  <span m=''3622630''>but</span> <span m=''3622950''>fallible.</span> <span m=''3625300''>So</span>
  <span m=''3625570''>the</span> <span m=''3625750''>answer</span> <span m=''3626020''>is</span>
  <span m=''3627270''>not</span> <span m=''3627660''>in</span> <span m=''3627800''>the</span>
  <span m=''3627920''>rules</span> <span m=''3628230''>there.</span> </p><p><span
  m=''3630850''>See,</span> <span m=''3631010''>why</span> <span m=''3631200''>does</span>
  <span m=''3631290''>it</span> <span m=''3631390''>deduce</span> <span m=''3631790''>that?</span>
  <span m=''3634710''>See,</span> <span m=''3634910''>Socrates</span> <span m=''3636370''>would</span>
  <span m=''3636510''>certainly</span> <span m=''3636840''>not</span> <span m=''3637030''>have
  made</span> <span m=''3637330''>this</span> <span m=''3637460''>error</span> <span
  m=''3637755''>of</span> <span m=''3638050''>logic.</span> <span m=''3640080''>What</span>
  <span m=''3640290''>NOT</span> <span m=''3640530''>needs in</span> <span m=''3640720''>this</span>
  <span m=''3640940''>language</span> <span m=''3641320''>is</span> <span m=''3641850''>not</span>
  <span m=''3642290''>NOT.</span> <span m=''3643370''>It''s</span> <span m=''3643490''>not</span>
  <span m=''3643650''>the</span> <span m=''3643730''>NOT</span> <span m=''3643930''>of</span>
  <span m=''3644030''>logic.</span> <span m=''3644930''>What NOT</span> <span m=''3645330''>needs</span>
  <span m=''3645530''>in</span> <span m=''3645620''>this</span> <span m=''3645780''>language</span>
  <span m=''3646180''>is</span> <span m=''3647240''>not</span> <span m=''3647840''>deducible</span>
  <span m=''3648710''>from</span> <span m=''3648950''>things</span> <span m=''3649220''>in</span>
  <span m=''3649300''>the</span> <span m=''3649390''>database</span> <span m=''3650810''>as</span>
  <span m=''3651000''>opposed</span> <span m=''3651570''>to</span> <span m=''3652230''>not</span>
  <span m=''3652930''>true.</span> <span m=''3655140''>That''s a</span> <span m=''3655370''>very</span>
  <span m=''3655640''>big</span> <span m=''3655860''>difference.</span> <span m=''3657300''>Subtle,</span>
  <span m=''3658180''>but</span> <span m=''3658380''>big.</span> </p><p><span m=''3659250''>So,</span>
  <span m=''3659700''>in</span> <span m=''3659850''>fact,</span> <span m=''3660790''>this</span>
  <span m=''3661030''>is</span> <span m=''3661160''>perfectly</span> <span m=''3661590''>happy</span>
  <span m=''3661920''>to</span> <span m=''3662010''>say</span> <span m=''3662250''>not</span>
  <span m=''3662590''>anything</span> <span m=''3662960''>that</span> <span m=''3663080''>it</span>
  <span m=''3663180''>doesn''t</span> <span m=''3663450''>know</span> <span m=''3663600''>about.</span>
  <span m=''3664610''>So</span> <span m=''3664790''>if</span> <span m=''3664860''>you</span>
  <span m=''3665000''>ask</span> <span m=''3665280''>it</span> <span m=''3665410''>is</span>
  <span m=''3665540''>it</span> <span m=''3665650''>not</span> <span m=''3665880''>true</span>
  <span m=''3666120''>that</span> <span m=''3666340''>Zeus</span> <span m=''3666660''>likes</span>
  <span m=''3666900''>chocolate</span> <span m=''3667370''>ice</span> <span m=''3667610''>cream?</span>
  <span m=''3667830''>It will</span> <span m=''3667940''>say</span> <span m=''3668120''>sure,</span>
  <span m=''3668390''>it''s</span> <span m=''3668540''>not</span> <span m=''3668750''>true.</span>
  <span m=''3670251''>Or</span> <span m=''3670700''>anything</span> <span m=''3671130''>else
  or</span> <span m=''3671370''>anything</span> <span m=''3671700''>it</span> <span
  m=''3671800''>doesn''t</span> <span m=''3672070''>know</span> <span m=''3672250''>about.</span>
  <span m=''3672850''>NOT</span> <span m=''3673080''>means</span> <span m=''3674260''>not</span>
  <span m=''3674920''>deducible</span> <span m=''3675740''>from</span> <span m=''3676080''>the</span>
  <span m=''3676280''>things</span> <span m=''3676690''>you''ve</span> <span m=''3676850''>told</span>
  <span m=''3677140''>me.</span> <span m=''3678280''>In</span> <span m=''3678450''>a</span>
  <span m=''3678510''>world</span> <span m=''3679090''>where</span> <span m=''3679430''>you''re</span>
  <span m=''3679640''>identifying</span> <span m=''3681030''>not</span> <span m=''3681630''>deducible</span>
  <span m=''3682760''>with,</span> <span m=''3682920''>in</span> <span m=''3683020''>fact,</span>
  <span m=''3683480''>not</span> <span m=''3683710''>true,</span> <span m=''3684540''>this</span>
  <span m=''3684650''>is</span> <span m=''3684750''>called</span> <span m=''3684930''>the</span>
  <span m=''3685000''>closed</span> <span m=''3685530''>world</span> <span m=''3685800''>assumption.</span>
  </p><p><span m=''3696870''>The</span> <span m=''3697270''>closed</span> <span m=''3697720''>world</span>
  <span m=''3697930''>assumption.</span> <span m=''3698320''>Anything</span> <span
  m=''3699270''>that</span> <span m=''3699510''>I</span> <span m=''3699620''>cannot</span>
  <span m=''3700260''>deduce</span> <span m=''3700830''>from</span> <span m=''3701240''>what</span>
  <span m=''3701780''>I</span> <span m=''3701920''>know</span> <span m=''3703550''>is</span>
  <span m=''3703730''>not</span> <span m=''3703980''>true,</span> <span m=''3706340''>right?</span>
  <span m=''3706500''>If</span> <span m=''3706610''>I</span> <span m=''3706690''>don''t</span>
  <span m=''3707000''>know</span> <span m=''3707150''>anything</span> <span m=''3707510''>about</span>
  <span m=''3707770''>x,</span> <span m=''3708220''>the</span> <span m=''3708440''>x</span>
  <span m=''3708660''>isn''t</span> <span m=''3708920''>true.</span> <span m=''3709290''>That''s</span>
  <span m=''3709590''>very</span> <span m=''3709820''>dangerous.</span> <span m=''3711420''>From</span>
  <span m=''3711510''>a</span> <span m=''3711610''>logical</span> <span m=''3712030''>point</span>
  <span m=''3712250''>of</span> <span m=''3712320''>view,</span> <span m=''3712440''>first</span>
  <span m=''3712650''>of all, it</span> <span m=''3712770''>doesn''t</span> <span
  m=''3712860''>really</span> <span m=''3713140''>makes</span> <span m=''3713380''>sense.</span>
  <span m=''3714480''>Because</span> <span m=''3714730''>if</span> <span m=''3714810''>I</span>
  <span m=''3715000''>don''t</span> <span m=''3715200''>know</span> <span m=''3715390''>anything</span>
  <span m=''3715740''>about</span> <span m=''3715980''>x,</span> <span m=''3718460''>I''m</span>
  <span m=''3718610''>willing</span> <span m=''3718860''>to</span> <span m=''3718920''>say</span>
  <span m=''3719110''>not</span> <span m=''3719390''>x.</span> <span m=''3720240''>But</span>
  <span m=''3721030''>am</span> <span m=''3721500''>I</span> <span m=''3721660''>willing</span>
  <span m=''3721890''>to</span> <span m=''3721950''>say</span> <span m=''3722130''>not</span>
  <span m=''3722740''>not</span> <span m=''3722970''>x?</span> <span m=''3723850''>Well,</span>
  <span m=''3723980''>sure,</span> <span m=''3724190''>I</span> <span m=''3724230''>don''t</span>
  <span m=''3724350''>know anything</span> <span m=''3724500''>about</span> <span
  m=''3724710''>that</span> <span m=''3724860''>either</span> <span m=''3725260''>maybe.</span>
  <span m=''3726470''>So</span> <span m=''3726660''>not</span> <span m=''3726910''>not</span>
  <span m=''3727100''>x</span> <span m=''3727270''>is</span> <span m=''3727370''>not</span>
  <span m=''3727540''>necessarily</span> <span m=''3727820''>the</span> <span m=''3727900''>same</span>
  <span m=''3728130''>as</span> <span m=''3728230''>x</span> <span m=''3729270''>and</span>
  <span m=''3729450''>so</span> <span m=''3729640''>on</span> <span m=''3729800''>and</span>
  <span m=''3729930''>so</span> <span m=''3730060''>on</span> <span m=''3730200''>and</span>
  <span m=''3730340''>so</span> <span m=''3730470''>on,</span> <span m=''3730620''>so</span>
  <span m=''3731670''>there''s</span> <span m=''3732510''>some</span> <span m=''3732630''>sort
  of</span> <span m=''3732980''>funny</span> <span m=''3733120''>bias</span> <span
  m=''3733550''>in</span> <span m=''3733650''>there.</span> <span m=''3735970''>So</span>
  <span m=''3736070''>that''s</span> <span m=''3736610''>sort</span> <span m=''3736800''>of</span>
  <span m=''3736880''>funny.</span> </p><p><span m=''3737290''>The</span> <span m=''3737480''>second</span>
  <span m=''3737810''>thing,</span> <span m=''3740200''>if</span> <span m=''3740330''>you</span>
  <span m=''3740410''>start</span> <span m=''3740680''>building</span> <span m=''3740990''>up</span>
  <span m=''3741620''>real</span> <span m=''3742330''>reasoning</span> <span m=''3742840''>programs</span>
  <span m=''3743380''>based</span> <span m=''3743690''>on</span> <span m=''3743850''>this,</span>
  <span m=''3744950''>think</span> <span m=''3745110''>how</span> <span m=''3745220''>dangerous</span>
  <span m=''3745730''>that</span> <span m=''3745910''>is.</span> <span m=''3747210''>You''re</span>
  <span m=''3747360''>saying I know</span> <span m=''3751130''>I''m</span> <span m=''3751290''>in</span>
  <span m=''3751360''>a</span> <span m=''3751410''>position</span> <span m=''3752060''>to</span>
  <span m=''3752330''>deduce</span> <span m=''3752720''>everything</span> <span m=''3753420''>true</span>
  <span m=''3754100''>that''s</span> <span m=''3754450''>relevant</span> <span m=''3754930''>to</span>
  <span m=''3755220''>this</span> <span m=''3755610''>problem.</span> <span m=''3757780''>I''m</span>
  <span m=''3757910''>reasoning,</span> <span m=''3758900''>and</span> <span m=''3759110''>built</span>
  <span m=''3759370''>into</span> <span m=''3759550''>my</span> <span m=''3759700''>reasoning</span>
  <span m=''3760100''>mechanism</span> <span m=''3761320''>is</span> <span m=''3761480''>the</span>
  <span m=''3761590''>assumption</span> <span m=''3762400''>that</span> <span m=''3762670''>anything</span>
  <span m=''3763200''>that</span> <span m=''3763360''>I</span> <span m=''3763570''>don''t</span>
  <span m=''3763890''>know</span> <span m=''3764170''>can''t</span> <span m=''3764480''>possibly</span>
  <span m=''3765020''>be</span> <span m=''3765160''>relevant</span> <span m=''3765570''>to</span>
  <span m=''3765650''>this</span> <span m=''3765840''>problem,</span> <span m=''3768560''>right?</span>
  </p><p><span m=''3768860''>There are a</span> <span m=''3768900''>lot</span> <span
  m=''3769100''>of</span> <span m=''3769180''>big</span> <span m=''3771100''>organizations</span>
  <span m=''3771790''>that</span> <span m=''3771930''>work</span> <span m=''3772160''>like</span>
  <span m=''3772350''>that,</span> <span m=''3772430''>right?</span> <span m=''3774720''>Most</span>
  <span m=''3775010''>corporate</span> <span m=''3775320''>marketing</span> <span
  m=''3775730''>divisions</span> <span m=''3776130''>work</span> <span m=''3776360''>like</span>
  <span m=''3776550''>that.</span> <span m=''3776830''>You</span> <span m=''3776950''>know</span>
  <span m=''3777990''>the</span> <span m=''3778100''>consequences</span> <span m=''3778460''>to</span>
  <span m=''3778820''>that.</span> <span m=''3780560''>So</span> <span m=''3780700''>it''s</span>
  <span m=''3780870''>very</span> <span m=''3781150''>dangerous</span> <span m=''3781780''>to</span>
  <span m=''3782450''>start</span> <span m=''3782800''>really</span> <span m=''3783790''>typing</span>
  <span m=''3784180''>in</span> <span m=''3784290''>these</span> <span m=''3784490''>big</span>
  <span m=''3784720''>logical</span> <span m=''3785150''>implication</span> <span
  m=''3785680''>systems</span> <span m=''3787100''>and</span> <span m=''3787970''>going</span>
  <span m=''3788270''>on</span> <span m=''3788430''>what</span> <span m=''3788610''>they</span>
  <span m=''3788750''>say,</span> <span m=''3789000''>because</span> <span m=''3789180''>they</span>
  <span m=''3789330''>have</span> <span m=''3789480''>this</span> <span m=''3789760''>really</span>
  <span m=''3790080''>limiting</span> <span m=''3790500''>assumption</span> <span
  m=''3790940''>built in.</span> <span m=''3792600''>So</span> <span m=''3792690''>you
  have</span> <span m=''3792860''>to be</span> <span m=''3793110''>very,</span> <span
  m=''3793430''>very</span> <span m=''3793630''>careful</span> <span m=''3793930''>about</span>
  <span m=''3794190''>that.</span> <span m=''3794905''>And</span> <span m=''3795380''>that''s</span>
  <span m=''3795680''>a</span> <span m=''3795740''>deep</span> <span m=''3795980''>problem.</span>
  <span m=''3796560''>That''s</span> <span m=''3796840''>not</span> <span m=''3796980''>a</span>
  <span m=''3797030''>problem</span> <span m=''3797430''>about</span> <span m=''3798210''>we</span>
  <span m=''3798390''>can</span> <span m=''3798530''>make</span> <span m=''3798710''>a</span>
  <span m=''3798770''>little</span> <span m=''3798990''>bit</span> <span m=''3799150''>cleverer</span>
  <span m=''3799570''>implementation</span> <span m=''3800280''>and</span> <span m=''3800370''>do</span>
  <span m=''3800480''>the</span> <span m=''3800590''>filters</span> <span m=''3801050''>and</span>
  <span m=''3801140''>organize</span> <span m=''3801620''>the</span> <span m=''3802360''>infinite</span>
  <span m=''3802710''>loops</span> <span m=''3802940''>to</span> <span m=''3803030''>make</span>
  <span m=''3803220''>them</span> <span m=''3803360''>go</span> <span m=''3803520''>away.</span>
  <span m=''3803840''>It''s</span> <span m=''3803970''>a</span> <span m=''3804010''>different</span>
  <span m=''3804310''>kind</span> <span m=''3804470''>of</span> <span m=''3804640''>problem.</span>
  <span m=''3805920''>It''s a</span> <span m=''3806060''>different</span> <span m=''3806340''>semantics.</span>
  </p><p><span m=''3807060''>So</span> <span m=''3808300''>I</span> <span m=''3808420''>think</span>
  <span m=''3808990''>to</span> <span m=''3809100''>wrap</span> <span m=''3809310''>this</span>
  <span m=''3809490''>up,</span> <span m=''3809770''>it''s</span> <span m=''3809970''>fair</span>
  <span m=''3810140''>to</span> <span m=''3810200''>say</span> <span m=''3811020''>that</span>
  <span m=''3811580''>logic</span> <span m=''3811910''>programming</span> <span m=''3812340''>I</span>
  <span m=''3812450''>think</span> <span m=''3812570''>is</span> <span m=''3812990''>a</span>
  <span m=''3813060''>terrifically</span> <span m=''3813660''>exciting</span> <span
  m=''3814080''>idea,</span> <span m=''3814650''>the</span> <span m=''3814880''>idea</span>
  <span m=''3815190''>that</span> <span m=''3815350''>you</span> <span m=''3816370''>can</span>
  <span m=''3816520''>bridge</span> <span m=''3816880''>this</span> <span m=''3817060''>gap</span>
  <span m=''3817310''>from</span> <span m=''3817440''>the</span> <span m=''3817550''>imperative</span>
  <span m=''3818010''>to the</span> <span m=''3818130''>declarative,</span> <span
  m=''3819440''>that</span> <span m=''3820090''>you</span> <span m=''3820240''>can</span>
  <span m=''3821360''>start</span> <span m=''3821680''>talking</span> <span m=''3822030''>about</span>
  <span m=''3822300''>relations</span> <span m=''3823640''>and</span> <span m=''3823830''>really</span>
  <span m=''3824100''>get</span> <span m=''3824280''>tremendous</span> <span m=''3824780''>power</span>
  <span m=''3826430''>by</span> <span m=''3826590''>going</span> <span m=''3826900''>above</span>
  <span m=''3827190''>the</span> <span m=''3827320''>abstraction</span> <span m=''3827850''>of</span>
  <span m=''3827920''>what''s</span> <span m=''3828110''>my</span> <span m=''3828270''>input</span>
  <span m=''3828570''>and</span> <span m=''3828670''>what''s</span> <span m=''3828850''>my</span>
  <span m=''3829060''>output.</span> <span m=''3830560''>And</span> <span m=''3830760''>linked</span>
  <span m=''3830940''>to</span> <span m=''3831040''>logic,</span> <span m=''3832540''>the</span>
  <span m=''3832690''>problem</span> <span m=''3833050''>is</span> <span m=''3833190''>it''s</span>
  <span m=''3834460''>a</span> <span m=''3834600''>goal</span> <span m=''3834910''>that</span>
  <span m=''3835020''>I</span> <span m=''3835160''>think</span> <span m=''3835290''>has</span>
  <span m=''3835450''>yet</span> <span m=''3835710''>to</span> <span m=''3835810''>be</span>
  <span m=''3835980''>realized.</span> </p><p><span m=''3838080''>And</span> <span
  m=''3838380''>probably</span> <span m=''3838740''>one</span> <span m=''3838900''>of</span>
  <span m=''3838960''>the</span> <span m=''3840140''>very</span> <span m=''3841050''>most</span>
  <span m=''3841240''>interesting</span> <span m=''3842310''>research</span> <span
  m=''3842740''>questions</span> <span m=''3843150''>going</span> <span m=''3843460''>on</span>
  <span m=''3843630''>now</span> <span m=''3843840''>in</span> <span m=''3843920''>languages</span>
  <span m=''3844690''>is</span> <span m=''3844840''>how</span> <span m=''3844990''>do</span>
  <span m=''3845060''>you</span> <span m=''3846530''>somehow</span> <span m=''3846890''>make</span>
  <span m=''3847090''>a</span> <span m=''3847160''>real</span> <span m=''3847390''>logic</span>
  <span m=''3847730''>language?</span> <span m=''3849460''>And</span> <span m=''3849690''>secondly,</span>
  <span m=''3850000''>how</span> <span m=''3850110''>do</span> <span m=''3850190''>you</span>
  <span m=''3850270''>bridge</span> <span m=''3850540''>the</span> <span m=''3850650''>gap</span>
  <span m=''3851330''>from</span> <span m=''3851540''>this</span> <span m=''3851690''>world</span>
  <span m=''3851940''>of</span> <span m=''3852040''>logic</span> <span m=''3852430''>and</span>
  <span m=''3852530''>relations</span> <span m=''3853380''>to</span> <span m=''3853740''>the</span>
  <span m=''3853860''>worlds</span> <span m=''3855110''>of</span> <span m=''3855210''>more</span>
  <span m=''3855520''>traditional</span> <span m=''3856020''>languages</span> <span
  m=''3856470''>and</span> <span m=''3856560''>somehow</span> <span m=''3856860''>combine</span>
  <span m=''3857210''>the</span> <span m=''3857290''>power</span> <span m=''3857680''>of</span>
  <span m=''3858180''>both.</span> <span m=''3858680''>OK,</span> <span m=''3859180''>let''s</span>
  <span m=''3859400''>break.</span> </p><p><span m=''3863750''>AUDIENCE: Couldn''t</span>
  <span m=''3864050''>you</span> <span m=''3864150''>solve</span> <span m=''3864440''>that</span>
  <span m=''3864640''>last</span> <span m=''3864970''>problem</span> <span m=''3865320''>by</span>
  <span m=''3865450''>having the</span> <span m=''3865900''>extra</span> <span m=''3866230''>rules</span>
  <span m=''3866690''>that</span> <span m=''3866950''>imply</span> <span m=''3867370''>it?</span>
  <span m=''3867430''>The</span> <span m=''3867820''>problem</span> <span m=''3868320''>here</span>
  <span m=''3868550''>is</span> <span m=''3868640''>you</span> <span m=''3868820''>have</span>
  <span m=''3869010''>the</span> <span m=''3869080''>definition</span> <span m=''3869600''>of</span>
  <span m=''3869670''>something,</span> <span m=''3870060''>but</span> <span m=''3870200''>you</span>
  <span m=''3870290''>don''t</span> <span m=''3870460''>have</span> <span m=''3870590''>the</span>
  <span m=''3870670''>definition</span> <span m=''3871130''>of</span> <span m=''3871190''>its</span>
  <span m=''3871330''>opposite.</span> <span m=''3872210''>If you include</span> <span
  m=''3872610''>in</span> <span m=''3872650''>the</span> <span m=''3872690''>database</span>
  <span m=''3873150''>something</span> <span m=''3873400''>that</span> <span m=''3873550''>says</span>
  <span m=''3875390''>something</span> <span m=''3875890''>implies</span> <span m=''3876380''>mortal</span>
  <span m=''3876710''>x,</span> <span m=''3876990''>something</span> <span m=''3877310''>else</span>
  <span m=''3877550''>implies</span> <span m=''3878020''>not</span> <span m=''3878320''>mortal</span>
  <span m=''3878470''>x,</span> <span m=''3878780''>haven''t</span> <span m=''3878980''>you</span>
  <span m=''3879180''>basically</span> <span m=''3879640''>solved</span> <span m=''3879900''>the</span>
  <span m=''3879970''>problem?</span> </p><p><span m=''3883370''>PROFESSOR: But</span>
  <span m=''3883520''>the</span> <span m=''3883720''>issue</span> <span m=''3883920''>is</span>
  <span m=''3884850''>do</span> <span m=''3884950''>you</span> <span m=''3885060''>put</span>
  <span m=''3885210''>a</span> <span m=''3885260''>finite</span> <span m=''3885660''>number</span>
  <span m=''3885950''>of</span> <span m=''3886010''>those</span> <span m=''3886240''>in?</span>
  </p><p><span m=''3890740''>AUDIENCE: If</span> <span m=''3890980''>things</span>
  <span m=''3891320''>are</span> <span m=''3891450''>specified</span> <span m=''3892060''>always</span>
  <span m=''3892370''>in  pairs--</span> </p><p><span m=''3894980''>PROFESSOR: But</span>
  <span m=''3895100''>the</span> <span m=''3895250''>impression</span> <span m=''3895590''>is</span>
  <span m=''3895750''>then</span> <span m=''3895840''>what</span> <span m=''3895950''>do
  you</span> <span m=''3895990''>do</span> <span m=''3896110''>about</span> <span
  m=''3896470''>deduction?</span> <span m=''3900200''>You</span> <span m=''3900440''>can''t</span>
  <span m=''3901180''>specify</span> <span m=''3901660''>NOTs.</span> <span m=''3903400''>But</span>
  <span m=''3903540''>the</span> <span m=''3903600''>problem</span> <span m=''3903900''>is,</span>
  <span m=''3904000''>in</span> <span m=''3904060''>a</span> <span m=''3904100''>big</span>
  <span m=''3904290''>system,</span> <span m=''3904710''>it</span> <span m=''3904790''>turns</span>
  <span m=''3905060''>out</span> <span m=''3905190''>that</span> <span m=''3905930''>might</span>
  <span m=''3906180''>not</span> <span m=''3906380''>be</span> <span m=''3906510''>a</span>
  <span m=''3906570''>finite</span> <span m=''3907060''>number</span> <span m=''3907390''>of</span>
  <span m=''3907520''>things.</span> <span m=''3912820''>There</span> <span m=''3913030''>are</span>
  <span m=''3913060''>also</span> <span m=''3914010''>sort</span> <span m=''3914440''>of</span>
  <span m=''3914770''>two</span> <span m=''3914990''>issues.</span> <span m=''3915290''>Partly</span>
  <span m=''3915620''>it</span> <span m=''3915690''>might</span> <span m=''3915850''>not</span>
  <span m=''3916010''>be</span> <span m=''3916130''>finite.</span> <span m=''3916690''>Partly</span>
  <span m=''3917170''>it</span> <span m=''3917320''>might</span> <span m=''3917560''>be</span>
  <span m=''3918300''>that''s</span> <span m=''3918630''>not</span> <span m=''3918770''>what</span>
  <span m=''3918900''>you</span> <span m=''3919040''>want.</span> </p><p><span m=''3921510''>So</span>
  <span m=''3921950''>a</span> <span m=''3922020''>good</span> <span m=''3922150''>example</span>
  <span m=''3922560''>would</span> <span m=''3922680''>be</span> <span m=''3922930''>suppose</span>
  <span m=''3923340''>I</span> <span m=''3923400''>want</span> <span m=''3923510''>to</span>
  <span m=''3923620''>do</span> <span m=''3923790''>connectivity.</span> <span m=''3925120''>I
  want</span> <span m=''3925290''>a</span> <span m=''3925340''>reason about</span>
  <span m=''3925830''>connectivity.</span> <span m=''3928050''>And</span> <span m=''3928850''>I''m
  going to</span> <span m=''3929060''>tell</span> <span m=''3929230''>you</span> <span
  m=''3929610''>there''s</span> <span m=''3929930''>four</span> <span m=''3930120''>things:</span>
  <span m=''3930460''>a</span> <span m=''3930930''>and</span> <span m=''3931420''>b</span>
  <span m=''3932100''>and</span> <span m=''3932300''>c</span> <span m=''3933240''>and</span>
  <span m=''3933420''>d.</span> <span m=''3935480''>And</span> <span m=''3935720''>I''ll</span>
  <span m=''3935810''>tell</span> <span m=''3936065''>you a is</span> <span m=''3936320''>connected</span>
  <span m=''3936740''>to</span> <span m=''3937810''>b</span> <span m=''3938690''>and</span>
  <span m=''3939530''>c''s</span> <span m=''3939740''>connected</span> <span m=''3940680''>to</span>
  <span m=''3941040''>d.</span> <span m=''3943200''>And</span> <span m=''3943330''>now</span>
  <span m=''3943490''>I''ll tell you is</span> <span m=''3943850''>a</span> <span
  m=''3943980''>connected</span> <span m=''3944400''>to</span> <span m=''3944480''>d?</span>
  <span m=''3945260''>That''s</span> <span m=''3945430''>the</span> <span m=''3945500''>question.</span>
  </p><p><span m=''3946780''>There''s</span> <span m=''3947070''>an</span> <span m=''3947120''>example</span>
  <span m=''3947800''>where</span> <span m=''3948010''>I</span> <span m=''3948080''>would</span>
  <span m=''3948240''>like</span> <span m=''3948680''>something</span> <span m=''3949100''>like</span>
  <span m=''3949280''>the</span> <span m=''3949360''>closed</span> <span m=''3949660''>world</span>
  <span m=''3949870''>assumption.</span> <span m=''3954200''>That''s</span> <span
  m=''3954720''>a</span> <span m=''3954860''>tiny</span> <span m=''3955210''>toy,</span>
  <span m=''3956250''>but</span> <span m=''3956380''>a</span> <span m=''3956420''>lot</span>
  <span m=''3956660''>of</span> <span m=''3956720''>times,</span> <span m=''3957000''>I</span>
  <span m=''3957060''>want</span> <span m=''3957170''>to</span> <span m=''3957280''>be</span>
  <span m=''3957440''>able</span> <span m=''3957570''>to</span> <span m=''3957630''>say</span>
  <span m=''3957820''>something</span> <span m=''3958130''>like</span> <span m=''3958550''>anything</span>
  <span m=''3958920''>that</span> <span m=''3959010''>I</span> <span m=''3959110''>haven''t</span>
  <span m=''3959390''>told</span> <span m=''3959640''>you,</span> <span m=''3959800''>assume</span>
  <span m=''3960090''>is</span> <span m=''3960200''>not</span> <span m=''3961030''>true.</span>
  <span m=''3964260''>So</span> <span m=''3964460''>it''s</span> <span m=''3964580''>not</span>
  <span m=''3964770''>as</span> <span m=''3964850''>simple</span> <span m=''3965170''>as</span>
  <span m=''3965250''>you</span> <span m=''3965380''>only</span> <span m=''3965670''>want</span>
  <span m=''3965840''>to</span> <span m=''3965910''>put</span> <span m=''3966100''>in</span>
  <span m=''3966280''>explicit</span> <span m=''3966990''>NOTs</span> <span m=''3967350''>all</span>
  <span m=''3967520''>over</span> <span m=''3967660''>the</span> <span m=''3967790''>place.</span>
  <span m=''3969470''>It''s</span> <span m=''3969640''>that</span> <span m=''3969790''>sometimes</span>
  <span m=''3970200''>it</span> <span m=''3970290''>really</span> <span m=''3970580''>isn''t</span>
  <span m=''3970870''>clear</span> <span m=''3971200''>what</span> <span m=''3971390''>you</span>
  <span m=''3972060''>even</span> <span m=''3972360''>want.</span> <span m=''3974150''>That</span>
  <span m=''3974560''>having  to</span> <span m=''3974910''>specify</span> <span m=''3975560''>both</span>
  <span m=''3975860''>everything</span> <span m=''3976310''>and</span> <span m=''3976490''>not</span>
  <span m=''3976760''>everything</span> <span m=''3977160''>is</span> <span m=''3977310''>too</span>
  <span m=''3977480''>precise,</span> <span m=''3977970''>and</span> <span m=''3978070''>then</span>
  <span m=''3978180''>you</span> <span m=''3978270''>get</span> <span m=''3978410''>down</span>
  <span m=''3978720''>into</span> <span m=''3979380''>problems</span> <span m=''3979830''>there.</span>
  <span m=''3980960''>But</span> <span m=''3981090''>there</span> <span m=''3981210''>are</span>
  <span m=''3981670''>a</span> <span m=''3981760''>lot</span> <span m=''3981860''>of</span>
  <span m=''3981950''>approaches</span> <span m=''3982430''>that</span> <span m=''3983680''>explicitly</span>
  <span m=''3984250''>put</span> <span m=''3984420''>in</span> <span m=''3984580''>NOTs</span>
  <span m=''3984910''>and</span> <span m=''3985000''>reason</span> <span m=''3985320''>based</span>
  <span m=''3985590''>on</span> <span m=''3985740''>that.</span> <span m=''3986510''>So</span>
  <span m=''3986690''>it''s</span> <span m=''3986820''>a</span> <span m=''3986860''>very</span>
  <span m=''3987080''>good</span> <span m=''3987280''>idea.</span> <span m=''3988070''>It''s</span>
  <span m=''3988250''>just</span> <span m=''3988410''>that</span> <span m=''3990050''>then</span>
  <span m=''3990190''>it</span> <span m=''3990290''>starts</span> <span m=''3990560''>becoming</span>
  <span m=''3990920''>a</span> <span m=''3990960''>little</span> <span m=''3991150''>cumbersome</span>
  <span m=''3991620''>in</span> <span m=''3991700''>the</span> <span m=''3991780''>very</span>
  <span m=''3992040''>large</span> <span m=''3992330''>problems</span> <span m=''3992660''>you''d</span>
  <span m=''3992780''>like to</span> <span m=''3993070''>use.</span> </p><p><span
  m=''4003460''>AUDIENCE: I''m</span> <span m=''4003580''>not</span> <span m=''4003760''>sure</span>
  <span m=''4003950''>how</span> <span m=''4004620''>directly</span> <span m=''4005030''>related</span>
  <span m=''4005220''>to the</span> <span m=''4005410''>argument</span> <span m=''4005670''>this</span>
  <span m=''4005860''>is, but</span> <span m=''4006160''>one</span> <span m=''4006290''>of</span>
  <span m=''4006380''>your</span> <span m=''4006480''>points</span> <span m=''4006900''>was</span>
  <span m=''4007140''>that</span> <span m=''4008680''>one of</span> <span m=''4008840''>the</span>
  <span m=''4008920''>dangers of</span> <span m=''4009320''>the</span> <span m=''4009440''>closed</span>
  <span m=''4009840''>rule</span> <span m=''4010070''>is</span> <span m=''4010150''>you</span>
  <span m=''4010260''>never</span> <span m=''4010520''>really</span> <span m=''4010740''>know</span>
  <span m=''4010940''>all</span> <span m=''4011100''>the</span> <span m=''4011190''>things</span>
  <span m=''4011570''>that</span> <span m=''4011650''>are</span> <span m=''4011730''>there.</span>
  <span m=''4013840''>You</span> <span m=''4014040''>never</span> <span m=''4014210''>really</span>
  <span m=''4014360''>know</span> <span m=''4014500''>all</span> <span m=''4014650''>the</span>
  <span m=''4014730''>parts</span> <span m=''4015020''>to</span> <span m=''4015140''>it.</span>
  <span m=''4015930''>Isn''t</span> <span m=''4016100''>that</span> <span m=''4016620''>a</span>
  <span m=''4016720''>major</span> <span m=''4017040''>problem</span> <span m=''4017330''>with</span>
  <span m=''4017470''>any</span> <span m=''4017600''>programming?</span> <span m=''4018160''>I</span>
  <span m=''4018320''>always</span> <span m=''4018620''>write</span> <span m=''4018820''>programs</span>
  <span m=''4019300''>where</span> <span m=''4019520''>I</span> <span m=''4020100''>assume</span>
  <span m=''4020440''>that I''ve</span> <span m=''4020710''>got</span> <span m=''4020890''>all</span>
  <span m=''4021010''>the</span> <span m=''4021110''>cases,</span> <span m=''4021600''>and</span>
  <span m=''4021720''>so</span> <span m=''4021820''>I</span> <span m=''4021890''>check
  for</span> <span m=''4022250''>them</span> <span m=''4022360''>all</span> <span
  m=''4022600''>or</span> <span m=''4022660''>whatever,</span> <span m=''4023020''>and</span>
  <span m=''4024020''>somewhere</span> <span m=''4024430''>down</span> <span m=''4024520''>the</span>
  <span m=''4024620''>road,</span> <span m=''4024880''>I</span> <span m=''4024960''>find</span>
  <span m=''4025160''>out that</span> <span m=''4025370''>I</span> <span m=''4025460''>didn''t</span>
  <span m=''4025750''>check</span> <span m=''4025960''>for</span> <span m=''4026060''>one</span>
  <span m=''4026240''>of them.</span> </p><p><span m=''4027390''>PROFESSOR: Well,</span>
  <span m=''4027870''>sure,</span> <span m=''4028130''>it''s</span> <span m=''4028280''>true.</span>
  <span m=''4028540''>But</span> <span m=''4028700''>the</span> <span m=''4028790''>problem</span>
  <span m=''4029150''>here</span> <span m=''4029430''>is</span> <span m=''4032020''>it''s</span>
  <span m=''4032220''>that</span> <span m=''4032460''>assumption</span> <span m=''4033790''>which</span>
  <span m=''4034040''>is</span> <span m=''4034350''>the</span> <span m=''4034630''>thing</span>
  <span m=''4034820''>that</span> <span m=''4034960''>you''re</span> <span m=''4035090''>making</span>
  <span m=''4035440''>if</span> <span m=''4035540''>you</span> <span m=''4035640''>believe</span>
  <span m=''4035940''>you''re</span> <span m=''4036060''>identifying</span> <span
  m=''4036610''>this</span> <span m=''4036760''>with</span> <span m=''4036930''>logic.</span>
  <span m=''4039600''>So</span> <span m=''4039750''>you''re</span> <span m=''4040080''>quite</span>
  <span m=''4040300''>right.</span> <span m=''4040510''>It''s</span> <span m=''4040650''>a</span>
  <span m=''4040970''>situation</span> <span m=''4041570''>you''re</span> <span m=''4041680''>never</span>
  <span m=''4041980''>in.</span> <span m=''4042220''>The</span> <span m=''4042300''>problem</span>
  <span m=''4042680''>is</span> <span m=''4043170''>if</span> <span m=''4043300''>you''re</span>
  <span m=''4043400''>starting</span> <span m=''4043720''>to</span> <span m=''4043830''>believe</span>
  <span m=''4044140''>that</span> <span m=''4044260''>what</span> <span m=''4044420''>this</span>
  <span m=''4044570''>is</span> <span m=''4044690''>doing</span> <span m=''4044920''>is</span>
  <span m=''4045050''>logic</span> <span m=''4046160''>and</span> <span m=''4046310''>you</span>
  <span m=''4046460''>look</span> <span m=''4046570''>at</span> <span m=''4046690''>the</span>
  <span m=''4046780''>rules</span> <span m=''4047050''>you</span> <span m=''4047180''>write
  down</span> <span m=''4047430''>and</span> <span m=''4047650''>say</span> <span
  m=''4047760''>what</span> <span m=''4047920''>can</span> <span m=''4048040''>I</span>
  <span m=''4048100''>deduce</span> <span m=''4048480''>from</span> <span m=''4048640''>them,</span>
  <span m=''4049620''>you have to</span> <span m=''4049770''>be</span> <span m=''4049870''>very</span>
  <span m=''4050200''>careful</span> <span m=''4050560''>to</span> <span m=''4050620''>remember</span>
  <span m=''4051100''>that</span> <span m=''4051600''>NOT</span> <span m=''4051850''>means</span>
  <span m=''4052030''>something</span> <span m=''4052400''>else.</span> <span m=''4053470''>And</span>
  <span m=''4053650''>it</span> <span m=''4053810''>means</span> <span m=''4054030''>something</span>
  <span m=''4054320''>else</span> <span m=''4054500''>based</span> <span m=''4054760''>on</span>
  <span m=''4054870''>an</span> <span m=''4054970''>assumption</span> <span m=''4055360''>which</span>
  <span m=''4055510''>is</span> <span m=''4055610''>probably</span> <span m=''4056080''>not</span>
  <span m=''4056310''>true.</span> </p><p><span m=''4059030''>AUDIENCE: Do I</span>
  <span m=''4059170''>understand</span> <span m=''4059520''>you</span> <span m=''4059590''>correctly</span>
  <span m=''4059980''>that</span> <span m=''4060270''>you</span> <span m=''4060430''>cannot</span>
  <span m=''4060940''>fix</span> <span m=''4061170''>this</span> <span m=''4061340''>problem</span>
  <span m=''4062340''>without</span> <span m=''4062670''>killing</span> <span m=''4062970''>off</span>
  <span m=''4063160''>all</span> <span m=''4063450''>possibilities</span> <span m=''4064020''>of</span>
  <span m=''4064510''>inference</span> <span m=''4065110''>through</span> <span m=''4065400''>altering</span>
  <span m=''4065730''>NOT?</span> </p><p><span m=''4067990''>PROFESSOR: No,</span>
  <span m=''4068470''>that''s</span> <span m=''4068780''>not</span> <span m=''4068960''>quite</span>
  <span m=''4069200''>right.</span> <span m=''4069370''>There</span> <span m=''4069490''>are</span>
  <span m=''4069510''>other--</span> <span m=''4072710''>there</span> <span m=''4073110''>are</span>
  <span m=''4073160''>ways</span> <span m=''4073430''>to</span> <span m=''4073530''>do</span>
  <span m=''4073690''>logic</span> <span m=''4074120''>with</span> <span m=''4074290''>real</span>
  <span m=''4074550''>NOTs.</span> <span m=''4076340''>There</span> <span m=''4076690''>are</span>
  <span m=''4076720''>actually</span> <span m=''4077030''>ways</span> <span m=''4077310''>to</span>
  <span m=''4077430''>do</span> <span m=''4077640''>that.</span> <span m=''4078540''>But</span>
  <span m=''4078680''>they''re</span> <span m=''4078860''>very</span> <span m=''4079220''>inefficient</span>
  <span m=''4079700''>as</span> <span m=''4079810''>far</span> <span m=''4079980''>as</span>
  <span m=''4080060''>anybody</span> <span m=''4080440''>knows.</span> <span m=''4081610''>And</span>
  <span m=''4081780''>they''re</span> <span m=''4081900''>much</span> <span m=''4082140''>more--</span>
  <span m=''4085390''>the,</span> <span m=''4085710''>quote,</span> <span m=''4086020''>inference</span>
  <span m=''4086520''>in</span> <span m=''4086620''>here</span> <span m=''4087440''>is</span>
  <span m=''4087630''>built</span> <span m=''4087880''>into</span> <span m=''4088070''>this</span>
  <span m=''4088260''>unifier</span> <span m=''4089070''>and</span> <span m=''4089240''>this</span>
  <span m=''4089380''>pattern</span> <span m=''4089720''>matching</span> <span m=''4090070''>unification</span>
  <span m=''4090365''>algorithm.</span> <span m=''4091980''>There</span> <span m=''4092110''>are</span>
  <span m=''4092160''>ways</span> <span m=''4092480''>to</span> <span m=''4092640''>automate</span>
  <span m=''4094490''>real</span> <span m=''4095070''>logical</span> <span m=''4095540''>reasoning.</span>
  <span m=''4096590''>But</span> <span m=''4096979''>it''s</span> <span m=''4097160''>not</span>
  <span m=''4097420''>based</span> <span m=''4097720''>on</span> <span m=''4097870''>that,</span>
  <span m=''4098520''>and</span> <span m=''4098729''>logic</span> <span m=''4099040''>programming</span>
  <span m=''4099460''>languages</span> <span m=''4099890''>don''t</span> <span m=''4100100''>tend</span>
  <span m=''4100279''>to</span> <span m=''4100350''>do</span> <span m=''4100510''>that</span>
  <span m=''4100729''>because</span> <span m=''4100990''>it''s</span> <span m=''4101149''>very</span>
  <span m=''4101420''>inefficient</span> <span m=''4102729''>as</span> <span m=''4102850''>far</span>
  <span m=''4103010''>as</span> <span m=''4103100''>anybody</span> <span m=''4103439''>knows.</span>
  <span m=''4109390''>All right,</span> <span m=''4109500''>thank</span> <span m=''4109740''>you.</span>
  </p>'
type: course
uid: 1d264c40a64a3604495574e9399e9070

---
None