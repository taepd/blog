---
title: 'blog 커스텀 중'
date: 2021-01-08
category: 'test'
draft: false
---

### 링크 미리보기는 구현하기 힘들듯
- 파싱이 필요한데, 마크다운 상태에서 파싱할 순 없고, 빌드 시점에 생성해주는 라이브러리가 있을 수도 있겠지만 구현하기 어려워 보임
[$card](https://www.acmicpc.net/problem/4949) {: target="_blank"} 속성태그가 먹히지 않음

<a href="https://www.acmicpc.net/problem/4949" target="_blank">https://www.acmicpc.net/problem/4949</a>
html로 대체 가능

### 1.11
- index container max-width 조정
    - layout > index.jsx의 maxWidth: rhythm 값을 조정했음
    -  '../utils/typography' 에서 가져온 속성인데, 알아보자.


<div>
<div style="display: flex;"><a target="_blank" rel="noopener noreferrer" style="display: block; color: inherit; text-decoration: none; flex-grow: 1; min-width: 0px;" href="https://leetcode.com/problems/valid-palindrome/"><div class="" role="button" tabindex="0" style="user-select: none; transition: background 20ms ease-in 0s; cursor: pointer; width: 100%; display: flex; flex-wrap: wrap-reverse; align-items: stretch; text-align: left; overflow: hidden; border: 1px solid rgba(55, 53, 47, 0.16); border-radius: 3px; position: relative; color: inherit; fill: inherit;"><div style="flex: 4 1 180px; padding: 12px 14px 14px; overflow: hidden; text-align: left;"><div style="font-size: 14px; line-height: 20px; color: rgb(55, 53, 47); white-space: nowrap; overflow: hidden; text-overflow: ellipsis; min-height: 24px; margin-bottom: 2px;">Valid Palindrome - LeetCode</div><div style="font-size: 12px; line-height: 16px; color: rgba(55, 53, 47, 0.6); height: 32px; overflow: hidden;">Given a string, determine if it is a palindrome, considering only alphanumeric characters and ignoring cases. Note: For the purpose of this problem, we define empty string as valid palindrome. Example 1: Input: "A man, a plan, a canal: Panama"Output: true Example 2: Input: "race a car"Output: false Constraints: s consists only of printable ASCII characters.</div><div style="display: flex; margin-top: 6px;"><img src="https://notion.so/image/https%3A%2F%2Fleetcode.com%2Ffavicon-192x192.png?table=block&amp;id=037ab35e-fc58-463a-ae03-b8ae9f261b5c&amp;userId=419b8a2d-7d06-4697-b451-00e11d75f0df&amp;cache=v2" style="width: 16px; height: 16px; min-width: 16px; margin-right: 6px;"><div style="font-size: 12px; line-height: 16px; color: rgb(55, 53, 47); white-space: nowrap; overflow: hidden; text-overflow: ellipsis;">https://leetcode.com/problems/valid-palindrome/</div></div></div><div style="flex: 1 1 180px; display: block; position: relative;"><div style="position: absolute; inset: 0px;"><div style="width: 100%; height: 100%;"><img src="https://notion.so/image/https%3A%2F%2Fleetcode.com%2Fstatic%2Fimages%2FLeetCode_Sharing.png?table=block&amp;id=037ab35e-fc58-463a-ae03-b8ae9f261b5c&amp;width=500&amp;userId=419b8a2d-7d06-4697-b451-00e11d75f0df&amp;cache=v2" style="display: block; object-fit: cover; border-radius: 1px; width: 100%; height: 100%;"></div></div></div></div></a></div>
</div>

