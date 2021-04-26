---
about_this_resource_text: <p><b>Topics covered:</b> Assignment, State, and Side-effects</p>
  <p><b> Instructors:</b> Hal Abelson and Gerald Jay Sussman</p> <p>Subtitles for
  this course are provided through the generous assistance of Henry Baker, Hoofar
  Pourzand, Heather Wood, Aleksejs Truhans, Steven Edwards, George Menhorn, and Mahendra
  Kumar.</p>
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
embedded_media:
- id: 5A.jpg
  parent_uid: 0d9197bbe8dc4cc36bd40a2ce243052f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/5a-assignment-state-and-side-effects/5A.jpg
  title: 5A.jpg
  type: null
  uid: f5fa7078c5a9c3c13182f049b5c96fbc
- id: Video-YouTube-Stream
  media_location: dO1aqPBJCPg
  parent_uid: 0d9197bbe8dc4cc36bd40a2ce243052f
  title: Video-YouTube-Stream
  type: Video
  uid: 8a2b1135eadfd037a4c87ca50a04384c
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT_Structure_of_Computer_Programs_1986/lec5a.mp4
  parent_uid: 0d9197bbe8dc4cc36bd40a2ce243052f
  title: Video-Internet Archive-MP4
  type: Video
  uid: dfcd18379b53fb9e758bec294939391c
- id: Thumbnail-OCW-JPG
  parent_uid: 0d9197bbe8dc4cc36bd40a2ce243052f
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 9461b9e8be54e716c6c59accdfb019c5
- id: 3Play-3PlayYouTubeid-MP4
  media_location: dO1aqPBJCPg
  parent_uid: 0d9197bbe8dc4cc36bd40a2ce243052f
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 4f6829e6a4b961ab608762c889243c0b
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/dO1aqPBJCPg/default.jpg
  parent_uid: 0d9197bbe8dc4cc36bd40a2ce243052f
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 913a96ed461f1c0835afa0836a05b8c4
- id: dO1aqPBJCPg.srt
  parent_uid: 0d9197bbe8dc4cc36bd40a2ce243052f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/5a-assignment-state-and-side-effects/dO1aqPBJCPg.srt
  title: 3play caption file
  type: null
  uid: e32b67c964695e42a59dbc3659985570
- id: dO1aqPBJCPg.pdf
  parent_uid: 0d9197bbe8dc4cc36bd40a2ce243052f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/5a-assignment-state-and-side-effects/dO1aqPBJCPg.pdf
  title: 3play pdf file
  type: null
  uid: 16ee3e36a574a5d66e45961725170e73
