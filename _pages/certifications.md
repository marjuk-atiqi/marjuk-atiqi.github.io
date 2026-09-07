---
permalink: /certifications/
title: "Professional Certifications"
---

<!-- প্রফেশনাল সার্টিফিকেশন কার্ড -->
<div style="background: #ffffff; border-left: 4px solid #0f172a; border-radius: 8px; padding: 24px; margin-bottom: 20px; box-shadow: 0 10px 15px -3px rgba(0,0,0,0.05); display: flex; gap: 20px; align-items: center;">
  
  <!-- সার্টিফিকেট থাম্বনেইল বা ব্যাজ -->
  <div style="flex-shrink: 0;">
    <img src="/images/oracle-sql-cert.png" alt="Certificate Badge" style="width: 70px; height: 70px; object-fit: cover; border-radius: 6px; border: 1px solid #e2e8f0;">
  </div>

  <!-- সার্টিফিকেটের বিবরণ -->
  <div style="flex-grow: 1;">
    <h3 style="margin: 0 0 6px 0; font-size: 1.2rem; color: #1f2937;">Oracle Database SQL Certified Expert</h3>
    <p style="margin: 0 0 10px 0; color: #4b5563; font-size: 0.95rem; font-weight: 600;">
      Oracle University, USA &nbsp;|&nbsp; Issued: 2012
    </p>
    
    <div style="display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; gap: 10px;">
      <span style="color: #6b7280; font-size: 0.9rem;">Credential ID: 12345678</span>
      
      <!-- মডার্ন সলিড ব্লু বাটন -->
      <button onclick="openModal('/images/oracle-sql-cert.png')" style="background-color: #1877F2; color: #ffffff; border: none; padding: 6px 14px; border-radius: 6px; font-size: 0.85rem; font-weight: 600; cursor: pointer; display: inline-flex; align-items: center; gap: 6px; box-shadow: 0 2px 4px rgba(24,119,242,0.2); transition: background-color 0.2s;" onmouseover="this.style.backgroundColor='#166fe5'" onmouseout="this.style.backgroundColor='#1877F2'">
        View Certificate
      </button>
    </div>
  </div>
</div>

<!-- পপআপ উইন্ডো (Modal) এবং ফিক্সড ক্লোজ আইকন -->
<div id="certModal" style="display: none; position: fixed; z-index: 99999; left: 0; top: 0; width: 100%; height: 100%; background-color: rgba(0,0,0,0.9); backdrop-filter: blur(5px); align-items: center; justify-content: center;" onclick="closeModal()">
  
  <!-- ক্লোজ আইকন (ওপরের ডান কোণায় স্পষ্ট গোল বাটন) -->
  <div style="position: fixed; top: 20px; right: 25px; background: #ffffff; width: 40px; height: 40px; border-radius: 50%; display: flex; align-items: center; justify-content: center; cursor: pointer; box-shadow: 0 4px 10px rgba(0,0,0,0.3); z-index: 100000;" onclick="closeModal()">
    <span style="color: #000000; font-size: 26px; font-weight: bold; line-height: 1;">&times;</span>
  </div>

  <!-- বড় প্রিভিউ ইমেজ -->
  <img id="modalImg" style="max-width: 85%; max-height: 85%; border-radius: 8px; box-shadow: 0 25px 50px -12px rgba(0,0,0,0.7);" onclick="event.stopPropagation()">
</div>

<!-- জাভাস্ক্রিপ্ট কোড -->
<script>
  function openModal(imgSrc) {
    document.getElementById('modalImg').src = imgSrc;
    document.getElementById('certModal').style.display = 'flex';
  }
  function closeModal() {
    document.getElementById('certModal').style.display = 'none';
  }
</script>
