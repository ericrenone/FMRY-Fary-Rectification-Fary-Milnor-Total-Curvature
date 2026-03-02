# FMRY — Fáry Rectification, Fáry-Milnor Total Curvature, and the Curvature-Topology Duality of the Gradient Correlation Manifold
## István Fáry's Two Theorems as the 2D and 3D Faces of a Single Curvature-Embedding Principle for the Learning Spectral Geometry
### A Unified Framework Extension — Bridges XL · XLI · XLII
#### Modules: FMRY · FSLE · FMTC · CKTD
#### Integrating with: KKSP (XXXVII–XXXIX) · MNGR (XXXIV–XXXVI) · CAGV (XXXI–XXXIII) · GXMD (XXVIII–XXX) · THRS (XXV–XXVII) · SKML (XIX–XXI) · TIDE (XVI–XVIII) · IMFL (XIII–XV) · BPSG (X–XII) · GCCT (III) · LKTL (I–II) · RG-ML · KQOM · FLML

---

```
===============================================================================
NOTATION KEY
[T]=Theorem  [V]=Verified  [C]=Conjecture  [H]=Hypothesis  [D]=Definition
(✓)=classical result  ([H])=working hypothesis  ([C])=open conjecture
([FS])=FSLE  ([FM])=FMTC  ([CK])=CKTD
===============================================================================
```

---

```
===============================================================================
FMRY — FÁRY RECTIFICATION AND FÁRY-MILNOR TOTAL CURVATURE FRAMEWORK
[D] Master module encompassing Bridges XL, XLI, and XLII.

FMRY unifies the two theorems of István Fáry — his 1948 straight-line graph
embedding theorem and his 1949 total curvature knot theorem — as complementary
faces of a single curvature-topology duality operating on the gradient
correlation manifold ℬ. Fáry's 1948 theorem (2-dimensional) states that every
planar graph has a straight-line embedding: curved edges carry no extra
topological information beyond straight (geodesic) ones. Fáry's 1949 theorem
(3-dimensional, proved simultaneously by Milnor in 1950) states that any closed
curve in Euclidean space with total absolute curvature at most 4π must be an
unknot. These two theorems — one collapsing edge geometry to its geodesic
minimum, one using curvature as a threshold for topological complexity —
constitute the curvature-embedding duality layer of the unified framework.

Three structures emerge:

  FSLE (Bridge XL)   — Fáry's straight-line embedding theorem (1948): every
                        simple planar G_ℬ admits a straight-line realization
                        (a Fáry embedding) in which all gradient correlations
                        are represented as straight segments; curved gradient
                        flows carry no extra planarity information beyond
                        geodesic paths; Tutte's spring theorem: every 3-
                        connected planar G_ℬ is the equilibrium of a gradient
                        spring system (spectral Hamiltonian); Schnyder's
                        3-tree decomposition: edges of maximal planar G_ℬ
                        partition into 3 spanning trees corresponding to the
                        Gallai-Edmonds D/A/C trifurcation; Harborth's integer-
                        distance conjecture; Sachs' 3D linkless embedding
                        conjecture

  FMTC (Bridge XLI)  — The Fáry-Milnor total curvature threshold (Fáry 1949;
                        Milnor 1950): ∮_K |κ(s)| ds ≤ 4π → K unknotted;
                        Fenchel's 2π lower bound for all closed curves; height
                        function proof (Milnor: one local maximum → trivial
                        knot); quadrisecant obstruction (Denne 2004: nontrivial
                        knot → alternating quadrisecant exists); Ekholm-White-
                        Wienholtz minimal surface proof (total curvature < 4π
                        → spanning disc self-intersection-free); polygonal
                        chain version (sum of turning angles); generalization
                        to Hadamard manifolds (Alexander-Bishop 1998);
                        six proof methods and their mutual relationships

  CKTD (Bridge XLII) — The curvature-topology duality: the Fáry-Milnor 4π
                        threshold as the spectral norm of ℒ_JL; the Fenchel
                        2π floor as the Berry-phase lower bound on gradient
                        trajectory winding; the Fáry straight-line embedding
                        as the geodesic rectification of G_ℬ (D_s-geodesics
                        replace curved edges without changing topology); the
                        unification of both Fáry theorems as the 2D/3D
                        expressions of the same curvature-dominated embedding
                        principle; the Tutte spring equilibrium as the
                        Hamiltonian gradient mechanics on ℬ; Schnyder 3-trees
                        as the spectral trifurcation (D/A/C); the Hadamard
                        manifold condition as λ₁(ℒ_JL) ≥ 0

FMRY CENTRAL IDENTIFICATION:

  The gradient trajectory γ_T: [0,T] → ℬ, treated as a closed curve
  (γ_T closed by the learning basin identification γ_T(0) ~ γ_T(T)), carries
  a total absolute curvature:

      Φ(γ_T) = ∮_{γ_T} |κ_{ℬ}(b)| ds_ℬ

  where |κ_ℬ(b)| = ‖∇²L(b_t)‖ / ‖∇L(b_t)‖ = the curvature of γ_T at
  parameter position b = b_t ∈ ℬ. By the Fáry-Milnor theorem ([H] applied
  on ℬ as Hadamard manifold when λ₁ ≥ 0):

      Φ(γ_T) ≤ 4π  →  γ_T is an unknot  →  Arf(Kγ_T) = 1 mod 2
                        → Vassiliev order-2: c₂(Kγ_T) = 0
                        → ℰ₂(γ_T) < ∞ with regularity

  By the Fáry straight-line theorem, when G_ℬ is planar (rank_ε(D_s) ≤ 4,
  CAGV Bridge XXXI), the gradient correlations can be represented as
  straight-line (geodesic) segments without any topological loss: the curved
  gradient flow through ℬ can be replaced by its geodesic rectification
  preserving all connectivity information. This "Fáry rectification" of G_ℬ
  is the 2D face of the same curvature-minimization principle that the
  Fáry-Milnor theorem encodes in 3D.

FMRY MASTER EQUATION (two faces, one principle):

  2D (FSLE): G_ℬ planar → Φ: G_ℬ → ℝ² straight-line embedding exists
             [curved edges = straight edges for planarity;
              Fáry-Tutte spring equilibrium: min ∑_{(i,j)∈E_ℬ} ‖bᵢ−bⱼ‖²]

  3D (FMTC): ∮_{γ_T} |κ_ℬ| ds ≤ 4π  →  γ_T unknotted
             [total curvature ≤ 4π is the topological unknottedness threshold;
              Fenchel lower bound: ∮ |κ| ds ≥ 2π for any closed γ_T]

  Duality (CKTD): Fáry rectification G_ℬ → G_ℬ^straight = "unknotting in 2D"
                  Fáry-Milnor Φ(γ_T) ≤ 4π = "unknotting in 3D"
                  Both: curvature minimization ↔ topological simplicity
                  Both proved by the same person (Fáry 1948, 1949)
                  Both connect to the same spectral quantity ℒ_JL:
                    Φ(G_ℬ rectification) = 0 (flat, λ₁ ≥ 0 Hadamard)
                    Φ(γ_T) = Tr(ℒ_JL) / (total arc length of γ_T)
===============================================================================
```

---

## Preamble: The Two Faces of Fáry's Curvature Principle

The preceding bridges have built the topological obstruction layer (KKSP XXXVII–XXXIX), the connectivity layer (MNGR XXXIV–XXXVI), the planar–knot invariant layer (CAGV XXXI–XXXIII), and the combinatorial extremal layer (GXMD XXVIII–XXX). A single mathematical figure, István Fáry (1922–1984), produced two theorems in consecutive years — 1948 and 1949 — that together constitute the curvature-topology duality layer of the unified framework. These two theorems address the same mathematical intuition from two different dimensions:

**In two dimensions (Fáry 1948):** The expressive power of curved edges in a planar graph drawing is exactly equal to the expressive power of straight-line segments. A planar graph drawn with curves can always be redrawn with straight lines, preserving the same combinatorial topology (vertices, edges, faces, incidences). Curvature of edges is topologically redundant for planarity.

**In three dimensions (Fáry 1949, Milnor 1950):** A closed curve in Euclidean 3-space with total absolute curvature at most 4π must be an unknot. Topological complexity (knotting) requires metric complexity (large total curvature). Below the 4π threshold, no amount of geometric wandering suffices to create a knot.

The unifying principle: **curvature, when bounded, forces topological simplicity.** In 2D, bounded curvature of edge paths is equivalent to zero curvature (straight lines) without changing topology. In 3D, bounded integral curvature ≤ 4π forces the learning trajectory to be topologically trivial (unknotted). These are the 2D and 3D faces of a single curvature-dominated embedding principle — and both were discovered within one year by the same mathematician, working at the intersection of graph theory and differential geometry.

István Fáry (1922–1984) was a Hungarian mathematician who studied at Budapest and Szeged (PhD 1947), then at the Sorbonne, before joining the University of Montreal (1955) and then Berkeley (1958), where he became a full professor in 1962. He worked at the interface of geometry and algebraic topology, and his two embedding theorems remain landmarks in both fields. His colleagues noted the rarity of theorems that simultaneously constrain a metric quantity (total curvature, which changes when a knot is deformed) and a topological invariant (knottedness, which is preserved under deformation) — such theorems combine, in a single inequality, an extrinsic geometric measurement with an intrinsic topological conclusion.

John Milnor independently proved the total curvature theorem in 1950 in his paper "On the total curvature of knots" (Annals of Mathematics). His proof used what became the Milnor-Fenner "height function" characterization: a closed curve in ℝ³ is an unknot if and only if some linear height function has exactly one local maximum on the curve. This height-function criterion is the prototype for the loss-function height criterion on the learning manifold ℬ.

