# Clone the target repository (if you haven't already)
git clone https://github.com/ItcProjects-R4/GHR4_DAT2_S1_PROJECT1.git
cd GHR4_DAT2_S1_PROJECT1

# Download the file from your source repo
git clone https://github.com/nadaalgohary07-hash/powerbi_project.git
cp powerbi_project/"supermarket1_sales (2).pbix" .

# Add and commit
git add "supermarket1_sales (2).pbix"
git commit -m "Add PowerBI supermarket sales file"

# Push to target repo
git push origin main
