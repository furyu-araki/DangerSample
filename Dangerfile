# github comment settings
github.dismiss_out_of_range_messages

# Warn when PR has no assignees
warn("A pull request is recommended to have some assignees") if github.pr_json["assignee"].nil?

# ktlint
checkstyle_format.base_path = Dir.pwd
checkstyle_format.report 'app/build/reports/ktlint/ktlint-debug.xml'