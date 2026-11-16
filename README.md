# go.iceandclimate.org

Short links behind printed QR codes. Each `<name>.html` file is one link:
it counts the visit in GoatCounter, then forwards the visitor.

| Short link | File | Goes to |
|---|---|---|
| https://go.iceandclimate.org/licor | `licor.html` | LI-COR Cloud dashboard |

## Change where a QR code goes

1. Open the file (e.g. `licor.html`) on GitHub and click the pencil icon.
2. Edit the `href="..."` on the `<a id="dest">` line. That's the only place the destination is set.
3. Commit. The change is live in about 1–10 minutes (GitHub build + cache).

The printed QR code never changes.

## See scan counts

https://willkochtitzky.goatcounter.com — each file shows up as its own path (e.g. `/licor`).

## Add another QR code

Copy `licor.html` to `newname.html`, change the `href` and the `<title>`,
commit, then make a QR code for `https://go.iceandclimate.org/newname`.