Fáry's straight-line embedding theorem was proved independently by Klaus Wagner (1936), Fáry (1948), and Sherman K. Stein (1951). It is a foundational result in computational geometry and graph drawing. Its deep generalization is **Tutte's spring theorem** (1963): every 3-connected planar graph admits a straight-line embedding in which all faces are convex, obtainable as the equilibrium of a system of springs with endpoints at the vertices. This spring equilibrium is precisely the Hamiltonian mechanics identification: springs between gradient correlation vectors bᵢ, bⱼ ∈ V_ℬ with spring constant D_s(bᵢ,bⱼ), and equilibrium = gradient descent fixed point.

**Schnyder's theorem** (1990) complements Fáry: every maximal planar graph (triangulation) has its edge set partitioned into exactly three spanning trees (a "Schnyder wood"), and conversely. The three Schnyder trees are identified with the Gallai-Edmonds trifurcation D/A/C (GL3, GXMD Bridge XXVIII): the three spanning forests of G_ℬ corresponding to the memorization (D), grokking-frontier (A), and generalization (C) basins.

**Denne's quadrisecant theorem** (2004) gives a third, independent proof of the Fáry-Milnor theorem: every nontrivial knot in ℝ³ has an **alternating quadrisecant** — a straight line meeting the knot in at least four points a, b, c, d with the alternating coloring pattern (the knot alternates between two strands as it crosses the line). The quadrisecant is the four-point obstruction to unknottedness; any knotted gradient trajectory γ_T contains four distinguished parameter vectors b₁, b₂, b₃, b₄ ∈ ℬ lying on a single "gradient secant line," with alternating crossing structure.

**Ekholm-White-Wienholtz** (2002) gave a sixth proof via minimal surface theory: if the total curvature of a closed curve is below 4π, then any area-minimizing disc spanning the curve has no interior self-intersections, hence the curve is an unknot. The spanning disc is the Seifert surface of the learning trajectory; the condition "no self-intersections" = the spectral condition rank_ε(D_s) ≤ 2 (the minimal disc is a 2-dimensional surface with no degenerate crossings).

The **Hadamard manifold generalization** (Alexander-Bishop 1998): the Fáry-Milnor theorem holds in any complete simply connected Riemannian 3-manifold of nonpositive sectional curvature (Hadamard manifold). The learning manifold ℬ with λ₁(ℒ_JL) ≥ 0 (the generalization condition) has nonpositive sectional curvature along gradient trajectories (from the Bochner-Weitzenböck formula and Ric(ℬ) ≥ 0 ↔ λ₁ ≥ 0), and is therefore a Hadamard-type space in which the Fáry-Milnor theorem applies.

Three bridges formalize this:

- **Bridge XL (FSLE):** Fáry's straight-line embedding theorem; Tutte springs; Schnyder 3-trees; Harborth integer-distance; Sachs 3D linkless analogue
- **Bridge XLI (FMTC):** The Fáry-Milnor total curvature theorem; Fenchel lower bound; height function proof; quadrisecants; Ekholm-White-Wienholtz minimal surface; Hadamard generalization
- **Bridge XLII (CKTD):** The curvature-topology duality unifying both theorems; spectral total curvature; Fáry rectification of G_ℬ; Schnyder = Gallai trifurcation; Hadamard = λ₁ ≥ 0; spring equilibrium = gradient fixed point

Together they constitute **FMRY — Fáry Rectification, Fáry-Milnor Total Curvature, and the Curvature-Topology Duality of the Gradient Correlation Manifold**.

---

## I. New Assumptions

### Fáry Straight-Line Assumptions FL1–FL3

```
FL1: A Fáry embedding of G_ℬ is a planar drawing Φ: V_ℬ → ℝ² of G_ℬ in
     which every edge (bᵢ,bⱼ) ∈ E_ℬ is drawn as the straight line segment
     from Φ(bᵢ) to Φ(bⱼ), with no two edges crossing except at shared
     endpoints. By Fáry's theorem (1948, ✓): every simple planar graph
     has a Fáry embedding.
     The Fáry embedding is the MINIMAL curvature realization of G_ℬ: among
     all planar drawings (edges as curves), the straight-line drawing
     minimizes the total edge curvature to zero. For G_ℬ planar
     (rank_ε(D_s) ≤ 4, CAGV Bridge XXXI, PC-1):
         Fáry embedding exists ↔ G_ℬ planar ↔ rank_ε(D_s) ≤ 4
     In the Fáry embedding, each straight segment Φ(bᵢ)Φ(bⱼ) represents
     the geodesic in ℝ² connecting the flat projections of bᵢ and bⱼ,
     i.e., the length-minimizing path between the projected parameter vectors.

FL2: Tutte's spring embedding of G_ℬ (1963, ✓):
     For every 3-vertex-connected planar graph G_ℬ (κ(G_ℬ) ≥ 3, MNGR XXXIV),
     the Tutte embedding Ψ: V_ℬ → ℝ² is defined as the unique harmonic map
     minimizing the spring energy:
         E_{spring}(Ψ) = ∑_{(bᵢ,bⱼ)∈E_ℬ} w_{ij} ‖Ψ(bᵢ)−Ψ(bⱼ)‖²
     where weights w_{ij} > 0, with the outer face (triangle a,b,c)
     fixed. The Tutte embedding exists, is unique, and every interior
     face is a convex polygon.
     Spectral identification:
         w_{ij} ↔ D_s(bᵢ,bⱼ) [gradient correlation as spring constant]
         E_{spring} ↔ ∑_{(i,j)} D_s(bᵢ,bⱼ) ‖bᵢ−bⱼ‖²_ℝ² = the projected
                       D_s-weighted gradient correlation energy
         Equilibrium ∇_Ψ E_{spring} = 0 ↔ Ψ(b) = harmonic mean of neighbors
         ↔ ℒ_JL Ψ = 0 (Laplacian equilibrium of Ψ at spectral gap)
     The Tutte spring embedding is the HARMONIC PROJECTION of G_ℬ: the
     unique D_s-harmonic map from the gradient correlation graph to ℝ².

FL3: Schnyder's 3-tree decomposition of maximal planar G_ℬ (1990, ✓):
     A maximal planar graph G_ℬ (triangulation: all faces triangles) has
     an edge partition E_ℬ = T₁ ⊔ T₂ ⊔ T₃ into three spanning trees
     (a Schnyder wood). Every edge belongs to exactly one of the three
     trees, and the three trees are characterized by their orientation
     properties at each interior vertex b ∈ V_ℬ:
         Every b ∈ V_ℬ has exactly one parent in T₁, one in T₂, one in T₃
         The three parent edges at b lie in the three sectors of the face
         partition around b determined by the outer triangle.
     The Schnyder wood is the CANONICAL TRIFURCATION of G_ℬ:
         T₁ ↔ D-spanning tree: edges in the memorization basin (λ₁ < 0)
         T₂ ↔ A-barrier edges: edges crossing the Gallai barrier
         T₃ ↔ C-spanning tree: edges in the generalization basin (λ₁ > 0)
     Schnyder's theorem: G_ℬ planar ↔ G_ℬ has a Schnyder wood.
     This is a planarity characterization via three-tree decomposition —
     the 3-tree structure is exactly the Gallai-Edmonds trifurcation (GL3,
     GXMD Bridge XXVIII) in the planarity regime.
```

### Fáry-Milnor Curvature Assumptions FM1–FM3

```
FM1: The gradient trajectory γ_T: [0,T] → ℬ, treated as a smooth
     closed curve (closed via the ergodic identification γ_T(0) ~ γ_T(T)),
     has total absolute curvature:
         Φ(γ_T) = ∮_{γ_T} |κ_ℬ(b_t)| dt
     where κ_ℬ(b_t) is the geodesic curvature of γ_T at parameter
     position b_t ∈ ℬ. In the gradient descent model:
         κ_ℬ(b_t) = ‖∇²L(b_t) · ∇L(b_t)‖ / ‖∇L(b_t)‖² [Frenet curvature]
     = the rate of turning of the gradient direction as the trajectory
     moves through ℬ = the "bending" of the gradient flow path.

     Fáry-Milnor theorem (✓; applied to ℬ as Hadamard manifold, FM3):
         Φ(γ_T) ≤ 4π  →  γ_T is unknotted (trivial knot)
         γ_T knotted  →  Φ(γ_T) > 4π                    (contrapositive)
     Under HKVS (CAGV Bridge XXXIII):
         γ_T unknotted ↔ Arf(Kγ_T) = 1 mod 2 ↔ c₂(Kγ_T) = 0
         ↔ the learning trajectory is topologically trivial
     Therefore: Φ(γ_T) ≤ 4π → Arf(Kγ_T) = 1 → generalization (λ₁ > 0)
     Contrapositive: λ₁ < 0 (memorization) → γ_T knotted → Φ(γ_T) > 4π

FM2: Fenchel's theorem (1929, ✓): for any smooth closed curve γ in ℝⁿ:
         Φ(γ) = ∮_γ |κ(s)| ds ≥ 2π
     with equality iff γ is a planar convex curve (circle or convex plane
     curve). The Fenchel lower bound 2π is the MINIMAL winding of any
     closed gradient trajectory γ_T — corresponding to a single complete
     revolution in ℬ. The Fáry-Milnor threshold 4π = 2 × 2π is exactly
     DOUBLE the Fenchel minimum: the transition from unknotted to potentially
     knotted requires the gradient trajectory to accumulate at least twice
     the minimal closed winding.
     Spectral interpretation:
         2π ≤ Φ(γ_T) ≤ 4π: trajectory unknotted, Arf = 1
         Φ(γ_T) = 2π (Fenchel equality): convex planar γ_T = circular
                  gradient orbit = Berry phase holonomy = 2π (BPSG X)
         Φ(γ_T) = 4π: FM boundary = grokking transition at Φ = 4π
         Φ(γ_T) > 4π: trajectory potentially knotted → Arf ≠ 1 (memorization)
         Gap 2π < Φ(γ_T) < 4π: "non-convex but unknotted" = generalization
                                  basin with curved gradient trajectory

FM3: Hadamard manifold assumption (Alexander-Bishop 1998, ✓):
     The Fáry-Milnor theorem holds on any complete, simply connected
     Riemannian 3-manifold of nonpositive sectional curvature (Hadamard
     manifold). More precisely: if γ is a simple closed curve in such a
     manifold with total geodesic curvature ∮ |κ| ds ≤ 4π, then γ bounds
     an embedded disc (γ is contractible, i.e., unknotted).
     The learning manifold ℬ under the generalization condition λ₁(ℒ_JL) ≥ 0
     satisfies: by Bochner-Weitzenböck, Ric(ℬ) ≥ −λ₁(ℒ_JL) · g_ℬ
     → λ₁ ≥ 0 ↔ Ric(ℬ) ≥ 0 (nonneg. Ricci along gradient directions)
     → ℬ has nonpositive sectional curvature along γ_T (Karcher-Sturm)
     → ℬ is locally Hadamard-type → FM applies to γ_T ⊂ ℬ.
     Under λ₁ > 0 (generalization): ℬ is a Hadamard manifold and
     Φ(γ_T) > 4π → γ_T knotted is impossible at the Hadamard floor:
         λ₁ > 0  →  ℬ Hadamard-type  →  FM threshold 4π applies
         →  Φ(γ_T) ≤ 4π (natural upper bound for smooth gradient descent)
         →  γ_T unknotted  →  generalization confirmed (consistent)
```

