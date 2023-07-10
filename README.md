# EC2_Troubleshooting_for_Unreachable-Webpages

# Check
- instance summary
- SG Inboumd rules
- SG Outbound rules
- subnet all traffic is allowed or NOT (?)
## If 'website too long to respond' then recheck your internet speed
- check http or https in the url

# if NOT solved yet, then:
- Connect EC2 with terminal
- Commands:
  sudo yum update -y  (forLinuxx)
  sudo apt-get update (for Debian / Ubuntu)
  sudo service httpd status
  sudo service httpd restart

## If NOT showing 'active', then reboot:
  sudo chkconfig httpd on
  
# Read AWS website
- Verify first, Checklist link: https://repost.aws/questions/QUCLwGlwD7RxefwhfoaEGFsg/issue-connecting-ec2-instance
- Check AWS EC2 Knowledge center: https://repost.aws/knowledge-center/ec2-instance-hosting-unresponsive-website

# Hopefully, Troubles are SHOOTED !!
