   <div align="center">

<img src="src-tauri/icons/128x128.png" alt="AutoClip" width="72" height="72">

# AutoClip

### One link, one click, one finished video

Open-source video editing and rendering on your own computer. Paste a link, choose a platform, and generate **videos, covers, and publishing copy** for TikTok, Instagram Reels, YouTube Shorts, Bilibili, YouTube, Douyin, and Xiaohongshu.

The software is free. Cloud models are billed based on usage. You can open the editor whenever you need to make adjustments.

<p>
  <a href="https://github.com/zhouxiaoka/autoclip/releases/latest"><img src="https://img.shields.io/github/v/release/zhouxiaoka/autoclip?style=flat-square" alt="GitHub release"></a>
  <a href="https://github.com/zhouxiaoka/autoclip/stargazers"><img src="https://img.shields.io/github/stars/zhouxiaoka/autoclip?style=flat-square" alt="GitHub stars"></a>
  <a href="https://github.com/zhouxiaoka/autoclip/releases"><img src="https://img.shields.io/github/downloads/zhouxiaoka/autoclip/total?style=flat-square" alt="Downloads"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="License: MIT"></a>
</p>

<a href="https://trendshift.io/repositories/25801"><img src="https://trendshift.io/api/badge/repositories/25801" alt="AutoClip — GitHub Trending" width="250" height="55"></a>