---

## II. Main Theorems and Bridges

### Bridge XL — FSLE: Fáry's Straight-Line Embedding

```
[T, FL-1] FÁRY'S STRAIGHT-LINE EMBEDDING THEOREM (✓; identification [H])
Under FL1, for the gradient correlation graph G_ℬ:
    G_ℬ planar  ↔  G_ℬ has a Fáry embedding (straight-line planar drawing)
    [Wagner 1936; Fáry 1948; Stein 1951] (✓)

Spectral identification: The Fáry embedding Φ: V_ℬ → ℝ²:
    bᵢ ↦ Φ(bᵢ) = (projection of bᵢ onto 2D spectral subspace spanned
                   by eigenvectors v₁, v₂ of D_s)
    Edge (bᵢ,bⱼ) ↦ straight segment Φ(bᵢ)Φ(bⱼ) = geodesic projection
    No crossings ↔ spectral separation: ‖Φ(bᵢ)−Φ(bⱼ)‖ > 0 for all edges

The rectification principle ([H]):
    Any gradient flow path bᵢ →^{curved} bⱼ (curved gradient trajectory
    segment) is topologically equivalent, for the purposes of planarity of
    G_ℬ, to the straight geodesic bᵢ →^{straight} bⱼ. The curvature of
    the gradient path carries no topological information beyond its
    endpoints. In the Fáry embedding, all gradient correlation edges are
    "rectified" to their geodesic connections — the straightest possible
    path in the projected spectral plane.
    Curvature of gradient flows: Fáry embedding = zero edge curvature ≡
    same topological information as curved gradient flows = curvature
    redundancy theorem for gradient correlation topology.

Fáry–Kuratowski connection:
    By Kuratowski's theorem (KKSP Bridge XXXVII, KP-1):
    G_ℬ planar ↔ no K₅ subdivision ∧ no K₃,₃ subdivision
    By Fáry: G_ℬ planar ↔ G_ℬ has a straight-line embedding
    Combined: G_ℬ has a straight-line embedding ↔ no K₅/K₃,₃ subdivision
    ↔ rank_ε(D_s) ≤ 4 (4CT bound, CAGV XXXI)
    The Kuratowski obstruction (subdivisions) is the COMBINATORIAL certificate
    of non-planarity; the Fáry embedding is the GEOMETRIC certificate of
    planarity — they are complementary.
```

```
[T, FL-2] TUTTE'S SPRING THEOREM AND GRADIENT HAMILTONIAN ([H])
Under FL2, for every 3-connected planar G_ℬ (κ(G_ℬ) ≥ 3):
    The Tutte spring embedding Ψ exists, is unique, and has convex faces.
    [Tutte 1963] (✓)
    The spring energy E_{spring}(Ψ) = ∑_{(i,j)∈E_ℬ} D_s(bᵢ,bⱼ) ‖Ψ(bᵢ)−Ψ(bⱼ)‖²
    is minimized by Ψ: the Tutte embedding is the minimum of a quadratic
    form in the projected positions {Ψ(b) : b ∈ V_ℬ}.

Gradient Hamiltonian identification ([H]):
    E_{spring} ↔ H_{spring} = ∑_{(i,j)} D_s(bᵢ,bⱼ) d²_gradient(bᵢ,bⱼ)/2
    = the D_s-weighted Cayley-Menger potential energy (CMGD XXXVI)
    = the 2D projection of the gradient covariance Hamiltonian
    The equilibrium condition ∇_{Ψ(b)} E_{spring} = 0:
        Ψ(b) = [∑_{b'∈N(b)} D_s(b,b')Ψ(b')] / [∑_{b'∈N(b)} D_s(b,b')]
        = D_s-weighted harmonic mean of projected neighbors of b
        = ℒ_JL Ψ = 0 (ℒ_JL-harmonic function at spectral gap)
    Tutte equilibrium ↔ ℒ_JL-harmonic projection ↔ λ₁(ℒ_JL) = 0
    (the equilibrium is achieved precisely at the grokking transition λ₁ = 0)
    For λ₁ > 0 (generalization): the spring system is "super-harmonic"
    with positive restoring force = D_s-weighted spectral gap.
    For λ₁ < 0 (memorization): the spring system is "sub-harmonic"
    with negative restoring force = gradient unstability.
    Tutte spring equilibrium is the CANONICAL MECHANICAL MODEL of grokking:
    the moment the gradient spring system reaches its harmonic equilibrium
    is the moment λ₁ = 0 = grokking (τ_learn pole, IMFL Bridge XIII).
```

```
[T, FL-3] SCHNYDER 3-TREES AS GALLAI-EDMONDS TRIFURCATION ([H])
Under FL3, for a maximal planar G_ℬ (triangulated gradient correlation graph):
    E_ℬ = T₁ ⊔ T₂ ⊔ T₃ [Schnyder wood; 3-tree decomposition]  (✓)

Gallai-Edmonds identification (under GL3, GXMD Bridge XXVIII) ([H]):
    T₁ (Schnyder tree 1) ↔ D-spanning forest: gradient trajectories
                              within the memorization basin (λ₁ < 0)
    T₂ (Schnyder tree 2) ↔ A-barrier spanning forest: gradient trajectories
                              crossing the Gallai barrier (λ₁ = 0 locus)
    T₃ (Schnyder tree 3) ↔ C-spanning forest: gradient trajectories
                              within the generalization basin (λ₁ > 0)

The Schnyder planarity characterization: G_ℬ planar ↔ Schnyder wood exists
↔ E_ℬ splits into exactly three spanning trees ↔ Gallai-Edmonds trifurcation
holds for G_ℬ (D, A, C are well-defined disjoint covering sets of V_ℬ).
The maximal planarity condition (G_ℬ triangulated) corresponds to:
    All gradient correlation clusters are exactly triangular
    ↔ every triple (bᵢ,bⱼ,b_k) with D_s correlations forms a triangle face
    ↔ Apollonian triangulation of G_ℬ (CAGV Bridge XXXII, APSC)
    ↔ the Apollonian network condition (all faces triangles, treewidth 3)
The Schnyder wood on the Apollonian G_ℬ has T₁, T₂, T₃ = the three Apollonian
fractal trees covering the D, A, C basins respectively.
Schnyder's theorem is the MAXIMAL PLANARITY expression of the Gallai-Edmonds
trifurcation: the 3-tree decomposition is the combinatorial witness that the
three spectral basins partition the gradient correlation graph.
```

```
[T, FL-4] HARBORTH'S INTEGER-DISTANCE CONJECTURE AND SPECTRAL INTEGRALITY ([H]/[C])
Harborth's conjecture (1987; open):
    Every planar graph has a Fáry embedding (straight-line planar drawing)
    in which all edge lengths are integers.                          ([C])
Under FL1 and the D_s-gradient distance:
    d_gradient(bᵢ,bⱼ)² = D_s(bᵢᵢ)+D_s(bⱼⱼ)−2D_s(bᵢⱼ) (CMGD XXXVI CM1)
    The Harborth conjecture becomes: ∃ Fáry embedding Φ of G_ℬ such that
    all edge lengths ‖Φ(bᵢ)−Φ(bⱼ)‖ ∈ ℤ.
    Spectral integrality condition ([H]):
    D_s integer-valued ↔ gradient covariances Cov_batch[∇L]_{ij} ∈ ℤ
    ↔ gradient vectors ∇L(b_t) are ℤ^n-valued (integer gradient model)
    ↔ the learning system operates on a discrete lattice in ℬ
    Under the arithmetic identification of TIDE (Bridge XVI): the 3DIK
    arithmetic structure has integer-valued coordinates in the Jn system;
    Harborth integrality ↔ Jn integer coordinates ↔ N_L ∈ ℤ (Luttinger
    integer condition, FLML). Harborth's conjecture for G_ℬ ↔ the
    Luttinger-Ward Jn integer-coordinate conjecture.
```

```
[T, FL-5] SACHS' 3D LINKLESS EMBEDDING ANALOGUE ([H]/[C])
Sachs' conjecture (1983; open): Every graph with a linkless embedding in
    ℝ³ has a linkless embedding in which all edges are straight line
    segments (analogous to Fáry in 2D).                              ([C])
Under FL1 and the 3D learning manifold ℬ ↪ ℓ^∞ (KZOP Bridge XXXIX, KZ-1):
    A Fáry-type 3D embedding of G_ℬ ↪ ℝ³ with straight-line edges
    and no two edges linking (forming a non-trivial link) exists iff
    G_ℬ has a linkless embedding in ℝ³.
    A linkless embedding of G_ℬ in ℝ³ ↔ the gradient trajectory γ_T can
    be drawn through G_ℬ without any two gradient loops forming a non-trivial
    link → the learning manifold ℬ has no interleaving gradient cycles.
    Sachs conjecture for G_ℬ: every G_ℬ with a linkless embedding in ℝ³
    can be drawn with straight-line (geodesic) edges without linking.
    This is the 3D generalization of the Fáry rectification principle.
```

