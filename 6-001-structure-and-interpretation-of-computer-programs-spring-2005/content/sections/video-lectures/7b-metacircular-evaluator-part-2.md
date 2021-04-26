---
about_this_resource_text: <p><b>Topics covered:</b> Metacircular Evaluator, Part 2</p>
  <p><b> Instructors:</b> Hal Abelson and Gerald Jay Sussman</p> <p>Subtitles for
  this course are provided through the generous assistance of Henry Baker, Hoofar
  Pourzand, Heather Wood, Aleksejs Truhans, Steven Edwards, George Menhorn, and Mahendra
  Kumar.</p>
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
embedded_media:
- id: 7B.jpg
  parent_uid: d3c1342e5db4adedb66673bcbfda3491
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/7b-metacircular-evaluator-part-2/7B.jpg
  title: 7B.jpg
  type: null
  uid: b59a27ab361cc061b77d69fb7217a8ab
- id: Video-YouTube-Stream
  media_location: QVEOq5k6Xi0
  parent_uid: d3c1342e5db4adedb66673bcbfda3491
  title: Video-YouTube-Stream
  type: Video
  uid: ec2419b6ca551e06e6602384c854cc48
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT_Structure_of_Computer_Programs_1986/lec7b.mp4
  parent_uid: d3c1342e5db4adedb66673bcbfda3491
  title: Video-Internet Archive-MP4
  type: Video
  uid: b398cc3ec70302296847d80b9415c54e
- id: Thumbnail-OCW-JPG
  parent_uid: d3c1342e5db4adedb66673bcbfda3491
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: a2f8339e6c03ff534faf21195af2c562
- id: 3Play-3PlayYouTubeid-MP4
  media_location: QVEOq5k6Xi0
  parent_uid: d3c1342e5db4adedb66673bcbfda3491
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 5e864813cba3b135839f9bda7aabab49
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/QVEOq5k6Xi0/default.jpg
  parent_uid: d3c1342e5db4adedb66673bcbfda3491
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: aa2d6c0f6dd857b9f152c703f90d64dd
- id: QVEOq5k6Xi0.srt
  parent_uid: d3c1342e5db4adedb66673bcbfda3491
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/7b-metacircular-evaluator-part-2/QVEOq5k6Xi0.srt
  title: 3play caption file
  type: null
  uid: 62e920d7681f04bdd7969af9966b67bc
- id: QVEOq5k6Xi0.pdf
  parent_uid: d3c1342e5db4adedb66673bcbfda3491
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/7b-metacircular-evaluator-part-2/QVEOq5k6Xi0.pdf
  title: 3play pdf file
  type: null
  uid: 771092351b136b40083a0f5d147ed2b9
