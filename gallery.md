---
layout: page
title: Gallery & Evidence
permalink: /gallery/
---

<div id="imageModal" style="display: none; position: fixed; z-index: 9999; left: 0; top: 0; width: 100%; height: 100%; background-color: rgba(0,0,0,0.9); align-items: center; justify-content: center; cursor: pointer;" onclick="closeModal()">
  <img id="modalImg" style="max-width: 90%; max-height: 90%; border-radius: 6px; box-shadow: 0 0 25px rgba(255,255,255,0.25);">
</div>

<script>
  function openModal(imgSrc) {
    document.getElementById('modalImg').src = imgSrc;
    document.getElementById('imageModal').style.display = 'flex';
  }
  function closeModal() {
    document.getElementById('imageModal').style.display = 'none';
  }
</script>

<div style="display: flex; align-items: center; gap: 20px; margin-bottom: 40px; padding: 15px; background: #fafafa; border-radius: 12px; border: 1px solid #eee;">
  <img src="{{ site.baseurl }}/images/cape-logo.png" alt="CAPE Kerala Logo" style="width: 90px; height: auto; cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge">
  <div>
    <h3 style="margin: 0; color: #333;">College of Engineering Pathanapuram</h3>
    <p style="margin: 5px 0 0 0; color: #666; font-size: 0.95em;">Co-operative Academy of Professional Education (CAPE), Government of Kerala</p>
  </div>
</div>

<div id="ieee-execom-section" style="margin-bottom: 60px;">
  <div style="display: flex; align-items: center; gap: 20px; margin-bottom: 15px;">
    <img src="{{ site.baseurl }}/images/ieee-logo.jpg" alt="IEEE Logo" style="width: 70px; height: 70px; object-fit: contain; cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge">
    <div>
      <h2 style="margin: 0;">IEEE Student Branch Board & Membership</h2>
      <p style="margin: 3px 0 0 0; color: #666; font-size: 0.95em;">Official Executive Committee Postings and Chapter Credentials</p>
    </div>
  </div>
  <p>Official records of election to the branch EXECOM along with international professional society membership credentials.
  <a href="{{ site.baseurl }}/projects#role-ieee-doc-head" style="text-decoration: underline; color: #00629B;">Read Role Details</a></p>

  <h4 style="color: #333; margin-bottom: 15px;">📋 Official EXECOM 2026 Board Postings</h4>
  <div style="display: grid; grid-template-columns: 1fr 1.2fr; gap: 20px; margin-bottom: 30px;">
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/ieee-execom-wie.jpeg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.85em; color: #555; margin-top: 5px;">IEEE WIE Executive Panel Design</p>
    </div>
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/ieee-execom-main.jpeg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.85em; color: #555; margin-top: 5px;">IEEE Student Branch Main Officer Board (Athul J: Documentation Head)</p>
    </div>
  </div>

  <h4 style="color: #333; margin-bottom: 15px;">📸 Branch Gatherings, Professional Oath, and Group Logs</h4>
  <div style="display: grid; grid-template-columns: 1fr 1.3fr; gap: 20px; margin-bottom: 30px; align-items: start;">
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/ieee-agm-oath.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.85em; color: #555; margin-top: 5px;">Elected Officers Taking the Student Leadership Pledge</p>
    </div>
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/ieee-agm-group.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.85em; color: #555; margin-top: 5px;">Branch Assembly Group Photo with Faculty Advisors</p>
    </div>
  </div>

  <h4 style="color: #333; margin-bottom: 15px;">📜 Verified Chapter & Society Membership Certificates</h4>
  <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px;">
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/ieee-cert-membership.png" style="border-radius: 6px; width: 100%; border: 1px solid #ddd; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.8em; color: #555; margin-top: 5px;">IEEE International Student Member Card</p>
    </div>
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/ieee-cert-pes.png" style="border-radius: 6px; width: 100%; border: 1px solid #ddd; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.8em; color: #555; margin-top: 5px;">IEEE Power & Energy Society Charter</p>
    </div>
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/ieee-cert-wie.png" style="border-radius: 6px; width: 100%; border: 1px solid #ddd; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.8em; color: #555; margin-top: 5px;">IEEE Women in Engineering Roster Charter</p>
    </div>
  </div>
