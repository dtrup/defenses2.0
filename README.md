# 📚 Book-Base: LLM-Powered Book Writing System

**The ultimate fork-and-write template for creating professional books with AI assistance.**

Transform your book idea into a complete manuscript using Claude Code's command system. No technical skills required - just fork, customize, and write.

## 🚀 Quick Start (5 Minutes)

### Fork This Repository
1. **Click "Fork"** in the top-right corner of this GitHub page
2. **Choose your account** as the destination
3. **Clone your fork**: `git clone https://github.com/YOUR-USERNAME/book-base.git`
4. **Rename the directory**: `mv book-base your-book-title`
5. **Enter the directory**: `cd your-book-title`

### Initialize Your Book
6. **Open in Claude Code** or your preferred LLM interface  
7. **Run `/setupBook`** - customize for your book
8. **Edit `TOC.md`** - add your chapter structure
9. **Run `/tocToChapters`** - generate chapter files
10. **Start writing** with `/prepareChapter 1`

## ⚡ The Writing Workflow

### Phase 1: Project Setup
```
/setupBook           → Customize book details and preferences
Edit TOC.md          → Define your chapter structure  
/tocToChapters       → Generate all chapter files
/bookStatus          → Verify everything looks good
```

### Phase 2: Chapter Creation (Repeat for each chapter)
```
/prepareChapter N    → Brainstorm ideas and research
/writeChapter N      → Write complete chapter content  
/styleCheck N        → Review for quality and consistency
/completeChapter N   → Finalize and mark complete
```

### Phase 3: Book Refinement
```
/thematicAnalysis    → Check consistency across chapters
/findGaps           → Identify weak areas or missing content
/revisionSweep      → Systematic improvement pass
/finalReview        → Publication readiness check
```

## 🎯 What Makes This Special

### ✅ Complete Workflow
From initial idea to publication-ready manuscript with guided steps.

### ✅ LLM-Optimized  
Every command designed specifically for AI writing assistance.

### ✅ Quality-Focused
Built-in style checking, consistency validation, and progress tracking.

### ✅ Flexible Structure
Works for any non-fiction book: business, memoir, technical, academic.

### ✅ Professional Output
Generates publication-ready content with proper structure and citations.

## 📋 Command Reference

| Command | Purpose | When to Use |
|---------|---------|-------------|
| `/setupBook` | Initialize project | After forking |
| `/tocToChapters` | Generate chapter files | After finalizing TOC |
| `/prepareChapter N` | Brainstorm & research | Before writing each chapter |
| `/writeChapter N` | Write chapter content | After brainstorming |
| `/styleCheck N` | Quality review | After writing |
| `/completeChapter N` | Mark chapter done | When satisfied with chapter |
| `/bookStatus` | Progress dashboard | Anytime for overview |
| `/thematicAnalysis` | Cross-chapter review | Mid-project and near end |
| `/findGaps` | Identify weak areas | When feeling stuck |
| `/revisionSweep` | Systematic improvements | Before final review |
| `/finalReview` | Publication prep | When book is complete |

## 🗂️ File Structure

```
your-book/
├── book.config.json       # Project configuration
├── TOC.md                 # Table of contents
├── style-guide.md         # Writing guidelines
├── BOOK_SUMMARY.md        # Progress dashboard
├── .claude/commands/      # Workflow commands (don't modify)
├── chapters/              # Final chapter content
├── brainstorms/           # Pre-writing idea development  
├── outlines/              # Chapter structure planning
└── .gitignore            # Git ignore patterns
```

## 🎨 Customization

### Book Types Supported
- **Business/Leadership**: Practical frameworks with case studies
- **Memoir/Personal**: Narrative non-fiction with reflection  
- **Technical**: Complex topics made accessible
- **Academic**: Rigorous analysis with broader appeal
- **Self-Help**: Actionable advice with supporting research

### Style Adaptation
Edit `style-guide.md` to match your:
- Voice (authoritative, conversational, academic)
- Tone (serious, witty, warm, analytical)  
- Technical level (beginner, intermediate, expert)
- Example style (stories, case studies, data, analogies)

## 💡 Pro Tips

### For Best Results
- **Trust the process**: Follow brainstorm → outline → write → review
- **Use research phase**: Let the LLM do web research during brainstorming
- **Check consistency**: Run `/thematicAnalysis` every 3-4 chapters
- **Track progress**: `/bookStatus` shows you exactly where you stand

### Common Workflows
- **Fast draft**: Skip outlines, go brainstorm → write → revise
- **Quality-first**: Brainstorm → outline → write → style check → revise
- **Research-heavy**: Extended brainstorming with multiple research passes

## 🆘 Getting Help

### If Commands Don't Work
1. Check you're in the project root directory
2. Verify required files exist (TOC.md, book.config.json)
3. Try `/bookStatus` to see project health

### If You Get Stuck
- **Writer's block**: Try `/findGaps` to identify what's missing
- **Quality concerns**: Run `/styleCheck` on problem chapters  
- **Structure issues**: Use `/thematicAnalysis` to see the big picture

---

## 🌟 Why This Works

**Traditional book writing** is overwhelming: blank page, no structure, inconsistent progress.

**Book-Base + LLM** gives you:
- Clear next steps at every stage
- Consistent quality and voice
- Progress tracking and motivation
- Professional workflows without complexity

**Result**: You focus on ideas and insights. The system handles structure, consistency, and process.

---

## 🌐 Publishing to GitHub Pages

### One-Time Setup
1. **Enable GitHub Pages** in your repository:
   - Go to Settings → Pages
   - Set Source to "Deploy from a branch"
   - Choose "main branch" and "/ (root)"
   - Save settings

2. **Configure your repository**:
   - Make sure your repo is public (for free GitHub Pages)
   - Your book will be available at: `https://YOUR-USERNAME.github.io/your-book-title/`

### Publishing Process
- **Automatic**: Every time you run `/completeChapter N`, the index.md is updated
- **Manual**: Edit `index.md` to add chapter links and update progress
- **Push changes**: `git add -A && git commit -m "Update book progress" && git push`

### Features You Get
- 📖 **Live book website** with table of contents
- 💬 **Reader comments** via Hypothesis on every chapter  
- 🔗 **Shareable links** to individual chapters
- 📊 **Progress tracking** visible to readers
- 🔄 **Automatic updates** when you push new content

---

*Ready to write your book? Fork this repo and run `/setupBook` to begin.*
