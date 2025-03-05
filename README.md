# DXWAP
DXWAP is a technology that helps you get the highest frame in high quality. The textures are loaded faster without reducing the quality and frame, and it makes for a better experience. At the heart of this technology is a powerful core that translates DirectX commands for Vulkan.  There are other technologies in DXWAP that you can see below.

# Contents
- DLSS
- DX Engine
- DXWAP SubSystem SDK
- Virtual Win32
- DXVK

# Install
Install Termux GitHub and install the following prerequisites:
<pre class="wp-block-code">
  <code>pkg install python </code>
</pre>
<p></p>
<pre class="wp-block-code">
  <code>pkg install git </code>
</pre>
<b>Universal Driver:</b>
If you want Adreno and Mali drivers and several small prerequisites to be installed, enter the following command:
<pre class="wp-block-code">
  <code>git clone https://github.com/zevenoxxx/DXWAP </code>
</pre>
<p></p>
<b>Adreno Driver:</b>
<pre class="wp-block-code">
  <code>git clone https://github.com/zevenoxxx/DXWAP/Adreno </code>
</pre>
<p></p>
<b>Mali Driver:</b>
<pre class="wp-block-code">
  <code>git clone https://github.com/zevenoxxx/DXWAP/Mali </code>
</pre>
Finally, restart your device to apply the changes.
<p></p>
<b>Currently, there is no official driver for PowerVR, but it can be developed.</b>

# Official driver development
Official driver development is a time-consuming and professional task. In the development phase, you need to know what driver you are writing, compile and debug it, and finally publish it officially.  You need to fully understand how to communicate with the hardware and operating system and find the signature associated with the BIOS. You must clone the <b>DXWAP SubSystem SDK</b> via Termux to access the development tools.
<pre class="wp-block-code">
  <code>git clone https://github.com/zevenoxxx/DXWAP/SDK </code>
