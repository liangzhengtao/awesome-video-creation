# Motion Graphics Skill

> Add professional motion graphics and animations to your videos.

## When to Use

- Adding animated text and titles to videos
- Creating lower thirds and info graphics
- Building animated transitions and reveals
- Designing kinetic typography for emphasis
- Creating data visualization animations
- Building branded intro/outro sequences

## Workflow

### Step 1: Plan Your Graphics

```markdown
Motion graphics planning:

GRAPHIC TYPE:
1. **Lower Thirds** - Name/title overlays
2. **Title Cards** - Section headers
3. **Callouts** - Arrows, circles, highlights
4. **Text Animations** - Kinetic typography
5. **Data Viz** - Charts, numbers, statistics
6. **Transitions** - Animated scene changes
7. **Subscribe/Watermark** - Brand elements

For each graphic, define:
- Content (text/data)
- Animation style (fade / slide / bounce / morph)
- Duration (typically 3-5 seconds)
- Position on screen
- Brand consistency requirements
```

### Step 2: Design Principles

```markdown
Motion graphics design rules:

LAYOUT:
- Use safe margins (10% from edges)
- Follow rule of thirds for placement
- Maintain consistent spacing
- Use grid alignment for complex layouts

TYPOGRAPHY:
- Maximum 2 fonts per video
- Sans-serif for screen readability
- Minimum 40px for 1080p text
- High contrast against background
- Add text shadows or background boxes for readability

COLOR:
- Use brand colors consistently
- Ensure accessibility (contrast ratio > 4.5:1)
- Use color to create hierarchy
- Limit palette to 3-4 colors

ANIMATION:
- Ease in/out for natural movement (never linear)
- Keep animations under 0.5 seconds
- Stagger multi-element reveals
- Use motion blur for fast movements
- Match animation speed to video pace
```

### Step 3: Create Templates

```markdown
Build reusable motion graphic templates:

LOWER THIRD TEMPLATE:
```
Composition: 1920x1080, 30fps, 5 seconds
Layers:
├── Background bar (brand color, 70% opacity)
├── Name text (white, bold, 48px)
├── Title text (light gray, regular, 32px)
├── Accent line (brand accent color, 3px)
└── Logo (optional, 64x64px)

Animation:
0.0s - Background bar slides in from left
0.2s - Name text fades in
0.4s - Title text fades in
0.6s - Accent line draws on
3.5s - Everything fades out
5.0s - End

Expression for smooth easing:
easeOut(t, 0, 0.5, 0, 1)
```

TITLE CARD TEMPLATE:
```
Composition: 1920x1080, 30fps, 4 seconds
Layers:
├── Background (gradient or video)
├── Main title (72px, bold)
├── Subtitle (36px, regular)
├── Decorative elements
└── Particle effects (optional)

Animation:
0.0s - Background scales up slightly
0.3s - Title word-by-word reveal
0.8s - Subtitle fades in
1.0s - Decorative elements animate in
3.0s - Everything scales and fades out
```
```

### Step 4: AI-Assisted Motion Graphics

```markdown
Use AI to speed up motion graphics creation:

TEXT GENERATION:
- Generate text variations and layouts
- Create data visualization descriptions
- Write kinetic typography scripts

AUTOMATION:
- After Effects expressions for repetitive animations
- CapCut auto-captions for text animation
- Premiere Pro auto-reframe for multi-format

PROMPT FOR AI-GENERATED GRAPHICS:
"Create a motion graphics storyboard for [element]:
- Style: [minimal / bold / corporate / playful]
- Colors: [hex codes]
- Animation: [type]
- Duration: [seconds]
- Key frames: [number]"
```

### Step 5: Export and Integration

```markdown
Export motion graphics for integration:

TRANSPARENT BACKGROUND:
- Format: ProRes 4444 + Alpha or WebM with alpha
- Resolution: Match project (1080p or 4K)
- Frame rate: Match project (24/30/60fps)

SOLID BACKGROUND:
- Format: H.264 or ProRes 422
- Use blending mode in editor (Screen, Add, Multiply)

TEMPLATE EXPORT:
- After Effects: .mogrt (Motion Graphics Template)
- Premiere Pro: .mogrt import
- Final Cut Pro: .motn template
```

