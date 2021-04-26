---
about_this_resource_text: '<p><b>Topics covered:</b> Computational Objects</p> <p><b>
  Instructors: </b>Hal Abelson and Gerald Jay Sussman</p> <p>Subtitles for this course
  are provided through the generous assistance of Henry Baker, Hoofar Pourzand, Heather
  Wood, Aleksejs Truhans, Steven Edwards, George Menhorn, and Mahendra Kumar.</p>'
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
embedded_media:
- id: 5B.jpg
  parent_uid: db6c4639d0f0726a08313f8ef7c1b992
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/5b-computational-objects/5B.jpg
  title: 5B.jpg
  type: null
  uid: f59421207eb17971a6ac354694cec84a
- id: Video-YouTube-Stream
  media_location: yedzRWhi-9E
  parent_uid: db6c4639d0f0726a08313f8ef7c1b992
  title: Video-YouTube-Stream
  type: Video
  uid: ba5a6c782badea9ffa0021391fa9ecd4
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT_Structure_of_Computer_Programs_1986/lec5b.mp4
  parent_uid: db6c4639d0f0726a08313f8ef7c1b992
  title: Video-Internet Archive-MP4
  type: Video
  uid: 7ebf39d98546c0a9dc2fb9f30d6e040b
- id: Thumbnail-OCW-JPG
  parent_uid: db6c4639d0f0726a08313f8ef7c1b992
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 3d12f785920d420e88cdf9ce91427bf3
- id: 3Play-3PlayYouTubeid-MP4
  media_location: yedzRWhi-9E
  parent_uid: db6c4639d0f0726a08313f8ef7c1b992
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 3ea71e088a6fd9b45a5c4a2b5ba57efa
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/yedzRWhi-9E/default.jpg
  parent_uid: db6c4639d0f0726a08313f8ef7c1b992
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: f96765db97b49b387f24366395191c6e
- id: yedzRWhi-9E.srt
  parent_uid: db6c4639d0f0726a08313f8ef7c1b992
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/5b-computational-objects/yedzRWhi-9E.srt
  title: 3play caption file
  type: null
  uid: d12472e86a00c589f5a6f115f4081aff
- id: yedzRWhi-9E.pdf
  parent_uid: db6c4639d0f0726a08313f8ef7c1b992
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/5b-computational-objects/yedzRWhi-9E.pdf
  title: 3play pdf file
  type: null
  uid: e2dd7fe7a875819f96a33bf59f8a38ba
