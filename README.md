/* Reset y Configuración Base */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    color: #111827;
    background-color: #F8F9FA;
}

/* Variables CSS */
:root {
    --bg-page: #F8F9FA;
    --bg-surface: #FFFFFF;
    --text-primary: #111827;
    --text-secondary: #6B7280;
    --text-accent: #0057B7;
    --border-subtle: #E5E7EB;
    --primary-500: #0057B7;
    --primary-600: #004C9F;
    --primary-100: #D6E6F7;
    --success: #10B981;
    --error: #EF4444;
    
    /* Espaciado */
    --space-xs: 8px;
    --space-sm: 16px;
    --space-md: 24px;
    --space-lg: 32px;
    --space-xl: 48px;
    --space-xxl: 64px;
    --space-xxxl: 96px;
}

/* Utilidades */
.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 var(--space-md);
}

/* Header */
.header {
    background-color: var(--bg-surface);
    border-bottom: 1px solid var(--border-subtle);
    height: 80px;
    position: sticky;
    top: 0;
    z-index: 1000;
}

.nav {
    height: 100%;
}

.nav-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 var(--space-md);
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.nav-logo {
    display: flex;
    align-items: center;
    gap: var(--space-sm);
}

.logo-img {
    width: 40px;
    height: 40px;
    object-fit: contain;
}

.nav-title {
    font-size: 20px;
    font-weight: 600;
    color: var(--text-primary);
}

.nav-back {
    background-color: var(--primary-500);
    color: white;
    padding: 12px 20px;
    border-radius: 8px;
    text-decoration: none;
    font-weight: 500;
    transition: background-color 250ms ease-out;
}

.nav-back:hover {
    background-color: var(--primary-600);
}

/* Main Content */
.main {
    padding: var(--space-xxl) 0;
}

.hero-section {
    text-align: center;
    margin-bottom: var(--space-xxxl);
}

.page-title {
    font-size: 48px;
    font-weight: 700;
    color: var(--text-primary);
    margin-bottom: var(--space-md);
}

.page-subtitle {
    font-size: 20px;
    color: var(--text-secondary);
    font-weight: 500;
}

/* QR Section */
.qr-section {
    background-color: var(--bg-surface);
    border-radius: 16px;
    padding: var(--space-xxl);
    margin-bottom: var(--space-xxxl);
    box-shadow: 0px 8px 24px rgba(0, 87, 183, 0.08);
}

.qr-container {
    display: flex;
    align-items: center;
    gap: var(--space-xl);
    max-width: 800px;
    margin: 0 auto;
}

.qr-code {
    flex-shrink: 0;
