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
- ticks per beat:4分音符を何tickで表すか(480tickで表すのが一般的）
- max tick:音符の中で最大のtick数
- tempo changes:テンポについての情報
  - [TempoChange(tempo=BPM, time=開始時間)]
- time sig:拍子記号についての情報
  - [TimeSignature(numerator=分子, denominator=分母, time=開始時間)]
- key sig:キーについての情報
  [KeySignature(key_name=調, key_number=調の番号, time=開始時間)]
- markers: 
- lyrics: 
- instruments: 
