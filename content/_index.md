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
    design:
      background:
        gradient_start: '#FEF4EC' # vanilla
        gradient_end: '#FAE0C6' # almond
        gradient_angle: 180
  - block: experience
    content:
      title: Research & Teaching Experience
      subtitle: |2-
        Developed a strong background in research and studying developmental psychology.
        
        * Managed multiple concurrent market research projects 
        * Created a new-in-kind research product
        * Processed & analyzed qualitative & quantitative data
        * Trained & led a team of RAs in completing an undergraduate research project
        * Provided class support, graded papers, & presented a lecture on developmental psychology
      
      
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
          description: ''
        - title: Research Assistant
          company: University of Utah, Social Development Lab
          company_url: 'https://psych.utah.edu/research/labs/social-development-lab.php'
          location: Salt Lake City, Utah
          date_start: '2018-01-01'
          date_end: '2021-05-07'
          description: ''
        - title: Teaching Assistant, PSY 1010 & 2010
          company: University of Utah, Department of Psychology
          company_url: 'https://psych.utah.edu/'
          location: Salt Lake City, Utah
          date_start: '2019-08-22'
          date_end: '2020-05-07'
          description: ''
    design:
      columns: '2'
      background:
        gradient_start: '#FAE0C6' # almond
        gradient_end: '#F5F3F7' # ghost white
        gradient_angle: 180
  - block: experience
    content:
      title: Applied Developmental Experience
      subtitle: |2-
        Worked with youth aged 2- to 15-years-old across educational and therapeutic contexts.
        
        * Provided classroom support
        * Facilitated socio-emotional learning 
        * Guided instructional activities in reading, writing, logic, & math
        * Implemented early intervention services & behavioral management
      date_format: Jan 2006
      items:
        - title: Instructional Aide
          company: San Luis Coastal Unified School District
          company_url: 'https://www.slcusd.org/'
          location: San Luis Obispo, California
          date_start: '2022-08-25'
          date_end: '2023-06-02'
          description: ''
        - title: Child Development Specialist
          company: Compass Center, Inc.
          company_url: 'https://compasscenterinc.com/about-us/'
          location: Santa Maria, California
          date_start: '2021-11-22'
          date_end: '2022-08-24'
          description: ''
        - title: Learning Coach & Behavior Technician
          company: Fit Learning SLC
          company_url: 'https://fitlearners.com/'
          location: Salt Lake City, Utah
          date_start: '2020-08-22'
          date_end: '2021-07-22'
          description: ''
        - title: Preschool Assistant
          company: The Children's Center
          company_url: 'https://childrenscenterutah.org/'
          location: Salt Lake City, Utah
          date_start: '2017-10-01'
          date_end: '2018-08-01'
          description: ''
    design:
      columns: '2'
      background:
        gradient_start: '#F5F3F7' # ghost white
        gradient_end: '#E0DAE7' # lavender
        gradient_angle: 180
  - block: experience
    content:
      title: Social Systems Experience
      subtitle: |2-
        Worked in contexts where social and economic institutions intersect with people's everyday lives

        * Worked one-on-one with low-income families to file federal & state tax returns
        * Participated in one of the largest survey data collection efforts in the U.S.
        * Connected survivors of domestic violence to legal & victim advocates
        * Conducted research on barriers in access to childcare subsidies among low-income families
      date_format: Jan 2006
      items:
        - title: Volunteer Income Tax Assitance (VITA) Volunteer
          company: United Way
          company_url: 'https://www.irs.gov/individuals/free-tax-return-preparation-for-qualifying-taxpayers'
          location: Santa Maria, California
          date_start: '2022-01-14'
          date_end: '2022-04-15'
          description: ''
        - title: Census Taker (Enumerator)
          company: United States Census Bureau
          company_url: 'https://www.census.gov/programs-surveys/decennial-census/decade/2020/2020-census-results.html'
          location: Salt Lake City, Utah
          date_start: '2020-08-22'
          date_end: '2020-09-24'
          description: ''
        - title: Student Intern
          company: YWCA, Family Justice Center
          company_url: 'https://slcfamilyjusticecenter.org/'
          location: Salt Lake City, Utah
          date_start: '2020-01-01'
          date_end: '2021-03-01'
          description: ''
        - title: Strategic Planning Intern
          company: U.S. Department of Health & Human Services
          company_url: 'https://aspe.hhs.gov/topics/strategic-plan'
          location: Washington, D.C.
          date_start: '2019-05-01'
          date_end: '2019-08-01'
          description: ''
    design:
      columns: '2'
      background:
        gradient_start: '#E0DAE7' # lavender
        gradient_end: '#D8E9E3' # mint cream
        gradient_angle: 180
  - block: features
    content:
      title: What I've Learned #add in overview or more skills, see if two rows is possible
      items:
        - name: R
          description: ''
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: ''          
          icon: chart-line
          icon_pack: fas
        - name: Microsoft Office
          description: ''
          icon: microsoft
          icon_pack: fab
        - name: Project Management
          description: ''
          icon: clipboard
          icon_pack: fas
        - name: Qualitative Methods
          description: ''
          icon: comment
          icon_pack: fas
        - name: Data Collection
          description: ''
          icon: box-archive
          icon_pack: fas
    design:
      background:
        gradient_start: '#D8E9E3' # mint cream
        gradient_end: '#FEF4EC' # vanilla
        gradient_angle: 180 
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: What I've Accomplished
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
      background:
        gradient_start: '#FEF4EC' # vanilla
        gradient_end: '#FAE0C6' # almond
        gradient_angle: 180
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
      background:
        gradient_start: '#FAE0C6' # almond
        gradient_end: '#F5F3F7' # ghost white
        gradient_angle: 180 

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