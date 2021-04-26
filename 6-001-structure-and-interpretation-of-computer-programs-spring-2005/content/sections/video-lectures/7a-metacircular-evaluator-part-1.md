---
about_this_resource_text: <p><b>Topics covered:</b> Metacircular Evaluator, Part 1</p>
  <p><b> Instructors:</b> Hal Abelson and Gerald Jay Sussman</p> <p>Subtitles for
  this course are provided through the generous assistance of Henry Baker, Hoofar
  Pourzand, Heather Wood, Aleksejs Truhans, Steven Edwards, George Menhorn, and Mahendra
  Kumar.</p>
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
embedded_media:
- id: 7A.jpg
  parent_uid: fc0495f305df1c5963fdacc15968c4aa
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/7a-metacircular-evaluator-part-1/7A.jpg
  title: 7A.jpg
  type: null
  uid: 159facf30a7cff40e9862a332ab83819
- id: Video-YouTube-Stream
  media_location: aAlR3cezPJg
  parent_uid: fc0495f305df1c5963fdacc15968c4aa
  title: Video-YouTube-Stream
  type: Video
  uid: 2765aaba48c74849973828dac55ab143
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT_Structure_of_Computer_Programs_1986/lec7a.mp4
  parent_uid: fc0495f305df1c5963fdacc15968c4aa
  title: Video-Internet Archive-MP4
  type: Video
  uid: 814e9a78c2a236fc81fa5b02c2892741
- id: Thumbnail-OCW-JPG
  parent_uid: fc0495f305df1c5963fdacc15968c4aa
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 62fe171946673af83a28d062869d0e85
- id: 3Play-3PlayYouTubeid-MP4
  media_location: aAlR3cezPJg
  parent_uid: fc0495f305df1c5963fdacc15968c4aa
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 86bec359b212609e65704e64f36a3626
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/aAlR3cezPJg/default.jpg
  parent_uid: fc0495f305df1c5963fdacc15968c4aa
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 2effaf4ed70b144a29ef166aa2548962
- id: aAlR3cezPJg.srt
  parent_uid: fc0495f305df1c5963fdacc15968c4aa
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/7a-metacircular-evaluator-part-1/aAlR3cezPJg.srt
  title: 3play caption file
  type: null
  uid: 4d07432cecc9713fab9398f6609f9edf
- id: aAlR3cezPJg.pdf
  parent_uid: fc0495f305df1c5963fdacc15968c4aa
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/7a-metacircular-evaluator-part-1/aAlR3cezPJg.pdf
  title: 3play pdf file
  type: null
  uid: 0b41187e21dfe262000f4d3adac855b1
- id: Caption-3Play YouTube id-SRT
  parent_uid: fc0495f305df1c5963fdacc15968c4aa
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: f6a8794d6a6235586671fe331f9466d7
- id: Transcript-3Play YouTube id-PDF
  parent_uid: fc0495f305df1c5963fdacc15968c4aa
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 9f5117df1335822d1dbed5038a1b15ea
inline_embed_id: 857974667a:metacircularevaluator,part182079757
layout: video
order_index: null
parent_uid: 4fcacad2c29981dd668a6b29822403cc
related_resources_text: ''
short_url: 7a-metacircular-evaluator-part-1
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/7a-metacircular-evaluator-part-1
template_type: Tabbed
title: '7A: Metacircular Evaluator, Part 1'
transcript: <p><span m='15314'>PROFESSOR:</span> <span m='15820'>Well</span> <span
  m='15970'>today</span> <span m='16260'>we're</span> <span m='16340'>going</span>
  <span m='16400'>to</span> <span m='16460'>learn</span> <span m='16650'>about</span>
  <span m='16920'>something</span> <span m='17580'>quite</span> <span m='17850'>amazing.</span>
  <span m='18410'>We're</span> <span m='18900'>going</span> <span m='19390'>to</span>
  <span m='19860'>understand</span> <span m='20480'>what</span> <span m='20640'>we</span>
  <span m='20780'>mean</span> <span m='21030'>by</span> <span m='21170'>a</span> <span
  m='21240'>program</span> <span m='22670'>a</span> <span m='22760'>little</span>
  <span m='22950'>bit</span> <span m='23120'>more</span> <span m='23320'>profoundly</span>
  <span m='23850'>than</span> <span m='24000'>we</span> <span m='24190'>have</span>
  <span m='24380'>up</span> <span m='24500'>till</span> <span m='24710'>now.</span>
  <span m='26800'>Up</span> <span m='27000'>till</span> <span m='27210'>now,</span>
  <span m='28330'>we've</span> <span m='28510'>been</span> <span m='28660'>thinking</span>
  <span m='29290'>of</span> <span m='29490'>programs</span> <span m='30060'>as</span>
  <span m='30650'>describing</span> <span m='31460'>machines.</span> </p><p><span
  m='32729'>So</span> <span m='33030'>for</span> <span m='33210'>example,</span> <span
  m='33700'>looking</span> <span m='34020'>at</span> <span m='34250'>this</span> <span
  m='36490'>still</span> <span m='36820'>store,</span> <span m='38050'>we</span> <span
  m='38300'>see</span> <span m='38510'>here</span> <span m='38800'>is</span> <span
  m='39000'>a</span> <span m='39830'>program</span> <span m='40870'>for</span> <span
  m='41010'>factorial.</span> <span m='42800'>And</span> <span m='42980'>what</span>
  <span m='43170'>it</span> <span m='43260'>is,</span> <span m='44380'>is</span> <span
  m='44570'>a</span> <span m='44630'>character</span> <span m='45100'>string</span>
  <span m='45390'>description,</span> <span m='46670'>if</span> <span m='46820'>you</span>
  <span m='46970'>will,</span> <span m='47680'>of</span> <span m='47850'>the</span>
  <span m='47920'>wiring</span> <span m='48430'>diagram</span> <span m='49310'>of</span>
  <span m='49440'>a</span> <span m='49520'>potentially</span> <span m='50970'>infinite</span>
  <span m='51390'>machine.</span> <span m='52230'>And</span> <span m='52630'>we</span>
  <span m='52800'>can</span> <span m='52930'>look</span> <span m='53030'>at</span>
  <span m='53130'>that</span> <span m='53240'>a</span> <span m='53350'>little</span>
  <span m='53570'>bit</span> <span m='53820'>and just</span> <span m='53920'>see</span>
  <span m='54110'>the</span> <span m='54260'>idea.</span> <span m='55130'>That</span>
  <span m='55660'>this</span> <span m='56010'>is</span> <span m='56170'>a</span> <span
  m='56290'>sort</span> <span m='56400'>of</span> <span m='56510'>compact</span> <span
  m='57090'>notation</span> <span m='57650'>which</span> <span m='57830'>says,</span>
  <span m='58580'>if</span> <span m='58760'>n</span> <span m='58910'>is</span> <span
  m='58950'>0,</span> <span m='59300'>the</span> <span m='59390'>result</span> <span
  m='59780'>is</span> <span m='59870'>one.</span> </p><p><span m='60170'>Well</span>
  <span m='60310'>here</span> <span m='60470'>comes</span> <span m='60710'>n</span>
  <span m='60960'>coming</span> <span m='61230'>into</span> <span m='61410'>this</span>
  <span m='61590'>machine,</span> <span m='62390'>and</span> <span m='62710'>if</span>
  <span m='62860'>it's</span> <span m='63100'>0,</span> <span m='63800'>then</span>
  <span m='64110'>I</span> <span m='64209'>control</span> <span m='64660'>this</span>
  <span m='64810'>switch</span> <span m='65440'>in</span> <span m='65600'>such</span>
  <span m='65850'>a</span> <span m='65910'>way</span> <span m='66110'>that</span>
  <span m='66230'>the</span> <span m='66360'>switch</span> <span m='66720'>allows</span>
  <span m='67040'>the</span> <span m='67160'>output</span> <span m='67480'>to</span>
  <span m='67560'>be</span> <span m='67700'>one.</span> <span m='69340'>Otherwise,</span>
  <span m='70520'>it's</span> <span m='70820'>n</span> <span m='71220'>times</span>
  <span m='71480'>factorial</span> <span m='71820'>of</span> <span m='72090'>n minus</span>
  <span m='72390'>one.</span> <span m='72970'>Well,</span> <span m='73240'>I'm</span>
  <span m='73350'>computing</span> <span m='73730'>factorial</span> <span m='74150'>of</span>
  <span m='74280'>n</span> <span m='74410'>minus</span> <span m='74750'>one</span>
  <span m='75300'>and</span> <span m='75450'>multiplying</span> <span m='75920'>that</span>
  <span m='76140'>by</span> <span m='76300'>n,</span> <span m='76890'>and,</span>
  <span m='77390'>in</span> <span m='77580'>the</span> <span m='77690'>case</span>
  <span m='78030'>that</span> <span m='78170'>it's</span> <span m='78330'>not</span>
  <span m='78620'>0,</span> <span m='78920'>this</span> <span m='79110'>switch</span>
  <span m='79350'>makes</span> <span m='79560'>the</span> <span m='79660'>output</span>
  <span m='80010'>come</span> <span m='80160'>from</span> <span m='80340'>there.</span>
  </p><p><span m='81900'>Of</span> <span m='82050'>course,</span> <span m='82380'>this</span>
  <span m='82550'>is</span> <span m='82660'>a</span> <span m='83060'>machine</span>
  <span m='83420'>with</span> <span m='83540'>a</span> <span m='83660'>potentially</span>
  <span m='84150'>infinite</span> <span m='84460'>number</span> <span m='84770'>of</span>
  <span m='84850'>parts,</span> <span m='85490'>because</span> <span m='86130'>factorial</span>
  <span m='86730'>occurs</span> <span m='87140'>within</span> <span m='87300'>factorial,</span>
  <span m='88470'>so</span> <span m='88640'>we</span> <span m='88750'>don't</span>
  <span m='88880'>know</span> <span m='89020'>how</span> <span m='89210'>deep</span>
  <span m='89430'>it</span> <span m='89510'>has</span> <span m='89760'>to</span> <span
  m='89850'>be.</span> <span m='91070'>But</span> <span m='91220'>that's</span> <span
  m='91570'>basically</span> <span m='92450'>what</span> <span m='92600'>our</span>
  <span m='92740'>notation</span> <span m='94250'>for</span> <span m='95280'>programs</span>
  <span m='95880'>really</span> <span m='96480'>means</span> <span m='96860'>to</span>
  <span m='96940'>us</span> <span m='97110'>at</span> <span m='97260'>this</span>
  <span m='97420'>point.</span> <span m='98310'>It's</span> <span m='98530'>a</span>
  <span m='99000'>character</span> <span m='99390'>string</span> <span m='99660'>description,</span>
  <span m='100130'>if</span> <span m='100240'>you</span> <span m='100360'>will,</span>
  <span m='101310'>of</span> <span m='101660'>a</span> <span m='101810'>wiring</span>
  <span m='102200'>diagram</span> <span m='102680'>that</span> <span m='102770'>could</span>
  <span m='103000'>also be</span> <span m='103280'>drawn</span> <span m='103580'>some</span>
  <span m='103770'>other</span> <span m='103920'>way.</span> </p><p><span m='104900'>And,</span>
  <span m='105070'>in</span> <span m='105130'>fact,</span> <span m='105390'>many</span>
  <span m='105580'>people have</span> <span m='105880'>proposed</span> <span m='106320'>to</span>
  <span m='106410'>me,</span> <span m='107100'>programming</span> <span m='107520'>languages</span>
  <span m='107950'>look</span> <span m='108120'>graphical</span> <span m='108620'>like</span>
  <span m='108860'>this.</span> <span m='109490'>I'm</span> <span m='109820'>not</span>
  <span m='109990'>sure</span> <span m='110140'>I</span> <span m='110200'>believe</span>
  <span m='110550'>there</span> <span m='110680'>are</span> <span m='110710'>many</span>
  <span m='110910'>advantages.</span> <span m='111500'>The</span> <span m='112050'>major</span>
  <span m='112390'>disadvantage,</span> <span m='113340'>of</span> <span m='113540'>course,</span>
  <span m='113840'>is</span> <span m='113980'>that</span> <span m='114090'>it</span>
  <span m='114200'>takes</span> <span m='114390'>up</span> <span m='114470'>more</span>
  <span m='114690'>space</span> <span m='115050'>on</span> <span m='115170'>a</span>
  <span m='115210'>page,</span> <span m='115930'>and,</span> <span m='116100'>therefore,</span>
  <span m='116530'>it's</span> <span m='116650'>harder</span> <span m='116960'>to</span>
  <span m='117070'>pack</span> <span m='117360'>into</span> <span m='117670'>a</span>
  <span m='117920'>listing</span> <span m='118380'>or</span> <span m='118910'>to</span>
  <span m='119190'>edit</span> <span m='119450'>very</span> <span m='119650'>well.</span>
  </p><p><span m='121090'>But</span> <span m='121530'>in</span> <span m='121620'>any</span>
  <span m='121810'>case,</span> <span m='123850'>there's</span> <span m='124060'>something</span>
  <span m='124350'>very</span> <span m='124620'>remarkable</span> <span m='125190'>that</span>
  <span m='125300'>can</span> <span m='125410'>happen</span> <span m='126020'>in</span>
  <span m='126120'>the</span> <span m='126200'>competition</span> <span m='126750'>world</span>
  <span m='127690'>which</span> <span m='127940'>is</span> <span m='128410'>that</span>
  <span m='128550'>you</span> <span m='128690'>can</span> <span m='128810'>have</span>
  <span m='129020'>something</span> <span m='129289'>called</span> <span m='129520'>a</span>
  <span m='129560'>universal</span> <span m='130130'>machine.</span> <span m='130450'>If</span>
  <span m='130770'>we</span> <span m='130979'>look</span> <span m='131100'>at</span>
  <span m='131230'>the</span> <span m='131760'>second</span> <span m='134690'>slide,</span>
  <span m='136110'>what</span> <span m='136280'>we</span> <span m='136410'>see</span>
  <span m='136750'>is</span> <span m='138200'>a</span> <span m='138340'>special</span>
  <span m='138780'>machine</span> <span m='139190'>called</span> <span m='139500'>eval.</span>
  </p><p><span m='141260'>There</span> <span m='141510'>is</span> <span m='141710'>a</span>
  <span m='141840'>machine</span> <span m='142230'>called</span> <span m='142510'>eval,</span>
  <span m='142765'>and</span> <span m='143020'>I'm</span> <span m='143130'>going</span>
  <span m='143240'>to</span> <span m='143360'>show</span> <span m='143580'>it</span>
  <span m='143670'>to</span> <span m='143750'>you</span> <span m='143890'>today.</span>
  <span m='145720'>It's</span> <span m='145920'>very</span> <span m='146240'>simple.</span>
  <span m='147780'>What</span> <span m='147970'>is</span> <span m='148100'>remarkable</span>
  <span m='149330'>is</span> <span m='149470'>that</span> <span m='149590'>it</span>
  <span m='149630'>will</span> <span m='149750'>fit</span> <span m='149910'>on</span>
  <span m='150100'>the</span> <span m='150180'>blackboard.</span> <span m='153350'>However,</span>
  <span m='153950'>eval</span> <span m='154980'>is</span> <span m='155150'>a</span>
  <span m='155260'>machine</span> <span m='156070'>which</span> <span m='156360'>takes</span>
  <span m='156780'>as</span> <span m='157040'>input</span> <span m='158170'>a</span>
  <span m='158310'>description</span> <span m='158900'>of</span> <span m='159010'>another</span>
  <span m='159280'>machine.</span> </p><p><span m='160450'>It</span> <span m='160590'>could</span>
  <span m='160720'>take</span> <span m='160920'>the</span> <span m='161000'>wiring</span>
  <span m='161450'>diagram</span> <span m='162390'>of</span> <span m='162550'>a</span>
  <span m='162620'>factorial</span> <span m='163180'>machine</span> <span m='164950'>as</span>
  <span m='165160'>input.</span> <span m='166490'>Having</span> <span m='166960'>done</span>
  <span m='167240'>so,</span> <span m='168560'>it</span> <span m='168830'>becomes</span>
  <span m='170370'>a</span> <span m='170500'>simulator</span> <span m='171140'>for</span>
  <span m='171310'>the</span> <span m='171480'>factorial</span> <span m='172020'>machine</span>
  <span m='173150'>such</span> <span m='173490'>that,</span> <span m='174220'>if</span>
  <span m='174350'>you</span> <span m='174470'>put</span> <span m='174630'>a</span>
  <span m='174670'>six</span> <span m='174950'>in,</span> <span m='175150'>out comes</span>
  <span m='175530'>a</span> <span m='175590'>720.</span> <span m='178910'>That's</span>
  <span m='179090'>a</span> <span m='179470'>very</span> <span m='179890'>remarkable</span>
  <span m='180720'>sort</span> <span m='180910'>of</span> <span m='181110'>machine.</span>
  <span m='182130'>And</span> <span m='182290'>the</span> <span m='182460'>most</span>
  <span m='182690'>amazing</span> <span m='183180'>part</span> <span m='183340'>of</span>
  <span m='183500'>it</span> <span m='183830'>is</span> <span m='184000'>that</span>
  <span m='184210'>it</span> <span m='184390'>fits on</span> <span m='184520'>a</span>
  <span m='184560'>blackboard.</span> </p><p><span m='185590'>By</span> <span m='185900'>contrast,</span>
  <span m='187430'>one</span> <span m='187680'>could</span> <span m='187830'>imagine</span>
  <span m='188100'>in</span> <span m='188370'>the</span> <span m='189020'>analog</span>
  <span m='189500'>electronics</span> <span m='190070'>world</span> <span m='191580'>a</span>
  <span m='191700'>very</span> <span m='191960'>different</span> <span m='192320'>machine,</span>
  <span m='194680'>a</span> <span m='194790'>machine</span> <span m='196590'>which</span>
  <span m='196840'>also</span> <span m='197180'>was,</span> <span m='197370'>in</span>
  <span m='197480'>some</span> <span m='197670'>sense,</span> <span m='198140'>universal,</span>
  <span m='199350'>where</span> <span m='199600'>you</span> <span m='199720'>gave</span>
  <span m='200010'>a</span> <span m='200070'>circuit</span> <span m='200440'>diagram</span>
  <span m='202060'>as</span> <span m='202250'>one</span> <span m='202410'>of</span>
  <span m='202500'>the</span> <span m='202590'>inputs,</span> <span m='203840'>for</span>
  <span m='204000'>example,</span> <span m='204380'>of</span> <span m='204500'>this</span>
  <span m='204630'>little</span> <span m='204830'>low-pass</span> <span m='205330'>filter,</span>
  <span m='206140'>one-pole</span> <span m='206590'>low-pass</span> <span m='207060'>filter.</span>
  <span m='208050'>And</span> <span m='208230'>you</span> <span m='208420'>can</span>
  <span m='208560'>imagine</span> <span m='209130'>that</span> <span m='209780'>you</span>
  <span m='209930'>could,</span> <span m='210080'>for</span> <span m='210230'>example,</span>
  <span m='210630'>scan</span> <span m='211030'>this</span> <span m='211250'>out--</span>
  <span m='212030'>the</span> <span m='212220'>scan</span> <span m='212640'>lines</span>
  <span m='214940'>are</span> <span m='215090'>the</span> <span m='215190'>signal</span>
  <span m='215590'>that's</span> <span m='216360'>describing</span> <span m='217390'>what</span>
  <span m='217740'>this</span> <span m='217950'>machine</span> <span m='219020'>is</span>
  <span m='219590'>to</span> <span m='219920'>simulate--</span> <span m='220770'>then</span>
  <span m='220990'>the</span> <span m='221150'>analog</span> <span m='221650'>of</span>
  <span m='222080'>that</span> <span m='222240'>which is</span> <span m='222320'>made
  out of</span> <span m='222610'>electrical</span> <span m='223040'>circuits,</span>
  <span m='223640'>should</span> <span m='223830'>configure</span> <span m='224270'>itself</span>
  <span m='224570'>into</span> <span m='224740'>a</span> <span m='224800'>filter</span>
  <span m='225140'>that</span> <span m='225500'>has the</span> <span m='225580'>frequency</span>
  <span m='225870'>response</span> <span m='226530'>specified</span> <span m='227010'>by</span>
  <span m='227110'>the</span> <span m='227210'>circuit</span> <span m='227500'>diagram.</span>
  <span m='229890'>That's</span> <span m='230200'>a</span> <span m='230290'>very</span>
  <span m='230650'>hard</span> <span m='230920'>machine</span> <span m='231220'>to</span>
  <span m='231290'>make,</span> <span m='231660'>and,</span> <span m='231840'>surely,</span>
  <span m='232180'>there's</span> <span m='232350'>no</span> <span m='232520'>chance</span>
  <span m='232870'>that</span> <span m='232950'>I</span> <span m='233040'>could</span>
  <span m='233180'>put</span> <span m='233350'>it on</span> <span m='233480'>a</span>
  <span m='233520'>blackboard.</span> </p><p><span m='235670'>So</span> <span m='236030'>we're
  going to</span> <span m='236090'>see</span> <span m='236270'>an</span> <span m='236360'>amazing</span>
  <span m='237000'>thing</span> <span m='237220'>today.</span> <span m='238430'>We're</span>
  <span m='238630'>going</span> <span m='238800'>to</span> <span m='238980'>see,</span>
  <span m='239860'>on</span> <span m='240070'>the</span> <span m='240140'>blackboard,</span>
  <span m='241240'>the</span> <span m='241420'>universal</span> <span m='241930'>machine.</span>
  <span m='242790'>And</span> <span m='243010'>we'll see</span> <span m='243120'>that</span>
  <span m='243290'>among</span> <span m='243890'>other</span> <span m='244110'>things,</span>
  <span m='244570'>it's</span> <span m='244760'>extremely</span> <span m='245420'>simple.</span>
  </p><p><span m='246780'>Now,</span> <span m='247810'>we're</span> <span m='247920'>getting</span>
  <span m='248240'>very</span> <span m='248480'>close</span> <span m='249120'>to</span>
  <span m='249240'>the</span> <span m='249330'>real</span> <span m='249540'>spirit</span>
  <span m='249900'>in</span> <span m='249980'>the</span> <span m='250070'>computer</span>
  <span m='250430'>at</span> <span m='250550'>this</span> <span m='250680'>point.</span>
  <span m='251280'>So</span> <span m='251620'>I</span> <span m='251730'>have</span>
  <span m='251940'>to</span> <span m='252190'>show</span> <span m='252430'>a</span>
  <span m='252490'>certain</span> <span m='252730'>amount</span> <span m='253010'>of</span>
  <span m='253580'>reverence</span> <span m='254030'>and</span> <span m='254110'>respect,</span>
  <span m='255100'>so</span> <span m='255290'>I'm</span> <span m='255410'>going</span>
  <span m='255590'>to</span> <span m='255680'>wear</span> <span m='255900'>a</span>
  <span m='255950'>suit</span> <span m='256170'>jacket</span> <span m='256550'>for</span>
  <span m='256620'>the</span> <span m='256790'>only</span> <span m='256970'>time</span>
  <span m='257579'>that you'll</span> <span m='257829'>ever</span> <span m='258010'>see</span>
  <span m='258170'>me</span> <span m='258260'>wear</span> <span m='258440'>a</span>
  <span m='258500'>suit</span> <span m='258700'>jacket</span> <span m='259060'>here.</span>
  <span m='260470'>And</span> <span m='260910'>I</span> <span m='261350'>think</span>
  <span m='261540'>I'm</span> <span m='261670'>also</span> <span m='261959'>going</span>
  <span m='262050'>to</span> <span m='263550'>put</span> <span m='263740'>on</span>
  <span m='263900'>an</span> <span m='264000'>appropriate</span> <span m='265330'>hat</span>
  <span m='265620'>for</span> <span m='265730'>the</span> <span m='265900'>occasion.</span>
  <span m='268780'>Now,</span> <span m='269000'>this</span> <span m='269180'>is</span>
  <span m='269290'>a</span> <span m='269710'>lecturer</span> <span m='270340'>which</span>
  <span m='270540'>I</span> <span m='270650'>have</span> <span m='270760'>to</span>
  <span m='270870'>warn</span> <span m='271150'>you--</span> <span m='274140'>let's</span>
  <span m='274340'>see,</span> <span m='274490'>normally,</span> <span m='275370'>people</span>
  <span m='276060'>under</span> <span m='276370'>40</span> <span m='277110'>and who</span>
  <span m='277390'>don't</span> <span m='277550'>have</span> <span m='277690'>several</span>
  <span m='277980'>children</span> <span m='278730'>are</span> <span m='278900'>advised</span>
  <span m='279610'>to</span> <span m='279780'>be</span> <span m='279890'>careful.</span>
  <span m='280370'>If</span> <span m='280530'>they're</span> <span m='280690'>really</span>
  <span m='281050'>worried,</span> <span m='281320'>they</span> <span m='281410'>should</span>
  <span m='281600'>leave.</span> <span m='283410'>Because</span> <span m='284170'>there's</span>
  <span m='284420'>a</span> <span m='284720'>certain</span> <span m='285050'>amount</span>
  <span m='285410'>of</span> <span m='285790'>mysticism</span> <span m='286360'>that</span>
  <span m='286490'>will</span> <span m='286610'>appear</span> <span m='286890'>here</span>
  <span m='288080'>which</span> <span m='288430'>may</span> <span m='288620'>be</span>
  <span m='288730'>disturbing</span> <span m='289720'>and</span> <span m='289910'>cause</span>
  <span m='290140'>trouble</span> <span m='290440'>in</span> <span m='290510'>your</span>
  <span m='290630'>minds.</span> </p><p><span m='291820'>Well</span> <span m='292040'>in</span>
  <span m='292120'>any</span> <span m='292340'>case,</span> <span m='293620'>let's</span>
  <span m='293940'>see,</span> <span m='295610'>I</span> <span m='295840'>wish</span>
  <span m='296070'>to</span> <span m='296220'>write</span> <span m='296520'>for</span>
  <span m='296600'>you</span> <span m='297100'>the</span> <span m='297300'>evaluator</span>
  <span m='299520'>for</span> <span m='301280'>Lisp.</span> <span m='302510'>Now</span>
  <span m='302640'>the</span> <span m='302760'>evaluator</span> <span m='303180'>isn't</span>
  <span m='303390'>very</span> <span m='303620'>complicated.</span> <span m='305020'>It's</span>
  <span m='305220'>very</span> <span m='305510'>much</span> <span m='305760'>like</span>
  <span m='305990'>all</span> <span m='306150'>the</span> <span m='306220'>programs</span>
  <span m='306650'>we've</span> <span m='306800'>seen</span> <span m='307030'>already.</span>
  <span m='308240'>That's</span> <span m='308500'>the</span> <span m='308610'>amazing</span>
  <span m='308990'>part</span> <span m='309200'>of</span> <span m='309290'>it.</span>
  <span m='310860'>It's</span> <span m='311160'>going</span> <span m='311440'>to</span>
  <span m='311720'>be--</span> <span m='312200'>and</span> <span m='312570'>I'm</span>
  <span m='312810'>going to</span> <span m='313140'>write it</span> <span m='313586'>right</span>
  <span m='314032'>here--</span> <span m='315370'>it's</span> <span m='315530'>a</span>
  <span m='315590'>program</span> <span m='315980'>called</span> <span m='316290'>eval.</span>
  <span m='322900'>And</span> <span m='323040'>it's</span> <span m='323190'>a</span>
  <span m='323300'>procedure</span> <span m='325550'>of</span> <span m='325720'>two</span>
  <span m='325970'>arguments</span> <span m='326380'>in</span> <span m='326490'>expression</span>
  <span m='327510'>of</span> <span m='328470'>an</span> <span m='328780'>environment.</span>
  <span m='331860'>And</span> <span m='332090'>like</span> <span m='332350'>every</span>
  <span m='332690'>interesting</span> <span m='333130'>procedure,</span> <span m='334120'>it's</span>
  <span m='334280'>a</span> <span m='334330'>case</span> <span m='334610'>analysis.</span>
  </p><p><span m='340460'>But</span> <span m='340730'>before</span> <span m='341090'>I</span>
  <span m='341190'>start</span> <span m='341570'>on</span> <span m='341840'>this,</span>
  <span m='342510'>I</span> <span m='342710'>want</span> <span m='342830'>to</span>
  <span m='342950'>tell</span> <span m='343140'>you</span> <span m='343270'>some</span>
  <span m='343490'>things.</span> <span m='344210'>The</span> <span m='344630'>program</span>
  <span m='344980'>we're going to</span> <span m='345150'>write</span> <span m='345310'>on</span>
  <span m='345370'>the</span> <span m='345440'>blackboard</span> <span m='346620'>is</span>
  <span m='346880'>ugly,</span> <span m='348280'>dirty,</span> <span m='349420'>disgusting,</span>
  <span m='351020'>not</span> <span m='351430'>the</span> <span m='351530'>way</span>
  <span m='351710'>I</span> <span m='351830'>would</span> <span m='351980'>write</span>
  <span m='352200'>this</span> <span m='352350'>is</span> <span m='352450'>a</span>
  <span m='352500'>professional.</span> <span m='354210'>It</span> <span m='354440'>is</span>
  <span m='354750'>written</span> <span m='355310'>with</span> <span m='355480'>concrete</span>
  <span m='356090'>syntax,</span> <span m='357300'>meaning</span> <span m='357510'>you've
  got</span> <span m='357940'>really to</span> <span m='358220'>use lots of</span>
  <span m='358300'>CARs</span> <span m='358560'>and</span> <span m='358715'>CDRs</span>
  <span m='358870'>which</span> <span m='359000'>is</span> <span m='359110'>exactly</span>
  <span m='359510'>what</span> <span m='359570'>I</span> <span m='359630'>told</span>
  <span m='359820'>you</span> <span m='359910'>not</span> <span m='360090'>to</span>
  <span m='360270'>do.</span> <span m='362550'>That's</span> <span m='363640'>on</span>
  <span m='363860'>purpose</span> <span m='365020'>in</span> <span m='365130'>this</span>
  <span m='365330'>case,</span> <span m='366070'>because</span> <span m='366380'>I</span>
  <span m='366470'>want it</span> <span m='366810'>to</span> <span m='366900'>be</span>
  <span m='367180'>small,</span> <span m='368440'>compact,</span> <span m='369270'>fit</span>
  <span m='369550'>on</span> <span m='369660'>the</span> <span m='369780'>blackboard</span>
  <span m='370390'>so</span> <span m='370490'>you</span> <span m='370610'>can</span>
  <span m='370740'>get</span> <span m='370930'>the</span> <span m='371010'>whole</span>
  <span m='371430'>thing.</span> <span m='372420'>So I don't want</span> <span m='372840'>to
  use</span> <span m='372960'>long</span> <span m='373300'>names</span> <span m='373600'>like</span>
  <span m='373800'>I</span> <span m='373940'>normally</span> <span m='374360'>use.</span>
  <span m='375800'>I</span> <span m='375970'>want</span> <span m='376140'>to</span>
  <span m='376160'>use</span> <span m='376310'>CAR-CDR</span> <span m='376670'>because
  it's</span> <span m='376940'>short.</span> </p><p><span m='379580'>Now,</span> <span
  m='379720'>that's</span> <span m='379920'>a</span> <span m='380270'>trade-off.</span>
  <span m='380950'>I</span> <span m='381110'>don't</span> <span m='381250'>want</span>
  <span m='381510'>you</span> <span m='381610'>writing</span> <span m='381900'>programs</span>
  <span m='382360'>like</span> <span m='382560'>this.</span> <span m='383570'>This</span>
  <span m='383810'>is</span> <span m='383960'>purely</span> <span m='384360'>for an</span>
  <span m='384620'>effect.</span> <span m='386090'>Now,</span> <span m='386200'>you're</span>
  <span m='386310'>going</span> <span m='386360'>to</span> <span m='386420'>have</span>
  <span m='386500'>to</span> <span m='386580'>work</span> <span m='386770'>a</span>
  <span m='386820'>little</span> <span m='386980'>harder</span> <span m='387220'>to</span>
  <span m='387320'>read</span> <span m='387530'>it,</span> <span m='387820'>but</span>
  <span m='387960'>I'm going to</span> <span m='388100'>try</span> <span m='388300'>to</span>
  <span m='388370'>make</span> <span m='388630'>it</span> <span m='388940'>clear</span>
  <span m='389270'>as</span> <span m='389590'>I'm</span> <span m='389760'>writing</span>
  <span m='390070'>it.</span> <span m='391270'>I'm</span> <span m='391470'>also--</span>
  <span m='392395'>this</span> <span m='392760'>is</span> <span m='392970'>a</span>
  <span m='393070'>pretty</span> <span m='393290'>much</span> <span m='393500'>complete</span>
  <span m='393890'>interpreter,</span> <span m='394410'>but</span> <span m='394730'>there's</span>
  <span m='394890'>going</span> <span m='394960'>to</span> <span m='395030'>be</span>
  <span m='395160'>room</span> <span m='395400'>for</span> <span m='395490'>putting</span>
  <span m='395720'>in</span> <span m='395810'>more</span> <span m='396010'>things--</span>
  <span m='396290'>I'm</span> <span m='396480'>going to leave</span> <span m='396740'>out</span>
  <span m='397260'>definition</span> <span m='397650'>and</span> <span m='398040'>assignment,</span>
  <span m='399160'>just</span> <span m='399380'>because</span> <span m='401420'>they</span>
  <span m='401540'>are</span> <span m='401560'>not</span> <span m='401760'>essential,</span>
  <span m='404520'>for a</span> <span m='404710'>mathematical</span> <span m='405310'>reason</span>
  <span m='405630'>I'll</span> <span m='405780'>show</span> <span m='405930'>you</span>
  <span m='406080'>later</span> <span m='406920'>and</span> <span m='407180'>also</span>
  <span m='408960'>they</span> <span m='409220'>take</span> <span m='409390'>up</span>
  <span m='409440'>more</span> <span m='409590'>space.</span> </p><p><span m='411670'>But,</span>
  <span m='412090'>in</span> <span m='412140'>any</span> <span m='412340'>case,</span>
  <span m='412850'>what do</span> <span m='413030'>we</span> <span m='413160'>have</span>
  <span m='413300'>to</span> <span m='413410'>do?</span> <span m='414170'>We</span>
  <span m='414280'>have</span> <span m='414410'>to</span> <span m='414540'>do</span>
  <span m='414980'>a</span> <span m='415080'>dispatch</span> <span m='416130'>which</span>
  <span m='416370'>breaks</span> <span m='416680'>the</span> <span m='416820'>types</span>
  <span m='417090'>of</span> <span m='417160'>expressions</span> <span m='417710'>up</span>
  <span m='418330'>into</span> <span m='419310'>particular</span> <span m='419840'>classes.</span>
  <span m='422030'>So</span> <span m='422310'>that's what</span> <span m='422390'>we're</span>
  <span m='422580'>going</span> <span m='422660'>to have</span> <span m='422950'>here.</span>
  <span m='423525'>Well,</span> <span m='423850'>what</span> <span m='424100'>expressions</span>
  <span m='424620'>are</span> <span m='424820'>there?</span> <span m='425150'>Let's</span>
  <span m='425350'>look</span> <span m='425440'>at</span> <span m='425540'>the</span>
  <span m='425610'>kinds</span> <span m='425820'>of</span> <span m='425890'>expressions.</span>
  </p><p><span m='426810'>We</span> <span m='426970'>can</span> <span m='427090'>have</span>
  <span m='427320'>things</span> <span m='427620'>like</span> <span m='428530'>the</span>
  <span m='428660'>numeral</span> <span m='429200'>three.</span> <span m='430420'>What</span>
  <span m='430570'>do I</span> <span m='430690'>want</span> <span m='430950'>that</span>
  <span m='431130'>to</span> <span m='431210'>do?</span> <span m='432720'>I</span>
  <span m='432850'>can</span> <span m='432980'>make</span> <span m='433170'>choices,</span>
  <span m='433670'>but</span> <span m='433770'>I</span> <span m='433880'>think</span>
  <span m='434110'>right</span> <span m='434380'>now,</span> <span m='435130'>I</span>
  <span m='435230'>want</span> <span m='435560'>it to</span> <span m='435640'>be</span>
  <span m='435790'>a</span> <span m='435840'>three.</span> <span m='437050'>That's</span>
  <span m='437170'>what</span> <span m='437260'>I</span> <span m='437360'>want.</span>
  <span m='438860'>So</span> <span m='439050'>that's</span> <span m='439170'>easy</span>
  <span m='439380'>enough.</span> <span m='439800'>That</span> <span m='440050'>means</span>
  <span m='440550'>I</span> <span m='440860'>want,</span> <span m='441710'>if</span>
  <span m='441900'>the</span> <span m='441990'>thing</span> <span m='442180'>is</span>
  <span m='442270'>a</span> <span m='442350'>number,</span> <span m='447050'>the</span>
  <span m='447520'>expression,</span> <span m='449490'>that</span> <span m='449720'>I</span>
  <span m='449850'>want</span> <span m='450180'>the</span> <span m='450250'>expression</span>
  <span m='450720'>itself</span> <span m='451080'>as</span> <span m='451230'>the</span>
  <span m='451380'>answer.</span> </p><p><span m='455420'>Now</span> <span m='455570'>the</span>
  <span m='455750'>next</span> <span m='455940'>possibility</span> <span m='456930'>is</span>
  <span m='457130'>things</span> <span m='457410'>that</span> <span m='457560'>we</span>
  <span m='457700'>represent</span> <span m='458200'>as</span> <span m='458430'>symbols.</span>
  <span m='459390'>Examples</span> <span m='459675'>of</span> <span m='460060'>symbols</span>
  <span m='460540'>are</span> <span m='460730'>things</span> <span m='461090'>like</span>
  <span m='461710'>x,</span> <span m='462860'>n,</span> <span m='463890'>eval,</span>
  <span m='464980'>number,</span> <span m='465345'>x.</span> <span m='467614'>What</span>
  <span m='468090'>do</span> <span m='468320'>I</span> <span m='468400'>mean</span>
  <span m='468630'>them</span> <span m='468740'>to be?</span> <span m='469630'>Those</span>
  <span m='470460'>are</span> <span m='470520'>things</span> <span m='470710'>that</span>
  <span m='470890'>stand</span> <span m='471080'>for</span> <span m='471190'>other</span>
  <span m='471340'>things.</span> <span m='471690'>Those</span> <span m='471880'>are
  the</span> <span m='471980'>variables</span> <span m='472490'>of</span> <span m='472580'>our</span>
  <span m='472710'>language.</span> </p><p><span m='474770'>And</span> <span m='474980'>so</span>
  <span m='475170'>I</span> <span m='475260'>want</span> <span m='475400'>to</span>
  <span m='475540'>be</span> <span m='475720'>able</span> <span m='475850'>to</span>
  <span m='475910'>say,</span> <span m='476200'>for</span> <span m='476370'>example,</span>
  <span m='477040'>that</span> <span m='477900'>x,</span> <span m='478390'>for</span>
  <span m='478540'>example,</span> <span m='478910'>transforms</span> <span m='479205'>to</span>
  <span m='479500'>it's</span> <span m='479670'>value</span> <span m='480130'>which</span>
  <span m='480340'>might</span> <span m='480560'>be</span> <span m='480670'>three.</span>
  <span m='482930'>Or</span> <span m='483120'>I</span> <span m='483190'>might</span>
  <span m='483430'>ask</span> <span m='483570'>something</span> <span m='484000'>like</span>
  <span m='485180'>car.</span> <span m='487920'>I</span> <span m='488080'>want</span>
  <span m='488330'>to</span> <span m='488400'>have</span> <span m='488570'>as</span>
  <span m='488650'>its</span> <span m='488830'>value--</span> <span m='489710'>be</span>
  <span m='489830'>something</span> <span m='490260'>like</span> <span m='490520'>some</span>
  <span m='490720'>procedure,</span> <span m='496730'>which</span> <span m='496970'>I</span>
  <span m='497100'>don't</span> <span m='497280'>know</span> <span m='497380'>what</span>
  <span m='497560'>is</span> <span m='497750'>inside</span> <span m='498220'>there,</span>
  <span m='498660'>perhaps</span> <span m='499050'>a</span> <span m='499120'>machine</span>
  <span m='499450'>language</span> <span m='499790'>code</span> <span m='500270'>or</span>
  <span m='500440'>something</span> <span m='500760'>like</span> <span m='500970'>that.</span>
  <span m='503100'>So,</span> <span m='503530'>well,</span> <span m='503660'>that's
  easy</span> <span m='503930'>enough.</span> <span m='504430'>I'm</span> <span m='504600'>going</span>
  <span m='504770'>to</span> <span m='504960'>push</span> <span m='505160'>that</span>
  <span m='505330'>off</span> <span m='506040'>on</span> <span m='506230'>someone</span>
  <span m='506570'>else.</span> <span m='507890'>If</span> <span m='508030'>something</span>
  <span m='508340'>is a</span> <span m='508420'>symbol,</span> <span m='510840'>if</span>
  <span m='511020'>the</span> <span m='511160'>expression</span> <span m='511690'>is</span>
  <span m='511800'>a</span> <span m='511860'>symbol,</span> <span m='513370'>then</span>
  <span m='513630'>I</span> <span m='513730'>want</span> <span m='513970'>the</span>
  <span m='514100'>answer</span> <span m='514380'>to</span> <span m='514450'>be</span>
  <span m='514549'>the</span> <span m='514640'>result,</span> <span m='514929'>looking</span>
  <span m='515370'>up</span> <span m='517980'>the</span> <span m='518140'>expression</span>
  <span m='519400'>in</span> <span m='519539'>the</span> <span m='519679'>environment.</span>
  </p><p><span m='526480'>Now</span> <span m='526610'>the</span> <span m='526750'>environment</span>
  <span m='528020'>is</span> <span m='528220'>a</span> <span m='528280'>dictionary</span>
  <span m='530010'>which</span> <span m='530310'>maps</span> <span m='531200'>the</span>
  <span m='532410'>symbol</span> <span m='532870'>names</span> <span m='533210'>to</span>
  <span m='533310'>their</span> <span m='533470'>values.</span> <span m='534060'>And</span>
  <span m='534330'>that's</span> <span m='534580'>all</span> <span m='534840'>it</span>
  <span m='534890'>is.</span> <span m='536280'>How</span> <span m='536570'>it's</span>
  <span m='536760'>done?</span> <span m='537530'>Well, we'll</span> <span m='537770'>see</span>
  <span m='537940'>that</span> <span m='538160'>later.</span> <span m='539760'>It's</span>
  <span m='539970'>very</span> <span m='540220'>easy.</span> <span m='541670'>It's</span>
  <span m='541890'>easy</span> <span m='542160'>to</span> <span m='542250'>make</span>
  <span m='542450'>data</span> <span m='542640'>structures</span> <span m='543020'>that
  are</span> <span m='543180'>tables</span> <span m='543550'>of</span> <span m='543630'>various</span>
  <span m='543990'>sorts.</span> <span m='544670'>But it's</span> <span m='545120'>only</span>
  <span m='545370'>a</span> <span m='545430'>table,</span> <span m='545790'>and</span>
  <span m='545900'>this</span> <span m='546050'>is</span> <span m='546120'>the</span>
  <span m='546250'>access</span> <span m='546640'>routine</span> <span m='546970'>for</span>
  <span m='547080'>some</span> <span m='547280'>table.</span> </p><p><span m='550040'>Well,</span>
  <span m='550220'>the</span> <span m='550400'>next</span> <span m='550590'>thing,</span>
  <span m='551400'>another</span> <span m='551640'>kind</span> <span m='551850'>of</span>
  <span m='551940'>expression--</span> <span m='552720'>you</span> <span m='552880'>have</span>
  <span m='553040'>things</span> <span m='553260'>that</span> <span m='553430'>are</span>
  <span m='553660'>described</span> <span m='554180'>constants</span> <span m='554710'>that</span>
  <span m='554790'>are</span> <span m='554870'>not</span> <span m='555110'>numbers,</span>
  <span m='556150'>like</span> <span m='557180'>'foo.</span> <span m='560170'>Well,</span>
  <span m='560410'>for</span> <span m='560510'>my</span> <span m='560740'>convenience,</span>
  <span m='561370'>I</span> <span m='561470'>want</span> <span m='561660'>to</span>
  <span m='561710'>syntactically</span> <span m='562450'>transform</span> <span m='563060'>that</span>
  <span m='564800'>into</span> <span m='565670'>a</span> <span m='566200'>list</span>
  <span m='566430'>structure</span> <span m='566850'>which</span> <span m='567060'>is,</span>
  <span m='567200'>quote</span> <span m='571060'>foo.</span> </p><p><span m='575140'>A</span>
  <span m='575470'>quoted</span> <span m='575800'>object,</span> <span m='576280'>whatever</span>
  <span m='576650'>it</span> <span m='576700'>is,</span> <span m='578420'>is</span>
  <span m='578640'>going</span> <span m='578930'>to</span> <span m='579050'>be</span>
  <span m='579340'>actually</span> <span m='579800'>an</span> <span m='579950'>abbreviation,</span>
  <span m='581090'>which</span> <span m='581330'>is</span> <span m='581430'>not</span>
  <span m='581650'>part</span> <span m='581770'>of the</span> <span m='581890'>evaluator</span>
  <span m='583310'>but</span> <span m='583550'>happens</span> <span m='583870'>somewhere</span>
  <span m='584190'>else,</span> <span m='584870'>an</span> <span m='584990'>abbreviation</span>
  <span m='585980'>for</span> <span m='586410'>an</span> <span m='586480'>expression</span>
  <span m='586960'>that</span> <span m='587080'>looks</span> <span m='587280'>like</span>
  <span m='587500'>this.</span> <span m='588780'>This</span> <span m='589140'>way,</span>
  <span m='589330'>I</span> <span m='589470'>can</span> <span m='589720'>test</span>
  <span m='590090'>for</span> <span m='590550'>the</span> <span m='590790'>type of</span>
  <span m='591110'>the</span> <span m='591230'>expression</span> <span m='591940'>as</span>
  <span m='592120'>being</span> <span m='592340'>a</span> <span m='592400'>quotation</span>
  <span m='593220'>by</span> <span m='593580'>examining</span> <span m='594490'>the</span>
  <span m='594780'>car</span> <span m='595120'>of</span> <span m='595220'>the</span>
  <span m='595330'>expression.</span> <span m='598460'>So</span> <span m='598670'>I'm</span>
  <span m='598790'>not</span> <span m='598950'>going</span> <span m='599020'>to</span>
  <span m='599090'>worry</span> <span m='599360'>about</span> <span m='599620'>that</span>
  <span m='599750'>in</span> <span m='599890'>the</span> <span m='600150'>evaluator.</span>
  <span m='601650'>It's</span> <span m='601780'>happening</span> <span m='602080'>somewhere</span>
  <span m='602250'>earlier</span> <span m='602710'>in</span> <span m='602780'>the</span>
  <span m='602870'>reader</span> <span m='603220'>or</span> <span m='603330'>something.</span>
  </p><p><span m='605540'>If</span> <span m='607680'>the</span> <span m='608060'>expression</span>
  <span m='610580'>of</span> <span m='610920'>the</span> <span m='611030'>expression</span>
  <span m='613820'>is</span> <span m='614680'>quote,</span> <span m='618310'>then</span>
  <span m='618500'>what</span> <span m='618620'>I</span> <span m='618920'>want,</span>
  <span m='620800'>I</span> <span m='621020'>want</span> <span m='621250'>quote</span>
  <span m='621570'>foo</span> <span m='622090'>to</span> <span m='622350'>itself</span>
  <span m='622950'>evaluate</span> <span m='623600'>to</span> <span m='624313'>foo.</span>
  <span m='625140'>It's</span> <span m='625320'>a</span> <span m='625380'>constant.</span>
  <span m='627530'>This</span> <span m='627720'>is</span> <span m='627810'>just</span>
  <span m='628020'>a</span> <span m='628100'>way</span> <span m='628420'>of</span>
  <span m='628520'>saying</span> <span m='629080'>that</span> <span m='629290'>this</span>
  <span m='629500'>evaluates</span> <span m='630170'>to</span> <span m='630360'>itself.</span>
  <span m='633150'>What</span> <span m='633340'>is</span> <span m='633460'>that?</span>
  <span m='633660'>That's</span> <span m='633960'>the</span> <span m='635380'>second</span>
  <span m='635880'>of</span> <span m='636070'>the</span> <span m='636130'>list.</span>
  <span m='636560'>It's the</span> <span m='636800'>second</span> <span m='637040'>element</span>
  <span m='637180'>of the</span> <span m='637330'>list.</span> <span m='638510'>The</span>
  <span m='638880'>second</span> <span m='639130'>element</span> <span m='639455'>of
  the list is it's</span> <span m='639780'>CADR.</span> <span m='641250'>So</span>
  <span m='641550'>I'm just going to  write</span> <span m='641820'>here,</span> <span
  m='641970'>CADR.</span> </p><p><span m='651290'>What</span> <span m='651470'>else</span>
  <span m='651670'>do</span> <span m='651770'>we</span> <span m='651870'>have</span>
  <span m='652120'>here?</span> <span m='652510'>We</span> <span m='652650'>have</span>
  <span m='652820'>lambda</span> <span m='653160'>expressions,</span> <span m='654890'>for</span>
  <span m='655230'>example,</span> <span m='656040'>lambda</span> <span m='656510'>of</span>
  <span m='662240'>x</span> <span m='662420'>plus</span> <span m='662660'>x</span>
  <span m='662850'>y.</span> <span m='664160'>Well,</span> <span m='664350'>I going</span>
  <span m='664660'>have to</span> <span m='664800'>have some</span> <span m='664990'>representation</span>
  <span m='665700'>for</span> <span m='665790'>the</span> <span m='665910'>procedure</span>
  <span m='666420'>which</span> <span m='666610'>is</span> <span m='666700'>the</span>
  <span m='666820'>value</span> <span m='667200'>of</span> <span m='667290'>an</span>
  <span m='667370'>expression,</span> <span m='668200'>of a</span> <span m='668320'>lambda</span>
  <span m='668610'>expression.</span> <span m='669600'>The</span> <span m='669730'>procedure</span>
  <span m='670140'>here is</span> <span m='670380'>not</span> <span m='670690'>the</span>
  <span m='670780'>expression</span> <span m='671990'>lambda</span> <span m='672320'>x.</span>
  <span m='673030'>That's</span> <span m='673550'>the</span> <span m='673700'>description</span>
  <span m='674240'>of</span> <span m='674350'>it,</span> <span m='674480'>the</span>
  <span m='674600'>textual</span> <span m='675000'>description.</span> </p><p><span
  m='676170'>However,</span> <span m='676760'>what</span> <span m='677040'>what I
  going to</span> <span m='677260'>expect</span> <span m='677720'>to</span> <span
  m='677790'>see</span> <span m='678010'>here</span> <span m='678590'>is</span> <span
  m='678800'>something</span> <span m='679280'>which</span> <span m='679490'>contains</span>
  <span m='679860'>an</span> <span m='680030'>environment</span> <span m='680500'>as</span>
  <span m='680600'>one</span> <span m='680730'>of</span> <span m='680800'>its</span>
  <span m='680930'>parts</span> <span m='683190'>if</span> <span m='683470'>I'm</span>
  <span m='683740'>implementing</span> <span m='684320'>a</span> <span m='684380'>lexical</span>
  <span m='684800'>language.</span> <span m='687360'>And</span> <span m='687550'>so</span>
  <span m='687950'>what</span> <span m='688120'>I'd</span> <span m='688260'>like</span>
  <span m='688450'>to</span> <span m='688550'>see</span> <span m='689240'>is</span>
  <span m='689440'>some</span> <span m='689990'>type</span> <span m='690380'>flags.</span>
  <span m='690790'>I'm</span> <span m='690840'>going to</span> <span m='691150'>have</span>
  <span m='691310'>to</span> <span m='691400'>be able</span> <span m='691610'>to</span>
  <span m='691690'>distinguish</span> <span m='692580'>procedures</span> <span m='693440'>later,</span>
  <span m='694280'>procedures</span> <span m='694860'>which</span> <span m='695050'>were</span>
  <span m='695620'>produced</span> <span m='695950'>by</span> <span m='696070'>lambdas,</span>
  <span m='696830'>from</span> <span m='697010'>ones</span> <span m='697190'>that</span>
  <span m='697300'>may</span> <span m='697420'>be</span> <span m='697570'>primitive.</span>
  <span m='699060'>And</span> <span m='699260'>so</span> <span m='699890'>I'm</span>
  <span m='700100'>going</span> <span m='700300'>to</span> <span m='700380'>have</span>
  <span m='700620'>some</span> <span m='701530'>flag,</span> <span m='701790'>which</span>
  <span m='702170'>I'll</span> <span m='702300'>just</span> <span m='702440'>arbitrarily</span>
  <span m='702900'>call</span> <span m='703110'>closure,</span> <span m='703510'>just</span>
  <span m='703700'>for</span> <span m='703780'>historical</span> <span m='704670'>reasons.</span>
  </p><p><span m='707760'>Now,</span> <span m='707990'>to</span> <span m='708060'>say</span>
  <span m='708320'>what</span> <span m='708580'>parts</span> <span m='708840'>of</span>
  <span m='708920'>this</span> <span m='709090'>are</span> <span m='709170'>important.</span>
  <span m='709920'>I'm</span> <span m='710070'>going to</span> <span m='710230'>need</span>
  <span m='710550'>to</span> <span m='710690'>know</span> <span m='711210'>the</span>
  <span m='711410'>bound</span> <span m='711770'>variable</span> <span m='711970'>list</span>
  <span m='712280'>and</span> <span m='712370'>the</span> <span m='712470'>body.</span>
  <span m='714220'>Well,</span> <span m='714400'>that's</span> <span m='714550'>the</span>
  <span m='714660'>CDR</span> <span m='714830'>of</span> <span m='715090'>this,</span>
  <span m='716100'>so</span> <span m='716260'>it's</span> <span m='716370'>going</span>
  <span m='716540'>to</span> <span m='716710'>be</span> <span m='718120'>x</span>
  <span m='719030'>and</span> <span m='720240'>plus</span> <span m='720870'>x</span>
  <span m='721220'>y</span> <span m='723030'>and</span> <span m='723230'>some</span>
  <span m='723390'>environment.</span> <span m='728170'>Now</span> <span m='728350'>this</span>
  <span m='728550'>is</span> <span m='728690'>not</span> <span m='728930'>something</span>
  <span m='729220'>that</span> <span m='729370'>users</span> <span m='731210'>should</span>
  <span m='731450'>ever</span> <span m='731680'>see,</span> <span m='733620'>this</span>
  <span m='733830'>is</span> <span m='733980'>purely</span> <span m='734390'>a</span>
  <span m='734460'>representation,</span> <span m='735570'>internally,</span> <span
  m='736680'>for</span> <span m='737050'>a</span> <span m='737500'>procedure</span>
  <span m='737940'>object.</span> <span m='738520'>It</span> <span m='738690'>contains</span>
  <span m='739400'>a bound</span> <span m='739800'>variable</span> <span m='740220'>list,</span>
  <span m='740770'>a</span> <span m='740930'>body,</span> <span m='741770'>and an</span>
  <span m='742010'>environment,</span> <span m='743550'>and</span> <span m='743960'>some</span>
  <span m='744180'>type</span> <span m='744440'>tag</span> <span m='744700'>saying,</span>
  <span m='745000'>I</span> <span m='745130'>am</span> <span m='745240'>a</span> <span
  m='745300'>procedure.</span> </p><p><span m='746340'>I'm</span> <span m='746460'>going</span>
  <span m='746530'>to</span> <span m='746590'>make</span> <span m='746830'>one</span>
  <span m='747040'>now.</span> <span m='748080'>So</span> <span m='748440'>if</span>
  <span m='751790'>the</span> <span m='751950'>CAR</span> <span m='753010'>of</span>
  <span m='753410'>the</span> <span m='753810'>expression</span> <span m='757090'>is</span>
  <span m='757650'>quote</span> <span m='758050'>lambda,</span> <span m='763720'>then</span>
  <span m='763850'>what I'm</span> <span m='763980'>going</span> <span m='764100'>to</span>
  <span m='764230'>put</span> <span m='764400'>here</span> <span m='765670'>is--</span>
  <span m='765970'>I'm</span> <span m='766080'>going</span> <span m='766140'>to</span>
  <span m='766200'>make</span> <span m='766360'>a</span> <span m='766420'>list</span>
  <span m='770640'>of</span> <span m='771080'>closure,</span> <span m='774760'>the</span>
  <span m='778320'>CDR</span> <span m='778650'>of</span> <span m='778770'>the</span>
  <span m='778860'>procedure</span> <span m='779970'>description</span> <span m='781670'>was</span>
  <span m='781840'>everything</span> <span m='782100'>except</span> <span m='782390'>the</span>
  <span m='782470'>lambda,</span> <span m='787520'>and</span> <span m='787960'>the</span>
  <span m='788030'>current</span> <span m='788290'>environment.</span> </p><p><span
  m='790250'>This</span> <span m='790580'>implements</span> <span m='791970'>the</span>
  <span m='792240'>rule</span> <span m='792630'>for</span> <span m='792880'>environments</span>
  <span m='794230'>in</span> <span m='794350'>the</span> <span m='794470'>environment</span>
  <span m='794890'>model.</span> <span m='795190'>It</span> <span m='795490'>has</span>
  <span m='795760'>to</span> <span m='795840'>do</span> <span m='796090'>with</span>
  <span m='796250'>construction</span> <span m='796830'>of</span> <span m='796900'>procedures</span>
  <span m='797580'>from</span> <span m='797740'>lambda</span> <span m='797980'>expressions.</span>
  <span m='799210'>The</span> <span m='799600'>environment</span> <span m='800160'>that</span>
  <span m='800300'>was</span> <span m='800430'>around</span> <span m='801540'>at</span>
  <span m='801720'>the</span> <span m='801820'>time</span> <span m='802060'>the</span>
  <span m='802180'>evaluator</span> <span m='802850'>encountered</span> <span m='803110'>the</span>
  <span m='803370'>lambda</span> <span m='803730'>expression</span> <span m='805620'>is</span>
  <span m='805820'>the</span> <span m='805940'>environment</span> <span m='808730'>where</span>
  <span m='808960'>the</span> <span m='809090'>procedure</span> <span m='809540'>resulting</span>
  <span m='810460'>interprets</span> <span m='810990'>it's</span> <span m='811150'>free</span>
  <span m='811410'>variables.</span> <span m='814720'>So</span> <span m='814910'>that's</span>
  <span m='815110'>part</span> <span m='815410'>of</span> <span m='815510'>that.</span>
  <span m='815920'>And</span> <span m='816110'>so</span> <span m='816160'>we</span>
  <span m='816260'>have</span> <span m='816390'>to</span> <span m='816480'>capture</span>
  <span m='816880'>that</span> <span m='817070'>environment</span> <span m='817620'>as</span>
  <span m='817790'>part</span> <span m='817990'>of</span> <span m='818050'>the</span>
  <span m='818120'>procedure</span> <span m='818540'>object.</span> <span m='819210'>And</span>
  <span m='819340'>we'll</span> <span m='819420'>see</span> <span m='819580'>how</span>
  <span m='819690'>that</span> <span m='819820'>gets</span> <span m='819960'>used</span>
  <span m='820200'>later.</span> </p><p><span m='821750'>There</span> <span m='822260'>are</span>
  <span m='822340'>also</span> <span m='822580'>conditional</span> <span m='823110'>expressions</span>
  <span m='824490'>of</span> <span m='824620'>things</span> <span m='824880'>like</span>
  <span m='825140'>COND</span> <span m='827240'>of</span> <span m='827540'>say,</span>
  <span m='828500'>p</span> <span m='828830'>one,</span> <span m='829240'>e</span>
  <span m='829540'>one,</span> <span m='831160'>p</span> <span m='831450'>two,</span>
  <span m='831920'>e</span> <span m='832230'>two.</span> <span m='834520'>Where</span>
  <span m='835080'>this</span> <span m='835430'>is</span> <span m='835610'>a</span>
  <span m='835680'>predicate,</span> <span m='836830'>a</span> <span m='836900'>predicate</span>
  <span m='837100'>is a</span> <span m='837410'>thing that is</span> <span m='837670'>either</span>
  <span m='837840'>true</span> <span m='838030'>or</span> <span m='838110'>false,</span>
  <span m='838990'>and the</span> <span m='839320'>expression</span> <span m='839830'>to</span>
  <span m='839910'>be</span> <span m='840030'>evaluated</span> <span m='840760'>if</span>
  <span m='840930'>the</span> <span m='841030'>predicate is</span> <span m='841470'>true.</span>
  <span m='843480'>A</span> <span m='843580'>set</span> <span m='843750'>of</span>
  <span m='843840'>clauses,</span> <span m='844680'>if</span> <span m='844820'>you
  will,</span> <span m='844970'>that's</span> <span m='845440'>the name for such a</span>
  <span m='845820'>thing.</span> <span m='846790'>So</span> <span m='847720'>I'm</span>
  <span m='847880'>going</span> <span m='848500'>put</span> <span m='848630'>that</span>
  <span m='848830'>somewhere</span> <span m='849150'>else.</span> <span m='849360'>We're</span>
  <span m='849440'>going</span> <span m='849500'>to</span> <span m='849560'>worry</span>
  <span m='849740'>about</span> <span m='850090'>that</span> <span m='850190'>in</span>
  <span m='850330'>another</span> <span m='850890'>piece</span> <span m='851080'>of</span>
  <span m='851150'>code.</span> </p><p><span m='852420'>So</span> <span m='852750'>EQ--</span>
  <span m='855900'>if</span> <span m='856200'>the</span> <span m='856350'>CAR</span>
  <span m='856640'>of the</span> <span m='856730'>expression</span> <span m='860450'>is</span>
  <span m='860680'>COND,</span> <span m='863680'>then</span> <span m='864200'>I'm</span>
  <span m='864300'>going</span> <span m='864470'>to</span> <span m='864570'>do</span>
  <span m='864710'>nothing</span> <span m='865020'>more</span> <span m='865530'>than</span>
  <span m='865700'>evaluate</span> <span m='866160'>the</span> <span m='866250'>COND,</span>
  <span m='869940'>the</span> <span m='870350'>CDR</span> <span m='870510'>of</span>
  <span m='870680'>the</span> <span m='870800'>expression.</span> <span m='874080'>That's</span>
  <span m='875850'>all</span> <span m='876040'>the</span> <span m='876130'>clauses</span>
  <span m='877180'>in</span> <span m='877410'>the</span> <span m='877510'>environment</span>
  <span m='878040'>that  I'm</span> <span m='878220'>given.</span> </p><p><span m='881430'>Well,</span>
  <span m='881590'>there's</span> <span m='881770'>one</span> <span m='881980'>more</span>
  <span m='882190'>case,</span> <span m='884290'>arbitrary</span> <span m='884890'>thing</span>
  <span m='885200'>like</span> <span m='885800'>the</span> <span m='886250'>sum</span>
  <span m='886480'>of</span> <span m='886710'>x</span> <span m='887490'>and</span>
  <span m='887850'>three,</span> <span m='890760'>where</span> <span m='890940'>this</span>
  <span m='891180'>is</span> <span m='892120'>an</span> <span m='892380'>operator</span>
  <span m='893000'>applied</span> <span m='893100'>to</span> <span m='893380'>operands,</span>
  <span m='895180'>and</span> <span m='895300'>there's</span> <span m='895450'>nothing</span>
  <span m='895710'>special</span> <span m='896120'>about</span> <span m='896410'>it.</span>
  <span m='896590'>It's</span> <span m='896800'>not</span> <span m='897030'>one</span>
  <span m='897170'>of</span> <span m='897230'>the</span> <span m='897300'>special</span>
  <span m='897660'>cases,</span> <span m='898310'>the</span> <span m='898450'>special</span>
  <span m='898950'>forms.</span> <span m='899850'>These</span> <span m='900230'>are</span>
  <span m='900350'>the</span> <span m='900440'>special</span> <span m='900890'>forms.</span>
  </p><p><span m='909650'>And</span> <span m='909750'>if</span> <span m='909860'>I
  were</span> <span m='910110'>writing</span> <span m='910460'>here a</span> <span
  m='910730'>professional</span> <span m='911310'>program,</span> <span m='911710'>again,</span>
  <span m='912360'>I</span> <span m='912480'>would</span> <span m='912630'>somehow</span>
  <span m='912970'>make</span> <span m='913180'>this</span> <span m='913350'>data</span>
  <span m='913600'>directed.</span> <span m='914370'>So</span> <span m='914660'>there</span>
  <span m='914760'>wouldn't</span> <span m='915020'>be</span> <span m='915160'>a</span>
  <span m='915230'>sequence</span> <span m='915700'>of</span> <span m='915780'>conditionals</span>
  <span m='916310'>here,</span> <span m='916690'>there'd</span> <span m='916870'>be
  a</span> <span m='917040'>dispatch</span> <span m='917590'>on</span> <span m='917820'>some</span>
  <span m='917950'>bits</span> <span m='919400'>if</span> <span m='919700'>I</span>
  <span m='919770'>were</span> <span m='919860'>trying</span> <span m='920090'>to</span>
  <span m='920160'>do</span> <span m='920290'>this</span> <span m='920940'>in</span>
  <span m='921070'>a</span> <span m='921110'>more</span> <span m='921280'>professional</span>
  <span m='921870'>way.</span> <span m='922360'>So</span> <span m='922540'>that,</span>
  <span m='922610'>in</span> <span m='922720'>fact,</span> <span m='923040'>I</span>
  <span m='923110'>can</span> <span m='923300'>add</span> <span m='923550'>to</span>
  <span m='923630'>the</span> <span m='923770'>thing</span> <span m='924820'>without</span>
  <span m='925310'>changing</span> <span m='925620'>my</span> <span m='925750'>program</span>
  <span m='926180'>much.</span> <span m='926710'>So,</span> <span m='926960'>for</span>
  <span m='927120'>example,</span> <span m='927590'>they</span> <span m='927730'>would</span>
  <span m='927870'>run</span> <span m='928120'>fast,</span> <span m='929090'>but</span>
  <span m='929210'>I'm</span> <span m='929340'>not</span> <span m='929570'>worried</span>
  <span m='929850'>about</span> <span m='930180'>that.</span> </p><p><span m='931280'>Here</span>
  <span m='931440'>we're</span> <span m='931560'>trying</span> <span m='931790'>to</span>
  <span m='931860'>look</span> <span m='932070'>at</span> <span m='932290'>this</span>
  <span m='932810'>in</span> <span m='933010'>its</span> <span m='933400'>entirety.</span>
  <span m='934890'>So</span> <span m='935260'>it's</span> <span m='935430'>else.</span>
  <span m='937360'>Well,</span> <span m='937750'>what</span> <span m='938050'>do we</span>
  <span m='938200'>do?</span> <span m='938560'>In</span> <span m='938720'>this</span>
  <span m='938940'>case,</span> <span m='939640'>I</span> <span m='939750'>have</span>
  <span m='939940'>to</span> <span m='940030'>somehow</span> <span m='940420'>do</span>
  <span m='940610'>an</span> <span m='940700'>addition.</span> <span m='944350'>Well,</span>
  <span m='944550'>I</span> <span m='944640'>could</span> <span m='944810'>find</span>
  <span m='945110'>out</span> <span m='945280'>what</span> <span m='945430'>the</span>
  <span m='945520'>plus</span> <span m='945890'>is.</span> <span m='946565'>I</span>
  <span m='946870'>have</span> <span m='947270'>to</span> <span m='947380'>find</span>
  <span m='947750'>out</span> <span m='948120'>what</span> <span m='948310'>the</span>
  <span m='948430'>x</span> <span m='948650'>and</span> <span m='948720'>the</span>
  <span m='948810'>three</span> <span m='949110'>are.</span> <span m='950550'>And</span>
  <span m='950780'>then</span> <span m='950930'>I have to</span> <span m='951070'>apply</span>
  <span m='951460'>the</span> <span m='951580'>result</span> <span m='952680'>of</span>
  <span m='952850'>finding</span> <span m='953120'>what</span> <span m='953210'>the</span>
  <span m='953330'>plus</span> <span m='953690'>is</span> <span m='954050'>to</span>
  <span m='954560'>the</span> <span m='954700'>result</span> <span m='955340'>of</span>
  <span m='955510'>finding</span> <span m='955830'>out</span> <span m='955910'>what</span>
  <span m='956040'>the</span> <span m='956160'>x</span> <span m='956360'>and the</span>
  <span m='956530'>three</span> <span m='956800'>are.</span> <span m='958020'>We'll</span>
  <span m='958500'>have</span> <span m='958720'>a</span> <span m='958760'>name</span>
  <span m='959020'>for</span> <span m='959110'>that.</span> </p><p><span m='959830'>So
  I'm</span> <span m='960210'>going to</span> <span m='960290'>apply</span> <span
  m='963950'>the</span> <span m='964660'>result</span> <span m='965070'>of</span>
  <span m='965190'>evaluating</span> <span m='968310'>the</span> <span m='968900'>CAR</span>
  <span m='971280'>of</span> <span m='971410'>the</span> <span m='971500'>expression--</span>
  <span m='973270'>the</span> <span m='973410'>car</span> <span m='973740'>of the</span>
  <span m='973890'>expression</span> <span m='974600'>is</span> <span m='974770'>the</span>
  <span m='974890'>operator--</span> <span m='977210'>in</span> <span m='977420'>the</span>
  <span m='977540'>environment</span> <span m='978080'>given.</span> <span m='980480'>So</span>
  <span m='980700'>evaluating</span> <span m='981380'>the</span> <span m='981480'>operator</span>
  <span m='981940'>gets</span> <span m='982190'>me</span> <span m='982300'>the</span>
  <span m='982390'>procedure.</span> <span m='984050'>Now</span> <span m='984400'>I
  have to</span> <span m='984490'>evaluate</span> <span m='984950'>all</span> <span
  m='985110'>the</span> <span m='985230'>operands</span> <span m='985940'>to</span>
  <span m='986020'>get</span> <span m='986240'>the</span> <span m='986370'>arguments.</span>
  <span m='987290'>I'll</span> <span m='987460'>call</span> <span m='987640'>that</span>
  <span m='987910'>EVLIST,</span> <span m='991170'>the</span> <span m='992050'>CDR</span>
  <span m='992850'>of</span> <span m='993050'>the</span> <span m='993160'>operands,</span>
  <span m='994480'>of</span> <span m='994610'>the</span> <span m='994710'>expression,</span>
  <span m='996790'>with</span> <span m='996990'>respect</span> <span m='997510'>to</span>
  <span m='997720'>the</span> <span m='998530'>environment.</span> <span m='1001940'>EVLIST</span>
  <span m='1002360'>will</span> <span m='1002480'>come</span> <span m='1002610'>up</span>
  <span m='1002750'>later--</span> <span m='1003290'>EVLIST,</span> <span m='1003820'>apply,</span>
  <span m='1004980'>COND</span> <span m='1005300'>pair,</span> <span m='1006000'>COND,</span>
  <span m='1007180'>lambda,</span> <span m='1007720'>define.</span> </p><p><span m='1010900'>So</span>
  <span m='1011160'>that</span> <span m='1011340'>what</span> <span m='1011360'>you</span>
  <span m='1011380'>are</span> <span m='1011400'>seeing</span> <span m='1011730'>here</span>
  <span m='1011960'>now</span> <span m='1012720'>is</span> <span m='1012900'>pretty</span>
  <span m='1013110'>much</span> <span m='1013360'>all</span> <span m='1013630'>there</span>
  <span m='1013850'>is</span> <span m='1014820'>in</span> <span m='1015010'>the</span>
  <span m='1015110'>evaluator</span> <span m='1015680'>itself.</span> <span m='1016590'>It's</span>
  <span m='1016790'>the</span> <span m='1017510'>case</span> <span m='1017860'>dispatch</span>
  <span m='1019490'>on</span> <span m='1019770'>the</span> <span m='1019880'>type</span>
  <span m='1020160'>of</span> <span m='1020230'>the</span> <span m='1020290'>expression</span>
  <span m='1021250'>with</span> <span m='1021370'>the</span> <span m='1021490'>default</span>
  <span m='1024900'>being</span> <span m='1025579'>a</span> <span m='1025670'>general</span>
  <span m='1026060'>application</span> <span m='1026869'>or</span> <span m='1027079'>a</span>
  <span m='1027130'>combination.</span> </p><p><span m='1037520'>Now</span> <span
  m='1037690'>there</span> <span m='1037839'>is</span> <span m='1037910'>lots</span>
  <span m='1038180'>of</span> <span m='1038280'>things</span> <span m='1038490'>we</span>
  <span m='1038609'>haven't</span> <span m='1038900'>defined</span> <span m='1039329'>yet.</span>
  <span m='1040089'>Let's</span> <span m='1040250'>just</span> <span m='1040450'>look</span>
  <span m='1040619'>at</span> <span m='1040710'>them</span> <span m='1040829'>and</span>
  <span m='1040910'>see</span> <span m='1041030'>what</span> <span m='1041150'>they</span>
  <span m='1041310'>are.</span> <span m='1041780'>We're</span> <span m='1041920'>going</span>
  <span m='1041980'>to</span> <span m='1042050'>have</span> <span m='1042160'>to</span>
  <span m='1042270'>do</span> <span m='1042440'>this</span> <span m='1042680'>later,</span>
  <span m='1043670'>evcond.</span> <span m='1045480'>We have to</span> <span m='1045859'>write</span>
  <span m='1046050'>apply.</span> <span m='1047579'>We're going to have to</span>
  <span m='1047930'>write</span> <span m='1048369'>EVLIST.</span> <span m='1048800'>We're</span>
  <span m='1049120'>going</span> <span m='1049250'>to</span> <span m='1049590'>write</span>
  <span m='1049840'>LOOKUP.</span> <span m='1051790'>I</span> <span m='1051910'>think</span>
  <span m='1052120'>that's</span> <span m='1052350'>everything,</span> <span m='1052910'>isn't</span>
  <span m='1053220'>there?</span> <span m='1053430'>Everything</span> <span m='1053820'>else</span>
  <span m='1054010'>is</span> <span m='1054130'>something</span> <span m='1054470'>which</span>
  <span m='1054620'>is</span> <span m='1054720'>simple,</span> <span m='1055130'>or</span>
  <span m='1055190'>primitive,</span> <span m='1055860'>or</span> <span m='1056110'>something</span>
  <span m='1056520'>like</span> <span m='1056800'>that.</span> </p><p><span m='1058570'>And,</span>
  <span m='1058980'>of</span> <span m='1059100'>course,</span> <span m='1059760'>we</span>
  <span m='1059920'>could</span> <span m='1060510'>many</span> <span m='1060810'>more</span>
  <span m='1061030'>special</span> <span m='1061370'>forms</span> <span m='1061700'>here,</span>
  <span m='1062020'>but</span> <span m='1062360'>that</span> <span m='1062720'>would
  be</span> <span m='1062850'>a</span> <span m='1062890'>bad</span> <span m='1063150'>idea</span>
  <span m='1063490'>in</span> <span m='1063580'>general</span> <span m='1063990'>in
  a</span> <span m='1064030'>language.</span> <span m='1064450'>You</span> <span m='1064520'>make</span>
  <span m='1064680'>a</span> <span m='1064730'>language</span> <span m='1065040'>very</span>
  <span m='1065240'>complicated</span> <span m='1066080'>by</span> <span m='1066180'>putting</span>
  <span m='1066410'>a</span> <span m='1066480'>lot</span> <span m='1066730'>of</span>
  <span m='1066810'>things</span> <span m='1067090'>in</span> <span m='1067220'>there.</span>
  <span m='1067690'>The</span> <span m='1067900'>number</span> <span m='1068220'>of</span>
  <span m='1068330'>reserve</span> <span m='1068730'>words</span> <span m='1069170'>that</span>
  <span m='1069300'>should</span> <span m='1069420'>exist</span> <span m='1069710'>in</span>
  <span m='1069770'>a</span> <span m='1069830'>language</span> <span m='1070780'>should</span>
  <span m='1070960'>be</span> <span m='1071060'>no</span> <span m='1071210'>more</span>
  <span m='1071430'>than</span> <span m='1071560'>a</span> <span m='1071610'>person</span>
  <span m='1071920'>could</span> <span m='1072000'>remember</span> <span m='1072540'>on</span>
  <span m='1072650'>his</span> <span m='1072780'>fingers</span> <span m='1073100'>and</span>
  <span m='1073220'>toes.</span> <span m='1074010'>And</span> <span m='1074310'>I</span>
  <span m='1074520'>get</span> <span m='1074710'>very</span> <span m='1074880'>upset</span>
  <span m='1075170'>with</span> <span m='1075270'>languages</span> <span m='1075710'>which</span>
  <span m='1076090'>have</span> <span m='1076430'>hundreds</span> <span m='1076820'>of</span>
  <span m='1077330'>reserve</span> <span m='1077760'>words.</span> <span m='1079410'>But</span>
  <span m='1079520'>that's</span> <span m='1079700'>where</span> <span m='1079790'>the</span>
  <span m='1079900'>reserve</span> <span m='1080300'>words</span> <span m='1080570'>go.</span>
  </p><p><span m='1084750'>Well,</span> <span m='1084920'>now</span> <span m='1085100'>let's</span>
  <span m='1085340'>get</span> <span m='1085470'>to</span> <span m='1085550'>the</span>
  <span m='1085830'>next</span> <span m='1086100'>part</span> <span m='1086350'>of</span>
  <span m='1086430'>this,</span> <span m='1086610'>the</span> <span m='1086710'>kernel,</span>
  <span m='1087140'>apply.</span> <span m='1089640'>What</span> <span m='1089880'>else</span>
  <span m='1090130'>is</span> <span m='1090240'>this</span> <span m='1090460'>doing?</span>
  <span m='1091590'>Well,</span> <span m='1091830'>apply's</span> <span m='1092380'>job</span>
  <span m='1093420'>is</span> <span m='1093630'>to</span> <span m='1093750'>take</span>
  <span m='1094190'>a</span> <span m='1094330'>procedure</span> <span m='1095940'>and</span>
  <span m='1096280'>apply</span> <span m='1096620'>it</span> <span m='1096730'>to</span>
  <span m='1096870'>its</span> <span m='1097020'>arguments</span> <span m='1097680'>after</span>
  <span m='1097990'>both</span> <span m='1098250'>have</span> <span m='1098380'>been</span>
  <span m='1098510'>evaluated</span> <span m='1098805'>to</span> <span m='1099100'>come</span>
  <span m='1099230'>up</span> <span m='1099350'>with</span> <span m='1099420'>a</span>
  <span m='1099500'>procedure</span> <span m='1099930'>and the</span> <span m='1100120'>arguments</span>
  <span m='1100980'>rather</span> <span m='1101240'>the</span> <span m='1101370'>operator</span>
  <span m='1101840'>symbols</span> <span m='1102560'>and</span> <span m='1102680'>the</span>
  <span m='1102800'>operand</span> <span m='1103350'>symbols,</span> <span m='1104140'>whatever</span>
  <span m='1104420'>they</span> <span m='1104560'>are--</span> <span m='1105360'>symbolic</span>
  <span m='1106260'>expressions.</span> </p><p><span m='1113270'>So</span> <span m='1113450'>we</span>
  <span m='1113620'>will</span> <span m='1113760'>define</span> <span m='1114420'>apply</span>
  <span m='1118200'>to</span> <span m='1118460'>be</span> <span m='1118690'>a</span>
  <span m='1118950'>procedure</span> <span m='1119830'>of</span> <span m='1120020'>two</span>
  <span m='1120200'>arguments,</span> <span m='1120810'>a</span> <span m='1120940'>procedure</span>
  <span m='1122510'>and</span> <span m='1122940'>arguments.</span> <span m='1127110'>And</span>
  <span m='1127460'>what</span> <span m='1127600'>does</span> <span m='1127740'>it</span>
  <span m='1127830'>do?</span> <span m='1128080'>It</span> <span m='1128160'>does</span>
  <span m='1128350'>nothing</span> <span m='1128680'>very</span> <span m='1128910'>complicated.</span>
  <span m='1129720'>It's</span> <span m='1130010'>got</span> <span m='1130190'>two</span>
  <span m='1130330'>cases.</span> <span m='1133580'>Either</span> <span m='1133950'>the</span>
  <span m='1134120'>procedure</span> <span m='1134570'>is</span> <span m='1134690'>primitive--</span>
  <span m='1142970'>And</span> <span m='1143480'>I</span> <span m='1143760'>don't</span>
  <span m='1143920'>know</span> <span m='1144080'>exactly</span> <span m='1144650'>how</span>
  <span m='1144860'>that</span> <span m='1145770'>is</span> <span m='1145940'>done.</span>
  </p><p><span m='1146930'>It's</span> <span m='1147110'>possible</span> <span m='1147490'>there's</span>
  <span m='1147780'>some</span> <span m='1148180'>type</span> <span m='1149530'>information</span>
  <span m='1150350'>just</span> <span m='1150680'>like</span> <span m='1150850'>we</span>
  <span m='1150930'>made</span> <span m='1151170'>closure</span> <span m='1151770'>for,</span>
  <span m='1152110'>here,</span> <span m='1152620'>being the</span> <span m='1153070'>description</span>
  <span m='1153580'>of</span> <span m='1153670'>the</span> <span m='1153760'>type</span>
  <span m='1154010'>of</span> <span m='1154110'>a</span> <span m='1154170'>compound</span>
  <span m='1154710'>thing--</span> <span m='1156810'>probably</span> <span m='1157290'>so.</span>
  <span m='1158550'>But</span> <span m='1158750'>it is</span> <span m='1158860'>not</span>
  <span m='1159030'>essential</span> <span m='1159450'>how</span> <span m='1159590'>that</span>
  <span m='1159800'>works,</span> <span m='1160720'>and,</span> <span m='1160880'>in</span>
  <span m='1160980'>fact,</span> <span m='1161280'>it</span> <span m='1161360'>turns</span>
  <span m='1161670'>out,</span> <span m='1162250'>as</span> <span m='1162420'>you</span>
  <span m='1162540'>probably</span> <span m='1163010'>know</span> <span m='1163280'>or
  have</span> <span m='1163450'>deduced,</span> <span m='1163950'>that</span> <span
  m='1164050'>you</span> <span m='1164140'>don't</span> <span m='1164260'>need</span>
  <span m='1164410'>any</span> <span m='1164580'>primitives</span> <span m='1164980'>anyway.</span>
  <span m='1167350'>You</span> <span m='1167600'>can</span> <span m='1167730'>compute</span>
  <span m='1167860'>anything</span> <span m='1168570'>without</span> <span m='1169000'>them</span>
  <span m='1170440'>because</span> <span m='1170680'>some of the</span> <span m='1170760'>lambda</span>
  <span m='1172340'>that I've been</span> <span m='1172570'>playing</span> <span m='1172910'>with.</span>
  <span m='1173190'>But</span> <span m='1173810'>it's</span> <span m='1173960'>nice</span>
  <span m='1174210'>to</span> <span m='1174400'>have</span> <span m='1174590'>them.</span>
  </p><p><span m='1174750'>So</span> <span m='1175290'>here</span> <span m='1175630'>we're</span>
  <span m='1175720'>going</span> <span m='1175850'>to do some</span> <span m='1175920'>magic</span>
  <span m='1176380'>which</span> <span m='1176520'>I'm</span> <span m='1176630'>not</span>
  <span m='1176780'>going</span> <span m='1176840'>to</span> <span m='1176900'>explain.</span>
  <span m='1178060'>Go to</span> <span m='1178300'>machine</span> <span m='1178590'>language,</span>
  <span m='1180460'>apply</span> <span m='1180920'>primop.</span> <span m='1182860'>Here's</span>
  <span m='1183200'>how it</span> <span m='1183390'>adds.</span> <span m='1184850'>Execute</span>
  <span m='1184986'>an</span> <span m='1185123'>add</span> <span m='1185260'>instruction.</span>
  <span m='1190360'>However,</span> <span m='1190960'>the</span> <span m='1191100'>interesting</span>
  <span m='1191470'>part</span> <span m='1191660'>of</span> <span m='1191700'>a</span>
  <span m='1191760'>language</span> <span m='1192170'>is</span> <span m='1192270'>the</span>
  <span m='1192380'>glue</span> <span m='1192680'>by</span> <span m='1192840'>which</span>
  <span m='1193000'>the</span> <span m='1193100'>predicates</span> <span m='1193480'>are</span>
  <span m='1193530'>glued</span> <span m='1193790'>together.</span> </p><p><span m='1194940'>So</span>
  <span m='1195110'>let's</span> <span m='1195300'>look</span> <span m='1195420'>at</span>
  <span m='1195550'>that.</span> <span m='1196910'>Well,</span> <span m='1197170'>the</span>
  <span m='1197280'>other</span> <span m='1197430'>possibility</span> <span m='1198820'>is</span>
  <span m='1198960'>that</span> <span m='1199070'>this</span> <span m='1199250'>is</span>
  <span m='1199950'>a</span> <span m='1200080'>compound</span> <span m='1200860'>made</span>
  <span m='1201210'>up</span> <span m='1201480'>by</span> <span m='1201740'>executing</span>
  <span m='1203000'>a</span> <span m='1203110'>lambda</span> <span m='1203430'>expression,</span>
  <span m='1204730'>this</span> <span m='1205140'>is</span> <span m='1205190'>a</span>
  <span m='1206030'>compound</span> <span m='1206430'>procedure.</span> <span m='1207620'>Well,</span>
  <span m='1208070'>we'll</span> <span m='1208420'>check</span> <span m='1208710'>its</span>
  <span m='1208890'>type.</span> <span m='1210110'>If</span> <span m='1210330'>it</span>
  <span m='1210450'>is</span> <span m='1216140'>closure,</span> <span m='1220580'>if</span>
  <span m='1220710'>it's</span> <span m='1220850'>one</span> <span m='1221030'>of</span>
  <span m='1221380'>those,</span> <span m='1222090'>then</span> <span m='1222460'>I</span>
  <span m='1222590'>have</span> <span m='1222710'>to</span> <span m='1222780'>do</span>
  <span m='1222910'>an</span> <span m='1223010'>eval</span> <span m='1223280'>of</span>
  <span m='1223550'>the</span> <span m='1223630'>body.</span> <span m='1224500'>The</span>
  <span m='1224590'>way</span> <span m='1224800'>I</span> <span m='1224970'>do</span>
  <span m='1225210'>this,</span> <span m='1225740'>the</span> <span m='1225960'>way</span>
  <span m='1226100'>I</span> <span m='1226240'>deal</span> <span m='1226520'>with</span>
  <span m='1226670'>this</span> <span m='1226860'>at</span> <span m='1227140'>all,</span>
  <span m='1228270'>is</span> <span m='1228520'>the</span> <span m='1228960'>way</span>
  <span m='1229110'>I</span> <span m='1229250'>evaluate</span> <span m='1229770'>the</span>
  <span m='1229920'>application</span> <span m='1230480'>of</span> <span m='1230550'>a</span>
  <span m='1230620'>procedure</span> <span m='1231000'>to</span> <span m='1231100'>its</span>
  <span m='1231210'>arguments,</span> <span m='1231730'>is</span> <span m='1231910'>by</span>
  <span m='1232050'>evaluating</span> <span m='1232580'>the</span> <span m='1232670'>body</span>
  <span m='1232980'>of the</span> <span m='1233070'>procedure</span> <span m='1234220'>in</span>
  <span m='1234400'>the</span> <span m='1234500'>environment</span> <span m='1234980'>resulting</span>
  <span m='1235450'>from</span> <span m='1235630'>extending</span> <span m='1236260'>the</span>
  <span m='1236380'>environment</span> <span m='1236940'>of</span> <span m='1237050'>the</span>
  <span m='1237160'>procedure</span> <span m='1237930'>with</span> <span m='1238060'>the</span>
  <span m='1238190'>bindings</span> <span m='1239040'>of</span> <span m='1239170'>the</span>
  <span m='1239300'>formal</span> <span m='1239670'>parameters</span> <span m='1241050'>of</span>
  <span m='1241190'>the</span> <span m='1241290'>procedure</span> <span m='1242000'>to</span>
  <span m='1242230'>the</span> <span m='1242410'>arguments</span> <span m='1242890'>that</span>
  <span m='1243010'>were</span> <span m='1243110'>passed</span> <span m='1243430'>to</span>
  <span m='1243540'>it.</span> <span m='1247030'>That</span> <span m='1247370'>was
  a</span> <span m='1247470'>long</span> <span m='1247650'>sentence.</span> </p><p><span
  m='1251130'>Well</span> <span m='1251300'>that's</span> <span m='1251580'>easy</span>
  <span m='1251860'>enough.</span> <span m='1252822'>Now</span> <span m='1253160'>here's</span>
  <span m='1253350'>going</span> <span m='1253410'>to</span> <span m='1253480'>be</span>
  <span m='1253540'>a</span> <span m='1253630'>lot</span> <span m='1253710'>of</span>
  <span m='1253800'>CAR-CDRing.</span> <span m='1256214'>I have</span> <span m='1256660'>to</span>
  <span m='1256800'>get</span> <span m='1256950'>the</span> <span m='1257020'>body</span>
  <span m='1257370'>of</span> <span m='1257460'>the</span> <span m='1257550'>procedure.</span>
  <span m='1259400'>Where's</span> <span m='1259610'>the</span> <span m='1259680'>body
  of</span> <span m='1259970'>the</span> <span m='1260060'>procedure</span> <span
  m='1261840'>in</span> <span m='1262010'>here?</span> <span m='1262960'>Well</span>
  <span m='1263280'>here's</span> <span m='1263500'>the</span> <span m='1263610'>CAR,</span>
  <span m='1264620'>here's</span> <span m='1264890'>the</span> <span m='1264990'>CDR</span>
  <span m='1265330'>is</span> <span m='1265410'>the</span> <span m='1265490'>whole</span>
  <span m='1265660'>rest</span> <span m='1265910'>of</span> <span m='1265950'>this.</span>
  <span m='1266130'>So</span> <span m='1266240'>here's</span> <span m='1266430'>the</span>
  <span m='1266540'>CADR.</span> <span m='1267040'>And</span> <span m='1267680'>so</span>
  <span m='1267810'>I</span> <span m='1267930'>see,</span> <span m='1268140'>what</span>
  <span m='1268260'>I</span> <span m='1268380'>have</span> <span m='1268680'>here</span>
  <span m='1268940'>is</span> <span m='1269050'>the</span> <span m='1269130'>body</span>
  <span m='1269470'>is</span> <span m='1269630'>the</span> <span m='1269970'>second</span>
  <span m='1270450'>element</span> <span m='1270800'>of</span> <span m='1270950'>the</span>
  <span m='1271040'>second</span> <span m='1271430'>element</span> <span m='1271800'>of</span>
  <span m='1272040'>the</span> <span m='1272450'>procedure.</span> <span m='1273200'>So
  it's</span> <span m='1273450'>the</span> <span m='1273530'>CADR</span> <span m='1273770'>of</span>
  <span m='1273880'>the</span> <span m='1273980'>CADR</span> <span m='1274290'>or</span>
  <span m='1274400'>the</span> <span m='1274490'>CADADR.</span> </p><p><span m='1279170'>It's</span>
  <span m='1279380'>the</span> <span m='1279630'>C-A-D-A-D-R,</span> <span m='1286050'>CADADR</span>
  <span m='1287030'>of</span> <span m='1287130'>the</span> <span m='1287230'>procedure.</span>
  <span m='1290260'>To</span> <span m='1290500'>evaluate</span> <span m='1291030'>the</span>
  <span m='1291110'>body</span> <span m='1292390'>in</span> <span m='1292540'>the</span>
  <span m='1292600'>result</span> <span m='1293020'>of</span> <span m='1293150'>binding</span>
  <span m='1294900'>that's</span> <span m='1295170'>making</span> <span m='1295490'>up</span>
  <span m='1295660'>more</span> <span m='1295900'>environment,</span> <span m='1298520'>well
  I need the </span> <span m='1298690'>formal</span> <span m='1299080'>parameters</span>
  <span m='1300270'>of</span> <span m='1300540'>the</span> <span m='1301230'>of</span>
  <span m='1301390'>the</span> <span m='1301550'>procedure,</span> <span m='1302130'>what</span>
  <span m='1302290'>is</span> <span m='1302420'>that?</span> <span m='1303500'>That's</span>
  <span m='1303930'>the</span> <span m='1304070'>CAR</span> <span m='1304500'>of</span>
  <span m='1304610'>the</span> <span m='1304710'>CDR.</span> <span m='1307720'>It's</span>
  <span m='1307860'>horrible</span> <span m='1308350'>isn't</span> <span m='1308550'>it?</span>
  <span m='1312440'>--of</span> <span m='1312700'>the</span> <span m='1312960'>procedure.</span>
  <span m='1315440'>Bind</span> <span m='1315750'>that</span> <span m='1316180'>to</span>
  <span m='1316360'>the</span> <span m='1316530'>arguments</span> <span m='1316930'>that</span>
  <span m='1317020'>were</span> <span m='1317150'>passed</span> <span m='1319820'>in</span>
  <span m='1320080'>the</span> <span m='1320370'>environment,</span> <span m='1321000'>which</span>
  <span m='1321240'>is</span> <span m='1321410'>passed</span> <span m='1321780'>also</span>
  <span m='1322230'>as</span> <span m='1322430'>part</span> <span m='1322730'>of</span>
  <span m='1322960'>the</span> <span m='1323430'>procedure.</span> <span m='1324540'>Well,</span>
  <span m='1324730'>that's</span> <span m='1325010'>the</span> <span m='1325980'>CAR</span>
  <span m='1326430'>of</span> <span m='1326560'>the</span> <span m='1326690'>CDR</span>
  <span m='1327030'>of</span> <span m='1327150'>the</span> <span m='1327200'>CDR</span>
  <span m='1327520'>of</span> <span m='1327620'>this,</span> <span m='1329670'>CADADR,</span>
  <span m='1335080'>of</span> <span m='1335560'>the</span> <span m='1336050'>procedure.</span>
  <span m='1340290'>Bind,</span> <span m='1341300'>eval,</span> <span m='1342050'>pair,</span>
  <span m='1342750'>COND,</span> <span m='1343760'>lamda,</span> <span m='1344410'>define--</span>
  </p><p><span m='1346490'>Now,</span> <span m='1346700'>of</span> <span m='1346770'>course,</span>
  <span m='1347420'>if</span> <span m='1347570'>I</span> <span m='1347640'>were</span>
  <span m='1347750'>being</span> <span m='1348040'>really</span> <span m='1348570'>a</span>
  <span m='1348810'>neat</span> <span m='1349060'>character,</span> <span m='1349370'>and</span>
  <span m='1349900'>I</span> <span m='1350030'>was</span> <span m='1350160'>being</span>
  <span m='1350650'>very</span> <span m='1350840'>careful,</span> <span m='1352240'>I</span>
  <span m='1352340'>would</span> <span m='1352450'>actually</span> <span m='1352800'>put</span>
  <span m='1352980'>an</span> <span m='1353160'>extra</span> <span m='1353490'>case</span>
  <span m='1353830'>here</span> <span m='1354290'>for</span> <span m='1354570'>checking</span>
  <span m='1354930'>for</span> <span m='1355090'>certain</span> <span m='1355310'>errors</span>
  <span m='1355670'>like,</span> <span m='1356180'>did</span> <span m='1356360'>you</span>
  <span m='1356540'>try</span> <span m='1356660'>to</span> <span m='1356790'>apply</span>
  <span m='1357100'>one</span> <span m='1357420'>to</span> <span m='1357840'>an</span>
  <span m='1357910'>argument?</span> <span m='1359000'>You</span> <span m='1359150'>get</span>
  <span m='1359330'>a</span> <span m='1360350'>undefined</span> <span m='1360910'>procedure</span>
  <span m='1361340'>type.</span> <span m='1362570'>So</span> <span m='1362880'>I</span>
  <span m='1363070'>may as well</span> <span m='1363220'>do</span> <span m='1363370'>that</span>
  <span m='1363550'>anyway.</span> <span m='1365500'>--else,</span> <span m='1367530'>some</span>
  <span m='1367770'>sort</span> <span m='1367880'>of</span> <span m='1368030'>error,</span>
  <span m='1375430'>like</span> <span m='1375660'>that.</span> </p><p><span m='1377610'>Now,</span>
  <span m='1377830'>of</span> <span m='1378120'>course,</span> <span m='1378870'>again,</span>
  <span m='1379290'>in</span> <span m='1379480'>some</span> <span m='1379690'>sort</span>
  <span m='1379880'>of</span> <span m='1380450'>more</span> <span m='1380770'>real</span>
  <span m='1381090'>system,</span> <span m='1382620'>written</span> <span m='1382890'>for</span>
  <span m='1383080'>professional</span> <span m='1383690'>reasons,</span> <span m='1385350'>this</span>
  <span m='1385650'>would</span> <span m='1385800'>be</span> <span m='1385970'>written</span>
  <span m='1386770'>with</span> <span m='1387060'>a</span> <span m='1387200'>case</span>
  <span m='1387470'>analysis</span> <span m='1388510'>done</span> <span m='1388720'>by</span>
  <span m='1388880'>some</span> <span m='1389070'>sort</span> <span m='1389170'>of</span>
  <span m='1389280'>dispatch.</span> <span m='1390750'>Over</span> <span m='1391020'>here,</span>
  <span m='1391550'>I</span> <span m='1391680'>would</span> <span m='1391810'>probably</span>
  <span m='1392070'>have</span> <span m='1392250'>other</span> <span m='1392420'>cases</span>
  <span m='1392790'>like,</span> <span m='1392970'>is</span> <span m='1393110'>this</span>
  <span m='1393250'>compiled</span> <span m='1393710'>code?</span> <span m='1396220'>It's</span>
  <span m='1396430'>very</span> <span m='1396600'>important.</span> </p><p><span m='1397020'>I</span>
  <span m='1397130'>might have</span> <span m='1397230'>distinguished</span> <span
  m='1397800'>the</span> <span m='1397900'>kind</span> <span m='1398090'>of</span>
  <span m='1398160'>code</span> <span m='1398410'>that's</span> <span m='1398600'>produced</span>
  <span m='1399530'>by</span> <span m='1400100'>a</span> <span m='1400230'>directly</span>
  <span m='1400610'>evaluating</span> <span m='1401030'>a lambda</span> <span m='1401360'>in</span>
  <span m='1401510'>interpretation</span> <span m='1402950'>from</span> <span m='1403150'>code</span>
  <span m='1403380'>that</span> <span m='1403530'>was</span> <span m='1403880'>produced</span>
  <span m='1404130'>by</span> <span m='1404240'>somebody's</span> <span m='1404650'>compiler</span>
  <span m='1405010'>or</span> <span m='1405190'>something</span> <span m='1405430'>like</span>
  <span m='1405650'>that.</span> <span m='1405880'>And</span> <span m='1406260'>we'll</span>
  <span m='1406370'>talk</span> <span m='1406580'>about</span> <span m='1406810'>that</span>
  <span m='1406990'>later.</span> <span m='1407230'>Or</span> <span m='1407360'>is</span>
  <span m='1407420'>this</span> <span m='1407580'>a</span> <span m='1407670'>piece</span>
  <span m='1407760'>Fortran</span> <span m='1408220'>program</span> <span m='1408530'>I</span>
  <span m='1408620'>have</span> <span m='1408710'>to</span> <span m='1408800'>go off</span>
  <span m='1408920'>and</span> <span m='1409150'>execute.</span> <span m='1410510'>It's</span>
  <span m='1410700'>a</span> <span m='1410830'>perfectly</span> <span m='1410990'>possible</span>
  <span m='1411400'>thing,</span> <span m='1411580'>at</span> <span m='1411660'>this</span>
  <span m='1411820'>point,</span> <span m='1412030'>to</span> <span m='1412090'>do</span>
  <span m='1412250'>that.</span> </p><p><span m='1412920'>In</span> <span m='1413060'>fact,</span>
  <span m='1413980'>in</span> <span m='1414090'>this</span> <span m='1414270'>concrete</span>
  <span m='1414730'>syntax</span> <span m='1415180'>evaluator</span> <span m='1415720'>I'm</span>
  <span m='1415830'>writing</span> <span m='1416070'>here,</span> <span m='1419000'>there's</span>
  <span m='1419340'>an</span> <span m='1419400'>assumption</span> <span m='1419890'>built</span>
  <span m='1420130'>in</span> <span m='1420290'>that this is</span> <span m='1420470'>Lisp,</span>
  <span m='1422600'>because</span> <span m='1422740'>I'm</span> <span m='1422860'>using</span>
  <span m='1423030'>CARs</span> <span m='1423350'>and</span> <span m='1423850'>CDRs.</span>
  <span m='1424360'>CAR means the</span> <span m='1424480'>operator,</span> <span
  m='1425300'>and</span> <span m='1425470'>CDR</span> <span m='1425720'>means</span>
  <span m='1426000'>the</span> <span m='1426130'>operand.</span> <span m='1426750'>In</span>
  <span m='1426920'>the</span> <span m='1427080'>text,</span> <span m='1427960'>there</span>
  <span m='1428190'>is</span> <span m='1428280'>an</span> <span m='1428360'>abstract</span>
  <span m='1428870'>syntax</span> <span m='1429270'>evaluator</span> <span m='1430340'>for</span>
  <span m='1430500'>which</span> <span m='1430770'>these</span> <span m='1431000'>could</span>
  <span m='1431180'>be--</span> <span m='1432160'>these</span> <span m='1432320'>are</span>
  <span m='1432450'>given</span> <span m='1432630'>abstract</span> <span m='1432990'>names</span>
  <span m='1433210'>like</span> <span m='1433350'>operator,</span> <span m='1433640'>and</span>
  <span m='1433930'>operand,</span> <span m='1434310'>and</span> <span m='1434490'>all</span>
  <span m='1434660'>these</span> <span m='1434800'>other</span> <span m='1434960'>things</span>
  <span m='1435190'>are like</span> <span m='1435480'>that.</span> <span m='1436160'>And,</span>
  <span m='1436410'>in that</span> <span m='1436610'>case,</span> <span m='1437090'>you</span>
  <span m='1437230'>could</span> <span m='1437360'>reprogram</span> <span m='1437840'>it</span>
  <span m='1437940'>to</span> <span m='1438040'>be</span> <span m='1438210'>ALGOL</span>
  <span m='1440160'>with</span> <span m='1440320'>no</span> <span m='1440470'>problem.</span>
  </p><p><span m='1443760'>Well,</span> <span m='1443950'>here</span> <span m='1444730'>we</span>
  <span m='1444860'>have</span> <span m='1445040'>added</span> <span m='1445380'>another</span>
  <span m='1445740'>couple</span> <span m='1445990'>of</span> <span m='1446060'>things</span>
  <span m='1447040'>that</span> <span m='1447410'>we</span> <span m='1447510'>haven't</span>
  <span m='1447720'>defined.</span> <span m='1450810'>I</span> <span m='1450930'>don't</span>
  <span m='1451150'>think</span> <span m='1451340'>I'll</span> <span m='1451480'>worry</span>
  <span m='1451710'>about</span> <span m='1451930'>these</span> <span m='1452150'>at</span>
  <span m='1452590'>all,</span> <span m='1453320'>however,</span> <span m='1453610'>this</span>
  <span m='1453800'>one</span> <span m='1453950'>will</span> <span m='1454060'>be</span>
  <span m='1454170'>interesting</span> <span m='1454560'>later.</span> <span m='1457930'>Let's</span>
  <span m='1458130'>just</span> <span m='1458470'>proceed</span> <span m='1458810'>through</span>
  <span m='1458940'>this</span> <span m='1459070'>and</span> <span m='1459160'>get</span>
  <span m='1459290'>it</span> <span m='1459400'>done.</span> <span m='1460550'>There's</span>
  <span m='1460700'>only</span> <span m='1460910'>two</span> <span m='1461030'>more</span>
  <span m='1461180'>blackboards</span> <span m='1461460'>so</span> <span m='1461690'>it</span>
  <span m='1461810'>can't</span> <span m='1461980'>be</span> <span m='1462080'>very</span>
  <span m='1462290'>long.</span> <span m='1467056'>It's</span> <span m='1467550'>carefully</span>
  <span m='1467930'>tailored</span> <span m='1468230'>to</span> <span m='1468280'>exactly</span>
  <span m='1468820'>fit.</span> </p><p><span m='1470070'>Well,</span> <span m='1470300'>what</span>
  <span m='1470410'>do we</span> <span m='1470570'>have</span> <span m='1470720'>left?</span>
  <span m='1470980'>We</span> <span m='1471060'>have</span> <span m='1471190'>to</span>
  <span m='1471280'>define</span> <span m='1471680'>EVLIST,</span> <span m='1472260'>which</span>
  <span m='1472430'>is</span> <span m='1472540'>over</span> <span m='1472770'>here.</span>
  <span m='1473730'>And</span> <span m='1473930'>EVLIST</span> <span m='1474280'>is</span>
  <span m='1474410'>nothing</span> <span m='1474760'>more</span> <span m='1475170'>than</span>
  <span m='1475470'>a</span> <span m='1475540'>map</span> <span m='1477350'>down</span>
  <span m='1477550'>a</span> <span m='1477600'>bunch</span> <span m='1477830'>of</span>
  <span m='1480620'>operands</span> <span m='1481950'>producing</span> <span m='1482600'>arguments.</span>
  <span m='1484240'>But</span> <span m='1484510'>I'm</span> <span m='1484600'>going</span>
  <span m='1484690'>to</span> <span m='1484780'>write</span> <span m='1485000'>it</span>
  <span m='1485080'>out.</span> <span m='1485820'>And</span> <span m='1486040'>one</span>
  <span m='1486170'>of</span> <span m='1486230'>the</span> <span m='1486290'>reasons</span>
  <span m='1486590'>I'm</span> <span m='1486690'>going</span> <span m='1486740'>to</span>
  <span m='1486800'>write</span> <span m='1487000'>this</span> <span m='1487150'>out</span>
  <span m='1487290'>is</span> <span m='1487380'>for a</span> <span m='1487510'>mystical</span>
  <span m='1487930'>reason,</span> <span m='1489920'>which</span> <span m='1490150'>is</span>
  <span m='1490230'>I</span> <span m='1490310'>want</span> <span m='1490440'>to</span>
  <span m='1490570'>make</span> <span m='1490800'>this</span> <span m='1491070'>evaluator</span>
  <span m='1491610'>so</span> <span m='1491820'>simple</span> <span m='1492180'>that</span>
  <span m='1492340'>it can</span> <span m='1492690'>understand</span> <span m='1493110'>itself.</span>
  <span m='1496450'>I'm going to</span> <span m='1496520'>really</span> <span m='1496820'>worry</span>
  <span m='1497100'>about</span> <span m='1497360'>that</span> <span m='1497470'>a</span>
  <span m='1497580'>little</span> <span m='1497810'>bit.</span> </p><p><span m='1500230'>So</span>
  <span m='1500650'>let's</span> <span m='1500800'>write</span> <span m='1501020'>it
  out</span> <span m='1501480'>completely.</span> <span m='1502850'>See,</span> <span
  m='1503010'>I</span> <span m='1503140'>don't</span> <span m='1503470'>want</span>
  <span m='1503600'>to</span> <span m='1503720'>worry</span> <span m='1504040'>about</span>
  <span m='1504270'>whether</span> <span m='1504460'>or</span> <span m='1504500'>not</span>
  <span m='1504750'>the thing</span> <span m='1504890'>can</span> <span m='1505030'>pass</span>
  <span m='1505270'>functional</span> <span m='1505620'>arguments.</span> <span m='1506080'>The</span>
  <span m='1506580'>value</span> <span m='1506900'>evaluator</span> <span m='1507080'>is</span>
  <span m='1507170'>not</span> <span m='1507360'>going</span> <span m='1507420'>to</span>
  <span m='1507490'>use</span> <span m='1507770'>them.</span> <span m='1508980'>The</span>
  <span m='1509090'>evaluator</span> <span m='1509350'>is</span> <span m='1509530'>not</span>
  <span m='1509690'>going</span> <span m='1509760'>to</span> <span m='1509820'>produce</span>
  <span m='1510080'>functional</span> <span m='1510380'>values.</span> <span m='1510880'>So</span>
  <span m='1511210'>even  if</span> <span m='1511320'>there</span> <span m='1511420'>were
  a</span> <span m='1511520'>different,</span> <span m='1511810'>alternative</span>
  <span m='1512310'>language</span> <span m='1512750'>that</span> <span m='1512920'>were</span>
  <span m='1513010'>very</span> <span m='1513200'>close</span> <span m='1513530'>to</span>
  <span m='1513630'>this,</span> <span m='1515210'>this</span> <span m='1515740'>evaluates</span>
  <span m='1516380'>a</span> <span m='1516510'>complex</span> <span m='1516950'>language</span>
  <span m='1517280'>like</span> <span m='1517480'>Scheme</span> <span m='1517840'>which</span>
  <span m='1518040'>does</span> <span m='1518260'>allow</span> <span m='1519330'>procedural</span>
  <span m='1519830'>arguments,</span> <span m='1520180'>procedural</span> <span m='1520610'>values,</span>
  <span m='1522080'>and</span> <span m='1522250'>procedural</span> <span m='1522640'>data.</span>
  </p><p><span m='1524070'>But</span> <span m='1524190'>even</span> <span m='1524410'>if</span>
  <span m='1524490'>I</span> <span m='1524570'>were</span> <span m='1524780'>evaluating</span>
  <span m='1525490'>ALGOL,</span> <span m='1527410'>which</span> <span m='1527570'>doesn't</span>
  <span m='1527840'>allow</span> <span m='1528100'>procedural</span> <span m='1528480'>values,</span>
  <span m='1529550'>I</span> <span m='1529650'>could</span> <span m='1529790'>use</span>
  <span m='1529970'>this</span> <span m='1530060'>evaluator.</span> <span m='1531580'>And</span>
  <span m='1531840'>this</span> <span m='1531940'>evaluator</span> <span m='1532490'>is</span>
  <span m='1532660'>not making any</span> <span m='1532870'>assumptions</span> <span
  m='1533330'>about</span> <span m='1533660'>that.</span> <span m='1534050'>And,</span>
  <span m='1534310'>in</span> <span m='1534450'>fact,</span> <span m='1534660'>if
  this</span> <span m='1534890'>value</span> <span m='1535120'>were to be</span> <span
  m='1535310'>restricted</span> <span m='1536280'>to</span> <span m='1536420'>not</span>
  <span m='1536580'>being</span> <span m='1536710'>able</span> <span m='1536850'>to</span>
  <span m='1536930'>that,</span> <span m='1537120'>it wouldn't</span> <span m='1537240'>matter,</span>
  <span m='1537500'>because it</span> <span m='1537700'>doesn't</span> <span m='1537920'>use</span>
  <span m='1538090'>any</span> <span m='1538250'>of</span> <span m='1538590'>those</span>
  <span m='1539370'>clever</span> <span m='1539650'>things.</span> <span m='1540640'>So</span>
  <span m='1540850'>that's</span> <span m='1541050'>why</span> <span m='1541370'>I'm</span>
  <span m='1541480'>arranging</span> <span m='1541550'>this to be</span> <span m='1541680'>super</span>
  <span m='1542060'>simple.</span> <span m='1544070'>This</span> <span m='1544360'>is
  sort of</span> <span m='1544430'>the</span> <span m='1544590'>kernel of</span> <span
  m='1545010'>all</span> <span m='1545240'>possible</span> <span m='1545610'>language</span>
  <span m='1545970'>evaluators.</span> <span m='1547810'>How</span> <span m='1547960'>about</span>
  <span m='1548190'>that?</span> </p><p><span m='1549420'>Evlist--</span> <span m='1552525'>well,</span>
  <span m='1552960'>what</span> <span m='1553280'>is</span> <span m='1553420'>it?</span>
  <span m='1553820'>It's</span> <span m='1553960'>the</span> <span m='1554030'>procedure</span>
  <span m='1554540'>of</span> <span m='1554670'>two</span> <span m='1554830'>arguments,</span>
  <span m='1555840'>l</span> <span m='1556180'>and an</span> <span m='1556300'>environment,</span>
  <span m='1558180'>where</span> <span m='1558400'>l</span> <span m='1558660'>is</span>
  <span m='1558730'>a</span> <span m='1558790'>list</span> <span m='1559480'>such</span>
  <span m='1559890'>that</span> <span m='1560210'>if</span> <span m='1564070'>the</span>
  <span m='1564190'>list</span> <span m='1566040'>of</span> <span m='1566260'>arguments</span>
  <span m='1567190'>is</span> <span m='1567660'>the</span> <span m='1567800'>empty</span>
  <span m='1568110'>list,</span> <span m='1570230'>then</span> <span m='1570430'>the</span>
  <span m='1570520'>result</span> <span m='1571790'>is</span> <span m='1571980'>the</span>
  <span m='1572090'>empty</span> <span m='1572380'>list.</span> <span m='1574130'>Otherwise,</span>
  <span m='1578060'>I</span> <span m='1578150'>want</span> <span m='1578420'>to</span>
  <span m='1578570'>cons</span> <span m='1578990'>up</span> <span m='1580920'>the</span>
  <span m='1580980'>result</span> <span m='1581390'>of</span> <span m='1581480'>evaluating</span>
  <span m='1588180'>the</span> <span m='1588390'>CAR</span> <span m='1588770'>of</span>
  <span m='1588890'>the</span> <span m='1589180'>list</span> <span m='1589450'>of</span>
  <span m='1589900'>operands</span> <span m='1591620'>in</span> <span m='1591780'>the</span>
  <span m='1591880'>environment.</span> <span m='1593260'>So</span> <span m='1593500'>I</span>
  <span m='1593560'>want</span> <span m='1593760'>the</span> <span m='1593980'>first</span>
  <span m='1594290'>operand</span> <span m='1594900'>evaluated,</span> <span m='1596000'>and</span>
  <span m='1596150'>I'm</span> <span m='1596220'>going</span> <span m='1596290'>to</span>
  <span m='1596360'>make</span> <span m='1596530'>a</span> <span m='1596590'>list</span>
  <span m='1596970'>of</span> <span m='1597310'>the</span> <span m='1597770'>results</span>
  <span m='1599020'>by</span> <span m='1599210'>CONSing</span> <span m='1599690'>that</span>
  <span m='1599970'>onto</span> <span m='1600250'>the</span> <span m='1600360'>result</span>
  <span m='1600735'>of</span> <span m='1601110'>this</span> <span m='1601430'>EVLISTing</span>
  <span m='1604450'>as</span> <span m='1604590'>a</span> <span m='1604640'>CDR</span>
  <span m='1605020'>recursion,</span> <span m='1605985'>the</span> <span m='1606410'>CDR</span>
  <span m='1608070'>of</span> <span m='1608210'>the</span> <span m='1608290'>list</span>
  <span m='1608880'>relative</span> <span m='1609200'>to the</span> <span m='1609340'>same</span>
  <span m='1609570'>environment.</span> <span m='1613350'>Evlist,</span> <span m='1614620'>cons,</span>
  <span m='1615250'>else,</span> <span m='1615910'>COND,</span> <span m='1616620'>lambda,</span>
  <span m='1617760'>define--</span> </p><p><span m='1620950'>And</span> <span m='1621200'>I</span>
  <span m='1621290'>have</span> <span m='1621490'>one</span> <span m='1621720'>more</span>
  <span m='1621950'>that</span> <span m='1622080'>I</span> <span m='1622150'>want</span>
  <span m='1622310'>to</span> <span m='1622470'>put</span> <span m='1622610'>on</span>
  <span m='1622730'>the</span> <span m='1622800'>blackboard.</span> <span m='1623620'>It's</span>
  <span m='1623870'>the</span> <span m='1624170'>essence</span> <span m='1624480'>of</span>
  <span m='1624550'>this</span> <span m='1624680'>whole</span> <span m='1624880'>thing.</span>
  <span m='1625470'>And</span> <span m='1625930'>there's</span> <span m='1626100'>some</span>
  <span m='1626290'>sort</span> <span m='1626460'>of</span> <span m='1627170'>next</span>
  <span m='1627450'>layer</span> <span m='1627740'>down.</span> <span m='1634540'>Conditionals--</span>
  <span m='1635770'>conditionals</span> <span m='1636190'>are the</span> <span m='1636390'>only</span>
  <span m='1636600'>thing</span> <span m='1636820'>left</span> <span m='1637090'>that</span>
  <span m='1637200'>are</span> <span m='1637290'>sort</span> <span m='1637440'>of</span>
  <span m='1637500'>substantial.</span> <span m='1638880'>Then</span> <span m='1639220'>below</span>
  <span m='1639540'>that,</span> <span m='1639810'>we</span> <span m='1639900'>have</span>
  <span m='1640040'>to</span> <span m='1640140'>worry</span> <span m='1640420'>about</span>
  <span m='1641040'>things</span> <span m='1641410'>like</span> <span m='1641850'>lookup</span>
  <span m='1642320'>and</span> <span m='1642530'>bind,</span> <span m='1643110'>and</span>
  <span m='1643780'>we'll</span> <span m='1644430'>look</span> <span m='1644540'>at</span>
  <span m='1644640'>that</span> <span m='1644820'>in a</span> <span m='1644870'>second.</span>
  <span m='1645530'>But</span> <span m='1645720'>of</span> <span m='1645830'>the</span>
  <span m='1645930'>substantial</span> <span m='1646490'>stuff</span> <span m='1646730'>at</span>
  <span m='1646880'>this</span> <span m='1647070'>level</span> <span m='1647340'>of</span>
  <span m='1647420'>detail,</span> <span m='1648740'>next</span> <span m='1649030'>important</span>
  <span m='1649360'>thing</span> <span m='1649480'>is</span> <span m='1649570'>how</span>
  <span m='1649650'>you</span> <span m='1649740'>deal</span> <span m='1649910'>with</span>
  <span m='1650000'>conditionals.</span> </p><p><span m='1651600'>Well,</span> <span
  m='1651860'>how</span> <span m='1652020'>do</span> <span m='1652080'>we</span> <span
  m='1652200'>have</span> <span m='1652480'>a</span> <span m='1652540'>conditional</span>
  <span m='1653000'>thing?</span> <span m='1657670'>It's</span> <span m='1657900'>a</span>
  <span m='1657970'>procedure</span> <span m='1659520'>of</span> <span m='1659900'>a</span>
  <span m='1660060'>set</span> <span m='1660210'>of</span> <span m='1660300'>clauses</span>
  <span m='1664150'>and</span> <span m='1664320'>an</span> <span m='1664390'>environment.</span>
  <span m='1667340'>And</span> <span m='1667800'>what</span> <span m='1668020'>does</span>
  <span m='1668130'>it</span> <span m='1668240'>do?</span> <span m='1669820'>It</span>
  <span m='1670020'>says,</span> <span m='1673860'>if</span> <span m='1674050'>I've</span>
  <span m='1674590'>no</span> <span m='1674730'>more</span> <span m='1674930'>clauses,</span>
  <span m='1682350'>well,</span> <span m='1682690'>I</span> <span m='1683070'>have
  to</span> <span m='1683130'>give</span> <span m='1683310'>this</span> <span m='1683480'>a</span>
  <span m='1683550'>value.</span> <span m='1684520'>It</span> <span m='1684870'>could</span>
  <span m='1685050'>be</span> <span m='1685230'>that it</span> <span m='1685370'>was</span>
  <span m='1685490'>an</span> <span m='1685580'>error.</span> <span m='1686540'>Supposing</span>
  <span m='1687050'>it</span> <span m='1687290'>run</span> <span m='1687430'>off</span>
  <span m='1687580'>the</span> <span m='1687710'>end</span> <span m='1687850'>of</span>
  <span m='1687980'>a</span> <span m='1688030'>conditional,</span> <span m='1689210'>it's</span>
  <span m='1689420'>pretty</span> <span m='1689610'>arbitrary.</span> <span m='1690060'>It's</span>
  <span m='1690180'>up</span> <span m='1690330'>to</span> <span m='1690460'>me</span>
  <span m='1690650'>as</span> <span m='1690770'>programmer</span> <span m='1691240'>to</span>
  <span m='1691320'>choose</span> <span m='1691860'>what</span> <span m='1692000'>I</span>
  <span m='1692160'>want to</span> <span m='1692330'>happen.</span> <span m='1693650'>It's</span>
  <span m='1693770'>convenient</span> <span m='1694200'>for</span> <span m='1694290'>me,</span>
  <span m='1694450'>right</span> <span m='1694660'>now,</span> <span m='1694870'>to</span>
  <span m='1695010'>write</span> <span m='1695240'>down</span> <span m='1695650'>that</span>
  <span m='1695820'>this</span> <span m='1695940'>has</span> <span m='1696120'>a</span>
  <span m='1696170'>value</span> <span m='1696600'>which</span> <span m='1696780'>is</span>
  <span m='1696850'>the</span> <span m='1697000'>empty</span> <span m='1697280'>list,</span>
  <span m='1698210'>doesn't</span> <span m='1698500'>matter.</span> <span m='1700100'>For</span>
  <span m='1700240'>error</span> <span m='1700470'>checking,</span> <span m='1700850'>some</span>
  <span m='1701080'>people</span> <span m='1701330'>might</span> <span m='1701530'>prefer</span>
  <span m='1702110'>something</span> <span m='1702470'>else.</span> </p><p><span m='1703110'>But</span>
  <span m='1703300'>the</span> <span m='1703390'>interesting</span> <span m='1703760'>things</span>
  <span m='1703920'>are</span> <span m='1704020'>the</span> <span m='1704140'>following</span>
  <span m='1704480'>ones.</span> <span m='1705570'>If</span> <span m='1706200'>I've</span>
  <span m='1706340'>got</span> <span m='1706560'>an</span> <span m='1706900'>else</span>
  <span m='1707175'>clause--</span> <span m='1711420'>You</span> <span m='1711510'>see,</span>
  <span m='1711640'>if I have</span> <span m='1711780'>a</span> <span m='1711810'>list</span>
  <span m='1711990'>of</span> <span m='1712090'>clauses,</span> <span m='1712790'>then</span>
  <span m='1713410'>each</span> <span m='1713610'>clause</span> <span m='1713960'>is</span>
  <span m='1714060'>a</span> <span m='1714120'>list.</span> <span m='1715480'>And</span>
  <span m='1715710'>so</span> <span m='1716060'>the</span> <span m='1716710'>predicate</span>
  <span m='1717090'>part</span> <span m='1717340'>is</span> <span m='1717480'>the</span>
  <span m='1717600'>CAAR</span> <span m='1719670'>of</span> <span m='1719820'>the</span>
  <span m='1719900'>clauses.</span> <span m='1723560'>It's</span> <span m='1723810'>the</span>
  <span m='1724390'>CAR,</span> <span m='1724720'>which</span> <span m='1725050'>is</span>
  <span m='1725230'>the</span> <span m='1725320'>first</span> <span m='1725630'>part</span>
  <span m='1726310'>of</span> <span m='1726580'>the</span> <span m='1726690'>first</span>
  <span m='1727140'>clause</span> <span m='1728070'>in</span> <span m='1728200'>the</span>
  <span m='1728250'>list</span> <span m='1728460'>of</span> <span m='1728530'>clauses.</span>
  <span m='1731090'>If</span> <span m='1731240'>it's</span> <span m='1731360'>an</span>
  <span m='1731470'>else,</span> <span m='1734440'>then it</span> <span m='1734790'>means
  I</span> <span m='1734980'>want</span> <span m='1735170'>my</span> <span m='1735310'>result</span>
  <span m='1735720'>of</span> <span m='1735800'>the</span> <span m='1735900'>conditional</span>
  <span m='1736590'>to</span> <span m='1736810'>be</span> <span m='1736890'>the</span>
  <span m='1736960'>result</span> <span m='1737270'>of</span> <span m='1737340'>evaluating</span>
  <span m='1737900'>the</span> <span m='1737970'>matching</span> <span m='1738400'>expression.</span>
  <span m='1739800'>So</span> <span m='1740150'>I</span> <span m='1740390'>eval</span>
  <span m='1743570'>the</span> <span m='1743740'>CADR.</span> <span m='1747090'>So</span>
  <span m='1747310'>this</span> <span m='1747480'>is</span> <span m='1747650'>the</span>
  <span m='1748870'>first</span> <span m='1749220'>clause,</span> <span m='1749970'>the</span>
  <span m='1750210'>second</span> <span m='1750610'>element</span> <span m='1750980'>of</span>
  <span m='1751090'>it,</span> <span m='1751190'>CADAR--</span> <span m='1752830'>CADAR</span>
  <span m='1753710'>of</span> <span m='1753870'>a</span> <span m='1753930'>CAR--</span>
  <span m='1756360'>of</span> <span m='1756500'>the</span> <span m='1756600'>clauses,</span>
  <span m='1761280'>with</span> <span m='1761460'>respect</span> <span m='1761790'>to
  the</span> <span m='1761900'>environment.</span> </p><p><span m='1766620'>Now</span>
  <span m='1766890'>the</span> <span m='1767090'>next</span> <span m='1767280'>possibility</span>
  <span m='1767830'>is</span> <span m='1767890'>more</span> <span m='1768100'>interesting.</span>
  <span m='1769630'>If</span> <span m='1769840'>it's</span> <span m='1770000'>false,</span>
  <span m='1773140'>if</span> <span m='1773320'>the</span> <span m='1773410'>first</span>
  <span m='1773740'>predicate</span> <span m='1774300'>in</span> <span m='1774410'>the</span>
  <span m='1774490'>predicate</span> <span m='1774860'>list</span> <span m='1775830'>is</span>
  <span m='1776020'>not</span> <span m='1776280'>an</span> <span m='1776410'>else,</span>
  <span m='1776780'>and</span> <span m='1776950'>it's</span> <span m='1777090'>not</span>
  <span m='1777320'>false,</span> <span m='1778125'>if it's</span> <span m='1778390'>not</span>
  <span m='1778770'>the</span> <span m='1778840'>word</span> <span m='1779170'>else,</span>
  <span m='1780170'>and</span> <span m='1780370'>if</span> <span m='1780450'>it's</span>
  <span m='1780630'>not</span> <span m='1781100'>a</span> <span m='1781260'>false</span>
  <span m='1781720'>thing--</span> <span m='1782050'>Let's</span> <span m='1782220'>write</span>
  <span m='1782370'>down</span> <span m='1782580'>what</span> <span m='1782720'>it
  is</span> <span m='1782890'>if it's a</span> <span m='1783120'>false</span> <span
  m='1783350'>thing.</span> <span m='1784360'>If</span> <span m='1784710'>the</span>
  <span m='1785640'>result</span> <span m='1786040'>of</span> <span m='1786150'>evaluating</span>
  <span m='1787200'>the</span> <span m='1787660'>first</span> <span m='1789590'>predicate,</span>
  <span m='1792090'>the</span> <span m='1792560'>clauses--</span> <span m='1795490'>respect</span>
  <span m='1795880'>the</span> <span m='1795990'>environment,</span> <span m='1798380'>if</span>
  <span m='1798550'>that</span> <span m='1798740'>evaluation</span> <span m='1800010'>yields</span>
  <span m='1800460'>false,</span> <span m='1801630'>then</span> <span m='1802070'>it</span>
  <span m='1802140'>means,</span> <span m='1802530'>I</span> <span m='1802660'>want</span>
  <span m='1802760'>to</span> <span m='1802860'>look</span> <span m='1802970'>at</span>
  <span m='1803090'>the</span> <span m='1803260'>next</span> <span m='1803420'>clause.</span>
  <span m='1804180'>So</span> <span m='1804490'>I</span> <span m='1804940'>want to</span>
  <span m='1805180'>discard the</span> <span m='1805350'>first</span> <span m='1805510'>one.</span>
  <span m='1805990'>So</span> <span m='1806365'>we just</span> <span m='1806740'>go</span>
  <span m='1806860'>around</span> <span m='1807120'>loop,</span> <span m='1807710'>evcond,</span>
  <span m='1810030'>the</span> <span m='1810180'>CDR</span> <span m='1810740'>of</span>
  <span m='1810950'>the</span> <span m='1811160'>clauses</span> <span m='1815450'>relative</span>
  <span m='1815650'>to</span> <span m='1815740'>that</span> <span m='1815920'>environment.</span>
  <span m='1821240'>And</span> <span m='1821700'>otherwise,</span> <span m='1824050'>I</span>
  <span m='1824140'>had</span> <span m='1824310'>a</span> <span m='1824370'>true</span>
  <span m='1824590'>clause,</span> <span m='1826970'>in</span> <span m='1827030'>which</span>
  <span m='1827200'>case,</span> <span m='1827450'>what</span> <span m='1827560'>I</span>
  <span m='1827740'>want</span> <span m='1827920'>is</span> <span m='1828060'>to</span>
  <span m='1828210'>evaluate</span> <span m='1831455'>the</span> <span m='1831952'>CADAR</span>
  <span m='1835440'>of</span> <span m='1835590'>the</span> <span m='1835670'>clauses</span>
  <span m='1840120'>relative</span> <span m='1840630'>to</span> <span m='1840710'>that</span>
  <span m='1840880'>environment.</span> </p><p><span m='1848200'>Boy,</span> <span
  m='1848620'>it's</span> <span m='1848780'>almost</span> <span m='1849170'>done.</span>
  <span m='1851210'>It's</span> <span m='1851540'>quite</span> <span m='1851890'>close</span>
  <span m='1852230'>to</span> <span m='1852350'>done.</span> <span m='1853730'>I</span>
  <span m='1853930'>think</span> <span m='1854070'>we're</span> <span m='1854170'>going</span>
  <span m='1854260'>to</span> <span m='1854340'>finish</span> <span m='1855130'>this</span>
  <span m='1855300'>part</span> <span m='1855510'>off.</span> <span m='1856210'>So</span>
  <span m='1856670'>just</span> <span m='1857100'>buzzing</span> <span m='1857520'>through</span>
  <span m='1857680'>this</span> <span m='1857880'>evaluator,</span> <span m='1858690'>but</span>
  <span m='1859060'>so</span> <span m='1859230'>far</span> <span m='1859420'>you're</span>
  <span m='1859530'>seeing</span> <span m='1859750'>almost</span> <span m='1860080'>everything.</span>
  <span m='1861220'>Let's</span> <span m='1861460'>look</span> <span m='1861580'>at</span>
  <span m='1861700'>the</span> <span m='1861900'>next</span> <span m='1863070'>transparency</span>
  <span m='1863750'>here.</span> </p><p><span m='1868980'>Here</span> <span m='1869325'>is</span>
  <span m='1869670'>bind.</span> <span m='1871980'>Bind</span> <span m='1872380'>is</span>
  <span m='1873250'>for</span> <span m='1873360'>making</span> <span m='1873770'>more</span>
  <span m='1873990'>table.</span> <span m='1875460'>And</span> <span m='1875600'>what
  we are going</span> <span m='1875840'>to</span> <span m='1876000'>do</span> <span
  m='1876250'>here</span> <span m='1877060'>is</span> <span m='1877270'>make</span>
  <span m='1878130'>a--</span> <span m='1879260'>we're</span> <span m='1879410'>going</span>
  <span m='1879500'>to</span> <span m='1879590'>make</span> <span m='1879930'>a</span>
  <span m='1880000'>no-frame</span> <span m='1881420'>for an</span> <span m='1881630'>environment</span>
  <span m='1882120'>structure.</span> <span m='1882800'>The</span> <span m='1882950'>environment</span>
  <span m='1883440'>structure</span> <span m='1884090'>is</span> <span m='1884260'>going</span>
  <span m='1884360'>to</span> <span m='1884460'>be</span> <span m='1884560'>represented</span>
  <span m='1885930'>as</span> <span m='1886170'>a</span> <span m='1886230'>list</span>
  <span m='1886480'>of</span> <span m='1886570'>frames.</span> <span m='1888080'>So</span>
  <span m='1888310'>given</span> <span m='1888670'>an</span> <span m='1888820'>existing</span>
  <span m='1889250'>environment</span> <span m='1889700'>structure,</span> <span m='1890360'>I'm</span>
  <span m='1890520'>going</span> <span m='1890600'>to</span> <span m='1890670'>make</span>
  <span m='1890870'>a</span> <span m='1890950'>new</span> <span m='1891180'>environment</span>
  <span m='1891680'>structure</span> <span m='1892280'>by</span> <span m='1892500'>consing</span>
  <span m='1892940'>a</span> <span m='1892990'>new</span> <span m='1893200'>frame</span>
  <span m='1893960'>onto</span> <span m='1894270'>the</span> <span m='1894390'>existing</span>
  <span m='1894850'>environment</span> <span m='1895270'>structure,</span> <span m='1896650'>where</span>
  <span m='1896870'>the</span> <span m='1896990'>new</span> <span m='1897270'>frame</span>
  <span m='1897710'>consists</span> <span m='1898080'>of</span> <span m='1898180'>the</span>
  <span m='1898270'>result</span> <span m='1898600'>of</span> <span m='1898700'>pairing</span>
  <span m='1899100'>up</span> <span m='1899380'>the</span> <span m='1899720'>variables,</span>
  <span m='1901110'>which</span> <span m='1901290'>are</span> <span m='1901320'>the</span>
  <span m='1901440'>bound</span> <span m='1901740'>variables of</span> <span m='1902140'>the</span>
  <span m='1902250'>procedure</span> <span m='1902840'>I'm</span> <span m='1903130'>applying,</span>
  <span m='1904030'>to</span> <span m='1904270'>the</span> <span m='1904830'>values</span>
  <span m='1905290'>which</span> <span m='1905470'>are the</span> <span m='1905610'>arguments</span>
  <span m='1906020'>that</span> <span m='1906130'>were</span> <span m='1906210'>passed</span>
  <span m='1907580'>that</span> <span m='1907810'>procedure.</span> </p><p><span m='1909690'>This</span>
  <span m='1909930'>is just</span> <span m='1910000'>making</span> <span m='1910220'>a</span>
  <span m='1910310'>list,</span> <span m='1912190'>adding</span> <span m='1912470'>a
  new</span> <span m='1912640'>element</span> <span m='1913000'>to</span> <span m='1913130'>our</span>
  <span m='1913260'>list</span> <span m='1913510'>of</span> <span m='1913600'>frames,</span>
  <span m='1914360'>which</span> <span m='1914550'>is</span> <span m='1914620'>an</span>
  <span m='1914680'>environment</span> <span m='1915110'>structure,</span> <span m='1915720'>to</span>
  <span m='1915890'>make</span> <span m='1916070'>a</span> <span m='1916130'>new</span>
  <span m='1916300'>environment.</span> <span m='1918391'>Where</span> <span m='1918890'>pair-up</span>
  <span m='1919600'>is</span> <span m='1919750'>very</span> <span m='1919980'>simple.</span>
  <span m='1921540'>Pair-up</span> <span m='1921920'>is</span> <span m='1922080'>nothing</span>
  <span m='1922410'>more</span> <span m='1923200'>than if</span> <span m='1923480'>I</span>
  <span m='1923600'>have</span> <span m='1923720'>a</span> <span m='1923900'>list</span>
  <span m='1924200'>of</span> <span m='1924280'>variables</span> <span m='1924610'>and</span>
  <span m='1924690'>a</span> <span m='1924740'>list</span> <span m='1925000'>of</span>
  <span m='1925080'>values,</span> <span m='1926080'>well,</span> <span m='1926550'>if</span>
  <span m='1926710'>I</span> <span m='1926780'>run</span> <span m='1927010'>out</span>
  <span m='1927140'>of</span> <span m='1927240'>variables</span> <span m='1927640'>and</span>
  <span m='1927730'>if</span> <span m='1927830'>I</span> <span m='1927900'>run</span>
  <span m='1928120'>out</span> <span m='1928210'>of</span> <span m='1928300'>values,</span>
  <span m='1928680'>everything's</span> <span m='1929050'>OK.</span> <span m='1929720'>Otherwise,</span>
  <span m='1930110'>I've</span> <span m='1930230'>given</span> <span m='1930470'>too</span>
  <span m='1930600'>many</span> <span m='1930830'>arguments.</span> </p><p><span m='1932990'>If</span>
  <span m='1933180'>I've</span> <span m='1933630'>not</span> <span m='1933930'>run</span>
  <span m='1934100'>out</span> <span m='1934220'>of</span> <span m='1934290'>variables,</span>
  <span m='1934720'>but I've</span> <span m='1935040'>run</span> <span m='1935190'>out</span>
  <span m='1935310'>of</span> <span m='1935390'>values,</span> <span m='1936070'>that</span>
  <span m='1936190'>I</span> <span m='1936280'>have</span> <span m='1936420'>too</span>
  <span m='1936600'>few</span> <span m='1936870'>arguments.</span> <span m='1938560'>And</span>
  <span m='1938880'>in the</span> <span m='1938970'>general</span> <span m='1939320'>case,</span>
  <span m='1939630'>where</span> <span m='1939770'>I</span> <span m='1939850'>don't</span>
  <span m='1940010'>have</span> <span m='1940160'>any</span> <span m='1940320'>errors,</span>
  <span m='1940640'>and I'm</span> <span m='1940750'>not</span> <span m='1941040'>done,</span>
  <span m='1942620'>then</span> <span m='1942890'>I</span> <span m='1943000'>really</span>
  <span m='1943400'>am</span> <span m='1943600'>just</span> <span m='1944080'>adding</span>
  <span m='1944470'>a</span> <span m='1944550'>new</span> <span m='1945150'>pair</span>
  <span m='1945740'>of</span> <span m='1946310'>the</span> <span m='1946860'>first</span>
  <span m='1947220'>variable</span> <span m='1947600'>with</span> <span m='1947710'>the</span>
  <span m='1949380'>first</span> <span m='1949650'>argument,</span> <span m='1951230'>the</span>
  <span m='1951300'>first</span> <span m='1951530'>value,</span> <span m='1952810'>onto</span>
  <span m='1953360'>a</span> <span m='1953440'>list</span> <span m='1955360'>resulting</span>
  <span m='1955780'>from</span> <span m='1955920'>pairing-up</span> <span m='1957010'>the</span>
  <span m='1957310'>rest</span> <span m='1957590'>of</span> <span m='1957700'>the</span>
  <span m='1957780'>variables</span> <span m='1958700'>with</span> <span m='1958850'>the</span>
  <span m='1959000'>rest</span> <span m='1959340'>of the</span> <span m='1960150'>values.</span>
  </p><p><span m='1962950'>Lookup</span> <span m='1963350'>is</span> <span m='1963460'>of</span>
  <span m='1963540'>course</span> <span m='1963820'>equally</span> <span m='1964230'>simple.</span>
  <span m='1966620'>If</span> <span m='1966840'>I</span> <span m='1966990'>have</span>
  <span m='1967290'>to</span> <span m='1967950'>look</span> <span m='1968170'>up</span>
  <span m='1968320'>a</span> <span m='1968410'>symbol</span> <span m='1968830'>in
  an</span> <span m='1968920'>environment,</span> <span m='1969970'>well, if the</span>
  <span m='1970360'>environment</span> <span m='1970820'>is</span> <span m='1970970'>empty,</span>
  <span m='1971170'>then</span> <span m='1971640'>I've</span> <span m='1971860'>got</span>
  <span m='1972020'>an</span> <span m='1972240'>unbound</span> <span m='1972490'>variable.</span>
  <span m='1974650'>Otherwise,</span> <span m='1976840'>what</span> <span m='1977080'>I'm</span>
  <span m='1977270'>going to do</span> <span m='1977510'>is</span> <span m='1977740'>use</span>
  <span m='1977970'>a</span> <span m='1978280'>special</span> <span m='1979280'>pair</span>
  <span m='1979520'>list</span> <span m='1979770'>lookup</span> <span m='1980070'>procedure,</span>
  <span m='1980470'>which</span> <span m='1980610'>we'll</span> <span m='1980730'>have</span>
  <span m='1981210'>very</span> <span m='1981440'>shortly,</span> <span m='1981980'>of</span>
  <span m='1982440'>the</span> <span m='1982540'>symbol</span> <span m='1982930'>in</span>
  <span m='1983070'>the</span> <span m='1983160'>first</span> <span m='1983470'>frame</span>
  <span m='1984560'>of</span> <span m='1984670'>the</span> <span m='1984780'>environment.</span>
  <span m='1985930'>Since</span> <span m='1986140'>I</span> <span m='1986230'>know</span>
  <span m='1986370'>the</span> <span m='1986480'>environment</span> <span m='1986850'>is
  not</span> <span m='1987010'>empty,</span> <span m='1987230'>it</span> <span m='1987310'>must</span>
  <span m='1987500'>have</span> <span m='1987590'>a</span> <span m='1987670'>first</span>
  <span m='1987910'>frame.</span> </p><p><span m='1989200'>So</span> <span m='1989380'>I</span>
  <span m='1989480'>lookup</span> <span m='1989830'>the</span> <span m='1989930'>symbol</span>
  <span m='1990280'>in</span> <span m='1990320'>the</span> <span m='1990400'>first</span>
  <span m='1990680'>frame.</span> <span m='1991140'>That</span> <span m='1991890'>becomes</span>
  <span m='1992220'>the</span> <span m='1992300'>value</span> <span m='1992730'>cell</span>
  <span m='1993000'>here.</span> <span m='1995150'>And</span> <span m='1995380'>then,</span>
  <span m='1996010'>if</span> <span m='1996230'>the</span> <span m='1996350'>value</span>
  <span m='1996760'>cell</span> <span m='1997030'>is</span> <span m='1997130'>empty,</span>
  <span m='1999070'>if</span> <span m='1999220'>there</span> <span m='1999430'>is</span>
  <span m='1999520'>no</span> <span m='1999670'>such</span> <span m='1999860'>value</span>
  <span m='2000180'>cell,</span> <span m='2000720'>then</span> <span m='2000830'>I</span>
  <span m='2000940'>have</span> <span m='2001060'>to</span> <span m='2001170'>continue</span>
  <span m='2001580'>and</span> <span m='2001660'>look</span> <span m='2001740'>at</span>
  <span m='2001820'>the</span> <span m='2001910'>rest</span> <span m='2002150'>of</span>
  <span m='2002190'>the</span> <span m='2002270'>frames.</span> <span m='2003720'>It</span>
  <span m='2003810'>means</span> <span m='2003960'>there</span> <span m='2004060'>was</span>
  <span m='2004200'>nothing</span> <span m='2004480'>found</span> <span m='2004790'>there.</span>
  </p><p><span m='2005990'>So</span> <span m='2006290'>that's a</span> <span m='2006610'>property</span>
  <span m='2007110'>of</span> <span m='2007150'>ASSQ</span> <span m='2007680'>is</span>
  <span m='2007760'>it</span> <span m='2007840'>returns</span> <span m='2008260'>emptiness</span>
  <span m='2009580'>if</span> <span m='2009670'>it</span> <span m='2009740'>doesn't</span>
  <span m='2010000'>find</span> <span m='2010270'>something.</span> <span m='2012010'>but</span>
  <span m='2012640'>if</span> <span m='2012750'>it</span> <span m='2012880'>did</span>
  <span m='2013080'>find</span> <span m='2013350'>something,</span> <span m='2013840'>then</span>
  <span m='2014290'>I'm</span> <span m='2014570'>going</span> <span m='2014620'>to</span>
  <span m='2014940'>use</span> <span m='2015020'>the</span> <span m='2015090'>CDR
  of the value</span> <span m='2015430'>cell</span> <span m='2015680'>here,</span>
  <span m='2016610'>which</span> <span m='2016810'>is</span> <span m='2016920'>the</span>
  <span m='2017030'>thing</span> <span m='2017270'>that</span> <span m='2017360'>was</span>
  <span m='2017470'>the</span> <span m='2017560'>pair</span> <span m='2018080'>consisting</span>
  <span m='2018670'>of</span> <span m='2018780'>the</span> <span m='2018880'>variable</span>
  <span m='2019390'>and</span> <span m='2019480'>the</span> <span m='2019570'>value.</span>
  <span m='2021050'>So</span> <span m='2021250'>the</span> <span m='2021340'>CDR</span>
  <span m='2021550'>of</span> <span m='2021650'>it</span> <span m='2021730'>is</span>
  <span m='2021840'>the</span> <span m='2021920'>value</span> <span m='2022250'>part.</span>
  </p><p><span m='2025000'>Finally,</span> <span m='2025560'>ASSQ</span> <span m='2026050'>is</span>
  <span m='2026150'>something</span> <span m='2026480'>you've</span> <span m='2026630'>probably</span>
  <span m='2027010'>seen</span> <span m='2027240'>already.</span> <span m='2027970'>ASSQ</span>
  <span m='2028550'>takes</span> <span m='2028830'>a</span> <span m='2028890'>symbol</span>
  <span m='2029320'>and</span> <span m='2029800'>a</span> <span m='2029940'>list</span>
  <span m='2030230'>of</span> <span m='2030330'>pairs,</span> <span m='2031520'>and</span>
  <span m='2031780'>if</span> <span m='2031900'>the</span> <span m='2032070'>list</span>
  <span m='2032310'>is</span> <span m='2032400'>empty,</span> <span m='2032710'>it's</span>
  <span m='2032870'>empty.</span> <span m='2033760'>If</span> <span m='2034290'>the</span>
  <span m='2034390'>symbol</span> <span m='2034740'>is</span> <span m='2034850'>the</span>
  <span m='2034940'>first</span> <span m='2035220'>thing</span> <span m='2035410'>in</span>
  <span m='2035560'>the</span> <span m='2035940'>list--</span> <span m='2037850'>That's</span>
  <span m='2038430'>an</span> <span m='2038530'>error.</span> <span m='2039820'>That</span>
  <span m='2040050'>should</span> <span m='2040160'>be</span> <span m='2040500'>CAAR,</span>
  <span m='2041210'>C-A-A-R.</span> <span m='2043250'>Everybody</span> <span m='2043550'>note</span>
  <span m='2043830'>that.</span> <span m='2047730'>Right</span> <span m='2047940'>there,</span>
  <span m='2048550'>OK?</span> </p><p><span m='2053121'>And</span> <span m='2053590'>in</span>
  <span m='2053750'>any</span> <span m='2054020'>case,</span> <span m='2054620'>if</span>
  <span m='2055110'>the</span> <span m='2055230'>symbol</span> <span m='2055550'>is</span>
  <span m='2055630'>the</span> <span m='2055730'>CAAR</span> <span m='2056179'>of</span>
  <span m='2056409'>the</span> <span m='2056520'> A list,</span> <span m='2057150'>then</span>
  <span m='2057489'>I</span> <span m='2057659'>want</span> <span m='2057840'>the</span>
  <span m='2058090'>first,</span> <span m='2058350'>the</span> <span m='2058610'>first</span>
  <span m='2058880'>pair,</span> <span m='2060389'>in</span> <span m='2060510'>the</span>
  <span m='2060639'> A list.</span> <span m='2062080'>So,</span> <span m='2062340'>in
  other</span> <span m='2062679'>words,</span> <span m='2062770'>if</span> <span m='2062820'>this</span>
  <span m='2063020'>is</span> <span m='2063100'>the</span> <span m='2063370'>key</span>
  <span m='2063600'>matching</span> <span m='2064469'>the</span> <span m='2064639'>right</span>
  <span m='2065090'>entry,</span> <span m='2066300'>otherwise,</span> <span m='2067120'>I</span>
  <span m='2067260'>want</span> <span m='2067380'>to</span> <span m='2067500'>look</span>
  <span m='2067699'>up</span> <span m='2067810'>that</span> <span m='2068000'>symbol</span>
  <span m='2068300'>in</span> <span m='2068389'>the</span> <span m='2068469'>rest.</span>
  <span m='2070080'>Sorry</span> <span m='2070429'>for</span> <span m='2070530'>producing</span>
  <span m='2070900'>a</span> <span m='2070960'>bug,</span> <span m='2072530'>bugs</span>
  <span m='2072810'>appear.</span> </p><p><span m='2075190'>Well,</span> <span m='2075489'>in</span>
  <span m='2075650'>any</span> <span m='2075830'>case,</span> <span m='2077219'>you're</span>
  <span m='2077360'>pretty</span> <span m='2077610'>much</span> <span m='2078050'>seeing</span>
  <span m='2078389'>the</span> <span m='2078500'>whole</span> <span m='2078730'>thing</span>
  <span m='2079010'>now.</span> <span m='2081880'>It's</span> <span m='2082050'>a</span>
  <span m='2082100'>very</span> <span m='2082380'>beautiful</span> <span m='2082820'>thing,</span>
  <span m='2084320'>even</span> <span m='2084530'>though</span> <span m='2084710'>it's</span>
  <span m='2084810'>written</span> <span m='2085010'>in</span> <span m='2085100'>an</span>
  <span m='2085150'>ugly</span> <span m='2085449'>style,</span> <span m='2086780'>being</span>
  <span m='2087100'>the</span> <span m='2087190'>kernel</span> <span m='2087560'>of
  every</span> <span m='2087790'>language.</span> <span m='2089600'>I suggest that
  we</span> <span m='2089810'>just--</span> <span m='2090210'>let's</span> <span m='2090420'>look</span>
  <span m='2090620'>at</span> <span m='2090690'>it</span> <span m='2090840'>for</span>
  <span m='2090940'>a</span> <span m='2090960'>while.</span> </p><p><span m='2096749'>[MUSIC
  PLAYING]</span> </p><p><span m='2149750'>Are</span> <span m='2149900'>there</span>
  <span m='2150070'>any</span> <span m='2150230'>questions?</span> <span m='2161180'>Alright,</span>
  <span m='2161400'>I</span> <span m='2161520'>suppose</span> <span m='2161810'>it's</span>
  <span m='2161910'>time</span> <span m='2162140'>to</span> <span m='2162180'>take</span>
  <span m='2162390'>a</span> <span m='2162460'>small</span> <span m='2162750'>break</span>
  <span m='2163050'>then.</span> <span m='2164044'>[MUSIC PLAYING]</span> </p><p><span
  m='2216780'>OK,</span> <span m='2216940'>now</span> <span m='2217120'>we're</span>
  <span m='2217240'>just</span> <span m='2217420'>going</span> <span m='2217550'>to</span>
  <span m='2217680'>do a</span> <span m='2217750'>little</span> <span m='2217940'>bit</span>
  <span m='2218060'>of</span> <span m='2218160'>practice</span> <span m='2219390'>understanding</span>
  <span m='2220240'>what</span> <span m='2220400'>it</span> <span m='2220520'>is</span>
  <span m='2220640'>we've</span> <span m='2220820'>just</span> <span m='2221100'>shown</span>
  <span m='2221360'>you.</span> <span m='2223470'>What</span> <span m='2223680'>we're</span>
  <span m='2223790'>going</span> <span m='2223880'>to</span> <span m='2223960'>do</span>
  <span m='2224190'>is</span> <span m='2224310'>go</span> <span m='2224520'>through,</span>
  <span m='2224760'>in</span> <span m='2224940'>detail,</span> <span m='2225510'>an</span>
  <span m='2225700'>evaluation</span> <span m='2227600'>by</span> <span m='2227840'>informally</span>
  <span m='2228420'>substituting</span> <span m='2229240'>through</span> <span m='2229560'>the</span>
  <span m='2229720'>interpreter.</span> <span m='2231500'>And</span> <span m='2231780'>since</span>
  <span m='2231950'>we</span> <span m='2232110'>have</span> <span m='2232270'>no</span>
  <span m='2232470'>assignments</span> <span m='2233190'>or</span> <span m='2233380'>definitions</span>
  <span m='2234040'>in</span> <span m='2234160'>this</span> <span m='2234290'>interpreter,</span>
  <span m='2235310'>we</span> <span m='2235420'>have</span> <span m='2236070'>no</span>
  <span m='2236190'>possible</span> <span m='2236610'>side</span> <span m='2236850'>effects,</span>
  <span m='2238130'>and</span> <span m='2238310'>so</span> <span m='2238470'>the</span>
  <span m='2240200'>we</span> <span m='2240330'>can</span> <span m='2240580'>do</span>
  <span m='2240690'>substitution</span> <span m='2241320'>with</span> <span m='2241450'>impunity</span>
  <span m='2242640'>and</span> <span m='2242820'>not</span> <span m='2242890'>worry</span>
  <span m='2243200'>about</span> <span m='2243560'>results.</span> </p><p><span m='2245330'>So</span>
  <span m='2245920'>the</span> <span m='2246140'>particular</span> <span m='2246540'>problem</span>
  <span m='2246950'>I'd</span> <span m='2247090'>like</span> <span m='2247280'>to</span>
  <span m='2247360'>look</span> <span m='2247660'>at</span> <span m='2248180'>is</span>
  <span m='2248320'>it</span> <span m='2248680'>an</span> <span m='2248800'>interesting</span>
  <span m='2249240'>one.</span> <span m='2250690'>It's</span> <span m='2250920'>the</span>
  <span m='2251130'>evaluation</span> <span m='2252586'>of</span> <span m='2254870'>quote,</span>
  <span m='2256540'>open,</span> <span m='2256810'>open,</span> <span m='2257140'>open,</span>
  <span m='2258410'>lambda</span> <span m='2259400'>of</span> <span m='2259610'>x,</span>
  <span m='2261910'>lambda</span> <span m='2262860'>of</span> <span m='2263100'>y</span>
  <span m='2265720'>plus</span> <span m='2266810'>x</span> <span m='2267220'>y,</span>
  <span m='2270460'>lambda,</span> <span m='2271960'>lambda,</span> <span m='2273140'>applied</span>
  <span m='2273610'>to</span> <span m='2273740'>three,</span> <span m='2275100'>applied</span>
  <span m='2275530'>to</span> <span m='2275640'>four,</span> <span m='2277020'>in</span>
  <span m='2277610'>some</span> <span m='2277840'>global</span> <span m='2278140'>environment</span>
  <span m='2278640'>which</span> <span m='2278980'>I'll call</span> <span m='2279130'>e0.</span>
  </p><p><span m='2284930'>So</span> <span m='2285140'>what we</span> <span m='2285320'>have</span>
  <span m='2285580'>here</span> <span m='2286350'>is</span> <span m='2286530'>a</span>
  <span m='2286610'>procedure</span> <span m='2287110'>of</span> <span m='2287220'>one</span>
  <span m='2287340'>argument</span> <span m='2287680'>x,</span> <span m='2287900'>which</span>
  <span m='2288080'>produces</span> <span m='2288600'>as</span> <span m='2288720'>its</span>
  <span m='2288890'>value</span> <span m='2289390'>a</span> <span m='2289460'>procedure</span>
  <span m='2289950'>of</span> <span m='2290090'>one</span> <span m='2290230'>argument</span>
  <span m='2290640'>y,</span> <span m='2290980'>which</span> <span m='2291210'>adds</span>
  <span m='2291440'>x</span> <span m='2291650'>to</span> <span m='2291750'>y.</span>
  <span m='2294300'>We</span> <span m='2294560'>are</span> <span m='2294710'>applying</span>
  <span m='2295210'>the</span> <span m='2295310'>procedure</span> <span m='2295730'>of
  one</span> <span m='2295940'>argument</span> <span m='2296310'>x</span> <span m='2297160'>to</span>
  <span m='2297380'>three.</span> <span m='2297960'>So</span> <span m='2298160'>x</span>
  <span m='2298540'>should become</span> <span m='2298860'>three.</span> <span m='2301400'>And</span>
  <span m='2301620'>the</span> <span m='2301700'>result</span> <span m='2302080'>of</span>
  <span m='2302210'>that</span> <span m='2302340'>should be</span> <span m='2302630'>procedure</span>
  <span m='2303020'>of</span> <span m='2303130'>one</span> <span m='2303240'>argument</span>
  <span m='2303590'>y,</span> <span m='2304460'>which</span> <span m='2304630'>will</span>
  <span m='2304830'>then</span> <span m='2304970'>apply</span> <span m='2305310'>to</span>
  <span m='2305710'>4.</span> <span m='2308910'>And</span> <span m='2309160'>there
  is</span> <span m='2309270'>a</span> <span m='2309330'>very</span> <span m='2309570'>simple</span>
  <span m='2309910'>case,</span> <span m='2311100'>they</span> <span m='2311250'>will</span>
  <span m='2311480'>then</span> <span m='2311700'>add</span> <span m='2311970'>those</span>
  <span m='2312190'>results.</span> </p><p><span m='2314790'>And</span> <span m='2315020'>now</span>
  <span m='2315170'>in</span> <span m='2315240'>order</span> <span m='2315430'>to</span>
  <span m='2315520'>do</span> <span m='2315690'>that,</span> <span m='2315870'>I</span>
  <span m='2315940'>want</span> <span m='2316050'>to</span> <span m='2316150'>make</span>
  <span m='2316300'>a</span> <span m='2316350'>very</span> <span m='2316570'>simple</span>
  <span m='2316860'>environment</span> <span m='2317360'>model.</span> <span m='2317660'>And</span>
  <span m='2317960'>at</span> <span m='2318160'>this</span> <span m='2318360'>point,</span>
  <span m='2318870'>you</span> <span m='2319000'>should</span> <span m='2319150'>already</span>
  <span m='2319560'>have</span> <span m='2319780'>in</span> <span m='2319850'>your</span>
  <span m='2319980'>mind</span> <span m='2321080'>the</span> <span m='2321200'>environments</span>
  <span m='2321740'>that</span> <span m='2321850'>this</span> <span m='2322070'>produces.</span>
  <span m='2324460'>But</span> <span m='2324610'>we're</span> <span m='2324740'>going
  to</span> <span m='2324790'>start</span> <span m='2325090'>out</span> <span m='2325480'>with</span>
  <span m='2325650'>a</span> <span m='2325700'>global</span> <span m='2326050'>environment,</span>
  <span m='2328810'>which</span> <span m='2328920'>I'll</span> <span m='2329250'>call</span>
  <span m='2329530'>e0,</span> <span m='2334590'>which</span> <span m='2334960'>is</span>
  <span m='2335110'>that.</span> <span m='2336740'>And</span> <span m='2336890'>it's</span>
  <span m='2337030'>going</span> <span m='2337160'>to</span> <span m='2337300'>have</span>
  <span m='2337570'>in</span> <span m='2337690'>it</span> <span m='2338050'>things,</span>
  <span m='2338420'>definitions</span> <span m='2339010'>for</span> <span m='2339160'>plus,</span>
  <span m='2340550'>and</span> <span m='2341730'>times,</span> <span m='2346400'>and--</span>
  <span m='2347390'>using</span> <span m='2347680'>Greek</span> <span m='2347920'>letters,</span>
  <span m='2348260'>isn't</span> <span m='2348330'>that</span> <span m='2348560'>interesting,</span>
  <span m='2349090'>for</span> <span m='2349260'>the</span> <span m='2349670'>objects--</span>
  <span m='2351290'>and</span> <span m='2351610'>minus,</span> <span m='2355591'>and</span>
  <span m='2356980'>quotient,</span> <span m='2358510'>and</span> <span m='2358790'>CAR,</span>
  <span m='2361800'>and</span> <span m='2362280'>CDR,</span> <span m='2364220'>and</span>
  <span m='2364660'>CONS,</span> <span m='2367100'>and</span> <span m='2367330'>EQ,</span>
  <span m='2368476'>and</span> <span m='2368830'>everything</span> <span m='2369190'>else</span>
  <span m='2369370'>you</span> <span m='2369470'>might</span> <span m='2369660'>imagine</span>
  <span m='2370100'>in a</span> <span m='2370160'>global</span> <span m='2370480'>environment.</span>
  <span m='2371270'>It's</span> <span m='2371650'>got something</span> <span m='2371860'>there</span>
  <span m='2372640'>for</span> <span m='2372800'>each</span> <span m='2372950'>of</span>
  <span m='2373020'>those</span> <span m='2373310'>things,</span> <span m='2374590'>something</span>
  <span m='2374940'>the</span> <span m='2375100'>machine</span> <span m='2375380'>is</span>
  <span m='2375470'>born</span> <span m='2375760'>with,</span> <span m='2376860'>that's</span>
  <span m='2377400'>e0.</span> </p><p><span m='2379220'>Now</span> <span m='2379400'>what</span>
  <span m='2379510'>does</span> <span m='2379630'>it</span> <span m='2379750'>mean</span>
  <span m='2380340'>to</span> <span m='2380640'>do</span> <span m='2380780'>this</span>
  <span m='2380950'>evaluation?</span> <span m='2382940'>Well,</span> <span m='2383360'>we</span>
  <span m='2383480'>go</span> <span m='2383670'>through</span> <span m='2383840'>the</span>
  <span m='2383940'>set</span> <span m='2384140'>of</span> <span m='2384220'>special</span>
  <span m='2384680'>forms.</span> <span m='2385670'>First</span> <span m='2385950'>of</span>
  <span m='2386000'>all,</span> <span m='2386120'>this</span> <span m='2386290'>is</span>
  <span m='2386400'>not</span> <span m='2386530'>a</span> <span m='2386660'>number.</span>
  <span m='2388670'>This</span> <span m='2388920'>is</span> <span m='2389050'>not</span>
  <span m='2389820'>a</span> <span m='2389920'>symbol.</span> <span m='2393210'>Gee,</span>
  <span m='2394050'>it's</span> <span m='2394290'>not</span> <span m='2394580'>a</span>
  <span m='2394650'>quoted</span> <span m='2394990'>expression.</span> <span m='2396520'>This</span>
  <span m='2397120'>is</span> <span m='2397250'>a</span> <span m='2397310'>quoted</span>
  <span m='2397610'>expression,</span> <span m='2399550'>but</span> <span m='2399660'>that's</span>
  <span m='2399840'>not</span> <span m='2399950'>what</span> <span m='2400060'>I</span>
  <span m='2400080'>interested</span> <span m='2400500'>in.</span> <span m='2400600'>The</span>
  <span m='2400790'>question</span> <span m='2401130'>is,</span> <span m='2401400'>whether</span>
  <span m='2401650'>or</span> <span m='2401670'>not</span> <span m='2401840'>the</span>
  <span m='2401930'>thing</span> <span m='2402090'>which</span> <span m='2402250'>is</span>
  <span m='2402350'>quoted</span> <span m='2402700'>is</span> <span m='2402840'>quoted</span>
  <span m='2403130'>expression?</span> <span m='2405890'>I'm</span> <span m='2406070'>evaluating</span>
  <span m='2407100'>an</span> <span m='2407270'>expression.</span> <span m='2407960'>This</span>
  <span m='2408220'>just</span> <span m='2408410'>says</span> <span m='2408550'>it's</span>
  <span m='2408720'>this</span> <span m='2408950'>particular</span> <span m='2409400'>expression.</span>
  <span m='2411410'>This</span> <span m='2411630'>is</span> <span m='2411720'>not</span>
  <span m='2411910'>a</span> <span m='2411970'>quoted</span> <span m='2412250'>expression.</span>
  <span m='2415230'>It's</span> <span m='2415490'>not</span> <span m='2415810'>a</span>
  <span m='2415890'>thing</span> <span m='2416090'>that</span> <span m='2416210'>begins</span>
  <span m='2416520'>with</span> <span m='2416640'>lambda.</span> <span m='2419120'>It's</span>
  <span m='2419310'>not</span> <span m='2419480'>a</span> <span m='2419520'>thing</span>
  <span m='2419670'>that</span> <span m='2419770'>begins</span> <span m='2420040'>with</span>
  <span m='2420150'>COND.</span> <span m='2422030'>Therefore,</span> <span m='2422700'>it's
  an</span> <span m='2422870'>application</span> <span m='2423410'>of</span> <span
  m='2423500'>its</span> <span m='2424630'>of</span> <span m='2424790'>an</span> <span
  m='2424870'>operated</span> <span m='2425350'>operands.</span> <span m='2426310'>It's
  a</span> <span m='2426450'>combination.</span> </p><p><span m='2428570'>The</span>
  <span m='2428870'>combination</span> <span m='2429930'>thus</span> <span m='2430270'>has</span>
  <span m='2430960'>this</span> <span m='2431710'>as</span> <span m='2432070'>the</span>
  <span m='2433350'>operator</span> <span m='2434200'>and</span> <span m='2434940'>this</span>
  <span m='2435120'>is</span> <span m='2435230'>the</span> <span m='2435370'>operands.</span>
  <span m='2440130'>Well,</span> <span m='2440410'>that</span> <span m='2440600'>means</span>
  <span m='2441080'>that</span> <span m='2441290'>what</span> <span m='2441760'>I'm</span>
  <span m='2442090'>going</span> <span m='2442560'>to</span> <span m='2442890'>do</span>
  <span m='2443220'>is</span> <span m='2443380'>transform this into</span> <span m='2443620'>apply</span>
  <span m='2447180'>of</span> <span m='2447350'>eval,</span> <span m='2450340'>of</span>
  <span m='2450610'>quote,</span> <span m='2451750'>open,</span> <span m='2452810'>open</span>
  <span m='2453260'>lambda</span> <span m='2453640'>of</span> <span m='2454010'>x,</span>
  <span m='2456110'>lambda</span> <span m='2456330'>of</span> <span m='2456940'>y--</span>
  <span m='2458180'>I'm</span> <span m='2458290'>evaluating the</span> <span m='2458560'>operator--</span>
  <span m='2459980'>plus</span> <span m='2460690'>x</span> <span m='2461100'>y,</span>
  <span m='2463080'>in</span> <span m='2463290'>the</span> <span m='2463420'>environment,</span>
  <span m='2467470'>also</span> <span m='2467880'>e0,</span> <span m='2472870'>with</span>
  <span m='2473070'>the</span> <span m='2473200'>operands</span> <span m='2473610'>that</span>
  <span m='2473880'>I'm</span> <span m='2474160'>going to</span> <span m='2474280'>apply</span>
  <span m='2474640'>this</span> <span m='2474860'>to,</span> <span m='2475230'>the</span>
  <span m='2475430'>arguments</span> <span m='2475990'>being</span> <span m='2476260'>the</span>
  <span m='2476330'>result</span> <span m='2476600'>of</span> <span m='2476870'>EVLIST,</span>
  <span m='2481210'>the</span> <span m='2481490'>list</span> <span m='2481730'>containing</span>
  <span m='2482130'>four,</span> <span m='2483740'>fin</span> <span m='2484020'>e0.</span>
  </p><p><span m='2489010'>I'm</span> <span m='2489250'>using</span> <span m='2489470'>this</span>
  <span m='2489640'>funny</span> <span m='2489900'>notation</span> <span m='2490430'>here</span>
  <span m='2490600'>for</span> <span m='2490730'>e0</span> <span m='2492380'>because</span>
  <span m='2492720'>this</span> <span m='2493010'>should</span> <span m='2493280'>be</span>
  <span m='2493950'>that</span> <span m='2494160'>environment.</span> <span m='2496840'>I</span>
  <span m='2497010'>haven't</span> <span m='2497310'>a</span> <span m='2497360'>name</span>
  <span m='2497580'>for</span> <span m='2497730'>it,</span> <span m='2497880'>because
  I have</span> <span m='2498030'>no</span> <span m='2498160'>environment</span> <span
  m='2498640'>to</span> <span m='2498740'>name it</span> <span m='2498840'>in.</span>
  <span m='2501960'>So</span> <span m='2502180'>this</span> <span m='2502370'>is</span>
  <span m='2502480'>just</span> <span m='2502740'>a</span> <span m='2503160'>representation</span>
  <span m='2504100'>of</span> <span m='2504340'>what</span> <span m='2504480'>would</span>
  <span m='2504630'>be</span> <span m='2504780'>a</span> <span m='2504830'>quoted</span>
  <span m='2505210'>expression,</span> <span m='2505750'>if</span> <span m='2505860'>you</span>
  <span m='2505970'>will.</span> <span m='2507730'>The</span> <span m='2507850'>data</span>
  <span m='2508080'>structure,</span> <span m='2509220'>which</span> <span m='2509460'>is</span>
  <span m='2509630'>the</span> <span m='2509760'>environment,</span> <span m='2510680'>goes</span>
  <span m='2510900'>there.</span> </p><p><span m='2513040'>Well,</span> <span m='2514210'>that's
  what</span> <span m='2514370'>we're</span> <span m='2514560'>seeing</span> <span
  m='2514890'>here.</span> <span m='2515850'>Well</span> <span m='2515990'>in order</span>
  <span m='2516400'>to</span> <span m='2516530'>do this,</span> <span m='2516730'>I</span>
  <span m='2516810'>have</span> <span m='2516900'>to</span> <span m='2516980'>do</span>
  <span m='2517080'>this,</span> <span m='2517310'>and</span> <span m='2517370'>I</span>
  <span m='2517520'>have to do</span> <span m='2517740'>that.</span> <span m='2519610'>Well</span>
  <span m='2519780'>this</span> <span m='2519930'>one's</span> <span m='2520160'>easy,</span>
  <span m='2520580'>so</span> <span m='2520720'>why</span> <span m='2520870'>don't</span>
  <span m='2520970'>we do</span> <span m='2521080'>that</span> <span m='2521240'>one</span>
  <span m='2521400'>first.</span> <span m='2523770'>This</span> <span m='2524020'>turns</span>
  <span m='2524260'>into</span> <span m='2524630'>apply</span> <span m='2526910'>of</span>
  <span m='2527180'>eval--</span> <span m='2527550'>just</span> <span m='2527780'>copying</span>
  <span m='2528010'>something</span> <span m='2528210'>now.</span> <span m='2529520'>Most</span>
  <span m='2529690'>of</span> <span m='2529860'>the</span> <span m='2529930'>substitution</span>
  <span m='2530470'>rule is</span> <span m='2530730'>copying.</span> <span m='2538530'>So</span>
  <span m='2538720'>I'm</span> <span m='2538870'>going</span> <span m='2539070'>to</span>
  <span m='2539490'>not</span> <span m='2539750'>say</span> <span m='2539890'>the</span>
  <span m='2539990'>words</span> <span m='2540320'>when I</span> <span m='2540520'>copy,</span>
  <span m='2541350'>because</span> <span m='2542100'>it's</span> <span m='2542490'>faster.</span>
  <span m='2546100'>And</span> <span m='2546740'>then</span> <span m='2546910'>the</span>
  <span m='2547040'>EVLIST</span> <span m='2547500'>is</span> <span m='2547590'>going</span>
  <span m='2547690'>to</span> <span m='2547790'>turn</span> <span m='2548000'>into</span>
  <span m='2548430'>a</span> <span m='2548660'>cons,</span> <span m='2551140'>of</span>
  <span m='2551620'>eval,</span> <span m='2554130'>of</span> <span m='2554430'>four,</span>
  <span m='2555840'>in</span> <span m='2556020'>e0--</span> <span m='2558780'>because</span>
  <span m='2559080'>it</span> <span m='2559140'>was</span> <span m='2559270'>not</span>
  <span m='2559460'>an</span> <span m='2559580'>empty</span> <span m='2559840'>list--</span>
  <span m='2562260'>onto</span> <span m='2563230'>the</span> <span m='2563700'>result</span>
  <span m='2564080'>of</span> <span m='2564180'>EVLISTing,</span> <span m='2567360'>on</span>
  <span m='2567570'>the</span> <span m='2567670'>empty</span> <span m='2568020'>list,</span>
  <span m='2568335'>in</span> <span m='2568650'>e0.</span> </p><p><span m='2572580'>And</span>
  <span m='2572950'>I'm going to start</span> <span m='2573060'>leaving</span> <span
  m='2573390'>out</span> <span m='2573560'>steps</span> <span m='2573850'>soon,</span>
  <span m='2574210'>because</span> <span m='2574400'>it's</span> <span m='2574550'>going</span>
  <span m='2574620'>to</span> <span m='2574690'>get</span> <span m='2574820'>boring.</span>
  <span m='2579870'>But</span> <span m='2580090'>this</span> <span m='2580260'>is</span>
  <span m='2580370'>basically</span> <span m='2580860'>the</span> <span m='2580950'>same</span>
  <span m='2581220'>thing</span> <span m='2581500'>as</span> <span m='2581700'>apply,</span>
  <span m='2584290'>of</span> <span m='2584710'>eval--</span> <span m='2587640'>I'm</span>
  <span m='2587750'>going</span> <span m='2587930'>to keep</span> <span m='2588000'>doing</span>
  <span m='2588280'>this--</span> <span m='2590230'>the</span> <span m='2590850'>lambda</span>
  <span m='2591180'>of</span> <span m='2591600'>x,</span> <span m='2592740'>the</span>
  <span m='2593030'>lambda</span> <span m='2593230'>of</span> <span m='2593770'>y,</span>
  <span m='2595120'>plus</span> <span m='2595690'>xy,</span> <span m='2596460'>3,</span>
  <span m='2598410'>close,</span> <span m='2599400'>e0.</span> <span m='2600240'>I'm
  a</span> <span m='2600310'>pretty</span> <span m='2600480'>good</span> <span m='2600650'>machine.</span>
  </p><p><span m='2604690'>Well,</span> <span m='2604950'>eval</span> <span m='2605380'>of</span>
  <span m='2605810'>four,</span> <span m='2606600'>that's</span> <span m='2606970'>meets</span>
  <span m='2607310'>the</span> <span m='2607410'>question,</span> <span m='2607710'>is
  it</span> <span m='2607840'>a</span> <span m='2607950'>number.</span> <span m='2608790'>So</span>
  <span m='2609210'>that's</span> <span m='2609470'>cons,</span> <span m='2611630'>cons</span>
  <span m='2612720'>of</span> <span m='2613120'>4.</span> <span m='2615280'>And</span>
  <span m='2615460'>EVLIST</span> <span m='2615760'>of</span> <span m='2615850'>the</span>
  <span m='2616130'>empty</span> <span m='2616270'>list</span> <span m='2616490'>is</span>
  <span m='2616620'>the</span> <span m='2616780'>empty</span> <span m='2617110'>list,</span>
  <span m='2617530'>so</span> <span m='2617860'>that's</span> <span m='2618850'>this.</span>
  <span m='2623270'>And</span> <span m='2623640'>that's</span> <span m='2623980'>very</span>
  <span m='2624190'>simple</span> <span m='2624480'>to</span> <span m='2624550'>understand,</span>
  <span m='2624860'>because</span> <span m='2625170'>that</span> <span m='2625460'>means</span>
  <span m='2626170'>the</span> <span m='2626290'>list</span> <span m='2626490'>containing</span>
  <span m='2626800'>four</span> <span m='2627030'>itself.</span> <span m='2628710'>So</span>
  <span m='2628930'>this</span> <span m='2629140'>is</span> <span m='2629300'>nothing</span>
  <span m='2629600'>more</span> <span m='2629840'>than</span> <span m='2630100'>apply</span>
  <span m='2633250'>of</span> <span m='2633410'>eval,</span> <span m='2635670'>quote,</span>
  <span m='2636000'>open,</span> <span m='2636340'>open,</span> <span m='2636680'>lambda</span>
  <span m='2637160'>of</span> <span m='2637670'>x,</span> <span m='2638140'>lambda</span>
  <span m='2638960'>of</span> <span m='2639140'>y,</span> <span m='2640610'>plus</span>
  <span m='2641130'>x</span> <span m='2641660'>y,</span> <span m='2644180'>three</span>
  <span m='2644760'>applied</span> <span m='2645400'>to,</span> <span m='2646590'>e0,</span>
  <span m='2648820'>applied</span> <span m='2649230'>to the</span> <span m='2649300'>list</span>
  <span m='2649600'>four--</span> <span m='2651678'>bang.</span> <span m='2653940'>So</span>
  <span m='2654170'>that's</span> <span m='2654470'>that</span> <span m='2654730'>step.</span>
  </p><p><span m='2658100'>Now</span> <span m='2658310'>let's</span> <span m='2658490'>look</span>
  <span m='2658590'>at</span> <span m='2658700'>the</span> <span m='2658860'>next,</span>
  <span m='2659030'>more</span> <span m='2659400'>interesting</span> <span m='2659550'>thing.</span>
  <span m='2660360'>What</span> <span m='2660560'>do I</span> <span m='2660640'>do</span>
  <span m='2660810'>to</span> <span m='2660900'>evaluate</span> <span m='2661440'>that?</span>
  <span m='2663070'>Evaluating</span> <span m='2663920'>this</span> <span m='2665310'>means</span>
  <span m='2665580'>I</span> <span m='2665680'>have</span> <span m='2665880'>to</span>
  <span m='2666050'>evaluate--</span> <span m='2667780'>Well,</span> <span m='2668110'>it's</span>
  <span m='2668290'>not.</span> <span m='2669460'>It's</span> <span m='2669640'>nothing</span>
  <span m='2670010'>but</span> <span m='2670200'>an</span> <span m='2670300'>application.</span>
  <span m='2671680'>It's</span> <span m='2671870'>not</span> <span m='2672030'>one</span>
  <span m='2672150'>of</span> <span m='2672200'>the</span> <span m='2672260'>special</span>
  <span m='2672610'>things.</span> <span m='2673570'>If</span> <span m='2673740'>the</span>
  <span m='2673870'>application</span> <span m='2674930'>of</span> <span m='2675330'>this</span>
  <span m='2675840'>operator,</span> <span m='2676530'>which</span> <span m='2676690'>we</span>
  <span m='2676810'>see</span> <span m='2677050'>here--</span> <span m='2677660'>here's</span>
  <span m='2678010'>the</span> <span m='2678280'>operator--</span> <span m='2680270'>applied</span>
  <span m='2680700'>to</span> <span m='2680790'>this</span> <span m='2681050'>operands,</span>
  <span m='2684610'>that</span> <span m='2684870'>combination.</span> <span m='2686570'>But</span>
  <span m='2687000'>we</span> <span m='2687110'>know</span> <span m='2687200'>how</span>
  <span m='2687280'>to</span> <span m='2687350'>do</span> <span m='2687510'>that,</span>
  <span m='2688870'>because</span> <span m='2689460'>that's</span> <span m='2689930'>the</span>
  <span m='2690740'>last</span> <span m='2691140'>case</span> <span m='2691390'>of</span>
  <span m='2691500'>the</span> <span m='2691890'>conditional.</span> <span m='2692370'>So</span>
  <span m='2692630'>substituting</span> <span m='2693240'>in</span> <span m='2693990'>for</span>
  <span m='2694340'>this</span> <span m='2694560'>evaluation,</span> <span m='2695800'>it's</span>
  <span m='2695970'>apply</span> <span m='2696330'>of</span> <span m='2696420'>eval</span>
  <span m='2696480'>of</span> <span m='2696860'>the</span> <span m='2696980'>operator</span>
  <span m='2697560'>in</span> <span m='2697710'>the</span> <span m='2697910'>EVLIST</span>
  <span m='2698270'>of</span> <span m='2698320'>the</span> <span m='2698410'>operands.</span>
  </p><p><span m='2701160'>Well,</span> <span m='2701320'>it's</span> <span m='2701440'>apply,</span>
  <span m='2703350'>of</span> <span m='2703810'>apply,</span> <span m='2707360'>of</span>
  <span m='2707790'>eval,</span> <span m='2710610'>of</span> <span m='2711050'>quote,</span>
  <span m='2711400'>open,</span> <span m='2711840'>lambda</span> <span m='2712100'>of</span>
  <span m='2712360'>x,</span> <span m='2715290'>lambda of</span> <span m='2715690'>y,</span>
  <span m='2719330'>plus</span> <span m='2719870'>x</span> <span m='2720300'>y,</span>
  <span m='2721940'>lambda,</span> <span m='2722830'>lambda,</span> <span m='2723780'>in</span>
  <span m='2724160'>environment</span> <span m='2724860'>e0.</span> <span m='2730520'>I'm</span>
  <span m='2730740'>going</span> <span m='2730820'>to</span> <span m='2730890'>short</span>
  <span m='2731170'>circuit</span> <span m='2731480'>the</span> <span m='2731590'>evaluation</span>
  <span m='2731905'>of</span> <span m='2732220'>the operands ,</span> <span m='2732730'>because</span>
  <span m='2732910'>they're</span> <span m='2733080'>the same</span> <span m='2733290'>as
  they</span> <span m='2733450'>were</span> <span m='2733610'>before.</span> <span
  m='2735230'>I</span> <span m='2735330'>got</span> <span m='2735450'>a</span> <span
  m='2735490'>list</span> <span m='2735710'>containing</span> <span m='2736030'>three,</span>
  <span m='2736410'>apply</span> <span m='2736720'>that,</span> <span m='2737650'>and</span>
  <span m='2738080'>apply</span> <span m='2738510'>that</span> <span m='2738750'>to</span>
  <span m='2738840'>four.</span> </p><p><span m='2742780'>Well</span> <span m='2743030'>let's</span>
  <span m='2743250'>see.</span> <span m='2744410'>Eval</span> <span m='2744620'>of
  a</span> <span m='2745120'>lambda</span> <span m='2745560'>expression</span> <span
  m='2748060'>produces</span> <span m='2748520'>a</span> <span m='2748600'>procedure</span>
  <span m='2749080'>object.</span> <span m='2752030'>So</span> <span m='2752340'>this</span>
  <span m='2752560'>is</span> <span m='2753520'>apply,</span> <span m='2756790'>of</span>
  <span m='2757250'>apply,</span> <span m='2760450'>of</span> <span m='2760640'>the</span>
  <span m='2760840'>procedure</span> <span m='2761290'>object</span> <span m='2761620'>closure,</span>
  <span m='2764530'>which</span> <span m='2764790'>contains</span> <span m='2766725'>the</span>
  <span m='2767160'>body</span> <span m='2767500'>of</span> <span m='2767590'>the</span>
  <span m='2767670'>procedure,</span> <span m='2768240'>x,</span> <span m='2768920'>which</span>
  <span m='2769240'>is</span> <span m='2769420'>lambda--</span> <span m='2769770'>which</span>
  <span m='2770140'>binds</span> <span m='2770400'>x</span> <span m='2771130'>[UNINTELLIGIBLE]</span>
  <span m='2772130'>the</span> <span m='2773780'>internals</span> <span m='2774210'>of</span>
  <span m='2774420'>the</span> <span m='2774930'>body,</span> <span m='2775830'>it</span>
  <span m='2775940'>returns</span> <span m='2776490'>the</span> <span m='2776580'>procedure</span>
  <span m='2777000'>of</span> <span m='2777110'>one</span> <span m='2777230'>argument</span>
  <span m='2777640'>y,</span> <span m='2778620'>which</span> <span m='2778910'>adds</span>
  <span m='2779720'>x</span> <span m='2780030'>to</span> <span m='2780160'>y.</span>
  <span m='2783210'>Environment</span> <span m='2783820'>e0</span> <span m='2784280'>is</span>
  <span m='2784390'>now</span> <span m='2784590'>captured</span> <span m='2785170'>in</span>
  <span m='2785300'>it,</span> <span m='2787050'>because</span> <span m='2787680'>this</span>
  <span m='2787820'>was</span> <span m='2787930'>evaluated</span> <span m='2788210'>with</span>
  <span m='2788510'>respect</span> <span m='2788960'>to</span> <span m='2789100'>e0.</span>
  <span m='2790340'>e0</span> <span m='2790620'>is</span> <span m='2790740'>part</span>
  <span m='2791050'>now</span> <span m='2791230'>of</span> <span m='2791340'>the</span>
  <span m='2791440'>closure</span> <span m='2791850'>object.</span> <span m='2793040'>Apply</span>
  <span m='2793520'>that</span> <span m='2794790'>to</span> <span m='2794880'>open,</span>
  <span m='2795500'>three,</span> <span m='2796010'>close,</span> <span m='2797370'>apply,</span>
  <span m='2798640'>to</span> <span m='2799080'>open,</span> <span m='2799500'>4,</span>
  <span m='2800050'>close,</span> <span m='2800880'>apply.</span> </p><p><span m='2807390'>So</span>
  <span m='2807810'>going</span> <span m='2808060'>from</span> <span m='2808280'>this</span>
  <span m='2808540'>step to</span> <span m='2808770'>this</span> <span m='2809060'>step</span>
  <span m='2809350'>meant</span> <span m='2809690'>that</span> <span m='2809800'>I</span>
  <span m='2809910'>made</span> <span m='2810140'>up</span> <span m='2810220'>a</span>
  <span m='2810300'>procedure</span> <span m='2810690'>object</span> <span m='2811010'>which</span>
  <span m='2811180'>captured</span> <span m='2811680'>in it</span> <span m='2814000'>e0</span>
  <span m='2814580'>as</span> <span m='2814750'>part</span> <span m='2814980'>of</span>
  <span m='2815060'>the</span> <span m='2815140'>procedure</span> <span m='2815570'>object.</span>
  <span m='2817150'>Now,</span> <span m='2817370'>we're going</span> <span m='2817470'>to</span>
  <span m='2817560'>pass</span> <span m='2817890'>those</span> <span m='2818120'>to</span>
  <span m='2818240'>apply.</span> <span m='2818620'>We have to</span> <span m='2818680'>apply</span>
  <span m='2818960'>this</span> <span m='2819120'>procedure</span> <span m='2820480'>to</span>
  <span m='2820660'>that</span> <span m='2820860'>set</span> <span m='2820970'>of</span>
  <span m='2821060'>arguments.</span> <span m='2822710'>Well,</span> <span m='2822990'>but</span>
  <span m='2823130'>that</span> <span m='2823330'>procedure</span> <span m='2825730'>is</span>
  <span m='2825870'>not</span> <span m='2826110'>primitive.</span> <span m='2827380'>It's,</span>
  <span m='2827530'>in</span> <span m='2827660'>fact,</span> <span m='2827910'>a</span>
  <span m='2828340'>thing</span> <span m='2828580'>which</span> <span m='2828740'>has</span>
  <span m='2828840'>got</span> <span m='2829010'>the</span> <span m='2829100'>tag</span>
  <span m='2829380'>closure,</span> <span m='2830140'>and,</span> <span m='2830500'>therefore,</span>
  <span m='2830800'>what we</span> <span m='2830980'>have</span> <span m='2831080'>to</span>
  <span m='2831180'>do</span> <span m='2831310'>is</span> <span m='2831440'>do a</span>
  <span m='2831590'>bind.</span> </p><p><span m='2833710'>We</span> <span m='2833830'>have</span>
  <span m='2833970'>to</span> <span m='2834070'>bind.</span> <span m='2835830'>A</span>
  <span m='2835920'>new</span> <span m='2836290'>environment</span> <span m='2836840'>is</span>
  <span m='2836960'>made</span> <span m='2838760'>at</span> <span m='2838930'>this</span>
  <span m='2839100'>point,</span> <span m='2840500'>which</span> <span m='2840760'>has</span>
  <span m='2841470'>as</span> <span m='2841670'>its</span> <span m='2841850'>parent</span>
  <span m='2842280'>environment</span> <span m='2842920'>the</span> <span m='2843200'>one</span>
  <span m='2843430'>over</span> <span m='2843680'>here,</span> <span m='2844360'>e0,</span>
  <span m='2846340'>that</span> <span m='2846980'>environment.</span> <span m='2850320'>And</span>
  <span m='2850410'>we'll</span> <span m='2850530'>call</span> <span m='2850750'>this</span>
  <span m='2850840'>one,</span> <span m='2851190'>e1.</span> <span m='2854620'>Now</span>
  <span m='2854790'>what's</span> <span m='2855030'>bound</span> <span m='2855370'>in</span>
  <span m='2855450'>there?</span> <span m='2856040'>x</span> <span m='2856300'>is</span>
  <span m='2856450'>bound</span> <span m='2856810'>to</span> <span m='2856950'>three.</span>
  <span m='2858620'>So</span> <span m='2858900'>I have</span> <span m='2859200'>x</span>
  <span m='2859610'>equal</span> <span m='2860040'>three.</span> <span m='2861480'>That's</span>
  <span m='2861680'>what's</span> <span m='2861880'>in</span> <span m='2862010'>there.</span>
  <span m='2864940'>And</span> <span m='2865140'>we'll</span> <span m='2865310'>call
  that</span> <span m='2865710'>e1.</span> <span m='2866240'>So</span> <span m='2866470'>what</span>
  <span m='2866750'>this</span> <span m='2867170'>transforms</span> <span m='2867850'>into</span>
  <span m='2869170'>is</span> <span m='2869380'>an</span> <span m='2869540'>eval</span>
  <span m='2869940'>of</span> <span m='2870090'>the</span> <span m='2870170'>body</span>
  <span m='2871710'>of</span> <span m='2871940'>this,</span> <span m='2872230'>which</span>
  <span m='2872420'>is</span> <span m='2872570'>this,</span> <span m='2874420'>the</span>
  <span m='2874550'>body</span> <span m='2874930'>of that</span> <span m='2875170'>procedure,</span>
  <span m='2876450'>in</span> <span m='2876620'>the</span> <span m='2876740'>environment</span>
  <span m='2877480'>that</span> <span m='2877630'>you</span> <span m='2877780'>just</span>
  <span m='2878050'>saw.</span> </p><p><span m='2880290'>So</span> <span m='2880600'>that's</span>
  <span m='2880890'>an</span> <span m='2880990'>apply,</span> <span m='2884320'>of</span>
  <span m='2884500'>eval,</span> <span m='2887030'>quote,</span> <span m='2887310'>open,</span>
  <span m='2887700'>lambda</span> <span m='2888160'>of</span> <span m='2888490'>y,</span>
  <span m='2890950'>plus</span> <span m='2891480'>x</span> <span m='2891870'>y--</span>
  <span m='2892240'>the</span> <span m='2892360'>body--</span> <span m='2895270'>in</span>
  <span m='2895610'>e1.</span> <span m='2900660'>And</span> <span m='2900840'>apply</span>
  <span m='2901190'>the</span> <span m='2901290'>result</span> <span m='2901690'>of</span>
  <span m='2901760'>that</span> <span m='2901930'>to</span> <span m='2902090'>four,</span>
  <span m='2903810'>open,</span> <span m='2904190'>close,</span> <span m='2904760'>4--</span>
  <span m='2906040'>list of</span> <span m='2906230'>arguments.</span> <span m='2908680'>Well,</span>
  <span m='2908840'>that's</span> <span m='2909150'>sensible</span> <span m='2909620'>enough</span>
  <span m='2909950'>because</span> <span m='2910460'>evaluating</span> <span m='2911130'>a</span>
  <span m='2911190'>lambda,</span> <span m='2911510'>I</span> <span m='2911600'>know</span>
  <span m='2911730'>what</span> <span m='2911860'>to</span> <span m='2911950'>do.</span>
  </p><p><span m='2913110'>That</span> <span m='2913240'>means</span> <span m='2913430'>I</span>
  <span m='2913530'>apply,</span> <span m='2917290'>the</span> <span m='2917420'>procedure</span>
  <span m='2917930'>which</span> <span m='2918110'>is</span> <span m='2918210'>closure,</span>
  <span m='2923680'>binds</span> <span m='2924140'>one</span> <span m='2924270'>argument</span>
  <span m='2924610'>y,</span> <span m='2925010'>adds</span> <span m='2925830'>x to</span>
  <span m='2926260'>y,</span> <span m='2929290'>with</span> <span m='2929690'>e1</span>
  <span m='2929960'>captured</span> <span m='2931620'>in</span> <span m='2931820'>it.</span>
  <span m='2935790'>And</span> <span m='2935970'>you</span> <span m='2936050'>should</span>
  <span m='2936220'>really</span> <span m='2936480'>see</span> <span m='2936690'>this.</span>
  <span m='2937800'>I</span> <span m='2937990'>somehow</span> <span m='2938670'>manufactured</span>
  <span m='2939610'>a</span> <span m='2939670'>closure.</span> <span m='2940140'>I</span>
  <span m='2940210'>should've</span> <span m='2940460'>put</span> <span m='2940640'>this</span>
  <span m='2940850'>here.</span> <span m='2941790'>There</span> <span m='2941920'>was</span>
  <span m='2942030'>one</span> <span m='2942170'>over</span> <span m='2942320'>here</span>
  <span m='2942550'>too.</span> <span m='2946230'>Well,</span> <span m='2946380'>there's</span>
  <span m='2946600'>one</span> <span m='2946810'>here</span> <span m='2947040'>now.</span>
  <span m='2948080'>I've</span> <span m='2948490'>captured</span> <span m='2949240'>e1,</span>
  <span m='2950360'>and</span> <span m='2950690'>this</span> <span m='2950880'>is</span>
  <span m='2951290'>the</span> <span m='2951460'>procedure</span> <span m='2952500'>of</span>
  <span m='2952900'>one</span> <span m='2953250'>argument</span> <span m='2953710'>y,</span>
  <span m='2955770'>whatever</span> <span m='2956090'>this</span> <span m='2956415'>is.</span>
  <span m='2957880'>That's</span> <span m='2958315'>what</span> <span m='2958750'>that</span>
  <span m='2958990'>is</span> <span m='2959320'>there,</span> <span m='2959650'>that</span>
  <span m='2960140'>closure.</span> </p><p><span m='2963040'>I'm</span> <span m='2963350'>going</span>
  <span m='2963410'>to</span> <span m='2963470'>apply</span> <span m='2963900'>that</span>
  <span m='2964880'>to</span> <span m='2965950'>four.</span> <span m='2970690'>Well,</span>
  <span m='2970820'>that's</span> <span m='2971060'>easy</span> <span m='2971360'>enough.</span>
  <span m='2976830'>That</span> <span m='2977200'>means</span> <span m='2977390'>I</span>
  <span m='2977510'>have</span> <span m='2977630'>to</span> <span m='2977730'>make</span>
  <span m='2977910'>a</span> <span m='2977980'>new</span> <span m='2978150'>environment</span>
  <span m='2978930'>by</span> <span m='2979180'>copying</span> <span m='2979720'>this</span>
  <span m='2979920'>pointer,</span> <span m='2981266'>which</span> <span m='2981650'>was</span>
  <span m='2981880'>the</span> <span m='2981950'>pointer</span> <span m='2982350'>of</span>
  <span m='2982430'>the</span> <span m='2982520'>procedure,</span> <span m='2985030'>which</span>
  <span m='2985210'>binds</span> <span m='2985450'>y</span> <span m='2986030'>equal</span>
  <span m='2986350'>4</span> <span m='2987260'>with</span> <span m='2987620'>that</span>
  <span m='2988300'>environment.</span> <span m='2989540'>And</span> <span m='2990040'>here's</span>
  <span m='2990250'>my</span> <span m='2990400'>new</span> <span m='2990550'>environment,</span>
  <span m='2990905'>which</span> <span m='2991260'>I'll</span> <span m='2991630'>call</span>
  <span m='2992050'>e2.</span> <span m='2995870'>And,</span> <span m='2996250'>of</span>
  <span m='2996550'>course,</span> <span m='2996880'>this</span> <span m='2997070'>application</span>
  <span m='2997800'>then</span> <span m='2998260'>is</span> <span m='2998440'>evaluate</span>
  <span m='2998990'>the</span> <span m='2999080'>body</span> <span m='2999640'>in</span>
  <span m='2999790'>e2.</span> </p><p><span m='3001910'>So</span> <span m='3002050'>this</span>
  <span m='3002270'>is</span> <span m='3002870'>eval,</span> <span m='3006220'>the</span>
  <span m='3007480'>body,</span> <span m='3007920'>which</span> <span m='3008090'>is</span>
  <span m='3008210'>plus</span> <span m='3008720'>x</span> <span m='3009170'>y,</span>
  <span m='3010580'>in</span> <span m='3010730'>the</span> <span m='3010830'>environment</span>
  <span m='3011300'>e2.</span> <span m='3013710'>But</span> <span m='3013940'>this</span>
  <span m='3014090'>is</span> <span m='3014180'>an</span> <span m='3014220'>application,</span>
  <span m='3015490'>so</span> <span m='3015710'>this is</span> <span m='3015940'>the</span>
  <span m='3016260'>apply,</span> <span m='3019060'>of</span> <span m='3019830'>eval,</span>
  <span m='3022220'>plus</span> <span m='3022600'>in</span> <span m='3022980'>e2,</span>
  <span m='3026500'>an</span> <span m='3026720'>EVLIST,</span> <span m='3029760'>quote,</span>
  <span m='3030240'>open,</span> <span m='3030650'>x</span> <span m='3031160'>y,</span>
  <span m='3036540'>in</span> <span m='3036960'>e2.</span> <span m='3044880'>Well,
  but</span> <span m='3045140'>let's</span> <span m='3045370'>see.</span> <span m='3045590'>That</span>
  <span m='3045850'>is</span> <span m='3047610'>apply,</span> <span m='3051020'>the</span>
  <span m='3051240'>object</span> <span m='3052060'>which</span> <span m='3052290'>is</span>
  <span m='3052410'>a</span> <span m='3052480'>result</span> <span m='3052820'>of</span>
  <span m='3052970'>that</span> <span m='3053220'>and</span> <span m='3053380'>plus.</span>
  <span m='3054190'>So</span> <span m='3054650'>here</span> <span m='3054890'>we</span>
  <span m='3055020'>are</span> <span m='3055210'>in</span> <span m='3055380'>e2,</span>
  <span m='3055650'>plus</span> <span m='3055980'>is</span> <span m='3056100'>not</span>
  <span m='3056370'>here,</span> <span m='3057030'>it's</span> <span m='3057270'>not</span>
  <span m='3057510'>here,</span> <span m='3057750'>oh,</span> <span m='3057920'>yes,</span>
  <span m='3058190'>but's</span> <span m='3058420'>here</span> <span m='3058620'>as
  some</span> <span m='3058830'>primitive</span> <span m='3059170'>operator.</span>
  <span m='3061780'>So</span> <span m='3062160'>it's</span> <span m='3062390'>the</span>
  <span m='3063080'>primitive</span> <span m='3063950'>operator</span> <span m='3064350'>for</span>
  <span m='3064470'>addition.</span> <span m='3068490'>Apply</span> <span m='3068910'>that</span>
  <span m='3070230'>to</span> <span m='3070990'>the</span> <span m='3071250'>result</span>
  <span m='3071760'>of</span> <span m='3071880'>evaluating</span> <span m='3072670'>x</span>
  <span m='3072890'>and</span> <span m='3073030'>y</span> <span m='3073330'>in</span>
  <span m='3073540'>e2.</span> <span m='3074370'>But</span> <span m='3074540'>we</span>
  <span m='3074750'>can</span> <span m='3074860'>see</span> <span m='3075000'>that</span>
  <span m='3075270'>x</span> <span m='3075520'>is</span> <span m='3075680'>three</span>
  <span m='3075990'>and</span> <span m='3076430'>y</span> <span m='3076930'>is</span>
  <span m='3077343'>four.</span> <span m='3078340'>So</span> <span m='3078500'>that's</span>
  <span m='3078810'>a</span> <span m='3080200'>three</span> <span m='3080600'>and</span>
  <span m='3080820'>four,</span> <span m='3082740'>here.</span> <span m='3083936'>And</span>
  <span m='3084280'>that</span> <span m='3084650'>magically</span> <span m='3085130'>produces</span>
  <span m='3085500'>for</span> <span m='3085600'>me  a</span> <span m='3085830'>seven.</span>
  </p><p><span m='3090520'>I</span> <span m='3090650'>wanted</span> <span m='3090920'>to</span>
  <span m='3091000'>go</span> <span m='3091210'>through</span> <span m='3091420'>this</span>
  <span m='3091600'>so</span> <span m='3091690'>you</span> <span m='3091870'>would</span>
  <span m='3092010'>see,</span> <span m='3092770'>essentially,</span> <span m='3093460'>one</span>
  <span m='3093700'>important</span> <span m='3094080'>ingredient,</span> <span m='3095760'>which</span>
  <span m='3095960'>is</span> <span m='3096060'>what's</span> <span m='3096310'>being</span>
  <span m='3096610'>passed</span> <span m='3096960'>around,</span> <span m='3097230'>and</span>
  <span m='3097310'>who</span> <span m='3097520'>owns</span> <span m='3098070'>what,</span>
  <span m='3098530'>and</span> <span m='3098670'>what</span> <span m='3098790'>his</span>
  <span m='3098950'>job</span> <span m='3099290'>is.</span> <span m='3100470'>So</span>
  <span m='3100730'>what</span> <span m='3100880'>do we</span> <span m='3101080'>have</span>
  <span m='3101280'>here?</span> <span m='3101700'>We</span> <span m='3101860'>have</span>
  <span m='3102020'>eval,</span> <span m='3104370'>and</span> <span m='3104870'>we</span>
  <span m='3105020'>have</span> <span m='3105170'>apply,</span> <span m='3105590'>the</span>
  <span m='3105730'>two</span> <span m='3105870'>main</span> <span m='3106110'>players.</span>
  <span m='3109370'>And</span> <span m='3109550'>there</span> <span m='3109730'>is</span>
  <span m='3109820'>a</span> <span m='3109870'>big</span> <span m='3110120'>loop</span>
  <span m='3110360'>the</span> <span m='3110480'>goes</span> <span m='3110690'>around</span>
  <span m='3110980'>like</span> <span m='3111210'>this.</span> <span m='3112320'>Which</span>
  <span m='3112560'>is</span> <span m='3113100'>eval</span> <span m='3116730'>produces</span>
  <span m='3117960'>a</span> <span m='3118120'>procedure</span> <span m='3120580'>and</span>
  <span m='3120780'>arguments</span> <span m='3123710'>for</span> <span m='3124100'>apply.</span>
  </p><p><span m='3126270'>Now</span> <span m='3126870'>some</span> <span m='3127080'>things</span>
  <span m='3127490'>eval</span> <span m='3127690'>could do by</span> <span m='3128050'>itself.</span>
  <span m='3129710'>Those</span> <span m='3129810'>are</span> <span m='3130060'>little</span>
  <span m='3130330'>self things</span> <span m='3130730'>here.</span> <span m='3130860'>They're
  not</span> <span m='3131220'>interesting.</span> <span m='3132700'>Also</span> <span
  m='3133150'>eval</span> <span m='3133520'>evaluates</span> <span m='3134000'>all</span>
  <span m='3134140'>of</span> <span m='3134290'>the</span> <span m='3134390'>arguments,</span>
  <span m='3134840'>one</span> <span m='3135020'>after</span> <span m='3135270'>another.</span>
  <span m='3136240'>That's</span> <span m='3136460'>not</span> <span m='3136630'>very</span>
  <span m='3136840'>interesting.</span> <span m='3137650'>Apply</span> <span m='3137900'>can</span>
  <span m='3138600'>apply</span> <span m='3138800'>some</span> <span m='3139020'>procedures</span>
  <span m='3139450'>like</span> <span m='3139670'>plus,</span> <span m='3141110'>not</span>
  <span m='3141340'>very</span> <span m='3141540'>interesting.</span> <span m='3142300'>However,</span>
  <span m='3142660'>if apply</span> <span m='3143060'>can't</span> <span m='3143290'>apply</span>
  <span m='3143570'>a</span> <span m='3143640'>procedure</span> <span m='3144060'>like</span>
  <span m='3144280'>plus,</span> <span m='3145350'>it</span> <span m='3145520'>produces</span>
  <span m='3145960'>an</span> <span m='3146120'>expression</span> <span m='3147910'>and</span>
  <span m='3148100'>environment</span> <span m='3151030'>for</span> <span m='3152520'>eval.</span>
  <span m='3155470'>The</span> <span m='3155640'>procedural</span> <span m='3156180'>arguments</span>
  <span m='3157110'>wrap</span> <span m='3157440'>up</span> <span m='3158460'>essentially</span>
  <span m='3159180'>the</span> <span m='3159240'>state</span> <span m='3159610'>of</span>
  <span m='3159690'>a</span> <span m='3159770'>computation</span> <span m='3161680'>and,</span>
  <span m='3161990'>certainly,</span> <span m='3162150'>the</span> <span m='3162310'>expression
  of</span> <span m='3162770'>environment.</span> </p><p><span m='3163740'>And</span>
  <span m='3163950'>so what</span> <span m='3164130'>we're</span> <span m='3164290'>actually</span>
  <span m='3164540'>going</span> <span m='3164680'>to</span> <span m='3164810'>do</span>
  <span m='3164960'>next</span> <span m='3165360'>is</span> <span m='3165430'>not
  the</span> <span m='3165600'>complete</span> <span m='3166010'>state,</span> <span
  m='3166570'>because it</span> <span m='3166740'>doesn't</span> <span m='3167000'>say</span>
  <span m='3167570'>who</span> <span m='3167850'>wants</span> <span m='3168170'>the</span>
  <span m='3168290'>answers.</span> <span m='3171280'>But</span> <span m='3171420'>what</span>
  <span m='3171560'>we're</span> <span m='3171660'>going</span> <span m='3171760'>to</span>
  <span m='3171870'>do--</span> <span m='3172180'>it's</span> <span m='3172370'>always</span>
  <span m='3172680'>got</span> <span m='3172960'>something</span> <span m='3173290'>like</span>
  <span m='3173500'>an</span> <span m='3173630'>expression of</span> <span m='3174130'>environment</span>
  <span m='3174950'>or</span> <span m='3175160'>procedure</span> <span m='3175440'>and</span>
  <span m='3175720'>arguments</span> <span m='3176360'>as</span> <span m='3176580'>the</span>
  <span m='3176680'>main</span> <span m='3176990'>loop</span> <span m='3177170'>that</span>
  <span m='3177300'>we're</span> <span m='3177390'>going</span> <span m='3177610'>around.</span>
  </p><p><span m='3178970'>There are</span> <span m='3179220'>minor</span> <span m='3179570'>little</span>
  <span m='3179810'>sub</span> <span m='3180060'>loops</span> <span m='3180340'>like</span>
  <span m='3181140'>eval</span> <span m='3181300'>through</span> <span m='3181500'>EVLIST,</span>
  <span m='3184400'>or</span> <span m='3185310'>eval</span> <span m='3185620'>through</span>
  <span m='3185930'>evcond,</span> <span m='3189290'>or</span> <span m='3189550'>apply</span>
  <span m='3190350'>through</span> <span m='3190960'>a</span> <span m='3191030'>primitive</span>
  <span m='3191380'>apply.</span> <span m='3196140'>But</span> <span m='3196420'>they're</span>
  <span m='3196550'>not</span> <span m='3196740'>the</span> <span m='3196860'>essential</span>
  <span m='3197310'>things.</span> <span m='3198500'>So</span> <span m='3198890'>that's</span>
  <span m='3199210'>what</span> <span m='3199300'>I</span> <span m='3199380'>wanted</span>
  <span m='3199720'>you to</span> <span m='3199930'>see.</span> <span m='3201860'>Are</span>
  <span m='3201970'>there</span> <span m='3202110'>any</span> <span m='3202220'>questions?</span>
  <span m='3205930'>Yes.</span> </p><p><span m='3208690'>AUDIENCE:</span> <span m='3209180'>I'm</span>
  <span m='3209380'>trying</span> <span m='3209590'>to</span> <span m='3209800'>understand</span>
  <span m='3210380'>how</span> <span m='3211230'>x</span> <span m='3211560'>got</span>
  <span m='3211800'>down</span> <span m='3212210'>to</span> <span m='3212670'>three</span>
  <span m='3215260'>instead</span> <span m='3215640'>of</span> <span m='3215710'>four.</span>
  <span m='3217070'>At</span> <span m='3217190'>the</span> <span m='3217520'>early</span>
  <span m='3217800'>part</span> <span m='3218120'>of</span> <span m='3218250'>the--</span>
  </p><p><span m='3218540'>PROFESSOR:</span> <span m='3220050'>Here.</span> <span
  m='3221310'>You</span> <span m='3221470'>want</span> <span m='3221670'>to</span>
  <span m='3221750'>know</span> <span m='3222040'>how</span> <span m='3222300'>x</span>
  <span m='3222540'>got</span> <span m='3222720'>down</span> <span m='3222920'>to</span>
  <span m='3222980'>three?</span> </p><p><span m='3223310'>AUDIENCE:</span> <span
  m='3223650'>Because</span> <span m='3223900'>x</span> <span m='3224390'>is</span>
  <span m='3224700'>the</span> <span m='3224930'>outer</span> <span m='3226450'>procedure,</span>
  <span m='3228550'>and</span> <span m='3228700'>x</span> <span m='3229140'>and</span>
  <span m='3229380'>y</span> <span m='3229770'>are the</span> <span m='3230010'>inner</span>
  <span m='3230260'>procedure.</span> </p><p><span m='3231040'>PROFESSOR:</span> <span
  m='3231270'>Fine.</span> <span m='3232570'>Well,</span> <span m='3232990'>I</span>
  <span m='3233220'>was</span> <span m='3233380'>very</span> <span m='3233580'>careful</span>
  <span m='3233910'>and</span> <span m='3233960'>mechanical.</span> <span m='3235280'>First</span>
  <span m='3235520'>of</span> <span m='3235580'>all,</span> <span m='3235820'>I should</span>
  <span m='3235990'>write</span> <span m='3236250'>those</span> <span m='3236470'>procedures</span>
  <span m='3236930'>again</span> <span m='3237230'>for</span> <span m='3237350'>you,</span>
  <span m='3237790'>pretty</span> <span m='3238080'>printed.</span> <span m='3240610'>First</span>
  <span m='3240930'>order</span> <span m='3241100'>of</span> <span m='3241150'>business,</span>
  <span m='3241440'>because</span> <span m='3241650'>you're</span> <span m='3241740'>probably</span>
  <span m='3242050'>not</span> <span m='3242260'>reading</span> <span m='3242550'>them</span>
  <span m='3242680'>well.</span> </p><p><span m='3243830'>So</span> <span m='3244030'>I</span>
  <span m='3244180'>have</span> <span m='3244330'>here</span> <span m='3245050'>that</span>
  <span m='3245530'>procedure</span> <span m='3247410'>of--</span> <span m='3248500'>was
  it</span> <span m='3248790'>x</span> <span m='3249090'>over</span> <span m='3249240'>there--</span>
  <span m='3251280'>which</span> <span m='3251550'>is--</span> <span m='3252690'>value</span>
  <span m='3253290'>of</span> <span m='3253450'>that</span> <span m='3253610'>procedure</span>
  <span m='3254030'>of</span> <span m='3254240'>y,</span> <span m='3255820'>which</span>
  <span m='3256210'>adds</span> <span m='3257230'>x</span> <span m='3257590'>to</span>
  <span m='3257790'>y,</span> <span m='3259600'>lambda,</span> <span m='3260710'>lambda,</span>
  <span m='3261430'>applied</span> <span m='3261980'>that</span> <span m='3262250'>to</span>
  <span m='3262360'>three,</span> <span m='3264100'>takes</span> <span m='3264410'>the</span>
  <span m='3264460'>result</span> <span m='3264840'>of</span> <span m='3265030'>that,</span>
  <span m='3265220'>and applied</span> <span m='3265540'>that</span> <span m='3265730'>to</span>
  <span m='3265810'>four.</span> <span m='3266140'>Is that</span> <span m='3266270'>not</span>
  <span m='3266580'>what</span> <span m='3266680'>I</span> <span m='3266750'>wrote?</span>
  </p><p><span m='3268810'>Now,</span> <span m='3270260'>you</span> <span m='3270430'>should</span>
  <span m='3270580'>immediately</span> <span m='3271050'>see</span> <span m='3271900'>that</span>
  <span m='3273670'>here is</span> <span m='3274070'>an</span> <span m='3274170'>application--</span>
  <span m='3275150'>let</span> <span m='3275240'>me</span> <span m='3275410'>get</span>
  <span m='3275640'>a white</span> <span m='3275800'>piece</span> <span m='3275990'>of</span>
  <span m='3276090'>chalk--</span> <span m='3277400'>here</span> <span m='3277730'>is</span>
  <span m='3278370'>an</span> <span m='3278510'>application,</span> <span m='3279986'>a</span>
  <span m='3280360'>combination.</span> <span m='3284300'>That</span> <span m='3284560'>combination</span>
  <span m='3285100'>has</span> <span m='3285310'>this</span> <span m='3285480'>as</span>
  <span m='3285620'>the</span> <span m='3285730'>operator</span> <span m='3288270'>and</span>
  <span m='3288470'>this</span> <span m='3288640'>as</span> <span m='3288780'>the</span>
  <span m='3288900'>operand.</span> <span m='3291040'>The</span> <span m='3291380'>three</span>
  <span m='3291830'>is</span> <span m='3292000'>going</span> <span m='3292260'>in
  for</span> <span m='3292430'>the</span> <span m='3292610'>x</span> <span m='3292880'>here.</span>
  <span m='3294900'>The</span> <span m='3295220'>result</span> <span m='3295810'>of</span>
  <span m='3295990'>this</span> <span m='3296590'>is</span> <span m='3296770'>a</span>
  <span m='3296830'>procedure</span> <span m='3297400'>of</span> <span m='3297540'>one</span>
  <span m='3297680'>argument</span> <span m='3298010'>y,</span> <span m='3298720'>which</span>
  <span m='3298970'>gets</span> <span m='3299210'>applied to</span> <span m='3299520'>four.</span>
  <span m='3301530'>So</span> <span m='3301980'>you</span> <span m='3302250'>just</span>
  <span m='3302520'>weren't</span> <span m='3302810'>reading</span> <span m='3303120'>the</span>
  <span m='3303180'>expression</span> <span m='3303850'>right.</span> </p><p><span
  m='3304190'>The</span> <span m='3304530'>way</span> <span m='3304740'>you</span>
  <span m='3304840'>see</span> <span m='3305010'>that</span> <span m='3305200'>over</span>
  <span m='3305370'>here</span> <span m='3309420'>is</span> <span m='3309710'>that</span>
  <span m='3310570'>here</span> <span m='3310890'>I</span> <span m='3311120'>have
  the</span> <span m='3311240'>actual</span> <span m='3311580'>procedure</span> <span
  m='3312010'>object,</span> <span m='3312490'>x.</span> <span m='3313340'>It's</span>
  <span m='3314280'>getting</span> <span m='3314460'>applied</span> <span m='3314820'>to</span>
  <span m='3314900'>three,</span> <span m='3315670'>the</span> <span m='3316030'>list</span>
  <span m='3316340'>containing</span> <span m='3316700'>three.</span> <span m='3318980'>What</span>
  <span m='3319120'>I'm</span> <span m='3319170'>left</span> <span m='3319500'>over</span>
  <span m='3319710'>with is</span> <span m='3319920'>something</span> <span m='3320230'>which</span>
  <span m='3320350'>gets</span> <span m='3320520'>applied</span> <span m='3320930'>to</span>
  <span m='3321250'>four.</span> <span m='3324080'>Are</span> <span m='3324210'>there</span>
  <span m='3324320'>any</span> <span m='3324440'>other</span> <span m='3324590'>questions?</span>
  <span m='3328600'>Time</span> <span m='3328820'>for</span> <span m='3328980'>our</span>
  <span m='3329290'>next</span> <span m='3329690'>small</span> <span m='3329840'>break</span>
  <span m='3330100'>then.</span> <span m='3330900'>Thank</span> <span m='3331140'>you.</span>
  <span m='3333735'>[MUSIC PLAYING]</span> </p><p><span m='3368410'>Let's</span> <span
  m='3368730'>see,</span> <span m='3370490'>at</span> <span m='3370700'>this</span>
  <span m='3370920'>point,</span> <span m='3373400'>you</span> <span m='3373520'>should</span>
  <span m='3373660'>be</span> <span m='3373790'>getting</span> <span m='3374090'>the</span>
  <span m='3374180'>feeling,</span> <span m='3374730'>what's</span> <span m='3375090'>this</span>
  <span m='3375390'>nonsense</span> <span m='3376000'>this</span> <span m='3376210'>Sussman</span>
  <span m='3376630'>character</span> <span m='3376955'>is</span> <span m='3377280'>feeding</span>
  <span m='3377710'>me?</span> <span m='3380740'>There's</span> <span m='3380950'>an</span>
  <span m='3381520'>awful</span> <span m='3381860'>lot</span> <span m='3382010'>of</span>
  <span m='3382170'>strange</span> <span m='3382600'>nonsense</span> <span m='3383640'>here.</span>
  <span m='3384800'>After</span> <span m='3385220'>all,</span> <span m='3385510'>he</span>
  <span m='3385710'>purported</span> <span m='3386200'>to</span> <span m='3386350'>explain</span>
  <span m='3386860'>to</span> <span m='3386950'>me</span> <span m='3387130'>Lisp,</span>
  <span m='3387690'>and</span> <span m='3388110'>he</span> <span m='3388300'>wrote</span>
  <span m='3388550'>me a  Lisp</span> <span m='3388860'>program</span> <span m='3389250'>on</span>
  <span m='3389330'>the</span> <span m='3389410'>blackboard.</span> </p><p><span m='3390892'>The</span>
  <span m='3391350'>Lisp</span> <span m='3391680'>program</span> <span m='3392070'>was</span>
  <span m='3392200'>intended</span> <span m='3392510'>to</span> <span m='3392580'>be</span>
  <span m='3392690'>interpreted</span> <span m='3393160'>for</span> <span m='3393240'>Lisp,</span>
  <span m='3393560'>but</span> <span m='3393910'>you</span> <span m='3394050'>need</span>
  <span m='3394190'>a</span> <span m='3394230'>Lisp</span> <span m='3394510'>interpreter</span>
  <span m='3394990'>in</span> <span m='3395150'>order to</span> <span m='3395280'>understand</span>
  <span m='3395700'>that</span> <span m='3395870'>program.</span> <span m='3398370'>How</span>
  <span m='3398610'>could</span> <span m='3398730'>that</span> <span m='3398900'>program</span>
  <span m='3399210'>have</span> <span m='3399320'>told</span> <span m='3399560'>me</span>
  <span m='3399720'>anything</span> <span m='3400100'>there</span> <span m='3400300'>is</span>
  <span m='3400800'>to</span> <span m='3401160'>be</span> <span m='3401310'>known</span>
  <span m='3402490'>about</span> <span m='3402840'>Lisp?</span> <span m='3404150'>How</span>
  <span m='3404410'>is</span> <span m='3404520'>that</span> <span m='3404560'>not</span>
  <span m='3404730'>completely</span> <span m='3405370'>vacuous?</span> <span m='3408490'>It's</span>
  <span m='3408580'>a</span> <span m='3408690'>very</span> <span m='3409230'>strange</span>
  <span m='3409880'>thing.</span> <span m='3410990'>Does</span> <span m='3411190'>it</span>
  <span m='3411280'>tell</span> <span m='3411430'>me</span> <span m='3411570'>anything</span>
  <span m='3411930'>at</span> <span m='3412010'>all?</span> </p><p><span m='3416070'>Well,
  you</span> <span m='3416290'>see,</span> <span m='3416450'>the</span> <span m='3416550'>whole</span>
  <span m='3416770'>thing</span> <span m='3417000'>is</span> <span m='3417300'>sort</span>
  <span m='3417510'>of</span> <span m='3417710'>like</span> <span m='3418090'>these</span>
  <span m='3418760'>Escher's</span> <span m='3419230'>hands</span> <span m='3420050'>that</span>
  <span m='3420700'>we</span> <span m='3420820'>see</span> <span m='3422380'>on</span>
  <span m='3422650'>this</span> <span m='3422780'>slide.</span> <span m='3426180'>Yes,</span>
  <span m='3426540'>eval</span> <span m='3426690'>and</span> <span m='3427130'>apply</span>
  <span m='3427830'>each</span> <span m='3428930'>sort</span> <span m='3429180'>of</span>
  <span m='3429400'>draw</span> <span m='3429630'>each</span> <span m='3429830'>other</span>
  <span m='3431550'>and</span> <span m='3431750'>construct</span> <span m='3433300'>the</span>
  <span m='3433380'>real</span> <span m='3433670'>thing,</span> <span m='3434960'>which</span>
  <span m='3435210'>can</span> <span m='3435560'>sit out and</span> <span m='3435950'>draw</span>
  <span m='3436390'>itself.</span> <span m='3437110'>Escher</span> <span m='3437370'>was</span>
  <span m='3437500'>a</span> <span m='3437570'>very</span> <span m='3437790'>brilliant</span>
  <span m='3438130'>man,</span> <span m='3438720'>he</span> <span m='3438820'>just</span>
  <span m='3438950'>didn't</span> <span m='3439040'>know</span> <span m='3439170'>the</span>
  <span m='3439300'>names</span> <span m='3439680'>of</span> <span m='3439760'>these</span>
  <span m='3439900'>spirits.</span> </p><p><span m='3443910'>Well,</span> <span m='3444130'>I'm</span>
  <span m='3444190'>going to</span> <span m='3444380'>do</span> <span m='3444530'>now,</span>
  <span m='3446130'>is</span> <span m='3446370'>I'm going to</span> <span m='3446450'>try</span>
  <span m='3446700'>to</span> <span m='3447210'>convince</span> <span m='3447700'>you</span>
  <span m='3448060'>that</span> <span m='3448410'>both</span> <span m='3448790'>this</span>
  <span m='3449050'>mean</span> <span m='3449350'>something,</span> <span m='3450110'>and,</span>
  <span m='3450520'>as</span> <span m='3450680'>a</span> <span m='3451360'>aside,</span>
  <span m='3453060'>I'm going to</span> <span m='3453180'>show</span> <span m='3453340'>you</span>
  <span m='3453510'>why you</span> <span m='3453710'>don't need</span> <span m='3453990'>definitions.</span>
  <span m='3456090'>Just</span> <span m='3456250'>turns</span> <span m='3456510'>out</span>
  <span m='3456770'>that</span> <span m='3457040'>that</span> <span m='3457160'>sort
  of falls</span> <span m='3457510'>out,</span> <span m='3458100'>why</span> <span
  m='3458250'>definitions</span> <span m='3458760'>are</span> <span m='3458930'>not</span>
  <span m='3459090'>essential</span> <span m='3459860'>in</span> <span m='3459960'>a</span>
  <span m='3460010'>mathematical</span> <span m='3460660'>sense</span> <span m='3462530'>for</span>
  <span m='3462720'>doing</span> <span m='3462990'>all</span> <span m='3463120'>the</span>
  <span m='3463260'>things</span> <span m='3463510'>we</span> <span m='3463630'>need</span>
  <span m='3463850'>to</span> <span m='3463930'>do</span> <span m='3464300'>for</span>
  <span m='3464460'>computing.</span> </p><p><span m='3469070'>Well,</span> <span
  m='3469260'>let's</span> <span m='3469480'>see</span> <span m='3469730'>here.</span>
  <span m='3470690'>Consider</span> <span m='3471430'>the</span> <span m='3471770'>following</span>
  <span m='3472220'>small</span> <span m='3472650'>program,</span> <span m='3473790'>what</span>
  <span m='3473910'>does</span> <span m='3474020'>it</span> <span m='3474150'>mean?</span>
  <span m='3474870'>This is a</span> <span m='3475080'>program</span> <span m='3475810'>for</span>
  <span m='3475950'>computing</span> <span m='3476760'>exponentials.</span> </p><p><span
  m='3487270'>The</span> <span m='3487480'>exponential</span> <span m='3488710'>of</span>
  <span m='3490000'>x</span> <span m='3490320'>to</span> <span m='3490430'>the</span>
  <span m='3490620'>nth</span> <span m='3490930'>power</span> <span m='3492500'>is</span>
  <span m='3492890'>if--</span> <span m='3496910'>and</span> <span m='3497250'>is</span>
  <span m='3497460'>zero,</span> <span m='3499200'>then</span> <span m='3499410'>the</span>
  <span m='3499510'>result</span> <span m='3500050'>is</span> <span m='3500210'>one.</span>
  <span m='3502070'>Otherwise,</span> <span m='3505590'>I</span> <span m='3505740'>want</span>
  <span m='3506140'>the</span> <span m='3506530'>product</span> <span m='3507780'>of</span>
  <span m='3508030'>x</span> <span m='3508810'>and</span> <span m='3508920'>the</span>
  <span m='3509030'>result of</span> <span m='3509520'>exponentiating</span> <span
  m='3512230'>x</span> <span m='3512730'>to</span> <span m='3512820'>the</span> <span
  m='3512960'>n</span> <span m='3513020'>minus</span> <span m='3513300'>one</span>
  <span m='3513510'>power.</span> <span m='3522858'>I</span> <span m='3523360'>think</span>
  <span m='3523680'>I</span> <span m='3524000'>got</span> <span m='3524160'>it</span>
  <span m='3524230'>right.</span> </p><p><span m='3526630'>Now</span> <span m='3526890'>this</span>
  <span m='3527120'>is</span> <span m='3527260'>a</span> <span m='3527560'>recursive</span>
  <span m='3528090'>definition.</span> <span m='3529470'>It's</span> <span m='3529710'>a</span>
  <span m='3530200'>definition</span> <span m='3530910'>of</span> <span m='3531070'>the</span>
  <span m='3531180'>exponentiation</span> <span m='3532470'>procedure</span> <span
  m='3533760'>in</span> <span m='3533930'>terms</span> <span m='3534230'>of</span>
  <span m='3534320'>itself.</span> <span m='3536410'>And,</span> <span m='3536750'>as</span>
  <span m='3537080'>it has</span> <span m='3537240'>been</span> <span m='3537390'>mentioned</span>
  <span m='3537750'>before,</span> <span m='3539380'>your</span> <span m='3540230'>high</span>
  <span m='3540450'>school</span> <span m='3540710'>geometry</span> <span m='3541220'>teacher</span>
  <span m='3541820'>probably</span> <span m='3542140'>gave</span> <span m='3542330'>you</span>
  <span m='3542410'>a</span> <span m='3542440'>hard</span> <span m='3542790'>time</span>
  <span m='3543010'>about</span> <span m='3543260'>things</span> <span m='3543470'>like</span>
  <span m='3543690'>that.</span> <span m='3545650'>Was</span> <span m='3545810'>that</span>
  <span m='3546010'>justified?</span> <span m='3547910'>Why</span> <span m='3548360'>does</span>
  <span m='3548600'>this</span> <span m='3548990'>self</span> <span m='3549550'>referential</span>
  <span m='3550190'>definition</span> <span m='3550980'>make</span> <span m='3551290'>any</span>
  <span m='3551580'>sense?</span> </p><p><span m='3553430'>Well,</span> <span m='3553580'>first</span>
  <span m='3553760'>of all,</span> <span m='3553890'>I'm</span> <span m='3554120'>going
  to</span> <span m='3554230'>convince</span> <span m='3554550'>you</span> <span m='3554680'>that</span>
  <span m='3554800'>your</span> <span m='3554910'>high</span> <span m='3555060'>school</span>
  <span m='3555280'>geometry</span> <span m='3555710'>teacher</span> <span m='3556500'>was</span>
  <span m='3556690'>I</span> <span m='3556820'>telling</span> <span m='3557090'>you</span>
  <span m='3557190'>nonsense.</span> <span m='3560370'>Consider</span> <span m='3560760'>the</span>
  <span m='3560860'>following</span> <span m='3561280'>set</span> <span m='3561490'>of</span>
  <span m='3562400'>definitions</span> <span m='3563190'>here.</span> <span m='3564490'>x</span>
  <span m='3565140'>plus</span> <span m='3565710'>y</span> <span m='3566490'>equals</span>
  <span m='3566970'>three,</span> <span m='3568280'>and</span> <span m='3568980'>x</span>
  <span m='3569510'>minus</span> <span m='3570000'>y</span> <span m='3571010'>equal</span>
  <span m='3571710'>one.</span> <span m='3573070'>Well,</span> <span m='3573250'>gee,</span>
  <span m='3574010'>this</span> <span m='3574250'>tells</span> <span m='3574500'>you</span>
  <span m='3574620'>x</span> <span m='3574850'>in</span> <span m='3574950'>terms</span>
  <span m='3575190'>of</span> <span m='3575290'>y,</span> <span m='3575600'>and</span>
  <span m='3575710'>this</span> <span m='3575850'>one</span> <span m='3575980'>tells</span>
  <span m='3576170'>you</span> <span m='3576280'>y</span> <span m='3576500'>in</span>
  <span m='3576560'>terms</span> <span m='3576780'>of</span> <span m='3576890'>x,</span>
  <span m='3577150'>presumably.</span> <span m='3580150'>And</span> <span m='3580340'>yet</span>
  <span m='3580510'>this</span> <span m='3580660'>happens</span> <span m='3580920'>to  have</span>
  <span m='3581180'>a</span> <span m='3581220'>unique</span> <span m='3581600'>solution</span>
  <span m='3582140'>in</span> <span m='3582270'>x</span> <span m='3582470'>and</span>
  <span m='3582570'>y.</span> </p><p><span m='3595910'>However,</span> <span m='3597090'>I</span>
  <span m='3597290'>could</span> <span m='3597400'>also</span> <span m='3597730'>write</span>
  <span m='3599530'>two</span> <span m='3600390'>x</span> <span m='3600860'>plus</span>
  <span m='3601330'>two</span> <span m='3601740'>y</span> <span m='3603530'>is</span>
  <span m='3603840'>six.</span> <span m='3606600'>These</span> <span m='3607160'>two</span>
  <span m='3607330'>equations</span> <span m='3608370'>have</span> <span m='3608570'>an</span>
  <span m='3608670'>infinite</span> <span m='3608990'>number</span> <span m='3609270'>solutions.</span>
  <span m='3615730'>And</span> <span m='3615880'>I</span> <span m='3615970'>could</span>
  <span m='3616130'>write</span> <span m='3616400'>you,</span> <span m='3616570'>for</span>
  <span m='3616800'>example,</span> <span m='3618970'>x</span> <span m='3619480'>minus</span>
  <span m='3619990'>y</span> <span m='3620610'>equal</span> <span m='3621010'>2,</span>
  <span m='3621520'>and</span> <span m='3621900'>these</span> <span m='3622600'>two</span>
  <span m='3622760'>equations</span> <span m='3623260'>have</span> <span m='3623430'>no</span>
  <span m='3623680'>solutions.</span> </p><p><span m='3629820'>Well,</span> <span
  m='3630000'>I</span> <span m='3630080'>have</span> <span m='3630300'>here</span>
  <span m='3630470'>three</span> <span m='3630830'>sets</span> <span m='3631150'>of</span>
  <span m='3631250'>simultaneous</span> <span m='3632030'>linear</span> <span m='3632350'>equations,</span>
  <span m='3635500'>this</span> <span m='3635860'>set,</span> <span m='3637180'>this</span>
  <span m='3637910'>set,</span> <span m='3638790'>and</span> <span m='3639000'>this</span>
  <span m='3639130'>set.</span> <span m='3639510'>But</span> <span m='3639730'>they</span>
  <span m='3640190'>have</span> <span m='3640400'>different</span> <span m='3640690'>numbers</span>
  <span m='3641020'>of</span> <span m='3641100'>solutions.</span> <span m='3642900'>The</span>
  <span m='3643070'>number</span> <span m='3643360'>of</span> <span m='3643420'>solutions</span>
  <span m='3643870'>is</span> <span m='3643960'>not</span> <span m='3644190'>in</span>
  <span m='3644260'>the</span> <span m='3644330'>form</span> <span m='3644810'>of
  the</span> <span m='3644940'>equations.</span> <span m='3645760'>They</span> <span
  m='3646540'>all</span> <span m='3646820'>three</span> <span m='3647040'>sets</span>
  <span m='3647300'>have</span> <span m='3647390'>the</span> <span m='3647460'>same</span>
  <span m='3647740'>form.</span> <span m='3648350'>The</span> <span m='3648730'>number</span>
  <span m='3648990'>of</span> <span m='3649060'>solutions</span> <span m='3649560'>is</span>
  <span m='3649780'>in the</span> <span m='3649880'>content.</span> </p><p><span m='3653000'>I</span>
  <span m='3653140'>can't</span> <span m='3653570'>tell</span> <span m='3653790'>by</span>
  <span m='3653920'>looking</span> <span m='3654180'>at</span> <span m='3654270'>the</span>
  <span m='3654350'>form</span> <span m='3654640'>of</span> <span m='3654740'>a</span>
  <span m='3654800'>definition</span> <span m='3655270'>whether</span> <span m='3655510'>it</span>
  <span m='3655570'>makes</span> <span m='3655830'>sense,</span> <span m='3656950'>only</span>
  <span m='3657210'>by</span> <span m='3657380'>its</span> <span m='3657560'>detailed</span>
  <span m='3658060'>content.</span> <span m='3659660'>What</span> <span m='3659810'>are</span>
  <span m='3659960'>the</span> <span m='3660080'>coefficients,</span> <span m='3661380'>for</span>
  <span m='3661590'>example,</span> <span m='3662060'>in</span> <span m='3662110'>the</span>
  <span m='3662170'>case</span> <span m='3662370'>of</span> <span m='3662460'>linear</span>
  <span m='3662760'>equations?</span> <span m='3665100'>So</span> <span m='3665230'>I</span>
  <span m='3665300'>shouldn't</span> <span m='3665530'>expect</span> <span m='3666030'>to</span>
  <span m='3666110'>be</span> <span m='3666220'>able</span> <span m='3666350'>to</span>
  <span m='3666440'>tell</span> <span m='3666990'>looking</span> <span m='3667320'>at</span>
  <span m='3667440'>something</span> <span m='3667790'>like</span> <span m='3668010'>this,</span>
  <span m='3668600'>from</span> <span m='3668800'>some</span> <span m='3668990'>simple</span>
  <span m='3669350'>things</span> <span m='3669630'>like,</span> <span m='3670120'>oh</span>
  <span m='3670320'>yes,</span> <span m='3671500'>EXPT</span> <span m='3672250'>is</span>
  <span m='3672380'>the</span> <span m='3672460'>solution</span> <span m='3672950'>of</span>
  <span m='3673100'>this</span> <span m='3673280'>recursion</span> <span m='3673860'>equation.</span>
  <span m='3676030'>Expt</span> <span m='3677390'>is</span> <span m='3677660'>the</span>
  <span m='3677780'>procedure</span> <span m='3678940'>which</span> <span m='3679250'>if</span>
  <span m='3679950'>substituted</span> <span m='3680510'>in</span> <span m='3680650'>here,</span>
  <span m='3682110'>gives</span> <span m='3682400'>me</span> <span m='3682960'>EXPT</span>
  <span m='3683590'>back.</span> </p><p><span m='3686040'>I</span> <span m='3686160'>can't</span>
  <span m='3686590'>tell,</span> <span m='3688100'>looking</span> <span m='3688440'>at</span>
  <span m='3688590'>this</span> <span m='3688740'>form,</span> <span m='3689850'>whether</span>
  <span m='3690050'>or</span> <span m='3690090'>not</span> <span m='3690490'>there's</span>
  <span m='3690700'>a</span> <span m='3690750'>single,</span> <span m='3691060'>unique</span>
  <span m='3691410'>solution</span> <span m='3691820'>for</span> <span m='3691950'>EXPT,</span>
  <span m='3693270'>an</span> <span m='3693420'>infinite</span> <span m='3693710'>number
  of</span> <span m='3693970'>solutions,</span> <span m='3694450'>or</span> <span
  m='3694560'>no</span> <span m='3694700'>solutions.</span> <span m='3697200'>It's</span>
  <span m='3697540'>got</span> <span m='3697640'>to</span> <span m='3697750'>be</span>
  <span m='3697860'>how</span> <span m='3698040'>it</span> <span m='3698160'>counts</span>
  <span m='3698600'>and</span> <span m='3698720'>things</span> <span m='3698930'>like</span>
  <span m='3699140'>that,</span> <span m='3699380'>the</span> <span m='3699470'>details.</span>
  <span m='3700490'>And it's</span> <span m='3701020'>harder</span> <span m='3701370'>in</span>
  <span m='3701450'>programming</span> <span m='3701970'>than</span> <span m='3702050'>linear</span>
  <span m='3702230'>algebra.</span> <span m='3702900'>There</span> <span m='3703520'>aren't</span>
  <span m='3703730'>too</span> <span m='3703880'>many</span> <span m='3704070'>theorems</span>
  <span m='3704410'>about</span> <span m='3704660'>it</span> <span m='3704740'>in</span>
  <span m='3704820'>programming.</span> </p><p><span m='3708450'>Well, I</span> <span
  m='3708580'>want</span> <span m='3708760'>to</span> <span m='3709620'>rewrite</span>
  <span m='3710060'>these</span> <span m='3710240'>equations</span> <span m='3710730'>a</span>
  <span m='3710780'>little</span> <span m='3710990'>bit,</span> <span m='3711860'>these</span>
  <span m='3713130'>over</span> <span m='3713340'>here.</span> <span m='3713970'>Because</span>
  <span m='3714250'>what</span> <span m='3714400'>we're</span> <span m='3714550'>investigating</span>
  <span m='3715250'>is</span> <span m='3715560'>equations</span> <span m='3716130'>like</span>
  <span m='3716360'>this.</span> <span m='3716770'>But</span> <span m='3717080'>I</span>
  <span m='3717210'>want</span> <span m='3717340'>to</span> <span m='3717470'>play</span>
  <span m='3717700'>a</span> <span m='3717770'>little</span> <span m='3718100'>with</span>
  <span m='3718420'>equations like</span> <span m='3718570'>this</span> <span m='3718710'>that</span>
  <span m='3718820'>we</span> <span m='3718920'>understand,</span> <span m='3720730'>just</span>
  <span m='3720910'>so</span> <span m='3720990'>we</span> <span m='3721070'>get</span>
  <span m='3721280'>some</span> <span m='3721430'>insight</span> <span m='3721850'>into</span>
  <span m='3722050'>this</span> <span m='3722230'>kind</span> <span m='3722380'>of</span>
  <span m='3722530'>question.</span> <span m='3724730'>We</span> <span m='3724910'>could</span>
  <span m='3725050'>rewrite</span> <span m='3725410'>our</span> <span m='3725650'>equations</span>
  <span m='3726130'>here,</span> <span m='3726790'>say</span> <span m='3727020'>these</span>
  <span m='3727420'>two,</span> <span m='3727550'>the</span> <span m='3727650'>ones</span>
  <span m='3727870'>that</span> <span m='3727950'>are</span> <span m='3728060'>interesting,</span>
  <span m='3729800'>as</span> <span m='3731500'>x</span> <span m='3732100'>equals</span>
  <span m='3733410'>three</span> <span m='3733900'>minus</span> <span m='3734350'>y,</span>
  <span m='3735860'>and</span> <span m='3736140'>y</span> <span m='3737070'>equals</span>
  <span m='3738250'>x</span> <span m='3738700'>minus</span> <span m='3739120'>one.</span>
  <span m='3742010'>What</span> <span m='3742470'>do we</span> <span m='3742590'>call</span>
  <span m='3742900'>this</span> <span m='3743090'>transformation?</span> <span m='3744050'>This
  is a</span> <span m='3744290'>linear</span> <span m='3744690'>transformation,</span>
  <span m='3745830'>t.</span> </p><p><span m='3749430'>Then</span> <span m='3749630'>what</span>
  <span m='3749780'>we're</span> <span m='3749870'>getting</span> <span m='3750210'>here</span>
  <span m='3751110'>is</span> <span m='3751270'>an</span> <span m='3751380'>equation</span>
  <span m='3753100'>x</span> <span m='3753430'>y</span> <span m='3755390'>equals</span>
  <span m='3756330'>t</span> <span m='3756700'>of</span> <span m='3756840'>x</span>
  <span m='3757070'>y.</span> <span m='3762990'>What</span> <span m='3763130'>am I</span>
  <span m='3763280'>looking</span> <span m='3763590'>for?</span> <span m='3764560'>I'm</span>
  <span m='3764750'>looking</span> <span m='3764980'>for</span> <span m='3765110'>a</span>
  <span m='3765160'>fixed</span> <span m='3765480'>point</span> <span m='3765680'>of</span>
  <span m='3765790'>t.</span> <span m='3767040'>The</span> <span m='3767160'>solution</span>
  <span m='3772030'>is</span> <span m='3772330'>a</span> <span m='3772980'>fixed</span>
  <span m='3773460'>point</span> <span m='3778580'>of</span> <span m='3779040'>t.</span>
  </p><p><span m='3781910'>So</span> <span m='3782160'>the</span> <span m='3782290'>methods</span>
  <span m='3782660'>we</span> <span m='3782830'>should</span> <span m='3783010'>have</span>
  <span m='3783240'>for</span> <span m='3783350'>looking</span> <span m='3783690'>for</span>
  <span m='3784160'>solutions</span> <span m='3784690'>to</span> <span m='3784830'>equations,</span>
  <span m='3785930'>if</span> <span m='3786180'>I</span> <span m='3786310'>can</span>
  <span m='3786480'>do</span> <span m='3786630'>it</span> <span m='3786730'>by</span>
  <span m='3786890'>fixed</span> <span m='3787200'>points,</span> <span m='3788720'>might</span>
  <span m='3789090'>be</span> <span m='3789230'>applicable.</span> <span m='3790880'>If</span>
  <span m='3791050'>I</span> <span m='3791130'>have</span> <span m='3791260'>a</span>
  <span m='3791320'>means</span> <span m='3791600'>of</span> <span m='3791690'>finding</span>
  <span m='3792070'>a</span> <span m='3792130'>solution</span> <span m='3792570'>to
  an</span> <span m='3792720'>equations</span> <span m='3793490'>by</span> <span m='3793710'>fixed</span>
  <span m='3793970'>points--</span> <span m='3795690'>just,</span> <span m='3797480'>might</span>
  <span m='3797680'>not</span> <span m='3797910'>work--</span> <span m='3798620'>but</span>
  <span m='3798760'>it</span> <span m='3798840'>might</span> <span m='3799100'>be</span>
  <span m='3799230'>applicable</span> <span m='3800060'>to</span> <span m='3800190'>investigating</span>
  <span m='3800780'>solutions of</span> <span m='3801160'>equations</span> <span m='3801670'>like</span>
  <span m='3801930'>this.</span> </p><p><span m='3807240'>But</span> <span m='3807450'>what</span>
  <span m='3807540'>I</span> <span m='3807610'>want</span> <span m='3807870'>you</span>
  <span m='3807940'>to</span> <span m='3808030'>feel</span> <span m='3808330'>is</span>
  <span m='3808520'>that this</span> <span m='3808700'>is</span> <span m='3808770'>an</span>
  <span m='3808880'>equation.</span> <span m='3810260'>It's</span> <span m='3810470'>an</span>
  <span m='3810560'>expression</span> <span m='3811400'>with</span> <span m='3811600'>several</span>
  <span m='3811930'>instances</span> <span m='3812430'>of</span> <span m='3812530'>various</span>
  <span m='3812930'>names</span> <span m='3814730'>which</span> <span m='3815250'>puts</span>
  <span m='3815470'>a</span> <span m='3815510'>constraint</span> <span m='3816920'>on</span>
  <span m='3817130'>the</span> <span m='3817220'>name,</span> <span m='3818390'>saying</span>
  <span m='3818690'>what</span> <span m='3818840'>that</span> <span m='3819020'>name</span>
  <span m='3819260'>could</span> <span m='3819620'>have</span> <span m='3819760'>as</span>
  <span m='3819860'>its</span> <span m='3820010'>value,</span> <span m='3821550'>rather</span>
  <span m='3821860'>than</span> <span m='3822060'>some</span> <span m='3822290'>sort</span>
  <span m='3822470'>of</span> <span m='3822770'>mechanical</span> <span m='3823430'>process</span>
  <span m='3823820'>of</span> <span m='3823910'>substitution</span> <span m='3824470'>right</span>
  <span m='3824740'>now.</span> <span m='3827740'>This</span> <span m='3827920'>is</span>
  <span m='3827960'>an</span> <span m='3828100'>equation</span> <span m='3828630'>which</span>
  <span m='3828800'>I'm</span> <span m='3828910'>going</span> <span m='3829030'>to</span>
  <span m='3829160'>try</span> <span m='3829310'>to</span> <span m='3829370'>solve.</span>
  </p><p><span m='3831220'>Well, let's</span> <span m='3831510'>play</span> <span
  m='3831800'>around</span> <span m='3831910'>and</span> <span m='3832010'>solve</span>
  <span m='3832375'>it.</span> <span m='3833960'>First</span> <span m='3834250'>of</span>
  <span m='3834340'>all,</span> <span m='3834480'>I</span> <span m='3834560'>want</span>
  <span m='3834820'>to</span> <span m='3834890'>write</span> <span m='3835160'>down</span>
  <span m='3836240'>the</span> <span m='3836840'>function</span> <span m='3837540'>which</span>
  <span m='3837800'>corresponds</span> <span m='3838490'>to</span> <span m='3838650'>t.</span>
  <span m='3840320'>First</span> <span m='3840690'>I</span> <span m='3840750'>want</span>
  <span m='3840890'>to</span> <span m='3841020'>write</span> <span m='3841200'>down</span>
  <span m='3841360'>the</span> <span m='3841430'>function</span> <span m='3841810'>which</span>
  <span m='3841950'>corresponds</span> <span m='3842520'>to</span> <span m='3842670'>t</span>
  <span m='3844560'>whose</span> <span m='3844720'>fixed</span> <span m='3845100'>point</span>
  <span m='3845370'>is</span> <span m='3845480'>the</span> <span m='3845640'>answer</span>
  <span m='3846140'>to</span> <span m='3846290'>this</span> <span m='3846480'>question.</span>
  <span m='3851950'>Well,</span> <span m='3852370'>let's</span> <span m='3852610'>consider</span>
  <span m='3852910'>the</span> <span m='3853030'>following</span> <span m='3853460'>procedure</span>
  <span m='3853960'>f.</span> <span m='3856870'>I</span> <span m='3856980'>claim</span>
  <span m='3857220'>it</span> <span m='3857270'>computes</span> <span m='3857660'>that</span>
  <span m='3857890'>function.</span> <span m='3859340'>f</span> <span m='3859580'>is</span>
  <span m='3860000'>that</span> <span m='3860450'>procedure</span> <span m='3860990'>of</span>
  <span m='3861180'>one</span> <span m='3861370'>argument</span> <span m='3862390'>g,</span>
  <span m='3865320'>which</span> <span m='3865570'>is</span> <span m='3866200'>that</span>
  <span m='3866860'>procedure</span> <span m='3867380'>of</span> <span m='3867790'>two</span>
  <span m='3867990'>arguments</span> <span m='3869450'>x</span> <span m='3871000'>and</span>
  <span m='3871320'>n.</span> <span m='3873430'>Which</span> <span m='3873650'>have</span>
  <span m='3873790'>the</span> <span m='3873870'>property</span> <span m='3874420'>that</span>
  <span m='3876970'>if</span> <span m='3878775'>n</span> <span m='3879630'>is</span>
  <span m='3879990'>zero,</span> <span m='3881740'>then the</span> <span m='3881990'>result</span>
  <span m='3882410'>is</span> <span m='3882590'>one,</span> <span m='3885370'>otherwise,</span>
  <span m='3889750'>the</span> <span m='3890030'>result</span> <span m='3890560'>is</span>
  <span m='3890760'>the</span> <span m='3890870'>product</span> <span m='3892030'>of</span>
  <span m='3892600'>x</span> <span m='3893540'>and</span> <span m='3894880'>g,</span>
  <span m='3896050'>applied</span> <span m='3896630'>to</span> <span m='3897520'>x,</span>
  <span m='3898740'>and</span> <span m='3899520'>minus</span> <span m='3900380'>n1.</span>
  <span m='3903370'>g,</span> <span m='3904310'>times,</span> <span m='3905320'>else,</span>
  <span m='3905950'>COND,</span> <span m='3906570'>lambda,</span> <span m='3907450'>lambda--</span>
  </p><p><span m='3911900'>Here</span> <span m='3912600'>f</span> <span m='3912870'>is</span>
  <span m='3913890'>a</span> <span m='3914020'>procedure,</span> <span m='3915050'>which</span>
  <span m='3915330'>if I</span> <span m='3915440'>had</span> <span m='3916370'>a</span>
  <span m='3916500'>solution</span> <span m='3916960'>to</span> <span m='3917050'>that</span>
  <span m='3917230'>equation,</span> <span m='3919050'>if</span> <span m='3919270'>I</span>
  <span m='3919370'>had</span> <span m='3919700'>a</span> <span m='3920160'>good</span>
  <span m='3920450'>exponentiation</span> <span m='3921460'>procedure,</span> <span
  m='3923420'>and</span> <span m='3923640'>I</span> <span m='3924190'>applied</span>
  <span m='3924910'>f</span> <span m='3925230'>to</span> <span m='3925530'>that</span>
  <span m='3925790'>procedure,</span> <span m='3927620'>then</span> <span m='3927880'>the</span>
  <span m='3927990'>result</span> <span m='3928960'>would</span> <span m='3929150'>be</span>
  <span m='3929410'>a</span> <span m='3929500'>good</span> <span m='3929800'>exponentiation</span>
  <span m='3930670'>procedure.</span> <span m='3937460'>Because,</span> <span m='3937870'>what</span>
  <span m='3938010'>does</span> <span m='3938130'>it</span> <span m='3938240'>do?</span>
  <span m='3939420'>Well,</span> <span m='3939960'>all</span> <span m='3940250'>it</span>
  <span m='3940410'>is</span> <span m='3940570'>is</span> <span m='3942400'>exposing</span>
  <span m='3942960'>g</span> <span m='3943140'>were</span> <span m='3943310'>a</span>
  <span m='3943490'>good</span> <span m='3943660'>exponentiation</span> <span m='3944200'>procedure,</span>
  <span m='3945650'>well</span> <span m='3945890'>then</span> <span m='3946030'>this</span>
  <span m='3946200'>would</span> <span m='3946390'>produce,</span> <span m='3946860'>as</span>
  <span m='3947010'>its</span> <span m='3947160'>value,</span> <span m='3947860'>a</span>
  <span m='3948010'>procedure</span> <span m='3948420'>to</span> <span m='3948560'>arguments</span>
  <span m='3948960'>x</span> <span m='3949310'>and</span> <span m='3949600'>n,</span>
  <span m='3950540'>such</span> <span m='3950800'>that</span> <span m='3950880'>if</span>
  <span m='3951150'>n were</span> <span m='3951270'>0,</span> <span m='3951550'>the</span>
  <span m='3951650'>result</span> <span m='3951930'>would</span> <span m='3952040'>be</span>
  <span m='3952160'>one,</span> <span m='3952490'>which is</span> <span m='3952650'>certainly</span>
  <span m='3952940'>true</span> <span m='3953130'>of</span> <span m='3953360'>exponentiation.</span>
  <span m='3954670'>Otherwise,</span> <span m='3955430'>it will</span> <span m='3955580'>be</span>
  <span m='3955660'>the</span> <span m='3955780'>result</span> <span m='3956110'>of</span>
  <span m='3956200'>multiplying</span> <span m='3956710'>x</span> <span m='3957270'>by</span>
  <span m='3957450'>the</span> <span m='3957730'>exponentiation</span> <span m='3958270'>procedure</span>
  <span m='3958610'>given</span> <span m='3958860'>to</span> <span m='3958960'>me</span>
  <span m='3960220'>with</span> <span m='3960430'>x</span> <span m='3961020'>and</span>
  <span m='3961150'>n</span> <span m='3961280'>minus</span> <span m='3961580'>one</span>
  <span m='3961750'>as</span> <span m='3961860'>arguments.</span> <span m='3963470'>So</span>
  <span m='3963710'>if this</span> <span m='3963930'>computed</span> <span m='3964260'>the</span>
  <span m='3964380'>correct</span> <span m='3964620'>exponentiation</span> <span m='3965145'>for</span>
  <span m='3965460'>n</span> <span m='3965680'>minus</span> <span m='3965930'>one,</span>
  <span m='3967930'>then</span> <span m='3968140'>this</span> <span m='3968300'>would</span>
  <span m='3968390'>be</span> <span m='3968490'>the</span> <span m='3968570'>correct</span>
  <span m='3968940'>exponentiation</span> <span m='3969780'>for</span> <span m='3970500'>exponent</span>
  <span m='3970920'>n,</span> <span m='3972160'>so</span> <span m='3972340'>this</span>
  <span m='3972530'>would</span> <span m='3972680'>have</span> <span m='3972800'>been</span>
  <span m='3972910'>the</span> <span m='3973010'>right</span> <span m='3973370'>exponentiation</span>
  <span m='3973890'>procedure.</span> </p><p><span m='3977500'>So what</span> <span
  m='3977770'>I</span> <span m='3977890'>really</span> <span m='3978140'>want</span>
  <span m='3978240'>to</span> <span m='3978350'>say</span> <span m='3978630'>here</span>
  <span m='3979370'>is</span> <span m='3981940'>E-X-P-T</span> <span m='3984450'>is</span>
  <span m='3986010'>a</span> <span m='3986210'>fixed</span> <span m='3986560'>point</span>
  <span m='3991680'>of</span> <span m='3992000'>f.</span> <span m='3997550'>Now</span>
  <span m='3997740'>our</span> <span m='3997810'>problem</span> <span m='3998170'>is</span>
  <span m='3998260'>there</span> <span m='3998370'>might</span> <span m='3998540'>be</span>
  <span m='3998660'>more</span> <span m='3998840'>than</span> <span m='3998960'>one</span>
  <span m='3999170'>fixed</span> <span m='3999420'>point.</span> <span m='4000060'>There</span>
  <span m='4000170'>might</span> <span m='4000410'>be</span> <span m='4001260'>no</span>
  <span m='4001460'>fixed</span> <span m='4001800'>points.</span> <span m='4003270'>I
  have</span> <span m='4003510'>to go</span> <span m='4003610'>hunting</span> <span
  m='4003950'>for</span> <span m='4004040'>the</span> <span m='4004120'>fixed</span>
  <span m='4004380'>points.</span> <span m='4008290'>Got</span> <span m='4008370'>to</span>
  <span m='4008450'>solve</span> <span m='4008750'>this</span> <span m='4008870'>equation.</span>
  </p><p><span m='4012160'>Well</span> <span m='4012370'>there</span> <span m='4012480'>are</span>
  <span m='4012550'>various</span> <span m='4012960'>ways to</span> <span m='4013270'>hunt</span>
  <span m='4013500'>for</span> <span m='4013590'>fixed</span> <span m='4013880'>points.</span>
  <span m='4015580'>Of</span> <span m='4015710'>course,</span> <span m='4015840'>the</span>
  <span m='4015930'>one</span> <span m='4016110'>we</span> <span m='4016240'>played</span>
  <span m='4016540'>with</span> <span m='4016740'>at</span> <span m='4016850'>the</span>
  <span m='4017310'>beginning</span> <span m='4017810'>of</span> <span m='4017890'>this</span>
  <span m='4018080'>term</span> <span m='4020020'>worked</span> <span m='4020330'>for</span>
  <span m='4020550'>cosine.</span> <span m='4026080'>Go into</span> <span m='4026380'>radians</span>
  <span m='4026720'>mode</span> <span m='4026940'>on</span> <span m='4027040'>your</span>
  <span m='4027150'>calculator</span> <span m='4027850'>and</span> <span m='4028040'>push</span>
  <span m='4028250'>cosine,</span> <span m='4029235'>and</span> <span m='4029720'>just</span>
  <span m='4029870'>keep</span> <span m='4030030'>doing</span> <span m='4030370'>it,</span>
  <span m='4031670'>and</span> <span m='4031840'>you</span> <span m='4032010'>get</span>
  <span m='4032240'>to</span> <span m='4032310'>some</span> <span m='4032510'>number</span>
  <span m='4032810'>which</span> <span m='4032990'>is</span> <span m='4033040'>about</span>
  <span m='4033320'>0.73</span> <span m='4034650'>or</span> <span m='4034940'>0.74.</span>
  <span m='4036090'>I</span> <span m='4036200'>can't</span> <span m='4036460'>remember</span>
  <span m='4036800'>which.</span> <span m='4042900'>By</span> <span m='4043250'>iterating</span>
  <span m='4043650'>a</span> <span m='4043760'>function,</span> <span m='4045640'>whose</span>
  <span m='4045800'>fixed</span> <span m='4046090'>point</span> <span m='4046330'>I'm</span>
  <span m='4046460'>searching</span> <span m='4046820'>for,</span> <span m='4047170'>it</span>
  <span m='4047570'>is</span> <span m='4047800'>sometimes</span> <span m='4048280'>the</span>
  <span m='4048370'>case</span> <span m='4049640'>that</span> <span m='4049810'>that</span>
  <span m='4050050'>function</span> <span m='4050420'>will</span> <span m='4050570'>converge</span>
  <span m='4051950'>in</span> <span m='4052090'>producing</span> <span m='4052430'>the</span>
  <span m='4052520'>fixed</span> <span m='4052760'>point.</span> </p><p><span m='4053770'>I</span>
  <span m='4053880'>think</span> <span m='4054120'>we</span> <span m='4054240'>luck</span>
  <span m='4054500'>out</span> <span m='4054780'>in</span> <span m='4054900'>this</span>
  <span m='4055080'>case,</span> <span m='4056460'>so</span> <span m='4056590'>let's</span>
  <span m='4056720'>look</span> <span m='4056900'>for</span> <span m='4057280'>it.</span>
  <span m='4059910'>Let's</span> <span m='4060080'>look</span> <span m='4060210'>at</span>
  <span m='4064460'>this</span> <span m='4065740'>slide.</span> <span m='4068030'>Consider</span>
  <span m='4068590'>the</span> <span m='4068710'>following</span> <span m='4069260'>sequence</span>
  <span m='4070450'>of</span> <span m='4070950'>procedures.</span> <span m='4076400'>e0</span>
  <span m='4077040'>over</span> <span m='4077240'>here</span> <span m='4079290'>is</span>
  <span m='4079450'>the</span> <span m='4079560'>procedure</span> <span m='4080250'>which</span>
  <span m='4080550'>does</span> <span m='4080810'>nothing</span> <span m='4081260'>at</span>
  <span m='4081320'>all.</span> <span m='4082940'>It's</span> <span m='4083120'>the</span>
  <span m='4083230'>procedure</span> <span m='4083910'>which</span> <span m='4084190'>produces</span>
  <span m='4084630'>an</span> <span m='4084740'>error</span> <span m='4085050'>for</span>
  <span m='4085240'>any</span> <span m='4085390'>arguments</span> <span m='4085870'>you</span>
  <span m='4085930'>give</span> <span m='4086120'>it.</span> <span m='4087780'>It's</span>
  <span m='4087930'>basically</span> <span m='4088410'>useless.</span> <span m='4094480'>Well,</span>
  <span m='4096770'>however,</span> <span m='4098359'>I</span> <span m='4098490'>can</span>
  <span m='4098689'>make</span> <span m='4098910'>an</span> <span m='4099130'>approximation.</span>
  <span m='4100080'>Let's</span> <span m='4100240'>consider</span> <span m='4100560'>it</span>
  <span m='4100649'>the</span> <span m='4100729'>worst</span> <span m='4101029'>possible</span>
  <span m='4101399'>approximation</span> <span m='4102590'>to</span> <span m='4102930'>exponentiation,</span>
  <span m='4104349'>because</span> <span m='4104779'>it</span> <span m='4104960'>does</span>
  <span m='4105160'>nothing.</span> </p><p><span m='4106990'>Well,</span> <span m='4107250'>supposing</span>
  <span m='4107840'>I</span> <span m='4108050'>substituted</span> <span m='4108920'>e0</span>
  <span m='4110090'>for</span> <span m='4111189'>g</span> <span m='4112350'>by</span>
  <span m='4112540'>calling</span> <span m='4112960'>f,</span> <span m='4113699'>as</span>
  <span m='4114029'>you</span> <span m='4114170'>see</span> <span m='4114370'>over</span>
  <span m='4114600'>here</span> <span m='4115490'>on</span> <span m='4115850'>e0.</span>
  <span m='4117380'>So</span> <span m='4117700'>you</span> <span m='4117920'>see</span>
  <span m='4118029'>over here,</span> <span m='4118700'>have</span> <span m='4118950'>e0</span>
  <span m='4119430'>there.</span> <span m='4120729'>Then</span> <span m='4121240'>gee,</span>
  <span m='4121500'>what's</span> <span m='4121770'>e1?</span> <span m='4123859'>e1</span>
  <span m='4124090'>is</span> <span m='4124189'>a</span> <span m='4124279'>procedure</span>
  <span m='4124670'>which</span> <span m='4124939'>exponentiate</span> <span m='4125680'>things</span>
  <span m='4126520'>to</span> <span m='4126800'>the</span> <span m='4126899'>0th</span>
  <span m='4127189'>power,</span> <span m='4128149'>with</span> <span m='4128300'>no</span>
  <span m='4128470'>trouble.</span> <span m='4129325'>It</span> <span m='4129819'>gets</span>
  <span m='4130020'>the</span> <span m='4130120'>right</span> <span m='4130319'>answer,</span>
  <span m='4131109'>anything</span> <span m='4131470'>to the</span> <span m='4131660'>zero</span>
  <span m='4131930'>is</span> <span m='4132029'>one,</span> <span m='4132420'>and</span>
  <span m='4132689'>it</span> <span m='4132870'>makes</span> <span m='4133080'>an</span>
  <span m='4133149'>error</span> <span m='4133410'>on</span> <span m='4133540'>anything</span>
  <span m='4133870'>else.</span> </p><p><span m='4137390'>Well,</span> <span m='4137590'>now</span>
  <span m='4138120'>what</span> <span m='4138470'>if</span> <span m='4138590'>I</span>
  <span m='4138700'>take</span> <span m='4140790'>e1</span> <span m='4141954'>and</span>
  <span m='4142380'>I</span> <span m='4142580'>substitute</span> <span m='4143074'>if</span>
  <span m='4143569'>for</span> <span m='4143830'>g</span> <span m='4145939'>by</span>
  <span m='4146040'>calling</span> <span m='4146430'>f</span> <span m='4146590'>on</span>
  <span m='4146950'>e1?</span> <span m='4150500'>Oh</span> <span m='4150689'>gosh,</span>
  <span m='4152160'>I</span> <span m='4152290'>have</span> <span m='4152580'>here</span>
  <span m='4153479'>a</span> <span m='4153609'>procedure</span> <span m='4154069'>of</span>
  <span m='4154149'>two</span> <span m='4154359'>arguments.</span> <span m='4155670'>Now</span>
  <span m='4155800'>remember</span> <span m='4156200'>e1</span> <span m='4156930'>was</span>
  <span m='4157200'>appropriate</span> <span m='4157800'>for</span> <span m='4157899'>taking</span>
  <span m='4158250'>exponentiations</span> <span m='4159100'>of</span> <span m='4159189'>0,</span>
  <span m='4161241'>for</span> <span m='4161960'>raising</span> <span m='4162260'>to
  the</span> <span m='4162569'>0</span> <span m='4162819'>exponent.</span> <span m='4164200'>So</span>
  <span m='4164490'>here,</span> <span m='4165600'>is</span> <span m='4165750'>n</span>
  <span m='4165939'>is</span> <span m='4166020'>0,</span> <span m='4166340'>the</span>
  <span m='4166460'>result</span> <span m='4166830'>is</span> <span m='4166939'>one,</span>
  <span m='4167240'>so</span> <span m='4167330'>this</span> <span m='4167500'>guy</span>
  <span m='4167660'>is</span> <span m='4167750'>good</span> <span m='4167910'>for</span>
  <span m='4168000'>that</span> <span m='4168240'>too.</span> <span m='4169520'>However,</span>
  <span m='4169990'>I</span> <span m='4170069'>can</span> <span m='4170260'>use</span>
  <span m='4170490'>something</span> <span m='4170810'>for</span> <span m='4170920'>raising</span>
  <span m='4171229'>to</span> <span m='4171439'>the</span> <span m='4171609'>0th power</span>
  <span m='4172479'>to</span> <span m='4172660'>multiply</span> <span m='4173210'>it</span>
  <span m='4173380'>by</span> <span m='4173569'>x</span> <span m='4173840'>to</span>
  <span m='4173939'>raise</span> <span m='4174109'>something</span> <span m='4174390'>to</span>
  <span m='4174470'>the</span> <span m='4174560'>first</span> <span m='4174890'>power.</span>
  <span m='4175979'>So</span> <span m='4176840'>e2</span> <span m='4177270'>is</span>
  <span m='4177420'>good</span> <span m='4177680'>for</span> <span m='4178060'>both</span>
  <span m='4178399'>power</span> <span m='4178720'>0</span> <span m='4179130'>and</span>
  <span m='4179290'>one.</span> </p><p><span m='4183800'>And</span> <span m='4184090'>e3</span>
  <span m='4184529'>is</span> <span m='4184670'>constructed</span> <span m='4185250'>from</span>
  <span m='4185390'>e2</span> <span m='4185810'>in</span> <span m='4185880'>the</span>
  <span m='4185950'>same</span> <span m='4186250'>way.</span> <span m='4187899'>And</span>
  <span m='4188060'>e3,</span> <span m='4188649'>of</span> <span m='4188890'>course,</span>
  <span m='4189130'>by</span> <span m='4189279'>the</span> <span m='4189370'>same</span>
  <span m='4189670'>argument</span> <span m='4190340'>is</span> <span m='4190569'>good</span>
  <span m='4190800'>for</span> <span m='4190899'>powers</span> <span m='4191590'>0,</span>
  <span m='4192240'>one,</span> <span m='4192700'>and</span> <span m='4193109'>two.</span>
  <span m='4195120'>And</span> <span m='4196030'>so</span> <span m='4196320'>I</span>
  <span m='4196440'>will</span> <span m='4196650'>assert</span> <span m='4197030'>for</span>
  <span m='4197170'>you,</span> <span m='4198190'>without</span> <span m='4198660'>proof,</span>
  <span m='4199690'>because</span> <span m='4200060'>the</span> <span m='4200140'>proof</span>
  <span m='4200450'>is</span> <span m='4200590'>horribly</span> <span m='4201100'>difficult.</span>
  <span m='4202520'>And</span> <span m='4202790'>that's</span> <span m='4202950'>the</span>
  <span m='4203030'>sort</span> <span m='4203210'>of</span> <span m='4203280'>thing</span>
  <span m='4203450'>that</span> <span m='4203580'>people</span> <span m='4203800'>called</span>
  <span m='4204050'>denotational</span> <span m='4204150'>semanticists</span> <span
  m='4206030'>do.</span> <span m='4207710'>This</span> <span m='4208160'>great</span>
  <span m='4208410'>idea</span> <span m='4208690'>was</span> <span m='4208820'>invented</span>
  <span m='4209170'>by</span> <span m='4209370'>Scott</span> <span m='4209850'>and</span>
  <span m='4209980'>Strachey.</span> <span m='4214240'>They're</span> <span m='4214560'>very</span>
  <span m='4214780'>famous</span> <span m='4215310'>mathematician</span> <span m='4215940'>types</span>
  <span m='4216560'>who</span> <span m='4217110'>invented</span> <span m='4217720'>the</span>
  <span m='4217910'>interpretation</span> <span m='4219140'>for</span> <span m='4219760'>these</span>
  <span m='4220190'>programs</span> <span m='4220690'>that</span> <span m='4220790'>we</span>
  <span m='4221030'>have</span> <span m='4222050'>that</span> <span m='4222440'>I'm</span>
  <span m='4222690'>talking</span> <span m='4223010'>to</span> <span m='4223070'>you</span>
  <span m='4223130'>about</span> <span m='4223350'>right</span> <span m='4223600'>now.</span>
  <span m='4224240'>And</span> <span m='4224420'>they</span> <span m='4224560'>proved,</span>
  <span m='4225210'>by</span> <span m='4225520'>topology</span> <span m='4226840'>that</span>
  <span m='4227360'>there</span> <span m='4227580'>is</span> <span m='4228300'>such</span>
  <span m='4228570'>a</span> <span m='4228630'>fixed</span> <span m='4228950'>point</span>
  <span m='4230140'>in</span> <span m='4230300'>the</span> <span m='4230390'>cases</span>
  <span m='4230720'>that</span> <span m='4230820'>we</span> <span m='4230940'>want.</span>
  </p><p><span m='4232220'>But</span> <span m='4232400'>the</span> <span m='4232510'>assertion</span>
  <span m='4232970'>is</span> <span m='4233990'>E-X-P-T</span> <span m='4236750'>is</span>
  <span m='4236980'>limit</span> <span m='4239580'>as</span> <span m='4239740'>n</span>
  <span m='4240860'>goes</span> <span m='4241180'>to</span> <span m='4241390'>infinity</span>
  <span m='4242730'>of</span> <span m='4243030'>em.</span> <span m='4243680'>and</span>
  <span m='4245550'>And</span> <span m='4245730'>that</span> <span m='4245870'>we've</span>
  <span m='4246010'>constructed</span> <span m='4246590'>this</span> <span m='4246810'>by</span>
  <span m='4246950'>the</span> <span m='4247040'>following</span> <span m='4247520'>way.</span>
  <span m='4250520'>--is</span> <span m='4251330'>Well,</span> <span m='4251770'>it's</span>
  <span m='4251960'>f</span> <span m='4252190'>of,</span> <span m='4252660'>f</span>
  <span m='4252890'>of,</span> <span m='4253225'>f</span> <span m='4253560'>of,</span>
  <span m='4253890'>f</span> <span m='4254180'>of,</span> <span m='4254470'>f</span>
  <span m='4254750'>of--</span> <span m='4257530'>f</span> <span m='4258090'>applied</span>
  <span m='4258560'>to</span> <span m='4259350'>anything</span> <span m='4259730'>at</span>
  <span m='4259980'>all.</span> <span m='4261120'>It</span> <span m='4261240'>didn't</span>
  <span m='4261450'>matter</span> <span m='4261700'>what</span> <span m='4261870'>that</span>
  <span m='4262090'>was,</span> <span m='4263270'>because,</span> <span m='4263500'>in</span>
  <span m='4263770'>fact,</span> <span m='4263930'>this always</span> <span m='4264210'>produces</span>
  <span m='4264460'>an</span> <span m='4264590'>error.</span> <span m='4267540'>Applied</span>
  <span m='4267950'>to</span> <span m='4268080'>this--</span> <span m='4272840'>That's</span>
  <span m='4273170'>by</span> <span m='4273300'>infinite</span> <span m='4273660'>nesting</span>
  <span m='4274020'>of</span> <span m='4274275'>f's.</span> </p><p><span m='4276380'>So</span>
  <span m='4276660'>now</span> <span m='4276890'>my</span> <span m='4277040'>problem</span>
  <span m='4278310'>is</span> <span m='4278470'>to</span> <span m='4278570'>make</span>
  <span m='4278810'>some</span> <span m='4278910'>infinite</span> <span m='4279320'>things.</span>
  <span m='4282590'>We</span> <span m='4282750'>need</span> <span m='4282940'>some</span>
  <span m='4283090'>infinite</span> <span m='4283730'>things.</span> <span m='4284920'>How</span>
  <span m='4285170'>am</span> <span m='4285560'>I going to</span> <span m='4285830'>nest</span>
  <span m='4285980'>up</span> <span m='4286080'>an</span> <span m='4286630'>f</span>
  <span m='4286910'>an</span> <span m='4287030'>infinite number</span> <span m='4287290'>of</span>
  <span m='4287370'>times?</span> <span m='4288980'>I'd</span> <span m='4289150'>better</span>
  <span m='4289340'>construct</span> <span m='4289830'>this.</span> <span m='4292380'>Well,</span>
  <span m='4292590'>I</span> <span m='4292660'>don't</span> <span m='4292800'>know.</span>
  <span m='4292930'>How</span> <span m='4293140'>would I</span> <span m='4293230'>make</span>
  <span m='4293410'>an</span> <span m='4293510'>infinite</span> <span m='4293810'>loop</span>
  <span m='4294000'>at</span> <span m='4294240'>all?</span> </p><p><span m='4294810'>Let's</span>
  <span m='4294990'>take</span> <span m='4295150'>a</span> <span m='4295200'>very</span>
  <span m='4295450'>simple</span> <span m='4295790'>infinite</span> <span m='4296130'>loop,</span>
  <span m='4296570'>the</span> <span m='4296690'>simplest</span> <span m='4297090'>infinite</span>
  <span m='4297410'>loop</span> <span m='4297560'>imaginable.</span> <span m='4303550'>If</span>
  <span m='4303790'>I</span> <span m='4303860'>were</span> <span m='4303970'>to</span>
  <span m='4304050'>take</span> <span m='4304980'>that</span> <span m='4305350'>procedure</span>
  <span m='4306290'>of</span> <span m='4306470'>one</span> <span m='4306650'>argument</span>
  <span m='4307110'>x</span> <span m='4308070'>which</span> <span m='4308300'>applies</span>
  <span m='4308900'>x</span> <span m='4309340'>to</span> <span m='4309640'>x</span>
  <span m='4315180'>and</span> <span m='4315370'>apply</span> <span m='4315750'>that</span>
  <span m='4315990'>to</span> <span m='4316060'>the</span> <span m='4316160'>procedure</span>
  <span m='4317220'>of</span> <span m='4317400'>one</span> <span m='4317580'>argument</span>
  <span m='4317980'>x</span> <span m='4319410'>which</span> <span m='4319660'>applies</span>
  <span m='4320030'>x</span> <span m='4320130'>to</span> <span m='4320480'>x,</span>
  <span m='4324770'>then</span> <span m='4325130'>this</span> <span m='4325320'>is</span>
  <span m='4325580'>an</span> <span m='4325740'>infinite</span> <span m='4326010'>loop.</span>
  </p><p><span m='4327440'>The</span> <span m='4327540'>reason</span> <span m='4327790'>why</span>
  <span m='4327970'>this</span> <span m='4328180'>is</span> <span m='4328380'>an infinite</span>
  <span m='4328440'>loop</span> <span m='4328620'>is</span> <span m='4328740'>as</span>
  <span m='4328850'>follows.</span> <span m='4329980'>The</span> <span m='4330190'>way</span>
  <span m='4330350'>I</span> <span m='4330500'>understand</span> <span m='4330990'>this</span>
  <span m='4331570'>is</span> <span m='4331770'>I</span> <span m='4331910'>substitute</span>
  <span m='4332700'>the</span> <span m='4333010'>argument</span> <span m='4334150'>for</span>
  <span m='4334390'>the</span> <span m='4334480'>formal</span> <span m='4334840'>parameter</span>
  <span m='4335840'>in</span> <span m='4335970'>the</span> <span m='4336090'>body.</span>
  <span m='4338850'>But</span> <span m='4339140'>if</span> <span m='4339240'>I</span>
  <span m='4339350'>do</span> <span m='4339550'>that,</span> <span m='4339800'>I</span>
  <span m='4339950'>take</span> <span m='4340330'>for</span> <span m='4340550'>each</span>
  <span m='4340730'>of</span> <span m='4340810'>these</span> <span m='4341020'>x's,</span>
  <span m='4342400'>I</span> <span m='4342590'>substitute</span> <span m='4343080'>one</span>
  <span m='4343240'>of</span> <span m='4343480'>these,</span> <span m='4344470'>making</span>
  <span m='4344780'>a</span> <span m='4344840'>copy</span> <span m='4345240'>of</span>
  <span m='4345310'>the</span> <span m='4345410'>original</span> <span m='4345740'>expression</span>
  <span m='4346170'>I</span> <span m='4346240'>just</span> <span m='4346420'>started</span>
  <span m='4346700'>with,</span> <span m='4348320'>the</span> <span m='4348410'>simplest</span>
  <span m='4348820'>infinite</span> <span m='4349130'>loop.</span> </p><p><span m='4355440'>Now</span>
  <span m='4355590'>I</span> <span m='4355700'>want</span> <span m='4355840'>to</span>
  <span m='4355970'>tell</span> <span m='4356160'>you</span> <span m='4356370'>about</span>
  <span m='4357250'>a</span> <span m='4357400'>particular</span> <span m='4358570'>operator</span>
  <span m='4360420'>which</span> <span m='4360630'>is</span> <span m='4360750'>constructed</span>
  <span m='4361360'>by</span> <span m='4361530'>a</span> <span m='4361780'>perturbation</span>
  <span m='4362230'>from</span> <span m='4362410'>this</span> <span m='4362640'>infinite</span>
  <span m='4362860'>loop.</span> <span m='4367040'>I'll</span> <span m='4367110'>call
  it</span> <span m='4367400'>y.</span> <span m='4372290'>This</span> <span m='4372600'>is</span>
  <span m='4372810'>called</span> <span m='4373440'>Curry's</span> <span m='4373930'>Paradoxical</span>
  <span m='4374750'>Combinator</span> <span m='4375290'>of</span> <span m='4375450'>y</span>
  <span m='4376680'>after</span> <span m='4377430'>a</span> <span m='4378110'>fellow
  by the</span> <span m='4378450'>name of</span> <span m='4378805'>Curry,</span> <span
  m='4379160'>who</span> <span m='4379570'>was</span> <span m='4379710'>a</span> <span
  m='4379980'>logician</span> <span m='4380440'>of</span> <span m='4380510'>the</span>
  <span m='4380590'>1930s</span> <span m='4381420'>also.</span> <span m='4384480'>And</span>
  <span m='4384640'>if</span> <span m='4384750'>I</span> <span m='4384880'>have</span>
  <span m='4385090'>a</span> <span m='4385170'>procedure</span> <span m='4385760'>of</span>
  <span m='4385930'>one</span> <span m='4386100'>argument</span> <span m='4386660'>f,</span>
  <span m='4388290'>what's</span> <span m='4388570'>it</span> <span m='4388670'>going</span>
  <span m='4388860'>to</span> <span m='4388930'>have</span> <span m='4389240'>in it?</span>
  <span m='4389330'>It's</span> <span m='4389460'>going</span> <span m='4389620'>to</span>
  <span m='4389680'>have</span> <span m='4389980'>a</span> <span m='4390110'>kind</span>
  <span m='4390370'>of</span> <span m='4390460'>infinite</span> <span m='4390770'>loop</span>
  <span m='4390970'>in</span> <span m='4391070'>it,</span> <span m='4391950'>which</span>
  <span m='4392280'>is</span> <span m='4393420'>that</span> <span m='4394040'>procedure</span>
  <span m='4394560'>of</span> <span m='4394710'>one</span> <span m='4394860'>argument</span>
  <span m='4395200'>x</span> <span m='4395960'>which</span> <span m='4396240'>applies</span>
  <span m='4396800'>f</span> <span m='4397080'>to</span> <span m='4397980'>x of</span>
  <span m='4398380'>x,</span> <span m='4401670'>applied</span> <span m='4402250'>to</span>
  <span m='4402760'>that</span> <span m='4403290'>procedure</span> <span m='4403730'>of</span>
  <span m='4403860'>one</span> <span m='4403990'>argument</span> <span m='4404340'>x,</span>
  <span m='4405220'>which</span> <span m='4405400'>applies</span> <span m='4405820'>f</span>
  <span m='4406180'>to</span> <span m='4406530'>f</span> <span m='4406970'>of</span>
  <span m='4407410'>x.</span> </p><p><span m='4412300'>Now</span> <span m='4412450'>what's</span>
  <span m='4412680'>this</span> <span m='4412900'>do?</span> <span m='4414590'>Suppose</span>
  <span m='4415050'>we</span> <span m='4415170'>apply</span> <span m='4415480'>y to</span>
  <span m='4415820'>F.</span> <span m='4421830'>Well,</span> <span m='4421940'>that's</span>
  <span m='4422060'>easy</span> <span m='4422250'>enough.</span> <span m='4422950'>That's</span>
  <span m='4423270'>this</span> <span m='4423600'>capital</span> <span m='4423970'>F</span>
  <span m='4424160'>over</span> <span m='4424350'>here.</span> <span m='4426910'>Well,</span>
  <span m='4427050'>the</span> <span m='4427440'>easiest</span> <span m='4427610'>thing</span>
  <span m='4427670'>to say</span> <span m='4427920'>there</span> <span m='4428340'>is,</span>
  <span m='4428470'>I</span> <span m='4428670'>substitute</span> <span m='4428810'>F</span>
  <span m='4429250'>for</span> <span m='4429390'>here.</span> <span m='4435320'>So</span>
  <span m='4435520'>that's</span> <span m='4435770'>going</span> <span m='4435970'>to</span>
  <span m='4436160'>give me,</span> <span m='4436360'>basically--</span> <span m='4438460'>because</span>
  <span m='4438960'>then</span> <span m='4439100'>I'm</span> <span m='4439240'>going</span>
  <span m='4439380'>to</span> <span m='4439900'>substitute</span> <span m='4440430'>this</span>
  <span m='4441480'>for</span> <span m='4441780'>x</span> <span m='4442220'>in</span>
  <span m='4442410'>here.</span> </p><p><span m='4448970'>Let</span> <span m='4449080'>me</span>
  <span m='4449180'>actually</span> <span m='4449350'>do</span> <span m='4449540'>it
  in</span> <span m='4449600'>steps,</span> <span m='4450230'>so</span> <span m='4450370'>you</span>
  <span m='4450480'>can</span> <span m='4450570'>see</span> <span m='4450710'>it</span>
  <span m='4450810'>completely.</span> <span m='4451730'>I'm going</span> <span m='4452090'>to</span>
  <span m='4452220'>be</span> <span m='4452350'>very</span> <span m='4452650'>careful.</span>
  <span m='4455020'>This</span> <span m='4455360'>is</span> <span m='4455860'>open,</span>
  <span m='4456360'>open,</span> <span m='4456870'>lambda</span> <span m='4457260'>of</span>
  <span m='4457420'>x ,</span> <span m='4459220'>capital</span> <span m='4459760'>F,</span>
  <span m='4461120'>x,</span> <span m='4461660'>x,</span> <span m='4466980'>applied</span>
  <span m='4467510'>to</span> <span m='4468860'>itself,</span> <span m='4473520'>F</span>
  <span m='4473940'>of</span> <span m='4474610'>x</span> <span m='4474930'>of</span>
  <span m='4475110'>x.</span> <span m='4477910'>Substituting</span> <span m='4478430'>this</span>
  <span m='4478670'>for</span> <span m='4478920'>this</span> <span m='4479130'>in</span>
  <span m='4479220'>here,</span> <span m='4479810'>this</span> <span m='4480450'>is</span>
  <span m='4483220'>F</span> <span m='4483490'>applied</span> <span m='4483930'>to--</span>
  <span m='4485600'>what</span> <span m='4485760'>is</span> <span m='4485900'>it--</span>
  <span m='4487040'>substituting</span> <span m='4487640'>this</span> <span m='4487850'>in</span>
  <span m='4487960'>here,</span> <span m='4488780'>open,</span> <span m='4489300'>open,</span>
  <span m='4489860'>lambda</span> <span m='4490590'>of</span> <span m='4490910'>x,</span>
  <span m='4492700'>F,</span> <span m='4493240'>of</span> <span m='4493850'>x</span>
  <span m='4494180'>and</span> <span m='4494350'>x,</span> <span m='4497150'>applied</span>
  <span m='4497660'>to</span> <span m='4499320'>lambda</span> <span m='4499600'>of</span>
  <span m='4499870'>x,</span> <span m='4502590'>F</span> <span m='4503300'>of</span>
  <span m='4504220'>x</span> <span m='4504520'>of</span> <span m='4504720'>x,</span>
  <span m='4506380'>F,</span> <span m='4507060'>lambda,</span> <span m='4508910'>pair,</span>
  <span m='4510260'>F.</span> </p><p><span m='4511510'>Oh,</span> <span m='4511720'>but
  what</span> <span m='4511920'>is</span> <span m='4512070'>this?</span> <span m='4513420'>This</span>
  <span m='4513830'>thing</span> <span m='4514030'>over</span> <span m='4514240'>here</span>
  <span m='4515340'>that</span> <span m='4515470'>I</span> <span m='4515600'>just</span>
  <span m='4515830'>computed,</span> <span m='4517270'>is</span> <span m='4517490'>this</span>
  <span m='4517740'>thing</span> <span m='4517930'>over</span> <span m='4518120'>here.</span>
  <span m='4520030'>But</span> <span m='4520330'>I just</span> <span m='4520630'>wrapped</span>
  <span m='4520850'>another</span> <span m='4521030'>F</span> <span m='4521250'>around</span>
  <span m='4521560'>it.</span> <span m='4523370'>So</span> <span m='4523610'>by</span>
  <span m='4523780'>applying</span> <span m='4524270'>y to</span> <span m='4524520'>F,</span>
  <span m='4524720'>I</span> <span m='4524790'>make</span> <span m='4524990'>an</span>
  <span m='4525090'>infinite</span> <span m='4525440'>series</span> <span m='4525700'>of</span>
  <span m='4525985'>F's.</span> <span m='4527850'>If</span> <span m='4528240'>I</span>
  <span m='4528330'>just</span> <span m='4528480'>let this</span> <span m='4528640'>run</span>
  <span m='4528970'>forever,</span> <span m='4529730'>I'll</span> <span m='4529980'>just</span>
  <span m='4530180'>keep</span> <span m='4530400'>making more</span> <span m='4530640'>and</span>
  <span m='4530700'>more</span> <span m='4530900'>F's</span> <span m='4531170'>outside.</span>
  <span m='4533170'>I ran</span> <span m='4533540'>an</span> <span m='4533680'>infinite</span>
  <span m='4533820'>loop</span> <span m='4534020'>which</span> <span m='4534160'>is</span>
  <span m='4534340'>useless,</span> <span m='4535150'>but</span> <span m='4535310'>it</span>
  <span m='4535360'>doesn't</span> <span m='4535600'>matter</span> <span m='4535820'>that</span>
  <span m='4535990'>the</span> <span m='4536070'>inside</span> <span m='4536430'>is</span>
  <span m='4536530'>useless.</span> </p><p><span m='4540220'>So</span> <span m='4542040'>y</span>
  <span m='4542380'>of</span> <span m='4542490'>F</span> <span m='4544490'>is</span>
  <span m='4546030'>F</span> <span m='4546180'>applied</span> <span m='4546600'>to</span>
  <span m='4547230'>y</span> <span m='4547600'>of</span> <span m='4547960'>F.</span>
  <span m='4550230'>So</span> <span m='4550500'>y</span> <span m='4550910'>is</span>
  <span m='4551070'>a</span> <span m='4551120'>magical</span> <span m='4551670'>thing</span>
  <span m='4553900'>which,</span> <span m='4554660'>when</span> <span m='4554820'>applied</span>
  <span m='4555190'>to</span> <span m='4555340'>some</span> <span m='4555650'>function,</span>
  <span m='4557450'>produces</span> <span m='4558200'>the</span> <span m='4558380'>object</span>
  <span m='4558840'>which</span> <span m='4558960'>is</span> <span m='4559070'>the</span>
  <span m='4559140'>fixed</span> <span m='4559400'>point</span> <span m='4559610'>of</span>
  <span m='4559690'>that</span> <span m='4559900'>function,</span> <span m='4561780'>if</span>
  <span m='4561970'>it</span> <span m='4562040'>exists,</span> <span m='4563200'>and</span>
  <span m='4563350'>if</span> <span m='4563500'>this</span> <span m='4563660'>all</span>
  <span m='4563830'>works.</span> <span m='4567910'>Because,</span> <span m='4568330'>indeed,</span>
  <span m='4568640'>if</span> <span m='4568740'>I</span> <span m='4568820'>take</span>
  <span m='4569070'>y</span> <span m='4569290'>of</span> <span m='4569460'>F</span>
  <span m='4569580'>and put</span> <span m='4569690'>it</span> <span m='4569900'>into
  F,</span> <span m='4570190'>I get</span> <span m='4570380'>y</span> <span m='4570550'>of</span>
  <span m='4570670'>F</span> <span m='4570830'>out.</span> </p><p><span m='4576240'>Now
  I</span> <span m='4576400'>want</span> <span m='4576640'>you</span> <span m='4576680'>to</span>
  <span m='4576770'>think</span> <span m='4577250'>this</span> <span m='4577850'>in</span>
  <span m='4578070'>terms</span> <span m='4578440'>of</span> <span m='4579840'>the</span>
  <span m='4580180'>eval-apply</span> <span m='4580750'>interpreter</span> <span m='4582000'>for</span>
  <span m='4582090'>a</span> <span m='4582180'>bit.</span> <span m='4583860'>I</span>
  <span m='4584020'>wrote</span> <span m='4584220'>down a</span> <span m='4584370'>whole</span>
  <span m='4584570'>bunch</span> <span m='4584810'>of</span> <span m='4584920'>recursion</span>
  <span m='4585300'>equations</span> <span m='4585750'>out</span> <span m='4585940'>there.</span>
  <span m='4588540'>They're</span> <span m='4588710'>simultaneous</span> <span m='4589410'>in</span>
  <span m='4589470'>the</span> <span m='4589530'>same</span> <span m='4589750'>way</span>
  <span m='4589880'>these</span> <span m='4590140'>are</span> <span m='4590210'>simultaneous</span>
  <span m='4590750'>equations.</span> <span m='4591470'>Exponentiation</span> <span
  m='4592420'>was</span> <span m='4592490'>not</span> <span m='4592750'>a</span> <span
  m='4592940'>simultaneous</span> <span m='4593200'>equation.</span> <span m='4593310'>It</span>
  <span m='4593430'>was</span> <span m='4593540'>only</span> <span m='4593680'>one</span>
  <span m='4593860'>variable</span> <span m='4594180'>I</span> <span m='4594550'>was</span>
  <span m='4594690'>looking for</span> <span m='4595030'>a  meaning</span> <span m='4595400'>for.</span>
  </p><p><span m='4598150'>But</span> <span m='4598340'>what</span> <span m='4598500'>Lisp</span>
  <span m='4598800'>is</span> <span m='4599540'>is</span> <span m='4599710'>the</span>
  <span m='4599810'>fixed</span> <span m='4600090'>point</span> <span m='4600330'>of</span>
  <span m='4600450'>the</span> <span m='4600500'>process</span> <span m='4601030'>which</span>
  <span m='4601210'>says,</span> <span m='4601380'>if</span> <span m='4601570'>I</span>
  <span m='4601690'>knew</span> <span m='4601970'>what</span> <span m='4602050'>Lisp
  was</span> <span m='4602660'>and</span> <span m='4602830'>substituted</span> <span
  m='4603175'>it</span> <span m='4603520'>in for</span> <span m='4604740'>eval,</span>
  <span m='4605320'>and</span> <span m='4605450'>apply,</span> <span m='4605830'>and</span>
  <span m='4605980'>so</span> <span m='4606190'>on,</span> <span m='4606570'>on</span>
  <span m='4606780'>the</span> <span m='4606850'>right</span> <span m='4607080'>hand</span>
  <span m='4607280'>sides</span> <span m='4607540'>of</span> <span m='4607650'>all</span>
  <span m='4607780'>those</span> <span m='4608740'>recursion</span> <span m='4609100'>equations,</span>
  <span m='4610990'>then</span> <span m='4611290'>if</span> <span m='4611470'>it</span>
  <span m='4611540'>was a</span> <span m='4611740'>real good</span> <span m='4611930'>Lisp,</span>
  <span m='4613190'>is</span> <span m='4613280'>a</span> <span m='4613350'>real</span>
  <span m='4613580'>one,</span> <span m='4614450'>then</span> <span m='4614630'>the</span>
  <span m='4614720'>left</span> <span m='4614990'>hand</span> <span m='4615180'>side</span>
  <span m='4615340'>would</span> <span m='4615480'>also</span> <span m='4615790'>be</span>
  <span m='4615960'>Lisp.</span> <span m='4618220'>So</span> <span m='4618380'>I</span>
  <span m='4618430'>made</span> <span m='4618690'>sense</span> <span m='4618980'>of</span>
  <span m='4619130'>that</span> <span m='4619280'>definition.</span> <span m='4622420'>Now</span>
  <span m='4622600'>whether</span> <span m='4622860'>or</span> <span m='4622920'>not</span>
  <span m='4623190'>there's</span> <span m='4623410'>an</span> <span m='4623510'>answer</span>
  <span m='4624630'>isn't</span> <span m='4624880'>so</span> <span m='4625030'>obvious.</span>
  <span m='4625410'>I</span> <span m='4625790'>can't</span> <span m='4626230'>attack</span>
  <span m='4626570'>that.</span> </p><p><span m='4627740'>Now</span> <span m='4627910'>these</span>
  <span m='4628140'>arguments</span> <span m='4628580'>that</span> <span m='4628710'>I'm</span>
  <span m='4628840'>giving</span> <span m='4629060'>you</span> <span m='4629160'>now</span>
  <span m='4629350'>are</span> <span m='4629450'>quite</span> <span m='4629750'>dangerous.</span>
  <span m='4630660'>Let's</span> <span m='4630860'>look</span> <span m='4631010'>over</span>
  <span m='4631190'>here.</span> <span m='4633570'>These are</span> <span m='4633940'>limit</span>
  <span m='4634190'>arguments.</span> <span m='4634610'>We're</span> <span m='4634710'>talking</span>
  <span m='4634900'>about</span> <span m='4635120'>limits,</span> <span m='4635490'>and
  it's</span> <span m='4635850'>really calculus,</span> <span m='4636810'>or</span>
  <span m='4637020'>topology,</span> <span m='4637930'>or</span> <span m='4638110'>something</span>
  <span m='4638440'>like</span> <span m='4638670'>that,</span> <span m='4638950'>a
  kind</span> <span m='4639150'>of</span> <span m='4639210'>analysis.</span> <span
  m='4641255'>Now</span> <span m='4641650'>here's</span> <span m='4641940'>an</span>
  <span m='4642030'>argument</span> <span m='4642410'>that</span> <span m='4642540'>you</span>
  <span m='4642670'>all</span> <span m='4642830'>believe.</span> <span m='4643380'>And</span>
  <span m='4643600'>I</span> <span m='4643700'>want</span> <span m='4643810'>to</span>
  <span m='4643920'>make</span> <span m='4644090'>sure</span> <span m='4644300'>you</span>
  <span m='4644740'>realize</span> <span m='4645370'>that</span> <span m='4645520'>I</span>
  <span m='4645680'>could</span> <span m='4645850'>be</span> <span m='4647010'>bullshitting</span>
  <span m='4647510'>you.</span> </p><p><span m='4649660'>What</span> <span m='4650000'>is</span>
  <span m='4650190'>this?</span> <span m='4654250'>u</span> <span m='4654550'>is</span>
  <span m='4654970'>the</span> <span m='4655280'>sum</span> <span m='4657600'>of</span>
  <span m='4657790'>1/2,</span> <span m='4658190'>1/4,</span> <span m='4658560'>and</span>
  <span m='4658680'>1/8,</span> <span m='4658860'>and</span> <span m='4658980'>so</span>
  <span m='4659250'>on,</span> <span m='4659500'>the</span> <span m='4659820'>sum</span>
  <span m='4660130'>of</span> <span m='4660220'>a</span> <span m='4660300'>geometric</span>
  <span m='4660850'>series.</span> <span m='4662820'>And,</span> <span m='4663010'>of</span>
  <span m='4663110'>course,</span> <span m='4663480'>I</span> <span m='4663580'>could</span>
  <span m='4663730'>play</span> <span m='4663930'>a</span> <span m='4663970'>game</span>
  <span m='4664260'>here.</span> <span m='4664820'>u</span> <span m='4665050'>minus</span>
  <span m='4665460'>one</span> <span m='4665770'>is</span> <span m='4665950'>1/2,</span>
  <span m='4666200'>plus</span> <span m='4666380'>1/4,</span> <span m='4666660'>plus</span>
  <span m='4666800'>1/8,</span> <span m='4667100'>and so</span> <span m='4667300'>on.</span>
  <span m='4673590'>What</span> <span m='4673720'>I could</span> <span m='4673930'>do</span>
  <span m='4674120'>here--</span> <span m='4676190'>oops.</span> <span m='4676680'>There</span>
  <span m='4676800'>is</span> <span m='4676860'>a</span> <span m='4677160'>parentheses</span>
  <span m='4677340'>error</span> <span m='4677570'>here.</span> <span m='4678920'>But</span>
  <span m='4679110'>I</span> <span m='4679190'>can</span> <span m='4679330'>put</span>
  <span m='4679470'>here</span> <span m='4679870'>two</span> <span m='4680250'>times</span>
  <span m='4680600'>u</span> <span m='4680720'>minus</span> <span m='4681040'>one</span>
  <span m='4681760'>is</span> <span m='4681990'>one</span> <span m='4682400'>plus</span>
  <span m='4682660'>1/2,</span> <span m='4682740'>plus</span> <span m='4683150'>1/4,</span>
  <span m='4683350'>plus</span> <span m='4683530'>1/8.</span> <span m='4687570'>Can</span>
  <span m='4687750'>I</span> <span m='4687840'>fix</span> <span m='4688200'>that?</span>
  <span m='4694010'>Yes,</span> <span m='4695760'>well.</span> <span m='4699520'>But</span>
  <span m='4699710'>that</span> <span m='4699920'>gives</span> <span m='4700120'>me</span>
  <span m='4700310'>back</span> <span m='4703970'>two</span> <span m='4704430'>times</span>
  <span m='4704680'>u</span> <span m='4704810'>minus</span> <span m='4705140'>one</span>
  <span m='4706080'>is</span> <span m='4706300'>u,</span> <span m='4707850'>therefore,</span>
  <span m='4708300'>we conclude</span> <span m='4708700'>that</span> <span m='4708830'>u</span>
  <span m='4708950'>is</span> <span m='4709170'>two.</span> <span m='4710300'>And</span>
  <span m='4710460'>this</span> <span m='4710610'>actually</span> <span m='4710960'>is</span>
  <span m='4711050'>true.</span> <span m='4711830'>There's</span> <span m='4712310'>no</span>
  <span m='4712460'>problem</span> <span m='4712830'>like</span> <span m='4713040'>that.</span>
  <span m='4713910'>But</span> <span m='4714300'>supposing</span> <span m='4716010'>I</span>
  <span m='4716170'>did</span> <span m='4716380'>something</span> <span m='4717110'>different.</span>
  </p><p><span m='4718540'>Supposing</span> <span m='4718800'>I</span> <span m='4718890'>start</span>
  <span m='4719130'>up</span> <span m='4719240'>with</span> <span m='4719340'>something</span>
  <span m='4719570'>which</span> <span m='4719740'>manifestly</span> <span m='4720350'>has</span>
  <span m='4720570'>no</span> <span m='4720720'>sum.</span> <span m='4721470'>v</span>
  <span m='4722520'>is</span> <span m='4722730'>one,</span> <span m='4723110'>plus</span>
  <span m='4723460'>two,</span> <span m='4723660'>plus</span> <span m='4723930'>four,</span>
  <span m='4724140'>plus</span> <span m='4724330'>8,</span> <span m='4724700'>plus</span>
  <span m='4724960'>dot,</span> <span m='4725270'>dot,</span> <span m='4725610'>dot.</span>
  <span m='4727390'>Well,</span> <span m='4727490'>v</span> <span m='4727720'>minus</span>
  <span m='4728040'>one is</span> <span m='4728190'>surely</span> <span m='4728520'>two,</span>
  <span m='4728660'>plus</span> <span m='4728880'>four,</span> <span m='4729040'>plus</span>
  <span m='4729280'>eight,</span> <span m='4729560'>plus</span> <span m='4729800'>dot,</span>
  <span m='4730000'>dot,</span> <span m='4730335'>dot.</span> <span m='4732010'>v</span>
  <span m='4732620'>minus</span> <span m='4732990'>one</span> <span m='4733210'>over</span>
  <span m='4733420'>two,</span> <span m='4734710'>gee,</span> <span m='4734850'>that</span>
  <span m='4735000'>looks</span> <span m='4735160'>like</span> <span m='4735350'>v</span>
  <span m='4735655'>again.</span> <span m='4737410'>From</span> <span m='4737700'>that</span>
  <span m='4737850'>I</span> <span m='4737950'>should</span> <span m='4738130'>be</span>
  <span m='4738300'>able to</span> <span m='4738380'>conclude</span> <span m='4740020'>that--</span>
  <span m='4741070'>that's</span> <span m='4741670'>also</span> <span m='4741990'>wrong,</span>
  <span m='4742270'>apparently.</span> <span m='4743070'>v</span> <span m='4743500'>equals</span>
  <span m='4743780'>minus</span> <span m='4744140'>one.</span> <span m='4752455'>That</span>
  <span m='4752720'>should be</span> <span m='4753070'>a</span> <span m='4753480'>minus
  one.</span> <span m='4755280'>And</span> <span m='4755630'>that's</span> <span m='4755880'>certainly</span>
  <span m='4756110'>a</span> <span m='4756170'>false</span> <span m='4756450'>conclusion.</span>
  </p><p><span m='4762000'>So</span> <span m='4762230'>when</span> <span m='4762450'>you</span>
  <span m='4762560'>play</span> <span m='4762830'>with</span> <span m='4762950'>limits,</span>
  <span m='4764180'>arguments</span> <span m='4764860'>that</span> <span m='4765050'>may</span>
  <span m='4765230'>work</span> <span m='4766870'>in</span> <span m='4767030'>one</span>
  <span m='4767300'>case</span> <span m='4769540'>they</span> <span m='4769660'>may</span>
  <span m='4769770'>not</span> <span m='4769990'>work</span> <span m='4770150'>in</span>
  <span m='4770240'>some</span> <span m='4770400'>other</span> <span m='4770530'>case.</span>
  <span m='4770750'>You have to</span> <span m='4770910'>be</span> <span m='4771000'>very</span>
  <span m='4771250'>careful.</span> <span m='4772240'>The</span> <span m='4772500'>arguments</span>
  <span m='4772910'>have</span> <span m='4773040'>to</span> <span m='4773110'>be</span>
  <span m='4773230'>well</span> <span m='4773450'>formed.</span> <span m='4775752'>And</span>
  <span m='4776210'>I</span> <span m='4776580'>don't</span> <span m='4776830'>know,</span>
  <span m='4778490'>in</span> <span m='4778690'>general,</span> <span m='4779760'>what</span>
  <span m='4780050'>the</span> <span m='4780130'>story</span> <span m='4780520'>is</span>
  <span m='4780610'>about</span> <span m='4780790'>arguments</span> <span m='4781330'>like</span>
  <span m='4781550'>this.</span> <span m='4783270'>We</span> <span m='4783410'>can</span>
  <span m='4783540'>read</span> <span m='4783730'>a</span> <span m='4783780'>pile</span>
  <span m='4784030'>of</span> <span m='4784190'>topology</span> <span m='4784610'>and</span>
  <span m='4784730'>find</span> <span m='4785030'>out.</span> </p><p><span m='4786060'>But,</span>
  <span m='4786600'>surely,</span> <span m='4787230'>at</span> <span m='4787440'>least</span>
  <span m='4787650'>you</span> <span m='4787760'>understand</span> <span m='4788340'>now,</span>
  <span m='4789190'>why</span> <span m='4789440'>it</span> <span m='4789530'>might</span>
  <span m='4789750'>be</span> <span m='4789880'>some</span> <span m='4790590'>meaning</span>
  <span m='4791160'>to</span> <span m='4791270'>the</span> <span m='4791370'>things</span>
  <span m='4791580'>we've</span> <span m='4791690'>been</span> <span m='4791790'>writing</span>
  <span m='4792050'>on</span> <span m='4792160'>the</span> <span m='4792230'>blackboard.</span>
  <span m='4793260'>And</span> <span m='4793730'>you</span> <span m='4793920'>understand</span>
  <span m='4794530'>what</span> <span m='4794730'>that</span> <span m='4794940'>might</span>
  <span m='4795200'>mean.</span> <span m='4796480'>So,</span> <span m='4796690'>I</span>
  <span m='4796780'>suppose,</span> <span m='4797080'>it's</span> <span m='4797230'>almost</span>
  <span m='4797650'>about</span> <span m='4797940'>time</span> <span m='4799120'>for</span>
  <span m='4800280'>you</span> <span m='4800540'>to</span> <span m='4801490'>merit</span>
  <span m='4802900'>being</span> <span m='4803160'>made</span> <span m='4803340'>a</span>
  <span m='4803380'>member</span> <span m='4804370'>of</span> <span m='4804480'>the</span>
  <span m='4804590'>grand</span> <span m='4804870'>recursive</span> <span m='4805130'>order</span>
  <span m='4805570'>of</span> <span m='4805720'>lambda</span> <span m='4806020'>calculus</span>
  <span m='4806550'>hackers.</span> <span m='4809320'>This</span> <span m='4809480'>is</span>
  <span m='4809590'>the</span> <span m='4809680'>badge.</span> <span m='4810820'>Because</span>
  <span m='4811030'>you</span> <span m='4811120'>now</span> <span m='4811360'>understand,</span>
  <span m='4811890'>for</span> <span m='4812040'>example,</span> <span m='4813500'>what</span>
  <span m='4813710'>it</span> <span m='4813840'>says</span> <span m='4814420'>at</span>
  <span m='4814540'>the</span> <span m='4814620'>very</span> <span m='4814900'>top,</span>
  <span m='4817000'>y</span> <span m='4817260'>F</span> <span m='4817420'>equals</span>
  <span m='4817530'>F</span> <span m='4817730'>y</span> <span m='4817920'>F.</span>
  <span m='4820810'>Thank</span> <span m='4821410'>you.</span> <span m='4821890'>Are</span>
  <span m='4822020'>there</span> <span m='4822160'>any</span> <span m='4822260'>questions?</span>
  <span m='4824710'>Yes,</span> <span m='4824960'>Lev.</span> </p><p><span m='4825150'>AUDIENCE:</span>
  <span m='4825510'>With</span> <span m='4825800'>this,</span> <span m='4826380'>it</span>
  <span m='4826580'>seems</span> <span m='4826830'>that</span> <span m='4827130'>then</span>
  <span m='4827370'>there's</span> <span m='4827640'>no</span> <span m='4827840'>need</span>
  <span m='4828150'>to</span> <span m='4828250'>define,</span> <span m='4829400'>as</span>
  <span m='4829590'>you</span> <span m='4829690'>imply,</span> <span m='4830250'>to</span>
  <span m='4830700'>just</span> <span m='4831000'>remember a</span> <span m='4831330'>value,</span>
  <span m='4831720'>to</span> <span m='4831850'>apply</span> <span m='4832190'>it</span>
  <span m='4832310'>later.</span> <span m='4834090'>Defines</span> <span m='4834620'>were</span>
  <span m='4834720'>kind</span> <span m='4834910'>of a</span> <span m='4835060'>side-effect</span>
  <span m='4835595'>it</span> <span m='4835850'>seemed</span> <span m='4836090'>in</span>
  <span m='4836180'>the</span> <span m='4836260'>language.</span> <span m='4836490'>[INTERPOSING]</span>
  <span m='4837075'>are</span> <span m='4837360'>order</span> <span m='4837860'>dependent.</span>
  <span m='4839300'>Does</span> <span m='4839510'>this</span> <span m='4839860'>eliminate</span>
  <span m='4840285'>the</span> <span m='4841145'>side-effect</span> <span m='4842015'>from</span>
  <span m='4842450'>the</span> <span m='4842820'>[INTERPOSING]</span> </p><p><span
  m='4843150'>PROFESSOR:</span> <span m='4843480'>The</span> <span m='4843990'>answer</span>
  <span m='4844420'>is,</span> <span m='4844900'>this</span> <span m='4845130'>is</span>
  <span m='4845230'>not</span> <span m='4845460'>the</span> <span m='4845520'>way</span>
  <span m='4845650'>these</span> <span m='4845840'>things</span> <span m='4846010'>were</span>
  <span m='4846280'>implemented.</span> <span m='4849180'>Define,</span> <span m='4850400'>indeed</span>
  <span m='4851120'>is</span> <span m='4851280'>implemented</span> <span m='4852270'>as</span>
  <span m='4852490'>an</span> <span m='4852600'>operation</span> <span m='4853220'>that</span>
  <span m='4853480'>actually</span> <span m='4853830'>modifies</span> <span m='4854125'>an</span>
  <span m='4854420'>environment</span> <span m='4855010'>structure,</span> <span m='4857940'>changes</span>
  <span m='4858380'>the</span> <span m='4858480'>frame</span> <span m='4859000'>that
  the</span> <span m='4859400'>define</span> <span m='4859980'>is</span> <span m='4861540'>executed</span>
  <span m='4862090'>in.</span> <span m='4863690'>And</span> <span m='4865290'>there</span>
  <span m='4865370'>are</span> <span m='4865410'>many</span> <span m='4865650'>reasons</span>
  <span m='4866050'>for</span> <span m='4866150'>that,</span> <span m='4867460'>but</span>
  <span m='4867630'>a</span> <span m='4867750'>lot</span> <span m='4867880'>of</span>
  <span m='4868000'>this</span> <span m='4868170'>has</span> <span m='4868370'>to</span>
  <span m='4868440'>do</span> <span m='4868600'>with</span> <span m='4868760'>making</span>
  <span m='4869070'>an</span> <span m='4869160'>interactive</span> <span m='4869590'>system.</span>
  <span m='4871340'>What</span> <span m='4871650'>this</span> <span m='4871850'>is</span>
  <span m='4871970'>saying</span> <span m='4872340'>is</span> <span m='4872740'>that</span>
  <span m='4872910'>if</span> <span m='4873050'>you've</span> <span m='4873280'>made</span>
  <span m='4873530'>a</span> <span m='4873580'>system,</span> <span m='4874150'>and</span>
  <span m='4874490'>you</span> <span m='4874750'>know</span> <span m='4875420'>you're</span>
  <span m='4875700'>not</span> <span m='4875920'>going to</span> <span m='4876000'>do
  any</span> <span m='4876315'>debugging</span> <span m='4876630'>or</span> <span
  m='4876690'>anything</span> <span m='4876980'>like</span> <span m='4877210'>that,</span>
  <span m='4877580'>and</span> <span m='4877930'>you</span> <span m='4878160'>know</span>
  <span m='4878370'>everything</span> <span m='4878840'>there</span> <span m='4879090'>is</span>
  <span m='4879960'>all</span> <span m='4880180'>at</span> <span m='4880240'>once,</span>
  <span m='4880505'>and</span> <span m='4880770'>you</span> <span m='4880930'>want
  to</span> <span m='4881070'>say,</span> <span m='4881170'>what</span> <span m='4881300'>is</span>
  <span m='4881420'>the</span> <span m='4881510'>meaning</span> <span m='4881740'>of</span>
  <span m='4881840'>a</span> <span m='4881930'>final</span> <span m='4882240'>set</span>
  <span m='4882390'>of</span> <span m='4882460'>equations?</span> <span m='4884090'>This</span>
  <span m='4884280'>gives</span> <span m='4884470'>you a</span> <span m='4884570'>meaning</span>
  <span m='4884900'>for</span> <span m='4885140'>it.</span> <span m='4885790'>But</span>
  <span m='4886050'>in</span> <span m='4886120'>order</span> <span m='4886310'>to</span>
  <span m='4886420'>make an</span> <span m='4886580'>interactive</span> <span m='4887130'>system,</span>
  <span m='4887490'>where</span> <span m='4887600'>you</span> <span m='4887740'>can</span>
  <span m='4887860'>change the</span> <span m='4888200'>meaning</span> <span m='4888500'>of</span>
  <span m='4888640'>one</span> <span m='4888780'>thing</span> <span m='4888920'>without</span>
  <span m='4889170'>changing</span> <span m='4889430'>everything</span> <span m='4889790'>else,</span>
  <span m='4890890'>incrementally,</span> <span m='4892740'>you</span> <span m='4893190'>can't</span>
  <span m='4893450'>do</span> <span m='4893580'>that</span> <span m='4893780'>by</span>
  <span m='4894020'>implementing</span> <span m='4894470'>it</span> <span m='4894570'>this</span>
  <span m='4894760'>way.</span> <span m='4900990'>Yes.</span> </p><p><span m='4901860'>AUDIENCE:</span>
  <span m='4902360'>Another</span> <span m='4902670'>question</span> <span m='4902980'>on</span>
  <span m='4903260'>your</span> <span m='4903390'>danger</span> <span m='4903730'>slide.</span>
  <span m='4904650'>It</span> <span m='4904810'>seemed</span> <span m='4905010'>that</span>
  <span m='4905940'>the</span> <span m='4906270'>two</span> <span m='4906400'>examples</span>
  <span m='4906780'>that</span> <span m='4906890'>you</span> <span m='4906990'>gave</span>
  <span m='4907210'>had to</span> <span m='4907350'>do</span> <span m='4907530'>with</span>
  <span m='4907600'>convergence</span> <span m='4907885'>and</span> <span m='4908170'>non-convergence?</span>
  <span m='4910300'>And</span> <span m='4911240'>that</span> <span m='4911520'>may</span>
  <span m='4911680'>or</span> <span m='4911740'>may</span> <span m='4911840'>not</span>
  <span m='4912010'>have</span> <span m='4912130'>something</span> <span m='4912390'>to</span>
  <span m='4912490'>do with</span> <span m='4912970'>function</span> <span m='4913380'>theory</span>
  <span m='4913690'>in</span> <span m='4913750'>a</span> <span m='4914060'>way</span>
  <span m='4914250'>which</span> <span m='4914760'>would</span> <span m='4914990'>lead
  you to</span> <span m='4915210'>think</span> <span m='4915360'>of</span> <span m='4915430'>it</span>
  <span m='4915540'>in</span> <span m='4915600'>terms</span> <span m='4915800'>of</span>
  <span m='4915870'>linear</span> <span m='4916140'>systems,</span> <span m='4917770'>or</span>
  <span m='4918010'>non-linear</span> <span m='4918430'>systems.</span> <span m='4919350'>How</span>
  <span m='4919500'>does</span> <span m='4919710'>this</span> <span m='4919900'>convergence</span>
  <span m='4920500'>relate</span> <span m='4920830'>to</span> <span m='4920950'>being</span>
  <span m='4921170'>able</span> <span m='4921400'>to</span> <span m='4922280'>see</span>
  <span m='4922620'>a priori</span> <span m='4923140'>what</span> <span m='4923440'>properties
  of</span> <span m='4923870'>that</span> <span m='4924150'>might</span> <span m='4924480'>be</span>
  <span m='4924590'>violated?</span> </p><p><span m='4925430'>PROFESSOR:</span> <span
  m='4925870'>I</span> <span m='4926030'>don't</span> <span m='4926300'>know.</span>
  <span m='4927680'>The</span> <span m='4927800'>answer</span> <span m='4928060'>is,</span>
  <span m='4928160'>I</span> <span m='4928270'>don't</span> <span m='4928550'>know</span>
  <span m='4928730'>under</span> <span m='4928930'>what</span> <span m='4929160'>circumstances.</span>
  <span m='4930610'>I</span> <span m='4930840'>don't</span> <span m='4930950'>know</span>
  <span m='4931060'>how</span> <span m='4931150'>to</span> <span m='4931230'>translate</span>
  <span m='4931790'>that</span> <span m='4932530'>into</span> <span m='4933320'>less</span>
  <span m='4933490'>than</span> <span m='4933570'>an</span> <span m='4933660'>hour</span>
  <span m='4933940'>of</span> <span m='4934050'>talk</span> <span m='4934380'>more.</span>
  <span m='4936910'>What</span> <span m='4937160'>are</span> <span m='4937300'>the</span>
  <span m='4937410'>conditions</span> <span m='4937950'>under</span> <span m='4938160'>which,</span>
  <span m='4938720'>for</span> <span m='4939020'>which</span> <span m='4939190'>we</span>
  <span m='4939350'>know</span> <span m='4939750'>that</span> <span m='4939850'>these</span>
  <span m='4940040'>things</span> <span m='4940210'>converge?</span> <span m='4942720'>And</span>
  <span m='4943020'>v,</span> <span m='4943320'>all</span> <span m='4943500'>that</span>
  <span m='4943640'>was</span> <span m='4943770'>telling</span> <span m='4944050'>you</span>
  <span m='4944220'>that</span> <span m='4944460'>arguments</span> <span m='4945090'>that</span>
  <span m='4945200'>are</span> <span m='4945230'>based</span> <span m='4945530'>on</span>
  <span m='4945660'>convergence</span> <span m='4948260'>are</span> <span m='4949000'>flaky</span>
  <span m='4949700'>if</span> <span m='4949810'>you</span> <span m='4949930'>don't</span>
  <span m='4950130'>know</span> <span m='4950330'>the</span> <span m='4950420'>convergence</span>
  <span m='4950910'>beforehand.</span> <span m='4952810'>You</span> <span m='4952970'>can</span>
  <span m='4953110'>make</span> <span m='4953340'>wrong</span> <span m='4953660'>arguments.</span>
  <span m='4954440'>You</span> <span m='4954520'>can</span> <span m='4954610'>make</span>
  <span m='4954800'>deductions,</span> <span m='4955970'>as</span> <span m='4956290'>if</span>
  <span m='4956420'>you</span> <span m='4956540'>know</span> <span m='4956720'>the</span>
  <span m='4956890'>answer,</span> <span m='4957400'>and</span> <span m='4957600'>not</span>
  <span m='4957810'>be</span> <span m='4957900'>stopped</span> <span m='4958210'>somewhere</span>
  <span m='4958610'>by</span> <span m='4958760'>some</span> <span m='4958940'>obvious</span>
  <span m='4959320'>contradiction.</span> </p><p><span m='4960690'>AUDIENCE:</span>
  <span m='4961400'>So</span> <span m='4961560'>can</span> <span m='4961700'>we</span>
  <span m='4961790'>say</span> <span m='4961990'>then</span> <span m='4962370'>that
  if</span> <span m='4962650'>F</span> <span m='4963080'>is</span> <span m='4963300'>a</span>
  <span m='4963380'>convergent</span> <span m='4963635'>mathematical</span> <span
  m='4963890'>expression,</span> <span m='4965490'>then</span> <span m='4965660'>the</span>
  <span m='4965945'>recursion</span> <span m='4966230'>property</span> <span m='4966810'>can</span>
  <span m='4967070'>be--</span> </p><p><span m='4967690'>PROFESSOR:</span> <span m='4968070'>Well,
  I</span> <span m='4968210'>think</span> <span m='4969180'>there's</span> <span m='4969640'>a</span>
  <span m='4969740'>technical</span> <span m='4970680'>kind</span> <span m='4970880'>of</span>
  <span m='4971120'>F,</span> <span m='4972740'>there</span> <span m='4973020'>is</span>
  <span m='4973100'>a</span> <span m='4973180'>technical</span> <span m='4973950'>description</span>
  <span m='4974400'>of</span> <span m='4974530'>those</span> <span m='4974760'>F's</span>
  <span m='4975020'>that</span> <span m='4975150'>have</span> <span m='4975270'>the</span>
  <span m='4975350'>property</span> <span m='4976000'>that</span> <span m='4977300'>when</span>
  <span m='4977530'>you</span> <span m='4979880'>iteratively</span> <span m='4980350'>apply</span>
  <span m='4980630'>them</span> <span m='4980790'>like</span> <span m='4980990'>this,</span>
  <span m='4981580'>you</span> <span m='4981700'>converge.</span> <span m='4983020'>Things</span>
  <span m='4983270'>that</span> <span m='4983440'>are</span> <span m='4983620'>monotonic,</span>
  <span m='4985020'>and</span> <span m='4985490'>continuous,</span> <span m='4987410'>and</span>
  <span m='4988470'>I</span> <span m='4988590'>forgot</span> <span m='4988950'>what</span>
  <span m='4989060'>else.</span> <span m='4989370'>There is</span> <span m='4989470'>a</span>
  <span m='4989510'>whole</span> <span m='4989650'>bunch</span> <span m='4989870'>of</span>
  <span m='4989930'>little</span> <span m='4990110'>conditions</span> <span m='4990580'>like</span>
  <span m='4990830'>that</span> <span m='4992010'>which</span> <span m='4992170'>have</span>
  <span m='4992360'>this</span> <span m='4992510'>property.</span> <span m='4993430'>Now</span>
  <span m='4993660'>the</span> <span m='4993770'>real</span> <span m='4993980'>problem</span>
  <span m='4994310'>is</span> <span m='4994530'>deducing</span> <span m='4994550'>from</span>
  <span m='4995190'>looking</span> <span m='4995520'>at</span> <span m='4995650'>the</span>
  <span m='4995820'>F,</span> <span m='4997000'>its</span> <span m='4997160'>definition</span>
  <span m='4997670'>here,</span> <span m='4998260'>whether</span> <span m='4998470'>not</span>
  <span m='4998650'>it has</span> <span m='4998830'>those</span> <span m='4999020'>properties,</span>
  <span m='5000370'>and</span> <span m='5000550'>that's</span> <span m='5000850'>very</span>
  <span m='5001060'>hard.</span> <span m='5002010'>The</span> <span m='5002290'>properties</span>
  <span m='5002790'>are</span> <span m='5003170'>easy.</span> <span m='5003280'>You
  can write</span> <span m='5003490'>them</span> <span m='5003590'>down.</span> </p><p><span
  m='5004580'>You can</span> <span m='5004770'>look</span> <span m='5004950'>in</span>
  <span m='5004990'>a</span> <span m='5005030'>book</span> <span m='5005250'>by</span>
  <span m='5005390'>Joe</span> <span m='5005630'>Stoy.</span> <span m='5006930'>It's
  a</span> <span m='5007040'>great</span> <span m='5007330'>book--</span> <span m='5008660'>Stoy.</span>
  <span m='5011780'>It's</span> <span m='5012250'>called,</span> <span m='5012530'><i>The</i></span>
  <span m='5013030'><i>Scott-Strachey</i></span> <span m='5016350'><i>Method</i></span>
  <span m='5017150'><i>of</i></span> <span m='5017360'><i>Denotational</i></span>
  <span m='5017870'><i>Semantics</i>,</span> <span m='5019560'>and it's</span> <span
  m='5019830'>by</span> <span m='5020000'>Joe</span> <span m='5020260'>Stoy,</span>
  <span m='5020930'>MIT</span> <span m='5021350'>Press.</span> <span m='5027960'>And</span>
  <span m='5028290'>he</span> <span m='5028390'>works</span> <span m='5028630'>out</span>
  <span m='5028740'>all</span> <span m='5028920'>this</span> <span m='5029080'>in</span>
  <span m='5029180'>great</span> <span m='5029380'>detail,</span> <span m='5030300'>enough</span>
  <span m='5030540'>to</span> <span m='5030630'>horrify</span> <span m='5030930'>you.</span>
  <span m='5035080'>But</span> <span m='5035310'>it</span> <span m='5035410'>really</span>
  <span m='5035700'>is</span> <span m='5035810'>readable.</span> </p><p><span m='5049150'>OK,</span>
  <span m='5049440'>well,</span> <span m='5049590'>thank</span> <span m='5049850'>you.</span>
  <span m='5051490'>Time</span> <span m='5051710'>for</span> <span m='5051830'>the</span>
  <span m='5051960'>bigger</span> <span m='5052160'>break,</span> <span m='5052450'>I</span>
  <span m='5052530'>suppose.</span> </p>
type: course
uid: fc0495f305df1c5963fdacc15968c4aa

---
None