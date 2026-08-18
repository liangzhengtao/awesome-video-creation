# AI-Generated Video Skill

> Create videos using AI generation tools for footage, animations, and visual effects.

## When to Use

- Creating B-roll footage that's hard or expensive to film
- Generating concept visualizations and mockups
- Producing animated explainer content
- Creating unique visual styles and aesthetics
- Generating product mockups and prototypes
- Building video content at scale with limited resources

## Workflow

### Step 1: Define Your AI Video Needs

```markdown
Assess what AI can help with in this project:

VIDEO TYPE: [explainer / B-roll / product demo / artistic / educational]
STYLE: [realistic / cinematic / anime / 3D / abstract / pixel art]
DURATION: [seconds needed]
RESOLUTION: [720p / 1080p / 4K]
CONSISTENCY: [how important is character/object consistency]

AI Video Use Cases:
1. **B-Roll Generation** - Supplement real footage with AI scenes
2. **Full AI Production** - Entire video generated with AI
3. **Hybrid Approach** - Mix AI and real footage
4. **Animation** - AI-assisted animation and motion
5. **Visual Effects** - AI enhancement of real footage
```

### Step 2: Choose Your Tools

```markdown
Select AI video tools based on needs:

FOR REALISTIC VIDEO:
- Runway Gen-3: High quality, text/image to video
- Pika Labs: Good quality, easy to use
- Kling AI: Longer clips, good motion
- Luma Dream Machine: Fast generation, good quality

FOR ANIMATION/STYLE:
- Deforum (Stable Diffusion): Artistic animations
- Kaiber: Style transfer and animation
- Genmo: Creative animated content

FOR CONSISTENT CHARACTERS:
- HeyGen: Talking head avatars
- D-ID: Photo-to-video faces
- Synthesia: Professional AI presenters

FOR ENHANCEMENT:
- Topaz Video AI: Upscaling and enhancement
- CapCut AI: Auto-editing features
- Adobe Firefly Video: Integrated with Premiere
```

### Step 3: Prompt Engineering for Video

```markdown
Write effective AI video prompts:

STRUCTURE: [Subject] + [Action] + [Setting] + [Style] + [Camera] + [Lighting]

EXAMPLES:

Basic: "A cat sitting on a windowsill"

Enhanced: "A fluffy orange tabby cat sitting peacefully on a sunlit
windowsill, watching rain fall outside, soft natural lighting from
the window, shallow depth of field, cinematic 4K, slow gentle camera
push in"

KEYWORD CATEGORIES:
- Subject: [what/who is in the scene]
- Action: [what's happening]
- Environment: [where it takes place]
- Style: [artistic direction]
- Camera: [angle, movement, lens]
- Lighting: [type, direction, mood]
- Quality: [resolution, detail level]

NEGATIVE PROMPTS:
"blurry, distorted, low quality, watermark, text, deformed,
disfigured, bad anatomy, extra limbs"
```

### Step 4: Maintain Consistency

```markdown
Achieve visual consistency across AI clips:

CHARACTER CONSISTENCY:
1. Use reference images for every generation
2. Lock seed numbers when you find a good result
3. Use consistent description templates
4. Train a LoRA/model on your character (advanced)
5. Use IP-Adapter for image-guided generation

STYLE CONSISTENCY:
1. Define a style prompt and reuse it
2. Use consistent negative prompts
3. Match color grading in post-production
4. Use the same model/settings across clips
5. Create a style guide document

SCENE CONSISTENCY:
1. Generate scene establishing shots first
2. Use image-to-video for continuation
3. Maintain consistent lighting descriptions
4. Lock environment details in a template
```

### Step 5: Post-Production Integration

```markdown
Integrate AI footage into your video:

UPSCALING:
- Run low-res AI clips through Topaz Video AI
- Target: 1080p minimum for final output
- Use "Proteus" model for general enhancement

STABILIZATION:
- AI clips may have jitter; stabilize in post
- Use warp stabilizer (Premiere/Resolve)
- Apply subtle motion blur if needed

COLOR MATCHING:
- Match AI clips to real footage color palette
- Use LUTs for consistent color treatment
- Adjust saturation (AI often oversaturates)

TIMING:
- AI clips may need speed adjustment
- Add subtle camera movement if static
- Use time remapping for natural pacing
```

## Tools

