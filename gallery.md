---
layout: page
title: Gallery & Evidence
permalink: /gallery/
---

<!-- WhatsApp Style Profile View Layout Elements -->
<div id="imageModal" style="display: none; position: fixed; z-index: 9999; left: 0; top: 0; width: 100%; height: 100%; background-color: rgba(0,0,0,0.85); align-items: center; justify-content: center; cursor: pointer;" onclick="closeModal()">
  <img id="modalImg" style="max-width: 90%; max-height: 90%; border-radius: 8px; box-shadow: 0 4px 20px rgba(255,255,255,0.2);">
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

<!-- 1. IEEE Tink-Her-Hack Section -->
<div id="ieee-tinkherhack" style="margin-bottom: 60px;">
  <h2>IEEE: Tink-Her-Hack 4.0</h2>
  <p>Evidence of student event coordination and our official report review files. 
  <a href="{{ site.baseurl }}/projects#role-tink-her-hack" style="text-decoration: underline; color: #00629B;">Read Role Details</a></p>
  
  <div style="padding: 12px; background: #fafafa; border-radius: 8px; border: 1px solid #ddd; margin-bottom: 20px;">
    <strong>Official Document:</strong> <a href="{{ site.baseurl }}/assets/reports/Tink-Her-Hack_4.0_Report.pdf" target="_blank">Open Event Report PDF</a>
  </div>

  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px;">
    <img src="{{ site.baseurl }}/images/tink-her-hack-group.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
    <img src="{{ site.baseurl }}/images/tink-her-hack-ceremony.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
  </div>
</div>

<hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;">

<!-- 2. IEDC Startup Summit Section -->
<div id="ieee-iedc" style="margin-bottom: 60px;">
  <h2>IEDC Startup Summit 2026</h2>
  <p>Photos from the student delegate trip to the state convention.
  <a href="{{ site.baseurl }}/projects#role-iedc-summit" style="text-decoration: underline; color: #00629B;">Read Role Details</a></p>
  
  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px;">
    <img src="{{ site.baseurl }}/images/iedc-summit-group.jpeg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
    <img src="{{ site.baseurl }}/images/iedc-summit-kit.jpeg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
  </div>
</div>

<hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;">

<!-- 3. NRPF Annual Meet Section -->
<div id="nss-nrpf" style="margin-bottom: 60px;">
  <h2>NRPF Annual Meet</h2>
  <p>Our college group pictures from the All-Kerala meeting.
  <a href="{{ site.baseurl }}/projects#role-nrpf-meet" style="text-decoration: underline; color: #00629B;">Read Role Details</a></p>
  
  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-bottom: 15px;">
    <img src="{{ site.baseurl }}/images/nrpf-all-kerala-ucs.JPG" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
    <img src="{{ site.baseurl }}/images/nrpf-regional-group.jpeg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
  </div>
  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px;">
    <img src="{{ site.baseurl }}/images/nrpf-dinner-arrangements.jpeg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
    <img src="{{ site.baseurl }}/images/nrpf-registration-pec.JPG" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
  </div>
</div>

<hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;">

<!-- 4. Aapda Mitra Training Section -->
<div id="aapda-mitra" style="margin-bottom: 60px;">
  <h2>Aapda Mitra: 7-Day Residential Training</h2>
  <p>Pictures from our emergency safety camp.
  <a href="{{ site.baseurl }}/projects#role-aapda-mitra" style="text-decoration: underline; color: #00629B;">Read Role Details</a></p>

  <div style="display: grid; grid-template-columns: 1fr 1.5fr; gap: 20px; align-items: start;">
    <img src="{{ site.baseurl }}/images/aapda-mitra-frame.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
    <div>
      <img src="{{ site.baseurl }}/images/aapda-mitra-group.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc; margin-bottom: 15px;">
      <div style="padding: 15px; background: #f0fbff; border-radius: 8px; text-align: center; border: 1px solid #00c6ff;">
        <h4 style="margin: 0 0 10px 0;">🎬 Camp Video Diary</h4>
        <a href="https://youtube.com/shorts/gs9gDMprpIc" target="_blank" style="font-weight: bold; text-decoration: underline; color: #00629B;">Watch Camp Memories on YouTube</a>
      </div>
    </div>
  </div>
</div>

<hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;">