- id: Caption-3Play YouTube id-SRT
  parent_uid: db6c4639d0f0726a08313f8ef7c1b992
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: e477f6232107ff2abaeb1934a9f85e6c
- id: Transcript-3Play YouTube id-PDF
  parent_uid: db6c4639d0f0726a08313f8ef7c1b992
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: aaddf809d40f45fdbf01c535007ffe5b
inline_embed_id: 700421795b:computationalobjects53600005
layout: video
order_index: null
parent_uid: 4fcacad2c29981dd668a6b29822403cc
related_resources_text: ''
short_url: 5b-computational-objects
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/5b-computational-objects
template_type: Tabbed
title: '5B: Computational Objects'
transcript: '<p><span m=''21170''>PROFESSOR: Well,</span> <span m=''21620''>now that</span>
  <span m=''21860''>we''ve</span> <span m=''22830''>given</span> <span m=''23250''>you</span>
  <span m=''23410''>some</span> <span m=''23640''>power</span> <span m=''24250''>to</span>
  <span m=''24550''>make</span> <span m=''24770''>independent</span> <span m=''25270''>local</span>
  <span m=''25610''>state</span> <span m=''26390''>and</span> <span m=''26540''>to</span>
  <span m=''26620''>model</span> <span m=''27020''>objects,</span> <span m=''28025''>I</span>
  <span m=''28340''>thought</span> <span m=''28590''>we''d</span> <span m=''29600''>do</span>
  <span m=''29870''>a</span> <span m=''29930''>bit</span> <span m=''30110''>of</span>
  <span m=''30470''>programming</span> <span m=''30800''>of</span> <span m=''31130''>a</span>
  <span m=''31230''>very</span> <span m=''31610''>complicated</span> <span m=''32240''>kind,</span>
  <span m=''33160''>just</span> <span m=''33620''>to</span> <span m=''34250''>illustrate</span>
  <span m=''34890''>what</span> <span m=''35030''>you</span> <span m=''35140''>can</span>
  <span m=''35260''>do</span> <span m=''35380''>with</span> <span m=''35490''>this</span>
  <span m=''35630''>sort</span> <span m=''35760''>of</span> <span m=''35900''>thing.</span>
  <span m=''40430''>I</span> <span m=''40560''>suppose,</span> <span m=''40880''>as</span>
  <span m=''41020''>I</span> <span m=''41120''>said,</span> <span m=''41420''>we</span>
  <span m=''41540''>were</span> <span m=''41660''>motivated</span> <span m=''42230''>by</span>
  <span m=''42390''>physical</span> <span m=''42840''>systems</span> <span m=''44080''>and</span>
  <span m=''44300''>the</span> <span m=''44360''>ways</span> <span m=''44610''>we</span>
  <span m=''44740''>like</span> <span m=''44950''>to</span> <span m=''45040''>think</span>
  <span m=''45250''>about</span> <span m=''45480''>physical</span> <span m=''45810''>systems,</span>
  <span m=''47000''>which</span> <span m=''47200''>is</span> <span m=''47360''>that</span>
  <span m=''47570''>there</span> <span m=''47780''>are</span> <span m=''48260''>these</span>
  <span m=''48780''>things</span> <span m=''49860''>that</span> <span m=''50000''>the</span>
  <span m=''50180''>world</span> <span m=''50360''>is</span> <span m=''50430''>made</span>
  <span m=''50700''>out</span> <span m=''50900''>of.</span> <span m=''52060''>And</span>
  <span m=''52230''>each</span> <span m=''52370''>of</span> <span m=''52470''>these</span>
  <span m=''52720''>things</span> <span m=''53240''>has</span> <span m=''54040''>particular</span>
  <span m=''54800''>independent</span> <span m=''55280''>local</span> <span m=''55570''>state,</span>
  <span m=''57310''>and</span> <span m=''57610''>therefore</span> <span m=''57710''>it</span>
  <span m=''58180''>is</span> <span m=''58470''>a</span> <span m=''58550''>thing.</span>
  <span m=''58830''>That''s</span> <span m=''58990''>what</span> <span m=''59150''>makes</span>
  <span m=''59410''>it a</span> <span m=''59550''>thing.</span> </p><p><span m=''61280''>And</span>
  <span m=''61470''>then</span> <span m=''61630''>we''re</span> <span m=''61770''>going</span>
  <span m=''61960''>to</span> <span m=''62040''>say</span> <span m=''62560''>that</span>
  <span m=''64330''>in the model in the world--we</span> <span m=''64430''>have</span>
  <span m=''64560''>a</span> <span m=''64940''>world</span> <span m=''66240''>and</span>
  <span m=''66320''>a</span> <span m=''66400''>model</span> <span m=''66960''>in</span>
  <span m=''67090''>our</span> <span m=''67200''>minds</span> <span m=''67610''>and</span>
  <span m=''67720''>in</span> <span m=''67830''>the</span> <span m=''67900''>computer</span>
  <span m=''69130''>of</span> <span m=''69320''>that</span> <span m=''69520''>world.</span>
  <span m=''70940''>And</span> <span m=''71250''>what I</span> <span m=''71300''>want</span>
  <span m=''71410''>to</span> <span m=''71520''>make</span> <span m=''71680''>is a</span>
  <span m=''71770''>correspondence</span> <span m=''72820''>between</span> <span m=''73140''>the</span>
  <span m=''73230''>objects</span> <span m=''73590''>in</span> <span m=''73660''>the</span>
  <span m=''73730''>world</span> <span m=''74120''>and</span> <span m=''74210''>the</span>
  <span m=''74300''>objects</span> <span m=''74620''>in</span> <span m=''74680''>the</span>
  <span m=''74740''>computer,</span> <span m=''75850''>the</span> <span m=''75980''>relationships</span>
  <span m=''76640''>between</span> <span m=''76880''>the</span> <span m=''76970''>objects</span>
  <span m=''77310''>in</span> <span m=''77370''>the</span> <span m=''77430''>world</span>
  <span m=''77930''>and the</span> <span m=''78140''>relationships</span> <span m=''78750''>between</span>
  <span m=''79600''>those same obj...--the</span> <span m=''80350''>model</span> <span
  m=''80770''>objects</span> <span m=''81200''>in</span> <span m=''81260''>the</span>
  <span m=''81330''>computer,</span> <span m=''83160''>and</span> <span m=''83380''>the</span>
  <span m=''83470''>functions</span> <span m=''83980''>that</span> <span m=''84130''>relate</span>
  <span m=''84680''>things</span> <span m=''84890''>in</span> <span m=''84970''>the</span>
  <span m=''85060''>world</span> <span m=''85850''>to</span> <span m=''86170''>the</span>
  <span m=''86250''>functions</span> <span m=''86680''>that</span> <span m=''86780''>relate</span>
  <span m=''87320''>things</span> <span m=''87550''>in</span> <span m=''87620''>the</span>
  <span m=''87690''>computer.</span> </p><p><span m=''90840''>This</span> <span m=''91120''>buys</span>
  <span m=''91530''>us</span> <span m=''93020''>modularity.</span> <span m=''94740''>If</span>
  <span m=''95000''>we</span> <span m=''95140''>really</span> <span m=''95360''>believe</span>
  <span m=''95650''>the</span> <span m=''95870''>world</span> <span m=''96100''>is</span>
  <span m=''96210''>like</span> <span m=''96460''>that,</span> <span m=''97170''>that</span>
  <span m=''97530''>it''s</span> <span m=''97720''>made out of</span> <span m=''97920''>these</span>
  <span m=''98090''>little</span> <span m=''98270''>pieces,</span> <span m=''98890''>and</span>
  <span m=''99220''>of</span> <span m=''99340''>course</span> <span m=''99510''>we</span>
  <span m=''99610''>could</span> <span m=''99690''>arrange</span> <span m=''100120''>our</span>
  <span m=''100280''>world</span> <span m=''100670''>to</span> <span m=''100750''>be</span>
  <span m=''100970''>like</span> <span m=''101250''>that,</span> <span m=''102080''>we</span>
  <span m=''102190''>could</span> <span m=''102280''>only</span> <span m=''102510''>model</span>
  <span m=''102770''>those</span> <span m=''102980''>things that</span> <span m=''103190''>are</span>
  <span m=''103470''>like</span> <span m=''103730''>that,</span> <span m=''105230''>then</span>
  <span m=''105630''>we</span> <span m=''105750''>can</span> <span m=''105860''>inherit</span>
  <span m=''106240''>the</span> <span m=''106310''>modularity</span> <span m=''106920''>in</span>
  <span m=''107030''>the</span> <span m=''107100''>world</span> <span m=''108160''>into</span>
  <span m=''108450''>our</span> <span m=''108550''>programming.</span> <span m=''110450''>That''s</span>
  <span m=''110660''>why</span> <span m=''110800''>we</span> <span m=''110950''>would</span>
  <span m=''111050''>invent</span> <span m=''112060''>some</span> <span m=''112280''>of
  this</span> <span m=''112430''>object-oriented</span> <span m=''113150''>programming.</span>
  </p><p><span m=''115420''>Well,</span> <span m=''115620''>let''s</span> <span m=''115830''>take</span>
  <span m=''116150''>the</span> <span m=''116480''>best</span> <span m=''116780''>kind</span>
  <span m=''116920''>of</span> <span m=''117060''>objects</span> <span m=''117490''>I</span>
  <span m=''117620''>know.</span> <span m=''118890''>They''re</span> <span m=''119090''>completely--they''re
  completely</span> <span m=''122210''>wonderful:</span> <span m=''123160''>electrical</span>
  <span m=''123710''>systems.</span> <span m=''126500''>Electrical</span> <span m=''127030''>systems</span>
  <span m=''128639''>really</span> <span m=''129020''>are</span> <span m=''130110''>the</span>
  <span m=''130270''>physicist''s</span> <span m=''130740''>best,</span> <span m=''131990''>best</span>
  <span m=''132600''>objects.</span> <span m=''134220''>You</span> <span m=''134320''>see</span>
  <span m=''134560''>over</span> <span m=''134730''>here</span> <span m=''135050''>I</span>
  <span m=''135130''>have</span> <span m=''135560''>some</span> <span m=''135810''>piece</span>
  <span m=''135980''>of</span> <span m=''136060''>machinery.</span> <span m=''136760''>Right</span>
  <span m=''137150''>here''s</span> <span m=''137370''>a</span> <span m=''137430''>piece</span>
  <span m=''137600''>of</span> <span m=''137690''>machinery.</span> <span m=''140040''>And</span>
  <span m=''140210''>it''s</span> <span m=''140380''>got</span> <span m=''140670''>an</span>
  <span m=''141140''>electrical</span> <span m=''141590''>wire</span> <span m=''142180''>connecting</span>
  <span m=''143660''>one</span> <span m=''143980''>part</span> <span m=''144120''>of</span>
  <span m=''144270''>the</span> <span m=''144340''>machinery</span> <span m=''145080''>with</span>
  <span m=''145270''>another</span> <span m=''145510''>part</span> <span m=''145680''>of
  the</span> <span m=''145850''>machinery.</span> <span m=''147190''>And</span> <span
  m=''147570''>one</span> <span m=''147680''>of</span> <span m=''147960''>the</span>
  <span m=''148060''>wonderful</span> <span m=''148500''>properties</span> <span m=''149780''>of</span>
  <span m=''149880''>the</span> <span m=''149990''>electrical</span> <span m=''150450''>world</span>
  <span m=''151640''>is that</span> <span m=''151840''>I</span> <span m=''152010''>can</span>
  <span m=''152080''>say</span> <span m=''152330''>this</span> <span m=''152540''>is</span>
  <span m=''152640''>an</span> <span m=''152750''>object,</span> <span m=''154030''>and</span>
  <span m=''154240''>this</span> <span m=''154400''>is</span> <span m=''154500''>an</span>
  <span m=''154610''>object,</span> <span m=''155630''>and they''re--</span> <span
  m=''156040''>the</span> <span m=''156210''>connection</span> <span m=''156640''>between</span>
  <span m=''156950''>them</span> <span m=''157070''>is</span> <span m=''157180''>clear.</span>
  <span m=''158310''>In</span> <span m=''158490''>principle,</span> <span m=''159700''>there
  is</span> <span m=''160030''>no</span> <span m=''160230''>connection</span> <span
  m=''160800''>that</span> <span m=''160850''>I</span> <span m=''161020''>didn''t</span>
  <span m=''161190''>describe</span> <span m=''161800''>with</span> <span m=''162110''>these</span>
  <span m=''162950''>wires.</span> </p><p><span m=''164740''>Let''s</span> <span m=''164860''>say</span>
  <span m=''165070''>if I</span> <span m=''166180''>have light bulbs,</span> <span
  m=''166560''>a</span> <span m=''166780''>light</span> <span m=''167070''>bulb</span>
  <span m=''167680''>and a</span> <span m=''168000''>power</span> <span m=''168260''>supply
  that''s</span> <span m=''168640''>plugged</span> <span m=''168920''>into</span>
  <span m=''169400''>the</span> <span m=''169960''>outlet.</span> <span m=''171370''>Then</span>
  <span m=''172020''>the</span> <span m=''172230''>connection</span> <span m=''172700''>is</span>
  <span m=''172830''>perfectly</span> <span m=''173210''>clear.</span> <span m=''173620''>There''s</span>
  <span m=''173880''>no</span> <span m=''174100''>other</span> <span m=''174340''>connections</span>
  <span m=''174860''>that</span> <span m=''174950''>we</span> <span m=''175070''>know</span>
  <span m=''175420''>of.</span> <span m=''176220''>If</span> <span m=''176520''>I
  were</span> <span m=''176610''>to</span> <span m=''176730''>tie</span> <span m=''177030''>a</span>
  <span m=''177110''>knot</span> <span m=''177950''>in</span> <span m=''178050''>the</span>
  <span m=''178150''>wire</span> <span m=''178470''>that</span> <span m=''178590''>connects</span>
  <span m=''178910''>the</span> <span m=''178990''>light</span> <span m=''179250''>bulb</span>
  <span m=''180640''>to</span> <span m=''180840''>the</span> <span m=''181610''>power</span>
  <span m=''181880''>supply,</span> <span m=''182540''>the</span> <span m=''182760''>light</span>
  <span m=''182980''>remains</span> <span m=''183370''>lit</span> <span m=''183530''>up.</span>
  <span m=''184040''>It</span> <span m=''184180''>doesn''t</span> <span m=''184480''>care.</span>
  <span m=''188300''>That the</span> <span m=''188490''>way</span> <span m=''188770''>the</span>
  <span m=''188910''>physics</span> <span m=''189220''>is</span> <span m=''189290''>arranged</span>
  <span m=''190100''>is</span> <span m=''190290''>such</span> <span m=''190550''>that</span>
  <span m=''190860''>the</span> <span m=''191120''>connection</span> <span m=''191510''>can</span>
  <span m=''191620''>be</span> <span m=''191730''>made</span> <span m=''191910''>abstract,</span>
  <span m=''193180''>at</span> <span m=''193330''>least</span> <span m=''193480''>for</span>
  <span m=''193590''>low</span> <span m=''193790''>frequencies</span> <span m=''194350''>and</span>
  <span m=''194480''>things</span> <span m=''194700''>like</span> <span m=''194920''>that.</span>
  <span m=''197840''>So</span> <span m=''198130''>in</span> <span m=''198220''>fact,</span>
  <span m=''198540''>we</span> <span m=''198650''>have</span> <span m=''198930''>captured</span>
  <span m=''199380''>all of</span> <span m=''199680''>the</span> <span m=''199780''>connections</span>
  <span m=''200260''>there</span> <span m=''200360''>really</span> <span m=''200680''>are.</span>
  </p><p><span m=''202350''>Well,</span> <span m=''202710''>as</span> <span m=''202790''>you
  can</span> <span m=''202950''>go</span> <span m=''203080''>one</span> <span m=''203320''>step</span>
  <span m=''203550''>further</span> <span m=''203830''>and</span> <span m=''203900''>talk</span>
  <span m=''204070''>about</span> <span m=''204190''>the</span> <span m=''204310''>most</span>
  <span m=''204590''>abstract</span> <span m=''205060''>types</span> <span m=''205330''>of</span>
  <span m=''206120''>electrical</span> <span m=''206490''>systems</span> <span m=''206840''>we</span>
  <span m=''207120''>have,</span> <span m=''207830''>digital</span> <span m=''208740''>to</span>
  <span m=''208910''>dual</span> <span m=''209100''>circuits.</span> <span m=''210951''>And</span>
  <span m=''211390''>here</span> <span m=''212020''>there</span> <span m=''212210''>are</span>
  <span m=''212560''>certain</span> <span m=''212900''>kinds</span> <span m=''213160''>of</span>
  <span m=''213250''>objects.</span> <span m=''214610''>For</span> <span m=''214910''>example,</span>
  <span m=''216580''>in</span> <span m=''216710''>digital</span> <span m=''217070''>circuits</span>
  <span m=''218050''>we</span> <span m=''218240''>have</span> <span m=''218440''>things</span>
  <span m=''218750''>like</span> <span m=''219400''>inverters.</span> <span m=''221092''>We</span>
  <span m=''221480''>have</span> <span m=''221710''>things</span> <span m=''221920''>like</span>
  <span m=''222110''>and-gates.</span> <span m=''223990''>We</span> <span m=''224130''>have</span>
  <span m=''224290''>things</span> <span m=''224540''>like</span> <span m=''224920''>or-gates.</span>
  <span m=''227210''>We</span> <span m=''227420''>connect</span> <span m=''227720''>them</span>
  <span m=''227850''>together</span> <span m=''228470''>by</span> <span m=''229030''>sort-of</span>
  <span m=''229470''>wires</span> <span m=''232060''>which</span> <span m=''232270''>represent</span>
  <span m=''233980''>abstract</span> <span m=''234540''>signals.</span> <span m=''235610''>We</span>
  <span m=''235780''>don''t</span> <span m=''235950''>really</span> <span m=''236110''>care</span>
  <span m=''236330''>as</span> <span m=''236440''>physical</span> <span m=''236800''>variables</span>
  <span m=''237230''>whether</span> <span m=''237390''>these</span> <span m=''237600''>are</span>
  <span m=''237650''>voltages</span> <span m=''238180''>or</span> <span m=''238270''>currents</span>
  <span m=''238700''>or</span> <span m=''238800''>some</span> <span m=''239010''>combination</span>
  <span m=''240080''>or</span> <span m=''240190''>anything</span> <span m=''240470''>like</span>
  <span m=''240720''>that,</span> <span m=''240810''>or</span> <span m=''240920''>water,</span>
  <span m=''242690''>water</span> <span m=''242940''>pressure.</span> <span m=''245160''>These</span>
  <span m=''245450''>abstract</span> <span m=''245860''>variables</span> <span m=''246220''>represent</span>
  <span m=''246670''>certain</span> <span m=''246900''>signals.</span> <span m=''249420''>And</span>
  <span m=''249640''>we</span> <span m=''249780''>build</span> <span m=''250060''>systems</span>
  <span m=''250660''>by</span> <span m=''250910''>wiring</span> <span m=''251490''>these</span>
  <span m=''251710''>things</span> <span m=''251950''>together</span> <span m=''252270''>with</span>
  <span m=''252440''>wires.</span> </p><p><span m=''254070''>So</span> <span m=''254260''>today</span>
  <span m=''254590''>what</span> <span m=''254710''>I''m</span> <span m=''254800''>going</span>
  <span m=''254870''>to</span> <span m=''254950''>show</span> <span m=''255190''>you,</span>
  <span m=''255600''>right</span> <span m=''255830''>now,</span> <span m=''257630''>we''re</span>
  <span m=''257730''>going</span> <span m=''257800''>to</span> <span m=''257880''>build</span>
  <span m=''258170''>up</span> <span m=''258410''>an</span> <span m=''258510''>invented</span>
  <span m=''258950''>language</span> <span m=''259800''>in</span> <span m=''260010''>Lisp,</span>
  <span m=''262160''>embedded</span> <span m=''262570''>in</span> <span m=''262650''>the</span>
  <span m=''262730''>same</span> <span m=''263020''>sense</span> <span m=''263310''>that</span>
  <span m=''263420''>Henderson''s</span> <span m=''263910''>picture</span> <span m=''264210''>language</span>
  <span m=''264590''>was</span> <span m=''264730''>embedded,</span> <span m=''266150''>which</span>
  <span m=''266340''>is</span> <span m=''266410''>not</span> <span m=''266620''>the</span>
  <span m=''266700''>same</span> <span m=''266960''>sense</span> <span m=''267930''>as</span>
  <span m=''268430''>the</span> <span m=''268790''>language</span> <span m=''269400''>of</span>
  <span m=''269780''>pattern</span> <span m=''270090''>match</span> <span m=''270470''>and</span>
  <span m=''270570''>substitution</span> <span m=''270870''>was</span> <span m=''271000''>done</span>
  <span m=''271190''>yesterday.</span> <span m=''272700''>The</span> <span m=''273020''>pattern</span>
  <span m=''273240''>match/substitution</span> <span m=''273880''>language</span>
  <span m=''274420''>was</span> <span m=''274630''>interpreted</span> <span m=''275410''>by</span>
  <span m=''275600''>a Lisp</span> <span m=''275850''>program.</span> <span m=''278160''>But</span>
  <span m=''278360''>the</span> <span m=''279240''>embedding</span> <span m=''279700''>of</span>
  <span m=''279850''>Henderson''s</span> <span m=''280280''>program</span> <span m=''280640''>is</span>
  <span m=''280720''>that</span> <span m=''280810''>we</span> <span m=''280920''>just</span>
  <span m=''281090''>build</span> <span m=''281310''>up</span> <span m=''281610''>more</span>
  <span m=''281850''>and</span> <span m=''281960''>more</span> <span m=''282110''>procedures</span>
  <span m=''282690''>that</span> <span m=''282890''>encapsulate</span> <span m=''283370''>the</span>
  <span m=''283440''>structure</span> <span m=''283860''>we</span> <span m=''283990''>want.</span>
  </p><p><span m=''285480''>So</span> <span m=''285700''>for</span> <span m=''285880''>example</span>
  <span m=''286330''>here,</span> <span m=''287660''>I''m</span> <span m=''287870''>going</span>
  <span m=''287930''>to</span> <span m=''287990''>have</span> <span m=''288140''>some</span>
  <span m=''288290''>various</span> <span m=''288830''>primitive</span> <span m=''289280''>kinds</span>
  <span m=''289560''>of</span> <span m=''289660''>objects,</span> <span m=''290090''>as</span>
  <span m=''290160''>you</span> <span m=''290300''>see,</span> <span m=''290930''>that</span>
  <span m=''291310''>one</span> <span m=''291480''>and</span> <span m=''291660''>that</span>
  <span m=''291850''>one.</span> <span m=''293026''>I''m</span> <span m=''293510''>going
  to</span> <span m=''293710''>use</span> <span m=''293930''>wires</span> <span m=''294350''>to</span>
  <span m=''294460''>combine</span> <span m=''294890''>them.</span> <span m=''295810''>The</span>
  <span m=''296100''>way</span> <span m=''296280''>I</span> <span m=''296410''>represent</span>
  <span m=''297510''>attaching--</span> <span m=''298420''>I</span> <span m=''298500''>can</span>
  <span m=''298650''>make</span> <span m=''298880''>wires.</span> <span m=''299870''>So</span>
  <span m=''300020''>let''s</span> <span m=''300180''>say</span> <span m=''300320''>A</span>
  <span m=''300560''>is</span> <span m=''300740''>a</span> <span m=''300800''>wire.</span>
  <span m=''301740''>And</span> <span m=''301940''>B</span> <span m=''302160''>is</span>
  <span m=''302260''>a</span> <span m=''302310''>wire.</span> <span m=''302690''>And
  C</span> <span m=''303040''>is</span> <span m=''303100''>a</span> <span m=''303170''>wire.</span>
  <span m=''303460''>And</span> <span m=''303640''>D</span> <span m=''303740''>is</span>
  <span m=''303850''>a</span> <span m=''303890''>wire.</span> <span m=''304230''>And
  E is</span> <span m=''304510''>wire.</span> <span m=''304830''>And</span> <span
  m=''305000''>S</span> <span m=''305260''>is</span> <span m=''305340''>a</span> <span
  m=''305390''>wire.</span> </p><p><span m=''306880''>Well,</span> <span m=''307770''>an</span>
  <span m=''307900''>or-gate</span> <span m=''308670''>that</span> <span m=''308990''>has</span>
  <span m=''309200''>both</span> <span m=''309480''>inputs,</span> <span m=''310130''>the</span>
  <span m=''310340''>inputs</span> <span m=''310730''>being</span> <span m=''311400''>A</span>
  <span m=''312040''>and</span> <span m=''312380''>B,</span> <span m=''313170''>and
  the</span> <span m=''313440''>output</span> <span m=''313830''>being</span> <span
  m=''314090''>Y or</span> <span m=''314420''>D,</span> <span m=''315070''>you</span>
  <span m=''315230''>notate</span> <span m=''315590''>like</span> <span m=''315830''>this.</span>
  <span m=''317940''>An</span> <span m=''318360''>and-gate,</span> <span m=''319600''>which</span>
  <span m=''319810''>has</span> <span m=''320030''>inputs</span> <span m=''320420''>A</span>
  <span m=''320670''>and</span> <span m=''320910''>B</span> <span m=''321270''>and</span>
  <span m=''321390''>output</span> <span m=''321750''>C,</span> <span m=''322230''>we</span>
  <span m=''322390''>notate</span> <span m=''322740''>like</span> <span m=''322990''>that.</span>
  <span m=''324820''>By</span> <span m=''325090''>making</span> <span m=''325600''>such</span>
  <span m=''325990''>a</span> <span m=''326090''>sequence</span> <span m=''326610''>of</span>
  <span m=''326780''>declarations,</span> <span m=''328030''>like</span> <span m=''328220''>this,</span>
  <span m=''329360''>I</span> <span m=''329530''>can</span> <span m=''329690''>wire</span>
  <span m=''329990''>together</span> <span m=''330760''>an</span> <span m=''330920''>arbitrary</span>
  <span m=''331360''>circuit.</span> <span m=''332750''>So</span> <span m=''332910''>I''ve</span>
  <span m=''332980''>just</span> <span m=''333250''>told</span> <span m=''333460''>you</span>
  <span m=''333690''>a</span> <span m=''333850''>set</span> <span m=''334030''>of</span>
  <span m=''334110''>primitives</span> <span m=''335390''>and</span> <span m=''335620''>means</span>
  <span m=''335870''>of</span> <span m=''335940''>combination</span> <span m=''336930''>for</span>
  <span m=''337590''>building</span> <span m=''337860''>digital</span> <span m=''338200''>circuits,</span>
  <span m=''340480''>when</span> <span m=''340640''>I</span> <span m=''340710''>need</span>
  <span m=''340930''>more</span> <span m=''341410''>in</span> <span m=''341530''>a</span>
  <span m=''341610''>real</span> <span m=''341830''>language</span> <span m=''342210''>than</span>
  <span m=''342300''>abstraction.</span> </p><p><span m=''343690''>And</span> <span
  m=''343850''>so</span> <span m=''344030''>for</span> <span m=''344200''>example,</span>
  <span m=''346150''>here</span> <span m=''346420''>I</span> <span m=''346680''>have--here
  I have</span> <span m=''350340''>a</span> <span m=''351430''>half</span> <span m=''351780''>adder.</span>
  <span m=''352240''>It''s</span> <span m=''352690''>something</span> <span m=''353060''>you</span>
  <span m=''353190''>all</span> <span m=''353750''>know</span> <span m=''354010''>if</span>
  <span m=''354100''>you''ve</span> <span m=''354270''>done</span> <span m=''354450''>any</span>
  <span m=''354730''>digital</span> <span m=''355110''>design.</span> <span m=''356930''>It''s</span>
  <span m=''357200''>used</span> <span m=''357510''>for</span> <span m=''358500''>adding</span>
  <span m=''358800''>numbers</span> <span m=''359120''>together</span> <span m=''359540''>on</span>
  <span m=''359770''>A and</span> <span m=''360110''>B</span> <span m=''360660''>and</span>
  <span m=''360830''>putting</span> <span m=''361100''>out</span> <span m=''361260''>a
  sum</span> <span m=''361620''>and</span> <span m=''361670''>a</span> <span m=''361730''>carry.</span>
  <span m=''363956''>And</span> <span m=''364390''>in</span> <span m=''364580''>fact,</span>
  <span m=''364820''>the</span> <span m=''364900''>wiring</span> <span m=''365260''>diagram</span>
  <span m=''365620''>is</span> <span m=''365710''>exactly</span> <span m=''366150''>what</span>
  <span m=''366260''>I</span> <span m=''366350''>told</span> <span m=''366610''>you.</span>
  <span m=''367450''>A</span> <span m=''367600''>half</span> <span m=''367810''>adder</span>
  <span m=''368740''>with</span> <span m=''369550''>things</span> <span m=''369860''>that</span>
  <span m=''370010''>come</span> <span m=''370230''>out</span> <span m=''370480''>of</span>
  <span m=''370570''>the</span> <span m=''370660''>box--</span> <span m=''371160''>you</span>
  <span m=''371260''>see</span> <span m=''371410''>the</span> <span m=''371490''>box,</span>
  <span m=''371880''>the</span> <span m=''371970''>boundary,</span> <span m=''372600''>the</span>
  <span m=''372800''>abstraction</span> <span m=''373400''>is</span> <span m=''373520''>always</span>
  <span m=''373810''>a</span> <span m=''373860''>box.</span> <span m=''374790''>And</span>
  <span m=''374900''>there</span> <span m=''374980''>are</span> <span m=''375020''>things</span>
  <span m=''375250''>that</span> <span m=''375340''>come</span> <span m=''375550''>out</span>
  <span m=''375710''>of</span> <span m=''375870''>it,</span> <span m=''377770''>A,</span>
  <span m=''378000''>B,</span> <span m=''378260''>S,</span> <span m=''378480''>and</span>
  <span m=''378590''>C.</span> <span m=''379700''>Those</span> <span m=''380110''>are</span>
  <span m=''380520''>the</span> <span m=''380700''>declared</span> <span m=''381200''>variables--declared
  variables</span> <span m=''384950''>of</span> <span m=''385530''>a</span> <span
  m=''385630''>lambda</span> <span m=''385940''>expression,</span> <span m=''386420''>which</span>
  <span m=''386620''>is the</span> <span m=''386700''>one</span> <span m=''386890''>that</span>
  <span m=''387020''>defines</span> <span m=''387460''>half</span> <span m=''387660''>adder.</span>
  </p><p><span m=''391400''>And</span> <span m=''391540''>internal</span> <span m=''391930''>to</span>
  <span m=''392030''>that,</span> <span m=''392620''>I</span> <span m=''392750''>make</span>
  <span m=''393010''>up</span> <span m=''393140''>some</span> <span m=''393380''>more</span>
  <span m=''393610''>wires,</span> <span m=''395250''>D</span> <span m=''395450''>and</span>
  <span m=''395660''>E,</span> <span m=''396080''>which</span> <span m=''396270''>I''m</span>
  <span m=''396340''>going</span> <span m=''396400''>to</span> <span m=''396460''>use</span>
  <span m=''396760''>for</span> <span m=''396840''>the</span> <span m=''396940''>interconnect--</span>
  <span m=''397760''>here</span> <span m=''398020''>E is</span> <span m=''398350''>this</span>
  <span m=''398550''>one</span> <span m=''399130''>and</span> <span m=''399470''>D</span>
  <span m=''399680''>is</span> <span m=''399810''>this</span> <span m=''400010''>wire,</span>
  <span m=''401140''>the</span> <span m=''401450''>interconnect</span> <span m=''401860''>that</span>
  <span m=''402000''>doesn''t</span> <span m=''402260''>come</span> <span m=''402430''>through</span>
  <span m=''402630''>the</span> <span m=''402810''>walls</span> <span m=''403110''>of</span>
  <span m=''403170''>the</span> <span m=''403240''>box--</span> <span m=''405100''>and</span>
  <span m=''405280''>wire</span> <span m=''405560''>things</span> <span m=''405790''>together</span>
  <span m=''406170''>as</span> <span m=''406290''>you</span> <span m=''406400''>just</span>
  <span m=''406630''>saw.</span> <span m=''408790''>And</span> <span m=''408910''>the</span>
  <span m=''409030''>nice</span> <span m=''409330''>thing</span> <span m=''409510''>about</span>
  <span m=''409820''>this</span> <span m=''410070''>that I''ve</span> <span m=''410260''>just</span>
  <span m=''410480''>shown</span> <span m=''410710''>you</span> <span m=''411030''>is
  this</span> <span m=''411330''>language</span> <span m=''411640''>is</span> <span
  m=''411720''>hierarchical</span> <span m=''412410''>in</span> <span m=''412470''>the</span>
  <span m=''412560''>right</span> <span m=''412790''>way.</span> <span m=''413890''>If</span>
  <span m=''414000''>a</span> <span m=''414070''>language</span> <span m=''414440''>isn''t</span>
  <span m=''414660''>hierarchical</span> <span m=''414925''>in</span> <span m=''415190''>the</span>
  <span m=''415270''>right</span> <span m=''415460''>way,</span> <span m=''415950''>if</span>
  <span m=''416100''>it</span> <span m=''416190''>turns</span> <span m=''416470''>out</span>
  <span m=''416940''>that</span> <span m=''417440''>a</span> <span m=''417730''>compound</span>
  <span m=''418140''>object</span> <span m=''418420''>doesn''t</span> <span m=''418650''>look</span>
  <span m=''418850''>like</span> <span m=''419070''>a</span> <span m=''419520''>primitive,</span>
  <span m=''420370''>there''s</span> <span m=''420550''>something</span> <span m=''420820''>wrong</span>
  <span m=''421030''>with the</span> <span m=''421410''>language--</span> <span m=''422180''>at</span>
  <span m=''422670''>least</span> <span m=''423000''>the</span> <span m=''423210''>way</span>
  <span m=''423340''>I</span> <span m=''423480''>feel</span> <span m=''423700''>about</span>
  <span m=''423960''>that.</span> </p><p><span m=''426300''>So</span> <span m=''426560''>here
  we have--here,</span> <span m=''427500''>instead</span> <span m=''427670''>of</span>
  <span m=''427840''>starting</span> <span m=''428180''>with</span> <span m=''428540''>mathematical</span>
  <span m=''429220''>functions,</span> <span m=''429660''>or</span> <span m=''429750''>things</span>
  <span m=''429970''>that</span> <span m=''430080''>compute</span> <span m=''430410''>mathematical</span>
  <span m=''430900''>functions,</span> <span m=''431230''>which is</span> <span m=''431360''>what</span>
  <span m=''431540''>we''ve</span> <span m=''431700''>been</span> <span m=''431810''>doing</span>
  <span m=''431990''>up</span> <span m=''432160''>until</span> <span m=''432340''>now,</span>
  <span m=''433870''>instead</span> <span m=''434170''>of</span> <span m=''434460''>starting</span>
  <span m=''434860''>with</span> <span m=''434980''>things</span> <span m=''435170''>that</span>
  <span m=''435350''>look</span> <span m=''435580''>like</span> <span m=''435770''>mathematical</span>
  <span m=''436260''>functions,</span> <span m=''436710''>or</span> <span m=''436820''>compute</span>
  <span m=''437140''>such</span> <span m=''437360''>things,</span> <span m=''437630''>we</span>
  <span m=''437900''>are</span> <span m=''438080''>starting</span> <span m=''438820''>with</span>
  <span m=''439050''>things</span> <span m=''439310''>that</span> <span m=''439520''>are</span>
  <span m=''440080''>electrical</span> <span m=''440520''>objects</span> <span m=''441060''>and</span>
  <span m=''441190''>we</span> <span m=''441330''>build</span> <span m=''441550''>up</span>
  <span m=''441770''>more</span> <span m=''441970''>electrical</span> <span m=''442350''>objects.</span>
  <span m=''443350''>And</span> <span m=''443590''>the</span> <span m=''443670''>glue</span>
  <span m=''444040''>we''re</span> <span m=''444130''>using</span> <span m=''445610''>is</span>
  <span m=''445790''>basically</span> <span m=''446320''>the</span> <span m=''446590''>Lisp</span>
  <span m=''446860''>structure:</span> <span m=''448320''>lambdas.</span> <span m=''450500''>Lambda</span>
  <span m=''450790''>is</span> <span m=''450950''>the</span> <span m=''451070''>ultimate</span>
  <span m=''451400''>glue,</span> <span m=''452165''>if</span> <span m=''452520''>you</span>
  <span m=''452660''>will.</span> </p><p><span m=''452930''>And</span> <span m=''453350''>of</span>
  <span m=''453640''>course,</span> <span m=''454170''>half</span> <span m=''454430''>adder</span>
  <span m=''454750''>itself</span> <span m=''455630''>can</span> <span m=''455890''>be</span>
  <span m=''455980''>used</span> <span m=''457650''>in</span> <span m=''457830''>a</span>
  <span m=''458770''>more</span> <span m=''459000''>complicated</span> <span m=''459580''>abstraction</span>
  <span m=''460170''>called</span> <span m=''460370''>a</span> <span m=''460410''>full</span>
  <span m=''460670''>adder,</span> <span m=''461670''>which</span> <span m=''461840''>in</span>
  <span m=''461960''>fact</span> <span m=''462250''>involves</span> <span m=''463110''>two</span>
  <span m=''463420''>half</span> <span m=''463680''>adders,</span> <span m=''464400''>as</span>
  <span m=''464510''>you</span> <span m=''464610''>see</span> <span m=''464810''>here,</span>
  <span m=''465230''>hooked</span> <span m=''465670''>together</span> <span m=''466670''>with</span>
  <span m=''466870''>some</span> <span m=''467040''>extra</span> <span m=''467390''>wires,</span>
  <span m=''468030''>that</span> <span m=''468170''>you</span> <span m=''468310''>see</span>
  <span m=''468490''>here,</span> <span m=''468700''>S,</span> <span m=''468910''>C1,</span>
  <span m=''469130''>and</span> <span m=''469420''>C2,</span> <span m=''470600''>and</span>
  <span m=''470770''>an</span> <span m=''471100''>or-gate,</span> <span m=''471930''>to</span>
  <span m=''472340''>manufacture</span> <span m=''472910''>a</span> <span m=''472950''>full</span>
  <span m=''473130''>adder,</span> <span m=''473880''>which</span> <span m=''474040''>takes</span>
  <span m=''474710''>a</span> <span m=''477340''>input</span> <span m=''477700''>number,</span>
  <span m=''478470''>another</span> <span m=''478850''>input</span> <span m=''479150''>number,</span>
  <span m=''479960''>a</span> <span m=''480090''>carry</span> <span m=''480510''>in,</span>
  <span m=''481360''>and</span> <span m=''481570''>produces</span> <span m=''482050''>output,</span>
  <span m=''482910''>a</span> <span m=''483040''>sum</span> <span m=''483460''>and</span>
  <span m=''483540''>a</span> <span m=''483630''>carry</span> <span m=''483990''>out.</span>
  <span m=''485900''>And</span> <span m=''485970''>out</span> <span m=''486070''>of</span>
  <span m=''486180''>full</span> <span m=''486410''>adders,</span> <span m=''486750''>you
  can</span> <span m=''486860''>make</span> <span m=''487050''>real</span> <span m=''487620''>adder</span>
  <span m=''488120''>chains</span> <span m=''489420''>and</span> <span m=''489820''>big</span>
  <span m=''490460''>adders.</span> </p><p><span m=''492990''>So</span> <span m=''493190''>we</span>
  <span m=''493340''>have</span> <span m=''493580''>here</span> <span m=''493760''>a</span>
  <span m=''493840''>language</span> <span m=''494230''>so</span> <span m=''494470''>far</span>
  <span m=''495750''>that</span> <span m=''496280''>has</span> <span m=''497500''>primitives,</span>
  <span m=''498600''>means</span> <span m=''498870''>of</span> <span m=''498920''>combination,</span>
  <span m=''499620''>and</span> <span m=''499760''>means</span> <span m=''499960''>of</span>
  <span m=''500050''>abstraction</span> <span m=''501110''>to</span> <span m=''501240''>real</span>
  <span m=''501430''>language.</span> <span m=''502270''>Now,</span> <span m=''502400''>how</span>
  <span m=''502560''>are we</span> <span m=''502650''>going</span> <span m=''502720''>to</span>
  <span m=''502800''>implement</span> <span m=''503230''>this?</span> <span m=''505000''>Well,</span>
  <span m=''505620''>let''s</span> <span m=''506040''>do</span> <span m=''506270''>it</span>
  <span m=''506430''>easily.</span> <span m=''507070''>Let''s</span> <span m=''507280''>look</span>
  <span m=''507380''>at</span> <span m=''507480''>the</span> <span m=''507550''>primitives.</span>
  <span m=''508610''>The only</span> <span m=''508820''>problem is</span> <span m=''509180''>we</span>
  <span m=''509290''>have</span> <span m=''509390''>to implement</span> <span m=''509540''>the</span>
  <span m=''509660''>primitives.</span> <span m=''511160''>Nothing</span> <span m=''511510''>else</span>
  <span m=''511700''>has</span> <span m=''511880''>to</span> <span m=''511940''>be</span>
  <span m=''512039''>implemented,</span> <span m=''513590''>because</span> <span m=''514159''>we''re</span>
  <span m=''514270''>picking</span> <span m=''514559''>up</span> <span m=''514700''>the</span>
  <span m=''514830''>means</span> <span m=''515049''>of</span> <span m=''515110''>combination</span>
  <span m=''515400''>and</span> <span m=''515690''>abstraction</span> <span m=''517640''>from</span>
  <span m=''517850''>Lisp,</span> <span m=''520090''>inheriting</span> <span m=''520640''>them</span>
  <span m=''520820''>in</span> <span m=''521200''>the</span> <span m=''521480''>embedding.</span>
  </p><p><span m=''523417''>OK,</span> <span m=''523820''>so</span> <span m=''523970''>let''s</span>
  <span m=''524220''>look</span> <span m=''524350''>at</span> <span m=''524420''>a</span>
  <span m=''524490''>particular</span> <span m=''525000''>primitive.</span> <span
  m=''525860''>An</span> <span m=''526130''>inverter</span> <span m=''526690''>is</span>
  <span m=''526800''>a</span> <span m=''526860''>nice</span> <span m=''527160''>one.</span>
  <span m=''531540''>Now,</span> <span m=''531720''>inverter</span> <span m=''532440''>has</span>
  <span m=''532810''>two</span> <span m=''532950''>wires</span> <span m=''533320''>coming</span>
  <span m=''533580''>in,</span> <span m=''533900''>an in</span> <span m=''534210''>and
  an</span> <span m=''534460''>out.</span> <span m=''537440''>And</span> <span m=''537550''>somehow,</span>
  <span m=''538570''>it''s</span> <span m=''538790''>going</span> <span m=''539040''>to</span>
  <span m=''539130''>have</span> <span m=''539390''>to</span> <span m=''539990''>know</span>
  <span m=''540220''>what</span> <span m=''540400''>to</span> <span m=''540500''>do</span>
  <span m=''541260''>when</span> <span m=''541490''>a</span> <span m=''541570''>signal</span>
  <span m=''541960''>comes</span> <span m=''542250''>in.</span> <span m=''544300''>So</span>
  <span m=''544480''>somehow</span> <span m=''544840''>it''s</span> <span m=''544950''>going</span>
  <span m=''545060''>to</span> <span m=''545170''>have</span> <span m=''545340''>to</span>
  <span m=''545440''>tell</span> <span m=''545990''>its</span> <span m=''546260''>input</span>
  <span m=''546580''>wire--</span> <span m=''547710''>and</span> <span m=''547900''>now</span>
  <span m=''548050''>we''re</span> <span m=''548170''>going</span> <span m=''548230''>to</span>
  <span m=''548300''>talk</span> <span m=''548510''>about</span> <span m=''549560''>objects</span>
  <span m=''550530''>and</span> <span m=''550650''>we''re going to</span> <span m=''550810''>see</span>
  <span m=''550980''>this</span> <span m=''551120''>in a</span> <span m=''551200''>little</span>
  <span m=''551390''>more</span> <span m=''551550''>detail</span> <span m=''551950''>soon--</span>
  <span m=''553260''>but</span> <span m=''553430''>it''s going</span> <span m=''553680''>to
  have to tell</span> <span m=''553990''>its input</span> <span m=''554360''>wire</span>
  <span m=''555850''>that</span> <span m=''556210''>when</span> <span m=''556490''>you</span>
  <span m=''556660''>change,</span> <span m=''557920''>tell</span> <span m=''558170''>me.</span>
  <span m=''560120''>So</span> <span m=''560280''>this</span> <span m=''560500''>object,</span>
  <span m=''561010''>the</span> <span m=''561210''>object</span> <span m=''561610''>which
  is</span> <span m=''561720''>the inverter</span> <span m=''562370''>has</span> <span
  m=''562650''>to</span> <span m=''562720''>tell</span> <span m=''563000''>the</span>
  <span m=''563140''>object</span> <span m=''563490''>which</span> <span m=''563620''>is</span>
  <span m=''563690''>the</span> <span m=''563810''>input</span> <span m=''564145''>wire,</span>
  <span m=''565070''>hi,</span> <span m=''565550''>my</span> <span m=''565780''>name</span>
  <span m=''565970''>is</span> <span m=''566090''>George.</span> <span m=''566870''>And</span>
  <span m=''567340''>my, my</span> <span m=''567520''>job</span> <span m=''568710''>is</span>
  <span m=''569010''>to</span> <span m=''569160''>do</span> <span m=''569320''>something</span>
  <span m=''569730''>with</span> <span m=''569940''>results</span> <span m=''570330''>when</span>
  <span m=''570480''>you</span> <span m=''570620''>change.</span> <span m=''571720''>So
  when</span> <span m=''571920''>you</span> <span m=''572100''>change,</span> <span
  m=''572640''>you</span> <span m=''572750''>get a</span> <span m=''572940''>change,</span>
  <span m=''573470''>tell</span> <span m=''573650''>me</span> <span m=''573790''>about</span>
  <span m=''574070''>it.</span> <span m=''574730''>Because</span> <span m=''574870''>I''ve
  got to</span> <span m=''575010''>do</span> <span m=''575160''>something</span> <span
  m=''575440''>with</span> <span m=''575560''>that.</span> </p><p><span m=''577010''>Well,</span>
  <span m=''577110''>that''s</span> <span m=''577360''>done</span> <span m=''577590''>down</span>
  <span m=''577810''>here</span> <span m=''578460''>by</span> <span m=''579230''>adding
  an</span> <span m=''579610''>action</span> <span m=''581540''>on</span> <span m=''581770''>the</span>
  <span m=''581870''>input</span> <span m=''582200''>wire</span> <span m=''583540''>called</span>
  <span m=''583820''>invert-in,</span> <span m=''585080''>where</span> <span m=''585270''>invert-in</span>
  <span m=''585660''>is</span> <span m=''585960''>defined</span> <span m=''586420''>over</span>
  <span m=''586600''>here</span> <span m=''587020''>to</span> <span m=''587120''>be</span>
  <span m=''587230''>a</span> <span m=''587280''>procedure</span> <span m=''588040''>of</span>
  <span m=''588150''>no</span> <span m=''588330''>arguments,</span> <span m=''589950''>which</span>
  <span m=''590750''>gets</span> <span m=''591080''>the</span> <span m=''591660''>logical</span>
  <span m=''592210''>not</span> <span m=''592960''>of</span> <span m=''593080''>the</span>
  <span m=''593210''>signal</span> <span m=''593600''>on</span> <span m=''593730''>the</span>
  <span m=''593860''>input</span> <span m=''594140''>wire.</span> <span m=''596130''>And</span>
  <span m=''596380''>after</span> <span m=''596710''>some</span> <span m=''596930''>delay,</span>
  <span m=''597300''>which</span> <span m=''597480''>is</span> <span m=''597560''>the</span>
  <span m=''597680''>inverter</span> <span m=''598100''>delay,</span> <span m=''599330''>all</span>
  <span m=''599520''>these</span> <span m=''599720''>electrical</span> <span m=''600130''>objects</span>
  <span m=''600490''>have</span> <span m=''600610''>delays,</span> <span m=''602870''>we''ll</span>
  <span m=''603460''>do</span> <span m=''603640''>the</span> <span m=''603740''>following</span>
  <span m=''604110''>thing--</span> <span m=''604560''>set</span> <span m=''604910''>the</span>
  <span m=''604980''>signal</span> <span m=''605380''>on</span> <span m=''605500''>the</span>
  <span m=''605650''>output</span> <span m=''606000''>wire</span> <span m=''606340''>to</span>
  <span m=''606460''>the</span> <span m=''606570''>new</span> <span m=''606710''>value.</span>
  <span m=''610160''>A</span> <span m=''610270''>very</span> <span m=''610530''>simple</span>
  <span m=''610850''>program.</span> </p><p><span m=''612400''>Now,</span> <span m=''612600''>you</span>
  <span m=''612680''>have</span> <span m=''612760''>to</span> <span m=''612850''>imagine</span>
  <span m=''613470''>that</span> <span m=''613830''>the</span> <span m=''613940''>output</span>
  <span m=''614240''>wire</span> <span m=''614540''>has</span> <span m=''614660''>to</span>
  <span m=''614720''>be</span> <span m=''614820''>sensitive</span> <span m=''615730''>and</span>
  <span m=''615960''>know</span> <span m=''616350''>that</span> <span m=''616600''>when</span>
  <span m=''616750''>its</span> <span m=''617100''>signal</span> <span m=''617780''>changes,</span>
  <span m=''619350''>it</span> <span m=''619530''>may</span> <span m=''619650''>have</span>
  <span m=''619820''>to</span> <span m=''619910''>tell</span> <span m=''620530''>other</span>
  <span m=''620740''>guys,</span> <span m=''621810''>hey,</span> <span m=''621980''>wake</span>
  <span m=''622230''>up.</span> <span m=''623840''>My</span> <span m=''624020''>value
  has</span> <span m=''624470''>changed.</span> <span m=''626050''>So</span> <span
  m=''626220''>when</span> <span m=''626360''>you hook</span> <span m=''626570''>together</span>
  <span m=''627400''>inverter</span> <span m=''628470''>with an</span> <span m=''628770''>and-gate</span>
  <span m=''629240''>or</span> <span m=''629350''>something</span> <span m=''629700''>like</span>
  <span m=''629930''>that,</span> <span m=''630390''>there</span> <span m=''630730''>has</span>
  <span m=''630830''>to be a</span> <span m=''630890''>lot</span> <span m=''630980''>of</span>
  <span m=''631070''>communication</span> <span m=''631680''>going</span> <span m=''631930''>on</span>
  <span m=''632930''>in order</span> <span m=''633050''>to</span> <span m=''633130''>make</span>
  <span m=''633290''>sure</span> <span m=''633750''>that</span> <span m=''633980''>the</span>
  <span m=''634040''>signal</span> <span m=''634310''>propagates</span> <span m=''634810''>right.</span>
  <span m=''636810''>And</span> <span m=''637060''>down</span> <span m=''637270''>here</span>
  <span m=''637520''>is</span> <span m=''637620''>nothing</span> <span m=''637900''>very</span>
  <span m=''638140''>exciting.</span> <span m=''638620''>This</span> <span m=''638790''>is</span>
  <span m=''638910''>just</span> <span m=''639260''>the</span> <span m=''639510''>definition</span>
  <span m=''639940''>of</span> <span m=''640050''>logical</span> <span m=''640460''>not</span>
  <span m=''640740''>for</span> <span m=''640870''>some</span> <span m=''641100''>particular</span>
  <span m=''641820''>representations</span> <span m=''642560''>of</span> <span m=''642760''>the</span>
  <span m=''643290''>logical</span> <span m=''643690''>values--</span> <span m=''644170''>1,</span>
  <span m=''644430''>0</span> <span m=''644780''>in</span> <span m=''644890''>this</span>
  <span m=''645000''>case.</span> </p><p><span m=''646240''>And</span> <span m=''646910''>we</span>
  <span m=''647080''>can</span> <span m=''647230''>look</span> <span m=''647410''>at</span>
  <span m=''647500''>things</span> <span m=''647740''>more</span> <span m=''648000''>complicated</span>
  <span m=''648550''>like</span> <span m=''648740''>and-gates.</span> <span m=''649780''>And-gates</span>
  <span m=''651000''>take</span> <span m=''651280''>two</span> <span m=''651500''>inputs,</span>
  <span m=''653170''>A1</span> <span m=''653550''>and</span> <span m=''653670''>A2,
  we''ll</span> <span m=''654000''>call</span> <span m=''654270''>them,</span> <span
  m=''654910''>and</span> <span m=''655000''>produce</span> <span m=''655280''>an</span>
  <span m=''655370''>output.</span> <span m=''656950''>But</span> <span m=''657060''>the</span>
  <span m=''657220''>structure</span> <span m=''657790''>of</span> <span m=''657880''>the</span>
  <span m=''658020''>and-gate</span> <span m=''658450''>is</span> <span m=''658580''>identical</span>
  <span m=''659530''>to</span> <span m=''659770''>the</span> <span m=''659840''>one</span>
  <span m=''660000''>we</span> <span m=''660120''>just</span> <span m=''660370''>saw.</span>
  <span m=''660860''>There''s</span> <span m=''661070''>one</span> <span m=''661270''>called</span>
  <span m=''661550''>an</span> <span m=''661670''>and-action</span> <span m=''662370''>procedure</span>
  <span m=''662790''>that''s</span> <span m=''663000''>defined,</span> <span m=''664570''>which</span>
  <span m=''664780''>is</span> <span m=''664860''>the</span> <span m=''664980''>thing</span>
  <span m=''665190''>that</span> <span m=''665340''>gets</span> <span m=''665570''>called</span>
  <span m=''667410''>when</span> <span m=''667810''>an</span> <span m=''668110''>input</span>
  <span m=''668570''>is</span> <span m=''668740''>changed.</span> <span m=''670910''>And</span>
  <span m=''671130''>what</span> <span m=''671280''>it</span> <span m=''671380''>does,</span>
  <span m=''671740''>of</span> <span m=''671850''>course,</span> <span m=''672150''>is</span>
  <span m=''672250''>nothing</span> <span m=''672530''>more</span> <span m=''672700''>than</span>
  <span m=''672880''>compute</span> <span m=''673230''>the</span> <span m=''673310''>logical</span>
  <span m=''673740''>and</span> <span m=''674170''>of</span> <span m=''674350''>the</span>
  <span m=''674420''>signals</span> <span m=''674780''>on</span> <span m=''674880''>the</span>
  <span m=''674980''>inputs.</span> <span m=''675900''>And</span> <span m=''676220''>after</span>
  <span m=''676720''>some</span> <span m=''676930''>delay,</span> <span m=''677550''>called</span>
  <span m=''677880''>the and-gate</span> <span m=''678260''>delay,</span> <span m=''680490''>calls</span>
  <span m=''680720''>this</span> <span m=''680890''>procedure,</span> <span m=''681320''>which</span>
  <span m=''681520''>sets</span> <span m=''681780''>a</span> <span m=''681820''>signal</span>
  <span m=''682180''>on</span> <span m=''682290''>the</span> <span m=''682400''>output</span>
  <span m=''683440''>to</span> <span m=''683570''>a</span> <span m=''683710''>new</span>
  <span m=''683840''>value.</span> </p><p><span m=''685470''>Now,</span> <span m=''685940''>how</span>
  <span m=''686200''>I</span> <span m=''686340''>implement</span> <span m=''686800''>these</span>
  <span m=''687030''>things</span> <span m=''687320''>is all</span> <span m=''687490''>wishful</span>
  <span m=''687820''>thinking.</span> <span m=''688350''>As</span> <span m=''688580''>you</span>
  <span m=''688730''>see</span> <span m=''688940''>here,</span> <span m=''689205''>I</span>
  <span m=''689470''>have</span> <span m=''689750''>an</span> <span m=''689850''>assignment</span>
  <span m=''690370''>operation.</span> <span m=''692020''>It''s</span> <span m=''692210''>not</span>
  <span m=''692470''>set.</span> <span m=''694570''>It''s</span> <span m=''694730''>a</span>
  <span m=''694790''>derived</span> <span m=''695290''>assignment</span> <span m=''695720''>operation</span>
  <span m=''696190''>in</span> <span m=''696270''>the</span> <span m=''696350''>same</span>
  <span m=''696600''>way</span> <span m=''696710''>we</span> <span m=''696820''>had</span>
  <span m=''697020''>functions</span> <span m=''697460''>that</span> <span m=''697570''>were</span>
  <span m=''697660''>derived</span> <span m=''697950''>from</span> <span m=''698070''>CAR
  and</span> <span m=''698390''>CDR.</span> <span m=''701000''>So</span> <span m=''701140''>I,</span>
  <span m=''701660''>by</span> <span m=''701860''>convention,</span> <span m=''703050''>label</span>
  <span m=''703380''>that</span> <span m=''703730''>with</span> <span m=''703890''>an</span>
  <span m=''704010''>exclamation</span> <span m=''704590''>point.</span> <span m=''706340''>And</span>
  <span m=''706520''>over</span> <span m=''706720''>here,</span> <span m=''707770''>you</span>
  <span m=''707920''>see</span> <span m=''708100''>there''s</span> <span m=''708390''>an</span>
  <span m=''708650''>action,</span> <span m=''709510''>which</span> <span m=''709730''>is</span>
  <span m=''709830''>to</span> <span m=''709970''>inform</span> <span m=''710730''>the</span>
  <span m=''711140''>wire,</span> <span m=''712210''>called</span> <span m=''712550''>A1</span>
  <span m=''713110''>locally</span> <span m=''713630''>in</span> <span m=''713830''>this</span>
  <span m=''714070''>and-gate,</span> <span m=''715590''>to</span> <span m=''715990''>call</span>
  <span m=''716650''>the</span> <span m=''717190''>and-action</span> <span m=''717660''>procedure
  when it</span> <span m=''718030''>gets</span> <span m=''718320''>changed,</span>
  <span m=''719550''>and</span> <span m=''719680''>the</span> <span m=''719810''>wire</span>
  <span m=''720400''>A2</span> <span m=''720960''>to</span> <span m=''721110''>call</span>
  <span m=''721310''>the</span> <span m=''721450''>and-action</span> <span m=''721910''>procedure</span>
  <span m=''722100''>when it</span> <span m=''722430''>gets</span> <span m=''722590''>changed.</span>
  <span m=''726310''>All</span> <span m=''726600''>very</span> <span m=''726840''>simple.</span>
  </p><p><span m=''729510''>Well,</span> <span m=''729970''>let''s</span> <span m=''730280''>talk</span>
  <span m=''730520''>a</span> <span m=''730580''>little</span> <span m=''730760''>bit</span>
  <span m=''730890''>about</span> <span m=''731120''>this</span> <span m=''731280''>communication</span>
  <span m=''732060''>that</span> <span m=''732870''>must</span> <span m=''733130''>occur</span>
  <span m=''734280''>between</span> <span m=''734690''>these</span> <span m=''735360''>various</span>
  <span m=''735790''>parts.</span> <span m=''738310''>Suppose,</span> <span m=''739040''>for</span>
  <span m=''739180''>example,</span> <span m=''743170''>I</span> <span m=''743320''>have</span>
  <span m=''743390''>a</span> <span m=''743460''>very</span> <span m=''743690''>simple</span>
  <span m=''744000''>circuit</span> <span m=''744460''>which</span> <span m=''744560''>contains</span>
  <span m=''745780''>an</span> <span m=''745940''>and</span> <span m=''747390''>with</span>
  <span m=''747910''>wires</span> <span m=''748940''>A</span> <span m=''749640''>and</span>
  <span m=''749980''>B.</span> <span m=''752010''>And</span> <span m=''753000''>that</span>
  <span m=''753310''>connects</span> <span m=''754230''>through</span> <span m=''754420''>a</span>
  <span m=''754480''>wire</span> <span m=''754890''>called</span> <span m=''755220''>C</span>
  <span m=''757060''>to</span> <span m=''757190''>an</span> <span m=''757330''>inverter</span>
  <span m=''759810''>which</span> <span m=''760040''>has</span> <span m=''760240''>a</span>
  <span m=''760280''>wire</span> <span m=''760580''>output</span> <span m=''760910''>called</span>
  <span m=''761200''>D.</span> <span m=''765920''>What are the comput...--here''s</span>
  <span m=''766310''>the</span> <span m=''766660''>physical</span> <span m=''767080''>world.</span>
  <span m=''767360''>It''s</span> <span m=''767490''>an</span> <span m=''767720''>abstraction</span>
  <span m=''768200''>of the</span> <span m=''768280''>physical</span> <span m=''768700''>world.</span>
  <span m=''769860''>Now I</span> <span m=''770040''>can</span> <span m=''770200''>buy</span>
  <span m=''770430''>these</span> <span m=''770630''>out of</span> <span m=''770750''>little</span>
  <span m=''771090''>pieces</span> <span m=''771510''>that</span> <span m=''771630''>you</span>
  <span m=''771760''>get</span> <span m=''771880''>at</span> <span m=''772010''>Radio</span>
  <span m=''772280''>Shack</span> <span m=''772640''>for</span> <span m=''772800''>a</span>
  <span m=''772860''>few</span> <span m=''773040''>cents.</span> <span m=''774880''>And</span>
  <span m=''775040''>there</span> <span m=''775150''>are</span> <span m=''775200''>boxes</span>
  <span m=''775620''>that</span> <span m=''775700''>act</span> <span m=''775950''>like</span>
  <span m=''776150''>this,</span> <span m=''777210''>which have</span> <span m=''777290''>little</span>
  <span m=''777680''>numbers</span> <span m=''777960''>on them</span> <span m=''778160''>like</span>
  <span m=''778380''>LS04</span> <span m=''779790''>or</span> <span m=''779880''>something.</span>
  </p><p><span m=''781530''>Now</span> <span m=''782710''>supposing</span> <span m=''783720''>I</span>
  <span m=''783830''>were</span> <span m=''784030''>to</span> <span m=''785090''>try</span>
  <span m=''785320''>to</span> <span m=''785390''>say</span> <span m=''785540''>what''s</span>
  <span m=''785760''>the</span> <span m=''786980''>computational</span> <span m=''787720''>model.</span>
  <span m=''789010''>What</span> <span m=''789160''>is</span> <span m=''789280''>the</span>
  <span m=''789380''>thing</span> <span m=''789730''>that</span> <span m=''789880''>corresponds</span>
  <span m=''790610''>to</span> <span m=''790720''>that, that</span> <span m=''791460''>part</span>
  <span m=''791610''>of</span> <span m=''791770''>reality</span> <span m=''792490''>in</span>
  <span m=''792650''>the</span> <span m=''792720''>mind</span> <span m=''793010''>of</span>
  <span m=''793110''>us</span> <span m=''793350''>and</span> <span m=''793480''>in</span>
  <span m=''793560''>the</span> <span m=''793630''>computer?</span> <span m=''795850''>Well,</span>
  <span m=''796220''>I have to</span> <span m=''796350''>assign</span> <span m=''796730''>for</span>
  <span m=''796850''>every</span> <span m=''797070''>object</span> <span m=''797360''>in</span>
  <span m=''797440''>the</span> <span m=''797490''>world</span> <span m=''798070''>an</span>
  <span m=''798200''>object</span> <span m=''798520''>in</span> <span m=''798590''>the</span>
  <span m=''798660''>computer,</span> <span m=''799550''>and</span> <span m=''799860''>for</span>
  <span m=''799980''>every</span> <span m=''800980''>relationship</span> <span m=''801890''>in</span>
  <span m=''802010''>the</span> <span m=''802160''>world</span> <span m=''802320''>between</span>
  <span m=''802670''>them</span> <span m=''802900''>a</span> <span m=''803220''>relationship</span>
  <span m=''803830''>in</span> <span m=''803900''>the</span> <span m=''803980''>computer.</span>
  <span m=''805750''>That''s</span> <span m=''806280''>my</span> <span m=''806410''>goal.</span>
  </p><p><span m=''808560''>So</span> <span m=''808920''>let''s</span> <span m=''809140''>do</span>
  <span m=''809280''>that.</span> <span m=''810900''>Well,</span> <span m=''811080''>I</span>
  <span m=''811160''>have</span> <span m=''811440''>some</span> <span m=''811720''>sort</span>
  <span m=''811960''>of</span> <span m=''812040''>thing</span> <span m=''812340''>called</span>
  <span m=''812980''>the</span> <span m=''813120''>signal,</span> <span m=''813840''>A.</span>
  <span m=''815401''>This is</span> <span m=''815810''>A.</span> <span m=''816100''>It''s</span>
  <span m=''816580''>a</span> <span m=''816700''>signal.</span> <span m=''817940''>It''s
  a</span> <span m=''818130''>cloudy</span> <span m=''818580''>thing</span> <span
  m=''818780''>like</span> <span m=''819020''>that.</span> <span m=''819900''>And</span>
  <span m=''820050''>I</span> <span m=''820200''>have</span> <span m=''820300''>another</span>
  <span m=''820570''>one</span> <span m=''820800''>down</span> <span m=''821060''>here</span>
  <span m=''821810''>which I''m</span> <span m=''821990''>going</span> <span m=''822080''>to</span>
  <span m=''822180''>call</span> <span m=''822390''>B.</span> <span m=''826720''>It''s</span>
  <span m=''826950''>another</span> <span m=''827160''>signal.</span> <span m=''829140''>Now</span>
  <span m=''830020''>this signal--these</span> <span m=''830270''>two</span> <span
  m=''830420''>signals</span> <span m=''831060''>are</span> <span m=''831320''>somehow</span>
  <span m=''831870''>going to have</span> <span m=''832170''>to hook</span> <span
  m=''832380''>together</span> <span m=''833800''>into</span> <span m=''834200''>a</span>
  <span m=''834710''>box,</span> <span m=''835170''>let''s</span> <span m=''835360''>call
  it</span> <span m=''835680''>this,</span> <span m=''836000''>which</span> <span
  m=''836180''>is</span> <span m=''836310''>the</span> <span m=''836620''>and-gate,</span>
  <span m=''837830''>action</span> <span m=''838230''>procedure.</span> <span m=''840320''>That''s</span>
  <span m=''840420''>the</span> <span m=''840670''>and-gate''s</span> <span m=''841180''>action</span>
  <span m=''841540''>procedure.</span> </p><p><span m=''847660''>And</span> <span
  m=''847900''>it''s</span> <span m=''848040''>going</span> <span m=''848120''>to
  produce--well, it''s going to</span> <span m=''849750''>interact</span> <span m=''850230''>with</span>
  <span m=''850720''>a</span> <span m=''856340''>signal</span> <span m=''856595''>object,</span>
  <span m=''857480''>which we</span> <span m=''857880''>call</span> <span m=''858240''>C--a
  wire object, excuse me, we call C.</span> <span m=''860650''>And</span> <span m=''860840''>then
  the--</span> <span m=''861330''>this</span> <span m=''861640''>is</span> <span m=''861740''>going</span>
  <span m=''861970''>to</span> <span m=''862150''>put</span> <span m=''862300''>out</span>
  <span m=''862520''>again,</span> <span m=''863120''>or</span> <span m=''863240''>connect</span>
  <span m=''863630''>to,</span> <span m=''864890''>another</span> <span m=''865630''>action</span>
  <span m=''865980''>procedure</span> <span m=''866370''>which</span> <span m=''866520''>is</span>
  <span m=''866620''>one</span> <span m=''866790''>associated</span> <span m=''867260''>with</span>
  <span m=''867380''>the</span> <span m=''867480''>inverter</span> <span m=''868240''>in</span>
  <span m=''868340''>the</span> <span m=''868450''>world,</span> <span m=''869940''>not.</span>
  <span m=''872860''>And</span> <span m=''873090''>I''m</span> <span m=''873180''>going</span>
  <span m=''873380''>to</span> <span m=''873640''>have</span> <span m=''874900''>another--another</span>
  <span m=''878990''>wire,</span> <span m=''879810''>which</span> <span m=''879980''>we''ll</span>
  <span m=''880100''>call</span> <span m=''880360''>D.</span> </p><p><span m=''882970''>So</span>
  <span m=''883390''>here''s</span> <span m=''883660''>my</span> <span m=''884370''>layout</span>
  <span m=''884810''>of</span> <span m=''884900''>stuff.</span> <span m=''885770''>Now</span>
  <span m=''886070''>we</span> <span m=''886260''>have to say</span> <span m=''886400''>what''s</span>
  <span m=''886630''>inside</span> <span m=''887080''>them</span> <span m=''887190''>and</span>
  <span m=''887260''>what</span> <span m=''887380''>they</span> <span m=''887510''>have</span>
  <span m=''887650''>to</span> <span m=''887750''>know</span> <span m=''888500''>to</span>
  <span m=''888960''>compute.</span> <span m=''891500''>Well,</span> <span m=''891730''>every--every</span>
  <span m=''892570''>one</span> <span m=''892720''>of</span> <span m=''892820''>these</span>
  <span m=''892930''>wires</span> <span m=''893280''>has</span> <span m=''893450''>to</span>
  <span m=''893530''>know</span> <span m=''893660''>what</span> <span m=''893900''>the</span>
  <span m=''893990''>value</span> <span m=''894410''>of</span> <span m=''894500''>the</span>
  <span m=''894580''>signal</span> <span m=''895110''>that''s</span> <span m=''895290''>on
  that</span> <span m=''895630''>wire</span> <span m=''896030''>is.</span> <span m=''897340''>So</span>
  <span m=''897550''>there''s</span> <span m=''897620''>going</span> <span m=''897690''>to</span>
  <span m=''897760''>be</span> <span m=''897840''>some</span> <span m=''898060''>variable</span>
  <span m=''898580''>inside</span> <span m=''898950''>here,</span> <span m=''899330''>we''ll</span>
  <span m=''899430''>call it</span> <span m=''899710''>signal.</span> <span m=''902670''>And</span>
  <span m=''903110''>he</span> <span m=''903250''>owns</span> <span m=''903520''>a</span>
  <span m=''903580''>value.</span> <span m=''905840''>So there</span> <span m=''905970''>must</span>
  <span m=''906150''>be</span> <span m=''906230''>some</span> <span m=''906380''>environment</span>
  <span m=''906870''>associated</span> <span m=''907370''>with</span> <span m=''907490''>this.</span>
  <span m=''908656''>And</span> <span m=''909060''>for</span> <span m=''909220''>each</span>
  <span m=''909370''>one</span> <span m=''909530''>of</span> <span m=''909650''>these,</span>
  <span m=''909770''>there</span> <span m=''909850''>must</span> <span m=''910010''>be</span>
  <span m=''910100''>an</span> <span m=''910160''>environment</span> <span m=''910550''>that</span>
  <span m=''910660''>binds</span> <span m=''911050''>signal.</span> <span m=''915400''>And</span>
  <span m=''915540''>there</span> <span m=''915610''>must</span> <span m=''915790''>be</span>
  <span m=''915860''>a</span> <span m=''915900''>signal</span> <span m=''916180''>here,</span>
  <span m=''916390''>therefore.</span> <span m=''919400''>And</span> <span m=''919680''>presumably,</span>
  <span m=''920140''>signal''s</span> <span m=''920500''>a</span> <span m=''920560''>value</span>
  <span m=''920890''>that''s</span> <span m=''921050''>either</span> <span m=''921210''>1</span>
  <span m=''921410''>or</span> <span m=''921510''>0,</span> <span m=''922920''>and</span>
  <span m=''923100''>signal.</span> </p><p><span m=''928000''>Now,</span> <span m=''929390''>we</span>
  <span m=''929590''>also</span> <span m=''929870''>have</span> <span m=''930030''>to</span>
  <span m=''930120''>have</span> <span m=''930210''>some</span> <span m=''931380''>list</span>
  <span m=''931680''>of</span> <span m=''931910''>people</span> <span m=''932240''>to</span>
  <span m=''932390''>inform</span> <span m=''933000''>if</span> <span m=''933140''>the</span>
  <span m=''933220''>signal</span> <span m=''933510''>here</span> <span m=''933700''>changes.</span>
  <span m=''936660''>We''re</span> <span m=''936810''>going to</span> <span m=''937010''>have
  to</span> <span m=''937200''>inform</span> <span m=''937460''>this.</span> <span
  m=''939300''>So</span> <span m=''939530''>I''ve</span> <span m=''939630''>got</span>
  <span m=''939850''>that</span> <span m=''940010''>list.</span> <span m=''940240''>We''ll</span>
  <span m=''940370''>call</span> <span m=''940650''>it</span> <span m=''941010''>the</span>
  <span m=''941470''>Action</span> <span m=''941880''>Procedures,</span> <span m=''943350''>AP.</span>
  <span m=''944500''>And</span> <span m=''944700''>it''s</span> <span m=''944810''>presumably</span>
  <span m=''945310''>a</span> <span m=''945370''>list.</span> <span m=''946500''>But</span>
  <span m=''946750''>the</span> <span m=''946950''>first</span> <span m=''947150''>thing</span>
  <span m=''947320''>on</span> <span m=''947510''>the</span> <span m=''947590''>list,</span>
  <span m=''947860''>in</span> <span m=''947920''>this</span> <span m=''948110''>case,</span>
  <span m=''948410''>is</span> <span m=''948560''>this</span> <span m=''948760''>guy.</span>
  <span m=''950500''>And</span> <span m=''951020''>the</span> <span m=''951250''>action</span>
  <span m=''951610''>procedures</span> <span m=''952080''>of</span> <span m=''952210''>this</span>
  <span m=''952350''>one</span> <span m=''953150''>happens to</span> <span m=''953460''>have</span>
  <span m=''953660''>some</span> <span m=''953730''>list</span> <span m=''954000''>of</span>
  <span m=''954070''>stuff.</span> <span m=''954810''>There</span> <span m=''954990''>might</span>
  <span m=''955140''>be</span> <span m=''955230''>other</span> <span m=''955400''>people</span>
  <span m=''955630''>who</span> <span m=''955860''>are</span> <span m=''956150''>sharing</span>
  <span m=''956760''>A,</span> <span m=''957200''>who</span> <span m=''957450''>are</span>
  <span m=''957510''>looking</span> <span m=''957880''>at</span> <span m=''958060''>it.</span>
  <span m=''959020''>So</span> <span m=''959340''>there</span> <span m=''959540''>might</span>
  <span m=''959740''>be</span> <span m=''959820''>other</span> <span m=''960080''>guys</span>
  <span m=''960420''>on</span> <span m=''960570''>this</span> <span m=''960770''>list,</span>
  <span m=''961070''>like</span> <span m=''961690''>somebody</span> <span m=''962060''>over</span>
  <span m=''962170''>there</span> <span m=''962340''>that</span> <span m=''962440''>we</span>
  <span m=''962540''>don''t</span> <span m=''962680''>know</span> <span m=''962830''>about.</span>
  <span m=''963630''>It''s the</span> <span m=''963790''>other</span> <span m=''963960''>guy</span>
  <span m=''964140''>attached</span> <span m=''964580''>to A.</span> </p><p><span
  m=''967200''>And</span> <span m=''967360''>the</span> <span m=''967460''>action</span>
  <span m=''967750''>procedure</span> <span m=''968120''>here</span> <span m=''968370''>also</span>
  <span m=''968700''>has to</span> <span m=''968980''>point to</span> <span m=''969340''>that,</span>
  <span m=''971010''>the</span> <span m=''971230''>list</span> <span m=''971450''>of</span>
  <span m=''971520''>action</span> <span m=''971870''>procedures.</span> <span m=''973070''>And</span>
  <span m=''973310''>of</span> <span m=''973390''>course,</span> <span m=''973730''>that</span>
  <span m=''973950''>means</span> <span m=''974170''>this</span> <span m=''974380''>one,</span>
  <span m=''975200''>its</span> <span m=''975380''>action</span> <span m=''975750''>procedures</span>
  <span m=''976770''>has</span> <span m=''977060''>to</span> <span m=''977890''>point</span>
  <span m=''978120''>up to</span> <span m=''978270''>here.</span> <span m=''978530''>This
  is the things--</span> <span m=''978770''>the</span> <span m=''979620''>people</span>
  <span m=''979880''>it</span> <span m=''980030''>has</span> <span m=''980190''>to</span>
  <span m=''980310''>inform.</span> <span m=''981770''>And</span> <span m=''981950''>this</span>
  <span m=''982160''>guy</span> <span m=''982340''>has</span> <span m=''982630''>some</span>
  <span m=''982860''>too.</span> <span m=''984280''>But</span> <span m=''984470''>I</span>
  <span m=''984560''>don''t</span> <span m=''984680''>know</span> <span m=''984760''>what</span>
  <span m=''984900''>they</span> <span m=''985040''>are</span> <span m=''985260''>because</span>
  <span m=''985360''>I</span> <span m=''985420''>didn''t</span> <span m=''985660''>draw
  it in</span> <span m=''985900''>my</span> <span m=''986060''>diagram.</span> <span
  m=''987190''>It''s the</span> <span m=''987350''>things</span> <span m=''987590''>connected</span>
  <span m=''987950''>to D.</span> </p><p><span m=''990320''>Now,</span> <span m=''991720''>it''s</span>
  <span m=''991900''>also</span> <span m=''992200''>the</span> <span m=''992310''>case</span>
  <span m=''993460''>that</span> <span m=''994060''>when</span> <span m=''994790''>the</span>
  <span m=''995050''>and-action</span> <span m=''995760''>procedure</span> <span m=''996240''>is</span>
  <span m=''996370''>awakened,</span> <span m=''996930''>saying</span> <span m=''997670''>one</span>
  <span m=''998070''>of</span> <span m=''998470''>the</span> <span m=''998590''>people</span>
  <span m=''999150''>who</span> <span m=''1001870''>know that you''ve told--one of
  the people you''ve</span> <span m=''1002090''>told</span> <span m=''1002630''>to</span>
  <span m=''1002820''>wake</span> <span m=''1003060''>you</span> <span m=''1003210''>up</span>
  <span m=''1003630''>if</span> <span m=''1003800''>their</span> <span m=''1004010''>signal</span>
  <span m=''1004340''>changes,</span> <span m=''1006960''>you</span> <span m=''1007160''>have
  to go</span> <span m=''1007420''>look</span> <span m=''1007630''>and</span> <span
  m=''1007710''>ask</span> <span m=''1007930''>them</span> <span m=''1008060''>what''s</span>
  <span m=''1008270''>their</span> <span m=''1008430''>signal</span> <span m=''1009290''>so</span>
  <span m=''1009440''>you</span> <span m=''1009580''>can</span> <span m=''1009730''>do</span>
  <span m=''1009890''>the</span> <span m=''1010050''>and,</span> <span m=''1011040''>and</span>
  <span m=''1011220''>produce</span> <span m=''1011480''>a</span> <span m=''1011540''>signal</span>
  <span m=''1011820''>for</span> <span m=''1011920''>this</span> <span m=''1012100''>one.</span>
  <span m=''1017090''>So</span> <span m=''1017250''>there</span> <span m=''1017390''>has</span>
  <span m=''1017610''>to</span> <span m=''1017720''>be,</span> <span m=''1017920''>for</span>
  <span m=''1018150''>example,</span> <span m=''1018890''>information</span> <span
  m=''1019500''>here</span> <span m=''1019760''>saying A1,</span> <span m=''1021390''>my</span>
  <span m=''1021680''>A1</span> <span m=''1022220''>is</span> <span m=''1022400''>this</span>
  <span m=''1022680''>guy,</span> <span m=''1023910''>and</span> <span m=''1024150''>my</span>
  <span m=''1024440''>A2</span> <span m=''1025589''>is</span> <span m=''1025800''>this</span>
  <span m=''1026060''>guy.</span> <span m=''1028930''>And</span> <span m=''1029170''>not</span>
  <span m=''1029380''>only</span> <span m=''1029630''>that,</span> <span m=''1031859''>when</span>
  <span m=''1032119''>I</span> <span m=''1032250''>do</span> <span m=''1032440''>my</span>
  <span m=''1032579''>and,</span> <span m=''1033520''>I''m</span> <span m=''1033690''>going</span>
  <span m=''1033800''>to</span> <span m=''1033900''>have</span> <span m=''1034040''>to</span>
  <span m=''1034170''>tell</span> <span m=''1034400''>this</span> <span m=''1034609''>guy</span>
  <span m=''1034819''>something.</span> <span m=''1036170''>So</span> <span m=''1036400''>I
  need an</span> <span m=''1036710''>output--</span> <span m=''1039904''>being</span>
  <span m=''1040700''>this</span> <span m=''1040800''>guy.</span> </p><p><span m=''1045800''>And</span>
  <span m=''1046079''>similarly,</span> <span m=''1048140''>this</span> <span m=''1048400''>guy''s</span>
  <span m=''1048680''>going</span> <span m=''1048770''>to</span> <span m=''1048850''>have</span>
  <span m=''1049040''>a thing</span> <span m=''1049390''>called</span> <span m=''1049550''>the</span>
  <span m=''1049660''>input</span> <span m=''1052220''>that</span> <span m=''1052620''>he</span>
  <span m=''1053340''>interrogates</span> <span m=''1054230''>to</span> <span m=''1054310''>find</span>
  <span m=''1054650''>out</span> <span m=''1056740''>what</span> <span m=''1057010''>the</span>
  <span m=''1057090''>value</span> <span m=''1057470''>of</span> <span m=''1057540''>the</span>
  <span m=''1057690''>signal</span> <span m=''1057920''>on</span> <span m=''1058020''>the</span>
  <span m=''1058120''>input</span> <span m=''1058370''>is,</span> <span m=''1058610''>when</span>
  <span m=''1058770''>the</span> <span m=''1058840''>signal</span> <span m=''1059090''>wakes</span>
  <span m=''1059240''>up and</span> <span m=''1059430''>says,</span> <span m=''1059520''>I''ve</span>
  <span m=''1059670''>changed,</span> <span m=''1061110''>and</span> <span m=''1061430''>sends</span>
  <span m=''1061580''>a</span> <span m=''1061700''>message</span> <span m=''1062020''>this</span>
  <span m=''1062220''>way</span> <span m=''1062420''>saying,</span> <span m=''1062980''>I''ve</span>
  <span m=''1063190''>changed.</span> <span m=''1063520''>This</span> <span m=''1063630''>guy</span>
  <span m=''1063730''>says,</span> <span m=''1064160''>OK,</span> <span m=''1064440''>what''s</span>
  <span m=''1064610''>your</span> <span m=''1064730''>value</span> <span m=''1065060''>now?</span>
  <span m=''1066900''>When he</span> <span m=''1067300''>gets</span> <span m=''1067530''>that</span>
  <span m=''1067730''>value,</span> <span m=''1068350''>then</span> <span m=''1068610''>he''s</span>
  <span m=''1068770''>going</span> <span m=''1068860''>to</span> <span m=''1068940''>have</span>
  <span m=''1069150''>to</span> <span m=''1069690''>say,</span> <span m=''1070110''>OK,</span>
  <span m=''1070840''>output</span> <span m=''1071220''>changes</span> <span m=''1071590''>this</span>
  <span m=''1071780''>guy,</span> <span m=''1074970''>changes</span> <span m=''1075380''>this</span>
  <span m=''1075600''>guy.</span> <span m=''1080600''>And</span> <span m=''1080840''>so</span>
  <span m=''1081070''>on.</span> <span m=''1082481''>And</span> <span m=''1082890''>so</span>
  <span m=''1083070''>I</span> <span m=''1083240''>have to have</span> <span m=''1083410''>at
  least</span> <span m=''1083600''>that</span> <span m=''1083780''>much</span> <span
  m=''1083950''>connected-ness.</span> </p><p><span m=''1086240''>Now,</span> <span
  m=''1086640''>let''s</span> <span m=''1086870''>go</span> <span m=''1086980''>back</span>
  <span m=''1087340''>and</span> <span m=''1087520''>look,</span> <span m=''1087720''>for</span>
  <span m=''1087860''>example,</span> <span m=''1088330''>at</span> <span m=''1088470''>the</span>
  <span m=''1088660''>and-gate.</span> <span m=''1090260''>Here</span> <span m=''1090410''>we</span>
  <span m=''1090590''>are</span> <span m=''1091090''>back</span> <span m=''1091430''>on</span>
  <span m=''1091570''>this</span> <span m=''1091660''>slide.</span> <span m=''1093670''>And</span>
  <span m=''1093810''>we</span> <span m=''1093930''>can</span> <span m=''1094100''>see</span>
  <span m=''1094300''>some</span> <span m=''1094480''>of</span> <span m=''1094530''>these</span>
  <span m=''1094730''>parts.</span> <span m=''1096040''>For</span> <span m=''1096280''>any</span>
  <span m=''1096490''>particular</span> <span m=''1096980''>and-gate,</span> <span
  m=''1097420''>there</span> <span m=''1097590''>is</span> <span m=''1097730''>an</span>
  <span m=''1097920''>A1,</span> <span m=''1098180''>there is</span> <span m=''1098400''>an</span>
  <span m=''1098470''>A2,</span> <span m=''1098780''>and</span> <span m=''1098860''>the</span>
  <span m=''1098960''>output.</span> <span m=''1101030''>And</span> <span m=''1101240''>those
  are, those are an environment that was created at the--those</span> <span m=''1107140''>produce</span>
  <span m=''1107580''>a</span> <span m=''1107660''>frame</span> <span m=''1108450''>at</span>
  <span m=''1108640''>the</span> <span m=''1108730''>time</span> <span m=''1109030''>and-gate</span>
  <span m=''1109650''>was</span> <span m=''1110720''>called,</span> <span m=''1113350''>a</span>
  <span m=''1113480''>frame</span> <span m=''1113850''>where</span> <span m=''1114040''>A1,</span>
  <span m=''1114420''>A2,</span> <span m=''1114880''>and</span> <span m=''1115060''>output</span>
  <span m=''1116670''>are--have</span> <span m=''1116860''>as</span> <span m=''1117030''>their</span>
  <span m=''1117200''>values,</span> <span m=''1118290''>they''re</span> <span m=''1118370''>bound</span>
  <span m=''1118810''>to</span> <span m=''1119630''>the</span> <span m=''1120980''>wires</span>
  <span m=''1121700''>which, they are--which were</span> <span m=''1123600''>passed</span>
  <span m=''1123960''>in.</span> <span m=''1126240''>In</span> <span m=''1126520''>that</span>
  <span m=''1126710''>environment,</span> <span m=''1127680''>I</span> <span m=''1127890''>constructed</span>
  <span m=''1129100''>a</span> <span m=''1129270''>procedure--</span> <span m=''1130890''>this</span>
  <span m=''1131260''>one</span> <span m=''1132970''>right</span> <span m=''1133260''>there.</span>
  <span m=''1134590''>And-action</span> <span m=''1135320''>procedure</span> <span
  m=''1135720''>was</span> <span m=''1135910''>constructed</span> <span m=''1136550''>in</span>
  <span m=''1136640''>that</span> <span m=''1136810''>environment.</span> <span m=''1137780''>That</span>
  <span m=''1138600''>was</span> <span m=''1138720''>the</span> <span m=''1138950''>result</span>
  <span m=''1139260''>of</span> <span m=''1139360''>evaluating</span> <span m=''1139820''>a</span>
  <span m=''1139880''>lambda</span> <span m=''1140190''>expression.</span> </p><p><span
  m=''1141620''>So</span> <span m=''1141910''>it</span> <span m=''1142770''>hangs</span>
  <span m=''1143170''>onto</span> <span m=''1143830''>the</span> <span m=''1144050''>frame</span>
  <span m=''1144440''>where</span> <span m=''1144610''>these</span> <span m=''1144900''>were</span>
  <span m=''1145000''>defined.</span> <span m=''1147620''>Local--part</span> <span
  m=''1147840''>of</span> <span m=''1147920''>its</span> <span m=''1148150''>local</span>
  <span m=''1148440''>state</span> <span m=''1148850''>is</span> <span m=''1149120''>that.</span>
  <span m=''1151700''>The</span> <span m=''1151890''>and-action</span> <span m=''1152530''>procedure,</span>
  <span m=''1152900''>therefore,</span> <span m=''1153240''>has</span> <span m=''1153680''>access</span>
  <span m=''1154180''>to</span> <span m=''1154590''>A1,</span> <span m=''1155000''>A2,</span>
  <span m=''1155400''>and</span> <span m=''1155490''>output</span> <span m=''1156070''>as</span>
  <span m=''1156340''>we</span> <span m=''1156490''>see</span> <span m=''1156720''>here.</span>
  <span m=''1157310''>A1,</span> <span m=''1158310''>A2,</span> <span m=''1159070''>and</span>
  <span m=''1159260''>output.</span> </p><p><span m=''1162360''>Now,</span> <span
  m=''1162510''>we</span> <span m=''1162610''>haven''t</span> <span m=''1162780''>looked</span>
  <span m=''1162960''>inside</span> <span m=''1163250''>of a</span> <span m=''1163290''>wire</span>
  <span m=''1163740''>yet.</span> <span m=''1166030''>That''s</span> <span m=''1166240''>all</span>
  <span m=''1166400''>that</span> <span m=''1166470''>remains.</span> <span m=''1169030''>Let''s</span>
  <span m=''1169300''>look</span> <span m=''1169390''>at</span> <span m=''1169480''>a</span>
  <span m=''1169520''>wire.</span> <span m=''1173520''>Like</span> <span m=''1173700''>the</span>
  <span m=''1173810''>overhead,</span> <span m=''1175680''>very</span> <span m=''1175890''>good.</span>
  <span m=''1179500''>Well,</span> <span m=''1179775''>the wire,</span> <span m=''1180050''>again,</span>
  <span m=''1180330''>is</span> <span m=''1180790''>a, is a</span> <span m=''1180940''>somewhat</span>
  <span m=''1181570''>complicated</span> <span m=''1182210''>mess.</span> <span m=''1183090''>Ooh,</span>
  <span m=''1184100''>wrong</span> <span m=''1184300''>one.</span> <span m=''1186840''>It''s
  a</span> <span m=''1187110''>big</span> <span m=''1187420''>complicated</span> <span
  m=''1187685''>mess,</span> <span m=''1188190''>like</span> <span m=''1188400''>that.</span>
  <span m=''1189780''>But</span> <span m=''1190200''>let''s</span> <span m=''1190400''>look</span>
  <span m=''1190580''>at</span> <span m=''1190640''>it</span> <span m=''1190750''>in</span>
  <span m=''1190830''>detail</span> <span m=''1192070''>and</span> <span m=''1192310''>see</span>
  <span m=''1192400''>what''s</span> <span m=''1192560''>going</span> <span m=''1192830''>on.</span>
  </p><p><span m=''1194720''>Well,</span> <span m=''1194840''>the</span> <span m=''1194910''>wire</span>
  <span m=''1195540''>is</span> <span m=''1195670''>one</span> <span m=''1195840''>of</span>
  <span m=''1195930''>these.</span> <span m=''1197760''>And</span> <span m=''1197920''>it
  has</span> <span m=''1198100''>to</span> <span m=''1198280''>have</span> <span m=''1200170''>two</span>
  <span m=''1200400''>things</span> <span m=''1201480''>that</span> <span m=''1201830''>are</span>
  <span m=''1201920''>part</span> <span m=''1202220''>of</span> <span m=''1202320''>it,</span>
  <span m=''1202660''>that</span> <span m=''1202880''>it''s</span> <span m=''1203060''>state.</span>
  <span m=''1205010''>One</span> <span m=''1205220''>of</span> <span m=''1205410''>them</span>
  <span m=''1205830''>is</span> <span m=''1206110''>the</span> <span m=''1206220''>signal</span>
  <span m=''1206600''>we</span> <span m=''1206760''>see</span> <span m=''1206960''>here.</span>
  <span m=''1207390''>In</span> <span m=''1207810''>other words,</span> <span m=''1208020''>when
  we</span> <span m=''1208230''>call</span> <span m=''1208580''>make-wire</span> <span
  m=''1209150''>to</span> <span m=''1209270''>make</span> <span m=''1209450''>a</span>
  <span m=''1209500''>wire,</span> <span m=''1210450''>then</span> <span m=''1210670''>the</span>
  <span m=''1210840''>first</span> <span m=''1211000''>thing</span> <span m=''1211150''>we</span>
  <span m=''1211270''>do</span> <span m=''1211500''>is</span> <span m=''1211620''>we</span>
  <span m=''1211750''>create</span> <span m=''1212180''>some</span> <span m=''1212370''>variables</span>
  <span m=''1214970''>which</span> <span m=''1215300''>are</span> <span m=''1215470''>the</span>
  <span m=''1215590''>signal</span> <span m=''1217160''>and</span> <span m=''1217420''>the</span>
  <span m=''1217540''>action</span> <span m=''1217960''>procedures</span> <span m=''1218530''>for</span>
  <span m=''1218650''>this</span> <span m=''1218820''>wire.</span> <span m=''1222042''>And</span>
  <span m=''1222510''>in</span> <span m=''1222690''>that</span> <span m=''1222880''>context,</span>
  <span m=''1223770''>we</span> <span m=''1223920''>define</span> <span m=''1224480''>various</span>
  <span m=''1226470''>functions--or procedures, excuse me, procedures.</span> </p><p><span
  m=''1227840''>One</span> <span m=''1228090''>of</span> <span m=''1228180''>them</span>
  <span m=''1228270''>is</span> <span m=''1228390''>called</span> <span m=''1228850''>set-my-signal</span>
  <span m=''1230200''>to</span> <span m=''1230320''>a</span> <span m=''1230430''>new</span>
  <span m=''1230590''>value.</span> <span m=''1232850''>And</span> <span m=''1233000''>what</span>
  <span m=''1233170''>that</span> <span m=''1233430''>does</span> <span m=''1234480''>is</span>
  <span m=''1235970''>takes</span> <span m=''1236390''>a</span> <span m=''1236450''>new</span>
  <span m=''1236590''>value</span> <span m=''1237020''>in.</span> <span m=''1237930''>If</span>
  <span m=''1238130''>that''s</span> <span m=''1238420''>equal</span> <span m=''1238650''>to</span>
  <span m=''1238730''>my</span> <span m=''1238860''>current</span> <span m=''1239150''>value</span>
  <span m=''1239450''>of my</span> <span m=''1239620''>signal,</span> <span m=''1239930''>I''m</span>
  <span m=''1240020''>done.</span> <span m=''1240360''>Otherwise,</span> <span m=''1241270''>I</span>
  <span m=''1241400''>set</span> <span m=''1241610''>the</span> <span m=''1241680''>signal</span>
  <span m=''1241920''>to</span> <span m=''1242030''>the</span> <span m=''1242100''>new</span>
  <span m=''1242240''>value</span> <span m=''1242770''>and</span> <span m=''1243000''>call</span>
  <span m=''1243320''>each of</span> <span m=''1243460''>the</span> <span m=''1243610''>action</span>
  <span m=''1243950''>procedures</span> <span m=''1246150''>that</span> <span m=''1246640''>I''ve</span>
  <span m=''1246940''>been, that I''ve been--what''s the right word?--</span> <span
  m=''1251700''>introduced</span> <span m=''1252280''>to.</span> <span m=''1254630''>I</span>
  <span m=''1254730''>get</span> <span m=''1254840''>introduced</span> <span m=''1255380''>when</span>
  <span m=''1256770''>the</span> <span m=''1257790''>and-gate</span> <span m=''1260070''>was</span>
  <span m=''1260790''>applied</span> <span m=''1261190''>to</span> <span m=''1261280''>me.</span>
  <span m=''1264130''>I</span> <span m=''1264300''>add</span> <span m=''1264500''>action</span>
  <span m=''1264820''>procedure</span> <span m=''1265150''>at</span> <span m=''1265220''>the</span>
  <span m=''1265290''>bottom.</span> </p><p><span m=''1267410''>Also,</span> <span
  m=''1268550''>I</span> <span m=''1268680''>have</span> <span m=''1268820''>to</span>
  <span m=''1268920''>define</span> <span m=''1269260''>a</span> <span m=''1269320''>way
  of</span> <span m=''1269620''>accepting an</span> <span m=''1270020''>action</span>
  <span m=''1270440''>procedure--</span> <span m=''1270870''>which</span> <span m=''1271030''>is</span>
  <span m=''1271090''>what</span> <span m=''1271210''>you</span> <span m=''1271330''>see</span>
  <span m=''1271500''>here---</span> <span m=''1272780''>which</span> <span m=''1273500''>increments</span>
  <span m=''1274080''>my</span> <span m=''1274220''>action</span> <span m=''1274560''>procedures</span>
  <span m=''1275620''>using</span> <span m=''1275880''>set</span> <span m=''1278050''>to</span>
  <span m=''1278460''>the</span> <span m=''1278530''>result</span> <span m=''1278940''>of</span>
  <span m=''1279030''>CONSing</span> <span m=''1279450''>up</span> <span m=''1279640''>a</span>
  <span m=''1279720''>new</span> <span m=''1280860''>process--a procedure,</span>
  <span m=''1281750''>which</span> <span m=''1281950''>is</span> <span m=''1282060''>passed</span>
  <span m=''1282340''>to</span> <span m=''1282420''>me,</span> <span m=''1282890''>on</span>
  <span m=''1283100''>to my actions</span> <span m=''1283570''>procedures</span> <span
  m=''1284020''>list.</span> <span m=''1285480''>And</span> <span m=''1285640''>for</span>
  <span m=''1285760''>technical</span> <span m=''1286210''>reasons,</span> <span m=''1286510''>I</span>
  <span m=''1286580''>have</span> <span m=''1286650''>to</span> <span m=''1286720''>call</span>
  <span m=''1286930''>that</span> <span m=''1287000''>procedure</span> <span m=''1287390''>one.</span>
  <span m=''1287780''>So</span> <span m=''1287930''>I''m not</span> <span m=''1288000''>going
  to</span> <span m=''1288150''>tell</span> <span m=''1288260''>you</span> <span m=''1288390''>anything</span>
  <span m=''1288640''>about</span> <span m=''1288890''>that,</span> <span m=''1289340''>that</span>
  <span m=''1289540''>has</span> <span m=''1289660''>to</span> <span m=''1289760''>do</span>
  <span m=''1289910''>with</span> <span m=''1291060''>event-driven</span> <span m=''1291630''>simulations</span>
  <span m=''1292240''>and</span> <span m=''1292330''>getting them</span> <span m=''1292610''>started,</span>
  <span m=''1294810''>which</span> <span m=''1294990''>takes</span> <span m=''1295230''>a</span>
  <span m=''1295280''>little</span> <span m=''1295450''>bit</span> <span m=''1295540''>of</span>
  <span m=''1295620''>thinking.</span> </p><p><span m=''1296950''>And</span> <span
  m=''1297190''>finally,</span> <span m=''1297660''>I''m</span> <span m=''1297790''>going
  to</span> <span m=''1297940''>define</span> <span m=''1298200''>a thing</span> <span
  m=''1298380''>called</span> <span m=''1298620''>the</span> <span m=''1298690''>dispatcher,</span>
  <span m=''1300040''>which</span> <span m=''1300260''>is</span> <span m=''1300340''>a</span>
  <span m=''1300710''>way</span> <span m=''1301050''>of</span> <span m=''1301510''>passing</span>
  <span m=''1301910''>a</span> <span m=''1301960''>message</span> <span m=''1302820''>to</span>
  <span m=''1302950''>a</span> <span m=''1303090''>wire,</span> <span m=''1305390''>which</span>
  <span m=''1305630''>is</span> <span m=''1305700''>going</span> <span m=''1305840''>to</span>
  <span m=''1306200''>be</span> <span m=''1306310''>used</span> <span m=''1306520''>to</span>
  <span m=''1306610''>extract</span> <span m=''1307170''>from</span> <span m=''1307360''>it</span>
  <span m=''1307630''>various</span> <span m=''1308030''>information,</span> <span
  m=''1309130''>like</span> <span m=''1310000''>what</span> <span m=''1310200''>is</span>
  <span m=''1310300''>the</span> <span m=''1310400''>current</span> <span m=''1310720''>signal</span>
  <span m=''1311060''>value?</span> <span m=''1313820''>What</span> <span m=''1314120''>is</span>
  <span m=''1314230''>the</span> <span m=''1314320''>method</span> <span m=''1314660''>of</span>
  <span m=''1314740''>setting</span> <span m=''1315070''>your</span> <span m=''1315250''>signal?</span>
  <span m=''1317180''>I</span> <span m=''1317260''>want</span> <span m=''1317360''>to</span>
  <span m=''1317460''>get</span> <span m=''1317690''>that</span> <span m=''1317840''>out</span>
  <span m=''1317990''>of</span> <span m=''1318140''>it.</span> <span m=''1320100''>How</span>
  <span m=''1320320''>do</span> <span m=''1320400''>I--how do I</span> <span m=''1321340''>add</span>
  <span m=''1321490''>another</span> <span m=''1321790''>action</span> <span m=''1322100''>procedure?</span>
  <span m=''1325510''>And</span> <span m=''1325700''>I''m going to</span> <span m=''1325800''>return</span>
  <span m=''1326260''>that</span> <span m=''1326450''>dispatch,</span> <span m=''1328050''>that</span>
  <span m=''1328280''>procedure</span> <span m=''1328760''>as</span> <span m=''1328860''>a</span>
  <span m=''1328920''>value.</span> </p><p><span m=''1329940''>So</span> <span m=''1330210''>the</span>
  <span m=''1330310''>wire</span> <span m=''1330685''>that</span> <span m=''1331060''>I''ve</span>
  <span m=''1331250''>constructed</span> <span m=''1332010''>is</span> <span m=''1332170''>a</span>
  <span m=''1332220''>message</span> <span m=''1332610''>accepting</span> <span m=''1333050''>object</span>
  <span m=''1334260''>which</span> <span m=''1334430''>accepts</span> <span m=''1334650''>a</span>
  <span m=''1334740''>message</span> <span m=''1335130''>like, like</span> <span m=''1336490''>what''s</span>
  <span m=''1336710''>your</span> <span m=''1336860''>method</span> <span m=''1337160''>of</span>
  <span m=''1337230''>adding</span> <span m=''1337500''>action</span> <span m=''1337820''>procedures?</span>
  <span m=''1339790''>In fact,</span> <span m=''1340170''>it''ll</span> <span m=''1340350''>give</span>
  <span m=''1340430''>me</span> <span m=''1340520''>a</span> <span m=''1340570''>procedure,</span>
  <span m=''1341600''>which</span> <span m=''1341890''>is</span> <span m=''1342120''>the
  add</span> <span m=''1342270''>action</span> <span m=''1342770''>procedure,</span>
  <span m=''1343090''>which</span> <span m=''1343240''>I</span> <span m=''1343320''>can</span>
  <span m=''1343440''>then</span> <span m=''1343560''>apply</span> <span m=''1345490''>to
  an</span> <span m=''1345670''>action</span> <span m=''1346020''>procedure</span>
  <span m=''1347050''>to</span> <span m=''1347190''>create</span> <span m=''1347530''>another</span>
  <span m=''1347770''>action</span> <span m=''1348050''>procedure</span> <span m=''1348420''>in</span>
  <span m=''1348520''>the</span> <span m=''1348620''>wire.</span> <span m=''1351620''>So</span>
  <span m=''1351790''>that''s</span> <span m=''1352110''>a</span> <span m=''1352170''>permission.</span>
  <span m=''1352820''>So</span> <span m=''1353130''>it''s</span> <span m=''1353440''>given</span>
  <span m=''1353640''>me</span> <span m=''1353790''>permission</span> <span m=''1354520''>to</span>
  <span m=''1354690''>change</span> <span m=''1355010''>your</span> <span m=''1355100''>action</span>
  <span m=''1355470''>procedures.</span> </p><p><span m=''1357450''>And</span> <span
  m=''1357870''>in</span> <span m=''1358040''>fact,</span> <span m=''1358480''>you</span>
  <span m=''1358650''>can</span> <span m=''1358810''>see</span> <span m=''1358990''>that</span>
  <span m=''1359620''>over</span> <span m=''1359870''>here.</span> <span m=''1361710''>Next</span>
  <span m=''1361910''>slide.</span> <span m=''1363278''>Ah.</span> <span m=''1367760''>This</span>
  <span m=''1367950''>is</span> <span m=''1368060''>nothing</span> <span m=''1368360''>very</span>
  <span m=''1368570''>interesting.</span> <span m=''1369120''>The</span> <span m=''1369220''>call</span>
  <span m=''1369580''>each of</span> <span m=''1369690''>the</span> <span m=''1369810''>action</span>
  <span m=''1370150''>procedures</span> <span m=''1370900''>is</span> <span m=''1371090''>just</span>
  <span m=''1371370''>a</span> <span m=''1371860''>CDRing</span> <span m=''1372040''>down</span>
  <span m=''1372200''>a</span> <span m=''1372260''>list.</span> <span m=''1372535''>And</span>
  <span m=''1372810''>I''m</span> <span m=''1372980''>not</span> <span m=''1373160''>going</span>
  <span m=''1373220''>to</span> <span m=''1373280''>even</span> <span m=''1373500''>talk</span>
  <span m=''1373730''>about</span> <span m=''1373930''>that</span> <span m=''1374100''>anymore.</span>
  <span m=''1374990''>We''re</span> <span m=''1375200''>too</span> <span m=''1375380''>advanced</span>
  <span m=''1375790''>for</span> <span m=''1375900''>that.</span> <span m=''1377560''>However,</span>
  <span m=''1378870''>if</span> <span m=''1379070''>I</span> <span m=''1379160''>want</span>
  <span m=''1379290''>to</span> <span m=''1379410''>get</span> <span m=''1379610''>a</span>
  <span m=''1379650''>signal</span> <span m=''1380070''>from</span> <span m=''1380240''>a</span>
  <span m=''1380280''>wire,</span> <span m=''1380970''>I</span> <span m=''1381230''>ask</span>
  <span m=''1381460''>the</span> <span m=''1381550''>wire--</span> <span m=''1382250''>which</span>
  <span m=''1382430''>is,</span> <span m=''1382510''>what</span> <span m=''1382650''>is</span>
  <span m=''1382740''>the</span> <span m=''1382810''>wire?</span> <span m=''1383090''>The</span>
  <span m=''1383170''>wire is</span> <span m=''1383550''>the</span> <span m=''1383630''>dispatch</span>
  <span m=''1384080''>returned</span> <span m=''1384460''>by</span> <span m=''1384560''>creating</span>
  <span m=''1384940''>the</span> <span m=''1385010''>wire.</span> <span m=''1385860''>It''s
  a</span> <span m=''1386030''>procedure.</span> <span m=''1386830''>I</span> <span
  m=''1386960''>call</span> <span m=''1387290''>that</span> <span m=''1387490''>dispatch</span>
  <span m=''1390010''>on</span> <span m=''1391070''>the</span> <span m=''1391310''>message</span>
  <span m=''1391650''>get-signal.</span> <span m=''1392590''>And</span> <span m=''1392970''>what
  I</span> <span m=''1393380''>should expect</span> <span m=''1393710''>to</span>
  <span m=''1393770''>get</span> <span m=''1394340''>is</span> <span m=''1394490''>a</span>
  <span m=''1394530''>method</span> <span m=''1394770''>of</span> <span m=''1394830''>getting</span>
  <span m=''1395020''>a</span> <span m=''1395070''>signal.</span> <span m=''1396900''>Or</span>
  <span m=''1397060''>actually,</span> <span m=''1397380''>I get</span> <span m=''1397560''>the</span>
  <span m=''1397640''>signal.</span> </p><p><span m=''1399220''>If</span> <span m=''1399400''>I</span>
  <span m=''1399480''>want</span> <span m=''1399620''>to</span> <span m=''1399760''>set</span>
  <span m=''1400010''>a</span> <span m=''1400060''>signal,</span> <span m=''1402750''>I</span>
  <span m=''1402970''>want</span> <span m=''1403090''>to</span> <span m=''1403200''>change</span>
  <span m=''1403500''>a</span> <span m=''1403540''>signal,</span> <span m=''1404540''>then</span>
  <span m=''1405800''>what</span> <span m=''1405920''>I''m</span> <span m=''1406080''>going</span>
  <span m=''1406280''>to</span> <span m=''1406340''>do</span> <span m=''1406940''>is</span>
  <span m=''1407110''>take</span> <span m=''1407300''>a</span> <span m=''1407350''>wire</span>
  <span m=''1407850''>as</span> <span m=''1407990''>an</span> <span m=''1408070''>argument</span>
  <span m=''1408450''>and a</span> <span m=''1408680''>new</span> <span m=''1408810''>value</span>
  <span m=''1409140''>for</span> <span m=''1409220''>the</span> <span m=''1409300''>signal,</span>
  <span m=''1409740''>I''m</span> <span m=''1410050''>going</span> <span m=''1410170''>to</span>
  <span m=''1410360''>ask</span> <span m=''1410610''>the</span> <span m=''1410700''>wire</span>
  <span m=''1411000''>for</span> <span m=''1411120''>permission</span> <span m=''1411600''>to</span>
  <span m=''1411700''>set</span> <span m=''1411960''>its</span> <span m=''1411980''>signal</span>
  <span m=''1412830''>and</span> <span m=''1413080''>use</span> <span m=''1413340''>that</span>
  <span m=''1413550''>permission,</span> <span m=''1415172''>which</span> <span m=''1415660''>is</span>
  <span m=''1415820''>a</span> <span m=''1415890''>procedure,</span> <span m=''1416780''>on</span>
  <span m=''1416980''>the</span> <span m=''1417050''>new</span> <span m=''1417190''>value.</span>
  <span m=''1418700''>And</span> <span m=''1418860''>if</span> <span m=''1418940''>we</span>
  <span m=''1419190''>go</span> <span m=''1419330''>back</span> <span m=''1419570''>to</span>
  <span m=''1419650''>the</span> <span m=''1419770''>overhead</span> <span m=''1420190''>here,</span>
  <span m=''1422750''>thank</span> <span m=''1423010''>you,</span> <span m=''1423972''>if
  we</span> <span m=''1424340''>go</span> <span m=''1424500''>back</span> <span m=''1424740''>to</span>
  <span m=''1424830''>the</span> <span m=''1424940''>overhead</span> <span m=''1425330''>here,</span>
  <span m=''1425980''>we</span> <span m=''1426160''>see</span> <span m=''1426330''>that
  the method--</span> <span m=''1426880''>if</span> <span m=''1427060''>I</span> <span
  m=''1427170''>ask</span> <span m=''1427440''>for</span> <span m=''1427540''>the</span>
  <span m=''1427660''>method</span> <span m=''1427930''>of</span> <span m=''1428000''>setting</span>
  <span m=''1428300''>the</span> <span m=''1428370''>signal,</span> <span m=''1429330''>that''s</span>
  <span m=''1429720''>over</span> <span m=''1429970''>here,</span> <span m=''1432030''>it''s</span>
  <span m=''1432420''>set-my-signal,</span> <span m=''1433270''>a</span> <span m=''1433320''>procedure</span>
  <span m=''1433680''>that''s</span> <span m=''1433960''>defined</span> <span m=''1434620''>inside</span>
  <span m=''1435150''>the</span> <span m=''1435230''>wire,</span> <span m=''1436270''>which</span>
  <span m=''1436520''>if</span> <span m=''1436620''>we</span> <span m=''1436750''>look</span>
  <span m=''1436940''>over</span> <span m=''1437170''>here</span> <span m=''1438770''>is</span>
  <span m=''1438920''>the</span> <span m=''1439040''>thing</span> <span m=''1439270''>that</span>
  <span m=''1439450''>says</span> <span m=''1440470''>set</span> <span m=''1440940''>my</span>
  <span m=''1441170''>internal</span> <span m=''1441570''>value</span> <span m=''1441950''>called</span>
  <span m=''1442180''>the</span> <span m=''1442240''>signal,</span> <span m=''1442780''>my</span>
  <span m=''1442930''>internal</span> <span m=''1443220''>variable,</span> <span m=''1444490''>which</span>
  <span m=''1444680''>is</span> <span m=''1444780''>the</span> <span m=''1444870''>signal,</span>
  <span m=''1447520''>to</span> <span m=''1447700''>the</span> <span m=''1447810''>new</span>
  <span m=''1447970''>value,</span> <span m=''1448640''>which</span> <span m=''1448800''>is</span>
  <span m=''1448940''>passed</span> <span m=''1449240''>to</span> <span m=''1449320''>me</span>
  <span m=''1449420''>as</span> <span m=''1449530''>an</span> <span m=''1449590''>argument,</span>
  <span m=''1450760''>and</span> <span m=''1451160''>then call each</span> <span m=''1451630''>of
  the</span> <span m=''1451720''>action</span> <span m=''1452030''>procedures</span>
  <span m=''1452380''>waking</span> <span m=''1452680''>them</span> <span m=''1452810''>up.</span>
  <span m=''1456340''>Very</span> <span m=''1456590''>simple.</span> </p><p><span
  m=''1459400''>Going</span> <span m=''1459640''>back</span> <span m=''1459900''>to</span>
  <span m=''1459990''>that</span> <span m=''1460230''>slide,</span> <span m=''1462500''>we</span>
  <span m=''1462690''>also</span> <span m=''1462940''>have</span> <span m=''1463280''>the</span>
  <span m=''1463550''>one</span> <span m=''1463800''>last</span> <span m=''1464110''>thing--</span>
  <span m=''1464310''>which</span> <span m=''1464960''>I</span> <span m=''1465140''>suppose</span>
  <span m=''1465440''>now</span> <span m=''1465600''>you</span> <span m=''1465720''>can</span>
  <span m=''1466100''>easily</span> <span m=''1466400''>work</span> <span m=''1466600''>out</span>
  <span m=''1466780''>for</span> <span m=''1466850''>yourself--</span> <span m=''1467810''>is</span>
  <span m=''1467970''>the</span> <span m=''1468030''>way</span> <span m=''1468180''>you</span>
  <span m=''1468280''>add an</span> <span m=''1468530''>action.</span> <span m=''1470100''>You</span>
  <span m=''1470610''>take</span> <span m=''1470690''>a</span> <span m=''1470750''>wire--a
  wire</span> <span m=''1473695''>and</span> <span m=''1474060''>an</span> <span m=''1474280''>action</span>
  <span m=''1474650''>procedure.</span> <span m=''1476470''>And</span> <span m=''1477000''>I</span>
  <span m=''1477180''>ask</span> <span m=''1477510''>the</span> <span m=''1477590''>wire</span>
  <span m=''1477960''>for</span> <span m=''1478070''>permission</span> <span m=''1478335''>to
  add</span> <span m=''1478600''>an</span> <span m=''1478780''>action.</span> <span
  m=''1480050''>Getting</span> <span m=''1480370''>that</span> <span m=''1480645''>permission,</span>
  <span m=''1480920''>I use</span> <span m=''1481170''>that</span> <span m=''1481360''>permission</span>
  <span m=''1482780''>to</span> <span m=''1482900''>give</span> <span m=''1483070''>it</span>
  <span m=''1483130''>an</span> <span m=''1483210''>action</span> <span m=''1483550''>procedure.</span>
  <span m=''1485020''>So</span> <span m=''1485500''>that''s</span> <span m=''1486110''>a</span>
  <span m=''1486230''>real</span> <span m=''1486540''>object.</span> </p><p><span
  m=''1488570''>There''s</span> <span m=''1488740''>a</span> <span m=''1488810''>few</span>
  <span m=''1488990''>more</span> <span m=''1489180''>details</span> <span m=''1489670''>about</span>
  <span m=''1489980''>this.</span> <span m=''1492460''>For</span> <span m=''1492690''>example,</span>
  <span m=''1494430''>how</span> <span m=''1494700''>am</span> <span m=''1494810''>I</span>
  <span m=''1494880''>going</span> <span m=''1495200''>to</span> <span m=''1497540''>control</span>
  <span m=''1497990''>this</span> <span m=''1498200''>thing?</span> <span m=''1498390''>How</span>
  <span m=''1498620''>do I</span> <span m=''1498690''>do</span> <span m=''1498830''>these</span>
  <span m=''1499020''>delays?</span> <span m=''1501290''>Let''s</span> <span m=''1501470''>look</span>
  <span m=''1501600''>at</span> <span m=''1501720''>that</span> <span m=''1501960''>for</span>
  <span m=''1502050''>a</span> <span m=''1502130''>second.</span> <span m=''1505275''>The</span>
  <span m=''1505620''>next</span> <span m=''1507420''>one</span> <span m=''1507540''>here.</span>
  <span m=''1508360''>Let''s</span> <span m=''1508610''>see.</span> <span m=''1509570''>We</span>
  <span m=''1509740''>know</span> <span m=''1510560''>when</span> <span m=''1510700''>we</span>
  <span m=''1510860''>looked</span> <span m=''1511090''>at</span> <span m=''1511260''>the</span>
  <span m=''1511770''>and-gate</span> <span m=''1513170''>or</span> <span m=''1513320''>the</span>
  <span m=''1513440''>not-gate</span> <span m=''1515150''>that</span> <span m=''1515450''>when</span>
  <span m=''1515760''>a</span> <span m=''1515900''>signal</span> <span m=''1516190''>changed</span>
  <span m=''1516460''>on</span> <span m=''1516550''>the</span> <span m=''1516640''>input,</span>
  <span m=''1517280''>there</span> <span m=''1517430''>was</span> <span m=''1517580''>a</span>
  <span m=''1517660''>delay.</span> <span m=''1518770''>And</span> <span m=''1518980''>then</span>
  <span m=''1519140''>it</span> <span m=''1519250''>was</span> <span m=''1519440''>going</span>
  <span m=''1519700''>to</span> <span m=''1520360''>call</span> <span m=''1520570''>the</span>
  <span m=''1520650''>procedure,</span> <span m=''1521640''>which was</span> <span
  m=''1521900''>going</span> <span m=''1522060''>to</span> <span m=''1522130''>change</span>
  <span m=''1522460''>the</span> <span m=''1522590''>output.</span> </p><p><span m=''1526040''>Well,</span>
  <span m=''1526820''>how</span> <span m=''1527010''>are</span> <span m=''1527120''>we
  going to</span> <span m=''1527250''>do</span> <span m=''1527520''>this?</span> <span
  m=''1528120''>We''re</span> <span m=''1528270''>going</span> <span m=''1528330''>to</span>
  <span m=''1528390''>make</span> <span m=''1528600''>up</span> <span m=''1528710''>some</span>
  <span m=''1529200''>mechanism,</span> <span m=''1529960''>a</span> <span m=''1530240''>fairly</span>
  <span m=''1530600''>complicated</span> <span m=''1531150''>mechanism</span> <span
  m=''1531560''>at</span> <span m=''1531650''>that,</span> <span m=''1532330''>which
  we''re</span> <span m=''1532480''>going</span> <span m=''1532610''>to</span> <span
  m=''1532740''>have to be</span> <span m=''1532890''>very</span> <span m=''1533110''>careful</span>
  <span m=''1533430''>about.</span> <span m=''1534720''>But</span> <span m=''1535130''>after</span>
  <span m=''1535470''>a</span> <span m=''1535510''>delay,</span> <span m=''1536220''>we''re</span>
  <span m=''1536360''>going</span> <span m=''1536440''>to</span> <span m=''1536520''>do</span>
  <span m=''1536750''>an</span> <span m=''1536820''>action.</span> <span m=''1537390''>A</span>
  <span m=''1537500''>delay</span> <span m=''1537750''>is a</span> <span m=''1537930''>number,</span>
  <span m=''1538220''>and an</span> <span m=''1538350''>action is</span> <span m=''1538700''>a</span>
  <span m=''1538750''>procedure.</span> <span m=''1540590''>What</span> <span m=''1540810''>that''s</span>
  <span m=''1541050''>going</span> <span m=''1541180''>to</span> <span m=''1541320''>be</span>
  <span m=''1541450''>is</span> <span m=''1541560''>they''re</span> <span m=''1541660''>going</span>
  <span m=''1541740''>to</span> <span m=''1541820''>have</span> <span m=''1541930''>a</span>
  <span m=''1541970''>special</span> <span m=''1542430''>structure</span> <span m=''1542920''>called</span>
  <span m=''1543180''>an</span> <span m=''1543260''>agenda,</span> <span m=''1545600''>which</span>
  <span m=''1545840''>is</span> <span m=''1545900''>a</span> <span m=''1546000''>thing</span>
  <span m=''1546290''>that</span> <span m=''1547120''>organizes</span> <span m=''1547760''>time</span>
  <span m=''1548150''>and</span> <span m=''1548250''>actions.</span> <span m=''1549510''>And</span>
  <span m=''1549720''>we''re</span> <span m=''1549930''>going to</span> <span m=''1550020''>see
  that</span> <span m=''1550200''>in</span> <span m=''1550240''>a</span> <span m=''1550280''>while.</span>
  <span m=''1550880''>I</span> <span m=''1551010''>don''t</span> <span m=''1551140''>want</span>
  <span m=''1551230''>to</span> <span m=''1551320''>get</span> <span m=''1551450''>into</span>
  <span m=''1551630''>that</span> <span m=''1551900''>right</span> <span m=''1552170''>now.</span>
  </p><p><span m=''1553070''>But</span> <span m=''1553280''>the</span> <span m=''1553450''>agenda</span>
  <span m=''1554260''>has</span> <span m=''1554690''>a</span> <span m=''1554790''>moment</span>
  <span m=''1555260''>at</span> <span m=''1555510''>which--at which</span> <span m=''1557280''>something</span>
  <span m=''1557650''>happens.</span> <span m=''1559130''>We''re</span> <span m=''1559270''>setting</span>
  <span m=''1559640''>up</span> <span m=''1560340''>for</span> <span m=''1560560''>later</span>
  <span m=''1561560''>at</span> <span m=''1561790''>some</span> <span m=''1562030''>moment,</span>
  <span m=''1562520''>which</span> <span m=''1562700''>is</span> <span m=''1562800''>the</span>
  <span m=''1562890''>sum</span> <span m=''1563120''>of</span> <span m=''1563220''>the</span>
  <span m=''1563310''>time,</span> <span m=''1563880''>which</span> <span m=''1564110''>is
  the</span> <span m=''1564180''>delay</span> <span m=''1564580''>time</span> <span
  m=''1564810''>plus</span> <span m=''1565020''>the</span> <span m=''1565120''>current</span>
  <span m=''1565400''>time,</span> <span m=''1565680''>which the</span> <span m=''1565840''>agenda</span>
  <span m=''1566090''>thinks</span> <span m=''1566530''>is</span> <span m=''1566690''>now.</span>
  <span m=''1568460''>We''re</span> <span m=''1568660''>going</span> <span m=''1569160''>to</span>
  <span m=''1569300''>set</span> <span m=''1569470''>up</span> <span m=''1569570''>to</span>
  <span m=''1569660''>do</span> <span m=''1569830''>this</span> <span m=''1570030''>action,</span>
  <span m=''1571080''>and</span> <span m=''1571250''>add</span> <span m=''1571490''>that</span>
  <span m=''1571750''>to</span> <span m=''1571840''>the</span> <span m=''1571970''>agenda.</span>
  </p><p><span m=''1575280''>And</span> <span m=''1575420''>the</span> <span m=''1575570''>way</span>
  <span m=''1575750''>this</span> <span m=''1575910''>machine</span> <span m=''1576260''>will</span>
  <span m=''1576380''>now</span> <span m=''1576600''>run</span> <span m=''1577320''>is</span>
  <span m=''1577480''>very</span> <span m=''1577690''>simple.</span> <span m=''1578660''>We</span>
  <span m=''1578810''>have</span> <span m=''1578930''>a</span> <span m=''1578970''>thing</span>
  <span m=''1579120''>called</span> <span m=''1579370''>propagate,</span> <span m=''1580030''>which</span>
  <span m=''1580250''>is</span> <span m=''1580480''>the</span> <span m=''1580620''>way</span>
  <span m=''1580800''>things</span> <span m=''1581050''>run.</span> <span m=''1582710''>If</span>
  <span m=''1582840''>the</span> <span m=''1582970''>agenda</span> <span m=''1583370''>is</span>
  <span m=''1583550''>empty,</span> <span m=''1584000''>we''re</span> <span m=''1584170''>done--if</span>
  <span m=''1584590''>there''s</span> <span m=''1584900''>nothing</span> <span m=''1585150''>more</span>
  <span m=''1585290''>to</span> <span m=''1585340''>be</span> <span m=''1585440''>done.</span>
  <span m=''1587440''>Otherwise,</span> <span m=''1589790''>we''re</span> <span m=''1589970''>going</span>
  <span m=''1590050''>to</span> <span m=''1590130''>take</span> <span m=''1590290''>the</span>
  <span m=''1590360''>first</span> <span m=''1590650''>item</span> <span m=''1590880''>off</span>
  <span m=''1590990''>the</span> <span m=''1591110''>agenda,</span> <span m=''1591690''>and</span>
  <span m=''1591870''>that''s</span> <span m=''1592020''>a</span> <span m=''1592080''>procedure</span>
  <span m=''1592540''>of</span> <span m=''1592620''>no</span> <span m=''1592810''>arguments.</span>
  <span m=''1594200''>So</span> <span m=''1594400''>that</span> <span m=''1594560''>we''re
  going to</span> <span m=''1594690''>see</span> <span m=''1594830''>extra</span>
  <span m=''1595090''>parentheses</span> <span m=''1595610''>here.</span> <span m=''1596030''>We</span>
  <span m=''1596280''>call</span> <span m=''1596580''>that</span> <span m=''1596800''>on</span>
  <span m=''1597020''>no</span> <span m=''1597230''>arguments.</span> <span m=''1599190''>That</span>
  <span m=''1599420''>takes</span> <span m=''1599620''>the</span> <span m=''1599740''>action.</span>
  <span m=''1602200''>Then</span> <span m=''1602470''>we</span> <span m=''1602590''>remove</span>
  <span m=''1602960''>that</span> <span m=''1603160''>first</span> <span m=''1603400''>item</span>
  <span m=''1603580''>from</span> <span m=''1603690''>the</span> <span m=''1603800''>agenda,</span>
  <span m=''1604630''>and</span> <span m=''1604800''>we</span> <span m=''1604900''>go</span>
  <span m=''1605050''>around</span> <span m=''1605250''>the</span> <span m=''1605320''>propagation</span>
  <span m=''1605625''>loop.</span> <span m=''1608395''>So</span> <span m=''1608890''>that''s</span>
  <span m=''1609210''>the</span> <span m=''1609330''>overall</span> <span m=''1609760''>structure</span>
  <span m=''1610180''>of</span> <span m=''1610330''>this</span> <span m=''1610480''>thing.</span>
  </p><p><span m=''1613380''>Now,</span> <span m=''1613540''>there''s</span> <span
  m=''1613730''>a, a</span> <span m=''1614310''>few</span> <span m=''1614540''>other</span>
  <span m=''1614730''>things</span> <span m=''1615000''>we</span> <span m=''1615160''>can</span>
  <span m=''1615520''>look</span> <span m=''1615810''>at.</span> <span m=''1617430''>And</span>
  <span m=''1617560''>then</span> <span m=''1617680''>we''re</span> <span m=''1617770''>going</span>
  <span m=''1617860''>to</span> <span m=''1617950''>look</span> <span m=''1618110''>into</span>
  <span m=''1618370''>the</span> <span m=''1618510''>agenda</span> <span m=''1619140''>a</span>
  <span m=''1619160''>little</span> <span m=''1619340''>while</span> <span m=''1619650''>from</span>
  <span m=''1619790''>now.</span> <span m=''1620410''>Now</span> <span m=''1620770''>the</span>
  <span m=''1620890''>overhead</span> <span m=''1621210''>again.</span> <span m=''1622800''>Well,</span>
  <span m=''1623500''>in</span> <span m=''1623610''>order</span> <span m=''1623740''>to</span>
  <span m=''1623810''>set</span> <span m=''1624010''>this</span> <span m=''1624170''>thing</span>
  <span m=''1624360''>going,</span> <span m=''1624700''>I just</span> <span m=''1624850''>want
  to</span> <span m=''1624980''>show</span> <span m=''1625160''>you</span> <span m=''1625330''>some</span>
  <span m=''1625510''>behavior</span> <span m=''1626000''>out</span> <span m=''1626120''>of</span>
  <span m=''1626240''>this</span> <span m=''1626810''>simulator.</span> <span m=''1627410''>By
  the</span> <span m=''1627910''>way,</span> <span m=''1628220''>you</span> <span
  m=''1628360''>may</span> <span m=''1628510''>think</span> <span m=''1628700''>this</span>
  <span m=''1628780''>simulator</span> <span m=''1629210''>is</span> <span m=''1629300''>very</span>
  <span m=''1629520''>simple,</span> <span m=''1630430''>and</span> <span m=''1630610''>probably</span>
  <span m=''1630940''>too</span> <span m=''1631080''>simple</span> <span m=''1631360''>to</span>
  <span m=''1631430''>be</span> <span m=''1631520''>useful.</span> <span m=''1632370''>The</span>
  <span m=''1632770''>fact</span> <span m=''1633060''>of</span> <span m=''1633120''>the</span>
  <span m=''1633190''>matter</span> <span m=''1633520''>is</span> <span m=''1633900''>that
  this</span> <span m=''1634250''>simulator</span> <span m=''1634680''>has</span>
  <span m=''1634860''>been</span> <span m=''1635020''>used</span> <span m=''1635730''>to</span>
  <span m=''1635840''>manufacture</span> <span m=''1636145''>a</span> <span m=''1636450''>fairly</span>
  <span m=''1636720''>large</span> <span m=''1636950''>computer.</span> <span m=''1638680''>So</span>
  <span m=''1638920''>this</span> <span m=''1639080''>is</span> <span m=''1639120''>a</span>
  <span m=''1639200''>real</span> <span m=''1639480''>live</span> <span m=''1639960''>example.</span>
  </p><p><span m=''1642360''>Actually,</span> <span m=''1642640''>not</span> <span
  m=''1642860''>exactly</span> <span m=''1643420''>this</span> <span m=''1643520''>simulator,</span>
  <span m=''1644010''>because</span> <span m=''1644500''>I''ll</span> <span m=''1644680''>tell</span>
  <span m=''1644790''>you</span> <span m=''1644900''>the</span> <span m=''1645000''>difference.</span>
  <span m=''1645560''>The</span> <span m=''1645990''>difference</span> <span m=''1646440''>is</span>
  <span m=''1646820''>that</span> <span m=''1646980''>there</span> <span m=''1647080''>were</span>
  <span m=''1647220''>many</span> <span m=''1647500''>more</span> <span m=''1647740''>different</span>
  <span m=''1647990''>kinds</span> <span m=''1648180''>of</span> <span m=''1648240''>primitives.</span>
  <span m=''1649820''>There''s</span> <span m=''1650090''>not</span> <span m=''1650290''>just</span>
  <span m=''1650440''>the</span> <span m=''1650510''>word</span> <span m=''1650680''>inverter</span>
  <span m=''1651450''>or</span> <span m=''1651590''>and-gate.</span> <span m=''1653200''>There</span>
  <span m=''1653340''>were</span> <span m=''1653380''>things</span> <span m=''1653690''>like</span>
  <span m=''1654340''>edge-triggered,</span> <span m=''1656670''>flip-flops,</span>
  <span m=''1657590''>and</span> <span m=''1659240''>latches,</span> <span m=''1660690''>transparent</span>
  <span m=''1661300''>latches,</span> <span m=''1662060''>and</span> <span m=''1662810''>adders,</span>
  <span m=''1663650''>and</span> <span m=''1663780''>things</span> <span m=''1663980''>like</span>
  <span m=''1664190''>that.</span> <span m=''1665170''>And</span> <span m=''1665380''>the</span>
  <span m=''1665420''>difficulty</span> <span m=''1666320''>with</span> <span m=''1666620''>that</span>
  <span m=''1667470''>is</span> <span m=''1667610''>that</span> <span m=''1667750''>there''s</span>
  <span m=''1667960''>pages</span> <span m=''1668410''>and</span> <span m=''1668510''>pages</span>
  <span m=''1669010''>of</span> <span m=''1669130''>the</span> <span m=''1669560''>definitions</span>
  <span m=''1670100''>of</span> <span m=''1670210''>all</span> <span m=''1670330''>these</span>
  <span m=''1670490''>primitives</span> <span m=''1671260''>with</span> <span m=''1671410''>numbers</span>
  <span m=''1671760''>like</span> <span m=''1672000''>LS04.</span> <span m=''1674690''>And</span>
  <span m=''1674930''>then</span> <span m=''1675190''>there''s</span> <span m=''1675490''>many</span>
  <span m=''1675720''>more</span> <span m=''1675880''>parameters</span> <span m=''1676370''>for</span>
  <span m=''1676480''>them.</span> <span m=''1676740''>It''s not</span> <span m=''1676880''>just</span>
  <span m=''1677350''>one</span> <span m=''1677550''>delay.</span> <span m=''1678480''>There''s</span>
  <span m=''1678580''>things</span> <span m=''1678810''>like</span> <span m=''1678980''>set</span>
  <span m=''1679150''>up</span> <span m=''1679270''>times</span> <span m=''1679650''>and</span>
  <span m=''1679730''>hold</span> <span m=''1680020''>times</span> <span m=''1680320''>and</span>
  <span m=''1680400''>all</span> <span m=''1680570''>that.</span> <span m=''1681220''>But</span>
  <span m=''1681440''>with</span> <span m=''1681550''>the</span> <span m=''1681640''>exception</span>
  <span m=''1681900''>of</span> <span m=''1682160''>that</span> <span m=''1682400''>part</span>
  <span m=''1682580''>of</span> <span m=''1682620''>the</span> <span m=''1682700''>complexity,</span>
  <span m=''1683610''>the</span> <span m=''1683990''>structure</span> <span m=''1684540''>of</span>
  <span m=''1684610''>the</span> <span m=''1684680''>simulator</span> <span m=''1686410''>that</span>
  <span m=''1686580''>we</span> <span m=''1686740''>use</span> <span m=''1686990''>for</span>
  <span m=''1687240''>building</span> <span m=''1687500''>a</span> <span m=''1687580''>real</span>
  <span m=''1687790''>computer,</span> <span m=''1689150''>that</span> <span m=''1689280''>works</span>
  <span m=''1691110''>is</span> <span m=''1691380''>exactly</span> <span m=''1692160''>what</span>
  <span m=''1692290''>you''re</span> <span m=''1692420''>seeing</span> <span m=''1692650''>here.</span>
  </p><p><span m=''1695110''>Well</span> <span m=''1695270''>in</span> <span m=''1695350''>any</span>
  <span m=''1695540''>case,</span> <span m=''1696580''>what</span> <span m=''1696780''>we</span>
  <span m=''1696930''>have</span> <span m=''1697170''>here</span> <span m=''1697770''>is</span>
  <span m=''1698200''>a</span> <span m=''1698350''>few</span> <span m=''1698550''>simple</span>
  <span m=''1698900''>things.</span> <span m=''1699270''>Like,</span> <span m=''1699510''>there''s</span>
  <span m=''1700240''>inverter</span> <span m=''1700820''>delays</span> <span m=''1700990''>being</span>
  <span m=''1701190''>set</span> <span m=''1701370''>up</span> <span m=''1701480''>and</span>
  <span m=''1701580''>making</span> <span m=''1701860''>a</span> <span m=''1701900''>new</span>
  <span m=''1702030''>agenda.</span> <span m=''1703030''>And</span> <span m=''1703170''>then</span>
  <span m=''1704110''>we</span> <span m=''1704260''>can</span> <span m=''1704410''>make</span>
  <span m=''1704620''>some</span> <span m=''1704940''>inputs.</span> <span m=''1706470''>There''s</span>
  <span m=''1706680''>input-1,</span> <span m=''1707140''>input-2,</span> <span m=''1707560''>a</span>
  <span m=''1707690''>sum and</span> <span m=''1708060''>a carry,</span> <span m=''1708380''>which
  are</span> <span m=''1708600''>wires.</span> <span m=''1709460''>I''m going</span>
  <span m=''1709570''>to</span> <span m=''1709720''>put</span> <span m=''1709840''>a</span>
  <span m=''1709880''>special</span> <span m=''1710280''>kind</span> <span m=''1710510''>of</span>
  <span m=''1710600''>object</span> <span m=''1710980''>called</span> <span m=''1711210''>a</span>
  <span m=''1711260''>probe</span> <span m=''1712560''>onto, onto</span> <span m=''1713810''>some</span>
  <span m=''1714070''>of</span> <span m=''1714120''>the</span> <span m=''1714190''>wires,</span>
  <span m=''1715030''>onto</span> <span m=''1715260''>sum and</span> <span m=''1715580''>onto</span>
  <span m=''1715790''>carry.</span> <span m=''1717810''>A probe</span> <span m=''1718260''>is</span>
  <span m=''1719320''>a, can</span> <span m=''1719390''>object</span> <span m=''1719770''>that
  has</span> <span m=''1719950''>the</span> <span m=''1720030''>property</span> <span
  m=''1720570''>that</span> <span m=''1720960''>when</span> <span m=''1721100''>you</span>
  <span m=''1721590''>change</span> <span m=''1722160''>a</span> <span m=''1722470''>wire</span>
  <span m=''1722730''>it''s</span> <span m=''1722990''>attached</span> <span m=''1723350''>to,</span>
  <span m=''1723750''>it</span> <span m=''1723930''>types</span> <span m=''1724060''>out
  a</span> <span m=''1724300''>message.</span> <span m=''1726120''>It''s</span> <span
  m=''1726190''>an</span> <span m=''1726280''>easy</span> <span m=''1726460''>thing</span>
  <span m=''1726610''>to</span> <span m=''1726690''>do.</span> </p><p><span m=''1727970''>And</span>
  <span m=''1728440''>then</span> <span m=''1728740''>once</span> <span m=''1728940''>we</span>
  <span m=''1729130''>have</span> <span m=''1729330''>that,</span> <span m=''1729610''>of</span>
  <span m=''1729750''>course,</span> <span m=''1730080''>the</span> <span m=''1730260''>way</span>
  <span m=''1730480''>you</span> <span m=''1730580''>put</span> <span m=''1730720''>the</span>
  <span m=''1730790''>probe</span> <span m=''1731060''>on,</span> <span m=''1731410''>the</span>
  <span m=''1731490''>first</span> <span m=''1731710''>thing</span> <span m=''1731850''>it</span>
  <span m=''1731920''>does,</span> <span m=''1732180''>it says,</span> <span m=''1732510''>the</span>
  <span m=''1732760''>current</span> <span m=''1733040''>value</span> <span m=''1733410''>of</span>
  <span m=''1733480''>the</span> <span m=''1733560''>sum</span> <span m=''1734110''>at</span>
  <span m=''1734310''>time</span> <span m=''1734600''>0</span> <span m=''1735410''>is</span>
  <span m=''1735610''>0</span> <span m=''1737660''>because</span> <span m=''1737830''>I</span>
  <span m=''1737890''>just</span> <span m=''1738080''>noticed</span> <span m=''1738400''>it.</span>
  <span m=''1739400''>And</span> <span m=''1739690''>the</span> <span m=''1739770''>value</span>
  <span m=''1740330''>of</span> <span m=''1740440''>the</span> <span m=''1740550''>carry</span>
  <span m=''1741550''>at</span> <span m=''1741860''>time</span> <span m=''1742130''>0,</span>
  <span m=''1742490''>this is</span> <span m=''1742640''>the</span> <span m=''1742750''>time,</span>
  <span m=''1744220''>is</span> <span m=''1744360''>0.</span> <span m=''1745556''>And</span>
  <span m=''1745940''>then</span> <span m=''1746390''>we</span> <span m=''1746500''>go</span>
  <span m=''1746680''>off</span> <span m=''1748080''>and</span> <span m=''1748250''>we</span>
  <span m=''1748360''>build</span> <span m=''1748670''>some</span> <span m=''1748750''>structure.</span>
  <span m=''1749620''>Like,</span> <span m=''1749820''>we</span> <span m=''1749940''>can</span>
  <span m=''1750080''>build</span> <span m=''1750290''>a</span> <span m=''1750330''>structure</span>
  <span m=''1750710''>here</span> <span m=''1750880''>that</span> <span m=''1751040''>says</span>
  <span m=''1754040''>you</span> <span m=''1754200''>have a</span> <span m=''1754440''>half-adder</span>
  <span m=''1756310''>on</span> <span m=''1756480''>input-1,</span> <span m=''1756970''>input-2,</span>
  <span m=''1757410''>sum, and</span> <span m=''1757750''>carry.</span> <span m=''1758420''>And
  we''re</span> <span m=''1758640''>going to</span> <span m=''1758730''>set</span>
  <span m=''1758960''>the</span> <span m=''1759050''>signal</span> <span m=''1759380''>on</span>
  <span m=''1759500''>input-1</span> <span m=''1759990''>to</span> <span m=''1760080''>1.</span>
  <span m=''1760420''>We do</span> <span m=''1760900''>some</span> <span m=''1761010''>propagation.</span>
  <span m=''1761880''>At</span> <span m=''1762130''>time</span> <span m=''1762480''>8,</span>
  <span m=''1763960''>which</span> <span m=''1764160''>you</span> <span m=''1764240''>could</span>
  <span m=''1764380''>see</span> <span m=''1764530''>going</span> <span m=''1764790''>through</span>
  <span m=''1764980''>this</span> <span m=''1765160''>thing</span> <span m=''1765290''>if</span>
  <span m=''1765380''>you</span> <span m=''1765480''>wanted</span> <span m=''1765800''>to,</span>
  <span m=''1766400''>the</span> <span m=''1766740''>new</span> <span m=''1766900''>value</span>
  <span m=''1767350''>of</span> <span m=''1767780''>sum</span> <span m=''1768300''>became</span>
  <span m=''1768720''>1.</span> <span m=''1769520''>And</span> <span m=''1769710''>the
  thing</span> <span m=''1769920''>says</span> <span m=''1770020''>I''m</span> <span
  m=''1770120''>done.</span> <span m=''1771150''>That</span> <span m=''1771320''>wasn''t</span>
  <span m=''1771490''>very</span> <span m=''1771730''>interesting.</span> </p><p><span
  m=''1772630''>But</span> <span m=''1772870''>we can</span> <span m=''1773030''>send</span>
  <span m=''1773190''>it</span> <span m=''1773290''>some</span> <span m=''1773330''>more</span>
  <span m=''1773510''>signals.</span> <span m=''1774150''>Like,</span> <span m=''1774250''>we</span>
  <span m=''1774380''>set-signal</span> <span m=''1774830''>on</span> <span m=''1774940''>input-2</span>
  <span m=''1775710''>to</span> <span m=''1776150''>be</span> <span m=''1776280''>one.</span>
  <span m=''1776590''>And</span> <span m=''1776900''>at</span> <span m=''1777060''>that</span>
  <span m=''1777230''>time if</span> <span m=''1777430''>we</span> <span m=''1777550''>propagate,</span>
  <span m=''1778390''>then it</span> <span m=''1778700''>carried</span> <span m=''1779240''>at</span>
  <span m=''1779430''>11,</span> <span m=''1779950''>the</span> <span m=''1780250''>carry</span>
  <span m=''1780590''>becomes</span> <span m=''1780950''>1,</span> <span m=''1781590''>and
  at</span> <span m=''1781870''>16,</span> <span m=''1782550''>the</span> <span m=''1782800''>sum''s</span>
  <span m=''1783150''>new</span> <span m=''1783280''>value</span> <span m=''1783570''>becomes</span>
  <span m=''1783870''>0.</span> <span m=''1785040''>And</span> <span m=''1785460''>you</span>
  <span m=''1785750''>might</span> <span m=''1785960''>want</span> <span m=''1786070''>to</span>
  <span m=''1786170''>work</span> <span m=''1786400''>out</span> <span m=''1786610''>that,</span>
  <span m=''1786750''>if</span> <span m=''1786840''>you</span> <span m=''1786970''>like,</span>
  <span m=''1787680''>about</span> <span m=''1787870''>the</span> <span m=''1788060''>digital</span>
  <span m=''1788370''>circuitry.</span> <span m=''1788990''>It''s</span> <span m=''1789220''>true,
  and</span> <span m=''1789530''>it</span> <span m=''1789680''>works.</span> <span
  m=''1790620''>And</span> <span m=''1790770''>it''s</span> <span m=''1790860''>not</span>
  <span m=''1791060''>very</span> <span m=''1791250''>interesting.</span> <span m=''1791535''>But</span>
  <span m=''1791820''>that''s</span> <span m=''1792100''>the</span> <span m=''1792170''>kind</span>
  <span m=''1792350''>of</span> <span m=''1792410''>behavior</span> <span m=''1793240''>we</span>
  <span m=''1793330''>get</span> <span m=''1793510''>out</span> <span m=''1793630''>of</span>
  <span m=''1793790''>this</span> <span m=''1793950''>thing.</span> </p><p><span m=''1801830''>So</span>
  <span m=''1802070''>what</span> <span m=''1802200''>I''ve</span> <span m=''1802300''>shown</span>
  <span m=''1802580''>you</span> <span m=''1802730''>right</span> <span m=''1802970''>now</span>
  <span m=''1803490''>is</span> <span m=''1803820''>a</span> <span m=''1804070''>large-scale</span>
  <span m=''1804850''>picture,</span> <span m=''1806550''>how</span> <span m=''1806920''>you,</span>
  <span m=''1807030''>at</span> <span m=''1807260''>a bigger,</span> <span m=''1807740''>big
  scale,</span> <span m=''1808810''>you</span> <span m=''1808970''>implement</span>
  <span m=''1810170''>an</span> <span m=''1810360''>event-driven</span> <span m=''1810900''>simulation</span>
  <span m=''1811480''>of</span> <span m=''1811560''>some</span> <span m=''1811770''>sort.</span>
  <span m=''1812952''>And</span> <span m=''1813370''>how</span> <span m=''1813600''>you</span>
  <span m=''1813730''>might</span> <span m=''1813900''>organize</span> <span m=''1814390''>it</span>
  <span m=''1814660''>to</span> <span m=''1815010''>have</span> <span m=''1815140''>nice</span>
  <span m=''1815400''>hierarchical</span> <span m=''1816010''>structure</span> <span
  m=''1817030''>allowing</span> <span m=''1817450''>you</span> <span m=''1817590''>to</span>
  <span m=''1817720''>build</span> <span m=''1818520''>abstract</span> <span m=''1819320''>boxes</span>
  <span m=''1820020''>that</span> <span m=''1820120''>you</span> <span m=''1820220''>can</span>
  <span m=''1820400''>instantiate.</span> <span m=''1821225''>But I</span> <span m=''1821620''>haven''t</span>
  <span m=''1821980''>told</span> <span m=''1822210''>you</span> <span m=''1822300''>any
  of the</span> <span m=''1822440''>details</span> <span m=''1823090''>about</span>
  <span m=''1823370''>how</span> <span m=''1823470''>this</span> <span m=''1823630''>agenda</span>
  <span m=''1824020''>and</span> <span m=''1824120''>things</span> <span m=''1824330''>like</span>
  <span m=''1824530''>that</span> <span m=''1824760''>work.</span> <span m=''1825780''>That</span>
  <span m=''1825980''>we''ll</span> <span m=''1826090''>do</span> <span m=''1826220''>next.</span>
  <span m=''1828630''>And</span> <span m=''1828740''>that''s</span> <span m=''1828920''>going</span>
  <span m=''1829000''>to</span> <span m=''1829080''>involve</span> <span m=''1830590''>change</span>
  <span m=''1831010''>and</span> <span m=''1831100''>mutation</span> <span m=''1831620''>of</span>
  <span m=''1831690''>data</span> <span m=''1832040''>and</span> <span m=''1832230''>things</span>
  <span m=''1832460''>like</span> <span m=''1832670''>that.</span> <span m=''1834310''>Are
  there any</span> <span m=''1834580''>questions</span> <span m=''1834990''>now,</span>
  <span m=''1835200''>before</span> <span m=''1835510''>I go</span> <span m=''1835650''>on?</span>
  <span m=''1847160''>Thank</span> <span m=''1847420''>you.</span> <span m=''1847550''>Let''s</span>
  <span m=''1847740''>take</span> <span m=''1847880''>a</span> <span m=''1847930''>break.</span>
  </p><p><span m=''1888940''>Well,</span> <span m=''1892600''>we''ve</span> <span
  m=''1892800''>been</span> <span m=''1892920''>making</span> <span m=''1893290''>a</span>
  <span m=''1894200''>simulation.</span> <span m=''1895060''>And</span> <span m=''1895370''>the</span>
  <span m=''1895640''>simulation</span> <span m=''1896250''>is</span> <span m=''1896370''>an</span>
  <span m=''1896480''>event-driven</span> <span m=''1897080''>simulation</span> <span
  m=''1898150''>where</span> <span m=''1899360''>the</span> <span m=''1899830''>objects</span>
  <span m=''1900300''>in</span> <span m=''1900370''>the</span> <span m=''1900440''>world</span>
  <span m=''1901340''>are</span> <span m=''1901520''>the</span> <span m=''1901660''>objects</span>
  <span m=''1902040''>in</span> <span m=''1902110''>the</span> <span m=''1902180''>computer.</span>
  <span m=''1903920''>And</span> <span m=''1904300''>the</span> <span m=''1904440''>changes</span>
  <span m=''1904860''>of</span> <span m=''1904940''>state</span> <span m=''1905250''>that</span>
  <span m=''1905350''>are</span> <span m=''1905410''>happening</span> <span m=''1905680''>in</span>
  <span m=''1905740''>the</span> <span m=''1906000''>world</span> <span m=''1906510''>in</span>
  <span m=''1906700''>time</span> <span m=''1907920''>are</span> <span m=''1908770''>organized</span>
  <span m=''1909400''>to</span> <span m=''1909490''>be</span> <span m=''1909710''>time</span>
  <span m=''1910150''>in</span> <span m=''1910300''>the</span> <span m=''1910380''>computer,</span>
  <span m=''1912940''>so</span> <span m=''1913140''>that</span> <span m=''1913300''>if</span>
  <span m=''1913520''>something</span> <span m=''1914300''>happens</span> <span m=''1914620''>after</span>
  <span m=''1914900''>something</span> <span m=''1915210''>else</span> <span m=''1915400''>in</span>
  <span m=''1915470''>the</span> <span m=''1915540''>world,</span> <span m=''1916430''>then</span>
  <span m=''1916630''>we</span> <span m=''1916730''>have</span> <span m=''1916930''>it</span>
  <span m=''1917150''>happen</span> <span m=''1917500''>after, after</span> <span
  m=''1919220''>the</span> <span m=''1919350''>corresponding</span> <span m=''1920000''>events</span>
  <span m=''1920910''>happen</span> <span m=''1921180''>in the</span> <span m=''1921240''>same</span>
  <span m=''1921500''>order</span> <span m=''1921720''>in</span> <span m=''1921790''>the</span>
  <span m=''1921860''>computer.</span> <span m=''1924420''>That''s</span> <span m=''1924680''>where</span>
  <span m=''1924770''>we</span> <span m=''1924870''>have</span> <span m=''1925000''>assignments,</span>
  <span m=''1925680''>when</span> <span m=''1926070''>we make</span> <span m=''1926470''>that</span>
  <span m=''1926610''>alignment.</span> </p><p><span m=''1928220''>Right</span> <span
  m=''1928470''>now</span> <span m=''1928590''>I</span> <span m=''1928650''>want</span>
  <span m=''1928780''>to</span> <span m=''1928900''>show</span> <span m=''1929140''>you</span>
  <span m=''1929790''>a</span> <span m=''1929890''>way</span> <span m=''1930050''>of</span>
  <span m=''1930130''>organizing</span> <span m=''1930830''>time,</span> <span m=''1931545''>which</span>
  <span m=''1931860''>is</span> <span m=''1932130''>an</span> <span m=''1932200''>agenda</span>
  <span m=''1933120''>or</span> <span m=''1933230''>priority</span> <span m=''1933740''>queue,</span>
  <span m=''1933990''>it''s</span> <span m=''1934110''>sometimes</span> <span m=''1934530''>called.</span>
  <span m=''1936040''>We''ll do some--we''ll</span> <span m=''1936290''>do</span>
  <span m=''1937190''>a</span> <span m=''1937250''>little</span> <span m=''1937470''>bit</span>
  <span m=''1937860''>of just</span> <span m=''1937990''>understanding</span> <span
  m=''1938650''>what</span> <span m=''1938800''>are</span> <span m=''1938940''>the</span>
  <span m=''1939010''>things</span> <span m=''1939230''>we</span> <span m=''1939380''>need</span>
  <span m=''1939530''>to</span> <span m=''1939680''>be</span> <span m=''1939790''>able</span>
  <span m=''1939890''>to</span> <span m=''1939980''>do to</span> <span m=''1940210''>make</span>
  <span m=''1940390''>agendas.</span> <span m=''1948330''>And so we''re going to have--and</span>
  <span m=''1948520''>so</span> <span m=''1949810''>right</span> <span m=''1950000''>now</span>
  <span m=''1950210''>over here,</span> <span m=''1950410''>I''m going</span> <span
  m=''1950470''>to</span> <span m=''1950540''>write</span> <span m=''1950740''>down</span>
  <span m=''1950860''>a</span> <span m=''1950950''>bunch</span> <span m=''1951180''>of</span>
  <span m=''1951440''>primitive</span> <span m=''1951750''>operations</span> <span
  m=''1952720''>for</span> <span m=''1952860''>manipulating</span> <span m=''1953380''>agendas.</span>
  <span m=''1955960''>I''m</span> <span m=''1956120''>not</span> <span m=''1956300''>going</span>
  <span m=''1956460''>to</span> <span m=''1956570''>show</span> <span m=''1956730''>you</span>
  <span m=''1956880''>the</span> <span m=''1957170''>code</span> <span m=''1957590''>for</span>
  <span m=''1957770''>them</span> <span m=''1958080''>because</span> <span m=''1958530''>they''re</span>
  <span m=''1958650''>all</span> <span m=''1958850''>very</span> <span m=''1959140''>simple,</span>
  <span m=''1960310''>and</span> <span m=''1960880''>you''ve</span> <span m=''1961030''>got</span>
  <span m=''1961300''>listings</span> <span m=''1961700''>of</span> <span m=''1961810''>all</span>
  <span m=''1961950''>that</span> <span m=''1962190''>anyway.</span> </p><p><span
  m=''1963680''>So</span> <span m=''1964000''>what do we</span> <span m=''1964140''>have?</span>
  <span m=''1964380''>We</span> <span m=''1964500''>have</span> <span m=''1964620''>things</span>
  <span m=''1964850''>like</span> <span m=''1965050''>make-agenda</span> <span m=''1971760''>which</span>
  <span m=''1972070''>produces</span> <span m=''1972770''>a</span> <span m=''1972880''>new</span>
  <span m=''1973060''>agenda.</span> <span m=''1979860''>We can ask--we</span> <span
  m=''1980090''>get</span> <span m=''1980300''>the</span> <span m=''1980380''>current-time</span>
  <span m=''1980920''>of</span> <span m=''1981020''>an</span> <span m=''1981100''>agenda,</span>
  <span m=''1990950''>which</span> <span m=''1991170''>gives</span> <span m=''1991380''>me</span>
  <span m=''1991510''>a</span> <span m=''1991590''>number,</span> <span m=''1992250''>a</span>
  <span m=''1992350''>time.</span> <span m=''1996990''>We can get--we</span> <span
  m=''1997160''>can</span> <span m=''1998420''>ask</span> <span m=''1998700''>whether</span>
  <span m=''1998920''>an</span> <span m=''1999190''>agenda</span> <span m=''1999340''>is</span>
  <span m=''1999510''>empty,</span> <span m=''2000650''>empty-agenda.</span> <span
  m=''2010200''>And</span> <span m=''2010320''>that</span> <span m=''2010510''>produces</span>
  <span m=''2011330''>either</span> <span m=''2011590''>a</span> <span m=''2011670''>true</span>
  <span m=''2011870''>or a</span> <span m=''2012080''>false.</span> </p><p><span m=''2022590''>We</span>
  <span m=''2022940''>can</span> <span m=''2023150''>add</span> <span m=''2023410''>an</span>
  <span m=''2023700''>object</span> <span m=''2024050''>to</span> <span m=''2024150''>an</span>
  <span m=''2024230''>agenda.</span> <span m=''2032710''>Actually,</span> <span m=''2032990''>what
  we</span> <span m=''2033210''>add</span> <span m=''2033370''>to</span> <span m=''2033460''>an
  agenda</span> <span m=''2034790''>is</span> <span m=''2034920''>an</span> <span
  m=''2035010''>operation--an action</span> <span m=''2035450''>to</span> <span m=''2035540''>be</span>
  <span m=''2035670''>done.</span> <span m=''2036910''>And</span> <span m=''2037090''>that</span>
  <span m=''2037300''>takes</span> <span m=''2037580''>a</span> <span m=''2037650''>time,</span>
  <span m=''2039550''>the</span> <span m=''2039850''>action</span> <span m=''2040180''>itself,</span>
  <span m=''2042630''>and</span> <span m=''2043160''>the</span> <span m=''2043240''>agenda</span>
  <span m=''2043560''>I</span> <span m=''2043650''>want to add it</span> <span m=''2044150''>to.</span>
  <span m=''2047850''>That</span> <span m=''2048010''>inserts</span> <span m=''2048460''>it</span>
  <span m=''2048580''>in</span> <span m=''2048699''>the</span> <span m=''2048820''>appropriate</span>
  <span m=''2049280''>place</span> <span m=''2049540''>in the</span> <span m=''2049679''>agenda.</span>
  <span m=''2050719''>I</span> <span m=''2050889''>can</span> <span m=''2051020''>get</span>
  <span m=''2051179''>the</span> <span m=''2051280''>first</span> <span m=''2051600''>item</span>
  <span m=''2051870''>off</span> <span m=''2051980''>an</span> <span m=''2052090''>agenda,</span>
  <span m=''2054270''>the</span> <span m=''2054380''>first</span> <span m=''2054610''>thing</span>
  <span m=''2054750''>I</span> <span m=''2054850''>have</span> <span m=''2054949''>to</span>
  <span m=''2055050''>do,</span> <span m=''2061960''>which</span> <span m=''2062159''>is</span>
  <span m=''2062250''>going</span> <span m=''2062449''>to</span> <span m=''2062500''>give</span>
  <span m=''2062679''>me</span> <span m=''2062800''>an</span> <span m=''2062889''>action.</span>
  <span m=''2066085''>And</span> <span m=''2066580''>I</span> <span m=''2066800''>can</span>
  <span m=''2066940''>remove</span> <span m=''2067320''>the</span> <span m=''2067400''>first</span>
  <span m=''2067670''>item</span> <span m=''2067889''>from</span> <span m=''2068000''>an</span>
  <span m=''2068110''>agenda.</span> <span m=''2069540''>That''s what I</span> <span
  m=''2069650''>have to be</span> <span m=''2070010''>able to do with</span> <span
  m=''2070440''>agendas.</span> <span m=''2071409''>That is</span> <span m=''2071630''>a</span>
  <span m=''2071719''>big</span> <span m=''2072060''>complicated</span> <span m=''2072620''>mess.</span>
  <span m=''2082530''>From</span> <span m=''2082719''>an</span> <span m=''2082760''>agenda.</span>
  </p><p><span m=''2085530''>Well,</span> <span m=''2085980''>let''s</span> <span
  m=''2086219''>see</span> <span m=''2086370''>how</span> <span m=''2086520''>we</span>
  <span m=''2086610''>can</span> <span m=''2086699''>organize</span> <span m=''2087290''>this</span>
  <span m=''2087480''>thing</span> <span m=''2087639''>as</span> <span m=''2087730''>a</span>
  <span m=''2087780''>data</span> <span m=''2088040''>structure</span> <span m=''2089552''>a</span>
  <span m=''2090048''>bit.</span> <span m=''2092528''>Well,</span> <span m=''2093030''>an</span>
  <span m=''2093219''>agenda</span> <span m=''2093639''>is</span> <span m=''2093810''>going</span>
  <span m=''2093989''>to</span> <span m=''2094179''>be</span> <span m=''2094989''>some</span>
  <span m=''2095250''>kind</span> <span m=''2095469''>of</span> <span m=''2095580''>list.</span>
  <span m=''2097988''>And</span> <span m=''2098470''>it''s</span> <span m=''2098720''>going</span>
  <span m=''2098820''>to</span> <span m=''2098920''>be</span> <span m=''2099020''>a</span>
  <span m=''2099100''>list</span> <span m=''2099490''>that</span> <span m=''2099710''>I''m</span>
  <span m=''2099810''>going</span> <span m=''2099910''>to</span> <span m=''2100000''>have</span>
  <span m=''2100190''>to be able to</span> <span m=''2100380''>modify.</span> <span
  m=''2101570''>So we have to</span> <span m=''2101900''>talk</span> <span m=''2102060''>about</span>
  <span m=''2102270''>modifying</span> <span m=''2103340''>of</span> <span m=''2103530''>lists,</span>
  <span m=''2105395''>because</span> <span m=''2105820''>I''m going to</span> <span
  m=''2106100''>add</span> <span m=''2106390''>things</span> <span m=''2106610''>to</span>
  <span m=''2106810''>it,</span> <span m=''2107535''>and</span> <span m=''2107880''>delete</span>
  <span m=''2108300''>things</span> <span m=''2108560''>from</span> <span m=''2108790''>it,</span>
  <span m=''2109420''>and</span> <span m=''2109590''>things</span> <span m=''2109810''>like</span>
  <span m=''2110040''>that.</span> <span m=''2111070''>It''s</span> <span m=''2111250''>organized</span>
  <span m=''2111800''>by</span> <span m=''2111960''>time.</span> <span m=''2113820''>It''s</span>
  <span m=''2113930''>probably</span> <span m=''2114300''>good</span> <span m=''2114570''>to
  keep it in</span> <span m=''2114850''>sorted</span> <span m=''2115200''>order.</span>
  </p><p><span m=''2118330''>But</span> <span m=''2118560''>sometimes</span> <span
  m=''2119040''>there</span> <span m=''2119150''>are</span> <span m=''2119190''>lots</span>
  <span m=''2119430''>of</span> <span m=''2119480''>things</span> <span m=''2119660''>that</span>
  <span m=''2119740''>happen</span> <span m=''2120000''>at</span> <span m=''2120080''>the</span>
  <span m=''2122170''>same time--approximate</span> <span m=''2122760''>same</span>
  <span m=''2123010''>time.</span> <span m=''2123420''>What</span> <span m=''2123920''>I
  have to</span> <span m=''2124100''>do</span> <span m=''2124400''>is</span> <span
  m=''2124530''>say,</span> <span m=''2124980''>group</span> <span m=''2125290''>things</span>
  <span m=''2125800''>by</span> <span m=''2125990''>the</span> <span m=''2126110''>time</span>
  <span m=''2126370''>at</span> <span m=''2126440''>which</span> <span m=''2126580''>they''re</span>
  <span m=''2126710''>supposed</span> <span m=''2126890''>to</span> <span m=''2127080''>happen.</span>
  <span m=''2129040''>So I''m</span> <span m=''2129310''>going to make an</span> <span
  m=''2129770''>agenda</span> <span m=''2130330''>as</span> <span m=''2130530''>a</span>
  <span m=''2130590''>list</span> <span m=''2130820''>of</span> <span m=''2130890''>segments.</span>
  <span m=''2132780''>And</span> <span m=''2133220''>so I''m going</span> <span m=''2133440''>to</span>
  <span m=''2133740''>draw</span> <span m=''2134070''>you</span> <span m=''2134290''>a</span>
  <span m=''2134350''>data</span> <span m=''2134590''>structure</span> <span m=''2134950''>for</span>
  <span m=''2135090''>an</span> <span m=''2135150''>agenda,</span> <span m=''2136780''>a</span>
  <span m=''2136870''>perfectly</span> <span m=''2137280''>reasonable</span> <span
  m=''2137575''>one.</span> </p><p><span m=''2139620''>Here''s</span> <span m=''2139820''>an</span>
  <span m=''2139940''>agenda.</span> <span m=''2141110''>It''s</span> <span m=''2141310''>a</span>
  <span m=''2141390''>thing</span> <span m=''2141640''>that</span> <span m=''2141830''>begins</span>
  <span m=''2142260''>with</span> <span m=''2142360''>a</span> <span m=''2142470''>name.</span>
  <span m=''2147630''>I''m</span> <span m=''2147900''>going</span> <span m=''2148030''>to</span>
  <span m=''2148200''>do it</span> <span m=''2148460''>right</span> <span m=''2148740''>now</span>
  <span m=''2149020''>out of</span> <span m=''2149400''>list</span> <span m=''2149640''>structure.</span>
  <span m=''2152620''>It''s</span> <span m=''2152770''>got</span> <span m=''2152920''>a</span>
  <span m=''2152940''>header.</span> <span m=''2153980''>There''s</span> <span m=''2154380''>a</span>
  <span m=''2154480''>reason</span> <span m=''2154850''>for</span> <span m=''2154970''>the</span>
  <span m=''2155050''>header.</span> <span m=''2155840''>We''re</span> <span m=''2155960''>going</span>
  <span m=''2156040''>to</span> <span m=''2156120''>see</span> <span m=''2156320''>the</span>
  <span m=''2156420''>reason</span> <span m=''2157180''>soon.</span> </p><p><span
  m=''2160680''>And</span> <span m=''2160880''>it</span> <span m=''2160950''>will</span>
  <span m=''2161080''>have</span> <span m=''2161450''>a</span> <span m=''2161580''>segment.</span>
  <span m=''2163750''>It</span> <span m=''2164090''>will have--it will</span> <span
  m=''2164290''>be</span> <span m=''2164460''>a</span> <span m=''2164510''>list</span>
  <span m=''2164890''>of</span> <span m=''2165210''>segments.</span> <span m=''2168310''>Supposing</span>
  <span m=''2168760''>this</span> <span m=''2168920''>agenda</span> <span m=''2169490''>has</span>
  <span m=''2169780''>two</span> <span m=''2169960''>segments,</span> <span m=''2171810''>they''re</span>
  <span m=''2172120''>the car''s--</span> <span m=''2173580''>successive</span> <span
  m=''2174090''>car''s</span> <span m=''2174400''>of</span> <span m=''2174530''>this</span>
  <span m=''2174670''>list.</span> <span m=''2176520''>Each</span> <span m=''2176780''>segment</span>
  <span m=''2178110''>is</span> <span m=''2178260''>going</span> <span m=''2178480''>to</span>
  <span m=''2178560''>have</span> <span m=''2179760''>a</span> <span m=''2179930''>time--</span>
  <span m=''2184160''>say</span> <span m=''2184660''>for</span> <span m=''2184960''>example,</span>
  <span m=''2185990''>10--</span> <span m=''2186900''>that</span> <span m=''2187040''>says</span>
  <span m=''2187450''>that</span> <span m=''2187900''>the</span> <span m=''2188020''>things</span>
  <span m=''2188310''>that</span> <span m=''2188430''>happen</span> <span m=''2188770''>in</span>
  <span m=''2188880''>this</span> <span m=''2189060''>segment</span> <span m=''2189460''>are</span>
  <span m=''2189670''>at</span> <span m=''2189910''>time</span> <span m=''2190150''>10.</span>
  </p><p><span m=''2193320''>And</span> <span m=''2193580''>what</span> <span m=''2193690''>I''m
  going to have in</span> <span m=''2194030''>here</span> <span m=''2195320''>is</span>
  <span m=''2195660''>another</span> <span m=''2196070''>data</span> <span m=''2196310''>structure</span>
  <span m=''2196670''>which</span> <span m=''2196830''>I''m</span> <span m=''2196930''>not</span>
  <span m=''2197090''>going</span> <span m=''2197160''>to</span> <span m=''2197230''>describe,</span>
  <span m=''2198530''>which</span> <span m=''2198730''>is</span> <span m=''2198870''>a</span>
  <span m=''2198970''>queue</span> <span m=''2199340''>of</span> <span m=''2199490''>things</span>
  <span m=''2199840''>to</span> <span m=''2199950''>do</span> <span m=''2200280''>at</span>
  <span m=''2200360''>time</span> <span m=''2200640''>10.</span> <span m=''2202240''>It''s</span>
  <span m=''2202350''>a</span> <span m=''2202600''>queue.</span> <span m=''2203330''>And</span>
  <span m=''2203450''>we''ll</span> <span m=''2203560''>talk</span> <span m=''2203750''>about</span>
  <span m=''2203920''>that</span> <span m=''2204030''>in</span> <span m=''2204140''>a</span>
  <span m=''2204200''>second.</span> <span m=''2205130''>But</span> <span m=''2205370''>abstractly,</span>
  <span m=''2206430''>the</span> <span m=''2206700''>queue</span> <span m=''2207990''>is</span>
  <span m=''2208150''>just</span> <span m=''2208490''>a</span> <span m=''2208700''>list</span>
  <span m=''2208910''>of</span> <span m=''2208990''>things</span> <span m=''2209190''>to</span>
  <span m=''2209270''>do</span> <span m=''2209480''>at</span> <span m=''2209530''>a</span>
  <span m=''2209570''>particular</span> <span m=''2209920''>time.</span> <span m=''2210200''>And</span>
  <span m=''2210480''>I</span> <span m=''2210540''>can</span> <span m=''2210770''>add</span>
  <span m=''2211150''>things</span> <span m=''2211440''>to</span> <span m=''2211640''>a
  queue.</span> <span m=''2213100''>This is</span> <span m=''2213330''>a</span> <span
  m=''2213400''>queue.</span> <span m=''2216140''>There''s a</span> <span m=''2216640''>time,</span>
  <span m=''2218460''>there''s a</span> <span m=''2218750''>segment.</span> </p><p><span
  m=''2222889''>Now,</span> <span m=''2223380''>I</span> <span m=''2223570''>may</span>
  <span m=''2223690''>have</span> <span m=''2223840''>another</span> <span m=''2224150''>segment</span>
  <span m=''2224580''>in</span> <span m=''2224860''>this</span> <span m=''2225770''>agenda.</span>
  <span m=''2228940''>Supposing</span> <span m=''2229380''>this</span> <span m=''2229490''>is</span>
  <span m=''2229570''>stuff</span> <span m=''2229820''>that</span> <span m=''2229930''>happens</span>
  <span m=''2230220''>at</span> <span m=''2230340''>time</span> <span m=''2230670''>30.</span>
  <span m=''2233410''>It</span> <span m=''2233720''>has,</span> <span m=''2234410''>of</span>
  <span m=''2234540''>course,</span> <span m=''2235140''>another</span> <span m=''2235510''>queue</span>
  <span m=''2236980''>of</span> <span m=''2237110''>things</span> <span m=''2237440''>that</span>
  <span m=''2237560''>are</span> <span m=''2238020''>queued</span> <span m=''2238350''>up</span>
  <span m=''2238490''>to</span> <span m=''2238580''>be</span> <span m=''2238690''>done</span>
  <span m=''2238950''>at</span> <span m=''2239430''>time</span> <span m=''2239730''>30.</span>
  <span m=''2243210''>Well,</span> <span m=''2243420''>there</span> <span m=''2243590''>are</span>
  <span m=''2243620''>various</span> <span m=''2244010''>things</span> <span m=''2244240''>I</span>
  <span m=''2244350''>have</span> <span m=''2244450''>to</span> <span m=''2244560''>be
  able</span> <span m=''2244850''>to do</span> <span m=''2245000''>to</span> <span
  m=''2245120''>an</span> <span m=''2245180''>agenda.</span> </p><p><span m=''2247090''>Supposing</span>
  <span m=''2247540''>I</span> <span m=''2247610''>want</span> <span m=''2247940''>to</span>
  <span m=''2248060''>add</span> <span m=''2248320''>to</span> <span m=''2248450''>an</span>
  <span m=''2248580''>agenda</span> <span m=''2249450''>another</span> <span m=''2249960''>thing</span>
  <span m=''2250200''>to</span> <span m=''2250300''>be</span> <span m=''2250410''>done</span>
  <span m=''2250710''>at</span> <span m=''2250900''>time</span> <span m=''2251170''>10.</span>
  <span m=''2253030''>Well,</span> <span m=''2253160''>that''s</span> <span m=''2253390''>not</span>
  <span m=''2253560''>very</span> <span m=''2253760''>hard.</span> <span m=''2254700''>I''m</span>
  <span m=''2254930''>going</span> <span m=''2255010''>to</span> <span m=''2255100''>walk</span>
  <span m=''2255450''>down</span> <span m=''2255740''>here,</span> <span m=''2256170''>looking</span>
  <span m=''2256490''>for</span> <span m=''2257390''>the</span> <span m=''2257480''>segment</span>
  <span m=''2257840''>of</span> <span m=''2257950''>time</span> <span m=''2258210''>10.</span>
  <span m=''2259730''>It</span> <span m=''2259880''>is</span> <span m=''2260010''>possible</span>
  <span m=''2260280''>that</span> <span m=''2260550''>there</span> <span m=''2260780''>is</span>
  <span m=''2260840''>no</span> <span m=''2260990''>segment</span> <span m=''2261370''>of</span>
  <span m=''2261460''>time</span> <span m=''2261730''>10.</span> <span m=''2262930''>We''ll</span>
  <span m=''2263250''>cover</span> <span m=''2263450''>that</span> <span m=''2263630''>case</span>
  <span m=''2263880''>in a</span> <span m=''2264180''>second.</span> <span m=''2265420''>But</span>
  <span m=''2265780''>if</span> <span m=''2266070''>I</span> <span m=''2266160''>find</span>
  <span m=''2266460''>a</span> <span m=''2266510''>segment</span> <span m=''2266840''>of</span>
  <span m=''2266940''>time</span> <span m=''2267190''>10,</span> <span m=''2267880''>then
  if</span> <span m=''2268050''>I</span> <span m=''2268200''>want</span> <span m=''2268320''>to</span>
  <span m=''2268430''>add</span> <span m=''2268590''>another</span> <span m=''2268860''>thing</span>
  <span m=''2269120''>to</span> <span m=''2269230''>be</span> <span m=''2269450''>done</span>
  <span m=''2269660''>at</span> <span m=''2269750''>time</span> <span m=''2270070''>10,</span>
  <span m=''2270650''>I</span> <span m=''2270820''>just</span> <span m=''2271070''>increase</span>
  <span m=''2271490''>that</span> <span m=''2271790''>queue--</span> <span m=''2273860''>"just</span>
  <span m=''2274410''>increase"</span> <span m=''2275100''>isn''t</span> <span m=''2275280''>such</span>
  <span m=''2275410''>an</span> <span m=''2275500''>obvious</span> <span m=''2275880''>idea.</span>
  <span m=''2276290''>But</span> <span m=''2276720''>I</span> <span m=''2276780''>increase</span>
  <span m=''2277460''>the</span> <span m=''2277810''>things</span> <span m=''2278050''>to</span>
  <span m=''2278130''>be</span> <span m=''2278220''>done</span> <span m=''2278440''>at</span>
  <span m=''2278530''>that</span> <span m=''2278750''>time.</span> </p><p><span m=''2281430''>Now,</span>
  <span m=''2281680''>supposing</span> <span m=''2281950''>I want</span> <span m=''2282110''>to</span>
  <span m=''2282190''>add</span> <span m=''2282410''>something</span> <span m=''2282700''>to</span>
  <span m=''2282780''>be</span> <span m=''2282900''>done</span> <span m=''2283110''>at</span>
  <span m=''2283230''>time</span> <span m=''2283760''>20.</span> <span m=''2285140''>There
  is</span> <span m=''2285570''>no</span> <span m=''2285730''>segment</span> <span
  m=''2287040''>for</span> <span m=''2287220''>time</span> <span m=''2287480''>20.</span>
  <span m=''2288680''>I''m</span> <span m=''2289100''>going</span> <span m=''2289170''>to</span>
  <span m=''2289300''>have</span> <span m=''2289460''>to</span> <span m=''2289550''>create</span>
  <span m=''2289850''>a</span> <span m=''2289900''>new</span> <span m=''2290040''>segment.</span>
  <span m=''2291340''>I</span> <span m=''2291510''>want</span> <span m=''2291690''>my</span>
  <span m=''2291850''>time</span> <span m=''2292160''>20</span> <span m=''2292440''>segment</span>
  <span m=''2293040''>to</span> <span m=''2293250''>exist</span> <span m=''2293590''>between</span>
  <span m=''2293960''>time</span> <span m=''2294240''>10</span> <span m=''2294730''>and</span>
  <span m=''2294920''>time</span> <span m=''2295170''>30.</span> <span m=''2297610''>Well,</span>
  <span m=''2298280''>that</span> <span m=''2298530''>takes</span> <span m=''2298710''>a</span>
  <span m=''2298760''>little</span> <span m=''2298970''>work.</span> <span m=''2300170''>I''m</span>
  <span m=''2300340''>going</span> <span m=''2300410''>to</span> <span m=''2300480''>have</span>
  <span m=''2300620''>to</span> <span m=''2300710''>do</span> <span m=''2301080''>a</span>
  <span m=''2301210''>CONS.</span> <span m=''2304260''>I''m going</span> <span m=''2304470''>to</span>
  <span m=''2304680''>have</span> <span m=''2304800''>to</span> <span m=''2304900''>make</span>
  <span m=''2305130''>a</span> <span m=''2305530''>new</span> <span m=''2307270''>element</span>
  <span m=''2307900''>of</span> <span m=''2308130''>the</span> <span m=''2308280''>agenda</span>
  <span m=''2308690''>list--list</span> <span m=''2309220''>of</span> <span m=''2309350''>segments.</span>
  <span m=''2313600''>I''m</span> <span m=''2313690''>going</span> <span m=''2313860''>to
  have</span> <span m=''2314030''>to</span> <span m=''2314130''>change.</span> <span
  m=''2315400''>Here''s</span> <span m=''2315700''>change.</span> <span m=''2317540''>I''m</span>
  <span m=''2317670''>going</span> <span m=''2317810''>to</span> <span m=''2317880''>have</span>
  <span m=''2317950''>to</span> <span m=''2318060''>change</span> <span m=''2319600''>the</span>
  <span m=''2319850''>CDR</span> <span m=''2321020''>of</span> <span m=''2321220''>the</span>
  <span m=''2321310''>CDR</span> <span m=''2321940''>of</span> <span m=''2322160''>the</span>
  <span m=''2322290''>agenda</span> <span m=''2324850''>to</span> <span m=''2325010''>point</span>
  <span m=''2325310''>that</span> <span m=''2325630''>a</span> <span m=''2325740''>new</span>
  <span m=''2325930''>CONS</span> <span m=''2327570''>of</span> <span m=''2328440''>the</span>
  <span m=''2328580''>new</span> <span m=''2328790''>segment</span> <span m=''2330150''>and</span>
  <span m=''2330620''>the</span> <span m=''2330920''>CDR</span> <span m=''2331310''>of</span>
  <span m=''2331510''>the</span> <span m=''2331610''>CDR</span> <span m=''2331970''>of</span>
  <span m=''2332110''>the</span> <span m=''2332200''>CDR</span> <span m=''2332670''>of
  the</span> <span m=''2332790''>agenda,</span> <span m=''2333771''>the</span> <span
  m=''2334252''>CD-D-D-DR.</span> </p><p><span m=''2336657''>And</span> <span m=''2337140''>this</span>
  <span m=''2337460''>is</span> <span m=''2337520''>going</span> <span m=''2337610''>to</span>
  <span m=''2337690''>have</span> <span m=''2337800''>a</span> <span m=''2337900''>new</span>
  <span m=''2338620''>segment</span> <span m=''2339070''>now</span> <span m=''2340380''>of</span>
  <span m=''2340610''>time</span> <span m=''2341350''>20</span> <span m=''2342470''>with</span>
  <span m=''2342660''>its</span> <span m=''2342810''>own</span> <span m=''2343090''>queue,</span>
  <span m=''2344930''>which</span> <span m=''2345190''>now has</span> <span m=''2345450''>one</span>
  <span m=''2345630''>element</span> <span m=''2345970''>in</span> <span m=''2346080''>it.</span>
  <span m=''2350730''>If</span> <span m=''2350940''>I</span> <span m=''2351060''>wanted</span>
  <span m=''2351260''>to</span> <span m=''2351460''>add</span> <span m=''2351670''>something</span>
  <span m=''2352000''>at</span> <span m=''2352090''>the</span> <span m=''2352340''>end,</span>
  <span m=''2352580''>I''m</span> <span m=''2352750''>going</span> <span m=''2352910''>to</span>
  <span m=''2352990''>have</span> <span m=''2353080''>to</span> <span m=''2353150''>replace</span>
  <span m=''2353570''>the</span> <span m=''2353690''>CDR</span> <span m=''2354590''>of</span>
  <span m=''2355540''>this, of this</span> <span m=''2357420''>list</span> <span m=''2358530''>with</span>
  <span m=''2358730''>something.</span> <span m=''2360770''>We''re</span> <span m=''2360870''>going
  to</span> <span m=''2360970''>have to</span> <span m=''2361070''>change</span> <span
  m=''2361530''>that</span> <span m=''2361750''>piece</span> <span m=''2361940''>of</span>
  <span m=''2362520''>data</span> <span m=''2362720''>structure.</span> <span m=''2364040''>So</span>
  <span m=''2364260''>I''m</span> <span m=''2364590''>going to need new</span> <span
  m=''2364790''>primitives</span> <span m=''2365210''>for</span> <span m=''2365320''>doing</span>
  <span m=''2365600''>this.</span> <span m=''2367210''>But I''m</span> <span m=''2367320''>just</span>
  <span m=''2367440''>showing</span> <span m=''2367600''>you</span> <span m=''2367740''>why</span>
  <span m=''2368060''>I</span> <span m=''2368160''>need</span> <span m=''2368390''>them.</span>
  </p><p><span m=''2369550''>And</span> <span m=''2369790''>finally,</span> <span
  m=''2371380''>if</span> <span m=''2371500''>I</span> <span m=''2371660''>wanted</span>
  <span m=''2371820''>to</span> <span m=''2371960''>add</span> <span m=''2372190''>a</span>
  <span m=''2372490''>thing</span> <span m=''2372660''>to</span> <span m=''2372730''>be</span>
  <span m=''2372830''>done</span> <span m=''2373010''>at</span> <span m=''2373090''>time</span>
  <span m=''2373390''>5,</span> <span m=''2377220''>I''m</span> <span m=''2377360''>going</span>
  <span m=''2377450''>to</span> <span m=''2377540''>have</span> <span m=''2377680''>to</span>
  <span m=''2377770''>change</span> <span m=''2378510''>this</span> <span m=''2378830''>one,</span>
  <span m=''2380820''>because</span> <span m=''2381010''>I''m</span> <span m=''2381120''>going
  to</span> <span m=''2381240''>have to</span> <span m=''2381340''>add</span> <span
  m=''2381570''>it in</span> <span m=''2381700''>over</span> <span m=''2381860''>here,</span>
  <span m=''2383330''>which</span> <span m=''2383540''>is</span> <span m=''2383640''>why</span>
  <span m=''2383950''>I</span> <span m=''2384060''>planned</span> <span m=''2384380''>ahead</span>
  <span m=''2384770''>and</span> <span m=''2385000''>had</span> <span m=''2385350''>a</span>
  <span m=''2385570''>header</span> <span m=''2385840''>cell,</span> <span m=''2387530''>which</span>
  <span m=''2387800''>has</span> <span m=''2388000''>a</span> <span m=''2388050''>place.</span>
  <span m=''2389400''>If</span> <span m=''2389530''>I''m</span> <span m=''2389590''>going
  to</span> <span m=''2389760''>change</span> <span m=''2390100''>things,</span> <span
  m=''2390300''>I have</span> <span m=''2390450''>to  have</span> <span m=''2390580''>places</span>
  <span m=''2391110''>for</span> <span m=''2391280''>the</span> <span m=''2391460''>change.</span>
  <span m=''2393420''>I</span> <span m=''2393900''>have to</span> <span m=''2394120''>have
  a</span> <span m=''2394250''>place</span> <span m=''2395300''>to</span> <span m=''2395450''>make</span>
  <span m=''2395680''>the</span> <span m=''2395760''>change.</span> </p><p><span m=''2398600''>If</span>
  <span m=''2398860''>I</span> <span m=''2399350''>remove</span> <span m=''2399790''>things</span>
  <span m=''2400080''>from</span> <span m=''2400250''>the</span> <span m=''2400380''>agenda,</span>
  <span m=''2401700''>that''s</span> <span m=''2401950''>not</span> <span m=''2402120''>so</span>
  <span m=''2402270''>hard.</span> <span m=''2402540''>Removing</span> <span m=''2402850''>them</span>
  <span m=''2403000''>from</span> <span m=''2403120''>the</span> <span m=''2403250''>beginning</span>
  <span m=''2403830''>is</span> <span m=''2404020''>pretty</span> <span m=''2404210''>easy,</span>
  <span m=''2404990''>which is</span> <span m=''2405310''>the</span> <span m=''2405350''>only</span>
  <span m=''2405530''>case</span> <span m=''2405760''>I</span> <span m=''2405970''>have.</span>
  <span m=''2406550''>I</span> <span m=''2406700''>can</span> <span m=''2406880''>go</span>
  <span m=''2407220''>looking</span> <span m=''2407540''>for</span> <span m=''2407650''>the</span>
  <span m=''2407740''>first, the first</span> <span m=''2409570''>segment.</span>
  <span m=''2411220''>I</span> <span m=''2411370''>see</span> <span m=''2411570''>if</span>
  <span m=''2411720''>it</span> <span m=''2411880''>has</span> <span m=''2412060''>a</span>
  <span m=''2412870''>non-empty</span> <span m=''2413420''>queue.</span> <span m=''2414510''>If
  it</span> <span m=''2414850''>has</span> <span m=''2415150''>a</span> <span m=''2415350''>non-empty</span>
  <span m=''2415600''>queue,</span> <span m=''2416250''>well,</span> <span m=''2416630''>I''m</span>
  <span m=''2416740''>going</span> <span m=''2416950''>to</span> <span m=''2417030''>delete</span>
  <span m=''2417420''>one</span> <span m=''2417610''>element</span> <span m=''2417910''>from</span>
  <span m=''2418010''>the</span> <span m=''2418120''>queue,</span> <span m=''2419320''>like</span>
  <span m=''2419510''>that.</span> <span m=''2420100''>If</span> <span m=''2420290''>the</span>
  <span m=''2420400''>queue</span> <span m=''2420620''>ever</span> <span m=''2420830''>becomes</span>
  <span m=''2421280''>empty,</span> <span m=''2422630''>then</span> <span m=''2422920''>I</span>
  <span m=''2423010''>have</span> <span m=''2423140''>to</span> <span m=''2423230''>delete</span>
  <span m=''2423460''>the</span> <span m=''2423540''>whole</span> <span m=''2423710''>segment.</span>
  <span m=''2424220''>And</span> <span m=''2424360''>then</span> <span m=''2424520''>this,
  this</span> <span m=''2425260''>changes</span> <span m=''2425710''>to</span> <span
  m=''2425810''>point</span> <span m=''2426070''>to</span> <span m=''2426150''>here.</span>
  <span m=''2428220''>So it''s</span> <span m=''2428430''>quite a</span> <span m=''2428700''>complicated</span>
  <span m=''2429180''>data</span> <span m=''2429380''>structure</span> <span m=''2429930''>manipulation</span>
  <span m=''2430540''>going</span> <span m=''2430780''>on,</span> <span m=''2432250''>the</span>
  <span m=''2432550''>details</span> <span m=''2432805''>of</span> <span m=''2433060''>which</span>
  <span m=''2434070''>are</span> <span m=''2434240''>not</span> <span m=''2434480''>really</span>
  <span m=''2434670''>very</span> <span m=''2434880''>exciting.</span> </p><p><span
  m=''2436440''>Now,</span> <span m=''2436550''>let''s</span> <span m=''2436730''>talk</span>
  <span m=''2436950''>about</span> <span m=''2437880''>queues.</span> <span m=''2438920''>They''re</span>
  <span m=''2439220''>similar.</span> <span m=''2441160''>Because</span> <span m=''2441410''>each</span>
  <span m=''2441580''>of</span> <span m=''2441700''>these</span> <span m=''2441820''>agendas</span>
  <span m=''2442540''>has</span> <span m=''2442780''>a</span> <span m=''2442840''>queue
  in</span> <span m=''2443180''>it.</span> <span m=''2444340''>What''s</span> <span
  m=''2444470''>a</span> <span m=''2444610''>queue?</span> <span m=''2449079''>A</span>
  <span m=''2449530''>queue</span> <span m=''2449680''>is</span> <span m=''2449850''>going</span>
  <span m=''2450010''>to</span> <span m=''2450080''>have</span> <span m=''2450210''>the</span>
  <span m=''2450290''>following</span> <span m=''2450730''>primitive</span> <span
  m=''2451110''>operations.</span> <span m=''2452350''>To</span> <span m=''2452960''>make</span>
  <span m=''2453330''>a queue,</span> <span m=''2460642''>this</span> <span m=''2461140''>gives</span>
  <span m=''2461440''>me a</span> <span m=''2461500''>new</span> <span m=''2461710''>queue.</span>
  <span m=''2467274''>I''m going to</span> <span m=''2467740''>have to be</span> <span
  m=''2468240''>able to</span> <span m=''2468520''>insert</span> <span m=''2472480''>into</span>
  <span m=''2472610''>a</span> <span m=''2472900''>queue</span> <span m=''2475910''>a</span>
  <span m=''2476310''>new</span> <span m=''2476520''>item.</span> <span m=''2484510''>I''m</span>
  <span m=''2484650''>going to have</span> <span m=''2484960''>to be</span> <span
  m=''2485230''>able to</span> <span m=''2485590''>delete</span> <span m=''2485750''>from
  a queue</span> <span m=''2487290''>the</span> <span m=''2487490''>first</span> <span
  m=''2487690''>item</span> <span m=''2488000''>in the</span> <span m=''2488080''>queue.</span>
  <span m=''2499988''>And</span> <span m=''2500440''>I</span> <span m=''2500630''>want</span>
  <span m=''2500980''>to</span> <span m=''2501050''>be able to get</span> <span m=''2501190''>the</span>
  <span m=''2501270''>first</span> <span m=''2501550''>thing</span> <span m=''2501710''>in</span>
  <span m=''2501780''>the</span> <span m=''2501860''>queue</span> <span m=''2511320''>from</span>
  <span m=''2511550''>some</span> <span m=''2511750''>queue.</span> <span m=''2512890''>I</span>
  <span m=''2513330''>also</span> <span m=''2513600''>have</span> <span m=''2513730''>to
  be able to</span> <span m=''2513920''>test</span> <span m=''2514240''>whether</span>
  <span m=''2514480''>a</span> <span m=''2514620''>queue is</span> <span m=''2514760''>empty.</span>
  </p><p><span m=''2527110''>And</span> <span m=''2527270''>when</span> <span m=''2527410''>you</span>
  <span m=''2527530''>invent</span> <span m=''2527900''>things</span> <span m=''2528150''>like</span>
  <span m=''2528400''>this,</span> <span m=''2529000''>I</span> <span m=''2529190''>want</span>
  <span m=''2529440''>you</span> <span m=''2529510''>to</span> <span m=''2529570''>be</span>
  <span m=''2529710''>very</span> <span m=''2529960''>careful</span> <span m=''2530590''>to</span>
  <span m=''2530760''>use</span> <span m=''2531020''>the</span> <span m=''2531140''>kinds</span>
  <span m=''2531690''>of</span> <span m=''2532210''>conventions</span> <span m=''2532780''>I</span>
  <span m=''2532880''>use</span> <span m=''2533090''>for</span> <span m=''2533220''>naming</span>
  <span m=''2533600''>things.</span> <span m=''2535120''>Notice</span> <span m=''2535570''>that
  I''m</span> <span m=''2535750''>careful</span> <span m=''2536290''>to</span> <span
  m=''2536600''>say</span> <span m=''2536850''>these</span> <span m=''2537170''>change</span>
  <span m=''2537510''>something</span> <span m=''2538190''>and</span> <span m=''2538450''>that</span>
  <span m=''2538710''>tests</span> <span m=''2538985''>it.</span> <span m=''2539870''>And</span>
  <span m=''2540050''>presumably,</span> <span m=''2540520''>I</span> <span m=''2540580''>did</span>
  <span m=''2540720''>the</span> <span m=''2540820''>same</span> <span m=''2541080''>thing</span>
  <span m=''2541240''>over</span> <span m=''2541490''>here.</span> <span m=''2544335''>OK,</span>
  <span m=''2544820''>and there</span> <span m=''2545220''>should</span> <span m=''2545350''>be
  an</span> <span m=''2545570''>empty</span> <span m=''2546180''>test over</span>
  <span m=''2546670''>here.</span> </p><p><span m=''2549240''>OK,</span> <span m=''2549430''>well,</span>
  <span m=''2549570''>how would</span> <span m=''2549880''>I</span> <span m=''2549960''>make</span>
  <span m=''2550200''>a</span> <span m=''2550250''>queue?</span> <span m=''2551720''>A</span>
  <span m=''2551820''>queue</span> <span m=''2552050''>wants</span> <span m=''2552260''>to</span>
  <span m=''2552320''>be</span> <span m=''2552410''>something</span> <span m=''2552700''>I</span>
  <span m=''2552800''>can</span> <span m=''2552940''>add</span> <span m=''2553210''>to</span>
  <span m=''2553340''>at</span> <span m=''2553440''>the</span> <span m=''2553580''>end</span>
  <span m=''2553810''>of,</span> <span m=''2555210''>and</span> <span m=''2555440''>pick</span>
  <span m=''2555620''>up</span> <span m=''2555760''>the</span> <span m=''2555870''>thing</span>
  <span m=''2556060''>at</span> <span m=''2556120''>the</span> <span m=''2556200''>beginning</span>
  <span m=''2556610''>of.</span> <span m=''2557840''>I</span> <span m=''2557950''>should</span>
  <span m=''2558090''>be</span> <span m=''2558180''>able</span> <span m=''2558250''>to
  delete</span> <span m=''2558540''>from</span> <span m=''2558640''>the</span> <span
  m=''2558720''>beginning</span> <span m=''2559290''>and</span> <span m=''2559520''>add</span>
  <span m=''2559800''>to</span> <span m=''2560070''>the</span> <span m=''2560310''>end.</span>
  <span m=''2561230''>Well,</span> <span m=''2561510''>I''m going to</span> <span
  m=''2561620''>show</span> <span m=''2561790''>you</span> <span m=''2561900''>a</span>
  <span m=''2561940''>very</span> <span m=''2562150''>simple</span> <span m=''2562400''>structure</span>
  <span m=''2562840''>for</span> <span m=''2562940''>that.</span> <span m=''2563740''>We</span>
  <span m=''2564050''>can</span> <span m=''2564180''>make</span> <span m=''2564380''>this</span>
  <span m=''2564580''>out</span> <span m=''2564680''>of</span> <span m=''2564780''>CONSes</span>
  <span m=''2565210''>as</span> <span m=''2565350''>well.</span> </p><p><span m=''2567080''>Here''s</span>
  <span m=''2567290''>a</span> <span m=''2567360''>queue.</span> <span m=''2569910''>It</span>
  <span m=''2570280''>has--it has</span> <span m=''2571730''>a</span> <span m=''2571830''>queue</span>
  <span m=''2572060''>header,</span> <span m=''2573710''>which</span> <span m=''2573920''>contains</span>
  <span m=''2574350''>two</span> <span m=''2574500''>parts--</span> <span m=''2575310''>a</span>
  <span m=''2575400''>front</span> <span m=''2575740''>pointer</span> <span m=''2578440''>and</span>
  <span m=''2579020''>a</span> <span m=''2579080''>rear</span> <span m=''2579340''>pointer.</span>
  <span m=''2582930''>And</span> <span m=''2583320''>here</span> <span m=''2583570''>I</span>
  <span m=''2583650''>have</span> <span m=''2583800''>a</span> <span m=''2583850''>queue</span>
  <span m=''2584870''>with</span> <span m=''2585300''>two</span> <span m=''2585550''>items</span>
  <span m=''2585920''>in</span> <span m=''2586090''>it.</span> <span m=''2589000''>The</span>
  <span m=''2589310''>first</span> <span m=''2589620''>item,</span> <span m=''2589970''>I</span>
  <span m=''2590090''>don''t</span> <span m=''2590230''>know,</span> <span m=''2590370''>it''s</span>
  <span m=''2590510''>perhaps</span> <span m=''2591250''>a</span> <span m=''2591330''>1.</span>
  <span m=''2592095''>And</span> <span m=''2592370''>the</span> <span m=''2592740''>second</span>
  <span m=''2593110''>item,</span> <span m=''2595300''>I don''t</span> <span m=''2595590''>know,
  let''s</span> <span m=''2595820''>give it</span> <span m=''2595950''>a</span> <span
  m=''2596250''>2.</span> <span m=''2601160''>The</span> <span m=''2601510''>reason</span>
  <span m=''2601760''>why</span> <span m=''2601960''>I</span> <span m=''2602160''>want</span>
  <span m=''2602350''>two</span> <span m=''2602510''>pointers</span> <span m=''2603000''>in</span>
  <span m=''2603120''>here,</span> <span m=''2604160''>a</span> <span m=''2604270''>front</span>
  <span m=''2604550''>pointer</span> <span m=''2604660''>and a</span> <span m=''2604770''>rear</span>
  <span m=''2605120''>pointer,</span> <span m=''2605740''>is</span> <span m=''2605950''>so
  I</span> <span m=''2606090''>can</span> <span m=''2606210''>add</span> <span m=''2606470''>to</span>
  <span m=''2606540''>the</span> <span m=''2606690''>end</span> <span m=''2607570''>without</span>
  <span m=''2607880''>having</span> <span m=''2608100''>to</span> <span m=''2608140''>chase</span>
  <span m=''2608540''>down</span> <span m=''2608830''>from</span> <span m=''2608930''>the</span>
  <span m=''2609040''>beginning.</span> </p><p><span m=''2611850''>So</span> <span
  m=''2612080''>for</span> <span m=''2612270''>example,</span> <span m=''2612660''>if</span>
  <span m=''2612770''>I</span> <span m=''2612840''>wanted</span> <span m=''2613080''>to</span>
  <span m=''2613240''>add</span> <span m=''2613450''>one</span> <span m=''2613630''>more</span>
  <span m=''2613820''>item</span> <span m=''2614110''>to this</span> <span m=''2614380''>queue,</span>
  <span m=''2615030''>if</span> <span m=''2615320''>I</span> <span m=''2615430''>want</span>
  <span m=''2615660''>to</span> <span m=''2615740''>add</span> <span m=''2615950''>on</span>
  <span m=''2616840''>another</span> <span m=''2617840''>item</span> <span m=''2619380''>to</span>
  <span m=''2619510''>be</span> <span m=''2620020''>worried</span> <span m=''2620380''>about</span>
  <span m=''2620600''>later,</span> <span m=''2620875''>all</span> <span m=''2621150''>I
  have to</span> <span m=''2621470''>do</span> <span m=''2621660''>is make</span>
  <span m=''2621820''>a</span> <span m=''2621950''>CONS,</span> <span m=''2623490''>which</span>
  <span m=''2623650''>contains</span> <span m=''2624060''>that</span> <span m=''2624210''>item,</span>
  <span m=''2625730''>say</span> <span m=''2625970''>a 3.</span> <span m=''2627530''>That''s</span>
  <span m=''2627770''>for</span> <span m=''2628300''>inserting</span> <span m=''2628870''>3</span>
  <span m=''2629270''>into</span> <span m=''2629410''>the</span> <span m=''2629540''>queue.</span>
  <span m=''2631340''>Then</span> <span m=''2631790''>I</span> <span m=''2631890''>have</span>
  <span m=''2632050''>to</span> <span m=''2632180''>change</span> <span m=''2632620''>this</span>
  <span m=''2632870''>pointer</span> <span m=''2633280''>here</span> <span m=''2638060''>to</span>
  <span m=''2638220''>here.</span> <span m=''2640100''>And</span> <span m=''2640300''>I</span>
  <span m=''2640360''>have</span> <span m=''2640510''>to</span> <span m=''2640620''>change</span>
  <span m=''2641070''>this</span> <span m=''2641300''>one</span> <span m=''2643090''>to</span>
  <span m=''2643390''>point</span> <span m=''2643640''>to</span> <span m=''2643720''>the</span>
  <span m=''2643830''>new</span> <span m=''2643980''>rear.</span> </p><p><span m=''2649120''>If</span>
  <span m=''2649360''>I</span> <span m=''2649430''>wish</span> <span m=''2649690''>to</span>
  <span m=''2650190''>take</span> <span m=''2650580''>the</span> <span m=''2650680''>first</span>
  <span m=''2650990''>element</span> <span m=''2651330''>of</span> <span m=''2651390''>the</span>
  <span m=''2651460''>queue,</span> <span m=''2651800''>the</span> <span m=''2651990''>first</span>
  <span m=''2652170''>item,</span> <span m=''2652980''>I just</span> <span m=''2653180''>go</span>
  <span m=''2653390''>chasing</span> <span m=''2653670''>down</span> <span m=''2653810''>the</span>
  <span m=''2653880''>front</span> <span m=''2654130''>pointer</span> <span m=''2654810''>until</span>
  <span m=''2654940''>I</span> <span m=''2655130''>find</span> <span m=''2655360''>the</span>
  <span m=''2655550''>first</span> <span m=''2655730''>one</span> <span m=''2656590''>and</span>
  <span m=''2656730''>pick</span> <span m=''2656890''>it</span> <span m=''2656960''>up.</span>
  <span m=''2658890''>If</span> <span m=''2659100''>I</span> <span m=''2659210''>wish</span>
  <span m=''2659450''>to</span> <span m=''2659970''>delete</span> <span m=''2660430''>the</span>
  <span m=''2660620''>first</span> <span m=''2660810''>item</span> <span m=''2661030''>from</span>
  <span m=''2661140''>the</span> <span m=''2661260''>queue,</span> <span m=''2662560''>delete-queue,</span>
  <span m=''2664220''>all I</span> <span m=''2664470''>do</span> <span m=''2664640''>is</span>
  <span m=''2664740''>move</span> <span m=''2664930''>the</span> <span m=''2665020''>front</span>
  <span m=''2665240''>pointer</span> <span m=''2665530''>along</span> <span m=''2665800''>this</span>
  <span m=''2665970''>way.</span> <span m=''2667450''>The</span> <span m=''2667910''>new</span>
  <span m=''2668100''>front</span> <span m=''2668360''>of</span> <span m=''2668420''>the</span>
  <span m=''2668500''>queue</span> <span m=''2668760''>is</span> <span m=''2668870''>now</span>
  <span m=''2669070''>this.</span> <span m=''2671700''>So</span> <span m=''2671850''>queues</span>
  <span m=''2672150''>are</span> <span m=''2672190''>very</span> <span m=''2672400''>simple</span>
  <span m=''2672750''>too.</span> </p><p><span m=''2674390''>So</span> <span m=''2674670''>what</span>
  <span m=''2674810''>you</span> <span m=''2674970''>see</span> <span m=''2675270''>now</span>
  <span m=''2677310''>is</span> <span m=''2677730''>that</span> <span m=''2677860''>I</span>
  <span m=''2677980''>need</span> <span m=''2678540''>a</span> <span m=''2678640''>certain</span>
  <span m=''2678940''>number</span> <span m=''2679210''>of</span> <span m=''2679450''>new</span>
  <span m=''2679690''>primitive</span> <span m=''2680110''>operations.</span> <span
  m=''2681350''>And I''m going to</span> <span m=''2681750''>give</span> <span m=''2681950''>them</span>
  <span m=''2682060''>some</span> <span m=''2682240''>names.</span> <span m=''2682560''>And</span>
  <span m=''2682880''>then</span> <span m=''2683250''>we''re going to</span> <span
  m=''2683480''>look</span> <span m=''2683620''>into</span> <span m=''2684070''>how</span>
  <span m=''2684320''>they</span> <span m=''2684500''>work,</span> <span m=''2684775''>and</span>
  <span m=''2685050''>how</span> <span m=''2685310''>they''re</span> <span m=''2685840''>used.</span>
  <span m=''2687350''>We</span> <span m=''2687460''>have</span> <span m=''2689400''>set</span>
  <span m=''2689860''>the</span> <span m=''2689960''>CAR</span> <span m=''2693150''>of</span>
  <span m=''2693670''>some</span> <span m=''2694440''>pair,</span> <span m=''2696040''>or
  a</span> <span m=''2696300''>thing</span> <span m=''2696560''>produced</span> <span
  m=''2696830''>by</span> <span m=''2696970''>CONSing,</span> <span m=''2698150''>to</span>
  <span m=''2698320''>a</span> <span m=''2698490''>new</span> <span m=''2698640''>value.</span>
  <span m=''2702370''>And</span> <span m=''2702930''>set</span> <span m=''2704360''>the</span>
  <span m=''2704710''>CDR</span> <span m=''2706770''>of</span> <span m=''2706870''>a</span>
  <span m=''2707020''>pair</span> <span m=''2708770''>to</span> <span m=''2709250''>a</span>
  <span m=''2709300''>new</span> <span m=''2709440''>value.</span> <span m=''2712680''>And</span>
  <span m=''2713140''>then</span> <span m=''2713380''>we''re</span> <span m=''2713460''>going</span>
  <span m=''2713550''>to</span> <span m=''2713650''>look</span> <span m=''2713820''>into</span>
  <span m=''2714040''>how</span> <span m=''2714250''>they</span> <span m=''2714410''>work.</span>
  </p><p><span m=''2716030''>I</span> <span m=''2716180''>needed</span> <span m=''2716520''>setting</span>
  <span m=''2716870''>CAR</span> <span m=''2717320''>over</span> <span m=''2717560''>here</span>
  <span m=''2718110''>to</span> <span m=''2718410''>delete</span> <span m=''2719300''>the</span>
  <span m=''2719510''>first</span> <span m=''2719720''>element of</span> <span m=''2720160''>the
  queue.</span> <span m=''2720960''>This</span> <span m=''2721190''>is</span> <span
  m=''2721270''>the</span> <span m=''2721360''>CAR,</span> <span m=''2721770''>and</span>
  <span m=''2721860''>I</span> <span m=''2721940''>had to</span> <span m=''2722060''>set</span>
  <span m=''2722340''>it.</span> <span m=''2723470''>I</span> <span m=''2723570''>had</span>
  <span m=''2723730''>to</span> <span m=''2723800''>be</span> <span m=''2723930''>able</span>
  <span m=''2724140''>to</span> <span m=''2724390''>set</span> <span m=''2724520''>the</span>
  <span m=''2724600''>CDR</span> <span m=''2725000''>to</span> <span m=''2725470''>be</span>
  <span m=''2725620''>able</span> <span m=''2725820''>to</span> <span m=''2725940''>move</span>
  <span m=''2726190''>the</span> <span m=''2726300''>rear</span> <span m=''2726550''>pointer,</span>
  <span m=''2726885''>or</span> <span m=''2727220''>to be</span> <span m=''2727530''>able
  to</span> <span m=''2727840''>increment the</span> <span m=''2728130''>queue here.</span>
  <span m=''2730160''>All</span> <span m=''2730300''>of</span> <span m=''2730440''>the</span>
  <span m=''2730560''>operations</span> <span m=''2731140''>I</span> <span m=''2731250''>did</span>
  <span m=''2732010''>were</span> <span m=''2732150''>made</span> <span m=''2732410''>out</span>
  <span m=''2732570''>of</span> <span m=''2732680''>those</span> <span m=''2732970''>that</span>
  <span m=''2733090''>I</span> <span m=''2733170''>just</span> <span m=''2733370''>showed</span>
  <span m=''2733480''>you</span> <span m=''2733640''>on</span> <span m=''2733810''>the,
  on the</span> <span m=''2734780''>last</span> <span m=''2735250''>blackboard.</span>
  <span m=''2738230''>Good.</span> <span m=''2738430''>Let''s</span> <span m=''2738610''>pause
  the</span> <span m=''2738850''>time, and</span> <span m=''2739050''>take</span>
  <span m=''2739260''>a</span> <span m=''2739310''>little</span> <span m=''2739470''>break</span>
  <span m=''2739860''>then.</span> </p><p><span m=''2798346''>When</span> <span m=''2798870''>we</span>
  <span m=''2799130''>originally</span> <span m=''2799540''>introduced</span> <span
  m=''2800040''>pairs</span> <span m=''2801770''>made</span> <span m=''2801970''>out</span>
  <span m=''2802100''>of</span> <span m=''2802190''>CONS,</span> <span m=''2802720''>made</span>
  <span m=''2802910''>by</span> <span m=''2803030''>CONS,</span> <span m=''2804620''>we</span>
  <span m=''2804840''>only</span> <span m=''2805090''>said</span> <span m=''2805340''>a</span>
  <span m=''2805390''>few</span> <span m=''2805620''>axioms</span> <span m=''2806140''>about</span>
  <span m=''2806490''>them,</span> <span m=''2808220''>which</span> <span m=''2808390''>were</span>
  <span m=''2808640''>of the form--</span> <span m=''2810040''>what</span> <span m=''2810250''>were</span>
  <span m=''2810460''>they--</span> <span m=''2812010''>for</span> <span m=''2812470''>all</span>
  <span m=''2812820''>X</span> <span m=''2813180''>and</span> <span m=''2813380''>Y,</span>
  <span m=''2814900''>the</span> <span m=''2815190''>CAR</span> <span m=''2816562''>of</span>
  <span m=''2816940''>the</span> <span m=''2817150''>CONS</span> <span m=''2819100''>of</span>
  <span m=''2819250''>X</span> <span m=''2819860''>and</span> <span m=''2819980''>Y</span>
  <span m=''2823160''>is</span> <span m=''2823430''>X</span> <span m=''2825320''>and</span>
  <span m=''2826040''>the</span> <span m=''2826200''>CDR</span> <span m=''2827332''>of</span>
  <span m=''2827680''>the</span> <span m=''2828230''>CONS</span> <span m=''2829810''>of</span>
  <span m=''2830160''>X</span> <span m=''2830470''>and</span> <span m=''2830580''>Y</span>
  <span m=''2832260''>is</span> <span m=''2832430''>Y.</span> <span m=''2834880''>Now,</span>
  <span m=''2835030''>these</span> <span m=''2835150''>say</span> <span m=''2835350''>nothing</span>
  <span m=''2835650''>about</span> <span m=''2835900''>whether</span> <span m=''2836220''>a</span>
  <span m=''2836300''>CONS</span> <span m=''2836880''>has</span> <span m=''2837180''>an</span>
  <span m=''2837300''>identity</span> <span m=''2839050''>like</span> <span m=''2839240''>a</span>
  <span m=''2839300''>person.</span> <span m=''2841850''>In</span> <span m=''2842160''>fact,</span>
  <span m=''2843020''>all</span> <span m=''2843290''>they</span> <span m=''2843500''>say</span>
  <span m=''2844210''>is</span> <span m=''2844370''>something</span> <span m=''2844720''>sort</span>
  <span m=''2844840''>of</span> <span m=''2844970''>abstract,</span> <span m=''2845730''>that
  a</span> <span m=''2846050''>CONS</span> <span m=''2846510''>is</span> <span m=''2846820''>the</span>
  <span m=''2846930''>parts</span> <span m=''2847310''>it''s</span> <span m=''2847440''>made</span>
  <span m=''2847660''>out</span> <span m=''2847850''>of.</span> <span m=''2849740''>And</span>
  <span m=''2849860''>of</span> <span m=''2849930''>course,</span> <span m=''2850200''>two</span>
  <span m=''2850370''>things</span> <span m=''2850660''>are</span> <span m=''2850710''>made</span>
  <span m=''2850890''>out of</span> <span m=''2851060''>the</span> <span m=''2851130''>same</span>
  <span m=''2851440''>parts,</span> <span m=''2852320''>they''re</span> <span m=''2852490''>the</span>
  <span m=''2852620''>same,</span> <span m=''2853980''>at</span> <span m=''2854110''>least</span>
  <span m=''2854240''>from</span> <span m=''2854320''>the</span> <span m=''2854410''>point</span>
  <span m=''2854580''>of</span> <span m=''2854630''>view</span> <span m=''2854840''>of
  these</span> <span m=''2855140''>axioms.</span> </p><p><span m=''2857390''>But</span>
  <span m=''2857630''>by</span> <span m=''2858030''>introducing</span> <span m=''2858520''>assignment--</span>
  <span m=''2859920''>in</span> <span m=''2860080''>fact,</span> <span m=''2860700''>mutable</span>
  <span m=''2861090''>data</span> <span m=''2861300''>is</span> <span m=''2861450''>a</span>
  <span m=''2861500''>kind</span> <span m=''2861730''>of</span> <span m=''2861790''>assignment,</span>
  <span m=''2862790''>we</span> <span m=''2863060''>have a set</span> <span m=''2863510''>CAR</span>
  <span m=''2863790''>and a set</span> <span m=''2864020''>CDR--</span> <span m=''2865590''>by</span>
  <span m=''2865740''>introducing</span> <span m=''2866170''>those,</span> <span m=''2866980''>these</span>
  <span m=''2867220''>axioms</span> <span m=''2867620''>no</span> <span m=''2867770''>longer</span>
  <span m=''2868030''>tell</span> <span m=''2868230''>the</span> <span m=''2868300''>whole</span>
  <span m=''2868480''>story.</span> <span m=''2869830''>And</span> <span m=''2870050''>they''re</span>
  <span m=''2870200''>still</span> <span m=''2870460''>true</span> <span m=''2870690''>if</span>
  <span m=''2870760''>written</span> <span m=''2871030''>exactly</span> <span m=''2871470''>like</span>
  <span m=''2871700''>this.</span> <span m=''2873250''>But</span> <span m=''2873560''>they</span>
  <span m=''2873660''>don''t</span> <span m=''2873850''>tell</span> <span m=''2874000''>the</span>
  <span m=''2874090''>whole</span> <span m=''2874330''>story.</span> <span m=''2876070''>Because</span>
  <span m=''2877110''>if</span> <span m=''2877310''>I''m</span> <span m=''2877470''>going</span>
  <span m=''2877690''>to</span> <span m=''2877780''>set</span> <span m=''2878060''>a</span>
  <span m=''2878170''>particular</span> <span m=''2879630''>CAR</span> <span m=''2880490''>in</span>
  <span m=''2880690''>a</span> <span m=''2880740''>particular</span> <span m=''2881150''>CONS,</span>
  <span m=''2883120''>the</span> <span m=''2883230''>questions</span> <span m=''2883730''>are,</span>
  <span m=''2884250''>well,</span> <span m=''2884460''>is</span> <span m=''2884610''>that</span>
  <span m=''2884810''>setting</span> <span m=''2885130''>all</span> <span m=''2885410''>CARs</span>
  <span m=''2885740''>and</span> <span m=''2885810''>all</span> <span m=''2886030''>CONSes</span>
  <span m=''2886520''>of</span> <span m=''2886640''>the</span> <span m=''2886730''>same</span>
  <span m=''2887180''>two</span> <span m=''2887430''>things</span> <span m=''2888180''>or</span>
  <span m=''2888310''>not?</span> <span m=''2890090''>If</span> <span m=''2890330''>I--if
  we</span> <span m=''2890790''>use</span> <span m=''2891010''>CONSes</span> <span
  m=''2891380''>to</span> <span m=''2891460''>make</span> <span m=''2891640''>up</span>
  <span m=''2891750''>things</span> <span m=''2891980''>like</span> <span m=''2892180''>rational</span>
  <span m=''2892610''>numbers,</span> <span m=''2895050''>or</span> <span m=''2895130''>things</span>
  <span m=''2895430''>like</span> <span m=''2896140''>3 over 4,</span> <span m=''2897250''>supposing</span>
  <span m=''2897710''>I</span> <span m=''2897920''>had</span> <span m=''2898750''>two</span>
  <span m=''2899540''>three-fourths.</span> <span m=''2901570''>Are</span> <span m=''2901780''>they
  the</span> <span m=''2902040''>same</span> <span m=''2902340''>one--</span> <span
  m=''2904110''>or are</span> <span m=''2904280''>they</span> <span m=''2904360''>different?</span>
  </p><p><span m=''2905340''>Well,</span> <span m=''2905610''>in the case of</span>
  <span m=''2905880''>numbers,</span> <span m=''2906210''>it</span> <span m=''2906320''>doesn''t</span>
  <span m=''2906600''>matter.</span> <span m=''2907860''>Because</span> <span m=''2908160''>there''s</span>
  <span m=''2908290''>no</span> <span m=''2908430''>meaning</span> <span m=''2908820''>to</span>
  <span m=''2908940''>changing</span> <span m=''2909300''>the</span> <span m=''2909410''>denominator</span>
  <span m=''2910050''>of</span> <span m=''2910130''>a</span> <span m=''2910180''>number.</span>
  <span m=''2913020''>What</span> <span m=''2913130''>you</span> <span m=''2913290''>could</span>
  <span m=''2913380''>do</span> <span m=''2913530''>is</span> <span m=''2913620''>make</span>
  <span m=''2913800''>a</span> <span m=''2913850''>number</span> <span m=''2914130''>which</span>
  <span m=''2914280''>has a</span> <span m=''2914420''>different</span> <span m=''2914670''>denominator.</span>
  <span m=''2916840''>But</span> <span m=''2916980''>the</span> <span m=''2917040''>concept</span>
  <span m=''2917500''>of</span> <span m=''2917580''>changing</span> <span m=''2918020''>a</span>
  <span m=''2918070''>number</span> <span m=''2918430''>which</span> <span m=''2918590''>has</span>
  <span m=''2918740''>to</span> <span m=''2918860''>have a</span> <span m=''2918980''>different</span>
  <span m=''2919290''>denominator</span> <span m=''2920090''>is sort of</span> <span
  m=''2920240''>a</span> <span m=''2920330''>very</span> <span m=''2920680''>weird,</span>
  <span m=''2921270''>and sort of</span> <span m=''2921570''>not</span> <span m=''2921820''>supported</span>
  <span m=''2922170''>by</span> <span m=''2922270''>what</span> <span m=''2922430''>you</span>
  <span m=''2922520''>think</span> <span m=''2922730''>of as</span> <span m=''2922910''>mathematics.</span>
  <span m=''2924770''>However,</span> <span m=''2925060''>when</span> <span m=''2925130''>these</span>
  <span m=''2925310''>CONSes</span> <span m=''2925680''>represent</span> <span m=''2926220''>things</span>
  <span m=''2926440''>in</span> <span m=''2926510''>the</span> <span m=''2926570''>physical</span>
  <span m=''2926960''>world,</span> <span m=''2928960''>then</span> <span m=''2929180''>changing</span>
  <span m=''2929570''>something</span> <span m=''2929830''>like</span> <span m=''2930020''>the</span>
  <span m=''2930040''>CAR</span> <span m=''2930640''>is</span> <span m=''2930790''>like</span>
  <span m=''2930940''>removing</span> <span m=''2931250''>a</span> <span m=''2931300''>piece</span>
  <span m=''2931510''>of the</span> <span m=''2931610''>fingernail.</span> <span m=''2933690''>And</span>
  <span m=''2933840''>so</span> <span m=''2933990''>CONSes</span> <span m=''2934440''>have</span>
  <span m=''2935750''>an</span> <span m=''2935890''>identity.</span> </p><p><span
  m=''2937770''>Let</span> <span m=''2937890''>me</span> <span m=''2937980''>show</span>
  <span m=''2938120''>you</span> <span m=''2938280''>what I</span> <span m=''2938370''>mean</span>
  <span m=''2938580''>about</span> <span m=''2938810''>identity,</span> <span m=''2939300''>first</span>
  <span m=''2939640''>of</span> <span m=''2939730''>all.</span> <span m=''2941280''>Let''s</span>
  <span m=''2941390''>do</span> <span m=''2941570''>some</span> <span m=''2942010''>little</span>
  <span m=''2942290''>example</span> <span m=''2942760''>here.</span> <span m=''2944320''>Supposing</span>
  <span m=''2944760''>I</span> <span m=''2944870''>define</span> <span m=''2950600''>A</span>
  <span m=''2951130''>to</span> <span m=''2951620''>the</span> <span m=''2951770''>CONS</span>
  <span m=''2953910''>of</span> <span m=''2954070''>1</span> <span m=''2954580''>and</span>
  <span m=''2954810''>2.</span> <span m=''2958040''>Well,</span> <span m=''2958320''>what</span>
  <span m=''2958610''>that</span> <span m=''2958810''>means,</span> <span m=''2959070''>first</span>
  <span m=''2959330''>of</span> <span m=''2959450''>all,</span> <span m=''2960920''>is</span>
  <span m=''2961030''>that</span> <span m=''2961760''>somewhere</span> <span m=''2962460''>in</span>
  <span m=''2962510''>some</span> <span m=''2962690''>environment</span> <span m=''2963780''>I''ve</span>
  <span m=''2963990''>made</span> <span m=''2964310''>a</span> <span m=''2964380''>symbol</span>
  <span m=''2964790''>A</span> <span m=''2965910''>to</span> <span m=''2966150''>have</span>
  <span m=''2966350''>a</span> <span m=''2966390''>value</span> <span m=''2967370''>which</span>
  <span m=''2967590''>is</span> <span m=''2967920''>a</span> <span m=''2968070''>pair</span>
  <span m=''2969250''>consisting</span> <span m=''2970190''>of</span> <span m=''2970430''>pointers</span>
  <span m=''2971000''>to</span> <span m=''2971560''>a</span> <span m=''2971740''>1</span>
  <span m=''2972670''>and a</span> <span m=''2972940''>pointer</span> <span m=''2973300''>to</span>
  <span m=''2973500''>a</span> <span m=''2973600''>2,</span> <span m=''2975390''>just</span>
  <span m=''2975650''>like</span> <span m=''2975850''>that.</span> <span m=''2978120''>Now,</span>
  <span m=''2978310''>supposing</span> <span m=''2978690''>I</span> <span m=''2978850''>also</span>
  <span m=''2979190''>say</span> <span m=''2979940''>define</span> <span m=''2980760''>B</span>
  <span m=''2986030''>to</span> <span m=''2986150''>be</span> <span m=''2986570''>the</span>
  <span m=''2986940''>CONS--</span> <span m=''2993320''>it</span> <span m=''2994060''>doesn''t</span>
  <span m=''2994400''>matter,</span> <span m=''2994700''>but</span> <span m=''2994830''>I</span>
  <span m=''2994880''>like</span> <span m=''2995090''>it</span> <span m=''2995170''>better,</span>
  <span m=''2995480''>it''s</span> <span m=''2995880''>prettier--</span> <span m=''2998240''>of</span>
  <span m=''2998600''>A and</span> <span m=''2998870''>A.</span> </p><p><span m=''3003970''>Well,</span>
  <span m=''3004130''>first</span> <span m=''3004400''>of</span> <span m=''3004460''>all,</span>
  <span m=''3004550''>I''m</span> <span m=''3004700''>using</span> <span m=''3004990''>the</span>
  <span m=''3005050''>name</span> <span m=''3005330''>A</span> <span m=''3005510''>twice.</span>
  <span m=''3007840''>At</span> <span m=''3008030''>this</span> <span m=''3008220''>moment,</span>
  <span m=''3008530''>I''m going</span> <span m=''3008600''>to</span> <span m=''3008820''>think</span>
  <span m=''3009000''>of</span> <span m=''3009100''>CONSes</span> <span m=''3009550''>as</span>
  <span m=''3009740''>having</span> <span m=''3010040''>identity.</span> <span m=''3011300''>This</span>
  <span m=''3011540''>is</span> <span m=''3011670''>the</span> <span m=''3011770''>same</span>
  <span m=''3012110''>one.</span> <span m=''3013690''>And</span> <span m=''3013860''>so</span>
  <span m=''3013950''>what</span> <span m=''3014080''>that</span> <span m=''3014300''>means</span>
  <span m=''3015300''>is</span> <span m=''3015460''>I</span> <span m=''3015560''>make</span>
  <span m=''3015750''>another</span> <span m=''3017140''>pair,</span> <span m=''3018790''>which</span>
  <span m=''3019040''>I''m</span> <span m=''3019200''>going to</span> <span m=''3019370''>call</span>
  <span m=''3019620''>B.</span> <span m=''3022340''>And</span> <span m=''3022620''>it</span>
  <span m=''3022850''>contains</span> <span m=''3026210''>two</span> <span m=''3026570''>pointers</span>
  <span m=''3027100''>to</span> <span m=''3027220''>A.</span> <span m=''3028940''>At</span>
  <span m=''3029120''>this</span> <span m=''3029300''>point,</span> <span m=''3029570''>I</span>
  <span m=''3029630''>have</span> <span m=''3029830''>three</span> <span m=''3030140''>names</span>
  <span m=''3031230''>for</span> <span m=''3031450''>this</span> <span m=''3031690''>object.</span>
  <span m=''3033260''>A is</span> <span m=''3033530''>its</span> <span m=''3033690''>name.</span>
  <span m=''3034790''>The</span> <span m=''3035170''>CAR of B</span> <span m=''3035590''>is</span>
  <span m=''3035880''>its</span> <span m=''3036090''>name.</span> <span m=''3037230''>And</span>
  <span m=''3037360''>the</span> <span m=''3037480''>CDR</span> <span m=''3037765''>of
  B</span> <span m=''3038050''>is</span> <span m=''3038170''>its</span> <span m=''3038320''>name.</span>
  <span m=''3039360''>It</span> <span m=''3039490''>has</span> <span m=''3039670''>several</span>
  <span m=''3039990''>aliases,</span> <span m=''3040590''>they''re</span> <span m=''3040750''>called.</span>
  </p><p><span m=''3044230''>Now,</span> <span m=''3044390''>supposing</span> <span
  m=''3045570''>I</span> <span m=''3045700''>do</span> <span m=''3045890''>something</span>
  <span m=''3046350''>like</span> <span m=''3048400''>set-the-CAR, the CAR</span>
  <span m=''3061364''>of</span> <span m=''3061860''>the</span> <span m=''3062210''>CAR
  of B</span> <span m=''3066950''>to</span> <span m=''3067560''>3.</span> <span m=''3072750''>What</span>
  <span m=''3072940''>that</span> <span m=''3073170''>means</span> <span m=''3073970''>is</span>
  <span m=''3074100''>I</span> <span m=''3074190''>find</span> <span m=''3074480''>the</span>
  <span m=''3074570''>CAR of</span> <span m=''3074930''>B,</span> <span m=''3076500''>that''s</span>
  <span m=''3077070''>this.</span> <span m=''3077830''>I</span> <span m=''3078030''>set</span>
  <span m=''3078280''>the</span> <span m=''3078360''>CAR</span> <span m=''3078700''>of
  that</span> <span m=''3078920''>to</span> <span m=''3078990''>be</span> <span m=''3079140''>3,</span>
  <span m=''3080270''>changing</span> <span m=''3080670''>this.</span> <span m=''3084760''>I''ve</span>
  <span m=''3084940''>changed</span> <span m=''3085280''>A.</span> <span m=''3087350''>If</span>
  <span m=''3087530''>I</span> <span m=''3087630''>were to</span> <span m=''3087820''>ask</span>
  <span m=''3088570''>what''s</span> <span m=''3088950''>the</span> <span m=''3089940''>CAR
  of</span> <span m=''3090250''>A--of A</span> <span m=''3093110''>now?</span> <span
  m=''3095340''>I</span> <span m=''3095460''>would</span> <span m=''3095620''>get</span>
  <span m=''3095820''>out</span> <span m=''3096890''>3,</span> <span m=''3098770''>even</span>
  <span m=''3099040''>though</span> <span m=''3099240''>here</span> <span m=''3099520''>we</span>
  <span m=''3099690''>see</span> <span m=''3100770''>that</span> <span m=''3101110''>A</span>
  <span m=''3102000''>was</span> <span m=''3102150''>the</span> <span m=''3102250''>CONS
  of</span> <span m=''3102690''>1</span> <span m=''3102890''>and</span> <span m=''3103010''>2.</span>
  </p><p><span m=''3105290''>I</span> <span m=''3105420''>caused</span> <span m=''3105700''>A
  to</span> <span m=''3105980''>change</span> <span m=''3106410''>by</span> <span
  m=''3106550''>changing</span> <span m=''3106930''>B.</span> <span m=''3108400''>There</span>
  <span m=''3108850''>is</span> <span m=''3108920''>sharing</span> <span m=''3109350''>here.</span>
  <span m=''3112010''>That''s</span> <span m=''3112510''>sometimes</span> <span m=''3112840''>what</span>
  <span m=''3112940''>we</span> <span m=''3113050''>want.</span> <span m=''3114240''>Surely</span>
  <span m=''3114770''>in</span> <span m=''3114860''>the</span> <span m=''3114960''>queues</span>
  <span m=''3115400''>and</span> <span m=''3115540''>things</span> <span m=''3115740''>like</span>
  <span m=''3115920''>that,</span> <span m=''3116270''>that''s</span> <span m=''3116400''>exactly</span>
  <span m=''3116950''>what</span> <span m=''3117130''>we</span> <span m=''3118860''>defined
  our--organized</span> <span m=''3119115''>our</span> <span m=''3119370''>data</span>
  <span m=''3119560''>structures</span> <span m=''3119960''>to</span> <span m=''3120090''>facilitate--</span>
  <span m=''3121790''>sharing.</span> <span m=''3124350''>But</span> <span m=''3124490''>inadvertent</span>
  <span m=''3125010''>sharing,</span> <span m=''3127790''>unanticipated</span> <span
  m=''3128370''>interactions</span> <span m=''3128950''>between</span> <span m=''3129220''>objects,</span>
  <span m=''3130850''>is</span> <span m=''3131010''>the</span> <span m=''3131060''>source</span>
  <span m=''3131350''>of</span> <span m=''3131470''>most</span> <span m=''3131630''>of</span>
  <span m=''3131790''>the</span> <span m=''3131870''>bugs</span> <span m=''3132590''>that</span>
  <span m=''3132750''>occur in</span> <span m=''3133100''>complicated</span> <span
  m=''3133550''>programs.</span> <span m=''3135350''>So</span> <span m=''3135540''>by</span>
  <span m=''3135700''>introducing</span> <span m=''3136280''>this</span> <span m=''3136470''>possibility</span>
  <span m=''3137820''>of</span> <span m=''3137990''>things</span> <span m=''3138210''>having</span>
  <span m=''3138460''>identity</span> <span m=''3140820''>and</span> <span m=''3140990''>sharing</span>
  <span m=''3141460''>and</span> <span m=''3141920''>having</span> <span m=''3142190''>multiple</span>
  <span m=''3142570''>names</span> <span m=''3142870''>for</span> <span m=''3142950''>the</span>
  <span m=''3143030''>same</span> <span m=''3143280''>thing,</span> <span m=''3144070''>we</span>
  <span m=''3144200''>get</span> <span m=''3144330''>a</span> <span m=''3144360''>lot</span>
  <span m=''3144530''>of</span> <span m=''3144590''>power.</span> <span m=''3145190''>But
  we''re</span> <span m=''3145320''>going</span> <span m=''3145410''>to</span> <span
  m=''3145490''>pay</span> <span m=''3145710''>for</span> <span m=''3145930''>it</span>
  <span m=''3146395''>with</span> <span m=''3146860''>lots</span> <span m=''3147330''>of</span>
  <span m=''3147390''>complexity</span> <span m=''3147970''>and</span> <span m=''3148060''>bugs.</span>
  </p><p><span m=''3152190''>So</span> <span m=''3152400''>also,</span> <span m=''3152800''>for</span>
  <span m=''3152990''>example,</span> <span m=''3153420''>if</span> <span m=''3153520''>I</span>
  <span m=''3153600''>just</span> <span m=''3153770''>looked</span> <span m=''3154030''>at</span>
  <span m=''3154140''>this</span> <span m=''3154390''>just</span> <span m=''3154570''>to</span>
  <span m=''3155430''>drive</span> <span m=''3155670''>that</span> <span m=''3155830''>home,</span>
  <span m=''3157080''>the</span> <span m=''3157320''>CADR</span> <span m=''3159110''>of</span>
  <span m=''3159280''>B,</span> <span m=''3162510''>which</span> <span m=''3162700''>has</span>
  <span m=''3162900''>nothing</span> <span m=''3163200''>to</span> <span m=''3163260''>do
  with</span> <span m=''3163480''>even</span> <span m=''3163710''>the</span> <span
  m=''3163800''>CAR</span> <span m=''3164730''>of</span> <span m=''3164910''>B,</span>
  <span m=''3165820''>apparently.</span> <span m=''3166560''>The</span> <span m=''3167040''>CADR</span>
  <span m=''3167360''>of</span> <span m=''3167490''>B,</span> <span m=''3168380''>what''s</span>
  <span m=''3168640''>that?</span> <span m=''3169350''>Take</span> <span m=''3169660''>that</span>
  <span m=''3169850''>CDR</span> <span m=''3170010''>of</span> <span m=''3170310''>B</span>
  <span m=''3171910''>and</span> <span m=''3172050''>now</span> <span m=''3172550''>take</span>
  <span m=''3172750''>the</span> <span m=''3172820''>CAR of</span> <span m=''3173120''>that.</span>
  <span m=''3173560''>Oh, that''s</span> <span m=''3173870''>3</span> <span m=''3174120''>also.</span>
  <span m=''3176480''>So</span> <span m=''3176660''>I</span> <span m=''3176760''>can
  have</span> <span m=''3177090''>non-local</span> <span m=''3177640''>interactions</span>
  <span m=''3179540''>by</span> <span m=''3179740''>sharing.</span> <span m=''3181120''>And
  I</span> <span m=''3181260''>have</span> <span m=''3181370''>to</span> <span m=''3181430''>be</span>
  <span m=''3181510''>very</span> <span m=''3181740''>careful of</span> <span m=''3182130''>that.</span>
  </p><p><span m=''3186640''>Well,</span> <span m=''3186930''>so</span> <span m=''3187180''>far,</span>
  <span m=''3187890''>of</span> <span m=''3188040''>course,</span> <span m=''3188890''>it</span>
  <span m=''3189050''>seems</span> <span m=''3189240''>I''ve</span> <span m=''3189390''>introduced</span>
  <span m=''3190050''>several</span> <span m=''3190530''>different</span> <span m=''3191610''>assignment</span>
  <span m=''3192030''>operators--</span> <span m=''3193030''>set,</span> <span m=''3194960''>set</span>
  <span m=''3195300''>CAR,</span> <span m=''3196730''>set</span> <span m=''3197090''>CDR.</span>
  <span m=''3198620''>Well,</span> <span m=''3199070''>maybe</span> <span m=''3199260''>I
  should just get</span> <span m=''3199390''>rid of</span> <span m=''3199480''>set
  CAR</span> <span m=''3200040''>and</span> <span m=''3200180''>set CDR.</span> <span
  m=''3200380''>Maybe they''re</span> <span m=''3200640''>not</span> <span m=''3200840''>worthwhile.</span>
  <span m=''3202820''>Well,</span> <span m=''3202930''>the</span> <span m=''3203080''>answer</span>
  <span m=''3203450''>is</span> <span m=''3203830''>that</span> <span m=''3204390''>once</span>
  <span m=''3204570''>you</span> <span m=''3204660''>let</span> <span m=''3204810''>the</span>
  <span m=''3204900''>camel''s</span> <span m=''3205230''>nose</span> <span m=''3205520''>into</span>
  <span m=''3205680''>the</span> <span m=''3205850''>tent,</span> <span m=''3206240''>the</span>
  <span m=''3206410''>rest</span> <span m=''3206650''>of</span> <span m=''3206710''>him</span>
  <span m=''3206860''>follows.</span> <span m=''3210160''>All</span> <span m=''3210440''>I</span>
  <span m=''3210540''>have</span> <span m=''3210650''>to</span> <span m=''3210750''>have</span>
  <span m=''3210880''>is</span> <span m=''3211000''>set,</span> <span m=''3211310''>and</span>
  <span m=''3211620''>I</span> <span m=''3211810''>can</span> <span m=''3211950''>make</span>
  <span m=''3212120''>all</span> <span m=''3212430''>of</span> <span m=''3214480''>the--all
  of the</span> <span m=''3214660''>bad</span> <span m=''3214990''>things</span> <span
  m=''3215240''>that</span> <span m=''3215330''>can</span> <span m=''3215420''>happen.</span>
  </p><p><span m=''3218550''>Let''s</span> <span m=''3218710''>play</span> <span m=''3218910''>with
  that</span> <span m=''3219190''>a</span> <span m=''3219230''>little</span> <span
  m=''3219440''>bit.</span> <span m=''3220690''>A</span> <span m=''3220820''>couple</span>
  <span m=''3221090''>of</span> <span m=''3221180''>days</span> <span m=''3221450''>ago,</span>
  <span m=''3221740''>when we</span> <span m=''3221910''>introduced</span> <span m=''3222860''>compound</span>
  <span m=''3223380''>data,</span> <span m=''3225170''>you</span> <span m=''3225330''>saw</span>
  <span m=''3225860''>Hal</span> <span m=''3226380''>show</span> <span m=''3226650''>you</span>
  <span m=''3227950''>a</span> <span m=''3228510''>definition</span> <span m=''3229030''>of</span>
  <span m=''3229130''>CONS</span> <span m=''3229580''>in</span> <span m=''3229730''>terms</span>
  <span m=''3229980''>of</span> <span m=''3230080''>a</span> <span m=''3230160''>message</span>
  <span m=''3230570''>acceptor.</span> <span m=''3232480''>I''m going</span> <span
  m=''3232870''>to show you</span> <span m=''3233020''>even</span> <span m=''3234860''>a</span>
  <span m=''3235090''>more</span> <span m=''3235260''>horrible</span> <span m=''3235740''>thing,</span>
  <span m=''3236880''>a</span> <span m=''3237280''>definition</span> <span m=''3237680''>of
  CONS</span> <span m=''3238110''>in terms</span> <span m=''3238290''>of</span> <span
  m=''3238400''>nothing</span> <span m=''3239600''>but</span> <span m=''3239730''>air,</span>
  <span m=''3242590''>hot</span> <span m=''3242800''>air.</span> <span m=''3244440''>What</span>
  <span m=''3244630''>is</span> <span m=''3244960''>the</span> <span m=''3245050''>definition</span>
  <span m=''3245470''>of</span> <span m=''3245540''>CONS,</span> <span m=''3246320''>of</span>
  <span m=''3246470''>the</span> <span m=''3246900''>old</span> <span m=''3247170''>functional</span>
  <span m=''3247640''>kind,</span> <span m=''3249300''>in</span> <span m=''3249470''>terms</span>
  <span m=''3249820''>of</span> <span m=''3250260''>purely</span> <span m=''3250600''>lambdic</span>
  <span m=''3250930''>expressions,</span> <span m=''3253330''>procedures?</span> <span
  m=''3257190''>Because</span> <span m=''3257610''>I''m</span> <span m=''3257720''>going
  to</span> <span m=''3257850''>then</span> <span m=''3258270''>modify</span> <span
  m=''3258720''>this</span> <span m=''3258900''>definition</span> <span m=''3260280''>to</span>
  <span m=''3260400''>get</span> <span m=''3260630''>assignment</span> <span m=''3261380''>to</span>
  <span m=''3261640''>be</span> <span m=''3261800''>only</span> <span m=''3262030''>one</span>
  <span m=''3262300''>kind</span> <span m=''3262560''>of</span> <span m=''3262630''>assignment,</span>
  <span m=''3264250''>to</span> <span m=''3264430''>get</span> <span m=''3264620''>rid</span>
  <span m=''3264780''>of</span> <span m=''3265020''>the</span> <span m=''3265650''>set</span>
  <span m=''3265930''>CAR</span> <span m=''3266280''>and set CDR</span> <span m=''3266630''>in</span>
  <span m=''3266750''>terms</span> <span m=''3267070''>of</span> <span m=''3267490''>set.</span>
  </p><p><span m=''3268580''>So</span> <span m=''3268840''>what if</span> <span m=''3268930''>I</span>
  <span m=''3269020''>define</span> <span m=''3273420''>CONS</span> <span m=''3275406''>of</span>
  <span m=''3276370''>X</span> <span m=''3276720''>and</span> <span m=''3276940''>Y</span>
  <span m=''3278560''>to</span> <span m=''3279040''>be</span> <span m=''3279290''>a</span>
  <span m=''3279420''>procedure</span> <span m=''3280430''>of</span> <span m=''3280800''>one</span>
  <span m=''3281020''>argument</span> <span m=''3281380''>called</span> <span m=''3281670''>a</span>
  <span m=''3281720''>message</span> <span m=''3282160''>M,</span> <span m=''3283550''>which</span>
  <span m=''3283760''>calls</span> <span m=''3284080''>that</span> <span m=''3284310''>message</span>
  <span m=''3285050''>on</span> <span m=''3285340''>X</span> <span m=''3285650''>and</span>
  <span m=''3285910''>Y?</span> <span m=''3291120''>This</span> <span m=''3291340''>[?
  idea ?]</span> <span m=''3291630''>was</span> <span m=''3291750''>invented</span>
  <span m=''3292050''>by</span> <span m=''3292160''>Alonzo</span> <span m=''3292590''>Church,</span>
  <span m=''3293860''>who was the</span> <span m=''3294080''>greatest</span> <span
  m=''3294370''>programmer</span> <span m=''3294890''>of</span> <span m=''3294950''>the</span>
  <span m=''3295000''>20th</span> <span m=''3295300''>century,</span> <span m=''3295800''>although</span>
  <span m=''3296090''>he</span> <span m=''3296180''>never</span> <span m=''3296420''>saw
  a</span> <span m=''3296600''>computer.</span> <span m=''3297870''>It was</span>
  <span m=''3297980''>done</span> <span m=''3298140''>in</span> <span m=''3298220''>the</span>
  <span m=''3298290''>1930s.</span> <span m=''3299130''>He was</span> <span m=''3299520''>a
  logician,</span> <span m=''3300650''>I</span> <span m=''3300780''>suppose</span>
  <span m=''3301110''>at</span> <span m=''3301330''>Princeton</span> <span m=''3301680''>at</span>
  <span m=''3301820''>the</span> <span m=''3301910''>time.</span> <span m=''3308660''>Define</span>
  <span m=''3309660''>CAR of</span> <span m=''3309990''>X</span> <span m=''3313290''>to</span>
  <span m=''3313380''>be</span> <span m=''3313520''>the</span> <span m=''3313610''>result</span>
  <span m=''3313930''>of</span> <span m=''3314030''>applying</span> <span m=''3314380''>X</span>
  <span m=''3315300''>to</span> <span m=''3315440''>that</span> <span m=''3315690''>procedure</span>
  <span m=''3316200''>of</span> <span m=''3316300''>two</span> <span m=''3316510''>arguments,</span>
  <span m=''3317390''>A</span> <span m=''3317690''>and</span> <span m=''3317990''>D,</span>
  <span m=''3319310''>which</span> <span m=''3319650''>selects</span> <span m=''3320270''>A.</span>
  <span m=''3323790''>I</span> <span m=''3323860''>will</span> <span m=''3324000''>define</span>
  <span m=''3324350''>CDR of</span> <span m=''3324630''>X</span> <span m=''3332890''>to</span>
  <span m=''3333730''>be</span> <span m=''3333850''>that</span> <span m=''3334090''>procedure,</span>
  <span m=''3334780''>to</span> <span m=''3335260''>be</span> <span m=''3335370''>the</span>
  <span m=''3335460''>result</span> <span m=''3335930''>of</span> <span m=''3336410''>applying</span>
  <span m=''3336870''>X</span> <span m=''3337410''>to</span> <span m=''3337710''>that</span>
  <span m=''3337960''>procedure</span> <span m=''3338870''>of</span> <span m=''3339180''>A</span>
  <span m=''3339490''>and</span> <span m=''3339770''>D,</span> <span m=''3340580''>which</span>
  <span m=''3341030''>selects</span> <span m=''3341500''>D.</span> </p><p><span m=''3346670''>Now,</span>
  <span m=''3346770''>you</span> <span m=''3346900''>may</span> <span m=''3347030''>not</span>
  <span m=''3347800''>recognize</span> <span m=''3348340''>this</span> <span m=''3348740''>as</span>
  <span m=''3348900''>CAR,</span> <span m=''3349330''>CDR, and</span> <span m=''3349430''>CONS.</span>
  <span m=''3350510''>But I''m</span> <span m=''3350790''>going to</span> <span m=''3350950''>demonstrate</span>
  <span m=''3351420''>to</span> <span m=''3351500''>you</span> <span m=''3351590''>that
  it</span> <span m=''3351800''>satisfies</span> <span m=''3352540''>the</span> <span
  m=''3352690''>original</span> <span m=''3353040''>axioms,</span> <span m=''3354140''>just</span>
  <span m=''3354440''>once.</span> <span m=''3355210''>And</span> <span m=''3355610''>then</span>
  <span m=''3356010''>we''re going</span> <span m=''3356360''>to do some</span> <span
  m=''3356530''>playing</span> <span m=''3356790''>of</span> <span m=''3357050''>games.</span>
  <span m=''3358290''>Consider</span> <span m=''3358680''>the</span> <span m=''3358770''>problem</span>
  <span m=''3359200''>CAR</span> <span m=''3360840''>of</span> <span m=''3361270''>CONS</span>
  <span m=''3363440''>of,</span> <span m=''3363980''>say,</span> <span m=''3364250''>35</span>
  <span m=''3365480''>and</span> <span m=''3365650''>47.</span> <span m=''3369695''>Well,</span>
  <span m=''3370170''>what</span> <span m=''3370430''>is</span> <span m=''3370570''>that?</span>
  <span m=''3371120''>It is</span> <span m=''3371360''>the</span> <span m=''3371460''>result</span>
  <span m=''3371750''>of</span> <span m=''3372580''>taking</span> <span m=''3372820''>car</span>
  <span m=''3373160''>of</span> <span m=''3373240''>the</span> <span m=''3373320''>result</span>
  <span m=''3373620''>of</span> <span m=''3373680''>substituting</span> <span m=''3374080''>35</span>
  <span m=''3374290''>and</span> <span m=''3374590''>47</span> <span m=''3375370''>for</span>
  <span m=''3375540''>X</span> <span m=''3375840''>and</span> <span m=''3375990''>Y</span>
  <span m=''3376630''>in</span> <span m=''3376990''>the</span> <span m=''3377410''>body</span>
  <span m=''3377760''>of</span> <span m=''3377830''>this.</span> <span m=''3379710''>Well,</span>
  <span m=''3379920''>that''s</span> <span m=''3380070''>easy</span> <span m=''3380280''>enough.</span>
  <span m=''3380690''>That''s</span> <span m=''3381060''>CAR</span> <span m=''3383332''>of</span>
  <span m=''3383750''>the</span> <span m=''3384130''>result</span> <span m=''3384560''>of</span>
  <span m=''3384630''>substituting</span> <span m=''3385690''>into</span> <span m=''3385970''>lambda</span>
  <span m=''3386310''>of</span> <span m=''3386550''>M,</span> <span m=''3387780''>M</span>
  <span m=''3388800''>of</span> <span m=''3388980''>35</span> <span m=''3389940''>and</span>
  <span m=''3390140''>47.</span> </p><p><span m=''3395750''>Well,</span> <span m=''3396220''>what</span>
  <span m=''3396300''>this</span> <span m=''3396490''>is,</span> <span m=''3396650''>is</span>
  <span m=''3396710''>the</span> <span m=''3396830''>result</span> <span m=''3397160''>of</span>
  <span m=''3397240''>substituting</span> <span m=''3397640''>this</span> <span m=''3398680''>object</span>
  <span m=''3399450''>for</span> <span m=''3399880''>X</span> <span m=''3400670''>in</span>
  <span m=''3400880''>the</span> <span m=''3400960''>body</span> <span m=''3401290''>of</span>
  <span m=''3401370''>that.</span> <span m=''3402830''>So</span> <span m=''3402990''>that''s</span>
  <span m=''3403260''>just</span> <span m=''3404720''>lambda</span> <span m=''3406170''>of</span>
  <span m=''3407020''>M--</span> <span m=''3408930''>that''s substituted,</span> <span
  m=''3409300''>because</span> <span m=''3410020''>this</span> <span m=''3410350''>object</span>
  <span m=''3410800''>is</span> <span m=''3410900''>being</span> <span m=''3411090''>substituted</span>
  <span m=''3411440''>for</span> <span m=''3411600''>X,</span> <span m=''3412920''>which</span>
  <span m=''3413070''>is</span> <span m=''3413240''>the</span> <span m=''3413340''>beginning</span>
  <span m=''3413780''>of</span> <span m=''3413860''>a</span> <span m=''3413920''>list,</span>
  <span m=''3414980''>lambda of</span> <span m=''3415420''>M--</span> <span m=''3417260''>M</span>
  <span m=''3417610''>of</span> <span m=''3417820''>35</span> <span m=''3418810''>and</span>
  <span m=''3419280''>47,</span> <span m=''3423160''>applied</span> <span m=''3423630''>to</span>
  <span m=''3424080''>that</span> <span m=''3424520''>procedure</span> <span m=''3425430''>of</span>
  <span m=''3425880''>A</span> <span m=''3426270''>and</span> <span m=''3426610''>D,</span>
  <span m=''3427570''>which</span> <span m=''3427750''>gives</span> <span m=''3427960''>me</span>
  <span m=''3428110''>A.</span> <span m=''3431030''>Well,</span> <span m=''3431140''>that''s</span>
  <span m=''3431390''>the</span> <span m=''3431470''>result</span> <span m=''3431870''>of</span>
  <span m=''3432000''>substituting</span> <span m=''3432280''>this</span> <span m=''3433020''>for</span>
  <span m=''3433450''>M</span> <span m=''3434010''>here.</span> <span m=''3435840''>So</span>
  <span m=''3436100''>that''s</span> <span m=''3436380''>the</span> <span m=''3436450''>same</span>
  <span m=''3436710''>thing</span> <span m=''3437060''>as</span> <span m=''3437930''>lambda</span>
  <span m=''3438290''>of</span> <span m=''3438760''>A,</span> <span m=''3439470''>D,</span>
  <span m=''3441230''>A,</span> <span m=''3442320''>applied</span> <span m=''3442690''>to</span>
  <span m=''3442780''>35</span> <span m=''3443740''>and</span> <span m=''3444070''>47.</span>
  <span m=''3446026''>Oh, well</span> <span m=''3446450''>that''s</span> <span m=''3446780''>35.</span>
  <span m=''3447560''>That''s</span> <span m=''3447940''>substituting</span> <span
  m=''3448150''>35</span> <span m=''3448700''>for</span> <span m=''3448890''>A</span>
  <span m=''3449210''>and</span> <span m=''3449430''>for</span> <span m=''3449600''>47</span>
  <span m=''3450100''>for</span> <span m=''3450270''>D</span> <span m=''3450540''>in</span>
  <span m=''3450820''>A.</span> <span m=''3455520''>So</span> <span m=''3455880''>I</span>
  <span m=''3456000''>don''t</span> <span m=''3456110''>need</span> <span m=''3456270''>any</span>
  <span m=''3456460''>data</span> <span m=''3456770''>at</span> <span m=''3456960''>all,</span>
  <span m=''3457900''>not</span> <span m=''3458070''>even</span> <span m=''3458330''>numbers.</span>
  <span m=''3460720''>This</span> <span m=''3461210''>is</span> <span m=''3461310''>Alonso</span>
  <span m=''3461820''>Church''s</span> <span m=''3462250''>hack.</span> </p><p><span
  m=''3472420''>Well,</span> <span m=''3472630''>now</span> <span m=''3474550''>we''re</span>
  <span m=''3474730''>going</span> <span m=''3474840''>to do</span> <span m=''3474950''>something</span>
  <span m=''3475250''>nasty</span> <span m=''3475670''>to</span> <span m=''3475780''>him.</span>
  <span m=''3476760''>Being a</span> <span m=''3476970''>logician,</span> <span m=''3477320''>he</span>
  <span m=''3477490''>wouldn''t</span> <span m=''3477670''>like</span> <span m=''3478010''>this.</span>
  <span m=''3478860''>But</span> <span m=''3479450''>as</span> <span m=''3479550''>programmers,</span>
  <span m=''3480860''>let''s</span> <span m=''3481060''>look</span> <span m=''3481140''>at</span>
  <span m=''3481230''>the</span> <span m=''3481360''>overhead.</span> <span m=''3483260''>And</span>
  <span m=''3483430''>here</span> <span m=''3483580''>we</span> <span m=''3483700''>go.</span>
  <span m=''3485390''>I''m</span> <span m=''3485730''>going</span> <span m=''3485930''>to</span>
  <span m=''3486020''>change</span> <span m=''3486420''>the</span> <span m=''3486480''>definition</span>
  <span m=''3486930''>of</span> <span m=''3487030''>CONS.</span> <span m=''3489570''>It''s</span>
  <span m=''3489800''>almost</span> <span m=''3490190''>the</span> <span m=''3490290''>same</span>
  <span m=''3490560''>as</span> <span m=''3490640''>Alonzo</span> <span m=''3491020''>Church''s,</span>
  <span m=''3491430''>but</span> <span m=''3491580''>not</span> <span m=''3491810''>quite.</span>
  <span m=''3494520''>What do</span> <span m=''3494670''>we</span> <span m=''3494860''>have</span>
  <span m=''3495060''>here?</span> <span m=''3496070''>The</span> <span m=''3496330''>CONS</span>
  <span m=''3496760''>of two</span> <span m=''3496960''>arguments,</span> <span m=''3497650''>X</span>
  <span m=''3497910''>and</span> <span m=''3498080''>Y,</span> <span m=''3499250''>is</span>
  <span m=''3499740''>going</span> <span m=''3499990''>to</span> <span m=''3500120''>be</span>
  <span m=''3500550''>that</span> <span m=''3500880''>procedure</span> <span m=''3501370''>of</span>
  <span m=''3501520''>one</span> <span m=''3501670''>argument</span> <span m=''3502090''>M,</span>
  <span m=''3503420''>which</span> <span m=''3503590''>supplies</span> <span m=''3504040''>M
  to</span> <span m=''3504340''>X</span> <span m=''3504560''>and</span> <span m=''3504660''>Y</span>
  <span m=''3504900''>as</span> <span m=''3505020''>before,</span> <span m=''3505920''>but</span>
  <span m=''3506420''>also</span> <span m=''3507980''>to</span> <span m=''3508350''>two</span>
  <span m=''3508540''>permissions,</span> <span m=''3509880''>the</span> <span m=''3510330''>permission</span>
  <span m=''3510800''>to</span> <span m=''3510900''>set</span> <span m=''3511190''>X</span>
  <span m=''3511580''>to N</span> <span m=''3512650''>and</span> <span m=''3512810''>the</span>
  <span m=''3512900''>permission</span> <span m=''3513165''>to</span> <span m=''3513430''>set</span>
  <span m=''3513610''>Y</span> <span m=''3513930''>to N,</span> <span m=''3514530''>given</span>
  <span m=''3514790''>that</span> <span m=''3514920''>I</span> <span m=''3515030''>have</span>
  <span m=''3515230''>an</span> <span m=''3515310''>N.</span> </p><p><span m=''3520940''>So</span>
  <span m=''3521220''>besides</span> <span m=''3521890''>the</span> <span m=''3522040''>things</span>
  <span m=''3522390''>that I</span> <span m=''3522490''>had</span> <span m=''3522740''>here</span>
  <span m=''3523320''>in</span> <span m=''3523590''>Church''s</span> <span m=''3524040''>definition,</span>
  <span m=''3525840''>what</span> <span m=''3525980''>I</span> <span m=''3526070''>have</span>
  <span m=''3526900''>is</span> <span m=''3527180''>that</span> <span m=''3527950''>the</span>
  <span m=''3528770''>thing</span> <span m=''3529380''>that</span> <span m=''3530600''>CONS</span>
  <span m=''3530990''>returns</span> <span m=''3532160''>will</span> <span m=''3532440''>apply</span>
  <span m=''3532870''>its</span> <span m=''3533150''>argument</span> <span m=''3534710''>to</span>
  <span m=''3535290''>not</span> <span m=''3535580''>just</span> <span m=''3535790''>the</span>
  <span m=''3535900''>values</span> <span m=''3536520''>of</span> <span m=''3536880''>the</span>
  <span m=''3537060''>X</span> <span m=''3537290''>and</span> <span m=''3537400''>Y</span>
  <span m=''3537890''>that</span> <span m=''3538460''>the</span> <span m=''3538540''>CONS</span>
  <span m=''3538840''>is</span> <span m=''3538930''>made</span> <span m=''3539220''>of,</span>
  <span m=''3539740''>but</span> <span m=''3539890''>also</span> <span m=''3540210''>permissions</span>
  <span m=''3540690''>to</span> <span m=''3540820''>set</span> <span m=''3541740''>X</span>
  <span m=''3542000''>and</span> <span m=''3542200''>Y</span> <span m=''3542760''>to</span>
  <span m=''3542890''>new</span> <span m=''3543050''>values.</span> <span m=''3546540''>Now,</span>
  <span m=''3546730''>of</span> <span m=''3546890''>course,</span> <span m=''3547060''>just</span>
  <span m=''3547270''>as</span> <span m=''3547500''>before,</span> <span m=''3548840''>CAR</span>
  <span m=''3549220''>is</span> <span m=''3549360''>exactly</span> <span m=''3549890''>the</span>
  <span m=''3550000''>same.</span> <span m=''3551690''>The</span> <span m=''3551910''>CAR</span>
  <span m=''3552270''>of X</span> <span m=''3552570''>is</span> <span m=''3552720''>nothing</span>
  <span m=''3553020''>more</span> <span m=''3553400''>than</span> <span m=''3553680''>applying</span>
  <span m=''3554230''>X,</span> <span m=''3554590''>as</span> <span m=''3554860''>in</span>
  <span m=''3554980''>Church''s</span> <span m=''3555280''>definition,</span> <span
  m=''3556800''>to</span> <span m=''3557150''>a</span> <span m=''3557240''>procedure,</span>
  <span m=''3557620''>in</span> <span m=''3557690''>this</span> <span m=''3557810''>case,</span>
  <span m=''3557990''>of</span> <span m=''3558110''>four</span> <span m=''3558360''>arguments,</span>
  <span m=''3559360''>which</span> <span m=''3559580''>selects</span> <span m=''3559950''>out</span>
  <span m=''3560120''>the</span> <span m=''3560200''>first</span> <span m=''3560470''>one.</span>
  <span m=''3562550''>And</span> <span m=''3562860''>just</span> <span m=''3563060''>as</span>
  <span m=''3563130''>we</span> <span m=''3563260''>did</span> <span m=''3563440''>before,</span>
  <span m=''3565360''>that</span> <span m=''3565690''>will</span> <span m=''3565770''>be</span>
  <span m=''3565910''>the</span> <span m=''3566010''>value</span> <span m=''3566410''>of</span>
  <span m=''3566510''>X</span> <span m=''3568750''>that</span> <span m=''3569200''>was</span>
  <span m=''3569800''>contained</span> <span m=''3570330''>in</span> <span m=''3570770''>the</span>
  <span m=''3571580''>procedure</span> <span m=''3572650''>which</span> <span m=''3572860''>is</span>
  <span m=''3572940''>the</span> <span m=''3573050''>result</span> <span m=''3573470''>of</span>
  <span m=''3573580''>evaluating</span> <span m=''3574200''>this</span> <span m=''3574410''>lambda</span>
  <span m=''3574730''>expression</span> <span m=''3575530''>in</span> <span m=''3575660''>the</span>
  <span m=''3575800''>environment</span> <span m=''3576260''>where</span> <span m=''3576400''>X
  and</span> <span m=''3576730''>Y are</span> <span m=''3577070''>defined</span> <span
  m=''3577470''>over</span> <span m=''3577620''>here.</span> <span m=''3581940''>That''s</span>
  <span m=''3582220''>the</span> <span m=''3582320''>value</span> <span m=''3582680''>of</span>
  <span m=''3582770''>CONS.</span> </p><p><span m=''3585640''>Now,</span> <span m=''3586130''>however,</span>
  <span m=''3586540''>the</span> <span m=''3586700''>exciting</span> <span m=''3587190''>part.</span>
  <span m=''3587730''>CDR,</span> <span m=''3587990''>of</span> <span m=''3588070''>course,</span>
  <span m=''3588350''>is the</span> <span m=''3588440''>same.</span> <span m=''3588960''>The</span>
  <span m=''3589530''>exciting</span> <span m=''3590000''>part,</span> <span m=''3591210''>set</span>
  <span m=''3591550''>CAR and</span> <span m=''3591880''>set CDR.</span> <span m=''3593570''>Well,</span>
  <span m=''3593820''>they''re</span> <span m=''3593960''>nothing</span> <span m=''3594270''>very</span>
  <span m=''3594450''>complicated</span> <span m=''3594960''>anymore.</span> <span
  m=''3595800''>Set</span> <span m=''3596190''>CAR</span> <span m=''3596640''>of</span>
  <span m=''3597150''>a</span> <span m=''3597350''>CONS</span> <span m=''3597835''>X</span>
  <span m=''3598920''>to</span> <span m=''3599050''>a</span> <span m=''3599170''>new</span>
  <span m=''3599640''>value</span> <span m=''3600030''>Y</span> <span m=''3601600''>is</span>
  <span m=''3601850''>nothing</span> <span m=''3602170''>more</span> <span m=''3602510''>than</span>
  <span m=''3602700''>applying</span> <span m=''3603210''>that</span> <span m=''3603450''>CONS,</span>
  <span m=''3604080''>which</span> <span m=''3604290''>is</span> <span m=''3604360''>the</span>
  <span m=''3604460''>procedure</span> <span m=''3605910''>of</span> <span m=''3606060''>four--the
  procedure of one</span> <span m=''3606210''>argument</span> <span m=''3607760''>which</span>
  <span m=''3607960''>applies</span> <span m=''3608370''>its</span> <span m=''3608590''>argument</span>
  <span m=''3609000''>to four</span> <span m=''3609320''>things,</span> <span m=''3611290''>to</span>
  <span m=''3611780''>a</span> <span m=''3611910''>procedure</span> <span m=''3613620''>which</span>
  <span m=''3613860''>is</span> <span m=''3614310''>of</span> <span m=''3614790''>four</span>
  <span m=''3615180''>arguments--</span> <span m=''3615950''>the</span> <span m=''3616210''>value</span>
  <span m=''3616475''>of</span> <span m=''3616740''>X,</span> <span m=''3617080''>the</span>
  <span m=''3617180''>value</span> <span m=''3617620''>of</span> <span m=''3617720''>Y,</span>
  <span m=''3618270''>permission</span> <span m=''3618710''>to</span> <span m=''3618780''>set</span>
  <span m=''3619050''>X,</span> <span m=''3619370''>the</span> <span m=''3619450''>permission</span>
  <span m=''3619820''>to</span> <span m=''3619900''>set</span> <span m=''3620130''>Y--</span>
  <span m=''3621390''>and</span> <span m=''3621590''>using</span> <span m=''3622670''>it--using
  that</span> <span m=''3622850''>permission</span> <span m=''3623220''>to</span>
  <span m=''3623300''>set</span> <span m=''3623610''>X</span> <span m=''3624940''>to</span>
  <span m=''3625460''>the</span> <span m=''3625540''>new</span> <span m=''3625670''>value.</span>
  <span m=''3631650''>And</span> <span m=''3631860''>similarly,</span> <span m=''3632230''>set-cdr</span>
  <span m=''3632780''>is</span> <span m=''3632880''>the</span> <span m=''3632960''>same</span>
  <span m=''3633250''>thing.</span> </p><p><span m=''3636120''>So what</span> <span
  m=''3636530''>you''ve</span> <span m=''3636710''>just</span> <span m=''3637000''>seen</span>
  <span m=''3637360''>is</span> <span m=''3637510''>that</span> <span m=''3637620''>I</span>
  <span m=''3637760''>didn''t</span> <span m=''3637910''>introduce</span> <span m=''3638330''>any</span>
  <span m=''3638470''>new</span> <span m=''3638600''>primitives</span> <span m=''3639020''>at</span>
  <span m=''3639110''>all.</span> <span m=''3640470''>Whether</span> <span m=''3640760''>or</span>
  <span m=''3640810''>not</span> <span m=''3641000''>I</span> <span m=''3641070''>want</span>
  <span m=''3641270''>to</span> <span m=''3641310''>implement</span> <span m=''3641770''>it</span>
  <span m=''3641860''>this</span> <span m=''3642070''>way</span> <span m=''3643130''>is</span>
  <span m=''3643290''>a</span> <span m=''3643340''>matter</span> <span m=''3643630''>of</span>
  <span m=''3643720''>engineering.</span> <span m=''3645340''>And</span> <span m=''3645480''>the</span>
  <span m=''3645610''>answer is</span> <span m=''3645880''>of</span> <span m=''3645960''>course</span>
  <span m=''3646260''>I</span> <span m=''3646360''>don''t</span> <span m=''3646470''>implement</span>
  <span m=''3646820''>it</span> <span m=''3646890''>this</span> <span m=''3647090''>way</span>
  <span m=''3648080''>for</span> <span m=''3648260''>reasons</span> <span m=''3648610''>that
  have</span> <span m=''3648840''>to</span> <span m=''3648910''>do</span> <span m=''3649020''>with</span>
  <span m=''3649150''>engineering.</span> <span m=''3651680''>However</span> <span
  m=''3652090''>in</span> <span m=''3652200''>principle,</span> <span m=''3652790''>logically,</span>
  <span m=''3654370''>once</span> <span m=''3654630''>I</span> <span m=''3654710''>introduced</span>
  <span m=''3655170''>one</span> <span m=''3655400''>assignment</span> <span m=''3655870''>operator,</span>
  <span m=''3657070''>I''ve</span> <span m=''3657280''>assigned--I''ve introduced</span>
  <span m=''3657750''>them all.</span> <span m=''3665420''>Are</span> <span m=''3665530''>there</span>
  <span m=''3665690''>any</span> <span m=''3665800''>questions?</span> <span m=''3669200''>Yes,</span>
  <span m=''3669940''>David.</span> </p><p><span m=''3672040''>AUDIENCE: I</span>
  <span m=''3672370''>can</span> <span m=''3672640''>follow you up until you get--I
  can follow</span> <span m=''3674860''>all</span> <span m=''3675170''>of</span> <span
  m=''3675480''>that.</span> <span m=''3675740''>But when we</span> <span m=''3676110''>bring</span>
  <span m=''3676370''>in</span> <span m=''3676540''>the</span> <span m=''3676730''>permissions,</span>
  <span m=''3678690''>defining</span> <span m=''3679150''>CONS</span> <span m=''3679640''>in</span>
  <span m=''3679760''>terms</span> <span m=''3680390''>of</span> <span m=''3680740''>the</span>
  <span m=''3680850''>lambda</span> <span m=''3681210''>N,</span> <span m=''3682160''>I</span>
  <span m=''3682250''>don''t</span> <span m=''3682470''>follow</span> <span m=''3682710''>where</span>
  <span m=''3683050''>N</span> <span m=''3683210''>gets</span> <span m=''3683450''>passed.</span>
  </p><p><span m=''3684210''>PROFESSOR: Oh,</span> <span m=''3684580''>I''m</span>
  <span m=''3684770''>sorry.</span> <span m=''3685100''>I''ll</span> <span m=''3685250''>show</span>
  <span m=''3685420''>you.</span> <span m=''3686340''>Let''s</span> <span m=''3686540''>follow</span>
  <span m=''3686820''>it.</span> <span m=''3687360''>Of</span> <span m=''3687500''>course,</span>
  <span m=''3687640''>we</span> <span m=''3687760''>could</span> <span m=''3687960''>do</span>
  <span m=''3688100''>it</span> <span m=''3688160''>on</span> <span m=''3688270''>the</span>
  <span m=''3688320''>blackboard.</span> <span m=''3689180''>It''s</span> <span m=''3689280''>not</span>
  <span m=''3689440''>so</span> <span m=''3689570''>hard.</span> <span m=''3690170''>But</span>
  <span m=''3690380''>it''s</span> <span m=''3690470''>also</span> <span m=''3690730''>easy</span>
  <span m=''3690990''>here.</span> </p><p><span m=''3692450''>Supposing</span> <span
  m=''3692910''>I</span> <span m=''3693010''>wish</span> <span m=''3693190''>to</span>
  <span m=''3693310''>set-cdr</span> <span m=''3694290''>of</span> <span m=''3694530''>X</span>
  <span m=''3695180''>to</span> <span m=''3695340''>Y.</span> <span m=''3697830''>See</span>
  <span m=''3698020''>that</span> <span m=''3698190''>right</span> <span m=''3698400''>there.</span>
  <span m=''3698520''>set-cdr</span> <span m=''3699020''>of X</span> <span m=''3699300''>to
  Y.</span> <span m=''3700450''>X</span> <span m=''3700710''>is</span> <span m=''3700850''>presumably</span>
  <span m=''3701400''>a</span> <span m=''3701460''>CONS,</span> <span m=''3703360''>a</span>
  <span m=''3703520''>thing</span> <span m=''3703680''>resulting</span> <span m=''3704130''>from</span>
  <span m=''3704230''>evaluating</span> <span m=''3704770''>CONS.</span> <span m=''3706890''>Therefore</span>
  <span m=''3707490''>X</span> <span m=''3708290''>comes from</span> <span m=''3708565''>a</span>
  <span m=''3708840''>place</span> <span m=''3709140''>over</span> <span m=''3709370''>here,</span>
  <span m=''3713170''>that that</span> <span m=''3713430''>X</span> <span m=''3713710''>is</span>
  <span m=''3713880''>of</span> <span m=''3714030''>the</span> <span m=''3714190''>result</span>
  <span m=''3714640''>of</span> <span m=''3714770''>evaluating</span> <span m=''3715380''>this</span>
  <span m=''3715570''>lambda</span> <span m=''3715860''>expression.</span> <span m=''3718110''>Right?</span>
  <span m=''3719380''>That</span> <span m=''3719760''>when</span> <span m=''3719880''>I</span>
  <span m=''3720070''>evaluated</span> <span m=''3720490''>that</span> <span m=''3720690''>lambda</span>
  <span m=''3720940''>expression,</span> <span m=''3724040''>I</span> <span m=''3724210''>evaluated</span>
  <span m=''3724475''>it</span> <span m=''3724740''>in</span> <span m=''3724930''>an</span>
  <span m=''3725110''>environment</span> <span m=''3726050''>where</span> <span m=''3726490''>the</span>
  <span m=''3727240''>arguments</span> <span m=''3727700''>to</span> <span m=''3727800''>CONS</span>
  <span m=''3728140''>were</span> <span m=''3728250''>defined.</span> </p><p><span
  m=''3731750''>That</span> <span m=''3732180''>means</span> <span m=''3732720''>that</span>
  <span m=''3733010''>as</span> <span m=''3733210''>free</span> <span m=''3733490''>variables</span>
  <span m=''3733990''>in</span> <span m=''3734120''>this</span> <span m=''3734250''>lambda</span>
  <span m=''3734530''>expression,</span> <span m=''3736070''>there is the--there</span>
  <span m=''3737340''>are</span> <span m=''3737850''>in</span> <span m=''3737960''>the</span>
  <span m=''3738040''>frame,</span> <span m=''3738670''>which</span> <span m=''3739280''>is</span>
  <span m=''3739440''>the</span> <span m=''3739950''>parent</span> <span m=''3740270''>frame</span>
  <span m=''3740890''>of</span> <span m=''3741140''>this</span> <span m=''3741380''>lambda</span>
  <span m=''3741840''>expression,</span> <span m=''3743570''>the</span> <span m=''3743860''>procedure</span>
  <span m=''3744240''>resulting</span> <span m=''3744670''>from</span> <span m=''3744780''>this</span>
  <span m=''3744940''>lambda</span> <span m=''3745140''>expression,</span> <span m=''3746740''>X</span>
  <span m=''3746970''>and</span> <span m=''3747070''>Y</span> <span m=''3747470''>have</span>
  <span m=''3747710''>places.</span> <span m=''3749250''>And it''s</span> <span m=''3749620''>possible</span>
  <span m=''3750140''>to</span> <span m=''3750260''>set</span> <span m=''3750540''>them.</span>
  <span m=''3751910''>I</span> <span m=''3752110''>set</span> <span m=''3752410''>them</span>
  <span m=''3752850''>to</span> <span m=''3753060''>an</span> <span m=''3753140''>N,</span>
  <span m=''3753810''>which</span> <span m=''3754020''>is</span> <span m=''3754140''>the</span>
  <span m=''3754260''>argument</span> <span m=''3755120''>of</span> <span m=''3755250''>the</span>
  <span m=''3755380''>permission.</span> <span m=''3757010''>The</span> <span m=''3757400''>permission</span>
  <span m=''3758410''>is</span> <span m=''3758580''>a</span> <span m=''3758640''>procedure</span>
  <span m=''3761380''>which</span> <span m=''3761660''>is</span> <span m=''3761820''>passed</span>
  <span m=''3762320''>to</span> <span m=''3762750''>M,</span> <span m=''3763430''>which
  is</span> <span m=''3763650''>the</span> <span m=''3763830''>argument</span> <span
  m=''3764290''>that</span> <span m=''3764800''>the</span> <span m=''3764990''>CONS</span>
  <span m=''3765330''>object</span> <span m=''3765810''>gets</span> <span m=''3766060''>passed.</span>
  </p><p><span m=''3767940''>Now,</span> <span m=''3768060''>let''s</span> <span m=''3768260''>go</span>
  <span m=''3768370''>back</span> <span m=''3768690''>here</span> <span m=''3770000''>in</span>
  <span m=''3770130''>the</span> <span m=''3770210''>set-cdr</span> <span m=''3772010''>The</span>
  <span m=''3772370''>CONS</span> <span m=''3772740''>object,</span> <span m=''3773695''>which</span>
  <span m=''3774020''>is</span> <span m=''3774180''>the</span> <span m=''3774270''>first</span>
  <span m=''3774530''>argument</span> <span m=''3774810''>of</span> <span m=''3774920''>set-cdr</span>
  <span m=''3776230''>gets</span> <span m=''3776480''>passed</span> <span m=''3776750''>an</span>
  <span m=''3776830''>argument.</span> <span m=''3780260''>That--there''s</span> <span
  m=''3780420''>a</span> <span m=''3780480''>procedure</span> <span m=''3780930''>of
  four</span> <span m=''3781190''>things,</span> <span m=''3781550''>indeed,</span>
  <span m=''3782230''>because</span> <span m=''3782910''>that''s</span> <span m=''3783160''>the</span>
  <span m=''3783240''>same</span> <span m=''3783440''>thing</span> <span m=''3783580''>as
  this</span> <span m=''3783860''>M over</span> <span m=''3784270''>here,</span> <span
  m=''3785080''>which</span> <span m=''3785260''>is</span> <span m=''3785380''>applied</span>
  <span m=''3785780''>to</span> <span m=''3785860''>four</span> <span m=''3786090''>objects.</span>
  <span m=''3787920''>The</span> <span m=''3788220''>object</span> <span m=''3788590''>over</span>
  <span m=''3788720''>here,</span> <span m=''3789280''>SD,</span> <span m=''3791265''>is,</span>
  <span m=''3791660''>in</span> <span m=''3791910''>fact,</span> <span m=''3792400''>this</span>
  <span m=''3792680''>permission.</span> <span m=''3795470''>When</span> <span m=''3795650''>I</span>
  <span m=''3795750''>use</span> <span m=''3796130''>SD,</span> <span m=''3797190''>I</span>
  <span m=''3797350''>apply it</span> <span m=''3797820''>to</span> <span m=''3797920''>Y,</span>
  <span m=''3799390''>right</span> <span m=''3799620''>there.</span> <span m=''3802910''>So</span>
  <span m=''3803090''>that</span> <span m=''3803310''>comes</span> <span m=''3803560''>from</span>
  <span m=''3803730''>this.</span> </p><p><span m=''3805740''>AUDIENCE: So</span>
  <span m=''3806170''>what</span> <span m=''3806420''>do</span> <span m=''3806510''>you--</span>
  </p><p><span m=''3807410''>PROFESSOR: So</span> <span m=''3808550''>to</span> <span
  m=''3808630''>finish</span> <span m=''3808920''>that,</span> <span m=''3809180''>the</span>
  <span m=''3809450''>N</span> <span m=''3809660''>that</span> <span m=''3809770''>was</span>
  <span m=''3809930''>here</span> <span m=''3810860''>is</span> <span m=''3811040''>the</span>
  <span m=''3811120''>Y</span> <span m=''3811420''>which</span> <span m=''3811640''>is</span>
  <span m=''3811750''>here.</span> <span m=''3814160''>How''s</span> <span m=''3814300''>that?</span>
  </p><p><span m=''3814810''>AUDIENCE: Right,</span> <span m=''3815320''>OK.</span>
  <span m=''3815750''>Now,</span> <span m=''3815960''>when</span> <span m=''3816110''>you</span>
  <span m=''3816200''>do</span> <span m=''3816450''>a</span> <span m=''3816550''>set-cdr,</span>
  <span m=''3819180''>X is</span> <span m=''3819630''>the</span> <span m=''3819730''>value</span>
  <span m=''3820130''>the</span> <span m=''3820240''>CDR</span> <span m=''3820780''>is</span>
  <span m=''3820930''>going</span> <span m=''3821030''>to</span> <span m=''3821120''>become.</span>
  </p><p><span m=''3821970''>PROFESSOR: The</span> <span m=''3822150''>X</span> <span
  m=''3823400''>over</span> <span m=''3823620''>here.</span> <span m=''3824742''>I''m</span>
  <span m=''3825110''>sorry,</span> <span m=''3825480''>that''s</span> <span m=''3825650''>not</span>
  <span m=''3825990''>true.</span> <span m=''3826200''>The</span> <span m=''3826950''>X
  is--set-cdr</span> <span m=''3827410''>has</span> <span m=''3827530''>two</span>
  <span m=''3827700''>arguments--</span> <span m=''3828720''>The</span> <span m=''3829140''>CONS</span>
  <span m=''3829590''>I''m</span> <span m=''3829700''>changing</span> <span m=''3831360''>and</span>
  <span m=''3831660''>the</span> <span m=''3832740''>value</span> <span m=''3833030''>I''m</span>
  <span m=''3833150''>changing</span> <span m=''3833490''>it to.</span> <span m=''3836150''>So
  you</span> <span m=''3836280''>have</span> <span m=''3836410''>them</span> <span
  m=''3836540''>backwards,</span> <span m=''3837870''>that''s</span> <span m=''3838030''>all.</span>
  <span m=''3841750''>Are</span> <span m=''3842240''>there any</span> <span m=''3842540''>other</span>
  <span m=''3842670''>questions?</span> <span m=''3847880''>Well,</span> <span m=''3848040''>thank</span>
  <span m=''3848310''>you.</span> <span m=''3848640''>It''s</span> <span m=''3848750''>time</span>
  <span m=''3848940''>for</span> <span m=''3849030''>lunch.</span> </p>'
type: course
uid: db6c4639d0f0726a08313f8ef7c1b992

---
None