## Convert .3gp to .mp4
`ffmpeg -y -i in.3gp out.mp4`

## Cut video to include 00:00:03 - 00:00:11
`ffmpeg -i in.mp4 -ss 00:00:03 -t 00:00:08 -async 1 out.mp4`
