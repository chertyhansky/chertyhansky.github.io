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

~/.tuxguitar-1.5.6/config/shortcuts.xml

```

<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<shortcuts>
    <shortcut action="action.song.new" keys="Control n"/>
    <shortcut action="action.file.save-as" keys="F12"/>
    <shortcut action="action.file.save" keys="Control s"/>
    <shortcut action="action.file.open" keys="Control o"/>
    <shortcut action="action.file.print" keys="Control p"/>
    <shortcut action="action.edit.undo" keys="Control z"/>
    <shortcut action="action.edit.redo" keys="Control y"/>
    <shortcut action="action.edit.set-mouse-mode-selection" keys="Shift v"/>
    <shortcut action="action.edit.set-mouse-mode-edition" keys="Shift e"/>
    <shortcut action="action.edit.voice-1" keys="q"/>
    <shortcut action="action.edit.voice-2" keys="e"/>
    <shortcut action="action.caret.go-right" keys="d"/>
    <shortcut action="action.caret.go-left" keys="a"/>
    <shortcut action="action.caret.go-up" keys="w"/>
    <shortcut action="action.caret.go-down" keys="s"/>
    <shortcut action="action.track.add-new" keys="Control Shift Ins"/>
    <shortcut action="action.track.go-first" keys="Control Up"/>
    <shortcut action="action.track.go-last" keys="Control Down"/>
    <shortcut action="action.track.go-next" keys="Down"/>
    <shortcut action="action.track.go-previous" keys="Up"/>
    <shortcut action="action.track.move-down" keys="Shift Control Down"/>
    <shortcut action="action.track.move-up" keys="Shift Control Up"/>
    <shortcut action="action.track.remove" keys="Control Shift Del"/>
    <shortcut action="action.measure.go-first" keys="Home"/>
    <shortcut action="action.measure.go-last" keys="End"/>
    <shortcut action="action.measure.go-next" keys="Right"/>
    <shortcut action="action.measure.go-previous" keys="Left"/>
    <shortcut action="action.note.general.tied" keys="="/>
    <shortcut action="action.note.general.clean-beat" keys="Control Del"/>
    <shortcut action="action.note.general.decrement-semitone" keys="Shift Left"/>
    <shortcut action="action.beat.general.delete-note-or-rest" keys="Del"/>
    <shortcut action="action.note.general.increment-semitone" keys="Shift Right"/>
    <shortcut action="action.beat.general.insert-rest" keys="Ins"/>
    <shortcut action="action.beat.general.voice-auto" keys="Control a"/>
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
    <shortcut action="action.note.duration.increment-duration" keys="+"/>
    <shortcut action="action.note.duration.decrement-duration" keys="-"/>
    <shortcut action="action.transport.play" keys="Space"/>
    <shortcut action="action.transport.metronome" keys="Shift m"/>
    <shortcut action="action.transport.count-down" keys="Shift c"/>
    <shortcut action="action.transport.set-loop-start" keys="Alt Control s"/>
    <shortcut action="action.transport.set-loop-end" keys="Alt Control e"/>
    <shortcut action="action.marker.go-previous" keys="Alt Left"/>
    <shortcut action="action.marker.go-next" keys="Alt Right"/>
    <shortcut action="action.gui.open-song-info-dialog" keys="F5"/>
    <shortcut action="action.gui.open-tempo-dialog" keys="Alt Control m"/>
    <shortcut action="action.gui.open-clef-dialog" keys="Alt Control c"/>
    <shortcut action="action.gui.open-key-signature-dialog" keys="Alt Control k"/>
    <shortcut action="action.gui.open-time-signature-dialog" keys="Alt Control t"/>
    <shortcut action="action.gui.open-triplet-feel-dialog" keys="Control 3"/>
    <shortcut action="action.gui.open-stroke-up-dialog" keys="k"/>
    <shortcut action="action.gui.open-stroke-down-dialog" keys="j"/>
    <shortcut action="action.gui.open-bend-dialog" keys="b"/>
    <shortcut action="action.gui.open-trill-dialog" keys="r"/>
    <shortcut action="action.gui.open-tremolo-picking-dialog" keys="Shift r"/>
    <shortcut action="action.gui.open-tremolo-bar-dialog" keys="Shift b"/>
    <shortcut action="action.gui.open-harmonic-dialog" keys="f"/>
    <shortcut action="action.gui.open-grace-dialog" keys="`"/>
    <shortcut action="action.gui.open-repeat-close-dialog" keys=";"/>
    <shortcut action="action.gui.open-repeat-alternative-dialog" keys="Shift ;"/>
    <shortcut action="action.gui.open-measure-add-dialog" keys="Control Ins"/>
    <shortcut action="action.gui.open-measure-clean-dialog" keys="Control x"/>
    <shortcut action="action.gui.open-measure-copy-dialog" keys="Control c"/>
    <shortcut action="action.gui.open-measure-paste-dialog" keys="Control v"/>
    <shortcut action="action.gui.open-transport-mode-dialog" keys="F9"/>
    <shortcut action="action.gui.open-marker-editor-dialog" keys="Shift Ins"/>
    <shortcut action="action.gui.toggle-browser-dialog" keys="Control b"/>
    <shortcut action="action.gui.toggle-transport-dialog" keys="Control t"/>
    <shortcut action="action.gui.open-documentation-dialog" keys="F1"/>
</shortcuts>

```
