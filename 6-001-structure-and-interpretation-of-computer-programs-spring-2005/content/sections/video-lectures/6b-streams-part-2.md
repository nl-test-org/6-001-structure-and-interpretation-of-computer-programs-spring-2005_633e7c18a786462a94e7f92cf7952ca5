---
about_this_resource_text: '<p><b>Topics covered: </b>Streams, Part 2</p> <p><b> Instructors:</b>
  Hal Abelson and Gerald Jay Sussman</p>  <p>Subtitles for this course are provided
  through the generous assistance of Henry Baker, Hoofar Pourzand, Heather Wood, Aleksejs
  Truhans, Steven Edwards, George Menhorn, and Mahendra Kumar.</p>'
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
embedded_media:
- id: 6B.jpg
  parent_uid: 2b3f4b452167491302a2e4dedb19bcbd
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/6b-streams-part-2/6B.jpg
  title: 6B.jpg
  type: null
  uid: 666fbe3ee558d5de9c365c404558e46e
- id: Video-YouTube-Stream
  media_location: qp05AtXbOP0
  parent_uid: 2b3f4b452167491302a2e4dedb19bcbd
  title: Video-YouTube-Stream
  type: Video
  uid: 26bc9682c609e6b4a2350714f5cc94b4
- id: Thumbnail-OCW-JPG
  parent_uid: 2b3f4b452167491302a2e4dedb19bcbd
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 4b77d3aef6204a9d58df4643fd9372a6
- id: 3Play-3PlayYouTubeid-MP4
  media_location: qp05AtXbOP0
  parent_uid: 2b3f4b452167491302a2e4dedb19bcbd
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 0bcad1788c6c03559aa9eb97ed7f0882
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/qp05AtXbOP0/default.jpg
  parent_uid: 2b3f4b452167491302a2e4dedb19bcbd
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 3083172f5235181072f34d8f7d53e2a9
- id: qp05AtXbOP0.srt
  parent_uid: 2b3f4b452167491302a2e4dedb19bcbd
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/6b-streams-part-2/qp05AtXbOP0.srt
  title: 3play caption file
  type: null
  uid: e2ee68d63621b5ada7ee948b186b0dad
- id: qp05AtXbOP0.pdf
  parent_uid: 2b3f4b452167491302a2e4dedb19bcbd
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/6b-streams-part-2/qp05AtXbOP0.pdf
  title: 3play pdf file
  type: null
  uid: 449fc46f264e5f94d2151e42b5fb7b60
- id: Caption-3Play YouTube id-SRT
  parent_uid: 2b3f4b452167491302a2e4dedb19bcbd
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 6d25708955a66e069a8c14c16db7c62b
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 2b3f4b452167491302a2e4dedb19bcbd
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: d78a2cca49beae6c41f04342221333ab
- id: Video-InternetArchive-MP4_1
  media_location: http://www.archive.org/download/MIT_Structure_of_Computer_Programs_1986/lec6b.mp4
  parent_uid: 2b3f4b452167491302a2e4dedb19bcbd
  title: Video-Internet Archive-MP4
  type: Video
  uid: f2fa85146c93a54202e2979061297f05
