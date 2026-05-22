---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    id: about-me
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Curriculum Vitae
        url: "uploads/CV Amdad Ahmed Awsaf.pdf"
      headings:
        about: 'About Me'
        education: 'Education'
        interests: 'Research Interests'
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: 'Research Agenda'
      subtitle: 'Equity-centered STEM education research'
      text: |-
        My research agenda focuses on how learners develop STEM identities and how educational environments can support access, engagement, and persistence. I study both formal and informal STEM learning contexts, with attention to engineering education, youth identity development, and equitable learning opportunities.

        I use quantitative, qualitative, and mixed-method approaches to examine how personal, educational, and societal identities shape STEM participation.

        This site highlights my research interests, publications, conference presentations, teaching, collaborations, awards, and contact information.
    design:
      columns: '1'
  - block: collection
    id: research-publications
    content:
      title: Selected Publications
      text: 'Use this section for your strongest publications, working papers, manuscripts, and conference papers.'
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Publication List
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    id: teaching
    content:
      title: Teaching
      subtitle: 'Courses, mentoring, and instructional experience'
      text: |-
        Add the courses you have taught or supported here. For each item, include the course title, your role, institution, semester, and a short note about your teaching responsibilities.

        **Suggested format**

        - Course title, role, institution, semester/year
        - Guest lecture or workshop title, audience, date
        - Mentoring or supervision experience
        - Teaching philosophy or inclusive teaching approach
    design:
      columns: '1'
  - block: collection
    id: conferences
    content:
      title: Conferences & Presentations
      text: 'Use this section for conference presentations, invited talks, workshops, posters, and symposium participation.'
      filters:
        folders:
          - events
    design:
      view: card
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 10
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: collection
    id: project-affiliations
    content:
      title: Project Affiliations
      text: 'Feature research teams, grants, collaborations, labs, and applied projects here.'
      filters:
        folders:
          - projects
    design:
      view: card
      columns: 2
  - block: markdown
    id: awards-honors
    content:
      title: Awards & Honors
      subtitle: 'Recognition, fellowships, grants, and academic honors'
      text: |-
        Add awards, scholarships, fellowships, travel grants, paper awards, and university recognitions here.

        **Suggested format**

        - Award name, organization, year
        - Fellowship or scholarship, organization, year
        - Travel award or research grant, organization, year
    design:
      columns: '1'
  - block: markdown
    id: courses
    content:
      title: Courses
      subtitle: 'Teaching and coursework highlights'
      text: |-
        Use this section to highlight courses taught, courses assisted, workshops led, or selected doctoral coursework relevant to your academic profile.

        You can later replace this section with a full course list or teaching portfolio page.
    design:
      columns: '1'
  - block: markdown
    id: contact
    content:
      title: Contact
      subtitle: 'I welcome conversations about STEM education, engineering identity, and informal STEM learning.'
      text: |-
        Email: [aawsa001@gmail.com](mailto:aawsa001@gmail.com)

        LinkedIn: [linkedin.com/in/awsaffiu](https://www.linkedin.com/in/awsaffiu/)

        Google Scholar: [Scholar profile](https://scholar.google.com/citations?user=kZqcwHEAAAAJ&hl=en)

        ORCID: [0009-0000-6943-4526](https://orcid.org/0009-0000-6943-4526)
    design:
      columns: '1'
  - block: cta-card
    demo: true # Only display this section in the HugoBlox Kit demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by HugoBlox Kit - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/kit" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/kit on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
