# Annotation Guidelines

## Objective
Annotate images with bounding boxes for four object categories: book, pen, pencil, and ruler.

## Object Definitions
- **Book:** Any book or notebook (open or closed)
- **Pen:** Any pen
- **Pencil:** Any pencil
- **Ruler:** Any ruler

## Annotation Rules

### Inclusion Criteria
- Objects with ≥25% visible and clearly identifiable
- Objects with ≥40% visible if blurry
- Label each distinct object separately even if overlapping

### Bounding Box Standards
- Draw tight bounding boxes around only the visible portion of each object
- Boxes should be as small as possible while fully containing the object
- Boxes may overlap if objects overlap
- Use rectangular boxes only (not rotated or irregular shapes)

### Region Attributes
**Occluded:** Mark "yes" if the object is partially hidden by another object (e.g., a book behind a pen). Mark "no" if fully visible.

**Truncated:** Mark "yes" if the object extends beyond the image boundary (e.g., a pen cut off at the edge of the photo). Mark "no" if fully within the frame.

### Exclusions
- Backgrounds and shadows
- Partial objects less than visibility threshold
- Decorative elements or logos
- Objects outside target categories
