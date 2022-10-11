# Preprocessing-of-MIDI-data
Preprocessing of MIDI data

## pretty_midi
https://craffel.github.io/pretty-midi/

## pypianoroll
https://salu133445.github.io/pypianoroll/

## mido
https://mido.readthedocs.io/en/latest/

## midi-toolkit
https://github.com/YatingMusic/miditoolkit

MidiFileクラス
- ticks_per_beat:4分音符を何tickで表すか(480tickで表すのが一般的）

- max_tick:音符の中で最大のtick数

- tempo_changes:テンポについての情報
  - [TempoChange(tempo=BPM, time=開始時間)]

- time_signature_changes:拍子記号についての情報
  - [TimeSignature(numerator=分子, denominator=分母, time=開始時間)]

- key_signature_changes:キーについての情報
  - [KeySignature(key_name=調, key_number=調の番号, time=開始時間)]

- markers:注目点についての情報（用途がよくわからんがギターソロとかにつけるのかな？）

- lyrics:歌詞についての情報(これも何に使えるかはよくわからん、Noteごとに文字割り当てれたら面白そう？）

- instruments:トラックごとにNote情報が入っている


Note(音符の情報)

- start:開始時間（tick）
- end:終了時間（tick）
- pitch:音程
- velocity:音量

to be continued...