<!-- 5. STORM Association Autoshow Section -->
<div id="association-storm" style="margin-bottom: 60px;">
  <div style="display: flex; align-items: center; gap: 20px; margin-bottom: 15px;">
    <!-- Clickable Interactive Logo with Fix for Letter Cutoffs -->
    <img src="{{ site.baseurl }}/images/storm-logo.png" alt="S.T.O.R.M. Logo" style="width: 85px; height: 85px; object-fit: contain; background: #000; border-radius: 50%; border: 2px solid #00629B; cursor: pointer; padding: 3px;" onclick="openModal(this.src)" title="Click to view full image">
    <div>
      <h2 style="margin: 0; font-size: 1.6em;">Mechanical Engineering Association: STORM</h2>
      <p style="margin: 3px 0 0 0; color: #666; font-size: 0.95em;">Sovereign Technological Organisation for Royal Mech (PEC)</p>
    </div>
  </div>
  <p style="color: #444;">Photos and media updates from our annual automobile exhibition events.</p>

  <!-- Sub-section: Autoshow 25 -->
  <div id="storm-25" style="margin-bottom: 40px; margin-top: 25px; padding: 20px; background: #fafafa; border-radius: 12px; border: 1px solid #e0e0e0;">
    <h3 style="margin-top: 0; color: #00629B;">🏎️ Punalur Auto Show '25</h3>
    <p><a href="{{ site.baseurl }}/projects#role-autoshow-25" style="text-decoration: underline; color: #00629B; font-weight: bold;">Read Role Details</a></p>
    
    <h4 style="color: #333; margin-bottom: 10px;">📋 Event Posters & Promotional Materials</h4>
    <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px; margin-bottom: 20px;">
      <img src="{{ site.baseurl }}/images/storm-25-poster-main.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
      <img src="{{ site.baseurl }}/images/storm-25-poster-malabari.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
      <img src="{{ site.baseurl }}/images/storm-25-poster-madmax.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
    </div>

    <h4 style="color: #333; margin-bottom: 10px;">📸 Exhibition Grounds & Vehicle Coordination</h4>
    <div style="display: grid; grid-template-columns: 1fr 1.2fr; gap: 15px; margin-bottom: 20px;">
      <img src="{{ site.baseurl }}/images/storm-25-entry-line.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
      <img src="{{ site.baseurl }}/images/storm-25-ground-circle.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
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

  <!-- Sub-section: Autoshow 26 -->
  <div id="storm-26" style="margin-top: 40px; padding: 20px; background: #fafafa; border-radius: 12px; border: 1px solid #e0e0e0;">
    <h3 style="color: #00629B; margin-top: 0;">🚀 Punalur Auto Show '26</h3>
    <p><a href="{{ site.baseurl }}/projects#role-autoshow-26" style="text-decoration: underline; color: #00629B; font-weight: bold;">Read Role Details</a></p>
    
    <h4 style="color: #333; margin-bottom: 15px;">📸 Staging & Exhibition Photos</h4>
    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px; margin-bottom: 20px;">
      <img src="{{ site.baseurl }}/images/storm-26-athul-single.jpeg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
      <img src="{{ site.baseurl }}/images/storm-26-athul-batman.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
    </div>

    <h4 style="color: #333; margin-bottom: 15px;">🌟 S.T.O.R.M. Association Team & Classmates</h4>
    <div style="text-align: center; margin-bottom: 25px;">
      <img src="{{ site.baseurl }}/images/storm-26-class-group-main.jpeg" style="border-radius: 12px; width: 100%; height: auto; border: 2px solid #00629B;">
      <p style="font-size: 0.9em; color: #555; margin-top: 8px;">Our final core student crew group picture at the public ground space.</p>
    </div>

    <!-- Official Showcase Graphics Section Fixed With Correct .jpg Storage Matches -->
    <h4 style="color: #333; margin-bottom: 12px;">📋 Official Showcase Feature Graphics</h4>
    
    <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px; margin-bottom: 15px;">
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-main.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">Official Main Poster</p>
      </div>
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-ratroad.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">'Rat Road' Custom Build</p>
      </div>
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-gonz.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">'Gonz Spec' SUV Build</p>
      </div>
    </div>

    <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px; margin-bottom: 15px;">
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-petric.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">'Petric' Custom Wrap Build</p>
      </div>
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-sheriff.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">'Sheriff' Custom Modification</p>
      </div>
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-stranger.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">'Stranger Things' Build</p>
      </div>
    </div>

    <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px; margin-bottom: 25px;">
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-criminal.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">'Criminal' Scissor Wrap</p>
      </div>
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-batman1.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">'Batman' Skyline Feature</p>
      </div>
      <div style="text-align: center;">
        <img src="{{ site.baseurl }}/images/storm-26-poster-coke.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
        <p style="font-size: 0.8em; color: #555; margin-top: 5px;">'Coca-Cola' Stance Build</p>
      </div>
    </div>

    <h4 style="color: #333; margin-bottom: 12px;">📸 On-Field Layout Metrics & Video Clips</h4>
    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px; margin-bottom: 15px;">
      <img src="{{ site.baseurl }}/images/storm-26-arena-lineup.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
      <img src="{{ site.baseurl }}/images/storm-26-ground-display.jpg" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
    </div>
    <div style="display: grid; grid-template-columns: 1.2fr 1fr 1fr; gap: 15px; margin-bottom: 25px;">
      <img src="{{ site.baseurl }}/images/storm-26-exhaust-flame.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
      <img src="{{ site.baseurl }}/images/storm-26-ratroad-front.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
      <img src="{{ site.baseurl }}/images/storm-26-bmw-spider.png" style="border-radius: 8px; width: 100%; border: 1px solid #ccc;">
    </div>

    <!-- Live Upload Updates -->
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
