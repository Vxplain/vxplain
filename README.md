<div align="center">

<h1 > Vxplain - Autogenerate Architecture Diagrams</h1>

<div align="center">
<img src="https://cdn.jsdelivr.net/gh/vxplain/media@main/extension/hero-rounded-shadow.png" alt="Vxplain Demo" width="1000">
</div>

<!-- [![VS Code Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/Vxplain.vxplain?color=blue&label=VS%20Marketplace)](https://marketplace.visualstudio.com/items?itemName=Vxplain.vxplain) -->
<!-- [![Downloads](https://img.shields.io/visual-studio-marketplace/d/Vxplain.vxplain?color=green)](https://marketplace.visualstudio.com/items?itemName=Vxplain.vxplain) -->
<!-- 
[![Rating](https://img.shields.io/visual-studio-marketplace/r/Vxplain.vxplain)](https://marketplace.visualstudio.com/items?itemName=Vxplain.vxplain) -->
[![GitHub Issues](https://img.shields.io/github/issues/Vxplain/vxplain?color=yellow&logo=github)](https://github.com/Vxplain/vxplain/issues)
[![Discord](https://img.shields.io/discord/1302012328182681630?label=Discord&logo=discord&logoColor=white)](https://discord.gg/FKxaBdyBJY)
[![Docs](https://img.shields.io/badge/Docs-docs.vxplain.com-purple)](https://docs.vxplain.com)
[![Website](https://img.shields.io/badge/Website-vxplain.com-purple)](https://www.vxplain.com)
<!-- [![Twitter](https://img.shields.io/badge/Twitter-Follow-1DA1F2?logo=x)](https://x.com/Vxplain_ai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?logo=linkedin)](https://www.linkedin.com/company/vxplain) -->

</div>

Vxplain is a visualization tool for coding agents, it provides you ability to generate architecture diagrams, call graphs, flowcharts etc, so your team can understand any codebase in minutes. This powerful VS Code extension reduces onboarding time from weeks to minutes by automatically generating visual representations of your code architecture and logic flows.

# 🚀 Key Features

<table>
<tr>
<td width="50%">

### 🏗️ Architecture Diagrams

Create comprehensive high-level design diagrams that map out your entire system architecture. Generate diagrams for your entire project or specific folders to understand complex systems at a glance.

</td>
<td width="50%">

<img src="https://cdn.jsdelivr.net/gh/vxplain/media@main/website/features/feat-arch.png" alt="Architecture Diagrams" width="100%">

</td>
</tr>
</table>

<table>
<tr>
<td width="50%">

<img src="https://cdn.jsdelivr.net/gh/vxplain/media@main/website/features/feat-graph.png" alt="Interactive Call Graphs" width="100%">

</td>
<td width="50%">

### 🔗 Interactive Call Graphs

Navigate complex codebases with interactive call graphs that show how functions, methods, and classes interact. Trace execution paths, identify dependencies, and understand data flow with intuitive visual representations.

</td>
</tr>
</table>



<table>
<tr>
<td width="50%">

### 📊 Code-to-Diagram Generation

Transform complex code snippets into clear flowcharts and diagrams. Perfect for understanding business logic, control flow, and algorithm implementation with instant visualizations.

</td>
<td width="50%">

<img src="https://cdn.jsdelivr.net/gh/vxplain/media@main/website/features/feat-flow.png" alt="Code-to-Diagram Generation" width="100%">

</td>

</tr>
</table>

<table>
<tr>
<td width="50%">

<img src="https://cdn.jsdelivr.net/gh/vxplain/media@main/website/features/feat-provider.png" alt="Bring Your Own LLMs or Run Locally" width="100%">

</td>
<td width="50%">

### 🤖 Bring Your Own LLMs or Run Locally

Integrate with your preferred LLM providers including OpenAI, Anthropic, local models, and custom endpoints. Maintain control over your data while leveraging the power of AI for code analysis.

</td>
</tr>
</table>

<table>
<tr>
<td width="50%">

### 📝 Multi-level Summaries

Get comprehensive summaries at multiple levels - from high-level architecture overviews to detailed function explanations. AI-generated human-readable documentation automatically.

</td>
<td width="50%">

<img src="https://cdn.jsdelivr.net/gh/vxplain/media@main/website/features/feat-summary.png" alt="Multi-level Summaries" width="100%">

</td>
</tr>
</table>

<table>
<tr>
<td width="50%">

<img src="https://cdn.jsdelivr.net/gh/vxplain/media@main/website/features/feat-dir.png" alt="Directory Tree Visualization" width="100%">

</td>
<td width="50%">

### 📁 Directory Tree Visualization

Get a bird's-eye view of your project structure with intelligent directory tree visualization. Quickly navigate large codebases, understand project organization, and open files directly from the tree.

</td>

</tr>
</table>



## And more coming soon...

1. **Chat Support**: Request Sophisticated visual representations of specific components from your code.
2. **Dependency Analysis**: Comprehensive visualization of module interdependencies.

# 🛠️ Use Cases

1. **Legacy Code Modernization**: Quickly understand older codebases before implementing changes.
2. **Accelerated Onboarding**: Help new team members understand complex systems in hours instead of weeks.
3. **Technical Knowledge Transfer**: Streamline explanations during team transitions with visual references.
4. **Architecture Documentation**: Generate visual artifacts that capture system design clearly and comprehensively.
5. **Code Reviews & Planning**: Enhance technical discussions with clear representations of code structure.

# 💻 Commands

1. **`Vxplain: Generate Diagram`**
2. **`Vxplain: View Call Graph`**
3. **`Vxplain: Open Extension`** | `Ctrl+Alt+v` (Windows/Linux) or `Cmd+Alt+v` (Mac)
4. **`Vxplain: Open Settings`** | `Ctrl+Alt+s` (Windows/Linux) or `Cmd+Alt+s` (Mac)
5. **`Vxplain: Check for Updates`**
6. **`Vxplain: Select LLM Provider`**

You can access these commands via the command palette (`Ctrl+Shift+P` or `Cmd+Shift+P`).

# ⚙️ Configuration And Settings

You can modify these settings by pressing `⌘ + ⌥ + s` or `Ctrl + Alt + s`.

1. **`Enable AI Features`**: Toggle AI features, so that you can use the extension without AI features. This will disable architecture diagrams, summaries, code-to-diagram generation. Default: `true`
2. **`Enable Analytics`**: Toggle analytics and crash data collection to help improve Vxplain. Default: `true`
3. **`Enable Auto Start`**: Toggle if the extension starts automatically when you open VS Code. Default: `true`

# 🔒 Privacy Notice

### API Providers

#### OpenAI

- OpenAI has a 30-day retention policy.
- OpenAI doesn't use this data in training.
- We're working with OpenAI to implement a zero-day retention policy.

#### Anthropic

- Anthropic has a 0-day retention policy.
- Anthropic doesn't use this data in training.

#### Vxplain

- **Your code is never stored on our servers.**
- No code or file contents are ever included in the telemetry data.
- All diagrams and analysis are stored in your local storage only.

> You can disable AI features or analytics in the settings.

If you have any questions about our [Privacy Policy](https://www.vxplain.com/privacy) practices, please don't hesitate to reach out to us at [raman@vxplain.com](mailto:raman@vxplain.com).

# ❓ FAQ

## Can I disable AI features?

Yes, you can disable AI features. However, this will disable architecture diagrams, summaries, code-to-diagram generation. Only function call graph and directory tree visualization will work. If that's what you need, you can update `Vxplain: Enable Ai Features` to `false` in the settings.

> If disabled, you won't need any active internet connection to use the extension. Everything happens locally.

## What configuration options are available?

Right now, configuration options are limited. We are working on it.
We will bring support to exclude the files and folders from analysis, control depth of analysis, and more.

## What usage data is collected? Can I disable it?

Yes, you can disable analytics. If you disable analytics, we will not collect any data at all. Which means, even the crash reports will not be collected and you will have to manually send them to us.

We collect usage data which is needed to improve vxplain experience, such as clicks, error logs, performance metrics, session replays and similar metrics. We never collect any source code, file contents, or any other sensitive data.

## Will this be open source?

We are still in early stages of development and eventurally, either all or some parts of the code will be open source.

# 🤝 Community

- **[Discord](https://discord.gg/FKxaBdyBJY)**: Connect with our community of professional developers.
- **Enterprise**: Contact raman@vxplain.com
- **[Docs](https://docs.vxplain.com)**: Learn more about Vxplain
- **[Issue Tracking](https://github.com/vxplain/vxplain/issues)**: Submit feature requests and contribute to our roadmap
- **[Twitter](https://x.com/Vxplain_ai)**
- **[LinkedIn](https://www.linkedin.com/company/vxplain)**
- **[Github](https://github.com/vxplain)**

<div align="center">

**Transform how you understand code with Vxplain**  
Visit [vxplain.com](https://www.vxplain.com) to learn more

<img src="https://cdn.jsdelivr.net/gh/vxplain/media@main/extension/logo-120x120.png" alt="Vxplain Logo" width="60">

</div>
