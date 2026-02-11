<!doctype html>
<html lang="id"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <meta name="description" content="Portal resmi MEDIA OSIM- Organisasi Siswa Intra Sekolah dengan sistem digital modern, transparan, dan akuntabel">
  <title>MEDIA OSIM| Official Site</title> 
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;800&amp;display=swap" rel="stylesheet"> 
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css"> 
  
  <style>
    /* === VARIABEL CSS === */
    :root {
        --bg-color: #F0F4F8; /* Default Light Mode */
        --text-color: #0F172A;
        --accent-color: #1E40AF;
        --secondary-bg: #FFFFFF;
        --nav-bg: rgba(240, 244, 248, 0.85);
        --transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
        --news-blue: #003366;
        --news-red: #CC0000;
        --news-yellow: #FF9900;
        --news-gray: #555555;
        --success-color: #10B981;
        --warning-color: #F59E0B;
        --info-color: #3B82F6;
    }

    .dark-mode {
        --bg-color: #0A192F; 
        --text-color: #ffffff;
        --accent-color: #C5A059; 
        --secondary-bg: #112240;
        --nav-bg: rgba(10, 25, 47, 0.85);
        --news-blue: #4A90E2;
        --news-gray: #CCCCCC;
        --success-color: #34D399;
        --warning-color: #FBBF24;
        --info-color: #60A5FA;
    }

    /* === RESET & BASE STYLES === */
    * { 
        margin: 0; 
        padding: 0; 
        box-sizing: border-box; 
        font-family: 'Plus Jakarta Sans', sans-serif; 
    }

    body {
        background-color: var(--bg-color);
        color: var(--text-color);
        transition: var(--transition);
        overflow-x: hidden;
        min-height: 100vh;
    }

    /* === NAVIGASI === */
    nav {
        position: fixed;
        top: 0; 
        left: 0; 
        width: 100%;
        padding: 25px 8%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        z-index: 1000;
        background: var(--nav-bg);
        backdrop-filter: blur(15px);
        border-bottom: 1px solid rgba(30, 64, 175, 0.1);
    }

    .logo {
        font-size: 1.6rem;
        font-weight: 800;
        color: var(--text-color);
        display: flex;
        align-items: center;
        gap: 12px;
    }

    .logo h1 {
        font-size: 1.6rem;
        margin: 0;
        font-weight: 800;
    }

    .nav-controls {
        display: flex;
        align-items: center;
        gap: 25px;
    }

    .theme-btn {
        background: var(--secondary-bg);
        border: 1px solid var(--accent-color);
        color: var(--accent-color);
        width: 45px; 
        height: 45px;
        border-radius: 50%;
        cursor: pointer;
        display: flex; 
        align-items: center; 
        justify-content: center;
        transition: var(--transition);
        outline: none;
    }

    .theme-btn:hover, 
    .theme-btn:focus {
        transform: scale(1.05);
    }

    /* === HAMBURGER MENU === */
    .hamburger {
        cursor: pointer;
        width: 30px;
        height: 20px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        z-index: 1001;
    }

    .hamburger span {
        display: block;
        height: 3px;
        width: 100%;
        background: var(--text-color);
        border-radius: 3px;
        transition: var(--transition);
    }

    .hamburger.active span:nth-child(1) { 
        transform: translateY(8.5px) rotate(45deg); 
    }
    .hamburger.active span:nth-child(2) { 
        opacity: 0; 
    }
    .hamburger.active span:nth-child(3) { 
        transform: translateY(-8.5px) rotate(-45deg); 
    }

    /* === SIDE MENU === */
    .side-menu {
        position: fixed;
        top: 0; 
        right: -100%;
        width: 100%; 
        height: 100vh;
        background: var(--bg-color);
        z-index: 900;
        display: grid;
        grid-template-columns: 1fr 1fr;
        transition: 0.6s ease-in-out;
        overflow-y: auto;
    }

    .side-menu.active { 
        right: 0; 
    }

    .menu-links {
        display: flex;
        flex-direction: column;
        padding: 120px 10% 50px 15%;
        gap: 20px;
    }

    .menu-section-title {
        font-size: 0.8rem;
        text-transform: uppercase;
        letter-spacing: 2px;
        color: var(--accent-color);
        margin-bottom: 5px;
        opacity: 0.8;
    }

    .menu-item {
        text-decoration: none;
        color: var(--text-color);
        display: flex;
        align-items: flex-start;
        gap: 20px;
        transition: 0.3s;
        padding: 15px;
        border-radius: 12px;
        cursor: pointer;
        outline: none;
    }

    .menu-item:hover, 
    .menu-item:focus {
        background: rgba(30, 64, 175, 0.1);
        transform: translateX(10px);
    }

    .menu-item i {
        font-size: 1.8rem;
        color: var(--accent-color);
        width: 40px;
        text-align: center;
        margin-top: 5px;
    }

    .menu-text h2 { 
        font-size: 1.6rem; 
        font-weight: 800; 
    }
    .menu-text p { 
        font-size: 0.9rem; 
        opacity: 0.6; 
        margin-top: 4px; 
    }

    .menu-extra {
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        padding: 120px 10% 50px 10%;
        border-left: 1px solid rgba(30, 64, 175, 0.1);
    }

    .quote-box {
        margin: 30px 0;
        padding: 25px;
        border-left: 4px solid var(--accent-color);
        background: var(--secondary-bg);
        border-radius: 0 15px 15px 0;
    }

    /* === HERO SECTION === */
    .hero {
        height: 100vh;
        display: flex;
        flex-direction: column;
        justify-content: center;
        padding: 0 8%;
    }

    .hero-title {
        font-size: clamp(2.5rem, 8vw, 5rem);
        font-weight: 800;
        line-height: 1.1;
    }

    .hero-title span { 
        color: var(--accent-color); 
    }

    /* === INFO GRID === */
    .info-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 50px;
        padding: 100px 8%;
        background: var(--secondary-bg);
    }

    .info-card h3 {
        color: var(--accent-color);
        font-size: 1.2rem;
        margin-bottom: 25px;
        text-transform: uppercase;
        display: flex;
        align-items: center; 
        gap: 10px;
    }

    .info-list { 
        list-style: none; 
    }
    .info-list li {
        display: flex;
        align-items: center;
        gap: 15px;
        margin-bottom: 15px;
        opacity: 0.9;
    }

    .info-list i { 
        color: var(--accent-color); 
        width: 20px; 
        text-align: center; 
    }

    /* === PAGE CONTENT === */
    .page-content {
        display: none;
        min-height: 100vh;
        padding: 120px 8% 60px;
    }

    .page-content.active {
        display: block;
    }

    /* === PENGUMUMAN PAGE === */
    .announcement-section {
        padding: 20px 0;
        background-color: var(--bg-color);
        max-width: 1200px;
        margin: 0 auto;
    }

    .section-title {
        border-left: 5px solid var(--news-blue);
        padding-left: 15px;
        margin-bottom: 40px;
        font-size: 1.8rem;
        font-weight: 800;
        color: var(--text-color);
        text-transform: uppercase;
        letter-spacing: 1px;
    }

    .news-container {
        display: flex;
        flex-direction: column;
        gap: 30px;
    }

    .news-card {
        display: flex;
        background: var(--secondary-bg);
        margin-bottom: 25px;
        border-radius: 10px;
        overflow: hidden;
        box-shadow: 0 4px 12px rgba(0,0,0,0.08);
        transition: var(--transition);
        border: 1px solid rgba(30, 64, 175, 0.1);
    }

    .news-card:hover,
    .news-card:focus-within {
        transform: translateY(-8px);
        box-shadow: 0 12px 25px rgba(0,0,0,0.15);
    }

    .news-image {
        width: 300px;
        min-height: 250px;
        overflow: hidden;
        flex-shrink: 0;
        position: relative;
    }

    .news-image img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        transition: transform 0.5s ease;
    }

    .news-card:hover .news-image img,
    .news-card:focus-within .news-image img {
        transform: scale(1.05);
    }

    .news-image-placeholder {
        width: 100%;
        height: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        background: linear-gradient(135deg, var(--accent-color) 0%, rgba(30, 64, 175, 0.7) 100%);
        color: white;
        font-size: 2.5rem;
    }

    .news-content {
        padding: 30px;
        flex: 1;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }

    .category {
        font-size: 0.75rem;
        color: var(--news-blue);
        font-weight: 800;
        text-transform: uppercase;
        letter-spacing: 1px;
        padding: 5px 12px;
        background: rgba(0, 51, 102, 0.1);
        border-radius: 4px;
        display: inline-block;
        margin-bottom: 15px;
    }

    .category.important {
        background: rgba(204, 0, 0, 0.1);
        color: var(--news-red);
    }

    .category.update {
        background: rgba(255, 153, 0, 0.1);
        color: var(--news-yellow);
    }

    .category.info {
        background: rgba(30, 64, 175, 0.1);
        color: var(--accent-color);
    }

    .news-headline {
        margin: 15px 0;
        font-size: 1.6rem;
        font-weight: 700;
        color: var(--text-color);
        line-height: 1.3;
    }

    .news-meta {
        font-size: 0.85rem;
        color: var(--news-gray);
        margin-bottom: 20px;
        display: flex;
        align-items: center;
        gap: 15px;
    }

    .news-meta i {
        margin-right: 5px;
        color: var(--accent-color);
    }

    .news-excerpt {
        color: var(--news-gray);
        line-height: 1.7;
        margin-bottom: 25px;
        font-size: 1rem;
    }

    .read-more {
        display: inline-flex;
        align-items: center;
        margin-top: 10px;
        color: var(--news-blue);
        text-decoration: none;
        font-weight: 700;
        transition: var(--transition);
        gap: 8px;
        cursor: pointer;
        background: none;
        border: none;
        font-size: 1rem;
    }

    .read-more:hover,
    .read-more:focus {
        color: var(--accent-color);
        gap: 12px;
        outline: none;
    }

    /* === PROGRAM KERJA PAGE === */
    .proker-container {
        width: 100%;
        max-width: 1200px;
        margin: 0 auto;
    }

    .proker-header {
        margin-bottom: 40px;
    }

    .proker-title {
        font-size: clamp(2rem, 5vw, 3.5rem);
        font-weight: 800;
        margin-bottom: 15px;
        line-height: 1.2;
        color: var(--text-color);
    }

    .proker-title span {
        color: var(--accent-color);
    }

    .proker-description {
        font-size: 1.1rem;
        max-width: 700px;
        opacity: 0.8;
        line-height: 1.6;
        margin-bottom: 30px;
    }

    .proker-filter {
        display: flex;
        gap: 15px;
        margin-bottom: 40px;
        flex-wrap: wrap;
    }

    .filter-btn {
        padding: 10px 24px;
        background: transparent;
        border: 2px solid var(--accent-color);
        color: var(--accent-color);
        border-radius: 8px;
        font-weight: 600;
        cursor: pointer;
        transition: var(--transition);
        font-size: 0.95rem;
        outline: none;
    }

    .filter-btn:hover,
    .filter-btn:focus {
        background: rgba(30, 64, 175, 0.1);
    }

    .filter-btn.active {
        background: var(--accent-color);
        color: var(--bg-color);
    }

    .proker-grid {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
        gap: 30px;
        margin-bottom: 50px;
    }

    .proker-card {
        background: var(--secondary-bg);
        border-radius: 16px;
        overflow: hidden;
        box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
        transition: var(--transition);
        border: 1px solid rgba(30, 64, 175, 0.1);
        display: flex;
        flex-direction: column;
        height: 100%;
    }

    .proker-card:hover,
    .proker-card:focus-within {
        transform: translateY(-10px);
        box-shadow: 0 15px 35px rgba(0, 0, 0, 0.15);
        border-color: var(--accent-color);
    }

    .proker-image {
        width: 100%;
        height: 200px;
        overflow: hidden;
        position: relative;
    }

    .proker-image-content {
        width: 100%;
        height: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        color: white;
        font-size: 2.5rem;
        position: relative;
        z-index: 2;
    }

    .proker-image-overlay {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: linear-gradient(135deg, rgba(30, 64, 175, 0.8), rgba(16, 185, 129, 0.8));
        z-index: 1;
    }

    .proker-card:nth-child(2) .proker-image-overlay {
        background: linear-gradient(135deg, rgba(245, 158, 11, 0.8), rgba(239, 68, 68, 0.8));
    }

    .proker-card:nth-child(3) .proker-image-overlay {
        background: linear-gradient(135deg, rgba(59, 130, 246, 0.8), rgba(147, 51, 234, 0.8));
    }

    .proker-card:nth-child(4) .proker-image-overlay {
        background: linear-gradient(135deg, rgba(16, 185, 129, 0.8), rgba(59, 130, 246, 0.8));
    }

    .proker-card:nth-child(5) .proker-image-overlay {
        background: linear-gradient(135deg, rgba(245, 158, 11, 0.8), rgba(16, 185, 129, 0.8));
    }

    .proker-card:nth-child(6) .proker-image-overlay {
        background: linear-gradient(135deg, rgba(239, 68, 68, 0.8), rgba(59, 130, 246, 0.8));
    }

    .proker-content {
        padding: 25px;
        flex: 1;
        display: flex;
        flex-direction: column;
    }

    .proker-name {
        font-size: 1.4rem;
        font-weight: 700;
        margin-bottom: 15px;
        color: var(--text-color);
        line-height: 1.3;
    }

    .proker-description-card {
        color: var(--news-gray);
        line-height: 1.6;
        margin-bottom: 20px;
        flex: 1;
        font-size: 0.95rem;
    }

    .proker-tags {
        display: flex;
        gap: 10px;
        margin-bottom: 20px;
        flex-wrap: wrap;
    }

    .proker-tag {
        padding: 6px 14px;
        border-radius: 20px;
        font-size: 0.8rem;
        font-weight: 600;
        text-transform: uppercase;
        letter-spacing: 0.5px;
    }

    .tag-performance {
        background: rgba(16, 185, 129, 0.15);
        color: var(--success-color);
        border: 1px solid rgba(16, 185, 129, 0.3);
    }

    .tag-potential {
        background: rgba(245, 158, 11, 0.15);
        color: var(--warning-color);
        border: 1px solid rgba(245, 158, 11, 0.3);
    }

    .tag-social {
        background: rgba(59, 130, 246, 0.15);
        color: var(--info-color);
        border: 1px solid rgba(59, 130, 246, 0.3);
    }

    .tag-live {
        background: rgba(239, 68, 68, 0.15);
        color: #EF4444;
        border: 1px solid rgba(239, 68, 68, 0.3);
    }

    .proker-footer {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding-top: 20px;
        border-top: 1px solid rgba(30, 64, 175, 0.1);
        margin-top: auto;
    }

    .proker-status {
        display: flex;
        align-items: center;
        gap: 8px;
        font-size: 0.9rem;
        font-weight: 600;
    }

    .status-dot {
        width: 10px;
        height: 10px;
        border-radius: 50%;
    }

    .status-ongoing {
        background: var(--success-color);
    }

    .status-planned {
        background: var(--warning-color);
    }

    .status-completed {
        background: var(--accent-color);
    }

    .proker-date {
        font-size: 0.85rem;
        opacity: 0.7;
    }

    .proker-stats {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 20px;
        margin-bottom: 50px;
        max-width: 800px;
    }

    .stat-card {
        background: var(--secondary-bg);
        padding: 25px;
        border-radius: 12px;
        text-align: center;
        transition: var(--transition);
        border: 1px solid rgba(30, 64, 175, 0.1);
    }

    .stat-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
    }

    .stat-number {
        font-size: 2.5rem;
        font-weight: 800;
        margin-bottom: 10px;
    }

    .stat-total .stat-number {
        color: var(--accent-color);
    }

    .stat-ongoing .stat-number {
        color: var(--success-color);
    }

    .stat-completed .stat-number {
        color: var(--warning-color);
    }

    .stat-label {
        font-size: 0.95rem;
        opacity: 0.8;
    }

    /* === PROFIL PAGE === */
    .profil-hierarchy {
        width: 100%;
        max-width: 1200px;
        margin: 40px auto 0;
    }

    .hierarchy-nav {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 20px;
        margin-bottom: 40px;
    }

    .hierarchy-card {
        background: var(--secondary-bg);
        border-radius: 15px;
        padding: 30px;
        text-align: center;
        cursor: pointer;
        transition: var(--transition);
        border: 2px solid transparent;
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 15px;
        outline: none;
    }

    .hierarchy-card:hover,
    .hierarchy-card:focus {
        transform: translateY(-10px);
        border-color: var(--accent-color);
        box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
    }

    .hierarchy-card.active {
        border-color: var(--accent-color);
        background: rgba(30, 64, 175, 0.05);
    }

    .hierarchy-icon {
        width: 80px;
        height: 80px;
        border-radius: 50%;
        background: linear-gradient(135deg, var(--accent-color) 0%, rgba(30, 64, 175, 0.8) 100%);
        display: flex;
        align-items: center;
        justify-content: center;
        color: white;
        font-size: 2rem;
        margin-bottom: 10px;
    }

    .hierarchy-card h3 {
        font-size: 1.3rem;
        margin-bottom: 10px;
        color: var(--text-color);
    }

    .hierarchy-card p {
        font-size: 0.9rem;
        opacity: 0.7;
        line-height: 1.5;
    }

    /* === DETAIL SECTION === */
    .detail-section {
        display: none;
        background: var(--secondary-bg);
        border-radius: 15px;
        padding: 40px;
        margin-top: 30px;
        animation: fadeIn 0.5s ease;
    }

    @keyframes fadeIn {
        from { 
            opacity: 0; 
            transform: translateY(20px); 
        }
        to { 
            opacity: 1; 
            transform: translateY(0); 
        }
    }

    .detail-section.active {
        display: block;
    }

    .detail-header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 30px;
        padding-bottom: 20px;
        border-bottom: 2px solid rgba(30, 64, 175, 0.1);
    }

    .detail-title {
        font-size: 1.8rem;
        font-weight: 700;
        color: var(--accent-color);
        display: flex;
        align-items: center;
        gap: 15px;
    }

    .back-btn {
        padding: 10px 20px;
        background: transparent;
        border: 2px solid var(--accent-color);
        color: var(--accent-color);
        border-radius: 8px;
        font-weight: 600;
        cursor: pointer;
        transition: var(--transition);
        display: flex;
        align-items: center;
        gap: 8px;
        outline: none;
    }

    .back-btn:hover,
    .back-btn:focus {
        background: var(--accent-color);
        color: var(--bg-color);
    }

    .detail-content {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
        gap: 25px;
    }

    .position-card {
        background: var(--bg-color);
        border-radius: 12px;
        padding: 25px;
        transition: var(--transition);
        border: 1px solid rgba(30, 64, 175, 0.1);
    }

    .position-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
    }

    .position-header {
        display: flex;
        align-items: center;
        gap: 15px;
        margin-bottom: 15px;
    }

    .position-icon {
        width: 50px;
        height: 50px;
        border-radius: 50%;
        background: rgba(30, 64, 175, 0.1);
        display: flex;
        align-items: center;
        justify-content: center;
        color: var(--accent-color);
        font-size: 1.2rem;
    }

    .position-title {
        font-size: 1.2rem;
        font-weight: 700;
        color: var(--text-color);
    }

    .position-desc {
        color: var(--news-gray);
        line-height: 1.6;
        margin-bottom: 15px;
        font-size: 0.95rem;
    }

    .member-list {
        list-style: none;
        margin-top: 15px;
    }

    .member-list li {
        padding: 12px 0;
        border-bottom: 1px solid rgba(0, 0, 0, 0.08);
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    .member-list li:last-child {
        border-bottom: none;
    }

    .member-info {
        display: flex;
        align-items: center;
        gap: 12px;
    }

    .member-avatar {
        width: 40px;
        height: 40px;
        border-radius: 50%;
        background: linear-gradient(135deg, var(--accent-color) 0%, rgba(30, 64, 175, 0.7) 100%);
        display: flex;
        align-items: center;
        justify-content: center;
        color: white;
        font-weight: 700;
        font-size: 0.9rem;
    }

    .member-details {
        display: flex;
        flex-direction: column;
    }

    .member-name {
        font-weight: 600;
        font-size: 1rem;
    }

    .member-class {
        font-size: 0.85rem;
        opacity: 0.7;
    }

    .view-detail {
        padding: 6px 15px;
        background: transparent;
        border: 1px solid var(--accent-color);
        color: var(--accent-color);
        border-radius: 6px;
        font-size: 0.8rem;
        cursor: pointer;
        transition: var(--transition);
        outline: none;
    }

    .view-detail:hover,
    .view-detail:focus {
        background: var(--accent-color);
        color: var(--bg-color);
    }

    /* === KEGIATAN PAGE === */
    .calendar-placeholder {
        background: var(--secondary-bg);
        border-radius: 15px;
        padding: 30px;
        max-width: 800px;
        width: 100%;
        margin-top: 40px;
        border: 2px dashed rgba(30, 64, 175, 0.3);
    }

    .calendar-header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 25px;
        padding-bottom: 15px;
        border-bottom: 1px solid rgba(30, 64, 175, 0.2);
    }

    .month-nav {
        background: transparent;
        border: none;
        color: var(--accent-color);
        font-size: 1.3rem;
        cursor: pointer;
        padding: 8px;
        border-radius: 50%;
        width: 45px;
        height: 45px;
        display: flex;
        align-items: center;
        justify-content: center;
        outline: none;
    }

    .month-nav:hover,
    .month-nav:focus {
        background: rgba(30, 64, 175, 0.1);
    }

    .current-month {
        font-size: 1.5rem;
        font-weight: 600;
    }

    .calendar-grid {
        display: grid;
        grid-template-columns: repeat(7, 1fr);
        gap: 8px;
        text-align: center;
    }

    .day-name {
        font-weight: 600;
        padding: 12px;
        color: var(--accent-color);
        background: rgba(30, 64, 175, 0.1);
        border-radius: 8px;
        font-size: 0.9rem;
    }

    .day {
        padding: 15px 8px;
        background: rgba(0, 0, 0, 0.05);
        border-radius: 8px;
        transition: var(--transition);
        font-size: 0.9rem;
    }

    .day.event {
        background: rgba(30, 64, 175, 0.15);
        color: var(--text-color);
        position: relative;
        cursor: pointer;
    }

    .day.event::after {
        content: '';
        position: absolute;
        bottom: 5px;
        left: 50%;
        transform: translateX(-50%);
        width: 5px;
        height: 5px;
        background: var(--accent-color);
        border-radius: 50%;
    }

    .day.event:hover,
    .day.event:focus {
        background: rgba(30, 64, 175, 0.25);
        outline: none;
    }

    .timeline {
        list-style: none;
        padding-left: 0;
        margin-top: 20px;
    }

    .timeline li {
        display: flex;
        align-items: center;
        gap: 15px;
        margin-bottom: 15px;
        padding: 12px;
        border-radius: 8px;
        background: rgba(30, 64, 175, 0.05);
    }

    .timeline i {
        color: var(--accent-color);
        font-size: 1.1rem;
    }

    /* === MODAL === */
    .modal {
        display: none;
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: rgba(0, 0, 0, 0.7);
        z-index: 2000;
        align-items: center;
        justify-content: center;
        padding: 20px;
    }

    .modal.active {
        display: flex;
    }

    .modal-content {
        background: var(--secondary-bg);
        border-radius: 15px;
        max-width: 800px;
        width: 100%;
        max-height: 90vh;
        overflow-y: auto;
        box-shadow: 0 20px 60px rgba(0,0,0,0.3);
    }

    .modal-header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 25px 30px;
        border-bottom: 1px solid rgba(30, 64, 175, 0.1);
    }

    .modal-title {
        display: flex;
        align-items: center;
        gap: 15px;
        font-size: 1.5rem;
        font-weight: 700;
        color: var(--text-color);
    }

    .modal-title i {
        color: var(--accent-color);
    }

    .close-modal {
        background: none;
        border: none;
        font-size: 2rem;
        color: var(--text-color);
        cursor: pointer;
        line-height: 1;
        padding: 0;
        width: 30px;
        height: 30px;
        display: flex;
        align-items: center;
        justify-content: center;
        outline: none;
    }

    .close-modal:hover,
    .close-modal:focus {
        color: var(--accent-color);
    }

    .modal-body {
        padding: 30px;
    }

    /* === BUTTONS === */
    .action-buttons {
        display: flex;
        gap: 20px;
        flex-wrap: wrap;
        justify-content: center;
        margin-top: 30px;
    }

    .btn {
        padding: 12px 25px;
        background: var(--accent-color);
        color: var(--bg-color);
        border: none;
        border-radius: 8px;
        font-weight: 600;
        font-size: 0.95rem;
        cursor: pointer;
        transition: var(--transition);
        display: flex;
        align-items: center;
        gap: 10px;
        text-decoration: none;
        outline: none;
    }

    .btn:hover,
    .btn:focus {
        transform: translateY(-3px);
        box-shadow: 0 8px 15px rgba(30, 64, 175, 0.3);
    }

    .btn-outline {
        background: transparent;
        border: 2px solid var(--accent-color);
        color: var(--accent-color);
    }

    .btn-outline:hover,
    .btn-outline:focus {
        background: var(--accent-color);
        color: var(--bg-color);
    }

    /* === FOOTER === */
    footer {
        padding: 40px 8%;
        text-align: center;
        opacity: 0.4;
        font-size: 0.8rem;
        border-top: 1px solid rgba(30, 64, 175, 0.1);
    }

    /* === RESPONSIVE === */
    @media (max-width: 1200px) {
        .news-image {
            width: 250px;
        }
        .proker-grid {
            grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
        }
    }

    @media (max-width: 992px) {
        .side-menu { 
            grid-template-columns: 1fr; 
        }
        .menu-extra { 
            display: none; 
        }
        .menu-links { 
            padding: 100px 8%; 
        }
        .news-card {
            flex-direction: column;
        }
        .news-image {
            width: 100%;
            height: 200px;
        }
        .hierarchy-nav {
            grid-template-columns: 1fr;
            max-width: 500px;
            margin-left: auto;
            margin-right: auto;
        }
        .proker-grid {
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
        }
        .proker-stats {
            grid-template-columns: repeat(2, 1fr);
        }
    }

    @media (max-width: 768px) {
        .action-buttons { 
            flex-direction: column; 
            width: 100%; 
        }
        .btn { 
            width: 100%; 
            justify-content: center; 
        }
        .detail-content {
            grid-template-columns: 1fr;
        }
        .proker-grid {
            grid-template-columns: 1fr;
        }
        .proker-stats {
            grid-template-columns: 1fr;
        }
        .proker-filter {
            justify-content: center;
        }
    }

    @media (max-width: 576px) {
        .detail-section { 
            padding: 25px; 
        }
        .proker-filter {
            flex-direction: column;
            align-items: stretch;
        }
        .filter-btn {
            width: 100%;
            text-align: center;
        }
        .hamburger {
            width: 25px;
            height: 18px;
        }
        .hamburger.active span:nth-child(1) { 
            transform: translateY(7.5px) rotate(45deg); 
        }
        .hamburger.active span:nth-child(3) { 
            transform: translateY(-7.5px) rotate(-45deg); 
        }
    }

    /* === AKSESIBILITAS === */
    @media (prefers-contrast: high) {
        :root {
            --text-color: #000000;
            --accent-color: #0000FF;
            --bg-color: #FFFFFF;
            --secondary-bg: #F0F0F0;
        }
        
        .dark-mode {
            --text-color: #FFFFFF;
            --accent-color: #FFFF00;
            --bg-color: #000000;
            --secondary-bg: #222222;
        }
    }

    @media (prefers-reduced-motion: reduce) {
        * {
            animation-duration: 0.01ms !important;
            animation-iteration-count: 1 !important;
            transition-duration: 0.01ms !important;
        }
        
        .news-card:hover,
        .proker-card:hover,
        .hierarchy-card:hover {
            transform: none !important;
        }
    }
  </style> 
 </head> 
 <body> 
  <nav> 
   <div class="logo">
     <i class="fas fa-shield-halved" style="color: var(--accent-color);" aria-hidden="true"></i> 
     <h1>MEDIA OSIM</h1>
   </div> 
   <div class="nav-controls"> 
    <button class="theme-btn" onclick="toggleTheme()" aria-label="Ubah tema gelap/terang">
      <i class="fas fa-moon" id="theme-icon"></i> 
    </button> 
    <div class="hamburger" onclick="toggleMenu()" role="button" aria-label="Buka/tutup menu navigasi" tabindex="0" aria-expanded="false">
      <span></span> 
      <span></span> 
      <span></span> 
    </div> 
   </div> 
  </nav> 
  
  <div class="side-menu" id="side-menu"> 
   <div class="menu-links"> 
    <div class="menu-section-title">
     Navigasi Halaman
    </div> 
    <a href="#" class="menu-item" onclick="showPage('home')" role="button" aria-label="Pergi ke halaman beranda"> 
     <i class="fas fa-house" aria-hidden="true"></i> 
     <div class="menu-text"> 
      <h2>Beranda</h2> 
      <p>Kembali ke halaman utama dan ringkasan info</p> 
     </div> 
    </a> 
    <a href="#" class="menu-item" onclick="showPage('tentang')" role="button" aria-label="Pergi ke halaman tentang kami"> 
     <i class="fas fa-landmark" aria-hidden="true"></i> 
     <div class="menu-text"> 
      <h2>Tentang Kami</h2> 
      <p>Visi, misi, sejarah, dan identitas OSIM</p> 
     </div> 
    </a> 
    <a href="#" class="menu-item" onclick="showPage('proker')" role="button" aria-label="Pergi ke halaman program kerja"> 
     <i class="fas fa-list-check" aria-hidden="true"></i> 
     <div class="menu-text"> 
      <h2>Program Kerja</h2> 
      <p>Detail rencana &amp; realisasi kerja OSIM</p> 
     </div> 
    </a> 
    <a href="#" class="menu-item" onclick="showPage('pengumuman')" role="button" aria-label="Pergi ke halaman pengumuman"> 
     <i class="fas fa-bullhorn" aria-hidden="true"></i> 
     <div class="menu-text"> 
      <h2>Pengumuman OSIM</h2> 
      <p>Informasi resmi dan pengumuman terbaru</p> 
     </div> 
    </a> 
    <a href="https://arin-ops.github.io/suarakann/" target="_blank" class="menu-item" rel="noopener noreferrer" aria-label="Buka portal aspirasi (halaman eksternal)"> 
     <i class="fas fa-comment-dots" aria-hidden="true"></i> 
     <div class="menu-text"> 
      <h2>Portal Aspirasi</h2> 
      <p>Suarakan pendapatmu di platform resmi</p> 
     </div> 
    </a> 
    
    <div class="menu-section-title" style="margin-top: 20px;">
     Sistem Digital
    </div> 
    <a href="#" class="menu-item" onclick="showPage('kegiatan')" role="button" aria-label="Pergi ke halaman kalender kegiatan"> 
     <i class="fas fa-calendar-alt" aria-hidden="true"></i> 
     <div class="menu-text"> 
      <h2>Kegiatan</h2> 
      <p>Lihat jadwal agenda mendatang</p> 
     </div> 
    </a> 
    <a href="#" class="menu-item" onclick="showPage('profil')" role="button" aria-label="Pergi ke halaman profil pengurus"> 
     <i class="fas fa-user-friends" aria-hidden="true"></i> 
     <div class="menu-text"> 
      <h2>Profil Pengurus</h2> 
      <p>Daftar lengkap jajaran pengurus OSIM</p> 
     </div> 
    </a> 
   </div> 
   
   <div class="menu-extra"> 
    <div class="menu-section-title">
     Inspirasi
    </div> 
