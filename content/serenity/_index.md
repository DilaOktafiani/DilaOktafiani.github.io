---
title: Serenity
summary: My courses
type: landing

cascade:
  - target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: serenity
    content:
      title: Serenity
      filters:
        folders:
          - serenity
    design:
      view: article-grid
      columns: 2

  - block: content
    id: youtube-playlist-section
    content:
      title: Serenity Playlist
      body: |
        <h2>Enjoy the Serenity Playlist</h2>
        <p>Relax with these soothing tracks:</p>

        <!-- NCT 2021 Beautiful -->
        <div class="youtube-video">
          <h3>NCT 2021 - Beautiful</h3>
          <iframe width="560" height="315" src="https://www.youtube.com/embed/tnyQbPIwyKE" 
            title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen></iframe>
        </div>

        <!-- Treasure - Slowmotion -->
        <div class="youtube-video">
          <h3>Treasure - Slowmotion</h3>
          <iframe width="560" height="315" src="https://www.youtube.com/embed/GGtUL0JRn-E" 
            title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen></iframe>
        </div>

        <!-- Taeyeon - Dream -->
        <div class="youtube-video">
          <h3>Taeyeon - Dream</h3>
          <iframe width="560" height="315" src="https://www.youtube.com/embed/aPGrQ9Xygxg" 
            title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen></iframe>
        </div>

        <!-- Hannah Bahng - Perfect Blues -->
        <div class="youtube-video">
          <h3>Hannah Bahng - Perfect Blues</h3>
          <iframe width="560" height="315" src="https://www.youtube.com/embed/M-9PLDrC_vQ" 
            title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen></iframe>
        </div>

    design:
      view: article-grid
      columns: 1
---
