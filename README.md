# Crocodile for GitLab (plugin)

<p><b>Crocodile for GitLab</b> is a powerful, free plugin designed to streamline how you manage GitLab CI/CD variables, pipelines, environments, and jobs directly from your JetBrains IDE. Fully compatible with GitLab Self-Managed, GitLab.com, and GitLab Dedicated.</p>

[![Version](https://img.shields.io/jetbrains/plugin/v/27303.svg)](https://plugins.jetbrains.com/plugin/27303-crocodile-for-gitlab/versions)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/27303.svg)](https://plugins.jetbrains.com/plugin/27303-crocodile-for-gitlab)

<h3>Key Features</h3>
<ul>
  <li><b>Comprehensive Variable Control:</b> Seamlessly create, edit, copy, or move CI/CD variables across environments.</li>
  <li><b>Smart Variable Tracking:</b> Instantly locate where specific variables are used throughout your project.</li>
  <li><b>Environment Management:</b> Effortlessly create, track, and delete deployment environments.</li>
  <li><b>Pipeline & Job Control:</b> Run, stop, or retry jobs, view live job logs, and check the associated Git log for branches or tags.</li>
  <li><b>Pipeline Notes:</b> Read and write persistent notes directly on your GitLab pipelines.</li>
  <li><b>Secure Collaboration:</b> Discuss pipeline tasks securely with other project participants right inside your IDE.</li>
  <li><b>Asynchronous Job Execution:</b> Trigger manual pipeline jobs and switch projects freely—the plugin notifies you the exact moment execution starts and finishes.</li>
  <li><b>Fail-Safe History:</b> Undo or redo any user actions related to variables and environments with a single click.</li>
</ul>

<h3>Advanced Variable Automation</h3>
<ul>
  <li><b>Secure Local Storage:</b> Save variables locally within your IDE's private configuration store.</li>
  <li><b>Cross-Project Portability:</b> Import existing variables directly into other GitLab projects.</li>
  <li><b>Flexible Imports & Triggers:</b> Populate environment configurations instantly from <code>.env</code> files, and create Git tags to trigger pipeline runs on demand.</li>
</ul>

<h3>Export Capabilities</h3>
<ul>
  <li><b>Run Configurations:</b> Export variables to <code>.env</code> files for fast local debugging.</li>
  <li><b>Documentation-Ready:</b> Export variables into structured Markdown tables to drop directly into your repository documentation.</li>
</ul>

<h3>Enterprise-Grade Security</h3>
<ul>
  <li><b>Zero Data Leakage:</b> Your access tokens, saved variables, and sensitive data are never transmitted to third parties.</li>
  <li><b>Direct API Communication:</b> The plugin communicates exclusively and securely with your configured GitLab API.</li>
  <li><b>Secure Local Credentials:</b> Sensitive fields are stored locally using the native JetBrains IDE credential store.</li>
  <li><b>On-Screen Obfuscation:</b> Sensitive data remains hidden on your screen until explicitly selected or placed into edit mode.</li>
</ul>

<br/>
<h3>An essential productivity booster for Developers, DevOps Engineers, and Platforms Teams everywhere!</h3>

<p>Releases: <a href="https://github.com/yansioux/Crocodile-for-GitLab-plugin/releases">https://github.com/yansioux/Crocodile-for-GitLab-plugin/releases</a></p>


## Installation

- **Via the In-IDE Marketplace (Recommended):**

  Navigate to <kbd>Settings</kbd> (or <kbd>Settings... ⌘,</kbd> on macOS) > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd>, search for **"Crocodile for GitLab"**, and click <kbd>Install</kbd>.

- **Via JetBrains Marketplace Website:**

  Visit the [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID) page and click the <kbd>Install to...</kbd> button while your IDE is active.

- **Via Manual Offline Installation:**

  If you need to install the plugin offline, download the latest release package from either the [JetBrains Marketplace Versions](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID/versions) page or the [GitHub Releases](https://github.com/yansioux/Crocodile-for-GitLab-plugin/releases) page.

  Then, import it inside your IDE via <kbd>Settings</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>

![Crocodile for GitLab logo](https://github.com/yansioux/Crocodile-for-GitLab-plugin/blob/main/Misc/Logo/200x200/pluginIcon.svg?raw=true)