<div class="quote-box" style="border-left: 6px solid var(--accent-color); padding-left: 20px; margin: 25px 0; background: var(--secondary-bg); padding-top: 15px; padding-bottom: 15px; transition: var(--transition);"> 
     
   <p style="font-weight: 900; font-size: 1.3rem; line-height: 2; margin-bottom: 20px; color: var(--text-color);"> 
      قَالَ رَسُوْلُ اللهِ صَلَّى اللهُ عَلَيْهِ وَسَلَّمَ : إِنَّ مِمَّا أَدْرَكَ النَّاسُ مِنْ كَلاَمِ النُّبُوَّةِ الأُوْلَى، إِذَا لَمْ تَسْتَحِ فَاصْنَعْ مَا شِئْتَ
   </p>

   <p style="font-style: italic; font-weight: 700; font-size: 1.0rem; line-height: 1.5; color: var(--text-color); margin-bottom: 10px;">
      Rasulullah shallallahu alaihi wa sallam bersabda: "Sesungguhnya ungkapan yang telah dikenal orang-orang dari ucapan nabi-nabi terdahulu adalah: Jika engkau tidak malu, berbuatlah sekehendak hatimu."
   </p> 

   <p style="color: var(--accent-color); font-weight: 800; font-size: 0.9rem; margin: 0;">
      — (HR. Bukhari)
   </p> 
