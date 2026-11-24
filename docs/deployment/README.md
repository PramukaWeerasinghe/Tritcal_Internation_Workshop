# Workshop deployment checklist
1. Check out the approved release.
2. Run: python -m unittest discover -s tests -v
3. Run: python src/pos.py
4. Record the release tag and customer approval.
5. For real deployments, verify backup, environment,
   migration, secrets, rollback and support owner.
