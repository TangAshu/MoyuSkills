# 生成模板

先实际打开并输入内置橘猫风格参考；它用于保护黑底、大主体、纵向比较和CT/MRI的视觉处理，仍是AI示意而非医学数据。用户另提供有权使用的对标图时，实际查看后可作为第二张视觉参考，但不能复制其像素、水印或错误。将下方动物替换为今天对象；品种、姿态只确定一套，四行复用。下述是供宿主图像工具使用的提示词正文，不是API参数或固定接口。

Use case: stylized-concept with photorealistic animal rendering and educational imaging illustration.
Asset: a single tall portrait social-media comparison image, approximately 1:2 aspect ratio.
Reference role: The bundled orange-cat image controls the sophisticated dark animal-imaging aesthetic, large subject scale, sparse yellow labels, vertical four-stage reveal, volumetric CT layers and grayscale soft-tissue MRI. It is an illustration, not verified anatomy. If the user supplies another rights-cleared reference, use it only for layout and attraction, not for medical facts. Generate a fresh requested animal; do not trace source pixels or copy a watermark.

Subject: [today's animal], one coherent individual standing in a calm left-facing full-body pose. All four rows keep the same silhouette, body proportions, head, feet, ears and tail position, almost the same display scale.
Layout: one black continuous background, FOUR horizontal bands in one vertical column. Short yellow paper-tag labels aligned on the left; the entire large animal takes most of each band to the right. No top headline, panel borders, cards, 2-by-2 grid, arrows, A/B markers or separate circular diagrams. All four animals fully visible. Minimal gap, rich subject detail.

Row 1 “目视”: highly photorealistic exterior, individually resolved fur/skin detail, realistic eyes, dimensional studio side lighting, physical presence. No cartoon lines.
Row 2 “X光”: detailed monochrome radiographic-style projection illustration of the same animal. Bright coherent bone network within a faint soft-tissue silhouette, layered gray shadows, flat projection feel; polished intricate structure, no plastic skeleton, no precision anatomical/clinical claim.
Row 3 “CT”: the same full animal as an exquisite grayscale volumetric reconstruction illustration, with clearly visible successive transverse cross-sectional layers integrated into the torso volume. Slightly separate a few adjacent planes to reveal depth and internal structure while keeping the animal silhouette intact. It must visibly differ from row 2. No gore, severed chunks, floating shape cards, or scanner parameters.
Row 4 “磁共振”: the same full animal as a sophisticated grayscale soft-tissue-dominant volume/cutaway illustration, emphasizing natural layered tissue textures, muscle volumes and differentiated gray regions in the same torso area. Soft tissues carry the interest; bone cortex and long-bone outlines are subdued dark gray, not bright white as in an X-ray. Preserve vivid silver/gray tissue information with depth and restrained edge light. MRI can also show cross-sectional information. No pink/cyan bone glow, white rib array, white spine, or rainbow recolored X-ray. A subtle cool environment rim light may define the silhouette; the represented signal/tissues remain grayscale.

Lighting: deep charcoal-black, clean silver-white contrast, controlled glow on fine information edges, visibly dimensional, premium biological visualization finish. Keep texture and shadow detail; avoid white blown-out masses.
Exact visible text only: “目视”, “X光”, “CT”, “磁共振”; small restrained bottom caption “AI成像示意，非真实扫描”.
Medical framing: these are AI-created visual illustrations of imaging differences, not genuine animal scan data or guaranteed anatomy. Never show lesions, patient IDs, numeric parameters, hospital brand or original account watermark.
Avoid: cartoon poster, colored-pencil animal, flat vector mascot, cream background, explanatory infographic, geometric circular slices, miniature animal anchors, oversized title/disclaimer, repeated identical skeletons in the last three rows.

## 针对修复

只提出实际看见的失败点。指令写明要改的行/区域和其余保持项，继续输入实际最新图；冻结已正确的动物身份、完整轮廓、朝向、主体尺寸、黑底和短标签。若MRI误生成彩色骨架，明确删除它，以软组织占主视觉的灰阶剖面/体积替代。不要为了防止解剖虚构，把作品退回灰色几何教材。