</div>
 
    
    <div class="menu-section-title" style="margin-top: 20px;">
     Hubungi Kami
    </div> 
    <ul class="info-list" style="margin-top: 10px;"> 
     <li><i class="fas fa-envelope" aria-hidden="true"></i> osimmamaarifrembang@gmail.com</li> 
     <li><i class="fab fa-instagram" aria-hidden="true"></i> @osim.mamrembang</li> 
     <li><i class="fab fa-tiktok" aria-hidden="true"></i> @osim.resmi</li> 
     <li><i class="fab fa-whatsapp" aria-hidden="true"></i> +62 838-4833-2165</li> 
    </ul> 
   </div> 
  </div> 
  
  <!-- HOME PAGE -->
  <main id="home-page" class="page-content active"> 
   <section class="hero"> 
    <h2 class="hero-title">Mewujudkan<br>Organisasi <span>Modern</span><br>&amp; Akuntabel</h2> 
    <p style="max-width: 600px; margin-top: 20px; opacity: 0.7; border-left: 3px solid var(--accent-color); padding-left: 20px;"> Pusat informasi resmi, transparansi program kerja, dan wadah aspirasi siswa yang aman secara digital. </p> 
   </section> 
  </main> 
  
  <!-- TENTANG KAMI PAGE -->
  <div id="tentang-page" class="page-content"> 
   <div class="proker-container"> 
    <div class="proker-header"> 
     <h2 class="proker-title">Tentang <span>OSIM Digital</span></h2> 
     <p class="proker-description">Mengenal lebih dalam visi, misi, sejarah, dan identitas organisasi kami.</p> 
    </div>
    
    <!-- VISI MISI SECTION -->
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; margin-bottom: 50px;">
      <div class="position-card" style="border-left: 5px solid var(--accent-color);">
        <div class="position-header">
          <div class="position-icon" style="background: rgba(30, 64, 175, 0.15);">
            <i class="fas fa-bullseye" style="color: var(--accent-color);"></i>
          </div>
          <div>
            <div class="position-title">Visi Kami</div>
          </div>
        </div>
        <p class="position-desc" style="font-style: italic; color: var(--accent-color); font-weight: 600;">
          "Mewujudkan organisasi siswa yang modern, transparan, dan akuntabel melalui pemanfaatan teknologi digital."
        </p>
      </div>
      
      <div class="position-card" style="border-left: 5px solid var(--success-color);">
        <div class="position-header">
          <div class="position-icon" style="background: rgba(16, 185, 129, 0.15);">
            <i class="fas fa-tasks" style="color: var(--success-color);"></i>
          </div>
          <div>
            <div class="position-title">Misi Kami</div>
          </div>
        </div>
        <ul class="member-list">
          <li style="border-bottom: none; padding: 8px 0;">
            <i class="fas fa-check-circle" style="color: var(--success-color); margin-right: 10px;"></i>
            Membangun sistem informasi terintegrasi
          </li>
          <li style="border-bottom: none; padding: 8px 0;">
            <i class="fas fa-check-circle" style="color: var(--success-color); margin-right: 10px;"></i>
            Meningkatkan transparansi pengelolaan organisasi
          </li>
          <li style="border-bottom: none; padding: 8px 0;">
            <i class="fas fa-check-circle" style="color: var(--success-color); margin-right: 10px;"></i>
            Memberikan wadah aspirasi yang aman dan terpercaya
          </li>
          <li style="border-bottom: none; padding: 8px 0;">
            <i class="fas fa-check-circle" style="color: var(--success-color); margin-right: 10px;"></i>
            Mengembangkan kompetensi digital anggota
          </li>
        </ul>
      </div>
    </div>
    
    <!-- SEJARAH SECTION -->
    <div class="position-card" style="margin-bottom: 40px;">
      <div class="position-header">
        <div class="position-icon">
          <i class="fas fa-history"></i>
        </div>
        <div>
          <div class="position-title">Sejarah OSIM Digital</div>
        </div>
      </div>
      <p class="position-desc">
        MEDIA OSIMdidirikan pada tahun 2026 sebagai inisiatif transformasi digital Organisasi Siswa Intra Madrasah. 
        Lahir dari kebutuhan akan transparansi, akuntabilitas, dan efisiensi dalam pengelolaan organisasi siswa.
      </p>
      <p class="position-desc">
        Dengan dukungan dari pihak sekolah dan antusiasme anggota, kami mengembangkan platform digital yang menyediakan 
        akses informasi real-time, sistem pengelolaan program kerja yang terstruktur, dan wadah aspirasi yang aman bagi seluruh siswa.
      </p>
    </div>
    
    <!-- NILAI-NILAI SECTION -->
    <h3 style="color: var(--accent-color); margin-bottom: 25px; display: flex; align-items: center; gap: 10px;">
      <i class="fas fa-gem"></i> Nilai-Nilai Inti
    </h3>
    
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-bottom: 50px;">
      <div class="proker-card" style="height: auto;">
        <div class="proker-content">
          <h3 class="proker-name" style="color: var(--accent-color);">
            <i class="fas fa-shield-alt" style="margin-right: 10px;"></i>Integritas
          </h3>
          <p class="proker-description-card">
            Bertindak jujur, transparan, dan konsisten dalam setiap keputusan dan tindakan.
          </p>
        </div>
      </div>
      
      <div class="proker-card" style="height: auto;">
        <div class="proker-content">
          <h3 class="proker-name" style="color: var(--success-color);">
            <i class="fas fa-lightbulb" style="margin-right: 10px;"></i>Inovasi
          </h3>
          <p class="proker-description-card">
            Terus mengembangkan ide kreatif dan solusi digital untuk kemajuan organisasi.
          </p>
        </div>
      </div>
      
      <div class="proker-card" style="height: auto;">
        <div class="proker-content">
          <h3 class="proker-name" style="color: var(--info-color);">
            <i class="fas fa-users" style="margin-right: 10px;"></i>Kolaborasi
          </h3>
          <p class="proker-description-card">
            Bekerja sama dengan semangat gotong royong untuk mencapai tujuan bersama.
          </p>
        </div>
      </div>
    </div>
    
    <!-- STRUKTUR SINGKAT -->
    <div class="position-card">
      <div class="position-header">
        <div class="position-icon">
          <i class="fas fa-sitemap"></i>
        </div>
        <div>
          <div class="position-title">Struktur Organisasi</div>
        </div>
      </div>
      <p class="position-desc">
        OSIM (Osganisasi Siswa Intra Madrasah) dipimpin oleh Pengurus Inti yang terdiri dari Ketua, Wakil Ketua, Sekretaris, dan Bendahara. 
        Didukung oleh Bidang Khusus (Humas, IT/Media, Kedisiplinan) dan berbagai Divisi sesuai minat bakat siswa.
      </p>
      <div class="action-buttons" style="margin-top: 20px;"> 
        <button class="btn" onclick="showPage('profil')"> 
          <i class="fas fa-user-friends"></i> Lihat Struktur Lengkap 
        </button> 
      </div>
    </div>
    
    <!-- KONTAK FOOTER -->
    <div style="margin-top: 60px; padding-top: 30px; border-top: 2px solid rgba(30, 64, 175, 0.1);">
      <h3 style="margin-bottom: 20px; color: var(--accent-color);">
        <i class="fas fa-comments"></i> Hubungi Kami
      </h3>
      <div style="display: flex; flex-wrap: wrap; gap: 20px; margin-bottom: 30px;">
        <a href="osimmamaarifrembang@gmail.com" class="btn btn-outline" style="text-decoration: none;">
          <i class="fas fa-envelope"></i> Email
        </a>
        <a href="https://www.instagram.com/osim.mamrembang?igsh=OXpqNWxoMzd4ZGQx" target="_blank" class="btn btn-outline" style="text-decoration: none;">
          <i class="fab fa-instagram"></i> Instagram
        </a>
        <a href="https://wa.me/qr/A4ZCS23YMT7QM1" target="_blank" class="btn btn-outline" style="text-decoration: none;">
          <i class="fab fa-whatsapp"></i> WhatsApp
        </a>
      </div>
    </div>
  </div> 
