# Iver Martinson, C Programmer

<a href="https://mynameisthe.com">mynameisthe.com</a>

## What I'm Working On

`Janurary 9th, 2026`
<br>
Right now I'm working towards a game engine. I want my projects to be completly my own, so I'm making all the libraries that I'd need for the engine. So far I've made a 3D renderer, an image parser, and a font parser. Those, too, also use only libraries I make (besides std libs and SDL for the renderer's window. Making a window seems pretty difficult). I've got plans for a physics engine, audio library, GUI library, and more. Some stuff I've started on, like the physics engine and audio library. I hope to get this finished by the time I'm 18 so that I can boast that I did all this when I was still a kid lol

## File Parsing Philosophy

Excerpt from PitMap status: *"Not 100% of the BMP format's capabilities are supported just yet, it's really only the popular/common ones. I'll add more support as I or others run into files that PitMap can't parse."*

## Project Statuses

(in order of functionality)

### Every Project

All projects are writen on Debian Linux and may not be compilable on other OSes. I don't really care to add support until they are at a state where it makes sense to care, or unless someone wants to use them on another platform.

### RasterIver

RasterIver is a competent GPU rasterizer that can render high poly objects at a fair FPS. It uses OBJ files. Texture file support is limited to whatever PitMap can read. It has animated textures too.

### YuzuParse

YuzuParse is an audio file parser and player that right now only supports WAV files. It decodes the PCM audio information and then uses PortAudio to play it back.

### PitMap

PitMap is an image parser that currently only supports BMP and GIF formats. Not 100% of the BMP format's capabilities are supported just yet, it's really only the popular/common ones. I'll add more support as I or others run into files that PitMap can't parse.

### SourParse

SourParse is a TTF/OTF font file parser. I think it technically supports OpenType format because OpenType is backwards compatible with TrueType? Idk. Anyways, it works pretty well but is definitly missing most features that the specs can deliver. 

### Fizzix

2D and 3D physics resolver that currently can't resolve physics. Oh well.

### LemonGUIce

GUI library that can only make a single rounded rectangle.

### Pomelo

A game engine that is currently just a file tree and an empty `int main()`.

## Pinned Repos

Half of this stuff is in a usable state but the other half are just pinned because I want to show off what I'm working on.
