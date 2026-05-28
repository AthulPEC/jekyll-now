---
layout: page
title: Gallery & Evidence
permalink: /gallery/
---

<!-- WhatsApp Style Profile View Popup Overlay Component -->
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

<!-- HEADER SECTION: Institutional Verification -->
<div style="display: flex; align-items: center; gap: 20px; margin-bottom: 40px; padding: 15px; background: #fafafa; border-radius: 12px; border: 1px solid #eee;">
  <img src="{{ site.baseurl }}/images/cape-logo.png" alt="CAPE Kerala Logo" style="width: 90px; height: auto; cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge">
  <div>
    <h3 style="margin: 0; color: #333;">College of Engineering Pathanapuram</h3>
    <p style="margin: 5px 0 0 0; color: #666; font-size: 0.95em;">Co-operative Academy of Professional Education (CAPE), Government of Kerala</p>
  </div>
</div>

<!-- SECTION 1: STORM Association Day - Punalur Auto Show '26 -->
<div id="storm-26" style="margin-bottom: 60px;">
  <div style="display: flex; align-items: center; gap: 20px; margin-bottom: 15px;">
    <img src="{{ site.baseurl }}/images/storm-logo.png" alt="S.T.O.R.M. Logo" style="width: 70px; height: 70px; object-fit: contain; background: #000; border-radius: 50%; border: 2px solid #00629B; cursor: pointer; padding: 3px;" onclick="openModal(this.src)">
    <div>
      <h2 style="margin: 0; font-size: 1.6em;">S.T.O.R.M. Punalur Auto Show '26</h2>
      <p style="margin: 3px 0 0 0; color: #666; font-size: 0.95em;">Mechanical Engineering Association Core Exhibition Events</p>
    </div>
  </div>
  <p style="color: #444;">Photos and video logs from our most recent annual automobile presentation event. Coordinated vehicle alignments, stance displays, and entry streams at the municipal grounds. <a href="{{ site.baseurl }}/projects#role-autoshow-26" style="text-decoration: underline; color: #00629B; font-weight: bold;">Read Role Details</a></p>
  
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

  <h4 style="color: #333; margin-bottom: 12px;">📸 On-Field Layout Metrics & Video Clips</h4>
  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px; margin-bottom: 15px;">
    <img src="{{ site.baseurl }}/images/storm-26-arena-lineup.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
    <img src="{{ site.baseurl }}/images/storm-26-ground-display.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
  </div>

  <!-- Live Video Logs -->
  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px; margin-bottom: 15px;">
    <div style="padding: 12px; background: #f0fbff; border-radius: 8px; border: 1px solid #00629B; text-align: center;">
      <h5 style="margin: 0 0 5px 0;">🎬 Official Aftermovie</h5>
      <a href="https://www.youtube.com/shorts/xVrFv5QRojc" target="_blank" style="font-size: 0.9em; font-weight: bold; color: #00629B;">Watch Log Clip →</a>
    </div>
    <div style="padding: 12px; background: #f0fbff; border-radius: 8px; border: 1px solid #00629B; text-align: center;">
      <h5 style="margin: 0 0 5px 0;">🔊 Field Stance Layout</h5>
      <a href="https://www.youtube.com/shorts/4v6p6JEPsdc" target="_blank" style="font-size: 0.9em; font-weight: bold; color: #00629B;">Watch Log Clip →</a>
    </div>
  </div>
</div>

<hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;">

