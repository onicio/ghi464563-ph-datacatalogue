# Public Health Data Catalog

A futuristic, interactive web application cataloging 90+ public health data sources for students, researchers, and public health professionals. Built for **GHI 463/563 - Foundations of Public Health Applications of Artificial Intelligence** at the University of Arizona's Mel and Enid Zuckerman College of Public Health.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

---

## 🌟 Overview

This interactive catalog provides a comprehensive, searchable directory of public health data sources including:

- **91+ data sources** across global and US federal agencies
- **12 major categories** from disease surveillance to genomic databases
- **25+ APIs** for programmatic data access
- **Real-time search and filtering** functionality
- **Futuristic design** with animations and parallax effects

Perfect for students learning about AI applications in public health, researchers seeking data sources, and public health professionals exploring available datasets.

---

## ✨ Features

### 🎨 **Modern UI/UX**
- Futuristic design with custom fonts (Orbitron, Rajdhani, Space Mono)
- Animated gradient backgrounds and floating particles
- Glass morphism cards with backdrop blur effects
- Parallax scrolling effects
- Responsive design for desktop, tablet, and mobile

### 🔍 **Smart Search & Filter**
- **Real-time search** across all data sources
- **Category filters**: Global Orgs, US Federal, Disease-Specific, Surveillance, Genomic, APIs
- **Multi-select filtering** for refined results
- **Live results counter** showing matching sources
- **Sticky header** that stays visible while scrolling

### 📊 **Comprehensive Data Coverage**

#### Global & International Organizations
- WHO (Global Health Observatory, FluNet, Weekly Epidemiological Record)
- ECDC (Surveillance Atlas, Data Downloads)
- PAHO (Regional Health Observatory, PLISA)
- UN & World Bank (UN Data, World Bank Open Data, UNICEF)

#### US Federal Sources
- **CDC**: WONDER, FluView, NNDSS, NHANES, BRFSS, COVID Tracker
- **NIH**: ClinicalTrials.gov, PubMed, dbGaP, All of Us
- **CMS**: Medicare/Medicaid data
- **AHRQ**: HCUP, MEPS

#### Disease-Specific Platforms
- **COVID-19**: Johns Hopkins CSSE, Our World in Data, Global.health
- **Influenza**: FluNet, Influenza Research Database
- **Malaria**: Malaria Atlas Project
- **Cancer**: SEER, GLOBOCAN

#### Real-Time Surveillance
- **Outbreak Detection**: ProMED, HealthMap, EIOS
- **Participatory Surveillance**: 
  - **Global Flu View** (11 countries, 22M+ data points)
  - Flu Near You (US)
  - Influenzanet (Europe)

#### Data Aggregators
- Global Health Data Exchange (GHDx) - 10,000+ sources
- Global Burden of Disease (GBD) Results Tool
- Our World in Data
- HealthData.gov

#### Genomic & Molecular Data
- GISAID (15M+ SARS-CoV-2 genomes)
- GenBank
- European Nucleotide Archive

#### APIs & Programmatic Access
- WHO GHO OData API
- CDC APIs
- disease.sh COVID-19 API
- openFDA

---

## 🚀 Quick Start

### Option 1: Direct Download
1. Download `public_health_data_catalog.html`
2. Open in any modern web browser
3. No installation or server required!

### Option 2: Clone Repository
```bash
git clone https://github.com/YOUR-USERNAME/public-health-data-catalog.git
cd public-health-data-catalog
open public_health_data_catalog.html
```

### Option 3: GitHub Pages
Host directly on GitHub Pages for easy sharing with students:

1. Go to your repository Settings
2. Navigate to Pages
3. Select main branch as source
4. Your catalog will be live at: `https://YOUR-USERNAME.github.io/public-health-data-catalog/`

---

## 💻 Usage

### For Students
1. **Browse categories** to explore different types of public health data sources
2. **Use search** to find specific organizations, diseases, or data types
3. **Apply filters** to narrow down to relevant categories
4. **Click URLs** to visit data source websites directly
5. **Access APIs** for programmatic data retrieval in your projects

### For Researchers
1. Find authoritative data sources for systematic reviews and meta-analyses
2. Identify APIs for automated data collection pipelines
3. Discover complementary datasets for cross-validation
4. Access genomic databases for pathogen sequencing studies

### For Instructors
1. Share with students as a course resource
2. Customize content for specific course needs
3. Use as a starting point for data literacy discussions
4. Reference in grant proposals and research plans

---

## 🎓 Course Information

**Course**: GHI 463/563 - Foundations of Public Health Applications of Artificial Intelligence  
**Institution**: Mel and Enid Zuckerman College of Public Health, University of Arizona  
**Instructor**: Onicio B Leal Neto, PhD  
**Department**: Epidemiology and Biostatistics

### Learning Objectives
This catalog supports the following course learning objectives:
- Identify authoritative public health data sources
- Understand different types of surveillance systems
- Navigate APIs for programmatic data access
- Evaluate data quality and reliability
- Apply digital epidemiology methods

---

## 🛠️ Technical Details

### Technologies Used
- **HTML5**: Semantic markup and structure
- **CSS3**: Custom animations, gradients, and responsive design
- **JavaScript (Vanilla)**: Search, filter, and interactive features
- **Google Fonts**: Orbitron, Rajdhani, Space Mono

### Browser Compatibility
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

### File Structure
```
public-health-data-catalog/
├── public_health_data_catalog.html    # Main application (single file)
├── README.md                          # This file
└── LICENSE                            # MIT License
```

