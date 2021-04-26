---
about_this_resource_text: <p><b>Topics covered:&nbsp;</b>Storage Allocation and Garbage
  Collection</p> <p><b> Instructors:</b> Hal Abelson and Gerald Jay Sussman</p> <p>Subtitles
  for this course are provided through the generous assistance of Henry Baker, Hoofar
  Pourzand, Heather Wood, Aleksejs Truhans, Steven Edwards, George Menhorn, and Mahendra
  Kumar.</p>
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
embedded_media:
- id: 10B.jpg
  parent_uid: de43479d33e354e7ec3284a110b13795
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/10b-storage-allocation-and-garbage-collection/10B.jpg
  title: 10B.jpg
  type: null
  uid: 35197d4d0e27cfcae643a92743f5d438
- id: Video-YouTube-Stream
  media_location: AbK4bZhUk48
  parent_uid: de43479d33e354e7ec3284a110b13795
  title: Video-YouTube-Stream
  type: Video
  uid: 0048f89e8e2b7f483bd502a5f2327e56
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT_Structure_of_Computer_Programs_1986/lec10b.mp4
  parent_uid: de43479d33e354e7ec3284a110b13795
  title: Video-Internet Archive-MP4
  type: Video
  uid: 9cb5b8c7641f57158dd4032f88f8ae09
- id: Thumbnail-OCW-JPG
  parent_uid: de43479d33e354e7ec3284a110b13795
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: fe0a310ef38de68a2f9ada1e0083083a
- id: 3Play-3PlayYouTubeid-MP4
  media_location: AbK4bZhUk48
  parent_uid: de43479d33e354e7ec3284a110b13795
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 1845d00499e222d78fb771a881768c07
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/AbK4bZhUk48/default.jpg
  parent_uid: de43479d33e354e7ec3284a110b13795
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 1dab11ea10af1d10bdaf367913d32a83
- id: AbK4bZhUk48.srt
  parent_uid: de43479d33e354e7ec3284a110b13795
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/10b-storage-allocation-and-garbage-collection/AbK4bZhUk48.srt
  title: 3play caption file
  type: null
  uid: 4c647238df1f6fe17022a01781300d23
- id: AbK4bZhUk48.pdf
  parent_uid: de43479d33e354e7ec3284a110b13795
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/10b-storage-allocation-and-garbage-collection/AbK4bZhUk48.pdf
  title: 3play pdf file
  type: null
  uid: a087f7372af7b42f1252ba55ad781557
