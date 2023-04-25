---
# Leave the homepage title empty to use the site title
title:
date: 2023-04-23
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Senior Research Associate
          company: Veris Insights
          company_url: 'https://verisinsights.com/'
          company_logo: org-gc
          location: Washington, D.C. (Remote)
          date_start: '2022-01-31'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Data analysis
              * Creating research deliverables
              * Managing projects
        - title: Instructional Aide
          company: San Luis Coastal Unified School District
          company_url: ''
          company_logo: org-x
          location: San Luis Obispo, California
          date_start: '2022-08-25'
          date_end: ''
          description: Provide socio-emotional, behavioral, and academic support in a kindergarten classroom 
    design:
      columns: '2'
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: Beginner
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: Beginner
          icon: chart-line
          icon_pack: fas
        - name: Project Management
          description: Intermediate
          icon: clipboard
          icon_pack: fas
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards & Scholarship'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: ''
          date_start: '2021-01-01'
          description: ''
          organization: University of Utah
          organization_url: https://our.utah.edu/
          title: Undergraduate Research Scholar Designation
          url: 'https://our.utah.edu/undergraduate-research-scholar-designation/'
        - date_end: ''
          date_start: '2021-01-01'
          description: ''
          organization: University of Utah
          organization_url: https://our.utah.edu/
          title: Francis Family Foundation Undergraduate Research Scholarship
          url: 'https://our.utah.edu/research-scholarship-opportunities/scholarship-opportunities/francis-fund/'
        - date_end: ''
          date_start: '2020-08-01'
          description: ''
          organization: University of Utah
          organization_url: https://csbs.utah.edu/
          title: Aimee LaPine Memorial Scholarship
          url: 'https://csbs.utah.edu/students/scholarships/database.php'
        - date_end: '2020-08-01'
          date_start: '2020-01-01'
          description: ''
          organization: University of Utah
          organization_url: https://our.utah.edu/
          title: Undergraduate Research Opportunities Program Scholar
          url: 'https://our.utah.edu/research-scholarship-opportunities/urop/'
        - date_end: '2018-08-01'
          date_start: '2020-01-01'
          description: ''
          organization: University of Utah
          organization_url: https://csbs.utah.edu/
          title: College of Social & Behavioral Sciences Solutions Scholar
          url: 'https://csbs.utah.edu/students/solutions-scholars.php'
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: ''
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Projects
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to send an email for further information about myself, the content you've seen, or anything relevant!
      # Contact (add or remove contact options as necessary)
      email: southwick.maia@gmail.com
      address:
        city: San Luis Obispo
        region: CA
        country: United States
        country_code: US
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: DM Me
          link: 'hhttps://www.linkedin.com/in/maia-southwick/'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
