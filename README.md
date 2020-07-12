```go
package lawzava

import "http"

func handleReadme(w http.ResponseWriter, r *http.Request) {
    http.Redirect(w, r, "https://lawzava.com", http.StatusMovedPermanently)
}
```

###### _i.e. go here: [https://lawzava.com](https://lawzava.com)_
