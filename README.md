### Project Idea
Build a web application to create resumes using LaTeX, allowing users to choose from different templates. Users will provide input for their chosen template, generate resumes as PDFs, and have the option to send the PDF resume via email directly from the app.

### Key Features
- **Frontend**: Vue.js UI with smooth transitions and skeleton loaders (using e.g. [Skeleton](https://skeleton.dev/) or Vue built-in loading strategies) to handle content loading.
- **Templates**: Multiple LaTeX-based resume templates for users to pick. Dynamic input forms adapt based on the selected template.
- **Resume Generation**: Take form data, inject it into the selected LaTeX template, and generate a high-quality PDF.
- **Email Integration**: Users can opt to have their generated resume PDF sent to their email address.
- **User Experience**: Responsive, intuitive design, with skeleton screens or loading states while content is being prepared (especially PDF generation or loading large templates).
- **(Optional)**: User authentication for saving resumes, managing templates, or previously generated versions.

### High-Level Stack
- **Frontend**: Vue.js 3 (with Skeleton or similar for loading experience)
- **Backend**: Node.js/Express or Python/Flask API handling PDF generation (using a LaTeX engine like pdfTeX, XeLaTeX) & email sending (SMTP or a service like SendGrid/Mailgun)
- **Storage**: Local (on-the-fly), or database if user accounts/profiles are needed

### Tasks
- [ ] Project setup: Vue.js UI & backend server
- [ ] Implement LaTeX template repository & preview system
- [ ] Build dynamic form generator for selected template fields
- [ ] Integrate LaTeX PDF resume generation
- [ ] Implement frontend skeleton loading components
- [ ] Add send-as-email functionality with PDF attachment
- [ ] Test end-to-end workflow (UI, PDF output, mail)
- [ ] Polish UI/UX

---
_Reference: User wants: latex resume builder webapp, multiple templates, user fills form, PDF output, email sending. Vue.js frontend with skeleton loading._
