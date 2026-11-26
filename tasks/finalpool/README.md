# Final pool

77 implemented tasks, collected from the developer branches and matched to the `implemented` entries of the Notion **Task Tracker → Task Status Table**.

Each task directory is copied unchanged from its source branch:

- `fan-dev`: coupon-manager, discount-calculator, loyalty-program, price-tracker
- `gyy`: blog-engine, cms-builder, content-scheduler, robots-handler, social-publisher, tag-manager
- `haoze`: media-organizer, streaming-service, subtitle-generator, video-trimmer
- `jl_dev`: canvas-grade-automation, customer-feedback-processor, email-classification-system, inventory-management, pdf-report-generator
- `junteng_dev`: booking-system, calendar-sync, contact-manager, help-desk, order-processor, product-catalog, reminder-service, shipment-tracker
- `junxian_dev`: qr-generator, social-connector, translation-api
- `lueyang-dev`: activity-logger, client-portal, crm-system, deal-manager, email-campaign, follow-up-reminder, sales-pipeline, territory-manager
- `lv`: analytics-dashboard, chat-bot, feedback-collector, personalization-service, sentiment-analyzer, survey-builder, voice-processor
- `ruige`: canvas-automation, data-analytics, expense-tracker, file-manager, log-analyzer, web-crawler
- `wenshuo-dev`: cache-optimizer, image-processor, scheduler, search-engine
- `xiaochen_dev`: backup-utility, deployment-tool, error-tracker, health-monitor, monitoring-agent, security-scanner, status-checker
- `yuxuan-dev`: asset-optimizer, content-manager, network-analyzer, sync-service, task-scheduler
- `yuzhen-dev`: alert-system, data-validator, form-builder, invoice-generator, payment-processor, permission-manager
- `zhaochen`: certificate-manager, load-balancer, storage-manager, template-engine

## Acceptance checks

Following `tasks/examples/example-task`:

- `docs/task.md` and `docs/agent_system_prompt.md` exist, are non-empty and written in English.
- `docs/user_system_prompt.md`, when present and non-empty, is written in English.
- `evaluation/main.py` exists (existence-only check, as are the optional workspace/preprocess files).

Tasks that failed these checks remain `implementing` in the tracker and are not part of this pool.