- id: Caption-3Play YouTube id-SRT
  parent_uid: d3c1342e5db4adedb66673bcbfda3491
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: b2a7c51c312a7be62c133243d5798431
- id: Transcript-3Play YouTube id-PDF
  parent_uid: d3c1342e5db4adedb66673bcbfda3491
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 1be9791a22c447112fa52a3d01bcc253
inline_embed_id: 800879527b:metacircularevaluator,part294626799
layout: video
order_index: null
parent_uid: 4fcacad2c29981dd668a6b29822403cc
related_resources_text: ''
short_url: 7b-metacircular-evaluator-part-2
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/7b-metacircular-evaluator-part-2
template_type: Tabbed
title: '7B: Metacircular Evaluator, Part 2'
transcript: <p><span m='994'>[MUSIC PLAYING]</span> </p><p><span m='16401'>PROFESSOR:</span>
  <span m='16930'>Well,</span> <span m='17240'>let's</span> <span m='17550'>see.</span>
  <span m='19520'>What</span> <span m='19840'>we</span> <span m='19950'>did</span>
  <span m='20120'>so</span> <span m='20290'>far</span> <span m='20500'>was</span>
  <span m='20630'>a</span> <span m='20690'>lot</span> <span m='20900'>of</span> <span
  m='20980'>fun,</span> <span m='21590'>was</span> <span m='21800'>it</span> <span
  m='21860'>useful</span> <span m='22210'>for</span> <span m='22390'>anything?</span>
  <span m='26330'>I</span> <span m='26490'>suppose</span> <span m='26790'>the</span>
  <span m='26890'>answer is</span> <span m='27280'>going</span> <span m='27370'>to</span>
  <span m='27460'>be</span> <span m='27550'>yes.</span> <span m='29380'>If</span>
  <span m='30190'>these</span> <span m='30540'>metacircular</span> <span m='31270'>interpreters</span>
  <span m='33030'>are</span> <span m='33300'>a</span> <span m='33350'>valuable</span>
  <span m='33930'>thing</span> <span m='34120'>to</span> <span m='34200'>play</span>
  <span m='34440'>with.</span> <span m='38050'>Well,</span> <span m='38210'>there</span>
  <span m='38500'>have</span> <span m='38730'>been</span> <span m='38830'>times</span>
  <span m='39080'>I spend</span> <span m='39330'>50%</span> <span m='39490'>of</span>
  <span m='39660'>my</span> <span m='39820'>time,</span> <span m='40920'>over</span>
  <span m='41270'>a</span> <span m='41300'>year,</span> <span m='42870'>trying</span>
  <span m='43450'>various</span> <span m='43970'>design</span> <span m='44490'>alternatives</span>
  <span m='45810'>by</span> <span m='45950'>experimenting</span> <span m='46590'>with</span>
  <span m='46720'>them</span> <span m='47020'>with</span> <span m='47220'>metacircular</span>
  <span m='47620'>interpreters--</span> <span m='49600'>metacircular</span> <span
  m='50240'>interpreters</span> <span m='50750'>like</span> <span m='51030'>the sort</span>
  <span m='51450'>you</span> <span m='51550'>just</span> <span m='51740'>saw.</span>
  <span m='52570'>Metacircular</span> <span m='53300'>is</span> <span m='53470'>because</span>
  <span m='54670'>they</span> <span m='55010'>are</span> <span m='55100'>defined</span>
  <span m='55510'>in</span> <span m='55610'>terms</span> <span m='55870'>of</span>
  <span m='55910'>themselves</span> <span m='56340'>in</span> <span m='56430'>such</span>
  <span m='56640'>a</span> <span m='56690'>way</span> <span m='56860'>that</span>
  <span m='57000'>the</span> <span m='57080'>language</span> <span m='57460'>they</span>
  <span m='57590'>interpret</span> <span m='58830'>contains</span> <span m='59280'>itself.</span>
  </p><p><span m='61270'>Such</span> <span m='61570'>interpreters</span> <span m='62090'>are</span>
  <span m='62530'>a</span> <span m='62840'>convenient</span> <span m='63380'>medium</span>
  <span m='63860'>for</span> <span m='64080'>exploring</span> <span m='64860'>language</span>
  <span m='65040'>issues.</span> <span m='66800'>If</span> <span m='66900'>you</span>
  <span m='67020'>want</span> <span m='67130'>to</span> <span m='67250'>try</span>
  <span m='68460'>adding</span> <span m='68750'>a</span> <span m='68790'>new</span>
  <span m='68950'>feature,</span> <span m='70560'>it's</span> <span m='70730'>sort</span>
  <span m='70830'>of</span> <span m='70930'>a</span> <span m='71010'>snap,</span>
  <span m='71510'>it's</span> <span m='71860'>easy,</span> <span m='72310'>you</span>
  <span m='72790'>just</span> <span m='73140'>do</span> <span m='73290'>it</span>
  <span m='74190'>and</span> <span m='74350'>see</span> <span m='74490'>what</span>
  <span m='74570'>happens.</span> <span m='75490'>You</span> <span m='75590'>play</span>
  <span m='75780'>with that</span> <span m='76100'>language</span> <span m='76460'>for</span>
  <span m='76590'>a</span> <span m='76620'>while</span> <span m='76920'>you</span>
  <span m='77020'>say,</span> <span m='77250'>gee,</span> <span m='77500'>I'm</span>
  <span m='77710'>didn't</span> <span m='77835'>like</span> <span m='77960'>that,</span>
  <span m='78660'>you</span> <span m='78770'>throw</span> <span m='79020'>it</span>
  <span m='79070'>away.</span> <span m='81090'>Or</span> <span m='81260'>you</span>
  <span m='81350'>might</span> <span m='81580'>want</span> <span m='81860'>to</span>
  <span m='83050'>see</span> <span m='83380'>what</span> <span m='83780'>the</span>
  <span m='83870'>difference</span> <span m='84240'>is</span> <span m='84410'>if</span>
  <span m='84520'>you'd</span> <span m='84640'>make</span> <span m='84870'>a</span>
  <span m='85230'>slight</span> <span m='85720'>difference</span> <span m='86100'>in</span>
  <span m='86240'>the</span> <span m='86330'>binding</span> <span m='86710'>strategy,</span>
  <span m='88950'>or</span> <span m='89560'>some</span> <span m='90080'>more</span>
  <span m='90300'>complicated</span> <span m='90900'>things</span> <span m='91140'>that</span>
  <span m='91260'>might</span> <span m='91440'>occur.</span> </p><p><span m='93720'>In</span>
  <span m='93860'>fact,</span> <span m='94130'>these</span> <span m='94280'>metacircular
  interpreters</span> <span m='95370'>are</span> <span m='96190'>an</span> <span m='96450'>excellent</span>
  <span m='96810'>medium</span> <span m='97190'>for</span> <span m='97380'>people</span>
  <span m='98310'>exchanging</span> <span m='100990'>ideas</span> <span m='101420'>about</span>
  <span m='101680'>language</span> <span m='102000'>design,</span> <span m='104030'>because</span>
  <span m='104460'>they're</span> <span m='104560'>pretty</span> <span m='104820'>easy</span>
  <span m='105000'>to</span> <span m='105060'>understand,</span> <span m='106340'>and</span>
  <span m='106450'>they're</span> <span m='106580'>short,</span> <span m='106960'>and</span>
  <span m='107100'>compact,</span> <span m='107900'>and</span> <span m='108050'>simple.</span>
  <span m='109690'>If</span> <span m='109820'>I</span> <span m='109930'>have</span>
  <span m='110110'>some</span> <span m='110340'>idea</span> <span m='111030'>that</span>
  <span m='112320'>I</span> <span m='112480'>want</span> <span m='112770'>somebody</span>
  <span m='113000'>to</span> <span m='113060'>criticize</span> <span m='114360'>like</span>
  <span m='114520'>say,</span> <span m='116400'>Dan</span> <span m='116610'>Friedman</span>
  <span m='117530'>at</span> <span m='117740'>Indiana,</span> <span m='119070'>I'd</span>
  <span m='120390'>write</span> <span m='120540'>a little</span> <span m='120770'>metacircular
  interpreter</span> <span m='121740'>and</span> <span m='122570'>send</span> <span
  m='122860'>him</span> <span m='123030'>some</span> <span m='123160'>network</span>
  <span m='123460'>mail</span> <span m='124260'>with</span> <span m='124700'>this</span>
  <span m='124920'>interpreter</span> <span m='125185'>in it.</span> <span m='125450'>He</span>
  <span m='125640'>could</span> <span m='125820'>whip it</span> <span m='125910'>up</span>
  <span m='126050'>on</span> <span m='126120'>his</span> <span m='126340'>machine</span>
  <span m='126760'>and</span> <span m='127450'>play</span> <span m='127620'>with</span>
  <span m='127770'>it and</span> <span m='127900'>say,</span> <span m='128850'>that's</span>
  <span m='129380'>no</span> <span m='129539'>good.</span> <span m='131940'>And</span>
  <span m='132120'>then</span> <span m='132310'>send</span> <span m='132490'>it</span>
  <span m='132560'>back</span> <span m='132790'>to</span> <span m='132880'>me</span>
  <span m='132990'>and</span> <span m='133090'>say,</span> <span m='133170'>well,</span>
  <span m='133340'>why</span> <span m='133520'>don't you try</span> <span m='133800'>this</span>
  <span m='134000'>one,</span> <span m='134140'>it's</span> <span m='134270'>a</span>
  <span m='134320'>little</span> <span m='134470'>better.</span> </p><p><span m='136880'>So</span>
  <span m='137200'>I</span> <span m='137300'>want</span> <span m='137410'>to</span>
  <span m='137520'>show</span> <span m='137680'>you</span> <span m='137870'>some</span>
  <span m='138120'>of</span> <span m='138330'>that</span> <span m='138540'>technology.</span>
  <span m='140160'>See,</span> <span m='140370'>because,</span> <span m='140690'>really,</span>
  <span m='142250'>it's</span> <span m='142450'>the</span> <span m='142580'>essential,</span>
  <span m='143020'>simple</span> <span m='143370'>technology</span> <span m='144750'>for</span>
  <span m='144880'>getting</span> <span m='145140'>started</span> <span m='145580'>in</span>
  <span m='146620'>designing</span> <span m='147030'>your</span> <span m='147190'>own</span>
  <span m='147290'>languages</span> <span m='147760'>for</span> <span m='147850'>particular</span>
  <span m='148210'>purposes.</span> <span m='150790'>Let's</span> <span m='151020'>start</span>
  <span m='151340'>by</span> <span m='151480'>adding</span> <span m='152275'>a</span>
  <span m='152610'>very</span> <span m='152980'>simple</span> <span m='153290'>feature</span>
  <span m='153680'>to</span> <span m='153780'>a</span> <span m='153890'>Lisp.</span>
  <span m='160640'>Now,</span> <span m='160970'>one</span> <span m='161230'>thing</span>
  <span m='161380'>I</span> <span m='161440'>want</span> <span m='161560'>to</span>
  <span m='161690'>tell</span> <span m='161850'>you</span> <span m='161970'>about</span>
  <span m='162650'>is</span> <span m='162800'>features,</span> <span m='163510'>before</span>
  <span m='163820'>I</span> <span m='163890'>start.</span> </p><p><span m='169560'>There</span>
  <span m='169760'>are</span> <span m='169790'>many</span> <span m='170050'>languages</span>
  <span m='170750'>that</span> <span m='170860'>have</span> <span m='170980'>made</span>
  <span m='171180'>a</span> <span m='171220'>mess</span> <span m='171440'>of</span>
  <span m='171550'>themselves</span> <span m='173100'>by</span> <span m='173270'>adding</span>
  <span m='173570'>huge</span> <span m='173850'>numbers</span> <span m='174230'>of</span>
  <span m='174320'>features.</span> <span m='176620'>Computer</span> <span m='177340'>scientists</span>
  <span m='177760'>have</span> <span m='177920'>a</span> <span m='177980'>joke</span>
  <span m='179320'>about</span> <span m='179670'>bugs</span> <span m='179990'>that</span>
  <span m='180130'>transform</span> <span m='180620'>it to</span> <span m='180760'>features</span>
  <span m='181870'>all</span> <span m='182080'>the</span> <span m='182160'>time.</span>
  <span m='185030'>But</span> <span m='185230'>I</span> <span m='185340'>like</span>
  <span m='185530'>to</span> <span m='185850'>think</span> <span m='186030'>of</span>
  <span m='186110'>it</span> <span m='186170'>is</span> <span m='186370'>that</span>
  <span m='188950'>many</span> <span m='189250'>systems</span> <span m='189690'>suffer</span>
  <span m='189960'>from</span> <span m='190120'>what's</span> <span m='190260'>called</span>
  <span m='190470'>creeping</span> <span m='190790'>featurism.</span> </p><p><span
  m='192820'>Which</span> <span m='193040'>is</span> <span m='193390'>that</span>
  <span m='195180'>George</span> <span m='195620'>has</span> <span m='196210'>a</span>
  <span m='196400'>pet</span> <span m='196860'>feature</span> <span m='197130'>he'd</span>
  <span m='197300'>like</span> <span m='197590'>in</span> <span m='197680'>the</span>
  <span m='197740'>system,</span> <span m='198485'>so</span> <span m='198780'>he</span>
  <span m='199000'>adds</span> <span m='199210'>it.</span> <span m='200170'>And then</span>
  <span m='200420'>Harry</span> <span m='201130'>says,</span> <span m='202230'>gee,</span>
  <span m='202390'>this</span> <span m='202490'>system</span> <span m='202830'>is</span>
  <span m='202910'>no</span> <span m='203030'>longer</span> <span m='203330'>what</span>
  <span m='203480'>exactly</span> <span m='203880'>I</span> <span m='203980'>like,</span>
  <span m='204200'>so</span> <span m='204360'>I'm</span> <span m='204580'>going</span>
  <span m='204800'>to add</span> <span m='205090'>my</span> <span m='205270'>favorite</span>
  <span m='205450'>feature.</span> <span m='206640'>And</span> <span m='207010'>then</span>
  <span m='208440'>Jim</span> <span m='208750'>adds</span> <span m='209110'>his</span>
  <span m='209460'>favorite</span> <span m='209840'>feature.</span> <span m='210710'>And,</span>
  <span m='210970'>after</span> <span m='211380'>a while, the</span> <span m='211830'>thing</span>
  <span m='212050'>has</span> <span m='212220'>a</span> <span m='212260'>manual</span>
  <span m='213230'>500</span> <span m='213930'>pages</span> <span m='214270'>long</span>
  <span m='215280'>that</span> <span m='215440'>no</span> <span m='215560'>one</span>
  <span m='215750'>can</span> <span m='215890'>understand.</span> </p><p><span m='217790'>And</span>
  <span m='217900'>sometimes</span> <span m='218310'>it's</span> <span m='218460'>the</span>
  <span m='218520'>same</span> <span m='218840'>person</span> <span m='219490'>who</span>
  <span m='220040'>writes</span> <span m='220360'>all</span> <span m='220470'>of</span>
  <span m='220590'>these</span> <span m='220780'>features</span> <span m='221220'>and</span>
  <span m='221390'>produces</span> <span m='221700'>this</span> <span m='221870'>terribly</span>
  <span m='222260'>complicated</span> <span m='222830'>thing.</span> <span m='224830'>In</span>
  <span m='224920'>some</span> <span m='225130'>cases,</span> <span m='225400'>like</span>
  <span m='225590'>editors,</span> <span m='227420'>it's</span> <span m='227580'>sort</span>
  <span m='227720'>of</span> <span m='227810'>reasonable</span> <span m='228150'>to</span>
  <span m='228250'>have</span> <span m='228360'>lots</span> <span m='228610'>of</span>
  <span m='228660'>features,</span> <span m='230980'>because</span> <span m='231320'>there</span>
  <span m='231430'>are</span> <span m='231450'>a</span> <span m='231530'>lot</span>
  <span m='231610'>of</span> <span m='231690'>things</span> <span m='231860'>you</span>
  <span m='231940'>want</span> <span m='232120'>to</span> <span m='232310'>be</span>
  <span m='232600'>able to</span> <span m='232700'>do  and many</span> <span m='232900'>of
  them </span> <span m='233030'>arbitrary.</span> <span m='235730'>But</span> <span
  m='236065'>in</span> <span m='236400'>computer</span> <span m='236710'>languages,</span>
  <span m='237930'>I</span> <span m='238030'>think</span> <span m='238180'>it's</span>
  <span m='238340'>a</span> <span m='238390'>disaster</span> <span m='239786'>to</span>
  <span m='240210'>have</span> <span m='240440'>too</span> <span m='240570'>much</span>
  <span m='240760'>stuff</span> <span m='241030'>in</span> <span m='241110'>them.</span>
  </p><p><span m='244110'>The</span> <span m='244410'>other</span> <span m='245060'>alternative</span>
  <span m='245570'>you</span> <span m='245680'>get</span> <span m='245830'>into is</span>
  <span m='246110'>something</span> <span m='246420'>called</span> <span m='246860'>feeping</span>
  <span m='247280'>creaturism,</span> <span m='249610'>which</span> <span m='249780'>is</span>
  <span m='249880'>where</span> <span m='250020'>you</span> <span m='250270'>have</span>
  <span m='250760'>a</span> <span m='250870'>box</span> <span m='251820'>which</span>
  <span m='252060'>has</span> <span m='252300'>a</span> <span m='252640'>display,</span>
  <span m='253360'>a</span> <span m='253700'>fancy</span> <span m='254070'>display,</span>
  <span m='254660'>and</span> <span m='254750'>a</span> <span m='254790'>mouse,</span>
  <span m='255940'>and</span> <span m='256760'>there</span> <span m='256980'>is</span>
  <span m='257269'>all</span> <span m='257370'>sorts</span> <span m='257640'>of</span>
  <span m='257760'>complexity</span> <span m='258290'>associated</span> <span m='258779'>with</span>
  <span m='258899'>all</span> <span m='259040'>this</span> <span m='259190'>fancy</span>
  <span m='259540'>IO.</span> <span m='261010'>And</span> <span m='261579'>your</span>
  <span m='261740'>computer</span> <span m='262050'>language</span> <span m='262400'>becomes</span>
  <span m='262930'>a</span> <span m='263480'>dismal,</span> <span m='263890'>little,</span>
  <span m='264140'>tiny</span> <span m='264430'>thing</span> <span m='264610'>that</span>
  <span m='264770'>barely</span> <span m='265090'>works</span> <span m='265440'>because</span>
  <span m='265710'>of</span> <span m='265830'>all</span> <span m='265960'>the</span>
  <span m='266090'>swapping,</span> <span m='266430'>and</span> <span m='266770'>disk</span>
  <span m='267070'>twitching,</span> <span m='267430'>and</span> <span m='267520'>so</span>
  <span m='267690'>on,</span> <span m='268100'>caused</span> <span m='268330'>by</span>
  <span m='268450'>your</span> <span m='268560'>Windows</span> <span m='268930'>system.</span>
  </p><p><span m='270080'>And</span> <span m='270230'>every</span> <span m='270420'>time</span>
  <span m='270690'>you</span> <span m='270890'>go</span> <span m='271050'>near</span>
  <span m='271260'>the</span> <span m='271360'>computer,</span> <span m='271840'>the</span>
  <span m='272040'>mouse</span> <span m='272320'>process</span> <span m='272650'>wakes</span>
  <span m='272930'>up</span> <span m='273070'>and</span> <span m='273160'>says,</span>
  <span m='273830'>gee</span> <span m='274850'>do you have</span> <span m='274990'>something</span>
  <span m='275270'>for</span> <span m='275380'>me</span> <span m='275530'>to</span>
  <span m='275610'>do,</span> <span m='275910'>and</span> <span m='276160'>then it</span>
  <span m='276400'>goes</span> <span m='276550'>back</span> <span m='276750'>to</span>
  <span m='276830'>sleep.</span> <span m='277440'>And</span> <span m='277610'>if</span>
  <span m='277690'>you</span> <span m='277920'>accidentally</span> <span m='278320'>push</span>
  <span m='278550'>mouse</span> <span m='278990'>with you</span> <span m='279360'>elbow,</span>
  <span m='279900'>a</span> <span m='279940'>big</span> <span m='280210'>puff</span>
  <span m='280380'>of</span> <span m='280420'>smoke</span> <span m='280670'>comes</span>
  <span m='280860'>out</span> <span m='280960'>of</span> <span m='281040'>your</span>
  <span m='281150'>computer</span> <span m='281600'>and</span> <span m='281700'>things</span>
  <span m='281900'>like</span> <span m='282070'>that.</span> <span m='282940'>So</span>
  <span m='283700'>two</span> <span m='284000'>ways</span> <span m='284290'>to</span>
  <span m='284400'>disastrously</span> <span m='285530'>destroy</span> <span m='285950'>a</span>
  <span m='286030'>system</span> <span m='286370'>by</span> <span m='286500'>adding</span>
  <span m='286750'>features.</span> </p><p><span m='287500'>But</span> <span m='287730'>try</span>
  <span m='288200'>right</span> <span m='288370'>now</span> <span m='288510'>to</span>
  <span m='288630'>add a</span> <span m='288750'>little,</span> <span m='288980'>simple</span>
  <span m='289330'>feature.</span> <span m='292300'>This</span> <span m='292800'>actually</span>
  <span m='293090'>is</span> <span m='293150'>a</span> <span m='293210'>good</span>
  <span m='293410'>one,</span> <span m='293900'>and</span> <span m='294060'>in</span>
  <span m='294120'>fact,</span> <span m='294350'>real</span> <span m='295170'>Lisps</span>
  <span m='295780'>have</span> <span m='296000'>it.</span> <span m='297250'>As</span>
  <span m='297500'>you've</span> <span m='297680'>seen,</span> <span m='299280'>there</span>
  <span m='299550'>are</span> <span m='299600'>procedures</span> <span m='300250'>like</span>
  <span m='301900'>plus</span> <span m='302260'>and</span> <span m='302550'>times</span>
  <span m='303420'>that</span> <span m='303600'>take</span> <span m='303820'>any</span>
  <span m='303950'>number</span> <span m='304190'>of</span> <span m='304280'>arguments.</span>
  <span m='305430'>So</span> <span m='305600'>we</span> <span m='305710'>can</span>
  <span m='305850'>write</span> <span m='306120'>things</span> <span m='306640'>like</span>
  <span m='306830'>the</span> <span m='306920'>sum</span> <span m='307590'>of</span>
  <span m='307780'>the</span> <span m='307880'>product</span> <span m='308830'>of</span>
  <span m='309080'>a</span> <span m='309440'>and</span> <span m='309710'>x</span>
  <span m='310005'>and</span> <span m='310300'>x,</span> <span m='311800'>and</span>
  <span m='312160'>the</span> <span m='312450'>product</span> <span m='314070'>of</span>
  <span m='314270'>b</span> <span m='314570'>and</span> <span m='314700'>x</span>
  <span m='316230'>and</span> <span m='316420'>c.</span> </p><p><span m='317540'>As</span>
  <span m='317750'>you</span> <span m='317830'>can</span> <span m='317950'>see</span>
  <span m='318190'>here,</span> <span m='318900'>addition</span> <span m='319430'>takes</span>
  <span m='320040'>three</span> <span m='320330'>arguments</span> <span m='320860'>or</span>
  <span m='320970'>two</span> <span m='321210'>arguments,</span> <span m='322320'>multiplication</span>
  <span m='322980'>takes</span> <span m='323240'>two</span> <span m='323420'>arguments</span>
  <span m='323820'>or</span> <span m='323960'>three</span> <span m='324230'>arguments,</span>
  <span m='325080'>taking</span> <span m='325800'>numbers</span> <span m='326250'>of</span>
  <span m='326370'>arguments</span> <span m='326820'>all</span> <span m='326940'>of</span>
  <span m='327070'>which are</span> <span m='327130'>to</span> <span m='327290'>be</span>
  <span m='327390'>treated</span> <span m='327750'>in</span> <span m='327810'>the</span>
  <span m='327870'>same</span> <span m='328170'>way.</span> <span m='330000'>This</span>
  <span m='330360'>is</span> <span m='331130'>a</span> <span m='331270'>valuable</span>
  <span m='331780'>thing,</span> <span m='332300'>indefinite</span> <span m='332900'>numbers</span>
  <span m='333290'>of</span> <span m='333400'>arguments.</span> </p><p><span m='334960'>Yet</span>
  <span m='335220'>the</span> <span m='335310'>particular</span> <span m='335810'>Lisp</span>
  <span m='336180'>system</span> <span m='337470'>that</span> <span m='337630'>I</span>
  <span m='337790'>showed</span> <span m='338110'>you</span> <span m='339420'>is</span>
  <span m='339530'>one</span> <span m='339800'>where</span> <span m='340460'>the</span>
  <span m='340620'>numbers</span> <span m='340920'>of</span> <span m='341010'>arguments</span>
  <span m='341265'>is</span> <span m='341520'>fixed,</span> <span m='342720'>because</span>
  <span m='342980'>I had to</span> <span m='343060'>match</span> <span m='343600'>the</span>
  <span m='343800'>arguments</span> <span m='344160'>against</span> <span m='344370'>the</span>
  <span m='344450'>formal</span> <span m='344720'>parameters</span> <span m='345640'>in</span>
  <span m='345830'>the</span> <span m='345910'>binder,</span> <span m='347040'>where</span>
  <span m='347200'>there's</span> <span m='347380'>a</span> <span m='347450'>pairup.</span>
  <span m='350810'>Well,</span> <span m='351080'>I'd</span> <span m='351190'>like</span>
  <span m='351460'>to</span> <span m='351520'>be</span> <span m='351660'>able</span>
  <span m='351800'>to</span> <span m='351900'>define</span> <span m='352540'>new</span>
  <span m='352710'>procedures</span> <span m='353220'>like</span> <span m='353460'>this</span>
  <span m='354970'>that</span> <span m='355180'>can</span> <span m='355320'>have</span>
  <span m='356230'>any</span> <span m='356430'>number</span> <span m='356680'>of</span>
  <span m='356760'>arguments.</span> <span m='358590'>Well</span> <span m='358920'>there's</span>
  <span m='359030'>several</span> <span m='359310'>parts</span> <span m='359650'>to</span>
  <span m='359710'>this</span> <span m='359920'>problem.</span> <span m='361150'>The</span>
  <span m='361600'>first</span> <span m='361880'>part</span> <span m='362330'>is</span>
  <span m='362490'>coming</span> <span m='362720'>up</span> <span m='362980'>with</span>
  <span m='363140'>the</span> <span m='363210'>syntactic</span> <span m='363870'>specification,</span>
  <span m='365630'>some</span> <span m='365940'>way</span> <span m='366160'>of</span>
  <span m='366640'>notating</span> <span m='368810'>the</span> <span m='370120'>additional</span>
  <span m='370620'>arguments,</span> <span m='372250'>of</span> <span m='372360'>which</span>
  <span m='372470'>you</span> <span m='372560'>don't</span> <span m='372650'>know</span>
  <span m='372740'>how</span> <span m='372900'>many</span> <span m='373070'>there</span>
  <span m='373270'>are.</span> <span m='375480'>And</span> <span m='375630'>then</span>
  <span m='375780'>there's</span> <span m='376020'>the</span> <span m='376120'>other</span>
  <span m='376290'>thing,</span> <span m='377180'>which</span> <span m='377440'>is</span>
  <span m='377560'>once</span> <span m='377830'>we've</span> <span m='377980'>notated</span>
  <span m='378480'>it,</span> <span m='379070'>how</span> <span m='379260'>are</span>
  <span m='379480'>we going to</span> <span m='379570'>interpret</span> <span m='379990'>that</span>
  <span m='380180'>notation</span> <span m='381720'>so</span> <span m='381940'>as</span>
  <span m='382010'>to</span> <span m='382120'>do</span> <span m='382280'>the</span>
  <span m='382390'>right</span> <span m='382700'>thing,</span> <span m='383930'>whatever</span>
  <span m='384300'>the</span> <span m='384540'>right</span> <span m='384850'>thing</span>
  <span m='385080'>is?</span> </p><p><span m='386980'>So</span> <span m='387310'>let's</span>
  <span m='387490'>consider</span> <span m='387640'>an</span> <span m='387740'>example</span>
  <span m='388230'>of</span> <span m='388320'>a</span> <span m='388370'>sort</span>
  <span m='388600'>of</span> <span m='388680'>thing</span> <span m='388890'>we</span>
  <span m='389010'>might</span> <span m='389230'>want</span> <span m='389320'>to</span>
  <span m='389420'>be</span> <span m='389540'>able</span> <span m='389720'>to</span>
  <span m='389830'>do.</span> <span m='393070'>So</span> <span m='393360'>an</span>
  <span m='393470'>example</span> <span m='393950'>might</span> <span m='394240'>be,</span>
  <span m='395430'>that</span> <span m='395670'>I</span> <span m='395800'>might want</span>
  <span m='395940'>to</span> <span m='395980'>be</span> <span m='396080'>able</span>
  <span m='396290'>to</span> <span m='396380'>define</span> <span m='396640'>a</span>
  <span m='396690'>procedure</span> <span m='398030'>which</span> <span m='398230'>is</span>
  <span m='398350'>a</span> <span m='398400'>procedure</span> <span m='399330'>of</span>
  <span m='399630'>one</span> <span m='399980'>required</span> <span m='400490'>argument</span>
  <span m='400870'>x</span> <span m='403330'>and</span> <span m='404500'>a</span>
  <span m='404580'>bunch</span> <span m='404860'>of</span> <span m='404980'>arguments,</span>
  <span m='405350'>I</span> <span m='405440'>don't</span> <span m='405530'>know</span>
  <span m='405620'>how</span> <span m='405820'>many</span> <span m='406000'>there</span>
  <span m='406160'>are,</span> <span m='406370'>called</span> <span m='406630'>y.</span>
  <span m='409090'>So</span> <span m='409250'>x</span> <span m='409480'>is</span>
  <span m='409610'>required,</span> <span m='415840'>and</span> <span m='416220'>there</span>
  <span m='416410'>are</span> <span m='416540'>many</span> <span m='416820'>y's,</span>
  <span m='419630'>many</span> <span m='420400'>argument--</span> <span m='424710'>y</span>
  <span m='424960'>will</span> <span m='425100'>be</span> <span m='425210'>the</span>
  <span m='425300'>list</span> <span m='425580'>of</span> <span m='425700'>them.</span>
  </p><p><span m='434480'>Now,</span> <span m='435360'>with</span> <span m='435510'>such</span>
  <span m='435740'>a</span> <span m='435810'>thing,</span> <span m='436050'>we</span>
  <span m='436190'>might</span> <span m='436430'>be</span> <span m='436500'>able</span>
  <span m='436630'>to</span> <span m='436700'>say</span> <span m='436950'>something</span>
  <span m='437370'>like,</span> <span m='439140'>map--</span> <span m='440720'>I'm</span>
  <span m='440830'>going to do</span> <span m='440980'>something to</span> <span m='441280'>every</span>
  <span m='441500'>one--</span> <span m='442590'>of</span> <span m='442800'>that</span>
  <span m='443080'>procedure</span> <span m='444310'>of</span> <span m='444510'>one</span>
  <span m='444710'>argument</span> <span m='445150'>u,</span> <span m='447060'>which</span>
  <span m='448270'>multiplies</span> <span m='449750'>x</span> <span m='450055'>by</span>
  <span m='450360'>u,</span> <span m='453260'>and</span> <span m='453350'>we'll</span>
  <span m='453560'>apply</span> <span m='453820'>that</span> <span m='454000'>to</span>
  <span m='454120'>y.</span> <span m='456890'>I've</span> <span m='457020'>used</span>
  <span m='457220'>a</span> <span m='457350'>dot</span> <span m='457650'>here</span>
  <span m='458600'>to</span> <span m='458720'>indicate</span> <span m='459570'>that</span>
  <span m='460350'>the</span> <span m='460440'>thing</span> <span m='460710'>after</span>
  <span m='461020'>this</span> <span m='462270'>is</span> <span m='462410'>a</span>
  <span m='462530'>list</span> <span m='462830'>of</span> <span m='462960'>all</span>
  <span m='463170'>the</span> <span m='463270'>rest</span> <span m='463510'>of</span>
  <span m='463590'>the</span> <span m='463700'>arguments.</span> <span m='466300'>I'm</span>
  <span m='466400'>making</span> <span m='466610'>a</span> <span m='466750'>syntactic</span>
  <span m='467340'>specification.</span> </p><p><span m='473320'>Now,</span> <span
  m='473490'>what</span> <span m='473630'>this</span> <span m='473800'>depends</span>
  <span m='474190'>upon,</span> <span m='475540'>the</span> <span m='475920'>reason</span>
  <span m='476220'>why</span> <span m='476420'>this</span> <span m='476580'>is</span>
  <span m='476670'>sort</span> <span m='476770'>of</span> <span m='476870'>a</span>
  <span m='476980'>reasonable</span> <span m='477440'>thing</span> <span m='477650'>to</span>
  <span m='477740'>do,</span> <span m='479830'>is</span> <span m='480010'>because</span>
  <span m='480390'>this</span> <span m='480530'>happens</span> <span m='480840'>to</span>
  <span m='480940'>be</span> <span m='481260'>a</span> <span m='481440'>syntax</span>
  <span m='482080'>that's</span> <span m='482270'>used</span> <span m='482610'>in</span>
  <span m='482730'>the</span> <span m='482960'>Lisp</span> <span m='483230'>reader</span>
  <span m='484440'>for</span> <span m='484640'>representing</span> <span m='486500'>conses.</span>
  <span m='488631'>We've</span> <span m='489120'>never</span> <span m='489510'>introduced</span>
  <span m='489860'>that</span> <span m='490110'>before.</span> <span m='491080'>You</span>
  <span m='491170'>may</span> <span m='491290'>have</span> <span m='491420'>seen</span>
  <span m='491700'>when</span> <span m='491850'>playing</span> <span m='492170'>with</span>
  <span m='492250'>the</span> <span m='492340'>system</span> <span m='492820'>that</span>
  <span m='493080'>if</span> <span m='493270'>you</span> <span m='493680'>cons</span>
  <span m='493800'>two things</span> <span m='493980'>together,</span> <span m='494220'>you</span>
  <span m='494400'>get</span> <span m='494710'>the</span> <span m='495040'>first,</span>
  <span m='495570'>space,</span> <span m='496140'>dot,</span> <span m='496450'>the</span>
  <span m='496740'>second,</span> <span m='497670'>space--</span> <span m='499800'>the</span>
  <span m='499940'>first,</span> <span m='500660'>space,</span> <span m='501220'>dot,</span>
  <span m='501680'>space,</span> <span m='502160'>the</span> <span m='502440'>second</span>
  <span m='503140'>with</span> <span m='503330'>parentheses</span> <span m='503880'>around</span>
  <span m='504150'>the</span> <span m='504200'>whole</span> <span m='504390'>thing.</span>
  </p><p><span m='506980'>So</span> <span m='507180'>that,</span> <span m='507410'>for</span>
  <span m='507600'>example,</span> <span m='509030'>this</span> <span m='509280'>x</span>
  <span m='509560'>dot</span> <span m='509850'>y</span> <span m='512860'>corresponds</span>
  <span m='513549'>to</span> <span m='513760'>a</span> <span m='514669'>pair,</span>
  <span m='516350'>which</span> <span m='516590'>has</span> <span m='516700'>got</span>
  <span m='516870'>an</span> <span m='517000'>x</span> <span m='517200'>in</span>
  <span m='517320'>it</span> <span m='518490'>and</span> <span m='518679'>a</span>
  <span m='519030'>y</span> <span m='519419'>in</span> <span m='519809'>it.</span>
  <span m='521870'>The</span> <span m='522020'>other</span> <span m='522270'>notations</span>
  <span m='522850'>that</span> <span m='522980'>you've</span> <span m='523120'>seen</span>
  <span m='523390'>so</span> <span m='523730'>far</span> <span m='524960'>are</span>
  <span m='525140'>things</span> <span m='525520'>like</span> <span m='527010'>a</span>
  <span m='527150'>procedure</span> <span m='530490'>of</span> <span m='530830'>arguments</span>
  <span m='531280'>x</span> <span m='531620'>and</span> <span m='532000'>y</span>
  <span m='532740'>and</span> <span m='533020'>z</span> <span m='533950'>which</span>
  <span m='534370'>do</span> <span m='534590'>things,</span> <span m='535720'>and</span>
  <span m='536250'>that</span> <span m='537050'>looks</span> <span m='537300'>like--</span>
  <span m='542000'>Just</span> <span m='542150'>looking</span> <span m='542420'>at</span>
  <span m='542500'>the</span> <span m='542570'>bound</span> <span m='543070'>variable</span>
  <span m='543210'>list,</span> <span m='543800'>it</span> <span m='544460'>looks</span>
  <span m='544660'>like</span> <span m='544910'>this,</span> <span m='550000'>x,</span>
  <span m='552970'>y,</span> <span m='555420'>z,</span> <span m='555960'>and</span>
  <span m='556300'>the</span> <span m='556770'>empty</span> <span m='557030'>thing.</span>
  </p><p><span m='558280'>If</span> <span m='558530'>I</span> <span m='558650'>have</span>
  <span m='558900'>a</span> <span m='558980'>list</span> <span m='559270'>of</span>
  <span m='559370'>arguments</span> <span m='559770'>I</span> <span m='559840'>wish</span>
  <span m='560060'>to</span> <span m='560160'>match</span> <span m='560500'>this</span>
  <span m='560670'>against,</span> <span m='562590'>supposing,</span> <span m='563030'>I</span>
  <span m='563090'>have</span> <span m='563180'>a</span> <span m='563270'>list</span>
  <span m='563500'>of</span> <span m='563580'>arguments</span> <span m='564390'>one,</span>
  <span m='564810'>two,</span> <span m='565020'>three,</span> <span m='565920'>I</span>
  <span m='566110'>want</span> <span m='566300'>to</span> <span m='566370'>match</span>
  <span m='566650'>these</span> <span m='566860'>against.</span> <span m='568800'>So</span>
  <span m='568980'>I</span> <span m='569080'>might</span> <span m='569300'>have</span>
  <span m='569500'>here</span> <span m='570860'>a</span> <span m='570970'>list</span>
  <span m='576130'>of</span> <span m='576300'>three</span> <span m='576570'>things,</span>
  <span m='582550'>one,</span> <span m='584230'>two,</span> <span m='585980'>three.</span>
  <span m='588990'>And</span> <span m='589250'>I</span> <span m='589300'>want</span>
  <span m='589830'>to</span> <span m='590090'>match</span> <span m='591050'>x,</span>
  <span m='591290'>y,</span> <span m='591590'>z</span> <span m='591980'>against</span>
  <span m='592270'>one,</span> <span m='592480'>two,</span> <span m='592630'>three.</span>
  </p><p><span m='594220'>Well,</span> <span m='594430'>it's</span> <span m='594560'>clear</span>
  <span m='594980'>that</span> <span m='595150'>the</span> <span m='595320'>one</span>
  <span m='595570'>matches</span> <span m='595950'>the</span> <span m='596110'>x,</span>
  <span m='596340'>because</span> <span m='596600'>I</span> <span m='596680'>can</span>
  <span m='596830'>just sort of</span> <span m='597030'>follow</span> <span m='597290'>the</span>
  <span m='597380'>structure,</span> <span m='598860'>and</span> <span m='599090'>the</span>
  <span m='599330'>two</span> <span m='599730'>matches</span> <span m='600130'>the</span>
  <span m='601040'>y,</span> <span m='602530'>and</span> <span m='602770'>the</span>
  <span m='602880'>three</span> <span m='603170'>matches</span> <span m='603590'>the</span>
  <span m='603720'>z.</span> <span m='605480'>But</span> <span m='605770'>now,</span>
  <span m='605940'>supposing</span> <span m='606440'>I</span> <span m='606500'>were</span>
  <span m='606580'>to</span> <span m='606660'>compare</span> <span m='607370'>this</span>
  <span m='608310'>x</span> <span m='608700'>dot</span> <span m='608980'>y--</span>
  <span m='609560'>this</span> <span m='609780'>is</span> <span m='610770'>x</span>
  <span m='611070'>dot</span> <span m='611370'>y--</span> <span m='612460'>supposing</span>
  <span m='612750'>I</span> <span m='612940'>compare</span> <span m='613290'>that</span>
  <span m='614690'>with</span> <span m='614920'>a</span> <span m='614970'>list</span>
  <span m='615230'>of</span> <span m='615360'>three</span> <span m='615590'>arguments,</span>
  <span m='616010'>one,</span> <span m='616270'>two,</span> <span m='616430'>three.</span>
  <span m='618510'>Let's</span> <span m='619200'>look</span> <span m='619310'>at</span>
  <span m='619430'>that</span> <span m='619600'>again.</span> <span m='628000'>One,</span>
  <span m='629300'>two,</span> <span m='629790'>three--</span> </p><p><span m='630930'>Well,</span>
  <span m='631710'>I</span> <span m='631790'>can</span> <span m='631890'>walk</span>
  <span m='632180'>along</span> <span m='632510'>here</span> <span m='633010'>and</span>
  <span m='633180'>say,</span> <span m='633380'>oh</span> <span m='633520'>yes,</span>
  <span m='634260'>x</span> <span m='634530'>matches</span> <span m='634890'>the</span>
  <span m='634970'>one,</span> <span m='638640'>the</span> <span m='638780'>y</span>
  <span m='639320'>matches</span> <span m='639820'>the</span> <span m='639900'>list,</span>
  <span m='640680'>which</span> <span m='640900'>is</span> <span m='641040'>two</span>
  <span m='641270'>and</span> <span m='641430'>three.</span> <span m='643740'>So</span>
  <span m='644350'>the</span> <span m='644640'>notation</span> <span m='645370'>I'm</span>
  <span m='645550'>choosing</span> <span m='645980'>here</span> <span m='646440'>is</span>
  <span m='646600'>one</span> <span m='646800'>that's</span> <span m='646920'>very</span>
  <span m='647150'>natural</span> <span m='649270'>for</span> <span m='649420'>Lisp</span>
  <span m='649770'>system.</span> <span m='652660'>But</span> <span m='652800'>I'm</span>
  <span m='652910'>going</span> <span m='652990'>to</span> <span m='653070'>choose</span>
  <span m='653410'>this</span> <span m='653560'>as a</span> <span m='653610'>notation</span>
  <span m='654140'>for</span> <span m='654270'>representing</span> <span m='654790'>a</span>
  <span m='654860'>bunch</span> <span m='655150'>of</span> <span m='655260'>arguments.</span>
  </p><p><span m='658290'>Now,</span> <span m='658440'>there's</span> <span m='658620'>an</span>
  <span m='658680'>alternative</span> <span m='659300'>possibility.</span> <span m='660770'>If</span>
  <span m='660900'>I</span> <span m='660990'>don't</span> <span m='661210'>want</span>
  <span m='661440'>to</span> <span m='661540'>take</span> <span m='661750'>one</span>
  <span m='661960'>special</span> <span m='662430'>out, or</span> <span m='662900'>two</span>
  <span m='663210'>special</span> <span m='663560'>ones</span> <span m='663850'>out</span>
  <span m='664040'>or</span> <span m='664110'>something</span> <span m='664420'>like</span>
  <span m='664640'>that,</span> <span m='666216'>if</span> <span m='666600'>I</span>
  <span m='666700'>don't</span> <span m='666880'>want</span> <span m='667030'>to</span>
  <span m='667080'>do</span> <span m='667300'>that,</span> <span m='668450'>if</span>
  <span m='668810'>I</span> <span m='669010'>want</span> <span m='669220'>to</span>
  <span m='669590'>talk</span> <span m='670090'>about</span> <span m='670540'>just</span>
  <span m='670760'>the</span> <span m='670840'>list</span> <span m='671030'>of</span>
  <span m='671130'>all</span> <span m='671270'>the</span> <span m='671420'>arguments</span>
  <span m='671790'>like</span> <span m='671970'>in</span> <span m='672040'>addition,</span>
  <span m='673880'>well</span> <span m='674200'>then</span> <span m='674360'>the</span>
  <span m='674630'>argument</span> <span m='675120'>list</span> <span m='676950'>I'm</span>
  <span m='677130'>going to</span> <span m='677240'>choose</span> <span m='677420'>to</span>
  <span m='677600'>be</span> <span m='678230'>that</span> <span m='678560'>procedure</span>
  <span m='679170'>of</span> <span m='679520'>all</span> <span m='679760'>the</span>
  <span m='679870'>arguments</span> <span m='680370'>x</span> <span m='681870'>which</span>
  <span m='682240'>does</span> <span m='682530'>something</span> <span m='682890'>with</span>
  <span m='683010'>x.</span> <span m='685140'>And</span> <span m='685300'>which,</span>
  <span m='685570'>for</span> <span m='685730'>example,</span> <span m='686890'>if</span>
  <span m='686960'>I</span> <span m='687040'>take</span> <span m='687240'>the</span>
  <span m='687320'>procedure,</span> <span m='689030'>which</span> <span m='689190'>takes</span>
  <span m='689420'>all</span> <span m='689610'>the</span> <span m='689710'>arguments</span>
  <span m='690115'>x</span> <span m='691180'>and</span> <span m='691350'>returned</span>
  <span m='691850'>the</span> <span m='691930'>list</span> <span m='692220'>of</span>
  <span m='692340'>them,</span> <span m='695040'>that's</span> <span m='695280'>list.</span>
  <span m='697710'>That's</span> <span m='697890'>the</span> <span m='697970'>procedure</span>
  <span m='698330'>list.</span> </p><p><span m='705850'>How</span> <span m='706050'>does</span>
  <span m='706170'>this</span> <span m='706370'>work?</span> <span m='706840'>Well,</span>
  <span m='707070'>indeed</span> <span m='707560'>what</span> <span m='707810'>I</span>
  <span m='708020'>had</span> <span m='708240'>as</span> <span m='708360'>the</span>
  <span m='708480'>bound</span> <span m='708780'>variable</span> <span m='709140'>list</span>
  <span m='709350'>in</span> <span m='709480'>this</span> <span m='709610'>case,</span>
  <span m='710670'>whatever</span> <span m='711090'>it</span> <span m='711150'>is,</span>
  <span m='711640'>is</span> <span m='711840'>being</span> <span m='712090'>matched</span>
  <span m='712450'>against</span> <span m='712750'>a</span> <span m='712790'>list</span>
  <span m='713010'>of</span> <span m='713100'>arguments.</span> <span m='715140'>This</span>
  <span m='715530'>symbol</span> <span m='715950'>now</span> <span m='716270'>is</span>
  <span m='716430'>all</span> <span m='716570'>of</span> <span m='716720'>the</span>
  <span m='716850'>arguments.</span> <span m='721490'>And</span> <span m='721690'>so</span>
  <span m='721820'>this</span> <span m='722000'>is</span> <span m='722090'>the</span>
  <span m='722440'>choice</span> <span m='722840'>I'm</span> <span m='722960'>making</span>
  <span m='723260'>for</span> <span m='723330'>a</span> <span m='723400'>particular</span>
  <span m='723830'>syntactic</span> <span m='724390'>specification,</span> <span m='725620'>for</span>
  <span m='725940'>the</span> <span m='726340'>description</span> <span m='726850'>of</span>
  <span m='726930'>procedures</span> <span m='728060'>which</span> <span m='728240'>take</span>
  <span m='729080'>indefinite</span> <span m='729600'>numbers</span> <span m='729900'>of</span>
  <span m='730010'>arguments.</span> </p><p><span m='733190'>There</span> <span m='733680'>are</span>
  <span m='733750'>two</span> <span m='733930'>cases</span> <span m='734330'>of</span>
  <span m='734490'>it,</span> <span m='735460'>this</span> <span m='735680'>one</span>
  <span m='735890'>and</span> <span m='736040'>this</span> <span m='736190'>one.</span>
  <span m='738420'>When</span> <span m='738560'>you</span> <span m='738710'>make</span>
  <span m='738960'>syntactic</span> <span m='739370'>specifications,</span> <span
  m='740390'>it's</span> <span m='740610'>important</span> <span m='741330'>that</span>
  <span m='741610'>it's</span> <span m='741840'>unambiguous,</span> <span m='743610'>that</span>
  <span m='744030'>neither</span> <span m='744570'>of</span> <span m='744680'>these</span>
  <span m='746080'>can</span> <span m='746290'>be</span> <span m='746410'>confused</span>
  <span m='746980'>with</span> <span m='748080'>a</span> <span m='748200'>representation</span>
  <span m='748860'>we</span> <span m='749000'>already</span> <span m='749420'>have,</span>
  <span m='750570'>this</span> <span m='750850'>one.</span> <span m='753610'>I</span>
  <span m='753730'>can</span> <span m='753850'>always</span> <span m='754220'>tell</span>
  <span m='755080'>whether</span> <span m='755430'>I</span> <span m='755650'>have</span>
  <span m='756600'>a</span> <span m='756750'>fixed</span> <span m='757140'>number</span>
  <span m='758200'>of</span> <span m='758350'>explicitly</span> <span m='758900'>named</span>
  <span m='759220'>arguments</span> <span m='760370'>made</span> <span m='760580'>by</span>
  <span m='760680'>these</span> <span m='760900'>formal</span> <span m='761180'>parameters,</span>
  <span m='762340'>or</span> <span m='763350'>a</span> <span m='763510'>fixed</span>
  <span m='763840'>number</span> <span m='764180'>of</span> <span m='764350'>named</span>
  <span m='764700'>formal</span> <span m='764970'>parameters</span> <span m='765470'>followed</span>
  <span m='765800'>by</span> <span m='766310'>a</span> <span m='766430'>thing</span>
  <span m='766620'>which</span> <span m='766770'>picks</span> <span m='766950'>up</span>
  <span m='767070'>all</span> <span m='767200'>the</span> <span m='767270'>rest</span>
  <span m='767520'>of</span> <span m='767620'>them,</span> <span m='769240'>or</span>
  <span m='769980'>a</span> <span m='771530'>list</span> <span m='771780'>of</span>
  <span m='771910'>all</span> <span m='772830'>the</span> <span m='772940'>arguments</span>
  <span m='773800'>which will</span> <span m='773920'>be</span> <span m='774080'>matched</span>
  <span m='774340'>against</span> <span m='774620'>this</span> <span m='774850'>particular</span>
  <span m='775240'>formal</span> <span m='775540'>parameter</span> <span m='775930'>called</span>
  <span m='776180'>x,</span> <span m='777010'>because</span> <span m='777170'>these</span>
  <span m='777290'>are</span> <span m='777630'>syntactically</span> <span m='778110'>distinguishable.</span>
  </p><p><span m='782250'>Many</span> <span m='782560'>languages</span> <span m='782970'>make</span>
  <span m='783180'>terrible</span> <span m='783580'>errors</span> <span m='783970'>in</span>
  <span m='784050'>that</span> <span m='784300'>form</span> <span m='785120'>where</span>
  <span m='785960'>whole</span> <span m='786340'>segments</span> <span m='786810'>of</span>
  <span m='786900'>interpretation</span> <span m='787470'>are</span> <span m='787560'>cut</span>
  <span m='787750'>off,</span> <span m='788340'>because</span> <span m='789230'>there</span>
  <span m='789410'>are</span> <span m='790420'>syntactic</span> <span m='791100'>ambiguities</span>
  <span m='792810'>in</span> <span m='793020'>the</span> <span m='793330'>language.</span>
  <span m='794560'>They</span> <span m='794720'>are</span> <span m='794790'>the</span>
  <span m='795270'>traditional problems</span> <span m='795630'>with</span> <span
  m='795750'>ALGOL</span> <span m='796120'>like</span> <span m='796330'>languages</span>
  <span m='796690'>having</span> <span m='796870'>to</span> <span m='796970'>do</span>
  <span m='797090'>with</span> <span m='797180'>the</span> <span m='797270'>nesting</span>
  <span m='797620'>of</span> <span m='797730'>ifs</span> <span m='799170'>in</span>
  <span m='799380'>the</span> <span m='802810'>predicate</span> <span m='803190'>part.</span>
  </p><p><span m='805060'>In</span> <span m='805260'>any</span> <span m='805460'>case,</span>
  <span m='807640'>now,</span> <span m='807880'>so</span> <span m='808030'>I've</span>
  <span m='808120'>told</span> <span m='808360'>you</span> <span m='808460'>about</span>
  <span m='808600'>the</span> <span m='808750'>syntax,</span> <span m='810360'>now,</span>
  <span m='810510'>what</span> <span m='810580'>are</span> <span m='810660'>we</span>
  <span m='810770'>going</span> <span m='810900'>to</span> <span m='811040'>do</span>
  <span m='811200'>about</span> <span m='811550'>the</span> <span m='813790'>semantics</span>
  <span m='814440'>of</span> <span m='814680'>this?</span> <span m='815250'>How</span>
  <span m='815470'>do</span> <span m='815570'>we</span> <span m='815670'>interpret</span>
  <span m='816130'>it?</span> <span m='816590'>Well</span> <span m='816840'>this</span>
  <span m='816990'>is</span> <span m='817040'>just</span> <span m='817280'>super</span>
  <span m='817570'>easy.</span> <span m='818440'>I'm</span> <span m='818630'>going</span>
  <span m='818710'>to</span> <span m='818790'>modify</span> <span m='819370'>the</span>
  <span m='819690'>metacircular interpreter</span> <span m='822090'>to</span> <span
  m='822230'>do</span> <span m='822400'>it.</span> <span m='823396'>And</span> <span
  m='823780'>that's</span> <span m='824050'>a</span> <span m='824090'>one</span> <span
  m='824330'>liner.</span> <span m='826020'>There</span> <span m='826280'>it</span>
  <span m='826450'>is.</span> <span m='827590'>I'm</span> <span m='827730'>changing</span>
  <span m='828120'>the</span> <span m='828200'>way</span> <span m='828350'>you</span>
  <span m='828470'>pair</span> <span m='828800'>things</span> <span m='829160'>up.</span>
  <span m='836390'>Here's</span> <span m='836970'>the</span> <span m='837040'>procedure</span>
  <span m='837930'>that</span> <span m='838360'>pairs</span> <span m='844450'>the</span>
  <span m='844950'>variables,</span> <span m='845930'>the</span> <span m='846070'>formal</span>
  <span m='846380'>parameters,</span> <span m='848070'>with</span> <span m='848210'>the</span>
  <span m='848340'>arguments</span> <span m='848840'>that</span> <span m='848970'>were</span>
  <span m='849070'>passed</span> <span m='852090'>from</span> <span m='852250'>the</span>
  <span m='853350'>last</span> <span m='853820'>description</span> <span m='854380'>of</span>
  <span m='854560'>the</span> <span m='855660'>metacircular interpreter.</span> </p><p><span
  m='858960'>And</span> <span m='859130'>here's</span> <span m='859390'>some</span>
  <span m='859550'>things</span> <span m='860150'>that</span> <span m='860390'>are</span>
  <span m='860430'>the</span> <span m='860540'>same</span> <span m='860840'>as</span>
  <span m='860910'>they</span> <span m='861030'>were</span> <span m='861220'>before.</span>
  <span m='862670'>In</span> <span m='862960'>other</span> <span m='863330'>words,
  if</span> <span m='863550'>the</span> <span m='863660'>list</span> <span m='863910'>of</span>
  <span m='864050'>variables</span> <span m='864460'>is</span> <span m='864560'>empty,</span>
  <span m='865510'>then</span> <span m='865780'>if</span> <span m='865880'>the</span>
  <span m='865960'>list</span> <span m='866170'>of</span> <span m='866260'>values</span>
  <span m='866750'>is</span> <span m='866860'>empty,</span> <span m='868610'>then</span>
  <span m='868750'>I</span> <span m='868840'>have</span> <span m='868940'>an</span>
  <span m='869020'>empty</span> <span m='869290'>list.</span> <span m='871050'>Otherwise,</span>
  <span m='871780'>I</span> <span m='871980'>have</span> <span m='872090'>too</span>
  <span m='872220'>many</span> <span m='872450'>arguments,</span> <span m='874840'>that</span>
  <span m='875290'>is,</span> <span m='875410'>if</span> <span m='875580'>I</span>
  <span m='875690'>have</span> <span m='876890'>empty</span> <span m='877230'>variables</span>
  <span m='878710'>but</span> <span m='878950'>not</span> <span m='879230'>empty</span>
  <span m='879530'>values.</span> <span m='881580'>If</span> <span m='881790'>I</span>
  <span m='881910'>have</span> <span m='883020'>empty</span> <span m='883340'>values,</span>
  <span m='885680'>but</span> <span m='886220'>the</span> <span m='886550'>variables</span>
  <span m='886810'>are</span> <span m='887070'>not</span> <span m='887280'>empty,</span>
  <span m='887660'>I have too</span> <span m='887820'>few</span> <span m='888030'>arguments.</span>
  </p><p><span m='890090'>The</span> <span m='890210'>variables</span> <span m='890600'>are
  a</span> <span m='890850'>symbol--</span> <span m='895620'>interesting</span> <span
  m='896050'>case--</span> <span m='898130'>then,</span> <span m='898910'>what</span>
  <span m='899060'>I</span> <span m='899220'>should</span> <span m='899410'>do</span>
  <span m='901170'>is</span> <span m='901650'>say,</span> <span m='902130'>oh</span>
  <span m='902320'>yes,</span> <span m='903050'>this</span> <span m='903430'>is</span>
  <span m='903590'>the</span> <span m='903660'>special</span> <span m='904040'>case</span>
  <span m='904600'>that</span> <span m='904790'>I</span> <span m='904920'>have</span>
  <span m='905340'>a</span> <span m='905450'>symbolic</span> <span m='906000'>tail.</span>
  <span m='909010'>I</span> <span m='909180'>have</span> <span m='909490'>here</span>
  <span m='910330'>a</span> <span m='912050'>thing</span> <span m='912740'>just</span>
  <span m='912980'>like</span> <span m='913180'>we</span> <span m='913310'>looked</span>
  <span m='913540'>over</span> <span m='913740'>here.</span> <span m='914900'>This</span>
  <span m='915090'>is</span> <span m='915230'>a</span> <span m='915770'>tail</span>
  <span m='916400'>which</span> <span m='916600'>is</span> <span m='916710'>a</span>
  <span m='916780'>symbol,</span> <span m='917430'>y.</span> <span m='918630'>It's</span>
  <span m='918850'>not</span> <span m='919030'>a</span> <span m='919090'>nil.</span>
  <span m='920730'>It's</span> <span m='920790'>not</span> <span m='920970'>the</span>
  <span m='921120'>empty</span> <span m='921420'>list.</span> <span m='923240'>Here's</span>
  <span m='923490'>a</span> <span m='923530'>symbolic</span> <span m='923950'>tail</span>
  <span m='924210'>that is</span> <span m='924290'>just</span> <span m='924430'>the</span>
  <span m='924500'>very</span> <span m='924670'>beginning</span> <span m='925060'>of</span>
  <span m='925160'>the</span> <span m='925260'>tail.</span> <span m='925600'>There</span>
  <span m='926070'>is</span> <span m='926170'>nothing</span> <span m='926470'>else.</span>
  </p><p><span m='927790'>In</span> <span m='928030'>that</span> <span m='928290'>case,</span>
  <span m='929960'>I</span> <span m='930090'>wish</span> <span m='930300'>to</span>
  <span m='930440'>match</span> <span m='933390'>that</span> <span m='933620'>variable</span>
  <span m='936090'>with</span> <span m='936270'>all</span> <span m='936450'>the</span>
  <span m='936540'>values</span> <span m='938120'>and</span> <span m='938630'>add</span>
  <span m='938830'>that</span> <span m='939840'>to</span> <span m='940410'>the</span>
  <span m='941600'>pairing</span> <span m='941940'>that I'm</span> <span m='942110'>making.</span>
  <span m='944500'>Otherwise,</span> <span m='945040'>I</span> <span m='945090'>go</span>
  <span m='945260'>through</span> <span m='945420'>the</span> <span m='945970'>normal</span>
  <span m='946390'>arrangement</span> <span m='947190'>of</span> <span m='947390'>making</span>
  <span m='947660'>up</span> <span m='947720'>the whole</span> <span m='948000'>pairing.</span>
  <span m='952020'>I</span> <span m='952190'>suppose</span> <span m='952850'>that's</span>
  <span m='953170'>very</span> <span m='953430'>simple.</span> <span m='954510'>And</span>
  <span m='954720'>that's</span> <span m='954960'>all</span> <span m='955130'>there</span>
  <span m='955340'>is</span> <span m='955500'>to</span> <span m='955700'>it.</span>
  <span m='957080'>And now</span> <span m='957340'>I'll</span> <span m='957550'>answer</span>
  <span m='957750'>some</span> <span m='957890'>questions.</span> <span m='962620'>The</span>
  <span m='962800'>first</span> <span m='962990'>one--</span> <span m='964220'>Are</span>
  <span m='964340'>there</span> <span m='964450'>any</span> <span m='964560'>questions?</span>
  <span m='966600'>Yes?</span> </p><p><span m='966950'>AUDIENCE:</span> <span m='967300'>Could</span>
  <span m='967764'>you</span> <span m='968228'>explain</span> <span m='968692'>that</span>
  <span m='969940'>third</span> <span m='970240'>form?</span> </p><p><span m='970450'>PROFESSOR:</span>
  <span m='970610'>This one?</span> <span m='972590'>Well,</span> <span m='972740'>maybe</span>
  <span m='972920'>we</span> <span m='973000'>should</span> <span m='973180'>look</span>
  <span m='973370'>at</span> <span m='973560'>the</span> <span m='974070'>thing</span>
  <span m='974310'>as</span> <span m='974520'>a</span> <span m='975280'>piece of</span>
  <span m='975470'>list</span> <span m='975720'>structure.</span> <span m='978570'>This</span>
  <span m='978930'>is</span> <span m='979040'>a</span> <span m='979130'>procedure</span>
  <span m='980450'>which</span> <span m='980770'>contains</span> <span m='981850'>a</span>
  <span m='982020'>lambda.</span> <span m='985970'>I'm</span> <span m='986120'>just</span>
  <span m='986210'>looking</span> <span m='986350'>at</span> <span m='986530'>the</span>
  <span m='986580'>list</span> <span m='986750'>structure</span> <span m='987110'>which</span>
  <span m='988780'>represents</span> <span m='989240'>this.</span> <span m='991090'>Here's</span>
  <span m='992010'>x.</span> <span m='992730'>These</span> <span m='992910'>are</span>
  <span m='993230'>our</span> <span m='993360'>symbols.</span> <span m='997410'>And</span>
  <span m='997630'>then</span> <span m='997790'>the</span> <span m='997890'>body</span>
  <span m='998350'>is</span> <span m='998660'>nothing</span> <span m='998960'>but</span>
  <span m='999090'>x.</span> <span m='1004840'>If</span> <span m='1005110'>I</span>
  <span m='1005220'>were</span> <span m='1005590'>looking</span> <span m='1005670'>for</span>
  <span m='1005980'>the</span> <span m='1006250'>bound variable</span> <span m='1006590'>list
  part</span> <span m='1007050'>of</span> <span m='1008040'>this</span> <span m='1008270'>procedure,</span>
  <span m='1010140'>I</span> <span m='1010270'>would</span> <span m='1010390'>go</span>
  <span m='1010530'>looking</span> <span m='1010920'>at</span> <span m='1011120'>the</span>
  <span m='1011230'>CADR,</span> <span m='1011955'>and</span> <span m='1012240'>I'd</span>
  <span m='1012400'>find</span> <span m='1012640'>a</span> <span m='1012700'>symbol.</span>
  <span m='1014010'>So</span> <span m='1014290'>the,</span> <span m='1014925'>naturally,</span>
  <span m='1015630'>which</span> <span m='1015750'>is this</span> <span m='1015960'>pairup</span>
  <span m='1016215'>thing</span> <span m='1016470'>I</span> <span m='1016560'>just</span>
  <span m='1016750'>showed</span> <span m='1017000'>you,</span> <span m='1018320'>is</span>
  <span m='1018500'>going</span> <span m='1018730'>to</span> <span m='1018820'>be</span>
  <span m='1018960'>matching</span> <span m='1019480'>a</span> <span m='1019550'>symbolic</span>
  <span m='1020050'>object</span> <span m='1021570'>against</span> <span m='1021950'>a</span>
  <span m='1022000'>list</span> <span m='1022260'>of</span> <span m='1022860'>arguments</span>
  <span m='1023440'>that</span> <span m='1023910'>were</span> <span m='1024060'>passed.</span>
  <span m='1025760'>And</span> <span m='1025940'>it will</span> <span m='1026060'>bind</span>
  <span m='1026470'>that</span> <span m='1026690'>symbol</span> <span m='1027050'>to</span>
  <span m='1027300'>the</span> <span m='1029000'>list</span> <span m='1029250'>of</span>
  <span m='1029300'>arguments.</span> </p><p><span m='1033910'>In</span> <span m='1034060'>this</span>
  <span m='1034280'>case,</span> <span m='1034619'>if I'm</span> <span m='1035859'>looking</span>
  <span m='1036109'>for</span> <span m='1036349'>it,</span> <span m='1036829'>the</span>
  <span m='1037030'>match</span> <span m='1037349'>will</span> <span m='1037520'>be</span>
  <span m='1038560'>against</span> <span m='1039020'>this</span> <span m='1039250'>in</span>
  <span m='1039380'>the</span> <span m='1039460'>bound</span> <span m='1039715'>variable</span>
  <span m='1039970'>list</span> <span m='1040420'>position.</span> <span m='1044140'>Now,</span>
  <span m='1045180'>if</span> <span m='1045530'>what</span> <span m='1045680'>this</span>
  <span m='1045819'>does</span> <span m='1046079'>is it</span> <span m='1046130'>gets
  a</span> <span m='1046369'>list</span> <span m='1046540'>of</span> <span m='1046619'>arguments</span>
  <span m='1046940'>and</span> <span m='1047020'>returns</span> <span m='1047460'>it,</span>
  <span m='1048520'>that's</span> <span m='1048730'>list.</span> <span m='1050530'>That's
  what the</span> <span m='1050690'>procedure</span> <span m='1051110'>is.</span>
  <span m='1054510'>Oh</span> <span m='1054630'>well,</span> <span m='1054860'>thank</span>
  <span m='1055140'>you.</span> <span m='1056140'>Let's</span> <span m='1056710'>take</span>
  <span m='1056870'>a</span> <span m='1056920'>break.</span> </p><p><span m='1057830'>[MUSIC
  PLAYING]</span> </p><p><span m='1100358'>PROFESSOR:</span> <span m='1100900'>Well</span>
  <span m='1101220'>let's</span> <span m='1101560'>see.</span> <span m='1103260'>Now,</span>
  <span m='1103420'>I'm going to</span> <span m='1103540'>tell</span> <span m='1103660'>you</span>
  <span m='1103740'>about</span> <span m='1103910'>a</span> <span m='1104230'>rather</span>
  <span m='1104540'>more</span> <span m='1104760'>substantial</span> <span m='1105560'>variation,</span>
  <span m='1107790'>one</span> <span m='1107990'>that's</span> <span m='1108160'>a</span>
  <span m='1109020'>famous</span> <span m='1110170'>variation</span> <span m='1111610'>that</span>
  <span m='1112440'>many</span> <span m='1112950'>early</span> <span m='1113230'>Lisps</span>
  <span m='1116180'>had.</span> <span m='1118250'>It's</span> <span m='1118400'>called</span>
  <span m='1118650'>dynamic</span> <span m='1119060'>binding</span> <span m='1119490'>of
  variables.</span> <span m='1121770'>And</span> <span m='1122380'>we'll</span> <span
  m='1122600'>investigate</span> <span m='1123160'>a</span> <span m='1123210'>little</span>
  <span m='1123450'>bit</span> <span m='1123600'>about</span> <span m='1123930'>that</span>
  <span m='1124170'>right</span> <span m='1124420'>now.</span> <span m='1127620'>I'm</span>
  <span m='1127740'>going</span> <span m='1127820'>to</span> <span m='1127900'>first</span>
  <span m='1128200'>introduce</span> <span m='1128610'>this</span> <span m='1128800'>by</span>
  <span m='1128950'>showing</span> <span m='1129300'>you</span> <span m='1129410'>the</span>
  <span m='1129490'>sort</span> <span m='1129710'>of</span> <span m='1129790'>thing</span>
  <span m='1130270'>that</span> <span m='1130640'>would</span> <span m='1130760'>make</span>
  <span m='1131000'>someone</span> <span m='1131360'>want</span> <span m='1131690'>this</span>
  <span m='1131900'>idea.</span> </p><p><span m='1133740'>I'm</span> <span m='1133950'>not</span>
  <span m='1134100'>going</span> <span m='1134170'>to</span> <span m='1134250'>tell</span>
  <span m='1134430'>what</span> <span m='1134630'>it</span> <span m='1134700'>is</span>
  <span m='1134950'>yet,</span> <span m='1135180'>I'm</span> <span m='1135450'>going
  to</span> <span m='1135650'>show</span> <span m='1135900'>you</span> <span m='1136680'>why</span>
  <span m='1136830'>you</span> <span m='1136920'>might</span> <span m='1137130'>want</span>
  <span m='1137410'>it.</span> <span m='1138640'>Suppose,</span> <span m='1139180'>for</span>
  <span m='1139340'>example,</span> <span m='1140890'>we</span> <span m='1141010'>looked</span>
  <span m='1141150'>at</span> <span m='1141240'>the</span> <span m='1141360'>sum</span>
  <span m='1141760'>procedure</span> <span m='1142100'>again</span> <span m='1144980'>for</span>
  <span m='1145210'>summing</span> <span m='1145520'>up</span> <span m='1145640'>a</span>
  <span m='1145710'>bunch</span> <span m='1145930'>of</span> <span m='1146030'>things.</span>
  <span m='1148140'>To</span> <span m='1148250'>be</span> <span m='1148400'>that</span>
  <span m='1148690'>procedure,</span> <span m='1149660'>of</span> <span m='1149930'>a</span>
  <span m='1150080'>term,</span> <span m='1153290'>lower</span> <span m='1153870'>bound,</span>
  <span m='1155230'>method</span> <span m='1155500'>of</span> <span m='1155860'>computing</span>
  <span m='1156130'>the</span> <span m='1156380'>next</span> <span m='1156640'>index,</span>
  <span m='1157360'>and</span> <span m='1157600'>upper</span> <span m='1157850'>bound,</span>
  <span m='1159500'>such</span> <span m='1159870'>that,</span> <span m='1163060'>if</span>
  <span m='1165240'>a</span> <span m='1165560'>is</span> <span m='1165740'>greater</span>
  <span m='1166010'>than</span> <span m='1166460'>b</span> <span m='1167150'>then</span>
  <span m='1167340'>the</span> <span m='1167430'>result</span> <span m='1167880'>is</span>
  <span m='1168070'>0,</span> <span m='1170330'>otherwise,</span> <span m='1173740'>it's</span>
  <span m='1174020'>the</span> <span m='1174150'>sum,</span> <span m='1175090'>of</span>
  <span m='1175340'>the</span> <span m='1175510'>term,</span> <span m='1176690'>procedure,</span>
  <span m='1178750'>applied</span> <span m='1179005'>to</span> <span m='1179260'>a</span>
  <span m='1180322'>and</span> <span m='1180680'>the</span> <span m='1180920'>result</span>
  <span m='1181300'>of</span> <span m='1181370'>adding</span> <span m='1181680'>up,</span>
  <span m='1183480'>terms,</span> <span m='1188400'>with</span> <span m='1188540'>the</span>
  <span m='1190330'>next</span> <span m='1191470'>a</span> <span m='1191710'>being
  the</span> <span m='1192140'>a,</span> <span m='1200400'>the</span> <span m='1201780'>next</span>
  <span m='1202080'>procedure</span> <span m='1202460'>passed</span> <span m='1202780'>along,</span>
  <span m='1206340'>and</span> <span m='1206740'>the</span> <span m='1206920'>upper</span>
  <span m='1206970'>bound</span> <span m='1207235'>being</span> <span m='1207500'>passed</span>
  <span m='1207770'>along.</span> <span m='1214510'>Blink,</span> <span m='1214980'>blink,</span>
  <span m='1215360'>blink--</span> </p><p><span m='1218900'>Now,</span> <span m='1219700'>when</span>
  <span m='1219880'>I</span> <span m='1219960'>use</span> <span m='1220290'>this</span>
  <span m='1220530'>sum</span> <span m='1220810'>procedure,</span> <span m='1222040'>I</span>
  <span m='1222230'>can</span> <span m='1222370'>use</span> <span m='1222600'>it,</span>
  <span m='1223110'>for</span> <span m='1223350'>example,</span> <span m='1223770'>like</span>
  <span m='1224010'>this.</span> <span m='1225450'>We</span> <span m='1225660'>can</span>
  <span m='1225860'>define</span> <span m='1230620'>the</span> <span m='1231080'>sum</span>
  <span m='1232630'>of</span> <span m='1232800'>the</span> <span m='1232890'>powers</span>
  <span m='1237470'>to</span> <span m='1237690'>be,</span> <span m='1238050'>for</span>
  <span m='1238160'>example,</span> <span m='1238460'>sum</span> <span m='1238680'>of</span>
  <span m='1238760'>a</span> <span m='1238850'>bunch of</span> <span m='1239150'>powers</span>
  <span m='1239480'>x</span> <span m='1239710'>to</span> <span m='1239820'>the</span>
  <span m='1240150'>n,</span> <span m='1241100'>to</span> <span m='1241270'>be</span>
  <span m='1241890'>that</span> <span m='1242270'>procedure</span> <span m='1243240'>of</span>
  <span m='1243620'>a,</span> <span m='1244840'>b,</span> <span m='1245250'>and</span>
  <span m='1245450'>n--</span> <span m='1245970'>lower</span> <span m='1246200'>bound,</span>
  <span m='1246400'>the</span> <span m='1246490'>upper</span> <span m='1246690'>bound,</span>
  <span m='1247000'>and</span> <span m='1247160'>n--</span> <span m='1248150'>which</span>
  <span m='1248350'>is</span> <span m='1248590'>sum,</span> <span m='1250964'>of</span>
  <span m='1251870'>lambda</span> <span m='1252710'>of</span> <span m='1252820'>x,</span>
  <span m='1253620'>the procedure</span> <span m='1253970'>of</span> <span m='1254220'>one</span>
  <span m='1254410'>argument</span> <span m='1254530'>x,</span> <span m='1255150'>which</span>
  <span m='1255370'>exponentiates</span> <span m='1258340'>x</span> <span m='1258660'>to</span>
  <span m='1258740'>the</span> <span m='1259190'>n,</span> <span m='1262400'>with</span>
  <span m='1262600'>the</span> <span m='1264430'>a,</span> <span m='1265310'>the</span>
  <span m='1265720'>incrementer,</span> <span m='1266005'>and</span> <span m='1267310'>b,</span>
  <span m='1268050'>being</span> <span m='1268690'>passed</span> <span m='1268970'>along.</span>
  </p><p><span m='1271440'>So</span> <span m='1272010'>we're</span> <span m='1272190'>adding</span>
  <span m='1272530'>up</span> <span m='1274030'>x</span> <span m='1274250'>to</span>
  <span m='1274340'>n,</span> <span m='1274890'>given</span> <span m='1275140'>an</span>
  <span m='1275270'>x.</span> <span m='1276340'>x</span> <span m='1276580'>takes</span>
  <span m='1276840'>on</span> <span m='1277030'>values</span> <span m='1277510'>from</span>
  <span m='1277680'>a</span> <span m='1277840'>to</span> <span m='1277920'>b,</span>
  <span m='1278620'>incrementing</span> <span m='1279180'>by</span> <span m='1279380'>one.</span>
  <span m='1282940'>I</span> <span m='1283080'>can</span> <span m='1283190'>also</span>
  <span m='1283460'>write</span> <span m='1284020'>the--</span> <span m='1287670'>That's</span>
  <span m='1287950'>right.</span> <span m='1289780'>Product,</span> <span m='1290140'>excuse</span>
  <span m='1290530'>me.</span> <span m='1291910'>The</span> <span m='1292170'>product</span>
  <span m='1292520'>of</span> <span m='1292590'>a</span> <span m='1292630'>bunch</span>
  <span m='1292840'>of</span> <span m='1292910'>powers.</span> <span m='1298080'>It's</span>
  <span m='1298170'>a</span> <span m='1298210'>strange</span> <span m='1298610'>name.</span>
  <span m='1300020'>I'm</span> <span m='1300150'>going</span> <span m='1300370'>to</span>
  <span m='1300760'>leave</span> <span m='1301160'>it there.</span> <span m='1301960'>Weird--</span>
  <span m='1305760'>I</span> <span m='1305940'>write</span> <span m='1306120'>up</span>
  <span m='1306590'>what</span> <span m='1307060'>I</span> <span m='1307530'>have.</span>
  <span m='1309410'>I'm</span> <span m='1309590'>sure</span> <span m='1309770'>that's</span>
  <span m='1310000'>right.</span> <span m='1310890'>And</span> <span m='1311570'>if</span>
  <span m='1311670'>I</span> <span m='1311710'>want</span> <span m='1311910'>the</span>
  <span m='1311970'>product</span> <span m='1312270'>of</span> <span m='1312570'>a</span>
  <span m='1313000'>bunch of</span> <span m='1313370'>powers--</span> <span m='1318630'>That</span>
  <span m='1318740'>was</span> <span m='1318880'>12</span> <span m='1319170'>brain</span>
  <span m='1319440'>cells,</span> <span m='1321560'>that</span> <span m='1321690'>double-take.</span>
  </p><p><span m='1323400'>I</span> <span m='1323530'>can</span> <span m='1323740'>for</span>
  <span m='1323890'>example</span> <span m='1324290'>use</span> <span m='1324930'>the</span>
  <span m='1325420'>procedure</span> <span m='1326040'>which</span> <span m='1326260'>is</span>
  <span m='1326370'>like</span> <span m='1326640'>sum,</span> <span m='1326890'>which</span>
  <span m='1327050'>is</span> <span m='1327110'>for</span> <span m='1327220'>making</span>
  <span m='1327640'>products,</span> <span m='1328650'>but it's</span> <span m='1328940'>similar</span>
  <span m='1329230'>to</span> <span m='1329350'>that,</span> <span m='1329720'>that</span>
  <span m='1330080'>you've</span> <span m='1330260'>seen</span> <span m='1330460'>before.</span>
  <span m='1331450'>There's</span> <span m='1331810'>a</span> <span m='1331860'>procedure</span>
  <span m='1335060'>of</span> <span m='1335210'>three</span> <span m='1335470'>arguments</span>
  <span m='1335850'>again.</span> <span m='1336725'>Which</span> <span m='1337090'>is</span>
  <span m='1337260'>the</span> <span m='1337380'>product</span> <span m='1340800'>of</span>
  <span m='1342430'>terms</span> <span m='1343080'>that</span> <span m='1343230'>are</span>
  <span m='1343380'>constructed,</span> <span m='1343980'>or</span> <span m='1344080'>factors</span>
  <span m='1344570'>in</span> <span m='1344730'>this</span> <span m='1344890'>case,</span>
  <span m='1345660'>constructed</span> <span m='1346270'>from</span> <span m='1346480'>exponentiating</span>
  <span m='1350680'>x</span> <span m='1350900'>to</span> <span m='1351155'>the</span>
  <span m='1351410'>n,</span> <span m='1354530'>where</span> <span m='1354750'>I</span>
  <span m='1354830'>start</span> <span m='1355150'>with</span> <span m='1355310'>a,</span>
  <span m='1355780'>I</span> <span m='1355970'>increment,</span> <span m='1356990'>and</span>
  <span m='1357110'>I</span> <span m='1357230'>go</span> <span m='1357350'>to</span>
  <span m='1357470'>b.</span> </p><p><span m='1361530'>Now,</span> <span m='1366840'>there's</span>
  <span m='1367090'>some</span> <span m='1367260'>sort</span> <span m='1367450'>of</span>
  <span m='1367540'>thing</span> <span m='1367790'>here</span> <span m='1367980'>that</span>
  <span m='1368140'>should</span> <span m='1368270'>disturb</span> <span m='1368690'>you</span>
  <span m='1368800'>immediately.</span> <span m='1370750'>These</span> <span m='1371130'>look</span>
  <span m='1371300'>the</span> <span m='1371380'>same.</span> <span m='1373180'>Why</span>
  <span m='1373440'>am I</span> <span m='1373620'>writing</span> <span m='1373910'>this</span>
  <span m='1374080'>code</span> <span m='1374360'>so</span> <span m='1374490'>many</span>
  <span m='1374700'>times?</span> <span m='1376590'>Here</span> <span m='1376990'>I</span>
  <span m='1377080'>am,</span> <span m='1378090'>in</span> <span m='1378180'>the</span>
  <span m='1378270'>same</span> <span m='1378550'>boat</span> <span m='1378790'>I've</span>
  <span m='1378920'>been</span> <span m='1379090'>in</span> <span m='1379220'>before.</span>
  <span m='1381270'>Wouldn't</span> <span m='1381530'>it be</span> <span m='1381640'>nice</span>
  <span m='1381910'>to</span> <span m='1381990'>make</span> <span m='1382160'>an</span>
  <span m='1382220'>abstraction</span> <span m='1382810'>here?</span> <span m='1383810'>What's</span>
  <span m='1384050'>an</span> <span m='1384130'>example</span> <span m='1384630'>of
  a good</span> <span m='1384790'>abstraction</span> <span m='1385400'>to</span> <span
  m='1385480'>make?</span> <span m='1385980'>Well,</span> <span m='1386140'>I</span>
  <span m='1386230'>see</span> <span m='1386410'>some</span> <span m='1386640'>codes</span>
  <span m='1387000'>that's</span> <span m='1387500'>identical.</span> <span m='1388470'>Here's</span>
  <span m='1388770'>one,</span> <span m='1390160'>and</span> <span m='1390420'>here's</span>
  <span m='1390670'>another.</span> </p><p><span m='1394450'>And</span> <span m='1394570'>so</span>
  <span m='1394690'>maybe</span> <span m='1394950'>I</span> <span m='1395030'>should</span>
  <span m='1395130'>be</span> <span m='1395240'>able</span> <span m='1395330'>to</span>
  <span m='1395390'>pull</span> <span m='1395640'>that</span> <span m='1395860'>out.</span>
  <span m='1397090'>I</span> <span m='1397230'>should</span> <span m='1397340'>be</span>
  <span m='1397450'>able</span> <span m='1397640'>to</span> <span m='1397740'>say,</span>
  <span m='1398580'>oh</span> <span m='1398760'>yes,</span> <span m='1400270'>the</span>
  <span m='1400670'>sum</span> <span m='1400930'>of</span> <span m='1401030'>the</span>
  <span m='1401130'>powers</span> <span m='1401580'>could</span> <span m='1401680'>be</span>
  <span m='1401850'>written</span> <span m='1402070'>in</span> <span m='1402150'>terms</span>
  <span m='1402470'>of</span> <span m='1402810'>something</span> <span m='1403140'>called</span>
  <span m='1403350'>the</span> <span m='1403460'>nth</span> <span m='1403730'>power</span>
  <span m='1404000'>procedure.</span> <span m='1405710'>Imagine</span> <span m='1406210'>somebody</span>
  <span m='1406650'>wanted</span> <span m='1407030'>to</span> <span m='1407130'>write</span>
  <span m='1407870'>a</span> <span m='1407960'>slightly</span> <span m='1408330'>different</span>
  <span m='1408690'>procedure that</span> <span m='1409050'>looks</span> <span m='1409330'>like</span>
  <span m='1409560'>this.</span> <span m='1417630'>The</span> <span m='1417820'>sum</span>
  <span m='1418120'>powers</span> <span m='1424050'>to</span> <span m='1424280'>be</span>
  <span m='1424460'>a</span> <span m='1424550'>procedure</span> <span m='1426366'>of</span>
  <span m='1426750'>a,</span> <span m='1427230'>b,</span> <span m='1427620'>and</span>
  <span m='1427830'>n,</span> <span m='1428900'>as</span> <span m='1429300'>the result
  of</span> <span m='1429680'>summing</span> <span m='1430110'>up</span> <span m='1431310'>the</span>
  <span m='1431530'>nth</span> <span m='1431880'>power.</span> <span m='1433556'>We're</span>
  <span m='1434000'>going to</span> <span m='1434210'>give a</span> <span m='1434390'>name</span>
  <span m='1434680'>to</span> <span m='1434760'>that</span> <span m='1434920'>idea,</span>
  <span m='1438300'>for</span> <span m='1438500'>starting</span> <span m='1438810'>at</span>
  <span m='1438900'>a,</span> <span m='1439720'>going</span> <span m='1440060'>by</span>
  <span m='1440240'>one,</span> <span m='1441280'>and</span> <span m='1441480'>ending</span>
  <span m='1441790'>at</span> <span m='1441830'>b.</span> </p><p><span m='1446000'>And</span>
  <span m='1446100'>similarly,</span> <span m='1450650'>I</span> <span m='1451050'>might</span>
  <span m='1451150'>want</span> <span m='1451270'>to</span> <span m='1451390'>write
  the</span> <span m='1451640'>product</span> <span m='1451980'>powers</span> <span
  m='1452290'>this</span> <span m='1452480'>way,</span> <span m='1452930'>abstracting</span>
  <span m='1453720'>out</span> <span m='1454400'>this</span> <span m='1454700'>idea.</span>
  <span m='1456270'>I</span> <span m='1456400'>might</span> <span m='1456700'>want</span>
  <span m='1457000'>this.</span> <span m='1462100'>Product</span> <span m='1462500'>powers,</span>
  <span m='1469540'>to</span> <span m='1469670'>be</span> <span m='1469830'>a</span>
  <span m='1469900'>procedure</span> <span m='1471556'>of</span> <span m='1472990'>a,</span>
  <span m='1473110'>b,</span> <span m='1473470'>and</span> <span m='1473880'>n,</span>
  <span m='1475350'>which</span> <span m='1475590'>is</span> <span m='1475690'>the</span>
  <span m='1475790'>product</span> <span m='1479870'>of</span> <span m='1480340'>the</span>
  <span m='1480530'>nth</span> <span m='1480855'>power</span> <span m='1481470'>operation</span>
  <span m='1486560'>on</span> <span m='1486860'>a</span> <span m='1487410'>with</span>
  <span m='1487540'>the</span> <span m='1487670'>incrementation</span> <span m='1488780'>and</span>
  <span m='1489110'>b</span> <span m='1489720'>being</span> <span m='1493950'>my</span>
  <span m='1495040'>arguments</span> <span m='1495620'>for</span> <span m='1496210'>the</span>
  <span m='1496380'>analogous-thing</span> <span m='1497100'>product.</span> </p><p><span
  m='1498380'>And I'd</span> <span m='1498670'>like</span> <span m='1498910'>to</span>
  <span m='1499020'>be</span> <span m='1499160'>able</span> <span m='1499380'>to</span>
  <span m='1499480'>define,</span> <span m='1502070'>I'd</span> <span m='1502240'>like</span>
  <span m='1502420'>to</span> <span m='1502500'>be</span> <span m='1502600'>able</span>
  <span m='1502760'>to</span> <span m='1502840'>define</span> <span m='1503210'>nth</span>
  <span m='1503420'>power--</span> <span m='1504680'>I'll</span> <span m='1505060'>put</span>
  <span m='1505210'>it</span> <span m='1505290'>over</span> <span m='1505480'>here.</span>
  <span m='1511215'>I'll</span> <span m='1511700'>put it at</span> <span m='1512190'>the</span>
  <span m='1512670'>top.</span> <span m='1525410'>--to</span> <span m='1525690'>be,</span>
  <span m='1525960'>in</span> <span m='1526080'>fact,</span> <span m='1526350'>my</span>
  <span m='1526480'>procedure</span> <span m='1527730'>of</span> <span m='1527940'>one</span>
  <span m='1528150'>argument</span> <span m='1528550'>x</span> <span m='1529710'>which</span>
  <span m='1529990'>is</span> <span m='1530440'>the</span> <span m='1530630'>result</span>
  <span m='1530990'>of</span> <span m='1531070'>exponentiating</span> <span m='1533610'>x</span>
  <span m='1534300'>to</span> <span m='1534620'>the</span> <span m='1535005'>n.</span>
  <span m='1535390'>But</span> <span m='1536160'>I</span> <span m='1536230'>have</span>
  <span m='1536300'>a</span> <span m='1536370'>problem.</span> <span m='1538640'>My</span>
  <span m='1538880'>environment</span> <span m='1539440'>model,</span> <span m='1540450'>that</span>
  <span m='1540830'>is</span> <span m='1541060'>my</span> <span m='1541690'>means</span>
  <span m='1542040'>of</span> <span m='1542130'>interpretation</span> <span m='1543970'>for</span>
  <span m='1544160'>the</span> <span m='1544240'>language</span> <span m='1544710'>that</span>
  <span m='1544810'>we've</span> <span m='1544940'>defined</span> <span m='1545370'>so</span>
  <span m='1545710'>far,</span> <span m='1546280'>does</span> <span m='1546520'>not</span>
  <span m='1546800'>give</span> <span m='1547010'>me</span> <span m='1547340'>a</span>
  <span m='1547530'>meaning</span> <span m='1548040'>for</span> <span m='1548200'>this</span>
  <span m='1548420'>n.</span> <span m='1552520'>Because,</span> <span m='1554620'>as</span>
  <span m='1554930'>you</span> <span m='1555060'>know,</span> <span m='1560700'>this</span>
  <span m='1561000'>n</span> <span m='1561260'>is</span> <span m='1561560'>free</span>
  <span m='1563250'>in</span> <span m='1563410'>this</span> <span m='1563610'>procedure.</span>
  </p><p><span m='1566410'>The</span> <span m='1566590'>environment</span> <span m='1567060'>model</span>
  <span m='1567320'>tells</span> <span m='1567680'>us</span> <span m='1568390'>that</span>
  <span m='1568820'>the</span> <span m='1568900'>meaning</span> <span m='1569220'>of</span>
  <span m='1569310'>a</span> <span m='1569370'>free</span> <span m='1569600'>variable</span>
  <span m='1571260'>is</span> <span m='1571430'>determined</span> <span m='1571910'>in</span>
  <span m='1572010'>the</span> <span m='1572120'>environment</span> <span m='1573210'>in</span>
  <span m='1573380'>which</span> <span m='1573590'>this</span> <span m='1573760'>procedure
  is</span> <span m='1574220'>defined.</span> <span m='1576640'>In</span> <span m='1576770'>a</span>
  <span m='1576810'>way I</span> <span m='1576960'>have</span> <span m='1577140'>written
  it,</span> <span m='1577370'>assuming</span> <span m='1577710'>these</span> <span
  m='1577880'>things</span> <span m='1578060'>are</span> <span m='1578120'>defined</span>
  <span m='1578560'>on</span> <span m='1578690'>the</span> <span m='1578750'>blackboard</span>
  <span m='1579250'>as</span> <span m='1579610'>is,</span> <span m='1581660'>this</span>
  <span m='1581910'>is</span> <span m='1582070'>defined</span> <span m='1582600'>in</span>
  <span m='1582720'>the</span> <span m='1582830'>global</span> <span m='1583150'>environment,</span>
  <span m='1584130'>where</span> <span m='1584290'>there</span> <span m='1584460'>is</span>
  <span m='1584540'>no</span> <span m='1584720'>end.</span> <span m='1585850'>Therefore,</span>
  <span m='1586360'>n</span> <span m='1586520'>is</span> <span m='1586670'>unbound</span>
  <span m='1587130'>variable.</span> </p><p><span m='1588720'>But</span> <span m='1588940'>it's</span>
  <span m='1589050'>perfectly</span> <span m='1589560'>clear,</span> <span m='1590830'>to</span>
  <span m='1590980'>most</span> <span m='1591290'>of</span> <span m='1591420'>us,</span>
  <span m='1592630'>that</span> <span m='1592850'>we</span> <span m='1592980'>would</span>
  <span m='1593130'>like</span> <span m='1593390'>it</span> <span m='1593490'>to</span>
  <span m='1593590'>be</span> <span m='1593770'>this</span> <span m='1594070'>n</span>
  <span m='1595480'>and</span> <span m='1595730'>this</span> <span m='1595950'>n.</span>
  <span m='1598990'>On</span> <span m='1599260'>the</span> <span m='1599440'>other</span>
  <span m='1599630'>hand,</span> <span m='1601880'>it</span> <span m='1602050'>would</span>
  <span m='1602150'>be</span> <span m='1602260'>nice.</span> <span m='1602840'>Certainly</span>
  <span m='1603095'>we've</span> <span m='1603350'>got</span> <span m='1603440'>to</span>
  <span m='1603540'>be</span> <span m='1603640'>careful</span> <span m='1604000'>here</span>
  <span m='1604580'>of</span> <span m='1604750'>keeping</span> <span m='1605080'>this</span>
  <span m='1605290'>to</span> <span m='1605390'>be</span> <span m='1605590'>this,</span>
  <span m='1609030'>and</span> <span m='1609270'>this</span> <span m='1609450'>one</span>
  <span m='1609630'>over</span> <span m='1609820'>here,</span> <span m='1610390'>wherever</span>
  <span m='1610810'>it is</span> <span m='1611720'>to</span> <span m='1612160'>be</span>
  <span m='1612310'>this</span> <span m='1612510'>one.</span> </p><p><span m='1617390'>Well,</span>
  <span m='1617870'>the</span> <span m='1618090'>desire</span> <span m='1618700'>to</span>
  <span m='1618840'>make</span> <span m='1619060'>this</span> <span m='1619340'>work</span>
  <span m='1620700'>has</span> <span m='1620960'>led</span> <span m='1621210'>to</span>
  <span m='1621360'>a</span> <span m='1621420'>very</span> <span m='1621750'>famous</span>
  <span m='1622200'>bug.</span> <span m='1624040'>I'll</span> <span m='1624610'>tell</span>
  <span m='1624820'>you</span> <span m='1624910'>about</span> <span m='1625090'>the</span>
  <span m='1625260'>famous</span> <span m='1625610'>bug.</span> <span m='1627310'>Look</span>
  <span m='1627430'>at</span> <span m='1627560'>this</span> <span m='1628740'>slide.</span>
  <span m='1630660'>This is</span> <span m='1630790'>an</span> <span m='1630920'>idea</span>
  <span m='1631310'>called</span> <span m='1631610'>dynamic</span> <span m='1632070'>binding.</span>
  <span m='1633990'>Where,</span> <span m='1634170'>instead</span> <span m='1634660'>of</span>
  <span m='1634970'>the</span> <span m='1635140'>free</span> <span m='1635400'>variable</span>
  <span m='1635910'>being</span> <span m='1636180'>interpreted</span> <span m='1637780'>in</span>
  <span m='1637980'>the</span> <span m='1638150'>environment</span> <span m='1639640'>of</span>
  <span m='1639880'>definition</span> <span m='1640460'>of</span> <span m='1640550'>a</span>
  <span m='1640620'>procedure,</span> <span m='1642250'>the</span> <span m='1642580'>free</span>
  <span m='1642820'>variable</span> <span m='1643340'>is</span> <span m='1643450'>interpreted</span>
  <span m='1644070'>as</span> <span m='1644230'>having</span> <span m='1644480'>its</span>
  <span m='1644640'>value</span> <span m='1645400'>in</span> <span m='1645640'>the</span>
  <span m='1645770'>environment</span> <span m='1647090'>of</span> <span m='1647260'>the</span>
  <span m='1647350'>caller</span> <span m='1648680'>of</span> <span m='1648770'>the</span>
  <span m='1648860'>procedure.</span> </p><p><span m='1651850'>So</span> <span m='1652160'>what</span>
  <span m='1652330'>you</span> <span m='1652670'>have</span> <span m='1653690'>is</span>
  <span m='1654270'>a</span> <span m='1654450'>system</span> <span m='1654850'>where</span>
  <span m='1655070'>you</span> <span m='1655230'>search</span> <span m='1655580'>up</span>
  <span m='1655880'>the</span> <span m='1656250'>chain</span> <span m='1656680'>of</span>
  <span m='1656790'>callers</span> <span m='1657940'>of</span> <span m='1658430'>a</span>
  <span m='1658610'>particular</span> <span m='1659020'>procedure,</span> <span m='1660520'>and,</span>
  <span m='1660680'>of</span> <span m='1661020'>course,</span> <span m='1661800'>in</span>
  <span m='1661990'>this</span> <span m='1662230'>case,</span> <span m='1662830'>since</span>
  <span m='1663220'>nth</span> <span m='1663480'>power</span> <span m='1663860'>is</span>
  <span m='1664030'>called</span> <span m='1664340'>from</span> <span m='1664490'>inside</span>
  <span m='1664920'>product</span> <span m='1665240'>whatever</span> <span m='1665610'>it</span>
  <span m='1665660'>is--</span> <span m='1666010'>I</span> <span m='1666480'>had</span>
  <span m='1666670'>to</span> <span m='1667010'>write</span> <span m='1667100'>our</span>
  <span m='1667370'>own</span> <span m='1667570'>sum which is the</span> <span m='1667690'>analogous</span>
  <span m='1668140'>procedure--</span> <span m='1670530'>and</span> <span m='1671860'>product</span>
  <span m='1672290'>is</span> <span m='1672500'>presumably</span> <span m='1673020'>called</span>
  <span m='1673360'>from</span> <span m='1674040'>product</span> <span m='1674400'>powers,</span>
  <span m='1675190'>as</span> <span m='1675300'>you</span> <span m='1675370'>see</span>
  <span m='1675530'>over</span> <span m='1675710'>here,</span> <span m='1676890'>then</span>
  <span m='1677060'>since</span> <span m='1677260'>product</span> <span m='1677570'>powers</span>
  <span m='1677970'>bind</span> <span m='1678360'>with</span> <span m='1678490'>variable</span>
  <span m='1678760'>n ,</span> <span m='1680070'>then</span> <span m='1681190'>nth</span>
  <span m='1681430'>powers</span> <span m='1681800'>n</span> <span m='1682350'>would</span>
  <span m='1682580'>be</span> <span m='1682700'>derived</span> <span m='1683220'>through</span>
  <span m='1683420'>that</span> <span m='1683630'>chain.</span> </p><p><span m='1688140'>Similarly,</span>
  <span m='1688780'>this</span> <span m='1689260'>n,</span> <span m='1690020'>the  nth</span>
  <span m='1690330'>power</span> <span m='1690595'>in</span> <span m='1690860'>n</span>
  <span m='1691200'>in</span> <span m='1691360'>this</span> <span m='1691580'>case,</span>
  <span m='1692380'>would</span> <span m='1692600'>come</span> <span m='1692850'>through</span>
  <span m='1693250'>nth</span> <span m='1693510'>power</span> <span m='1693810'>here</span>
  <span m='1694100'>being</span> <span m='1694360'>called</span> <span m='1694610'>from</span>
  <span m='1694760'>inside</span> <span m='1695150'>sum.</span> <span m='1695800'>You</span>
  <span m='1695960'>can</span> <span m='1696130'>see</span> <span m='1696440'>it</span>
  <span m='1696510'>being</span> <span m='1696750'>called</span> <span m='1697030'>from</span>
  <span m='1697170'>inside</span> <span m='1697560'>sum</span> <span m='1697800'>here.</span>
  <span m='1699730'>It's</span> <span m='1700680'>called</span> <span m='1701050'>term</span>
  <span m='1701360'>here.</span> <span m='1702900'>But</span> <span m='1703280'>sum</span>
  <span m='1703590'>was</span> <span m='1703740'>called</span> <span m='1704060'>from</span>
  <span m='1704200'>inside</span> <span m='1704770'>of</span> <span m='1704930'>sum</span>
  <span m='1705190'>powers,</span> <span m='1707060'>which</span> <span m='1707260'>bound</span>
  <span m='1707610'>n.</span> <span m='1708930'>Therefore,</span> <span m='1709430'>there</span>
  <span m='1709520'>would</span> <span m='1709610'>be</span> <span m='1709730'>an
  n</span> <span m='1710020'>available</span> <span m='1712700'>for</span> <span m='1713300'>that</span>
  <span m='1713880'>n</span> <span m='1714970'>to</span> <span m='1715120'>get it's</span>
  <span m='1715370'>value</span> <span m='1715760'>from.</span> </p><p><span m='1719430'>What</span>
  <span m='1719590'>we</span> <span m='1719690'>have</span> <span m='1719860'>below</span>
  <span m='1720190'>this</span> <span m='1720390'>white</span> <span m='1720670'>line</span>
  <span m='1722170'>plus</span> <span m='1722490'>over</span> <span m='1722650'>here,</span>
  <span m='1723380'>is</span> <span m='1723520'>what's</span> <span m='1723630'>called</span>
  <span m='1723840'>a</span> <span m='1723880'>dynamic</span> <span m='1724380'>binding</span>
  <span m='1725420'>view</span> <span m='1725580'>of</span> <span m='1725680'>the</span>
  <span m='1725920'>world.</span> <span m='1726540'>If</span> <span m='1726690'>that</span>
  <span m='1726930'>works,</span> <span m='1727600'>that's</span> <span m='1727720'>a</span>
  <span m='1727800'>dynamic</span> <span m='1728260'>binding</span> <span m='1728620'>view.</span>
  <span m='1730850'>Now,</span> <span m='1731000'>let's</span> <span m='1731200'>take</span>
  <span m='1731370'>a</span> <span m='1731420'>look,</span> <span m='1731630'>for</span>
  <span m='1731800'>example,</span> <span m='1734710'>at just</span> <span m='1734970'>what
  it</span> <span m='1735130'>takes</span> <span m='1735310'>to implement</span> <span
  m='1735760'>that.</span> <span m='1735990'>That's</span> <span m='1736140'>real</span>
  <span m='1736530'>easy.</span> </p><p><span m='1737480'>In</span> <span m='1737660'>fact,</span>
  <span m='1737990'>the</span> <span m='1738240'>very</span> <span m='1738490'>first</span>
  <span m='1738790'>Lisps</span> <span m='1739830'>that</span> <span m='1740220'>had</span>
  <span m='1740460'>any</span> <span m='1740860'>interpretations</span> <span m='1741400'>of</span>
  <span m='1741470'>the</span> <span m='1741540'>free</span> <span m='1741720'>variables</span>
  <span m='1742190'>at all,</span> <span m='1743360'>had</span> <span m='1743500'>dynamic</span>
  <span m='1743930'>binding</span> <span m='1744440'>interpretations</span> <span
  m='1745110'>for</span> <span m='1745180'>the</span> <span m='1745250'>free</span>
  <span m='1745430'>variables.</span> <span m='1746490'>APL</span> <span m='1747870'>has</span>
  <span m='1748000'>dynamic</span> <span m='1748390'>binding</span> <span m='1748680'>interpretation</span>
  <span m='1749240'>for</span> <span m='1749320'>the</span> <span m='1749400'>free</span>
  <span m='1749570'>variables,</span> <span m='1752790'>not</span> <span m='1753080'>lexical</span>
  <span m='1753470'>or</span> <span m='1753560'>static</span> <span m='1753970'>binding.</span>
  <span m='1755220'>So,</span> <span m='1755810'>of</span> <span m='1755950'>course,</span>
  <span m='1756090'>the</span> <span m='1756180'>change</span> <span m='1756540'>is
  in</span> <span m='1756600'>eval.</span> <span m='1758790'>And</span> <span m='1759160'>it's</span>
  <span m='1759560'>really</span> <span m='1759790'>in</span> <span m='1759910'>two</span>
  <span m='1760040'>places.</span> </p><p><span m='1762780'>First</span> <span m='1763190'>of</span>
  <span m='1763310'>all,</span> <span m='1764740'>one</span> <span m='1764960'>thing</span>
  <span m='1765120'>we</span> <span m='1765250'>see,</span> <span m='1766590'>is</span>
  <span m='1766760'>that</span> <span m='1767140'>things</span> <span m='1767450'>become</span>
  <span m='1767710'>a</span> <span m='1767760'>little</span> <span m='1767990'>simpler.</span>
  <span m='1772460'>If</span> <span m='1772580'>I</span> <span m='1772660'>don't</span>
  <span m='1772820'>have</span> <span m='1773010'>to</span> <span m='1773160'>have</span>
  <span m='1773320'>the</span> <span m='1773690'>environment</span> <span m='1773990'>be</span>
  <span m='1774290'>the</span> <span m='1774530'>environment</span> <span m='1774930'>of</span>
  <span m='1774970'>definition</span> <span m='1775520'>for</span> <span m='1775660'>procedure,</span>
  <span m='1776380'>the</span> <span m='1776690'>procedure</span> <span m='1777120'>need</span>
  <span m='1777310'>not</span> <span m='1777520'>capture</span> <span m='1778490'>the</span>
  <span m='1778640'>environment</span> <span m='1779130'>at</span> <span m='1779260'>the</span>
  <span m='1779380'>time</span> <span m='1779580'>it's</span> <span m='1779690'>defined.</span>
  <span m='1782030'>And</span> <span m='1782230'>so</span> <span m='1782410'>if</span>
  <span m='1782500'>we</span> <span m='1782620'>look</span> <span m='1782840'>here</span>
  <span m='1783060'>at</span> <span m='1783270'>this</span> <span m='1784390'>slide,</span>
  <span m='1785720'>we</span> <span m='1786050'>see</span> <span m='1786540'>that</span>
  <span m='1786900'>the</span> <span m='1787200'>clause</span> <span m='1787900'>for</span>
  <span m='1788840'>a</span> <span m='1789010'>lambda</span> <span m='1789420'>expression,</span>
  <span m='1790780'>which</span> <span m='1790970'>is</span> <span m='1791060'>the</span>
  <span m='1791130'>way a</span> <span m='1791330'>procedure</span> <span m='1791610'>is</span>
  <span m='1791890'>defined,</span> <span m='1793960'>does</span> <span m='1794110'>not</span>
  <span m='1794400'>make</span> <span m='1794580'>up</span> <span m='1794780'>a</span>
  <span m='1794920'>thing</span> <span m='1795170'>which</span> <span m='1795340'>has</span>
  <span m='1795570'>a</span> <span m='1795890'>type</span> <span m='1796200'>closure</span>
  <span m='1797820'>and</span> <span m='1798170'>a</span> <span m='1799020'>attached</span>
  <span m='1800040'>environment</span> <span m='1800550'>structure.</span> <span m='1801290'>It's</span>
  <span m='1801490'>just</span> <span m='1801680'>the</span> <span m='1801770'>expression</span>
  <span m='1802200'>itself.</span> <span m='1802540'>And we'll</span> <span m='1802770'>decompose</span>
  <span m='1803430'>that</span> <span m='1803610'>some</span> <span m='1803740'>other</span>
  <span m='1803880'>way</span> <span m='1804040'>somewhere</span> <span m='1804370'>else.</span>
  </p><p><span m='1806440'>The</span> <span m='1806620'>other</span> <span m='1806840'>thing</span>
  <span m='1807010'>we</span> <span m='1807150'>see</span> <span m='1808260'>is</span>
  <span m='1808450'>the</span> <span m='1808680'>applicator</span> <span m='1811350'>must</span>
  <span m='1811660'>be</span> <span m='1811760'>able</span> <span m='1811900'>to</span>
  <span m='1811960'>get</span> <span m='1812210'>the</span> <span m='1812320'>environment</span>
  <span m='1813060'>of</span> <span m='1813260'>the</span> <span m='1813340'>caller.</span>
  <span m='1814290'>The</span> <span m='1814530'>caller</span> <span m='1815440'>of
  a</span> <span m='1815670'>procedure</span> <span m='1816780'>is</span> <span m='1816930'>right</span>
  <span m='1817150'>here.</span> <span m='1819560'>If</span> <span m='1819720'>the</span>
  <span m='1819800'>expression</span> <span m='1820190'>we're</span> <span m='1820360'>evaluating
  is</span> <span m='1820830'>anpplication</span> <span m='1822720'>or a</span> <span
  m='1822900'>combination,</span> <span m='1823840'>then</span> <span m='1824140'>we're</span>
  <span m='1824230'>going</span> <span m='1824440'>to</span> <span m='1824530'>call</span>
  <span m='1824900'>a</span> <span m='1824960'>procedure</span> <span m='1825680'>which</span>
  <span m='1825890'>is</span> <span m='1825990'>the</span> <span m='1826070'>value</span>
  <span m='1826440'>of</span> <span m='1826540'>the</span> <span m='1826660'>operator.</span>
  <span m='1829840'>The</span> <span m='1830080'>environment</span> <span m='1830660'>of</span>
  <span m='1830770'>the</span> <span m='1830860'>caller</span> <span m='1832060'>is</span>
  <span m='1832200'>the</span> <span m='1832310'>environment</span> <span m='1832680'>we</span>
  <span m='1832890'>have</span> <span m='1833100'>right</span> <span m='1833310'>here,</span>
  <span m='1833580'>available</span> <span m='1834070'>now.</span> </p><p><span m='1835890'>So</span>
  <span m='1836070'>all</span> <span m='1836250'>I</span> <span m='1836340'>have</span>
  <span m='1836420'>to</span> <span m='1836510'>do</span> <span m='1836700'>is</span>
  <span m='1836850'>pass that</span> <span m='1837150'>environment</span> <span m='1838300'>to</span>
  <span m='1838430'>the</span> <span m='1838570'>applicator,</span> <span m='1840060'>to</span>
  <span m='1840170'>apply.</span> <span m='1841490'>And</span> <span m='1841720'>if</span>
  <span m='1841780'>we</span> <span m='1841880'>look</span> <span m='1841990'>at</span>
  <span m='1842110'>that</span> <span m='1842340'>here,</span> <span m='1843540'>the</span>
  <span m='1843710'>only</span> <span m='1843970'>change</span> <span m='1844310'>we</span>
  <span m='1844430'>have</span> <span m='1844570'>to</span> <span m='1844680'>make</span>
  <span m='1845810'>is</span> <span m='1846030'>that</span> <span m='1847140'>fellow</span>
  <span m='1847340'>takes</span> <span m='1847650'>that</span> <span m='1847820'>environment</span>
  <span m='1848860'>and</span> <span m='1849160'>uses</span> <span m='1849530'>that</span>
  <span m='1849720'>environment</span> <span m='1851450'>for</span> <span m='1851690'>the</span>
  <span m='1851800'>purpose</span> <span m='1852980'>of</span> <span m='1853670'>extending</span>
  <span m='1854490'>that</span> <span m='1855070'>environment</span> <span m='1857240'>when</span>
  <span m='1857460'>abiding</span> <span m='1858060'>the</span> <span m='1858260'>formal</span>
  <span m='1858630'>parameters</span> <span m='1859110'>of</span> <span m='1859170'>the</span>
  <span m='1859240'>procedure</span> <span m='1859920'>to</span> <span m='1860100'>the</span>
  <span m='1860250'>arguments</span> <span m='1860740'>that</span> <span m='1860900'>were</span>
  <span m='1860990'>passed,</span> <span m='1863870'>not</span> <span m='1864050'>an</span>
  <span m='1864180'>environment</span> <span m='1864560'>that</span> <span m='1864700'>was</span>
  <span m='1864830'>captured</span> <span m='1865260'>in</span> <span m='1865370'>the</span>
  <span m='1865460'>procedure.</span> </p><p><span m='1866810'>The</span> <span m='1867030'>reason</span>
  <span m='1867360'>why</span> <span m='1867590'>the</span> <span m='1867790'>first</span>
  <span m='1867990'>Lisps</span> <span m='1868350'>were</span> <span m='1868530'>implemented</span>
  <span m='1868960'>this</span> <span m='1869140'>way,</span> <span m='1869680'>is
  the</span> <span m='1869880'>sort</span> <span m='1870000'>of</span> <span m='1870120'>the</span>
  <span m='1870230'>obvious,</span> <span m='1870690'>accidental</span> <span m='1871310'>implementation.</span>
  <span m='1874130'>And,</span> <span m='1874320'>of</span> <span m='1874490'>course,</span>
  <span m='1874670'>as</span> <span m='1874870'>usual,</span> <span m='1875230'>people</span>
  <span m='1875480'>got</span> <span m='1875670'>used</span> <span m='1875830'>to</span>
  <span m='1875990'>it</span> <span m='1876060'>and</span> <span m='1876200'>liked</span>
  <span m='1876530'>it.</span> <span m='1877250'>And</span> <span m='1877450'>there</span>
  <span m='1877530'>were</span> <span m='1877650'>some</span> <span m='1877830'>people</span>
  <span m='1878090'>said,</span> <span m='1878410'>this</span> <span m='1878640'>is</span>
  <span m='1878730'>the</span> <span m='1878820'>way</span> <span m='1878960'>to</span>
  <span m='1879100'>do</span> <span m='1879330'>it.</span> <span m='1881590'>Unfortunately</span>
  <span m='1882300'>that</span> <span m='1882490'>causes</span> <span m='1882800'>some</span>
  <span m='1882970'>serious</span> <span m='1883520'>problems.</span> <span m='1885310'>The</span>
  <span m='1885570'>most</span> <span m='1885870'>important,</span> <span m='1886350'>serious</span>
  <span m='1886720'>problem</span> <span m='1887570'>in</span> <span m='1888470'>using</span>
  <span m='1888870'>dynamic</span> <span m='1889340'>binding</span> <span m='1891050'>is</span>
  <span m='1891240'>there's</span> <span m='1891450'>a</span> <span m='1891510'>modularity</span>
  <span m='1892240'>crisis</span> <span m='1892710'>that's</span> <span m='1892890'>involved</span>
  <span m='1893300'>it.</span> </p><p><span m='1895460'>If</span> <span m='1895610'>two</span>
  <span m='1895780'>people are</span> <span m='1896100'>working</span> <span m='1896410'>together</span>
  <span m='1896700'>on</span> <span m='1896830'>some</span> <span m='1896980'>big</span>
  <span m='1897160'>system,</span> <span m='1898370'>then</span> <span m='1898790'>an</span>
  <span m='1898900'>important</span> <span m='1899370'>thing</span> <span m='1899560'>to</span>
  <span m='1899670'>want</span> <span m='1900400'>is</span> <span m='1900550'>that</span>
  <span m='1900680'>the</span> <span m='1900780'>names</span> <span m='1901170'>used</span>
  <span m='1901420'>by</span> <span m='1901580'>each</span> <span m='1901770'>one</span>
  <span m='1903070'>don't</span> <span m='1903260'>interfere</span> <span m='1903610'>with</span>
  <span m='1903710'>the</span> <span m='1903790'>names</span> <span m='1904100'>of</span>
  <span m='1904170'>the</span> <span m='1904380'>other.</span> <span m='1907930'>It's</span>
  <span m='1908100'>important</span> <span m='1908580'>that</span> <span m='1908700'>when</span>
  <span m='1908830'>I</span> <span m='1909000'>invent</span> <span m='1909430'>some</span>
  <span m='1909960'>segment</span> <span m='1910260'>of</span> <span m='1910360'>code</span>
  <span m='1911060'>that</span> <span m='1911260'>no</span> <span m='1911370'>one</span>
  <span m='1911540'>can</span> <span m='1911670'>make</span> <span m='1911870'>my</span>
  <span m='1912080'>code</span> <span m='1912360'>stop</span> <span m='1912640'>working</span>
  <span m='1913980'>by</span> <span m='1914100'>using</span> <span m='1914480'>my</span>
  <span m='1914650'>names</span> <span m='1914985'>that</span> <span m='1915320'>I
  use</span> <span m='1915630'>internal</span> <span m='1915970'>to</span> <span m='1916040'>my</span>
  <span m='1916210'>code,</span> <span m='1916760'>internal</span> <span m='1917200'>to</span>
  <span m='1917280'>his</span> <span m='1917490'>code.</span> </p><p><span m='1919850'>However,</span>
  <span m='1921080'>dynamic</span> <span m='1921510'>binding</span> <span m='1921960'>violates</span>
  <span m='1922550'>that</span> <span m='1922760'>particular</span> <span m='1923140'>modularity</span>
  <span m='1923730'>constraint</span> <span m='1924300'>in</span> <span m='1924440'>a</span>
  <span m='1924490'>clear</span> <span m='1924790'>way.</span> <span m='1926670'>Consider,</span>
  <span m='1927270'>for</span> <span m='1927470'>example,</span> <span m='1929190'>what</span>
  <span m='1929360'>happens</span> <span m='1929760'>over</span> <span m='1929980'>here.</span>
  <span m='1932540'>Suppose</span> <span m='1933040'>it</span> <span m='1933140'>was</span>
  <span m='1933250'>the</span> <span m='1933350'>case</span> <span m='1935500'>that</span>
  <span m='1935630'>I</span> <span m='1935750'>decided</span> <span m='1937430'>to</span>
  <span m='1937590'>change</span> <span m='1938340'>the</span> <span m='1938510'>word</span>
  <span m='1938890'>next.</span> <span m='1939810'>Supposing</span> <span m='1940070'>somebody</span>
  <span m='1940600'>is</span> <span m='1940700'>writing</span> <span m='1944010'>sum,</span>
  <span m='1945190'>and</span> <span m='1945370'>somebody</span> <span m='1945630'>else</span>
  <span m='1945820'>is</span> <span m='1945870'>going</span> <span m='1945950'>to</span>
  <span m='1946030'>use</span> <span m='1946310'>sum.</span> </p><p><span m='1948970'>The</span>
  <span m='1949300'>writer of</span> <span m='1949790'>sum</span> <span m='1950470'>has</span>
  <span m='1950780'>a</span> <span m='1950850'>choice</span> <span m='1951170'>of</span>
  <span m='1951240'>what</span> <span m='1951410'>names</span> <span m='1951680'>he</span>
  <span m='1951790'>may</span> <span m='1951940'>use.</span> <span m='1953790'>Let's</span>
  <span m='1953940'>say,</span> <span m='1954040'>I'm</span> <span m='1954260'>that</span>
  <span m='1954470'>writer.</span> <span m='1956760'>Well,</span> <span m='1957170'>by</span>
  <span m='1957380'>gosh,</span> <span m='1957800'>just</span> <span m='1957970'>happens</span>
  <span m='1958300'>I</span> <span m='1958410'>didn't</span> <span m='1958530'>want</span>
  <span m='1958610'>to</span> <span m='1958680'>call</span> <span m='1958860'>this</span>
  <span m='1959030'>next.</span> <span m='1959300'>I</span> <span m='1959350'>called</span>
  <span m='1959700'>it</span> <span m='1960000'>n.</span> <span m='1961500'>So</span>
  <span m='1961810'>all</span> <span m='1962090'>places</span> <span m='1962410'>where</span>
  <span m='1962580'>you  see</span> <span m='1962760'>next,</span> <span m='1964340'>I</span>
  <span m='1964480'>called</span> <span m='1964870'>it</span> <span m='1965180'>n.</span>
  <span m='1968140'>Whoops.</span> <span m='1969940'>I</span> <span m='1970080'>changed</span>
  <span m='1970400'>nothing</span> <span m='1970670'>about</span> <span m='1970780'>the</span>
  <span m='1970890'>specifications</span> <span m='1971185'>of</span> <span m='1971480'>this</span>
  <span m='1971700'>program,</span> <span m='1973430'>but</span> <span m='1973610'>this</span>
  <span m='1973770'>program</span> <span m='1974120'>stops</span> <span m='1974420'>working.</span>
  <span m='1976110'>Not</span> <span m='1976260'>only</span> <span m='1976420'>that,</span>
  <span m='1976590'>unfortunately,</span> <span m='1977030'>this</span> <span m='1977190'>one</span>
  <span m='1977350'>does</span> <span m='1977570'>too.</span> </p><p><span m='1979730'>Why</span>
  <span m='1979950'>do</span> <span m='1980210'>these</span> <span m='1980490'>programs</span>
  <span m='1980660'>stop</span> <span m='1980960'>working?</span> <span m='1982260'>Well,
  it's</span> <span m='1982530'>sort</span> <span m='1982680'>of</span> <span m='1982770'>clear.</span>
  <span m='1984480'>Instead</span> <span m='1984850'>of</span> <span m='1986980'>chasing</span>
  <span m='1987480'>out</span> <span m='1987790'>the</span> <span m='1988320'>value</span>
  <span m='1988830'>of</span> <span m='1988990'>the</span> <span m='1989130'>n</span>
  <span m='1989380'>that</span> <span m='1989490'>occurs</span> <span m='1989810'>in</span>
  <span m='1989890'>nth</span> <span m='1990110'>power</span> <span m='1990970'>over</span>
  <span m='1991180'>here</span> <span m='1992650'>or</span> <span m='1992940'>over</span>
  <span m='1993100'>here,</span> <span m='1994870'>through</span> <span m='1995430'>the</span>
  <span m='1996030'>environment</span> <span m='1996450'>of</span> <span m='1996490'>definition,</span>
  <span m='1997200'>where</span> <span m='1997350'>this</span> <span m='1997570'>one</span>
  <span m='1998020'>is</span> <span m='1998260'>always</span> <span m='1998700'>linked</span>
  <span m='1998930'>to</span> <span m='1999010'>this</span> <span m='1999220'>one,</span>
  <span m='1999940'>if it</span> <span m='2000070'>was</span> <span m='2000240'>through</span>
  <span m='2000380'>the</span> <span m='2000480'>environment</span> <span m='2000880'>of</span>
  <span m='2000940'>definition,</span> <span m='2001660'>because</span> <span m='2002110'>here</span>
  <span m='2002570'>is</span> <span m='2002770'>the</span> <span m='2002870'>definition.</span>
  <span m='2004370'>This</span> <span m='2004580'>lambda</span> <span m='2004950'>expression</span>
  <span m='2005460'>was</span> <span m='2005630'>executed</span> <span m='2006560'>in</span>
  <span m='2006790'>the</span> <span m='2006890'>environment</span> <span m='2007320'>where</span>
  <span m='2007450'>that</span> <span m='2007650'>n</span> <span m='2007880'>was</span>
  <span m='2008020'>defined.</span> <span m='2010700'>If</span> <span m='2010880'>instead</span>
  <span m='2011180'>of</span> <span m='2011270'>doing</span> <span m='2011540'>that,</span>
  <span m='2012040'>I have</span> <span m='2012350'>to chase</span> <span m='2012630'>through</span>
  <span m='2012780'>the</span> <span m='2012870'>call</span> <span m='2013150'>chain,</span>
  <span m='2014486'>then</span> <span m='2014860'>look</span> <span m='2015080'>what</span>
  <span m='2015140'>horrible</span> <span m='2015520'>thing</span> <span m='2015720'>happens.</span>
  </p><p><span m='2017320'>Well,</span> <span m='2018800'>this</span> <span m='2019010'>was</span>
  <span m='2019160'>called</span> <span m='2019440'>from</span> <span m='2019580'>inside</span>
  <span m='2020030'>sum</span> <span m='2020470'>as</span> <span m='2020700'>term,</span>
  <span m='2021980'>term</span> <span m='2022210'>a.</span> <span m='2024780'>I'm</span>
  <span m='2024930'>looking</span> <span m='2025190'>for a</span> <span m='2025330'>value</span>
  <span m='2025690'>of</span> <span m='2025740'>n.</span> <span m='2027350'>Instead
  of</span> <span m='2027620'>getting</span> <span m='2027860'>this</span> <span m='2028060'>one,</span>
  <span m='2028900'>I</span> <span m='2029010'>get</span> <span m='2029210'>that</span>
  <span m='2029450'>one.</span> <span m='2030700'>So</span> <span m='2030850'>by</span>
  <span m='2031050'>changing the</span> <span m='2031310'>insides</span> <span m='2031580'>of</span>
  <span m='2031850'>this</span> <span m='2032030'>program,</span> <span m='2032870'>this</span>
  <span m='2033110'>program</span> <span m='2033430'>stops</span> <span m='2033720'>working.</span>
  <span m='2036770'>So</span> <span m='2037000'>I</span> <span m='2037080'>no</span>
  <span m='2037260'>longer</span> <span m='2037580'>have</span> <span m='2037890'>a</span>
  <span m='2037950'>quantifier,</span> <span m='2038770'>as</span> <span m='2038940'>I</span>
  <span m='2039020'>described</span> <span m='2039490'>before.</span> <span m='2042700'>The</span>
  <span m='2042800'>lambda</span> <span m='2043160'>symbol</span> <span m='2043500'>is</span>
  <span m='2043580'>supposed</span> <span m='2043770'>to</span> <span m='2043950'>be</span>
  <span m='2044250'>a</span> <span m='2044370'>quantifier.</span> <span m='2045430'>A</span>
  <span m='2045710'>thing</span> <span m='2045870'>which</span> <span m='2046030'>has
  the</span> <span m='2046090'>property</span> <span m='2047520'>that</span> <span
  m='2047810'>the</span> <span m='2048100'>names</span> <span m='2048590'>that</span>
  <span m='2049179'>are</span> <span m='2049300'>bound</span> <span m='2049650'>by</span>
  <span m='2049860'>it</span> <span m='2050580'>are</span> <span m='2050780'>unimportant,</span>
  <span m='2052699'>that</span> <span m='2052800'>I</span> <span m='2052889'>can</span>
  <span m='2053489'>uniformly</span> <span m='2054060'>substitute</span> <span m='2054489'>any</span>
  <span m='2054739'>names</span> <span m='2055110'>for</span> <span m='2055219'>these</span>
  <span m='2056850'>throughout</span> <span m='2057380'>this</span> <span m='2057560'>thing,</span>
  <span m='2057760'>so</span> <span m='2057880'>long</span> <span m='2058070'>as</span>
  <span m='2058110'>they</span> <span m='2058230'>don't</span> <span m='2058370'>occur
  in</span> <span m='2058770'>here,</span> <span m='2059080'>the</span> <span m='2059320'>new</span>
  <span m='2059540'>names,</span> <span m='2060920'>and</span> <span m='2061139'>the</span>
  <span m='2061199'>meaning</span> <span m='2061489'>of</span> <span m='2061590'>this</span>
  <span m='2061699'>expression</span> <span m='2062120'>should</span> <span m='2062250'>remain</span>
  <span m='2062510'>unchanged.</span> </p><p><span m='2064040'>I've</span> <span m='2064239'>just</span>
  <span m='2064520'>changed</span> <span m='2064770'>the</span> <span m='2064840'>meaning</span>
  <span m='2065110'>of</span> <span m='2065150'>the</span> <span m='2065190'>expression</span>
  <span m='2065600'>by</span> <span m='2065719'>changing</span> <span m='2066050'>the</span>
  <span m='2066429'>one</span> <span m='2066570'>of</span> <span m='2066639'>the</span>
  <span m='2066719'>names.</span> <span m='2068690'>So</span> <span m='2068889'>lambda</span>
  <span m='2069199'>is</span> <span m='2069330'>no</span> <span m='2069480'>longer
  a</span> <span m='2069750'>well</span> <span m='2070040'>defined</span> <span m='2070460'>idea.</span>
  <span m='2072170'>It's</span> <span m='2072250'>a</span> <span m='2072310'>very</span>
  <span m='2072560'>serious</span> <span m='2072960'>problem.</span> <span m='2074550'>So</span>
  <span m='2074760'>for</span> <span m='2074850'>that</span> <span m='2075080'>reason,</span>
  <span m='2076730'>I</span> <span m='2076909'>and</span> <span m='2077060'>my</span>
  <span m='2077230'>buddies</span> <span m='2078370'>have</span> <span m='2080070'>given</span>
  <span m='2080370'>up</span> <span m='2080580'>this</span> <span m='2080850'>particular</span>
  <span m='2081389'>kind</span> <span m='2081659'>of</span> <span m='2081760'>abstraction,</span>
  <span m='2083179'>which</span> <span m='2083400'>I</span> <span m='2083469'>would</span>
  <span m='2083650'>like</span> <span m='2083880'>to</span> <span m='2084130'>have,</span>
  <span m='2085710'>in</span> <span m='2085820'>favor</span> <span m='2086150'>of</span>
  <span m='2086219'>a</span> <span m='2086280'>modularity</span> <span m='2086969'>principle.</span>
  </p><p><span m='2088090'>But</span> <span m='2088330'>this</span> <span m='2088409'>is</span>
  <span m='2088510'>the</span> <span m='2088570'>kind</span> <span m='2088800'>of</span>
  <span m='2088860'>experiment</span> <span m='2089500'>you</span> <span m='2089620'>can</span>
  <span m='2089790'>do</span> <span m='2092070'>if</span> <span m='2092190'>you</span>
  <span m='2092310'>want</span> <span m='2092420'>to</span> <span m='2092530'>play</span>
  <span m='2092780'>with</span> <span m='2092909'>these</span> <span m='2093060'>interpreters.</span>
  <span m='2094530'>You</span> <span m='2095020'>can</span> <span m='2095120'>try</span>
  <span m='2095449'>them out</span> <span m='2095600'>this</span> <span m='2095739'>way,</span>
  <span m='2095889'>that</span> <span m='2096090'>way,</span> <span m='2096230'>and
  the</span> <span m='2096340'>other</span> <span m='2096489'>way.</span> <span m='2098270'>You</span>
  <span m='2098460'>see</span> <span m='2099010'>what</span> <span m='2099250'>makes</span>
  <span m='2099430'>a</span> <span m='2099480'>nicer</span> <span m='2099780'>language.</span>
  <span m='2102680'>So</span> <span m='2102930'>that's</span> <span m='2103050'>a</span>
  <span m='2103100'>very</span> <span m='2103310'>important</span> <span m='2103610'>thing</span>
  <span m='2103740'>to</span> <span m='2103800'>be</span> <span m='2103890'>able</span>
  <span m='2104020'>to</span> <span m='2104110'>do.</span> <span m='2104990'>Now,</span>
  <span m='2105280'>I</span> <span m='2105530'>would</span> <span m='2105780'>like</span>
  <span m='2105970'>to</span> <span m='2106040'>give</span> <span m='2106190'>you</span>
  <span m='2106350'>a</span> <span m='2106430'>feeling</span> <span m='2106720'>for</span>
  <span m='2106920'>I</span> <span m='2106970'>think</span> <span m='2107150'>the</span>
  <span m='2107260'>right</span> <span m='2107580'>thing</span> <span m='2107780'>to</span>
  <span m='2107880'>do</span> <span m='2108090'>is</span> <span m='2108270'>here.</span>
  </p><p><span m='2110880'>How are</span> <span m='2111130'>you</span> <span m='2111260'>going</span>
  <span m='2111490'>to</span> <span m='2111640'>I</span> <span m='2111950'>get</span>
  <span m='2112180'>this</span> <span m='2112390'>kind</span> <span m='2112730'>of</span>
  <span m='2113250'>power</span> <span m='2113790'>in a</span> <span m='2114190'>lexical</span>
  <span m='2114780'>system?</span> <span m='2116280'>And</span> <span m='2116390'>the</span>
  <span m='2116510'>answer</span> <span m='2116870'>is,</span> <span m='2116960'>of</span>
  <span m='2117200'>course,</span> <span m='2117570'>what</span> <span m='2117700'>I</span>
  <span m='2117820'>really</span> <span m='2118180'>want</span> <span m='2118440'>is</span>
  <span m='2118550'>a</span> <span m='2118610'>something</span> <span m='2118940'>that</span>
  <span m='2119140'>makes</span> <span m='2119420'>up</span> <span m='2119570'>for</span>
  <span m='2119690'>me</span> <span m='2120800'>an</span> <span m='2120930'>exponentiator</span>
  <span m='2121640'>for a</span> <span m='2121790'>particular</span> <span m='2122240'>n.</span>
  <span m='2123690'>Given</span> <span m='2123930'>an</span> <span m='2124040'>n,</span>
  <span m='2124290'>it</span> <span m='2124420'>will</span> <span m='2124540'>make</span>
  <span m='2124740'>me</span> <span m='2124900'>an</span> <span m='2125140'>exponentiator.</span>
  <span m='2126280'>Oh, but</span> <span m='2126530'>that's</span> <span m='2126790'>easy</span>
  <span m='2127030'>too.</span> <span m='2128170'>In other</span> <span m='2128330'>words,</span>
  <span m='2128420'>I</span> <span m='2128520'>can</span> <span m='2128650'>write</span>
  <span m='2128840'>my</span> <span m='2129760'>program</span> <span m='2130210'>this</span>
  <span m='2130370'>way.</span> <span m='2135450'>I'm</span> <span m='2135725'>going</span>
  <span m='2136000'>to define</span> <span m='2136270'>a thing</span> <span m='2136480'>called</span>
  <span m='2137120'>PGEN,</span> <span m='2140320'>which</span> <span m='2140550'>is</span>
  <span m='2140640'>a</span> <span m='2140720'>procedure</span> <span m='2141045'>of</span>
  <span m='2141370'>n</span> <span m='2143200'>which</span> <span m='2143460'>produces</span>
  <span m='2144000'>for</span> <span m='2144210'>me</span> <span m='2144420'>an</span>
  <span m='2144830'>exponentiator.</span> <span m='2150240'>--x</span> <span m='2150540'>to</span>
  <span m='2150660'>the</span> <span m='2150860'>n.</span> </p><p><span m='2156900'>Given</span>
  <span m='2157160'>that</span> <span m='2157270'>I</span> <span m='2157390'>have</span>
  <span m='2157690'>that,</span> <span m='2158590'>then</span> <span m='2158870'>I</span>
  <span m='2158980'>can</span> <span m='2159170'>capture</span> <span m='2159550'>the</span>
  <span m='2159690'>abstraction</span> <span m='2160240'>I</span> <span m='2160310'>wanted</span>
  <span m='2161540'>even</span> <span m='2161760'>better,</span> <span m='2162180'>because</span>
  <span m='2162530'>now it's</span> <span m='2162730'>encapsulated</span> <span m='2163470'>in</span>
  <span m='2163570'>a</span> <span m='2163630'>way</span> <span m='2164090'>where</span>
  <span m='2164340'>I</span> <span m='2164400'>can't</span> <span m='2164700'>be</span>
  <span m='2164800'>destroyed</span> <span m='2165500'>by</span> <span m='2165700'>a</span>
  <span m='2165760'>change</span> <span m='2166030'>of</span> <span m='2166110'>names.</span>
  <span m='2167890'>I</span> <span m='2167970'>can</span> <span m='2168070'>define</span>
  <span m='2171500'>some</span> <span m='2171860'>powers</span> <span m='2177120'>to</span>
  <span m='2177460'>be</span> <span m='2177650'>a</span> <span m='2177750'>procedure</span>
  <span m='2178650'>again</span> <span m='2179020'>of</span> <span m='2179210'>a,</span>
  <span m='2179690'>b,</span> <span m='2180070'>and</span> <span m='2180200'>n</span>
  <span m='2181650'>which</span> <span m='2181890'>is</span> <span m='2182040'>the</span>
  <span m='2182140'>sum</span> <span m='2184260'>of</span> <span m='2185790'>the</span>
  <span m='2185890'>term</span> <span m='2186220'>function</span> <span m='2186910'>generated</span>
  <span m='2187570'>by</span> <span m='2187700'>using</span> <span m='2188070'>this</span>
  <span m='2188220'>generator,</span> <span m='2189340'>PGEN,</span> <span m='2191720'>n,</span>
  <span m='2194460'>with</span> <span m='2195000'>a,</span> <span m='2195630'>incrementer,</span>
  <span m='2196240'>and</span> <span m='2197330'>b.</span> <span m='2202490'>And</span>
  <span m='2202640'>I</span> <span m='2202800'>can</span> <span m='2202910'>define</span>
  <span m='2206610'>the</span> <span m='2206940'>product</span> <span m='2207280'>of</span>
  <span m='2207360'>powers</span> <span m='2213920'>to</span> <span m='2214320'>be</span>
  <span m='2214800'>a</span> <span m='2215170'>procedure</span> <span m='2216860'>of</span>
  <span m='2217100'>a,</span> <span m='2217490'>b,</span> <span m='2218010'>and</span>
  <span m='2218240'>n</span> <span m='2219870'>which</span> <span m='2220070'>is</span>
  <span m='2220180'>the</span> <span m='2220350'>product</span> <span m='2223920'>PGEN,</span>
  <span m='2227170'>n,</span> <span m='2227920'>with</span> <span m='2228150'>a,</span>
  <span m='2229010'>increment,</span> <span m='2229500'>and</span> <span m='2229740'>b.</span>
  </p><p><span m='2231150'>Now,</span> <span m='2231500'>of</span> <span m='2231650'>course,</span>
  <span m='2231890'>this is</span> <span m='2232070'>a</span> <span m='2232140'>very</span>
  <span m='2232410'>simple</span> <span m='2232750'>example</span> <span m='2233600'>where</span>
  <span m='2234050'>this</span> <span m='2234340'>object</span> <span m='2234890'>that
  I'm</span> <span m='2235030'>trying</span> <span m='2235220'>to</span> <span m='2235310'>abstract</span>
  <span m='2235630'>over</span> <span m='2235850'>is</span> <span m='2235910'>small.</span>
  <span m='2237280'>But</span> <span m='2237500'>it</span> <span m='2237590'>could
  be</span> <span m='2237700'>a</span> <span m='2237750'>100</span> <span m='2237990'>lines</span>
  <span m='2238250'>of</span> <span m='2238310'>code.</span> <span m='2240100'>And</span>
  <span m='2240350'>so,</span> <span m='2240700'>the</span> <span m='2241120'>purpose</span>
  <span m='2241500'>of</span> <span m='2241730'>this</span> <span m='2242090'>is,</span>
  <span m='2242230'>of</span> <span m='2242350'>course,</span> <span m='2242830'>to</span>
  <span m='2243040'>make</span> <span m='2243240'>it</span> <span m='2243380'>simple.</span>
  <span m='2243670'>I'd</span> <span m='2243750'>give</span> <span m='2243900'>a</span>
  <span m='2244000'>name</span> <span m='2244270'>to</span> <span m='2244440'>it,</span>
  <span m='2244790'>it's</span> <span m='2244980'>just</span> <span m='2245210'>that</span>
  <span m='2245270'>here</span> <span m='2245510'>it's a</span> <span m='2245630'>parameterized</span>
  <span m='2246490'>name.</span> <span m='2248200'>It's</span> <span m='2248360'>a</span>
  <span m='2248410'>name</span> <span m='2248680'>that</span> <span m='2248810'>depends</span>
  <span m='2249190'>upon,</span> <span m='2249500'>explicitly,</span> <span m='2250400'>the</span>
  <span m='2250860'>lexically</span> <span m='2251460'>apparent</span> <span m='2252820'>value</span>
  <span m='2253240'>of</span> <span m='2253610'>n.</span> <span m='2257130'>So</span>
  <span m='2257270'>you</span> <span m='2257340'>can</span> <span m='2257460'>think</span>
  <span m='2257620'>of</span> <span m='2257730'>this</span> <span m='2257850'>as a</span>
  <span m='2257940'>long</span> <span m='2258280'>name.</span> <span m='2260210'>And</span>
  <span m='2260310'>here,</span> <span m='2260490'>I've</span> <span m='2260550'>solved</span>
  <span m='2260850'>my</span> <span m='2260980'>problem</span> <span m='2263520'>by</span>
  <span m='2263640'>naming</span> <span m='2264370'>the</span> <span m='2264550'>term</span>
  <span m='2265150'>generation</span> <span m='2266180'>procedures</span> <span m='2268380'>within</span>
  <span m='2268630'>an</span> <span m='2268820'>n in</span> <span m='2268990'>them.</span>
  </p><p><span m='2275080'>Are there any</span> <span m='2275350'>questions?</span>
  <span m='2277140'>Oh,</span> <span m='2277370'>yes,</span> <span m='2277980'>David.</span>
  </p><p><span m='2278380'>AUDIENCE:</span> <span m='2278730'>Is</span> <span m='2278870'>the</span>
  <span m='2279070'>only</span> <span m='2279270'>solution</span> <span m='2281230'>to</span>
  <span m='2283010'>the</span> <span m='2283170'>problem</span> <span m='2283660'>you</span>
  <span m='2283820'>raise</span> <span m='2284470'>to</span> <span m='2284820'>create</span>
  <span m='2285300'>another</span> <span m='2285920'>procedure?</span> <span m='2286470'>In</span>
  <span m='2286560'>other</span> <span m='2286690'>words,</span> <span m='2287000'>can
  this</span> <span m='2287250'>only</span> <span m='2287470'>work in</span> <span
  m='2287850'>languages</span> <span m='2288470'>that</span> <span m='2288660'>are</span>
  <span m='2289020'>capable</span> <span m='2289620'>of</span> <span m='2289720'>defining</span>
  <span m='2290360'>objects</span> <span m='2290760'>as</span> <span m='2290870'>procedures?</span>
  </p><p><span m='2292402'>PROFESSOR:</span> <span m='2292810'>Oh,</span> <span m='2293210'>I</span>
  <span m='2293420'>see.</span> <span m='2296530'>My</span> <span m='2296800'>solution</span>
  <span m='2297570'>to</span> <span m='2298520'>making</span> <span m='2298900'>this</span>
  <span m='2299020'>abstraction,</span> <span m='2300170'>when</span> <span m='2300310'>I</span>
  <span m='2300420'>didn't</span> <span m='2300530'>want</span> <span m='2300730'>include</span>
  <span m='2301030'>the</span> <span m='2301120'>procedure</span> <span m='2301650'>inside</span>
  <span m='2302220'>the</span> <span m='2302290'>body,</span> <span m='2303240'>depends</span>
  <span m='2303660'>upon</span> <span m='2303950'>my</span> <span m='2304070'>ability</span>
  <span m='2304520'>to</span> <span m='2304760'>return</span> <span m='2305120'>a</span>
  <span m='2305180'>procedure</span> <span m='2305730'>or</span> <span m='2306140'>export</span>
  <span m='2306590'>one.</span> <span m='2308190'>And</span> <span m='2308360'>that's</span>
  <span m='2308550'>right.</span> <span m='2310410'>If</span> <span m='2310580'>I</span>
  <span m='2310730'>don't</span> <span m='2310880'>have</span> <span m='2311110'>that,</span>
  <span m='2312330'>then</span> <span m='2312490'>I</span> <span m='2312570'>just</span>
  <span m='2312720'>don't</span> <span m='2312880'>have</span> <span m='2313090'>this</span>
  <span m='2313230'>ability</span> <span m='2313550'>to</span> <span m='2313610'>make</span>
  <span m='2313800'>an</span> <span m='2314040'>abstraction</span> <span m='2314440'>in</span>
  <span m='2314550'>a</span> <span m='2314600'>way</span> <span m='2318950'>where</span>
  <span m='2319090'>I</span> <span m='2319160'>don't</span> <span m='2319320'>have</span>
  <span m='2319490'>possibilities</span> <span m='2319850'>of</span> <span m='2320000'>symbol</span>
  <span m='2320270'>conflicts</span> <span m='2320690'>that</span> <span m='2320810'>were</span>
  <span m='2320930'>unanticipated.</span> <span m='2323000'>That's</span> <span m='2323210'>right.</span>
  <span m='2325610'>I</span> <span m='2325780'>consider</span> <span m='2326580'>being</span>
  <span m='2326890'>able</span> <span m='2327050'>to</span> <span m='2327200'>return</span>
  <span m='2327830'>the</span> <span m='2327960'>procedural</span> <span m='2328430'>value</span>
  <span m='2332690'>and,</span> <span m='2332870'>therefore,</span> <span m='2336070'>to</span>
  <span m='2336210'>sort</span> <span m='2336320'>of</span> <span m='2336430'>have</span>
  <span m='2336690'>first</span> <span m='2336940'>class</span> <span m='2337230'>procedures,</span>
  <span m='2337780'>in</span> <span m='2337880'>general,</span> <span m='2339130'>as</span>
  <span m='2339350'>being</span> <span m='2339570'>essential</span> <span m='2340700'>to</span>
  <span m='2340840'>doing</span> <span m='2341090'>very</span> <span m='2341310'>good</span>
  <span m='2341500'>modular</span> <span m='2341840'>programming.</span> </p><p><span
  m='2343700'>Now,</span> <span m='2343860'>indeed</span> <span m='2344400'>there</span>
  <span m='2344660'>are</span> <span m='2344690'>many</span> <span m='2344990'>other</span>
  <span m='2345250'>ways</span> <span m='2345530'>to</span> <span m='2345630'>skin</span>
  <span m='2345900'>this</span> <span m='2346110'>cat.</span> <span m='2347440'>What</span>
  <span m='2347560'>you</span> <span m='2347690'>can</span> <span m='2347810'>do</span>
  <span m='2347940'>is</span> <span m='2348040'>take</span> <span m='2349130'>for</span>
  <span m='2349340'>each</span> <span m='2349520'>of</span> <span m='2349620'>the</span>
  <span m='2349720'>bad</span> <span m='2350070'>things</span> <span m='2350380'>that</span>
  <span m='2350500'>you</span> <span m='2350630'>have</span> <span m='2350840'>to</span>
  <span m='2351080'>worry</span> <span m='2351380'>about,</span> <span m='2352430'>you
  can</span> <span m='2352490'>make</span> <span m='2352640'>a</span> <span m='2352680'>special</span>
  <span m='2353010'>feature</span> <span m='2353420'>that</span> <span m='2353570'>covers</span>
  <span m='2353890'>that</span> <span m='2354710'>thing.</span> <span m='2355840'>You</span>
  <span m='2355940'>can</span> <span m='2356040'>make</span> <span m='2356200'>a</span>
  <span m='2356260'>package</span> <span m='2356700'>system.</span> <span m='2357930'>You
  can</span> <span m='2358010'>make</span> <span m='2358200'>a</span> <span m='2358240'>module</span>
  <span m='2358730'>system</span> <span m='2359110'>as</span> <span m='2359330'>in</span>
  <span m='2359450'>Ada,</span> <span m='2359660'>et</span> <span m='2359910'>cetera.</span>
  <span m='2362240'>And</span> <span m='2362430'>all</span> <span m='2362590'>of</span>
  <span m='2362750'>those</span> <span m='2363000'>work,</span> <span m='2363280'>or</span>
  <span m='2363510'>they</span> <span m='2363640'>cover</span> <span m='2363870'>little</span>
  <span m='2364130'>regions</span> <span m='2364540'>of</span> <span m='2365015'>it.</span>
  <span m='2366440'>The</span> <span m='2366620'>thing</span> <span m='2366830'>is</span>
  <span m='2366960'>that</span> <span m='2367090'>returning</span> <span m='2367410'>procedures</span>
  <span m='2367860'>as</span> <span m='2368020'>values</span> <span m='2368430'>cover</span>
  <span m='2368650'>all</span> <span m='2368820'>of</span> <span m='2368980'>those</span>
  <span m='2369220'>problems.</span> <span m='2372700'>And</span> <span m='2372900'>so</span>
  <span m='2373230'>it's</span> <span m='2373370'>the</span> <span m='2373450'>simplest</span>
  <span m='2373890'>mechanism</span> <span m='2375250'>that</span> <span m='2375820'>gives</span>
  <span m='2375990'>you</span> <span m='2376100'>the</span> <span m='2376230'>best</span>
  <span m='2377150'>modularity,</span> <span m='2379260'>gives you</span> <span m='2379500'>all</span>
  <span m='2379770'>of the</span> <span m='2379860'>known</span> <span m='2380110'>modularity</span>
  <span m='2380670'>mechanisms.</span> </p><p><span m='2385590'>Well,</span> <span
  m='2385900'>I</span> <span m='2385960'>suppose it's</span> <span m='2386290'>time</span>
  <span m='2386480'>for</span> <span m='2386590'>the</span> <span m='2386700'>next</span>
  <span m='2386950'>break,</span> <span m='2387420'>thank</span> <span m='2387660'>you.</span>
  </p><p><span m='2388248'>[MUSIC PLAYING]</span> </p><p><span m='2441871'>PROFESSOR:</span>
  <span m='2442390'>Well,</span> <span m='2442500'>yesterday</span> <span m='2442980'>when</span>
  <span m='2443120'>you</span> <span m='2443240'>learned</span> <span m='2443440'>about</span>
  <span m='2443690'>streams,</span> <span m='2445880'>Hal</span> <span m='2446290'>worried</span>
  <span m='2446770'>to</span> <span m='2446860'>you</span> <span m='2447100'>about</span>
  <span m='2449380'>the</span> <span m='2449810'>order</span> <span m='2450150'>of</span>
  <span m='2450250'>evaluation</span> <span m='2452110'>and</span> <span m='2452270'>delayed</span>
  <span m='2452630'>arguments</span> <span m='2453130'>to</span> <span m='2453240'>procedures.</span>
  <span m='2455420'>The</span> <span m='2455830'>way</span> <span m='2456040'>we</span>
  <span m='2456840'>played</span> <span m='2457090'>with</span> <span m='2457270'>streams</span>
  <span m='2457650'>yesterday,</span> <span m='2460110'>it</span> <span m='2460410'>was</span>
  <span m='2460570'>the</span> <span m='2460620'>responsibility</span> <span m='2461480'>of</span>
  <span m='2461590'>the</span> <span m='2461680'>caller</span> <span m='2463320'>and</span>
  <span m='2463450'>the</span> <span m='2463590'>callee</span> <span m='2465500'>to</span>
  <span m='2465910'>both</span> <span m='2466230'>agree</span> <span m='2467170'>that
  an</span> <span m='2467740'>argument</span> <span m='2468110'>was</span> <span m='2468240'>delayed,</span>
  <span m='2469165'>and</span> <span m='2469620'>the</span> <span m='2469730'>callee</span>
  <span m='2470100'>must</span> <span m='2471670'>force</span> <span m='2472060'>the</span>
  <span m='2472180'>argument</span> <span m='2472520'>if</span> <span m='2472630'>it</span>
  <span m='2472710'>needs</span> <span m='2472960'>the</span> <span m='2473100'>answer.</span>
  <span m='2475250'>So</span> <span m='2475310'>there</span> <span m='2475590'>had
  to</span> <span m='2475720'>be a</span> <span m='2475780'>lot</span> <span m='2475960'>of</span>
  <span m='2476020'>hand</span> <span m='2476300'>shaking</span> <span m='2477160'>between</span>
  <span m='2477940'>the</span> <span m='2478400'>designer</span> <span m='2478990'>of
  a</span> <span m='2479060'>procedure</span> <span m='2480070'>and</span> <span m='2480320'>user</span>
  <span m='2480710'>of</span> <span m='2480850'>it</span> <span m='2483330'>over</span>
  <span m='2483590'>delayedness.</span> </p><p><span m='2486100'>That</span> <span
  m='2486680'>turns</span> <span m='2486900'>out,</span> <span m='2487020'>of</span>
  <span m='2487160'>course,</span> <span m='2487310'>to</span> <span m='2487400'>be</span>
  <span m='2487550'>a</span> <span m='2487750'>fairly</span> <span m='2488040'>bad</span>
  <span m='2488340'>thing,</span> <span m='2489510'>it</span> <span m='2489670'>works</span>
  <span m='2489920'>all</span> <span m='2490060'>right</span> <span m='2490270'>with</span>
  <span m='2490400'>streams.</span> <span m='2491810'>But</span> <span m='2491950'>as</span>
  <span m='2492030'>a</span> <span m='2492110'>general</span> <span m='2492490'>thing,</span>
  <span m='2493020'>what you</span> <span m='2493220'>want</span> <span m='2493470'>is</span>
  <span m='2495020'>an</span> <span m='2495160'>idea</span> <span m='2495530'>to</span>
  <span m='2495610'>have</span> <span m='2495710'>a</span> <span m='2495810'>locus,</span>
  <span m='2496510'>a</span> <span m='2496620'>decision,</span> <span m='2497080'>a</span>
  <span m='2497140'>design</span> <span m='2497520'>decision</span> <span m='2497970'>in</span>
  <span m='2498040'>general,</span> <span m='2498715'>to</span> <span m='2498970'>have</span>
  <span m='2499200'>a</span> <span m='2499270'>place</span> <span m='2499620'>where</span>
  <span m='2499810'>it's</span> <span m='2499940'>made,</span> <span m='2500580'>explicitly,</span>
  <span m='2501670'>and</span> <span m='2501920'>notated</span> <span m='2503140'>in</span>
  <span m='2503250'>a</span> <span m='2503300'>clear</span> <span m='2503570'>way.</span>
  <span m='2505900'>And</span> <span m='2506120'>so</span> <span m='2506340'>it's</span>
  <span m='2506490'>not</span> <span m='2506710'>a</span> <span m='2506750'>very</span>
  <span m='2506980'>good</span> <span m='2507160'>idea</span> <span m='2508080'>to</span>
  <span m='2508300'>have</span> <span m='2508510'>to</span> <span m='2508600'>have</span>
  <span m='2508720'>an</span> <span m='2508780'>agreement,</span> <span m='2510560'>between</span>
  <span m='2511210'>the</span> <span m='2511410'>person</span> <span m='2511630'>who</span>
  <span m='2511750'>writes</span> <span m='2511990'>a</span> <span m='2512040'>procedure</span>
  <span m='2512470'>and</span> <span m='2512570'>the</span> <span m='2512670'>person</span>
  <span m='2513430'>who</span> <span m='2514240'>calls</span> <span m='2514560'>it,</span>
  <span m='2515200'>about</span> <span m='2515540'>such</span> <span m='2515740'>details</span>
  <span m='2516250'>as,</span> <span m='2516390'>maybe,</span> <span m='2516640'>the</span>
  <span m='2516730'>arguments of</span> <span m='2517120'>evaluation,</span> <span
  m='2518510'>the</span> <span m='2518650'>order</span> <span m='2518890'>of</span>
  <span m='2518980'>evaluation.</span> </p><p><span m='2519500'>Although,</span> <span
  m='2519750'>that's</span> <span m='2519990'>not</span> <span m='2520160'>so</span>
  <span m='2520290'>bad.</span> <span m='2520750'>I</span> <span m='2521090'>mean,</span>
  <span m='2521280'>we</span> <span m='2521380'>have</span> <span m='2521590'>other</span>
  <span m='2521990'>such</span> <span m='2522160'>agreements</span> <span m='2522560'>like,</span>
  <span m='2522920'>the</span> <span m='2523100'>input's a</span> <span m='2523410'>number.</span>
  <span m='2524540'>But</span> <span m='2524880'>it</span> <span m='2525250'>would</span>
  <span m='2525410'>be</span> <span m='2525580'>nice</span> <span m='2525940'>if</span>
  <span m='2526430'>only</span> <span m='2526650'>one</span> <span m='2526850'>of</span>
  <span m='2526930'>these</span> <span m='2527150'>guys could</span> <span m='2527480'>take</span>
  <span m='2527650'>responsibility,</span> <span m='2528660'>completely.</span> <span
  m='2531020'>Now</span> <span m='2531180'>this</span> <span m='2531340'>is</span>
  <span m='2531460'>not</span> <span m='2532550'>a</span> <span m='2532670'>new</span>
  <span m='2532890'>idea.</span> </p><p><span m='2535510'>ALGOL</span> <span m='2536010'>60</span>
  <span m='2537900'>had</span> <span m='2539010'>two</span> <span m='2539260'>different</span>
  <span m='2539510'>ways</span> <span m='2539740'>of</span> <span m='2539820'>calling</span>
  <span m='2540350'>a</span> <span m='2540620'>procedure.</span> <span m='2542020'>The</span>
  <span m='2542230'>arguments</span> <span m='2542600'>could</span> <span m='2542680'>be</span>
  <span m='2542770'>passed</span> <span m='2543090'>by</span> <span m='2543250'>name</span>
  <span m='2543540'>or</span> <span m='2543590'>by</span> <span m='2543770'>value.</span>
  <span m='2545590'>And</span> <span m='2545710'>what</span> <span m='2545850'>that</span>
  <span m='2546090'>meant</span> <span m='2546960'>was</span> <span m='2547310'>that</span>
  <span m='2547660'>a</span> <span m='2547820'>name</span> <span m='2548140'>argument</span>
  <span m='2549090'>was</span> <span m='2549280'>delayed.</span> <span m='2551110'>That</span>
  <span m='2551280'>when</span> <span m='2551380'>you</span> <span m='2551470'>passed</span>
  <span m='2551770'>an</span> <span m='2551830'>argument</span> <span m='2552180'>by</span>
  <span m='2552330'>name,</span> <span m='2552810'>that</span> <span m='2553880'>its</span>
  <span m='2554020'>value</span> <span m='2554390'>would</span> <span m='2554510'>only</span>
  <span m='2554760'>be</span> <span m='2555950'>obtained</span> <span m='2556990'>if</span>
  <span m='2557140'>you</span> <span m='2557290'>accessed</span> <span m='2558230'>that</span>
  <span m='2559140'>argument.</span> </p><p><span m='2562290'>So</span> <span m='2562530'>what
  I'd</span> <span m='2562690'>like</span> <span m='2562870'>to</span> <span m='2562950'>do</span>
  <span m='2563100'>now</span> <span m='2563520'>is</span> <span m='2563660'>show</span>
  <span m='2563880'>you,</span> <span m='2564330'>first</span> <span m='2564720'>of</span>
  <span m='2564830'>all,</span> <span m='2565780'>a</span> <span m='2565870'>little</span>
  <span m='2566110'>bit</span> <span m='2566280'>about,</span> <span m='2566540'>again,</span>
  <span m='2567040'>we're</span> <span m='2567120'>going</span> <span m='2567170'>to</span>
  <span m='2567220'>make</span> <span m='2567340'>a</span> <span m='2567390'>modification</span>
  <span m='2568040'>to</span> <span m='2568120'>a</span> <span m='2568210'>language.</span>
  <span m='2570320'>In</span> <span m='2570410'>this</span> <span m='2570600'>case,</span>
  <span m='2570840'>we're</span> <span m='2571030'>going to add</span> <span m='2571220'>a</span>
  <span m='2571260'>feature.</span> <span m='2573370'>We're</span> <span m='2573510'>going</span>
  <span m='2573560'>to</span> <span m='2573610'>add</span> <span m='2573820'>the</span>
  <span m='2573910'>feature</span> <span m='2574760'>of,</span> <span m='2575290'>by</span>
  <span m='2575730'>name</span> <span m='2576070'>parameters,</span> <span m='2576650'>if</span>
  <span m='2576780'>you</span> <span m='2576900'>will,</span> <span m='2577310'>or</span>
  <span m='2577480'>delayed</span> <span m='2577980'>parameters.</span> <span m='2580430'>Because,</span>
  <span m='2580690'>in</span> <span m='2580780'>fact,</span> <span m='2581070'>the</span>
  <span m='2581160'>default</span> <span m='2583360'>in</span> <span m='2583540'>our</span>
  <span m='2583690'>Lisp</span> <span m='2583940'>system</span> <span m='2584800'>is</span>
  <span m='2585130'>by</span> <span m='2585480'>the</span> <span m='2585580'>value</span>
  <span m='2585990'>of</span> <span m='2586080'>a</span> <span m='2586150'>pointer.</span>
  <span m='2588220'>A</span> <span m='2588300'>pointer</span> <span m='2588690'>is</span>
  <span m='2588790'>copied,</span> <span m='2589220'>but</span> <span m='2589330'>the</span>
  <span m='2589680'>data</span> <span m='2589940'>structure</span> <span m='2590390'>it</span>
  <span m='2590530'>points</span> <span m='2590920'>at</span> <span m='2591418'>is</span>
  <span m='2591916'>not.</span> <span m='2593410'>But</span> <span m='2593530'>I'd</span>
  <span m='2593650'>like</span> <span m='2593810'>to,</span> <span m='2593920'>in</span>
  <span m='2594020'>fact,</span> <span m='2594330'>show</span> <span m='2594530'>you</span>
  <span m='2595990'>is</span> <span m='2596160'>how</span> <span m='2596300'>you</span>
  <span m='2596480'>add</span> <span m='2597230'>name</span> <span m='2597580'>arguments</span>
  <span m='2598000'>as</span> <span m='2598100'>well.</span> </p><p><span m='2599990'>Now</span>
  <span m='2600160'>again,</span> <span m='2600660'>why</span> <span m='2601020'>would</span>
  <span m='2601190'>we</span> <span m='2601330'>need</span> <span m='2601550'>such</span>
  <span m='2601760'>a</span> <span m='2601800'>thing?</span> <span m='2603100'>Well</span>
  <span m='2603280'>supposing</span> <span m='2603720'>we</span> <span m='2603860'>wanted</span>
  <span m='2604070'>to</span> <span m='2604250'>invent</span> <span m='2605270'>certain</span>
  <span m='2605630'>kinds</span> <span m='2605970'>of</span> <span m='2606730'>what</span>
  <span m='2606930'>otherwise</span> <span m='2607340'>would</span> <span m='2607450'>be</span>
  <span m='2607560'>special</span> <span m='2607950'>forms,</span> <span m='2608870'>reserve</span>
  <span m='2609260'>words?</span> <span m='2609720'>But I'd</span> <span m='2609910'>rather</span>
  <span m='2610140'>not</span> <span m='2610390'>take</span> <span m='2610540'>up</span>
  <span m='2610700'>reserve</span> <span m='2611020'>words.</span> <span m='2612180'>I</span>
  <span m='2612330'>want</span> <span m='2612570'>procedures</span> <span m='2613410'>that</span>
  <span m='2613600'>can</span> <span m='2613720'>do</span> <span m='2613880'>things</span>
  <span m='2614180'>like</span> <span m='2614410'>if.</span> </p><p><span m='2616360'>If</span>
  <span m='2616600'>is</span> <span m='2616670'>special,</span> <span m='2618280'>or</span>
  <span m='2618440'>cond, or</span> <span m='2618910'>whatever</span> <span m='2619240'>it</span>
  <span m='2619300'>is. It's</span> <span m='2619540'>the</span> <span m='2619610'>same</span>
  <span m='2619880'>thing.</span> <span m='2620600'>It's</span> <span m='2620760'>special</span>
  <span m='2621350'>in</span> <span m='2621560'>that</span> <span m='2621860'>it</span>
  <span m='2622000'>determines</span> <span m='2622460'>whether</span> <span m='2622690'>or</span>
  <span m='2622730'>not</span> <span m='2622950'>to</span> <span m='2623080'>evaluate</span>
  <span m='2623510'>the</span> <span m='2623570'>consequent</span> <span m='2624050'>or</span>
  <span m='2624190'>the</span> <span m='2624320'>alternative</span> <span m='2626320'>based</span>
  <span m='2626760'>on</span> <span m='2627820'>the</span> <span m='2627980'>value</span>
  <span m='2628360'>of</span> <span m='2628430'>the</span> <span m='2628510'>predicate</span>
  <span m='2628880'>part of</span> <span m='2629170'>an</span> <span m='2629220'>expression.</span>
  <span m='2630840'>So</span> <span m='2631940'>taking</span> <span m='2632150'>the</span>
  <span m='2632220'>value</span> <span m='2632510'>of</span> <span m='2632580'>one</span>
  <span m='2632790'>thing</span> <span m='2633450'>determines</span> <span m='2633950'>whether</span>
  <span m='2634150'>or</span> <span m='2634230'>not</span> <span m='2634430'>to</span>
  <span m='2634510'>do</span> <span m='2634600'>something</span> <span m='2635010'>else.</span>
  </p><p><span m='2637270'>Whereas</span> <span m='2637570'>all</span> <span m='2637680'>the</span>
  <span m='2637800'>procedures</span> <span m='2638220'>like</span> <span m='2638440'>plus,</span>
  <span m='2639920'>the</span> <span m='2639980'>ones that</span> <span m='2640140'>we</span>
  <span m='2640240'>can</span> <span m='2640350'>define</span> <span m='2640730'>right</span>
  <span m='2640970'>now,</span> <span m='2641480'>evaluate</span> <span m='2641960'>all</span>
  <span m='2642110'>of</span> <span m='2642250'>their</span> <span m='2642430'>arguments</span>
  <span m='2644940'>before</span> <span m='2645900'>application.</span> <span m='2648670'>So,</span>
  <span m='2648900'>for</span> <span m='2649060'>example,</span> <span m='2650390'>supposing</span>
  <span m='2650790'>I</span> <span m='2650850'>wish</span> <span m='2651010'>to</span>
  <span m='2651110'>be</span> <span m='2651190'>able</span> <span m='2651370'>to</span>
  <span m='2651440'>define</span> <span m='2651750'>something</span> <span m='2652080'>like</span>
  <span m='2655250'>the</span> <span m='2655600'>reverse</span> <span m='2656150'>of</span>
  <span m='2656350'>if</span> <span m='2657920'>in</span> <span m='2658050'>terms</span>
  <span m='2658320'>of</span> <span m='2658430'>if.</span> <span m='2659452'>Call</span>
  <span m='2659860'>it</span> <span m='2660160'>unless.</span> <span m='2664890'>We've</span>
  <span m='2665120'>a</span> <span m='2665320'>predicate,</span> <span m='2665770'>a</span>
  <span m='2665900'>consequent,</span> <span m='2666580'>and an</span> <span m='2666760'>alternative.</span>
  </p><p><span m='2668190'>Now</span> <span m='2668690'>what I</span> <span m='2668770'>would</span>
  <span m='2669080'>like</span> <span m='2669340'>to</span> <span m='2669430'>sort</span>
  <span m='2669570'>of</span> <span m='2669720'>be</span> <span m='2669880'>able</span>
  <span m='2670040'>to</span> <span m='2670140'>do</span> <span m='2670360'>is</span>
  <span m='2670500'>say--</span> <span m='2670890'>oh, I'll</span> <span m='2671100'>do
  it</span> <span m='2671200'>in</span> <span m='2671310'>terms</span> <span m='2671470'>of</span>
  <span m='2671550'>cond.</span> <span m='2672440'>Cond,</span> <span m='2675700'>if</span>
  <span m='2675920'>not</span> <span m='2676180'>the predicate,</span> <span m='2678750'>then</span>
  <span m='2679270'>take</span> <span m='2679480'>the</span> <span m='2679550'>consequent,</span>
  <span m='2681660'>otherwise,</span> <span m='2684310'>take</span> <span m='2684670'>the</span>
  <span m='2685030'>alternative.</span> <span m='2691290'>Now,</span> <span m='2691460'>what</span>
  <span m='2691570'>I'd</span> <span m='2691720'>like</span> <span m='2691930'>this</span>
  <span m='2692110'>to</span> <span m='2692220'>mean,</span> <span m='2693380'>is</span>
  <span m='2693620'>supposing</span> <span m='2694040'>I</span> <span m='2694130'>do</span>
  <span m='2694320'>something</span> <span m='2694720'>like</span> <span m='2694970'>this.</span>
  <span m='2696920'>I'd</span> <span m='2697200'>like</span> <span m='2697410'>this</span>
  <span m='2697630'>unless</span> <span m='2701910'>say</span> <span m='2702490'>if</span>
  <span m='2702670'>equals</span> <span m='2703150'>one,</span> <span m='2703510'>0,</span>
  <span m='2705140'>then</span> <span m='2705350'>the</span> <span m='2705510'>answer</span>
  <span m='2705860'>is</span> <span m='2706120'>two,</span> <span m='2707920'>otherwise,</span>
  <span m='2709280'>the</span> <span m='2709790'>quotient</span> <span m='2710240'>of</span>
  <span m='2710430'>one</span> <span m='2710730'>and</span> <span m='2710930'>0.</span>
  </p><p><span m='2715980'>What</span> <span m='2716100'>I'd</span> <span m='2716210'>like</span>
  <span m='2716410'>that</span> <span m='2716600'>to</span> <span m='2716710'>mean</span>
  <span m='2717280'>is</span> <span m='2717430'>the</span> <span m='2717520'>result</span>
  <span m='2717920'>of</span> <span m='2718010'>substituting</span> <span m='2720170'>equal</span>
  <span m='2720500'>one,</span> <span m='2720740'>0,</span> <span m='2721460'>and</span>
  <span m='2721700'>two,</span> <span m='2722030'>and</span> <span m='2722180'>the</span>
  <span m='2722220'>quotient of</span> <span m='2722630'>one,</span> <span m='2722860'>0</span>
  <span m='2723450'>for</span> <span m='2723860'>p,</span> <span m='2724120'>c,</span>
  <span m='2724425'>and</span> <span m='2724730'>a.</span> <span m='2725580'>I'd</span>
  <span m='2725810'>like</span> <span m='2726100'>that</span> <span m='2726310'>to</span>
  <span m='2726430'>mean,</span> <span m='2726720'>and</span> <span m='2726820'>this</span>
  <span m='2726950'>is</span> <span m='2727090'>funny,</span> <span m='2727950'>I'd</span>
  <span m='2728270'>like</span> <span m='2728560'>it</span> <span m='2728650'>to</span>
  <span m='2728750'>transform</span> <span m='2729280'>into</span> <span m='2729580'>or</span>
  <span m='2729720'>mean</span> <span m='2730770'>cond</span> <span m='2734990'>not</span>
  <span m='2736940'>equal</span> <span m='2737430'>one,</span> <span m='2737850'>0,</span>
  <span m='2740620'>then</span> <span m='2740840'>the</span> <span m='2740940'>result</span>
  <span m='2741760'>is</span> <span m='2741990'>two,</span> <span m='2744370'>otherwise</span>
  <span m='2748260'>I</span> <span m='2748370'>want</span> <span m='2748590'>it  to</span>
  <span m='2748650'>be</span> <span m='2748780'>the</span> <span m='2748910'>quotient</span>
  <span m='2749870'>one</span> <span m='2750480'>and</span> <span m='2750760'>0.</span>
  </p><p><span m='2754480'>Now,</span> <span m='2754650'>you</span> <span m='2754820'>know</span>
  <span m='2755050'>that</span> <span m='2755160'>if</span> <span m='2755270'>I</span>
  <span m='2755400'>were to</span> <span m='2755580'>type</span> <span m='2755880'>this</span>
  <span m='2756070'>into</span> <span m='2756210'>Lisp,</span> <span m='2757800'>I'd</span>
  <span m='2757930'>get</span> <span m='2758220'>a</span> <span m='2758500'>two.</span>
  <span m='2759970'>There's</span> <span m='2760270'>no</span> <span m='2760440'>problem</span>
  <span m='2760850'>with</span> <span m='2760990'>that.</span> <span m='2762910'>However,</span>
  <span m='2763260'>if</span> <span m='2763400'>I</span> <span m='2763490'>were</span>
  <span m='2763590'>to</span> <span m='2763690'>type</span> <span m='2763940'>this</span>
  <span m='2764210'>into</span> <span m='2764370'>Lisp,</span> <span m='2765170'>because</span>
  <span m='2765670'>all</span> <span m='2765940'>the</span> <span m='2766070'>arguments</span>
  <span m='2766410'>are</span> <span m='2766520'>evaluated</span> <span m='2767040'>before</span>
  <span m='2767310'>I</span> <span m='2767400'>start,</span> <span m='2768700'>then</span>
  <span m='2769400'>I'm</span> <span m='2769520'>going</span> <span m='2769590'>to</span>
  <span m='2769670'>get</span> <span m='2769810'>an</span> <span m='2769900'>error</span>
  <span m='2770190'>out</span> <span m='2770280'>of</span> <span m='2770380'>this.</span>
  <span m='2773380'>So</span> <span m='2773600'>that</span> <span m='2773770'>if</span>
  <span m='2773910'>the</span> <span m='2774020'>substitutions</span> <span m='2774610'>work</span>
  <span m='2774830'>at</span> <span m='2774900'>all,</span> <span m='2775140'>of</span>
  <span m='2775420'>course,</span> <span m='2775980'>I</span> <span m='2776130'>would</span>
  <span m='2776190'>get</span> <span m='2776350'>the</span> <span m='2776430'>right</span>
  <span m='2776590'>answer.</span> <span m='2776880'>But</span> <span m='2777090'>here's
  a</span> <span m='2777180'>case</span> <span m='2777780'>where</span> <span m='2778760'>the</span>
  <span m='2779150'>substitutions</span> <span m='2779580'>don't</span> <span m='2779770'>work.</span>
  <span m='2782920'>I</span> <span m='2783060'>don't</span> <span m='2783200'>get
  the</span> <span m='2783280'>wrong</span> <span m='2783510'>answer.</span> <span
  m='2783860'>I</span> <span m='2783950'>get</span> <span m='2784120'>no</span> <span
  m='2784310'>answer.</span> <span m='2784670'>I get</span> <span m='2784970'>an</span>
  <span m='2785210'>error.</span> </p><p><span m='2788420'>Now,</span> <span m='2788630'>however,</span>
  <span m='2789230'>I'd</span> <span m='2789470'>like</span> <span m='2789630'>to</span>
  <span m='2789720'>be</span> <span m='2789930'>able</span> <span m='2790080'>to</span>
  <span m='2790280'>make my</span> <span m='2790430'>definition</span> <span m='2791670'>so</span>
  <span m='2791860'>that</span> <span m='2792020'>this</span> <span m='2792180'>kind</span>
  <span m='2792320'>of</span> <span m='2792450'>thing</span> <span m='2792640'>works.</span>
  <span m='2794270'>What</span> <span m='2794660'>I</span> <span m='2794830'>want</span>
  <span m='2794990'>to</span> <span m='2795150'>do</span> <span m='2795380'>is</span>
  <span m='2795510'>say</span> <span m='2795690'>something</span> <span m='2796010'>special</span>
  <span m='2796700'>about</span> <span m='2797270'>c</span> <span m='2798040'>and</span>
  <span m='2798250'>a.</span> <span m='2799930'>I</span> <span m='2800070'>want</span>
  <span m='2800330'>them</span> <span m='2800460'>to</span> <span m='2800560'>be</span>
  <span m='2800690'>delayed</span> <span m='2802340'>automatically.</span> <span m='2806300'>I</span>
  <span m='2806470'>don't</span> <span m='2806710'>want</span> <span m='2806960'>them</span>
  <span m='2807050'>to</span> <span m='2807150'>be</span> <span m='2807290'>evaluated</span>
  <span m='2808570'>at</span> <span m='2808810'>the</span> <span m='2808980'>time</span>
  <span m='2809270'>I</span> <span m='2809340'>call.</span> </p><p><span m='2811520'>So</span>
  <span m='2811780'>I'm</span> <span m='2811890'>going to</span> <span m='2812010'>make</span>
  <span m='2812140'>a</span> <span m='2812200'>declaration,</span> <span m='2812860'>and
  then I'm</span> <span m='2812980'>going to see</span> <span m='2813360'>how</span>
  <span m='2813450'>to</span> <span m='2813550'>implement</span> <span m='2814190'>such</span>
  <span m='2814490'>a</span> <span m='2814540'>declaration.</span> <span m='2815600'>But</span>
  <span m='2815820'>again,</span> <span m='2816150'>I</span> <span m='2816320'>want
  you</span> <span m='2816570'>to</span> <span m='2816670'>say</span> <span m='2817150'>to</span>
  <span m='2817270'>yourself,</span> <span m='2817840'>oh,</span> <span m='2818260'>this</span>
  <span m='2818480'>is an</span> <span m='2818870'>interesting</span> <span m='2819330'>kluge</span>
  <span m='2819490'>he's</span> <span m='2819830'>adding in</span> <span m='2819950'>here.</span>
  <span m='2822140'>The</span> <span m='2822380'>piles</span> <span m='2822750'>of</span>
  <span m='2822850'>kluges</span> <span m='2823230'>make</span> <span m='2823430'>a</span>
  <span m='2823480'>big</span> <span m='2823730'>complicated</span> <span m='2824280'>mess.</span>
  <span m='2825750'>And</span> <span m='2826870'>is this</span> <span m='2827000'>going</span>
  <span m='2827130'>to</span> <span m='2827550'>foul</span> <span m='2827780'>up</span>
  <span m='2827870'>something</span> <span m='2828240'>else</span> <span m='2828540'>that</span>
  <span m='2828690'>might</span> <span m='2829290'>occur.</span> <span m='2830120'>First</span>
  <span m='2830390'>of</span> <span m='2830440'>all,</span> <span m='2830560'>is</span>
  <span m='2830660'>it</span> <span m='2830760'>syntactically</span> <span m='2831960'>unambiguous?</span>
  <span m='2833860'>Well,</span> <span m='2834230'>it</span> <span m='2834350'>will
  be</span> <span m='2834570'>syntactically</span> <span m='2834770'>unambiguous</span>
  <span m='2834980'>with</span> <span m='2835730'>what</span> <span m='2836010'>we've</span>
  <span m='2836120'>seen</span> <span m='2836340'>so</span> <span m='2836610'>far.</span>
  </p><p><span m='2837840'>But</span> <span m='2838150'>what</span> <span m='2838330'>I'm</span>
  <span m='2838420'>going</span> <span m='2838500'>to</span> <span m='2838580'>do</span>
  <span m='2839010'>may,</span> <span m='2839230'>in</span> <span m='2839360'>fact,</span>
  <span m='2840130'>cause</span> <span m='2840390'>trouble.</span> <span m='2841670'>It</span>
  <span m='2841870'>may</span> <span m='2842140'>be</span> <span m='2842370'>that</span>
  <span m='2842540'>the</span> <span m='2842640'>thing</span> <span m='2842820'>I</span>
  <span m='2843130'>had</span> <span m='2843800'>will</span> <span m='2843950'>conflict</span>
  <span m='2844390'>with</span> <span m='2845180'>type</span> <span m='2845450'>declarations</span>
  <span m='2845970'>I might</span> <span m='2846050'>want</span> <span m='2846200'>to</span>
  <span m='2846380'>add</span> <span m='2846620'>in the</span> <span m='2846700'>future</span>
  <span m='2848200'>for</span> <span m='2848370'>giving</span> <span m='2848700'>some</span>
  <span m='2848980'>system,</span> <span m='2849820'>some</span> <span m='2850050'>compiler</span>
  <span m='2850360'>or</span> <span m='2850670'>something,</span> <span m='2851270'>the</span>
  <span m='2851390'>ability</span> <span m='2851640'>to</span> <span m='2851730'>optimize</span>
  <span m='2852330'>given</span> <span m='2852710'>the</span> <span m='2852810'>types</span>
  <span m='2853120'>are</span> <span m='2853190'>known.</span> <span m='2854300'>Or</span>
  <span m='2854690'>it</span> <span m='2854980'>might</span> <span m='2855380'>conflict</span>
  <span m='2855880'>with</span> <span m='2856010'>other</span> <span m='2856240'>types</span>
  <span m='2856470'>of</span> <span m='2856530'>declarations</span> <span m='2857090'>I</span>
  <span m='2857130'>might</span> <span m='2857350'>want</span> <span m='2857430'>to</span>
  <span m='2857510'>make</span> <span m='2857690'>about</span> <span m='2858020'>the</span>
  <span m='2858820'>formal</span> <span m='2859090'>parameters.</span> <span m='2860570'>So</span>
  <span m='2860770'>I'm</span> <span m='2860910'>not</span> <span m='2861200'>making</span>
  <span m='2861430'>a</span> <span m='2861470'>general</span> <span m='2861830'>mechanism</span>
  <span m='2862320'>here</span> <span m='2863810'>where</span> <span m='2863990'>I</span>
  <span m='2864070'>can</span> <span m='2864220'>add</span> <span m='2864520'>declarations.</span>
  <span m='2864925'>And</span> <span m='2865330'>I</span> <span m='2865470'>would</span>
  <span m='2865600'>like</span> <span m='2865810'>to be</span> <span m='2866100'>able
  to do</span> <span m='2866230'>that.</span> <span m='2866750'>But</span> <span m='2867010'>I
  don't</span> <span m='2867180'>want</span> <span m='2867390'>to</span> <span m='2867510'>talk</span>
  <span m='2867750'>about</span> <span m='2868020'>that</span> <span m='2868210'>right</span>
  <span m='2868450'>now.</span> </p><p><span m='2871010'>So</span> <span m='2871220'>here
  I'm</span> <span m='2871440'>going</span> <span m='2871530'>to</span> <span m='2871630'>do,</span>
  <span m='2872030'>I'm</span> <span m='2872230'>going</span> <span m='2872390'>to</span>
  <span m='2872980'>build</span> <span m='2873280'>a</span> <span m='2873350'>kluge.</span>
  <span m='2877050'>So</span> <span m='2877740'>we're</span> <span m='2877830'>going</span>
  <span m='2877890'>to</span> <span m='2877960'>define</span> <span m='2883320'>unless</span>
  <span m='2887510'>of</span> <span m='2887670'>a</span> <span m='2887890'>predicate--</span>
  <span m='2888770'>and</span> <span m='2888870'>I'm</span> <span m='2888970'>going</span>
  <span m='2889080'>to</span> <span m='2889140'>call</span> <span m='2889360'>these</span>
  <span m='2889540'>by</span> <span m='2889710'>name--</span> <span m='2892810'>the</span>
  <span m='2893000'>consequent,</span> <span m='2894000'>and</span> <span m='2894220'>name</span>
  <span m='2894460'>the</span> <span m='2894600'>alternative.</span> <span m='2899850'>Huh,</span>
  <span m='2901370'>huh--</span> <span m='2902670'>I</span> <span m='2902810'>got</span>
  <span m='2903040'>caught</span> <span m='2903460'>in</span> <span m='2904050'>the</span>
  <span m='2904830'>corner.</span> <span m='2911240'>If</span> <span m='2911990'>not</span>
  <span m='2913030'>p</span> <span m='2913940'>then</span> <span m='2914100'>the</span>
  <span m='2914200'>result</span> <span m='2914760'>is</span> <span m='2914980'>c,</span>
  <span m='2916870'>else--</span> <span m='2920110'>that's</span> <span m='2920530'>what</span>
  <span m='2920630'>I'd</span> <span m='2920780'>like.</span> <span m='2924670'>Where</span>
  <span m='2924985'>I</span> <span m='2925300'>can</span> <span m='2925550'>explicitly</span>
  <span m='2926220'>declare</span> <span m='2927510'>certain</span> <span m='2927910'>of</span>
  <span m='2928010'>the</span> <span m='2928100'>parameters</span> <span m='2929170'>to</span>
  <span m='2929500'>be</span> <span m='2929680'>delayed,</span> <span m='2930570'>to</span>
  <span m='2930680'>be</span> <span m='2930820'>computed</span> <span m='2931270'>later.</span>
  </p><p><span m='2935008'>Now,</span> <span m='2935410'>this</span> <span m='2935830'>is</span>
  <span m='2935970'>actually</span> <span m='2936250'>a</span> <span m='2936300'>very</span>
  <span m='2936550'>complicated</span> <span m='2937120'>modification</span> <span
  m='2937780'>to an</span> <span m='2937910'>interpreter</span> <span m='2938830'>rather</span>
  <span m='2939100'>than a</span> <span m='2939170'>simple</span> <span m='2939500'>one.</span>
  <span m='2940450'>The</span> <span m='2940680'>ones</span> <span m='2940790'>you
  saw</span> <span m='2940970'>before,</span> <span m='2941890'>dynamic</span> <span
  m='2942560'>binding</span> <span m='2943420'>or</span> <span m='2943650'>adding</span>
  <span m='2945270'>indefinite</span> <span m='2945780'>argument</span> <span m='2946290'>procedures,</span>
  <span m='2947630'>is</span> <span m='2947730'>relatively</span> <span m='2948110'>simple.</span>
  <span m='2949280'>But</span> <span m='2949520'>this</span> <span m='2949660'>one</span>
  <span m='2949820'>changes</span> <span m='2950230'>a</span> <span m='2950290'>basic</span>
  <span m='2950650'>strategy.</span> <span m='2952120'>The</span> <span m='2952510'>problem</span>
  <span m='2952890'>here</span> <span m='2954060'>is</span> <span m='2954270'>that</span>
  <span m='2954500'>our</span> <span m='2954720'>interpreter,</span> <span m='2956840'>as</span>
  <span m='2957170'>written,</span> <span m='2958070'>evaluates</span> <span m='2959610'>a</span>
  <span m='2959680'>combination</span> <span m='2961050'>by</span> <span m='2961320'>evaluating</span>
  <span m='2962540'>the</span> <span m='2962800'>procedure,</span> <span m='2964310'>the</span>
  <span m='2964420'>operator</span> <span m='2964880'>producing</span> <span m='2965280'>the</span>
  <span m='2965360'>procedure,</span> <span m='2966190'>and</span> <span m='2966390'>evaluating</span>
  <span m='2966650'>the</span> <span m='2966910'>operands</span> <span m='2968380'>producing</span>
  <span m='2969150'>the</span> <span m='2969740'>arguments,</span> <span m='2970790'>and</span>
  <span m='2970990'>then</span> <span m='2971130'>doing</span> <span m='2971410'>apply</span>
  <span m='2972500'>of</span> <span m='2972700'>the</span> <span m='2972790'>procedure</span>
  <span m='2974410'>to</span> <span m='2974550'>the</span> <span m='2974660'>arguments.</span>
  </p><p><span m='2976110'>However,</span> <span m='2976700'>here,</span> <span m='2977260'>I</span>
  <span m='2977470'>don't</span> <span m='2977740'>want</span> <span m='2978010'>to</span>
  <span m='2978140'>evaluate</span> <span m='2979670'>the</span> <span m='2979950'>operands</span>
  <span m='2980470'>to</span> <span m='2980540'>produce</span> <span m='2980790'>the</span>
  <span m='2980890'>arguments</span> <span m='2981790'>until</span> <span m='2982110'>after</span>
  <span m='2982430'>I</span> <span m='2982550'>examined</span> <span m='2983040'>the</span>
  <span m='2983120'>procedure</span> <span m='2984640'>to</span> <span m='2984790'>see</span>
  <span m='2984990'>what</span> <span m='2985160'>the</span> <span m='2985250'>procedure's</span>
  <span m='2985690'>declarations</span> <span m='2986310'>look</span> <span m='2986490'>like.</span>
  <span m='2989590'>So</span> <span m='2989740'>let's</span> <span m='2989930'>look</span>
  <span m='2990070'>at</span> <span m='2990210'>that.</span> <span m='2992680'>Here</span>
  <span m='2992920'>we</span> <span m='2993050'>have</span> <span m='2993910'>a</span>
  <span m='2994070'>changed</span> <span m='2995710'>evaluator.</span> <span m='2997480'>I'm</span>
  <span m='2997600'>starting</span> <span m='2998040'>with</span> <span m='2998350'>the</span>
  <span m='2999240'>simple</span> <span m='2999920'>lexical</span> <span m='3000420'>evaluator,</span>
  <span m='3001870'>not</span> <span m='3002110'>dynamic,</span> <span m='3004180'>but</span>
  <span m='3004380'>we're</span> <span m='3004470'>going</span> <span m='3004530'>to</span>
  <span m='3004600'>have</span> <span m='3004860'>to</span> <span m='3005440'>do</span>
  <span m='3005700'>something</span> <span m='3006320'>sort</span> <span m='3006530'>of</span>
  <span m='3006730'>similar</span> <span m='3007330'>in</span> <span m='3007480'>some</span>
  <span m='3007740'>ways.</span> <span m='3009750'>Because</span> <span m='3010280'>of</span>
  <span m='3010340'>the</span> <span m='3010400'>fact</span> <span m='3010930'>that,</span>
  <span m='3011930'>if</span> <span m='3012150'>I</span> <span m='3012270'>delay</span>
  <span m='3012640'>a</span> <span m='3012710'>procedure--</span> <span m='3013710'>I'm</span>
  <span m='3013810'>sorry--</span> <span m='3014100'>delay an</span> <span m='3014330'>argument</span>
  <span m='3014660'>to a</span> <span m='3014750'>procedure,</span> <span m='3015400'>I'm</span>
  <span m='3015590'>going</span> <span m='3015690'>to</span> <span m='3015790'>have</span>
  <span m='3015940'>to</span> <span m='3016090'>attach and</span> <span m='3016530'>environment</span>
  <span m='3017150'>to</span> <span m='3017350'>it.</span> </p><p><span m='3019360'>Remember</span>
  <span m='3019810'>how</span> <span m='3020240'>Hal</span> <span m='3020560'>implemented</span>
  <span m='3021030'>delay.</span> <span m='3023380'>Hal</span> <span m='3023660'>implemented</span>
  <span m='3024060'>delay</span> <span m='3024670'>as</span> <span m='3024920'>being</span>
  <span m='3025520'>a</span> <span m='3025610'>procedure</span> <span m='3026330'>of</span>
  <span m='3026620'>no</span> <span m='3026860'>arguments</span> <span m='3028650'>which</span>
  <span m='3029480'>does</span> <span m='3029790'>some</span> <span m='3029900'>expression.</span>
  <span m='3031180'>That's</span> <span m='3031410'>what</span> <span m='3031550'>delay</span>
  <span m='3031860'>of</span> <span m='3031950'>the</span> <span m='3032030'>expression</span>
  <span m='3032350'>is.</span> <span m='3035370'>--of</span> <span m='3035820'>that</span>
  <span m='3036210'>expression.</span> <span m='3039180'>This</span> <span m='3039590'>turned</span>
  <span m='3039830'>into</span> <span m='3040020'>something</span> <span m='3040360'>like</span>
  <span m='3040610'>this.</span> </p><p><span m='3044520'>Now,</span> <span m='3044870'>however,</span>
  <span m='3045180'>if</span> <span m='3045290'>I</span> <span m='3045390'>evaluate</span>
  <span m='3045960'>a</span> <span m='3046020'>lambda</span> <span m='3046360'>expression,</span>
  <span m='3046950'>I</span> <span m='3047450'>have</span> <span m='3047670'>to</span>
  <span m='3047760'>capture</span> <span m='3048440'>the</span> <span m='3048590'>environment.</span>
  <span m='3051410'>The</span> <span m='3051560'>reason</span> <span m='3051840'>why</span>
  <span m='3052130'>is</span> <span m='3052280'>because</span> <span m='3052720'>there</span>
  <span m='3053000'>are</span> <span m='3055360'>variables</span> <span m='3055970'>in</span>
  <span m='3056070'>there</span> <span m='3056920'>who's</span> <span m='3057330'>meaning</span>
  <span m='3057630'>I</span> <span m='3057790'>wish</span> <span m='3057870'>to</span>
  <span m='3058450'>derive</span> <span m='3059060'>from</span> <span m='3059310'>the</span>
  <span m='3059370'>context</span> <span m='3059910'>where</span> <span m='3060070'>this</span>
  <span m='3060280'>was</span> <span m='3060460'>written.</span> </p><p><span m='3064010'>So</span>
  <span m='3064290'>that's</span> <span m='3064560'>why a</span> <span m='3064830'>lambda</span>
  <span m='3064910'>does</span> <span m='3065130'>the</span> <span m='3065240'>job.</span>
  <span m='3066095'>It's</span> <span m='3066520'>the</span> <span m='3066780'>right</span>
  <span m='3067090'>thing.</span> <span m='3068070'>And</span> <span m='3068280'>such</span>
  <span m='3068440'>that the</span> <span m='3068560'>forcing</span> <span m='3072050'>of</span>
  <span m='3073990'>a</span> <span m='3074180'>delayed</span> <span m='3074530'>expression</span>
  <span m='3076240'>was</span> <span m='3076770'>same</span> <span m='3077070'>thing</span>
  <span m='3077390'>as</span> <span m='3078650'>calling</span> <span m='3079130'>that</span>
  <span m='3079300'>with</span> <span m='3079390'>no</span> <span m='3079600'>arguments.</span>
  <span m='3081090'>It's</span> <span m='3081230'>just</span> <span m='3081360'>the</span>
  <span m='3081460'>opposite of</span> <span m='3081910'>this.</span> <span m='3084100'>Producing</span>
  <span m='3085600'>an</span> <span m='3085730'>environment</span> <span m='3086300'>of</span>
  <span m='3086420'>the</span> <span m='3086500'>call</span> <span m='3087370'>which</span>
  <span m='3087640'>is,</span> <span m='3087700'>in</span> <span m='3087860'>fact,</span>
  <span m='3088120'>the</span> <span m='3088210'>environment</span> <span m='3088750'>where</span>
  <span m='3089010'>this</span> <span m='3089200'>was</span> <span m='3089430'>defined</span>
  <span m='3090900'>with</span> <span m='3091020'>an</span> <span m='3091100'>extra</span>
  <span m='3091370'>frame</span> <span m='3091650'>in it that's</span> <span m='3091840'>empty.</span>
  <span m='3093132'>I</span> <span m='3093560'>don't</span> <span m='3093610'>care</span>
  <span m='3093830'>about</span> <span m='3094080'>that.</span> </p><p><span m='3096240'>Well,</span>
  <span m='3096570'>if</span> <span m='3096660'>we</span> <span m='3096750'>go</span>
  <span m='3096880'>back</span> <span m='3097130'>to</span> <span m='3097230'>this</span>
  <span m='3098860'>slide,</span> <span m='3101040'>since</span> <span m='3101370'>it's</span>
  <span m='3101520'>the</span> <span m='3101640'>case,</span> <span m='3102350'>if
  we</span> <span m='3102570'>look</span> <span m='3102700'>at</span> <span m='3102820'>this</span>
  <span m='3103010'>for</span> <span m='3103100'>a</span> <span m='3103190'>second,</span>
  <span m='3104280'>everything</span> <span m='3104700'>is</span> <span m='3104800'>the</span>
  <span m='3104880'>same</span> <span m='3105150'>as</span> <span m='3105210'>it</span>
  <span m='3105290'>was</span> <span m='3105590'>before</span> <span m='3106470'>except</span>
  <span m='3106950'>the</span> <span m='3107050'>case</span> <span m='3108210'>of</span>
  <span m='3108390'>applications</span> <span m='3109720'>or</span> <span m='3109850'>combinations.</span>
  <span m='3111980'>And</span> <span m='3112150'>combinations</span> <span m='3112710'>are</span>
  <span m='3112760'>going</span> <span m='3112860'>to</span> <span m='3112950'>do</span>
  <span m='3113070'>two</span> <span m='3113250'>things.</span> <span m='3114680'>One,</span>
  <span m='3114920'>is</span> <span m='3115000'>I</span> <span m='3115100'>have</span>
  <span m='3115190'>to</span> <span m='3115310'>evaluate</span> <span m='3116640'>the</span>
  <span m='3117100'>procedure--</span> <span m='3118010'>forget</span> <span m='3118310'>the</span>
  <span m='3118390'>procedure--</span> <span m='3118770'>by</span> <span m='3118920'>evaluating</span>
  <span m='3119280'>the</span> <span m='3119370'>operator.</span> <span m='3120425'>That's</span>
  <span m='3120840'>what  you</span> <span m='3121030'>see</span> <span m='3121200'>right</span>
  <span m='3121380'>here.</span> <span m='3122380'>I</span> <span m='3122440'>have</span>
  <span m='3122530'>to</span> <span m='3122630'>make</span> <span m='3122850'>sure</span>
  <span m='3123340'>that</span> <span m='3123620'>that's</span> <span m='3123920'>current,</span>
  <span m='3124490'>that</span> <span m='3124670'>is</span> <span m='3124770'>not
  a</span> <span m='3124990'>delayed</span> <span m='3125330'>object,</span> <span
  m='3126510'>and</span> <span m='3126640'>evaluate</span> <span m='3127130'>that</span>
  <span m='3127350'>to the</span> <span m='3127480'>point</span> <span m='3127740'>where</span>
  <span m='3128390'>it's</span> <span m='3128530'>forced</span> <span m='3129450'>now.</span>
  <span m='3130730'>And</span> <span m='3130910'>then</span> <span m='3131090'>I</span>
  <span m='3131200'>have</span> <span m='3131360'>to</span> <span m='3131520'>somehow</span>
  <span m='3132230'>apply</span> <span m='3132680'>that</span> <span m='3133310'>to</span>
  <span m='3133550'>the</span> <span m='3136580'>operands.</span> <span m='3138460'>But</span>
  <span m='3138570'>I</span> <span m='3138670'>have</span> <span m='3138770'>to</span>
  <span m='3138860'>keep</span> <span m='3139060'>the</span> <span m='3139210'>environment,</span>
  <span m='3139680'>pass</span> <span m='3139940'>that</span> <span m='3140040'>environmental</span>
  <span m='3140540'>along.</span> <span m='3141530'>So</span> <span m='3141880'>some</span>
  <span m='3142100'>of</span> <span m='3142170'>those</span> <span m='3142350'>operands</span>
  <span m='3142740'>I</span> <span m='3142800'>may</span> <span m='3142920'>have</span>
  <span m='3143050'>to</span> <span m='3143190'>delay.</span> <span m='3143710'>I</span>
  <span m='3144020'>may</span> <span m='3144150'>have</span> <span m='3144280'>to</span>
  <span m='3144370'>attach</span> <span m='3145390'>that</span> <span m='3145690'>environment</span>
  <span m='3146530'>to</span> <span m='3146660'>those</span> <span m='3146880'>operands.</span>
  </p><p><span m='3149302'>This is</span> <span m='3149910'>a</span> <span m='3149960'>rather</span>
  <span m='3150200'>complicated</span> <span m='3150760'>thing</span> <span m='3150920'>happening</span>
  <span m='3151280'>here.</span> <span m='3152990'>Looking</span> <span m='3153310'>at
  that in</span> <span m='3153570'>apply.</span> <span m='3156400'>Apply,</span> <span
  m='3156830'>well</span> <span m='3157100'>it</span> <span m='3157150'>has</span>
  <span m='3157310'>a</span> <span m='3157730'>primitive</span> <span m='3158100'>procedure</span>
  <span m='3159370'>thing</span> <span m='3159640'>just</span> <span m='3159870'>like</span>
  <span m='3160070'>before.</span> <span m='3162610'>But</span> <span m='3162870'>the</span>
  <span m='3162970'>compound</span> <span m='3163460'>one is a</span> <span m='3163710'>little</span>
  <span m='3163920'>more</span> <span m='3164120'>interesting.</span> <span m='3167250'>I</span>
  <span m='3167420'>have</span> <span m='3167600'>to</span> <span m='3167730'>evaluate</span>
  <span m='3168160'>the</span> <span m='3168230'>body,</span> <span m='3168570'>just</span>
  <span m='3168820'>as</span> <span m='3168920'>before,</span> <span m='3170550'>in</span>
  <span m='3170750'>an</span> <span m='3170920'>environment</span> <span m='3172310'>which</span>
  <span m='3172530'>is</span> <span m='3172770'>the</span> <span m='3173000'>result</span>
  <span m='3173410'>of</span> <span m='3173510'>binding</span> <span m='3174320'>some</span>
  <span m='3175640'>formal</span> <span m='3176010'>parameters</span> <span m='3176950'>to</span>
  <span m='3177190'>arguments</span> <span m='3178790'>in</span> <span m='3179050'>the</span>
  <span m='3179550'>environment.</span> <span m='3180290'>That's</span> <span m='3180540'>true.</span>
  </p><p><span m='3181530'>The</span> <span m='3181700'>environment</span> <span m='3182160'>is</span>
  <span m='3182240'>the</span> <span m='3182330'>one</span> <span m='3182520'>that</span>
  <span m='3182660'>comes</span> <span m='3182940'>from</span> <span m='3183070'>the</span>
  <span m='3183150'>procedure</span> <span m='3183580'>now.</span> <span m='3183820'>It's</span>
  <span m='3183950'>a</span> <span m='3184000'>lexical</span> <span m='3184390'>language,</span>
  <span m='3185640'>statically</span> <span m='3186030'>bound.</span> <span m='3188040'>However,</span>
  <span m='3189530'>one</span> <span m='3189800'>thing</span> <span m='3189930'>I</span>
  <span m='3190050'>have to</span> <span m='3190350'>do is</span> <span m='3190630'>strip</span>
  <span m='3190990'>off</span> <span m='3191150'>the</span> <span m='3191230'>declarations</span>
  <span m='3191830'>to</span> <span m='3191920'>get</span> <span m='3192070'>the</span>
  <span m='3192140'>names</span> <span m='3192390'>of the</span> <span m='3192480'>variables.</span>
  <span m='3192960'>That's</span> <span m='3193090'>what</span> <span m='3193190'>this</span>
  <span m='3193330'>guy</span> <span m='3193500'>does,</span> <span m='3194780'>vnames.</span>
  <span m='3195450'>And</span> <span m='3195650'>the other</span> <span m='3195850'>thing</span>
  <span m='3196170'>I have to</span> <span m='3196340'>do</span> <span m='3197050'>is</span>
  <span m='3197250'>process</span> <span m='3197730'>these</span> <span m='3197940'>declarations,</span>
  <span m='3199130'>deciding</span> <span m='3199710'>which</span> <span m='3199970'>of</span>
  <span m='3200420'>these</span> <span m='3200770'>operands--</span> <span m='3201770'>that's</span>
  <span m='3202120'>the</span> <span m='3202290'>operands</span> <span m='3202660'>now,</span>
  <span m='3202910'>as</span> <span m='3203020'>opposed</span> <span m='3203120'>to</span>
  <span m='3203220'>the</span> <span m='3203330'>arguments--</span> <span m='3204150'>which</span>
  <span m='3204380'>of</span> <span m='3204490'>these</span> <span m='3204610'>operands</span>
  <span m='3205080'>to</span> <span m='3205220'>evaluate,</span> <span m='3206730'>and</span>
  <span m='3206900'>which</span> <span m='3207110'>of</span> <span m='3207230'>them</span>
  <span m='3208010'>are</span> <span m='3208250'>to</span> <span m='3208400'>be</span>
  <span m='3211110'>encapsulated</span> <span m='3211880'>in</span> <span m='3212010'>delays</span>
  <span m='3213020'>of</span> <span m='3213150'>some</span> <span m='3213370'>sort.</span>
  </p><p><span m='3217280'>The</span> <span m='3217540'>other</span> <span m='3217730'>thing</span>
  <span m='3217910'>you</span> <span m='3218010'>see</span> <span m='3218220'>here</span>
  <span m='3218870'>is</span> <span m='3219050'>that</span> <span m='3219220'>we</span>
  <span m='3219400'>got a</span> <span m='3219530'>primitive,</span> <span m='3220630'>a</span>
  <span m='3220720'>primitive</span> <span m='3221140'>like</span> <span m='3221940'>plus,</span>
  <span m='3222690'>had</span> <span m='3222940'>better</span> <span m='3223170'>get</span>
  <span m='3223460'>at the</span> <span m='3223540'>real</span> <span m='3224960'>operands.</span>
  <span m='3225820'>So</span> <span m='3226030'>here</span> <span m='3226260'>is</span>
  <span m='3226410'>a place</span> <span m='3226500'>where</span> <span m='3226690'>we're
  going to have to</span> <span m='3226760'>force</span> <span m='3227070'>them.</span>
  <span m='3227690'>And</span> <span m='3228120'>we're</span> <span m='3228280'>going</span>
  <span m='3228330'>to</span> <span m='3228380'>look</span> <span m='3228630'>at what</span>
  <span m='3228830'>evlist</span> <span m='3229050'>is</span> <span m='3229120'>going</span>
  <span m='3229220'>to have to</span> <span m='3229350'>do</span> <span m='3229460'>a</span>
  <span m='3229510'>bunch</span> <span m='3229710'>of</span> <span m='3229780'>forces.</span>
  </p><p><span m='3231340'>So</span> <span m='3231480'>we</span> <span m='3231560'>have</span>
  <span m='3231670'>two</span> <span m='3231810'>different</span> <span m='3232040'>kinds</span>
  <span m='3232270'>of</span> <span m='3232440'>evlist</span> <span m='3232620'>now.</span>
  <span m='3232780'>We</span> <span m='3232980'>have</span> <span m='3233140'>evlist</span>
  <span m='3233440'>and</span> <span m='3233650'>gevlist.</span> <span m='3234570'>Gevlist</span>
  <span m='3235040'>is</span> <span m='3235150'>going</span> <span m='3235350'>to</span>
  <span m='3235750'>wrap</span> <span m='3235980'>delays</span> <span m='3236340'>around</span>
  <span m='3236670'>some</span> <span m='3236870'>things</span> <span m='3237210'>and</span>
  <span m='3237340'>force</span> <span m='3237620'>others,</span> <span m='3238900'>evaluate</span>
  <span m='3239330'>others.</span> <span m='3239870'>And</span> <span m='3240080'>this</span>
  <span m='3240250'>guy's</span> <span m='3240590'>going</span> <span m='3240810'>to</span>
  <span m='3240900'>do</span> <span m='3241500'>some</span> <span m='3243520'>forcing</span>
  <span m='3244505'>of</span> <span m='3244990'>things.</span> <span m='3247900'>Just</span>
  <span m='3248090'>looking</span> <span m='3248260'>at</span> <span m='3248430'>this</span>
  <span m='3248530'>a</span> <span m='3248580'>little</span> <span m='3248830'>bit,</span>
  <span m='3249710'>this</span> <span m='3249960'>is</span> <span m='3250060'>a</span>
  <span m='3250100'>game</span> <span m='3250450'>you</span> <span m='3250550'>must</span>
  <span m='3250770'>play</span> <span m='3250970'>for</span> <span m='3251070'>yourself,</span>
  <span m='3251570'>you</span> <span m='3251700'>know.</span> <span m='3252250'>It's</span>
  <span m='3252410'>not</span> <span m='3252700'>something</span> <span m='3253220'>that</span>
  <span m='3253770'>you're</span> <span m='3253920'>going</span> <span m='3254070'>to
  see</span> <span m='3254180'>all</span> <span m='3254450'>possible</span> <span
  m='3254870'>variations</span> <span m='3255610'>on an</span> <span m='3255850'>evaluator</span>
  <span m='3257420'>talking</span> <span m='3257800'>to</span> <span m='3257900'>me.</span>
  <span m='3259730'>What</span> <span m='3259880'>you</span> <span m='3259990'>have</span>
  <span m='3260110'>to</span> <span m='3260220'>do</span> <span m='3260390'>is</span>
  <span m='3260480'>do</span> <span m='3260600'>this</span> <span m='3260780'>for</span>
  <span m='3260840'>yourself.</span> <span m='3261410'>And</span> <span m='3261560'>after</span>
  <span m='3261710'>you</span> <span m='3261840'>feel</span> <span m='3262160'>this,</span>
  <span m='3262980'>you</span> <span m='3263090'>play</span> <span m='3263330'>this</span>
  <span m='3263530'>a</span> <span m='3263660'>bit,</span> <span m='3264330'>you</span>
  <span m='3264420'>get</span> <span m='3264570'>to</span> <span m='3264610'>see</span>
  <span m='3264780'>all</span> <span m='3264880'>the</span> <span m='3264980'>possible</span>
  <span m='3265320'>design</span> <span m='3265630'>decisions and</span> <span m='3266040'>what</span>
  <span m='3266230'>they</span> <span m='3266330'>might</span> <span m='3266580'>mean,</span>
  <span m='3267900'>and</span> <span m='3268040'>how</span> <span m='3268180'>they</span>
  <span m='3268280'>interact</span> <span m='3268660'>with</span> <span m='3268750'>each</span>
  <span m='3268910'>other.</span> <span m='3269930'>So</span> <span m='3270130'>what</span>
  <span m='3270360'>languages</span> <span m='3270790'>might</span> <span m='3270990'>have</span>
  <span m='3271980'>in</span> <span m='3272120'>them.</span> <span m='3273160'>And</span>
  <span m='3273290'>what</span> <span m='3273430'>are</span> <span m='3273570'>some
  of the</span> <span m='3273680'>consistent</span> <span m='3274200'>sets</span>
  <span m='3274970'>that</span> <span m='3275100'>make</span> <span m='3275290'>a</span>
  <span m='3275340'>legitimate</span> <span m='3275760'>language.</span> <span m='3277200'>Whereas</span>
  <span m='3277530'>what</span> <span m='3277700'>things</span> <span m='3277920'>are</span>
  <span m='3278010'>complicated</span> <span m='3278480'>kluges</span> <span m='3278670'>that</span>
  <span m='3278940'>are just</span> <span m='3279330'>piles</span> <span m='3279660'>of</span>
  <span m='3279730'>junk.</span> </p><p><span m='3281850'>So</span> <span m='3281990'>evlist</span>
  <span m='3282460'>of</span> <span m='3282640'>course,</span> <span m='3282830'>over</span>
  <span m='3283000'>here,</span> <span m='3283850'>just</span> <span m='3284060'>as</span>
  <span m='3284150'>I</span> <span m='3284280'>said,</span> <span m='3284840'>is</span>
  <span m='3284980'>a</span> <span m='3285050'>list</span> <span m='3285280'>of</span>
  <span m='3285380'>operands</span> <span m='3286700'>which</span> <span m='3287080'>are</span>
  <span m='3287310'>going</span> <span m='3287490'>to</span> <span m='3287660'>be</span>
  <span m='3288000'>undelayed</span> <span m='3289150'>after</span> <span m='3289450'>evaluation.</span>
  <span m='3290750'>So</span> <span m='3290960'>these are</span> <span m='3291070'>going</span>
  <span m='3291150'>to</span> <span m='3291240'>be</span> <span m='3291320'>forced,</span>
  <span m='3293290'>whatever</span> <span m='3293600'>that's</span> <span m='3293930'>going
  to</span> <span m='3294090'>mean.</span> <span m='3296050'>And</span> <span m='3296610'>gevlist,</span>
  <span m='3297070'>which</span> <span m='3297490'>is</span> <span m='3297830'>the</span>
  <span m='3298020'>next</span> <span m='3298210'>thing--</span> <span m='3301320'>Thank</span>
  <span m='3301600'>you.</span> </p><p><span m='3304040'>What</span> <span m='3304180'>we</span>
  <span m='3304300'>see</span> <span m='3304520'>here,</span> <span m='3307900'>well</span>
  <span m='3308230'>there's</span> <span m='3308420'>a</span> <span m='3308520'>couple</span>
  <span m='3308630'>of</span> <span m='3308730'>possibilities.</span> <span m='3309810'>Either</span>
  <span m='3310060'>it's</span> <span m='3310160'>a</span> <span m='3310210'>normal,</span>
  <span m='3310590'>ordinary</span> <span m='3311050'>thing,</span> <span m='3312570'>a</span>
  <span m='3312680'>symbol</span> <span m='3313030'>sitting</span> <span m='3313300'>there</span>
  <span m='3313750'>like</span> <span m='3314090'>the</span> <span m='3314330'>predicate</span>
  <span m='3315300'>in</span> <span m='3315450'>the</span> <span m='3315590'>unless,</span>
  <span m='3317680'>and</span> <span m='3317860'>that's</span> <span m='3318020'>what
  we</span> <span m='3318230'>have</span> <span m='3318440'>here.</span> <span m='3319390'>In</span>
  <span m='3319530'>which</span> <span m='3319670'>case,</span> <span m='3319990'>this</span>
  <span m='3320250'>is</span> <span m='3320450'>intended</span> <span m='3320860'>to</span>
  <span m='3320920'>be</span> <span m='3321090'>evaluated</span> <span m='3321400'>in</span>
  <span m='3321710'>applicative</span> <span m='3322180'>order.</span> <span m='3323340'>And</span>
  <span m='3323860'>it's,</span> <span m='3324000'>essentially,</span> <span m='3324440'>just</span>
  <span m='3324650'>what</span> <span m='3324730'>we</span> <span m='3324840'>had</span>
  <span m='3325030'>before.</span> <span m='3325630'>It's</span> <span m='3326120'>mapping</span>
  <span m='3326720'>eval</span> <span m='3328130'>down</span> <span m='3328440'>the</span>
  <span m='3328500'>list.</span> <span m='3330020'>In other words,</span> <span m='3330270'>I</span>
  <span m='3330400'>evaluate</span> <span m='3330990'>the</span> <span m='3331180'>first</span>
  <span m='3331420'>expression</span> <span m='3332750'>and</span> <span m='3333580'>continue</span>
  <span m='3334570'>gevlisting</span> <span m='3335460'>the</span> <span m='3335690'>CDR</span>
  <span m='3335840'>of</span> <span m='3336010'>the</span> <span m='3336110'>expression</span>
  <span m='3336540'>in</span> <span m='3336640'>the</span> <span m='3336740'>environment.</span>
  </p><p><span m='3337900'>However,</span> <span m='3338300'>it's</span> <span m='3338490'>possible</span>
  <span m='3339230'>that</span> <span m='3339470'>this</span> <span m='3339710'>is</span>
  <span m='3339900'>a</span> <span m='3341660'>name</span> <span m='3342540'>parameter.</span>
  <span m='3343600'>If</span> <span m='3344070'>it's</span> <span m='3344300'>a</span>
  <span m='3344360'>name</span> <span m='3344620'>parameter,</span> <span m='3345190'>I</span>
  <span m='3345340'>want</span> <span m='3345480'>to</span> <span m='3345620'>put</span>
  <span m='3345750'>a</span> <span m='3345790'>delay</span> <span m='3346200'>in</span>
  <span m='3347020'>which</span> <span m='3347320'>combines</span> <span m='3348170'>that</span>
  <span m='3348530'>expression,</span> <span m='3349260'>which</span> <span m='3349460'>I'm</span>
  <span m='3350080'>calling</span> <span m='3350390'>by</span> <span m='3350540'>name,</span>
  <span m='3353480'>with</span> <span m='3353660'>the</span> <span m='3353780'>environment</span>
  <span m='3355960'>that's</span> <span m='3356210'>available</span> <span m='3356860'>at</span>
  <span m='3357010'>this</span> <span m='3357160'>time</span> <span m='3359070'>and</span>
  <span m='3359250'>passing</span> <span m='3359630'>that</span> <span m='3359920'>as</span>
  <span m='3360060'>the</span> <span m='3360150'>parameter.</span> <span m='3362790'>And</span>
  <span m='3362970'>this</span> <span m='3363080'>is</span> <span m='3363140'>part</span>
  <span m='3363300'>of</span> <span m='3363450'>the</span> <span m='3363540'>mapping</span>
  <span m='3363940'>process</span> <span m='3364350'>that</span> <span m='3364440'>you</span>
  <span m='3364530'>see</span> <span m='3364670'>here.</span> </p><p><span m='3369070'>The</span>
  <span m='3369240'>only</span> <span m='3369540'>other</span> <span m='3369810'>interesting</span>
  <span m='3370160'>place</span> <span m='3370520'>in</span> <span m='3371850'>this</span>
  <span m='3372040'>interpreter</span> <span m='3372720'>is</span> <span m='3372930'>cond.</span>
  <span m='3374700'>People</span> <span m='3374970'>tend</span> <span m='3375180'>to</span>
  <span m='3375260'>write</span> <span m='3375520'>this</span> <span m='3375720'>thing,</span>
  <span m='3375930'>and then</span> <span m='3376000'>they</span> <span m='3376180'>leave</span>
  <span m='3376440'>this</span> <span m='3376620'>one</span> <span m='3376800'>out.</span>
  <span m='3378550'>There's</span> <span m='3378780'>a</span> <span m='3378820'>place</span>
  <span m='3379050'>where</span> <span m='3379130'>you</span> <span m='3379230'>have</span>
  <span m='3379390'>to</span> <span m='3379550'>force.</span> <span m='3380510'>Conditionals</span>
  <span m='3382130'>have</span> <span m='3382370'>to</span> <span m='3382500'>know</span>
  <span m='3384340'>whether</span> <span m='3384560'>or</span> <span m='3384610'>not</span>
  <span m='3384860'>the</span> <span m='3384970'>answer</span> <span m='3385180'>is</span>
  <span m='3385260'>true</span> <span m='3385420'>or</span> <span m='3385470'>false.</span>
  <span m='3385990'>It's</span> <span m='3386120'>like</span> <span m='3386300'>a</span>
  <span m='3386360'>primitive.</span> <span m='3388550'>When</span> <span m='3388740'>you</span>
  <span m='3388910'>do a</span> <span m='3389070'>conditional,</span> <span m='3389680'>you</span>
  <span m='3389820'>have</span> <span m='3389950'>to</span> <span m='3390090'>force.</span>
  </p><p><span m='3391890'>Now, I'm</span> <span m='3392020'>not</span> <span m='3392170'>going</span>
  <span m='3392230'>to</span> <span m='3392290'>look</span> <span m='3392420'>at</span>
  <span m='3392550'>any</span> <span m='3392700'>more</span> <span m='3392880'>of</span>
  <span m='3392980'>this</span> <span m='3393080'>in</span> <span m='3393190'>any</span>
  <span m='3393370'>detail.</span> <span m='3394350'>It</span> <span m='3394710'>isn't</span>
  <span m='3395320'>very</span> <span m='3395620'>exciting.</span> <span m='3396750'>And</span>
  <span m='3396910'>what's</span> <span m='3397130'>left</span> <span m='3397470'>is</span>
  <span m='3397990'>how</span> <span m='3398180'>you</span> <span m='3398320'>make</span>
  <span m='3398510'>delays.</span> <span m='3398990'>Well,</span> <span m='3399150'>delays</span>
  <span m='3399600'>are</span> <span m='3400040'>data</span> <span m='3400300'>structures</span>
  <span m='3401350'>which</span> <span m='3401610'>contain</span> <span m='3402540'>an</span>
  <span m='3402680'>expression,</span> <span m='3403180'>an</span> <span m='3403380'>environment,</span>
  <span m='3403820'>and</span> <span m='3403920'>a</span> <span m='3404010'>type</span>
  <span m='3404310'>on</span> <span m='3404520'>them.</span> </p><p><span m='3404840'>And</span>
  <span m='3404970'>it</span> <span m='3405060'>says</span> <span m='3405420'>they're</span>
  <span m='3405740'>a</span> <span m='3405820'>thunk.</span> <span m='3406680'>That</span>
  <span m='3407260'>comes</span> <span m='3407460'>from</span> <span m='3407580'>ALGOL</span>
  <span m='3407880'>language,</span> <span m='3409150'>and</span> <span m='3409580'>it's</span>
  <span m='3409750'>claimed</span> <span m='3410000'>to</span> <span m='3410100'>be</span>
  <span m='3410230'>the</span> <span m='3410310'>sound</span> <span m='3410700'>of</span>
  <span m='3410790'>something</span> <span m='3411110'>being</span> <span m='3411290'>pushed</span>
  <span m='3411490'>on</span> <span m='3411570'>a</span> <span m='3411640'>stack.</span>
  <span m='3412970'>I</span> <span m='3413140'>don't</span> <span m='3413280'>know.</span>
  <span m='3413410'>I</span> <span m='3413530'>was</span> <span m='3413660'>not</span>
  <span m='3413850'>an</span> <span m='3414070'>ALGOLician</span> <span m='3415170'>or</span>
  <span m='3415790'>an</span> <span m='3415930'>ALGOLite</span> <span m='3416540'>or</span>
  <span m='3416610'>whatever,</span> <span m='3417560'>so</span> <span m='3417730'>I</span>
  <span m='3417830'>don't</span> <span m='3418080'>know.</span> <span m='3418740'>But</span>
  <span m='3418860'>that's what</span> <span m='3419040'>was</span> <span m='3419220'>claimed.</span>
  </p><p><span m='3420270'>And</span> <span m='3420460'>undelay</span> <span m='3420990'>is</span>
  <span m='3421120'>something</span> <span m='3421870'>which</span> <span m='3422140'>will</span>
  <span m='3422320'>recursively</span> <span m='3422930'>undelay</span> <span m='3423400'>thunks</span>
  <span m='3423750'>until</span> <span m='3424010'>the</span> <span m='3424140'>thunk</span>
  <span m='3424530'>becomes</span> <span m='3424860'>something</span> <span m='3425120'>which</span>
  <span m='3425280'>isn't</span> <span m='3425500'>a</span> <span m='3425600'>thunk.</span>
  <span m='3427860'>This</span> <span m='3428130'>is</span> <span m='3428240'>the</span>
  <span m='3428310'>way</span> <span m='3428440'>you</span> <span m='3428620'>implement</span>
  <span m='3429140'>a</span> <span m='3429280'>call</span> <span m='3429480'>by</span>
  <span m='3429610'>name</span> <span m='3429930'>like</span> <span m='3430150'>thing</span>
  <span m='3430370'>in</span> <span m='3430625'>ALGOL.</span> <span m='3432050'>And</span>
  <span m='3432460'>that's</span> <span m='3432800'>about</span> <span m='3433060'>all</span>
  <span m='3433240'>there</span> <span m='3433450'>is.</span> </p><p><span m='3435210'>Are</span>
  <span m='3435340'>there</span> <span m='3435500'>any</span> <span m='3435630'>questions?</span>
  </p><p><span m='3446840'>AUDIENCE:</span> <span m='3447330'>Gerry?</span> </p><p><span
  m='3447560'>PROFESSOR:</span> <span m='3447880'>Yes,</span> <span m='3448460'>Vesko?</span>
  </p><p><span m='3449626'>AUDIENCE:</span> <span m='3450080'>I</span> <span m='3450200'>noticed</span>
  <span m='3450590'>you</span> <span m='3450760'>avoided</span> <span m='3452080'>calling</span>
  <span m='3452460'>by</span> <span m='3452610'>name</span> <span m='3453500'>in</span>
  <span m='3453660'>the</span> <span m='3453900'>primitive</span> <span m='3454280'>procedures,</span>
  <span m='3456360'>I</span> <span m='3456510'>was</span> <span m='3456660'>wondering</span>
  <span m='3458390'>what</span> <span m='3458480'>cause</span> <span m='3458690'>you
  have on</span> <span m='3459020'>that?</span> <span m='3459350'>You never</span>
  <span m='3459680'>need that?</span> </p><p><span m='3460070'>PROFESSOR:</span> <span
  m='3460460'>Vesko</span> <span m='3460680'>is asking</span> <span m='3462150'>if</span>
  <span m='3462440'>it's</span> <span m='3462610'>ever</span> <span m='3463440'>reasonable</span>
  <span m='3464060'>to</span> <span m='3464190'>call</span> <span m='3464600'>a</span>
  <span m='3464720'>primitive</span> <span m='3465060'>procedure</span> <span m='3465440'>by</span>
  <span m='3465620'>name?</span> <span m='3467140'>The</span> <span m='3467320'>answer</span>
  <span m='3467700'>is,</span> <span m='3467970'>yes.</span> <span m='3469270'>There's</span>
  <span m='3469650'>one</span> <span m='3469930'>particular</span> <span m='3470390'>case</span>
  <span m='3470790'>where</span> <span m='3471030'>it's</span> <span m='3471140'>reasonable,</span>
  <span m='3471680'>actually</span> <span m='3471960'>two.</span> <span m='3476050'>Construction</span>
  <span m='3476610'>of</span> <span m='3476700'>a</span> <span m='3476750'>data</span>
  <span m='3476960'>structure</span> <span m='3477440'>like</span> <span m='3477710'>cons</span>
  <span m='3479110'>where</span> <span m='3479250'>making</span> <span m='3479630'>an</span>
  <span m='3479700'>array</span> <span m='3480150'>if</span> <span m='3480280'>you</span>
  <span m='3480450'>have</span> <span m='3480690'>arrays</span> <span m='3481010'>with
  any</span> <span m='3481190'>number</span> <span m='3481400'>of</span> <span m='3481480'>elements.</span>
  <span m='3483690'>It's</span> <span m='3483950'>unnecessary</span> <span m='3485980'>to</span>
  <span m='3486190'>evaluate</span> <span m='3486740'>those</span> <span m='3486950'>arguments.</span>
  <span m='3487440'>All</span> <span m='3487610'>you</span> <span m='3487750'>need</span>
  <span m='3488000'>is</span> <span m='3488150'>promises</span> <span m='3489060'>to</span>
  <span m='3489220'>evaluate</span> <span m='3489610'>those</span> <span m='3489780'>arguments</span>
  <span m='3490100'>if</span> <span m='3490180'>you</span> <span m='3490300'>look</span>
  <span m='3490430'>at</span> <span m='3490550'>them.</span> <span m='3491160'>If</span>
  <span m='3491590'>I</span> <span m='3491740'>cons</span> <span m='3492290'>together</span>
  <span m='3494350'>two</span> <span m='3494610'>things,</span> <span m='3496300'>then</span>
  <span m='3496530'>I</span> <span m='3496750'>could</span> <span m='3496990'>cons</span>
  <span m='3497040'>together</span> <span m='3497220'>the</span> <span m='3497310'>promises</span>
  <span m='3497800'>just</span> <span m='3498020'>as</span> <span m='3498100'>easily</span>
  <span m='3498410'>as</span> <span m='3498490'>I</span> <span m='3498570'>can</span>
  <span m='3498710'>cons</span> <span m='3499090'>together</span> <span m='3499380'>the</span>
  <span m='3499510'>things.</span> <span m='3501830'>And</span> <span m='3502120'>it's</span>
  <span m='3502280'>not</span> <span m='3502400'>even when I</span> <span m='3502660'>CAR</span>
  <span m='3502990'>CDR</span> <span m='3503450'>them</span> <span m='3503580'>that
  I</span> <span m='3503720'>have to</span> <span m='3503810'>look</span> <span m='3503940'>at</span>
  <span m='3504070'>them.</span> <span m='3504840'>That</span> <span m='3504950'>just</span>
  <span m='3505120'>gets</span> <span m='3505340'>out</span> <span m='3505510'>the</span>
  <span m='3505590'>promises</span> <span m='3506020'>and</span> <span m='3506150'>passes</span>
  <span m='3506530'>them to</span> <span m='3506590'>somebody.</span> </p><p><span
  m='3508260'>That's</span> <span m='3508560'>why</span> <span m='3508710'>the</span>
  <span m='3508820'>lambda</span> <span m='3509160'>calculus</span> <span m='3509700'>definition,</span>
  <span m='3510250'>the</span> <span m='3510640'>Alonzo</span> <span m='3511070'>Church</span>
  <span m='3511320'>definition</span> <span m='3511650'>of</span> <span m='3512230'>CAR,</span>
  <span m='3512620'>CDR,</span> <span m='3513040'>and</span> <span m='3513130'>cons</span>
  <span m='3513385'>makes</span> <span m='3513640'>sense.</span> <span m='3514420'>It's</span>
  <span m='3514540'>because</span> <span m='3514810'>no</span> <span m='3514930'>work</span>
  <span m='3515140'>is</span> <span m='3515250'>done</span> <span m='3515500'>in CAR,</span>
  <span m='3515860'>CDR,</span> <span m='3515940'>and</span> <span m='3516390'>cons,</span>
  <span m='3516530'>it's just</span> <span m='3516730'>shuffling</span> <span m='3517120'>data,</span>
  <span m='3518180'>it's</span> <span m='3518350'>just</span> <span m='3518680'>routing,</span>
  <span m='3519080'>if</span> <span m='3519370'>you</span> <span m='3519660'>will.</span>
  </p><p><span m='3520760'>However,</span> <span m='3521320'>the</span> <span m='3521450'>things</span>
  <span m='3521700'>that</span> <span m='3521920'>do</span> <span m='3522100'>have</span>
  <span m='3522240'>to</span> <span m='3522330'>look</span> <span m='3522470'>at</span>
  <span m='3522540'>data</span> <span m='3522770'>are</span> <span m='3522960'>things</span>
  <span m='3523180'>like</span> <span m='3523370'>plus.</span> <span m='3525280'>Because</span>
  <span m='3525800'>they</span> <span m='3525860'>have</span> <span m='3526020'>a</span>
  <span m='3526060'>look</span> <span m='3526180'>at</span> <span m='3526310'>the</span>
  <span m='3526400'>bits</span> <span m='3526990'>that</span> <span m='3527320'>the</span>
  <span m='3527410'>numbers</span> <span m='3527760'>are</span> <span m='3527910'>made</span>
  <span m='3528050'>out</span> <span m='3528380'>of,</span> <span m='3528690'>unless
  they're</span> <span m='3529100'>lambda</span> <span m='3529440'>calculus</span>
  <span m='3530220'>numbers</span> <span m='3530530'>which</span> <span m='3530670'>are</span>
  <span m='3530730'>funny.</span> <span m='3532460'>They</span> <span m='3532690'>have</span>
  <span m='3532910'>to look at the</span> <span m='3532950'>bits</span> <span m='3533600'>to</span>
  <span m='3533810'>be</span> <span m='3534090'>able to</span> <span m='3534230'>crunch</span>
  <span m='3534520'>them</span> <span m='3534630'>together</span> <span m='3534920'>to</span>
  <span m='3535110'>do the</span> <span m='3535310'>add.</span> </p><p><span m='3539210'>So,</span>
  <span m='3539540'>in</span> <span m='3539650'>fact,</span> <span m='3540360'>data</span>
  <span m='3540680'>constructors,</span> <span m='3541820'>data</span> <span m='3542050'>selectors,</span>
  <span m='3543280'>and,</span> <span m='3543500'>in</span> <span m='3543600'>fact,</span>
  <span m='3543870'>things</span> <span m='3544090'>that</span> <span m='3544260'>side-effect</span>
  <span m='3544420'>data</span> <span m='3544850'>objects</span> <span m='3548300'>don't</span>
  <span m='3548500'>need</span> <span m='3548690'>to</span> <span m='3548790'>do</span>
  <span m='3549030'>any</span> <span m='3549230'>forcing</span> <span m='3551410'>in</span>
  <span m='3551770'>the</span> <span m='3551860'>laziest</span> <span m='3552400'>possible</span>
  <span m='3552810'>interpreters.</span> <span m='3556460'>On</span> <span m='3556550'>the</span>
  <span m='3556640'>other</span> <span m='3556760'>hand</span> <span m='3557000'>predicates</span>
  <span m='3557480'>on data</span> <span m='3557910'>structures</span> <span m='3558370'>have</span>
  <span m='3558530'>to.</span> <span m='3561710'>Is</span> <span m='3561890'>this</span>
  <span m='3562110'>a</span> <span m='3562230'>pair?</span> <span m='3563560'>Or</span>
  <span m='3563770'>is it a</span> <span m='3563920'>symbol?</span> <span m='3564640'>Well,
  you</span> <span m='3564850'>better</span> <span m='3565040'>find</span> <span m='3565370'>out.</span>
  <span m='3565690'>You got</span> <span m='3565830'>to look</span> <span m='3566010'>at</span>
  <span m='3566200'>it</span> <span m='3566310'>then.</span> <span m='3570300'>Any</span>
  <span m='3570500'>other</span> <span m='3570630'>questions?</span> <span m='3580050'>Oh,</span>
  <span m='3580150'>well,</span> <span m='3580350'>I</span> <span m='3580430'>suppose</span>
  <span m='3580680'>it's</span> <span m='3580810'>time</span> <span m='3581040'>for</span>
  <span m='3581120'>a</span> <span m='3581210'>break.</span> <span m='3581610'>Thank
  you.</span> <span m='3582106'>[MUSIC PLAYING]</span> <span m='3602950'>and</span>
  </p>
type: course
uid: d3c1342e5db4adedb66673bcbfda3491

---
None