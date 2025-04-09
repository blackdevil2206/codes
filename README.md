This Python script checks whether a live stream is online, retrieves the video resolution and framerate using FFprobe, and then records the stream using FFmpeg. It includes video filtering, text overlay, and async audio resampling. If video details can't be fetched, it uses default recording settings. It also handles corrupt frames and includes a retry mechanism for offline streams.

