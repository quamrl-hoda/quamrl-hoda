raise HTTPError(req.full_url, code, msg, hdrs, fp)
urllib.error.HTTPError: HTTP Error 404: Not Found
import time
import threading
start = time.perf_counter()


url_list = [
    'https://github.com/quamrl-hoda/Amazon-Clone.git'
]

data_list = [ 'data1.txt']

import urllib.request
def file_download(url, filename):
    urllib.request.urlretrieve(url,filename)
threads = []
for i in range(len(url_list)):
    t = threading.Thread(target = file_download, args = (url_list[i], data_list[i]))
    t.start()
    threads.append(t)

for thread in threads:
    thread.join()

end = time.perf_counter()

print(f"the program finished in {round(end - start, 2)} seconds.")
    
