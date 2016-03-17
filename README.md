# Music 

[![Build Status](https://travis-ci.org/go-music/music.svg?branch=master)](https://travis-ci.org/go-music/music) [![GoDoc](https://godoc.org/gopkg.in/music.v0?status.svg)](https://godoc.org/gopkg.in/music.v0) [![Go Report Card](https://goreportcard.com/badge/gopkg.in/music.v0)](https://goreportcard.com/report/gopkg.in/music.v0)

https://gopkg.in/music.v0

#### Opinionated models of certain atomic musical concepts

There's an example command-line utility `music.go` to demo the libraries:

    go run music.go -k "C minor 7"
    
This will output:
    
    root: C
    major: false
    minor: true
    tones:
      3: D#
      5: G
      7: A#

Author: [Charney Kaye](http://w.charney.io)

## Note

A Note is used to represent the relative duration and pitch of a sound.

[![GoDoc](https://godoc.org/gopkg.in/music.v0/note?status.svg)](https://godoc.org/gopkg.in/music.v0/note) [![Coverage](https://img.shields.io/badge/coverage-100%-brightgreen.svg?style=flat)](https://gocover.io/gopkg.in/music.v0/note)

## Interval

An interval is the difference between two pitches.

[![GoDoc](https://godoc.org/gopkg.in/music.v0/interval?status.svg)](https://godoc.org/gopkg.in/music.v0/interval) [![Coverage](https://img.shields.io/badge/coverage-100%-brightgreen.svg?style=flat)](https://gocover.io/gopkg.in/music.v0/interval)

## Key

The key of a piece is a group of pitches, or scale upon which a music composition is created in classical, Western art, and Western pop music.

[![GoDoc](https://godoc.org/gopkg.in/music.v0/key?status.svg)](https://godoc.org/gopkg.in/music.v0/key) [![Coverage](https://img.shields.io/badge/coverage-100%-brightgreen.svg?style=flat)](https://gocover.io/gopkg.in/music.v0/key)

## Chord

A chord, in music, is any harmonic set of three or more notes that is heard as if sounding simultaneously.

[![GoDoc](https://godoc.org/gopkg.in/music.v0/chord?status.svg)](https://godoc.org/gopkg.in/music.v0/chord) [![Coverage](https://img.shields.io/badge/coverage-100%-brightgreen.svg?style=flat)](https://gocover.io/gopkg.in/music.v0/chord)
