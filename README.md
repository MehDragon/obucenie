{
  "branches": {
    "main": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C1",
      "id": "main",
      "type": "branch"
    },
    "bugFix": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C1",
      "id": "bugFix",
      "type": "branch"
    }
  },
  "commits": {
    "C0": {
      "type": "commit",
      "parents": [],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 09:50:22 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C0",
      "rootCommit": true
    },
    "C1": {
      "type": "commit",
      "parents": [
        "C0"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 09:50:22 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C1"
    }
  },
  "tags": {},
  "HEAD": {
    "id": "HEAD",
    "target": "bugFix",
    "type": "general ref"
  }
}
