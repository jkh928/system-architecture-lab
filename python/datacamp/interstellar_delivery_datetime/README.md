### Interstellar Delivery: Python Datetime Logic
This project focuses on building reusable utility functions to handle space logistics scheduling using Python's datetime module.

#### 🚀 Logic & Sequence
Following a Think-First approach, this script handles three core logistics requirements:   
* Date Formatting: Translating Unix timestamps (computer-readable) into human-readable strings.   
* Landing Estimation: Using timedelta to project arrival dates based on days in transit.   
* Deadline Tracking: Calculating the integer count of days remaining until a delivery deadline.

#### 🛠️ Protocols Applied
* Data Shape: Utilized .days attribute to ensure return types are clean integers for downstream processing.
* Complexity Filter: Optimized for $O(1)$ time complexity by using native Python subtraction for time differences.
* Format Control: Implemented .strftime() for consistent "DD-MM-YYYY" output.