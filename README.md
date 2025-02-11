# spenking-music

## Running

To run dev build: 

```
bundle exec jekyll serve
```

## File Naming

This is run off of a blog framework, so the order of the posts comes from "dates" in their filenames. 
- 0000 years are "Crosses Split" album
- 1000 years are "Bad Blood, Good Blood" album
- 2000 years are uncollected songs I wrote (Category is `" "`)
- 2001 years are "Covers" I want to keep track of
- 2002 years are covers I don't really care about anymore, could be deleted
- 4000 years are miscellaneous files.

## Compressing video assets

```
ffmpeg -i assets/videos/2022-01-05-untitled-1.mov -vcodec h264 -acodec aac assets/videos2022-01-05-untitled-1.mp4
```

```
ffmpeg -i assets/videos/2023-07-14-golden-necklace.mp4 -vf scale=640:360 -preset slow -crf 18 assets/videos/2023-07-14-golden-necklace2.mp4
```
