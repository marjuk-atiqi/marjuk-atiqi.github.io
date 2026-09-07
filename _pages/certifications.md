---
permalink: /certifications/
title: "Professional Certifications"
---

<!-- প্রফেশনাল সার্টিফিকেশন কার্ড -->
<div style="background: #ffffff; border-top: 4px solid #0f172a; border-radius: 8px; padding: 24px; margin-bottom: 20px; box-shadow: 0 10px 15px -3px rgba(0,0,0,0.05); display: flex; gap: 20px; align-items: center;">
  
  <!-- ছোট থাম্বনেইল বা ব্যাজ (এটিতে ক্লিক করলে পপআপ হবে না, শুধু নরমাল দেখাবে) -->
  <div style="flex-shrink: 0;">
    <img src="/images/your-certificate.png" alt="Certificate Badge" style="width: 70px; height: 70px; object-fit: cover; border-radius: 6px; border: 1px solid #e2e8f0;">
  </div>

  <!-- সার্টিফিকেটের বিবরণ -->
  <div style="flex-grow: 1;">
    <h3 style="margin: 0 0 6px 0; font-size: 1.2rem; color: #1f2937;">Oracle Database SQL Certified Expert</h3>
    <p style="margin: 0 0 8px 0; color: #4b5563; font-size: 0.95rem; font-weight: 600;">
      Oracle University, USA &nbsp;|&nbsp; Issued: 2012
    </p>
    <p style="margin: 0; color: #6b7280; font-size: 0.9rem;">
      Credential ID: 12345678 
      <!-- শুধু এই বাটনে ক্লিক করলেই পপআপ প্রিভিউ দেখাবে -->
      <span style="color: #1877F2; cursor: pointer; margin-left: 10px; font-weight: 600;" onclick="openModal('/images/your-certificate.png')">[View Certificate]</span>
    </p>
  </div>
</div>

<!-- পপআপ উইন্ডো (Modal) এর জন্য কোড -->
<div id="certModal" style="display: none; position: fixed; z-index: 9999; left: 0; top: 0; width: 100%; height: 100%; background-color: rgba(0,0,0,0.8); backdrop-filter: blur(4px); align-items: center; justify-content: center;" onclick="closeModal()">
  <span style="position: absolute; top: 20px; right: 35px; color: #ffffff; font-size: 40px; font-weight: bold; cursor: pointer;" onclick="closeModal()">&times;</span>
  <img id="modalImg" style="max-width: 85%; max-height: 85%; border-radius: 8px; box-shadow: 0 20px 25px -5px rgba(0,0,0,0.5);" onclick="event.stopPropagation()">
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