</div>

<hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;">

<div id="ieee-tinkherhack" style="margin-bottom: 60px;">
  <h2>IEEE: Tink-Her-Hack 4.0</h2>
  <p>Tink-Her-Hack is an annual women-exclusive hackathon presented by TinkerHub. At the College of Engineering Pathanapuram (CE Pathanapuram), the event is organized primarily by the IEDC (Innovation & Entrepreneurship Development Cell) in close association with the IEEE Women in Engineering (WIE) and IEEE Student Branch.
  <a href="{{ site.baseurl }}/projects#role-tink-her-hack" style="text-decoration: underline; color: #00629B;">Read Role Details</a></p>
  
  <div style="padding: 12px; background: #fafafa; border-radius: 8px; border: 1px solid #ddd; margin-bottom: 20px;">
    <strong>Official Document:</strong> <a href="{{ site.baseurl }}/assets/reports/Tink-Her-Hack_4.0_Report.pdf" target="_blank">Open Event Report PDF</a>
  </div>

  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px;">
    <img src="{{ site.baseurl }}/images/tink-her-hack-group.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
    <img src="{{ site.baseurl }}/images/tink-her-hack-ceremony.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
  </div>
</div>

<hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;">

<div id="ieee-iedc" style="margin-bottom: 60px;">
  <div style="display: flex; align-items: center; gap: 20px; margin-bottom: 15px;">
    <img src="{{ site.baseurl }}/images/iedc-logo.jpg" alt="IEDC Logo" style="width: 70px; height: 70px; object-fit: contain; cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge">
    <div>
      <h2 style="margin: 0;">IEDC Startup Summit 2026</h2>
      <p style="margin: 3px 0 0 0; color: #666; font-size: 0.95em;">Innovation & Entrepreneurship Development Cell State Assembly</p>
    </div>
  </div>
  <p>Representing the College of Engineering Pathanapuram as a Student Delegate at the All-Kerala IEDC Startup Summit 2026 hosted at Amal Jyothi College of Engineering, Kanjirappally.
  <a href="{{ site.baseurl }}/projects#role-iedc-summit" style="text-decoration: underline; color: #00629B;">Read Role Details</a></p>
  
  <div style="display: grid; grid-template-columns: 1.51fr 1.33fr; gap: 20px; align-items: end;">
    <img src="{{ site.baseurl }}/images/iedc-summit-group.jpeg" style="border-radius: 12px; width: 100%; height: auto; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
    <img src="{{ site.baseurl }}/images/iedc-summit-kit.jpeg" style="border-radius: 12px; width: 100%; height: auto; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
  </div>
  <p style="font-size: 0.9em; color: #666; margin-top: 15px;"><em>Left: The College of Engineering Pathanapuram delegate group at the summit main venue. Right: Official Delegate kit and startup summit session materials.</em></p>
</div>

<hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;">

