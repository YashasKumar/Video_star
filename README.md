Video Streamer Application
This web application allows users to interact with video playback, add timestamps, create revisions, adjust audio and visual settings, and save data locally using localStorage.

Features
Video Playback: Play videos from local sources by specifying the video path.
Timestamps: Add named timestamps during video playback.
Revisions: Create segments (revisions) of videos with start and end markers.
Visual Adjustments: Adjust brightness, contrast, and saturation of the video.
Local Storage: Save timestamps and revisions locally for persistence across sessions.
Getting Started
To run the application locally:

Clone this repository:

bash
git clone https://github.com/your-username/video-streamer.git
cd video-streamer
Add your own video file to the project directory.

Open index.html in your web browser.

Use the controls to interact with the video:

Add Timestamp: Click to add a timestamp with a name.
Start Flag / End Flag: Mark the start and end of a revision segment.
End Revision: End the current revision segment.
Adjust Visuals: Modify brightness, contrast, and saturation of the video.
Reload the page to see previously saved timestamps and revisions.

Customizing Video Path
To use your own video file, replace "class2.mp4" in the <source> tag of the <video> element in index.html with your video file name and path.

html
<source src="your-video-file.mp4" type="video/mp4">
Technologies Used
HTML5 Video API
JavaScript (ES6)
CSS3 for styling
License
This project is licensed under the MIT License - see the LICENSE file for details.
