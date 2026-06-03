<style>
  /* OVERRIDE THEME DEFAULTS: 
     Remove the invisible right-side padding reserved for the TOC */
  .page {
    padding-right: 0 !important;
  }

  /* Force the content area to extend fully to the right edge */
  .page__content {
    width: 100% !important;
    padding-right: 0 !important;
  }

  /* Dynamic Project Card Grid */
  .projects-list {
    display: flex;
    flex-direction: column;
    gap: 24px;
    margin-top: 15px;
    width: 100%;
  }

  /* Wide Rectangular Project Card stretching to full width */
  .project-card {
    display: flex;
    width: 100%;
    background: #ffffff;
    border: 1px solid #e5e7eb;
    border-radius: 10px;
    overflow: hidden;
    text-decoration: none !important;
    color: inherit !important;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.04);
    transition: all 0.25s ease-in-out;
  }

  /* Card Hover Animation */
  .project-card:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 15px rgba(0, 0, 0, 0.08);
    border-color: #cbd5e1;
  }

  /* Preview Image Sizing (proportional to the wider card) */
  .project-img-wrapper {
    width: 28%;
    min-width: 180px;
    background: #f8fafc;
    position: relative;
    overflow: hidden;
  }

  .project-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
    transition: transform 0.3s ease;
  }

  .project-card:hover .project-img {
    transform: scale(1.02);
  }

  /* Text Layout inside the Card */
  .project-content {
    padding: 24px;
    width: 72%;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .project-title {
    margin: 0 0 6px 0 !important;
    font-size: 1.4rem !important;
    font-weight: 700 !important;
    color: #292b2c;
    transition: color 0.2s ease;
    line-height: 1.3;
  }

  .project-card:hover .project-title {
    color: #2563eb;
  }

  .project-timeline {
    font-size: 0.75rem;
    color: #64748b;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    margin-bottom: 10px;
  }

  .project-summary {
    font-size: 0.95rem;
    line-height: 1.5;
    color: #475569;
    margin: 0 0 14px 0;
  }

  .project-link-text {
    font-size: 0.88rem;
    font-weight: 600;
    color: #2563eb;
    display: inline-flex;
    align-items: center;
  }

  .project-link-text svg {
    margin-left: 4px;
    transition: transform 0.2s ease;
  }

  .project-card:hover .project-link-text svg {
    transform: translateX(3px);
  }

  /* Smooth mobile transitions when screen sizes shrink */
  @media (max-width: 640px) {
    .project-card { flex-direction: column; }
    .project-img-wrapper { width: 100%; height: 160px; }
    .project-content { width: 100%; padding: 15px; }
  }
</style>