---

### Bridge XLI — FMTC: Fáry-Milnor Total Curvature Threshold

```
[T, FM-1] FÁRY-MILNOR THEOREM ON THE LEARNING MANIFOLD (✓; identification [H])
Under FM1 and FM3, for the gradient trajectory γ_T: [0,T] → ℬ:
    ∮_{γ_T} |κ_ℬ(b)| ds ≤ 4π  →  γ_T is unknotted  [Fáry 1949; Milnor 1950] (✓)
    γ_T nontrivially knotted  →  ∮_{γ_T} |κ_ℬ(b)| ds > 4π  (contrapositive) (✓)

Spectral chain of implications (under FM3 and HKVS, CAGV XXXIII) ([H]):
    λ₁(ℒ_JL) > 0 (generalization)
      ↔ ℬ is a Hadamard-type manifold along γ_T (FM3)
      → FM applies: Φ(γ_T) ≤ 4π is consistent with γ_T unknotted
      ↔ Arf(Kγ_T) = 1 (HKVS)
      ↔ c₂(Kγ_T) = 0 (Vassiliev order-2, HKVS)
      ↔ ℰ₂(γ_T) = Tr(ℒ_JL²)/2 < ∞ (integral Menger curvature, CMGD XXXVI)

    λ₁(ℒ_JL) < 0 (memorization):
      → γ_T may be knotted (Arf may be ≠ 1)
      → Φ(γ_T) > 4π (necessary condition for knotting)
      → gradient trajectory bends more than 4π total curvature
      → deeply memorizing systems have high-curvature gradient paths

The 4π threshold in units of ℒ_JL:
    Φ(γ_T) = ∮ |κ_ℬ| ds = ∫₀^T ‖∇²L(b_t) · ∇L(b_t)‖/‖∇L(b_t)‖² dt
    Under uniform gradient magnitude ‖∇L‖ ≈ σ (constant noise level):
    Φ(γ_T) ≈ ∫₀^T ‖∇²L(b_t)‖/σ dt = (1/σ) ∫₀^T ‖H_t‖_F dt
    where H_t = ∇²L(b_t) is the Hessian at time t.
    ∫₀^T ‖H_t‖_F dt = Tr(ℒ_JL) · T/T_learn [under ergodic Hessian averaging]
    → Φ(γ_T) ≈ Tr(ℒ_JL) / (σ · T_learn) = total spectral mass of ℒ_JL
    FM threshold: Φ(γ_T) ≤ 4π ↔ Tr(ℒ_JL) ≤ 4π · σ · T_learn
    = the total spectral mass of ℒ_JL is bounded by 4π times the noise-
    learning time product.
```

```
[T, FM-2] FENCHEL LOWER BOUND AND BERRY PHASE FLOOR ([H])
Under FM2, for any smooth closed gradient trajectory γ_T:
    Φ(γ_T) ≥ 2π  [Fenchel's theorem] (✓)
    with equality iff γ_T is a planar convex curve.

Berry phase identification ([H]):
    The holonomy of the gradient bundle along γ_T:
        Θ_{Berry}(γ_T) = ∮_{γ_T} A_ℬ · db
    where A_ℬ is the Berry connection on the spectral bundle over ℬ.
    For γ_T unknotted and convex (Fenchel equality):
        Θ_{Berry} = 2π [one full winding, trivial holonomy]
    For γ_T unknotted and non-convex (2π < Φ < 4π):
        2π < Θ_{Berry} < 4π [non-trivial winding, unknotted]
    For γ_T knotted (Φ > 4π):
        Θ_{Berry} > 4π [double winding, knotted holonomy]
    Fenchel-Fáry-Milnor hierarchy:
        2π = Fenchel minimum = minimal Berry phase of any closed gradient loop
        4π = FM threshold = knotting onset = double Berry phase
        n · 2π = nth-winding = linking number n knot invariant
    Under BPSG (Bridge XII, BPSL): the BPS saturation condition λ₁ = |Δ_t|
    corresponds to Φ(γ_T) = 2π (circular orbit, Fenchel equality):
        BPS saturation ↔ Φ = 2π (circular Berry orbit)
        λ₁ > |Δ_t| (deep generalization) ↔ 2π < Φ < 4π (non-convex unknot)
        λ₁ < |Δ_t| (deep memorization) ↔ Φ > 4π (potentially knotted)
```

```
[T, FM-3] HEIGHT FUNCTION PROOF AND LOSS LANDSCAPE CRITERION ([H])
Milnor's height function proof (1950, ✓): a simple closed curve K in ℝ³
is unknotted iff there exists a linear height function h: ℝ³ → ℝ such that
K ∩ h⁻¹(c) is at most one point for all but finitely many values c (i.e.,
h restricted to K has exactly one local maximum).

Learning manifold identification ([H]):
    Height function h: ℬ → ℝ ↔ loss function L: ℬ → ℝ
    K ↔ gradient trajectory γ_T: [0,T] → ℬ
    h restricted to K has exactly one local maximum ↔ L restricted to
    γ_T has exactly one local maximum (one "peak" of loss along trajectory)
    
    Milnor criterion: γ_T unknotted ↔ ∃ "good" L (or reparametrization of
    L) such that L|_{γ_T} has exactly one local maximum on γ_T.
    
    For the gradient descent trajectory: b_t decreases along ∇L, so L(b_t)
    is generically DECREASING along γ_T. The gradient flow is already a
    "monotone height function" on γ_T — L decreases from max at b₀ to min
    at b*. The gradient descent trajectory is therefore ALWAYS unknotted by
    the Milnor criterion: the loss L itself is the height function with
    exactly one local maximum at b₀ (the initialization).
    
    This gives the fundamental reason why gradient descent trajectories tend
    to be unknotted: the loss function L is a Lyapunov (height) function on
    γ_T with unique maximum at the start, so the Milnor criterion applies
    and γ_T is unknotted → Φ(γ_T) ≤ 4π → FM threshold satisfied.
    
    Failure mode (knotted memorization, λ₁ < 0): when the gradient trajectory
    enters a memorization basin with multiple loss spikes (local oscillations
    of L along γ_T), the height function has multiple local maxima → Milnor
    criterion fails → γ_T may be knotted → Φ(γ_T) > 4π → memorization.
```

```
[T, FM-4] QUADRISECANT OBSTRUCTION AND FOUR-POINT KNOTTING STRUCTURE ([H])
Denne's quadrisecant theorem (2004, ✓): every nontrivial knot K in ℝ³ has
an alternating quadrisecant — a line ℓ meeting K in (at least) four points
a, b, c, d such that the arcs of K between consecutive meeting points
alternate between the two strands of ℓ.

Gradient trajectory identification ([H]):
    γ_T knotted → ∃ gradient secant line ℓ ⊂ ℬ meeting γ_T in ≥ 4 points
    b₁, b₂, b₃, b₄ ∈ γ_T ∩ ℓ with alternating strand structure.
    The quadrisecant b₁,b₂,b₃,b₄ ∈ ℬ lying on a single geodesic ℓ ⊂ ℬ
    represents FOUR CORRELATED GRADIENT PARAMETER VECTORS collinear in ℬ
    with an alternating correlation pattern.
    
    Quadrisecant ↔ 4-point correlation obstruction:
    b₁, b₂, b₃, b₄ ∈ V_ℬ collinear in ℬ with alternating strands
    ↔ ∃ 4-point gradient correlation pattern with D_s(bᵢ,bⱼ) structured as
    an alternating 4-cycle (b₁−b₃ and b₂−b₄ anti-correlated)
    ↔ a 4-point non-planar correlation pattern in G_ℬ (K₄ subdivision along ℓ)
    
    Quadrisecant → K₅ or K₃,₃ subdivision (Kuratowski, KKSP Bridge XXXVII):
    The alternating 4-secant structure generates a K₃,₃-type bipartite pattern
    {b₁,b₃} × {b₂,b₄} with the secant line ℓ as the bipartite "witness"
    → K₃,₃ subdivision → G_ℬ non-planar at the 4-point scale
    → rank_ε(D_s) ≥ 5 at the secant scale
    → the quadrisecant is the 4-point non-planarity certificate.
    
    Connection to Menger vertex-connectivity (MNGR Bridge XXXIV, MV-1):
    The 4 quadrisecant points require at minimum 4-vertex connectivity to
    be mutually accessible along the secant → κ(G_ℬ) ≥ 4 at the secant
    scale (Wagner's K₅-minor threshold, KKSP Bridge XXXVIII, KS-2).
```

```
[T, FM-5] EKHOLM-WHITE-WIENHOLTZ MINIMAL SURFACE AND SEIFERT BASIN ([H])
Ekholm-White-Wienholtz theorem (2002, ✓): if a smooth closed curve K in ℝ³
has total curvature less than 4π, then any area-minimizing disc spanning K
has no interior self-intersections (is an embedded disc).

Learning manifold identification ([H]):
    K ↔ gradient trajectory γ_T (closed curve in ℬ)
    Area-minimizing disc ↔ Seifert surface S(γ_T): an embedded surface
    in ℬ with boundary ∂S = γ_T, minimizing the spectral area functional:
        Area_{D_s}(S) = ∫_S √(det G_{ij}) dA, G_{ij} = D_s-metric on S
    "No interior self-intersections" of S ↔ S is an embedded (not merely
    immersed) surface in ℬ → Seifert surface is non-singular
    
    EWW criterion ([H]):
    Φ(γ_T) < 4π → Seifert surface S(γ_T) has no self-intersections
                 → γ_T is unknotted (contractible) → Arf(Kγ_T) = 1
                 → ℰ₂(γ_T) = Tr(ℒ_JL²)/2 < ∞ (CMGD XXXVI)
    Φ(γ_T) ≥ 4π → S(γ_T) may have self-intersections → γ_T may be knotted
    
    The self-intersections of S(γ_T) correspond to degenerate points of the
    Seifert spanning surface in ℬ — points where two branches of the
    generalization basin boundary cross. At such crossing points:
        det(G_{ij}) = 0  ↔  rank(D_s|_S) < 2  ↔  spectral rank drop
        ↔ the minimal surface self-intersection = a zero of the D_s metric
        ↔ a grokking-frontier crossing (λ₁ = 0 locus, Gallai barrier A)
    EWW: Φ(γ_T) < 4π → no self-intersections → Gallai barrier A does not
    cross-cut the Seifert surface → no λ₁ = 0 crossing interior to S(γ_T)
    → the generalization basin boundary is smooth and unknotted.
```