<div id="nss-nrpf" style="margin-bottom: 60px;">
  <div style="display: flex; align-items: center; gap: 20px; margin-bottom: 15px;">
    <div style="display: flex; gap: 10px;">
      <img src="{{ site.baseurl }}/images/nss-logo.jpg" alt="NSS Logo" style="width: 60px; height: 60px; border-radius: 50%; object-fit: cover; cursor: pointer;" onclick="openModal(this.src)">
      <img src="{{ site.baseurl }}/images/nrpf-logo.jpg" alt="NRPF Logo" style="width: 60px; height: 60px; border-radius: 50%; object-fit: cover; cursor: pointer;" onclick="openModal(this.src)">
    </div>
    <div>
      <h2>NRPF Annual Meet</h2>
      <p style="margin: 3px 0 0 0; color: #666; font-size: 0.95em;">National Service Scheme Nature Resource Protection Wing Assembly</p>
    </div>
  </div>
  <p>Participation in the National Service Scheme (NSS) Natural Resource Protection Force (NRPF) Annual State Meet representing the NSS Unit 314 of College of Engineering Pathanapuram at ACE College of Engineering, Trivandrum.
  <a href="{{ site.baseurl }}/projects#role-nrpf-meet" style="text-decoration: underline; color: #00629B;">Read Role Details</a></p>
  
  <div style="display: grid; grid-template-columns: 1.8fr 1fr; gap: 20px; align-items: end; margin-bottom: 10px;">
    <img src="{{ site.baseurl }}/images/nrpf-all-kerala-ucs.JPG" style="border-radius: 12px; width: 100%; height: auto; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
    <img src="{{ site.baseurl }}/images/nrpf-regional-group.jpeg" style="border-radius: 12px; width: 100%; height: auto; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
  </div>
  <p style="font-size: 0.9em; color: #666; margin-bottom: 25px;"><em>Left: Group photo of all-Kerala Unit Coordinators (UC's) and state leadership blocks at the venue center. Right: Regional group photo of Kollam-Pathanamthitta district volunteers.</em></p>

  <div style="display: grid; grid-template-columns: 1.8fr 1fr; gap: 20px; align-items: end;">
    <img src="{{ site.baseurl }}/images/nrpf-dinner-arrangements.jpeg" style="border-radius: 12px; width: 100%; height: auto; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
    <img src="{{ site.baseurl }}/images/nrpf-registration-pec.JPG" style="border-radius: 12px; width: 100%; height: auto; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
  </div>
  <p style="font-size: 0.9em; color: #666; margin-top: 15px;"><em>Left: Assembly area dining arrangements at the host institution. Right: On-site counter workspace setup during regional registration.</em></p>
</div>

<hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;">

<div id="aapda-mitra" style="margin-bottom: 60px;">
  <div style="display: flex; align-items: center; gap: 20px; margin-bottom: 15px;">
    <img src="{{ site.baseurl }}/images/ndma-logo.png" alt="NDMA Logo" style="width: 70px; height: auto; cursor: pointer;" onclick="openModal(this.src)">
    <div>
      <h2>Aapda Mitra: 7-Day Residential Training</h2>
      <p style="margin: 3px 0 0 0; color: #666; font-size: 0.95em;">National Disaster Management Authority Training Program</p>
    </div>
  </div>
  <p>Pictures from our emergency safety camp.
  <a href="{{ site.baseurl }}/projects#role-aapda-mitra" style="text-decoration: underline; color: #00629B;">Read Role Details</a></p>

  <div style="display: grid; grid-template-columns: 1fr 1.5fr; gap: 20px; align-items: start;">
    <img src="{{ site.baseurl }}/images/aapda-mitra-frame.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
    <div>
      <img src="{{ site.baseurl }}/images/aapda-mitra-group.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; margin-bottom: 15px; cursor: pointer;" onclick="openModal(this.src)">
      <div style="padding: 15px; background: #f0fbff; border-radius: 8px; text-align: center; border: 1px solid #00c6ff;">
        <h4 style="margin: 0 0 10px 0;">🎬 Camp Video Diary</h4>
        <a href="https://youtube.com/shorts/gs9gDMprpIc" target="_blank" style="font-weight: bold; text-decoration: underline; color: #00629B;">Watch Camp Memories on YouTube</a>
      </div>
    </div>
  </div>
</div>

<hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;">

<div id="association-storm" style="margin-bottom: 60px;">
  <div style="display: flex; align-items: center; gap: 20px; margin-bottom: 15px;">
    <img src="{{ site.baseurl }}/images/storm-logo.png" alt="S.T.O.R.M. Logo" style="width: 85px; height: 85px; object-fit: contain; background: #000; border-radius: 50%; border: 2px solid #00629B; cursor: pointer; padding: 5px;" onclick="openModal(this.src)" title="Click to open full profile logo">
    <div>
      <h2 style="margin: 0; font-size: 1.6em;">Mechanical Engineering Association: STORM</h2>
      <p style="margin: 3px 0 0 0; color: #666; font-size: 0.95em;">Sovereign Technological Organisation for Royal Mech (PEC)</p>
    </div>
  </div>
  <p style="color: #444;">Photos and media updates from our annual automobile exhibition events.</p>

  <div id="storm-25" style="margin-bottom: 40px; margin-top: 25px; padding: 20px; background: #fafafa; border-radius: 12px; border: 1px solid #e0e0e0;">
    <h3 style="color: #00629B; margin-top: 0;">🏎️ Punalur Auto Show '25</h3>
    <p><a href="{{ site.baseurl }}/projects#role-autoshow-25" style="text-decoration: underline; color: #00629B; font-weight: bold;">Read Role Details</a></p>
    
    <h4 style="color: #333; margin-bottom: 10px;">📋 Event Posters & Promotional Materials</h4>
    <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px; margin-bottom: 20px;">
      <img src="{{ site.baseurl }}/images/storm-25-poster-main.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <img src="{{ site.baseurl }}/images/storm-25-poster-malabari.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <img src="{{ site.baseurl }}/images/storm-25-poster-madmax.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
    </div>

    <h4 style="color: #333; margin-bottom: 10px;">📸 Exhibition Grounds & Vehicle Coordination</h4>
    <div style="display: grid; grid-template-columns: 1fr 1.2fr; gap: 15px; margin-bottom: 20px;">
      <img src="{{ site.baseurl }}/images/storm-25-entry-line.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <img src="{{ site.baseurl }}/images/storm-25-ground-circle.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
    </div>

    <h4 style="color: #333; margin-bottom: 10px;">🎬 Production Video Logs</h4>
    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px; margin-bottom: 15px;">
      <div style="padding: 12px; background: #f0fbff; border-radius: 8px; border: 1px solid #00629B; text-align: center;">
        <h5 style="margin: 0 0 5px 0;">🎬 Official Promo Teaser</h5>
        <a href="https://www.youtube.com/shorts/P_HnHx1C7do" target="_blank" style="font-size: 0.9em; font-weight: bold; color: #00629B;">Watch Teaser →</a>
      </div>
      <div style="padding: 12px; background: #f0fbff; border-radius: 8px; border: 1px solid #00629B; text-align: center;">
        <h5 style="margin: 0 0 5px 0;">🔱 Vehicle Entry Gate Log</h5>
        <a href="https://www.youtube.com/shorts/8cj0zOSvr2g" target="_blank" style="font-size: 0.9em; font-weight: bold; color: #00629B;">Watch Arrival Log →</a>
      </div>
    </div>
    <div style="padding: 12px; background: #f0fbff; border-radius: 8px; border: 1px solid #00629B; text-align: center;">
      <h5 style="margin: 0 0 5px 0;">🔊 Main Exhibition Walkthrough</h5>
      <a href="https://www.youtube.com/shorts/iC5Rt0aplwE" target="_blank" style="font-size: 0.9em; font-weight: bold; color: #00629B;">Watch Walkthrough →</a>
    </div>
  </div>

  <div id="storm-26" style="margin-top: 40px; padding: 20px; background: #fafafa; border-radius: 12px; border: 1px solid #e0e0e0;">
    <h3 style="color: #00629B; margin-top: 0;">🚀 Punalur Auto Show '26</h3>
    <p><a href="{{ site.baseurl }}/projects#role-autoshow-26" style="text-decoration: underline; color: #00629B; font-weight: bold;">Read Role Details</a></p>
    
    <h4 style="color: #333; margin-bottom: 15px;">📸 Staging & Exhibition Photos</h4>
    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px; margin-bottom: 20px;">
      <img src="{{ site.baseurl }}/images/storm-26-athul-single.jpeg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <img src="{{ site.baseurl }}/images/storm-26-athul-batman.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
    </div>

    <h4 style="color: #333; margin-bottom: 15px;">🌟 S.T.O.R.M. Association Team & Classmates</h4>
    <div style="text-align: center; margin-bottom: 25px;">
      <img src="{{ site.baseurl }}/images/storm-26-class-group-main.jpeg" style="border-radius: 12px; width: 100%; height: auto; border: 2px solid #00629B; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.9em; color: #555; margin-top: 8px;">Our final core student crew group picture at the public ground space.</p>
    </div>

    <h4 style="color: #333; margin-bottom: 12px;">📋 Official Showcase Feature Graphics</h4>
    <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px; margin-bottom: 15px;">
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-main.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">Official Main Poster</p>
      </div>
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-ratroad.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">'Rat Road' Custom Build</p>
      </div>
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-gonz.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">'Gonz Spec' SUV Build</p>
      </div>
    </div>

    <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px; margin-bottom: 15px;">
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-petric.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">'Petric' Custom Wrap Build</p>
      </div>
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-sheriff.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">'Sheriff' Custom Modification</p>
      </div>
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-stranger.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">'Stranger Things' Build</p>
      </div>
    </div>

    <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px; margin-bottom: 25px;">
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-criminal.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">'Criminal' Scissor Wrap</p>
      </div>
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-batman1.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">'Batman' Skyline Feature</p>
      </div>
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-coke.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">'Coca-Cola' Stance Build</p>
      </div>
    </div>

    <h4 style="color: #333; margin-bottom: 12px;">📸 On-Field Layout Metrics & Video Clips</h4>
    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px; margin-bottom: 15px;">
      <img src="{{ site.baseurl }}/images/storm-26-arena-lineup.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <img src="{{ site.baseurl }}/images/storm-26-ground-display.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
    </div>
    <div style="display: grid; grid-template-columns: 1.2fr 1fr 1fr; gap: 15px; margin-bottom: 25px;">
      <img src="{{ site.baseurl }}/images/storm-26-exhaust-flame.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <img src="{{ site.baseurl }}/images/storm-26-ratroad-front.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <img src="{{ site.baseurl }}/images/storm-26-bmw-spider.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
    </div>

    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px; margin-bottom: 15px;">
      <div style="padding: 12px; background: #f0fbff; border-radius: 8px; border: 1px solid #00629B; text-align: center;">
        <h5 style="margin: 0 0 5px 0;">🎬 Official Aftermovie</h5>
        <a href="https://www.youtube.com/shorts/xVrFv5QRojc" target="_blank" style="font-size: 0.9em; font-weight: bold; color: #00629B;">Watch Log Clip →</a>
      </div>
      <div style="padding: 12px; background: #f0fbff; border-radius: 8px; border: 1px solid #00629B; text-align: center;">
        <h5 style="margin: 0 0 5px 0;">🦇 Batman Wrap Focus</h5>
        <a href="https://www.youtube.com/shorts/q43qkpWjcu4" target="_blank" style="font-size: 0.9em; font-weight: bold; color: #00629B;">Watch Log Clip →</a>
      </div>
    </div>
    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px;">
      <div style="padding: 12px; background: #f0fbff; border-radius: 8px; border: 1px solid #00629B; text-align: center;">
        <h5 style="margin: 0 0 5px 0;">🔊 Field Stance Layout</h5>
        <a href="https://www.youtube.com/shorts/4v6p6JEPsdc" target="_blank" style="font-size: 0.9em; font-weight: bold; color: #00629B;">Watch Log Clip →</a>
      </div>
      <div style="padding: 12px; background: #f0fbff; border-radius: 8px; border: 1px solid #00629B; text-align: center;">
        <h5 style="margin: 0 0 5px 0;">🏎️ BMW Traction Run</h5>
        <a href="https://www.youtube.com/shorts/PE2vjBGV2ZE" target="_blank" style="font-size: 0.9em; font-weight: bold; color: #00629B;">Watch Log Clip →</a>
      </div>
    </div>
  </div>
</div>
