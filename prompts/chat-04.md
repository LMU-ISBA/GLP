# AI Coding Agent Prompt Creation

A comprehensive guide to creating effective prompts for AI coding agents like Lovable to build SDG-focused web applications.

## 🖥️ Setup Instructions

**Before you begin:**
1. Go to [lovable.dev](https://lovable.dev) (or your preferred AI coding agent)
2. Ensure you have access to a reasoning model (o3, Claude 4, or Gemini 2.5 Pro)
3. **Prerequisites**: Complete Chat 01 (SDG selection), Chat 02 (Deep research), and Chat 03 (Elevator pitch)
4. Gather a UI mockup or design inspiration (e.g., from Dribbble)

---

## 🎯 Understanding AI Coding Agents

AI coding agents like Lovable are specialized tools that can:
- **Generate Complete Applications**: Create full-stack web apps from descriptions
- **Understand Design Context**: Interpret UI mockups and design requirements
- **Implement Best Practices**: Follow modern development standards and frameworks
- **Iterate Rapidly**: Make changes based on feedback and requirements

### 🔧 **Popular AI Coding Agents**
- **Lovable**: Specialized in rapid web app prototyping
- **Bolt.new**: Full-stack development with real-time preview
- **Cursor**: AI-powered IDE with code generation
- **GitHub Copilot**: Code completion and generation assistant

---

## 🚀 Step-by-Step Prompt Creation

### 📝 **Step 1: Define Your ROLE**

Establish the AI's expertise for development tasks.

**Example Role:**
```markdown
ROLE: You are an expert full-stack developer and UX/UI designer specializing in creating compelling landing pages for social impact startups. You excel at translating business concepts into user-friendly, conversion-optimized web experiences.
```

### 🌍 **Step 2: Build Comprehensive CONTEXT**

Combine all previous research and visual inspiration.

#### **Context Component 1: Project Foundation**
```markdown
CONTEXT:
- SDG Focus: [Insert your chosen SDG from Chat 01]
- Target Audience: [From your Chat 01 career counselor responses]
- Research Insights: [Key findings from Chat 02 deep research]
- Elevator Pitch: [Your final pitch from Chat 03]
```

#### **Context Component 2: Visual Design Reference**
- **UI Mockup**: Upload image from Dribbble or design inspiration
- **Design Style**: Modern, clean, professional, accessible
- **Brand Personality**: [Based on your SDG and target audience]

#### **Context Component 3: Technical Requirements**
```markdown
- Platform: Web application (responsive design)
- Purpose: Landing page for startup pitch competition demo
- Timeline: Rapid prototype development
- Framework: [Specify if needed, e.g., React, Vue, or let AI choose]
```

### 🎯 **Step 3: Define Your TASK**

Be specific about deliverables and requirements.

**Core Task:**
```markdown
TASK: Create a compelling landing page for my SDG-focused web application that includes:

1. Hero section with elevator pitch integration
2. Problem/solution explanation
3. Key features overview
4. SDG impact demonstration
5. Call-to-action for demo/signup
6. Contact/about section

The landing page should be suitable for presentation at a startup pitch competition and effectively communicate the value proposition to both judges and potential users.
```

### 📚 **Step 4: Provide EXAMPLES**

Reference proven frameworks and structures.

**Example Framework - PRD for AI Prototyping:**
```markdown
EXAMPLES:
Use a startup landing page structure:
- Hero: Problem statement + solution in one compelling headline
- Social Proof: SDG alignment and impact metrics
- Features: 3-4 key capabilities with icons/visuals
- Demo/Preview: Screenshot or video placeholder
- CTA: Primary action (Try Demo, Sign Up, Learn More)
- Footer: Contact, social links, additional resources

Reference sites like: Stripe, Notion, or Figma for clean, conversion-focused design patterns.
```

### 📄 **Step 5: Specify OUTPUT FORMAT**

Ensure the result is exactly what you need.

```markdown
OUTPUT FORMAT:
- LLM-friendly Markdown with clear sections
- Include HTML/CSS/JavaScript code blocks
- Provide component-based structure
- Add comments explaining design decisions
- Include placeholder content that can be easily customized
- Responsive design considerations noted
```

### 🗣️ **Step 6: Set Clear TONE**

Eliminate ambiguity in requirements.

```markdown
TONE: 
- No ambiguity in technical specifications
- Clear, actionable instructions
- Professional yet approachable copy
- Emphasize social impact and innovation
- Maintain startup energy and optimism
```

### 🤖 **Step 7: Select Reasoning MODEL**

Choose models that excel at structured thinking.

**Recommended Models:**
- **OpenAI o3**: For complex development planning
- **Claude 4 Opus**: For design and UX reasoning
- **Gemini 2.5 Pro**: For comprehensive solution architecture

---

## 🔄 Implementation & Feedback Process

### 🚀 **Step 8: Submit to Lovable**

1. **Format Your Prompt**: Ensure all components are clearly structured
2. **Include Visual References**: Upload UI mockup or design inspiration
3. **Submit Complete Request**: Don't break into multiple small requests
4. **Monitor Generation**: Watch for errors or clarification requests

### 📊 **Step 9: Evaluate Output Quality**

#### ✅ **What to Look For (Good)**
- **Design Quality**: Clean, modern, professional appearance
- **Content Integration**: Elevator pitch and SDG focus clearly communicated
- **Technical Implementation**: Responsive, accessible, fast-loading
- **User Experience**: Intuitive navigation and clear call-to-actions
- **Brand Consistency**: Aligns with your SDG mission and target audience

#### ❌ **What to Flag (Needs Improvement)**
- **Generic Content**: Placeholder text not customized to your project
- **Poor Responsiveness**: Doesn't work well on mobile devices
- **Unclear Value Proposition**: Elevator pitch not prominently featured
- **Missing SDG Connection**: Impact and alignment not clearly communicated
- **Technical Issues**: Broken links, slow loading, accessibility problems

### 🔄 **Step 10: Iteration Strategy**

**Feedback Template:**
```markdown
FEEDBACK FOR LOVABLE:

POSITIVE ASPECTS:
- [Specific elements that work well]
- [Design choices that align with requirements]

AREAS FOR IMPROVEMENT:
- [Specific issues with proposed solutions]
- [Missing elements from original requirements]

PRIORITY CHANGES:
1. [Most critical fix needed]
2. [Secondary improvement]
3. [Nice-to-have enhancement]

Please update the code addressing these priorities while maintaining the positive aspects.
```

---

## 🎯 Complete Prompt Template

```markdown
ROLE: You are an expert full-stack developer and UX/UI designer specializing in social impact startup landing pages.

CONTEXT:
- SDG Focus: [Your chosen SDG]
- Elevator Pitch: [Your refined pitch from Chat 03]
- Target Audience: [From Chat 01 analysis]
- Research Insights: [Key findings from Chat 02]
- Design Reference: [Describe uploaded UI mockup]
- Purpose: Startup pitch competition demo

TASK: Create a compelling, responsive landing page that showcases my SDG-focused web application with hero section, problem/solution explanation, key features, impact demonstration, and strong call-to-action.

EXAMPLES: Follow successful startup landing page patterns (Stripe, Notion-style) with clear value proposition, social proof, and conversion optimization.

OUTPUT FORMAT: Complete HTML/CSS/JavaScript code with component structure, responsive design, and detailed implementation comments.

TONE: Professional, innovative, impact-focused, with clear technical specifications and no ambiguity.

Generate the complete landing page code now.
```

---

## 💡 Pro Tips for Success

### ✅ **Best Practices**
- **Start with reasoning models** for better prompt structure
- **Include visual references** to guide design decisions
- **Be specific about technical requirements** (frameworks, features)
- **Reference successful examples** for pattern recognition
- **Plan for iteration** - first attempt rarely perfect

### 🚀 **Advanced Techniques**
- **Multi-stage prompting**: Break complex requests into phases
- **A/B testing**: Generate multiple versions for comparison
- **User story integration**: Include target user personas
- **Performance requirements**: Specify loading speed and accessibility needs
- **Integration planning**: Consider future feature additions

---

## 🔍 Quality Assurance Checklist

Before submitting your final prototype:

- [ ] **Functionality**: All links and interactions work
- [ ] **Responsiveness**: Tests well on mobile, tablet, desktop
- [ ] **Content**: Elevator pitch prominently featured
- [ ] **SDG Alignment**: Clear connection to chosen sustainable goal
- [ ] **Visual Appeal**: Professional, modern design
- [ ] **Performance**: Fast loading, optimized images
- [ ] **Accessibility**: Proper contrast, alt tags, semantic HTML
- [ ] **Call-to-Action**: Clear next steps for visitors