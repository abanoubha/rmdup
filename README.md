# rmdup

remove duplicate files ; find duplicate files and choose to remove them.

## Commands

```sh
# build
go mod tidy && go build -o rmdup .

# run
./rmdup
```

## Resources & References

- [dupeguru](https://github.com/arsenetar/dupeguru) written in python 3 + C
- [fslint](https://github.com/pixelb/fslint) written in python 3 + shell
- Video Duplicate near Finder, written in Rust, on [GitHub](https://github.com/Farmadupe/vid_dup_finder_lib)
- CLI tool to find duplicate files, written in Go, on [GitHub](https://github.com/m-manu/go-find-duplicates)
- [dskDitto](https://github.com/jdefrancesco/dskDitto) : Super fast duplicate file finder written in Golang.

## Tasks

- [ ] indexing: storing a hashmap of files
- [ ] search for duplicates
- [ ] remove the duplicate file, if the user chose so

