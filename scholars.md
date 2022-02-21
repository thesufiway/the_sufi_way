---
title: Scholars
layout: collection
permalink: /scholars/
collection: scholars
entries_layout: grid
classes: wide
---

We are an independent platform planning and executing these outdoor events and
programs. We invite expert Islamic scholars as guest speakers from across India, who
are traditionally trained and also well connected with the masses. The two scholars who
whole-heartedly supported the concept and accepted the invitation to our first event
hail from North India and associated with *Jamia Arifia* (a renowned Islamic
educational institution in U.P. India, known for its quality education, research works,
publications and it also shares a MoU with Al-Azhar University, Cairo, Egypt). Below is
the short profile of the Scholars.The list will continue to grow… Insha’Allah!

{% for staff_member in site.staff_members %}
  <h2>
    <a href="{{ staff_member.url }}">
      {{ staff_member.name }} - {{ staff_member.position }}
    </a>
  </h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}