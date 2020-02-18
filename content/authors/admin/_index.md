---
# Display name
name: William T. Katz

# Username (this should match the folder name)
authors:
- admin

# Is this the primary user of the site?
superuser: true

# Role/position
#role: Senior Software Eng

# Organizations/Affiliations
# organizations:
# - name: Janelia Research Campus
#   url: "http://janelia.org"

# Short bio (displayed in user profile at end of posts)
bio: My research interests include versioned datastores, 3D visualization, and deep learning.

interests:
- Branched Versioning of Data
- 3D Visualization, particularly for image volumes
- Deep Learning

education:
  courses:
  - course: PhD, Biomedical Engineering
    institution: University of Virginia
  - course: MD (Medical Scientist Training Program)
    institution: University of Virginia
  - course: MS coursework, Computer Science
    institution: Stanford University
  - course: BS, Biological Sciences
    institution: Stanford University
  - course: International Baccalaureate
    institution: St. Mary's International, Tokyo, Japan

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
- icon: google-scholar
  icon_pack: ai
  link: https://scholar.google.com/citations?user=M7zclcAAAAAJ&hl=en
- icon: github
  icon_pack: fab
  link: https://github.com/DocSavage
- icon: twitter
  icon_pack: fab
  link: https://twitter.com/WTKatz
- icon: envelope
  icon_pack: fas
  link: '#contact'  # For a direct email link, use "mailto:test@example.org".
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: "billkatz@gmail.com"

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
- Researchers
- Visitors
---
**I like working at the intersection of computer science and biomedical research.**

I'm a research scientist on the FlyEM Team at the Howard Hughes Medical Institute's Janelia Research Campus.  We use cutting-edge electron microscopy to image fruit fly brains at nanometer resolution.  After extracting likely neurons from the 25+ Teravoxel image volumes (through our collaboration with Google Research), our team of bio experts proofread the results.  The result is a connectome, a map of the neural circuits.  I've been designing the [data systems](http://dvid.io) that allow us to flexibly capture versions of our proofreading and all the data we generate while reconsructing the connectome.

I have two research goals in the near future: 

* To create a github-like way of distributing published data and allowing pull requests of changes from other researchers.
* To develop interesting ways to visualize the richness of our nanometer-resolution, segmented image volumes.