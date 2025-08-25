
Manual: Build only	✅	Set VALIDATE_ONLY: true
Manual: Build + Deploy	✅	Set VALIDATE_ONLY: false
Manual: Deploy only	✅	Use release.yaml
Push/PR: Build only	✅	Automatically done
Push/PR: Build + Deploy	✅	Automatically done (since VALIDATE_ONLY logic only applies to manual trigger)
Call deploy from another workflow	✅	release.yaml can be used as reusable
