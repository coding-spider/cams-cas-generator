# This is used for triggring CAS statement from CAMS website

It uses puppeteer for automating the statement generation process

# Sample Use
node cams-statement-generator.js --email=test@email.com --password=Demo@123 --fromDate=1992-01-01 --toDate=2021-01-01 --headless

# You can run this in debug mode too
DEBUG=cams node cams-statement-generator.js --email=test@email.com --password=Demo@123 --fromDate=1992-01-01 --toDate=2021-01-01 --headless

# Can disable headless mode for testing
DEBUG=cams node cams-statement-generator.js --email=test@email.com --password=Demo@123 --fromDate=1992-01-01 --toDate=2021-01-01 --headless=false
