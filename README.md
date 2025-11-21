<h1>Create Your First Expo App (Using npx create-expo-app@latest)</h1>

<p>A fully updated step-by-step guide for creating your first React Native app with Expo, following the latest Expo documentation (2025).</p>

<h2>Tags</h2>
<ul>
  <li>React Native</li>
  <li>Expo</li>
  <li>Mobile App</li>
  <li>Cross-Platform</li>
  <li>JavaScript</li>
  <li>Beginner</li>
  <li>Tutorial</li>
</ul>

<h2>Steps</h2>

<h3>1. Install Node.js</h3>
<ul>
  <li>Download and install Node.js from <a href="https://nodejs.org">https://nodejs.org</a></li>
  <li>Verify installation in terminal/cmd:
    <pre><code>node -v
npm -v</code></pre>
  </li>
</ul>

<h3>2. Create a New Expo Project</h3>
<ul>
  <li>Open terminal and run:
    <pre><code>npx create-expo-app MyFirstApp</code></pre>
  </li>
  <li>Select <strong>"blank"</strong> template when prompted</li>
  <li>Navigate into project folder:
    <pre><code>cd MyFirstApp</code></pre>
  </li>
</ul>

<h3>3. Start the Development Server</h3>
<ul>
  <li>Run:
    <pre><code>npx expo start</code></pre>
  </li>
  <li>Expo Dev Tools will open in browser</li>
  <li>Terminal will display a QR code</li>
</ul>

<h3>4. Run the App on a Device</h3>
<ul>
  <li>Install <strong>Expo Go</strong> on Android or iOS</li>
  <li>Scan QR code from terminal/Expo Dev Tools</li>
  <li>The app opens instantly on your device</li>
</ul>
<p><em>Tip:</em> Press <code>a</code> for Android emulator or <code>i</code> for iOS simulator if available</p>

<h3>5. Edit Your App</h3>
<ul>
  <li>Open <code>App.js</code> in VS Code or any editor</li>
  <li>Example code:
    <pre><code>import { Text, View } from 'react-native';

export default function App() {
  return (
    &lt;View style={{ flex:1, justifyContent:'center', alignItems:'center' }}&gt;
      &lt;Text&gt;Hello, First Expo App!&lt;/Text&gt;
    &lt;/View&gt;
  );
}</code></pre>
  </li>
  <li>Save → App reloads automatically (hot reload/live refresh)</li>
</ul>

<h3>6. Optional – Build or Publish</h3>
<ul>
  <li>Build APK / IPA:
    <pre><code>npx expo build:android
npx expo build:ios</code></pre>
  </li>
  <li>Publish instantly:
    <pre><code>npx expo publish</code></pre>
  </li>
</ul>

<h2>Result</h2>
<p>✅ Your first React Native app is running on a real device or simulator, ready for further development.</p>
