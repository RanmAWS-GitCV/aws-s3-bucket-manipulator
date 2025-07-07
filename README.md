# AWS S3 Bucket Manipulator 🪣

A simple Python-based command-line tool to interact with your AWS S3 environment.  
It allows you to list, create, and delete S3 buckets using `boto3`.

>⚠️ This is a learning project and not intended for production use. Some error handling and validations are simplified or missing. Use with caution on live AWS environments.


---

## 🚀 Features

- ✅ List all existing S3 buckets in your account
- ✅ Create new S3 buckets in a specified AWS region
- ✅ Delete existing S3 buckets with account ID verification
- ✅ Simple UI through command-line prompts
- ✅ Built using `boto3` and Python 3

---

## 🛠 Requirements

- Python 3.x
- AWS credentials configured (via `~/.aws/credentials` or environment variables)
- `boto3` installed

Install with:

```bash
pip install boto3

▶️ How to Run

python s3_bucket_manipulator.py

Follow the prompts to:

    Authenticate

    Choose between listing, creating, or deleting S3 buckets

⚙️ AWS Permissions

Make sure the user or role executing this tool has the following permissions:

    s3:ListBucket

    s3:CreateBucket

    s3:DeleteBucket

    sts:GetCallerIdentity

📦 File Structure

s3_bucket_manipulator.py       # The main script
README.md        # Project documentation

📚 What I Learned

This project helped me practice:

    Using boto3 to interact with AWS services

    Managing basic AWS credentials and permissions

    Writing basic error handling for real-world use

    Designing a minimal CLI-based user experience