---

### Bridge XLII — CKTD: Curvature-Topology Duality

```
[T, CK-1] THE TWO FÁRY THEOREMS AS ONE CURVATURE-EMBEDDING PRINCIPLE ([H])
Both Fáry theorems are instances of the same curvature-dominated embedding
principle operating in different dimensions:

    Dimension 2 (Fáry 1948): G_ℬ planar  ↔  straight-line Fáry embedding
                Curvature of edges → ZERO without changing topology
                Principle: TOPOLOGICAL TYPE does not require EDGE CURVATURE

    Dimension 3 (Fáry 1949): Φ(γ_T) ≤ 4π → γ_T unknotted
                Curvature below 4π → TRIVIAL TOPOLOGICAL TYPE
                Principle: BOUNDED CURVATURE forces TOPOLOGICAL SIMPLICITY

    Unified principle ([H]):
    For the gradient correlation structure (G_ℬ, γ_T, ℬ):
    "Curvature, when minimized or bounded, forces the embedding to be
     topologically simplest — straight (planar), or unknotted (trivial)."

    Spectral unification: Both thresholds are controlled by λ₁(ℒ_JL):
        2D: G_ℬ planar (rank_ε(D_s) ≤ 4) → Fáry embedding exists
            λ₁(ℒ_JL) > 0 (generalization) + 4CT (CAGV XXXI) → planarity
        3D: Φ(γ_T) ≤ 4π → γ_T unknotted
            λ₁(ℒ_JL) > 0 (generalization, Hadamard condition FM3) → FM holds
    In both dimensions: λ₁ > 0 ↔ curvature-bounded ↔ topologically simple.

    The Fáry DUALITY:
        2D duality: [curved edge] ↔ [straight edge]  (isotopic, same topology)
        3D duality: [bounded total curvature] ↔ [unknotted]  (FM threshold)
        Framework: [gradient path curvature] ↔ [λ₁(ℒ_JL) sign]
                   [Fáry planar rectification] ↔ [Fáry-Milnor unknotted γ_T]
```

```
[T, CK-2] SCHNYDER TREES = GALLAI-EDMONDS TRIFURCATION (MAXIMAL PLANARITY) ([H])
For a maximal planar G_ℬ (Apollonian triangulation, CAGV XXXII):
    Schnyder 3-tree partition E_ℬ = T₁ ⊔ T₂ ⊔ T₃  (FL3 ✓)
    Gallai-Edmonds trifurcation V_ℬ = D ⊔ A ⊔ C    (GL3, GXMD XXVIII)
    Identification ([H]):
    T₁ = spanning tree of D-edges (memorization basin, λ₁ < 0)
    T₂ = spanning tree of A-barrier edges (grokking frontier, λ₁ = 0)
    T₃ = spanning tree of C-edges (generalization basin, λ₁ > 0)
    
    Schnyder dimension formula: every vertex b ∈ V_ℬ has a unique
    Schnyder coordinate triple (a₁(b), a₂(b), a₃(b)) ∈ ℕ³ with
    a₁(b) + a₂(b) + a₃(b) = |V_ℬ| − 3.
    This Schnyder coordinate encodes the relative "sizes" of the three
    spectral basins as seen from vertex b.
    Under the GL1 + GL3 identification:
        a₁(b) = # of D-type gradient modes accessible from b (memorization depth)
        a₂(b) = # of A-type modes (grokking frontier width at b)
        a₃(b) = # of C-type modes (generalization depth from b)
    The Schnyder embedding Φ_S: V_ℬ → ℝ² via barycentric coordinates
    (a₁,a₂,a₃)/(|V_ℬ|−3) is the canonical Fáry embedding for maximal
    planar G_ℬ: a straight-line drawing with integer Schnyder coordinates.
    Harborth integrality (FL-4): the Schnyder embedding Φ_S has integer
    vertex coordinates → satisfies the Harborth condition for all edges
    of G_ℬ if all D_s eigenvalues are integer-valued (spectral integrality).
```

```
[T, CK-3] HADAMARD CONDITION = GENERALIZATION CONDITION ([H])
Under FM3 and Bochner-Weitzenböck for ℒ_JL:
    Ric(ℬ)(X,X) = ‖∇X‖²_{D_s} − 〈X, ℒ_JL X〉_{L²(ℬ,μ)}   [Weitzenböck]
    λ₁(ℒ_JL) ≥ 0  →  Ric(ℬ) ≥ −λ₁ · g_ℬ ≥ 0  [nonneg. Ricci along γ_T]
    
    Sectional curvature of ℬ along γ_T:
    sec_ℬ(γ_T) = −Ric(ℬ)(ṫ, ṫ) / ‖ṫ‖² ≤ 0  [nonpositive → Hadamard-type]
    
    Hadamard manifold conditions for ℬ:
    (i) Complete: ℬ complete under D_s metric ← A1 (A₁ coercive V→∞)
    (ii) Simply connected: ℬ simply connected ← A5 (V→∞ forces contractibility)
    (iii) Nonpositive sectional curvature: sec(ℬ) ≤ 0 ← λ₁(ℒ_JL) ≥ 0
    
    → λ₁ ≥ 0  ↔  ℬ is a Hadamard manifold along γ_T
    → FM theorem applies to γ_T ⊂ ℬ
    → Φ(γ_T) ≤ 4π certifies γ_T unknotted in ℬ  (✓ by FM3)
    
    Deep consequence:
    λ₁ > 0 (strict generalization) → strict Hadamard → FM holds
    → any gradient descent trajectory in the generalization basin
    satisfies the Fáry-Milnor unknottedness criterion automatically,
    provided the loss landscape is sufficiently smooth.
    
    The generalization condition λ₁ > 0 is the spectral realization of the
    Hadamard (complete, simply connected, nonpositive curvature) condition:
    generalization = learning in a Hadamard manifold.
```

```
[T, CK-4] TOTAL CURVATURE AS SPECTRAL TRACE ([H])
Under FM1 and the ergodic identification of Φ(γ_T) with ℒ_JL:
    Φ(γ_T) = ∮_{γ_T} |κ_ℬ| ds
            ≈ ∫₀^{T_learn} |κ_ℬ(b_t)| dt / T_learn × T_learn
            = ∫₀^{T_learn} ‖H(b_t)‖_F / ‖∇L(b_t)‖ dt / T_learn × T_learn
    Under ergodic averaging over the steady state ρ_∞ ∝ exp(−𝒮̄/D_eff):
    Φ(γ_T)/T_learn ≈ 〈|κ_ℬ|〉_ρ∞ = ∫_ℬ |κ_ℬ(b)| ρ_∞(b) d^nb
                    = Tr(ℒ_JL |ℒ_JL|^{-1/2}) / Z_learn  [spectral trace formula]
    
    The Fáry-Milnor bound in spectral form:
    Φ(γ_T) ≤ 4π  ↔  Tr(ℒ_JL) · T_learn / (σ · Z_learn) ≤ 4π
    where σ = typical gradient noise, Z_learn = τ_learn (IMFL XIII, partition function).
    
    Spectral hierarchy:
    Fenchel lower bound: Tr(ℒ_JL) ≥ 2π · σ · Z_learn / T_learn (all trajectories)
    FM threshold:        Tr(ℒ_JL) ≤ 4π · σ · Z_learn / T_learn (unknotted trajectories)
    FM gap:              2π ≤ Tr(ℒ_JL) / (σ · Z_learn / T_learn) ≤ 4π  (generalization)
    
    The FM gap [2π, 4π] is the SPECTRAL WINDOW of unknotted gradient descent:
    the learning system must have total spectral mass between the Fenchel
    minimum (2π, minimal winding) and the FM threshold (4π, knotting onset).
    Generalization = operating in this spectral window.
    Grokking transition: Φ(γ_T) → 4π from below (Milnor-Fenchel approach to
    the FM threshold) = the total spectral mass approaches the knotting threshold
    = τ_learn pole (IMFL Bridge XIII, PVIL) = λ₁ → 0.
```

```
[T, CK-5] SPRING EQUILIBRIUM AND GROKKING AS TUTTE HARMONIC POINT ([H])
Under FL2 and CK-3, integrating the Tutte spring theorem with the spectral
Hamiltonian:
    E_{spring}(Ψ) = ∑_{(i,j)} D_s(bᵢ,bⱼ) ‖Ψ(bᵢ)−Ψ(bⱼ)‖²  [Tutte spring energy]
    H_{JL} = 〈φ, ℒ_JL φ〉_{L²(ℬ,μ)}                         [ℒ_JL Rayleigh form]
    
    Both are quadratic forms in the configuration {Ψ(b)} / {φ(b)}.
    The Tutte harmonic condition ℒ_JL Ψ = 0 is the zero-eigenvalue condition
    of ℒ_JL: Ψ is a λ₁ = 0 mode → the spring equilibrium position is
    exactly the grokking eigenmode of ℒ_JL.
    
    Grokking = Tutte equilibrium ([H]):
    The gradient spring system reaches its Tutte harmonic equilibrium
    at precisely t = t* (grokking transition, PVIL Bridge XIII):
        E_{spring}(Ψ(t*)) = 0 (harmonic ↔ zero energy ↔ λ₁ = 0)
        For t < t*: E_{spring} > 0 (pre-grokking spring tension)
        For t > t*: E_{spring} = 0 achieved and Ψ stabilizes (post-grokking)
    The Tutte embedding at t = t* gives the canonical Fáry straight-line
    drawing of G_ℬ at the grokking transition — the "grokking Fáry embedding"
    in which gradient correlations are drawn at their harmonic equilibrium
    positions in the spectral plane.
    After grokking (t > t*): E_{spring} resumes a positive value > 0 as
    the system moves into the generalization basin C with λ₁ > 0 and the
    spring configuration adjusts to the new spectral metric.
```