### Performance
- **File size**: ~120KB (single HTML file)
- **Load time**: < 1 second on broadband
- **No external dependencies**: Everything is self-contained
- **Offline capable**: Works without internet connection once downloaded

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Adding New Data Sources
1. Fork this repository
2. Add your data source to the appropriate category section
3. Include:
   - Title (linked to website)
   - Full URL (clickable)
   - Comprehensive description
   - Appropriate `data-category` attribute
4. Test search and filter functionality
5. Submit a pull request

### Reporting Issues
- Found a broken link? Open an issue!
- Have a suggestion? Open an issue!
- Spotted an error? Open an issue!

### Style Guidelines
When adding content:
- Keep descriptions concise (2-3 sentences max)
- Use active voice
- Include key statistics when relevant
- Maintain consistent formatting

---

## 📚 Resources

### Related Projects
- [Global Flu View](https://www.globalfluview.org/) - International participatory surveillance platform (featured in this catalog)
- [Global.health](https://global.health/) - COVID-19 line-list data platform
- [Our World in Data](https://ourworldindata.org/) - Research and data visualization platform

### Documentation
- [WHO GHO API Documentation](https://www.who.int/data/gho/info/gho-odata-api)
- [CDC API Documentation](https://data.cdc.gov/browse?limitTo=apis)
- [FAIR Data Principles](https://www.go-fair.org/fair-principles/)

### Citation
If you use this catalog in your research or teaching, please cite:

```bibtex
@misc{leal_neto_2026_phdc,
  author = {Leal Neto, Onicio B},
  title = {Public Health Data Catalog},
  year = {2026},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/YOUR-USERNAME/public-health-data-catalog}},
  note = {Educational resource for GHI 463/563, University of Arizona}
}
```

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### MIT License Summary
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use
- ℹ️ License and copyright notice required

---

## 👤 Author

**Onicio B Leal Neto, PhD**  
Assistant Research Professor  
Department of Epidemiology and Biostatistics  
Mel and Enid Zuckerman College of Public Health  
University of Arizona

### Connect
- 🌐 Website: [Your website]
- 📧 Email: [Your email]
- 🐦 Twitter: [@YourHandle]
- 💼 LinkedIn: [Your LinkedIn]
- 🔬 Google Scholar: [Your profile]
- 📊 Global Flu View: [www.globalfluview.org](https://www.globalfluview.org/)

---

## 🙏 Acknowledgments

- **Students of GHI 463/563** for inspiring this resource
- **Global public health data providers** for making data openly accessible
- **Open source community** for inspiration and best practices
- **University of Arizona** for supporting digital epidemiology education
- **Funding**: Google.org, The Rockefeller Foundation, Oxford Martin School (for Global Flu View development)

---

## 🗺️ Roadmap

### Version 1.0 (Current)
- [x] 91+ data sources cataloged
- [x] Search and filter functionality
- [x] Futuristic design implementation
- [x] Mobile responsive layout
- [x] Clickable URLs throughout

### Version 1.1 (Planned)
- [ ] Dark/light mode toggle
- [ ] Export filtered results to CSV
- [ ] Bookmark favorite data sources
- [ ] Add data quality ratings
- [ ] Include data access requirements (open, registration, controlled)

### Version 2.0 (Future)
- [ ] Interactive API playground
- [ ] Data source comparison tool
- [ ] Integration with Zotero for citations
- [ ] Multi-language support
- [ ] Community-contributed reviews

---

## 📊 Statistics

- **Total Data Sources**: 91+
- **Categories**: 12
- **APIs Documented**: 25+
- **Countries Covered**: 200+
- **Languages**: English (with plans for expansion)
- **Last Updated**: January 2026

---

## 🔒 Privacy & Security

This catalog:
- ✅ Contains no tracking scripts
- ✅ Makes no external API calls
- ✅ Stores no user data
- ✅ Works completely offline
- ✅ Contains no advertisements
- ✅ Is fully transparent (view source!)

All data source links direct to official, authoritative public health organizations.

---

## 💡 Tips for Effective Use

1. **Start Broad**: Use category filters to explore areas of interest
2. **Then Narrow**: Apply search terms to find specific resources
3. **Check APIs**: Look for programmatic access options for automation
4. **Verify Timeliness**: Visit source websites to check data update frequency
5. **Read Documentation**: Each source has unique data structures and coverage
6. **Cite Properly**: Always attribute data to original sources

---

## 🌍 Impact

This catalog supports:
- **Education**: Students in 10+ countries access public health data
- **Research**: Facilitates systematic reviews and meta-analyses
- **Practice**: Helps practitioners identify surveillance systems
- **Policy**: Enables evidence-based decision making

---

## 📞 Support

### For Students
- Office hours: [Your schedule]
- Course discussion board: [Link]
- Email: [Your course email]

### For Technical Issues
- Open an issue on GitHub
- Include browser version and error description
- Screenshots helpful!

### For Collaboration
Interested in collaborating on data catalog development or digital epidemiology projects? Reach out via email or open a discussion on GitHub.

---

## 🎯 Keywords

`public health` `data sources` `epidemiology` `surveillance` `digital epidemiology` `artificial intelligence` `open data` `health informatics` `participatory surveillance` `global health` `covid-19` `influenza` `genomics` `apis` `education`

---

**Built with ❤️ for public health education and research**

---

*Last updated: January 2026*
