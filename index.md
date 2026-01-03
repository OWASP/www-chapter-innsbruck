---

layout: col-sidebar
title: OWASP Innsbruck
tags: Innsbruck
level: 3
region: Europe
country: Austria

---

![logo](img/Owasp_Tirol_Logo%20Berge.jpg)

# 📅 Upcoming Events

## ☕ Informal Networking for the Local Cyber Security Community

<!-- <div style="background-color: #fff7f0; border-left: 4px solid #ff6b35; padding: 20px; margin-bottom: 20px;"> -->

- **📅 When:** Bi-Monthly, next on Wednesday 14th January 2026
- **🕐 Time:** 18:30 onwards
- **📍 Location:** We've reserved a space at "Wohnzimmer" Fürstenweg 5, 6020 Innsbruck
- **🗣️ Language:** [German and English]

Casual meetup for people interested in cybersecurity in Innsbruck! No formal presentations—just good conversations, knowledge sharing, and networking over coffee or drinks.

**Who should come?**

- Security professionals
- Developers interested in application security
- Students exploring cybersecurity
- Anyone curious about it and want to meet new people

Drop by and looking forward to meet you!

<!-- </div> -->

## 🎤 Next OWASP Chapter Meeting - February 5, 2026

<div style="background-color: #e8f4f8; border-left: 4px solid #2196F3; padding: 20px; margin-bottom: 25px;">

**Date:** Thursday, February 5, 2026  
**Time:** 17:00 - 18:30  
**Location:** Wirtschaftskammer Tirol, Wilhelm-Greil-Str 7, 6020 Innsbruck  
**Language:** This time, the entire meet-up will be in English!

**[Register Here →](http://veranstaltung.wktirol.at/28037)**

#### Agenda

- 17:00 - Welcome to OWASP Innsbruck + Updates - *Sven Schleier*
- 17:15 - **Semgrep: Custom Rule Writing** - *Will Douglas*
- 18:00 - **A Whirlwind Tour of Software Vulnerabilities** - *Matthias Gander*
- 18:20 - Networking - Snacks and Drinks

</div>




<div style="background-color: #f0f7ff; border-left: 4px solid #0066cc; padding: 20px; margin-bottom: 20px;">

**📅 Date:** Thursday, February 5, 2026  
**🕐 Time:** 17:00 - 18:30  
**📍 Location:** Wirtschaftskammer Tirol, Wilhelm-Greil-Str 7, 6020 Innsbruck  
**🗣️ Language:** This time, the entire meet-up will be in English!  

**[📝 Register Here →](http://veranstaltung.wktirol.at/28037)**

### Agenda

- 17:00 - Welcome to OWASP Innsbruck + Updates - *Sven Schleier*
- 17:15 - **Semgrep: Custom Rule Writing** - *Will Douglas*
- 18:00 - **A Whirlwind Tour of Software Vulnerabilities** - *Matthias Gander*
- 18:20 - Networking, Snacks & Drinks 🍕🍺

### Details to talks

#### Talk: Semgrep: An introduction to custom rule writing by Will Douglas

**Abstract**:

Semgrep is a static analysis tool used for scanning source code to identify potential vulnerabilities but also can be used for other cases that might be of interest to a developer such as code correctness. There is both an enterprise and a free and open-source version of Semgrep but this presentation will focus on custom rule writing for the free version. The custom rules afforded by Semgrep allows practitioners to identify bugs and continually adapt those rules based their tested reliability through triaging reported results along with information gleaned from other security activities.

**Bio Will Douglas**:

Will Douglas is the Team Leader for Product Security Engineering at MED-EL focusing on the security of both medical and non-medical products throughout their development lifecycle prior to release. He initially started out working in different IT and web development positions before transitioning to cybersecurity in early 2015. His introduction to the professional cybersecurity space was focused primarily on offensive security as a Security Consultant for Cigital, a company which was later acquired by Synopsys. In 2021 he moved from the United States to Austria to join MED-EL's Product Security team where he holds his current position.

#### Talk: A Whirlwind Tour of Software Vulnerabilities (a gentle introduction) by Matthias Gander

**Abstract**:

Software is the foundation of everything from critical infrastructure to daily conveniences. But what happens when that foundation has cracks? This lightning talk provides a high-level introduction to the world of software vulnerabilities. We will move quickly to establish the core concepts and motivations behind vulnerabilities, explore common types of weaknesses that plague modern systems, and demystify how we find, enumerate (like CVE), and rate (like CVSS) these critical flaws. This session is perfect for those new to the field or seasoned experts looking for a concise refresher on the fundamentals.

**Bio Matthias Gander**:

Matthias Gander is a senior Information Security Manager for Swarovski with a background in computer science. He brings a diverse perspective from his past roles, which include penetration testing, security consulting, and lecturing at the university of Innsbruck. Today, he focuses on the strategic side of security, e.g., building security programs, writing policies, and having endless discussions about managing risk.

</div>

---

## Welcome

Welcome to the OWASP Innsbruck Chapter, your regional chapter in Tyrol, Austria.

**What is OWASP?**

It is a global community that has provided knowledge, tools and standards as open source for over 20 years to help develop more secure software and applications. The spectrum ranges from web and mobile apps to generative AI and secure software development in general.

Whether you are a developer, a cybersecurity professional or someone who is simply interested in software and application security, OWASP Innsbruck provides a platform for learning, knowledge sharing and networking. Through a variety of events and initiatives, we strive to create an inclusive environment where everyone can contribute, learn and grow.

## OWASP Innsbruck Chapter

OWASP Innsbruck was formed in September 2025 by Bettina and Sven Schleier.

## Support - WKO Tyrol

We would like to sincerely thank the Wirtschaftskammer (WKO) Tyrol for kindly providing their facilities and support, as well as Peter Stelzhammer, speaker of the IT Security Experts Group Tyrol of the WKO for his support.

<script>
// Add clickable link icons to all headings
document.addEventListener('DOMContentLoaded', function() {
  const headings = document.querySelectorAll('h2, h3, h4, h5, h6');
  
  headings.forEach(heading => {
    if (!heading.id) return; // Skip if no ID
    
    // Create the link icon
    const link = document.createElement('a');
    link.href = '#' + heading.id;
    link.innerHTML = ' 🔗';
    link.className = 'heading-anchor';
    link.title = 'Copy link to clipboard';
    link.style.textDecoration = 'none';
    link.style.opacity = '0';
    link.style.transition = 'opacity 0.2s';
    link.style.marginLeft = '8px';
    link.style.fontSize = '0.8em';
    
    // Copy to clipboard when clicked
    link.addEventListener('click', function(e) {
      e.preventDefault();
      const url = window.location.href.split('#')[0] + '#' + heading.id;
      
      navigator.clipboard.writeText(url).then(() => {
        link.innerHTML = ' ✓';
        setTimeout(() => link.innerHTML = ' 🔗', 1500);
      }).catch(() => {
        // Fallback if clipboard fails
        alert('Link: ' + url);
      });
    });
    
    // Show icon on hover
    heading.addEventListener('mouseenter', () => link.style.opacity = '0.5');
    heading.addEventListener('mouseleave', () => link.style.opacity = '0');
    link.addEventListener('mouseenter', () => link.style.opacity = '1');
    
    heading.appendChild(link);
  });
});
</script>
