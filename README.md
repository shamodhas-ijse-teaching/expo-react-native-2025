<project>
  <title>Create Your First Expo App (Using npx create-expo-app@latest)</title>
  <description>A fully updated step-by-step guide for creating your first React Native app with Expo, following the latest Expo documentation (2025).</description>

  <tags>
    <tag>React Native</tag>
    <tag>Expo</tag>
    <tag>Mobile App</tag>
    <tag>Cross-Platform</tag>
    <tag>JavaScript</tag>
    <tag>Beginner</tag>
    <tag>Tutorial</tag>
  </tags>

  <step id="1">
    <title>Install Node.js</title>
    <instructions>
      <item>Download and install Node.js from <link>https://nodejs.org</link></item>
      <item>Verify installation in terminal/cmd:
        <code>
node -v
npm -v
        </code>
      </item>
    </instructions>
  </step>

  <step id="2">
    <title>Create a New Expo Project</title>
    <instructions>
      <item>Open terminal and run:
        <code>npx create-expo-app MyFirstApp</code>
      </item>
      <item>Select <strong>"blank"</strong> template when prompted</item>
      <item>Navigate into project folder:
        <code>cd MyFirstApp</code>
      </item>
    </instructions>
  </step>

  <step id="3">
    <title>Start the Development Server</title>
    <instructions>
      <item>Run:
        <code>npx expo start</code>
      </item>
      <item>Expo Dev Tools will open in browser</item>
      <item>Terminal will display a QR code</item>
    </instructions>
  </step>

  <step id="4">
    <title>Run the App on a Device</title>
    <instructions>
      <item>Install <strong>Expo Go</strong> on Android or iOS</item>
      <item>Scan QR code from terminal/Expo Dev Tools</item>
      <item>The app opens instantly on your device</item>
      <tip>Press <code>a</code> for Android emulator or <code>i</code> for iOS simulator if available</tip>
    </instructions>
  </step>

  <step id="5">
    <title>Edit Your App</title>
    <instructions>
      <item>Open <code>App.js</code> in VS Code or any editor</item>
      <item>Example code:
<code>
import { Text, View } from 'react-native';

export default function App() {
  return (
    &lt;View style={{ flex:1, justifyContent:'center', alignItems:'center' }}&gt;
      &lt;Text&gt;Hello, First Expo App!&lt;/Text&gt;
    &lt;/View&gt;
  );
}
</code>
      </item>
      <item>Save → App reloads automatically (hot reload/live refresh)</item>
    </instructions>
  </step>

  <step id="6">
    <title>Optional – Build or Publish</title>
    <instructions>
      <item>Build APK / IPA:
<code>
npx expo build:android
npx expo build:ios
</code>
      </item>
      <item>Publish instantly:
<code>
npx expo publish
</code>
      </item>
    </instructions>
  </step>

  <result>
    ✅ Your first React Native app is running on a real device or simulator, ready for further development.
  </result>

</project>
