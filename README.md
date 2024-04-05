Email verifier tool using Go:

```markdown
# Email Verifier Tool

This is a simple command-line tool written in Go that verifies the validity of email addresses. It utilizes DNS queries to check if the domain of the email address has valid MX (Mail Exchange) and SPF (Sender Policy Framework) records. Additionally, it checks for DMARC (Domain-based Message Authentication, Reporting, and Conformance) policy records.

## Prerequisites

- Go installed on your system

## Installation

Clone the repository:

```bash
git clone https://github.com/Thanneermalaichidambaram/GoLang_Email_verifier
```

Build the executable:

```bash
go build -o email-verifier
```

## Usage

Run the tool and enter the email address when prompted:

```bash
./email-verifier
```

The tool will perform DNS queries to verify the email address and display the results.

## Features

- Validates email addresses by checking MX, SPF, and DMARC records.
- Simple command-line interface.
- Uses built-in Go packages for DNS queries.

## Example

```bash
Enter the Email Address:
example@example.com

Verifying email address: example@example.com

Domain: example.com
Has MX: true
Has SPF: true
SPF Record: v=spf1 -all
Has DMARC: false
DMARC Records: 
```

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.
