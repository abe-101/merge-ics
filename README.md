## merge-ics

This script will get all .ics files (iCalendar files, as
specified in the RFC 2445 specification), read it and
aggregate all events to a new .ics file. If one of the
sourcefiles is not readable (or is not RFC 2445 compatible),
it will be ignored.

## Install Dependencies

```
pip install -r requirements.txt
```

## Usage

```
python merge-ics.py <path to source folder> <name and path for merged file> <name of new calendar>
```

