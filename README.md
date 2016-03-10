# slim2haml

A dirty hack to allow converting SLIM files into HAML

## Why?

I have no qualms with SLIM. In many ways, its syntax is superior to HAML.

What I *don't* like, though, is a project that's half-SLIM, half-ERB, half-HAML.
Like, one of the projects I'm currently working on.

This goes *some* of the way to fixing this.

## Installation

This is Ruby-based, so you should have a working Ruby > 1.9.x. with `bundler`
already installed.

```bash
bundle install
```

## Usage

You should `cd` into the directory where you want to convert the SLIM files.

Then simply run this binary:

```
</path/to/>/slim2haml
```

It will convert the SLIM files to ERB files first, then convert the ERB to HAML.

## Further development

I don't know if anyone else will find this useful but if you do and
would like it to be a bit easier to install and use, let me know and I'll
get onto it.

