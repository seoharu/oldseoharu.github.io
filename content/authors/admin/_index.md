---
# Display name
title: CHOI SEOYEON (최서연)

# Is this the primary user of the site?
superuser: true

# Role/position
role: ''

# Status emoji
status:
  icon: 💻

# Organizations/Affiliations
organizations:
- name: JBNU-MACS
  url: "https://jbnu.macs.or.kr/"

# Short bio (displayed in user profile at end of posts)
bio: My research interests include distributed robotics, mobile computing and programmable matter.

#interests:
#- Artificial Intelligence
#- Computational Linguistics
#- Information Retrieval

education:
 courses:
 - course: BSc in Division of Computer Science and Engineering 
   institution: JEONBUK NATIONAL UNIVERSITY
   start_year: 2022
   status: Ongoing

# Social/Academic Networking
# For available icons, see: https://docs.hugoblox.com/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
  - icon: envelope
    icon_pack: fas
    link: '#'
    onclick: 'showEmailPopup()' 
    # link: 'about/#contact' # For a direct email link, use "mailto:test@example.org".
    # <p>Contact me via email: <a href="mailto:yunseul@jbnu.ac.kr">yunseul@jbnu.ac.kr</a></p>

  - icon: github
    icon_pack: fab
    link: https://github.com/seoharu
  # - icon: twitter
  #   icon_pack: fab
  #   link: https://twitter.com/wowchemy
  # - icon: instagram
  #   icon_pack: fab
  #   link: https://instagram.com/geocushen

# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
# email: ""
---

CHOI SEOYEON is currently pursuing a bachelor's degree at university, with a double major in Medical AI. 
Additionally, I am working as an undergraduate researcher in a lab, where I am involved in projects related to my main area of interest, Medical AI.

{{< icon name="download" pack="fas" >}} {{< staticref "uploads/resume.pdf" "newtab" >}}Download{{< /staticref >}} my resumé as a PDF.

<script>
  function showEmailPopup() {
    document.getElementById("emailPopup").style.display = "block";
  }

  function closeEmailPopup() {
    document.getElementById("emailPopup").style.display = "none";
  }
</script>

<div id="emailPopup" class="modal" style="display:none;">
  <div class="modal-content">
    <span class="close" onclick="closeEmailPopup()">&times;</span>
    <p>Contact me via email: <a href="mailto:yunseul@jbnu.ac.kr">yunseul@jbnu.ac.kr</a></p>
  </div>
</div>

<style>
.modal {
  position: fixed;
  z-index: 1;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0,0,0,0.5);
}

.modal-content {
  background-color: white;
  margin: 15% auto;
  padding: 20px;
  width: 80%;
}

.close {
  float: right;
  font-size: 28px;
  cursor: pointer;
}
</style>
