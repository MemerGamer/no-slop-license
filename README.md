### Complying With NSL-Licensed Projects

[![License: NSL-1.0](https://img.shields.io/badge/License-NSL%201.0-blue.svg)](https://github.com/[your-username]/no-slop-license)

If you're building a commercial product using NSL-licensed code:

1. **Review and understand all code** (AI-generated or not)
2. **If you used >=50% AI for new features:**
   - Copy [`TEMPLATE-AI_USAGE.md`](./TEMPLATE-AI_USAGE.md)
   - Fill it out honestly
   - Include attribution to the original project
3. **If you used >=70% AI:**
   - Don't distribute commercially, OR
   - Get explicit permission from the copyright holder

## Examples

### Compliant Usage

**Scenario:** Building a commercial SaaS on top of an NSL-licensed library

- Used AI to generate 60% of new API endpoints
- Human architects designed the system
- All code reviewed and tested by qualified developers
- Included `AI_USAGE.md` with metrics
- Added attribution in the app's "About" page

**Result:** Fully compliant, no issues.

---

### Violation

**Scenario:** "Competitor" product

- Downloaded NSL-licensed project
- Prompted: "Rebrand this, add a dashboard, make it blue"
- 85% of changes were unmodified AI output
- No understanding of internals
- Sold as a new product with no attribution

**Result:** License violation, must cease commercial distribution.

---

### No Restrictions

**Scenario:** Personal project or open-source contribution

- Used AI for 100% of code generation
- No commercial purpose

**Result:** No restrictions at all. Go wild!

## Why This Matters

**For creators:**

- Your work gets credit even when extended commercially
- Prevents low-effort exploitation
- Encourages meaningful contributions
- Still allows smart AI usage

**For users:**

- Clear rules for commercial AI usage
- Doesn't ban AI tools, just requires thoughtfulness
- More permissive than GPL for non-commercial use

**For the ecosystem:**

- Raises the bar on commercial derivatives
- Maintains code quality standards
- Encourages understanding over vibecoding

## FAQ

**Q: Is this "open source"?**  
A: It's source-available with commercial restrictions, so likely not OSI-approved. It's closer to Fair Source or Commons Clause but with specific AI provisions.

**Q: How do you measure the 50%/70% thresholds?**  
A: By significant lines of code or functional contribution. It's a good-faith standard - obvious vibecoding is obvious.

**Q: What counts as "AI-generated"?**  
A: Code where AI produced the implementation from prompts without substantial human redesign (>40% changes). See full definitions in the license.

**Q: Can I use GitHub Copilot?**  
A: Yes! Autocomplete, code completion, and smart assistance don't count toward the AI percentage.

**Q: What if I disagree about the percentage?**  
A: The license assumes good faith. If there's a dispute, the commercial distributor has the burden to demonstrate reasonable human authorship.

**Q: Can I dual-license my project (NSL + MIT)?**  
A: Yes! You could offer NSL for free use and MIT (or a commercial license) for those who want zero restrictions.

## Status

**This license is currently in DRAFT status**

We're seeking:

- Community feedback on terms
- Legal review from IP lawyers
- Adoption by early projects
- SPDX identifier registration

**Want to help?** Open an issue or PR!

## Contributing

This license is a community effort. We welcome:

- Feedback on clarity and enforceability
- Legal expertise and review
- Real-world use cases and edge cases
- Documentation improvements
- Translation to other languages
  Please open issues and related PRs to contribute!

## Projects Using NSL

_Be the first!_ Open a PR to add your project here.

---

- No-Slop License itself :), see [AI_USAGE](./AI_USAGE.md)

## License

This license text itself is released under CC0 (public domain).  
Use it, modify it, fork it - no attribution required.

## Contact

- Issues: [GitHub Issues](../../issues)
- Discussions: [GitHub Discussions](../../discussions)
- Created by: [@MemerGamer](https://github.com/MemerGamer)

---

**Stop the slop. Build with intention**
