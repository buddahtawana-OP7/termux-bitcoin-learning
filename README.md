
# termux-bitcoin-learning
My journey learning Git and hunting bounties 
# 1. Go to your repo folder
cd \~/termux-bitcoin-learning

# 2. Update README with proper content
cat > README.md << 'EOF'
# Termux Bitcoin Learning Journey

**Goal**: Master Git + hunt and complete paid bounties to earn Bitcoin.

**Started**: May 2026  
**Username**: buddahtawana-OP7  
**Current Status**: Learning Git basics in Termux on 4GB device

## Commands Learned
- git config
- git clone
- git status / git add / git commit / git push

## Next Goal
Find and complete my first paid bounty (starting with Algora.io or Gitcoin).

This repo is my public proof of consistent effort.
EOF

# 3. Push the changes
git add README.md
git commit -m "feat: update README with clear goals and progress"
git push origin main