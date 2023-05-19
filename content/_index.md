---
# Leave the homepage title empty to use the site title
title:
date: 2023-04-23
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Hi there!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: What I've Done - Research & Teaching
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
          location: Washington, D.C. (Remote)
          date_start: '2022-01-31'
          date_end: ''
          description: |2-
              * Proposed a novel product which led to a nine-month research project developing a unique sourcing resource to support talent acquisition professionals in building a more diverse, equitable workforce
              * Managed a portfolio of multiple concurrent research projects, including both collaborative and individual assignments on trends in job seeker decision-making and macroeconomic analysis
        - title: Research Assistant
          company: University of Utah, Social Development Lab
          company_url: 'https://psych.utah.edu/research/labs/social-development-lab.php'
          location: Salt Lake City, Utah
          date_start: '2018-01-01'
          date_end: '2021-05-07'
          description: |2-
          Principal investigators: [Drs. Monisha Pasupathi](https://psych.utah.edu/people/faculty/pasupathi-monisha.php) & [Cecilia Wainryb] (https://psych.utah.edu/people/faculty/wainryb-cecilia.php)

          * Developed an undergraduate thesis exploring social relationships, conflict, and interpersonal resolution by creating a university-scale online survey, leading a team of RAs quantifying qualitative data, and performing a series of statistical analyses from 400 coded narratives
          * Processed and analyzed narrative and survey data from over 200 college freshmen in a multi-institution longitudinal study investigating the effects of displacement caused by COVID-19, such as disruptions in identity development, mental health concerns, and additional impacts
        - title: Teaching Assistant, PSY 1010 & 2010
          company: University of Utah, Department of Psychology
          company_url: ''
          location: Salt Lake City, Utah
          date_start: '2019-08-22'
          date_end: '2020-05-07'
          description: |2-
          * Graded student papers and provided support to 150 students to promote classroom success in a general psychology class
          * Prepared and presented a 40-minute lecture focused on the development of sense of self across infancy to adolescence to a general psychology class of 300 students
    design:
      columns: '2'
  - block: experience
    content:
      title: What I've Done - Applied Developmental Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Instructional Aide
          company: San Luis Coastal Unified School District
          company_url: ''
          location: San Luis Obispo, California
          date_start: '2022-08-25'
          date_end: ''
          description: |2-
          * Assisting the teacher with the preparation and presentation of instructional activities in reading, language, math, and other subject areas 
          * Supporting the teacher in classroom management and socio-emotional learning
        - title: Child Development Specialist
          company: Compass Center, Inc.
          company_url: ''
          location: Santa Maria, California
          date_start: '2021-11-22'
          date_end: '2022-08-24'
          description: |2-
          * Provided one-on-one intervention for two- to three-year-old toddlers, modeled effective adult-child interactions, and maintained weekly visits to provide complete early intervention services
          * Designed implemented, and adapted activities for language, cognitive, fine and gross motor, sensory, self-help, and socio-emotional development
        - title: Learning Coach & Behavior Technician
          company: Fit Learning SLC
          company_url: ''
          location: Salt Lake City, Utah
          date_start: '2020-08-22'
          date_end: '2021-07-22'
          description: |2-
          * Coached students aged 8 to 15 in core math and reading skills to promote cognitive fitness and help students achieve fluency in previously struggling educational areas
          * Engaged in behavioral management throughout coaching sessions with learners using principles from applied behavioral analysis and general reinforcement strategies
        - title: Preschool Assistant
          company: The Children's Center
          company_url: ''
          location: Salt Lake City, Utah
          date_start: '2017-10-01'
          date_end: '2018-08-01'
          description: |2-
          * Interacted with 9 children aged 4-5 with emotional and behavioral challenges through play and demonstration of socially appropriate behaviors and emotion management techniques
          * Assisted 2 Therapeutic Preschool Specialists in managing and maintaining the classroom to create a safe and consistent environment for the children
    design:
      columns: '2'
  - block: features
    content:
      title: What I've Learned
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
      title: 'What I've Accomplished'
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
  - block: contact
    id: contact
    content:
      title: Reach Out!
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
#All hidden blocks - here for future use:
#- block: collection
    id: posts
    #content:
     # title: Recent Posts
      #subtitle: ''
      # text: ''
      # Choose how many pages you would like to display (0 = all pages)
      # count: ''
      # Filter on criteria
      #filters:
       # folders:
       #   - post
       # author: ""
       # category: ""
       # tag: ""
       # exclude_featured: false
       # exclude_future: false
       # exclude_past: false
       # publication_type: ""
      # Choose how many pages you would like to offset by
     # offset: 0
      # Page order: descending (desc) or ascending (asc) date.
     #order: desc
    design:
      # Choose a layout view
    #  view: compact
     # columns: '2'
#  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
       Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
       Filter toolbar (optional).
       Add or remove as many filters (`filter_button` instances) as you like.
       To show all items, set `tag` to "*".
       To filter by a specific tag, set `tag` to an existing tag name.
       To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - #name: All
          #tag: '*'
        - #name: Projects
          #tag: Deep Learning
        - #name: Other
          tag: Demo
    design:
       Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
       For Showcase view, flip alternate rows?
      flip_alt_rows: false
#  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
     # columns: '2'
      #view: card
#  - block: collection
    id: talks
    content:
     # title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
#  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
#  - block: collection
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