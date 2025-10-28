---
title: 'Home'
date: 2025-05-30
type: landing

design:
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Good Turn Labor's Never Give Up Transitional Living
      text: An 84-day structured transitional housing program in Omaha, Nebraska operated under the nonprofit 501(c)(3) organization, Good Turn Labor, to support formerly incarcerated individuals as they reintegrate into the community.
      primary_action:
        text: Support The Program
        url: https://www.convergepay.com/hosted-payments?ssl_txn_auth_token=QVQ%2BZQDeRS%2Bl9WmNDygSkQAAAZgfevef
        icon: rocket-launch
    design:
      css_class: "dark text-white"
      background:
        color: "#0E2240"
        image:
          filename: bg-waves.svg
          filters:
            brightness: 0.5
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
        
  # GLOBAL STYLES (hidden, zero spacing)
  - block: markdown
    id: global-styles
    content:
      text: >
        <style>
          /* Titles + accents */
          .section-title { color:#0E2240; font-weight:700; text-align:center; margin-bottom:.5rem; }
          .section-underline { display:inline-block; border-bottom:4px solid #FECA1B; border-radius:2px; padding-bottom:.25rem; }
          .highlight-text { color:#4D3B2F; }

          /* Buttons */
          .button-gold {
            background-color:#FECA1B; color:#0E2240;
            font-weight:700; border-radius:8px;
            padding:.6rem 1.2rem; text-decoration:none;
            display:inline-block;
          }
          .button-gold:hover { background-color:#FFD84A; }

          /* Layout + containers */
          * { box-sizing:border-box; }
          html, body { width:100%; overflow-x:hidden; }
          .container-pad { padding-left:1rem; padding-right:1rem; box-sizing:border-box; max-width:100%; }
          .no-overflow { overflow-x:hidden !important; max-width:100vw; }
          img, iframe, video { max-width:100%; height:auto; display:block; }

          /* Testimonials */
          .testimonials-grid {
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
            gap:1.25rem;
            max-width:1100px;
            margin:0 auto;
            padding:0 1rem;
          }
          @media (max-width:430px){ .testimonials-grid{grid-template-columns:1fr;} }
          .testimonial-card {
            background:#F9FAFB; border-left:4px solid #FECA1B;
            border-radius:8px; padding:1rem 1.25rem;
            box-shadow:0 2px 5px rgba(0,0,0,0.05);
            text-align:left; color:#0E2240;
            font-size:0.95rem; line-height:1.5;
            overflow-wrap:anywhere; word-break:normal;
          }
          .testimonial-card strong { display:block; margin-top:0.5rem; font-size:0.9rem; color:#4D3B2F; }

          /* Sponsors — fixed width + padding */
          .sponsor-wrap {
            text-align:center;
            padding:2.5rem 1rem;
            max-width:900px; margin:0 auto;
            width:100%;
          }
          .sponsor-list {
            display:grid;
            grid-template-columns:repeat(auto-fit, minmax(180px,1fr));
            gap:1rem;
            list-style:none;
            padding:0;
            margin:0 auto;
            width:100%;
            max-width:700px;
          }
          @media (max-width: 400px){
            .sponsor-list{ grid-template-columns:1fr; }
          }
          .sponsor-item {
            background:#FFF8E1;
            border-left:4px solid #FECA1B;
            border-radius:8px;
            padding:.75rem;
            color:#0E2240;
            word-break:break-word; overflow-wrap:anywhere;
          }

          /* Donate card helpers */
          .title-on-dark { color:#FFFFFF !important; }
          .text-on-dark { color:#FFFFFF !important; }
        </style>
    design:
      css_class: "hidden"
      spacing:
        padding: [0,0,0,0]
        margin: [0,0,0,0]

  - block: stats
    content:
      items:
        - statistic: "45"
          description: |
            Men Admitted     
            Since March 2025
        - statistic: "--%"
          description: |
            Graduation Rate     
            (Data Not Yet Available) 
        - statistic: "--%"
          description: |
            1-Year Recidivism Rate     
            (Data Not Yet Available) 
    design:
      css_class: "bg-white"
      spacing:
        padding: ["1rem", 0, "1rem", 0]

  - block: markdown
    id: program
    content:
      title: '<span class="section-title"><span class="section-underline">About the Program</span></span>'
      text: >
        <img src="/media/logo.png" alt="NGU Logo" style="max-height:200px;display:block;margin:0 auto 1rem auto;">
        <span class="highlight-text" style="font-size:1.125rem;text-align:center;display:block;">
        Never Give Up (NGU) Transitional Living serves <strong>men released from prison</strong> in Nebraska who:
        <br>(a) are approved for community supervision or parole,<br>
        (b) are motivated to participate in structured reentry support, and<br>
        (c) have applied to the program and completed a phone interview and background review (people convicted of sex offenses are not eligible).
        <br><br>
        The <strong>overarching goal</strong> of the program is to reduce recidivism and promote successful reintegration by fostering personal accountability, community support, and access to essential resources.</span>
    design:
      css_class: "bg-gray-100"

  - block: cta-image-paragraph
    content:
      items:
        - title: '<span class="section-title"><span class="section-underline">The NGU Approach</span></span>'
          text: '<span style="color:#4d4d4d;">Never Give Up Transitional Living creates a supportive space where individuals with lived experiences (i.e., previously incarcerated) serve as mentors, helping participants navigate challenges related to addiction, antisocial thinking patterns, employment, and prosocial and community reintegration.<br><br>By offering structured support, the program seeks to empower participants to rebuild their lives and achieve long-term stability.</span>'
          feature_icon: bolt
          features:
            - '<span style="color:#36454F;">84 days of programming</span>'
            - '<span style="color:#36454F;">24/7 supervision and accountability</span>'
            - '<span style="color:#36454F;">Stable housing</span>'
            - '<span style="color:#36454F;">Commitment to sobriety and recovery support</span>'
            - '<span style="color:#36454F;">Employment and workforce development</span>'
            - '<span style="color:#36454F;">Therapy and life skills development</span>'
            - '<span style="color:#36454F;">Family, prosocial peers, and community network (re)development</span>'
          image: unohockey_3_2025.jpeg
          button:
            text: Program Overview (PDF)
            url: /docs/NGUProgramDescription.pdf
            style: "background-color:#FECA1B;color:#0E2240;font-weight:700;border-radius:8px;padding:.5rem 1rem;"
        - title: '<span class="section-title"><span class="section-underline">What Makes NGU Unique?</span></span>'
          text: '<span style="color:#4d4d4d;">Rooted in experience. Strengthened by research. Driven by hope.</span>'
          feature_icon: bolt
          features:
            - '<span style="color:#36454F;"><strong>Built for real change.</strong> Helping people rebuild lives -- not just get by.</span>'
            - '<span style="color:#36454F;"><strong>Out-of-the-box.</strong> Innovative methods tailored for lasting impact.</span>'
            - '<span style="color:#36454F;"><strong>We&apos;ve been there.</strong> Our staff have done time, and changed their lives.</span>'
            - '<span style="color:#36454F;"><strong>We don&apos;t give up.</strong> No matter your past, we believe in your future.</span>'
            - '<span style="color:#36454F;"><strong>Evidence-based.</strong> Built with researchers to refine and prove results.</span>'
          image: groupphoto1.jpeg
          button:
            text: Meet the NGU Team
            url: /people
            style: "background-color:#FECA1B;color:#0E2240;font-weight:700;border-radius:8px;padding:.5rem 1rem;display:block;margin:0 auto;"
    design:
      css_class: "bg-white"

  - block: features
    content:
      title: '<span class="section-title"><span class="section-underline">NGU Programming + Services</span></span>'
      items:
        - name: Dialectical Behavior Therapy (DBT)
          icon: light-bulb
          description: Evidence-based group therapy focused on emotional regulation, distress tolerance, and interpersonal skills.
        - name: Intensive Outpatient Programming (IOP)
          icon: chat-bubble-oval-left-ellipsis
          description: Structured in-house clinical treatment that includes group sessions, relapse prevention, and coping strategies.
        - name: Individual Counseling
          icon: user
          description: One-on-one sessions with licensed counselors to address trauma, mental health, substance use, and personal growth.
        - name: Alcoholics Anonymous (AA) and Narcotics Anonymous (NA)
          icon: star
          description: Peer-led recovery group attendance offering 12-step support and a strong sober community.
        - name: Financial Literacy Classes
          icon: currency-dollar
          description: Practical education on budgeting, saving, credit, and building long-term financial stability.
        - name: Faith-Based Support
          icon: heart
          description: Spiritual mentorship and participation in faith-based community activities.
        - name: Housing & Basic Needs
          icon: home
          description: Safe and stable housing for the program duration, including provision of initial clothing, food, transportation, and cellphones.
        - name: Essential Documents Assistance
          icon: identification
          description: Support with obtaining or replacing ID, Social Security cards, EBT, and Medicaid enrollment if needed.
        - name: Community & Family Engagement
          icon: users
          description: Organized social outings, volunteer experiences, and family visitation days to help participants rebuild connections with loved ones and the community.
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"

  - block: markdown
    id: testimonials
    content:
      title: '<span class="section-title"><span class="section-underline">Voices from NGU</span></span>'
      text: >
        <div class="container-pad no-overflow" style="max-width:1100px;margin:0 auto;text-align:center;">
          <p style="font-size:1.125rem;color:#4D3B2F;margin-bottom:2rem;">
            Real words from participants, family, and community partners who’ve seen the impact up close.
          </p>
          <div class="testimonials-grid">
            <div class="testimonial-card">
              “Be ready for a life changing experience. This program is very motivating. It's very uplifting. NGU enabled me to become self-sufficient, maintain good employment, work on my credit, and just become an all-around productive member of society and a good person.”
              <strong>— Jason G., Program Participant</strong>
            </div>
            <div class="testimonial-card">
              “This! Is the real deal. I am so impressed with Never Give Up home. I had the honor of visiting with Shane yesterday when I visited my son. It was hard to keep the tears back. Shane's commitment to re-entry is phenomenal.”
              <strong>— Allison D., Participant’s Mother</strong>
            </div>
            <div class="testimonial-card">
              “I've had the opportunity to work with numerous transitional living programs. NGU stands out as a model of excellence. Shane's commitment to structured support, accountability, and genuine care creates real opportunities for lasting change.”
              <strong>— Brian Bencker, Assistant Program Director, NDCS Community Supervision Service</strong>
            </div>
            <div class="testimonial-card">
              “It is great to see [the men] come in and start their financial journey with us...Some of them have been able to do things they hadn't done before such as purchase a car from a dealership or a home. It is the confidence that comes from being able to accomplish goals in a way they maybe hadn't before that makes this partnership special to all of us!”
              <strong>— Yvonne, Financial Sales Manager, Centris Bank</strong>
            </div>
          </div>
        </div>
    design:
      css_class: "bg-white"
      spacing:
        padding: ["3rem", "1rem", "3rem", "1rem"]

  - block: cta-card
    id: donate
    content:
      title: '<span class="section-title title-on-dark"><span class="section-underline">Help us Change Lives</span></span>'
      text: >
        <p class="text-on-dark">Donate to Never Give Up through the 501(c)(3) organization, Good Turn Labor, LLC.</p>
      button:
        text: Support Our Mission
        url: https://www.convergepay.com/hosted-payments?ssl_txn_auth_token=QVQ%2BZQDeRS%2Bl9WmNDygSkQAAAZgfevef
        style: "background-color:#FECA1B;color:#0E2240;font-weight:700;border-radius:8px;padding:.6rem 1.2rem;"
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
      card:
        css_class: "text-white"
        css_style: "background-color:#0E2240 !important; color:#FFFFFF !important; border-radius:14px;"

  - block: markdown
    id: sponsors
    content:
      title: '<span class="section-title"><span class="section-underline">Our Sponsors</span></span>'
      text: >
        <div class="sponsor-wrap no-overflow">
          <p style="font-size:1.125rem;color:#0E2240;max-width:700px;margin:0 auto 2rem auto;">
            We’re deeply grateful to our partners who make the Never Give Up Transitional Living Program possible through their generosity and belief in second chances.
          </p>
          <ul class="sponsor-list">
            <li class="sponsor-item">Omaha Community Foundation</li>
            <li class="sponsor-item">William & Ruth Scott Family Foundation</li>
            <li class="sponsor-item">The Sherwood Foundation</li>
            <li class="sponsor-item">John L. Scott Foundation</li>
            <li class="sponsor-item">Lozier Foundation</li>
            <li class="sponsor-item">Don Scott Foundation</li>
          </ul>
        </div>
    design:
      css_class: "bg-white"
      spacing:
        padding: ["3rem", "1rem", "3rem", "1rem"]

  - block: markdown
    id: news
    content:
      title: '<span class="section-title"><span class="section-underline">NGU in the News</span></span>'
      text: >
        <style>
          .news-videos{display:flex;flex-wrap:wrap;justify-content:center;gap:1rem;}
          .news-video{flex:1 1 480px;max-width:480px;}
          iframe{width:100%;height:270px;border-radius:12px;}
        </style>
        <div class="news-videos">
          <div class="news-video">
            <iframe src="https://www.youtube.com/embed/FeUuBwGDzQw" title="NGU in the News - KETV" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
          <div class="news-video">
            <iframe src="https://www.youtube.com/embed/KwdsjcoviiE" title="NGU in the News - Second Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
        </div>
    design:
      css_class: "bg-gray-100"

  - block: markdown
    content:
      title: '<span class="section-title"><span class="section-underline">Moments at NGU</span></span>'
      text: >
        <style>
          .gallery-container{display:flex;flex-wrap:wrap;gap:1rem;justify-content:center;}
          .gallery-item{flex:1 1 calc(48% - 1rem);max-width:calc(48% - 1rem);box-shadow:0 4px 10px rgba(0,0,0,0.2);border-radius:12px;overflow:hidden;background:white;text-align:center;}
          .gallery-item img{width:100%;height:auto;display:block;}
          .gallery-caption{padding:0.5rem;font-size:1rem;color:#0E2240;}
          @media(max-width:640px){.gallery-item{flex:1 1 100%;max-width:100%;}}
        </style>
        <div class="gallery-container">
          <div class="gallery-item"><img src="/media/IOP3_62525.jpg" alt="Intensive Outpatient Programming"><div class="gallery-caption">Intensive Outpatient Programming</div></div>
          <div class="gallery-item"><img src="/media/unohockey_1_2025.jpeg" alt="UNO Hockey"><div class="gallery-caption">2025 UNO Hockey Game</div></div>
          <div class="gallery-item"><img src="/media/kickball_5.jpeg" alt="Kickball Tournament"><div class="gallery-caption">Kickball Tournament</div></div>
          <div class="gallery-item"><img src="/media/trunkortreat2025.jpeg" alt="Trunk or Treat"><div class="gallery-caption">2025 Trunk or Treat</div></div>
          <div class="gallery-item"><img src="/media/july42025_1.jpeg" alt="July 4th 1"><div class="gallery-caption">2025 July Fourth Extravaganza</div></div>
          <div class="gallery-item"><img src="/media/house_garden.jpg" alt="House Garden"><div class="gallery-caption">House Garden</div></div>
          <div class="gallery-item"><img src="/media/beavercreek_saturday_2.jpg" alt="Beavercreek Outing"><div class="gallery-caption">Saturday Group Outing</div></div>
          <div class="gallery-item"><img src="/media/house_flowers.jpeg" alt="House Flowers"><div class="gallery-caption">House Flowers</div></div>
        </div>
    design:
      css_class: "bg-white"
      spacing:
        padding: ["2rem", "0", "2rem", "0"]

  - block: features
    id: contact
    content:
      title: '<span class="section-title"><span class="section-underline">Contact Us</span></span>'
      items:
        - name: Program Director Shane Reilly, M.S.
          icon: phone
          description: "📞 (402) 359-7404"
        - name: Email Us
          icon: envelope
          description: "[ngutlomaha@gmail.com](mailto:ngutlomaha@gmail.com)"
        - name: Location
          icon: map-pin
          description: "Omaha, Nebraska"
        - name: Want to help us spread the word?
          icon: chat-bubble-oval-left
          description: |
            <a href="/docs/NGU Brochure.pdf" target="_blank" rel="noopener noreferrer" class="button-gold">
              Download Our Brochure
            </a>
            <br>
            Share it with someone who might benefit or want to support us!
    design:
      css_class: "bg-gray-100"
---
