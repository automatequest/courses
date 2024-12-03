# Tech Courses Documentation

    This project uses Antora to manage and build technical course documentation.

    ## Workflow

    1. **Add a Course**: Create a new Asciidoc file in `modules/ROOT/pages/`.
    2. **Update Navigation**: Add a link to the new course in `modules/ROOT/nav.adoc`.
    3. **Build the Site**: Run `antora antora-playbook.yml` to generate the site.

    ## Adding/Modifying Content

    - To add a new course, create a new `.adoc` file in the `pages` directory.
    - Update the `nav.adoc` file to include the new course in the navigation.
    - Modify existing courses by editing their respective `.adoc` files.

    ## Deploying to Netlify

    1. **Connect to Netlify**: Log in to your Netlify account and create a new site from Git.
    2. **Configure Build Settings**: Ensure the build command is `antora antora-playbook.yml` and the publish directory is `public`.
    3. **Deploy**: Once configured, Netlify will automatically build and deploy your site whenever you push changes to the repository.
