
# 插件推荐


## VST

### Guitar

[Guitar VST Review and Comparison: Strawberry Evolution, RealStrat3, and AGF](https://www.youtube.com/watch?v=ctp4Vk_wx0c)

- Strawberry Evolution:

	声音很自然，很多预设都有很出色的音色。

	比较适合背景

- RealStrat3


- AGF

	比较适合solo

	扫弦模式的声音比较sloppy（松散）












# Sampling

## [Pro Tip - How To Tune Drum Samples To Your Track](https://www.youtube.com/watch?v=KCSZFUqWNuk)

可以用在各种drum上，put it in key

方法一：首先找准sample的pitch，让它和你的曲子调一致（fabfilter Q可以根据频谱这个功能）

方法二：tuner stock插件，看tuner把sample调到想要的pitch


## [How To Sample A Kick From ANY Song...](https://www.youtube.com/watch?v=VIcSXnlpvFk)

Tool: Multiband sidechain / volume shaper

BPM align -> cut Tail (fade out) -> Volume Shaper Plugin


## [取樣切切切！好玩的「懶人作曲法」，可以把盧廣仲的歌變成 lo-fi hip-hop？](https://www.youtube.com/watch?v=_Klaz8iFN0Q)

用Ableton的Simpler

三个全用模式：

- Classic

- 1-Shot

- Slice 切片
	- Gate模式（键盘按住的时候才播放，放掉就停止）
	- slice by transient：自动切在声音发出的瞬间
	- playback through：播放就自动继续播下一个切片
	- sensitivity：切片切的精确度


或者logic10.5的quick sampler也可以切片。







# Mix 混音

## Reverb

### [The Reverb Trick All The Pros Use... - clean up your mix, sound tighter](https://www.youtube.com/watch?v=ETvhemYVUh8&t=50s)

（和KSHMR人声reverb和delay的技巧一样）

不要直接给原轨道加混响，而是把原始轨信号发送到新的混响轨道，新的轨道设置100%wet混响，然后EQ同时高切和低切混响轨。

然后把混响轨以音频形式导出到新轨道（不输出），然后在混响轨道挂一个compressor，sidechain到音频轨道。



### [Lessons of KSHMR: Secret Reverb Tips](https://www.youtube.com/watch?v=ZcICh7UsPuU&t=207s)

1. sidechaining the reverb to the dry signal

新建一个Audio Effect Rack（cmd+G），一个dry轨，一个reverb轨（100%wet），sidechain到一个节奏和dry signal一致的轨上（sidechain轨道mute掉，只用来sidechain）。

如果把compressor放到reverb效果器之前，可以去除掉reverb里的crash噪音。（因为compressor在后，放大了噪音）

2. 和弦之间reverb不打架（当和弦变化太快，reverb可能相互混杂，如何处理）

新建一个Audio Effect Rack， 新建一个Reverb Switch轨道，加上100%混响效果器，把它的混响开关自动化做在每个和弦进入的音头位置，然后马上关掉，再打开。

reverb chain上最后挂一个utility插件，它要配合每个reverb效果器的突然关掉的部分，去除click声音。

3. reverse Reverb to glue notes of melody together

把混响输出成音频到新轨道上，然后切片一些关键节奏点，reverse混响，再加一个fade in。

4. Introduce a new instrument / vocal

把待引入的人声的第一句截取出来，复制到一个新轨道上，reverse，然后加上reverb效果器（100%wet），再reverse一遍，和原轨道一起播放。（可以再reverb效果器之前再挂个自动的ping pong delay使效果更好）


5. 给低频声部的乐器增加宽度

将它以音频导出到新轨道，然后提高12半音（高八度），挂上simple delay（100%）和reverb（100%），最后挂个eq低切。

也可以再做一个新轨，提高两个八度（相同的处理）







## [The Ultimate Mixing Guide for EDM (Part 1)](https://www.youtube.com/watch?v=_756jb7Swic)

- use a reference track（最强大的混音利器）

recommended referencing plugin: Magic AB

把AB插件挂在master轨最后。

首先可以loop你的歌和reference track的drop部分，然后调到大致相同的响度水平，再进行接下来的mix对比

然后把各个bus（lead，bass，pad，drum【Kick】）的音量从0db慢慢调高，不断AB，直到你的曲子的bus和reference track的对应bus响度水平大致相同。可能也需要在你的lead bus里的不同lead之间做音量的均衡，以更贴近reference track。

- Big Z的个人技巧：EQ-specific referencing：逐频段去AB。

在AB插件后最后挂一个EQ，solo要AB的频段。

大概确保每个频段的音量水平相近就好，不要求完全一样。

	- bass频段(80-300Hz)：比较音量，根据和参考轨的差距，去调整自己bass的音量（如果有多个bass，调频段最接近的那个），以及调整EQ来使声音更接近，或者消除harsh频段。
	- 中频（300-1kHz）：同上
	- 高频（1k-5kHz）：同上
	- 超高频（5kHZ以上）：






## [KSHMR-让Drop更强力](https://www.youtube.com/watch?v=ggPFSHV-6rA&list=PL1PEZ--NZi2I7-EwhyomvXDGoopREzTGc&index=9)

Bass: Sub bass（可以做一些pitch automation，使得声音更有趣） + gritty bass (音域更高的bass，使得bass整体在mix中更突出(可以适当提高极高频)，同时要切掉极低频，给sub bass腾出空间)


Lead：Main Lead（ping pong delay可以给予很强的空间感） + 不同lead间的 call response + super saw去突出其它的leads。鼓励用简单的旋律，留出空间用reverb填补。

Strings：用less synthy的乐器使得整体更人性化，更有趣

Top Drums：drop开头的crash（side chain一下），最后一节的crash（可以pan到左右，更有趣）和reversed crash

automated Vocal chops：add tension，不断推进drop

## [混一首歌的完整流程](https://www.youtube.com/watch?v=LYe1UcWk4qI&t=83s)

记住：混音是无数小的变化叠加在一起的效果，永远不要指望一个操作可以突然让整首歌听起来好很多。

- 歌曲结构tag

- side chain调整

drop部分，画上synth，bass的sidechain曲线

- reference track

先把整体调整到和参考曲相同的响度水平，然后用ab软件去对比不同元素的音量占比，并相应地调整音量。

【先混鼓组+bass（mute其它轨先）】

由于贝斯频率不太好听出音量的差异，所以可以用ab软件后的EQ插件去solo要对比的频率段，来判断和参考曲的差别。

bass元素：用扫频法移除不悦耳的频率；

鼓组元素：比较不同频段的鼓元素音量的差别，以及kick的putch、depth，snare的bass的差别。

【加入/unmute synth】

也是类似鼓组和bass的方式，针对不同的频段去逐段调整。


## 不同乐器混法

### Vocal

#### [How To Make Vocals Sound HUGE](https://www.youtube.com/watch?v=iwnGoLIW-vM)

如何没有多条人声录音轨，如何只用一条人声轨做出立体声。

- 复制单音轨到两个新轨道LR，分别pan到最左最右

现在LR两个音轨是一模一样的，需要改变一些特性（pitch,timing,formant）让它们听起来不太一样

- pitch & timing

如果录的是多条人声，多条人声每个词的pitch肯定都是有一点不一样的（很微小的不一样），我们利用这个原理，用调音高软件（比如melodyne）去微调L轨的音高

如果是melodyne，可以一键微调所有音符的timeing和pitch：选中所有notes，然后选择edit->Add Ramdom Deviations。

- formant

如果是melodyne，选中工具栏的formant工具，然后就可以改变formant了。

LR轨可以分别把整体formant调高和调低

最后mix原干声轨和LR轨就可以了（逐渐引入LR轨的音量）。







### Drum


#### [Lessons of KSHMR: Five Tips for Snares](https://www.youtube.com/watch?v=b4ONZKNW61o&list=PL1PEZ--NZi2I7-EwhyomvXDGoopREzTGc&index=6)

- How to find the key of the snare

用肥波Q2的音高显示功能，找到snare的共振点。


- How to gate a snare

如果snare的混响尾巴太长，可以给return轨后面挂一个gate插件，把多余的混响消除掉。


- 让snare更powerful

加一层噪音，用gate插件sidechain到snare上。（噪音层还可以加reverb和另一个gate来增强效果）

- snare roll

用一个snare采样，放到三个不同的按键上，每个采样都用不一的随机eq增加声音声音的差异，并且其中两个snare分别pan到左右两边一点。

每个采样后面还可以单独挂reverb轨（和发送到混响return轨是一样的效果），然后还可以挂utility做音量自动化（可以make tension等），最后再挂个compressor，sidechain到干声轨道，防止干扰干声。

- control the width of snare

直接用utility插件的width去改，可能产生相位抵消问题。

但是utility可以选择只采样左侧或者右侧的声音，但是同时在两边播放。


- create movement with snares

用preshift snare替代pure snare。

将原本的snare sample给reverse一下，然后放在原本的sample前面一点，去掉原sample的后面部分，这样就在原sample的基础上加了前置声响，更有意思。









### guitar

### Piano

#### [Make your piano sound dope](https://www.youtube.com/watch?v=Naatm19hDI0)

- M1 Piano

Mono Piano

1.first add some stereo imaging to it - izotope stereo image

勾选stereosize，然后适当调整width

2.compression

fabfilter C2

调整threshold获得平均2-3db的压缩

调高一点attack，让钢琴的attack声音进来，使声音达到一种比较好的状态

增加一点wet gain（make up gain）

再增加一点dry gain（干声的输出分贝）

最终效果：钢琴声整体听起来更紧致，不松散

3.EQ

扫频bell curve所有的harsh频段（越高频率的bell的Q值越大，切除db数越小）

800-1200 muddy frequency常出现的频段，扫频bell curve。

由于EQ削弱了一些高频，再用Multiband Saturator（e.g. fabfilter Saturn）提升一点高频作为补偿

用oeksound的soothe插件，看能不能去除更多EQ不好去除的harsh频率。

4.Add Reverb and Delay

注意：不要让reverb和delay过多淹没了干声

- Kontakt Piano（Maverick）

这个piano声音本身比较soft，而且已经比较wide了，不用再add stereo image了。

后续处理流程类似M1 Piano。

总结，所有的处理都是subtle effect，stereo效果调到适中，EQ拿掉harsh频段。


## Compression

[How To Use Compression - Detailed Tutorial](https://www.youtube.com/watch?v=yi0J9JsRdI4&t=576s)

## EQ


### EQ怎么混人声

- [人声融不进mix？三步人声EQ公式](https://www.youtube.com/watch?v=qdDDVortvRU)

1. Step 1: High Pass Filter 低频切除

把人声中不必要的极低频去掉，这些极低频会使人声在mix中显得“脏”。一般cutoff的点是80-120HZ，具体取决于听觉。

调整cutoff点时，【一定要在mix中听】（这一点很重要，任何时候做混音都应该是在mix中调，因为solo听起来好听和mix里听起来好听完全是两码事！）

2. Step 2: A Shelfing Filter 高频shelf提升

cutoff点大概在8kHz，提升这以上的频率（1-6dB），可以提升人声的明亮度。

3. Step 3: The Sweep 扫频

EQ提升扫频，降低尖锐的频率（通常在1KHz左右）。


额外提示：

- 针对不同的音乐风格有不同的提升方式，比如说有些音乐风格要让人声更清晰/明亮（嘻哈/摇滚等），可以提升2k-5kHz的频率段。
- 一般使得人声脱离mix的频段都是中低频，所以也可以适当降低中低频使人声更加sit in。
- 如果boost/cut某些频段使得人声过大/更小，相应降低/提升音量即可。





- [Kshmr的人声混音教程](https://www.youtube.com/watch?v=GIcuVlOQ3SQ&t=134s)

1. 事先将干声音量明显过大过小的clip的音量整体调整一下，给后续compressor少一点工作量。

2. EQ：低切所有人声基频到不了的地方，一般100Hz一下可以直接切，shelf boost on 高频部分，让声音更亮

3. Compressor：3-5dB的平均压缩量（CLA-2A e.g.）。可以叠加多个不同的压缩（Renaissance Vox e.g.），同样调整阈值让压缩量在3-5dB。

4. Add Reverb and Ping pong Delay：可以将干声、delay、reverb做成不同的channel，delay和reverb的channel后加上input为干声的compressor，以确保delay和reverb不会干扰干声的表现。

5. EQ：7-10KHz的频段适当提升，可以给人声提供更亮的感觉。

6. 想要更丰满的声音，可以叠加多个录制，分别pan到两边（doubles）。但是容易出现的一种问题是，多次录制的一些词语的时间差会造成不和谐，特别是b、p音节。所以需要将辅助音轨调成warp模式，然后做词语的微调拉伸。

7. harmonies：类似doubles，但唱的和旋律不一样。




# Master 母带

## [Master应该多大响度](https://www.youtube.com/watch?v=xTLA648ll7I&list=PLSS6kttCOax67OiNbRgNxMpnJOJyFSCaA&index=24)

比流平台限制更高一点的master响度虽然会使整个轨道的最响部分遭到一定压缩，但是低音部分也会相应被提升，使得整首歌虽然丢失一些动态，但是更有一种in your face的感觉。

Spotify: -14 LUFS
Youtube: -8 LUFS

## [7步master公式](https://www.youtube.com/watch?v=k0FpX200S1s)

- master的目的
	- 最终瑕疵检查修正
	- 不同监听设备的效果一致性
	- 改善提升（大声 + 好听 ）
	- 专辑flow
	- 最终成形


- 第一步 将多轨混音后的结果音频导出，96kHz 24bit采样率是比较标准的，并选择2-3个参考曲放到master项目中对比。
	- 没有专业参考曲的master就像盲人摸象
	- 尽量用音响，而不是耳机来mastewr
	- 在不同的音量水平、设备和不同的站位听

- 第二步：Fix it
	- 如果发现有额外的噪音、尖锐的cymbals，突出的频率，过度压缩，distorted/dipping tracks等严重的问题，直接回到mix阶段，而不要尝试master阶段去修复。

- 第三步： Enhance it
	- 只要是能让整体更好听的做法都应该尝试，很多小的改进最后加总会产生很不一样的效果。
	- 可以尝试的效果器：EQ、Tape Emulator，Exciter，Compressor, Bass Enhancer, Stereo Widener


- 第四步：


## [10minMaster流程](https://www.youtube.com/watch?v=m0Jx2h-lQkA)

- referencing a good song similar to your song

用参考曲时，记得把参考曲的音量低一点，因为参考曲已经是master过的，这样才能保证对比客观。

找到和参考曲相差的地方，然后用四样工具调整：

- EQ

根据参考曲来调，比如人声靠前，低频提升，高频提升等。

（一定要是很subtle的调整【0-2dB】，因为master影响的是整个track。）

- Compressor [gives more energy]

平行压缩（调整压缩器比例）

- Limiter (Make it Louder)

将celling设为[-1, -0.5]dB，防止声音处理的抖动。

降低threshold，直到歌曲最大声的部分在-10LFUS



## [Ableton母带流程](https://www.youtube.com/watch?v=iejvS8_xuac&list=PLOctUQcLxBKyWWAeItQscKuMckOBbnrMn&index=25)

1. EQ8

M/S Mode，切掉Side 100Hz以下的低频（低频集中在中间）

2. EQ8

切掉40Hz以下的极低频，让整体声音更紧致，压缩器也不用针对无用的极低频进行工作

切掉18kHz以上的极高频，一般是harsh sounds

3. Glue Compressor

调整threshold直到平均压缩3-5dB的声音，再用make up gain提升3-5dB。（主要用耳朵听，不要过度压缩）

4. OTT

给声音整体染色，提升一点音量。但是不要过度（less than 30% wet）

5. Saturator （【A little warmer】 preset）

10-20% wet，让声音整体更亮，更刺激一点，少许，不要太高不然会听到distortion效果。

6. EQ Eight

M/S mode，去除Side部分之前效果器给带来的低频杂音（cutoff一般在120Hz左右）

7. Glue Compressor

让整体音量更均衡，依然是压缩3-5dB，gain提升3-5dB，slow attck，quick release，4:1 ratio。

8. Limiter

看drop/chorus部分master轨，一般提升gain到平均压缩3-5dB（celling=-0.5/-1dB）。




# Trick

## 节奏

### 怎么制造活泼的节奏

1. 《暗号》 - 周杰伦

左边pan一个八分的沙锤，极其微妙，极其带感，谁用谁知道。

## 制造缥缈的感觉

1. 《Roses》- Chainsmokers


开始的airy 合成器的声音，配上Kickstart的8分音符的sidechain，就变得非常缥缈


## 人声

### 人声和声

1. 《Roses》- Chainsmokers

男声低八度垫在女声之下，可以给声音加一层质感，因为更低，相当于贝斯，所以也有更稳的感觉。

《Roses》的buildup之前，把两轨录的女声放在中间，两轨男声分别pan在极左和极右。


### 人声切片

1. 《Roses》- Chainsmokers

直接把人声丢进Ableton里的sampler，然后玩单音，就可以玩出《Roses》里面的那种效果。

另外，把混响大的不尖锐Lead和切片叠在一起，也可以增加人声的质感。


## 混响过度

1. 《Roses》- Chainsmokers

段落处突然提升某主要乐器/人声的混响比例，达到过渡的效果


## 鼓


### Drop的鼓和Verse的鼓用同一个

1. 《Roses》- Chainsmokers

在Drop部分用的和Verse一样的鼓，只是调高了Velocity，鼓更有力了一些。


## 叠声音

### 大道至简 Less is more

1. 《Roses》- Chainsmokers

Drew提到说他们用声音不喜欢叠很多，因为发现早期这样干的时候mix有大麻烦，还不如就用最少的声音去达到效果。

当发现一个声音不够wide，不够low，就换一个声音，而不是去不断地叠声音。


### 怎么让声音叠的尽可能大

1. 《Roses》- Chainsmokers

不同声部的声音不走完全相同的melody，而是组合在一起，在不同声部发挥作用。

比如，高音的chord和低音的bass配合，如果chord下来了，bass可以往上走，互相配合。

《Roses》里面，用了一个saw bass去走和弦根音，然后用一个808 bass去和super saw chord打配合，此消彼长。
