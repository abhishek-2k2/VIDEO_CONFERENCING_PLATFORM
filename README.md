<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>

<h1>Video Conferencing Application</h1>
<p>This project is a real-time video conferencing application that allows users to engage in video meetings with integrated chat functionality. Built using the GetStream platform, it provides seamless video and audio communication with additional features like chat, multi-user conferencing, and screen sharing.</p>

<h2>Features</h2>
<ul>
    <li><strong>Real-Time Video & Audio Communication:</strong> Seamless video and audio streaming between participants using GetStream for real-time communication.</li>
    <li><strong>Chat Functionality:</strong> Integrated chat feature using the GetStream API to enable text messaging between participants during the conference.</li>
    <li><strong>Screen Sharing:</strong> Participants can share their screen for presentations and collaboration during a call.</li>
    <li><strong>Multi-User Conference:</strong> Supports multiple participants in a single video call, ideal for team meetings or group discussions.</li>
    <li><strong>Responsive Design:</strong> The application is fully responsive, ensuring a smooth user experience on both desktop and mobile devices.</li>
</ul>

<h2>Project Components</h2>

<h3>GetStream for Communication</h3>
<p>The application leverages the <strong>GetStream</strong> API for real-time communication, including video streaming and chat functionality. GetStream’s scalable infrastructure ensures low-latency connections, making the video calls smooth and responsive.</p>



<h3>Chat Feature</h3>
<p>The chat feature is implemented using GetStream’s messaging API, allowing participants to send real-time messages during the video conference. This enhances collaboration and ensures seamless communication between users.</p>

<h3>Screen Sharing</h3>
<p>The application supports screen sharing through WebRTC’s <code>getDisplayMedia()</code> API, enabling participants to share their screen for presentations or other collaborative tasks.</p>

<h3>Multi-User Support</h3>
<p>The app allows multiple users to join a single conference room, making it ideal for team meetings, group collaborations, or virtual events. The interface dynamically adjusts to manage multiple video streams effectively.</p>

<h3>Responsive Design</h3>
<ul>
    <li>The user interface is designed to be responsive, offering a seamless experience across devices, including desktop, tablet, and mobile.</li>
    <li>All controls, such as muting audio, toggling video, and starting/stopping screen sharing, are easily accessible from the interface.</li>
</ul>

<h2>Error Handling</h2>
<ul>
    <li><strong>Connection Issues:</strong> The application detects network connectivity problems and automatically tries to reconnect users in case of disconnection.</li>
    <li><strong>Media Access Errors:</strong> If a user denies access to their camera or microphone, the app provides clear instructions on enabling access.</li>
    <li><strong>Screen Sharing Errors:</strong> Any issues during screen sharing are handled gracefully, with user-friendly messages guiding participants to resolve them.</li>
</ul>

<h2>Live Demo</h2>
<p>You can try out the live demo of the project here:</p>
<p><a href="https://video-conferencing-pied.vercel.app/" target="_blank">Live Demo</a></p>

<h2>Conclusion</h2>
<p>This Video Conferencing Application offers a complete solution for virtual meetings, combining real-time video and audio with text chat and screen sharing. Built using GetStream and WebRTC, it ensures a reliable and high-quality communication experience for users across devices.</p>

</body>
</html>