<!-- SECTION 2: NSS Unit 314 - NRPF Annual Meet (March 2026) -->
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
  <p>Participation in the National Service Scheme (NSS) Natural Resource Protection Force (NRPF) Annual State Meet representing the NSS Unit 314 of College of Engineering Pathanapuram at ACE College of Engineering, Trivandrum. <a href="{{ site.baseurl }}/projects#role-nrpf-meet" style="text-decoration: underline; color: #00629B; font-weight: bold;">Read Role Details</a></p>
  
  <div style="display: grid; grid-template-columns: 1.8fr 1fr; gap: 20px; align-items: end; margin-bottom: 10px;">
    <img src="{{ site.baseurl }}/images/nrpf-all-kerala-ucs.JPG" style="border-radius: 12px; width: 100%; height: auto; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
    <img src="{{ site.baseurl }}/images/nrpf-regional-group.jpeg" style="border-radius: 12px; width: 100%; height: auto; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
  </div>
  <p style="font-size: 0.9em; color: #666; margin-bottom: 25px;"><em>Left: Group photo of all-Kerala Unit Coordinators (UC's) and state leadership blocks. Right: Regional group photo of Kollam-Pathanamthitta district volunteers.</em></p>

  <div style="display: grid; grid-template-columns: 1.8fr 1fr; gap: 20px; align-items: end;">
    <img src="{{ site.baseurl }}/images/nrpf-dinner-arrangements.jpeg" style="border-radius: 12px; width: 100%; height: auto; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
    <img src="{{ site.baseurl }}/images/nrpf-registration-pec.JPG" style="border-radius: 12px; width: 100%; height: auto; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
  </div>
  <p style="font-size: 0.9em; color: #666; margin-top: 15px;"><em>Left: Assembly area dining arrangements at the host institution. Right: On-site counter workspace setup during regional registration.</em></p>
</div>

<hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;">

<!-- SECTION 3: IEDC Startup Summit 2026 (March 2026) -->
<div id="ieee-iedc" style="margin-bottom: 60px;">
  <div style="display: flex; align-items: center; gap: 20px; margin-bottom: 15px;">
    <img src="{{ site.baseurl }}/images/iedc-logo.jpg" alt="IEDC Logo" style="width: 70px; height: 70px; object-fit: contain; cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge">
    <div>
      <h2 style="margin: 0;">IEDC Startup Summit 2026</h2>
      <p style="margin: 3px 0 0 0; color: #666; font-size: 0.95em;">Innovation & Entrepreneurship Development Cell State Assembly</p>
    </div>
  </div>
  <p>Representing the College of Engineering Pathanapuram as a Student Delegate at the All-Kerala IEDC Startup Summit 2026 hosted at Amal Jyothi College of Engineering, Kanjirappally. <a href="{{ site.baseurl }}/projects#role-iedc-summit" style="text-decoration: underline; color: #00629B; font-weight: bold;">Read Role Details</a></p>
  
  <div style="display: grid; grid-template-columns: 1.51fr 1.33fr; gap: 20px; align-items: end;">
    <img src="{{ site.baseurl }}/images/iedc-summit-group.jpeg" style="border-radius: 12px; width: 100%; height: auto; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
    <img src="{{ site.baseurl }}/images/iedc-summit-kit.jpeg" style="border-radius: 12px; width: 100%; height: auto; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
  </div>
  <p style="font-size: 0.9em; color: #666; margin-top: 15px;"><em>Left: The College of Engineering Pathanapuram delegate group at the summit main venue. Right: Official Delegate kit and startup summit session materials.</em></p>
</div>

<hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;">

<!-- SECTION 4: IEEE Tink-Her-Hack 4.0 Hackathon (February 2026) -->
<div id="ieee-tinkherhack" style="margin-bottom: 60px;">
  <h2>IEEE: Tink-Her-Hack 4.0</h2>
  <p>Tink-Her-Hack is an annual women-exclusive hackathon presented by TinkerHub. At the College of Engineering Pathanapuram (CE Pathanapuram), the event is organized primarily by the IEDC (Innovation & Entrepreneurship Development Cell) in close association with the IEEE Women in Engineering (WIE) and IEEE Student Branch. <a href="{{ site.baseurl }}/projects#role-tink-her-hack" style="text-decoration: underline; color: #00629B; font-weight: bold;">Read Role Details</a></p>
  
  <div style="padding: 12px; background: #fafafa; border-radius: 8px; border: 1px solid #ddd; margin-bottom: 20px;">
    <strong>Official Document:</strong> <a href="{{ site.baseurl }}/assets/reports/Tink-Her-Hack_4.0_Report.pdf" target="_blank">Open Event Report PDF</a>
  </div>

  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px;">
    <img src="{{ site.baseurl }}/images/tink-her-hack-group.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
    <img src="{{ site.baseurl }}/images/tink-her-hack-ceremony.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
  </div>
</div>

<hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;">

<!-- SECTION 5: NDMA Aapda Mitra Disaster Management Training Camp (Early 2026) -->
<div id="aapda-mitra" style="margin-bottom: 60px;">
  <div style="display: flex; align-items: center; gap: 20px; margin-bottom: 15px;">
    <img src="{{ site.baseurl }}/images/ndma-logo.png" alt="NDMA Logo" style="width: 70px; height: auto; cursor: pointer;" onclick="openModal(this.src)">
    <div>
      <h2>Aapda Mitra: 7-Day Residential Training</h2>
      <p style="margin: 3px 0 0 0; color: #666; font-size: 0.95em;">National Disaster Management Authority Training Program</p>
    </div>
  </div>
  <p>Pictures and summary verification tracking metrics from our safety camp. <a href="{{ site.baseurl }}/projects#role-aapda-mitra" style="text-decoration: underline; color: #00629B; font-weight: bold;">Read Role Details</a></p>

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

<!-- SECTION 6: IEEE Branch Leadership, AGM Oath & Credentials -->
<div id="ieee-execom-section" style="margin-bottom: 60px;">
  <div style="display: flex; align-items: center; gap: 20px; margin-bottom: 15px;">
    <img src="{{ site.baseurl }}/images/ieee-logo.jpg" alt="IEEE Logo" style="width: 70px; height: 70px; object-fit: contain; cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge">
    <div>
      <h2 style="margin: 0; font-size: 1.6em;">IEEE Student Branch Board & Membership</h2>
      <p style="margin: 3px 0 0 0; color: #666; font-size: 0.95em;">Official Executive Committee Postings and Chapter Credentials</p>
    </div>
  </div>
  <p style="color: #444;">Official records of election to the branch EXECOM along with international professional society membership credentials. <a href="{{ site.baseurl }}/projects#role-ieee-doc-head" style="text-decoration: underline; color: #00629B; font-weight: bold;">Read Role Details</a></p>

  <h4 style="color: #333; margin-bottom: 15px;">📋 Official EXECOM Board Groups</h4>
  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-bottom: 30px;">
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/ieee-execom-wie.jpeg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.85em; color: #555; margin-top: 5px;">IEEE Women in Engineering (WIE) Group Photo</p>
    </div>
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/ieee-execom-main.jpeg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.85em; color: #555; margin-top: 5px;">IEEE Student Branch Main Officer Board poster (Athul J: Documentation Head)</p>
    </div>
  </div>

  <h4 style="color: #333; margin-bottom: 15px;">📸 IEEE Annual General Meeting (AGM) Officer Oath & Group Photo</h4>
  <div style="display: grid; grid-template-columns: 1fr 1.3fr; gap: 20px; margin-bottom: 35px; align-items: start;">
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/ieee-agm-oath.png" alt="Elected Officers Taking the Student Leadership Pledge" style="border-radius: 8px; width: 100%; height: auto; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.85em; color: #555; margin-top: 5px;">Elected Officers Taking the Student Leadership Pledge</p>
    </div>
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/ieee-agm-group.jpg" alt="IEEE AGM Officer Group Photo" style="border-radius: 8px; width: 100%; height: auto; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.85em; color: #555; margin-top: 5px;">IEEE AGM Executive Committee Group Photo with Faculty Advisors</p>
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

<!-- SECTION 7: S.T.O.R.M. Chandra '25 & ISRO Space Expo Exhibition -->
<div id="storm-space-expo" style="margin-bottom: 60px;">
  <div style="display: flex; align-items: center; gap: 20px; margin-bottom: 15px;">
    <img src="{{ site.baseurl }}/images/storm-logo.png" alt="S.T.O.R.M. Logo" style="width: 70px; height: 70px; object-fit: contain; background: #000; border-radius: 50%; border: 2px solid #00629B; cursor: pointer; padding: 3px;" onclick="openModal(this.src)">
    <div>
      <h2 style="margin: 0; font-size: 1.6em;">S.T.O.R.M. Chandra '25 & ISRO Space Expo</h2>
      <p style="margin: 3px 0 0 0; color: #666; font-size: 0.95em;">ISRO "Space on Wheels" VSSC Space Expo Program</p>
    </div>
  </div>
  <p style="color: #444;">Highlights from our Association Day celebration hosting the Indian Space Research Organisation (ISRO) Vikram Sarabhai Space Centre (VSSC) exhibition. Delivered the formal Vote of Thanks speech and collaborated with my peer group to explain high-level space systems to visiting students. <a href="{{ site.baseurl }}/projects#role-storm-space-expo" style="text-decoration: underline; color: #00629B; font-weight: bold;">Read Role Details</a></p>

  <h4 style="color: #333; margin-bottom: 15px;">🏆 Academic Merits & Award Presentation Ceremonies</h4>
  <div style="display: grid; grid-template-columns: 1fr 1fr 0.8fr; gap: 15px; margin-bottom: 25px; align-items: end;">
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/storm-space-award-presentation.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.8em; color: #555; margin-top: 5px;">Mementos receiving ceremony from the chief guest on stage</p>
    </div>
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/storm-space-award-clapping.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.8em; color: #555; margin-top: 5px;">Award presentation with faculty and association panel members</p>
    </div>
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/athul-isro-expo-mementos.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.8em; color: #555; margin-top: 5px;">Close-up shot of the Department Topper awards</p>
    </div>
  </div>

  <h4 style="color: #333; margin-bottom: 15px;">🎤 Formal Ceremony & Event Branding</h4>
  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-bottom: 30px; align-items: start;">
    <div style="text-align: center;">
      <div style="overflow: hidden; border-radius: 12px; border: 1px solid #ccc; height: 420px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
        <img src="{{ site.baseurl }}/images/storm-space-vote-of-thanks.jpg" style="width: 100%; height: 100%; object-fit: cover; cursor: pointer;" onclick="openModal(this.src)">
      </div>
      <p style="font-size: 0.85em; color: #555; margin-top: 8px;">Athul J delivering the formal Vote of Thanks speech during the opening ceremony</p>
    </div>
    <div style="text-align: center;">
      <div style="overflow: hidden; border-radius: 12px; border: 1px solid #ccc; height: 420px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
        <!-- Fixed extension layout bug from .jpg to .jpeg to match your folder -->
        <img src="{{ site.baseurl }}/images/storm-space-poster.jpeg" style="width: 100%; height: 100%; object-fit: cover; object-position: center 30%; cursor: pointer;" onclick="openModal(this.src)">
      </div>
      <p style="font-size: 0.85em; color: #555; margin-top: 8px;">Official S.T.O.R.M. Association Day 'CHANDRA' Commemorative Space Expo Design</p>
    </div>
  </div>

  <h4 style="color: #333; margin-bottom: 15px;">🏛️ Approved Stage Ceremonies (On-Dais View)</h4>
  <div style="display: grid; grid-template-columns: 1.2fr 1fr; gap: 20px; margin-bottom: 30px;">
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/storm-dais-guest-gift.jpg" style="border-radius: 12px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.85em; color: #555; margin-top: 5px;">Honorable chief guest receiving our official association token gift on stage</p>
    </div>
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/storm-dais-principal-tribute.jpg" style="border-radius: 12px; width: 100%; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.85em; color: #555; margin-top: 5px;">Chief Guest presenting a formal token of tribute to our college Principal</p>
    </div>
  </div>

  <h4 style="color: #333; margin-bottom: 15px;">📸 Exhibition Records & Out-of-Dais Audience View</h4>
  <div style="display: grid; grid-template-columns: 1.2fr 1fr; gap: 20px; margin-bottom: 35px; align-items: start;">
    <div style="text-align: center;">
      <div style="overflow: hidden; border-radius: 12px; border: 1px solid #ccc; max-height: 480px; box-shadow: 0 4px 12px rgba(0,0,0,0.08);">
        <img src="{{ site.baseurl }}/images/isro-grid-view.jpg" style="width: 100%; height: auto; object-fit: cover; cursor: pointer;" onclick="openModal(this.src)">
      </div>
      <p style="font-size: 0.85em; color: #555; margin-top: 5px;">Student Interaction Logs: Explaining space expo modules to school teams</p>
    </div>
    <div style="text-align: center;">
      <div style="overflow: hidden; border-radius: 12px; border: 1px solid #ccc; max-height: 480px; box-shadow: 0 4px 12px rgba(0,0,0,0.08);">
        <img src="{{ site.baseurl }}/images/isro-expo-audience-view.jpg" style="width: 100%; height: auto; object-fit: cover; cursor: pointer;" onclick="openModal(this.src)">
      </div>
      <p style="font-size: 0.85em; color: #555; margin-top: 5px;">Out-of-Dais View: Student assembly attending the keynote presentations</p>
    </div>
  </div>

  <h4 style="color: #333; margin-bottom: 15px;">🚍 ISRO "Space on Wheels" Fleet Units</h4>
  <div style="display: grid; grid-template-columns: 1fr 1.15fr; gap: 20px; margin-bottom: 10px;">
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/isro-bus-front-view.jpg" alt="ISRO Bus Front View" style="border-radius: 12px; width: 100%; height: 320px; object-fit: cover; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.85em; color: #555; margin-top: 5px;">Front view of the ISRO Space on Wheels tour exhibition vehicle arriving on campus layout</p>
    </div>
    <div style="text-align: center;">
      <img src="{{ site.baseurl }}/images/isro-bus-side.jpg" alt="ISRO Bus Landscape View" style="border-radius: 12px; width: 100%; height: 320px; object-fit: cover; border: 1px solid #ccc; cursor: pointer;" onclick="openModal(this.src)">
      <p style="font-size: 0.85em; color: #555; margin-top: 5px;">High clarity landscape view of the parked mobile exhibition trailer showroom</p>
    </div>
  </div>
</div>

<hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;">

<!-- SECTION 8: STORM Association Day - Punalur Auto Show '25 -->
<div id="storm-25" style="margin-bottom: 60px;">
  <div style="display: flex; align-items: center; gap: 20px; margin-bottom: 15px;">
    <img src="{{ site.baseurl }}/images/storm-logo.png" alt="S.T.O.R.M. Logo" style="width: 70px; height: 70px; object-fit: contain; background: #000; border-radius: 50%; border: 2px solid #00629B; cursor: pointer; padding: 3px;" onclick="openModal(this.src)">
    <div>
      <h2 style="margin: 0; font-size: 1.6em;">S.T.O.R.M. Punalur Auto Show '25</h2>
      <p style="margin: 3px 0 0 0; color: #666; font-size: 0.95em;">Mechanical Engineering Association Early Event Logs</p>
    </div>
  </div>
  <p style="color: #444;">Supervised vehicle track paths, entry sorting grids, and visitor crowd parameters at the public Chemmanthoor Municipal Grounds. <a href="{{ site.baseurl }}/projects#role-autoshow-25" style="text-decoration: underline; color: #00629B; font-weight: bold;">Read Role Details</a></p>
  
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
</div>
