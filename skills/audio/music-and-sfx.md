# Music and SFX Skill

> Select, create, and mix music and sound effects for professional video production.

## When to Use

- Adding background music to videos
- Creating or selecting sound effects for transitions
- Building immersive audio environments
- Mixing multiple audio layers
- Finding royalty-free music and sound effects
- Creating custom music with AI tools

## Workflow

### Step 1: Music Selection Strategy

```markdown
Choose the right music for your video:

VIDEO MOOD: [energetic / calm / dramatic / playful / serious]
CONTENT TYPE: [tutorial / vlog / documentary / commercial]
TARGET AUDIENCE: [age range, interests]

MUSIC SELECTION CRITERIA:
1. **Mood Match** - Music should enhance, not contradict the content
2. **Energy Level** - Match or slightly exceed video energy
3. **Tempo** - Fast (120+ BPM) for energy, slow (60-90 BPM) for emotion
4. **Instrumentation** - Electronic for tech, acoustic for personal
5. **Vocals** - Instrumental preferred under narration
6. **Build** - Look for songs with dynamic changes (verse/chorus)

MUSIC STRUCTURE FOR VIDEO:
| Section | Music Type | Volume |
|---------|-----------|--------|
| Hook | Energetic, attention-grabbing | -12dB |
| Intro | Builds from quiet to medium | -18dB to -15dB |
| Main Content | Consistent, low energy | -24dB to -18dB |
| Key Moments | Swell/build for emphasis | -12dB (temporary) |
| CTA/Outro | Energy returns, positive | -15dB |
```

### Step 2: Sound Effects Design

```markdown
Plan sound effects for your video:

SFX CATEGORIES:
1. **Transitions** - Whoosh, swoosh, click for scene changes
2. **Emphasis** - Ding, pop, sparkle for key points
3. **UI Sounds** - Click, tap, swipe for screen recordings
4. **Ambient** - Room tone, nature, city for atmosphere
5. **Foley** - Physical sounds matching on-screen actions
6. **Musical** - Stings, risers, impacts for dramatic moments

SFX TIMING MAP:
| Time | Visual | SFX | Purpose |
|------|--------|-----|---------|
| 0:00 | Title appears | Musical sting | Attention |
| 0:15 | Cut to new section | Soft whoosh | Transition |
| 1:30 | Text highlight | Subtle ding | Emphasis |
| 3:00 | Screen recording | UI click | Realism |
| 5:00 | Big reveal | Impact + reverb | Drama |

SFX SOURCES:
- Royalty-free: Freesound.org, Zapsplat, BBC Sound Effects
- Premium: Epidemic Sound, Artlist, SoundSnap
- AI Generation: Stable Audio, AudioCraft
```

### Step 3: Audio Mixing

```markdown
Mix music, voice, and effects:

MIXING HIERARCHY (by priority):
1. **Dialogue/Voiceover** - Always the star (-6dB to -3dB)
2. **Sound Effects** - Support visuals (-12dB to -6dB)
3. **Music** - Bed/underlay (-18dB to -12dB)

DUCKING TECHNIQUE:
- When voice starts, music drops 6-10dB
- Attack: 200-500ms (gradual drop)
- Release: 500-1000ms (gradual return)
- Use sidechain compression or manual automation

FREQUENCY SEPARATION:
- Voice: 100Hz-8kHz (this is the voice's territory)
- Music: Scoop 2-5kHz to make room for voice
- SFX: Avoid competing with voice frequencies
- Use EQ to carve space for each element

STEREO FIELD:
- Voice: Center (always)
- Music: Wide stereo
- SFX: Panned to match visual position
- Ambient: Full stereo width
```

### Step 4: AI Music Generation

```markdown
Use AI to create custom music:

TOOLS:
1. **Suno AI** - Full song generation from text prompts
2. **Udio** - High-quality music generation
3. **AIVA** - Classical and cinematic music
4. **Soundraw** - Customizable royalty-free music
5. **Mubert** - Generative music streams
6. **Stable Audio** - Open-source music generation

PROMPT TEMPLATE:
"Create a [genre] track for a [video type] about [topic].
Mood: [emotional keywords]
Tempo: [BPM range]
Instruments: [preferred instruments]
Duration: [length needed]
Structure: [intro → build → main → outro]
Reference: [similar song/artist]"

POST-GENERATION:
- [ ] Check for AI artifacts (weird sounds)
- [ ] Ensure seamless loop if needed
- [ ] Verify commercial use rights
- [ ] Match loudness to your mix (-18dB to -24dB bed)
```

### Step 5: Final Mix and Master

