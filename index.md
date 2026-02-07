---

layout: col-sidebar
title: OWASP Innsbruck
tags: Innsbruck
level: 3
region: Europe
country: Austria

---

![logo](img/Owasp_Tirol_Logo%20Berge.jpg)


# Welcome 

Welcome to the OWASP Innsbruck Chapter, your regional chapter in Tyrol, Austria.

**What is OWASP?**

It is a global community that has provided knowledge, tools and standards as open source for 25 years to help develop more secure software and applications. The spectrum ranges from web and mobile apps to generative AI and secure software development in general.

Whether you are a developer, a cybersecurity professional or someone who is simply interested in software and application security, OWASP Innsbruck provides a platform for learning, knowledge sharing and networking. Through a variety of events and initiatives, we strive to create an inclusive environment where everyone can contribute, learn and grow.

## OWASP Innsbruck Chapter

OWASP Innsbruck was formed in September 2025 by Bettina and Sven Schleier.

## Support - WKO Tyrol

We would like to sincerely thank the Wirtschaftskammer (WKO) Tyrol for kindly providing their facilities and support, as well as Peter Stelzhammer, speaker of the IT Security Experts Group Tyrol of the WKO for his support.

# 📅 Upcoming Events

## ☕ Informal Networking for the Local Cyber Security Community

<div style="background-color: #fff7f0; border-left: 4px solid #ff6b35; padding: 20px; margin-bottom: 20px;">

<p><strong>📅 When:</strong> Bi-Monthly, next one will be in March and will be announced here soon</p>
<p><strong>🕐 Time:</strong> 18:30 onwards</p>
<p><strong>📍 Location:</strong> We've reserved a space at "Wohnzimmer" Fürstenweg 5, 6020 Innsbruck</p>
<p><strong>🗣️ Language:</strong> German and English</p>

<p>Casual meetup for people interested in cybersecurity in Innsbruck! No formal presentations—just good conversations, knowledge sharing, and networking over coffee or drinks.</p>

<p><strong>Who should come?</strong></p>
<ul>
  <li>Security professionals</li>
  <li>Developers interested in application security</li>
  <li>Students exploring cybersecurity</li>
  <li>Anyone curious about it and want to meet new people</li>
</ul>

<p>We are looking forward to meet you!</p>

</div>


## 🎤 4th OWASP Chapter Meeting - Thursday 9th April, 2026

<div style="background-color: #f0f7ff; border-left: 4px solid #0066cc; padding: 20px; margin-bottom: 20px;">

<p><strong>📅 When:</strong> Bi-monthly, next on Thursday, 9th April, 2026</p>
<p><strong>🕐 Time:</strong> 17:00 - 18:30</p>
<p><strong>📍 Location:</strong> Wirtschaftskammer Tirol, Wilhelm-Greil-Str 7, 6020 Innsbruck</p>
<p><strong>🗣️ Language:</strong> This time, the entire meet-up will be in English!</p>

<!-- <p><strong><a href="http://veranstaltung.wktirol.at/28037">📝 Register Here →</a></strong></p> -->

<h3>Agenda</h3>
<ul>
  <li>17:00 - Welcome to OWASP Innsbruck + Updates - <em>Sven Schleier</em></li>
  <li>17:15 - <strong>First talk</strong> - <em>TBD</em></li>
  <li>18:00 - <strong>Second talk</strong> - <em>TBD</em></li>
  <li>18:20 - Networking &amp; Drinks 🍺</li>
</ul>

<h3>Details to talks</h3>

<h4>TBD</h4>

</div>

<img referrerpolicy="no-referrer-when-downgrade" src="https://static.scarf.sh/a.png?x-pxid=d801338d-6e9c-4dfe-ba33-7b66389ff341" />

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
