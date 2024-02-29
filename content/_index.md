---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: hero
    id: home
    content:
      title: In-Process Psychotherapy
      image:
        filename: logo.png
      cta:
        label: '**Schedule an Appointment**'
        url: '#contact'
        style: primary
        #q: how do I change the color of this?
      cta_alt:
        label: Ask a question
        url: '#contact'
      cta_note:
        label: >-
          &nbsp;
      
          <p style="text-align: left;">Psychotherapy is a journey. We begin to look carefully and honestly at ourselves. In time, feelings surface and are freed. We change.</p>
      text: |-
        Offering Professional Counselling and Psychotherapy in Abingdon, Oxford, and Online.




    design:
      background:
        video:
      # Name of video in `assets/media/`.
          filename: intro.mp4
      # Post-processing: flip the video horizontally?
          flip: false

  - block: markdown
    content:
      title: Welcome
      subtitle: 
      text: '<p style="text-align: center;">We come to therapy when something is too painful to bear. A crisis: loss, death, a failing relationship, trauma.
      
      <p style="text-align: center;">Sometimes there isn’t anything clear. We’re not feeling alive, we’re unhappy, purposeless, lonely, or frightened.
      
      <p style="text-align: center;">Seeking help is an expression of hope for something better.</p>'
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin


  - block: logos
    content:
      title: Supported and Regulated By
      subtitle:
      # Path to the logo images within the `assets/media/` folder
      logo_folder: logos
    design:
      columns: '1'
  
  - block: collection
    id: info
    content:
      title: Find Out More
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: "questions"
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
      title: Our Work
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
##        - name: All
##          tag: '*'
##        - name: Deep Learning#
##          tag: Deep Learning
##        - name: Other
##          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: testimonials
    content:
      title: Testimonials
      subtitle: How clients describe our work
      items:
        - name: Client D
          username: Student
          # Image path relative to assets/media/ folder
          image_filename: testimonials/clientd.png
          link: 
          text: I found the experience of being really listened to by someone who I trusted and could rely upon transformed my relationship to some of the things that had happened in my past.
        - name: Client F
          username: Academic
          image_filename: testimonials/clientf.png
          link: 
          text: Ben always seems calm, attentive and purposeful. In each session we unravel a little bit more, taking out the knots in the things I'm stuck with.
        - name: Client B
          username: Local Authority Manager
          image_filename: testimonials/clientb.png
          link: 
          text: I feel like I've become interested in myself again - feel like I have as much right to be here as anyone else. Taking an hour a week to pay attention to what's actually going on for me has been transforming.

  - block: experience
    content:
      title: Working in Association With
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Abingdon Natural Health and Therapy Centre
          company: Abingdon
          company_url: 'https://abingdonnaturalhealth.co.uk/'
          company_logo: abnathealth
          location: Abingdon
          date_start: '2016-01-01'
          date_end: ''
          description: |2-
              The Centre brings together a range of experienced and dedicated therapists qualified in Psychotherapy, Counselling, Natural Health, Holistic and Complementary Therapies.
        - title: Oxford Men's Counselling Service
          company: OMCS
          company_url: 'http://www.omcs.org.uk/'
          company_logo: omcs
          location: Oxford
          date_start: '2016-01-01'
          date_end: ''
          description: Committed to providing a professional counselling service in a supportive environment where men can explore issues relevant to them 
        - title: St Ethelwolds House
          company: St Eths
          company_url: 'https://ethelwoldhouse.com/'
          company_logo: steths
          location: Abingdon
          date_start: '2016-01-01'
          date_end: ''
          description: St Ethelwold’s House is a welcoming spiritual centre offering a place of sanctuary and quiet to all people who are open to a deeper meaning in their lives. 
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        If you have any questions or would like to arrange an initial meeting, please get in touch, sharing anything you feel comfortable with.
      # Contact (add or remove contact options as necessary)
      email: hello@inprocess.org.uk
      phone: 07395 876 287
      #appointment_url: 'https://calendly.com'
      #address:
       # street: 450 Serra Mall
        #city: Stanford
        #region: CA
        #postcode: '94305'
        #country: United States
        #country_code: US
      #coordinates:
       # latitude: '37.4275'
        #longitude: '-122.1697'
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
       # - 'Monday 10:00 to 13:00'
        #- 'Wednesday 09:00 to 10:00'
      #contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: DM Me
      #    link: 'https://twitter.com/Twitter'
      #  - icon: skype
      #    icon_pack: fab
      #    name: Skype Me
      #    link: 'skype:echo123?call'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
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
  - block: contact
    id: location
    content:
      title: Locations
      subtitle: I work at a number of different sites across Oxfordshire
      text: |-
        Click the links below for maps
      # Contact (add or remove contact options as necessary)
      #email: hello@inprocess.org.uk
      #phone: 07395 876 287
      #appointment_url: 'https://calendly.com'
      #office_hours:
       # - 'Monday 10:00 to 13:00'
        #- 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: location-dot
          icon_pack: fas
          name: Abingdon Natural Health and Therapy Centre
          link: 'https://maps.app.goo.gl/74RhKA9JK2uUEDxj7'
        - icon: location-dot
          icon_pack: fas
          name: Restore, Manzil Way, Oxford
          link: 'https://maps.app.goo.gl/V4QRNeoeiY2uutPf6'
        - icon: location-dot
          icon_pack: fas
          name: St Ethelwold’s House, Abingdon
          link: 'https://maps.app.goo.gl/9trfTCvuPXQp3UZQ9'
      #  - icon: skype
      #    icon_pack: fab
      #    name: Skype Me
      #    link: 'skype:echo123?call'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      #form:
        #provider: netlify
        #formspree:
          #id:
        #netlify:
          # Enable CAPTCHA challenge to reduce spam?
          #captcha: true
    design:
      columns: '2'

---