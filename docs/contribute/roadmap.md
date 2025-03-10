# Project Roadmap

## feat-course-search-2025-spring

Status: Under Development
Release Data: 2025/03/22 (目標)

### Features (In order of their priorities)

1. Course Search Feature
   1. Create the course search api with NestJS?
2. Super Courses Compatibility
3. Google Drive Sync Feature
4. Internationalisation with i18n

### Updates

1. Change Schedule Data Structure
   1. Make it machine readable (no "3/M"!)
2. Add Status Management Library
   1. Jotai, Redux?
3. Add Useful Links

### TODO

1. Should add converting feature from old data structure
   1. Detect the existence of old data and replace it with new one after user's confirmation: "古いタイプのデータが見つかりました，旧式を使い続けるか，データを変換して新式を使うか選択してください"
   2. Just leave old type data there (just in case)
2. Deploy "development" branch as alpha ver. on alpha.catalogue.icu
   1. Add link to alpha ver. to the original app
3. Move the original app to "www.catalogue.icu/classic-2024"