</div>
  
  <!-- PENGUMUMAN PAGE (PORTAL BERITA) -->
  <div id="pengumuman-page" class="page-content"> 
   <div class="announcement-section"> 
    <h2 class="section-title">Portal Berita OSIM</h2> 
    <p style="margin-bottom: 40px; font-size: 1.1rem; opacity: 0.8; max-width: 800px; line-height: 1.6;"> Sumber informasi resmi dan terpercaya dari Organisasi Siswa Intra Madrasah. Semua pengumuman, berita, dan perkembangan terbaru tersaji secara formal dan transparan. </p> 
     
    <div class="news-container" id="news-container"> 
     <!-- Berita akan diisi dari Firebase -->
    </div> 
    
    <div class="action-buttons" style="margin-top: 50px;"> 
     <button class="btn btn-outline active" onclick="filterNews('all')" aria-label="Tampilkan semua berita"> 
      <i class="fas fa-layer-group" aria-hidden="true"></i> Semua Berita 
     </button> 
     <button class="btn btn-outline" onclick="filterNews('important')" aria-label="Tampilkan hanya berita penting"> 
      <i class="fas fa-exclamation-circle" aria-hidden="true"></i> Penting 
     </button> 
     <button class="btn" onclick="subscribeNewsletter()" aria-label="Berlangganan newsletter"> 
      <i class="fas fa-bell" aria-hidden="true"></i> Berlangganan Berita 
     </button> 
    </div> 
   </div> 
  </div> 
  
  <!-- PROGRAM KERJA PAGE -->
  <div id="proker-page" class="page-content"> 
   <div class="proker-container"> 
    <div class="proker-header"> 
     <h2 class="proker-title">Program Kerja <span>OSIM</span></h2> 
     <p class="proker-description">Koleksi program kerja yang telah direncanakan dan sedang berjalan. Setiap kartu menunjukkan detail dan progress.</p> 
     
     <!-- FILTER BUTTONS -->
     <div class="proker-filter">
        <button class="filter-btn active" onclick="filterProker('all')" aria-label="Tampilkan semua program">
            Semua
        </button>
        <button class="filter-btn" onclick="filterProker('ongoing')" aria-label="Tampilkan program yang sedang berjalan">
            Berjalan
        </button>
        <button class="filter-btn" onclick="filterProker('completed')" aria-label="Tampilkan program yang sudah selesai">
            Selesai
        </button>
        <button class="filter-btn" onclick="filterProker('planned')" aria-label="Tampilkan program yang sudah direncanakan">
            Terencana
        </button>
     </div>
    </div>
    
    <!-- PROKER GRID (akan diisi dari Firebase) -->
    <div class="proker-grid" id="proker-grid">
        <!-- Data akan diisi dari Firebase -->
    </div>
    
    <!-- STATISTIK -->
    <div class="proker-stats">
        <div class="stat-card stat-total">
            <div class="stat-number">0</div>
            <div class="stat-label">Total Program</div>
        </div>
        <div class="stat-card stat-ongoing">
            <div class="stat-number">0</div>
            <div class="stat-label">Sedang Berjalan</div>
        </div>
        <div class="stat-card stat-completed">
            <div class="stat-number">0</div>
            <div class="stat-label">Telah Selesai</div>
        </div>
    </div>
    
    <div class="action-buttons"> 
     <a href="https://arin-ops.github.io/suarakann/" target="_blank" class="btn btn-outline" rel="noopener noreferrer"> 
      <i class="fas fa-lightbulb" aria-hidden="true"></i> Berikan Saran 
     </a> 
     <button class="btn" onclick="refreshProkerData()" aria-label="Muat ulang data program kerja">
        <i class="fas fa-sync-alt" aria-hidden="true"></i> Refresh Data
     </button>
    </div> 
   </div> 
  </div>
  
  <!-- KEGIATAN PAGE -->
  <div id="kegiatan-page" class="page-content"> 
   <div class="not-found-container"> 
    <div class="not-found-icon"> <i class="fas fa-calendar-alt" aria-hidden="true"></i> 
    </div> 
    <h2 class="not-found-title">Kalender Kegiatan <span>OSIM 2026/2027</span></h2> 
    <p class="not-found-desc"> Lihat semua agenda dan kegiatan OSIM yang telah direncanakan. Kalender ini akan terus diperbarui dengan kegiatan-kegiatan terbaru. </p> 
    <div class="calendar-placeholder"> 
     <div class="calendar-header"> 
      <button class="month-nav" onclick="changeMonth(-1)" aria-label="Bulan sebelumnya"><i class="fas fa-chevron-left" aria-hidden="true"></i></button> 
      <div class="current-month" id="currentMonth"></div> 
      <button class="month-nav" onclick="changeMonth(1)" aria-label="Bulan berikutnya"><i class="fas fa-chevron-right" aria-hidden="true"></i></button> 
     </div> 
     <div class="calendar-grid" id="calendarGrid"> 
      <div class="day-name">Min</div> 
      <div class="day-name">Sen</div> 
      <div class="day-name">Sel</div> 
      <div class="day-name">Rab</div> 
      <div class="day-name">Kam</div> 
      <div class="day-name">Jum</div> 
      <div class="day-name">Sab</div> 
     </div> 
    </div> 
    <div class="coming-soon" style="margin-top: 40px; max-width: 800px;"> 
     <h3><i class="fas fa-calendar-check" aria-hidden="true"></i> Kegiatan Mendatang</h3> 
     <ul class="timeline" id="upcoming-events-list">
        <!-- Data akan diisi dari Firebase -->
     </ul> 
    </div> 
    <div class="action-buttons"> 
     <button class="btn btn-outline" onclick="activateReminders()" aria-label="Aktifkan pengingat kegiatan"> 
      <i class="fas fa-bell" aria-hidden="true"></i> Aktifkan Pengingat 
     </button> 
    </div> 
   </div> 
  </div> 
  
  <!-- PROFIL PAGE HIERARKI -->
  <div id="profil-page" class="page-content"> 
   <div class="not-found-container"> 
    <div class="not-found-icon"> <i class="fas fa-user-friends" aria-hidden="true"></i> 
    </div> 
    <h2 class="not-found-title">Struktur & Tim <span>Pengurus OSIM</span></h2> 
    <p class="not-found-desc"> Kenali struktur organisasi dan anggota tim osim 2026. Klik pada kategori untuk melihat detail lebih lanjut. </p> 
    
    <!-- HIERARKI NAVIGASI -->
    <div class="profil-hierarchy">
        <div class="hierarchy-nav">
            <div class="hierarchy-card active" onclick="showDetail('inti')" role="button" tabindex="0" aria-label="Lihat pengurus inti">
                <div class="hierarchy-icon">
                    <i class="fas fa-crown" aria-hidden="true"></i>
                </div>
                <h3>Pengurus Inti</h3>
                <p>Ketua, Wakil, Sekretaris, Bendahara. Pimpinan tertinggi OSIM yang bertanggung jawab penuh atas organisasi.</p>
            </div>
            
            <div class="hierarchy-card" onclick="showDetail('khusus')" role="button" tabindex="0" aria-label="Lihat bidang khusus">
                <div class="hierarchy-icon">
                    <i class="fas fa-star" aria-hidden="true"></i>
                </div>
                <h3>Bidang Khusus</h3>
                <p>Hubungan Masyarakat, IT/Media, Kedisiplinan. Tim khusus dengan fungsi strategis dan spesifik.</p>
            </div>
            
            <div class="hierarchy-card" onclick="showDetail('divisi')" role="button" tabindex="0" aria-label="Lihat divisi">
                <div class="hierarchy-icon">
                    <i class="fas fa-sitemap" aria-hidden="true"></i>
                </div>
                <h3>Divisi</h3>
                <p>Olahraga, Seni, Keagamaan, dll. Unit operasional yang menjalankan program kerja harian.</p>
            </div>
        </div>
        
        <!-- DETAIL PENGURUS INTI -->
        <div class="detail-section active" id="detail-inti">
            <div class="detail-header">
                <div class="detail-title">
                    <i class="fas fa-crown" aria-hidden="true"></i>
                    Pengurus Inti OSIM 2025/2026
                </div>
                <button class="back-btn" onclick="backToMain()" aria-label="Kembali ke menu utama">
                    <i class="fas fa-arrow-left" aria-hidden="true"></i> Kembali
                </button>
            </div>
            
            <div class="detail-content" id="pengurus-inti-content">
                <!-- Data akan diisi dari Firebase -->
            </div>
        </div>
        
        <!-- DETAIL BIDANG KHUSUS -->
        <div class="detail-section" id="detail-khusus">
            <div class="detail-header">
                <div class="detail-title">
                    <i class="fas fa-star" aria-hidden="true"></i>
                    Bidang Khusus OSIM
                </div>
                <button class="back-btn" onclick="backToMain()" aria-label="Kembali ke menu utama">
                    <i class="fas fa-arrow-left" aria-hidden="true"></i> Kembali
                </button>
            </div>
            
            <div class="detail-content" id="pengurus-khusus-content">
                <!-- Data akan diisi dari Firebase -->
            </div>
        </div>
        
        <!-- DETAIL DIVISI -->
        <div class="detail-section" id="detail-divisi">
            <div class="detail-header">
                <div class="detail-title">
                    <i class="fas fa-sitemap" aria-hidden="true"></i>
                    Divisi OSIM
                </div>
                <button class="back-btn" onclick="backToMain()" aria-label="Kembali ke menu utama">
                    <i class="fas fa-arrow-left" aria-hidden="true"></i> Kembali
                </button>
            </div>
            
            <div class="detail-content" id="pengurus-divisi-content">
                <!-- Data akan diisi dari Firebase -->
            </div>
        </div>
    </div>
    
    <div class="action-buttons" style="margin-top: 40px;"> 
     <button class="btn btn-outline" onclick="showJoinInfo()" aria-label="Informasi bergabung dengan OSIM"> 
      <i class="fas fa-user-plus" aria-hidden="true"></i> Bergabung dengan OSIM 
     </button> 
     <button class="btn" onclick="showDetail('inti')" aria-label="Lihat struktur lengkap OSIM"> 
      <i class="fas fa-users" aria-hidden="true"></i> Lihat Struktur Lengkap 
     </button> 
    </div> 
   </div> 
  </div>
  
  <!-- MODAL DETAIL BERITA -->
  <div class="modal" id="news-modal" role="dialog" aria-labelledby="modal-news-title" aria-hidden="true">
    <div class="modal-content">
        <div class="modal-header">
            <div class="modal-title">
                <i class="fas fa-newspaper" aria-hidden="true"></i>
                <span id="modal-news-title">Judul Berita</span>
            </div>
            <button class="close-modal" onclick="closeModal()" aria-label="Tutup modal">&times;</button>
        </div>
        <div class="modal-body">
            <div style="margin-bottom: 25px;">
                <span class="category" id="modal-news-category">KATEGORI</span>
                <div style="font-size: 0.9rem; color: var(--news-gray); margin-top: 10px;">
                    <i class="far fa-calendar" aria-hidden="true"></i> <span id="modal-news-date">Tanggal</span> | 
                    <i class="far fa-user" aria-hidden="true"></i> <span id="modal-news-author">Penulis</span>
                </div>
            </div>
            
            <div id="modal-news-content">
                <p>Konten berita lengkap akan muncul di sini.</p>
            </div>
            
            <div style="margin-top: 30px; padding-top: 20px; border-top: 1px solid rgba(0,0,0,0.1);">
                <h4 style="color: var(--accent-color); margin-bottom: 15px;">Lampiran</h4>
                <div style="display: flex; gap: 10px; flex-wrap: wrap;">
                    <span style="padding: 8px 15px; background: rgba(30, 64, 175, 0.1); border-radius: 6px; font-size: 0.85rem;">
                        <i class="fas fa-file-pdf" aria-hidden="true"></i> PDF Pengumuman
                    </span>
                    <span style="padding: 8px 15px; background: rgba(30, 64, 175, 0.1); border-radius: 6px; font-size: 0.85rem;">
                        <i class="fas fa-image" aria-hidden="true"></i> Foto Dokumentasi
                    </span>
                </div>
            </div>
        </div>
    </div>
  </div>
  
  <footer>
    © 2026 MEDIA OSIM. Hak Cipta Dilindungi. 
  </footer> 

  <!-- SCRIPT UTAMA -->
  <script>
    // === VARIABEL GLOBAL ===
    window.currentDate = new Date();
    window.announcementsData = {};
    window.prokerData = {};
    window.pengurusData = {};
    window.firebaseEvents = {};

    // === FUNGSI UTAMA ===
    document.addEventListener('DOMContentLoaded', function() {
        applyTheme();
        showPage('home');
        updateCalendar();
        
        if (window.renderCalendarDays) {
            window.renderCalendarDays(window.currentDate.getFullYear(), window.currentDate.getMonth());
        }
        
        initializeEventListeners();
        initializeFirebase();
        
        console.log('MEDIA OSIMWebsite telah dimuat dengan sukses!');
    });

    // === INISIALISASI EVENT LISTENERS ===
    function initializeEventListeners() {
        // Close modal ketika klik di luar
        document.addEventListener('click', function(e) {
            const modal = document.getElementById('news-modal');
            if (e.target && e.target.classList && e.target.classList.contains('modal') && modal) {
                closeModal();
            }
        });

        // Close modal dengan tombol Escape
        document.addEventListener('keydown', function(e) {
            if (e.key === 'Escape') {
                closeModal();
            }
        });
        
        // Keyboard navigation untuk hamburger menu
        const hamburger = document.querySelector('.hamburger');
        if (hamburger) {
            hamburger.addEventListener('keydown', function(e) {
                if (e.key === 'Enter' || e.key === ' ') {
                    e.preventDefault();
                    toggleMenu();
                }
            });
        }
        
        // Keyboard navigation untuk menu items
        const menuItems = document.querySelectorAll('.menu-item, .hierarchy-card, .filter-btn');
        menuItems.forEach(item => {
            item.addEventListener('keydown', function(e) {
                if (e.key === 'Enter' || e.key === ' ') {
                    e.preventDefault();
                    this.click();
                }
            });
        });
    }

    // === FUNGSI FIREBASE ===
    function initializeFirebase() {
        // Import modul Firebase dari CDN
        const firebaseScript = document.createElement('script');
        firebaseScript.type = 'module';
        firebaseScript.textContent = `
            import { initializeApp } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-app.js";
            import { getDatabase, ref, onValue } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-database.js";
            import { getAnalytics } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-analytics.js";

            const firebaseConfig = {
                apiKey: "AIzaSyCT7yu1D0qsW2lyK4ZMYia029nEvvMMDCs",
                authDomain: "webosim-5c4a7.firebaseapp.com",
                projectId: "webosim-5c4a7",
                storageBucket: "webosim-5c4a7.firebasestorage.app",
                messagingSenderId: "769601153494",
                appId: "1:769601153494:web:057f7f8ec7574ba486dc77",
                measurementId: "G-QEBT3N7QGL",
                databaseURL: "https://webosim-5c4a7-default-rtdb.asia-southeast1.firebasedatabase.app"
            };

            const app = initializeApp(firebaseConfig);
            const db = getDatabase(app);
            const analytics = getAnalytics(app);

            // --- LOGIKA PENGUMUMAN DARI DATABASE ---
            const annRef = ref(db, 'announcements');
            onValue(annRef, (snapshot) => {
                const container = document.getElementById('news-container');
                const data = snapshot.val();
                
                if (data && container) {
                    container.innerHTML = '';
                    Object.entries(data).forEach(([id, announcement]) => {
                        const article = document.createElement('article');
                        article.className = 'news-card';
                        article.setAttribute('data-category', announcement.category || 'all');
                        
                        let categoryClass = '';
                        if (announcement.category === 'PENTING') categoryClass = 'important';
                        else if (announcement.category === 'UPDATE') categoryClass = 'update';
                        else if (announcement.category === 'INFO') categoryClass = 'info';
                        
                        article.innerHTML = \`
                            <div class="news-image">
                                <div class="news-image-placeholder">
                                    <i class="fas fa-\${announcement.icon || 'newspaper'}"></i>
                                </div>
                            </div>
                            <div class="news-content">
                                <span class="category \${categoryClass}">\${announcement.category || 'UMUM'}</span>
                                <h3 class="news-headline">\${announcement.title || 'Tanpa Judul'}</h3>
                                <p class="news-meta">
                                    <i class="far fa-calendar"></i> Diposting: \${announcement.date || 'Tanpa tanggal'}
                                    <i class="far fa-user"></i> Oleh: \${announcement.author || 'Anonim'}
                                </p>
                                <p class="news-excerpt">\${announcement.excerpt || 'Tidak ada ringkasan'}</p>
                                <button class="read-more" onclick="showNewsDetailFromFirebase('\${id}')" aria-label="Baca selengkapnya tentang \${announcement.title || 'berita ini'}">
                                    Baca Selengkapnya <i class="fas fa-arrow-right"></i>
                                </button>
                            </div>
                        \`;
                        container.appendChild(article);
                    });
                }
                
                window.announcementsData = data || {};
            });

            // --- LOGIKA EVENT/KALENDER DARI DATABASE ---
            onValue(ref(db, 'events'), (snapshot) => {
                const data = snapshot.val();
                window.firebaseEvents = data || {};
                
                const kegiatanPage = document.getElementById('kegiatan-page');
                if (kegiatanPage && kegiatanPage.classList.contains('active')) {
                    if (window.renderCalendarDays) {
                        window.renderCalendarDays(window.currentDate.getFullYear(), window.currentDate.getMonth());
                    }
                }
                
                const upcomingList = document.getElementById('upcoming-events-list');
                if(upcomingList && data) {
                    upcomingList.innerHTML = '';
                    
                    const today = new Date();
                    const upcoming = [];
                    
                    Object.entries(data).forEach(([dateStr, eventData]) => {
                        const eventDate = new Date(dateStr);
                        if (eventDate >= today) {
                            upcoming.push({ date: dateStr, name: eventData.name || eventData });
                        }
                    });
                    
                    upcoming.sort((a, b) => new Date(a.date) - new Date(b.date));
                    
                    upcoming.slice(0, 3).forEach(item => {
                        const li = document.createElement('li');
                        li.innerHTML = \`<i class="fas fa-calendar-check"></i> <strong>\${item.name}:</strong> \${formatDate(item.date)}\`;
                        upcomingList.appendChild(li);
                    });
                }
            });

            // --- LOGIKA PROKER DARI DATABASE ---
            onValue(ref(db, 'proker'), (snapshot) => {
                const data = snapshot.val();
                window.prokerData = data || {};
                
                const prokerPage = document.getElementById('proker-page');
                if (prokerPage && prokerPage.classList.contains('active')) {
                    renderProkerFromFirebase();
                    updateProkerStats();
                }
            });

            // --- LOGIKA PENGURUS DARI DATABASE ---
            onValue(ref(db, 'pengurus'), (snapshot) => {
                const data = snapshot.val();
                window.pengurusData = data || {};
                
                const profilPage = document.getElementById('profil-page');
                if (profilPage && profilPage.classList.contains('active')) {
                    renderPengurusFromFirebase();
                }
            });

            function formatDate(dateString) {
                const date = new Date(dateString);
                return date.toLocaleDateString('id-ID', { 
                    day: 'numeric', 
                    month: 'long', 
                    year: 'numeric' 
                });
            }

            function renderProkerFromFirebase() {
                const container = document.getElementById('proker-grid');
                if (!container || !window.prokerData) return;
                
                container.innerHTML = '';
                
                Object.entries(window.prokerData).forEach(([id, proker]) => {
                    const card = document.createElement('div');
                    card.className = 'proker-card';
                    card.setAttribute('data-status', proker.status || 'planned');
                    card.setAttribute('role', 'article');
                    card.setAttribute('aria-label', \`Program kerja: \${proker.name}\`);
                    
                    let statusText = 'Terencana';
                    let statusClass = 'status-planned';
                    if (proker.status === 'ongoing') {
                        statusText = 'Berjalan';
                        statusClass = 'status-ongoing';
                    } else if (proker.status === 'completed') {
                        statusText = 'Selesai';
                        statusClass = 'status-completed';
                    }
                    
                    let tagsHTML = '';
                    if (proker.tags && Array.isArray(proker.tags)) {
                        tagsHTML = proker.tags.map(tag => {
                            let tagClass = 'tag-potential';
                            if (tag === 'PERFORMAN') tagClass = 'tag-performance';
                            else if (tag === 'SOCIAL') tagClass = 'tag-social';
                            else if (tag === 'Live Chat') tagClass = 'tag-live';
                            return \`<span class="proker-tag \${tagClass}">\${tag}</span>\`;
                        }).join('');
                    }
                    
                    card.innerHTML = \`
                        <div class="proker-image">
                            <div class="proker-image-overlay"></div>
                            <div class="proker-image-content">
                                <i class="fas fa-\${proker.icon || 'tasks'}"></i>
                                <div style="font-size: 1rem; margin-top: 10px;">\${proker.shortName || proker.name.substring(0, 10)}</div>
                            </div>
                        </div>
                        <div class="proker-content">
                            <h3 class="proker-name">\${proker.name || 'Tanpa Nama'}</h3>
                            <p class="proker-description-card">\${proker.description || 'Tidak ada deskripsi'}</p>
                            <div class="proker-tags">
                                \${tagsHTML}
                            </div>
                            <div class="proker-footer">
                                <div class="proker-status">
                                    <span class="status-dot \${statusClass}"></span>
                                    <span>\${statusText}</span>
                                </div>
                                <div class="proker-date">\${proker.date || 'Tanpa tanggal'}</div>
                            </div>
                        </div>
                    \`;
                    
                    container.appendChild(card);
                });
            }

            function updateProkerStats() {
                if (!window.prokerData) return;
                
                let total = 0, ongoing = 0, completed = 0;
                
                Object.values(window.prokerData).forEach(proker => {
                    total++;
                    if (proker.status === 'ongoing') ongoing++;
                    else if (proker.status === 'completed') completed++;
                });
                
                const totalEl = document.querySelector('.stat-total .stat-number');
                const ongoingEl = document.querySelector('.stat-ongoing .stat-number');
                const completedEl = document.querySelector('.stat-completed .stat-number');
                
                if (totalEl) totalEl.textContent = total;
                if (ongoingEl) ongoingEl.textContent = ongoing;
                if (completedEl) completedEl.textContent = completed;
            }

            function renderPengurusFromFirebase() {
                if (!window.pengurusData) return;
                
                renderPengurusSection('inti', window.pengurusData.inti);
                renderPengurusSection('khusus', window.pengurusData.khusus);
                renderPengurusSection('divisi', window.pengurusData.divisi);
            }

            function renderPengurusSection(sectionId, data) {
                const container = document.getElementById(\`pengurus-\${sectionId}-content\`);
                if (!container) return;
                
                container.innerHTML = '';
                
                if (!data) {
                    container.innerHTML = '<p style="text-align: center; padding: 40px;">Data belum tersedia.</p>';
                    return;
                }
                
                Object.entries(data).forEach(([positionId, position]) => {
                    const positionCard = document.createElement('div');
                    positionCard.className = 'position-card';
                    
                    const positionName = positionId.replace(/_/g, ' ')
                        .split(' ')
                        .map(word => word.charAt(0).toUpperCase() + word.slice(1))
                        .join(' ');
                    
                    positionCard.innerHTML = \`
                        <div class="position-header">
                            <div class="position-icon">
                                <i class="fas fa-\${position.icon || 'user'}"></i>
                            </div>
                            <div>
                                <div class="position-title">\${positionName}</div>
                            </div>
                        </div>
                        <p class="position-desc">\${position.description || 'Tidak ada deskripsi'}</p>
                        <ul class="member-list">
                            \${position.members ? Object.entries(position.members).map(([memberId, member]) => \`
                                <li>
                                    <div class="member-info">
                                        <div class="member-avatar">\${getInitials(member.name)}</div>
                                        <div class="member-details">
                                            <div class="member-name">\${member.name || 'Tidak ada nama'}</div>
                                            <div class="member-class">\${member.class || 'Tidak ada kelas'}</div>
                                        </div>
                                    </div>
                                    <button class="view-detail" onclick="showMemberDetail('\${memberId}', '\${positionId}', '\${sectionId}')" aria-label="Lihat detail \${member.name || 'anggota'}">
                                        Detail
                                    </button>
                                </li>
                            \`).join('') : '<li>Tidak ada anggota</li>'}
                        </ul>
                    \`;
                    
                    container.appendChild(positionCard);
                });
            }

            function getInitials(name) {
                if (!name) return '??';
                return name.split(' ').map(n => n[0]).join('').toUpperCase().substring(0, 2);
            }

            window.getEventsForDate = function(year, month, day) {
                if (!window.firebaseEvents) return [];
                const dateKey = \`\${year}-\${month + 1}-\${day}\`;
                const events = window.firebaseEvents[dateKey];
                
                if (Array.isArray(events)) {
                    return events;
                } else if (typeof events === 'string') {
                    return [events];
                } else if (events && events.name) {
                    return [events.name];
                }
                return [];
            };

            window.showNewsDetailFromFirebase = function(newsId) {
                if (!window.announcementsData || !window.announcementsData[newsId]) {
                    alert('Data pengumuman tidak ditemukan');
                    return;
                }

                const news = window.announcementsData[newsId];
                const modal = document.getElementById('news-modal');
                if (!modal) return;
                
                const titleEl = document.getElementById('modal-news-title');
                const categoryEl = document.getElementById('modal-news-category');
                const dateEl = document.getElementById('modal-news-date');
                const authorEl = document.getElementById('modal-news-author');
                const contentEl = document.getElementById('modal-news-content');
                
                if (titleEl) titleEl.textContent = news.title || 'Tanpa Judul';
                if (categoryEl) {
                    categoryEl.textContent = news.category || 'UMUM';
                    categoryEl.className = \`category \${news.category === 'PENTING' ? 'important' : news.category === 'UPDATE' ? 'update' : ''}\`;
                }
                if (dateEl) dateEl.textContent = news.date || 'Tanpa tanggal';
                if (authorEl) authorEl.textContent = news.author || 'Anonim';
                if (contentEl) contentEl.innerHTML = news.fullContent || '<p>Tidak ada konten lengkap.</p>';
                
                modal.classList.add('active');
                modal.setAttribute('aria-hidden', 'false');
                document.body.style.overflow = 'hidden';
            };

            window.showMemberDetail = function(memberId, positionId, sectionId) {
                if (!window.pengurusData || 
                    !window.pengurusData[sectionId] || 
                    !window.pengurusData[sectionId][positionId] ||
                    !window.pengurusData[sectionId][positionId].members ||
                    !window.pengurusData[sectionId][positionId].members[memberId]) {
                    alert('Data anggota tidak ditemukan');
                    return;
                }
                
                const member = window.pengurusData[sectionId][positionId].members[memberId];
                alert(\`Detail Anggota:\\n\\nNama: \${member.name}\\nKelas: \${member.class || 'Tidak ada'}\\nJabatan: \${positionId.replace(/_/g, ' ')}\\nDivisi: \${sectionId}\\n\\nKontak: \${member.contact || 'Tidak ada'}\`);
            };

            window.renderProkerFromFirebase = renderProkerFromFirebase;
            window.updateProkerStats = updateProkerStats;
            window.renderPengurusFromFirebase = renderPengurusFromFirebase;
        `;
        
        document.head.appendChild(firebaseScript);
    }

    // === FUNGSI FILTER PROKER ===
    function filterProker(filter) {
        try {
            const buttons = document.querySelectorAll('.filter-btn');
            if (!buttons.length) return;
            
            buttons.forEach(btn => {
                if (btn) btn.classList.remove('active');
            });
            
            if (event && event.target) {
                event.target.classList.add('active');
            }
            
            const cards = document.querySelectorAll('.proker-card');
            if (!cards.length) return;
            
            cards.forEach(card => {
                if (card) {
                    if (filter === 'all') {
                        card.style.display = 'flex';
                    } else {
                        const status = card.getAttribute('data-status');
                        let show = false;
                        if (filter === 'ongoing' && status === 'ongoing') show = true;
                        if (filter === 'completed' && status === 'completed') show = true;
                        if (filter === 'planned' && status === 'planned') show = true;
                        
                        card.style.display = show ? 'flex' : 'none';
                    }
                }
            });
        } catch (error) {
            console.error('Error in filterProker:', error);
        }
    }

    // === FUNGSI HIERARKI PROFIL ===
    function showDetail(sectionId) {
        try {
            const cards = document.querySelectorAll('.hierarchy-card');
            if (!cards.length) return;
            
            cards.forEach(card => {
                if (card) card.classList.remove('active');
            });
            
            const targetCard = event?.target?.closest('.hierarchy-card');
            if (targetCard) {
                targetCard.classList.add('active');
            }
            
            const sections = document.querySelectorAll('.detail-section');
            sections.forEach(section => {
                if (section) section.classList.remove('active');
            });
            
            const selectedSection = document.getElementById('detail-' + sectionId);
            if (selectedSection) {
                selectedSection.classList.add('active');
                selectedSection.scrollIntoView({ behavior: 'smooth', block: 'start' });
                
                if (window.pengurusData && window.pengurusData[sectionId]) {
                    const container = document.getElementById(`pengurus-${sectionId}-content`);
                    if (container && container.innerHTML.includes('Data belum tersedia')) {
                        if (window.renderPengurusFromFirebase) {
                            window.renderPengurusFromFirebase();
                        }
                    }
                }
            }
        } catch (error) {
            console.error('Error in showDetail:', error);
        }
    }

    function backToMain() {
        try {
            const cards = document.querySelectorAll('.hierarchy-card');
            if (!cards.length) return;
            
            cards.forEach(card => {
                if (card) card.classList.remove('active');
            });
            
            if (cards[0]) cards[0].classList.add('active');
            
            const sections = document.querySelectorAll('.detail-section');
            sections.forEach(section => {
                if (section) section.classList.remove('active');
            });
            
            const intiSection = document.getElementById('detail-inti');
            if (intiSection) intiSection.classList.add('active');
        } catch (error) {
            console.error('Error in backToMain:', error);
        }
    }

    // === FUNGSI MODAL ===
    function closeModal() {
        try {
            const modal = document.getElementById('news-modal');
            if (modal) {
                modal.classList.remove('active');
                modal.setAttribute('aria-hidden', 'true');
            }
            document.body.style.overflow = 'auto';
        } catch (error) {
            console.error('Error in closeModal:', error);
        }
    }

    // === FUNGSI FILTER BERITA ===
    function filterNews(type) {
        try {
            const newsCards = document.querySelectorAll('.news-card');
            if (!newsCards.length) return;
            
            newsCards.forEach(card => {
                if (card) {
                    if (type === 'all') {
                        card.style.display = 'flex';
                    } else if (type === 'important') {
                        const category = card.getAttribute('data-category');
                        if (category && category.includes('PENTING')) {
                            card.style.display = 'flex';
                        } else {
                            card.style.display = 'none';
                        }
                    }
                }
            });
            
            const buttons = document.querySelectorAll('#pengumuman-page .btn-outline');
            buttons.forEach(btn => {
                if (btn) btn.classList.remove('active');
            });
            
            if (event && event.target) {
                event.target.classList.add('active');
            }
        } catch (error) {
            console.error('Error in filterNews:', error);
        }
    }

    // === LOGIKA TEMA ===
    function applyTheme() {
        try {
            const savedTheme = localStorage.getItem('theme') || 'light';
            const body = document.body;
            const icon = document.getElementById('theme-icon');
            
            if (savedTheme === 'dark') {
                body.classList.add('dark-mode');
                if (icon) icon.classList.replace('fa-moon', 'fa-sun');
            } else {
                body.classList.remove('dark-mode');
                if (icon) icon.classList.replace('fa-sun', 'fa-moon');
            }
        } catch (error) {
            console.error('Error in applyTheme:', error);
        }
    }

    window.toggleTheme = function() {
        try {
            const body = document.body;
            const icon = document.getElementById('theme-icon');
            const isDark = body.classList.toggle('dark-mode');
            
            if (isDark) {
                localStorage.setItem('theme', 'dark');
                if (icon) icon.classList.replace('fa-moon', 'fa-sun');
            } else {
                localStorage.setItem('theme', 'light');
                if (icon) icon.classList.replace('fa-sun', 'fa-moon');
            }
        } catch (error) {
            console.error('Error in toggleTheme:', error);
        }
    };

    // === FUNGSI NAVIGASI ===
    function toggleMenu() {
        try {
            const menu = document.getElementById('side-menu');
            const hamburger = document.querySelector('.hamburger');
            
            if (menu && hamburger) {
                const isActive = menu.classList.toggle('active');
                hamburger.classList.toggle('active');
                hamburger.setAttribute('aria-expanded', isActive);
                document.body.style.overflow = isActive ? 'hidden' : 'auto';
                
                if (isActive) {
                    const firstMenuItem = menu.querySelector('.menu-item');
                    if (firstMenuItem) firstMenuItem.focus();
                }
            }
        } catch (error) {
            console.error('Error in toggleMenu:', error);
        }
    }

    function showPage(pageName) {
        try {
            const pages = document.querySelectorAll('.page-content');
            if (!pages.length) return;
            
            pages.forEach(page => {
                if (page) page.classList.remove('active');
            });
            
            const selectedPage = document.getElementById(pageName + '-page');
            if (selectedPage) {
                selectedPage.classList.add('active');
                
                if (pageName === 'proker' && window.prokerData) {
                    if (window.renderProkerFromFirebase) window.renderProkerFromFirebase();
                    if (window.updateProkerStats) window.updateProkerStats();
                }
                
                if (pageName === 'tentang') {
                    console.log('Halaman Tentang Kami dimuat');
                }
                
                if (pageName === 'profil' && window.pengurusData) {
                    if (window.renderPengurusFromFirebase) window.renderPengurusFromFirebase();
                }
                
                if (pageName === 'kegiatan') {
                    setTimeout(() => {
                        updateCalendar();
                        if (window.renderCalendarDays) {
                            window.renderCalendarDays(window.currentDate.getFullYear(), window.currentDate.getMonth());
                        }
                    }, 100);
                }
            }
            
            const pageTitle = pageName === 'home' ? 'MEDIA OSIM| Official Site' : getPageTitle(pageName) + ' | MEDIA OSIM';
            document.title = pageTitle;
            
            const stateObj = { page: pageName };
            const title = pageTitle;
            const url = pageName === 'home' ? '/' : `/${pageName}`;
            history.pushState(stateObj, title, url);
            
            const menu = document.getElementById('side-menu');
            const hamburger = document.querySelector('.hamburger');
            if (menu && hamburger && menu.classList.contains('active')) {
                menu.classList.remove('active');
                hamburger.classList.remove('active');
                hamburger.setAttribute('aria-expanded', 'false');
                document.body.style.overflow = 'auto';
            }
            
            window.scrollTo({ top: 0, behavior: 'smooth' });
        } catch (error) {
            console.error('Error in showPage:', error);
        }
    }

    function getPageTitle(pageName) {
        const titles = { 
            'home': 'Beranda', 
            'tentang': 'Tentang Kami',
            'proker': 'Program Kerja', 
            'pengumuman': 'Pengumuman OSIM', 
            'kegiatan': 'Kegiatan', 
            'profil': 'Profil Pengurus' 
        };
        return titles[pageName] || 'Halaman';
    }

    window.addEventListener('popstate', function(event) {
        if (event.state && event.state.page) {
            showPage(event.state.page);
        }
    });

    // === FUNGSI KALENDER ===
    function updateCalendar() {
        try {
            const options = { month: 'long', year: 'numeric' };
            const monthElement = document.getElementById('currentMonth');
            if (monthElement) {
                monthElement.textContent = window.currentDate.toLocaleDateString('id-ID', options);
            }
        } catch (error) {
            console.error('Error in updateCalendar:', error);
        }
    }

    function changeMonth(direction) {
        try {
            window.currentDate.setMonth(window.currentDate.getMonth() + direction);
            updateCalendar();
            if (window.renderCalendarDays) {
                window.renderCalendarDays(window.currentDate.getFullYear(), window.currentDate.getMonth());
            }
        } catch (error) {
            console.error('Error in changeMonth:', error);
        }
    }

    // === FUNGSI RENDER KALENDER ===
    window.renderCalendarDays = function(year, month) {
        try {
            const now = new Date();
            const daysInMonth = new Date(year, month + 1, 0).getDate();
            const firstDayOfMonth = new Date(year, month, 1).getDay();
            const calendarGrid = document.getElementById('calendarGrid');
            if (!calendarGrid) return;
            
            const dayNames = calendarGrid.querySelectorAll('.day-name');
            calendarGrid.innerHTML = '';
            dayNames.forEach(name => calendarGrid.appendChild(name.cloneNode(true)));
            
            for (let i = 0; i < firstDayOfMonth; i++) {
                const emptyDay = document.createElement('div');
                emptyDay.className = 'day';
                emptyDay.setAttribute('aria-hidden', 'true');
                calendarGrid.appendChild(emptyDay);
            }
            
            for (let day = 1; day <= daysInMonth; day++) {
                const dayElement = document.createElement('div');
                dayElement.className = 'day';
                dayElement.textContent = day;
                dayElement.setAttribute('role', 'button');
                dayElement.setAttribute('tabindex', '0');
                dayElement.setAttribute('aria-label', `Tanggal ${day}`);
                
                if (day === now.getDate() && year === now.getFullYear() && month === now.getMonth()) {
                    dayElement.style.background = 'rgba(30, 64, 175, 0.2)';
                    dayElement.style.fontWeight = 'bold';
                    dayElement.setAttribute('aria-label', `Hari ini, tanggal ${day}`);
                }
                
                if (typeof window.getEventsForDate === 'function') {
                    const events = window.getEventsForDate(year, month, day);
                    if (events.length > 0) {
                        dayElement.classList.add('event');
                        dayElement.title = events.join('\n');
                        dayElement.setAttribute('aria-label', `${day} - ${events.join(', ')}`);
                        
                        dayElement.addEventListener('click', function() {
                            showEventDetails(day, month, year, events);
                        });
                        
                        dayElement.addEventListener('keydown', function(e) {
                            if (e.key === 'Enter' || e.key === ' ') {
                                e.preventDefault();
                                showEventDetails(day, month, year, events);
                            }
                        });
                    }
                }
                calendarGrid.appendChild(dayElement);
            }
        } catch (error) {
            console.error('Error in renderCalendarDays:', error);
        }
    };

    // === FUNGSI HELPER ===
    function showEventDetails(day, month, year, events) {
        const eventDate = new Date(year, month, day);
        const formattedDate = eventDate.toLocaleDateString('id-ID', { 
            weekday: 'long', 
            year: 'numeric', 
            month: 'long', 
            day: 'numeric' 
        });
        
        alert(`📅 ${formattedDate}\n\n📋 Kegiatan:\n${events.map(e => `• ${e}`).join('\n')}`);
    }

    function subscribeNewsletter() {
        const email = prompt('Masukkan email Anda untuk berlangganan newsletter:');
        if (email && email.includes('@')) {
            alert('Berlangganan newsletter berhasil! Anda akan mendapatkan notifikasi via email.');
            localStorage.setItem('newsletter_subscription', email);
        } else if (email) {
            alert('Email tidak valid. Silakan coba lagi.');
        }
    }

    function refreshProkerData() {
        if (window.renderProkerFromFirebase) {
            window.renderProkerFromFirebase();
            window.updateProkerStats();
            alert('Data program kerja diperbarui!');
        }
    }

    function activateReminders() {
        if (Notification.permission === 'granted') {
            alert('Pengingat sudah aktif! Anda akan mendapatkan notifikasi untuk kegiatan mendatang.');
        } else if (Notification.permission !== 'denied') {
            Notification.requestPermission().then(permission => {
                if (permission === 'granted') {
                    alert('Pengingat diaktifkan! Anda akan mendapatkan notifikasi untuk kegiatan mendatang.');
                }
            });
        } else {
            alert('Izin notifikasi ditolak. Silakan aktifkan manual di pengaturan browser.');
        }
    }

    function showJoinInfo() {
        alert('Untuk bergabung dengan OSIM:\n\n1. Ikuti pengumuman pendaftaran di awal tahun ajaran\n2. Siapkan CV dan motivation letter\n3. Ikuti proses seleksi\n\nHubungi admin untuk info lebih lanjut.');
    }

    // Pesan konfirmasi
    console.log('Aplikasi MEDIA OSIMsiap digunakan!');
  </script>

</body>
</html>
