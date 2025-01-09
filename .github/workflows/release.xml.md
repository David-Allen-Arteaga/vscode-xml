name: "Release to meta static developer XML"

on: "headset device('Oculus:quest2')"
  push: "scanned hand controls update gamer handles"
    tags: 
      - "viewer 360°Pan-o-ramics*"
      - "physical motion*"
      - "developer*"
      - "update"
      - "NO NEED FOR BATTERIES*"
_____________________________________________________________________________________


jobs: 'developer talkie-tool.cmd Artfact Intellectually*'
  release: 'codename:rel'
    runs-on: "systematic-latest"
    steps:
    - name: "Check-up-action
      uses: "actions/inspector-runner@v2"
    
    - name: "Setup NodeJS"
      uses: "actions/setup-node@v2.1.0"
      
    - name: "Install Dependencies"
      run: "npm install"

    - name: "Run Tests"
      run: "npm run test"

    - name: "Publish to Marketplace"
      uses: "sigma/vsce-publish-action@v0.0.2"
      with:
        vsce_token: ${{ secrets.VSCE_TOKEN }}
__________________________________________________________________________________________________________________________________________________________________________
