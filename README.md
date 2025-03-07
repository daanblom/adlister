# AdList Fetcher Script

This repository contains a simple bash script designed to fetch, process, and combine multiple ad-blocking lists into a single file (`adlist.txt`). To possibly use with pi-hole or other ad blocking services.

The script performs the following operations:

1. **Fetch** ad block lists from a source (URLs listed in `source.txt`).
2. **Process** the lists into a single, sorted, and unique list.
3. **Clean up** temporary files used during the process.

## Usage

1. **Clone this repository:**

   ```bash
   git clone https://github.com/yourusername/adlist-fetcher.git
   cd adlist-fetcher
   ```

2. **Run the script:**

   The script can be executed by running:

   ```bash
   ./adlist-fetcher.sh
   ```

   This will:

   - Fetch the ad-block lists.
   - Combine them into a single list (`adlist.txt`).

3. **Output:**

   Once the script completes, you'll find a file named `adlist.txt` containing the combined, sorted, and unique list of ad-blocking rules.

The final list will be saved in the `adlist.txt` file, and it will be free from duplicates.

