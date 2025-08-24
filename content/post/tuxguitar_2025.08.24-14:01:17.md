+++
author = "Akaky Chertyhansky"
title = 'Tuxguitar Shortcuts'
date = 2025-08-24T14:01:17+05:00
description = "Забацал кастомную хоткеизацию"
tags = [
    "linux",
    "keyboard",
    "tuxguitar",
]
categories = [
    "linux",
    "guitar",
]
+++

## Описание

Будет позже

## Код

~/.config/tuxguitar/config/shortcuts.xml

```
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<shortcuts TG_version="1.6.6">
    <shortcut action="action.song.new" keys="Ctrl n"/>
    <shortcut action="action.file.save-as" keys="Shift Ctrl s"/>
    <shortcut action="action.file.save" keys="Ctrl s"/>
    <shortcut action="action.file.open" keys="Ctrl o"/>
    <shortcut action="action.file.close-current" keys="Ctrl w"/>
    <shortcut action="action.file.print" keys="Ctrl p"/>
    <shortcut action="action.file.print-preview" keys="Ctrl Shift p"/>
    <shortcut action="action.edit.repeat" keys="Ctrl r"/>
    <shortcut action="action.edit.undo" keys="Ctrl z"/>
    <shortcut action="action.edit.redo" keys="Ctrl y"/>
    <shortcut action="action.edit.set-mouse-mode-selection" keys="Shift v"/>
    <shortcut action="action.edit.set-mouse-mode-edition" keys="Shift e"/>
    <shortcut action="action.edit.voice-1" keys="q"/>
    <shortcut action="action.edit.voice-2" keys="e"/>
    <shortcut action="action.caret.go-right" keys="d"/>
    <shortcut action="action.caret.go-left" keys="a"/>
    <shortcut action="action.caret.go-up" keys="w"/>
    <shortcut action="action.caret.go-down" keys="s"/>
    <shortcut action="action.track.add-new" keys="Shift Ctrl Ins"/>
    <shortcut action="action.track.change-mute" keys="Alt m"/>
    <shortcut action="action.track.change-solo" keys="Alt s"/>
    <shortcut action="action.track.go-first" keys="Ctrl Up"/>
    <shortcut action="action.track.go-last" keys="Ctrl Down"/>
    <shortcut action="action.track.go-next" keys="Down"/>
    <shortcut action="action.track.go-previous" keys="Up"/>
    <shortcut action="action.track.move-down" keys="Shift Ctrl Down"/>
    <shortcut action="action.track.move-up" keys="Shift Ctrl Up"/>
    <shortcut action="action.track.remove" keys="Shift Ctrl Del"/>
    <shortcut action="action.measure.go-first" keys="Home"/>
    <shortcut action="action.measure.go-last" keys="End"/>
    <shortcut action="action.measure.go-next" keys="Right"/>
    <shortcut action="action.measure.go-previous" keys="Left"/>
    <shortcut action="action.note.general.clean-beat" keys="Ctrl Del"/>
    <shortcut action="action.note.general.decrement-semitone" keys="Shift Left"/>
    <shortcut action="action.beat.general.delete-note-or-rest" keys="NumEnter"/>
    <shortcut action="action.note.general.increment-semitone" keys="Shift Right"/>
    <shortcut action="action.beat.general.insert-rest" keys="Ins"/>
    <shortcut action="action.beat.general.voice-auto" keys="Ctrl a"/>
    <shortcut action="action.note.general.shift-down" keys="Shift Down"/>
    <shortcut action="action.note.general.shift-up" keys="Shift Up"/>
    <shortcut action="action.note.general.set-fret-number-0" keys="0"/>
    <shortcut action="action.note.general.set-fret-number-1" keys="1"/>
    <shortcut action="action.note.general.set-fret-number-2" keys="2"/>
    <shortcut action="action.note.general.set-fret-number-3" keys="3"/>
    <shortcut action="action.note.general.set-fret-number-4" keys="4"/>
    <shortcut action="action.note.general.set-fret-number-5" keys="5"/>
    <shortcut action="action.note.general.set-fret-number-6" keys="6"/>
    <shortcut action="action.note.general.set-fret-number-7" keys="7"/>
    <shortcut action="action.note.general.set-fret-number-8" keys="8"/>
    <shortcut action="action.note.general.set-fret-number-9" keys="9"/>
    <shortcut action="action.note.effect.change-accentuated" keys="Shift ."/>
    <shortcut action="action.note.effect.change-dead" keys="x"/>
    <shortcut action="action.note.effect.change-fade-in" keys="Shift ,"/>
    <shortcut action="action.note.effect.change-ghost" keys="g"/>
    <shortcut action="action.note.effect.change-hammer" keys="h"/>
    <shortcut action="action.note.effect.change-heavy-accentuated" keys="Shift z"/>
    <shortcut action="action.note.effect.change-let-ring" keys="l"/>
    <shortcut action="action.note.effect.change-palm-mute" keys="m"/>
    <shortcut action="action.note.effect.change-slide" keys="z"/>
    <shortcut action="action.note.effect.change-staccato" keys="Shift s"/>
    <shortcut action="action.note.effect.change-tapping" keys="t"/>
    <shortcut action="action.note.effect.change-vibrato" keys="v"/>
    <shortcut action="action.note.duration.change-division-type" keys="/"/>
    <shortcut action="action.note.duration.change-dotted" keys="."/>
    <shortcut action="action.note.duration.change-double-dotted" keys="*"/>
    <shortcut action="action.note.duration.increment-duration" keys="-"/>
    <shortcut action="action.note.duration.decrement-duration" keys="+"/>
    <shortcut action="action.transport.play" keys="Space"/>
    <shortcut action="action.transport.metronome" keys="Shift m"/>
    <shortcut action="action.transport.count-down" keys="Shift"/>
    <shortcut action="action.transport.set-loop-start" keys="Alt Ctrl s"/>
    <shortcut action="action.transport.set-loop-end" keys="Alt Ctrl e"/>
    <shortcut action="action.marker.go-previous" keys="Alt Left"/>
    <shortcut action="action.marker.go-next" keys="Alt Right"/>
    <shortcut action="action.marker.go-first" keys="Alt Shift Left"/>
    <shortcut action="action.marker.go-last" keys="Alt Shift Right"/>
    <shortcut action="action.view.layout-increment-scale" keys="Shift ="/>
    <shortcut action="action.view.layout-decrement-scale" keys="Shift -"/>
    <shortcut action="action.gui.open-settings-editor" keys="F7"/>
    <shortcut action="action.gui.open-song-info-dialog" keys="F5"/>
    <shortcut action="action.gui.open-tempo-dialog" keys="Alt Ctrl m"/>
    <shortcut action="action.gui.open-clef-dialog" keys="Alt Ctrl c"/>
    <shortcut action="action.gui.open-key-signature-dialog" keys="Shift Ctrl k"/>
    <shortcut action="action.gui.open-time-signature-dialog" keys="Shift Ctrl t"/>
    <shortcut action="action.gui.open-triplet-feel-dialog" keys="Ctrl 3"/>
    <shortcut action="action.gui.open-stroke-up-dialog" keys="k"/>
    <shortcut action="action.gui.open-stroke-down-dialog" keys="j"/>
    <shortcut action="action.gui.open-bend-dialog" keys="b"/>
    <shortcut action="action.gui.open-trill-dialog" keys="r"/>
    <shortcut action="action.gui.open-tremolo-picking-dialog" keys="Shift r"/>
    <shortcut action="action.gui.open-tremolo-bar-dialog" keys="Shift b"/>
    <shortcut action="action.gui.open-harmonic-dialog" keys="f"/>
    <shortcut action="action.gui.open-grace-dialog" keys="`"/>
    <shortcut action="action.gui.open-text-dialog" keys="Shift t"/>
    <shortcut action="action.gui.open-repeat-close-dialog" keys=";"/>
    <shortcut action="action.gui.open-repeat-alternative-dialog" keys="Shift ;"/>
    <shortcut action="action.gui.open-measure-add-dialog" keys="Ctrl Ins"/>
    <shortcut action="action.gui.open-measure-clean-dialog" keys="Ctrl x"/>
    <shortcut action="action.gui.open-measure-copy-dialog" keys="Ctrl c"/>
    <shortcut action="action.gui.open-measure-paste-dialog" keys="Ctrl v"/>
    <shortcut action="action.gui.open-transport-mode-dialog" keys="F9"/>
    <shortcut action="action.gui.open-marker-editor-dialog" keys="Shift Ins"/>
    <shortcut action="action.gui.toggle-browser-dialog" keys="Control b"/>
    <shortcut action="action.gui.toggle-transport-dialog" keys="Control t"/>
    <shortcut action="action.gui.toggle-marker-list" keys="Shift Ctrl m"/>
    <shortcut action="action.gui.open-documentation-dialog" keys="F1"/>
    <shortcut action="action.file.close-others" keys=""/>
    <shortcut action="action.file.close-all" keys=""/>
    <shortcut action="action.edit.cut" keys=""/>
    <shortcut action="action.edit.copy" keys=""/>
    <shortcut action="action.edit.paste" keys=""/>
    <shortcut action="action.edit.set-natural-key" keys=""/>
    <shortcut action="action.selection.clear" keys=""/>
    <shortcut action="action.selection.extend-left" keys=""/>
    <shortcut action="action.selection.extend-right" keys=""/>
    <shortcut action="action.selection.extend-previous" keys=""/>
    <shortcut action="action.selection.extend-next" keys=""/>
    <shortcut action="action.selection.extend-first" keys=""/>
    <shortcut action="action.selection.extend-last" keys=""/>
    <shortcut action="action.selection.select-all" keys=""/>
    <shortcut action="action.track.clone" keys=""/>
    <shortcut action="action.note.duration.tied" keys=""/>
    <shortcut action="action.beat.general.move-left" keys=""/>
    <shortcut action="action.beat.general.move-right" keys=""/>
    <shortcut action="action.beat.general.remove-unused-voice" keys=""/>
    <shortcut action="action.beat.general.voice-down" keys=""/>
    <shortcut action="action.beat.general.voice-up" keys=""/>
    <shortcut action="action.beat.general.remove-text" keys=""/>
    <shortcut action="action.beat.general.remove-chord" keys=""/>
    <shortcut action="action.note.effect.change-popping" keys=""/>
    <shortcut action="action.note.effect.change-slapping" keys=""/>
    <shortcut action="action.note.duration.set-whole" keys=""/>
    <shortcut action="action.note.duration.set-half" keys=""/>
    <shortcut action="action.note.duration.set-quarter" keys=""/>
    <shortcut action="action.note.duration.set-eighth" keys=""/>
    <shortcut action="action.note.duration.set-sixteenth" keys=""/>
    <shortcut action="action.note.duration.set-thirty-second" keys=""/>
    <shortcut action="action.note.duration.set-sixty-fourth" keys=""/>
    <shortcut action="action.transport.playStop" keys=""/>
    <shortcut action="action.transport.stop" keys=""/>
    <shortcut action="action.view.layout-set-page" keys=""/>
    <shortcut action="action.view.layout-set-linear" keys=""/>
    <shortcut action="action.view.layout-set-multitrack" keys=""/>
    <shortcut action="action.view.layout-set-score-enabled" keys=""/>
    <shortcut action="action.view.layout-set-tablature-enabled" keys=""/>
    <shortcut action="action.view.layout-set-compact" keys=""/>
    <shortcut action="action.view.layout-set-chord-name-enabled" keys=""/>
    <shortcut action="action.view.layout-set-chord-diagram-enabled" keys=""/>
    <shortcut action="action.transport.highlight-played-beat" keys=""/>
    <shortcut action="action.gui.open-key-binding-editor" keys=""/>
    <shortcut action="action.gui.open-plugin-list-dialog" keys=""/>
    <shortcut action="action.gui.open-beat-move-dialog" keys=""/>
    <shortcut action="action.gui.open-chord-dialog" keys=""/>
    <shortcut action="action.gui.open-measure-remove-dialog" keys=""/>
    <shortcut action="action.gui.open-track-tuning-dialog" keys=""/>
    <shortcut action="action.gui.open-track-properties-dialog" keys=""/>
    <shortcut action="action.gui.open-scale-dialog" keys=""/>
    <shortcut action="action.gui.open-url-dialog" keys=""/>
    <shortcut action="action.gui.open-transpose-dialog" keys=""/>
    <shortcut action="action.gui.toggle-fretboard-editor" keys=""/>
    <shortcut action="action.gui.toggle-piano-editor" keys=""/>
    <shortcut action="action.gui.toggle-matrix-editor" keys=""/>
    <shortcut action="action.gui.toggle-lyric-editor" keys=""/>
    <shortcut action="action.gui.toggle-channels-dialog" keys=""/>
    <shortcut action="action.gui.toggle-main-toolbar" keys=""/>
    <shortcut action="action.gui.toggle-edit-toolbar" keys=""/>
    <shortcut action="action.gui.toggle-table-viewer" keys=""/>
    <shortcut action="action.gui.open-about-dialog" keys=""/>
    <shortcut action="action.gui.go-to-homepage" keys=""/>
    <shortcut action="tuner.tuner" keys=""/>
    <shortcut action="batch.converter" keys=""/>
</shortcuts>

```
