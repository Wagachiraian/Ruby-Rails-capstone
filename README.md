# Prompt-Powered Kickstart: A Beginner's Toolkit for Ruby on Rails

## 1. Title & Objective

**Title:** Prompt-Powered Kickstart: A Beginner's Toolkit for Ruby on Rails

**What technology did I choose?** Ruby on Rails

**Why did I choose it?**
I chose Ruby on Rails because I am a complete beginner in software development 
and wanted to learn a beginner friendly web framework. Rails is known for being 
easy to read and understand, and it allows you to build a working web application 
very quickly. Big companies like Shopify, GitHub and Airbnb were built using Rails.

**What is the end goal?**
Build a simple working web page and a JSON API endpoint using Ruby on Rails 
and document the entire learning journey using AI prompts.

---

## 2. Quick Summary of Ruby on Rails

**What is it?**
Ruby on Rails is a web application framework written in the Ruby programming 
language. It helps developers build websites and web apps faster by providing 
ready-made solutions for common tasks.

**Where is it used?**
It is used for building web applications and APIs.

**Real world example:**
Shopify, GitHub and Airbnb were all built using Ruby on Rails.

---

## 3. System Requirements

- OS: Windows 10
- Ruby 4.0.3
- Rails 8.1.3
- SQLite3 2.9.3
- Node.js LTS
- VS Code
- Git (via GitHub Desktop)

---

## 4. Installation & Setup Instructions

### Step 1 - Install Ruby
Download from: https://rubyinstaller.org/downloads/
Download Ruby+Devkit 4.0.3-1 (x64)
Run installer and select option 1 when prompted.

Verify:
### Step 2 - Install Rails
Verify:
### Step 3 - Install SQLite3
### Step 4 - Install Node.js
Download from: https://nodejs.org/en
Download the LTS version and install.

### Step 5 - Create Rails App
### Step 6 - Generate Pages Controller
### Step 7 - Generate API Controller
### Step 8 - Run the Server
---

## 5. Minimal Working Example

### Web Page
File: app/views/pages/home.html.erb
```html
<div style="text-align: center; font-family: Arial; margin-top: 100px;">
  <h1>Hello World!</h1>
  <h2>Welcome to My Ruby on Rails App</h2>
  <p>Built by Ian Wagachiraian - Moringa AI Capstone Project</p>
  <p>Powered by Ruby on Rails</p>
</div>
```
Visit: http://localhost:3000

### JSON API Endpoint
File: app/controllers/api_controller.rb
```ruby
class ApiController < ApplicationController
  def hello
    render json: { 
      message: "Hello from Ruby on Rails API!",
      status: "success",
      author: "Ian Wagachiraian"
    }
  end
end
```
Visit: http://localhost:3000/api/hello

**Expected Output:**
```json
{"message":"Hello from Ruby on Rails API!","status":"success","author":"Ian Wagachiraian"}
```

---

## 6. AI Prompt Journal

**Prompt 1:**
I am a very new person in coding and software development but I want to learn 
about Ruby and Rails and how to make a simple web using them. Tell me what is 
Ruby on Rails and why should a beginner learn it? Also give me the following:
1. What to Install in order to begin the learning
2. The process of installing whatever is needed.
3. Give me a recap of what I will learn numbered as topics so that its clear.

Ai help: Through Ai I was able to install all the tools required to be able to work with Ruby language.

**Prompt 2:**
I have Installed all the required tools for starting. Now i want you to take me 
step after step in setting everything up and connecting it together and even to 
Github. What we will do:
1. I will be sending you screenshots after every step so that you can tell me the next step.
2. Every thing you provide please give it as a code so that it can be easy to copy and paste.
3. If you see anything Wrong in the screenshots tell me and explain it using very simple language.
4. Lets do this!
AI help:AI managed to take me through every single step in setting up by understanding my screen shots and following them until everything was set up. 
---

## 7. Common Issues & Fixes

| Issue | Cause | Fix |
|-------|-------|-----|
| 'gem' is not recognized | Ruby not installed properly | Reinstall Ruby and reopen terminal |
| Windows warned about installer | Windows security warning | Click "Keep anyway" - the file is safe |
| Cannot edit in read-only editor | File opened in wrong panel | Click the file directly in the sidebar |
| The system cannot find the path | Already in the correct folder | Remove "Desktop\" from the cd command |

---

## 8. References

- Ruby on Rails Official Site: https://rubyonrails.org
- Ruby Installer for Windows: https://rubyinstaller.org
- Node.js: https://nodejs.org
- VS Code: https://code.visualstudio.com
- GitHub: https://github.com