| Tool | Type | Price | Best For |
|------|------|-------|----------|
| Runway | Gen-3 video | $12-76/mo | Highest quality |
| Pika Labs | Video generation | Free/$8/mo | Quick iterations |
| Kling AI | Long video | Free/$8/mo | Longer clips |
| HeyGen | Talking heads | $24/mo | AI presenters |
| Synthesia | AI avatars | $22/mo | Corporate/edu |
| Topaz Video AI | Enhancement | $299 | Upscaling |
| Stable Video Diffusion | Open-source | Free | Local generation |
| Luma Dream Machine | Fast gen | Free/$30/mo | Quick concepts |

## Templates

### AI Video Prompt Template

```markdown
# Scene: [Scene Name]

## Base Prompt
[Subject] [action] in [setting], [style keywords],
[camera movement], [lighting], [quality modifiers]

## Negative Prompt
[standard negatives] + [scene-specific negatives]

## Settings
- Model: [Runway/Pika/Kling/etc.]
- Aspect Ratio: [16:9/9:16/1:1]
- Duration: [4s/8s/16s]
- Seed: [locked number if consistent]
- CFG/Guidance: [value]

## Reference Images
- [ ] Character ref: [attached]
- [ ] Style ref: [attached]
- [ ] Scene ref: [attached]
```

### Hybrid Production Plan

```markdown
# Video: [Title]
# Approach: Hybrid (Real + AI)

## Real Footage Needed
| # | Shot | Source | Notes |
|---|------|--------|-------|
| 1 | Talking head | Self-film | Main narration |
| 2 | Product demo | Self-film | Screen capture |

## AI-Generated Clips
| # | Scene | Tool | Prompt Summary |
|---|-------|------|----------------|
| 1 | City aerial | Runway | Futuristic city, drone shot |
| 2 | Nature B-roll | Pika | Forest timelapse, golden hour |

## Integration Plan
- Scene 3: Real → AI transition via dissolve
- Scene 7: AI B-roll under real narration
- Color grade: Apply unified LUT to all clips
```

## Pitfalls

### Common Mistakes

1. **Uncanny valley** - AI humans look "almost right" which is creepy; avoid or stylize
2. **Inconsistent characters** - Characters change appearance between clips
3. **Weird hand/finger artifacts** - Still common; avoid close-ups of AI hands
4. **Legal ambiguity** - Check platform ToS for commercial use of AI content
5. **Over-reliance** - AI footage works best mixed with real content
6. **Ignoring artifacts** - Always review AI clips frame by frame before using
7. **Wrong physics** - AI often violates physics; viewers notice subconsciously

### Quality Checks

- [ ] No visible artifacts or distortion in AI clips?
- [ ] Characters remain consistent across scenes?
- [ ] Physics and motion look natural?
- [ ] AI footage color matches real footage?
- [ ] Legal rights cleared for commercial use?
- [ ] Upscaled quality meets platform standards?

## Pro Tips

1. **Image-to-video beats text-to-video** - Start with a generated or real image for better control
2. **Generate 10, use 1** - AI generation is a numbers game; over-generate and curate
3. **Use AI for what it's good at** - Abstract, artistic, and nature scenes; avoid realistic humans
4. **Lock seeds** - When you get a good result, save the seed for variations
5. **Post-process heavily** - AI footage needs color grading and stabilization to blend
6. **Mix real and AI** - Use real footage for trust-building (faces, hands), AI for atmosphere
7. **Stay current** - AI video tools improve monthly; revisit old assessments quarterly

## 中文版本

### 何时使用

- 创建难以拍摄或成本高昂的B-roll素材
- 生成概念可视化和模型
- 制作动画解说内容
- 创建独特的视觉风格和美学
- 生成产品模型和原型
- 以有限资源大规模构建视频内容

### 工作流程概要

1. **确定AI视频需求** - 类型、风格、时长、一致性要求
2. **选择工具** - Runway、Pika、Kling、HeyGen等
3. **提示词工程** - 主体+动作+场景+风格+镜头+灯光
4. **保持一致性** - 角色、风格、场景的视觉统一
5. **后期整合** - 超分辨率、稳定、色彩匹配

### 常见陷阱

- 恐怖谷效应
- 角色外观不一致
- 手部/手指伪影
- 商用版权不明确
- 过度依赖AI

### 专业建议

- 图生视频优于文生视频
- 生成10个，选用1个
- AI擅长抽象、艺术、自然场景
- 锁定随机种子以保持一致性
- 真实素材与AI素材混合使用
