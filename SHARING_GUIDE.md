# 📊 AGORA Content Workflow — Sharing & Update Guide

## How to Share with Your Team

### **Option 1: Google Drive (RECOMMENDED for Easy Collaboration)**

**Best for:** Team collaboration with update capabilities

**Steps:**
1. Upload `AGORA_Content_Workflow_Visual.html` to Google Drive
2. Right-click → **Open with → Chrome** (or your browser)
3. Share the link with your team with **"Viewer"** or **"Editor"** access
4. Team members can:
   - View the workflow in browser
   - Print it (Ctrl+P)
   - Take screenshots

**Link to Share:**
```
https://drive.google.com/file/d/[FILE_ID]/view
```

---

### **Option 2: Notion (BEST for Living Documentation)**

**Best for:** Living document with real-time updates and notes

**Steps:**
1. Go to **notion.so** → Create new workspace or page
2. Click **+ Embed** → **Embed Link**
3. Paste this code block:
   ```
   <iframe src="file:///[YOUR_PATH]/AGORA_Content_Workflow_Visual.html"
   width="100%" height="2000" style="border: none;"></iframe>
   ```
   OR simply upload the HTML file directly to Notion
4. Share the page link with your team
5. Team members can comment, add notes, and track updates

**Notion Advantages:**
- Real-time collaboration
- Comments & discussion
- Version history
- Database integration (track task completion)

---

### **Option 3: Simple File Sharing (Dropbox/OneDrive)**

**Steps:**
1. Upload to Dropbox/OneDrive shared folder
2. Right-click → **Share**
3. Set to **"Can view"** or **"Can edit"**
4. Send link to team
5. Team opens in browser directly

---

### **Option 4: Host on Web (GitHub Pages - FREE)**

**Best for:** Public/permanent URL that never changes

**Steps:**
1. Create GitHub account (if you don't have)
2. Create new repository: `agora-workflow`
3. Upload `AGORA_Content_Workflow_Visual.html`
4. Go to **Settings → Pages**
5. Select **main branch** as source
6. GitHub generates link: `https://[username].github.io/agora-workflow/`
7. Share this link with team — always updated!

---

## How to Update the Workflow in the Future

### **Update Method 1: Direct HTML Editing (Simple Changes)**

**For:** Changing names, priorities, owners

**Steps:**
1. Open `AGORA_Content_Workflow_Visual.html` in a text editor
2. Use `Ctrl+F` to find task details
3. Edit the owner badges or priorities
4. Save file (`Ctrl+S`)
5. Refresh browser to see changes

**Example — Changing Task Owner:**
```html
<!-- Find this: -->
<span class="owner-badge">Mridu</span>

<!-- Change to: -->
<span class="owner-badge">Mridu + New Person</span>
```

---

### **Update Method 2: Google Sheets → HTML (Structured)**

**Best for:** Managing data separately, then exporting

**Setup:**
1. Create Google Sheet with columns:
   - Task #
   - Phase
   - Task Name
   - Owner
   - Priority
2. Use **Sheet2HTML** (free tool) to convert
   - Go to: `https://www.sheet2html.com/`
   - Paste your sheet URL
   - Download as HTML
   - Copy the table into your HTML file

---

### **Update Method 3: Use a Simple Database (Airtable - Better)**

**Best for:** Team updates without coding

**Setup:**
1. Go to **airtable.com** → Create base
2. Create table with fields:
   - Task Number
   - Phase
   - Task Title
   - Owner
   - Priority
   - Notes
3. Share with team (they can edit)
4. Use **Airtable API** or export to JSON
5. Auto-generate HTML from Airtable

---

## Format Recommendation for Your Team

### **PRIMARY FORMAT: Google Sheets + HTML Display**

This gives you best of both worlds:

```
├── Google Sheets (Master Data)
│   └─ All tasks, owners, priorities
│   └─ Team can comment & collaborate
│   └─ Single source of truth
│
└── HTML File (Beautiful Display)
    └─ Visual workflow diagram
    └─ Shared on Drive/Notion
    └─ Updated when sheet changes
```

---

## Team Access Levels

| Role | Access Type | Can Edit | Use Case |
|------|------------|----------|----------|
| **Ramesh Sir** | Editor | Yes | Final approval, strategic changes |
| **Mridu** | Editor | Yes | Task ownership changes |
| **Team Members** | Viewer | No | View current workflow |
| **Anyone (Public)** | Viewer | No | Share with external partners |

---

## Step-by-Step Setup (Quick Start)

### **Option A: Google Drive (Fastest)**
1. Right-click on HTML file → **Open with → Google Drive**
2. File → **Share** → Copy link → Send to team

### **Option B: Notion (Best UX)**
1. Create Notion workspace
2. Add new page → **Upload file** (HTML)
3. Share page → Set to public or shared with team

### **Option C: GitHub (Most Professional)**
1. Create GitHub repo
2. Upload HTML file
3. Enable GitHub Pages
4. Share auto-generated URL

---

## Version Control Tips

**If you're updating frequently:**

Use GitHub with descriptive commits:
```bash
git commit -m "Update: Changed Task 4 owner to Mridu + Abhinav"
git commit -m "Feature: Added 2 new tasks to Phase 2"
git commit -m "Refactor: Reorganized Educational Repurposing tasks"
```

This keeps a history of all changes.

---

## How Team Members Can Update (No Code Skills Needed)

### **Method 1: Google Sheets Edit**
1. Open shared Google Sheet
2. Find task row
3. Edit owner/priority cell
4. Changes appear in HTML automatically (if using sync)

### **Method 2: Comment on Notion**
1. View workflow in Notion
2. Click comment button on any task
3. Type suggestion
4. You review and implement

### **Method 3: Email/Slack with Changes**
- Team sends update request
- You edit HTML file and reshare
- No system access needed for team

---

## Recommended Setup for AGORA Team

**Tier 1 - Master Data:**
- Google Sheet shared with Mridu, Ramesh Sir
- Single source of truth
- Monthly review of priorities

**Tier 2 - Visual Display:**
- GitHub Pages URL (permanent)
- Notion page (with comments)
- Google Drive backup

**Tier 3 - Team Access:**
- Shared link in Slack/Discord
- Embedded in team project management tool
- Printed/posted in office

---

## Files You Have

1. **AGORA_Content_Workflow_Visual.html** — Main display file
2. **SHARING_GUIDE.md** — This document
3. **AGORA_Content_Production_Workflow.html** — Original table version (backup)

---

## Quick Commands

**To refresh after edits:**
- Browser: `F5` or `Ctrl+R`
- If using Google Drive: File auto-saves

**To print workflow:**
- Browser: `Ctrl+P` → Save as PDF
- Looks great in B&W and color

**To share with external partner:**
- GitHub public link (no authentication needed)
- Or download PDF and email

---

## Questions?

- **Editing HTML:** Open file in any text editor (VS Code, Notepad++)
- **Sharing links:** Most platforms auto-save & sync
- **Mobile view:** Responsive design works on all devices
- **Printing:** Use browser Print function (Ctrl+P)

---

## Next Steps

1. ✅ Choose sharing method (Google Sheets recommended)
2. ✅ Upload HTML file to chosen platform
3. ✅ Share link with your team
4. ✅ Create backup in multiple locations
5. ✅ Brief team on how to provide updates

**Your workflow is ready to use!** 🚀
