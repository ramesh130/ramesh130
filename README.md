# 👋 Hi, I'm Ramesh Prasad

**Software Architect & Engineering Leader** (ex-Dolby) | 20+ years building **mobile, media, streaming and cloud platforms** | Now applying codec-style measurement to **LLM agent evaluation**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ramesh130)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ramesh130)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ramesh130@gmail.com)
[![Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@rameshprasad)


## 🚀 About Me
I'm a technology leader and software architect based in Sydney. My career runs the full media stack, from wavelet codecs on DSPs and FPGAs, through HLS/DASH ad-insertion platforms, to ultra-low-latency WebRTC SDKs on Android. I've moved between hands-on engineering, architecture, and leadership at startups and global technology companies.

- 🔬 **Current Focus**: Evaluating LLM agents on quality, cost and latency together, the way codecs are judged on rate-distortion curves
- 🚀 **Active Project**: [pareto-eval](https://github.com/ramesh130/pareto-eval), a Pareto-frontier eval harness with a judge-calibration gate
- 📚 **Learning**: AI Agents course by Ed Donner
- 🏗️ **Background**: Software architecture, platform strategy, SDK design, and performance engineering (startup time, jank, memory, latency)
- 💼 **Experience**: Dolby Laboratories (Senior Staff Architect) | AdSparx, acquired by Discovery (VP Engineering) | CCentric, acquired by EY | Co-founder & CEO, Einsteiner Technologies
- 🎓 **Education**: M.E. & B.E. in Electronics and Telecommunications | Product Management, Stanford
- 🇦🇺 **Open to**: Senior architecture, engineering leadership, AI-enabled product, and fractional CTO roles in Australia


## 🔧 Technologies & Tools
**Languages**
- Kotlin, Java, TypeScript, C, C++, Python, Swift

**Mobile & Client Platforms**
- Android, iOS, React Native, Jetpack Compose, JNI, NDK
- Profiling with Perfetto and Android Studio Profiler

**Media & Streaming**
- WebRTC, HLS, MPEG-DASH, Smooth Streaming, RTSP/RTP/RTCP, RTMP
- H.264/AVC, JPEG2000, wavelets, FFMPEG, MP4Box
- DRM: Widevine, PlayReady, Common Encryption

**Cloud & Backend**
- AWS (EC2, S3, CloudFront, RDS, ElastiCache, Elastic Beanstalk), Azure Media Services
- REST, microservices, pub-sub, Node.js

**AI & Evaluation**
- LLM agent evaluation, LLM-as-a-judge calibration (Cohen's kappa), Anthropic & OpenAI APIs
- uv, pytest, GitHub Actions

---

## 🌟 Featured Project

### ⚖️ [pareto-eval](https://github.com/ramesh130/pareto-eval)
**Multi-axis evaluation for LLM agents | Quality × Cost × Latency**
- Reports quality, USD cost and p95 latency together as a **Pareto frontier** instead of one scalar score
- Borrows the **rate-distortion curve** from video compression: a configuration is dominated when another beats it on every axis
- **Judge-calibration gate**: measures LLM-judge vs human agreement with Cohen's kappa before any judge score counts
- **CI gate** asks "did this change fall behind the frontier we already had?", not just "did quality drop?"
- Puts Claude and GPT variants on the same frontier in one run
- **Tech**: Python, uv, Anthropic & OpenAI SDKs, pytest
- 📄 [Write-up](https://github.com/ramesh130/pareto-eval/blob/HEAD/docs/writeup.md) · [Design decisions](https://github.com/ramesh130/pareto-eval/blob/HEAD/docs/decisions.md)

<img src="https://github.com/ramesh130/pareto-eval/blob/HEAD/docs/frontier.svg?raw=true" alt="Quality vs cost Pareto frontier" width="600">

## 🌟 Selected Platform Work
- **Millicast Android SDK** (Dolby): ultra-low-latency WebRTC streaming on Android in Kotlin, Java and JNI
- **OptiView Player** (Dolby): HLS/DASH streaming with ads and analytics for Android and React Native
- **DolbyON / Capture SDK** (Dolby): audio/video capture, encode, decode, transcode and editing pipeline for Android
- **Dynamic ad-insertion platform** (AdSparx, acquired by Discovery): client SDKs, media servers, manifest manipulation, transcoding and linear ad detection
- **ABC iView for Android Mobile and TV**: Kotlin (consulting)
- **Qwik codec family** (iFlect): wavelet-based image and video codecs for mobile, DSP and FPGA

### 📚 [SCPD-AI](https://github.com/ramesh130/SCPD-AI)
- A curated map of free material matching each course in Stanford's AI Graduate Certificate


## 📜 Patents & Publications
- 🏅 **US Patent 7,522,774**: Methods and apparatuses for compressing digital image data (family: EP1730846)
- 🏅 Patent filings on detecting advertisements in streamed media and on dynamic ad insertion in MPEG-DASH and Smooth Streaming with DRM
- 📖 *Wavelet Based Scalable Video Codec*, Springer/IEEE ICCCT 2010
- 📖 *Real time encoding of H.264 on handhelds*, *Scalable Video Coding and Applications*, and more


## 🤝 Let's Connect!
I'm always happy to talk about:
- 🤖 Evaluating LLM agents: frontiers, judges, and honest metrics
- 📱 Mobile SDK and platform architecture
- 🎬 Streaming, codecs, and media pipelines
- 🧭 Engineering leadership and technical strategy

**Reach out via:**
- 📧 [ramesh130@gmail.com](mailto:ramesh130@gmail.com)
- 🔗 [LinkedIn](https://www.linkedin.com/in/ramesh130)
- ✍️ [Medium](https://medium.com/@rameshprasad)

**Thanks for visiting! 🚀**