---

## III. Compact Reference Block

```
── FSLE ──────────────────────────────────────────────────────────────────────
Fáry (1948): G_ℬ planar ↔ straight-line (Fáry) embedding exists  (✓)
Also: Wagner (1936), Stein (1951) independent proofs
Rectification: curved gradient flow ↔ geodesic (straight) gradient path  ([H])
Planarity without curvature: edge curvature redundant for topology  ([H])
Tutte spring theorem: 3-connected planar G_ℬ = harmonic spring equilibrium  (✓)
E_{spring} = ∑ D_s(bᵢ,bⱼ)‖Ψ(bᵢ)−Ψ(bⱼ)‖²; equilibrium ↔ ℒ_JL Ψ=0  ([H])
Grokking = Tutte equilibrium: λ₁=0 ↔ spring energy=0 ↔ Fáry harmonic map  ([H])
Schnyder 3-trees: E_ℬ=T₁⊔T₂⊔T₃ for maximal planar G_ℬ  (✓)
T₁↔D-basin; T₂↔A-barrier; T₃↔C-basin  [Gallai-Edmonds trifurcation]  ([H])
Schnyder coord (a₁,a₂,a₃)/(|V|−3) = Fáry embedding via D/A/C basin depths  ([H])
Harborth conjecture: integer edge lengths for planar Fáry embedding  ([C])
Harborth ↔ Jn integer coordinates (TIDE XVII) ↔ N_L ∈ ℤ (FLML)  ([H])
Sachs 3D analogue: linkless embedding ↔ straight-line linkless embedding  ([C])
Fáry-Kuratowski: Fáry (geometric planarity cert.) ↔ Kuratowski (combinatorial cert.)

── FMTC ──────────────────────────────────────────────────────────────────────
Fáry (1949), Milnor (1950): ∮_K |κ|ds ≤ 4π → K unknotted  (✓)
Contrapositive: K knotted → total curvature > 4π  (✓)
Fenchel (1929): ∮|κ|ds ≥ 2π for any closed curve; equality = convex plane curve  (✓)
4π = 2×2π: FM threshold = double Fenchel minimum  (✓)
Spectral: 2π ≤ Φ(γ_T) ≤ 4π = unknotted = generalization window  ([H])
Φ(γ_T) = 2π (Fenchel equality): BPS saturation λ₁=|Δ_t| (BPSG XII)  ([H])
Φ(γ_T) = 4π (FM threshold): grokking transition λ₁→0, τ_learn pole  ([H])
Height function proof (Milnor): K unknotted ↔ ∃ height function h with unique max  (✓)
L(b_t) = height function on γ_T; unique max at b₀ → γ_T unknotted  ([H])
Multiple loss spikes on γ_T → multiple maxima → Milnor criterion fails → knotted  ([H])
Quadrisecants (Denne 2004): knotted K → alternating quadrisecant line exists  (✓)
Quadrisecant ↔ 4-point alternating gradient correlation obstruction  ([H])
4-secant → K₃,₃-type subdivision → G_ℬ non-planar (KKSP XXXVII)  ([H])
EWW (2002): Φ < 4π → area-minimizing disc (Seifert surface) self-intersection-free  (✓)
Seifert surface S(γ_T) = generalization basin boundary; self-int = Gallai crossing  ([H])
Hadamard generalization (Alexander-Bishop 1998): FM holds in sec≤0 manifolds  (✓)
ℬ Hadamard ↔ λ₁(ℒ_JL) ≥ 0 (generalization) ↔ Bochner-Weitzenböck Ric≥0  ([H])
Φ(γ_T) ≈ Tr(ℒ_JL)/(σ·Z_learn/T_learn): total curvature = spectral trace  ([H])
Six proofs of FM: Milnor-Fenner, Pannwitz 4-secant, Crofton-average, Ekholm-White-
Wienholtz minimal surface, Denne quadrisecant, Alexandrov-Bishop Hadamard  (✓ all)

── CKTD ──────────────────────────────────────────────────────────────────────
Unified Fáry principle: curvature minimization ↔ topological simplicity  ([H])
2D: curved edge ↔ straight edge (Fáry 1948); 3D: Φ≤4π ↔ unknotted (Fáry 1949)  (✓)
Both: λ₁>0 ↔ curvature-bounded ↔ topologically simple (planar and unknotted)  ([H])
Hadamard = λ₁≥0 (spectral realization of nonpositive sectional curvature)  ([H])
Generalization = learning in a Hadamard manifold (complete, simply connected, sec≤0)  ([H])
Fenchel-FM spectral window: 2π ≤ Tr(ℒ_JL)/(σ·Z/T) ≤ 4π = generalization band  ([H])
Below 2π: impossible (Fenchel theorem); above 4π: knotted memorization  ([H])
Grokking = FM threshold approach: Φ(γ_T)→4π from below as λ₁→0  ([H])
Tutte equilibrium = grokking: E_{spring}→0 ↔ λ₁→0 ↔ Fáry harmonic map  ([H])
Schnyder = Gallai: T₁⊔T₂⊔T₃ = D⊔A⊔C for maximal planar (Apollonian) G_ℬ  ([H])
CK-topology chain: λ₁>0 → Hadamard → FM → Φ≤4π → unknotted → Arf=1 → gen.  ([H])
CK-geometry chain: λ₁>0 → planar G_ℬ → Fáry embedding → straight-line G_ℬ  ([H])
Integer-dist Harborth ↔ arithmetic integrality (TIDE XVI-XVIII) ↔ SKML XX  ([C])
Sachs 3D linkless ↔ γ_T non-linking in ℬ^{3D} ↔ Arf(Kγ_T)=1 (HKVS XXXIII)  ([C])
```

---

## IV. Extended Master Equivalence — Three New Languages

Under the full assumption set including FL1–FL3, FM1–FM3, and CKTD:

```
(XL)   G_ℬ planar → Fáry straight-line embedding exists; E_ℬ = T₁⊔T₂⊔T₃  [FSLE]
(XLI)  Φ(γ_T) ≤ 4π → γ_T unknotted; Fenchel: Φ ≥ 2π always              [FMTC]
(XLII) λ₁>0 ↔ Hadamard ↔ FM applies ↔ curvature-bounded ↔ topol. simple  [CKTD]

Master equivalences extending the 39-language chain:

  (XL) ↔ (XXXI): Fáry embedding ↔ G_ℬ planar ↔ 4CT χ≤4 (CAGV XXXI)
  (XL) ↔ (XXXVII): Fáry (geometric) ↔ Kuratowski (combinatorial) planarity
  (XL) ↔ (XXVIII): Schnyder T₁⊔T₂⊔T₃ ↔ Gallai-Edmonds D⊔A⊔C (GXMD XXVIII)
  (XL) ↔ (XXXIV): Tutte equilibrium κ≥3 ↔ Menger 3-vertex connectivity (MNGR XXXIV)
  (XLI) ↔ (XXXIII): Φ(γ_T)≤4π → unknotted ↔ Arf=1 ↔ Vassiliev-2=0 (HKVS CAGV)
  (XLI) ↔ (XXXVI): Φ(γ_T) = Tr(ℒ_JL²)^{1/2}/(...) ↔ integral Menger ℰ₂ (CMGD)
  (XLI) ↔ (XII): Fenchel Φ=2π = BPS saturation λ₁=|Δ_t| (BPSL BPSG)
  (XLI) ↔ (XIII): Φ→4π (FM threshold) ↔ τ_learn pole (PVIL IMFL)
  (XLII) ↔ (I): λ₁>0 ↔ Hadamard condition ↔ generalization (ℒ_JL spectrum)
  (XLII) ↔ (III): Hadamard manifold ↔ Cooper condensate (λ₁>0, GCCT III)
  (XLII) ↔ (XXXIX): Kuratowski-Ulam comeager ↔ FM genericity in ℬ_θ×ℬ_D (KZOP)

New three-way FM-Kuratowski-Menger:
  G_ℬ planar ↔ Fáry embedding (XL, FSLE)
            ↔ no K₅/K₃,₃ subdivision (XXXVII, KRPN)
            ↔ rank_ε(D_s) ≤ 4 (XXXI, 4CT)
  γ_T unknotted ↔ Φ(γ_T) ≤ 4π (XLI, FMTC)
              ↔ Arf(Kγ_T) = 1 (XXXIII, HKVS)
              ↔ ℰ₂(γ_T) = Tr(ℒ_JL²)/2 < ∞ (XXXVI, CMGD)
  λ₁>0 ↔ Hadamard ↔ FM applicable (XLII, CKTD)
       ↔ Fáry embedding of G_ℬ exists (XL, planarity regime)
       ↔ κ(G_ℬ) ≥ 1 (XXXIV, Menger connectivity)
```

---

## V. Extended Master Equivalence — Forty-Two Languages

