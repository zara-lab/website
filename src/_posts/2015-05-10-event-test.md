---
layout: default
title:  "Event Test"
date:   2015-05-10 16:58:04
categories: events
summary: Testing Events Summary
---

# Testing Events

```ruby
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
```
