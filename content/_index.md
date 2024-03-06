---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:

  # codigo Jeibros
  - block: Accomplishments
    content:
      title: 'Education'
      date_format: Jan 2006
      items:
      - date_end: '2016-06-24'
        date_start: '2012-11-05'
        organization: University of the Basque Country
        organization_url: https://ehu.eus
        description: Quadrotor Team Modeling and Control for DLO Transportation
        title: PhD Computer Science
        url: 'https://addi.ehu.es/handle/10810/21886'
    
      - date_end: '2009-06-30'
        date_start: '2003-09-01'
        organization: TECNUN - University of Navarra
        organization_url: https://tecnun.unav.edu/
        title: MS Industrial Engineering
        url: ''
    design:
      columns: '2'
    
     
  - block: Accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://ec.europa.eu/transparency/expert-groups-register/screen/expert-groups/consult?lang=en&do=groupDetail.groupDetail&groupID=3774
          date_end: '2022-10-10'
          date_start: '2021-07-01'
          description: Member of the European Group of Experts on Artificial Intelligence ethics in Education and Training
          organization: European Commission
          organization_url: https://ec.europa.eu/transparency/expert-groups-register/screen/expert-groups/consult?lang=en&do=groupDetail.groupDetail&groupID=3774
          title: Expert on Artificial Intelligence in Education and Training
          url: ''
        - certificate_url: https://www.mirmi.tum.de/mirmi/startseite/
          date_end: ''
          date_start: '2023-06-01'
          description: Visiting professor in following universities.
        - 2023: MIRMI
        - 2019: Sapienza
        - 2020: University of Kavala
        - 2019: Grenoble
          organization: MIRMI
    #     icon:MIRMI.png
          organization_url: https://www.mirmi.tum.de/mirmi/startseite/
          title: Visiting Professor
          url: https://www.mirmi.tum.de/mirmi/startseite/
          
    #    -  certificate_url: ''
    #       date_end: ''
    #       date_start: '2019-07-01'
    #      description: ''
    #       organization: Universitá de la Sapienza
    #       organization_url: https://www.uniroma1.it/en/pagina-strutturale/home
    #      title: 'Object-Oriented Programming in R'
    #      url: ''
    design:
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
 
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
      title: Media appearances
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
 
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Estaré encantado de escucharte.
      # Contact (add or remove contact options as necessary)
      email: hola@julianestevez.com
      
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/jeibros'
        
       
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