- id: Caption-3Play YouTube id-SRT
  parent_uid: de43479d33e354e7ec3284a110b13795
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 6f04f3be9ba9a34f3be48fe9e916a8cd
- id: Transcript-3Play YouTube id-PDF
  parent_uid: de43479d33e354e7ec3284a110b13795
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 6e740eef4d7b5c596049ad857f2a2434
inline_embed_id: 4537327610b:storageallocationandgarbagecollection29627025
layout: video
order_index: null
parent_uid: 4fcacad2c29981dd668a6b29822403cc
related_resources_text: ''
short_url: 10b-storage-allocation-and-garbage-collection
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/10b-storage-allocation-and-garbage-collection
template_type: Tabbed
title: '10B: Storage Allocation and Garbage Collection'
transcript: '<p><span m=''4970''>[MUSIC-- "JESU, JOY OF MAN''S DESIRING" BY JOHANN
  SEBASTIAN BACH]</span> </p><p><span m=''18910''>PROFESSOR: Well,</span> <span m=''19170''>there''s</span>
  <span m=''19360''>one</span> <span m=''19590''>bit</span> <span m=''19750''>of</span>
  <span m=''19850''>mystery</span> <span m=''20310''>left,</span> <span m=''21240''>which</span>
  <span m=''21970''>I''d</span> <span m=''22140''>like</span> <span m=''22330''>to</span>
  <span m=''22420''>get</span> <span m=''22580''>rid</span> <span m=''22700''>of</span>
  <span m=''22800''>right</span> <span m=''23020''>now.</span> <span m=''24440''>And</span>
  <span m=''24820''>that''s</span> <span m=''25380''>that</span> <span m=''25870''>we''ve</span>
  <span m=''26020''>been</span> <span m=''26590''>blithely</span> <span m=''27260''>doing</span>
  <span m=''27690''>things</span> <span m=''27970''>like</span> <span m=''28210''>cons</span>
  <span m=''30120''>assuming</span> <span m=''30480''>there''s</span> <span m=''30660''>always</span>
  <span m=''31020''>another</span> <span m=''31320''>one.</span> <span m=''33660''>That</span>
  <span m=''33950''>we''ve</span> <span m=''34110''>been</span> <span m=''35300''>doing</span>
  <span m=''35610''>these</span> <span m=''35830''>things</span> <span m=''36120''>like</span>
  <span m=''36500''>car-ing</span> <span m=''36870''>and</span> <span m=''37060''>cdr-ing</span>
  <span m=''37480''>and</span> <span m=''37590''>assuming</span> <span m=''37930''>that</span>
  <span m=''38040''>we</span> <span m=''38150''>had</span> <span m=''38350''>some</span>
  <span m=''38530''>idea</span> <span m=''38750''>how</span> <span m=''38890''>this</span>
  <span m=''39040''>can</span> <span m=''39140''>be</span> <span m=''39250''>done.</span>
  <span m=''40020''>Now</span> <span m=''40230''>indeed</span> <span m=''41060''>we</span>
  <span m=''41760''>said</span> <span m=''41990''>that</span> <span m=''42230''>that''s</span>
  <span m=''42440''>equivalent</span> <span m=''42910''>to</span> <span m=''43450''>having</span>
  <span m=''43800''>procedures.</span> <span m=''45780''>But</span> <span m=''46000''>that</span>
  <span m=''46200''>doesn''t</span> <span m=''46430''>really</span> <span m=''46660''>solve</span>
  <span m=''47020''>the</span> <span m=''47110''>problem,</span> <span m=''47700''>because</span>
  <span m=''48280''>the</span> <span m=''48360''>procedure</span> <span m=''48790''>need</span>
  <span m=''49020''>all sorts</span> <span m=''49380''>of</span> <span m=''49430''>complicated</span>
  <span m=''49890''>mechanisms</span> <span m=''50300''>like</span> <span m=''50470''>environment</span>
  <span m=''50910''>structures</span> <span m=''51600''>and</span> <span m=''51750''>things</span>
  <span m=''51960''>like</span> <span m=''52150''>that</span> <span m=''52360''>to</span>
  <span m=''52440''>work.</span> <span m=''53010''>And</span> <span m=''53160''>those</span>
  <span m=''53340''>were</span> <span m=''53460''>ultimately</span> <span m=''53860''>made</span>
  <span m=''54090''>out of conses</span> <span m=''55350''>in</span> <span m=''55430''>the</span>
  <span m=''55510''>model</span> <span m=''55770''>that</span> <span m=''55880''>we</span>
  <span m=''55990''>had,</span> <span m=''56650''>so</span> <span m=''57050''>that</span>
  <span m=''57240''>really</span> <span m=''57440''>doesn''t</span> <span m=''57710''>solve</span>
  <span m=''57940''>the</span> <span m=''58010''>problem.</span> </p><p><span m=''59380''>Now</span>
  <span m=''59930''>the</span> <span m=''60330''>problem</span> <span m=''60710''>here</span>
  <span m=''60970''>is</span> <span m=''61870''>the</span> <span m=''62170''>glue</span>
  <span m=''62510''>the</span> <span m=''62660''>data</span> <span m=''62860''>structure''s</span>
  <span m=''63310''>made</span> <span m=''63560''>out</span> <span m=''63680''>of.</span>
  <span m=''64760''>What</span> <span m=''64940''>kind</span> <span m=''65150''>of</span>
  <span m=''65230''>possible</span> <span m=''65650''>thing</span> <span m=''65890''>could
  it</span> <span m=''66120''>be?</span> <span m=''67370''>We''ve</span> <span m=''67580''>been</span>
  <span m=''67800''>showing</span> <span m=''68100''>you</span> <span m=''68220''>things</span>
  <span m=''68530''>like</span> <span m=''69590''>a</span> <span m=''69750''>machine,</span>
  <span m=''70500''>a</span> <span m=''70610''>computer</span> <span m=''71060''>that</span>
  <span m=''71220''>has</span> <span m=''73045''>a</span> <span m=''73310''>controller,</span>
  <span m=''74380''>and some</span> <span m=''74700''>registers,</span> <span m=''75480''>and</span>
  <span m=''75640''>maybe</span> <span m=''75920''>a</span> <span m=''75960''>stack.</span>
  <span m=''76980''>And</span> <span m=''77180''>we</span> <span m=''77380''>haven''t</span>
  <span m=''77600''>said anything</span> <span m=''77910''>about,</span> <span m=''78170''>for</span>
  <span m=''78270''>example,</span> <span m=''78980''>larger</span> <span m=''79430''>memory.</span>
  <span m=''80570''>And</span> <span m=''80650''>I</span> <span m=''80740''>think</span>
  <span m=''80920''>that''s what</span> <span m=''81130''>we</span> <span m=''81240''>have</span>
  <span m=''81360''>to</span> <span m=''81440''>worry</span> <span m=''81610''>about</span>
  <span m=''81860''>right</span> <span m=''82100''>now.</span> </p><p><span m=''83740''>But</span>
  <span m=''84180''>just</span> <span m=''85380''>to</span> <span m=''85560''>make</span>
  <span m=''85740''>it</span> <span m=''85900''>perfectly</span> <span m=''86310''>clear</span>
  <span m=''86560''>that</span> <span m=''86710''>this</span> <span m=''86860''>is</span>
  <span m=''86980''>an</span> <span m=''87160''>inessential,</span> <span m=''88920''>purely</span>
  <span m=''89630''>implementational</span> <span m=''90470''>thing,</span> <span
  m=''91220''>I''d</span> <span m=''91320''>like</span> <span m=''91520''>to</span>
  <span m=''92170''>show</span> <span m=''92390''>you,</span> <span m=''92550''>for</span>
  <span m=''92700''>example,</span> <span m=''93010''>how</span> <span m=''93110''>you</span>
  <span m=''93210''>can</span> <span m=''93300''>do it</span> <span m=''93500''>all
  with</span> <span m=''93640''>the</span> <span m=''93710''>numbers.</span> <span
  m=''94800''>That''s</span> <span m=''95520''>an</span> <span m=''96090''>easy</span>
  <span m=''96410''>one.</span> <span m=''97590''>Famous</span> <span m=''98000''>fellow</span>
  <span m=''98210''>by</span> <span m=''98310''>the</span> <span m=''98420''>name</span>
  <span m=''98540''>of</span> <span m=''98620''>Godel,</span> <span m=''103480''>a</span>
  <span m=''104120''>logician</span> <span m=''104780''>at</span> <span m=''104830''>the</span>
  <span m=''104920''>end</span> <span m=''105020''>of</span> <span m=''105120''>the</span>
  <span m=''105200''>1930s,</span> <span m=''106910''>invented</span> <span m=''107620''>a</span>
  <span m=''107780''>very</span> <span m=''108040''>clever</span> <span m=''108360''>way</span>
  <span m=''108640''>of</span> <span m=''108750''>encoding</span> <span m=''110290''>the</span>
  <span m=''111050''>complicated</span> <span m=''111660''>expressions</span> <span
  m=''112890''>as</span> <span m=''113110''>numbers.</span> <span m=''114320''>For</span>
  <span m=''114550''>example--</span> <span m=''115540''>I''m</span> <span m=''115780''>not</span>
  <span m=''116030''>saying</span> <span m=''116210''>exactly</span> <span m=''116650''>what</span>
  <span m=''116780''>Godel''s</span> <span m=''117430''>scheme</span> <span m=''117820''>is,</span>
  <span m=''118040''>because</span> <span m=''118160''>he</span> <span m=''118250''>didn''t</span>
  <span m=''118480''>use</span> <span m=''118640''>words</span> <span m=''118870''>like</span>
  <span m=''119050''>cons.</span> <span m=''119660''>He had</span> <span m=''119900''>other</span>
  <span m=''120150''>kinds</span> <span m=''120470''>of</span> <span m=''121070''>ways</span>
  <span m=''121210''>of</span> <span m=''121350''>combining</span> <span m=''121720''>to
  make</span> <span m=''121890''>expressions.</span> <span m=''123090''>But</span>
  <span m=''123420''>he</span> <span m=''123750''>said,</span> <span m=''123960''>I''m</span>
  <span m=''124100''>going</span> <span m=''124210''>to</span> <span m=''124330''>assign
  a</span> <span m=''124680''>number to</span> <span m=''125120''>every</span> <span
  m=''125860''>algebraic</span> <span m=''126320''>expression.</span> <span m=''127920''>And</span>
  <span m=''128050''>the way</span> <span m=''128340''>I''m going</span> <span m=''128389''>to
  manufacture</span> <span m=''129000''>these</span> <span m=''129190''>numbers</span>
  <span m=''129789''>is</span> <span m=''129970''>by</span> <span m=''130120''>combining</span>
  <span m=''130660''>the</span> <span m=''130740''>numbers</span> <span m=''131060''>of</span>
  <span m=''131150''>the</span> <span m=''131250''>parts.</span> </p><p><span m=''132470''>So</span>
  <span m=''132690''>for</span> <span m=''132910''>example,</span> <span m=''134030''>what</span>
  <span m=''134210''>we</span> <span m=''134340''>were</span> <span m=''134430''>doing</span>
  <span m=''134700''>our</span> <span m=''134900''>world,</span> <span m=''135420''>we</span>
  <span m=''135580''>could</span> <span m=''135690''>say</span> <span m=''135880''>that</span>
  <span m=''137140''>if</span> <span m=''137350''>objects</span> <span m=''140930''>are</span>
  <span m=''141090''>represented</span> <span m=''141610''>by</span> <span m=''141740''>numbers,</span>
  <span m=''150650''>then</span> <span m=''154130''>cons</span> <span m=''156000''>of</span>
  <span m=''156820''>x</span> <span m=''157170''>and</span> <span m=''157420''>y</span>
  <span m=''158150''>could</span> <span m=''158330''>be</span> <span m=''158450''>represented</span>
  <span m=''159140''>by</span> <span m=''161290''>2</span> <span m=''161660''>to the</span>
  <span m=''162030''>x</span> <span m=''162660''>times</span> <span m=''162990''>2</span>
  <span m=''163280''>to the y.</span> <span m=''166130''>Because</span> <span m=''166680''>then</span>
  <span m=''166840''>we</span> <span m=''166970''>could</span> <span m=''167090''>extract</span>
  <span m=''167580''>the</span> <span m=''167670''>parts.</span> <span m=''169560''>We</span>
  <span m=''169750''>could</span> <span m=''169890''>say,</span> <span m=''170160''>for</span>
  <span m=''170390''>example,</span> <span m=''171070''>that</span> <span m=''171510''>then</span>
  <span m=''171750''>car</span> <span m=''174445''>of,</span> <span m=''174890''>say,</span>
  <span m=''175530''>x</span> <span m=''177310''>is</span> <span m=''177500''>the</span>
  <span m=''177580''>number</span> <span m=''179120''>of</span> <span m=''179900''>factors</span>
  <span m=''182840''>of</span> <span m=''183270''>2</span> <span m=''184090''>in</span>
  <span m=''184770''>x.</span> <span m=''186690''>And</span> <span m=''187330''>of</span>
  <span m=''187480''>course</span> <span m=''187730''>cdr</span> <span m=''187890''>is</span>
  <span m=''188040''>the</span> <span m=''188160''>same</span> <span m=''188440''>thing.</span>
  <span m=''190690''>It''s</span> <span m=''191110''>the</span> <span m=''191690''>number</span>
  <span m=''192050''>of</span> <span m=''192430''>factors</span> <span m=''193110''>of</span>
  <span m=''193820''>3</span> <span m=''194460''>in</span> <span m=''195090''>x.</span>
  </p><p><span m=''196510''>Now</span> <span m=''196700''>this</span> <span m=''196870''>is</span>
  <span m=''196980''>a</span> <span m=''197080''>perfectly</span> <span m=''197620''>reasonable</span>
  <span m=''198070''>scheme,</span> <span m=''199220''>except</span> <span m=''199570''>for</span>
  <span m=''199660''>the</span> <span m=''199750''>fact</span> <span m=''200020''>that</span>
  <span m=''200120''>the</span> <span m=''200200''>numbers</span> <span m=''200530''>rapidly</span>
  <span m=''201460''>get</span> <span m=''201650''>to</span> <span m=''201720''>be</span>
  <span m=''201840''>much</span> <span m=''202090''>larger</span> <span m=''202870''>in</span>
  <span m=''203220''>number</span> <span m=''203450''>of</span> <span m=''203520''>digits</span>
  <span m=''204220''>than</span> <span m=''204740''>the</span> <span m=''205220''>number</span>
  <span m=''205440''>of</span> <span m=''205500''>protons</span> <span m=''205940''>in</span>
  <span m=''206000''>the</span> <span m=''206060''>universe.</span> <span m=''207950''>So</span>
  <span m=''208100''>there''s</span> <span m=''208290''>no</span> <span m=''208490''>easy</span>
  <span m=''208750''>way</span> <span m=''208980''>to</span> <span m=''209040''>use</span>
  <span m=''209410''>this</span> <span m=''209600''>scheme</span> <span m=''209960''>other</span>
  <span m=''210140''>than the</span> <span m=''210420''>theoretical</span> <span m=''210920''>one.</span>
  <span m=''213430''>On</span> <span m=''213640''>the</span> <span m=''213770''>other</span>
  <span m=''213910''>hand,</span> <span m=''214800''>there</span> <span m=''215440''>are</span>
  <span m=''215680''>other</span> <span m=''215900''>ways</span> <span m=''216270''>of</span>
  <span m=''216400''>representing</span> <span m=''217010''>these</span> <span m=''217250''>things.</span>
  <span m=''218450''>We</span> <span m=''218700''>have</span> <span m=''218800''>been</span>
  <span m=''219110''>thinking</span> <span m=''219420''>in</span> <span m=''219520''>terms</span>
  <span m=''220230''>of</span> <span m=''220830''>little</span> <span m=''221800''>boxes.</span>
  <span m=''224010''>We''ve</span> <span m=''224230''>been</span> <span m=''224360''>thinking</span>
  <span m=''224660''>about</span> <span m=''225120''>our</span> <span m=''225360''>cons
  structures</span> <span m=''226590''>as</span> <span m=''226730''>looking</span>
  <span m=''227000''>sort</span> <span m=''227270''>of</span> <span m=''227380''>like</span>
  <span m=''227630''>this.</span> <span m=''230280''>They''re little</span> <span
  m=''230660''>pigeon</span> <span m=''230970''>holes</span> <span m=''231560''>with</span>
  <span m=''231800''>things</span> <span m=''232060''>in</span> <span m=''232240''>them.</span>
  <span m=''233610''>And</span> <span m=''233740''>of</span> <span m=''233870''>course</span>
  <span m=''234010''>we</span> <span m=''234140''>arrange</span> <span m=''234190''>them
  in little</span> <span m=''234880''>trees.</span> <span m=''237210''>I</span> <span
  m=''237370''>wish</span> <span m=''237660''>that</span> <span m=''237900''>the</span>
  <span m=''238740''>semiconductor</span> <span m=''239300''>manufacturers</span>
  <span m=''240060''>would</span> <span m=''240210''>supply</span> <span m=''240550''>me</span>
  <span m=''240680''>with</span> <span m=''240830''>something</span> <span m=''241120''>appropriate</span>
  <span m=''241670''>for</span> <span m=''241780''>this,</span> <span m=''242390''>but</span>
  <span m=''242950''>actually</span> <span m=''243900''>what</span> <span m=''244130''>they</span>
  <span m=''244280''>do</span> <span m=''244440''>supply</span> <span m=''244830''>me</span>
  <span m=''245000''>with</span> <span m=''246290''>is</span> <span m=''246510''>a</span>
  <span m=''247100''>linear</span> <span m=''247550''>memory.</span> </p><p><span
  m=''249380''>Memory</span> <span m=''249760''>is</span> <span m=''249930''>sort</span>
  <span m=''250060''>of</span> <span m=''250220''>a</span> <span m=''250350''>big</span>
  <span m=''250950''>pile</span> <span m=''251430''>of</span> <span m=''252580''>pigeonholes,</span>
  <span m=''255170''>pigeonholes</span> <span m=''255790''>like</span> <span m=''256010''>this.</span>
  <span m=''257720''>Each</span> <span m=''257910''>of</span> <span m=''257970''>which</span>
  <span m=''258130''>can</span> <span m=''258260''>hold</span> <span m=''258740''>a</span>
  <span m=''258839''>certain</span> <span m=''259140''>sized</span> <span m=''259670''>object,</span>
  <span m=''260959''>a</span> <span m=''261070''>fixed</span> <span m=''261470''>size</span>
  <span m=''261760''>object.</span> <span m=''263390''>So,</span> <span m=''263600''>for</span>
  <span m=''263770''>example,</span> <span m=''264050''>a</span> <span m=''264100''>complicated</span>
  <span m=''264600''>list</span> <span m=''264850''>with</span> <span m=''264930''>25</span>
  <span m=''265410''>elements</span> <span m=''265720''>won''t</span> <span m=''265890''>fit
  in</span> <span m=''266080''>one</span> <span m=''266250''>of</span> <span m=''266340''>these.</span>
  <span m=''268550''>However,</span> <span m=''268860''>each</span> <span m=''269050''>of</span>
  <span m=''269120''>these is</span> <span m=''269460''>indexed</span> <span m=''269990''>by
  an</span> <span m=''270270''>address.</span> <span m=''273970''>So</span> <span
  m=''274130''>the</span> <span m=''274290''>address</span> <span m=''274580''>might</span>
  <span m=''274830''>be</span> <span m=''274980''>zero</span> <span m=''275390''>here,</span>
  <span m=''275710''>one</span> <span m=''276010''>here,</span> <span m=''276240''>two</span>
  <span m=''276470''>here,</span> <span m=''276750''>three</span> <span m=''276960''>here,</span>
  <span m=''277160''>and</span> <span m=''277280''>so</span> <span m=''277530''>on.</span>
  <span m=''278060''>That</span> <span m=''278410''>we</span> <span m=''278590''>write</span>
  <span m=''278900''>these</span> <span m=''279060''>down</span> <span m=''279270''>as</span>
  <span m=''279400''>numbers</span> <span m=''279770''>is</span> <span m=''279870''>unimportant.</span>
  <span m=''280400''>What</span> <span m=''280520''>matters</span> <span m=''280810''>is
  that</span> <span m=''280920''>they''re</span> <span m=''281180''>distinct</span>
  <span m=''282030''>as</span> <span m=''282250''>a</span> <span m=''282290''>way</span>
  <span m=''282370''>to</span> <span m=''282450''>get</span> <span m=''282620''>to</span>
  <span m=''282710''>the</span> <span m=''282900''>next</span> <span m=''283090''>one.</span>
  <span m=''284970''>And</span> <span m=''285130''>inside</span> <span m=''285385''>of</span>
  <span m=''285640''>each</span> <span m=''285820''>of</span> <span m=''285900''>these,</span>
  <span m=''286390''>we</span> <span m=''286580''>can</span> <span m=''286720''>stuff</span>
  <span m=''287020''>something</span> <span m=''287810''>into</span> <span m=''288300''>these</span>
  <span m=''288560''>pigeonholes.</span> <span m=''289530''>That''s what memory</span>
  <span m=''290210''>is</span> <span m=''290320''>like,</span> <span m=''291060''>for</span>
  <span m=''291180''>those of you</span> <span m=''291380''>who</span> <span m=''291670''>haven''t</span>
  <span m=''292300''>built</span> <span m=''292580''>a</span> <span m=''292620''>computer.</span>
  </p><p><span m=''296690''>Now</span> <span m=''296920''>the</span> <span m=''297010''>problem</span>
  <span m=''297460''>is</span> <span m=''297570''>how are</span> <span m=''297730''>we</span>
  <span m=''297830''>going</span> <span m=''298010''>to</span> <span m=''298130''>impose</span>
  <span m=''298640''>on</span> <span m=''298850''>this</span> <span m=''299060''>type</span>
  <span m=''299280''>of</span> <span m=''299360''>structure,</span> <span m=''300560''>this</span>
  <span m=''300810''>nice</span> <span m=''301080''>tree</span> <span m=''301300''>structure.</span>
  <span m=''303290''>Well</span> <span m=''303520''>it''s</span> <span m=''303660''>not</span>
  <span m=''303870''>very</span> <span m=''304090''>hard,</span> <span m=''304640''>and</span>
  <span m=''304790''>there</span> <span m=''304930''>have</span> <span m=''305030''>been</span>
  <span m=''305130''>numerous</span> <span m=''305480''>schemes</span> <span m=''305810''>involved</span>
  <span m=''306210''>in</span> <span m=''306250''>this.</span> <span m=''306630''>The</span>
  <span m=''306860''>most</span> <span m=''307250''>important</span> <span m=''307670''>one</span>
  <span m=''308090''>is</span> <span m=''308290''>to</span> <span m=''308390''>say,</span>
  <span m=''308890''>well</span> <span m=''309250''>assuming</span> <span m=''309730''>that</span>
  <span m=''309860''>the</span> <span m=''309930''>semiconductor</span> <span m=''310500''>manufacturer</span>
  <span m=''311130''>allows</span> <span m=''311540''>me</span> <span m=''311670''>to</span>
  <span m=''312160''>arrange</span> <span m=''313220''>my</span> <span m=''313390''>memory</span>
  <span m=''313920''>so that</span> <span m=''314210''>one</span> <span m=''314380''>of</span>
  <span m=''314440''>these</span> <span m=''314630''>pigeonholes</span> <span m=''315160''>is</span>
  <span m=''315320''>big</span> <span m=''315530''>enough</span> <span m=''315910''>to</span>
  <span m=''316390''>hold</span> <span m=''316850''>the</span> <span m=''317080''>address</span>
  <span m=''317640''>of</span> <span m=''317730''>another</span> <span m=''320120''>I</span>
  <span m=''320230''>haven''t</span> <span m=''320450''>made.</span> <span m=''321706''>Now
  it</span> <span m=''322130''>actually</span> <span m=''322560''>has</span> <span
  m=''322660''>to</span> <span m=''322730''>be</span> <span m=''322800''>a</span>
  <span m=''322860''>little</span> <span m=''323040''>bit</span> <span m=''323190''>bigger</span>
  <span m=''323450''>because</span> <span m=''323620''>I</span> <span m=''323730''>have</span>
  <span m=''323840''>to</span> <span m=''323920''>also</span> <span m=''324190''>install</span>
  <span m=''324820''>or</span> <span m=''324980''>store</span> <span m=''326420''>some</span>
  <span m=''327030''>information</span> <span m=''327610''>as</span> <span m=''327730''>to</span>
  <span m=''327820''>a</span> <span m=''327920''>tag</span> <span m=''328215''>which</span>
  <span m=''328510''>describes</span> <span m=''328970''>the</span> <span m=''329070''>kind</span>
  <span m=''329260''>of</span> <span m=''329340''>thing</span> <span m=''329520''>that''s</span>
  <span m=''329720''>there.</span> <span m=''330390''>And</span> <span m=''330560''>we''ll</span>
  <span m=''330660''>see</span> <span m=''330820''>that</span> <span m=''330940''>in</span>
  <span m=''331070''>a</span> <span m=''331120''>second.</span> <span m=''332350''>And</span>
  <span m=''332730''>of</span> <span m=''332870''>course</span> <span m=''333100''>if</span>
  <span m=''333230''>the</span> <span m=''333510''>semiconductor</span> <span m=''334000''>manufacturer</span>
  <span m=''334560''>doesn''t</span> <span m=''334860''>arrange it</span> <span m=''335140''>so</span>
  <span m=''335230''>I</span> <span m=''335330''>can</span> <span m=''335460''>do</span>
  <span m=''335600''>that,</span> <span m=''336050''>then</span> <span m=''336240''>of</span>
  <span m=''336320''>course</span> <span m=''336490''>I</span> <span m=''336580''>can,</span>
  <span m=''337470''>with</span> <span m=''337720''>some</span> <span m=''337950''>cleverness,</span>
  <span m=''338670''>arrange</span> <span m=''339480''>combinations</span> <span m=''340180''>of</span>
  <span m=''340230''>these</span> <span m=''340610''>to</span> <span m=''340730''>fit</span>
  <span m=''340910''>together</span> <span m=''341220''>in</span> <span m=''341280''>that</span>
  <span m=''341490''>way.</span> </p><p><span m=''343770''>So</span> <span m=''343960''>we''re</span>
  <span m=''344030''>going</span> <span m=''344100''>to</span> <span m=''344180''>have</span>
  <span m=''344450''>to</span> <span m=''346430''>imagine</span> <span m=''347100''>imposing</span>
  <span m=''348250''>this</span> <span m=''348510''>complicated</span> <span m=''349040''>tree
  structure</span> <span m=''349630''>on our</span> <span m=''349860''>nice</span>
  <span m=''350120''>linear</span> <span m=''350830''>memory.</span> <span m=''351740''>If</span>
  <span m=''352240''>we</span> <span m=''352350''>look</span> <span m=''352510''>at</span>
  <span m=''352580''>the</span> <span m=''352690''>first</span> <span m=''353770''>still</span>
  <span m=''354070''>store,</span> <span m=''354590''>we</span> <span m=''354740''>see</span>
  <span m=''356600''>a</span> <span m=''356740''>classic</span> <span m=''357220''>scheme</span>
  <span m=''357540''>for</span> <span m=''357680''>doing</span> <span m=''357960''>that.</span>
  <span m=''359490''>It''s</span> <span m=''359750''>a</span> <span m=''360410''>standard</span>
  <span m=''360810''>way</span> <span m=''361050''>of</span> <span m=''361170''>representing</span>
  <span m=''361850''>Lisp</span> <span m=''361970''>structures</span> <span m=''363910''>in</span>
  <span m=''364070''>a</span> <span m=''364930''>linear</span> <span m=''365270''>memory.</span>
  <span m=''365980''>What</span> <span m=''366330''>we</span> <span m=''366640''>do</span>
  <span m=''366880''>is</span> <span m=''367100''>we</span> <span m=''367220''>divide</span>
  <span m=''367650''>this</span> <span m=''367850''>memory</span> <span m=''369520''>into</span>
  <span m=''370130''>two</span> <span m=''370680''>parts.</span> <span m=''372030''>An</span>
  <span m=''372210''>array</span> <span m=''372520''>called</span> <span m=''372790''>the</span>
  <span m=''372870''>cars,</span> <span m=''374520''>and</span> <span m=''374770''>an
  array</span> <span m=''375130''>called</span> <span m=''375260''>the</span> <span
  m=''375350''>cdrs.</span> <span m=''377580''>Now</span> <span m=''377790''>whether</span>
  <span m=''378050''>those</span> <span m=''378330''>happen</span> <span m=''378630''>to</span>
  <span m=''378680''>be</span> <span m=''378830''>sequential</span> <span m=''379350''>addresses</span>
  <span m=''380110''>or</span> <span m=''380470''>whatever,</span> <span m=''381160''>it''s</span>
  <span m=''381380''>not</span> <span m=''381560''>important.</span> <span m=''382560''>That''s</span>
  <span m=''383100''>somebody''s</span> <span m=''383930''>implementation</span> <span
  m=''384610''>details.</span> <span m=''385800''>But</span> <span m=''386020''>there</span>
  <span m=''386160''>are</span> <span m=''386220''>two</span> <span m=''387540''>arrays</span>
  <span m=''388020''>here.</span> <span m=''388960''>Linear</span> <span m=''389250''>arrays</span>
  <span m=''389990''>indexed</span> <span m=''390520''>by</span> <span m=''391010''>sequential</span>
  <span m=''391580''>indices</span> <span m=''392010''>like</span> <span m=''392230''>this.</span>
  <span m=''394840''>What</span> <span m=''395050''>is</span> <span m=''395180''>stored</span>
  <span m=''395560''>in</span> <span m=''395650''>each</span> <span m=''395840''>of</span>
  <span m=''395940''>these</span> <span m=''396150''>pigeonholes</span> <span m=''397620''>is</span>
  <span m=''398100''>a</span> <span m=''398270''>typed</span> <span m=''399250''>object.</span>
  </p><p><span m=''401430''>And</span> <span m=''401670''>what</span> <span m=''401790''>we</span>
  <span m=''401980''>have</span> <span m=''402180''>here</span> <span m=''402620''>are</span>
  <span m=''402880''>types</span> <span m=''403290''>which</span> <span m=''403630''>begin</span>
  <span m=''403960''>with</span> <span m=''404310''>letters</span> <span m=''404840''>like</span>
  <span m=''405400''>p,</span> <span m=''405770''>standing</span> <span m=''405970''>for</span>
  <span m=''406160''>a</span> <span m=''406210''>pair.</span> <span m=''407790''>Or</span>
  <span m=''408120''>n,</span> <span m=''408380''>standing</span> <span m=''408700''>for</span>
  <span m=''408810''>a</span> <span m=''408920''>number.</span> <span m=''410040''>Or</span>
  <span m=''410650''>e,</span> <span m=''411000''>standing</span> <span m=''411250''>for</span>
  <span m=''411380''>an</span> <span m=''411510''>empty</span> <span m=''411860''>list.</span>
  <span m=''414890''>The</span> <span m=''415040''>end</span> <span m=''415300''>of</span>
  <span m=''415390''>the</span> <span m=''415470''>list.</span> <span m=''417110''>And</span>
  <span m=''417290''>so if</span> <span m=''417360''>we</span> <span m=''417520''>wish</span>
  <span m=''417710''>to</span> <span m=''417840''>represent</span> <span m=''419020''>an</span>
  <span m=''419180''>object</span> <span m=''419600''>like</span> <span m=''419810''>this,</span>
  <span m=''420090''>the list</span> <span m=''420420''>beginning</span> <span m=''420930''>with</span>
  <span m=''421290''>1,</span> <span m=''421660''>2</span> <span m=''422710''>and</span>
  <span m=''422910''>then</span> <span m=''423080''>having</span> <span m=''423350''>a</span>
  <span m=''423440''>3</span> <span m=''423720''>and a</span> <span m=''423850''>4</span>
  <span m=''424140''>as</span> <span m=''424250''>its</span> <span m=''424310''>second</span>
  <span m=''424660''>and</span> <span m=''424760''>third</span> <span m=''424960''>elements.</span>
  <span m=''426430''>A</span> <span m=''426520''>list</span> <span m=''426700''>containing</span>
  <span m=''427320''>a</span> <span m=''427550''>list</span> <span m=''427900''>as</span>
  <span m=''428010''>its</span> <span m=''428170''>first</span> <span m=''428480''>part</span>
  <span m=''429410''>and</span> <span m=''429610''>then</span> <span m=''429820''>two</span>
  <span m=''430220''>numbers</span> <span m=''430720''>as</span> <span m=''430860''>a</span>
  <span m=''430930''>second</span> <span m=''431290''>and</span> <span m=''431400''>third</span>
  <span m=''431630''>parts.</span> <span m=''432610''>Then</span> <span m=''433140''>of</span>
  <span m=''433230''>course</span> <span m=''433450''>we</span> <span m=''433610''>draw
  it</span> <span m=''434040''>sort</span> <span m=''434140''>of</span> <span m=''434250''>like</span>
  <span m=''434460''>this</span> <span m=''434640''>these</span> <span m=''434860''>days,</span>
  <span m=''435120''>in</span> <span m=''435250''>box-and-pointer</span> <span m=''435880''>notation.</span>
  <span m=''437320''>And</span> <span m=''437470''>you</span> <span m=''437560''>see,</span>
  <span m=''437900''>these</span> <span m=''438260''>are</span> <span m=''438300''>the</span>
  <span m=''438450''>three</span> <span m=''439600''>cells</span> <span m=''440150''>that</span>
  <span m=''440690''>have</span> <span m=''440910''>as</span> <span m=''441050''>their</span>
  <span m=''441190''>car</span> <span m=''441440''>pointer</span> <span m=''442010''>the</span>
  <span m=''442860''>object</span> <span m=''443330''>which</span> <span m=''443530''>is</span>
  <span m=''443790''>either</span> <span m=''444030''>1,</span> <span m=''444360''>2</span>
  <span m=''445170''>or</span> <span m=''445400''>3</span> <span m=''446280''>or</span>
  <span m=''446500''>4.</span> </p><p><span m=''448390''>And</span> <span m=''448530''>then</span>
  <span m=''448680''>of</span> <span m=''448840''>course</span> <span m=''449000''>the</span>
  <span m=''449090''>1,</span> <span m=''449360''>2,</span> <span m=''449820''>the</span>
  <span m=''449950''>car</span> <span m=''450300''>of</span> <span m=''450380''>this</span>
  <span m=''450540''>entire</span> <span m=''450860''>structure,</span> <span m=''451410''>is</span>
  <span m=''451590''>itself</span> <span m=''451860''>a</span> <span m=''451900''>substructure</span>
  <span m=''452830''>which</span> <span m=''453100''>contains</span> <span m=''453750''>a</span>
  <span m=''453870''>sublist</span> <span m=''454320''>like</span> <span m=''454530''>that.</span>
  <span m=''455940''>What</span> <span m=''456160''>I''m</span> <span m=''456280''>about</span>
  <span m=''456580''>to</span> <span m=''456660''>do</span> <span m=''457260''>is</span>
  <span m=''457640''>put</span> <span m=''457980''>down</span> <span m=''459160''>places</span>
  <span m=''459660''>which</span> <span m=''459830''>are--</span> <span m=''459970''>I''m</span>
  <span m=''460100''>going</span> <span m=''460200''>to</span> <span m=''460300''>assign</span>
  <span m=''460760''>indices.</span> <span m=''461880''>Like</span> <span m=''462030''>this</span>
  <span m=''462220''>1,</span> <span m=''462780''>over</span> <span m=''462970''>here,</span>
  <span m=''463650''>represents</span> <span m=''465240''>the</span> <span m=''465530''>index</span>
  <span m=''466230''>of</span> <span m=''466470''>this</span> <span m=''466590''>cell.</span>
  <span m=''469850''>But</span> <span m=''469910''>that</span> <span m=''470250''>pointer</span>
  <span m=''470750''>that we</span> <span m=''470910''>see</span> <span m=''471110''>here</span>
  <span m=''472570''>is</span> <span m=''472700''>a</span> <span m=''472820''>reference</span>
  <span m=''473940''>to</span> <span m=''474350''>the</span> <span m=''475540''>pair
  of</span> <span m=''475780''>pigeonholes</span> <span m=''476340''>in</span> <span
  m=''476420''>the</span> <span m=''476500''>cars</span> <span m=''476800''>and</span>
  <span m=''476850''>the</span> <span m=''476930''>cdrs</span> <span m=''477430''>that</span>
  <span m=''477530''>are</span> <span m=''477640''>labeled</span> <span m=''478000''>by</span>
  <span m=''478160''>1</span> <span m=''478800''>in</span> <span m=''478960''>my</span>
  <span m=''479110''>linear</span> <span m=''479440''>memory</span> <span m=''479750''>down</span>
  <span m=''479980''>here.</span> </p><p><span m=''482000''>So</span> <span m=''482410''>if</span>
  <span m=''482520''>I</span> <span m=''482590''>wish</span> <span m=''482790''>to</span>
  <span m=''482930''>impose</span> <span m=''483360''>this</span> <span m=''483480''>structure</span>
  <span m=''484160''>on</span> <span m=''484380''>my</span> <span m=''484500''>linear</span>
  <span m=''484810''>memory,</span> <span m=''485920''>what</span> <span m=''486120''>I</span>
  <span m=''486240''>do</span> <span m=''486510''>is</span> <span m=''486600''>I</span>
  <span m=''486690''>say,</span> <span m=''486920''>oh</span> <span m=''487080''>yes,</span>
  <span m=''487610''>why don''t</span> <span m=''487860''>we</span> <span m=''488380''>drop</span>
  <span m=''488780''>this</span> <span m=''490980''>into</span> <span m=''491210''>cell</span>
  <span m=''491490''>1?</span> <span m=''492220''>I</span> <span m=''492290''>pick</span>
  <span m=''492500''>one.</span> <span m=''492660''>There''s</span> <span m=''492870''>1.</span>
  <span m=''494270''>And</span> <span m=''494490''>that</span> <span m=''494710''>says</span>
  <span m=''495190''>that</span> <span m=''495400''>its</span> <span m=''495620''>car,</span>
  <span m=''496330''>I''m</span> <span m=''496480''>going</span> <span m=''496560''>to</span>
  <span m=''496640''>assign</span> <span m=''496990''>it</span> <span m=''497100''>to</span>
  <span m=''497180''>be</span> <span m=''497290''>a</span> <span m=''497340''>pair.</span>
  <span m=''497950''>It''s</span> <span m=''498130''>a</span> <span m=''498190''>pair,</span>
  <span m=''500390''>which</span> <span m=''500570''>is</span> <span m=''500680''>in</span>
  <span m=''500800''>index</span> <span m=''501160''>5.</span> <span m=''502590''>And</span>
  <span m=''503040''>the</span> <span m=''503410''>cdr,</span> <span m=''504020''>which</span>
  <span m=''504200''>is</span> <span m=''504290''>this</span> <span m=''504440''>one</span>
  <span m=''504600''>over</span> <span m=''504730''>here,</span> <span m=''505450''>is</span>
  <span m=''505610''>a</span> <span m=''505680''>pair</span> <span m=''506130''>which</span>
  <span m=''506330''>I''m</span> <span m=''506360''>going to</span> <span m=''506580''>stick</span>
  <span m=''506850''>into</span> <span m=''506940''>place</span> <span m=''507230''>2.</span>
  <span m=''508340''>p2.</span> <span m=''510890''>And</span> <span m=''511980''>take</span>
  <span m=''512150''>a</span> <span m=''512240''>look</span> <span m=''512330''>at</span>
  <span m=''512429''>p2.</span> <span m=''512950''>Oh</span> <span m=''513080''>yes,</span>
  <span m=''513390''>well</span> <span m=''513549''>p2</span> <span m=''514090''>is</span>
  <span m=''514230''>a</span> <span m=''514299''>thing</span> <span m=''514720''>whose</span>
  <span m=''515200''>car</span> <span m=''516100''>is</span> <span m=''516280''>the</span>
  <span m=''516400''>number</span> <span m=''516780''>3,</span> <span m=''517370''>so
  as</span> <span m=''517730''>you see, an</span> <span m=''517840''>n3.</span> <span
  m=''519520''>And</span> <span m=''519750''>whose</span> <span m=''520010''>cdr,</span>
  <span m=''520840''>over</span> <span m=''521039''>here,</span> <span m=''521850''>is</span>
  <span m=''522590''>a</span> <span m=''522830''>pair,</span> <span m=''524080''>which</span>
  <span m=''524380''>lives</span> <span m=''524620''>in</span> <span m=''525110''>place</span>
  <span m=''525430''>4.</span> <span m=''526640''>So</span> <span m=''526850''>that''s
  what</span> <span m=''526970''>this</span> <span m=''527090''>p4</span> <span m=''527550''>is.</span>
  <span m=''528650''>p4</span> <span m=''530010''>is</span> <span m=''530360''>a</span>
  <span m=''530650''>number</span> <span m=''531910''>whose</span> <span m=''532150''>value</span>
  <span m=''532510''>is</span> <span m=''532640''>4</span> <span m=''533100''>in</span>
  <span m=''533310''>its car</span> <span m=''534690''>and</span> <span m=''534930''>whose</span>
  <span m=''535150''>cdr</span> <span m=''535970''>is</span> <span m=''536200''>an</span>
  <span m=''536310''>empty</span> <span m=''536710''>list</span> <span m=''537810''>right</span>
  <span m=''538040''>there.</span> <span m=''539170''>And</span> <span m=''539550''>that</span>
  <span m=''539930''>ends it.</span> </p><p><span m=''540690''>So</span> <span m=''540810''>this</span>
  <span m=''540980''>is</span> <span m=''542040''>the</span> <span m=''542210''>traditional</span>
  <span m=''543280''>way</span> <span m=''543640''>of</span> <span m=''543790''>representing</span>
  <span m=''544890''>this</span> <span m=''545130''>kind</span> <span m=''545390''>of</span>
  <span m=''545750''>binary</span> <span m=''546330''>tree</span> <span m=''548640''>in</span>
  <span m=''548760''>a</span> <span m=''548810''>linear</span> <span m=''549120''>memory.</span>
  <span m=''551620''>Now</span> <span m=''553980''>the</span> <span m=''554190''>next</span>
  <span m=''554400''>question,</span> <span m=''554740''>of</span> <span m=''554950''>course,</span>
  <span m=''555160''>that</span> <span m=''555260''>we</span> <span m=''555370''>might</span>
  <span m=''555590''>want</span> <span m=''555680''>to</span> <span m=''555770''>worry</span>
  <span m=''556020''>about</span> <span m=''556700''>is</span> <span m=''556830''>just</span>
  <span m=''556980''>a</span> <span m=''557020''>little</span> <span m=''557210''>bit
  of</span> <span m=''557400''>implementation.</span> <span m=''558440''>That</span>
  <span m=''558780''>means</span> <span m=''559020''>that</span> <span m=''559120''>when</span>
  <span m=''559260''>I</span> <span m=''559370''>write</span> <span m=''559780''>procedures</span>
  <span m=''560350''>of</span> <span m=''560460''>the</span> <span m=''560570''>form</span>
  <span m=''562690''>assigned</span> <span m=''563250''>a,</span> <span m=''563750''>[UNINTELLIGIBLE]</span>
  <span m=''563860''>procedures--</span> <span m=''564600''>lines</span> <span m=''565140''>of</span>
  <span m=''565940''>register</span> <span m=''566350''>machine</span> <span m=''566700''>code</span>
  <span m=''567180''>of</span> <span m=''567440''>the form</span> <span m=''567830''>assigned</span>
  <span m=''568440''>a,</span> <span m=''568760''>the</span> <span m=''569000''>car</span>
  <span m=''569300''>of</span> <span m=''569600''>[UNINTELLIGIBLE]</span> <span m=''570140''>b,</span>
  <span m=''570870''>what</span> <span m=''570990''>I</span> <span m=''571110''>really</span>
  <span m=''571430''>mean</span> <span m=''572580''>is</span> <span m=''575020''>addressing</span>
  <span m=''575600''>these</span> <span m=''576690''>elements.</span> <span m=''578740''>And</span>
  <span m=''579000''>so</span> <span m=''579120''>we''re</span> <span m=''579340''>going
  to</span> <span m=''579540''>think</span> <span m=''579690''>of</span> <span m=''579840''>that</span>
  <span m=''579990''>as</span> <span m=''580830''>a</span> <span m=''581870''>abbreviation</span>
  <span m=''582600''>for it.</span> </p><p><span m=''584470''>Now</span> <span m=''584660''>of</span>
  <span m=''584770''>course</span> <span m=''585330''>in</span> <span m=''585440''>order</span>
  <span m=''585650''>to</span> <span m=''585750''>write</span> <span m=''585970''>that</span>
  <span m=''586170''>down</span> <span m=''586430''>I''m</span> <span m=''586530''>going</span>
  <span m=''586620''>to</span> <span m=''586720''>introduce</span> <span m=''587230''>some</span>
  <span m=''587420''>sort</span> <span m=''587630''>of</span> <span m=''587990''>a</span>
  <span m=''588150''>structure</span> <span m=''588630''>called</span> <span m=''588810''>a</span>
  <span m=''588870''>vector.</span> <span m=''592120''>And we''re</span> <span m=''592340''>going</span>
  <span m=''592410''>to</span> <span m=''592490''>have</span> <span m=''592610''>something</span>
  <span m=''592910''>which</span> <span m=''593090''>will</span> <span m=''593530''>reference</span>
  <span m=''593990''>a</span> <span m=''594050''>vector,</span> <span m=''596700''>just</span>
  <span m=''597100''>so</span> <span m=''597230''>we</span> <span m=''597330''>can</span>
  <span m=''597710''>write</span> <span m=''597920''>it</span> <span m=''598030''>down.</span>
  <span m=''598710''>Which</span> <span m=''598890''>takes</span> <span m=''599130''>the</span>
  <span m=''599220''>name</span> <span m=''599480''>of</span> <span m=''599530''>the</span>
  <span m=''599610''>vector,</span> <span m=''601120''>or</span> <span m=''601280''>the--</span>
  <span m=''602240''>I don''t</span> <span m=''602490''>think</span> <span m=''602760''>that</span>
  <span m=''602880''>name</span> <span m=''603180''>is</span> <span m=''603280''>the</span>
  <span m=''603350''>right</span> <span m=''603560''>word.</span> <span m=''603970''>Which</span>
  <span m=''604180''>takes</span> <span m=''604370''>the</span> <span m=''604460''>vector</span>
  <span m=''607870''>and</span> <span m=''608210''>the</span> <span m=''608870''>index,</span>
  <span m=''610945''>and</span> <span m=''611420''>I</span> <span m=''611820''>have
  to have</span> <span m=''611980''>a</span> <span m=''612010''>way</span> <span m=''612190''>of</span>
  <span m=''612260''>setting</span> <span m=''612610''>one</span> <span m=''612750''>of</span>
  <span m=''612830''>those</span> <span m=''613100''>with</span> <span m=''613210''>something</span>
  <span m=''613430''>called</span> <span m=''613580''>a</span> <span m=''613620''>vector</span>
  <span m=''613950''>set,</span> <span m=''614630''>I</span> <span m=''614860''>don''t</span>
  <span m=''614970''>really</span> <span m=''615160''>care.</span> <span m=''616280''>But</span>
  <span m=''616430''>let''s</span> <span m=''616620''>look,</span> <span m=''616880''>for</span>
  <span m=''617030''>example,</span> <span m=''618160''>at</span> <span m=''618480''>then</span>
  <span m=''618930''>that</span> <span m=''619180''>kind</span> <span m=''619400''>of</span>
  <span m=''619520''>implementation</span> <span m=''621330''>of</span> <span m=''621570''>car</span>
  <span m=''622550''>and</span> <span m=''622720''>cdr.</span> </p><p><span m=''626470''>So</span>
  <span m=''626700''>for</span> <span m=''626890''>example</span> <span m=''627330''>if</span>
  <span m=''627480''>I</span> <span m=''627600''>happen</span> <span m=''627930''>to</span>
  <span m=''628220''>have</span> <span m=''629300''>a</span> <span m=''629770''>register</span>
  <span m=''630320''>b,</span> <span m=''631270''>which</span> <span m=''631470''>contains</span>
  <span m=''632800''>the</span> <span m=''633070''>type</span> <span m=''633450''>index</span>
  <span m=''633930''>of</span> <span m=''634020''>a</span> <span m=''634110''>pair,</span>
  <span m=''636130''>and</span> <span m=''636360''>therefore</span> <span m=''637010''>it</span>
  <span m=''637170''>is</span> <span m=''637320''>the</span> <span m=''637580''>pointer</span>
  <span m=''638090''>to</span> <span m=''638250''>a</span> <span m=''638320''>pair,</span>
  <span m=''639470''>then</span> <span m=''639590''>I</span> <span m=''639710''>could</span>
  <span m=''639830''>take</span> <span m=''640010''>the</span> <span m=''640080''>car</span>
  <span m=''640420''>of that</span> <span m=''641680''>and</span> <span m=''641930''>if</span>
  <span m=''642070''>I--</span> <span m=''642370''>write this down--</span> <span
  m=''642760''>I</span> <span m=''642850''>might</span> <span m=''643060''>put</span>
  <span m=''643190''>that in</span> <span m=''643360''>register</span> <span m=''643710''>a.</span>
  <span m=''644490''>What</span> <span m=''644660''>that</span> <span m=''644870''>really</span>
  <span m=''645250''>is</span> <span m=''645460''>is a</span> <span m=''645580''>representation</span>
  <span m=''646480''>of</span> <span m=''648650''>the</span> <span m=''648980''>assign</span>
  <span m=''649400''>to</span> <span m=''649660''>a,</span> <span m=''650120''>the</span>
  <span m=''650500''>value</span> <span m=''650970''>of</span> <span m=''651070''>vector</span>
  <span m=''651360''>reffing--</span> <span m=''652890''>or</span> <span m=''653470''>array</span>
  <span m=''653750''>indexing,</span> <span m=''654250''>if</span> <span m=''654360''>you</span>
  <span m=''654480''>will--</span> <span m=''654630''>or</span> <span m=''654700''>something,</span>
  <span m=''656280''>the</span> <span m=''656600''>cars</span> <span m=''657130''>object--</span>
  <span m=''658490''>whatever</span> <span m=''658790''>that</span> <span m=''658960''>is--</span>
  <span m=''659990''>with</span> <span m=''660150''>the</span> <span m=''660240''>index,</span>
  <span m=''660620''>b.</span> <span m=''662650''>And</span> <span m=''662850''>similarly</span>
  <span m=''663140''>for</span> <span m=''663260''>cdr.</span> <span m=''664015''>And</span>
  <span m=''664430''>we</span> <span m=''664600''>can</span> <span m=''664750''>do</span>
  <span m=''664890''>the</span> <span m=''665000''>same</span> <span m=''665280''>thing</span>
  <span m=''665850''>for</span> <span m=''666330''>assignment</span> <span m=''666970''>to</span>
  <span m=''667550''>data</span> <span m=''667770''>structures,</span> <span m=''669150''>if</span>
  <span m=''669360''>we</span> <span m=''669480''>need</span> <span m=''669710''>to</span>
  <span m=''669790''>do</span> <span m=''669930''>that</span> <span m=''670150''>sort</span>
  <span m=''670260''>of</span> <span m=''670370''>thing</span> <span m=''670540''>at</span>
  <span m=''670610''>all.</span> <span m=''671840''>It''s</span> <span m=''672440''>not</span>
  <span m=''672660''>too</span> <span m=''672790''>hard</span> <span m=''673010''>to</span>
  <span m=''673070''>build</span> <span m=''673320''>that.</span> </p><p><span m=''674580''>Well</span>
  <span m=''674800''>now</span> <span m=''675000''>the</span> <span m=''675160''>next</span>
  <span m=''675330''>question</span> <span m=''675590''>is</span> <span m=''675690''>how</span>
  <span m=''675870''>are we going to</span> <span m=''676020''>do</span> <span m=''676170''>allocation.</span>
  <span m=''678010''>And</span> <span m=''678190''>every</span> <span m=''678370''>so</span>
  <span m=''678540''>often</span> <span m=''678810''>I</span> <span m=''678900''>say</span>
  <span m=''679190''>I</span> <span m=''679390''>want</span> <span m=''679600''>a</span>
  <span m=''679670''>cons.</span> <span m=''681550''>Now</span> <span m=''681940''>conses</span>
  <span m=''682350''>don''t</span> <span m=''682600''>grow</span> <span m=''682780''>on</span>
  <span m=''682950''>trees.</span> <span m=''683790''>Or</span> <span m=''684050''>maybe</span>
  <span m=''684310''>they</span> <span m=''684390''>should.</span> <span m=''685340''>But
  I have to</span> <span m=''685740''>have</span> <span m=''685920''>some</span> <span
  m=''686140''>way</span> <span m=''686350''>of</span> <span m=''687770''>getting</span>
  <span m=''688070''>the</span> <span m=''688110''>next</span> <span m=''688410''>one.</span>
  <span m=''689980''>I</span> <span m=''690140''>have</span> <span m=''690300''>to</span>
  <span m=''690450''>have</span> <span m=''690590''>some</span> <span m=''690780''>idea</span>
  <span m=''691110''>of</span> <span m=''691570''>if</span> <span m=''691740''>their</span>
  <span m=''691880''>memory</span> <span m=''692210''>is</span> <span m=''692630''>unused</span>
  <span m=''693770''>that I</span> <span m=''693920''>might</span> <span m=''694120''>want</span>
  <span m=''694180''>to</span> <span m=''694260''>allocate</span> <span m=''694740''>from.</span>
  <span m=''695630''>And</span> <span m=''695870''>there</span> <span m=''696030''>are</span>
  <span m=''696180''>many</span> <span m=''696430''>schemes</span> <span m=''696780''>for</span>
  <span m=''696890''>doing</span> <span m=''697170''>this.</span> <span m=''697380''>And</span>
  <span m=''697570''>the</span> <span m=''697630''>particular</span> <span m=''698030''>thing</span>
  <span m=''698200''>I''m</span> <span m=''698300''>showing</span> <span m=''698560''>you</span>
  <span m=''698660''>right</span> <span m=''698880''>now</span> <span m=''699270''>is</span>
  <span m=''699650''>not</span> <span m=''699910''>essential.</span> <span m=''702100''>However</span>
  <span m=''702580''>it''s</span> <span m=''702720''>convenient</span> <span m=''703220''>and</span>
  <span m=''703350''>has</span> <span m=''703470''>been</span> <span m=''703620''>done</span>
  <span m=''703800''>many</span> <span m=''704030''>times.</span> <span m=''704960''>One
  scheme''s</span> <span m=''705400''>was</span> <span m=''705480''>called</span>
  <span m=''705640''>the</span> <span m=''705710''>free</span> <span m=''705920''>list</span>
  <span m=''706190''>allocation</span> <span m=''706740''>scheme.</span> <span m=''707660''>What</span>
  <span m=''707870''>that</span> <span m=''708100''>means</span> <span m=''708390''>is</span>
  <span m=''708780''>that</span> <span m=''708950''>all</span> <span m=''709180''>of</span>
  <span m=''709290''>the</span> <span m=''709380''>free</span> <span m=''709660''>memory</span>
  <span m=''710030''>that</span> <span m=''710220''>there</span> <span m=''710410''>is</span>
  <span m=''710570''>in</span> <span m=''710640''>the</span> <span m=''710710''>world</span>
  <span m=''711670''>is</span> <span m=''711860''>linked</span> <span m=''712090''>together</span>
  <span m=''712460''>in</span> <span m=''712500''>a</span> <span m=''712550''>linked</span>
  <span m=''712810''>list,</span> <span m=''714700''>just</span> <span m=''714950''>like</span>
  <span m=''715390''>all</span> <span m=''715580''>the</span> <span m=''715710''>other</span>
  <span m=''715840''>stuff.</span> <span m=''716960''>And</span> <span m=''717140''>whenever</span>
  <span m=''717390''>you</span> <span m=''717530''>need</span> <span m=''718410''>a</span>
  <span m=''718540''>free</span> <span m=''718820''>cell</span> <span m=''719100''>to</span>
  <span m=''719220''>make</span> <span m=''719410''>a</span> <span m=''719450''>new</span>
  <span m=''719590''>cons,</span> <span m=''721090''>you</span> <span m=''721230''>grab</span>
  <span m=''721500''>the</span> <span m=''721590''>first,</span> <span m=''721900''>one</span>
  <span m=''722380''>make</span> <span m=''722560''>the</span> <span m=''722640''>free</span>
  <span m=''722810''>list</span> <span m=''723010''>be</span> <span m=''723120''>the</span>
  <span m=''723220''>cdr</span> <span m=''723500''>of</span> <span m=''723610''>it,</span>
  <span m=''724440''>and</span> <span m=''724620''>then</span> <span m=''724770''>allocate</span>
  <span m=''725220''>that.</span> </p><p><span m=''726030''>And</span> <span m=''726190''>so</span>
  <span m=''726640''>what</span> <span m=''726810''>that</span> <span m=''726990''>looks</span>
  <span m=''727170''>like</span> <span m=''727380''>is</span> <span m=''727450''>something</span>
  <span m=''727720''>like</span> <span m=''727940''>this.</span> <span m=''729530''>Here</span>
  <span m=''729700''>we</span> <span m=''729930''>have</span> <span m=''730200''>the</span>
  <span m=''730630''>free</span> <span m=''730870''>list</span> <span m=''733960''>starting</span>
  <span m=''734360''>in</span> <span m=''736280''>6.</span> <span m=''738510''>And</span>
  <span m=''738690''>what</span> <span m=''738860''>that</span> <span m=''739050''>is</span>
  <span m=''740110''>is</span> <span m=''740330''>a</span> <span m=''740540''>pointer-off</span>
  <span m=''741130''>to</span> <span m=''741260''>say</span> <span m=''743130''>8.</span>
  <span m=''744860''>So</span> <span m=''745020''>what</span> <span m=''745140''>it</span>
  <span m=''745230''>says</span> <span m=''745450''>is,</span> <span m=''745590''>this</span>
  <span m=''745760''>one</span> <span m=''745930''>is</span> <span m=''746030''>free</span>
  <span m=''746650''>and</span> <span m=''746870''>the</span> <span m=''747020''>next</span>
  <span m=''747170''>one</span> <span m=''747360''>is</span> <span m=''747470''>an</span>
  <span m=''747590''>8.</span> <span m=''748870''>This</span> <span m=''749110''>one</span>
  <span m=''749290''>is</span> <span m=''749420''>free</span> <span m=''750100''>and</span>
  <span m=''750250''>the</span> <span m=''750380''>next</span> <span m=''750520''>one</span>
  <span m=''750730''>is</span> <span m=''750840''>in</span> <span m=''751550''>3,</span>
  <span m=''752380''>the</span> <span m=''752530''>next</span> <span m=''752680''>one</span>
  <span m=''752880''>that''s</span> <span m=''752990''>free.</span> <span m=''753930''>That
  one''s</span> <span m=''754370''>free</span> <span m=''755140''>and</span> <span
  m=''755330''>the</span> <span m=''755500''>next</span> <span m=''755670''>one</span>
  <span m=''755920''>is</span> <span m=''756170''>in</span> <span m=''756990''>0.</span>
  <span m=''757680''>That</span> <span m=''758110''>one''s</span> <span m=''758280''>free</span>
  <span m=''758490''>and</span> <span m=''758570''>the</span> <span m=''758700''>next</span>
  <span m=''758830''>one''s</span> <span m=''759010''>in</span> <span m=''759140''>15.</span>
  <span m=''760940''>Something</span> <span m=''761270''>like</span> <span m=''761500''>that.</span>
  <span m=''762780''>We</span> <span m=''762940''>can</span> <span m=''763070''>imagine</span>
  <span m=''763490''>having</span> <span m=''763810''>such</span> <span m=''764010''>a</span>
  <span m=''764060''>structure.</span> </p><p><span m=''766400''>Given</span> <span
  m=''766630''>that</span> <span m=''766750''>we</span> <span m=''766930''>have</span>
  <span m=''767110''>something</span> <span m=''767450''>like</span> <span m=''767690''>that,</span>
  <span m=''769480''>then</span> <span m=''769740''>it''s</span> <span m=''769880''>possible</span>
  <span m=''770480''>to</span> <span m=''770990''>just</span> <span m=''771230''>get</span>
  <span m=''771440''>one</span> <span m=''771620''>when</span> <span m=''771780''>you</span>
  <span m=''771880''>need</span> <span m=''772090''>it.</span> <span m=''773940''>And</span>
  <span m=''774150''>so</span> <span m=''774510''>a</span> <span m=''774700''>program</span>
  <span m=''775730''>for</span> <span m=''775840''>doing</span> <span m=''776080''>cons,</span>
  <span m=''777560''>this is</span> <span m=''777760''>what</span> <span m=''777960''>cons</span>
  <span m=''778280''>might</span> <span m=''778500''>turn</span> <span m=''778700''>into.</span>
  <span m=''779320''>To</span> <span m=''779600''>assign</span> <span m=''779980''>to
  a</span> <span m=''780080''>register</span> <span m=''780560''>A</span> <span m=''781170''>the</span>
  <span m=''781280''>result</span> <span m=''781700''>of</span> <span m=''781840''>cons-ing,</span>
  <span m=''784550''>a</span> <span m=''784690''>B</span> <span m=''785010''>onto</span>
  <span m=''785410''>C,</span> <span m=''785870''>the</span> <span m=''786280''>value</span>
  <span m=''786770''>in</span> <span m=''786890''>this</span> <span m=''787070''>containing</span>
  <span m=''787370''>B</span> <span m=''787810''>and</span> <span m=''787900''>the</span>
  <span m=''787990''>value</span> <span m=''788250''>containing</span> <span m=''788560''>C,</span>
  <span m=''789370''>what we</span> <span m=''789600''>have</span> <span m=''789700''>to</span>
  <span m=''789800''>do</span> <span m=''790210''>is</span> <span m=''790580''>get</span>
  <span m=''790800''>the</span> <span m=''790890''>current</span> <span m=''791240''>[?
  type ?]</span> <span m=''791390''>ahead</span> <span m=''791590''>of</span> <span
  m=''791640''>the</span> <span m=''791710''>freelist,</span> <span m=''792580''>make</span>
  <span m=''792810''>the</span> <span m=''792910''>free</span> <span m=''793100''>list</span>
  <span m=''793400''>be</span> <span m=''793600''>its</span> <span m=''793810''>cdr.</span>
  <span m=''795680''>Then</span> <span m=''796250''>we</span> <span m=''796430''>have</span>
  <span m=''796600''>to</span> <span m=''797420''>change</span> <span m=''797860''>the</span>
  <span m=''797970''>cars</span> <span m=''798380''>to</span> <span m=''798490''>be</span>
  <span m=''799640''>the</span> <span m=''799840''>thing</span> <span m=''800020''>we''re</span>
  <span m=''800590''>making</span> <span m=''800970''>up</span> <span m=''801090''>to</span>
  <span m=''801220''>be</span> <span m=''801960''>in</span> <span m=''802160''>A</span>
  <span m=''803140''>to</span> <span m=''803310''>be</span> <span m=''803580''>the</span>
  <span m=''803660''>B,</span> <span m=''804490''>the</span> <span m=''804670''>thing</span>
  <span m=''804850''>in</span> <span m=''804970''>B.</span> <span m=''805680''>And</span>
  <span m=''805940''>we</span> <span m=''806210''>have</span> <span m=''806360''>to</span>
  <span m=''807020''>make</span> <span m=''807320''>change</span> <span m=''807560''>the</span>
  <span m=''807660''>cdrs</span> <span m=''808120''>of</span> <span m=''809290''>the</span>
  <span m=''809450''>thing</span> <span m=''809650''>that''s</span> <span m=''809810''>in</span>
  <span m=''809930''>A</span> <span m=''810880''>to</span> <span m=''811000''>be</span>
  <span m=''811160''>C.</span> <span m=''813750''>And</span> <span m=''813960''>then</span>
  <span m=''814080''>what we</span> <span m=''814270''>have</span> <span m=''814470''>in
  A</span> <span m=''814550''>is</span> <span m=''814840''>the</span> <span m=''814930''>right</span>
  <span m=''815220''>new</span> <span m=''815390''>frob,</span> <span m=''816020''>whatever</span>
  <span m=''816380''>it is.</span> <span m=''816650''>The</span> <span m=''816920''>object</span>
  <span m=''817360''>that</span> <span m=''817470''>we</span> <span m=''817590''>want.</span>
  </p><p><span m=''820470''>Now</span> <span m=''821480''>there''s</span> <span m=''821610''>a</span>
  <span m=''821660''>little</span> <span m=''821880''>bit</span> <span m=''822040''>of</span>
  <span m=''822430''>a</span> <span m=''822500''>cheat</span> <span m=''822770''>here</span>
  <span m=''822950''>that</span> <span m=''823030''>I</span> <span m=''823110''>haven''t</span>
  <span m=''823280''>told</span> <span m=''823490''>you</span> <span m=''823580''>about,</span>
  <span m=''824040''>which</span> <span m=''824270''>is</span> <span m=''824400''>somewhere</span>
  <span m=''824770''>around</span> <span m=''825100''>here</span> <span m=''825500''>I</span>
  <span m=''825630''>haven''t</span> <span m=''825920''>set</span> <span m=''826950''>that
  I''ve</span> <span m=''828760''>the</span> <span m=''829050''>type</span> <span
  m=''829490''>of</span> <span m=''829990''>the</span> <span m=''830290''>thing</span>
  <span m=''830530''>that</span> <span m=''830620''>I''m</span> <span m=''830770''>cons-ing</span>
  <span m=''831170''>up</span> <span m=''831280''>to</span> <span m=''831380''>be</span>
  <span m=''831490''>a</span> <span m=''831540''>pair,</span> <span m=''832380''>and</span>
  <span m=''832450''>I</span> <span m=''832600''>ought</span> <span m=''832780''>to.</span>
  <span m=''833510''>So</span> <span m=''833690''>there</span> <span m=''833840''>should</span>
  <span m=''834000''>be</span> <span m=''834570''>some</span> <span m=''834780''>sort</span>
  <span m=''834930''>of</span> <span m=''834990''>bits</span> <span m=''835310''>here</span>
  <span m=''835850''>are</span> <span m=''835970''>being</span> <span m=''836260''>set,</span>
  <span m=''836570''>and I</span> <span m=''836640''>just</span> <span m=''836790''>haven''t</span>
  <span m=''836940''>written</span> <span m=''837210''>that</span> <span m=''837430''>down.</span>
  <span m=''839810''>We</span> <span m=''839940''>could</span> <span m=''840040''>have</span>
  <span m=''840150''>arranged it,</span> <span m=''840550''>of</span> <span m=''840730''>course,</span>
  <span m=''840910''>for</span> <span m=''840980''>the</span> <span m=''841060''>free</span>
  <span m=''841240''>lift to be made</span> <span m=''841720''>out</span> <span m=''841830''>of</span>
  <span m=''841940''>pairs.</span> <span m=''843100''>And</span> <span m=''843290''>so</span>
  <span m=''843440''>then</span> <span m=''843630''>there''s</span> <span m=''843810''>no</span>
  <span m=''843960''>problem</span> <span m=''844350''>with</span> <span m=''844490''>that.</span>
  <span m=''846430''>But</span> <span m=''846660''>that</span> <span m=''846840''>sort</span>
  <span m=''847000''>of--</span> <span m=''847290''>again,</span> <span m=''847840''>an</span>
  <span m=''847980''>inessential</span> <span m=''848510''>detail</span> <span m=''848825''>in</span>
  <span m=''849440''>a</span> <span m=''849510''>way</span> <span m=''850160''>some</span>
  <span m=''850580''>particular</span> <span m=''851510''>programmer</span> <span
  m=''851885''>or</span> <span m=''852260''>architect</span> <span m=''852830''>or</span>
  <span m=''852910''>whatever</span> <span m=''853280''>might</span> <span m=''853500''>manufacture</span>
  <span m=''854290''>his</span> <span m=''854540''>machine</span> <span m=''855020''>or</span>
  <span m=''856000''>Lisp</span> <span m=''856270''>system.</span> </p><p><span m=''857540''>So</span>
  <span m=''857860''>for</span> <span m=''858090''>example,</span> <span m=''859230''>just</span>
  <span m=''859470''>looking</span> <span m=''859770''>at</span> <span m=''860020''>this,</span>
  <span m=''860610''>to</span> <span m=''860880''>allocate</span> <span m=''863670''>given</span>
  <span m=''863930''>that I</span> <span m=''864070''>had</span> <span m=''864220''>already</span>
  <span m=''864600''>the</span> <span m=''864690''>structure</span> <span m=''865110''>that</span>
  <span m=''865830''>you</span> <span m=''866010''>saw</span> <span m=''866200''>before,</span>
  <span m=''867200''>supposing</span> <span m=''867570''>I</span> <span m=''867640''>wanted</span>
  <span m=''867850''>to</span> <span m=''867950''>allocate</span> <span m=''869400''>a</span>
  <span m=''869550''>new</span> <span m=''869760''>cell,</span> <span m=''870700''>which</span>
  <span m=''870900''>is</span> <span m=''870990''>going</span> <span m=''871260''>to</span>
  <span m=''871900''>be</span> <span m=''873210''>representation</span> <span m=''874040''>of</span>
  <span m=''874250''>list</span> <span m=''875190''>one,</span> <span m=''875550''>one,</span>
  <span m=''875950''>two,</span> <span m=''877360''>where</span> <span m=''877590''>already</span>
  <span m=''878280''>one</span> <span m=''878680''>two</span> <span m=''878950''>was</span>
  <span m=''879230''>the</span> <span m=''879380''>car</span> <span m=''880350''>of</span>
  <span m=''880530''>the</span> <span m=''881040''>list</span> <span m=''881160''>we</span>
  <span m=''881240''>were</span> <span m=''881330''>playing</span> <span m=''881580''>with</span>
  <span m=''881710''>before.</span> <span m=''883430''>Well</span> <span m=''883670''>that''s</span>
  <span m=''883780''>not</span> <span m=''883950''>so</span> <span m=''884110''>hard.</span>
  <span m=''884780''>I</span> <span m=''884930''>stored</span> <span m=''885250''>that</span>
  <span m=''885460''>one</span> <span m=''885610''>and</span> <span m=''885750''>one,</span>
  <span m=''886220''>so</span> <span m=''886800''>p1</span> <span m=''887010''>one</span>
  <span m=''887320''>is</span> <span m=''887570''>the</span> <span m=''887670''>representation</span>
  <span m=''888650''>of</span> <span m=''888870''>this.</span> <span m=''889530''>This</span>
  <span m=''889900''>is</span> <span m=''890050''>p5.</span> <span m=''891690''>That''s</span>
  <span m=''892000''>going</span> <span m=''892170''>to</span> <span m=''892340''>be</span>
  <span m=''892540''>the</span> <span m=''892770''>cdr</span> <span m=''893100''>of</span>
  <span m=''893180''>this.</span> <span m=''894070''>Now</span> <span m=''894240''>we''re</span>
  <span m=''894310''>going</span> <span m=''894380''>to</span> <span m=''894460''>pull</span>
  <span m=''894680''>something</span> <span m=''894990''>off</span> <span m=''895130''>the</span>
  <span m=''895230''>free</span> <span m=''895400''>list,</span> <span m=''895610''>but
  remember</span> <span m=''896080''>the</span> <span m=''896220''>free list</span>
  <span m=''896360''>started</span> <span m=''896740''>at</span> <span m=''896880''>six.</span>
  <span m=''897780''>The</span> <span m=''898150''>new</span> <span m=''898340''>free</span>
  <span m=''898530''>list</span> <span m=''898780''>after</span> <span m=''899060''>this</span>
  <span m=''899230''>allocation</span> <span m=''899770''>is</span> <span m=''899830''>eight,</span>
  <span m=''901290''>a free</span> <span m=''901540''>list</span> <span m=''901700''>beginning</span>
  <span m=''902050''>at</span> <span m=''902130''>eight.</span> <span m=''902890''>And</span>
  <span m=''903140''>of</span> <span m=''903230''>course</span> <span m=''903740''>in</span>
  <span m=''903960''>six</span> <span m=''904260''>now</span> <span m=''904510''>we</span>
  <span m=''904700''>have</span> <span m=''905020''>a</span> <span m=''905140''>number</span>
  <span m=''905510''>one,</span> <span m=''906140''>which</span> <span m=''906320''>is</span>
  <span m=''906360''>what</span> <span m=''906480''>we</span> <span m=''906590''>wanted,</span>
  <span m=''907480''>with</span> <span m=''908020''>its</span> <span m=''908280''>cdr</span>
  <span m=''908550''>being</span> <span m=''909060''>the</span> <span m=''909660''>pair</span>
  <span m=''910110''>starting in</span> <span m=''910540''>location</span> <span m=''911050''>five.</span>
  <span m=''913330''>And</span> <span m=''913540''>that''s</span> <span m=''913800''>no</span>
  <span m=''913950''>big</span> <span m=''914150''>deal.</span> </p><p><span m=''916810''>So</span>
  <span m=''917490''>the</span> <span m=''917650''>only</span> <span m=''917820''>problem</span>
  <span m=''918170''>really</span> <span m=''918770''>remaining</span> <span m=''919260''>here</span>
  <span m=''920030''>is,</span> <span m=''921070''>well,</span> <span m=''921380''>I</span>
  <span m=''921480''>don''t</span> <span m=''921670''>have</span> <span m=''921830''>an</span>
  <span m=''921960''>infinitely</span> <span m=''922530''>large</span> <span m=''922890''>memory.</span>
  <span m=''925080''>If</span> <span m=''925250''>I</span> <span m=''925340''>do</span>
  <span m=''925500''>this</span> <span m=''925710''>for</span> <span m=''925800''>a</span>
  <span m=''925890''>little</span> <span m=''926130''>while,</span> <span m=''927180''>say,</span>
  <span m=''927560''>for</span> <span m=''927730''>example,</span> <span m=''928070''>supposing
  it</span> <span m=''928410''>takes</span> <span m=''928630''>me</span> <span m=''928730''>a</span>
  <span m=''928790''>microsecond</span> <span m=''929070''>to</span> <span m=''929470''>do</span>
  <span m=''929620''>a</span> <span m=''929925''>cons,</span> <span m=''930640''>and
  I</span> <span m=''930850''>have a</span> <span m=''931240''>million</span> <span
  m=''931910''>cons</span> <span m=''932290''>memory</span> <span m=''933680''>then
  I''m only going to</span> <span m=''934150''>run out</span> <span m=''934570''>in
  a</span> <span m=''934610''>second,</span> <span m=''936000''>and</span> <span m=''936160''>that''s</span>
  <span m=''936340''>pretty</span> <span m=''936540''>bad.</span> <span m=''938000''>So</span>
  <span m=''938540''>what</span> <span m=''938760''>we</span> <span m=''938880''>do</span>
  <span m=''939260''>to</span> <span m=''939350''>prevent</span> <span m=''939660''>that</span>
  <span m=''939950''>disaster,</span> <span m=''940620''>that</span> <span m=''940840''>ecological</span>
  <span m=''941470''>disaster,</span> <span m=''942520''>talk</span> <span m=''942880''>about</span>
  <span m=''943400''>right</span> <span m=''943570''>after</span> <span m=''943850''>questions.</span>
  <span m=''944300''>Are</span> <span m=''944360''>there</span> <span m=''944510''>any</span>
  <span m=''944630''>questions?</span> <span m=''951500''>Yes.</span> </p><p><span
  m=''952030''>AUDIENCE: In</span> <span m=''952560''>the</span> <span m=''952730''>environment</span>
  <span m=''953290''>diagrams</span> <span m=''953940''>that</span> <span m=''954100''>we</span>
  <span m=''954190''>were</span> <span m=''954290''>drawing</span> <span m=''954830''>we</span>
  <span m=''955440''>would</span> <span m=''956740''>use</span> <span m=''956940''>the</span>
  <span m=''957030''>body of</span> <span m=''957330''>procedures,</span> <span m=''958330''>and</span>
  <span m=''958480''>you would</span> <span m=''958630''>eventually</span> <span m=''959060''>wind</span>
  <span m=''959370''>up</span> <span m=''960190''>with</span> <span m=''960800''>things</span>
  <span m=''961050''>that</span> <span m=''961180''>were</span> <span m=''961270''>no</span>
  <span m=''961450''>longer</span> <span m=''961780''>useful</span> <span m=''962450''>in</span>
  <span m=''962620''>that</span> <span m=''962890''>structure.</span> <span m=''964930''>How</span>
  <span m=''965450''>is</span> <span m=''965790''>that</span> <span m=''965960''>represented?</span>
  </p><p><span m=''966890''>PROFESSOR: There''s</span> <span m=''967215''>two</span>
  <span m=''967540''>problems</span> <span m=''967940''>here.</span> <span m=''969180''>One</span>
  <span m=''969430''>you</span> <span m=''969560''>were</span> <span m=''969630''>asking</span>
  <span m=''970480''>is</span> <span m=''970960''>that</span> <span m=''971200''>material</span>
  <span m=''971610''>becomes</span> <span m=''972930''>useless.</span> <span m=''973870''>We''ll</span>
  <span m=''973970''>talk</span> <span m=''974140''>about</span> <span m=''974330''>that
  in</span> <span m=''974440''>a</span> <span m=''974550''>second.</span> <span m=''974920''>That
  has</span> <span m=''975150''>to</span> <span m=''975240''>do</span> <span m=''975390''>with</span>
  <span m=''975560''>how</span> <span m=''975670''>to</span> <span m=''975740''>prevent</span>
  <span m=''975990''>ecological</span> <span m=''976480''>disasters.</span> <span
  m=''978100''>If</span> <span m=''978280''>I</span> <span m=''978360''>make</span>
  <span m=''978560''>a</span> <span m=''978610''>lot</span> <span m=''978790''>of</span>
  <span m=''978860''>garbage</span> <span m=''979250''>I</span> <span m=''979310''>have</span>
  <span m=''979470''>to</span> <span m=''979580''>somehow</span> <span m=''979910''>be</span>
  <span m=''980030''>able</span> <span m=''980120''>to</span> <span m=''980190''>clean</span>
  <span m=''980450''>up</span> <span m=''980600''>after</span> <span m=''980830''>myself.</span>
  <span m=''981820''>And</span> <span m=''982080''>we''ll</span> <span m=''982180''>talk</span>
  <span m=''982350''>about</span> <span m=''982670''>that in a</span> <span m=''982900''>second.</span>
  <span m=''983430''>The</span> <span m=''983570''>other</span> <span m=''983890''>question</span>
  <span m=''984160''>you''re</span> <span m=''984330''>asking</span> <span m=''984600''>is</span>
  <span m=''984690''>how</span> <span m=''984820''>you</span> <span m=''984940''>represent</span>
  <span m=''985370''>the</span> <span m=''985460''>environments,</span> <span m=''986650''>I</span>
  <span m=''986930''>think.</span> </p><p><span m=''987210''>AUDIENCE: Yes.</span>
  </p><p><span m=''987600''>PROFESSOR: OK.</span> <span m=''988190''>And</span> <span
  m=''988320''>the</span> <span m=''988520''>environment structures</span> <span m=''988940''>can</span>
  <span m=''989090''>be</span> <span m=''989180''>represented</span> <span m=''989540''>in</span>
  <span m=''989780''>arbitrary</span> <span m=''990250''>ways.</span> <span m=''990860''>There</span>
  <span m=''991170''>are</span> <span m=''991200''>lots</span> <span m=''991500''>of</span>
  <span m=''991600''>them.</span> <span m=''991780''>I mean,</span> <span m=''991910''>here</span>
  <span m=''992120''>I''m just</span> <span m=''992300''>telling</span> <span m=''992520''>you</span>
  <span m=''992590''>about</span> <span m=''992790''>list</span> <span m=''992880''>cells.</span>
  <span m=''993630''>Of</span> <span m=''993710''>course</span> <span m=''993940''>every</span>
  <span m=''994160''>real</span> <span m=''994400''>system</span> <span m=''994960''>has</span>
  <span m=''995380''>vectors</span> <span m=''995810''>of</span> <span m=''995920''>arbitrary</span>
  <span m=''996400''>length</span> <span m=''996790''>as</span> <span m=''997010''>well</span>
  <span m=''997280''>as</span> <span m=''997660''>the</span> <span m=''998000''>vectors</span>
  <span m=''998360''>of</span> <span m=''998540''>length,</span> <span m=''998800''>too,</span>
  <span m=''999280''>which</span> <span m=''999500''>represent</span> <span m=''999890''>list</span>
  <span m=''1000190''>cells.</span> <span m=''1001080''>And</span> <span m=''1002230''>the</span>
  <span m=''1002630''>environment</span> <span m=''1003090''>structures</span> <span
  m=''1003610''>that</span> <span m=''1003770''>one</span> <span m=''1003920''>uses</span>
  <span m=''1005070''>in</span> <span m=''1005270''>a</span> <span m=''1005460''>professionally</span>
  <span m=''1006040''>written</span> <span m=''1006260''>Lisp</span> <span m=''1006500''>system</span>
  <span m=''1007250''>tend</span> <span m=''1007600''>to</span> <span m=''1007690''>be</span>
  <span m=''1009110''>vectors</span> <span m=''1009890''>which</span> <span m=''1010070''>contain</span>
  <span m=''1010680''>a</span> <span m=''1010810''>number</span> <span m=''1011050''>of</span>
  <span m=''1011120''>elements</span> <span m=''1011450''>approximately</span> <span
  m=''1012100''>equal</span> <span m=''1012350''>to</span> <span m=''1012450''>the</span>
  <span m=''1012540''>number</span> <span m=''1012740''>of</span> <span m=''1012830''>arguments--</span>
  <span m=''1013260''>a</span> <span m=''1013340''>little</span> <span m=''1013540''>bit</span>
  <span m=''1013690''>more</span> <span m=''1013940''>because</span> <span m=''1015970''>you</span>
  <span m=''1016090''>need</span> <span m=''1016290''>certain</span> <span m=''1016510''>glue.</span>
  <span m=''1018290''>So</span> <span m=''1019330''>remember,</span> <span m=''1019620''>the</span>
  <span m=''1019730''>environment</span> <span m=''1020120''>[UNINTELLIGIBLE]</span>
  <span m=''1020360''>frames.</span> <span m=''1020740''>The</span> <span m=''1020810''>frames
  are</span> <span m=''1021100''>constructed</span> <span m=''1021680''>by</span>
  <span m=''1022100''>applying</span> <span m=''1023140''>a</span> <span m=''1023230''>procedure.</span>
  <span m=''1023980''>In</span> <span m=''1024170''>doing</span> <span m=''1024470''>so,
  an</span> <span m=''1024819''>allocation</span> <span m=''1025480''>is</span> <span
  m=''1025599''>made</span> <span m=''1026369''>of</span> <span m=''1026920''>a</span>
  <span m=''1027380''>place</span> <span m=''1027700''>which</span> <span m=''1028060''>is</span>
  <span m=''1028220''>the</span> <span m=''1028849''>number</span> <span m=''1029250''>of</span>
  <span m=''1029369''>arguments</span> <span m=''1029859''>long</span> <span m=''1030170''>plus</span>
  <span m=''1030450''>[? unglue ?]</span> <span m=''1031270''>that</span> <span m=''1031490''>gets</span>
  <span m=''1031660''>linked</span> <span m=''1031839''>into</span> <span m=''1032099''>a</span>
  <span m=''1032160''>chain.</span> <span m=''1033859''>It''s</span> <span m=''1033960''>just</span>
  <span m=''1034170''>like</span> <span m=''1034339''>algol</span> <span m=''1034740''>at
  that</span> <span m=''1035200''>level.</span> <span m=''1039810''>There</span> <span
  m=''1039940''>any</span> <span m=''1040060''>other</span> <span m=''1040190''>questions?</span>
  <span m=''1043700''>OK.</span> <span m=''1043920''>Thank</span> <span m=''1044170''>you,</span>
  <span m=''1044240''>and</span> <span m=''1044520''>let''s</span> <span m=''1044690''>take</span>
  <span m=''1044829''>a</span> <span m=''1045050''>short</span> <span m=''1045310''>break.</span>
  </p><p><span m=''1046106''>[MUSIC-- "JESU, JOY OF MAN''S DESIRING" BY JOHANN SEBASTIAN
  BACH]</span> </p><p><span m=''1092270''>PROFESSOR: Well,</span> <span m=''1093450''>as
  I</span> <span m=''1093660''>just</span> <span m=''1093870''>said,</span> <span
  m=''1094310''>computer</span> <span m=''1095030''>memories</span> <span m=''1095840''>supplied</span>
  <span m=''1096300''>by</span> <span m=''1096410''>the</span> <span m=''1096510''>semiconductor</span>
  <span m=''1097180''>manufacturers</span> <span m=''1098170''>are</span> <span m=''1098350''>finite.</span>
  <span m=''1099420''>And</span> <span m=''1099570''>that''s</span> <span m=''1099730''>quite</span>
  <span m=''1099870''>a</span> <span m=''1099930''>pity.</span> <span m=''1101620''>It</span>
  <span m=''1101760''>might</span> <span m=''1101940''>not</span> <span m=''1102080''>always</span>
  <span m=''1102420''>be</span> <span m=''1102570''>that</span> <span m=''1102820''>way.</span>
  <span m=''1104030''>Just</span> <span m=''1104370''>for</span> <span m=''1104500''>a</span>
  <span m=''1104540''>quick</span> <span m=''1104740''>calculation,</span> <span m=''1105480''>you</span>
  <span m=''1105610''>can</span> <span m=''1105750''>see</span> <span m=''1105970''>that</span>
  <span m=''1106650''>it''s</span> <span m=''1106900''>possible</span> <span m=''1107990''>that</span>
  <span m=''1108370''>if</span> <span m=''1108480''>[? memory ?]</span> <span m=''1108860''>prices</span>
  <span m=''1109230''>keep</span> <span m=''1109400''>going</span> <span m=''1109620''>at</span>
  <span m=''1109910''>the</span> <span m=''1109990''>rate</span> <span m=''1110180''>they''re</span>
  <span m=''1110300''>going</span> <span m=''1111240''>that</span> <span m=''1111550''>if</span>
  <span m=''1111660''>you</span> <span m=''1112130''>still</span> <span m=''1112300''>took</span>
  <span m=''1112420''>a</span> <span m=''1112480''>microsecond</span> <span m=''1112740''>second</span>
  <span m=''1113050''>to do a</span> <span m=''1113240''>cons,</span> <span m=''1114480''>then--</span>
  <span m=''1114950''>first</span> <span m=''1115230''>of</span> <span m=''1115310''>all,</span>
  <span m=''1115470''>everybody</span> <span m=''1115940''>should</span> <span m=''1116130''>know</span>
  <span m=''1116290''>that</span> <span m=''1116450''>there''s</span> <span m=''1116660''>about</span>
  <span m=''1116840''>pi</span> <span m=''1117120''>times</span> <span m=''1117260''>ten
  to</span> <span m=''1117480''>the</span> <span m=''1117590''>seventh</span> <span
  m=''1117840''>seconds</span> <span m=''1118250''>in</span> <span m=''1118330''>a</span>
  <span m=''1118370''>year.</span> <span m=''1119450''>And</span> <span m=''1119700''>so</span>
  <span m=''1119900''>that</span> <span m=''1120130''>would be</span> <span m=''1121600''>ten</span>
  <span m=''1121800''>to the</span> <span m=''1121910''>seventh</span> <span m=''1122220''>plus
  ten to the</span> <span m=''1122640''>sixth</span> <span m=''1122830''>is ten</span>
  <span m=''1123100''>to</span> <span m=''1123160''>the</span> <span m=''1123240''>thirteenth.</span>
  <span m=''1123940''>So</span> <span m=''1124040''>there''s</span> <span m=''1124150''>maybe</span>
  <span m=''1124470''>ten to</span> <span m=''1124730''>the</span> <span m=''1124800''>fourteenth</span>
  <span m=''1125280''>conses</span> <span m=''1125535''>in the</span> <span m=''1125790''>life
  of a</span> <span m=''1126030''>machine.</span> <span m=''1127520''>If</span> <span
  m=''1127650''>there</span> <span m=''1127760''>was</span> <span m=''1127890''>ten</span>
  <span m=''1128040''>to the</span> <span m=''1128190''>fourteenth</span> <span m=''1128660''>words</span>
  <span m=''1128940''>of</span> <span m=''1129040''>memory</span> <span m=''1129720''>on</span>
  <span m=''1129900''>your</span> <span m=''1130010''>machine,</span> <span m=''1131280''>you''d</span>
  <span m=''1131440''>never</span> <span m=''1131660''>run</span> <span m=''1131840''>out.</span>
  </p><p><span m=''1134020''>And</span> <span m=''1134140''>that''s</span> <span m=''1134390''>not</span>
  <span m=''1134600''>completely</span> <span m=''1135020''>unreasonable.</span> <span
  m=''1136310''>Ten to</span> <span m=''1136540''>the</span> <span m=''1136620''>fourteenth</span>
  <span m=''1137070''>is</span> <span m=''1137220''>not</span> <span m=''1137520''>a</span>
  <span m=''1137570''>very</span> <span m=''1137810''>large</span> <span m=''1138100''>number.</span>
  <span m=''1143860''>I</span> <span m=''1143960''>don''t</span> <span m=''1144150''>think</span>
  <span m=''1144320''>it</span> <span m=''1144420''>is.</span> <span m=''1145180''>But</span>
  <span m=''1145580''>then</span> <span m=''1145920''>again</span> <span m=''1146260''>I</span>
  <span m=''1146370''>like</span> <span m=''1146520''>to</span> <span m=''1146570''>play</span>
  <span m=''1146730''>with</span> <span m=''1146830''>astronomy.</span> <span m=''1148700''>It''s</span>
  <span m=''1149570''>at</span> <span m=''1149710''>least</span> <span m=''1149960''>ten</span>
  <span m=''1150120''>to</span> <span m=''1150200''>the</span> <span m=''1150280''>eighteenth</span>
  <span m=''1150560''>centimeters</span> <span m=''1151070''>between</span> <span
  m=''1151380''>us</span> <span m=''1151540''>and</span> <span m=''1151620''>the</span>
  <span m=''1151690''>nearest</span> <span m=''1151980''>star.</span> <span m=''1152930''>But</span>
  <span m=''1153920''>the</span> <span m=''1154440''>thing</span> <span m=''1154930''>I''m</span>
  <span m=''1155720''>about</span> <span m=''1155970''>to</span> <span m=''1156080''>worry</span>
  <span m=''1156380''>about</span> <span m=''1158410''>is,</span> <span m=''1158850''>at</span>
  <span m=''1159330''>least</span> <span m=''1159550''>in</span> <span m=''1159620''>the</span>
  <span m=''1159710''>current</span> <span m=''1159990''>economic</span> <span m=''1160480''>state</span>
  <span m=''1160660''>of</span> <span m=''1160740''>affairs,</span> <span m=''1161340''>ten
  to</span> <span m=''1161510''>the</span> <span m=''1161630''>fourteenth</span> <span
  m=''1162130''>pieces</span> <span m=''1162330''>of</span> <span m=''1162440''>memory</span>
  <span m=''1162800''>is</span> <span m=''1162900''>expensive.</span> <span m=''1164200''>And</span>
  <span m=''1164430''>so</span> <span m=''1165270''>I</span> <span m=''1165410''>suppose</span>
  <span m=''1165840''>what</span> <span m=''1165970''>we</span> <span m=''1166090''>have</span>
  <span m=''1166280''>to</span> <span m=''1166380''>do</span> <span m=''1166820''>is</span>
  <span m=''1167030''>make</span> <span m=''1167280''>do</span> <span m=''1167420''>with</span>
  <span m=''1167590''>much</span> <span m=''1167860''>smaller.</span> <span m=''1168120''>Memories</span>
  </p><p><span m=''1170170''>Now</span> <span m=''1172900''>in</span> <span m=''1173040''>general</span>
  <span m=''1173380''>we</span> <span m=''1173550''>want</span> <span m=''1173650''>to</span>
  <span m=''1173760''>have</span> <span m=''1173940''>an</span> <span m=''1174000''>illusion</span>
  <span m=''1174380''>of</span> <span m=''1174470''>infinity.</span> <span m=''1175800''>All</span>
  <span m=''1176010''>we</span> <span m=''1176140''>need</span> <span m=''1176280''>to</span>
  <span m=''1176420''>do</span> <span m=''1176620''>is</span> <span m=''1176740''>arrange</span>
  <span m=''1177130''>it</span> <span m=''1177760''>so</span> <span m=''1178000''>that</span>
  <span m=''1178140''>whenever</span> <span m=''1178460''>you</span> <span m=''1178630''>look,</span>
  <span m=''1178850''>the</span> <span m=''1178960''>thing</span> <span m=''1179170''>is</span>
  <span m=''1179310''>there.</span> <span m=''1182670''>That''s</span> <span m=''1183430''>really</span>
  <span m=''1184250''>an</span> <span m=''1184310''>important</span> <span m=''1184850''>idea.</span>
  <span m=''1189540''>A</span> <span m=''1189660''>person</span> <span m=''1190010''>or
  a</span> <span m=''1190150''>computer</span> <span m=''1190510''>lives</span> <span
  m=''1190760''>only</span> <span m=''1190960''>a</span> <span m=''1191110''>finite</span>
  <span m=''1191260''>amount</span> <span m=''1191410''>of</span> <span m=''1191590''>time</span>
  <span m=''1192470''>and</span> <span m=''1192530''>can</span> <span m=''1192660''>only</span>
  <span m=''1192830''>take</span> <span m=''1192970''>a</span> <span m=''1193010''>finite</span>
  <span m=''1193290''>number</span> <span m=''1193490''>of</span> <span m=''1193570''>looks</span>
  <span m=''1193850''>at</span> <span m=''1194080''>something.</span> <span m=''1195280''>And</span>
  <span m=''1195470''>so</span> <span m=''1195560''>you</span> <span m=''1195690''>really</span>
  <span m=''1195900''>only</span> <span m=''1196130''>need</span> <span m=''1196320''>a</span>
  <span m=''1196370''>finite</span> <span m=''1196700''>amount</span> <span m=''1196920''>of</span>
  <span m=''1196970''>stuff.</span> <span m=''1198190''>But</span> <span m=''1198390''>you
  have</span> <span m=''1198510''>to</span> <span m=''1198580''>arrange</span> <span
  m=''1198920''>it</span> <span m=''1199050''>so</span> <span m=''1199170''>no</span>
  <span m=''1199270''>matter</span> <span m=''1199420''>how</span> <span m=''1199590''>much</span>
  <span m=''1199800''>there</span> <span m=''1200030''>is,</span> <span m=''1201730''>how</span>
  <span m=''1201840''>much</span> <span m=''1202010''>you</span> <span m=''1202120''>really</span>
  <span m=''1202400''>claim</span> <span m=''1202740''>there</span> <span m=''1202980''>is,</span>
  <span m=''1203300''>there''s</span> <span m=''1203690''>always</span> <span m=''1204000''>enough</span>
  <span m=''1204230''>stuff</span> <span m=''1204650''>so</span> <span m=''1205020''>that</span>
  <span m=''1205120''>when</span> <span m=''1205240''>you</span> <span m=''1205310''>take</span>
  <span m=''1205470''>a</span> <span m=''1205530''>look,</span> <span m=''1206430''>it''s</span>
  <span m=''1206630''>there.</span> <span m=''1206900''>And</span> <span m=''1206990''>so
  you</span> <span m=''1207140''>only need</span> <span m=''1207390''>a</span> <span
  m=''1207450''>finite</span> <span m=''1207750''>amount.</span> </p><p><span m=''1208750''>But</span>
  <span m=''1209370''>let''s</span> <span m=''1209640''>see.</span> <span m=''1211630''>One</span>
  <span m=''1211850''>problem</span> <span m=''1212260''>is,</span> <span m=''1212450''>as</span>
  <span m=''1212750''>was</span> <span m=''1212950''>brought</span> <span m=''1213180''>up,</span>
  <span m=''1213500''>that</span> <span m=''1214160''>there</span> <span m=''1214350''>are</span>
  <span m=''1214530''>possible</span> <span m=''1214980''>ways</span> <span m=''1216540''>that</span>
  <span m=''1217160''>there</span> <span m=''1217300''>is</span> <span m=''1217350''>lots</span>
  <span m=''1217610''>of</span> <span m=''1217680''>stuff</span> <span m=''1217920''>that</span>
  <span m=''1218030''>we</span> <span m=''1218150''>make</span> <span m=''1218440''>that</span>
  <span m=''1218560''>we</span> <span m=''1218660''>don''t</span> <span m=''1218830''>need.</span>
  <span m=''1219410''>And</span> <span m=''1219510''>we</span> <span m=''1219610''>could</span>
  <span m=''1219760''>recycle</span> <span m=''1220290''>the</span> <span m=''1220360''>material</span>
  <span m=''1220790''>out of</span> <span m=''1221000''>which</span> <span m=''1221220''>its</span>
  <span m=''1221390''>made.</span> <span m=''1222760''>An</span> <span m=''1222870''>example</span>
  <span m=''1224940''>is</span> <span m=''1225150''>the</span> <span m=''1225580''>fact</span>
  <span m=''1225780''>that</span> <span m=''1225970''>we''re</span> <span m=''1226300''>building</span>
  <span m=''1227370''>environment</span> <span m=''1227820''>structures,</span> <span
  m=''1228430''>and</span> <span m=''1228540''>we</span> <span m=''1228650''>do</span>
  <span m=''1228830''>so</span> <span m=''1229040''>every</span> <span m=''1229370''>time</span>
  <span m=''1229600''>we</span> <span m=''1229720''>call</span> <span m=''1229920''>a</span>
  <span m=''1229980''>procedure.</span> <span m=''1230470''>We</span> <span m=''1230660''>have
  built</span> <span m=''1230930''>in</span> <span m=''1231170''>it a</span> <span
  m=''1231640''>environment</span> <span m=''1232090''>frame.</span> <span m=''1232810''>That</span>
  <span m=''1233400''>environment</span> <span m=''1233820''>frame</span> <span m=''1234250''>doesn''t</span>
  <span m=''1234530''>necessarily</span> <span m=''1234840''>have</span> <span m=''1234970''>a</span>
  <span m=''1235000''>very</span> <span m=''1235240''>long</span> <span m=''1235510''>lifetime.</span>
  <span m=''1236730''>Its</span> <span m=''1237290''>lifetime,</span> <span m=''1237570''>meaning</span>
  <span m=''1237810''>its</span> <span m=''1237960''>usefulness,</span> <span m=''1239250''>may</span>
  <span m=''1239730''>exist</span> <span m=''1240050''>only</span> <span m=''1240330''>over</span>
  <span m=''1240880''>the</span> <span m=''1241360''>invocation</span> <span m=''1241890''>of</span>
  <span m=''1241940''>the</span> <span m=''1242010''>procedure.</span> <span m=''1242850''>Or</span>
  <span m=''1243170''>if the</span> <span m=''1243260''>procedure</span> <span m=''1244040''>exports</span>
  <span m=''1244500''>another</span> <span m=''1244750''>procedure</span> <span m=''1245200''>by</span>
  <span m=''1245400''>returning</span> <span m=''1245860''>it as</span> <span m=''1246040''>a</span>
  <span m=''1246100''>value</span> <span m=''1246470''>and</span> <span m=''1246840''>that</span>
  <span m=''1247200''>procedure</span> <span m=''1247480''>is</span> <span m=''1247680''>defined</span>
  <span m=''1247880''>inside</span> <span m=''1248200''>of</span> <span m=''1248260''>it,</span>
  <span m=''1248540''>well</span> <span m=''1249010''>then</span> <span m=''1249630''>the</span>
  <span m=''1249810''>lifetime</span> <span m=''1250400''>of</span> <span m=''1250550''>the</span>
  <span m=''1250990''>frame</span> <span m=''1251410''>of</span> <span m=''1251560''>the</span>
  <span m=''1251980''>outer</span> <span m=''1252210''>procedure</span> <span m=''1252720''>still</span>
  <span m=''1253070''>is</span> <span m=''1253530''>only</span> <span m=''1253810''>the</span>
  <span m=''1253910''>lifetime</span> <span m=''1254350''>of</span> <span m=''1254400''>the</span>
  <span m=''1255600''>procedure</span> <span m=''1257070''>which</span> <span m=''1257230''>was</span>
  <span m=''1257350''>exported.</span> </p><p><span m=''1258530''>And</span> <span
  m=''1258710''>so</span> <span m=''1258910''>ultimately,</span> <span m=''1259660''>a</span>
  <span m=''1259800''>lot</span> <span m=''1259940''>of</span> <span m=''1260080''>that</span>
  <span m=''1260230''>is</span> <span m=''1260380''>garbage.</span> <span m=''1261960''>There</span>
  <span m=''1262180''>are</span> <span m=''1262230''>other</span> <span m=''1262450''>ways</span>
  <span m=''1262730''>of</span> <span m=''1262810''>producing</span> <span m=''1263210''>garbage</span>
  <span m=''1263590''>as</span> <span m=''1263690''>well.</span> <span m=''1265370''>Users</span>
  <span m=''1265860''>produce</span> <span m=''1266190''>garbage.</span> <span m=''1267240''>An</span>
  <span m=''1267380''>example</span> <span m=''1268230''>of</span> <span m=''1268490''>user</span>
  <span m=''1268810''>garbage</span> <span m=''1269230''>is</span> <span m=''1269310''>something</span>
  <span m=''1269580''>like</span> <span m=''1269810''>this.</span> <span m=''1270930''>If</span>
  <span m=''1271070''>we</span> <span m=''1271180''>write</span> <span m=''1271370''>a</span>
  <span m=''1271860''>program</span> <span m=''1272870''>to,</span> <span m=''1273310''>for</span>
  <span m=''1273480''>example,</span> <span m=''1274040''>append</span> <span m=''1274500''>two</span>
  <span m=''1274870''>lists</span> <span m=''1275220''>together,</span> <span m=''1276060''>well</span>
  <span m=''1276280''>one</span> <span m=''1276460''>way</span> <span m=''1276600''>to</span>
  <span m=''1276730''>do</span> <span m=''1276970''>it</span> <span m=''1277560''>is</span>
  <span m=''1277790''>to</span> <span m=''1278420''>reverse</span> <span m=''1279120''>the</span>
  <span m=''1279590''>first</span> <span m=''1279890''>list</span> <span m=''1280140''>onto</span>
  <span m=''1280740''>the</span> <span m=''1280850''>empty</span> <span m=''1281120''>list</span>
  <span m=''1281440''>and</span> <span m=''1281590''>reverse</span> <span m=''1282020''>that</span>
  <span m=''1282680''>onto</span> <span m=''1283020''>the</span> <span m=''1283230''>second</span>
  <span m=''1283440''>list.</span> <span m=''1284760''>Now</span> <span m=''1284950''>that''s</span>
  <span m=''1285240''>not</span> <span m=''1285500''>terribly</span> <span m=''1285910''>bad</span>
  <span m=''1286170''>way</span> <span m=''1286320''>of</span> <span m=''1286410''>doing</span>
  <span m=''1286690''>it.</span> <span m=''1288160''>And</span> <span m=''1288350''>however,</span>
  <span m=''1288830''>the</span> <span m=''1289170''>intermediate</span> <span m=''1289670''>result,</span>
  <span m=''1290100''>which</span> <span m=''1290260''>is</span> <span m=''1290340''>the</span>
  <span m=''1290440''>reversal</span> <span m=''1291070''>of</span> <span m=''1291190''>the</span>
  <span m=''1291280''>first</span> <span m=''1291620''>list</span> <span m=''1293970''>as</span>
  <span m=''1294310''>done</span> <span m=''1294540''>by</span> <span m=''1294690''>this</span>
  <span m=''1294880''>program,</span> <span m=''1296800''>is</span> <span m=''1296970''>never</span>
  <span m=''1297200''>going</span> <span m=''1297300''>to</span> <span m=''1297390''>be</span>
  <span m=''1297540''>accessed</span> <span m=''1297990''>ever</span> <span m=''1298270''>again</span>
  <span m=''1298590''>after</span> <span m=''1298900''>it''s</span> <span m=''1299020''>copied</span>
  <span m=''1299380''>back</span> <span m=''1299700''>on</span> <span m=''1299840''>to</span>
  <span m=''1299920''>the</span> <span m=''1300200''>second.</span> <span m=''1301010''>It''s</span>
  <span m=''1301150''>an</span> <span m=''1301250''>intermediate</span> <span m=''1301700''>result.</span>
  <span m=''1303580''>It''s</span> <span m=''1303740''>going</span> <span m=''1303860''>to</span>
  <span m=''1303980''>be</span> <span m=''1304390''>hard</span> <span m=''1304700''>to</span>
  <span m=''1304780''>ever</span> <span m=''1304990''>see</span> <span m=''1306120''>how</span>
  <span m=''1306340''>anybody</span> <span m=''1306750''>would</span> <span m=''1306870''>ever</span>
  <span m=''1307070''>be</span> <span m=''1307230''>able</span> <span m=''1307330''>to</span>
  <span m=''1307400''>access</span> <span m=''1307820''>it.</span> <span m=''1308600''>In</span>
  <span m=''1308680''>fact,</span> <span m=''1308930''>it</span> <span m=''1309060''>will</span>
  <span m=''1309200''>go</span> <span m=''1309420''>away.</span> </p><p><span m=''1311050''>Now</span>
  <span m=''1311280''>if</span> <span m=''1311360''>we</span> <span m=''1311470''>make</span>
  <span m=''1311670''>a</span> <span m=''1311730''>lot</span> <span m=''1311920''>of</span>
  <span m=''1312020''>garbage</span> <span m=''1312410''>like</span> <span m=''1312680''>that,</span>
  <span m=''1312920''>and</span> <span m=''1313110''>we</span> <span m=''1313190''>should</span>
  <span m=''1313370''>be</span> <span m=''1313460''>allowed</span> <span m=''1313800''>to,</span>
  <span m=''1314650''>then</span> <span m=''1315010''>there''s</span> <span m=''1315460''>got</span>
  <span m=''1315570''>to</span> <span m=''1315680''>be</span> <span m=''1315810''>some</span>
  <span m=''1316010''>way</span> <span m=''1316110''>to</span> <span m=''1316210''>reclaim</span>
  <span m=''1316650''>that</span> <span m=''1316860''>garbage.</span> <span m=''1318800''>Well,</span>
  <span m=''1319440''>what</span> <span m=''1319780''>I''d like to</span> <span m=''1319860''>tell</span>
  <span m=''1320050''>you</span> <span m=''1320170''>about</span> <span m=''1320440''>now</span>
  <span m=''1321780''>is</span> <span m=''1322040''>a</span> <span m=''1322470''>very</span>
  <span m=''1322730''>clever</span> <span m=''1323050''>technique</span> <span m=''1324390''>whereby</span>
  <span m=''1326770''>a</span> <span m=''1326880''>Lisp</span> <span m=''1327150''>system</span>
  <span m=''1328010''>can</span> <span m=''1328320''>prove</span> <span m=''1329330''>a</span>
  <span m=''1329480''>small</span> <span m=''1329820''>theorem</span> <span m=''1330350''>every</span>
  <span m=''1330600''>so</span> <span m=''1330800''>often</span> <span m=''1331320''>on</span>
  <span m=''1331430''>the</span> <span m=''1331550''>[? forum, ?]</span> <span m=''1331970''>the</span>
  <span m=''1332330''>following</span> <span m=''1332750''>piece</span> <span m=''1332980''>of</span>
  <span m=''1333100''>junk</span> <span m=''1334830''>will</span> <span m=''1335020''>never</span>
  <span m=''1335260''>be</span> <span m=''1335420''>accessed</span> <span m=''1335860''>again.</span>
  <span m=''1337410''>It</span> <span m=''1337550''>can</span> <span m=''1337670''>have</span>
  <span m=''1337890''>no</span> <span m=''1338140''>affect</span> <span m=''1338450''>on</span>
  <span m=''1338540''>the</span> <span m=''1338630''>future</span> <span m=''1338930''>of</span>
  <span m=''1338990''>the</span> <span m=''1339060''>computation.</span> <span m=''1341400''>It''s</span>
  <span m=''1341960''>actually</span> <span m=''1342290''>based</span> <span m=''1342560''>on</span>
  <span m=''1342650''>a</span> <span m=''1342690''>very</span> <span m=''1342910''>simple</span>
  <span m=''1343230''>idea.</span> </p><p><span m=''1344920''>We''ve</span> <span
  m=''1345150''>designed</span> <span m=''1345560''>our</span> <span m=''1345720''>computers</span>
  <span m=''1346410''>to</span> <span m=''1346690''>look</span> <span m=''1346950''>sort</span>
  <span m=''1347080''>of</span> <span m=''1347210''>like</span> <span m=''1347460''>this.</span>
  <span m=''1348570''>There''s</span> <span m=''1349260''>some</span> <span m=''1350060''>data</span>
  <span m=''1350340''>path,</span> <span m=''1352010''>which</span> <span m=''1352200''>contains</span>
  <span m=''1352620''>the</span> <span m=''1352700''>registers.</span> <span m=''1355280''>There
  are things</span> <span m=''1355550''>like</span> <span m=''1355730''>x,</span>
  <span m=''1357390''>and</span> <span m=''1357645''>env,</span> <span m=''1359170''>and</span>
  <span m=''1359590''>val,</span> <span m=''1360830''>and</span> <span m=''1361340''>so</span>
  <span m=''1361840''>on.</span> <span m=''1362610''>And</span> <span m=''1362820''>there''s</span>
  <span m=''1362940''>one</span> <span m=''1363100''>here</span> <span m=''1363260''>called</span>
  <span m=''1363560''>stack,</span> <span m=''1366170''>some</span> <span m=''1366410''>sort</span>
  <span m=''1366870''>which</span> <span m=''1367150''>points</span> <span m=''1367490''>off</span>
  <span m=''1367710''>to</span> <span m=''1368370''>a</span> <span m=''1368490''>structure</span>
  <span m=''1369030''>somewhere,</span> <span m=''1369540''>which</span> <span m=''1369690''>is</span>
  <span m=''1369780''>the</span> <span m=''1369870''>stack.</span> <span m=''1370240''>And</span>
  <span m=''1370320''>we''ll</span> <span m=''1370430''>worry</span> <span m=''1370610''>about
  that in</span> <span m=''1370830''>a</span> <span m=''1370960''>second.</span> <span
  m=''1371740''>There''s</span> <span m=''1371860''>some</span> <span m=''1372070''>finite</span>
  <span m=''1372890''>controller,</span> <span m=''1374300''>finite</span> <span m=''1374900''>state</span>
  <span m=''1375390''>machine</span> <span m=''1375910''>controller.</span> <span
  m=''1376730''>And there''s some</span> <span m=''1377180''>control</span> <span
  m=''1377580''>signals</span> <span m=''1377970''>that</span> <span m=''1378050''>go</span>
  <span m=''1378210''>this</span> <span m=''1378450''>way</span> <span m=''1378970''>and</span>
  <span m=''1379850''>predicate</span> <span m=''1380240''>results</span> <span m=''1380640''>that</span>
  <span m=''1380740''>come</span> <span m=''1380940''>this</span> <span m=''1381130''>way,</span>
  <span m=''1381970''>not</span> <span m=''1382270''>the</span> <span m=''1382380''>interesting</span>
  <span m=''1382790''>part.</span> </p><p><span m=''1384260''>There''s</span> <span
  m=''1384400''>some</span> <span m=''1384610''>sort</span> <span m=''1385090''>of</span>
  <span m=''1385340''>structured</span> <span m=''1385900''>memory,</span> <span m=''1386820''>which</span>
  <span m=''1387070''>I</span> <span m=''1387140''>just</span> <span m=''1387320''>told</span>
  <span m=''1387530''>you</span> <span m=''1387600''>how</span> <span m=''1387730''>to</span>
  <span m=''1387800''>make,</span> <span m=''1388370''>which</span> <span m=''1388600''>may</span>
  <span m=''1388780''>contain</span> <span m=''1389600''>a</span> <span m=''1389680''>stack.</span>
  <span m=''1390460''>I</span> <span m=''1390570''>didn''t</span> <span m=''1390750''>tell</span>
  <span m=''1390880''>you</span> <span m=''1390960''>how</span> <span m=''1391050''>to</span>
  <span m=''1391130''>make</span> <span m=''1391330''>things</span> <span m=''1391560''>of</span>
  <span m=''1391620''>arbitrary</span> <span m=''1392120''>shape,</span> <span m=''1392690''>only</span>
  <span m=''1392940''>pairs.</span> <span m=''1393450''>But</span> <span m=''1393790''>in</span>
  <span m=''1393930''>fact</span> <span m=''1394290''>with</span> <span m=''1394500''>what</span>
  <span m=''1394670''>I''ve</span> <span m=''1394850''>told</span> <span m=''1395100''>you</span>
  <span m=''1395310''>can</span> <span m=''1395400''>simulate</span> <span m=''1395850''>a</span>
  <span m=''1395970''>stack</span> <span m=''1396280''>by</span> <span m=''1396420''>a</span>
  <span m=''1396490''>big</span> <span m=''1396680''>list.</span> <span m=''1397800''>I</span>
  <span m=''1397890''>don''t</span> <span m=''1398120''>plan</span> <span m=''1398350''>to</span>
  <span m=''1398430''>do</span> <span m=''1398590''>that,</span> <span m=''1398820''>it''s</span>
  <span m=''1398920''>not</span> <span m=''1399070''>a</span> <span m=''1399140''>nice</span>
  <span m=''1399420''>way</span> <span m=''1399530''>to</span> <span m=''1399640''>do</span>
  <span m=''1399850''>it.</span> <span m=''1400360''>But</span> <span m=''1400580''>we</span>
  <span m=''1400690''>could</span> <span m=''1401650''>have</span> <span m=''1401780''>something</span>
  <span m=''1402060''>like</span> <span m=''1402300''>that.</span> <span m=''1402990''>We</span>
  <span m=''1403150''>have</span> <span m=''1403270''>all</span> <span m=''1403500''>sorts</span>
  <span m=''1403680''>of</span> <span m=''1403780''>little</span> <span m=''1403980''>data</span>
  <span m=''1404230''>structures</span> <span m=''1404740''>in</span> <span m=''1404910''>here</span>
  <span m=''1405880''>that are</span> <span m=''1406100''>hooked</span> <span m=''1406310''>together</span>
  <span m=''1406700''>in</span> <span m=''1406780''>funny</span> <span m=''1407090''>ways.</span>
  <span m=''1410115''>They</span> <span m=''1410570''>connect</span> <span m=''1411030''>to</span>
  <span m=''1411100''>other</span> <span m=''1411290''>things.</span> <span m=''1412560''>And</span>
  <span m=''1412720''>so</span> <span m=''1412990''>on.</span> <span m=''1413250''>And</span>
  <span m=''1413610''>ultimately</span> <span m=''1414420''>things</span> <span m=''1414980''>up</span>
  <span m=''1415140''>there</span> <span m=''1415750''>are</span> <span m=''1415910''>pointers</span>
  <span m=''1416390''>to</span> <span m=''1416500''>these.</span> <span m=''1417190''>The</span>
  <span m=''1417300''>things</span> <span m=''1417540''>that are</span> <span m=''1417700''>in</span>
  <span m=''1417800''>the</span> <span m=''1417890''>registers</span> <span m=''1419410''>are</span>
  <span m=''1419550''>pointers</span> <span m=''1420020''>off</span> <span m=''1420280''>to</span>
  <span m=''1420730''>the</span> <span m=''1421010''>data</span> <span m=''1421210''>structures</span>
  <span m=''1421640''>that</span> <span m=''1421690''>live</span> <span m=''1421900''>in</span>
  <span m=''1422000''>this</span> <span m=''1422220''>Lisp</span> <span m=''1422400''>structure</span>
  <span m=''1422790''>memory.</span> </p><p><span m=''1424910''>Now</span> <span m=''1428630''>the</span>
  <span m=''1428790''>truth</span> <span m=''1429060''>of</span> <span m=''1429130''>the</span>
  <span m=''1429200''>matter</span> <span m=''1429530''>is</span> <span m=''1431010''>that</span>
  <span m=''1431210''>the</span> <span m=''1431720''>entire</span> <span m=''1432110''>consciousness</span>
  <span m=''1432660''>of this</span> <span m=''1432870''>machine is</span> <span m=''1433290''>in</span>
  <span m=''1433360''>these</span> <span m=''1433520''>registers.</span> <span m=''1435550''>There</span>
  <span m=''1436000''>is</span> <span m=''1436100''>no</span> <span m=''1436320''>possible</span>
  <span m=''1436780''>way</span> <span m=''1437460''>that</span> <span m=''1437820''>the</span>
  <span m=''1437900''>machine,</span> <span m=''1438830''>if</span> <span m=''1439020''>done</span>
  <span m=''1439380''>correctly,</span> <span m=''1440160''>if</span> <span m=''1440310''>built</span>
  <span m=''1440560''>correctly,</span> <span m=''1441370''>can</span> <span m=''1441560''>access</span>
  <span m=''1441990''>anything</span> <span m=''1442350''>in this</span> <span m=''1442410''>Lisp</span>
  <span m=''1442650''>structure</span> <span m=''1442980''>memory</span> <span m=''1444530''>unless</span>
  <span m=''1444970''>the</span> <span m=''1445060''>thing</span> <span m=''1445250''>in
  that</span> <span m=''1445410''>Lisp</span> <span m=''1445580''>structure</span>
  <span m=''1445950''>memory</span> <span m=''1448130''>is</span> <span m=''1448310''>connected</span>
  <span m=''1448880''>by</span> <span m=''1449040''>a</span> <span m=''1449130''>sequence</span>
  <span m=''1449860''>of</span> <span m=''1450070''>data</span> <span m=''1450310''>structures</span>
  <span m=''1452210''>to</span> <span m=''1452410''>the</span> <span m=''1452500''>registers.</span>
  <span m=''1455070''>If it''s</span> <span m=''1455290''>accessible</span> <span
  m=''1456010''>by</span> <span m=''1456470''>legitimate</span> <span m=''1456980''>data
  structure</span> <span m=''1457550''>selectors</span> <span m=''1458890''>from</span>
  <span m=''1459190''>the</span> <span m=''1459500''>pointers</span> <span m=''1459940''>that
  are</span> <span m=''1460100''>stored</span> <span m=''1460330''>in these</span>
  <span m=''1460560''>registers.</span> <span m=''1462280''>Things</span> <span m=''1462530''>like</span>
  <span m=''1463050''>array</span> <span m=''1463350''>references,</span> <span m=''1463890''>perhaps.</span>
  <span m=''1464940''>Or</span> <span m=''1466080''>cons</span> <span m=''1466350''>cell</span>
  <span m=''1466610''>references,</span> <span m=''1467100''>cars and</span> <span
  m=''1467490''>cdrs.</span> </p><p><span m=''1468790''>But</span> <span m=''1469200''>I</span>
  <span m=''1469330''>can''t just</span> <span m=''1469640''>talk</span> <span m=''1469830''>about
  a</span> <span m=''1470020''>random</span> <span m=''1470260''>place in this</span>
  <span m=''1470710''>memory,</span> <span m=''1470970''>because</span> <span m=''1471130''>I</span>
  <span m=''1471180''>can''t</span> <span m=''1471440''>get</span> <span m=''1471630''>to</span>
  <span m=''1471770''>it.</span> <span m=''1472740''>These</span> <span m=''1472990''>are</span>
  <span m=''1473040''>being</span> <span m=''1473250''>arbitrary</span> <span m=''1473500''>names</span>
  <span m=''1474020''>I''m not</span> <span m=''1474130''>allowed</span> <span m=''1474430''>to
  count,</span> <span m=''1476580''>at</span> <span m=''1477140''>least</span> <span
  m=''1477650''>as</span> <span m=''1477840''>I''m</span> <span m=''1478050''>evaluating</span>
  <span m=''1478630''>expressions.</span> <span m=''1481620''>If</span> <span m=''1481800''>that''s</span>
  <span m=''1482090''>the</span> <span m=''1482190''>case</span> <span m=''1483510''>then</span>
  <span m=''1483640''>there''s</span> <span m=''1483820''>a</span> <span m=''1483870''>very</span>
  <span m=''1484070''>simple</span> <span m=''1484370''>theorem</span> <span m=''1484600''>to</span>
  <span m=''1484680''>be</span> <span m=''1484790''>proved.</span> <span m=''1487160''>Which</span>
  <span m=''1487390''>is,</span> <span m=''1487940''>if</span> <span m=''1488110''>I</span>
  <span m=''1488220''>start</span> <span m=''1488520''>with</span> <span m=''1488640''>all</span>
  <span m=''1488860''>lead</span> <span m=''1489030''>pointers</span> <span m=''1489390''>that
  are in</span> <span m=''1489590''>all</span> <span m=''1489730''>these</span> <span
  m=''1489870''>registers</span> <span m=''1491210''>and</span> <span m=''1491370''>recursively</span>
  <span m=''1491950''>chase</span> <span m=''1492250''>out,</span> <span m=''1492850''>marking</span>
  <span m=''1493570''>all</span> <span m=''1493740''>the</span> <span m=''1493910''>places</span>
  <span m=''1494180''>I</span> <span m=''1494260''>can</span> <span m=''1494450''>get</span>
  <span m=''1494660''>to</span> <span m=''1495240''>by</span> <span m=''1495490''>selectors,</span>
  <span m=''1496960''>then</span> <span m=''1497090''>eventually</span> <span m=''1497860''>I</span>
  <span m=''1497980''>mark</span> <span m=''1498240''>everything</span> <span m=''1498600''>they</span>
  <span m=''1498680''>can</span> <span m=''1498820''>be</span> <span m=''1498900''>gotten</span>
  <span m=''1499180''>to.</span> <span m=''1500750''>Anything</span> <span m=''1501000''>which</span>
  <span m=''1501160''>is</span> <span m=''1501240''>not</span> <span m=''1501490''>so</span>
  <span m=''1501660''>marked</span> <span m=''1502000''>is</span> <span m=''1502140''>garbage</span>
  <span m=''1502470''>and</span> <span m=''1502800''>can</span> <span m=''1503010''>be</span>
  <span m=''1503120''>recycled.</span> <span m=''1505560''>Very</span> <span m=''1505790''>simple.</span>
  <span m=''1507200''>Cannot</span> <span m=''1507630''>affect</span> <span m=''1507880''>the</span>
  <span m=''1507940''>future of</span> <span m=''1508230''>the</span> <span m=''1508350''>computation.</span>
  </p><p><span m=''1511180''>So</span> <span m=''1511340''>let</span> <span m=''1511440''>me</span>
  <span m=''1511500''>show</span> <span m=''1511660''>you</span> <span m=''1511820''>that</span>
  <span m=''1512070''>in</span> <span m=''1512170''>a</span> <span m=''1512230''>particular</span>
  <span m=''1515120''>example.</span> <span m=''1516616''>Now</span> <span m=''1517070''>that</span>
  <span m=''1517400''>means</span> <span m=''1517550''>I''m going</span> <span m=''1517680''>to</span>
  <span m=''1517810''>have</span> <span m=''1517970''>to</span> <span m=''1518360''>append</span>
  <span m=''1518770''>to</span> <span m=''1518970''>my</span> <span m=''1519800''>description</span>
  <span m=''1520290''>of</span> <span m=''1520370''>the</span> <span m=''1520440''>list</span>
  <span m=''1520620''>structure</span> <span m=''1521710''>a</span> <span m=''1521810''>mark.</span>
  <span m=''1523640''>And</span> <span m=''1523790''>so</span> <span m=''1523940''>here,</span>
  <span m=''1524140''>for</span> <span m=''1524300''>example,</span> <span m=''1525410''>is</span>
  <span m=''1525710''>a</span> <span m=''1526250''>Lisp</span> <span m=''1526500''>structured</span>
  <span m=''1526910''>memory.</span> <span m=''1529080''>And</span> <span m=''1529290''>in</span>
  <span m=''1529390''>this</span> <span m=''1529490''>Lisp</span> <span m=''1529700''>structured</span>
  <span m=''1530060''>memory</span> <span m=''1530340''>is</span> <span m=''1530440''>a
  Lisp</span> <span m=''1530730''>structure</span> <span m=''1531360''>beginning</span>
  <span m=''1531740''>in</span> <span m=''1531840''>a</span> <span m=''1531890''>place</span>
  <span m=''1532200''>I''m</span> <span m=''1532320''>going</span> <span m=''1532430''>to</span>
  <span m=''1532540''>call--</span> <span m=''1535640''>this</span> <span m=''1536080''>is</span>
  <span m=''1536150''>the</span> <span m=''1536270''>root.</span> <span m=''1538590''>Now</span>
  <span m=''1538720''>it</span> <span m=''1538790''>doesn''t</span> <span m=''1539060''>really</span>
  <span m=''1539310''>have</span> <span m=''1539520''>to</span> <span m=''1539600''>have</span>
  <span m=''1539720''>a</span> <span m=''1539850''>root.</span> <span m=''1540120''>It
  could</span> <span m=''1540280''>be</span> <span m=''1540410''>a</span> <span m=''1540470''>bunch</span>
  <span m=''1540740''>of</span> <span m=''1540860''>them,</span> <span m=''1540970''>like</span>
  <span m=''1541170''>all</span> <span m=''1541280''>the</span> <span m=''1541390''>registers.</span>
  <span m=''1542670''>But</span> <span m=''1542820''>I</span> <span m=''1542910''>could</span>
  <span m=''1543050''>cleverly</span> <span m=''1543460''>arrange</span> <span m=''1543770''>it</span>
  <span m=''1544100''>so</span> <span m=''1544290''>all</span> <span m=''1544460''>the</span>
  <span m=''1544560''>registers,</span> <span m=''1545060''>all</span> <span m=''1545270''>the
  things that</span> <span m=''1545460''>are in</span> <span m=''1545660''>old</span>
  <span m=''1545820''>registers</span> <span m=''1546300''>are</span> <span m=''1546470''>also</span>
  <span m=''1546850''>at</span> <span m=''1546980''>the</span> <span m=''1547080''>right</span>
  <span m=''1547310''>moment</span> <span m=''1548310''>put</span> <span m=''1548470''>into</span>
  <span m=''1548700''>this</span> <span m=''1549610''>root</span> <span m=''1549830''>structure,</span>
  <span m=''1550460''>and</span> <span m=''1550670''>then we''ve</span> <span m=''1550770''>got</span>
  <span m=''1550960''>one</span> <span m=''1551150''>pointer</span> <span m=''1551470''>to</span>
  <span m=''1551660''>it.</span> <span m=''1551850''>I don''t</span> <span m=''1552000''>really</span>
  <span m=''1552270''>care.</span> </p><p><span m=''1554570''>So</span> <span m=''1554890''>the</span>
  <span m=''1555090''>idea</span> <span m=''1555460''>is</span> <span m=''1555630''>we''re</span>
  <span m=''1555750''>going</span> <span m=''1555860''>to</span> <span m=''1555970''>cons
  up</span> <span m=''1556440''>stuff</span> <span m=''1556690''>until</span> <span
  m=''1556990''>our</span> <span m=''1557110''>free</span> <span m=''1557290''>list</span>
  <span m=''1557520''>is</span> <span m=''1557620''>empty.</span> <span m=''1558720''>We''ve</span>
  <span m=''1558840''>run</span> <span m=''1559050''>out</span> <span m=''1559150''>of</span>
  <span m=''1559250''>things.</span> <span m=''1560950''>Now we''re going</span> <span
  m=''1561200''>to</span> <span m=''1561330''>do</span> <span m=''1561460''>this</span>
  <span m=''1561670''>process</span> <span m=''1563320''>of</span> <span m=''1563520''>proving</span>
  <span m=''1563870''>the</span> <span m=''1563960''>theorem</span> <span m=''1564560''>that</span>
  <span m=''1564700''>a</span> <span m=''1564740''>certain</span> <span m=''1565000''>percentage</span>
  <span m=''1565440''>of</span> <span m=''1565510''>the</span> <span m=''1565590''>memory</span>
  <span m=''1565910''>has</span> <span m=''1566030''>got</span> <span m=''1566390''>crap
  in it.</span> <span m=''1567850''>And</span> <span m=''1568060''>then we''re going
  to</span> <span m=''1568410''>recycle</span> <span m=''1568900''>that</span> <span
  m=''1569820''>to</span> <span m=''1569940''>grow</span> <span m=''1570170''>new</span>
  <span m=''1570320''>trees,</span> <span m=''1572140''>a</span> <span m=''1572220''>standard</span>
  <span m=''1572550''>use</span> <span m=''1572780''>of</span> <span m=''1573850''>such</span>
  <span m=''1574090''>garbage.</span> </p><p><span m=''1577090''>So</span> <span m=''1577360''>in</span>
  <span m=''1577490''>any</span> <span m=''1577670''>case,</span> <span m=''1577910''>what
  do</span> <span m=''1578030''>we</span> <span m=''1578220''>have</span> <span m=''1578420''>here?</span>
  <span m=''1578840''>Well</span> <span m=''1579050''>we</span> <span m=''1579150''>have</span>
  <span m=''1579750''>some</span> <span m=''1580010''>data</span> <span m=''1580250''>structure</span>
  <span m=''1580940''>which</span> <span m=''1581140''>starts</span> <span m=''1581540''>out</span>
  <span m=''1581700''>over</span> <span m=''1581820''>here</span> <span m=''1586190''>one.</span>
  <span m=''1587502''>And</span> <span m=''1587940''>in</span> <span m=''1588100''>fact</span>
  <span m=''1588970''>it</span> <span m=''1590600''>has a</span> <span m=''1590970''>car</span>
  <span m=''1591120''>in</span> <span m=''1591640''>five,</span> <span m=''1592310''>and</span>
  <span m=''1592530''>its</span> <span m=''1592700''>cdr</span> <span m=''1592950''>is</span>
  <span m=''1593050''>in two.</span> <span m=''1593980''>And</span> <span m=''1594190''>all</span>
  <span m=''1594400''>the</span> <span m=''1594480''>marks</span> <span m=''1594760''>start</span>
  <span m=''1595020''>out at</span> <span m=''1595250''>zero.</span> <span m=''1596700''>Well
  let''s</span> <span m=''1596870''>start</span> <span m=''1597140''>marking,</span>
  <span m=''1597900''>just</span> <span m=''1598080''>to</span> <span m=''1598160''>play</span>
  <span m=''1598350''>this</span> <span m=''1598540''>game.</span> <span m=''1599920''>OK.</span>
  <span m=''1602540''>So</span> <span m=''1603370''>for</span> <span m=''1603680''>example,</span>
  <span m=''1604420''>since</span> <span m=''1604670''>I</span> <span m=''1605180''>can</span>
  <span m=''1605310''>access</span> <span m=''1606210''>one</span> <span m=''1606540''>from</span>
  <span m=''1606680''>the</span> <span m=''1606780''>root</span> <span m=''1607000''>I</span>
  <span m=''1607090''>will</span> <span m=''1607240''>mark</span> <span m=''1607510''>that.</span>
  <span m=''1608390''>Let me</span> <span m=''1608610''>mark it.</span> <span m=''1610960''>Bang.</span>
  <span m=''1612430''>That''s</span> <span m=''1612580''>marked.</span> <span m=''1614560''>Now</span>
  <span m=''1616020''>since</span> <span m=''1616340''>I</span> <span m=''1616450''>have</span>
  <span m=''1616570''>a</span> <span m=''1616810''>five</span> <span m=''1617190''>here</span>
  <span m=''1617630''>I</span> <span m=''1617760''>can</span> <span m=''1617910''>go</span>
  <span m=''1618020''>to</span> <span m=''1618130''>five</span> <span m=''1619110''>and</span>
  <span m=''1619380''>see,</span> <span m=''1619920''>well I''ll</span> <span m=''1620120''>mark</span>
  <span m=''1620380''>that.</span> <span m=''1621450''>Bang.</span> <span m=''1621760''>That''s</span>
  <span m=''1621940''>useful</span> <span m=''1622250''>stuff.</span> </p><p><span
  m=''1622900''>But</span> <span m=''1623180''>five</span> <span m=''1623520''>references</span>
  <span m=''1624010''>as</span> <span m=''1624150''>a</span> <span m=''1624200''>number</span>
  <span m=''1624500''>in</span> <span m=''1624550''>its</span> <span m=''1624720''>car,</span>
  <span m=''1625310''>I''m not</span> <span m=''1625410''>interested</span> <span
  m=''1625750''>in</span> <span m=''1625850''>marking</span> <span m=''1626070''>numbers</span>
  <span m=''1626920''>but</span> <span m=''1627140''>its</span> <span m=''1627280''>cdr</span>
  <span m=''1627430''>is</span> <span m=''1627580''>seven.</span> <span m=''1628700''>So</span>
  <span m=''1628890''>I</span> <span m=''1628980''>can</span> <span m=''1629130''>mark</span>
  <span m=''1629380''>that.</span> <span m=''1630450''>Bang.</span> <span m=''1632260''>Seven</span>
  <span m=''1632660''>is</span> <span m=''1632770''>the</span> <span m=''1632870''>empty</span>
  <span m=''1633110''>list,</span> <span m=''1633730''>the</span> <span m=''1634070''>only
  thing that</span> <span m=''1634400''>references,</span> <span m=''1636000''>and
  it''s</span> <span m=''1636200''>got</span> <span m=''1636280''>a</span> <span m=''1636350''>number</span>
  <span m=''1636670''>in</span> <span m=''1636710''>its</span> <span m=''1636880''>car.</span>
  <span m=''1637120''>Not</span> <span m=''1637290''>interesting.</span> <span m=''1639490''>Well</span>
  <span m=''1639610''>now</span> <span m=''1639760''>let''s</span> <span m=''1639950''>go</span>
  <span m=''1640050''>back</span> <span m=''1640330''>here.</span> <span m=''1640500''>I</span>
  <span m=''1640550''>forgot</span> <span m=''1640880''>about</span> <span m=''1641150''>something.</span>
  <span m=''1641650''>Two.</span> <span m=''1642840''>See</span> <span m=''1643090''>in
  other words,</span> <span m=''1643630''>if I''m</span> <span m=''1643730''>looking</span>
  <span m=''1643960''>at</span> <span m=''1644070''>cell</span> <span m=''1644290''>one,</span>
  <span m=''1645390''>cell</span> <span m=''1645690''>one</span> <span m=''1645960''>contains</span>
  <span m=''1648210''>a</span> <span m=''1648380''>two</span> <span m=''1648670''>right</span>
  <span m=''1648870''>over</span> <span m=''1649020''>here.</span> <span m=''1650370''>A</span>
  <span m=''1650480''>reference</span> <span m=''1650850''>to</span> <span m=''1650970''>two.</span>
  <span m=''1651730''>That</span> <span m=''1652270''>means</span> <span m=''1652450''>I</span>
  <span m=''1652560''>should</span> <span m=''1652740''>go</span> <span m=''1653190''>mark</span>
  <span m=''1654530''>two.</span> <span m=''1655700''>Bang.</span> <span m=''1657140''>Two</span>
  <span m=''1657500''>contains a</span> <span m=''1657870''>reference</span> <span
  m=''1658320''>to</span> <span m=''1658420''>four.</span> <span m=''1658960''>It''s
  got a</span> <span m=''1659460''>number</span> <span m=''1659800''>in its</span>
  <span m=''1659990''>car,</span> <span m=''1660330''>I''m not interested</span> <span
  m=''1660760''>in</span> <span m=''1660860''>that,</span> <span m=''1661510''>so
  I''m going</span> <span m=''1661760''>to</span> <span m=''1661870''>go</span> <span
  m=''1662020''>mark</span> <span m=''1662280''>that.</span> <span m=''1663780''>Four</span>
  <span m=''1664420''>refers</span> <span m=''1664810''>to</span> <span m=''1664930''>seven</span>
  <span m=''1665290''>through</span> <span m=''1665480''>its</span> <span m=''1665620''>car,</span>
  <span m=''1666810''>and</span> <span m=''1667020''>is</span> <span m=''1667280''>empty</span>
  <span m=''1667420''>in</span> <span m=''1667590''>its</span> <span m=''1667840''>cdr,</span>
  <span m=''1668500''>but</span> <span m=''1668620''>I''ve</span> <span m=''1668760''>already</span>
  <span m=''1669010''>marked</span> <span m=''1669270''>that</span> <span m=''1669430''>one</span>
  <span m=''1669630''>so I don''t</span> <span m=''1669840''>have</span> <span m=''1669910''>to</span>
  <span m=''1669990''>mark it</span> <span m=''1670250''>again.</span> <span m=''1671400''>This</span>
  <span m=''1671720''>is</span> <span m=''1671840''>all</span> <span m=''1672100''>the</span>
  <span m=''1672250''>accessible</span> <span m=''1672630''>structure</span> <span
  m=''1673040''>from</span> <span m=''1673190''>that</span> <span m=''1673390''>place.</span>
  <span m=''1675000''>Simple</span> <span m=''1675400''>recursive</span> <span m=''1675720''>mark</span>
  <span m=''1675970''>algorithm.</span> </p><p><span m=''1678710''>Now</span> <span
  m=''1679130''>there</span> <span m=''1679490''>are</span> <span m=''1679550''>some</span>
  <span m=''1679850''>unhappinesses</span> <span m=''1680680''>about</span> <span
  m=''1681020''>that</span> <span m=''1681160''>algorithm,</span> <span m=''1681940''>and</span>
  <span m=''1682070''>we</span> <span m=''1682180''>can</span> <span m=''1682670''>worry</span>
  <span m=''1682950''>about</span> <span m=''1683210''>that</span> <span m=''1683430''>a</span>
  <span m=''1683490''>second.</span> <span m=''1684920''>But</span> <span m=''1685310''>basically</span>
  <span m=''1685860''>you''ll</span> <span m=''1686000''>see</span> <span m=''1686160''>that</span>
  <span m=''1686250''>all the</span> <span m=''1686560''>things</span> <span m=''1686800''>that</span>
  <span m=''1686900''>have</span> <span m=''1686990''>not</span> <span m=''1687280''>been</span>
  <span m=''1687410''>marked</span> <span m=''1689710''>are</span> <span m=''1690470''>places</span>
  <span m=''1690880''>that</span> <span m=''1691010''>are</span> <span m=''1691080''>free,</span>
  <span m=''1691450''>and</span> <span m=''1691550''>I</span> <span m=''1691650''>could</span>
  <span m=''1691790''>recycle.</span> <span m=''1694220''>So</span> <span m=''1694380''>the</span>
  <span m=''1694470''>next</span> <span m=''1694710''>stage</span> <span m=''1695010''>after</span>
  <span m=''1695200''>that</span> <span m=''1695330''>is</span> <span m=''1695450''>going</span>
  <span m=''1695590''>to be to</span> <span m=''1695720''>scan</span> <span m=''1696050''>through</span>
  <span m=''1696210''>all</span> <span m=''1696340''>of</span> <span m=''1696390''>my</span>
  <span m=''1696500''>memory,</span> <span m=''1698920''>looking</span> <span m=''1699220''>for</span>
  <span m=''1699330''>things</span> <span m=''1699570''>that</span> <span m=''1699650''>are</span>
  <span m=''1699740''>not</span> <span m=''1699970''>marked.</span> <span m=''1701180''>Every</span>
  <span m=''1701360''>time</span> <span m=''1701510''>I</span> <span m=''1701570''>come</span>
  <span m=''1701840''>across</span> <span m=''1702070''>a</span> <span m=''1702110''>marked</span>
  <span m=''1702500''>thing I</span> <span m=''1702730''>unmark it,</span> <span m=''1703240''>and</span>
  <span m=''1703370''>every time</span> <span m=''1703480''>I come</span> <span m=''1703840''>across</span>
  <span m=''1704070''>an</span> <span m=''1704150''>unmarked</span> <span m=''1704600''>thing</span>
  <span m=''1705120''>I''m</span> <span m=''1705340''>going to</span> <span m=''1706390''>link</span>
  <span m=''1706660''>it</span> <span m=''1706750''>together</span> <span m=''1707070''>in</span>
  <span m=''1707160''>my</span> <span m=''1707290''>free</span> <span m=''1707520''>list.</span>
  <span m=''1708770''>Classic,</span> <span m=''1709170''>very</span> <span m=''1709400''>simple</span>
  <span m=''1709700''>algorithm.</span> </p><p><span m=''1712120''>So</span> <span
  m=''1712450''>let''s</span> <span m=''1712730''>see.</span> <span m=''1713840''>Is</span>
  <span m=''1713950''>that</span> <span m=''1714160''>very</span> <span m=''1714400''>simple?</span>
  <span m=''1714770''>Yes</span> <span m=''1715040''>it</span> <span m=''1715130''>is.</span>
  <span m=''1715570''>I''m</span> <span m=''1715750''>not</span> <span m=''1715930''>going</span>
  <span m=''1716010''>to</span> <span m=''1716080''>go</span> <span m=''1716240''>through</span>
  <span m=''1716410''>the</span> <span m=''1716530''>code</span> <span m=''1716960''>in</span>
  <span m=''1717100''>any</span> <span m=''1717290''>detail,</span> <span m=''1718020''>but</span>
  <span m=''1718270''>I just want to show you</span> <span m=''1718690''>about</span>
  <span m=''1719000''>how</span> <span m=''1719120''>long</span> <span m=''1719390''>it</span>
  <span m=''1719570''>is.</span> <span m=''1720090''>Let''s</span> <span m=''1720300''>look</span>
  <span m=''1720370''>at</span> <span m=''1720440''>the</span> <span m=''1720520''>mark</span>
  <span m=''1720950''>phase.</span> <span m=''1722490''>Here''s</span> <span m=''1722650''>the</span>
  <span m=''1722830''>first</span> <span m=''1723010''>part</span> <span m=''1723210''>of</span>
  <span m=''1723260''>the</span> <span m=''1723320''>mark</span> <span m=''1723560''>phase.</span>
  <span m=''1725060''>We</span> <span m=''1725150''>pick</span> <span m=''1725350''>up</span>
  <span m=''1725480''>the</span> <span m=''1725610''>root.</span> <span m=''1728280''>We''re</span>
  <span m=''1728380''>going</span> <span m=''1728510''>to</span> <span m=''1729080''>use</span>
  <span m=''1729370''>that</span> <span m=''1729550''>as</span> <span m=''1729690''>a</span>
  <span m=''1729770''>recursive</span> <span m=''1730230''>procedure</span> <span
  m=''1730650''>call.</span> <span m=''1732380''>We''re</span> <span m=''1732510''>going</span>
  <span m=''1732600''>to</span> <span m=''1733480''>sweep</span> <span m=''1733870''>from</span>
  <span m=''1734100''>there,</span> <span m=''1734880''>after</span> <span m=''1735110''>when</span>
  <span m=''1735240''>we''re</span> <span m=''1735390''>done</span> <span m=''1735800''>with</span>
  <span m=''1736270''>marking.</span> <span m=''1737380''>And</span> <span m=''1737560''>then</span>
  <span m=''1737740''>we''re</span> <span m=''1737960''>going</span> <span m=''1738110''>to</span>
  <span m=''1738460''>do</span> <span m=''1738650''>a</span> <span m=''1738720''>little</span>
  <span m=''1738950''>couple of</span> <span m=''1739230''>instructions</span> <span
  m=''1739840''>that</span> <span m=''1740030''>do</span> <span m=''1740180''>this</span>
  <span m=''1740390''>checking</span> <span m=''1740760''>out</span> <span m=''1740910''>on</span>
  <span m=''1740980''>the</span> <span m=''1741060''>marks</span> <span m=''1741420''>and</span>
  <span m=''1741510''>changing</span> <span m=''1741850''>the</span> <span m=''1741920''>marks</span>
  <span m=''1742240''>and</span> <span m=''1742340''>things</span> <span m=''1742550''>like</span>
  <span m=''1742750''>that,</span> <span m=''1743120''>according</span> <span m=''1743470''>to</span>
  <span m=''1743520''>the</span> <span m=''1743630''>algorithm</span> <span m=''1744000''>I''ve</span>
  <span m=''1744100''>just</span> <span m=''1744350''>shown</span> <span m=''1744600''>you.</span>
  <span m=''1745500''>It</span> <span m=''1745640''>comes</span> <span m=''1745980''>out</span>
  <span m=''1746320''>here.</span> <span m=''1746470''>You have to</span> <span m=''1746540''>mark</span>
  <span m=''1746750''>the</span> <span m=''1746830''>cars</span> <span m=''1747180''>of</span>
  <span m=''1747280''>things</span> <span m=''1747940''>and</span> <span m=''1748130''>you</span>
  <span m=''1748330''>also</span> <span m=''1748560''>have</span> <span m=''1748660''>to</span>
  <span m=''1748740''>be able</span> <span m=''1748860''>to</span> <span m=''1748920''>mark</span>
  <span m=''1749190''>the</span> <span m=''1749290''>cdrs</span> <span m=''1749670''>of</span>
  <span m=''1749790''>things.</span> <span m=''1750660''>That''s</span> <span m=''1750920''>the</span>
  <span m=''1751050''>entire</span> <span m=''1751430''>mark</span> <span m=''1751730''>phase.</span>
  </p><p><span m=''1754370''>I''ll</span> <span m=''1754530''>just</span> <span m=''1754670''>tell
  you</span> <span m=''1754820''>a</span> <span m=''1754960''>little</span> <span
  m=''1755210''>story</span> <span m=''1755530''>about</span> <span m=''1755810''>this.</span>
  <span m=''1756590''>The</span> <span m=''1756870''>old</span> <span m=''1757170''>DEC</span>
  <span m=''1757990''>PDP-6</span> <span m=''1758750''>computer,</span> <span m=''1761010''>this</span>
  <span m=''1761200''>was</span> <span m=''1761360''>the</span> <span m=''1761410''>way</span>
  <span m=''1761700''>that</span> <span m=''1762730''>the</span> <span m=''1762950''>mark-sweep</span>
  <span m=''1763570''>garbage</span> <span m=''1763860''>collection,</span> <span
  m=''1764190''>as it was, was</span> <span m=''1764420''>written.</span> <span m=''1766740''>The</span>
  <span m=''1767060''>program</span> <span m=''1767550''>was</span> <span m=''1767710''>so</span>
  <span m=''1767900''>small</span> <span m=''1769000''>that</span> <span m=''1769740''>with</span>
  <span m=''1770040''>the</span> <span m=''1770130''>data</span> <span m=''1770560''>that</span>
  <span m=''1771080''>it</span> <span m=''1771190''>needed,</span> <span m=''1771940''>with</span>
  <span m=''1772230''>the</span> <span m=''1772480''>registers</span> <span m=''1772880''>that
  it</span> <span m=''1772970''>needed</span> <span m=''1773250''>to</span> <span
  m=''1773360''>manipulate</span> <span m=''1774060''>the</span> <span m=''1774310''>memory,</span>
  <span m=''1776190''>it</span> <span m=''1776390''>fit</span> <span m=''1776580''>into</span>
  <span m=''1776740''>the</span> <span m=''1776910''>fast</span> <span m=''1777230''>registers</span>
  <span m=''1777650''>of the</span> <span m=''1777750''>machine,</span> <span m=''1778070''>which</span>
  <span m=''1778200''>were</span> <span m=''1778340''>16.</span> <span m=''1779280''>The</span>
  <span m=''1779340''>whole</span> <span m=''1779490''>program.</span> <span m=''1779800''>And</span>
  <span m=''1780110''>you</span> <span m=''1780270''>could</span> <span m=''1780380''>execute</span>
  <span m=''1780700''>instructions</span> <span m=''1781220''>in</span> <span m=''1781290''>the</span>
  <span m=''1781350''>fast</span> <span m=''1781600''>registers.</span> <span m=''1783170''>So
  it''s</span> <span m=''1783330''>an</span> <span m=''1783440''>extremely</span>
  <span m=''1784140''>small</span> <span m=''1784450''>program,</span> <span m=''1785960''>and
  it</span> <span m=''1786080''>could</span> <span m=''1786180''>run</span> <span
  m=''1786360''>very</span> <span m=''1786560''>fast.</span> </p><p><span m=''1788870''>Now</span>
  <span m=''1790090''>unfortunately,</span> <span m=''1790820''>of</span> <span m=''1790920''>course,</span>
  <span m=''1791600''>this</span> <span m=''1791900''>program,</span> <span m=''1792350''>because</span>
  <span m=''1792760''>the</span> <span m=''1792880''>fact</span> <span m=''1793130''>that
  it''s</span> <span m=''1793280''>recursive</span> <span m=''1795960''>in</span>
  <span m=''1796340''>the</span> <span m=''1796420''>way</span> <span m=''1796590''>that</span>
  <span m=''1796720''>you</span> <span m=''1796850''>do</span> <span m=''1797010''>something</span>
  <span m=''1797320''>first</span> <span m=''1797630''>and</span> <span m=''1797720''>then</span>
  <span m=''1797810''>you</span> <span m=''1797890''>do</span> <span m=''1797990''>something</span>
  <span m=''1798370''>after</span> <span m=''1798650''>that,</span> <span m=''1799270''>you
  have to</span> <span m=''1799440''>work</span> <span m=''1799690''>on</span> <span
  m=''1799770''>the</span> <span m=''1799850''>cars</span> <span m=''1800170''>and
  then the</span> <span m=''1800410''>cdrs,</span> <span m=''1801190''>it</span> <span
  m=''1801330''>requires</span> <span m=''1801770''>auxiliary</span> <span m=''1802290''>memory.</span>
  <span m=''1803410''>So</span> <span m=''1804430''>Lisp</span> <span m=''1804710''>systems--</span>
  <span m=''1805680''>those</span> <span m=''1805920''>requires</span> <span m=''1806350''>a</span>
  <span m=''1806530''>stack</span> <span m=''1806890''>for</span> <span m=''1807040''>marking.</span>
  <span m=''1808260''>Lisp</span> <span m=''1808530''>systems</span> <span m=''1809170''>that</span>
  <span m=''1809900''>are</span> <span m=''1810200''>built</span> <span m=''1810460''>this</span>
  <span m=''1810640''>way</span> <span m=''1811560''>have</span> <span m=''1811780''>a</span>
  <span m=''1811860''>limit</span> <span m=''1812220''>to</span> <span m=''1812320''>the</span>
  <span m=''1812440''>depth</span> <span m=''1812760''>of</span> <span m=''1813010''>recursion</span>
  <span m=''1813620''>you</span> <span m=''1813740''>can</span> <span m=''1813850''>have</span>
  <span m=''1814480''>in</span> <span m=''1814860''>data</span> <span m=''1815190''>structures</span>
  <span m=''1815910''>in</span> <span m=''1816060''>either</span> <span m=''1816290''>the</span>
  <span m=''1816420''>car</span> <span m=''1816750''>or</span> <span m=''1816800''>the</span>
  <span m=''1816880''>cdr,</span> <span m=''1817830''>and</span> <span m=''1818050''>that</span>
  <span m=''1818190''>doesn''t</span> <span m=''1818410''>work</span> <span m=''1818580''>very</span>
  <span m=''1818800''>nicely.</span> </p><p><span m=''1819930''>On</span> <span m=''1820090''>the</span>
  <span m=''1820200''>other</span> <span m=''1820310''>hand,</span> <span m=''1820700''>you</span>
  <span m=''1820840''>never</span> <span m=''1821080''>notice</span> <span m=''1821400''>it</span>
  <span m=''1821490''>if</span> <span m=''1821590''>it''s</span> <span m=''1821730''>big</span>
  <span m=''1821910''>enough.</span> <span m=''1823180''>And</span> <span m=''1823430''>that''s</span>
  <span m=''1823620''>certainly</span> <span m=''1823910''>been</span> <span m=''1825810''>the</span>
  <span m=''1825930''>case</span> <span m=''1826230''>for</span> <span m=''1826350''>most</span>
  <span m=''1827030''>Maclisp,</span> <span m=''1827490''>for</span> <span m=''1827650''>example,</span>
  <span m=''1828740''>which</span> <span m=''1828920''>ran</span> <span m=''1829150''>Macsyma</span>
  <span m=''1830040''>where you</span> <span m=''1830240''>could</span> <span m=''1830370''>deal</span>
  <span m=''1830540''>with</span> <span m=''1830760''>expressions</span> <span m=''1831300''>of</span>
  <span m=''1831380''>thousands</span> <span m=''1831840''>of</span> <span m=''1831920''>elements</span>
  <span m=''1832250''>long.</span> <span m=''1833560''>These</span> <span m=''1833790''>are</span>
  <span m=''1834180''>algebraic expressions</span> <span m=''1834750''>with</span>
  <span m=''1835010''>thousand</span> <span m=''1835350''>of</span> <span m=''1835490''>terms.</span>
  <span m=''1836870''>And there''s</span> <span m=''1837080''>no</span> <span m=''1837230''>problem</span>
  <span m=''1837640''>with</span> <span m=''1837790''>that.</span> <span m=''1839490''>Such,</span>
  <span m=''1839800''>the</span> <span m=''1839840''>garbage</span> <span m=''1840060''>collector</span>
  <span m=''1840300''>does</span> <span m=''1840520''>work.</span> </p><p><span m=''1842190''>On</span>
  <span m=''1842330''>the</span> <span m=''1842450''>other</span> <span m=''1842580''>hand,</span>
  <span m=''1842990''>there''s</span> <span m=''1843140''>a</span> <span m=''1843190''>very</span>
  <span m=''1843430''>clever</span> <span m=''1843990''>modification</span> <span
  m=''1844660''>to</span> <span m=''1844750''>this</span> <span m=''1844850''>algorithm,</span>
  <span m=''1845300''>which</span> <span m=''1845450''>I</span> <span m=''1845520''>will</span>
  <span m=''1845630''>not</span> <span m=''1845810''>describe,</span> <span m=''1846900''>by</span>
  <span m=''1847370''>Peter</span> <span m=''1847710''>Deutsch</span> <span m=''1849020''>and</span>
  <span m=''1849590''>Schorr</span> <span m=''1850030''>and</span> <span m=''1850150''>Waite--</span>
  <span m=''1850720''>Herb</span> <span m=''1850960''>Schorr</span> <span m=''1851220''>from</span>
  <span m=''1851400''>IBM</span> <span m=''1851870''>and</span> <span m=''1852440''>Waite,</span>
  <span m=''1852700''>who</span> <span m=''1852900''>I</span> <span m=''1853120''>don''t</span>
  <span m=''1853330''>know.</span> <span m=''1855380''>That</span> <span m=''1855820''>algorithm</span>
  <span m=''1856720''>allows</span> <span m=''1857160''>you</span> <span m=''1857310''>to</span>
  <span m=''1857470''>build--</span> <span m=''1857860''>you</span> <span m=''1858000''>do</span>
  <span m=''1858130''>can</span> <span m=''1858250''>do</span> <span m=''1858340''>this</span>
  <span m=''1858470''>without</span> <span m=''1858720''>auxiliary</span> <span m=''1859180''>memory,</span>
  <span m=''1860580''>by</span> <span m=''1860720''>remembering</span> <span m=''1861280''>as</span>
  <span m=''1861500''>you</span> <span m=''1861610''>walk</span> <span m=''1861870''>the</span>
  <span m=''1861990''>data</span> <span m=''1862190''>structures</span> <span m=''1863050''>where</span>
  <span m=''1863180''>you</span> <span m=''1863310''>came</span> <span m=''1863550''>from</span>
  <span m=''1863740''>by</span> <span m=''1863840''>reversing</span> <span m=''1864300''>the</span>
  <span m=''1864380''>pointers</span> <span m=''1864760''>as</span> <span m=''1864850''>you</span>
  <span m=''1864960''>go</span> <span m=''1865110''>down</span> <span m=''1865570''>and</span>
  <span m=''1865760''>crawling</span> <span m=''1866080''>up</span> <span m=''1866200''>the</span>
  <span m=''1866300''>reverse</span> <span m=''1866650''>pointers as</span> <span
  m=''1867010''>you</span> <span m=''1867110''>go</span> <span m=''1867270''>up.</span>
  <span m=''1867520''>It''s a</span> <span m=''1867950''>rather</span> <span m=''1868200''>tricky</span>
  <span m=''1868520''>algorithm.</span> <span m=''1869130''>The</span> <span m=''1869310''>first</span>
  <span m=''1869490''>time you</span> <span m=''1869770''>write it--</span> <span
  m=''1870160''>or in</span> <span m=''1870220''>fact,</span> <span m=''1870520''>the</span>
  <span m=''1870860''>first</span> <span m=''1870990''>three</span> <span m=''1871230''>times</span>
  <span m=''1871470''>you write it it</span> <span m=''1871710''>has</span> <span
  m=''1871810''>a</span> <span m=''1871910''>terrible</span> <span m=''1872230''>bug
  in it.</span> <span m=''1874350''>And</span> <span m=''1874500''>it''s</span> <span
  m=''1874640''>also</span> <span m=''1876110''>rather</span> <span m=''1876330''>slow,</span>
  <span m=''1876640''>because</span> <span m=''1876910''>it''s</span> <span m=''1877070''>complicated.</span>
  <span m=''1878110''>It</span> <span m=''1878280''>takes</span> <span m=''1878500''>about</span>
  <span m=''1878700''>six</span> <span m=''1878840''>times</span> <span m=''1879070''>as</span>
  <span m=''1879130''>many</span> <span m=''1879550''>memory</span> <span m=''1879780''>references</span>
  <span m=''1880910''>to</span> <span m=''1881070''>do the</span> <span m=''1881230''>sorts
  of</span> <span m=''1881530''>things</span> <span m=''1881960''>that</span> <span
  m=''1882420''>we''re</span> <span m=''1882510''>talking</span> <span m=''1882840''>about.</span>
  </p><p><span m=''1884580''>Well</span> <span m=''1884770''>now</span> <span m=''1885300''>once</span>
  <span m=''1885620''>I''ve</span> <span m=''1885820''>done</span> <span m=''1886020''>this</span>
  <span m=''1886190''>marking</span> <span m=''1886600''>phase,</span> <span m=''1887070''>and</span>
  <span m=''1887570''>I</span> <span m=''1887770''>get</span> <span m=''1887950''>into</span>
  <span m=''1888140''>a</span> <span m=''1888200''>position</span> <span m=''1888570''>where</span>
  <span m=''1889060''>things</span> <span m=''1889330''>look</span> <span m=''1889520''>like</span>
  <span m=''1889750''>this,</span> <span m=''1890200''>let''s look--</span> <span
  m=''1890920''>yes.</span> <span m=''1891510''>Here</span> <span m=''1891670''>we</span>
  <span m=''1891800''>have</span> <span m=''1893080''>the</span> <span m=''1893330''>mark</span>
  <span m=''1893750''>done,</span> <span m=''1894160''>just</span> <span m=''1894410''>as</span>
  <span m=''1894500''>I</span> <span m=''1894610''>did</span> <span m=''1894820''>it.</span>
  <span m=''1895590''>Now</span> <span m=''1895780''>we</span> <span m=''1895860''>have</span>
  <span m=''1895970''>to</span> <span m=''1896060''>perform</span> <span m=''1896410''>the</span>
  <span m=''1896500''>sweep</span> <span m=''1896860''>phase.</span> <span m=''1897330''>And</span>
  <span m=''1897640''>I</span> <span m=''1897840''>described</span> <span m=''1898300''>to
  you what</span> <span m=''1898530''>this</span> <span m=''1898660''>sweep</span>
  <span m=''1898850''>is</span> <span m=''1898990''>like.</span> <span m=''1899820''>I''m</span>
  <span m=''1900000''>going</span> <span m=''1900150''>to</span> <span m=''1900310''>walk</span>
  <span m=''1900620''>down</span> <span m=''1900920''>from</span> <span m=''1901080''>one</span>
  <span m=''1901240''>end</span> <span m=''1901410''>of</span> <span m=''1901470''>memory</span>
  <span m=''1901800''>or</span> <span m=''1901900''>the</span> <span m=''1902130''>other,</span>
  <span m=''1902430''>I</span> <span m=''1902550''>don''t</span> <span m=''1902720''>care</span>
  <span m=''1902930''>where,</span> <span m=''1903380''>scanning</span> <span m=''1903980''>every</span>
  <span m=''1904260''>cell</span> <span m=''1905270''>that''s</span> <span m=''1905560''>in</span>
  <span m=''1905690''>the</span> <span m=''1905760''>memory.</span> <span m=''1906836''>And</span>
  <span m=''1907190''>as</span> <span m=''1907440''>I</span> <span m=''1907540''>scan</span>
  <span m=''1907960''>these</span> <span m=''1908120''>cells,</span> <span m=''1909190''>I''m</span>
  <span m=''1909390''>going</span> <span m=''1909650''>to</span> <span m=''1910180''>link</span>
  <span m=''1910410''>them</span> <span m=''1910550''>together,</span> <span m=''1911000''>if</span>
  <span m=''1911180''>they</span> <span m=''1911330''>are</span> <span m=''1911410''>free,</span>
  <span m=''1912020''>into</span> <span m=''1912150''>the</span> <span m=''1912290''>free</span>
  <span m=''1912510''>list.</span> <span m=''1913180''>And</span> <span m=''1913400''>if</span>
  <span m=''1913480''>they''re</span> <span m=''1913650''>not</span> <span m=''1913890''>free,</span>
  <span m=''1914070''>I''m going</span> <span m=''1914200''>to</span> <span m=''1914330''>unmark</span>
  <span m=''1914730''>them</span> <span m=''1914860''>so</span> <span m=''1914990''>the</span>
  <span m=''1915100''>marks</span> <span m=''1915370''>become</span> <span m=''1915670''>zero.</span>
  </p><p><span m=''1917500''>And</span> <span m=''1917690''>in</span> <span m=''1917770''>fact</span>
  <span m=''1918080''>what</span> <span m=''1918210''>I</span> <span m=''1918290''>get--</span>
  <span m=''1918770''>well</span> <span m=''1918900''>the</span> <span m=''1918980''>program</span>
  <span m=''1919430''>is</span> <span m=''1919650''>not</span> <span m=''1919860''>very</span>
  <span m=''1920050''>complicated.</span> <span m=''1920460''>It</span> <span m=''1920610''>looks</span>
  <span m=''1920790''>sort</span> <span m=''1920900''>of</span> <span m=''1921010''>like</span>
  <span m=''1921200''>this--</span> <span m=''1921360''>it''s</span> <span m=''1921480''>a</span>
  <span m=''1921530''>little</span> <span m=''1921750''>longer.</span> <span m=''1922780''>Here''s</span>
  <span m=''1922950''>the</span> <span m=''1923160''>first</span> <span m=''1923580''>piece</span>
  <span m=''1923820''>of</span> <span m=''1923950''>it.</span> <span m=''1924820''>This</span>
  <span m=''1925030''>one''s</span> <span m=''1925200''>coming</span> <span m=''1925410''>down</span>
  <span m=''1925590''>from</span> <span m=''1925690''>the</span> <span m=''1925800''>top</span>
  <span m=''1926090''>of</span> <span m=''1926180''>memory.</span> <span m=''1926710''>I</span>
  <span m=''1926840''>don''t</span> <span m=''1927010''>want</span> <span m=''1927180''>you</span>
  <span m=''1927280''>to</span> <span m=''1927820''>try</span> <span m=''1928240''>to</span>
  <span m=''1928340''>understand</span> <span m=''1928950''>this</span> <span m=''1929110''>at</span>
  <span m=''1929200''>this</span> <span m=''1929360''>point.</span> <span m=''1929580''>It''s</span>
  <span m=''1929750''>rather</span> <span m=''1930000''>simple.</span> <span m=''1931030''>It''s</span>
  <span m=''1931170''>a</span> <span m=''1931490''>very</span> <span m=''1931680''>simple</span>
  <span m=''1932010''>algorithm,</span> <span m=''1933080''>but</span> <span m=''1933310''>there''s</span>
  <span m=''1933550''>pieces</span> <span m=''1933860''>of</span> <span m=''1933980''>it</span>
  <span m=''1934130''>that</span> <span m=''1934260''>just</span> <span m=''1934450''>sort
  of</span> <span m=''1935060''>look</span> <span m=''1935260''>like</span> <span
  m=''1935510''>this.</span> <span m=''1935970''>They''re</span> <span m=''1936200''>all</span>
  <span m=''1936420''>sort</span> <span m=''1936610''>of</span> <span m=''1936830''>obvious.</span>
  <span m=''1938600''>And</span> <span m=''1939000''>after</span> <span m=''1939290''>we''ve</span>
  <span m=''1939420''>done</span> <span m=''1939620''>the</span> <span m=''1939770''>sweep,</span>
  <span m=''1940260''>we</span> <span m=''1940390''>get</span> <span m=''1940520''>an</span>
  <span m=''1940610''>answer</span> <span m=''1940930''>that</span> <span m=''1941060''>looks</span>
  <span m=''1941270''>like</span> <span m=''1941490''>that.</span> </p><p><span m=''1945330''>Now</span>
  <span m=''1945530''>there</span> <span m=''1945690''>are</span> <span m=''1945740''>some</span>
  <span m=''1945890''>disadvantages</span> <span m=''1946560''>with</span> <span m=''1946710''>mark-sweep</span>
  <span m=''1947150''>algorithms</span> <span m=''1947730''>of</span> <span m=''1947870''>this</span>
  <span m=''1948010''>sort.</span> <span m=''1949590''>Serious</span> <span m=''1950010''>ones.</span>
  <span m=''1951940''>One</span> <span m=''1952190''>important</span> <span m=''1952510''>disadvantage</span>
  <span m=''1952970''>is</span> <span m=''1953070''>that</span> <span m=''1953210''>your</span>
  <span m=''1953300''>memories</span> <span m=''1953650''>get</span> <span m=''1953820''>larger</span>
  <span m=''1954250''>and</span> <span m=''1954320''>larger.</span> <span m=''1956498''>As</span>
  <span m=''1956910''>you</span> <span m=''1957060''>say,</span> <span m=''1957520''>address</span>
  <span m=''1957790''>spaces</span> <span m=''1958220''>get</span> <span m=''1958360''>larger</span>
  <span m=''1958640''>and</span> <span m=''1958700''>larger,</span> <span m=''1958960''>you''re</span>
  <span m=''1959100''>willing</span> <span m=''1959350''>to</span> <span m=''1959440''>represent</span>
  <span m=''1959860''>more</span> <span m=''1960070''>and</span> <span m=''1960130''>more</span>
  <span m=''1960330''>stuff,</span> <span m=''1961200''>then</span> <span m=''1962330''>it</span>
  <span m=''1962450''>gets</span> <span m=''1962860''>very</span> <span m=''1963080''>costly</span>
  <span m=''1963560''>to</span> <span m=''1963670''>scan all of</span> <span m=''1964180''>memory.</span>
  <span m=''1966360''>What</span> <span m=''1966520''>you''d</span> <span m=''1966620''>really</span>
  <span m=''1966920''>like</span> <span m=''1967120''>to</span> <span m=''1967200''>do</span>
  <span m=''1967400''>is</span> <span m=''1967510''>only</span> <span m=''1967710''>scan</span>
  <span m=''1968080''>useful</span> <span m=''1968410''>stuff.</span> <span m=''1970490''>It
  would even</span> <span m=''1970860''>be</span> <span m=''1970990''>better</span>
  <span m=''1972060''>if</span> <span m=''1972200''>you</span> <span m=''1972380''>realized</span>
  <span m=''1973050''>that</span> <span m=''1973340''>some</span> <span m=''1973550''>stuff</span>
  <span m=''1974550''>was</span> <span m=''1976120''>known</span> <span m=''1976470''>to</span>
  <span m=''1976550''>be</span> <span m=''1976670''>good</span> <span m=''1976910''>and</span>
  <span m=''1976990''>useful,</span> <span m=''1978330''>and</span> <span m=''1978490''>you
  don''t</span> <span m=''1978630''>have</span> <span m=''1978770''>to</span> <span
  m=''1979080''>look</span> <span m=''1979200''>at</span> <span m=''1979320''>it</span>
  <span m=''1979460''>more</span> <span m=''1979600''>than</span> <span m=''1979740''>once</span>
  <span m=''1979980''>or</span> <span m=''1980020''>twice.</span> <span m=''1980370''>Or</span>
  <span m=''1980510''>very</span> <span m=''1980740''>rarely.</span> <span m=''1981550''>Whereas</span>
  <span m=''1981780''>other</span> <span m=''1981970''>stuff</span> <span m=''1982360''>that</span>
  <span m=''1983330''>you''re</span> <span m=''1983390''>not</span> <span m=''1983560''>so</span>
  <span m=''1983640''>sure</span> <span m=''1983890''>about,</span> <span m=''1985010''>you</span>
  <span m=''1985120''>can</span> <span m=''1985270''>look</span> <span m=''1985430''>at</span>
  <span m=''1985590''>more</span> <span m=''1985820''>detail</span> <span m=''1987220''>every</span>
  <span m=''1987460''>time</span> <span m=''1987670''>you</span> <span m=''1987790''>want</span>
  <span m=''1987920''>to</span> <span m=''1988280''>do</span> <span m=''1988450''>this,</span>
  <span m=''1989930''>want</span> <span m=''1990110''>to</span> <span m=''1990150''>garbage</span>
  <span m=''1990470''>collect.</span> </p><p><span m=''1991910''>Well</span> <span
  m=''1992810''>there</span> <span m=''1993030''>are</span> <span m=''1993200''>algorithms</span>
  <span m=''1993800''>that are</span> <span m=''1993930''>organized</span> <span m=''1994460''>in</span>
  <span m=''1994530''>this</span> <span m=''1994710''>way.</span> <span m=''1995660''>Let</span>
  <span m=''1995800''>me</span> <span m=''1995900''>tell</span> <span m=''1996060''>you</span>
  <span m=''1996180''>about</span> <span m=''1996850''>a</span> <span m=''1996970''>famous</span>
  <span m=''1997350''>old</span> <span m=''1997600''>algorithm</span> <span m=''1998240''>which</span>
  <span m=''1998430''>allows</span> <span m=''1998730''>you</span> <span m=''1998850''>only</span>
  <span m=''1999130''>look</span> <span m=''1999330''>at</span> <span m=''1999530''>the</span>
  <span m=''1999630''>part</span> <span m=''1999860''>of</span> <span m=''1999930''>memory</span>
  <span m=''2000180''>which</span> <span m=''2000370''>is</span> <span m=''2000460''>known</span>
  <span m=''2000670''>to</span> <span m=''2000740''>be</span> <span m=''2000840''>useful.</span>
  <span m=''2002800''>And</span> <span m=''2003120''>which</span> <span m=''2003310''>happens
  to</span> <span m=''2003590''>be</span> <span m=''2003730''>the fastest</span> <span
  m=''2004190''>known</span> <span m=''2004410''>garbage</span> <span m=''2004690''>collector</span>
  <span m=''2004980''>algorithm.</span> <span m=''2006310''>This</span> <span m=''2006480''>is</span>
  <span m=''2006580''>the</span> <span m=''2006990''>Minsky-Feinchel-Yochelson</span>
  <span m=''2008170''>garbage</span> <span m=''2008640''>collector</span> <span m=''2008840''>algorithm.</span>
  <span m=''2010150''>It</span> <span m=''2010510''>was</span> <span m=''2011480''>invented</span>
  <span m=''2012460''>by</span> <span m=''2012720''>Minsky</span> <span m=''2013250''>in</span>
  <span m=''2013570''>1961</span> <span m=''2014800''>or</span> <span m=''2014940''>''60</span>
  <span m=''2015380''>or</span> <span m=''2015470''>something,</span> <span m=''2016320''>for</span>
  <span m=''2016660''>the</span> <span m=''2016800''>RLE</span> <span m=''2018890''>PDP-1</span>
  <span m=''2020230''>Lisp,</span> <span m=''2020540''>which</span> <span m=''2020670''>had</span>
  <span m=''2020820''>4,096</span> <span m=''2021810''>words</span> <span m=''2022610''>of</span>
  <span m=''2022730''>list</span> <span m=''2023010''>memory,</span> <span m=''2025870''>and</span>
  <span m=''2026100''>a</span> <span m=''2026210''>drum.</span> <span m=''2028480''>And</span>
  <span m=''2028600''>the</span> <span m=''2028710''>whole</span> <span m=''2028970''>idea</span>
  <span m=''2030050''>was</span> <span m=''2030220''>to</span> <span m=''2030320''>garbage</span>
  <span m=''2030690''>collect</span> <span m=''2030890''>this</span> <span m=''2031050''>terrible</span>
  <span m=''2031410''>memory.</span> </p><p><span m=''2033380''>What</span> <span
  m=''2033580''>Minsky</span> <span m=''2033940''>realized</span> <span m=''2034390''>was</span>
  <span m=''2034520''>the</span> <span m=''2034670''>easiest</span> <span m=''2034960''>way</span>
  <span m=''2035060''>to</span> <span m=''2035150''>do</span> <span m=''2035330''>this</span>
  <span m=''2036230''>is</span> <span m=''2036420''>to</span> <span m=''2036510''>scan</span>
  <span m=''2036900''>the</span> <span m=''2036980''>memory</span> <span m=''2037560''>in</span>
  <span m=''2037640''>the</span> <span m=''2037720''>same</span> <span m=''2038010''>sense,</span>
  <span m=''2038480''>walking</span> <span m=''2039290''>the</span> <span m=''2039740''>good</span>
  <span m=''2039950''>structure,</span> <span m=''2041610''>copying</span> <span m=''2042100''>it</span>
  <span m=''2042620''>out</span> <span m=''2042810''>into</span> <span m=''2043030''>the</span>
  <span m=''2043120''>drum,</span> <span m=''2044820''>compacted.</span> <span m=''2046350''>And</span>
  <span m=''2046590''>then</span> <span m=''2046790''>when</span> <span m=''2047330''>we</span>
  <span m=''2047420''>were</span> <span m=''2047510''>done</span> <span m=''2047830''>copying</span>
  <span m=''2048239''>it</span> <span m=''2048300''>all</span> <span m=''2048530''>out,</span>
  <span m=''2049030''>then</span> <span m=''2049330''>you</span> <span m=''2049429''>swap</span>
  <span m=''2049750''>that</span> <span m=''2049960''>back</span> <span m=''2050190''>into</span>
  <span m=''2050360''>your</span> <span m=''2050500''>memory.</span> <span m=''2052300''>Now</span>
  <span m=''2052460''>whether</span> <span m=''2052580''>or</span> <span m=''2052600''>you</span>
  <span m=''2052770''>not</span> <span m=''2052989''>use</span> <span m=''2053219''>a</span>
  <span m=''2053280''>drum, or</span> <span m=''2053719''>another</span> <span m=''2053940''>piece</span>
  <span m=''2054190''>of</span> <span m=''2054260''>memory,</span> <span m=''2054590''>or</span>
  <span m=''2054670''>something</span> <span m=''2054940''>like</span> <span m=''2055159''>that</span>
  <span m=''2055540''>isn''t</span> <span m=''2055830''>important.</span> <span m=''2057030''>In</span>
  <span m=''2057250''>fact,</span> <span m=''2057480''>I</span> <span m=''2057540''>don''t</span>
  <span m=''2057670''>think</span> <span m=''2057800''>people</span> <span m=''2058010''>use</span>
  <span m=''2058260''>drums</span> <span m=''2058560''>anymore</span> <span m=''2058880''>for</span>
  <span m=''2059030''>anything.</span> </p><p><span m=''2060350''>But</span> <span
  m=''2062080''>this</span> <span m=''2062350''>algorithm</span> <span m=''2063060''>basically</span>
  <span m=''2064270''>depends</span> <span m=''2064639''>upon</span> <span m=''2064900''>having</span>
  <span m=''2065370''>about</span> <span m=''2065920''>twice</span> <span m=''2066250''>as</span>
  <span m=''2066360''>much</span> <span m=''2066699''>address</span> <span m=''2067130''>space</span>
  <span m=''2067540''>as</span> <span m=''2067670''>you''re</span> <span m=''2067840''>actually</span>
  <span m=''2068139''>using.</span> <span m=''2070270''>And</span> <span m=''2070400''>so</span>
  <span m=''2070530''>what</span> <span m=''2070679''>you</span> <span m=''2070830''>have</span>
  <span m=''2071860''>is</span> <span m=''2072060''>some,</span> <span m=''2072310''>initially,</span>
  <span m=''2073020''>some</span> <span m=''2073389''>mixture</span> <span m=''2075219''>of</span>
  <span m=''2075370''>useful</span> <span m=''2075750''>data</span> <span m=''2076040''>and</span>
  <span m=''2076219''>garbage.</span> <span m=''2077110''>So</span> <span m=''2077239''>this</span>
  <span m=''2077400''>is</span> <span m=''2077989''>called</span> <span m=''2078239''>fromspace.</span>
  <span m=''2085179''>And</span> <span m=''2085420''>this</span> <span m=''2085560''>is</span>
  <span m=''2085830''>a</span> <span m=''2085989''>mixture</span> <span m=''2086449''>of</span>
  <span m=''2086550''>crud.</span> <span m=''2087800''>Some of</span> <span m=''2088210''>it''s</span>
  <span m=''2088409''>important</span> <span m=''2088929''>and</span> <span m=''2089020''>some</span>
  <span m=''2089219''>of</span> <span m=''2089320''>it</span> <span m=''2089400''>isn''t.</span>
  </p><p><span m=''2092000''>Now</span> <span m=''2092219''>there''s</span> <span
  m=''2092980''>another</span> <span m=''2093380''>place</span> <span m=''2094210''>which</span>
  <span m=''2094400''>is</span> <span m=''2094620''>hopefully</span> <span m=''2095130''>big</span>
  <span m=''2095340''>enough,</span> <span m=''2095770''>if we</span> <span m=''2095949''>recall,</span>
  <span m=''2096370''>tospace,</span> <span m=''2097100''>which is</span> <span m=''2097310''>where
  we''re</span> <span m=''2097570''>copying</span> <span m=''2098010''>to.</span>
  <span m=''2101590''>And</span> <span m=''2101730''>what</span> <span m=''2101860''>happens</span>
  <span m=''2102280''>is--</span> <span m=''2102660''>and I''m</span> <span m=''2102820''>not</span>
  <span m=''2102990''>going</span> <span m=''2103060''>to</span> <span m=''2103130''>go</span>
  <span m=''2103260''>through</span> <span m=''2103400''>this</span> <span m=''2103560''>detail.</span>
  <span m=''2104970''>It''s</span> <span m=''2105170''>in</span> <span m=''2105270''>our</span>
  <span m=''2105390''>book</span> <span m=''2106090''>quite</span> <span m=''2106300''>explicitly.</span>
  <span m=''2107590''>There''s</span> <span m=''2108780''>a</span> <span m=''2108920''>root</span>
  <span m=''2109160''>point</span> <span m=''2109390''>where</span> <span m=''2109530''>you</span>
  <span m=''2109660''>start</span> <span m=''2109990''>from.</span> <span m=''2111030''>And</span>
  <span m=''2111170''>the</span> <span m=''2111310''>idea</span> <span m=''2111740''>is</span>
  <span m=''2112210''>that</span> <span m=''2112470''>you</span> <span m=''2113650''>start
  with</span> <span m=''2113830''>the</span> <span m=''2113960''>root.</span> <span
  m=''2114600''>You</span> <span m=''2114780''>copy</span> <span m=''2115160''>the</span>
  <span m=''2115260''>first</span> <span m=''2115530''>thing</span> <span m=''2115730''>you</span>
  <span m=''2115890''>see,</span> <span m=''2117890''>the</span> <span m=''2118030''>first</span>
  <span m=''2118290''>thing</span> <span m=''2118450''>that the</span> <span m=''2118610''>root
  points</span> <span m=''2119140''>at,</span> <span m=''2119430''>to the</span> <span
  m=''2119980''>beginning</span> <span m=''2120600''>of</span> <span m=''2120760''>tospace.</span>
  <span m=''2122810''>The</span> <span m=''2123000''>first</span> <span m=''2123190''>thing</span>
  <span m=''2123430''>is</span> <span m=''2123620''>a</span> <span m=''2123740''>pair</span>
  <span m=''2124390''>or</span> <span m=''2124520''>something</span> <span m=''2124790''>like,</span>
  <span m=''2125040''>a</span> <span m=''2125130''>data</span> <span m=''2125360''>structure.</span>
  </p><p><span m=''2127560''>You</span> <span m=''2127740''>then</span> <span m=''2129020''>also</span>
  <span m=''2129380''>leave</span> <span m=''2129630''>behind</span> <span m=''2130420''>a</span>
  <span m=''2130540''>broken</span> <span m=''2130880''>heart</span> <span m=''2131190''>saying,</span>
  <span m=''2131830''>I</span> <span m=''2131980''>moved</span> <span m=''2132330''>this</span>
  <span m=''2132800''>object</span> <span m=''2133860''>from</span> <span m=''2134310''>here</span>
  <span m=''2135210''>to</span> <span m=''2135350''>here,</span> <span m=''2135780''>giving</span>
  <span m=''2135990''>the</span> <span m=''2136080''>place</span> <span m=''2136330''>where</span>
  <span m=''2136450''>it</span> <span m=''2136510''>moved</span> <span m=''2136790''>to.</span>
  <span m=''2137800''>This</span> <span m=''2138030''>is</span> <span m=''2138130''>called</span>
  <span m=''2138350''>a</span> <span m=''2138390''>broken</span> <span m=''2138710''>heart</span>
  <span m=''2139010''>because</span> <span m=''2139620''>a</span> <span m=''2139740''>friend</span>
  <span m=''2139960''>of</span> <span m=''2140010''>mine</span> <span m=''2140190''>who</span>
  <span m=''2140270''>implemented</span> <span m=''2140730''>one</span> <span m=''2140870''>of</span>
  <span m=''2141010''>these</span> <span m=''2141140''>in</span> <span m=''2141360''>1966</span>
  <span m=''2144000''>was</span> <span m=''2144130''>a very</span> <span m=''2144440''>romantic</span>
  <span m=''2144760''>character</span> <span m=''2145460''>and</span> <span m=''2145820''>called</span>
  <span m=''2146090''>it a</span> <span m=''2146140''>broken</span> <span m=''2146460''>heart.</span>
  </p><p><span m=''2149580''>But</span> <span m=''2149830''>in</span> <span m=''2149950''>any</span>
  <span m=''2150130''>case,</span> <span m=''2151600''>the</span> <span m=''2151810''>next</span>
  <span m=''2152040''>thing</span> <span m=''2152190''>you</span> <span m=''2152300''>do</span>
  <span m=''2152950''>is</span> <span m=''2153100''>now</span> <span m=''2153260''>you</span>
  <span m=''2153370''>have</span> <span m=''2153520''>a</span> <span m=''2153570''>new</span>
  <span m=''2153750''>free</span> <span m=''2153990''>pointer</span> <span m=''2154360''>which</span>
  <span m=''2154540''>is</span> <span m=''2154640''>here,</span> <span m=''2155180''>and</span>
  <span m=''2155380''>you</span> <span m=''2155470''>start</span> <span m=''2155760''>scanning.</span>
  <span m=''2157840''>You</span> <span m=''2158000''>scan this</span> <span m=''2158420''>data</span>
  <span m=''2158610''>structure</span> <span m=''2158890''>you</span> <span m=''2159110''>just</span>
  <span m=''2159310''>copied.</span> <span m=''2160235''>And</span> <span m=''2160700''>every</span>
  <span m=''2161030''>time</span> <span m=''2161200''>you</span> <span m=''2161300''>encounter</span>
  <span m=''2161650''>a</span> <span m=''2161710''>pointer</span> <span m=''2162020''>in
  it,</span> <span m=''2162160''>you</span> <span m=''2162310''>treat it</span> <span
  m=''2162600''>as</span> <span m=''2162710''>if it</span> <span m=''2162880''>was</span>
  <span m=''2163050''>the</span> <span m=''2163100''>root pointer</span> <span m=''2163590''>here.</span>
  <span m=''2164000''>Oh,</span> <span m=''2164190''>I''m</span> <span m=''2164310''>sorry.</span>
  <span m=''2165170''>The other thing</span> <span m=''2165530''>you</span> <span
  m=''2165650''>do is</span> <span m=''2165790''>you</span> <span m=''2165900''>now</span>
  <span m=''2166070''>move</span> <span m=''2166260''>the</span> <span m=''2166330''>root
  pointer to</span> <span m=''2166810''>there.</span> </p><p><span m=''2169220''>So</span>
  <span m=''2169500''>now</span> <span m=''2169650''>you</span> <span m=''2169780''>scan</span>
  <span m=''2170110''>this, and</span> <span m=''2170270''>everything</span> <span
  m=''2170650''>you</span> <span m=''2170760''>see</span> <span m=''2170960''>you</span>
  <span m=''2171090''>treat</span> <span m=''2171310''>as</span> <span m=''2171420''>it</span>
  <span m=''2171510''>were</span> <span m=''2171670''>the</span> <span m=''2171790''>root
  pointer.</span> <span m=''2174110''>So</span> <span m=''2174560''>if</span> <span
  m=''2174640''>you</span> <span m=''2174730''>see</span> <span m=''2174920''>something,</span>
  <span m=''2175510''>well</span> <span m=''2175750''>it</span> <span m=''2176080''>points</span>
  <span m=''2176360''>up</span> <span m=''2176500''>into</span> <span m=''2176690''>there</span>
  <span m=''2176900''>somewhere.</span> <span m=''2178510''>Is</span> <span m=''2178700''>it</span>
  <span m=''2178820''>pointing</span> <span m=''2179450''>at</span> <span m=''2179690''>a</span>
  <span m=''2179750''>thing</span> <span m=''2179940''>which</span> <span m=''2180100''>you''ve</span>
  <span m=''2180220''>not</span> <span m=''2180420''>copied</span> <span m=''2180720''>yet?</span>
  <span m=''2181780''>Is</span> <span m=''2181880''>there</span> <span m=''2181970''>a</span>
  <span m=''2182010''>broken</span> <span m=''2182290''>heart</span> <span m=''2182540''>there?</span>
  <span m=''2183880''>If</span> <span m=''2184050''>there''s</span> <span m=''2184230''>a</span>
  <span m=''2184280''>broken</span> <span m=''2184550''>heart</span> <span m=''2184740''>there</span>
  <span m=''2184940''>and it''s</span> <span m=''2185030''>something</span> <span
  m=''2185280''>you</span> <span m=''2185370''>have</span> <span m=''2185590''>copied,</span>
  <span m=''2186190''>you''ve</span> <span m=''2186320''>just</span> <span m=''2186580''>replaced</span>
  <span m=''2186950''>this</span> <span m=''2187110''>pointer</span> <span m=''2187380''>with</span>
  <span m=''2187620''>the thing a</span> <span m=''2187680''>broken</span> <span m=''2188000''>heart</span>
  <span m=''2188220''>points</span> <span m=''2188450''>at.</span> <span m=''2190620''>If</span>
  <span m=''2190820''>this</span> <span m=''2190960''>thing</span> <span m=''2191090''>has</span>
  <span m=''2191180''>not</span> <span m=''2191370''>been</span> <span m=''2191490''>copied,</span>
  <span m=''2192190''>you</span> <span m=''2192340''>copy</span> <span m=''2192700''>it</span>
  <span m=''2192770''>to</span> <span m=''2192860''>the</span> <span m=''2193030''>next</span>
  <span m=''2193200''>place</span> <span m=''2193510''>over</span> <span m=''2193690''>here.</span>
  <span m=''2194430''>Move</span> <span m=''2194650''>your</span> <span m=''2194790''>free</span>
  <span m=''2195000''>pointer</span> <span m=''2195400''>over</span> <span m=''2195560''>here,</span>
  <span m=''2198000''>and</span> <span m=''2198170''>then</span> <span m=''2199230''>leave</span>
  <span m=''2199560''>a</span> <span m=''2199630''>broken</span> <span m=''2199860''>heart</span>
  <span m=''2200070''>behind</span> <span m=''2201140''>and</span> <span m=''2201320''>scan.</span>
  </p><p><span m=''2203670''>And</span> <span m=''2203990''>eventually</span> <span
  m=''2204530''>when</span> <span m=''2204680''>the</span> <span m=''2204760''>scant</span>
  <span m=''2205130''>pointer</span> <span m=''2205390''>hits</span> <span m=''2205590''>the</span>
  <span m=''2205680''>free</span> <span m=''2205870''>pointer,</span> <span m=''2206840''>everything</span>
  <span m=''2207220''>in</span> <span m=''2207320''>memory</span> <span m=''2207620''>has</span>
  <span m=''2207770''>been</span> <span m=''2207910''>copied.</span> <span m=''2210140''>And</span>
  <span m=''2210290''>then</span> <span m=''2210440''>there''s</span> <span m=''2210640''>a</span>
  <span m=''2210690''>whole</span> <span m=''2210840''>bunch</span> <span m=''2211060''>of</span>
  <span m=''2211270''>empty</span> <span m=''2211440''>space</span> <span m=''2211700''>up</span>
  <span m=''2211820''>here,</span> <span m=''2211990''>which</span> <span m=''2212170''>you</span>
  <span m=''2212260''>could</span> <span m=''2212360''>either</span> <span m=''2212540''>make</span>
  <span m=''2212740''>into</span> <span m=''2212830''>a</span> <span m=''2212950''>free</span>
  <span m=''2213150''>list,</span> <span m=''2213370''>if</span> <span m=''2213450''>that''s</span>
  <span m=''2213620''>what</span> <span m=''2213720''>you</span> <span m=''2213820''>want</span>
  <span m=''2213930''>to</span> <span m=''2214050''>do.</span> <span m=''2214470''>But</span>
  <span m=''2214740''>generally</span> <span m=''2215040''>you</span> <span m=''2215110''>don''t</span>
  <span m=''2215270''>in this</span> <span m=''2215480''>kind</span> <span m=''2215610''>of</span>
  <span m=''2215730''>system.</span> <span m=''2216270''>In this</span> <span m=''2216480''>system</span>
  <span m=''2216810''>you</span> <span m=''2216920''>sequentially</span> <span m=''2217470''>allocate</span>
  <span m=''2218700''>your</span> <span m=''2218810''>memory.</span> <span m=''2220910''>That
  is</span> <span m=''2221110''>a</span> <span m=''2221190''>very,</span> <span m=''2221460''>very</span>
  <span m=''2221650''>nice</span> <span m=''2221890''>algorithm,</span> <span m=''2223010''>and</span>
  <span m=''2223300''>sort</span> <span m=''2223430''>of</span> <span m=''2223560''>the</span>
  <span m=''2223630''>one</span> <span m=''2223820''>we</span> <span m=''2223940''>use</span>
  <span m=''2224210''>in</span> <span m=''2224540''>the</span> <span m=''2224800''>scheme</span>
  <span m=''2225090''>that</span> <span m=''2225220''>you''ve</span> <span m=''2225380''>been</span>
  <span m=''2225500''>using.</span> <span m=''2226790''>And</span> <span m=''2228630''>it''s</span>
  <span m=''2228980''>expected--</span> <span m=''2229490''>I</span> <span m=''2229560''>believe</span>
  <span m=''2230180''>no</span> <span m=''2230350''>one</span> <span m=''2230480''>has</span>
  <span m=''2230620''>found</span> <span m=''2230870''>a</span> <span m=''2230920''>faster</span>
  <span m=''2231190''>algorithm</span> <span m=''2231750''>than that.</span> </p><p><span
  m=''2232400''>There</span> <span m=''2232710''>are</span> <span m=''2232780''>very</span>
  <span m=''2232990''>simple</span> <span m=''2233280''>modifications</span> <span
  m=''2233605''>to</span> <span m=''2233930''>this</span> <span m=''2234150''>algorithm</span>
  <span m=''2234890''>invented</span> <span m=''2235390''>by</span> <span m=''2235890''>Henry</span>
  <span m=''2236280''>Baker</span> <span m=''2237490''>which</span> <span m=''2237690''>allow</span>
  <span m=''2237990''>one</span> <span m=''2238250''>to</span> <span m=''2238610''>run</span>
  <span m=''2239060''>this</span> <span m=''2239170''>algorithm</span> <span m=''2239590''>in</span>
  <span m=''2239690''>real</span> <span m=''2239920''>time,</span> <span m=''2240370''>meaning</span>
  <span m=''2240600''>you</span> <span m=''2240670''>don''t</span> <span m=''2240780''>have</span>
  <span m=''2240860''>to</span> <span m=''2240940''>stop</span> <span m=''2241210''>to</span>
  <span m=''2241310''>garbage</span> <span m=''2241610''>collect.</span> <span m=''2242010''>But</span>
  <span m=''2242330''>you</span> <span m=''2242440''>could</span> <span m=''2242560''>interleave</span>
  <span m=''2243470''>the</span> <span m=''2243820''>consing</span> <span m=''2244420''>that</span>
  <span m=''2244800''>the</span> <span m=''2244900''>machine</span> <span m=''2245230''>does</span>
  <span m=''2245410''>when</span> <span m=''2245510''>its</span> <span m=''2245640''>running</span>
  <span m=''2246290''>with</span> <span m=''2246640''>steps</span> <span m=''2246960''>of</span>
  <span m=''2247050''>the</span> <span m=''2247140''>garbage</span> <span m=''2247470''>collection</span>
  <span m=''2247870''>process,</span> <span m=''2248850''>so</span> <span m=''2249060''>that</span>
  <span m=''2249710''>the</span> <span m=''2249810''>garbage</span> <span m=''2250260''>collector''s</span>
  <span m=''2250640''>distributed,</span> <span m=''2251160''>and</span> <span m=''2251370''>the
  machine</span> <span m=''2251490''>doesn''t</span> <span m=''2251670''>have</span>
  <span m=''2251760''>to</span> <span m=''2251840''>stop,</span> <span m=''2252440''>and</span>
  <span m=''2252600''>garbage</span> <span m=''2252980''>collecting can</span> <span
  m=''2253070''>start.</span> </p><p><span m=''2254640''>Of</span> <span m=''2254800''>course</span>
  <span m=''2254950''>in</span> <span m=''2255020''>the</span> <span m=''2255090''>case</span>
  <span m=''2255340''>of</span> <span m=''2256300''>machines</span> <span m=''2256650''>with</span>
  <span m=''2256800''>virtual</span> <span m=''2257200''>memory</span> <span m=''2257520''>where</span>
  <span m=''2259220''>a</span> <span m=''2259280''>lot</span> <span m=''2259490''>of</span>
  <span m=''2259590''>it</span> <span m=''2259650''>is</span> <span m=''2259860''>in</span>
  <span m=''2260070''>inaccessible</span> <span m=''2260630''>places,</span> <span
  m=''2261480''>this</span> <span m=''2261760''>becomes</span> <span m=''2262070''>a</span>
  <span m=''2262120''>very</span> <span m=''2262590''>expensive</span> <span m=''2263040''>process.</span>
  <span m=''2264460''>And</span> <span m=''2265470''>there</span> <span m=''2265680''>have</span>
  <span m=''2265820''>been</span> <span m=''2265960''>numerous</span> <span m=''2267200''>attempts</span>
  <span m=''2267610''>to</span> <span m=''2267690''>make</span> <span m=''2267880''>this</span>
  <span m=''2268030''>much</span> <span m=''2268240''>better.</span> <span m=''2269190''>There</span>
  <span m=''2269430''>is</span> <span m=''2269540''>a</span> <span m=''2270580''>nice</span>
  <span m=''2270840''>paper,</span> <span m=''2271150''>for</span> <span m=''2271290''>those</span>
  <span m=''2271510''>of</span> <span m=''2271690''>you</span> <span m=''2271860''>who
  are interested,</span> <span m=''2272520''>by</span> <span m=''2272990''>Moon</span>
  <span m=''2273450''>and</span> <span m=''2273640''>other</span> <span m=''2273830''>people</span>
  <span m=''2274690''>which</span> <span m=''2274860''>describes</span> <span m=''2276170''>a</span>
  <span m=''2276210''>modification</span> <span m=''2276890''>to</span> <span m=''2276960''>the</span>
  <span m=''2277060''>incremental</span> <span m=''2277940''>Minsky-Feinchel-Yochelson</span>
  <span m=''2278700''>algorithm,</span> <span m=''2279500''>and</span> <span m=''2279750''>modification</span>
  <span m=''2280290''>the</span> <span m=''2280370''>Baker</span> <span m=''2280580''>algorithm</span>
  <span m=''2283570''>which</span> <span m=''2284390''>is</span> <span m=''2284780''>more</span>
  <span m=''2285040''>efficient</span> <span m=''2285460''>for</span> <span m=''2285650''>virtual</span>
  <span m=''2285980''>memory</span> <span m=''2286240''>systems.</span> </p><p><span
  m=''2288340''>Well</span> <span m=''2289820''>I</span> <span m=''2289930''>think</span>
  <span m=''2290180''>now</span> <span m=''2290410''>the</span> <span m=''2290630''>mystery</span>
  <span m=''2291080''>to</span> <span m=''2291210''>this</span> <span m=''2291380''>is
  sort of</span> <span m=''2291770''>gone.</span> <span m=''2292840''>And</span> <span
  m=''2293080''>I''d like to</span> <span m=''2293160''>see</span> <span m=''2293390''>if</span>
  <span m=''2293420''>there are</span> <span m=''2293550''>any</span> <span m=''2293660''>questions.</span>
  <span m=''2299780''>Yes.</span> </p><p><span m=''2300810''>AUDIENCE: I</span> <span
  m=''2300860''>saw</span> <span m=''2302110''>one</span> <span m=''2302330''>of</span>
  <span m=''2302440''>you</span> <span m=''2302760''>run</span> <span m=''2303020''>the</span>
  <span m=''2303100''>garbage</span> <span m=''2303470''>collector</span> <span m=''2303760''>on</span>
  <span m=''2303990''>the</span> <span m=''2304100''>systems</span> <span m=''2304490''>upstairs,</span>
  <span m=''2305950''>and</span> <span m=''2306140''>it</span> <span m=''2306330''>seemed</span>
  <span m=''2306680''>to</span> <span m=''2306740''>me</span> <span m=''2306840''>to</span>
  <span m=''2306930''>run</span> <span m=''2307110''>extremely</span> <span m=''2307640''>fast.</span>
  <span m=''2308040''>Did</span> <span m=''2308390''>the</span> <span m=''2308800''>whole</span>
  <span m=''2309010''>thing</span> <span m=''2309260''>take--</span> <span m=''2310190''>does
  it</span> <span m=''2310520''>sweep</span> <span m=''2310810''>through</span> <span
  m=''2310960''>all</span> <span m=''2311120''>of</span> <span m=''2311280''>memory?</span>
  </p><p><span m=''2311880''>PROFESSOR: No.</span> <span m=''2312510''>It</span> <span
  m=''2312670''>swept</span> <span m=''2312800''>through</span> <span m=''2312920''>exactly</span>
  <span m=''2313400''>what</span> <span m=''2313530''>was</span> <span m=''2313650''>needed</span>
  <span m=''2314200''>to</span> <span m=''2314480''>copy</span> <span m=''2314870''>the</span>
  <span m=''2314970''>useful</span> <span m=''2315260''>structure.</span> <span m=''2317320''>It''s</span>
  <span m=''2317460''>a</span> <span m=''2317510''>copying</span> <span m=''2317900''>collector.</span>
  <span m=''2320030''>And</span> <span m=''2320220''>it is</span> <span m=''2320420''>very</span>
  <span m=''2320600''>fast.</span> <span m=''2321910''>On</span> <span m=''2322170''>the</span>
  <span m=''2322430''>whole,</span> <span m=''2322810''>I</span> <span m=''2322900''>suppose</span>
  <span m=''2323330''>to</span> <span m=''2323870''>copy--</span> <span m=''2325090''>in</span>
  <span m=''2325190''>a</span> <span m=''2325240''>Bobcat--</span> <span m=''2327000''>to</span>
  <span m=''2327160''>copy,</span> <span m=''2328370''>I</span> <span m=''2328590''>think,</span>
  <span m=''2330170''>a</span> <span m=''2330330''>three</span> <span m=''2330470''>megabyte</span>
  <span m=''2330880''>thing</span> <span m=''2330990''>or</span> <span m=''2331100''>something</span>
  <span m=''2331500''>is</span> <span m=''2332450''>less</span> <span m=''2332680''>than</span>
  <span m=''2332770''>a</span> <span m=''2332820''>second,</span> <span m=''2335150''>real</span>
  <span m=''2335380''>time.</span> <span m=''2336800''>Really,</span> <span m=''2337230''>these</span>
  <span m=''2337390''>are</span> <span m=''2337450''>very</span> <span m=''2337670''>small</span>
  <span m=''2337920''>programs.</span> <span m=''2338690''>One</span> <span m=''2338920''>thing</span>
  <span m=''2339100''>you should</span> <span m=''2339200''>realise</span> <span m=''2341050''>is</span>
  <span m=''2341340''>that</span> <span m=''2343070''>garbage</span> <span m=''2343330''>collectors</span>
  <span m=''2343600''>have</span> <span m=''2343810''>to</span> <span m=''2343890''>be</span>
  <span m=''2344010''>small.</span> <span m=''2345400''>Not</span> <span m=''2345700''>because</span>
  <span m=''2346000''>they</span> <span m=''2346090''>have</span> <span m=''2346250''>to</span>
  <span m=''2346340''>be</span> <span m=''2346720''>fast,</span> <span m=''2347830''>but</span>
  <span m=''2348050''>because</span> <span m=''2348360''>no</span> <span m=''2348510''>one</span>
  <span m=''2348650''>can</span> <span m=''2348770''>debug</span> <span m=''2349200''>a</span>
  <span m=''2349250''>complicated</span> <span m=''2349810''>garbage</span> <span
  m=''2350120''>collector.</span> <span m=''2351340''>A</span> <span m=''2351440''>garbage</span>
  <span m=''2351740''>collector,</span> <span m=''2352120''>if</span> <span m=''2352270''>it</span>
  <span m=''2352350''>doesn''t</span> <span m=''2352620''>work,</span> <span m=''2354110''>will</span>
  <span m=''2354480''>trash</span> <span m=''2354900''>your</span> <span m=''2355000''>memory</span>
  <span m=''2355320''>in</span> <span m=''2355420''>such</span> <span m=''2355610''>a</span>
  <span m=''2355650''>way</span> <span m=''2355780''>that</span> <span m=''2355930''>you</span>
  <span m=''2356060''>cannot</span> <span m=''2356390''>figure</span> <span m=''2356590''>out</span>
  <span m=''2356710''>what</span> <span m=''2356870''>the</span> <span m=''2356940''>hell</span>
  <span m=''2357120''>happened.</span> <span m=''2358350''>You</span> <span m=''2358450''>need</span>
  <span m=''2358620''>an</span> <span m=''2358710''>audit</span> <span m=''2359210''>trail.</span>
  <span m=''2360660''>Because</span> <span m=''2361030''>it</span> <span m=''2361120''>rearranges</span>
  <span m=''2361580''>everything,</span> <span m=''2361990''>and</span> <span m=''2362280''>how
  do you</span> <span m=''2362460''>know</span> <span m=''2362570''>what</span> <span
  m=''2362670''>happened</span> <span m=''2363020''>there?</span> </p><p><span m=''2363740''>So</span>
  <span m=''2364180''>this</span> <span m=''2364470''>is</span> <span m=''2364570''>the</span>
  <span m=''2364690''>only</span> <span m=''2364960''>kind</span> <span m=''2365110''>of</span>
  <span m=''2365270''>program</span> <span m=''2365940''>that</span> <span m=''2366940''>it</span>
  <span m=''2367110''>really,</span> <span m=''2367480''>seriously</span> <span m=''2367940''>matters</span>
  <span m=''2368560''>if</span> <span m=''2368670''>you</span> <span m=''2368780''>stare</span>
  <span m=''2369040''>at it</span> <span m=''2369320''>long</span> <span m=''2369600''>enough</span>
  <span m=''2369770''>so</span> <span m=''2369900''>you</span> <span m=''2370100''>believe</span>
  <span m=''2370640''>that</span> <span m=''2370760''>it</span> <span m=''2370830''>works.</span>
  <span m=''2371970''>And</span> <span m=''2372180''>sort</span> <span m=''2372410''>of</span>
  <span m=''2372510''>prove</span> <span m=''2372810''>it to</span> <span m=''2372920''>yourself.</span>
  <span m=''2375100''>So there''s</span> <span m=''2375310''>no</span> <span m=''2375420''>way</span>
  <span m=''2375620''>to debug</span> <span m=''2375740''>it.</span> <span m=''2376940''>And</span>
  <span m=''2377120''>that</span> <span m=''2377310''>takes</span> <span m=''2378250''>it</span>
  <span m=''2378330''>being</span> <span m=''2378510''>small</span> <span m=''2378790''>enough
  so</span> <span m=''2378990''>you can</span> <span m=''2379230''>hold it in</span>
  <span m=''2379500''>your</span> <span m=''2379640''>head.</span> <span m=''2381690''>Garbage</span>
  <span m=''2382010''>collectors</span> <span m=''2382400''>are</span> <span m=''2382660''>special</span>
  <span m=''2383300''>in</span> <span m=''2383350''>this</span> <span m=''2383550''>way.</span>
  <span m=''2385020''>So</span> <span m=''2385240''>every</span> <span m=''2385510''>reasonable</span>
  <span m=''2385940''>garbage</span> <span m=''2386210''>collector has</span> <span
  m=''2386550''>gotten</span> <span m=''2386760''>small,</span> <span m=''2387130''>and
  generally</span> <span m=''2387530''>small</span> <span m=''2387740''>programs are</span>
  <span m=''2388070''>fast.</span> <span m=''2392120''>Yes.</span> </p><p><span m=''2392430''>AUDIENCE:
  Can</span> <span m=''2392560''>you repeat the</span> <span m=''2392690''>name</span>
  <span m=''2393010''>of</span> <span m=''2393220''>this</span> <span m=''2393650''>technique</span>
  <span m=''2394050''>once</span> <span m=''2394260''>again?</span> </p><p><span m=''2394510''>PROFESSOR:
  That''s</span> <span m=''2394940''>the</span> <span m=''2395050''>Minsky-Feinchel-Yochelson</span>
  <span m=''2396220''>garbage</span> <span m=''2396510''>collector.</span> </p><p><span
  m=''2398420''>AUDIENCE: You got that?</span> </p><p><span m=''2399340''>PROFESSOR:
  Minsky</span> <span m=''2399530''>invented</span> <span m=''2399870''>it in</span>
  <span m=''2400030''>''61</span> <span m=''2400810''>for</span> <span m=''2400930''>the</span>
  <span m=''2401050''>RLE</span> <span m=''2401360''>PDP-1.</span> <span m=''2402210''>A</span>
  <span m=''2402350''>version</span> <span m=''2402910''>of</span> <span m=''2403060''>it</span>
  <span m=''2404170''>was</span> <span m=''2404450''>developed</span> <span m=''2404900''>and</span>
  <span m=''2405450''>elaborated</span> <span m=''2406660''>to</span> <span m=''2406740''>be</span>
  <span m=''2406840''>used</span> <span m=''2407140''>in</span> <span m=''2407410''>Multics</span>
  <span m=''2408230''>Maclisp</span> <span m=''2409100''>by Feinchel</span> <span
  m=''2409395''>and</span> <span m=''2409690''>Yochelson</span> <span m=''2411500''>in</span>
  <span m=''2412010''>somewhere</span> <span m=''2412410''>around</span> <span m=''2412480''>1968</span>
  <span m=''2413320''>or</span> <span m=''2413920''>''69.</span> </p><p><span m=''2419570''>OK.</span>
  <span m=''2420650''>Let''s</span> <span m=''2420820''>take</span> <span m=''2420970''>a</span>
  <span m=''2421010''>break.</span> </p><p><span m=''2422640''>[MUSIC: "JESU, JOY
  OF MAN''S DESIRING" BY JOHANN SEBASTIAN BACH]</span> </p><p><span m=''2477310''>PROFESSOR:
  Well</span> <span m=''2477870''>we''ve</span> <span m=''2478030''>come</span> <span
  m=''2478210''>to</span> <span m=''2478270''>the</span> <span m=''2478390''>end</span>
  <span m=''2478520''>of</span> <span m=''2478610''>this</span> <span m=''2479080''>subject,</span>
  <span m=''2480200''>and</span> <span m=''2481600''>we''ve</span> <span m=''2481890''>already</span>
  <span m=''2482190''>shown</span> <span m=''2482480''>you</span> <span m=''2482640''>a</span>
  <span m=''2482730''>universal</span> <span m=''2483280''>machine</span> <span m=''2484590''>which</span>
  <span m=''2484790''>is</span> <span m=''2484860''>down</span> <span m=''2485140''>to</span>
  <span m=''2486020''>evaluator.</span> <span m=''2486740''>It''s down to</span> <span
  m=''2487135''>the</span> <span m=''2487530''>level</span> <span m=''2487770''>of</span>
  <span m=''2487820''>detail</span> <span m=''2488210''>you</span> <span m=''2488380''>could</span>
  <span m=''2488480''>imagine</span> <span m=''2488880''>you</span> <span m=''2488980''>could</span>
  <span m=''2489130''>make</span> <span m=''2489370''>one.</span> <span m=''2490420''>This</span>
  <span m=''2490650''>is</span> <span m=''2490760''>a</span> <span m=''2490830''>particular</span>
  <span m=''2492330''>implementation</span> <span m=''2492960''>of</span> <span m=''2493060''>Lisp,</span>
  <span m=''2494050''>built</span> <span m=''2494390''>on</span> <span m=''2495270''>one</span>
  <span m=''2495530''>of</span> <span m=''2495800''>those</span> <span m=''2496260''>scheme</span>
  <span m=''2496620''>chips</span> <span m=''2496840''>that</span> <span m=''2496910''>was</span>
  <span m=''2497030''>talked</span> <span m=''2497290''>about</span> <span m=''2497530''>yesterday,</span>
  <span m=''2498120''>sitting</span> <span m=''2498450''>over</span> <span m=''2498600''>here.</span>
  <span m=''2499180''>This</span> <span m=''2499580''>is</span> <span m=''2499690''>mostly</span>
  <span m=''2500100''>interface</span> <span m=''2500790''>to</span> <span m=''2501140''>somebody''s</span>
  <span m=''2501590''>memory</span> <span m=''2502480''>with</span> <span m=''2502940''>a</span>
  <span m=''2502990''>little</span> <span m=''2503300''>bit</span> <span m=''2503430''>of</span>
  <span m=''2503520''>timing</span> <span m=''2503930''>and</span> <span m=''2504070''>other</span>
  <span m=''2504200''>such</span> <span m=''2504430''>stuff.</span> <span m=''2505010''>But</span>
  <span m=''2505490''>this</span> <span m=''2505650''>fellow</span> <span m=''2505880''>actually</span>
  <span m=''2506220''>ran</span> <span m=''2506490''>Lisp</span> <span m=''2506750''>at
  a</span> <span m=''2508030''>fairly</span> <span m=''2508360''>reasonable</span>
  <span m=''2508760''>rate,</span> <span m=''2509430''>as</span> <span m=''2509590''>interpretive.</span>
  <span m=''2510610''>It</span> <span m=''2510840''>ran</span> <span m=''2511400''>Lisp</span>
  <span m=''2511630''>as fast as</span> <span m=''2512270''>a</span> <span m=''2512910''>DEC</span>
  <span m=''2513120''>PDP-10</span> <span m=''2514350''>back</span> <span m=''2514610''>in</span>
  <span m=''2514800''>1979.</span> <span m=''2516500''>And</span> <span m=''2516650''>so</span>
  <span m=''2517660''>it''s</span> <span m=''2517960''>gotten</span> <span m=''2518660''>pretty</span>
  <span m=''2519100''>hardware.</span> <span m=''2519870''>Pretty</span> <span m=''2520360''>concrete.</span>
  </p><p><span m=''2522470''>We''ve</span> <span m=''2522680''>also</span> <span m=''2523940''>downed</span>
  <span m=''2524280''>you</span> <span m=''2524490''>a</span> <span m=''2524550''>bit</span>
  <span m=''2524770''>with</span> <span m=''2524910''>the</span> <span m=''2525000''>things</span>
  <span m=''2525260''>you</span> <span m=''2525400''>can</span> <span m=''2525660''>compute.</span>
  <span m=''2527370''>But</span> <span m=''2527600''>is</span> <span m=''2527720''>it</span>
  <span m=''2528010''>the</span> <span m=''2528210''>case</span> <span m=''2528550''>that</span>
  <span m=''2528880''>there</span> <span m=''2529540''>are</span> <span m=''2529580''>things</span>
  <span m=''2529800''>we</span> <span m=''2529910''>can''t</span> <span m=''2530170''>compute?</span>
  <span m=''2531850''>And</span> <span m=''2531990''>so</span> <span m=''2532130''>I''d</span>
  <span m=''2532180''>like</span> <span m=''2532460''>to</span> <span m=''2532730''>end</span>
  <span m=''2532950''>this</span> <span m=''2533180''>with</span> <span m=''2533740''>showing</span>
  <span m=''2534090''>you</span> <span m=''2534240''>some</span> <span m=''2534450''>things</span>
  <span m=''2534690''>that</span> <span m=''2534800''>you''d</span> <span m=''2534900''>like</span>
  <span m=''2535140''>be</span> <span m=''2535250''>able</span> <span m=''2535390''>to</span>
  <span m=''2535450''>compute</span> <span m=''2536330''>that</span> <span m=''2536610''>you</span>
  <span m=''2536900''>can''t.</span> <span m=''2538190''>The</span> <span m=''2538750''>answer</span>
  <span m=''2539060''>is</span> <span m=''2539170''>yes,</span> <span m=''2539610''>there</span>
  <span m=''2539760''>are</span> <span m=''2539790''>things</span> <span m=''2540040''>you</span>
  <span m=''2540160''>can''t</span> <span m=''2540270''>compute.</span> </p><p><span
  m=''2542720''>For</span> <span m=''2542910''>example,</span> <span m=''2544530''>something</span>
  <span m=''2544910''>you''d</span> <span m=''2545060''>really</span> <span m=''2545410''>like</span>
  <span m=''2547900''>is--</span> <span m=''2548200''>if</span> <span m=''2548350''>you''re</span>
  <span m=''2548500''>writing</span> <span m=''2548730''>[UNINTELLIGIBLE],</span>
  <span m=''2549860''>you''d</span> <span m=''2549970''>like</span> <span m=''2550140''>a</span>
  <span m=''2550210''>program</span> <span m=''2550860''>that</span> <span m=''2550980''>would</span>
  <span m=''2551100''>check</span> <span m=''2551590''>that the</span> <span m=''2552480''>thing</span>
  <span m=''2552660''>you''re</span> <span m=''2552800''>going</span> <span m=''2552990''>to</span>
  <span m=''2553060''>do</span> <span m=''2553430''>will</span> <span m=''2553600''>work.</span>
  <span m=''2554630''>Wouldn''t</span> <span m=''2554770''>that</span> <span m=''2554950''>be</span>
  <span m=''2555040''>nice?</span> <span m=''2556080''>You''d</span> <span m=''2556210''>like</span>
  <span m=''2556450''>something</span> <span m=''2556780''>that</span> <span m=''2556890''>would</span>
  <span m=''2557010''>catch</span> <span m=''2557260''>infinite</span> <span m=''2557600''>loops,</span>
  <span m=''2557960''>for</span> <span m=''2558060''>example,</span> <span m=''2559550''>in</span>
  <span m=''2559700''>programs</span> <span m=''2560120''>that were</span> <span m=''2560230''>written</span>
  <span m=''2560500''>by</span> <span m=''2561930''>users.</span> <span m=''2563190''>But</span>
  <span m=''2563390''>in</span> <span m=''2563450''>general</span> <span m=''2563760''>you</span>
  <span m=''2563920''>can''t</span> <span m=''2564190''>write</span> <span m=''2564430''>such</span>
  <span m=''2564580''>a</span> <span m=''2564630''>program</span> <span m=''2565430''>that
  will</span> <span m=''2565570''>read</span> <span m=''2565890''>any</span> <span
  m=''2566100''>program</span> <span m=''2566450''>and</span> <span m=''2566510''>determine</span>
  <span m=''2566900''>whether</span> <span m=''2567140''>or</span> <span m=''2567190''>not</span>
  <span m=''2568500''>it''s</span> <span m=''2568680''>an</span> <span m=''2568760''>infinite</span>
  <span m=''2569050''>loop.</span> </p><p><span m=''2570990''>Let</span> <span m=''2571110''>me</span>
  <span m=''2571220''>show</span> <span m=''2571390''>you</span> <span m=''2571530''>that.
  It''s</span> <span m=''2571840''>a</span> <span m=''2571880''>little</span> <span
  m=''2572080''>bit</span> <span m=''2572230''>of</span> <span m=''2572680''>a</span>
  <span m=''2572800''>minor</span> <span m=''2573130''>mathematics.</span> <span m=''2578780''>Let''s</span>
  <span m=''2579000''>imagine</span> <span m=''2579900''>that</span> <span m=''2580310''>we</span>
  <span m=''2580410''>just</span> <span m=''2580600''>had</span> <span m=''2580680''>a</span>
  <span m=''2580770''>mathematical</span> <span m=''2581360''>function</span> <span
  m=''2581870''>before</span> <span m=''2582120''>we</span> <span m=''2582200''>start.</span>
  <span m=''2582620''>And</span> <span m=''2582780''>there</span> <span m=''2582960''>is</span>
  <span m=''2583070''>one,</span> <span m=''2583910''>called</span> <span m=''2584190''>s,</span>
  <span m=''2585650''>which</span> <span m=''2585920''>takes</span> <span m=''2586650''>a</span>
  <span m=''2586780''>procedure</span> <span m=''2592770''>and</span> <span m=''2592980''>its</span>
  <span m=''2593110''>argument,</span> <span m=''2593690''>a.</span> <span m=''2599320''>And</span>
  <span m=''2599510''>what</span> <span m=''2599730''>s</span> <span m=''2600040''>does</span>
  <span m=''2601760''>is</span> <span m=''2601910''>it</span> <span m=''2602030''>determines</span>
  <span m=''2603240''>whether</span> <span m=''2603610''>or</span> <span m=''2603670''>not</span>
  <span m=''2604020''>it''s</span> <span m=''2604250''>safe</span> <span m=''2604590''>to</span>
  <span m=''2604730''>run</span> <span m=''2605030''>p</span> <span m=''2605370''>on</span>
  <span m=''2605610''>a.</span> <span m=''2606632''>And</span> <span m=''2606970''>what</span>
  <span m=''2607150''>I</span> <span m=''2607210''>mean</span> <span m=''2607420''>by</span>
  <span m=''2607570''>that</span> <span m=''2607710''>is</span> <span m=''2607850''>this:</span>
  <span m=''2608550''>it''s</span> <span m=''2608810''>true</span> <span m=''2611950''>if</span>
  <span m=''2613590''>p</span> <span m=''2614030''>applied</span> <span m=''2614500''>to</span>
  <span m=''2614640''>a</span> <span m=''2615820''>will</span> <span m=''2616000''>converge</span>
  <span m=''2621540''>to</span> <span m=''2621680''>a</span> <span m=''2621820''>value</span>
  <span m=''2624600''>without</span> <span m=''2624930''>an</span> <span m=''2625030''>error.</span>
  <span m=''2632365''>And</span> <span m=''2632840''>it''s</span> <span m=''2633110''>false</span>
  <span m=''2636140''>if</span> <span m=''2636670''>p of a</span> <span m=''2639950''>loops</span>
  <span m=''2640260''>forever</span> <span m=''2646050''>or</span> <span m=''2646230''>makes</span>
  <span m=''2646450''>an</span> <span m=''2646560''>error.</span> </p><p><span m=''2655000''>Now
  that''s</span> <span m=''2655590''>surely</span> <span m=''2656650''>a</span> <span
  m=''2656740''>function.</span> <span m=''2658780''>There</span> <span m=''2659030''>is</span>
  <span m=''2659120''>some</span> <span m=''2659540''>for</span> <span m=''2659740''>every</span>
  <span m=''2660040''>procedure</span> <span m=''2661280''>and</span> <span m=''2661460''>for</span>
  <span m=''2661590''>every</span> <span m=''2661830''>argument</span> <span m=''2662200''>you</span>
  <span m=''2662320''>could</span> <span m=''2662460''>give</span> <span m=''2662660''>it</span>
  <span m=''2663676''>that</span> <span m=''2664060''>is</span> <span m=''2664320''>either</span>
  <span m=''2664560''>true</span> <span m=''2664860''>or</span> <span m=''2664940''>false</span>
  <span m=''2665900''>that it</span> <span m=''2666230''>converges</span> <span m=''2666850''>without</span>
  <span m=''2667190''>making</span> <span m=''2667440''>an</span> <span m=''2667510''>error.</span>
  <span m=''2668440''>And</span> <span m=''2668600''>you</span> <span m=''2668680''>could</span>
  <span m=''2668800''>make</span> <span m=''2668980''>a</span> <span m=''2669020''>giant</span>
  <span m=''2669410''>table</span> <span m=''2669730''>of</span> <span m=''2669910''>them.</span>
  <span m=''2671770''>But</span> <span m=''2672460''>the</span> <span m=''2672520''>question</span>
  <span m=''2672850''>is,</span> <span m=''2672990''>can</span> <span m=''2673110''>you</span>
  <span m=''2673220''>write</span> <span m=''2673440''>a</span> <span m=''2673500''>procedure</span>
  <span m=''2674100''>that</span> <span m=''2674280''>compute</span> <span m=''2674710''>the</span>
  <span m=''2674820''>values</span> <span m=''2675260''>of</span> <span m=''2675320''>this</span>
  <span m=''2675480''>function?</span> <span m=''2677430''>Well</span> <span m=''2677630''>let''s</span>
  <span m=''2677800''>assume</span> <span m=''2678120''>that</span> <span m=''2678250''>we</span>
  <span m=''2678390''>can.</span> </p><p><span m=''2679720''>Suppose</span> <span
  m=''2684260''>that</span> <span m=''2684590''>we</span> <span m=''2684680''>have</span>
  <span m=''2684780''>a</span> <span m=''2684890''>procedure</span> <span m=''2691910''>called</span>
  <span m=''2692260''>"safe"</span> <span m=''2696450''>that</span> <span m=''2698740''>computes</span>
  <span m=''2698950''>the</span> <span m=''2699070''>value</span> <span m=''2699520''>of
  s.</span> <span m=''2712170''>Now</span> <span m=''2712720''>I''m going</span> <span
  m=''2713090''>to</span> <span m=''2713130''>show</span> <span m=''2713370''>you</span>
  <span m=''2713820''>by</span> <span m=''2714020''>several</span> <span m=''2714400''>methods</span>
  <span m=''2715980''>that</span> <span m=''2717620''>you</span> <span m=''2717830''>can''t</span>
  <span m=''2718130''>do</span> <span m=''2718280''>this.</span> <span m=''2719760''>The</span>
  <span m=''2720030''>easiest</span> <span m=''2720440''>one,</span> <span m=''2720660''>or</span>
  <span m=''2720730''>the</span> <span m=''2720910''>first</span> <span m=''2721100''>one,</span>
  <span m=''2721310''>let''s</span> <span m=''2721620''>define</span> <span m=''2721910''>a</span>
  <span m=''2721960''>procedure</span> <span m=''2722300''>called</span> <span m=''2722540''>diag1.</span>
  <span m=''2723810''>Given</span> <span m=''2724050''>that</span> <span m=''2724150''>we</span>
  <span m=''2724290''>have</span> <span m=''2724540''>safe,</span> <span m=''2725240''>we</span>
  <span m=''2725430''>can</span> <span m=''2725660''>define</span> <span m=''2726070''>diag1</span>
  <span m=''2737770''>to</span> <span m=''2737990''>be</span> <span m=''2738130''>the</span>
  <span m=''2738250''>procedure</span> <span m=''2739830''>of</span> <span m=''2740030''>one</span>
  <span m=''2740230''>argument,</span> <span m=''2741020''>p,</span> <span m=''2742540''>which</span>
  <span m=''2742760''>has</span> <span m=''2742890''>the</span> <span m=''2743010''>following</span>
  <span m=''2743430''>properties.</span> <span m=''2744780''>If</span> <span m=''2748170''>if</span>
  <span m=''2748310''>it''s</span> <span m=''2748490''>safe</span> <span m=''2749100''>to</span>
  <span m=''2749230''>apply</span> <span m=''2749690''>p</span> <span m=''2749950''>to</span>
  <span m=''2750140''>itself,</span> <span m=''2753390''>then</span> <span m=''2753660''>I</span>
  <span m=''2753780''>wish</span> <span m=''2754030''>to</span> <span m=''2754190''>have</span>
  <span m=''2754490''>an</span> <span m=''2754620''>infinite</span> <span m=''2754980''>loop.</span>
  <span m=''2759330''>Otherwise</span> <span m=''2759830''>I''m</span> <span m=''2759900''>going</span>
  <span m=''2759960''>to</span> <span m=''2760020''>return</span> <span m=''2760460''>3.</span>
  <span m=''2763680''>Remember</span> <span m=''2763830''>it was</span> <span m=''2763990''>42.</span>
  <span m=''2764470''>What''s</span> <span m=''2764720''>the</span> <span m=''2765300''>answer</span>
  <span m=''2765590''>to</span> <span m=''2765640''>the</span> <span m=''2765760''>big</span>
  <span m=''2765910''>question?</span> <span m=''2767060''>Where</span> <span m=''2767260''>of</span>
  <span m=''2767340''>course</span> <span m=''2767560''>we</span> <span m=''2767660''>know
  what</span> <span m=''2768070''>an infinite</span> <span m=''2768250''>loop is.</span>
  <span m=''2772050''>Infinite</span> <span m=''2772340''>loop,</span> <span m=''2773700''>to</span>
  <span m=''2774000''>be</span> <span m=''2774110''>a</span> <span m=''2774170''>procedure</span>
  <span m=''2774810''>of</span> <span m=''2775160''>no</span> <span m=''2775380''>arguments,</span>
  <span m=''2776130''>which</span> <span m=''2776360''>is</span> <span m=''2776540''>that</span>
  <span m=''2776720''>nice</span> <span m=''2776970''>lambda</span> <span m=''2777290''>calculus</span>
  <span m=''2777770''>loop.</span> <span m=''2778430''>Lambda of</span> <span m=''2778720''>x,</span>
  <span m=''2779640''>x of x,</span> <span m=''2781440''>applied</span> <span m=''2781890''>to</span>
  <span m=''2782030''>lambda</span> <span m=''2782370''>of</span> <span m=''2782890''>x,</span>
  <span m=''2784010''>x</span> <span m=''2784390''>of x.</span> <span m=''2784680''>So
  there''s</span> <span m=''2784970''>nothing</span> <span m=''2785270''>left</span>
  <span m=''2785470''>to</span> <span m=''2785550''>the</span> <span m=''2785630''>imagination</span>
  <span m=''2786280''>here.</span> </p><p><span m=''2789830''>Well</span> <span m=''2789970''>let''s</span>
  <span m=''2790160''>see</span> <span m=''2790290''>what</span> <span m=''2790410''>the</span>
  <span m=''2790490''>story</span> <span m=''2790930''>is.</span> <span m=''2792500''>I''m</span>
  <span m=''2792670''>supposing</span> <span m=''2793200''>it''s</span> <span m=''2793350''>the</span>
  <span m=''2793460''>case</span> <span m=''2795560''>that</span> <span m=''2796210''>we</span>
  <span m=''2797100''>worry</span> <span m=''2797380''>about</span> <span m=''2797820''>the</span>
  <span m=''2798100''>procedure</span> <span m=''2799030''>called</span> <span m=''2799350''>diag1</span>
  <span m=''2802290''>applied</span> <span m=''2802690''>to</span> <span m=''2802780''>diag1.</span>
  <span m=''2805860''>Well</span> <span m=''2806330''>what</span> <span m=''2806740''>could
  it</span> <span m=''2806860''>possibly</span> <span m=''2807370''>be?</span> <span
  m=''2809970''>Well</span> <span m=''2810920''>I</span> <span m=''2811080''>don''t</span>
  <span m=''2811210''>know.</span> <span m=''2811390''>We''re</span> <span m=''2811510''>going</span>
  <span m=''2811590''>to</span> <span m=''2811660''>substitute</span> <span m=''2812260''>diag1</span>
  <span m=''2813250''>for</span> <span m=''2813850''>p</span> <span m=''2814640''>in</span>
  <span m=''2814790''>the</span> <span m=''2814870''>body</span> <span m=''2815170''>here.</span>
  <span m=''2817310''>Well</span> <span m=''2817990''>is</span> <span m=''2818170''>it</span>
  <span m=''2818300''>safe</span> <span m=''2818630''>to</span> <span m=''2818830''>compute</span>
  <span m=''2819210''>diag1</span> <span m=''2819730''>of</span> <span m=''2819800''>diag1?</span>
  <span m=''2820220''>I</span> <span m=''2820380''>don''t</span> <span m=''2820500''>know.</span>
  <span m=''2820780''>There</span> <span m=''2820890''>are</span> <span m=''2820930''>two</span>
  <span m=''2821060''>possibilities.</span> <span m=''2823400''>If</span> <span m=''2823580''>it''s</span>
  <span m=''2823720''>safe</span> <span m=''2823940''>to</span> <span m=''2824090''>compute</span>
  <span m=''2824570''>diag1</span> <span m=''2824690''>of</span> <span m=''2824740''>diag1</span>
  <span m=''2825980''>that means</span> <span m=''2826160''>it</span> <span m=''2826260''>shouldn''t</span>
  <span m=''2826590''>loop.</span> <span m=''2828490''>That</span> <span m=''2828680''>means</span>
  <span m=''2828790''>I</span> <span m=''2828900''>go to</span> <span m=''2829000''>here,</span>
  <span m=''2829230''>but</span> <span m=''2829340''>then I</span> <span m=''2829540''>produce</span>
  <span m=''2829970''>an</span> <span m=''2830030''>infinite loop.</span> <span m=''2830560''>So</span>
  <span m=''2830720''>it</span> <span m=''2830800''>can''t</span> <span m=''2831010''>be</span>
  <span m=''2831240''>safe.</span> <span m=''2832210''>But</span> <span m=''2832480''>if
  it''s</span> <span m=''2832650''>not</span> <span m=''2832920''>safe</span> <span
  m=''2833170''>to</span> <span m=''2833280''>compute</span> <span m=''2833570''>diag1</span>
  <span m=''2833990''>of</span> <span m=''2834040''>diag1</span> <span m=''2834930''>then
  the</span> <span m=''2835180''>answer</span> <span m=''2835420''>to</span> <span
  m=''2835490''>this</span> <span m=''2835690''>is</span> <span m=''2835810''>3.</span>
  <span m=''2836020''>But</span> <span m=''2836140''>that''s</span> <span m=''2836350''>diag1</span>
  <span m=''2836630''>of</span> <span m=''2836720''>diag1,</span> <span m=''2837240''>so
  it</span> <span m=''2837360''>had</span> <span m=''2837510''>to</span> <span m=''2837550''>be</span>
  <span m=''2837660''>safe.</span> </p><p><span m=''2840530''>So</span> <span m=''2840740''>therefore</span>
  <span m=''2842590''>by</span> <span m=''2842780''>contradiction</span> <span m=''2844440''>you</span>
  <span m=''2844590''>cannot</span> <span m=''2845470''>produce</span> <span m=''2845890''>safe.</span>
  <span m=''2847470''>For</span> <span m=''2847620''>those</span> <span m=''2847870''>of</span>
  <span m=''2847940''>you</span> <span m=''2848170''>who were</span> <span m=''2848260''>boggled</span>
  <span m=''2848610''>by</span> <span m=''2848810''>that</span> <span m=''2849090''>one</span>
  <span m=''2850360''>I''m</span> <span m=''2850450''>going to</span> <span m=''2850680''>say</span>
  <span m=''2850910''>it</span> <span m=''2851020''>again,</span> <span m=''2851400''>in</span>
  <span m=''2851450''>a</span> <span m=''2851470''>different</span> <span m=''2851750''>way.</span>
  <span m=''2852820''>Listen</span> <span m=''2852970''>to</span> <span m=''2853160''>one</span>
  <span m=''2853290''>more</span> <span m=''2853500''>alternative.</span> <span m=''2855530''>Let''s</span>
  <span m=''2855760''>define</span> <span m=''2856200''>diag2.</span> <span m=''2859840''>These
  are</span> <span m=''2860170''>named</span> <span m=''2860540''>diag</span> <span
  m=''2862770''>because</span> <span m=''2863110''>of</span> <span m=''2863220''>Cantor''s</span>
  <span m=''2863560''>diagonal</span> <span m=''2864130''>argument.</span> <span m=''2865260''>These</span>
  <span m=''2865440''>are</span> <span m=''2865540''>instances</span> <span m=''2866590''>of</span>
  <span m=''2867150''>a</span> <span m=''2867260''>famous</span> <span m=''2867610''>argument</span>
  <span m=''2867940''>which</span> <span m=''2868060''>was</span> <span m=''2868180''>originally</span>
  <span m=''2868570''>used</span> <span m=''2868700''>by</span> <span m=''2869490''>Cantor</span>
  <span m=''2870440''>in</span> <span m=''2870620''>the</span> <span m=''2871310''>late</span>
  <span m=''2871520''>part</span> <span m=''2871670''>of the</span> <span m=''2871820''>last</span>
  <span m=''2872070''>century</span> <span m=''2872600''>to</span> <span m=''2872980''>prove</span>
  <span m=''2873210''>that</span> <span m=''2873350''>the</span> <span m=''2873650''>real</span>
  <span m=''2873930''>numbers</span> <span m=''2875120''>were</span> <span m=''2875320''>not</span>
  <span m=''2875490''>countable,</span> <span m=''2876420''>that</span> <span m=''2876770''>there</span>
  <span m=''2877040''>are</span> <span m=''2877090''>too</span> <span m=''2877240''>many</span>
  <span m=''2877460''>real</span> <span m=''2877690''>numbers</span> <span m=''2878070''>to</span>
  <span m=''2878160''>be</span> <span m=''2878250''>counted</span> <span m=''2878630''>by</span>
  <span m=''2878880''>integers.</span> <span m=''2880190''>That there</span> <span
  m=''2880510''>are</span> <span m=''2880540''>more</span> <span m=''2880890''>points</span>
  <span m=''2881230''>on</span> <span m=''2881300''>a</span> <span m=''2881380''>line,</span>
  <span m=''2881790''>for</span> <span m=''2881930''>example,</span> <span m=''2882470''>than</span>
  <span m=''2882710''>there</span> <span m=''2882950''>are</span> <span m=''2883590''>counting</span>
  <span m=''2883960''>numbers.</span> <span m=''2885260''>It</span> <span m=''2885490''>may</span>
  <span m=''2885670''>or</span> <span m=''2885720''>may</span> <span m=''2885870''>not</span>
  <span m=''2886090''>be</span> <span m=''2886210''>obvious,</span> <span m=''2886730''>and</span>
  <span m=''2886800''>I</span> <span m=''2886870''>don''t</span> <span m=''2887030''>want</span>
  <span m=''2887110''>to</span> <span m=''2887190''>get</span> <span m=''2887330''>into</span>
  <span m=''2887500''>that</span> <span m=''2887760''>now.</span> </p><p><span m=''2890900''>But</span>
  <span m=''2891500''>diag2</span> <span m=''2893560''>is</span> <span m=''2893750''>again</span>
  <span m=''2894110''>a</span> <span m=''2894180''>procedure of</span> <span m=''2894520''>one</span>
  <span m=''2894860''>argument</span> <span m=''2895340''>p.</span> <span m=''2895820''>It''s</span>
  <span m=''2896030''>almost</span> <span m=''2896290''>the</span> <span m=''2896370''>same</span>
  <span m=''2896650''>as</span> <span m=''2896720''>the</span> <span m=''2896790''>previous</span>
  <span m=''2897150''>one,</span> <span m=''2897890''>which</span> <span m=''2898150''>is,</span>
  <span m=''2898720''>if</span> <span m=''2899220''>it''s</span> <span m=''2899400''>safe</span>
  <span m=''2900810''>to</span> <span m=''2901080''>compute</span> <span m=''2902640''>p</span>
  <span m=''2903430''>on</span> <span m=''2903770''>p,</span> <span m=''2905240''>then</span>
  <span m=''2905540''>I''m</span> <span m=''2905690''>going</span> <span m=''2905910''>to</span>
  <span m=''2906150''>produce--</span> <span m=''2909310''>then</span> <span m=''2910050''>I</span>
  <span m=''2910180''>want</span> <span m=''2910310''>to</span> <span m=''2910440''>compute</span>
  <span m=''2911650''>some</span> <span m=''2911910''>other</span> <span m=''2912230''>things</span>
  <span m=''2914010''>other</span> <span m=''2914310''>than</span> <span m=''2916470''>p</span>
  <span m=''2916570''>of</span> <span m=''2917120''>p.</span> <span m=''2918960''>Otherwise</span>
  <span m=''2919420''>I''m going to</span> <span m=''2919570''>put</span> <span m=''2919700''>out</span>
  <span m=''2919910''>false.</span> <span m=''2923600''>Where</span> <span m=''2923870''>other</span>
  <span m=''2924110''>then</span> <span m=''2924580''>it</span> <span m=''2924900''>says,</span>
  <span m=''2925480''>whatever</span> <span m=''2925910''>p</span> <span m=''2926070''>of</span>
  <span m=''2926220''>p,</span> <span m=''2926320''>I''m</span> <span m=''2926450''>going
  to</span> <span m=''2926510''>put</span> <span m=''2926750''>out something</span>
  <span m=''2927080''>else.</span> </p><p><span m=''2928880''>I can</span> <span m=''2928990''>give</span>
  <span m=''2929180''>you</span> <span m=''2929270''>an</span> <span m=''2929330''>example</span>
  <span m=''2929760''>of</span> <span m=''2929850''>a</span> <span m=''2930320''>definition</span>
  <span m=''2930770''>of</span> <span m=''2930860''>other</span> <span m=''2931090''>than</span>
  <span m=''2931650''>which</span> <span m=''2931860''>I</span> <span m=''2932030''>think</span>
  <span m=''2932210''>works.</span> <span m=''2933890''>Let''s</span> <span m=''2934160''>see.</span>
  <span m=''2935640''>Yes.</span> <span m=''2936330''>Where other</span> <span m=''2936720''>than</span>
  <span m=''2944130''>be a</span> <span m=''2944490''>procedure</span> <span m=''2945040''>of</span>
  <span m=''2945180''>one</span> <span m=''2945330''>argument</span> <span m=''2945710''>x</span>
  <span m=''2946580''>which</span> <span m=''2946770''>says,</span> <span m=''2948170''>if</span>
  <span m=''2949280''>its</span> <span m=''2949470''>eq</span> <span m=''2951560''>x</span>
  <span m=''2951930''>to,</span> <span m=''2952070''>say,</span> <span m=''2952190''>quote
  a,</span> <span m=''2953650''>then the</span> <span m=''2953770''>answer</span>
  <span m=''2954090''>is</span> <span m=''2954400''>quote</span> <span m=''2954700''>b.</span>
  <span m=''2955720''>Otherwise</span> <span m=''2956290''>it''s quote a.</span> <span
  m=''2960090''>That</span> <span m=''2960490''>always</span> <span m=''2960950''>produces</span>
  <span m=''2961320''>something</span> <span m=''2962060''>which</span> <span m=''2962330''>is</span>
  <span m=''2962430''>not</span> <span m=''2962670''>what its</span> <span m=''2962870''>argument</span>
  <span m=''2963260''>is.</span> <span m=''2965350''>That''s</span> <span m=''2965570''>all</span>
  <span m=''2965790''>it</span> <span m=''2965950''>is.</span> <span m=''2966540''>That''s
  all</span> <span m=''2966720''>I</span> <span m=''2966820''>wanted.</span> </p><p><span
  m=''2968250''>Well</span> <span m=''2968460''>now</span> <span m=''2968620''>let''s</span>
  <span m=''2968800''>consider</span> <span m=''2969180''>this</span> <span m=''2969370''>one,</span>
  <span m=''2969580''>diag2</span> <span m=''2970150''>of</span> <span m=''2970210''>diag2.</span>
  <span m=''2978220''>Well</span> <span m=''2978540''>look.</span> <span m=''2979560''>This</span>
  <span m=''2980250''>only</span> <span m=''2980530''>does</span> <span m=''2980800''>something</span>
  <span m=''2981220''>dangerous,</span> <span m=''2982090''>like</span> <span m=''2982310''>calling</span>
  <span m=''2982680''>p</span> <span m=''2982880''>of</span> <span m=''2982950''>p,</span>
  <span m=''2984820''>if</span> <span m=''2984970''>it''s</span> <span m=''2985120''>safe</span>
  <span m=''2985350''>to</span> <span m=''2985440''>do</span> <span m=''2985620''>so.</span>
  <span m=''2987470''>So</span> <span m=''2987680''>if</span> <span m=''2987860''>safe</span>
  <span m=''2988160''>defined</span> <span m=''2988750''>at</span> <span m=''2988800''>all,</span>
  <span m=''2990450''>if</span> <span m=''2990620''>you</span> <span m=''2990840''>can</span>
  <span m=''2990990''>define</span> <span m=''2991390''>such</span> <span m=''2991530''>a</span>
  <span m=''2991590''>procedure,</span> <span m=''2992010''>safe,</span> <span m=''2992930''>then</span>
  <span m=''2993390''>this</span> <span m=''2993590''>procedure</span> <span m=''2994790''>is</span>
  <span m=''2994960''>always</span> <span m=''2995260''>defined</span> <span m=''2995680''>and</span>
  <span m=''2995760''>therefore</span> <span m=''2996090''>safe</span> <span m=''2996600''>on</span>
  <span m=''2996790''>any</span> <span m=''2996950''>inputs.</span> <span m=''3001540''>So</span>
  <span m=''3002030''>diag2</span> <span m=''3002670''>of diag2</span> <span m=''3004000''>must</span>
  <span m=''3004310''>reduce to</span> <span m=''3004850''>other</span> <span m=''3005070''>than</span>
  <span m=''3010930''>diag2</span> <span m=''3011440''>of</span> <span m=''3011550''>diag2.</span>
  <span m=''3015496''>And</span> <span m=''3015980''>that</span> <span m=''3016180''>doesn''t</span>
  <span m=''3016370''>make</span> <span m=''3016550''>sense,</span> <span m=''3017650''>so
  we</span> <span m=''3017880''>have</span> <span m=''3018100''>a</span> <span m=''3018160''>contradiction,</span>
  <span m=''3020020''>and</span> <span m=''3020260''>therefore we</span> <span m=''3020620''>can''t</span>
  <span m=''3020870''>define</span> <span m=''3021190''>safe.</span> </p><p><span
  m=''3022950''>I just</span> <span m=''3023130''>waned</span> <span m=''3023290''>to</span>
  <span m=''3023380''>do</span> <span m=''3023480''>that</span> <span m=''3023700''>twice,</span>
  <span m=''3024800''>slightly</span> <span m=''3025200''>differently,</span> <span
  m=''3026850''>so</span> <span m=''3027040''>you</span> <span m=''3027210''>wouldn''t</span>
  <span m=''3027460''>feel</span> <span m=''3029780''>that</span> <span m=''3029940''>the</span>
  <span m=''3030040''>first</span> <span m=''3030270''>one</span> <span m=''3030370''>was</span>
  <span m=''3030490''>a</span> <span m=''3030540''>trick.</span> <span m=''3032260''>They</span>
  <span m=''3032740''>may be</span> <span m=''3032960''>both</span> <span m=''3033230''>tricks,</span>
  <span m=''3034180''>but they''re</span> <span m=''3034200''>at least</span> <span
  m=''3034350''>slightly</span> <span m=''3034710''>different.</span> </p><p><span
  m=''3037300''>So</span> <span m=''3037510''>I</span> <span m=''3037600''>suppose</span>
  <span m=''3037900''>that</span> <span m=''3038110''>pretty</span> <span m=''3038310''>much</span>
  <span m=''3038520''>wraps</span> <span m=''3038860''>it</span> <span m=''3038950''>up.</span>
  <span m=''3040080''>I''ve</span> <span m=''3040240''>just</span> <span m=''3040440''>proved</span>
  <span m=''3040610''>what</span> <span m=''3040700''>we</span> <span m=''3040790''>call</span>
  <span m=''3040980''>the</span> <span m=''3041070''>halting</span> <span m=''3041460''>theorem,</span>
  <span m=''3043360''>and I</span> <span m=''3043540''>suppose</span> <span m=''3043810''>with
  that</span> <span m=''3044100''>we''re</span> <span m=''3044180''>going</span> <span
  m=''3044280''>to</span> <span m=''3044370''>halt.</span> <span m=''3046720''>I hope</span>
  <span m=''3046870''>you have</span> <span m=''3047060''>a</span> <span m=''3047100''>good</span>
  <span m=''3047290''>time.</span> <span m=''3050900''>Are there any</span> <span
  m=''3051280''>questions?</span> <span m=''3053300''>Yes.</span> </p><p><span m=''3053810''>AUDIENCE:
  What</span> <span m=''3054130''>is</span> <span m=''3054390''>the</span> <span m=''3054510''>value</span>
  <span m=''3054970''>of</span> <span m=''3055120''>s</span> <span m=''3055350''>of</span>
  <span m=''3055450''>diag1?</span> </p><p><span m=''3056940''>PROFESSOR: Of what?</span>
  </p><p><span m=''3057430''>AUDIENCE: S</span> <span m=''3057890''>of</span> <span
  m=''3058080''>diag1.</span> <span m=''3060120''>If</span> <span m=''3060370''>you</span>
  <span m=''3060530''>said</span> <span m=''3060710''>s</span> <span m=''3061020''>is</span>
  <span m=''3061140''>a</span> <span m=''3061210''>function and</span> <span m=''3061700''>we</span>
  <span m=''3061810''>can</span> <span m=''3062340''>[INTERPOSING VOICES]</span> </p><p><span
  m=''3062620''>PROFESSOR: Oh, I</span> <span m=''3062830''>don''t</span> <span m=''3063040''>know.</span>
  <span m=''3063870''>I</span> <span m=''3064030''>don''t</span> <span m=''3064190''>know.</span>
  <span m=''3064350''>It''s</span> <span m=''3064410''>a function,</span> <span m=''3064810''>but
  I don''t know</span> <span m=''3065150''>how to</span> <span m=''3065360''>compute
  it.</span> <span m=''3066850''>I</span> <span m=''3067400''>can''t</span> <span
  m=''3067620''>do</span> <span m=''3067820''>it.</span> <span m=''3068610''>I''m</span>
  <span m=''3068790''>just</span> <span m=''3068940''>a</span> <span m=''3068970''>machine,</span>
  <span m=''3069330''>too.</span> <span m=''3071530''>Right?</span> <span m=''3072210''>There''s</span>
  <span m=''3072450''>no</span> <span m=''3072640''>machine</span> <span m=''3073070''>that</span>
  <span m=''3073240''>in</span> <span m=''3073370''>principle--</span> <span m=''3074670''>it</span>
  <span m=''3074830''>might</span> <span m=''3075140''>be</span> <span m=''3075350''>that</span>
  <span m=''3075500''>in</span> <span m=''3075610''>that</span> <span m=''3075800''>particular</span>
  <span m=''3076210''>case</span> <span m=''3076420''>you</span> <span m=''3076510''>just</span>
  <span m=''3076690''>asked,</span> <span m=''3076950''>with</span> <span m=''3077090''>some</span>
  <span m=''3077270''>thinking</span> <span m=''3077580''>I</span> <span m=''3077670''>could
  figure it</span> <span m=''3078080''>out.</span> <span m=''3078580''>But</span>
  <span m=''3078750''>in</span> <span m=''3078890''>general</span> <span m=''3079770''>I</span>
  <span m=''3079920''>can''t</span> <span m=''3080180''>compute</span> <span m=''3080490''>the</span>
  <span m=''3080570''>value</span> <span m=''3080880''>of s</span> <span m=''3081130''>any</span>
  <span m=''3081320''>better</span> <span m=''3081510''>than</span> <span m=''3081670''>any</span>
  <span m=''3081780''>other</span> <span m=''3081930''>machine</span> <span m=''3082210''>can.</span>
  <span m=''3083780''>There</span> <span m=''3083920''>is</span> <span m=''3084110''>such</span>
  <span m=''3084260''>a</span> <span m=''3084320''>function,</span> <span m=''3086160''>it''s</span>
  <span m=''3086290''>just</span> <span m=''3086480''>that</span> <span m=''3086530''>no</span>
  <span m=''3086660''>machine</span> <span m=''3087010''>can</span> <span m=''3087120''>be</span>
  <span m=''3087210''>built</span> <span m=''3087410''>to</span> <span m=''3087480''>compute</span>
  <span m=''3087780''>it.</span> </p><p><span m=''3089580''>Now</span> <span m=''3090890''>there''s</span>
  <span m=''3091230''>a</span> <span m=''3091310''>way</span> <span m=''3091720''>of</span>
  <span m=''3091940''>saying</span> <span m=''3092310''>that</span> <span m=''3092430''>that</span>
  <span m=''3092590''>should</span> <span m=''3092700''>not</span> <span m=''3092880''>be</span>
  <span m=''3092980''>surprising.</span> <span m=''3095350''>Going</span> <span m=''3095650''>through</span>
  <span m=''3095960''>this--</span> <span m=''3096390''>I</span> <span m=''3096470''>mean,</span>
  <span m=''3096730''>I</span> <span m=''3096830''>don''t</span> <span m=''3096960''>have</span>
  <span m=''3097330''>time</span> <span m=''3097590''>to</span> <span m=''3097640''>do</span>
  <span m=''3097800''>this</span> <span m=''3097990''>here,</span> <span m=''3098440''>but</span>
  <span m=''3099890''>the</span> <span m=''3100160''>number</span> <span m=''3101020''>of</span>
  <span m=''3101190''>functions</span> <span m=''3102180''>is</span> <span m=''3102360''>very</span>
  <span m=''3102610''>large.</span> <span m=''3104600''>If</span> <span m=''3104770''>there''s</span>
  <span m=''3104980''>a</span> <span m=''3105020''>certain</span> <span m=''3105280''>number</span>
  <span m=''3105560''>of</span> <span m=''3106070''>answers</span> <span m=''3107000''>possible</span>
  <span m=''3107405''>and</span> <span m=''3107810''>a</span> <span m=''3107960''>certain</span>
  <span m=''3108210''>number</span> <span m=''3108480''>of</span> <span m=''3108540''>inputs</span>
  <span m=''3108940''>possible,</span> <span m=''3109530''>then</span> <span m=''3109845''>it''s</span>
  <span m=''3110160''>the</span> <span m=''3110250''>number</span> <span m=''3110450''>of</span>
  <span m=''3110520''>answers</span> <span m=''3110920''>raised</span> <span m=''3111180''>to</span>
  <span m=''3111250''>the</span> <span m=''3111320''>number</span> <span m=''3111550''>inputs</span>
  <span m=''3111890''>is the</span> <span m=''3112000''>number</span> <span m=''3112230''>of</span>
  <span m=''3112290''>possible</span> <span m=''3112610''>functions.</span> <span
  m=''3114720''>On</span> <span m=''3114870''>one</span> <span m=''3115030''>variable.</span>
  <span m=''3118150''>Now</span> <span m=''3118290''>that''s</span> <span m=''3118510''>always</span>
  <span m=''3118840''>bigger</span> <span m=''3121900''>than</span> <span m=''3122390''>the</span>
  <span m=''3122490''>thing you''re</span> <span m=''3122730''>raising</span> <span
  m=''3123040''>to,</span> <span m=''3123690''>the</span> <span m=''3124090''>exponent.</span>
  <span m=''3125480''>The</span> <span m=''3128380''>number</span> <span m=''3128580''>of</span>
  <span m=''3128650''>functions</span> <span m=''3129150''>is</span> <span m=''3129310''>larger</span>
  <span m=''3130020''>than</span> <span m=''3130190''>the</span> <span m=''3131710''>number</span>
  <span m=''3132060''>of</span> <span m=''3132150''>programs</span> <span m=''3133080''>that</span>
  <span m=''3133520''>one</span> <span m=''3133640''>can</span> <span m=''3133750''>write,</span>
  <span m=''3134920''>by</span> <span m=''3135070''>an</span> <span m=''3135340''>infinity</span>
  <span m=''3135790''>counting</span> <span m=''3136130''>argument.</span> <span m=''3137840''>And</span>
  <span m=''3138270''>it''s</span> <span m=''3138380''>much</span> <span m=''3138650''>larger.</span>
  <span m=''3139475''>So</span> <span m=''3139880''>there</span> <span m=''3140060''>must</span>
  <span m=''3140290''>be</span> <span m=''3141350''>a</span> <span m=''3141490''>lot</span>
  <span m=''3141630''>of</span> <span m=''3141770''>functions</span> <span m=''3142160''>that</span>
  <span m=''3142280''>can''t</span> <span m=''3142460''>be</span> <span m=''3142540''>computed
  by</span> <span m=''3142980''>programs.</span> </p><p><span m=''3146280''>AUDIENCE:
  A few moments</span> <span m=''3146640''>ago you were talking</span> <span m=''3147000''>about</span>
  <span m=''3147300''>specifications</span> <span m=''3148540''>and automatic</span>
  <span m=''3148930''>generation</span> <span m=''3149235''>of</span> <span m=''3149540''>solutions.</span>
  <span m=''3150640''>Do</span> <span m=''3150810''>you</span> <span m=''3150980''>see</span>
  <span m=''3151190''>any</span> <span m=''3151350''>steps</span> <span m=''3151700''>between</span>
  <span m=''3152040''>specifications</span> <span m=''3152376''>and</span> <span m=''3153050''>solutions?</span>
  </p><p><span m=''3157250''>PROFESSOR: Steps</span> <span m=''3157650''>between.</span>
  <span m=''3158720''>You mean, you''re</span> <span m=''3159045''>saying,</span>
  <span m=''3159370''>how</span> <span m=''3159680''>you</span> <span m=''3159750''>go</span>
  <span m=''3159900''>about</span> <span m=''3161950''>constructing</span> <span m=''3162720''>devices</span>
  <span m=''3163320''>given</span> <span m=''3163540''>that</span> <span m=''3163640''>have</span>
  <span m=''3163800''>specifications</span> <span m=''3164145''>for the</span> <span
  m=''3164490''>device?</span> <span m=''3165205''>Sure.</span> </p><p><span m=''3165500''>AUDIENCE:
  There''s a</span> <span m=''3165580''>lot</span> <span m=''3165810''>of</span> <span
  m=''3167420''>software</span> <span m=''3167790''>engineering</span> <span m=''3168260''>that
  goes through</span> <span m=''3168680''>specifications</span> <span m=''3169520''>through</span>
  <span m=''3169890''>many</span> <span m=''3170120''>layers</span> <span m=''3170400''>of</span>
  <span m=''3170470''>design</span> <span m=''3170930''>and</span> <span m=''3171340''>then</span>
  <span m=''3171703''>implementation.</span> </p><p><span m=''3172430''>PROFESSOR:
  Yes?</span> </p><p><span m=''3172850''>AUDIENCE: I was</span> <span m=''3173030''>curious</span>
  <span m=''3173295''>if you think</span> <span m=''3173560''>that''s</span> <span
  m=''3173840''>realistic.</span> </p><p><span m=''3175600''>PROFESSOR: Well</span>
  <span m=''3175810''>I</span> <span m=''3175880''>think</span> <span m=''3176110''>that</span>
  <span m=''3176260''>some</span> <span m=''3176430''>of</span> <span m=''3176520''>it''s</span>
  <span m=''3176640''>realistic</span> <span m=''3177070''>and</span> <span m=''3177210''>some
  of</span> <span m=''3177380''>it</span> <span m=''3177520''>isn''t.</span> <span
  m=''3178100''>I mean,</span> <span m=''3178260''>surely</span> <span m=''3178590''>if</span>
  <span m=''3178720''>I</span> <span m=''3178810''>want</span> <span m=''3179040''>to</span>
  <span m=''3179090''>build an</span> <span m=''3179340''>electrical</span> <span
  m=''3179840''>filter</span> <span m=''3181270''>and</span> <span m=''3181680''>I</span>
  <span m=''3181860''>have</span> <span m=''3182030''>a</span> <span m=''3185680''>rather</span>
  <span m=''3185950''>interesting</span> <span m=''3186300''>possibility.</span> <span
  m=''3187160''>Supposing</span> <span m=''3187890''>I</span> <span m=''3188000''>want</span>
  <span m=''3188220''>to</span> <span m=''3188270''>build</span> <span m=''3188500''>a</span>
  <span m=''3188580''>thing</span> <span m=''3189590''>that</span> <span m=''3189900''>matches</span>
  <span m=''3190280''>some</span> <span m=''3191750''>power</span> <span m=''3192180''>output</span>
  <span m=''3192560''>to</span> <span m=''3192820''>the</span> <span m=''3192910''>radio</span>
  <span m=''3193270''>transmitter,</span> <span m=''3197592''>to</span> <span m=''3197940''>some</span>
  <span m=''3198210''>antenna.</span> <span m=''3199906''>And</span> <span m=''3200310''>I''m</span>
  <span m=''3200610''>really</span> <span m=''3200790''>out of</span> <span m=''3200960''>this</span>
  <span m=''3201090''>power--</span> <span m=''3201970''>it''s output</span> <span
  m=''3202310''>tube out</span> <span m=''3202510''>here.</span> <span m=''3203230''>And</span>
  <span m=''3203290''>the</span> <span m=''3203380''>problem</span> <span m=''3203700''>is</span>
  <span m=''3203850''>that they</span> <span m=''3203970''>have</span> <span m=''3204100''>different</span>
  <span m=''3204390''>impedances.</span> <span m=''3205920''>I</span> <span m=''3206010''>want</span>
  <span m=''3206230''>them</span> <span m=''3206330''>to</span> <span m=''3206400''>match</span>
  <span m=''3206680''>the</span> <span m=''3206780''>impedances.</span> <span m=''3207550''>I</span>
  <span m=''3207650''>also</span> <span m=''3207870''>want</span> <span m=''3207950''>to</span>
  <span m=''3208020''>make</span> <span m=''3208160''>a</span> <span m=''3208200''>filter</span>
  <span m=''3208580''>in</span> <span m=''3208650''>there</span> <span m=''3209260''>which</span>
  <span m=''3209410''>is</span> <span m=''3209510''>going</span> <span m=''3209710''>to</span>
  <span m=''3209760''>get</span> <span m=''3209920''>rid</span> <span m=''3210020''>of</span>
  <span m=''3210100''>some</span> <span m=''3210580''>harmonic</span> <span m=''3211090''>radiation.</span>
  </p><p><span m=''3212780''>Well</span> <span m=''3214060''>one</span> <span m=''3214340''>old-fashioned</span>
  <span m=''3215140''>technique</span> <span m=''3215540''>for</span> <span m=''3215660''>doing</span>
  <span m=''3215940''>this</span> <span m=''3216170''>is</span> <span m=''3216270''>called</span>
  <span m=''3216830''>image</span> <span m=''3217110''>impedances,</span> <span m=''3217770''>or</span>
  <span m=''3217840''>something</span> <span m=''3218130''>like</span> <span m=''3218380''>that.</span>
  <span m=''3218860''>And what</span> <span m=''3219060''>you</span> <span m=''3219180''>do
  is</span> <span m=''3219350''>you</span> <span m=''3219490''>say</span> <span m=''3219650''>you</span>
  <span m=''3219720''>have</span> <span m=''3219800''>a</span> <span m=''3219890''>basic</span>
  <span m=''3220240''>module</span> <span m=''3221160''>called</span> <span m=''3221510''>an</span>
  <span m=''3221930''>L-section.</span> <span m=''3223300''>Looks</span> <span m=''3223480''>like</span>
  <span m=''3223680''>this.</span> <span m=''3227080''>If</span> <span m=''3227270''>I</span>
  <span m=''3227380''>happen</span> <span m=''3227650''>to</span> <span m=''3227750''>connect</span>
  <span m=''3228020''>this</span> <span m=''3228210''>to</span> <span m=''3228310''>some</span>
  <span m=''3228580''>resistance,</span> <span m=''3229200''>r,</span> <span m=''3230100''>and
  if I</span> <span m=''3230470''>make</span> <span m=''3230640''>this</span> <span
  m=''3230830''>impedance</span> <span m=''3231600''>x,</span> <span m=''3232040''>xl,</span>
  <span m=''3232870''>and</span> <span m=''3233030''>if</span> <span m=''3233130''>it</span>
  <span m=''3233220''>happens</span> <span m=''3233570''>to</span> <span m=''3233660''>be</span>
  <span m=''3234220''>q</span> <span m=''3234520''>times</span> <span m=''3234880''>r,</span>
  <span m=''3235150''>then</span> <span m=''3235850''>this</span> <span m=''3235980''>produces</span>
  <span m=''3237510''>a</span> <span m=''3237600''>low</span> <span m=''3237760''>pass</span>
  <span m=''3238050''>filter</span> <span m=''3238730''>with</span> <span m=''3238860''>a</span>
  <span m=''3238990''>q</span> <span m=''3239170''>square</span> <span m=''3239440''>plus</span>
  <span m=''3239710''>one</span> <span m=''3239990''>impedance</span> <span m=''3240290''>match.</span>
  <span m=''3242110''>Just</span> <span m=''3242380''>what</span> <span m=''3242470''>I</span>
  <span m=''3242560''>need.</span> <span m=''3243120''>Because</span> <span m=''3243310''>now</span>
  <span m=''3243490''>I</span> <span m=''3243560''>can</span> <span m=''3243710''>take</span>
  <span m=''3243930''>two</span> <span m=''3244090''>of</span> <span m=''3244220''>these,</span>
  <span m=''3244340''>hook</span> <span m=''3244470''>them</span> <span m=''3244610''>together</span>
  <span m=''3245420''>like</span> <span m=''3246050''>this.</span> <span m=''3251660''>OK,</span>
  <span m=''3252090''>and I</span> <span m=''3252220''>take</span> <span m=''3252370''>another</span>
  <span m=''3252610''>one</span> <span m=''3256010''>and</span> <span m=''3256210''>I''ll</span>
  <span m=''3256360''>hook</span> <span m=''3256480''>them</span> <span m=''3256570''>together</span>
  <span m=''3256880''>like</span> <span m=''3257150''>that.</span> <span m=''3258290''>And</span>
  <span m=''3258390''>I</span> <span m=''3258500''>have</span> <span m=''3258650''>two</span>
  <span m=''3258790''>L-sections</span> <span m=''3259330''>hooked</span> <span m=''3259450''>together.</span>
  <span m=''3260320''>And</span> <span m=''3260690''>this</span> <span m=''3260930''>will</span>
  <span m=''3261150''>step</span> <span m=''3261360''>the</span> <span m=''3261480''>impedance</span>
  <span m=''3261780''>down</span> <span m=''3262020''>to</span> <span m=''3262100''>one
  that</span> <span m=''3262370''>I</span> <span m=''3262460''>know,</span> <span
  m=''3263550''>and</span> <span m=''3263700''>this</span> <span m=''3263840''>will</span>
  <span m=''3263920''>step it</span> <span m=''3264170''>up</span> <span m=''3264340''>to</span>
  <span m=''3264450''>one</span> <span m=''3264650''>I</span> <span m=''3264770''>know.</span>
  <span m=''3265530''>Each</span> <span m=''3265710''>of</span> <span m=''3265780''>these
  is</span> <span m=''3265980''>a</span> <span m=''3266050''>low</span> <span m=''3266230''>pass</span>
  <span m=''3266510''>filter</span> <span m=''3266710''>getting</span> <span m=''3266890''>rid</span>
  <span m=''3267010''>of</span> <span m=''3267060''>some</span> <span m=''3267200''>harmonics.</span>
  <span m=''3268090''>It''s</span> <span m=''3268300''>good</span> <span m=''3268450''>filter,</span>
  <span m=''3269140''>it''s</span> <span m=''3269320''>called</span> <span m=''3269680''>a
  pie-section</span> <span m=''3270030''>filter.</span> <span m=''3270270''>Great.</span>
  </p><p><span m=''3271700''>Except</span> <span m=''3272020''>for</span> <span m=''3272090''>the</span>
  <span m=''3272170''>fact</span> <span m=''3272640''>that</span> <span m=''3272940''>in</span>
  <span m=''3273070''>doing</span> <span m=''3273380''>what</span> <span m=''3273520''>I</span>
  <span m=''3273620''>just</span> <span m=''3273880''>did,</span> <span m=''3274090''>I''ve</span>
  <span m=''3274300''>made a</span> <span m=''3274480''>terrible</span> <span m=''3276530''>inefficiency</span>
  <span m=''3277110''>in</span> <span m=''3277200''>this</span> <span m=''3277280''>system.</span>
  <span m=''3278620''>I''ve</span> <span m=''3278880''>made</span> <span m=''3279120''>two</span>
  <span m=''3279260''>coils</span> <span m=''3279630''>where</span> <span m=''3279750''>I
  should have</span> <span m=''3280010''>made</span> <span m=''3280220''>one.</span>
  <span m=''3281620''>And</span> <span m=''3282010''>the</span> <span m=''3282320''>problem</span>
  <span m=''3282630''>with</span> <span m=''3282780''>most</span> <span m=''3283280''>software</span>
  <span m=''3283730''>engineering</span> <span m=''3284190''>art</span> <span m=''3284990''>is</span>
  <span m=''3285200''>that</span> <span m=''3285370''>there''s</span> <span m=''3285560''>no</span>
  <span m=''3286250''>mechanism,</span> <span m=''3286800''>other</span> <span m=''3286950''>than</span>
  <span m=''3287110''>peephole</span> <span m=''3287440''>optimization</span> <span
  m=''3287765''>and</span> <span m=''3288090''>compilers,</span> <span m=''3288760''>for</span>
  <span m=''3288980''>getting</span> <span m=''3289240''>rid</span> <span m=''3289410''>of</span>
  <span m=''3290010''>the</span> <span m=''3290280''>redundant</span> <span m=''3290750''>parts</span>
  <span m=''3291070''>that are</span> <span m=''3291190''>constructed</span> <span
  m=''3291940''>when</span> <span m=''3292140''>doing</span> <span m=''3292580''>top</span>
  <span m=''3292810''>down</span> <span m=''3293010''>design.</span> <span m=''3295350''>It''s</span>
  <span m=''3295560''>even</span> <span m=''3295770''>worse,</span> <span m=''3296120''>there</span>
  <span m=''3296260''>are</span> <span m=''3296290''>lots</span> <span m=''3296530''>of</span>
  <span m=''3296610''>very</span> <span m=''3296820''>important</span> <span m=''3297160''>structures</span>
  <span m=''3297580''>that</span> <span m=''3297680''>you</span> <span m=''3297780''>can''t</span>
  <span m=''3297990''>construct</span> <span m=''3298350''>at all</span> <span m=''3298570''>this</span>
  <span m=''3298740''>way.</span> </p><p><span m=''3301110''>So</span> <span m=''3301250''>I</span>
  <span m=''3301370''>think</span> <span m=''3301570''>that</span> <span m=''3302310''>the</span>
  <span m=''3302380''>standard</span> <span m=''3302740''>top</span> <span m=''3302990''>down</span>
  <span m=''3303210''>design</span> <span m=''3303320''>is</span> <span m=''3303550''>a</span>
  <span m=''3303700''>rather</span> <span m=''3303940''>shallow</span> <span m=''3304290''>business.</span>
  <span m=''3305710''>Doesn''t</span> <span m=''3306090''>really</span> <span m=''3306360''>capture</span>
  <span m=''3306690''>what</span> <span m=''3306830''>people</span> <span m=''3307040''>want</span>
  <span m=''3307150''>to</span> <span m=''3307260''>do</span> <span m=''3307430''>in</span>
  <span m=''3307510''>design.</span> <span m=''3308315''>I''ll give</span> <span m=''3308670''>you</span>
  <span m=''3308920''>another</span> <span m=''3309210''>electrical</span> <span m=''3309650''>example.</span>
  <span m=''3310100''>Electrical</span> <span m=''3310520''>examples</span> <span
  m=''3310880''>are</span> <span m=''3310960''>so</span> <span m=''3311080''>much</span>
  <span m=''3311270''>clearer</span> <span m=''3311990''>than</span> <span m=''3312140''>computational</span>
  <span m=''3312760''>examples,</span> <span m=''3313130''>because</span> <span m=''3313370''>computation</span>
  <span m=''3313790''>examples</span> <span m=''3314440''>require</span> <span m=''3314800''>a</span>
  <span m=''3314840''>certain</span> <span m=''3315010''>degree</span> <span m=''3315210''>of</span>
  <span m=''3315280''>complexity</span> <span m=''3315810''>to</span> <span m=''3315890''>explain</span>
  <span m=''3316280''>them.</span> <span m=''3317220''>But</span> <span m=''3318020''>one</span>
  <span m=''3318180''>of</span> <span m=''3318230''>my</span> <span m=''3318370''>favorite</span>
  <span m=''3318710''>examples</span> <span m=''3319160''>in the</span> <span m=''3319240''>electrical</span>
  <span m=''3319650''>world</span> <span m=''3320720''>is</span> <span m=''3320830''>how</span>
  <span m=''3321040''>would I</span> <span m=''3321110''>ever</span> <span m=''3321340''>come</span>
  <span m=''3321530''>up</span> <span m=''3321660''>with</span> <span m=''3321770''>the</span>
  <span m=''3321860''>output</span> <span m=''3322210''>stage</span> <span m=''3322590''>of</span>
  <span m=''3323330''>this</span> <span m=''3323540''>inter-stage</span> <span m=''3324370''>connection</span>
  <span m=''3325320''>in</span> <span m=''3325460''>an</span> <span m=''3325570''>IF</span>
  <span m=''3325860''>amplifier.</span> <span m=''3327530''>It''s a</span> <span m=''3328350''>little</span>
  <span m=''3328520''>transistor</span> <span m=''3329070''>here,</span> <span m=''3329630''>and</span>
  <span m=''3330720''>let''s see.</span> <span m=''3332410''>Well I''m going</span>
  <span m=''3332660''>to have a</span> <span m=''3332960''>tank,</span> <span m=''3336660''>and</span>
  <span m=''3336840''>I''m going</span> <span m=''3337030''>to hook</span> <span m=''3337180''>this</span>
  <span m=''3337290''>up</span> <span m=''3337560''>to,</span> <span m=''3338630''>say,</span>
  <span m=''3341510''>I''m going to link-couple</span> <span m=''3342300''>that</span>
  <span m=''3342560''>to</span> <span m=''3342650''>the</span> <span m=''3342860''>input</span>
  <span m=''3343040''>of</span> <span m=''3343130''>the</span> <span m=''3343210''>next</span>
  <span m=''3343450''>stage.</span> </p><p><span m=''3344850''>Here''s</span> <span
  m=''3345210''>a</span> <span m=''3345520''>perfectly</span> <span m=''3345980''>plausible</span>
  <span m=''3346800''>plan--</span> <span m=''3348580''>well</span> <span m=''3348900''>except</span>
  <span m=''3349170''>for</span> <span m=''3349240''>the</span> <span m=''3349320''>fact</span>
  <span m=''3349620''>that</span> <span m=''3349770''>since</span> <span m=''3350050''>I</span>
  <span m=''3350130''>put</span> <span m=''3350320''>that</span> <span m=''3350480''>going</span>
  <span m=''3350730''>up</span> <span m=''3351010''>I</span> <span m=''3351070''>should</span>
  <span m=''3351250''>make</span> <span m=''3351450''>that</span> <span m=''3351560''>going</span>
  <span m=''3351690''>that way.</span> <span m=''3353170''>Here''s a</span> <span
  m=''3353370''>perfectly</span> <span m=''3353780''>plausible</span> <span m=''3354230''>plan</span>
  <span m=''3354670''>for</span> <span m=''3354920''>a--</span> <span m=''3356050''>no</span>
  <span m=''3356190''>I</span> <span m=''3356290''>shouldn''t.</span> <span m=''3357270''>I''m
  dumb.</span> <span m=''3357940''>Excuse me.</span> <span m=''3359690''>Doesn''t</span>
  <span m=''3360010''>matter.</span> <span m=''3360730''>The point is</span> <span
  m=''3360920''>[UNINTELLIGIBLE]</span> <span m=''3361540''>plan</span> <span m=''3361830''>for</span>
  <span m=''3362070''>a</span> <span m=''3362180''>couple</span> <span m=''3362280''>[UNINTELLIGIBLE]</span>
  <span m=''3362560''>stages</span> <span m=''3362940''>together.</span> <span m=''3364590''>Now</span>
  <span m=''3364760''>what</span> <span m=''3364910''>the</span> <span m=''3364950''>problem</span>
  <span m=''3365370''>is</span> <span m=''3365510''>is</span> <span m=''3365630''>what''s</span>
  <span m=''3365910''>this</span> <span m=''3366210''>hierarchically?</span> <span
  m=''3367620''>It''s</span> <span m=''3367790''>not</span> <span m=''3368070''>one</span>
  <span m=''3368320''>thing.</span> <span m=''3369480''>Hierarchically</span> <span
  m=''3370500''>it</span> <span m=''3370620''>doesn''t</span> <span m=''3370820''>make</span>
  <span m=''3370980''>any</span> <span m=''3371100''>sense</span> <span m=''3371340''>at</span>
  <span m=''3371440''>all.</span> <span m=''3371990''>It''s</span> <span m=''3372260''>the</span>
  <span m=''3373110''>inductance</span> <span m=''3373340''>of</span> <span m=''3373490''>a</span>
  <span m=''3373630''>tuned</span> <span m=''3373870''>circuit,</span> <span m=''3375600''>it''s</span>
  <span m=''3375860''>the</span> <span m=''3376640''>primary</span> <span m=''3377140''>of
  a</span> <span m=''3377230''>transformer,</span> <span m=''3379190''>and</span>
  <span m=''3379400''>it''s</span> <span m=''3379550''>also</span> <span m=''3380450''>the</span>
  <span m=''3380770''>DC</span> <span m=''3381210''>path</span> <span m=''3381520''>by</span>
  <span m=''3381700''>which</span> <span m=''3381900''>bias</span> <span m=''3382350''>conditions</span>
  <span m=''3382790''>get</span> <span m=''3382980''>to</span> <span m=''3383070''>the</span>
  <span m=''3383860''>collector</span> <span m=''3384300''>of</span> <span m=''3384410''>that</span>
  <span m=''3384510''>transistor.</span> <span m=''3386460''>And</span> <span m=''3386820''>there''s</span>
  <span m=''3387030''>no</span> <span m=''3387250''>simple</span> <span m=''3387600''>top-down</span>
  <span m=''3388110''>design</span> <span m=''3388530''>that''s</span> <span m=''3388660''>going</span>
  <span m=''3388760''>to</span> <span m=''3388850''>produce</span> <span m=''3389170''>a</span>
  <span m=''3389230''>structure</span> <span m=''3389630''>like</span> <span m=''3389880''>that</span>
  <span m=''3390270''>with</span> <span m=''3390450''>so</span> <span m=''3390580''>many</span>
  <span m=''3390770''>overlapping</span> <span m=''3392910''>uses</span> <span m=''3393290''>for
  a</span> <span m=''3393400''>particular</span> <span m=''3393750''>thing.</span>
  </p><p><span m=''3394530''>Playing</span> <span m=''3396030''>Scrabble,</span> <span
  m=''3397030''>where you have to do</span> <span m=''3397590''>triple</span> <span
  m=''3397860''>word</span> <span m=''3398100''>scores,</span> <span m=''3399015''>or</span>
  <span m=''3399370''>whatever,</span> <span m=''3400530''>is</span> <span m=''3400650''>not</span>
  <span m=''3400860''>so</span> <span m=''3401000''>easy</span> <span m=''3401270''>in</span>
  <span m=''3401370''>top-down</span> <span m=''3402790''>design</span> <span m=''3403050''>strategy.</span>
  <span m=''3404950''>Yet</span> <span m=''3405340''>most</span> <span m=''3405640''>of</span>
  <span m=''3405740''>real</span> <span m=''3405960''>engineering</span> <span m=''3406430''>is</span>
  <span m=''3406550''>based</span> <span m=''3406860''>on</span> <span m=''3407510''>getting</span>
  <span m=''3407740''>the</span> <span m=''3407810''>most</span> <span m=''3408100''>oomph</span>
  <span m=''3409840''>for</span> <span m=''3410270''>effort.</span> <span m=''3412140''>And</span>
  <span m=''3412660''>that''s</span> <span m=''3412820''>what</span> <span m=''3412910''>you''re</span>
  <span m=''3413000''>seeing</span> <span m=''3413230''>here.</span> <span m=''3414860''>Yeah?</span>
  </p><p><span m=''3415550''>AUDIENCE: Is</span> <span m=''3415720''>this</span> <span
  m=''3415950''>the</span> <span m=''3416140''>last</span> <span m=''3416330''>question?</span>
  </p><p><span m=''3420282''>[LAUGHTER]</span> </p><p><span m=''3438640''>PROFESSOR:
  Apparently</span> <span m=''3439240''>so.</span> <span m=''3443240''>Thank</span>
  <span m=''3443950''>you.</span> </p><p><span m=''3446092''>[APPLAUSE]</span> </p><p><span
  m=''3459040''>[MUSIC-- "JESU, JOY OF MAN''S DESIRING" BY JOHANN SEBASTIAN BACH]</span>
  </p>'
type: course
uid: de43479d33e354e7ec3284a110b13795

---
None