```
λ₁(ℒ_JL) > 0
  ⟺ C_α>1          ⟺ KE metric        ⟺ Poincaré ineq.   ⟺ Bellman finite
  ⟺ Möbius conv.   ⟺ K-polystable     ⟺ MMP terminates   ⟺ Ca_eff<Ca_c
  ⟺ N_L conserved  ⟺ Δ_t>0            ⟺ λ₁≥|Δ_t|         ⟺ τ_learn isomonodromic
  ⟺ SU(2,1;ℤ[i])  ⟺ WDVV holds       ⟺ ψ₃≠0             ⟺ Z-coord=N_L
  ⟺ volcano base   ⟺ Z_ε=AP∪finite   ⟺ ∃compress≺ℳ      ⟺ −∇L=Skolem fn
  ⟺ Quot^P repble  ⟺ GIT-stable       ⟺ moment map μ=0   ⟺ ARS terminates
  ⟺ word prob CR   ⟺ L-sys ρ<1        ⟺ ν(G_ℬ)=n_s
  ⟺ h(G_ℬ)=|Δ_t| at saturation  [Cheeger, GXMD]
  ⟺ K_k minor = k-compression    [Hadwiger, GXMD]
  ⟺ G_ℬ planar → χ≤4             [4CT, CAGV]
  ⟺ Apollonian 4-compress unique  [APSC, CAGV]
  ⟺ Arf(Kγ) = 1                  [Vassiliev-2, HKVS CAGV]
  ⟺ κ(G_ℬ) ≥ 1                   [Menger, MNGR XXXIV]
  ⟺ G_ℬ ↪ M non-trivially        [Menger sponge, MGSF XXXV]
  ⟺ rank(CM_ℬ) = rank_ε(D_s)     [Cayley-Menger, CMGD XXXVI]
  ⟺ no K₅/K₃,₃ subdiv. (planar)  [Kuratowski, KRPN XXXVII]
  ⟺ κ≥5+nonplanar → K₅ subdiv.   [Kelmans-Seymour, KSMC XXXVIII]
  ⟺ ∃b*, ℬ↪ℓ^∞, A_grok comeager  [Kuratowski toolkit, KZOP XXXIX]
  ⟺ G_ℬ planar → Fáry embedding  [FSLE XL]
  ⟺ Φ(γ_T) ≤ 4π → γ_T unknotted [FMTC XLI]
  ⟺ ℬ Hadamard → FM applicable   [CKTD XLII]

λ₁>0  →  CONDENSATE = GENERALIZATION
  [Fáry embedding of G_ℬ; γ_T unknotted (Φ≤4π); ℬ Hadamard;
   spring equilibrium post-grokking; Schnyder 3-tree = D/A/C;
   Seifert surface non-singular; Milnor criterion satisfied (L unique max)]

λ₁=0  →  GROKKING
  [FM threshold approach: Φ(γ_T)→4π; Tutte spring harmonic equilibrium;
   τ_learn pole; EWW disc self-intersection at grokking frontier;
   Gallai barrier A = Schnyder tree T₂ sole connector]

λ₁<0  →  MEMORIZATION
  [γ_T knotted (Φ>4π); alternating quadrisecant exists (Denne);
   Seifert surface self-intersecting; height function has multiple maxima;
   spring energy subharmonic; Fáry embedding fails (G_ℬ non-planar)]
```

---

## VI. Bridge Map — Bridges XL–XLII

```
XL    FSLE    Fáry straight-line (1948): planar G_ℬ ↔ Fáry embedding; Tutte springs;
              Schnyder 3-trees = D/A/C trifurcation; Harborth integer dist.; Sachs 3D
XLI   FMTC    Fáry-Milnor (1949/1950): ∮|κ|≤4π → unknotted; Fenchel 2π floor;
              height function/loss criterion; quadrisecant (Denne); EWW disc;
              Hadamard generalization; six proof methods
XLII  CKTD    Curvature-topology duality: unified Fáry principle; Hadamard=λ₁≥0;
              Φ = Tr(ℒ_JL)/(spectral norm); Tutte equilibrium = grokking;
              [2π,4π] spectral window = generalization band
```

---

## VII. New Identification Table

```
Fáry embedding Φ: V_ℬ→ℝ² [FSLE]     ↔ straight-line projection of G_ℬ     = geodesic rectification
Fáry rectification [FSLE]             ↔ curved edge → geodesic edge          = curvature redundancy
Tutte spring E_{spring} [FL2]         ↔ D_s-weighted correlation energy       = gradient Hamiltonian
Tutte equilibrium ∇E=0 [FL2]          ↔ ℒ_JL Ψ=0 (λ₁=0 harmonic mode)       = grokking Fáry map
Schnyder T₁ [FL3]                     ↔ D-basin spanning tree                 = memorization forest
Schnyder T₂ [FL3]                     ↔ A-barrier spanning tree               = grokking frontier edges
Schnyder T₃ [FL3]                     ↔ C-basin spanning tree                 = generalization forest
Schnyder coord (a₁,a₂,a₃) [CK-2]     ↔ D/A/C basin depth triple at b         = spectral trifurcation
Harborth integer dist. [FL-4]          ↔ D_s integer eigenvalues               = spectral integrality
Sachs 3D linkless [FL-5]              ↔ γ_T non-linking in ℬ^3D               = Arf=1 (HKVS XXXIII)
Φ(γ_T) [FM1]                          ↔ total Hessian norm along γ_T           = spectral curvature integral
Φ(γ_T) ≤ 4π [FM1]                    ↔ γ_T unknotted ↔ Arf=1                 = generalization threshold
Φ(γ_T) = 2π [FM2, Fenchel equality]  ↔ convex γ_T ↔ BPS saturation λ₁=|Δ_t| = Berry phase = 2π
Φ(γ_T) > 4π [FM1 contrapositive]     ↔ γ_T knotted ↔ Arf≠1                  = memorization
[2π, 4π] spectral window [CK-4]       ↔ generalization band                   = Fenchel-FM gap
Φ → 4π from below [CK-4]             ↔ grokking transition λ₁→0              = τ_learn pole (PVIL XIII)
Height function L unique max [FM-3]   ↔ γ_T unknotted (Milnor)               = smooth loss descent
Multiple loss spikes on γ_T [FM-3]    ↔ multiple maxima → knotted risk        = memorization oscillations
Quadrisecant b₁b₂b₃b₄ [FM-4]         ↔ 4-point alternating correlation       = K₃,₃ subdivision seed
Quadrisecant → K₃,₃ [FM-4]          ↔ non-planar 4-secant structure          = Kuratowski obstruction
EWW disc non-singular [FM-5]          ↔ Seifert surface S(γ_T) embedded       = non-crossing gen. boundary
EWW self-intersection [FM-5]          ↔ λ₁=0 crossing of Seifert surface      = Gallai barrier A crossing
Hadamard condition [FM3]              ↔ sec(ℬ)≤0 ↔ λ₁(ℒ_JL)≥0              = generalization = Hadamard
Fáry 2D principle [CK-1]             ↔ edge curvature → zero (no loss)        = 2D topological simplicity
Fáry 3D principle [CK-1]             ↔ total curvature ≤ 4π → unknotted       = 3D topological simplicity
Unified Fáry [CK-1]                   ↔ bounded curvature → topol. simple      = λ₁>0 curvature duality
Tr(ℒ_JL) [CK-4]                      ↔ Φ(γ_T) × σ × Z_learn/T_learn          = total spectral mass
Tr(ℒ_JL) ≤ 4πσZ/T [CK-4]           ↔ Φ(γ_T) ≤ 4π → unknotted               = FM spectral bound
```

---

## VIII. Open Conjectures

**[C, FMRY-C1] Fáry Rectification Conjecture:**
The Fáry embedding of G_ℬ (when G_ℬ is planar) is the unique D_s-geodesic
realization of the gradient correlation structure: among all planar drawings
of G_ℬ, the Fáry embedding minimizes the total edge-curvature functional
∑_{(i,j)∈E_ℬ} ∫_{edge} |κ_{ij}(s)| ds = 0 (exactly zero, as straight lines
have zero curvature). The Fáry drawing is the "most rectified" representation
of G_ℬ, consistent with the principle that learning in the generalization
regime (λ₁ > 0) corresponds to straight-line (geodesic) gradient flows.

**[C, FMRY-C2] Fáry-Milnor Grokking Threshold:**
At the grokking transition t = t* (λ₁ = 0, τ_learn pole), the total curvature
of the gradient trajectory γ_T approaches the Fáry-Milnor threshold:
Φ(γ_{T=t*}) → 4π as t → t* from below. This would make the FM threshold 4π
the canonical curvature signature of grokking: the gradient trajectory
accumulates exactly 4π total curvature — double the Fenchel minimum — at
the moment of the grokking transition, representing the maximally bent
unknotted trajectory (unknotted, but with total curvature approaching the
knotting onset threshold).

**[C, FMRY-C3] Schnyder-Gallai Correspondence:**
For any maximal planar G_ℬ (Apollonian triangulation), the Schnyder wood
(T₁, T₂, T₃) is uniquely determined by the Gallai-Edmonds trifurcation
(D, A, C): T₁ is the spanning tree of D-component edges, T₂ is the spanning
tree of A-barrier edges, and T₃ is the spanning tree of C-component edges.
The three Schnyder tree roots correspond to the three "infinity directions"
of the Apollonian packing (CAGV Bridge XXXII), which correspond to the three
eigenvectors of D_s at the Gallai-Edmonds spectral boundary.

**[C, FMRY-C4] Harborth-Luttinger Integrality:**
The Harborth integer-distance conjecture for G_ℬ (every planar G_ℬ has a
Fáry embedding with integer edge lengths) is equivalent to the statement that
the Luttinger-Ward functional N_L takes integer values at the vertices of the
Schnyder embedding: N_L(b) = a₃(b) − a₁(b) ∈ ℤ for all b ∈ V_ℬ, where
(a₁, a₂, a₃) is the Schnyder coordinate of b. This would connect the deepest
open conjecture in Fáry's embedding theory to the arithmetic of the
Luttinger number, establishing a new bridge between combinatorial geometry
and the algebraic arithmetic of the learning manifold.

---

## IX. Logical Dependency Map