- id: Caption-3Play YouTube id-SRT
  parent_uid: 0d9197bbe8dc4cc36bd40a2ce243052f
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 1540537fd65c6fb66864b04530ec2e12
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 0d9197bbe8dc4cc36bd40a2ce243052f
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 23a47f2e9be0cb8b792125b5b1477037
inline_embed_id: 285560465a:assignment,state,andside-effects86670352
layout: video
order_index: null
parent_uid: 4fcacad2c29981dd668a6b29822403cc
related_resources_text: ''
short_url: 5a-assignment-state-and-side-effects
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/5a-assignment-state-and-side-effects
template_type: Tabbed
title: '5A: Assignment, State, and Side-effects'
transcript: <p><span m='0'>[MUSIC PLAYING]</span> </p><p><span m='16830'>PROFESSOR:</span>
  <span m='17350'>Well,</span> <span m='18430'>so</span> <span m='18620'>far</span>
  <span m='18820'>we've</span> <span m='20270'>invented</span> <span m='20730'>enough</span>
  <span m='21030'>programming</span> <span m='22330'>to</span> <span m='22480'>do</span>
  <span m='22630'>some</span> <span m='22800'>very</span> <span m='23030'>complicated</span>
  <span m='23600'>things.</span> <span m='24850'>And</span> <span m='27310'>you</span>
  <span m='27540'>surely</span> <span m='27950'>learned</span> <span m='28160'>a</span>
  <span m='28210'>lot</span> <span m='28430'>about</span> <span m='28710'>programming</span>
  <span m='29100'>at</span> <span m='29160'>this</span> <span m='29330'>point.</span>
  <span m='29760'>You've</span> <span m='29860'>learned</span> <span m='30080'>almost
  all</span> <span m='30450'>the</span> <span m='30520'>most</span> <span m='30750'>important</span>
  <span m='31080'>tricks</span> <span m='31940'>that</span> <span m='32189'>usually</span>
  <span m='32450'>don't</span> <span m='32640'>get</span> <span m='32810'>taught</span>
  <span m='33610'>to</span> <span m='33700'>people</span> <span m='34000'>until</span>
  <span m='34230'>they</span> <span m='34630'>have</span> <span m='34770'>had a</span>
  <span m='34870'>lot</span> <span m='34970'>of</span> <span m='35080'>experience.</span>
  <span m='36610'>For</span> <span m='36750'>example,</span> <span m='37080'>data</span>
  <span m='37260'>directed</span> <span m='37630'>programming</span> <span m='38130'>is</span>
  <span m='39120'>a</span> <span m='39220'>major</span> <span m='39500'>trick,</span>
  <span m='40800'>and</span> <span m='41010'>yesterday</span> <span m='41420'>you
  also saw an</span> <span m='41810'>interpreted</span> <span m='42450'>language.</span>
  </p><p><span m='45300'>We</span> <span m='45490'>did</span> <span m='45610'>this</span>
  <span m='45840'>all</span> <span m='46220'>in</span> <span m='47160'>a</span> <span
  m='47210'>computer</span> <span m='47570'>language,</span> <span m='48720'>at</span>
  <span m='48900'>this</span> <span m='49070'>point,</span> <span m='50130'>where</span>
  <span m='50320'>there</span> <span m='50400'>was</span> <span m='50570'>no</span>
  <span m='50730'>assignment</span> <span m='51300'>statement.</span> <span m='54020'>And</span>
  <span m='54260'>presumably,</span> <span m='55200'>for</span> <span m='55330'>those</span>
  <span m='55620'>of you who've</span> <span m='55880'>seen</span> <span m='56110'>your</span>
  <span m='56220'>Basic</span> <span m='56720'>or</span> <span m='56790'>Pascal</span>
  <span m='57430'>or</span> <span m='57480'>whatever,</span> <span m='58600'>that's</span>
  <span m='59210'>usually</span> <span m='59490'>considered</span> <span m='59830'>the</span>
  <span m='59910'>most</span> <span m='60170'>important</span> <span m='60580'>thing.</span>
  <span m='62040'>Well</span> <span m='62240'>today,</span> <span m='62570'>we're</span>
  <span m='62690'>going</span> <span m='62750'>to</span> <span m='62820'>do</span>
  <span m='62900'>some</span> <span m='63070'>thing</span> <span m='63210'>horrible.</span>
  <span m='63580'>We're</span> <span m='63950'>going to</span> <span m='64150'>add
  an</span> <span m='64470'>assignment</span> <span m='64910'>statement.</span> </p><p><span
  m='67370'>And</span> <span m='67610'>since</span> <span m='67710'>we</span> <span
  m='67860'>can do</span> <span m='67990'>all</span> <span m='68160'>these</span>
  <span m='68290'>wonderful</span> <span m='68590'>things</span> <span m='68790'>without</span>
  <span m='69110'>it,</span> <span m='69220'>why</span> <span m='69430'>should</span>
  <span m='69580'>we</span> <span m='69770'>add</span> <span m='69920'>it?</span>
  <span m='71110'>An</span> <span m='71230'>important</span> <span m='71600'>thing</span>
  <span m='71760'>to</span> <span m='71840'>understand</span> <span m='72370'>is</span>
  <span m='72480'>that</span> <span m='72630'>today</span> <span m='72910'>we're</span>
  <span m='73040'>going</span> <span m='73290'>to,</span> <span m='74600'>first of
  all,</span> <span m='74950'>have</span> <span m='75090'>a</span> <span m='75150'>rule,</span>
  <span m='76590'>which</span> <span m='76770'>is</span> <span m='76830'>going</span>
  <span m='76930'>to</span> <span m='77030'>always</span> <span m='77270'>be</span>
  <span m='77380'>obeyed,</span> <span m='77640'>which</span> <span m='77900'>is the</span>
  <span m='77980'>only</span> <span m='78200'>reason</span> <span m='78610'>we</span>
  <span m='78790'>ever</span> <span m='79120'>add a</span> <span m='79160'>feature</span>
  <span m='79520'>to</span> <span m='79720'>our</span> <span m='80160'>language</span>
  <span m='81710'>is</span> <span m='81860'>because</span> <span m='82170'>there is</span>
  <span m='82250'>a</span> <span m='82300'>good</span> <span m='82470'>reason.</span>
  <span m='83636'>And</span> <span m='84030'>the</span> <span m='84240'>good</span>
  <span m='84400'>reason</span> <span m='84700'>is</span> <span m='84780'>going</span>
  <span m='84860'>to</span> <span m='84940'>boil</span> <span m='85270'>down</span>
  <span m='85580'>to</span> <span m='85920'>the</span> <span m='86520'>ability,</span>
  <span m='87470'>you</span> <span m='87650'>now</span> <span m='87910'>get</span>
  <span m='88050'>an</span> <span m='88150'>ability</span> <span m='88730'>to</span>
  <span m='89240'>break</span> <span m='89490'>a</span> <span m='89550'>problem</span>
  <span m='89970'>into</span> <span m='90150'>pieces</span> <span m='90500'>that are</span>
  <span m='90660'>different</span> <span m='91010'>sets of</span> <span m='91220'>pieces</span>
  <span m='91570'>then</span> <span m='91660'>you</span> <span m='91760'>could</span>
  <span m='91900'>have</span> <span m='92010'>broken it</span> <span m='92360'>down</span>
  <span m='92590'>without</span> <span m='92950'>that,</span> <span m='94510'>give</span>
  <span m='94660'>you</span> <span m='94810'>another</span> <span m='95070'>means</span>
  <span m='95310'>of</span> <span m='95380'>decomposition.</span> </p><p><span m='98350'>However,</span>
  <span m='98680'>let's</span> <span m='98850'>just</span> <span m='99020'>start.</span>
  <span m='99490'>Let</span> <span m='99640'>me</span> <span m='99900'>quick</span>
  <span m='100160'>begin</span> <span m='100800'>by</span> <span m='100950'>reviewing</span>
  <span m='101870'>the</span> <span m='102060'>kind</span> <span m='102250'>of</span>
  <span m='102440'>language</span> <span m='103270'>that</span> <span m='103730'>we</span>
  <span m='106690'>have</span> <span m='106860'>now.</span> <span m='108240'>We've</span>
  <span m='108420'>been</span> <span m='108520'>writing</span> <span m='108760'>what's</span>
  <span m='108890'>called</span> <span m='109120'>functional</span> <span m='109600'>programs.</span>
  <span m='111310'>And</span> <span m='111470'>functional</span> <span m='111870'>programs</span>
  <span m='113210'>are</span> <span m='113770'>a</span> <span m='114010'>kind</span>
  <span m='114490'>of</span> <span m='114910'>encoding</span> <span m='116610'>of</span>
  <span m='116770'>mathematical</span> <span m='117450'>truths.</span> <span m='118890'>For</span>
  <span m='119100'>example,</span> <span m='119510'>when</span> <span m='119700'>we</span>
  <span m='119810'>look</span> <span m='119970'>at</span> <span m='120130'>the</span>
  <span m='120910'>factorial</span> <span m='121490'>procedure</span> <span m='122120'>that</span>
  <span m='122420'>you</span> <span m='122720'>see</span> <span m='122930'>on</span>
  <span m='123120'>the</span> <span m='123370'>slide</span> <span m='123710'>here,</span>
  <span m='125200'>it's</span> <span m='125400'>basically</span> <span m='125850'>two</span>
  <span m='126010'>clauses.</span> <span m='127090'>If</span> <span m='127290'>n</span>
  <span m='127410'>is</span> <span m='127530'>one,</span> <span m='127710'>the</span>
  <span m='127780'>result</span> <span m='128110'>is</span> <span m='128240'>one,</span>
  <span m='128680'>otherwise</span> <span m='128800'>n</span> <span m='128860'>times</span>
  <span m='129530'>factorial</span> <span m='129930'>n</span> <span m='130580'>minus</span>
  <span m='130850'>one.</span> <span m='131230'>That's</span> <span m='131440'>factorial
  of</span> <span m='131910'>n.</span> <span m='132990'>Well, that</span> <span m='133210'>is</span>
  <span m='133460'>factorial</span> <span m='133950'>of</span> <span m='134286'>n.</span>
  </p><p><span m='134960'>And</span> <span m='135110'>written</span> <span m='135360'>down</span>
  <span m='135650'>in</span> <span m='135760'>some</span> <span m='135950'>other</span>
  <span m='136160'>obscure</span> <span m='136470'>notation</span> <span m='136930'>that</span>
  <span m='137040'>you</span> <span m='137120'>might</span> <span m='137290'>have</span>
  <span m='137410'>learned</span> <span m='137670'>in</span> <span m='138360'>calculus</span>
  <span m='138840'>classes,</span> <span m='140940'>mathematical</span> <span m='141530'>logic,</span>
  <span m='142310'>what you</span> <span m='142560'>see</span> <span m='142770'>there</span>
  <span m='143390'>is</span> <span m='144090'>if</span> <span m='144950'>n</span>
  <span m='145540'>equals</span> <span m='145850'>one,</span> <span m='146230'>for</span>
  <span m='146720'>the</span> <span m='147370'>result</span> <span m='147960'>of</span>
  <span m='148090'>n</span> <span m='148380'>factorial</span> <span m='148630'>is</span>
  <span m='148950'>one,</span> <span m='149270'>otherwise,</span> <span m='150010'>greater</span>
  <span m='150260'>than</span> <span m='150330'>one,</span> <span m='150680'>n</span>
  <span m='150850'>factorial</span> <span m='151060'>is</span> <span m='151370'>n</span>
  <span m='151560'>times</span> <span m='151660'>n</span> <span m='151880'>minus</span>
  <span m='152040'>one</span> <span m='152250'>factorial.</span> </p><p><span m='152680'>True</span>
  <span m='152920'>statements,</span> <span m='155030'>that's</span> <span m='155230'>the</span>
  <span m='155300'>kind</span> <span m='155480'>of</span> <span m='155560'>language</span>
  <span m='155900'>we've been</span> <span m='156200'>using.</span> <span m='157000'>And</span>
  <span m='157220'>whenever</span> <span m='157520'>we</span> <span m='157660'>have</span>
  <span m='157830'>true</span> <span m='158000'>statements</span> <span m='158480'>of</span>
  <span m='158620'>that</span> <span m='158760'>sort,</span> <span m='159290'>there</span>
  <span m='159610'>is</span> <span m='159810'>a</span> <span m='159930'>kind</span>
  <span m='160310'>of,</span> <span m='161010'>a</span> <span m='161200'>way</span>
  <span m='161500'>of</span> <span m='165340'>understanding</span> <span m='165900'>how</span>
  <span m='166040'>they</span> <span m='166170'>work</span> <span m='167490'>which</span>
  <span m='167700'>is</span> <span m='167830'>that</span> <span m='168040'>such</span>
  <span m='168270'>processes</span> <span m='168840'>can</span> <span m='169050'>be</span>
  <span m='169260'>involved</span> <span m='169970'>by</span> <span m='170170'>substitution.</span>
  </p><p><span m='171390'>And so</span> <span m='171550'>we</span> <span m='171680'>see</span>
  <span m='171890'>on</span> <span m='172050'>the</span> <span m='172540'>second</span>
  <span m='172960'>slide</span> <span m='173270'>here,</span> <span m='174820'>that</span>
  <span m='175660'>the</span> <span m='175900'>way</span> <span m='176090'>we</span>
  <span m='176230'>understand</span> <span m='177650'>the</span> <span m='178010'>execution</span>
  <span m='178860'>implied</span> <span m='180360'>by</span> <span m='180740'>those</span>
  <span m='180990'>statements</span> <span m='181880'>in</span> <span m='182010'>arranged</span>
  <span m='182040'>in</span> <span m='182380'>that</span> <span m='182550'>order,</span>
  <span m='184190'>is</span> <span m='184450'>that</span> <span m='184680'>you</span>
  <span m='185040'>do</span> <span m='185150'>successive</span> <span m='185640'>substitutions</span>
  <span m='187040'>of</span> <span m='187230'>arguments</span> <span m='187940'>for</span>
  <span m='188050'>formal</span> <span m='188370'>parameters</span> <span m='188870'>in</span>
  <span m='188980'>the</span> <span m='189050'>body</span> <span m='189370'>of</span>
  <span m='189480'>a</span> <span m='190300'>procedure.</span> </p><p><span m='192430'>This</span>
  <span m='192770'>is</span> <span m='193060'>basically a</span> <span m='193500'>sequence</span>
  <span m='193840'>of</span> <span m='193960'>equalities.</span> <span m='194710'>Factorial</span>
  <span m='195300'>four</span> <span m='195610'>is</span> <span m='195930'>four</span>
  <span m='196130'>times</span> <span m='196350'>factorial</span> <span m='196820'>three.</span>
  <span m='197390'>That</span> <span m='197700'>is</span> <span m='198120'>four</span>
  <span m='198470'>times</span> <span m='198700'>three</span> <span m='198900'>times</span>
  <span m='199120'>factorial</span> <span m='199390'>of</span> <span m='199660'>two</span>
  <span m='200170'>and</span> <span m='200320'>so</span> <span m='200540'>on.</span>
  <span m='201290'>We're</span> <span m='201410'>always</span> <span m='201740'>preserving</span>
  <span m='203020'>truth.</span> <span m='206580'>Even</span> <span m='206870'>though</span>
  <span m='206990'>we're</span> <span m='207200'>talking</span> <span m='207630'>about</span>
  <span m='207900'>true</span> <span m='208120'>statements,</span> <span m='208980'>there</span>
  <span m='209190'>might</span> <span m='209360'>be</span> <span m='209470'>more</span>
  <span m='209710'>than</span> <span m='209860'>one</span> <span m='210140'>organization</span>
  <span m='210900'>of</span> <span m='211050'>these</span> <span m='211210'>true</span>
  <span m='211390'>statements</span> <span m='212060'>to</span> <span m='212230'>describe</span>
  <span m='212660'>the</span> <span m='212750'>computation</span> <span m='213340'>of</span>
  <span m='213430'>a</span> <span m='213500'>particular</span> <span m='214630'>function,</span>
  <span m='215940'>the</span> <span m='216360'>computation</span> <span m='216920'>of</span>
  <span m='217000'>the</span> <span m='217080'>value</span> <span m='217440'>of</span>
  <span m='217490'>a</span> <span m='217520'>particular</span> <span m='217860'>function.</span>
  </p><p><span m='218640'>So,</span> <span m='218910'>for</span> <span m='219120'>example,</span>
  <span m='219710'>looking</span> <span m='219950'>at</span> <span m='220030'>the</span>
  <span m='220120'>next</span> <span m='220390'>one</span> <span m='220540'>here.</span>
  <span m='222460'>Here is</span> <span m='222740'>a</span> <span m='222790'>way</span>
  <span m='223020'>of</span> <span m='223390'>looking</span> <span m='223680'>at</span>
  <span m='223770'>the</span> <span m='223860'>sum</span> <span m='227940'>of</span>
  <span m='228160'>n and</span> <span m='228270'>m.</span> <span m='229780'>And</span>
  <span m='229950'>we</span> <span m='230080'>did</span> <span m='230270'>this</span>
  <span m='230470'>one</span> <span m='230650'>by</span> <span m='230820'>a</span>
  <span m='230890'>recursive</span> <span m='231390'>process.</span> <span m='232930'>It's</span>
  <span m='233490'>the</span> <span m='234750'>increment</span> <span m='235340'>of</span>
  <span m='235540'>the</span> <span m='235630'>sum</span> <span m='236020'>of</span>
  <span m='236140'>the</span> <span m='236240'>decrement</span> <span m='236470'>of</span>
  <span m='236810'>n</span> <span m='237480'>and</span> <span m='237670'>m.</span>
  <span m='240130'>And,</span> <span m='240260'>of</span> <span m='240500'>course,</span>
  <span m='240760'>there</span> <span m='241420'>is</span> <span m='241640'>some</span>
  <span m='242030'>piece</span> <span m='242300'>of</span> <span m='242720'>mathematical</span>
  <span m='243390'>logic</span> <span m='243780'>here</span> <span m='244100'>that</span>
  <span m='244410'>describes</span> <span m='244950'>that.</span> <span m='246240'>It's</span>
  <span m='246420'>the</span> <span m='246580'>increment</span> <span m='247360'>of</span>
  <span m='247770'>the</span> <span m='247990'>sum</span> <span m='248590'>of</span>
  <span m='248720'>the</span> <span m='248850'>decrement</span> <span m='249380'>of</span>
  <span m='249880'>n</span> <span m='250080'>and</span> <span m='250360'>m,</span>
  <span m='251450'>just</span> <span m='251680'>like</span> <span m='251920'>that.</span>
  <span m='253120'>So</span> <span m='253370'>there's</span> <span m='254030'>nothing</span>
  <span m='254360'>particularly</span> <span m='255420'>magic</span> <span m='255830'>about</span>
  <span m='256170'>that.</span> </p><p><span m='256440'>And,</span> <span m='256570'>of</span>
  <span m='256660'>course,</span> <span m='257180'>if</span> <span m='257339'>we</span>
  <span m='257450'>can</span> <span m='257550'>also</span> <span m='257800'>look</span>
  <span m='257959'>at</span> <span m='258060'>an</span> <span m='258339'>iterative</span>
  <span m='258779'>process</span> <span m='259059'>for</span> <span m='259339'>the</span>
  <span m='259480'>same,</span> <span m='260209'>a</span> <span m='260339'>program</span>
  <span m='260769'>that</span> <span m='260890'>evolves</span> <span m='261269'>an</span>
  <span m='261380'>iterative</span> <span m='261700'>process,</span> <span m='262920'>for</span>
  <span m='263060'>the</span> <span m='263170'>same</span> <span m='264110'>function.</span>
  <span m='265310'>These</span> <span m='265490'>are</span> <span m='265570'>two</span>
  <span m='265760'>things</span> <span m='266040'>that</span> <span m='266160'>compute</span>
  <span m='266480'>the</span> <span m='266560'>same</span> <span m='267150'>answer.</span>
  <span m='269930'>And</span> <span m='270150'>we</span> <span m='270370'>have</span>
  <span m='270580'>equivalent</span> <span m='271030'>mathematical</span> <span m='271610'>truths</span>
  <span m='273730'>that</span> <span m='274040'>are</span> <span m='274220'>arranged</span>
  <span m='274580'>there.</span> <span m='276720'>And</span> <span m='277000'>just</span>
  <span m='277110'>the</span> <span m='277190'>way</span> <span m='277380'>you</span>
  <span m='277520'>arrange</span> <span m='277880'>those</span> <span m='278110'>truths</span>
  <span m='278440'>determine</span> <span m='278840'>the</span> <span m='278920'>particular</span>
  <span m='279270'>process.</span> <span m='280430'>In</span> <span m='280550'>the
  way</span> <span m='280830'>choose</span> <span m='281160'>and</span> <span m='281250'>arrange</span>
  <span m='281570'>them</span> <span m='282040'>determines</span> <span m='282390'>the</span>
  <span m='282450'>process</span> <span m='282810'>that's</span> <span m='282990'>evolved.</span>
  </p><p><span m='284400'>So</span> <span m='284590'>we</span> <span m='284710'>have</span>
  <span m='284890'>the</span> <span m='284970'>flexibility</span> <span m='285900'>of</span>
  <span m='286070'>talking</span> <span m='286370'>about</span> <span m='286790'>both</span>
  <span m='287270'>the</span> <span m='287370'>function</span> <span m='287800'>to</span>
  <span m='287910'>be</span> <span m='288050'>computed,</span> <span m='288710'>and</span>
  <span m='288890'>the</span> <span m='288960'>method</span> <span m='289260'>by</span>
  <span m='289380'>which</span> <span m='289550'>it's</span> <span m='289670'>computed.</span>
  <span m='290410'>So</span> <span m='290670'>it's</span> <span m='290800'>not</span>
  <span m='291010'>clear</span> <span m='291210'>we</span> <span m='291980'>need</span>
  <span m='292220'>more.</span> <span m='293580'>However,</span> <span m='294010'>today</span>
  <span m='294240'>I'm</span> <span m='294340'>going</span> <span m='294550'>to</span>
  <span m='294650'>this</span> <span m='294830'>awful</span> <span m='295150'>thing.</span>
  <span m='295440'>I'm</span> <span m='295700'>going</span> <span m='295850'>to introduce</span>
  <span m='296280'>this</span> <span m='296420'>assignment</span> <span m='297540'>operation.</span>
  </p><p><span m='299070'>Now,</span> <span m='299870'>what</span> <span m='300030'>is</span>
  <span m='300180'>this?</span> <span m='302890'>Well,</span> <span m='303090'>first</span>
  <span m='303350'>of</span> <span m='303410'>all,</span> <span m='303560'>there is</span>
  <span m='303640'>going</span> <span m='303880'>to</span> <span m='303980'>be</span>
  <span m='304890'>another</span> <span m='305310'>kind</span> <span m='305750'>of</span>
  <span m='307830'>kind</span> <span m='308080'>of</span> <span m='308150'>statement,</span>
  <span m='308650'>if</span> <span m='308750'>you</span> <span m='308860'>will,</span>
  <span m='309390'>in</span> <span m='309510'>a</span> <span m='309580'>programming</span>
  <span m='309960'>language</span> <span m='310270'>called</span> <span m='310470'>Set!</span>
  <span m='313800'>Things</span> <span m='314220'>that</span> <span m='314490'>do</span>
  <span m='315020'>things</span> <span m='315300'>like</span> <span m='315540'>assignment,</span>
  <span m='316040'>I'm</span> <span m='316180'>going</span> <span m='316250'>to</span>
  <span m='316320'>put</span> <span m='316550'>exclamation</span> <span m='317110'>points</span>
  <span m='317390'>after.</span> <span m='318570'>We'll</span> <span m='318730'>talk</span>
  <span m='318930'>about</span> <span m='319040'>what</span> <span m='319170'>that</span>
  <span m='319400'>means</span> <span m='319880'>in</span> <span m='320090'>a</span>
  <span m='320470'>second.</span> <span m='320990'>The</span> <span m='321210'>exclamation</span>
  <span m='321690'>point,</span> <span m='321850'>again</span> <span m='322160'>like</span>
  <span m='322390'>question</span> <span m='322710'>mark,</span> <span m='323160'>is</span>
  <span m='323290'>an</span> <span m='323370'>arbitrary</span> <span m='323960'>thing</span>
  <span m='324140'>we</span> <span m='324280'>attach</span> <span m='324610'>to</span>
  <span m='324730'>the</span> <span m='324820'>symbol</span> <span m='325110'>which</span>
  <span m='325300'>is</span> <span m='325350'>the</span> <span m='325470'>name,</span>
  <span m='325960'>has</span> <span m='326160'>no</span> <span m='326380'>significance</span>
  <span m='326990'>to</span> <span m='327100'>the</span> <span m='327190'>system.</span>
  <span m='328090'>The</span> <span m='328320'>only</span> <span m='328560'>significance</span>
  <span m='329090'>is</span> <span m='329200'>to</span> <span m='329320'>me</span>
  <span m='329560'>and</span> <span m='329780'>you</span> <span m='330030'>to</span>
  <span m='330730'>alert</span> <span m='331090'>you</span> <span m='331220'>that
  this</span> <span m='331520'>is</span> <span m='331600'>an</span> <span m='331710'>assignment</span>
  <span m='333660'>of</span> <span m='333760'>some</span> <span m='333980'>sort.</span>
  </p><p><span m='335910'>But</span> <span m='336130'>we're</span> <span m='336230'>going</span>
  <span m='336390'>to</span> <span m='336440'>set</span> <span m='336720'>a</span>
  <span m='336870'>variable</span> <span m='338850'>to</span> <span m='339390'>a</span>
  <span m='339470'>value.</span> <span m='343800'>And</span> <span m='344000'>what</span>
  <span m='344170'>that's</span> <span m='344450'>going</span> <span m='344580'>to</span>
  <span m='344720'>mean</span> <span m='345210'>is</span> <span m='345360'>that</span>
  <span m='345480'>there</span> <span m='345690'>is</span> <span m='345810'>a</span>
  <span m='346140'>time</span> <span m='346950'>at</span> <span m='347120'>which</span>
  <span m='347290'>something</span> <span m='347680'>happens.</span> <span m='348600'>Here's</span>
  <span m='348900'>a</span> <span m='348990'>time.</span> <span m='350100'>If</span>
  <span m='350390'>I</span> <span m='350570'>have</span> <span m='350760'>time</span>
  <span m='351140'>going</span> <span m='351400'>this</span> <span m='351580'>way,</span>
  <span m='353580'>it's</span> <span m='353750'>a</span> <span m='353860'>time</span>
  <span m='354180'>access.</span> <span m='355030'>Time</span> <span m='355370'>progresses</span>
  <span m='356220'>by</span> <span m='356440'>walking</span> <span m='356880'>down</span>
  <span m='357140'>the</span> <span m='357220'>page.</span> <span m='358650'>Then</span>
  <span m='358970'>an</span> <span m='359070'>assignment</span> <span m='359640'>is</span>
  <span m='359790'>the</span> <span m='359920'>first</span> <span m='360190'>thing</span>
  <span m='360380'>we</span> <span m='360620'>have</span> <span m='360980'>that</span>
  <span m='361250'>produces</span> <span m='361760'>the</span> <span m='361850'>difference</span>
  <span m='362230'>between</span> <span m='362940'>a</span> <span m='363080'>before</span>
  <span m='363550'>and an</span> <span m='363730'>after.</span> </p><p><span m='366670'>All</span>
  <span m='367040'>the</span> <span m='367190'>other</span> <span m='367430'>programs</span>
  <span m='368110'>that</span> <span m='368220'>we've</span> <span m='368420'>written,</span>
  <span m='369150'>that</span> <span m='369330'>have</span> <span m='369530'>no</span>
  <span m='369660'>assignments</span> <span m='370130'>in</span> <span m='370250'>them,</span>
  <span m='370660'>the</span> <span m='370880'>order</span> <span m='371190'>in</span>
  <span m='371270'>which</span> <span m='371460'>they</span> <span m='371600'>were</span>
  <span m='371750'>evaluated</span> <span m='372400'>didn't</span> <span m='372660'>matter.</span>
  <span m='374590'>But</span> <span m='374910'>assignment</span> <span m='375400'>is
  special, it</span> <span m='375970'>produces</span> <span m='376520'>a</span> <span
  m='376600'>moment</span> <span m='377000'>in</span> <span m='377120'>time.</span>
  <span m='377990'>So</span> <span m='378230'>there</span> <span m='378430'>is</span>
  <span m='378520'>a</span> <span m='378600'>moment</span> <span m='378960'>before</span>
  <span m='379430'>the</span> <span m='380210'>set</span> <span m='383210'>occurs</span>
  <span m='383840'>and</span> <span m='384200'>after,</span> <span m='387410'>such</span>
  <span m='387980'>that</span> <span m='391020'>after</span> <span m='391390'>this</span>
  <span m='391650'>moment</span> <span m='392020'>in</span> <span m='392150'>time,</span>
  <span m='393510'>the</span> <span m='393800'>variable</span> <span m='396780'>has</span>
  <span m='399120'>the</span> <span m='399500'>value,</span> <span m='402990'>value.</span>
  <span m='409310'>Independent</span> <span m='409870'>of</span> <span m='410030'>what</span>
  <span m='410210'>value</span> <span m='410610'>it</span> <span m='410690'>had</span>
  <span m='410870'>before,</span> <span m='412790'>set!</span> <span m='413340'>changes</span>
  <span m='413940'>the</span> <span m='414040'>value</span> <span m='415090'>of</span>
  <span m='415220'>the</span> <span m='415350'>variable.</span> </p><p><span m='417660'>Until</span>
  <span m='418090'>this</span> <span m='418280'>moment,</span> <span m='418930'>we</span>
  <span m='419080'>had</span> <span m='419360'>nothing</span> <span m='420280'>that</span>
  <span m='420830'>changed.</span> <span m='423150'>So,</span> <span m='423420'>for</span>
  <span m='423590'>example,</span> <span m='424930'>one</span> <span m='425210'>of</span>
  <span m='425270'>the</span> <span m='425330'>things</span> <span m='425530'>we</span>
  <span m='425650'>can</span> <span m='425770'>think</span> <span m='425990'>of</span>
  <span m='426370'>is</span> <span m='426600'>that</span> <span m='426910'>the</span>
  <span m='427150'>procedures</span> <span m='427690'>we</span> <span m='427830'>write</span>
  <span m='428040'>for</span> <span m='428120'>something</span> <span m='428390'>like</span>
  <span m='428600'>factorial</span> <span m='429630'>are</span> <span m='429890'>in</span>
  <span m='429970'>fact</span> <span m='430640'>pretty</span> <span m='430810'>much</span>
  <span m='431010'>identical</span> <span m='431450'>to</span> <span m='431530'>the</span>
  <span m='431630'>function</span> <span m='432100'>factorial.</span> <span m='433740'>Factorial</span>
  <span m='434110'>of</span> <span m='434500'>four,</span> <span m='434840'>if</span>
  <span m='435110'>I</span> <span m='435380'>write</span> <span m='435540'>fact4,</span>
  <span m='437290'>independent</span> <span m='437830'>of</span> <span m='437930'>what</span>
  <span m='438120'>context</span> <span m='438640'>it's</span> <span m='438760'>in,</span>
  <span m='439720'>and</span> <span m='439880'>independent</span> <span m='440260'>of</span>
  <span m='440340'>how</span> <span m='440500'>many</span> <span m='440660'>times</span>
  <span m='440920'>I</span> <span m='440980'>write</span> <span m='441350'>it, I</span>
  <span m='441410'>always</span> <span m='441620'>get</span> <span m='441720'>the</span>
  <span m='441790'>same</span> <span m='442020'>answer.</span> <span m='443040'>It's</span>
  <span m='443450'>always</span> <span m='443680'>24.</span> <span m='445430'>It's
  a</span> <span m='445560'>unique</span> <span m='446050'>map</span> <span m='446820'>from
  the</span> <span m='447130'>argument</span> <span m='448210'>to</span> <span m='448350'>the</span>
  <span m='448480'>answer.</span> </p><p><span m='450360'>And</span> <span m='450520'>all</span>
  <span m='450670'>the</span> <span m='450740'>programs</span> <span m='451160'>we've</span>
  <span m='451270'>written</span> <span m='451500'>so</span> <span m='451670'>far</span>
  <span m='452030'>are like</span> <span m='452300'>that.</span> <span m='453580'>However,</span>
  <span m='454270'>once</span> <span m='454520'>I</span> <span m='454600'>have</span>
  <span m='454680'>assignment,</span> <span m='455170'>that</span> <span m='455300'>isn't</span>
  <span m='455530'>true.</span> <span m='457020'>So,</span> <span m='457270'>for</span>
  <span m='457480'>example,</span> <span m='459320'>if</span> <span m='459540'>I</span>
  <span m='459650'>were</span> <span m='459790'>to</span> <span m='460730'>define</span>
  <span m='464700'>count</span> <span m='466890'>to</span> <span m='467320'>be</span>
  <span m='467740'>one.</span> <span m='470070'>And</span> <span m='470300'>then</span>
  <span m='470460'>I'm going</span> <span m='470670'>to</span> <span m='470780'>define</span>
  <span m='471040'>also</span> <span m='471650'>a</span> <span m='471730'>procedure,</span>
  <span m='475260'>a simple</span> <span m='475550'>procedure</span> <span m='475900'>called</span>
  <span m='476160'>demo,</span> <span m='479640'>which</span> <span m='479770'>takes</span>
  <span m='480070'>argument</span> <span m='480380'>x</span> <span m='481990'>and</span>
  <span m='482240'>does</span> <span m='482730'>the</span> <span m='482960'>following</span>
  <span m='483330'>operations.</span> <span m='483870'>It</span> <span m='484080'>first</span>
  <span m='484420'>sets</span> <span m='488300'>x</span> <span m='488660'>to</span>
  <span m='488880'>x</span> <span m='489100'>plus</span> <span m='489320'>one.</span>
  <span m='489650'>My</span> <span m='489830'>gosh,</span> <span m='490200'>this</span>
  <span m='490350'>looks</span> <span m='490540'>just</span> <span m='490740'>like</span>
  <span m='491020'>FORTRAN,</span> <span m='491470'>right--</span> <span m='493160'>in</span>
  <span m='493350'>a</span> <span m='493400'>funny</span> <span m='493630'>syntax.</span>
  <span m='496910'>And</span> <span m='497120'>then</span> <span m='497400'>add</span>
  <span m='498870'>to</span> <span m='499500'>x</span> <span m='500840'>count,</span>
  <span m='502755'>Oh,</span> <span m='503220'>I just</span> <span m='503410'>made</span>
  <span m='503540'>a</span> <span m='503580'>mistake.</span> </p><p><span m='504330'>I</span>
  <span m='504750'>want</span> <span m='505010'>to</span> <span m='505460'>say,</span>
  <span m='505750'>set!</span> <span m='506060'>count</span> <span m='506230'>to</span>
  <span m='506380'>one</span> <span m='506470'>plus</span> <span m='506610'>count.</span>
  <span m='510310'>It's</span> <span m='510750'>this</span> <span m='510950'>thing</span>
  <span m='511020'>defined</span> <span m='511330'>here.</span> <span m='514350'>And</span>
  <span m='514960'>then plus </span> <span m='515789'>x</span> <span m='516049'>count.</span>
  <span m='520409'>Then</span> <span m='520669'>I</span> <span m='520750'>can</span>
  <span m='520919'>try</span> <span m='521210'>this</span> <span m='521440'>procedure.</span>
  <span m='522559'>Let's</span> <span m='522760'>run</span> <span m='523010'>it.</span>
  <span m='523880'>So,</span> <span m='524720'>suppose I</span> <span m='524950'>get</span>
  <span m='525260'>a</span> <span m='525500'>prompt</span> <span m='526430'>and</span>
  <span m='526570'>I</span> <span m='526670'>say,</span> <span m='527480'>demo</span>
  <span m='527860'>three.</span> </p><p><span m='532210'>Well, what</span> <span m='532560'>happens</span>
  <span m='533020'>here?</span> <span m='533540'>The</span> <span m='534100'>first</span>
  <span m='534350'>thing</span> <span m='534490'>that</span> <span m='534600'>happens</span>
  <span m='535560'>is</span> <span m='535750'>count</span> <span m='535990'>is</span>
  <span m='536090'>currently</span> <span m='536450'>one.</span> <span m='537020'>Currently,</span>
  <span m='537280'>there</span> <span m='537540'>is</span> <span m='537650'>a</span>
  <span m='537730'>time.</span> <span m='539130'>We're</span> <span m='539380'>talking</span>
  <span m='539450'>about</span> <span m='539660'>time.</span> <span m='540710'>x</span>
  <span m='541030'>gets</span> <span m='541280'>three.</span> <span m='542960'>At</span>
  <span m='543180'>this</span> <span m='543410'>moment,</span> <span m='544750'>I</span>
  <span m='544910'>say,</span> <span m='545380'>oh</span> <span m='545500'>yes,</span>
  <span m='545760'>count</span> <span m='546020'>is</span> <span m='546090'>incremented,</span>
  <span m='546330'>so</span> <span m='546620'>count</span> <span m='546960'>is</span>
  <span m='547080'>two.</span> <span m='548690'>two</span> <span m='549300'>plus</span>
  <span m='549570'>three</span> <span m='549790'>is</span> <span m='549920'>five.</span>
  <span m='550710'>So</span> <span m='551040'>the</span> <span m='551170'>answer</span>
  <span m='551260'>I</span> <span m='551570'>get</span> <span m='551800'>out</span>
  <span m='552040'>is</span> <span m='552280'>five.</span> <span m='554460'>Then</span>
  <span m='554720'>I</span> <span m='554850'>say,</span> <span m='556830'>demo</span>
  <span m='559760'>of</span> <span m='560250'>say,</span> <span m='560710'>three</span>
  <span m='561130'>again.</span> </p><p><span m='563640'>What do</span> <span m='564100'>I</span>
  <span m='564200'>get?</span> <span m='564830'>Well,</span> <span m='565030'>now</span>
  <span m='565560'>count</span> <span m='565900'>is</span> <span m='566080'>two,</span>
  <span m='566290'>it's</span> <span m='566440'>not</span> <span m='566680'>one</span>
  <span m='566900'>anymore,</span> <span m='568930'>because</span> <span m='569100'>I</span>
  <span m='569310'>have</span> <span m='569530'>incremented</span> <span m='570190'>it.</span>
  <span m='570760'>But</span> <span m='571120'>now</span> <span m='571330'>I</span>
  <span m='571680'>go</span> <span m='571860'>through</span> <span m='572070'>this</span>
  <span m='572240'>process,</span> <span m='572680'>three</span> <span m='573000'>goes</span>
  <span m='573210'>into</span> <span m='573340'>x,</span> <span m='575050'>count</span>
  <span m='575380'>becomes</span> <span m='575790'>one</span> <span m='575960'>plus</span>
  <span m='576140'>count, so</span> <span m='576450'>that's</span> <span m='576710'>three</span>
  <span m='576980'>now.</span> <span m='578160'>The</span> <span m='578290'>sum</span>
  <span m='578510'>of</span> <span m='578680'>those</span> <span m='578860'>two</span>
  <span m='579000'>is</span> <span m='579130'>six,</span> <span m='579740'>so</span>
  <span m='579930'>the</span> <span m='580030'>answer</span> <span m='580350'>is</span>
  <span m='580450'>six.</span> </p><p><span m='582130'>And</span> <span m='582220'>what
  we</span> <span m='582460'>see</span> <span m='583100'>is</span> <span m='583280'>the</span>
  <span m='583400'>same</span> <span m='583750'>expression</span> <span m='585190'>leads</span>
  <span m='585480'>to</span> <span m='585590'>two</span> <span m='585760'>different</span>
  <span m='586060'>answers,</span> <span m='588850'>depending</span> <span m='589260'>upon</span>
  <span m='589590'>time.</span> <span m='592170'>So</span> <span m='592390'>demo</span>
  <span m='592790'>is</span> <span m='592930'>not</span> <span m='593100'>a</span>
  <span m='593140'>function,</span> <span m='594290'>does</span> <span m='594450'>not</span>
  <span m='594670'>compute</span> <span m='594980'>a</span> <span m='595040'>mathematical</span>
  <span m='595630'>function.</span> <span m='600020'>In</span> <span m='600170'>fact,</span>
  <span m='600400'>you</span> <span m='600490'>could</span> <span m='600600'>also</span>
  <span m='600880'>see</span> <span m='601110'>why</span> <span m='601360'>now,</span>
  <span m='601570'>of</span> <span m='601680'>course,</span> <span m='602270'>this</span>
  <span m='603100'>is</span> <span m='603180'>the</span> <span m='603280'>first</span>
  <span m='603620'>place</span> <span m='603930'>where</span> <span m='604350'>the</span>
  <span m='604560'>substitution</span> <span m='605320'>model</span> <span m='605650'>isn't</span>
  <span m='605880'>going</span> <span m='605990'>to</span> <span m='606100'>work.</span>
  <span m='607780'>This</span> <span m='608030'>kills</span> <span m='608400'>the</span>
  <span m='608520'>substitution</span> <span m='608730'>model</span> <span m='609040'>dead.</span>
  </p><p><span m='611410'>You</span> <span m='611490'>know,</span> <span m='611570'>with</span>
  <span m='611720'>quotation</span> <span m='612560'>there</span> <span m='612850'>were</span>
  <span m='612940'>some</span> <span m='613130'>little</span> <span m='613350'>problems</span>
  <span m='613910'>that</span> <span m='614060'>a</span> <span m='614100'>philosopher</span>
  <span m='614550'>might</span> <span m='614780'>notice</span> <span m='616300'>with</span>
  <span m='616530'>the</span> <span m='616690'>substitutions,</span> <span m='617380'>because</span>
  <span m='617580'>you</span> <span m='617640'>have</span> <span m='617730'>to</span>
  <span m='617810'>worry</span> <span m='618040'>about</span> <span m='618280'>what</span>
  <span m='618870'>deductions</span> <span m='619260'>you</span> <span m='619410'>can</span>
  <span m='619560'>make</span> <span m='620980'>when</span> <span m='621110'>you</span>
  <span m='621190'>substitute</span> <span m='621650'>into</span> <span m='621760'>quotes,</span>
  <span m='622510'>if</span> <span m='622620'>you're</span> <span m='622750'>allowed</span>
  <span m='623000'>to</span> <span m='623070'>do</span> <span m='623210'>that</span>
  <span m='623370'>at</span> <span m='623460'>all.</span> <span m='625150'>But</span>
  <span m='626290'>here</span> <span m='626500'>the</span> <span m='626610'>substitution</span>
  <span m='627030'>model</span> <span m='627350'>is</span> <span m='627460'>dead,</span>
  <span m='628230'>can't</span> <span m='628460'>do</span> <span m='628590'>anything</span>
  <span m='628930'>at</span> <span m='629170'>all.</span> </p><p><span m='629810'>Because,</span>
  <span m='630590'>supposing</span> <span m='631560'>I</span> <span m='631780'>wanted</span>
  <span m='632220'>to</span> <span m='632980'>use</span> <span m='633310'>a</span>
  <span m='633360'>substitution</span> <span m='633890'>model</span> <span m='634330'>to</span>
  <span m='634490'>consider</span> <span m='634810'>substituting</span> <span m='635270'>for</span>
  <span m='635420'>count?</span> <span m='637560'>Well,</span> <span m='638230'>my</span>
  <span m='638520'>gosh,</span> <span m='639580'>if I</span> <span m='639700'>substitute</span>
  <span m='640080'>for</span> <span m='640200'>here and</span> <span m='640550'>here,</span>
  <span m='642010'>they're</span> <span m='642150'>different</span> <span m='642480'>ones.</span>
  <span m='644540'>It's</span> <span m='644650'>not</span> <span m='644820'>the</span>
  <span m='644880'>same</span> <span m='645160'>count</span> <span m='645450'>any</span>
  <span m='645590'>more.</span> <span m='646570'>I</span> <span m='646680'>get</span>
  <span m='646820'>the</span> <span m='646890'>wrong</span> <span m='647160'>answer.</span>
  <span m='647880'>The</span> <span m='648220'>substitution</span> <span m='648720'>model</span>
  <span m='648950'>is</span> <span m='649000'>a static</span> <span m='649440'>phenomenon</span>
  <span m='651270'>that</span> <span m='651410'>describes</span> <span m='651840'>things</span>
  <span m='652070'>that</span> <span m='652140'>are</span> <span m='652220'>true</span>
  <span m='654100'>and</span> <span m='654220'>not</span> <span m='654550'>things</span>
  <span m='654640'>that</span> <span m='654720'>change.</span> <span m='655560'>Here,</span>
  <span m='655770'>we</span> <span m='655860'>have</span> <span m='656010'>truths</span>
  <span m='656320'>that</span> <span m='656510'>change.</span> </p><p><span m='661860'>OK,
  Well,</span> <span m='662200'>before</span> <span m='662680'>I</span> <span m='662790'>give</span>
  <span m='662980'>you</span> <span m='664270'>any</span> <span m='665740'>understanding</span>
  <span m='666470'>of</span> <span m='666560'>this,</span> <span m='666770'>this</span>
  <span m='666920'>is</span> <span m='667080'>very</span> <span m='667330'>bad.</span>
  <span m='667870'>Now,</span> <span m='668060'>we've</span> <span m='668200'>lost</span>
  <span m='668450'>our</span> <span m='668530'>model</span> <span m='668810'>of</span>
  <span m='668890'>computation.</span> <span m='671520'>Pretty</span> <span m='671730'>soon,</span>
  <span m='672040'>I'm going to</span> <span m='672110'>have</span> <span m='672220'>to</span>
  <span m='672300'>build</span> <span m='672490'>you</span> <span m='672610'>a</span>
  <span m='672650'>new</span> <span m='672790'>model</span> <span m='673090'>of</span>
  <span m='673420'>computation.</span> <span m='675030'>But</span> <span m='675250'>ours</span>
  <span m='675630'>plays</span> <span m='675840'>with</span> <span m='675980'>this,</span>
  <span m='676180'>just</span> <span m='676420'>now,</span> <span m='676760'>in</span>
  <span m='676880'>an</span> <span m='676970'>informal</span> <span m='677430'>sense.</span>
  <span m='678710'>Of</span> <span m='678750'>course,</span> <span m='678970'>what
  you</span> <span m='679180'>already</span> <span m='679550'>see</span> <span m='680650'>is</span>
  <span m='680810'>that</span> <span m='680970'>when</span> <span m='681100'>I</span>
  <span m='681190'>have</span> <span m='681490'>something</span> <span m='681790'>like</span>
  <span m='681990'>assignment,</span> <span m='682950'>the</span> <span m='683340'>model</span>
  <span m='683690'>that</span> <span m='683830'>we're</span> <span m='683920'>going</span>
  <span m='683990'>to</span> <span m='684070'>need</span> <span m='684600'>is</span>
  <span m='684860'>different</span> <span m='685190'>from</span> <span m='685340'>the</span>
  <span m='685420'>model</span> <span m='685680'>that</span> <span m='685820'>we</span>
  <span m='685960'>had</span> <span m='686260'>before</span> <span m='686990'>in</span>
  <span m='687220'>that</span> <span m='687500'>the</span> <span m='687760'>variables,</span>
  <span m='688390'>those</span> <span m='688770'>symbols</span> <span m='689220'>like</span>
  <span m='689520'>count,</span> <span m='690270'>or</span> <span m='690460'>x</span>
  <span m='691010'>are</span> <span m='691260'>no</span> <span m='691480'>longer</span>
  <span m='691840'>going</span> <span m='691960'>to</span> <span m='692080'>refer</span>
  <span m='692550'>to</span> <span m='692780'>the</span> <span m='692900'>values</span>
  <span m='693390'>they</span> <span m='693680'>have,</span> <span m='694100'>but</span>
  <span m='694380'>rather</span> <span m='694650'>to</span> <span m='694820'>some</span>
  <span m='695010'>sort</span> <span m='695160'>of</span> <span m='695250'>place</span>
  <span m='696020'>where</span> <span m='696180'>the</span> <span m='696300'>value</span>
  <span m='696610'>restored.</span> </p><p><span m='697810'>We're</span> <span m='697970'>going
  to</span> <span m='698090'>have to</span> <span m='698180'>think</span> <span m='698390'>that</span>
  <span m='698620'>way</span> <span m='698770'>for</span> <span m='698930'>a</span>
  <span m='698960'>while.</span> <span m='700330'>And it's</span> <span m='700520'>going</span>
  <span m='700620'>to</span> <span m='700720'>be</span> <span m='700830'>a</span>
  <span m='700930'>very</span> <span m='701190'>bad</span> <span m='701590'>thing</span>
  <span m='701900'>and</span> <span m='702290'>cause</span> <span m='702570'>a</span>
  <span m='702610'>lot</span> <span m='702900'>of</span> <span m='702960'>trouble.</span>
  <span m='704590'>And</span> <span m='704770'>so,</span> <span m='705060'>as</span>
  <span m='705170'>I</span> <span m='705230'>said,</span> <span m='705590'>the</span>
  <span m='705780'>very</span> <span m='706060'>fact</span> <span m='706250'>that</span>
  <span m='706450'>we're</span> <span m='706540'>inventing</span> <span m='706950'>this</span>
  <span m='707350'>bad</span> <span m='707800'>thing,</span> <span m='708270'>means</span>
  <span m='708540'>that</span> <span m='708650'>there</span> <span m='708760'>had</span>
  <span m='708900'>better</span> <span m='709080'>be</span> <span m='709190'>a</span>
  <span m='709240'>good</span> <span m='709400'>reason</span> <span m='709750'>for</span>
  <span m='709990'>it,</span> <span m='710610'>otherwise,</span> <span m='711110'>just</span>
  <span m='711350'>a</span> <span m='711390'>waste</span> <span m='711680'>of</span>
  <span m='711760'>time</span> <span m='712040'>and a</span> <span m='712150'>lot</span>
  <span m='712270'>of</span> <span m='712390'>effort.</span> </p><p><span m='713510'>Let's</span>
  <span m='713710'>just</span> <span m='713850'>look</span> <span m='714020'>at</span>
  <span m='714080'>some</span> <span m='714250'>of</span> <span m='714400'>it</span>
  <span m='714820'>just</span> <span m='714990'>to</span> <span m='715070'>play.</span>
  <span m='716090'>Supposing</span> <span m='716560'>we</span> <span m='717020'>write</span>
  <span m='717250'>down</span> <span m='717460'>the</span> <span m='717560'>functional</span>
  <span m='718070'>version,</span> <span m='718570'>functional</span> <span m='719130'>meaning</span>
  <span m='719510'>in</span> <span m='719630'>the</span> <span m='719720'>old</span>
  <span m='719960'>style,</span> <span m='722030'>of</span> <span m='722270'>factorial</span>
  <span m='722530'>by</span> <span m='722770'>an</span> <span m='723400'>iterative</span>
  <span m='724030'>process.</span> <span m='729780'>Factorial</span> <span m='731935'>of</span>
  <span m='732885'>n,</span> <span m='738110'>we're</span> <span m='738390'>going</span>
  <span m='738670'>to</span> <span m='738930'>iterate</span> <span m='742660'>of</span>
  <span m='743010'>m</span> <span m='743350'>and</span> <span m='743650'>i,</span>
  <span m='746230'>which</span> <span m='746410'>says</span> <span m='746810'>if</span>
  <span m='750950'>i</span> <span m='751680'>is</span> <span m='751870'>greater</span>
  <span m='752170'>than</span> <span m='752430'>n,</span> <span m='753700'>then</span>
  <span m='754060'>the</span> <span m='754140'>result</span> <span m='754550'>is</span>
  <span m='754680'>m,</span> <span m='756430'>otherwise,</span> <span m='760030'>the</span>
  <span m='760180'>result of</span> <span m='760530'>iterating</span> <span m='763650'>the</span>
  <span m='764040'>product</span> <span m='765240'>of</span> <span m='765560'>i</span>
  <span m='765740'>and</span> <span m='765940'>m.</span> <span m='766930'>So</span>
  <span m='767580'>m</span> <span m='767750'>is</span> <span m='767930'>going</span>
  <span m='768210'>to</span> <span m='768350'>be</span> <span m='768560'>the</span>
  <span m='768670'>product</span> <span m='769050'>that I'm</span> <span m='769200'>accumulating.</span>
  <span m='771690'>m is</span> <span m='772100'>the</span> <span m='772190'>product.</span>
  <span m='778170'>And</span> <span m='778420'>the</span> <span m='778520'>count</span>
  <span m='778820'>I'm</span> <span m='778910'>going to</span> <span m='779060'>increase</span>
  <span m='779460'>by</span> <span m='779590'>one.</span> <span m='784810'>Plus,</span>
  <span m='785920'>ITER,</span> <span m='786860'>ELSE,</span> <span m='789590'>COND,</span>
  <span m='790190'>define.</span> </p><p><span m='792060'>I'm</span> <span m='792230'>going
  to</span> <span m='792300'>start</span> <span m='792590'>this</span> <span m='792770'>up.</span>
  <span m='797000'>And</span> <span m='797490'>these</span> <span m='797690'>days,</span>
  <span m='797920'>you</span> <span m='798010'>should</span> <span m='798140'>have</span>
  <span m='798260'>no</span> <span m='798410'>trouble</span> <span m='798690'>reading</span>
  <span m='798980'>something</span> <span m='799300'>like</span> <span m='799510'>this.</span>
  <span m='801020'>What</span> <span m='801130'>I</span> <span m='801250'>have</span>
  <span m='801520'>here</span> <span m='802060'>is</span> <span m='802880'>a</span>
  <span m='803000'>product</span> <span m='803430'>there</span> <span m='803540'>being</span>
  <span m='803750'>accumulated</span> <span m='804390'>and</span> <span m='804490'>a</span>
  <span m='804590'>counter.</span> <span m='806750'>I</span> <span m='806840'>start</span>
  <span m='807160'>them</span> <span m='807320'>up</span> <span m='807450'>both</span>
  <span m='807690'>at</span> <span m='807790'>one.</span> <span m='809050'>I'm</span>
  <span m='809190'>going</span> <span m='809330'>to</span> <span m='809610'>buzz</span>
  <span m='809920'>the</span> <span m='810030'>counter</span> <span m='810440'>up,</span>
  <span m='811140'>i</span> <span m='811350'>goes to</span> <span m='811620'>i</span>
  <span m='811800'>plus</span> <span m='812030'>one</span> <span m='812210'>every</span>
  <span m='812380'>time</span> <span m='812570'>around.</span> <span m='814800'>But</span>
  <span m='814970'>that's</span> <span m='815180'>only</span> <span m='815570'>our</span>
  <span m='815730'>putting</span> <span m='816040'>a</span> <span m='816120'>time</span>
  <span m='816460'>on</span> <span m='816740'>the</span> <span m='816820'>process,</span>
  <span m='818600'>each</span> <span m='818810'>of</span> <span m='818910'>this is</span>
  <span m='819080'>just</span> <span m='819320'>a</span> <span m='819520'>set of truths,</span>
  <span m='820630'>true</span> <span m='820850'>rules.</span> <span m='822840'>And</span>
  <span m='823220'>m</span> <span m='823480'>is</span> <span m='823600'>going</span>
  <span m='823830'>to</span> <span m='824510'>get</span> <span m='824600'>a</span>
  <span m='824700'>new</span> <span m='824860'>values</span> <span m='825310'>of</span>
  <span m='825410'>i</span> <span m='825620'>and</span> <span m='825740'>m,</span>
  <span m='826200'>i</span> <span m='826370'>times</span> <span m='826730'>m</span>
  <span m='827010'>each</span> <span m='827180'>time</span> <span m='827370'>around,</span>
  <span m='828740'>and</span> <span m='828900'>eventually</span> <span m='829330'>i</span>
  <span m='829460'>is</span> <span m='829600'>going</span> <span m='829680'>to</span>
  <span m='829770'>be</span> <span m='829860'>bigger</span> <span m='830090'>than</span>
  <span m='830260'>n,</span> <span m='830550'>in</span> <span m='830600'>which</span>
  <span m='830770'>case,</span> <span m='830970'>the</span> <span m='831090'>answer's</span>
  <span m='831400'>going</span> <span m='831490'>to</span> <span m='831580'>be</span>
  <span m='831680'>m.</span> </p><p><span m='832750'>Now,</span> <span m='832890'>I'm</span>
  <span m='833340'>speaking</span> <span m='833790'>to</span> <span m='834020'>you,
  use</span> <span m='834240'>time</span> <span m='834530'>in</span> <span m='834760'>this.</span>
  <span m='835760'>That's just</span> <span m='836150'>because</span> <span m='836300'>I</span>
  <span m='836390'>know</span> <span m='836530'>how</span> <span m='836690'>the</span>
  <span m='836750'>computer</span> <span m='837100'>works.</span> <span m='838210'>But</span>
  <span m='838490'>I</span> <span m='838560'>didn't</span> <span m='838760'>have</span>
  <span m='838920'>to.</span> <span m='839090'>This</span> <span m='839240'>could</span>
  <span m='839350'>be</span> <span m='839480'>a</span> <span m='839540'>purely</span>
  <span m='839920'>mathematical</span> <span m='840570'>description</span> <span m='841630'>at</span>
  <span m='841810'>this</span> <span m='841990'>point,</span> <span m='842430'>because</span>
  <span m='842530'>substitution</span> <span m='843040'>will</span> <span m='843150'>work</span>
  <span m='843370'>for</span> <span m='843460'>this.</span> </p><p><span m='845280'>But</span>
  <span m='845470'>let's</span> <span m='845670'>set</span> <span m='845800'>right</span>
  <span m='845990'>down</span> <span m='846490'>a</span> <span m='846640'>similar</span>
  <span m='847030'>sort</span> <span m='847160'>of</span> <span m='847290'>program,</span>
  <span m='848660'>using</span> <span m='848870'>the</span> <span m='848940'>same</span>
  <span m='849220'>algorithm,</span> <span m='850690'>but</span> <span m='851470'>with</span>
  <span m='851630'>assignments.</span> <span m='855296'>So</span> <span m='855780'>this
  is</span> <span m='855960'>called the</span> <span m='856230'>functional</span>
  <span m='856670'>version.</span> <span m='863840'>I</span> <span m='863930'>want</span>
  <span m='864100'>to</span> <span m='864140'>write</span> <span m='864300'>down</span>
  <span m='864540'>an</span> <span m='864650'>imperative</span> <span m='864930'>version.</span>
  <span m='874150'>Factorial</span> <span m='874585'>of</span> <span m='875020'>n.</span>
  <span m='876010'>I'm going to</span> <span m='876280'>create</span> <span m='876670'>my</span>
  <span m='876830'>two</span> <span m='877090'>variables.</span> <span m='880120'>Let</span>
  <span m='883130'>i</span> <span m='884000'>initialize</span> <span m='884550'>itself</span>
  <span m='884870'>to</span> <span m='885000'>one,</span> <span m='886420'>and</span>
  <span m='887220'>m be</span> <span m='887390'>initialized</span> <span m='888100'>to</span>
  <span m='888230'>one,</span> <span m='888950'>similar.</span> </p><p><span m='890930'>We'll</span>
  <span m='891380'>create</span> <span m='891640'>a</span> <span m='891690'>loop</span>
  <span m='899350'>which</span> <span m='899670'>has</span> <span m='900680'>COND</span>
  <span m='903530'>greater</span> <span m='903820'>than</span> <span m='904190'>i,</span>
  <span m='905150'>and</span> <span m='905470'>if</span> <span m='905630'>i</span>
  <span m='905840'>is greater</span> <span m='906130'>than</span> <span m='906300'>n,</span>
  <span m='906470'>we're</span> <span m='906640'>done.</span> <span m='907360'>And</span>
  <span m='907610'>the</span> <span m='907700'>result</span> <span m='908170'>is</span>
  <span m='908390'>m,</span> <span m='909030'>the</span> <span m='909110'>product</span>
  <span m='909490'>I'm</span> <span m='909630'>accumulating.</span> <span m='910910'>Otherwise,</span>
  <span m='915410'>I'm going to</span> <span m='915770'>write</span> <span m='916010'>down</span>
  <span m='916240'>three</span> <span m='916510'>things</span> <span m='916790'>to</span>
  <span m='916880'>do.</span> <span m='919320'>I'm</span> <span m='919510'>going</span>
  <span m='919660'>to</span> <span m='919820'>set!</span> <span m='922300'>m</span>
  <span m='923630'>to</span> <span m='923840'>the</span> <span m='923980'>product</span>
  <span m='925460'>of</span> <span m='925690'>i</span> <span m='926130'>and</span>
  <span m='926410'>m,</span> <span m='929370'>set!</span> <span m='929800'>i</span>
  <span m='932930'>to</span> <span m='933730'>the</span> <span m='933880'>sum</span>
  <span m='934240'>of</span> <span m='934310'>i and</span> <span m='934610'>one,</span>
  <span m='937540'>and</span> <span m='938080'>go</span> <span m='938210'>around</span>
  <span m='938460'>the</span> <span m='938650'>loop</span> <span m='939080'>again.</span>
  <span m='940610'>Looks</span> <span m='940820'>very</span> <span m='941060'>familiar</span>
  <span m='941450'>to</span> <span m='941510'>you</span> <span m='941890'>FORTRAN</span>
  <span m='942290'>programmers.</span> <span m='944890'>ELSE,</span> <span m='945610'>COND,</span>
  <span m='946110'>define,</span> <span m='946710'>funny</span> <span m='946950'>syntax</span>
  <span m='947500'>though.</span> <span m='951270'>Start</span> <span m='951540'>the</span>
  <span m='951610'>loop</span> <span m='951890'>up,</span> <span m='956280'>and</span>
  <span m='956560'>that's</span> <span m='956810'>the</span> <span m='956870'>program.</span>
  </p><p><span m='959320'>Now,</span> <span m='959480'>this</span> <span m='959690'>program,</span>
  <span m='961220'>how</span> <span m='961620'>do we</span> <span m='961750'>think</span>
  <span m='961940'>about</span> <span m='962250'>it?</span> <span m='962790'>Well,
  let's</span> <span m='962960'>just</span> <span m='963060'>say</span> <span m='963230'>what</span>
  <span m='963450'>we're</span> <span m='963590'>seeing</span> <span m='963910'>here.</span>
  <span m='964690'>There</span> <span m='965130'>are</span> <span m='965320'>two</span>
  <span m='965780'>local</span> <span m='966110'>variables, i and m,</span> <span
  m='967480'>that</span> <span m='967630'>have</span> <span m='967720'>been</span>
  <span m='967820'>initialized</span> <span m='968340'>to</span> <span m='968430'>one.</span>
  <span m='970810'>Every</span> <span m='971090'>time</span> <span m='971310'>around</span>
  <span m='971510'>the</span> <span m='971860'>loop,</span> <span m='972070'>I</span>
  <span m='972210'>test to</span> <span m='972280'>see</span> <span m='972460'>if</span>
  <span m='972530'>i</span> <span m='972760'>is</span> <span m='972900'>greater</span>
  <span m='973120'>than</span> <span m='973300'>n,</span> <span m='974030'>which</span>
  <span m='974230'>is the</span> <span m='974320'>input</span> <span m='974580'>argument,</span>
  <span m='975470'>and</span> <span m='975660'>if</span> <span m='975740'>so,</span>
  <span m='975930'>the</span> <span m='976040'>result</span> <span m='976420'>is</span>
  <span m='976490'>the</span> <span m='976580'>product</span> <span m='976880'>being</span>
  <span m='977080'>accumulated</span> <span m='977530'>in</span> <span m='977940'>m.</span>
  <span m='979240'>However,</span> <span m='979700'>if it's</span> <span m='979960'>not</span>
  <span m='980270'>the</span> <span m='980450'>end</span> <span m='980620'>of</span>
  <span m='980720'>the</span> <span m='980790'>loop,</span> <span m='981300'>if</span>
  <span m='981470'>I'm</span> <span m='982290'>not</span> <span m='982520'>done,</span>
  <span m='983640'>then</span> <span m='983890'>what</span> <span m='984060'>I'm going
  to</span> <span m='984230'>do</span> <span m='984470'>is</span> <span m='984630'>change</span>
  <span m='984910'>the</span> <span m='985040'>product</span> <span m='985830'>to</span>
  <span m='986040'>be</span> <span m='986160'>the</span> <span m='986260'>result</span>
  <span m='986600'>of</span> <span m='986670'>multiplying</span> <span m='987220'>i</span>
  <span m='987420'>times</span> <span m='987710'>the</span> <span m='987800'>current</span>
  <span m='988080'>product.</span> </p><p><span m='989130'>Which is</span> <span m='989280'>sort</span>
  <span m='989480'>of</span> <span m='989530'>what</span> <span m='989670'>we were</span>
  <span m='989880'>doing</span> <span m='990170'>here.</span> <span m='991530'>Except</span>
  <span m='991660'>here</span> <span m='991860'>I</span> <span m='991900'>wasn't</span>
  <span m='992150'>changing.</span> <span m='993386'>I</span> <span m='993750'>was</span>
  <span m='993860'>making</span> <span m='994140'>another</span> <span m='995090'>copy,</span>
  <span m='996410'>because</span> <span m='996830'>the</span> <span m='997120'>substitution</span>
  <span m='997730'>model</span> <span m='998220'>says,</span> <span m='998550'>you</span>
  <span m='998670'>copy</span> <span m='999200'>the</span> <span m='999460'>body</span>
  <span m='1001110'>of</span> <span m='1001260'>the</span> <span m='1001350'>procedure</span>
  <span m='1003030'>with</span> <span m='1003310'>the</span> <span m='1003860'>arguments</span>
  <span m='1004410'>substituted</span> <span m='1004850'>for</span> <span m='1004920'>the</span>
  <span m='1004990'>formal</span> <span m='1005310'>parameters.</span> <span m='1006710'>Here</span>
  <span m='1006970'>I'm</span> <span m='1007040'>not</span> <span m='1007220'>worried</span>
  <span m='1007370'>about</span> <span m='1007580'>copying,</span> <span m='1008540'>here</span>
  <span m='1008835'>I've</span> <span m='1009130'>changed</span> <span m='1009590'>the</span>
  <span m='1009690'>value</span> <span m='1010030'>of</span> <span m='1010080'>m.</span>
  <span m='1011990'>I</span> <span m='1012170'>also</span> <span m='1012470'>then</span>
  <span m='1012670'>change</span> <span m='1013010'>the</span> <span m='1013080'>value</span>
  <span m='1013390'>of</span> <span m='1013600'>i</span> <span m='1013890'>to</span>
  <span m='1014240'>i plus</span> <span m='1014550'>one,</span> <span m='1015790'>and</span>
  <span m='1015940'>go</span> <span m='1016090'>buzzing</span> <span m='1016450'>around.</span>
  </p><p><span m='1018300'>Seems</span> <span m='1018490'>like</span> <span m='1018650'>essentially</span>
  <span m='1019080'>the</span> <span m='1019160'>same</span> <span m='1019430'>program,</span>
  <span m='1020880'>but</span> <span m='1021200'>there</span> <span m='1021310'>are</span>
  <span m='1021360'>some</span> <span m='1021580'>ways</span> <span m='1021840'>of</span>
  <span m='1021920'>making</span> <span m='1022230'>errors</span> <span m='1022540'>here</span>
  <span m='1022880'>that</span> <span m='1023110'>didn't</span> <span m='1023330'>exist</span>
  <span m='1024510'>until</span> <span m='1024920'>today.</span> <span m='1026160'>For</span>
  <span m='1026400'>example,</span> <span m='1027609'>if</span> <span m='1027819'>I</span>
  <span m='1027920'>were</span> <span m='1028020'>to</span> <span m='1028099'>do</span>
  <span m='1028250'>the</span> <span m='1028359'>horrible</span> <span m='1028800'>thing</span>
  <span m='1030079'>of</span> <span m='1030490'>not</span> <span m='1030660'>being</span>
  <span m='1030810'>careful</span> <span m='1031119'>in</span> <span m='1031180'>writing</span>
  <span m='1031400'>my</span> <span m='1031510'>program</span> <span m='1032579'>and</span>
  <span m='1033079'>interchange</span> <span m='1035069'>those</span> <span m='1035329'>two</span>
  <span m='1035460'>assignments,</span> <span m='1036760'>the</span> <span m='1037300'>program</span>
  <span m='1037630'>wouldn't</span> <span m='1037890'>compute</span> <span m='1038010'>the</span>
  <span m='1038109'>same</span> <span m='1038349'>function.</span> </p><p><span m='1040339'>I</span>
  <span m='1040470'>get</span> <span m='1040609'>a</span> <span m='1040690'>timing</span>
  <span m='1041119'>error</span> <span m='1041339'>because</span> <span m='1041650'>there's
  a</span> <span m='1041839'>dependency</span> <span m='1042700'>that</span> <span
  m='1044550'>m</span> <span m='1044859'>depends</span> <span m='1045240'>upon</span>
  <span m='1045480'>having</span> <span m='1045750'>the</span> <span m='1045960'>last</span>
  <span m='1046170'>value</span> <span m='1046560'>of</span> <span m='1046940'>i.</span>
  <span m='1047460'>If</span> <span m='1047650'>I</span> <span m='1047750'>try</span>
  <span m='1047980'>to</span> <span m='1048200'>i</span> <span m='1048440'>first,</span>
  <span m='1050914'>then</span> <span m='1051390'>I've</span> <span m='1051610'>got</span>
  <span m='1051740'>the</span> <span m='1051820'>wrong</span> <span m='1052070'>value</span>
  <span m='1052240'>of</span> <span m='1052350'>i</span> <span m='1052570'>when</span>
  <span m='1052760'>I</span> <span m='1052820'>multiply</span> <span m='1053380'>by</span>
  <span m='1053520'>m.</span> <span m='1056060'>It's</span> <span m='1056210'>a</span>
  <span m='1056260'>bug</span> <span m='1056520'>that</span> <span m='1056650'>wasn't</span>
  <span m='1056890'>available</span> <span m='1057390'>until</span> <span m='1057660'>this</span>
  <span m='1057830'>moment,</span> <span m='1058600'>until we</span> <span m='1058820'>introduced</span>
  <span m='1059330'>something</span> <span m='1059690'>that had</span> <span m='1060000'>time</span>
  <span m='1060340'>in it.</span> </p><p><span m='1063470'>So,</span> <span m='1063710'>as</span>
  <span m='1063830'>I</span> <span m='1063930'>said,</span> <span m='1065540'>first</span>
  <span m='1065840'>we</span> <span m='1065930'>need</span> <span m='1066100'>a</span>
  <span m='1066120'>new</span> <span m='1066260'>model</span> <span m='1066510'>of</span>
  <span m='1066610'>computation,</span> <span m='1067520'>and</span> <span m='1067650'>second,</span>
  <span m='1067880'>we</span> <span m='1067970'>have</span> <span m='1068090'>to</span>
  <span m='1068260'>be</span> <span m='1068390'>damn</span> <span m='1068650'>good</span>
  <span m='1068800'>reason</span> <span m='1069140'>for</span> <span m='1069270'>doing</span>
  <span m='1069580'>this</span> <span m='1069790'>kind</span> <span m='1069960'>of</span>
  <span m='1070070'>ugly</span> <span m='1070390'>thing.</span> <span m='1072800'>Are</span>
  <span m='1072920'>there</span> <span m='1073060'>any</span> <span m='1073180'>questions?</span>
  <span m='1078800'>Speak</span> <span m='1079050'>loudly,</span> <span m='1079410'>David.</span>
  </p><p><span m='1080505'>AUDIENCE:</span> <span m='1080880'>I'm</span> <span m='1081020'>confused</span>
  <span m='1081590'>about,</span> <span m='1082030'>we've</span> <span m='1082250'>introduced</span>
  <span m='1082730'>set</span> <span m='1082990'>now,</span> <span m='1083960'>but</span>
  <span m='1084220'>we</span> <span m='1084340'>had</span> <span m='1084600'>let</span>
  <span m='1084920'>before and</span> <span m='1085340'>define</span> <span m='1085870'>before.</span>
  <span m='1087630'>I'm</span> <span m='1087770'>confused</span> <span m='1088130'>about</span>
  <span m='1088270'>the</span> <span m='1088400'>difference</span> <span m='1088820'>between</span>
  <span m='1089160'>the</span> <span m='1089250'>three.</span> <span m='1089980'>Wouldn't</span>
  <span m='1090300'>define</span> <span m='1091030'>work</span> <span m='1091370'>in</span>
  <span m='1091440'>the</span> <span m='1091520'>same</span> <span m='1091820'>situation</span>
  <span m='1092440'>as</span> <span m='1092740'>set</span> <span m='1093060'>if</span>
  <span m='1093270'>you</span> <span m='1094100'>introduced</span> <span m='1094520'>it</span>
  <span m='1094640'>a</span> <span m='1094960'>bit?</span> </p><p><span m='1095280'>PROFESSOR:</span>
  <span m='1095780'>No,  define</span> <span m='1096440'>is</span> <span m='1096790'>intended</span>
  <span m='1097360'>for</span> <span m='1097530'>setting</span> <span m='1097830'>something</span>
  <span m='1098230'>once</span> <span m='1098510'>the</span> <span m='1098610'>first</span>
  <span m='1098910'>time,</span> <span m='1099350'>for</span> <span m='1099550'>making</span>
  <span m='1100010'>it.</span> <span m='1102790'>You've</span> <span m='1103060'>never</span>
  <span m='1103290'>seen</span> <span m='1103470'>me</span> <span m='1103630'>write</span>
  <span m='1103830'>on</span> <span m='1103910'>a</span> <span m='1104000'>blackboard</span>
  <span m='1105560'>two</span> <span m='1105870'>defines</span> <span m='1106280'>in</span>
  <span m='1106370'>a</span> <span m='1106440'>row</span> <span m='1106910'>whose</span>
  <span m='1107360'>intention</span> <span m='1109090'>was</span> <span m='1109260'>to</span>
  <span m='1109370'>change</span> <span m='1109810'>the</span> <span m='1109960'>old</span>
  <span m='1110180'>value</span> <span m='1110560'>of</span> <span m='1110640'>some</span>
  <span m='1110940'>variable</span> <span m='1111350'>to</span> <span m='1111440'>a</span>
  <span m='1111540'>new</span> <span m='1111700'>one.</span> </p><p><span m='1111970'>AUDIENCE:</span>
  <span m='1112170'>Is</span> <span m='1112410'>that</span> <span m='1113070'>by</span>
  <span m='1113260'>convention</span> <span m='1113990'>or--</span> </p><p><span m='1114380'>PROFESSOR:</span>
  <span m='1115260'>No, it's</span> <span m='1115650'>intention.</span> <span m='1118120'>The</span>
  <span m='1118310'>answer</span> <span m='1118700'>is</span> <span m='1119460'>that,</span>
  <span m='1120010'>for</span> <span m='1120150'>example,</span> <span m='1121000'>internal</span>
  <span m='1121490'>to</span> <span m='1121590'>a</span> <span m='1121680'>procedure,</span>
  <span m='1123070'>two</span> <span m='1123430'>defines</span> <span m='1123830'>in</span>
  <span m='1123930'>a</span> <span m='1123980'>row</span> <span m='1124820'>are</span>
  <span m='1125430'>illegal,</span> <span m='1126770'>two</span> <span m='1126920'>defines</span>
  <span m='1127250'>in a</span> <span m='1127370'>row</span> <span m='1127540'>of</span>
  <span m='1127640'>the</span> <span m='1127740'>same</span> <span m='1128000'>variable.</span>
  <span m='1129850'>x</span> <span m='1130530'>can't</span> <span m='1130650'>be</span>
  <span m='1130730'>defined</span> <span m='1131260'>twice.</span> <span m='1131890'>Whether</span>
  <span m='1132160'>or</span> <span m='1132210'>not</span> <span m='1132420'>a</span>
  <span m='1132460'>system</span> <span m='1132840'>catches</span> <span m='1133200'>that</span>
  <span m='1133470'>error</span> <span m='1133740'>is</span> <span m='1134020'>a</span>
  <span m='1134300'>different</span> <span m='1134680'>question,</span> <span m='1136010'>but</span>
  <span m='1136690'>I</span> <span m='1136860'>legislate</span> <span m='1137450'>to</span>
  <span m='1137540'>you</span> <span m='1138290'>that</span> <span m='1138430'>define</span>
  <span m='1138840'>happens</span> <span m='1139330'>once</span> <span m='1139850'>on</span>
  <span m='1140010'>anything.</span> </p><p><span m='1140840'>Now,</span> <span m='1141100'>indeed,
  in</span> <span m='1141470'>interactive</span> <span m='1142040'>debugging,</span>
  <span m='1143480'>we</span> <span m='1143700'>intend</span> <span m='1144190'>that</span>
  <span m='1144480'>you</span> <span m='1144770'>interacting</span> <span m='1145310'>with</span>
  <span m='1145460'>your</span> <span m='1145600'>computer</span> <span m='1146600'>will</span>
  <span m='1146770'>redefine</span> <span m='1147240'>things,</span> <span m='1148240'>and</span>
  <span m='1148370'>so</span> <span m='1148460'>there's</span> <span m='1148660'>a</span>
  <span m='1148700'>special</span> <span m='1149040'>exception</span> <span m='1149430'>made</span>
  <span m='1150050'>for</span> <span m='1150210'>interactive</span> <span m='1150630'>debugging.</span>
  <span m='1151610'>But</span> <span m='1152760'>define</span> <span m='1153560'>is</span>
  <span m='1153760'>intended</span> <span m='1154330'>to mean to</span> <span m='1155430'>set</span>
  <span m='1155760'>up</span> <span m='1155900'>something</span> <span m='1157740'>which</span>
  <span m='1158340'>will</span> <span m='1158480'>be</span> <span m='1158640'>forever</span>
  <span m='1159360'>that</span> <span m='1159730'>value</span> <span m='1160160'>after</span>
  <span m='1160420'>that</span> <span m='1160630'>point.</span> <span m='1162460'>It's</span>
  <span m='1162650'>as</span> <span m='1162760'>if</span> <span m='1162900'>all</span>
  <span m='1163050'>the</span> <span m='1163200'>defines</span> <span m='1163540'>were</span>
  <span m='1163650'>done</span> <span m='1163870'>at</span> <span m='1163940'>the</span>
  <span m='1164020'>beginning.</span> <span m='1166490'>In</span> <span m='1166640'>fact,</span>
  <span m='1167040'>the</span> <span m='1167400'>only</span> <span m='1167640'>legal</span>
  <span m='1167930'>place</span> <span m='1168170'>to</span> <span m='1168260'>put</span>
  <span m='1168480'>a</span> <span m='1168560'>define</span> <span m='1169280'>in</span>
  <span m='1169460'>Scheme,</span> <span m='1169870'>internal</span> <span m='1170290'>to</span>
  <span m='1170380'>a</span> <span m='1170460'>procedure,</span> <span m='1171120'>is</span>
  <span m='1171250'>just</span> <span m='1171840'>at</span> <span m='1172090'>the</span>
  <span m='1172150'>beginning</span> <span m='1172450'>of</span> <span m='1172530'>a</span>
  <span m='1172570'>lambda</span> <span m='1172800'>expression,</span> <span m='1176120'>the</span>
  <span m='1176290'>beginning</span> <span m='1176560'>of the</span> <span m='1176650'>body</span>
  <span m='1176970'>of</span> <span m='1177040'>a</span> <span m='1177110'>procedure.</span>
  </p><p><span m='1181750'>Now,</span> <span m='1183300'>let</span> <span m='1183540'>of</span>
  <span m='1183720'>course</span> <span m='1183910'>does</span> <span m='1184640'>nothing</span>
  <span m='1184920'>like</span> <span m='1185140'>either</span> <span m='1185430'>of</span>
  <span m='1185480'>that.</span> <span m='1186670'>I</span> <span m='1186950'>mean,</span>
  <span m='1188200'>if you</span> <span m='1188390'>look at</span> <span m='1188520'>what's</span>
  <span m='1188670'>happening</span> <span m='1189010'>with a</span> <span m='1189090'>let,</span>
  <span m='1190280'>this</span> <span m='1190520'>happens</span> <span m='1190850'>again</span>
  <span m='1191140'>exactly</span> <span m='1191650'>once.</span> <span m='1192220'>It</span>
  <span m='1192420'>sets</span> <span m='1192660'>up</span> <span m='1192760'>a</span>
  <span m='1192810'>context</span> <span m='1193270'>where</span> <span m='1193410'>i</span>
  <span m='1193610'>and</span> <span m='1193740'>m</span> <span m='1193960'>are</span>
  <span m='1194520'>values</span> <span m='1194920'>one</span> <span m='1195270'>and</span>
  <span m='1195410'>one.</span> <span m='1196820'>That</span> <span m='1197200'>context</span>
  <span m='1198880'>exists</span> <span m='1199290'>throughout</span> <span m='1199670'>this</span>
  <span m='1200070'>scope,</span> <span m='1201500'>this</span> <span m='1201630'>region</span>
  <span m='1202000'>of</span> <span m='1202090'>the</span> <span m='1202170'>program.</span>
  <span m='1205080'>However,</span> <span m='1205700'>you</span> <span m='1205840'>don't</span>
  <span m='1206020'>think</span> <span m='1206190'>of</span> <span m='1206370'>that
  let</span> <span m='1206720'>as</span> <span m='1208880'>setting</span> <span m='1209210'>i</span>
  <span m='1209370'>again.</span> <span m='1211110'>It</span> <span m='1211220'>doesn't</span>
  <span m='1211500'>change</span> <span m='1211820'>it.</span> <span m='1212350'>i</span>
  <span m='1212550'>never</span> <span m='1212790'>changes</span> <span m='1213240'>because</span>
  <span m='1213670'>of the</span> <span m='1213760'>let.</span> <span m='1215390'>i</span>
  <span m='1215500'>gets</span> <span m='1215700'>created</span> <span m='1216180'>because</span>
  <span m='1216480'>of</span> <span m='1216930'>let.</span> </p><p><span m='1218690'>In</span>
  <span m='1218970'>fact,</span> <span m='1219780'>the</span> <span m='1220060'>let</span>
  <span m='1220280'>is</span> <span m='1220490'>a</span> <span m='1220550'>very</span>
  <span m='1220730'>simple</span> <span m='1221070'>idea.</span> <span m='1222300'>Let</span>
  <span m='1222580'>does</span> <span m='1222760'>nothing</span> <span m='1223080'>more,</span>
  <span m='1224080'>Let</span> <span m='1226310'>a</span> <span m='1227970'>variable</span>
  <span m='1228650'>one</span> <span m='1229380'>to</span> <span m='1229930'>have</span>
  <span m='1230490'>value</span> <span m='1230930'>one;</span> <span m='1231370'>I'll</span>
  <span m='1231810'>write this</span> <span m='1232190'>down</span> <span m='1232380'>a</span>
  <span m='1232420'>little</span> <span m='1232680'>bit more</span> <span m='1232860'>neatly;</span>
  <span m='1237150'>Let's</span> <span m='1237660'>write,</span> <span m='1238900'>var</span>
  <span m='1240020'>one</span> <span m='1240420'>have</span> <span m='1240890'>value,</span>
  <span m='1241440'>the</span> <span m='1241530'>value</span> <span m='1241850'>of</span>
  <span m='1241910'>expression</span> <span m='1242340'>e1,</span> <span m='1243120'>and</span>
  <span m='1243890'>variable</span> <span m='1244500'>two,</span> <span m='1245720'>have</span>
  <span m='1245880'>this</span> <span m='1246050'>value of the</span> <span m='1246470'>expression</span>
  <span m='1246750'>e2,</span> <span m='1248200'>in an</span> <span m='1248470'>expression</span>
  <span m='1249030'>e3,</span> <span m='1251660'>is</span> <span m='1251870'>the</span>
  <span m='1251960'>same</span> <span m='1252330'>thing</span> <span m='1254170'>as</span>
  <span m='1257480'>a</span> <span m='1257630'>procedure</span> <span m='1259400'>of</span>
  <span m='1260060'>var</span> <span m='1260420'>one</span> <span m='1262140'>and</span>
  <span m='1262380'>var</span> <span m='1262620'>two,</span> <span m='1264550'>the</span>
  <span m='1264880'>formal</span> <span m='1265190'>parameters,</span> <span m='1267020'>and</span>
  <span m='1267230'>e3</span> <span m='1268010'>being</span> <span m='1268370'>the</span>
  <span m='1268460'>body,</span> <span m='1270950'>where</span> <span m='1271570'>var</span>
  <span m='1271980'>one</span> <span m='1272270'>is</span> <span m='1272520'>bound</span>
  <span m='1272790'>to</span> <span m='1272860'>the</span> <span m='1272940'>value</span>
  <span m='1273310'>of</span> <span m='1273510'>e1,</span> <span m='1274420'>and</span>
  <span m='1274670'>var</span> <span m='1275010'>two</span> <span m='1275700'>gets</span>
  <span m='1275900'>the</span> <span m='1276260'>value of</span> <span m='1276480'>e2.</span>
  </p><p><span m='1279590'>So</span> <span m='1280180'>this</span> <span m='1280420'>is,</span>
  <span m='1280540'>in</span> <span m='1280650'>fact,</span> <span m='1280920'>a</span>
  <span m='1280970'>perfectly</span> <span m='1281360'>understandable</span> <span
  m='1281880'>thing</span> <span m='1282050'>from a</span> <span m='1282200'>substitution</span>
  <span m='1282750'>point</span> <span m='1282940'>of</span> <span m='1283000'>view.</span>
  <span m='1284930'>This</span> <span m='1285220'>is</span> <span m='1285490'>really</span>
  <span m='1285790'>the</span> <span m='1285880'>same</span> <span m='1286130'>expression</span>
  <span m='1286900'>written</span> <span m='1287110'>in</span> <span m='1287200'>two</span>
  <span m='1287300'>different</span> <span m='1287550'>ways.</span> <span m='1291820'>In</span>
  <span m='1291960'>fact,</span> <span m='1292290'>the</span> <span m='1292370'>way</span>
  <span m='1292550'>the</span> <span m='1292670'>actual</span> <span m='1293000'>system</span>
  <span m='1293320'>works</span> <span m='1293650'>is</span> <span m='1293850'>this</span>
  <span m='1294030'>gets</span> <span m='1294220'>translated</span> <span m='1294680'>into</span>
  <span m='1294840'>this</span> <span m='1295010'>before</span> <span m='1295270'>anything</span>
  <span m='1295450'>happens.</span> </p><p><span m='1297311'>AUDIENCE:</span> <span
  m='1297750'>OK,</span> <span m='1298100'>I'm</span> <span m='1298190'>still</span>
  <span m='1298420'>unclear</span> <span m='1298800'>as</span> <span m='1298970'>then</span>
  <span m='1299170'>what</span> <span m='1299360'>makes</span> <span m='1299620'>the</span>
  <span m='1299690'>difference</span> <span m='1299940'>between</span> <span m='1300070'>a</span>
  <span m='1300190'>let</span> <span m='1300540'>and</span> <span m='1300650'>a</span>
  <span m='1300740'>define.</span> <span m='1301360'>They</span> <span m='1301610'>could--</span>
  </p><p><span m='1302125'>PROFESSOR:</span> <span m='1302430'>A</span> <span m='1302540'>define</span>
  <span m='1302980'>is</span> <span m='1303260'>a</span> <span m='1303410'>syntactic</span>
  <span m='1303780'>sugar,</span> <span m='1304620'>whereby,</span> <span m='1305570'>essentially</span>
  <span m='1306050'>a</span> <span m='1306130'>bunch</span> <span m='1306480'>of</span>
  <span m='1306800'>variables</span> <span m='1307210'>get</span> <span m='1307700'>created</span>
  <span m='1307860'>by lets</span> <span m='1308270'>and</span> <span m='1308390'>then</span>
  <span m='1308550'>set</span> <span m='1308720'>up</span> <span m='1308860'>once.</span>
  <span m='1317170'>OK,</span> <span m='1317460'>time</span> <span m='1317670'>for</span>
  <span m='1317790'>the</span> <span m='1317880'>first</span> <span m='1318150'>break,</span>
  <span m='1318430'>I</span> <span m='1318480'>think.</span> <span m='1318790'>Thank</span>
  <span m='1319050'>you.</span> <span m='1323480'>[MUSIC PLAYING]</span> </p><p><span
  m='1384430'>Well</span> <span m='1385210'>let's</span> <span m='1385490'>see.</span>
  <span m='1386530'>I</span> <span m='1386620'>now</span> <span m='1386810'>have</span>
  <span m='1386980'>to</span> <span m='1387170'>rebuild</span> <span m='1387760'>the</span>
  <span m='1387830'>model</span> <span m='1388250'>of computation,</span> <span m='1390240'>so</span>
  <span m='1390370'>you</span> <span m='1390520'>understand</span> <span m='1391010'>how</span>
  <span m='1391870'>some</span> <span m='1392210'>such</span> <span m='1392510'>mechanical</span>
  <span m='1393060'>mechanism</span> <span m='1393550'>could</span> <span m='1393690'>work</span>
  <span m='1394590'>that</span> <span m='1395120'>can</span> <span m='1395260'>do</span>
  <span m='1395460'>what we've</span> <span m='1395630'>just</span> <span m='1395880'>talked</span>
  <span m='1396170'>about.</span> <span m='1397600'>I</span> <span m='1397710'>just</span>
  <span m='1398000'>recently</span> <span m='1398410'>destroyed</span> <span m='1399690'>your</span>
  <span m='1400380'>substitution</span> <span m='1401020'>model.</span> <span m='1402730'>Unfortunately,</span>
  <span m='1403370'>this</span> <span m='1403530'>model is</span> <span m='1403870'>significantly</span>
  <span m='1404440'>more</span> <span m='1404600'>complicated</span> <span m='1405070'>than
  the</span> <span m='1405180'>substitution</span> <span m='1405630'>model.</span>
  </p><p><span m='1406380'>It's</span> <span m='1406750'>called</span> <span m='1406950'>the</span>
  <span m='1407050'>environment</span> <span m='1407620'>model.</span> <span m='1409010'>And</span>
  <span m='1409230'>I'm</span> <span m='1409350'>going</span> <span m='1409510'>to</span>
  <span m='1409600'>have</span> <span m='1409690'>to</span> <span m='1409780'>introduce</span>
  <span m='1410120'>some</span> <span m='1410320'>terminology,</span> <span m='1412130'>which</span>
  <span m='1412300'>is</span> <span m='1412380'>very</span> <span m='1412590'>good</span>
  <span m='1412800'>terminology</span> <span m='1413100'>for</span> <span m='1413400'>you
  to</span> <span m='1413550'>know</span> <span m='1413800'>anyway.</span> <span m='1414660'>It's</span>
  <span m='1414830'>about</span> <span m='1415130'>names.</span> <span m='1416640'>And</span>
  <span m='1416880'>we're</span> <span m='1416950'>going to</span> <span m='1417020'>give</span>
  <span m='1417240'>names</span> <span m='1417670'>to</span> <span m='1418050'>the</span>
  <span m='1418270'>kinds</span> <span m='1418590'>of</span> <span m='1418690'>names</span>
  <span m='1419080'>things</span> <span m='1419360'>have</span> <span m='1420040'>and</span>
  <span m='1420150'>the</span> <span m='1420270'>way</span> <span m='1420490'>those</span>
  <span m='1420700'>names are</span> <span m='1420920'>used.</span> <span m='1422720'>So</span>
  <span m='1422920'>this</span> <span m='1423070'>is</span> <span m='1423170'>a</span>
  <span m='1425100'>meta-description,</span> <span m='1427150'>if</span> <span m='1427300'>you</span>
  <span m='1427440'>will.</span> <span m='1428290'>Anyway,</span> <span m='1428740'>there  is</span>
  <span m='1428890'>a</span> <span m='1428970'>pile</span> <span m='1429340'>of</span>
  <span m='1429450'>an</span> <span m='1429560'>unfortunate</span> <span m='1430080'>terminology</span>
  <span m='1430660'>here,</span> <span m='1430840'>but</span> <span m='1430950'>we're</span>
  <span m='1431050'>going</span> <span m='1431120'>to</span> <span m='1431180'>need</span>
  <span m='1431400'>this</span> <span m='1431570'>to</span> <span m='1431650'>understand</span>
  <span m='1432350'>what's</span> <span m='1432530'>called</span> <span m='1432730'>the</span>
  <span m='1432810'>environment</span> <span m='1433290'>model.</span> <span m='1434770'>We're</span>
  <span m='1434950'>about</span> <span m='1435180'>to</span> <span m='1435240'>do</span>
  <span m='1435340'>a</span> <span m='1435390'>little</span> <span m='1435570'>bit</span>
  <span m='1435700'>of</span> <span m='1435810'>boring,</span> <span m='1436700'>dog-work</span>
  <span m='1437210'>here.</span> </p><p><span m='1438250'>Let's</span> <span m='1438410'>look</span>
  <span m='1438550'>at</span> <span m='1438640'>the</span> <span m='1439340'>first</span>
  <span m='1440450'>transparency.</span> <span m='1442280'>And</span> <span m='1442410'>we</span>
  <span m='1442580'>see</span> <span m='1443610'>a</span> <span m='1444760'>description</span>
  <span m='1445250'>of</span> <span m='1445360'>a</span> <span m='1445400'>word</span>
  <span m='1445770'>called</span> <span m='1446220'>bound.</span> <span m='1448880'>And</span>
  <span m='1449020'>we're</span> <span m='1449120'>going</span> <span m='1449190'>to</span>
  <span m='1449260'>say</span> <span m='1449580'>that</span> <span m='1449750'>a</span>
  <span m='1449800'>variable,</span> <span m='1450410'>v,</span> <span m='1451170'>is</span>
  <span m='1451390'>bound</span> <span m='1451760'>in</span> <span m='1451850'>an</span>
  <span m='1451980'>expression,</span> <span m='1452500'>e,</span> <span m='1453660'>if</span>
  <span m='1453840'>the</span> <span m='1453990'>meaning</span> <span m='1454880'>of</span>
  <span m='1455170'>e</span> <span m='1455500'>is</span> <span m='1455660'>unchanged</span>
  <span m='1456590'>by</span> <span m='1456740'>the</span> <span m='1456890'>uniform</span>
  <span m='1457330'>replacement</span> <span m='1459890'>of</span> <span m='1460030'>a</span>
  <span m='1460090'>variable</span> <span m='1461130'>w,</span> <span m='1461580'>not</span>
  <span m='1461810'>occurring</span> <span m='1462210'>in</span> <span m='1462520'>e,</span>
  <span m='1462650'>for</span> <span m='1462780'>every</span> <span m='1463065'>occurrence</span>
  <span m='1463350'>of</span> <span m='1463540'>v</span> <span m='1463850'>in</span>
  <span m='1464300'>e.</span> <span m='1465440'>Now</span> <span m='1465820'>that's</span>
  <span m='1466140'>a</span> <span m='1466190'>long</span> <span m='1466510'>sentence,</span>
  <span m='1467470'>so,</span> <span m='1467780'>I</span> <span m='1467860'>think,</span>
  <span m='1468030'>I'm</span> <span m='1468130'>going</span> <span m='1468190'>to</span>
  <span m='1468250'>have</span> <span m='1468390'>to</span> <span m='1468510'>say</span>
  <span m='1469020'>a</span> <span m='1469170'>little</span> <span m='1469370'>bit</span>
  <span m='1469510'>about</span> <span m='1469800'>that</span> <span m='1470000'>before</span>
  <span m='1470530'>we</span> <span m='1470720'>even</span> <span m='1471390'>fool</span>
  <span m='1471690'>around</span> <span m='1471950'>at</span> <span m='1472010'>all</span>
  <span m='1472210'>here.</span> </p><p><span m='1473490'>Bound</span> <span m='1473860'>variables</span>
  <span m='1474350'>we're</span> <span m='1474480'>talking</span> <span m='1474820'>about</span>
  <span m='1475030'>here.</span> <span m='1484030'>And</span> <span m='1484390'>you've</span>
  <span m='1484510'>seen</span> <span m='1484710'>lots</span> <span m='1485080'>of</span>
  <span m='1485220'>them.</span> <span m='1486710'>You</span> <span m='1486810'>may</span>
  <span m='1486940'>not</span> <span m='1487150'>know</span> <span m='1487330'>that</span>
  <span m='1487450'>you've</span> <span m='1487590'>seen</span> <span m='1487770'>lots</span>
  <span m='1488040'>of</span> <span m='1488100'>them.</span> <span m='1488170'>Well,</span>
  <span m='1488390'>I</span> <span m='1488510'>suppose</span> <span m='1489010'>in</span>
  <span m='1489150'>your</span> <span m='1489730'>logic</span> <span m='1490550'>you
  saw</span> <span m='1490710'>a</span> <span m='1490840'>logical</span> <span m='1491320'>variables</span>
  <span m='1491880'>like,</span> <span m='1493310'>for</span> <span m='1493620'>every</span>
  <span m='1494220'>x</span> <span m='1494610'>there</span> <span m='1494890'>exists</span>
  <span m='1495910'>a</span> <span m='1495990'>y</span> <span m='1496590'>such</span>
  <span m='1496730'>that</span> <span m='1497120'>p</span> <span m='1497410'>is</span>
  <span m='1497530'>true of</span> <span m='1497900'>x</span> <span m='1498210'>and</span>
  <span m='1498410'>y</span> <span m='1498690'>from</span> <span m='1498870'>your</span>
  <span m='1499010'>calculus</span> <span m='1499600'>class.</span> <span m='1502960'>This</span>
  <span m='1503280'>variable,</span> <span m='1503610'>x,</span> <span m='1504040'>and</span>
  <span m='1504170'>this</span> <span m='1504300'>variable,</span> <span m='1504630'>y,</span>
  <span m='1505080'>are</span> <span m='1505240'>bound,</span> <span m='1506780'>because</span>
  <span m='1508300'>the</span> <span m='1508590'>meaning</span> <span m='1508950'>of</span>
  <span m='1509030'>this</span> <span m='1509210'>expression</span> <span m='1510050'>does</span>
  <span m='1510250'>not</span> <span m='1510540'>depend</span> <span m='1510920'>upon</span>
  <span m='1512750'>the</span> <span m='1512980'>particular</span> <span m='1513500'>letters</span>
  <span m='1513910'>I</span> <span m='1514020'>used</span> <span m='1514390'>to</span>
  <span m='1514490'>describe</span> <span m='1514930'>x</span> <span m='1515130'>and</span>
  <span m='1515220'>y.</span> <span m='1516640'>If</span> <span m='1516830'>I</span>
  <span m='1516920'>were</span> <span m='1517030'>to</span> <span m='1517110'>change</span>
  <span m='1518010'>the</span> <span m='1518180'>w</span> <span m='1518710'>for</span>
  <span m='1518890'>x,</span> <span m='1519710'>then</span> <span m='1520190'>said</span>
  <span m='1520510'>for</span> <span m='1520720'>every</span> <span m='1521000'>w</span>
  <span m='1521520'>there</span> <span m='1521740'>exists</span> <span m='1522090'>a</span>
  <span m='1522140'>y</span> <span m='1523250'>such</span> <span m='1523690'>that</span>
  <span m='1524000'>p</span> <span m='1524140'>is</span> <span m='1524260'>true</span>
  <span m='1524430'>of</span> <span m='1524590'>w</span> <span m='1524990'>and</span>
  <span m='1525120'>y,</span> <span m='1526090'>it</span> <span m='1526170'>would</span>
  <span m='1526260'>be</span> <span m='1526360'>the</span> <span m='1526420'>same</span>
  <span m='1526680'>sentence.</span> <span m='1529540'>That's</span> <span m='1529740'>what</span>
  <span m='1529850'>it</span> <span m='1529910'>means.</span> </p><p><span m='1530390'>Or</span>
  <span m='1530680'>another</span> <span m='1530950'>case</span> <span m='1531250'>of</span>
  <span m='1531350'>this</span> <span m='1532300'>that</span> <span m='1532580'>you've</span>
  <span m='1532730'>seen</span> <span m='1533670'>is</span> <span m='1534360'>integral</span>
  <span m='1535420'>say,</span> <span m='1535690'>from</span> <span m='1536760'>0</span>
  <span m='1537150'>to</span> <span m='1537360'>one</span> <span m='1537800'>of</span>
  <span m='1538210'>dx</span> <span m='1540600'>over</span> <span m='1541110'>one</span>
  <span m='1541440'>plus</span> <span m='1541840'>x</span> <span m='1542100'>square.</span>
  <span m='1546080'>Well</span> <span m='1546370'>that's something</span> <span m='1546630'>you</span>
  <span m='1546730'>see</span> <span m='1546900'>all</span> <span m='1547020'>the</span>
  <span m='1547130'>time.</span> <span m='1547440'>And</span> <span m='1548040'>this</span>
  <span m='1549465'>x</span> <span m='1549870'>is</span> <span m='1549990'>a</span>
  <span m='1550060'>bound</span> <span m='1550420'>variable.</span> <span m='1552270'>If</span>
  <span m='1552420'>I</span> <span m='1552520'>change</span> <span m='1552820'>that</span>
  <span m='1553080'>to a</span> <span m='1553280'>t,</span> <span m='1554350'>the</span>
  <span m='1554490'>expression</span> <span m='1555070'>is</span> <span m='1555190'>still</span>
  <span m='1555430'>the</span> <span m='1555530'>same</span> <span m='1555810'>thing.</span>
  <span m='1558170'>This</span> <span m='1558330'>is</span> <span m='1558980'>a</span>
  <span m='1559080'>1/4</span> <span m='1559470'>of</span> <span m='1559570'>the</span>
  <span m='1560100'>arctan</span> <span m='1560600'>of</span> <span m='1560690'>one</span>
  <span m='1560880'>or</span> <span m='1561950'>something</span> <span m='1562240'>like</span>
  <span m='1562450'>that.</span> <span m='1564850'>Yes,</span> <span m='1565020'>that's</span>
  <span m='1565210'>the</span> <span m='1565370'>arctan</span> <span m='1565590'>of</span>
  <span m='1565790'>one.</span> <span m='1566620'>So</span> <span m='1566820'>bound</span>
  <span m='1567160'>variables</span> <span m='1567600'>are</span> <span m='1567660'>actually</span>
  <span m='1567920'>fairly</span> <span m='1568210'>common,</span> <span m='1569210'>for</span>
  <span m='1569380'>those</span> <span m='1569590'>of</span> <span m='1569670'>you
  who have</span> <span m='1569980'>played</span> <span m='1570210'>a</span> <span
  m='1570260'>bit</span> <span m='1570680'>with</span> <span m='1571700'>mathematics.</span>
  </p><p><span m='1573690'>Well,</span> <span m='1573840'>let's go</span> <span m='1574010'>into</span>
  <span m='1574200'>the</span> <span m='1576570'>programming</span> <span m='1577100'>world.</span>
  <span m='1579100'>Instead</span> <span m='1579390'>of</span> <span m='1579470'>the</span>
  <span m='1579560'>quantifier</span> <span m='1580300'>being</span> <span m='1580590'>something</span>
  <span m='1581010'>like,</span> <span m='1581650'>for</span> <span m='1582220'>every,
  or</span> <span m='1582640'>there</span> <span m='1582820'>exists,</span> <span
  m='1583370'>or</span> <span m='1583550'>integral,</span> <span m='1584000'>a</span>
  <span m='1584290'>quantifier</span> <span m='1584860'>is</span> <span m='1584950'>a</span>
  <span m='1585000'>symbol</span> <span m='1585360'>that</span> <span m='1585490'>binds</span>
  <span m='1585850'>a</span> <span m='1585900'>variable.</span> <span m='1587570'>And</span>
  <span m='1587940'>we</span> <span m='1588130'>are going</span> <span m='1588280'>to</span>
  <span m='1588360'>use the quantifier</span> <span m='1588510'>lambda</span> <span
  m='1589840'>as</span> <span m='1589990'>being</span> <span m='1590190'>the</span>
  <span m='1590280'>essential</span> <span m='1590670'>thing</span> <span m='1590840'>that</span>
  <span m='1591000'>binds</span> <span m='1591320'>variables.</span> </p><p><span
  m='1593970'>And</span> <span m='1594140'>so</span> <span m='1594310'>we</span> <span
  m='1594440'>have</span> <span m='1594850'>some</span> <span m='1595060'>nice</span>
  <span m='1595300'>examples</span> <span m='1595850'>here</span> <span m='1596710'>like</span>
  <span m='1597330'>that</span> <span m='1597730'>procedure</span> <span m='1599010'>of</span>
  <span m='1599230'>one</span> <span m='1599450'>argument</span> <span m='1600010'>y</span>
  <span m='1602710'>which</span> <span m='1602930'>does</span> <span m='1603160'>the</span>
  <span m='1603240'>following</span> <span m='1603610'>thing.</span> <span m='1604370'>It</span>
  <span m='1604540'>calls</span> <span m='1604900'>the</span> <span m='1604990'>procedure</span>
  <span m='1605740'>of</span> <span m='1605930'>one</span> <span m='1606120'>argument</span>
  <span m='1606560'>x,</span> <span m='1607800'>which</span> <span m='1608380'>multiplies</span>
  <span m='1610000'>x</span> <span m='1610300'>by</span> <span m='1610540'>y,</span>
  <span m='1612700'>and</span> <span m='1613060'>applies</span> <span m='1613490'>that</span>
  <span m='1613750'>to</span> <span m='1613870'>three.</span> <span m='1618810'>That</span>
  <span m='1619080'>procedure</span> <span m='1619470'>has</span> <span m='1619620'>the</span>
  <span m='1619710'>property</span> <span m='1620100'>there of</span> <span m='1620350'>two</span>
  <span m='1620540'>bound</span> <span m='1620860'>variables</span> <span m='1621370'>in</span>
  <span m='1621510'>it,</span> <span m='1622120'>x</span> <span m='1622360'>and</span>
  <span m='1622500'>y.</span> <span m='1624790'>This</span> <span m='1625030'>quantifier,</span>
  <span m='1625730'>lambda</span> <span m='1626140'>here,</span> <span m='1626390'>binds</span>
  <span m='1626850'>this</span> <span m='1627060'>y,</span> <span m='1627825'>and</span>
  <span m='1628160'>this</span> <span m='1628500'>quantifier,</span> <span m='1629490'>lambda,</span>
  <span m='1629880'>binds</span> <span m='1630210'>that</span> <span m='1630470'>x.</span>
  <span m='1632120'>Because,</span> <span m='1633010'>if</span> <span m='1633260'>I</span>
  <span m='1633370'>were</span> <span m='1633480'>to</span> <span m='1633560'>take</span>
  <span m='1633760'>an</span> <span m='1633840'>arbitrary</span> <span m='1634300'>symbol</span>
  <span m='1634650'>does</span> <span m='1634810'>not</span> <span m='1635000'>occur</span>
  <span m='1635560'>in</span> <span m='1635700'>this</span> <span m='1635830'>expression</span>
  <span m='1636360'>like</span> <span m='1636550'>w</span> <span m='1637970'>and</span>
  <span m='1638150'>replace</span> <span m='1638890'>all</span> <span m='1639150'>y's</span>
  <span m='1639600'>with</span> <span m='1639750'>w's</span> <span m='1640130'>in
  this</span> <span m='1640390'>expression,</span> <span m='1640980'>the</span> <span
  m='1641540'>expression</span> <span m='1641980'>is</span> <span m='1642070'>still</span>
  <span m='1642230'>the</span> <span m='1642310'>same,</span> <span m='1643610'>the</span>
  <span m='1643900'>same</span> <span m='1644170'>procedure.</span> </p><p><span m='1646240'>And</span>
  <span m='1646400'>this</span> <span m='1646490'>is</span> <span m='1646540'>an</span>
  <span m='1646610'>important</span> <span m='1647010'>idea.</span> <span m='1647430'>The</span>
  <span m='1647530'>reason</span> <span m='1647760'>why</span> <span m='1647910'>we</span>
  <span m='1648090'>had</span> <span m='1648260'>such</span> <span m='1648490'>things</span>
  <span m='1648730'>like</span> <span m='1648970'>that</span> <span m='1650270'>is</span>
  <span m='1650390'>a</span> <span m='1650430'>kind</span> <span m='1650570'>of</span>
  <span m='1650700'>modularity.</span> <span m='1651500'>If</span> <span m='1651620'>two</span>
  <span m='1651740'>people</span> <span m='1651980'>are</span> <span m='1652030'>writing</span>
  <span m='1652300'>programs,</span> <span m='1654450'>and</span> <span m='1654550'>they</span>
  <span m='1654630'>work</span> <span m='1654800'>together,</span> <span m='1655340'>it</span>
  <span m='1655450'>shouldn't</span> <span m='1655640'>matter</span> <span m='1655840'>what</span>
  <span m='1655990'>names</span> <span m='1656240'>they</span> <span m='1656350'>use</span>
  <span m='1657720'>internal</span> <span m='1658150'>to</span> <span m='1658250'>their</span>
  <span m='1658420'>own</span> <span m='1658530'>little</span> <span m='1659450'>machines</span>
  <span m='1659960'>that they're</span> <span m='1660190'>building.</span> <span m='1662490'>And</span>
  <span m='1662850'>so,</span> <span m='1663200'>what</span> <span m='1663610'>I'm</span>
  <span m='1663720'>really</span> <span m='1663920'>telling</span> <span m='1664220'>you</span>
  <span m='1664350'>there,</span> <span m='1665550'>is</span> <span m='1665740'>that,</span>
  <span m='1665960'>for</span> <span m='1666140'>example,</span> <span m='1666850'>this</span>
  <span m='1667080'>is</span> <span m='1667170'>equivalent</span> <span m='1667740'>to</span>
  <span m='1668650'>that</span> <span m='1669000'>procedure</span> <span m='1669490'>of</span>
  <span m='1669640'>one</span> <span m='1669800'>argument</span> <span m='1670190'>y</span>
  <span m='1671010'>which</span> <span m='1672540'>uses</span> <span m='1673030'>that</span>
  <span m='1673260'>procedure</span> <span m='1673600'>of</span> <span m='1673710'>one</span>
  <span m='1673830'>argument</span> <span m='1674260'>d</span> <span m='1675210'>which</span>
  <span m='1675470'>multiplies</span> <span m='1678070'>z</span> <span m='1678330'>by</span>
  <span m='1678590'>y.</span> <span m='1681200'>Because</span> <span m='1681990'>nobody</span>
  <span m='1682300'>cares</span> <span m='1682690'>what I</span> <span m='1682910'>used
  in</span> <span m='1683290'>here.</span> <span m='1686270'>It's</span> <span m='1686450'>a</span>
  <span m='1686480'>nice</span> <span m='1686700'>example.</span> </p><p><span m='1688880'>On</span>
  <span m='1689090'>the</span> <span m='1689240'>other</span> <span m='1689390'>hand,</span>
  <span m='1691120'>I</span> <span m='1691270'>have</span> <span m='1691420'>some</span>
  <span m='1693070'>variables</span> <span m='1693470'>that</span> <span m='1693560'>are</span>
  <span m='1693650'>not</span> <span m='1693910'>bound.</span> <span m='1695320'>For</span>
  <span m='1695440'>example,</span> <span m='1700080'>that</span> <span m='1700570'>procedure</span>
  <span m='1700880'>of</span> <span m='1700990'>one</span> <span m='1701110'>argument</span>
  <span m='1701460'>x</span> <span m='1702220'>which</span> <span m='1702450'>multiplies</span>
  <span m='1704060'>x</span> <span m='1704330'>by</span> <span m='1704600'>y.</span>
  <span m='1707390'>In</span> <span m='1707560'>this</span> <span m='1707800'>case,</span>
  <span m='1709540'>y</span> <span m='1709920'>is</span> <span m='1710110'>not</span>
  <span m='1710400'>bound.</span> <span m='1712370'>Supposing</span> <span m='1712880'>y</span>
  <span m='1713090'>had</span> <span m='1713270'>the</span> <span m='1713350'>value</span>
  <span m='1713670'>three,</span> <span m='1715400'>and</span> <span m='1715710'>z
  had the</span> <span m='1716140'>value</span> <span m='1716440'>four,</span> <span
  m='1718860'>then</span> <span m='1719360'>this</span> <span m='1719670'>procedure</span>
  <span m='1720150'>would</span> <span m='1720300'>be</span> <span m='1720410'>the</span>
  <span m='1720500'>thing</span> <span m='1721180'>that</span> <span m='1721420'>multiplies</span>
  <span m='1722570'>its</span> <span m='1722770'>argument</span> <span m='1723660'>by</span>
  <span m='1723850'>three.</span> <span m='1724910'>If</span> <span m='1725130'>I</span>
  <span m='1725210'>were</span> <span m='1725330'>to</span> <span m='1725380'>replace</span>
  <span m='1725820'>every</span> <span m='1726070'>instance</span> <span m='1726360'>of</span>
  <span m='1726480'>y</span> <span m='1726730'>with</span> <span m='1727010'>z,</span>
  <span m='1727320'>I</span> <span m='1727730'>would have a</span> <span m='1727920'>different</span>
  <span m='1728200'>procedure</span> <span m='1728490'>which</span> <span m='1728630'>multiplies</span>
  <span m='1729660'>every</span> <span m='1730190'>argument</span> <span m='1730530'>that's</span>
  <span m='1730640'>given</span> <span m='1731430'>by</span> <span m='1731590'>four.</span>
  </p><p><span m='1733491'>And,</span> <span m='1733980'>in</span> <span m='1734340'>fact,</span>
  <span m='1734830'>we</span> <span m='1734960'>have</span> <span m='1735090'>a</span>
  <span m='1735140'>name</span> <span m='1735410'>for</span> <span m='1735530'>such</span>
  <span m='1735740'>a</span> <span m='1735790'>variable.</span> <span m='1737810'>Here,</span>
  <span m='1738390'>we</span> <span m='1738580'>say</span> <span m='1738810'>that</span>
  <span m='1738960'>a</span> <span m='1739010'>variable,</span> <span m='1739500'>v,</span>
  <span m='1739850'>is</span> <span m='1740140'>free</span> <span m='1742950'>in</span>
  <span m='1743080'>the</span> <span m='1743200'>expression,</span> <span m='1743680'>e,</span>
  <span m='1744080'>if</span> <span m='1744240'>the</span> <span m='1744350'>meaning</span>
  <span m='1744670'>of</span> <span m='1744730'>the</span> <span m='1744800'>expression,</span>
  <span m='1745055'>e,</span> <span m='1745310'>is</span> <span m='1745570'>changed</span>
  <span m='1746070'>by</span> <span m='1746200'>the</span> <span m='1746290'>uniform</span>
  <span m='1746670'>replacement</span> <span m='1747470'>of</span> <span m='1747650'>a</span>
  <span m='1747700'>variable,</span> <span m='1748170'>w,</span> <span m='1748520'>not</span>
  <span m='1748720'>occurring</span> <span m='1749120'>in e</span> <span m='1749590'>for</span>
  <span m='1749830'>every</span> <span m='1750040'>occurrence</span> <span m='1750470'>of</span>
  <span m='1750590'>v</span> <span m='1750790'>and</span> <span m='1750980'>e.</span>
  </p><p><span m='1753120'>So</span> <span m='1757920'>that's</span> <span m='1758310'>why</span>
  <span m='1758960'>this</span> <span m='1759660'>variable</span> <span m='1760010'>over</span>
  <span m='1760150'>here,</span> <span m='1760680'>y,</span> <span m='1761590'>is</span>
  <span m='1761770'>a</span> <span m='1761910'>free</span> <span m='1762260'>variable.</span>
  <span m='1769010'>And</span> <span m='1769380'>so</span> <span m='1769790'>free</span>
  <span m='1770170'>variables</span> <span m='1771100'>in</span> <span m='1771370'>this</span>
  <span m='1771630'>expression--</span> <span m='1773610'>And</span> <span m='1774020'>other</span>
  <span m='1774290'>examples</span> <span m='1774770'>of</span> <span m='1775060'>that</span>
  <span m='1776220'>is</span> <span m='1776420'>that</span> <span m='1776620'>procedure</span>
  <span m='1777730'>of</span> <span m='1778030'>one</span> <span m='1778300'>argument</span>
  <span m='1778690'>y,</span> <span m='1780530'>which</span> <span m='1780720'>is</span>
  <span m='1780910'>just</span> <span m='1781100'>what we</span> <span m='1781260'>had</span>
  <span m='1781440'>before,</span> <span m='1782360'>which</span> <span m='1782550'>uses</span>
  <span m='1782950'>that</span> <span m='1783160'>procedure</span> <span m='1783580'>of</span>
  <span m='1783700'>one</span> <span m='1783820'>argument</span> <span m='1784200'>x</span>
  <span m='1785180'>that</span> <span m='1785710'>multiplies</span> <span m='1787280'>x</span>
  <span m='1787610'>by</span> <span m='1787860'>y--</span> <span m='1791540'>use</span>
  <span m='1791730'>that</span> <span m='1791970'>on</span> <span m='1792160'>three.</span>
  <span m='1796940'>This</span> <span m='1798320'>procedure</span> <span m='1799080'>has</span>
  <span m='1799290'>a</span> <span m='1799360'>free</span> <span m='1799570'>variable</span>
  <span m='1800060'>in</span> <span m='1800170'>it</span> <span m='1801090'>which</span>
  <span m='1801300'>is</span> <span m='1801450'>asterisk.</span> <span m='1805010'>See,</span>
  <span m='1805310'>because,</span> <span m='1806020'>if</span> <span m='1806170'>that</span>
  <span m='1806350'>has</span> <span m='1806520'>a</span> <span m='1806570'>normal</span>
  <span m='1806820'>meaning</span> <span m='1807080'>of</span> <span m='1807170'>multiplication,</span>
  <span m='1809135'>then</span> <span m='1809520'>if</span> <span m='1809750'>I were
  to</span> <span m='1809820'>replace</span> <span m='1810460'>uniformly</span> <span
  m='1811120'>all</span> <span m='1811360'>asterisks</span> <span m='1811940'>with</span>
  <span m='1812110'>pluses,</span> <span m='1814200'>then</span> <span m='1814510'>the</span>
  <span m='1814610'>meaning</span> <span m='1814970'>of</span> <span m='1815120'>this</span>
  <span m='1815270'>expression</span> <span m='1815770'>would</span> <span m='1815920'>change.</span>
  <span m='1819360'>That's</span> <span m='1819530'>what</span> <span m='1819620'>you</span>
  <span m='1819700'>mean</span> <span m='1819890'>by</span> <span m='1820000'>a</span>
  <span m='1820070'>free</span> <span m='1820270'>variable.</span> </p><p><span m='1822850'>So,
  so</span> <span m='1823070'>far</span> <span m='1823300'>you've</span> <span m='1823490'>learned</span>
  <span m='1823780'>some</span> <span m='1823970'>logician</span> <span m='1824470'>words</span>
  <span m='1825670'>which</span> <span m='1825870'>describe</span> <span m='1826350'>the</span>
  <span m='1826430'>way</span> <span m='1826660'>names</span> <span m='1827020'>are</span>
  <span m='1827120'>used.</span> <span m='1829020'>Now,</span> <span m='1829200'>we</span>
  <span m='1829440'>have</span> <span m='1829570'>to</span> <span m='1829610'>do a
  little</span> <span m='1829840'>bit</span> <span m='1830000'>more</span> <span m='1830220'>playing</span>
  <span m='1830560'>around</span> <span m='1830890'>here,</span> <span m='1832490'>a</span>
  <span m='1833040'>little</span> <span m='1833250'>bit</span> <span m='1833430'>more.</span>
  <span m='1835200'>I</span> <span m='1835300'>want</span> <span m='1835410'>to</span>
  <span m='1835520'>tell</span> <span m='1835700'>you</span> <span m='1836890'>about</span>
  <span m='1837410'>the</span> <span m='1837660'>regions</span> <span m='1838160'>are</span>
  <span m='1838310'>over which</span> <span m='1838600'>variables</span> <span m='1839010'>are</span>
  <span m='1839050'>defined.</span> </p><p><span m='1842270'>You</span> <span m='1842410'>see,</span>
  <span m='1843520'>we've</span> <span m='1843710'>been</span> <span m='1843870'>very</span>
  <span m='1844130'>informal</span> <span m='1844530'>about</span> <span m='1844800'>this</span>
  <span m='1844970'>up</span> <span m='1845100'>till</span> <span m='1845260'>now,</span>
  <span m='1846360'>and,</span> <span m='1846490'>of</span> <span m='1846680'>course,</span>
  <span m='1846880'>many</span> <span m='1847130'>of</span> <span m='1847190'>you</span>
  <span m='1847450'>have</span> <span m='1847730'>probably</span> <span m='1848350'>understood</span>
  <span m='1848870'>very</span> <span m='1849070'>clearly</span> <span m='1849440'>or</span>
  <span m='1849480'>most</span> <span m='1849760'>of</span> <span m='1849830'>you,</span>
  <span m='1850450'>that</span> <span m='1850670'>the</span> <span m='1850840'>x</span>
  <span m='1851320'>that's</span> <span m='1851530'>being</span> <span m='1851960'>declared</span>
  <span m='1852490'>here</span> <span m='1853700'>is</span> <span m='1853860'>defined</span>
  <span m='1854310'>only</span> <span m='1854660'>in</span> <span m='1854830'>here.</span>
  <span m='1858250'>This</span> <span m='1858650'>x</span> <span m='1859620'>is</span>
  <span m='1859770'>the</span> <span m='1859860'>defined</span> <span m='1860140'>only</span>
  <span m='1860410'>in</span> <span m='1860530'>here,</span> <span m='1861620'>and</span>
  <span m='1861870'>this</span> <span m='1862060'>y</span> <span m='1863000'>is</span>
  <span m='1863220'>defined</span> <span m='1863580'>only</span> <span m='1863920'>in</span>
  <span m='1864030'>here.</span> <span m='1867080'>We</span> <span m='1867340'>have</span>
  <span m='1867430'>a</span> <span m='1867450'>name</span> <span m='1867750'>for</span>
  <span m='1867870'>such</span> <span m='1868060'>an</span> <span m='1868150'>idea.</span>
  <span m='1868400'>It's</span> <span m='1868530'>called a</span> <span m='1868770'>scope.</span>
  </p><p><span m='1871660'>And</span> <span m='1871800'>let me</span> <span m='1871920'>give
  you</span> <span m='1872250'>another</span> <span m='1872570'>piece</span> <span
  m='1872780'>of</span> <span m='1872870'>terminology.</span> <span m='1874710'>It's</span>
  <span m='1874850'>a</span> <span m='1874920'>long</span> <span m='1875220'>story.</span>
  <span m='1876050'>If</span> <span m='1876230'>x</span> <span m='1876440'>is</span>
  <span m='1876510'>a</span> <span m='1876580'>bound</span> <span m='1876940'>variable</span>
  <span m='1877110'>in</span> <span m='1877590'>e,</span> <span m='1878110'>then</span>
  <span m='1878440'>there is</span> <span m='1878510'>a</span> <span m='1878550'>lambda</span>
  <span m='1878850'>expression</span> <span m='1879340'>where</span> <span m='1879530'>it</span>
  <span m='1879620'>is</span> <span m='1879720'>bound.</span> <span m='1880560'>So</span>
  <span m='1880890'>the</span> <span m='1881190'>only</span> <span m='1881460'>way</span>
  <span m='1881600'>you</span> <span m='1881710'>can</span> <span m='1881820'>get</span>
  <span m='1881920'>a</span> <span m='1882030'>bound</span> <span m='1882470'>variable</span>
  <span m='1883300'>ultimately</span> <span m='1883800'>is by  lambda</span> <span
  m='1884270'>expression.</span> <span m='1884970'>Then you</span> <span m='1885230'>may</span>
  <span m='1885400'>worry,</span> <span m='1886450'>does</span> <span m='1886640'>define</span>
  <span m='1887090'>quite</span> <span m='1888120'>an</span> <span m='1888250'>exception</span>
  <span m='1888700'>to</span> <span m='1888780'>this?</span> <span m='1889670'>And</span>
  <span m='1889930'>it</span> <span m='1890030'>turns</span> <span m='1890300'>out,</span>
  <span m='1890460'>we</span> <span m='1890560'>could</span> <span m='1890680'>always</span>
  <span m='1890940'>arrange</span> <span m='1891330'>things</span> <span m='1891650'>so</span>
  <span m='1891750'>you</span> <span m='1891840'>don't</span> <span m='1891990'>need</span>
  <span m='1892130'>any</span> <span m='1892290'>defines.</span> <span m='1893100'>And</span>
  <span m='1893170'>we'll</span> <span m='1893250'>see</span> <span m='1893400'>that</span>
  <span m='1893570'>in</span> <span m='1893610'>a</span> <span m='1893660'>while.</span>
  <span m='1894070'>It's</span> <span m='1894520'>a</span> <span m='1894690'>very</span>
  <span m='1894950'>magical</span> <span m='1895370'>thing.</span> <span m='1896900'>So</span>
  <span m='1897120'>define</span> <span m='1897520'>really</span> <span m='1897730'>can</span>
  <span m='1897860'>go</span> <span m='1898000'>away.</span> <span m='1899000'>The</span>
  <span m='1899100'>really,</span> <span m='1899430'>only</span> <span m='1899650'>thing</span>
  <span m='1899790'>that</span> <span m='1899950'>makes</span> <span m='1900260'>names</span>
  <span m='1900910'>is</span> <span m='1901060'>lambda .</span> <span m='1902650'>That's</span>
  <span m='1902850'>its</span> <span m='1903020'>job.</span> <span m='1904350'>And</span>
  <span m='1904480'>what's</span> <span m='1904680'>so</span> <span m='1904850'>amazing</span>
  <span m='1905300'>about</span> <span m='1905490'>a</span> <span m='1905590'>lot</span>
  <span m='1905680'>of</span> <span m='1905780'>things</span> <span m='1906380'>is</span>
  <span m='1906510'>you</span> <span m='1906640'>can compute</span> <span m='1907090'>with</span>
  <span m='1907220'>only</span> <span m='1907440'>lambda.</span> </p><p><span m='1908740'>But,</span>
  <span m='1908970'>in</span> <span m='1909060'>any</span> <span m='1909250'>case,</span>
  <span m='1911414'>a</span> <span m='1911840'>lambda</span> <span m='1912220'>expression</span>
  <span m='1912680'>has</span> <span m='1913390'>a</span> <span m='1913540'>place</span>
  <span m='1913830'>where it</span> <span m='1913990'>declares</span> <span m='1915300'>a</span>
  <span m='1915390'>variable.</span> <span m='1915880'>We</span> <span m='1916150'>call
  it</span> <span m='1916210'>the</span> <span m='1916510'>formal parameter</span>
  <span m='1916900'>list</span> <span m='1918980'>or</span> <span m='1919310'>the</span>
  <span m='1919700'>bound</span> <span m='1919970'>variable</span> <span m='1920340'>list.</span>
  <span m='1921410'>We</span> <span m='1921590'>say</span> <span m='1921850'>that
  the</span> <span m='1921930'>lambda</span> <span m='1922180'>expression</span> <span
  m='1922760'>binds--</span> <span m='1923290'>so</span> <span m='1923620'>it's</span>
  <span m='1923920'>a</span> <span m='1924380'>verb--</span> <span m='1924970'>binds</span>
  <span m='1925500'>the</span> <span m='1925600'>variables</span> <span m='1925970'>declared
  in</span> <span m='1926380'>it's</span> <span m='1926530'>found</span> <span m='1926750'>variable</span>
  <span m='1927100'>list.</span> <span m='1928730'>In</span> <span m='1928830'>addition,</span>
  <span m='1929200'>those</span> <span m='1929410'>parts</span> <span m='1929650'>of</span>
  <span m='1929710'>the</span> <span m='1929770'>expression</span> <span m='1930310'>where</span>
  <span m='1930450'>the</span> <span m='1930580'>variable</span> <span m='1931180'>is</span>
  <span m='1931520'>defined,</span> <span m='1933350'>which</span> <span m='1933490'>was</span>
  <span m='1933600'>declared</span> <span m='1934030'>by</span> <span m='1934170'>some</span>
  <span m='1934420'>declaration,</span> <span m='1935680'>is</span> <span m='1935830'>called</span>
  <span m='1936040'>the</span> <span m='1936070'>scope</span> <span m='1938050'>of</span>
  <span m='1938610'>that</span> <span m='1938830'>variable.</span> <span m='1940400'>So</span>
  <span m='1940840'>these</span> <span m='1941250'>are</span> <span m='1941460'>scopes.</span>
  <span m='1942270'>This</span> <span m='1942490'>is</span> <span m='1942610'>the</span>
  <span m='1942710'>scope</span> <span m='1943110'>of</span> <span m='1943220'>y.</span>
  <span m='1947140'>And</span> <span m='1947450'>this</span> <span m='1947600'>is</span>
  <span m='1947670'>the</span> <span m='1947770'>scope</span> <span m='1948160'>of</span>
  <span m='1948280'>x--</span> <span m='1953030'>that</span> <span m='1953430'>sort</span>
  <span m='1953600'>of</span> <span m='1953690'>thing.</span> </p><p><span m='1961460'>OK,</span>
  <span m='1964060'>well,</span> <span m='1964230'>now</span> <span m='1964390'>we</span>
  <span m='1964490'>have</span> <span m='1964590'>enough</span> <span m='1964800'>terminology</span>
  <span m='1966360'>to</span> <span m='1966810'>begin</span> <span m='1967070'>to</span>
  <span m='1967120'>understand</span> <span m='1968230'>how</span> <span m='1968480'>to</span>
  <span m='1969930'>make</span> <span m='1970100'>a</span> <span m='1970150'>new</span>
  <span m='1970280'>model</span> <span m='1970740'>for</span> <span m='1970930'>computation,</span>
  <span m='1971970'>because</span> <span m='1972360'>the</span> <span m='1972460'>key</span>
  <span m='1972740'>thing</span> <span m='1972960'>going</span> <span m='1973220'>on</span>
  <span m='1973420'>here</span> <span m='1975040'>is</span> <span m='1975250'>that</span>
  <span m='1975410'>we</span> <span m='1975540'>destroyed</span> <span m='1975970'>the</span>
  <span m='1976060'>substitution</span> <span m='1976630'>model,</span> <span m='1977020'>and</span>
  <span m='1977270'>we</span> <span m='1977450'>now</span> <span m='1977670'>have</span>
  <span m='1977780'>to</span> <span m='1977880'>have</span> <span m='1977950'>a</span>
  <span m='1978020'>model</span> <span m='1978540'>that</span> <span m='1978820'>represents</span>
  <span m='1980330'>the</span> <span m='1980550'>names</span> <span m='1980920'>as</span>
  <span m='1981200'>referring</span> <span m='1981630'>to</span> <span m='1981730'>places.</span>
  <span m='1983950'>Because</span> <span m='1984040'>if we</span> <span m='1984150'>are
  going to</span> <span m='1984430'>change</span> <span m='1984790'>something,</span>
  <span m='1985675'>then</span> <span m='1986080'>we</span> <span m='1986230'>have</span>
  <span m='1986460'>a</span> <span m='1986520'>place</span> <span m='1986820'>where</span>
  <span m='1986960'>it's</span> <span m='1987080'>stored.</span> </p><p><span m='1989660'>You</span>
  <span m='1989790'>see,</span> <span m='1990860'>if</span> <span m='1991320'>a</span>
  <span m='1991410'>name</span> <span m='1991760'>only</span> <span m='1992020'>refers</span>
  <span m='1992490'>to</span> <span m='1992650'>a</span> <span m='1992700'>value,</span>
  <span m='1994080'>and</span> <span m='1994200'>if</span> <span m='1994310'>I</span>
  <span m='1994410'>tried</span> <span m='1994760'>to</span> <span m='1994860'>change</span>
  <span m='1995270'>the</span> <span m='1995390'>name's</span> <span m='1995850'>meaning,</span>
  <span m='1996810'>well,</span> <span m='1998450'>that's</span> <span m='1998870'>not</span>
  <span m='1999050'>clear.</span> <span m='1999280'>There's</span> <span m='1999460'>nothing</span>
  <span m='2001040'>that</span> <span m='2001680'>is</span> <span m='2001960'>the</span>
  <span m='2002770'>place</span> <span m='2003190'>that</span> <span m='2003360'>that</span>
  <span m='2003570'>name</span> <span m='2003790'>referred</span> <span m='2004190'>to.</span>
  <span m='2005030'>How am</span> <span m='2005260'>I</span> <span m='2005340'>really</span>
  <span m='2005550'>saying</span> <span m='2005700'>it?</span> <span m='2005960'>There</span>
  <span m='2006080'>is</span> <span m='2006190'>nothing</span> <span m='2006300'>shared</span>
  <span m='2007460'>among</span> <span m='2007820'>all</span> <span m='2008040'>of</span>
  <span m='2008130'>the</span> <span m='2008220'>instances</span> <span m='2008710'>of</span>
  <span m='2008800'>that</span> <span m='2009030'>name.</span> <span m='2009840'>And</span>
  <span m='2010020'>what</span> <span m='2010090'>we</span> <span m='2010260'>really</span>
  <span m='2010500'>mean,</span> <span m='2011050'>by a</span> <span m='2011190'>name,</span>
  <span m='2011800'>is that</span> <span m='2011940'>we</span> <span m='2012080'>fan</span>
  <span m='2012420'>something</span> <span m='2012780'>out.</span> <span m='2014440'>We've</span>
  <span m='2014620'>given</span> <span m='2014870'>something</span> <span m='2015180'>a</span>
  <span m='2015220'>name,</span> <span m='2015700'>and</span> <span m='2015890'>you</span>
  <span m='2016040'>have</span> <span m='2016300'>it,</span> <span m='2016790'>and</span>
  <span m='2016950'>you</span> <span m='2017140'>have</span> <span m='2017350'>it,</span>
  <span m='2017600'>because</span> <span m='2017790'>I'm</span> <span m='2017930'>given</span>
  <span m='2018140'>you</span> <span m='2018270'>a</span> <span m='2018340'>reference</span>
  <span m='2018760'>to</span> <span m='2018920'>it,</span> <span m='2019160'>and</span>
  <span m='2019370'>I've</span> <span m='2019470'>given</span> <span m='2019550'>you
  a</span> <span m='2019810'>reference</span> <span m='2020160'>to</span> <span m='2020320'>it.</span>
  <span m='2021130'>And</span> <span m='2021380'>we'll see</span> <span m='2021550'>a</span>
  <span m='2021610'>lot</span> <span m='2021800'>about</span> <span m='2022060'>that.</span>
  </p><p><span m='2023580'>So</span> <span m='2023750'>let</span> <span m='2023880'>me</span>
  <span m='2024000'>tell</span> <span m='2024150'>you</span> <span m='2024280'>about</span>
  <span m='2024520'>environments.</span> <span m='2025986'>I</span> <span m='2026340'>need
  the</span> <span m='2026700'>overhead</span> <span m='2027300'>projection</span>
  <span m='2028150'>machine,</span> <span m='2029400'>thank</span> <span m='2029700'>you.</span>
  <span m='2032140'>And</span> <span m='2032380'>so</span> <span m='2032610'>here</span>
  <span m='2035610'>is</span> <span m='2035830'>a</span> <span m='2038890'>bunch of</span>
  <span m='2039190'>environment</span> <span m='2039780'>structures.</span> <span
  m='2041590'>An</span> <span m='2041740'>environment</span> <span m='2043620'>is</span>
  <span m='2043770'>a</span> <span m='2043830'>way</span> <span m='2044030'>of</span>
  <span m='2044130'>doing</span> <span m='2044370'>substitutions</span> <span m='2045060'>virtually.</span>
  <span m='2046490'>It</span> <span m='2046850'>represents</span> <span m='2047240'>a</span>
  <span m='2047310'>place</span> <span m='2048020'>where</span> <span m='2048219'>something</span>
  <span m='2048620'>is</span> <span m='2048719'>stored</span> <span m='2049350'>which</span>
  <span m='2049560'>is</span> <span m='2049639'>the</span> <span m='2049830'>substitutions</span>
  <span m='2050530'>that</span> <span m='2050719'>you</span> <span m='2050820'>haven't</span>
  <span m='2051120'>done.</span> <span m='2054540'>It's</span> <span m='2054710'>a</span>
  <span m='2054760'>place</span> <span m='2055270'>where</span> <span m='2055560'>everything</span>
  <span m='2055900'>accumulates,</span> <span m='2056639'>where</span> <span m='2056790'>the</span>
  <span m='2056929'>names</span> <span m='2057639'>of</span> <span m='2057949'>the</span>
  <span m='2058030'>variables</span> <span m='2058630'>are</span> <span m='2058889'>associated</span>
  <span m='2059940'>with</span> <span m='2060120'>the</span> <span m='2060199'>values</span>
  <span m='2060600'>they</span> <span m='2060900'>have</span> <span m='2061850'>such</span>
  <span m='2062230'>that</span> <span m='2062830'>when</span> <span m='2063020'>you</span>
  <span m='2063600'>say,</span> <span m='2064610'>what</span> <span m='2064760'>dose</span>
  <span m='2064880'>this</span> <span m='2065070'>name</span> <span m='2065310'>mean,</span>
  <span m='2066020'>you</span> <span m='2066190'>look</span> <span m='2066360'>it</span>
  <span m='2066429'>up</span> <span m='2066570'>in</span> <span m='2066719'>an</span>
  <span m='2066780'>environment.</span> </p><p><span m='2068090'>So</span> <span m='2068239'>an</span>
  <span m='2068389'>environment</span> <span m='2068830'>is</span> <span m='2069000'>a</span>
  <span m='2069050'>function,</span> <span m='2070830'>or a</span> <span m='2071050'>table,</span>
  <span m='2072290'>or</span> <span m='2072420'>something</span> <span m='2072739'>like</span>
  <span m='2072940'>that.</span> <span m='2073290'>But</span> <span m='2073469'>it's</span>
  <span m='2073580'>a</span> <span m='2073639'>structured</span> <span m='2074179'>sort</span>
  <span m='2074340'>of</span> <span m='2074489'>table.</span> <span m='2075790'>It's</span>
  <span m='2075980'>made</span> <span m='2076199'>out of</span> <span m='2076350'>things</span>
  <span m='2076590'>called</span> <span m='2076810'>frames.</span> <span m='2081050'>Frames</span>
  <span m='2081440'>are</span> <span m='2081560'>pieces</span> <span m='2083679'>of</span>
  <span m='2083820'>environment,</span> <span m='2084870'>and</span> <span m='2085120'>they
  are</span> <span m='2085210'>chained</span> <span m='2085550'>together,</span> <span
  m='2087170'>in</span> <span m='2087290'>some</span> <span m='2087440'>nice</span>
  <span m='2087730'>ways,</span> <span m='2088909'>by</span> <span m='2089130'>what's</span>
  <span m='2089320'>called</span> <span m='2089909'>parent</span> <span m='2090270'>links</span>
  <span m='2090960'>or</span> <span m='2091199'>something</span> <span m='2091550'>like</span>
  <span m='2091790'>that.</span> </p><p><span m='2093940'>So</span> <span m='2094409'>here,</span>
  <span m='2095679'>we</span> <span m='2095870'>have</span> <span m='2096360'>an</span>
  <span m='2096489'>environment</span> <span m='2096989'>structure</span> <span m='2097740'>consisting</span>
  <span m='2098470'>of</span> <span m='2098870'>three</span> <span m='2099560'>environments,</span>
  <span m='2100100'>basically,</span> <span m='2100660'>a,</span> <span m='2101780'>b,</span>
  <span m='2103330'>and</span> <span m='2103690'>c.</span> <span m='2105250'>d</span>
  <span m='2105550'>is</span> <span m='2105700'>also an</span> <span m='2106050'>environment,</span>
  <span m='2106580'>but</span> <span m='2106680'>it's</span> <span m='2106810'>the</span>
  <span m='2106900'>same</span> <span m='2107220'>one,</span> <span m='2108730'>they</span>
  <span m='2109140'>share.</span> <span m='2111480'>And</span> <span m='2111610'>that's</span>
  <span m='2111750'>the</span> <span m='2112280'>essence</span> <span m='2112420'>of</span>
  <span m='2113320'>assignment.</span> <span m='2114550'>If</span> <span m='2114750'>I</span>
  <span m='2114870'>change</span> <span m='2115320'>a</span> <span m='2115410'>variable,</span>
  <span m='2116690'>a</span> <span m='2116810'>value</span> <span m='2117180'>of</span>
  <span m='2117260'>a</span> <span m='2117310'>valuable</span> <span m='2117680'>that</span>
  <span m='2117850'>lives</span> <span m='2118120'>here,</span> <span m='2118410'>like</span>
  <span m='2118650'>that</span> <span m='2118900'>one,</span> <span m='2119970'>it</span>
  <span m='2120130'>should</span> <span m='2120250'>be</span> <span m='2120370'>visible</span>
  <span m='2121070'>from</span> <span m='2121300'>all</span> <span m='2121560'>places</span>
  <span m='2121950'>that</span> <span m='2122050'>you're</span> <span m='2122160'>looking</span>
  <span m='2122520'>at it</span> <span m='2122760'>from.</span> <span m='2123750'>Take
  this</span> <span m='2124050'>one,</span> <span m='2124180'>x.</span> <span m='2124990'>If</span>
  <span m='2125140'>I</span> <span m='2125230'>change</span> <span m='2125510'>the</span>
  <span m='2125650'>x</span> <span m='2126470'>to</span> <span m='2127370'>four,</span>
  <span m='2128400'>it's</span> <span m='2128560'>visible</span> <span m='2128850'>from</span>
  <span m='2129010'>other</span> <span m='2129180'>places.</span> <span m='2130340'>But</span>
  <span m='2130490'>I'm not</span> <span m='2130660'>going</span> <span m='2130740'>to</span>
  <span m='2130810'>worry</span> <span m='2131050'>about</span> <span m='2131310'>that</span>
  <span m='2131520'>right</span> <span m='2131770'>now.</span> <span m='2132270'>We're</span>
  <span m='2132370'>going</span> <span m='2132410'>to</span> <span m='2132450'>talk</span>
  <span m='2132630'>a</span> <span m='2132680'>lot</span> <span m='2132850'>about</span>
  <span m='2133040'>that</span> <span m='2133200'>in a</span> <span m='2133240'>little</span>
  <span m='2133430'>while.</span> </p><p><span m='2134590'>What</span> <span m='2134800'>do
  we</span> <span m='2135010'>have</span> <span m='2135210'>here?</span> <span m='2136830'>Well,</span>
  <span m='2137040'>these</span> <span m='2137240'>are</span> <span m='2137300'>called</span>
  <span m='2137560'>frames.</span> <span m='2137990'>Here</span> <span m='2138140'>is</span>
  <span m='2138200'>a</span> <span m='2138270'>frame,</span> <span m='2139230'>here's</span>
  <span m='2139760'>a</span> <span m='2139820'>frame,</span> <span m='2140840'>and</span>
  <span m='2141010'>here's</span> <span m='2141230'>a</span> <span m='2141280'>frame.</span>
  <span m='2143270'>a</span> <span m='2143410'>is</span> <span m='2143590'>an</span>
  <span m='2143650'>environment</span> <span m='2144170'>which</span> <span m='2144320'>consists</span>
  <span m='2144820'>of</span> <span m='2145250'>the</span> <span m='2145430'>table</span>
  <span m='2146570'>which</span> <span m='2146730'>is</span> <span m='2147040'>frame</span>
  <span m='2147340'>two,</span> <span m='2148360'>followed</span> <span m='2148660'>by</span>
  <span m='2148770'>the</span> <span m='2148870'>table</span> <span m='2150100'>labeled</span>
  <span m='2150390'>frame</span> <span m='2150660'>one.</span> <span m='2152570'>And,</span>
  <span m='2153430'>in</span> <span m='2153630'>this</span> <span m='2153830'>environment,</span>
  <span m='2156090'>in</span> <span m='2156260'>say</span> <span m='2156580'>this</span>
  <span m='2156760'>environment,</span> <span m='2158930'>frame</span> <span m='2159280'>two,</span>
  <span m='2161780'>x</span> <span m='2162030'>and</span> <span m='2162220'>y</span>
  <span m='2162670'>are</span> <span m='2162840'>bound.</span> <span m='2164150'>They</span>
  <span m='2164270'>have</span> <span m='2164390'>values.</span> <span m='2165920'>Sorry,</span>
  <span m='2166220'>in</span> <span m='2166360'>frame</span> <span m='2166695'>one--</span>
  <span m='2167290'>In</span> <span m='2167420'>frame</span> <span m='2167730'>two,</span>
  <span m='2169790'>z</span> <span m='2170120'>is</span> <span m='2170270'>bound,</span>
  <span m='2170770'>and</span> <span m='2171270'>x</span> <span m='2171510'>is</span>
  <span m='2171660'>bound,</span> <span m='2172480'>and</span> <span m='2172780'>y</span>
  <span m='2173100'>is</span> <span m='2173260'>bound,</span> <span m='2175340'>but</span>
  <span m='2175590'>the</span> <span m='2175690'>value</span> <span m='2176130'>of</span>
  <span m='2176250'>x</span> <span m='2176680'>that</span> <span m='2176860'>we</span>
  <span m='2177050'>see,</span> <span m='2177550'>looking</span> <span m='2177880'>from</span>
  <span m='2178080'>this</span> <span m='2178300'>point</span> <span m='2178560'>of</span>
  <span m='2178620'>view,</span> <span m='2180050'>is</span> <span m='2180250'>this</span>
  <span m='2180470'>x.</span> <span m='2180940'>It's x</span> <span m='2181130'>is</span>
  <span m='2181180'>seven,</span> <span m='2182580'>rather</span> <span m='2182950'>than</span>
  <span m='2183380'>this</span> <span m='2183920'>one</span> <span m='2184130'>which</span>
  <span m='2184290'>is</span> <span m='2184410'>three.</span> <span m='2184940'>We</span>
  <span m='2185160'>say</span> <span m='2185440'>that</span> <span m='2185620'>this</span>
  <span m='2185800'>x</span> <span m='2186380'>shadows</span> <span m='2186990'>this</span>
  <span m='2187230'>x.</span> <span m='2191070'>From</span> <span m='2191330'>environment</span>
  <span m='2191920'>three--</span> <span m='2193320'>from</span> <span m='2193630'>frame</span>
  <span m='2193950'>three,</span> <span m='2194550'>from</span> <span m='2194770'>environment</span>
  <span m='2195190'>b,</span> <span m='2195870'>which</span> <span m='2196050'>refers</span>
  <span m='2196370'>to</span> <span m='2196460'>frame</span> <span m='2196780'>three,</span>
  <span m='2197540'>we</span> <span m='2197830'>have</span> <span m='2198300'>variables</span>
  <span m='2199810'>n</span> <span m='2200110'>and</span> <span m='2200300'>y</span>
  <span m='2200650'>bound</span> <span m='2201320'>and</span> <span m='2201480'>also</span>
  <span m='2201900'>x.</span> <span m='2204740'>This</span> <span m='2205190'>y</span>
  <span m='2205820'>shadow</span> <span m='2206310'>this</span> <span m='2206540'>one.</span>
  <span m='2208630'>So</span> <span m='2208820'>the</span> <span m='2208940'>value,</span>
  <span m='2209620'>looking</span> <span m='2209920'>from</span> <span m='2210080'>this</span>
  <span m='2210240'>point</span> <span m='2210500'>of</span> <span m='2210580'>view,</span>
  <span m='2210980'>of</span> <span m='2211350'>y</span> <span m='2212050'>is</span>
  <span m='2212240'>two.</span> <span m='2213410'>The</span> <span m='2213650'>value</span>
  <span m='2213990'>for</span> <span m='2214090'>looking</span> <span m='2214380'>from</span>
  <span m='2214500'>this</span> <span m='2214640'>point</span> <span m='2214840'>of</span>
  <span m='2214900'>view</span> <span m='2215690'>and</span> <span m='2215980'>m</span>
  <span m='2216110'>is one.</span> <span m='2216500'>And</span> <span m='2216620'>the</span>
  <span m='2216690'>value, looking</span> <span m='2217150'>from</span> <span m='2217260'>this</span>
  <span m='2217400'>point</span> <span m='2217580'>of</span> <span m='2217620'>view,</span>
  <span m='2217750'>of</span> <span m='2217860'>x</span> <span m='2218135'>is</span>
  <span m='2218410'>three.</span> </p><p><span m='2222310'>So</span> <span m='2222480'>there</span>
  <span m='2222640'>we</span> <span m='2222880'>have</span> <span m='2223220'>a</span>
  <span m='2223340'>very</span> <span m='2223570'>simple</span> <span m='2223890'>environment</span>
  <span m='2224300'>structure</span> <span m='2224620'>made</span> <span m='2224820'>out
  of</span> <span m='2224990'>frames.</span> <span m='2226340'>These</span> <span
  m='2226720'>correspond</span> <span m='2227610'>to</span> <span m='2228370'>the</span>
  <span m='2228490'>applications</span> <span m='2229140'>of</span> <span m='2229220'>procedures.</span>
  <span m='2230990'>And</span> <span m='2231130'>we'll</span> <span m='2231250'>see</span>
  <span m='2231400'>that</span> <span m='2231620'>in a</span> <span m='2231680'>second.</span>
  <span m='2234390'>So</span> <span m='2234520'>now</span> <span m='2234730'>I</span>
  <span m='2234800'>have to make</span> <span m='2234950'>you</span> <span m='2235120'>some</span>
  <span m='2235180'>other</span> <span m='2236000'>nice</span> <span m='2236290'>little</span>
  <span m='2236430'>structure</span> <span m='2236860'>that</span> <span m='2236980'>we</span>
  <span m='2237100'>build.</span> </p><p><span m='2240870'>Next</span> <span m='2241200'>slide,</span>
  <span m='2242210'>we</span> <span m='2242400'>see</span> <span m='2243780'>an</span>
  <span m='2243930'>object,</span> <span m='2245080'>which</span> <span m='2245240'>I'm</span>
  <span m='2245350'>going</span> <span m='2245430'>to</span> <span m='2245500'>draw</span>
  <span m='2245820'>procedures.</span> <span m='2247850'>This</span> <span m='2248070'>is</span>
  <span m='2248210'>a</span> <span m='2248350'>procedure.</span> <span m='2250190'>A</span>
  <span m='2250290'>procedure</span> <span m='2250700'>is</span> <span m='2250800'>made</span>
  <span m='2251000'>out of</span> <span m='2251210'>two</span> <span m='2251380'>parts.</span>
  <span m='2253150'>It's</span> <span m='2253320'>sort</span> <span m='2253450'>of</span>
  <span m='2253580'>like</span> <span m='2253860'>a</span> <span m='2254160'>cons.</span>
  <span m='2257210'>However,</span> <span m='2257500'>it's</span> <span m='2257620'>the</span>
  <span m='2257730'>two</span> <span m='2257900'>parts.</span> <span m='2260820'>The</span>
  <span m='2261110'>first</span> <span m='2261410'>part</span> <span m='2261720'>refers</span>
  <span m='2262300'>to</span> <span m='2263380'>some</span> <span m='2264140'>code,</span>
  <span m='2265690'>something</span> <span m='2266090'>that</span> <span m='2266180'>can</span>
  <span m='2266300'>be</span> <span m='2266410'>executed,</span> <span m='2267500'>a</span>
  <span m='2267630'>set</span> <span m='2267800'>of</span> <span m='2267880'>instructions,</span>
  <span m='2268530'>if</span> <span m='2268650'>you</span> <span m='2268770'>will.</span>
  <span m='2268940'>You</span> <span m='2269060'>can</span> <span m='2269180'>think</span>
  <span m='2269340'>of</span> <span m='2269420'>it</span> <span m='2269500'>that</span>
  <span m='2269740'>way.</span> <span m='2270750'>And</span> <span m='2270860'>the</span>
  <span m='2270970'>second</span> <span m='2271340'>part</span> <span m='2272020'>is</span>
  <span m='2272200'>the</span> <span m='2272270'>environment.</span> <span m='2273830'>The</span>
  <span m='2274150'>procedure</span> <span m='2274730'>is</span> <span m='2274800'>the</span>
  <span m='2274880'>whole</span> <span m='2275110'>thing.</span> <span m='2277250'>And</span>
  <span m='2277420'>we're</span> <span m='2277590'>going to have</span> <span m='2277740'>to</span>
  <span m='2277910'>use</span> <span m='2278170'>this</span> <span m='2279200'>to</span>
  <span m='2279620'>capture</span> <span m='2280430'>the</span> <span m='2280820'>values</span>
  <span m='2281290'>of</span> <span m='2281420'>the</span> <span m='2281500'>free</span>
  <span m='2281740'>variables</span> <span m='2284080'>that</span> <span m='2284290'>occur</span>
  <span m='2284570'>in</span> <span m='2284630'>the</span> <span m='2284710'>procedure.</span>
  <span m='2286250'>If a</span> <span m='2286350'>variable</span> <span m='2287340'>occurs</span>
  <span m='2287600'>in the</span> <span m='2287710'>procedure</span> <span m='2288120'>it's</span>
  <span m='2288320'>either</span> <span m='2288380'>bound</span> <span m='2288690'>in</span>
  <span m='2288760'>that</span> <span m='2288950'>procedure</span> <span m='2289350'>or</span>
  <span m='2289480'>free.</span> <span m='2291170'>If</span> <span m='2291310'>it's</span>
  <span m='2291460'>bound,</span> <span m='2292420'>then</span> <span m='2292820'>the</span>
  <span m='2292900'>value</span> <span m='2293250'>will</span> <span m='2293350'>somehow</span>
  <span m='2293670'>be</span> <span m='2293850'>easy</span> <span m='2294070'>to</span>
  <span m='2294150'>find.</span> <span m='2296930'>It will</span> <span m='2297250'>be
  in</span> <span m='2297380'>some</span> <span m='2297500'>easy</span> <span m='2297760'>environment</span>
  <span m='2298170'>to</span> <span m='2298220'>get</span> <span m='2298440'>at.</span>
  <span m='2299070'>If</span> <span m='2299230'>it's</span> <span m='2299400'>free,</span>
  <span m='2300910'>we're</span> <span m='2301030'>going</span> <span m='2301110'>to</span>
  <span m='2301190'>have</span> <span m='2301330'>to have</span> <span m='2301470'>something</span>
  <span m='2301720'>that</span> <span m='2301800'>goes</span> <span m='2302070'>with</span>
  <span m='2302170'>the</span> <span m='2302290'>procedure</span> <span m='2303000'>that</span>
  <span m='2303280'>says</span> <span m='2303450'>where</span> <span m='2303720'>we'll</span>
  <span m='2303930'>go look</span> <span m='2304090'>for</span> <span m='2304260'>its</span>
  <span m='2304380'>value.</span> <span m='2307100'>And</span> <span m='2307200'>the</span>
  <span m='2307300'>reasons</span> <span m='2307570'>why</span> <span m='2307940'>are</span>
  <span m='2308470'>not</span> <span m='2308660'>obvious</span> <span m='2309060'>yet,</span>
  <span m='2309280'>but</span> <span m='2309430'>will</span> <span m='2310080'>be</span>
  <span m='2310200'>soon.</span> </p><p><span m='2312290'>So</span> <span m='2312550'>here's</span>
  <span m='2312900'>a</span> <span m='2312950'>procedure</span> <span m='2313400'>object.</span>
  <span m='2313760'>It's</span> <span m='2313870'>a</span> <span m='2313920'>composite</span>
  <span m='2314490'>object</span> <span m='2314920'>consisting</span> <span m='2315350'>of</span>
  <span m='2315640'>a</span> <span m='2315860'>piece</span> <span m='2316090'>of</span>
  <span m='2316170'>code</span> <span m='2320200'>and</span> <span m='2320440'>a</span>
  <span m='2320720'>environment</span> <span m='2321230'>structure.</span> <span m='2322750'>Now</span>
  <span m='2322940'>I</span> <span m='2323040'>will</span> <span m='2323170'>tell</span>
  <span m='2323340'>you</span> <span m='2323490'>the</span> <span m='2323600'>new</span>
  <span m='2323760'>rules,</span> <span m='2324300'>the</span> <span m='2324550'>complete</span>
  <span m='2324930'>new</span> <span m='2325100'>rules,</span> <span m='2326400'>for</span>
  <span m='2326640'>evaluation.</span> <span m='2330690'>The</span> <span m='2330890'>first</span>
  <span m='2331100'>rule</span> <span m='2331330'>is--</span> <span m='2331400'>there's</span>
  <span m='2331630'>only two</span> <span m='2331820'>of</span> <span m='2331990'>them.</span>
  <span m='2333250'>These</span> <span m='2333480'>correspond</span> <span m='2334100'>to</span>
  <span m='2334150'>the</span> <span m='2334240'>substitution</span> <span m='2334780'>model</span>
  <span m='2335070'>rules.</span> <span m='2337250'>And the</span> <span m='2337550'>first</span>
  <span m='2337860'>one</span> <span m='2338310'>has</span> <span m='2338570'>to</span>
  <span m='2338680'>do</span> <span m='2338930'>with</span> <span m='2339660'>how</span>
  <span m='2339890'>do</span> <span m='2339980'>you</span> <span m='2340070'>apply</span>
  <span m='2340720'>a</span> <span m='2340830'>procedure</span> <span m='2341950'>to</span>
  <span m='2342150'>its</span> <span m='2342290'>arguments?</span> <span m='2345610'>And</span>
  <span m='2345750'>a</span> <span m='2346060'>procedural</span> <span m='2346550'>object</span>
  <span m='2346880'>is</span> <span m='2346950'>applied</span> <span m='2347530'>to</span>
  <span m='2347730'>a set</span> <span m='2347910'>of</span> <span m='2348020'>arguments</span>
  <span m='2348890'>by</span> <span m='2349140'>constructing</span> <span m='2349680'>a</span>
  <span m='2349750'>new</span> <span m='2349910'>frame.</span> <span m='2351270'>That</span>
  <span m='2351580'>frame</span> <span m='2351790'>will</span> <span m='2351940'>contain</span>
  <span m='2352560'>the</span> <span m='2352780'>mapping</span> <span m='2353320'>of</span>
  <span m='2353460'>the</span> <span m='2353550'>former</span> <span m='2353860'>parameters</span>
  <span m='2354340'>to</span> <span m='2354440'>the</span> <span m='2354570'>actual</span>
  <span m='2355000'>parameters</span> <span m='2355540'>of</span> <span m='2355610'>the</span>
  <span m='2356000'>arguments</span> <span m='2356540'>that</span> <span m='2356670'>were</span>
  <span m='2356820'>supplied</span> <span m='2358890'>in the</span> <span m='2359120'>call.</span>
  </p><p><span m='2361490'>As</span> <span m='2361680'>you</span> <span m='2361780'>know,</span>
  <span m='2362440'>when</span> <span m='2362590'>we</span> <span m='2362720'>make</span>
  <span m='2362950'>up</span> <span m='2363100'>a</span> <span m='2364010'>call</span>
  <span m='2364310'>to</span> <span m='2364380'>a</span> <span m='2364450'>procedure</span>
  <span m='2364830'>like</span> <span m='2365320'>lambda</span> <span m='2365680'>x</span>
  <span m='2366000'>times</span> <span m='2366330'>x</span> <span m='2366540'>y,</span>
  <span m='2366980'>and</span> <span m='2367080'>we</span> <span m='2367280'>call</span>
  <span m='2367540'>that</span> <span m='2367800'>with</span> <span m='2368040'>the</span>
  <span m='2368170'>argument</span> <span m='2368670'>three,</span> <span m='2370210'>then</span>
  <span m='2370500'>we're</span> <span m='2370590'>going</span> <span m='2370680'>to</span>
  <span m='2370770'>need</span> <span m='2371070'>some</span> <span m='2371280'>mapping</span>
  <span m='2371720'>of</span> <span m='2371900'>x</span> <span m='2372190'>to</span>
  <span m='2372310'>three.</span> <span m='2374290'>It's</span> <span m='2374420'>the</span>
  <span m='2374480'>same</span> <span m='2374740'>thing</span> <span m='2374940'>as</span>
  <span m='2375090'>later</span> <span m='2375380'>substituting,</span> <span m='2376810'>if</span>
  <span m='2376940'>you</span> <span m='2377070'>will,</span> <span m='2377910'>the</span>
  <span m='2378490'>three</span> <span m='2378770'>for</span> <span m='2378900'>the</span>
  <span m='2379080'>x</span> <span m='2379540'>in</span> <span m='2379640'>the</span>
  <span m='2379730'>old</span> <span m='2379960'>model.</span> <span m='2381990'>So</span>
  <span m='2382160'>I'm</span> <span m='2382270'>going</span> <span m='2382340'>to</span>
  <span m='2382420'>build</span> <span m='2382620'>a</span> <span m='2382660'>frame</span>
  <span m='2383200'>which</span> <span m='2383370'>contains</span> <span m='2383900'>x</span>
  <span m='2384080'>equals</span> <span m='2384360'>three</span> <span m='2385160'>as</span>
  <span m='2385300'>the</span> <span m='2385390'>information</span> <span m='2385900'>in</span>
  <span m='2385990'>that</span> <span m='2386200'>frame.</span> </p><p><span m='2389230'>Now,</span>
  <span m='2389870'>the</span> <span m='2390530'>body</span> <span m='2390860'>of</span>
  <span m='2390920'>the</span> <span m='2391000'>procedure</span> <span m='2391400'>will</span>
  <span m='2391550'>then</span> <span m='2391700'>have</span> <span m='2391850'>to</span>
  <span m='2391940'>be</span> <span m='2392030'>evaluated</span> <span m='2392640'>which</span>
  <span m='2392810'>is</span> <span m='2392920'>this.</span> <span m='2394170'>I</span>
  <span m='2394350'>will</span> <span m='2394480'>be</span> <span m='2394620'>evaluated</span>
  <span m='2395440'>in</span> <span m='2395650'>an</span> <span m='2395720'>environment</span>
  <span m='2404120'>which</span> <span m='2404460'>is</span> <span m='2404710'>constructed</span>
  <span m='2405690'>by</span> <span m='2406060'>adjoining</span> <span m='2406470'>the</span>
  <span m='2406550'>new</span> <span m='2406730'>frame</span> <span m='2407060'>that</span>
  <span m='2407140'>we</span> <span m='2407260'>just</span> <span m='2407510'>made</span>
  <span m='2408420'>to</span> <span m='2408780'>the</span> <span m='2408930'>environment</span>
  <span m='2409460'>which</span> <span m='2409610'>was</span> <span m='2409800'>part</span>
  <span m='2410200'>of</span> <span m='2410320'>the</span> <span m='2410450'>procedure</span>
  <span m='2410920'>that</span> <span m='2411030'>we</span> <span m='2411140'>applied.</span>
  </p><p><span m='2413100'>So</span> <span m='2413290'>I'm</span> <span m='2413420'>going</span>
  <span m='2413640'>to</span> <span m='2414200'>make</span> <span m='2414480'>a</span>
  <span m='2414530'>little</span> <span m='2414750'>example</span> <span m='2415150'>of</span>
  <span m='2415220'>that</span> <span m='2415430'>here.</span> <span m='2419220'>Supposing</span>
  <span m='2420430'>I</span> <span m='2420590'>have</span> <span m='2423180'>some</span>
  <span m='2423500'>environment.</span> <span m='2425110'>Here's</span> <span m='2425340'>a</span>
  <span m='2425400'>frame</span> <span m='2426400'>which</span> <span m='2426540'>represents</span>
  <span m='2426920'>it.</span> <span m='2427980'>And</span> <span m='2428260'>some</span>
  <span m='2428470'>procedure--</span> <span m='2428940'>which</span> <span m='2429090'>I'm</span>
  <span m='2429190'>going to</span> <span m='2429380'>draw</span> <span m='2429590'>with</span>
  <span m='2429950'>circles</span> <span m='2430190'>here because it's</span> <span
  m='2430410'>easier</span> <span m='2430790'>than</span> <span m='2431340'>little</span>
  <span m='2431520'>triangles--</span> <span m='2433370'>Sorry,</span> <span m='2435430'>those</span>
  <span m='2435700'>are</span> <span m='2435740'>rhombuses,</span> <span m='2437780'>rhomboidal</span>
  <span m='2438250'>little</span> <span m='2438460'>pieces</span> <span m='2438780'>of</span>
  <span m='2438940'>fruit</span> <span m='2439680'>jelly</span> <span m='2440120'>or</span>
  <span m='2440250'>something.</span> </p><p><span m='2442710'>So</span> <span m='2442930'>here's</span>
  <span m='2443220'>a</span> <span m='2443510'>procedure</span> <span m='2444070'>which</span>
  <span m='2444250'>takes</span> <span m='2444500'>this</span> <span m='2444670'>environment.</span>
  <span m='2445960'>And</span> <span m='2446510'>the</span> <span m='2446700'>procedure</span>
  <span m='2447150'>has</span> <span m='2447290'>a</span> <span m='2447340'>piece</span>
  <span m='2447530'>of</span> <span m='2447610'>code,</span> <span m='2448230'>which</span>
  <span m='2448400'>is</span> <span m='2448490'>a</span> <span m='2448700'>lambda</span>
  <span m='2448920'>expression,</span> <span m='2450200'>which</span> <span m='2450400'>binds</span>
  <span m='2450780'>x</span> <span m='2451010'>and</span> <span m='2451150'>y</span>
  <span m='2453210'>and</span> <span m='2453460'>then</span> <span m='2453630'>executes</span>
  <span m='2454480'>an</span> <span m='2455600'>expression,</span> <span m='2456160'>e.</span>
  <span m='2458010'>And</span> <span m='2458230'>this</span> <span m='2458380'>is
  the</span> <span m='2458480'>procedure.</span> <span m='2459345'>We'll</span> <span
  m='2459650'>call it</span> <span m='2459920'>p.</span> <span m='2461470'>I</span>
  <span m='2461630'>wish</span> <span m='2461840'>to</span> <span m='2461970'>apply</span>
  <span m='2462700'>that</span> <span m='2463040'>procedure</span> <span m='2464550'>to</span>
  <span m='2465080'>three</span> <span m='2465340'>and</span> <span m='2465460'>four.</span>
  <span m='2466490'>So</span> <span m='2466590'>I</span> <span m='2466820'>want to</span>
  <span m='2466930'>do</span> <span m='2467205'>p of</span> <span m='2467480'>three</span>
  <span m='2467840'>and</span> <span m='2468030'>four.</span> </p><p><span m='2469790'>What</span>
  <span m='2470050'>I'm</span> <span m='2470130'>going</span> <span m='2470330'>to</span>
  <span m='2470400'>do,</span> <span m='2470590'>of</span> <span m='2470800'>course,</span>
  <span m='2471040'>is</span> <span m='2471200'>make</span> <span m='2471410'>a</span>
  <span m='2471460'>new</span> <span m='2471600'>frame.</span> <span m='2473210'>I</span>
  <span m='2473360'>build</span> <span m='2473570'>a</span> <span m='2473620'>frame</span>
  <span m='2475290'>which</span> <span m='2475500'>contains</span> <span m='2476620'>x</span>
  <span m='2477390'>equals</span> <span m='2477820'>three,</span> <span m='2478630'>and</span>
  <span m='2479100'>y</span> <span m='2479660'>equals</span> <span m='2480080'>four.</span>
  <span m='2481740'>I'm</span> <span m='2481990'>going</span> <span m='2482220'>to</span>
  <span m='2482310'>connect</span> <span m='2482740'>that</span> <span m='2482990'>frame</span>
  <span m='2484370'>to</span> <span m='2484700'>this</span> <span m='2484820'>frame</span>
  <span m='2484900'>over</span> <span m='2485170'>here.</span> <span m='2487680'>And</span>
  <span m='2487930'>then</span> <span m='2488100'>this</span> <span m='2488310'>environment,</span>
  <span m='2489810'>with</span> <span m='2490010'>I will</span> <span m='2490230'>call</span>
  <span m='2490570'>b,</span> <span m='2491590'>is</span> <span m='2491810'>the</span>
  <span m='2491940'>environment</span> <span m='2492440'>in</span> <span m='2492550'>which</span>
  <span m='2492750'>I</span> <span m='2492840'>will</span> <span m='2493010'>evaluate</span>
  <span m='2493920'>the</span> <span m='2494060'>body</span> <span m='2494470'>of</span>
  <span m='2494540'>e.</span> <span m='2499940'>Now,</span> <span m='2501980'>e</span>
  <span m='2502220'>may</span> <span m='2502400'>contain</span> <span m='2503120'>references</span>
  <span m='2503630'>to</span> <span m='2503720'>x</span> <span m='2504020'>and</span>
  <span m='2504180'>y</span> <span m='2504420'>and</span> <span m='2504570'>other</span>
  <span m='2504730'>things.</span> <span m='2506890'>x</span> <span m='2507120'>and</span>
  <span m='2507250'>y</span> <span m='2508090'>will</span> <span m='2508780'>have</span>
  <span m='2509010'>values</span> <span m='2509500'>right</span> <span m='2509720'>here.</span>
  <span m='2510790'>Other</span> <span m='2511050'>things</span> <span m='2511390'>will</span>
  <span m='2511500'>have</span> <span m='2511670'>their</span> <span m='2511820'>values</span>
  <span m='2512310'>here.</span> </p><p><span m='2515040'>How</span> <span m='2515230'>do</span>
  <span m='2515320'>we</span> <span m='2515420'>get</span> <span m='2515640'>this</span>
  <span m='2515820'>frame?</span> <span m='2516920'>That</span> <span m='2517490'>we</span>
  <span m='2517600'>do</span> <span m='2517760'>by</span> <span m='2517910'>the</span>
  <span m='2517990'>construction</span> <span m='2518550'>of</span> <span m='2518620'>procedures</span>
  <span m='2519640'>which</span> <span m='2519860'>is</span> <span m='2519950'>the</span>
  <span m='2520110'>other</span> <span m='2520260'>rule.</span> <span m='2521980'>And</span>
  <span m='2522120'>I</span> <span m='2522270'>think</span> <span m='2522510'>that's</span>
  <span m='2523560'>the</span> <span m='2523780'>next</span> <span m='2524010'>slide.</span>
  <span m='2525500'>Rule</span> <span m='2525780'>two,</span> <span m='2527910'>when</span>
  <span m='2528070'>a lambda</span> <span m='2528500'>expression</span> <span m='2528990'>is</span>
  <span m='2529080'>evaluated,</span> <span m='2530000'>relative</span> <span m='2530420'>to</span>
  <span m='2530500'>a</span> <span m='2530580'>particular</span> <span m='2531080'>environment--</span>
  <span m='2534150'>See,</span> <span m='2534480'>the</span> <span m='2535160'>way</span>
  <span m='2535310'>I</span> <span m='2535450'>get</span> <span m='2535670'>a</span>
  <span m='2535710'>procedure</span> <span m='2536250'>is</span> <span m='2536410'>by</span>
  <span m='2536570'>evaluating</span> <span m='2537090'>the</span> <span m='2537180'>lambda</span>
  <span m='2537470'>expression.</span> </p><p><span m='2538300'>Here's</span> <span
  m='2538620'>a</span> <span m='2538810'>lambda</span> <span m='2539310'>expression.</span>
  <span m='2540110'>By</span> <span m='2540270'>evaluating</span> <span m='2541030'>it,</span>
  <span m='2541900'>I</span> <span m='2542070'>get</span> <span m='2542220'>a</span>
  <span m='2542260'>procedure</span> <span m='2542630'>which</span> <span m='2542800'>I</span>
  <span m='2542880'>can</span> <span m='2543000'>apply</span> <span m='2543370'>to</span>
  <span m='2543520'>three.</span> <span m='2545170'>Now</span> <span m='2545360'>this</span>
  <span m='2545560'>lambda</span> <span m='2545870'>expression</span> <span m='2546810'>is</span>
  <span m='2546980'>evaluated</span> <span m='2547300'>in an</span> <span m='2547620'>environment</span>
  <span m='2548710'>where</span> <span m='2549000'>y</span> <span m='2549700'>is</span>
  <span m='2549860'>defined.</span> <span m='2551820'>And</span> <span m='2551990'>I</span>
  <span m='2552090'>want</span> <span m='2552370'>the</span> <span m='2552460'>body</span>
  <span m='2552860'>of</span> <span m='2552930'>this</span> <span m='2553130'>which</span>
  <span m='2553290'>contains</span> <span m='2553670'>a</span> <span m='2553760'>free</span>
  <span m='2554870'>version</span> <span m='2555280'>of</span> <span m='2555400'>y.</span>
  <span m='2556680'>y</span> <span m='2556990'>is</span> <span m='2557170'>free</span>
  <span m='2557790'>in</span> <span m='2558000'>here,</span> <span m='2558780'>it's</span>
  <span m='2559010'>bound</span> <span m='2559410'>over</span> <span m='2559670'>the</span>
  <span m='2559770'>whole</span> <span m='2560030'>thing,</span> <span m='2561480'>but</span>
  <span m='2561630'>it's</span> <span m='2561790'>free</span> <span m='2562160'>over</span>
  <span m='2562370'>here.</span> <span m='2563350'>I</span> <span m='2563510'>want</span>
  <span m='2563830'>that</span> <span m='2564080'>y</span> <span m='2565460'>to</span>
  <span m='2565590'>be</span> <span m='2565820'>this</span> <span m='2566040'>one.</span>
  <span m='2567440'>I</span> <span m='2567620'>evaluate</span> <span m='2568330'>this</span>
  <span m='2568750'>body</span> <span m='2569860'>of</span> <span m='2570150'>this</span>
  <span m='2570390'>procedure</span> <span m='2571850'>in</span> <span m='2572060'>the</span>
  <span m='2572190'>environment</span> <span m='2573150'>where</span> <span m='2573460'>y</span>
  <span m='2574270'>was</span> <span m='2574420'>created.</span> <span m='2575470'>That's</span>
  <span m='2575620'>this</span> <span m='2575820'>kind</span> <span m='2575960'>of</span>
  <span m='2576100'>thing,</span> <span m='2576430'>because</span> <span m='2576640'>that
  was</span> <span m='2576750'>done</span> <span m='2576900'>by</span> <span m='2577800'>application.</span>
  </p><p><span m='2579140'>Now,</span> <span m='2580330'>if</span> <span m='2580490'>I</span>
  <span m='2580600'>ever</span> <span m='2580800'>want</span> <span m='2580930'>to</span>
  <span m='2581050'>look</span> <span m='2581300'>up</span> <span m='2581580'>the</span>
  <span m='2581720'>value</span> <span m='2582070'>of</span> <span m='2582180'>y,</span>
  <span m='2583140'>I</span> <span m='2583280'>have to</span> <span m='2583370'>know</span>
  <span m='2583490'>where</span> <span m='2583710'>it</span> <span m='2583760'>is.</span>
  <span m='2584370'>Therefore,</span> <span m='2584950'>this</span> <span m='2585180'>procedural</span>
  <span m='2585640'>was</span> <span m='2585800'>created,</span> <span m='2586720'>the</span>
  <span m='2586790'>creation</span> <span m='2587260'>of</span> <span m='2587360'>the</span>
  <span m='2587440'>procedure</span> <span m='2587880'>which</span> <span m='2588070'>is</span>
  <span m='2588150'>the</span> <span m='2588240'>result</span> <span m='2588570'>of</span>
  <span m='2588680'>evaluating</span> <span m='2589130'>that</span> <span m='2589330'>lambda</span>
  <span m='2589530'>expression</span> <span m='2590140'>had</span> <span m='2590340'>better</span>
  <span m='2590570'>capture</span> <span m='2592200'>a</span> <span m='2592310'>pointer</span>
  <span m='2592780'>or</span> <span m='2593150'>remember</span> <span m='2594230'>the</span>
  <span m='2594480'>frame</span> <span m='2594820'>in</span> <span m='2594900'>which</span>
  <span m='2595100'>y</span> <span m='2595760'>was</span> <span m='2595940'>bound.</span>
  <span m='2598110'>So</span> <span m='2598310'>that's</span> <span m='2598510'>what</span>
  <span m='2598620'>this</span> <span m='2598790'>rule</span> <span m='2599090'>is</span>
  <span m='2599180'>telling</span> <span m='2599530'>us.</span> </p><p><span m='2602100'>So,</span>
  <span m='2602350'>for</span> <span m='2602610'>example,</span> <span m='2604590'>if</span>
  <span m='2604800'>I</span> <span m='2604890'>happen</span> <span m='2605310'>to</span>
  <span m='2605450'>be</span> <span m='2606370'>evaluating</span> <span m='2608180'>a</span>
  <span m='2608300'>lambda</span> <span m='2608610'>expression,</span> <span m='2611030'>lambda</span>
  <span m='2611280'>expression</span> <span m='2612530'>in</span> <span m='2612790'>e,</span>
  <span m='2614100'>lambda</span> <span m='2614400'>of</span> <span m='2614640'>say,</span>
  <span m='2614870'>x</span> <span m='2615250'>and</span> <span m='2615390'>y,</span>
  <span m='2617370'>let's</span> <span m='2617530'>call</span> <span m='2617790'>it</span>
  <span m='2618400'>g</span> <span m='2619630'>in</span> <span m='2619910'>e,</span>
  <span m='2621410'>evaluating</span> <span m='2622040'>that.</span> <span m='2623020'>Well,</span>
  <span m='2623340'>all that</span> <span m='2623570'>means</span> <span m='2624130'>is</span>
  <span m='2624290'>I</span> <span m='2624420'>now</span> <span m='2624650'>construct</span>
  <span m='2625180'>a</span> <span m='2625230'>procedure</span> <span m='2625710'>object.</span>
  <span m='2627190'>e is</span> <span m='2627470'>some</span> <span m='2627690'>environment.</span>
  <span m='2628990'>e is</span> <span m='2629270'>something</span> <span m='2629810'>which</span>
  <span m='2629950'>has</span> <span m='2630080'>a</span> <span m='2630130'>pointer</span>
  <span m='2630500'>to</span> <span m='2630740'>it.</span> <span m='2631920'>I</span>
  <span m='2632090'>construct</span> <span m='2633280'>a</span> <span m='2633390'>procedure</span>
  <span m='2633860'>object</span> <span m='2635320'>that</span> <span m='2635460'>points</span>
  <span m='2635710'>up</span> <span m='2635840'>to</span> <span m='2635930'>that</span>
  <span m='2636120'>environment,</span> <span m='2638690'>where</span> <span m='2639100'>the</span>
  <span m='2639230'>code</span> <span m='2639720'>of that</span> <span m='2640670'>is</span>
  <span m='2640830'>a</span> <span m='2640990'>lambda</span> <span m='2641280'>expression</span>
  <span m='2641750'>or</span> <span m='2641830'>whatever</span> <span m='2642120'>that</span>
  <span m='2642290'>translates</span> <span m='2642770'>into.</span> <span m='2646330'>And</span>
  <span m='2646510'>this</span> <span m='2646700'>is</span> <span m='2646820'>the</span>
  <span m='2646910'>procedure.</span> </p><p><span m='2652380'>So</span> <span m='2652530'>this</span>
  <span m='2652750'>produces</span> <span m='2653320'>for</span> <span m='2653540'>me--</span>
  <span m='2653800'>this</span> <span m='2655470'>object</span> <span m='2655910'>here,</span>
  <span m='2656570'>this</span> <span m='2657040'>environment</span> <span m='2657640'>pointer,</span>
  <span m='2658290'>captures</span> <span m='2659040'>the</span> <span m='2659140'>place</span>
  <span m='2659760'>where</span> <span m='2659970'>this</span> <span m='2660220'>lambda</span>
  <span m='2660590'>expression</span> <span m='2661140'>was</span> <span m='2661680'>evaluated,</span>
  <span m='2662670'>where</span> <span m='2662790'>the</span> <span m='2662910'>definition</span>
  <span m='2663850'>was</span> <span m='2664130'>used,</span> <span m='2665610'>where
  the</span> <span m='2665820'>definition</span> <span m='2666180'>was</span> <span
  m='2666320'>used</span> <span m='2666510'>to</span> <span m='2666610'>make</span>
  <span m='2666850'>a</span> <span m='2666900'>procedure,</span> <span m='2670120'>to</span>
  <span m='2670500'>make</span> <span m='2670810'>the</span> <span m='2670920'>procedure.</span>
  <span m='2672950'>So</span> <span m='2673120'>it</span> <span m='2673250'>picks</span>
  <span m='2673490'>up</span> <span m='2673660'>the</span> <span m='2673810'>environment</span>
  <span m='2674360'>from</span> <span m='2674500'>the</span> <span m='2674580'>place</span>
  <span m='2674870'>where</span> <span m='2675020'>that</span> <span m='2675190'>procedure</span>
  <span m='2675540'>was</span> <span m='2675700'>defined,</span> <span m='2677310'>stores</span>
  <span m='2677790'>it in</span> <span m='2678010'>the</span> <span m='2678090'>procedure</span>
  <span m='2678530'>itself,</span> <span m='2679680'>and</span> <span m='2679880'>then</span>
  <span m='2679970'>when the</span> <span m='2680040'>procedure</span> <span m='2680430'>is</span>
  <span m='2680510'>used,</span> <span m='2681340'>the</span> <span m='2681510'>environment</span>
  <span m='2681980'>where</span> <span m='2682120'>it</span> <span m='2682210'>was</span>
  <span m='2682300'>defined</span> <span m='2682710'>is</span> <span m='2682840'>extended</span>
  <span m='2683490'>with</span> <span m='2683910'>the</span> <span m='2684370'>new</span>
  <span m='2684510'>frame.</span> </p><p><span m='2688740'>So</span> <span m='2688880'>this</span>
  <span m='2689010'>gives</span> <span m='2689190'>us</span> <span m='2689300'>a</span>
  <span m='2689370'>locus</span> <span m='2689830'>for</span> <span m='2689920'>putting</span>
  <span m='2690400'>where</span> <span m='2690990'>a</span> <span m='2691170'>variable</span>
  <span m='2691600'>has</span> <span m='2691770'>a</span> <span m='2691820'>value.</span>
  <span m='2693090'>And,</span> <span m='2693250'>for</span> <span m='2693450'>example,</span>
  <span m='2694090'>if</span> <span m='2694200'>there</span> <span m='2694370'>are</span>
  <span m='2694410'>lots</span> <span m='2694720'>of</span> <span m='2694820'>guys</span>
  <span m='2695120'>pointing</span> <span m='2695490'>in at</span> <span m='2695700'>that</span>
  <span m='2696210'>environment,</span> <span m='2697820'>then</span> <span m='2697980'>they</span>
  <span m='2698090'>share</span> <span m='2699440'>that</span> <span m='2699920'>place.</span>
  <span m='2701430'>And</span> <span m='2701540'>we'll see</span> <span m='2701710'>more</span>
  <span m='2701910'>of</span> <span m='2702050'>that</span> <span m='2702180'>shortly.</span>
  </p><p><span m='2703810'>Well,</span> <span m='2704220'>now</span> <span m='2704440'>you</span>
  <span m='2704520'>have</span> <span m='2704650'>a</span> <span m='2704690'>new</span>
  <span m='2704900'>model</span> <span m='2707310'>for</span> <span m='2708310'>understanding</span>
  <span m='2708860'>the</span> <span m='2708940'>execution</span> <span m='2709400'>of</span>
  <span m='2709470'>programs.</span> <span m='2710573'>I</span> <span m='2711046'>suppose</span>
  <span m='2711520'>I'll</span> <span m='2711750'>take</span> <span m='2711970'>questions</span>
  <span m='2712420'>now,</span> <span m='2713340'>and</span> <span m='2713560'>then
  we'll</span> <span m='2713670'>go</span> <span m='2713840'>on</span> <span m='2713970'>and</span>
  <span m='2714080'>use</span> <span m='2714300'>that</span> <span m='2714510'>for</span>
  <span m='2714600'>something.</span> </p><p><span m='2717802'>AUDIENCE:</span> <span
  m='2718280'>Is</span> <span m='2718440'>it</span> <span m='2718610'>right</span>
  <span m='2718890'>to</span> <span m='2718980'>say</span> <span m='2719240'>then,</span>
  <span m='2719540'>the</span> <span m='2719750'>environment</span> <span m='2721010'>is</span>
  <span m='2721240'>that</span> <span m='2721870'>linked</span> <span m='2722440'>chain</span>
  <span m='2723060'>of</span> <span m='2723310'>frames--</span> </p><p><span m='2723695'>PROFESSOR:</span>
  <span m='2724080'>That's</span> <span m='2724270'>right.</span> </p><p><span m='2724580'>AUDIENCE:</span>
  <span m='2724890'>starting with--</span> <span m='2725650'>working</span> <span
  m='2725950'>all</span> <span m='2726120'>the</span> <span m='2726370'>way</span>
  <span m='2726730'>back?</span> </p><p><span m='2727076'>PROFESSOR:</span> <span
  m='2727422'>Yes, the</span> <span m='2727770'>environment</span> <span m='2728360'>is</span>
  <span m='2728630'>a</span> <span m='2728750'>sequence</span> <span m='2729240'>of</span>
  <span m='2729400'>frames</span> <span m='2730630'>linked</span> <span m='2730870'>together.</span>
  <span m='2732470'>And</span> <span m='2732850'>the</span> <span m='2733110'>way</span>
  <span m='2733240'>I</span> <span m='2733380'>like</span> <span m='2733540'>to</span>
  <span m='2733610'>think</span> <span m='2733760'>about</span> <span m='2734030'>it,</span>
  <span m='2734110'>it's</span> <span m='2734190'>the</span> <span m='2734280'>pointer</span>
  <span m='2734600'>to</span> <span m='2734700'>the</span> <span m='2734880'>first</span>
  <span m='2735050'>one,</span> <span m='2736930'>because</span> <span m='2737290'>once</span>
  <span m='2737750'>you've</span> <span m='2737830'>got</span> <span m='2738040'>that
  you've</span> <span m='2738260'>got</span> <span m='2738430'>them</span> <span m='2738670'>all.</span>
  <span m='2744080'>Anybody</span> <span m='2744350'>else?</span> </p><p><span m='2744995'>AUDIENCE:</span>
  <span m='2745260'>Is</span> <span m='2745330'>it</span> <span m='2745480'>possible</span>
  <span m='2745940'>to</span> <span m='2746080'>evaluate</span> <span m='2746550'>a</span>
  <span m='2746620'>procedure</span> <span m='2747520'>or</span> <span m='2747630'>to</span>
  <span m='2747800'>define</span> <span m='2747990'>a</span> <span m='2748050'>procedure</span>
  <span m='2748420'>in</span> <span m='2748570'>two different</span> <span m='2748750'>environments</span>
  <span m='2749025'>such</span> <span m='2749300'>that it will</span> <span m='2749750'>behave</span>
  <span m='2750170'>differently,</span> <span m='2751400'>and</span> <span m='2751580'>have</span>
  <span m='2751700'>pointers to</span> <span m='2751800'>both--</span> </p><p><span
  m='2752140'>PROFESSOR:</span> <span m='2752400'>Oh, yes.</span> <span m='2753600'>The</span>
  <span m='2753670'>same</span> <span m='2753970'>procedure</span> <span m='2754370'>is</span>
  <span m='2754440'>not</span> <span m='2754630'>going</span> <span m='2754700'>to</span>
  <span m='2754770'>have</span> <span m='2754920'>two</span> <span m='2755030'>different</span>
  <span m='2755260'>environments.</span> <span m='2757290'>The</span> <span m='2757410'>same</span>
  <span m='2758320'>code,</span> <span m='2759150'>the</span> <span m='2759270'>same</span>
  <span m='2759570'>lambda</span> <span m='2759920'>expression</span> <span m='2760930'>can</span>
  <span m='2761120'>be</span> <span m='2761320'>evaluated</span> <span m='2761800'>in
  two</span> <span m='2761990'>environments</span> <span m='2762410'>producing</span>
  <span m='2762760'>two</span> <span m='2762860'>different</span> <span m='2763110'>procedures.</span>
  <span m='2766220'>Each</span> <span m='2766490'>procedure--</span> </p><p><span
  m='2767140'>AUDIENCE:</span> <span m='2767370'>Their definition</span> <span m='2767870'>has</span>
  <span m='2768030'>the</span> <span m='2768100'>same</span> <span m='2768400'>name.</span>
  <span m='2768690'>Their</span> <span m='2768810'>operation--</span> </p><p><span
  m='2769170'>PROFESSOR:</span> <span m='2769250'>The definition</span> <span m='2770010'>is</span>
  <span m='2770190'>written</span> <span m='2770590'>the</span> <span m='2770680'>same,</span>
  <span m='2770940'>with</span> <span m='2771010'>the</span> <span m='2771070'>same</span>
  <span m='2771290'>characters.</span> <span m='2772570'>I</span> <span m='2772730'>can</span>
  <span m='2772870'>evaluate</span> <span m='2773400'>that</span> <span m='2773630'>set</span>
  <span m='2773780'>of</span> <span m='2773860'>characters,</span> <span m='2775060'>whatever,</span>
  <span m='2776500'>that</span> <span m='2776700'>list</span> <span m='2776900'>structure</span>
  <span m='2777220'>that</span> <span m='2777370'>defines,</span> <span m='2778240'>that</span>
  <span m='2778670'>is</span> <span m='2778950'>the</span> <span m='2779090'>textual</span>
  <span m='2779530'>representation.</span> <span m='2781340'>I</span> <span m='2781530'>can</span>
  <span m='2781730'>evaluate</span> <span m='2782300'>that</span> <span m='2782730'>in</span>
  <span m='2782910'>two</span> <span m='2783030'>different</span> <span m='2783320'>environments</span>
  <span m='2783650'>producing</span> <span m='2783970'>two different</span> <span
  m='2784300'>procedures.</span> <span m='2785650'>Each</span> <span m='2785850'>of</span>
  <span m='2785920'>those</span> <span m='2786150'>procedures</span> <span m='2787550'>has</span>
  <span m='2787880'>its</span> <span m='2788020'>own</span> <span m='2788760'>local</span>
  <span m='2791180'>sets</span> <span m='2791270'>of</span> <span m='2791700'>variables,</span>
  <span m='2792470'>and</span> <span m='2792600'>we'll</span> <span m='2792710'>see</span>
  <span m='2792880'>that</span> <span m='2793060'>right</span> <span m='2793280'>now.</span>
  <span m='2796770'>Anybody</span> <span m='2797210'>else?</span> <span m='2802670'>OK,</span>
  <span m='2802930'>thank</span> <span m='2803180'>you.</span> <span m='2803280'>Let's</span>
  <span m='2803440'>take</span> <span m='2803590'>a</span> <span m='2803630'>break.</span>
  <span m='2808750'>[MUSIC PLAYING]</span> </p><p><span m='2842870'>Well,</span> <span
  m='2843770'>now</span> <span m='2844170'>I've</span> <span m='2844410'>done</span>
  <span m='2844550'>this</span> <span m='2844680'>terrible</span> <span m='2845080'>thing</span>
  <span m='2845330'>to</span> <span m='2845420'>you.</span> <span m='2846670'>I've</span>
  <span m='2846830'>introduced</span> <span m='2848490'>a</span> <span m='2848610'>very</span>
  <span m='2849280'>complicated</span> <span m='2850020'>thing,</span> <span m='2852890'>assignment,</span>
  <span m='2854600'>which</span> <span m='2854810'>destroys</span> <span m='2855350'>most</span>
  <span m='2855620'>of</span> <span m='2855670'>the</span> <span m='2855750'>interesting</span>
  <span m='2856090'>mathematical</span> <span m='2856680'>properties</span> <span
  m='2857190'>of</span> <span m='2857320'>our</span> <span m='2857420'>programs.</span>
  <span m='2861230'>Why</span> <span m='2861550'>should</span> <span m='2861760'>I</span>
  <span m='2861890'>have</span> <span m='2862020'>done</span> <span m='2862240'>this?</span>
  <span m='2863270'>What</span> <span m='2863580'>possible</span> <span m='2864090'>good</span>
  <span m='2864340'>could</span> <span m='2864480'>this</span> <span m='2864720'>do?</span>
  <span m='2866590'>Clearly</span> <span m='2867130'>not</span> <span m='2867960'>a</span>
  <span m='2868000'>nice</span> <span m='2868370'>thing,</span> <span m='2869550'>so</span>
  <span m='2869760'>I</span> <span m='2869840'>better</span> <span m='2870060'>have</span>
  <span m='2870310'>a</span> <span m='2870380'>good</span> <span m='2870530'>excuse.</span>
  <span m='2872490'>Well,</span> <span m='2872910'>let's</span> <span m='2873300'>do</span>
  <span m='2873480'>a</span> <span m='2873500'>little</span> <span m='2873730'>bit</span>
  <span m='2873890'>of</span> <span m='2874180'>playing,</span> <span m='2874750'>first</span>
  <span m='2875160'>of</span> <span m='2875300'>all,</span> <span m='2875890'>with</span>
  <span m='2876150'>some</span> <span m='2876430'>very</span> <span m='2876730'>interesting</span>
  <span m='2877080'>programs</span> <span m='2877460'>that</span> <span m='2877570'>have</span>
  <span m='2877690'>assignment.</span> <span m='2878870'>Understand</span> <span m='2879560'>something</span>
  <span m='2879800'>special</span> <span m='2880240'>about</span> <span m='2880560'>them</span>
  <span m='2881450'>that</span> <span m='2881650'>makes</span> <span m='2881870'>them</span>
  <span m='2882000'>somewhat</span> <span m='2882370'>valuable.</span> </p><p><span
  m='2884820'>Start</span> <span m='2885250'>with</span> <span m='2885340'>a</span>
  <span m='2885420'>very</span> <span m='2885680'>simple</span> <span m='2886080'>program</span>
  <span m='2887820'>which</span> <span m='2887930'>I'm</span> <span m='2888010'>going
  to</span> <span m='2888110'>call</span> <span m='2888320'>make-counter.</span> <span
  m='2890670'>I'm</span> <span m='2890910'>going to</span> <span m='2891030'>define</span>
  <span m='2897340'>make-counter</span> <span m='2904190'>to</span> <span m='2904380'>be</span>
  <span m='2904560'>a</span> <span m='2904700'>procedure</span> <span m='2906480'>of</span>
  <span m='2906690'>one</span> <span m='2906900'>argument</span> <span m='2907570'>n</span>
  <span m='2909240'>which</span> <span m='2909510'>returns</span> <span m='2910080'>as</span>
  <span m='2910210'>its</span> <span m='2910380'>value</span> <span m='2911150'>a</span>
  <span m='2911280'>procedure</span> <span m='2911900'>of</span> <span m='2912040'>no</span>
  <span m='2912280'>arguments--</span> <span m='2914390'>a</span> <span m='2914640'>procedure</span>
  <span m='2915040'>that</span> <span m='2915140'>produces</span> <span m='2915420'>a</span>
  <span m='2915490'>procedure--</span> <span m='2916840'>which</span> <span m='2917220'>sets</span>
  <span m='2917630'>n</span> <span m='2922820'>to</span> <span m='2923260'>the</span>
  <span m='2923410'>increment</span> <span m='2923880'>of</span> <span m='2924145'>n</span>
  <span m='2927990'>and</span> <span m='2928140'>returns</span> <span m='2928600'>that</span>
  <span m='2928850'>value</span> <span m='2929280'>of</span> <span m='2929630'>n.</span>
  </p><p><span m='2935520'>Now</span> <span m='2935730'>we're going to</span> <span
  m='2935850'>investigate</span> <span m='2936540'>the</span> <span m='2936620'>behavior</span>
  <span m='2936970'>of</span> <span m='2937320'>this.</span> <span m='2937560'>It's</span>
  <span m='2937680'>a sort</span> <span m='2937880'>of</span> <span m='2938000'>interesting</span>
  <span m='2938530'>thing.</span> <span m='2939840'>In</span> <span m='2939970'>order
  to</span> <span m='2940280'>investigate</span> <span m='2940800'>the</span> <span
  m='2940860'>behavior,</span> <span m='2941200'>I</span> <span m='2941540'>have</span>
  <span m='2941700'>to</span> <span m='2941870'>make</span> <span m='2942050'>an</span>
  <span m='2942150'>environment</span> <span m='2942710'>model,</span> <span m='2944180'>because</span>
  <span m='2944340'>we</span> <span m='2944440'>can't</span> <span m='2944660'>understand</span>
  <span m='2945130'>this</span> <span m='2945230'>any</span> <span m='2945430'>other</span>
  <span m='2945610'>way.</span> <span m='2948630'>So</span> <span m='2948800'>let's</span>
  <span m='2948990'>just</span> <span m='2949160'>do</span> <span m='2949330'>that.</span>
  </p><p><span m='2950040'>We</span> <span m='2950240'>start</span> <span m='2950570'>out</span>
  <span m='2951700'>with</span> <span m='2951910'>some</span> <span m='2952150'>sort</span>
  <span m='2952430'>of--</span> <span m='2953005'>let's</span> <span m='2953380'>say</span>
  <span m='2953720'>there is a</span> <span m='2953830'>global</span> <span m='2954280'>environment</span>
  <span m='2954840'>that</span> <span m='2954900'>the</span> <span m='2954970'>machine</span>
  <span m='2955270'>is</span> <span m='2955390'>born</span> <span m='2955650'>with.</span>
  <span m='2956240'>Global</span> <span m='2956515'>we'll</span> <span m='2956790'>call</span>
  <span m='2957050'>it.</span> <span m='2959720'>And</span> <span m='2960170'>it's</span>
  <span m='2960380'>going</span> <span m='2960470'>to</span> <span m='2960550'>have</span>
  <span m='2960860'>in it</span> <span m='2963030'>a</span> <span m='2963150'>bunch</span>
  <span m='2963430'>of</span> <span m='2963520'>initial</span> <span m='2963850'>things.</span>
  <span m='2964530'>We</span> <span m='2964690'>all</span> <span m='2964860'>know</span>
  <span m='2965060'>what it's</span> <span m='2965250'>got.</span> <span m='2965820'>It's</span>
  <span m='2966000'>got</span> <span m='2966210'>things</span> <span m='2966460'>in</span>
  <span m='2966550'>it</span> <span m='2967400'>like</span> <span m='2967830'>say,</span>
  <span m='2968420'>plus,</span> <span m='2969650'>and</span> <span m='2970200'>times,</span>
  <span m='2972310'>and</span> <span m='2972930'>quotient,</span> <span m='2974350'>and</span>
  <span m='2975190'>difference,</span> <span m='2976190'>and</span> <span m='2976740'>CAR,</span>
  <span m='2978590'>and</span> <span m='2979170'>et</span> <span m='2979330'>cetera,</span>
  <span m='2981640'>lots</span> <span m='2981900'>of</span> <span m='2982010'>things.</span>
  <span m='2982960'>I</span> <span m='2983130'>don't</span> <span m='2983260'>know</span>
  <span m='2983360'>what</span> <span m='2983520'>they</span> <span m='2983670'>are,</span>
  <span m='2984350'>some</span> <span m='2984700'>various</span> <span m='2984950'>squiggles</span>
  <span m='2985810'>that</span> <span m='2986160'>are</span> <span m='2987030'>the</span>
  <span m='2987450'>things</span> <span m='2987750'>the</span> <span m='2987860'>machine</span>
  <span m='2988190'>is</span> <span m='2988290'>born</span> <span m='2988610'>with.</span>
  <span m='2991290'>And</span> <span m='2991510'>by</span> <span m='2991670'>doing</span>
  <span m='2992020'>the</span> <span m='2992110'>definition</span> <span m='2992760'>here,</span>
  <span m='2994740'>what</span> <span m='2994870'>I</span> <span m='2994970'>plan</span>
  <span m='2995280'>to</span> <span m='2995360'>do--</span> </p><p><span m='2996350'>Well,</span>
  <span m='2996570'>what</span> <span m='2996670'>am</span> <span m='2996740'>I</span>
  <span m='2996840'>doing?</span> <span m='2997390'>I'm</span> <span m='2997520'>doing</span>
  <span m='2997760'>this</span> <span m='2998080'>relative</span> <span m='2998530'>to</span>
  <span m='2998630'>the</span> <span m='2998730'>global</span> <span m='2999070'>environment.</span>
  <span m='2999780'>So</span> <span m='2999930'>here's</span> <span m='3000180'>my</span>
  <span m='3000380'>environment</span> <span m='3000970'>pointer.</span> <span m='3003580'>In
  order</span> <span m='3004040'>to</span> <span m='3004160'>do</span> <span m='3004320'>that</span>
  <span m='3004490'>I</span> <span m='3004590'>have</span> <span m='3004730'>to</span>
  <span m='3004870'>evaluate</span> <span m='3005480'>this</span> <span m='3005660'>lambda</span>
  <span m='3005980'>expression.</span> <span m='3008270'>That</span> <span m='3008640'>means</span>
  <span m='3008800'>I</span> <span m='3008860'>make</span> <span m='3009050'>a</span>
  <span m='3009120'>procedure</span> <span m='3009570'>object.</span> </p><p><span
  m='3011490'>So</span> <span m='3011670'>I'm going to</span> <span m='3011800'>make</span>
  <span m='3011990'>a</span> <span m='3012050'>procedure</span> <span m='3012500'>object</span>
  <span m='3012870'>here.</span> <span m='3017400'>And</span> <span m='3017530'>the</span>
  <span m='3017650'>procedure</span> <span m='3018050'>object</span> <span m='3018390'>has,</span>
  <span m='3018770'>as</span> <span m='3019040'>the</span> <span m='3019480'>place</span>
  <span m='3019750'>it's</span> <span m='3020020'>defined,</span> <span m='3021290'>the</span>
  <span m='3021430'>global</span> <span m='3021780'>environment.</span> <span m='3023820'>The</span>
  <span m='3024240'>procedure</span> <span m='3024630'>object</span> <span m='3025000'>contains</span>
  <span m='3028140'>some</span> <span m='3028450'>code</span> <span m='3028760'>that</span>
  <span m='3028910'>represents</span> <span m='3029760'>a</span> <span m='3029880'>procedure</span>
  <span m='3030260'>of</span> <span m='3030380'>one</span> <span m='3030500'>argument</span>
  <span m='3030880'>n</span> <span m='3032110'>which</span> <span m='3032300'>returns</span>
  <span m='3032800'>a</span> <span m='3032880'>procedure</span> <span m='3033390'>of</span>
  <span m='3033470'>no</span> <span m='3033670'>arguments</span> <span m='3034400'>which</span>
  <span m='3034630'>does</span> <span m='3034870'>something.</span> <span m='3038320'>And</span>
  <span m='3038730'>the</span> <span m='3038990'>define</span> <span m='3040460'>is</span>
  <span m='3040640'>a</span> <span m='3040780'>way</span> <span m='3041040'>of</span>
  <span m='3041930'>changing</span> <span m='3042440'>this</span> <span m='3042620'>environment,</span>
  <span m='3044290'>so</span> <span m='3044580'>that I</span> <span m='3044690'>now</span>
  <span m='3044950'>add</span> <span m='3045270'>to</span> <span m='3045450'>it</span>
  <span m='3045910'>a</span> <span m='3046010'>make-counter,</span> <span m='3052350'>a</span>
  <span m='3052420'>special</span> <span m='3052930'>rule</span> <span m='3053230'>for</span>
  <span m='3053340'>the</span> <span m='3053440'>special</span> <span m='3053820'>thing</span>
  <span m='3054470'>defined.</span> <span m='3055470'>But</span> <span m='3055930'>what</span>
  <span m='3056270'>that</span> <span m='3056500'>is,</span> <span m='3058720'>is
  it</span> <span m='3059160'>gives</span> <span m='3059390'>me</span> <span m='3059570'>that</span>
  <span m='3059810'>pointer</span> <span m='3061200'>to</span> <span m='3061330'>that</span>
  <span m='3061550'>procedure.</span> <span m='3063840'>So</span> <span m='3064010'>now</span>
  <span m='3064260'>the</span> <span m='3064350'>global</span> <span m='3064690'>environment</span>
  <span m='3065090'>contains</span> <span m='3065410'>make-counter</span> <span m='3065940'>as</span>
  <span m='3066040'>well.</span> </p><p><span m='3069330'>Now,</span> <span m='3069700'>we're
  going to</span> <span m='3070040'>do</span> <span m='3070230'>some</span> <span
  m='3070440'>operations.</span> <span m='3071800'>I'm</span> <span m='3072030'>going</span>
  <span m='3072100'>to</span> <span m='3072170'>use</span> <span m='3072440'>this</span>
  <span m='3072600'>to</span> <span m='3072700'>make</span> <span m='3072900'>some</span>
  <span m='3073040'>counters.</span> <span m='3074596'>We'll</span> <span m='3075090'>see</span>
  <span m='3075400'>what a</span> <span m='3075520'>counter</span> <span m='3076020'>is.</span>
  <span m='3077140'>So</span> <span m='3077300'>let's</span> <span m='3077650'>define</span>
  <span m='3083360'>c1</span> <span m='3084860'>to</span> <span m='3085020'>be</span>
  <span m='3085280'>a</span> <span m='3085380'>counter</span> <span m='3085870'>beginning</span>
  <span m='3086200'>at</span> <span m='3086300'>0.</span> <span m='3095440'>Well,</span>
  <span m='3096180'>we</span> <span m='3096320'>know</span> <span m='3096420'>how</span>
  <span m='3096550'>to</span> <span m='3096610'>do</span> <span m='3096790'>this</span>
  <span m='3097100'>now,</span> <span m='3097460'>according</span> <span m='3097800'>to</span>
  <span m='3097880'>the</span> <span m='3097950'>model.</span> <span m='3099660'>I</span>
  <span m='3099770'>have</span> <span m='3099900'>to</span> <span m='3100080'>evaluate</span>
  <span m='3100560'>the</span> <span m='3100630'>expression</span> <span m='3101210'>make-counter</span>
  <span m='3103090'>in</span> <span m='3103250'>the</span> <span m='3103340'>global</span>
  <span m='3103680'>environment,</span> <span m='3105430'>make-counter</span> <span
  m='3105560'>of</span> <span m='3105920'>0.</span> </p><p><span m='3107900'>Well,</span>
  <span m='3108510'>I</span> <span m='3108640'>look</span> <span m='3108900'>up</span>
  <span m='3109040'>make-counter</span> <span m='3109710'>and</span> <span m='3109920'>see</span>
  <span m='3110190'>that</span> <span m='3110320'>it's</span> <span m='3110440'>a</span>
  <span m='3110500'>procedure.</span> <span m='3113630'>I'm</span> <span m='3113830'>going</span>
  <span m='3113950'>to</span> <span m='3114070'>have</span> <span m='3114190'>to</span>
  <span m='3114270'>apply</span> <span m='3114630'>that</span> <span m='3114830'>procedure.</span>
  <span m='3116010'>The</span> <span m='3116370'>way</span> <span m='3116540'>I</span>
  <span m='3116690'>apply</span> <span m='3117080'>the</span> <span m='3117190'>procedure</span>
  <span m='3118500'>is</span> <span m='3118650'>by</span> <span m='3118800'>constructing</span>
  <span m='3119350'>a</span> <span m='3119400'>frame.</span> <span m='3122400'>So</span>
  <span m='3122570'>I</span> <span m='3122640'>construct</span> <span m='3123120'>a</span>
  <span m='3123170'>frame</span> <span m='3126690'>which</span> <span m='3128310'>has</span>
  <span m='3129110'>a</span> <span m='3129280'>value</span> <span m='3129810'>for</span>
  <span m='3130030'>n</span> <span m='3130140'>in</span> <span m='3130480'>it</span>
  <span m='3131820'>which</span> <span m='3132030'>is</span> <span m='3132170'>0,</span>
  <span m='3134030'>and</span> <span m='3134180'>the</span> <span m='3134330'>parent</span>
  <span m='3134730'>environment</span> <span m='3136030'>is</span> <span m='3136240'>the</span>
  <span m='3136350'>one</span> <span m='3136640'>which</span> <span m='3136850'>is</span>
  <span m='3136990'>the</span> <span m='3137430'>environment</span> <span m='3137910'>of</span>
  <span m='3138000'>definition</span> <span m='3138560'>of</span> <span m='3138640'>make-counter.</span>
  <span m='3143890'>So</span> <span m='3144060'>I've</span> <span m='3144140'>made</span>
  <span m='3144410'>an</span> <span m='3144530'>environment</span> <span m='3145380'>by</span>
  <span m='3146080'>applying</span> <span m='3146910'>make-counter</span> <span m='3147810'>to</span>
  <span m='3147980'>0.</span> </p><p><span m='3151580'>Now,</span> <span m='3151800'>I</span>
  <span m='3151900'>have</span> <span m='3152010'>to</span> <span m='3152100'>evaluate</span>
  <span m='3152610'>the</span> <span m='3152690'>body</span> <span m='3153530'>of</span>
  <span m='3153730'>make-counter,</span> <span m='3154360'>which</span> <span m='3154580'>is</span>
  <span m='3154700'>this</span> <span m='3154910'>lambda</span> <span m='3155240'>expression,</span>
  <span m='3156670'>in</span> <span m='3156880'>that</span> <span m='3157080'>environment.</span>
  <span m='3160730'>Well</span> <span m='3160940'>evaluating</span> <span m='3161550'>this</span>
  <span m='3161740'>body,</span> <span m='3162770'>this</span> <span m='3163010'>body</span>
  <span m='3163310'>is</span> <span m='3163400'>a</span> <span m='3163460'>lambda</span>
  <span m='3163770'>expression.</span> <span m='3166360'>Evaluate</span> <span m='3166480'>a</span>
  <span m='3166880'>lambda</span> <span m='3167160'>expression</span> <span m='3167550'>means</span>
  <span m='3167750'>make a</span> <span m='3167980'>procedure</span> <span m='3168400'>object.</span>
  <span m='3169570'>So</span> <span m='3169710'>I'm going to</span> <span m='3169830'>make</span>
  <span m='3169970'>a</span> <span m='3170030'>procedure</span> <span m='3170460'>object.</span>
  </p><p><span m='3176840'>And</span> <span m='3176980'>that</span> <span m='3177120'>procedure</span>
  <span m='3177520'>object</span> <span m='3177810'>has</span> <span m='3178170'>the</span>
  <span m='3178550'>environment</span> <span m='3179050'>it was</span> <span m='3179180'>defined</span>
  <span m='3179620'>in</span> <span m='3179780'>being</span> <span m='3180060'>that,</span>
  <span m='3184370'>where</span> <span m='3184490'>n</span> <span m='3184750'>was</span>
  <span m='3184900'>defined</span> <span m='3185250'>to</span> <span m='3185300'>be</span>
  <span m='3185400'>0.</span> <span m='3187656'>And it has</span> <span m='3188110'>some</span>
  <span m='3188320'>code,</span> <span m='3188880'>which</span> <span m='3189090'>is</span>
  <span m='3189250'>the</span> <span m='3190290'>procedure</span> <span m='3190630'>of</span>
  <span m='3190710'>no</span> <span m='3190920'>arguments</span> <span m='3191370'>which</span>
  <span m='3191570'>does</span> <span m='3191820'>something,</span> <span m='3193621'>that</span>
  <span m='3194080'>sets</span> <span m='3194630'>something,</span> <span m='3195450'>and</span>
  <span m='3196060'>returns</span> <span m='3196410'>n.</span> <span m='3197622'>And</span>
  <span m='3198050'>this</span> <span m='3198400'>thing</span> <span m='3199530'>is</span>
  <span m='3199720'>going</span> <span m='3199970'>to</span> <span m='3200080'>be</span>
  <span m='3200440'>the</span> <span m='3200720'>object,</span> <span m='3202310'>which</span>
  <span m='3202510'>in</span> <span m='3202600'>the</span> <span m='3202680'>global</span>
  <span m='3203020'>environment,</span> <span m='3203400'>will</span> <span m='3203480'>have</span>
  <span m='3203610'>the</span> <span m='3203690'>name</span> <span m='3203950'>c1.</span>
  <span m='3206020'>So</span> <span m='3206240'>we</span> <span m='3206340'>construct</span>
  <span m='3206830'>a</span> <span m='3206980'>name</span> <span m='3207280'>here,</span>
  <span m='3207580'>c1,</span> <span m='3208980'>and</span> <span m='3209130'>say</span>
  <span m='3209280'>that</span> <span m='3209540'>equals</span> <span m='3212136'>that.</span>
  </p><p><span m='3215560'>Now,</span> <span m='3215760'>but</span> <span m='3215920'>also</span>
  <span m='3216240'>make</span> <span m='3216440'>another</span> <span m='3216750'>counter,</span>
  <span m='3222960'>c2</span> <span m='3224070'>to</span> <span m='3224190'>be</span>
  <span m='3224350'>make-counter</span> <span m='3230790'>say,</span> <span m='3231060'>starting</span>
  <span m='3231360'>with</span> <span m='3231570'>10.</span> <span m='3233868'>Then</span>
  <span m='3234310'>I</span> <span m='3234500'>do</span> <span m='3234680'>essentially</span>
  <span m='3235110'>the</span> <span m='3235210'>same</span> <span m='3235530'>thing.</span>
  <span m='3237270'>I</span> <span m='3237350'>apply</span> <span m='3237760'>the</span>
  <span m='3237820'>make-counter</span> <span m='3238350'>procedure,</span> <span
  m='3239310'>which</span> <span m='3239480'>I</span> <span m='3239550'>got</span>
  <span m='3239760'>from</span> <span m='3239910'>here,</span> <span m='3241140'>to</span>
  <span m='3241270'>make</span> <span m='3241430'>another</span> <span m='3241720'>frame</span>
  <span m='3242750'>with</span> <span m='3243080'>n</span> <span m='3243380'>being</span>
  <span m='3243760'>10.</span> <span m='3245690'>That</span> <span m='3246190'>frame</span>
  <span m='3246490'>has</span> <span m='3246710'>the</span> <span m='3246790'>global</span>
  <span m='3247110'>environment</span> <span m='3247690'>as</span> <span m='3247970'>its</span>
  <span m='3248780'>parent.</span> <span m='3250050'>I</span> <span m='3250240'>then</span>
  <span m='3250490'>construct</span> <span m='3250980'>a</span> <span m='3251040'>procedure</span>
  <span m='3253120'>which</span> <span m='3253510'>has</span> <span m='3255290'>that</span>
  <span m='3255770'>as</span> <span m='3256060'>it's</span> <span m='3256450'>frame</span>
  <span m='3256750'>of</span> <span m='3256830'>definition.</span> <span m='3260440'>The</span>
  <span m='3260810'>code</span> <span m='3261140'>of</span> <span m='3261240'>it</span>
  <span m='3261360'>is</span> <span m='3261860'>the</span> <span m='3262150'>procedure</span>
  <span m='3262560'>of</span> <span m='3262660'>no</span> <span m='3262840'>arguments</span>
  <span m='3263240'>which</span> <span m='3263420'>does</span> <span m='3263660'>something.</span>
  <span m='3265390'>And</span> <span m='3265770'>it does</span> <span m='3266110'>a</span>
  <span m='3266160'>set,</span> <span m='3267780'>and</span> <span m='3268000'>so</span>
  <span m='3268220'>on.</span> <span m='3268700'>And</span> <span m='3269010'>n</span>
  <span m='3269390'>comes</span> <span m='3269630'>out.</span> <span m='3271510'>And</span>
  <span m='3271930'>c2</span> <span m='3274102'>is</span> <span m='3274576'>this.</span>
  </p><p><span m='3276950'>Well,</span> <span m='3277140'>you're</span> <span m='3277190'>already</span>
  <span m='3277590'>beginning</span> <span m='3277880'>to</span> <span m='3277960'>see</span>
  <span m='3278140'>something</span> <span m='3278460'>fairly</span> <span m='3278780'>interesting.</span>
  <span m='3280200'>There</span> <span m='3280370'>are</span> <span m='3280580'>two</span>
  <span m='3280850'>n's</span> <span m='3281520'>here.</span> <span m='3282880'>They</span>
  <span m='3283170'>are</span> <span m='3283250'>not</span> <span m='3283560'>one</span>
  <span m='3283790'>n.</span> <span m='3286330'>Each</span> <span m='3286640'>time</span>
  <span m='3287000'>I</span> <span m='3287070'>called</span> <span m='3287350'>make-counter,</span>
  <span m='3288680'>I</span> <span m='3288770'>made</span> <span m='3289020'>another</span>
  <span m='3289310'>instance</span> <span m='3289720'>of</span> <span m='3289810'>n.</span>
  <span m='3292520'>These</span> <span m='3292880'>are</span> <span m='3292930'>distinct</span>
  <span m='3293400'>and</span> <span m='3293510'>separate</span> <span m='3293810'>from</span>
  <span m='3293950'>each</span> <span m='3294120'>other.</span> <span m='3297880'>Now,</span>
  <span m='3298080'>let's</span> <span m='3298300'>do</span> <span m='3298450'>some</span>
  <span m='3298660'>execution,</span> <span m='3299310'>use</span> <span m='3299480'>those</span>
  <span m='3299740'>counters.</span> <span m='3300783'>I'm</span> <span m='3301206'>going</span>
  <span m='3301630'>to</span> <span m='3301870'>use</span> <span m='3302200'>those</span>
  <span m='3302440'>counters.</span> </p><p><span m='3305990'>Well, what</span> <span
  m='3306290'>happens</span> <span m='3307990'>if</span> <span m='3308240'>I</span>
  <span m='3308360'>say,</span> <span m='3311520'>c1</span> <span m='3314430'>at</span>
  <span m='3314590'>this</span> <span m='3314750'>point?</span> <span m='3315900'>Well,</span>
  <span m='3316540'>I</span> <span m='3316650'>go</span> <span m='3316840'>over</span>
  <span m='3316980'>here,</span> <span m='3317690'>and</span> <span m='3317820'>I</span>
  <span m='3317910'>say,</span> <span m='3318310'>oh</span> <span m='3318420'>yes,</span>
  <span m='3318800'>c1</span> <span m='3319220'>is</span> <span m='3319350'>a</span>
  <span m='3319420'>procedure.</span> <span m='3320840'>I'm</span> <span m='3320880'>going</span>
  <span m='3321300'>to call this</span> <span m='3321390'>procedure</span> <span m='3321910'>on</span>
  <span m='3322040'>no</span> <span m='3322230'>arguments,</span> <span m='3323300'>but</span>
  <span m='3323490'>it</span> <span m='3323640'>has</span> <span m='3323780'>no</span>
  <span m='3324270'>parameters.</span> <span m='3325060'>That's</span> <span m='3325270'>right.</span>
  <span m='3327020'>What's</span> <span m='3327240'>its</span> <span m='3327390'>body?</span>
  <span m='3328080'>Well,</span> <span m='3328380'>I</span> <span m='3328570'>have
  to</span> <span m='3328700'>look</span> <span m='3328950'>over</span> <span m='3329180'>here,</span>
  <span m='3329470'>because I didn't</span> <span m='3329930'>write it down.</span>
  <span m='3330130'>It</span> <span m='3330320'>said,</span> <span m='3330910'>set</span>
  <span m='3331260'>n</span> <span m='3331480'>to</span> <span m='3331700'>one</span>
  <span m='3331950'>plus</span> <span m='3332200'>n</span> <span m='3333860'>and</span>
  <span m='3334080'>return</span> <span m='3334460'>n,</span> <span m='3337330'>increment</span>
  <span m='3337800'>n.</span> </p><p><span m='3339050'>Well,</span> <span m='3339370'>the</span>
  <span m='3339560'>n</span> <span m='3339760'>it</span> <span m='3339920'>sees</span>
  <span m='3340910'>is</span> <span m='3341120'>this</span> <span m='3341320'>one.</span>
  <span m='3342970'>So</span> <span m='3343340'>I</span> <span m='3343850'>increment</span>
  <span m='3344100'>that</span> <span m='3344510'>n.</span> <span m='3345490'>That</span>
  <span m='3346080'>becomes</span> <span m='3346450'>one,</span> <span m='3348241'>and</span>
  <span m='3348680'>I</span> <span m='3348880'>return</span> <span m='3349240'>the</span>
  <span m='3349300'>value</span> <span m='3349670'>one.</span> <span m='3353050'>Supposing</span>
  <span m='3353740'>I</span> <span m='3353860'>then</span> <span m='3355710'>called</span>
  <span m='3355970'>c2.</span> <span m='3358220'>Well,</span> <span m='3358680'>what</span>
  <span m='3358940'>do</span> <span m='3359260'>I</span> <span m='3359380'>do?</span>
  <span m='3359820'>I</span> <span m='3360160'>say</span> <span m='3360435'>c2</span>
  <span m='3361300'>is</span> <span m='3361430'>this</span> <span m='3361630'>procedure</span>
  <span m='3362050'>which</span> <span m='3362210'>does</span> <span m='3362390'>the</span>
  <span m='3362480'>same</span> <span m='3362760'>thing,</span> <span m='3363420'>but</span>
  <span m='3363600'>here's</span> <span m='3363860'>the</span> <span m='3364050'>n.</span>
  <span m='3365450'>It</span> <span m='3365640'>becomes</span> <span m='3366010'>11.</span>
  <span m='3371140'>And</span> <span m='3371320'>so</span> <span m='3371490'>I</span>
  <span m='3371590'>have</span> <span m='3371700'>an 11</span> <span m='3373880'>which</span>
  <span m='3374040'>is</span> <span m='3374100'>the</span> <span m='3374180'>value.</span>
  <span m='3375980'>I</span> <span m='3376150'>then</span> <span m='3376380'>can</span>
  <span m='3376560'>say,</span> <span m='3377160'>let's</span> <span m='3377290'>try</span>
  <span m='3377490'>c1</span> <span m='3377870'>again.</span> <span m='3381580'>c1</span>
  <span m='3382030'>is</span> <span m='3382170'>this,</span> <span m='3383210'>that's</span>
  <span m='3383650'>two,</span> <span m='3387210'>so</span> <span m='3387360'>the</span>
  <span m='3387490'>answer</span> <span m='3387840'>is</span> <span m='3388090'>two.</span>
  <span m='3389660'>And</span> <span m='3389950'>c2</span> <span m='3393510'>gives</span>
  <span m='3393710'>me</span> <span m='3393830'>a</span> <span m='3393900'>12</span>
  <span m='3394280'>by</span> <span m='3394420'>the</span> <span m='3394530'>same</span>
  <span m='3394810'>method,</span> <span m='3395780'>by</span> <span m='3395900'>walking</span>
  <span m='3396310'>down</span> <span m='3396560'>here</span> <span m='3396780'>looking</span>
  <span m='3397100'>at</span> <span m='3397190'>that</span> <span m='3397700'>and</span>
  <span m='3397840'>saying,</span> <span m='3398030'>here's</span> <span m='3398290'>the</span>
  <span m='3398440'>n,</span> <span m='3398590'>I'm</span> <span m='3398730'>incrementing.</span>
  </p><p><span m='3401630'>So</span> <span m='3401830'>what I</span> <span m='3401950'>have</span>
  <span m='3402190'>are</span> <span m='3402430'>computational</span> <span m='3403040'>objects.</span>
  <span m='3404920'>There</span> <span m='3405490'>are</span> <span m='3405580'>two</span>
  <span m='3406190'>counters,</span> <span m='3409110'>each</span> <span m='3409280'>with</span>
  <span m='3409430'>its</span> <span m='3409560'>own</span> <span m='3409780'>independent</span>
  <span m='3410280'>local</span> <span m='3410580'>state.</span> <span m='3415540'>Let's</span>
  <span m='3415780'>talk</span> <span m='3415990'>about</span> <span m='3416230'>this
  a</span> <span m='3416380'>little.</span> <span m='3416650'>This</span> <span m='3416820'>is</span>
  <span m='3417650'>a</span> <span m='3417740'>strange</span> <span m='3418200'>thing.</span>
  <span m='3421270'>What's</span> <span m='3421470'>an</span> <span m='3421580'>object?</span>
  <span m='3424140'>It's</span> <span m='3424290'>not</span> <span m='3424490'>at
  all</span> <span m='3424710'>obvious</span> <span m='3425150'>what</span> <span
  m='3425280'>an</span> <span m='3425390'>object</span> <span m='3425830'>is.</span>
  <span m='3427560'>We</span> <span m='3427800'>like</span> <span m='3428020'>to</span>
  <span m='3428120'>think</span> <span m='3428390'>about</span> <span m='3428670'>objects,</span>
  <span m='3430950'>because</span> <span m='3431580'>it's</span> <span m='3431720'>economical</span>
  <span m='3432510'>to</span> <span m='3432620'>think</span> <span m='3432840'>that</span>
  <span m='3433050'>way.</span> <span m='3434800'>It's</span> <span m='3434960'>an</span>
  <span m='3435040'>intellectual</span> <span m='3436800'>economy.</span> <span m='3438670'>I</span>
  <span m='3438870'>am</span> <span m='3439020'>an</span> <span m='3439090'>object.</span>
  <span m='3441120'>You</span> <span m='3441490'>are</span> <span m='3441660'>an</span>
  <span m='3441730'>object.</span> <span m='3443610'>We</span> <span m='3443820'>are</span>
  <span m='3443960'>not</span> <span m='3444240'>the</span> <span m='3444340'>same</span>
  <span m='3444730'>object.</span> </p><p><span m='3447600'>I</span> <span m='3447770'>can</span>
  <span m='3447930'>divide</span> <span m='3448310'>the</span> <span m='3448520'>world</span>
  <span m='3448730'>into</span> <span m='3448900'>two</span> <span m='3449040'>parts,</span>
  <span m='3450120'>me</span> <span m='3451070'>and</span> <span m='3451380'>you,</span>
  <span m='3452180'>and there's</span> <span m='3452450'>other</span> <span m='3452620'>things</span>
  <span m='3452850'>as</span> <span m='3452940'>well,</span> <span m='3454690'>such</span>
  <span m='3455050'>that</span> <span m='3455600'>most</span> <span m='3456050'>of</span>
  <span m='3456130'>the</span> <span m='3456230'>things</span> <span m='3456500'>I</span>
  <span m='3456600'>might</span> <span m='3456840'>want</span> <span m='3457060'>to</span>
  <span m='3457130'>discuss</span> <span m='3457720'>about</span> <span m='3458540'>my</span>
  <span m='3458840'>workings</span> <span m='3459770'>do</span> <span m='3459900'>not</span>
  <span m='3460070'>involve</span> <span m='3460500'>you,</span> <span m='3461410'>and</span>
  <span m='3461590'>most</span> <span m='3461840'>of</span> <span m='3461890'>the</span>
  <span m='3461930'>things</span> <span m='3462330'>I</span> <span m='3462510'>want</span>
  <span m='3462600'>to</span> <span m='3462690'>discuss</span> <span m='3463030'>about</span>
  <span m='3463210'>your</span> <span m='3463420'>workings</span> <span m='3463790'>don't</span>
  <span m='3463970'>involve</span> <span m='3464340'>me.</span> <span m='3465750'>I</span>
  <span m='3465930'>have</span> <span m='3466070'>a</span> <span m='3466130'>blood</span>
  <span m='3466430'>pressure,</span> <span m='3467570'>a</span> <span m='3467710'>temperature,</span>
  <span m='3470060'>a</span> <span m='3470360'>respiration</span> <span m='3470990'>rate,</span>
  <span m='3473350'>a</span> <span m='3473440'>certain</span> <span m='3473680'>amount</span>
  <span m='3473880'>of</span> <span m='3473930'>sugar</span> <span m='3474200'>in</span>
  <span m='3474260'>my</span> <span m='3474410'>blood,</span> <span m='3476270'>and</span>
  <span m='3476900'>numerous,</span> <span m='3477400'>thousands,</span> <span m='3477890'>of</span>
  <span m='3477960'>state</span> <span m='3478270'>variables--</span> <span m='3478610'>millions</span>
  <span m='3479070'>actually,</span> <span m='3479400'>or</span> <span m='3479850'>I</span>
  <span m='3480090'>don't know</span> <span m='3480290'>how many--</span> <span m='3481030'>huge</span>
  <span m='3481350'>numbers</span> <span m='3481640'>of</span> <span m='3481740'>state</span>
  <span m='3482130'>variables</span> <span m='3482510'>in</span> <span m='3482590'>the</span>
  <span m='3482670'>physical</span> <span m='3483040'>sense</span> <span m='3485020'>which</span>
  <span m='3485190'>represent</span> <span m='3485870'>the</span> <span m='3485950'>state</span>
  <span m='3486190'>of</span> <span m='3486270'>me</span> <span m='3486470'>as</span>
  <span m='3486560'>a</span> <span m='3486610'>particle,</span> <span m='3488910'>and</span>
  <span m='3489240'>you</span> <span m='3489450'>have</span> <span m='3489610'>gazillions</span>
  <span m='3490060'>of</span> <span m='3490130'>them</span> <span m='3490250'>as</span>
  <span m='3490340'>well.</span> </p><p><span m='3492770'>And</span> <span m='3492960'>most</span>
  <span m='3493220'>of</span> <span m='3493260'>mine</span> <span m='3493600'>are</span>
  <span m='3493730'>uncoupled</span> <span m='3494060'>to</span> <span m='3494140'>most</span>
  <span m='3494300'>of</span> <span m='3494470'>yours.</span> <span m='3497290'>So</span>
  <span m='3497490'>we</span> <span m='3497590'>can</span> <span m='3497750'>compute</span>
  <span m='3498170'>the</span> <span m='3498260'>properties</span> <span m='3498840'>of</span>
  <span m='3499050'>me</span> <span m='3500630'>without</span> <span m='3501000'>worrying</span>
  <span m='3501340'>too</span> <span m='3501440'>much</span> <span m='3501640'>about</span>
  <span m='3501780'>the</span> <span m='3501920'>properties</span> <span m='3502370'>of</span>
  <span m='3502460'>you.</span> <span m='3503940'>If</span> <span m='3504030'>we</span>
  <span m='3504140'>had</span> <span m='3504290'>to</span> <span m='3504360'>work</span>
  <span m='3504540'>about</span> <span m='3504780'>both</span> <span m='3504970'>of</span>
  <span m='3505060'>us</span> <span m='3505190'>together,</span> <span m='3506020'>than</span>
  <span m='3506220'>the</span> <span m='3506310'>number</span> <span m='3506610'>of</span>
  <span m='3506670'>states</span> <span m='3507060'>that</span> <span m='3507140'>we</span>
  <span m='3507240'>have</span> <span m='3507350'>to</span> <span m='3507460'>consider</span>
  <span m='3507820'>is</span> <span m='3507910'>the</span> <span m='3508000'>product</span>
  <span m='3508380'>of</span> <span m='3508460'>the number of</span> <span m='3508740'>states</span>
  <span m='3508970'>you</span> <span m='3509070'>have</span> <span m='3509180'>and
  the</span> <span m='3509230'>number of</span> <span m='3509440'>states</span> <span
  m='3509650'>I</span> <span m='3509840'>have.</span> <span m='3510540'>But</span>
  <span m='3510820'>this</span> <span m='3510970'>way</span> <span m='3511120'>it's</span>
  <span m='3511270'>almost</span> <span m='3511650'>a</span> <span m='3511690'>sum.</span>
  </p><p><span m='3512760'>Now,</span> <span m='3512960'>indeed</span> <span m='3513280'>there</span>
  <span m='3513430'>are</span> <span m='3513480'>forces</span> <span m='3514290'>that</span>
  <span m='3514780'>couple</span> <span m='3515090'>us.</span> <span m='3516110'>I'm</span>
  <span m='3516310'>talking</span> <span m='3516690'>to</span> <span m='3516770'>you</span>
  <span m='3516930'>and</span> <span m='3517010'>your</span> <span m='3517170'>state</span>
  <span m='3517420'>changes.</span> <span m='3518420'>I'm</span> <span m='3518640'>looking</span>
  <span m='3518960'>at you</span> <span m='3519100'>and</span> <span m='3519180'>my</span>
  <span m='3519360'>state</span> <span m='3519630'>changes.</span> <span m='3521680'>Some</span>
  <span m='3522070'>of</span> <span m='3522140'>my</span> <span m='3522300'>state</span>
  <span m='3522580'>variables,</span> <span m='3523000'>a</span> <span m='3523080'>very</span>
  <span m='3523290'>few</span> <span m='3523500'>of</span> <span m='3523700'>them,</span>
  <span m='3524370'>therefore,</span> <span m='3525010'>are</span> <span m='3525240'>coupled</span>
  <span m='3525550'>to</span> <span m='3525640'>yours.</span> <span m='3526190'>If</span>
  <span m='3526300'>you</span> <span m='3526420'>were</span> <span m='3526490'>to</span>
  <span m='3526550'>suddenly</span> <span m='3526880'>yell</span> <span m='3527180'>very</span>
  <span m='3527400'>loud,</span> <span m='3527860'>my</span> <span m='3528010'>blood</span>
  <span m='3528240'>pressure</span> <span m='3528470'>would</span> <span m='3528610'>go</span>
  <span m='3528780'>up.</span> </p><p><span m='3534320'>However,</span> <span m='3534970'>and</span>
  <span m='3535180'>it</span> <span m='3535250'>may</span> <span m='3535390'>not</span>
  <span m='3535640'>be</span> <span m='3535890'>always</span> <span m='3536270'>appropriate</span>
  <span m='3537270'>to</span> <span m='3537390'>think</span> <span m='3537590'>about</span>
  <span m='3537850'>the</span> <span m='3537920'>world</span> <span m='3538210'>as</span>
  <span m='3538260'>being</span> <span m='3538460'>made</span> <span m='3538580'>out</span>
  <span m='3538740'>of</span> <span m='3538820'>independent</span> <span m='3539580'>states</span>
  <span m='3540220'>and</span> <span m='3540360'>independent</span> <span m='3540690'>particles.</span>
  <span m='3542260'>Lots</span> <span m='3542470'>of the</span> <span m='3542560'>bugs</span>
  <span m='3542900'>that</span> <span m='3542970'>occur</span> <span m='3543030'>in</span>
  <span m='3543280'>things</span> <span m='3543460'>like</span> <span m='3543620'>quantum</span>
  <span m='3543900'>mechanics,</span> <span m='3545350'>or</span> <span m='3545480'>the</span>
  <span m='3545550'>bugs</span> <span m='3545810'>in</span> <span m='3545880'>our</span>
  <span m='3545960'>minds</span> <span m='3546430'>that</span> <span m='3546530'>occur</span>
  <span m='3547000'>when</span> <span m='3547170'>we</span> <span m='3547270'>think</span>
  <span m='3547450'>about</span> <span m='3547660'>things</span> <span m='3547860'>like</span>
  <span m='3548000'>quantum</span> <span m='3548230'>mechanics,</span> <span m='3548900'>are</span>
  <span m='3549110'>due</span> <span m='3549240'>the</span> <span m='3549350'>fact</span>
  <span m='3549630'>that</span> <span m='3549710'>we are</span> <span m='3549840'>trying</span>
  <span m='3550080'>to</span> <span m='3550140'>think</span> <span m='3550340'>about</span>
  <span m='3550610'>things</span> <span m='3551020'>being</span> <span m='3551280'>broken</span>
  <span m='3551640'>up</span> <span m='3551760'>into</span> <span m='3551910'>independent</span>
  <span m='3552470'>pieces,</span> <span m='3553650'>when</span> <span m='3553800'>in</span>
  <span m='3553860'>fact</span> <span m='3554380'>there's</span> <span m='3554840'>more</span>
  <span m='3555130'>coupling</span> <span m='3555880'>than</span> <span m='3556150'>we</span>
  <span m='3556260'>see</span> <span m='3556670'>on</span> <span m='3556790'>the</span>
  <span m='3556860'>surface,</span> <span m='3558110'>or that</span> <span m='3558350'>we</span>
  <span m='3558470'>want</span> <span m='3558720'>to</span> <span m='3558800'>believe</span>
  <span m='3559160'>in,</span> <span m='3559750'>because</span> <span m='3559870'>we</span>
  <span m='3559960'>want</span> <span m='3560070'>to</span> <span m='3560180'>compute</span>
  <span m='3560520'>efficiently</span> <span m='3561030'>and</span> <span m='3561090'>effectively.</span>
  <span m='3562300'>We've</span> <span m='3562480'>been</span> <span m='3562630'>trained</span>
  <span m='3563030'>to</span> <span m='3563090'>think</span> <span m='3563310'>that</span>
  <span m='3563520'>way.</span> </p><p><span m='3569336'>Well,</span> <span m='3569810'>let's</span>
  <span m='3570130'>see.</span> <span m='3571440'>How</span> <span m='3571820'>would</span>
  <span m='3571910'>we</span> <span m='3572010'>know</span> <span m='3572240'>if</span>
  <span m='3572340'>we</span> <span m='3572430'>had</span> <span m='3572600'>objects</span>
  <span m='3573110'>at</span> <span m='3573320'>all?</span> <span m='3575140'>How</span>
  <span m='3575320'>can</span> <span m='3575380'>we</span> <span m='3575520'>tell</span>
  <span m='3576260'>if</span> <span m='3576550'>we</span> <span m='3576690'>have</span>
  <span m='3576830'>objects?</span> <span m='3577690'>Consider</span> <span m='3579830'>some</span>
  <span m='3580020'>possible</span> <span m='3580400'>optical</span> <span m='3580820'>illusions.</span>
  <span m='3581770'>This</span> <span m='3582560'>could</span> <span m='3582700'>be</span>
  <span m='3582830'>done.</span> <span m='3584805'>These</span> <span m='3585270'>pieces</span>
  <span m='3585510'>of</span> <span m='3585610'>chalk</span> <span m='3585920'>are</span>
  <span m='3585980'>not</span> <span m='3586210'>appropriately</span> <span m='3587090'>identical,</span>
  <span m='3587790'>but</span> <span m='3587970'>supposing</span> <span m='3588280'>you</span>
  <span m='3588400'>couldn't</span> <span m='3588640'>tell</span> <span m='3588830'>the</span>
  <span m='3588900'>difference</span> <span m='3589180'>of</span> <span m='3589240'>them</span>
  <span m='3589370'>by</span> <span m='3589520'>looking</span> <span m='3589850'>at</span>
  <span m='3590030'>them.</span> <span m='3592130'>Well,</span> <span m='3592300'>there's</span>
  <span m='3592440'>a</span> <span m='3592480'>possibility</span> <span m='3593340'>that</span>
  <span m='3593540'>this</span> <span m='3593700'>all</span> <span m='3593860'>a</span>
  <span m='3593910'>game</span> <span m='3594180'>I'm</span> <span m='3594290'>playing</span>
  <span m='3594600'>with</span> <span m='3594720'>mirrors.</span> <span m='3595725'>It's</span>
  <span m='3596340'>really</span> <span m='3596560'>the</span> <span m='3596680'>same</span>
  <span m='3596980'>piece</span> <span m='3597150'>of</span> <span m='3597220'>chalk,</span>
  <span m='3599430'>but</span> <span m='3599570'>you're</span> <span m='3599690'>seeing</span>
  <span m='3599980'>two</span> <span m='3600170'>of</span> <span m='3600310'>them.</span>
  <span m='3601660'>How</span> <span m='3601830'>would</span> <span m='3601950'>you</span>
  <span m='3602060'>know</span> <span m='3602760'>if</span> <span m='3602880'>you're</span>
  <span m='3603000'>seeing</span> <span m='3603250'>one</span> <span m='3603420'>or</span>
  <span m='3603520'>two?</span> <span m='3605160'>Well,</span> <span m='3605730'>there's</span>
  <span m='3605900'>only</span> <span m='3606090'>one</span> <span m='3606240'>way</span>
  <span m='3606370'>I</span> <span m='3606510'>know.</span> <span m='3607430'>You</span>
  <span m='3607540'>grab</span> <span m='3607850'>one</span> <span m='3608020'>of</span>
  <span m='3608110'>them</span> <span m='3608250'>and</span> <span m='3608430'>change</span>
  <span m='3608790'>it</span> <span m='3609510'>and</span> <span m='3609670'>see</span>
  <span m='3609800'>if</span> <span m='3609870'>the</span> <span m='3609970'>other</span>
  <span m='3610110'>one</span> <span m='3610280'>changed.</span> <span m='3613580'>And</span>
  <span m='3614050'>it</span> <span m='3614260'>didn't,</span> <span m='3615075'>so</span>
  <span m='3615490'>there's</span> <span m='3615780'>two</span> <span m='3615960'>of</span>
  <span m='3616020'>them.</span> </p><p><span m='3619070'>And,</span> <span m='3619500'>on</span>
  <span m='3619710'>the</span> <span m='3619800'>other</span> <span m='3619890'>hand,</span>
  <span m='3620080'>there</span> <span m='3620300'>is some other</span> <span m='3620520'>screwy</span>
  <span m='3620890'>properties</span> <span m='3621390'>of</span> <span m='3621480'>things</span>
  <span m='3621720'>like</span> <span m='3621940'>that.</span> <span m='3622580'>Like,</span>
  <span m='3622760'>how</span> <span m='3622920'>do</span> <span m='3623000'>we</span>
  <span m='3623080'>know if</span> <span m='3623300'>something</span> <span m='3623630'>changed?</span>
  <span m='3625040'>We</span> <span m='3625280'>have</span> <span m='3625440'>to</span>
  <span m='3625530'>look</span> <span m='3625720'>at</span> <span m='3625910'>it</span>
  <span m='3626340'>before</span> <span m='3626780'>and</span> <span m='3626900'>after</span>
  <span m='3627260'>the</span> <span m='3627380'>change.</span> <span m='3628760'>The</span>
  <span m='3628870'>change</span> <span m='3629150'>is</span> <span m='3629240'>an</span>
  <span m='3629300'>assignment,</span> <span m='3630050'>it's</span> <span m='3630335'>a</span>
  <span m='3630620'>moment</span> <span m='3630950'>in</span> <span m='3631040'>time.</span>
  <span m='3632200'>But</span> <span m='3632410'>that</span> <span m='3632520'>means</span>
  <span m='3632680'>we</span> <span m='3632750'>have to</span> <span m='3632890'>know</span>
  <span m='3633060'>it  was the</span> <span m='3633120'>same</span> <span m='3633390'>one</span>
  <span m='3633870'>that</span> <span m='3634020'>we're</span> <span m='3634120'>looking</span>
  <span m='3634420'>at.</span> <span m='3636540'>So</span> <span m='3636700'>some</span>
  <span m='3636890'>very</span> <span m='3637350'>strange,</span> <span m='3637950'>and</span>
  <span m='3638050'>unusual,</span> <span m='3638580'>and</span> <span m='3638690'>obscure,</span>
  <span m='3638980'>and--</span> <span m='3639270'>I</span> <span m='3639360'>don't</span>
  <span m='3639540'>understand</span> <span m='3640410'>the</span> <span m='3640890'>problems</span>
  <span m='3641460'>associated</span> <span m='3642770'>with</span> <span m='3642950'>assignment,</span>
  <span m='3644670'>and</span> <span m='3644870'>change,</span> <span m='3645540'>and</span>
  <span m='3645720'>objects.</span> <span m='3647380'>These</span> <span m='3647670'>could</span>
  <span m='3647780'>get</span> <span m='3648050'>very,</span> <span m='3648340'>very</span>
  <span m='3648610'>bad.</span> </p><p><span m='3651420'>For</span> <span m='3651630'>example,</span>
  <span m='3653270'>here</span> <span m='3653560'>I</span> <span m='3653680'>am,</span>
  <span m='3653980'>I</span> <span m='3654160'>am</span> <span m='3654290'>a</span>
  <span m='3654360'>particular</span> <span m='3655120'>person,</span> <span m='3655910'>a</span>
  <span m='3656250'>particular</span> <span m='3656460'>object.</span> <span m='3657650'>Now,</span>
  <span m='3658110'>I</span> <span m='3658330'>can</span> <span m='3658480'>take</span>
  <span m='3658690'>out</span> <span m='3658830'>my</span> <span m='3658950'>knife,</span>
  <span m='3660040'>and</span> <span m='3660860'>cut</span> <span m='3661050'>my</span>
  <span m='3661170'>fingernail.</span> <span m='3662430'>A</span> <span m='3662550'>piece</span>
  <span m='3662730'>of</span> <span m='3662790'>my</span> <span m='3662890'>fingernail</span>
  <span m='3663510'>has</span> <span m='3663720'>fallen</span> <span m='3664000'>off</span>
  <span m='3664190'>onto</span> <span m='3664410'>the</span> <span m='3664470'>table.</span>
  <span m='3666030'>I</span> <span m='3666170'>believe</span> <span m='3666470'>I</span>
  <span m='3666580'>am</span> <span m='3666720'>the</span> <span m='3666810'>same</span>
  <span m='3667950'>person</span> <span m='3669090'>I</span> <span m='3669190'>was</span>
  <span m='3669430'>a</span> <span m='3669470'>second</span> <span m='3669840'>ago,</span>
  <span m='3670820'>but</span> <span m='3671100'>I'm</span> <span m='3671200'>not</span>
  <span m='3671390'>physically</span> <span m='3671770'>the</span> <span m='3671850'>same</span>
  <span m='3672090'>in</span> <span m='3672150'>the</span> <span m='3672210'>slightest.</span>
  </p><p><span m='3674490'>I</span> <span m='3674640'>have</span> <span m='3674790'>changed.</span>
  <span m='3675620'>Why</span> <span m='3675890'>am</span> <span m='3676020'>I</span>
  <span m='3676090'>the</span> <span m='3676190'>same?</span> <span m='3678180'>What</span>
  <span m='3678340'>is</span> <span m='3678430'>the</span> <span m='3678550'>identity</span>
  <span m='3679040'>of</span> <span m='3679130'>me?</span> <span m='3681070'>I</span>
  <span m='3681240'>don't</span> <span m='3681400'>know.</span> <span m='3685170'>Except</span>
  <span m='3685500'>for the</span> <span m='3685630'>fact</span> <span m='3685870'>that</span>
  <span m='3686180'>I</span> <span m='3686380'>have</span> <span m='3687060'>some</span>
  <span m='3687190'>sort</span> <span m='3687310'>of</span> <span m='3687420'>identity.</span>
  <span m='3689770'>And</span> <span m='3689890'>so,</span> <span m='3690040'>I</span>
  <span m='3690180'>think</span> <span m='3690310'>by</span> <span m='3690570'>introducing</span>
  <span m='3691030'>assignment</span> <span m='3691630'>and</span> <span m='3692410'>objects,</span>
  <span m='3694580'>we</span> <span m='3694770'>have</span> <span m='3694980'>opened</span>
  <span m='3695300'>ourselves</span> <span m='3695770'>up</span> <span m='3696250'>to</span>
  <span m='3696480'>all</span> <span m='3696740'>the</span> <span m='3696820'>horrible</span>
  <span m='3697220'>questions</span> <span m='3697580'>of</span> <span m='3697670'>philosophy</span>
  <span m='3698470'>that</span> <span m='3698570'>have</span> <span m='3698680'>been</span>
  <span m='3698800'>plaguing</span> <span m='3699190'>philosophers</span> <span m='3700090'>for</span>
  <span m='3700320'>some</span> <span m='3700490'>thousands</span> <span m='3700860'>of</span>
  <span m='3700950'>years</span> <span m='3701350'>about</span> <span m='3701630'>this</span>
  <span m='3701710'>sort</span> <span m='3701850'>of</span> <span m='3701990'>thing.</span>
  <span m='3703510'>It's</span> <span m='3703610'>why</span> <span m='3703970'>mathematics</span>
  <span m='3704340'>is a</span> <span m='3704410'>lot</span> <span m='3704620'>cleaner.</span>
  </p><p><span m='3705880'>Let's</span> <span m='3706130'>look</span> <span m='3706280'>at</span>
  <span m='3706390'>the</span> <span m='3706790'>best</span> <span m='3707120'>things</span>
  <span m='3707390'>I</span> <span m='3707520'>know</span> <span m='3707720'>to</span>
  <span m='3707810'>say</span> <span m='3708830'>about</span> <span m='3709190'>actions</span>
  <span m='3709590'>and</span> <span m='3709680'>identity.</span> <span m='3712500'>We</span>
  <span m='3712750'>say</span> <span m='3712960'>that an</span> <span m='3713170'>action,</span>
  <span m='3713500'>a,</span> <span m='3713680'>had</span> <span m='3713890'>an</span>
  <span m='3713980'>effect</span> <span m='3714320'>on</span> <span m='3714450'>an</span>
  <span m='3714510'>object,</span> <span m='3714970'>x,</span> <span m='3715740'>or</span>
  <span m='3716050'>equivalently,</span> <span m='3716510'>that</span> <span m='3717190'>x</span>
  <span m='3717430'>was</span> <span m='3717580'>changed</span> <span m='3717880'>by</span>
  <span m='3718050'>a,</span> <span m='3718980'>if</span> <span m='3719130'>some</span>
  <span m='3719340'>property,</span> <span m='3719790'>p,</span> <span m='3720000'>which</span>
  <span m='3720140'>was</span> <span m='3720290'>true</span> <span m='3720520'>of
  x</span> <span m='3720810'>before</span> <span m='3721230'>a,</span> <span m='3721610'>became</span>
  <span m='3722410'>false</span> <span m='3722570'>of</span> <span m='3722860'>x</span>
  <span m='3723160'>after</span> <span m='3723550'>a.</span> <span m='3725100'>Let's</span>
  <span m='3725320'>test.</span> <span m='3726770'>It</span> <span m='3726920'>still</span>
  <span m='3727090'>means</span> <span m='3727190'>I have</span> <span m='3727460'>to</span>
  <span m='3727600'>have the</span> <span m='3727750'>x</span> <span m='3728900'>before</span>
  <span m='3729270'>and</span> <span m='3729330'>after.</span> <span m='3730950'>Or,</span>
  <span m='3731190'>the</span> <span m='3731360'>other</span> <span m='3731490'>way</span>
  <span m='3731670'>of</span> <span m='3731750'>saying</span> <span m='3732000'>this</span>
  <span m='3732200'>is,</span> <span m='3733050'>we</span> <span m='3733210'>say</span>
  <span m='3733420'>that</span> <span m='3733540'>two</span> <span m='3733810'>objects</span>
  <span m='3734065'>x and y are</span> <span m='3734320'>the same</span> <span m='3734570'>for
  any</span> <span m='3734740'>action</span> <span m='3735080'>which</span> <span
  m='3735230'>has</span> <span m='3735410'>an</span> <span m='3735460'>effect</span>
  <span m='3735760'>on</span> <span m='3736180'>x</span> <span m='3736650'>has</span>
  <span m='3736830'>the</span> <span m='3736890'>same</span> <span m='3737110'>effect</span>
  <span m='3737390'>on</span> <span m='3737570'>y.</span> </p><p><span m='3739580'>However,</span>
  <span m='3740150'>objects</span> <span m='3740610'>are</span> <span m='3740680'>very</span>
  <span m='3740940'>useful,</span> <span m='3741500'>as</span> <span m='3741630'>I</span>
  <span m='3741700'>said,</span> <span m='3742080'>for</span> <span m='3742230'>intellectual</span>
  <span m='3742690'>economy.</span> <span m='3744650'>One</span> <span m='3744900'>of</span>
  <span m='3744990'>the</span> <span m='3745080'>things</span> <span m='3745310'>that's</span>
  <span m='3745750'>incredibly</span> <span m='3746260'>useful</span> <span m='3746560'>about</span>
  <span m='3746860'>them,</span> <span m='3748350'>is</span> <span m='3748560'>that</span>
  <span m='3748850'>the</span> <span m='3749180'>world</span> <span m='3750840'>is,</span>
  <span m='3751610'>we</span> <span m='3751800'>like</span> <span m='3751980'>to</span>
  <span m='3752050'>think</span> <span m='3752230'>about,</span> <span m='3752580'>made</span>
  <span m='3752760'>out</span> <span m='3752880'>of</span> <span m='3752980'>independent</span>
  <span m='3753360'>objects</span> <span m='3753690'>with</span> <span m='3753820'>independent</span>
  <span m='3754140'>local</span> <span m='3754390'>state.</span> <span m='3755050'>We</span>
  <span m='3755170'>like</span> <span m='3755380'>to</span> <span m='3755460'>think</span>
  <span m='3755670'>that</span> <span m='3755840'>way,</span> <span m='3756110'>although</span>
  <span m='3756340'>it</span> <span m='3756430'>isn't</span> <span m='3756600'>completely</span>
  <span m='3756960'>true.</span> </p><p><span m='3759730'>When</span> <span m='3759910'>we</span>
  <span m='3760030'>want</span> <span m='3760250'>to</span> <span m='3760340'>make</span>
  <span m='3760580'>very</span> <span m='3760800'>complicated</span> <span m='3761320'>programs</span>
  <span m='3762030'>that</span> <span m='3762290'>deal</span> <span m='3762470'>with</span>
  <span m='3762640'>such</span> <span m='3762830'>a</span> <span m='3762880'>world,</span>
  <span m='3764020'>if</span> <span m='3764170'>we</span> <span m='3764260'>want</span>
  <span m='3764500'>those</span> <span m='3764750'>programs</span> <span m='3765210'>to</span>
  <span m='3765300'>be</span> <span m='3765400'>understandable</span> <span m='3765970'>by</span>
  <span m='3766130'>us</span> <span m='3766930'>and</span> <span m='3767100'>also</span>
  <span m='3767380'>to be</span> <span m='3767550'>changeable,</span> <span m='3768740'>so</span>
  <span m='3768930'>that if</span> <span m='3769070'>we</span> <span m='3769160'>change</span>
  <span m='3769420'>the</span> <span m='3769500'>world</span> <span m='3769770'>we</span>
  <span m='3769940'>change the</span> <span m='3770110'>program</span> <span m='3770430'>only</span>
  <span m='3770630'>a</span> <span m='3770690'>little</span> <span m='3770860'>bit,</span>
  <span m='3771390'>then</span> <span m='3771570'>we</span> <span m='3771680'>want</span>
  <span m='3771890'>there</span> <span m='3772000'>to</span> <span m='3772060'>be</span>
  <span m='3772180'>connections,</span> <span m='3772730'>isomorphism,</span> <span
  m='3773810'>between</span> <span m='3774120'>the</span> <span m='3774210'>objects</span>
  <span m='3774560'>in</span> <span m='3774630'>the</span> <span m='3774700'>world</span>
  <span m='3775180'>and</span> <span m='3775300'>the</span> <span m='3775420'>objects</span>
  <span m='3775790'>in</span> <span m='3775910'>our</span> <span m='3776130'>mental</span>
  <span m='3776480'>model.</span> <span m='3778720'>The</span> <span m='3778920'>modularity</span>
  <span m='3779450'>of</span> <span m='3779560'>the</span> <span m='3779620'>world</span>
  <span m='3779950'>can</span> <span m='3780060'>give</span> <span m='3780170'>us
  the</span> <span m='3780280'>modularity</span> <span m='3780880'>in</span> <span
  m='3780960'>our</span> <span m='3781050'>programming.</span> <span m='3782400'>So</span>
  <span m='3782540'>we</span> <span m='3782670'>invent</span> <span m='3782950'>things</span>
  <span m='3783140'>called</span> <span m='3783330'>object-oriented</span> <span m='3784110'>programming</span>
  <span m='3784590'>and</span> <span m='3784670'>things</span> <span m='3784860'>like</span>
  <span m='3785050'>that</span> <span m='3787150'>to</span> <span m='3787250'>provide</span>
  <span m='3787560'>us</span> <span m='3787660'>with</span> <span m='3787720'>that</span>
  <span m='3788080'>power.</span> </p><p><span m='3789950'>But</span> <span m='3790210'>it's</span>
  <span m='3790360'>even</span> <span m='3790590'>easier.</span> <span m='3790990'>Let's</span>
  <span m='3791230'>play</span> <span m='3791430'>a</span> <span m='3791520'>little</span>
  <span m='3791750'>game.</span> <span m='3792310'>I</span> <span m='3792390'>want</span>
  <span m='3792490'>to</span> <span m='3792580'>play</span> <span m='3792730'>a</span>
  <span m='3792790'>little</span> <span m='3792970'>game,</span> <span m='3793370'>show</span>
  <span m='3793600'>you</span> <span m='3793740'>an even</span> <span m='3794120'>easier</span>
  <span m='3795110'>example</span> <span m='3796080'>of</span> <span m='3796310'>where</span>
  <span m='3796930'>modularity</span> <span m='3797690'>can</span> <span m='3797840'>be</span>
  <span m='3797980'>enhanced</span> <span m='3799080'>by</span> <span m='3799210'>using</span>
  <span m='3799550'>an</span> <span m='3799610'>assignment</span> <span m='3800020'>statement,</span>
  <span m='3801010'>judiciously.</span> <span m='3802960'>One</span> <span m='3803150'>thing</span>
  <span m='3803250'>I</span> <span m='3803360'>want</span> <span m='3803570'>to</span>
  <span m='3804020'>enforce</span> <span m='3804540'>and</span> <span m='3804720'>impress</span>
  <span m='3804960'>on</span> <span m='3805110'>you,</span> <span m='3805510'>is</span>
  <span m='3805780'>don't</span> <span m='3806280'>use</span> <span m='3806480'>assignment</span>
  <span m='3806850'>statements</span> <span m='3807180'>the</span> <span m='3807350'>way
  you use</span> <span m='3807590'>it</span> <span m='3807710'>in</span> <span m='3807800'>FORTRAN</span>
  <span m='3808220'>or</span> <span m='3808280'>Basic</span> <span m='3808690'>or</span>
  <span m='3808770'>something</span> <span m='3809080'>or</span> <span m='3809180'>Pascal,</span>
  <span m='3810120'>to</span> <span m='3810250'>do</span> <span m='3810380'>the</span>
  <span m='3810470'>things</span> <span m='3810670'>you</span> <span m='3810750'>don't</span>
  <span m='3810930'>have</span> <span m='3811080'>to</span> <span m='3811230'>do</span>
  <span m='3811420'>with</span> <span m='3811590'>it.</span> <span m='3814200'>It's</span>
  <span m='3814440'>not</span> <span m='3814670'>the</span> <span m='3814760'>right</span>
  <span m='3815010'>way</span> <span m='3815160'>to</span> <span m='3815250'>think</span>
  <span m='3815770'>for</span> <span m='3815910'>most</span> <span m='3816200'>things.</span>
  <span m='3817010'>Sometimes</span> <span m='3817335'>it's</span> <span m='3817660'>essential,</span>
  <span m='3818710'>or</span> <span m='3818810'>maybe</span> <span m='3819080'>it's</span>
  <span m='3819230'>essential.</span> <span m='3819810'>We'll</span> <span m='3819900'>see</span>
  <span m='3820040'>more</span> <span m='3820230'>about</span> <span m='3820510'>that</span>
  <span m='3820800'>too.</span> </p><p><span m='3822320'>OK,</span> <span m='3822620'>let</span>
  <span m='3822760'>me</span> <span m='3822830'>show</span> <span m='3822970'>you</span>
  <span m='3823230'>a</span> <span m='3823350'>fun</span> <span m='3823640'>game</span>
  <span m='3823920'>here.</span> <span m='3827270'>There</span> <span m='3827600'>was</span>
  <span m='3828480'>mathematician</span> <span m='3829760'>by</span> <span m='3829920'>the</span>
  <span m='3830260'>name</span> <span m='3830460'>of</span> <span m='3830720'>Cesaro--</span>
  <span m='3831750'>or</span> <span m='3831970'>Cesaro,</span> <span m='3832290'>Cesaro</span>
  <span m='3832920'>I</span> <span m='3833030'>suppose</span> <span m='3833360'>it</span>
  <span m='3833450'>is--</span> <span m='3834760'>who</span> <span m='3834900'>figured</span>
  <span m='3835210'>out</span> <span m='3835530'>a</span> <span m='3835640'>clever</span>
  <span m='3835920'>way</span> <span m='3836410'>of</span> <span m='3836640'>computing</span>
  <span m='3837090'>pi.</span> <span m='3838450'>It</span> <span m='3838640'>turns</span>
  <span m='3838970'>out</span> <span m='3840000'>that</span> <span m='3842990'>if</span>
  <span m='3843120'>I</span> <span m='3843200'>take</span> <span m='3843400'>to</span>
  <span m='3843560'>random</span> <span m='3843860'>numbers,</span> <span m='3845240'>two</span>
  <span m='3845630'>integers</span> <span m='3846320'>at</span> <span m='3846510'>random,</span>
  <span m='3847740'>and</span> <span m='3848100'>compute</span> <span m='3848430'>the</span>
  <span m='3848540'>greatest</span> <span m='3848790'>common</span> <span m='3849000'>divisor,</span>
  <span m='3850980'>their</span> <span m='3851110'>greatest</span> <span m='3851390'>common</span>
  <span m='3851550'>divisor</span> <span m='3851880'>is</span> <span m='3852060'>either</span>
  <span m='3852250'>one</span> <span m='3852500'>or</span> <span m='3852590'>it's</span>
  <span m='3852720'>not</span> <span m='3852960'>one.</span> <span m='3853920'>If
  it's</span> <span m='3854130'>one,</span> <span m='3854330'>then</span> <span m='3854440'>they</span>
  <span m='3854580'>have</span> <span m='3854750'>no</span> <span m='3854880'>common</span>
  <span m='3855140'>divisors.</span> <span m='3858240'>If</span> <span m='3858420'>their</span>
  <span m='3859050'>greatest</span> <span m='3859140'>common</span> <span m='3859670'>divisor</span>
  <span m='3860050'>is</span> <span m='3860140'>one--</span> <span m='3861060'>the</span>
  <span m='3861270'>probability</span> <span m='3862050'>that</span> <span m='3862240'>two</span>
  <span m='3862390'>random</span> <span m='3862650'>numbers,</span> <span m='3863150'>two</span>
  <span m='3863280'>numbers</span> <span m='3863590'>chosen</span> <span m='3863890'>at</span>
  <span m='3863960'>random,</span> <span m='3864870'>has</span> <span m='3865100'>as
  greatest</span> <span m='3865510'>common</span> <span m='3865570'>divisor</span>
  <span m='3865930'>one</span> <span m='3866750'>is</span> <span m='3866910'>related</span>
  <span m='3867290'>to</span> <span m='3867370'>pi.</span> </p><p><span m='3869580'>In</span>
  <span m='3869750'>fact--</span> <span m='3871310'>yes,</span> <span m='3871590'>it's</span>
  <span m='3871720'>very</span> <span m='3871900'>strange--</span> <span m='3873070'>of</span>
  <span m='3873240'>course</span> <span m='3873400'>there</span> <span m='3873550'>are</span>
  <span m='3873590'>other</span> <span m='3873710'>ways</span> <span m='3873890'>of</span>
  <span m='3873930'>computing</span> <span m='3874240'>pi, like</span> <span m='3874600'>dropping</span>
  <span m='3874980'>pins</span> <span m='3875300'>on</span> <span m='3875830'>flags,</span>
  <span m='3876840'>and</span> <span m='3876990'>things</span> <span m='3877140'>like</span>
  <span m='3877310'>that,</span> <span m='3877570'>and  sort</span> <span m='3877680'>of</span>
  <span m='3877780'>the</span> <span m='3877840'>same</span> <span m='3878100'>kind</span>
  <span m='3878300'>of</span> <span m='3878400'>thing.</span> <span m='3880110'>So</span>
  <span m='3880280'>the</span> <span m='3880390'>probability</span> <span m='3882160'>of</span>
  <span m='3883150'>that</span> <span m='3883540'>the</span> <span m='3883640'>GCD</span>
  <span m='3885910'>of</span> <span m='3886650'>number</span> <span m='3887020'>one</span>
  <span m='3887870'>and</span> <span m='3888150'>number</span> <span m='3888510'>two,</span>
  <span m='3889350'>two</span> <span m='3889670'>random</span> <span m='3889950'>numbers</span>
  <span m='3890490'>chosen,</span> <span m='3891760'>is</span> <span m='3892210'>6</span>
  <span m='3892640'>over</span> <span m='3892800'>pi</span> <span m='3893190'>squared.</span>
  <span m='3895660'>I'm</span> <span m='3895790'>not</span> <span m='3895940'>going</span>
  <span m='3896000'>to</span> <span m='3896060'>try</span> <span m='3896210'>to</span>
  <span m='3896270'>prove</span> <span m='3896520'>that.</span> <span m='3897240'>It's</span>
  <span m='3897370'>actually</span> <span m='3897610'>not</span> <span m='3897780'>too</span>
  <span m='3897900'>hard</span> <span m='3898940'>and</span> <span m='3899070'>sort
  of</span> <span m='3899240'>fun.</span> </p><p><span m='3901120'>How</span> <span
  m='3901480'>would we</span> <span m='3901670'>estimate</span> <span m='3902160'>such</span>
  <span m='3902350'>probability?</span> <span m='3903590'>Well,</span> <span m='3903730'>the</span>
  <span m='3903780'>way</span> <span m='3903940'>we</span> <span m='3904090'>do</span>
  <span m='3904260'>that,</span> <span m='3904660'>the</span> <span m='3904990'>way</span>
  <span m='3905160'>we</span> <span m='3905250'>estimate</span> <span m='3905630'>probabilities,</span>
  <span m='3907340'>is</span> <span m='3907500'>by</span> <span m='3907630'>doing</span>
  <span m='3907810'>lots</span> <span m='3908020'>of</span> <span m='3908070'>experiments,</span>
  <span m='3909300'>and</span> <span m='3909460'>then</span> <span m='3909620'>computing</span>
  <span m='3910000'>the</span> <span m='3910100'>ratios</span> <span m='3910660'>of
  the</span> <span m='3910760'>ones</span> <span m='3910990'>that</span> <span m='3911080'>come</span>
  <span m='3911260'>out</span> <span m='3911450'>one</span> <span m='3911620'>way</span>
  <span m='3911890'>to</span> <span m='3912260'>the</span> <span m='3912340'>total</span>
  <span m='3912540'>number of</span> <span m='3912850'>experiments</span> <span m='3913160'>we</span>
  <span m='3913270'>do.</span> <span m='3916320'>It's</span> <span m='3916420'>called</span>
  <span m='3916620'>Monte</span> <span m='3916870'>Carlo,</span> <span m='3917720'>and</span>
  <span m='3918150'>it's</span> <span m='3918350'>useful</span> <span m='3918730'>in</span>
  <span m='3919020'>other</span> <span m='3919230'>contexts</span> <span m='3919680'>for</span>
  <span m='3919780'>doing</span> <span m='3919990'>things</span> <span m='3920180'>like</span>
  <span m='3920340'>integrals</span> <span m='3920730'>where</span> <span m='3920830'>you</span>
  <span m='3920900'>have</span> <span m='3921060'>lots</span> <span m='3921280'>and</span>
  <span m='3921340'>lots</span> <span m='3921540'>of</span> <span m='3921600'>variables--</span>
  <span m='3922960'>the</span> <span m='3923080'>space</span> <span m='3923440'>which</span>
  <span m='3923570'>is</span> <span m='3923870'>limiting</span> <span m='3924010'>the</span>
  <span m='3924110'>dimensions</span> <span m='3924410'>you</span> <span m='3924560'>are</span>
  <span m='3924650'>doing</span> <span m='3924780'>you</span> <span m='3924900'>integral</span>
  <span m='3925250'>in.</span> </p><p><span m='3926360'>But</span> <span m='3927650'>going</span>
  <span m='3927940'>back</span> <span m='3928190'>to</span> <span m='3928290'>here,</span>
  <span m='3930710'>Let's</span> <span m='3930890'>look</span> <span m='3931060'>at</span>
  <span m='3931190'>this</span> <span m='3931320'>slide,</span> <span m='3934070'>We</span>
  <span m='3934200'>can</span> <span m='3934320'>use</span> <span m='3934680'>Cesaro's</span>
  <span m='3935100'>method</span> <span m='3935780'>for</span> <span m='3935930'>estimating</span>
  <span m='3936420'>pi</span> <span m='3937390'>with</span> <span m='3938410'>n</span>
  <span m='3938650'>trials</span> <span m='3939880'>by</span> <span m='3940130'>taking</span>
  <span m='3940370'>the</span> <span m='3940520'>square</span> <span m='3940950'>root</span>
  <span m='3941050'>of six</span> <span m='3941360'>over</span> <span m='3941830'>a</span>
  <span m='3942050'>Monte</span> <span m='3942340'>Carlo,</span> <span m='3943370'>a</span>
  <span m='3943490'>Monte</span> <span m='3943850'>Carlo</span> <span m='3945850'>experiment</span>
  <span m='3946840'>with</span> <span m='3947090'>n</span> <span m='3947770'>trials,</span>
  <span m='3948880'>using</span> <span m='3949240'>Cesaro's</span> <span m='3949880'>experiment,</span>
  <span m='3951410'>where</span> <span m='3951880'>Cesaro's</span> <span m='3952190'>experiment</span>
  <span m='3954150'>is</span> <span m='3954400'>the</span> <span m='3954470'>test</span>
  <span m='3954850'>of</span> <span m='3955000'>whether</span> <span m='3955240'>the</span>
  <span m='3955380'>GCD</span> <span m='3956300'>of</span> <span m='3956550'>two</span>
  <span m='3956720'>random</span> <span m='3957040'>numbers--</span> <span m='3959070'>And</span>
  <span m='3959170'>you</span> <span m='3959270'>can</span> <span m='3959390'>see</span>
  <span m='3959630'>that</span> <span m='3959760'>I've</span> <span m='3959970'>already</span>
  <span m='3960200'>got</span> <span m='3960450'>some</span> <span m='3960630'>assignments</span>
  <span m='3961200'>in</span> <span m='3961310'>here,</span> <span m='3961880'>just</span>
  <span m='3962210'>by</span> <span m='3962350'>what</span> <span m='3962630'>I</span>
  <span m='3962820'>wrote.</span> <span m='3963990'>The</span> <span m='3964270'>fact</span>
  <span m='3964530'>that</span> <span m='3964800'>this</span> <span m='3964980'>word</span>
  <span m='3965350'>rand,</span> <span m='3966620'>in</span> <span m='3966760'>parentheses,</span>
  <span m='3967470'>therefore,</span> <span m='3967930'>that</span> <span m='3968150'>procedure</span>
  <span m='3968550'>call,</span> <span m='3969230'>yields</span> <span m='3969500'>a</span>
  <span m='3969560'>different</span> <span m='3969870'>value</span> <span m='3970530'>than</span>
  <span m='3970750'>this</span> <span m='3970940'>one,</span> <span m='3971530'>at</span>
  <span m='3971640'>least</span> <span m='3971830'>that's</span> <span m='3972140'>what</span>
  <span m='3972220'>I'm</span> <span m='3972310'>assuming</span> <span m='3972630'>by</span>
  <span m='3972730'>writing</span> <span m='3973010'>this</span> <span m='3973180'>this</span>
  <span m='3973330'>way,</span> <span m='3974680'>indicates</span> <span m='3975460'>that</span>
  <span m='3975840'>this</span> <span m='3976010'>is</span> <span m='3976120'>not</span>
  <span m='3976300'>a</span> <span m='3976340'>function,</span> <span m='3978240'>that</span>
  <span m='3978390'>there's</span> <span m='3978590'>internal</span> <span m='3978930'>state</span>
  <span m='3979270'>in</span> <span m='3979360'>it</span> <span m='3979710'>which</span>
  <span m='3979860'>is</span> <span m='3979960'>changing.</span> <span m='3985110'>If</span>
  <span m='3985450'>the</span> <span m='3985660'>GCD</span> <span m='3986130'>of</span>
  <span m='3986300'>those</span> <span m='3986480'>two</span> <span m='3986590'>random</span>
  <span m='3986840'>numbers</span> <span m='3987550'>is</span> <span m='3987730'>equal</span>
  <span m='3988020'>to</span> <span m='3988150'>one,</span> <span m='3988530'>that's</span>
  <span m='3989010'>the</span> <span m='3989110'>experiment.</span> </p><p><span m='3991530'>So</span>
  <span m='3991730'>here</span> <span m='3991940'>I</span> <span m='3992000'>have</span>
  <span m='3992430'>an</span> <span m='3992560'>experimental</span> <span m='3993200'>method</span>
  <span m='3993570'>for</span> <span m='3993720'>estimating</span> <span m='3994260'>the</span>
  <span m='3994330'>value</span> <span m='3994700'>of</span> <span m='3995080'>pi.</span>
  <span m='3996560'>Where,</span> <span m='3997080'>I</span> <span m='3997300'>can</span>
  <span m='3997480'>easily</span> <span m='3997940'>divide</span> <span m='3998320'>this</span>
  <span m='3998480'>problem</span> <span m='3998790'>into</span> <span m='3998970'>two</span>
  <span m='3999140'>parts.</span> <span m='4000160'>One</span> <span m='4000570'>is</span>
  <span m='4000810'>the</span> <span m='4000920'>specific</span> <span m='4002120'>Monte</span>
  <span m='4002380'>Carlo</span> <span m='4002670'>experiment</span> <span m='4003070'>of</span>
  <span m='4003250'>Cesaro,</span> <span m='4003610'>which</span> <span m='4003930'>you</span>
  <span m='4004040'>just</span> <span m='4004270'>saw,</span> <span m='4005040'>and</span>
  <span m='4005160'>the</span> <span m='4005290'>other</span> <span m='4005480'>is</span>
  <span m='4005550'>the</span> <span m='4005660'>general</span> <span m='4006110'>technique</span>
  <span m='4006700'>of</span> <span m='4006880'>doing</span> <span m='4007240'>Monte</span>
  <span m='4007500'>Carlo</span> <span m='4007820'>experiments.</span> <span m='4009320'>And</span>
  <span m='4009460'>that's</span> <span m='4009600'>what</span> <span m='4009710'>this</span>
  <span m='4009900'>is.</span> </p><p><span m='4011190'>If</span> <span m='4011380'>I</span>
  <span m='4011470'>want</span> <span m='4011760'>to</span> <span m='4012210'>do</span>
  <span m='4012470'>Monte</span> <span m='4012790'>Carlo</span> <span m='4013110'>experiments</span>
  <span m='4014340'>with</span> <span m='4014620'>n</span> <span m='4014850'>trials,</span>
  <span m='4015860'>a</span> <span m='4015930'>certain</span> <span m='4016140'>number</span>
  <span m='4016320'>of</span> <span m='4016390'>trials,</span> <span m='4017080'>and</span>
  <span m='4017220'>a</span> <span m='4017270'>particular</span> <span m='4017720'>experiment,</span>
  <span m='4019390'>the</span> <span m='4019590'>way</span> <span m='4019710'>I</span>
  <span m='4019830'>do</span> <span m='4020040'>that</span> <span m='4020930'>is</span>
  <span m='4021100'>I</span> <span m='4021190'>make</span> <span m='4021400'>a</span>
  <span m='4021450'>little</span> <span m='4021720'>iterative</span> <span m='4022050'>procedure</span>
  <span m='4023460'>which</span> <span m='4023750'>has</span> <span m='4024180'>variable</span>
  <span m='4024600'>the</span> <span m='4024690'>number</span> <span m='4024910'>of</span>
  <span m='4024970'>trials</span> <span m='4025240'>remaining</span> <span m='4025750'>and</span>
  <span m='4025860'>the</span> <span m='4025960'>number</span> <span m='4026210'>trials</span>
  <span m='4026540'>that</span> <span m='4026620'>have</span> <span m='4026720'>been</span>
  <span m='4026830'>passed,</span> <span m='4028080'>that</span> <span m='4028440'>I've</span>
  <span m='4028660'>gotten</span> <span m='4028890'>true.</span> <span m='4030230'>And</span>
  <span m='4030790'>if</span> <span m='4031010'>the</span> <span m='4031090'>number</span>
  <span m='4031290'>remaining</span> <span m='4031690'>is</span> <span m='4031790'>0,</span>
  <span m='4032200'>then</span> <span m='4032440'>the</span> <span m='4032570'>answer</span>
  <span m='4032850'>is</span> <span m='4032930'>the</span> <span m='4033010'>number</span>
  <span m='4033320'>past</span> <span m='4033700'>divided</span> <span m='4034170'>by</span>
  <span m='4034300'>this</span> <span m='4034460'>whole</span> <span m='4034620'>number</span>
  <span m='4034820'>of</span> <span m='4034880'>trials,</span> <span m='4036070'>was</span>
  <span m='4036260'>the</span> <span m='4036350'>estimate</span> <span m='4036650'>of</span>
  <span m='4036700'>the</span> <span m='4036760'>probability.</span> <span m='4039150'>And</span>
  <span m='4039430'>if</span> <span m='4039560'>it's</span> <span m='4039740'>not,</span>
  <span m='4040120'>if</span> <span m='4040850'>I</span> <span m='4040950'>have</span>
  <span m='4041050'>more</span> <span m='4041240'>trials</span> <span m='4041560'>to</span>
  <span m='4041650'>do,</span> <span m='4042140'>then</span> <span m='4042300'>let's</span>
  <span m='4042520'>do</span> <span m='4042660'>one.</span> </p><p><span m='4042870'>We</span>
  <span m='4042970'>do</span> <span m='4043160'>an</span> <span m='4043230'>experiment.</span>
  <span m='4043860'>We</span> <span m='4044020'>call</span> <span m='4044540'>the</span>
  <span m='4044870'>procedure</span> <span m='4045750'>which</span> <span m='4045970'>is</span>
  <span m='4046070'>experiment</span> <span m='4046540'>on</span> <span m='4046710'>no</span>
  <span m='4046910'>arguments.</span> <span m='4047350'>We</span> <span m='4047450'>do</span>
  <span m='4047630'>the</span> <span m='4047740'>experiment</span> <span m='4049200'>and</span>
  <span m='4049370'>then,</span> <span m='4049500'>if</span> <span m='4049580'>that</span>
  <span m='4049760'>turned</span> <span m='4049930'>out</span> <span m='4050060'>to</span>
  <span m='4050100'>be</span> <span m='4050220'>true,</span> <span m='4050870'>we</span>
  <span m='4051440'>go</span> <span m='4051600'>around</span> <span m='4051870'>the</span>
  <span m='4051950'>loop</span> <span m='4052830'>decrementing</span> <span m='4053390'>the</span>
  <span m='4053470'>number</span> <span m='4053720'>of</span> <span m='4053830'>experiments</span>
  <span m='4054190'>we</span> <span m='4054290'>have</span> <span m='4054410'>to</span>
  <span m='4054490'>do</span> <span m='4054810'>by</span> <span m='4054960'>one</span>
  <span m='4055620'>and</span> <span m='4055890'>incrementing</span> <span m='4056230'>the</span>
  <span m='4056560'>number</span> <span m='4056780'>that</span> <span m='4056900'>were</span>
  <span m='4056990'>passed.</span> </p><p><span m='4058650'>And</span> <span m='4058940'>if</span>
  <span m='4059080'>the</span> <span m='4059330'>experiment</span> <span m='4059450'>was</span>
  <span m='4059560'>false,</span> <span m='4060550'>we</span> <span m='4060690'>just</span>
  <span m='4061410'>go</span> <span m='4061560'>around</span> <span m='4061720'>the</span>
  <span m='4061880'>loop</span> <span m='4062400'>decrementing</span> <span m='4062980'>the</span>
  <span m='4063060'>number</span> <span m='4063390'>of</span> <span m='4063570'>experiments</span>
  <span m='4063660'>remaining</span> <span m='4064530'>and</span> <span m='4064700'>keeping
  the</span> <span m='4064990'>number</span> <span m='4065250'>passed</span> <span
  m='4066030'>the</span> <span m='4066170'>same.</span> <span m='4068910'>We</span>
  <span m='4069030'>start</span> <span m='4069360'>this</span> <span m='4069540'>up</span>
  <span m='4070070'>iterating</span> <span m='4070240'>over</span> <span m='4070730'>the</span>
  <span m='4070810'>total</span> <span m='4071030'>number</span> <span m='4071250'>of</span>
  <span m='4071320'>trials</span> <span m='4073070'>with</span> <span m='4073190'>0</span>
  <span m='4073540'>experiments</span> <span m='4074110'>past.</span> <span m='4075420'>A</span>
  <span m='4075600'>very</span> <span m='4075840'>elegant</span> <span m='4076260'>little</span>
  <span m='4076460'>program.</span> <span m='4077730'>And</span> <span m='4077940'>I</span>
  <span m='4078050'>don't</span> <span m='4078230'>have</span> <span m='4078330'>to</span>
  <span m='4078440'>just</span> <span m='4078630'>do</span> <span m='4078760'>this</span>
  <span m='4078920'>with</span> <span m='4079450'>Cesaro's</span> <span m='4080060'>experiment,</span>
  <span m='4080530'>it</span> <span m='4080590'>could</span> <span m='4080700'>be</span>
  <span m='4080810'>lots</span> <span m='4081090'>of</span> <span m='4081170'>Monte</span>
  <span m='4081410'>Carlo</span> <span m='4081720'>experiments</span> <span m='4082210'>I</span>
  <span m='4082260'>might</span> <span m='4082500'>do.</span> </p><p><span m='4083390'>Of</span>
  <span m='4083530'>course,</span> <span m='4083680'>this</span> <span m='4083810'>depends</span>
  <span m='4084190'>upon</span> <span m='4084510'>the</span> <span m='4084620'>existence</span>
  <span m='4085060'>of</span> <span m='4085180'>some</span> <span m='4085340'>sort</span>
  <span m='4085490'>of</span> <span m='4085860'>random</span> <span m='4086220'>number</span>
  <span m='4086490'>generator.</span> <span m='4087440'>And</span> <span m='4087570'>random</span>
  <span m='4087870'>number</span> <span m='4088020'>generators</span> <span m='4089370'>generally</span>
  <span m='4089780'>look</span> <span m='4089960'>something</span> <span m='4090300'>like</span>
  <span m='4090530'>this.</span> <span m='4093570'>There</span> <span m='4093930'>is</span>
  <span m='4094050'>a</span> <span m='4095200'>random</span> <span m='4095500'>number</span>
  <span m='4095740'>generator--</span> <span m='4097550'>is</span> <span m='4097760'>in</span>
  <span m='4097880'>fact</span> <span m='4098810'>a</span> <span m='4100149'>procedure</span>
  <span m='4103000'>which</span> <span m='4103240'>is</span> <span m='4103350'>going</span>
  <span m='4103630'>to</span> <span m='4103720'>do</span> <span m='4103899'>something</span>
  <span m='4104260'>just</span> <span m='4104490'>like</span> <span m='4104660'>the</span>
  <span m='4104750'>counter.</span> <span m='4105710'>It's</span> <span m='4105930'>going</span>
  <span m='4106160'>to</span> <span m='4106330'>update</span> <span m='4106899'>an</span>
  <span m='4107060'>x</span> <span m='4108370'>to</span> <span m='4109760'>the</span>
  <span m='4109850'>result</span> <span m='4110189'>of</span> <span m='4110250'>applying</span>
  <span m='4110649'>some</span> <span m='4110870'>function</span> <span m='4111270'>to</span>
  <span m='4111359'>x,</span> <span m='4112359'>where</span> <span m='4112500'>this</span>
  <span m='4112700'>function</span> <span m='4113540'>is</span> <span m='4113710'>some</span>
  <span m='4113910'>screwy</span> <span m='4114370'>kind</span> <span m='4114600'>of</span>
  <span m='4114680'>function</span> <span m='4115240'>that</span> <span m='4115550'>you</span>
  <span m='4115640'>might</span> <span m='4115840'>find</span> <span m='4116050'>out</span>
  <span m='4116250'>in</span> <span m='4116340'>Knuth's</span> <span m='4116710'>books</span>
  <span m='4118399'>on</span> <span m='4118800'>the</span> <span m='4119050'>details</span>
  <span m='4119520'>of</span> <span m='4119600'>programming.</span> <span m='4121689'>He</span>
  <span m='4121970'>does</span> <span m='4122260'>these</span> <span m='4122399'>wonderful</span>
  <span m='4122870'>books</span> <span m='4123350'>that</span> <span m='4123950'>are</span>
  <span m='4124130'>full</span> <span m='4124359'>of the</span> <span m='4124470'>details</span>
  <span m='4125020'>of</span> <span m='4125100'>programming,</span> <span m='4125810'>because</span>
  <span m='4125930'>I</span> <span m='4126060'>can't</span> <span m='4126290'>remember</span>
  <span m='4127050'>how</span> <span m='4127240'>to</span> <span m='4127300'>make</span>
  <span m='4127460'>a</span> <span m='4127500'>random</span> <span m='4127710'>number</span>
  <span m='4127939'>generator,</span> <span m='4128479'>but</span> <span m='4128810'>I</span>
  <span m='4128939'>can</span> <span m='4129100'>look</span> <span m='4129260'>it</span>
  <span m='4129330'>up</span> <span m='4129490'>there,</span> <span m='4129770'>and</span>
  <span m='4130050'>I can find</span> <span m='4130370'>out.</span> </p><p><span m='4131720'>And
  then,</span> <span m='4131939'>eventually,</span> <span m='4132300'>I</span> <span
  m='4132390'>return</span> <span m='4133000'>the</span> <span m='4133270'>value</span>
  <span m='4133550'>of</span> <span m='4133630'>x</span> <span m='4134130'>which</span>
  <span m='4134410'>is</span> <span m='4134680'>the</span> <span m='4134850'>state</span>
  <span m='4135229'>variable</span> <span m='4135700'>internal</span> <span m='4136250'>to</span>
  <span m='4136359'>the</span> <span m='4136439'>random</span> <span m='4136689'>number</span>
  <span m='4136930'>generator.</span> <span m='4138319'>That</span> <span m='4138640'>state</span>
  <span m='4138760'>variable</span> <span m='4139420'>is</span> <span m='4139580'>initialized</span>
  <span m='4140140'>somehow,</span> <span m='4141129'>and</span> <span m='4141439'>has</span>
  <span m='4141700'>a</span> <span m='4141760'>value.</span> <span m='4143479'>And</span>
  <span m='4143689'>this</span> <span m='4143840'>procedure</span> <span m='4144270'>is</span>
  <span m='4144370'>defined</span> <span m='4144840'>in</span> <span m='4144970'>the</span>
  <span m='4145050'>context</span> <span m='4145600'>where</span> <span m='4145810'>that</span>
  <span m='4146490'>variable</span> <span m='4147490'>is</span> <span m='4147640'>bound.</span>
  <span m='4150450'>So</span> <span m='4150620'>this</span> <span m='4150790'>is</span>
  <span m='4150920'>a</span> <span m='4151439'>hidden</span> <span m='4151779'>piece</span>
  <span m='4152010'>of</span> <span m='4152120'>local</span> <span m='4152460'>state</span>
  <span m='4153996'>that</span> <span m='4154470'>you</span> <span m='4154670'>see</span>
  <span m='4154890'>here.</span> <span m='4155930'>And</span> <span m='4156149'>this</span>
  <span m='4156310'>procedure</span> <span m='4158649'>is</span> <span m='4158779'>defined</span>
  <span m='4159210'>in</span> <span m='4159380'>that</span> <span m='4159630'>context.</span>
  </p><p><span m='4161720'>Now,</span> <span m='4161880'>that's</span> <span m='4162090'>a</span>
  <span m='4162460'>very</span> <span m='4162770'>simple</span> <span m='4163109'>thing</span>
  <span m='4163290'>to</span> <span m='4163380'>do.</span> <span m='4164103'>And</span>
  <span m='4164576'>it's</span> <span m='4165189'>very</span> <span m='4165420'>nice.</span>
  <span m='4166020'>Supposing,</span> <span m='4166580'>I</span> <span m='4166640'>didn't</span>
  <span m='4166800'>want</span> <span m='4166890'>to</span> <span m='4166970'>use</span>
  <span m='4167130'>assignments.</span> <span m='4169080'>Supposing,</span> <span
  m='4169430'>I</span> <span m='4169569'>wanted</span> <span m='4169720'>to</span>
  <span m='4169810'>write</span> <span m='4170010'>this</span> <span m='4170170'>program</span>
  <span m='4170550'>without</span> <span m='4170819'>assignments.</span> <span m='4172840'>What</span>
  <span m='4173050'>problems</span> <span m='4173399'>would</span> <span m='4173520'>I</span>
  <span m='4173720'>have?</span> <span m='4175580'>Well,</span> <span m='4176870'>let's</span>
  <span m='4177130'>see.</span> <span m='4177890'>I'd</span> <span m='4178050'>like</span>
  <span m='4178210'>to</span> <span m='4178310'>use</span> <span m='4178479'>the</span>
  <span m='4178609'>overhead</span> <span m='4180460'>machine</span> <span m='4180810'>here,</span>
  <span m='4182170'>thank</span> <span m='4182430'>you.</span> </p><p><span m='4184540'>First</span>
  <span m='4184820'>of</span> <span m='4185100'>all, let's</span> <span m='4185189'>look</span>
  <span m='4185270'>at</span> <span m='4185359'>the</span> <span m='4185430'>whole</span>
  <span m='4185670'>thing.</span> <span m='4185870'>It's</span> <span m='4185990'>a</span>
  <span m='4186040'>big</span> <span m='4186250'>story.</span> <span m='4188140'>Unfortunately,</span>
  <span m='4188830'>which</span> <span m='4188920'>tells</span> <span m='4189130'>you</span>
  <span m='4189260'>there is</span> <span m='4189439'>something</span> <span m='4189540'>wrong.</span>
  <span m='4191720'>It's</span> <span m='4191859'>at</span> <span m='4191939'>least</span>
  <span m='4192220'>that</span> <span m='4192399'>big,</span> <span m='4193245'>and</span>
  <span m='4193600'>it's</span> <span m='4193880'>monolithic.</span> <span m='4197020'>You</span>
  <span m='4197440'>don't</span> <span m='4197580'>have</span> <span m='4197720'>to</span>
  <span m='4197790'>understand</span> <span m='4198190'>or</span> <span m='4198230'>look</span>
  <span m='4198350'>at</span> <span m='4198780'>the</span> <span m='4199030'>text</span>
  <span m='4199350'>there</span> <span m='4199580'>right</span> <span m='4199780'>now</span>
  <span m='4200150'>to</span> <span m='4200300'>see that it's</span> <span m='4200670'>monolithic.</span>
  <span m='4202120'>It</span> <span m='4202300'>isn't</span> <span m='4202630'>a</span>
  <span m='4202690'>thing</span> <span m='4202960'>which</span> <span m='4203150'>is</span>
  <span m='4203270'>Cesaro's</span> <span m='4203900'>experiment.</span> <span m='4205090'>It's</span>
  <span m='4205320'>not</span> <span m='4205580'>pulled</span> <span m='4205820'>out</span>
  <span m='4206110'>from</span> <span m='4206350'>the</span> <span m='4206580'>Monte</span>
  <span m='4206880'>Carlo</span> <span m='4207240'>process.</span> <span m='4210050'>It's</span>
  <span m='4210210'>not</span> <span m='4210450'>separated.</span> </p><p><span m='4210890'>Let's</span>
  <span m='4211080'>look</span> <span m='4211250'>why.</span> <span m='4214350'>Remember,</span>
  <span m='4214710'>the</span> <span m='4214880'>constraint</span> <span m='4215410'>here</span>
  <span m='4215900'>is</span> <span m='4216080'>that</span> <span m='4216240'>every</span>
  <span m='4217130'>procedure</span> <span m='4218940'>return</span> <span m='4219330'>the</span>
  <span m='4219410'>same</span> <span m='4219750'>value</span> <span m='4221130'>for</span>
  <span m='4221240'>the</span> <span m='4221350'>same</span> <span m='4221660'>arguments.</span>
  <span m='4223070'>Every</span> <span m='4223260'>procedure</span> <span m='4223590'>represents</span>
  <span m='4224010'>a</span> <span m='4224090'>function.</span> <span m='4226800'>That's</span>
  <span m='4227200'>a</span> <span m='4227250'>different</span> <span m='4227600'>kind</span>
  <span m='4227740'>of</span> <span m='4227890'>constraint.</span> <span m='4228275'>Because</span>
  <span m='4228660'>when</span> <span m='4228890'>I</span> <span m='4228980'>have</span>
  <span m='4229070'>assignments,</span> <span m='4229560'>I</span> <span m='4229670'>can</span>
  <span m='4229830'>change</span> <span m='4230120'>some</span> <span m='4230250'>internal</span>
  <span m='4230540'>state</span> <span m='4230780'>variable.</span> </p><p><span m='4231840'>So</span>
  <span m='4231980'>let's</span> <span m='4232150'>see</span> <span m='4232300'>how</span>
  <span m='4232510'>that</span> <span m='4232890'>causes</span> <span m='4233200'>things</span>
  <span m='4233420'>to</span> <span m='4233500'>go</span> <span m='4233670'>wrong.</span>
  <span m='4235060'>Well,</span> <span m='4235280'>start</span> <span m='4235540'>at
  the</span> <span m='4235620'>beginning.</span> <span m='4238510'>The</span> <span
  m='4238850'>estimate</span> <span m='4239230'>of</span> <span m='4239720'>pi</span>
  <span m='4240710'>looks</span> <span m='4240960'>sort</span> <span m='4241120'>of</span>
  <span m='4241230'>the</span> <span m='4241330'>same.</span> <span m='4242950'>What</span>
  <span m='4243240'>I'm</span> <span m='4243370'>doing</span> <span m='4244190'>is</span>
  <span m='4244350'>I</span> <span m='4244430'>take</span> <span m='4244910'>the</span>
  <span m='4245130'>square</span> <span m='4245600'>root</span> <span m='4246440'>of</span>
  <span m='4246600'>six</span> <span m='4246880'>over</span> <span m='4247320'>the</span>
  <span m='4247560'>random</span> <span m='4247900'>GCD</span> <span m='4248450'>test</span>
  <span m='4249400'>applied</span> <span m='4249820'>to</span> <span m='4250150'>n,</span>
  <span m='4250880'>whereas</span> <span m='4251080'>that's</span> <span m='4251320'>what</span>
  <span m='4251430'>this</span> <span m='4251640'>is.</span> </p><p><span m='4252990'>But</span>
  <span m='4253280'>here,</span> <span m='4253660'>we</span> <span m='4253750'>are</span>
  <span m='4253780'>beginning</span> <span m='4254050'>to</span> <span m='4254110'>see</span>
  <span m='4254290'>something</span> <span m='4254610'>funny.</span> <span m='4255390'>The</span>
  <span m='4255520'>random</span> <span m='4255870'>GCD</span> <span m='4256340'>test</span>
  <span m='4256630'>of</span> <span m='4256710'>a</span> <span m='4256760'>certain</span>
  <span m='4256990'>number</span> <span m='4257210'>of</span> <span m='4257290'>trials</span>
  <span m='4258520'>is</span> <span m='4258770'>just</span> <span m='4258970'>like</span>
  <span m='4259120'>we</span> <span m='4259250'>had</span> <span m='4259430'>before,</span>
  <span m='4260540'>an</span> <span m='4261130'>iteration</span> <span m='4262660'>on</span>
  <span m='4262920'>the</span> <span m='4263030'>number</span> <span m='4263330'>of</span>
  <span m='4263400'>trials</span> <span m='4263730'>remaining,</span> <span m='4264580'>the</span>
  <span m='4264960'>number</span> <span m='4265290'>of</span> <span m='4265360'>trials</span>
  <span m='4265750'>that</span> <span m='4265860'>have</span> <span m='4266030'>been</span>
  <span m='4266210'>passed,</span> <span m='4267750'>and</span> <span m='4268190'>another</span>
  <span m='4268760'>variable</span> <span m='4269230'>x.</span> </p><p><span m='4270870'>What's</span>
  <span m='4271090'>that</span> <span m='4271290'>x?</span> <span m='4272370'>That</span>
  <span m='4272630'>x</span> <span m='4272960'>is</span> <span m='4273460'>the</span>
  <span m='4273700'>state</span> <span m='4273990'>of</span> <span m='4274080'>the</span>
  <span m='4274160'>random</span> <span m='4274420'>number</span> <span m='4274670'>generator.</span>
  <span m='4278950'>And</span> <span m='4279290'>it is</span> <span m='4279870'>now</span>
  <span m='4280090'>going</span> <span m='4280280'>to</span> <span m='4280340'>be</span>
  <span m='4280430'>used</span> <span m='4280800'>here.</span> <span m='4281150'>The</span>
  <span m='4281360'>same</span> <span m='4281700'>random</span> <span m='4281930'>update</span>
  <span m='4282390'>function</span> <span m='4282770'>that I</span> <span m='4282930'>have</span>
  <span m='4283080'>over</span> <span m='4283240'>here</span> <span m='4283890'>is</span>
  <span m='4284040'>the</span> <span m='4284120'>one</span> <span m='4284270'>I</span>
  <span m='4284330'>would</span> <span m='4284440'>have</span> <span m='4284540'>used</span>
  <span m='4284790'>in</span> <span m='4284890'>a</span> <span m='4284930'>random</span>
  <span m='4285160'>number</span> <span m='4285400'>generator</span> <span m='4285890'>if</span>
  <span m='4285940'>I</span> <span m='4285990'>were</span> <span m='4286040'>building</span>
  <span m='4286460'>it</span> <span m='4286550'>the</span> <span m='4286710'>other</span>
  <span m='4286870'>way,</span> <span m='4287740'>the</span> <span m='4288020'>one</span>
  <span m='4288100'>I</span> <span m='4288290'>get out</span> <span m='4288510'>of</span>
  <span m='4288750'>Knuth's</span> <span m='4289080'>books.</span> <span m='4291710'>x</span>
  <span m='4291970'>is</span> <span m='4292060'>going</span> <span m='4292150'>to</span>
  <span m='4292250'>get</span> <span m='4292420'>transformed</span> <span m='4292700'>into</span>
  <span m='4292980'>x1,</span> <span m='4293180'>I</span> <span m='4293380'>need</span>
  <span m='4293610'>two</span> <span m='4293760'>random</span> <span m='4293960'>numbers.</span>
  <span m='4294950'>And</span> <span m='4295030'>x1</span> <span m='4295250'>is</span>
  <span m='4295480'>going</span> <span m='4295560'>to</span> <span m='4295640'>get</span>
  <span m='4295800'>transformed</span> <span m='4296170'>into</span> <span m='4296520'>x2,</span>
  <span m='4297400'>I</span> <span m='4297520'>have</span> <span m='4297630'>two</span>
  <span m='4297770'>random</span> <span m='4298010'>numbers.</span> <span m='4299550'>I</span>
  <span m='4299760'>then</span> <span m='4300000'>have</span> <span m='4300240'>to</span>
  <span m='4300660'>do</span> <span m='4300850'>exactly</span> <span m='4301250'>what</span>
  <span m='4301320'>I</span> <span m='4301390'>did</span> <span m='4301560'>before.</span>
  <span m='4302620'>I</span> <span m='4302770'>take</span> <span m='4302970'>the</span>
  <span m='4303050'>GCD</span> <span m='4303370'>of</span> <span m='4303530'>x1</span>
  <span m='4303740'>x2.</span> <span m='4303870'>If</span> <span m='4304260'>that's</span>
  <span m='4304520'>one,</span> <span m='4305330'>then</span> <span m='4305520'>I</span>
  <span m='4305600'>go</span> <span m='4305780'>around</span> <span m='4305940'>the</span>
  <span m='4306110'>loop</span> <span m='4306350'>with</span> <span m='4306490'>x2</span>
  <span m='4307960'>being</span> <span m='4308260'>the</span> <span m='4308430'>next</span>
  <span m='4308600'>value</span> <span m='4309010'>of</span> <span m='4309265'>x.</span>
  </p><p><span m='4314850'>You</span> <span m='4314930'>see</span> <span m='4315060'>what's</span>
  <span m='4315270'>happened</span> <span m='4315640'>here</span> <span m='4316910'>is</span>
  <span m='4317110'>that</span> <span m='4317240'>the</span> <span m='4317310'>state</span>
  <span m='4317570'>of</span> <span m='4317650'>the</span> <span m='4317740'>random</span>
  <span m='4317950'>number</span> <span m='4318190'>generator</span> <span m='4318630'>is</span>
  <span m='4318720'>no</span> <span m='4318940'>longer</span> <span m='4319290'>confined</span>
  <span m='4319880'>to</span> <span m='4319960'>the</span> <span m='4320060'>insides</span>
  <span m='4320480'>of</span> <span m='4320560'>the</span> <span m='4320620'>random</span>
  <span m='4320870'>number</span> <span m='4321120'>generator.</span> <span m='4321495'>It</span>
  <span m='4321870'>has</span> <span m='4322110'>leaked</span> <span m='4322440'>out.</span>
  <span m='4323450'>It</span> <span m='4323650'>has</span> <span m='4323790'>leaked</span>
  <span m='4324070'>out</span> <span m='4324300'>into</span> <span m='4324560'>my</span>
  <span m='4324790'>procedure</span> <span m='4326690'>that</span> <span m='4326880'>does</span>
  <span m='4327850'>the</span> <span m='4328970'>Monte</span> <span m='4329240'>Carlo</span>
  <span m='4329550'>experiment.</span> <span m='4330720'>But</span> <span m='4330930'>what's</span>
  <span m='4331100'>worse</span> <span m='4331340'>than</span> <span m='4331490'>that,</span>
  <span m='4331980'>is</span> <span m='4332110'>it's</span> <span m='4332240'>also,</span>
  <span m='4332800'>because</span> <span m='4333250'>it</span> <span m='4333330'>was</span>
  <span m='4333480'>contained</span> <span m='4333890'>inside</span> <span m='4334220'>my</span>
  <span m='4334330'>experiment</span> <span m='4334950'>itself,</span> <span m='4335540'>Cesaro,</span>
  <span m='4336890'>it</span> <span m='4337090'>leaked</span> <span m='4337340'>out</span>
  <span m='4337470'>of</span> <span m='4337770'>that</span> <span m='4337980'>too.</span>
  <span m='4338090'>Because</span> <span m='4338430'>Cesaro</span> <span m='4338620'>called</span>
  <span m='4338970'>twice,</span> <span m='4340910'>has</span> <span m='4341110'>to</span>
  <span m='4341220'>have a</span> <span m='4341320'>different</span> <span m='4341570'>value</span>
  <span m='4341920'>each</span> <span m='4342100'>time,</span> <span m='4342520'>if</span>
  <span m='4342590'>I</span> <span m='4342790'>going</span> <span m='4342930'>to have</span>
  <span m='4343100'>a</span> <span m='4343230'>legitimate</span> <span m='4344170'>experimental</span>
  <span m='4344780'>test.</span> <span m='4346360'>So</span> <span m='4346790'>Cesaro</span>
  <span m='4347060'>can't</span> <span m='4347320'>be</span> <span m='4347420'>a</span>
  <span m='4347480'>function</span> <span m='4347860'>either,</span> <span m='4351110'>unless</span>
  <span m='4351470'>I</span> <span m='4351580'>pass</span> <span m='4351910'>it</span>
  <span m='4352390'>the</span> <span m='4352760'>seed</span> <span m='4353030'>of</span>
  <span m='4353300'>the</span> <span m='4353440'>random</span> <span m='4353640'>number</span>
  <span m='4353880'>generator</span> <span m='4354165'>that</span> <span m='4354450'>is</span>
  <span m='4354560'>going</span> <span m='4354730'>to go</span> <span m='4354800'>wandering</span>
  <span m='4355170'>around.</span> </p><p><span m='4356490'>So</span> <span m='4356720'>unfortunately,</span>
  <span m='4357370'>the</span> <span m='4357460'>seed</span> <span m='4357650'>of</span>
  <span m='4358050'>random</span> <span m='4358310'>number</span> <span m='4358750'>generator</span>
  <span m='4359390'>has</span> <span m='4359740'>leaked</span> <span m='4360030'>out</span>
  <span m='4360600'>into</span> <span m='4360890'>Cesaro,</span> <span m='4361590'>from</span>
  <span m='4361800'>the</span> <span m='4361820'>random</span> <span m='4362040'>number</span>
  <span m='4362240'>generator,</span> <span m='4362850'>that's</span> <span m='4363190'>leaked</span>
  <span m='4363480'>into</span> <span m='4363790'>the</span> <span m='4363920'>Monte</span>
  <span m='4364170'>Carlo</span> <span m='4364490'>experiment.</span> <span m='4365465'>And,</span>
  <span m='4365800'>unfortunately,</span> <span m='4366960'>my</span> <span m='4367070'>Monte</span>
  <span m='4367350'>Carlo</span> <span m='4367930'>experiment</span> <span m='4368180'>here
  is</span> <span m='4368350'>no longer</span> <span m='4368620'>general.</span> <span
  m='4370310'>The</span> <span m='4370430'>Monte</span> <span m='4370670'>Carlo</span>
  <span m='4370980'>experiment</span> <span m='4371430'>here</span> <span m='4372190'>knows</span>
  <span m='4372500'>how</span> <span m='4372620'>many</span> <span m='4372780'>random</span>
  <span m='4372990'>numbers</span> <span m='4373310'>I</span> <span m='4373390'>need</span>
  <span m='4373730'>to</span> <span m='4373900'>do</span> <span m='4373970'>the</span>
  <span m='4374080'>experiment.</span> </p><p><span m='4378530'>That's</span> <span
  m='4379110'>sort</span> <span m='4379220'>of</span> <span m='4379330'>horrible.</span>
  <span m='4380230'>I</span> <span m='4380310'>lost</span> <span m='4380660'>an</span>
  <span m='4380720'>ability</span> <span m='4381180'>to</span> <span m='4381280'>decompose</span>
  <span m='4381630'>a</span> <span m='4381680'>problem</span> <span m='4381990'>into</span>
  <span m='4382060'>pieces,</span> <span m='4383310'>because</span> <span m='4384090'>I</span>
  <span m='4384200'>wasn't</span> <span m='4384530'>willing</span> <span m='4384760'>to</span>
  <span m='4384880'>accept</span> <span m='4386400'>the</span> <span m='4386510'>little</span>
  <span m='4386800'>loop</span> <span m='4387930'>of</span> <span m='4388230'>information,</span>
  <span m='4390720'>the</span> <span m='4391170'>feedback</span> <span m='4391770'>process,</span>
  <span m='4392730'>that</span> <span m='4393130'>happens</span> <span m='4393870'>inside</span>
  <span m='4394390'>the</span> <span m='4394470'>random</span> <span m='4394720'>number</span>
  <span m='4394960'>generator</span> <span m='4395320'>before</span> <span m='4395920'>that</span>
  <span m='4396150'>was</span> <span m='4396370'>made</span> <span m='4396700'>by</span>
  <span m='4396860'>having</span> <span m='4397950'>an</span> <span m='4398000'>assignment</span>
  <span m='4398760'>to</span> <span m='4398850'>a</span> <span m='4398940'>state</span>
  <span m='4399200'>variable</span> <span m='4399640'>that was</span> <span m='4399750'>confined</span>
  <span m='4400250'>to</span> <span m='4400310'>the</span> <span m='4400400'>random</span>
  <span m='4400640'>number</span> <span m='4400870'>generator.</span> <span m='4402770'>So</span>
  <span m='4403290'>the</span> <span m='4403390'>fact</span> <span m='4403670'>that</span>
  <span m='4403730'>the</span> <span m='4403800'>random</span> <span m='4404010'>number</span>
  <span m='4404240'>generator</span> <span m='4404590'>is</span> <span m='4404720'>an</span>
  <span m='4404820'>object,</span> <span m='4406070'>with an</span> <span m='4406300'>internal</span>
  <span m='4406590'>state</span> <span m='4406850'>variable,</span> <span m='4408220'>it's</span>
  <span m='4408360'>affected</span> <span m='4408900'>by</span> <span m='4409040'>nothing,</span>
  <span m='4409380'>but</span> <span m='4409530'>it'll</span> <span m='4409680'>give</span>
  <span m='4409840'>you</span> <span m='4409970'>something,</span> <span m='4410280'>and
  it will</span> <span m='4410410'>apply it's</span> <span m='4410780'>force</span>
  <span m='4411030'>to</span> <span m='4411130'>you,</span> <span m='4412930'>that</span>
  <span m='4413180'>was</span> <span m='4413420'>what</span> <span m='4413530'>we're</span>
  <span m='4413620'>missing</span> <span m='4413950'>now.</span> </p><p><span m='4418140'>OK,</span>
  <span m='4419540'>well</span> <span m='4419740'>I</span> <span m='4419840'>think</span>
  <span m='4420090'>we've</span> <span m='4420260'>seen</span> <span m='4420820'>enough</span>
  <span m='4421200'>reason</span> <span m='4421520'>for</span> <span m='4421650'>doing</span>
  <span m='4421980'>this,</span> <span m='4422870'>and</span> <span m='4423130'>it</span>
  <span m='4423470'>all</span> <span m='4423810'>sort</span> <span m='4424100'>of</span>
  <span m='4424190'>looks</span> <span m='4424390'>very</span> <span m='4424580'>wonderful.</span>
  <span m='4425510'>Wouldn't</span> <span m='4425810'>it</span> <span m='4425890'>be</span>
  <span m='4426020'>nice</span> <span m='4428970'>if</span> <span m='4429450'>assignment</span>
  <span m='4429930'>was</span> <span m='4430070'>a</span> <span m='4430120'>good</span>
  <span m='4430370'>thing</span> <span m='4431840'>and</span> <span m='4432060'>maybe</span>
  <span m='4432300'>it's</span> <span m='4432420'>worth</span> <span m='4432680'>it,</span>
  <span m='4433030'>but</span> <span m='4433490'>I'm</span> <span m='4433610'>not</span>
  <span m='4433830'>sure.</span> <span m='4435440'>As</span> <span m='4435650'>Mr.</span>
  <span m='4436080'>Gilbert and</span> <span m='4436440'>Sullivan</span> <span m='4436750'>said,</span>
  <span m='4437090'>things</span> <span m='4437300'>are</span> <span m='4437370'>seldom</span>
  <span m='4437730'>what</span> <span m='4437860'>they</span> <span m='4437990'>seem,</span>
  <span m='4438580'>skim</span> <span m='4438890'>milk</span> <span m='4439180'>masquerades</span>
  <span m='4439870'>as</span> <span m='4439990'>cream.</span> </p><p><span m='4441940'>Are</span>
  <span m='4442060'>there</span> <span m='4442210'>any</span> <span m='4443350'>questions?</span>
  <span m='4457010'>Are</span> <span m='4457130'>there</span> <span m='4457270'>any</span>
  <span m='4457430'>philosophers</span> <span m='4458040'>here?</span> <span m='4460120'>Anybody</span>
  <span m='4460430'>want</span> <span m='4460520'>to</span> <span m='4460600'>argue</span>
  <span m='4460940'>about</span> <span m='4461600'>objects?</span> <span m='4464590'>You're</span>
  <span m='4464760'>just</span> <span m='4464950'>floored,</span> <span m='4465290'>right?</span>
  <span m='4469840'>And you</span> <span m='4469970'>haven't</span> <span m='4470160'>done</span>
  <span m='4470300'>your</span> <span m='4470410'>homework</span> <span m='4470700'>yet.
  You</span> <span m='4470910'>haven't</span> <span m='4471100'>come</span> <span
  m='4471240'>up</span> <span m='4471340'>with</span> <span m='4471450'>a good</span>
  <span m='4471560'>question.</span> <span m='4476790'>Oh,</span> <span m='4477030'>well.</span>
  <span m='4480110'>Sure,</span> <span m='4480750'>thank</span> <span m='4481010'>you.</span>
  <span m='4481120'>Let's</span> <span m='4481320'>take</span> <span m='4481540'>the</span>
  <span m='4481580'>long</span> <span m='4481820'>break</span> <span m='4482110'>now.</span>
  </p>
type: course
uid: 0d9197bbe8dc4cc36bd40a2ce243052f

---
None