import uuid
import datetime

def generate_unique_code():
    timestamp = datetime.datetime.now().isoformat()
    unique_id = uuid.uuid4()
    return f"Generated at {timestamp} with ID: {unique_id}"

if __name__ == "__main__":
    print(generate_unique_code())