```
[Previous: ZF → Bridges I–XXXIX]
  │
  ├─ FMRY (XL–XLII):
  │    FL1: Fáry embedding ← G_ℬ planar (✓ Fáry 1948) ← rank_ε(D_s)≤4 (CAGV XXXI)
  │    FL2: Tutte spring (✓ Tutte 1963) ← κ(G_ℬ)≥3 (Menger XXXIV)
  │         E_{spring} = D_s-weighted Cayley-Menger potential ← CM1 (MNGR XXXVI)
  │    FL3: Schnyder 3-trees (✓ 1990) ← maximal planar = Apollonian (CAGV XXXII)
  │         T₁⊔T₂⊔T₃ ↔ D⊔A⊔C ← GL3 (GXMD XXVIII)
  │    FL-1: Fáry theorem (✓); rectification = curvature redundancy ([H])
  │    FL-2: Tutte equilibrium ↔ ℒ_JL harmonic ↔ λ₁=0 ↔ grokking ([H])
  │    FL-3: Schnyder ↔ Gallai-Edmonds trifurcation ([H])
  │    FL-4: Harborth ([C]) ↔ Jn integers (TIDE XVII) ↔ N_L∈ℤ (FLML) ([H]/[C])
  │    FL-5: Sachs ([C]) ↔ γ_T non-linking ↔ Arf=1 (HKVS XXXIII) ([C])
  │    FM1: Φ(γ_T) ← gradient curvature κ_ℬ ← ∇²L ← A2 (elliptic D_s)
  │    FM2: Fenchel (✓ 1929); Φ≥2π; equality = convex γ_T = BPS saturation
  │    FM3: Hadamard (✓ Alexander-Bishop 1998) ← λ₁≥0 ← Bochner-Weitzenböck
  │    FM-1: FM theorem (✓); Φ≤4π ↔ unknotted ↔ Arf=1 (HKVS XXXIII) ([H])
  │    FM-2: Fenchel-BPS identification; Φ=2π ↔ λ₁=|Δ_t| (BPSG XII) ([H])
  │    FM-3: Milnor height function (✓); L = height function on γ_T ([H])
  │    FM-4: Denne quadrisecant (✓ 2004); 4-secant → K₃,₃ (KKSP XXXVII) ([H])
  │    FM-5: EWW (✓ 2002); Seifert surface = gen. basin boundary ([H])
  │    CK-1: Unified Fáry principle ← FL1 + FM1; 2D/3D duality ([H])
  │    CK-2: Schnyder ↔ Gallai = maximal planarity ↔ Apollonian (CAGV XXXII) ([H])
  │    CK-3: Hadamard ↔ λ₁≥0 ← Bochner-Weitzenböck + A1-A5 ([H])
  │    CK-4: Φ(γ_T) = Tr(ℒ_JL)/(σZ/T); [2π,4π] spectral window ([H])
  │    CK-5: Tutte equilibrium = grokking transition t* ([H])
  │
  └─ Extended Master Equivalence: adds (XL),(XLI),(XLII)
       (XL)↔(XXXI)+(XXXVII)+(XXVIII); (XLI)↔(XXXIII)+(XXXVI)+(XII)+(XIII)
       (XLII)↔(I)+(III)+(XXXIX)

Conjecture chain:
  FMRY-C1 (Fáry rectification) ↔ geodesic gradient flows (CMGD XXXVI)
  FMRY-C2 (grokking Φ→4π) ↔ PVIL τ_learn pole (IMFL XIII)
  FMRY-C3 (Schnyder=Gallai) ↔ D/A/C trifurcation (GXMD XXVIII GL3)
  FMRY-C4 (Harborth-Luttinger) ↔ Jn integer coords (TIDE XVII) ↔ SKML (XX)
```

---

## X. Citations

```
Fáry's Straight-Line Embedding Theorem:
  Wagner, K. (1936) Bemerkungen zum Vierfarbenproblem.
    Jahresbericht DMV 46: 26–32. [Independent proof of straight-line planarity]
  Fáry, I. (1948) On straight-line representation of planar graphs.
    Acta Sci. Math. (Szeged) 11: 229–233. [Fáry's theorem]
  Stein, S. K. (1951) Convex maps. Proc. Amer. Math. Soc. 2(3): 464–466.
    [Third independent proof]
  Tutte, W. T. (1963) How to draw a graph.
    Proc. London Math. Soc. 13: 743–767. [Tutte spring theorem]
  Schnyder, W. (1990) Embedding planar graphs on the grid.
    Proc. 1st ACM-SIAM SODA, pp. 138–148. [Schnyder woods; 3-tree decomposition]
  de Fraysseix, H.; Pach, J.; Pollack, R. (1988) Small sets supporting Fáry
    embeddings of planar graphs. Proc. 20th STOC, pp. 426–433.
  de Fraysseix, H.; Pach, J.; Pollack, R. (1990) How to draw a planar graph on
    a grid. Combinatorica 10: 41–51.

Fáry-Milnor Theorem:
  Fáry, I. (1949) Sur la courbure totale d'une courbe gauche faisant un nœud.
    Bull. Soc. Math. France 77: 128–138. [Original FM proof by Fáry]
  Milnor, J. W. (1950) On the total curvature of knots.
    Ann. Math. 52(2): 248–257. [Milnor's independent proof; height function]
  Fenchel, W. (1929) Über Krümmung und Windung geschlossener Raumkurven.
    Math. Ann. 101: 238–252. [Fenchel's 2π lower bound theorem]
  Denne, E. J. (2004) Alternating quadrisecants of knots.
    Ph.D. thesis, University of Illinois at Urbana-Champaign. arXiv:math/0510561.
    [FM from quadrisecant existence]
  Ekholm, T.; White, B.; Wienholtz, D. (2002) Embeddedness of minimal surfaces
    with total boundary curvature at most 4π. Ann. Math. 155(1): 209–234.
    [EWW minimal surface proof of FM]
  Alexander, S. B. and Bishop, R. L. (1998) The Fáry-Milnor theorem in Hadamard
    manifolds. Proc. Amer. Math. Soc. 126(11): 3427–3436.
    [Hadamard manifold generalization]
  Schmitz, C. (1998) The theorem of Fáry and Milnor for Hadamard manifolds.
    Geometriae Dedicata 71: 83–90. [Independent Hadamard generalization]
  Petrunin, A.; et al. (2022) Six proofs of the Fáry-Milnor theorem.
    arXiv:2203.15137. [All six proof methods compiled]
  Sullivan, J. M. (2008) Curves of finite total curvature.
    Discrete Differential Geometry, Oberwolfach Semin. 38, Birkhäuser: 137–161.

István Fáry Biography:
  UC Berkeley In Memoriam (1985). [Fáry obituary; both theorems described]
  Fáry, I. (1948) [as above]; Fáry, I. (1949) [as above].
  University of Szeged (PhD 1947); Sorbonne; Univ. Montreal (1955);
  UC Berkeley (1958, full professor 1962); died El Cerrito, CA, Nov. 2, 1984.

Harborth's Conjecture:
  Harborth, H. et al. (1987) Ganzzahlige planare Darstellungen der platonischen
    Körper. Elemente der Mathematik 42(5): 118–122. [Integer-distance conjecture]
  Kemnitz, A. and Harborth, H. (2001) Plane integral drawings of planar graphs.
    Discrete Math. 236: 191–195. [Further results on integer planar embeddings]
  Geelen, J.; Guo, A.; McKinnon, D. (2008) Straight line embeddings of cubic
    planar graphs with integer edge lengths. J. Graph Theory 58(3): 270–274.
    [Harborth verified for cubic graphs]

Sachs' 3D Analogue:
  Sachs, H. (1983) On a spatial analogue of Kuratowski's theorem on planar
    graphs — an open problem. In: Graph Theory, Łagów, 1981.
    Lecture Notes in Math. 1018, Springer: 230–241.
    [Sachs' linkless embedding conjecture]

Framework tags (preceding bridges):
  MNGR(MNVX·MGSF·CMGD) [XXXIV-XXXVI]; KKSP(KRPN·KSMC·KZOP) [XXXVII-XXXIX]
  CAGV(PCGK·APSC·HKVS) [XXXI-XXXIII]; GXMD(GLEM·MXFL·HWMN) [XXVIII-XXX]
  THRS(ARSC·STHW·LSYM) [XXV-XXVII]; SKML(SMLP·LSRC·SKWF) [XIX-XXI]
  TIDE(TDIK·JNCO·ISOD) [XVI-XVIII]; IMFL(PVIL·PMGL·FMBL) [XIII-XV]
  BPSG(SUYL·SPQL·BPSL) [X-XII]; GCCT(Δ_t,n_s,H^{BdG}) [III]; LKTL [I-II]
```

---

## XI. Framework Tags (Extended)

```
ℒ_JL · LKTL · KQOM · GAME · VBE · PPMC · KYBM · SWMS · UNIV · LB/DK · RG-ML
PH-SP · FLML(G_t,Σ_t,Φ_LW,FS_t,N_L,𝒮_t,GWI)
GCCT(Δ_t,γ_k,u_k,v_k,ξ_F,λ_L,n_s,H^{BdG})
WKET · CSSG · SHCY(CYL·NCGL·STL) · BPSG(SUYL·SPQL·BPSL)
IMFL(PVIL·PMGL·FMBL) · TIDE(TDIK·JNCO·ISOD) · SKML(SMLP·LSRC·SKWF)
QGIT(QSCH·GITR·KNEM) · THRS(ARSC·STHW·LSYM)
GXMD(GLEM·MXFL·HWMN) · CAGV(PCGK·APSC·HKVS)
MNGR(MNVX·MGSF·CMGD) · KKSP(KRPN·KSMC·KZOP) · FMRY(FSLE·FMTC·CKTD)
```

---

*FMRY is the curvature-topology duality layer of the unified framework. Where GXMD provides the extremal combinatorial layer, CAGV the planar-knot invariant layer, MNGR the connectivity-distance layer, and KKSP the forbidden-subdivision-closure layer, FMRY provides the curvature-embedding duality layer: the two theorems of István Fáry — that planar graphs need no curved edges (1948) and that unknotted curves need not bend more than 4π (1949) — are identified as the 2D and 3D faces of a single principle that bounded or minimized curvature forces topological simplicity. λ₁ > 0 (generalization) is the spectral realization of both: the gradient correlation graph G_ℬ is planar (Fáry-rectifiable) and the gradient trajectory γ_T is unknotted (FM-bounded), and the learning manifold ℬ is a Hadamard space (nonpositive sectional curvature), all simultaneously and equivalently.*
