# 音程（Interval）

> In music theory, an interval is a difference in pitch between two sounds.
> -- <cite>[Wikipedia](<https://en.wikipedia.org/wiki/Interval_(music)>)</cite>

- 理解
  - Wikipedia 强调的是两个音之间的不同，其实我们主要关心的是两个音的距离；这应该是为什么中文翻译为音程
  - 中文维基：音程（Interval）是一个特定乐音体系中，两个音之间音高的距离

## 音程的单位

### 半音（Semitone）

> A semitone, also called a half step or a half tone, is the smallest musical interval commonly used in Western tonal music, and it is considered the most dissonant when sounded harmonically.
> -- <cite>[Wikipedia](https://en.wikipedia.org/wiki/Semitone)</cite>

- 理解
  - 半音是常用的最小音程单位

### 全音（Whole Tone）

> In Western music theory, a major second (sometimes also called whole tone or a whole step) is a second spanning two semitones.
> -- <cite>[Wikipedia](https://en.wikipedia.org/wiki/Major_second)</cite>

- 理解
  - 全音是两个半音；有时候也叫大二度（Major Second）

### 音分（Cent）

> The cent is a logarithmic unit of measure used for musical intervals. Twelve-tone equal temperament divides the octave into 12 semitones of 100 cents each.
> -- <cite>[Wikipedia](<https://en.wikipedia.org/wiki/Cent_(music)>)</cite>

- 理解
  - 音分是一个半音的百分之一，通常用于度量极小的音程
  - 某些调音软件上会以音分为单位显示和标准音的差距；通常误差十个音分之内是可以接受的

## 音程的名称

> In Western music theory, an interval is named according to its number (also called diatonic number) and quality.
> -- <cite>[Wikipedia](<https://en.wikipedia.org/wiki/Interval_(music)#Interval_number_and_quality>)</cite>

### 度数（Number）

> The number of an interval is the number of letter names or staff positions (lines and spaces) it encompasses, including the positions of both notes forming the interval.
> -- <cite>[Wikipedia](<https://en.wikipedia.org/wiki/Interval_(music)#Number>)</cite>

- 理解
  - 有几个音就是几度。升降记号不影响度数
- 实例
  - C 到 E 的音程是三度，因为 CDE 有三个音
  - C 到 E♭ 的音程也是三度，因为 CDE 还是三个音
  - C 到 D♯ 的音程是二度，因为 CD 是两个音
  - 尽管 D♯ 和 E♭ 是同一个音，但是作为不同名字来使用的时候，算出来的音程是不同的

### 形态（Quality）

> The name of any interval is further qualified using the terms perfect (P), major (M), minor (m), augmented (A), and diminished (d). This is called its interval quality.
> -- <cite>[Wikipedia](<https://en.wikipedia.org/wiki/Interval_(music)#Quality>)</cite>

- 理解

  - 基本规则是：1，4，5，8 度的形态有 Perfect（纯或者完全），Augmented（增），Diminished（减）；2，3，6，7 度的形态有 Major（大），Minor（小），Augmented（增），Diminished（减）；根据音数（音程内所含半音的个数）来决定形态
  - 1，4，5，8 度的 Perfect 形态分别包含 0，5，7，12 个半音
    - 如果音数多一个，则称为 Augmented（增）音程，多两个，则为 Double Augmented（倍增）音程；理论上还存在倍倍增音程，实际应用中倍增音程及以上很少见
    - 如果音数少一个，则称为 Diminished（减）音程，少两个，则为 Double Diminished（倍减）音程；理论上还存在倍倍减音程，实际应用中倍减音程及以上很少见
  - 2，3，6，7 度的 Major 形态分别包含 2，4，9，11 个半音
    - 如果音数多一个，则称为 Augmented（增）音程，多两个，则为 Double Augmented（倍增）音程；理论上还存在倍倍增音程，实际应用中倍增音程及以上很少见
    - 如果音数少一个，则称为 Minor（小）音程
    - 如果音数少两个，则称为 Diminished（减）音程，少三个，则为 Double Diminished（倍减）音程；理论上还存在倍倍减音程，实际应用中倍减音程及以上很少见

- 实例

  - C 到 G♯ 是增五度，因为 CDEFG 有五个音，并且 C 到 G♯ 之间有 8 个半音，比纯五度的 7 个半音多一个，所以是增五度，记做 A5
  - C 到 G 是纯五度，因为 CDEFG 有五个音，并且 C 到 G 之间有 7 个半音，所以是纯五度，记做 P5
  - B 到 F 是减五度，因为 BCDEF 有五个音，并且 B 到 F 之间有 6 个半音，比纯五度的 7 个半音少一个，所以是减五度，记做 d5
  - C♭ 到 E 是增三度，因为 CDE 有三个音，并且 C♭ 到 E 之间有 5 个半音，比大三度的 4 个半音多一个，所以是增三度，记做 A3
  - C 到 E 是大三度，因为 CDE 有三个音，并且 C 到 E 之间有 4 个半音，所以是大三度，记做 M3
  - D 到 F 是小三度，因为 DEF 有三个音，并且 D 到 F 之间有 3 个半音，比大三度的 4 个半音少一个，所以是小三度，记做 m3
  - D♯ 到 F 是减三度，因为 DEF 有三个音，并且 D♯ 到 F 之间有 2 个半音，比小三度的 3 个半音还少一个，所以是减三度，记做 d3
