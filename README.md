<h1 dir="auto">
<strong>LIP TO SPEECH SYNTHESIS</strong>
</h1>
<p dir="auto"> "Project done by Team Espada as a part of Varcons Techcnologies Internship. Team members - Nikhil Kumar Singh, Prateeksha K Ankolekar, Shreya Shenoy K, Vaishnavi Bhatt." </p>
<h2 dir="auto">
Prerequisites</h2>
<ul dir="auto">
<li>
<code>Python 3.6</code></li>
<li>"ffmpeg: "<code>sudo ap-get install ffmpeg</code></li>
<li> Install necessary packages using <code> pip install -r requirements,txt</code></li>
<li> Face Detection should be downloaded to <code>face_detection/detection/sfd/s3fd.pth</code></li>
<h2 dir="auto">You can lip-sync any video to any audio:</h2>
<code>python inference.py --checkpoint_path <ckpt> --face <video.mp4> --audio <an-audio-source> </code>
<p dir="auto"> The result is savedd(by default) in <code>results/result_voice.mp4</code>.You can specify it as an argument, similar to several other available options. The audio source can be any file supported by <code>FFMPEG</code> containing audio data: <code>*.wav</code>,  <code>*.mp3</code> or even a video file, from which the code will automatically extract the audio.</p>
<h2 dir="auto"> Evaluation</h2>
<p dir="auto"> Please check the <code>evaluation/</code> folder for the instructions.</p>