**[Official Website](https://zhouxiaoka.github.io/autoclip_intro/)** · **[Download Desktop App](https://github.com/zhouxiaoka/autoclip/releases/latest)** · [Showcase](https://zhouxiaoka.github.io/autoclip_intro/cases/) · [Research](docs/research/2026-10-what-drives-views/article-en.md) · [Quick Start](#quick-start) · [Documentation](#documentation) · [Report an Issue](https://github.com/zhouxiaoka/autoclip/issues/new/choose)

**English** · [简体中文](README.md) · [日本語](README-JA.md) · [한국어](README-KO.md) · [Español](README-ES.md) · [Português](README-PT.md) · [Русский](README-RU.md) · [Français](README-FR.md)

</div>

**[Latest Stable Release](https://github.com/zhouxiaoka/autoclip/releases/latest)**. The desktop app, CLI, and MCP are updated together. Check the version with `autoclip --version` or the MCP `get_version` tool. See the [changelog](CHANGELOG.md) for fixes to one-click video generation, subtitle pagination, speaker framing, and long-video processing queues. Existing users should upgrade to the latest version.

## Real-World Video Examples

Click a thumbnail or the "Play" link to watch the complete generated video. The language listed below refers to the subtitle language of the finished video. Six examples are featured here, with another ten available in the expandable section.

### Vertical Format · Interview Style and Full-Screen Podcast Style

<table width="100%">
<tr>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/gates-ezra/01.mp4?v=2026-10-01g"><img src="docs/images/demos/gates-ezra-01.jpg" width="180" alt="Bill Gates — Can AI Pretend to Be Stupid During Testing?"></a><br>
<strong>Bill Gates</strong><br>
Interview Style · Douyin · Chinese<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/gates-ezra/01.mp4?v=2026-10-01g">▶ Play 1:01</a> · <a href="https://www.youtube.com/watch?v=A_156w0aYtU">Original</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/ai-labs-debate/01.mp4?v=2026-10-01g"><img src="docs/images/demos/ai-labs-debate-01.jpg" width="180" alt="AI Experts Debate — We're Driving Toward a Cliff in the Fog"></a><br>
<strong>AI Experts Debate</strong><br>
Interview Style · Shorts · English<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/ai-labs-debate/01.mp4?v=2026-10-01g">▶ Play 1:25</a> · <a href="https://www.youtube.com/watch?v=OhOmLqR5nN4">Original</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/robbins-36months/01.mp4?v=2026-10-01g"><img src="docs/images/demos/robbins-36months-01.jpg" width="180" alt="Tony Robbins — Minimal Risk, Maximum Reward?"></a><br>
<strong>Tony Robbins</strong><br>
Full-Screen Podcast · Douyin · Chinese<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/robbins-36months/01.mp4?v=2026-10-01g">▶ Play 1:45</a> · <a href="https://www.youtube.com/watch?v=DuRcrbP3kag">Original</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/garfield-poehler/01.mp4?v=2026-10-01g"><img src="docs/images/demos/garfield-poehler-01.jpg" width="180" alt="Andrew Garfield and Amy Poehler — I Love Competition but Hate Fake Casualness"></a><br>
<strong>Andrew Garfield × Amy Poehler</strong><br>
Full-Screen Podcast · Shorts · English<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/garfield-poehler/01.mp4?v=2026-10-01g">▶ Play 1:01</a> · <a href="https://www.youtube.com/watch?v=OJV8AaWCxQQ">Original</a>
</td>
</tr>
</table>

### Horizontal Format · Preserve the Original Aspect Ratio

<table width="100%">
<tr>
<td align="center" valign="top" width="50%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/luyu-tongliya/01.mp4?v=2026-10-01g"><img src="docs/images/demos/luyu-tongliya-01.jpg" width="360" alt="Tong Liya and Lu Yu — Dance Is in My Bones"></a><br>
<strong>Tong Liya × Lu Yu</strong><br>
Original Aspect Ratio · Bilibili · Chinese<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/luyu-tongliya/01.mp4?v=2026-10-01g">▶ Play 1:41</a> · <a href="https://www.bilibili.com/video/BV1qheu6kEFV/">Original</a>
</td>
<td align="center" valign="top" width="50%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/altman-uses-ai/01.mp4?v=2026-10-01g"><img src="docs/images/demos/altman-uses-ai-01.jpg" width="360" alt="Sam Altman — Is AI a Renaissance or an Industrial Revolution?"></a><br>
<strong>Sam Altman</strong><br>
Original Aspect Ratio · Bilibili · Chinese<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/altman-uses-ai/01.mp4?v=2026-10-01g">▶ Play 2:02</a> · <a href="https://www.youtube.com/watch?v=jZh55CQwSh8">Original</a>
</td>
</tr>
</table>

<details>
<summary>View 10 More Real-World Examples</summary>

<table width="100%">
<tr>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/neumann-doac/01.mp4?v=2026-10-01g"><img src="docs/images/demos/neumann-doac-01.jpg" width="180" alt="Adam Neumann — Success Is How You Feel One Minute Before Death"></a><br>
<strong>Adam Neumann</strong><br>
Full-Screen Podcast · TikTok · English<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/neumann-doac/01.mp4?v=2026-10-01g">▶ Play 0:59</a> · <a href="https://www.youtube.com/watch?v=IQ4JVWdj4Q0">Original</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/luyu-xiaoqi/02.mp4?v=2026-10-01g"><img src="docs/images/demos/luyu-xiaoqi-02.jpg" width="180" alt="Xiaoqi and Lu Yu — Wanting to Prove Yourself While Fearing Attention"></a><br>
<strong>Xiaoqi × Lu Yu</strong><br>
Interview Style · Douyin · Chinese<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/luyu-xiaoqi/02.mp4?v=2026-10-01g">▶ Play 0:50</a> · <a href="https://www.bilibili.com/video/BV1ighy6AEPz/">Original</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/luyu-guokeyu/01.mp4?v=2026-10-01g"><img src="docs/images/demos/luyu-guokeyu-01.jpg" width="180" alt="Guo Keyu and Lu Yu — The Joy of Acting Is in the Creative Process, Not the Result"></a><br>
<strong>Guo Keyu × Lu Yu</strong><br>
Interview Style · Douyin · Chinese<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/luyu-guokeyu/01.mp4?v=2026-10-01g">▶ Play 1:11</a> · <a href="https://www.bilibili.com/video/BV1LDYV6HEXR/">Original</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/dafoe-hot-ones/01.mp4?v=2026-10-01g"><img src="docs/images/demos/dafoe-hot-ones-01.jpg" width="180" alt="Willem Dafoe — How Fake Teeth Helped Him Become His Character"></a><br>
<strong>Willem Dafoe</strong><br>
Full-Screen Podcast · TikTok · English<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/dafoe-hot-ones/01.mp4?v=2026-10-01g">▶ Play 1:07</a> · <a href="https://www.youtube.com/watch?v=YqugY2zTIoI">Original</a>
</td>
</tr>
<tr>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/tim-luoyonghao/01.mp4?v=2026-10-01g"><img src="docs/images/demos/tim-luoyonghao-01.jpg" width="180" alt="TIM and Luo Yonghao — Internet Celebrities Rise Quickly and Fade Even Faster"></a><br>
<strong>TIM × Luo Yonghao</strong><br>
Interview Style · Douyin · Chinese<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/tim-luoyonghao/01.mp4?v=2026-10-01g">▶ Play 1:05</a> · <a href="https://www.bilibili.com/video/BV1B5xkzPEhx/">Original</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/jensen-dwarkesh/01.mp4?v=2026-10-01g"><img src="docs/images/demos/jensen-dwarkesh-01.jpg" width="180" alt="Jensen Huang — AI Is a Five-Layer Cake, and Energy Is the Foundation"></a><br>
<strong>Jensen Huang</strong><br>
Interview Style · Xiaohongshu · Chinese<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/jensen-dwarkesh/01.mp4?v=2026-10-01g">▶ Play 1:17</a> · <a href="https://www.youtube.com/watch?v=Hrbq66XqtCo">Original</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/karpathy-dwarkesh/01.mp4?v=2026-10-01g"><img src="docs/images/demos/karpathy-dwarkesh-01.jpg" width="180" alt="Andrej Karpathy — AI Still Cannot Work as an Intern Due to Its Cognitive Limitations"></a><br>
<strong>Andrej Karpathy</strong><br>
Interview Style · Douyin · Chinese<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/karpathy-dwarkesh/01.mp4?v=2026-10-01g">▶ Play 0:43</a> · <a href="https://www.youtube.com/watch?v=lXUZvyajciY">Original</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/apple-a20/01.mp4?v=2026-10-01g"><img src="docs/images/demos/apple-a20-01.jpg" width="180" alt="A20 Pro — Apple Chips Are Not Built Like LEGO"></a><br>
<strong>A20 Pro</strong><br>
Interview Style · Xiaohongshu · Chinese<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/apple-a20/01.mp4?v=2026-10-01g">▶ Play 2:00</a> · <a href="https://www.bilibili.com/video/BV1e4Y96FEaJ/">Original</a>
</td>
</tr>
<tr>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/stallone-nyt/01.mp4?v=2026-10-01g"><img src="docs/images/demos/stallone-nyt-01.jpg" width="180" alt="Sylvester Stallone — Writing Rocky at 60 as a Declaration of War on Aging"></a><br>
<strong>Sylvester Stallone</strong><br>
Interview Style · Douyin · Chinese<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/stallone-nyt/01.mp4?v=2026-10-01g">▶ Play 1:39</a> · <a href="https://www.youtube.com/watch?v=ccs-B_nTfZs">Original</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/mrbeast-colin-samir/01.mp4?v=2026-10-01g"><img src="docs/images/demos/mrbeast-colin-samir-01.jpg" width="180" alt="MrBeast — The First Five Seconds of a YouTube Video Matter More Than the Thumbnail"></a><br>
<strong>MrBeast</strong><br>
Full-Screen Podcast · TikTok · English<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/mrbeast-colin-samir/01.mp4?v=2026-10-01g">▶ Play 1:42</a> · <a href="https://www.youtube.com/watch?v=9IQ_ldV9z_A">Original</a>
</td>
<td></td>
<td></td>
</tr>
</table>

</details>

Watch more examples of videos, covers, and publishing copy in the **[official showcase](https://zhouxiaoka.github.io/autoclip_intro/cases/)**. You are welcome to [submit your own creations](https://github.com/zhouxiaoka/autoclip/discussions/new?category=show-and-tell). Original footage remains the property of its respective owners and is shown solely to demonstrate the results.

## What AutoClip Can Do

### Paste a Link and Generate Videos

Choose a platform, and AutoClip automatically generates videos that meet its aspect ratio and duration requirements.

For each platform, AutoClip ranks candidate clips and automatically generates up to 10 qualifying clips. Additional candidates remain available as alternatives, which you can generate individually using the "Generate This Clip" option.

Every finished clip includes a cover image, title, description, hashtags, and a ZIP publishing package.

### Finished Videos Come Ready to Publish

Douyin and Xiaohongshu use interview-style layouts by default. TikTok, Instagram Reels, and YouTube Shorts use full-screen podcast layouts by default. Both vertical styles can be selected manually.

Captions and publishing copy follow the platform's language settings. Bilibili and YouTube use horizontal video layouts by default.

The frame follows the active speaker, while shots without people retain the complete original image. Branded outro clips are enabled by default and can be disabled in Settings. Copied publishing copy does not include AutoClip branding.

### Your Videos Stay on Your Computer

Editing, framing, and rendering run locally on your computer.

You can choose your analysis model. Subtitles can come from the original creator, local Whisper or SenseVoice transcription, or a configured cloud transcription service.

The CLI, MCP, and desktop app all use the same one-click video generation workflow.

## Real-World Processing Time and Costs

The following measurements were collected from three different source videos during development. They are not a controlled speed comparison using the same input.

Costs are estimated from the Qwen-Plus text model usage at the time of testing. They exclude cloud speech recognition, AI image generation, and publishing service fees. Actual charges depend on the service provider you choose.

| Version | Source Video | Processing Time | Estimated Text Model Cost (CNY) |
| --- | --- | ---: | ---: |
| **New version · With subtitles** | Jensen Huang · 1h 43m (English → Xiaohongshu) | **7.5 minutes / 10 clips** | **¥0.09** |
| New version · Without subtitles | TIM × Luo Yonghao · 2h 52m (Chinese → Douyin) | 29.5 minutes / 10 clips | ¥0.20 |
| Older version | MrBeast · 2h 06m (English → TikTok) | 65 minutes | ¥0.64 |

<details>
<summary>Test Conditions and Records</summary>

Testing took place on October 1, 2026, using the same Apple Silicon Mac. The first two examples used the new processing pipeline and automatically generated 10 clips each. The older pipeline generated 33 clips, so the source material and output quantities differed.

The Jensen Huang example used creator-provided subtitles. The TIM example used local Whisper Base transcription.

When creator-provided subtitles are available, transcription can be skipped. Otherwise, local or cloud transcription can be selected. Generating additional platforms or alternative clips increases processing time and usage.

For complete processing records and cost calculation methods, see [Cost and Processing Time](docs/COST_PER_VIDEO.md).

</details>

## You Choose the Models and Control Your Data

Editing and rendering take place on your computer.

When cloud analysis is enabled, relevant subtitles and text are sent to the selected service. Visual analysis or reference-frame image generation sends the necessary sampled frames. Cloud transcription sends audio.

When local analysis and local transcription are used, the corresponding cloud APIs are not required.

Finished videos are uploaded only when you choose to publish through a connected platform. Anonymous analytics and error reporting can be disabled in Settings.

See the [Privacy Policy](docs/PRIVACY.md) for details.

## Quick Start

| Use Case | Recommended Method | Requirements |
| --- | --- | --- |
| Create videos on your computer | **Desktop App** | macOS with Apple Silicon or Windows x64 |
| Self-host a Web service or run on Linux | **Docker** | Docker and Compose v2 |
| Batch processing or agent integration | **CLI / MCP** | Python 3.10+ (Python 3.11 recommended) and FFmpeg |

### Desktop App

1. **Download and install:** Visit [Releases](https://github.com/zhouxiaoka/autoclip/releases/latest). For macOS with Apple Silicon, download the `.dmg` file. For Windows 10 or 11 x64, download the `-setup.exe` installer. The installer includes Python and FFmpeg.
2. **Configure your model:** In Settings, select a provider, enter your API key, choose an available analysis model, test the connection, and save. For local models, start the service in Ollama or LM Studio and load a model first.
3. **Paste a link and choose a platform:** Start with an interview or podcast that already has subtitles. Select your preferred vertical layout if needed. For videos without subtitles, prepare Whisper or SenseVoice in Settings, or configure cloud transcription.
4. **Review and download:** Preview the generated videos and check subtitle accuracy, framing, and content completeness. Download the publishing package or connect an account to publish directly. Generate alternative clips if you need more options.

Intel-based Macs and Linux can use Docker or the CLI.

See the [Installation Guide](docs/USER_INSTALLATION_GUIDE.md) and [Latest Release](https://github.com/zhouxiaoka/autoclip/releases/latest) for installation requirements, first-launch notices, and the acceptance scope of the current release.

[Complete Installation and First-Use Guide](docs/USER_INSTALLATION_GUIDE.md) · [Need Help?](docs/FAQ.md)

### Docker / Web Deployment

```bash
git clone https://github.com/zhouxiaoka/autoclip.git
cd autoclip
cp env.example .env
mkdir -p data logs uploads
docker compose up -d --build
```

Open the [Web Interface](http://localhost:3000). The [API Documentation](http://localhost:8000/docs) becomes available after the backend starts.

For deployment details, see the [Docker Guide](DOCKER.md).

If you encounter directory permission errors on Linux, correct ownership of the data directories before starting:

```bash
docker compose run --rm --no-deps --user root --entrypoint sh autoclip -c 'chown -R autoclip:autoclip /app/data /app/logs /app/uploads'
docker compose up -d
```

When accessing the application through a LAN IP address or custom domain, add the frontend address to `AUTOCLIP_ALLOWED_ORIGINS` in `.env`. Multiple addresses can be separated by commas.

### CLI / MCP

Python 3.10 or later is required, with Python 3.11 recommended. FFmpeg and FFprobe must be available in your PATH. The local CLI does not require Redis.

Download the [Official CLI / MCP ZIP](https://github.com/zhouxiaoka/autoclip/releases/latest). Extract it and run the following commands from the extracted directory:

```bash
python3 -m venv venv
source venv/bin/activate
python -m pip install -r requirements.txt
python -m pip install --force-reinstall --no-deps autoclip_mcp-*-py3-none-any.whl
```

Alternatively, install directly without downloading the ZIP:

```bash
# One-line installation
uvx autoclip-mcp
npx skills add zhouxiaoka/autoclip
```

Or install from source in the cloned repository's root directory:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python -m pip install --no-deps .
autoclip --version
```

The commands above are for macOS and Linux. On Windows, create and activate the virtual environment using:

```powershell
py -m venv venv
.\venv\Scripts\Activate.ps1
```

Then run the same `python -m pip` installation commands.

Save your model configuration before use. You can reuse settings from the desktop app. For standalone use, configure your own data directory using the ZIP's example configuration without API keys.

See the [CLI / MCP Guide](docs/CLI_AND_MCP.md) for details.

The `produce` command does not use the temporary provider override from the older `run --provider` command. Existing subtitles can be supplied using `--srt` to skip transcription.

```bash
autoclip --version
autoclip produce talk.mp4 --srt talk.srt --platform douyin --portrait-style podcast --json
autoclip outputs PROJECT_ID --export-kits
```

The MCP server is started by the client. To debug it separately, run `autoclip mcp` in another terminal.

For OpenCode, run:

```bash
autoclip mcp install opencode
```

This writes the configuration to the client.

Replace `PROJECT_ID` with the project ID from the generated output.

The new MCP entry points are `start_quick_output` and `get_quick_output_status`. The client's `command` must point to the absolute path of the `autoclip` executable inside the virtual environment, and `args` must be `["mcp"]`.

The older `run` and `export` commands and legacy clipping tools remain compatible.

See the [CLI / MCP Guide](docs/CLI_AND_MCP.md), [OpenCode Integration](docs/OPENCODE.md), and [Agent Skill](skills/autoclip/SKILL.md).

## Model Configuration

| Method | Configuration |
| --- | --- |
| Cloud API | Select a provider in Settings and enter your own API key. OpenAI-compatible services can also use a custom Base URL. |
| Ollama | Default address: `http://localhost:11434/v1`. Pull and start a local model first, then select a model actually provided by the running service. No API key is required. |
| LM Studio | Load a model and start the Local Server. Default address: `http://localhost:1234/v1`. |

When Docker accesses a model service running on the host computer, `localhost` points to the container itself. Change the address to one that the container can use to reach the host.

[Model Configuration Guide](docs/MULTI_LLM_PROVIDER_GUIDE.md) · [Local Models and Container Configuration](docs/CLI_AND_MCP.md)

## Special Thanks ❤️

<table>
<tr>
<td align="center" width="140">
<a href="https://88api.ai/sign-up?aff=2PIc"><img src="docs/sponsors/88api-logo.jpg" alt="88API" width="88"></a><br>
<a href="https://88api.ai/sign-up?aff=2PIc"><strong>88API</strong></a>
</td>
<td>
Thanks to <strong>88API Token Aggregation Platform</strong> for sponsoring AutoClip!

The platform aggregates language and coding models, including GPT, Claude, Gemini, Grok, DeepSeek, Kimi, and GLM. These models can be used for subtitle analysis, highlight selection, and title generation.

🎨 <strong>Multimedia Capabilities:</strong> The platform offers image models such as GPT-Image, Gemini, and Grok; video models such as Seedance, Veo, MiniMax Hailuo H3, Kling, and Grok; and speech capabilities such as Whisper and TTS. AutoClip can connect to compatible interfaces for analysis, cover image generation, and subtitle transcription.

🏷️ <strong>Services and Billing:</strong> According to the partner, the platform is operated by an overseas company and offers human customer support, official invoices, and a 1:1 top-up ratio. Actual model availability, services, and billing terms are determined by the platform.

🎁 <strong>New User Offer:</strong> Register through the <a href="https://88api.ai/sign-up?aff=2PIc">exclusive referral link</a> to receive trial credits for testing model capabilities. Eligibility and conditions are subject to the promotion page. See the <a href="docs/88API_SETUP.md">Integration Guide</a>.
</td>
</tr>
<tr>
<td align="center" width="140">
<a href="https://www.infistar.cc/register?aff=XLK3BCM6&amp;ref_source=link"><img src="docs/sponsors/infistar-logo.svg" alt="Infistar" width="88"></a><br>
<a href="https://www.infistar.cc/register?aff=XLK3BCM6&amp;ref_source=link"><strong>Infistar.cc<br>Infinite Galaxy</strong></a>
</td>
<td>
Thanks to <strong>Infistar.cc</strong> for sponsoring AutoClip!

The service provides multi-model APIs suitable for long-video subtitle analysis, highlight selection, and title generation.

⚙️ <strong>Compatible Integration:</strong> Select an OpenAI-compatible interface in AutoClip, then enter the Base URL, API key, and an available model.

🧩 <strong>Model Selection:</strong> The partner offers model families such as Claude, GPT, Gemini, and DeepSeek. You can compare models that support compatible interfaces for subtitle analysis and highlight selection.

🏷️ <strong>Pricing and Services:</strong> According to the partner, some models cost as little as 0.1% of their official list prices. RMB settlement, invoicing, and model verification are also offered. Specific models, pricing, and service conditions are subject to the platform.

🎁 <strong>Exclusive AutoClip Offer:</strong> Register through the <a href="https://www.infistar.cc/register?aff=XLK3BCM6&amp;ref_source=link">exclusive referral link</a> to receive <strong>$5 in trial credits</strong>. Eligibility and conditions are subject to the promotion page. See the <a href="docs/INFISTAR_SETUP.md">Integration Guide</a>.
</td>
</tr>
<tr>
<td align="center" width="140">
<a href="https://go.apimart.ai/tw-autoclip"><img src="docs/sponsors/apimart.png" alt="APIMart" width="88"></a><br>
<a href="https://go.apimart.ai/tw-autoclip"><strong>APIMart</strong></a>
</td>
<td>
Thanks to <strong>APIMart</strong> for sponsoring this project!

APIMart is a low-cost API platform focused on AI image and video generation. GPT-Image-2 is advertised at prices as low as <strong>$0.006 per image</strong>, with more than <strong>160 images per US dollar</strong>.

Images and videos use a unified asynchronous API. Submit a task, receive an ID, and retrieve results through callbacks. The service is designed to handle large batches without request timeouts, and switching models does not require code changes.

Pay only for usage, with no monthly fee. You can get started through the <a href="https://go.apimart.ai/tw-autoclip">registration link</a>.
</td>
</tr>
</table>

## Frequently Asked Questions

<details>
<summary>Do I need to pay or provide an API key?</summary>

The software is free and open-source under the MIT License.

Cloud analysis, transcription, and AI image generation are billed by the selected service provider and require your own credentials. Automatic cover design does not use paid image generation by default.

Local analysis through Ollama or LM Studio does not require a cloud API key, but suitable hardware is needed.

Direct publishing also requires your own Bilibili or [Upload-Post](https://www.upload-post.com) account.

</details>

<details>
<summary>Will my videos be uploaded?</summary>

Editing and rendering take place on your computer.

Cloud analysis sends relevant subtitles and text to the selected service. Visual analysis or reference-frame image generation sends the necessary sampled frames, while cloud transcription sends audio.

Local analysis and transcription do not require the corresponding cloud APIs.

Finished videos are uploaded only when you choose to publish through a connected platform. Anonymous analytics and error reporting can be disabled in Settings.

See the [Privacy Policy](docs/PRIVACY.md) for details.

</details>

<details>
<summary>What types of videos work best?</summary>

Interviews, podcasts, courses, and talking-head videos are the primary tested use cases. Videos with creator-provided subtitles are processed fastest.

If subtitles are missing, use local or cloud transcription. For gameplay recordings or videos with little spoken dialogue, you can enable visual recognition and select a model that supports images. You should still review the selected clips.

</details>

<details>
<summary>Why were no clips generated?</summary>

Check the specific stage that failed:

- Verify that subtitle extraction or transcription succeeded.
- Check the model connection.
- Ensure FFmpeg is working correctly and sufficient disk space is available.
- Confirm that candidate clips satisfy the target platform's requirements.

YouTube long-form videos require complete clips of at least 180 seconds. For shorter source material, consider YouTube Shorts or Bilibili.

If the issue persists, include the output of `autoclip --version`, your operating system, source video duration, selected model, and sanitized logs when reporting the problem.

See [Known Issues](https://github.com/zhouxiaoka/autoclip/issues/96).

</details>

[Complete Troubleshooting Guide](docs/FAQ.md) · [Known Issues](https://github.com/zhouxiaoka/autoclip/issues/96)

## Documentation

| What You Want to Learn | Documentation |
| --- | --- |
| Installation and first video | [Installation Guide](docs/USER_INSTALLATION_GUIDE.md) |
| Self-hosting and automation | [Docker Deployment](DOCKER.md) · [CLI / MCP](docs/CLI_AND_MCP.md) · [Agent Skill](skills/autoclip/SKILL.md) · [OpenCode Integration](docs/OPENCODE.md) |
| Model configuration and troubleshooting | [Model Configuration](docs/MULTI_LLM_PROVIDER_GUIDE.md) · [FAQ](docs/FAQ.md) |
| Releases, roadmap, and privacy | [Changelog](CHANGELOG.md) · [Roadmap](ROADMAP.md) · [Community Board](docs/COMMUNITY_BOARD.md) · [Privacy Policy](docs/PRIVACY.md) |
| Research notes | [Choose the Right Moments, Not More Effects](docs/research/2026-10-what-drives-views/article-en.md) |
| Development and translation | [Contribution Guide](CONTRIBUTING.md) · [Translation Maintenance](docs/i18n.md) |

## Contributing

Contributions are welcome, including bug fixes, generated video examples, user feedback, and translation improvements.

If AutoClip has been useful to you, consider giving the project a Star.

- **Questions and discussion:** [GitHub Discussions](https://github.com/zhouxiaoka/autoclip/discussions) · [First Video Q&A](https://github.com/zhouxiaoka/autoclip/discussions/128) · [Share Ideas](https://github.com/zhouxiaoka/autoclip/discussions/129)
- **Report a bug:** Use the [Issue Templates](https://github.com/zhouxiaoka/autoclip/issues/new/choose). Include your operating system, version, selected model, reproduction steps, and sanitized logs.
- **Business inquiries:** [christine_zhouye@163.com](mailto:christine_zhouye@163.com)

This is a personally maintained project. Response times vary, and instant support or one-to-one deployment assistance is not provided.

![Star History](https://api.star-history.com/svg?repos=zhouxiaoka/autoclip&type=Date)

Thanks to FastAPI, React, Tauri, FFmpeg, yt-dlp, Whisper, FunASR, and all contributors.

This project is licensed under the [MIT License](LICENSE).
