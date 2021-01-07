# resulta
## Web Development Challenge

- Drupal 7 module developed
- used hooks hook_block_view and resulta_block_info to create blocks
- function getData developed with the following function:
    - file_get_contents() function used to get contents from API endpoint URL
    - json_decode() function used to decode the json content and saved in an array (team_arr)
    - bootstrap table created to show the data
    - the block is rendered in the front page

