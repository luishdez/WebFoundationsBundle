
# WebFoundationsBundle

## Global variables

    wf_html_language # default: app.session.locale
    wf_google_analytics_code

## Blocks

    wf_meta
        wf_meta_charset # default: utf-8
        wf_meta_viewport # default: width=device-width,initial-scale=1        
        wf_meta_title
        wf_meta_description
        wf_meta_author
        wf_meta_favicon # default: {{asset('favicon.ico')}}

    wf_head
        wf_stylesheet
        wf_head_js

    wf_body
        wf_chromeframe
        wf_body_content
        wf_bottom_js
        wf_google_analytics