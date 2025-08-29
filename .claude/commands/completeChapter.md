---
description: Finalize chapter and update project progress
allowed-tools: Read, Write, Edit, Bash
---

# Complete Chapter $1: Finalize and Publish

Mark chapter as complete and update all project tracking.

## Your Task

1. **Final quality check**:
   - Read @chapters/chapter-$1.md to verify it's complete
   - Count words and verify meets targets in @book.config.json
   - Check for any [TODO], [RESEARCH], or [REVISE] markers
   - Ensure smooth transitions into and out of chapter

2. **Update progress tracking**:
   - Update chapter status to "✅ Complete" in @chapters/chapter-$1.md
   - Add final word count and completion date  
   - Update @BOOK_SUMMARY.md with:
     - Chapter marked as complete
     - Updated word count totals
     - Brief chapter summary
     - Overall book progress percentage

3. **Prepare for publication** (if configured):
   - Add hypothesis commenting script to chapter end if github_pages enabled in config
   - Create/update index.md with hyperlinked TOC if needed
   - Stage files for git if repository exists

4. **Report completion**:
   - Show chapter stats (word count, completion date)
   - Display updated book progress (X of Y chapters, total words)
   - Suggest logical next steps (next chapter to work on, or publication prep if book is complete)

Focus on making this chapter truly publication-ready.