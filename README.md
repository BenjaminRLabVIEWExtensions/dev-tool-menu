<div id="top"></div>

[![GitHub all releases][release-shield]][release-url]
[![Wiki][wiki-shield]][wiki-url]
[![Issues][issues-shield]][issues-url]
[![Zero-Clause BSD][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

# BenjaminR LabVIEW Menus

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#installation">Installation Instructions</a>
    </li>
    <li>
      <a href="#file-menu">File Menu</a>
    </li>
    <li>
      <a href="#tools-menu">Tools Menu</a>
    </li>
    <li>
      <a href="#help-menu">Help Menu</a>
    </li>
    <li>
      <a href="#other-information">Other Information</a>
    </li>
  </ol>
</details>

BenjaminR LabVIEW Menu VIs into the LabVIEW Menus (File, Tools, and Help).

## Installation
- Download the Insert LVClass Property Node.vip.
- Use VIPM to install it on your LabVIEW version (2020+).
		
## File Menu
<p>Select File &gt;&gt; BenjaminR &gt;&gt; &lsquo;Tool&rsquo;. Tool menu items are described below.</p>
<details open>
	<summary>File Menu (Click to collapse)</summary>
	<p><img src="/src/help/BenjaminR/img/fileMenu.png" alt="" /></p>
</details>
<ul>
	<li style="padding-left: 10px;"><strong>New VI from Template</strong>&nbsp;&ndash; Creates a new VI from template.</li>
	<p><img src="/src/help/BenjaminR/img/_BenjaminR_VI_Template.png" alt="" /></p>
</ul>

## Tools Menu
<p>Select Tools &gt;&gt; BenjaminR &gt;&gt; &lsquo;Tool&rsquo;. Tool menu items are described below</p>
<details open>
	<summary>Tools Menu (Click to collapse)</summary>
	<p><img src="/src/help/BenjaminR/img/toolsMenu.png" alt="" /></p>
</details>
<ul>
	<li style="padding-left: 10px;"><strong>Create New VI from Template</strong>&nbsp;&ndash; Creates a new VI from template.</li>
	<p><img src="/src/help/BenjaminR/img/_BenjaminR_VI_Template.png" alt="" /></p>
	<li style="padding-left: 10px;"><strong>IDE Tools&nbsp;</strong>&ndash; Submenu containing tools interacting with the LabVIEW IDE.</li>
	<details open>
		<summary>IDE Tools Menu (Click to collapse)</summary>
		<p><img src="/src/help/BenjaminR/img/ideToolMenu.png" alt="" /></p>
	</details>
	<li style="padding-left: 10px;"><strong>IDE Tools: Quit and Restart LabVIEW</strong>&nbsp;&ndash; Quits then restart LabVIEW.</li>
	<p><img src="/src/help/BenjaminR/img/ideToolsRestart.png" alt="" /></p>
	<li style="padding-left: 10px;"><strong>IDE Tools: Refresh LabVIEW Menus</strong>&nbsp;&ndash; Refreshes the File, Tools, and Help menus.</li>
	<p><img src="/src/help/BenjaminR/img/ideToolsRefreshMenu.png" alt="" /></p>
	<li style="padding-left: 10px;"><strong>VI Tools&nbsp;</strong>&ndash; Submenu containing tools interacting with VIs.</li>
	<details open>
		<summary>VI Tools Menu (Click to collapse)</summary>
		<p><img src="/src/help/BenjaminR/img/viToolMenu.png" alt="" /></p>
	</details>
	<li style="padding-left: 10px;"><strong>VI Tools: Determine ConPane Pattern</strong>&nbsp;&ndash; Select a Connector Pane pattern in the ring and run the VI to find out the pattern number.</li>
	<p><img src="/src/help/BenjaminR/img/viToolsConPane.png" alt="" /></p>
	<li style="padding-left: 10px;"><strong>VI Tools: Save Global</strong>&nbsp;&ndash;Changes the defaults of all controls on the front panel to be the current values and saves the VI.</li>
	<p><img src="/src/help/BenjaminR/img/viToolsSaveGlobal.png" alt="" /></p>
	<li style="padding-left: 10px;"><strong>VI Tools: System Error Cluster Replacement</strong>&nbsp;&ndash; Replaces the current error clusters on the front panel with System error cluster.</li>
	<p><img src="/src/help/BenjaminR/img/viToolsReplaceError.png" alt="" /></p>
</ul>

## Help Menu
<h3 id="help-menu">Help Menu</h3>
<p>Select Help &gt;&gt; BenjaminR &gt;&gt; &lsquo;Tool. Tool menu items are described below.</p>
<details open>
	<summary>Help Menu (Click to collapse)</summary>
	<p><img src="/src/help/BenjaminR/img/helpMenu.png" alt="" /></p>
</details>
<ul>
	<li style="padding-left: 10px;"><strong>About&nbsp;</strong>&ndash; Opens the BenjaminR About dialog.</li>
	<p><img src="/src/help/BenjaminR/img/about.png" alt="" /></p>
	<li style="padding-left: 10px;"><strong>LabVIEW Menus (Help)&nbsp;</strong>&ndash; Opens the BenjaminR LabVIEW Menus help in the default browser.</li>
</ul>
<hr />

<h3 id="other-information">Other Information</h3>
<h4>Package File Installation Locations</h4>
<p>Code installation locations are relative to the LabVIEW directory. Files are stored in the following locations:</p>
<ul>
	<li style="padding-left: 10px;"><strong>File menu code&nbsp;</strong>&ndash; \wizard\BenjaminR</li>
	<li style="padding-left: 10px;"><strong>Tools menu code&nbsp;</strong>&ndash; \project\BenjaminR</li>
	<li style="padding-left: 10px;"><strong>Help menu code&nbsp;</strong>&ndash; \help\BenjaminR</li>
</ul>
		
## Other Information
#### Package File Installation Locations
<p>Code installation locations are relative to the LabVIEW directory. Files are stored in the following locations:</p>
<ul>
  <li style="padding-left: 10px;"><strong>File menu code&nbsp;</strong>&ndash; \wizard\BenjaminR</li>
  <li style="padding-left: 10px;"><strong>Tools menu code&nbsp;</strong>&ndash; \project\BenjaminR</li>
  <li style="padding-left: 10px;"><strong>Help menu code&nbsp;</strong>&ndash; \help\BenjaminR</li>
</ul>

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[release-shield]: https://img.shields.io/github/v/release/BenjaminRLabVIEWExtensions/dev-tool-menu?color=orange&logo=labview&style=for-the-badge
[release-url]: https://github.com/BenjaminRLabVIEWExtensions/dev-tool-menu/releases/tag/1.2.0
[wiki-shield]: https://img.shields.io/github/discussions/BenjaminRLabVIEWExtensions/dev-tool-menu?style=for-the-badge
[wiki-url]: https://github.com/BenjaminRLabVIEWExtensions/dev-tool-menu/wiki
[issues-shield]: https://img.shields.io/github/issues/BenjaminRLabVIEWExtensions/dev-tool-menu?style=for-the-badge
[issues-url]: https://github.com/BenjaminRLabVIEWExtensions/dev-tool-menu/issues
[license-shield]: https://img.shields.io/badge/LICENSE-Zero--Clause%20BSD-green?style=for-the-badge
[license-url]: https://github.com/BenjaminRLabVIEWExtensions/dev-tool-menu/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/benjaminrouffet/