inline_embed_id: 186018096b:streams,part233500843
layout: video
order_index: null
parent_uid: 4fcacad2c29981dd668a6b29822403cc
related_resources_text: ''
short_url: 6b-streams-part-2
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/6b-streams-part-2
template_type: Tabbed
title: '6B: Streams, Part 2'
transcript: '<p><span m=''20970''>PROFESSOR: OK,</span> <span m=''21090''>well,</span>
  <span m=''21560''>we''ve</span> <span m=''21700''>been</span> <span m=''21830''>looking</span>
  <span m=''22190''>at</span> <span m=''23430''>streams,</span> <span m=''24100''>this</span>
  <span m=''24580''>signal</span> <span m=''24990''>processing</span> <span m=''25690''>way</span>
  <span m=''26420''>of</span> <span m=''26740''>putting</span> <span m=''27010''>systems</span>
  <span m=''27390''>together.</span> <span m=''28870''>And</span> <span m=''28980''>remember,</span>
  <span m=''29270''>the</span> <span m=''29390''>key</span> <span m=''29650''>idea</span>
  <span m=''30980''>is</span> <span m=''31170''>that</span> <span m=''31920''>we</span>
  <span m=''32119''>decouple</span> <span m=''34220''>the</span> <span m=''34680''>apparent</span>
  <span m=''35200''>order</span> <span m=''35530''>of</span> <span m=''35620''>events</span>
  <span m=''36460''>in</span> <span m=''36570''>our</span> <span m=''36670''>programs</span>
  <span m=''37560''>from</span> <span m=''37680''>the</span> <span m=''37800''>actual</span>
  <span m=''38220''>order</span> <span m=''38480''>of</span> <span m=''38560''>events</span>
  <span m=''39390''>in</span> <span m=''39490''>the</span> <span m=''39600''>computer.</span>
  <span m=''40635''>And</span> <span m=''41090''>that</span> <span m=''41360''>means</span>
  <span m=''41530''>that</span> <span m=''41650''>we</span> <span m=''41760''>can</span>
  <span m=''41880''>start</span> <span m=''42640''>dealing</span> <span m=''42970''>with</span>
  <span m=''43110''>very</span> <span m=''43400''>long</span> <span m=''43630''>streams</span>
  <span m=''45010''>and</span> <span m=''45240''>only</span> <span m=''45510''>having</span>
  <span m=''45820''>to</span> <span m=''45900''>generate</span> <span m=''46340''>the</span>
  <span m=''46450''>elements</span> <span m=''46830''>on</span> <span m=''46970''>demand.</span>
  <span m=''47500''>That</span> <span m=''47780''>sort</span> <span m=''47940''>of</span>
  <span m=''48040''>on-demand</span> <span m=''48650''>computation</span> <span m=''49570''>is</span>
  <span m=''49730''>built</span> <span m=''50040''>into</span> <span m=''50170''>the</span>
  <span m=''50310''>stream''s</span> <span m=''50670''>data</span> <span m=''50890''>structure.</span>
  <span m=''54450''>So if</span> <span m=''54660''>we</span> <span m=''54750''>have</span>
  <span m=''54860''>a</span> <span m=''54910''>very</span> <span m=''55200''>long</span>
  <span m=''55410''>stream,</span> <span m=''55630''>we</span> <span m=''55740''>only</span>
  <span m=''55990''>compute</span> <span m=''56320''>what</span> <span m=''56460''>we</span>
  <span m=''56560''>need.</span> <span m=''58040''>The</span> <span m=''58430''>things</span>
  <span m=''58640''>only</span> <span m=''58930''>get</span> <span m=''59090''>computed</span>
  <span m=''59510''>when</span> <span m=''59610''>we</span> <span m=''59760''>actually</span>
  <span m=''60300''>ask</span> <span m=''60580''>for</span> <span m=''60660''>them.</span>
  </p><p><span m=''60750''>Well, what  are</span> <span m=''61150''>examples?</span>
  <span m=''62110''>Are they</span> <span m=''62270''>actually</span> <span m=''62820''>asking</span>
  <span m=''63180''>for</span> <span m=''63280''>them?</span> <span m=''64800''>For</span>
  <span m=''65239''>instance,</span> <span m=''65550''>we</span> <span m=''65670''>might</span>
  <span m=''69510''>ask</span> <span m=''69770''>for</span> <span m=''69880''>the</span>
  <span m=''70000''>n-th</span> <span m=''70300''>element</span> <span m=''70660''>of</span>
  <span m=''70750''>a</span> <span m=''70790''>stream.</span> <span m=''76360''>Here''s</span>
  <span m=''76530''>a</span> <span m=''76580''>procedure</span> <span m=''77010''>that</span>
  <span m=''77180''>computes</span> <span m=''77550''>the</span> <span m=''77650''>n-th</span>
  <span m=''78130''>element</span> <span m=''78400''>of a</span> <span m=''78670''>stream.</span>
  <span m=''80400''>An</span> <span m=''80530''>integer</span> <span m=''80680''>n,</span>
  <span m=''80980''>the</span> <span m=''81300''>n-th</span> <span m=''81640''>element</span>
  <span m=''81920''>of</span> <span m=''81980''>some</span> <span m=''82150''>stream</span>
  <span m=''82430''>s,</span> <span m=''83205''>and</span> <span m=''83480''>we</span>
  <span m=''83650''>just</span> <span m=''83810''>recursively</span> <span m=''84430''>walk
  down</span> <span m=''84710''>the stream.</span> <span m=''85570''>And the</span>
  <span m=''85820''>end</span> <span m=''85910''>of 0,</span> <span m=''86360''>we</span>
  <span m=''86480''>compute</span> <span m=''86790''>the</span> <span m=''86890''>head.</span>
  <span m=''87960''>Otherwise,</span> <span m=''88410''>it''s the</span> <span m=''88680''>n-th</span>
  <span m=''89320''>the</span> <span m=''89720''>minus</span> <span m=''90030''>1</span>
  <span m=''90540''>element</span> <span m=''91710''>of</span> <span m=''91920''>the</span>
  <span m=''92000''>tail</span> <span m=''92280''>of</span> <span m=''92350''>the</span>
  <span m=''92420''>stream.</span> <span m=''94310''>Those</span> <span m=''94410''>two</span>
  <span m=''94650''>are</span> <span m=''94770''>just</span> <span m=''95010''>like</span>
  <span m=''95200''>for</span> <span m=''95350''>Lisp,</span> <span m=''95610''>but</span>
  <span m=''95700''>the</span> <span m=''95800''>difference</span> <span m=''96210''>is</span>
  <span m=''96570''>those</span> <span m=''96780''>elements</span> <span m=''97120''>aren''t</span>
  <span m=''97410''>going</span> <span m=''97480''>to</span> <span m=''97550''>get</span>
  <span m=''98170''>computed</span> <span m=''98880''>until</span> <span m=''99150''>we</span>
  <span m=''99270''>walk</span> <span m=''99580''>down,</span> <span m=''99840''>taking</span>
  <span m=''100150''>successive</span> <span m=''100650''>n-ths.</span> <span m=''101700''>So</span>
  <span m=''101810''>that''s</span> <span m=''102020''>one</span> <span m=''102260''>way</span>
  <span m=''102850''>that</span> <span m=''103120''>the</span> <span m=''103250''>stream</span>
  <span m=''103630''>elements</span> <span m=''103980''>might</span> <span m=''104190''>get</span>
  <span m=''104370''>forced.</span> </p><p><span m=''105910''>And</span> <span m=''105990''>another</span>
  <span m=''106360''>way,</span> <span m=''107210''>here''s</span> <span m=''107400''>a</span>
  <span m=''107460''>little</span> <span m=''107610''>procedure</span> <span m=''107980''>that</span>
  <span m=''108140''>prints</span> <span m=''108420''>a</span> <span m=''108470''>stream.</span>
  <span m=''109300''>We</span> <span m=''109390''>say</span> <span m=''109540''>print</span>
  <span m=''109800''>a</span> <span m=''109890''>stream,</span> <span m=''111770''>so</span>
  <span m=''112270''>to</span> <span m=''112340''>print</span> <span m=''112540''>a</span>
  <span m=''112590''>stream</span> <span m=''112900''>s.</span> <span m=''114150''>Well,</span>
  <span m=''114300''>what</span> <span m=''114550''>do</span> <span m=''114740''>we</span>
  <span m=''114930''>do?</span> <span m=''115315''>We</span> <span m=''115700''>print</span>
  <span m=''115930''>the</span> <span m=''116020''>head</span> <span m=''116210''>of</span>
  <span m=''116280''>the</span> <span m=''116350''>stream,</span> <span m=''117120''>and</span>
  <span m=''117450''>that</span> <span m=''117950''>will</span> <span m=''118030''>cause</span>
  <span m=''118270''>the</span> <span m=''118340''>head</span> <span m=''118540''>to</span>
  <span m=''118630''>be</span> <span m=''118750''>computed.</span> <span m=''119720''>And</span>
  <span m=''119850''>then</span> <span m=''119990''>we</span> <span m=''120100''>recursively</span>
  <span m=''121350''>print</span> <span m=''121600''>stream</span> <span m=''121880''>the</span>
  <span m=''121970''>tail</span> <span m=''122230''>of</span> <span m=''122310''>the</span>
  <span m=''122370''>stream.</span> <span m=''124990''>And</span> <span m=''125210''>if</span>
  <span m=''125310''>we''re</span> <span m=''125430''>already</span> <span m=''125740''>done,</span>
  <span m=''126020''>maybe</span> <span m=''126380''>we</span> <span m=''126670''>have</span>
  <span m=''126710''>to</span> <span m=''126950''>return</span> <span m=''127190''>something</span>
  <span m=''127530''>about</span> <span m=''127680''>the</span> <span m=''127840''>message</span>
  <span m=''128210''>done.</span> <span m=''129660''>OK,</span> <span m=''129889''>and</span>
  <span m=''130039''>then</span> <span m=''130289''>so</span> <span m=''130460''>if</span>
  <span m=''130539''>you</span> <span m=''130620''>make</span> <span m=''130830''>a</span>
  <span m=''130880''>stream,</span> <span m=''131710''>you</span> <span m=''131810''>could</span>
  <span m=''131920''>say</span> <span m=''132040''>here''s</span> <span m=''132250''>the</span>
  <span m=''132340''>stream,</span> <span m=''132610''>this</span> <span m=''132880''>very</span>
  <span m=''133090''>long</span> <span m=''133290''>stream.</span> <span m=''134310''>And</span>
  <span m=''135010''>then</span> <span m=''135300''>you</span> <span m=''135460''>say</span>
  <span m=''135610''>print</span> <span m=''135850''>the</span> <span m=''135930''>stream,</span>
  <span m=''136370''>and</span> <span m=''136470''>the</span> <span m=''136570''>elements</span>
  <span m=''136940''>of</span> <span m=''136990''>the</span> <span m=''137060''>stream</span>
  <span m=''137700''>will</span> <span m=''137900''>get</span> <span m=''138240''>computed</span>
  <span m=''138910''>successively</span> <span m=''139900''>as</span> <span m=''140120''>that</span>
  <span m=''140300''>print</span> <span m=''140550''>calls</span> <span m=''140890''>them.</span>
  <span m=''141320''>They</span> <span m=''141430''>won''t</span> <span m=''141610''>get</span>
  <span m=''141710''>all</span> <span m=''141850''>computed</span> <span m=''142190''>initially.</span>
  <span m=''144680''>So</span> <span m=''144820''>in</span> <span m=''144930''>this</span>
  <span m=''145050''>way,</span> <span m=''145190''>we</span> <span m=''145330''>can</span>
  <span m=''148140''>deal</span> <span m=''148290''>with</span> <span m=''148430''>some</span>
  <span m=''148570''>very</span> <span m=''148900''>long</span> <span m=''149140''>streams.</span>
  <span m=''150190''>Well,</span> <span m=''150800''>how</span> <span m=''150970''>long</span>
  <span m=''151160''>can a stream</span> <span m=''151425''>be?</span> <span m=''153600''>Well,</span>
  <span m=''153880''>it</span> <span m=''154160''>can</span> <span m=''154260''>be</span>
  <span m=''154350''>infinitely</span> <span m=''154780''>long.</span> </p><p><span
  m=''156360''>Let''s</span> <span m=''156560''>look</span> <span m=''156660''>at
  an</span> <span m=''156770''>example</span> <span m=''157230''>here</span> <span
  m=''157390''>on</span> <span m=''157460''>the</span> <span m=''157540''>computer.</span>
  <span m=''158920''>I</span> <span m=''159030''>could</span> <span m=''160020''>walk</span>
  <span m=''160270''>up</span> <span m=''160390''>to</span> <span m=''160490''>this</span>
  <span m=''160660''>computer,</span> <span m=''161060''>and</span> <span m=''161150''>I</span>
  <span m=''161220''>could</span> <span m=''161380''>say--</span> <span m=''163400''>how</span>
  <span m=''163710''>about</span> <span m=''164770''>we''ll</span> <span m=''164910''>define</span>
  <span m=''167140''>the</span> <span m=''167300''>stream</span> <span m=''167760''>of</span>
  <span m=''167910''>integers</span> <span m=''171650''>starting</span> <span m=''172270''>with</span>
  <span m=''172400''>some</span> <span m=''172630''>number</span> <span m=''172930''>N,</span>
  <span m=''174070''>the</span> <span m=''174250''>stream</span> <span m=''174480''>of</span>
  <span m=''174560''>positive</span> <span m=''175010''>integers</span> <span m=''175820''>starting</span>
  <span m=''176170''>with</span> <span m=''176280''>some</span> <span m=''176460''>number</span>
  <span m=''176740''>n.</span> <span m=''179760''>And</span> <span m=''180210''>that''s</span>
  <span m=''182610''>cons-stream</span> <span m=''186820''>of</span> <span m=''187110''>n</span>
  <span m=''190090''>onto</span> <span m=''192540''>the</span> <span m=''192990''>integers</span>
  <span m=''195600''>from</span> <span m=''198490''>one</span> <span m=''198710''>more.</span>
  <span m=''204680''>So</span> <span m=''204780''>there</span> <span m=''204890''>are</span>
  <span m=''205160''>the</span> <span m=''205260''>integers.</span> </p><p><span m=''208800''>Then</span>
  <span m=''209320''>I</span> <span m=''209410''>could</span> <span m=''209550''>say</span>
  <span m=''210530''>let''s</span> <span m=''210660''>get</span> <span m=''210760''>all</span>
  <span m=''210880''>the</span> <span m=''211010''>integers.</span> <span m=''214410''>define</span>
  <span m=''216770''>the</span> <span m=''217290''>stream</span> <span m=''217630''>of</span>
  <span m=''217700''>integers</span> <span m=''221058''>to</span> <span m=''221500''>be</span>
  <span m=''221960''>the</span> <span m=''222060''>integers</span> <span m=''223330''>starting</span>
  <span m=''223790''>with</span> <span m=''223940''>1.</span> <span m=''228840''>And</span>
  <span m=''229210''>now</span> <span m=''229330''>if</span> <span m=''229430''>I</span>
  <span m=''229490''>say</span> <span m=''229680''>something</span> <span m=''230000''>like</span>
  <span m=''230220''>what''s</span> <span m=''230470''>the</span> <span m=''234680''>what''s</span>
  <span m=''234860''>the</span> <span m=''234950''>20th</span> <span m=''235380''>integer.</span>
  <span m=''242995''>So</span> <span m=''243480''>it''s</span> <span m=''243830''>21</span>
  <span m=''244350''>because</span> <span m=''244470''>we</span> <span m=''244550''>start</span>
  <span m=''244790''>counting at</span> <span m=''245140''>0.</span> </p><p><span
  m=''247270''>Or</span> <span m=''247410''>I</span> <span m=''247480''>can</span>
  <span m=''247620''>do</span> <span m=''247720''>more</span> <span m=''247870''>complicated</span>
  <span m=''248480''>things.</span> <span m=''249450''>Let</span> <span m=''249540''>me</span>
  <span m=''249630''>to</span> <span m=''249710''>define a</span> <span m=''249910''>little</span>
  <span m=''250100''>predicate</span> <span m=''250510''>here.</span> <span m=''253740''>How</span>
  <span m=''254030''>about</span> <span m=''254110''>define</span> <span m=''257769''>no-seven.</span>
  <span m=''259160''>It''s going to test</span> <span m=''259866''>an</span> <span
  m=''260220''>integer,</span> <span m=''261829''>and</span> <span m=''262070''>it''s
  going to</span> <span m=''262240''>say</span> <span m=''262530''>it''s</span> <span
  m=''262730''>not.</span> <span m=''268820''>I</span> <span m=''268940''>take</span>
  <span m=''269160''>the</span> <span m=''269250''>remainder</span> <span m=''271590''>of</span>
  <span m=''272680''>x</span> <span m=''273320''>by</span> <span m=''273450''>7,</span>
  <span m=''276690''>I</span> <span m=''276830''>don''t</span> <span m=''277120''>get</span>
  <span m=''277920''>0.</span> <span m=''281890''>And</span> <span m=''283720''>then</span>
  <span m=''284090''>I</span> <span m=''284170''>could</span> <span m=''284320''>say</span>
  <span m=''286180''>define</span> <span m=''287886''>the</span> <span m=''288320''>integers</span>
  <span m=''288930''>with</span> <span m=''289060''>no sevens</span> <span m=''290210''>to</span>
  <span m=''290360''>be,</span> <span m=''290630''>take</span> <span m=''290880''>all</span>
  <span m=''291070''>the integers</span> <span m=''292740''>and</span> <span m=''292940''>filter</span>
  <span m=''296460''>them</span> <span m=''298000''>to</span> <span m=''298220''>have</span>
  <span m=''298450''>no</span> <span m=''298600''>sevens.</span> </p><p><span m=''311570''>So</span>
  <span m=''311710''>now I''ve</span> <span m=''311880''>got</span> <span m=''312080''>the</span>
  <span m=''312220''>stream of</span> <span m=''312490''>all</span> <span m=''312650''>the</span>
  <span m=''312820''>integers</span> <span m=''313420''>that</span> <span m=''313800''>are</span>
  <span m=''313870''>not</span> <span m=''314060''>divisible</span> <span m=''314440''>by</span>
  <span m=''314580''>seven.</span> <span m=''316360''>So</span> <span m=''316620''>if</span>
  <span m=''316720''>I</span> <span m=''316770''>say</span> <span m=''316970''>what''s</span>
  <span m=''317230''>the</span> <span m=''322650''>100th</span> <span m=''323020''>integer</span>
  <span m=''324770''>and</span> <span m=''324890''>the</span> <span m=''325020''>list</span>
  <span m=''325250''>not</span> <span m=''325420''>divisible</span> <span m=''325770''>by</span>
  <span m=''325900''>seven,</span> <span m=''326240''>I</span> <span m=''326930''>get</span>
  <span m=''327000''>117.</span> <span m=''328320''>Or if I''d</span> <span m=''328720''>like</span>
  <span m=''328880''>to</span> <span m=''328980''>say</span> <span m=''332380''>well,</span>
  <span m=''332500''>gee,</span> <span m=''333470''>what</span> <span m=''333560''>are</span>
  <span m=''333660''>all</span> <span m=''333820''>of</span> <span m=''333990''>them?</span>
  <span m=''335270''>So</span> <span m=''335420''>I</span> <span m=''335480''>could</span>
  <span m=''335610''>say</span> <span m=''335770''>print</span> <span m=''337790''>stream</span>
  <span m=''338940''>all</span> <span m=''339100''>these</span> <span m=''339280''>integers</span>
  <span m=''339540''>with</span> <span m=''339670''>no</span> <span m=''339810''>seven,</span>
  <span m=''340570''>it</span> <span m=''340930''>goes</span> <span m=''341160''>off</span>
  <span m=''341310''>printing.</span> <span m=''345100''>You may</span> <span m=''345220''>have</span>
  <span m=''345360''>to</span> <span m=''345460''>wait a</span> <span m=''345730''>very</span>
  <span m=''345980''>long</span> <span m=''346210''>time</span> <span m=''346460''>to</span>
  <span m=''346510''>see</span> <span m=''346680''>them</span> <span m=''346840''>all.</span>
  </p><p><span m=''352670''>Well,</span> <span m=''352830''>you</span> <span m=''352930''>can</span>
  <span m=''353030''>start</span> <span m=''353240''>asking,</span> <span m=''353600''>gee,</span>
  <span m=''355080''>is</span> <span m=''355240''>it</span> <span m=''355340''>really</span>
  <span m=''355640''>true</span> <span m=''355870''>that</span> <span m=''356040''>this</span>
  <span m=''356200''>data</span> <span m=''356430''>structure</span> <span m=''358330''>with</span>
  <span m=''358470''>the integers</span> <span m=''358980''>is</span> <span m=''359080''>really</span>
  <span m=''359900''>all</span> <span m=''360090''>the</span> <span m=''360210''>integers?</span>
  <span m=''361100''>And</span> <span m=''361300''>let</span> <span m=''361360''>me</span>
  <span m=''361430''>draw</span> <span m=''361570''>a</span> <span m=''361620''>picture</span>
  <span m=''362480''>of</span> <span m=''362660''>that</span> <span m=''362830''>program</span>
  <span m=''363230''>I</span> <span m=''363300''>just</span> <span m=''363560''>wrote.</span>
  <span m=''368170''>Here''s</span> <span m=''368340''>the</span> <span m=''368410''>definition</span>
  <span m=''368830''>of</span> <span m=''368890''>the integers</span> <span m=''369350''>again</span>
  <span m=''369590''>that</span> <span m=''369690''>I</span> <span m=''369770''>just</span>
  <span m=''369980''>typed</span> <span m=''370280''>in,</span> <span m=''372410''>Right</span>
  <span m=''372600''>it''s</span> <span m=''372750''>a</span> <span m=''372810''>cons</span>
  <span m=''373650''>of</span> <span m=''373770''>the</span> <span m=''373970''>first</span>
  <span m=''374170''>integer</span> <span m=''374530''>under</span> <span m=''374690''>the</span>
  <span m=''374850''>integer</span> <span m=''375130''>starting</span> <span m=''375450''>with</span>
  <span m=''375580''>the</span> <span m=''375670''>rest.</span> <span m=''377680''>Now,</span>
  <span m=''377780''>we</span> <span m=''377860''>can</span> <span m=''377920''>make</span>
  <span m=''378060''>a</span> <span m=''378120''>picture</span> <span m=''378540''>of</span>
  <span m=''378670''>that</span> <span m=''378810''>and</span> <span m=''378930''>see</span>
  <span m=''379080''>what</span> <span m=''379190''>it</span> <span m=''379270''>looks</span>
  <span m=''379500''>like.</span> </p><p><span m=''382720''>Conceptually,</span> <span
  m=''383290''>what</span> <span m=''383390''>I</span> <span m=''383500''>have</span>
  <span m=''383750''>is</span> <span m=''383870''>a</span> <span m=''383910''>box</span>
  <span m=''385130''>that''s</span> <span m=''385460''>the</span> <span m=''385790''>integer</span>
  <span m=''386270''>starting</span> <span m=''386650''>with</span> <span m=''386760''>n.</span>
  <span m=''387420''>It</span> <span m=''387580''>takes</span> <span m=''387900''>in</span>
  <span m=''388070''>some</span> <span m=''388300''>number</span> <span m=''388600''>n,</span>
  <span m=''391540''>and</span> <span m=''391660''>it''s</span> <span m=''391790''>going</span>
  <span m=''391840''>to</span> <span m=''391900''>return</span> <span m=''392230''>a</span>
  <span m=''392260''>stream</span> <span m=''392760''>of--</span> <span m=''395050''>this</span>
  <span m=''395210''>infinite</span> <span m=''395600''>stream</span> <span m=''395920''>of</span>
  <span m=''396020''>all</span> <span m=''396160''>integers</span> <span m=''396520''>starting</span>
  <span m=''396870''>with</span> <span m=''396990''>n.</span> <span m=''397705''>And</span>
  <span m=''398100''>what</span> <span m=''398240''>do</span> <span m=''398390''>I</span>
  <span m=''398490''>do?</span> <span m=''398690''>Well,</span> <span m=''399510''>this</span>
  <span m=''399690''>is an</span> <span m=''399910''>integers</span> <span m=''401190''>from</span>
  <span m=''401990''>box.</span> <span m=''405070''>What''s</span> <span m=''405250''>it</span>
  <span m=''405340''>got</span> <span m=''405560''>in</span> <span m=''405690''>it?</span>
  <span m=''405800''>Well,</span> <span m=''407430''>it</span> <span m=''407550''>takes</span>
  <span m=''407810''>in</span> <span m=''407960''>this</span> <span m=''408140''>n,</span>
  <span m=''412250''>and</span> <span m=''412380''>it</span> <span m=''413190''>increments</span>
  <span m=''413710''>it.</span> <span m=''418030''>And</span> <span m=''418210''>then</span>
  <span m=''418660''>it</span> <span m=''418810''>puts</span> <span m=''419030''>the</span>
  <span m=''419110''>result</span> <span m=''419560''>into</span> <span m=''420290''>recursively</span>
  <span m=''421450''>another</span> <span m=''421920''>integer''s</span> <span m=''422360''>from</span>
  <span m=''422700''>box.</span> <span m=''426870''>It</span> <span m=''427080''>takes
  the</span> <span m=''427140''>result</span> <span m=''427500''>of</span> <span m=''427790''>that</span>
  <span m=''428570''>and</span> <span m=''428690''>the</span> <span m=''428810''>original</span>
  <span m=''429170''>n</span> <span m=''430020''>and</span> <span m=''430400''>puts</span>
  <span m=''430630''>those</span> <span m=''430830''>together</span> <span m=''432080''>with
  a</span> <span m=''432280''>cons</span> <span m=''433480''>and</span> <span m=''433580''>forms</span>
  <span m=''433890''>a</span> <span m=''433930''>stream.</span> <span m=''434270''>So</span>
  <span m=''434580''>that''s</span> <span m=''434850''>a</span> <span m=''434900''>picture</span>
  <span m=''435290''>of</span> <span m=''435360''>that</span> <span m=''435520''>program</span>
  <span m=''435930''>I</span> <span m=''436120''>wrote.</span> </p><p><span m=''438530''>Let''s</span>
  <span m=''438730''>see.</span> <span m=''438780''>These</span> <span m=''438940''>kind</span>
  <span m=''439120''>of</span> <span m=''439190''>diagrams</span> <span m=''439730''>we</span>
  <span m=''439830''>first</span> <span m=''440080''>saw</span> <span m=''440790''>drawn</span>
  <span m=''441000''>by</span> <span m=''441120''>Peter</span> <span m=''441380''>Henderson,</span>
  <span m=''441830''>the</span> <span m=''441890''>same</span> <span m=''442110''>guy</span>
  <span m=''442270''>who</span> <span m=''442360''>did</span> <span m=''442510''>the</span>
  <span m=''442630''>Escher</span> <span m=''442890''>language.</span> <span m=''443320''>We</span>
  <span m=''443440''>call</span> <span m=''443610''>them</span> <span m=''443710''>Henderson</span>
  <span m=''444150''>diagrams.</span> <span m=''445410''>And</span> <span m=''445520''>the</span>
  <span m=''445630''>convention</span> <span m=''446170''>here</span> <span m=''446410''>is</span>
  <span m=''446490''>that</span> <span m=''446630''>you</span> <span m=''446740''>put</span>
  <span m=''446900''>these</span> <span m=''447100''>things</span> <span m=''447320''>together.</span>
  <span m=''448530''>And</span> <span m=''449170''>the</span> <span m=''449410''>solid</span>
  <span m=''449840''>lines</span> <span m=''451090''>are</span> <span m=''451150''>things</span>
  <span m=''451420''>coming</span> <span m=''451700''>out</span> <span m=''451820''>are</span>
  <span m=''451890''>streams,</span> <span m=''453040''>and</span> <span m=''453260''>dotted</span>
  <span m=''453580''>lines</span> <span m=''454710''>are</span> <span m=''454870''>initial</span>
  <span m=''455290''>values</span> <span m=''455760''>going</span> <span m=''456070''>in.</span>
  <span m=''457270''>So</span> <span m=''457450''>this</span> <span m=''457620''>one</span>
  <span m=''458090''>has</span> <span m=''458310''>the</span> <span m=''458380''>shape</span>
  <span m=''458790''>of--</span> <span m=''459440''>it</span> <span m=''459590''>takes</span>
  <span m=''459860''>in</span> <span m=''459950''>some</span> <span m=''460170''>integer,</span>
  <span m=''460660''>some</span> <span m=''460830''>initial</span> <span m=''461130''>value,</span>
  <span m=''461820''>and</span> <span m=''461990''>outputs</span> <span m=''462370''>a</span>
  <span m=''462410''>stream.</span> </p><p><span m=''466410''>Again,</span> <span
  m=''466710''>you</span> <span m=''466800''>can</span> <span m=''466930''>ask.</span>
  <span m=''468380''>Is</span> <span m=''468520''>that</span> <span m=''468700''>data</span>
  <span m=''468930''>structure</span> <span m=''469300''>integers</span> <span m=''469710''>really</span>
  <span m=''470050''>all</span> <span m=''470230''>the</span> <span m=''470470''>integers?</span>
  <span m=''472340''>Or</span> <span m=''472470''>is</span> <span m=''472590''>it</span>
  <span m=''473040''>is</span> <span m=''473500''>something</span> <span m=''473810''>that''s</span>
  <span m=''474020''>cleverly</span> <span m=''474580''>arranged</span> <span m=''474930''>so</span>
  <span m=''475050''>that</span> <span m=''475190''>whenever</span> <span m=''475480''>you</span>
  <span m=''475690''>look</span> <span m=''475970''>for</span> <span m=''476100''>an</span>
  <span m=''476180''>integer</span> <span m=''476500''>you</span> <span m=''476630''>find</span>
  <span m=''476920''>it</span> <span m=''477030''>there?</span> <span m=''478190''>That''s</span>
  <span m=''478360''>sort</span> <span m=''478520''>of</span> <span m=''478590''>a</span>
  <span m=''478650''>philosophical</span> <span m=''479310''>question,</span> <span
  m=''479640''>right?</span> <span m=''479780''>If</span> <span m=''479840''>something</span>
  <span m=''481200''>is</span> <span m=''481340''>there</span> <span m=''482150''>whenever</span>
  <span m=''482470''>you</span> <span m=''482650''>look,</span> <span m=''482860''>is</span>
  <span m=''482990''>it</span> <span m=''483090''>really</span> <span m=''483350''>there</span>
  <span m=''483580''>or</span> <span m=''483620''>not?</span> <span m=''484450''>It''s</span>
  <span m=''484860''>sort of</span> <span m=''484980''>the</span> <span m=''486230''>same</span>
  <span m=''486480''>sense</span> <span m=''486750''>in</span> <span m=''486820''>which</span>
  <span m=''487310''>the</span> <span m=''487400''>money</span> <span m=''487740''>in</span>
  <span m=''487830''>your</span> <span m=''487970''>savings</span> <span m=''488390''>account</span>
  <span m=''488710''>is</span> <span m=''488810''>in</span> <span m=''488900''>the</span>
  <span m=''488990''>bank.</span> </p><p><span m=''492380''>Well,</span> <span m=''496400''>let</span>
  <span m=''496510''>me</span> <span m=''496620''>do</span> <span m=''496730''>another</span>
  <span m=''497040''>example.</span> <span m=''499830''>Gee,</span> <span m=''499970''>we</span>
  <span m=''500060''>started</span> <span m=''500390''>the</span> <span m=''500460''>course</span>
  <span m=''500720''>with</span> <span m=''500840''>an</span> <span m=''500930''>algorithm</span>
  <span m=''501820''>from</span> <span m=''502040''>Alexandria,</span> <span m=''503340''>which</span>
  <span m=''503530''>was</span> <span m=''504210''>Heron</span> <span m=''504550''>of</span>
  <span m=''504640''>Alexandria''s</span> <span m=''505290''>algorithm</span> <span
  m=''505790''>for</span> <span m=''505910''>computing the</span> <span m=''506330''>square</span>
  <span m=''506760''>root.</span> <span m=''508470''>Let''s</span> <span m=''509230''>take</span>
  <span m=''509370''>a</span> <span m=''509650''>look</span> <span m=''509780''>at</span>
  <span m=''509910''>another</span> <span m=''510890''>Alexandrian</span> <span m=''511570''>algorithm.</span>
  <span m=''512030''>This</span> <span m=''512159''>one</span> <span m=''512330''>is</span>
  <span m=''512890''>Eratosthenes</span> <span m=''514400''>method</span> <span m=''514809''>for</span>
  <span m=''516510''>computing</span> <span m=''517490''>all</span> <span m=''517780''>of</span>
  <span m=''517860''>the</span> <span m=''517950''>primes.</span> <span m=''521169''>It</span>
  <span m=''521320''>is</span> <span m=''521520''>called</span> <span m=''521659''>the</span>
  <span m=''521730''>Sieve</span> <span m=''522009''>of</span> <span m=''522289''>Eratosthenes.</span>
  <span m=''522830''>And</span> <span m=''522900''>what</span> <span m=''523049''>you</span>
  <span m=''523159''>do</span> <span m=''524090''>is</span> <span m=''524280''>you</span>
  <span m=''529190''>start</span> <span m=''529550''>out,</span> <span m=''531080''>and</span>
  <span m=''531210''>you</span> <span m=''531330''>list</span> <span m=''531530''>all</span>
  <span m=''531680''>the</span> <span m=''531830''>integers,</span> <span m=''532560''>say,</span>
  <span m=''532750''>starting</span> <span m=''533090''>with</span> <span m=''533240''>2.</span>
  <span m=''533880''>And then</span> <span m=''534000''>you</span> <span m=''534120''>take</span>
  <span m=''534300''>the</span> <span m=''534490''>first</span> <span m=''534680''>integer,</span>
  <span m=''535020''>and you</span> <span m=''535170''>say,</span> <span m=''535780''>oh,</span>
  <span m=''535890''>that''s</span> <span m=''536130''>prime.</span> <span m=''537310''>And</span>
  <span m=''537420''>then</span> <span m=''537530''>you go</span> <span m=''537710''>look</span>
  <span m=''537820''>at</span> <span m=''537940''>the</span> <span m=''538040''>rest,</span>
  <span m=''538740''>and</span> <span m=''538880''>you</span> <span m=''538960''>cross</span>
  <span m=''539310''>out</span> <span m=''539460''>all</span> <span m=''539600''>the</span>
  <span m=''539690''>things</span> <span m=''539940''>divisible</span> <span m=''540360''>by</span>
  <span m=''540610''>2.</span> <span m=''541230''>So</span> <span m=''541590''>I</span>
  <span m=''541730''>cross</span> <span m=''542060''>out</span> <span m=''542250''>this</span>
  <span m=''543000''>and</span> <span m=''543320''>this</span> <span m=''543755''>and</span>
  <span m=''544190''>this.</span> <span m=''545250''>This</span> <span m=''545430''>takes</span>
  <span m=''545660''>a</span> <span m=''545710''>long</span> <span m=''545960''>time</span>
  <span m=''546290''>because</span> <span m=''546480''>I</span> <span m=''546550''>have</span>
  <span m=''546690''>to</span> <span m=''546790''>do</span> <span m=''546950''>it</span>
  <span m=''547260''>for</span> <span m=''547990''>all</span> <span m=''548140''>of</span>
  <span m=''548290''>the</span> <span m=''548520''>integers.</span> <span m=''551160''>So</span>
  <span m=''551930''>I</span> <span m=''552080''>go</span> <span m=''552230''>through</span>
  <span m=''552380''>the</span> <span m=''552500''>entire</span> <span m=''554360''>list</span>
  <span m=''554655''>of</span> <span m=''554950''>integers,</span> <span m=''558390''>crossing</span>
  <span m=''559130''>the</span> <span m=''559680''>ones</span> <span m=''559870''>divisible</span>
  <span m=''560280''>by</span> <span m=''560470''>2.</span> </p><p><span m=''562010''>And</span>
  <span m=''562330''>now</span> <span m=''562450''>when</span> <span m=''562570''>I</span>
  <span m=''562640''>finish</span> <span m=''563220''>with</span> <span m=''563430''>all</span>
  <span m=''563750''>of the</span> <span m=''563960''>integers,</span> <span m=''564750''>I</span>
  <span m=''564890''>go</span> <span m=''565030''>back</span> <span m=''565280''>and</span>
  <span m=''565400''>look</span> <span m=''565610''>and</span> <span m=''565690''>say</span>
  <span m=''565820''>what</span> <span m=''565990''>am</span> <span m=''566110''>I</span>
  <span m=''566180''>left</span> <span m=''566510''>with?</span> <span m=''567040''>Well,</span>
  <span m=''567200''>the</span> <span m=''567370''>first</span> <span m=''567550''>thing</span>
  <span m=''567670''>that</span> <span m=''567810''>starts</span> <span m=''568130''>there
  is</span> <span m=''568460''>3.</span> <span m=''569330''>So</span> <span m=''569510''>3
  is</span> <span m=''569740''>a prime.</span> <span m=''570770''>And</span> <span
  m=''570900''>now</span> <span m=''571030''>I</span> <span m=''571100''>go</span>
  <span m=''571250''>back</span> <span m=''571990''>through</span> <span m=''572290''>what</span>
  <span m=''572440''>I''m</span> <span m=''572600''>left</span> <span m=''572890''>with,</span>
  <span m=''573370''>and</span> <span m=''573490''>I</span> <span m=''573530''>cross</span>
  <span m=''573850''>out</span> <span m=''573950''>all</span> <span m=''574050''>the</span>
  <span m=''574140''>things</span> <span m=''574370''>divisible</span> <span m=''574670''>by</span>
  <span m=''574820''>3.</span> <span m=''575120''>So</span> <span m=''575270''>let''s</span>
  <span m=''575450''>see,</span> <span m=''575560''>9</span> <span m=''576960''>and</span>
  <span m=''577210''>15</span> <span m=''578590''>and</span> <span m=''578910''>21</span>
  <span m=''580070''>and</span> <span m=''580490''>27</span> <span m=''581300''>and</span>
  <span m=''581450''>33</span> <span m=''583090''>and</span> <span m=''583240''>so</span>
  <span m=''583480''>on.</span> <span m=''584050''>I</span> <span m=''584370''>won''t</span>
  <span m=''584650''>finish.</span> <span m=''585350''>Then</span> <span m=''585590''>I
  see what</span> <span m=''585690''>I''m</span> <span m=''585880''>left</span> <span
  m=''586160''>with.</span> <span m=''587250''>And</span> <span m=''588250''>the</span>
  <span m=''588600''>next</span> <span m=''588850''>one</span> <span m=''588950''>I</span>
  <span m=''589010''>have</span> <span m=''589120''>is</span> <span m=''589310''>5.</span>
  <span m=''590860''>Now</span> <span m=''590980''>I</span> <span m=''591070''>can</span>
  <span m=''591490''>through</span> <span m=''591610''>the</span> <span m=''591720''>rest,</span>
  <span m=''592460''>and</span> <span m=''592620''>I</span> <span m=''592700''>find</span>
  <span m=''592960''>the</span> <span m=''593020''>first</span> <span m=''593330''>one</span>
  <span m=''593470''>that''s</span> <span m=''593670''>divisible</span> <span m=''594010''>by</span>
  <span m=''594140''>5.</span> <span m=''594540''>I cross</span> <span m=''594850''>out</span>
  <span m=''595190''>from</span> <span m=''595330''>the</span> <span m=''595470''>remainder</span>
  <span m=''595940''>all</span> <span m=''596050''>the</span> <span m=''596160''>ones
  that</span> <span m=''596390''>are</span> <span m=''596590''>divisible</span> <span
  m=''596910''>by</span> <span m=''597050''>5.</span> <span m=''598030''>And</span>
  <span m=''598480''>I</span> <span m=''598610''>do</span> <span m=''598770''>that,</span>
  <span m=''599870''>and</span> <span m=''600030''>then</span> <span m=''600140''>I</span>
  <span m=''600220''>go</span> <span m=''600370''>through</span> <span m=''600850''>and</span>
  <span m=''601000''>find</span> <span m=''601360''>7.</span> <span m=''601890''>Go</span>
  <span m=''602030''>through</span> <span m=''602210''>all</span> <span m=''602390''>the</span>
  <span m=''602480''>rest,</span> <span m=''602740''>cross</span> <span m=''603000''>out</span>
  <span m=''603130''>things</span> <span m=''603350''>divisible</span> <span m=''603770''>7,
  and</span> <span m=''604100''>I</span> <span m=''604170''>keep</span> <span m=''604440''>doing</span>
  <span m=''604700''>that</span> <span m=''604880''>forever.</span> <span m=''606810''>And</span>
  <span m=''606920''>when</span> <span m=''607030''>I''m</span> <span m=''607140''>done,</span>
  <span m=''607360''>what</span> <span m=''607480''>I''m</span> <span m=''607580''>left</span>
  <span m=''607800''>with</span> <span m=''607930''>is</span> <span m=''608050''>a</span>
  <span m=''608100''>list</span> <span m=''608340''>of</span> <span m=''608440''>all</span>
  <span m=''608550''>the</span> <span m=''608620''>primes.</span> <span m=''610120''>So</span>
  <span m=''610240''>that''s</span> <span m=''610470''>the</span> <span m=''612030''>Sieve</span>
  <span m=''612440''>of</span> <span m=''612620''>Eratosthenes.</span> </p><p><span
  m=''615430''>Let''s</span> <span m=''615590''>look</span> <span m=''615750''>at</span>
  <span m=''615900''>it</span> <span m=''615990''>as</span> <span m=''616140''>a</span>
  <span m=''616820''>computer</span> <span m=''617170''>program.</span> <span m=''617930''>It''s</span>
  <span m=''618090''>a</span> <span m=''618130''>procedure</span> <span m=''619130''>called</span>
  <span m=''619350''>sieve.</span> <span m=''627910''>Now, I</span> <span m=''628090''>just</span>
  <span m=''628300''>write</span> <span m=''628770''>what</span> <span m=''628950''>I</span>
  <span m=''629050''>did.</span> <span m=''630480''>I''ll</span> <span m=''630690''>say</span>
  <span m=''630890''>to</span> <span m=''631060''>sieve</span> <span m=''633400''>some</span>
  <span m=''633680''>stream</span> <span m=''634080''>s.</span> <span m=''638770''>I''m</span>
  <span m=''638940''>going</span> <span m=''639000''>to</span> <span m=''639060''>build</span>
  <span m=''639300''>a</span> <span m=''639330''>stream</span> <span m=''640290''>whose</span>
  <span m=''640540''>first</span> <span m=''640810''>element</span> <span m=''641110''>is</span>
  <span m=''641200''>the</span> <span m=''641280''>head</span> <span m=''641500''>of</span>
  <span m=''641560''>this.</span> <span m=''641870''>Remember,</span> <span m=''642050''>I</span>
  <span m=''642730''>always</span> <span m=''642990''>found</span> <span m=''643160''>the</span>
  <span m=''643220''>first</span> <span m=''643500''>thing</span> <span m=''643640''>I</span>
  <span m=''643700''>was</span> <span m=''643880''>left</span> <span m=''644150''>with,</span>
  <span m=''644930''>and</span> <span m=''645080''>the</span> <span m=''645170''>rest</span>
  <span m=''645460''>of</span> <span m=''645560''>it</span> <span m=''645710''>is</span>
  <span m=''645880''>the</span> <span m=''645980''>result</span> <span m=''646450''>of</span>
  <span m=''647450''>taking</span> <span m=''647860''>the</span> <span m=''647940''>tail</span>
  <span m=''648220''>of</span> <span m=''648480''>this,</span> <span m=''650820''>filtering</span>
  <span m=''651550''>it</span> <span m=''652730''>to</span> <span m=''652880''>throw</span>
  <span m=''653170''>away</span> <span m=''653360''>all</span> <span m=''653550''>the</span>
  <span m=''653640''>things</span> <span m=''653910''>that are</span> <span m=''654030''>divisible</span>
  <span m=''654560''>by</span> <span m=''654690''>the</span> <span m=''654760''>head</span>
  <span m=''654960''>of</span> <span m=''655000''>this,</span> <span m=''656510''>and</span>
  <span m=''656640''>now</span> <span m=''656750''>sieving</span> <span m=''657090''>the</span>
  <span m=''657170''>result.</span> <span m=''659020''>That''s</span> <span m=''659360''>just</span>
  <span m=''659540''>what</span> <span m=''659620''>I</span> <span m=''659710''>did.</span>
  </p><p><span m=''661980''>And</span> <span m=''662130''>now</span> <span m=''662430''>to</span>
  <span m=''662720''>get</span> <span m=''662890''>the</span> <span m=''663110''>infinite</span>
  <span m=''663720''>stream</span> <span m=''664040''>of</span> <span m=''664150''>times,</span>
  <span m=''665060''>we</span> <span m=''665180''>just</span> <span m=''665360''>sieve
  all</span> <span m=''665760''>the</span> <span m=''665870''>integers</span> <span
  m=''666190''>starting</span> <span m=''666530''>from</span> <span m=''666680''>2.</span>
  <span m=''674920''>Let''s</span> <span m=''675070''>try</span> <span m=''675250''>that.</span>
  <span m=''676300''>We</span> <span m=''676590''>can</span> <span m=''676720''>actually</span>
  <span m=''677840''>do</span> <span m=''678050''>it.</span> <span m=''679760''>I</span>
  <span m=''679930''>typed in</span> <span m=''680270''>the</span> <span m=''680350''>definition</span>
  <span m=''680820''>of</span> <span m=''680890''>sieve</span> <span m=''681150''>before,</span>
  <span m=''681700''>I</span> <span m=''681830''>hope,</span> <span m=''682830''>so</span>
  <span m=''682990''>I</span> <span m=''683050''>can</span> <span m=''683170''>say</span>
  <span m=''683370''>something</span> <span m=''683750''>like</span> <span m=''685010''>define</span>
  <span m=''687070''>the</span> <span m=''687600''>primes</span> <span m=''692380''>to</span>
  <span m=''692960''>be</span> <span m=''694740''>the</span> <span m=''694840''>result</span>
  <span m=''695240''>of</span> <span m=''695340''>sieving</span> <span m=''698040''>the</span>
  <span m=''698440''>integers</span> <span m=''700330''>starting</span> <span m=''700840''>with</span>
  <span m=''701050''>2.</span> <span m=''706760''>So</span> <span m=''706870''>now
  I''ve</span> <span m=''707040''>got</span> <span m=''707310''>this</span> <span
  m=''707480''>list</span> <span m=''707730''>of</span> <span m=''707810''>primes.</span>
  <span m=''708100''>That''s</span> <span m=''708270''>all</span> <span m=''708560''>of</span>
  <span m=''708650''>the</span> <span m=''708750''>primes,</span> <span m=''710730''>right?</span>
  <span m=''710990''>So,</span> <span m=''711180''>if</span> <span m=''711490''>for</span>
  <span m=''711670''>example,</span> <span m=''711980''>what''s</span> <span m=''712170''>the</span>
  <span m=''712250''>20th</span> <span m=''712650''>prime</span> <span m=''712960''>in</span>
  <span m=''713030''>that</span> <span m=''713190''>list?</span> <span m=''721010''>73.</span>
  <span m=''722540''>See, and</span> <span m=''722670''>that</span> <span m=''722820''>little</span>
  <span m=''723000''>pause,</span> <span m=''723990''>it</span> <span m=''724090''>was</span>
  <span m=''724200''>only</span> <span m=''724510''>at</span> <span m=''724590''>the</span>
  <span m=''724670''>point</span> <span m=''724910''>when</span> <span m=''725030''>I</span>
  <span m=''725080''>started</span> <span m=''725360''>asking</span> <span m=''725600''>for</span>
  <span m=''725690''>the</span> <span m=''725790''>20th</span> <span m=''726150''>prime</span>
  <span m=''726420''>is</span> <span m=''726500''>that</span> <span m=''726610''>it</span>
  <span m=''726730''>started</span> <span m=''727050''>computing.</span> <span m=''730370''>Or</span>
  <span m=''730480''>I</span> <span m=''730580''>can</span> <span m=''730730''>say</span>
  <span m=''730970''>here</span> <span m=''733850''>let''s</span> <span m=''734020''>look</span>
  <span m=''734140''>at</span> <span m=''734190''>all of</span> <span m=''734340''>the</span>
  <span m=''734490''>primes.</span> <span m=''742780''>And</span> <span m=''742840''>there</span>
  <span m=''742920''>it</span> <span m=''743100''>goes</span> <span m=''743290''>computing</span>
  <span m=''743630''>all of</span> <span m=''743800''>the</span> <span m=''743970''>primes.</span>
  <span m=''745350''>Of course,</span> <span m=''745540''>it will</span> <span m=''745620''>take</span>
  <span m=''745850''>a</span> <span m=''745890''>while</span> <span m=''746220''>again</span>
  <span m=''746530''>if</span> <span m=''746650''>I</span> <span m=''746670''>want</span>
  <span m=''746770''>to</span> <span m=''746870''>look</span> <span m=''746970''>at</span>
  <span m=''747080''>all</span> <span m=''747260''>of</span> <span m=''747380''>them,</span>
  <span m=''747520''>so</span> <span m=''747790''>let''s</span> <span m=''748010''>stop</span>
  <span m=''748380''>it.</span> </p><p><span m=''752030''>Let</span> <span m=''752110''>me</span>
  <span m=''752200''>draw you</span> <span m=''752310''>a</span> <span m=''752430''>picture
  of</span> <span m=''752830''>that.</span> <span m=''753130''>Well, I''ve</span>
  <span m=''753280''>got</span> <span m=''753460''>a</span> <span m=''753510''>picture</span>
  <span m=''753850''>of</span> <span m=''753910''>that.</span> <span m=''754890''>What''s</span>
  <span m=''755050''>that</span> <span m=''755180''>program</span> <span m=''755470''>really</span>
  <span m=''755690''>look</span> <span m=''755890''>like?</span> <span m=''757900''>Again,</span>
  <span m=''758050''>some</span> <span m=''758230''>practice</span> <span m=''758670''>with</span>
  <span m=''758790''>these</span> <span m=''758960''>diagrams,</span> <span m=''759490''>I</span>
  <span m=''759550''>have</span> <span m=''759640''>a</span> <span m=''759730''>sieve</span>
  <span m=''760070''>box.</span> <span m=''762610''>How</span> <span m=''762740''>does</span>
  <span m=''762850''>sieve</span> <span m=''763160''>work?</span> <span m=''763560''>It</span>
  <span m=''763710''>takes</span> <span m=''763950''>in</span> <span m=''764050''>a</span>
  <span m=''764090''>stream.</span> <span m=''768850''>It</span> <span m=''769010''>splits</span>
  <span m=''769420''>off</span> <span m=''769610''>the</span> <span m=''769700''>head</span>
  <span m=''769930''>from</span> <span m=''770060''>the</span> <span m=''770140''>tail.</span>
  <span m=''770870''>And</span> <span m=''770960''>the</span> <span m=''771060''>first</span>
  <span m=''771400''>thing</span> <span m=''771750''>that''s</span> <span m=''772240''>going</span>
  <span m=''772310''>to</span> <span m=''772380''>come</span> <span m=''772540''>out</span>
  <span m=''772740''>of</span> <span m=''772840''>the</span> <span m=''772920''>sieve</span>
  <span m=''773500''>is</span> <span m=''773660''>the</span> <span m=''773730''>head</span>
  <span m=''773960''>of</span> <span m=''774030''>the</span> <span m=''774150''>original</span>
  <span m=''774480''>stream.</span> <span m=''777796''>Then</span> <span m=''778270''>it</span>
  <span m=''778450''>also</span> <span m=''778720''>takes</span> <span m=''779020''>the</span>
  <span m=''779100''>head</span> <span m=''779860''>and</span> <span m=''780030''>uses</span>
  <span m=''780460''>that.</span> <span m=''782550''>It</span> <span m=''782750''>takes</span>
  <span m=''782940''>the</span> <span m=''783010''>stream.</span> <span m=''783850''>It</span>
  <span m=''784250''>filters</span> <span m=''784590''>the</span> <span m=''784680''>tail</span>
  <span m=''785650''>and</span> <span m=''785800''>uses</span> <span m=''786050''>the</span>
  <span m=''786140''>head</span> <span m=''786540''>to</span> <span m=''786820''>filter</span>
  <span m=''787150''>for</span> <span m=''787290''>nondivisibility.</span> <span m=''789152''>It</span>
  <span m=''789620''>takes</span> <span m=''789870''>the</span> <span m=''789930''>result</span>
  <span m=''790260''>of</span> <span m=''790330''>nondivisibility</span> <span m=''791280''>and</span>
  <span m=''791440''>puts</span> <span m=''791630''>it</span> <span m=''791710''>through</span>
  <span m=''792210''>another</span> <span m=''792470''>sieve</span> <span m=''792680''>box</span>
  <span m=''794000''>and</span> <span m=''794140''>puts</span> <span m=''794320''>the
  result</span> <span m=''794520''>together.</span> <span m=''795130''>So</span> <span
  m=''795280''>you</span> <span m=''795410''>can</span> <span m=''795540''>think</span>
  <span m=''795720''>of</span> <span m=''795820''>this</span> <span m=''796060''>sieve</span>
  <span m=''796330''>a</span> <span m=''796380''>filter,</span> <span m=''797170''>but</span>
  <span m=''797340''>notice</span> <span m=''797620''>that</span> <span m=''797750''>it''s</span>
  <span m=''797890''>an</span> <span m=''797980''>infinitely</span> <span m=''798490''>recursive</span>
  <span m=''798840''>filter.</span> <span m=''799650''>Because</span> <span m=''799780''>inside</span>
  <span m=''800160''>the</span> <span m=''800220''>sieve</span> <span m=''800430''>box</span>
  <span m=''801540''>is</span> <span m=''801690''>another</span> <span m=''801980''>sieve</span>
  <span m=''802200''>box,</span> <span m=''803420''>and</span> <span m=''803560''>inside</span>
  <span m=''803870''>that</span> <span m=''804040''>is</span> <span m=''804140''>another</span>
  <span m=''804450''>sieve</span> <span m=''804660''>box</span> <span m=''804980''>and</span>
  <span m=''805040''>another</span> <span m=''805310''>sieve</span> <span m=''805490''>box.</span>
  </p><p><span m=''807130''>So</span> <span m=''807330''>you see</span> <span m=''807460''>we</span>
  <span m=''807550''>start</span> <span m=''807780''>getting</span> <span m=''807950''>some</span>
  <span m=''808090''>very</span> <span m=''808290''>powerful</span> <span m=''808760''>things.</span>
  <span m=''808960''>We''re</span> <span m=''809050''>starting</span> <span m=''809310''>to</span>
  <span m=''809430''>mix</span> <span m=''810410''>this</span> <span m=''811040''>signal</span>
  <span m=''811440''>processing</span> <span m=''812020''>view</span> <span m=''812220''>of</span>
  <span m=''812300''>the</span> <span m=''812390''>world</span> <span m=''813900''>with</span>
  <span m=''814260''>things</span> <span m=''814490''>like</span> <span m=''814660''>recursion</span>
  <span m=''815340''>that</span> <span m=''815470''>come</span> <span m=''815620''>from</span>
  <span m=''815760''>computation.</span> <span m=''816690''>And</span> <span m=''817056''>there</span>
  <span m=''817422''>are</span> <span m=''817790''>all</span> <span m=''818010''>sorts</span>
  <span m=''818240''>of</span> <span m=''818290''>interesting</span> <span m=''818660''>things</span>
  <span m=''818870''>you</span> <span m=''818970''>can</span> <span m=''819080''>do</span>
  <span m=''819210''>that</span> <span m=''819330''>are</span> <span m=''819390''>like</span>
  <span m=''819670''>this.</span> <span m=''820970''>All right,</span> <span m=''821330''>any</span>
  <span m=''821490''>questions?</span> <span m=''828190''>OK,</span> <span m=''828450''>let''s</span>
  <span m=''828610''>take</span> <span m=''828750''>a</span> <span m=''828780''>break.</span>
  </p><p><span m=''868820''>Well,</span> <span m=''868970''>we''ve</span> <span m=''869110''>been</span>
  <span m=''869260''>looking</span> <span m=''869990''>at</span> <span m=''870090''>a</span>
  <span m=''870200''>couple</span> <span m=''870480''>of</span> <span m=''870570''>examples</span>
  <span m=''871050''>of</span> <span m=''871130''>stream</span> <span m=''871440''>programming.</span>
  <span m=''874790''>All</span> <span m=''876900''>the</span> <span m=''877020''>stream</span>
  <span m=''877320''>procedures</span> <span m=''878240''>that</span> <span m=''878360''>we''ve</span>
  <span m=''878490''>looked</span> <span m=''878690''>at</span> <span m=''878830''>so</span>
  <span m=''879040''>far</span> <span m=''879770''>have</span> <span m=''879920''>the</span>
  <span m=''879990''>same</span> <span m=''880250''>kind</span> <span m=''880510''>of</span>
  <span m=''880780''>character.</span> <span m=''881490''>We''ve been</span> <span
  m=''881680''>writing</span> <span m=''882000''>these</span> <span m=''882500''>recursive</span>
  <span m=''883000''>procedures</span> <span m=''884170''>that</span> <span m=''884340''>kind</span>
  <span m=''884470''>of</span> <span m=''884600''>generate</span> <span m=''885180''>these</span>
  <span m=''885300''>stream</span> <span m=''885620''>elements</span> <span m=''885980''>one</span>
  <span m=''886150''>at</span> <span m=''886220''>a</span> <span m=''886290''>time</span>
  <span m=''886580''>and</span> <span m=''886670''>put</span> <span m=''886820''>them</span>
  <span m=''886940''>together</span> <span m=''887300''>in</span> <span m=''888000''>cons-streams.</span>
  <span m=''889090''>So</span> <span m=''889260''>we''ve</span> <span m=''889380''>been</span>
  <span m=''889480''>thinking</span> <span m=''889770''>a</span> <span m=''889820''>lot</span>
  <span m=''890030''>about</span> <span m=''890280''>generators.</span> <span m=''891000''>There''s</span>
  <span m=''891170''>another</span> <span m=''891530''>way</span> <span m=''891990''>to</span>
  <span m=''892340''>think</span> <span m=''892530''>about</span> <span m=''892640''>stream</span>
  <span m=''893010''>processing,</span> <span m=''893820''>and</span> <span m=''893970''>that''s</span>
  <span m=''894130''>to</span> <span m=''894240''>focus</span> <span m=''895330''>not</span>
  <span m=''895570''>on</span> <span m=''896090''>programs</span> <span m=''896530''>that</span>
  <span m=''896640''>sort</span> <span m=''896820''>of</span> <span m=''897400''>process</span>
  <span m=''897840''>these</span> <span m=''898000''>elements</span> <span m=''898530''>as</span>
  <span m=''898710''>you</span> <span m=''898830''>walk</span> <span m=''899060''>down</span>
  <span m=''899260''>the</span> <span m=''899320''>stream,</span> <span m=''900250''>but</span>
  <span m=''900420''>on</span> <span m=''900550''>things</span> <span m=''900840''>that</span>
  <span m=''902840''>kind</span> <span m=''903010''>of</span> <span m=''904210''>process</span>
  <span m=''904740''>the streams</span> <span m=''905040''>all</span> <span m=''905230''>at</span>
  <span m=''905300''>once.</span> </p><p><span m=''907350''>To</span> <span m=''907440''>show</span>
  <span m=''907580''>you</span> <span m=''907680''>what</span> <span m=''907780''>I</span>
  <span m=''907830''>mean,</span> <span m=''908220''>let</span> <span m=''908360''>me</span>
  <span m=''908440''>start</span> <span m=''908680''>by</span> <span m=''908780''>defining</span>
  <span m=''909180''>two</span> <span m=''909950''>procedures</span> <span m=''910480''>that</span>
  <span m=''910580''>will</span> <span m=''910680''>come</span> <span m=''910860''>in</span>
  <span m=''910950''>handy.</span> <span m=''912410''>The</span> <span m=''912490''>first</span>
  <span m=''912700''>one''s</span> <span m=''912860''>called</span> <span m=''913060''>add</span>
  <span m=''913310''>streams.</span> <span m=''915450''>Add</span> <span m=''915660''>streams</span>
  <span m=''915980''>takes</span> <span m=''917440''>two</span> <span m=''917580''>streams:</span>
  <span m=''918850''>s1</span> <span m=''920040''>and</span> <span m=''920190''>s2.</span>
  <span m=''922330''>and.</span> <span m=''922460''>It''s</span> <span m=''922580''>going</span>
  <span m=''922660''>to</span> <span m=''922750''>produce</span> <span m=''923910''>a</span>
  <span m=''924030''>stream</span> <span m=''924920''>whose</span> <span m=''925160''>elements</span>
  <span m=''925550''>are</span> <span m=''925620''>the</span> <span m=''926780''>are</span>
  <span m=''926900''>the</span> <span m=''927240''>corresponding</span> <span m=''927730''>sums.</span>
  <span m=''930380''>We</span> <span m=''930480''>just sort of</span> <span m=''930860''>add</span>
  <span m=''931110''>them</span> <span m=''931230''>element-wise.</span> <span m=''932970''>If</span>
  <span m=''933120''>either</span> <span m=''933360''>stream</span> <span m=''933620''>is</span>
  <span m=''933720''>empty,</span> <span m=''934040''>we</span> <span m=''934160''>just</span>
  <span m=''934350''>return</span> <span m=''934640''>the</span> <span m=''934760''>other</span>
  <span m=''934940''>one.</span> <span m=''936810''>Otherwise,</span> <span m=''937810''>we''re</span>
  <span m=''938010''>going</span> <span m=''938060''>to</span> <span m=''938120''>make</span>
  <span m=''938290''>a new</span> <span m=''938440''>stream</span> <span m=''939700''>whose</span>
  <span m=''941160''>head</span> <span m=''941760''>is</span> <span m=''941930''>the</span>
  <span m=''942000''>sum</span> <span m=''942220''>of</span> <span m=''942270''>the</span>
  <span m=''942350''>two</span> <span m=''942530''>heads</span> <span m=''943960''>and</span>
  <span m=''944160''>whose</span> <span m=''944370''>tail</span> <span m=''946080''>is</span>
  <span m=''946240''>the</span> <span m=''946320''>result</span> <span m=''946760''>of</span>
  <span m=''946890''>recursively</span> <span m=''948020''>adding the tails.</span>
  <span m=''950090''>So</span> <span m=''950260''>that</span> <span m=''950290''>will</span>
  <span m=''950440''>produce</span> <span m=''950730''>the</span> <span m=''950830''>element-wise</span>
  <span m=''951510''>sum</span> <span m=''951830''>of</span> <span m=''951930''>two</span>
  <span m=''952100''>streams.</span> </p><p><span m=''953150''>And</span> <span m=''953310''>then</span>
  <span m=''953470''>another</span> <span m=''953760''>useful</span> <span m=''954120''>thing</span>
  <span m=''955400''>to</span> <span m=''955610''>have</span> <span m=''955830''>around</span>
  <span m=''956150''>is</span> <span m=''956190''>scale</span> <span m=''956640''>stream.</span>
  <span m=''957500''>Scale</span> <span m=''957880''>stream</span> <span m=''959600''>takes</span>
  <span m=''959870''>some</span> <span m=''960040''>constant</span> <span m=''960510''>number</span>
  <span m=''960820''>in</span> <span m=''960890''>a</span> <span m=''960930''>stream</span>
  <span m=''961220''>s</span> <span m=''964150''>and</span> <span m=''965200''>is</span>
  <span m=''965350''>going</span> <span m=''965420''>to</span> <span m=''965500''>produce</span>
  <span m=''965920''>the</span> <span m=''965970''>stream</span> <span m=''967220''>of</span>
  <span m=''967460''>elements</span> <span m=''967870''>of</span> <span m=''968000''>s</span>
  <span m=''968140''>multiplied</span> <span m=''968630''>by</span> <span m=''968720''>this</span>
  <span m=''968900''>constant.</span> <span m=''969710''>And</span> <span m=''969890''>that''s</span>
  <span m=''970070''>easy,</span> <span m=''970280''>that''s</span> <span m=''970450''>just</span>
  <span m=''970650''>a</span> <span m=''970690''>map</span> <span m=''972240''>of</span>
  <span m=''972530''>the</span> <span m=''973560''>function</span> <span m=''974050''>of</span>
  <span m=''974170''>an</span> <span m=''974320''>element</span> <span m=''974740''>that</span>
  <span m=''974880''>multiplies</span> <span m=''975420''>it</span> <span m=''975510''>by</span>
  <span m=''975630''>the</span> <span m=''975720''>constant,</span> <span m=''976370''>and</span>
  <span m=''976480''>we</span> <span m=''976600''>map</span> <span m=''976930''>that</span>
  <span m=''977040''>down the stream.</span> </p><p><span m=''980520''>So</span> <span
  m=''980700''>given</span> <span m=''980940''>those</span> <span m=''981110''>two,</span>
  <span m=''982730''>let</span> <span m=''982810''>me</span> <span m=''982890''>show</span>
  <span m=''983020''>you</span> <span m=''983150''>what</span> <span m=''983230''>I</span>
  <span m=''983320''>mean</span> <span m=''983510''>by</span> <span m=''983630''>programs</span>
  <span m=''984150''>that</span> <span m=''984900''>operate</span> <span m=''985290''>on</span>
  <span m=''985420''>streams</span> <span m=''986270''>all</span> <span m=''986570''>at</span>
  <span m=''986660''>once.</span> <span m=''987910''>Let''s</span> <span m=''988260''>look</span>
  <span m=''988430''>at</span> <span m=''988580''>this.</span> <span m=''990200''>Suppose</span>
  <span m=''990330''>I</span> <span m=''990380''>write</span> <span m=''990630''>this.</span>
  <span m=''991680''>I</span> <span m=''991840''>say</span> <span m=''991970''>define--</span>
  <span m=''996618''>I''ll</span> <span m=''997070''>call it</span> <span m=''997470''>ones--</span>
  <span m=''999590''>to</span> <span m=''999810''>be</span> <span m=''1003120''>cons-stream</span>
  <span m=''1008050''>of</span> <span m=''1008800''>1</span> <span m=''1011540''>onto</span>
  <span m=''1011880''>ones.</span> <span m=''1014860''>What''s</span> <span m=''1015250''>that?</span>
  <span m=''1016950''>That''s</span> <span m=''1017260''>going</span> <span m=''1017340''>to</span>
  <span m=''1017420''>be</span> <span m=''1017500''>an</span> <span m=''1017580''>infinite</span>
  <span m=''1018070''>stream</span> <span m=''1018400''>of</span> <span m=''1018500''>ones</span>
  <span m=''1019870''>because</span> <span m=''1020330''>the</span> <span m=''1020530''>first</span>
  <span m=''1020730''>thing</span> <span m=''1020900''>is</span> <span m=''1021040''>1.</span>
  <span m=''1023330''>And</span> <span m=''1023470''>the</span> <span m=''1023560''>tail</span>
  <span m=''1023880''>of</span> <span m=''1024010''>it</span> <span m=''1024470''>is</span>
  <span m=''1024640''>a</span> <span m=''1024690''>thing</span> <span m=''1025619''>whose</span>
  <span m=''1025810''>first</span> <span m=''1026069''>thing</span> <span m=''1026260''>is</span>
  <span m=''1026380''>1</span> <span m=''1027670''>and</span> <span m=''1027819''>whose</span>
  <span m=''1027930''>tail</span> <span m=''1028300''>is</span> <span m=''1028410''>a</span>
  <span m=''1028480''>thing</span> <span m=''1029089''>whose</span> <span m=''1029329''>first</span>
  <span m=''1029569''>thing</span> <span m=''1029780''>is</span> <span m=''1029910''>1</span>
  <span m=''1030589''>and</span> <span m=''1030770''>so</span> <span m=''1030940''>on</span>
  <span m=''1031099''>and</span> <span m=''1031220''>so</span> <span m=''1031349''>on</span>
  <span m=''1031450''>and</span> <span m=''1031569''>so</span> <span m=''1031680''>on.</span>
  <span m=''1031780''>So</span> <span m=''1031869''>that''s</span> <span m=''1032079''>an</span>
  <span m=''1032319''>infinite</span> <span m=''1032500''>stream</span> <span m=''1032780''>of</span>
  <span m=''1032890''>ones.</span> </p><p><span m=''1035130''>And</span> <span m=''1035280''>now</span>
  <span m=''1035349''>using</span> <span m=''1035670''>that,</span> <span m=''1036109''>let</span>
  <span m=''1036319''>me give you</span> <span m=''1036520''>another</span> <span
  m=''1036810''>definition</span> <span m=''1037290''>of</span> <span m=''1037380''>the</span>
  <span m=''1037460''>integers.</span> <span m=''1038599''>We</span> <span m=''1039210''>can</span>
  <span m=''1039339''>define</span> <span m=''1042390''>the</span> <span m=''1042589''>integers</span>
  <span m=''1046869''>to</span> <span m=''1047060''>be--</span> <span m=''1048270''>well,</span>
  <span m=''1048420''>the</span> <span m=''1048620''>first</span> <span m=''1048830''>integer</span>
  <span m=''1049760''>we''ll</span> <span m=''1049880''>take</span> <span m=''1050100''>to</span>
  <span m=''1050200''>be</span> <span m=''1050330''>1,</span> <span m=''1052131''>this</span>
  <span m=''1052570''>cons-stream of</span> <span m=''1053410''>1</span> <span m=''1054830''>onto</span>
  <span m=''1057150''>the</span> <span m=''1057280''>element-wise</span> <span m=''1057950''>sum</span>
  <span m=''1060180''>onto</span> <span m=''1060640''>add streams</span> <span m=''1062070''>of</span>
  <span m=''1062490''>the</span> <span m=''1062790''>integers</span> <span m=''1067710''>to</span>
  <span m=''1067820''>ones.</span> <span m=''1074950''>The</span> <span m=''1075350''>integers</span>
  <span m=''1075700''>are a</span> <span m=''1075830''>thing</span> <span m=''1077290''>whose</span>
  <span m=''1078770''>first</span> <span m=''1079110''>element</span> <span m=''1079470''>is</span>
  <span m=''1079610''>1,</span> <span m=''1080970''>and</span> <span m=''1081160''>the</span>
  <span m=''1081240''>rest</span> <span m=''1081510''>of</span> <span m=''1081560''>them</span>
  <span m=''1081850''>you</span> <span m=''1081990''>get</span> <span m=''1083130''>by</span>
  <span m=''1083290''>taking</span> <span m=''1083680''>those</span> <span m=''1083880''>integers</span>
  <span m=''1084760''>and</span> <span m=''1084940''>incrementing</span> <span m=''1085380''>each</span>
  <span m=''1085540''>one</span> <span m=''1085700''>by</span> <span m=''1085860''>one.</span>
  <span m=''1086640''>So</span> <span m=''1086840''>the</span> <span m=''1086920''>second</span>
  <span m=''1087250''>element</span> <span m=''1087530''>of</span> <span m=''1087600''>the</span>
  <span m=''1087720''>integers</span> <span m=''1088580''>is</span> <span m=''1089420''>the</span>
  <span m=''1089800''>first</span> <span m=''1090110''>element</span> <span m=''1090400''>of</span>
  <span m=''1090510''>the</span> <span m=''1090610''>integers</span> <span m=''1090990''>incremented</span>
  <span m=''1091500''>by</span> <span m=''1091650''>one.</span> <span m=''1093940''>And</span>
  <span m=''1094060''>the</span> <span m=''1094130''>rest</span> <span m=''1094360''>of</span>
  <span m=''1094410''>that</span> <span m=''1094550''>is</span> <span m=''1094660''>the</span>
  <span m=''1094740''>next</span> <span m=''1095040''>one,</span> <span m=''1095390''>and</span>
  <span m=''1095490''>the</span> <span m=''1095600''>third</span> <span m=''1095830''>element</span>
  <span m=''1096110''>of</span> <span m=''1096210''>that</span> <span m=''1096690''>is</span>
  <span m=''1096940''>the</span> <span m=''1097000''>same</span> <span m=''1097340''>as</span>
  <span m=''1097490''>the</span> <span m=''1098420''>first</span> <span m=''1098740''>element</span>
  <span m=''1099190''>of</span> <span m=''1099340''>the</span> <span m=''1099430''>tail</span>
  <span m=''1099690''>of</span> <span m=''1099780''>the</span> <span m=''1099880''>integers</span>
  <span m=''1101040''>incremented</span> <span m=''1101380''>by</span> <span m=''1101540''>one,</span>
  <span m=''1102560''>which</span> <span m=''1102750''>is</span> <span m=''1102870''>the</span>
  <span m=''1102930''>same</span> <span m=''1103260''>as</span> <span m=''1103430''>the</span>
  <span m=''1105050''>first</span> <span m=''1105360''>element</span> <span m=''1105670''>of</span>
  <span m=''1105740''>the</span> <span m=''1105850''>original</span> <span m=''1106700''>integers</span>
  <span m=''1107620''>incremented</span> <span m=''1108130''>by</span> <span m=''1108270''>one</span>
  <span m=''1108930''>and</span> <span m=''1109090''>incremented</span> <span m=''1109510''>by</span>
  <span m=''1109640''>one</span> <span m=''1109860''>again</span> <span m=''1110690''>and</span>
  <span m=''1110870''>so</span> <span m=''1111050''>on.</span> </p><p><span m=''1115240''>That</span>
  <span m=''1115310''>looks</span> <span m=''1115500''>pretty</span> <span m=''1115700''>suspicious.</span>
  <span m=''1116310''>See,</span> <span m=''1116540''>notice</span> <span m=''1116870''>that</span>
  <span m=''1117000''>it</span> <span m=''1117060''>works</span> <span m=''1118000''>because</span>
  <span m=''1118510''>of</span> <span m=''1118600''>delay.</span> <span m=''1120150''>See,</span>
  <span m=''1120430''>this</span> <span m=''1120620''>looks</span> <span m=''1120970''>like--</span>
  <span m=''1122480''>let''s</span> <span m=''1122580''>take a</span> <span m=''1122700''>look</span>
  <span m=''1122880''>at</span> <span m=''1122970''>ones.</span> <span m=''1123870''>This</span>
  <span m=''1124100''>looks</span> <span m=''1124350''>like</span> <span m=''1124540''>it</span>
  <span m=''1124620''>couldn''t</span> <span m=''1125010''>even</span> <span m=''1125240''>be</span>
  <span m=''1125370''>processed</span> <span m=''1126380''>because</span> <span m=''1126700''>it''s</span>
  <span m=''1126810''>suddenly</span> <span m=''1127120''>saying</span> <span m=''1127780''>in</span>
  <span m=''1127910''>order</span> <span m=''1128110''>to</span> <span m=''1128210''>know</span>
  <span m=''1128330''>what</span> <span m=''1128470''>ones</span> <span m=''1128840''>is,</span>
  <span m=''1129010''>I</span> <span m=''1129070''>say</span> <span m=''1129250''>it''s</span>
  <span m=''1129410''>cons-stream of</span> <span m=''1129930''>something</span> <span
  m=''1130270''>onto</span> <span m=''1130510''>ones.</span> <span m=''1131130''>The</span>
  <span m=''1131300''>reason</span> <span m=''1131530''>that</span> <span m=''1131730''>works</span>
  <span m=''1132080''>is</span> <span m=''1132190''>because</span> <span m=''1132480''>of</span>
  <span m=''1132570''>that</span> <span m=''1132660''>very</span> <span m=''1132890''>sneaky</span>
  <span m=''1133220''>hidden</span> <span m=''1133470''>delay</span> <span m=''1133850''>in
  there.</span> <span m=''1135250''>Because</span> <span m=''1135560''>what</span>
  <span m=''1135700''>this</span> <span m=''1135860''>really</span> <span m=''1136300''>is,</span>
  <span m=''1137960''>remember,</span> <span m=''1138190''>cons-stream</span> <span
  m=''1138530''>is just</span> <span m=''1138870''>an</span> <span m=''1138950''>abbreviation.</span>
  <span m=''1140290''>This</span> <span m=''1140480''>really</span> <span m=''1140830''>is</span>
  <span m=''1141880''>cons</span> <span m=''1143530''>of</span> <span m=''1143970''>1</span>
  <span m=''1145790''>onto</span> <span m=''1146020''>delay</span> <span m=''1148030''>of</span>
  <span m=''1148520''>ones.</span> </p><p><span m=''1152140''>So</span> <span m=''1152320''>how</span>
  <span m=''1152430''>does</span> <span m=''1152590''>that</span> <span m=''1152740''>work?</span>
  <span m=''1155500''>You</span> <span m=''1155590''>say</span> <span m=''1155730''>I''m</span>
  <span m=''1155790''>going</span> <span m=''1155900''>to</span> <span m=''1155960''>define</span>
  <span m=''1156380''>ones.</span> <span m=''1158020''>First</span> <span m=''1158270''>I</span>
  <span m=''1158390''>see</span> <span m=''1158490''>what</span> <span m=''1158650''>ones</span>
  <span m=''1158830''>is</span> <span m=''1159030''>supposed</span> <span m=''1159320''>to</span>
  <span m=''1159400''>be</span> <span m=''1159500''>defined</span> <span m=''1160000''>as.</span>
  <span m=''1160700''>Well,</span> <span m=''1160890''>ones</span> <span m=''1161540''>is</span>
  <span m=''1161700''>supposed</span> <span m=''1162070''>to</span> <span m=''1162130''>be</span>
  <span m=''1162270''>defined</span> <span m=''1162890''>as</span> <span m=''1164980''>a</span>
  <span m=''1165100''>cons</span> <span m=''1165810''>whose</span> <span m=''1167020''>first</span>
  <span m=''1167320''>part</span> <span m=''1167530''>is</span> <span m=''1167660''>1</span>
  <span m=''1168290''>and</span> <span m=''1168410''>whose</span> <span m=''1168540''>second</span>
  <span m=''1168900''>part</span> <span m=''1169170''>is,</span> <span m=''1169410''>well,</span>
  <span m=''1169610''>it''s</span> <span m=''1169720''>a</span> <span m=''1169770''>promise</span>
  <span m=''1170070''>to</span> <span m=''1170160''>compute</span> <span m=''1170460''>something
  that</span> <span m=''1170800''>I</span> <span m=''1170860''>don''t</span> <span
  m=''1171010''>worry</span> <span m=''1171250''>about</span> <span m=''1171450''>yet.</span>
  <span m=''1172710''>So</span> <span m=''1172840''>it</span> <span m=''1172900''>doesn''t</span>
  <span m=''1173150''>bother</span> <span m=''1173460''>me</span> <span m=''1173600''>that</span>
  <span m=''1173740''>at</span> <span m=''1173900''>the</span> <span m=''1173990''>point</span>
  <span m=''1174290''>I</span> <span m=''1174360''>do</span> <span m=''1174530''>this</span>
  <span m=''1174680''>definition,</span> <span m=''1175230''>ones</span> <span m=''1175460''>isn''t</span>
  <span m=''1175640''>defined.</span> <span m=''1177270''>Having</span> <span m=''1177530''>run</span>
  <span m=''1177700''>the</span> <span m=''1177770''>definition</span> <span m=''1178310''>now,</span>
  <span m=''1178480''>ones</span> <span m=''1178760''>is</span> <span m=''1178880''>defined.</span>
  <span m=''1180670''>So</span> <span m=''1180830''>that</span> <span m=''1180950''>when</span>
  <span m=''1181060''>I</span> <span m=''1181120''>go and</span> <span m=''1181340''>look</span>
  <span m=''1181510''>at</span> <span m=''1181580''>the</span> <span m=''1181670''>tail</span>
  <span m=''1181960''>of</span> <span m=''1182080''>it,</span> <span m=''1182170''>it''s</span>
  <span m=''1182330''>defined.</span> <span m=''1184920''>It''s</span> <span m=''1185160''>very</span>
  <span m=''1185510''>sneaky.</span> <span m=''1186590''>And</span> <span m=''1186750''>an</span>
  <span m=''1186840''>integer</span> <span m=''1187140''>is</span> <span m=''1187230''>the</span>
  <span m=''1187300''>same</span> <span m=''1187580''>way.</span> <span m=''1188470''>I</span>
  <span m=''1188570''>can</span> <span m=''1188700''>refer</span> <span m=''1189040''>to</span>
  <span m=''1189090''>integers</span> <span m=''1189540''>here</span> <span m=''1189970''>because</span>
  <span m=''1191120''>hidden</span> <span m=''1191390''>way</span> <span m=''1191540''>down--</span>
  <span m=''1192060''>because</span> <span m=''1192340''>of</span> <span m=''1192430''>this</span>
  <span m=''1192530''>cons-stream.</span> <span m=''1193210''>It''s</span> <span m=''1193670''>the</span>
  <span m=''1193990''>cons-stream</span> <span m=''1194440''>of</span> <span m=''1194770''>1</span>
  <span m=''1195360''>onto</span> <span m=''1195630''>something</span> <span m=''1196000''>that</span>
  <span m=''1196110''>I</span> <span m=''1196200''>don''t</span> <span m=''1196360''>worry</span>
  <span m=''1196610''>that</span> <span m=''1196830''>yet.</span> <span m=''1197050''>So</span>
  <span m=''1197170''>I</span> <span m=''1197300''>don''t</span> <span m=''1197420''>look</span>
  <span m=''1197580''>at</span> <span m=''1197730''>it,</span> <span m=''1197840''>and</span>
  <span m=''1197900''>I</span> <span m=''1197960''>don''t</span> <span m=''1198150''>notice</span>
  <span m=''1198470''>that</span> <span m=''1198580''>integers</span> <span m=''1198970''>isn''t</span>
  <span m=''1199180''>defined</span> <span m=''1200250''>at</span> <span m=''1200370''>the</span>
  <span m=''1200460''>point</span> <span m=''1200660''>where</span> <span m=''1200760''>I</span>
  <span m=''1200830''>try</span> <span m=''1200970''>and</span> <span m=''1201110''>run</span>
  <span m=''1201250''>the</span> <span m=''1201320''>definition.</span> </p><p><span
  m=''1206320''>OK,</span> <span m=''1206770''>let</span> <span m=''1206940''>me draw</span>
  <span m=''1207060''>a</span> <span m=''1207120''>picture</span> <span m=''1207460''>of</span>
  <span m=''1207560''>that</span> <span m=''1207660''>integers</span> <span m=''1207790''>thing</span>
  <span m=''1208430''>because</span> <span m=''1208560''>it</span> <span m=''1208700''>still</span>
  <span m=''1210280''>maybe</span> <span m=''1210550''>seems a</span> <span m=''1210750''>little</span>
  <span m=''1210920''>bit</span> <span m=''1211020''>shaky.</span> <span m=''1212430''>What</span>
  <span m=''1212540''>do</span> <span m=''1212640''>I</span> <span m=''1212740''>do?</span>
  <span m=''1215020''>I''ve</span> <span m=''1215120''>got</span> <span m=''1215290''>the</span>
  <span m=''1215360''>stream</span> <span m=''1215660''>of</span> <span m=''1215760''>ones,</span>
  <span m=''1220540''>and</span> <span m=''1220740''>that</span> <span m=''1220880''>sort</span>
  <span m=''1220990''>of</span> <span m=''1221110''>comes</span> <span m=''1221420''>in</span>
  <span m=''1222920''>and</span> <span m=''1223490''>goes</span> <span m=''1223720''>into</span>
  <span m=''1224470''>an</span> <span m=''1224610''>adder</span> <span m=''1224930''>that''s</span>
  <span m=''1225130''>going</span> <span m=''1225200''>to</span> <span m=''1225270''>be</span>
  <span m=''1225340''>this</span> <span m=''1225420''>add</span> <span m=''1225720''>streams</span>
  <span m=''1226140''>thing.</span> <span m=''1229310''>And</span> <span m=''1231470''>that</span>
  <span m=''1231650''>goes</span> <span m=''1231870''>in--</span> <span m=''1233260''>that''s</span>
  <span m=''1233460''>going</span> <span m=''1233540''>to</span> <span m=''1233620''>put</span>
  <span m=''1233820''>out</span> <span m=''1235260''>the</span> <span m=''1235380''>integers.</span>
  <span m=''1240760''>And</span> <span m=''1240960''>the</span> <span m=''1241050''>other</span>
  <span m=''1241310''>thing</span> <span m=''1241510''>that</span> <span m=''1241630''>goes</span>
  <span m=''1241840''>into</span> <span m=''1242030''>the</span> <span m=''1242200''>adder</span>
  <span m=''1242420''>here</span> <span m=''1244790''>is</span> <span m=''1245170''>the</span>
  <span m=''1245280''>integer,</span> <span m=''1245640''>so</span> <span m=''1245770''>there''s
  a</span> <span m=''1245960''>little</span> <span m=''1246150''>feedback</span> <span
  m=''1246670''>loop.</span> <span m=''1248060''>And</span> <span m=''1248190''>all</span>
  <span m=''1248350''>I</span> <span m=''1248420''>need</span> <span m=''1248590''>to</span>
  <span m=''1248670''>start</span> <span m=''1248990''>it</span> <span m=''1249100''>off</span>
  <span m=''1250130''>is</span> <span m=''1251020''>someplace</span> <span m=''1251470''>I''ve</span>
  <span m=''1251560''>got</span> <span m=''1251660''>a</span> <span m=''1251700''>stick</span>
  <span m=''1251930''>that</span> <span m=''1252060''>initial</span> <span m=''1252430''>1.</span>
  </p><p><span m=''1257100''>In</span> <span m=''1257260''>a</span> <span m=''1257440''>real</span>
  <span m=''1257640''>signal</span> <span m=''1257940''>processing</span> <span m=''1258450''>thing,
  this</span> <span m=''1258730''>might</span> <span m=''1258910''>be</span> <span
  m=''1259510''>a</span> <span m=''1259640''>delay</span> <span m=''1260000''>element</span>
  <span m=''1261060''>with</span> <span m=''1261350''>that</span> <span m=''1261460''>was</span>
  <span m=''1261580''>initialized</span> <span m=''1262080''>to</span> <span m=''1262190''>1.</span>
  <span m=''1262910''>But</span> <span m=''1263030''>there''s</span> <span m=''1263200''>a</span>
  <span m=''1263260''>picture</span> <span m=''1263730''>of</span> <span m=''1264880''>that</span>
  <span m=''1265080''>ones</span> <span m=''1265360''>program.</span> <span m=''1267860''>And</span>
  <span m=''1267990''>in</span> <span m=''1268070''>fact,</span> <span m=''1268410''>that</span>
  <span m=''1268630''>looks</span> <span m=''1268820''>a</span> <span m=''1268880''>lot</span>
  <span m=''1269280''>like--</span> <span m=''1269860''>if</span> <span m=''1270010''>you''ve</span>
  <span m=''1270130''>seen</span> <span m=''1271420''>real</span> <span m=''1271900''>signal</span>
  <span m=''1272730''>block</span> <span m=''1272980''>diagram</span> <span m=''1273460''>things,</span>
  <span m=''1273780''>that</span> <span m=''1273910''>looks</span> <span m=''1274080''>a</span>
  <span m=''1274140''>lot</span> <span m=''1274400''>like</span> <span m=''1275660''>accumulators,</span>
  <span m=''1276200''>finite</span> <span m=''1276640''>state</span> <span m=''1276850''>accumulators.</span>
  <span m=''1277360''>And</span> <span m=''1277920''>in</span> <span m=''1278130''>fact,</span>
  <span m=''1278390''>we</span> <span m=''1278500''>can</span> <span m=''1278850''>modify</span>
  <span m=''1279320''>this</span> <span m=''1279480''>a</span> <span m=''1279530''>little</span>
  <span m=''1279750''>bit</span> <span m=''1280970''>to</span> <span m=''1281280''>change</span>
  <span m=''1281640''>this</span> <span m=''1282280''>into</span> <span m=''1282500''>something</span>
  <span m=''1282790''>that</span> <span m=''1282930''>integrates</span> <span m=''1283420''>a</span>
  <span m=''1283460''>stream</span> <span m=''1285380''>or</span> <span m=''1285650''>a</span>
  <span m=''1285700''>finite</span> <span m=''1286120''>state</span> <span m=''1286350''>accumulator,</span>
  <span m=''1286900''>however you</span> <span m=''1287280''>like</span> <span m=''1287440''>to</span>
  <span m=''1287510''>think</span> <span m=''1287700''>about</span> <span m=''1287980''>it.</span>
  </p><p><span m=''1288440''>So</span> <span m=''1288640''>instead</span> <span m=''1288900''>of</span>
  <span m=''1288990''>the</span> <span m=''1289080''>ones</span> <span m=''1289400''>coming</span>
  <span m=''1289690''>in and</span> <span m=''1289860''>getting</span> <span m=''1290150''>out</span>
  <span m=''1290250''>the</span> <span m=''1290370''>integers,</span> <span m=''1291710''>what</span>
  <span m=''1291900''>we''ll</span> <span m=''1292000''>do</span> <span m=''1292210''>is</span>
  <span m=''1293090''>say</span> <span m=''1293320''>there''s</span> <span m=''1293530''>a</span>
  <span m=''1293560''>stream</span> <span m=''1293970''>s</span> <span m=''1294200''>coming</span>
  <span m=''1294490''>in,</span> <span m=''1295460''>and</span> <span m=''1295820''>we''re</span>
  <span m=''1296010''>going</span> <span m=''1296080''>to</span> <span m=''1296140''>get</span>
  <span m=''1296370''>out</span> <span m=''1299460''>the</span> <span m=''1299660''>integral</span>
  <span m=''1300060''>of</span> <span m=''1300320''>this,</span> <span m=''1302660''>successive</span>
  <span m=''1303210''>values</span> <span m=''1303490''>of</span> <span m=''1303620''>that,</span>
  <span m=''1304530''>and</span> <span m=''1304700''>it</span> <span m=''1304780''>looks</span>
  <span m=''1305050''>almost</span> <span m=''1305380''>the</span> <span m=''1305430''>same.</span>
  <span m=''1305700''>The</span> <span m=''1305820''>only</span> <span m=''1306020''>thing</span>
  <span m=''1306190''>we''re</span> <span m=''1306300''>going</span> <span m=''1306380''>to</span>
  <span m=''1306460''>do</span> <span m=''1306670''>is</span> <span m=''1307030''>when</span>
  <span m=''1307210''>s</span> <span m=''1307410''>comes</span> <span m=''1307630''>in</span>
  <span m=''1307760''>here,</span> <span m=''1309220''>before</span> <span m=''1309530''>we</span>
  <span m=''1309670''>just</span> <span m=''1309930''>add it</span> <span m=''1310230''>in</span>
  <span m=''1311000''>we''re</span> <span m=''1311120''>going</span> <span m=''1311220''>to</span>
  <span m=''1312320''>multiply</span> <span m=''1312890''>it</span> <span m=''1313010''>by</span>
  <span m=''1313140''>some</span> <span m=''1313360''>number</span> <span m=''1313610''>dt.</span>
  <span m=''1317680''>And</span> <span m=''1317800''>now</span> <span m=''1318020''>what
  we</span> <span m=''1318140''>have</span> <span m=''1318400''>here,</span> <span
  m=''1318530''>this</span> <span m=''1318690''>is</span> <span m=''1318790''>exactly</span>
  <span m=''1319200''>the</span> <span m=''1319280''>same</span> <span m=''1319550''>thing.</span>
  <span m=''1320000''>We</span> <span m=''1320090''>have</span> <span m=''1320210''>a</span>
  <span m=''1320260''>box,</span> <span m=''1323340''>which</span> <span m=''1323520''>is</span>
  <span m=''1323620''>an</span> <span m=''1323710''>integrator.</span> <span m=''1329790''>And</span>
  <span m=''1329930''>it</span> <span m=''1330030''>takes</span> <span m=''1330300''>in</span>
  <span m=''1330410''>a</span> <span m=''1330450''>stream</span> <span m=''1330800''>s,</span>
  <span m=''1331930''>and</span> <span m=''1333560''>instead</span> <span m=''1333850''>of</span>
  <span m=''1333940''>1</span> <span m=''1334150''>here,</span> <span m=''1335000''>we</span>
  <span m=''1335110''>can</span> <span m=''1335250''>put</span> <span m=''1335440''>the</span>
  <span m=''1336910''>additional</span> <span m=''1337310''>value</span> <span m=''1337650''>for</span>
  <span m=''1337760''>the</span> <span m=''1337890''>integral.</span> </p><p><span
  m=''1339980''>And that</span> <span m=''1340230''>one</span> <span m=''1340310''>looks</span>
  <span m=''1340490''>very</span> <span m=''1340980''>much</span> <span m=''1341230''>like</span>
  <span m=''1341420''>a</span> <span m=''1342720''>signal</span> <span m=''1343030''>processing</span>
  <span m=''1343650''>block</span> <span m=''1343940''>diagram</span> <span m=''1344420''>program.</span>
  <span m=''1345270''>In</span> <span m=''1345570''>fact,</span> <span m=''1345740''>here''s
  the</span> <span m=''1345830''>procedure</span> <span m=''1346380''>that</span>
  <span m=''1346890''>looks</span> <span m=''1347060''>exactly</span> <span m=''1347470''>like</span>
  <span m=''1347670''>that.</span> <span m=''1351490''>Find the</span> <span m=''1351830''>integral</span>
  <span m=''1352810''>of</span> <span m=''1352970''>a</span> <span m=''1353040''>stream.</span>
  <span m=''1354010''>So</span> <span m=''1354240''>an</span> <span m=''1354370''>integral''s</span>
  <span m=''1354610''>going</span> <span m=''1354680''>to</span> <span m=''1354760''>take</span>
  <span m=''1354940''>a</span> <span m=''1354980''>stream</span> <span m=''1355710''>and</span>
  <span m=''1355860''>produce</span> <span m=''1356160''>a</span> <span m=''1356210''>new</span>
  <span m=''1356350''>stream,</span> <span m=''1357580''>and</span> <span m=''1357730''>it</span>
  <span m=''1357810''>takes</span> <span m=''1358050''>in</span> <span m=''1358160''>an</span>
  <span m=''1358280''>initial</span> <span m=''1358600''>value</span> <span m=''1359560''>and</span>
  <span m=''1359740''>some</span> <span m=''1359920''>time</span> <span m=''1360180''>constant.</span>
  <span m=''1362230''>And</span> <span m=''1362360''>what do</span> <span m=''1362530''>we</span>
  <span m=''1362640''>do?</span> <span m=''1363040''>Well,</span> <span m=''1363250''>we</span>
  <span m=''1363370''>internally</span> <span m=''1363960''>define</span> <span m=''1364410''>this</span>
  <span m=''1364560''>thing</span> <span m=''1364820''>int, and</span> <span m=''1365230''>we</span>
  <span m=''1365400''>make</span> <span m=''1365560''>this</span> <span m=''1365710''>internal</span>
  <span m=''1366130''>name</span> <span m=''1366350''>so</span> <span m=''1366470''>we</span>
  <span m=''1366570''>can</span> <span m=''1366700''>feed it</span> <span m=''1367050''>back,</span>
  <span m=''1367850''>loop it</span> <span m=''1368050''>around</span> <span m=''1368410''>itself.</span>
  <span m=''1369400''>And</span> <span m=''1369620''>int</span> <span m=''1369890''>is</span>
  <span m=''1370000''>defined</span> <span m=''1370400''>to</span> <span m=''1370510''>be</span>
  <span m=''1371070''>something</span> <span m=''1371450''>that</span> <span m=''1371600''>starts</span>
  <span m=''1372000''>out</span> <span m=''1372270''>at</span> <span m=''1372380''>the</span>
  <span m=''1372500''>initial</span> <span m=''1372790''>value,</span> <span m=''1374990''>and</span>
  <span m=''1377470''>the</span> <span m=''1377640''>rest</span> <span m=''1377940''>of</span>
  <span m=''1378030''>it</span> <span m=''1378170''>is</span> <span m=''1378500''>gotten</span>
  <span m=''1378800''>by</span> <span m=''1379410''>adding</span> <span m=''1379730''>together.</span>
  <span m=''1381280''>We</span> <span m=''1381410''>take</span> <span m=''1381650''>our</span>
  <span m=''1381780''>input</span> <span m=''1382070''>stream,</span> <span m=''1382520''>scale</span>
  <span m=''1382990''>it by</span> <span m=''1383130''>dt,</span> <span m=''1383980''>and</span>
  <span m=''1384130''>add</span> <span m=''1384330''>that</span> <span m=''1384500''>to
  int.</span> <span m=''1386880''>And</span> <span m=''1387070''>now</span> <span
  m=''1387100''>we''ll</span> <span m=''1387290''>return</span> <span m=''1387650''>from</span>
  <span m=''1387770''>all</span> <span m=''1387940''>that</span> <span m=''1388120''>the</span>
  <span m=''1388210''>value</span> <span m=''1388560''>of</span> <span m=''1388640''>integral</span>
  <span m=''1388990''>is this thing</span> <span m=''1389410''>int.</span> <span m=''1390690''>And</span>
  <span m=''1390800''>we</span> <span m=''1390910''>use</span> <span m=''1391120''>this</span>
  <span m=''1391270''>internal</span> <span m=''1391620''>definition</span> <span
  m=''1392130''>syntax</span> <span m=''1392600''>so</span> <span m=''1392690''>we</span>
  <span m=''1392800''>could</span> <span m=''1393240''>write</span> <span m=''1393490''>a</span>
  <span m=''1393580''>little</span> <span m=''1393820''>internal</span> <span m=''1394180''>definition</span>
  <span m=''1394670''>that</span> <span m=''1394780''>refers</span> <span m=''1395140''>to</span>
  <span m=''1395270''>itself.</span> </p><p><span m=''1401880''>Well,</span> <span
  m=''1402320''>there are</span> <span m=''1402610''>all</span> <span m=''1402810''>sorts</span>
  <span m=''1403020''>of</span> <span m=''1403100''>things</span> <span m=''1403290''>we</span>
  <span m=''1403380''>can</span> <span m=''1403510''>do.</span> <span m=''1403710''>Let''s</span>
  <span m=''1404010''>try</span> <span m=''1404120''>this</span> <span m=''1404310''>one.</span>
  <span m=''1405500''>how</span> <span m=''1405750''>about</span> <span m=''1405930''>the</span>
  <span m=''1406130''>Fibonacci</span> <span m=''1406640''>numbers.</span> <span m=''1406895''>You</span>
  <span m=''1407150''>can say</span> <span m=''1407360''>define</span> <span m=''1412340''>fibs.</span>
  <span m=''1416350''>Well,</span> <span m=''1416490''>what</span> <span m=''1416830''>are</span>
  <span m=''1416910''>the</span> <span m=''1416950''>Fibonacci</span> <span m=''1417310''>numbers?</span>
  <span m=''1417985''>They''re</span> <span m=''1418390''>something</span> <span m=''1424580''>that</span>
  <span m=''1424760''>starts</span> <span m=''1425130''>out</span> <span m=''1425870''>with</span>
  <span m=''1426040''>0,</span> <span m=''1428690''>and</span> <span m=''1428840''>the</span>
  <span m=''1429010''>next</span> <span m=''1429180''>one</span> <span m=''1429350''>is</span>
  <span m=''1429470''>1.</span> <span m=''1436260''>And</span> <span m=''1436510''>the</span>
  <span m=''1436590''>rest</span> <span m=''1436840''>of</span> <span m=''1436890''>the</span>
  <span m=''1437030''>Fibonacci</span> <span m=''1437490''>numbers</span> <span m=''1438240''>are</span>
  <span m=''1438400''>gotten</span> <span m=''1438750''>by</span> <span m=''1439910''>adding</span>
  <span m=''1446470''>the</span> <span m=''1446890''>Fibonacci</span> <span m=''1447460''>numbers</span>
  <span m=''1450020''>to</span> <span m=''1450280''>their</span> <span m=''1450470''>own</span>
  <span m=''1450610''>tail.</span> <span m=''1457570''>There''s</span> <span m=''1457800''>a</span>
  <span m=''1457860''>definition</span> <span m=''1458360''>of</span> <span m=''1458440''>the</span>
  <span m=''1458510''>Fibonacci</span> <span m=''1459050''>numbers.</span> </p><p><span
  m=''1460580''>How</span> <span m=''1460720''>does</span> <span m=''1460900''>that</span>
  <span m=''1461080''>work?</span> <span m=''1461430''>Well,</span> <span m=''1463540''>we</span>
  <span m=''1463650''>start</span> <span m=''1463950''>off,</span> <span m=''1464190''>and</span>
  <span m=''1464320''>someone</span> <span m=''1464570''>says</span> <span m=''1464900''>compute</span>
  <span m=''1465260''>for</span> <span m=''1465380''>us</span> <span m=''1465520''>the</span>
  <span m=''1465650''>Fibonacci</span> <span m=''1466120''>numbers,</span> <span m=''1469292''>and</span>
  <span m=''1469730''>we''re</span> <span m=''1469880''>going</span> <span m=''1469950''>to</span>
  <span m=''1470020''>tell</span> <span m=''1470220''>you</span> <span m=''1470400''>it</span>
  <span m=''1470490''>starts</span> <span m=''1470830''>out</span> <span m=''1470980''>with</span>
  <span m=''1471070''>0</span> <span m=''1471380''>and</span> <span m=''1471520''>1.</span>
  <span m=''1475790''>And</span> <span m=''1476590''>everything</span> <span m=''1477020''>after</span>
  <span m=''1477330''>the</span> <span m=''1477420''>0</span> <span m=''1477720''>and</span>
  <span m=''1477870''>1</span> <span m=''1479260''>is</span> <span m=''1479420''>gotten</span>
  <span m=''1479670''>by</span> <span m=''1479800''>summing</span> <span m=''1480150''>two</span>
  <span m=''1480320''>streams.</span> <span m=''1481150''>One</span> <span m=''1481410''>is</span>
  <span m=''1481530''>the</span> <span m=''1481610''>fibs</span> <span m=''1481930''>themselves,</span>
  <span m=''1483840''>and</span> <span m=''1484080''>the</span> <span m=''1484310''>other</span>
  <span m=''1484460''>one</span> <span m=''1484580''>is</span> <span m=''1484690''>the</span>
  <span m=''1484780''>tail</span> <span m=''1485200''>of the fibs.</span> </p><p><span
  m=''1488870''>So</span> <span m=''1489180''>if</span> <span m=''1489270''>I</span>
  <span m=''1489340''>know</span> <span m=''1489510''>that</span> <span m=''1489680''>these</span>
  <span m=''1489820''>start</span> <span m=''1490070''>out</span> <span m=''1490180''>with</span>
  <span m=''1490280''>0</span> <span m=''1490580''>and</span> <span m=''1490690''>1,</span>
  <span m=''1491790''>I</span> <span m=''1491910''>know</span> <span m=''1492100''>that</span>
  <span m=''1492430''>the</span> <span m=''1492660''>fibs</span> <span m=''1492950''>now</span>
  <span m=''1493100''>start</span> <span m=''1493360''>out</span> <span m=''1493490''>with</span>
  <span m=''1493590''>0</span> <span m=''1494840''>and</span> <span m=''1495020''>1,</span>
  <span m=''1495760''>and</span> <span m=''1495860''>the</span> <span m=''1495960''>tail</span>
  <span m=''1496245''>of the fibs</span> <span m=''1496530''>start</span> <span m=''1496780''>out</span>
  <span m=''1496900''>with</span> <span m=''1497030''>1.</span> <span m=''1498360''>So
  as</span> <span m=''1498560''>soon</span> <span m=''1498760''>as</span> <span m=''1498850''>I</span>
  <span m=''1498910''>know</span> <span m=''1499080''>that,</span> <span m=''1499660''>I</span>
  <span m=''1499790''>know</span> <span m=''1499930''>that</span> <span m=''1500080''>the</span>
  <span m=''1500160''>next</span> <span m=''1500450''>one</span> <span m=''1500580''>here
  is</span> <span m=''1500850''>0</span> <span m=''1501180''>plus</span> <span m=''1501440''>1</span>
  <span m=''1501610''>is</span> <span m=''1501730''>1,</span> <span m=''1502385''>and</span>
  <span m=''1502690''>that</span> <span m=''1503190''>tells</span> <span m=''1503370''>me</span>
  <span m=''1503450''>that</span> <span m=''1503590''>the</span> <span m=''1503680''>next</span>
  <span m=''1503910''>one</span> <span m=''1504040''>here</span> <span m=''1504260''>is</span>
  <span m=''1504370''>1</span> <span m=''1504600''>and</span> <span m=''1504670''>the</span>
  <span m=''1504740''>next</span> <span m=''1504950''>one</span> <span m=''1505070''>here</span>
  <span m=''1505290''>is</span> <span m=''1505400''>1.</span> <span m=''1506300''>And</span>
  <span m=''1506440''>as</span> <span m=''1506520''>soon</span> <span m=''1506680''>as</span>
  <span m=''1506780''>I</span> <span m=''1506870''>know</span> <span m=''1507060''>that,</span>
  <span m=''1507330''>I</span> <span m=''1507410''>know</span> <span m=''1507540''>that</span>
  <span m=''1507680''>the</span> <span m=''1507760''>next</span> <span m=''1508010''>one</span>
  <span m=''1508140''>is</span> <span m=''1508270''>2.</span> <span m=''1509390''>So</span>
  <span m=''1509720''>the</span> <span m=''1509810''>next</span> <span m=''1510020''>one</span>
  <span m=''1510120''>here</span> <span m=''1510360''>is</span> <span m=''1510530''>2</span>
  <span m=''1510680''>and</span> <span m=''1510740''>the</span> <span m=''1510800''>next</span>
  <span m=''1511010''>one</span> <span m=''1511110''>here</span> <span m=''1511320''>is</span>
  <span m=''1511440''>2.</span> <span m=''1511700''>And</span> <span m=''1511810''>this</span>
  <span m=''1511920''>is 3.</span> <span m=''1514720''>This</span> <span m=''1514850''>one</span>
  <span m=''1514960''>goes</span> <span m=''1515160''>to</span> <span m=''1515260''>3,</span>
  <span m=''1516250''>and</span> <span m=''1516380''>this</span> <span m=''1516530''>is</span>
  <span m=''1516670''>5.</span> <span m=''1518530''>So it''s a</span> <span m=''1518740''>perfectly</span>
  <span m=''1519100''>sensible</span> <span m=''1519460''>definition.</span> <span
  m=''1521500''>It''s a</span> <span m=''1521880''>one-line</span> <span m=''1522240''>definition.</span>
  <span m=''1522830''>And</span> <span m=''1522990''>again,</span> <span m=''1523310''>I</span>
  <span m=''1523790''>could</span> <span m=''1524080''>walk</span> <span m=''1524300''>over</span>
  <span m=''1524470''>to</span> <span m=''1524580''>the</span> <span m=''1524650''>computer</span>
  <span m=''1525060''>and</span> <span m=''1525150''>type</span> <span m=''1525410''>that</span>
  <span m=''1525590''>in,</span> <span m=''1525890''>exactly</span> <span m=''1526360''>that,</span>
  <span m=''1526690''>and</span> <span m=''1527100''>then say</span> <span m=''1527440''>print</span>
  <span m=''1527740''>stream</span> <span m=''1528070''>the</span> <span m=''1528140''>Fibonacci</span>
  <span m=''1528650''>numbers,</span> <span m=''1528970''>and</span> <span m=''1529030''>they</span>
  <span m=''1529150''>all</span> <span m=''1529270''>come</span> <span m=''1529450''>flying</span>
  <span m=''1529800''>out.</span> </p><p><span m=''1532790''>See,</span> <span m=''1532920''>this</span>
  <span m=''1533070''>is</span> <span m=''1533180''>a</span> <span m=''1533230''>lot</span>
  <span m=''1533590''>like</span> <span m=''1533860''>learning</span> <span m=''1534120''>about</span>
  <span m=''1534490''>recursion</span> <span m=''1534830''>again.</span> <span m=''1536810''>Instead</span>
  <span m=''1537290''>of</span> <span m=''1537750''>thinking</span> <span m=''1538130''>that</span>
  <span m=''1538330''>recursive</span> <span m=''1538980''>procedures,</span> <span
  m=''1540970''>we</span> <span m=''1541160''>have</span> <span m=''1541350''>recursively</span>
  <span m=''1541950''>defined</span> <span m=''1542650''>data</span> <span m=''1542940''>objects.</span>
  <span m=''1545160''>But</span> <span m=''1545480''>that</span> <span m=''1545640''>shouldn''t</span>
  <span m=''1545990''>surprise</span> <span m=''1546480''>you</span> <span m=''1546640''>at</span>
  <span m=''1546800''>all,</span> <span m=''1547040''>because</span> <span m=''1547400''>by</span>
  <span m=''1547540''>now,</span> <span m=''1548150''>you</span> <span m=''1548230''>should</span>
  <span m=''1548370''>be</span> <span m=''1548460''>coming</span> <span m=''1548770''>to</span>
  <span m=''1548910''>really</span> <span m=''1549190''>believe</span> <span m=''1549530''>that</span>
  <span m=''1549650''>there''s</span> <span m=''1549830''>no</span> <span m=''1550020''>difference</span>
  <span m=''1550790''>really</span> <span m=''1551770''>between</span> <span m=''1552080''>procedures</span>
  <span m=''1552570''>and</span> <span m=''1552690''>data.</span> <span m=''1553090''>In</span>
  <span m=''1553240''>fact,</span> <span m=''1553430''>in</span> <span m=''1553510''>some</span>
  <span m=''1553710''>sense,</span> <span m=''1553970''>the</span> <span m=''1554080''>underlying</span>
  <span m=''1554470''>streams</span> <span m=''1554720''>are</span> <span m=''1555550''>procedures</span>
  <span m=''1556040''>sitting</span> <span m=''1556320''>there,</span> <span m=''1556510''>although</span>
  <span m=''1556680''>we</span> <span m=''1556770''>don''t</span> <span m=''1556950''>think</span>
  <span m=''1557130''>of</span> <span m=''1557240''>them</span> <span m=''1557350''>that</span>
  <span m=''1557560''>way.</span> <span m=''1558210''>So</span> <span m=''1558390''>the</span>
  <span m=''1558480''>fact</span> <span m=''1558650''>that</span> <span m=''1558820''>we</span>
  <span m=''1559050''>have</span> <span m=''1559440''>recursive</span> <span m=''1559800''>procedures,</span>
  <span m=''1560640''>well,</span> <span m=''1560910''>then it</span> <span m=''1561060''>should</span>
  <span m=''1561190''>be</span> <span m=''1561290''>natural</span> <span m=''1561710''>that</span>
  <span m=''1561830''>we</span> <span m=''1562590''>have</span> <span m=''1562810''>recursive</span>
  <span m=''1563140''>data,</span> <span m=''1563430''>too.</span> </p><p><span m=''1567840''>OK,</span>
  <span m=''1567990''>well, this is</span> <span m=''1568210''>all</span> <span m=''1568280''>pretty</span>
  <span m=''1569240''>neat.</span> <span m=''1569720''>Unfortunately,</span> <span
  m=''1570470''>there</span> <span m=''1571770''>are</span> <span m=''1571890''>problems</span>
  <span m=''1572370''>that</span> <span m=''1572510''>streams</span> <span m=''1572820''>aren''t</span>
  <span m=''1573120''>going</span> <span m=''1573260''>to</span> <span m=''1573390''>solve.</span>
  <span m=''1574990''>Let</span> <span m=''1575130''>me</span> <span m=''1575680''>show</span>
  <span m=''1575830''>you</span> <span m=''1575990''>one</span> <span m=''1576160''>of</span>
  <span m=''1576220''>them.</span> <span m=''1577580''>See, in</span> <span m=''1577850''>the</span>
  <span m=''1577920''>same</span> <span m=''1578250''>way,</span> <span m=''1579200''>let''s</span>
  <span m=''1579400''>imagine</span> <span m=''1579820''>that</span> <span m=''1579960''>we''re</span>
  <span m=''1580700''>building</span> <span m=''1581130''>an</span> <span m=''1581190''>analog</span>
  <span m=''1581680''>computer</span> <span m=''1582130''>to</span> <span m=''1582210''>solve</span>
  <span m=''1582500''>some</span> <span m=''1582700''>differential</span> <span m=''1583210''>equation</span>
  <span m=''1585300''>like,</span> <span m=''1586810''>say,</span> <span m=''1587350''>we</span>
  <span m=''1587400''>want</span> <span m=''1587480''>to</span> <span m=''1587560''>solve</span>
  <span m=''1587800''>the</span> <span m=''1587880''>equation</span> <span m=''1590970''>y</span>
  <span m=''1591190''>prime</span> <span m=''1591470''>dy</span> <span m=''1591820''>dt</span>
  <span m=''1593320''>is</span> <span m=''1593470''>y</span> <span m=''1593720''>squared,</span>
  <span m=''1594480''>and</span> <span m=''1594820''>I''m going</span> <span m=''1594910''>to</span>
  <span m=''1595000''>give</span> <span m=''1595150''>you</span> <span m=''1595230''>some</span>
  <span m=''1595410''>initial</span> <span m=''1595740''>value.</span> <span m=''1596390''>I''ll
  tell</span> <span m=''1596600''>you</span> <span m=''1596660''>y</span> <span m=''1597090''>of
  0</span> <span m=''1597380''>equals</span> <span m=''1597610''>1.</span> <span m=''1601060''>Let''s</span>
  <span m=''1601620''>say</span> <span m=''1601810''>dt</span> <span m=''1602630''>is</span>
  <span m=''1602770''>equal</span> <span m=''1603020''>to</span> <span m=''1603440''>something.</span>
  </p><p><span m=''1606770''>Now, in</span> <span m=''1606890''>the</span> <span m=''1607000''>old</span>
  <span m=''1607210''>days,</span> <span m=''1607990''>people</span> <span m=''1608240''>built</span>
  <span m=''1608510''>analog</span> <span m=''1608930''>computers</span> <span m=''1609440''>to</span>
  <span m=''1609530''>solve</span> <span m=''1609800''>these</span> <span m=''1609970''>kinds</span>
  <span m=''1610220''>of</span> <span m=''1610300''>things.</span> <span m=''1611040''>And</span>
  <span m=''1611370''>the</span> <span m=''1611590''>way</span> <span m=''1611700''>you</span>
  <span m=''1611790''>do</span> <span m=''1611910''>that</span> <span m=''1612070''>is</span>
  <span m=''1612190''>really</span> <span m=''1612430''>simple.</span> <span m=''1613020''>You</span>
  <span m=''1613180''>get</span> <span m=''1613350''>yourself</span> <span m=''1613700''>an</span>
  <span m=''1613810''>integrator,</span> <span m=''1620060''>like</span> <span m=''1620260''>that</span>
  <span m=''1620520''>one,</span> <span m=''1620800''>an</span> <span m=''1621030''>integrator</span>
  <span m=''1621270''>box.</span> <span m=''1623055''>And we</span> <span m=''1623440''>put</span>
  <span m=''1623630''>in</span> <span m=''1623740''>the</span> <span m=''1623850''>initial</span>
  <span m=''1624160''>value</span> <span m=''1625240''>y of</span> <span m=''1625620''>0</span>
  <span m=''1625830''>is</span> <span m=''1626010''>1.</span> <span m=''1628530''>And</span>
  <span m=''1628710''>now</span> <span m=''1629210''>if</span> <span m=''1629360''>we</span>
  <span m=''1629450''>feed</span> <span m=''1629650''>something</span> <span m=''1630060''>in
  and</span> <span m=''1630230''>get</span> <span m=''1630380''>something</span> <span
  m=''1630730''>out,</span> <span m=''1630900''>we''ll</span> <span m=''1631010''>say,</span>
  <span m=''1631550''>gee,</span> <span m=''1631750''>what</span> <span m=''1631880''>we''re</span>
  <span m=''1631980''>getting</span> <span m=''1632270''>out</span> <span m=''1632400''>is</span>
  <span m=''1632510''>the</span> <span m=''1632580''>answer.</span> <span m=''1633890''>And</span>
  <span m=''1634300''>what</span> <span m=''1634500''>we''re</span> <span m=''1634590''>going</span>
  <span m=''1634670''>to</span> <span m=''1634750''>feed</span> <span m=''1634970''>in</span>
  <span m=''1635990''>is</span> <span m=''1636150''>the</span> <span m=''1636220''>derivative,</span>
  <span m=''1637550''>and</span> <span m=''1637910''>the</span> <span m=''1638420''>derivative</span>
  <span m=''1638940''>is</span> <span m=''1639040''>supposed</span> <span m=''1639220''>to</span>
  <span m=''1639400''>be</span> <span m=''1639490''>the</span> <span m=''1639560''>square</span>
  <span m=''1639890''>of</span> <span m=''1639950''>the</span> <span m=''1640080''>answer.</span>
  <span m=''1641490''>So</span> <span m=''1641660''>if</span> <span m=''1641720''>we</span>
  <span m=''1641820''>take</span> <span m=''1642030''>these</span> <span m=''1642210''>values</span>
  <span m=''1643170''>and</span> <span m=''1644410''>map</span> <span m=''1646170''>using</span>
  <span m=''1646500''>square,</span> <span m=''1650760''>and</span> <span m=''1650900''>if</span>
  <span m=''1650990''>I</span> <span m=''1651070''>feed</span> <span m=''1651320''>this</span>
  <span m=''1651500''>around,</span> <span m=''1656030''>that''s</span> <span m=''1656530''>how</span>
  <span m=''1656670''>I</span> <span m=''1657430''>build a</span> <span m=''1657570''>block</span>
  <span m=''1657910''>diagram</span> <span m=''1658530''>for</span> <span m=''1658640''>an</span>
  <span m=''1658750''>analog</span> <span m=''1659110''>computer</span> <span m=''1659490''>that</span>
  <span m=''1659650''>solves</span> <span m=''1660000''>this</span> <span m=''1660140''>differential</span>
  <span m=''1660590''>equation.</span> </p><p><span m=''1662910''>Now, what</span>
  <span m=''1663130''>we''d</span> <span m=''1663290''>like</span> <span m=''1663520''>to</span>
  <span m=''1663630''>do</span> <span m=''1664260''>is</span> <span m=''1664430''>write</span>
  <span m=''1664630''>a</span> <span m=''1664670''>stream</span> <span m=''1664980''>program</span>
  <span m=''1665420''>that</span> <span m=''1665630''>looks</span> <span m=''1665820''>exactly</span>
  <span m=''1666270''>like</span> <span m=''1666490''>that.</span> <span m=''1667230''>And
  what do</span> <span m=''1667490''>I</span> <span m=''1667540''>mean</span> <span
  m=''1667710''>exactly</span> <span m=''1668170''>like</span> <span m=''1668390''>that?</span>
  <span m=''1669390''>Well,</span> <span m=''1670050''>I''d</span> <span m=''1670210''>say</span>
  <span m=''1670390''>define</span> <span m=''1675320''>y</span> <span m=''1677040''>to</span>
  <span m=''1677390''>be</span> <span m=''1677520''>the</span> <span m=''1677690''>integral</span>
  <span m=''1684972''>of</span> <span m=''1685450''>dy</span> <span m=''1687590''>starting</span>
  <span m=''1688010''>at</span> <span m=''1688100''>1</span> <span m=''1688915''>with</span>
  <span m=''1689290''>0.001</span> <span m=''1690670''>as</span> <span m=''1690780''>a</span>
  <span m=''1690880''>time</span> <span m=''1691150''>step.</span> <span m=''1693790''>And</span>
  <span m=''1693940''>I''d</span> <span m=''1694070''>like</span> <span m=''1694250''>to</span>
  <span m=''1694360''>say</span> <span m=''1694650''>that</span> <span m=''1694870''>says</span>
  <span m=''1695100''>this.</span> <span m=''1696805''>And then</span> <span m=''1697230''>I''d</span>
  <span m=''1697440''>like</span> <span m=''1697580''>to</span> <span m=''1697670''>say,</span>
  <span m=''1697830''>well,</span> <span m=''1698010''>dy</span> <span m=''1698220''>is</span>
  <span m=''1698530''>gotten</span> <span m=''1698760''>by</span> <span m=''1698910''>mapping</span>
  <span m=''1699635''>the</span> <span m=''1699950''>square</span> <span m=''1700280''>along</span>
  <span m=''1700550''>y.</span> <span m=''1700850''>So</span> <span m=''1701020''>define</span>
  <span m=''1703580''>dy</span> <span m=''1705680''>to</span> <span m=''1705910''>be</span>
  <span m=''1706090''>map</span> <span m=''1708190''>square</span> <span m=''1712110''>along</span>
  <span m=''1712470''>y.</span> <span m=''1713510''>So</span> <span m=''1713700''>there''s</span>
  <span m=''1713890''>a</span> <span m=''1714430''>stream</span> <span m=''1714840''>description</span>
  <span m=''1715610''>of</span> <span m=''1715750''>this</span> <span m=''1715890''>analog</span>
  <span m=''1716270''>computer,</span> <span m=''1718690''>and</span> <span m=''1718830''>unfortunately,</span>
  <span m=''1719490''>it</span> <span m=''1719590''>doesn''t</span> <span m=''1719900''>work.</span>
  </p><p><span m=''1721410''>And</span> <span m=''1721520''>you</span> <span m=''1721630''>can</span>
  <span m=''1721740''>see</span> <span m=''1721870''>why</span> <span m=''1722050''>it</span>
  <span m=''1722120''>doesn''t</span> <span m=''1722400''>work</span> <span m=''1722990''>because</span>
  <span m=''1723240''>when</span> <span m=''1723340''>I</span> <span m=''1723400''>come</span>
  <span m=''1723650''>in and</span> <span m=''1723780''>say</span> <span m=''1723940''>define</span>
  <span m=''1724730''>y</span> <span m=''1726440''>to</span> <span m=''1726580''>be</span>
  <span m=''1726680''>the</span> <span m=''1726820''>integral</span> <span m=''1727210''>of</span>
  <span m=''1727290''>dy,</span> <span m=''1729090''>it</span> <span m=''1729220''>says,</span>
  <span m=''1729360''>oh,</span> <span m=''1729550''>the</span> <span m=''1729650''>integral</span>
  <span m=''1729750''>of</span> <span m=''1729800''>y--</span> <span m=''1730030''>huh?</span>
  <span m=''1731190''>Oh,</span> <span m=''1731300''>that''s</span> <span m=''1731510''>undefined.</span>
  <span m=''1733710''>So</span> <span m=''1733890''>I</span> <span m=''1733960''>can''t</span>
  <span m=''1735150''>write</span> <span m=''1735370''>this</span> <span m=''1735540''>definition</span>
  <span m=''1736000''>before</span> <span m=''1736320''>I''ve</span> <span m=''1736860''>written</span>
  <span m=''1737160''>this</span> <span m=''1737310''>one.</span> <span m=''1738770''>On</span>
  <span m=''1738880''>the</span> <span m=''1738990''>other</span> <span m=''1739110''>hand,</span>
  <span m=''1739250''>if</span> <span m=''1739340''>I</span> <span m=''1739390''>try</span>
  <span m=''1739560''>and</span> <span m=''1739620''>write</span> <span m=''1739820''>this</span>
  <span m=''1740010''>one</span> <span m=''1740170''>first,</span> <span m=''1740510''>it</span>
  <span m=''1740600''>says,</span> <span m=''1740770''>oh, I</span> <span m=''1740920''>define</span>
  <span m=''1741280''>y</span> <span m=''1741480''>to be</span> <span m=''1741680''>the</span>
  <span m=''1741790''>map</span> <span m=''1742100''>of</span> <span m=''1742290''>square</span>
  <span m=''1742450''>along</span> <span m=''1742720''>y?</span> <span m=''1743580''>Oh,</span>
  <span m=''1743710''>that''s</span> <span m=''1743800''>not</span> <span m=''1744100''>defined</span>
  <span m=''1744380''>yet.</span> <span m=''1745770''>So</span> <span m=''1745910''>I</span>
  <span m=''1745970''>can''t</span> <span m=''1746210''>write</span> <span m=''1746390''>this</span>
  <span m=''1746560''>one</span> <span m=''1746720''>first, and</span> <span m=''1747070''>I</span>
  <span m=''1747120''>can''t</span> <span m=''1747340''>write</span> <span m=''1747530''>that</span>
  <span m=''1747730''>one</span> <span m=''1747860''>first.</span> <span m=''1749060''>So</span>
  <span m=''1749210''>I</span> <span m=''1749270''>can''t</span> <span m=''1750510''>quite</span>
  <span m=''1750840''>play</span> <span m=''1751050''>this</span> <span m=''1751270''>game.</span>
  </p><p><span m=''1757560''>Well,</span> <span m=''1757690''>is there a</span> <span
  m=''1757850''>way</span> <span m=''1758130''>out?</span> <span m=''1760460''>See,</span>
  <span m=''1760800''>we</span> <span m=''1760890''>can</span> <span m=''1760980''>do</span>
  <span m=''1761070''>that</span> <span m=''1761200''>with</span> <span m=''1761340''>ones.</span>
  <span m=''1762200''>See,</span> <span m=''1762380''>over</span> <span m=''1762550''>here,</span>
  <span m=''1762720''>we</span> <span m=''1762860''>did</span> <span m=''1763020''>this</span>
  <span m=''1765180''>thing</span> <span m=''1765410''>ones,</span> <span m=''1767270''>and
  we</span> <span m=''1767380''>were</span> <span m=''1767540''>able</span> <span
  m=''1767820''>to</span> <span m=''1767920''>define</span> <span m=''1768340''>ones</span>
  <span m=''1768650''>in</span> <span m=''1768760''>terms</span> <span m=''1769090''>of</span>
  <span m=''1769200''>ones</span> <span m=''1769470''>because</span> <span m=''1770380''>of</span>
  <span m=''1770540''>this</span> <span m=''1770700''>delay</span> <span m=''1770990''>that</span>
  <span m=''1771130''>was</span> <span m=''1771280''>built</span> <span m=''1771520''>inside</span>
  <span m=''1772450''>because</span> <span m=''1772790''>cons-stream</span> <span
  m=''1773400''>had</span> <span m=''1773520''>a</span> <span m=''1773640''>delay.</span>
  <span m=''1774770''>Now,</span> <span m=''1774900''>why''s</span> <span m=''1775120''>it</span>
  <span m=''1775230''>sensible?</span> <span m=''1776070''>Why''s</span> <span m=''1776270''>it</span>
  <span m=''1776370''>sensible</span> <span m=''1776790''>for</span> <span m=''1776920''>cons-stream</span>
  <span m=''1777430''>to</span> <span m=''1777500''>be</span> <span m=''1777630''>built</span>
  <span m=''1777840''>with</span> <span m=''1777970''>this</span> <span m=''1778120''>delay?</span>
  <span m=''1780730''>The</span> <span m=''1780850''>reason</span> <span m=''1781130''>is</span>
  <span m=''1781260''>that</span> <span m=''1781380''>cons-stream</span> <span m=''1781940''>can</span>
  <span m=''1782080''>do</span> <span m=''1782210''>a</span> <span m=''1782250''>useful</span>
  <span m=''1782710''>thing</span> <span m=''1783570''>without</span> <span m=''1783940''>looking</span>
  <span m=''1784230''>at</span> <span m=''1784320''>its</span> <span m=''1784490''>tail.</span>
  <span m=''1785950''>See,</span> <span m=''1786150''>if</span> <span m=''1786280''>I</span>
  <span m=''1786350''>say</span> <span m=''1787470''>this</span> <span m=''1787690''>is</span>
  <span m=''1787830''>cons-stream</span> <span m=''1788400''>of</span> <span m=''1788600''>1</span>
  <span m=''1788790''>onto</span> <span m=''1789050''>something</span> <span m=''1789910''>without</span>
  <span m=''1790240''>knowing</span> <span m=''1790490''>anything</span> <span m=''1790970''>about</span>
  <span m=''1791230''>something,</span> <span m=''1792210''>I</span> <span m=''1792340''>know</span>
  <span m=''1792490''>that</span> <span m=''1792640''>the</span> <span m=''1792720''>stream</span>
  <span m=''1792980''>starts</span> <span m=''1793320''>off</span> <span m=''1793490''>with</span>
  <span m=''1793610''>1.</span> <span m=''1794870''>That''s</span> <span m=''1795060''>why</span>
  <span m=''1795190''>it was</span> <span m=''1795330''>sensible</span> <span m=''1795860''>to</span>
  <span m=''1795920''>build</span> <span m=''1796160''>something</span> <span m=''1796470''>like</span>
  <span m=''1796660''>cons-stream.</span> <span m=''1799960''>So</span> <span m=''1800110''>we</span>
  <span m=''1800200''>put</span> <span m=''1800380''>a</span> <span m=''1800440''>delay</span>
  <span m=''1800780''>in</span> <span m=''1801090''>there,</span> <span m=''1801440''>and</span>
  <span m=''1801600''>that</span> <span m=''1801760''>allows</span> <span m=''1802190''>us</span>
  <span m=''1802320''>to</span> <span m=''1802460''>have</span> <span m=''1802610''>this</span>
  <span m=''1802690''>sort</span> <span m=''1802850''>of</span> <span m=''1803000''>self-referential</span>
  <span m=''1804010''>definition.</span> </p><p><span m=''1806320''>Well,</span> <span
  m=''1806500''>integral</span> <span m=''1806740''>is</span> <span m=''1806920''>a</span>
  <span m=''1806960''>little</span> <span m=''1807130''>bit</span> <span m=''1807270''>the</span>
  <span m=''1807340''>same</span> <span m=''1807630''>way.</span> <span m=''1808190''>See,</span>
  <span m=''1808370''>notice</span> <span m=''1809350''>for</span> <span m=''1809470''>an</span>
  <span m=''1809600''>integral,</span> <span m=''1811980''>I</span> <span m=''1812120''>can--</span>
  <span m=''1814620''>let''s</span> <span m=''1814750''>go</span> <span m=''1814810''>back</span>
  <span m=''1814990''>and</span> <span m=''1815070''>look</span> <span m=''1815160''>at</span>
  <span m=''1815250''>integral</span> <span m=''1815550''>for a</span> <span m=''1815700''>second.</span>
  <span m=''1817580''>See,</span> <span m=''1817690''>notice</span> <span m=''1818010''>integral,</span>
  <span m=''1821360''>it</span> <span m=''1821500''>makes</span> <span m=''1821740''>sense</span>
  <span m=''1822040''>to</span> <span m=''1822150''>say</span> <span m=''1822960''>what''s</span>
  <span m=''1823200''>the</span> <span m=''1823440''>first</span> <span m=''1824010''>thing</span>
  <span m=''1824310''>in</span> <span m=''1824440''>the</span> <span m=''1824580''>integral</span>
  <span m=''1826100''>without</span> <span m=''1826470''>knowing</span> <span m=''1826760''>the</span>
  <span m=''1826820''>stream</span> <span m=''1827110''>that</span> <span m=''1827210''>you''re</span>
  <span m=''1827390''>integrating.</span> <span m=''1828970''>Because</span> <span
  m=''1829080''>the</span> <span m=''1829160''>first</span> <span m=''1829490''>thing</span>
  <span m=''1829630''>in</span> <span m=''1829700''>the</span> <span m=''1829780''>integral</span>
  <span m=''1830130''>is</span> <span m=''1830220''>always</span> <span m=''1830500''>going</span>
  <span m=''1830590''>to</span> <span m=''1830680''>be</span> <span m=''1830770''>the</span>
  <span m=''1830900''>initial</span> <span m=''1831250''>value</span> <span m=''1831550''>that</span>
  <span m=''1831700''>you''re</span> <span m=''1831850''>handed.</span> <span m=''1833140''>So</span>
  <span m=''1833320''>integral</span> <span m=''1833930''>could</span> <span m=''1834240''>be</span>
  <span m=''1834560''>a</span> <span m=''1834670''>procedure</span> <span m=''1835180''>like</span>
  <span m=''1835500''>cons-stream.</span> <span m=''1837090''>You</span> <span m=''1837220''>could</span>
  <span m=''1837340''>define</span> <span m=''1837790''>it,</span> <span m=''1838150''>and</span>
  <span m=''1838330''>then</span> <span m=''1838500''>even</span> <span m=''1838880''>before</span>
  <span m=''1839250''>it</span> <span m=''1839360''>knows</span> <span m=''1839590''>what</span>
  <span m=''1839710''>it''s</span> <span m=''1839830''>supposed</span> <span m=''1840010''>to</span>
  <span m=''1840190''>be</span> <span m=''1840300''>integrating,</span> <span m=''1842860''>it</span>
  <span m=''1843160''>knows</span> <span m=''1843470''>enough</span> <span m=''1843730''>to</span>
  <span m=''1843840''>say</span> <span m=''1844020''>what</span> <span m=''1844210''>its</span>
  <span m=''1844360''>initial</span> <span m=''1844650''>value</span> <span m=''1845030''>is.</span>
  </p><p><span m=''1846710''>So</span> <span m=''1846880''>we</span> <span m=''1847000''>can</span>
  <span m=''1847120''>make</span> <span m=''1847270''>a</span> <span m=''1847310''>smarter</span>
  <span m=''1847760''>integral,</span> <span m=''1848350''>which</span> <span m=''1848570''>is</span>
  <span m=''1848660''>aha,</span> <span m=''1848740''>you''re</span> <span m=''1849150''>going
  to</span> <span m=''1849420''>give me</span> <span m=''1849490''>a stream</span>
  <span m=''1849930''>to</span> <span m=''1850040''>integrate</span> <span m=''1850850''>and</span>
  <span m=''1851010''>an</span> <span m=''1851120''>initial</span> <span m=''1851390''>value,</span>
  <span m=''1852090''>but</span> <span m=''1852230''>I</span> <span m=''1852290''>really</span>
  <span m=''1852560''>don''t</span> <span m=''1852700''>have</span> <span m=''1852850''>to</span>
  <span m=''1852950''>look</span> <span m=''1853150''>at</span> <span m=''1853500''>that</span>
  <span m=''1853710''>stream</span> <span m=''1854030''>that</span> <span m=''1854140''>I''m</span>
  <span m=''1854240''>supposed</span> <span m=''1854420''>to</span> <span m=''1854610''>integrate</span>
  <span m=''1855270''>until</span> <span m=''1855510''>you</span> <span m=''1855660''>ask</span>
  <span m=''1855830''>me</span> <span m=''1855890''>to</span> <span m=''1855960''>work</span>
  <span m=''1856210''>down</span> <span m=''1856430''>the</span> <span m=''1856490''>stream.</span>
  <span m=''1858430''>In</span> <span m=''1858560''>other</span> <span m=''1858680''>words,</span>
  <span m=''1859050''>integral</span> <span m=''1859860''>can</span> <span m=''1860000''>be</span>
  <span m=''1860100''>like</span> <span m=''1860300''>cons-stream, and</span> <span
  m=''1860730''>you</span> <span m=''1860870''>can</span> <span m=''1861010''>expect</span>
  <span m=''1861720''>that</span> <span m=''1862200''>there''s</span> <span m=''1862370''>going</span>
  <span m=''1862460''>to</span> <span m=''1862560''>be</span> <span m=''1862650''>a</span>
  <span m=''1862690''>delay</span> <span m=''1863110''>around</span> <span m=''1863410''>its</span>
  <span m=''1863530''>integrand.</span> <span m=''1863710''>And</span> <span m=''1864020''>we</span>
  <span m=''1864130''>can</span> <span m=''1864250''>write</span> <span m=''1864570''>that.</span>
  <span m=''1865610''>Here''s</span> <span m=''1865850''>a</span> <span m=''1865910''>procedure</span>
  <span m=''1866290''>that</span> <span m=''1866450''>does</span> <span m=''1866690''>that.</span>
  </p><p><span m=''1867650''>Another</span> <span m=''1867970''>version</span> <span
  m=''1868270''>of</span> <span m=''1868340''>integral,</span> <span m=''1868900''>and</span>
  <span m=''1869040''>this</span> <span m=''1869160''>is</span> <span m=''1869220''>almost</span>
  <span m=''1869560''>like</span> <span m=''1869720''>the</span> <span m=''1869810''>previous</span>
  <span m=''1870250''>one,</span> <span m=''1871190''>except</span> <span m=''1871870''>the</span>
  <span m=''1872090''>stream</span> <span m=''1872510''>it''s</span> <span m=''1872670''>going</span>
  <span m=''1872730''>to</span> <span m=''1872790''>get</span> <span m=''1873020''>in</span>
  <span m=''1873800''>is</span> <span m=''1873960''>going</span> <span m=''1874040''>to</span>
  <span m=''1874120''>expect</span> <span m=''1874510''>to</span> <span m=''1874600''>be</span>
  <span m=''1874730''>a</span> <span m=''1874780''>delayed</span> <span m=''1875310''>object.</span>
  <span m=''1877110''>And</span> <span m=''1877230''>how</span> <span m=''1877380''>does</span>
  <span m=''1877530''>this</span> <span m=''1877660''>integral</span> <span m=''1878050''>work?</span>
  <span m=''1878850''>Well,</span> <span m=''1879620''>the</span> <span m=''1879780''>little</span>
  <span m=''1880010''>thing</span> <span m=''1880200''>it''s</span> <span m=''1880350''>going</span>
  <span m=''1880420''>to</span> <span m=''1880500''>define</span> <span m=''1880910''>inside
  of</span> <span m=''1881340''>itself</span> <span m=''1882090''>says</span> <span
  m=''1883100''>on</span> <span m=''1883260''>the</span> <span m=''1883330''>cons-stream,</span>
  <span m=''1884750''>the</span> <span m=''1884870''>initial</span> <span m=''1885170''>value
  is</span> <span m=''1885530''>the</span> <span m=''1885650''>initial</span> <span
  m=''1885940''>value,</span> <span m=''1887190''>but</span> <span m=''1887890''>only</span>
  <span m=''1888260''>inside</span> <span m=''1888740''>of</span> <span m=''1888790''>that</span>
  <span m=''1888970''>cons-stream,</span> <span m=''1889750''>and</span> <span m=''1889880''>remember,</span>
  <span m=''1890190''>there''s</span> <span m=''1890410''>going</span> <span m=''1890510''>to</span>
  <span m=''1890600''>be</span> <span m=''1890700''>a</span> <span m=''1891070''>hidden</span>
  <span m=''1891340''>delay</span> <span m=''1891630''>inside</span> <span m=''1892040''>here.</span>
  <span m=''1894950''>Only</span> <span m=''1895350''>inside</span> <span m=''1895670''>of
  that</span> <span m=''1895760''>cons-stream</span> <span m=''1896940''>will</span>
  <span m=''1897170''>I</span> <span m=''1897890''>start</span> <span m=''1898260''>looking</span>
  <span m=''1898730''>at</span> <span m=''1900400''>what</span> <span m=''1900570''>the</span>
  <span m=''1900680''>actual</span> <span m=''1901100''>delayed</span> <span m=''1901410''>object</span>
  <span m=''1901820''>is.</span> </p><p><span m=''1903180''>So</span> <span m=''1903350''>my</span>
  <span m=''1903520''>answer</span> <span m=''1903880''>is</span> <span m=''1904120''>the</span>
  <span m=''1904350''>first</span> <span m=''1904610''>thing''s</span> <span m=''1904790''>the</span>
  <span m=''1904910''>initial</span> <span m=''1905220''>value.</span> <span m=''1905970''>If</span>
  <span m=''1906120''>anybody</span> <span m=''1906500''>now</span> <span m=''1906710''>asks</span>
  <span m=''1906980''>me</span> <span m=''1907100''>for</span> <span m=''1907230''>my</span>
  <span m=''1907380''>tail,</span> <span m=''1908430''>at</span> <span m=''1908620''>that</span>
  <span m=''1908970''>point,</span> <span m=''1910050''>I''m</span> <span m=''1910190''>going</span>
  <span m=''1910280''>to</span> <span m=''1910360''>force</span> <span m=''1910780''>that</span>
  <span m=''1910960''>delayed</span> <span m=''1911250''>object--</span> <span m=''1912680''>and
  I''ll</span> <span m=''1913000''>call that</span> <span m=''1913170''>s--</span>
  <span m=''1914500''>and</span> <span m=''1914640''>I</span> <span m=''1914710''>do
  the</span> <span m=''1914830''>add</span> <span m=''1914980''>streams.</span> <span
  m=''1916410''>So</span> <span m=''1916610''>this</span> <span m=''1916780''>is</span>
  <span m=''1917620''>an</span> <span m=''1917690''>integral</span> <span m=''1918060''>which</span>
  <span m=''1918230''>is</span> <span m=''1918300''>sort</span> <span m=''1918440''>of</span>
  <span m=''1918580''>like</span> <span m=''1918840''>cons-stream.</span> <span m=''1919260''>It''s</span>
  <span m=''1919390''>not</span> <span m=''1919620''>going</span> <span m=''1919700''>to</span>
  <span m=''1919780''>actually</span> <span m=''1920330''>try</span> <span m=''1920580''>and</span>
  <span m=''1921480''>see</span> <span m=''1921840''>what</span> <span m=''1922010''>you</span>
  <span m=''1922140''>handed</span> <span m=''1922510''>it</span> <span m=''1923930''>as</span>
  <span m=''1924120''>the</span> <span m=''1924180''>thing</span> <span m=''1924380''>to</span>
  <span m=''1924560''>integrate</span> <span m=''1925050''>until</span> <span m=''1925740''>you</span>
  <span m=''1925910''>look</span> <span m=''1926080''>past</span> <span m=''1926400''>the</span>
  <span m=''1926490''>first</span> <span m=''1926800''>element.</span> <span m=''1930120''>And</span>
  <span m=''1930250''>if</span> <span m=''1930330''>we</span> <span m=''1930420''>do</span>
  <span m=''1930580''>that</span> <span m=''1931620''>and</span> <span m=''1931760''>we</span>
  <span m=''1931870''>can</span> <span m=''1932000''>make</span> <span m=''1932210''>this</span>
  <span m=''1932400''>work,</span> <span m=''1933130''>all</span> <span m=''1933540''>we</span>
  <span m=''1933650''>have</span> <span m=''1933810''>to</span> <span m=''1933900''>do</span>
  <span m=''1934050''>here</span> <span m=''1934770''>is</span> <span m=''1935890''>say</span>
  <span m=''1936120''>define</span> <span m=''1936720''>y</span> <span m=''1937320''>to</span>
  <span m=''1937510''>the</span> <span m=''1937800''>integral</span> <span m=''1938880''>of</span>
  <span m=''1941390''>delay</span> <span m=''1941820''>of</span> <span m=''1941960''>y,</span>
  <span m=''1943860''>of</span> <span m=''1944120''>delay</span> <span m=''1944440''>of</span>
  <span m=''1944550''>dy.</span> <span m=''1947090''>So</span> <span m=''1947360''>y</span>
  <span m=''1947660''>is</span> <span m=''1947770''>going</span> <span m=''1947880''>to</span>
  <span m=''1948000''>be</span> <span m=''1948200''>the</span> <span m=''1948660''>integral</span>
  <span m=''1951640''>of</span> <span m=''1951960''>delay</span> <span m=''1952310''>of</span>
  <span m=''1952420''>dy</span> <span m=''1953380''>starting</span> <span m=''1953830''>at</span>
  <span m=''1954150''>1,</span> <span m=''1954390''>and</span> <span m=''1954450''>now</span>
  <span m=''1954590''>this</span> <span m=''1954760''>will</span> <span m=''1954850''>work.</span>
  <span m=''1955280''>Because</span> <span m=''1955610''>I</span> <span m=''1955700''>type</span>
  <span m=''1955980''>in</span> <span m=''1956180''>the</span> <span m=''1956320''>definition</span>
  <span m=''1956810''>of</span> <span m=''1956920''>y,</span> <span m=''1957175''>and</span>
  <span m=''1957430''>that</span> <span m=''1958190''>says,</span> <span m=''1958380''>oh,
  I''m</span> <span m=''1958630''>supposed to use</span> <span m=''1958730''>the</span>
  <span m=''1958880''>integral</span> <span m=''1959340''>of</span> <span m=''1960470''>something</span>
  <span m=''1960790''>I</span> <span m=''1960840''>don''t</span> <span m=''1960970''>care</span>
  <span m=''1961150''>about</span> <span m=''1961370''>right</span> <span m=''1961570''>now</span>
  <span m=''1961670''>because</span> <span m=''1961860''>it''s</span> <span m=''1962010''>a</span>
  <span m=''1962060''>delay.</span> </p><p><span m=''1964600''>And</span> <span m=''1964780''>these</span>
  <span m=''1965030''>things,</span> <span m=''1965330''>now</span> <span m=''1965460''>you</span>
  <span m=''1965590''>define</span> <span m=''1965940''>dy.</span> <span m=''1966320''>Now,</span>
  <span m=''1966500''>y</span> <span m=''1966730''>is</span> <span m=''1966810''>defined.</span>
  <span m=''1967550''>So when I</span> <span m=''1967940''>define</span> <span m=''1968300''>dy,</span>
  <span m=''1969190''>it</span> <span m=''1969270''>can</span> <span m=''1969390''>see</span>
  <span m=''1969560''>that</span> <span m=''1969720''>definition</span> <span m=''1970180''>for</span>
  <span m=''1970320''>y.</span> <span m=''1971700''>Everything is</span> <span m=''1972090''>now</span>
  <span m=''1972250''>started</span> <span m=''1972670''>up.</span> <span m=''1972840''>Both</span>
  <span m=''1973040''>streams</span> <span m=''1973280''>have</span> <span m=''1973410''>their</span>
  <span m=''1973520''>first</span> <span m=''1973810''>element.</span> <span m=''1974920''>And</span>
  <span m=''1975080''>then</span> <span m=''1975160''>when</span> <span m=''1975240''>I</span>
  <span m=''1975300''>start</span> <span m=''1975560''>mapping</span> <span m=''1975950''>down,</span>
  <span m=''1976230''>looking</span> <span m=''1976490''>at</span> <span m=''1976600''>successive</span>
  <span m=''1977030''>elements,</span> <span m=''1977400''>both</span> <span m=''1977590''>y</span>
  <span m=''1977870''>and</span> <span m=''1978000''>dy</span> <span m=''1978090''>are</span>
  <span m=''1978410''>defined.</span> <span m=''1980590''>So</span> <span m=''1980760''>there''s</span>
  <span m=''1980950''>a</span> <span m=''1980990''>little</span> <span m=''1981210''>game</span>
  <span m=''1981450''>you</span> <span m=''1981560''>can</span> <span m=''1981670''>play</span>
  <span m=''1982160''>that</span> <span m=''1982350''>goes</span> <span m=''1982520''>a</span>
  <span m=''1982570''>little</span> <span m=''1982820''>bit</span> <span m=''1983440''>beyond</span>
  <span m=''1984670''>just</span> <span m=''1984970''>using</span> <span m=''1985270''>the</span>
  <span m=''1985370''>delay</span> <span m=''1985940''>that''s</span> <span m=''1986130''>hidden</span>
  <span m=''1986350''>inside</span> <span m=''1986700''>streams.</span> <span m=''1988390''>Questions?</span>
  <span m=''1993178''>OK,</span> <span m=''1993650''>let''s</span> <span m=''1993880''>take</span>
  <span m=''1994020''>a</span> <span m=''1994060''>break.</span> </p><p><span m=''2047300''>Well,</span>
  <span m=''2048409''>just</span> <span m=''2048670''>before</span> <span m=''2048920''>the</span>
  <span m=''2049030''>break,</span> <span m=''2050571''>I''m</span> <span m=''2050949''>not</span>
  <span m=''2051080''>sure</span> <span m=''2051199''>if</span> <span m=''2051270''>you</span>
  <span m=''2051370''>noticed</span> <span m=''2051739''>it,</span> <span m=''2051820''>but</span>
  <span m=''2051949''>something</span> <span m=''2052290''>nasty</span> <span m=''2052690''>started</span>
  <span m=''2053130''>to happen.</span> <span m=''2054320''>We''ve</span> <span m=''2055000''>been</span>
  <span m=''2055120''>going</span> <span m=''2055409''>along</span> <span m=''2057409''>with</span>
  <span m=''2057560''>the</span> <span m=''2057679''>streams</span> <span m=''2059139''>and</span>
  <span m=''2059340''>divorcing</span> <span m=''2060710''>time</span> <span m=''2061040''>in</span>
  <span m=''2061110''>the</span> <span m=''2061190''>programs</span> <span m=''2061630''>from</span>
  <span m=''2061730''>time</span> <span m=''2062010''>in</span> <span m=''2062090''>the</span>
  <span m=''2062170''>computers,</span> <span m=''2062900''>and</span> <span m=''2063040''>all</span>
  <span m=''2063270''>that</span> <span m=''2064580''>divorcing</span> <span m=''2065010''>got</span>
  <span m=''2065179''>hidden</span> <span m=''2065440''>inside</span> <span m=''2065800''>the</span>
  <span m=''2065850''>streams.</span> <span m=''2067310''>And</span> <span m=''2067520''>then</span>
  <span m=''2067670''>at</span> <span m=''2067750''>the</span> <span m=''2067840''>very</span>
  <span m=''2068130''>end,</span> <span m=''2068320''>we</span> <span m=''2068420''>saw</span>
  <span m=''2068639''>that</span> <span m=''2068830''>sometimes</span> <span m=''2069770''>in</span>
  <span m=''2069909''>order</span> <span m=''2070040''>to</span> <span m=''2070120''>really</span>
  <span m=''2070429''>take</span> <span m=''2070679''>advantage</span> <span m=''2071540''>of</span>
  <span m=''2071699''>this</span> <span m=''2071850''>method,</span> <span m=''2072179''>you</span>
  <span m=''2072260''>have</span> <span m=''2072420''>to</span> <span m=''2072580''>pull</span>
  <span m=''2072850''>out</span> <span m=''2073650''>other</span> <span m=''2073900''>delays.</span>
  <span m=''2074389''>You have</span> <span m=''2074510''>to</span> <span m=''2074610''>write</span>
  <span m=''2074810''>some</span> <span m=''2074960''>explicit</span> <span m=''2075460''>delays</span>
  <span m=''2076060''>that</span> <span m=''2076179''>are</span> <span m=''2076290''>not</span>
  <span m=''2076480''>hidden</span> <span m=''2076800''>inside</span> <span m=''2077190''>that</span>
  <span m=''2077370''>cons-stream.</span> </p><p><span m=''2079030''>And</span> <span
  m=''2079380''>I</span> <span m=''2079510''>did</span> <span m=''2079630''>a</span>
  <span m=''2079690''>very</span> <span m=''2080050''>simple</span> <span m=''2080409''>example</span>
  <span m=''2080810''>with</span> <span m=''2080949''>differential</span> <span m=''2081400''>equations,</span>
  <span m=''2082350''>but</span> <span m=''2082520''>if</span> <span m=''2082600''>you</span>
  <span m=''2082670''>have</span> <span m=''2082790''>some</span> <span m=''2082980''>very</span>
  <span m=''2083260''>complicated</span> <span m=''2083830''>system</span> <span m=''2084150''>with</span>
  <span m=''2084250''>all</span> <span m=''2084449''>kinds</span> <span m=''2084730''>of</span>
  <span m=''2084800''>self-loops,</span> <span m=''2085929''>it</span> <span m=''2086040''>becomes</span>
  <span m=''2086389''>very,</span> <span m=''2087010''>very</span> <span m=''2087310''>difficult</span>
  <span m=''2087770''>to</span> <span m=''2087820''>see</span> <span m=''2088010''>where</span>
  <span m=''2088280''>you</span> <span m=''2088420''>need</span> <span m=''2088679''>those</span>
  <span m=''2088949''>delays.</span> <span m=''2089929''>And</span> <span m=''2090060''>if</span>
  <span m=''2090150''>you</span> <span m=''2090250''>leave</span> <span m=''2090420''>them</span>
  <span m=''2090540''>out</span> <span m=''2090699''>by</span> <span m=''2090810''>mistake,</span>
  <span m=''2091440''>it</span> <span m=''2091570''>becomes</span> <span m=''2091860''>very,</span>
  <span m=''2092150''>very</span> <span m=''2092389''>difficult</span> <span m=''2092760''>to</span>
  <span m=''2092830''>see</span> <span m=''2092969''>why</span> <span m=''2093270''>the
  thing</span> <span m=''2093360''>maybe</span> <span m=''2093699''>isn''t</span>
  <span m=''2093830''>working.</span> <span m=''2095550''>So</span> <span m=''2095710''>that''s</span>
  <span m=''2096380''>kind</span> <span m=''2096590''>of</span> <span m=''2096690''>mess,</span>
  <span m=''2097530''>that</span> <span m=''2098160''>by</span> <span m=''2098900''>getting</span>
  <span m=''2099200''>this</span> <span m=''2099380''>power</span> <span m=''2100180''>and</span>
  <span m=''2100330''>allowing</span> <span m=''2100740''>us</span> <span m=''2100860''>to</span>
  <span m=''2100960''>use</span> <span m=''2101130''>delay,</span> <span m=''2101480''>we</span>
  <span m=''2102030''>end</span> <span m=''2102360''>up</span> <span m=''2102460''>with</span>
  <span m=''2102560''>some</span> <span m=''2102720''>very</span> <span m=''2103030''>complicated</span>
  <span m=''2103610''>programming</span> <span m=''2104110''>sometimes,</span> <span
  m=''2104415''>because</span> <span m=''2104720''>it</span> <span m=''2104850''>can''t</span>
  <span m=''2105080''>all</span> <span m=''2105320''>be</span> <span m=''2105450''>hidden</span>
  <span m=''2105680''>inside</span> <span m=''2106070''>the</span> <span m=''2106200''>streams.</span>
  </p><p><span m=''2108690''>Well,</span> <span m=''2108860''>is there a</span> <span
  m=''2108960''>way</span> <span m=''2109150''>out</span> <span m=''2109290''>of</span>
  <span m=''2109430''>that?</span> <span m=''2111036''>Yeah,</span> <span m=''2111470''>there</span>
  <span m=''2111750''>is</span> <span m=''2111850''>a</span> <span m=''2111900''>way
  out of</span> <span m=''2112260''>that.</span> <span m=''2113480''>We</span> <span
  m=''2113740''>could</span> <span m=''2114860''>change</span> <span m=''2115220''>the</span>
  <span m=''2115320''>language</span> <span m=''2115750''>so</span> <span m=''2115870''>that</span>
  <span m=''2116190''>all</span> <span m=''2116430''>procedures</span> <span m=''2116990''>acted</span>
  <span m=''2117230''>like</span> <span m=''2117370''>cons-stream,</span> <span m=''2119030''>so</span>
  <span m=''2119220''>that</span> <span m=''2119770''>every</span> <span m=''2120060''>procedure</span>
  <span m=''2120540''>automatically</span> <span m=''2122320''>has</span> <span m=''2122560''>an</span>
  <span m=''2122640''>implicit</span> <span m=''2123520''>delay</span> <span m=''2124550''>around
  its</span> <span m=''2124970''>arguments.</span> <span m=''2125450''>And</span>
  <span m=''2125520''>what</span> <span m=''2125650''>would</span> <span m=''2125760''>that</span>
  <span m=''2125970''>mean?</span> <span m=''2127520''>That</span> <span m=''2127660''>would</span>
  <span m=''2127800''>mean</span> <span m=''2128250''>when</span> <span m=''2128400''>you</span>
  <span m=''2128500''>call</span> <span m=''2128800''>a</span> <span m=''2128850''>procedure,</span>
  <span m=''2130090''>the</span> <span m=''2130360''>arguments</span> <span m=''2130760''>wouldn''t</span>
  <span m=''2130950''>get</span> <span m=''2131090''>evaluated.</span> <span m=''2132210''>Instead,</span>
  <span m=''2132930''>they''d</span> <span m=''2133160''>only</span> <span m=''2133360''>be</span>
  <span m=''2133510''>evaluated</span> <span m=''2134080''>when</span> <span m=''2134190''>you
  need</span> <span m=''2134550''>them,</span> <span m=''2134820''>so</span> <span
  m=''2134950''>they</span> <span m=''2135030''>might</span> <span m=''2135210''>be</span>
  <span m=''2135300''>passed</span> <span m=''2135670''>off</span> <span m=''2135790''>to</span>
  <span m=''2135880''>some</span> <span m=''2136070''>other</span> <span m=''2136230''>procedure,</span>
  <span m=''2136670''>which</span> <span m=''2136830''>wouldn''t</span> <span m=''2137040''>evaluate</span>
  <span m=''2137550''>them</span> <span m=''2137730''>either.</span> </p><p><span
  m=''2139260''>So</span> <span m=''2139420''>all</span> <span m=''2139540''>these</span>
  <span m=''2139820''>procedures</span> <span m=''2140310''>would</span> <span m=''2140430''>be</span>
  <span m=''2140540''>passing</span> <span m=''2140900''>promises</span> <span m=''2141420''>around.</span>
  <span m=''2142150''>And</span> <span m=''2142280''>then</span> <span m=''2142420''>finally</span>
  <span m=''2142770''>maybe</span> <span m=''2143180''>when</span> <span m=''2143320''>you</span>
  <span m=''2143430''>finally</span> <span m=''2143950''>got</span> <span m=''2144150''>down</span>
  <span m=''2144620''>to</span> <span m=''2144770''>having</span> <span m=''2144970''>to</span>
  <span m=''2145090''>look</span> <span m=''2145510''>at</span> <span m=''2145740''>the</span>
  <span m=''2146300''>value</span> <span m=''2146760''>of</span> <span m=''2146830''>something</span>
  <span m=''2147350''>that</span> <span m=''2147490''>was</span> <span m=''2147630''>handed</span>
  <span m=''2147900''>to</span> <span m=''2147970''>a</span> <span m=''2148040''>primitive</span>
  <span m=''2148420''>operator</span> <span m=''2149300''>would you</span> <span m=''2149550''>actually</span>
  <span m=''2149910''>start</span> <span m=''2150140''>calling</span> <span m=''2150500''>in</span>
  <span m=''2150590''>all</span> <span m=''2150720''>those</span> <span m=''2150910''>promises.</span>
  <span m=''2152380''>If</span> <span m=''2152580''>we</span> <span m=''2152670''>did</span>
  <span m=''2152910''>that,</span> <span m=''2153260''>since</span> <span m=''2153670''>everything</span>
  <span m=''2154090''>would</span> <span m=''2154200''>have</span> <span m=''2154360''>a</span>
  <span m=''2154400''>uniform</span> <span m=''2155020''>delay,</span> <span m=''2157090''>then</span>
  <span m=''2157360''>you</span> <span m=''2157450''>wouldn''t</span> <span m=''2157580''>have</span>
  <span m=''2157700''>to</span> <span m=''2157830''>write</span> <span m=''2158040''>any</span>
  <span m=''2158220''>explicit</span> <span m=''2158690''>delays,</span> <span m=''2158945''>because
  it</span> <span m=''2159200''>would</span> <span m=''2159340''>be</span> <span m=''2159490''>automatically</span>
  <span m=''2160130''>built</span> <span m=''2160370''>into</span> <span m=''2160490''>the</span>
  <span m=''2160610''>way the</span> <span m=''2160750''>language</span> <span m=''2161190''>works.</span>
  </p><p><span m=''2162920''>Or</span> <span m=''2163370''>another</span> <span m=''2163670''>way</span>
  <span m=''2163760''>to</span> <span m=''2163840''>say</span> <span m=''2164090''>that,</span>
  <span m=''2165090''>technically</span> <span m=''2165620''>what</span> <span m=''2165760''>I''m</span>
  <span m=''2165870''>describing</span> <span m=''2167300''>is</span> <span m=''2167510''>what''s</span>
  <span m=''2167720''>called--</span> <span m=''2169130''>if</span> <span m=''2169250''>we</span>
  <span m=''2169360''>did</span> <span m=''2169530''>that,</span> <span m=''2169690''>our</span>
  <span m=''2169800''>language</span> <span m=''2170260''>would</span> <span m=''2170420''>be</span>
  <span m=''2172140''>so-called</span> <span m=''2172720''>normal-order</span> <span
  m=''2175240''>evaluation</span> <span m=''2176070''>language</span> <span m=''2180240''>versus</span>
  <span m=''2181990''>what</span> <span m=''2182120''>we''ve</span> <span m=''2182270''>actually</span>
  <span m=''2182600''>been</span> <span m=''2182720''>working</span> <span m=''2183140''>with,</span>
  <span m=''2183960''>which</span> <span m=''2184140''>is</span> <span m=''2184260''>called</span>
  <span m=''2184450''>applicative</span> <span m=''2184725''>order--</span> <span
  m=''2191240''>versus</span> <span m=''2192260''>applicative-order</span> <span m=''2193000''>evaluation.</span>
  </p><p><span m=''2194560''>And</span> <span m=''2194700''>remember</span> <span
  m=''2195180''>the</span> <span m=''2195270''>substitution</span> <span m=''2195880''>model</span>
  <span m=''2196130''>for</span> <span m=''2196340''>applicative</span> <span m=''2196670''>order.
  It</span> <span m=''2197000''>says</span> <span m=''2197170''>when</span> <span
  m=''2197300''>you</span> <span m=''2197390''>go</span> <span m=''2197570''>and</span>
  <span m=''2199170''>evaluate</span> <span m=''2199640''>a</span> <span m=''2199690''>combination,</span>
  <span m=''2200590''>you</span> <span m=''2200690''>find</span> <span m=''2200890''>the</span>
  <span m=''2200950''>values</span> <span m=''2201370''>of</span> <span m=''2201460''>all</span>
  <span m=''2201540''>the</span> <span m=''2201610''>pieces.</span> <span m=''2203590''>You</span>
  <span m=''2203770''>evaluate</span> <span m=''2204320''>the</span> <span m=''2204410''>arguments</span>
  <span m=''2204940''>and</span> <span m=''2205070''>then</span> <span m=''2205200''>you</span>
  <span m=''2205690''>substitute</span> <span m=''2206220''>them</span> <span m=''2206370''>in</span>
  <span m=''2206430''>the</span> <span m=''2206510''>body</span> <span m=''2206810''>of</span>
  <span m=''2206870''>the</span> <span m=''2206930''>procedure.</span> <span m=''2207600''>Normal</span>
  <span m=''2207990''>order</span> <span m=''2208490''>says</span> <span m=''2208790''>no,</span>
  <span m=''2208930''>don''t</span> <span m=''2209110''>do</span> <span m=''2209230''>that.</span>
  <span m=''2209890''>What</span> <span m=''2210140''>you</span> <span m=''2210240''>do</span>
  <span m=''2210460''>is</span> <span m=''2211070''>effectively</span> <span m=''2212740''>substitute</span>
  <span m=''2213360''>in</span> <span m=''2213450''>the</span> <span m=''2213530''>body</span>
  <span m=''2213840''>of</span> <span m=''2213910''>the</span> <span m=''2213980''>procedure,</span>
  <span m=''2214460''>but</span> <span m=''2214610''>instead</span> <span m=''2214880''>of</span>
  <span m=''2214960''>evaluating</span> <span m=''2215590''>the</span> <span m=''2215690''>arguments,</span>
  <span m=''2216400''>you</span> <span m=''2216640''>just</span> <span m=''2216820''>put</span>
  <span m=''2216950''>a</span> <span m=''2217000''>promise</span> <span m=''2217370''>to</span>
  <span m=''2217480''>compute</span> <span m=''2217790''>them</span> <span m=''2217910''>there.</span>
  <span m=''2218640''>Or</span> <span m=''2219000''>another</span> <span m=''2219200''>way</span>
  <span m=''2219320''>to</span> <span m=''2219390''>say</span> <span m=''2219630''>that</span>
  <span m=''2219820''>is</span> <span m=''2219920''>you</span> <span m=''2220010''>take</span>
  <span m=''2220230''>the</span> <span m=''2220320''>expressions</span> <span m=''2220920''>for</span>
  <span m=''2221030''>the</span> <span m=''2221130''>arguments,</span> <span m=''2221590''>if</span>
  <span m=''2221690''>you</span> <span m=''2221790''>like,</span> <span m=''2222310''>and</span>
  <span m=''2222490''>substitute</span> <span m=''2223040''>them</span> <span m=''2223220''>in</span>
  <span m=''2223300''>the</span> <span m=''2223370''>body</span> <span m=''2223690''>of</span>
  <span m=''2223750''>the</span> <span m=''2223830''>procedure</span> <span m=''2224280''>and</span>
  <span m=''2224370''>go</span> <span m=''2224520''>on,</span> <span m=''2225200''>and</span>
  <span m=''2225340''>never</span> <span m=''2225590''>really</span> <span m=''2225890''>simplify</span>
  <span m=''2226320''>anything</span> <span m=''2227140''>until</span> <span m=''2227360''>you</span>
  <span m=''2227450''>get</span> <span m=''2227580''>down</span> <span m=''2227770''>to</span>
  <span m=''2227870''>a</span> <span m=''2227920''>primitive</span> <span m=''2228250''>operator.</span>
  <span m=''2229340''>So that</span> <span m=''2229595''>would be</span> <span m=''2229850''>a</span>
  <span m=''2229900''>normal-order</span> <span m=''2230490''>language.</span> </p><p><span
  m=''2231840''>Well,</span> <span m=''2232270''>why don''t</span> <span m=''2232550''>we</span>
  <span m=''2232640''>do</span> <span m=''2232800''>that?</span> <span m=''2233490''>Because</span>
  <span m=''2233910''>if</span> <span m=''2234080''>we</span> <span m=''2234170''>did,</span>
  <span m=''2235030''>we''d</span> <span m=''2235140''>get</span> <span m=''2235310''>all</span>
  <span m=''2235540''>the</span> <span m=''2235660''>advantages</span> <span m=''2236140''>of</span>
  <span m=''2236220''>delayed</span> <span m=''2236550''>evaluation</span> <span m=''2238000''>with</span>
  <span m=''2238150''>none</span> <span m=''2238330''>of</span> <span m=''2238410''>the</span>
  <span m=''2238470''>mess.</span> <span m=''2238940''>In</span> <span m=''2239100''>fact,</span>
  <span m=''2239440''>if</span> <span m=''2239530''>we</span> <span m=''2239640''>did</span>
  <span m=''2239900''>that</span> <span m=''2240430''>and</span> <span m=''2240630''>cons</span>
  <span m=''2241020''>was</span> <span m=''2241190''>just</span> <span m=''2241440''>a</span>
  <span m=''2241900''>delayed</span> <span m=''2242250''>procedure,</span> <span m=''2242670''>that</span>
  <span m=''2242830''>would</span> <span m=''2242930''>make</span> <span m=''2243100''>cons</span>
  <span m=''2243430''>the</span> <span m=''2243510''>same</span> <span m=''2243740''>as</span>
  <span m=''2243840''>cons-stream.</span> <span m=''2244710''>We</span> <span m=''2244820''>wouldn''t</span>
  <span m=''2244950''>need</span> <span m=''2245090''>streams</span> <span m=''2245390''>of</span>
  <span m=''2245470''>all</span> <span m=''2246460''>because</span> <span m=''2246780''>lists</span>
  <span m=''2247110''>would</span> <span m=''2247240''>automatically</span> <span
  m=''2247930''>be</span> <span m=''2248070''>streams.</span> <span m=''2249610''>That''s</span>
  <span m=''2249810''>how</span> <span m=''2249950''>lists</span> <span m=''2250170''>would</span>
  <span m=''2250310''>behave,</span> <span m=''2250675''>and</span> <span m=''2251040''>data</span>
  <span m=''2251250''>structures</span> <span m=''2251620''>would</span> <span m=''2251730''>behave</span>
  <span m=''2252010''>that</span> <span m=''2252200''>way.</span> <span m=''2252350''>Everything</span>
  <span m=''2252710''>would</span> <span m=''2252830''>behave</span> <span m=''2253130''>that</span>
  <span m=''2253340''>way,</span> <span m=''2255090''>right?</span> <span m=''2255270''>You''d</span>
  <span m=''2255360''>never</span> <span m=''2256350''>really</span> <span m=''2256740''>do</span>
  <span m=''2256880''>any</span> <span m=''2257030''>computation</span> <span m=''2257720''>until</span>
  <span m=''2257850''>you</span> <span m=''2257990''>actually</span> <span m=''2258510''>needed</span>
  <span m=''2258820''>the</span> <span m=''2258900''>answer.</span> <span m=''2261020''>You</span>
  <span m=''2261130''>wouldn''t</span> <span m=''2261330''>have</span> <span m=''2261450''>to</span>
  <span m=''2261570''>worry</span> <span m=''2261810''>about</span> <span m=''2261990''>all</span>
  <span m=''2262140''>these</span> <span m=''2262330''>explicit</span> <span m=''2262780''>annoying</span>
  <span m=''2263130''>delays.</span> <span m=''2264790''>Well,</span> <span m=''2265300''>why</span>
  <span m=''2265440''>don''t</span> <span m=''2265560''>we</span> <span m=''2265670''>do</span>
  <span m=''2265850''>that?</span> </p><p><span m=''2267160''>First</span> <span m=''2267460''>of
  all,</span> <span m=''2267630''>I should</span> <span m=''2267710''>say</span> <span
  m=''2267850''>people</span> <span m=''2268120''>do</span> <span m=''2268340''>do</span>
  <span m=''2268440''>that.</span> <span m=''2269230''>There''s</span> <span m=''2269410''>some</span>
  <span m=''2269520''>very</span> <span m=''2270970''>beautiful</span> <span m=''2271380''>languages.</span>
  <span m=''2271850''>One</span> <span m=''2272000''>of</span> <span m=''2272050''>the</span>
  <span m=''2272860''>very</span> <span m=''2273080''>nicest</span> <span m=''2273660''>is</span>
  <span m=''2273750''>a</span> <span m=''2273810''>language</span> <span m=''2274430''>called</span>
  <span m=''2274690''>Miranda,</span> <span m=''2275920''>which</span> <span m=''2276170''>is</span>
  <span m=''2277490''>developed</span> <span m=''2277870''>by</span> <span m=''2278010''>David</span>
  <span m=''2278330''>Turner</span> <span m=''2278680''>at</span> <span m=''2278750''>the</span>
  <span m=''2278810''>University</span> <span m=''2279270''>of</span> <span m=''2279360''>Kent.</span>
  <span m=''2280710''>And</span> <span m=''2280880''>that''s</span> <span m=''2281060''>how</span>
  <span m=''2281170''>this</span> <span m=''2281330''>language</span> <span m=''2281650''>works.</span>
  <span m=''2281930''>It''s</span> <span m=''2282020''>a</span> <span m=''2282110''>normal-order</span>
  <span m=''2282670''>language</span> <span m=''2283100''>and</span> <span m=''2284510''>its</span>
  <span m=''2284710''>data</span> <span m=''2284940''>structures,</span> <span m=''2286240''>which</span>
  <span m=''2286430''>look</span> <span m=''2286650''>like</span> <span m=''2286900''>lists,</span>
  <span m=''2287210''>are</span> <span m=''2287330''>actually</span> <span m=''2287680''>streams.</span>
  <span m=''2288160''>And</span> <span m=''2289000''>you</span> <span m=''2289100''>write</span>
  <span m=''2289250''>ordinary</span> <span m=''2289630''>procedures</span> <span
  m=''2290130''>in</span> <span m=''2290230''>Miranda,</span> <span m=''2290700''>and</span>
  <span m=''2290790''>they</span> <span m=''2291390''>do</span> <span m=''2291530''>these</span>
  <span m=''2291710''>prime</span> <span m=''2292000''>things</span> <span m=''2292310''>and</span>
  <span m=''2292540''>eight</span> <span m=''2292680''>queens</span> <span m=''2293080''>things,</span>
  <span m=''2293350''>just</span> <span m=''2293950''>without</span> <span m=''2294240''>anything</span>
  <span m=''2294560''>special.</span> <span m=''2294970''>It''s</span> <span m=''2295090''>all</span>
  <span m=''2295700''>built</span> <span m=''2295950''>in</span> <span m=''2296060''>there.</span>
  <span m=''2297790''>But</span> <span m=''2298160''>there''s</span> <span m=''2298330''>a</span>
  <span m=''2298380''>price.</span> </p><p><span m=''2301190''>Remember</span> <span
  m=''2301370''>how</span> <span m=''2301460''>we</span> <span m=''2301570''>got</span>
  <span m=''2301820''>here.</span> <span m=''2303170''>We''re</span> <span m=''2303340''>decoupling</span>
  <span m=''2304940''>time</span> <span m=''2305380''>in</span> <span m=''2305500''>the</span>
  <span m=''2305870''>programs</span> <span m=''2306380''>from</span> <span m=''2306520''>time</span>
  <span m=''2306800''>in</span> <span m=''2306870''>the</span> <span m=''2306940''>machines.</span>
  <span m=''2307480''>And</span> <span m=''2308040''>if</span> <span m=''2308160''>we</span>
  <span m=''2308240''>put</span> <span m=''2308420''>delay,</span> <span m=''2308970''>that</span>
  <span m=''2309260''>sort of</span> <span m=''2309380''>decouples</span> <span m=''2309510''>it</span>
  <span m=''2309850''>everywhere,</span> <span m=''2310400''>not</span> <span m=''2310570''>just</span>
  <span m=''2310780''>in</span> <span m=''2310870''>streams.</span> <span m=''2311835''>Remember
  what</span> <span m=''2312230''>we''re</span> <span m=''2312560''>trying</span>
  <span m=''2312740''>to</span> <span m=''2312930''>do.</span> <span m=''2313140''>We''re</span>
  <span m=''2313250''>trying</span> <span m=''2313590''>to</span> <span m=''2314100''>think</span>
  <span m=''2314440''>about</span> <span m=''2315990''>programming</span> <span m=''2316590''>as
  a</span> <span m=''2316690''>way</span> <span m=''2316800''>to</span> <span m=''2316900''>specify</span>
  <span m=''2317470''>processes.</span> <span m=''2319300''>And</span> <span m=''2319400''>if</span>
  <span m=''2319480''>we</span> <span m=''2319550''>give</span> <span m=''2319690''>up</span>
  <span m=''2319820''>too</span> <span m=''2320100''>much</span> <span m=''2320330''>time,</span>
  <span m=''2320660''>our</span> <span m=''2320750''>language</span> <span m=''2321120''>becomes</span>
  <span m=''2321690''>more</span> <span m=''2321890''>elegant,</span> <span m=''2323770''>but</span>
  <span m=''2324470''>it</span> <span m=''2324540''>becomes</span> <span m=''2324760''>a
  little</span> <span m=''2324900''>bit</span> <span m=''2325020''>less</span> <span
  m=''2325260''>expressive.</span> <span m=''2327030''>There are</span> <span m=''2327210''>certain</span>
  <span m=''2327710''>distinctions</span> <span m=''2328510''>that</span> <span m=''2328640''>we</span>
  <span m=''2328760''>can''t</span> <span m=''2329320''>draw.</span> </p><p><span
  m=''2331480''>One</span> <span m=''2331640''>of</span> <span m=''2331700''>them,</span>
  <span m=''2331960''>for</span> <span m=''2332270''>instance,</span> <span m=''2332560''>is</span>
  <span m=''2332680''>iteration.</span> <span m=''2333980''>Remember</span> <span
  m=''2335430''>this</span> <span m=''2335580''>old</span> <span m=''2335780''>procedure,</span>
  <span m=''2336820''>iterative</span> <span m=''2337460''>factorial,</span> <span
  m=''2338280''>that</span> <span m=''2338450''>we</span> <span m=''2338630''>looked</span>
  <span m=''2338860''>at</span> <span m=''2339620''>quite a</span> <span m=''2339750''>long</span>
  <span m=''2339990''>time</span> <span m=''2340250''>ago.</span> <span m=''2341230''>Iterative</span>
  <span m=''2341740''>factorial</span> <span m=''2342330''>had</span> <span m=''2342490''>a</span>
  <span m=''2342540''>thing,</span> <span m=''2342820''>and</span> <span m=''2342900''>it</span>
  <span m=''2343020''>said</span> <span m=''2343160''>there</span> <span m=''2343280''>was</span>
  <span m=''2343410''>an</span> <span m=''2343820''>internal</span> <span m=''2344290''>procedure,</span>
  <span m=''2345220''>and</span> <span m=''2345380''>there</span> <span m=''2345460''>was</span>
  <span m=''2345580''>a</span> <span m=''2345620''>state</span> <span m=''2345990''>which</span>
  <span m=''2346130''>was</span> <span m=''2346240''>a</span> <span m=''2346290''>product</span>
  <span m=''2346790''>and</span> <span m=''2346880''>a</span> <span m=''2346960''>counter,</span>
  <span m=''2348770''>and</span> <span m=''2348940''>we</span> <span m=''2349340''>iterate</span>
  <span m=''2349750''>that</span> <span m=''2349970''>going</span> <span m=''2350250''>around
  the</span> <span m=''2350550''>loop.</span> <span m=''2352120''>And</span> <span
  m=''2352300''>we</span> <span m=''2352370''>said</span> <span m=''2352500''>that</span>
  <span m=''2352600''>was</span> <span m=''2352720''>an</span> <span m=''2352800''>iterative</span>
  <span m=''2353210''>procedure</span> <span m=''2353650''>because it</span> <span
  m=''2353880''>didn''t</span> <span m=''2354140''>build</span> <span m=''2354360''>up</span>
  <span m=''2354460''>state.</span> <span m=''2355730''>And</span> <span m=''2356110''>the</span>
  <span m=''2356200''>reason</span> <span m=''2356430''>it</span> <span m=''2356510''>didn''t</span>
  <span m=''2356700''>build</span> <span m=''2356880''>up</span> <span m=''2356970''>state
  is</span> <span m=''2357450''>because</span> <span m=''2358630''>this</span> <span
  m=''2359370''>iter</span> <span m=''2359630''>that''s</span> <span m=''2359830''>called</span>
  <span m=''2360300''>is</span> <span m=''2360470''>just</span> <span m=''2360660''>passing</span>
  <span m=''2361590''>these</span> <span m=''2361840''>things</span> <span m=''2362050''>around</span>
  <span m=''2362310''>to</span> <span m=''2362430''>itself.</span> <span m=''2363900''>Or</span>
  <span m=''2364060''>in</span> <span m=''2364120''>the</span> <span m=''2364180''>substitution</span>
  <span m=''2364850''>model,</span> <span m=''2365520''>you</span> <span m=''2365700''>could</span>
  <span m=''2365810''>see</span> <span m=''2365980''>in</span> <span m=''2366070''>the</span>
  <span m=''2366130''>substitution</span> <span m=''2366790''>model</span> <span m=''2367060''>that</span>
  <span m=''2367180''>Jerry</span> <span m=''2367500''>did,</span> <span m=''2368780''>that</span>
  <span m=''2368940''>in an</span> <span m=''2369100''>iterative</span> <span m=''2369480''>procedure,</span>
  <span m=''2369980''>that</span> <span m=''2370170''>state</span> <span m=''2370420''>doesn''t</span>
  <span m=''2370680''>have</span> <span m=''2370920''>to</span> <span m=''2371030''>grow.</span>
  <span m=''2371660''>And</span> <span m=''2371970''>in</span> <span m=''2372140''>fact,</span>
  <span m=''2372380''>we</span> <span m=''2372450''>said</span> <span m=''2372600''>it</span>
  <span m=''2372680''>doesn''t,</span> <span m=''2373030''>so</span> <span m=''2373120''>this</span>
  <span m=''2373300''>is</span> <span m=''2373410''>an</span> <span m=''2373500''>iteration.</span>
  </p><p><span m=''2374840''>But</span> <span m=''2375160''>now</span> <span m=''2375290''>think</span>
  <span m=''2375590''>about</span> <span m=''2375870''>this</span> <span m=''2376050''>exact</span>
  <span m=''2376620''>same</span> <span m=''2377060''>text</span> <span m=''2377540''>if</span>
  <span m=''2377650''>we</span> <span m=''2377730''>had</span> <span m=''2377850''>a</span>
  <span m=''2377890''>normal-order</span> <span m=''2378620''>language.</span> <span
  m=''2381150''>What</span> <span m=''2381280''>would</span> <span m=''2381380''>happen</span>
  <span m=''2381810''>is</span> <span m=''2382680''>this</span> <span m=''2383070''>would</span>
  <span m=''2383210''>no</span> <span m=''2383370''>longer</span> <span m=''2383690''>be</span>
  <span m=''2383850''>an</span> <span m=''2384230''>iterative</span> <span m=''2384310''>procedure?</span>
  <span m=''2385650''>And</span> <span m=''2385870''>if</span> <span m=''2385960''>you</span>
  <span m=''2386070''>really</span> <span m=''2386460''>think</span> <span m=''2386800''>about</span>
  <span m=''2387020''>the</span> <span m=''2387100''>details</span> <span m=''2387630''>of</span>
  <span m=''2387710''>the</span> <span m=''2387790''>substitution</span> <span m=''2388430''>model,</span>
  <span m=''2388670''>which</span> <span m=''2388850''>I''m</span> <span m=''2389020''>not</span>
  <span m=''2389240''>going</span> <span m=''2389320''>to</span> <span m=''2389390''>do</span>
  <span m=''2389580''>here,</span> <span m=''2391210''>this</span> <span m=''2391460''>expression</span>
  <span m=''2391970''>would</span> <span m=''2392130''>grow.</span> <span m=''2392330''>Why</span>
  <span m=''2392530''>would</span> <span m=''2392680''>it</span> <span m=''2392760''>grow?</span>
  <span m=''2393280''>It''s</span> <span m=''2393450''>because</span> <span m=''2393720''>when</span>
  <span m=''2393840''>iter</span> <span m=''2394440''>calls</span> <span m=''2394730''>itself,</span>
  <span m=''2395950''>it</span> <span m=''2396080''>calls</span> <span m=''2396330''>itself</span>
  <span m=''2396640''>with</span> <span m=''2396740''>this</span> <span m=''2396910''>product.</span>
  <span m=''2398080''>If</span> <span m=''2398220''>it''s</span> <span m=''2398360''>a</span>
  <span m=''2398410''>normal-order</span> <span m=''2399000''>language,</span> <span
  m=''2399390''>that</span> <span m=''2399560''>multiplication</span> <span m=''2400210''>is</span>
  <span m=''2400300''>not</span> <span m=''2400490''>going</span> <span m=''2400550''>to</span>
  <span m=''2400620''>get</span> <span m=''2400830''>done.</span> <span m=''2402510''>That''s</span>
  <span m=''2402670''>going to</span> <span m=''2402870''>say I''m</span> <span m=''2403080''>to</span>
  <span m=''2403170''>call</span> <span m=''2403420''>myself</span> <span m=''2403940''>with</span>
  <span m=''2404050''>a</span> <span m=''2404170''>promise</span> <span m=''2404680''>to</span>
  <span m=''2404790''>compute</span> <span m=''2405120''>this</span> <span m=''2405290''>product.</span>
  <span m=''2406670''>And</span> <span m=''2406840''>now iter</span> <span m=''2407250''>goes
  around</span> <span m=''2407620''>again.</span> <span m=''2409760''>And</span> <span
  m=''2410580''>I''m going to</span> <span m=''2410730''>call</span> <span m=''2411110''>myself</span>
  <span m=''2411780''>with</span> <span m=''2411970''>a</span> <span m=''2412010''>promise</span>
  <span m=''2412550''>to</span> <span m=''2412770''>compute</span> <span m=''2413330''>this</span>
  <span m=''2413680''>product</span> <span m=''2414090''>where</span> <span m=''2414200''>now</span>
  <span m=''2414360''>one</span> <span m=''2414570''>of</span> <span m=''2414620''>the</span>
  <span m=''2415390''>one</span> <span m=''2416820''>factors</span> <span m=''2417150''>is</span>
  <span m=''2417260''>a</span> <span m=''2417310''>promise.</span> <span m=''2418400''>And</span>
  <span m=''2418530''>I</span> <span m=''2418570''>call</span> <span m=''2418880''>myself</span>
  <span m=''2419210''>again.</span> <span m=''2419430''>And if</span> <span m=''2419520''>you</span>
  <span m=''2419660''>write</span> <span m=''2419900''>out</span> <span m=''2420050''>the</span>
  <span m=''2420110''>substitution</span> <span m=''2420750''>model</span> <span m=''2421970''>for</span>
  <span m=''2422120''>that</span> <span m=''2422580''>iterative</span> <span m=''2422950''>process,</span>
  <span m=''2423800''>you''ll</span> <span m=''2423920''>see</span> <span m=''2424100''>exactly</span>
  <span m=''2424740''>the</span> <span m=''2424830''>same</span> <span m=''2425770''>growth</span>
  <span m=''2426220''>in</span> <span m=''2426430''>state,</span> <span m=''2427150''>all</span>
  <span m=''2427340''>those</span> <span m=''2427570''>promises</span> <span m=''2428130''>that</span>
  <span m=''2428210''>are</span> <span m=''2428290''>getting</span> <span m=''2428540''>remembered</span>
  <span m=''2428920''>that</span> <span m=''2429080''>have</span> <span m=''2429200''>to</span>
  <span m=''2429330''>get</span> <span m=''2429480''>called</span> <span m=''2429790''>in</span>
  <span m=''2429880''>at</span> <span m=''2429970''>the</span> <span m=''2430050''>very</span>
  <span m=''2430480''>end.</span> </p><p><span m=''2431790''>So</span> <span m=''2432320''>one</span>
  <span m=''2432610''>of</span> <span m=''2432680''>the</span> <span m=''2434160''>disadvantages</span>
  <span m=''2435100''>is</span> <span m=''2435210''>that</span> <span m=''2435340''>you</span>
  <span m=''2435420''>can''t</span> <span m=''2435690''>really</span> <span m=''2435970''>express</span>
  <span m=''2436330''>iteration.</span> <span m=''2436980''>Maybe</span> <span m=''2437170''>that''s</span>
  <span m=''2437340''>a</span> <span m=''2437400''>little</span> <span m=''2438330''>theoretical</span>
  <span m=''2438900''>reason</span> <span m=''2439210''>why</span> <span m=''2439380''>not,</span>
  <span m=''2439610''>but</span> <span m=''2439730''>in</span> <span m=''2439820''>fact,</span>
  <span m=''2440710''>people</span> <span m=''2440980''>who</span> <span m=''2441080''>are</span>
  <span m=''2442310''>trying</span> <span m=''2442490''>to</span> <span m=''2442660''>write</span>
  <span m=''2442850''>real</span> <span m=''2443010''>operating</span> <span m=''2443510''>systems</span>
  <span m=''2444320''>in</span> <span m=''2444430''>these</span> <span m=''2444610''>languages</span>
  <span m=''2445070''>are</span> <span m=''2445170''>running</span> <span m=''2445430''>into</span>
  <span m=''2445640''>exactly</span> <span m=''2446460''>these</span> <span m=''2446750''>types</span>
  <span m=''2447030''>of</span> <span m=''2447090''>problems.</span> <span m=''2448240''>Like</span>
  <span m=''2448510''>it''s</span> <span m=''2448670''>perfectly</span> <span m=''2449140''>possible</span>
  <span m=''2450010''>to</span> <span m=''2451650''>implement</span> <span m=''2452110''>a</span>
  <span m=''2452170''>text</span> <span m=''2452540''>editor</span> <span m=''2453550''>in</span>
  <span m=''2453690''>languages</span> <span m=''2454150''>like</span> <span m=''2454380''>these.</span>
  <span m=''2454610''>But</span> <span m=''2455120''>after</span> <span m=''2455330''>you</span>
  <span m=''2455470''>work</span> <span m=''2455700''>a</span> <span m=''2455740''>while,</span>
  <span m=''2456970''>you</span> <span m=''2457100''>suddenly</span> <span m=''2457390''>have</span>
  <span m=''2457560''>3</span> <span m=''2457780''>megabytes</span> <span m=''2458830''>of</span>
  <span m=''2459010''>stuff,</span> <span m=''2459460''>which</span> <span m=''2459630''>is--</span>
  <span m=''2461240''>I</span> <span m=''2461370''>guess</span> <span m=''2461500''>they</span>
  <span m=''2461600''>call</span> <span m=''2461760''>them</span> <span m=''2462100''>the</span>
  <span m=''2462250''>dragging</span> <span m=''2462800''>tail</span> <span m=''2463100''>problem</span>
  <span m=''2463990''>of</span> <span m=''2464470''>people</span> <span m=''2464740''>who</span>
  <span m=''2464830''>are</span> <span m=''2464910''>looking</span> <span m=''2465230''>at</span>
  <span m=''2465310''>these,</span> <span m=''2466310''>of</span> <span m=''2466450''>promises</span>
  <span m=''2467020''>that</span> <span m=''2467150''>sort</span> <span m=''2467320''>of</span>
  <span m=''2467390''>haven''t</span> <span m=''2467660''>been</span> <span m=''2467790''>called</span>
  <span m=''2468070''>in</span> <span m=''2468170''>because</span> <span m=''2468290''>you</span>
  <span m=''2468390''>couldn''t</span> <span m=''2468610''>quite</span> <span m=''2469260''>express</span>
  <span m=''2469650''>an</span> <span m=''2469730''>iteration.</span> <span m=''2470230''>And</span>
  <span m=''2470690''>one</span> <span m=''2470950''>of</span> <span m=''2471030''>the</span>
  <span m=''2472140''>research</span> <span m=''2473280''>questions</span> <span m=''2473800''>in</span>
  <span m=''2473860''>these</span> <span m=''2474010''>kinds</span> <span m=''2474250''>of</span>
  <span m=''2474330''>languages</span> <span m=''2474850''>are</span> <span m=''2474930''>figuring</span>
  <span m=''2475480''>out</span> <span m=''2475830''>the</span> <span m=''2476040''>right</span>
  <span m=''2476240''>compiler</span> <span m=''2476760''>technology</span> <span
  m=''2477540''>to</span> <span m=''2477930''>get</span> <span m=''2478110''>rid</span>
  <span m=''2478250''>of</span> <span m=''2478320''>the</span> <span m=''2478390''>so-called</span>
  <span m=''2478880''>dragging</span> <span m=''2479340''>tails.</span> <span m=''2480110''>It''s</span>
  <span m=''2480260''>not</span> <span m=''2481170''>simple.</span> </p><p><span m=''2483940''>But</span>
  <span m=''2484280''>there''s</span> <span m=''2484510''>another</span> <span m=''2486130''>kind</span>
  <span m=''2486220''>of</span> <span m=''2486320''>more</span> <span m=''2486450''>striking</span>
  <span m=''2486910''>issue</span> <span m=''2487990''>about</span> <span m=''2488310''>why</span>
  <span m=''2488520''>you</span> <span m=''2488670''>just</span> <span m=''2488900''>don''t</span>
  <span m=''2489190''>go</span> <span m=''2489380''>ahead</span> <span m=''2489680''>and</span>
  <span m=''2489780''>make</span> <span m=''2489980''>your</span> <span m=''2490100''>language</span>
  <span m=''2490480''>normal</span> <span m=''2490640''>order.</span> <span m=''2492056''>And</span>
  <span m=''2492550''>the</span> <span m=''2492710''>reason</span> <span m=''2493020''>is</span>
  <span m=''2494670''>that</span> <span m=''2495190''>normal-order</span> <span m=''2495890''>evaluation</span>
  <span m=''2497250''>and</span> <span m=''2497440''>side</span> <span m=''2497760''>effects</span>
  <span m=''2498890''>just</span> <span m=''2499490''>don''t</span> <span m=''2499940''>mix.</span>
  <span m=''2502000''>They</span> <span m=''2502150''>just</span> <span m=''2502400''>don''t</span>
  <span m=''2502770''>go</span> <span m=''2502920''>together</span> <span m=''2503350''>very</span>
  <span m=''2503600''>well.</span> <span m=''2505350''>Somehow,</span> <span m=''2505930''>you</span>
  <span m=''2506260''>can''t--</span> <span m=''2508360''>it''s</span> <span m=''2508840''>sort</span>
  <span m=''2508950''>of</span> <span m=''2509070''>you</span> <span m=''2509190''>can''t</span>
  <span m=''2509540''>simultaneously</span> <span m=''2510980''>go</span> <span m=''2511150''>around</span>
  <span m=''2511500''>trying</span> <span m=''2511720''>to</span> <span m=''2511930''>model</span>
  <span m=''2512340''>objects</span> <span m=''2512800''>with</span> <span m=''2512940''>local</span>
  <span m=''2513260''>state</span> <span m=''2513610''>and</span> <span m=''2513770''>change</span>
  <span m=''2515730''>and</span> <span m=''2515900''>at</span> <span m=''2515990''>the</span>
  <span m=''2516060''>same</span> <span m=''2516450''>time</span> <span m=''2517210''>do</span>
  <span m=''2517350''>these</span> <span m=''2517570''>normal-order</span> <span m=''2518130''>tricks</span>
  <span m=''2518430''>of</span> <span m=''2518520''>de-coupling</span> <span m=''2519130''>time.</span>
  <span m=''2520400''>Let</span> <span m=''2520530''>me</span> <span m=''2520960''>just</span>
  <span m=''2521080''>show</span> <span m=''2521220''>you a</span> <span m=''2521370''>really</span>
  <span m=''2521610''>simple</span> <span m=''2522010''>example,</span> <span m=''2522580''>very,</span>
  <span m=''2523010''>very</span> <span m=''2523180''>simple.</span> </p><p><span
  m=''2523790''>Suppose</span> <span m=''2524070''>we</span> <span m=''2524160''>had</span>
  <span m=''2524290''>a</span> <span m=''2524330''>normal-order</span> <span m=''2524950''>language.</span>
  <span m=''2527520''>And</span> <span m=''2527820''>I''m</span> <span m=''2527900''>going</span>
  <span m=''2527990''>to</span> <span m=''2528220''>start</span> <span m=''2528570''>out</span>
  <span m=''2528750''>in</span> <span m=''2528940''>this</span> <span m=''2529130''>language.</span>
  <span m=''2529550''>This</span> <span m=''2529680''>is</span> <span m=''2529800''>now</span>
  <span m=''2529930''>normal</span> <span m=''2530310''>order.</span> <span m=''2530520''>I''m
  going</span> <span m=''2530660''>to</span> <span m=''2530980''>define</span> <span
  m=''2531440''>x</span> <span m=''2531630''>to</span> <span m=''2531720''>be</span>
  <span m=''2531810''>0.</span> <span m=''2533570''>It''s just</span> <span m=''2533770''>some</span>
  <span m=''2533990''>variable</span> <span m=''2534740''>I''ll</span> <span m=''2534900''>initialize.</span>
  <span m=''2535750''>And now I''m going</span> <span m=''2536050''>to</span> <span
  m=''2536120''>define</span> <span m=''2536340''>this</span> <span m=''2536470''>little</span>
  <span m=''2536680''>funny</span> <span m=''2537140''>function,</span> <span m=''2538610''>which</span>
  <span m=''2539090''>is</span> <span m=''2539280''>an</span> <span m=''2539370''>identity</span>
  <span m=''2539850''>function.</span> <span m=''2542640''>And</span> <span m=''2543190''>what</span>
  <span m=''2543390''>it</span> <span m=''2543500''>does,</span> <span m=''2543760''>it</span>
  <span m=''2544060''>keeps</span> <span m=''2544360''>track</span> <span m=''2544740''>of</span>
  <span m=''2544850''>the</span> <span m=''2544920''>last</span> <span m=''2545240''>time</span>
  <span m=''2545430''>you</span> <span m=''2545520''>called</span> <span m=''2545860''>it</span>
  <span m=''2545940''>using</span> <span m=''2546290''>x.</span> <span m=''2551620''>So</span>
  <span m=''2551670''>the</span> <span m=''2551750''>identity</span> <span m=''2552220''>of</span>
  <span m=''2552360''>n</span> <span m=''2552860''>just</span> <span m=''2553520''>returns</span>
  <span m=''2553930''>n,</span> <span m=''2554120''>but</span> <span m=''2554250''>it</span>
  <span m=''2554390''>sets</span> <span m=''2554570''>x</span> <span m=''2554820''>to</span>
  <span m=''2554900''>be n.</span> <span m=''2556760''>And</span> <span m=''2556900''>now</span>
  <span m=''2557240''>I''ll define a</span> <span m=''2557700''>little increment</span>
  <span m=''2558000''>function,</span> <span m=''2559640''>which</span> <span m=''2559820''>is</span>
  <span m=''2559990''>a</span> <span m=''2560050''>very</span> <span m=''2560870''>little,</span>
  <span m=''2561220''>simple</span> <span m=''2561610''>scenario.</span> </p><p><span
  m=''2562580''>Now,</span> <span m=''2562890''>imagine</span> <span m=''2563060''>I''m</span>
  <span m=''2563180''>interacting</span> <span m=''2563770''>with</span> <span m=''2563900''>this</span>
  <span m=''2564060''>in</span> <span m=''2564130''>the</span> <span m=''2564200''>normal-order</span>
  <span m=''2564780''>language,</span> <span m=''2565810''>and</span> <span m=''2566310''>I</span>
  <span m=''2566430''>type</span> <span m=''2566690''>the</span> <span m=''2566770''>following.</span>
  <span m=''2567230''>I say</span> <span m=''2567940''>define</span> <span m=''2568360''>y</span>
  <span m=''2569740''>to</span> <span m=''2570200''>be</span> <span m=''2570660''>increment</span>
  <span m=''2571410''>the</span> <span m=''2571540''>identity</span> <span m=''2572000''>function</span>
  <span m=''2572390''>of</span> <span m=''2572470''>3,</span> <span m=''2572770''>so</span>
  <span m=''2572940''>y is</span> <span m=''2573200''>going</span> <span m=''2573290''>to</span>
  <span m=''2573390''>be</span> <span m=''2573480''>4.</span> <span m=''2577410''>Now,</span>
  <span m=''2577530''>I</span> <span m=''2577590''>say</span> <span m=''2577730''>what''s</span>
  <span m=''2577990''>x?</span> <span m=''2579520''>Well,</span> <span m=''2579680''>x
  should</span> <span m=''2580090''>have</span> <span m=''2580180''>been</span> <span
  m=''2580460''>the</span> <span m=''2580670''>value</span> <span m=''2581040''>that</span>
  <span m=''2581180''>was</span> <span m=''2581330''>remembered</span> <span m=''2581800''>last</span>
  <span m=''2582720''>when</span> <span m=''2582850''>I</span> <span m=''2582900''>called</span>
  <span m=''2583130''>the</span> <span m=''2583230''>identity</span> <span m=''2583630''>function.</span>
  <span m=''2584710''>So you''d</span> <span m=''2584970''>expect</span> <span m=''2585440''>to</span>
  <span m=''2585480''>say, well, x is</span> <span m=''2585960''>3</span> <span m=''2586220''>at</span>
  <span m=''2586360''>this</span> <span m=''2586500''>point,</span> <span m=''2586880''>but</span>
  <span m=''2587050''>it''s</span> <span m=''2587210''>not.</span> <span m=''2588530''>Because</span>
  <span m=''2589190''>when</span> <span m=''2589350''>I</span> <span m=''2589420''>defined</span>
  <span m=''2590360''>y</span> <span m=''2590620''>here,</span> <span m=''2591840''>what</span>
  <span m=''2591950''>I</span> <span m=''2592070''>really</span> <span m=''2592410''>defined</span>
  <span m=''2592810''>y</span> <span m=''2593060''>to</span> <span m=''2593100''>be</span>
  <span m=''2593460''>increment</span> <span m=''2594010''>of</span> <span m=''2594390''>a</span>
  <span m=''2594530''>promise</span> <span m=''2594960''>to</span> <span m=''2595070''>do</span>
  <span m=''2595230''>this</span> <span m=''2595490''>thing.</span> <span m=''2597000''>So</span>
  <span m=''2597160''>I</span> <span m=''2597230''>didn''t</span> <span m=''2597490''>look</span>
  <span m=''2597670''>at</span> <span m=''2597800''>y,</span> <span m=''2598320''>so</span>
  <span m=''2598490''>that</span> <span m=''2598650''>identity</span> <span m=''2599050''>function</span>
  <span m=''2599390''>didn''t</span> <span m=''2599600''>get</span> <span m=''2599800''>run.</span>
  <span m=''2601560''>So</span> <span m=''2601800''>if</span> <span m=''2601990''>I</span>
  <span m=''2602080''>type in</span> <span m=''2602430''>this</span> <span m=''2602560''>definition</span>
  <span m=''2603330''>and</span> <span m=''2603520''>look</span> <span m=''2603670''>at</span>
  <span m=''2603750''>x,</span> <span m=''2603990''>I''m</span> <span m=''2604070''>going</span>
  <span m=''2604130''>to</span> <span m=''2604190''>get</span> <span m=''2604340''>0.</span>
  </p><p><span m=''2608360''>Now,</span> <span m=''2608500''>if</span> <span m=''2608600''>I</span>
  <span m=''2608660''>go</span> <span m=''2608810''>look</span> <span m=''2609020''>at</span>
  <span m=''2609120''>y</span> <span m=''2610180''>and</span> <span m=''2610320''>say</span>
  <span m=''2610500''>what''s</span> <span m=''2610790''>y,</span> <span m=''2611530''>say</span>
  <span m=''2611700''>y is</span> <span m=''2612080''>4,</span> <span m=''2612660''>looking</span>
  <span m=''2613120''>at</span> <span m=''2613290''>y,</span> <span m=''2613620''>that</span>
  <span m=''2613820''>very</span> <span m=''2614080''>active</span> <span m=''2614400''>looking</span>
  <span m=''2614690''>at</span> <span m=''2614800''>y</span> <span m=''2615310''>caused</span>
  <span m=''2615630''>the</span> <span m=''2615760''>identity</span> <span m=''2616180''>function</span>
  <span m=''2616650''>to</span> <span m=''2616930''>be</span> <span m=''2617090''>run.</span>
  <span m=''2618342''>And</span> <span m=''2618840''>now</span> <span m=''2619070''>x
  will</span> <span m=''2619370''>get</span> <span m=''2619520''>remembered</span>
  <span m=''2619930''>as 3.</span> <span m=''2620740''>So</span> <span m=''2620910''>here</span>
  <span m=''2621160''>x</span> <span m=''2621400''>will be</span> <span m=''2621510''>0.</span>
  <span m=''2622020''>Here,</span> <span m=''2622130''>x</span> <span m=''2622350''>will</span>
  <span m=''2622420''>be</span> <span m=''2622550''>3.</span> <span m=''2623280''>That''s</span>
  <span m=''2623500''>a</span> <span m=''2624240''>tiny,</span> <span m=''2624800''>little,</span>
  <span m=''2625230''>simple</span> <span m=''2625610''>scenario,</span> <span m=''2626290''>but</span>
  <span m=''2626470''>you</span> <span m=''2626560''>can</span> <span m=''2626710''>see</span>
  <span m=''2627710''>what</span> <span m=''2627890''>kind</span> <span m=''2628080''>of</span>
  <span m=''2628170''>a</span> <span m=''2628220''>mess</span> <span m=''2628560''>that''s</span>
  <span m=''2628770''>going</span> <span m=''2628850''>to</span> <span m=''2628930''>make</span>
  <span m=''2630370''>for</span> <span m=''2630560''>debugging</span> <span m=''2632050''>interactive</span>
  <span m=''2632640''>programs</span> <span m=''2634200''>when you</span> <span m=''2634390''>have</span>
  <span m=''2634570''>normal-order</span> <span m=''2635220''>evaluation.</span> </p><p><span
  m=''2637100''>It''s</span> <span m=''2637200''>very</span> <span m=''2637510''>confusing.</span>
  <span m=''2639690''>But</span> <span m=''2639810''>it''s</span> <span m=''2639940''>very</span>
  <span m=''2640160''>confusing</span> <span m=''2640600''>for</span> <span m=''2640760''>a</span>
  <span m=''2640790''>very</span> <span m=''2641220''>deep</span> <span m=''2641560''>reason,</span>
  <span m=''2642850''>which</span> <span m=''2643040''>is</span> <span m=''2643200''>that</span>
  <span m=''2643370''>the</span> <span m=''2643450''>whole</span> <span m=''2644110''>idea</span>
  <span m=''2645290''>of</span> <span m=''2645470''>putting</span> <span m=''2645770''>in</span>
  <span m=''2645890''>delays</span> <span m=''2646980''>is</span> <span m=''2647120''>that</span>
  <span m=''2647250''>you</span> <span m=''2647350''>throw</span> <span m=''2647670''>away</span>
  <span m=''2647970''>time.</span> <span m=''2649780''>That''s</span> <span m=''2650050''>why</span>
  <span m=''2650280''>we</span> <span m=''2650420''>can</span> <span m=''2650550''>have</span>
  <span m=''2650740''>these</span> <span m=''2650900''>infinite</span> <span m=''2651240''>processes.</span>
  <span m=''2651750''>Since</span> <span m=''2651960''>we''ve</span> <span m=''2652100''>thrown</span>
  <span m=''2652400''>away</span> <span m=''2652620''>time,</span> <span m=''2652910''>we</span>
  <span m=''2652990''>don''t</span> <span m=''2653150''>have</span> <span m=''2653310''>to</span>
  <span m=''2653400''>wait</span> <span m=''2653620''>for</span> <span m=''2653710''>them</span>
  <span m=''2653870''>to</span> <span m=''2654010''>run,</span> <span m=''2657690''>right?</span>
  <span m=''2657790''>We</span> <span m=''2658410''>decouple</span> <span m=''2658930''>the</span>
  <span m=''2659040''>order</span> <span m=''2659310''>of</span> <span m=''2659410''>events</span>
  <span m=''2659710''>in</span> <span m=''2659850''>the</span> <span m=''2659930''>computer</span>
  <span m=''2660650''>from</span> <span m=''2661000''>what</span> <span m=''2661120''>we</span>
  <span m=''2661230''>write in</span> <span m=''2661510''>our</span> <span m=''2661620''>programs.</span>
  <span m=''2662320''>But</span> <span m=''2662510''>when</span> <span m=''2662610''>we</span>
  <span m=''2662710''>talk</span> <span m=''2662920''>about</span> <span m=''2663180''>state</span>
  <span m=''2663730''>and</span> <span m=''2663960''>set</span> <span m=''2664710''>and</span>
  <span m=''2664900''>change,</span> <span m=''2665440''>that''s</span> <span m=''2665680''>exactly</span>
  <span m=''2666220''>what</span> <span m=''2666370''>we</span> <span m=''2666480''>do</span>
  <span m=''2666680''>want</span> <span m=''2666910''>control</span> <span m=''2667350''>of.</span>
  <span m=''2668760''>So</span> <span m=''2668940''>it''s</span> <span m=''2669070''>almost</span>
  <span m=''2669520''>as</span> <span m=''2669680''>if</span> <span m=''2669780''>there''s</span>
  <span m=''2669970''>this</span> <span m=''2670140''>fundamental</span> <span m=''2671480''>contradiction</span>
  <span m=''2672960''>in</span> <span m=''2673070''>what</span> <span m=''2673230''>you</span>
  <span m=''2673390''>want.</span> </p><p><span m=''2674570''>And</span> <span m=''2676040''>that</span>
  <span m=''2676250''>brings</span> <span m=''2676450''>us</span> <span m=''2676550''>back</span>
  <span m=''2676730''>to</span> <span m=''2676820''>these</span> <span m=''2677770''>sort</span>
  <span m=''2677940''>of</span> <span m=''2678010''>philosophical</span> <span m=''2678710''>mutterings</span>
  <span m=''2679280''>about</span> <span m=''2679420''>what</span> <span m=''2679560''>is</span>
  <span m=''2679700''>it</span> <span m=''2679790''>that</span> <span m=''2679930''>you''re</span>
  <span m=''2680020''>trying</span> <span m=''2680200''>to</span> <span m=''2680370''>model</span>
  <span m=''2680720''>and</span> <span m=''2680820''>how</span> <span m=''2680930''>do</span>
  <span m=''2681030''>you</span> <span m=''2681120''>look</span> <span m=''2681240''>at</span>
  <span m=''2681360''>the</span> <span m=''2681610''>world.</span> <span m=''2682410''>Or</span>
  <span m=''2682980''>sometimes</span> <span m=''2683410''>this is</span> <span m=''2683610''>called</span>
  <span m=''2683870''>the</span> <span m=''2684860''>debate</span> <span m=''2685200''>over</span>
  <span m=''2685400''>functional</span> <span m=''2685890''>programming.</span> <span
  m=''2693570''>A</span> <span m=''2694030''>so-called</span> <span m=''2694600''>purely</span>
  <span m=''2695490''>functional</span> <span m=''2696100''>language</span> <span
  m=''2697100''>is</span> <span m=''2697260''>one</span> <span m=''2697420''>that</span>
  <span m=''2697550''>just</span> <span m=''2697730''>doesn''t</span> <span m=''2698020''>have</span>
  <span m=''2698290''>any</span> <span m=''2698530''>side</span> <span m=''2698800''>effects.</span>
  <span m=''2700440''>Since</span> <span m=''2700690''>you</span> <span m=''2700820''>have</span>
  <span m=''2700940''>no</span> <span m=''2701110''>side</span> <span m=''2701400''>effects,</span>
  <span m=''2701640''>there''s</span> <span m=''2701790''>no</span> <span m=''2702010''>assignment</span>
  <span m=''2702450''>operator,</span> <span m=''2703270''>so</span> <span m=''2703450''>there</span>
  <span m=''2703540''>are</span> <span m=''2703570''>no</span> <span m=''2703700''>terrible</span>
  <span m=''2704720''>consequences</span> <span m=''2705420''>of</span> <span m=''2705560''>it.</span>
  <span m=''2706360''>You</span> <span m=''2706480''>can</span> <span m=''2706590''>use</span>
  <span m=''2706770''>a</span> <span m=''2706820''>substitution-like</span> <span
  m=''2707710''>thing.</span> <span m=''2707930''>Programs</span> <span m=''2708370''>really</span>
  <span m=''2708890''>are</span> <span m=''2709090''>like</span> <span m=''2709350''>mathematics</span>
  <span m=''2710040''>and</span> <span m=''2710120''>not</span> <span m=''2710910''>like</span>
  <span m=''2711120''>models</span> <span m=''2711480''>in</span> <span m=''2711550''>the</span>
  <span m=''2711630''>real</span> <span m=''2711800''>world,</span> <span m=''2712085''>not</span>
  <span m=''2712370''>like</span> <span m=''2712640''>objects</span> <span m=''2713040''>in</span>
  <span m=''2713110''>the</span> <span m=''2713180''>real</span> <span m=''2713370''>world.</span>
  </p><p><span m=''2715050''>There</span> <span m=''2715160''>are</span> <span m=''2715180''>a</span>
  <span m=''2715270''>lot</span> <span m=''2715370''>of</span> <span m=''2715460''>wonderful</span>
  <span m=''2715860''>things</span> <span m=''2716100''>about</span> <span m=''2716350''>functional</span>
  <span m=''2716720''>languages.</span> <span m=''2717170''>Since</span> <span m=''2717340''>there''s</span>
  <span m=''2717510''>no</span> <span m=''2717650''>time,</span> <span m=''2717990''>you</span>
  <span m=''2718080''>never</span> <span m=''2718270''>have</span> <span m=''2718430''>any</span>
  <span m=''2718560''>synchronization</span> <span m=''2719240''>problems.</span>
  <span m=''2720750''>And</span> <span m=''2720880''>if</span> <span m=''2720970''>you</span>
  <span m=''2721080''>want</span> <span m=''2721180''>to</span> <span m=''2721290''>put</span>
  <span m=''2721470''>something</span> <span m=''2721780''>into</span> <span m=''2722110''>a</span>
  <span m=''2722650''>parallel</span> <span m=''2723140''>algorithm,</span> <span
  m=''2724710''>you</span> <span m=''2724830''>can</span> <span m=''2724970''>run</span>
  <span m=''2725470''>the</span> <span m=''2725580''>pieces</span> <span m=''2725920''>of</span>
  <span m=''2726000''>that</span> <span m=''2726160''>parallel</span> <span m=''2726820''>processing</span>
  <span m=''2727330''>any</span> <span m=''2727510''>way</span> <span m=''2727650''>you</span>
  <span m=''2727810''>want.</span> <span m=''2729260''>There''s</span> <span m=''2729480''>just</span>
  <span m=''2729800''>never</span> <span m=''2730020''>any</span> <span m=''2730140''>synchronization</span>
  <span m=''2730810''>to</span> <span m=''2730880''>worry</span> <span m=''2731120''>that,
  and</span> <span m=''2731350''>it''s</span> <span m=''2731500''>a</span> <span m=''2731550''>very</span>
  <span m=''2731860''>congenial</span> <span m=''2732330''>environment</span> <span
  m=''2732790''>for</span> <span m=''2732880''>doing</span> <span m=''2733150''>this.</span>
  <span m=''2733640''>The</span> <span m=''2733780''>price</span> <span m=''2734200''>is</span>
  <span m=''2734780''>you</span> <span m=''2734850''>give</span> <span m=''2735040''>up</span>
  <span m=''2735160''>assignment.</span> <span m=''2739060''>So</span> <span m=''2739380''>an</span>
  <span m=''2739670''>advocate</span> <span m=''2740170''>of</span> <span m=''2740260''>a</span>
  <span m=''2740320''>functional</span> <span m=''2740740''>language</span> <span
  m=''2741070''>would</span> <span m=''2741170''>say,</span> <span m=''2741310''>gee,</span>
  <span m=''2741460''>that''s</span> <span m=''2741670''>just</span> <span m=''2741840''>a</span>
  <span m=''2741920''>tiny</span> <span m=''2742320''>price</span> <span m=''2742620''>to</span>
  <span m=''2742720''>pay.</span> <span m=''2744520''>You</span> <span m=''2744630''>probably</span>
  <span m=''2744980''>shouldn''t</span> <span m=''2745210''>use</span> <span m=''2745360''>assignment</span>
  <span m=''2745690''>most</span> <span m=''2745950''>of the time</span> <span m=''2746140''>anyway.</span>
  <span m=''2746510''>And</span> <span m=''2746970''>if</span> <span m=''2747150''>you</span>
  <span m=''2747220''>just</span> <span m=''2747410''>give</span> <span m=''2747530''>up</span>
  <span m=''2747650''>assignment,</span> <span m=''2748470''>you</span> <span m=''2748590''>can</span>
  <span m=''2749020''>be in</span> <span m=''2749190''>this</span> <span m=''2749360''>much,</span>
  <span m=''2749630''>much</span> <span m=''2750720''>nicer</span> <span m=''2751040''>world</span>
  <span m=''2752060''>than</span> <span m=''2752160''>this</span> <span m=''2752340''>place</span>
  <span m=''2752600''>with</span> <span m=''2752730''>objects.</span> </p><p><span
  m=''2754190''>Well,</span> <span m=''2755030''>what''s</span> <span m=''2755200''>the</span>
  <span m=''2755360''>rejoinder</span> <span m=''2755860''>to</span> <span m=''2755990''>that?</span>
  <span m=''2756300''>Remember</span> <span m=''2757170''>how</span> <span m=''2757300''>we</span>
  <span m=''2757420''>got</span> <span m=''2757640''>into</span> <span m=''2757990''>this</span>
  <span m=''2758240''>mess.</span> <span m=''2760300''>We</span> <span m=''2760380''>started</span>
  <span m=''2760730''>trying</span> <span m=''2761040''>to</span> <span m=''2762100''>model</span>
  <span m=''2762490''>things</span> <span m=''2762730''>that</span> <span m=''2762850''>had</span>
  <span m=''2763000''>local</span> <span m=''2763310''>state.</span> <span m=''2764440''>So</span>
  <span m=''2764550''>remember</span> <span m=''2764930''>Jerry''s</span> <span m=''2765310''>random</span>
  <span m=''2765670''>number</span> <span m=''2765920''>generator.</span> <span m=''2766840''>There</span>
  <span m=''2767120''>was</span> <span m=''2767400''>this</span> <span m=''2767510''>random</span>
  <span m=''2767870''>number</span> <span m=''2768110''>generator</span> <span m=''2769370''>that</span>
  <span m=''2769490''>had</span> <span m=''2769640''>some</span> <span m=''2769830''>little</span>
  <span m=''2770000''>state</span> <span m=''2770370''>in</span> <span m=''2770540''>it</span>
  <span m=''2770700''>to</span> <span m=''2770970''>compute</span> <span m=''2771250''>the</span>
  <span m=''2771410''>next</span> <span m=''2771580''>random</span> <span m=''2771870''>number</span>
  <span m=''2772140''>and</span> <span m=''2772210''>the</span> <span m=''2772290''>next</span>
  <span m=''2772530''>random</span> <span m=''2772800''>number</span> <span m=''2773060''>and</span>
  <span m=''2773120''>the</span> <span m=''2773200''>next</span> <span m=''2773450''>random</span>
  <span m=''2773730''>number.</span> <span m=''2774080''>And</span> <span m=''2774370''>we</span>
  <span m=''2774520''>wanted</span> <span m=''2774670''>to</span> <span m=''2774730''>hide</span>
  <span m=''2775040''>that</span> <span m=''2775240''>state</span> <span m=''2775550''>away</span>
  <span m=''2775740''>from</span> <span m=''2775930''>the</span> <span m=''2776350''>Cesaro</span>
  <span m=''2777830''>compute</span> <span m=''2778200''>part</span> <span m=''2778440''>process,</span>
  <span m=''2779420''>and</span> <span m=''2779850''>that''s</span> <span m=''2780170''>why</span>
  <span m=''2780280''>we</span> <span m=''2780400''>needed</span> <span m=''2780640''>set.</span>
  <span m=''2781050''>We wanted</span> <span m=''2781220''>to</span> <span m=''2781270''>package</span>
  <span m=''2781670''>that</span> <span m=''2781840''>stated</span> <span m=''2782160''>modularly.</span>
  </p><p><span m=''2784070''>Well,</span> <span m=''2784590''>a</span> <span m=''2784880''>functional</span>
  <span m=''2785250''>programming</span> <span m=''2785700''>person</span> <span m=''2786030''>would</span>
  <span m=''2786140''>say,</span> <span m=''2786290''>well,</span> <span m=''2786790''>you''re</span>
  <span m=''2786920''>just</span> <span m=''2787160''>all</span> <span m=''2787300''>wet.</span>
  <span m=''2787560''>I</span> <span m=''2787610''>mean,</span> <span m=''2787870''>you</span>
  <span m=''2787950''>can</span> <span m=''2788100''>write</span> <span m=''2788310''>a</span>
  <span m=''2788360''>perfectly</span> <span m=''2788810''>good</span> <span m=''2788990''>modular</span>
  <span m=''2789400''>program.</span> <span m=''2789840''>It''s</span> <span m=''2789940''>just</span>
  <span m=''2790140''>you''re</span> <span m=''2791100''>thinking about</span> <span
  m=''2791340''>modularity</span> <span m=''2792070''>wrong.</span> <span m=''2793250''>You''re</span>
  <span m=''2793380''>hung</span> <span m=''2793700''>up</span> <span m=''2793920''>in</span>
  <span m=''2794030''>this</span> <span m=''2794200''>next</span> <span m=''2794470''>random</span>
  <span m=''2794760''>number</span> <span m=''2795030''>and</span> <span m=''2795090''>the</span>
  <span m=''2795170''>next</span> <span m=''2795420''>random</span> <span m=''2795700''>number</span>
  <span m=''2795960''>and</span> <span m=''2796030''>the</span> <span m=''2796110''>next</span>
  <span m=''2796370''>random</span> <span m=''2796630''>number.</span> <span m=''2796880''>Why</span>
  <span m=''2797100''>don''t</span> <span m=''2797250''>you</span> <span m=''2797340''>just</span>
  <span m=''2797540''>say</span> <span m=''2798530''>let''s</span> <span m=''2798680''>write</span>
  <span m=''2798850''>a</span> <span m=''2798910''>program.</span> <span m=''2799880''>Let''s</span>
  <span m=''2800300''>write</span> <span m=''2800470''>an</span> <span m=''2800580''>enumerator</span>
  <span m=''2801940''>which</span> <span m=''2802180''>just</span> <span m=''2802410''>generates</span>
  <span m=''2802890''>an</span> <span m=''2802990''>infinite</span> <span m=''2803360''>stream</span>
  <span m=''2803690''>of</span> <span m=''2803790''>random</span> <span m=''2804160''>numbers.</span>
  <span m=''2809010''>We can</span> <span m=''2809290''>sort of</span> <span m=''2809610''>have</span>
  <span m=''2809870''>that stream</span> <span m=''2810290''>all</span> <span m=''2810430''>at</span>
  <span m=''2810500''>once,</span> <span m=''2812640''>and</span> <span m=''2812800''>that''s</span>
  <span m=''2812970''>going</span> <span m=''2813040''>to</span> <span m=''2813100''>be</span>
  <span m=''2813170''>our</span> <span m=''2813260''>source</span> <span m=''2813730''>of</span>
  <span m=''2813850''>random</span> <span m=''2814180''>numbers.</span> <span m=''2814540''>And
  then</span> <span m=''2814710''>if</span> <span m=''2814790''>you</span> <span m=''2814950''>like,</span>
  <span m=''2815510''>you</span> <span m=''2815630''>can</span> <span m=''2815770''>put</span>
  <span m=''2815960''>that</span> <span m=''2816160''>through</span> <span m=''2816300''>some</span>
  <span m=''2816480''>sort</span> <span m=''2816690''>of</span> <span m=''2816770''>processor,</span>
  <span m=''2817850''>which</span> <span m=''2818060''>is--</span> <span m=''2818530''>I</span>
  <span m=''2818660''>don''t</span> <span m=''2818790''>know--</span> <span m=''2819530''>a</span>
  <span m=''2819920''>Cesaro</span> <span m=''2820860''>test,</span> <span m=''2824660''>and</span>
  <span m=''2825090''>that</span> <span m=''2825150''>can</span> <span m=''2825340''>do</span>
  <span m=''2825480''>what</span> <span m=''2825600''>it</span> <span m=''2825700''>wants.</span>
  </p><p><span m=''2826880''>And</span> <span m=''2827480''>what</span> <span m=''2827600''>would</span>
  <span m=''2827710''>come</span> <span m=''2827900''>out</span> <span m=''2828120''>of</span>
  <span m=''2828220''>there</span> <span m=''2828680''>would</span> <span m=''2828850''>be</span>
  <span m=''2829020''>a</span> <span m=''2829070''>stream</span> <span m=''2829640''>of</span>
  <span m=''2836320''>successive</span> <span m=''2841130''>approximations</span>
  <span m=''2846790''>to pi.</span> <span m=''2848140''>So</span> <span m=''2848360''>as</span>
  <span m=''2848450''>we</span> <span m=''2848570''>looked</span> <span m=''2849190''>further</span>
  <span m=''2849790''>down</span> <span m=''2850040''>this</span> <span m=''2850130''>stream,</span>
  <span m=''2850870''>we''d</span> <span m=''2851040''>tug</span> <span m=''2851280''>on</span>
  <span m=''2851400''>this</span> <span m=''2851600''>Cesaro</span> <span m=''2851950''>thing,</span>
  <span m=''2853170''>and</span> <span m=''2853330''>it</span> <span m=''2853400''>would</span>
  <span m=''2853850''>pull</span> <span m=''2854110''>out</span> <span m=''2854260''>more</span>
  <span m=''2854420''>and</span> <span m=''2854480''>more</span> <span m=''2854650''>random</span>
  <span m=''2854930''>numbers.</span> <span m=''2855540''>And</span> <span m=''2855640''>the</span>
  <span m=''2855750''>further</span> <span m=''2856070''>and</span> <span m=''2856160''>further</span>
  <span m=''2856370''>we</span> <span m=''2856470''>look</span> <span m=''2856610''>down
  the stream,</span> <span m=''2857120''>the</span> <span m=''2857200''>better</span>
  <span m=''2857480''>an</span> <span m=''2857530''>approximation</span> <span m=''2858220''>we''d</span>
  <span m=''2858310''>get</span> <span m=''2858490''>to</span> <span m=''2858600''>pi.</span>
  <span m=''2859720''>And</span> <span m=''2859810''>it would</span> <span m=''2859900''>do</span>
  <span m=''2860000''>exactly</span> <span m=''2860470''>the</span> <span m=''2860540''>same</span>
  <span m=''2860750''>as</span> <span m=''2860820''>the</span> <span m=''2860950''>other</span>
  <span m=''2861080''>computation,</span> <span m=''2861850''>except</span> <span
  m=''2862120''>we''re thinking</span> <span m=''2862450''>about</span> <span m=''2862590''>the</span>
  <span m=''2862740''>modularity</span> <span m=''2863390''>different.</span> <span
  m=''2863890''>We''re</span> <span m=''2863980''>saying</span> <span m=''2864310''>imagine</span>
  <span m=''2864580''>we</span> <span m=''2864750''>had</span> <span m=''2865060''>all</span>
  <span m=''2865420''>those</span> <span m=''2865660''>infinite</span> <span m=''2866020''>streams</span>
  <span m=''2866270''>of</span> <span m=''2866360''>random</span> <span m=''2866670''>numbers</span>
  <span m=''2866990''>all</span> <span m=''2867160''>at</span> <span m=''2867220''>once.</span>
  <span m=''2869400''>You</span> <span m=''2869500''>can</span> <span m=''2869610''>see</span>
  <span m=''2869750''>the</span> <span m=''2869830''>details</span> <span m=''2870280''>of</span>
  <span m=''2870360''>this</span> <span m=''2871250''>procedure</span> <span m=''2871670''>in
  the</span> <span m=''2871760''>book.</span> </p><p><span m=''2873860''>Similarly,</span>
  <span m=''2874600''>there</span> <span m=''2874780''>are</span> <span m=''2874900''>other</span>
  <span m=''2875070''>things</span> <span m=''2875670''>that</span> <span m=''2875870''>we</span>
  <span m=''2876070''>tend</span> <span m=''2876550''>to</span> <span m=''2876650''>get</span>
  <span m=''2876940''>locked</span> <span m=''2877290''>into</span> <span m=''2878350''>on</span>
  <span m=''2878870''>this</span> <span m=''2879210''>one</span> <span m=''2879480''>and</span>
  <span m=''2879700''>that</span> <span m=''2879920''>one</span> <span m=''2880080''>and</span>
  <span m=''2880170''>the</span> <span m=''2880250''>next</span> <span m=''2880520''>one</span>
  <span m=''2880660''>and</span> <span m=''2880730''>the</span> <span m=''2880800''>next</span>
  <span m=''2881040''>one,</span> <span m=''2881330''>which</span> <span m=''2881550''>don''t</span>
  <span m=''2881720''>have</span> <span m=''2881880''>to</span> <span m=''2881980''>be</span>
  <span m=''2882240''>that</span> <span m=''2882520''>way.</span> <span m=''2883280''>Like</span>
  <span m=''2883500''>you</span> <span m=''2883570''>might</span> <span m=''2883770''>think</span>
  <span m=''2883930''>about</span> <span m=''2885320''>like</span> <span m=''2885480''>a</span>
  <span m=''2885560''>banking</span> <span m=''2886000''>system,</span> <span m=''2887750''>which</span>
  <span m=''2887930''>is a</span> <span m=''2888080''>very</span> <span m=''2888330''>simple</span>
  <span m=''2888680''>idea.</span> <span m=''2888900''>Imagine</span> <span m=''2889260''>we</span>
  <span m=''2889390''>have</span> <span m=''2889530''>a</span> <span m=''2889580''>program</span>
  <span m=''2890430''>that</span> <span m=''2890650''>sort</span> <span m=''2890820''>of</span>
  <span m=''2890960''>represents</span> <span m=''2891430''>a</span> <span m=''2891480''>bank</span>
  <span m=''2891760''>account.</span> <span m=''2898810''>The</span> <span m=''2899020''>bank</span>
  <span m=''2899320''>account</span> <span m=''2899890''>might</span> <span m=''2900160''>have</span>
  <span m=''2900440''>in</span> <span m=''2900620''>it--</span> <span m=''2902860''>if</span>
  <span m=''2902990''>we</span> <span m=''2903080''>looked</span> <span m=''2903290''>at</span>
  <span m=''2903410''>this</span> <span m=''2903530''>in</span> <span m=''2903650''>a</span>
  <span m=''2904580''>sort</span> <span m=''2904750''>of</span> <span m=''2904820''>message-passing</span>
  <span m=''2905590''>view</span> <span m=''2905770''>of</span> <span m=''2905820''>the</span>
  <span m=''2906020''>world,</span> <span m=''2906410''>we''d</span> <span m=''2906610''>say</span>
  <span m=''2906740''>a</span> <span m=''2906780''>bank</span> <span m=''2907070''>account</span>
  <span m=''2907370''>is</span> <span m=''2907460''>an</span> <span m=''2907540''>object</span>
  <span m=''2908600''>that</span> <span m=''2908730''>has</span> <span m=''2908900''>some</span>
  <span m=''2909070''>local</span> <span m=''2909350''>state</span> <span m=''2909670''>in</span>
  <span m=''2909780''>there,</span> <span m=''2909950''>which</span> <span m=''2910130''>is</span>
  <span m=''2910230''>the</span> <span m=''2910310''>balance,</span> <span m=''2911190''>say.</span>
  </p><p><span m=''2914110''>And</span> <span m=''2914290''>a</span> <span m=''2914340''>user</span>
  <span m=''2914720''>using</span> <span m=''2915070''>this</span> <span m=''2915160''>system</span>
  <span m=''2915590''>comes</span> <span m=''2916420''>and</span> <span m=''2916630''>sends</span>
  <span m=''2916900''>a</span> <span m=''2916960''>transaction</span> <span m=''2917640''>request.</span>
  <span m=''2919410''>So</span> <span m=''2919550''>the</span> <span m=''2919650''>user</span>
  <span m=''2919930''>sends</span> <span m=''2920150''>a</span> <span m=''2920200''>transaction</span>
  <span m=''2920800''>request,</span> <span m=''2921070''>like</span> <span m=''2921230''>deposit</span>
  <span m=''2921700''>some</span> <span m=''2921850''>money,</span> <span m=''2922360''>and</span>
  <span m=''2922460''>the</span> <span m=''2922560''>bank</span> <span m=''2922850''>account</span>
  <span m=''2923130''>maybe--</span> <span m=''2923970''>let''s</span> <span m=''2924120''>say</span>
  <span m=''2924210''>the</span> <span m=''2924300''>bank</span> <span m=''2924550''>account</span>
  <span m=''2924780''>always</span> <span m=''2925040''>responds</span> <span m=''2925490''>with</span>
  <span m=''2925620''>what</span> <span m=''2925770''>the</span> <span m=''2925850''>current</span>
  <span m=''2926170''>balance</span> <span m=''2926505''>is.</span> <span m=''2928560''>The</span>
  <span m=''2928780''>user</span> <span m=''2928840''>says let''s</span> <span m=''2929190''>deposits</span>
  <span m=''2929670''>some</span> <span m=''2929750''>money,</span> <span m=''2929990''>and</span>
  <span m=''2930050''>the</span> <span m=''2930120''>bank</span> <span m=''2930360''>account</span>
  <span m=''2931510''>sends</span> <span m=''2931810''>back</span> <span m=''2932000''>a</span>
  <span m=''2932050''>message</span> <span m=''2932410''>which</span> <span m=''2932580''>is</span>
  <span m=''2932690''>the</span> <span m=''2932780''>balance.</span> <span m=''2934350''>And</span>
  <span m=''2935540''>the</span> <span m=''2935840''>user</span> <span m=''2936290''>says</span>
  <span m=''2936560''>deposit some</span> <span m=''2937050''>more,</span> <span m=''2937320''>and</span>
  <span m=''2937380''>the</span> <span m=''2937430''>bank</span> <span m=''2937670''>account</span>
  <span m=''2937970''>sends back a</span> <span m=''2938330''>message.</span> <span
  m=''2939150''>And</span> <span m=''2939300''>just</span> <span m=''2939460''>like</span>
  <span m=''2939590''>the</span> <span m=''2939680''>random</span> <span m=''2939950''>number</span>
  <span m=''2940190''>generator,</span> <span m=''2940620''>you''d</span> <span m=''2940760''>say,</span>
  <span m=''2940900''>gee,</span> <span m=''2941060''>we</span> <span m=''2941170''>would</span>
  <span m=''2941290''>like</span> <span m=''2941540''>to use</span> <span m=''2941720''>set.</span>
  <span m=''2943200''>We''d</span> <span m=''2943310''>like</span> <span m=''2943440''>to</span>
  <span m=''2943570''>have</span> <span m=''2944210''>balance</span> <span m=''2944740''>be</span>
  <span m=''2944850''>a</span> <span m=''2944900''>piece</span> <span m=''2945100''>of</span>
  <span m=''2945200''>local</span> <span m=''2945550''>state</span> <span m=''2945830''>inside</span>
  <span m=''2946150''>this</span> <span m=''2946290''>bank</span> <span m=''2946550''>account</span>
  <span m=''2946850''>because</span> <span m=''2947080''>we</span> <span m=''2947170''>want</span>
  <span m=''2947240''>to</span> <span m=''2947320''>separate</span> <span m=''2947710''>the</span>
  <span m=''2947770''>state</span> <span m=''2948040''>of</span> <span m=''2948110''>the</span>
  <span m=''2948190''>user</span> <span m=''2948500''>from</span> <span m=''2948640''>the</span>
  <span m=''2948700''>state</span> <span m=''2948940''>of</span> <span m=''2949000''>the</span>
  <span m=''2949070''>bank</span> <span m=''2949280''>account.</span> </p><p><span
  m=''2953280''>Well,</span> <span m=''2953630''>that''s</span> <span m=''2954620''>the</span>
  <span m=''2954690''>message-processing</span> <span m=''2955990''>view.</span> <span
  m=''2956420''>There''s</span> <span m=''2956720''>a</span> <span m=''2956770''>stream</span>
  <span m=''2957210''>view</span> <span m=''2957460''>with</span> <span m=''2957570''>that</span>
  <span m=''2957820''>thing,</span> <span m=''2959600''>which</span> <span m=''2959780''>does</span>
  <span m=''2959960''>the</span> <span m=''2960030''>same</span> <span m=''2960300''>thing</span>
  <span m=''2960660''>without</span> <span m=''2961030''>any</span> <span m=''2961210''>set
  or</span> <span m=''2961510''>side</span> <span m=''2961760''>effects.</span> <span
  m=''2962740''>And</span> <span m=''2962860''>the</span> <span m=''2962970''>idea</span>
  <span m=''2963790''>is</span> <span m=''2966220''>again</span> <span m=''2967400''>we</span>
  <span m=''2967540''>don''t</span> <span m=''2968180''>think</span> <span m=''2968410''>about</span>
  <span m=''2968680''>anything</span> <span m=''2969060''>having</span> <span m=''2969380''>local</span>
  <span m=''2969660''>state.</span> <span m=''2971180''>We</span> <span m=''2971310''>think</span>
  <span m=''2971480''>about</span> <span m=''2971650''>the</span> <span m=''2971820''>bank</span>
  <span m=''2972130''>account</span> <span m=''2972460''>as</span> <span m=''2972580''>something</span>
  <span m=''2973270''>that''s</span> <span m=''2973640''>going</span> <span m=''2973720''>to</span>
  <span m=''2973800''>process</span> <span m=''2975470''>a</span> <span m=''2975610''>stream</span>
  <span m=''2976500''>of</span> <span m=''2976670''>transaction</span> <span m=''2977320''>requests.</span>
  <span m=''2978640''>So</span> <span m=''2978840''>think</span> <span m=''2979050''>about</span>
  <span m=''2979290''>this</span> <span m=''2979450''>bank</span> <span m=''2979730''>account
  not</span> <span m=''2980160''>as</span> <span m=''2980240''>something</span> <span
  m=''2980520''>that</span> <span m=''2980670''>goes</span> <span m=''2980880''>message</span>
  <span m=''2981270''>by</span> <span m=''2981400''>message,</span> <span m=''2982200''>but</span>
  <span m=''2982640''>something</span> <span m=''2983080''>that</span> <span m=''2984080''>takes</span>
  <span m=''2984360''>in</span> <span m=''2984460''>a</span> <span m=''2984510''>stream</span>
  <span m=''2985010''>of</span> <span m=''2985100''>transaction</span> <span m=''2985710''>requests</span>
  <span m=''2986210''>like</span> <span m=''2986390''>maybe</span> <span m=''2986610''>successive</span>
  <span m=''2987160''>deposit</span> <span m=''2987630''>announced.</span> <span m=''2989490''>1,</span>
  <span m=''2990300''>2,</span> <span m=''2991080''>2,</span> <span m=''2991930''>4,</span>
  <span m=''2992850''>those</span> <span m=''2993100''>might</span> <span m=''2993230''>be</span>
  <span m=''2993340''>successive</span> <span m=''2993820''>amounts</span> <span m=''2994150''>to</span>
  <span m=''2994240''>deposit.</span> <span m=''2995940''>And</span> <span m=''2996200''>then</span>
  <span m=''2997170''>coming</span> <span m=''2997500''>out</span> <span m=''2997660''>of</span>
  <span m=''2997740''>it</span> <span m=''2997860''>is</span> <span m=''2997980''>the</span>
  <span m=''2998050''>successive</span> <span m=''2998570''>balances</span> <span
  m=''2999120''>1,</span> <span m=''2999730''>3,</span> <span m=''3000810''>5,</span>
  <span m=''3001920''>9.</span> </p><p><span m=''3003770''>So</span> <span m=''3003930''>we</span>
  <span m=''3004040''>think</span> <span m=''3004200''>of</span> <span m=''3004260''>the</span>
  <span m=''3004340''>bank</span> <span m=''3004620''>account</span> <span m=''3004920''>not</span>
  <span m=''3005100''>as</span> <span m=''3005180''>something</span> <span m=''3005430''>that</span>
  <span m=''3005550''>has</span> <span m=''3005740''>state,</span> <span m=''3006270''>but</span>
  <span m=''3006600''>something</span> <span m=''3006900''>that</span> <span m=''3007030''>acts</span>
  <span m=''3008940''>sort of</span> <span m=''3009210''>on</span> <span m=''3009300''>the</span>
  <span m=''3009490''>infinite</span> <span m=''3009970''>stream</span> <span m=''3010260''>of</span>
  <span m=''3010380''>requests.</span> <span m=''3010820''>But</span> <span m=''3010930''>remember,</span>
  <span m=''3011180''>we''ve</span> <span m=''3011360''>thrown</span> <span m=''3011580''>away</span>
  <span m=''3011780''>time.</span> <span m=''3012370''>So what</span> <span m=''3012610''>we</span>
  <span m=''3012760''>can</span> <span m=''3012900''>do</span> <span m=''3013110''>is</span>
  <span m=''3013250''>if</span> <span m=''3013350''>the</span> <span m=''3013440''>user''s</span>
  <span m=''3013860''>here,</span> <span m=''3016280''>we</span> <span m=''3016410''>can</span>
  <span m=''3016530''>have</span> <span m=''3017720''>this</span> <span m=''3017950''>infinite</span>
  <span m=''3018360''>stream</span> <span m=''3018660''>of</span> <span m=''3018760''>requests</span>
  <span m=''3019160''>being</span> <span m=''3019360''>generated</span> <span m=''3019900''>one</span>
  <span m=''3020100''>at</span> <span m=''3020170''>a</span> <span m=''3020240''>time</span>
  <span m=''3021530''>coming</span> <span m=''3021790''>from</span> <span m=''3021940''>the</span>
  <span m=''3022040''>user</span> <span m=''3024190''>and</span> <span m=''3025470''>this</span>
  <span m=''3025640''>transaction</span> <span m=''3026260''>stream</span> <span m=''3026520''>coming</span>
  <span m=''3026780''>back</span> <span m=''3027000''>on</span> <span m=''3027110''>a</span>
  <span m=''3027160''>printer</span> <span m=''3027510''>being</span> <span m=''3027720''>printed</span>
  <span m=''3028040''>one</span> <span m=''3028210''>at</span> <span m=''3028280''>a</span>
  <span m=''3028350''>time.</span> <span m=''3030010''>And</span> <span m=''3030160''>if</span>
  <span m=''3030250''>we</span> <span m=''3030320''>drew</span> <span m=''3030580''>a
  little</span> <span m=''3030630''>line</span> <span m=''3031010''>here,</span> <span
  m=''3032570''>right</span> <span m=''3032810''>there</span> <span m=''3033160''>to</span>
  <span m=''3033360''>the</span> <span m=''3033470''>user,</span> <span m=''3033850''>the</span>
  <span m=''3033910''>user</span> <span m=''3034220''>couldn''t</span> <span m=''3034550''>tell</span>
  <span m=''3035870''>that</span> <span m=''3036460''>this</span> <span m=''3036550''>system</span>
  <span m=''3036910''>doesn''t</span> <span m=''3037180''>have</span> <span m=''3037360''>state.</span>
  <span m=''3039560''>It</span> <span m=''3039730''>looks</span> <span m=''3039910''>just</span>
  <span m=''3040250''>like</span> <span m=''3040470''>the</span> <span m=''3040580''>other</span>
  <span m=''3040830''>one,</span> <span m=''3041300''>but</span> <span m=''3041410''>there''s</span>
  <span m=''3041570''>no</span> <span m=''3041680''>state</span> <span m=''3041990''>in</span>
  <span m=''3042110''>there.</span> </p><p><span m=''3045120''>And</span> <span m=''3045320''>by</span>
  <span m=''3045430''>the</span> <span m=''3045550''>way,</span> <span m=''3046800''>just</span>
  <span m=''3046950''>to</span> <span m=''3047040''>show</span> <span m=''3047230''>you,</span>
  <span m=''3047360''>here''s</span> <span m=''3047580''>an</span> <span m=''3047660''>actual</span>
  <span m=''3048510''>implementation</span> <span m=''3050550''>of</span> <span m=''3050760''>this--</span>
  <span m=''3051000''>we''ll call it</span> <span m=''3051260''>make</span> <span
  m=''3051460''>deposit</span> <span m=''3051900''>account</span> <span m=''3052240''>because</span>
  <span m=''3052410''>you</span> <span m=''3052490''>can</span> <span m=''3052610''>only</span>
  <span m=''3052780''>deposit.</span> <span m=''3053835''>It</span> <span m=''3054320''>takes</span>
  <span m=''3054580''>an</span> <span m=''3054830''>initial</span> <span m=''3055240''>balance</span>
  <span m=''3056090''>and</span> <span m=''3056270''>then</span> <span m=''3056370''>a</span>
  <span m=''3056410''>stream</span> <span m=''3056840''>of</span> <span m=''3056920''>deposits</span>
  <span m=''3057430''>you</span> <span m=''3057540''>might</span> <span m=''3057740''>make.</span>
  <span m=''3060020''>And</span> <span m=''3060370''>what</span> <span m=''3060540''>is</span>
  <span m=''3060690''>it?</span> <span m=''3060820''>Well, it''s</span> <span m=''3061080''>just</span>
  <span m=''3061260''>cons-stream</span> <span m=''3061820''>of</span> <span m=''3061900''>the</span>
  <span m=''3061980''>balance</span> <span m=''3063240''>onto</span> <span m=''3064140''>make</span>
  <span m=''3064390''>a</span> <span m=''3064440''>new</span> <span m=''3064580''>account</span>
  <span m=''3064930''>stream</span> <span m=''3066210''>whose</span> <span m=''3066460''>initial</span>
  <span m=''3066840''>balance</span> <span m=''3067530''>is</span> <span m=''3067710''>the</span>
  <span m=''3067840''>old</span> <span m=''3068060''>balance</span> <span m=''3068490''>plus</span>
  <span m=''3068700''>the</span> <span m=''3068780''>first</span> <span m=''3069090''>thing</span>
  <span m=''3069250''>in</span> <span m=''3069320''>the</span> <span m=''3069380''>deposit</span>
  <span m=''3069830''>stream</span> <span m=''3070900''>and</span> <span m=''3073820''>make</span>
  <span m=''3074020''>deposit</span> <span m=''3074440''>account</span> <span m=''3074750''>works</span>
  <span m=''3074970''>on</span> <span m=''3075070''>the</span> <span m=''3075130''>rest</span>
  <span m=''3075460''>of</span> <span m=''3075650''>which</span> <span m=''3075840''>is</span>
  <span m=''3075970''>the</span> <span m=''3076060''>tail</span> <span m=''3076400''>of</span>
  <span m=''3076470''>the</span> <span m=''3076550''>deposit stream.</span> <span
  m=''3078300''>So</span> <span m=''3078500''>there''s</span> <span m=''3080450''>sort</span>
  <span m=''3080630''>of</span> <span m=''3080950''>a</span> <span m=''3081830''>very</span>
  <span m=''3082120''>typical</span> <span m=''3082890''>message-passing,</span> <span
  m=''3084650''>object-oriented</span> <span m=''3085500''>thing</span> <span m=''3085860''>that''s</span>
  <span m=''3086220''>done</span> <span m=''3086430''>without</span> <span m=''3086700''>side</span>
  <span m=''3086890''>effects</span> <span m=''3087180''>at</span> <span m=''3087320''>all.</span>
  <span m=''3088790''>There are</span> <span m=''3089230''>very</span> <span m=''3089560''>many</span>
  <span m=''3089780''>things</span> <span m=''3090010''>you</span> <span m=''3090120''>can</span>
  <span m=''3090240''>do</span> <span m=''3090350''>this</span> <span m=''3090550''>way.</span>
  </p><p><span m=''3092250''>Well,</span> <span m=''3093680''>can</span> <span m=''3093820''>you</span>
  <span m=''3093880''>do</span> <span m=''3094070''>everything</span> <span m=''3094520''>without</span>
  <span m=''3094770''>assignment?</span> <span m=''3096400''>Can</span> <span m=''3096570''>everybody</span>
  <span m=''3096770''>go</span> <span m=''3096940''>over</span> <span m=''3097600''>to</span>
  <span m=''3097750''>purely</span> <span m=''3098050''>functional</span> <span m=''3098450''>languages?</span>
  <span m=''3100050''>Well,</span> <span m=''3101430''>we</span> <span m=''3101490''>don''t</span>
  <span m=''3101720''>know,</span> <span m=''3102260''>but</span> <span m=''3102390''>there</span>
  <span m=''3102510''>seem</span> <span m=''3102790''>to</span> <span m=''3102880''>be</span>
  <span m=''3102990''>places</span> <span m=''3103970''>where</span> <span m=''3104100''>purely</span>
  <span m=''3104450''>functional</span> <span m=''3104850''>programming</span> <span
  m=''3105340''>breaks</span> <span m=''3105640''>down.</span> <span m=''3108100''>Where</span>
  <span m=''3108320''>it</span> <span m=''3108400''>starts</span> <span m=''3108630''>hurting</span>
  <span m=''3109060''>is</span> <span m=''3109180''>when</span> <span m=''3109320''>you</span>
  <span m=''3109450''>have</span> <span m=''3109580''>things</span> <span m=''3109820''>like</span>
  <span m=''3110030''>this,</span> <span m=''3110420''>but</span> <span m=''3110610''>you</span>
  <span m=''3110720''>also</span> <span m=''3111120''>mix</span> <span m=''3111380''>it</span>
  <span m=''3111470''>up</span> <span m=''3112070''>with</span> <span m=''3112700''>the</span>
  <span m=''3112940''>other</span> <span m=''3113100''>things</span> <span m=''3113350''>that</span>
  <span m=''3113440''>we</span> <span m=''3113520''>had</span> <span m=''3113650''>to</span>
  <span m=''3113750''>worry</span> <span m=''3114000''>that,</span> <span m=''3114160''>which</span>
  <span m=''3114330''>are</span> <span m=''3114400''>objects</span> <span m=''3114910''>and</span>
  <span m=''3115100''>sharing</span> <span m=''3115930''>and</span> <span m=''3116140''>two</span>
  <span m=''3116300''>independent</span> <span m=''3117440''>agents</span> <span m=''3117760''>being</span>
  <span m=''3118040''>the same.</span> </p><p><span m=''3118850''>So under</span>
  <span m=''3119150''>a</span> <span m=''3119360''>typical</span> <span m=''3119760''>one,</span>
  <span m=''3120030''>suppose</span> <span m=''3120180''>you</span> <span m=''3120320''>want</span>
  <span m=''3120400''>to</span> <span m=''3120480''>extend</span> <span m=''3120850''>this</span>
  <span m=''3121000''>bank</span> <span m=''3121270''>account.</span> <span m=''3122960''>So</span>
  <span m=''3123380''>here''s</span> <span m=''3123560''>a</span> <span m=''3123610''>bank</span>
  <span m=''3123920''>account.</span> <span m=''3132220''>Bank</span> <span m=''3132480''>accounts</span>
  <span m=''3132830''>take in</span> <span m=''3133130''>a</span> <span m=''3133170''>stream</span>
  <span m=''3133560''>of</span> <span m=''3133650''>transaction</span> <span m=''3134330''>requests</span>
  <span m=''3135180''>and</span> <span m=''3135410''>put</span> <span m=''3135550''>out</span>
  <span m=''3135720''>streams</span> <span m=''3136090''>of,</span> <span m=''3136180''>say,</span>
  <span m=''3136360''>balances</span> <span m=''3136970''>or</span> <span m=''3137300''>responses</span>
  <span m=''3137880''>to</span> <span m=''3137980''>that.</span> <span m=''3138780''>But</span>
  <span m=''3139070''>suppose</span> <span m=''3139220''>you</span> <span m=''3139280''>want</span>
  <span m=''3139390''>to</span> <span m=''3139490''>model</span> <span m=''3139880''>the</span>
  <span m=''3139960''>fact</span> <span m=''3140130''>that</span> <span m=''3140300''>this</span>
  <span m=''3140450''>is</span> <span m=''3140560''>a</span> <span m=''3140620''>joint</span>
  <span m=''3141020''>bank</span> <span m=''3141270''>account</span> <span m=''3142110''>between</span>
  <span m=''3142440''>two</span> <span m=''3143420''>independent</span> <span m=''3143950''>people.</span>
  <span m=''3146090''>So</span> <span m=''3146260''>suppose</span> <span m=''3147860''>there
  are</span> <span m=''3147970''>two</span> <span m=''3148150''>people,</span> <span
  m=''3149000''>say,</span> <span m=''3149190''>Bill</span> <span m=''3150270''>and</span>
  <span m=''3150510''>Dave,</span> <span m=''3151890''>who</span> <span m=''3151940''>have</span>
  <span m=''3152110''>a</span> <span m=''3152160''>joint</span> <span m=''3152450''>bank
  account.</span> <span m=''3155960''>How</span> <span m=''3156100''>would</span>
  <span m=''3156190''>you</span> <span m=''3156270''>model</span> <span m=''3156650''>this?</span>
  </p><p><span m=''3156850''>Well,</span> <span m=''3157320''>Bill</span> <span m=''3157890''>puts</span>
  <span m=''3158150''>out</span> <span m=''3158300''>a</span> <span m=''3158340''>stream</span>
  <span m=''3158620''>of</span> <span m=''3158700''>transaction</span> <span m=''3159290''>requests,</span>
  <span m=''3160250''>and</span> <span m=''3160460''>Dave</span> <span m=''3160650''>puts</span>
  <span m=''3160870''>out</span> <span m=''3160990''>a</span> <span m=''3161030''>stream</span>
  <span m=''3161300''>of</span> <span m=''3161400''>transaction</span> <span m=''3161685''>requests,</span>
  <span m=''3162070''>and</span> <span m=''3162390''>somehow,</span> <span m=''3162690''>they</span>
  <span m=''3162820''>have</span> <span m=''3162940''>to</span> <span m=''3163040''>merge</span>
  <span m=''3163920''>into</span> <span m=''3164130''>this</span> <span m=''3164290''>bank</span>
  <span m=''3164570''>account.</span> <span m=''3165880''>So</span> <span m=''3166080''>what</span>
  <span m=''3166220''>you</span> <span m=''3166320''>might</span> <span m=''3166490''>do</span>
  <span m=''3166600''>is</span> <span m=''3166690''>write</span> <span m=''3166850''>a</span>
  <span m=''3166890''>little</span> <span m=''3167390''>stream</span> <span m=''3167820''>processing</span>
  <span m=''3168370''>thing</span> <span m=''3169490''>called</span> <span m=''3170000''>merge,</span>
  <span m=''3177190''>which sort</span> <span m=''3177350''>of</span> <span m=''3177610''>takes</span>
  <span m=''3177930''>these,</span> <span m=''3178140''>merges</span> <span m=''3178530''>them</span>
  <span m=''3178660''>together,</span> <span m=''3179330''>produces</span> <span m=''3179760''>a</span>
  <span m=''3179810''>single</span> <span m=''3180120''>stream</span> <span m=''3180390''>for</span>
  <span m=''3180490''>the</span> <span m=''3180590''>bank</span> <span m=''3180870''>account.</span>
  <span m=''3181190''>Now</span> <span m=''3181300''>they''re</span> <span m=''3181420''>both</span>
  <span m=''3181630''>talking</span> <span m=''3181930''>to</span> <span m=''3182020''>the</span>
  <span m=''3182110''>same</span> <span m=''3182350''>bank</span> <span m=''3182600''>account.</span>
  <span m=''3183610''>That''s</span> <span m=''3183800''>all</span> <span m=''3183980''>great,</span>
  <span m=''3184360''>but</span> <span m=''3184570''>how</span> <span m=''3184670''>do</span>
  <span m=''3184740''>you</span> <span m=''3184810''>write</span> <span m=''3184980''>merge?</span>
  <span m=''3186600''>What''s</span> <span m=''3186870''>this</span> <span m=''3187170''>procedure</span>
  <span m=''3187650''>merge?</span> <span m=''3189730''>You want to do</span> <span
  m=''3190070''>something</span> <span m=''3190350''>that''s</span> <span m=''3190540''>reasonable.</span>
  </p><p><span m=''3192760''>Your</span> <span m=''3192900''>first</span> <span m=''3193170''>guess</span>
  <span m=''3193390''>might</span> <span m=''3193590''>be</span> <span m=''3193700''>to</span>
  <span m=''3193760''>say,</span> <span m=''3193890''>well,</span> <span m=''3194070''>we''ll</span>
  <span m=''3194180''>take</span> <span m=''3194380''>alternate</span> <span m=''3195330''>requests</span>
  <span m=''3195840''>from</span> <span m=''3196000''>Bill and</span> <span m=''3196300''>Dave.</span>
  <span m=''3198160''>But</span> <span m=''3198350''>what</span> <span m=''3198570''>happens</span>
  <span m=''3198930''>if</span> <span m=''3200050''>suddenly</span> <span m=''3200380''>in</span>
  <span m=''3200450''>the</span> <span m=''3200510''>middle</span> <span m=''3200750''>of</span>
  <span m=''3200880''>this</span> <span m=''3201000''>thing,</span> <span m=''3201160''>Dave</span>
  <span m=''3201410''>goes</span> <span m=''3201610''>away</span> <span m=''3201840''>on</span>
  <span m=''3201950''>vacation</span> <span m=''3202480''>for</span> <span m=''3202610''>two</span>
  <span m=''3202760''>years?</span> <span m=''3204150''>Then</span> <span m=''3204370''>Bill''s</span>
  <span m=''3204580''>sort</span> <span m=''3204790''>of</span> <span m=''3204950''>stuck.</span>
  <span m=''3207690''>So</span> <span m=''3207850''>what</span> <span m=''3207970''>you</span>
  <span m=''3208100''>want</span> <span m=''3208240''>to</span> <span m=''3208370''>do</span>
  <span m=''3208590''>is--</span> <span m=''3208750''>well,</span> <span m=''3208930''>it''s</span>
  <span m=''3209030''>hard</span> <span m=''3209220''>to</span> <span m=''3209300''>describe.</span>
  <span m=''3209750''>What</span> <span m=''3209880''>you</span> <span m=''3209990''>want</span>
  <span m=''3210110''>to</span> <span m=''3210220''>do</span> <span m=''3210440''>is</span>
  <span m=''3212060''>what</span> <span m=''3212230''>people</span> <span m=''3212490''>call</span>
  <span m=''3212750''>fair</span> <span m=''3213090''>merge.</span> <span m=''3218410''>The</span>
  <span m=''3218570''>idea</span> <span m=''3218840''>of</span> <span m=''3218900''>fair</span>
  <span m=''3219220''>merge</span> <span m=''3219860''>is</span> <span m=''3220770''>it</span>
  <span m=''3220940''>sort</span> <span m=''3221110''>of</span> <span m=''3221270''>should</span>
  <span m=''3221470''>do</span> <span m=''3221630''>them</span> <span m=''3221850''>alternately,</span>
  <span m=''3222460''>but</span> <span m=''3222600''>if</span> <span m=''3222710''>there''s</span>
  <span m=''3222910''>nothing</span> <span m=''3223250''>waiting</span> <span m=''3223620''>here,</span>
  <span m=''3223860''>it</span> <span m=''3223930''>should</span> <span m=''3224090''>take</span>
  <span m=''3224310''>one</span> <span m=''3224490''>twice.</span> </p><p><span m=''3226010''>Notice</span>
  <span m=''3226220''>I</span> <span m=''3226280''>can''t</span> <span m=''3226440''>even</span>
  <span m=''3226590''>say</span> <span m=''3226950''>that</span> <span m=''3227190''>without</span>
  <span m=''3227460''>talking</span> <span m=''3227820''>about</span> <span m=''3228100''>time.</span>
  <span m=''3231300''>So</span> <span m=''3232240''>one</span> <span m=''3232450''>of</span>
  <span m=''3232500''>the</span> <span m=''3232750''>other</span> <span m=''3234450''>active</span>
  <span m=''3234830''>researcher</span> <span m=''3235100''>areas</span> <span m=''3235370''>in</span>
  <span m=''3235610''>functional</span> <span m=''3235970''>languages</span> <span
  m=''3236470''>is</span> <span m=''3236590''>inventing</span> <span m=''3237960''>little</span>
  <span m=''3238230''>things</span> <span m=''3238510''>like</span> <span m=''3238720''>fair</span>
  <span m=''3238990''>merge</span> <span m=''3240320''>and</span> <span m=''3240480''>maybe</span>
  <span m=''3240720''>some</span> <span m=''3240940''>others,</span> <span m=''3241470''>which</span>
  <span m=''3241810''>will</span> <span m=''3242580''>take</span> <span m=''3243630''>the</span>
  <span m=''3243830''>places</span> <span m=''3244320''>where</span> <span m=''3244420''>I</span>
  <span m=''3244500''>used</span> <span m=''3244650''>to</span> <span m=''3244810''>need</span>
  <span m=''3245020''>side</span> <span m=''3245280''>effects</span> <span m=''3245590''>and</span>
  <span m=''3245660''>objects</span> <span m=''3246730''>and</span> <span m=''3246880''>sort</span>
  <span m=''3247030''>of</span> <span m=''3247310''>hide</span> <span m=''3247900''>them</span>
  <span m=''3248050''>away</span> <span m=''3248360''>in</span> <span m=''3248470''>some</span>
  <span m=''3248630''>very</span> <span m=''3248950''>well-defined</span> <span m=''3249510''>modules</span>
  <span m=''3249940''>of</span> <span m=''3250020''>the</span> <span m=''3250100''>system</span>
  <span m=''3250830''>so</span> <span m=''3251020''>that</span> <span m=''3251160''>all</span>
  <span m=''3251290''>the</span> <span m=''3251360''>problems</span> <span m=''3251910''>of</span>
  <span m=''3253020''>assignment</span> <span m=''3253560''>don''t</span> <span m=''3253660''>sort</span>
  <span m=''3253830''>of</span> <span m=''3253920''>leak</span> <span m=''3254140''>out</span>
  <span m=''3254250''>all</span> <span m=''3254430''>over</span> <span m=''3254590''>the</span>
  <span m=''3254690''>system</span> <span m=''3255060''>but</span> <span m=''3255510''>are</span>
  <span m=''3255610''>captured</span> <span m=''3256090''>in</span> <span m=''3256210''>some</span>
  <span m=''3256420''>fairly</span> <span m=''3256760''>well-understood</span> <span
  m=''3257400''>things.</span> </p><p><span m=''3260780''>More</span> <span m=''3260940''>generally,</span>
  <span m=''3261830''>I</span> <span m=''3261970''>think</span> <span m=''3262110''>what</span>
  <span m=''3262220''>you''re</span> <span m=''3262340''>seeing</span> <span m=''3263140''>is</span>
  <span m=''3263290''>that we''re</span> <span m=''3263410''>running</span> <span
  m=''3263740''>across</span> <span m=''3264350''>what</span> <span m=''3264480''>I</span>
  <span m=''3264530''>think</span> <span m=''3264690''>is a</span> <span m=''3264800''>very</span>
  <span m=''3265060''>basic</span> <span m=''3265510''>problem</span> <span m=''3265860''>in</span>
  <span m=''3265960''>computer</span> <span m=''3266300''>science,</span> <span m=''3266950''>which</span>
  <span m=''3267160''>is</span> <span m=''3267250''>how</span> <span m=''3267480''>to</span>
  <span m=''3268490''>define</span> <span m=''3268850''>languages</span> <span m=''3269310''>that</span>
  <span m=''3269450''>somehow</span> <span m=''3270150''>can</span> <span m=''3270380''>talk</span>
  <span m=''3270680''>about</span> <span m=''3270860''>delayed</span> <span m=''3271340''>evaluation,</span>
  <span m=''3274140''>but</span> <span m=''3274320''>also</span> <span m=''3275920''>be</span>
  <span m=''3276110''>able</span> <span m=''3276240''>to</span> <span m=''3276310''>reflect</span>
  <span m=''3276700''>this</span> <span m=''3276820''>view</span> <span m=''3276980''>that</span>
  <span m=''3277130''>there are</span> <span m=''3277280''>objects</span> <span m=''3277690''>in</span>
  <span m=''3277770''>the</span> <span m=''3277840''>world.</span> <span m=''3278360''>How</span>
  <span m=''3278520''>do</span> <span m=''3278640''>we</span> <span m=''3279290''>somehow</span>
  <span m=''3279620''>get</span> <span m=''3279870''>both?</span> <span m=''3281230''>And</span>
  <span m=''3281820''>I</span> <span m=''3281950''>think</span> <span m=''3282140''>that''s</span>
  <span m=''3282280''>a</span> <span m=''3282330''>very</span> <span m=''3282490''>hard</span>
  <span m=''3282700''>problem.</span> <span m=''3283040''>And it</span> <span m=''3283200''>may</span>
  <span m=''3283370''>be</span> <span m=''3283740''>that</span> <span m=''3284250''>it''s</span>
  <span m=''3284390''>a</span> <span m=''3284460''>very</span> <span m=''3284710''>hard</span>
  <span m=''3284970''>problem</span> <span m=''3285480''>that</span> <span m=''3286030''>has</span>
  <span m=''3286420''>almost</span> <span m=''3286750''>nothing</span> <span m=''3287020''>to</span>
  <span m=''3287120''>do</span> <span m=''3287250''>with</span> <span m=''3287380''>computer</span>
  <span m=''3287770''>science,</span> <span m=''3288600''>that</span> <span m=''3288750''>it</span>
  <span m=''3288850''>really</span> <span m=''3289080''>is</span> <span m=''3289200''>a</span>
  <span m=''3289260''>problem</span> <span m=''3289660''>having</span> <span m=''3289930''>to</span>
  <span m=''3290020''>do</span> <span m=''3290120''>with</span> <span m=''3290250''>two</span>
  <span m=''3290670''>very</span> <span m=''3291070''>incompatible</span> <span m=''3291580''>ways</span>
  <span m=''3291830''>of</span> <span m=''3291950''>looking</span> <span m=''3292200''>at</span>
  <span m=''3292290''>the</span> <span m=''3292510''>world.</span> <span m=''3293840''>OK,</span>
  <span m=''3294210''>questions?</span> </p><p><span m=''3317556''>AUDIENCE: You mentioned</span>
  <span m=''3318052''>earlier</span> <span m=''3318550''>that</span> <span m=''3320140''>once</span>
  <span m=''3320450''>you introduce</span> <span m=''3320770''>assignment,</span>
  <span m=''3321570''>the</span> <span m=''3321640''>general</span> <span m=''3322080''>rule</span>
  <span m=''3323410''>for</span> <span m=''3323520''>using the</span> <span m=''3323930''>substitution</span>
  <span m=''3324430''>model</span> <span m=''3324890''>is</span> <span m=''3325280''>you</span>
  <span m=''3325370''>can''t.</span> <span m=''3325890''>Unless</span> <span m=''3326170''>you''re</span>
  <span m=''3326280''>very</span> <span m=''3326530''>careful,</span> <span m=''3326860''>you</span>
  <span m=''3327060''>can''t.</span> </p><p><span m=''3327570''>PROFESSOR: Right.</span>
  </p><p><span m=''3328260''>AUDIENCE: Is</span> <span m=''3328540''>there</span>
  <span m=''3328680''>a</span> <span m=''3328730''>set</span> <span m=''3328910''>of</span>
  <span m=''3329010''>techniques</span> <span m=''3330160''>or</span> <span m=''3330620''>a</span>
  <span m=''3330820''>set</span> <span m=''3331240''>of</span> <span m=''3332550''>guidelines</span>
  <span m=''3333310''>for</span> <span m=''3334330''>localizing</span> <span m=''3335080''>the
  effects</span> <span m=''3335580''>of</span> <span m=''3336010''>assignment</span>
  <span m=''3336440''>so</span> <span m=''3336690''>that</span> <span m=''3337030''>the</span>
  <span m=''3337140''>very</span> <span m=''3337370''>careful</span> <span m=''3337750''>becomes</span>
  <span m=''3338200''>defined?</span> </p><p><span m=''3340300''>PROFESSOR: I</span>
  <span m=''3340420''>don''t</span> <span m=''3340640''>know.</span> <span m=''3342890''>Let
  me</span> <span m=''3343130''>think.</span> <span m=''3345430''>Well,</span> <span
  m=''3345600''>certainly,</span> <span m=''3347000''>there</span> <span m=''3347130''>was</span>
  <span m=''3347270''>an</span> <span m=''3347350''>assignment</span> <span m=''3347740''>inside</span>
  <span m=''3348280''>memo</span> <span m=''3348580''>proc,</span> <span m=''3350150''>but</span>
  <span m=''3350310''>that</span> <span m=''3350470''>was</span> <span m=''3350690''>sort</span>
  <span m=''3350770''>of</span> <span m=''3351060''>hidden</span> <span m=''3351150''>away.</span>
  <span m=''3351480''>It</span> <span m=''3351600''>ended</span> <span m=''3351800''>up</span>
  <span m=''3351920''>not</span> <span m=''3352130''>making</span> <span m=''3352420''>any</span>
  <span m=''3352570''>difference.</span> <span m=''3353480''>Part</span> <span m=''3353610''>of</span>
  <span m=''3353730''>the</span> <span m=''3353800''>reason</span> <span m=''3354100''>for</span>
  <span m=''3354200''>that</span> <span m=''3354350''>is</span> <span m=''3354500''>once</span>
  <span m=''3355550''>this</span> <span m=''3355730''>thing</span> <span m=''3355910''>triggered</span>
  <span m=''3357190''>that it</span> <span m=''3357580''>had</span> <span m=''3357730''>run</span>
  <span m=''3357910''>and</span> <span m=''3358010''>gotten</span> <span m=''3358260''>an</span>
  <span m=''3358360''>answer,</span> <span m=''3358800''>that</span> <span m=''3358990''>answer</span>
  <span m=''3359260''>will</span> <span m=''3359370''>never</span> <span m=''3359600''>change.</span>
  <span m=''3360390''>So</span> <span m=''3360670''>that</span> <span m=''3360870''>was</span>
  <span m=''3360960''>sort</span> <span m=''3361070''>of</span> <span m=''3361170''>a</span>
  <span m=''3361210''>one-time</span> <span m=''3361810''>assignment.</span> <span
  m=''3362080''>So</span> <span m=''3362350''>one</span> <span m=''3362600''>very</span>
  <span m=''3362830''>general</span> <span m=''3363190''>thing</span> <span m=''3363340''>you</span>
  <span m=''3363480''>can</span> <span m=''3363620''>do</span> <span m=''3364310''>is</span>
  <span m=''3364550''>if</span> <span m=''3364640''>you</span> <span m=''3364760''>only</span>
  <span m=''3364920''>do</span> <span m=''3365020''>what''s</span> <span m=''3365180''>called
  a</span> <span m=''3365350''>one-time</span> <span m=''3365870''>assignment</span>
  <span m=''3367675''>and</span> <span m=''3368090''>never</span> <span m=''3368330''>change</span>
  <span m=''3368750''>anything,</span> <span m=''3369640''>then</span> <span m=''3369790''>you</span>
  <span m=''3369870''>can</span> <span m=''3370000''>do</span> <span m=''3370150''>better.</span>
  </p><p><span m=''3371250''>One</span> <span m=''3371420''>of</span> <span m=''3371500''>the</span>
  <span m=''3371990''>problems</span> <span m=''3372570''>in</span> <span m=''3372770''>this</span>
  <span m=''3372970''>merge</span> <span m=''3373680''>thing,</span> <span m=''3374610''>people</span>
  <span m=''3374960''>have--</span> <span m=''3377156''>let me see if</span> <span
  m=''3377640''>this</span> <span m=''3377840''>is</span> <span m=''3377960''>right.</span>
  <span m=''3378490''>I</span> <span m=''3378680''>think</span> <span m=''3379140''>it''s</span>
  <span m=''3379390''>true</span> <span m=''3380160''>that</span> <span m=''3380390''>with</span>
  <span m=''3380630''>fair</span> <span m=''3380910''>merge,</span> <span m=''3382280''>with</span>
  <span m=''3382430''>just</span> <span m=''3382690''>fair</span> <span m=''3382910''>merge,</span>
  <span m=''3383180''>you</span> <span m=''3383270''>can</span> <span m=''3383410''>begin</span>
  <span m=''3384490''>effectively</span> <span m=''3385110''>simulating</span> <span
  m=''3387060''>assignment</span> <span m=''3387800''>in</span> <span m=''3387900''>the</span>
  <span m=''3388000''>rest</span> <span m=''3388240''>of</span> <span m=''3388310''>the</span>
  <span m=''3388570''>language.</span> <span m=''3390820''>It</span> <span m=''3391000''>seems</span>
  <span m=''3391220''>like</span> <span m=''3391450''>anything</span> <span m=''3391980''>you</span>
  <span m=''3392070''>do</span> <span m=''3392450''>to</span> <span m=''3392670''>go</span>
  <span m=''3392820''>outside--</span> <span m=''3393630''>I''m</span> <span m=''3393840''>not</span>
  <span m=''3394050''>quite</span> <span m=''3394330''>sure</span> <span m=''3394490''>that''s</span>
  <span m=''3394710''>true</span> <span m=''3394860''>for</span> <span m=''3395000''>fair</span>
  <span m=''3395275''>merge,</span> <span m=''3395550''>but</span> <span m=''3395690''>it''s</span>
  <span m=''3395830''>true</span> <span m=''3396440''>of</span> <span m=''3396680''>a</span>
  <span m=''3396810''>little</span> <span m=''3397070''>bit</span> <span m=''3397220''>more</span>
  <span m=''3397370''>general</span> <span m=''3397670''>things</span> <span m=''3398330''>that</span>
  <span m=''3398500''>people</span> <span m=''3398740''>have</span> <span m=''3398840''>been</span>
  <span m=''3398950''>doing.</span> <span m=''3399520''>So</span> <span m=''3399700''>it</span>
  <span m=''3399790''>might</span> <span m=''3399990''>be</span> <span m=''3400100''>that</span>
  <span m=''3400230''>any</span> <span m=''3400430''>little</span> <span m=''3400630''>bit</span>
  <span m=''3400830''>you</span> <span m=''3400960''>put</span> <span m=''3401140''>in,</span>
  <span m=''3401530''>suddenly</span> <span m=''3402490''>if</span> <span m=''3402630''>they</span>
  <span m=''3402710''>allow</span> <span m=''3402980''>you</span> <span m=''3403080''>to</span>
  <span m=''3403150''>build</span> <span m=''3403370''>arbitrary</span> <span m=''3403840''>stuff,</span>
  <span m=''3404150''>it''s</span> <span m=''3404290''>almost</span> <span m=''3404610''>as</span>
  <span m=''3404690''>bad</span> <span m=''3404910''>as</span> <span m=''3405000''>having</span>
  <span m=''3405280''>assignment</span> <span m=''3405850''>altogether.</span> <span
  m=''3407970''>But</span> <span m=''3408280''>that''s</span> <span m=''3409110''>an</span>
  <span m=''3409200''>area</span> <span m=''3409460''>that</span> <span m=''3409590''>people</span>
  <span m=''3409850''>are</span> <span m=''3409900''>thinking</span> <span m=''3410200''>about
  now.</span> </p><p><span m=''3411590''>AUDIENCE: I guess</span> <span m=''3412040''>I</span>
  <span m=''3412060''>don''t</span> <span m=''3412290''>see</span> <span m=''3412420''>the</span>
  <span m=''3412540''>problem</span> <span m=''3413240''>here</span> <span m=''3413460''>with</span>
  <span m=''3413700''>merge</span> <span m=''3414840''>if</span> <span m=''3417010''>I</span>
  <span m=''3417080''>call</span> <span m=''3417420''>Bill,</span> <span m=''3417680''>if</span>
  <span m=''3417940''>Bill is a</span> <span m=''3418380''>procedure,</span> <span
  m=''3419510''>then</span> <span m=''3420130''>Bill</span> <span m=''3420550''>is</span>
  <span m=''3420680''>going</span> <span m=''3420930''>to</span> <span m=''3421070''>increment</span>
  <span m=''3421510''>the</span> <span m=''3421760''>bank</span> <span m=''3422040''>account</span>
  <span m=''3422390''>or</span> <span m=''3422580''>build</span> <span m=''3423100''>the</span>
  <span m=''3423180''>list</span> <span m=''3423570''>that ''s</span> <span m=''3423690''>going</span>
  <span m=''3423770''>to</span> <span m=''3423850''>put</span> <span m=''3424010''>in</span>
  <span m=''3424120''>the</span> <span m=''3424170''>next</span> <span m=''3424430''>element.</span>
  <span m=''3424730''>If</span> <span m=''3424840''>I</span> <span m=''3424940''>call</span>
  <span m=''3425210''>Dave</span> <span m=''3425400''>twice</span> <span m=''3425780''>in</span>
  <span m=''3425850''>a</span> <span m=''3425900''>row,</span> <span m=''3426110''>that</span>
  <span m=''3426300''>will</span> <span m=''3426410''>do</span> <span m=''3426560''>that.</span>
  <span m=''3427170''>I''m</span> <span m=''3427240''>not</span> <span m=''3427420''>sure</span>
  <span m=''3427590''>where</span> <span m=''3427790''>fair</span> <span m=''3428100''>merge</span>
  <span m=''3428440''>has</span> <span m=''3428660''>to</span> <span m=''3428750''>be</span>
  <span m=''3428920''>involved.</span> </p><p><span m=''3429350''>PROFESSOR: The problem
  is</span> <span m=''3429740''>imagine</span> <span m=''3430150''>these</span> <span
  m=''3430350''>really</span> <span m=''3430650''>as</span> <span m=''3430770''>people.</span>
  <span m=''3431200''>See,</span> <span m=''3431360''>here</span> <span m=''3431610''>I</span>
  <span m=''3431740''>have</span> <span m=''3431860''>the</span> <span m=''3431910''>user</span>
  <span m=''3432290''>who''s</span> <span m=''3432790''>interacting</span> <span m=''3433240''>with</span>
  <span m=''3433360''>this</span> <span m=''3433490''>bank</span> <span m=''3433750''>account.</span>
  <span m=''3434850''>Put in</span> <span m=''3434960''>a</span> <span m=''3435170''>request,</span>
  <span m=''3435590''>get an</span> <span m=''3435680''>answer.</span> <span m=''3435960''>Put
  in a</span> <span m=''3436150''>request,</span> <span m=''3436490''>get an</span>
  <span m=''3436680''>answer.</span> </p><p><span m=''3437070''>AUDIENCE: Right.</span>
  </p><p><span m=''3438200''>PROFESSOR: But</span> <span m=''3438820''>if</span> <span
  m=''3439040''>the</span> <span m=''3439190''>only</span> <span m=''3439380''>way</span>
  <span m=''3439520''>I</span> <span m=''3439610''>can</span> <span m=''3439750''>process</span>
  <span m=''3440170''>request</span> <span m=''3440660''>is</span> <span m=''3440750''>to</span>
  <span m=''3440860''>alternate</span> <span m=''3441370''>them</span> <span m=''3441500''>from</span>
  <span m=''3441670''>two</span> <span m=''3441830''>people--</span> </p><p><span
  m=''3442290''>AUDIENCE: Well,</span> <span m=''3442746''>why would</span> <span
  m=''3443202''>you</span> <span m=''3443660''>alternate</span> <span m=''3443940''>them?</span>
  </p><p><span m=''3444220''>PROFESSOR: Why</span> <span m=''3444470''>don''t</span>
  <span m=''3444600''>I?</span> </p><p><span m=''3445070''>AUDIENCE: Yes.</span> <span
  m=''3446140''>Why</span> <span m=''3446260''>do</span> <span m=''3446420''>you?</span>
  </p><p><span m=''3446580''>PROFESSOR: Think</span> <span m=''3446720''>of</span>
  <span m=''3446800''>them</span> <span m=''3446880''>as</span> <span m=''3446980''>real</span>
  <span m=''3447160''>people,</span> <span m=''3447470''>right?</span> <span m=''3447640''>This</span>
  <span m=''3447770''>guy</span> <span m=''3447840''>might</span> <span m=''3448040''>go</span>
  <span m=''3448160''>away</span> <span m=''3448390''>for</span> <span m=''3448580''>a</span>
  <span m=''3448760''>year.</span> <span m=''3449280''>And</span> <span m=''3449410''>you''re</span>
  <span m=''3450360''>sitting</span> <span m=''3450610''>here</span> <span m=''3450770''>at</span>
  <span m=''3450830''>the</span> <span m=''3450910''>bank</span> <span m=''3451160''>account</span>
  <span m=''3451610''>window,</span> <span m=''3452470''>and</span> <span m=''3452600''>you</span>
  <span m=''3452700''>can''t</span> <span m=''3452930''>put</span> <span m=''3453080''>in
  two</span> <span m=''3453330''>requests</span> <span m=''3453800''>because</span>
  <span m=''3453900''>it''s</span> <span m=''3454040''>waiting</span> <span m=''3454330''>for</span>
  <span m=''3454450''>this</span> <span m=''3454670''>guy.</span> </p><p><span m=''3455480''>AUDIENCE:
  Why</span> <span m=''3455640''>does</span> <span m=''3455810''>it</span> <span m=''3455880''>have</span>
  <span m=''3455990''>to</span> <span m=''3456100''>be</span> <span m=''3456200''>waiting</span>
  <span m=''3456610''>for</span> <span m=''3456740''>one?</span> </p><p><span m=''3457380''>PROFESSOR:
  Because</span> <span m=''3457870''>it''s</span> <span m=''3457990''>trying</span>
  <span m=''3458160''>to</span> <span m=''3458340''>compute a</span> <span m=''3458690''>function.</span>
  <span m=''3459110''>I</span> <span m=''3459180''>have</span> <span m=''3459330''>to</span>
  <span m=''3459420''>define</span> <span m=''3460370''>a</span> <span m=''3460440''>function.</span>
  <span m=''3461720''>Another</span> <span m=''3461930''>way</span> <span m=''3462030''>to</span>
  <span m=''3462120''>say</span> <span m=''3462390''>that</span> <span m=''3462810''>is</span>
  <span m=''3462970''>the</span> <span m=''3463110''>answer</span> <span m=''3463470''>to</span>
  <span m=''3463550''>what</span> <span m=''3463710''>comes</span> <span m=''3463960''>out</span>
  <span m=''3464100''>of</span> <span m=''3464210''>this</span> <span m=''3464320''>merge</span>
  <span m=''3464670''>box</span> <span m=''3466260''>is</span> <span m=''3466450''>not</span>
  <span m=''3467480''>a</span> <span m=''3467590''>function</span> <span m=''3468160''>of</span>
  <span m=''3468690''>what</span> <span m=''3468880''>goes</span> <span m=''3469130''>in.</span>
  <span m=''3471690''>Because,</span> <span m=''3472210''>see,</span> <span m=''3472390''>what</span>
  <span m=''3472770''>would</span> <span m=''3472890''>the</span> <span m=''3472960''>function</span>
  <span m=''3473360''>be?</span> <span m=''3473490''>Suppose</span> <span m=''3475950''>he</span>
  <span m=''3476110''>puts</span> <span m=''3476340''>in</span> <span m=''3476500''>1,</span>
  <span m=''3477290''>1,</span> <span m=''3477880''>1,</span> <span m=''3478350''>1,</span>
  <span m=''3479820''>and</span> <span m=''3479960''>he</span> <span m=''3480090''>puts
  in</span> <span m=''3480300''>2,</span> <span m=''3481160''>2,</span> <span m=''3481870''>2,</span>
  <span m=''3482420''>2.</span> <span m=''3483470''>What''s</span> <span m=''3483610''>the</span>
  <span m=''3483750''>answer</span> <span m=''3484070''>supposed</span> <span m=''3484430''>to
  be?</span> <span m=''3485910''>It''s</span> <span m=''3486140''>not</span> <span
  m=''3486380''>good</span> <span m=''3486530''>enough</span> <span m=''3486720''>to</span>
  <span m=''3486810''>say</span> <span m=''3486960''>it''s</span> <span m=''3487110''>1,</span>
  <span m=''3487380''>2,</span> <span m=''3487640''>1,</span> <span m=''3487880''>2,</span>
  <span m=''3488170''>1,</span> <span m=''3488400''>2.</span> </p><p><span m=''3488740''>AUDIENCE:
  I understand.</span> <span m=''3489390''>But</span> <span m=''3489670''>when</span>
  <span m=''3489830''>Bill</span> <span m=''3490060''>puts in</span> <span m=''3490380''>1,</span>
  <span m=''3490700''>1</span> <span m=''3490920''>goes</span> <span m=''3491190''>in.</span>
  <span m=''3491560''>When Dave</span> <span m=''3491870''>puts</span> <span m=''3492140''>in
  2</span> <span m=''3492430''>twice,</span> <span m=''3492850''>2</span> <span m=''3493130''>goes</span>
  <span m=''3493370''>in</span> <span m=''3493500''>twice.</span> <span m=''3493950''>When</span>
  <span m=''3494130''>Bill</span> <span m=''3494380''>puts in--</span> </p><p><span
  m=''3495090''>PROFESSOR: Right.</span> </p><p><span m=''3495450''>AUDIENCE: Why</span>
  <span m=''3495630''>can''t it</span> <span m=''3495960''>be</span> <span m=''3496800''>hooked</span>
  <span m=''3497020''>to</span> <span m=''3497140''>the</span> <span m=''3497260''>time</span>
  <span m=''3497670''>of</span> <span m=''3497840''>the</span> <span m=''3497990''>input--</span>
  <span m=''3498680''>the</span> <span m=''3498800''>actual</span> <span m=''3499240''>procedural--</span>
  </p><p><span m=''3500100''>PROFESSOR: Because</span> <span m=''3500340''>I</span>
  <span m=''3500600''>don''t</span> <span m=''3500880''>have</span> <span m=''3501380''>time.</span>
  <span m=''3503980''>See,</span> <span m=''3504150''>all</span> <span m=''3504370''>I</span>
  <span m=''3504440''>can</span> <span m=''3504600''>say</span> <span m=''3504960''>is</span>
  <span m=''3505120''>I''m</span> <span m=''3505260''>going</span> <span m=''3505330''>to</span>
  <span m=''3506200''>define</span> <span m=''3506500''>a</span> <span m=''3506550''>function.</span>
  <span m=''3506900''>I</span> <span m=''3507000''>don''t</span> <span m=''3507310''>have</span>
  <span m=''3507580''>time.</span> <span m=''3512070''>There''s</span> <span m=''3512250''>no</span>
  <span m=''3512370''>concept</span> <span m=''3512850''>if</span> <span m=''3512960''>it''s</span>
  <span m=''3513110''>going</span> <span m=''3513220''>to</span> <span m=''3513740''>alternate,</span>
  <span m=''3514260''>except</span> <span m=''3514580''>if</span> <span m=''3514690''>nobody''s</span>
  <span m=''3515100''>there,</span> <span m=''3515320''>it''s</span> <span m=''3515450''>going</span>
  <span m=''3515530''>to</span> <span m=''3515610''>wait</span> <span m=''3515800''>a</span>
  <span m=''3515840''>while</span> <span m=''3516110''>for</span> <span m=''3516250''>him.</span>
  <span m=''3518420''>It''s</span> <span m=''3518670''>just</span> <span m=''3518880''>going</span>
  <span m=''3518950''>to</span> <span m=''3519020''>say</span> <span m=''3519610''>I</span>
  <span m=''3519840''>have</span> <span m=''3520080''>the</span> <span m=''3520240''>stream</span>
  <span m=''3520620''>of</span> <span m=''3520720''>requests,</span> <span m=''3521660''>the</span>
  <span m=''3521910''>timeless</span> <span m=''3522500''>infinite</span> <span m=''3522950''>streams</span>
  <span m=''3523390''>of</span> <span m=''3523510''>all</span> <span m=''3523710''>the</span>
  <span m=''3523790''>requests</span> <span m=''3524190''>that</span> <span m=''3524340''>Dave</span>
  <span m=''3524580''>would</span> <span m=''3524750''>have</span> <span m=''3524920''>made,</span>
  <span m=''3527600''>right?</span> <span m=''3527810''>And</span> <span m=''3527920''>the</span>
  <span m=''3528010''>timeless</span> <span m=''3528450''>infinite</span> <span m=''3528770''>stream</span>
  <span m=''3529050''>of</span> <span m=''3529170''>all</span> <span m=''3529280''>the</span>
  <span m=''3529340''>requests</span> <span m=''3529710''>Bill</span> <span m=''3529890''>would</span>
  <span m=''3530030''>have made,</span> <span m=''3530310''>and</span> <span m=''3530590''>I</span>
  <span m=''3530700''>want</span> <span m=''3530780''>to</span> <span m=''3530870''>operate</span>
  <span m=''3531310''>on</span> <span m=''3531470''>them.</span> <span m=''3531690''>See,</span>
  <span m=''3531850''>that''s</span> <span m=''3532060''>how</span> <span m=''3532200''>this</span>
  <span m=''3532480''>bank</span> <span m=''3532740''>account</span> <span m=''3533060''>is</span>
  <span m=''3533180''>working.</span> </p><p><span m=''3536710''>And</span> <span
  m=''3536820''>the</span> <span m=''3536940''>problem</span> <span m=''3537390''>is</span>
  <span m=''3537600''>that</span> <span m=''3537760''>these</span> <span m=''3537960''>poor</span>
  <span m=''3538130''>people</span> <span m=''3538550''>who</span> <span m=''3538640''>are</span>
  <span m=''3538770''>sitting</span> <span m=''3539040''>at</span> <span m=''3539120''>the</span>
  <span m=''3539180''>bank</span> <span m=''3539450''>account</span> <span m=''3540340''>windows</span>
  <span m=''3540800''>have</span> <span m=''3541460''>the</span> <span m=''3542180''>misfortune</span>
  <span m=''3542760''>to</span> <span m=''3542890''>exist</span> <span m=''3543250''>in</span>
  <span m=''3543390''>time.</span> <span m=''3545340''>They</span> <span m=''3545450''>don''t</span>
  <span m=''3545730''>see</span> <span m=''3545910''>their</span> <span m=''3546120''>infinite</span>
  <span m=''3546470''>stream</span> <span m=''3547700''>of</span> <span m=''3547870''>all</span>
  <span m=''3548020''>the</span> <span m=''3548090''>requests</span> <span m=''3548490''>they</span>
  <span m=''3548600''>would</span> <span m=''3548720''>have</span> <span m=''3548850''>ever</span>
  <span m=''3549040''>made.</span> <span m=''3550070''>They''re</span> <span m=''3550220''>waiting</span>
  <span m=''3550520''>now,</span> <span m=''3550750''>and</span> <span m=''3550840''>they</span>
  <span m=''3550920''>want</span> <span m=''3551120''>an</span> <span m=''3551210''>answer.</span>
  <span m=''3554290''>So</span> <span m=''3554980''>if</span> <span m=''3555060''>you''re</span>
  <span m=''3555170''>sitting</span> <span m=''3555470''>there--</span> <span m=''3556340''>if</span>
  <span m=''3556560''>this</span> <span m=''3556730''>is</span> <span m=''3556860''>the</span>
  <span m=''3558700''>screen</span> <span m=''3559020''>operation</span> <span m=''3559550''>on</span>
  <span m=''3559650''>some</span> <span m=''3559820''>time-sharing</span> <span m=''3560360''>system</span>
  <span m=''3561630''>and</span> <span m=''3561770''>it''s</span> <span m=''3561910''>working</span>
  <span m=''3562220''>functionally,</span> <span m=''3562660''>you</span> <span m=''3562750''>want</span>
  <span m=''3562840''>an</span> <span m=''3562940''>answer</span> <span m=''3563270''>then</span>
  <span m=''3563410''>when</span> <span m=''3563540''>you</span> <span m=''3563630''>talk</span>
  <span m=''3563850''>the</span> <span m=''3563940''>character.</span> <span m=''3565290''>You</span>
  <span m=''3565370''>don''t</span> <span m=''3565530''>want</span> <span m=''3565680''>it
  to</span> <span m=''3565800''>have</span> <span m=''3565930''>to</span> <span m=''3566030''>wait</span>
  <span m=''3566270''>for</span> <span m=''3566380''>everybody in</span> <span m=''3566860''>the</span>
  <span m=''3566940''>whole</span> <span m=''3567090''>system</span> <span m=''3567410''>to</span>
  <span m=''3567510''>have</span> <span m=''3567600''>typed</span> <span m=''3567850''>one</span>
  <span m=''3568000''>character</span> <span m=''3568400''>before</span> <span m=''3568690''>it</span>
  <span m=''3568760''>can</span> <span m=''3568860''>get</span> <span m=''3568990''>around</span>
  <span m=''3569230''>to</span> <span m=''3569310''>service</span> <span m=''3569670''>you.</span>
  <span m=''3570910''>So</span> <span m=''3571060''>that''s</span> <span m=''3571260''>the</span>
  <span m=''3571330''>problem.</span> <span m=''3573890''>I</span> <span m=''3574100''>mean,</span>
  <span m=''3574310''>the</span> <span m=''3574450''>fact</span> <span m=''3574700''>that</span>
  <span m=''3574830''>people</span> <span m=''3575080''>live</span> <span m=''3575240''>in</span>
  <span m=''3575360''>time,</span> <span m=''3575790''>apparently.</span> <span m=''3576850''>If</span>
  <span m=''3577330''>they</span> <span m=''3577470''>didn''t,</span> <span m=''3577790''>it</span>
  <span m=''3577930''>wouldn''t</span> <span m=''3578070''>be</span> <span m=''3578170''>a</span>
  <span m=''3578220''>problem.</span> </p><p><span m=''3589100''>AUDIENCE: I''m</span>
  <span m=''3589280''>afraid</span> <span m=''3589600''>I</span> <span m=''3589640''>miss</span>
  <span m=''3589950''>the</span> <span m=''3590060''>point</span> <span m=''3590400''>of</span>
  <span m=''3591030''>having</span> <span m=''3591410''>no</span> <span m=''3591600''>time</span>
  <span m=''3592040''>in</span> <span m=''3592240''>this</span> <span m=''3592660''>banking</span>
  <span m=''3593380''>transaction.</span> <span m=''3594740''>Isn''t time</span> <span
  m=''3595480''>very</span> <span m=''3595880''>important?</span> <span m=''3596880''>For
  instance,</span> <span m=''3597640''>the</span> <span m=''3597840''>sequence</span>
  <span m=''3598320''>of</span> <span m=''3598510''>events.</span> <span m=''3600790''>If</span>
  <span m=''3601220''>Dave</span> <span m=''3602790''>take</span> <span m=''3603090''>out</span>
  <span m=''3603390''>$100,</span> <span m=''3604160''>then</span> <span m=''3606770''>the</span>
  <span m=''3606900''>timing</span> <span m=''3607150''>sequence</span> <span m=''3607620''>should
  be</span> <span m=''3608000''>important.</span> <span m=''3608400''>How</span> <span
  m=''3608580''>do</span> <span m=''3608680''>you</span> <span m=''3608790''>treat</span>
  <span m=''3609450''>transactions</span> <span m=''3609890''>as</span> <span m=''3610310''>streams?</span>
  </p><p><span m=''3611260''>PROFESSOR: Well,</span> <span m=''3611790''>that''s</span>
  <span m=''3612050''>the</span> <span m=''3612910''>thing</span> <span m=''3613070''>I''m</span>
  <span m=''3613670''>saying.</span> <span m=''3614260''>This</span> <span m=''3614430''>is</span>
  <span m=''3614530''>an</span> <span m=''3614590''>example</span> <span m=''3614970''>where</span>
  <span m=''3615090''>you</span> <span m=''3615220''>can''t.</span> <span m=''3617510''>You</span>
  <span m=''3617720''>can''t.</span> <span m=''3618610''>The</span> <span m=''3618860''>point</span>
  <span m=''3619000''>is</span> <span m=''3619110''>what</span> <span m=''3619280''>comes</span>
  <span m=''3619540''>out</span> <span m=''3619710''>of</span> <span m=''3619800''>here</span>
  <span m=''3620340''>is</span> <span m=''3620480''>simply</span> <span m=''3620750''>not</span>
  <span m=''3620960''>a</span> <span m=''3621010''>function</span> <span m=''3621410''>of</span>
  <span m=''3621490''>the</span> <span m=''3621560''>stream</span> <span m=''3621860''>going</span>
  <span m=''3622170''>in</span> <span m=''3622250''>here</span> <span m=''3622450''>and</span>
  <span m=''3622510''>the</span> <span m=''3622570''>stream</span> <span m=''3622830''>going</span>
  <span m=''3623100''>in</span> <span m=''3623190''>here.</span> <span m=''3624170''>It''s</span>
  <span m=''3624350''>a</span> <span m=''3624400''>function</span> <span m=''3624750''>of</span>
  <span m=''3624820''>the</span> <span m=''3624900''>stream</span> <span m=''3625210''>going</span>
  <span m=''3625500''>in</span> <span m=''3625610''>here</span> <span m=''3626230''>and</span>
  <span m=''3626320''>the</span> <span m=''3626420''>stream</span> <span m=''3626660''>going</span>
  <span m=''3626910''>in</span> <span m=''3627000''>here</span> <span m=''3627180''>and</span>
  <span m=''3627280''>some</span> <span m=''3627510''>kind</span> <span m=''3627720''>of</span>
  <span m=''3627800''>information</span> <span m=''3628340''>about</span> <span m=''3628610''>time,</span>
  <span m=''3629360''>which</span> <span m=''3629670''>is</span> <span m=''3629780''>precisely</span>
  <span m=''3630340''>what</span> <span m=''3630480''>a</span> <span m=''3630540''>normal-order</span>
  <span m=''3631050''>language</span> <span m=''3631420''>won''t let</span> <span
  m=''3631800''>you</span> <span m=''3631870''>say.</span> </p><p><span m=''3634810''>AUDIENCE:
  In order to</span> <span m=''3635160''>brings</span> <span m=''3635370''>this</span>
  <span m=''3635540''>back</span> <span m=''3635850''>into</span> <span m=''3636680''>a</span>
  <span m=''3636770''>more</span> <span m=''3636950''>functional</span> <span m=''3637380''>perspective,</span>
  <span m=''3638510''>could</span> <span m=''3638720''>we</span> <span m=''3639220''>just</span>
  <span m=''3639510''>explicitly</span> <span m=''3640040''>time</span> <span m=''3640310''>stamp
  all the</span> <span m=''3640810''>inputs</span> <span m=''3641250''>from</span>
  <span m=''3641330''>Bill</span> <span m=''3641590''>and</span> <span m=''3641690''>Dave</span>
  <span m=''3642600''>and</span> <span m=''3643340''>define</span> <span m=''3643740''>fair</span>
  <span m=''3643990''>merge to</span> <span m=''3644390''>just</span> <span m=''3644600''>be
  the</span> <span m=''3644760''>sort</span> <span m=''3645200''>on</span> <span m=''3645390''>those</span>
  <span m=''3645650''>time</span> <span m=''3645920''>stamps?</span> </p><p><span
  m=''3649150''>PROFESSOR: Yeah, you can do that.</span> <span m=''3649550''>You</span>
  <span m=''3649680''>can</span> <span m=''3649790''>do</span> <span m=''3649910''>that</span>
  <span m=''3650140''>sort</span> <span m=''3650280''>of</span> <span m=''3650430''>thing.</span>
  <span m=''3650600''>Another</span> <span m=''3650910''>thing</span> <span m=''3651110''>you</span>
  <span m=''3651230''>could</span> <span m=''3651350''>say</span> <span m=''3651710''>is</span>
  <span m=''3651860''>imagine</span> <span m=''3652420''>that</span> <span m=''3653200''>really</span>
  <span m=''3653480''>what</span> <span m=''3653640''>this</span> <span m=''3653830''>function</span>
  <span m=''3654190''>is,</span> <span m=''3654770''>is</span> <span m=''3654960''>that</span>
  <span m=''3655110''>it</span> <span m=''3655240''>does</span> <span m=''3655440''>a</span>
  <span m=''3655530''>read</span> <span m=''3655800''>every</span> <span m=''3656020''>microsecond,</span>
  <span m=''3658900''>and</span> <span m=''3659070''>then</span> <span m=''3659200''>if</span>
  <span m=''3659290''>there''s</span> <span m=''3659480''>none</span> <span m=''3659710''>there,</span>
  <span m=''3659880''>that''s</span> <span m=''3660110''>considered</span> <span m=''3660490''>an</span>
  <span m=''3660590''>empty</span> <span m=''3660830''>one.</span> <span m=''3660970''>That''s</span>
  <span m=''3661120''>about</span> <span m=''3661360''>equivalent</span> <span m=''3662290''>to</span>
  <span m=''3662710''>what</span> <span m=''3662930''>you</span> <span m=''3663040''>said.</span>
  <span m=''3663610''>And</span> <span m=''3663790''>yes,</span> <span m=''3664310''>you</span>
  <span m=''3664410''>can</span> <span m=''3664570''>do</span> <span m=''3664750''>that,</span>
  <span m=''3665140''>but</span> <span m=''3665250''>that''s</span> <span m=''3665480''>a</span>
  <span m=''3665530''>clg.</span> <span m=''3667110''>So</span> <span m=''3667550''>it''s</span>
  <span m=''3667650''>not</span> <span m=''3667790''>quite</span> <span m=''3668060''>only</span>
  <span m=''3668720''>implementation</span> <span m=''3669480''>we''re</span> <span
  m=''3669600''>worried</span> <span m=''3669930''>about.</span> <span m=''3670170''>We''re</span>
  <span m=''3670740''>worried</span> <span m=''3671090''>about</span> <span m=''3671290''>expressive</span>
  <span m=''3671780''>power</span> <span m=''3672140''>in</span> <span m=''3672210''>the</span>
  <span m=''3672280''>language,</span> <span m=''3672730''>and what</span> <span m=''3672930''>we''re</span>
  <span m=''3673060''>running</span> <span m=''3673330''>across</span> <span m=''3673670''>is</span>
  <span m=''3673790''>a</span> <span m=''3673970''>real</span> <span m=''3674140''>mismatch</span>
  <span m=''3675060''>between</span> <span m=''3675370''>what</span> <span m=''3675520''>we</span>
  <span m=''3675630''>can</span> <span m=''3675780''>say</span> <span m=''3676010''>easily</span>
  <span m=''3676390''>and</span> <span m=''3676490''>what</span> <span m=''3676620''>we''d</span>
  <span m=''3676760''>like</span> <span m=''3676970''>to</span> <span m=''3677070''>say.</span>
  </p><p><span m=''3678824''>AUDIENCE: It</span> <span m=''3679322''>sounds like</span>
  <span m=''3679820''>where we''re</span> <span m=''3680085''>getting</span> <span
  m=''3680350''>hung</span> <span m=''3680550''>up</span> <span m=''3680680''>with</span>
  <span m=''3680790''>that</span> <span m=''3681060''>is</span> <span m=''3681290''>the</span>
  <span m=''3681570''>fact it</span> <span m=''3681630''>expects</span> <span m=''3682040''>one</span>
  <span m=''3682340''>input</span> <span m=''3682550''>from</span> <span m=''3682850''>both</span>
  <span m=''3683140''>Bill and</span> <span m=''3683480''>Dave</span> <span m=''3683745''>at</span>
  <span m=''3684010''>the</span> <span m=''3684280''>same</span> <span m=''3684700''>time.</span>
  </p><p><span m=''3686080''>PROFESSOR: It''s</span> <span m=''3686270''>not</span>
  <span m=''3686480''>quite</span> <span m=''3686770''>one,</span> <span m=''3687090''>but</span>
  <span m=''3687200''>it''s</span> <span m=''3687340''>anything</span> <span m=''3687780''>you</span>
  <span m=''3687910''>define.</span> <span m=''3688530''>So</span> <span m=''3688680''>you</span>
  <span m=''3688800''>can</span> <span m=''3688920''>say</span> <span m=''3689090''>Dave</span>
  <span m=''3689420''>can</span> <span m=''3689600''>go</span> <span m=''3689730''>twice</span>
  <span m=''3690070''>as</span> <span m=''3690160''>often,</span> <span m=''3690510''>but
  if</span> <span m=''3691000''>anything</span> <span m=''3691450''>you</span> <span
  m=''3691610''>predefine,</span> <span m=''3692800''>it''s</span> <span m=''3692930''>not</span>
  <span m=''3693150''>the</span> <span m=''3693240''>right</span> <span m=''3693490''>thing.</span>
  <span m=''3696110''>You</span> <span m=''3696290''>can''t</span> <span m=''3696710''>decide</span>
  <span m=''3697170''>at</span> <span m=''3697280''>some</span> <span m=''3697520''>particular</span>
  <span m=''3698650''>function</span> <span m=''3699080''>of</span> <span m=''3699200''>their</span>
  <span m=''3699880''>input</span> <span m=''3700190''>requests.</span> <span m=''3701930''>Worse</span>
  <span m=''3702200''>yet,</span> <span m=''3702560''>I</span> <span m=''3702640''>mean,</span>
  <span m=''3702790''>worse</span> <span m=''3703040''>yet,</span> <span m=''3704180''>there
  are</span> <span m=''3704510''>things that</span> <span m=''3704670''>even</span>
  <span m=''3704870''>merge</span> <span m=''3705190''>can''t</span> <span m=''3705430''>do.</span>
  <span m=''3707290''>One</span> <span m=''3707450''>thing</span> <span m=''3707590''>you</span>
  <span m=''3707690''>might</span> <span m=''3707860''>want</span> <span m=''3707940''>to</span>
  <span m=''3708020''>do</span> <span m=''3708120''>that''s</span> <span m=''3708280''>even</span>
  <span m=''3708490''>more</span> <span m=''3708720''>general is</span> <span m=''3709170''>suddenly</span>
  <span m=''3710260''>you</span> <span m=''3710610''>add</span> <span m=''3710850''>somebody</span>
  <span m=''3711210''>else</span> <span m=''3711370''>to</span> <span m=''3711470''>this</span>
  <span m=''3711620''>bank</span> <span m=''3711870''>account</span> <span m=''3712190''>system.</span>
  <span m=''3712470''>You go</span> <span m=''3712700''>and you</span> <span m=''3712820''>add</span>
  <span m=''3713080''>John</span> <span m=''3713310''>to</span> <span m=''3713400''>this</span>
  <span m=''3713550''>bank</span> <span m=''3713800''>account</span> <span m=''3714070''>system.</span>
  <span m=''3716030''>And</span> <span m=''3716180''>now</span> <span m=''3716610''>there''s</span>
  <span m=''3717010''>yet</span> <span m=''3717160''>another</span> <span m=''3717480''>stream</span>
  <span m=''3717750''>that''s</span> <span m=''3717920''>going</span> <span m=''3717990''>to</span>
  <span m=''3718060''>come</span> <span m=''3718250''>into</span> <span m=''3718370''>the</span>
  <span m=''3718490''>picture</span> <span m=''3718840''>at</span> <span m=''3718930''>some</span>
  <span m=''3719120''>time</span> <span m=''3719410''>which</span> <span m=''3719570''>we</span>
  <span m=''3719640''>haven''t</span> <span m=''3719890''>prespecified.</span> </p><p><span
  m=''3722040''>So</span> <span m=''3722140''>that''s</span> <span m=''3722320''>something</span>
  <span m=''3722610''>even</span> <span m=''3722920''>fair</span> <span m=''3723150''>merge</span>
  <span m=''3723510''>can''t</span> <span m=''3723710''>do, and</span> <span m=''3723960''>they''re</span>
  <span m=''3724050''>things</span> <span m=''3724290''>called--</span> <span m=''3725662''>I</span>
  <span m=''3726010''>forget--</span> <span m=''3727220''>natagers</span> <span m=''3727790''>or</span>
  <span m=''3727890''>something.</span> <span m=''3728860''>That''s</span> <span m=''3729550''>a</span>
  <span m=''3729670''>generalization</span> <span m=''3730400''>of fair</span> <span
  m=''3730660''>merge</span> <span m=''3730980''>to</span> <span m=''3731090''>allow</span>
  <span m=''3731350''>that.</span> <span m=''3731790''>There''s</span> <span m=''3732150''>a</span>
  <span m=''3732200''>whole</span> <span m=''3732650''>sort</span> <span m=''3732870''>of</span>
  <span m=''3732970''>research</span> <span m=''3733360''>discipline</span> <span
  m=''3733850''>saying</span> <span m=''3734010''>how</span> <span m=''3734140''>far</span>
  <span m=''3734580''>can</span> <span m=''3734730''>you</span> <span m=''3734840''>push</span>
  <span m=''3735070''>this</span> <span m=''3735240''>functional</span> <span m=''3735610''>perspective</span>
  <span m=''3736620''>by</span> <span m=''3736790''>adding</span> <span m=''3737640''>more</span>
  <span m=''3737870''>and</span> <span m=''3737940''>more</span> <span m=''3738100''>mechanism?</span>
  <span m=''3739580''>And</span> <span m=''3739810''>how</span> <span m=''3739950''>far</span>
  <span m=''3740180''>does</span> <span m=''3740340''>that</span> <span m=''3740490''>go</span>
  <span m=''3740600''>before</span> <span m=''3740820''>the</span> <span m=''3740900''>whole</span>
  <span m=''3741070''>thing</span> <span m=''3741220''>breaks</span> <span m=''3741470''>down
  and</span> <span m=''3741720''>you</span> <span m=''3741800''>might</span> <span
  m=''3742010''>as</span> <span m=''3742090''>well</span> <span m=''3742250''>been</span>
  <span m=''3742370''>using</span> <span m=''3742660''>set</span> <span m=''3742890''>anyway.</span>
  </p><p><span m=''3745610''>AUDIENCE: You need</span> <span m=''3746080''>to set</span>
  <span m=''3746340''>him up</span> <span m=''3746570''>on</span> <span m=''3746710''>automatic</span>
  <span m=''3746750''>deposit.</span> </p><p><span m=''3748960''>[LAUGHTER]</span>
  </p><p><span m=''3759630''>PROFESSOR: OK,</span> <span m=''3759880''>thank</span>
  <span m=''3760080''>you.</span> </p>'
type: course
uid: 2b3f4b452167491302a2e4dedb19bcbd

---
None