# Microsoft Office 365 Drift Detection
## What is configuration drift, how to detect and manage it without expensive tools
### Tags: SharePoint Online, Teams, Exchange, M365
If you manage a Microsoft 365 environment, you know how much time goes into getting your configuration right — balancing usability, security, and compliance. But here’s the problem: even the best-configured environment won’t stay that way forever.

Configuration drift happens when your settings change without you planning for it. Maybe someone in IT makes a quick fix to solve a problem. Maybe an admin tweaks a setting for a user without thinking of the bigger picture. Or maybe someone with good intentions just doesn’t understand the impact of their changes. Whatever the cause, drift can turn a secure setup into a risky mess without you even noticing.

## What is Configuration Drift?

Configuration drift is any change in your M365 settings that doesn’t match your baseline — the “golden standard” you originally set. 

These changes can be:
- Planned but Forgotten: Approved changes that never got documented.
- Unplanned and Reactive: Quick fixes that seemed harmless.
- Malicious or Unauthorized: Changes that someone shouldn’t have made.

## Why Drift is a Problem

- Compliance Risks: You could fail an audit because your settings don’t match your policy.
- Security Gaps: Critical settings (like MFA or external sharing) could be weakened without anyone realizing.
- Operational Problems: Unplanned changes can cause unpredictable issues.

## How to Stop Drift: Start with a Standard
The first step is knowing what “correct” looks like. There are a few good places to start:

### CISA (Secure Cloud Business Applications - SCuBA)
- Solid, well-documented standards.
- Tool: [SCuBAGear](https://github.com/cisagov/ScubaGear), which you can automate for easy checks.
- [CISA SCuBA Project Documentation](https://www.cisa.gov/resources-tools/services/secure-cloud-business-applications-scuba-project)

### NCSC (UK Public Sector Guidance)
- UK-focused, good for government or public sector setups.
- [NCSC M365 Security Guidance](https://www.microsoft.com/en-gb/industry/blog/cross-industry/2024/02/28/updated-office-365-security-and-compliance-guidance-for-the-uk-public-sector/)

### CIS (Center for Internet Security)
- Widely recognized, with a detailed guide you can actually use.
- [CIS M365 Benchmark](https://www.cisecurity.org/benchmark/microsoft_365)

## Tools to Detect Drift (Free vs. Paid)
### Free Tools (Manual Setup, but Full Control)
- [Maester](https://maester.dev): Prebuilt security tests for M365.
- [SCuBAGear](https://github.com/cisagov/ScubaGear): Direct CISA standards in a free tool.
- [Microsoft365DSC](https://microsoft365dsc.com/): A bit more complex but very customizable.

### Paid Tools (Easy Setup, but Costly)
- [Simeon Cloud](https://www.simeoncloud.com/): Multi-tenant management, automated corrections.
- [Inforcer](https://www.inforcer.com/platform?utm_term=multi-tenant%20management%20for%20microsoft%20365&utm_campaign=Branded+Traffic&utm_source=adwords&utm_medium=ppc&hsa_acc=6508419029&hsa_cam=22137321577&hsa_grp=173868275935&hsa_ad=729287627697&hsa_src=g&hsa_tgt=kwd-2338776488823&hsa_kw=multi-tenant%20management%20for%20microsoft%20365&hsa_mt=b&hsa_net=adwords&hsa_ver=3&gad_source=1&gad_campaignid=22137321577&gbraid=0AAAAAo8xqkpFpIe5HEFgWm_btfTN4m2ZP&gclid=EAIaIQobChMIreyc3eqijQMVxaaDBx1F2DjbEAMYAiAAEgJTOfD_BwE): More automation and policy control.

## Getting Started: Build a Simple Drift Detection Process
1. Define Your Baseline: Figure out the settings that matter (like Conditional Access, External Sharing, MFA).
2. Pick Your Tool: If you’re new, start with a free tool like Maester. If you want automation, look at paid options.
3. Set a Review Schedule: Check monthly for low-risk environments, weekly for high-risk.

## Final Thoughts
Configuration drift is going to happen. The question is whether you’ll notice before it becomes a problem. Start with a free tool, learn how it works, and upgrade to a paid option if you need to. But whatever you do, don’t ignore drift — it’s the easiest way to lose control of your Microsoft 365 environment.