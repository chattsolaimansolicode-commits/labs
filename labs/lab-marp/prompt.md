# Create a Skill: Solicode Marp Presentation

## Objective

Create a reusable Skill named `solicode-marp-presentation`.

This Skill will help me create professional Marp presentations for Solicode school projects and labs.

The Skill must follow the teacher's requirements and use a simple, clean, professional presentation style.

## 1. Presentation Structure

Every presentation must follow these 7 required sections:

1. Page de garde
2. Introduction
3. Besoin
4. Analyse
5. Conception
6. Réalisation
7. Conclusion

Adapt the content to the project or lab provided by the user.

Do not add unnecessary sections or information.

Follow the user's reference presentation whenever one is provided.

## 2. Marp Configuration

Every presentation must use Markdown and Marp.

Start with this configuration:

```yaml
---
marp: true
theme: default
size: 16:9
paginate: true
---
```

Use:
- `---` to separate slides.
- Markdown headings, lists, bold text and images.
- Simple slide layouts.
- Clear and readable content.

## 3. Design Rules

The presentation must be:

- Simple and professional.
- 100% based on the default Marp theme.
- Easy to read and understand.
- Not overloaded with text.
- Consistent from the first slide to the last.

Avoid:
- Complex CSS.
- Unnecessary animations.
- Excessive colors.
- Complicated layouts.
- Decorative elements that do not add value.

Do not create a custom theme unless the user explicitly requests it.

## 4. Logos and Images

For Solicode presentations, keep these exact logo filenames when they are provided:

```markdown
![Solicode](logo_solicode.png)
![OFPPT](ofppt_logo.png)
```

Never rename or invent image filenames.

Use images only when they are relevant to the project.

## 5. Presenter Notes

This is a mandatory requirement.

Every slide must contain one short presenter note using an HTML comment.

Example:

```markdown
<!--
Je vais présenter le contexte général de mon projet.
-->
```

Rules:
- Add notes to every slide.
- Write notes in simple French.
- Use only one short sentence per slide.
- The note must explain what the presenter should say about that slide.
- Do not make notes long or complicated.
- Keep notes inside the Markdown source, not as visible slide content.

## 6. Content Accuracy

Respect the information provided by the user.

Important rules:

- Never invent project features.
- Never claim that a feature is completed if it is only planned.
- Clearly distinguish between implemented features and planned features.
- Use the real technologies provided by the user.
- Use the actual entities, attributes and relationships when available.
- If important information is missing, ask the user instead of inventing it.
- Use simple and correct French for the presentation.

## 7. Required Marp Techniques

When the assignment requires them, help the user apply these Marp techniques:

- Install and activate the Marp VS Code extension.
- Create slides using Markdown and `---`.
- Format text and lists.
- Insert images, logos and backgrounds.
- Use available themes: `default`, `gaia`, `uncover`.
- Use directives such as pagination, header, footer, background and color.
- Use custom CSS only when required.
- Apply CSS classes to slides when required.
- Add presenter notes.
- Create progressive lists when appropriate.
- Export presentations to PDF, HTML and PPTX.

Do not force every technique into every presentation. Apply only what is relevant to the assignment.

## 8. GitHub and Deliverables

When the assignment requires a GitHub submission:

- Keep the presentation source file in Markdown (`.md`).
- Include the necessary images and assets.
- Verify that image paths are correct.
- Check the slides in VS Code using Marp.


## 9. Workflow

Before creating a presentation:

1. Read the teacher's instructions.
2. Read the user's project or lab information.
3. Analyze any reference presentation provided.
4. Identify the required sections.
5. Identify the actual project information.
6. Ask about missing essential information.
7. Create the complete Marp Markdown presentation.
8. Add one short presenter note to every slide.
9. Check that the presentation follows all requirements.

## 10. Final Rules

- Follow the teacher's instructions first.
- Follow the user's reference presentation when provided.
- Do not add unnecessary sections.
- Do not invent information.
- Keep the design simple.
- Keep the French A1
- Make the presentation ready to open in VS Code with Marp.

The goal is to create presentations that are correct, simple, professional and ready for school evaluation.