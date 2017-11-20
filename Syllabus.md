---
title: Belt Syllabus
layout: article
published: true
overview:
logo:
teaser: 'Black_belt_syl.png'
url: 'gtjj.ca'
belticonsize: '{:height="36px" width="36px"}'
beltsyl:
- icon: "/images/belt/yellow.png"
  pdfkids: "/pdf/kids/White Belt Children 2015.pdf"
  pdfadults: "/pdf/WHITE BELT SYLLABUS 2015.pdf"
  title: "7th Kyu"
  linktxt: "White to Yellow Belt"

- icon: "/images/belt/orange.png"
  pdfkids: "/pdf/kids/Yellow Belt Chilren 2015.pdf"
  pdfadults: "/pdf/YELLOW BELT SYLLABUS 2015.pdf"
  title: "6th Kyu"
  linktxt: "Yellow to Orange Belt"

- icon: "/images/belt/green.png"
  pdfkids: "/pdf/kids/ORANGE BELT CHILDREN 2015.pdf"
  pdfadults: "/pdf/ORANGE BELT SYLLABUS 2015.pdf"
  title: "5th Kyu"
  linktxt: "Orange to Green Belt"

- icon: "/images/belt/green-stripe.png"
  pdfkids: "/pdf/kids/GREEN BELT CHILDREN 2015.pdf"
  pdfadults: "/pdf/GREEN BELT SYLLABUS 2015.pdf"
  title: "4th Kyu"
  linktxt: "Green to Green-Stripe Belt"

- icon: "/images/belt/blue.png"
  pdfkids: "/pdf/kids/GREEN STRIPE CHILDREN 2015"
  pdfadults: "/pdf/GREEN STRIPE SYLLABUS 2015.pdf"
  title: "3rd Kyu"
  linktxt: "Green-Stripe to Blue Belt"

- icon: "/images/belt/brown.png"
  pdfkids: "/pdf/kids/BLUE BELT CHILDREN 2015.pdf"
  pdfadults: "/pdf/BLUE BELT SYLLABUS 2015.pdf"
  title: "2nd Kyu"
  linktxt: "Blue to Brown Belt"

- icon: "/images/belt/brown-stripe.png"
  pdfkids: "/pdf/kids/BROWN BELT CHILDREN 2015.pdf"
  pdfadults: "/pdf/BROWN BELT SYLLABUS 2015.pdf"
  title: "1st Kyu"
  linktxt: "Brown to Brown-Stripe Belt"

- icon: "/images/belt/black.png"
  pdfkids: "/pdf/kids/JUNIOR BLACK BELT GRADING REQUIREMENTS.pdf"
  pdfadults: "/pdf/SHODAN GRADING REQUIREMENTS 2015.pdf"
  title: "Shodan"
  linktxt: "Brown-Stripe to Black Belt"

- icon: "/images/belt/black.png"
  pdfadults: "/pdf/NIDAN SYLLABUS.pdf"
  title: "Nidan"
  linktxt: "Black To 2nd Black Belt (Nidan)"

---

### Junior:
{% if page.beltsyl %}
  {% for belt in page.beltsyl %}
          {% if forloop.first %}  
| Level | Junior Syllabus|
|-------|--------|
| [![]({{belt.icon}}){{page.belticonsize}} {{belt.title}}]({{belt.pdfkids}}) | [{{belt.linktxt}}]({{belt.pdfkids}}) |
          {% else %}
  {% for pdf in belt.pdfkids %}| [![]({{belt.icon}}){{page.belticonsize}} {{belt.title}}]({{pdf}}) | [{{belt.linktxt}}]({{pdf}}) |
    {% endfor %}
    {% endif %}
    {% unless forloop.last %} {% endunless %}
  {% endfor %}
{% endif %}

### Adult:
{% if page.beltsyl %}
  {% for belt in page.beltsyl %}
          {% if forloop.first %}  
| Level | Adult Syllabus|
|-------|--------|
| [![]({{belt.icon}}){{page.belticonsize}} {{belt.title}}]({{belt.pdfadults}}) | [{{belt.linktxt}}]({{belt.pdfadults}}) |
          {% else %}
  {% for pdf in belt.pdfadults %}| [![]({{belt.icon}}){{page.belticonsize}} {{belt.title}}]({{pdf}}) | [{{belt.linktxt}}]({{pdf}}) |
    {% endfor %}
    {% endif %}
    {% unless forloop.last %} {% endunless %}
  {% endfor %}
{% endif %}

