```markdown
Final audio mix checklist:

LEVELS:
- [ ] Voice: -6dB to -3dB peak
- [ ] Music: -18dB to -12dB (under voice)
- [ ] SFX: -12dB to -6dB
- [ ] Overall: -16 LUFS integrated

PROCESSING:
- [ ] EQ applied to each element
- [ ] Compression on voice (3:1 ratio)
- [ ] Sidechain ducking on music
- [ ] De-essing on voice
- [ ] Reverb on SFX (subtle)
- [ ] Limiter on master bus

SPATIAL:
- [ ] Voice centered
- [ ] Music in stereo
- [ ] SFX panned correctly
- [ ] No phase cancellation issues

QUALITY:
- [ ] No clipping anywhere
- [ ] Clean transitions between sections
- [ ] Consistent volume throughout
- [ ] Sounds good on phone speakers
- [ ] Sounds good on headphones
- [ ] Sounds good on laptop speakers
```

## Tools

| Tool | Platform | Price | Best For |
|------|----------|-------|----------|
| Epidemic Sound | Web | $15/mo | Curated music library |
| Artlist | Web | $10/mo | Unlimited music |
| Freesound.org | Web | Free | Community SFX |
| Suno AI | Web | Free/$10/mo | AI music generation |
| AIVA | Web | Free/$15/mo | Cinematic music |
| Audacity | All | Free | Basic mixing |
| Adobe Audition | Win/Mac | $23/mo | Professional mixing |

## Templates

### Music Cue Sheet

```markdown
# Music Cue Sheet: [Video Title]

| # | Start | End | Duration | Track | Source | License | Notes |
|---|-------|-----|----------|-------|--------|---------|-------|
| 1 | 0:00 | 0:30 | 30s | Opening Theme | Epidemic | Standard | Energetic |
| 2 | 0:30 | 8:00 | 7:30 | Background Bed | Artlist | Unlimited | Low energy |
| 3 | 5:15 | 5:25 | 10s | Sting (reveal) | Suno AI | Custom | Dramatic |
| 4 | 9:30 | 10:00 | 30s | Outro Theme | Epidemic | Standard | Uplifting |

Total music duration: [X:XX]
License requirements: [list needed licenses]
```

### SFX Layer Plan

```markdown
# SFX Plan: [Video Title]

| Timecode | Visual | SFX Type | Description | Source |
|----------|--------|----------|-------------|--------|
| 0:00 | Logo reveal | Impact | Deep boom + reverb | Freesound |
| 0:15 | Scene change | Whoosh | Left to right swoosh | Zapsplat |
| 2:30 | Text pop up | Pop | Light bubble pop | Custom |
| 4:00 | Screen tap | UI Click | Soft tap sound | Freesound |
| 8:00 | End card | Musical sting | Positive chime | Epidemic |
```

## Pitfalls

### Common Mistakes

1. **Music too loud** - Voice should always be clearly audible over music
2. **Copyright strikes** - Using copyrighted music without proper license
3. **No ducking** - Music and voice fighting for attention
4. **Too many SFX** - Sound effects should enhance, not distract
5. **Wrong mood** - Upbeat music during serious content
6. **No audio variety** - Same track throughout entire video
7. **Ignoring transitions** - Audio transitions are as important as visual ones

### Quality Checks

- [ ] Voice is clearly audible at all times
- [ ] Music doesn't distract from content
- [ ] SFX match visual actions
- [ ] No copyright issues
- [ ] Consistent loudness (-16 LUFS)
- [ ] Smooth audio transitions
- [ ] Mix sounds good on multiple devices

## Pro Tips

1. **Music first, edit second** - Edit video to the music beat for natural rhythm
2. **Layer SFX** - Combine 2-3 sounds for richer effects (impact + reverb + sub)
3. **Silence is powerful** - A moment of silence before a key point creates emphasis
4. **Match BPM to content** - Fast BPM for excitement, slow for reflection
5. **Use risers** - Build anticipation with rising tones before reveals
6. **Test on phone** - Most viewers hear on phone speakers; bass disappears
7. **Save your mix** - Export stems so you can remix later

## 中文版本

### 何时使用

- 为视频添加背景音乐
- 为转场创建或选择音效
- 构建沉浸式音频环境
- 混合多个音频层
- 寻找免版税音乐和音效
- 使用AI工具创建自定义音乐

### 工作流程概要

1. **音乐选择策略** - 情绪匹配、能量级别、节奏、器乐
2. **音效设计** - 转场、强调、UI音、环境音
3. **音频混合** - 层级优先级、闪避技术、频率分离
4. **AI音乐生成** - Suno、Udio、AIVA等工具
5. **最终混音** - 电平、处理、空间、质量检查

### 常见陷阱

- 音乐声音太大
- 版权侵权
- 没有闪避处理
- 音效过多
- 情绪不匹配

### 专业建议

- 先选音乐再剪辑
- 分层音效创造丰富效果
- 静默也是力量
- 匹配BPM与内容
- 在手机上测试混音
