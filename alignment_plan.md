# Alignment Plan: USM Ecosystem (Skill Installer)

## 1. Metadata Alignment
- **File**: `meta.yaml`
- **Change**: Set `scope: universal`. The installer places skills in `~/.skills/`, which is the global source of truth.
- **Change**: Ensure `name: "skill-installer"` to match folder name.

## 2. Documentation Alignment
- **File**: `SKILL.md`
- **Change**: Update frontmatter `name` to `skill-installer`.
- **Change**: Reference `skill-manager` for the post-installation `meta.yaml` and `sync_skills.sh` steps.
- **NEW File**: `README.md` following the USM template.

## 3. Structure Alignment
- **NEW File**: `LICENSE.txt` (Apache 2.0).
- **Directory**: Check if `scripts/` or `references/` are needed for `clawhub` or `skillhub` integration.

## 4. GitHub Publication
- **Action**: Initialize Git, commit, and push to `ZiweiAxis/skill-installer`.