{% comment %}
| Level | Junior Syllabus|
|-------|--------|
| [![yellow belt](/images/belt/yellow.png){:height="36px" width="36px"} 7th Kyu](/pdf/kids/White Belt Children 2015.pdf) | [White to Yellow Belt](/pdf/kids/White Belt Children 2015.pdf) |
| [![orange belt](/images/belt/orange.png){:height="36px" width="36px"} 6th Kyu](/pdf/kids/Yellow Belt Chilren 2015.pdf)  | [Yellow To Orange Belt](/pdf/kids/Yellow Belt Chilren 2015.pdf) |
| [![green belt](/images/belt/green.png){:height="36px" width="36px"} 5th Kyu](/pdf/kids/ORANGE BELT CHILDREN 2015.pdf)  | [Orange To Green Belt](/pdf/kids/ORANGE BELT CHILDREN 2015.pdf) |
| [![green stripe belt](/images/belt/green-stripe.png){:height="36px" width="36px"} 4th Kyu](/pdf/kids/GREEN BELT CHILDREN 2015.pdf)  | [Green To Green Stripe Belt](/pdf/kids/GREEN BELT CHILDREN 2015.pdf) |
| [![](/images/belt/blue.png){:height="36px" width="36px"} 3rd Kyu](/pdf/kids/GREEN STRIPE CHILDREN 2015.pdf)  | [Green Stripe To Blue Belt](/pdf/kids/GREEN STRIPE CHILDREN 2015.pdf) |
| [![](/images/belt/brown.png){:height="36px" width="36px"} 2nd Kyu](/pdf/kids/BLUE BELT CHILDREN 2015.pdf)  | [Blue To Brown Belt](/pdf/kids/BLUE BELT CHILDREN 2015.pdf) |
| [![](/images/belt/brown-stripe.png){:height="36px" width="36px"} 1st Kyu](/pdf/kids/BROWN BELT CHILDREN 2015.pdf) | [Brown To Brown-Stripe Belt](/pdf/kids/BROWN BELT CHILDREN 2015.pdf) |
| [![](/images/belt/black.png){:height="36px" width="36px"} Shodan](/pdf/kids/JUNIOR BLACK BELT GRADING REQUIREMENTS.pdf)  | [Brown-Stripe To 1st Black Belt (Shodan)](/pdf/kids/JUNIOR BLACK BELT GRADING REQUIREMENTS.pdf) |

### Adult:

| Level | Adult Syllabus
|-------|--------|
| ![](/images/belt/yellow.png){:height="36px" width="36px"} 7th Kyu | [White to Yellow Belt](/pdf/WHITE BELT SYLLABUS 2015.pdf) |
| ![](/images/belt/orange.png){:height="36px" width="36px"} 6th Kyu | [Yellow To Orange Belt](/pdf/YELLOW BELT SYLLABUS 2015.pdf) |
| ![](/images/belt/green.png){:height="36px" width="36px"} 5th Kyu | [Orange To Green Belt](/pdf/ORANGE BELT SYLLABUS 2015.pdf) |
| ![](/images/belt/green-stripe.png){:height="36px" width="36px"} 4th Kyu | [Green To Green Stripe Belt](/pdf/GREEN BELT SYLLABUS 2015.pdf) |
| ![](/images/belt/blue.png){:height="36px" width="36px"} 3rd Kyu | [Green Stripe To Blue Belt](/pdf/GREEN STRIPE SYLLABUS 2015.pdf) |
| ![](/images/belt/brown.png){:height="36px" width="36px"} 2nd Kyu | [Blue To Brown Belt](/pdf/BLUE BELT SYLLABUS 2015.pdf) |
| ![](/images/belt/brown-stripe.png){:height="36px" width="36px"} 1st Kyu | [Brown To Brown Stripe Belt](/pdf/BROWN BELT SYLLABUS 2015.pdf) |
| ![](/images/belt/black.png){:height="36px" width="36px"} Shodan | [Brown-Stripe To 1st Black Belt (Shodan)](/pdf/SHODAN GRADING REQUIREMENTS 2015.pdf) |
| ![](/images/belt/black.png){:height="36px" width="36px"} Nidan | [Black To 2nd Black Belt (Nidan)](/pdf/NIDAN SYLLABUS.pdf) |




<table>
  <thead>
    <tr>
      <th>Level</th>
      <th>Adult Syllabus</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>7th Kyu</td>
      <td><a href="/pdf/WHITE BELT SYLLABUS 2015.pdf">White to Yellow Belt</a></td>
    </tr>
    <tr>
      <td>6th Kyu</td>
      <td><a href="/pdf/YELLOW BELT SYLLABUS 2015.pdf">Yellow To Orange Belt</a></td>
    </tr>
    <tr>
      <td>5th Kyu</td>
      <td><a href="/pdf/ORANGE BELT SYLLABUS 2015.pdf">Orange To Green Belt</a></td>
    </tr>
    <tr>
      <td>4th Kyu</td>
      <td><a href="/pdf/GREEN BELT SYLLABUS 2015.pdf">Green To Green Stripe Belt</a></td>
    </tr>
    <tr>
      <td>3rd Kyu</td>
      <td><a href="/pdf/GREEN STRIPE SYLLABUS 2015.pdf">Green Stripe To Blue Belt</a></td>
    </tr>
    <tr>
      <td>2nd Kyu</td>
      <td><a href="/pdf/BLUE BELT SYLLABUS 2015.pdf">Blue To Brown Belt</a></td>
    </tr>
    <tr>
      <td>1st Kyu</td>
      <td><a href="/pdf/BROWN BELT SYLLABUS 2015.pdf">Brown To Brown Stripe Belt</a></td>
    </tr>
    <tr>
      <td>Shodan</td>
      <td><a href="/pdf/SHODAN GRADING REQUIREMENTS 2015.pdf">Brown To 1st Black Belt (Shodan)</a></td>
    </tr>
    <tr>
      <td><img src="/images/belt/black.png"> Nidan</td>
      <td><a href="/pdf/NIDAN SYLLABUS.pdf">Black To 2nd Black Belt (Nidan)</a></td>
    </tr>
  </tbody>
</table>
{% endcomment %}