## Tools

| Tool | Platform | Price | Best For |
|------|----------|-------|----------|
| Adobe After Effects | Win/Mac | $23/mo | Professional motion graphics |
| Apple Motion | Mac | $50 | FCP integration |
| CapCut | All platforms | Free | Quick text animations |
| DaVinci Resolve (Fusion) | All | Free | Node-based compositing |
| Canva | Web | Free/$13/mo | Simple animated graphics |
| Rive | Web | Free | Interactive animations |
| Lottie/Web | Web | Free | Lightweight animations |

## Templates

### After Effects Expression Library

```javascript
// Smooth bounce
amp = 0.05;
freq = 3;
decay = 5;
n = 0;
if (numKeys > 0) {
  n = nearestKey(time).index;
  if (key(n).time > time) n--;
}
if (n > 0) {
  t = time - key(n).time;
  startVal = key(n).value;
  velocity = velocityAtTime(key(n).time - 0.001);
  value + velocity * amp * Math.sin(freq * t * 2 * Math.PI) / Math.exp(decay * t);
} else {
  value;
}

// Typewriter effect
txt = text.sourceText;
n = Math.round(time * 15); // characters per second
txt.substr(0, n);

// Wiggle with control
wiggle(2, 25); // frequency, amplitude
```

### Lower Third Design Specs

```markdown
# Lower Third Style Guide

## Style A: Minimal
- Height: 120px
- Background: Semi-transparent dark (#000000, 70%)
- Name: White, Montserrat Bold, 42px
- Title: #CCCCCC, Montserrat Regular, 28px
- Animation: Slide in from left, 0.4s ease-out

## Style B: Bold
- Height: 160px
- Background: Brand gradient
- Name: White, Impact, 52px
- Title: White, Open Sans, 24px
- Animation: Scale up + fade, 0.3s

## Style C: Modern
- Height: 100px
- Background: Accent color bar, left aligned
- Name: Dark (#1a1a1a), Roboto Bold, 36px
- Title: Dark (#666666), Roboto Regular, 24px
- Animation: Bar extends + text reveals, 0.5s
```

## Pitfalls

### Common Mistakes

1. **Over-animation** - Every element doesn't need to move; static is fine
2. **Inconsistent style** - Mixing animation styles within one video
3. **Too small text** - Text must be readable on mobile
4. **Poor timing** - Animations too fast to read or too slow to watch
5. **Linear easing** - Always use ease-in/ease-out; linear looks robotic
6. **Overcrowding** - Too many graphic elements at once
7. **No brand consistency** - Every video looks different

### Quality Checks

- [ ] All text is readable at target resolution
- [ ] Animations feel smooth and natural
- [ ] Graphics don't obscure important video content
- [ ] Brand colors and fonts are consistent
- [ ] File sizes are optimized for delivery
- [ ] Templates are reusable and editable

## Pro Tips

1. **Ease everything** - Use easy ease (F9) on every keyframe
2. **Pre-compose** - Group related layers for easy management
3. **Use null objects** - Parent animations to nulls for easy control
4. **Motion blur** - Enable for fast movements; disable for UI elements
5. **Save presets** - Save frequently used animations as presets
6. **Use expressions** - Automate repetitive animations with code
7. **Match music** - Time graphic animations to music beats

## 中文版本

### 何时使用

- 为视频添加动画文字和标题
- 创建下方三分之一字幕和信息图形
- 构建动画转场和揭示效果
- 设计动态排版强调
- 创建数据可视化动画
- 构建品牌化的片头/片尾序列

### 工作流程概要

1. **规划图形** - 确定类型、内容、动画风格、时长
2. **设计原则** - 布局、排版、颜色、动画规则
3. **创建模板** - 构建可复用的动态图形模板
4. **AI辅助** - 利用AI加速创作
5. **导出整合** - 透明背景导出、混合模式

### 常见陷阱

- 过度动画
- 风格不一致
- 文字太小
- 时机不当
- 线性缓动

### 专业建议

- 所有关键帧都使用缓动
- 预合成相关图层
- 使用空对象控制动画
- 快速运动启用运动模糊
- 保存常用动画预设
