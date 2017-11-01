# Cookie Cat Markdown Editor

An editor to write markdown documents

This spec is in-progress and not at all complete.

## Core Features

- Markdown (Github flavor, with syntax highlighting?)
- Saves documents in plain text on the filesystem (NOT a database) so that they can be edited in other markdown editors
    - Tags and metadata must be saved within the file
    - These tags/metadata must be user-readable- there's no point saving them this way otherwise
- Pretty interface
- Version control (git, maybe, or a similar tool)

## Bonus features that would be cool some day

- cloud syncing


## Intended Audience

- People who want to write prose and
  - care about version control
  - want to edit using multiple editors (perhaps on phone, tablet, computer, someone else's computer, etc)
  - want to organize files in their own way

**Example**: Tess is both a programmer and a writer. She would like to be able to edit fiction the way she edits code. She has multiple devices including a computer and a phone, and has prefers different apps on each. It's important to her that any app she uses produces files she can open on her other devices. It's also important to her that she be able to keep her files where she would like them, in folder structures that make sense to her.
